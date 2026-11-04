# Swedish Slang Mechanics — Extraction Checklist

**Purpose:** analyze the actual mechanics of how Swedish slang forms and works, using the
corpus collected in `language_corpus/Swedish/` and, where useful, the grammar/vocabulary
reference in `source_reference/languages/Swedish/`. Findings here are what eventual synthesis
work (deriving invented slang for the sci-fi setting) will be grounded in.

**This is research only — nothing here is canon** until worked into actual setting material by
explicit decision.

**Status legend:** `[x]` analyzed and written into its output file · `[ ]` not yet done.

**Project-relevance note.** Swedish is a "second-era" (Tepenian-stage) contributing-language
candidate for the sibling `TepenianLanguage` project — its associated domain idea there is
"technical studies." Triaged and extracted 2026-11-03/04. See `00_Book_Triage_Catalog.md` for the
full triage and `00_RESUME_HERE.md` for the full wave-by-wave detail, incident log, and flagship
findings.

**Phase 1 status: extraction complete for the clearly-in-scope English-medium pool (2026-11-04).**
**A standing open item blocks full Phase 1 closure: the triage catalog's §5 flags 37
Swedish-medium-of-Swedish files (incl. the flagship slang dictionary *Svenska idiom: 3.500
vardagsuttryck*) that need the user's explicit ruling before extraction — not extracted this
pass per this project's "flag, don't guess" rule. Phase 1 is complete for the authorized scope,
not complete in the "every real candidate extracted" sense until that ruling is made.**

---

## Morphological typology

**Swedish: fusional with an active ongoing simplification trend**, North Germanic branch. Noun
gender has visibly collapsed from a historical 3-4-category system (masculine/feminine/neuter, or
an intermediate "common"+neuter stage) down to the modern 2-way *en*-gender/*ett*-gender split —
documented independently across three sources spanning 1923-2008 in this corpus (Björkhagen,
Uppvall, and the modern grammars), giving an unusually well-dated diachronic trail for a single
project session. Verb-subject number/person agreement, extinct in the modern spoken and written
standard, was still alive in the formal "literary language" register as late as the 1930s per this
corpus's own sources. Definiteness is marked by a bound suffix on the noun (*en bil* → *bilen*)
layered with a separate preposed definite article when the noun is modified by an adjective — a
double-definiteness system, not unique to Swedish among the Scandinavian languages but worth
tracking consistently. See `established/004_swedish_andersson_chapter.md` for the fullest single
academic-linguistics treatment in this corpus.

---

## Output files — Markdown, sharded by numbered file, not JSON

**Storage model.** All extracted content — raw reference data, mechanics analysis, synthesized
results — lives as **Markdown** (occasionally `.txt`), not hand-authored JSON.

| Directory | Contents | Numbering |
|---|---|---|
| `established/` | The real Swedish baseline — vocabulary/grammar tables extracted per lesson/chapter/section, per `00_Reference_Extraction_Spec.md` | `001_<label>.md`, `002_<label>.md`, ... |
| `analysis/` | Mechanics findings, one file per mechanism (or closely related group), narrative writeup + examples table | `001_<mechanism>.md`, ... |
| `synthesized/` | Derived in-universe slang output, one file per batch. **Explicitly provisional** — revise via each term's own Revision History subsection, never silent overwrite | `001_<batch>.md`, ... |

**Output files table:**

| File(s) | Contents |
|---|---|
| `established/001-005_*.md` | Essential grammars (Holmes & Hinchliffe; Björkhagen 1923; Uppvall; Andersson academic chapter) + In-Flight Swedish phrasebook. |
| `established/006-007_*.md` | Representative samples of Norstedts and Prismas EN-SV/SV-EN dictionaries — register-tag cross-comparison flagship finding (skit-/skita disagreement). |
| `established/008-018_*.md` | Courses: Teach Yourself Swedish (Croghan 1995/96, McClean 1947), FSI Swedish Basic Course (sampled, non-redundant-supplement), Advanced Spoken Swedish (Söderbäck), Colloquial Swedish (1996 & 2007, both with dedicated Slang glossaries), Beginning Swedish (Johnson 1939), Glossika 1-3 (sampled). |
| `established/019_*.md` | Beginner's Swedish (Mellor) — non-redundant-supplement, etymology-essay series. |
| `established/020-034_*.md` | Native-literature readers: Astrid Lindgren (9 titles), Jansson's Moomin TV-tie-in book, Holmström, Wallström, Alander (x2), The Svenssons. Flagship: recurring "världens bästa [X]" idiolect template across all 3 Karlsson books. |
| `established/035-036_*.md` | Historical Dictionary of Sweden, Culture and Customs of Sweden — the Rinkebysvensk/förortsvenska immigrant-multiethnolect finding. |

**Phase 1 totals: 44 files (`001`-`036`, incl. lettered sub-parts), ~335,000 words**, every file
independently verified (12-column structural check + placeholder-residue grep) by the orchestrating
session. Full wave-by-wave detail and the complete incident log (a numbering collision between two
concurrently-dispatched waves, a new vector-outline/no-text-layer PDF gotcha, a gap-fill for a
missed title) are in `00_RESUME_HERE.md`.

**NOT extracted — the §5 Swedish-medium-of-Swedish pile (37 files)**, pending the user's ruling.
This includes the flagship slang dictionary *Svenska idiom: 3.500 vardagsuttryck* (Hans Luthman),
the *Nya mål*/*Rivstart*/*På svenska!* SFI course series, and two standalone Swedish-medium grammar
references. See the triage catalog §5 for the full list.

---

## Field/column conventions

Same shared conventions as every other language in this project — see
`../00_Usage_Tier_Taxonomy.md`, `../../language_corpus/00_Source_Reliability_Guide.md`,
`../00_Historical_and_Geographic_Context_Guide.md`, and
`../00_Word_Concept_and_Morphological_Typology_Guide.md`.

## Graphify

This language gets its own graph, scoped to `datasets/Swedish/`. Run `/graphify datasets/Swedish`
next. **Before running: `cd` into `datasets/Swedish/` first**, don't run graphify's own Python
calls from the repo root with only a `root=` argument.

## Mechanisms examined

- [ ] *(none yet — Phase 1 is reference extraction only; mechanics analysis (`analysis/`) hasn't
      started. Strong candidate mechanisms already surfaced incidentally during extraction and are
      ready to seed this work — see "Suggested next-session order" below)*

## Suggested next-session order

1. **Resolve the §5 Swedish-medium ruling** — the single largest open item for this language.
   Resolving it toward extraction would unlock the flagship slang dictionary *Svenska idiom* and
   the SFI course series, the largest coherent content block left untouched.
2. Create real native-speaker query sheets in `grammar_logic/native_speaker_queries/` (folder does
   not yet exist) — candidates already flagged during extraction: the cross-dictionary skit-/skita
   register-tag disagreement (is one dictionary simply out of date, or is this live register
   variation a single-dictionary snapshot can't resolve?); whether `jävla` really is restricted the
   way its absence from one dictionary's sampled range suggests.
3. Begin `analysis/` mechanics work. Strong candidate mechanisms already surfaced during Phase 1
   extraction, ready to seed this without further source reading: the Rinkebysvensk/förortsvenska
   immigrant multiethnolect and its contested literary adoption; the *jätte-*/*skit-* productive
   intensifier-prefix pair (register-inconsistently tagged across dictionaries); the *-is*/*-a(n)*
   clipping/hypocorism system (dagis, godis, morsa, Kalle); the colloquial consonant-dropping system
   (jag→ja, mig→mej, de/dem→dom); the "världens bästa [X]" self-praise idiolect template.
4. Run `/graphify datasets/Swedish` once the above has produced real `analysis/` content worth
   graphing alongside `established/`.
