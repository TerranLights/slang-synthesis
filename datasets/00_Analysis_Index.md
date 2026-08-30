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

**Prerequisite column.** A language cannot move past `not started` here until its corpus in
`language_corpus/` is at least `in progress` — analysis needs material to analyze.

**Scaling.** Structured output (`established/`, `analysis/`, `synthesized/`) lives as sharded JSON
directories, not single files — see the per-language `00_Extraction_Checklist.md` for shard-size
targets. Each language also gets its **own** `graphify-out/` scoped to `datasets/<Language>/`,
never one repo-wide graph. If a single language's own graph outgrows graphify's size warnings,
narrow further by graphing `established/`, `analysis/`, and `synthesized/` separately.

---

## Status by language

*(No language has a corpus in progress yet — this table will grow rows as
`language_corpus/00_Corpus_Collection_Index.md` entries move past `not started`. Add a row here
the same commit a language's corpus work begins, not just when analysis itself starts, so the two
indexes stay in sync.)*

| Language | Corpus status (see language_corpus index) | Analysis status | Folder |
|---|---|---|---|
| — | — | — | — |

---

## Maintenance rule

**When a language's mechanics analysis begins, add its folder here and flip status to `in
progress` in the same commit.** Keep this index and `language_corpus/00_Corpus_Collection_Index.md`
consistent — a language should never show `complete` corpus here without an actual row, and never
show analysis progress beyond what the corpus supports.
