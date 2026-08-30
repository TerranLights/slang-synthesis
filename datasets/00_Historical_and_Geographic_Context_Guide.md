# Historical & Geographic Context Guide

**Purpose.** A slang term is not timeless or universal — a term perfectly natural in 1960 could be
completely alien in 1790, and a term in constant use in one city may be unknown a few hundred
kilometers away in the same language (Quebec City French vs. Marseille French; Shenzhen Mandarin
slang vs. Singaporean Mandarin slang). When this is knowable, it matters for analysis — a
mechanism that looks "universal" might actually be a regional or era-bound pattern once enough
entries carry this context.

**These fields are optional, not required.** Most slang collected from general web research will
not come with confidently attestable date/place attribution, and forcing the field would produce
either false precision (guessing an era/region without real basis) or noise (empty placeholders
everywhere). **Fill them in only when the source actually supports it** — a term explicitly dated
in a source, discussed as regional in a source, or drawn from a source with clear
temporal/geographic scope (a specific era's media, a region-specific forum/subtitle track).

## Fields

Added to `established/`, `analysis/` (on examples), and `synthesized/` (as `based_on_*` context)
entries:

| Field | Type | Meaning |
|---|---|---|
| `attested_era` | string or `null` | When the term is/was in use, as precisely as the source actually supports — `"1960s"`, `"1960s–1970s"`, `"contemporary (2020s)"`, `"pre-1900, exact period unclear"`. Use `null` when genuinely unknown, not a guess. |
| `attested_region` | array of strings or `null` | Where the term is/was in use, as specifically as the source supports — `["Quebec City", "Quebec (broader)"]`, `["Shenzhen", "Guangdong"]`. An array because a term can have multiple documented regions. `null` when unknown — most entries will legitimately be `null` here. |
| `geographic_scope` | string or `null` | Coarse classification when `attested_region` is populated: `local` (single city/small area), `regional` (province/state-sized or a defined dialect area), `national`, `transnational` (spans a language's speaker population across borders). Optional even when `attested_region` is known — only fill in if genuinely clear. |

**`null` is a legitimate, expected value — not a TODO.** Don't backfill these with a best guess to
avoid leaving them empty; an honestly-unknown field is more useful than a false one, especially
since wrong era/region attribution could actively mislead a later finding (e.g. wrongly treating a
1960s-only term as evidence of a still-active contemporary mechanism).

## Why this matters for analysis

If enough `established/`/`analysis/` entries carry real `attested_era`/`attested_region` data, it
becomes possible to notice things like: a `slang_type` (see
`00_Usage_Tier_Taxonomy.md`) that only shows up in one region's data but not another's; a mechanism
that was productive in one era and has since gone dormant; or a `synthesized/` term whose real-world
basis terms are actually era-bound in a way that should inform whether it's being used
anachronistically in the sci-fi setting. **None of this requires exhaustive coverage** — even a
handful of confidently-dated/placed entries per language can surface a pattern worth flagging in
the language's own `.md` writeups.

## Maintenance rule

If a later source contradicts an existing `attested_era`/`attested_region` value (e.g. a term
thought region-specific turns out to be broader), update the entry and note the correction — don't
silently overwrite without a trace, same discipline as `synthesized/`'s `revision_history`.
