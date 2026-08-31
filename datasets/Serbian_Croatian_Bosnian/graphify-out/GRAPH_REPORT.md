# Graph Report - Serbian_Croatian_Bosnian  (2026-08-31)

## Corpus Check
- Large corpus: 106 files · ~753,430 words. Semantic extraction will be expensive (many Claude tokens). Consider running on a subfolder.

## Summary
- 468 nodes · 568 edges · 45 communities (29 shown, 16 thin omitted)
- Extraction: 79% EXTRACTED · 20% INFERRED · 1% AMBIGUOUS · INFERRED: 116 edges (avg confidence: 0.76)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- Source Book Catalog & Reference Docs
- Flagship Textbook: Aorist, Dialect Tags & Cases
- Companion Grammar: Alphabets & Jat Reflex
- Colloquial Serbian: Script & Register
- Magner Lessons 2-6: Cr./S. Convention
- Flagship Textbook: E/J & B/C/S Glossary Tagging
- Magner Lessons 7-11: Cyrillic & Dialect Pronunciation
- Serbian Folk Tales: Taboo-Avoidance Naming
- Croatian Purism & Adjective Declension
- Colloquial Croatian/Serbian: Aspect & Case
- Hammond's Serbian: Modal Verbs & Gender
- Colloquial Books: Regional Lexical Variants
- Magner Lessons 12-16: Clitics & Script
- Magner Lessons 17-21: Onomatopoeia & Clothing Verbs
- Case-Governing Verb/Adjective Inventories
- Hammond's Consonant Classification & Palatalization
- Aorist Paradigms & Ići-Derivatives
- Tense Negative/Interrogative System & Question Formation
- Pronoun System: Demonstratives & Reflexives
- Deverbal Nouns & Adverb Classification
- Enclitic Rules & Particle Inventory
- Standardization History: Illyrian & Vukovian Reform
- Primary Dialect Split & Jat-Reflex System
- Derivational Suffixes & Slang-Adjacent Vocabulary
- Colloquial Idioms & Register-Tagged Exclamations
- Conjunction System & Relative Clauses
- Community 26
- Community 27
- Community 28
- Community 29
- Community 30
- Community 31
- Community 32
- Community 33
- Community 34
- Community 35
- Community 36
- Community 37
- Community 38
- Community 39
- Community 40
- Community 41
- Community 42
- Community 43
- Community 44

## God Nodes (most connected - your core abstractions)
1. `Lila Hammond, "Serbian: An Essential Grammar" (Routledge, 2005) — third, Serbian-specific reference book for this language, distinct from the comparative B/C/S flagship textbook and the companion Alexander Grammar already extracted elsewhere in this dataset. This PDF's embedded Cyrillic font is corrupted on pdftotext extraction across the whole book; all files in this chunk use the book's parallel clean Latin-script transliteration as the primary form.` - 60 edges
2. `Bosnian, Croatian, Serbian, a Textbook (Alexander & Elias-Bursać, 2nd ed. 2010)` - 23 edges
3. `Colloquial Serbian (Hawkesworth & Ćalić, 2006)` - 22 edges
4. `Bosnian, Croatian, Serbian: A Grammar with Sociolinguistic Commentary (Ronelle Alexander, 2006)` - 16 edges
5. `Bosnian, Croatian, Serbian, a Textbook (Alexander & Elias-Bursać, 2010)` - 13 edges
6. `Ekavian/Ijekavian ([E]/[J]) Jat-Reflex Alternation` - 12 edges
7. `[B]/[C]/[S] Regional Standard-Language Tagging Convention` - 12 edges
8. `Lesson 4 (Četvrta lekcija)` - 11 edges
9. `Lesson 5 (Peta lekcija)` - 11 edges
10. `Lesson 6 (Šesta lekcija)` - 11 edges

## Surprising Connections (you probably didn't know these)
- `Regional/Teen Colloquial Family Terms (stara/stari/starci, kèva)` --semantically_similar_to--> `Syllable-Switching Slang-Formation Mechanism (flagged, detailed in a later chunk)`  [INFERRED] [semantically similar]
  established/011_lesson09.md → 00_Extraction_Checklist.md
- `Magner Lesson 1 (vision-reading test)` --cites--> `Introduction to the Croatian and Serbian Language (Magner, 1991/1998)`  [EXTRACTED]
  established/002_lesson01_magner_vision_test.md → 00_Book_Triage_Catalog.md
- `ùrok/pònos — Russian/BCS false-friend pair` --semantically_similar_to--> `B/C/S Vocabulary Differences Beyond Pronunciation`  [INFERRED] [semantically similar]
  established/002_lesson01_magner_vision_test.md → established/003_lesson01_complete.md
- `agentive and diminutive suffixes flagged as slang-formation-relevant` --semantically_similar_to--> `hypothesized connection: BCS phonotactics and syllable-switching slang mechanism (cf. Sarajevo/Zagreb slang documented elsewhere in this dataset, e.g. vozdra/zdravo, đido/dođi — not independently verified in this chunk)`  [INFERRED] [semantically similar]
  established/043_grammar_ch18_word_formation.md → established/045_grammar_ch20_phonology.md
- `Ijekavian/ekavian dialect naming & Dialect Choice guidance` --semantically_similar_to--> `Distinct-root Cr./S. lexical pairs (vs jat-only pairs)`  [INFERRED] [semantically similar]
  established/059_magner_lesson02-06.md → established/063_magner_lesson22-26.md

## Hyperedges (group relationships)
- **Lessons Documenting the Ekavian/Ijekavian Jat-Reflex Split** — concept_ekavian_ijekavian_jat_reflex, established_002_lesson01_magner_vision_test, established_004_lesson02, established_005_lesson03, established_006_lesson04, established_007_lesson05, established_008_lesson06, established_009_lesson07, established_010_lesson08, established_011_lesson09, established_012_lesson10, established_013_lesson11 [INFERRED 0.85]
- **Explicitly-Flagged Slang/Colloquial Register Findings in this Chunk** — vocab_ma_moj_slang, vocab_keva_slang, vocab_stara_stari_starci, vocab_limunada_ljubic_genre_slang, concept_teen_family_slang_terms [EXTRACTED 1.00]
- **Flagship Textbook Lesson-by-Lesson Extraction Sequence (Lessons 1-11)** — book_alexander_elias_textbook, established_001_lesson01_basics, established_003_lesson01_complete, established_004_lesson02, established_005_lesson03, established_006_lesson04, established_007_lesson05, established_008_lesson06, established_009_lesson07, established_010_lesson08, established_011_lesson09, established_012_lesson10, established_013_lesson11 [EXTRACTED 1.00]
- **BCS's Three Layered Regional-Variation Tagging Systems** — concept_bcs_regional_tagging, concept_ej_ekavian_ijekavian_alternation, concept_montenegrin_variant [EXTRACTED 0.90]
- **Trilingual Coffee-Culture Vocabulary Cluster** — established_016_lesson14_recept_za_kahvu_kavu_kafu, established_016_lesson14_dzezva_fildzan, established_015_lesson13_kafana_kavana [INFERRED 0.80]
- **BCS Verb-Morphology Teaching System (aspect, type, adverbs/participles)** — concept_verb_conjugation_type_system, concept_aorist_imperfect_past_tenses, concept_verbal_adverbs_participles, concept_passive_impersonal_formation [EXTRACTED 0.85]
- **National language-naming disputes across chapters 21-26 (srpskohrvatski/hrvatskosrpski, bosanski/bošnjački, Montenegrin movement, S-language/C-language framing)** — datasets_serbian_croatian_bosnian_established_031_socioling_ch21_novi_sad_agreement, datasets_serbian_croatian_bosnian_established_033_socioling_ch23_bosanski_bosnjacki_dispute, datasets_serbian_croatian_bosnian_established_034_socioling_ch24_croatian_declaration_spring, datasets_serbian_croatian_bosnian_established_035_socioling_ch25_montenegrin_language_movement, datasets_serbian_croatian_bosnian_established_036_socioling_ch26_s_language_c_language [INFERRED 0.85]
- **BCS consonant-softening and accent-shift system spanning grammar chapters 10-12, 19, and 20 (Types A/B/C softening, PLACE-vs-FORM accent, palatalization origin)** — datasets_serbian_croatian_bosnian_established_040_grammar_ch10_12_consonant_softening_types, datasets_serbian_croatian_bosnian_established_044_grammar_ch19_place_vs_form_accent_model, datasets_serbian_croatian_bosnian_established_045_grammar_ch20_palatalization_origin, datasets_serbian_croatian_bosnian_established_045_grammar_ch20_l_to_o_shift [EXTRACTED 0.90]
- **Full BCS case-usage/preposition-government review, assembled across grammar chapters 1-3, 4-6, 7-9, and 17** — datasets_serbian_croatian_bosnian_established_037_grammar_ch1_3_seven_case_system, datasets_serbian_croatian_bosnian_established_038_grammar_ch4_6_u_word_na_word_inventory, datasets_serbian_croatian_bosnian_established_039_grammar_ch7_9_instrumental_bare_functions, datasets_serbian_croatian_bosnian_established_042_grammar_ch17_case_usage_review_system [EXTRACTED 0.90]
- **Cross-tense negative/interrogative/negative-interrogative construction system (present, perfect, future, aorist)** — datasets_serbian_croatian_bosnian_established_048_serbian_essential_ch6a_verbs_part1_present_tense_neg_interrogative, datasets_serbian_croatian_bosnian_established_048_serbian_essential_ch6a_verbs_part1_perfect_tense_neg_interrogative, datasets_serbian_croatian_bosnian_established_048_serbian_essential_ch6a_verbs_part1_future_tense_formation, datasets_serbian_croatian_bosnian_established_048_serbian_essential_ch6a_verbs_part1_aorist_tense_system, datasets_serbian_croatian_bosnian_established_049_serbian_essential_ch6b_verbs_part2_interrogative_formation_inventory [INFERRED 0.85]
- **Nominal and pronominal declension system: three-declension noun framework, irregular nouns, and personal/demonstrative pronoun declension sharing the same case syncretism patterns** — datasets_serbian_croatian_bosnian_established_051_serbian_essential_ch7b_nouns_part2_three_declension_framework, datasets_serbian_croatian_bosnian_established_051_serbian_essential_ch7b_nouns_part2_irregular_nouns_seven_types, datasets_serbian_croatian_bosnian_established_052_serbian_essential_ch8_pronouns_personal_pronoun_declension, datasets_serbian_croatian_bosnian_established_052_serbian_essential_ch8_pronouns_demonstrative_pronouns [INFERRED 0.75]
- **Discourse-grammar layer: particles/conjunctions/exclamations, enclitic-ordering rules, and quantifier/determiner systems that govern casual spoken-register sentence construction** — datasets_serbian_croatian_bosnian_established_057_serbian_essential_ch15_17_quantifiers_determiners_particles_particles_conjunctions_exclamations_inventory, datasets_serbian_croatian_bosnian_established_055_serbian_essential_ch12_13_conjunctions_enclitics_enclitic_interaction_rules, datasets_serbian_croatian_bosnian_established_057_serbian_essential_ch15_17_quantifiers_determiners_particles_determiner_classes, datasets_serbian_croatian_bosnian_established_057_serbian_essential_ch15_17_quantifiers_determiners_particles_quantifier_classes [INFERRED 0.75]
- **Cross-lesson Cr./S. regional lexical-doublet examples** — datasets_serbian_croatian_bosnian_established_059_magner_lesson02_06_ploca_tabla, datasets_serbian_croatian_bosnian_established_062_magner_lesson17_21_kupaonica_kupatilo, datasets_serbian_croatian_bosnian_established_063_magner_lesson22_26_gospodarstvo_imanje, datasets_serbian_croatian_bosnian_established_064_magner_lesson27_30_obitelj_porodica [INFERRED 0.85]
- **Kajkavian dialect glossary example set (Lesson 22 song)** — datasets_serbian_croatian_bosnian_established_063_magner_lesson22_26_kajkavian_subdialect, datasets_serbian_croatian_bosnian_established_063_magner_lesson22_26_bum_budem, datasets_serbian_croatian_bosnian_established_063_magner_lesson22_26_lojtra [EXTRACTED 1.00]
- **Cross-lesson agentive/demonym gender-suffix formation patterns** — datasets_serbian_croatian_bosnian_established_060_magner_lesson07_11_occupation_gender_suffix, datasets_serbian_croatian_bosnian_established_064_magner_lesson27_30_ac_anin_demonym_pattern, datasets_serbian_croatian_bosnian_established_060_magner_lesson07_11_novinar_novinarka, datasets_serbian_croatian_bosnian_established_061_magner_lesson12_16_licanin_demonym [INFERRED 0.75]
- **Croatian/Serbian/Bosnian Lexical Variant Cluster** — datasets_serbian_croatian_bosnian_established_073_colloquial_hr_sr_glossary_croatian_serbian_bosnian_lexical_variation, datasets_serbian_croatian_bosnian_established_073_colloquial_hr_sr_glossary_kava_kafa_kahva_variant, datasets_serbian_croatian_bosnian_established_073_colloquial_hr_sr_glossary_part7_vlak_voz_variant, datasets_serbian_croatian_bosnian_established_073_colloquial_hr_sr_glossary_part7_teta_tetka_variant, datasets_serbian_croatian_bosnian_established_073_colloquial_hr_sr_glossary_part8_zracna_luka_aerodrom_variant, datasets_serbian_croatian_bosnian_established_068_colloquial_hr_sr_units10_12_kuna_dinar_currency_variant, datasets_serbian_croatian_bosnian_established_068_colloquial_hr_sr_units10_12_tisuca_hiljada_lexical_variant, datasets_serbian_croatian_bosnian_established_069_colloquial_hr_sr_units13_15_sijecanj_januar_months_variant [EXTRACTED 0.90]
- **Case-System Teaching Sequence** — datasets_serbian_croatian_bosnian_established_066_colloquial_hr_sr_units04_06_accusative_case, datasets_serbian_croatian_bosnian_established_066_colloquial_hr_sr_units04_06_genitive_case, datasets_serbian_croatian_bosnian_established_066_colloquial_hr_sr_units04_06_dative_case, datasets_serbian_croatian_bosnian_established_066_colloquial_hr_sr_units04_06_instrumental_case, datasets_serbian_croatian_bosnian_established_065_colloquial_hr_sr_units01_03_vocative_case [EXTRACTED 0.85]
- **Explicitly-Flagged Colloquial/Idiom Cluster** — datasets_serbian_croatian_bosnian_established_067_colloquial_hr_sr_units07_09_cura_coll, datasets_serbian_croatian_bosnian_established_067_colloquial_hr_sr_units07_09_blago_tebi_idiom, datasets_serbian_croatian_bosnian_established_070_colloquial_hr_sr_units16_18_jesi_li_normalan_idiom, datasets_serbian_croatian_bosnian_established_070_colloquial_hr_sr_units16_18_gubite_se_idiom, datasets_serbian_croatian_bosnian_established_071_colloquial_hr_sr_units19_20_baka_servis_idiom, datasets_serbian_croatian_bosnian_established_071_colloquial_hr_sr_units19_20_jedva_cekam_idiom [INFERRED 0.80]
- **Ekavian/Ijekavian Isogloss Evidence Across Colloquial Serbian** — established_074_colloquial_sr_units01_03_ekavian_ijekavian_contrast, established_075_colloquial_sr_units04_06_zivели_zivjeli_toast_contrast, established_076_colloquial_sr_units07_09_bosnian_ijekavian_dialect_flag, established_077_colloquial_sr_units10_12_svijeta_uvijek_dialect_voice, established_080_colloquial_sr_units18_19_kotor_posvetiti_dialect_annotation, established_080_colloquial_sr_units18_19_kotor_plesati_regional_flag [INFERRED 0.90]
- **"Ekipa" Narrative Thread Colloquial-Register Showcase** — established_074_colloquial_sr_units01_03_ekipa_reading_strand, established_074_colloquial_sr_units01_03_super_exclamation, established_077_colloquial_sr_units10_12_svijeta_uvijek_dialect_voice, established_078_colloquial_sr_units13_15_sibling_argument_colloquial_idioms, established_080_colloquial_sr_units18_19_kotor_plesati_regional_flag [INFERRED 0.85]
- **Source-Marked Colloquial-Register Items** — established_076_colloquial_sr_units07_09_escajg_colloquial_tag, established_079_colloquial_sr_units16_17_gepek_colloquial_car_term, established_080_colloquial_sr_units18_19_kotor_baka_servis_idiom, established_075_colloquial_sr_units04_06_kovceg_kofer_register [INFERRED 0.85]
- **Taboo-avoidance naming documented independently for three feared animals (snake, wolf, bear)** — established_084_folktales_part1_taboo_avoidance_naming, established_084_folktales_part1_snake_euphemism_set, established_088_folktales_part5_wolf_euphemism_set, established_088_folktales_part5_bear_euphemism_set [INFERRED 0.90]
- **Anthology-internal dialect/register variation across independently-collected tales** — established_086_folktales_part3_dialect_contrast_cudotvorni_prsten, established_090_folktales_part7_dialect_contrast_cela, established_087_folktales_part4_ottoman_turkish_loanword_layer [INFERRED 0.80]
- **Book's inline margin-gloss folk-demonology/mythology apparatus (recurring supernatural beings)** — established_084_folktales_part1_zmaj_dragon, established_085_folktales_part2_ala, established_088_folktales_part5_vile_fairies, established_088_folktales_part5_djavo_devil, established_089_folktales_part6_usud_sreca_fate [INFERRED 0.85]

## Communities (45 total, 16 thin omitted)

### Community 0 - "Source Book Catalog & Reference Docs"
Cohesion: 0.06
Nodes (63): Book Triage Catalog, Extraction Checklist, Bosnian, Croatian, Serbian, a Textbook (Alexander & Elias-Bursać, 2010), Bosnian, Croatian, Serbian, a Grammar: With Sociolinguistic Commentary (Alexander, 2006), Serbian: An Essential Grammar (Hammond, Routledge, 2005), Colloquial Serbian and Croatian (Hawkesworth), Introduction to the Croatian and Serbian Language (Magner, 1991/1998), Vukove bajke / Serbian Folk Tales (+55 more)

### Community 1 - "Flagship Textbook: Aorist, Dialect Tags & Cases"
Cohesion: 0.05
Nodes (46): Bosnian, Croatian, Serbian, a Textbook (Alexander & Elias-Bursać, 2nd ed. 2010), Aorist and Imperfect: Archaic Literary Past Tenses, [B]/[C]/[S] Regional Standard-Language Tagging Convention, Preposition Case-Government System (directional vs. static minimal pairs), BCS Collective Nouns (cveće-type and ùnučad-type), BCS Conditional Mood (Formation, Politeness, Purpose, Conditionals), Dative Logical-Subject / Experiencer Constructions, Ekavian/Ijekavian (E/J) Jat-Reflex Alternation (+38 more)

### Community 2 - "Companion Grammar: Alphabets & Jat Reflex"
Cohesion: 0.06
Nodes (37): svest [E] / svijest [J] (consciousness), ćirilica (Cyrillic alphabet), glagoljica (Glagolitic alphabet), Bosnian, Croatian, Serbian: A Grammar with Sociolinguistic Commentary (Ronelle Alexander, 2006), jat' (historical vowel underlying ekavian/ijekavian/ikavian split), latinica (Latin alphabet), ekavian/ijekavian/ikavian pronunciation split, štokavian/čakavian/kajkavian primary dialect split (+29 more)

### Community 3 - "Colloquial Serbian: Script & Register"
Cohesion: 0.07
Nodes (34): Colloquial Serbian (Hawkesworth & Ćalić, 2006), Dual Cyrillic/Latin Script Presentation, Ekavian vs. Ijekavian Reflex Contrast, "Ekipa" Reading Strand (Colloquial-Register Narrative), super (colloquial exclamation), Belgrade Toponymy (Kalemegdan, Knez Mihajlova, Zeleni Venac, Dorćol, Zemun), живели/живјели Dialect Toast Contrast, Explicit Bosnian Ijekavian Dialect Flag (Sanja & Dado) (+26 more)

### Community 4 - "Magner Lessons 2-6: Cr./S. Convention"
Cohesion: 0.07
Nodes (29): abecéda (Cr.) / àzbuka (S.) — alphabet, Magner, Introduction to the Croatian and Serbian Language — Lessons 2-6, Genitive/dative/instrumental-governing prepositions (Lessons 2-6), Cr./S. slash-and-separate-sentence convention, dèda (S.) / djèd (Cr.) — grandfather, Future tense: Cr./S. structural contrast, Ijekavian/ekavian dialect naming & Dialect Choice guidance, "Krivi broj" (Wrong Number) anecdote (+21 more)

### Community 5 - "Flagship Textbook: E/J & B/C/S Glossary Tagging"
Cohesion: 0.09
Nodes (23): E/J and B/C/S dialect-tag glossary convention, pòzdraviti (to greet), prèdsednik/prèdsjednik (president, E/J pair), prèvesti/prevèdem vs. prèvesti/prevèzem (translate vs. transport homograph), Bosnian, Croatian, Serbian: A Textbook with Exercises and Basic Grammar (Alexander & Elias-Bursać, 2010), štampa [B,S] (the press), sudija [B,S] / sudac [C] (judge), 1954 Novi Sad agreement (srpskohrvatski/hrvatskosrpski naming) (+15 more)

### Community 6 - "Magner Lessons 7-11: Cyrillic & Dialect Pronunciation"
Cohesion: 0.09
Nodes (22): Magner, Introduction to the Croatian and Serbian Language — Lessons 7-11, Cyrillic alphabet origin & national variants (Lesson 11), Nominative/accusative/instrumental day-name case pattern, džèpar / džèparoš — pickpocket (slang occupation term), h:k pronunciation & h-dropping/v-alternation dialect pattern, kùhati (Cr.) / kùvati (S.) — to cook (h→v pattern), Dative case & special uses of na (Lesson 8), nèdjelja/nèdelja — Sunday/week double duty (+14 more)

### Community 7 - "Serbian Folk Tales: Taboo-Avoidance Naming"
Cohesion: 0.14
Nodes (20): Srpske narodne bajke (Serbian Folk Fairy Tales, Kreativni centar, 2000), Snake euphemism set (баук, баурина, баја, непоменица), Taboo-Avoidance Naming (feared-animal name replacement), Tale: Баш-Челик ("Baš-Čelik" / True Steel), буздован (buzdovan) — hero's signature mace weapon, Змај (zmaj) — shapeshifting dragon figure, Ала (ala) — dragon-adjacent devouring monster, курва — vulgar insult appearing plainly in a children's-marketed anthology (+12 more)

### Community 8 - "Croatian Purism & Adjective Declension"
Cohesion: 0.11
Nodes (19): "differential" dictionaries and characteristic-lexicon politics, novohrvatski (post-1991 lexical purification), zrakomlat vs. helikopter (purist-coinage reception example), -in singulative suffix (ethnonym/inhabitant nouns), three-way short/long/longer adjective system in Gsg./DLsg., aspect-partner derivation typology (suffixation vs. prefixation), §89-93 review sections: full declension paradigm charts, stati/stajati prefixed-verb family as vocabulary-building pattern (+11 more)

### Community 9 - "Colloquial Croatian/Serbian: Aspect & Case"
Cohesion: 0.11
Nodes (19): Colloquial Croatian and Serbian (Hawkesworth, 1998), Da li vs. Verb+li Question Formation, Enclitics and Word Order, Verb Aspect (Imperfective/Perfective), Vocative Case, Accusative Case, Adjective Definite/Indefinite Forms, Dative Case (+11 more)

### Community 10 - "Hammond's Serbian: Modal Verbs & Gender"
Cohesion: 0.16
Nodes (18): Lila Hammond, "Serbian: An Essential Grammar" (Routledge, 2005) — third, Serbian-specific reference book for this language, distinct from the comparative B/C/S flagship textbook and the companion Alexander Grammar already extracted elsewhere in this dataset. This PDF's embedded Cyrillic font is corrupted on pdftotext extraction across the whole book; all files in this chunk use the book's parallel clean Latin-script transliteration as the primary form., Beginner stress-placement heuristic and Belgrade-vs-Bosnia unstressed-vowel-length register note, Trebati's five da-clause modal constructions plus the potreban+biti impersonal-adjective alternative, moći (mogu, možeš, može, možemo, možete, mogu) — full present-tense modal paradigm, Gender-of-nouns default nominative/plural ending patterns with exceptions, Full declined paradigms of koji/kakav/koliki/čiji across case, gender, and number, Vocative-formation rules: k/c/h→č/c/š consonant alternation, -a→-o shift, -ica→-ice rule, Complete case-by-case paradigms of archaic feminine nouns мати/mati and кћи/kći (+10 more)

### Community 11 - "Colloquial Books: Regional Lexical Variants"
Cohesion: 0.17
Nodes (12): Zdravo/Bog/Bok Greeting Register-Politics, Kuna/Dinar Currency Regional Variant, Tisuća/Hiljada — Croatian/Serbian "Thousand", Sevdalinka — Explicitly Tagged Bosnian Term, Siječanj/Januar — Slavonic vs. Latin Month Names, Croatian/Serbian/Bosnian Lexical Variation Tagging, Ijekavian/Ekavian Regional Variation, Kava/Kafa/Kahva — Three-Way C/S/B Variant (+4 more)

### Community 12 - "Magner Lessons 12-16: Clitics & Script"
Cohesion: 0.18
Nodes (11): Magner, Introduction to the Croatian and Serbian Language — Lessons 12-16, Clitic pronoun placement (Wackernagel position), Comparative/superlative adjective suffixation, Adjectival vs nominal declension of country names, Latin vs Cyrillic cursive & ijekavian/ekavian word substitutions, januar (S.) / siječanj (Cr.) — January, Letter-writing formal/informal register map, "Poštovani gospodine..." / "Dragi prijatelju" — formal/informal salutations (+3 more)

### Community 13 - "Magner Lessons 17-21: Onomatopoeia & Clothing Verbs"
Cohesion: 0.18
Nodes (11): Bird/animal-sound onomatopoeia set (pas laje, mačka mjauče, etc.), Balkan "correction factor" punctuality norm, Magner, Introduction to the Croatian and Serbian Language — Lessons 17-21, Verb pairs for putting on/taking off clothing (oblačiti/obući vs stavljati/skidati), Consonant-cluster phonology illustration wordlist (p.100-101), Foreign place-name transliteration convention (phonetic vs original spelling), Masculine-to-feminine noun pairing via -ica, kruh (Cr.) / hleb (S.) — bread (+3 more)

### Community 14 - "Case-Governing Verb/Adjective Inventories"
Cohesion: 0.29
Nodes (7): Closed-class dative-governing verb inventories organized by semantic/morphological type (giving, telling, pri-motion, impersonal liking/seeming), Extended genitive usage: closed-class genitive-governing adjectives/verbs, partitive-quantity and number-of-people noun classes, countable/uncountable existential three-way split, Three-way cardinal numeral agreement behavior: jedan (full adjective), dva/tri/četiri/oba (partial), pet+ (genitive-plural-governing, singular neuter), Collective numerals (-oje/-oro) for mixed-gender groups, including the deca counting exception, Number nouns (dvojica, trojica...) for male-human-only groups, formed with -ица/-ica, no female equivalent, jedanaesterac "a penalty kick" — football-specific coinage derived from jedanaest "eleven" via -ерац/-erac, referencing the 11-metre penalty spot, Countable/uncountable/both-class quantifier system with genitive-complement and verb-agreement rules

### Community 15 - "Hammond's Consonant Classification & Palatalization"
Cohesion: 0.33
Nodes (6): Hammond's consonant classification: obstruent/resonant, labial/dental/palatal/velar, 14 voiced/voiceless pairs plus 11 unpaired consonants, Cyrillic-Latin 30-letter alphabet correspondence table with English sound references, Complete consonant+/j/ mutation table (d+j→đ, t+j→ć, l+j→lj, etc.) with lexical exceptions, Palatalization before e and i: k/g/h→č/ž/š and k/g/h→c/z/s alternations with worked verb paradigms, baka/baki, Anka/Anki, Olga/Olgi, Beograđanka/Beograđanki, Bosanka/Bosanki, frizerka/frizerki — feminine occupational-name exceptions to k→c/g→z/h→s palatalization, Hard-vs-soft adjective base classification governing the -o/-e case-ending alternation

### Community 16 - "Aorist Paradigms & Ići-Derivatives"
Cohesion: 0.33
Nodes (6): Aorist tense: three discourse uses, full worked paradigms across three stem-shape classes, and its own negative/interrogative system, uzeti/vratiti/napisati (vowel-stem) and moći/reći/poći/zagrepsti (consonant-stem) — full worked aorist paradigm set, zagrepsti, zagrebem "to scratch" (P) — new headword, model consonant-stem aorist verb, Five additional ići-derivative prefixed verbs (proći, prići, naći, naići, obići, zaći) with -đ- present stem and -š- past stem, proći, prići, naći, naići, obići, zaći — the five newly-tabulated ići-derivatives, 14-prefix inventory of aspectual/directional verb-forming prefixes (do-, za-, u-, od-, iz-, pri-, pod-, na-, o-/ob-, s-/sa-, uz-, pro-, pre-, raz-) with per-prefix core meanings

### Community 17 - "Tense Negative/Interrogative System & Question Formation"
Cohesion: 0.33
Nodes (6): Future tense formation mechanics: enclitic/fused/da+present variants, negative/interrogative ambiguity with volition sense, Perfect tense negative/interrogative/negative-interrogative system (long-vs-short biti auxiliary split), Present tense negative/interrogative/negative-interrogative construction system, Nine-way inventory of question-forming strategies (intonation, question-word, li, da li, je li, zar, zar ne, da+present, li-after-modal), The "true double negative" construction where two negatives combine to an affirmative meaning, plus biti-replaces-imati negated-existence pattern, Internal ordering rule for co-occurring pronominal enclitics (dative→genitive→accusative) plus ju/je accusative allomorphy — genuinely new relative to prior clitic-placement extractions

### Community 18 - "Pronoun System: Demonstratives & Reflexives"
Cohesion: 0.33
Nodes (6): Three-way deictic demonstrative system (ovaj/taj/onaj) extending to manner and extent compounds, Possessive pronoun declension as adjectives; reflexive svoj vs. 3rd-person possessive ambiguity, sebe/se true reflexivity and reciprocity; emphatic reflexive sam, Seven universal pronouns (svako, svašta, svaki, svačiji, svakakav, svi, sve) with declension-class and animacy restrictions, Five-type adjective semantic taxonomy (descriptive/possessive/material/time/place), each cross-tagged indefinite or definite by default, Possessive/demonstrative/indefinite/interrogative/negative determiner sub-classes

### Community 19 - "Deverbal Nouns & Adverb Classification"
Cohesion: 0.33
Nodes (6): Passive participle as base for a productive deverbal noun category (rešiti→rešen→rešenje), parallel to English -ing/-ion, Živeli! "Cheers!" and Živeo kralj! "Long live the King!" — active past participle used as a fixed salutation/toast formula, Four-way adverb morphological-origin classification: substantival, adjectival, pronominal, verbal, Indefinite/negative/universal branch of the pronominal-adverb grid (iko-/neko-/niko-/svako- series), Present and past verbal-adverb semantic range (manner/condition/cause), subject-identity constraint, and lexicalization into adjectives, ikada/nekada/nikada/svakada, ikako/nekako/nikako/svakako, igde/negde/nigde/svuda — the indefinite/negative/universal pronominal-adverb set

### Community 20 - "Enclitic Rules & Particle Inventory"
Cohesion: 0.33
Nodes (6): Four genuinely new enclitic-interaction procedural rules: title/name inseparability, a/i cannot trigger clitic placement, subject-after-cluster default, negated-past-auxiliary non-enclitic status, Chapter 17's full particle/conjunction/exclamation reference inventory — informal/discourse-register vocabulary, evo/eto — paired presentational-deictic particles ("here you are"/"there you are"), li interrogative enclitic and the ne bi li construction, flagged by the source as often carrying sarcastic/humorous overtones, Main/subordinate clause typology, including relative and interrogative subordinate clauses, Sentence-element typology: subject/predicate/object/complement/adverbial, and definiteness conveyed via aspect and word position

### Community 21 - "Standardization History: Illyrian & Vukovian Reform"
Cohesion: 0.60
Nodes (5): Illyrian movement (Ljudevit Gaj), Vukovian language-reform movement (Vuk Karadžić), ahavci vs. vukovci Illyrian-era factional split, NDH (1941-45) state-mandated language purism, phonological ("write as you speak") vs. morphophonemic ("write for the eye") spelling debate

### Community 22 - "Primary Dialect Split & Jat-Reflex System"
Cohesion: 0.40
Nodes (5): Kajkavian/Čakavian/Štokavian three-way dialect split (organized by the interrogative "what?": kaj/ča/što), Ikavian/Ijekavian/Ekavian jat-reflex sub-dialects of Štokavian, Vuk Karadžić's phonetic Cyrillic alphabet reform and vernacular dictionary (1818), 19th-century Serbo-Croatian unification and its late-20th-century political breakup, Illustrative jat-reflex vocabulary set: mliko/mlijeko/mleko "milk", vrime/vrijeme/vreme "time", pet "five" (counter-example)

### Community 23 - "Derivational Suffixes & Slang-Adjacent Vocabulary"
Cohesion: 0.40
Nodes (5): Five semantic noun types (proper/common/mass/collective/abstract) with characteristic derivational suffixes, narkoman "drug addict", siledžija "bully/rapist", kravetina "cow (derog., of a woman)" — slang-adjacent common-noun-suffix examples flagged for this project's slang-synthesis relevance, Capitalization rule for possessive adjectives (capitalized from proper name/nationality/deity/nickname, not from country/city/area -ski forms), Adjective-forming suffix categories: basic -k/-n pair, possessive suffixes (-in/-ji/-nji/-šnji/-ski/-ov/-ev), augmentative suffixes (-av/-at/-ovit), Noun-forming suffix categories: agent/event nouns from verbs, trait nouns from adjectives, place/professional/demonym/diminutive/pejorative nouns from nouns, o/e-linked compounding

### Community 24 - "Colloquial Idioms & Register-Tagged Exclamations"
Cohesion: 0.40
Nodes (5): Blago Tebi/Njoj — Fixed Exclamatory Idiom, Cura (coll.) — Source-Tagged Colloquial Register, Napiti Se — Reflexive Intoxication Verb, Gubi(te) Se! — Imperative-Phrase Idiom Set, Jesi li Normalan?! — Stock Exclamation

### Community 25 - "Conjunction System & Relative Clauses"
Cohesion: 0.50
Nodes (4): infinitive-loss / da + present change (east-to-west gradient), conjunction system §143 (a-k): compound conjunctions, da vs. što, kako, relative clauses: systematic case/gender/number agreement (A/R notation), jedan drugi / jedni drugi reciprocal construction

### Community 26 - "Community 26"
Cohesion: 0.67
Nodes (3): Cardinal Numbers and Case Government, Distributive and Collective-Numeral Declension, Obojica vs. Oboje — "Both" Gender Distinction

### Community 27 - "Community 27"
Cohesion: 0.67
Nodes (3): Demonstrative Pronouns (taj/ovaj/onaj), Possessive Adjectives from Proper Nouns, Relative Pronoun Koji/Što

### Community 28 - "Community 28"
Cohesion: 0.67
Nodes (3): Ђаво (đavo) — the devil, folk-demonology figure, Виле (vile/vily) — winged fairy-maidens of Serbian epic tradition, Усуд и Срећа — personified Fate and Fortune

## Ambiguous Edges - Review These
- `Lesson 9 (Deveta lekcija) — Belgrade/teen slang` → `STRUKE professions table — systematic C/S/[B] profession-lexeme comparison`  [AMBIGUOUS]
  established/013_lesson11.md · relation: references
- `palatalization: historical origin of Types A/B/C consonant softening` → `hypothesized connection: BCS phonotactics and syllable-switching slang mechanism (cf. Sarajevo/Zagreb slang documented elsewhere in this dataset, e.g. vozdra/zdravo, đido/dođi — not independently verified in this chunk)`  [AMBIGUOUS]
  established/045_grammar_ch20_phonology.md · relation: rationale_for
- `cluster simplification at morpheme boundaries` → `hypothesized connection: BCS phonotactics and syllable-switching slang mechanism (cf. Sarajevo/Zagreb slang documented elsewhere in this dataset, e.g. vozdra/zdravo, đido/dođi — not independently verified in this chunk)`  [AMBIGUOUS]
  established/045_grammar_ch20_phonology.md · relation: rationale_for

## Knowledge Gaps
- **212 isolated node(s):** `Bosnian, Croatian, Serbian, a Grammar: With Sociolinguistic Commentary (Alexander, 2006)`, `Serbian: An Essential Grammar (Hammond, Routledge, 2005)`, `Colloquial Serbian and Croatian (Hawkesworth)`, `Vukove bajke / Serbian Folk Tales`, `Future Tense Formation (clitic ću/ćeš/će)` (+207 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **16 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **What is the exact relationship between `Lesson 9 (Deveta lekcija) — Belgrade/teen slang` and `STRUKE professions table — systematic C/S/[B] profession-lexeme comparison`?**
  _Edge tagged AMBIGUOUS (relation: references) - confidence is low._
- **What is the exact relationship between `palatalization: historical origin of Types A/B/C consonant softening` and `hypothesized connection: BCS phonotactics and syllable-switching slang mechanism (cf. Sarajevo/Zagreb slang documented elsewhere in this dataset, e.g. vozdra/zdravo, đido/dođi — not independently verified in this chunk)`?**
  _Edge tagged AMBIGUOUS (relation: rationale_for) - confidence is low._
- **What is the exact relationship between `cluster simplification at morpheme boundaries` and `hypothesized connection: BCS phonotactics and syllable-switching slang mechanism (cf. Sarajevo/Zagreb slang documented elsewhere in this dataset, e.g. vozdra/zdravo, đido/dođi — not independently verified in this chunk)`?**
  _Edge tagged AMBIGUOUS (relation: rationale_for) - confidence is low._
- **Why does `Lila Hammond, "Serbian: An Essential Grammar" (Routledge, 2005) — third, Serbian-specific reference book for this language, distinct from the comparative B/C/S flagship textbook and the companion Alexander Grammar already extracted elsewhere in this dataset. This PDF's embedded Cyrillic font is corrupted on pdftotext extraction across the whole book; all files in this chunk use the book's parallel clean Latin-script transliteration as the primary form.` connect `Hammond's Serbian: Modal Verbs & Gender` to `Community 32`, `Community 33`, `Case-Governing Verb/Adjective Inventories`, `Hammond's Consonant Classification & Palatalization`, `Aorist Paradigms & Ići-Derivatives`, `Tense Negative/Interrogative System & Question Formation`, `Pronoun System: Demonstratives & Reflexives`, `Deverbal Nouns & Adverb Classification`, `Enclitic Rules & Particle Inventory`, `Primary Dialect Split & Jat-Reflex System`, `Derivational Suffixes & Slang-Adjacent Vocabulary`?**
  _High betweenness centrality (0.024) - this node is a cross-community bridge._
- **Why does `Bosnian, Croatian, Serbian: A Grammar with Sociolinguistic Commentary (Ronelle Alexander, 2006)` connect `Companion Grammar: Alphabets & Jat Reflex` to `Flagship Textbook: E/J & B/C/S Glossary Tagging`?**
  _High betweenness centrality (0.021) - this node is a cross-community bridge._
- **What connects `Bosnian, Croatian, Serbian, a Grammar: With Sociolinguistic Commentary (Alexander, 2006)`, `Serbian: An Essential Grammar (Hammond, Routledge, 2005)`, `Colloquial Serbian and Croatian (Hawkesworth)` to the rest of the system?**
  _212 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Source Book Catalog & Reference Docs` be split into smaller, more focused modules?**
  _Cohesion score 0.061955965181771634 - nodes in this community are weakly interconnected._