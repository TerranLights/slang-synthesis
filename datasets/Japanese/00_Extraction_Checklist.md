# Japanese Slang Mechanics — Extraction Checklist

**Full Phase 1 triage complete 2026-10-13.** See `00_Book_Triage_Catalog.md` for the source-material
survey — by far the largest corpus this project has triaged (8.9GB, 619 files, ~180+ in-scope
sources after scope filtering). Unlike every prior language, the large majority of in-scope material
has no usable text layer at all (CJK script defeats OCR far more consistently than any Latin/
Cyrillic-script language handled so far), so waves are organized by content category rather than by
text-layer status.

**Purpose:** analyze the actual mechanics of how Japanese slang forms and works, using the
corpus collected in `language_corpus/Japanese/` and, where useful, the grammar/vocabulary
reference in `source_reference/languages/Japanese/`. Findings here are what eventual synthesis
work (deriving invented slang for the sci-fi setting) will be grounded in.

**This is research only — nothing here is canon** until worked into actual setting material by
explicit decision.

**Status legend:** `[x]` analyzed and written into its output file · `[ ]` not yet done.

---

## Morphological typology

**Japanese: agglutinative, with a unique multi-script writing system** — see
`00_Book_Triage_Catalog.md`'s morphological typology note for the preliminary profile (hiragana/
katakana/kanji mixed-script system, no word-boundary spacing in standard text, heavily agglutinative
verb/adjective conjugation, grammaticalized keigo honorific/politeness system). Refine here once
Wave 1/2 extraction lands with real worked examples.

---

## Output files — Markdown, sharded by numbered file, not JSON

Same storage model as every other language in this project — see `../00_Reference_Extraction_Spec.md`.

| Directory | Contents | Numbering |
|---|---|---|
| `established/` | The real Japanese baseline — vocabulary/grammar tables extracted per lesson/chapter/section | `001_<label>.md`, `002_<label>.md`, ... |
| `analysis/` | Mechanics findings (Phase 3, not started) | `001_<mechanism>.md`, ... |
| `synthesized/` | Derived in-universe slang output (Phase 6, not started) | `001_<batch>.md`, ... |

Fill this table in as files are created:

| File | Contents |
|---|---|
| *(pending Wave 1 dispatch)* | |

## Field/column conventions

Same shared conventions as every other language — `Usage Tier`, `Attested Era`/`Attested Region`/
`Geographic Scope`, `Transcription Confidence`/`Vision Reading Confidence`, morpheme breakdowns
where relevant. See `../00_Reference_Extraction_Spec.md`. **New for Japanese**: vocabulary entries
should record the writing-system form actually used (kanji/hiragana/katakana) alongside romanization
and gloss, since script choice itself carries register/semantic information in Japanese (e.g.
katakana for loanwords or emphatic/slangy effect) in a way no prior language in this project has
needed to track.

## Graphify

This language gets its own graph, scoped to `datasets/Japanese/`. Not yet run — build after waves
land, likely in stages given the corpus's unprecedented scale (may need multiple incremental
`--update` runs rather than one single full build, given graphify's own 2,000,000-word/500-file
size-warning threshold could plausibly be approached by this language alone). **Must `cd` into
`datasets/Japanese/` first, never run graphify's Python calls from the repo root.**

## Mechanisms examined

- [ ] *(not started — Phase 1 reference extraction only so far, Phase 3 mechanics analysis has not
      begun)*

## Reference extraction progress (Phase 1)

- [x] Wave 1 — Writing System foundation (27 source files → 61 `established/` files,
      ~277,000 words). Full extraction for compact/lesson-structured sources; representative
      sampling for oversized kanji-dictionary-style references, per this project's standing
      practice. See commit history for the full per-source breakdown.
- [ ] Wave 2 — Grammar, Workbooks, Usage (42 files)
- [ ] Wave 3 — Audio Courses, Textbooks (~65 files)
- [ ] Wave 4 — Vocabulary/Dictionaries (~25 files, incl. 2 oversized-dictionary samples)
- [ ] Wave 5 — Children's Books, Readers (tiered: 4 full readers + ~4 sampled picture books)
- [ ] Wave 6 — Society/Culture gems + remaining course material (~10 files)
