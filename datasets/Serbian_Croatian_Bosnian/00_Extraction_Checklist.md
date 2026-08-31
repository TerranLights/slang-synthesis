# Serbian/Croatian/Bosnian Slang Mechanics — Extraction Checklist

**This is the pipeline's first test-run language — everything below is tentative until the
developer reviews it.** See `../../methodology-observations/serbian_croatian_bosnian_test_run.md`
for process findings (including the full bridge-scale-test writeup), and `00_Book_Triage_Catalog.md`
(this folder) for the source-material survey.

**Purpose:** analyze the actual mechanics of how Serbian/Croatian/Bosnian slang forms and works,
using the corpus collected in `language_corpus/Serbian_Croatian_Bosnian/` and, where useful, the
grammar/vocabulary reference in `source_reference/languages/Serbian, Croatian, Bosnian/`. Findings
here are what eventual synthesis work (deriving invented slang for the sci-fi setting) will be
grounded in.

**This is research only — nothing here is canon** until worked into actual setting material by
explicit decision.

**Status legend:** `[x]` analyzed and written into its output file · `[~]` partially done · `[ ]` not
yet done.

---

## Morphological typology

**Serbian/Croatian/Bosnian: fusional.** Grammatical categories (case, number, gender) are merged
into single, non-separable affixes rather than agglutinated as distinct stacked morphemes — e.g.
`mòje` (neuter possessive "my") fuses possession, gender, and number into one ending, not separable
into individually-meaningful pieces the way an agglutinative language's morphology would be. **Held
across the full-book bridge-scale extraction** (Lessons 1-20 plus appendices and the full glossary,
~8,450 vocabulary rows) — no agglutinative or polysynthetic behavior turned up anywhere, no morpheme
breakdowns were needed in any of the 32 output files. See
`../00_Word_Concept_and_Morphological_Typology_Guide.md`.

---

## Output files — Markdown, sharded by numbered file

**Status: 7 of this language's 9 real reference documents fully extracted.** All 3 clean-text-layer
books are done — the flagship Alexander & Elias-Bursać textbook (32 files, ~8,450 rows, ~338,000
words), Alexander's companion *Grammar: With Sociolinguistic Commentary* (15 files, ~990 rows,
~67,000 words), and Hammond's *Serbian: An Essential Grammar* (13 files, ~780 rows, ~52,000 words).
Four vision-only books are also now done — Magner's *Introduction to the Croatian and Serbian
Language* (30 lessons, `established/002`+`059`-`064`, ~1,190 rows), Hawkesworth's *Colloquial
Croatian and Serbian* (16 files, `established/065`-`073`+parts, ~1,868 rows, ~96,000 words),
Hawkesworth & Ćalić's *Colloquial Serbian* (13 files, `established/074`-`083`+parts, ~1,563 rows,
~95,500 words), and *Serbian Folk Tales* (9 files, `established/084`-`092`, ~535 rows, ~45,000
words). Combined: 104 `established/` files, ~15,373 rows, ~745,000 words for this language so far.
Only 1 remaining garbled-OCR book (plus the trivial audio-recordings key) is left: *Teach Yourself
Serbian*. A bonus 12-reading "Čitanka" section inside Magner's own book (starting PDF p. 95, past the
30 lessons) was found but deliberately deferred — see
the deferred-content note in Reference extraction progress below.

| Directory | File | Contents |
|---|---|---|
| `established/` | `001_lesson01_basics.md` | Original manual test-run sample of Lesson 1 (20 entries) — **superseded** by `003_lesson01_complete.md`, kept for methodology history. |
| `established/` | `002_lesson01_magner_vision_test.md` | Magner's *Introduction to the Croatian and Serbian Language*, Lesson 1 (86 entries) — this project's **vision-reading test** (scanned, no text layer), medium-high confidence, retrofitted `Vision Reading Confidence` column. |
| `established/` | `003_lesson01_complete.md` | Alexander & Elias-Bursać, Lesson 1 (Prva lekcija), full re-extraction (181 rows) — supersedes `001`. |
| `established/` | `004_lesson02.md` | Lesson 2 (Druga lekcija) — 204 rows. |
| `established/` | `005_lesson03.md` | Lesson 3 (Treća lekcija) — 127 rows. |
| `established/` | `006_lesson04.md` | Lesson 4 (Četvrta lekcija) — 204 rows. |
| `established/` | `007_lesson05.md` | Lesson 5 (Peta lekcija) — 285 rows; a real `pdftotext` column-scrambling bug was caught and self-corrected (see observations log). |
| `established/` | `008_lesson06.md` | Lesson 6 (Šesta lekcija) — 237 rows. |
| `established/` | `009_lesson07.md` | Lesson 7 (Sedma lekcija) — 160 rows; **source explicitly labels a phrase "Amusing slang usage"** (`Ma moj!`) — first source-self-labeled slang in the project. |
| `established/` | `010_lesson08.md` | Lesson 8 (Osma lekcija) — 90 rows. |
| `established/` | `011_lesson09.md` | Lesson 9 (Deveta lekcija) — 179 rows; **explicit Belgrade slang (`kèva` "Mom") and teen slang (`stara`/`stari`/`starci`)**, plus regional colloquial family-term variation across 4 cities/regions. |
| `established/` | `012_lesson10.md` | Lesson 10 (Deseta lekcija) — 230 rows. |
| `established/` | `013_lesson11.md` | Lesson 11 (Jedanaesta lekcija) — 239 rows. |
| `established/` | `014_lesson12.md` | Lesson 12 (Dvanaesta lekcija) — 186 rows. |
| `established/` | `015_lesson13.md` | Lesson 13 (Trinaesta lekcija) — 178 rows. |
| `established/` | `016_lesson14.md` | Lesson 14 (Četrnaesta lekcija) — 200 rows. |
| `established/` | `017_lesson15.md` | Lesson 15 (Petnaesta lekcija) — 133 rows; a possible source erratum (reversed `[B]`/`[C]` tag) verified against the page image and recorded faithfully rather than "corrected." |
| `established/` | `018_lesson16.md` + `018_lesson16_vocab2.md` + `018_lesson16_vocab3.md` | Lesson 16 (Šesnaesta lekcija) — 110+77+125 = 312 rows; the subagent split its own output into 3 files unprompted once it grew large, correctly following the "don't let a file grow unbounded" rule on its own initiative. |
| `established/` | `019_lesson17.md` | Lesson 17 (Sedamnaesta lekcija) — 139 rows. |
| `established/` | `020_lesson18.md` | Lesson 18 (Osamnaesta lekcija) — 157 rows; reading/poetry-comprehension lesson, thinner grammar section flagged transparently rather than padded. |
| `established/` | `021_lesson19.md` | Lesson 19 (Devetnaesta lekcija) — 205 rows; **first `archaic` and `regional` usage-tier entries in the project** (Montenegrin dialect forms explicitly glossed in an epic-poem excerpt). |
| `established/` | `022_lesson20.md` | Lesson 20 (Dvadeseta lekcija, final lesson) — 302 rows, a graded reading with 8 vocabulary boxes. |
| `established/` | `023_appendices1-6_grammar_reference.md` | Appendices 1-6, consolidated grammar-reference tables — 106 rows. |
| `established/` | `024_appendix9_verb_types.md` | Appendix 9, verb-type classification — 23 rows. |
| `established/` | `025_appendices7-8_literary_readings.md` | Appendices 7-8, two copyrighted short stories (Albahari, Bazdulj) — vocabulary-only extraction, no plot/prose reproduction — 95 rows. **Contains the single most important finding of this test run: a footnoted syllable-switching slang-formation mechanism** (`vozdra`<`zdravo`, `žemka`<`kažem`), with regional (Sarajevo/Zagreb) and historical (1960s Zagreb) attestation. |
| `established/` | `026_glossary_bcs_english_part1.md` | BCS-English Glossary, part 1 of 5 (A through hvala) — 809 rows. First `taboo` (explicitly "vulg." in source), `colloquial`, `literary` (poetic), and `technical.grammar`/`technical.linguistics` dot-notation entries in the project. |
| `established/` | `027_glossary_bcs_english_part2.md` | Glossary part 2 (hvala through napasti) — 798 rows. |
| `established/` | `028_glossary_bcs_english_part3.md` | Glossary part 3 (napadati through posvetiti) — 792 rows. |
| `established/` | `029_glossary_bcs_english_part4.md` | Glossary part 4 (posvećujem se through stalan) — 801 rows. |
| `established/` | `030_glossary_bcs_english_part5.md` | Glossary part 5 (stalo through Ž, end of glossary) — 972 rows. |
| `established/` | `031_socioling_ch21_intro_writing_standardization.md` | Alexander, *Grammar: With Sociolinguistic Commentary*, Ch. 21 — writing-system history, standardization to 1974 — 19 rows. |
| `established/` | `032_socioling_ch22_dialect_differences.md` | Ch. 22, "Dialect Differences" — 111 rows across two source-curated tables (ekavian/ijekavian/ikavian pronunciation chart, 42-pair East/West lexical list). **The single highest-value chapter in this book for this project's purposes** — direct, explicitly-labeled regional/national lexical data plus the source's own argument that vocabulary (not alphabet/pronunciation/grammar) is the real B/C/S differentiator. |
| `established/` | `033_socioling_ch23_bosnian.md` | Ch. 23, "Bosnia" — 27 rows (Ottoman-loanword doublets, the Bosnian/Bosniak naming dispute); sensitive 1990s political content handled source-attributed, not editorialized, matching the Kosovo-note discipline from `006_lesson04.md`. |
| `established/` | `034_socioling_ch24_croatian.md` | Ch. 24, "Croatia" — 20 rows (dialect-faction nicknames, purist coinages, named standardization documents); WWII-era NDH language-policy history handled with the same neutral, source-attributed discipline. |
| `established/` | `035_socioling_ch25_serbian_montenegro.md` | Ch. 25, "Serbia"/"Montenegro" — 22 rows, including the Nikčević 1997 Montenegrin-orthography proposals (ś/ź/з). **Confirms and substantially deepens the Lesson 8/19 Montenegrin finding** with real scholarly nuance (claimed distinguishing features are shared East Herzegovinian dialect features, not exclusively Montenegrin, per the source's own verdict). |
| `established/` | `036_socioling_ch26_one_or_more_languages.md` | Ch. 26 (final chapter), the author's own "one language or more than one" synthesis — 7 rows, deliberately thin. Contains a load-bearing meta-finding: the source states its own `[B]`/`[C]`/`[S]` tagging convention is a simplification of a frequency gradient, not a hard categorical split — relevant to how every `Usage Tier`/`Attested Region` tag drawn from this book should be read. |
| `established/` | `037_grammar_ch1-3_supplementary.md` | Grammar Ch. 1-3, non-redundant supplement to Lessons 1-3 — 52 rows, 15 new grammar points (the book's own accent notation system, the formally-named XYZ clitic model, additional verb-conjugation types). |
| `established/` | `038_grammar_ch4-6_supplementary.md` | Grammar Ch. 4-6, non-redundant supplement to Lessons 4-6 — 51 rows, 18 new grammar points (full 6-slot XYZ clitic model, complete genitive plural rules, u-word/na-word inventory). |
| `established/` | `039_grammar_ch7-9_supplementary.md` | Grammar Ch. 7-9, non-redundant supplement to Lessons 7-9 — 26 rows, 17 new grammar points, including §89-93's complete case-by-case declension paradigm tables (the single highest-value find in this chunk — a systematic reference the lesson-based textbook never assembles in one place). |
| `established/` | `040_grammar_ch10-12_supplementary.md` | Grammar Ch. 10-12, non-redundant supplement to Lessons 10-12 — 10 rows, 14 new grammar points. **Closes a real gap**: extracts the full Type A/B/C consonant-softening system, which Chapter 20's phonology extraction (`045`) had already found referenced as "presented earlier" but which no prior file had actually captured. |
| `established/` | `041_grammar_ch13-16_supplementary.md` | Grammar Ch. 13-16, non-redundant supplement to Lessons 13-16 — grammar-points-only (no vocabulary table; pure grammatical exposition), 17 sections including the full conjunction system and full paradigm tables for all 16 verb conjugation types. |
| `established/` | `042_grammar_ch17_case_usage_review.md` | Grammar Ch. 17, "Cases of nouns, review" (§154-160) — new content, no lesson analog — 63 rows: every case-governing preposition, 15 genuinely distinct B/C/S lexical-synonym pairs, one representative (not exhaustive) Ekavian/Ijekavian pair flagged as such to avoid bulk-reproducing hundreds of near-duplicate footnote pairs. |
| `established/` | `043_grammar_ch18_word_formation.md` | Grammar Ch. 18, "Word Formation" (§161-163) — new content, no lesson analog — **~400 rows across 35 derivational-suffix patterns**, the largest single chunk of this book. Directly flags diminutive and agentive suffixes as the productive, affect-loaded categories — relevant to future Phase 3/5 slang-mechanics work. |
| `established/` | `044_grammar_ch19_clitic_accent.md` | Grammar Ch. 19, clitic placement/BCS accent (§164-166) — new content, no lesson analog — 14 rows, the book's genuinely first full treatment of the XYZ model and rhythmic-constituent framework. |
| `established/` | `045_grammar_ch20_phonology.md` | Grammar Ch. 20, "The Sound Structure of BCS" (§167) — new content, no lesson analog — 20 rows. Draws an explicit (flagged-as-hypothesis) structural connection between BCS's cluster-simplification/fleeting-vowel rules and the syllable-switching slang mechanism in `025_appendices7-8_literary_readings.md`. |
| `established/` | `046_serbian_essential_ch1-2_cultural_dialects.md` | Hammond, *Serbian: An Essential Grammar*, Ch. 1-2 (cultural/literary background, dialects) — 19 rows. Delivered real Attested Region data via the kajkavski/čakavski/štokavski split and the štokavian jat-reflex sub-split, each source-tagged to named regions. |
| `established/` | `047_serbian_essential_ch3-5_alphabet_pronunciation_stress.md` | Hammond, Ch. 3-5 (alphabet, pronunciation, stress), non-redundant supplement to `044`/`045` — 52 rows, including a full Cyrillic↔Latin correspondence table and a Belgrade-vs-Bosnia regional vowel-length register note. |
| `established/` | `048_serbian_essential_ch6a_verbs_part1.md` | Hammond, Ch. 6 §6.1-6.9 (verb tenses), non-redundant supplement — 1 row (near-total overlap correctly skipped), but full worked aorist paradigms across three stem-shape classes not previously captured. |
| `established/` | `049_serbian_essential_ch6b_verbs_part2.md` | Hammond, Ch. 6 §6.10-6.18 (imperative through modal verbs), non-redundant supplement — 10 rows, including the 9-way interrogative-formation inventory and 5 new *ići*-derivatives. |
| `established/` | `050_serbian_essential_ch7a_nouns_part1.md` | Hammond, Ch. 7 §7.1-7.3 (noun types/gender/case usage), non-redundant supplement — 62 rows, including closed-class case-governing verb/adjective inventories and some directly slang-relevant vocabulary (*narkoman*, *siledžija*, *mangup*). |
| `established/` | `051_serbian_essential_ch7b_nouns_part2.md` | Hammond, Ch. 7 §7.4 (noun declension), non-redundant supplement — 47 rows. Filled a real gap: the archaic *mati*/*kći* paradigms, previously only named, now fully tabulated; also the suppletive *čovek*/*ljudi* counting rule, new to this project. |
| `established/` | `052_serbian_essential_ch8_pronouns.md` | Hammond, Ch. 8 (pronouns), non-redundant supplement — 29 rows. New content: the internal case-ordering rule within a clitic cluster (dative→genitive→accusative), confirmed complementary to the existing XYZ/rhythmic-constituent models, not a duplicate. |
| `established/` | `053_serbian_essential_ch9_adjectives.md` | Hammond, Ch. 9 (adjectives), non-redundant supplement — 31 rows, including the possessive-adjective capitalization rule and the passive-participle-to-deverbal-noun derivational pattern, both new to this project. |
| `established/` | `054_serbian_essential_ch10-11_adverbs_prepositions.md` | Hammond, Ch. 10-11 (adverbs, prepositions), non-redundant supplement — 27 rows, including preposition accentuation as proclitics (entirely new) and 5 preposition headwords absent from the existing master inventory. |
| `established/` | `055_serbian_essential_ch12-13_conjunctions_enclitics.md` | Hammond, Ch. 12-13 (conjunctions, enclitics), non-redundant supplement — 63 rows: full plain-language conjunction inventory plus 4 genuinely new enclitic-interaction rules. **Cracked the book's font-substitution cipher** (š→e, č→a, ć→z, ž→f, đ→]) — a fixed, decodable mapping, not random corruption (see PDF gotchas note below). |
| `established/` | `056_serbian_essential_ch14_numerals.md` | Hammond, Ch. 14 (numerals), extracted fully (little prior overlap) — 131 rows: cardinal/ordinal declension, fractions, collectives, multiplicatives, approximatives, distributives, frequentatives, weights/measures, age, calendar/time vocabulary. |
| `established/` | `057_serbian_essential_ch15-17_quantifiers_determiners_particles.md` | Hammond, Ch. 15-17 (quantifiers, determiners, particles/conjunctions/exclamations), extracted fully — 116 rows. Ch. 17's `li`/`ne bi li` entry carries the source's own explicit "sarcastic/humorous overtones" annotation — the strongest informal-register signal in this book. |
| `established/` | `058_serbian_essential_ch18-20_sentences_word_formation.md` | Hammond, Ch. 18-20 (sentences, sentence structure, word formation), Ch.18-19 extracted fully, Ch.20 checked against `043_grammar_ch18_word_formation.md` (found only 1 genuine duplicate) — ~148 rows, including a 14-prefix verb-formation inventory. |
| `established/` | `059_magner_lesson02-06.md` | Magner Lessons 2-6, vision-read — ~345 rows. A genuine syntactic (not just phonological) Cr./S. divergence found: Croatian favors infinitive+`će` future, Serbian leans on `da`+present. |
| `established/` | `060_magner_lesson07-11.md` | Magner Lessons 7-11, vision-read — 216 rows, book pp. 36-66. 9 rows flagged `low_confidence` near a binding-gutter shadow. |
| `established/` | `061_magner_lesson12-16.md` | Magner Lessons 12-16, vision-read — ~172 rows, book pp. 67-95. A Dalmatian folk song gave ikavian dialect glosses distinct from the book's usual Cr./S. binary. |
| `established/` | `062_magner_lesson17-21.md` | Magner Lessons 17-21, vision-read — ~130 rows, PDF pp. 55-69. Correctly excluded ~9 ambiguous entries from a misaligned phonology word list rather than guess. |
| `established/` | `063_magner_lesson22-26.md` | Magner Lessons 22-26, vision-read — ~90 rows, PDF pp. 69-82. A kajkavian-dialect song (Zagorje sub-dialect) gave a source-provided kajkavian→standard glossary, a regional axis orthogonal to the book's usual comparison. |
| `established/` | `064_magner_lesson27-30.md` | Magner Lessons 27-30 (final lessons), vision-read — ~114 rows, PDF pp. 83-94. Confirmed Lesson 30 is genuinely the book's final lesson; found a bonus 12-reading "Čitanka" (Reader) section starting at PDF p. 95, **not extracted, flagged as deferred** (see below). |
| `established/` | `065_colloquial_hr_sr_units01-03.md` | Hawkesworth, *Colloquial Croatian and Serbian*, Units 1-3, vision-read — ~300 rows, PDF pp. 15-46. |
| `established/` | `066_colloquial_hr_sr_units04-06.md` | Units 4-6, vision-read — ~250 rows, PDF pp. 47-81. Strong register-tagged material: `halo` flagged telephone-only, informal `Bog!` vs. formal `do viđenja`, `čuj` vs. `slušaj`. |
| `established/` | `067_colloquial_hr_sr_units07-09.md` | Units 7-9, vision-read — ~290 rows, PDF pp. 82-115. |
| `established/` | `068_colloquial_hr_sr_units10-12.md` | Units 10-12, vision-read — ~220 rows. |
| `established/` | `069_colloquial_hr_sr_units13-15.md` | Units 13-15, vision-read — ~220 rows. |
| `established/` | `070_colloquial_hr_sr_units16-18.md` | Units 16-18, vision-read — ~290 rows. |
| `established/` | `071_colloquial_hr_sr_units19-20.md` | Units 19-20 (final units), vision-read — ~155 rows. |
| `established/` | `072_colloquial_hr_sr_grammar_summary.md` | Grammar summary, non-redundant supplement to 3 prior books — 2 rows kept (mobile-a epenthesis, distributive-numeral paradigms), correctly identified near-total overlap with existing content. Distinguished the book's own pedagogical handwritten-Cyrillic facsimile from real marginalia. |
| `established/` | `073_colloquial_hr_sr_glossary.md` + `_part2` through `_part8` | Croatian/Serbian-English glossary, vision-read exhaustively — ~827 entries across 8 files. All `core` tier (no taboo/slang/archaic diversity), but real value: ~1/3 of entries carry Ijekavian/Ekavian or B/C/S national-variant tagging. One flagged print erratum (`grad` glossed "own" instead of "town"). |
| `established/` | `074_colloquial_sr_units01-03.md` | Hawkesworth & Ćalić, *Colloquial Serbian* (2006), Units 1-3, non-redundant supplement to `065` — 61 rows, only genuinely new items kept. First Ekavian-only, Cyrillic-primary source in this project. |
| `established/` | `075_colloquial_sr_units04-06.md` | Units 4-6, mixed new/supplement — ~110 rows. A directly-observed dialect contrast in one scene: hosts toast "живели!" (Ekavian), a Bosnian-heritage guest replies "живјели!" (Ijekavian). |
| `established/` | `076_colloquial_sr_units07-09.md` | Units 7-9, mixed new/supplement (unit topics don't align 1:1 with the sister book) — ~140 rows. Source-marked colloquial tag on `escajg` ("coll. alternative to pribor za jelo"). |
| `established/` | `077_colloquial_sr_units10-12.md` | Units 10-12 (Bus journey, Family, **Village life** — the last with no analog in the sister book) — ~185 rows. Colloquial animal-simile idiom set (`gladan kao vuk`, etc.); another embedded Ekavian/Ijekavian dialogue contrast. |
| `established/` | `078_colloquial_sr_units13-15.md` | Units 13-15 (**Music** — no analog in the sister book — through Packing/Departure) — ~185 rows. Strong cultural content: Guča trumpet festival, EXIT Festival, gusle epic-song tradition. |
| `established/` | `079_colloquial_sr_units16-17.md` | Units 16-17, mixed new/supplement — ~110 rows. `гепек` (car boot/trunk, < German *Gepäck*) as an unmarked colloquial term; flagged a source's own mislabeled gender tag rather than silently correcting it. |
| `established/` | `080_colloquial_sr_units18-19_kotor.md` | Units 18-19, **Montenegro-specific (Kotor/Cetinje/Budva), no analog in the sister book** — 76 rows. Honestly reported the dialogue uses standard Ekavian, not the distinctive Montenegrin dialect markers documented elsewhere in this project — did not force a false connection. |
| `established/` | `081_colloquial_sr_unit20.md` | Unit 20 (final unit, "Kraj") — 46 rows. Register content: reversed-order vocative exclamations (`Budalo jedna!`), a Belgrade cultural term (`сплав`, river barge/floating club). |
| `established/` | `082_colloquial_sr_grammar_summary.md` | Grammar summary, non-redundant supplement — **0 rows kept**, a near-total duplicate of `072` (same author's sister-book grammar summary), verified via targeted greps before concluding nothing new survived the bar. Honest empty-result reporting rather than padding. |
| `established/` | `083_colloquial_sr_glossary.md` + `_part2`-`_part4` | Serbian-English glossary, vision-read exhaustively — **~1,337 entries** across 4 files. Several source-tagged `(informal)` colloquial items (`čika`, `drugar`) plus common colloquialisms (`kako da ne`, `nema veze`, `žurka`); no taboo-tier vocabulary (expected for a beginner course glossary). |
| `established/` | `084_folktales_part1.md` | *Srpske narodne bajke* (Serbian Folk Fairy Tales, ed. Marinković & Marković, 2000), tales 1-3 — 57 rows. First **taboo-avoidance naming** finding: the source explains "snake" (*zmija*) was avoided out of fear, substituted with euphemisms (*baurina*, "nepomenica"/"the unmentionable one"). |
| `established/` | `085_folktales_part2.md` | Tales continued (Baš-Čelik through Stojša i Mladen) — 59 rows. A taboo item (*kurva*) appears plainly despite this being a children's-marketed anthology. |
| `established/` | `086_folktales_part3.md` | Tales continued — 107 rows. Found a genuine **source-internal dialect/register contrast**: one tale is consistently Ijekavian with dense Ottoman Turkish loanwords, sharply distinct from the Ekavian, near-Turkism-free register of surrounding tales — likely reflecting different original collectors/regions within the anthology. |
| `established/` | `087_folktales_part4.md` | Tales continued — 58 rows. A dense cluster of Ottoman Turkish loanwords used as ordinary narrative vocabulary, all glossed by the book's own margin notes; visible Ekavian/Ijekavian mixing within a single tale. |
| `established/` | `088_folktales_part5.md` | Tales continued — 60 rows. **Second confirmation of taboo-avoidance naming**, this time for wolf and bear (euphemisms *alo*, *kamenko*) — now a recurring, well-attested folkloric practice across multiple animals in this book, not a one-off. |
| `established/` | `089_folktales_part6.md` | Tales continued — 74 rows. Captured *usud* (personified Fate) and *krsno ime* (Slava, the family patron-saint feast) as culturally load-bearing terms. |
| `established/` | `090_folktales_part7.md` | Tales continued — 70 rows. **Found 4 tales not in the originally-captured table of contents** (Пепељуга/Cinderella, Ћела, Ђевојка бржа од коња, Тамни вилајет) — the TOC snapshot used for dispatch planning was incomplete. Striking false-friend/regional-polysemy find: *kokoška* glossed as "ball of yarn," not "hen," in this regional usage. |
| `established/` | `091_folktales_part8.md` | **Not more tales** — this range is the book's own "Пустоловни додатак" (Adventure Appendix), a folklore-studies essay on fairy-tale collecting (Vuk Karadžić's methodology, dialect variants, a Proppian structure exercise) — 40 rows of vocabulary drawn from its own inline definitions. Also corrected the assumed glossary location (see `092`). |
| `established/` | `092_folktales_glossary.md` | The book's own "Мање познате речи и изрази" section — turned out to be a **bare word→page-number index, not a defining glossary**; 411 entries with analyst-supplied glosses (flagged as such, not source-extracted), confidence-flagged per row. Confirms the tales are printed unchanged from Vuk Karadžić's original 19th-century Ijekavian recordings, specifically to preserve this vocabulary — legitimizes `Attested Era: 19th c.` for the whole book. |
| `analysis/` | *(none yet)* | Phase 3 not started — gated on `language_corpus/Serbian_Croatian_Bosnian/` reaching `in progress`. |
| `synthesized/` | *(none yet)* | Phase 5 not started. |

**Deliberately excluded from extraction** (per `00_Book_Triage_Catalog.md`): Appendix 10 (answer key
— drill content, per the coverage rule), the English-BCS reverse glossary (redundant with the
BCS-English glossary already extracted), and the Index (no content value).

**No `_index.json` manifest** — this table is the human-readable index. `/graphify
datasets/Serbian_Croatian_Bosnian` provides the machine-queryable pointer/summary layer.

---

## Field/column conventions

**Usage-tier / slang-type categorization.** `established/` vocabulary tables carry a `Usage Tier`
column — see `../00_Usage_Tier_Taxonomy.md`. At full-book scale, real diversity emerged:
`core` (the vast majority), `colloquial`, `formal`, `slang` (explicitly source-labeled twice —
Lesson 7, Lesson 9), `taboo` (explicitly "vulg." in the glossary), `literary` (poetic-marked
glossary entries, plus the literary-appendix vocabulary), `archaic`, and `regional` (Montenegrin
dialect forms). Dictionaries/glossaries turned out to be an even richer source of tier diversity
than "colloquial" chapters (the Dutch test run's finding) — a dictionary's whole purpose is marking
register, so it does so far more explicitly and frequently than a teaching grammar's prose.

**Transcription risk carries through** from `language_corpus/` sources — see
[`../../language_corpus/00_Source_Reliability_Guide.md`](../../language_corpus/00_Source_Reliability_Guide.md).
Not yet relevant here since no corpus collection has begun.

**Vision-reading risk.** 7 files are now vision-read (no text layer): `established/002` (the
project's original vision-reading test) plus `059`-`064` (Magner's Lessons 2-30, extracted this
session across 6 subagent chunks with zero marginalia found in any of them — unlike `002`'s copy,
which had a previous owner's pencil marks). This session also added `065`-`073`+parts (Hawkesworth's
*Colloquial Croatian and Serbian*, 16 files, vision-read, no marginalia found anywhere). This session
also added `074`-`083`+parts (Hawkesworth & Ćalić's *Colloquial Serbian*, 13 files, vision-read, no
marginalia found anywhere), and `084`-`092` (*Serbian Folk Tales*, 9 files, vision-read; real
marginalia — a library accession stamp and a handwritten underline — was found and correctly
excluded, unlike the other vision-read books in this batch). 45 files in this language are now
vision-read in total; the other 59 have a real text
layer, so `Vision Reading Confidence` is `n/a` throughout them. See
`../00_Reference_Extraction_Spec.md`'s Vision-reading guard section. This will change further once
the remaining vision-only books (`03.Colloquial Serbian and Croatian.pdf`, `Colloquial Serbian/
Colloquial Serbian.pdf`, `29.Serbian Folk Tales.pdf`, `Teach Yourself Serbian.pdf`) are extracted.

**Historical & geographic context.** `Attested Era`/`Attested Region`/`Geographic Scope` columns —
see [`../00_Historical_and_Geographic_Context_Guide.md`](../00_Historical_and_Geographic_Context_Guide.md).
Exercised extensively at full-book scale via the source's own `[B]`/`[C]`/`[S]` and `[E]`/`[J]`
(Ekavian/Ijekavian) tagging, plus explicit Montenegrin-dialect and city-specific-slang attribution
(Belgrade, Zagreb, Sarajevo).

**PDF text-extraction gotchas found at this scale** (see observations log for full detail — worth
knowing before extracting any other two-column-glossary-style source): (1) `pdftotext -layout` can
scramble multi-column vocabulary-table layouts, requiring cross-checking against page context; (2)
`pdftotext -layout` on a genuinely two-column dictionary/glossary page interleaves left/right column
text on shared lines, requiring per-column bounding-box extraction (`-x`/`-W` or left/right crops)
instead; (3) a third-party "Advanced PDF Repair" tool's own processing artifacts can introduce
additional column-reconstruction noise on top of the above; (4) **new, found during the Hammond
*Serbian: An Essential Grammar* extraction**: a fixed, decodable font-substitution cipher on
Cyrillic and Latin-diacritic characters (this book's specific mapping: š→e, č→a, ć→z, ž→f, đ→]) —
distinct from garbled OCR (there's a real, present text layer) and from the other column bugs above;
confirmed independently by 4 different subagents extracting different chapters, all correctly
identified the pattern and either cross-referenced known vocabulary to decode it or fell back to the
book's own parallel Latin-script column when unsure. Worth checking for on any future PDF whose
Cyrillic renders as unrelated glyph soup despite having a real text layer — it may be this same kind
of fixed-but-undocumented font remapping rather than unusable garbage.
- **(5) A scanned book's page images can be two-printed-pages-per-scan spreads, not one-page-per-scan.**
  Found on `Colloquial Serbian/Colloquial Serbian.pdf` (194 physical PDF pages for a book with
  printed page numbers up to ~375) — a naive `printed_page ≈ PDF_page + fixed_offset` estimate is
  wrong by roughly half. **Every one of 10 subagents dispatched against this file independently
  self-corrected** by directly inspecting a few rendered pages before committing to a range, rather
  than trusting the dispatch's estimate — worth explicitly telling future vision-reading dispatches
  to verify their assumed offset empirically on the first page or two before assuming any fixed
  formula, since spread-scanning isn't detectable from `pdfinfo`'s page count alone.

## Graphify

This language gets its own graph, scoped to `datasets/Serbian_Croatian_Bosnian/` (separate from
`language_corpus/Serbian_Croatian_Bosnian/`'s own graph). **Rebuilt after Colloquial Serbian's
completion** (97 files, ~708,000 words) — 339 nodes, 438 edges, 37 communities. See `graphify-out/`
in this folder. Semantic extraction was split into 7 subagent chunks this time; the cache-based
incremental-update path still isn't available since the original bridge-test merge bypassed the
cache-save step, so every rebuild has been a full re-extraction — worth using the cache path properly
if a future rebuild needs it at larger scale. **Known minor graph-quality issues, left unfixed** (both
benign, not corruption, both would need manual node-ID reconciliation across chunks to fix):
(1) the flagship textbook still appears as two separate god nodes under different node IDs; (2) this
rebuild's chunk 4 (Hammond's book) guessed 20 cross-chunk node IDs pointing at chunk 3's files instead
of just noting the relationship in a label — none of the guessed IDs matched chunk 3's actual node
IDs, so all 20 edges were silently dropped as dangling at build time (438 valid out of 458 raw edges).
The lesson for future dispatches: **instruct subagents to note likely cross-chunk connections in a
node's label/description, not to fabricate a specific cross-chunk edge/ID** — worth adding to the
graphify dispatch instructions template if this recurs.

**Before re-running: `cd` into `datasets/Serbian_Croatian_Bosnian/` first, don't run graphify's own
Python calls from the repo root with only a `root=` argument.** Confirmed real bug (Hungarian test
run): `save_manifest()` and likely other graphify internals resolve output paths relative to the
*working directory*, not `root=` — running from the repo root can silently corrupt the repo-root
`graphify-out/manifest.json`. **After running, always check `git status`/`git diff` on the repo-root
`graphify-out/` before committing.** See `../00_Reference_Extraction_Spec.md` for the full writeup.

## Mechanisms examined

- [ ] *(not started — Phase 1 reference extraction only so far, Phase 3 mechanics analysis has not
      begun. However, the syllable-switching slang mechanism found in `025_appendices7-8_literary_
      readings.md` is flagged as an obvious first candidate once Phase 3 begins.)*

## Reference extraction progress (Phase 1)

- [x] `01.Bosnian Croatian Serbian a Textbook...` — **full book complete** (all 20 lessons +
      Appendices 1-6, 9, 7-8 + full BCS-English glossary, 32 files, ~8,450 rows). This is the
      project's first full-book bridge-scale extraction — see
      `../../methodology-observations/serbian_croatian_bosnian_test_run.md` for the full writeup.
- [x] `11.Bosnian Croatian Serbian - A grammar & Social Commentary.pdf` — **full book complete**,
      the second full-book extraction for this language (15 files, `established/031`-`045`, ~990
      rows, ~67,000 words). Sociolinguistic Commentary (Ch. 21-26) extracted first per the
      register-chapter-prioritization finding; Grammar (Ch. 1-20) extracted second, deliberately
      scoped against the already-extracted flagship textbook — Chapters 1-16 (which the source's own
      preface states correspond directly to the textbook's Lessons 1-16) extracted as
      non-redundant supplements only, Chapters 17-20 (no lesson analog: case-usage review, word
      formation, clitic placement/accent, phonology) extracted fully and normally.
- [x] `10.Serbian an essential grammar.pdf` — **full book complete** (13 files,
      `established/046`-`058`, ~780 rows, ~52,000 words). Third full-book extraction for this
      language, all three of it deliberately checked against the two prior books' overlapping
      grammar content — extracted normally where genuinely new (dialects, numerals, quantifiers/
      determiners/particles, sentence structure), as non-redundant supplements where it overlapped
      (verbs, nouns, pronouns, adjectives, adverbs/prepositions, conjunctions/enclitics). This
      book's PDF has a decodable font-substitution cipher on Cyrillic and diacritic characters
      (š→e, č→a, ć→z, ž→f, đ→]) — confirmed independently by 4 different subagents; see the
      PDF gotchas note below.
- [x] `12.Introduction to the Croatian and Serbian language.pdf` (Magner) — **all 30 lessons complete**
      (Lesson 1 in `established/002`, Lessons 2-30 in `established/059`-`064`, vision-read across 6
      subagent chunks, ~1,190 rows total). Page ranges chained with zero gaps or overlaps (PDF pp.
      7-9, 10-24, 25-40, 40-54, 55-69, 69-82, 83-94), independently cross-validated by each chunk's
      own boundary-finding. **A bonus 12-reading "Čitanka" (Reader) section was found starting at PDF
      p. 95, beyond the 30 lessons — not extracted, deliberately deferred** (see the deferred-content
      note below) rather than opening a new dispatch wave for it in the same pass.
- [ ] **Deferred:** Magner's own "Čitanka" (Reader) section, PDF pp. 95+ — 12 numbered readings (e.g.
      "Šestinska svadba," "Iskustva mladog liječnika") past the 30 lessons, found but not extracted
      during the lessons pass. Worth returning to for literary/archaic-tier vocabulary, same rationale
      as the deferred *Serbian Folk Tales* below.
- [x] `03.Colloquial Serbian and Croatian.pdf` (318p, vision-only) — **full book complete** (16
      files, `established/065`-`073`+parts, ~1,868 rows, ~96,000 words): all 20 units, the grammar
      summary, and the full glossary. Confirms the register-prioritization finding once more — the
      "colloquial" framing genuinely delivered register-tagged content (e.g. `halo` flagged
      telephone-only, informal/formal parting-word pairs) that formal grammar chapters don't.
- [x] `Colloquial Serbian/Colloquial Serbian.pdf` (194p, vision-only) — **full book complete** (13
      files, `established/074`-`083`+parts, ~1,563 rows, ~95,500 words). Distinct edition/title from
      the book above (same author, "grew out of" it per its own acknowledgements) — Serbian-only,
      Cyrillic-primary, Ekavian. Non-redundant-supplement pattern applied to overlapping units;
      genuinely new content extracted fully (Village life, Music, Kotor/Montenegro — no analog in the
      sister book). Confirmed a fixed PDF page-spread-scan gotcha: this file packs 2 printed pages
      per PDF image, so simple offset-based page estimates were wrong by roughly half — every
      subagent correctly self-corrected by direct inspection; see the PDF gotchas note below.
- [x] `29.Serbian Folk Tales.pdf` (240p, vision-only) — **full book complete**, revisited and
      extracted rather than left deferred (9 files, `established/084`-`092`, ~535 rows, ~45,000
      words). Pure literary/folkloric content — vocabulary-only extraction via the book's own inline
      "+" margin glosses, no plot/prose reproduction. Best finding: two independently-attested
      taboo-avoidance-naming patterns (snake, then wolf/bear), a real documented example of
      taboo-inversion slang mechanics. Also found source-internal dialect/register contrasts between
      tales (different original collectors/regions within one anthology) and 4 tales missing from
      the initially-captured table of contents.
- [ ] `Teach Yourself Serbian/Teach Yourself Serbian.pdf` (177p, garbled OCR text layer — needs
      vision reading, not `pdftotext`) — not started, low priority per the triage catalog.
- [ ] `01.Key to audio recordings.PDF` (2p, trivial) — low value, not started.

**Correction to a stale claim in this section (found during the follow-on extraction pass):**
Phase 0 triage for this language is already complete — see `00_Book_Triage_Catalog.md`, which
covers all 9 real reference documents (2 of which live in subfolders: `Colloquial Serbian/` and
`Teach Yourself Serbian/`, each containing one book). There is no separate set of "6 untriaged
audio-course subfolders" for this language — that claim, which appeared in an earlier version of
this section, was inaccurate (likely conflated with the Hungarian language folder's own 6 deferred
subfolders, a genuinely different situation). Corrected here so it doesn't get repeated.

**Resolved methodology questions (see `../00_Reference_Extraction_Spec.md` and
`../../methodology-observations/serbian_croatian_bosnian_test_run.md`):** coverage is
comprehensive-but-not-exhaustive (every grammar point, every distinct vocabulary item, every
regional annotation; skip repeated drills — except dense glossaries, which get genuinely exhaustive
treatment since they have no padding to skip); extraction is subagent-parallelized, chunked by
lesson/chapter; **confirmed working at bridge-test scale (28 chunks, up from the previously-tested
3)** — see the observations log for the full verdict on readiness for full-language-folder-scale
extraction across all 40+ languages.

## Suggested next-session order

**Goal: full-language-folder extraction for this language** (see
`methodology-observations/serbian_croatian_bosnian_test_run.md`'s bridge-scale-test verdict —
methodology validated for this, budgeting wave-based dispatch per `00_Reference_Extraction_Spec.md`).

1. **7 of 9 books done: all 3 clean-text-layer books, Magner's full 30 lessons, both
   "Colloquial"-titled books, and Serbian Folk Tales.** What remains: `Teach Yourself Serbian.pdf`
   (177p, garbled OCR text layer — needs vision reading, not `pdftotext`). `01.Key to audio
   recordings.PDF` (trivial, 2 pages) and Magner's deferred "Čitanka" reader section (PDF pp. 95+)
   can be picked up cheaply alongside it.
2. Once all 9 real reference documents are extracted (or explicitly deferred with reason), this
   language's Phase 1 is genuinely complete — update `ROADMAP.md`/`00_Analysis_Index.md` to reflect
   that milestone explicitly, since it would be the first language to reach it.
3. Given the full corpus now available, Phase 3 (mechanics analysis) could plausibly begin once
   `language_corpus/Serbian_Croatian_Bosnian/` reaches `in progress` — the syllable-switching slang
   mechanism alone is a strong first analysis target.
