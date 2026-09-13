# Russian — *Modern Russian Grammar: A Practical Guide* (John Dunn & Shamil Khairov,
Routledge, 2009), Part 4 of 4

**Source citation:** Dunn, J. & Khairov, S., *Modern Russian Grammar: A Practical Guide*
(Routledge, 2009). This file covers PDF pages 721–913 of
`source_reference/languages/Russian/Russian Learning Pack [up-to-date as of 2012]/Vol 1 of 3/
45.Modern Russian Grammar A Practical Guide.pdf`, corresponding to the book's own printed pages
362–460 (§19.2.4 "Telling the time the 'digital' way" through §23.3 "Discourse words", the end of
the book's substantive grammar chapters). Sibling files (not produced by this subagent) cover pp.
1–240, 241–480 and 481–720 of the same PDF/book (printed pages ~1–361).

## Coverage note

**Back matter correctly excluded.** PDF pages 914–962 (printed pages 461–469) are the book's
alphabetical subject Index ("Note: references are to sections, not to pages") and were confirmed
via direct page-by-page inspection to contain no further grammar or vocabulary content — only
section-number cross-references (e.g. "declension of сам 7.8.1"). Nothing from this range was
extracted.

**PDF extraction gotcha — a new variant for this project's records.** `pdftotext` on this file
initially looked like clean text (`pdfinfo` reports a real text layer, English renders perfectly),
but every embedded Cyrillic example sentence/word came back as **silently dropped whitespace**, not
garbled glyphs — this is a different failure mode from all six Cyrillic font-substitution ciphers
already catalogued in `00_Reference_Extraction_Spec.md`. Investigation with PyMuPDF confirmed the
cause: **the book's Russian-language example sentences are embedded as small raster images
(`Img1`–`Img18` per page, `FlateDecode`/Indexed), not as text at all** — only the English
explanatory prose and translations are real, extractable text. This is presumably an artifact of
how the original publisher typeset Cyrillic in this particular digital edition.

**Fix applied:** rendered all 193 pages (721–913) to 200dpi PNG via `pdftoppm`, then OCR'd each
page with Tesseract using a combined `eng+rus` language model (the `rus.traineddata` fast model was
not preinstalled and was fetched for this session). Combined-language OCR proved highly accurate —
cross-checked against 20+ known Russian/English gloss pairs throughout the chunk (e.g. "ровно
девять часов" / "nine o'clock precisely", "Московское время... В эфире новости" / "Moscow time...
Here is the news") with no decode errors, only the ordinary minor character-confusion noise typical
of OCR (occasional а/a, е/e homoglyph slips, stray punctuation) rather than any systematic cipher.
Every Cyrillic example quoted below was cross-verified against its own English gloss in the source
and is marked `verified` in Vision Reading Confidence; a handful of single isolated words with no
adjacent gloss to cross-check are marked `plausible_unverified`.

**Non-redundant-supplement scope decision.** This chunk spans Chapter 22 ("Coming and going" —
unidirectional/multidirectional verbs of motion, prefixed verbs of motion, prefix–preposition
correlation). This project already has two dedicated verbs-of-motion sources
(`057_russian_verbs_of_motion.md`, Stilman's English-medium overview, and
`028_russkie_glagoly_dvizheniya_s_pristavkami.md`, 815 lines, prefixed-verb-of-motion specialist)
plus verb-of-motion coverage scattered through several general grammars. `057` already tabulates the
prefix–preposition correlation table that this book also gives (§22.2.3). **Chapter 22 is treated
as confirmed redundant and is deliberately NOT re-extracted in vocabulary/grammar-point depth here**
— only a one-line pointer is kept below. Everything else in this chunk (functionally-organized
notional/functional grammar of time, place, manner, cause, condition, concession, purpose, reported
speech, comparison, gerunds, word order/focus, and register/discourse) is organized by a
notional-functional syllabus not duplicated in this project's existing paradigm-organized grammars
(Wade's *Comprehensive Russian Grammar*, the Cambridge *Reference Grammar of Russian*, etc.), so it
is extracted in full as genuinely new material.

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| ровно | precisely, exactly (of time) | adverb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | placed before the preposition в when combined: "ровно в семь часов" |
| по московскому времени | Moscow time (official time-zone marker) | prepositional phrase | core | — | contemporary | — | — | grammar_reference | n/a | verified | abbreviated мск in writing |
| по местному времени | local time | prepositional phrase | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| по Гринвичу | Greenwich Mean Time | prepositional phrase | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| год (abbrev. г.) | year | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | ordinal + год; год abbreviated to г. in writing |
| до нашей эры (до н.э.) | BC | prepositional phrase | core | — | contemporary | — | — | grammar_reference | n/a | verified | "до рождества Христова" also possible, much rarer |
| нашей эры (н.э.) | AD | prepositional phrase | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| век (abbrev. в.) | century | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| декада | a ten-day period (NOT "decade") | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | false-friend warning explicit in source; "decade" of years = десятилетие |
| примерно | approximately | adverb | formal-leaning | — | contemporary | — | — | grammar_reference | n/a | verified | more formal than где-то |
| приблизительно | approximately | adverb | formal-leaning | — | contemporary | — | — | grammar_reference | n/a | verified | |
| где-то | about, somewhere in the region of | adverb | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | explicitly marked more informal by source |
| около (+gen.) | about, approximately | preposition | core | — | contemporary | — | — | grammar_reference | n/a | verified | most frequent preposition for approximation |
| с (+acc., approximation) | about (a round number) | preposition | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | used with десяток/полсотни/сотня |
| десяток | a group of ten | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | plural used for imprecise large quantity: "десятки раз" |
| полсотни | about fifty | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| сотня | a hundred (imprecise) | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | plural "сотни тысяч людей" |
| много | much, many, a lot | quantifier | core | — | contemporary | — | — | grammar_reference | n/a | verified | indeclinable; only nom./acc. without preposition |
| многое | much, a great deal | quantifier | core | — | contemporary | — | — | grammar_reference | n/a | verified | declines like neuter adjective, all cases |
| многие | many (of a larger group) | quantifier | core | — | contemporary | — | — | grammar_reference | n/a | verified | declines like plural adjective; alone = "many people" |
| немало | quite a lot, a fair number/amount | quantifier | core | — | contemporary | — | — | grammar_reference | n/a | verified | similar to много, slightly smaller quantity implied |
| большое количество | a great quantity, many | noun phrase | formal | — | contemporary | — | — | grammar_reference | n/a | verified | replaces много in oblique cases/after prepositions |
| огромное количество | an enormous quantity, very many | noun phrase | formal | — | contemporary | — | — | grammar_reference | n/a | verified | |
| множество | a great number, many | noun | formal | — | contemporary | — | — | grammar_reference | n/a | verified | |
| (целый) ряд | a (great) number, many | noun phrase | formal | — | contemporary | — | — | grammar_reference | n/a | verified | |
| куча | heaps (of) | noun | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | large unspecified quantity, informal register explicit in source |
| тьма | multitudes (of), hordes (of) | noun | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | |
| уйма | masses (of) | noun | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | |
| не перечесть | you can't keep count (of), there's no end to | expression | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | |
| мало | not much, few, little | quantifier | core | — | contemporary | — | — | grammar_reference | n/a | verified | connotation often negative ("too little/not enough") |
| мало кто | not many people | quantifier phrase | core | — | contemporary | — | — | grammar_reference | n/a | verified | takes singular verb as subject |
| немного | some, a bit, a little | quantifier | core | — | contemporary | — | — | grammar_reference | n/a | verified | neutral/positive connotation |
| немножко | some, a bit, a little (diminutive) | quantifier | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | more informal diminutive of немного |
| несколько | several, a few, some | quantifier | core | — | contemporary | — | — | grammar_reference | n/a | verified | declines, all cases (see also 8.6.3) |
| некоторый / некоторые | some, a certain / some (of a larger group) | quantifier | core | — | contemporary | — | — | grammar_reference | n/a | verified | declines like adjective |
| чуть | just, (very) slightly | adverb | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| чуть не | almost, nearly (involuntary actions) | expression | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| чуть ли не | almost, just about | expression | core | — | contemporary | — | — | grammar_reference | n/a | verified | wider range of contexts than чуть не |
| чуть-чуть / чуточку | just a little bit (emphatic) | adverb | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | more emphatic than чуть |
| маленькое/небольшое количество | a small quantity | noun phrase | formal | — | contemporary | — | — | grammar_reference | n/a | verified | replaces мало/немного in oblique cases |
| некоторое количество | a certain quantity | noun phrase | formal | — | contemporary | — | — | grammar_reference | n/a | verified | |
| горстка | a handful (of) | noun | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | |
| кучка | a handful (of) | noun | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | |
| кот наплакал | very little, precious little | idiom | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | literally "the cat cried [that much]" |
| раз-два и обчёлся | very few, can count on fingers of one hand | idiom | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | |
| именно | precisely, that is (emphasis, cleft-sentence equivalent) | particle | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| как раз | precisely, exactly (that very) | particle phrase | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| вот | that's (strong emphasis, sentence-initial w/ question words) | particle | core | — | contemporary | — | — | grammar_reference | n/a | verified | also a discourse filler, see §23.3 |
| -то (emphatic, hyphenated) | emphatic particle, always hyphen-joined | particle | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | combines with и and уж: "нам-то", "они-то и есть" |
| же | emphatic particle, esp. after question words | particle | core | — | contemporary | — | — | grammar_reference | n/a | verified | "Я же тебе говорил!" |
| какой-то / какой-нибудь | some (specific) / some (unspecified) | pronoun | core | — | contemporary | — | — | grammar_reference | n/a | verified | marks indefinite noun |
| утром / днём / вечером / ночью | in the morning / during the day / in the evening / at night | adverb (instr. case) | core | — | contemporary | — | — | grammar_reference | n/a | verified | no dedicated word for "afternoon" — днём or после обеда used |
| с утра | early/first thing in the morning | adverbial phrase | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| по утрам / по ночам (etc.) | in the mornings / at night (regularly) | prepositional phrase | core | — | contemporary | — | — | grammar_reference | n/a | verified | по + dat. plural for regular/habitual time-of-day |
| скоро / нескоро | soon / not for a long time yet | adverb | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| давно / недавно | a long time ago; for a long time (continuing) / recently; not for long (continuing) | adverb | core | — | contemporary | — | — | grammar_reference | n/a | verified | meaning shifts with tense — completed vs. continuing action, §21.1.4 vs §21.1.13 |
| на днях | recently/the other day (past) or soon/any day now (future) | adverbial phrase | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| когда-то / некогда / в своё время | once, at some time in the past | adverb | core | — | contemporary | — | — | grammar_reference | n/a | verified | когда-то most widely used of the three |
| до / после (+gen.) | before / after | preposition | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| перед (+instr.) | immediately before | preposition | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| раньше (+gen.) | before (earliest possible time) | preposition/adverb | core | — | contemporary | — | — | grammar_reference | n/a | verified | comparative of рано |
| по (+prep., 'upon') | (immediately) after | preposition | formal | — | contemporary | — | — | grammar_reference | n/a | verified | only with deverbal nouns, e.g. "по окончании" |
| за (+acc.) ... до (+gen.) | X [time] before | correlative construction | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| через (+acc.) ... после (+gen.) | X [time] after | correlative construction | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| через / спустя (+acc.) | after the elapse of (a period) | preposition | core | — | contemporary | — | — | grammar_reference | n/a | verified | спустя uniquely can precede or follow its noun |
| тому назад | ago | adverbial phrase | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| позже / попозже / потом | afterwards (adverb) | adverb | core (позже) / colloquial (попозже, потом) | — | contemporary | — | — | grammar_reference | n/a | verified | попозже more informal |
| до того как / прежде чем | before (conjunction) | conjunction | core | — | contemporary | — | — | grammar_reference | n/a | verified | прежде чем + infinitive if same subject |
| после того как | after (conjunction) | conjunction | core | — | contemporary | — | — | grammar_reference | n/a | verified | less frequent than English equivalent; often avoided in informal register |
| долго / недолго | for a long time / for a short time, not for long | adverb | core | — | contemporary | — | — | grammar_reference | n/a | verified | unspecified duration of completed action |
| за (+acc., duration) | in [X time] (achievement within a period) | preposition | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| в течение (+gen.) | during, in the course of | preposition | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| на (+acc., intended duration) | for (an intended/planned duration) | preposition | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| во время (+gen.) | during (against a backdrop event) | prepositional phrase | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| в годы (+gen.) | during the years/period of | prepositional phrase | core | — | contemporary | — | — | grammar_reference | n/a | verified | used for a multi-year backdrop period |
| пока | while, for as long as | conjunction | core | — | contemporary | — | — | grammar_reference | n/a | verified | emphasizes simultaneity more than когда |
| с (+gen., starting point) | from | preposition | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| до (+gen., 'until') | until | preposition | core | — | contemporary | — | — | grammar_reference | n/a | verified | ambiguous vs. "up to and including" |
| вплоть до | right up until | prepositional phrase | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| по (+acc., 'up to and including') | until (unambiguously inclusive) | preposition | formal | — | contemporary | — | — | grammar_reference | n/a | verified | official-document register |
| с тех пор как | since | conjunction | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| как только | as soon as | conjunction | core | — | contemporary | — | — | grammar_reference | n/a | verified | future events require future perfective |
| пока (не) ... до тех пор | until (negated conjunction, reinforced) | conjunction | core | — | contemporary | — | — | grammar_reference | n/a | verified | requires negative particle не before the verb |
| вокзал / станция / факультет / кафедра / почта / почтамт / завод / фабрика / предприятие / дача | (mainline) station / (local) station / faculty / university department / post office / main post office / factory (heavy) / factory (light) / enterprise / dacha | nouns | core | — | contemporary | — | — | grammar_reference | n/a | verified | irregular на-group despite being enclosed-space nouns |
| у (+gen., location) | at (someone's place) | preposition | core | — | contemporary | — | — | grammar_reference | n/a | verified | used with persons: "у врача", "у тебя" |
| за границей / за рубежом | abroad | set phrase | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| за пределами | beyond the boundaries of, outside | set phrase | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| за столом | at table | set phrase | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| за городом | out of town, in the country | set phrase | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| за бортом | overboard | set phrase | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| за кулисами | backstage | set phrase | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| перед (+instr., location) | in front of | preposition | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| под (+instr.) | under(neath); just outside (with towns); at (of battles) | preposition | core | — | contemporary | — | — | grammar_reference | n/a | verified | "под Сталинградом" = at Stalingrad |
| над (+instr.) | above, over | preposition | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| при (+prep., location) | attached to, adjacent to; in the presence of | preposition | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| здесь / тут / там | here / here / there | adverb | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| близко / далеко / рядом / впереди / сзади | near(by) / far / close by, next door / ahead / behind | adverb | core | — | contemporary | — | — | grammar_reference | n/a | verified | combine with к/от/с per §21.2.13 |
| где | where (conjunction, location) | conjunction | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| сюда / туда | (to) here / (to) there | adverb | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| куда | where(to) (conjunction, destination) | conjunction | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| из / с / от / из-за / из-под | out of / from (на-locations) / from (у-locations) / from behind / from under | preposition | core | — | contemporary | — | — | grammar_reference | n/a | verified | starting-point correlates of в/на/у/за/под |
| отсюда / оттуда | from here / from there | adverb | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| откуда | from where (conjunction) | conjunction | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| до (+gen., point reached) | as far as | preposition | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| от (+gen.) ... до (+gen.) | from ... to (distance between two places) | correlative construction | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| по (+dat., motion along a surface) | along, through, around | preposition | core | — | contemporary | — | — | grammar_reference | n/a | verified | can be unidirectional or non-directional |
| по дороге / по пути | on the way (to) | set phrase | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| через (+acc., across) | across, over, via | preposition | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| образ / путь / способ | way, manner, fashion | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | used with qualifier + instrumental for manner |
| порядок (в + prep.) | in the usual/prescribed way | set phrase | formal | — | contemporary | — | — | grammar_reference | n/a | verified | bureaucratic register explicit in source |
| с (+instr., abstract noun of manner) | with [quality] (manner) | preposition | core | — | contemporary | — | — | grammar_reference | n/a | verified | used far more than English "with" |
| как (manner conjunction) | as, the way (that) | conjunction | core | — | contemporary | — | — | grammar_reference | n/a | verified | distinguish так, как ('as') from так как ('since') |
| из-за (+gen.) | because of (negative outcome) | preposition | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| благодаря (+dat.) | because of, thanks to (positive outcome) | preposition | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| по причине | for [a] reason (euphemistic, e.g. "по техническим причинам") | prepositional phrase | formal | — | contemporary | — | — | grammar_reference | n/a | verified | explicit euphemism-for-undesirable-events use noted by source |
| по (+dat., inadvertent cause) | out of, as a result of (unintentional) | preposition | core | — | contemporary | — | — | grammar_reference | n/a | verified | "по рассеянности" = out of absent-mindedness |
| ввиду / в результате / в силу / вследствие (+gen.) | because of, owing to, as a result/consequence of | preposition | formal | — | contemporary | — | — | grammar_reference | n/a | verified | more written than spoken register, per source |
| от (+gen., physical cause) | of, from (direct involuntary cause) | preposition | core | — | contemporary | — | — | grammar_reference | n/a | verified | "умер от голода" |
| с (+gen., informal physical cause) | of, from (figurative/set expressions) | preposition | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | "умер со смеху"; explicit informal-register note in source |
| из (+gen., conscious motive) | out of (deliberate motive) | preposition | core | — | contemporary | — | — | grammar_reference | n/a | verified | "из любопытства", "из вредности" |
| потому что / потому как / так как / поскольку / ибо | because, as, since, for | conjunction | core (потому что, так как) / colloquial (потому как) / formal-bureaucratic (поскольку) / archaic-formal (ибо) | — | contemporary | — | — | grammar_reference | n/a | verified | register spread explicitly given by source |
| так что | (and) so | conjunction | core | — | contemporary | — | — | grammar_reference | n/a | verified | indicates consequence |
| поэтому | therefore, that's why | adverb | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| вот и | and that's why (undesired consequence) | expression | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | |
| если | if (conditional conjunction) | conjunction | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| бы | conditional/subjunctive particle | particle | core | — | contemporary | — | — | grammar_reference | n/a | verified | follows если directly |
| если бы не (+noun) | if it were not for | conditional phrase | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| случайно / вдруг / всё-таки (in conditions) | by any chance / suddenly, by some chance / after all | adverb | core | — | contemporary | — | — | grammar_reference | n/a | verified | mark tentativeness of an open condition (Russian keeps future tense, unlike English "were to") |
| при (+prep., replacing если) | should ... (conditional, abstract noun) | preposition | formal | — | contemporary | — | — | grammar_reference | n/a | verified | "при желании", "при необходимости" |
| в случае (+gen.) | in the event of | prepositional phrase | formal | — | contemporary | — | — | grammar_reference | n/a | verified | |
| несмотря на (+acc.) / несмотря на то, что | in spite of, despite / in spite of the fact that | prepositional phrase / conjunction | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| несмотря ни на что | in spite of everything | expression | core | — | contemporary | — | — | grammar_reference | n/a | verified | self-contained only; extended form uses "несмотря на всё (то), что" |
| вопреки (+dat.) | in spite of, contrary to | preposition | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| при (+prep., concessive 'for all his...') | for (all his/her...) | preposition | core | — | contemporary | — | — | grammar_reference | n/a | verified | "при всём своём таланте" |
| всё же / всё равно / всё-таки | still, all the same / still, even so / still, all the same | adverb | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| хотя / хоть | although | conjunction | core (хотя) / colloquial (хоть) | — | contemporary | — | — | grammar_reference | n/a | verified | хоть = shortened informal form |
| при (всём) том, что | although | conjunction | formal | — | contemporary | — | — | grammar_reference | n/a | verified | |
| а то / иначе | or else | conjunction | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| [question word] + бы ... ни | no matter [who/what/where/how...] | correlative construction | core | — | contemporary | — | — | grammar_reference | n/a | verified | conditional verb form for hypothetical; indicative for real events |
| для (+gen.) / на (+acc., purpose) | for (the purpose of) | preposition | core | — | contemporary | — | — | grammar_reference | n/a | verified | для = concrete object's purpose; на = more abstract |
| за (+instr., purpose) | to fetch/for (going to get something) | preposition | core | — | contemporary | — | — | grammar_reference | n/a | verified | "сбегать за хлебом" |
| чтобы (+infin./+past tense) | in order to / so that | conjunction | core | — | contemporary | — | — | grammar_reference | n/a | verified | infinitive if same subject, past tense if different subjects |
| для того, чтобы / с тем, чтобы | in order to, so that (reinforced) | conjunction | formal-leaning | — | contemporary | — | — | grammar_reference | n/a | verified | |
| с целью | with the aim of | prepositional phrase | formal | — | contemporary | — | — | grammar_reference | n/a | verified | |
| заявлять/заявить | to claim, state, declare | verb | formal | — | contemporary | — | — | grammar_reference | n/a | verified | near-synonym of говорить/сказать in formal register |
| сообщать/сообщить | to announce, state | verb | formal | — | contemporary | — | — | grammar_reference | n/a | verified | |
| утверждать | to affirm, state (imperfective only) | verb | formal | — | contemporary | — | — | grammar_reference | n/a | verified | |
| будто | (reporting with speaker's distancing/skepticism) | conjunction | core | — | contemporary | — | — | grammar_reference | n/a | verified | marks speaker's disbelief in reported claim |
| мол / мол де / дескать | (he) claims, allegedly (distancing particle) | particle | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | spoken/informal-written register explicit in source |
| якобы | supposedly, allegedly (strong disbelief) | particle | core | — | contemporary | — | — | grammar_reference | n/a | verified | stronger degree of disbelief than мол/дескать |
| ли (indirect question particle) | if, whether | particle | core | — | contemporary | — | — | grammar_reference | n/a | verified | enclitic, follows first stressed word; distinguish from если |
| интересно (бы знать) | I wonder, it would be interesting to know | expression | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| осведомляться/осведомиться | to enquire (formal) | verb | formal | — | contemporary | — | — | grammar_reference | n/a | verified | |
| справляться/справиться (о + prep.) | to enquire | verb | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| чем (comparative conjunction) | than | conjunction | core | — | contemporary | — | — | grammar_reference | n/a | verified | required when 2nd element is not nom./acc.; comma normally precedes |
| гораздо / намного / значительно | a lot (more/less) | adverb | core/formal | — | contemporary | — | — | grammar_reference | n/a | verified | значительно more formal |
| много / куда (informal comparative intensifiers) | a lot (more), "way" (more) | adverb | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | куда adds extra expressiveness, per source |
| больше/более, меньше/менее | more, less | quantifier | core | — | contemporary | — | — | grammar_reference | n/a | verified | больше/меньше vs более/менее distinguish quantity-expression from long-comparative use |
| чем + comparative ... тем + comparative | the more ... the more | correlative construction | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| тем более (что) | all the more so (because), especially (because) | expression | core | — | contemporary | — | — | grammar_reference | n/a | verified | used more frequently than English equivalent |
| тот же (самый) | the same | pronoun phrase | core | — | contemporary | — | — | grammar_reference | n/a | verified | самый optional |
| такой же | the same (of the same sort) | pronoun phrase | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| одинаково | the same (adverbially, 'in the same way') | adverb | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| похожий (на + acc.) / похоже (что) | similar (to) / it looks as if | adjective/expression | core | — | contemporary | — | — | grammar_reference | n/a | verified | predicative almost always short form |
| как (comparison conjunction) | as, like | conjunction | core | — | contemporary | — | — | grammar_reference | n/a | verified | follows такой/так |
| другой / иной | different (another) | adjective | core (другой) / formal (иной) | — | contemporary | — | — | grammar_reference | n/a | verified | |
| разный / различный | different (from each other / various) | adjective | core (разный) / formal (различный) | — | contemporary | — | — | grammar_reference | n/a | verified | различный has a short form |
| отличаться от (+gen.) / различаться | to differ from / to differ (from each other) | verb | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| разница / различие | difference | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | разница singular-only; различие has plural |
| в отличие от (+gen.) | unlike | prepositional phrase | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| не похожий (на) | unlike (in other senses) | adjective phrase | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| ведущий / выдающийся / действующий / окружающий / отсутствующий / потрясающий / предшествующий / присутствующий / решающий / следующий / смягчающий / текущий | leading, presenter / outstanding / active, functioning / surrounding / absent / staggering, amazing / preceding / present / deciding, decisive / following, next / mitigating / current | adjective (participle-derived) | core | — | contemporary | — | — | grammar_reference | n/a | verified | лексикализованные participles, no longer restricted to formal-only register per source |
| вооружённый / воспитанный / разочарованный / убеждённый / умеренный / цивилизованный | armed / well brought up / disenchanted, disappointed / convinced / moderate / civilised | adjective (participle-derived) | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| верующий / курящий / служащий | believer / smoker / white-collar worker (all also function as nouns) | noun (participle-derived) | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| данные / подданный / подчинённый | data / subject (of the crown) / subordinate | noun (participle-derived) | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| впрочем | however, on second thoughts | вводное слово (parenthetical) | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| значит | so (also a discourse filler, §23.3) | вводное слово | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| итак | and so | вводное слово | formal-leaning | — | contemporary | — | — | grammar_reference | n/a | verified | |
| как бы то ни было | however that may be | вводное слово | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| кроме того / к тому же | in addition, moreover | вводное слово | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| однако | however | вводное слово | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| следовательно / стало быть / таким образом | therefore | вводное слово | formal (следовательно, таким образом) / colloquial (стало быть) | — | contemporary | — | — | grammar_reference | n/a | verified | |
| тем не менее | nonetheless, nevertheless | вводное слово | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| конечно | of course | вводное слово | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| (само собой) разумеется | of course | вводное слово | formal-leaning | — | contemporary | — | — | grammar_reference | n/a | verified | |
| должно быть | it must be the case that | вводное слово | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| наверное / наверно | probably | вводное слово | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | наверное more in writing, наверно more in speech, per source's explicit note |
| по-видимому | apparently | вводное слово | formal-leaning | — | contemporary | — | — | grammar_reference | n/a | verified | |
| пожалуй | probably, perhaps | вводное слово | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| кажется | it seems | вводное слово | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| возможно / может быть | it is possible that / perhaps | вводное слово | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| допустим / предположим | let us assume / let us suppose | вводное слово | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| одним словом / короче говоря | in a word / to put it briefly | вводное слово | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| собственно говоря | strictly speaking | вводное слово | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| шутки в сторону | joking apart | вводное слово | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | |
| кстати (говоря) / между прочим | by the way | вводное слово | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| к счастью / к сожалению | fortunately / unfortunately | вводное слово | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| во-первых / во-вторых / в-третьих | in the first/second/third place | вводное слово | core | — | contemporary | — | — | grammar_reference | n/a | verified | enumerator sequence |
| а (topic-shift conjunction) | and, but (introduces new topic/development, esp. in questions) | conjunction | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| а вдруг | what if?, suppose | expression | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | |
| в общем | in general, on the whole | discourse word | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| в принципе | in principle | discourse word | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| так (discourse filler) | so, well (gains thinking time) | discourse word | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | initial vowel sometimes lengthened ("Та-ак") when stalling |
| так сказать | so to speak | discourse word | core | — | contemporary | — | — | grammar_reference | n/a | verified | |
| это (самое) | the whatsit (word-search filler) | discourse word | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | |
| как его/её там | the whatever-it's-called, what's-its-name | discourse word | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | |
| как бы | sort of | discourse word | youth slang | — | contemporary | — | — | grammar_reference | n/a | verified | flagship find: source gives explicit sociolinguistic "health warning" — see grammar point 23.3 |
| типа | like | discourse word | youth slang | — | contemporary | — | — | grammar_reference | n/a | verified | same explicit health-warning framing as как бы |
| блин | (emphasizes preceding word; euphemism for an obscenity) | discourse word / mild expletive | taboo-adjacent slang | — | contemporary | — | — | grammar_reference | n/a | verified | literally "pancake"; source explicitly identifies it as a transparent euphemism for блядь, offensive to many Russians despite common youth use |

## Grammar points

### 19.2.4–19.2.6 Telling the time: the 'digital' method and time zones
Alongside the "traditional" clock-face method (covered in a sibling file), Russian has a
"digital" method that reads times as raw numbers (Московское время пятнадцать часов, тридцать
минут — "Moscow time is 15.30"), originally from military/bureaucratic usage but now common in
ordinary speech. Zero minutes/hours are indicated by ноль ("шестнадцать ноль пять" = 16.05). The
24-hour clock is common but not obligatory even in informal "digital" contexts. Question phrases
for "at what time" are в котором часу?, в какое время? and во сколько? (the last is the most
informal). The preposition в (+acc.) marks "at [time]" for whole hours or digital times; ровно, if
used, precedes the preposition. In informal speech в can be dropped before "traditional"-method
times before the half-hour; the construction cannot be used at all between the half-hour and the
hour (Russian disallows stacked prepositions) — speakers either switch to the digital method or
drop connecting words entirely. Russia spans eleven time zones; Moscow time is the de facto
national reference for all rail/air timetables, marked по московскому времени (abbrev. мск).

### 19.3 Talking about the date
The date is asked with Какое сегодня число? and given with an ordinal + optional число ("Сегодня
двадцать девятое [число]"). When a month is given, число is dropped and the month is genitive
("первое сентября"). Years use an ordinal + год (год abbreviated to г. in writing); when a full
date is given, the year is genitive. European day-month-year figure order is used, sometimes with
Roman numerals for the month. In spoken Russian, years are often abbreviated to their last two or
three digits when unambiguous ("в сорок первом году" = 1941). Decades use an ordinal + годы
("девяностые годы" = the (19)90s); the false friend декада means a ten-day period, not a decade of
years (десятилетие). Centuries use an ordinal + век (abbrev. в.), always with capital Roman
numerals when given in figures. до нашей эры (до н.э.) marks BC; нашей эры (н.э.) marks AD.

### 19.4–19.5 Approximate and imprecise quantity
Russian has a rich, register-stratified system for approximation. Flexible adverbs (примерно,
приблизительно — more formal; где-то — more informal) work in any grammatical context. Placing a
numeral after its noun also signals approximation ("лет сорок пять" ≈ "about forty-five"), as does
the preposition около (+gen.), the most frequent dedicated approximation preposition, or (more
colloquially) с (+acc.) combined with the round-number nouns десяток/полсотни/сотня. Because two
prepositions cannot combine in Russian, около/с cannot be used where the quantity phrase is itself
already governed by a preposition. A hyphenated range of two numerals ("пять-шесть", "двадцать
пять-тридцать") also marks approximation and can combine with the other devices.

For imprecise large quantities: много/многое/многие (indeclinable/declinable variants with
different case restrictions and reference — много for bare uncountable/countable bulk, многое for
"much of X" declining as neuter, многие for "many people/things of a larger group" declining as
plural) form the core system; немало is a near-synonym implying a slightly smaller quantity.
Formal register replacements usable in any case/after prepositions include большое/огромное
количество, множество, (целый) ряд; colloquial-register equivalents include куча, тьма, уйма, не
перечесть. For imprecise small quantities, мало (often carrying a negative "too little" nuance) and
немного/its diminutive colloquial form немножко form the core pair; несколько ('several') and
некоторый/некоторые ('some'/'a certain') pattern similarly but with different case-agreement rules
(несколько-plural agrees in case with несколько itself; some/certain agree as adjectives). чуть,
чуть не ('almost', involuntary), and чуть ли не ('almost', broader use) intensify smallness or
near-completion; чуть-чуть/чуточку are more emphatic variants of чуть. Formal small-quantity
equivalents are маленькое/небольшое/некоторое количество; colloquial equivalents are горстка,
кучка, and the vivid idioms кот наплакал and раз-два и обчёлся.

### 20.1–20.4 Word order, focus and definiteness
Unlike English, Russian word order is not structurally required to mark subject vs. object (case
endings do that job); instead it encodes information flow — old/topic information first, new/most
important information last. This lets a Russian sentence like "Марию пригласил Иван" (object-verb-
subject) correspond to an English cleft sentence ("It was Ivan who invited Mariia"). This principle
governs adjective/pronoun placement (before the noun, with post-posed adjectives adding emphasis or,
with short comparatives, in informal register with по- prefixed forms — "человек помоложе"),
adverb placement (immediately before what they qualify, or sentence-initial when qualifying the
whole sentence), and small unstressed-pronoun placement (tucked mid-sentence). Passive verbs are
used less than in English and, per the source, are especially characteristic of formal register;
Russian more often achieves the same "recipient-first" effect by simply fronting the direct object
with an active verb. Emphasis beyond word order alone is added with именно and как раз (both
roughly "precisely"/cleft-sentence equivalents) or via a family of emphasis particles: вот
(strong, sentence-initial, esp. with question words), the always-hyphenated -то (which can stack
with и and уж), and же (esp. after question words). Definiteness/indefiniteness, unmarked by any
article in Russian, is signalled by word order (indefinite nouns trend to sentence end, definite
nouns to sentence start) or by qualifiers: какой-то/какой-нибудь and the numeral один function as
indefinite-article equivalents; этот and тот (often with который) function as definite-article
equivalents.

### 21.1 Time (functional-notional survey)
This section systematically catalogues, by function rather than by paradigm, the full set of
devices for locating an event in time: parts of the day (instrumental case: утром, днём, вечером,
ночью; с утра "first thing"; по + dat. plural for regularity); days of the week (в + acc. for a
specific occurrence, по + dat. plural for regularity); seasons (instrumental); a large stock of
adverbial time words (вчера/сегодня/завтра/позавчера/послезавтра; на прошлой/этой/будущей неделе
etc.; скоро/нескоро; давно/недавно — noting that давно/недавно flip their nuance between "a long
time ago"/"not long ago" for completed actions (§21.1.4) and "for a long time"/"not for long" for
still-continuing actions (§21.1.13); на днях; когда-то/некогда/в своё время); the conjunction когда
(sometimes dropped in informal future-referring speech); a full before/after system (до/после +gen.,
перед +instr. "immediately before", раньше +gen. "earliest possible", formal-register по +prep.
"upon", за...до and через...после for relative event ordering, через/спустя for elapsed time,
тому назад for "ago", the adverbs раньше/позже/попозже[colloq]/потом[colloq], and the conjunctions
до того как/прежде чем [+infin. if same subject]/после того как — the last explicitly flagged by
the source as rarer than its English counterpart and best avoided in informal registers in favor of
prepositional-noun paraphrases or a reframed clause with когда); duration for completed actions
(bare accusative, or the adverbs долго/недолго for unspecified duration); duration for continuing
actions (same accusative construction but present tense, or давно/недавно again); further duration
devices (за +acc. for "achieved within," в течение +gen. "during/in the course of" for
states/repeated/non-occurring actions, на +acc. for intended duration, во время +gen. and the
multi-year в годы +gen. for backdrop events, пока for exact simultaneity); and the from/to/until
system (с +gen. from, до +gen./вплоть до until, formal по +acc. "up to and including" [explicitly
unambiguous vs. до], с тех пор как since, как только as soon as, and the reinforced negated пока
не...до тех пор for until).

### 21.2 Place (functional-notional survey)
An unusually granular, idiom-heavy catalogue of every major means of locating something in space,
organized as a set of категория-specific default prepositions with named exceptions: в for
towns/cities/districts/regions and (with named exceptions Кипр/Куба/Мальта → на, and a politically-
loaded note on the post-1991 в Украине/на Украине split, the latter now perceived as
potentially offensive in Ukraine); на for islands/peninsulas/mountain ranges (exceptions Крым,
Альпы → в); в for мир but на for свет; на for geographic/climatic-zone nouns and compass points; в
for enclosed-space nouns generally, but a named irregular на-group (вокзал, станция, факультет,
кафедра, почта, почтамт, завод, фабрика, предприятие, дача); на for open-space nouns (рынок,
стадион, остановка, улица, площадь; на улице can idiomatically mean "outside"); в for
парк/сад/переулок; a meaning-bearing в/на split for двор (courtyard vs. "outside"); a meaning-
bearing в/на split for transport (interior-focus vs. means-of-travel-focus); в for organisations;
на for function/activity-denoting locations (в with the same nouns instead describes content, not
location); у (+gen.) for "at [a person's] place"; and a further battery of prepositions (за +acc./
+instr., перед, под, над, при +prep.) each with idiom-rich set-phrase clusters (за границей, за
рубежом, за пределами, за столом, за городом, за бортом, за кулисами). Adverbs (здесь/тут/там,
близко/далеко/рядом/впереди/сзади, combinable with к/от/с) and где cover the remaining "other ways"
of expressing location. Destination and starting-point prepositions correlate systematically with
their location counterparts (в→в+acc.; на→на+acc.; у→к; за+instr.→за+acc.; под+instr.→под+acc. only
literally; adverbs сюда/туда and conjunction куда for destination; из/с/от/из-за/из-под and adverbs
отсюда/оттуда and conjunction откуда for starting point). до (+gen.) marks a point actually reached;
от...до marks distance between two points; по (+dat.) marks motion along a surface (in one
direction, multiple directions, or none in particular; includes the set phrases по дороге/по пути);
через (+acc.) marks "across/via."

### 21.3 Manner
Adverbs (placed immediately before the verb) are the default manner device. A qualifier + noun in
the instrumental is a second device, especially productive with the "way/manner/fashion" nouns
образ, путь, способ (and, in bureaucratic register, порядок governed by в + prepositional). с
(+instr.) with an abstract noun is a third device used far more frequently than its literal English
equivalent ("с большим удовольствием" = "greatly [enjoy]"). The conjunction как covers manner
clauses ("Сделайте так, как я советую"), with an explicit warning to distinguish так, как ('as') from
the causal conjunction так как ('since').

### 21.4 Causes and consequences
Two everyday prepositions split by valence of outcome: из-за (+gen., negative outcome) vs.
благодаря (+dat., positive outcome), both "because of." по (+dat.) with причина expresses cause,
including a euphemistic bureaucratic use ("по техническим причинам" = "for technical reasons," used
to avoid a fuller undesirable explanation) and, with abstract nouns directly, an inadvertent-cause
sense ("по рассеянности" = "out of absent-mindedness"). Four written-register prepositions (ввиду,
в результате, в силу, вследствие, all +gen.) offer near-synonymous "because of" alternatives. от
(+gen.) covers direct, physical, involuntary causes ("умер от голода"); the near-synonymous с
(+gen.) is explicitly flagged as informal-register and typically figurative/set-phrase ("умер со
смеху"). из (+gen.) covers conscious motive ("из любопытства", "из вредности"). Five near-synonymous
causal conjunctions (потому что, потому как, так как, поскольку, ибо) are explicitly register-
stratified by the source: потому как = informal, ибо = nowadays very formal only, поскольку =
widely used but perceived by some as bureaucratic/journalistic register, потому что/так как =
otherwise unmarked core. Consequence is marked by поэтому ("therefore"), the colloquial idiom вот и
(marking an undesired consequence), and the conjunction так что ("and so").

### 21.5–21.6 Conditions and concessions
Conditions split into open (fulfillable) vs. unreal (hypothetical/impossible), a distinction the
source stresses is sharper in Russian than in English — a Russian sentence keeps the future tense
for anything not literally impossible, even tentative-sounding English "were to" conditions;
tentativeness/improbability is instead flagged lexically with случайно, вдруг, or всё-таки. Open
conditions use если + future/present/past tense as appropriate (plus imperative for
recommendations, infinitive for generic subjects); unreal conditions use если + бы + the
conditional/past-tense verb in both halves, with бы normally directly after если. если бы не + noun
gives "if it were not for..." Conditions can also be formed without если by using the imperative
mood idiomatically, or (informally, increasingly also in writing) simply by juxtaposing two clauses
with no conjunction at all ("Жарко покажется — открой окно"). In more formal registers, при
(+prep.) with an abstract noun, or the phrase в случае (+gen.), can replace an если-clause. In
indirect speech, a condition can look unreal in English (tense-shifted) while remaining a true open
condition in the Russian original — the future perfective is retained. Concession (the "reverse of
condition") is expressed with несмотря на (+acc.)/несмотря на то, что ("in spite of"/"in spite of
the fact that" — with несмотря ни на что as a fixed self-contained "in spite of everything," and
несмотря на всё (то), что as its extended form), вопреки (+dat.), or concessive при (+prep., "for
all his/her..."); with the adverbs всё же/всё равно/всё-таки; with the conjunctions хотя (core) and
its informal-register shortened form хоть, and the formal-register phrase при (всём) том, что; with
а то/иначе ("or else"); and with a productive question-word + бы...ни pattern ("Куда бы ты ни
поехал..." = "Wherever you go...") that uses the conditional for hypothetical/generalized reference
and ordinary tenses for real events.

### 21.7 Purpose
для (+gen.) marks the purpose of a concrete object/space; на (+acc.) is similar but favors more
abstract contexts and focus-on-intended-purpose. за (+instr.) marks "going to fetch" something
(shopping, queuing, collecting someone). чтобы is the default purpose conjunction: + infinitive when
both clauses share a subject, + past tense when subjects differ; it can be reinforced with для
того or с тем (more formal); it can be dropped entirely in short sentences sharing a subject where
the main verb is a verb of motion or a semantically related verb (остановиться, остаться) — but
must be retained in more complex sentences, when the purpose-clause is fronted, or when the
infinitive is negated. с целью (+infin. or +gen. noun) is a formal-register purpose phrase.

### 21.8 Reporting the words of others
Direct speech uses inverted commas within a paragraph but dashes when dialogue is laid out in its
own paragraphs; a speech-act verb following direct speech always precedes its subject. Indirect
statements use говорить/сказать plus the (non-omissible, unlike English "that") conjunction что;
formal-register near-synonyms include заявлять/заявить, сообщать/сообщить, утверждать (imperfective-
only), alongside many further reporting verbs (добавлять, думать, кричать, надеяться, объяснять,
отвечать, полагать, понимать, предполагать, считать, шептать). A present-tense reporting verb can be
inserted mid-quote, comma-separated, as a device for avoiding an awkward stack of что-clauses.
Instructions/prohibitions in reported speech use чтобы. A speaker's distancing from a reported claim
is marked by the conjunction будто, or — especially in spoken/informal-written register — by the
particles мол/мол де/дескать; a stronger degree of disbelief is marked by якобы. Indirect questions
use спрашивать/спросить plus the enclitic particle ли (following the first stressed word, normally
the verb) rather than a conjunction — critically distinguished from если ('if' in a true
condition); other question-introducing verbs/phrases include интересно (бы знать), интересоваться/
поинтересоваться, осведомляться/осведомиться (formal), справляться/справиться. Crucially, Russian
does NOT shift tense in indirect speech the way English does: the tense/aspect of the reported verb
always matches what was actually said, which can make an English tense-shifted unreal-looking
condition ("He said that if he didn't pass...") correspond to a Russian sentence that is really
still an open condition in the future perfective.

### 21.9 Comparisons
The short comparative of adjectives/adverbs is used with predicative adjectives and, in informal
register, with attributive adjectives immediately following their noun (typically with a по- prefix:
"человек помоложе"). Its second-element comparison ("than X") is genitive when the compared item is
nominative/accusative, or introduced by the conjunction чем (preceded by a comma) in all other
contexts — чем is also preferred for complex sentences or to avoid ambiguity. Extent-of-comparison
("X years older") uses на (+acc.); "a lot more/less" uses гораздо/намного/значительно (formal-
leaning) or, informally, много/куда (куда adds extra expressiveness, per the source). больше/более
and меньше/менее ("more"/"less") are interchangeable in quantity expressions but otherwise diverge
(больше/меньше preferred generally; only более/менее form the long comparative); both are
indeclinable and thus avoided in oblique/prepositional contexts via paraphrase. чем + comparative...
тем + comparative gives "the more...the more"; тем более (что) gives "all the more so (because)."
The long comparative form is used with attributive adjectives and any predicative adjective lacking
a short form; four irregular declinable comparatives (лучший, худший, больший, меньший) function as
ordinary attributive adjectives but — except for лучший — are used less than their English
counterparts, mostly restricted to abstract/set-phrase contexts (большая часть, в большей/меньшей
степени). менее marks a lesser degree. "The same" is тот же (самый) (identity), such variants as
такой же (same kind), одинаково (adverbial "same way"); "similar" is похожий (на+acc.)/похоже (что);
the comparison conjunction is как. "Different" splits into другой/иной (different = another; иной
more formal), разный/различный (different from each other / various; различный more formal, has a
short form), verbs отличаться от/различаться, nouns разница (singular-only)/различие (has plural),
and the prepositional phrase в отличие от ("unlike").

### 21.10 Gerunds for context
Gerunds (verbal adverbs) let a single clause do double duty as adverb-of-manner and as a compressed
subordinate clause (time/reason/condition/concession), but only when the gerund clause shares its
subject with the main clause; they occur rarely in speech but widely in written registers. The
imperfective gerund marks simultaneity (unnegated) or manner-without-doing ("без ... -ing";
negated). The perfective gerund normally marks an action preceding the main verb, though it can
mark simultaneity when the focus is on the outcome/totality of the gerund's action rather than its
process (e.g. "она... поступила, выйдя замуж" — the focus is on the state of being married, not the
process of marrying).

### Chapter 22 — Coming and going (verbs of motion): confirmed redundant, not re-extracted
This chapter (unidirectional/multidirectional verb pairs, their perfective partners, prefixed verbs
of motion, the prefix–preposition correlation table, and figurative/idiomatic uses) duplicates
material already fully captured in `057_russian_verbs_of_motion.md` and
`028_russkie_glagoly_dvizheniya_s_pristavkami.md` (which already tabulates the same
prefix-preposition correlation this book gives in §22.2.3), plus scattered treatment across several
general grammars. Per the non-redundant-supplement rule, no vocabulary/grammar-point detail is
re-extracted here.

### 23.1 Register: formal vs. informal language, and the boundary with non-standard language
The source frames register primarily along a formal/informal axis (rather than written/spoken,
since both exist in both registers) and explicitly separates informal language (used appropriately
by everybody) from **non-standard language**, which it defines as forms disapproved of by educated
speakers — noting a whole Internet subculture built on deliberately non-standard, playfully
misspelled forms, and cautioning that learners should approach non-standard usage only with total
confidence in the standard language first, since even non-standard language has its own internal
"rules" that a learner can violate embarrassingly. Formal written language is typified by long,
grammatically complex sentences; heavy use of long-form participles (a functional near-equivalent of
relative clauses, illustrated with genuinely dense multi-clause participial sentences quoted from
actual Russian passport-law regulations); a preference for abstract/verbal-noun constructions over
finite verbs; and avoidance of first-person singular in favor of depersonalized/passive
constructions (illustrated with a real newspaper passage on Putin's early presidency). A number of
participles have lexicalized into ordinary core-register adjectives/nouns no longer carrying the
formal-only restriction (ведущий, выдающийся, действующий, окружающий, отсутствующий, потрясающий,
предшествующий, присутствующий, решающий, следующий, смягчающий, текущий, вооружённый,
воспитанный, разочарованный, убеждённый, умеренный, цивилизованный, верующий, курящий, служащий,
данные, подданный, подчинённый).

### 23.2 Constructing a text: вводные слова and the topic-shift conjunction а
Russian вводные слова ("introductory words," comma-set-off parentheticals not necessarily at
sentence-start) are catalogued by function: sentence-linking (впрочем, значит, итак, как бы то ни
было, кроме того, к тому же, однако, следовательно, стало быть, таким образом, тем не менее);
probability-marking (конечно, (само собой) разумеется, должно быть, наверное/наверно — with the
source explicitly noting наверное skews to writing and наверно to speech, по-видимому, пожалуй,
кажется, возможно, может быть); metacommentary on the utterance itself (допустим, предположим,
одним словом, короче говоря, собственно говоря, шутки в сторону, кстати (говоря), между прочим);
speaker-attitude marking (к счастью, к сожалению); and argument-enumeration (во-первых, во-вторых,
в-третьих). Separately, the conjunction а, beyond its ordinary clause-linking role, functions
sentence-initially (especially in dialogue/questions) as a topic-shift/emphasis marker, and combines
in the fixed phrase а вдруг ("what if?").

### 23.3 Discourse words — flagship register/slang finding
This closing section is the highest-value content in the entire chunk for the project's slang-
mechanics purposes. The source defines "discourse words" as near-meaningless structural fillers
(thinking-time fillers, or hedging/emphasis markers) and gives a general-purpose list: в общем, вот,
в принципе, значит, так (can lengthen its vowel — "Та-ак" — when a speaker is stalling for time),
так сказать, это (самое) and как его/её там (both word-search fillers meaning roughly "the
whatsit"/"what's-its-name"). It then explicitly isolates **three discourse words "particularly
characteristic of the speech of young people"**: как бы ("sort of"), типа ("like"), and блин
(intensifies/emphasizes the preceding word). The source pairs this finding with an unusually direct
sociolinguistic judgment for a pedagogical grammar: these three come with a "serious health
warning" — their use is regarded by many Russians as signaling an inadequate grasp of the language
or an inability to think/speak clearly, and блин specifically is identified as a transparent
euphemism for an obscenity (the source does not spell out блядь, but the euphemistic relationship is
explicit), offensive to many Russians despite widespread casual/youth use. This is a rare instance
of a mainstream pedagogical grammar directly naming and register-flagging youth slang/filler
particles alongside an explicit taboo-euphemism note — directly relevant to this project's
register-mechanics and taboo-avoidance-naming findings from other sources (cf. SCB Phase 1's
taboo-avoidance-naming finding).
