# Russian — Established Vocabulary/Grammar: Ultimate Russian Advanced, Lessons 1–3

**Source:** Jack Blanshei (Living Language / Random House), *Ultimate Russian: Advanced* (1998,
content revised 2003), Уроки (Lessons) 1–3, pp. 5–60 (of 428 PDF pages total). No text layer at all
(`pdftotext` returns zero real characters across the whole file — confirmed via a full-document
non-ASCII-character scan returning 0 hits; `pdfinfo` shows "Producer: Adobe Acrobat 9.0 Image
Conversion Plug-in", i.e. every page is a raster scan). PDF page = printed page + 16 (verified
empirically: printed p. 5 = PDF p. 21, the start of Lesson 1's dialogue; page-spread gotcha checked
for and **not** present — one printed page per PDF page throughout the sampled range).

**Extraction method — OCR substituted for manual vision-reading, with a new source-specific
gotcha found and corrected.** Given the sheer page count (428 pages, no text layer), pages were
rendered to PNG (`pdftoppm -r 200`) and passed through Tesseract OCR (`rus+eng`, downloaded
`tessdata_fast` model since only `eng` ships on this machine) rather than reading each page image
individually — a faster path to the same underlying text a manual vision-read would produce, since
Tesseract's raw output was cross-checked word-by-word against the parallel English translation the
book itself provides for every dialogue line and against my own knowledge of Russian, not trusted
blind. **New gotcha confirmed and worth flagging for any future OCR-based (as opposed to purely
photographic vision-reading) pass on a Russian source:** this book prints an acute stress-accent
mark over each word's stressed vowel (a pedagogical convention, not the letter ё), and Tesseract
frequently misreads an accented о as the actual Cyrillic letter **б** and an accented е as **ё**
(e.g. "города" OCRs as "гброда"; "время" OCRs as "врёмя", which happens to coincide with a
correctly-decoded ё elsewhere — the two are visually indistinguishable in the OCR output and must
be disambiguated by knowing the real word). All Cyrillic in this file has been corrected by hand
against the real Russian word; **Vision Reading Confidence is marked `verified` only where the
English parallel translation or clear dictionary knowledge confirms the reading, `plausible_unverified`
elsewhere** — no entry here relies on raw uncorrected OCR output.

**Coverage note — non-redundant-supplement scoping applied to vocabulary as well as grammar.**
This is book #20 of Russian's Phase 1 corpus and the first genuinely *advanced*-level dialogue
course; its 20 lessons are structured identically (А. Диалог / В. Примечания / С. Грамматика и
словоупотребление / D. Идиоматика / E. Строго по делу [business vocabulary] / Упражнения). Given
how much overlap this project's ~30 prior Russian sources already have with everyday dialogue
vocabulary (airports, hotels, apartments, food, etc.), this file does **not** re-tabulate common
concrete nouns already extracted many times over (чемодан, дверь, гостиница, окно, etc.). It
**does** fully capture: (1) the Идиоматика (idiomatic-usage) sections — small, curated, and
genuinely register-focused; (2) the Строго по делу (business/thematic) sections — dense
domain-specific vocabulary unlikely to be duplicated; (3) register/usage distinctions flagged in
Примечания (e.g. near-synonym discrimination, colloquial vs. formal forms, sociolinguistic asides);
(4) grammar points not already thoroughly covered elsewhere in this corpus, noting explicitly where
a grammar point is skipped as redundant with prior sources (esp. Timberlake's *A Reference Grammar
of Russian*, Wade's *A Comprehensive Russian Grammar*, and Offord & Gogolitsyna's *Using Russian: A
Guide to Contemporary Usage*, the corpus's register-flagship source).

No handwritten marginalia found in the sampled page images (clean scan).

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| рейс | flight (a specific flight number/route) | noun | core | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | Lesson 1, Note 1: distinguished from полёт (any act of flying) — Начинается посадка на рейс № 549 (Flight No. 549 is now boarding) vs. Наш полёт был спокойным (our flight was smooth) |
| полёт | flight (the act of flying) | noun | core | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | See рейс above; near-synonym discrimination |
| С приездом! | Welcome! (to someone arriving) | interjection/idiom | colloquial | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | Lesson 1, Note 13: colloquial shortened form of "Поздравляю вас с приездом!" (lit. I congratulate you on your arrival), used to greet arriving friends/relatives |
| Добро пожаловать! | Welcome! (more formal, to a place) | interjection/idiom | formal | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | Contrasted with С приездом! — used when someone arrives somewhere for the first time; register pair worth preserving for a synthesis project modeling formal/informal greeting splits |
| наличность | "dough," (cash) money | noun | colloquial | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | Lesson 1, Note 10, book's own gloss is "dough" — distinguished from неутральный "наличные (деньги)" (cash on hand) and "платить наличными" (to pay in cash) |
| техника | equipment/technology/technique/engineering (broad polysemous term) | noun | core | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | Lesson 1, Note 11: строительная техника (civil engineering), вычислительная техника (computer science), техника безопасности (safety rules); idiom Это дело техники (It's a matter of technique) |
| хватать/хватить | to suffice, be enough | verb (imperfective/perfective) | core | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | Lesson 1, Note 8; takes genitive object. Idiom: Этого мне ещё не хватало! ("That was the last straw!") |
| девушка | Miss (address form for a woman of any age in a service role) | noun | colloquial | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | Lesson 1, Note 7 — flight attendants, salespeople, waitresses; sociolinguistic address-form convention |
| супруг / супруга | spouse (husband / wife, formal register) | noun | formal | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | Lesson 1, Note 9; plural супруги = "married couple." Formal register — contrasts with neutral муж/жена |
| отдавать/отдать | to give/hand over/turn in (root of several fixed idioms) | verb | core | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | Lesson 1, Note 14, fixed collocations: отдать себе отчёт (to realize), отдавать жизнь науке (to devote one's life to), отдать под суд (to prosecute), отдавать честь (to salute), отдавать должное (to give someone credit/due) |
| останавливаться/остановиться | to stay (lodging), lit. to stop oneself | verb (reflexive) | core | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | Lesson 1, Note 15 |
| везти (impersonal) | to be lucky/have luck go one's way | verb (impersonal, 3rd person only) | core | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | Lesson 1, Note 17: affected person in dative — Ему всегда везёт (He's always lucky), Нам повезло (We were lucky) |
| Скольколет, сколько зим! | Long time no see! | idiom | colloquial | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | Lesson 1, D. Idiomatika greeting set; lit. "How many summers, how many winters!" |
| Салют! | Hi!/Bye! | interjection | colloquial | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | Book itself notes it is functionally like Italian "Ciao" (works for both hello and goodbye) |
| Счастливо! | Take care! | interjection | colloquial | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | Shortened from "счастливо оставаться" (lit. "stay lucky") per book's own footnote |
| Счастливого пути! | Bon voyage! | idiom | core | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | — |
| До скорого! | See you soon! | idiom | colloquial | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | Shortened from "до скорого свидания" |
| глава / пьяница / коллега / судья | head, chief / drunkard / colleague / judge (common-gender nouns) | noun (common gender) | core | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | Lesson 1 grammar §3: nouns that can denote either a male or female referent without changing form |
| писатель / писательница | writer (masc. default / explicit feminine) | noun | core / colloquial (fem. form) | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | Flagship sociolinguistic finding: book's own footnote states the explicit feminine forms писательница, журналистка, and (to a lesser extent) секретарша are "considered less prestigious" than using the grammatically-masculine profession noun for a woman — a genuine, source-marked register asymmetry worth carrying into any register-mapping for the target conlang |
| виноград, морковь, изюм, капуста, картофель, лук | grapes, carrots, raisins, cabbage, potatoes, onions | noun (singularia tantum) | core | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | Lesson 1 grammar §3: fruit/vegetable nouns used only in the singular in Russian |
| сосна, вишня, берёза, клубника | pine (tree), cherry (tree), birch (tree), strawberry/-ies | noun (singularia tantum, mass/collective) | core | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | Whole tree/plant species rendered as singular-only nouns |
| джинсы, очки, брюки, ножницы, трусики, консервы, духи, деньги, волосы, будни | jeans, glasses, trousers, scissors, briefs, preserves, perfume, money, hair, weekdays | noun (pluralia tantum) | core | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | Lesson 1 grammar §3 pluralia-tantum list — objects with multiple components pattern as plural-only |
| природные ресурсы | natural resources | noun phrase | technical | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | Lesson 1, Строго по делу (Geography and Economy) |
| современная рыночная экономика | modern market economy | noun phrase | technical | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | — |
| фонды капиталовложений | investment funds | noun phrase | technical | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | — |
| решения по снижению себестоимости продукции | cost-cutting decisions | noun phrase | technical | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | — |
| неспособность по собираемости налогов | inability to collect taxes | noun phrase | technical | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | — |
| налоги с доходов предприятий | corporate (income) taxes | noun phrase | technical | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | — |
| гиперинфляция | runaway inflation, hyperinflation | noun | technical | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | — |
| утечка капитала за границу | capital flight abroad | noun phrase | technical | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | — |
| ухудшение состояния зданий и оборудования | deterioration of physical plant(s) | noun phrase | technical | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | — |
| ледоколы | icebreakers | noun | technical | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | Lesson 1 geography section, re: Vladivostok's port kept open year-round |
| тайга / тундра / вечная мерзлота | taiga (boreal forest) / tundra / permafrost | noun | technical | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | Physical-geography terminology from the Строго по делу section |
| жаловаться | to complain | verb | core | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | Lesson 2, Идиоматика "Complaining" set |
| подать жалобу | to file a complaint | idiom (verb phrase) | formal | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | Same set — register step up from жаловаться, used for formal grievances (e.g. "с дирекцию гостиницы") |
| быть в претензии (на кого-то) | to hold a grudge (against someone) | idiom | core | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | Same set |
| ворчать | to gripe, grumble | verb | colloquial | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | Same set |
| нытьё | whining | noun | colloquial | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | Same set — abstract noun from ныть (to whine) |
| капать на мозги | to pester, nag (someone) | idiom | slang | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | Book's own gloss: lit. "to drip water on someone's brains" — vivid, register-marked idiom, genuinely colorful and worth flagging as slang-mechanics-relevant (bodily/liquid metaphor for annoyance) |
| плакаться в жилетку | to cry on someone's shoulder | idiom | colloquial | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | Lit. "to cry into someone's vest" — book itself flags this as a Russian-specific image contrasting with the English "shoulder" idiom, i.e. a genuine cross-linguistic idiom-mapping mismatch worth preserving for conlang idiom design |
| Сталинский дом (Дом СТАЛИН) | "Stalin-era building" — a spacious prewar/Stalin-period apartment building with high ceilings | noun phrase (real-estate jargon) | slang | — | contemporary (source published 1998/2003; refers to 1930s-50s construction) | Russia | national | grammar_reference | n/a | verified | Lesson 3, Строго по делу real-estate jargon list — explicitly labeled by the book as "colloquial terms that have become standard" in real-estate listings; abbreviated in ads as "Дом СТАЛИН" |
| Хрущёвский дом (Дом ХРУЩ) | "Khrushchev-era building" — a cheap 5-story walk-up apartment block (no elevator/garbage chute), 4 units/floor | noun phrase (real-estate jargon) | slang | — | contemporary (source published 1998/2003; refers to 1950s-60s mass housing) | Russia | national | grammar_reference | n/a | verified | Same list — named after Khrushchev-era mass housing construction; a genuine era-specific coinage tied to Soviet housing policy, high value for a conlang's own "housing-era slang" layer |
| Блочный дом (Дом БЛОЧ) | a block-built apartment complex (prefab concrete panel construction) | noun phrase (real-estate jargon) | slang | — | contemporary (source published 1998/2003) | Russia | national | grammar_reference | n/a | verified | Same list |
| домофон | door intercom (video/audio) | noun | core | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | Same list |
| советский ремонт | "Soviet finish" — wallpapered interior (as opposed to painted walls) | noun phrase (real-estate jargon) | slang | — | contemporary (source published 1998/2003) | Russia | national | grammar_reference | n/a | verified | Contrasted with западный ремонт ("Western finish" = painted walls) — a genuine East/West-coded register pair in Russian real-estate slang, directly useful for a conlang's own core/foreign-coded vocabulary split |
| западный ремонт | "Western finish" — painted-wall interior, associated with foreign/renovated standard | noun phrase (real-estate jargon) | slang | — | contemporary (source published 1998/2003) | Russia | national | grammar_reference | n/a | verified | See советский ремонт above |
| кодовый подъезд | a building entrance with a keypad/coded lock | noun phrase (real-estate jargon) | slang | — | contemporary (source published 1998/2003) | Russia | national | grammar_reference | n/a | verified | — |
| раздельный санузел (с/у разд.) | separate toilet and bathroom (as opposed to combined) | noun phrase (real-estate jargon, abbreviation) | slang | — | contemporary (source published 1998/2003) | Russia | national | grammar_reference | n/a | verified | Book gives the standard listing abbreviation "с/у разд." |
| СВЧ-печь / микроволновка | microwave oven (formal / slang term) | noun | core / slang | — | contemporary (source published 1998/2003) | Russia | national | grammar_reference | n/a | verified | Book explicitly calls микроволновка "another slang expression for a microwave oven" — direct, source-marked formal/slang lexical doublet |
| набраться (colloquial sense) | to get dead drunk | verb (reflexive, colloquial) | slang | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | Lesson 3, Note 2 — book explicitly flags this as "very colloquial"; base verb набрать/набирать (to dial/gain/gather) extended metaphorically to intoxication, a genuine polysemy chain (dial→gain speed/altitude/points→gain strength/wisdom→get drunk) worth modeling for conlang semantic-extension patterns |
| вы не туда попали | you've got the wrong number (lit. "you've fallen/landed in the wrong place") | idiom | core | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | Lesson 3, Note 3 — verb попасть extends to попасть на работу (land a job), попасть под дождь (get caught in the rain), попасть под суд (be brought to trial) |
| вешать трубку / класть трубку / бросать трубку | to hang up the phone (neutral / neutral / to slam down) | verb phrase (idiom set) | core / core / colloquial (emphatic) | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | Lesson 3, Note 4 — three-way register-graded synonym set for the same action, escalating in emphasis |
| я вас слушаю | "I'm listening" — standard telephone self-identification response | idiom | formal | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | Lesson 3, Note 5 |
| созвонимся | "we'll be in touch (by phone)" | idiom | colloquial | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | Lesson 3, Идиоматика "Making Phone Calls" — closing formula |
| разъединение связи | (phone) disconnection | noun phrase | technical | — | contemporary (source published 1998/2003) | — | — | grammar_reference | n/a | verified | Lesson 3, Строго по делу framing of the domestic phone system's chronic reliability problems |
| жетон (телефонный) | (phone booth) token | noun | core | — | contemporary (source published 1998/2003; pre-cellphone-era technology) | Russia | national | grammar_reference | n/a | verified | Public phone booths required a purchased token, sold at kiosks/newsstands — dated infrastructure-specific vocabulary |

## Grammar points

### 1. Present tense of 1st/2nd conjugation verbs (Lesson 1, §C.1)

**Skipped as redundant** with dozens of prior corpus sources' fuller treatments (e.g. Timberlake,
Wade, Szczepanska). Book's own contribution worth a one-line note: it explicitly uses the present
tense to translate an English "has/have been -ing" construction when the action began in the past
and continues (Сколько лет вы уже живёте в Москве? — "How long have you been living in Moscow?"),
paired with an aspectual framing not always spelled out this explicitly in beginner sources.

### 2–3. Nominative case; nominative noun endings/gender (Lesson 1, §C.2–3)

**Largely redundant** with prior full paradigm tables in this corpus. Two genuinely useful
consolidations kept above in Vocabulary: the common-gender noun set (глава, пьяница, коллега,
судья) and the singularia/pluralia tantum lists, plus the writer/writer(fem.) prestige-asymmetry
sociolinguistic note, none of which needed repeating from this specific angle in prior sources.

### Идиоматика: Hellos and Good-byes (Lesson 1, §D)

A short curated set of formality-graded greetings/farewells, captured in full above (Vocabulary) —
genuinely new content (this specific curated register-graded set doesn't duplicate any prior
source's greeting list in this corpus).

### Lesson 2 grammar (§C): Genitive case; Telling time; The Calendar

**Skipped as redundant** — standard genitive-case endings and cardinal-number-governed
case-selection rules (1 vs. 2-4 vs. 5+) already fully tabulated by multiple prior sources (e.g.
Timberlake, Szczepanska, Schaum's Outline). Telling-time and calendar-date constructions
(nominative for current hour/date, genitive for "at/on" a date or "past the hour," dative + к for
"by" a deadline, genitive plural час for 5+, special terms четверть/пол/полдень/полночь) are
likewise standard and not re-tabulated, though the systematic dative-"by X o'clock" and genitive-
"from...to" prepositional pairing (с...до vs. с...по, the latter being inclusive of the end point)
is a clean, fully worked contrast worth a one-line flag for any future case-usage cross-reference.

### Lesson 2 Идиоматика: Complaining

Fully captured above (Vocabulary) — a compact, register-graded escalation ladder from neutral
жаловаться (to complain) through formal подать жалобу (to file a complaint) to colloquial/vivid
ворчать, нытьё, капать на мозги, and плакаться в жилетку. The last two are genuinely
slang-mechanics-relevant (metaphor-based idioms), and плакаться в жилетку is explicitly flagged by
the book as diverging from the English "cry on someone's shoulder" image (Russian uses "vest").

### Lesson 2 Строго по делу: Business Facilities; Telecommunications

Mostly compositional business-technical noun phrases (услуги телесвязи, конференц-залы,
бизнес-центры, обмен валюты) and a long list of real-1990s telecom joint-venture/company names
(МГТС, Ростелеком, Rosnet, сотовая связь, волоконно-оптическая сеть) — a period-piece snapshot of
post-Soviet telecom liberalization rather than durable core vocabulary. Not individually tabulated;
representative sample only per the non-redundant-supplement scoping above, since these are
transparent technical compounds without independent register interest.

### Lesson 3 grammar (§C): Dative case; Negation

Dative-case endings and the standard list of dative-governing verbs (помогать, советовать,
сообщать, рекомендовать, отвечать, верить, завидовать) and prepositions (к, по, благодаря,
вопреки) are **largely redundant** with prior sources. **One genuinely useful consolidation kept
here:** the full negative-pronoun declension table (ничто/никто/никакой/ничей across all six
cases, including the "preposition splits the ни- prefix from the pronoun" rule — ни о чём, ни с
кем) is a clean, fully-worked paradigm not seen tabulated this completely in several prior
grammar-only sources in this corpus.

| Case | nothing | no one | none (whatever) | nobody's |
|---|---|---|---|---|
| Nom. | ничто | никто | никакой | ничей |
| Gen. | ничего | никого | никакого | ничьего |
| Dat. | ничему | никому | никакому | ничьему |
| Acc. | ничто | никого | никакой/ничего | ничей/ничьего |
| Instr. | ни с чем | ни с кем | ни с каким | ни с чьим |
| Prep. | ни о чём | ни о ком | ни о каком | ни о чьём |

Also notable: Russian permits (in fact requires) multiple co-occurring negatives in one clause
(Мы никогда нигде ни с кем не хотели встречаться — "We never wanted to meet with anyone
anywhere"), unlike English's single-negation rule — a genuine typological point worth flagging for
any negation-marking design in the derived conlang.

### Lesson 3 Идиоматика: Making Phone Calls

Fully captured above (Vocabulary) — telephone-etiquette formulas for placing a call, answering,
handling a bad connection, and ending a conversation (Хас прервали — "We got cut off"; Плохо
слышно — "Bad connection"; Созвонимся — "We'll be in touch").

### Lesson 3 Строго по делу: Недвижимость (Real Estate)

**Flagship find of these three lessons.** The book explicitly frames a block of terms as
"colloquial terms that have become standard for describing rental property" in real-estate
listings — captured in full above (Vocabulary): Сталинский/Хрущёвский/Блочный дом (era-coded
housing-type slang tied directly to Soviet housing-construction history), советский vs. западный
ремонт (an East/West-coded finish-quality register pair), and микроволновка as an explicitly
source-labeled slang doublet for СВЧ-печь. This is exactly the kind of "housing generation ↔
lexical coinage" mechanism (a named historical period yielding a durable common noun) that the
project's slang-mechanics analysis phase will want as a template.

---

**Known gap carried forward:** none yet — this file covers Lessons 1–3 in full per the coverage
rule above; Lessons 4 onward continue in `076b_ultimate_russian_advanced.md` and further
lettered siblings.
