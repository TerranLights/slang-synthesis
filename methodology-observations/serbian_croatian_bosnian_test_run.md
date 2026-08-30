# Test Run: Serbian, Croatian, Bosnian — Methodology Observations

**Status: tentative throughout.** This is the pipeline's first end-to-end test run, chosen
specifically to validate the methodology (small corpus, single-nation-adjacent but three-identity
language pack) before committing to the "extraction-first, all languages, before any web research"
sequencing rule for the remaining ~40 languages. Every finding below is provisional until reviewed.

**Why this language was picked:** see conversation history — smallest reference corpus of the
three shortlisted candidates (Hungarian, Dutch, Serbian/Croatian/Bosnian) at ~264MB / 9 real files,
and it forces the pipeline to confront the "one reference folder, three national/language
identities" edge case immediately rather than later.

---

## Log

Entries added chronologically as the test run progresses. Each entry: what happened, what it
suggests about the methodology (not the language content itself).

---

### 2026-08-30 — Phase 0 triage pass

**Tooling gotcha: a shell one-liner silently corrupted the initial file inventory.** Before the real
triage pass, an earlier `find ... -exec ls -lh {} \; | awk '{print $5, $NF}'` was used to eyeball
folder contents. `awk`'s default field splitting is whitespace-based, so every multi-word filename
got truncated to its last space-separated token — `"01.Bosnian Croatian Serbian a Textbook With
Exercises and Basic Grammar.pdf"` printed as just `"Grammar.pdf"`. This gave a materially wrong
picture of the folder's actual contents (looked like a handful of generically-named files, not 9
real, identifiable, well-attributed books) until `find . -type f | sort` was used instead. **Lesson
for future triage passes on other languages: never rely on a field-splitting `awk`/shell one-liner
to summarize filenames — use `find -type f` or `ls -1` and read full names directly.**

**OCR/scan handling is the norm here, not the edge case.** Of 9 real reference files, only 3 had a
clean, usable `pdftotext` text layer (the two Alexander/Elias-Bursać volumes and the Routledge
Serbian grammar). **5 of 9 (~56%) had no usable text layer at all**, and a 6th (`Teach Yourself
Serbian.pdf`) had a text layer that *exists* but is garbled OCR-soup, unusable as plain text despite
technically not being "empty" — a third failure mode beyond the binary "has text layer / doesn't"
`ROADMAP.md` Phase 1 currently assumes. **Recommend updating `ROADMAP.md`'s OCR/scan-handling note
to explicitly name this as a common, not rare, condition, and to add "garbled/corrupted text layer"
as a distinct triage category alongside "clean text layer" and "no text layer."** If this ~56% rate
generalizes even roughly across the other ~40 languages' reference material, OCR/vision-reading
capacity is a much bigger share of total Phase 1 effort than the roadmap currently implies.

---

### 2026-08-30 — First `established/` shard populated (20 entries, Lesson 1 of the Alexander & Elias-Bursać textbook)

**`attested_region` validated strongly by real source material.** The chosen first book (*Bosnian,
Croatian, Serbian, a Textbook*) is explicitly comparative by design — it tags vocabulary and
dialogue lines with `[B]`/`[C]`/`[S]` markers throughout, e.g. `njen [B,S]` vs. `njèzin [C]` for
"her/hers," or `šta [B,S]` vs. `što [C]` for "what." This maps onto the `attested_region` schema
field almost perfectly with no interpretive work required — the source is doing the classification,
we're just transcribing it. **This is a best-case scenario, though, not necessarily representative:**
this particular book was *chosen* partly because it's a three-way comparative grammar. Other
languages won't have a source doing this labeling work for us; expect `attested_region` to be
`null` far more often once we're not extracting from a book specifically designed to mark regional
variants.

**`frequency`/`weight` fields have no real data source in a teaching grammar.** The schema treats
these as populatable fields, but a pedagogical grammar textbook only gives *lesson ordering*
("Lesson 1" implies basic/common vocabulary), not actual measured usage frequency. Left both fields
`null` for every entry in this shard rather than inferring a frequency from lesson-placement, since
that would be a guess dressed up as data — exactly the kind of false-precision the historical-context
guide already warns against for `attested_era`/`attested_region`. **Tentative conclusion: `frequency`
and `weight` will likely stay `null` for most/all grammar-reference-sourced entries, and only become
populatable once a real frequency-dictionary-type source or corpus-frequency data enters the
pipeline** (possibly not until Phase 2 web research, or a dedicated frequency-list source if one
exists for a given language). Worth deciding explicitly whether that's the intended behavior or
whether the schema needs a "pedagogical_ordering" field distinct from true frequency, so the two
aren't conflated later.

**`attested_era` is only derivable at whole-book granularity from a grammar reference**, not
per-word — a book's publication date supports "contemporary (as of the book's publication)" for
every entry drawn from it, but says nothing about how long any individual word has actually been in
use. This is coarser than the field name might imply. Not a problem for this schema (the field is
explicitly optional and `null`-tolerant), just a real limit on what a grammar-reference source can
actually tell us, worth keeping in mind when reading these entries later.

**`usage_tier` skewed entirely to `core` in this first pass** — unsurprising, since Lesson 1 of a
beginner textbook is definitionally basic/everyday vocabulary. None of `technical`, `taboo`,
`slang`, `literary`, `archaic`, etc. got exercised yet. **Expect this to remain true for most of
Phase 1** (grammar-reference extraction) — the richer usage-tier variety this schema was built for
will likely only show up once Phase 2 (web research, slang corpus collection) begins, or if we
specifically extract from the flagged-but-deferred `29.Serbian Folk Tales.pdf` (literary/archaic
register) or the still-inaccessible "Colloquial" titles once their OCR/scan issue is resolved.

**Copyright discipline held at this scale, worth watching as scale increases.** This shard's
`notes` fields include a couple of short illustrative quotes (a single sentence from the Lesson 1
dialogue) alongside paraphrased grammar explanations — no verbatim reproduction of full vocabulary
boxes or dialogue blocks. Feels consistent with the selective-quote-plus-paraphrase discipline
`ROADMAP.md` Phase 1 calls for. **Flag for later, larger extraction passes: re-confirm this
discipline holds once extraction moves faster/covers more pages per pass** — it's easy to maintain
by hand at 20 entries from 2 pages, less obviously so at the pace needed to cover 531 pages.

**The most consequential finding of this pass: manual, read-and-transcribe extraction at this
granularity does not scale to the stated plan.** Producing 20 real, well-sourced entries from
roughly 2 pages of one 531-page book took a genuinely substantial single pass. At that rate,
exhaustively extracting even this one (smallest-of-the-shortlist) language's 9 real reference
documents — let alone all ~40 languages' full reference libraries — via this same manual,
page-by-page approach is not tractable in reasonable time. **This directly bears on the "all
reference extraction must complete, for every language, before any web research begins" sequencing
rule the developer asked to defer deciding on.** Two live open questions this raises, to flag
explicitly rather than resolve unilaterally:

1. Should Phase 1 extraction per book/language be **exhaustive** (every lesson, every page) or
   **representative/sampled** (enough real entries to be genuinely useful, not full coverage)? This
   test run has been sampling so far (one lesson of one book), not attempting exhaustive coverage.
2. Should extraction work be **parallelized via subagents**, similar to how `/graphify`'s own
   Part B dispatches multiple subagents at once for semantic extraction, rather than one continuous
   manual read-through? This could substantially change the tractability math for the "extract
   everything before any web research" gate.

**Not resolving either question here — flagging both for the developer's explicit input**, since
they materially affect the scale/sequencing decision already flagged as deferred.

---

### 2026-08-30 — Storage model changed: Markdown-first, JSON shards dropped entirely

**Resolved, not just flagged.** Following developer discussion, the pipeline's storage model
changed from hand-authored JSON shards (`established/analysis/synthesized` directories of
`.json` files with `_index.json` manifests) to **Markdown-first**: numbered `.md` files (vocabulary
tables, mechanism writeups, synthesized-slang writeups) as the sole content store, with
`/graphify datasets/<Language>` providing the organized-summary/pointer layer instead of a
hand-maintained manifest. Reasoning (developer + assistant converged):

- Matches the Inner Tepenia GDD repo's own pattern (prose Markdown, not JSON) that this project's
  whole extraction methodology is modeled on.
- Subagents produce much more reliable Markdown than deeply-nested JSON with many optional fields —
  a real risk given the "subagent-parallelized extraction" method decided in the same discussion.
- Removes a genuine duplication the JSON-shard design had introduced without it being noticed: the
  checklist template already had a Markdown `## Output files` table *and* parallel JSON shards for
  the same content.
- Graphify's own node schema already carries `source_file`/`source_location` — exactly the
  "addresses pointing to where the full corpus of any particular thing is located" the developer
  asked for, with no bespoke schema needed. Numeric data (weight/frequency/etc.) lives as ordinary
  table columns in the Markdown itself rather than needing a separate JSON field.

**What changed:**
- `datasets/_TEMPLATE/{established,analysis,synthesized}/` now hold one `.md` template each
  (`001_TEMPLATE.md`) instead of `_index.json` + `001_TEMPLATE_SHARD.json`.
- New `datasets/00_Reference_Extraction_Spec.md` — the reusable Phase 1 subagent prompt (coverage
  rule, copyright discipline, Markdown table format, chunking convention), mirroring how
  `/graphify` itself has a shared `extraction-spec.md` handed to every semantic-extraction
  subagent.
- `datasets/00_Usage_Tier_Taxonomy.md` and `datasets/00_Historical_and_Geographic_Context_Guide.md`
  updated from JSON-field phrasing ("field," "null," "array") to Markdown-column phrasing
  ("column," "—" for unknown, semicolon-separated lists).
- `datasets/Serbian_Croatian_Bosnian/established/001_lesson01_basics.json` converted to
  `.md` (a real table, same 20 entries, same content — no data lost in the conversion).
- All `_index.json` files removed project-wide; none will be created going forward.

**A second, unrelated bug found and fixed while doing this conversion:** the earlier `replace_all`
edits that filled `{{Language}}` → `"Serbian/Croatian/Bosnian"` in the per-language checklist copies
had silently corrupted every file path containing the placeholder —
`` `language_corpus/{{Language}}/` `` became the literal, broken
`` `language_corpus/Serbian/Croatian/Bosnian/` `` (three extra, non-existent path segments) instead
of the real folder name `Serbian_Croatian_Bosnian`. **This went unnoticed for several turns** since
the broken paths still *looked* plausible in prose. Fixed by hand in both checklist files. **Added a
standing warning to both `_TEMPLATE/00_Extraction_Checklist.md` files**: fill `{{Language}}` with
the folder-safe name in paths, the display name in prose — don't naive-replace both from the same
value. Worth double-checking any other file touched by that same original `replace_all` pass for the
same corruption (the taxonomy/guide docs were checked during this pass and were clean — they don't
reference this language's specific paths).

---

### 2026-08-30 — Word-concept / morphological typology added as a new methodology dimension

Developer flagged, independent of the storage-model discussion above: "word" is not a stable
cross-linguistic unit (Finnish `pikkupukkikaupungissamme` = an entire English phrase in one
orthographic word). Added `datasets/00_Word_Concept_and_Morphological_Typology_Guide.md` — typology
categories (isolating/agglutinative/fusional/polysynthetic, usually mixed rather than pure), a
per-language "Morphological typology" field added to the checklist template (filled in during Phase
0, before extraction), and a morpheme-breakdown convention for `established/` vocabulary tables when
a surface word-form has real compositional structure worth decomposing.

**Applied retroactively to this test-run language:** Serbian/Croatian/Bosnian characterized as
fusional (case/gender/number fused into single non-separable endings, e.g. `mòje`) — no
agglutinative/polysynthetic behavior in the material extracted so far, so no morpheme breakdowns
were needed in the existing shard. This is a genuinely different typology than Finnish's
agglutinative case (the example that prompted this guide), which is itself a useful early
cross-language data point once a second language gets extracted.

**Also cross-referenced into the taxonomy doc:** `morphological_play` (an existing slang-derivation
type in `00_Usage_Tier_Taxonomy.md`) means something different depending on typology — rich in
agglutinative languages where morphological combination is already grammatically normal, more
marked in isolating languages. Noted in both docs so this doesn't get missed during Phase 3
analysis on a later, more morphologically complex language.

---

### 2026-08-30 — Index prerequisite rule found stale against the actual pipeline shape

`datasets/00_Analysis_Index.md`'s original prerequisite note said a language "cannot move past `not
started`... until its corpus in `language_corpus/` is at least `in progress`" — written with
`analysis/` and `synthesized/` in mind. But `established/` (the real-language grammar/vocab
baseline) is populated from `source_reference/` material during **Phase 1**, which has no
dependency on the slang corpus (**Phase 2**) at all. This test run populated a real
`established/` shard while `language_corpus/Serbian_Croatian_Bosnian/` is still completely empty —
which is correct pipeline behavior, not a rule violation, but the index's own prose didn't account
for it. **Fixed the index's wording to distinguish `established/`'s Phase-1-only dependency from
`analysis/`/`synthesized/`'s genuine Phase-2 dependency**, same commit as this observation. Worth
double-checking during review whether this distinction should also be reflected more explicitly in
the per-language checklist template, not just the master index.
