# Slang Mechanics Analysis Index

**Purpose.** Tracks, per real-world language, whether its collected slang corpus has been
analyzed for the *mechanics* of how the slang actually forms and works — semantic shift,
phonological reduction/clipping, borrowing/code-switching, taboo inversion, metaphor productivity,
morphological play, register-marking, etc. — and where that analysis lives. This is the second
stage of the pipeline (see the repo `README.md`), downstream of `language_corpus/`.

**Status legend:**
- `not started` — no analysis has begun (may also mean corpus collection itself hasn't finished —
  check `language_corpus/00_Corpus_Collection_Index.md` first)
- `in progress` — partially analyzed, see the language's own `00_Extraction_Checklist.md`
- `complete` — mechanics analysis finished and ready to inform synthesis work

**Folder convention.** Each language in progress or complete gets its own folder here:
`datasets/<Language>/`, containing a `00_Extraction_Checklist.md` (tracks which mechanisms have
been examined, which corpus entries they were drawn from, what's still unexamined) plus numbered
output files (`01_...md`, `02_...md`, ...) holding the actual mechanics writeups — one per
mechanism or per coherent finding, in the same narrative style as the extraction files elsewhere
in this project family (quote real examples, name the actual linguistic phenomenon, don't invent
terminology that already exists). Copy `_TEMPLATE/` to start a new language.

**Prerequisite column — refined during the first test run (2026-08-30), see
`methodology-observations/serbian_croatian_bosnian_test_run.md`.** The `analysis/` and
`synthesized/` shards genuinely need `language_corpus/` to be at least `in progress` first. **The
`established/` shard does not** — it's populated from `source_reference/` grammar/vocabulary
material (Phase 1), which has no dependency on the slang corpus (Phase 2) at all. In practice this
means a language's `datasets/<Language>/` folder can show real progress (an `established/` shard)
before its `language_corpus/<Language>/` folder has anything in it — this is expected, not a
violation of the sequencing rule, as long as `analysis/`/`synthesized/` stay empty until the corpus
catches up.

**Scaling.** Content (`established/`, `analysis/`, `synthesized/`) lives as sharded Markdown files,
not JSON and not single monolithic files — see the per-language `00_Extraction_Checklist.md` and
`00_Reference_Extraction_Spec.md` for the numbering/chunking convention. Each language also gets its
**own** `graphify-out/` scoped to `datasets/<Language>/`, never one repo-wide graph — this is the
organized-summary/pointer layer over the Markdown content, not a separately hand-authored one. If a
single language's own graph outgrows graphify's size warnings, narrow further by graphing
`established/`, `analysis/`, and `synthesized/` separately.

---

## Status by language

| Language | Corpus status (see language_corpus index) | Analysis status | Folder |
|---|---|---|---|
| Serbian/Croatian/Bosnian | not started *(test-run language)* | not started — `established/` has 60 Markdown files (Phase 1, all 3 clean-text-layer reference books fully extracted: Alexander & Elias-Bursać's flagship textbook, Alexander's companion *Grammar with Sociolinguistic Commentary*, and Hammond's *Serbian: An Essential Grammar* — ~10,220 vocabulary entries, ~457,000 words; own `graphify-out/` built (241 nodes, 355 edges, 12 communities); only 5 vision-only/garbled-OCR books remain for this language's Phase 1 to be fully complete; tentative, see `methodology-observations/serbian_croatian_bosnian_test_run.md` for the full-language-folder-scale readiness verdict and per-book findings); `analysis/`/`synthesized/` correctly empty pending `language_corpus/` progress | `datasets/Serbian_Croatian_Bosnian/` |
| Hungarian | not started *(test-run language)* | not started — `established/` has 3 Markdown files (Phase 1, ~273 vocabulary entries across 3 chapters, subagent-parallelized extraction, tentative); own `graphify-out/` built; `analysis/`/`synthesized/` correctly empty pending `language_corpus/` progress | `datasets/Hungarian/` |
| Dutch | not started *(test-run language)* | not started — `established/` has 3 Markdown files (Phase 1, ~290 entries across 3 chapters chosen for typological/register diversity — foundational, colloquial, diminutives; confirmed real Usage Tier diversity beyond `core`, tentative); own `graphify-out/` built; `analysis/`/`synthesized/` correctly empty pending `language_corpus/` progress | `datasets/Dutch/` |

---

## Maintenance rule

**When a language's mechanics analysis begins, add its folder here and flip status to `in
progress` in the same commit.** Keep this index and `language_corpus/00_Corpus_Collection_Index.md`
consistent — a language should never show `complete` corpus here without an actual row, and never
show analysis progress beyond what the corpus supports.
