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
`00_Book_Triage_Catalog.md` for the full triage and `00_RESUME_HERE.md` for the wave plan (paced at
one wave per day per explicit user constraint — token-burn concern).

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
| `established/001-005_*.md` | *A Dictionary of Cantonese Slang* (Hutton & Bolton) — representative sample (front matter/A, D-E, J, NG-P, back matter), Wave 1, DONE |
| `established/006-028_*.md` | *Cantonese: A Comprehensive Grammar* (Matthews & Yip) — full front-to-back extraction (front matter through Index), Wave 1, DONE |

**Wave 1 totals:** 28 files, ~123,229 words, all passing 12-column structural verification. Full
detail, incident log, and flagship findings in `00_RESUME_HERE.md`.

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

- [ ] *(none yet — Wave 1 is reference extraction only; mechanics analysis starts once enough
      `established/` material exists)*

## Suggested next-session order

1. Verify Wave 1's structural output (12-column check, placeholder grep).
2. Dispatch Wave 2 (Tier 2: `04.Basic Cantonese A Grammar and Workbook.pdf`, `03.Colloquial
   Cantonese 2010.pdf`, `06.Cantonese - Languages of the World.pdf`) — **one wave per day**, so not
   before the next day.
