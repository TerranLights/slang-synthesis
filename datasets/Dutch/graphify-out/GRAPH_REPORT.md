# Graph Report - Dutch  (2026-08-30)

## Corpus Check
- Corpus is ~21,240 words - fits in a single context window. You may not need a graph.

## Summary
- 39 nodes · 61 edges · 5 communities
- Extraction: 92% EXTRACTED · 8% INFERRED · 0% AMBIGUOUS · INFERRED: 5 edges (avg confidence: 0.83)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- Diminutives & Vowel Length
- Colloquial Register & Particles
- Book Triage Catalog
- Phonology, Spelling & Plurals
- Extraction Checklist Meta

## God Nodes (most connected - your core abstractions)
1. `Ch.1-3: Pronunciation, Spelling, The Plural (Established Vocabulary/Grammar)` - 12 edges
2. `Ch.22: Diminutives (Established Vocabulary/Grammar)` - 10 edges
3. `Ch.16: Colloquial Speech and Writing (Established Vocabulary/Grammar)` - 9 edges
4. `Dutch Reference Material Triage Catalog` - 6 edges
5. `Dutch Slang Mechanics Extraction Checklist` - 6 edges
6. `Dutch: An Essential Grammar (Shetter & Van der Cruysse-Van Antwerpen)` - 5 edges
7. `Diminutive Suffix System (Productive Derivational Morphology)` - 5 edges
8. `Diminutive Allomorph Selection (-je/-tje/-etje/-pje)` - 5 edges
9. `Closed/Open Syllable Spelling Logic` - 4 edges
10. `Plural in -en (Default Strategy)` - 4 edges

## Surprising Connections (you probably didn't know these)
- `Ch.1-3: Pronunciation, Spelling, The Plural (Established Vocabulary/Grammar)` --cites--> `Dutch: An Essential Grammar (Shetter & Van der Cruysse-Van Antwerpen)`  [EXTRACTED]
  established/001_chapters1-3_pronunciation_spelling_plural.md → 00_Book_Triage_Catalog.md
- `Ch.16: Colloquial Speech and Writing (Established Vocabulary/Grammar)` --cites--> `Dutch: An Essential Grammar (Shetter & Van der Cruysse-Van Antwerpen)`  [EXTRACTED]
  established/002_chapter16_colloquial_speech.md → 00_Book_Triage_Catalog.md
- `Ch.22: Diminutives (Established Vocabulary/Grammar)` --cites--> `Dutch: An Essential Grammar (Shetter & Van der Cruysse-Van Antwerpen)`  [EXTRACTED]
  established/003_chapter22_diminutives.md → 00_Book_Triage_Catalog.md
- `Dutch Slang Mechanics Extraction Checklist` --cites--> `Ch.1-3: Pronunciation, Spelling, The Plural (Established Vocabulary/Grammar)`  [EXTRACTED]
  00_Extraction_Checklist.md → established/001_chapters1-3_pronunciation_spelling_plural.md
- `Dutch Slang Mechanics Extraction Checklist` --cites--> `Ch.16: Colloquial Speech and Writing (Established Vocabulary/Grammar)`  [EXTRACTED]
  00_Extraction_Checklist.md → established/002_chapter16_colloquial_speech.md

## Hyperedges (group relationships)
- **Colloquial/Register Marking Recurs Across the Particles and Diminutives Chapters** — datasets_dutch_established_002_chapter16_colloquial_speech_usage_tier_diversity_finding, datasets_dutch_established_002_chapter16_colloquial_speech_discourse_particle_system, datasets_dutch_established_003_chapter22_diminutives_diminutive_personalizing_suffix, datasets_dutch_established_003_chapter22_diminutives_diminutive_as_adverb_construction [INFERRED 0.85]
- **Vowel Length Tracks Morphological Form Across Plural and Diminutive Formation** — datasets_dutch_established_001_chapters1_3_pronunciation_spelling_plural_plural_irregular_vowel_lengthening, datasets_dutch_established_001_chapters1_3_pronunciation_spelling_plural_closed_open_syllable_spelling, datasets_dutch_established_003_chapter22_diminutives_vowel_length_alternation_diminutive [INFERRED 0.85]

## Communities (5 total, 0 thin omitted)

### Community 0 - "Diminutives & Vowel Length"
Cohesion: 0.29
Nodes (10): Plural in -eren, Incl. Meaning-Differentiated Doublets, Irregular Vowel-Lengthening Plurals, bloempje/bloemetje Rule-vs-Usage Split, Diminutive Allomorph Selection (-je/-tje/-etje/-pje), Diminutive-Derived Adverb Construction (+ -s), Diminutive as Personalizing Suffix (Attitude/Stance Marking), Diminutive Semantic Drift and Full Lexicalization, Ch.22: Diminutives (Established Vocabulary/Grammar) (+2 more)

### Community 1 - "Colloquial Register & Particles"
Cohesion: 0.31
Nodes (9): engerd ("creep" — colloquial-tagged vocabulary example), Dutch Discourse Particle System (eens, even, maar, toch, wel), Ch.16: Colloquial Speech and Writing (Established Vocabulary/Grammar), hoor (reassurance tag particle), mekaar (colloquial contraction of elkaar), Particle Combination/Stacking and Placement Rules, Particle toch (Stress-Conditioned Meaning), Colloquial-Register Chapter Surfaces Usage Tier Diversity (+1 more)

### Community 2 - "Book Triage Catalog"
Cohesion: 0.29
Nodes (8): Basic Dutch: A Grammar and Workbook, Colloquial Dutch, Dutch: A Comprehensive Grammar, Dutch Reference Material Triage Catalog, Dutch Reference Grammar, Dutch: An Essential Grammar (Shetter & Van der Cruysse-Van Antwerpen), pdftotext Stray Digit Prefix Extraction Quirk, The Phonology of Dutch

### Community 3 - "Phonology, Spelling & Plurals"
Cohesion: 0.43
Nodes (7): Assimilation (Voicing Agreement Across Consonant Clusters), Closed/Open Syllable Spelling Logic, Ch.1-3: Pronunciation, Spelling, The Plural (Established Vocabulary/Grammar), F/V and S/Z Consonant Alternation, Plural in -en (Default Strategy), Latin-Derived and Stress-Shifting Plurals (-i/-a/-heden), reden/redden Minimal-Pair Spelling Example

### Community 4 - "Extraction Checklist Meta"
Cohesion: 0.50
Nodes (5): Diminutive Suffix System (Productive Derivational Morphology), Dutch Slang Mechanics Extraction Checklist, Dutch Morphological Typology (Analytic/Mildly Fusional), Usage-Tier / Slang-Type Categorization Scheme, Plural in -s (Three Subgroups Incl. All Diminutives)

## Knowledge Gaps
- **9 isolated node(s):** `Basic Dutch: A Grammar and Workbook`, `The Phonology of Dutch`, `Dutch Reference Grammar`, `Colloquial Dutch`, `Usage-Tier / Slang-Type Categorization Scheme` (+4 more)
  These have ≤1 connection - possible missing edges or undocumented components.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Dutch: An Essential Grammar (Shetter & Van der Cruysse-Van Antwerpen)` connect `Book Triage Catalog` to `Diminutives & Vowel Length`, `Colloquial Register & Particles`, `Phonology, Spelling & Plurals`?**
  _High betweenness centrality (0.404) - this node is a cross-community bridge._
- **Why does `Ch.1-3: Pronunciation, Spelling, The Plural (Established Vocabulary/Grammar)` connect `Phonology, Spelling & Plurals` to `Diminutives & Vowel Length`, `Colloquial Register & Particles`, `Book Triage Catalog`, `Extraction Checklist Meta`?**
  _High betweenness centrality (0.380) - this node is a cross-community bridge._
- **Why does `Ch.16: Colloquial Speech and Writing (Established Vocabulary/Grammar)` connect `Colloquial Register & Particles` to `Book Triage Catalog`, `Extraction Checklist Meta`?**
  _High betweenness centrality (0.296) - this node is a cross-community bridge._
- **What connects `Basic Dutch: A Grammar and Workbook`, `The Phonology of Dutch`, `Dutch Reference Grammar` to the rest of the system?**
  _9 weakly-connected nodes found - possible documentation gaps or missing edges._