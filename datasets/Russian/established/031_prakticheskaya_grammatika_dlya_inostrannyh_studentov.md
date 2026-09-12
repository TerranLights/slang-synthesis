# Russian — Established Vocabulary/Grammar: Practical Syntax for Foreign Students (full book)

**Source:** И.Б. Игнатова, С.М. Андреева, С.Б. Мордас, *Практическая грамматика: Учебное пособие
для иностранных студентов* (Petrovskaya Academy of Sciences and Arts / St. Petersburg–Belgorod,
2006), 184 pp. Full book covered (all 12 Разделы, pp. 5–184). Clean text layer throughout —
`pdftotext -layout` produced correct, unscrambled Cyrillic with no font-substitution cipher and no
stress-mark corruption; no vision-reading was needed and no marginalia (handwritten or otherwise)
was found anywhere in the scanned/rendered pages checked.

**Coverage note / "non-redundant supplement" scope decision.** This book is a *syntax-of-the-
complex-sentence* teaching grammar aimed at foreign students at the "First Certification Level" —
structurally very different from the paradigm-focused reference grammars already in Wave 1. Each
of its 12 sections (Разделы) states one grammatical pattern via a single model sentence or a small
comparison table, then drills it through pages of near-identical transformation exercises using a
narrow, repeated vocabulary set (mostly names like Антон/Марта/Виктор and everyday-life nouns).
Per the coverage rule, **the drills themselves are skipped almost entirely** — only the rule
statements, the comparison/paradigm tables, and the case-government/valency data embedded in them
are extracted.

Cross-checked against the 15 sources already in Wave 1 (see `../00_Extraction_Checklist.md`)
before extracting each section:

- **Раздел XII (Глаголы движения — motion verbs, pp. 149–184, this book's longest section)
  is almost entirely redundant with `028_russkie_glagoly_dvizheniya_s_pristavkami.md`**, a
  dedicated 673-entry motion-verb specialist reference covering all 16 prefixes (this book only
  covers 10) with fuller idiom coverage, an aspectual layer, and register notes that this book
  lacks entirely. **Skipped**: the unprefixed-pair conjugation drills, the по-/при-/у-/в-/вы-/
  под-/от-/до-/про-/пере-/за-/об- prefix-by-prefix exercise blocks, and the transitive-motion-verb
  (нести–носить/вести–водить/везти–возить) conjugation and prefixed-form drills — all of this
  vocabulary and prefix-meaning content already exists in `028` in greater depth. **Kept**: this
  book's own case-government/rection table (see Grammar points below) — `028` is organized as a
  per-prefix vocabulary+idiom list and does not tabulate the governed case/preposition per prefix
  the way this book's own summary table does, so that angle is genuinely non-redundant even though
  the underlying prefix inventory is not new.
- **Раздел VIII (aspect) and Раздел V/IX (participles/gerunds) partially overlap** general aspect
  and participle-formation coverage already present across the Wave 1 grammars (Timberlake, Wade,
  Schaum's, the SEELRC reference grammar, etc.), but this book's own tight pedagogical
  systematizations — the 4-way НСВ/СВ meaning-contrast table, the infinitive-governing-verb lists
  by aspect, the imperative-aspect pragmatic-function table, and the participle↔gerund
  "motivating-link-with-the-predicate" substitutability rule — are compact, clean formulations not
  seen in quite this shape in prior extractions, so they are kept as genuinely useful restatements/
  systematizations rather than being treated as new grammar per se.
- **Раздел I–IV, VI, VII, X, XI (indirect speech, active/passive, comparison/short adjectives,
  conditional, concessive, participle/gerund synonymy, causal-consequential) are this book's real
  strength**: none of the Wave 1 sources organize these specific syntactic-connective systems
  (это/чтобы reported-speech transforms, the для+Р.п. ↔ чтобы+infinitive purpose-clause
  equivalence, если/если бы real-vs-irreal conditionals, хотя/несмотря на то что/вопреки
  concessives, потому что/так как/поэтому/благодаря/из-за/от causal contrasts) into this kind of
  compact means-of-expression comparison table. These are extracted in full as new content.

---

## Vocabulary

This book is not vocabulary-dense — its running text reuses a small, deliberately repeated
teaching-drill vocabulary (Антон, Марта, Виктор, Хуан, etc. plus everyday nouns) that carries no
new lexical information. The table below captures only vocabulary items that carry genuine new
information: near-synonym verb pairs whose case-government/valency the book spells out explicitly
(a systematic semantic-discrimination exercise not reducible to a single gloss), plus a handful of
connective words/phrases whose meaning is the whole point of a section.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| учить – выучить | to study/learn (memorize) — govs что: stихотворение, слова, правило, урок | verb (aspectual pair) | core | — | contemporary (source published 2006) | — | — | grammar_reference | n/a | n/a | Contrasted explicitly with изучать below; p. 67–68 |
| изучать – изучить | to study (acquire knowledge of a field/subject) — govs кого?/что?: Пушкина, литературу, язык; "изучать что-либо по чему" (by a textbook); also "to investigate scientifically" (на ком?/чём? — on animals, via a microscope) | verb (aspectual pair) | core | — | contemporary (source published 2006) | — | — | grammar_reference | n/a | n/a | p. 67–68 |
| писать – написать | to write (graphic signs; a text; to compose/author) — govs что: буквы, письмо, роман; писать (для кого? о чём? куда?) | verb (aspectual pair) | core | — | contemporary (source published 2006) | — | — | grammar_reference | n/a | n/a | p. 69 |
| описывать – описать | to describe (a person/place/event in speech or writing; sense 2: to systematically describe a collection's features for scientific purposes) — govs кого?/что?; кому?/чему?; в чём?/на чём? | verb (aspectual pair) | core | — | contemporary (source published 2006) | — | — | grammar_reference | n/a | n/a | Distinguished from писать–написать: писать creates a text, описывать is the descriptive content within it; p. 69 |
| просить – попросить | to ask/request (a favor, or an object) — govs кого? о чём? чего? у кого? | verb (aspectual pair) | core | — | contemporary (source published 2006) | — | — | grammar_reference | n/a | n/a | p. 70 |
| спрашивать – спросить | to ask (a question, to find something out) — govs кого? что? у кого? о ком/чём? где? чем? (спросить глазами/взглядом — to ask with one's eyes) | verb (aspectual pair) | core | — | contemporary (source published 2006) | — | — | grammar_reference | n/a | n/a | Minimal pair vs. просить: "Больной попросил воды" (asked FOR water) vs. "Больной спросил, не осталось ли воды" (asked WHETHER there was water left); p. 70–71 |
| смотреть – посмотреть | to look/watch — govs на кого/что?, во что? (бинокль), через/сквозь что?, за кем/чем? (to look after/take care of), or "относиться к чему-л. с т.з." (to regard, evaluate) | verb (aspectual pair) | core | — | contemporary (source published 2006) | — | — | grammar_reference | n/a | n/a | 4 distinct senses tabulated; p. 71–72 |
| осматривать – осмотреть | to examine/inspect thoroughly (a patient, a place, a building) — govs кого?/что?; за сколько времени?; с какой целью? | verb (aspectual pair) | core | — | contemporary (source published 2006) | — | — | grammar_reference | n/a | n/a | p. 72 |
| рассматривать – рассмотреть | (sense 1) to make out/discern with strained vision — govs в чём? на чём? через что?; (sense 2) to deliberate/consider formally (a proposal, application) — govs где?: в комиссии, на собрании | verb (aspectual pair) | core | — | contemporary (source published 2006) | — | — | grammar_reference | n/a | n/a | Same root triad смотреть/осматривать/рассматривать deliberately contrasted in one exercise set; p. 72–73 |
| благодаря (чему?/кому?) + Д.п. | "thanks to" — marks a cause that *helps/enables* the action (answers "благодаря чему?") | preposition | core | — | contemporary (source published 2006) | — | — | grammar_reference | n/a | n/a | Contrasted with из-за below; governs dative, unlike most Russian causal prepositions | 
| из-за (чего?/кого?) + Р.п. | "because of" — marks a cause that *hinders/prevents* the action (answers "из-за чего?") | preposition | core | — | contemporary (source published 2006) | — | — | grammar_reference | n/a | n/a | p. 131 |
| от + Р.п. (causal) | "from/out of" — marks an involuntary physiological/emotional cause (от радости, от волнения, от страха) | preposition | core | — | contemporary (source published 2006) | — | — | grammar_reference | n/a | n/a | Three-way от/из-за/благодаря causal-preposition drill, p. 132–133 |

## Grammar points

### Indirect speech transforms (Раздел I, pp. 6–11)

Direct-to-indirect speech conversion is organized by original sentence type, each governing a
different connective:
- A statement → **что**: «Я позвоню тебе вечером» → он сказал, что он позвонит вечером.
- A yes/no question → **ли** (inverted word order, verb first): «Ты видел фильм?» → спросил,
  видел ли он фильм.
- A wh-question → the question word itself becomes the subordinator: «Куда ты поедешь?» → спросил,
  куда я поеду.
- A command/request → **чтобы** + past-tense verb (not infinitive): «Посмотри фильм» → сказал,
  чтобы он посмотрел фильм.

The book flags что vs. чтобы as the single most common learner confusion point in this system
(Упражнение 7 is a fill-in-the-blank drill specifically on that pair) — что reports a fact, чтобы
reports a directive.

### Active/passive correspondence (Раздел III, pp. 17–29)

**Imperfective**: Active `Им.п.(кто?) + В.п.(что?) + V-НСВ` ↔ Passive `Им.п.(что?) + Тв.п.(кем?) +
V-НСВ-ся`, unchanged across present/past/future (Студент читает текст ↔ Текст читается
студентом). The book notes a pragmatic wrinkle: when the speaker cares only about the fact that an
action occurs, not who performs it, Russian often prefers a subject-less active plural ("В
лаборатории проводят эксперимент") over either full active or passive framing — both are marked as
natural, more natural than a heavier passive construction, when the agent is unspecified/irrelevant.

**Perfective**: formed with the short passive participle (not a ся-form), agreeing in number/gender
with the derived subject. Three suffix classes, each with worked examples and (for -ен-/-ён-) a
consonant-alternation table keyed off the 1st-person-singular non-past form to avoid a common
learner error:
- **-н-** — from -ать/-ять/-еть infinitives: прочитать → прочита-н.
- **-ен-/-ён-** — from -ить infinitives / consonant-stem past tems: получить → получ-ен; a full
  consonant-alternation table is given (т/ч, т/щ, д/ж, д/ж/жд, з/ж, с/ш, б/бл, п/пл, в/вл), e.g.
  встретить → я встречу → встреч-ен; купить → я куплю → купл-ен.
- **-т-** — a small closed class: открыть → откры-т, начать → нача-т, взять → взя-т, понять →
  поня-т.

### Comparative and superlative adjective formation, short adjectives (Раздел IV, pp. 30–41)

- **Comparative**: `-ее/-ей` for most adjectives (stress on the suffix if the stem is disyllabic,
  on the stem if polysyllabic); `-е` for stems in -г-, -к-, -х-, -д-, -т-, -ст- with an obligatory
  consonant alternation (г/ж: дорогой→дороже; к/ч: крепкий→крепче; х/ш: тихий→тише; д/ж:
  молодой→моложе; ст/щ: чистый→чище), with some -к-/-ок- adjectives dropping the suffix entirely
  along with the alternation: низкий→ниже, короткий→короче. Suppletive/irregular set: плохой→хуже,
  хороший→лучше, маленький→меньше, большой→больше, тонкий→тоньше.
- **Superlative**: `-ейш-` (unstressed-final-consonant stems) or `-айш-` (stems in -г-, -к-, -х-,
  with the same alternation as comparatives): красивый→красивейший, строгий→строжайший. Irregular
  set: хороший→лучший, плохой→худший, низкий→низший, маленький→малейший, большой→величайший.
- **Short-form adjectives**: agree in gender/number but don't decline; formed by stripping the full
  ending, with a fill vowel (-е-/-о-) inserted before a stem-final cluster depending on the
  preceding consonant's hardness/softness (молодой→молод, интересный→интересен, крепкий→крепок).
  Irregular short forms are listed as a closed exception set: большой→велик, злой→зол, маленький→
  мал, чужой→чужд, хитрый→хитёр, светлый→светел, острый→остёр.

### Participle formation (Раздел V, pp. 42–53)

Four participle classes, each tabulated with the deriving finite form and suffix:
- **Present active** (`-ущ-/-ющ-` from 1st-conjugation present stems, `-ащ-/-ящ-` from
  2nd-conjugation): читают→читающий, находятся→находящийся.
- **Past active** (`-вш-` from an infinitive/past stem ending in a vowel, `-ш-` from a
  consonant-final past stem): читал→читавший; нёс→нёсший, помог→помогший.
- **Present passive** (`-ем-` from 1st-conjugation, `-им-` from 2nd-conjugation): читают→читаемый,
  любят→любимый.
- **Past passive** (`-нн-`, `-енн-`, `-т-` — the same three-way split as the short passive
  participle above, just with the long/attributive `-нн-`/`-енн-` doubling instead of `-н-`/`-ен-`):
  прочитать→прочитанный, построить→построенный, закрыть→закрытый.

**Rule of thumb given for choosing between active/passive participle** (Упражнение 4 series):
if the noun being modified is the *doer* of the action, use active; if it is the *undergoer*, use
passive — the same который-clause each corresponds to is given as a paraphrase check (студент,
читавший книгу = который читал книгу).

### Conditional relations (Раздел VI, p. 55)

Three-way means-of-expression table:
- **при + abstract noun (Р.п.)** — names a condition under which an action can occur (При работе
  над текстом пользуйтесь словарем).
- **если** (real condition) — the subordinate clause names a condition the main clause's action
  depends on.
- **если бы** (irreal/potential condition) — names a desired or hypothetical condition; both
  clauses take the "бы + past tense" construction (Если бы у меня было время, я бы пришёл).

### Concessive relations (Раздел VII, p. 61)

Four-way means-of-expression table, contrasted with the causal/conditional systems above:
- **вопреки + Д.п.** — "despite" (predictions, expectations).
- **несмотря на + В.п.** — "despite/in spite of" (a noun phrase).
- **хотя** — subordinating conjunction ("although"), clause can precede or follow the main clause.
- **несмотря на то, что** — subordinating conjunction, synonymous with хотя but heavier/more formal.
- **пусть** — a concessive particle, listed but not worked in the exercises shown.

### Aspect: core meaning contrasts (Раздел VIII, pp. 76–90)

A compact 4-row НСВ-vs-СВ meaning-contrast table is the section's organizing device:

| # | НСВ (что делать?) | СВ (что сделать?) |
|---|---|---|
| 1 | states a fact of an action occurring (any tense) | states the *result* of an action that occurred/will occur |
| 2 | repeated/regular action | single, one-time occurrence, with a quantitative/qualitative evaluation of the result |
| 3 | ongoing process (duration: долго, весь день, 2 часа) | completeness (a) — done "in X time" (за + В.п.); or suddenness (b) — вдруг, неожиданно |
| 4 | simultaneous/parallel actions | sequential actions |

When НСВ and СВ co-occur in one sentence, НСВ marks the ongoing backdrop action against which the
СВ action (momentary/resultative) happens: "Когда он писал письмо, он вспомнил слова отца."

A related **duration-vs.-completion-time contrast** is drilled separately: НСВ + a bare duration
phrase (весь вечер, 2 часа) asks "Сколько времени?"; СВ + за + duration asks "За сколько времени?"
— Диего делал домашнее задание 2 часа (НСВ, process) vs. Диего сделал домашнее задание за 2 часа
(СВ, completed within that span).

**Aktionsart via prefix** (a further subsection, p. 92): several fixed prefixes layer an
Aktionsart meaning onto an otherwise-plain СВ derivation rather than a purely telic/perfective one:
- **за-** marks *inceptive* aspect (onset of a state/sound): заплакать, заболеть, запеть,
  замолчать, засмеяться.
- **по-** (from unidirectional motion verbs) also marks onset: пойти, побежать, полететь; separately,
  **по-** on non-motion verbs marks a *short* duration: поспать, постоять, поговорить.
- **про-** marks a *long/extended* duration: простоять, проговорить, просидеть, проболтать.

### Aspect in the infinitive (Раздел VIII, pp. 98–102)

A governing-verb-class table determines which aspect the dependent infinitive takes:
- **НСВ infinitive** follows: phasal verbs (начинать/начать, продолжать, кончать/кончить,
  переставать/перестать, бросать/бросить, прекращать/прекратить, приниматься/приняться);
  учиться/научиться, привыкать/привыкнуть, любить/полюбить, нравиться/понравиться, уметь;
  verbs of negative disposition toward the action (запрещать/запретить, уставать/устать,
  надоедать/надоесть, ненавидеть); words expressing prohibition/pointlessness (опасно, плохо,
  довольно, хватит, вредно, стыдно, незачем, бесполезно); and always after a negated modal
  (не надо, не нужно, не следует, не стоит).
- **СВ infinitive** follows: забыть, успеть, удаться, спешить — verbs about a single achieved (or
  failed) result.
- **нельзя** takes either aspect with a meaning split: **nельзя + НСВ** = prohibition ("Нельзя
  входить: там идёт собрание" — you may not, it's forbidden); **нельзя + СВ** = physical
  impossibility ("Нельзя войти, дверь закрыта на ключ" — you can't, it's physically blocked).

### Aspect in the imperative (Раздел VIII, pp. 103–108)

НСВ imperatives express: (1) durative/repeated actions ("Регулярно занимайтесь спортом!"),
(2) an invitation to perform an action ("Входите, раздевайтесь, садитесь!"), (3) urging someone to
begin/continue ("Теперь пишите!"), (4) urging a change in *manner* of an ongoing action ("Идите
быстрее!"), (5) granting permission ("Можно войти? — Входите!"). СВ imperatives express a single
concrete request/demand/order for one specific completed action ("Дайте, пожалуйста, словарь!",
"Закройте дверь!").

### Gerund (деепричастие) formation (Раздел IX, pp. 109–110)

- **From НСВ**: present-stem + -я (vowel-final stem: отвечают→отвечая) or -а/-я (consonant-final
  stem: говорят→говоря); a small -ся class adds -я-сь; a few -ть infinitives on -давать/-вставать
  keep -я off the infinitive stem itself (давая, вставая); быть → future-stem-based будучи (-учи
  suffix, unique to this verb in the modern language per the book).
- **From СВ**: past-stem + -в (окончил→окончив); reflexives take -вши-сь (научился→научившись);
  a small class of -ти infinitives (future-tense stem) take -я instead of -в (войти→войдя,
  принести→принеся).
- **A closed list of verbs with no gerund form in ordinary speech** is given: писать, хотеть, ждать,
  пить, мочь, петь, помочь, бежать, ехать, спать, казаться, есть, бить.

Gerunds from НСВ mark an unfinished action simultaneous with the main verb; gerunds from СВ mark a
completed action either preceding or following the main verb's action — illustrated with a minimal
pair (Отвечая на вопросы... vs. Ответив на вопросы...).

Gerund constructions can be paraphrased as when-, because-, if-, or though-clauses — the book
frames this explicitly as "деепричастные конструкции, соотносительные с придаточными
предложениями," with one worked example per relation type (temporal, causal, conditional,
concessive), each convertible in both directions.

### Participle/gerund synonymy — the "motivating link with the predicate" test (Раздел X, pp. 117–121)

A participle phrase can be replaced by a gerund only when the participle's action has a
*motivating* (explanatory/causal-in-effect) relationship to the sentence's main predicate — i.e.
when the participial clause functions like an implicit "because/when X, then Y." Where this link is
absent — the participle merely identifies which referent is meant, with no bearing on the
predicate — substitution is ungrammatical/nonsensical. Contrast given: "Задумавшийся Виктор не
услышал вопроса" → "Задумавшись, Виктор не услышал вопроса" (motivating: his being lost in thought
*explains* not hearing — substitution works) vs. "Живущий в Москве брат часто пишет мне" (merely
identifies which brother — *"Живя в Москве, брат часто пишет мне"* would wrongly imply living in
Moscow causes the letter-writing — substitution rejected).

### Causal-consequential relations (Раздел XI, pp. 122–148)

**In complex sentences**: потому что and так как are presented as synonymous cause-markers, but
with a word-order asymmetry — a так как-clause may either precede or follow the main clause, while
a потому что-clause always follows it. поэтому marks the *consequence*, and its clause always
follows the main clause (Стало темно, поэтому я зажёг свет.).

**In simple sentences**: three causal prepositions are systematically contrasted (see Vocabulary
table above for each's case government): благодаря + Д.п. (enabling cause), из-за + Р.п.
(hindering cause), от + Р.п. (involuntary physiological/emotional cause — от радости, от страха).

**Purpose-clause equivalence**: для + Р.п. (in a simple sentence) is presented as directly
convertible with чтобы + infinitive (in a complex sentence) — "Для понимания друг друга нужны
знания" ↔ "Чтобы понять друг друга, нужны знания" — with a drilled nominalization pattern (для
строительства ↔ чтобы строить) for converting между verb-derived abstract nouns and their
underlying infinitives.

**Via gerund constructions**: causal relations can also be expressed by a gerund clause (see
Раздел IX above) — treated as a third parallel means alongside the conjunction-based and
preposition-based systems, cross-referenced rather than re-explained here.

### Motion-verb prefix case government (Раздел XII, p. 167–168) — kept as non-redundant supplement

The book's own consolidated table ties each of its 10 covered prefixes to the case/preposition it
governs (not tabulated this way in `028`, which is organized as a per-prefix vocabulary+idiom list):

| Prefix | Core meaning | Question/preposition | Case |
|---|---|---|---|
| по- | onset of movement (no arrival implied) | куда? (в, на); к кому? (к) | В.п.; Д.п. |
| при- | arrival at destination | куда? (в, на); от кого?/куда? (от, из, с) | В.п.; Р.п. |
| у- | departure/long-term absence | откуда? (из, с); куда? (в, на) | Р.п.; В.п. |
| в-(во-) | movement inward | куда? (в) | В.п. |
| вы- | movement outward / brief absence | откуда? (из) | Р.п. |
| под-(подо-) | approach to an object | к кому/чему? (к) | Д.п. |
| от-(ото-) | movement away from an object | от кого/чего? (от) | Р.п. |
| до- | reaching a final goal | до кого/чего? (до) | Р.п. |
| про- | movement through/past; a covered distance; a bounded duration | через/сквозь что?; мимо кого/чего?; bare В.п. for distance | В.п.; Р.п. |
| пере- | movement from one side/place to another | через что?; bare В.п. | В.п. |
| за- | detour from the main route; brief visit; movement behind an object | куда? (в, на); за кем/чем? (за); к кому? (к) | В.п.; Т.п.; Д.п. |
| об-(обо-) | movement around/past; sequential visits to multiple points | вокруг кого/чего? (вокруг); bare В.п. | Р.п.; В.п. |

The remaining ~30 pages of Раздел XII (unprefixed-pair conjugation drills, per-prefix fill-in-the-
blank exercises, transitive нести/вести/везти-family conjugation and prefixation, and the
"переходные глаголы движения" object-case drills) duplicate `028`'s vocabulary and idiom coverage
and were not re-extracted; see the coverage note above.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`. All example sentences
above are single illustrative sentences reproduced from the source's own worked examples (not the
drill exercises), used here only to anchor the paraphrased grammar rule.
