# Romanian Slang Mechanics — Extraction Checklist

**Full Phase 1 push started 2026-10-04.** See `00_Book_Triage_Catalog.md` for the source-material
survey (5 real files, 54MB — the smallest corpus triaged so far).

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

| File | Contents |
|---|---|
| *(pending Wave 1/2 dispatch)* | |

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

- [ ] `01.Colloquial Romanian.pdf` (172pp, clean text)
- [ ] `10.Romanian An Essential Grammar.pdf` (232pp, clean text)
- [ ] `11.Romanian grammar.pdf` (183pp, clean text)
- [ ] `02.Teach Yourself Romanian.pdf` (140pp, vision-read)
- [ ] `03.Introduction to Romanian.djvu` (257pp, vision-read)
