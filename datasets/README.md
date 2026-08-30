# Datasets

Per-language analysis of slang mechanics — how each language's slang actually forms and works,
distilled from `language_corpus/` (and, where useful, `source_reference/`).

**Start here:** [`00_Analysis_Index.md`](00_Analysis_Index.md) — tracks which languages have
analysis started/complete and where each one's folder lives.

**Shared taxonomy:** [`00_Usage_Tier_Taxonomy.md`](00_Usage_Tier_Taxonomy.md) — the cross-language
categories used to tag standard-vocabulary usage tiers and slang-derivation types, so findings are
comparable across languages instead of each one inventing its own labels.

**Historical & geographic context:**
[`00_Historical_and_Geographic_Context_Guide.md`](00_Historical_and_Geographic_Context_Guide.md) —
optional `attested_era`/`attested_region` fields for when a source actually supports dating or
localizing a term; `null` is a legitimate value, not a gap to guess-fill.

**Starting a new language:** copy [`_TEMPLATE/`](_TEMPLATE/) into a new `<Language>/` folder here,
then add a row to the index in the same commit. Requires that language's corpus in
`language_corpus/` to already be at least in progress.
