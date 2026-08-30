# Word-Concept & Morphological Typology Guide

**Purpose.** "Word" is not a stable cross-linguistic unit. A flat vocabulary table assumes each
row is one atomic lexical item — that assumption breaks down badly for many languages this project
will cover. This guide exists so extraction and analysis correctly interpret what counts as "one
lexical item" *for a given language*, instead of silently importing an English-shaped assumption
into every language's data.

**The concrete case that prompted this (Finnish):** `pikkupukkikaupungissamme` is one
orthographic "word," glossing to the entire English phrase "in our small goat-town." It decomposes
as `pikku` (small) + `pukki` (goat) + `kaupunki→kaupungi-` (town, stem-altered) + `-ssa` (inessive
case, "in") + `-mme` (1st person plural possessive, "our"). Treating this as a single opaque
vocabulary entry — the way `established/` tables treat, say, English "goat" — would lose the
entire internal structure that a mechanics-analysis pass actually needs to reason about
morphological slang formation in Finnish.

---

## Typology categories (starting point, not exhaustive)

Most real languages sit on a continuum or mix strategies rather than falling cleanly into one
bucket — use these as orientation, not a rigid checklist, and note genuine mixed/borderline cases
rather than forcing a single label.

| Typology | Roughly | Example behavior |
|---|---|---|
| `isolating` | Little to no inflection; grammatical relationships mostly shown by word order and separate function words | Vietnamese, Mandarin — each morpheme is usually its own orthographic word |
| `agglutinative` | Grammatical meaning built by stringing together separable morphemes, each with one clear function, minimal fusion between them | Finnish, Turkish, Hungarian, Korean, Japanese — a single "word" can correspond to a whole English phrase/clause |
| `fusional` | Grammatical categories merged into single affixes that can't be cleanly split into one-morpheme-one-function pieces | Most Slavic languages (Serbian/Croatian/Bosnian, Russian, Polish), Latin, most Romance languages — case/number/gender often fused into one ending |
| `polysynthetic` | Extreme morpheme-per-word density; a single word can encode what English needs a full sentence for, often incorporating what would be separate arguments/objects in English | Many indigenous American and some Siberian/Arctic languages — check per-language whether any staged reference material falls here |

**A language can (and often does) mix these** — e.g. a fusional language with some agglutinative
derivational morphology layered on top. Record what's actually observed, not which single category
"wins."

## Where this lives per language

**Record a language's typology profile during Phase 0 triage**, alongside the book catalog — add a
"Morphological Typology" note to that language's `00_Extraction_Checklist.md` (see
`_TEMPLATE/00_Extraction_Checklist.md`). This should be a short characterization (which category or
mix applies, with one or two concrete examples if available), not a full grammatical treatise —
detailed treatment belongs in the actual `established/` grammar-points sections.

## How this affects `established/` extraction

For any word-form that is itself a composed unit worth decomposing (agglutinative or polysynthetic
languages especially, but also complex fusional forms when genuinely informative), the vocabulary
table's `Term` row should be accompanied by a **Morpheme Breakdown** note — either an extra column
or an inline `Notes` entry — showing the segmentation and per-morpheme gloss, the same way the
Finnish example above was decomposed. **Don't force this on every entry** — a simple, non-composed
lexical item doesn't need a breakdown. Use it when the surface "word" is doing compositional work
an atomic gloss would hide.

## How this affects mechanics analysis (`analysis/`)

The `morphological_play` slang-derivation type in `00_Usage_Tier_Taxonomy.md` means something
substantially different depending on a language's typology:

- In an **agglutinative** language, rich, productive morphological combination is already a normal
  feature of the *standard* language — slang-specific morphological play needs to be distinguished
  from ordinary grammatical productivity, not just "any word with multiple morphemes."
- In an **isolating** language, morphological play is comparatively rare and therefore more
  marked/notable when it does occur as a slang mechanism.
- In a **fusional** language, nonstandard reanalysis or extension of an existing fusional pattern
  (e.g. applying a case ending in an unexpected way for effect) is itself a distinct, worth-noting
  mechanism.

When analyzing `morphological_play` for a given language, ground the finding in that language's own
typology rather than assuming what counts as "playful" morphology transfers directly from English or
from any other language already analyzed.

## Maintenance rule

If a language's reference material reveals a typology detail worth generalizing (a mixed-strategy
pattern that recurs across languages, a typology category not listed above), add it here — same
promotion discipline as `00_Usage_Tier_Taxonomy.md`.
