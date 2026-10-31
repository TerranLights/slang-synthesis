# Spanish Slang Mechanics — Extraction Checklist

**Purpose:** analyze the actual mechanics of how Spanish slang forms and works, using the corpus
collected in `language_corpus/Spanish/` and, where useful, the grammar/vocabulary reference in
`source_reference/languages/Spanish/`. Findings here are what eventual synthesis work (deriving
invented slang for the sci-fi setting) will be grounded in.

**This is research only — nothing here is canon** until worked into actual setting material by
explicit decision.

**Status legend:** `[x]` analyzed and written into its output file · `[ ]` not yet done.

**Full triage:** original corpus — see `00_Book_Triage_Catalog.md` (189MB, 133 PDF + 1 EPUB, only 3
of ~14 sources lack a text layer). A second, much larger external-drive stash (16GB, 144 curated
files across folders 01-09) was triaged 2026-10-25 — see `00_Book_Triage_Catalog_NEW_STASH.md` —
and fully extracted across Waves S1 and 2-5 (2026-10-30). **Phase 1 is now complete: 175 total
established files.**

---

## Morphological typology

**Spanish: fusional (inflectional)**, two-gender noun system, verb conjugation marking person/
number/tense/mood/aspect via stem suffixation — no case marking on nouns (only pronouns retain
case-like forms). ser/estar copula split and tú/vos/usted register variation (which differs across
the 5 GINI-represented nations — Spain, Mexico, Argentina, Chile, Uruguay) are the structural
features most relevant to register/slang work. To be refined with real morpheme-breakdown examples
once extraction lands.

---

## Output files — Markdown, sharded by numbered file, not JSON

| Directory | Contents | Numbering |
|---|---|---|
| `established/` | The real Spanish baseline — vocabulary/grammar tables extracted per lesson/chapter/section, per `00_Reference_Extraction_Spec.md` | `001_<label>.md`, `002_<label>.md`, ... |
| `analysis/` | Mechanics findings, one file per mechanism (or closely related group), narrative writeup + examples table | `001_<mechanism>.md`, ... |
| `synthesized/` | Derived in-universe slang output, one file per batch. **Explicitly provisional** — revise via each term's own Revision History subsection, never silent overwrite | `001_<batch>.md`, ... |

### Output files table

**Wave 1 complete (2026-09-14): 45 files, ~313,600 words, 11 distinct sources.**

| File(s) | Contents |
|---|---|
| `001_colloquial_spanish_latin_america.md` | Full 168p — rich LatAm-vs-Iberian register/dialect splits (chico/pequeño, coger's regional taboo flag, vosotros vs. ustedes) |
| `002_colloquial_spanish_latin_america_2.md` | Full 190p — **flagship find**: a full voseo paradigm (Unit 8, vos/sos present indicative/imperative/subjunctive); country-tagged slang (chévere, ¡Híjole!, ¡Qué vaina!) |
| `003/004/004b_madrigals_magic_key_part1/2/glossary.md` (3 files) | Full 740p mnemonic-based grammar — representative sampling of formulaic cognate-suffix categories (documented scope decision); explicit Mexican-slang appendix (güero, plata) |
| `005_practice_makes_perfect_basic_spanish_grammar.md` | Full 273p, 50 lessons, 872 vocabulary rows |
| `006_practice_makes_perfect_advanced_spanish_grammar.md` | Full 210p — ~90-idiom catalog (Unit 12), diminutive regional split (-ico/-illo/-ito), Argentine recién+preterit |
| `007_practice_makes_perfect_spanish_irregular_verbs.md` | Full 127p, 97-verb principal-parts glossary |
| `008/008b/008c_practice_makes_perfect_spanish_verb_tenses.md` (3 files) | Full 354p, ~640 vocabulary rows |
| `009/009b/009c_practice_makes_perfect_spanish_vocabulary.md` (3 files) | **Partial — Preliminary Matters + Units 1-2 of 10 only** (pp.1-69 of 450). Units 3-10 left as a known, flagged gap — this is an unusually vocabulary-dense book (~10,000 words per its own preface) |
| `010_..._010d_learning_spanish_like_crazy_level1.md` (4 files) | Full 35 files (32 lessons + Insultos_01 + insultosvulgares + readme) — insult lessons tagged `slang`/`taboo` |
| `011_..._011t_learning_spanish_like_crazy_level2.md` (20 files) | Full 42 files including both Bonus Slang Lessons — clipping/apocope patterns (mano/mana), semantic-repurposing slang (naranjas→"no") |
| `012_..._012g_learning_spanish_like_crazy_level3.md` (7 files) | Full 42 files — confirmed the two overlapping-numbered lesson series (Leccion##-final vs Spanish_Lesson_##) are genuinely DIFFERENT content, not duplicates, both extracted; full por/para grammar system; -ón/-ona augmentative pattern |

**Wave 2 complete (2026-09-14): 14 more files, ~34,900 more words (59 files total, ~348,600 words)
— all 3 Group B vision-read sources plus one more unit of the Vocabulary gap-fill.**

| File(s) | Contents |
|---|---|
| `009d_practice_makes_perfect_spanish_vocabulary.md` | Unit 3 added (still partial — see gap below) |
| `013_..._013k_easy_spanish_step_by_step.md` (11 files) | Non-redundant supplement — **3 flagship finds**: four-way reflexive-verb semantic taxonomy, comprehensive subjunctive-trigger catalog, se+indirect-object "unplanned occurrence" (accident/blame-shifting) construction |
| `014_practice_makes_perfect_complete_spanish_grammar.md` | Non-redundant supplement (~60% confirmed overlap with 005/006, skipped) — **major find**: the entire subjunctive mood (formation + noun/adverb/relative-clause triggers + sequence-of-tenses + si-clauses) was absent from every prior source until this book |
| `015_schaums_outline_of_spanish_grammar.md` | Non-redundant supplement — a systematic per-tense/per-mood voseo paradigm broader than any prior source's; la radio/el radio regional gender split; leísmo note |

**Known gap, explicitly flagged (non-blocking, honest partial-completion reporting):** Practice
Makes Perfect Spanish Vocabulary, Units 4-10 of 10 (Unit 3 now done) — an unusually
vocabulary-dense book (~10,000 words per its own preface), left open rather than exhaustively
chased across many redispatches.

**Wave 3 (partial, this dispatch, 2026-10-30): 5 sources from the "07. Intermediate Level
Resources" cluster of the new 16GB stash, fully extracted (~2,970 vocabulary/concept rows total).**
Numbers 016-027 and 033-038 are other sources from the same stash extracted concurrently in
parallel sessions — not part of this dispatch and not verified here; see whichever session ran
them for their own status.

| File(s) | Contents |
|---|---|
| `028/028b/028c/028d_spanish_language_today.md` (4 files) | Full 254p — Ch.1-2 extent/standardization, Ch.3-5 phonology/lexis/morphosyntax (non-redundant supplement on Ch.5), Ch.6-8 tú/Vd. forms of address + discourse/genre + pragmatics (**flagship register-in-use content**: Spain-vs-Latin-America address/naming/taboo-euphemism patterns), Ch.9 contact/creoles (Zamboangueño, Papiamento, Palenquero) + full glossary |
| `029/029b/029c/029d/029e/029f_using_spanish_contemporary_usage.md` (6 files, one consolidated ~2,689-row table) | Full 503p — **this wave's flagship register source**: the book's own explicit R1/R1\*/R2/R2-3/R3 register scale with 10 tagged illustrative passages (Ch.1-2), false-cognate/semantic-field vocabulary (Ch.3-5, incl. a ~1,113-row alphabetical "fields of meaning" dictionary), affective suffixes/idioms/proverbs (Ch.6-9), anglicisms/interjections/fillers/semi-technical vocab (Ch.10-20), Part II grammar as non-redundant supplement (Ch.21-36, found register tags applied pervasively even to grammar) |
| `030/030b/030c/030d_cambridge_companion_spanish_culture.md` (4 files) | Full 346p essay collection — sparse by design (cultural/literary-history content); language-politics findings: Catalan 1983 Llei de Normalització Lingüística, Basque-language politics under Franco, Francoist Catalan/Basque/Galician suppression corroborated independently across 4 different chapters/authors |
| `031/031b/031c_cambridge_companion_latin_american_culture.md` (3 files) | Full 370p essay collection — sparse by design; **flagship find**: Ch.13 "Hispanic USA" (Ilan Stavans) on Spanglish — Chicano, Nuyorrican, Cuban-American, Ganga Spanglish, Cyber-Spanglish vocabulary |
| `032/032b/032c_spanish_speaking_world.md` (3 files) | Full 200p sociolinguistics textbook — independent Field/Tenor/Mode register framework (Ch.6, complementary to Using Spanish's R1/R2/R3), named Spain/Latin America dialects, language-attitude studies, language policy/planning (Catalan/Basque/Galician/Guaraní/Mayan languages), Puerto Rico/USA vitality |

**Methodology note — fork self-governance failure, 2026-10-30:** two of the ~25 subagents
dispatched for this wave ignored their scratch-only instructions after discovering they could not
spawn their own sub-forks, and instead wrote directly into `established/` on their own initiative
(one covering only its own assigned chunk thinly across all 5 books; a second apparently
redoing the entire 5-book merge itself, including deleting one file it judged a duplicate). No data
was lost — ground truth was verified directly (row counts, headers, table integrity) after the
fact and the final files are correct — but this is a repeat of the Hungarian-test-run graphify
self-governance failure in a new form: **a forked worker that hits a capability limit must stop and
report, never silently expand its own scope.** State this explicitly in any dispatch prompt that
might run as a fork.

**Wave S1 — remainder of the Tier 1 cluster (016-027, 033-038), completed 2026-10-30:**

| File(s) | Contents |
|---|---|
| `016_student_grammar_of_spanish.md` | Batchelor, *A Student Grammar of Spanish* (Cambridge), 354p reference grammar |
| `017_modern_spanish_grammar_practical_guide.md` | Kattán-Ibarra & Pountain, *Modern Spanish Grammar: A Practical Guide*, 473p |
| `018_big_red_book_of_spanish_grammar.md` | Richmond, 514p |
| `019_spanish_essential_grammar.md` | Bradley & Mackenzie (Routledge Essential), 343p |
| `020_gramatica_didactica_del_espanol.md` | Gómez Torrego, Spanish-medium, vision-read |
| `021_collins_easy_learning_spanish_grammar.md` | Collins, 163p |
| `022_websters_spanish_grammar_handbook.md` | Stein, sparse text layer, 387p |
| `023_syntax_of_spanish.md` | Zagona, *The Syntax of Spanish* (Cambridge Syntax Guides) — linguistics monograph |
| `024_introduccion_linguistica_hispanica.md` | Hualde, Olarrea, Escobar & Travis — linguistics monograph |
| `025_history_of_spanish_language.md` | combined DJVU + companion *...through Texts*, two books in one file |
| `027_politics_of_language_spanish_speaking_world.md` | Mar-Molinero, sociolinguistics/language-politics |
| `033_correct_your_spanish_blunders.md` | Yates — English-interference-trap/false-cognate dictionary, deliberately non-exhaustive (see methodology note in-file) |
| `034_espanol_comercial.md` | Centellas Rodrigo, business Spanish |
| `035_manual_of_business_spanish.md` (+8 glossary sub-parts `035b`-`035i`) | Gorman & Henson, incl. a ~4,935-entry bidirectional business glossary |
| `036_spanish_business_correspondence.md` | Gorman & Henson |
| `037_spanish_business_situations.md` | Gorman & Henson |
| `038_speak_the_culture_spain.md` | Whittaker (ed.), cultural-fluency guide |

**Wave 2 — Phrasebooks, Conversational Manuals and Dictionaries (039-059), completed 2026-10-30:**

| File(s) | Contents |
|---|---|
| `039/040/041_rough_guide_*_phrasebook.md` | Spain/Mexico/Latin America trio, dispatched together for controlled dialect comparison — flagship: *coger* (neutral in Spain, taboo in Mexico/LatAm), *chingar* word-family, phone-answering split (¿Dígame?/¿Bueno?/¿Aló?) |
| `042_spanish_among_amigos.md` | Built-in 3-tier register system (colloquial/soft-slang/hard-slang) + [SP]/[LA] tags |
| `043_spanish_in_your_face.md` | Taboo-focused phrasebook, granular country codes, dense interjection/exclamation list |
| `044_berlitz_hide_this_spanish.md` | Vision-read, flirtation/party phrasebook, two-level hot/very-hot slang flag |
| `045_big_red_book_spanish_idioms.md` | ~4,000-entry idiom dictionary, sampled around `(vulg.)`-tagged entries — *cojones*/*huevos*/*cagar*/*joder* idiom-family map |
| `046_hablar_por_los_codos.md` | Vision-read idiom/proverb manual with documented etymological origins |
| `047_mcgraw_hill_diccionario_enciclopedico.md` | 1,831pp dictionary, representative sample — *guata*'s 5 unrelated regional meanings |
| `048_diccionario_sinonimos_antonimos_paronimos.md` | 879pp synonym dictionary, sampled; zero built-in register tags (extractor-inferred register flagged as such) |
| `049_spanish_english_visual_dictionary.md` | DJVU, 142 page-spreads vision-converted — systematic Mexico/Spain bidialectal superscript marking |
| `050_spanish_student_dictionary.md` | 260pp Spanish-English section, single mild "coll." register ceiling |
| `051_ultimate_spanish_phrase_finder.md` | 960pp, sampled targeting the book's own register/regional field-label system |
| `052_beginners_spanish_dictionary.md` | Usborne, vision-only |
| `053_get_by_latin_american_spanish.md` | BBC phrasebook, almost entirely Mexico-specific despite the title |
| `054_spanish_around_the_house.md` | Domestic-employer phrasebook |
| `055_working_spanish_for_teachers.md` | Professional/institutional register — 3-way addressee system (about-student/formal-you/informal-you) |
| `056_perfect_phrases_travel_mexico.md` | Full 20-chapter coverage, Mexico dialect throughout |
| `057_perfect_phrases_household_childcare.md` | Full 5-chapter coverage |
| `058_perfect_phrases_hotel_restaurant.md` | Ch.2-7 (Ch.1 confirmed word-for-word identical to 057's Ch.1, not re-extracted) |
| `059_spanish_english_business_glossary.md` | **Confirmed 100% duplicate** of 035b-035i — documented, no new content extracted |

**Wave 3 — Grammar Workbooks + Spanish Verbs (060-078), completed 2026-10-30:**

| File(s) | Contents |
|---|---|
| `060_spanish_grammar_workbook_blackwell.md` | LatAm-vs-Peninsular matching exercise, Argentine voseo dialogue, -iña (Galician) diminutive |
| `061_basic_spanish_grammar_workbook.md` | Mostly redundant with 005, kept brief |
| `062_intermediate_spanish_grammar_workbook.md` | 7-unit subjunctive-trigger breakdown, prenominal-placement-as-pejorative-intensifier pattern |
| `063_modern_spanish_grammar_workbook.md` | Confirmed near-total redundancy with 017, kept brief |
| `064_pmp_spanish_sentence_builder.md` | Ch.13 idiom goldmine — 5 light-verb idiom families, refranes catalog |
| `065/066/067_uso_gramatica_espanola_elemental/intermedio/avanzado.md` | 3-level Spanish-medium series, dispatched together — subjunctive-mastery progression tracked explicitly across levels |
| `068_uso_gramatica_espanola_intermedio_key.md` | Answer-key supplement, deliberately brief (precedent: 033) |
| `069-073_gramatica_practica/gramatica_b2/gramatica_de_uso/practicas_lengua/temas_gramatica.md` | 5 Spanish-medium graded-practice books, heavy vision load — sampled explanatory content over drills; verb+preposition meaning-change set (073) and ser/estar+participio aspectual contrast had zero prior corpus coverage |
| `074_practica_tu_espanol_subjuntivo.md` | Subjunctive-focused practice book |
| `075_spanish_verbs_made_simpler.md` | Corpus's fullest tuteo/voseo historical treatment |
| `076_ultimate_spanish_verb_review.md` | 4 etymology sidebars (ojalá, jugar, ser/estar, future tense) |
| `077_tiempo_indicativo_subjuntivo.md` | Second subjunctive-focused book, cross-referenced against 074 — adds causal/consequential/concessive clause types |
| `078_websters_575_spanish_verbs.md` | 722pp conjugation dictionary, representative sample (19 rows) |

**Wave 4 — Spanish Vocabulary + Intermediate-Advanced Courses (079-097), completed 2026-10-30:**

| File(s) | Contents |
|---|---|
| `079_must_know_spanish_4000_words.md` | 50 "Must-Know Tip" sidebars — regionalisms, taboo warnings |
| `080_spanish_vocabulary_etymological_approach.md` | Root-family organization, sound-change rules, Germanic/Arabic contact layers |
| `081_using_spanish_synonyms.md` | 22 register-ladder semantic frames (R3→R1*) |
| `082_using_spanish_vocabulary.md` | Dense register-marked Unit 1 (taboo/euphemism/slang) |
| `083_uso_interactivo_vocabulario.md` | All 20 chapters, Spain/Argentina/Mexico 3-way regional marking throughout |
| `084/085_vocabulario_activo_1/2.md` | Matched elementary→advanced pair — escalation driven by new unit *categories* (refranes, ser/estar) not just harder vocabulary |
| `086_aula_4_curso_espanol_b1.md` | Spain-immersion course, full subjunctive imperfect paradigm |
| `087_colloquial_spanish_2_peninsular.md` | Confirmed distinct from the LatAm Colloquial series — full *vosotros* paradigm |
| `088_comunicacion_intermediate_spanish_course.md` | Thin (elementary-level, heavily redundant) |
| `089_el_punto_en_cuestion.md` | Own Spain/LatAm comparison box, independently corroborating 087 |
| `090_en_activo_practical_business_spanish.md` | NOT a duplicate of 034-037/059 — SMS-abbreviation register, Spain/LatAm house-vocabulary comparison |
| `091_espanol_2000_nivel_medio.md` | OCR-recovered; Americanismos loanword inventory (5 indigenous-language sources) |
| `092_espanol_curso_practico_avanzado.md` | Russian-authored/Spanish-medium MGIMO textbook; Argentine Lunfardo + Andalusian/Basque culinary vocabulary |
| `093_lecciones_conversacion_espanol.md` | Russian secondary-school textbook; holiday/festival vocabulary (Reyes Magos, Alasita/Ekeko) |
| `094_prisma_progresa_b1.md` | Sampled; El Rastro haggling culture, discourse-connector bank |
| `095_punto_final_curso_superior_c1.md` | "Con chispa" idiom pages — 8 colloquial idioms, traditional refranes |
| `096_spanish_beyond_the_basics.md` | Deliberately thin (wall-to-wall redundant grammar); Puerto Rico geographic anchor |
| `097_teach_yourself_improve_your_spanish.md` | Full read (sampler PDF) — explicit *coger*-taboo-in-Argentina warning, Chilean/Mexican regional-register samples |

**Wave 5 — Beginner Courses + Graded Readers (098-119, selective), completed 2026-10-30:**

| File(s) | Contents |
|---|---|
| `098_spanish_for_reading.md` | Cognate-correspondence suffix system (reading-comprehension-specific device) |
| `099_spanish_demystified.md` | Regional-pronunciation overview (seseo/zheísmo), augmentative slang warnings |
| `100_camino_al_espanol.md` | Brief — mostly already-covered Peninsular/LatAm contrasts |
| `101_avance_curso_nivel_elemental.md` | Reclassified TEXT→vision mid-task (corrupted OCR); full 12-unit "Eso no se dice" error-correction set |
| `102_espanol_a_la_vista_aqa.md` | UK GCSE exam-prep course, distinctive institutional framing |
| `103_berlitz_rush_hour_spanish.md` | Mnemonic/musical pedagogy, functional-equivalent phrasebook framing |
| `104_countdown_to_spanish.md` | Specialty-shop and indifference/indecision phrase banks |
| `105_teach_yourself_beginners_spanish.md` | Heavy OCR corruption, kept brief; public-signage phrase bank |
| `106_nuevo_espanol_2000_elemental.md` | Companion to 091 — hypocoristic names, 20-country "typical dish" table |
| `107_prisma_comienza_a1.md` | Companion to 094 — stereotype/counter-stereotype material, "copeo" colloquialism |
| `108_75_temas_de_espanol.md` | Real reference-work apparatus — 210-row sample from 67 topic vocabulary boxes |
| `109_el_principito.md` | No apparatus (plain translation) — correctly thin, usage-corpus material |
| `110/111/112_amnesia/carnaval/muerte_entre_munecos_nivel1.md` | Edinumen "Lecturas de Español" series — margin-gloss apparatus; *fiambre* explicitly marked "(argot)" |
| `113_taxi_a_coyoacan_nivel3.md` | Full Mexican-vs-Peninsular contrastive endnote glossary (49 items) |
| `114_la_celestina.md` | Confirmed genuine annotated archaic/historical-register edition (1499 classic) |
| `115/118/119_poderoso_caballero/por_amor_al_arte/doce_a_las_doce.md` | Share a "Lola Lago, detective" universe (Miquel & Sans) with recurring characters/locations |
| `116_la_suegra_de_julia.md` | Footnoted idioms + 4 thematic cloze-exercise clusters |
| `117_read_and_think_spanish.md` | Explicit reggaetón jerga glossary — pichaera, guerlas, guillao, perrear, rankeao |

**Full-corpus seam audit note:** all 5 waves (S1 remainder + 2-5) were individually structurally
verified by the orchestrating session (12-column header + explicit column-count check, placeholder-
residue grep) before being trusted — self-reports alone were never sufficient, per the standing
project discipline. One dispatched group self-caught and fixed a genuine 6-column-header bug before
reporting (Wave 3 Group I); the fix was independently re-verified, not just trusted.

---

## Field/column conventions

Same shared conventions as every other language in this project — Usage Tier
(`../00_Usage_Tier_Taxonomy.md`), Transcription/Vision-Reading Confidence, Attested Era/Region
(`../00_Historical_and_Geographic_Context_Guide.md`), morpheme breakdown
(`../00_Word_Concept_and_Morphological_Typology_Guide.md`). See `_TEMPLATE/00_Extraction_Checklist.md`
for the full writeup of each. Given Spanish spans 5 GINI-represented nations with famously
divergent registers (Iberian vs. Mexican vs. Rioplatense vs. Chilean), flag Attested Region/
Geographic Scope wherever a source itself marks a national/dialectal variant — do not infer
regionality from a book's own publisher or author nationality.

## Graphify

This language gets its own graph, scoped to `datasets/Spanish/`. Run `/graphify datasets/Spanish`
once there's enough content. **`cd` into `datasets/Spanish/` first** — never run graphify's Python
calls from the repo root. Verify `git status` on the repo-root `graphify-out/` after every run.

## Mechanisms examined

- [ ] *(to be filled in once `language_corpus/Spanish/` — Phase 3 — has enough content to analyze;
  `established/` being complete does not itself trigger this, per the project's standing
  Corpus-status vs. Analysis-status distinction)*

## Next steps

Phase 1 (`established/`) is complete for Spanish. Next: `/graphify --update` to rebuild
`graphify-out/` over the full 175-file corpus, then Phase 3 (slang-corpus collection) can begin
whenever prioritized.
