# Russian — Established Vocabulary/Grammar: Case System via Dialogues (non-redundant supplement)

**Source:** Л. Н. Булгакова, И. В. Захаренко, В. В. Красных, *Мои друзья падежи: Грамматика в
диалогах* ["My Friends the Cases: Grammar in Dialogues"] (Русский язык. Курсы, 2002), Russian-medium
throughout. Full book: 213 printed pages / 110 PDF pages, six parts (one per case, in the
nominative→prepositional→accusative→genitive→dative→instrumental teaching order) plus an appendix.
This file covers the whole book at a survey level; see "What was skipped as redundant" below for why
most of the paradigm-drill content was not re-transcribed.

**Non-redundant-supplement scope decision.** Russian's six-case system is already extensively
covered by Wave 1 (`004_seelrc_russian_reference_grammar.md`, the two-part Timberlake *Reference
Grammar of Russian*, Wade's *Comprehensive Russian Grammar*, the *Schaum's Outline*, and others). This
book is ~90% repeated declension-drill exercises reusing the same paradigm endings already tabulated
by those sources — pedagogical padding per the extraction spec's coverage rule, correctly skipped
here. What genuinely justified extraction:
1. The book's own methodological framing (a "кассы"/frame-based dialogue-construction drill system)
   — not previously captured, useful context for how this corpus's dialogue examples are structured.
2. A **systematic preposition-by-case functional map for spatial and temporal expression**
   (Приложение, pp. 176–181) — organizes every common spatial/temporal preposition by which case it
   governs and which question it answers (КУДА?/ГДЕ?/ОТКУДА?, etc.). Prior Wave-1 sources present case
   government per-preposition scattered through their own chapters; this book's single consolidated
   table is a fuller, more systematic version of that specific cut, which the extraction spec calls
   out as worth capturing even on an already-covered topic.
3. A **full personal-pronoun declension paradigm** (Table 4, p. 211) with illustrative example
   sentences per case/person — a genuinely comprehensive single-table version not seen consolidated
   this way in prior Russian extractions.
4. A sample of the **verb-government tables** (pp. 182–199, "Глаголы, их формы и управление") pairing
   aspect pairs of verbs with the case (and preposition, where relevant) each governs — useful as
   grammar-mechanic data (case government constrains word order/collocation, relevant to later slang-
   mechanics analysis) even though the underlying verb list itself overlaps with dedicated verb
   dictionaries already in Wave 1 (`016`–`018`, *The Big Silver Book of Russian Verbs*).
5. A handful of dialogue excerpts illustrating **colloquial register/pragmatic formulas** (apologies,
   invitations, small talk) that show natural spoken usage patterns rather than bare paradigm forms.

**What was skipped as redundant, and why:**
- The noun/adjective/pronoun case-ending paradigm tables reproduced at the start of each of the six
  case chapters (e.g. pp. 6–8 nominative endings by gender/hardness of stem) — identical information,
  in less systematic form, to what Wave 1's dedicated reference grammars already tabulate.
- The hundreds of individual drill dialogues built from the book's "касса" (frame) vocabulary
  substitution lists — these deliberately reuse a small closed set of already-common vocabulary
  (city/metro/cultural proper nouns, everyday objects) in near-identical sentence frames across every
  chapter; extracting them item-by-item would just be bulk-reproducing drill material the coverage
  rule says to skip.
- The "Глаголы движения" (motion-verb) table (pp. 200–201) — this corpus already has a specialist
  motion-verb-with-prefixes reference (`028_russkie_glagoly_dvizheniya_s_pristavkami.md`); this book's
  table is a compressed subset of that same territory.
- The end-of-book test (Тест, pp. 202–210, 50 multiple-choice items) and its answer-key "matrices"
  (Контрольная/Рабочая матрица, pp. 208–210) — assessment material, not grammar/vocabulary content.
- Declension summary Tables 1, 2, 3, 5, and 6 (nouns, adjectives, and possessive/demonstrative
  pronouns) are referenced on p. 211 as printed on a separate foldout insert ("см. таблицы ... на
  вкладке") rather than on a regular numbered page; this insert was not located in the digitized PDF
  page sequence and so could not be extracted. Only Table 4 (personal pronouns), which is on a regular
  page, was captured.

## PDF-extraction notes

- **Real, clean Cyrillic text layer — no font-substitution cipher.** Unlike several other sources in
  this corpus's Wave 1 pass, `pdftotext` on this file produces directly legible Russian throughout;
  verified by reading dozens of widely-separated passages (preface, all six case chapters, appendix).
  No decode was needed.
- **Two printed pages scanned per PDF page (spread scanning).** `pdfinfo` reports 110 PDF pages, but
  the book's own table of contents and printed page numbers run to 213 — confirmed empirically by
  rendering PDF pages to images (e.g. PDF page 107 shows printed pages 210–211 side by side). This
  matches the "two-printed-pages-per-image spread" gotcha already flagged in the extraction spec; a
  naive `printed_page ≈ PDF_page + offset` estimate would have been wrong by roughly half.
- **Front-matter OCR scrambling.** The first few pages (half-title, copyright/CIP block, preface)
  show classic multi-column ABBYY FineReader scrambling — two overlapping copyright-page text blocks
  interleaved character-by-character (e.g. `Б» лгакова Л. П.За I арен ю И В., ] С, асных В В`) and a
  duplicated/interleaved preface paragraph. This is garbling of *layout*, not a character cipher — the
  underlying Cyrillic glyphs are correct, just extracted out of visual order from a cluttered page with
  overlapping text boxes. Did not affect the substantive chapter content, which is single-column and
  extracts cleanly.
- **Dense grid tables render as scanned images, not as OCR'd text.** The consolidated declension
  tables (pp. 208–211: test answer-key matrices, Table 4) do not appear in the `pdftotext` output at
  all — confirmed by rendering those pages to PNG and reading them visually. Table 4 (pronoun
  declension) was extracted this way; the checkerboard-pattern answer-key matrices were confirmed to
  be non-content (test-scoring aids) and correctly excluded.
- **No handwritten marginalia found** on any page inspected (rendered or OCR'd) — the copy digitized
  appears to be a clean, unmarked reference copy.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| в чём? / на чём? | in what? / on what? — locative question | interrogative + preposition | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | n/a | Governs prepositional case (П.п.); answers ГДЕ? (where, static location). p.177 |
| над чем? / под чем? / рядом с чем? / за чем? / перед чем? | above/under/beside/behind/in-front-of what? | preposition + interrogative | core | — | contemporary (2002) | — | — | grammar_reference | n/a | n/a | All govern instrumental case (Т.п.); static-location prepositions. p.177 |
| из чего? / с чего? / у чего? / около чего? / от чего? / до чего? / мимо чего? / напротив чего? | out of / off of / at / near / from / up to / past / opposite what? | preposition + interrogative | core | — | contemporary (2002) | — | — | grammar_reference | n/a | n/a | All govern genitive case (Р.п.); answer ОТКУДА? (source/origin) or static proximity. p.177 |
| к чему? / по чему? | toward / along what? | preposition + interrogative | core | — | contemporary (2002) | — | — | grammar_reference | n/a | n/a | Govern dative case (Д.п.); answer КУДА? (direction) or path-along. p.177 |
| справа (от чего?) / слева (от чего?) / в центре чего? / в середине чего? | to the right of / to the left of / in the center of / in the middle of | adverb + preposition phrase | core | — | contemporary (2002) | — | — | grammar_reference | n/a | n/a | Genitive-governing spatial-relation adverbs, static (ГДЕ?). p.179 |
| справа от чего? / слева от чего? / в середину чего? | (direction) to the right/left of / into the middle of | adverb + preposition phrase | core | — | contemporary (2002) | — | — | grammar_reference | n/a | n/a | Same phrases but marking direction (КУДА?), also genitive-governing. p.179 |
| находиться / лежать / стоять / висеть | to be located / to lie / to stand / to hang | verb (imperfective, static-position) | core | — | contemporary (2002) | — | — | grammar_reference | n/a | n/a | Static-location verb set paired with П.п. (ГДЕ?). p.179 |
| положить / поставить / повесить | to lay/place / to stand up (place) / to hang (place) | verb (perfective, placement) | core | — | contemporary (2002) | — | — | grammar_reference | n/a | n/a | Placement-action verb set paired with В.п. (КУДА?). p.179 |
| (по)йти / (по)ехать / повернуть / бежать | to go (on foot) / to go (by vehicle) / to turn / to run | verb (motion) | core | — | contemporary (2002) | — | — | grammar_reference | n/a | n/a | Directional motion verbs, В.п. government for destination. p.179 |
| в четверть первого / в половине первого / без четверти час | quarter past twelve / half past twelve / quarter to one | time expression (idiom) | core | — | contemporary (2002) | — | — | grammar_reference | n/a | n/a | Clock-time idioms combining В.п./Р.п.; illustrates that Russian clock time is expressed from the *next* hour ("first" = 1:00), not the preceding one. p.178 |
| в среду / во вторник / на этой неделе / в этом месяце / в этом году / в этом веке | on Wednesday / on Tuesday / this week / this month / this year / this century | time expression | core | — | contemporary (2002) | — | — | grammar_reference | n/a | n/a | Case/preposition selection varies by the size of the time unit (в + В.п. for weekday, на + П.п. for week, в + П.п. for month/year/century) — a systematic pattern this book tabulates explicitly. p.178 |
| в прошлом месяце / в прошлом году / на прошлой неделе / в прошлую среду | last month / last year / last week / last Wednesday | time expression | core | — | contemporary (2002) | — | — | grammar_reference | n/a | n/a | "Prошлый/будущий" (last/next) + time-unit noun, case governed by the same unit-size pattern as above. p.178 |
| заниматься / интересоваться / увлекаться / пользоваться / гордиться / любоваться / восхищаться чем? | to occupy oneself with / be interested in / be keen on / use / be proud of / admire / be delighted by what? | verb (imperfective) + instrumental government | core | — | contemporary (2002) | — | — | grammar_reference | n/a | n/a | Full instrumental-government verb set from the appendix's verb table, p.182ff.; e.g. заниматься спортом "to do sports." |
| работать / стать кем? | to work as / to become (occupation) whom? | verb + instrumental government | core | — | contemporary (2002) | — | — | grammar_reference | n/a | n/a | Predicate-instrumental construction: "он работает инженером" (he works as an engineer), "он хочет стать историком" (he wants to become a historian). p.182 |
| заболеть / болеть чем? | to fall ill with / to be ill with (an illness) | verb + instrumental government | core | — | contemporary (2002) | — | — | grammar_reference | n/a | n/a | Illness named in instrumental: грипп, ангина. p.182 |
| знакомиться / здороваться / прощаться / встречаться / договариваться / советоваться / спорить с кем? | to get acquainted with / greet / say goodbye to / meet / arrange with / consult / argue with whom? | verb (reflexive, reciprocal) + с + instrumental government | core | — | contemporary (2002) | — | — | grammar_reference | n/a | n/a | Reciprocal/social verbs governing с + Т.п. rather than bare instrumental — a distinct government subpattern from the "чем?" set above. p.182 |
| резать / мыть / вытирать / чистить чем? | to cut / wash / wipe / clean with what (instrument) | verb + instrumental (instrumental-of-means) | core | — | contemporary (2002) | — | — | grammar_reference | n/a | n/a | Canonical instrumental-of-means use, paired with typical instrument nouns (нож, мыло, полотенце). p.181 |
| извини за опоздание! | sorry for being late! | fixed apology formula | colloquial | — | contemporary (2002) | — | — | grammar_reference | n/a | n/a | Illustrative colloquial dialogue formula (genitive/accusative-governing "извини за + В.п."); from a Genitive-chapter dialogue exercise, p.106. |
| давайте поиграем! | let's play (a game)! | fixed pedagogical-game formula | colloquial | — | contemporary (2002) | — | — | grammar_reference | n/a | n/a | The book's own recurring instruction-formula introducing a role-play communicative task; useful register marker for informal spoken-register invitations built on давайте + 1pl-future. |
| он, она, оно, они (склонение) | he, she, it, they (declension) | pronoun (personal, 3rd person) | core | — | contemporary (2002) | — | — | grammar_reference | n/a | plausible_unverified | Full paradigm from Table 4 (p.211, vision-read — dense grid not present in OCR text layer): И.п. он/она/оно/они; Р.п. его(у него)/её(у неё)/его(у него)/их(у них); Д.п. ему(к нему)/ей(к ней)/ему(к нему)/им(к ним); В.п. его(за него)/её(за неё)/его(за него)/их(за них); Т.п. им(с ним)/ею~ней(с нею~ней)/им(с ним)/ими(с ними); П.п. о нём/о ней/о нём/о них. Bracketed alt-forms show the н-prefixed variant used after a preposition (е→не, etc.), a rule this table states explicitly as a footnote. |
| я, ты, мы, вы (склонение) | I, you(sg), we, you(pl) (declension) | pronoun (personal, 1st/2nd person) | core | — | contemporary (2002) | — | — | grammar_reference | n/a | plausible_unverified | Same Table 4: И.п. я/ты/мы/вы; Р.п. меня/тебя/нас/вас; Д.п. мне/тебе/нам/вам; В.п. меня/тебя/нас/вас; Т.п. мной(мною)/тобой(тобою)/нами/вами; П.п. обо мне/о тебе/о нас/о вас. No preposition-triggered н-alternation for 1st/2nd person (that rule is 3rd-person-only). |

## Grammar points

### The book's dialogue/"кассы" (frame) teaching method

The preface (pp. 3–5) states the book's own pedagogical design, useful context for reading any
dialogue example drawn from it: each of the six case-chapters opens with a compact reference table of
that case's noun/adjective/pronoun endings, then moves to exercises built around "кассы" (lit.
"cash-register drawers," i.e. substitution frames) — a fixed dialogue skeleton with a paradigm slot
that a student fills from a supplied word list, e.g. the model `А: [Name] дома? Б: Нет, он поехал в
[destination].` with a column of interchangeable names/destinations to substitute in. Each chapter
closes with a summary dialogue or text integrating all of that case's core meanings. The authors are
explicit that this is a frame/schema-based ("фреймовый") presentation, not a rote paradigm drill — the
substitution lists are deliberately built from "the most typical communicative situations and
frequent communicative fragments of Russian speech" (paraphrased, p.3), which is why the drill
vocabulary itself (Moscow geography, everyday errands, family small talk) recurs so heavily across
chapters rather than introducing much genuinely new lexis.

### Preposition-by-case functional map for space (Приложение, pp. 176–179)

The appendix organizes spatial prepositions by a two-axis grid: which case each preposition governs,
and which of three questions it answers — КУДА? (where to — destination), ГДЕ? (where — static
location), or ОТКУДА? (where from — origin). Genitive-governing prepositions (из, с, у, около, от, до,
мимо, напротив) all answer ОТКУДА?; dative-governing (к, по) answer КУДА?; instrumental-governing
(над, под, рядом с, за, перед) and prepositional-governing (в, на) both answer ГДЕ? — with в/на
additionally reusable for КУДА? when paired with a directional verb instead of a static one (this
book's own worked example: "иду в парк" vs. "нахожусь в парке," both "в" + different case per
motion-vs-location, a fusional-case hallmark). The same three-way axis is reused for a parallel
"справа/слева/в центре/в середине" (right of/left of/in the center of/in the middle of) subset that
is genitive-governing regardless of the КУДА?/ГДЕ? distinction — only the surface phrase changes
(справа от чего? → в середину чего?), not the case.

### Preposition/case selection for time expressions scales with the size of the time unit

The appendix's time-expression table (p.178) shows a systematic pattern not framed this way in prior
Wave-1 extractions: the preposition-and-case pairing for "this/last/next X" changes depending on how
large the time unit X is. Weekday uses в + В.п. (в среду). Week uses на + П.п. (на этой неделе).
Month, year, and century all use в + П.п. (в этом месяце / в этом году / в этом веке). "Ago" (назад)
takes bare accusative with no preposition (неделю назад). This is a clean illustration of how Russian
case/preposition choice for time is grammaticalized by semantic category (unit-size) rather than
being lexically idiosyncratic per word — directly relevant to later slang-mechanics analysis of which
grammatical slots are "fixed" (rule-governed) versus open to reanalysis/innovation.

### Verb-government tables (Приложение, "Глаголы, их формы и управление," pp. 182–199)

A large reference table (not reproduced in full — a compact per-verb government list, closer to a
dictionary than connected prose, and largely redundant with the dedicated verb-dictionary sources
already in Wave 1) pairing each verb's aspectual pair (НСВ/СВ) with the case (and preposition, where
one is required) it governs. The genuinely useful pattern the sampled entries surface: government
splits along a semantic line between (a) verbs of engagement/attitude taking bare instrumental
(заниматься, интересоваться, гордиться — "to be occupied by/interested in/proud of" something,
conceptually treating the object as an instrument/means of the mental state) and (b) reciprocal
social verbs taking с + instrumental (знакомиться, здороваться, встречаться — "to become acquainted
with/greet/meet" someone, treating the interlocutor as a co-participant "with" whom the action is
mutually performed) — a case-marking distinction between "instrument of an internal state" and
"co-participant of a mutual action" that the underlying case system encodes structurally rather than
through separate vocabulary.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `../../00_Reference_Extraction_Spec.md`.
