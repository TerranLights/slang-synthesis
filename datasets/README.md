# Datasets

Per-language analysis of slang mechanics — how each language's slang actually forms and works,
distilled from `language_corpus/` (and `source_reference/`, for the `established/` baseline).

**Start here:** [`00_Analysis_Index.md`](00_Analysis_Index.md) — tracks which languages have
analysis started/complete and where each one's folder lives.

**Extraction spec:** [`00_Reference_Extraction_Spec.md`](00_Reference_Extraction_Spec.md) — the
reusable subagent prompt for Phase 1 (grammar/vocabulary reference extraction): coverage rule,
copyright discipline, output format, chunking convention.

**Shared taxonomy:** [`00_Usage_Tier_Taxonomy.md`](00_Usage_Tier_Taxonomy.md) — the cross-language
categories used to tag standard-vocabulary usage tiers and slang-derivation types, so findings are
comparable across languages instead of each one inventing its own labels.

**Historical & geographic context:**
[`00_Historical_and_Geographic_Context_Guide.md`](00_Historical_and_Geographic_Context_Guide.md) —
optional `Attested Era`/`Attested Region` columns for when a source actually supports dating or
localizing a term; `—` is a legitimate value, not a gap to guess-fill.

**Word-concept & morphological typology:**
[`00_Word_Concept_and_Morphological_Typology_Guide.md`](00_Word_Concept_and_Morphological_Typology_Guide.md)
— "word" isn't a stable unit across languages (agglutinative languages like Finnish can pack a
whole English phrase into one orthographic word); how to record composed word-forms and interpret
`morphological_play` per-language.

**Storage model.** Content is Markdown (occasionally `.txt`), sharded into numbered files per
lesson/chapter/mechanism/batch — not hand-authored JSON. `/graphify datasets/<Language>` provides
the organized-summary/pointer layer over that content once there's enough to graph.

**Starting a new language:** copy [`_TEMPLATE/`](_TEMPLATE/) into a new `<Language>/` folder here,
then add a row to the index in the same commit. The `established/` directory only needs
`source_reference/` material to get going — `analysis/` and `synthesized/` are the parts gated on
`language_corpus/` being at least in progress.
