# Graph Report - Serbian_Croatian_Bosnian  (2026-08-31)

## Corpus Check
- Large corpus: 117 files · ~850,625 words. Semantic extraction will be expensive (many Claude tokens). Consider running on a subfolder.

## Summary
- 453 nodes · 561 edges · 29 communities (25 shown, 4 thin omitted)
- Extraction: 78% EXTRACTED · 22% INFERRED · 0% AMBIGUOUS · INFERRED: 125 edges (avg confidence: 0.77)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- Colloquial Serbian: Idiom & Register
- Magner's Croatian/Serbian: Dialect Convention & Aorist
- Teach Yourself Serbian: Formality & Address Register
- BCS Grammar Core: Case, Aspect & Jat Reflex
- Flagship Textbook: Archaic Tenses & Aspect Pairing
- Serbian Folk Tales: Demonology & Taboo-Avoidance Naming
- Colloquial Croatian/Serbian: Case & Question Formation
- Hammond's Serbian: Dialect Groups & Karadžić Reform
- Standardization History: Alphabets & Illyrian Movement
- BCS Glossary Part 4-5: E/J and B/C/S Lexical Splits
- Colloquial Croatian/Serbian: Register-Tagged Idioms
- Naming Disputes & Pluricentric-Language Status
- Hammond's Serbian: Noun Declension Classes
- Grammar Supplement: Accent Notation & Clitic Model
- Grammar Supplement: Consonant Softening & Verb Types
- Hammond's Serbian: Pronoun & Adverb Series
- Hammond's Serbian: Consonant Mutation & Word Formation
- Case Review: Coffee-Word Regional Triplet & Prepositions
- Bosnia Chapter: Turcizmi & Bosniak Naming
- Word Formation: Derivational Suffix System
- Clitic Placement & Prosodic Accent Shift
- Grammar Supplement: Irregular Noun Alternations
- Hammond's Serbian: Case-Governed Number Nouns
- Hammond's Serbian: Numeral Category System
- Hammond's Serbian: Modal Verbs & Ići-Derivatives
- Hammond's Serbian: Syllabic R Vowel
- Hammond's Serbian: Adjective Taxonomy & Toast Formula
- Hammond's Serbian: Adverb & Preposition Classification
- Hammond's Serbian: Dates & Time-Telling

## God Nodes (most connected - your core abstractions)
1. `Bosnian, Croatian, Serbian, a Grammar with Sociolinguistic Commentary (Alexander, 2006)` - 36 edges
2. `Magner: Introduction to the Croatian and Serbian Language` - 36 edges
3. `Bosnian, Croatian, Serbian, a Textbook (Alexander & Elias-Bursać, 2010)` - 29 edges
4. `Alexander & Elias-Bursać, Bosnian Croatian Serbian: A Textbook (2010)` - 27 edges
5. `Српске народне бајке (Serbian Folk Fairy Tales, Kreativni centar 2000)` - 23 edges
6. `Colloquial Serbian (Hawkesworth & Ćalić, 2006)` - 22 edges
7. `Colloquial Croatian and Serbian (Hawkesworth, 1998)` - 17 edges
8. `Book's Colloquial-Register Framing and Priority` - 16 edges
9. `C/B/S and Ijekavian/Ekavian Dialect-Tagging Convention` - 16 edges
10. `Bosnian/Croatian/Serbian Regional Lexical-Variant Tagging` - 13 edges

## Surprising Connections (you probably didn't know these)
- `Extraction Checklist` --conceptually_related_to--> `[B]/[C]/[S] Dialect-Tagging Convention`  [INFERRED]
  00_Extraction_Checklist.md → established/004_lesson02.md
- `Adjective Comparison: Suffix -ij- and Consonant-Softening` --references--> `Alexander & Elias-Bursać, Bosnian Croatian Serbian: A Textbook (2010)`  [EXTRACTED]
  established/013_lesson11.md → 00_Book_Triage_Catalog.md
- `Inclinational se-Construction` --references--> `Alexander & Elias-Bursać, Bosnian Croatian Serbian: A Textbook (2010)`  [EXTRACTED]
  established/007_lesson05.md → 00_Book_Triage_Catalog.md
- `Prepositions of Motion Toward a Person (k/ka vs. do/kod)` --references--> `Alexander & Elias-Bursać, Bosnian Croatian Serbian: A Textbook (2010)`  [EXTRACTED]
  established/009_lesson07.md → 00_Book_Triage_Catalog.md
- `Reflexive Possessive svoj vs. njegov/njen` --references--> `Alexander & Elias-Bursać, Bosnian Croatian Serbian: A Textbook (2010)`  [EXTRACTED]
  established/007_lesson05.md → 00_Book_Triage_Catalog.md

## Hyperedges (group relationships)
- **BCS Case-System Concepts Forming One Coherent Grammatical Subsystem** — concept_genitive_case_uses, concept_dative_locative_instrumental_syncretism, concept_u_words_na_words, concept_dative_experiencer_construction [INFERRED 0.80]
- **BCS Verbal Tense/Aspect Machinery (Past, Future, Aspect, Conjugation Typology)** — concept_perfective_imperfective_aspect, concept_past_tense_l_participle, concept_future_tense_formation, concept_verb_conjugation_types_16, concept_clitic_second_position [INFERRED 0.85]
- **Belgrade/Teen Informal Kinship-Address Slang Cluster (Lesson 9)** — vocab_keva_belgrade_slang_mother, vocab_stara_stari_starci_teen_kinship, vocab_regional_father_terms [EXTRACTED 1.00]
- **BCS Pluricentric Variation System (E/J reflex + B/C/S lexical tagging + Montenegrin)** — established_014_lesson12_ekavian_ijekavian_alternation, established_014_lesson12_bcs_dialect_tagging_convention, established_021_lesson19_montenegrin_variant [INFERRED 0.85]
- **BCS Verb-Morphology Teaching Sequence (aspect, converbs, archaic pasts, conjugation types)** — established_014_lesson12_verbal_aspect_imperfective_perfective, established_014_lesson12_verbal_adverbs_present_past, established_014_lesson12_aorist_imperfect_past_tenses, established_024_appendix9_verb_types_conjugation_type_system [INFERRED 0.75]
- **Documented Slang Attestation via Bazdulj Story Footnote** — established_025_appendices7_8_literary_readings_syllable_switching_slang, established_025_appendices7_8_literary_readings_ljubav_na_spanjolski_nacin, established_014_lesson12_bcs_textbook [EXTRACTED 1.00]
- **BCS language-naming and identity politics across chapters 21-26** — established_033_socioling_ch23_bosnian_naming_dispute_concept, established_036_socioling_ch26_one_or_more_languages_s_c_language_concept, established_031_socioling_ch21_intro_writing_standardization_varijanta_concept [INFERRED 0.80]
- **East/West lexical variant pairs documented across sociolinguistic and grammar chapters** — established_032_socioling_ch22_dialect_differences_kava_kafa, established_032_socioling_ch22_dialect_differences_kazaliste_pozoriste, established_042_grammar_ch17_case_usage_review_kafa_kava_kahva, established_033_socioling_ch23_bosnian_kahva_kafa [INFERRED 0.85]
- **XYZ clitic-placement model formalized and extended across grammar chapters** — established_037_grammar_ch1_3_supplementary_doc, established_039_grammar_ch7_9_supplementary_doc, established_040_grammar_ch10_12_supplementary_doc, established_044_grammar_ch19_clitic_accent_doc, established_037_grammar_ch1_3_supplementary_xyz_clitic_model_concept [INFERRED 0.85]
- **Hammond Ch.7 case-usage and noun-declension system** — established_050_serbian_essential_ch7a_nouns_part1_concept_genitive_case_usage, established_050_serbian_essential_ch7a_nouns_part1_concept_dative_case_usage, established_050_serbian_essential_ch7a_nouns_part1_concept_vocative_case_formation, established_051_serbian_essential_ch7b_nouns_part2_concept_three_declension_framework, established_051_serbian_essential_ch7b_nouns_part2_concept_irregular_noun_types [EXTRACTED 1.00]
- **Hammond enclitic/proclitic ordering and accentuation system** — established_052_serbian_essential_ch8_pronouns_concept_enclitic_pronoun_ordering, established_055_serbian_essential_ch12_13_conjunctions_enclitics_concept_enclitic_ordering_rules, established_054_serbian_essential_ch10_11_adverbs_prepositions_concept_preposition_proclitic_accentuation [INFERRED 0.85]
- **Hammond Ch.6 tense/mood system (present, future, aorist, modal)** — established_048_serbian_essential_ch6a_verbs_part1_concept_present_tense_neg_interrog, established_048_serbian_essential_ch6a_verbs_part1_concept_future_tense_formation, established_048_serbian_essential_ch6a_verbs_part1_concept_aorist_tense, established_048_serbian_essential_ch6a_verbs_part1_concept_future_ii_historical_present_passive, established_049_serbian_essential_ch6b_verbs_part2_concept_trebati_modal_constructions [EXTRACTED 1.00]
- **Croatian/Serbian Lexical Doublet Documentation Across Lessons** — established_059_magner_lesson02_06_cr_s_dialect_convention, established_062_magner_lesson17_21_kava_kafa, established_063_magner_lesson22_26_food_vocabulary, established_064_magner_lesson27_30_obitelj_porodica_family_pair [INFERRED 0.75]
- **Dialectal/Regional Variation Beyond the Standard Cr./S. Axis** — established_063_magner_lesson22_26_kajkavian_subdialect, established_064_magner_lesson27_30_south_slavic_comparison, established_059_magner_lesson02_06_ijekavian_ekavian_naming [INFERRED 0.80]
- **Grammar Points Documented Across Magner Lessons 2-30** — established_059_magner_lesson02_06_three_gender_possessive_paradigm, established_061_magner_lesson12_16_clitic_wackernagel, established_061_magner_lesson12_16_comparative_superlative_suffix, established_064_magner_lesson27_30_demonym_formation [INFERRED 0.70]
- **Croatian/Serbian/Bosnian Dialectal Variant Pairs** — datasets_serbian_croatian_bosnian_established_073_colloquial_hr_sr_glossary_dialectal_tagging_convention, datasets_serbian_croatian_bosnian_established_065_colloquial_hr_sr_units01_03_stol_sto_variant, datasets_serbian_croatian_bosnian_established_066_colloquial_hr_sr_units04_06_hladnjak_frizider, datasets_serbian_croatian_bosnian_established_068_colloquial_hr_sr_units10_12_kuna_dinar, datasets_serbian_croatian_bosnian_established_068_colloquial_hr_sr_units10_12_tisuca_hiljada, datasets_serbian_croatian_bosnian_established_069_colloquial_hr_sr_units13_15_sijecanj_januar_variant, datasets_serbian_croatian_bosnian_established_071_colloquial_hr_sr_units19_20_svibanj_maj_variant, datasets_serbian_croatian_bosnian_established_073_colloquial_hr_sr_glossary_part2_kolodvor_stanica, datasets_serbian_croatian_bosnian_established_073_colloquial_hr_sr_glossary_part3_netko_neko, datasets_serbian_croatian_bosnian_established_073_colloquial_hr_sr_glossary_part7_teta_tetka, datasets_serbian_croatian_bosnian_established_073_colloquial_hr_sr_glossary_part8_vol_vo [INFERRED 0.85]
- **Colloquial Register Markers Across Units 1-20** — datasets_serbian_croatian_bosnian_established_065_colloquial_hr_sr_units01_03_colloquial_register_framing, datasets_serbian_croatian_bosnian_established_065_colloquial_hr_sr_units01_03_zdravo, datasets_serbian_croatian_bosnian_established_065_colloquial_hr_sr_units01_03_para, datasets_serbian_croatian_bosnian_established_066_colloquial_hr_sr_units04_06_halo, datasets_serbian_croatian_bosnian_established_066_colloquial_hr_sr_units04_06_pa_tako, datasets_serbian_croatian_bosnian_established_067_colloquial_hr_sr_units07_09_cura, datasets_serbian_croatian_bosnian_established_067_colloquial_hr_sr_units07_09_blago_tebi_njoj, datasets_serbian_croatian_bosnian_established_067_colloquial_hr_sr_units07_09_napiti_se, datasets_serbian_croatian_bosnian_established_068_colloquial_hr_sr_units10_12_valjda, datasets_serbian_croatian_bosnian_established_069_colloquial_hr_sr_units13_15_ubit_ce_me_stari, datasets_serbian_croatian_bosnian_established_070_colloquial_hr_sr_units16_18_gubite_se, datasets_serbian_croatian_bosnian_established_070_colloquial_hr_sr_units16_18_jesi_li_normalan, datasets_serbian_croatian_bosnian_established_070_colloquial_hr_sr_units16_18_straznjica, datasets_serbian_croatian_bosnian_established_071_colloquial_hr_sr_units19_20_baka_servis, datasets_serbian_croatian_bosnian_established_071_colloquial_hr_sr_units19_20_jedva_cekam, datasets_serbian_croatian_bosnian_established_073_colloquial_hr_sr_glossary_part5_ni_slucajno [INFERRED 0.85]
- **Verb Morphology System (Aspect, Tense, Mood)** — datasets_serbian_croatian_bosnian_established_065_colloquial_hr_sr_units01_03_aspect_imperfective_perfective, datasets_serbian_croatian_bosnian_established_068_colloquial_hr_sr_units10_12_future_tense_formation, datasets_serbian_croatian_bosnian_established_070_colloquial_hr_sr_units16_18_imperative_formation, datasets_serbian_croatian_bosnian_established_071_colloquial_hr_sr_units19_20_conditional_mood, datasets_serbian_croatian_bosnian_established_071_colloquial_hr_sr_units19_20_participles_gerunds [INFERRED 0.75]
- **Ekavian/Ijekavian Dialectal Contrast Markers Across Colloquial Serbian** — established_075_colloquial_sr_units04_06_ekavian_ijekavian_contrast, established_075_colloquial_sr_units04_06_ziveli_zivjeli_toast, established_080_colloquial_sr_units18_19_kotor_posvetiti_se_dialectal, established_080_colloquial_sr_units18_19_kotor_plesati_regional_annotation, established_076_colloquial_sr_units07_09_dialectal_annotation_sanja_dado [INFERRED 0.85]
- **Explicit Source-Marked Colloquial-Register Annotations** — established_076_colloquial_sr_units07_09_colloquial_register_marking, established_076_colloquial_sr_units07_09_escajg, established_079_colloquial_sr_units16_17_gepek, established_080_colloquial_sr_units18_19_kotor_baka_servis, established_078_colloquial_sr_units13_15_svirka [INFERRED 0.85]
- **Ekipa Strand Belgrade Youth/Informal Register** — established_074_colloquial_sr_units01_03_ekipa_reading_strand, established_074_colloquial_sr_units01_03_super_interjection, established_074_colloquial_sr_units01_03_castiti_idiom, established_078_colloquial_sr_units13_15_gledati_svoja_posla [INFERRED 0.75]
- **Taboo-Avoidance Naming Confirmed for Snake, Wolf, and Bear** — concept_taboo_avoidance_naming, vocab_zmija_taboo_names, vocab_vuk_taboo_names, vocab_medved_taboo_names [INFERRED 0.90]
- **Змaj / Аждаја / Ала — the Balkan Dragon-Family Mythological Cluster** — concept_zmaj_dragon, concept_azdaja_dragon_serpent, concept_ala_hail_demon [INFERRED 0.80]
- **Source-marked formal/informal register-tiering findings across TYS** — established_093_tys_units01_03_drug_drugarica, established_096_tys_units10_12_kinship_register, established_095_tys_units07_09_mejl_register, established_098_tys_units16_18_epistolary_register [INFERRED 0.75]
- **Informal/slang word-formation mechanisms noted across TYS (clipping, diminutive suffixation, colloquial coinage)** — established_101_tys_units19plus_cevapi_clipping, established_097_tys_units13_15_diminutive_register, established_095_tys_units07_09_majmun [INFERRED 0.70]
- **Teach Yourself Serbian — full-book unit chain (20 units, grammar summary, glossary)** — established_093_tys_units01_03_unit_content, established_094_tys_units04_06_unit_content, established_095_tys_units07_09_unit_content, established_096_tys_units10_12_unit_content, established_097_tys_units13_15_unit_content, established_098_tys_units16_18_unit_content, established_101_tys_units19plus_unit_content, established_099_tys_grammar_summary_paradigm_tables, established_100_tys_glossary_part1_content, established_100_tys_glossary_part2_content, established_100_tys_glossary_part3_content [INFERRED 0.85]

## Communities (29 total, 4 thin omitted)

### Community 0 - "Colloquial Serbian: Idiom & Register"
Cohesion: 0.05
Nodes (44): Colloquial Serbian (Hawkesworth & Ćalić, 2006), Ja častim! (treating/paying idiom), Crn (Black) = Red Wine Idiom, Deca — Grammatically Feminine Collective Noun, Dual Cyrillic/Latin Script Presentation, Ekipa Reading Strand (Informal-Register Narrative Device), super (colloquial exclamation), Ekavian/Ijekavian Dialectal Contrast (+36 more)

### Community 1 - "Magner's Croatian/Serbian: Dialect Convention & Aorist"
Cohesion: 0.07
Nodes (39): Croatian/Serbian Slash-and-Separate Sentence Convention, Croatian/Serbian Future Tense Structural Contrast, hrvatskosŕpski / srpskohrvatski Compound Word-Order Contrast, Ijekavian/Ekavian Dialect Naming and Choice Guidance, Krivi broj (Wrong Number) Deliberately Unaccented Anecdote, Magner: Introduction to the Croatian and Serbian Language, Syllabic /r/ as a Full Vowel, Three-Gender Noun System and Possessive Adjective Paradigm (+31 more)

### Community 2 - "Teach Yourself Serbian: Formality & Address Register"
Cohesion: 0.06
Nodes (39): Teach Yourself Serbian (Norris & Ribnikar, 2003), drug/drugarica: Communist-era 'comrade' register layered on 'friend', gospodin/gospođa/gospođica — formal address titles, T-V formal/informal 'you' distinction (vi vs ti), TYS Units 1-3 (greetings, alphabets, T-V distinction), zdravo — colloquial hello/goodbye, бакалница — heard often, rarely seen written (spoken/written register asymmetry), да-construction preferred over bare infinitive ('hoću da kupim') (+31 more)

### Community 3 - "BCS Grammar Core: Case, Aspect & Jat Reflex"
Cohesion: 0.10
Nodes (35): [B]/[C]/[S] Dialect-Tagging Convention, Clitic Second-Position Placement Rule, Adjective Comparison: Suffix -ij- and Consonant-Softening, Dative-Experiencer / Subjectless Sentence Construction, Dative/Locative/Instrumental Plural Syncretism, Ekavian/Ijekavian (Jat Reflex) Split, BCS Future Tense (hteti/htjeti-based Auxiliary), Genitive Case and Its Uses (+27 more)

### Community 4 - "Flagship Textbook: Archaic Tenses & Aspect Pairing"
Cohesion: 0.12
Nodes (33): Aorist and Imperfect: Archaic/Literary Past Tenses, Bosnian/Croatian/Serbian Regional Lexical-Variant Tagging, Bosnian, Croatian, Serbian, a Textbook (Alexander & Elias-Bursać, 2010), Ekavian/Ijekavian (E/J) Jat-Reflex Alternation, odoh ja ("I'm out of here" — colloquial aorist survival), Relative Conjunction/Pronoun koji, Present and Past Verbal Adverbs (Converbs), Verbal Aspect: Imperfective/Perfective Pairing (+25 more)

### Community 5 - "Serbian Folk Tales: Demonology & Taboo-Avoidance Naming"
Cohesion: 0.08
Nodes (31): Српске народне бајке (Serbian Folk Fairy Tales, Kreativni centar 2000), Ала — crop/hail-storm demon fought by dragons, Аждаја/Аждаха — dragon-serpent formed from a snake after 100 years, Баш-Челик — the mythic iron man antagonist, Ђаво — folk-demonology of the devil (appearance, haunts, proverbs), Formulaic Rule-of-Three Repetition (oral-tale register marker), Ottoman Turkish Loanword Layer (clustered by tale/dialect zone), Taboo-Avoidance Naming (Euphemistic Substitution for Feared Animals) (+23 more)

### Community 6 - "Colloquial Croatian/Serbian: Case & Question Formation"
Cohesion: 0.08
Nodes (31): Verbal Aspect (Imperfective/Perfective), da li vs. li Question Formation (Croatian/Serbian Split), Enclitic Word Order Rule, Colloquial Croatian and Serbian (Hawkesworth, 1998), stol/sto (table, Croatian/Serbian lexical variant), Case System Overview (Accusative/Genitive/Dative/Instrumental/Locative), hladnjak/frizider (fridge, regional variant pair), Cardinal Number Case Government (+23 more)

### Community 7 - "Hammond's Serbian: Dialect Groups & Karadžić Reform"
Cohesion: 0.08
Nodes (24): Čakavian dialect (čakavski), Jat-reflex sub-dialects (Ikavian/Ijekavian/Ekavian), Kajkavian dialect (kajkavski), Serbo-Croatian unification and 1990s breakup, Štokavian dialect (štokavski), Vuk Karadžić's phonetic alphabet reform, Serbian: An Essential Grammar (Hammond, 2005), mleko/mlijeko/mliko, vreme/vrijeme/vrime jat-reflex example set (+16 more)

### Community 8 - "Standardization History: Alphabets & Illyrian Movement"
Cohesion: 0.10
Nodes (21): ćirilica (Cyrillic alphabet), Chapter 21: Introduction, Writing Systems, Language Standardization, glagoljica (Glagolitic alphabet), Illyrian movement language reform, istočna varijanta / zapadna varijanta terms, latinica (Latin alphabet), "Piši kao što govoriš" (Vuk's maxim), Varijanta: eastern/western variant framework (+13 more)

### Community 9 - "BCS Glossary Part 4-5: E/J and B/C/S Lexical Splits"
Cohesion: 0.10
Nodes (20): BCS-English Glossary, part 4 (po- through sta-), pòzorište (theater) [B,S], pravda (justice), prèdsednik/prèdsjednik (president, E/J pair), prèvod/prijèvod (translation, E/J and B,S vs C forms), prijatelj (friend/pal, B,C-only sense split), Bosnian, Croatian, Serbian, a Textbook with Exercises and Basic Grammar (Alexander & Elias-Bursać, 2010), BCS-English Glossary, part 5 (sta- through Ž, end) (+12 more)

### Community 10 - "Colloquial Croatian/Serbian: Register-Tagged Idioms"
Cohesion: 0.12
Nodes (16): Book's Colloquial-Register Framing and Priority, para (money, colloquial genitive plural), Zdravo (greeting, Communism-association note), halo (telephone-only greeting), pa tako (colloquial evasive idiom), blago tebi/njoj (lucky you/her! idiom), cura (girl, explicitly (coll.)-tagged), napiti se (to get drunk, intoxication register) (+8 more)

### Community 11 - "Naming Disputes & Pluricentric-Language Status"
Cohesion: 0.18
Nodes (16): Bosnian, Croatian, Serbian, a Grammar with Sociolinguistic Commentary (Alexander, 2006), Bosnian vs. Bosniak language-naming dispute, Chapter 26: One Language, or More Than One?, "jedan ali ne jedinstven" ("one but not uniform"), naš jezik / naški (self-referential unmarked language name), BCS as a pluricentric language, S-language vs. C-language distinction, Aspect-pair typology: suffixation vs. prefixation (+8 more)

### Community 12 - "Hammond's Serbian: Noun Declension Classes"
Cohesion: 0.14
Nodes (14): Gender of nouns (nominative/plural ending patterns), Noun-type taxonomy (proper/common/mass/collective/abstract), Vocative case formation rules (k/c/h→č/c/š, -a→-o, -ica→-ice), narkoman, siledžija, kravetina (slang-adjacent derivational-suffix examples), A declension (masculine/neuter nouns) endings summary, E declension (feminine/masc.-a nouns, mати/mati) endings summary, I declension (feminine consonant-final nouns, кћи/kći) endings summary, Irregular noun declension, seven types (-ov-/-ev-, -en-/-et-, -es-, -lac, etc.) (+6 more)

### Community 13 - "Grammar Supplement: Accent Notation & Clitic Model"
Cohesion: 0.17
Nodes (13): Book's accent notation system (length + tone), lijep accent-notation worked example (-ije- as single complex vowel), Reference Grammar Chapters 1-3 (Supplementary), jat (the historical vowel underlying E/J split), -in singulative suffix (Srbin, Bugarin, Arapin), XYZ model of clitic placement, da as obligatory X-slot conjunction (XYZ model example), Reference Grammar Chapters 7-9 (Supplementary) (+5 more)

### Community 14 - "Grammar Supplement: Consonant Softening & Verb Types"
Cohesion: 0.18
Nodes (11): aorist/imperfect condensed paradigm (upitati, reći, biti), Consonant softening system: Types A, B, C, Reference Grammar Chapters 10-12 (Supplementary), oko/uho (eye/ear, neuter sg. → feminine pl. irregular nouns), s-/ov-/on-/k- now/here/there/question-word adverb paradigm, Sixteen verb-conjugation type reference table, Chapter 20: The Sound Structure of BCS, nepostojano a (fleeting vowel mechanism) (+3 more)

### Community 15 - "Hammond's Serbian: Pronoun & Adverb Series"
Cohesion: 0.22
Nodes (9): Demonstrative pronouns (ovaj/taj/onaj and derived series), Possessive pronouns (moj/tvoj/svoj/naš/vaš/njegov/njen/njihov), Universal pronouns (svako/svašta/svaki/svi/sve etc.), svoj (reflexive possessive pronoun), Possessive adjective formation + capitalization rule, Pronominal-adverb indefinite/negative/universal grid (iko-/neko-/niko-/svako-), ikada/nekada/nikada/svakada series (indefinite pronominal-adverb branch), što (relative conjunction) vs. koji (relative pronoun) usage split (+1 more)

### Community 16 - "Hammond's Serbian: Consonant Mutation & Word Formation"
Cohesion: 0.25
Nodes (8): Consonant classification framework (obstruent/resonant, place), /j/-mutation table (d+j→đ, t+j→ć, etc.), Palatalization before e and i (k/g/h→č/ž/š, k/g/h→c/z/s), Word-final consonant clusters (traditional four vs. wider eight), Hard vs. soft adjective base classification (governs -o/-e alternation), Passive participle as base for deverbal nouns (-nje), Noun/adjective-forming suffix system (Ch.20.2), kiša→kišan→kišobran (stacked word-formation worked example)

### Community 17 - "Case Review: Coffee-Word Regional Triplet & Prepositions"
Cohesion: 0.29
Nodes (7): kahva/kafa (coffee, h-restored vs. common spelling), advokat/odvjetnik (lawyer, S,B vs. C regional lexical split), Seven-case usage system, full review, Chapter 17: Cases of Nouns, Review, jedan drugi / jedni drugi (reciprocal "each other"), kafa/kava/kahva (coffee, three-way regional split), kroz/među/na/nad/pod/pred/u/uz/za (accusative-governing prepositions)

### Community 18 - "Bosnia Chapter: Turcizmi & Bosniak Naming"
Cohesion: 0.33
Nodes (6): bosanski jezik / bošnjački jezik (contested language name), Bošnjak/bošnjak (Bosniak ethnonym), ćuprija/most (bridge, Turkish-derived vs. native doublet), Chapter 23: Bosnia, sanjak/sandžak (Ottoman administrative unit), Turcizmi: Turkish-derived loanwords in Bosnian speech

### Community 19 - "Word Formation: Derivational Suffix System"
Cohesion: 0.33
Nodes (6): -ac/-lac/-ač/-nik agentive suffixes, BCS derivational morphology system (word formation), -ić/-če/-ce diminutive/affectionate suffixes, Chapter 18: Word Formation, -in / -an-in nationality-origin suffix (Srbin, Beograđanin), NA-/PRE-/ZA- verbal prefixation families

### Community 20 - "Clitic Placement & Prosodic Accent Shift"
Cohesion: 0.33
Nodes (6): Chapter 19: Clitic Placement and BCS Prosody, Four-accent system terms (kratkosilazni etc.), junak/đak (PLACE-vs-FORM accent shift worked example), kazati/kažem (infinitive/present PLACE-vs-FORM accent example), Rhythmic constituent model of clitic placement, skakanje (Bosnian accent retraction onto prepositions)

### Community 21 - "Grammar Supplement: Irregular Noun Alternations"
Cohesion: 0.40
Nodes (5): Reference Grammar Chapters 4-6 (Supplementary), gazda (landlord, masc. noun on fem. -a declension), posao/posla (-o/-l alternation, work/job), sveska/svezaka (irregular inserted -z- in Gpl.), vrata/kola (plural-form, singular-meaning neuter nouns)

### Community 22 - "Hammond's Serbian: Case-Governed Number Nouns"
Cohesion: 0.50
Nodes (4): Dative case usage (closed-class verb inventories by semantic type), Genitive case usage (closed-class verbs/adjectives, partitive nouns), Number nouns (-ица/-ica, male-human-only groups), dvojica/trojica/desetorica-type number nouns example set

### Community 23 - "Hammond's Serbian: Numeral Category System"
Cohesion: 0.50
Nodes (4): Cardinal-numeral declension (jedan / dva-tri-četiri / pet+), Collective numerals (-oje/-oro, mixed-gender groups), Four numeral categories (cardinal/ordinal/collective/number-noun), Quantifier types (countable/uncountable/collective-governing)

### Community 24 - "Hammond's Serbian: Modal Verbs & Ići-Derivatives"
Cohesion: 0.67
Nodes (3): Iћi/ići prefixed derivatives (proći, prići, naći, naići, obići, zaći), Trebati's five modal да/da-clause constructions + potreban alternative, moći, mogu (full present-tense modal paradigm)

## Knowledge Gaps
- **222 isolated node(s):** `Hammond, Serbian: An Essential Grammar (2005)`, `Reflexive Possessive svoj vs. njegov/njen`, `šta/što, ko/tko - core B,S vs. C interrogative pair`, `Bošnjak (ethnonym) vs. Bosanac (civic demonym)`, `đ vs. dj Orthographic Substitution Note` (+217 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **4 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Bosnian, Croatian, Serbian, a Grammar with Sociolinguistic Commentary (Alexander, 2006)` connect `Naming Disputes & Pluricentric-Language Status` to `Standardization History: Alphabets & Illyrian Movement`, `BCS Glossary Part 4-5: E/J and B/C/S Lexical Splits`, `Grammar Supplement: Accent Notation & Clitic Model`, `Grammar Supplement: Consonant Softening & Verb Types`, `Case Review: Coffee-Word Regional Triplet & Prepositions`, `Bosnia Chapter: Turcizmi & Bosniak Naming`, `Word Formation: Derivational Suffix System`, `Clitic Placement & Prosodic Accent Shift`, `Grammar Supplement: Irregular Noun Alternations`?**
  _High betweenness centrality (0.052) - this node is a cross-community bridge._
- **Why does `Chapter 22: Dialect Differences` connect `BCS Glossary Part 4-5: E/J and B/C/S Lexical Splits` to `Naming Disputes & Pluricentric-Language Status`?**
  _High betweenness centrality (0.016) - this node is a cross-community bridge._
- **What connects `Hammond, Serbian: An Essential Grammar (2005)`, `Reflexive Possessive svoj vs. njegov/njen`, `šta/što, ko/tko - core B,S vs. C interrogative pair` to the rest of the system?**
  _222 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Colloquial Serbian: Idiom & Register` be split into smaller, more focused modules?**
  _Cohesion score 0.046511627906976744 - nodes in this community are weakly interconnected._
- **Should `Magner's Croatian/Serbian: Dialect Convention & Aorist` be split into smaller, more focused modules?**
  _Cohesion score 0.06882591093117409 - nodes in this community are weakly interconnected._
- **Should `Teach Yourself Serbian: Formality & Address Register` be split into smaller, more focused modules?**
  _Cohesion score 0.059379217273954114 - nodes in this community are weakly interconnected._
- **Should `BCS Grammar Core: Case, Aspect & Jat Reflex` be split into smaller, more focused modules?**
  _Cohesion score 0.09915966386554621 - nodes in this community are weakly interconnected._