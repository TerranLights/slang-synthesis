# Graph Report - Hungarian  (2026-09-09)

## Corpus Check
- Corpus is ~30,668 words - fits in a single context window. You may not need a graph.

## Summary
- 60 nodes · 109 edges · 8 communities
- Extraction: 86% EXTRACTED · 14% INFERRED · 0% AMBIGUOUS · INFERRED: 15 edges (avg confidence: 0.74)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- Root-Family Radiation: hülye/agy/dög/baszik
- Polysemy Fans & Semantic Narrowing
- Ethnonym & Body-Type Euphemism Clusters
- Denominal Verbing & Prefix Stacking
- Graded-Vulgarity Dismissal Formulas
- Euphemism Substitution Templates
- Simile-Template Slot-Fillers
- Genericized Proper Names & Minced Oaths

## God Nodes (most connected - your core abstractions)
1. `Magyar Szlengszótár (source book)` - 47 edges
2. `Root-Family Radiation (one root, many senses)` - 9 edges
3. `Szinonimamutató (synonym index) section structure` - 8 edges
4. `Polysemy Fan (one base verb, unrelated senses)` - 7 edges
5. `Productive Denominal -zik/-ázik/-ozik Verbing` - 5 edges
6. `Simile-Template Slot-Filler (mint X constructions)` - 5 edges
7. `Semantic Bleaching of Violent/Mortality Roots Into Intensifiers` - 5 edges
8. `ki a fene?/franc?/picsa?/szar?/túró? escalation ladder` - 4 edges
9. `dög family (döglik/dögös/dögunalmas/dögrováson van)` - 4 edges
10. `szar- hub-noun compound family (9-sense polysemy + szarrágó, szarrá ver)` - 4 edges

## Surprising Connections (you probably didn't know these)
- `meg- perfective-prefix verb series` --semantically_similar_to--> `Productive Denominal -zik/-ázik/-ozik Verbing`  [INFERRED] [semantically similar]
  04_szlengszotar_dictionary_pp180-269.md → 02_szlengszotar_kovecses_A-E_sample.md
- `össze- "together" prefix verb series` --semantically_similar_to--> `Productive Denominal -zik/-ázik/-ozik Verbing`  [INFERRED] [semantically similar]
  04_szlengszotar_dictionary_pp180-269.md → 02_szlengszotar_kovecses_A-E_sample.md
- `ki a fene?/franc?/picsa?/szar?/túró? escalation ladder` --semantically_similar_to--> `mint X simile-template cluster (mint a mák/villám/pinán a szőr...)`  [INFERRED] [semantically similar]
  01_szlengszotar_dictionary_pp90-179.md → 04_szlengszotar_dictionary_pp180-269.md
- `elküld a francba/pitlibe/anyjába dismissal paradigm` --semantically_similar_to--> `ki a fene?/franc?/picsa?/szar?/túró? escalation ladder`  [INFERRED] [semantically similar]
  02_szlengszotar_kovecses_A-E_sample.md → 01_szlengszotar_dictionary_pp90-179.md
- `Arbitrary abstract-word euphemism redirection (előny, fax, galamb)` --cites--> `Magyar Szlengszótár (source book)`  [EXTRACTED]
  01_szlengszotar_dictionary_pp90-179.md → 00_Extraction_Checklist.md

## Hyperedges (group relationships)
- **Root-Family Radiation Instances Across the Dictionary** — language_corpus_hungarian_02_szlengszotar_kovecses_a_e_sample_root_family_radiation, language_corpus_hungarian_02_szlengszotar_kovecses_a_e_sample_agy_family, language_corpus_hungarian_02_szlengszotar_kovecses_a_e_sample_duma_family, language_corpus_hungarian_02_szlengszotar_kovecses_a_e_sample_dog_family, language_corpus_hungarian_03_szlengszotar_dictionary_pp270_336_zsir_haj_family, language_corpus_hungarian_04_szlengszotar_dictionary_pp180_269_segg_family, language_corpus_hungarian_04_szlengszotar_dictionary_pp180_269_szar_family, language_corpus_hungarian_04_szlengszotar_dictionary_pp180_269_lo_family [INFERRED 0.85]
- **Taboo-Root Compounding Hub Nouns** — language_corpus_hungarian_04_szlengszotar_dictionary_pp180_269_taboo_root_compounding, language_corpus_hungarian_04_szlengszotar_dictionary_pp180_269_segg_family, language_corpus_hungarian_04_szlengszotar_dictionary_pp180_269_szar_family, language_corpus_hungarian_04_szlengszotar_dictionary_pp180_269_lofasz_taboo_compounds, language_corpus_hungarian_02_szlengszotar_kovecses_a_e_sample_agy_family [INFERRED 0.80]
- **Productive Denominal Verbing Across the Book** — language_corpus_hungarian_02_szlengszotar_kovecses_a_e_sample_denominal_verbing_suffix, language_corpus_hungarian_02_szlengszotar_kovecses_a_e_sample_denominal_verbing_examples, language_corpus_hungarian_03_szlengszotar_dictionary_pp270_336_denominal_verbing_examples, language_corpus_hungarian_01_szlengszotar_dictionary_pp90_179_gany_ganyol_denominal_verb [INFERRED 0.85]

## Communities (8 total, 0 thin omitted)

### Community 0 - "Root-Family Radiation: hülye/agy/dög/baszik"
Cohesion: 0.18
Nodes (13): hülye — most productive headword sampled, kibaszott / kibaszott jó / kibaszottul intensifier family, agy family (agyal/agyament/agyfasz/agyhúgykövet kap), baszik(ik) family (baszd meg, baszki(kám)), dög family (döglik/dögös/dögunalmas/dögrováson van), dugás family (dugás/dugesz/dugi/dugipénz — sex vs. concealment branch), duma family (dumagép/dumál/dumálgat/dumcsi/dumcsizik...), Root-Family Radiation (one root, many senses) (+5 more)

### Community 1 - "Polysemy Fans & Semantic Narrowing"
Cohesion: 0.30
Nodes (12): Magyar Szlengszótár (source book), elszáll polysemy fan (ejaculation/drug high/crash), kever polysemy (walk/trouble/sex/busy), bögre semantic narrowing (girlfriend/woman/vagina), lő / lök / löket polysemy fan on motion-verb bases, lófasz a seggedbe! / lófasz(t)! taboo rejection compounds, Polysemy Fan (one base verb, unrelated senses), potyázik 7-sense polysemy chain (freeloading) (+4 more)

### Community 2 - "Ethnonym & Body-Type Euphemism Clusters"
Cohesion: 0.25
Nodes (9): Page-Mapping & Representative-Sampling Methodology, Flagged ethnic slurs (feka/fekália, kgst indián, húzott szemű), cigány synonym-index ethnonym-substitution cluster, Ethnonym-as-Euphemism Substitution Family, kövér (fat) synonym-index cluster, közösül (sex) synonym-index cluster, ~40+ items, Szinonimamutató (synonym index) section structure, zsandár/zsaru/zsernyák/zsé police-slang cluster (+1 more)

### Community 3 - "Denominal Verbing & Prefix Stacking"
Cohesion: 0.38
Nodes (7): gány → gányol denominal verb, Denominal verbing examples (cserkészik, bazíroz, bemagol), Productive Denominal -zik/-ázik/-ozik Verbing, Denominal verbing at alphabet tail (sztárol, szuperál, szörfözik, zsugázik), Agglutinative Prefix Stacking (meg-/össze- verb series), meg- perfective-prefix verb series, össze- "together" prefix verb series

### Community 4 - "Graded-Vulgarity Dismissal Formulas"
Cohesion: 0.40
Nodes (6): ki a fene?/franc?/picsa?/szar?/túró? escalation ladder, Graded-Vulgarity Dismissal-Formula Slot-Filler, elküld a francba/pitlibe/anyjába dismissal paradigm, löki a X-et evasive-talk slot-filler template, löki a (nagy/link/rabló/rossz/süket) dumát two-slot template, mint X simile-template cluster (mint a mák/villám/pinán a szőr...)

### Community 5 - "Euphemism Substitution Templates"
Cohesion: 0.40
Nodes (5): Arbitrary abstract-word euphemism redirection (előny, fax, galamb), elmész a francba!/picsába! (2-step ladder variant), Euphemism Substitution With Swappable Destination/Object, lemegy a keszonba / lemegy Turkesztánba (oral sex euphemism pair), Register-Escalation Ladder (one frame, graded vulgarity)

### Community 6 - "Simile-Template Slot-Fillers"
Cohesion: 0.40
Nodes (5): hány, mint a lakodalmas/murányi kutya (vomiting simile), kevés vagy, mint... escalating put-down simile chain, akkora, mint egy ház/olajtó/liftajtó simile slot, berúg intoxication cluster + berúg, mint a X simile, Simile-Template Slot-Filler (mint X constructions)

### Community 7 - "Genericized Proper Names & Minced Oaths"
Cohesion: 0.67
Nodes (3): Genericized proper names (Kovács János, HVCS, linda, háryjános), basszorkányos Varga János! / béna béla / Móricka, Rhyming/Alliterative Stock-Name Substitution (minced oaths)

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Magyar Szlengszótár (source book)` connect `Polysemy Fans & Semantic Narrowing` to `Root-Family Radiation: hülye/agy/dög/baszik`, `Ethnonym & Body-Type Euphemism Clusters`, `Denominal Verbing & Prefix Stacking`, `Graded-Vulgarity Dismissal Formulas`, `Euphemism Substitution Templates`, `Simile-Template Slot-Fillers`, `Genericized Proper Names & Minced Oaths`?**
  _High betweenness centrality (0.914) - this node is a cross-community bridge._
- **Why does `elmész a francba!/picsába! (2-step ladder variant)` connect `Euphemism Substitution Templates` to `Polysemy Fans & Semantic Narrowing`?**
  _High betweenness centrality (0.027) - this node is a cross-community bridge._
- **Why does `meg- perfective-prefix verb series` connect `Denominal Verbing & Prefix Stacking` to `Polysemy Fans & Semantic Narrowing`?**
  _High betweenness centrality (0.023) - this node is a cross-community bridge._
- **Are the 2 inferred relationships involving `Productive Denominal -zik/-ázik/-ozik Verbing` (e.g. with `meg- perfective-prefix verb series` and `össze- "together" prefix verb series`) actually correct?**
  _`Productive Denominal -zik/-ázik/-ozik Verbing` has 2 INFERRED edges - model-reasoned connections that need verification._