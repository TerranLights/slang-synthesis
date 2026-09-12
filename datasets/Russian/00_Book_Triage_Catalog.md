# Russian — Reference Material Triage Catalog

**Status: full triage complete, 2026-09-12.** Russian is one of the 43 Inner Tepenia GDD
Gini-index high-priority languages (Russia, ~25M effective) — see `../../LANGUAGE_INDEX.md`.
`source_reference/languages/Russian/` is ~3.6GB, 204 real files (171 PDF + 31 DJVU + 1 JPG + 1 DOC)
across a top-level `Russian Grammar books/` folder, a single top-level course book (*Troika*), and a
3-volume "Russian Learning Pack [up-to-date as of 2012]" that is itself subdivided into
`Vol 1 of 3`, `Vol 2 of 3` (with `01 - Audio Courses, Textbooks, Manuals`, `02 - A Collection of
Folk Tales...`, `03 - Dictionaries, Phrasebooks` subfolders), and `Vol 3 of 3`. No audio/video files
exist despite folder naming ("Audio Courses" folder holds only PDFs) — confirmed via extension
census. This is by a wide margin the largest and most heterogeneous corpus this project has
triaged so far — roughly 1.5x Hungarian's file count and the first corpus where the **large
majority of files are scanned image-only PDFs/DJVUs with no text layer at all**.

**Tooling note:** the same subfolder-path gotcha applies as with Hungarian/Korean — use
`find -printf '%p'`, not `%f`, inside the nested `Vol N of 3` folders.

---

## Scope filtering — categories excluded from Phase 1 entirely

Given the corpus size, filtering happened at the category level first (unlike smaller languages'
per-file triage), following the same content-type-boundary precedent set by Hungarian/Korean:

- **Non-English bilingual dictionaries/phrasebooks** (Russian-Norwegian, Russian-Dutch,
  Russian-Bulgarian, Russian-Modern Greek, Russian-Italian Proverbs, Russian-Portuguese,
  Berlitz Hebrew-Russian, Russian-German/-French/-Spanish phrasebooks, Rusko-Český Slovník,
  Russisk-Dansk ordbog, a Hebrew-Russian children's illustrated dictionary) — this project's
  extraction is English-medium; a Russian-English pairing is in scope, a Russian-X pairing for any
  other language is not. The one exception kept: `Russian-English Phrasebook.djvu` (Dictionaries,
  Phrasebooks/12) and the English-Russian technical-terms dictionary (05) — both have an English
  side.
- **Non-English-metalanguage courses** (Hable Ruso, Lecciones de Ruso, El Ruso Gramatica Practica,
  El Ruso En Ejercicios, Casos y Preposiciones del Idioma Ruso — all Spanish-medium; Ruski jezik —
  Serbian-medium; RU-SK konverzácia — Slovak-medium) — same exclusion rule as Hungarian's
  non-English-metalanguage courses.
- **Travel guides** (Frommer's Moscow & St. Petersburg, По странам и континентам, Russian for
  Tourists).
- **History/culture/literature/poetry volumes** (The Cambridge History of Russia I/II/III, The
  Cambridge Introduction to Russian Poetry, The Cambridge Introduction to Russian Literature, The
  Cambridge Companion to Modern Russian Culture, Pop Culture Russia!, Русские стереотипы поведения
  традиции ментальность, Какие мы русские, Поговорим о России, Russian Culture Reader, Из истории
  русской культуры, От Пушкина до Бродского [poetry anthology], О России на русском, Россия и
  русские сегодня, Россия традиции прошлого и настоящее, Как иметь дело с русскими [business/culture
  guide], Русский без границ *Literature* volume [its *Grammar* sibling volume stays in scope]).
- **Test/exam-only booklets** (Тесты тесты тесты × 3 levels, Учебно-тренировочные тесты × 3 parts,
  Practice Tests × 2 levels) — near-zero narrative/register content, mostly answer-key drills.
- **Fiction/genre reading** (4 Ravenloft novels in Russian [Gothic horror translations], Sergey
  Ivanovich i Tanya, Short Stories By Soviet Writers, Russian fairy tales Parallel Texts, An
  Advanced Russian Tabloid Reader) — deferred; these are closer to `language_corpus/` register
  material than Phase 1 grammar/vocabulary reference, and this corpus already has enough in-scope
  reader/register material without them.
- **Niche specialist jargon** (Russian for Chessplayers, Russian for Mathematicians) — real
  vocabulary but low relevance to slang/register work; deferred rather than dropped.
- **Pure picture/frequency dictionaries with minimal running text** (Picture Dictionary Russian,
  Russian Learners' Dictionary 10000 Words in Frequency Order, Learn Russian the Fast and Fun Way)
  — word-list format, low per-page yield relative to extraction cost.
- **The 20-volume "Сказочник" folk-tale series** (Vol 2/02 subfolder) — a large from-scratch
  Russian-only children's-reader anthology with no text layer on any volume. Precedent (SCB's single
  folk-tale anthology, in scope) supports *some* representative content, but 20 full volumes of
  vision-reading is disproportionate; flagged for **representative sampling** (2-3 volumes) in a
  later wave rather than full coverage, the same discipline used on oversized dictionaries.

**None of the above is a permanent exclusion** — it is a scoping decision to keep this run
tractable, the same judgment call Hungarian's grab-bag-subfolder filtering made. Revisit if a later
pass has budget to spare.

---

## In-scope material — grouped by text-layer status

### Group A — Clean text layer, high value, no duplication (Wave 1)

| File | Pages | Notes |
|---|---|---|
| `Russian Grammar books/A Basic Modern Russian Grammar.pdf` | 195 | Core grammar reference |
| `Russian Grammar books/A Comprehensive Russian Grammar.pdf` | 632 | = Terence Wade's *A Comprehensive Russian Grammar* (Blackwell); **duplicate of `Vol 1 of 3/43.A Comprehensive Russian Grammar (Blackwell).pdf`** — confirmed via title-page match, extract once |
| `Russian Grammar books/compgrammar_russian.pdf` | 141 | = Edna Andrews, *Russian* (SEELRC 2001) — **duplicate of `stand_alone_russian.pdf`** in the same folder, confirmed via matching table-of-contents text; extract once |
| `Russian Grammar books/intermediate_russian_grammar_and_workbook.pdf` | 239 | **Duplicate of `Vol 1 of 3/41.Intermediate Russian a Grammar and Workbook.pdf`** — extract once |
| `Russian Grammar books/Reference Grammar Russian.pdf` | 511 | **Duplicate of `Vol 1 of 3/44.A Reference Grammar of Russian (Cambridge).pdf`** — extract once |
| `Vol 1 of 3/03.Russian A Self-Teaching Guide.pdf` | 313 | Course |
| `Vol 1 of 3/23.Colloquial Russian 2.pdf` | 353 | Course, second volume |
| `Vol 1 of 3/39.Russian Grammar (Schaum's Outlines).pdf` | 361 | Reference grammar |
| `Vol 1 of 3/55.The Big Silver Book of Russian Verbs.pdf` | 673 | Verb reference |
| `Vol 1 of 3/56.Using Russian Vocabulary.pdf` | 636 | Vocabulary/usage guide |
| `Vol 1 of 3/59.Newspaper Russian A Vocabulary of Administrative and Commercial Idiom.pdf` | 133 | Register-specific vocabulary |
| `Vol 1 of 3/61.Using Russian A Guide to Contemporary Usage.pdf` | 529 | **Register flagship candidate** — same title pattern as Korean's and Hungarian's strongest register sources |
| `Vol 1 of 3/28.Let's Speak Russian! - Давайте говорить по-русски.djvu` | 160 | Course, real DJVU text layer |
| `Vol 1 of 3/33.Teach Yourself Russian Grammar.djvu` | 216 | Reference grammar, real DJVU text layer |
| `Vol 3 of 3/26.Русский без границ Grammar.pdf` | 192 | Grammar volume (its Literature sibling excluded, see above) |
| `Vol 3 of 3/10.Русские глаголы движения с приставками.pdf` | 162 | Prefixed verbs-of-motion — a notoriously hard, register-relevant Russian grammar topic |
| `Vol 3 of 3/24.Когда не помогают словари. Часть I.pdf` | 206 | "When dictionaries don't help" — lexical/collocation practicum, idiom-adjacent |

**18 files nominally, 6 net duplicates → 15 distinct sources, ~4,850 pages.** Duplicates are noted
so a dispatched subagent can skip re-extracting content already covered under a different filename.

### Group B — Clean text layer, Russian-medium or narrower value (Wave 2 candidates)

`Vol 1 of 3/12.Uchebnik russkogo yazyka dlya studentov inostrancev.pdf` (303p, Russian-medium
foreign-student textbook), `Vol 1 of 3/36.Практическая грамматика для иностранных студентов.pdf`
(184p, has a parallel English title), `Vol 1 of 3/69.Russian Translation Theory and Practice.pdf`
(200p), `Vol 1 of 3/86.Синяя звезда - Blue Star Stories and tales...pdf` (258p, reader with
exercises), `Vol 2/01/10.Русский язык как иностранный. Рабочая тетрадь I сертификационный
уровень.pdf` (251p, workbook), `Vol 2/01/20.Chekhov's Humorous Short Stories...pdf` (73p, reader
with English notes and vocabulary — register/literary value), `Vol 2/01/19.Человек в современном
мире.pdf` (199p), `Vol 2/03/05.Англо-русский и рус-англ словарь техн. терминов.djvu` (English-Russian
technical dictionary — real English content), `Vol 2/03/06.Орфоэпический словарь русского
языка.djvu` (pronunciation dictionary, phonology reference value), `Vol 3/07.Изучаем виды
глагола.pdf` (60p, aspect study), `Vol 3/08.Мои друзья падежи (Грамматика в диалогах).pdf` (110p,
cases via dialogues), `Vol 3/12.Начинаем изучать русский.pdf` (74p), `Vol 3/15.Домашнее чтение
Учебное пособие.pdf` (136p, reader), `Vol 3/21.Читаем российские газеты.pdf` (67p, newspaper-register
reading practice), `Vol 3/22.Я читаю и говорю по-русски.pdf` (66p), `Vol 3/24.Когда не помогают
словари. Часть II.pdf` (127p, second half of the Part I already in Wave 1).

### Group C — No text layer at all, real reference/course value (Wave 3, vision-reading)

This is the largest and most consequential group in this corpus — **roughly 150 of the 204 files
in this corpus are scanned image-only with no usable text layer**, a far higher proportion than any
prior language this project has extracted (SCB ~56%, Hungarian ~50%, Korean ~35%; Russian is closer
to ~75%). Only the highest-value items are prioritized for vision-reading; the rest are deferred
(see below) rather than attempted exhaustively, given the sheer scale.

**Highest-priority vision-read targets:**
- `Vol 1 of 3/25.Streetwise Russian The Practical Guide to Contemporary Slang and Colloquial
  Expressions.pdf` (210p) — **the single highest-value target in the entire corpus**: a dedicated
  contemporary-slang guide, directly on-mission for this project.
- `Vol 1 of 3/100.Dermo! The Real Russian Tolstoi Never Used.pdf` (160p) — a slang dictionary by
  title; per the Hungarian *Magyar Szlengszótár* precedent, this likely belongs in
  `language_corpus/Russian/` (Phase 3) rather than `established/` once read — confirm the routing
  the same way Hungarian's slang dictionary was confirmed, rather than assuming.
- `Russian Grammar books/Living Russian Grammar.pdf` (179p) + `Living Russian Grammar Answer Key.pdf`
  (27p) — a complete grammar+workbook pair, high value despite requiring full vision-reading.
- `Vol 1 of 3/05.Colloquial Russian The Complete Course for Beginners.pdf` (317p)
- `Vol 1 of 3/06.Teach Yourself Russian.pdf` (160p)
- `Vol 1 of 3/02.The New Penguin Russian Course A Complete Course for Beginners.pdf` (528p)
- `Vol 1 of 3/04.Survival Russian a Course in Conversational Russian.pdf` (308p)
- `Vol 1 of 3/07.Russian in Exercises.pdf` (172p; skip the parallel Spanish-medium
  `07.El Ruso En Ejercicios.pdf`)
- `Vol 1 of 3/18.Ultimate Russian Beginner-Intermediate.pdf` (524p)
- `Vol 1 of 3/27.Ultimate Russian Advanced.pdf` (428p)
- `Vol 1 of 3/19.Linguaphone Russian Course.pdf` (85p)
- `Vol 1 of 3/24.Let's talk about life an integrated approach to Russian conversation.pdf` (286p)
- `Vol 1 of 3/26.How to say about it — Specific expressions of the colloquial speech.pdf` (265p) —
  register/colloquial-expressions guide
- `Vol 1 of 3/32.Essential Russian Grammar.pdf` (132p)
- `Vol 1 of 3/34.The Oxford Russian Grammar and Verbs.pdf` (257p)
- `Vol 1 of 3/35.Russian A practical grammar with exercises.pdf` (292p; skip the Spanish-medium
  `35.El Ruso Gramatica Practica.pdf`)
- `Vol 1 of 3/37.Russian Grammar Workbook A Self-Study Reference and Practice Book.djvu`
- `Vol 1 of 3/40.Russian Grammar in Literary Contexts.pdf` (426p)
- `Vol 1 of 3/45.Modern Russian Grammar A Practical Guide.pdf` (962p — largest single grammar in the
  corpus; near-zero text layer detected, confirm before committing full vision-reading budget)
- `Vol 1 of 3/47.Russian Grammar in Exercises and Comments.` Part 1 Morphology (424p) + Part 2
  Syntax (417p)
- `Vol 1 of 3/50.The Case Book for Russian.pdf` (316p)
- `Vol 1 of 3/52.Russian Verbs of Motion.pdf` (81p)
- `Vol 1 of 3/53.Vozvratnye Glagoly v Russkom Yazyke (Reflexive Verbs in Russian).pdf` (132p)
- `Vol 1 of 3/54.Verb use in Russian - Употребление видов глагола в русском языке.pdf` (137p)
- `Vol 1 of 3/57.Walking on Russian vocabulary - Прогулки по русской лексике.pdf` (226p)
- `Vol 1 of 3/58.Учебно-справочное пособие по лексике русского языка.pdf` (330p)
- `Vol 1 of 3/62.Everything in its time.pdf` (237p)
- `Vol 1 of 3/67.Russian Punctuation and Related Symbols.pdf` (266p)
- `Vol 1 of 3/42.Russian Grammar in Illustrations.djvu`
- `Vol 2/01/07.10 уроков русского речевого этикета.pdf` (106p) — **Russian speech-etiquette
  lessons, directly register-relevant**
- `Vol 2/01/03/04/05/06/08/09/11/13/14/16/17/18` — remaining Vol 2 course/vocabulary/thematic-text
  books (13 files, 92-475pp each)
- `Vol 2/01/12.Spravochnik po russkoy grammatike.djvu` — grammar reference
- `Vol 2/01/15.VocabuLearn Russian Level 1/2/3.pdf` — vocabulary courses (large files, mostly word
  lists — lower per-page yield, deprioritize within Wave 3)
- `Vol 3/01.Лексические трудности при изучении русского языка.pdf` (180p)
- `Vol 3/02.Лексика русского языка сборник упражнений.pdf` (376p)
- `Vol 3/03.Вариантные формы в русском языке.pdf` (135p)
- `Vol 3/04.Падежи! Ах падежи!.pdf` (188p)
- `Vol 3/05.Русские падежи.pdf` (56p)
- `Vol 3/06.300 глаголов совершенного и несовершенного вида в речевых ситуациях.pdf` (44p)
- `Vol 3/09.По-русски - без ошибок!.pdf` (310p)
- `Vol 3/11.Русский язык в грамматических таблицах.pdf` (133p)
- `Vol 3/27.Sintaksicheskaya frazeologiya dlya russkih i inostrancev.pdf` (97p) — syntactic
  phraseology
- `Vol 3/13.Говорим по-русски без переводчика.pdf` (87p)
- `Troika A Communicative Approach to Russian Language, Life, and Culture.pdf` (628p, top-level) —
  standard university course textbook

**Deferred within Group C, lower priority still (real value, but this run must draw a line
somewhere):** `Vol 2/01/09.Будем знакомы! Рабочая тетрадь.pdf`, `Vol 2/01/16/17.Россия день
сегодняшний / экономика и общество.pdf` (thematic texts, borderline culture), `Vol 2/01/13.Знаю и
люблю русские глаголы.pdf`, `Vol 2/01/08.Слушайте Спрашивайте Отвечайте.pdf`, `Vol 3/16` [poetry,
already excluded above], the 81/82/83/84 readers in Vol 1, `Vol 2/03/09.Большой фразеологический
словарь для детей.pdf` (a genuine Russian-only phraseological dictionary — real slang/idiom value,
but 224 pages of vision-reading for a children's dictionary is a lower-priority use of budget than
the items above), and the 20-volume Сказочник folk-tale series (representative-sample candidate,
see Scope filtering above).

---

## Recommended Phase 1 extraction priority order

**Wave 1 — clean text, highest value, dedup-aware (Group A, 15 distinct sources, ~4,850 pages):**
As listed in Group A above. Several are large (600+ pages) and should be split into 2 dispatch
chunks each (e.g. pp.1-300 / pp.300-632 for *A Comprehensive Russian Grammar*) rather than handled
as a single subagent call, mirroring the per-book chunking used for Korean's largest sources.

**Wave 2 — remaining clean-text supplements (Group B, 16 sources):** non-redundant-supplement
pattern applies heavily here — several titles (case guides, aspect guides, dialogue-based grammar)
likely overlap substantially with Wave 1's core grammars.

**Wave 3 — vision-reading (Group C, ~45 prioritized sources plus explicitly deferred items):** by
far the largest vision-reading burden this project has taken on. Expect this wave alone to need
multiple extraction sessions given ~45 sources averaging 250+ pages each. *Streetwise Russian* and
*Dermo!* should be extracted first within this wave given their direct slang/register relevance.

## Morphological typology (preliminary, per Phase 0 convention)

**Russian: fusional (inflectional), with six grammatical cases** (nominative, genitive, dative,
accusative, instrumental, prepositional) marked by noun/adjective/pronoun endings that fuse case,
number, and gender into a single morpheme — unlike Hungarian/Korean/Japanese's agglutinative
stacking, a single Russian case ending typically cannot be cleanly segmented into separate case +
number + gender morphemes. Verbal aspect (perfective/imperfective) is a further, largely
non-agglutinative dimension layered on top, frequently realized through suppletion or prefixation
rather than a clean stackable suffix. Register/politeness is expressed through the ты/вы
distinction (a T-V pronoun system, closer to French/German/Hungarian's te/maga-style split than to
Korean's fully grammaticalized six-level system) plus lexical choice, not through dedicated
honorific verb morphology. Will be refined with a real morpheme breakdown once the first grammar
extraction lands.
