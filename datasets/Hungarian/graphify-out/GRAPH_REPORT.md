# Graph Report - Hungarian  (2026-08-30)

## Corpus Check
- Corpus is ~23,259 words - fits in a single context window. You may not need a graph.

## Summary
- 31 nodes · 56 edges · 6 communities
- Extraction: 93% EXTRACTED · 7% INFERRED · 0% AMBIGUOUS · INFERRED: 4 edges (avg confidence: 0.88)
- Token cost: 21,000 input · 7,500 output

## Community Hubs (Navigation)
- Reference Docs & Case-Stacking Examples
- The Case System (Chapter 6)
- Nouns & Suffixing (Chapter 5)
- Consonant Length & Assimilation
- Phonology Doc & Sound Rules
- Vowel Harmony

## God Nodes (most connected - your core abstractions)
1. `Chapters 1-3: Phonology and Vowel Harmony` - 12 edges
2. `Chapter 6: The Case System` - 10 edges
3. `Chapter 5: Nouns` - 8 edges
4. `Hungarian Extraction Checklist` - 7 edges
5. `Agglutination / Suffix Stacking` - 6 edges
6. `The Hungarian Case System (23 cases)` - 6 edges
7. `Rounds - Hungarian: An Essential Grammar (2nd ed., 2009)` - 5 edges
8. `Vowel Harmony` - 5 edges
9. `Consonant Length (Gemination)` - 4 edges
10. `v-Assimilation of Instrumental (-val/-vel) and Translative (-va/-ve) Suffixes` - 4 edges

## Surprising Connections (you probably didn't know these)
- `Hungarian Extraction Checklist` --references--> `Chapters 1-3: Phonology and Vowel Harmony`  [EXTRACTED]
  00_Extraction_Checklist.md → established/001_chapters1-3_phonology_vowel_harmony.md
- `Hungarian Extraction Checklist` --references--> `Chapter 5: Nouns`  [EXTRACTED]
  00_Extraction_Checklist.md → established/002_chapter5_nouns.md
- `Hungarian Extraction Checklist` --references--> `Chapter 6: The Case System`  [EXTRACTED]
  00_Extraction_Checklist.md → established/003_chapter6_case_system.md
- `Chapters 1-3: Phonology and Vowel Harmony` --cites--> `Rounds - Hungarian: An Essential Grammar (2nd ed., 2009)`  [EXTRACTED]
  established/001_chapters1-3_phonology_vowel_harmony.md → 00_Book_Triage_Catalog.md
- `Chapter 5: Nouns` --cites--> `Rounds - Hungarian: An Essential Grammar (2nd ed., 2009)`  [EXTRACTED]
  established/002_chapter5_nouns.md → 00_Book_Triage_Catalog.md

## Hyperedges (group relationships)
- **Vowel harmony as a cross-chapter governing mechanism** — datasets_hungarian_established_001_chapters1_3_phonology_vowel_harmony_vowel_harmony, datasets_hungarian_established_002_chapter5_nouns_noun_stem_classes, datasets_hungarian_established_003_chapter6_case_system_case_system_overview [INFERRED 0.85]
- **Agglutinative suffix-stacking demonstrated across all three chapters** — datasets_hungarian_established_002_chapter5_nouns_agglutination_suffix_stacking, datasets_hungarian_established_002_chapter5_nouns_ismerosomhoz_baratnoideneknek_example, datasets_hungarian_established_003_chapter6_case_system_gyerekeire_triple_stack_example, datasets_hungarian_established_003_chapter6_case_system_konyvekben_case_stacking_example [INFERRED 0.85]
- **Hungarian consonant assimilation family (voicing, sibilant, pre-j gemination, v-assimilation)** — datasets_hungarian_established_001_chapters1_3_phonology_vowel_harmony_voicing_devoicing_assimilation, datasets_hungarian_established_001_chapters1_3_phonology_vowel_harmony_sibilant_assimilation, datasets_hungarian_established_001_chapters1_3_phonology_vowel_harmony_consonant_lengthening_before_j, datasets_hungarian_established_003_chapter6_case_system_v_assimilation_instrumental_translative [INFERRED 0.75]

## Communities (6 total, 0 thin omitted)

### Community 0 - "Reference Docs & Case-Stacking Examples"
Cohesion: 0.38
Nodes (7): Hungarian Book Triage Catalog, Magyar Szlengszotar (Hungarian Slang Dictionary), Rounds - Hungarian: An Essential Grammar (2nd ed., 2009), Hungarian Extraction Checklist, Agglutination / Suffix Stacking, gyerekeire triple-stack morpheme example, konyvekben / konyvemben case-after-plural/possessive example

### Community 1 - "The Case System (Chapter 6)"
Cohesion: 0.52
Nodes (7): The Hungarian Case System (23 cases), Chapter 6: The Case System, Inessive Case (-ban/-ben), Locative Cases Group (interior/exterior/near x motion-toward/static/motion-away), Oblique Cases Group (dative, instrumental, translative, causal-final, essive-formal, terminative, distributive, essive), v-Assimilation of Instrumental (-val/-vel) and Translative (-va/-ve) Suffixes, Verb/Case Government

### Community 2 - "Nouns & Suffixing (Chapter 5)"
Cohesion: 0.40
Nodes (6): Hungarian Article System (definite/indefinite/zero), Chapter 5: Nouns, ismerosomhoz / baratnoideknek suffix-stacking examples, lovak / lorol v-stem alternation example, Hungarian Noun Stem Classes (vowel-final, low-vowel, v-stem, -alom/-elem, fleeting-vowel, regular), Singular/Plural Usage Rules Beyond Count

### Community 3 - "Consonant Length & Assimilation"
Cohesion: 0.50
Nodes (4): adja/hagyja/mutatja worked paradigm (lengthening before j), Consonant Length (Gemination), Consonant Lengthening Before j, szeretem / szerettem minimal pair

### Community 4 - "Phonology Doc & Sound Rules"
Cohesion: 0.67
Nodes (4): Chapters 1-3: Phonology and Vowel Harmony, Assimilation of Sibilants, Hungarian Stress and Intonation Rules, Voicing and Devoicing Assimilation

### Community 5 - "Vowel Harmony"
Cohesion: 0.67
Nodes (3): asztalok/gyerekek/fuzetek/ismerosok/papirok five-stem harmony paradigm, Neutral Vowels in Vowel Harmony, Vowel Harmony

## Knowledge Gaps
- **1 isolated node(s):** `Magyar Szlengszotar (Hungarian Slang Dictionary)`
  These have ≤1 connection - possible missing edges or undocumented components.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Chapters 1-3: Phonology and Vowel Harmony` connect `Phonology Doc & Sound Rules` to `Reference Docs & Case-Stacking Examples`, `Consonant Length & Assimilation`, `Vowel Harmony`?**
  _High betweenness centrality (0.393) - this node is a cross-community bridge._
- **Why does `Chapter 6: The Case System` connect `The Case System (Chapter 6)` to `Reference Docs & Case-Stacking Examples`?**
  _High betweenness centrality (0.235) - this node is a cross-community bridge._
- **Why does `Chapter 5: Nouns` connect `Nouns & Suffixing (Chapter 5)` to `Reference Docs & Case-Stacking Examples`?**
  _High betweenness centrality (0.227) - this node is a cross-community bridge._
- **Are the 2 inferred relationships involving `Agglutination / Suffix Stacking` (e.g. with `gyerekeire triple-stack morpheme example` and `konyvekben / konyvemben case-after-plural/possessive example`) actually correct?**
  _`Agglutination / Suffix Stacking` has 2 INFERRED edges - model-reasoned connections that need verification._
- **What connects `Magyar Szlengszotar (Hungarian Slang Dictionary)` to the rest of the system?**
  _1 weakly-connected nodes found - possible documentation gaps or missing edges._