# Russian — Established Vocabulary/Grammar: *Let's Speak Russian!* (Давайте говорить по-русски), Разделы 1–9 + selected Раздел 10 / Grammar Tables

**Source:** Глазунова О. И. (Glazunova, O. I.), *Давайте говорить по-русски. Учебник по русскому
языку* [*Let's Speak Russian! A Russian Language Textbook*], 5th stereotype ed., Moscow: Русский
язык, 2003 (1st ed. 1997, 2nd corrected ed. 2000). 336 pp. Intermediate/advanced conversational
Russian textbook, ISBN 5-200-03203-2. Source file: `source_reference/languages/Russian/Russian
Learning Pack [up-to-date as of 2012]/Vol 1 of 3/28.Let's Speak Russian! - Давайте говорить
по-русски.djvu` (160 DjVu pages, each page image a two-printed-page spread — ~320-336 printed
pages total). Pages covered in this pass: printed pp. 7–250 (Разделы 1–9, complete grammar
apparatus + representative vocabulary), p. 288–289 (Раздел 10, phonetics course — one wordplay
text sampled), pp. 290–291 (Грамматические таблицы — noun-ending tables sampled).

## Coverage note — extraction method and scope decisions

**DjVu text-layer is unreliable; this file is vision-read.** `djvutxt` on this file returns a
baked-in OCR text layer (visible via `djvudump` as a `TXTz` chunk per page) that garbles Cyrillic
into look-alike Latin/digit glyphs (e.g. "Глазунова О. И." → "fna3yHoBa O. H."; "говорить по-русски"
→ "rOBOpHTb nO-PyccKH"). Unlike the fixed 1:1 font-substitution ciphers found in some prior PDF
sources in this corpus, this is **not cleanly decodable**: the substitution is many-to-one and
context-dependent (e.g. the glyph "H" decodes to **both** и and н depending on context — confirmed
by cross-checking "говорить" [H→и] against "Глазунова" [H→н] in the same page's text layer). Per
the extraction spec's guidance for undecodable substitution, this file falls back to full
**vision-reading**: pages rendered via `ddjvu -format=ppm` → `PIL` PNG at half native resolution
(~1720×1184 px per spread), read directly. All rows below are vision-read; **no OCR/text-layer
extraction was used for any vocabulary or grammar content in this file.**

**Page-numbering drift.** The djvu-page-to-printed-page offset is not a single fixed formula across
the whole book — it drifted by −2 printed pages roughly three times over the book (evidently front
matter/illustration pages that don't carry a printed folio), stabilizing at `printed_left = 2×n − 8`
(where `n` = djvu page index) from roughly djvu page 83 onward, having started at `2×n − 2`. Located
empirically by checking header page numbers on each fetched spread rather than trusting a single
formula throughout — consistent with this project's prior "verify the offset empirically" finding
on other vision-read sources.

**Scope decision (comprehensive-but-not-exhaustive, stated explicitly per spec).** This is a 336-page
book; full page-by-page vocabulary extraction at that scale is impractical in one pass. What was
covered:
- **Every grammar point listed in the table of contents for Разделы 1–9** (24 points total) — each
  read directly from its own textbook page(s) and paraphrased below.
- **The vocabulary/phrase "boxes"** (tabular lexical-complex displays) that open or anchor each
  Раздел's topic (transport, food, appearance, art/architecture, telephone, medical, holidays) —
  these are the book's own deliberately curated core-vocabulary lists, not incidental dialogue words.
- **Footnoted "КОММЕНТАРИИ" glosses** encountered on the specific pages read (these are the book's
  own in-context idiom/vocabulary explanations and are high-value — several are colloquial idioms,
  not core vocabulary).
- **Раздел 10 (Фонетический курс, pp. 251–289)** — this is a phonetics/IPA-articulation course with
  low lexical yield; **only its closing page (288–289) was extracted**, because it contains a
  genuinely valuable segmentation/homophony wordplay text ("Несуразные вещи") directly relevant to
  slang-mechanics research (word-boundary reanalysis humor: *несу разные вещи* / *несуразные вещи*,
  *не сумел* / *несу мел*, *та марка* / *Тамарка*, *там арка* / *Тамарка*). The rest of Раздел 10 (IPA
  consonant/vowel articulation drills) was **not extracted** — it is pronunciation pedagogy, not
  vocabulary or slang-relevant grammar.
- **Грамматические таблицы (pp. 290–311)** — only the opening nominative/genitive noun-ending
  summary table (pp. 290–291) was sampled as a representative, condensed cross-reference; the full
  case-table run (accusative through prepositional, adjectives, pronouns) was **not extracted** in
  this pass given time budget — flagged here for a possible follow-up file.
- **Русско-английский словарь (p. ~312 onward, 2000+ entries)** — **deliberately skipped entirely.**
  A general-purpose alphabetical bilingual glossary of this scale is bulk vocabulary reproduction by
  its nature; extracting it item-by-item would violate the copyright-discipline rule against
  bulk-reproducing a vocabulary box, and it is not slang-specific (general core vocabulary, already
  well covered by other established/ files in this language folder).
- **Dialogue transcripts and drill exercises** were read for context but not transcribed — per the
  coverage rule, these mostly reuse vocabulary already captured in the same Раздел's lexical-complex
  box or comment footnotes.

**Follow-up flagged for a future dispatch:** a `025b_lets_speak_russian.md` covering the remainder of
Раздел 10's phonetics content (if judged worth it for stress/reduction patterns relevant to slang
pronunciation) and the full Грамматические таблицы case-ending run, would be a reasonable next chunk
if this book is revisited.

No handwritten marginalia was found on any page read — all content vision-read was clearly printed/
typeset matter.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| собирательные числительные (двое, трое, четверо...) | collective numerals ("two/three/four of," used with masc./neut. nouns, children, pluralia tantum) | numeral | core | — | contemporary (source pub. 2003) | — | — | grammar_reference | n/a | plausible_unverified | Раздел 1, p.19; used with людьми, детьми, and nouns lacking singular (сутки, ножницы) |
| -ся (постфикс) | reflexive/reciprocal/passive verb postfix | grammatical morpheme | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | Раздел 1, p.24; e.g. мыться "to wash oneself," встречаться "to meet (each other)" |
| ты / вы | you (informal singular) / you (formal or plural) | pronoun | core | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 1, p.17; T–V register system, textbook's own explicit note |
| пожалуйста | please / you're welcome | particle | core | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 1, p.27, drawn from an excerpted essay on cross-cultural confusion around the word's dual use |
| идти/ходить, ехать/ездить, etc. | verbs of motion (determinate/indeterminate pairs) | verb | core | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 2, p.36; foundational unidirectional/multidirectional motion-verb distinction |
| приставки (motion-verb prefixes: в-, вы-, при-, у-, etc.) | directional prefixes on motion verbs | grammatical morpheme | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | Раздел 2, p.57 |
| разбор слова по составу | morphological word analysis (root/prefix/suffix parsing) | metalinguistic term | technical | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | Раздел 2, p.60; the textbook's own term for morpheme-breakdown exercises |
| универмаг | department store | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 2 shopping vocabulary, p.77 |
| одевать/одеть vs. надевать/надеть | to dress (someone) vs. to put on (clothing) | verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | Раздел 3, p.84; classic learner confusion pair, textbook devotes a full grammar point to distinguishing them |
| такой / тот, сам / самый | "such"/"that (one)"; "-self" (emphatic) / "the very" | pronoun/particle | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | Раздел 3, p.88 |
| сравнительная степень (прилагательных/наречий) | comparative degree of adjectives/adverbs | grammatical category | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | Раздел 3, p.94 |
| совершенный / несовершенный вид | perfective / imperfective verbal aspect | grammatical category | core | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 4, p.100; central Russian verb-system distinction |
| превосходная степень | superlative degree | grammatical category | core | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 4, p.112 |
| действительные / страдательные причастия | active / passive participles | grammatical category | core | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 4, p.121 |
| приготовить (готовить/приготовить) | to prepare/cook | verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | Раздел 4 food-vocabulary box, pp.96–99 |
| энергичный человек | energetic person | adjective phrase | core | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 5 character-description drill, p.158 |
| рассеянный | absent-minded, scatterbrained | adjective | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 5, p.158; describing a person's character flaw casually |
| лаять | to bark (of a dog) | verb | core | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 5, p.158, anchor for an anecdote's punchline |
| терять голову | to lose one's head / to panic | idiom (verb phrase) | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 5, p.158; idiom explicitly flagged for pre-teaching before the anecdote that uses it |
| будить/разбудить, просыпаться/проснуться | to wake (someone) / to wake up (oneself) | verb | core | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 5, p.158 |
| деепричастие / деепричастный оборот | (Russian) adverbial participle / gerund clause | grammatical category | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | Раздел 5, p.138 |
| частицы не и ни | negative particles "не" and "ни" | particle | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | Раздел 5, p.144 |
| очень, совершенно, достаточно, немного | very, completely, sufficiently, a little (degree adverbs) | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | Раздел 5, p.154 |
| зрительный зал, партер, амфитеатр, бельэтаж, ярус, ложа | auditorium, orchestra/stalls, amphitheatre section, dress circle, tier, box (theatre seating terms) | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 6 theatre vocabulary box, p.160 |
| постановка | production, staging (of a play/opera/ballet) | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 6, p.161 footnote, glossed from ставить/поставить |
| БДТ | Bolshoi Drama Theatre (abbreviation) | proper noun (initialism) | technical | — | contemporary | Saint Petersburg | local | grammar_reference | n/a | verified | Раздел 6, p.161 footnote |
| действительный/страдательный оборот речи | active-voice / passive-voice construction | grammatical category | core | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 6, p.162 |
| что служит чем / что служит для чего | "X serves as Y" / "X serves for/to Y" (function/purpose qualification construction) | grammatical construction | core | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 6, p.176; used for art/architecture critique register |
| зодчий | architect (native Russian synonym for the Greek-derived "архитектор") | noun | literary | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 6, p.177 footnote; textbook explicitly flags it as a Russian synonym of a borrowed word |
| благодаря / из-за | thanks to (positive cause) / because of (often negative cause) | preposition | core | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 6, p.179; textbook explicitly contrasts benefaction-vs-blame connotation |
| заложить (закладывать/заложить) | to found, lay the foundation of | verb | literary | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 6, p.184 footnote, from a text on the Piskaryovskoye Memorial Cemetery |
| братская могила | mass/common grave (for war dead) | noun | literary | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 6, p.184 footnote |
| скорбный | mournful, sorrowful | adjective | literary | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 6, p.184 footnote, glossed as печальный |
| алло | hello (telephone-answering only) | interjection | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 7 telephone-etiquette box, p.186 |
| позовите (попросите) к телефону | "please call [X] to the phone" | fixed phrase | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 7, p.186 |
| нас разъединили | "we got disconnected/cut off" | fixed phrase | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 7, p.186 |
| вы ошиблись номером | "you have the wrong number" | fixed phrase | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 7, p.186 |
| последний из могикан | "the last of the Mohicans" (used for "the very last one") | idiom | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 7, p.197 footnote, glossed explicitly as meaning "самый последний" |
| как без рук, сама не своя | "helpless, like without hands"; "not herself" (beside herself, distraught) | idiom | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 7, p.197 footnote |
| выходить из себя | to lose one's temper, fly into a rage | idiom (verb phrase) | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 7, p.197 footnote |
| не тяни душу | "don't drag it out / spit it out already" (stop making me suffer waiting) | idiom | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 7, p.197 footnote |
| неопределённые местоимения (-то, -нибудь, кое-) | indefinite pronouns formed with particles -то ("some [specific but unknown]"), -нибудь ("any, whichever"), кое- ("some [known to speaker but unspecified]") | pronoun | core | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 7, p.188; -либо flagged as the formal/scientific-register synonym of -нибудь |
| выражение цели (для, ради, во имя, с целью, в целях, чтобы) | expressing purpose: "for," "for the sake of," "in the name of," "with the aim of," "in order to" | grammatical construction | core | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 7, p.198; ради/во имя flagged as marking an elevated, exalted purpose vs. neutral для |
| прямая и косвенная речь | direct and reported (indirect) speech | grammatical category | core | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 7, p.204 |
| болеть/заболеть (чем) | to be sick/fall sick (with an illness) | verb | core | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 8 medical vocabulary box, p.211 |
| выписывать/выписать рецепт | to write/issue a prescription | verb phrase | core | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 8, p.211 |
| делать/сделать укол (прививку) | to give an injection / vaccination | verb phrase | core | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 8, p.211 |
| градусник | thermometer | noun | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 8, p.226 footnote, glossed as a colloquial synonym of термометр |
| безличные предложения | impersonal sentences (no grammatical subject) | grammatical category | core | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 8, pp.216, 220; two-part grammar treatment, covers both weather/state impersonals (знобит, тошнит) and modal impersonals (нужно, надо, нельзя) |
| выражение условия (если) | expressing condition with "если" | grammatical construction | core | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 8, p.227 |
| праздновать/отпраздновать, отмечать/отметить | to celebrate, to mark/observe (a holiday) | verb | core | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 9 holiday-vocabulary box, p.232 |
| поздравлять/поздравить (с чем) | to congratulate (someone on something) | verb | core | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 9, p.232 |
| Масленица | Maslenitsa (pre-Lenten pancake festival) | proper noun | core | — | contemporary | Russia | national | grammar_reference | n/a | verified | Раздел 9, p.233 text, ancient custom of seeing off winter and welcoming spring |
| наряжать/нарядить | to decorate/dress up (e.g. a New Year's tree) | verb | core | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 9, p.234 footnote |
| ещё чего! | "no way! / like hell!" (expressing refusal/disagreement) | idiom (interjection) | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 9, p.244 footnote, textbook explicitly flags it as "разговорная фраза" (colloquial phrase) expressing disagreement or refusal |
| выражение уступки (хотя, несмотря на то что, пусть/пускай, как ни, сколько ни) | expressing concession: "although," "despite the fact that," "let/may," "no matter how," "however much" | grammatical construction | core | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 9, pp.235–237; textbook notes хотя is the colloquial-register default, несмотря на то что the bookish/formal-register synonym |
| знаки препинания (точка, вопросительный/восклицательный знак, запятая, многоточие) | punctuation marks (period, question/exclamation mark, comma, ellipsis) | metalinguistic term | technical | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 9, p.244 |
| несуразный | absurd, nonsensical | adjective | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 10, p.288–289 wordplay text "Несуразные вещи," built on the homophone pair несу разные вещи / несуразные вещи |
| ага | yeah, uh-huh (colloquial affirmative) | interjection | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 10, p.289 footnote, glossed as "= да" |
| постой | wait, hold on | interjection | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 10, p.289 footnote, glossed as "= подожди" |
| некогда мне | "I have no time" | idiom | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 10, p.289 footnote |
| ну тебя | "leave me alone / to hell with you" (mild dismissal) | idiom | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 10, p.289 footnote, glossed as "оставь меня в покое" |
| частица то (emphatic-то) | emphatic particle "-то" attached to a word to flag it as the speaker's point of focus | grammatical morpheme | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | Раздел 10, p.289 footnote, textbook's own explicit metalinguistic gloss: marks "the most important words from the speaker's point of view" |

## Grammar points

### Genitive case in combination with numerals (Раздел 1, p.16)
Numerals govern different noun cases depending on the final digit: 1 → nominative singular; 2–4 →
genitive singular; 5+ → genitive plural (with the usual exceptions for compound numerals ending in
1–4). Paraphrased from the textbook's own paradigm tables rather than quoted verbatim.

### Collective numerals (Раздел 1, p.19)
Двое, трое, четверо, etc. are used instead of the ordinary numerals два/три/четыре specifically with:
masculine/neuter animate nouns referring to people, personal pronouns, nouns that exist only in the
plural (сутки "24-hour period," ножницы "scissors"), and the words дети/люди. They are not used with
feminine nouns denoting people (one says "три женщины," never "*трое женщин").

### Verbs with the postfix -ся (Раздел 1, p.24)
The -ся postfix marks reflexive (мыться "wash oneself"), reciprocal (встречаться "meet each other"),
and passive (строиться "be built") readings depending on the specific verb and context — the textbook
frames this as one morphological device covering three distinct semantic functions, disambiguated
only by context and the verb's own lexical meaning.

### Verbs of motion (Раздел 2, p.36)
The core determinate/indeterminate motion-verb pairs (идти/ходить, ехать/ездить, бежать/бегать,
плыть/плавать, лететь/летать, нести/носить, вести/водить, везти/возить) — determinate verbs describe
motion in one direction at one specific time; indeterminate verbs describe habitual, repeated, or
multi-directional motion.

### Motion verbs with prefixes (Раздел 2, p.57)
Directional prefixes (в-/вы-, при-/у-, под-/от-, за-, про-, пере-, до-) attach to the indeterminate
motion-verb stem to derive perfective/imperfective aspectual pairs with specific spatial meaning
(e.g. войти "enter," выйти "exit," приехать "arrive," уехать "leave").

### Word-formation analysis / разбор слова по составу (Раздел 2, p.60)
The textbook's own method for parsing a word into its constituent morphemes (prefix–root–
suffix–ending), applied here specifically to prefixed motion verbs to make the compositional meaning
visible to learners.

### Imperative mood (Раздел 3, p.71)
Formation and usage of the Russian imperative, including softened/polite request forms.

### Verbs of motion in figurative meaning (Раздел 3, p.80)
Motion verbs (идти, ходить, бежать, etc.) used non-literally — e.g. "идёт дождь" (it's raining),
"время идёт" (time passes) — a semantic extension of the core motion-verb system covered earlier.

### Одевать/одеть vs. надевать/надеть (Раздел 3, p.84)
Одевать/одеть takes a person as its direct object ("одеть ребёнка" — to dress a child); надевать/
надеть takes an item of clothing ("надеть пальто" — to put on a coat). A frequent learner confusion
point the textbook devotes a dedicated section to.

### Такой/тот, сам/самый; наречие так (Раздел 3, p.88)
Такой ("such a") vs. тот ("that [aforementioned] one"); сам (emphatic "-self," e.g. "я сам сделал" —
"I did it myself") vs. самый (superlative-forming "the very," e.g. "самый лучший" — "the very best");
так as a manner adverb ("so, in this way").

### Comparative degree of adjectives and adverbs (Раздел 3, p.94)
Formation of comparatives via the -ее/-ей suffix (быстрее) and the small set of suppletive/irregular
comparatives (лучше, хуже, больше, меньше), plus the compound comparative with более.

### Perfective and imperfective verbal aspect (Раздел 4, p.100)
Aspect (not tense) distinguishes a completed, result-focused action (perfective) from an ongoing,
repeated, or process-focused one (imperfective) — realized lexically via prefixation or suppletion
rather than via a dedicated tense inflection. Central to Russian's fusional/aspectual verb system.

### Superlative degree (Раздел 4, p.112)
Formed either analytically with самый + adjective (самый интересный) or synthetically with the
suffix -ейш-/-айш- (интереснейший) — the textbook notes the synthetic form is more literary/bookish
in register than the analytic one.

### Active and passive participles (Раздел 4, p.121)
Active participles (читающий "reading," читавший "having read") describe the agent performing an
action; passive participles (читаемый "being read," прочитанный "having been read") describe the
patient undergoing it — covered as the participial counterpart to the active/passive voice system
elaborated further in Раздел 6.

### Constructions with быть in the present tense (Раздел 5, p.132)
Russian normally omits быть ("to be") in present-tense predication (Он врач — "He is a doctor," no
copula); the textbook covers the specific constructions where an explicit present-tense form is
nonetheless required or idiomatic.

### Деепричастие / деепричастный оборот (Раздел 5, p.138)
The adverbial participle (deeprichastie) expresses a secondary, simultaneous or sequential action by
the same subject as the main verb, without its own tense marking (e.g. "читая книгу, она улыбалась" —
"reading the book, she smiled"). Formed from imperfective stems (-я/-а) or perfective stems (-в/-вши).

### Particles не and ни (Раздел 5, p.144)
Не is the standard negating particle; ни intensifies negation in a context that already has не
elsewhere in the clause (никто не пришёл — "nobody came," lit. "not-anyone not came") or forms
universal-quantifier expressions with -ни (кто ни, где ни — "whoever," "wherever").

### Degree adverbs очень, совершенно, достаточно, немного, etc. (Раздел 5, p.154)
A paradigm of intensity/degree adverbs graded from "a little" to "completely," with notes on which
collocate naturally with which adjective classes (совершенно pairs with absolute/non-gradable
adjectives; очень with gradable ones).

### Active and passive voice constructions (Раздел 6, p.162)
When the active-voice predicate is imperfective, the passive equivalent uses a -ся-suffixed verb form
(исполняют → исполняются); when the active-voice predicate is perfective, the passive equivalent
uses the short-form passive participle instead (представили → (был) представлен). This aspect-
dependent choice of passive strategy is presented as a rule, illustrated with parallel tense-marked
example columns rather than reproduced verbatim here.

### Constructions for qualifying an object/phenomenon (Раздел 6, p.173)
"Что служит чем" ("X serves as Y") points to a potential-use/designation reading; "что служит для
чего" (+ infinitive or deverbal noun) qualifies an object by the specific function/purpose it's
designed for. Presented via architecture-vocabulary example sentences (building materials, purpose
of structural elements).

### Expression of cause and effect in a simple sentence (Раздел 6, p.179)
Cause can be expressed with the prepositions благодаря ("thanks to," carries positive/favorable
connotation from the speaker's standpoint) and из-за ("because of," typically carries a negative
connotation) — both govern the dative/genitive respectively and are explicitly contrasted for their
differing evaluative coloring, not treated as free variants.

### Indefinite pronouns with particles -то, -нибудь, кое- (Раздел 7, p.188)
-То marks a specific but unidentified referent known to exist ("кто-то позвонил" — "someone [a
specific person] called"); -нибудь marks free-choice indifference ("кто-нибудь" — "anyone, whoever it
may be"); кое- marks a referent known to the speaker but deliberately left vague. -Либо is flagged as
the scientific/formal-register synonym of -нибудь (какие-либо замечания).

### Expression of purpose (Раздел 7, p.198)
Для + genitive (neutral purpose/designation); ради and во имя (elevated, "for the sake of," used for
high-minded or noble purposes, stylistic synonyms of для); чтобы + infinitive (subordinate purpose
clause, dropped when the main-clause verb is itself a motion verb and subjects coincide, e.g. "Мы
приехали в Россию изучать русский язык"); с целью / в целях (formal/scientific register, + infinitive
or deverbal noun).

### Direct and indirect (reported) speech (Раздел 7, p.204)
Direct speech reproduces the speaker's exact words (with dash- or quote-punctuation conventions
detailed by position relative to the reporting clause); indirect speech reports content in the
narrator's own words, requiring pronoun/verb-person shifts and the conjunction что (for statements)
or чтобы (for reported requests/commands).

### Impersonal sentences, Part I (Раздел 8, p.216)
Sentences with no possible grammatical subject (no nominative-case noun): used for uncontrollable
physical/psychological states (меня знобит "I have chills," мне хочется "I feel like [doing]"), for
describing weather/ambient conditions (похолодало "it got colder"), and via predicative adverbs for
describing a room's or environment's state (в комнате душно "it's stuffy in the room").

### Impersonal sentences, Part II (Раздел 8, p.220)
Extends the impersonal pattern to нет/не было/не будет ("there isn't/wasn't/won't be" + genitive) and
to modal impersonals (можно, нельзя, нужно, надо, необходимо, (не) стоит, (не) следует + infinitive) —
covering both existential negation and deontic/permission modality within the same impersonal
syntactic frame.

### Expression of condition in a complex sentence (Раздел 8, p.227)
Conditional clauses formed with если ("if") for real/hypothetical conditions, distinguished from
counterfactual conditionals by verb mood/tense within the если-clause.

### Expression of concession (Раздел 9, pp.235–237)
Хотя and несмотря на то что both introduce a concessive clause whose content would logically block
the main clause but doesn't in practice; хотя is the colloquial-register default (can co-occur with
но in the main clause), несмотря на то что is more typical of bookish/written registers. Пусть/
пускай, and как/сколько + particle ни, form an alternative concessive pattern that additionally
carries the speaker's emotional coloring (regret, irritation, or conviction). In a simple sentence,
concession is expressed with несмотря на, независимо от, or вопреки (+ dative), the latter three
being markedly more formal/scientific in register than the хотя-clause pattern, which dominates in
speech.

### Punctuation rules in Russian (Раздел 9, p.244)
A systematic table of Russian punctuation marks (period, question mark, exclamation mark, comma,
ellipsis) each paired with its governing rule and an example — comma placement around clause-initial/
medial/final vocatives, between unconjoined coordinate elements, and around coordinated elements
joined by contrastive а/но/однако or by repeated и...и/да...да/ни...ни/или...или are the rules
specifically illustrated on the pages read.

### Homophony-based wordplay ("Несуразные вещи") (Раздел 10, p.288–289)
Not a formal grammar point in the textbook's own terms, but a genuinely useful phonetic/lexical
finding for slang-mechanics purposes: the textbook presents a short comic dialogue (attributed to
A. Shibayev) exploiting word-boundary reanalysis at normal speech tempo, where phonetically identical
strings parse into entirely different meanings depending on segmentation: *несу разные вещи* ("I'm
carrying various things") / *несуразные вещи* ("nonsensical things"); *несу мел* ("I'm carrying
chalk") / *не сумел* ("[I] didn't manage to"); *ему же надо будет* ("he'll need it") / *ему жена
добудет* ("his wife will get it for him"); *та марка* / *там арка* / *Тамарка* (a stamp / an arch /
the name "Tamarka," all near-homophones). The textbook frames this explicitly as a demonstration that
"phonetic differences are erased at fast speech tempo and meaning becomes clear only from context" —
directly relevant background for any slang-formation mechanism built on segmental reanalysis or
punning homophony.

### Noun-ending paradigm: nominative and genitive singular/plural (Грамматические таблицы, pp.290–291)
A condensed cross-reference table (not reproduced verbatim here per copyright discipline) giving
nominative-singular endings by gender/stem-hardness (masc. hard consonant/-й; fem. -а/-я; neut. -о/
-е, plus the mixed-declension -мя nouns and indeclinable borrowed neuters like метро, пальто, такси,
интервью — explicitly noted as not changing by case at all) and genitive-singular/plural endings,
including the partitive genitive -у/-ю alternate ending for mass nouns in small quantities (чашка
чая/чаю) and the mobile genitive-plural zero-ending pattern for feminine/neuter nouns (газета →
газет, окно → окон) versus the -ов/-ей endings for most masculines.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `../../00_Reference_Extraction_Spec.md`.
