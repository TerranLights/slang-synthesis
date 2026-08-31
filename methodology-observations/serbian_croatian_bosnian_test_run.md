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

### 2026-08-30 — Vision-based extraction test: works well, one real new risk found

**Setup.** Chose `12.Introduction to the Croatian and Serbian language.pdf` (Magner, Revised
Edition, 1991/1998) — a scanned, no-text-layer book — specifically to test vision-based extraction
before it's used at scale (~half of every language's reference PDFs are expected to need this, per
the OCR-rate finding above and the Hungarian run). Dispatched one subagent on Lesson 1 (PDF pages
7-12, printed pp. 1-6), explicitly instructed to add a self-assessed "Vision-reading confidence
notes" section — an analog to `transcription_confidence` for audio/subtitle sources, but for the
image-reading case.

**Independently verified for accuracy, not just plausibility-checked.** Before dispatching, read the
same pages directly (this coordinating session is itself multimodal) and recorded the vocabulary
list as independent ground truth. **Every vocabulary item and every `(Cr.)`/`(S.)` dialect tag in
the subagent's output matched exactly** — `dévojka`=Serbia/`djévojka`=Croatia, `kò`=Serbia/`tkò`=
Croatia, `jèst`=Croatia/`jèste`=Serbia, `lép`=Serbia/`lijèp`=Croatia, `vèžba`=Serbia/`vjèžba`=
Croatia, all correct. No discrepancies found. This is a real accuracy check, not just an internal-
consistency check — vision-based extraction produced output that matches independent human (well,
independent-model) reading of the same source.

**A genuinely new risk found, not anticipated by the extraction spec: distinguishing print from
handwritten marginalia.** One page spread in this specific scanned copy has a previous owner's
handwritten pencil answers filled into blank exercise spaces. The subagent correctly identified
these as reader annotations and excluded them from extraction — but this is exactly the kind of
failure mode a less careful vision-reading pass could get wrong (misattributing a stranger's
handwritten guess as the textbook's own printed content, silently corrupting the vocabulary data
with someone else's possibly-wrong homework answer). **This risk is specific to physical scanned
books (used copies can carry marginalia) and has no analog in the clean-text-layer extractions done
so far.** Worth adding explicit "distinguish source content from reader annotation" guidance to
`00_Reference_Extraction_Spec.md` for any vision-reading dispatch.

**Other honestly-flagged uncertainty, exactly as intended by the confidence-notes request:**
- A binding/gutter shadow (common in book scans) partially obscured a few characters near page
  centers — the subagent correctly noted where it had to infer a word's correct form from a cleaner
  occurrence elsewhere on the page rather than the obscured instance itself, rather than guessing
  silently.
- Fine-grained pitch-accent diacritic subtyping (grave vs. acute vs. circumflex-like marks,
  distinguishing among Cr&S's four accent categories) was flagged as lower-confidence than the
  vocabulary/gloss content itself — an honest, well-calibrated distinction between "I'm confident
  about the word" and "I'm less confident about this one fine phonological detail of it."
- Self-reported overall confidence: **medium-high**, with a specific, reasoned basis (clean typeset
  print, not degraded/faded — the gutter shadow was the only recurring obstacle) rather than a bare
  unqualified rating.

**Verdict: vision-based extraction is viable and worth using at scale**, with two concrete process
additions worth making before scaling it up: (1) add the marginalia-vs-print distinction to the
extraction spec, (2) consider whether a `Vision Reading Confidence` column (parallel to
`Transcription Confidence`) belongs in the standard `established/` table schema for any entry
sourced from a scanned/vision-read book, the same way subtitle/transcript entries carry that
column today — this test run's ad hoc "confidence notes section at the end" approach worked, but a
per-row column would let a low-confidence *specific entry* be flagged precisely rather than only a
whole-file confidence note covering everything uniformly.

**Both formalized, same day, after developer sign-off.** `datasets/00_Reference_Extraction_Spec.md`
now has a dedicated "Vision-reading guard: distinguish print from handwritten marginalia" section
(mandatory for any no-text-layer source: check whether content is genuinely typeset vs. a reader's
handwriting, exclude the latter entirely, default to excluding when genuinely unclear) and a
`Vision Reading Confidence` column rule (same three-tier scale as `Transcription Confidence`:
`verified`/`plausible_unverified`/`low_confidence`, or `n/a` for text-layer sources). Retrofitted
onto every existing `established/` table project-wide (this language's two files, all of Hungarian's
three) via a script that inserts the new column before `Notes`, defaulting to `n/a` for text-layer
sources and `verified` for `002_lesson01_magner_vision_test.md`'s rows specifically (matching that
file's own already-recorded medium-high confidence and this session's independent accuracy check —
no single row was found to warrant a lower rating). Both `_TEMPLATE/established/001_TEMPLATE.md`
and `_TEMPLATE/analysis/001_TEMPLATE.md` updated so every future language starts with the column
already in place, not needing its own retrofit.

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

---

### 2026-08-30 — Bridge-scale test: one full book, full-language-folder-scale readiness verdict

**Purpose of this run.** After three prior test runs each covered a single lesson/chapter-sized
slice (~20-300 entries), the developer asked directly whether the pipeline was ready for full,
complete extraction of an entire language folder. Honest assessment at the time: not yet confirmed
— every validated data point so far was small-scale. The developer's proposed bridge: extract one
complete, very large book (not a whole language folder, not a single lesson) as an intermediate
scale test. Recommended and confirmed: Alexander & Elias-Bursać's *Bosnian, Croatian, Serbian, a
Textbook* (531 pages) — this project's flagship SCB source, clean text layer, 20 lessons + 9
appendices + a full bilingual glossary, large enough to actually stress the pipeline's untested
edges (parallelism at real scale, checklist-write concurrency beyond n=3, sustained subagent
dispatch across dozens of chunks) without yet committing to all 40+ languages.

**Scale achieved.** 32 output files in `established/`, ~338,000 words, ~8,452 vocabulary-table rows,
covering the entire book: all 20 lessons, Appendices 1-6/9/7-8, and the full 5-part BCS-English
glossary (~4,172 glossary entries alone). Compare to the Hungarian run's 3-chunk/~350-entry test —
this run dispatched **28 extraction chunks** (roughly 9x the prior largest run) in a single language.

**Finding 1 — a real hard system limit: 20 concurrent subagents.** Dispatching wave 2 (8 chunks at
once, on top of wave 1's already-running chunks) hit a genuine ceiling: 6-7 of 8 `Agent` calls were
flatly rejected with "Concurrent subagent limit reached. You can run 20 subagents at once. Do not
retry." This is the first time this project's work has actually hit a hard platform limit rather
than a soft best-practice concern. **Resolved by waiting for in-flight chunks to complete (freeing
slots) and retrying the remaining wave-2 chunks in smaller batches** (4, then more, as slots freed),
paced with periodic `find`-based disk-state checks plus `ScheduleWakeup` between retries rather than
busy-polling. **This is now a confirmed, load-bearing planning constraint for the full 40+-language
rollout**: any dispatch plan involving more than ~15-18 chunks at once needs an explicit wave/retry
strategy, not a single flat `Agent` burst.

**Finding 2 — serialized checklist updates, chosen proactively, worked cleanly at this scale.**
The Dutch run's own finding (n=3 concurrent checklist writers self-protected, but "not a guarantee"
at higher parallelism) was treated as a real caution here, not just a historical note: at 28
concurrent-ish chunks, no subagent was told to touch the shared `00_Extraction_Checklist.md` at all.
A single manual pass compiled the full Output files table and Reference extraction progress
checkboxes after all chunks landed. **Zero checklist corruption, zero lost updates** — confirms the
serialized-update mitigation (already promoted into `00_Reference_Extraction_Spec.md` after the
Dutch run) is the right call once parallelism exceeds single digits, not just a theoretical
recommendation.

**Finding 3 — check-first duplicate-prevention validated in production, twice.** Every dispatch was
instructed to check whether its target output file already existed with substantive content and
stop if so, specifically to protect against retry-driven duplicate dispatch during the wave-based
concurrency-limit workaround. This was actually exercised: **glossary part 4** (`029_glossary_bcs_
english_part4.md`) was dispatched twice — a long-running original wave-2 attempt eventually
succeeded in the background well after the hard-rejection was understood, and a later explicit retry
of the same chunk was also issued. The second dispatch correctly detected the file already existed
with ~800 substantive entries and stopped without overwriting. **Glossary part 5** (`030_glossary_
bcs_english_part5.md`) hit the same double-dispatch scenario via a closer race; the second dispatch
did write content, but manual verification (`wc -l`/`head`/`tail` against the file) confirmed the
final file is coherent, complete, and not corrupted — no interleaved or truncated output. **Verdict:
the check-first pattern is a real, working safety net for exactly the kind of retry-driven duplicate
dispatch this bridge test's own concurrency-limit workaround created** — worth keeping as a standing
instruction in the extraction spec for any future high-parallelism run, not just this one.

**Finding 4 — two distinct PDF-extraction bugs, both self-corrected by subagents without
intervention.** (a) Lesson 5's subagent initially had `pdftotext -layout` scramble a two-column
vocabulary box, swapping "pet"/"fifth" and "peti, peto, peta"/"five" — caught and corrected by the
subagent itself via cross-reference to a numeral chart elsewhere on the same page, flagged in Notes.
(b) The glossary's two-column dictionary layout (parts 3, 4, 5) triggered a related but distinct bug:
`pdftotext -layout` interleaved left/right column text onto shared lines, corrupting alphabetical
order — fixed by switching to per-column bounding-box extraction (`-x`/`-W` flags or left/right
crops) instead of a single `-layout` pass. Glossary part 2 additionally showed artifacts from a
third-party "Advanced PDF Repair" tool's own prior processing, caught via raw-vs-layout
cross-checking. **All three fixes were subagent-initiated, not developer-flagged** — worth recording
as a growing catalog of concrete two-column/multi-column PDF gotchas future language extractions
should watch for from the start, not rediscover independently each time.

**Finding 5 — source errata flagged, never silently "corrected."** Lesson 15's subagent found what
looked like a reversed `[B]`/`[C]` dialect tag on `tko`/`ko` (inconsistent with the pattern
established elsewhere in the book) — rather than normalizing it to match the expected pattern, it
verified against the actual rendered page image and recorded the anomaly faithfully with an explicit
flag (`tko_ko_editorial_dialect_tag_anomaly`, later confirmed as a genuine graph node). This is the
behavior this project's copyright/fidelity discipline is meant to produce, and it held under real
pressure to "fix" an apparent inconsistency.

**Finding 6 — the most significant single content finding: syllable-switching slang formation.**
Appendices 7-8's subagent, extracting vocabulary from two copyrighted short stories, surfaced a
footnoted slang-formation mechanism: syllables within a word get reordered/switched to form new slang
terms — `vozdra` < `zdravo` ("hello"), `žemka` < `kažem` ("I say") — with explicit regional (Sarajevo/
Zagreb) and historical (1960s Zagreb) attestation in the source. This is exactly the kind of
real-world slang-mechanics data point the entire project exists to accumulate, and it came from
literary-appendix vocabulary extraction, not a dictionary or a "colloquial" chapter — a data point
worth remembering when triaging future languages' literary/reading-comprehension sections. Graphify
gave it its own well-developed concept node and made it the anchor of a hyperedge tying together the
run's first taboo entry, an archaic pair, and the Montenegrin-regional-variant cluster — the graph
correctly recognized it as a structural hub for this run's usage-tier diversity, not an isolated
curiosity.

**Finding 7 — new usage-tier and taxonomy territory, all first-appearances in this project.**
Lesson 19 (an epic-poetry lesson) produced this project's **first `archaic` and `regional`
usage-tier entries** — Montenegrin-dialect forms explicitly glossed by the source in context (`vakat`/
`zeman`/`putalj`, Ottoman-Turkism epic-register vocabulary). The glossary (parts 1 and 5) produced
this project's **first `taboo` entries** (`gòvno`, explicitly marked "vulg." in the source) and
**first `literary` tier** usage, plus the **first dot-notation subcategory use anywhere in the
project**: `technical.grammar`/`technical.linguistics` on glossary entries that are themselves
grammatical/linguistic terminology. Confirms the taxonomy's dot-notation extensibility (designed but
previously untested on real data) works as intended the first time real data called for it.

**Finding 8 — explicit source-labeled slang, twice.** Lesson 7 flags a phrase as "Amusing slang
usage" in its own text (`Ma moj!`, an ungrammatical retort to `Ma nemoj!`) — the first time a source
in this project has self-labeled something as slang rather than requiring inference from register
cues. Lesson 9 similarly surfaces explicit Belgrade slang (`kèva` "Mom") and teen slang (`stara`/
`stari`/`starci`), alongside genuine regional variation in ordinary family-term vocabulary across
four cities/regions in the same lesson.

**Finding 9 — a subagent split its own output file unprompted, correctly.** Lesson 16's dispatch grew
large enough (letters from three different correspondents, each a distinct register/vocabulary set)
that its subagent split into three files (`018_lesson16.md` + `_vocab2.md` + `_vocab3.md`) on its own
initiative, without being told to, correctly following the spirit of the "don't let output files grow
unbounded" guidance even though no explicit split threshold was given. Worth treating as a working,
generalizable behavior rather than a one-off — future dispatch prompts don't need to hand-specify
a file-size split point.

**Finding 10 — graphify held up at ~9x the largest prior per-language scale**, including a real
two-subagent semantic-extraction split (17 files each) — the first time this project's graphify
integration has itself been chunked across multiple parallel dispatches rather than a single pass.
Result: 136 nodes, 206 edges, 10 communities, clean health (one collapsed edge — two independent
subagents both noted the same real cross-file relationship between Lesson 2 and Lesson 4's B/C/S
dialect tagging, collapsed to one edge on graph build; benign, not corruption). The `[B]/[C]/[S]`
dialect-tagging convention emerged as the single highest-degree god node (20 edges) — a strong signal
that node-collapsing discipline (extracting recurring *concepts*, not one node per vocabulary row)
continues to scale correctly even at 8x the content volume tested previously. A genuine hyperedge
("Usage-tier diversity across sources: slang mechanism, taboo entry, archaic register, Montenegrin
regional variant") ties together findings 6 and 7 above as a single structural pattern — another
example, following the Dutch run's precedent, of graphify surfacing a cross-cutting pattern no single
extraction subagent could have seen alone.

**Overall verdict: the methodology is validated for full-language-folder-scale extraction**, with
one firm operational caveat. Every mechanism this run stress-tested — parallel dispatch, the shared
extraction spec producing consistent output across 28 independent subagents, check-first
duplicate-safety, serialized shared-file updates, self-correcting PDF-extraction-bug handling, and
graphify's node-collapsing discipline — held at ~9x the previous largest scale with zero data loss
and zero corruption. The one real constraint discovered is **the 20-concurrent-subagent platform
ceiling**, which is a planning/pacing concern (wave-based dispatch with retry logic), not a
methodology flaw — it doesn't block full-language-scale extraction, it just means a single language's
full extraction (let alone dispatching multiple languages in parallel) needs to be planned in waves
rather than assumed to fire as one uncapped burst. **Recommendation: proceed to full-language-folder
extraction**, budgeting for wave-based dispatch on any language whose full extraction plan exceeds
~15-18 concurrent chunks, and continuing the check-first + serialized-checklist safety patterns as
standing practice rather than optional caution. As with every test run, all findings above remain
tentative pending developer review before being treated as settled process.

---

### 2026-08-30 — Full-language-folder extraction: two more complete books, all clean-text-layer sources done

Following the bridge test's positive verdict, the developer greenlit full-language extraction for
this language and asked which language to continue with — this one, being the smallest and most
tractable corpus (9 real reference documents vs. Hungarian's 131 or Dutch's 84), with a validated
methodology and infrastructure already in place. Extracted the two remaining clean-text-layer books
in full: Alexander's companion *Grammar: With Sociolinguistic Commentary* (15 files, ~990 rows,
~67,000 words) and Hammond's *Serbian: An Essential Grammar* (13 files, ~780 rows, ~52,000 words).
**All 3 of this language's clean-text-layer books are now fully extracted** — 60 `established/`
files, ~10,220 rows, ~457,000 words total. Only the 5 remaining vision-only/garbled-OCR books stand
between this language and complete Phase 1 coverage.

**A new, reusable extraction pattern: "non-redundant supplement" dispatch.** Both books substantially
overlap with already-extracted grammar content (the same core word classes taught by every reference
grammar). Rather than re-extracting duplicate ground or skipping overlapping chapters wholesale,
every dispatch for an overlapping chapter was instructed to check prior `established/` files first
and extract *only* genuinely new/deeper material — full paradigm tables not assembled elsewhere,
finer-grained rules, or a different author's independent examples. This worked cleanly across both
books: several chunks came back with near-empty vocabulary tables (correctly recognizing near-total
overlap, e.g. Hammond's Ch.6 §6.1-6.9 kept only 1 new row) while others found real, substantial gaps
even in "already covered" territory (e.g. Alexander's Ch.10-12 chunk found the Type A/B/C consonant-
softening system that a later chapter had already cited as "presented earlier" but no file had
actually captured; Hammond's Ch.7 declension chunk fully tabulated the archaic *mati*/*kći* paradigms
that prior files had only named). **Recommend promoting this pattern into the extraction spec**:
when a third-plus source covers the same grammar territory, dispatch as "extract only what's new,
state what you skipped and why" rather than either full re-extraction or wholesale chapter-skipping.

**A new PDF gotcha, independently confirmed by multiple subagents: a decodable font-substitution
cipher.** Hammond's book renders Cyrillic (and in some subsections, Latin diacritics) as unrelated
glyphs under `pdftotext` — but unlike garbled OCR, this is a *fixed, consistent* character-level
substitution, not random corruption: one subagent extracting Chapters 12-13 actually cracked the
mapping (š→e, č→a, ć→z, ž→f, đ→]) by cross-referencing garbled forms against known Serbian
vocabulary. Four different subagents independently encountered and correctly handled this same
issue across different chapters — either falling back to the book's own clean parallel Latin-script
column (the safe default) or decoding specific forms with explicit confidence flagging. Distinct
from the three previously-catalogued PDF gotchas (column-scrambling, two-column interleaving,
third-party-repair-tool artifacts) — worth checking for on any future source whose Cyrillic renders
as unrelated glyph soup despite having a genuine text layer.

**Genuinely new content highlights:**
- Alexander's Sociolinguistic Commentary (Ch. 21-26) delivered exactly the register/dialect data
  hoped for — Chapter 22 alone gave two source-curated, explicitly-labeled regional lexical tables
  plus the author's own argument that vocabulary (not alphabet/pronunciation/grammar) is the real
  B/C/S differentiator, and Chapter 25 substantially deepened the existing Montenegrin finding with
  real scholarly nuance (the Nikčević orthography movement's claimed distinguishing features are
  actually shared East Herzegovinian dialect features, per the source's own verdict).
- Alexander's Chapter 18 (word formation) flagged diminutive and agentive suffixes as the productive,
  affect-loaded derivational categories — directly relevant to future Phase 3/5 slang-mechanics work.
- Hammond's Chapter 2 (Dialects) delivered clean, source-tagged Attested Region data via the
  kajkavski/čakavski/štokavski split, independent confirmation of a phenomenon Alexander's book also
  covers from a different author's perspective.
- Hammond's Chapter 17 particles chapter carries the source's own explicit "sarcastic/humorous
  overtones" annotation on `li`/`ne bi li` — a genuine informal-register signal found via the
  register-prioritization principle, in a chapter type (particles/exclamations) not previously
  tested for this.
- Hammond's noun-type chapter surfaced directly slang-relevant vocabulary (`narkoman`, `siledžija`,
  `kravetina`, `mangup`) while covering ordinary derivational-suffix grammar — a reminder that
  slang-adjacent vocabulary can turn up incidentally in grammar-illustration examples, not just in
  dictionaries or colloquial-labeled chapters.

**Graph scaling confirmed clean.** Rebuilt twice this session (once after each book), growing from
136→219→241 nodes across 34→49→62 files with consistently healthy diagnostics (one benign collapsed
edge each time — never dangling/missing endpoints) and zero repo-root cross-contamination. The
node-collapsing discipline continues to hold at nearly double the bridge-test's original scale.

**Status: all clean-text-layer Phase 1 material for this language is done.** What remains is
entirely vision-reading work (5 books) — a genuinely different cost/effort profile than what's been
tested so far. Everything above remains tentative pending developer review, same as every prior
entry in this log.
