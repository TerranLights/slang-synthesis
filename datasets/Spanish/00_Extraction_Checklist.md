# Spanish Slang Mechanics — Extraction Checklist

**Purpose:** analyze the actual mechanics of how Spanish slang forms and works, using the corpus
collected in `language_corpus/Spanish/` and, where useful, the grammar/vocabulary reference in
`source_reference/languages/Spanish/`. Findings here are what eventual synthesis work (deriving
invented slang for the sci-fi setting) will be grounded in.

**This is research only — nothing here is canon** until worked into actual setting material by
explicit decision.

**Status legend:** `[x]` analyzed and written into its output file · `[ ]` not yet done.

**Full triage:** see `00_Book_Triage_Catalog.md` — 189MB corpus, 133 PDF files + 1 EPUB, much
smaller and cleaner than Russian/Hungarian/Korean (only 3 of ~14 distinct sources lack a text
layer). Extraction proceeds in 2 waves.

---

## Morphological typology

**Spanish: fusional (inflectional)**, two-gender noun system, verb conjugation marking person/
number/tense/mood/aspect via stem suffixation — no case marking on nouns (only pronouns retain
case-like forms). ser/estar copula split and tú/vos/usted register variation (which differs across
the 5 GINI-represented nations — Spain, Mexico, Argentina, Chile, Uruguay) are the structural
features most relevant to register/slang work. To be refined with real morpheme-breakdown examples
once extraction lands.

---

## Output files — Markdown, sharded by numbered file, not JSON

| Directory | Contents | Numbering |
|---|---|---|
| `established/` | The real Spanish baseline — vocabulary/grammar tables extracted per lesson/chapter/section, per `00_Reference_Extraction_Spec.md` | `001_<label>.md`, `002_<label>.md`, ... |
| `analysis/` | Mechanics findings, one file per mechanism (or closely related group), narrative writeup + examples table | `001_<mechanism>.md`, ... |
| `synthesized/` | Derived in-universe slang output, one file per batch. **Explicitly provisional** — revise via each term's own Revision History subsection, never silent overwrite | `001_<batch>.md`, ... |

### Output files table

**Wave 1 complete (2026-09-14): 45 files, ~313,600 words, 11 distinct sources.**

| File(s) | Contents |
|---|---|
| `001_colloquial_spanish_latin_america.md` | Full 168p — rich LatAm-vs-Iberian register/dialect splits (chico/pequeño, coger's regional taboo flag, vosotros vs. ustedes) |
| `002_colloquial_spanish_latin_america_2.md` | Full 190p — **flagship find**: a full voseo paradigm (Unit 8, vos/sos present indicative/imperative/subjunctive); country-tagged slang (chévere, ¡Híjole!, ¡Qué vaina!) |
| `003/004/004b_madrigals_magic_key_part1/2/glossary.md` (3 files) | Full 740p mnemonic-based grammar — representative sampling of formulaic cognate-suffix categories (documented scope decision); explicit Mexican-slang appendix (güero, plata) |
| `005_practice_makes_perfect_basic_spanish_grammar.md` | Full 273p, 50 lessons, 872 vocabulary rows |
| `006_practice_makes_perfect_advanced_spanish_grammar.md` | Full 210p — ~90-idiom catalog (Unit 12), diminutive regional split (-ico/-illo/-ito), Argentine recién+preterit |
| `007_practice_makes_perfect_spanish_irregular_verbs.md` | Full 127p, 97-verb principal-parts glossary |
| `008/008b/008c_practice_makes_perfect_spanish_verb_tenses.md` (3 files) | Full 354p, ~640 vocabulary rows |
| `009/009b/009c_practice_makes_perfect_spanish_vocabulary.md` (3 files) | **Partial — Preliminary Matters + Units 1-2 of 10 only** (pp.1-69 of 450). Units 3-10 left as a known, flagged gap — this is an unusually vocabulary-dense book (~10,000 words per its own preface) |
| `010_..._010d_learning_spanish_like_crazy_level1.md` (4 files) | Full 35 files (32 lessons + Insultos_01 + insultosvulgares + readme) — insult lessons tagged `slang`/`taboo` |
| `011_..._011t_learning_spanish_like_crazy_level2.md` (20 files) | Full 42 files including both Bonus Slang Lessons — clipping/apocope patterns (mano/mana), semantic-repurposing slang (naranjas→"no") |
| `012_..._012g_learning_spanish_like_crazy_level3.md` (7 files) | Full 42 files — confirmed the two overlapping-numbered lesson series (Leccion##-final vs Spanish_Lesson_##) are genuinely DIFFERENT content, not duplicates, both extracted; full por/para grammar system; -ón/-ona augmentative pattern |

**Known gap, explicitly flagged (non-blocking, honest partial-completion reporting):** Practice
Makes Perfect Spanish Vocabulary, Units 3-10 of 10 (see above).

---

## Field/column conventions

Same shared conventions as every other language in this project — Usage Tier
(`../00_Usage_Tier_Taxonomy.md`), Transcription/Vision-Reading Confidence, Attested Era/Region
(`../00_Historical_and_Geographic_Context_Guide.md`), morpheme breakdown
(`../00_Word_Concept_and_Morphological_Typology_Guide.md`). See `_TEMPLATE/00_Extraction_Checklist.md`
for the full writeup of each. Given Spanish spans 5 GINI-represented nations with famously
divergent registers (Iberian vs. Mexican vs. Rioplatense vs. Chilean), flag Attested Region/
Geographic Scope wherever a source itself marks a national/dialectal variant — do not infer
regionality from a book's own publisher or author nationality.

## Graphify

This language gets its own graph, scoped to `datasets/Spanish/`. Run `/graphify datasets/Spanish`
once there's enough content. **`cd` into `datasets/Spanish/` first** — never run graphify's Python
calls from the repo root. Verify `git status` on the repo-root `graphify-out/` after every run.

## Mechanisms examined

- [ ] *(to be filled in once established/ has enough content to analyze)*

## Suggested next-session order

1. Wave 1 (Group A clean-text sources, 11 distinct sources — 8 standalone + Learning Spanish Like
   Crazy's 3 levels) — prioritize the built-in slang/insult lessons.
2. Wave 2 (Group B vision-reading, 3 sources) — apply non-redundant-supplement pattern for
   Practice Makes Perfect Complete Spanish Grammar against Basic + Advanced.
3. Graphify rebuild once both waves land.
