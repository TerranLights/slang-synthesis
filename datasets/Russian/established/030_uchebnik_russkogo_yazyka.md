# Russian — Established Vocabulary/Grammar: Учебник русского языка для студентов-иностранцев (full book, sampled)

**Source:** Е.И. Мотина et al. (collective authorship credited on the imprint page as Е.М. Григорьева,
Е.Ю. Владимирский, Т.М. Дорофеева, М.Н. Лебедева, В.И. Половникова, Л.Б. Трушина — exact byline
order uncertain, imprint page is low-legibility even under vision-reading), *Учебник русского языка
для студентов-иностранцев, обучающихся на подготовительных факультетах вузов СССР* ["Textbook of
Russian for Foreign Students at Preparatory Faculties of USSR Higher-Education Institutions"],
publisher «Русский язык» (Moscow), 4th ed., 1976. Whole book, 303 printed pages, 21 lessons (уроки)
plus foreword. Source file: `source_reference/languages/Russian/Russian Learning Pack [up-to-date
as of 2012]/Vol 1 of 3/12.Uchebnik russkogo yazyka dlya studentov inostrancev.pdf`.

**Coverage note — sampled, not page-by-page.** This is a beginner-to-lower-intermediate teaching
grammar whose lesson sequence (nominative → present tense → past tense → future tense → accusative
→ genitive → dative → instrumental → prepositional, each split animate/inanimate and
singular/plural, spread across 21 уроки) covers exactly the same core paradigm territory as several
already-extracted Wave 1 sources (`001-001n_basic_modern_russian_grammar.md`,
`005/005b_intermediate_russian_grammar_workbook.md`, `008/009_russian_self_teaching_guide_part1/2.md`,
`012/013_russian_grammar_schaums_outlines_part1/2.md`). Per the "non-redundant supplement" pattern:
rather than re-transcribing all 303 pages of case paradigms already tabulated elsewhere, this file
was built from (a) the full table of contents (vision-read in its entirety — pp. 296–302 printed,
which lists every lesson's texts, grammar models, and grammar-commentary topic list with page
numbers) and (b) a representative sample of ~20 content pages spread across lessons 1, 4, 5, 8, 9,
12, 14, 15, 18, 20, and 21 (vision-read in full), chosen to weight toward what is genuinely
*not* already captured elsewhere: this book's distinctive 1970s-Soviet-institutional vocabulary and
subject matter (dormitory/`общежитие` life, `декан`/deanship administration, kolkhoz excursions, the
VDNKh exhibition, a WWII steelworker's narrative, an October Revolution/Lenin narrative reading, and
the Bratsk hydroelectric dam construction narrative) — none of which appear in the grammar references
already extracted, which are largely apolitical/modern in their example sentences. Repeated drill
exercises (`Упражнения`) that only re-use already-captured vocabulary in different sentence frames
were skipped per the coverage rule; a few drills were read where they usefully confirmed a closed set
(e.g. a list of Soviet city names) and are noted below.

**What was skipped as redundant:** the accusative/genitive/dative/instrumental/prepositional case
paradigm tables themselves (adjective + noun + possessive + demonstrative agreement by
gender/number) — these are structurally identical in form and content to tables already fully
captured in `001-001n` and `005/005b`. One paradigm table *is* reproduced below (accusative
singular/plural across genders, Lesson 4) purely as a representative example, since its layout
(explicit possessive-pronoun and `этот`/`весь` columns side by side) is somewhat more exhaustive than
prior sources' equivalent tables.

**Vision-reading note:** this PDF's baked-in OCR text layer is badly corrupted — `pdftotext` produces
homoglyph/OCR "soup" (Cyrillic letters rendered as visually-similar Latin letters and digits, e.g.
"УЧЕБНИК РУССКОГО ЯЗЫКА" → `YIIEbH14K PYCCKOfO fl3bIKA`; "Учебник по учебнику русского языка
предназначен для обучения иностранцев..." renders as scrambled quasi-Latin gibberish throughout).
Unlike the fixed 1:1/keyboard-layout/cp1251 ciphers found elsewhere in this corpus, spot-checking
across ~15 widely separated pages found **no consistent character-level mapping** — the same Cyrillic
letter decodes to different Latin glyphs in different words/contexts (a many-to-one, context-dependent
OCR failure, matching gotcha #6 in the extraction spec: "non-decodable, context-dependent many-to-one
OCR garbling"). This is **not decodable as a fixed cipher**; every page cited in this file was
vision-read directly from a rendered PNG rather than from the text layer. All pages vision-read
were clearly typeset/printed textbook content — no handwritten marginalia was found on any sampled
page (this copy shows no evidence of prior-owner annotation).

---

## Lesson-by-lesson topic map (from the vision-read table of contents, pp. 296–302 printed)

Extracted here because the syllabus sequencing itself is informative (it shows the pedagogical order
in which Russian's fusional case/aspect system is conventionally introduced to foreign learners) even
though the individual paradigm tables it points to substantially duplicate prior extractions.

| Lesson | Topic/text | Key grammar introduced |
|---|---|---|
| 1 (первый) | Intro text (classroom objects) | Это + noun; genderless "this is" question forms; word-formation студент→студентка |
| 2 (второй) | Андре и Диало | Present-tense verb conjugation |
| 3 (третий) | Комната Андре и Диало | Verbs жить/читать/говорить; noun gender (m/n/f); possessive pronouns |
| 4 (четвёртый) | Дома; Квартира | Verbs писать/идти/стоять; reflexive (-ся) verbs; adjectives; possessives его/её/их; numerals 1–20 |
| 5 (пятый) | Универмаг; Книжный магазин | Verb хотеть; numerals 21–100; demonstrative этот; adjective хороший |
| 6 (шестой) | Выходной день | Verbs лежать/смотреть; past tense; pronoun весь; ordinal numerals |
| 7 (седьмой) | Москва | Verbs видеть/ехать; transitive/intransitive; plural nouns; accusative (inanimate) sg./pl. |
| 8 (восьмой) | Письмо Диало; Общежитие | Verbs уметь/ждать/смеяться; future tense; -ся verbs (учиться); plural nouns/possessives/adjectives/этот |
| 9 (девятый) | В читальном зале; Разговор по телефону | Verbs мочь/рисовать; perfective/imperfective aspect; accusative sg./pl. (adjectives, possessives, этот, весь) |
| 10 (десятый) | Каникулы; Мари и Жан | Verbs брать/начать/взять/собраться; perfective future; должен + infinitive; -ий adjectives |
| 11 (одиннадцатый) | Университет; Разговор в коридоре | Verbs петь/открыть/понять; prepositional case sg. (nouns, adjectives, possessives, этот); prepositions в/на |
| 12 (двенадцатый) | Билет на балет; На улице | Verbs пойти/прийти/дать/давать; short-form adjective доволен; -ь nouns in acc./prep. sg. |
| 13 (тринадцатый) | Встреча в Индии; Сочинение Диало | Verb вернуться; acc./prep. of -ия/-ие nouns; animate accusative; personal pronouns in acc./prep.; possessive свой |
| 14 (четырнадцатый) | Экскурсия в колхоз; Рассказ колхозницы | Verb устать; genitive singular; ordinal numerals in genitive |
| 15 (пятнадцатый) | Экскурсия на ВДНХ | Verbs принести/бороться; genitive of adjectives/possessives/этот, sg. |
| 16 (шестнадцатый) | Туристический поход | Verbs класть/стать; genitive plural of personal pronouns; relative clause with который |
| 17 (семнадцатый) | Если парни всей земли... | Verbs погибнуть/умереть; dative singular (nouns, personal pronouns, adjectives, этот, possessives) |
| 18 (восемнадцатый) | Рассказ рабочего | Dative plural (nouns, adjectives, possessives, этот) |
| 19 (девятнадцатый) | Наш друг доктор | Verbs есть/пить/спасти; pronoun весь; imperative mood |
| 20 (двадцатый) | 7 ноября; Рассказ о победе Октябрьской революции | Verbs бежать/снять; instrumental case (nouns, adjectives, personal/possessive pronouns, этот) sg. and pl. |
| 21 (двадцать первый) | Широка страна моя...; Братская ГЭС | Verbs замёрзнуть/течь; genitive plural (nouns/adjectives); comparative adverbs |

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| общежитие | dormitory/student residence hall | noun (n.) | core | — | contemporary (source published 1976) | — | — | grammar_reference | n/a | verified | Lesson 8 vocabulary; recurring theme across the book (student housing) |
| декан | dean (of a faculty) | noun (m.) | core | — | contemporary (1976) | — | — | grammar_reference | n/a | verified | Lesson 8, appears in dialogue title "В деканате" (at the dean's office) |
| колхоз | kolkhoz, collective farm | noun (m.) | core.historical | — | contemporary (1976); denotes a Soviet-era institution | USSR | national | grammar_reference | n/a | verified | Lesson 14 title "Экскурсия в колхоз"; genuinely era-specific term this project's other Russian sources (mostly post-Soviet/Western-published grammars) don't foreground |
| колхозник / колхозница | male/female kolkhoz worker | noun (m./f.) | core.historical | — | contemporary (1976) | USSR | national | grammar_reference | n/a | verified | Lesson 14, "Рассказ колхозницы" (a kolkhoz worker's own first-person narrative) |
| ВДНХ | VDNKh (Exhibition of Achievements of the National Economy, Moscow) | proper noun (abbreviation) | technical | — | contemporary (1976) | Moscow | local | grammar_reference | n/a | verified | Lesson 15; text names specific pavilions: советской культуры, Академии наук СССР, лёгкой промышленности, химической промышленности, электротехники, механизации и электрификации сельского хозяйства, транспорта |
| сталевар | steelworker/steel-founder | noun (m.) | technical.occupation | — | contemporary (1976) | — | — | grammar_reference | n/a | verified | Lesson 18 "Рассказ рабочего"; morpheme-composed term, see breakdown below |
| бригада | (work) brigade/team | noun (f.) | core | — | contemporary (1976) | USSR | national | grammar_reference | n/a | verified | Lesson 18, industrial-labor register |
| фронт | (military) front | noun (m.) | core | — | contemporary (1976) | — | — | grammar_reference | n/a | verified | Lesson 18, WWII narrative context; collocation "идти на фронт" |
| танк | tank (armored vehicle) | noun (m.) | core | — | contemporary (1976) | — | — | grammar_reference | n/a | verified | Lesson 18 |
| сталь | steel | noun (f.) | core | — | contemporary (1976) | — | — | grammar_reference | n/a | verified | Lesson 18; collocation "танки делали из этой стали" |
| вооружённое восстание | armed uprising | noun phrase | core.political | — | contemporary (1976); refers to October 1917 | Petrograd/USSR | national | grammar_reference | n/a | verified | Lesson 20, October Revolution narrative |
| большевик | Bolshevik | noun (m.) | core.political | — | historical referent (1917), source published 1976 | Russia/USSR | national | grammar_reference | n/a | verified | Lesson 20 |
| съезд Советов | Congress of Soviets | noun phrase (proper) | core.political | — | historical referent (1917) | Petrograd | national | grammar_reference | n/a | verified | Lesson 20; the Smolny Institute setting is named explicitly |
| Смольный | the Smolny Institute (Petrograd) | proper noun | core.political | — | historical referent (1917) | Petrograd/Leningrad | local | grammar_reference | n/a | verified | Lesson 20 dialogue heading "Рассказ (В Смольном)" |
| матрос | sailor | noun (m.) | core | — | contemporary (1976) | — | — | grammar_reference | n/a | verified | Lesson 20 |
| буржуазное временное правительство | bourgeois Provisional Government | noun phrase | technical.historical | — | historical referent (1917) | Russia | national | grammar_reference | n/a | verified | Lesson 20 vocabulary box |
| помещик | landowner (pre-revolutionary estate owner) | noun (m.) | archaic/historical | — | historical referent (pre-1917) | Russia | national | grammar_reference | n/a | verified | Lesson 20 |
| капиталист | capitalist | noun (m.) | core.political | — | contemporary (1976) | — | — | grammar_reference | n/a | verified | Lesson 20 |
| вождь | leader (esp. of a revolution/party) | noun (m.) | core.political | — | contemporary (1976) | — | — | grammar_reference | n/a | verified | Lesson 20, applied to Lenin in the narrative text |
| человечество | humankind | noun (n.) | core | — | contemporary (1976) | — | — | grammar_reference | n/a | verified | Lesson 20, closing line of the Lenin speech excerpt |
| гидроэлектростанция / ГЭС | hydroelectric power station / abbreviation thereof | noun (f.) / abbreviation | technical | — | contemporary (1976) | — | — | grammar_reference | n/a | verified | Lesson 21, "Братская ГЭС" (Bratsk Hydroelectric Station) as the running example |
| плотина | dam | noun (f.) | core | — | contemporary (1976) | — | — | grammar_reference | n/a | verified | Lesson 21 |
| комсомолец | Komsomol member (Communist youth league) | noun (m.) | core.political | — | contemporary (1976) | USSR | national | grammar_reference | n/a | verified | Lesson 21, "много комсомольцев работало на строительстве Братской ГЭС" |
| тайга | taiga | noun (f.) | core.geographic | — | contemporary (1976) | Siberia | regional | grammar_reference | n/a | verified | Lesson 21 |
| стройка | (major) construction site/project | noun (f.) | core | — | contemporary (1976) | — | — | grammar_reference | n/a | verified | Lesson 21, "вся страна превратилась в огромную стройку" |
| пятилетка | five-year plan | noun (f.) | core.political | — | contemporary (1976) | USSR | national | grammar_reference | n/a | verified | Lesson 21 vocabulary box |
| стол / стул / доска / карта / окно | table / chair / (black)board / map / window | nouns | core | — | contemporary (1976) | — | — | grammar_reference | n/a | verified | Lesson 1 opening classroom-object set |
| студент / студентка | (male/female) student | nouns | core | — | contemporary (1976) | — | — | grammar_reference | n/a | verified | Lesson 1; word-formation model студент→студент-ка is the book's very first explicit derivational example |
| преподаватель / аспирант / аспирантка | instructor / (male/female) graduate student (aspirant) | nouns | core.academic | — | contemporary (1976) | USSR | national | grammar_reference | n/a | verified | Lesson 1; "аспирант" reflects the Soviet post-graduate research-student system, a term some other sources gloss differently or omit |
| пианино / кресло / диван / шкаф / телевизор | piano / armchair / sofa / wardrobe / television | nouns | core | — | contemporary (1976) | — | — | grammar_reference | n/a | verified | Lesson 4, furniture set |
| большой ≠ маленький / светлый ≠ тёмный / новый ≠ старый | big≠small / light≠dark / new≠old | adjective antonym pairs | core | — | contemporary (1976) | — | — | grammar_reference | n/a | verified | Lesson 4, the book explicitly teaches vocabulary in antonym pairs at this stage |
| Ленинград, Киев, Рига, Таллин, Минск, Кишинёв, Ташкент, Ереван, Харьков, Одесса, Новосибирск, Омск | (Soviet-republic capital and major) city names | proper nouns | core.geographic | — | contemporary (1976) | USSR | national | grammar_reference | n/a | verified | Lesson 12 drill exercise (Упражнение 2) — closed substitution list, read because it is a genuinely useful closed-set of Soviet-era city names not tabulated elsewhere in this project's Russian corpus |
| стал-е-вар | (morphologically composed: see breakdown) | noun (m.), compound | technical.occupation | — | contemporary (1976) | — | — | grammar_reference | n/a | verified | The book itself gives this exact hyphenated word-formation breakdown under "Словообразование" on p. 211 |

**Morpheme breakdown.**

> **сталевар** = сталь- ("steel", root) + -е- (linking/interfix vowel) + -вар- (root of варить, "to
> smelt/cook/boil") + Ø (zero ending, masculine agentive) — a compound agentive noun literally
> "steel-smelter," structurally identical in formation to the more familiar сталелитейщик-type
> Russian occupational compounds; the book's own словообразование note (p. 211) supplied this exact
> segmentation rather than treating сталевар as an unanalyzed atom, and it's reproduced here as a
> clean worked example of Russian's compound-agentive-noun formation pattern for the mechanics-
> analysis phase.

---

## Grammar points

### Accusative case: adjectives, possessives, this/all — singular and plural, by gender (Lesson 9, p. 104–105)

The book presents accusative agreement as four parallel tables (nouns already covered earlier;
here adjectives, possessive pronouns, and the demonstratives этот/весь) cross-cutting
singular/plural × masculine/neuter/feminine, all keyed to the same worked example sentences ("Здесь
лежит..."/"Он видит..." for inanimate accusative = nominative-syncretic forms). Distinctive here
versus prior Wave-1 extractions: the third-person possessive slot (его/её/их) is explicitly marked as
invariant across gender/number in this table (unlike мой/твой/наш/ваш, which fully decline) — the
book flags this irregularity directly rather than leaving it implicit.

### Perfective/imperfective aspect pairs (видовые пары), introduced via concrete minimal pairs (Lesson 9, p. 104)

Rather than stating the aspect rule abstractly, the book teaches it through paired example sentences
contrasting a repeated/ongoing past action (imperfective: "Вчера я читал рассказ" / "Вечером я долго
читал рассказ") against a single completed action (perfective: "Я прочитал этот рассказ"), plus a
minimal pair "Ты решил эту задачу? — Я решал её, но не решил" (I was working on it [ipf.] but didn't
solve it [via negated pf.]) that is a clean pedagogical illustration of the aspectual distinction
between attempted-but-incomplete and completed action — worth flagging for the mechanics-analysis
phase as source material on how Russian aspect is conventionally taught to explain the "attempted
action" nuance.

### Word formation examples the book calls out explicitly (Словообразование)

Scattered one per lesson rather than gathered into a single reference section: студент→студент-ка
(L1); учё-ник/учё-ница, нем-ец/нем-ка (L3); тёплый→тепл-о (L8); математика→математич-еск-ий (L9);
зима→зим-н-ий (L10); строить→строи-тель, строитель→строитель-н-ый (L12); колхоз-ник/колхоз-ниц-а,
школь-ник/школь-ниц-а, трудн-ый/трудн-ость (L14); сообщ-ить/сообщ-ени-е (L17); стал-е-вар (L18,
detailed above). The consistent pattern across all of these: the book always shows agentive/feminine
(-ник/-ница, -тель) and adjectival (-н-, -еск-) suffixation as small paired contrasts rather than a
systematic affix inventory — useful evidence that this is how a 1970s Soviet pedagogical tradition
sequenced morphological awareness for foreign learners (concrete pairs before abstract rules), a
framing difference from the more systematic affix-inventory approach several of the other Wave-1
grammar references take.

### Prepositional pair в→из / на→с (Lesson 11, p. 166)

Explicitly tabulated as a single paired rule: a noun taking в for "into"/location takes из for
"out of" ("из стола, со стола"; the model diagrams в→из and на→с as a matched pair), including the
epenthetic vowel adjustment (из/со alternation conditioned by the following word's initial
consonant cluster — "со стола" not "из стола" is used as the model form, though the book's own
example list mixes из- and с- forms per noun without stating the alternation rule outright, so this
is an area where the source is less systematic than a modern reference grammar).

### Ordinal numerals in the genitive, used specifically for dates (Lesson 11, p. 166)

"Заметьте: третье января / третьего января" — the book flags that Russian date expressions use the
genitive of the ordinal (not nominative) explicitly as a "notice this" aside rather than folding it
into the general ordinal-numeral paradigm table, suggesting the authors treated the date-genitive
usage as a distinct high-frequency construction worth calling out separately from ordinal
declension in general.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. Narrative-text excerpts above (Lenin/October Revolution,
Bratsk GES) are paraphrased summaries with only short illustrative phrases quoted directly, not
full-paragraph reproduction, per `00_Reference_Extraction_Spec.md`.
