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

| File | Contents |
|---|---|
| *(none yet — Wave 1 in progress)* | |

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
