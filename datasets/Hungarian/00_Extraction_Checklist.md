# Hungarian Slang Mechanics — Extraction Checklist

**This is the pipeline's second test-run language — everything below is tentative until the
developer reviews it.** See `../../methodology-observations/hungarian_test_run.md` for process
findings (comparing against the first, Serbian/Croatian/Bosnian, test run) and
`00_Book_Triage_Catalog.md` (this folder) for the source-material survey. (`Hungarian` is its own
folder-safe name — no display-name-vs-path-name split needed here, unlike Serbian/Croatian/Bosnian.)

**Purpose:** analyze the actual mechanics of how Hungarian slang forms and works, using the
corpus collected in `language_corpus/Hungarian/` and, where useful, the grammar/vocabulary
reference in `source_reference/languages/Hungarian/`. Findings here are what eventual synthesis
work (deriving invented slang for the sci-fi setting) will be grounded in.

**This is research only — nothing here is canon** until worked into actual setting material by
explicit decision.

**Status legend:** `[x]` analyzed and written into its output file · `[ ]` not yet done.

---

## Morphological typology

*(Fill in during Phase 0 triage, before extraction begins — see
`../00_Word_Concept_and_Morphological_Typology_Guide.md`. What is this language's approach to the
concept of a "word"? Isolating / agglutinative / fusional / polysynthetic / a mix — with one or two
concrete examples if available. This affects how `established/` vocabulary entries should be
recorded and how `morphological_play` should be interpreted in `analysis/`.)*

**Hungarian: agglutinative.** Grammatical relationships (case, possession, plurality, tense,
definiteness) are marked by stacking separable, individually-meaningful suffixes onto a stem,
governed by **vowel harmony** (a suffix's vowel changes to match the stem's own front/back and
rounded/unrounded vowel quality — see the grammar's own Chapter 3). The case system alone (Chapter
6 of the Rounds grammar) covers an unusually large inventory of grammatical cases expressed this
way, rather than via prepositions as in English. Concrete example, pending a real extracted
instance: a Hungarian noun can take a case suffix, a possessive suffix, and a plural marker all
stacked on one stem, each piece independently identifiable — the general "agglutinative" pattern
the Word-Concept guide's Finnish example illustrates. See
`../00_Word_Concept_and_Morphological_Typology_Guide.md`. Will be refined with a real morpheme
breakdown once the Chapter 6 (case system) extraction pass completes.

---

## Output files — Markdown, sharded by numbered file, not JSON

**Storage model.** All extracted content — raw reference data, mechanics analysis, synthesized
results — lives as **Markdown** (occasionally `.txt`), not hand-authored JSON. This matches how the
rest of this project's own methodology documentation works, and lets `/graphify` serve as the
organized-summary/pointer layer instead of a manually-maintained manifest (see Graphify section
below).

| Directory | Contents | Numbering |
|---|---|---|
| `established/` | The real Hungarian baseline — vocabulary/grammar tables extracted per lesson/chapter/section, per `00_Reference_Extraction_Spec.md` | `001_<label>.md`, `002_<label>.md`, ... |
| `analysis/` | Mechanics findings, one file per mechanism (or closely related group), narrative writeup + examples table | `001_<mechanism>.md`, ... |
| `synthesized/` | Derived in-universe slang output, one file per batch. **Explicitly provisional** — revise via each term's own Revision History subsection, never silent overwrite | `001_<batch>.md`, ... |

Copy `_TEMPLATE/established/001_TEMPLATE.md`, `_TEMPLATE/analysis/001_TEMPLATE.md`,
`_TEMPLATE/synthesized/001_TEMPLATE.md` as starting points. **Don't let a single file grow
unbounded** — split into a new numbered file once one gets unwieldy to read/diff, same discipline
used in `language_corpus/`. **No `_index.json` manifest to maintain** — this checklist's own
`## Output files` table (below) is the human-readable index; `/graphify` (see below) is the
machine-queryable one.

Fill this table in as files are created:

| File | Contents |
|---|---|
| `established/001_chapters1-3_phonology_vowel_harmony.md` | Rounds, *Hungarian: An Essential Grammar* (2nd ed., 2009), Chapters 1-3 (Alphabet, Pronunciation, Vowel Harmony), pp. 3-12. ~65 vocabulary items, 14 grammar-point subsections, morpheme breakdowns for consonant-lengthening pairs and all ten of Chapter 3's vowel-harmony worked examples. |
| `established/002_chapter5_nouns.md` | Rounds, *Hungarian: An Essential Grammar* (2nd ed., 2009), Chapter 5 "Nouns," pp. 76–85: articles (definite/indefinite/zero), suffix stacking & vowel harmony, noun stem classes (vowel-final, low-vowel, v-stem, `-alom/-elem`, fleeting-vowel, regular) and their plural formation, singular/plural usage rules. ~100 vocabulary items, morpheme breakdowns for representative stem-alternation examples. |
| `established/003_chapter6_case_system.md` | Rounds, *Hungarian: An Essential Grammar* (2nd ed., 2009), Chapter 6 "The Case System," pp. 86-113: all 23 Hungarian cases (grammatical, locative, oblique, less-productive), verb/case government, plural declension. ~115 representative vocabulary items (deliberately not exhaustive — case coverage prioritized over cataloguing every declension-table word), 11 morpheme breakdowns including a triple-stack example (`gyerekeire`). |

---

## Field/column conventions

**Usage-tier / slang-type categorization.** `established/` vocabulary tables carry a `Usage Tier`
column (e.g. `core`, `technical`, `taboo`, `slang`, ...) — see `../00_Usage_Tier_Taxonomy.md` for
the shared vocabulary, kept consistent across languages so findings are comparable. `analysis/` and
`synthesized/` entries carry `Slang Type` and `Derived From Tiers` tags, capturing which
standard-language tier(s) a given slang-formation mechanism actually draws from. **Every tier/type
is extensible with dot-notation subcategories** (`technical.medical`) — use them freely as real
data surfaces distinctions worth keeping, and promote a subcategory into the shared taxonomy doc
once it recurs across 2+ languages.

**Transcription risk carries through.** Any `analysis/` example drawn from a corpus entry that was
itself sourced from a subtitle/transcript keeps that entry's `Source Type` and `Transcription
Confidence` — see
[`../../language_corpus/00_Source_Reliability_Guide.md`](../../language_corpus/00_Source_Reliability_Guide.md).
Don't build a mechanism finding on a `low_confidence` example without saying so.

**Historical & geographic context — optional, fill in only when the source supports it.** Entries
carry `Attested Era`/`Attested Region`/`Geographic Scope` columns — see
[`../00_Historical_and_Geographic_Context_Guide.md`](../00_Historical_and_Geographic_Context_Guide.md).
`—` is a legitimate value, not a gap to guess-fill; false precision here is worse than an honest
unknown.

**Morphological composition.** For agglutinative/polysynthetic (or complex fusional) word-forms,
`established/` entries include a morpheme breakdown rather than treating the surface form as
atomic — see `../00_Word_Concept_and_Morphological_Typology_Guide.md`.

## Graphify

This language gets its own graph, scoped to `datasets/Hungarian/` (separate from
`language_corpus/Hungarian/`'s own graph). Run `/graphify datasets/Hungarian` once there's
enough written here to be worth graphing — no need to do this before any content exists. Its
`graph.json` (nodes carrying `source_file`/`source_location`) is this language's organized-summary
and pointer layer — no separate hand-authored index needed. If a single language's graph itself
grows past graphify's own size warnings (2M words / 500 files), narrow further — e.g. graph
`established/`, `analysis/`, and `synthesized/` as separate runs rather than one combined pass.

## Mechanisms examined

- [ ] *(not started — Phase 1 reference extraction only so far, Phase 3 mechanics analysis has not
      begun)*

## Reference extraction progress (Phase 1)

Extracting from `Hungarian-An-Essential-Grammar-Second-Edition-.pdf` (Rounds, 2nd ed., 2009),
subagent-parallelized per `../00_Reference_Extraction_Spec.md` — the first real test of that method
(the Serbian/Croatian/Bosnian run's shard was done manually, before the spec existed).

- [x] Chapters 1-3 (Alphabet, Pronunciation, Vowel Harmony) — written to `established/001_chapters1-3_phonology_vowel_harmony.md`
- [x] Chapter 5 (Nouns) — written to `established/002_chapter5_nouns.md`
- [x] Chapter 6 (Case system) — written to `established/003_chapter6_case_system.md`
- [ ] Chapter 4 (Verbs) — deliberately deferred for this test run (60 pages, would be a 4th chunk;
      3 parallel chunks is enough to validate the method without ballooning scope)
- [ ] `ON-HUNGARIAN-MORPHOLOGY.pdf`, `750-Hungarian-proverbs.pdf`,
      `A-complete-practical-grammar-...pdf` — not started
- [ ] `Magyar Szlengszótár.pdf` (slang dictionary) — needs vision-reading approach decided first;
      see `00_Book_Triage_Catalog.md`'s scope note on the Phase 1/Phase 2 boundary question this
      file raises
- [ ] 6 subfolders of audio-course material — not triaged yet, see `00_Book_Triage_Catalog.md`

## Suggested next-session order

1. Once the 3 parallel-subagent chunks land, compare results against the Serbian/Croatian/Bosnian
   manual pass — see `../../methodology-observations/hungarian_test_run.md` for the comparison.
2. Decide a vision-reading approach for `Magyar Szlengszótár.pdf` (image-only) — it's genuinely
   high-value slang content, not just grammar reference.
3. Triage the 6 audio-course subfolders before considering this language's Phase 1 triage complete.
