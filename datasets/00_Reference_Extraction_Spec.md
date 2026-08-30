# Reference-Book Extraction Spec

**Purpose.** The reusable subagent prompt for Phase 1 (grammar/vocabulary reference extraction from
`source_reference/`). Every extraction subagent gets this verbatim, the same way `/graphify`'s own
`extraction-spec.md` is handed to every semantic-extraction subagent — so results stay consistent
regardless of which subagent, book, or language produced them. Adjust the bracketed placeholders per
dispatch; don't rewrite the rules themselves per-language.

---

## Coverage rule — comprehensive-but-not-exhaustive

A grammar textbook is mostly pedagogical padding: repeated drills, duplicate example sentences
reusing the same vocabulary in slightly different exercises. That's low information density for
this project's purposes. **Extract:**

- **Every grammar point** in the assigned chunk — there are relatively few of these per
  lesson/chapter, and they constrain how slang can even form later.
- **Every distinct vocabulary item** in the assigned chunk — not a sample, genuinely all of it.
- **Every explicit dialectal/regional/register annotation** the source itself marks (e.g. `[B]`/
  `[C]`/`[S]`-style tags, "formal" vs. "colloquial" labels, footnoted usage notes) — this is
  frequently the highest-value content in a comparative or sociolinguistically-annotated source and
  must never be skipped.

**Skip:** repeated drill exercises and example sentences that don't introduce new vocabulary or
grammar beyond what's already been captured from this same chunk.

## Copyright discipline

Reference material is copyrighted. **Selective quotes + paraphrase + analysis only.** A short
illustrative quote (a single sentence, a short phrase) is fine when it's genuinely useful evidence.
**Never bulk-reproduce a vocabulary box, dialogue block, or explanatory passage verbatim.**
Paraphrase grammar explanations in your own words; cite page numbers rather than quoting at length.

## Output format

Write to a Markdown file (path specified per dispatch) following this structure — see
`_TEMPLATE/established/001_TEMPLATE.md` for the literal template:

1. A header naming the language and the lesson/chapter/section covered, with the source citation
   (author(s), title, edition/year, page range).
2. A **Vocabulary** table with these exact columns: `Term | Gloss | Part of Speech | Usage Tier |
   Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type |
   Transcription Confidence | Vision Reading Confidence | Notes`.
3. A **Grammar points** section, one subsection per rule, paraphrased explanation with a short
   illustrative example if useful.

### Vision-reading guard: distinguish print from handwritten marginalia

**Mandatory whenever the source has no text layer and is being read visually (a scanned book).**
Confirmed as a real risk during the Serbian/Croatian/Bosnian test run: a used/scanned copy can carry
a previous owner's handwritten notes, underlines, or pencil-filled exercise answers alongside the
book's own printed content. **Before extracting anything from a vision-read page, actively check
whether it is genuinely typeset/printed source material or handwritten annotation added by a
reader.** Handwritten content — even when it looks like a plausible answer — is never source
content: it may be a student's own (possibly wrong) guess, not the book's authoritative material,
and must never be extracted as if it were.

- If a mark is clearly print (consistent typeset font, matches the surrounding printed page) —
  proceed normally.
- If a mark is clearly handwritten (pen/pencil, inconsistent with the printed typeface, sits in a
  margin or a blank/answer space) — **exclude it entirely**, and note in the file's coverage note
  that marginalia was found and excluded (don't just silently skip it — flag it, the same way the
  Magner test run did).
- If genuinely unclear which it is — **default to treating it as marginalia and exclude it**, the
  same "default to the riskier assumption when uncertain" principle already used for subtitle/
  transcript `source_type` defaulting (see `../language_corpus/00_Source_Reliability_Guide.md`).
  Missing a genuinely-printed word is a smaller loss than silently extracting a stranger's
  handwritten error as if it were the book's own content.

### Morphological composition

Before extracting, check this language's own "Morphological typology" note in its
`00_Extraction_Checklist.md`. **If the language is agglutinative, polysynthetic, or has complex
fusional forms, do not treat every surface "word" as an atomic vocabulary item.** When a word-form
is itself a composed unit (multiple morphemes each carrying distinct meaning), add a morpheme
breakdown beneath its table row — see `00_Word_Concept_and_Morphological_Typology_Guide.md` for the
format and a worked example. Simple, non-composed lexical items don't need this; use it when an
atomic gloss would hide real compositional structure the mechanics-analysis phase will need later.

### Column rules

- **Usage Tier** — one of `core`, `formal`, `colloquial`, `technical`, `regional`, `literary`,
  `archaic`, `taboo`, `slang` from `00_Usage_Tier_Taxonomy.md`, or a dot-notation subcategory
  (`technical.medical`) if the source genuinely supports a finer distinction. Most grammar-reference
  vocabulary will be `core`.
- **Weight/Frequency** — leave as `—` unless the source is a genuine frequency dictionary or
  corpus-frequency list. **A teaching grammar's lesson ordering ("this is Lesson 1 vocabulary") is
  not real frequency data** — don't infer a frequency value from pedagogical placement.
- **Attested Era** — `—` unless the source supports it. A book's own publication date can justify
  "contemporary (source published YYYY)" for everything drawn from it; this is coarse (whole-book,
  not per-word) but legitimate. See `00_Historical_and_Geographic_Context_Guide.md`.
- **Attested Region** / **Geographic Scope** — `—` unless the source explicitly marks a regional/
  dialectal variant (e.g. comparative B/C/S-style tags). Don't infer regionality from a book's own
  publisher or title.
- **Source Type** — `grammar_reference`, `dictionary`, `corpus_database`, or another type from
  `../language_corpus/00_Source_Reliability_Guide.md`. Reference books extracted here are virtually
  always `grammar_reference` or `dictionary`, never a subtitle/transcript type.
- **Transcription Confidence** — `n/a` for reference-book extraction (this field only matters for
  subtitle/transcript-sourced entries during Phase 2 corpus collection).
- **Vision Reading Confidence** — the analog of Transcription Confidence, but for entries read from
  a scanned/image-only source instead of a clean text layer. `n/a` when the source had a real text
  layer (`pdftotext` or equivalent produced usable text — no vision-reading was needed for this
  entry). When the source was vision-read, use the same three-tier scale as Transcription
  Confidence: `verified` (cross-checked — e.g. the same word also appears elsewhere on a clearly
  legible part of the page, or was independently confirmed), `plausible_unverified` (read with
  reasonable confidence but not independently cross-checked), `low_confidence` (genuine doubt about
  a specific character/word — faded print, obscured by a scan artifact like a binding-gutter shadow,
  an unusual font, or any of the marginalia-adjacent ambiguity described above). Confirmed useful
  during the Serbian/Croatian/Bosnian vision-reading test: don't just write a whole-file confidence
  note and leave every row silently uniform — flag the specific rows that actually carry more
  uncertainty than the rest, the same way Transcription Confidence already does per-entry rather
  than per-file.

## Chunking

Each subagent is assigned one lesson/chapter/section (or a bounded page range if the source has no
clean chapter structure) and writes its own numbered output file
(`established/NNN_<label>.md`). **Don't let a single file grow unbounded** — if a chunk's real
content is large, split it into multiple numbered files rather than one sprawling one, same
discipline used throughout this project's other sharded content.

## After extraction: no manual JSON manifest needed

Unlike earlier drafts of this pipeline, there is **no `_index.json` to hand-maintain**. The
checklist's own `## Output files` table is the human-readable index — update it (or have it updated)
after each dispatch. **Have the extraction subagent update it directly as part of its own task**
(the Output files table row and the relevant progress checkbox) — confirmed during the Hungarian
test run that subagents will do this reliably when explicitly instructed to, removing a manual
coordination step.

**Caution on multiple subagents writing to the same shared checklist file.** Confirmed safe with 3
parallel subagents during the Hungarian and Dutch test runs — when a subagent's own Read-then-Edit
found the file already changed by a sibling subagent, it re-read and merged rather than overwriting,
unprompted, on both occasions it was tested. **This has only been confirmed at n=3 parallel
subagents, not at higher counts.** If a future dispatch parallelizes many more chunks against one
book (e.g. a full 20+ chapter book in one pass), don't assume this self-protective behavior scales
indefinitely — consider having subagents skip the checklist update entirely and doing it as a single
serialized follow-up pass once all chunks land, rather than risking a real collision at higher
parallelism.

The machine-queryable summary/pointer layer comes from running `/graphify datasets/<Language>` once
there's enough content to be worth graphing — its `source_file`/`source_location` fields are the
"address" back to the exact Markdown table an entry came from.

**When running graphify on `established/` content specifically**, instruct its semantic-extraction
subagents *not* to create one node per vocabulary table row — a chapter's vocabulary table can have
100+ entries, and a node-per-row approach produces an unusable graph. Instead extract nodes for the
grammar concepts/mechanisms discussed, the source book itself, and only the handful of vocabulary/
morpheme-breakdown examples that are genuinely illustrative of a named concept. Confirmed during the
Hungarian test run: this produced a small, navigable, genuinely useful graph (31 nodes) with
cross-chapter hyperedges surfacing real patterns (e.g. vowel harmony as a governing mechanism across
multiple chapters) — the payoff this whole storage model was designed around. The Dutch test run
confirmed this further: graphify surfaced a genuine cross-chapter linguistic pattern (vowel length
tracking morphological form across three independently-extracted chapters) that no single extraction
subagent could have noticed alone — treat a per-language graphify run as a real analytical step, not
just bookkeeping.

**Mandatory before running any per-language `/graphify` command: `cd` into that language's own
folder first (e.g. `datasets/<Language>/`), don't run it from the repo root with a `root=` argument
alone.** Confirmed as a real, repeat-risk bug during the Hungarian test run:
`graphify.detect.save_manifest()` (and likely other graphify internals) resolve their output path
relative to the *current working directory*, not the `root=` argument passed to the Python call —
running the manifest-save step for a per-language graph from the repo root silently overwrote and
corrupted the repo-root `graphify-out/manifest.json` instead of writing to the language's own
`graphify-out/manifest.json`. **After any per-language graphify run, always `git status`/`git diff`
the repo-root `graphify-out/` directory specifically, before committing, to catch this kind of
cross-contamination** — it will not be obvious from the language folder's own output that anything
went wrong.

---

## Dispatch template (fill in per subagent)

```
You are a reference-extraction subagent for the slang-synthesis project.
Read [SOURCE FILE, PAGE RANGE] of [BOOK TITLE, AUTHOR(S), EDITION/YEAR].
Follow datasets/00_Reference_Extraction_Spec.md exactly (coverage rule, copyright discipline,
output format, column rules).
Write your output to [EXACT OUTPUT PATH] using the Write tool at that exact absolute path.
```
