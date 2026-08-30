# Serbian/Croatian/Bosnian Slang Mechanics — Extraction Checklist

**This is the pipeline's first test-run language — everything below is tentative until the
developer reviews it.** See `../../methodology-observations/serbian_croatian_bosnian_test_run.md`
for process findings, and `00_Book_Triage_Catalog.md` (this folder) for the source-material survey.

**Purpose:** analyze the actual mechanics of how Serbian/Croatian/Bosnian slang forms and works,
using the corpus collected in `language_corpus/Serbian_Croatian_Bosnian/` and, where useful, the
grammar/vocabulary reference in `source_reference/languages/Serbian, Croatian, Bosnian/`. Findings
here are what eventual synthesis work (deriving invented slang for the sci-fi setting) will be
grounded in.

**This is research only — nothing here is canon** until worked into actual setting material by
explicit decision.

**Status legend:** `[x]` analyzed and written into its output file · `[ ]` not yet done.

---

## Morphological typology

**Serbian/Croatian/Bosnian: fusional.** Grammatical categories (case, number, gender) are merged
into single, non-separable affixes rather than agglutinated as distinct stacked morphemes — e.g.
Lesson 1's `mòje` (neuter possessive "my") fuses possession, gender, and number into one ending,
not separable into individually-meaningful pieces the way an agglutinative language's morphology
would be. No agglutinative or polysynthetic behavior observed in the material extracted so far;
no morpheme breakdowns were needed in `established/001_lesson01_basics.md` as a result. See
`../00_Word_Concept_and_Morphological_Typology_Guide.md`. Revisit if later extraction turns up
compound-word formation or derivational chains worth decomposing.

---

## Output files — Markdown, sharded by numbered file

| Directory | File | Contents |
|---|---|---|
| `established/` | `001_lesson01_basics.md` | Lesson 1 vocabulary + grammar points, Alexander & Elias-Bursać textbook. 20 vocabulary entries, tentative. |
| `established/` | `002_lesson01_magner_vision_test.md` | Lesson 1 ("Prva lekcija") vocabulary + grammar points, Magner's *Introduction to the Croatian and Serbian Language* (1991/1998). 86 vocabulary entries. This is a **vision-reading test** — extracted from a scanned, text-layer-less PDF via direct vision reading, with an honest confidence self-assessment in its own "Vision-reading confidence notes" section. Overall confidence rated medium-high by the extracting subagent. |
| `analysis/` | *(none yet)* | Phase 3 not started — gated on `language_corpus/Serbian_Croatian_Bosnian/` reaching `in progress`. |
| `synthesized/` | *(none yet)* | Phase 5 not started. |

**No `_index.json` manifest** — this table is the human-readable index. `/graphify
datasets/Serbian_Croatian_Bosnian` (once run) provides the machine-queryable pointer/summary layer.

---

## Field/column conventions

**Usage-tier / slang-type categorization.** `established/` vocabulary tables carry a `Usage Tier`
column — see `../00_Usage_Tier_Taxonomy.md`. All 20 entries extracted so far are `core` (Lesson 1
material is definitionally basic vocabulary) — expect `technical`/`taboo`/`slang`/etc. to only
appear once Phase 2 corpus collection or later chapters (esp. the "Grammar & Social Commentary"
volume) are extracted.

**Transcription risk carries through** from `language_corpus/` sources — see
[`../../language_corpus/00_Source_Reliability_Guide.md`](../../language_corpus/00_Source_Reliability_Guide.md).
Not yet relevant here since no corpus collection has begun.

**Vision-reading risk — directly relevant to this language.** `established/002_lesson01_magner_
vision_test.md` was the project's first vision-reading test (a scanned, no-text-layer book), and
carries a real `Vision Reading Confidence` column (retrofitted `verified` throughout — see that
file's header for the retrofit note and its own "Vision-reading confidence notes" section for the
full self-assessment). See `../00_Reference_Extraction_Spec.md`'s Vision-reading guard section —
this same test found and correctly excluded a previous book owner's handwritten pencil marginalia,
confirming that guard is a real, not hypothetical, necessity.

**Historical & geographic context.** `Attested Era`/`Attested Region`/`Geographic Scope` columns —
see [`../00_Historical_and_Geographic_Context_Guide.md`](../00_Historical_and_Geographic_Context_Guide.md).
This language's first shard already exercised `Attested Region` meaningfully: the source's own
explicit `[B]`/`[C]`/`[S]` tags map directly onto it (e.g. `šta` tagged Bosnia/Serbia vs. `što`
tagged Croatia).

## Graphify

This language gets its own graph, scoped to `datasets/Serbian_Croatian_Bosnian/` (separate from
`language_corpus/Serbian_Croatian_Bosnian/`'s own graph). Not yet run — `established/` currently has
one file, likely below the threshold where graphing pays off yet.

## Mechanisms examined

- [ ] *(not started — Phase 1 reference extraction only so far, Phase 3 mechanics analysis has not
      begun; see `established/` for current progress)*

## Reference extraction progress (Phase 1)

- [x] `01.Bosnian Croatian Serbian a Textbook...` — Lesson 1 only (20 entries in
      `established/001_lesson01_basics.md`), tentative
- [ ] `01.Bosnian Croatian Serbian a Textbook...` — Lessons 2-20 not yet done
- [ ] `11.Bosnian Croatian Serbian - A grammar & Social Commentary.pdf` — not started
- [ ] `10.Serbian an essential grammar.pdf` — not started
- [x] `12.Introduction to the Croatian and Serbian language.pdf` (Magner) — Lesson 1 only (86 entries
      in `established/002_lesson01_magner_vision_test.md`), **vision-reading test** — no text layer
      in this PDF, extracted via direct vision reading of rendered page images; see that file's
      "Vision-reading confidence notes" section for a reliability self-assessment (medium-high
      confidence) before deciding whether to extend this method to the rest of the book or the
      other 5 vision-only books.
- [ ] `12.Introduction to the Croatian and Serbian language.pdf` (Magner) — Lessons 2-30 not yet done
- [ ] Remaining 5 vision-only books — deferred, see `00_Book_Triage_Catalog.md`

**Resolved methodology questions (see `../00_Reference_Extraction_Spec.md` and
`../../methodology-observations/serbian_croatian_bosnian_test_run.md`):** coverage should be
comprehensive-but-not-exhaustive (every grammar point, every distinct vocabulary item, every
regional annotation; skip repeated drills) and extraction should be subagent-parallelized, chunked
by lesson/chapter, rather than manual single-pass reading. Not yet re-executed at that scale for
this language — Lesson 1 was done manually before this decision was finalized.

## Suggested next-session order

1. Dispatch parallel subagents (per `../00_Reference_Extraction_Spec.md`) across the remaining
   lessons of the Textbook and the two other clean-text-layer books
   (`11.Bosnian Croatian Serbian - A grammar & Social Commentary.pdf`,
   `10.Serbian an essential grammar.pdf`).
2. Decide an OCR/vision-reading approach for the 6 books without a usable text layer before
   attempting to extract from them.
