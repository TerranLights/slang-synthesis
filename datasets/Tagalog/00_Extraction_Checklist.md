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

**Tagalog: Austronesian, non-concatenative and verb-centered rather than agglutinative in the
Finnish/Korean/Japanese sense this project has seen before.** A single root takes a *different*
affix per trigger category rather than stacking affixes linearly — the same root (e.g. *luto*
"cook") surfaces as 5+ distinct lexical forms depending purely on which argument (actor, object,
locative, instrumental/conveyance, beneficiary, causative) is grammatically focused. Confirmed with
real worked examples across all 14 sources. Productive reduplication does at least four distinct
grammatical jobs (verbal aspect, adjectival intensification/plurality, habitual-adverb derivation,
a formally distinct "moderative" function), and recurs independently on non-verbal items too
(sari-sari, halo-halo, turo-turo). Spanish/English loanword strata are pervasive, sometimes
coexisting in triplicate for a single domain (three parallel numeral systems for counting vs.
telling time, generationally stratified). A genuine sociolinguistic distinction between "Filipino"
and "Tagalog" as structurally distinct varieties, tied concretely to divergent -um-/mag- and
i-/-an trigger choices, was found in a closing essay (established/010f). The *ka-* morpheme
surfaces with at least four unrelated grammatical functions — flagged as an open question for
later mechanics work.

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
| `001-005` | Tagalog Grammar (phonology/nouns/markers, pronouns/adjectives/sentences, verbal focus/trigger system, time/particles/conjunctions) + The World's Major Languages academic typology chapter |
| `006-006c` | Ngumiti ka naman! Tagalog with Humor (all 140 lessons) |
| `007-007l` | Basic Tagalog for Foreigners and Non-Tagalogs (all 44 lessons + 6 appendices) |
| `008-008d` | Teach Yourself Tagalog (18 units) + Living Language Tagalog Complete Course (15 lessons) |
| `009-009c` | VocabuLearn Tagalog Level 1 (full) + Filipino Basic Course (sampled) + Advanced Tagalog Reader (sampled) |
| `010-010f` | Headstart for the Philippines (5 modules + glossary supplement) |
| `011-011c` | Diccionario Ingles-Español-Tagalog (sampled across all 3 volumes) |
| `012-012c` | Making Out in Tagalog (flagship slang source, full extraction) |
| `013` | The Philippines (Language and National Identity in Asia) |
| `014` | Headstart for the Philippines Cultural Notes |

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

- [x] Wave 1 — Clean-text sources (5 sources → established/001-005, 011, 013; ~15 files).
      Tagalog Grammar + The World's Major Languages fully extracted (001-005, ~257 rows,
      flagship chapter 003 covers the full trigger/focus affix system with real worked
      examples). Headstart for the Philippines extracted in full (010/010b-f, 307 rows, all
      5 modules + glossary supplement). Diccionario Ingles-Español-Tagalog representatively
      sampled across all 3 volumes (011/011b/011c, 406 rows — a pre-1940 Spanish-influenced
      orthography, with an emergent trigger/focus overview compiled from real dictionary
      entries). The Philippines (Language and National Identity) extracted in full (013) —
      found an explicit note on Taglish code-mixing as a growing mechanism among younger
      speakers.
- [x] Wave 2 — Vision-read sources (9 sources → established/006-010, 012, 014; ~26 files).
      **Flagship slang source Making Out in Tagalog fully extracted** (012/012b/012c, 382
      rows) — genuinely vulgar/intimate register preserved and tagged, not sanitized; caught
      a mid-extraction silent image-read failure and re-verified the entire book page-by-page
      before finalizing. Ngumiti ka naman! (006-006c, 466 rows, all 140 lessons) and Basic
      Tagalog for Foreigners (007-007l, 953 rows, all 44 lessons + appendices) both extracted
      in full. Teach Yourself Tagalog + Living Language Tagalog + Headstart Cultural Notes
      (008-008d, 014) all extracted in full — recovered cleanly from a session-limit
      interruption via disk-state verification (both courses had actually completed before
      the interrupt, contrary to the failure notification). VocabuLearn Tagalog extracted in
      full (009, 1,323 rows); Filipino Basic Course and Advanced Tagalog Reader
      representatively sampled (009b/009c) given their real scale (745pp/471pp — both turned
      out to be far larger multi-lesson corpora than their triage-stage titles suggested).
      **New gotcha**: a genuine duplicate-scan page pair (Headstart Cultural Notes) — caught
      by reading printed page numbers directly rather than trusting PDF page order.

**Notable cross-source findings**: a productive English-loanword-plus-native-affixation slang
mechanism cross-confirmed across three independent sources (nag-eenjoy, nagsuicide,
mag-aapologize); a linked face/politeness concept cluster (utang na loob/pakikisama/amor
propio/hiya) flagged as a strong Phase 3 mechanics candidate; a documented two-era polysemy
case ("abuso") from a native-speaker essay on English-root Filipinization in tabloid
headlines; a living generational word-clipping process (older ikamo/ikako vs. younger sabi
ko). See commit history for the full per-source breakdown.

**File-numbering collision resolved**: two independent dispatches collided at `003`/`004`/`005`
(Tagalog Grammar's own 5-file sequence vs. Headstart/Diccionario/Making Out In Tagalog). Kept
the Tagalog Grammar series as `001`-`005` and renumbered Headstart → `010`/`010b-f`, Diccionario
→ `011`/`011b/c`, Making Out In Tagalog → `012`/`012b/c`, and The Philippines (Language and
National Identity) → `013`, fixing all internal cross-references.

Corpus was copied from `/media/kuroskalacs/Home-Theater/w-lang/Tagalog (Filipino)/` into this
project's standard `source_reference/languages/Tagalog/` location before extraction began.

**Full Phase 1 reference extraction for Tagalog is now complete** — 41 established files,
~256,000 words, the 9th language in this project to reach Phase 1 completion. Graphify rebuild,
status-doc updates, methodology log, and project memory still pending.
