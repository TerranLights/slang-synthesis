# Ilocano — Phase 1 Extraction Checklist

**Status: Phase 1 complete, 2026-10-30.** First-ever extraction pass for this language, done in a
single wave (I1, 19 files) across both triaged source books. Full incident/seam-audit detail in
`00_RESUME_HERE.md`.

## Sources

1. **A Reference Grammar of Ilocano** — Carl Ralph Galvez Rubino, 1997 UCSB PhD dissertation, 549
   PDF pages, no text layer (full vision-read). Files 001-012.
2. **Ilocano Dictionary and Grammar, Ilocano-English/English-Ilocano** — Carl Rubino, 2000,
   University of Hawaiʻi Press PALI Language Texts series, 868 PDF pages, real OCR text layer
   (vision for the Grammar Outline, pdftotext for the dictionary body). Files 013-019.

## File 1 — Reference Grammar (full coverage, all 18 chapters + front/back matter)

| # | Scope | Words |
|---|---|---|
| 001 | Front matter (Abstract, TOC) + Ch.1 Introduction + Ch.2 Phonology | 13,071 |
| 002 | Ch.3 Articles/Demonstratives/Case + Ch.4 Pronouns (flagship: fused ergative×absolutive portmanteau clitics) | 7,304 |
| 003 | Ch.5 Nouns (dense derivational-morphology chapter, ~30 affix patterns) | 34,369 |
| 004 | Ch.6 Adjectives (flagship: ~90-item bodily-anomaly descriptor field) | 20,828 |
| 005 | Ch.7 Numbers (flagship: dual native/Spanish numeral system with borrowed Spanish gender agreement) | 9,848 |
| 006 | Ch.8a Verbs — Focus and transitivity, intransitive/transitive affixes (flagship: *maki-* comitative cluster, the language's core trigger system) | 29,059 |
| 007 | Ch.8b Verbs — Detransitivization, *pa-* causation, Aspect, all 14 irregular verbs, nominalization | 21,334 |
| 008 | Ch.9 Adverbs (flagship: dense discourse-particle/politeness-register chapter) | 10,025 |
| 009 | Ch.10 Existentials + Ch.11 Sentence types (flagship: interjections, social formulas, privacy-convention greeting norms) | 13,911 |
| 010 | Ch.12 Imperatives + Ch.13 Negation + Ch.14 Interrogativity (flagship: three-tier imperative politeness system) | 12,532 |
| 011 | Ch.15 Transitivity/Voice + Ch.16 Reciprocals + Ch.17 Reflexives + Ch.18 Clause combining | 11,694 |
| 012 | Glossary (112-entry linguistic-terms glossary, reproduced in full) + References + Map Appendix + Index | 7,899 |

**Subtotal: 192,874 words.**

## File 2 — Dictionary and Grammar (Grammar Outline full coverage; Dictionary representative sampling)

| # | Scope | Method | Words |
|---|---|---|---|
| 013 | Grammar Outline pt.1 — Intro, Phonology, Pronouns, start of Nouns | vision | 18,960 |
| 014 | Grammar Outline pt.2 — Nouns through Coordination, incl. the Abbreviations key | vision | 20,808 |
| 015 | Ilocano-English dictionary sample 1 (A– through early-mid alphabet) | pdftotext | 9,116 |
| 016 | Ilocano-English dictionary sample 2 (mid-alphabet, I–P) | pdftotext | 8,923 |
| 017 | Ilocano-English dictionary sample 3 (S–Y; confirmed I-E/E-I boundary at PDF p.735→739) | pdftotext | 10,483 |
| 018 | English-Ilocano dictionary sample (confirmed boundary at PDF p.840→841) | pdftotext | 8,327 |
| 019 | Back matter — Traditional Ilocano Songs ("Kankanta Nga Iloko"), Appendixes | pdftotext/vision | 7,197 |

**Subtotal: 82,814 words.**

**Grand total: 275,688 words across 19 established files.**

## Flagship findings

- **The *maki-* comitative verb cluster** (file 006) — seven named sub-derivations (simple,
  reciprocal, desiderative, social, communal-task, pretentative, transference), a fully elaborated
  comitative macro-role with no counterpart yet found in this project's Tagalog material.
- **Reduplication multiplexing five distinct grammatical jobs** (file 007) — imperfective,
  frequentative, recent-past, plurality, and intensity/distributivity, richer than Tagalog's
  three-way reduplication system.
- **Fused ergative×absolutive pronoun portmanteaus** (file 002) — an 8×8 table of historically
  fused actor+patient enclitic pairs, a real-world precedent for compressed pronoun-pair clitics.
- **Dual native/Spanish numeral system** (file 005) — native numerals obligatory for
  derivational morphology, Spanish-loan numerals obligatory for time/dates and preferred for ages
  and large prices, with Spanish ordinals retaining Spanish grammatical gender agreement despite
  Ilocano having no native gender system.
- **Hawaii-contact data** (files 001, 015, 016): Ch.1's explicit statement that one-fifth of
  Hawaii's population is Ilocano-descended and that Ilocano is taught in Hawaii schools; dictionary
  entries *Aloha*, *Haway*/*Hawayano*, *kanaka* ("Hawaiian use only"), and a worked example sentence
  about Ilocano customs changing "here in Hawai'i."
- **Substantial slang/taboo register material** across the dictionary sample files (015-018):
  sexual/anatomical taboo vocabulary, an explicit ethnic slur flagged by the dictionary itself
  (*panggalatot*, derogatory toward Pangasinan speakers), syllable-reversal slang coinages, drug and
  sex-work slang, and WWII-occupation-era currency/weapon slang.
- **Traditional-song genre vocabulary** (file 019) — *duayya* (lullaby), *dung-aw* (dirge),
  *as-asug* (lament-of-the-dead), with documented oral-tradition textual variation (footnoted
  alternate lines/titles).

## Known gaps / future work

- Dictionary sampling (015-018) is representative, not exhaustive, per this project's standing
  convention for oversized dictionaries — a denser follow-up pass is a candidate for later revisit
  if initial coverage proves thin relative to the dictionary's real richness (same caveat logged for
  Korean and Hawaiian).
- A second confirmed duplicate book (File 3 in the original triage) was deliberately not extracted
  — redundant scan of File 2 with no text layer.
