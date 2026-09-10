# Graph Report - Hungarian  (2026-09-09)

## Corpus Check
- 55 files · ~474,805 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 229 nodes · 332 edges · 10 communities
- Extraction: 79% EXTRACTED · 20% INFERRED · 0% AMBIGUOUS · INFERRED: 68 edges (avg confidence: 0.77)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- Colloquial Hungarian: Register & Coverb System
- Rounds/Kornai: Agglutinative Morphology Core
- Diaspora Hungarian: Borrowing Typology & Contact
- FSI Vol.2: Discourse Particles & Register
- Teach Yourself Hungarian: Address Register System
- FSI/Magyaróra: Colloquial & Taboo Vocabulary
- FSI/Magyaróra: Politeness & Loanword Verbalization
- Szólások és Közmondások: Idiom & Register Tagging
- FSI Vol.1: Socialist-Era Institutional Vocabulary
- Hungarian Verbs & Practical Grammar: Verb Morphology

## God Nodes (most connected - your core abstractions)
1. `Hungarian Language Contact Outside Hungary (Fenyvesi ed., 2005)` - 27 edges
2. `Established 008: On Hungarian Morphology Part 2 (Kornai)` - 17 edges
3. `Colloquial Hungarian (Rounds & Sólyom, 2002)` - 16 edges
4. `Teach Yourself Hungarian, 2nd ed. (Pontifex, 2003)` - 13 edges
5. `Established 007: On Hungarian Morphology Part 1 (Kornai)` - 11 edges
6. `Established 005: Verbs Part 2 (Rounds Ch.4)` - 10 edges
7. `Established 004: Verbs Part 1 (Rounds Ch.4)` - 9 edges
8. `Register/Dialect Tagging (ECH/SLH, rég/táj/nép/biz/durva/argó)` - 9 edges
9. `Socialist-Era Institutional Vocabulary (FSI Course)` - 9 edges
10. `Hungarian in Words and Pictures (Magyar nyelvkönyv, 1990)` - 9 edges

## Surprising Connections (you probably didn't know these)
- `jöjj marked 'practically extinct in colloquial Hungarian'` --semantically_similar_to--> `szia/szervusz cross-source register-dating disagreement`  [INFERRED] [semantically similar]
  established/051_hungarian_verbs_part1.md → established/047_hiwap_sample_late.md
- `Hungarian Book Triage Catalog` --references--> `Magyar szólások és közmondások (O. Nagy Gábor)`  [EXTRACTED]
  00_Book_Triage_Catalog.md → established/009_szolasok_kozmondasok_part1.md
- `Conditional Mood as Politeness-Raising Strategy` --conceptually_related_to--> `Te/Maga/Ön Politeness-Register System`  [INFERRED]
  established/023_magyarora_sample_late.md → established/013_fsi_vol1_units01-04.md
- `Mizujs (casual contracted greeting)` --semantically_similar_to--> `Dehogy / sőt as colloquial discourse particles`  [INFERRED] [semantically similar]
  established/021_magyarora_sample_early.md → established/018_fsi_vol2_units21-24.md
- `panyika address-term gap-filling borrowing (HS)` --semantically_similar_to--> `te/maga/ön three-way second-person address register system`  [INFERRED] [semantically similar]
  established/027_hungarian_language_contact_part1.md → established/034_tyh_units01-05.md

## Hyperedges (group relationships)
- **Flagship Morphological Findings: Lowering Diacritic + Derivational Stacking** — hungarian_established_005_chapter4_verbs_part2, hungarian_established_007_on_hungarian_morphology_part1, hungarian_established_008_on_hungarian_morphology_part2, concept_lowering_diacritic, concept_productive_derivational_endings, concept_derivational_vs_inflectional_suffix_ordering [INFERRED 0.85]
- **Vowel Harmony Documented Across Pedagogical and Theoretical Sources** — hungarian_established_001_chapters1_3_phonology_vowel_harmony, hungarian_established_002_chapter5_nouns, hungarian_established_003_chapter6_case_system, hungarian_established_007_on_hungarian_morphology_part1, concept_vowel_harmony [INFERRED 0.85]
- **Szólások és Közmondások Register-Tagging System Across Chunks** — hungarian_established_009_szolasok_kozmondasok_part1, hungarian_established_010_szolasok_kozmondasok_part2, hungarian_established_011_szolasok_kozmondasok_part3, hungarian_established_012_szolasok_kozmondasok_part4, concept_register_tagging_taxonomy [INFERRED 0.85]
- **FSI Course Socialist-Era Institutional Vocabulary Cluster** — datasets_hungarian_established_013_fsi_vol1_units01_04_socialist_era_institutional_vocabulary, datasets_hungarian_established_013_fsi_vol1_units01_04_maszek_vocab, datasets_hungarian_established_013_fsi_vol1_units01_04_uttoro_aruhaz_vocab, datasets_hungarian_established_015_fsi_vol1_units09_12_kulak_vocab, datasets_hungarian_established_015_fsi_vol1_units09_12_munkaverseny_vocab, datasets_hungarian_established_016_fsi_vol2_units13_16_uzemi_ebed_vocab, datasets_hungarian_established_016_fsi_vol2_units13_16_lakashivatal_kiutalni_vocab, datasets_hungarian_established_016_fsi_vol2_units13_16_altalanos_gimnazium_vocab [INFERRED 0.85]
- **Hungarian Taboo-Intensifier and 'Drunk' Register Ladders** — datasets_hungarian_established_021_magyarora_sample_early_taboo_intensifier_scale, datasets_hungarian_established_021_magyarora_sample_early_kurva_jo_vocab, datasets_hungarian_established_021_magyarora_sample_early_szar_vulgaris_vocab, datasets_hungarian_established_021_magyarora_sample_early_a_kurva_eletbe_vocab, datasets_hungarian_established_022_magyarora_sample_mid_drunk_register_ladder, datasets_hungarian_established_022_magyarora_sample_mid_pias_vocab, datasets_hungarian_established_022_magyarora_sample_mid_ittas_vocab, datasets_hungarian_established_022_magyarora_sample_mid_reszeg_vocab [EXTRACTED 1.00]
- **Hungarian Politeness-Register Continuum (te/maga/ön/archaic/tegez-magaz)** — datasets_hungarian_established_013_fsi_vol1_units01_04_te_maga_on_politeness_system, datasets_hungarian_established_022_magyarora_sample_mid_tegez_magaz_register_system, datasets_hungarian_established_025_complete_practical_grammar_part1_archaic_address_forms, datasets_hungarian_established_025_complete_practical_grammar_part1_kegyed_vocab, datasets_hungarian_established_015_fsi_vol1_units09_12_on_vs_maga_formality_shift, datasets_hungarian_established_023_magyarora_sample_late_conditional_mood_politeness [INFERRED 0.85]
- **gyerek→dzserek consonant-affrication convergence across independent contact varieties (Vojvodina, Oberwart, McKeesport AH, Australia)** — established_028_hungarian_language_contact_part2_gyerek_dzserek_affrication, established_029_hungarian_language_contact_ch8_austria_noun_class_leveling, established_030_hungarian_language_contact_ch9_usa_part1_dzserek_possessive_loss, established_032_hungarian_language_contact_ch10_australia_dzserek_merger_fourth_instance [INFERRED 0.85]
- **de Groot's Ch.11 synthesis: three separately-documented HO symptoms unified as one Appositional→Free-Pronoun person-marking shift** — established_033_hungarian_language_contact_ch11_grammars_appositional_free_pronoun_shift, established_029_hungarian_language_contact_ch8_austria_narrow_user_semi_speaker, established_030_hungarian_language_contact_ch9_usa_part1_causal_taxonomy [INFERRED 0.85]
- **Hungarian formality/address-register ecosystem documented convergently across independent pedagogical sources** — established_034_tyh_units01_05_te_maga_on_register, established_035_tyh_units06_11_courtesy_address_tetszik, established_039_colloquial_hu_intro_units01_02_pertut_inni_ritual [INFERRED 0.75]
- **'Group of seven' fully-irregular verb paradigm class across sources** — datasets_hungarian_established_044_colloquial_hu_units_f_backmatter_case_declension_13, datasets_hungarian_established_051_hungarian_verbs_part1_book, datasets_hungarian_established_052_hungarian_verbs_part2_verb_index_classification, datasets_hungarian_established_053_practical_hungarian_grammar_book [INFERRED 0.75]
- **szervusz/szia register-dating disagreement across independent sources** — datasets_hungarian_established_045_hiwap_sample_early_szervusz_no_period_marking, datasets_hungarian_established_047_hiwap_sample_late_szia_glossary_entry, datasets_hungarian_established_047_hiwap_sample_late_szervusz_glossary_entry, datasets_hungarian_established_047_hiwap_sample_late_szia_szervusz_disagreement [INFERRED 0.85]
- **Coverb/preverb directional-and-idiom system documented across four files** — datasets_hungarian_established_041_colloquial_hu_units07_10_coverb_system, datasets_hungarian_established_042_colloquial_hu_units_d_past_tense_class_system, datasets_hungarian_established_048_hungarian_with_ease_part1_preverb_slang_formation, datasets_hungarian_established_051_hungarian_verbs_part1_coverb_idiom_opacity [INFERRED 0.75]

## Communities (10 total, 0 thin omitted)

### Community 0 - "Colloquial Hungarian: Register & Coverb System"
Cohesion: 0.07
Nodes (39): Colloquial Hungarian (Rounds & Sólyom, 2002), Definite vs. indefinite conjugation, -ik verb class, piros/vörös red color-pair political-register split, tessék multi-use pragmatics, Coverb system (directional + perfectivizing preverbs), Nine-way locative case system (inside/outside/near × toward/static/from), Possessive suffix system (singular + plural possessed) (+31 more)

### Community 1 - "Rounds/Kornai: Agglutinative Morphology Core"
Cohesion: 0.12
Nodes (37): On Hungarian Morphology (Kornai), Hungarian: An Essential Grammar (Rounds), Agglutinative Suffix Stacking, Hungarian Case System, Coverbs (Hungarian Verbal Prefixes), Definite/Indefinite Verb Conjugation, Derivational Order Meaningful, Inflectional Order Fixed, Irregular Verb Stem Classes (Group of Seven, -szik, v-stems) (+29 more)

### Community 2 - "Diaspora Hungarian: Borrowing Typology & Contact"
Cohesion: 0.09
Nodes (31): Lanstyák & Szabómihály borrowing typology (loanword/loanform/calque/loanblend/semantic loan/convergence), Csángó as a roofless, diffuse Ausbau-language, Hungarian Language Contact Outside Hungary (Fenyvesi ed., 2005), filesz/nyúl Csángó dialect-internal isogloss ('rabbit'), horcsica 'mustard' (HS loanword proper, illustrative), Overfulfilment of the norm / hypercorrection mechanism, panyika address-term gap-filling borrowing (HS), duduk 'stupid' (VH colloquial-domain Serbian borrowing) (+23 more)

### Community 3 - "FSI Vol.2: Discourse Particles & Register"
Cohesion: 0.09
Nodes (23): Közmondások (Proverbs) as colloquial/idiomatic register source, Conversational discourse particles (hiszen/pláne/apropó/dehogy/sőt), Diminutive suffixes (-ka/-ke/-cska/-cske) as affection marker, FSI Hungarian Basic Course Vol.2, Units 17-20, Jézus-Mária (colloquial exclamation of surprise/dismay), Alkudni (informal marketplace bargaining register), Dehogy / sőt as colloquial discourse particles, FSI Hungarian Basic Course Vol.2, Units 21-24 (+15 more)

### Community 4 - "Teach Yourself Hungarian: Address Register System"
Cohesion: 0.12
Nodes (22): krumpli (colloquial) vs. burgonya (formal/menu) 'potato' register pair, Hungarian cardinal/ordinal agglutinative numeral system, Teach Yourself Hungarian, 2nd ed. (Pontifex, 2003), te/maga/ön three-way second-person address register system, tetszik + infinitive third ('courtesy') address system, -ka/-ke diminutive first-name affection/familiarity system, jár vs. megy habitual/one-off aspectual verb pair, kicsi→kicsik irregular adjective plural (illustrative) (+14 more)

### Community 5 - "FSI/Magyaróra: Colloquial & Taboo Vocabulary"
Cohesion: 0.11
Nodes (20): Definite vs. Indefinite Verb Conjugation, FSI Hungarian Basic Course Vol.1, Units 5-8, Hungarian Possessive Suffix System, Verbal Prefix (Preverb/Igekötő) Aspect System, Viccelni (to joke) - rare colloquial-register verb, A kurva életbe (vulgáris) - taboo curse phrase, Magyaróra / New Paths to the Hungarian Language (early sample), International (Latinate) vs. Native Hungarian Trait-Vocabulary Doublets (+12 more)

### Community 6 - "FSI/Magyaróra: Politeness & Loanword Verbalization"
Cohesion: 0.11
Nodes (19): Kezét csókolom (formal greeting idiom), Te/Maga/Ön Politeness-Register System, Ön vs. Maga formality distinction (single porter usage), Generálozni (denominal loan-verb 'to overhaul'), Colloquial Clipping Word-Formation (köszi/bocs/mobil/rögzítő), Denominal Loanword Verbalization (-ez/-el/-öl), Magyaróra / New Paths to the Hungarian Language (mid sample), Three-Tier 'Drunk' Register Ladder (ittas/részeg/piás) (+11 more)

### Community 7 - "Szólások és Közmondások: Idiom & Register Tagging"
Cohesion: 0.28
Nodes (15): Magyar szólások és közmondások (O. Nagy Gábor), Euphemism Chain Pattern (Body-Part/Object Imagery for Taboo Topics), Placename/Proper-Name-Anchored Fixed Similes, Register/Dialect Tagging (ECH/SLH, rég/táj/nép/biz/durva/argó), Established 009: Szólások és Közmondások Part 1, Established 010: Szólások és Közmondások Part 2, Established 011: Szólások és Közmondások Part 3, Established 012: Szólások és Közmondások Part 4 (+7 more)

### Community 8 - "FSI Vol.1: Socialist-Era Institutional Vocabulary"
Cohesion: 0.20
Nodes (14): FSI Hungarian Basic Course Vol.1, Units 1-4, Hungarian Double Negation as Standard Grammar, MASZEK (private-sector business), Socialist-Era Institutional Vocabulary (FSI Course), Úttörő Áruház (Pioneer Department Store), FSI Hungarian Basic Course Vol.1, Units 9-12, Kulák (Soviet-derived pejorative for wealthy peasant), Munkaverseny (socialist labor competition) (+6 more)

### Community 9 - "Hungarian Verbs & Practical Grammar: Verb Morphology"
Cohesion: 0.28
Nodes (9): Hungarian Verbs and Essentials of Grammar, Coverb+verb idiomatic-opacity pattern (kicsinál/átver), jöjj marked 'practically extinct in colloquial Hungarian', Reflexive verb-forming suffixes as their own productive category, focizik — denominal -ik verb from clipped sport-name noun, Verb Index as reverse-lookup morphological classification key, Practical Hungarian Grammar (Törkenczy, 2002), Complex verb construction (nominal + van, missing copula) (+1 more)

## Ambiguous Edges - Review These
- `piros/vörös red color-pair political-register split` → `baszik listed matter-of-factly with no register flag`  [AMBIGUOUS]
  established/053_practical_hungarian_grammar.md · relation: semantically_similar_to

## Knowledge Gaps
- **66 isolated node(s):** `szeretem/szerettem consonant-length minimal pair`, `"Nem esik messze az alma a fájától" (apple/tree proverb)`, `legeslegeslegeslegnagyobb (iterated ultra-superlative)`, `"Füstbe megy" / "Csak úgy füstölt" (register-decay-flagged idiom)`, `MASZEK (private-sector business)` (+61 more)
  These have ≤1 connection - possible missing edges or undocumented components.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **What is the exact relationship between `piros/vörös red color-pair political-register split` and `baszik listed matter-of-factly with no register flag`?**
  _Edge tagged AMBIGUOUS (relation: semantically_similar_to) - confidence is low._
- **Why does `Te/Maga/Ön Politeness-Register System` connect `FSI/Magyaróra: Politeness & Loanword Verbalization` to `FSI Vol.1: Socialist-Era Institutional Vocabulary`, `FSI Vol.2: Discourse Particles & Register`?**
  _High betweenness centrality (0.049) - this node is a cross-community bridge._
- **Why does `Dehogy / sőt as colloquial discourse particles` connect `FSI Vol.2: Discourse Particles & Register` to `FSI/Magyaróra: Colloquial & Taboo Vocabulary`?**
  _High betweenness centrality (0.037) - this node is a cross-community bridge._
- **Are the 2 inferred relationships involving `Established 008: On Hungarian Morphology Part 2 (Kornai)` (e.g. with `Established 004: Verbs Part 1 (Rounds Ch.4)` and `utazzam (archaic vs. regular -ik-verb subjunctive)`) actually correct?**
  _`Established 008: On Hungarian Morphology Part 2 (Kornai)` has 2 INFERRED edges - model-reasoned connections that need verification._
- **Are the 2 inferred relationships involving `Established 007: On Hungarian Morphology Part 1 (Kornai)` (e.g. with `Established 002: Nouns (Rounds Ch.5)` and `Derivational Order Meaningful, Inflectional Order Fixed`) actually correct?**
  _`Established 007: On Hungarian Morphology Part 1 (Kornai)` has 2 INFERRED edges - model-reasoned connections that need verification._
- **What connects `szeretem/szerettem consonant-length minimal pair`, `"Nem esik messze az alma a fájától" (apple/tree proverb)`, `legeslegeslegeslegnagyobb (iterated ultra-superlative)` to the rest of the system?**
  _66 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Colloquial Hungarian: Register & Coverb System` be split into smaller, more focused modules?**
  _Cohesion score 0.06747638326585695 - nodes in this community are weakly interconnected._