# Graph Report - Serbian_Croatian_Bosnian  (2026-08-30)

## Corpus Check
- Large corpus: 68 files · ~515,802 words. Semantic extraction will be expensive (many Claude tokens). Consider running on a subfolder.

## Summary
- 264 nodes · 393 edges · 29 communities (21 shown, 8 thin omitted)
- Extraction: 81% EXTRACTED · 19% INFERRED · 1% AMBIGUOUS · INFERRED: 74 edges (avg confidence: 0.78)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- Magner: Cr./S. Comparative Convention & Syntactic Divergence
- Flagship Textbook: B/C/S Tagging & Verb System
- Core Grammar Mechanisms (Aspect, Clitics, Softening)
- Hammond: Alphabet, Stress & Interrogative Inventory
- Naming Disputes & Standardization Agreements
- Consonant Softening, Jat Reflex & the XYZ Model
- Flagship Textbook: B/C/S Lexical-Choice Pairs
- Early Source-Labeled Slang & Project Index Docs
- Bosnian/Bosniak Identity & Turkish Loanword Layer
- Verb Tense Paradigms (Aorist, Future, Present)
- Numeral System & Irregular Noun Declension
- Imperative, Instrumental Case & Se-Verb Taxonomy
- Pronoun Declension & Enclitic Ordering
- National Lexical Variants & the East-West Syntax Shift
- Word Formation & the Syllable-Switching Slang Connection
- Jat-Reflex Sub-Dialects & Vuk Karadžić Reform
- Case-Governing Verb/Adjective Inventories
- Noun Types & Slang-Adjacent Derogatory Vocabulary
- Modal Verbs (trebati, moći, potreban)
- Adverb Classification & Lexicalized Verbal Adverbs
- Discourse Particles & Register-Marked Interjections
- Community 21
- Community 22
- Community 23
- Community 24
- Community 25
- Community 26
- Community 27
- Community 28

## God Nodes (most connected - your core abstractions)
1. `Hammond, Serbian: An Essential Grammar (2005)` - 48 edges
2. `Magner, Introduction to the Croatian and Serbian Language (source book; continues established/002's Lesson 1 coverage via the same [Cr.]/[S.] comparative-dialect convention)` - 30 edges
3. `B/C/S Dialect-Tag Convention ([B]/[C]/[S])` - 15 edges
4. `Bosnian, Croatian, Serbian: A Textbook (Alexander & Elias-Bursać, 2010)` - 15 edges
5. `Bosnian, Croatian, Serbian, a Grammar with Sociolinguistic Commentary (Alexander, 2006)` - 15 edges
6. `Bosnian, Croatian, Serbian, a Textbook: With Exercises and Basic Grammar (Alexander & Elias-Bursać, 2010)` - 13 edges
7. `Ekavian/Ijekavian Jat-Reflex Split ([E]/[J])` - 12 edges
8. `Lesson 6 (Šesta lekcija)` - 10 edges
9. `Lesson 10 (Deseta lekcija)` - 10 edges
10. `B/C/S Regional Lexical Tagging Convention` - 9 edges

## Surprising Connections (you probably didn't know these)
- `Serbian/Croatian/Bosnian Slang Mechanics Extraction Checklist` --references--> `Bosnian, Croatian, Serbian, a Textbook: With Exercises and Basic Grammar (Alexander & Elias-Bursać, 2010)`  [EXTRACTED]
  00_Extraction_Checklist.md → 00_Book_Triage_Catalog.md
- `Serbian/Croatian/Bosnian Slang Mechanics Extraction Checklist` --references--> `Bosnian, Croatian, Serbian, a Grammar: With Sociolinguistic Commentary (Alexander, 2006)`  [EXTRACTED]
  00_Extraction_Checklist.md → 00_Book_Triage_Catalog.md
- `Serbian/Croatian/Bosnian Slang Mechanics Extraction Checklist` --references--> `Serbian: An Essential Grammar (Hammond, 2005)`  [EXTRACTED]
  00_Extraction_Checklist.md → 00_Book_Triage_Catalog.md
- `Lesson 10 (Deseta lekcija)` --semantically_similar_to--> `Locative/Dative Case Syncretism`  [INFERRED] [semantically similar]
  established/012_lesson10.md → established/008_lesson06.md
- `pozdrav (printed gender marker inconsistency)` --conceptually_related_to--> `Grammar Chapters 4-6: Possessive Adjectives, Genitive Plural, Aspect Derivation`  [AMBIGUOUS]
  established/029_glossary_bcs_english_part4.md → established/038_grammar_ch4-6_supplementary.md

## Hyperedges (group relationships)
- **BCS Oblique-Case System Buildup (Genitive → Locative/Dative → Instrumental)** — established_006_lesson04, established_008_lesson06, established_009_lesson07, concept_bcs_genitive_case_usage, concept_bcs_locative_dative_case, concept_bcs_instrumental_case [INFERRED 0.85]
- **BCS Compound-Tense System (Future and Past, both built on biti + non-finite form)** — established_011_lesson09, established_012_lesson10, concept_bcs_future_tense_formation, concept_bcs_past_tense_l_participle, concept_bcs_clitic_word_order [INFERRED 0.85]
- **This Project's Earliest Source-Labeled Slang/Colloquial Findings** — established_009_lesson07, established_011_lesson09, concept_bcs_amusing_slang_ma_moj, concept_bcs_teen_slang_family_terms, vocab_bcs_stara_stari_starci [EXTRACTED 1.00]
- **B/C/S Dialect-Tagging Convention Across the Corpus** — established_014_lesson12_bcs_dialect_tagging, established_019_lesson17_historija_povijest_istorija, established_023_appendices1-6_personal_names_tagging, established_026_glossary_part1_bcs_english_glossary, established_028_glossary_part3_smejati_smijati_se [INFERRED 0.80]
- **Ekavian/Ijekavian Jat-Reflex System** — established_014_lesson12_ekavian_ijekavian_alternation, established_021_lesson19_montenegrin_dialect, established_022_lesson20_jat_reflex_dual_presentation, established_024_appendix9_verb_type_system [INFERRED 0.85]
- **Syllable-Switching Slang Mechanism and Its Textual Evidence** — established_025_appendices7-8_syllable_switching_slang, established_025_appendices7-8_vozdra, established_014_lesson12_bcs_dialect_tagging [INFERRED 0.75]
- **BCS jat-reflex dialect system, treated across sociolinguistic and grammar chapters** — concept_jat_reflex_ekavian_ijekavian_ikavian, established_032_socioling_ch22_dete_dijete_dite_triad, established_037_grammar_ch1_3_jat_term, established_045_grammar_ch20_phonology_chapter [INFERRED 0.80]
- **B/C/S national-standard naming and identity politics across sociolinguistic chapters** — concept_bosnian_bosniak_naming_dispute, concept_novi_sad_agreement_1954, concept_s_language_c_language_distinction, concept_croatian_declaration_1967, concept_montenegrin_language_movement_nikcevic [INFERRED 0.85]
- **XYZ/rhythmic-constituent clitic-placement model built progressively across grammar chapters 1-3, 7-9, and 19** — concept_xyz_clitic_rhythmic_constituent_model, established_037_grammar_ch1_3_supplementary_chapter, established_039_grammar_ch7_9_supplementary_chapter, established_044_grammar_ch19_clitic_accent_chapter [INFERRED 0.90]
- **Serbian dialect classification and alphabet-reform history** — established_046_serbian_essential_ch1_2_cultural_dialects_kajkavski_cakavski_stokavski_split, established_046_serbian_essential_ch1_2_cultural_dialects_jat_reflex_subdialects, established_046_serbian_essential_ch1_2_cultural_dialects_vuk_karadzic_alphabet_reform [INFERRED 0.85]
- **Extended case-usage system beyond the flagship textbook (genitive/dative/vocative)** — established_050_serbian_essential_ch7a_nouns_part1_genitive_case_usage_extended, established_050_serbian_essential_ch7a_nouns_part1_dative_case_verb_classes, established_050_serbian_essential_ch7a_nouns_part1_vocative_case_formation_rules [INFERRED 0.85]
- **Enclitic-mechanics threads spanning pronoun, enclitic-order, and future-tense chapters** — established_052_serbian_essential_ch8_pronouns_enclitic_pronoun_ordering, established_055_serbian_essential_ch12_13_conjunctions_enclitics_enclitic_ordering_procedural_rules, established_048_serbian_essential_ch6a_verbs_part1_future_tense_formation_mechanics [INFERRED 0.75]
- **The book's escalating toolkit of Cr./S. dialect-contrast devices: slash-pair tags, jat reflex, regional lexical-choice pairs, a genuine syntactic (future-tense) divergence, and full parallel-narrative substitution** — established_059_magner_lesson02_06_cr_s_dual_presentation_convention, established_059_magner_lesson02_06_jat_reflex_pattern, established_059_magner_lesson02_06_regional_lexical_choice_pairs, established_059_magner_lesson02_06_future_tense_syntactic_divergence, established_064_magner_lesson27_30_parallel_narrative_lexical_substitution [INFERRED 0.85]
- **Regional/sub-dialect axes the book documents that are orthogonal to its usual standard-Croatian/standard-Serbian binary: kajkavian (Zagorje), Dalmatian ikavian/coastal, and neighboring South Slavic languages given for comparison** — established_063_magner_lesson22_26_kajkavian_song_po_lojtrici, established_061_magner_lesson12_16_oj_violo_song, established_064_magner_lesson27_30_south_slavic_comparison_text [INFERRED 0.85]
- **The book's recurring pedagogical pattern of compact stand-alone domain-vocabulary reference boxes (occupations, months, countries, body parts, clothing, foods, weights/measures, nationality designations) presented separately from the running dialogues** — established_060_magner_lesson07_11_occupations_glossary, established_061_magner_lesson12_16_dual_month_name_systems, established_061_magner_lesson12_16_countries_continents_glossary, established_061_magner_lesson12_16_body_parts_glossary, established_062_magner_lesson17_21_clothing_vocabulary, established_063_magner_lesson22_26_common_foods_glossary, established_062_magner_lesson17_21_weights_measures_glossary, established_064_magner_lesson27_30_nationality_designations_list [INFERRED 0.75]

## Communities (29 total, 8 thin omitted)

### Community 0 - "Magner: Cr./S. Comparative Convention & Syntactic Divergence"
Cohesion: 0.08
Nodes (37): abeceda (Cr.) / azbuka (S.) — "alphabet", illustrative Lesson 2 Cr./S. tagged lexical pair, Cr./S. slash-pair and dual-column dialect presentation convention (single-word diffs slashed, multi-word diffs given as separate tagged sentences), Lesson 6 future-tense Cr./S. syntactic divergence: Cr. infinitive + cliticized htjeti vs S. da + present as alternative construction — first genuine syntactic (not phonological/lexical) Cr./S. axis found, Ijekavian/ekavian jat-reflex (ije/je vs e) pattern, incl. the jekavski/ijekavski synonym label and dialect-choice guidance, "Krivi broj" (Wrong Number) anecdote — the book's first deliberately unaccented running text, showcasing real-world printed Cr&S orthography, Magner, Introduction to the Croatian and Serbian Language (source book; continues established/002's Lesson 1 coverage via the same [Cr.]/[S.] comparative-dialect convention), Regional lexical-choice pairs beyond the jat split (ploca/tabla, obitelj/porodica, glazba/muzika, kazaliste/pozoriste, ured/kancelarija, kravata/masna, zlica/kasika), Vocative case address forms (Lesson 6): masc. titles -e/-u, fem. titles -o, surname stays unchanged (+29 more)

### Community 1 - "Flagship Textbook: B/C/S Tagging & Verb System"
Cohesion: 0.08
Nodes (36): B/C/S Regional Lexical Tagging Convention, Bosnian, Croatian, Serbian: A Textbook (Alexander & Elias-Bursać, 2010), da li vs. clitic -li Question Formation, Ekavian/Ijekavian (Jat Reflex) Alternation, odoh ja (colloquial aorist idiom, "I'm out of here"), BCS Conditional Mood (formation, politeness, conditionals), Indirect Discourse Tense Preservation (no backshift), Relative Pronoun koji (gender/number vs. case agreement) (+28 more)

### Community 2 - "Core Grammar Mechanisms (Aspect, Clitics, Softening)"
Cohesion: 0.16
Nodes (33): Adjective Comparison (-ij- suffix / consonant softening), Verbal Aspect (Perfective/Imperfective), B/C/S Dialect-Tag Convention ([B]/[C]/[S]), Clitic Second-Position / Ordering Rule, Consonant Softening (Palatalization Set), Ekavian/Ijekavian Jat-Reflex Split ([E]/[J]), Future Tense (clitic ću/ćeš/će auxiliary), Genitive Case (formation and uses) (+25 more)

### Community 3 - "Hammond: Alphabet, Stress & Interrogative Inventory"
Cohesion: 0.15
Nodes (15): Hammond, Serbian: An Essential Grammar (2005), Serbo-Croatian unification and its late-20th-century breakup, South Slavic language classification, Cyrillic ↔ Latin alphabet correspondence table, Beginner stress-placement heuristic and vowel-length register note, Nine-way inventory of interrogative-formation strategies, The 'true double negative' (two negatives cancel to affirmative), Accusative singular animate/inanimate split for masculine nouns (+7 more)

### Community 4 - "Naming Disputes & Standardization Agreements"
Cohesion: 0.21
Nodes (14): 1967 Croatian "Declaration on the Name and Position of the Croatian Literary Language", Montenegrin-language movement (Vojislav Nikčević, 1994-1997), 1954 Novi Sad Agreement (Serbo-Croatian / Croato-Serbian naming, varijanta framework), Štokavian / čakavian / kajkavian primary dialect split, "Varijanta" (variant) east/west descriptive framework for Serbo-Croatian, ćirilica (Cyrillic alphabet, BCS term), gajica (modern Croatian name for the Latin alphabet, honoring Ljudevit Gaj), glagoljica (Glagolitic alphabet) (+6 more)

### Community 5 - "Consonant Softening, Jat Reflex & the XYZ Model"
Cohesion: 0.21
Nodes (13): Three-way consonant softening system (Types A, B, C), Jat reflex: ekavian / ijekavian / ikavian dialect split, XYZ / rhythmic constituent model of BCS clitic placement, Bosnian, Croatian, Serbian, a Grammar with Sociolinguistic Commentary (Alexander, 2006), jat (name of the historical Slavic sound underlying the ekavian/ijekavian split), Grammar Chapters 1-3: Accent Notation, Jat, XYZ Clitic Model, Case System Overview, Aorist and imperfect tense — condensed paradigm reference (§122a), "Body-ache" construction: prefixed variants of boleti/boljeti (+5 more)

### Community 6 - "Flagship Textbook: B/C/S Lexical-Choice Pairs"
Cohesion: 0.18
Nodes (11): Bosnian, Croatian, Serbian, a Textbook (Alexander & Elias-Bursać, 2010), posvetiti se / posvećujem se (mid-entry glossary continuation), pozdrav (printed gender marker inconsistency), projekat [B,S] / projekt [B,C] "project", šta [B,S] / što [C] "what", sto [B,S] / stol [C] "table", svest [E] / svijest [J] "consciousness", Possessive pronominal adjective formation (five-step stem-shift process) (+3 more)

### Community 7 - "Early Source-Labeled Slang & Project Index Docs"
Cohesion: 0.31
Nodes (9): "Ma moj!" Slang Retort (source-labeled slang), Teen/Regional Slang Family-Address Terms (kèva, stara/stari/starci), Book Triage Catalog, Serbian/Croatian/Bosnian Slang Mechanics Extraction Checklist, Magner Lesson 1 (vision-reading test), Bosnian, Croatian, Serbian, a Grammar: With Sociolinguistic Commentary (Alexander, 2006), Introduction to the Croatian and Serbian Language (Magner, rev. 1991/1998), Serbian: An Essential Grammar (Hammond, 2005) (+1 more)

### Community 8 - "Bosnian/Bosniak Identity & Turkish Loanword Layer"
Cohesion: 0.28
Nodes (9): Bosnian vs. Bosniak language-naming dispute, Proposed /h/-restoration in Bosnian/Bosniak orthography (kahva, sahat, lahak, mehak), S-language (symbolic) vs. C-language (communicative) distinction, Turcizmi — Turkish-derived loanwords characteristic of Bosnian speech, bosanski jezik ("Bosnian language", contested official school-language name), Chapter 23: Bosnia (language and identity politics), ćuprija (Turkish-derived) / most (native) "bridge" doublet, naš jezik / naški ("our language", situationally-scoped self-referential term) (+1 more)

### Community 9 - "Verb Tense Paradigms (Aorist, Future, Present)"
Cohesion: 0.22
Nodes (9): Aorist tense: uses and full worked paradigms, Future tense formation mechanics (enclitic ću/infinitive fusion), Present-tense negative/interrogative/negative-interrogative paradigm, zagrepsti, zagrebem ('to scratch'), Ići derivatives — additional prefixed forms (proći, prići, naći...), kišobran ('umbrella', stacked word-formation example), krvav ('bloody', augmentative suffix -av), Noun-forming suffix categories (agent/event/trait/place/demonym/diminutive) (+1 more)

### Community 10 - "Numeral System & Irregular Noun Declension"
Cohesion: 0.22
Nodes (9): čovek ↔ ljudi suppletive counting rule, Declension of irregular nouns — seven irregularity types, nebo/čudo -es- infix class (nebo→nebesa), Collective numerals (dvoje/troje/četvoro... mixed-gender groups), dvojica (a group of two male human beings), Four numeral-form system (cardinal/ordinal/collective/number-noun), jedanaesterac ('a penalty kick', from jedanaest 'eleven'), Number nouns (dvojica/trojica... male-human-only groups) (+1 more)

### Community 11 - "Imperative, Instrumental Case & Se-Verb Taxonomy"
Cohesion: 0.29
Nodes (8): Aspect-pair formation typology (simplex, prefixal, derived-imperfective), Se-verb functional taxonomy (reflexive, reciprocal, inclinational, passive, intransitivizing, impersonal), Full productive imperative-mood system (stem derivation, hajde, neka, nemoj), Bare (prepositionless) instrumental case functions, Grammar Chapters 7-9: Imperative, Instrumental, Vocative, Se-verbs, Future Tense, Conditional sentence taxonomy: real / potential / unreal (§132), BCS conjunction system (a-k): compound conjunctions, da vs. što, kako, doubled comparatives (§143), Grammar Chapters 13-16: Conditional Mood, Relative Clauses, Conjunctions, Full Verb Paradigms

### Community 12 - "Pronoun Declension & Enclitic Ordering"
Cohesion: 0.25
Nodes (8): Order of unstressed personal pronouns (dative→genitive→accusative), Declension of personal pronouns (stressed/unstressed forms), Reflexive possessive svoj vs. njegov/njen, sebe / se (reflexive pronoun), svoj / svoje / svoja ('one's own'), Order and importance of enclitics — procedural rules, Indefinite and negative determiners (neki/bilo koji/ničiji...), Quantifier classification (countable/uncountable/collective)

### Community 13 - "National Lexical Variants & the East-West Syntax Shift"
Cohesion: 0.29
Nodes (7): Genuine B/C/S national lexical-variant pairs (not just phonological E/J splits), Loss of the infinitive, replaced by da + present (live east-to-west syntactic change), dete/dijete/dite "child" (ekavian/ijekavian/ikavian jat-reflex triad), Chapter 22: Dialect Differences, kava [C] / kafa [S] / kahva [B] "coffee", Grammar Chapter 17: Cases of Nouns, Review, Full case-governing preposition inventory (Acc/Gen/Dat/Loc/Instr)

### Community 14 - "Word Formation & the Syllable-Switching Slang Connection"
Cohesion: 0.40
Nodes (5): BCS derivational word formation (verbal prefixation, nominal suffixation, compounding), zrakomlat (purist coinage) vs. helikopter (loanword) "helicopter", Agentive and diminutive nominal suffixes (slang-formation-relevant productive morphology), Grammar Chapter 18: Word Formation, Phonotactic connection to BCS syllable-switching slang (vozdra, đido, žibje)

### Community 15 - "Jat-Reflex Sub-Dialects & Vuk Karadžić Reform"
Cohesion: 0.40
Nodes (5): Jat-reflex sub-dialects (Ikavian/Ijekavian/Ekavian), Kajkavian/Čakavian/Štokavian three-way dialect split, mleko/mlijeko/mliko jat-reflex triad ('milk'), štokavski (Štokavian dialect), Vuk Karadžić's phonetic alphabet reform

### Community 16 - "Case-Governing Verb/Adjective Inventories"
Cohesion: 0.40
Nodes (5): Consonant classification framework (obstruent/resonant, place), /j/-mutation table (consonant + j merges), Dative case — closed-class verb inventories by semantic type, Genitive case usage — closed-class governing adjectives/verbs, partitive nouns, Vocative case formation rules (consonant alternations, -a→-o shift)

### Community 17 - "Noun Types & Slang-Adjacent Derogatory Vocabulary"
Cohesion: 0.40
Nodes (5): kravetina ('cow', derogatory of a woman), narkoman ('drug addict'), Types of nouns (proper/common/mass/collective/abstract), siledžija ('bully, rapist'), Possessive-adjective capitalization rule

### Community 18 - "Modal Verbs (trebati, moći, potreban)"
Cohesion: 0.50
Nodes (4): moći (can/be able to) full present paradigm, potreban, potrebna (necessary; impersonal alternative to trebati), trebati (to need to/have to/should), Trebati's five da-clause modal constructions

### Community 19 - "Adverb Classification & Lexicalized Verbal Adverbs"
Cohesion: 0.50
Nodes (4): Four-way adverb morphological classification, bivši ('former', lexicalized past verbal adverb), budući ('future', lexicalized present verbal adverb), Pronominal-adverb indefinite/negative/universal branch (iko-/neko-/niko-/svako-)

### Community 20 - "Discourse Particles & Register-Marked Interjections"
Cohesion: 0.50
Nodes (4): baš (emphatic particle, 'exactly/really'), evo / eto (paired presentational-deictic particles), li / ne bi li (interrogative particle; sarcastic-hope construction), Particles, conjunctions and exclamations inventory (Ch.17)

## Ambiguous Edges - Review These
- `pozdrav (printed gender marker inconsistency)` → `Grammar Chapters 4-6: Possessive Adjectives, Genitive Plural, Aspect Derivation`  [AMBIGUOUS]
  established/029_glossary_bcs_english_part4.md · relation: conceptually_related_to
- `Regional lexical-choice pairs beyond the jat split (ploca/tabla, obitelj/porodica, glazba/muzika, kazaliste/pozoriste, ured/kancelarija, kravata/masna, zlica/kasika)` → `mangup — colloquial/slang term for a rascal or scamp, Turkish-derived, term of affectionate reproach`  [AMBIGUOUS]
  established/063_magner_lesson22-26.md · relation: conceptually_related_to

## Knowledge Gaps
- **97 isolated node(s):** `Lesson 1 Basics (superseded manual test-run)`, `stara/stari/starci (teen slang for parents)`, `BCS Collective Nouns`, `Present and Past Verbal Adverbs`, `odoh ja (colloquial aorist idiom, "I'm out of here")` (+92 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **8 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **What is the exact relationship between `pozdrav (printed gender marker inconsistency)` and `Grammar Chapters 4-6: Possessive Adjectives, Genitive Plural, Aspect Derivation`?**
  _Edge tagged AMBIGUOUS (relation: conceptually_related_to) - confidence is low._
- **What is the exact relationship between `Regional lexical-choice pairs beyond the jat split (ploca/tabla, obitelj/porodica, glazba/muzika, kazaliste/pozoriste, ured/kancelarija, kravata/masna, zlica/kasika)` and `mangup — colloquial/slang term for a rascal or scamp, Turkish-derived, term of affectionate reproach`?**
  _Edge tagged AMBIGUOUS (relation: conceptually_related_to) - confidence is low._
- **Why does `Hammond, Serbian: An Essential Grammar (2005)` connect `Hammond: Alphabet, Stress & Interrogative Inventory` to `Verb Tense Paradigms (Aorist, Future, Present)`, `Numeral System & Irregular Noun Declension`, `Pronoun Declension & Enclitic Ordering`, `Jat-Reflex Sub-Dialects & Vuk Karadžić Reform`, `Case-Governing Verb/Adjective Inventories`, `Noun Types & Slang-Adjacent Derogatory Vocabulary`, `Modal Verbs (trebati, moći, potreban)`, `Adverb Classification & Lexicalized Verbal Adverbs`, `Discourse Particles & Register-Marked Interjections`, `Community 23`, `Community 24`, `Community 25`, `Community 26`?**
  _High betweenness centrality (0.077) - this node is a cross-community bridge._
- **Why does `Bosnian, Croatian, Serbian, a Grammar with Sociolinguistic Commentary (Alexander, 2006)` connect `Consonant Softening, Jat Reflex & the XYZ Model` to `Naming Disputes & Standardization Agreements`, `Flagship Textbook: B/C/S Lexical-Choice Pairs`, `Bosnian/Bosniak Identity & Turkish Loanword Layer`, `Imperative, Instrumental Case & Se-Verb Taxonomy`, `National Lexical Variants & the East-West Syntax Shift`, `Word Formation & the Syllable-Switching Slang Connection`?**
  _High betweenness centrality (0.050) - this node is a cross-community bridge._
- **What connects `Lesson 1 Basics (superseded manual test-run)`, `stara/stari/starci (teen slang for parents)`, `BCS Collective Nouns` to the rest of the system?**
  _97 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Magner: Cr./S. Comparative Convention & Syntactic Divergence` be split into smaller, more focused modules?**
  _Cohesion score 0.07657657657657657 - nodes in this community are weakly interconnected._
- **Should `Flagship Textbook: B/C/S Tagging & Verb System` be split into smaller, more focused modules?**
  _Cohesion score 0.0761904761904762 - nodes in this community are weakly interconnected._