# Russian Slang Mechanics — Extraction Checklist

**Purpose:** analyze the actual mechanics of how Russian slang forms and works, using the corpus
collected in `language_corpus/Russian/` and, where useful, the grammar/vocabulary reference in
`source_reference/languages/Russian/`. Findings here are what eventual synthesis work (deriving
invented slang for the sci-fi setting) will be grounded in.

**This is research only — nothing here is canon** until worked into actual setting material by
explicit decision.

**Status legend:** `[x]` analyzed and written into its output file · `[ ]` not yet done.

**Full triage:** see `00_Book_Triage_Catalog.md` — 204-file, ~3.6GB corpus, the largest and most
heterogeneous this project has processed. ~75% of files are scanned image-only with no text layer
(the highest proportion of any language triaged so far). Extraction proceeds in 3 waves; Wave 3
(vision-reading) is expected to span multiple sessions given its scale (~45 prioritized sources).

---

## Morphological typology

**Russian: fusional (inflectional), six-case system** (nominative, genitive, dative, accusative,
instrumental, prepositional), case/number/gender fused into single noun/adjective/pronoun endings
rather than agglutinatively stacked. Verbal aspect (perfective/imperfective) is a further dimension
often realized via suppletion/prefixation. Register expressed via ты/вы (T-V pronoun system) plus
lexical choice, not dedicated honorific morphology. To be refined with real morpheme-breakdown
examples once extraction lands.

---

## Output files — Markdown, sharded by numbered file, not JSON

| Directory | Contents | Numbering |
|---|---|---|
| `established/` | The real Russian baseline — vocabulary/grammar tables extracted per lesson/chapter/section, per `00_Reference_Extraction_Spec.md` | `001_<label>.md`, `002_<label>.md`, ... |
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
for the full writeup of each.

## Graphify

This language gets its own graph, scoped to `datasets/Russian/`. Run `/graphify datasets/Russian`
once Wave 1 lands. **`cd` into `datasets/Russian/` first** — never run graphify's Python calls from
the repo root. Verify `git status` on the repo-root `graphify-out/` after every run.

## Mechanisms examined

- [ ] *(to be filled in once established/ has enough content to analyze)*

## Suggested next-session order

1. Complete Wave 1 (Group A clean-text sources, 15 distinct sources after dedup).
2. Wave 2 (Group B clean-text supplements) — apply non-redundant-supplement pattern heavily, several
   titles likely overlap Wave 1's core grammars.
3. Wave 3 (Group C vision-reading, ~45 prioritized sources) — start with *Streetwise Russian* and
   *Dermo!* given direct slang relevance; expect this wave to span multiple sessions.
4. Graphify rebuild once Wave 3 substantially lands.
