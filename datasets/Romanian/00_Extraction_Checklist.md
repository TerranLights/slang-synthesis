# Romanian Slang Mechanics — Extraction Checklist

**Phase 1 (reference extraction) complete as of 2026-10-04.** Seventh language in the project to
reach this milestone, after Serbian/Croatian/Bosnian, Hungarian, Korean, Russian, Spanish, and
Dutch. 78 `established/` files, ~251,000 words, from all 5 in-scope sources identified in
`00_Book_Triage_Catalog.md` — the smallest corpus triaged so far, completed in a single continuous
push with zero usage-limit disruptions.

**Purpose:** analyze the actual mechanics of how Romanian slang forms and works, using the
corpus collected in `language_corpus/Romanian/` and, where useful, the grammar/vocabulary
reference in `source_reference/languages/Romanian/`. Findings here are what eventual synthesis
work (deriving invented slang for the sci-fi setting) will be grounded in.

**This is research only — nothing here is canon** until worked into actual setting material by
explicit decision.

**Status legend:** `[x]` analyzed and written into its output file · `[ ]` not yet done.

---

## Morphological typology

**Romanian: fusional, Romance language with a retained synthetic case system** — see
`00_Book_Triage_Catalog.md` for the preliminary profile; refine here once extraction lands with
real worked examples (nominative/accusative syncretism, genitive/dative syncretism, the postposed
definite article, the three-gender system with its unusual neuter class).

---

## Output files — Markdown, sharded by numbered file, not JSON

**Storage model.** All extracted content lives as Markdown, not hand-authored JSON — see
`../00_Reference_Extraction_Spec.md` for the full schema/conventions this project uses throughout.

| Directory | Contents | Numbering |
|---|---|---|
| `established/` | The real Romanian baseline — vocabulary/grammar tables extracted per lesson/chapter/section | `001_<label>.md`, `002_<label>.md`, ... |
| `analysis/` | Mechanics findings (Phase 3, not started) | `001_<mechanism>.md`, ... |
| `synthesized/` | Derived in-universe slang output (Phase 6, not started) | `001_<batch>.md`, ... |

Fill this table in as files are created:

| Files | Source | Contents |
|---|---|---|
| `001`–`001q` (18 files) | Colloquial Romanian (Gönczöl-Davies & Deletant, Routledge) | Full book, Introduction + all 19 units — flagship case-system coverage (nominative/accusative, genitive/dative, vocative, postposed article, `pe`-marked DOM); real slang (`cică`, `nasol`, `șmecher`, `gaiță`) |
| `002`–`002h` (8 files) | Romanian: An Essential Grammar (Gönczöl-Davies, Routledge) | Full book, 16 chapters + glossary + sampled verb appendix; explicit "(very coll.)"/"(slang)" tags, regional/taboo-avoidance annotations |
| `003`–`003n` (14 files) | Romanian grammar (academic reference) | Full book, intro through Interjection chapter; numerals as signature strength; living dialectal simple-perfect tense note |
| `004`–`004m` (13 files) | Teach Yourself Romanian | Full book, all 20 units + appendix notes; register-stratified future-tense system, colloquial numeral/demonstrative clipping |
| `005`–`005z` (26 files) | Introduction to Romanian (vision-read, DJVU) | Full book, 24 lessons (book turned out to have 24, not the 21 initially estimated) + appendices + curated glossary sample |

## Field/column conventions

Same shared conventions as every other language in this project — `Usage Tier`, `Attested Era`/
`Attested Region`/`Geographic Scope`, `Transcription Confidence`/`Vision Reading Confidence`,
morpheme breakdowns where relevant. See `../00_Reference_Extraction_Spec.md`.

## Graphify

This language gets its own graph, scoped to `datasets/Romanian/`. Not yet run — build after Wave
1/2 extraction lands. **Must `cd` into `datasets/Romanian/` first, never run graphify's Python
calls from the repo root.**

## Mechanisms examined

- [ ] *(not started — Phase 1 reference extraction only so far, Phase 3 mechanics analysis has not
      begun)*

## Reference extraction progress (Phase 1)

- [x] `01.Colloquial Romanian.pdf` (172pp, clean text) — see `established/001`–`001q`
- [x] `10.Romanian An Essential Grammar.pdf` (232pp, clean text) — see `established/002`–`002h`
- [x] `11.Romanian grammar.pdf` (183pp, clean text) — see `established/003`–`003n`
- [x] `02.Teach Yourself Romanian.pdf` (140pp, vision-read) — see `established/004`–`004m`
- [x] `03.Introduction to Romanian.djvu` (257pp, vision-read) — see `established/005`–`005z`

## Next steps

Phase 1 is done for this language. Future work starts at Phase 2 (web scraping) or Phase 3 (slang
mechanics analysis) — see `ROADMAP.md`.
