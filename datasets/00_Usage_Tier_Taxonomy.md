# Usage-Tier & Slang-Type Taxonomy

**Purpose.** A shared, cross-language vocabulary for two categorization dimensions that every
language's `established/` and `analysis/` Markdown tables should use consistently, so findings are
comparable across languages rather than each language inventing its own ad hoc labels.

**This is a living document.** Start from the categories below, but if a language's real data
doesn't fit, extend this file (don't force a fit) and note the addition's language of origin.
Language-specific values are fine in an `established/` entry's `Usage Tier` column even before
they're added here — but if the same value keeps recurring across 2+ languages, promote it into
this shared list in the same commit.

**See also `00_Word_Concept_and_Morphological_Typology_Guide.md`** — the `morphological_play`
derivation type below means something different depending on a language's morphological typology
(agglutinative languages have rich morphological combination built into standard grammar; isolating
languages don't), so ground any `morphological_play` finding in that language's own typology
profile.

**Every tier and derivation type here is extensible with subcategories, by design.** Real
findings will very likely turn up distinctions this list doesn't anticipate — a language's
`technical` vocabulary might turn out to split usefully into `technical.medical` and
`technical.military`, or `taboo_inversion` into `taboo_inversion.religious` vs.
`taboo_inversion.bodily`. **Use dot-notation to nest:** `usage_tier: "technical.medical"`,
`derived_from_tiers: ["taboo.religious"]`. A bare top-level value (`"technical"`) is always valid
on its own — subcategories are opt-in, added only when a language's actual data earns them, never
invented speculatively. Nesting can go more than one level deep if warranted
(`"technical.medical.anatomy"`). **When a subcategory gets used by 2+ languages, list it under its
parent tier's row in the tables below** so it stops being implicit.

---

## 1. Usage tiers (for `established/` vocabulary entries)

Categorizes *where in the standard language* a given vocabulary entry sits — independent of raw
frequency. A word can be high-frequency and formal (function words), or low-frequency and
colloquial (a rare slang term), so `usage_tier` and `frequency`/`weight` are separate axes.

| Tier | Description |
|---|---|
| `core` | Basic, register-neutral vocabulary — usable in nearly any context |
| `formal` | Written/official/elevated register — legal, academic, ceremonial |
| `colloquial` | Everyday spoken register, informal but not slang |
| `technical` | Domain-specific jargon (trade, profession, hobby, science) — *subcategories: none yet promoted* |
| `regional` | Dialectal/regional variant not standard across the whole language area |
| `literary` | Poetic, archaic-flavored, or reserved for written/literary contexts |
| `archaic` | Historical usage, no longer in active standard use |
| `taboo` | Vulgar, profane, or socially restricted vocabulary — *subcategories: none yet promoted* |
| `slang` | Already-established slang that has entered common informal use (distinct from newly
  synthesized slang in `synthesized/`) |

## 2. Slang-derivation types (for `analysis/` mechanism entries)

Categorizes *which usage tier(s) a given slang-formation mechanism draws from* — i.e. what
"area" of the standard language it raids, inverts, compresses, or repurposes. Record in the
`analysis/` writeup's "Derived from tiers" field — a mechanism can draw from more than one tier,
list them all.

| Type | Description | Typical source tier(s) |
|---|---|---|
| `technical_leak` | Jargon from a specific trade/domain leaks into general informal use | `technical` |
| `taboo_inversion` | A taboo term repurposed, softened, or reclaimed | `taboo` |
| `euphemism_chain` | Successive euphemistic replacement of a taboo/sensitive core term | `taboo`, `core` |
| `phonological_reduction` | Clipping/contraction of an existing standard term | any |
| `semantic_shift` | An existing word's meaning drifts/extends into new slang use | any |
| `borrowing` | Term imported from another language or dialect | `regional`, foreign |
| `metaphor_productivity` | A specific standard-language semantic domain becomes a productive
  metaphor source (e.g. military, agriculture, cooking) | `core`, `technical` |
| `morphological_play` | Nonstandard affixation/word-formation on an existing standard root | `core` |
| `register_inversion` | A `formal`/`literary` term deployed ironically in low-register contexts | `formal`, `literary` |

**Both tables are starting points, not a closed set** — expect them to grow as real corpus work
begins. Add rows rather than stretching an existing one to cover a poor fit.

---

## Maintenance rule

**When a language's `analysis/` work identifies a genuinely new usage tier or derivation type not
listed here, add it in the same commit**, with a one-line note of which language surfaced it. The
same applies to subcategories that reach 2+ languages — promote them into the relevant row's
"subcategories" note rather than leaving them implicit in per-language shard data only.
