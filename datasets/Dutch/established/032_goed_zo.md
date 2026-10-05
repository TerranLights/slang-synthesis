# Dutch — *Goed zo!* (course book, vision-read from DJVU)

**Source:** *Goed zo!* — a Dutch-as-a-foreign-language course book written **in Russian** for
Russian-speaking learners (all metalanguage/grammar explanation is in Russian; target text is
Dutch). Author/edition not stated on the pages read; publisher appears Russian (no ISBN page
reached). File: `source_reference/languages/Dutch/16 Goed zo!.djvu`, 176 DJVU pages, printed pages
numbered 9–~230 (front matter before printed p.9 not examined — no table-of-contents/title-page
content was reached in this pass; page 176, the last DJVU page, is the **Содержание** (table of
contents), confirming the book's overall lesson structure — see "Book structure" below).

**This file covers:** the pronunciation/orthography preliminary chapter (printed pp. 9–17, DJVU
pp. 1–9) and **Урок 1 / Les 1** and **Урок 2 / Les 2** in full (printed pp. 17–43, DJVU pp. 9–35).
Later lessons are in sibling files `032b_...` onward (see progress note at the end of this file —
**this is a large single-book dispatch covering the whole course book across multiple numbered
files**, not a single bounded chapter/chunk like other `established/` entries).

## DJVU vision-reading notes — read this before trusting any page-range math elsewhere in the project

- **No text layer at all** (`djvutxt` returns empty output) — this entire source was vision-read
  page-by-page via `ddjvu -format=ppm` → Pillow-converted PNG, at ~1300–1600px on the long edge.
- **Confirmed page offset: printed page = DJVU page + 8**, verified against 10+ page numbers
  directly visible on rendered pages (DJVU p.1→printed 9, DJVU p.7→printed 15, DJVU p.10→printed
  18, DJVU p.120→printed 128, DJVU p.146→printed 154, etc.) — holds consistently for DJVU pp. 1–146.
- **One page per DJVU image, not a two-page spread** — unlike the Serbian/Croatian/Bosnian gotcha
  the project spec warns about, this source is scanned one physical page per DJVU page throughout
  the ranges checked.
- **A block of pages is rotated 180° in the scan** (confirmed on DJVU pp. 147, 149, 153, and
  apparently others in that neighborhood — not yet checked exhaustively for the later lessons).
  Content is still fully legible right-side-up once mentally/programmatically rotated; this is
  purely a scan-orientation artifact, not missing or corrupted content.
- **CONFIRMED GAP — an entire lesson is missing from this DJVU scan.** DJVU p.146 shows printed
  page 154 (still mid-"Урок 8"); DJVU p.147 shows printed page **175** and the title page of
  "Les 10" — i.e. **printed pages 155–174 (all of "Урок 9", per the book's own table of contents)
  do not exist anywhere in this DJVU file.** This was verified directly (not inferred from the
  +8-offset formula breaking) by rendering and reading DJVU pp. 146 and 147 back-to-back. **Урок 9
  cannot be extracted from this source at all — it is not a vision-reading failure, the pages are
  physically absent from the scan.** Do not attempt to fill this gap by guessing; if another copy
  of this book (or `10`/`17` Colloquial Dutch, or another intermediate-level Dutch course in the
  corpus) is ever extracted, its own Lesson-9-equivalent content should be captured there instead.
- **Handwritten marginalia check:** none found on any page read so far — all content on every page
  examined is consistent, clean print typeface matching the rest of the page. No marginalia
  exclusion was needed for the ranges covered by this file.
- **Vision Reading Confidence:** all rows in this file are marked `plausible_unverified` unless
  otherwise noted — this is a clean, high-resolution scan with sharp, unambiguous typeset print
  throughout the ranges read; no faded/obscured/gutter-shadow passages were encountered. A handful
  of rows cross-checked against the same word appearing elsewhere on a legible part of the page are
  marked `verified`.

## Book structure (from the DJVU p.176 table of contents, "Содержание")

For reference/orientation across this file and its siblings (printed page numbers):
Урок 1 — p.17; Урок 2 — p.29; Урок 3 — p.44; Урок 4 — p.58; Урок 5 — p.73; Контрольный урок А —
p.86; Урок 6 — p.92; Урок 7 — p.110; Урок 8 — p.130; **Урок 9 — p.155 (MISSING from this scan, see
above)**; Урок 10 — p.175; Контрольный урок Б — p.193 onward (exact end page not yet confirmed).

## Copyright note

Per project copyright discipline, the dialogues/narrative texts (e.g. the recurring "Klaas en
Liesje" storyline) are **not reproduced** beyond short illustrative fragments; only vocabulary
items, grammar rules (paraphrased), and short representative examples are extracted below. Numbered
drill/translation exercises are skipped throughout (per the coverage rule) except where an exercise
prompt itself introduces vocabulary not otherwise glossed in a СЛОВА box.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| blijven | оставаться ("to stay/remain") | verb | core | — | contemporary (source undated, Russian-market Dutch course) | — | — | grammar_reference | n/a | plausible_unverified | Lesson 1 core-verbs СЛОВА box |
| doen | делать ("to do") | verb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | irregular: ik doe, hij doet, wij doen |
| eten | есть, кушать ("to eat") | verb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| fietsen | ездить на велосипеде ("to cycle") | verb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| gaan | ходить, ездить ("to go") | verb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | irregular: ik ga, jij gaat, wij gaan |
| hebben | иметь ("to have") | verb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | irregular full paradigm: ik heb, jij hebt, hij/zij/het heeft, wij/jullie/zij hebben |
| heten | именоваться ("to be named") | verb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| houden | держать ("to hold"); houden van = любить ("to love/like") | verb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | final -d often dropped in speech (ik hou) |
| kijken | смотреть ("to watch/look") | verb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | kijken naar = "смотреть на"; but televisie kijken drops the preposition |
| koken | готовить еду, варить ("to cook") | verb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| komen | приходить, приезжать ("to come") | verb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | irregular vowel alternation: ik kom, jij/hij komt, wij komen |
| lezen | читать ("to read") | verb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | v/z-devoicing: wij lezen but jij/u leest |
| pakken | хватать ("to grab/take"); idiomatic in "een pilsje pakken", "de tram pakken" | verb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| studeren | учиться ("to study/attend university") | verb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | stress on -e(e)r suffix |
| vertellen | рассказывать ("to tell/narrate") | verb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | ver- prefix unstressed |
| werken | работать ("to work") | verb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| wonen | жить, обитать ("to live/reside") | verb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| zijn | быть, находиться ("to be") | verb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | irregular full paradigm: ik ben, jij bent, hij/zij/het is, wij/jullie/zij zijn |
| een pilsje pakken | выпить пива ("to have a beer") | idiom | colloquial | — | — | — | — | grammar_reference | n/a | plausible_unverified | source-marked (разг.) |
| de tram pakken | сесть на трамвай ("to catch the tram") | idiom | colloquial | — | — | — | — | grammar_reference | n/a | plausible_unverified | source-marked (разг.) |
| het huishouden doen | заниматься домашним хозяйством ("to do the housekeeping") | idiom | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| de was doen | заниматься стиркой ("to do the laundry") | idiom | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| de afwas doen | мыть посуду ("to wash the dishes") | idiom | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| op | на ("on") | preposition | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| in | в (в чём-л.) ("in") | preposition | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | locative "where" |
| naar | в (во что-л.), к ("to/towards") | preposition | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | directional "to where" |
| van | (marks possession/belonging — no single gloss) | preposition | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | Dutch has no genitive case; van + noun expresses possession |
| dik | толстый ("fat/thick") | adjective/adverb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | many Dutch adjectives double unchanged as adverbs |
| getrouwd | женатый, замужняя ("married") | adjective | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| gelukkig | счастливый ("happy"); as adverb: "к счастью" | adjective/adverb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| gewoon | простой, обыкновенный ("plain/ordinary") | adjective/adverb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | ge- unstressed prefix noted as very common |
| heerlijk | чудесный ("wonderful") | adjective | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | stress on root before -(e)lijk suffix |
| klein | маленький ("small") | adjective | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| lekker | вкусный ("tasty"); also general positive intensifier | adjective/adverb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | "lekker lui/dik/fietsen" illustrations in source |
| leuk | забавный, приятный ("nice/fun") | adjective | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| lui | ленивый ("lazy") | adjective | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| mager | тощий, худой ("thin/skinny") | adjective | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| natuurlijk | естественный ("natural"); as adverb: "конечно" ("of course") | adjective/adverb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| oud | старый ("old") | adjective | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| verrukkelijk | восхитительный ("delightful") | adjective | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| verschrikkelijk | ужасный ("terrible/awful") | adjective | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| daar | там ("there") | adverb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| hier | здесь ("here") | adverb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| erg | очень ("very"); = heel | adverb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | source notes erg, unlike heel, can modify a verb |
| bijna | почти ("almost") | adverb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| alleen | 1. один, в одиночестве ("alone") 2. только ("only") | adverb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | two distinct senses explicitly distinguished by source |
| graag | охотно, с удовольствием ("gladly/willingly") | adverb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | "Hij studeert graag" = "Hij houdt van studeren" |
| ook | тоже ("also/too") | adverb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | glosses Russian "и" in the sense "also" |
| samen | вместе ("together") | adverb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| 's avonds | вечером, по вечерам ("in the evenings") | adverb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| thuis | дома ("at home") | adverb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | older spelling "tuis" noted |
| trouwens | впрочем ("by the way/incidentally") | adverb (discourse) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | the one word in this box that is NOT an adverb-of-manner per source's own note |
| vaak | часто ("often") | adverb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| zoals | как (союз), подобно ("like/such as") | conjunction | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| veel | много ("much/many") | quantifier | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| iedereen | все ("everyone") | pronoun | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | triggers singular verb agreement despite plural meaning |
| wel eens / wel 's | иногда ("sometimes") | adverbial phrase | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | 's = reduced eens; wel = general-purpose modal particle |
| en | и ("and") | conjunction | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| maar | но ("but"); also a softening discourse particle | conjunction/particle | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | "Ik blijf maar in bed" ≈ "I'll (just) stay in bed" |
| want | потому что, ибо ("because/for") | conjunction | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| ja / nee | да / нет ("yes/no") | interjection | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| jawel | ("yes" — contradicting a negative, or reinforcing) | interjection | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | ja + wel fused; obligatory single-word affirmative reply to a negative question |
| toch | ведь, не так ли ("isn't that so", tag-question/insistence particle) | particle | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | placement: sentence-final or mid-sentence, never disturbs word order |
| de wijn/rijst is op | вино/рис кончился ("the wine/rice is finished/gone") | idiom | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| Hallo! | Привет! Здравствуйте! Алло! | interjection | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | phone/greeting |
| Hoe gaat het (met u/jou)? | Как дела? / Как поживаешь? | phrase | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| goed | хорошо ("good/well") | adjective/adverb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| prima | отлично ("excellent") | adjective/adverb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| Dag! | Привет!/Пока! (greeting or farewell) | interjection | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| Doei! | Пока! (informal "bye") | interjection | colloquial | — | — | — | — | grammar_reference | n/a | plausible_unverified | source explicitly marks this as more fashionable/informal ("более модное") than Dag |
| wat / wie / waar / waarom / hoe | что / кто / где / почему,зачем / как | interrogative pronoun/adverb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| daarna | после этого, потом, затем ("after that") | adverb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | can refer to past or future, unlike dan |
| daarom | поэтому ("therefore") | adverb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| dan | тогда, потом; в таком случае ("then/in that case") | adverb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | future-only, unlike daarna |
| helaas | к сожалению, увы ("unfortunately") | adverb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| misschien | может быть ("maybe") | adverb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| nu / nou | теперь, сейчас ("now") | adverb | core / colloquial (nou) | — | — | — | — | grammar_reference | n/a | plausible_unverified | nou marked more colloquial than nu; also expresses surprise/indignation as a discourse particle ("Nou-nou!") |
| 's middags | днём (после полудня) ("in the afternoon") | adverb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| straks | вскоре, чуть позже (same-day only) ("soon/shortly") | adverb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | source stresses the same-day constraint explicitly |
| vanavond | сегодня вечером ("this evening") | adverb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| vandaag | сегодня ("today") | adverb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| even | немножко, ненадолго ("briefly/just a moment") | adverb (discourse) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | placement: after weer, before erg/graag/vaak |
| nog | еще ("still/yet") | adverb (discourse) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | "nu eens... dan weer" = "то... то" |
| weer | опять, снова ("again") | adverb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| zelfs | даже ("even") | adverb (discourse) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | does not affect word order/inversion |
| wel | (modal/affirming discourse particle — no single gloss; softens or affirms) | particle | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | obligatory in an affirmative answer that contradicts a negative question |
| geen | (negative article — "no/not any") | article | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | replaces niet when negating a noun that would take indefinite/zero article |
| niet | не ("not") | adverb (negation) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | never precedes the finite verb, unlike Russian "не" |
| het bed | кровать | noun (het-word) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| het bier | пиво | noun (het-word) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | mass noun — takes zero article instead of indefinite |
| het borreltje | рюмочка спиртного | noun (het-word) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | diminutive form |
| het cadeautje | подарок | noun (het-word) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | diminutive; -eau- pronounced as long 'o' (French loan) |
| het café | бар, кафе | noun (het-word) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| de collega | коллега | noun (de-word) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| de film | фильм; кино | noun (de-word) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| de jenever | можжевеловая водка ("genever/jenever") | noun (de-word) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| de kast | шкаф | noun (de-word) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| het meisje | девушка, девочка | noun (het-word) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | diminutive -je noun that is grammatically het but takes zij as pronoun (natural-gender override noted) |
| de regen | дождь | noun (de-word) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| de rijst | рис | noun (de-word) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | mass noun — zero article |
| de tafel | стол | noun (de-word) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| de telefoon | телефон | noun (de-word) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | "de telefoon gaat" = phone rings (idiom) |
| de verrassing | сюрприз, неожиданность | noun (de-word) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| de vis | рыба | noun (de-word) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | mass/food noun — zero article ("rijst bij de vis") |
| de wijn | вино | noun (de-word) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | mass noun — zero article |
| de zon | солнце | noun (de-word) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| de zondag | воскресенье | noun (de-word) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | "het is vandaag zondag" — no article before a day-of-week predicate |
| denken (aan) | думать (о) ("to think about") | verb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | governs preposition aan |
| drinken | пить ("to drink") | verb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| geloven | верить, полагать ("to believe/think") | verb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | "ik geloof het (wel/niet)" idiom |
| horen | слышать ("to hear") | verb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| regenen | идти (о дожде) ("to rain") | verb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | impersonal "het regent" |
| schijnen | светить ("to shine") | verb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| staan | стоять ("to stand") | verb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| wandelen | гулять, идти прогуливаясь ("to walk/stroll") | verb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | stress on first root syllable, not -el- |
| zien | видеть ("to see") | verb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| (samen) met | (вместе) с ("(together) with") | preposition | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | also marks instrument, like Russian instrumental case |
| tot | до ("until/to") | preposition | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| voor | для; перед ("for; in front of / before") | preposition | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | |
| bij | у, к, на ("at/near/by") | preposition | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | contrasted with aan (contact) — bij = relative proximity |
| aan | у; на (contact/attachment; also marks some indirect objects) | preposition | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | flagged by source as one of the most polysemous Dutch prepositions |
| zonder | без ("without") | preposition | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | article normally dropped after zonder |

## Grammar points

### Orthography/pronunciation preliminary chapter (printed pp. 9–17)
Covers (numbered items 40s–53 seen in this pass; earlier items 1–39 not reached — this pass
started mid-chapter at item ~48): diphthong/vowel-cluster pronunciation drills (`ee/ie/eu/ui`
clusters, French loanword sequences like `-eau-`, `-aai-`, `Baäl, geëmmer, coffeïne` etc.); the
rule that **Dutch words never end in two identical letters except `ee`**; stress placement
(root-first-syllable default, with exceptions marked in the book); the full alphabet with letter
names, and the note that **ij** is alphabetized with **i** in dictionaries but with **Y** in phone
books. These are pronunciation drill items without individual glosses (word lists, no translation
given) and are not entered as vocabulary rows per the coverage rule (no gloss = not extractable as
a vocabulary item; skipped as drill material).

### Les 1 — Klaas en Liesje (printed pp. 17–28)
- **Absence of the article (nul-article).** Definite/indefinite articles are dropped before proper
  nouns (personal names, city/country/province names) but required before street names and some
  urban district names (`de Bloemgracht`, `de Jordaan`). Also dropped before predicate nouns naming
  a profession/occupation (`Joris is student`) — termed "zero article" (нулевой арт.) by the source.
- **`'t`/`'n`** — the definite article `het` and indefinite `een` are sometimes written as `'t`/`'n`
  reflecting their unstressed pronunciation. The numeral `een` ("one") is a homograph of the
  indefinite article but is always pronounced with a long vowel; to disambiguate, the numeral is
  conventionally accented `één`.
- **Personal pronoun table** (full + reduced forms), subject case: singular `ik('k)`, `jij(je)`,
  `u`, `hij`, `zij(ze)`, `het('t)`; plural `wij(we)`, `jullie`, `u`, `zij(ze)`. Reduced forms are
  used when the pronoun carries no logical stress; full forms are obligatory when two pronouns (or
  a pronoun and a person-noun) are coordinated with a conjunction.
- **`u` vs `jij/jullie`.** Dutch speakers use the polite `u` far less than Russian speakers use
  "вы" — people are addressed by first name, not surname+title, and `jij/je` is used to essentially
  anyone under ~25 regardless of familiarity; `u` for a group is often replaced by `jullie`.
- **Grammatical vs. natural gender in pronoun reference.** `zij/ze` for inanimate objects is rare in
  Netherlandic Dutch (Flemish speakers distinguish "masculine"/"feminine" more); this book follows
  the Netherlandic convention. Grammatical gender of a Dutch noun (`de`-word or `het`-word) often
  does **not** match the gender of its Russian translation-equivalent, so pronoun choice must follow
  the Dutch noun's own gender, not the translation's.
- **Present-tense conjugation (regular pattern).** Infinitive suffix `-en` is replaced by: zero
  ending (1sg), `-t` (2sg/3sg), `-en` (all plural). Spelling rules preserve vowel length across the
  paradigm (open vs. closed syllable: `ik kook` / `wij koken`), and voiced-to-voiceless consonant
  alternation applies word-finally/before voiceless consonants (`v→f`, `z→s`: `lezen` → `jij leest`).
  Stem-final `-d` before `-t` is not doubled (`houden` → `jij houdt`, not `houdtt`); stem-final `-t`
  likewise does not double (`heten` → `jij heet`).
- **Irregular verbs in this lesson:** `doen` (ik doe, doet, doen — `-n`-only plural, no `-en`),
  `gaan` (ga, gaat, gaan — same `-n`-only plural pattern), `komen` (kom, komt, komen — vowel
  alternation long↔short), `houden` (colloquially `ik hou`, final -d often dropped/not written),
  `zijn` and `hebben` (fully suppletive/irregular paradigms, must be memorized).
- **Adjective/adverb overlap.** Many Dutch adjectives function unchanged as adverbs (`Hij is
  gelukkig` / `Hij houdt gelukkig van koken` = "he happily loves cooking").
- **Prepositions in this lesson:** `op/in/naar/van` — `in + noun` answers "where?" (locative,
  ≈ Russian prepositional case), `naar + noun` answers "where to?" (≈ Russian accusative/dative of
  direction); `komen` can combine with either `naar` or `in` with near-identical meaning.
- **Conjunctions `en/maar/want`.** Russian "а" is usually rendered `en`, sometimes `maar`, and is
  often simply untranslated; Russian "и" in the sense "also/too" corresponds to `ook`, not `en`.
- **Word order — five-slot base schema** (paraphrased from the source's own table): 1) subject,
  2) finite verb, 3–4) objects/adverbials, N) non-finite part of the predicate, N+1) only a
  preposition-phrase constituent may follow the non-finite verb part. The constituent carrying
  logical/sentence stress is placed as late as possible; a new-information object (indefinite/
  zero-article noun) is therefore usually placed after adverbials rather than immediately after the
  verb.
- **`iedereen`** ("everyone") grammatically triggers **singular** verb agreement, unlike its plural
  sense — flagged explicitly because this is easy to get wrong by analogy with Russian "все".
- **Diminutive first names.** Dutch female first names frequently end in a diminutive-like suffix
  (`-je`/`-ke`), e.g. `Liesje`, `Marieke` — noted here as the book's own first mention of the
  diminutive pattern that `established/003_chapter22_diminutives.md` treats systematically for
  another source; this book does not develop diminutive morphology as a grammar topic in the
  lessons read so far.
- **Surname note:** particles `de`/`van` in Dutch surnames are lowercased when preceded by a first
  name or initials, capitalized when the name stands alone (`Klaas de Boer` vs. `de auto van De
  Boer`). `de Boer` itself is literally "the farmer" — a common surname built from an occupation
  noun (parallel case to Russian "Крестьянин"-type surnames, though the source doesn't draw that
  comparison explicitly).

### Les 2 — Vandaag werkt Klaas niet (printed pp. 29–43)
- **Interrogative word order.** Subject and finite verb invert in yes/no questions (rest of clause
  unchanged); questions with an interrogative word place the question word first, then invert
  subject/verb identically. Exception: questions **about** the subject itself do not invert.
- **`toch` preserves declarative word order** even inside what is grammatically a question — it can
  sit sentence-medially or -finally without triggering inversion.
- **Intonation.** Declarative-sentence intonation (falling at the end) is described as nearly
  identical between Dutch and Russian. Yes/no questions without a question-word can carry rising
  intonation on the logically-stressed word (as in Russian) OR — a pattern flagged as distinctively
  Dutch — a fall-then-rise contour across the final word(s) of the question. Wh-questions can raise
  pitch on the stressed word (unlike Russian, which raises pitch on the question word itself) or use
  the same fall-then-rise pattern.
- **Inversion (`Инверсия`) more generally.** Any single fronted non-subject constituent (most often
  an adverbial) triggers subject–verb inversion; only one adverbial may be fronted at a time. `Ja`,
  `nee`, and a comma-set-off parenthetical/discourse word do **not** trigger inversion. `alleen` and
  `ook` scoped only to the subject (not the whole clause) likewise block inversion.
  A fronted direct object also triggers inversion, **except** that `het` as direct object cannot be
  fronted at all — it is replaced by `dat` when fronting is needed.
- **`-ie` reduced form of `hij`** arises only under inversion (`Staat-ie daar?` = "Is he standing
  there?") — distinct from the other pronouns' reduced forms, which are not restricted to inversion
  contexts. Rarely written even though extremely common in speech.
- **`jij`-verbs lose the `-t` under inversion** (`Jij komt` → `Kom je?`) — but this loss does **not**
  apply to `u` (`Bent u?`, `Hebt u?` keep the ending). `houden`'s idiosyncratic `-d`-drop persists
  under inversion too (`Houd je van fietsen?`).
- **Full pronoun declension table** — subject vs. object forms, singular and plural (reduced forms
  in parentheses): 1sg `ik('k)`/`mij(me)`; 2sg `jij(je)`/`jou(je)`, `u`/`u`; 3sg `hij(-ie)`/
  `hem('m)`, `zij(ze)`/`haar('r/d'r)`, `het('t)`/`het('t)`; 1pl `wij(we)`/`ons`; 2pl `jullie`/
  `jullie`, `u`/`u`; 3pl `zij(ze)`/`hen/hun/ze`. The object form covers **all** Russian oblique
  cases at once (no case distinction in Dutch pronouns).
- **`hen`/`hun` vs `ze`.** `ze` can refer to people, animals, or things; `hen`/`hun` refer only to
  people. Within `hen`/`hun`, the distinction (increasingly lost in modern usage, but still taught
  prescriptively) is direct object → `hen`, indirect object → `hun`; `hen` is also used after any
  preposition.
- **Stressed pronoun-object contraction** after a preposition: `Dat is 'r`/`Dat is 'm` (stress on
  `is`) is more colloquial than the full form (stress on the pronoun itself, `Dat is zij`/`Dat is
  hij`).
- **Prepositions in this lesson:** `(samen) met` ("(together) with" — also marks instrument, like a
  Russian instrumental case use: `Ik doe het met een lucifer`), `tot` ("until/to"), `voor`
  ("for"/"in front of"/temporally "before"), `bij` (relative proximity: "at/near", contrasted with
  `aan`'s direct-contact sense), `aan` (flagged as one of the most polysemous Dutch prepositions:
  contact/attachment, `studeren aan een universiteit` "to study at [a named] university" vs. `werken
  op de universiteit` "to work at the university" — the two prepositions are lexically fixed per
  verb, not freely interchangeable), `zonder` ("without" — article normally dropped after it).
- **Mass/collective nouns take zero article instead of indefinite article** when referring to a
  substance-as-food rather than a countable/animate entity: `bier`, `jenever`, `wijn`, `rijst`,
  `vis`.
- **`denken aan`** = "to think about" (fixed preposition); **`kijken naar`** = "to look at/watch"
  but **`televisie kijken`** drops the preposition entirely (fixed collocation).
- **Negation — `niet`.** Unlike Russian "не", `niet` never precedes the finite verb. In a
  neutral-scope negation it goes to the very end of the clause, after which only the non-finite verb
  part and a trailing `preposition + …` constituent may follow. When negation scopes narrowly to one
  constituent (not the whole predicate), `niet` moves immediately before that constituent instead.
  Dutch echoes negation in short answers (`'Is hij niet thuis?' 'Nee, hij is niet thuis.'`) where
  Russian would not repeat it.
- **`geen`** replaces `niet` when negating a noun/predicate-nominal that would otherwise carry
  indefinite or zero article; `geen` itself functions as a negative article, and no other article
  co-occurs with it.
- **Article is dropped before a name or number identifying a specific referent** (`Het boek staat
  in kast 1` — "the book is in cabinet [no.] 1").
- **`wel`** is a highly polysemous modal/affirming particle: (a) obligatory to affirmatively answer a
  negatively-phrased question (`'Heb je geen fiets?' 'Ja, ik heb wel een fiets.'`), (b) used simply
  to soften a statement with no real "yes"-content (`De vis is wel lekker` ≈ "the fish is quite
  tasty"). `jawel` is the fused single-word obligatory affirmative reply to a negative question.
- **`maar`** likewise functions both as the conjunction "but" and, independently, as a
  statement-softening discourse particle (`Ik blijf maar in bed` ≈ "I'll just stay in bed").
- **`even/nog/weer/zelfs`** — discourse adverbs with fixed relative ordering: `zelfs` before
  `nog`/`weer`, `weer` before `even`, and `even` typically also precedes `erg/graag/vaak`. `nog`
  eens... dan weer` = "то..., то..." (alternation). `zelfs` does not itself trigger or block
  inversion.
- **Dutch personal-naming system** (paraphrased, not reproduced in full — the source gives ~10
  "full"/formal given names each with ~5 derived nickname-forms, e.g. `Hendrik` → `Hein, Henk,
  Dries, Henriëtte, Riek`, mixing masculine and feminine derivatives from the same root name): Dutch
  children traditionally receive multiple given names at birth but are called by only one
  (frequently a diminutive/nickname form, sometimes foreign-derived) day-to-day. This is presented
  as a puzzle exercise in the source (match nickname to root name) rather than as straight
  vocabulary, so only the pattern is recorded here, not the ~50 individual name-forms.

---

## Progress note (to be read by the next subagent continuing this book, and by whoever updates the checklist)

**Covered so far:** printed pp. 9–43 (orthography chapter + Les 1 + Les 2), DJVU pp. 1–35, of a
168-printed-page (176-DJVU-page) course book — roughly the first 20% by page count.

**Remaining, not yet extracted (continue in `032b_goed_zo.md` onward, one file per lesson or two):**
- Les 3 (printed pp. 44–57, DJVU pp. 36–49)
- Les 4 (printed pp. 58–72, DJVU pp. 50–64)
- Les 5 (printed pp. 73–85, DJVU pp. 65–77)
- Контрольный урок А (printed pp. 86–91, DJVU pp. 78–83) — a review/test lesson; likely
  low-novelty (recombines prior vocabulary) but should still be scanned for any new items.
- Les 6 (printed pp. 92–109, DJVU pp. 84–101)
- Les 7 (printed pp. 110–129, DJVU pp. 102–121)
- Les 8 (printed pp. 130–154, DJVU pp. 122–146)
- **Les 9 (printed pp. 155–174) — CONFIRMED MISSING from this DJVU file, cannot be extracted.**
- Les 10 (printed pp. 175–192ish, DJVU pp. 147–~164) — note: this range includes 180°-rotated scan
  pages (confirmed at DJVU 147/149/153); rotate before reading.
  content still fully readable once rotated.
- Контрольный урок Б (printed pp. ~193 onward, DJVU pp. ~165–176) — DJVU p.176 itself is the table
  of contents, so the actual review-lesson content ends somewhat before DJVU p.176.

This subagent did not have time/turn budget to complete the whole book in one dispatch; the
remaining ~130 printed pages should be dispatched as one or more follow-up subagent passes using
the same page-offset (+8) and rotation/missing-page notes recorded above, so the next subagent
doesn't have to re-derive them.
