# Cantonese Slang Mechanics — Extraction Checklist

**Purpose:** analyze the actual mechanics of how Cantonese slang forms and works, using the
corpus collected in `language_corpus/Cantonese/` and, where useful, the grammar/vocabulary
reference in `source_reference/languages/Cantonese/`. Findings here are what eventual synthesis
work (deriving invented slang for the sci-fi setting) will be grounded in.

**This is research only — nothing here is canon** until worked into actual setting material by
explicit decision.

**Status legend:** `[x]` analyzed and written into its output file · `[ ]` not yet done.

**Project-relevance note.** Cantonese is a secondary-priority language in this project — excluded
as a structural contributor to the sibling TepenianHawaiian project's Modern Hawaiian construction
(writing-system/tonal mismatch), but wanted as an auxiliary reinforcement reference. See
`00_Book_Triage_Catalog.md` for the full triage and `00_RESUME_HERE.md` for the full wave-by-wave
detail, incident log, and flagship findings.

**Phase 1 status: COMPLETE (2026-11-03).** All 5 waves from the triage catalog's priority order were
extracted — originally planned at one wave per day, but Waves 2-5 were run back-to-back in a single
session at the user's explicit direction, overriding that pacing for this occasion.

---

## Morphological typology

**Cantonese: analytic/isolating**, like Mandarin and unlike this project's agglutinative languages
(Korean, Hungarian, Japanese, Tagalog's non-concatenative system). Grammatical relationships are
carried by word order, particles, and a classifier system rather than by stacking morphemes onto a
stem. The defining structural complexity instead sits in the **tone system** (6-9 citation tones
depending on counting convention, plus a lexical/non-regular tone-change process) and in a rich
**register/code-mixing system** (Cantonese/English/Mandarin triglossia in Hong Kong) — this second
axis is likely the more direct feeder into slang mechanics once analysis begins. See the triage
catalog's "Morphological typology" section for the full writeup.

---

## Output files — Markdown, sharded by numbered file, not JSON

**Storage model.** All extracted content — raw reference data, mechanics analysis, synthesized
results — lives as **Markdown** (occasionally `.txt`), not hand-authored JSON.

| Directory | Contents | Numbering |
|---|---|---|
| `established/` | The real Cantonese baseline — vocabulary/grammar tables extracted per lesson/chapter/section, per `00_Reference_Extraction_Spec.md` | `001_<label>.md`, `002_<label>.md`, ... |
| `analysis/` | Mechanics findings, one file per mechanism (or closely related group), narrative writeup + examples table | `001_<mechanism>.md`, ... |
| `synthesized/` | Derived in-universe slang output, one file per batch. **Explicitly provisional** — revise via each term's own Revision History subsection, never silent overwrite | `001_<batch>.md`, ... |

Fill this table in as files are created:

| File | Contents |
|---|---|
| `established/001-005_*.md` | *A Dictionary of Cantonese Slang* (Hutton & Bolton) — representative sample (front matter/A, D-E, J, NG-P, back matter). Wave 1. |
| `established/006-028_*.md` | *Cantonese: A Comprehensive Grammar* (Matthews & Yip) — full front-to-back (front matter through Index). Wave 1. |
| `established/029a-c_*.md` | *Basic Cantonese: A Grammar and Workbook* (Yip & Matthews) — full, clean text layer. Wave 2. |
| `established/030a-c_*.md` | *Colloquial Cantonese* (2010 edition) — full 15-unit course, clean text layer. Wave 2. |
| `established/031_*.md` | *Cantonese* (Killingley, Languages of the World/Materials 06) — full grammar sketch. Wave 2. |
| `established/032-037_*.md` | *Intermediate Cantonese: A Grammar and Workbook* (Yip & Matthews) — full, vision-read. Wave 3. |
| `established/038-047_*.md` | *Teach Yourself Cantonese* — full course, vision-read. Wave 3. |
| `established/048_*.md` | *Language Relations in Guangzhou* (Page, NTNU thesis) — academic sociolinguistic. Wave 4. |
| `established/049_*.md` | "Hong Kong" chapter, *Language and National Identity in Asia* (Simpson) — academic sociolinguistic. Wave 4. |
| `established/050-053_*.md` | *Lonely Planet Cantonese Phrasebook* — full book. Wave 5. |
| `established/054_*.md` | Pimsleur "Cantonese I" Supplemental Reading Booklet. Wave 5. |
| `established/055_*.md` | *Colloquial Cantonese* (1994 edition) — non-redundant-supplement check only (confirmed near-identical to the 2010 edition). Wave 5. |

**Phase 1 totals: 60 files (`001`-`055`, incl. lettered sub-parts), ~323,000 words**, every file
independently verified (12-column structural check + placeholder-residue grep) by the orchestrating
session across all 5 waves. Full wave-by-wave detail, the complete incident log (a connection-error
subagent retry, a mid-wave Chinese-medium exclusion of `11.Gateway to Cantonese.djvu`, and a
triage-verdict correction on the Pimsleur booklet), and flagship findings are all in
`00_RESUME_HERE.md`.

---

## Field/column conventions

Same shared conventions as every other language in this project — see
`../00_Usage_Tier_Taxonomy.md`, `../../language_corpus/00_Source_Reliability_Guide.md`,
`../00_Historical_and_Geographic_Context_Guide.md`, and
`../00_Word_Concept_and_Morphological_Typology_Guide.md`. Cantonese's own typology (analytic/
isolating) means the morpheme-breakdown convention is expected to see light use, per the note
above.

## Graphify

This language gets its own graph, scoped to `datasets/Cantonese/`. Run `/graphify datasets/Cantonese`
once there's enough written here to be worth graphing. **Before running: `cd` into
`datasets/Cantonese/` first**, don't run graphify's own Python calls from the repo root with only a
`root=` argument (confirmed real bug, see `00_Reference_Extraction_Spec.md`).

## Mechanisms examined

- [ ] *(none yet — Phase 1 is reference extraction only; mechanics analysis (`analysis/`) hasn't
      started. A substantial set of candidate mechanisms has already surfaced incidentally across
      all 5 waves and is ready to seed this work — see "Suggested next-session order" below)*

## Suggested next-session order

1. ~~Verify Wave 1's structural output~~ — done; all 5 waves structurally verified.
2. Create real native-speaker query sheets in `grammar_logic/native_speaker_queries/` (folder exists
   but is still empty) — strong candidates already flagged during extraction: the *haih*/*mhaih*
   premise-agreement answer logic (vs. English truth-value yes/no), several particle-tone
   pragmatic-force mappings, and the unresolved idiom *waahk-gwái-geuk* ("draw a ghost's leg").
3. Begin `analysis/` mechanics work. Strong candidate mechanisms already surfaced during Phase 1
   extraction, ready to seed this without further source reading: classifier-mismatch register
   inversion; the *gwái*/*séi* taboo-intensifier system and *gwái*-infixation ("magic of gwái"); the
   *-lóu/-pó/-jái/-léui/-mūi* pejorative-suffix family (incl. the *gwái-* foreigner-naming set); the
   rule-governed English/Japanese loanword-nativization system documented in Intermediate Grammar
   Unit 25; the "water" = money slang register; and the book-named "Shortcuts" phrase-clipping
   pattern documented independently in both *Basic Cantonese* and *Teach Yourself Cantonese*.
4. Run `/graphify datasets/Cantonese` once the above has produced real `analysis/` content worth
   graphing alongside `established/`.
