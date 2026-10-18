# Tagalog Slang Mechanics — Extraction Checklist

**Phase 0 triage complete 2026-10-18.** See `00_Book_Triage_Catalog.md` for the source-material
survey (25 real files, ~303MB, currently staged on an external drive — not yet copied into this
project's `source_reference/languages/Tagalog/` tree; see the triage catalog's location note).
Tagalog is directly relevant to both this project's slang-mechanics work and the user's parallel
"Tepenian Hawaiian" pidgin-synthesis project, alongside Korean, Latin American/Mexican Spanish,
and Ilocano.

**Purpose:** analyze the actual mechanics of how Tagalog slang forms and works, using the
corpus collected in `language_corpus/Tagalog/` and, where useful, the grammar/vocabulary
reference in `source_reference/languages/Tagalog/`. Findings here are what eventual synthesis
work (deriving invented slang for the sci-fi setting, and feeding the Tepenian Hawaiian pidgin
project) will be grounded in.

**This is research only — nothing here is canon** until worked into actual setting material by
explicit decision.

**Status legend:** `[x]` analyzed and written into its output file · `[ ]` not yet done.

---

## Morphological typology

**Tagalog: Austronesian, with a non-concatenative verb-centered affix-and-trigger (voice/focus)
system** — see `00_Book_Triage_Catalog.md`'s morphological typology note for the preliminary
profile (the trigger system, productive reduplication, heavy Spanish + growing English loanword
strata). This is the first Austronesian-family language in this project — refine here once Wave 1
extraction lands with real worked examples.

---

## Output files — Markdown, sharded by numbered file, not JSON

Same storage model as every other language in this project — see `../00_Reference_Extraction_Spec.md`.

| Directory | Contents | Numbering |
|---|---|---|
| `established/` | The real Tagalog baseline — vocabulary/grammar tables extracted per lesson/chapter/section | `001_<label>.md`, `002_<label>.md`, ... |
| `analysis/` | Mechanics findings (Phase 3, not started) | `001_<mechanism>.md`, ... |
| `synthesized/` | Derived in-universe slang output (Phase 6, not started) | `001_<batch>.md`, ... |

Fill this table in as files are created:

| File | Contents |
|---|---|
| *(pending Wave 1/2 dispatch — triage only so far)* | |

## Field/column conventions

Same shared conventions as every other language — `Usage Tier`, `Attested Era`/`Attested Region`/
`Geographic Scope`, `Transcription Confidence`/`Vision Reading Confidence`, morpheme breakdowns
where relevant. See `../00_Reference_Extraction_Spec.md`. **New for Tagalog**: vocabulary entries
involving verbal affixes should record the trigger/focus category (agent-trigger, object-trigger,
etc.) explicitly, since this is the core grammatical mechanism of the language, parallel to how
Japanese entries record script form.

## Graphify

This language gets its own graph, scoped to `datasets/Tagalog/`. Not yet run — build after waves
land. **Must `cd` into `datasets/Tagalog/` first, never run graphify's Python calls from the repo
root.**

## Mechanisms examined

- [ ] *(not started — Phase 0 triage only so far, Phase 1 reference extraction has not begun)*

## Reference extraction progress (Phase 1)

- [ ] Wave 1 — Clean-text sources (5 files: Headstart for the Philippines, Tagalog Grammar,
      Tagalog [World's Major Languages], Diccionario Ingles-Español-Tagalog [sampled], The
      Philippines [Language and National Identity])
- [ ] Wave 2 — Vision-read sources (9 files: Basic Tagalog for Foreigners, Teach Yourself Tagalog,
      Living Language Tagalog, Headstart Cultural Notes, Filipino Basic Course [sampled], Ngumiti
      ka naman!, Making Out in Tagalog [flagship slang], VocabuLearn Tagalog, Advanced Tagalog
      Reader [sampled])

**Before Wave 1/2 dispatch**: copy the source corpus from
`/media/kuroskalacs/Home-Theater/w-lang/Tagalog (Filipino)/` into this project's standard
`source_reference/languages/Tagalog/` location.
