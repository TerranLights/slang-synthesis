# Russian — Established Vocabulary/Grammar: The Verb (Aspect continued) through Word Order

**Source:** Terence Wade, *A Comprehensive Russian Grammar*, 3rd edition (Blackwell/Wiley-Blackwell,
2011). PDF pages 321-632 (this is the second half of the book; a sibling extraction, `established/002`,
covers PDF pages 1-320 — do not duplicate that range). Printed page numbers run roughly 285-596
(PDF page = printed page + 36, confirmed empirically against running headers). Chapters covered here:
the tail of §254 "Meanings of verbal prefixes," §255-283 (aspect usage), Reflexive Verbs, Impersonal
Constructions, The Passive Voice, The Conditional and Subjunctive Moods, Constructions Expressing
Obligation/Necessity/Possibility, Verbs of Motion, Participles, Gerunds, The Adverb, The Preposition,
The Conjunction, The Particle, and Word Order (§§254-484). The book's back matter — Glossary,
Bibliography, Subject Index, Word Index (roughly PDF pages 568-632) — was checked and contains no
extractable target-language grammar/vocabulary content (indices and a glossary of grammatical
terminology only); it is excluded as out of scope for the coverage rule.

**Coverage note / scope decision (auditable):** This is a single ~247-printed-page span covering many
verb-mechanics chapters plus several large closed-word-class chapters. Per the coverage rule's
"comprehensive-but-not-exhaustive" principle:
- **Closed word classes were extracted exhaustively** — every distinct verbal prefix (§254), primary
  preposition, adverbial/secondary preposition (§401-453), conjunction (§454-467), and particle
  (§468-474) the source lists is captured as its own vocabulary row, because for these categories the
  *inventory itself* is the vocabulary (there are finitely many, and each is a genuine lexical item).
- **Open-class illustrative examples were sampled, not bulk-reproduced.** Some sections (verbal
  prefix meanings, verbs of motion, participle/gerund formation) illustrate a single grammatical
  pattern with 2-6 near-identical example verb pairs. Per the coverage rule ("repeated drill exercises
  and example sentences that don't introduce new vocabulary or grammar... are skipped") and the
  copyright discipline against bulk-reproducing vocabulary boxes, 1-3 representative pairs per
  sub-pattern were kept rather than every example verb listed; this is flagged per section below where
  it applies, not silently.
- **Every distinct grammar point (numbered section, §254-484) is paraphrased**, even where its
  vocabulary yield is thin or overlaps a prior aspectual concept.

**PDF extraction gotcha — stress-mark corruption (new pattern for this project, worth flagging for
future Russian sources):** This PDF has a genuine text layer (`pdftotext` extracts real text, not
garbled OCR noise), but the font used for **stressed vowels** (Russian pedagogical texts mark stress
with an accent over a vowel) is corrupted: the accented-vowel glyphs extract as digits, blank spaces,
or stray punctuation instead of the correct Cyrillic vowel — e.g. printed `вы́сыпа́ться` extracts as
`в1спаться`, `просыпа́ть/проспа́ть` extracts basically intact except the accent mark's host vowel is
sometimes dropped or replaced (`засиде́ться в гостя́х` → `засидться в гост х`). The *unaccented*
letters of a word are reliably correct; only the specific vowel carrying a stress mark is at risk of
being wrong or missing. This is a narrower version of the "fixed font-substitution cipher" gotcha in
`00_Reference_Extraction_Spec.md` — no single consistent offset was found (several different
corrupted glyphs appear: `1`, `#`, `)`, `"`, `!`, blank), so it was not decoded; entries below reflect
the word's non-stressed letters read directly from the text layer, with the specific missing/uncertain
letter restored from context/known vocabulary where confidently inferable and left as a gap marker
`(?)` where not. This does not affect grammar-point paraphrase quality (explanatory prose is unaccented
and extracts cleanly) but does affect a handful of vocabulary-row spellings; flagged per-row in Notes
where a specific letter was reconstructed rather than read directly.

No handwritten marginalia was found in this range — this source has a real text layer throughout the
extracted range and no vision-reading was required, so the marginalia guard does not apply here.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| вы- | perfective prefix: exhaustive/completive action (continuation of §254 item 3, begun in sibling `002`) | verbal prefix | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | Always stressed as perfective prefix (per source note); stressed only in вы́глядеть 'to look' as imperfective prefix. Page 285/pdf321. |
| до- | perfective prefix: completion of an already-begun action; achievement of a hard-won result | verbal prefix | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | e.g. дожива́ть/дожи́ть до ста́рости 'to live to old age'; договори́ться 'to come to an agreement'. p.285. |
| за- | perfective prefix: movement behind; process covering an area; absorption in an action (often detrimental, reflexive); acquisition; fastening/securing; spoiling by excess | verbal prefix | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | Six distinct submeanings listed — richest prefix in this range. e.g. закла́дывать ру́ки за́ спину 'to put one's hands behind one's back'; засиде́ться в гостя́х 'to outstay one's welcome'; завоева́ть 'to conquer'; застегну́ть 'to fasten (a coat)'; закорми́ть щенка́ 'to overfeed a puppy'. pp.285-286. |
| из(о)-/ис- | perfective prefix: extraction/selection; action affecting the whole of an object | verbal prefix | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | избра́ть 'to elect'; исключи́ть 'to exclude, expel'; изорва́ть руба́шку 'to tear a shirt all over' (pf. only). p.286. |
| на- | perfective prefix: action directed onto a surface; action performed to the point of satisfaction; quantity/accumulation | verbal prefix | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | нажа́ть (на) кно́пку 'to press a button'; нае́сться 'to eat one's fill'; нарва́ть цвето́в 'to pick some flowers'. p.286. |
| над(о)- | perfective prefix: superimposition; detaching part of a surface | verbal prefix | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | надстро́ить эта́ж 'to add a storey'; надкуси́ть гру́шу 'to take a bite out of a pear'. p.286-287. |
| недо- | perfective prefix: shortfall (opposite of excess — cross-referenced against §254 item 13(v), "pre-") | verbal prefix | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | недооце́нивать/недооцени́ть 'to underrate'; недосоли́ть ка́шу 'not to put enough salt in the porridge'. p.287. |
| о-/об-/обо- | perfective prefix: action affecting many objects/people; detailed comprehensive action; action directed over a whole area; error; endowment with/acquisition of a quality or state; outdoing; deception | verbal prefix | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | Seven submeanings — second-richest prefix. e.g. опроси́ть студе́нтов 'to canvas student opinion'; обсуди́ть 'to discuss'; окле́ить сте́ны обо́ями 'to wall-paper'; оговори́ться 'to make a slip of the tongue'; обесси́ть vs. облегчи́ть 'to lighten, relieve'; обогна́ть 'to overtake'; обману́ть 'to deceive'. Source notes some verbs carry the prefix only in the perfective, e.g. вдове́ть/овдове́ть 'to be widowed'. pp.287-288. |
| обез-/обес- | perfective prefix: deprival (bookish register) | verbal prefix | literary | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | обесце́нить 'to devalue'. Explicitly marked bookish by the source. p.288. |
| от(о)- | perfective prefix: moving/receding a certain distance; detachment; reversal of an action | verbal prefix | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | отста́ть от други́х 'to lag behind the others'; оторва́ть листо́к 'to tear off a sheet'; отвы́кнуть от куре́ния 'to get out of the habit of smoking'. p.288. |
| пере- | perfective prefix: movement across; redoing; division; action affecting many objects; excess; reciprocal action; outdoing | verbal prefix | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | Seven submeanings. перепры́гнуть (че́рез) кана́ву 'to jump across a ditch'; перекра́сить 'to repaint'; перепили́ть 'to saw through'; перегрузи́ть маши́ну 'to overload a vehicle'; перепи́сываться (impf. only) 'to correspond'; перекрича́ть толпу́ 'to shout down a crowd'. pp.288-289. |
| под(о)- | perfective prefix: movement/position under; approach; addition of substance/material; furtive/underhand action; supplementary action | verbal prefix | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | подложи́ть поду́шку под го́лову 'to place a pillow under one's head'; подде́лать 'to forge, counterfeit'; подслу́шать 'to eavesdrop'. pp.289-290. |
| пре- | perfective prefix: transformation; termination; excess (mainly bookish styles) | verbal prefix | literary | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | преобразова́ть 'to transform'; прекрати́ть 'to curtail'; превы́сить 'to exceed'. Explicitly marked bookish. p.290. |
| пред(о)- | perfective prefix: anticipation | verbal prefix | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | предви́деть (impf. only) 'to foresee'; предупреди́ть 'to warn, prevent'. p.290. |
| при- | perfective prefix: approach/arrival; attachment; addition; limited/partial action; accustoming | verbal prefix | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | приблизиться 'to approach'; приземли́ться 'to land'; привяза́ть соба́ку к де́реву 'to tie a dog to a tree'; привста́ть 'to half rise'; привы́кнуть к дисципли́не 'to get used to discipline'. pp.290-291. |
| про- | perfective prefix: through/past; harmful error | verbal prefix | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | пропусти́ть 'to miss, let past'; проспа́ть 'to oversleep, sleep in'. p.291. |
| раз(о)-/рас- | perfective prefix: separation/dispersal/disintegration/distribution; reversal of an action | verbal prefix | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | раздви́нуть занаве́ски 'to part the curtains'; разме́стить раке́ты 'to deploy missiles'; развяза́ть 'to untie'; разду́мать 'to change one's mind'. p.292. |
| с(о)- | perfective prefix: removal; descent; joining; joint feeling or action | verbal prefix | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | све́ргнуть самодержа́вие 'to overthrow an autocracy'; спусти́ться на морско́е дно 'to descend to the sea bed'; скрепи́ть 'to staple together'; сочу́вствовать (impf. only) 'to sympathize'. p.292. |
| у- | perfective prefix: removal; imparting a quality | verbal prefix | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | удали́ть о́пухоль 'to remove a tumour'; упрости́ть 'to simplify'. p.292-293. |
| добива́ться / доби́ться | to try to achieve / to achieve | verb (impf./pf. aspectual pair) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | One of a listed set of pairs (§257(3)(iii), p.298-299) where the imperfective denotes *attempt* and the perfective denotes *successful achievement* — a distinct aspectual subclass from the ordinary impf./pf. pairing. |
| дока́зывать / доказа́ть | to contend / to prove | verb (impf./pf. aspectual pair) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | Same attempt/achievement subclass, p.299. |
| лови́ть / пойма́ть | to try to catch / to catch | verb (impf./pf. aspectual pair) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | Same subclass, p.299. |
| реша́ть / реши́ть | to tackle / to solve | verb (impf./pf. aspectual pair) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | Same subclass, p.299. |
| сдава́ть / сдать (экза́мен) | to take / to pass (an examination) | verb (impf./pf. aspectual pair) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | Same subclass, p.299. |
| уверя́ть / уве́рить | to try to assure / to assure | verb (impf./pf. aspectual pair) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | Same subclass, p.299. |
| угова́ривать / уговори́ть | to try to persuade / to persuade | verb (impf./pf. aspectual pair) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | Same subclass, p.299. |
| начина́ть / нача́ть | to begin | verb (impf./pf. aspectual pair) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §278: mandatorily takes an imperfective infinitive complement ('verbs of beginning'). p.316. |
| принима́ться / приня́ться | to get down to (doing something) | verb (impf./pf. aspectual pair) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §278, verb of beginning. p.316. |
| стать | to begin (pf. only, in this construction) | verb | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §278, verb of beginning, perfective-only in this sense. p.316. |
| продолжа́ть | to continue | verb | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §278: verb of continuing, takes imperfective infinitive; the perfective продо́лжить instead takes a direct object, not an infinitive. p.316-317. |
| броса́ть / бро́сить | to give up (doing something) | verb (impf./pf. aspectual pair) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §278, verb of concluding. p.317. |
| конча́ть / ко́нчить | to finish | verb (impf./pf. aspectual pair) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §278, verb of concluding. p.317. |
| перестава́ть / переста́ть | to cease | verb (impf./pf. aspectual pair) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §278, verb of concluding. p.317. |
| прекраща́ть / прекрати́ть | to desist | verb (impf./pf. aspectual pair) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §278, verb of concluding. p.317. |
| включа́ть (impf. past) | 'switched on' (with implication it was later switched off again) | verb | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §259(2), p.302-303: one of a listed set of imperfective-past verbs whose distinctive submeaning is 'action and its reverse' — a genuine aspectual-semantic category, not just a random example list. |
| выключа́ть (impf. past) | 'switched off' (implying later switched on again) | verb | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | Same 'action and reverse' set, p.303. |
| закрыва́ть (impf. past) | 'closed' (implying later reopened) | verb | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | Same set, p.303. |
| класть (impf. past) | 'put down' (implying later picked up again) | verb | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | Same set, p.303. |
| ложи́ться (impf. past) | 'lay down' (implying later got up again) | verb | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | Same set, p.303. |
| надева́ть (impf. past) | 'put on' (implying later took off again) | verb | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | Same set, p.303. |
| поднима́ться (impf. past) | 'ascended' (implying later came down again) | verb | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | Same set, p.303. |
| спуска́ться (impf. past) | 'descended' (implying later went up again) | verb | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | Same set, p.303. |

## Grammar points

### §254 Meanings of verbal prefixes (tail, prefixes 3-21)

See the vocabulary table above for the full inventory. Russian perfectivizing prefixes are not
semantically empty markers of aspect alone — each carries one or more distinct lexical submeanings
(direction, degree, completeness, error, etc.) layered onto the base verb's meaning. A single prefix
regularly carries several unrelated submeanings (e.g. за- covers "movement behind," "process covering
an area," "absorption in an action," "acquisition," "fastening," and "spoiling by excess" as six
distinct, non-overlapping uses). Two prefixes (обез-/обес-, пре-) are explicitly marked by the source
as belonging mainly to bookish/literary registers rather than neutral core vocabulary. pp.285-293.

### §255 The imperfective and perfective aspects — general principles

The imperfective describes an action in progress, developing towards a goal, or several actions
happening simultaneously/in no fixed order — it "does not move events" but describes circumstance.
It combines naturally with conjunctions implying development (по ме́ре того́ как 'in proportion as',
чем...тем 'the...the', в то вре́мя как/пока́ 'while') and with adverbs marking duration. The perfective,
by contrast, emphasizes result and "moves events" — a sequence of perfectives in one sentence advances
the narrative step by step, each action completing before the next begins (illustrated: a man removes
his coat, sits down, and picks up a diary — three sequential perfectives). The perfective past can also
have present relevance (a "pure perfect" reading): Я забы́л 'I have forgotten/I forget', Он у́мер 'he
is dead (has died)'. p.293-295.

### §256 Aspect in the present tense

Russian's present tense has only the imperfective form (there is no perfective present — a "perfective
present-tense" form is grammatically future in meaning). It covers: actions in progress, habitual
actions, general/timeless statements, capabilities/qualities, near-future intention (especially with
verbs of motion: Сего́дня ве́чером иду́ в кино́ 'I'm going to the cinema this evening'), the "historic
present" (present tense used for vividness in past narration), the "continuous present" (an action
begun in the past and still ongoing — where English uses a present perfect or pluperfect), and reported
speech (Russian preserves the tense of the original direct utterance rather than "backshifting" as
English does — Он сказа́л, что лю́бит её 'he said he loved her', literally 'he said that he loves her';
using a past tense in the reported clause would instead imply the loving was itself in the past/no
longer true). p.295-298.

### §257 Aspect in the past tense

Durative past meanings are always imperfective. A distinct submeaning: imperfective past can denote
*endeavour* (attempt, possibly failed) with the perfective denoting *successful completion of that
same attempt* — a small closed set of pairs works this way (see vocabulary table: добива́ться/доби́ться
etc.), distinguishing this from the ordinary "action in progress vs. completed action" aspectual
contrast. For repeated past actions: imperfective is standard, reinforced optionally by бы́ло; secondary
imperfectives (a further derived form, e.g. съеда́ть alongside primary есть 'to eat') are preferred over
primary imperfectives in frequentative contexts because primaries carry durative connotations
unsuited to repetition. When counting repetitions: irregular/spaced-out repetition takes the
imperfective, but a rapid, tightly-clustered series of identical actions can be treated as one composite
action and takes the perfective (e.g. чи́ркнул дважды 'struck [a match] twice' — perfective, because the
two strikes are treated as one event). Verbs of beginning stay imperfective even under rapid repetition.
pp.298-300.

### §258 The imperfective past as "statement of fact" (констата́ция фа́кта)

A named submeaning: the imperfective past states that an action occurred at some point, with zero
elaboration of manner, time, place, or result — a bald "yes, it happened" (Вы звони́ли ему́? — Да,
звони́л. 'Did you ring him? — Yes, I did.'). This is especially common in vague-context questions,
whereabouts-checks, and reminders. As soon as the context is filled in (when, why, with what result),
the perfective takes over instead. pp.300-302.

### §259 Imperfective past denoting "an action and its reverse"

A distinct, closed-ish semantic category (see vocabulary table): certain imperfective-past verbs imply
not just that an action happened, but that its natural opposite subsequently happened too — Он
открыва́л окно́ can mean 'he opened the window (and has since closed it again)', versus perfective Он
откры́л окно́ 'he opened the window (and it is still open)'. This generalizes to any verb whose action
has a natural reverse, not just the listed closed set. pp.302-303.

### §260 Aspect when emphasis is on *who* performed an action

When a question or statement is really about the *identity* of the agent (rather than the action's
completion, since completion is already given/obvious from context), the imperfective is used: Кто мыл
посу́ду? 'Who washed the dishes?' (the dishes are clearly already washed — the question is about who
did it). The perfective instead appears when the *quality* of the result is stressed, or the verb denotes
"discovery" (Кто изобрёл ра́дио? 'Who invented radio?'), or the action was accidental/undesired (Кто
разби́л ча́шку? 'Who broke the cup?'). pp.303-304.

### §261 Imperfective past for a forthcoming/scheduled event

The imperfective past can denote that an event was *due* to happen (regardless of whether it did):
По́езд отходи́л в пять часо́в 'the train was due to leave at five'. p.305.

### §262 Negated verbs in the past

Negated imperfective = the action never happened at all; negated perfective = the action was attempted
but did not succeed, or an expected event failed to materialize (Меня́ никто́ не встре́тил 'no one met
me' — implying someone was expected to). Negated imperfective can also negate a perfective-implied
supposition (someone assumed you were fired; you correct them: Меня́ не уволня́ли, я ушёл сам 'I
wasn't dismissed, I left of my own accord'). pp.305-306.

### §263 Aspect in the future

Imperfective future = focus on the manner/progress of a future action; perfective future = focus on
expected result. Both can co-occur in one sentence, one imperfective framing an ongoing action, a
perfective completing within it: Когда́ я бу́ду проходи́ть ми́мо апте́ки, куплю́ табле́тки от ка́шля 'when
I'm passing the chemist's [impf.], I'll buy [pf.] some cough drops'. pp.306-307.

### §264 The "logical" future

Unlike English (which drops the future tense after "when," "as soon as," "before," "until," "after"),
Russian keeps an explicit future (imperfective or perfective) in these subordinate clauses: Когда́ вы
бу́дете ремонти́ровать маши́ну, не забу́дьте... 'when you're overhauling [future impf.] the car, don't
forget...'. p.307.

### §265 The future in reported speech

Reported speech preserves the future tense of the original direct utterance (parallel to §256(viii)'s
present-tense rule) rather than backshifting to a conditional, as English sometimes does. p.307-308.

### §266 The future expressing repeated actions

Repeated future actions are usually imperfective. A perfective future can instead stress the *sequential*
relationship between two repeated events (first X happens, then Y happens, every time) rather than
their simultaneity. A "historic perfective future" appears in literary/narrative styles for vivid rapid
repeated movements in past-frequentative contexts (Он то вздохнёт, то а́хнет 'she would now sigh, now
moan') — a stylistic device, not literal future tense. The perfective future can also express "constant
readiness" rather than genuine repetition: Он вам всегда́ помо́жет 'he'll always help you' (implying
readiness, not that helping recurs identically every time). pp.308-309.

### §267 The perfective future as a warning (colloquial)

First-person-singular perfective future can express a mock threat/warning in colloquial speech: Я тебе́
попо́рю! roughly 'I'll give you argue!' — an idiomatic, colloquial-register construction worth flagging
for the mechanics-analysis phase (a register-marked construction, not literal future meaning). p.309.

### §268 Aspect in questions

Questions about intended actions default to imperfective (Что вы бу́дете де́лать? 'what are you going to
do?') unless successful completion is specifically emphasized (Вы найдёте э́тот дом? 'will you find the
house?'). Ordering food defaults to perfective since the diner is expected to actually receive the
dish. Colloquial requests often use a negated verb form (Вы не ска́жете...? 'could you tell me...?'
literally 'won't you say'). pp.309-310.

### §269-275 Aspect in the imperative

The imperfective imperative covers general injunctions, frequentative instructions, and "continue
doing X" instructions (§269); the perfective covers ordering a single, specific action (§270), with
negated imperfective used to forbid an action. Both aspects can co-occur in one sentence (imperfective
forbidding, perfective ordering). The imperfective imperative is also used for exhortations, wishes, and
conventional/ritualized invitations (a flight attendant's "проходи́те, пожа́луйста" 'please move down the
aisle'; §271), while a more formal/professional register prefers the perfective for a specific
instruction (a doctor to a nurse). §272: the imperfective imperative is preferred when an instruction is
the expected, routine action in a given script (an exam invigilator's stock instructions), while
non-routine/one-off instructions take the perfective. §273: negative commands are usually imperfective,
*except* when the utterance is a warning against an inadvertent mishap (Не поскользни́сь! 'mind you
don't slip!'), which takes the perfective — often paired with смотри́! 'mind!'. §274: a repeated action
described by an explicit count ("twice," "several times") takes the perfective imperative even though
repetition is otherwise imperfective territory. §275: future perfectives, or a bare infinitive, can
express a peremptory/categorical command (Сиде́ть смирно! 'sit still!'). pp.310-314.

### §276-283 Aspect in the infinitive

The perfective infinitive names a single completed action; the imperfective names a repeated or ongoing
one, or simply names the action with no completion implied at all (§276). §277: imperfective infinitives
combine with verbs/expressions of habituation (привы́к встава́ть ра́но 'used to getting up early',
предпочита́ть 'to prefer'); perfective can appear even in frequentative contexts when the frequency
word attaches to a different word in the sentence, not the infinitive itself (Я всегда́ рад помо́чь 'I'm
always glad to help' — always modifies "glad," not "help"). §278: certain verb classes *mandatorily*
take the imperfective infinitive — verbs of beginning, continuing, and concluding (full list captured
in the vocabulary table above) — because these verbs are inherently about the internal
process/continuation of the complement action, which is exactly what the imperfective encodes. §279:
imperfective infinitive combines with expressions of inadvisability (не на́до, не сле́дует, бесполе́зно);
не до́лжен + imperfective = inadvisability, + perfective = supposition/expectation; not-perfective can
express advisability. Нельзя́ + imperfective = "forbidden," + perfective = "physically impossible" — a
sharp, testable minimal-pair distinction (Нельзя́ входи́ть 'you can't go in [it's forbidden]' vs. Нельзя́
войти́ 'you can't get in [door's locked]'). §280: a request/intention for a single completed action
takes a perfective infinitive complement; adding не between the main verb and the infinitive switches
it to imperfective (a request NOT to do something is about ongoing avoidance, not a completed act).
§281: infinitives after не хочу́ 'I don't want to' can take either aspect, imperfective preferred after
a categorical refusal; the impersonal reflexive не хо́чется virtually requires the imperfective. §282:
пора́ + imperfective = 'it's time to [begin]'; пора́ + perfective = 'it's necessary to [get something
done]' — again a minimal pair distinguished purely by aspect. §283: verbs of motion take an
imperfective infinitive complement when the goal-action is a process (пошла́ ста́вить ча́йник 'went to
put the kettle on'), perfective when its result is what's emphasized (пошёл почини́ть часы́ 'went to get
the clock mended [i.e., fixed]'). pp.314-320.

### §284 Reflexive verbs: conjugation

The reflexive particle -ся attaches after a consonant, -й, or an active participle; -сь attaches after
a vowel. Full present-tense, past-tense, and imperative paradigms are given for мы́ться 'to wash
(oneself)' and верну́ться 'to return' — a hard-stem first-conjugation-type and a soft-stem
second-conjugation-type reflexive, respectively. Note this is purely morphophonological (choice of
-ся/-сь is governed by what precedes it, not by meaning) — the *semantic* classes of reflexive verbs
(true reflexive, reciprocal, passive-in-meaning, etc.) are covered in the following sections (§285-293).
pp.320-321.

## Reflexive Verbs (§285-293) — Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| бри́ться/по- | to shave (oneself) | verb (reflexive, true) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §285(1), personal-grooming "true reflexive" set. p.321. |
| гото́виться/при- | to get ready, prepare oneself | verb (reflexive, true) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §285(1). p.321. |
| гримирова́ться/за- | to put on make-up | verb (reflexive, true) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §285(1). p.321. |
| завива́ться/зави́ться | to have one's hair waved | verb (reflexive, true) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §285(1). p.321. |
| кра́ситься/вы́-, по- | to dye one's hair | verb (reflexive, true) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §285(1). p.321. |
| кра́ситься/на- | to make up one's face | verb (reflexive, true) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §285(1) — note same base verb краситься pairs with different perfectives for two distinct senses (dye hair vs. apply makeup). p.321. |
| купа́ться/вы́-, ис- | to bathe (oneself) | verb (reflexive, true) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §285(1). p.321. |
| мы́ться/по-, вы́- | to wash (oneself) | verb (reflexive, true) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §285(1); also the conjugation-paradigm verb in §284. p.321. |
| обува́ться/обу́ться | to put on one's shoes | verb (reflexive, true) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §285(1). p.321. |
| одева́ться/оде́ться | to dress oneself | verb (reflexive, true) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §285(1). p.321. |
| переодева́ться/переоде́ться | to change (one's clothes) | verb (reflexive, true) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §285(1). p.321. |
| причёсываться/причеса́ться | to do one's hair, have one's hair done | verb (reflexive, true) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §285(1). p.321. |
| пу́дриться/на-, по- | to powder one's face | verb (reflexive, true) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §285(1). p.321. |
| раздева́ться/разде́ться | to get undressed | verb (reflexive, true) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §285(1). p.321. |
| разува́ться/разу́ться | to take off one's shoes | verb (reflexive, true) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §285(1). p.321. |
| умыва́ться/умы́ться | to wash one's hands and face | verb (reflexive, true) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §285(1). p.321. |
| броса́ться/бро́ситься | to rush | verb (reflexive, true) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §285(2)(i). p.321. |
| защища́ться/защити́ться | to defend oneself | verb (reflexive, true) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §285(2)(i). p.321. |
| прислоня́ться/прислони́ться | to lean | verb (reflexive, true) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §285(2)(i). p.321. |
| ложи́ться/лечь | to lie down | verb (reflexive, imperfective only) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §285(2)(ii): reflexive only in imperfective; the perfective лечь is not reflexive. p.321. |
| пересажа́ться/пересе́сть | to change places, trains, etc. | verb (reflexive, imperfective only) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §285(2)(ii). p.321. |
| сади́ться/сесть | to sit down | verb (reflexive, imperfective only) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §285(2)(ii). p.321. |
| станови́ться/стать | to (go and) stand | verb (reflexive, imperfective only) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §285(2)(ii). p.321. |
| усáживаться/усéсться | to settle down | verb (reflexive, both aspects) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | Note to §285: exceptionally reflexive in both aspects, unlike the pairs immediately above. p.321. |
| запаса́ться/запасти́сь | to stock up with | verb (semi-reflexive) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §286: "semi-reflexive" — action performed *for* rather than *to* oneself. p.321. |
| укла́дываться/уложи́ться | to pack | verb (semi-reflexive) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §286. p.321. |
| дели́ться/по- | to share | verb (reflexive, reciprocal) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §289(2); takes c + instrumental for the co-participant. p.323-324. |
| здоро́ваться/по- | to say hello | verb (reflexive, reciprocal) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §289(2). p.324. |
| мири́ться/по-, при- | to make it up (after a quarrel) | verb (reflexive, reciprocal) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §289(2). p.324. |
| обнима́ться/обня́ться | to embrace | verb (reflexive, reciprocal) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §289(2); subject must be plural absent c + instrumental. p.324. |
| объединя́ться/объедини́ться | to amalgamate | verb (reflexive, reciprocal) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §289(2). p.324. |
| проща́ться/прости́ться | to say goodbye | verb (reflexive, reciprocal) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §289(2). p.324. |
| сове́товаться/по- | to take advice | verb (reflexive, reciprocal) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §289(2). p.324. |
| совеща́ться (impf. only) | to consult | verb (reflexive, reciprocal) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §289(2). p.324. |
| срабо́таться (pf. only) | to achieve a good working relationship | verb (reflexive, reciprocal) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §289(2). p.324. |
| усла́вливаться/усло́виться | to agree | verb (reflexive, reciprocal) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §289(2). p.324. |
| целова́ться/по- | to kiss | verb (reflexive, reciprocal) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §289(2). p.324. |
| дра́ться | to fight | verb (reflexive, reciprocal/conflict) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §289(4), conflict-denoting reciprocal reflexive. p.324. |
| боро́ться/по- | to struggle | verb (reflexive, reciprocal/conflict) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §289(4). p.324. |
| руга́ться/по- | to abuse one another | verb (reflexive, reciprocal/conflict) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §289(4). p.324. |
| ссо́риться/по- | to quarrel | verb (reflexive, reciprocal/conflict) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §289(4). p.324. |
| боя́ться + gen. | to fear | verb (reflexive, reflexive-only, feeling) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §290(1): reflexive-only feeling verbs. p.325. |
| горди́ться + instr. | to be proud of | verb (reflexive, reflexive-only, feeling) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §290(1). p.325. |
| любова́ться/по- + instr./на + acc. | to admire | verb (reflexive, reflexive-only, feeling) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §290(1). p.325. |
| наде́яться на + acc. | to hope for, rely on | verb (reflexive, reflexive-only, feeling) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §290(1). p.325. |
| наслажда́ться + instr. | to revel in | verb (reflexive, reflexive-only, feeling) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §290(1). p.325. |
| нра́виться/по- + dat. | to please | verb (reflexive, reflexive-only, feeling) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §290(1). p.325. |
| опаса́ться + gen. | to fear | verb (reflexive, reflexive-only, feeling) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §290(1). p.325. |
| расплака́ться (pf. only) | to burst into tears | verb (reflexive, reflexive-only, feeling) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §290(1). p.325. |
| рассмея́ться (pf. only) | to burst out laughing | verb (reflexive, reflexive-only, feeling) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §290(1). p.325. |
| смея́ться/за- + dat./над + instr. | to laugh (at) | verb (reflexive, reflexive-only, feeling) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §290(1). p.325. |
| сомнева́ться/усомни́ться в + prep. | to doubt | verb (reflexive, reflexive-only, feeling) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §290(1). p.325. |
| улыба́ться/улыбну́ться | to smile | verb (reflexive, reflexive-only, feeling) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §290(1). p.325. |
| беспоко́иться/по- | to worry | verb (reflexive, feeling; has transitive non-reflexive counterpart) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §290(2); contrast Это меня́ беспоко́ит 'that concerns me' (transitive) vs. Я беспоко́юсь 'I am worried' (reflexive). p.325. |
| весели́ться/по- | to enjoy oneself | verb (reflexive, feeling) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §290(2). p.325. |
| волнова́ться/вз- | to get excited | verb (reflexive, feeling) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §290(2). p.325. |
| восхища́ться/восхити́ться + instr. | to be delighted | verb (reflexive, feeling) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §290(2). p.325. |
| печа́литься/о- | to grieve | verb (reflexive, feeling) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §290(2). p.325. |
| признава́ться/призна́ться в + prep. | to confess to | verb (reflexive, feeling) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §290(2). p.325. |
| пуга́ться/ис- + gen. | to be frightened | verb (reflexive, feeling) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §290(2). p.325. |
| ра́доваться/об- + dat. | to rejoice | verb (reflexive, feeling) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §290(2). p.325. |
| расстра́иваться/расстро́иться | to get distraught, upset | verb (reflexive, feeling) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §290(2). p.325. |
| серди́ться/рас- на + acc. | to get angry | verb (reflexive, feeling) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §290(2). p.325. |
| удивля́ться/удиви́ться + dat. | to be surprised | verb (reflexive, feeling) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §290(2). p.325. |
| проси́ться/по- | to apply | verb (reflexive, intense/purposeful action) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §291. p.325. |
| пыта́ться/по- | to attempt | verb (reflexive, intense/purposeful action) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §291. p.325. |
| стара́ться/по- | to try | verb (reflexive, intense/purposeful action) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §291. p.325. |
| стреми́ться (impf. only) | to strive | verb (reflexive, intense/purposeful action) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §291. p.325. |
| стуча́ться/по- | to knock (hoping to be admitted) | verb (reflexive, intense/purposeful action) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §291. p.325. |
| труди́ться/по- | to labour | verb (reflexive, intense/purposeful action) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §291. p.325. |
| высыпа́ться/вы́спаться | to have a good sleep | verb (reflexive, thoroughness) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §292(1). p.325-326. |
| доу́чиваться/доучи́ться | to complete one's studies | verb (reflexive, thoroughness) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §292(1). p.326. |
| наеда́ться/нае́сться | to eat one's fill | verb (reflexive, thoroughness) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §292(1). p.326. |
| напива́ться/напи́ться | to slake one's thirst / get drunk | verb (reflexive, thoroughness) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §292(1); dual meaning explicitly given by the source (neutral 'quench thirst' and colloquial 'get drunk'). p.326. |
| насмотре́ться (pf. only) | to look one's fill | verb (reflexive, thoroughness) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §292(1). p.326. |
| заду́мываться/заду́маться | to be lost in thought | verb (reflexive, absorption, за-) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §292(2). p.326. |
| засма́триваться/засмотре́ться | to be absorbed in looking at something | verb (reflexive, absorption, за-) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §292(2). p.326. |
| бода́ться | to butt (of cattle) | verb (reflexive, potential-to-act) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §293: reflexive denoting inherent potential/capacity to perform a (usually harmful) action — Коро́вы боду́тся 'cows butt'. p.326. |
| жа́литься/жечься | to sting (of nettles) | verb (reflexive, potential-to-act) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §293: source form is жжётся 'stings' (крапи́ва жжётся). p.326. |
| куса́ться | to bite (of dogs) | verb (reflexive, potential-to-act) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §293. p.326. |
| цара́паться | to scratch (of cats) | verb (reflexive, potential-to-act) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §293. p.326. |

### §285 The "true" reflexive

A relatively small closed category where the agent turns the action back on themselves — the source's
own core example set is personal grooming (shaving, washing, dressing, doing one's hair/makeup, etc.,
captured in full in the vocabulary table above). A second subset is reflexive only in the imperfective
aspect (ложи́ться/лечь, сади́ться/сесть, станови́ться/стать, пересажа́ться/пересе́сть) — the perfective
partner drops the reflexive marker entirely, an irregular pairing worth flagging for mechanics analysis.
Уса́живаться/усе́сться is exceptional in keeping -ся in both aspects. pp.320-321.

### §286 Semi-reflexive verbs

A small class describing an action performed *for* rather than *to* the agent (запаса́ться 'to stock up
with', укла́дываться 'to pack') — distinct from true reflexives semantically even though morphologically
identical. p.321.

### §287 Intransitive reflexives

The reflexive ending can convert a transitive verb into its intransitive counterpart: возвраща́ть 'to
return [something]' (transitive) vs. возвраща́ться 'to return [oneself/come back]' (intransitive).
Unlike English, which often uses one verb both transitively and intransitively ('she stops the bus' /
'the bus stops'), Russian systematically distinguishes the two, either lexically (different verb roots:
выра́щивать 'to grow [something]' vs. расти́ 'to grow [intransitive]') or via the reflexive suffix
(остана́вливать/остана́вливаться). All the intransitive-reflexive examples given can also be used
transitively without -ся. p.322.

### §288 Reflexive verbs with passive meaning

Reflexive suffixes on imperfective transitive verbs commonly express a passive meaning, normally with
a third-person subject: Симфо́ния исполня́ется (орке́стром) 'the symphony is performed (by an
orchestra)'. This "reflexive passive" is distinguished from the plain intransitive use by whether an
agent can be named (typically in the instrumental) — if an agent can be added, it's a true passive
reading, not merely intransitive. Critically, **this reflexive-passive construction is essentially
imperfective-only**; the perfective passive is instead expressed via a participle (cross-referenced to
§359(3), outside this range). pp.322-323.

### §289 Reciprocal meanings

A distinct semantic reflexive class denoting mutual/joint action (full closed vocabulary list captured
above). These combine with c + instrumental to name a co-participant, in which case the subject can be
singular (Я здоро́ваюсь/проща́юсь с ним 'I say hello/goodbye to him'); without c + instrumental the
subject must be plural (Друзья́ обняли́сь 'the friends embraced'). A conflict-denoting subgroup (дра́ться,
боро́ться, руга́ться, ссо́риться) works the same way. Reflexive verbs of motion prefixed раз- or с- can
likewise express joint/dispersive action (разбега́ться/разбежа́ться 'to disperse', слета́ться/слете́ться
'to congregate' — cross-referenced to §331 in the Verbs of Motion chapter). pp.323-324.

### §290 Reflexive verbs of feeling and attitude

Two subclasses: verbs that exist *only* as reflexives (боя́ться, горди́ться, наде́яться, etc.) versus
verbs that have a non-reflexive transitive counterpart with a related but distinct meaning
(беспоко́иться 'to worry' [reflexive, about oneself] vs. беспоко́ить 'to concern/trouble' [transitive,
someone/something else] — Это меня́ беспоко́ит 'that concerns me' vs. Я беспоко́юсь 'I am worried').
pp.325.

### §291 Reflexives of intense/purposeful action

A small set (доби́ться, принима́ться, проси́ться, пыта́ться, стара́ться, стреми́ться, стуча́ться,
труди́ться) denoting effortful or goal-directed action. p.325.

### §292 Reflexives emphasizing thoroughness

Mostly prefixed вы-, до-, or на- and denoting exhaustive/complete performance of an action
(вы́спаться 'to sleep one's fill', нае́сться 'to eat one's fill'). A related за- prefixed subgroup denotes
absorption in an activity (заду́маться 'to be lost in thought'). pp.325-326.

### §293 Reflexives denoting potential/capacity to act

A small, semantically tight set describing an inherent capacity (usually to cause harm): cows butt,
nettles sting, dogs bite, cats scratch — the reflexive here marks a standing property of the subject
rather than a one-off event. p.326.

## Impersonal Constructions (§294-299) — Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| вечере́ть | to draw towards evening (impersonal) | verb (impersonal, 3sg only) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §294: natural-process impersonal verb; past tense uses the neuter (вечере́ло). p.326. |
| моро́зить | to be frosty (impersonal) | verb (impersonal, 3sg only) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §294. p.326. |
| светáть | to grow light, dawn (impersonal) | verb (impersonal, 3sg only) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §294. p.326. |
| сквози́ть | to be a draught (impersonal) | verb (impersonal, 3sg only) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §294. p.326. |
| смерка́ться | to grow dark early evening (impersonal) | verb (impersonal, 3sg only) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §294. p.326. |
| темне́ть | to grow dark (impersonal) | verb (impersonal, 3sg only) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §294. p.326. |
| знобить (+ acc.) | to feel shivery, feverish | verb (impersonal, animate accusative) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §295(1): Петра́ зноби́т 'Petr feels shivery' — the experiencer is a grammatical accusative object, not a subject. p.327. |
| клони́ть ко сну (+ acc.) | to feel drowsy | verb phrase (impersonal, animate accusative) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §295(1). p.327. |
| лихора́дить (+ acc.) | to feel feverish | verb (impersonal, animate accusative) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §295(1). p.327. |
| рвать (+ acc.) | to vomit (impersonal) | verb (impersonal, animate accusative) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §295(1); perfective вы́рвало. p.327. |
| тошни́ть (+ acc.) | to feel sick | verb (impersonal, animate accusative) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §295(1); perfective стошни́ло. p.327. |
| тяну́ть (+ acc., друг к дру́гу) | to feel drawn (to each other) | verb (impersonal, animate accusative) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §295(1). p.327. |
| зуде́ть (+ acc.) | to itch, be itching (to do something) | verb (impersonal, animate accusative) | colloquial | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §295(1), figurative sense (itching to find out something). p.327. |
| нездоро́виться (+ dat.) | to feel off colour | verb (impersonal, reflexive, animate dative) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §295(2): reflexive impersonal with dative experiencer. p.327. |
| не рабо́таться (+ dat.) | to not feel like working | verb (impersonal, reflexive, animate dative) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §295(2). p.327. |
| не спа́ться (+ dat.) | to not feel sleepy | verb (impersonal, reflexive, animate dative) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §295(2). p.327. |
| хоте́ться (+ dat.) | to feel like (doing/having something) | verb (impersonal, reflexive, animate dative) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §295(2): Мне хо́чется пить 'I feel thirsty'. p.327. |
| везти́ (+ dat., в чём) | to be lucky (at something) | verb (impersonal, dative) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §297(1): Мне везёт в ка́рты 'I'm lucky at cards'. p.328. |
| повезти́ (+ dat.) | to have gotten lucky | verb (impersonal, dative, pf.) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §297(1). p.328. |
| удава́ться/уда́ться (+ dat.) | to succeed (in doing something) | verb (impersonal, dative) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §297(1). p.328. |
| доводи́ться/дове́стись (+ dat.) | to happen to, have occasion to | verb (impersonal, dative) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §297(1). p.328. |
| хвата́ть/хвати́ть (+ gen., + dat.) | to be sufficient/enough (of) | verb (impersonal, dative + genitive) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §297(2): the person appears in dative, the quantifiable item in genitive — Ему́ всегда́ не хвата́ет де́нег 'he's always short of money'. p.328-329. |
| недостава́ть (+ gen., + dat.) | to lack, be short of | verb (impersonal, dative + genitive) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §297(2). p.328. |

### §294 Impersonal constructions for natural processes

A closed set of 3rd-person-singular-only verbs describes weather/light/atmospheric processes with no
grammatical subject at all (not even "it" — Russian simply has no subject slot here): вечере́ет 'evening
is drawing in', моро́зит 'there's frost about', смерка́ется ра́но 'it gets dark early'. Past tense uses
the neuter form (as with any subjectless construction). p.326.

### §295 Impersonal constructions with an animate accusative or dative experiencer

Physical states, involuntary reactions, and urges are expressed with the affected person NOT as
grammatical subject, but as an accusative (знобит, тошнит, рвёт — physical symptoms) or dative (with
a reflexive verb: не спится, хочется — desires/moods) object of a subjectless verb. This is a
structurally important typological point: Russian systematically avoids treating the experiencer of an
involuntary physical/emotional state as a grammatical agent — a pattern any invented slang-synthesis
work modeling involuntary/altered states (intoxication, fear, possession, etc.) could productively
borrow or subvert. pp.326-327.

### §296 Impersonal constructions with an external force/agent

A distinct pattern for accidental natural-force events: the affected object appears in the accusative,
the causing force (lightning, flood, etc.) in the instrumental, with the verb in neuter past and no
subject: Да́чу зажгло́ мо́лнией 'the cottage was struck by lightning' (literally 'it struck the cottage
by-means-of lightning'). The agent can be omitted (Ло́дку кача́ло 'the boat was pitching') or, in an
alternative construction, promoted to nominative subject (Его́ уби́ла мо́лния 'lightning killed him').
The distinction between this construction and the ordinary 3rd-person-plural is aspectual/agentive:
neuter-singular = accidental (Его́ уби́ло в перестре́лке 'he was killed in a skirmish' — no one is to
blame), 3rd-plural = intentional (Его́ уби́ли в рукопа́шном бою́ 'he was killed in hand-to-hand combat' —
someone did it deliberately). pp.327-328.

### §297 Impersonal constructions of chance, success, sufficiency

Chance/luck/success impersonals (везёт, повезло́, удало́сь, довело́сь) take a dative experiencer;
sufficiency/insufficiency impersonals (хвата́ет, недостаёт) take dative for the person AND genitive for
the quantifiable item lacking. p.328-329.

### §298 Second-person-singular for generic "one"/"you"

Russian uses a bare 2nd-person-singular verb form (with no addressee necessarily meant) the way English
uses generic "you" or "one": Ко всему́ привы́каешь 'you/one can get used to anything'. The pronoun ты
can be added purely for rhetorical emphasis without narrowing the reference back to a specific
addressee. p.329.

### §299 Third-person-plural for unspecified agent ("they")

The bare 3rd-person plural (no pronoun) denotes action by an unspecified "authority" or unnamed third
party: Меня́ задержа́ли 'I was arrested [by them/the authorities]'. This can also be a purely
conventional plural referring to what is really a single unspecified person (Тебя́ спра́шивают 'someone
is asking for you') — distinguished from §298's 2nd-singular generic by register/stance: the 3rd-plural
"identifies with authority," the 2nd-singular "identifies with the individual" (the source's own
framing, illustrated with a school-exam anecdote). pp.329-330.

## The Passive Voice (§300-303)

**Vocabulary note:** this short chapter is almost entirely grammatical mechanism rather than new lexical
items — no substantive new vocabulary table beyond what's already captured; the example verbs used
(лови́ться, составля́ться, открыва́ться, покры́ться, напо́лниться, освети́ться, смени́ться, созда́ться,
разби́ться) are common core verbs already representative of patterns captured elsewhere in this file, so
per the coverage rule's redundancy-avoidance principle they are not re-tabled as separate rows.

### §300 The passive voice — introductory comments

Russian has four distinct ways of expressing passive meaning, unlike English's single be+participle
construction: (1) reflexive verbs, (2) 3rd-person-plural, (3) participles (§359-360(2), outside this
range), and (4) word order alone (§478(2)(i), outside this range). p.330.

### §301 Passive via imperfective reflexive verbs

An imperfective reflexive verb can express a passive meaning, with the agent optionally expressed in
the instrumental (Сме́та составля́ется бухга́лтером 'the estimate is being prepared by an accountant') or
omitted entirely. Ambiguity risk flagged by the source: an animate-subject reflexive is often instead a
"true" reflexive (Он мо́ется 'he is washing himself', not 'he is being washed') or a joint-action
reflexive (Пассажи́ры собира́ются 'the passengers are gathering') — genuine passive readings with
animate subjects do occur, but are the marked case, not the default (Геро́и награжда́ются госуда́рством
'heroes are rewarded by the state'). p.331.

### §302 Passive via third-person plural

Choosing 3rd-plural over the reflexive passive specifically foregrounds that a human agent is doing the
acting, even when unnamed: Магази́н открыва́ется 'the shop opens' (reflexive, agentless/process-focused)
versus Дверь открыва́ют 'the door is being opened [by someone]' (3rd-plural, agent-focused). p.331.

### §303 Perfective reflexives with passive meaning

Perfective passive meaning is normally carried by a participle, not a reflexive verb (participles are
covered in §339-366, later in this file) — but a semantically narrow set of perfective reflexives can
still express passive-like meaning: covering (покры́лись 'became covered'), filling (напо́лнился 'filled
[with]'), illuminating (освети́лись), and a handful of others (сменя́ться 'to be replaced/yield to',
создава́ться 'to be created/develop', разби́ться 'to get smashed'). Critically, **animate instrumental
agents are excluded from this perfective-reflexive-passive construction** — they require the participle
construction instead: Кружо́к созда́лся 'the club got set up' (agentless) is fine, but "Кружо́к созда́лся
ученика́ми" (intended: 'by the pupils') is ungrammatical; only Кружо́к был со́здан ученика́ми (participle)
works. This is a sharp, testable grammatical constraint. pp.331-332.

## The Conditional and Subjunctive Moods (§304-312)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| бы (particle) | conditional/subjunctive/hypothetical marker | particle | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | The single particle underlying every construction in this chapter: conditional mood, desire, subjunctive purpose, hypothesis, concession. Combines with a past-tense verb form to strip it of literal past-tense meaning. §304-312, pp.333-340. |
| чтобы (conjunction) | so that / (in order) to / that (subjunctive complementizer) | conjunction | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | Never combines with present or future tense — only with the past tense (in its subjunctive uses) or a bare infinitive (in its purpose-clause-same-subject use). §308-310, pp.335-338. |
| во что бы то ни ста́ло | at any cost | idiom (fixed phrase) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §312 note, a concessive-construction-derived fixed phrase. p.340. |
| как бы то ни́ было | however that might be | idiom (fixed phrase) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §312 note. p.340. |
| как э́то ни парадокса́льно | paradoxical as it may seem | idiom (fixed phrase) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §312 note. p.340. |
| как э́то ни стра́нно | strange as it may seem | idiom (fixed phrase) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §312 note. p.340. |

### §304 The conditional mood — introductory comments

Distinguishes a real future condition ("if he wakes his wife, she will be angry" — rendered with a plain
future tense in Russian) from a hypothetical/contrary-to-expectation condition ("if he woke his wife,
she would be angry" — rendered by the dedicated conditional mood, е́сли бы + past, ... + бы + past).
Russian's conditional mood is morphologically just "past tense + бы," used in both the if-clause and
the result clause — there's no separate conditional verb form. p.333.

### §305 Formation of the conditional

Structure: е́сли бы + past tense (condition) / past tense + бы (result); clause order is free, бы can
shift position within the result clause, and то 'then' can optionally introduce the result clause after
the condition. Critically, **the same construction covers both a present/future hypothetical and a
past (pluperfect-equivalent) hypothetical** — Russian doesn't distinguish "I would go if they invited
me" from "I would have gone if they had invited me" morphologically; only context disambiguates. The
если clause can also be dropped entirely, leaving just [past tense + бы] to mean "this is what I'd do
[if I had my way]." The conditional favors the perfective aspect, though either aspect is possible.
pp.333-334.

### §306 Imperative and без as conditional substitutes

Two colloquial devices substitute for a full е́сли-conditional: (1) a bare singular imperative can stand
in for either е́сли бы + past ("if I had chanced to...") or е́сли + future ("if X breaks out..."); (2) a
без + genitive prepositional phrase ('without X') can imply 'had it not been for X, ...' — Без Лю́бы, я
бы не получи́л вы́сшего образова́ния 'had it not been for Lyuba, I wouldn't have gotten a higher
education'. p.334-335.

### §307 The particle бы expressing desire

Past tense + бы, outside a full conditional construction, expresses a wish: Я с удово́льствием пошёл бы
в теа́тр 'I would love to go to the theater'. Хоте́л(а) бы 'I would like to' is the most common
lexicalization of this pattern. The same construction, addressed to someone else, softens an imperative
into a mild suggestion (Помо́г бы ей 'you might give her a hand') — markedly less peremptory than a bare
imperative (Помоги́те ей! 'help her!'). pp.335.

### §308 The subjunctive expressing wish/desire (чтобы + past)

Key same-subject/different-subject distinction: "I want to X" (same subject for wanting and doing) uses
a plain infinitive (Я хочу́ голосова́ть); "I want you to X" (different subjects) requires чтобы + past
tense (Я хочу́, что́бы вы голосова́ли) — чтобы here is never used with present/future, only past, even
though the meaning is not literally past at all. This same чтобы + past pattern extends to any verb/
expression of desirability or its opposite (тре́бовать 'to demand', наста́ивать 'to insist', ва́жно 'it's
important', про́тив того́ 'against'), to reported requests/warnings via сказа́ть and предупреди́ть, and
idiomatically to a sharp warning (Что́бы я э́того бо́льше не слы́шал! 'don't let me ever hear that
again!'). pp.335-337.

### §309 The subjunctive of purposeful endeavour

Parallel to §308 but for verbs of active effort rather than mere wishing: добива́ться/доби́ться того́,
что́бы 'to work toward/try to get X to happen' takes the same что́бы + past construction while
expressing intent (contrasted with the indicative, used once the goal is actually achieved:
доби́лся того́, что она́ согласи́лась 'he got her to agree'). Other verbs in this construction: де́лать
всё, что́бы; забо́титься о том, что́бы; следи́ть за тем, что́бы; стреми́ться к тому́, что́бы. pp.337.

### §310 Purpose clauses

Same subject in both clauses → что́бы + infinitive ("he got up to open the window"). Different subjects
→ что́бы + past tense subjunctive ("he got up so that she could sit down") — the same same-subject/
different-subject split already seen governing §308's wish-construction governs purpose clauses too, a
genuinely productive pattern across this whole chapter. pp.337-338.

### §311 The expression of hypothesis

A parallel indicative/subjunctive contrast for relative clauses and complement clauses depending on
whether the described entity/event is real or merely hypothetical: "the man who swam the Channel" (a
real, specific person) → indicative relative clause; "a man who has never heard of Tolstoy" (a
hypothetical category, possibly empty) → subjunctive relative clause (кото́рый бы не слыха́л). The same
contrast extends to verbs of perception/statement (ви́деть, заме́тить, по́мнить, сказа́ть, слы́шать): the
indicative acknowledges an event genuinely occurred (even if unwitnessed), while the subjunctive
expresses doubt or non-witness of whether it occurred at all. Includes a special idiom не то, что́бы
'it's not that...' and a note that боя́ться 'to fear' can take either mood depending on whether the
feared outcome is presented as a real possibility (indicative) or a remote/unlikely one (subjunctive,
with an "illogical" negative particle inserted: Бою́сь, что́бы он не провали́лся 'I'm afraid he might
fail'). pp.338-340.

### §312 Concessive constructions ("whoever/whatever/however...")

A dedicated concessive pattern: [interrogative word] + бы + ни + past tense = English "-ever"
constructions (кто бы ни 'whoever', что бы ни 'whatever', как бы ни 'however', ско́лько бы ни 'however
much'). Бы can be dropped when referring to an actual (not hypothetical) incident. The future tense can
substitute for this construction to mean "no matter which one you pick, all instances are covered"
(Каку́ю газе́ту ни откро́ешь... 'whichever paper you open...'). Several fixed idiomatic phrases derive
directly from this pattern (captured in the vocabulary table above). pp.340.

## Constructions Expressing Obligation, Necessity, Possibility, or Potential (§313-314)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| до́лжен, должна́, должно́, должны́ | must, should, is supposed to, is due to | short-form adjective (modal) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | Agrees with subject in gender/number like any short-form adjective, not a fixed particle; combines with был/будет for past/future obligation. §313(1). pp.341-342. |
| ну́жно | necessary, needed ('ought to') | predicate adverb (modal) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §313(2)(i)-(ii). Distinguished from на́до in the negative: не ну́жно 'not necessary' (you may skip it) vs. не на́до 'you should not' (prescriptive, stronger). p.342-343. |
| на́до | necessary, needed ('ought to') | predicate adverb (modal) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §313(2); near-synonym of ну́жно but sharply diverges in the negative (see above). p.342-343. |
| сто́ит | it is worth (doing) | predicate adverb (modal) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §313(3)(i): mild, recommendation-level modal, weakest of this set. p.343. |
| сле́дует | one should, ought to | predicate adverb (modal) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §313(3)(ii): more categorical than сто́ит. p.343. |
| прийти́сь (impersonal, dative) | to have to (reluctantly) | verb (impersonal modal) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §313(3)(iii): implies reluctant acceptance of necessity — Ему́ пришло́сь бежа́ть всю доро́гу 'he had to run all the way'. p.343. |
| вы́нужден | forced (to) | short-form adjective (modal) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §313(3)(iv): stronger than прийти́сь, implies external compulsion. p.343. |
| обя́зан | obliged (to) | short-form adjective (modal) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §313(3)(iv): duty-based obligation, e.g. professional duty. p.343. |
| мочь / смочь | to be (physically/circumstantially) able | verb (impf./pf. modal) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §314(1). Distinguished from уме́ть 'to know how to' — Я уме́ю пла́вать 'I know how to swim' (skill) vs. Сего́дня я не могу́ пла́вать 'I can't swim today [circumstantially, e.g. injury]' (ability-in-context). Note: the imperfective future of мочь is rarely used; быть в состоя́нии + infinitive substitutes instead. p.343. |
| уме́ть | to know how to, be able to (skill-based) | verb (impf.) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §314(1) Note (a): the skill-based counterpart to мочь's circumstantial ability. p.343. |
| быть в состоя́нии + infinitive | to be in a position to, be able to | verb phrase (modal) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §314(1) Note (b): substitutes for the rarely-used imperfective future of мочь. p.343. |

### §313 Expressing obligation and necessity

A graded scale of obligation-expressing words, from weakest to strongest recommendation/compulsion:
сто́ит (mild, "worth doing") < сле́дует (more categorical "should") < ну́жно/на́до (necessity) < до́лжен
(moral duty, "must") < обя́зан (formal/professional duty) < вы́нужден (external compulsion, "forced")
< пришло́сь (reluctant necessity that actually occurred). До́лжен is grammatically a short-form
adjective (agrees with subject gender/number: до́лжен/должна́/должно́/должны́) rather than an invariable
particle, and combines with был/бу́дет for past/future forms, plus a distinct parenthetical use (до́лжно́
быть 'must have,' expressing supposition rather than obligation: Она́, должно́ быть, заболе́ла 'she must
have fallen ill'). The ну́жно/на́до near-synonym pair sharply diverges under negation: не ну́жно 'not
necessary' (permission to skip) vs. не на́до 'you should not' (a prescriptive prohibition) — a testable
minimal pair. pp.341-343.

### §314 Expressing possibility or potential

Мочь/смочь 'to be able' expresses circumstantial/physical ability, contrasted with уме́ть 'to know how
to' for learned skill — a clean two-way ability distinction (skill vs. circumstance) worth flagging for
mechanics analysis, since English "can" collapses both. The imperfective future of мочь is avoided in
practice in favor of a periphrastic future construction, быть в состоя́нии + infinitive. p.343.

## Verbs of Motion (§315-338)

**Scope decision:** the 14 unidirectional/multidirectional verb-of-motion pairs are a closed,
foundational lexical set — extracted exhaustively. The prefixed compounds built on -ходи́ть/-йти́ (§331)
are similarly a closed, systematic paradigm — extracted exhaustively with their governing prepositions,
since the preposition-per-prefix mapping is itself a genuine grammar point, not incidental vocabulary.
Figurative/idiomatic uses of both simple and compound motion verbs (§330, §336) are explicitly
introduced by the source itself as "a representative sample," so a representative subset (not the full
list) is captured here per the same principle, flagged accordingly.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| идти́ / ходи́ть | to go, walk (unidirectional / multidirectional) | verb (motion pair) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §315-316, pair 1 of the 14 foundational simple motion-verb pairs; идти́ is irregular in perfectivization (see below). pp.345-346. |
| е́хать / е́здить | to travel, ride, drive (unidirectional / multidirectional) | verb (motion pair) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §316, pair 2. p.346. |
| бежа́ть / бе́гать | to run (unidirectional / multidirectional) | verb (motion pair) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §316, pair 3. p.346. |
| лете́ть / лета́ть | to fly (unidirectional / multidirectional) | verb (motion pair) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §316, pair 4. p.346. |
| плыть / пла́вать | to swim, float, sail (unidirectional / multidirectional) | verb (motion pair) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §316, pair 5. p.346. |
| нести́ / носи́ть | to carry (unidirectional / multidirectional) | verb (motion pair) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §316, pair 6; also core to §324's take/carry contrast set. p.346. |
| вести́ / води́ть | to lead (unidirectional / multidirectional) | verb (motion pair) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §316, pair 7; also means 'to drive [a vehicle]' (§324 note, §325(3)). p.346. |
| везти́ / вози́ть | to convey, transport (unidirectional / multidirectional) | verb (motion pair) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §316, pair 8. p.346. |
| лезть / ла́зить | to climb (unidirectional / multidirectional) | verb (motion pair) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §316, pair 9. p.346. |
| ползти́ / по́лзать | to crawl (unidirectional / multidirectional) | verb (motion pair) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §316, pair 10. p.346. |
| тащи́ть / таска́ть | to drag (unidirectional / multidirectional) | verb (motion pair) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §316, pair 11. p.346. |
| гнать / гоня́ть | to drive, chase (unidirectional / multidirectional) | verb (motion pair) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §316, pair 12; also used of driving livestock (§325 note: гнать/гоня́ть ста́до). p.346. |
| кати́ть / ката́ть | to roll (unidirectional / multidirectional) | verb (motion pair) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §316, pair 13; ката́ться also idiomatically means 'to go skating/cycling/rowing' (§330(2)(iv)). p.346. |
| брести́ / броди́ть | to plod along (with difficulty) / to wander aimlessly (unidirectional / multidirectional) | verb (motion pair) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §316, pair 14: the source flags this pair as semantically atypical of the series — броди́ть, unlike the other 13 multidirectional partners, cannot denote motion toward a destination at all. p.346. |
| нести́ / носи́ть vs. вести́ / води́ть vs. везти́ / вози́ть | three distinct verbs of 'taking/bringing' distinguished by mode of transport | verb (motion, semantic contrast set) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §324: нести́/носи́ть = carry on foot; вести́/води́ть = lead/take a person or animal (walking) or drive a vehicle; везти́/вози́ть = convey by vehicle. Distinguished from бра́ть/взять 'to take', which (unlike all three) doesn't specify the purpose/destination of the journey — a fine four-way lexical distinction English collapses into one verb. p.353-354. |
| вход́ить / войти́ | to enter | verb (prefixed motion compound) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §331(4): governs в + accusative. Part of the systematic 15-item -ходи́ть/-йти́ prefix paradigm. p.358. |
| всход́ить / взойти́ | to go up on to | verb (prefixed motion compound) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §331(4): governs на + accusative. p.358. |
| вых́одить / вы́йти | to go out of | verb (prefixed motion compound) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §331(4): governs из + genitive. p.358. |
| дох́одить / дойти́ | to go as far as | verb (prefixed motion compound) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §331(4): governs до + genitive; figuratively дойти́ до слёз 'to be reduced to tears' (§336(1)). p.358, 362. |
| зах́одить / зайти́ | to call on someone / call in at a place / go a long way into | verb (prefixed motion compound) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §331(4): governs к + dative (a person) or в/на + accusative (a place); figuratively зайти́ сли́шком далеко́ 'to go too far' (§336(1)). p.358-359, 362. |
| нах́одить / найти́ | to find | verb (prefixed motion compound) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §331(4): governs a bare accusative (direct object, not a prepositional phrase — the only one in the paradigm with no preposition). p.359. |
| обх́одить / обойти́ | to go round / to inspect, avoid | verb (prefixed motion compound) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §331(4): governs вокру́г + genitive ('go round') or bare accusative ('inspect/avoid'). p.359. |
| отх́одить / отойти́ | to move away from | verb (prefixed motion compound) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §331(4): governs от + genitive. p.359. |
| перех́одить / перейти́ | to cross | verb (prefixed motion compound) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §331(4): governs че́рез + accusative or bare accusative; figuratively перейти́ к друго́й те́ме 'to switch to a different topic' (§336(1)). p.359, 362. |
| подх́одить / подойти́ | to go up to | verb (prefixed motion compound) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §331(4): governs к + dative; figuratively 'to be suitable' (§336(1)). p.359, 362. |
| прих́одить / прийти́ | to come to see a person / arrive at a place | verb (prefixed motion compound) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §331(4): governs к + dative (person) or в/на + accusative (place); figuratively прийти́ в го́лову 'to occur [to someone]' (§336(1)). p.359, 362. |
| прох́одить / пройти́ | to pass / cover (a distance) | verb (prefixed motion compound) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §331(4): governs ми́мо + genitive or bare accusative; figuratively used of time/pain passing (§336(1)). p.359, 362. |
| расход́иться / разойти́сь | to disperse to (separate destinations) | verb (prefixed motion compound, reflexive) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §331(4): governs по + dative; figuratively разойти́сь во мне́ниях 'not to see eye to eye' (§336(1)). p.359, 362. |
| сх́одить / сойти́ | to come down from, step off | verb (prefixed motion compound) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §331(4): governs с + genitive; figuratively сойти́ с ума́ 'to go mad' (§336(1)). p.359, 362. Distinguish from the unrelated, unprefixed-multidirectional-based perfective сходи́ть 'to go [somewhere] and come back' in §337 — same surface form, different construction. |
| сход́иться / сойти́сь | to come together with | verb (prefixed motion compound, reflexive) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §331(4): governs с + instrumental; figuratively сойти́сь во мне́ниях 'to see eye to eye' (§336(1)). p.359, 362. |
| ух́одить / уйти́ | to leave (a person or a place) | verb (prefixed motion compound) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §331(4): governs от + genitive (a person) or из/с + genitive (a place). p.359. |
| Идёт война́, уро́к, фильм | 'a war/lesson/film is on/in progress' | idiom (figurative motion-verb use) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §330(1)(i), representative sample of unidirectional-only figurative uses (source itself calls this list representative, not exhaustive). p.357. |
| Идёт дождь, снег | it is raining, snowing | idiom (figurative motion-verb use) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §330(1)(i). p.357. |
| вести́ войну́ | to wage war | idiom (figurative motion-verb use) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §330(1)(ii). p.357. |
| нести́ отве́тственность | to bear the responsibility | idiom (figurative motion-verb use) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §330(1)(iii). p.357. |
| Ему́ везёт / повезло́ | he is lucky / is in luck | idiom (figurative motion-verb use) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §330(1)(vi) — везти́, itself in the motion-verb family, lexicalized into a dedicated luck idiom; cross-reference §297's impersonal-dative везёт/повезло́ (same lexical item, same construction type). p.357-358. |
| носи́ть зва́ние, и́мя | to bear a title, a name | idiom (figurative motion-verb use) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §330(2)(i), multidirectional-only figurative use. p.358. |
| води́ть за нос | to lead [someone] up the garden path | idiom (figurative motion-verb use) | colloquial | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §330(2)(ii); a vivid deception idiom worth flagging for slang-mechanics analysis. p.358. |
| ходи́т слух / хо́дят слу́хи | rumour has it / rumours are rife | idiom (figurative motion-verb use) | colloquial | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §330(2)(iii); идёт слух is also possible per the source, though less common — a rare case of the unidirectional intruding on multidirectional-only figurative territory. p.358. |
| входи́ть/войти́ в мо́ду | to come into fashion | idiom (figurative compound-motion-verb use) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §336(1), representative sample (explicitly marked non-exhaustive by the source). p.362. |
| заводи́ть/завести́ часы́ | to wind up a watch | idiom (figurative compound-motion-verb use) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §336(2). p.363. |
| разводи́ться/развести́сь | to get divorced | idiom (figurative compound-motion-verb use) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §336(2) — notable that 'to divorce' is lexically a compound of the same root as 'to lead/take' (вести́), i.e. literally 'to be led apart'. p.363. |
| приноси́ть/принести́ по́льзу | to bring benefit | idiom (figurative compound-motion-verb use) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §336(3). p.363. |
| сходи́ть (pf. only, с- + multidirectional) | to go [somewhere] and come back (round trip, brief) | verb (compound perfective, no imperfective) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §337: unlike simple unprefixed multidirectional verbs (which can only express a single return-trip meaning in the *past* tense, §323), с-perfectives of this type can express the same round-trip meaning in future, infinitive, and imperative too. Must be kept distinct from the identically-spelled сходи́ть (imperfective of сойти́, §331) which means 'to descend'. p.363-364. |

### §315-316 Unidirectional vs. multidirectional verbs of motion

Russian's core typological innovation for motion verbs: 14 semantic categories of motion each get
*two* distinct imperfective verbs rather than one — a unidirectional verb (movement in one direction,
typically on a single occasion) and a multidirectional verb (movement in more than one direction,
general/habitual capacity, or round trips). This is a dimension entirely orthogonal to
perfective/imperfective aspect — both members of each pair are imperfective; the aspectual system layers
on top via prefixation (§326-338). pp.345-346.

### §317-318 Imperatives and past tense of motion verbs

Imperatives follow the general rule of §227 (outside this range). A special note: похать's imperative
пое́зжай is used for a single positive command, while е́зди is used for frequentative/generic commands and
не е́зди for negative ones — an unusually irregular imperative-suppletion pattern worth flagging. Several
motion verbs (брести́, везти́, вести́, идти́, лезть, нести́) have irregular masculine past-tense forms
that drop or alter their final consonant (шёл, вёз, вёл, etc.) rather than following the regular -л
pattern. pp.346-347.

### §319 "To go": идти́/ходи́ть vs. е́хать/е́здить

The single most basic motion-verb distinction: "to go" on foot is идти́/ходи́ть; "to go" by any vehicle is
е́хать/е́здить. Substantial trips (to another country, etc.) default to the vehicle-pair even when the
means of transport isn't specified. Идти́/ходи́ть extends idiomatically to trains, ships (alternating with
плыть), and road vehicles (alternating with е́хать) — П"оезд идёт 'the train is moving' is standard.
pp.347-348.

### §320-321 Functions of unidirectional verbs

Unidirectional verbs describe movement in one direction, typically (but not necessarily) in a straight
line, typically on a single occasion, with a destination that may be unspecified, specific, or given as
a general direction (a compass point). Their future tense is markedly rarer than present/past. They CAN
express repeated action, but specifically when the one-way nature of the trip is what's being stressed
(letters winging their way one-way repeatedly; a daily walk TO work, contrasted with the multidirectional
verb used for the daily round trip) — a genuinely fine-grained aspectual-directional distinction. pp.348-350.

### §322-323 Functions of multidirectional verbs

Multidirectional verbs cover: (1) the action in the abstract/as a capacity/skill (combines naturally
with люби́ть, предпочита́ть, уме́ть, учи́ться); (2) actual back-and-forth/round-and-round movement; (3)
habitual action construed as a round trip. Critically, **only the PAST tense of a multidirectional verb
can denote a single specific completed return journey** (На про́шлой неде́ле она́ е́здила в Ло́ндон 'she
went to London last week [and came back]') — this reading is unavailable in present or future tense.
The past-tense multidirectional can also report what happened at the destination between the outward
and return legs, and appears in questions/negation about whether a round trip occurred at all. pp.350-352.

### §324-325 Distinguishing "to take/carry/lead/drive/convey"

нести́/носи́ть (carry, on foot), вести́/води́ть (lead a person/animal on foot, OR drive a vehicle), and
везти́/вози́ть (convey by vehicle) form a three-way lexical split that collapses to a single English verb
("take" or "drive"). All three differ from бра́ть/взять 'to take' in that they specify the *purpose* of
the journey being to transport that object/person — брать does not carry this implication (Возьми́те
меня́ с собо́й 'take me with you' implies you're going anyway; a specific errand would use one of the
motion-based verbs instead). A speaker's choice between нести́ and везти́ for the *same physical object*
on the *same trip* depends on whether transporting that object is the actual purpose of the journey
(§324, Note b's train-passenger example is a genuinely elegant illustration of this pragmatic point).
pp.353-354.

### §326-329 Perfectives of unidirectional and multidirectional verbs

Unidirectional perfectives are formed with по- (по-йти́ is the sole irregular one, with -йти́ replacing
-идти́) and denote the *beginning* of a one-way journey/setting off — crucially NOT completion of the
whole trip (Он пошёл на по́чту 'he has set off/gone to the post office [and is not back]', contrasted
with the multidirectional Он ходи́л на по́чту 'he went/has been to the post office [implying he's back]').
English "went" is thus systematically ambiguous between these two Russian constructions depending on
whether a return is implied. Пойти́ additionally has two specialized idiomatic senses: a toddler's first
steps, and a child starting school (§327) — and figures in the "illogical" past-for-immediate-future
Я пошёл! 'I'm off!'. §328 draws a fine distinction between не ходи́л (no trip occurred at all) and не
пошёл (a planned trip was abandoned/didn't happen despite intent). Multidirectional perfectives (also
по-) denote a short-duration action, past or future (Он полета́л над го́родом 'he flew around the town
for a bit'). pp.354-357.

### §330 Figurative/idiomatic uses split by directionality

A striking pattern: when either partner of a unidirectional/multidirectional pair takes on a figurative
meaning, **only one of the two members can be used in that figurative sense** — the normal directional
contrast collapses and gets replaced by an arbitrary lexicalized split (е.g. "a war is on" uses only the
unidirectional идёт; "to bear a title" uses only the multidirectional носи́ть). This is a productive
mechanism for the mechanics-analysis phase: idiomatic/figurative drift systematically favors one member
of an aspectual-directional pair over the other, a pattern any invented-slang derivation could reuse
(picking the "wrong" member of a pair as a marker of figurative/slang register). pp.357-358.

### §331-333 Compound (prefixed) verbs of motion

All 14 simple motion-verb pairs can take up to 15 different prefixes, but the prefixed compounds lose
the unidirectional/multidirectional distinction entirely: the multidirectional member becomes the basis
of the new imperfective, and the unidirectional member becomes the basis of the new perfective. This is
a major structural reorganization — the same lexical material is repurposed from a directional contrast
into a plain aspectual (imperfective/perfective) contrast once prefixed. Compound verbs of motion are
mostly intransitive, taking a following noun via a preposition whose choice is itself governed
per-prefix (fully tabulated for the -ходи́ть/-йти́ family in the vocabulary table above — see §331(4) for
the systematic preposition-per-prefix pattern, which generalizes to the other 13 prefixed families with
the same prefixes). A few spelling rules apply in forming these compounds: an "o" buffer vowel is
inserted between a consonant-final prefix and -йти (войти́, обойти́, etc.), and a hard sign (ъ) is
inserted between a consonant-final prefix and stems in -езжа́ть/-е́хать (въезжа́ть, въе́хать). pp.358-360.

### §334 Prefixed verbs of motion — illustrative examples

Illustrative sentence-level examples of various prefix+motion-verb compounds in use (dragging a pilot
out of a burning aircraft, a bus pulling up to a rocket launch pad, etc.) — these are drill-style
examples reinforcing the already-tabulated §331 paradigm rather than introducing new distinct
vocabulary, so per the coverage rule they are paraphrased here rather than re-tabled. pp.360-361.

### §335 Imperfective past of a compound motion verb: "action and its reverse"

Directly parallel to §259's general pattern: the imperfective past of a *prefixed* compound motion verb
can imply the action's later reversal (Он приходи́л 'he came [and has since left again]', Он уезжа́л 'he
went away [and has since returned]'). Most frequent with в-/вы-, за-, под-, при-/у- prefixes. p.361-362.

### §336 Figurative/idiomatic uses of compound motion verbs

A further, explicitly-marked-as-"representative sample" list of idioms built on prefixed motion verbs,
organized by prefix family (-ходи́ть/-йти́, -води́ть/-вести́, -носи́ть/-нести́) — representative subset
captured in the vocabulary table above per the source's own framing. pp.362-363.

### §337-338 Perfectives in с-, за-, из-, на- built directly on multidirectional verbs (no imperfective)

A distinct, smaller word-formation pattern from the systematic §331 prefixation: с- attaches directly
to a *multidirectional* verb (not the whole aspectual pair) to create a perfective-only verb with no
imperfective partner at all, meaning "go somewhere briefly and return" — and, unlike the simple
unprefixed multidirectional verb (which can only express this "round trip" meaning in the past tense,
§323), this с-perfective can express it in the future, infinitive, and imperative too (Сходи́ к Ма́е...
'pop over to Maya's...' — an imperative round-trip instruction, impossible with the simple verb). За-,
из-, and на- similarly combine directly with multidirectional verbs to form perfective-only compounds
with distinct meanings: за- = "beginning of an action" (заходи́л по ко́мнате 'began pacing the room'),
из- = "covering the whole area" (изъе́здил всю страну́ 'traveled the length and breadth of the country').
pp.363-364.

## Participles (§339-366)

**Scope decision:** §339-358 (formation morphology — stress patterns, consonant mutations,
conjugation-class-by-conjugation-class formation rules for each of the five participle types) is dense
morphological mechanism with very little independently-glossable vocabulary; it is paraphrased in
grammar-point form below rather than tabled, since the "vocabulary" here is really the paradigm itself
(a handful of verb-form pairs illustrating each rule), not a set of new lexical items. §363
("Participles as adjectives and nouns") is different — it lists genuinely lexicalized items (participles
that have drifted to function as ordinary adjectives or nouns), and is tabled in full below since each
is a real distinct vocabulary item.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| блестя́щий | brilliant | adjective (lexicalized present active participle) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §363(1)(i). p.382. |
| веду́щий | leading | adjective (lexicalized present active participle) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §363(1)(i). p.382. |
| выдаю́щийся | outstanding | adjective (lexicalized present active participle) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §363(1)(i). p.382. |
| далеко́ иду́щий | far-reaching | adjective phrase (lexicalized present active participle) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §363(1)(i). p.382. |
| подходя́щий | suitable | adjective (lexicalized present active participle) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §363(1)(i); also cf. its literal-verb sense 'going up to' in the motion-verb chapter. p.382. |
| сле́дующий | next, following | adjective (lexicalized present active participle) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §363(1)(i). p.382. |
| соотве́тствующий | appropriate | adjective (lexicalized present active participle) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §363(1)(i). p.382. |
| теку́щий | current | adjective (lexicalized present active participle) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §363(1)(i), literally 'flowing'. p.382. |
| куря́щий | a smoker | noun (lexicalized present active participle) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §363(1)(ii). p.382. |
| начина́ющий | a beginner | noun (lexicalized present active participle) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §363(1)(ii). p.382. |
| непью́щий | a teetotaller | noun (lexicalized present active participle) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §363(1)(ii). p.382. |
| трудя́щийся | a worker | noun (lexicalized present active participle) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §363(1)(ii); Soviet-era register association (трудя́щиеся 'the working people') worth flagging for mechanics/register analysis. p.382. |
| уча́щийся | a pupil, student | noun (lexicalized present active participle) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §363(1)(ii). p.382. |
| бы́вший | former | adjective (lexicalized past active participle) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §363(2)(i). p.382. |
| пострада́вший | a casualty | noun (lexicalized past active participle) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §363(2)(ii). p.382. |
| сумасше́дший | a madman | noun (lexicalized past active participle) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §363(2)(ii). p.382. |
| уме́рший | the deceased | noun (lexicalized past active participle) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §363(2)(ii); exceptional stress (see §343). p.382. |
| уцеле́вший | a survivor | noun (lexicalized past active participle) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §363(2)(ii). p.382. |
| вообража́емый | imaginary | adjective (lexicalized imperfective passive participle) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §363(3). p.383. |
| люби́мый | favourite | adjective (lexicalized imperfective passive participle) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §363(3). p.383. |
| терпи́мый | tolerable | adjective (lexicalized imperfective passive participle) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §363(3). p.383. |
| уважа́емый | respected | adjective (lexicalized imperfective passive participle) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §363(3); also used as a polite address form ('esteemed [name]') in wider Russian usage, though the source doesn't flag that use here. p.383. |
| невыноси́мый | unbearable | adjective (negative-prefixed lexicalized participle) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §363(3) Note: parallels English '-ble' adjectives. p.383. |
| незабыва́емый | unforgettable | adjective (negative-prefixed lexicalized participle) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §363(3) Note. p.383. |
| необходи́мый | indispensable | adjective (negative-prefixed lexicalized participle) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §363(3) Note. p.383. |
| незамени́мый | irreplaceable | adjective (negative-prefixed lexicalized participle, from a pf. stem) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §363(3) Note. p.383. |
| неизлечи́мый / излечи́мый | (in)curable | adjective (negative-prefixed lexicalized participle, from a pf. stem) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §363(3) Note. p.383. |
| неоспори́мый | indisputable | adjective (negative-prefixed lexicalized participle, from a pf. stem) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §363(3) Note. p.383. |
| непобеди́мый | invincible | adjective (negative-prefixed lexicalized participle, from a pf. stem) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §363(3) Note. p.383. |
| несовмести́мый / совмести́мый | (in)compatible | adjective (negative-prefixed lexicalized participle, from a pf. stem) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §363(3) Note. p.383. |
| незави́симый | independent | adjective (negative-prefixed lexicalized participle, from an intransitive verb) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §363(3) Note. p.383. |
| обвиня́емый | the accused | noun (lexicalized imperfective passive participle) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §363(3). p.383. |
| содержи́мое | contents (of a receptacle) | noun (lexicalized imperfective passive participle, neuter) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §363(3). p.383. |
| заключённый | convict | noun (lexicalized perfective passive participle) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §363(4). p.383. |
| краде́ное | stolen goods | noun (adjectival noun, participial-adjective origin) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §364(3). p.384. |
| ва́реное яйцо́ | a boiled egg | noun phrase (participial adjective, single -н-) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §364(1): illustrates the participial-adjective pattern (no prefix, single -н- vs. a true participle's double -нн- or circumstantial-detail-triggered participle form). p.383-384. |
| Здесь за́нято? | Is this place taken/occupied? | idiom (impersonal short-form participle) | colloquial | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §366(1): a fixed conversational formula built on an impersonal neuter short-form perfective passive participle. p.385. |
| За всё запла́чено | Everything has been paid for | idiom (impersonal short-form participle) | colloquial | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §366(1). p.385. |
| Ку́шать по́дано | Dinner is served | idiom (impersonal short-form participle) | literary | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §366(1); a fixed, somewhat archaic/theatrical register formula (butler/servant announcement). p.385. |
| Ска́зано — сде́лано | No sooner said than done | idiom (impersonal short-form participle) | colloquial | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §366 Note. p.385. |
| Давно́ не то́плено | The heating hasn't been on for ages | idiom (impersonal imperfective short-form participle, colloquial/negative) | colloquial | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §366(2): the source flags this pattern (impersonal use of an *imperfective* participle) as specifically colloquial and mainly found in the negative. p.385. |

### §339 Participles — introductory overview

Russian has five participle types: present active, past active (with distinct imperfective and
perfective forms), imperfective passive, and perfective passive (in both a short predicative form and a
long attributive form). All decline like adjectives (agreeing in case/gender/number) except the
perfective passive short form, which functions like a short adjective (predicate-only, no case
inflection). Participles are largely confined to written/literary registers — a genuine register marker
— except for the ones lexicalized as ordinary adjectives/nouns (§363) and the perfective-passive short
form, which is fully at home in ordinary spoken predicates ("the door is locked," etc.). p.365.

### §340-343 Present and past active participle formation

Present active: replace the 3rd-plural present -т with -щий/-щая/-щее/-щие (reflexive verbs keep -ся
throughout: смею́щийся). Stress generally follows the 3rd-plural for 1st-conjugation verbs and the
infinitive for 2nd-conjugation verbs, with a documented set of exceptions and doublets (both forms
mutually acceptable) listed by the source. Past active: replace masculine past -л with -вший (or, when
the masculine past doesn't end in -л, add -ший directly); a documented set of -ну- stem verbs and a few
individual irregular verbs (пости́чь-type, воскре́снуть, etc.) have doublet or irregular forms. pp.365-368.

### §344-347 Imperfective passive participle formation and gaps

Formed from the 1st-person-plural present of an imperfective *transitive* verb + adjectival endings.
This participle has severe lexical gaps: many unprefixed transitive verbs simply lack it (жева́ть 'to
chew', копа́ть 'to dig'), as do whole morphological classes (§346: verbs in -ереть/-зть/-оть/-сть/-уть/
-чь; most verbs in -ти except вести́ and нести́; most monosyllabic verbs; many 1st-conjugation
consonant-stem and 2nd-conjugation verbs). Crucially, **where the base verb lacks this participle, its
secondary-imperfective near-synonym often has it instead** (§347: есть 'to eat' has no participle, but
its synonym съеда́ть does → съеда́емый) — a productive workaround pattern. A small set of intransitive/
semi-transitive verbs governing dative or instrumental also form this participle unusually (предше́ствовать
'to precede' → предше́ствуемый). pp.368-370.

### §348-358 Perfective passive participle formation (short and long form)

Only formed from perfective *transitive* verbs, mostly with suffix -н-/-ен- (a minority -т-). Formation
rules are heavily conjugation-class- and stem-final-consonant-dependent: -ать/-ять infinitives → -ан/-ян
(§349, with a documented е→ё stress mutation, §349(2)); -ить/-еть 2nd-conjugation infinitives → -ен/-ён
with an extensive, fully cataloged set of consonant mutations (б:бл, в:вл, м:мл, п:пл, ф:фл, д:ж, д:жд,
з:ж, с:ш, ст:щ, т:ч, т:щ — §353, each mutation also independently visible in the corresponding
imperfective infinitive and deverbal noun, a genuinely productive cross-paradigm consonant-alternation
pattern worth flagging for the mechanics-analysis phase); -ти/-зть/-сть/-чь infinitives → replace final
-т of the 3rd-singular with -н (§355); and a further large "-т" class (§357) covering -оть, -уть, -ыть,
compounds of -бить/-вить/-лить/-пить/-шить, verbs introducing -н-/-м- in conjugation (взять, деть,
жать, клясть, -нять, нача́ть, распя́ть), and -ереть verbs — each with its own stress and vowel-mutation
quirks individually cataloged by the source (e.g. дать and its compounds have unusually variable stress
patterns, §350). The long-form (attributive) participle is uniformly derived by adding full adjectival
endings (-ный/-ная/-ное/-ные, or -тый/-тая/-тое/-тые for the -т- class) onto the masculine short form.
pp.370-377.

### §359 Functions of short-form participles

Only passive participles have short forms (active participles are long-form only). The imperfective
passive short form is rare in practice — a reflexive verb or 3rd-plural construction is preferred
instead for ordinary passive statements. The perfective passive short form, by contrast, is extremely
common and functions as a predicate agreeing with its subject in gender/number, denoting either
completion of an action (Война́ объя́влена 'war has been declared') or a resulting state (Дверь за́перта
'the door is locked') — the same short form covers both readings, disambiguated by context. It combines
with tensed forms of быть for past/future/conditional passive meaning, and its agent can be named in the
instrumental. pp.377-378.

### §360-362 Functions and agreement of long-form participles; participial synonymy

Long-form participles (active and passive alike) function as a replacement for a relative clause
introduced by кото́рый. Active participles qualify the subject/experiencer of the participial action;
passive participles qualify its object. Timing relative to the main verb is systematically encoded:
present active = simultaneous with the main verb (regardless of the main verb's own tense); imperfective
past active = simultaneous with a past main verb; perfective past active = completed *before* the main
verb's action; imperfective passive = simultaneous with the main verb (any tense/aspect); perfective
passive = completed before the main verb's action. §361: the long-form participle agrees in case as
well as gender/number (unlike кото́рый, which only tracks the antecedent's gender/number, taking its own
case from its role inside the relative clause) — participles can also precede the noun they qualify (as
a pure adjective) or have material inserted between the participle and its noun, especially in
literary/journalistic style. §362: where a verb has both an imperfective passive participle and a
present active participle of its reflexive counterpart, the two can be synonymous, but the passive
participle is required once an agent is explicitly named (a true reflexive can never carry passive
meaning: одева́ющийся can only mean 'getting dressed [oneself]', never 'being dressed [by someone]').
pp.378-382.

### §363-365 Participles lexicalized as adjectives/nouns; participial adjectives; a stress-based
### minimal pair between short adjectives and short participles

§363's full lexicalized-participle inventory is captured in the vocabulary table above. §364: a related
but formally distinct category of "participial adjectives" differs from true long-form participles by
dropping any prefix and by having a single -н- rather than the participle's double -нн- (варёное яйцо́
'a boiled egg' as an ordinary adjective vs. сва́ренное в кастрю́льке яйцо́ 'an egg [that was specifically]
boiled in a saucepan' as a true participle, triggered by the added circumstantial detail). §365: a subtle
minimal pair exists between certain short-form adjectives and short-form participles built on the same
root, distinguished only by whether the feminine/neuter/plural endings double the н (adjective: -нна/
-нно/-нны, a genuine character-trait meaning) or not (participle: -на/-но/-ны, a resulting-state/action
meaning) — Она́ была́ озабо́ченна (adj., 'she was [an] anxious [person]/careworn by temperament') vs. Она́
была́ озабо́чена отъе́здом ма́тери (participle, 'she was worried BY her mother's departure' — a specific
triggered state, agent nameable). This is a sharp, testable spelling-based semantic distinction. pp.382-385.

### §366 Impersonal use of short-form participles

A neuter short-form perfective passive participle, used with no grammatical subject at all, forms a
family of common conversational and set-phrase constructions (see vocabulary table: Здесь за́нято? 'is
this seat taken?', Ку́шать по́дано 'dinner is served', Ска́зано — сде́лано 'no sooner said than done').
The imperfective equivalent of this same impersonal construction is specifically flagged by the source
as colloquial and mainly restricted to negative statements (Давно́ не то́плено 'the heating hasn't been
on for ages'). pp.385.

## Gerunds (§367-380)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| бу́дучи | being | gerund (irregular, from быть) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §368 Note (c): the only gerund of быть 'to be'; also the standard workaround gerund for мочь 'to be able' (§371, via the periphrastic synonym быть в состоя́нии). p.386. |
| припева́ючи (жить припева́ючи) | to live in clover | idiom (fossilized gerund) | colloquial | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §368 Note (d): the gerund survives productively only in this one fixed idiom. p.387. |
| благодаря́ (+ dat.) | thanks to | preposition (from a fossilized imperfective gerund) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §380(1): distinguish from the same form still used as a live gerund of благодари́ть + accusative ('thanking'). p.394. |
| исключа́я | excluding, except for | preposition (from a fossilized imperfective gerund) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §380(1). p.394. |
| кра́дучись | stealthily | adverb (from a fossilized imperfective gerund) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §380(1). p.394. |
| мо́лча | silently | adverb (from a fossilized imperfective gerund) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §380(1). p.394. |
| не счита́я | not counting | preposition (from a fossilized imperfective gerund) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §380(1). p.394. |
| не теря́я вре́мени | without delay | adverbial phrase (from a fossilized imperfective gerund) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §380(1). p.394. |
| су́дя по | judging by | preposition (from a fossilized imperfective gerund) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §380(1); distinguish from the still-live gerund судя́ 'judging'. p.394. |
| открове́нно говоря́ | frankly speaking | idiom (fossilized-gerund discourse formula) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §380 Note (a). p.394. |
| стро́го говоря́ | strictly speaking | idiom (fossilized-gerund discourse formula) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §380 Note (a). p.394. |
| не говоря́ уж (о + prep.) | let alone, to say nothing of | idiom (fossilized-gerund discourse formula) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §380 Note (a). p.394. |
| не покладя́ рук | tirelessly | idiom (fossilized-gerund adverbial) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §380 Note (b), literally 'without putting down one's hands'. p.394. |
| не́хотя | reluctantly | adverb (fossilized negated gerund) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §380 Note (b). p.394. |
| слу́шать разинув рот | to listen open-mouthed | idiom (fossilized perfective-gerund phrase) | colloquial | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §380(2). p.394. |
| сказа́ть положа́ ру́ку на́ сердце | to say hand on heart | idiom (fossilized perfective-gerund phrase) | colloquial | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §380(2). p.394. |
| рабо́тать спустя́ рукава́ | to work in a slipshod fashion | idiom (fossilized perfective-gerund phrase) | colloquial | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §380(2), literally 'with sleeves let down' — a vivid idiom for careless work, worth flagging for slang-mechanics analysis. p.394. |
| сиде́ть сложа́ ру́ки | to sit twiddling one's thumbs | idiom (fossilized perfective-gerund phrase) | colloquial | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §380(2), literally 'sitting with hands folded'. p.394. |
| спустя́ (недéлю спустя́) | later, after (a week later) | preposition (from a fossilized perfective gerund) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §380(2) Note; cross-referenced to §439(2)(i) in the Conjunction/temporal-preposition territory, outside this range. p.394. |

### §367 The gerund — introductory comments

Gerunds ("verbal adverbs") are indeclinable verb forms substituting for a co-ordinate or adverbial
clause ("and," "when," "since," "by," "without," etc.). The key formal contrast with participles: both
have English "-ing" equivalents, but participles are adjectival (agree in gender/case/number, replace a
кото́рый-relative-clause) while gerunds never inflect at all (the weeping boy = пла́чущий ма́льчик,
participle, vs. he sits weeping = он сиди́т, пла́ча, gerund). Imperfective and perfective gerunds exist,
paralleling the aspectual system. p.385-386.

### §368-369 Imperfective gerund formation

Add -я (-а after ж/ч/ш/щ) to the present-tense stem. A cluster of individually irregular/dual-form
verbs is catalogued (маха́ть → маха́я/маш́а; ка́пать → ка́пая; the reflexive suffix becomes -сь: жа́луясь).
Stress generally follows the 1st-person singular, with a small set of exceptions retaining stem stress
despite end-stressed conjugation (гля́дя, лёжа, сидя́, стоя́ — the source's own transcription list is
partly garbled by this PDF's stress-mark corruption, but the base forms are unambiguous from context).
pp.386-387.

### §370-371 Verbs lacking an imperfective gerund, and compensation strategies

A substantial closed list of common verbs (бежа́ть, бить, вить, врать, гнить, есть, éхать, ждать, лезть,
лить, петь, пить, рвать, слать, стона́ть, ткать, хоте́ть, шить, and more) simply has no imperfective
gerund at all — plus whole morphological classes (с:ш/з:ж-mutating 1st-conjugation consonant stems,
verbs in -чь, verbs in -ереть, verbs with the -ну- suffix). The productive workaround (§371, directly
parallel to §347's passive-participle workaround): where the primary verb lacks a gerund, either a
near-synonym (моч́ь → быть в состоя́нии → бу́дучи в состоя́нии; хоте́ть → жела́ть → жела́я) or a secondary
imperfective derived from the same root (есть → съеда́ть → съеда́я; е́хать → проезжа́ть → проезжа́я; пить →
выпива́ть → выпива́я) supplies a usable gerund instead. This "verb has a systematic morphological gap,
compensate via a near-synonym or secondary-imperfective" pattern recurs three times now in this file
(imperfective passive participles §347, imperfective gerunds §371) and is worth flagging to the
mechanics-analysis phase as a general Russian verbal-paradigm-repair strategy. pp.387-388.

### §372-376 Perfective gerund formation

Verbs in -ть → replace the perfective infinitive ending with -в (написа́в 'having written'); д-stem verbs
in -сть also take -в (присе́в). Reflexive perfective gerunds take -вшись instead (верну́вшись 'having
returned') — with a documented set of irregular/figurative forms (опёршись 'having leaned on', also used
figuratively 'relying on'). Some perfective gerunds have alternative forms in -я/-а as well as -в, the
-в form generally preferred in writing; the -я/-а alternative is specifically common with reflexive
verbs. Verbs in -ти and (non-d-stem) -сть form the gerund from the 3rd-plural stem + -я (with a further
-ши subclass for compounds of грести́, пасти́, расти́, цвести́). Verbs in -чь and -зть add -ши to the
masculine past tense. This is, like the participle chapter, primarily morphological mechanism rather
than new lexical content — captured here in paraphrase rather than tabled, except where a form is itself
a fossilized fixed idiom (see vocabulary table). pp.388-390.

### §377-379 Functions of gerunds; special constructional constraints; sequence reversal

The imperfective gerund denotes an action simultaneous with the main verb (parallel, or one
interrupting the other) — and, depending on context, can be glossed into English as "when," "while,"
"since," "if," or a bare "-ing," disambiguated only by context (the source's own parenthetical-gloss
examples make this genuinely ambiguous-in-isolation point well). The perfective gerund denotes an
action completed *before* the main verb's action, or (less commonly) a resulting state persisting into
the main verb's time-frame (Он сиде́л, вы́тянув но́ги 'he sat with his legs stretched out'). §378: the
gerund's understood subject MUST be identical to the main clause's grammatical subject — this rules out
combining a gerund with an impersonal main clause (*Подходя́ к ле́су, мне ста́ло хо́лодно is ungrammatical;
must instead be Когда́ я подходи́л к ле́су, мне ста́ло хо́лодно) and rules out a gerund alongside a passive
main clause where the passive subject isn't the logical (semantic) agent of the gerund's action — a
subtle same-subject constraint any invented-language design modeling converb/gerund systems should note
as a real cross-linguistic complication, not a given. §379: very occasionally the main-clause action can
actually *precede* the gerund's action (Он вы́шел, хло́пнув две́рью 'he went out, slamming the door' — the
slam is simultaneous with or after the exit, not before it) — explicitly flagged by the source as
non-normative, an exception rather than a productive pattern. pp.390-393.

### §380 Gerunds (and former gerunds) functioning as other parts of speech

A number of gerund forms have fossilized into prepositions, adverbs, or fixed idiomatic phrases,
losing their original verbal argument structure and often shifting case-government in the process
(благодаря́ 'thanks to' governs the dative as a preposition, but the still-live verbal gerund благодаря́
'thanking' governs the accusative — a genuine case-government split between a word's grammaticalized
and literal senses, worth flagging for the mechanics-analysis phase as a concrete example of
grammaticalization-in-progress). A cluster of perfective-gerund-derived idioms (§380(2), full set
captured in the vocabulary table above) are vivid body-part-based phrases for careless/reluctant/
attentive action — a genuinely productive site for slang/register analysis given how idiom-dense and
colloquial-leaning this particular cluster is. pp.393-394.

## The Adverb (§381-400)

**Scope decision:** Russian adverbs derived productively from adjectives (§382, e.g. -о/-е on virtually
any descriptive adjective) are an open, rule-governed class — captured here via the *rule* plus a small
illustrative sample, not exhaustively (that would mean tabling every adjective in the language a second
time). The genuinely closed, foundational sets — primary spatial/temporal/manner adverbs, the
indefinite/negative adverb series, and interrelating adverbs — are extracted exhaustively below, since
these are irreducible core vocabulary, not rule-derived forms.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| где / здесь / там | where / here / there (location) | adverb (primary spatial) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §387(1). Тут (also 'here') is more colloquial than здесь and can carry a temporal sense ('at this point [in a narrative]'). p.401-402. |
| тут | here (colloquial); at this point (temporal) | adverb (primary spatial, colloquial) | colloquial | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §387(1) Note. p.402. |
| куда́ / сюда́ / туда́ | where (to) / here (to) / there (to) (direction) | adverb (primary spatial, directional) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §387(2): the directional counterparts of где/здесь/там — Russian systematically distinguishes location-adverbs from direction-adverbs, a distinction English collapses. p.402. |
| отку́да / отсю́да / отту́да | from where / from here / from there | adverb (primary spatial, source/withdrawal) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §387(3): completes a three-way где/куда/откуда (location/direction-to/direction-from) system — a clean typological point about how thoroughly Russian grammaticalizes spatial deixis compared to English. Отку́да вы зна́ете? idiomatically = 'how do you know?'. p.402. |
| тогда́ | then, at that time | adverb (primary temporal) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §388(1): distinguished from пото́м/зате́м 'then, afterwards' — тогда́ anchors to a specific past reference time, пото́м/зате́м denote sequence. p.402. |
| когда́ / как | when / as | conjunction-adverb (primary temporal) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §388(2): когда́ (or в то вре́мя как) is preferred for 'as/when' in time clauses; как is instead used specifically after verbs of perception (ви́деть, слу́шать, слы́шать, смотре́ть) and after жда́ть/люби́ть governing an object clause. p.402-403. |
| как / как вдруг | when suddenly... / than | adverb/conjunction (primary temporal, sudden-interruption) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §388(3): introduces a sudden interruption of an ongoing action, often paired with a negative main clause or the words не успе́ть/едва́ ('hardly had... when'). p.403. |
| уж (= уже́) | already; (уж не =) no longer | adverb (primary temporal, aspectual-temporal marker) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §389: far more frequently used than English "already" — often marks an action as earlier/more-complete-than-expected with no direct English equivalent at all, and is critical for disambiguating relative tense sequence between two past-tense clauses (§389(2)'s worked example). Уж нет replaces уж не when there's no following predicate. p.403-404. |
| ещё / ещё не | still, yet / not yet | adverb (primary temporal) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §390: also can mean 'additional' (a distinct, non-temporal sense) and can be synonymous with уж in temporal contexts. Ещё нет replaces ещё не with no following predicate. Ещё раз 'once more' (repetition) contrasts with сно́ва 'again' (resumption after a gap) and опя́ть (synonym of сно́ва, but can carry irritation/complaint overtones). p.404-405. |
| до́лго | for a long time (a definite but unspecified duration) | adverb (primary temporal) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §391(1). p.405. |
| давно́ | for a long time (implying an unfinished, still-ongoing action or state); a long time ago | adverb (primary temporal) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §391(2): sharply distinguished from до́лго by aspectual implication — давно́ implies the state/action continues into the present (parallel to §256(vii)'s "continuous present"); note also a subtle negative-context tense distinction: я давно́ не курю́ 'I haven't smoked in a while [and have quit]' vs. я давно́ не кури́л 'I haven't smoked in a while [but might again]'. p.405. |
| неда́вно | recently | adverb (primary temporal) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §391(3): refers to a single recent event, contrasted with (в/за) после́днее вре́мя 'recently, of late', which instead describes a process/state extending over a period. p.405-406. |
| так | thus, like that; so (degree) | adverb (primary manner/degree) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §392: covers both manner ('do it like this') and degree/extent ('so much that...'); не так can mean specifically 'wrongly, the wrong way' (a common intensifier-negation idiom). Так же (two words) + a comparative expresses 'just as X as' — omitted in negative comparisons; та́к же... как и adds emphasis when linking two qualities of the same referent. Как твоё и́мя? and Как тебя́ зову́т? use как as an interrogative equivalent to English "what" when eliciting personal details — a genuine translation trap (English "what," not "how," in this frame). p.406-407. |
| там, где / туда́, куда́ / отту́да, отку́да / тогда́, когда́ / так, как | 'there, where' / 'to there, to where' / etc. — correlative place/direction/time/manner pairs | adverb (interrelating/correlative pair) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §393: a systematic correlative-adverb construction (demonstrative + relative adverb in sequence) used when no specific place/time/manner referent is named — structurally parallel to English "wherever," "whenever," "however" but realized as two separate words rather than a single "-ever" compound. p.407. |
| то́же / та́кже | also, as well, too | adverb | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §394: near-synonyms with a genuine register split (то́же more colloquial, та́кже more official/formal) plus a distributional split — то́же is preferred when identifying with an already-mentioned action/state/attribute (parallel structure), та́кже is preferred when adding genuinely new/supplementary information, and та́кже (never то́же) combines with the conjunction а. p.407-409. |
| где-то / куда́-то / ка́к-то / когда́-то / почему́-то | somewhere / somewhere(-to) / somehow / once, at some point / for some reason | adverb (indefinite, -то series) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §395(1): denotes a real but unidentified referent (place/manner/time/cause), predominantly in past/present contexts — the adverbial counterpart of the -то indefinite pronoun series (§138, outside this range). p.409-410. |
| где-нибудь / куда́-нибудь / ка́к-нибудь / когда́-нибудь / почему́-нибудь | somewhere/anywhere / somehow/anyhow / ever, at any time / for some/any reason | adverb (indefinite, -нибудь series) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §395(2): used in questions, in future contexts implying a choice not yet made, after imperatives, for varying circumstances across repeated occasions, and (distinctively) to imply inferior/random quality ('not just anywhere, but...'). p.410. |
| где-либо / куда́-либо / etc. | (-либо series: even more indefinite than -нибудь) anywhere/ever at all | adverb (indefinite, -либо series) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §395(3): the strongest degree of indefiniteness in this family — "at any place/time you care to name." p.410. |
| ко́е-где́ / ко́е-как / ко́е-когда́ / ко́е-куда́ | in various places / with great difficulty, carelessly / occasionally / to a particular place | adverb (indefinite, ко́е- series) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §395(4): ко́е-как has two quite distinct glosses depending on context — 'with great difficulty' (of an accomplishment) vs. 'carelessly, any old how' (of quality) — a genuine ambiguity worth flagging for slang-mechanics analysis given the pejorative-quality sense's colloquial productivity. p.410-411. |
| нигде́ / никуда́ / ника́к / никогда́ / ниотку́да / ниско́лько | nowhere / nowhere(-to) / in no way / never / from nowhere / not at all | adverb (negative, ни- series) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §396: formed by prefixing ни- onto the corresponding где/куда/как/когда/откуда/сколько; combines obligatorily with не (or, in a copula-less sentence, нет) exactly like the negative pronoun series (§133) — and, like negative pronouns, these can stack multiple negatives in a single sentence (Никто́ никогда́ никуда́ не е́здит 'no one ever goes anywhere'). Note the fixed-phrase distinction ни ра́зу 'not once' vs. не раз 'more than once'. pp.411-412. |
| не́где / не́зачем / не́когда / не́куда / но́ткуда | there is nowhere (to) / there is no point (in) / there is no time (to) / there is nowhere (to, direction) / there is no place from which | adverb (impersonal-infinitive "potential negative" series) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §397: the "potential negative adverb" series (parallel to the potential negative pronoun series, §137), used only with an infinitive in an impersonal (or personal-dative-experiencer) construction — Ей не́когда бы́ло разгова́ривать 'she had no time to talk'; не́когда also independently means 'once, at one time'. Has a positive counterpart with есть/бы́ло/бу́дет + куда́: Есть куда́ пойти́ 'there is somewhere to go'. pp.412-413. |

### §381 Adverbs — introductory comments

Adverbs are indeclinable; they modify verbs, adjectives, other adverbs, or nouns, and answer "where/
when/how/why/for what purpose/to what extent." Distinctively, essentially *all* Russian adverbs derive
historically from another part of speech (though for the primary adverbs — так, там, тогда́, etc. — the
original derivation is no longer synchronically transparent). Adjectives are the most productive source.
p.395.

### §382 Adverbs derived from adjectives

The dominant pattern (-о/-е) simply reuses the neuter short-form adjective ending, sometimes with a
stress shift that distinguishes the adverb from the adjective (больно́ 'is sick' vs. бо́льно 'painfully,
it hurts'). Adjectives lacking a plain -о/-е adverb instead form one periphrastically with по- + the
dative masculine/neuter singular (по-но́вому 'in a new way', по-пре́жнему 'as before'). Adjectives in
-ский/-цкий take -и (логи́чески 'logically'), with nationality/animate-connotation adjectives optionally
adding по- (по-ру́сски 'in Russian'); when по- is present, the adverb answers "similar to whom/what?"
rather than "how/in what way?" — a genuine semantic split riding on a single morphological choice.
Adjectives of the "wolf's" type (§151(1)) form adverbs in -ьи, always with по- (по-медве́жьи 'like a
bear'). A further, more opaque pattern fossilizes a preposition + the oblique case of an adjective into
a single word (с + old genitive *пра́ва → спра́ва 'on/from the right') — genuinely unproductive today,
a closed set of frozen historical formations. pp.395-398.

### §383 Adverbs derived from nouns

Many adverbs are simply the frozen instrumental singular of a noun (верхо́м 'on horseback', ша́гом 'at a
walking pace' [implied by the pattern], шёпотом 'in a whisper') — some from nouns no longer otherwise in
use (пешко́м 'on foot', укра́дкой 'furtively'). Others fossilize a preposition-noun phrase into one word
across every oblique case (вслух 'aloud' [acc.], и́здали 'from afar' [gen.], кста́ти 'apropos' [dat.],
сли́шком 'too' [instr.], вме́сте 'together' [prep.]) — a genuinely rich, cross-case word-formation
pattern. A distinct location/destination-pair subset (вдали́/вдаль, внизу́/вниз, внутри́/внутрь,
впереди́/вперёд, наверху́/наве́рх) formally encodes the same location-vs-direction distinction already
seen in §387's primary spatial adverbs — this static/directional split recurs as a genuine structural
theme across multiple word classes in Russian, worth flagging to the mechanics-analysis phase as a
systemic feature, not a one-off quirk. pp.398-399.

### §384 Adverbs derived from verbs

Covered in more depth already at §368-380 (gerund-derived adverbs); this section is a short
cross-reference restating the pattern (кра́дучись 'stealthily', сло́мя го́лову 'at breakneck speed', an
adverbial phrase built on a fossilized perfective gerund). p.399.

### §385 Adverbs derived from numerals

A productive series: вдвоём/втроём/вчетверо́м... 'as a group of two/three/four', во-пе́рвых/во-вторы́х/
в-тре́тьих... 'in the first/second/third place', одна́жды/два́жды/три́жды... 'once/twice/thrice' — plus
впервы́е 'for the first time', наедине́ 'in private', and the idiom оди́н на оди́н 'tête-à-tête'. p.400.

### §386 Adverbs derived from pronouns

Demonstrative-pronoun-derived adverbs include зате́м/пото́м 'afterwards' (near-synonyms, with a genuine
usage split covered by the source at length: пото́м is commoner, and picks up secondary colloquial senses
'later' and 'besides,' while зате́м specifically can denote purpose — 'that's what I came for'),
сейча́с 'now' (broader in temporal range than тепе́рь, able to refer to imminent past or future as well
as strict present), and the pair с тех пор/до тех пор 'since then/until then'. Interrogative-pronoun-
derived adverbs include заче́м? 'for what purpose?' (asks about intended purpose) vs. почему́? 'why?'
(asks about cause) — a clean purpose/cause distinction English "why" collapses. Possessive-pronoun-
derived adverbs (по-мо́ему, по-тво́ему, по-на́шему, по-ва́шему 'in my/your/our/your[formal] opinion')
have a stress pattern distinguishing them from the dative case of the same pronouns (моему́ 'to my...').
Весь-derived adverbs include везде́/всю́ду 'everywhere', весьма́ 'extremely', совсе́м 'quite/entirely' (with
a subtle scope-of-negation ambiguity the source flags directly: Э́то не совсе́м пра́вда 'that's not
QUITE true' [partial truth] vs. Э́то совсе́м не пра́вда 'that's not true AT ALL' [word order changes
which word совсе́м modifies]). pp.400-401.

### §387-388 Primary spatial and temporal adverbs

Fully captured in the vocabulary table above. Key structural point: Russian's spatial-adverb system
cleanly three-ways location (где), direction-to (куда́), and direction-from (отку́да) — English "where"
covers all three, forcing disambiguation by context or extra words ("where FROM," "where TO") that
Russian bakes directly into the lexeme. Temporally, когда́/как's split (§388(2)) between general
time-clauses (когда́/в то вре́мя как) and complement clauses after perception verbs (как) is a genuinely
fine distinction with no direct single-word English analogue. §388(3)'s как/как вдруг pattern for
narrating a sudden interruption (often with a negated main clause, or не успе́ть/едва́) is a distinctive
narrative-syntax construction worth flagging for any invented-language design modeling suspense/surprise
marking. pp.401-403.

### §389-391 Уж, ещё, and the до́лго/давно́/неда́вно set

Fully captured in the vocabulary table above; these are among the most pragmatically loaded function
words in the language (уж and ещё both carry aspectual-sequencing information beyond their literal
"already/still" glosses, disambiguating which of two past events happened first) — genuinely
high-value targets for any invented-slang system wanting compact temporal/evidential marking. pp.403-406.

### §392-394 Так, interrelating adverbs, то́же/та́кже

Fully captured in the vocabulary table above. §394's то́же/та́кже split (colloquial-vs-formal register,
PLUS a distinct "parallel identification" vs. "additional information" semantic split layered on top of
the register split) is a genuinely rich two-dimensional near-synonym pair worth flagging as a model for
how slang register-splitting can work on an existing near-synonym pair rather than requiring wholly new
vocabulary. pp.406-409.

### §395-397 Indefinite and negative adverb series

Fully captured in the vocabulary table above. These three parallel series (-то/-нибудь/-либо for
positive indefiniteness of increasing vagueness; ни- for negation; the separate "potential negative"
series for impersonal infinitive constructions) together form one of Russian's most systematic
closed-class paradigms — the same six interrogative roots (где/куда́/как/когда́/отку́да/ско́лько) are run
through three or four distinct prefixation/suffixation patterns to cover the full space of
definite/indefinite/negative/"no possibility of" meanings. This kind of systematic paradigmatic
cross-product (same root set × multiple grammatical dimensions) is a productive model for
slang-synthesis mechanics — an invented language reusing one root inventory across several
morphologically-marked dimensions rather than inventing separate roots per meaning. pp.409-413.

### §398-400 Comparative and superlative adverbs

Comparative adverbs in -о/-е are formally identical to short-form comparative adjectives (see §179-180,
outside this range) — the same surface form serves double duty as predicate-adjective-comparative and
adverb-comparative, disambiguated only by syntactic position. Multi-syllable adverbs (and all adverbs
not ending in -о/-е) instead take periphrastic бо́лее 'more'/ме́нее 'less'. Comparative adverbs appear in
the same construction types as comparative adjectives: чем 'than', a bare genitive of comparison,
modification by горазд/мно́го/наму́ного/куда́ 'much', чем...тем 'the...the', по- prefixed for 'a little
more', an instrumental or на + accusative to quantify the exact difference, and как мо́жно + comparative
for 'as X as possible'. §399: бо́льше/бо́лее and ме́ньше/ме́нее split along a neutral/bookish register axis,
with бо́льше/ме́ньше additionally being the *only* option for denoting extent/degree of preference (Он
лю́бит дочь бо́льше, чем сы́на — not *бо́лее). §400: the superlative adverb is comparative-in-е/-ее +
всего́ (comparing an entity against its own other states/times) or всех (comparing against other
entities) — a further genuinely fine-grained distinction ("I work best of all [times]" vs. "I work best
[compared to other people]") collapsed into one English "best." pp.413-415.




## The Preposition (§401-453)

**Scope decision — the largest chapter in this file's range (66 printed pages, §401-453).** The three
genuinely closed preposition inventories (§402 primary, §406 adverbial, §407 noun/verb-derived) are
extracted exhaustively below — this IS the vocabulary of the Russian preposition system. The extensive
per-noun idiosyncrasy lists for в/на selection (§409, geographic terminology; §410, ordinary nouns with
different в/на meanings) are each 20-30 entries long and function exactly like a "vocabulary box" of
drilled examples illustrating one governing principle (idiosyncratic, non-rule-derivable в/на case
selection per lexical item) — per the coverage rule and copyright discipline, these are paraphrased with
a representative sample rather than reproduced in full; the governing PRINCIPLES (which noun classes go
which way, and why) are captured in full since those are the actual grammar content. The semantic
sub-chapters (§408-453) are paraphrased with their central rule stated precisely and 1-3 illustrative
collocations kept per rule, since the bulk of the source's own text here is worked examples reinforcing
one point already stated, not new distinct grammar/vocabulary.

### Closed preposition inventories

| Term | Gloss (central meaning(s)) | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| без | without (+ gen.) | preposition (primary) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §402(1). p.417. |
| в | into (+ acc.) / in (+ prep.) | preposition (primary) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §402(2); by far the most semantically extended preposition in the language — see §408-413. p.417. |
| для | for (+ gen.) | preposition (primary) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §402(3). p.417. |
| до | as far as (+ gen.) | preposition (primary) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §402(4); also central to the temporal terminal-point and spatial-limit systems (§425, §434). p.417. |
| за | behind (+ acc., motion / + instr., static) | preposition (primary) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §402(5); one of the most polysemous prepositions — spatial, causal, purposive, and extent meanings all documented separately (§414-415, §443, §446, §445). p.417. |
| из | out of (+ gen.) | preposition (primary) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §402(6); the systematic opposite of в (§408(3)). p.417. |
| из-за | from behind (+ gen.) | preposition (compound-primary) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §402(7) Note (a): traditionally grouped with the primaries though not strictly one; also a major causal preposition (§443(1)). p.417. |
| из-под | from under (+ gen.) | preposition (compound-primary) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §402(8) Note (a); also denotes a container's former contents (§450(3): буты́лка из-под молока́ 'an [empty] milk bottle'). p.417. |
| к | towards (+ dat.) | preposition (primary) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §402(9); the systematic opposite of от (§420). p.417. |
| кро́ме | except for (+ gen.) | preposition (primary) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §402(10). p.417. |
| ме́жду | between (+ instr.) | preposition (primary) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §402(11); occasionally + genitive plural in poetic/idiomatic contexts (ме́жду двух огне́й 'between the devil and the deep blue sea'). p.417, 439-440. |
| на | on to (+ acc.) / on (+ prep.) | preposition (primary) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §402(12); the second major semantically-extended spatial preposition, paired systematically with в (§408-413). p.417. |
| над | above (+ instr.) | preposition (primary) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §402(13); unlike под, never takes the accusative (no directional "to above" sense). p.417, 439. |
| о | against (+ acc.) / about, concerning (+ prep.) | preposition (primary) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §402(14); spelled об before а/э/и/о/у, обо in a few fixed combinations (обо всём, обо мне). p.417. |
| от | from (+ gen.) | preposition (primary) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §402(15); the systematic opposite of к; also a major causal preposition (§443). p.417, 420, 443. |
| пе́ред | in front of (+ instr.) | preposition (primary) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §402(16); also denotes the object of guilt/duty/responsibility (§444(3)). p.417, 437, 466. |
| по | up to (+ acc.) / along (+ dat.) / after (+ prep.) | preposition (primary) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §402(17); one of the most multivalent prepositions — spatial extent-along-a-surface, distributive, causal, criterial, and communication-medium meanings are all separately documented. p.417, 424, 443-448, 451. |
| под | under (+ acc., motion / + instr., static) | preposition (primary) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §402(18); systematically parallels за's acc./instr. motion/static split. p.417, 417-419. |
| при | in the presence of (+ prep.) | preposition (primary) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §402(19); a genuinely rich preposition for coincidence-in-time and attachment meanings (§422, §442). p.417. |
| про | about (+ acc., colloquial) | preposition (primary) | colloquial | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §402(20); a colloquial synonym of о + prepositional (§453(3) Note). p.417. |
| ра́ди | for the sake of (+ gen.) | preposition (primary) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §402(21). p.417. |
| с | approximately (+ acc.) / down from (+ gen.) / with (+ instr.) | preposition (primary) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §402(22); three unrelated central meanings split by case governed — a genuinely striking case of one preposition doing three jobs distinguished only by the case of its object. p.417. |
| у | at (+ gen.) | preposition (primary) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §402(23); also 'at the house/place of' (§420(1)(ii)) and the source of borrowing/theft/inquiry (§450(6)). p.417, 442, 479. |
| че́рез | across (+ acc.) | preposition (primary) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §402(24); also central to the temporal "after the expiry of" system (§439(2)(i)). p.417, 424, 459. |
| близ / вблизи́ / вдоль / взаме́н / вме́сто / вне / внутри́ (loc.) / вну́трь (dir.) / во́зле / вокру́г / вопреки́ (+dat.) / впереди́ / вро́де / ми́мо / навстре́чу (+dat.) / накану́не / наперекор (+dat.) / напро́тив / о́коло / относи́тельно / по́дле / подо́бно (+dat.) / позади́ / поперёк / по́сле / посреди́ / про́тив / све́рх / свы́ше / сза́ди / сквозь (+acc.) / согла́сно (+dat.) / среди́ | near / close to / into the depths of / along / in exchange for / instead of / outside / inside (location) / inside (direction) / close to / around / contrary to / in front of / like / past / towards / on the eve of / in defiance of / opposite / near / with regard to / by the side of / similar to / behind / across, athwart / after / in the midst of / opposite / above / more than / behind / through / according to / among | preposition (adverbial, all + genitive unless noted) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §406(1): the full one-word adverbial-preposition inventory — a genuinely closed, exhaustively-listable set, distinct from the primary prepositions in deriving historically from adverbs. p.421-422. |
| вблизи́ от / вдали́ от / вме́сте с (+instr.) / впло́ть до / всле́д за (+instr.) / незави́симо от / ря́дом с (+instr.) / согла́сно с (+instr.) | close to / far from / together with / right up to / (immediately) after / irrespective of / next to / in accordance with | preposition (adverbial, compound with a primary) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §406(2): the second, compound-adverbial inventory — an adverbial preposition fused with a primary preposition. p.422. |
| поря́дка / посре́дством / путём | of the order of / by means of / by dint of | preposition (noun-derived, one-word, + genitive) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §407(1)(i). p.422. |
| в ви́де / ввиду́ / в интере́сах / в ка́честве / в направле́нии / во вре́мя / в по́льзу / в продолже́ние / в результа́те / в си́лу / всле́дствие / в сто́рону / в тече́ние / в хо́де / в це́лях / за счёт / на протяже́нии / с це́лью | in the form of / in view of / in the interests of / in the capacity of / in the direction of / during / in favor of / in the course of / as a result of / on the strength of / in consequence of / in the direction of / during the course of / during the course of / for the purpose of / at the expense of / over the course of / with the object of | preposition (noun-derived, one primary + noun, all + genitive) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §407(1)(ii): a very productive Russian pattern — a noun in a fixed oblique case fused with a governing primary preposition to create a new compound preposition, heavily used in formal/bureaucratic/scientific registers. p.422. |
| в зави́симости от / в отли́чие от / в связи́ с (+instr.) / по направле́нию к (+dat.) / по отноше́нию к (+dat.) / по сравне́нию с (+instr.) | depending on / unlike / in connection with / in the direction of / in relation to / by comparison with | preposition (noun-derived, two primaries) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §407(1)(iii): the same fusion pattern, now sandwiching the noun between two primary prepositions. p.422. |
| благодаря́ (+dat.) / включа́я (+acc.) / начина́я с (+gen.) / несмотря́ на (+acc.) / не счита́я (+gen.) / спустя́ (+acc.) / су́дя по (+dat.) | thanks to / including / beginning with / despite / not counting / after / judging by | preposition (verb-derived, from gerunds) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §407(2): cross-referenced to §380's fuller treatment of gerund-to-preposition grammaticalization, already captured in this file's Gerunds section. Спустя́ can precede or follow its noun (две неде́ли спустя́ / спустя́ две неде́ли). p.422. |

### §401 Prepositions — introductory comments

A preposition expresses the relationship between two words; every Russian preposition governs an
oblique case of its object (some govern two or three different cases with different meanings). Three
broad formation classes exist: primary (a small closed set of monomorphemic prepositions), adverbial
(derived historically from adverbs), and noun-/verb-derived (compound, transparently built from a noun
phrase or gerund). p.416.

### §402 The primary prepositions and their cases

Fully captured in the vocabulary table above — the grid the source itself presents (preposition × case
× central meaning) is one of the most information-dense single pages in the whole book: several
prepositions (за, по, под, с) govern strikingly different, even unrelated, meanings depending purely on
which case follows them, a pattern any invented-language design reusing a small closed adposition
inventory across multiple grammatical roles could study directly. p.416-417.

### §403-405 Repetition, the buffer vowel -о, and stress

Repeating a preposition before each of several co-ordinated objects is normally optional, EXCEPT when
the objects are split across separate clauses, where repetition becomes mandatory. A buffer vowel -о is
inserted on consonant-final primary prepositions before certain consonant clusters — the source
catalogs this cluster-by-cluster (вр-, вс-, вт-, дн-, мн- account for most cases; a further,
narrower set of clusters is preposition-specific, often echoing the preposition's own final consonant).
Prepositions are normally unstressed, but a documented, largely colloquial set of noun+preposition
combinations (mostly with за, на, по, под, до, из, о/об, and mostly body parts, geographic features,
and time words) shifts stress onto the preposition itself — often specifically in an idiomatic/
figurative sense, while the same noun in a literal sense keeps ordinary noun stress (ле́зть на́ стену
'to climb up onto the wall' [literal, preposition-stressed] vs. ле́зть на сте́ну [figurative, 'to go
berserk', noun-stressed] — the source's own minimal pair). This preposition-stress-shift-marks-
idiom/register pattern is a concrete, testable phonological register marker worth flagging for the
mechanics-analysis phase. pp.418-421.

### §408 The core в/на/из/с spatial system

The foundational Russian spatial preposition system: в + prepositional = 'in, inside' (static location);
на + prepositional = 'on, on top of' (static location); в/на + accusative = the directional counterparts
('into'/'onto'); из/с + genitive = the withdrawal counterparts ('out of'/'down from'), systematically
opposed to в and на respectively. This в↔из / на↔с symmetry (each static preposition has one dedicated
"exit" preposition) is close to fully systematic but has a documented set of exceptions (лежа́ть в
посте́ли 'to lie in bed' but встать с посте́ли 'to get out of bed', not *из посте́ли) that must be learned
lexically. в also independently means 'wearing' with articles of clothing (он в боти́нках 'he's wearing
shoes') — distinct from носи́ть 'to wear habitually'. pp.422-424.

### §409-410 Idiosyncratic в/на selection with geographic terms and ordinary nouns

**Sampled, not exhaustive** (source's own list runs to dozens of items; representative selection kept
per the coverage rule). The GOVERNING PRINCIPLES, captured in full: countries take в almost universally,
except island-nations and a few fixed exceptions (на Ку́бе); former-Soviet-republic names mostly take в,
with some -щина-suffixed regional names and Ukraine itself showing lasting в/на variation (a
politically-loaded usage point the source flags: "в Украи́не is becoming increasingly acceptable");
natural terrain features split along an "enclosed" (в: desert, steppe, taiga) vs. "open, elevated, or
flat" (на: highlands, meadow, plain, glade) semantic axis; mountain RANGES take в if their name is
grammatically plural (в Альпах) and на if singular (на Кавка́зе) — a rare case of a noun's own
morphological number determining an unrelated preposition choice; islands/peninsulas/archipelagoes
default to на, with a further exception for -ия-suffixed island names (в Сарди́нии); compass points
always take на; most town/building/organization names take в, EXCEPT a specific cluster of nouns
historically associated with open areas or pre-Revolutionary relay-station complexes (по́чта, ста́нция,
вокза́л, ры́нок, фа́брика, etc.) which take на for purely etymological/historical reasons that are
completely opaque synchronically — the single clearest illustration in this whole chapter of a
preposition choice being lexically memorized rather than semantically predictable. §410 catalogs a
further ~20 ordinary nouns (во́здух 'air', глубина́ 'depth', глаз 'eye', ме́сто 'place', мо́ре 'sea', не́бо
'sky', окно́ 'window', по́ле 'field', ру́ки 'hands', свет 'light', etc.) where в vs. на genuinely shifts
the *meaning*, not just registers a synonym — each pairing is individually idiomatic and worth
learning as a discrete lexical fact rather than derivable from a rule. pp.423-431.

### §411-413 Withdrawal exceptions; nouns of activity/event; extended spatial meanings

A residual class of nouns combines only with с + genitive for withdrawal even when their static location
is expressed by в (самолёт в во́здухе 'the aircraft is in the air' but с во́здуха, never из во́здуха, 'from
the air'). §412: на (not в) is the default preposition for nouns denoting activities/events (на войне́
'at war', на конце́рте 'at a concert', на рабо́те 'at work') — в is reserved for a performance where the
performer is the grammatical subject, or for referring to a work's content. §413: в/на extend
metaphorically to cover 'covered in' (в цара́пинах 'covered in scratches'), distance (в киломе́тре от...
'a kilometre from...'), group membership (в гостя́х 'visiting' — note the source flags this as often a
pure abstraction, usable even for a lone guest), and states/moods (в восто́рге 'delighted', в хоро́шем
настрое́нии 'in a good mood') — plus a sharp minimal pair worth flagging: в са́мом де́ле 'really, indeed'
(confirms a claim) vs. на са́мом де́ле 'in fact, actually' (contradicts appearance/a prior claim) — two
near-identical fixed phrases with opposite rhetorical functions. pp.431-434.

### §414-419 Prepositions of relative position (за/пе́ред/под/над/ме́жду family)

За + instrumental = 'behind, beyond' (static); за + accusative = movement to that position;
из-за + genitive = withdrawal from it — a clean three-way static/directional-to/directional-from
paradigm, mirroring §408's в/на/из-с system but for the "behind" relation specifically. За also extends
to sequence ('one after another'), pursuit ('to chase'), and occupation with an activity. Пе́ред 'in
front of' (+instr. only — unlike за, it has NO accusative directional counterpart: you cannot express
"to move to a position in front of" with пе́ред+acc; a different construction is required). Под
'under': + instrumental for static location (also extending figuratively to 'under arrest/influence/
threat/control'), + accusative for movement-to-underneath (and for 'putting a field under a crop',
'placing under threat'), из-под + genitive for withdrawal (also figuratively 'escaping [someone's]
influence/control'). Над 'above/over' (+instr. only, parallel to пе́ред's directional gap — над also has
no accusative form; повёрх substitutes for 'over the top of' in a physical-covering sense). Ме́жду
'between' and средѝ/посреди́ 'in the middle of, amid' — средѝ additionally can mean 'among, surrounded
by' where посреди́ cannot. Напро́тив/про́тив 'opposite' — про́тив (but not напро́тив) also independently
means 'against, opposed to'. Вдоль 'along', вне 'outside', внутри́/внутрь 'inside' (static/directional),
вокру́г 'around', ми́мо 'past' round out this family (already captured in the §406 inventory table).
pp.434-441.

### §420-423 Prepositions of proximity, approach, and distance (у/к/от family, and near-synonyms)

У + genitive = 'at, by, near' an object, and distinctively also 'at the house/place of' a person (у
сестры́ 'at [my] sister's place') — a use with no single-word English equivalent. К + dative = 'towards'
(a place) or 'to see' (a person) — the systematic directional counterpart of у, and also used for bodily
orientation (стоя́ть бо́ком к мосту́ 'to stand sideways-on to the bridge'). От + genitive = 'away from',
the systematic withdrawal-counterpart of к. A cluster of near-synonymous proximity prepositions (близ,
вблизи́, во́зле, о́коло, недалеко́ от, неподалёку от, ря́дом с) is differentiated by degree of closeness and
register (во́зле implying the greatest closeness; неподалёку more colloquial than недалеко́) — genuinely
fine shading among words English would flatten to "near." Вдали́ от/далеко́ от 'far from' — вдали́ от
crucially cannot express movement (only static distance), while далеко́ от can. pp.441-444.

### §424-425 Prepositions of "along/across/through" and spatial limit

По + dative is the default for movement along/over a surface in an unspecified or multi-directional
way (also extending to "throughout many locations": ходи́ть по магази́нам 'to go round the shops'). Че́рез
+ accusative = 'through, across, via', implying a clear destination/emergence on the other side (so
incompatible with aimless-wandering verbs like броди́ть, гуля́ть, which prefer по instead) — it also
denotes a spatial or recurring interval ('every five kilometres', 'at regular intervals') and an
intermediary ('through an interpreter'). Сквозь + accusative specifically implies difficulty/resistance
in passing through (cf. че́рез, which implies easier passage) and is the only option with a climatic
noun (сквозь тума́н 'through the fog', never *че́рез тума́н). Поперёк 'crosswise, athwart'; вглубь 'deep
into'. До + genitive = 'as far as' (a spatial limit); по + accusative = 'up to and including' a point on
the body or an object (with several idioms built on this exact pattern: сыт по го́рло 'fed up to the back
teeth', влюби́ться по у́ши 'to fall head over heels in love' — literally 'in love up to the ears').
pp.444-447.

### §426-433 Temporal prepositions

A dense, highly lexicalized system for telling time and expressing calendar relationships — в + acc. on
the hour and up to the half-hour, в + prep. on the half-hour, без + gen. after the half-hour (see §206,
outside this range, for the full clock-telling system); в for days/months/this-last-next constructions,
на + accusative instead for ordinals above "first" and for other/next (a systematic "first is special"
pattern recurring across days, parts-of-day, weeks, months, and years alike — the source's own examples
show this pattern generalizing across at least five distinct noun categories, worth flagging as a single
underlying rule rather than five separate coincidental facts); по + dative plural for recurring points
in time ('on Wednesdays'); в for general/epochal time-nouns (age, era, period) but во вре́мя specifically
for activities/events, with a further register/formality gradient among the near-synonyms во вре́мя, в
тече́ние, в хо́де, на протяже́нии, во времена́ (the last reserved for temporally-and-spatially distant
historical contexts) — genuinely rich material for any invented-language temporal/register system. в +
accusative for weather-in-general contexts. Festival names split between в (secular/most festivals) and
на (persisting specifically with religious festivals: на Па́сху 'at Easter', на Рождество́ 'at Christmas')
— another case where an ostensibly single semantic category (festivals) splits its preposition by a
non-obvious criterion (religious vs. secular origin). pp.447-454.

### §434-439 Prepositions denoting temporal terminal points, approach, duration, and sequence

С + genitive 'since/from'; до + genitive 'until' (exclusive) vs. по + accusative 'up to and including'
(inclusive) — a genuinely sharp до/по minimal pair the source illustrates with a single worked example
(a holiday ending 26 March "до 1 April" = back by the 1st, vs. "по 1 April" = back by the 2nd) that is
exactly the kind of testable temporal-boundary distinction worth flagging for any invented calendar/
scheduling vocabulary. К + dative 'by' (a deadline); под + accusative 'towards, approaching' (a time)
or, distinctly, 'on the eve of' a festival (synonym of накану́не). В/за + accusative both denote time
taken to complete an action, with a documented preference for за when в would be ambiguous with a
clock-time reading, or when the duration is being framed as excessive relative to the task. Plain
accusative with no preposition at all marks duration-that-coincides-with-an-ongoing action, while на +
accusative marks a duration that FOLLOWS the completion of an action (a state effective for that
period) — a genuinely subtle "does the time span overlap the action or follow it" distinction realized
purely by presence/absence of a preposition. По́сле 'after' (an event) vs. че́рез 'after the expiry of/in'
(a time period, usable for past, present, or future reference) — че́рез cannot be separated from its
noun; спустя́ can substitute for either in past-tense narration and may precede or follow its noun. По +
prepositional is a formal/scientific synonym of по́сле with verbal nouns (по возвраще́нии 'upon
returning'). За + instrumental marks simple sequence ("year after year"). На + accusative marks a
duration allocated AFTER an action's completion (parallel to §436's overlap/follow distinction).
pp.454-460.

### §440-442 Temporal attributive phrases; positioning within a span; coincidence in time (при)

За + accusative dates a periodical issue; от + genitive dates a document. Средѝ 'in the middle of [a
span]'; ме́жду 'positioned between two named events'. При + prepositional is a genuinely versatile
coincidence-in-time preposition: 'in the presence of', 'in the lifetime of/under [a ruler/regime]'
(при Ста́лине 'under Stalin'), and governing a specific closed set of nouns (вид, звук, мысль,
сло́во/слова́ — 'at the sight/sound/thought/words of') plus nouns of light source, opportunity,
circumstance, and social/political order (при социали́зме 'under socialism'). pp.460-462.

### §443-448 Causal, feeling-object, extent, purposive, concessive, and distributive prepositions

**Causal (§443):** из-за (external cause, unfavorable outcome) vs. благодаря́ (external cause, favorable
outcome) — a genuinely elegant valence-marked pair, with the source noting real-world blurring toward
благодаря́-as-neutral-synonym; от (physical or involuntary-emotional cause) vs. из (motivating,
deliberate-action-triggering emotional cause — уби́йство из ре́вности 'a murder motivated by jealousy'
vs. заплака́ть от ра́дости 'to weep with joy [involuntarily]') — a fine involuntary/deliberate distinction
riding on preposition choice alone; по + dative (cause is itself the noun's inherent meaning: по боле́зни
'due to illness', по гру́пости 'out of stupidity' — but из-за instead when the affected party differs
from the causing party); за + instrumental for absence/worthlessness-as-cause (за неиме́нием 'for want
of'). **Feeling-object (§444):** к + dative (most feelings/attitudes generally), на + accusative
(specifically anger/indignation/resentment), пе́ред + instrumental (guilt/duty/responsibility/fear/
embarrassment — a genuinely coherent semantic cluster around interpersonal accountability), по +
dative (yearning/grief: скуча́ть по де́тям 'to miss the children' — first/second-person pronouns after
this construction take the PREPOSITIONAL case specifically, not the expected dative, an irregular
government worth flagging). **Extent (§445):** в + accusative for dimension-quantifying phrases (ка́бель
толщино́й в ру́ку 'a cable an arm's-width thick') and в + accusative in "N times more/less" comparisons;
в + prepositional and до + genitive both used with сте́пень 'degree' (partially interchangeable, в
preferred at the lower/comparative end); до + genitive for "to the point of" (a rich idiom cluster: до
после́дней ка́пли 'to the last drop', до у́паду 'till you drop'); за + accusative for "in excess of"; на +
accusative for percentages, ratios, monetary values, grades, and spatial extension; о́коло/поря́дка/с +
accusative all mark approximation, differentiated by what kind of noun each combines with. **Purpose
(§446):** в + accusative (fixed phrases: в защи́ту 'in defense of', в честь 'in honor of'), для + genitive
('meant/designed for' — can also govern a verbal noun as a periphrastic purpose clause), за + accusative
(the object of struggle/competition, OR, distinctly with instrumental, 'to fetch': идти́ за водо́й 'to go
for water'), на + accusative (an aspired-to profession, a tested quality, a precautionary purpose: на
вся́кий слу́чай 'just in case'), о + prepositional (the object of a plea/request), под + accusative (an
area's designated function). **Concessive (§447):** несмотря́ на + accusative is the default/neutral
option; вопреки́, невзира́я на, наперекор belong to more official registers; при + весь ('for all
[his talent]...') is a further concessive construction worth flagging as distinct from несмотря́ на.
**Distributive (§448):** по + dative (singular nouns) / по + accusative (the numerals 2-4, 200-400, and
increasingly in modern usage most other numerals too, in a construction that has shifted from
colloquial-only to fully standard-written over time — an explicit, dateable register-shift the source
itself flags) expresses "X each" — По чём? 'how much (each)?' is a fixed colloquial fixed-phrase built
directly on this construction. pp.462-474.

### §449-453 Summary tables: prepositions grouped by the case they govern

**Scope note:** these five sections re-organize (by governed case, rather than by semantic domain) much
of the same material already covered above by domain — genuinely new material specific to this
re-organization is what's paraphrased here; already-covered ground is cross-referenced rather than
repeated. §449 (accusative): в as the target of throwing/shooting/striking (distinct from its already-
covered directional sense); в + a game name with игра́ть; в + belief/infatuation (ве́рить в, влюби́ться в);
за denoting reward/payment/punishment-for, mistaken-identity ('to pass oneself off as'), and seizing-by
(взять за́ руку 'to take by the hand'); a fixed idiom что за (= како́й, invariant for case: Что за
му́ка! 'what torment!'); на with a large, heterogeneous cluster of abstract-relation verbs/nouns
(жа́ловаться на 'to complain about', наде́яться на 'to hope for', ме́да/спрос на 'fashion/demand for');
о + accusative for the object of collision/friction (Во́лны разбива́ются о ри́фы 'waves smash against the
reefs'); под + accusative for 'support' (под ру́ки) and 'imitation/in the style of' (петь под Шаля́пина
'to sing in imitation of Shalyapin'). §450 (genitive): для in a comparative sense ('warm for November');
из as source/material/composition; от in protective/curative contexts (защища́ть от, лека́рство от
ка́шля); с with verbs of beginning and for spelling ('with a capital letter' — vs. че́рез for a
non-initial letter, e.g. параши́т is "spelled with а ю"); у as the source of borrowing/purchase/theft/
inquiry (a genuinely productive "human source" preposition, contrasted with от for a passive-recipient
context and с for tax/due-payment contexts — a three-way source-preposition split by the recipient's
agency). §451 (dative): к relating a part to a whole, or marking emotional-reaction nouns (к сожале́нию
'unfortunately', к сча́стью 'fortunately' — a small, highly productive discourse-adverbial construction);
по for communication media (по ра́дио, по по́чте, по телефо́ну), for 'according to', for a judgment
criterion, and (echoing §449's в-as-target sense) for a diffuse/moving target (стреля́ть по врагу́ 'to
fire on the enemy', vs. в + a fixed/specific target). §452 (instrumental): за linking observation/
surveillance verbs to their object (следи́ть за 'to keep watch on'); с as the core comitative
'with/together with' preposition, extending to public-transport-vehicle names when adjective-qualified.
§453 (prepositional): в linking accusation/suspicion/confession/certainty/doubt/reproach vocabulary to
its object (обвини́ть в 'to accuse of', призна́ться в 'to confess to'); на for musical instruments and
languages (игра́ть на скри́пке, говори́ть на трёх языка́х); о as the core 'about, concerning' preposition
(про being its colloquial synonym, already noted in §402's про entry); при meaning 'given, in view of,
thanks to' when weighing a circumstance against an outcome. pp.474-483.

## The Conjunction (§454-467)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| и | and | conjunction (co-ordinating, connective) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §455(1). p.485. |
| и... и | both... and | conjunction (co-ordinating, connective, emphatic) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §455(2); literary-register synonyms: как... так и, and (still more emphatic) не то́лько... но и. p.485. |
| ни... ни | neither... nor | conjunction (co-ordinating, connective, negative) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §455(3): не is added only with a single shared predicate across both subjects — a subtle agreement rule genuinely worth flagging (Ни он, ни она́ не игра́ет vs. Ни он, ни она́ не игра́ет, ни поёт with no не needed on the second clause when there are two separate predicates). p.485-486. |
| а | and, but, whereas | conjunction (co-ordinating, adversative) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §456(1): links contrasting-but-not-conflicting ideas, introduces a positive correction after a negative (Приро́да не храм, а мастерска́я 'nature is not a temple, but a workshop'), introduces supplementary questions/statements, and introduces parenthetical asides. Contrasted directly against и (adds compatible information) and но (antithesis/incompatibility) in the source's own three-way minimal-triplet illustration — a clean model for how a single conjunction-choice slot can carry three distinct logical relations. p.486-488. |
| но | but | conjunction (co-ordinating, adversative) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §456(2): links genuinely incompatible/unexpected ideas; near-synonym of одна́ко 'however' (which CAN replace но) and несмотря́ на э́то 'despite this' (which instead combines with it, except sentence-initially). p.486-488. |
| одна́ко | however | conjunction/adverb | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §456(2) Note. p.487. |
| всё же | all the same | conjunction/adverb (adversative) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §456(2) Note. p.487. |
| зато́ | on the other hand, but then | conjunction (adversative) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §456(2) Note: До́рого, зато́ хоро́шая вещь 'It's expensive, but then it's quality'. p.487. |
| и́ли | or | conjunction (disjunctive) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §457(1): does not normally appear in negative contexts (negative "or" uses ни...ни instead); 'or else/otherwise' is instead rendered by а то/а не то/ина́че. p.488-489. |
| и́ли... и́ли (ли́бо... ли́бо) | either... or | conjunction (disjunctive) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §457(2). p.489. |
| не то... не то | either... or (implying difficulty of identification) | conjunction (disjunctive) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §457(3): distinctively marks genuine uncertainty about which of two things is the case, not just presenting alternatives. p.489. |
| то... то | now... now | conjunction (disjunctive, alternation) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §457(4): marks alternating/oscillating states (то красне́ет, то бледне́ет 'now he blushes, now he pales'). p.489. |
| то ли... то ли | maybe... maybe | conjunction (disjunctive, conjectural) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §457(5): distinctively marks the speaker's own uncertainty/guesswork, not objective alternation. p.489. |
| что | that | conjunction (subordinating, explanatory) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §458(1): unlike English "that" (droppable: 'I think (that) he's out'), Russian что is never droppable. Also combines with a fixed set of verb/adjective + preposition constructions (изве́стен тем, что..., наказа́ть за то, что..., обвиня́ть в том, что..., поздра́вить с тем, что...) to render an English "preposition + -ing" — genuinely useful as a template for any invented-language calquing of English gerund-complement constructions. p.489-490. |
| чтобы (explanatory) | that, to (after verbs of request/command/warning) | conjunction (subordinating, explanatory) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §458(2): чтобы + past tense after verbs of asking/ordering/warning (проси́ть, прика́зывать, предупрежда́ть) — preferred specifically in impersonal constructions; when the governing verb takes a direct/indirect object instead, a plain infinitive is used instead (contrast Скажи́те ему́, чтобы он не уходи́л vs. Он попроси́л меня́ откры́ть дверь). p.490-491. |
| бу́дто / бу́дто бы | as if, that (casting doubt on a claim) | conjunction (subordinating, explanatory, doubt-marking) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §458(3): distinctively questions the truth of the reported statement — 'allegedly'-flavored, not neutral reported speech. Also doubles as a comparative conjunction (§464(2)). p.491. |
| я́кобы | allegedly, supposedly | conjunction/particle (doubt-marking) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §458(3): a close synonym of бу́дто/бу́дто бы in this "casting doubt" function. p.491. |
| благодаря́ тому́ что | thanks to the fact that | conjunction (subordinating, causal) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §459(1): favorable-circumstance causal, parallel to the preposition благодаря́ (§443(1)). p.492. |
| ввиду́ того́ что | in view of the fact that | conjunction (subordinating, causal, official register) | formal | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §459(2); near-synonyms вследствие того́ что 'in consequence of the fact that' and в си́лу того́ что 'on account of the fact that' belong to the same official register. p.492. |
| из-за того́ что | because of the fact that (unfavorable) | conjunction (subordinating, causal) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §459(3): parallel to the preposition из-за (§443(1)), typically unfavorable outcome. p.492. |
| оттого́ что | because of the fact that (involuntary cause) | conjunction (subordinating, causal) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §459(4): parallel to the preposition от's involuntary-cause sense (§443(3)(i)). p.492. |
| поско́льку | as long as, insofar as | conjunction (subordinating, causal/conditional) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §459(5). p.492. |
| потому́ что | because | conjunction (subordinating, causal) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §459(6): the default neutral causal conjunction, always following (never preceding) its main clause — unlike its near-synonym так как, which can precede or follow. A comma splits потому́/что when the cause is emphasized by an inserted word (бу́дто бы, ещё и, мо́жет быть, то́лько). p.492-493. |
| так как | because, since | conjunction (subordinating, causal) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §459(7): virtually identical in meaning to потому́ что, but can precede OR follow the main clause (unlike потому́ что, which always follows) — a genuine word-order flexibility distinction between two near-synonyms. p.493. |
| под предло́гом что | on the pretext that | conjunction (subordinating, causal, pretended cause) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §459(7) Note (b): specifically marks a FALSE/pretended cause, distinct from every other causal conjunction in this set, all of which assert a genuine cause. p.493. |
| и́бо | for | conjunction (subordinating, causal, high style) | literary | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §459(7) Note (b): restricted to high/scientific style. p.493. |
| чтобы (purpose) | in order to, in order that | conjunction (subordinating, purpose) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §460: same-subject clauses take чтобы + infinitive; different-subject clauses take чтобы + past tense — the identical same-subject/different-subject split already documented for §308-310's subjunctive-of-desire construction, now shown to be the SAME underlying principle governing purpose clauses too (a single generalization spanning three separately-numbered grammar sections). Omitted after verbs of motion with no subject change (Он пришёл поговори́ть 'he came to chat'), except when the purpose is not strictly sequential, involves a negated infinitive, or the infinitive carries adverbial modifiers. p.494-495. |
| для того́ чтобы / с тем чтобы | in order to/that (emphatic) | conjunction (subordinating, purpose, emphatic) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §460(ii): throws the purposive meaning into greater relief than plain чтобы. p.494. |
| вме́сто того́ чтобы | instead of | conjunction (subordinating, purpose, rejected alternative) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §460(v). p.495. |
| так что | so, so that | conjunction (subordinating, result) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §461: the default neutral result conjunction. p.495. |
| всле́дствие чего́ / в результа́те чего́ | in consequence of which / as a result of which | conjunction (subordinating, result, official register) | formal | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §461. p.495. |
| е́сли | if | conjunction (subordinating, conditional) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §462(1): fully treated already in this file's Conditional Mood section (§304-305). p.496. |
| е́сли не | unless | conjunction (subordinating, conditional, negative) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §462(2). p.496. |
| при усло́вии что | on condition that | conjunction (subordinating, conditional) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §462(3). p.496. |
| раз | if, since, now that | conjunction (subordinating, conditional, colloquial-to-literary) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §462(4): the source explicitly notes this word has migrated from conversational into literary style over time — a documented, dateable register shift. p.496. |
| ко́ли / коль; коль ско́ро | if (colloquial/obsolescent) | conjunction (subordinating, conditional, dated) | archaic | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §462(5): ко́ли/коль are flagged explicitly as colloquial AND obsolescent, rarely found in writing; коль ско́ро instead has a specific polemical/rhetorical-intensity register. p.496. |
| доста́точно | it is sufficient, all it takes | conjunction/predicate (subordinating, conditional nuance) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §462(6): a predicate word that can acquire a genuinely conditional shading ('all it would take is X, and Y would happen'). p.496-497. |
| хотя́ / хоть | although | conjunction (subordinating, concessive) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §463(1): the main clause can be reinforced with а, зато́, но, or одна́ко for extra contrastive emphasis. p.497. |
| пусть (пуска́й) | even if, albeit | conjunction (subordinating, concessive, colloquial/emotive) | colloquial | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §463(2): distinctively colloquial/emotive register compared to хотя́. p.497. |
| как | as, like | conjunction (subordinating, comparative) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §464(1): introduces a direct comparison; intensified by та́к же как or то́чно та́к же как. p.497-498. |
| бу́дто / как бу́дто (бы) / сло́вно / то́чно | as if | conjunction (subordinating, comparative, hypothetical) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §464(2): бу́дто alone introduces a statement seemingly at odds with reality (overlapping its explanatory-conjunction doubt-marking sense, §458(3)); the compound forms как бу́дто (бы)/сло́вно/то́чно instead compare two genuinely similar (not doubted) situations — a subtle scope distinction within one small conjunction family. p.497-498. |
| до того́ как | before | conjunction (subordinating, temporal) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §465-466(1). Intensified forms: задо́лго до того́ как 'long before', ещё до того́ как 'even before'. p.499-500. |
| пе́ред тем как | just before | conjunction (subordinating, temporal, close proximity) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §466(2): retains перед's sense of close temporal proximity (unlike the more neutral до тог как); an infinitive can replace the finite clause under same-subject conditions. p.499-500. |
| пре́жде чем | before | conjunction (subordinating, temporal) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §466(3): synonym of до того́ как in strictly temporal contexts, but distinctively required (not just preferred) in precautionary, "you-should-X-before-Y" inexpediency, or logical-dependency framings — a genuine functional split within apparent synonymy. p.500. |
| по́сле того́ как | after | conjunction (subordinating, temporal) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §466(4): a perfective gerund can substitute when both clauses share a subject (parallel to §377's gerund-for-adverbial-clause substitution, already documented). p.500-501. |
| пока́ | while, by the time (that) | conjunction (subordinating, temporal) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §466(5): covers both 'while' (two parallel or interrupting actions) and 'by the time that'; synonym в то вре́мя как available for the 'while' sense; also used in an "opportunist" sense ('while the coast is clear'). p.501. |
| пока́... не | until | conjunction (subordinating, temporal, negative) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §466(6): takes the conventional (non-literal) не — usable with both future and past tense; a genuinely counterintuitive negative-particle-that-doesn't-negate pattern worth flagging for any invented-language "expletive negation" feature. p.501-502. |
| с тех пор как | since | conjunction (subordinating, temporal) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §466(7). p.502. |
| когда́ | when, as, whenever, after | conjunction (subordinating, temporal) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §467(1): the general-purpose temporal conjunction; a gerund can substitute under same-subject conditions (parallel pattern to по́сле того́ как above). Also combines specifically with жда́ть and люби́ть as a complement-clause introducer (Мы жда́ли, когда́ кто́-нибудь появи́тся 'we waited for someone to appear'). p.502-503. |
| как (temporal, sudden) / как вдруг | when (suddenly) | conjunction (subordinating, temporal, interruption) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §467(2)-(3): marks a sudden interruption, typically paired with a negated main-clause verb (especially не успе́ть 'not to have had time to') or едва́ 'hardly', or with сто́ит/сто́ило 'no sooner than' (which combines only with perfective infinitives) — directly parallel to the adverbial как/как вдруг already documented in §388(3), confirming this is one coherent construction spanning both word classes. p.503-504. |

### §454 Conjunctions — introductory comments

Two broad classes: co-ordinating (link elements of equal grammatical status — connective, adversative,
disjunctive) and subordinating (introduce a dependent clause — explanatory, causal, conditional,
concessive, comparative, temporal, purpose, result). Many compound conjunctions traditionally written
with an internal comma (ввиду́ того́(,) что) now also appear without one; keeping the comma throws the
subordinate clause's own meaning into sharper relief — a live orthographic variation, not a hard rule.
p.484.

### §455-457 Co-ordinating conjunctions: connective, adversative, disjunctive

Fully captured in the vocabulary table above. The three-way а/и/но minimal-triplet the source builds
(§456(3): "Он молодо́й, и/а/но..." differing only by which conjunction fills the slot) is a genuinely
elegant, compact illustration of how three logical relations (addition, contrast, antithesis) can be
carried by conjunction choice alone holding everything else constant — a directly reusable model for
designing an invented language's own small closed conjunction-choice paradigm. The ни/и agreement rules
(§455(3)) and gender-mismatch predicate-compatibility rules recurring across ни...ни and и́ли...и́ли
constructions are a genuinely subtle piece of Russian syntax worth flagging to the mechanics-analysis
phase. pp.485-489.

### §458 Explanatory conjunctions

Что introduces reported statements (never omissible, unlike English "that") and also renders English
"preposition + -ing" via a closed set of verb-plus-preposition-plus-[то,]-что constructions (fully
captured in the vocabulary table). Чтобы + past tense follows verbs of request/command/warning,
specifically in impersonal constructions (a plain infinitive substitutes when the governing verb takes
a direct/indirect object instead — the identical same-subject/different-subject-style split recurring
yet again). Бу́дто/бу́дто бы/я́кобы all cast doubt on the truth of what they introduce — a genuinely
compact evidentiality marker built into ordinary subordinating conjunctions, worth flagging as a model
for encoding speaker-stance-toward-truth directly in a function word rather than a separate modal
particle. pp.489-491.

### §459 Causal conjunctions

A graded register/valence system fully captured in the vocabulary table: потому́ что (neutral default,
clause-final-only) and так как (neutral, either clause order) are near-perfect synonyms differing only
in word-order flexibility; благодаря́ тому́ что (favorable outcome) and из-за того́ что (unfavorable
outcome) mirror the causal-preposition valence split already documented at §443(1); ввиду́ того́ что /
всле́дствие того́ что / в си́лу того́ что form an official-register cluster; под предло́гом что
distinctively marks a FALSE cause rather than a genuine one. pp.492-493.

### §460-461 Conjunctions of purpose and result

§460's чтобы-governed same-subject/different-subject split is now documented as the SAME underlying
rule already seen governing §308's subjunctive-of-desire and §310's purpose clauses — worth flagging to
the mechanics-analysis phase as one generalization spanning three separately-numbered grammar sections
of this source, a good example of how a reference grammar's own numbering can obscure an underlying
unity that a systematic cross-file analysis surfaces. Чтобы is dropped after a same-subject verb of
motion (Он пришёл поговори́ть) except under three specific conditions (non-sequential purpose, a negated
subordinate infinitive, or an adverbially-modified infinitive) — each independently worth remembering.
§461's result conjunctions (так что neutral; всле́дствие чего́/в результа́те чего́ official-register) are
comparatively simple by contrast. pp.494-496.

### §462-463 Conditional and concessive conjunctions

Ко́ли/коль is explicitly flagged by the source as colloquial-and-obsolescent (a dying word, still findable
but rare in writing) — genuinely useful data for any historical/archaic-register modeling in the
slang-synthesis project, since this is one of the few places in this whole book where the source
explicitly marks a word as receding from the language rather than just informal. Раз is flagged as
having moved the OPPOSITE direction — from conversational into literary register — a documented
register migration in the reverse direction from ко́ли/коль, within the same short conditional-conjunction
section. Хотя́/хоть (neutral concessive) vs. пусть/пуска́й (colloquial/emotive concessive) parallel the
familiar core/colloquial split pattern recurring throughout this file. pp.496-497.

### §464 Comparative conjunctions

Как for direct comparison; бу́дто/как бу́дто(бы)/сло́вно/то́чно for hypothetical "as if" comparison, with
a documented internal split (bare бу́дто implies the compared situation is NOT actually the case —
overlapping its §458(3) evidentiality-marking sense — while the compound forms merely compare two
genuinely similar real situations without casting doubt on either). pp.497-498.

### §465-467 Temporal conjunctions

A key typological point stated explicitly by the source: English temporal PREPOSITIONS ('before',
'after', 'until', 'since') double as temporal CONJUNCTIONS with no change of form, but their Russian
prepositional counterparts (до/пе́ред, по́сле, до, с) do NOT do likewise — Russian instead requires a
dedicated, longer conjunctional phrase built from the preposition + a demonstrative + "as/that" (до
того́ как, по́сле того́ как, etc.), fully tabled above. A second key typological point: Russian
consistently uses the FUTURE tense after these temporal conjunctions when future meaning is intended
(когда́ он придёт 'when he arrives' — literally 'when he will arrive'), where English conjunctions like
"when/if/until/as soon as" block the future tense entirely — the same "logical future" rule already
documented at §264 in the Aspect chapter, now shown recurring identically in this entirely separate part
of the grammar (Conjunctions), a good confirmation that this is a deep, pervasive rule rather than a
narrow aspectual footnote. По́сле того́ как and когда́ both allow gerund substitution under a shared-subject
condition — the THIRD context in this file (after §377's general gerund function and §466(4)'s
по́сле-clause-specific note) where the same gerund-for-finite-subordinate-clause substitution shows up,
confirming it as one of the most productive syntactic economy devices in the whole language. pp.498-504.

## The Particle (§468-474)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| ведь | you know, after all (explanatory/reminding) | particle | colloquial | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §470(1), §473(3): explains/justifies, prompts a desired answer, issues a gentle reminder, or administers a mild reproof — genuinely polysemantic, disambiguated only by context/intonation. Of verbal origin per §468(4). pp.506-507, 511-512. |
| вот | here is/there is; now, for instance (citing an example); (in warnings/exclamations) | particle | colloquial | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §470(2), §471(1), §473(4): points something out, cites a statement as illustrative, combines with interrogatives ('that's where/why...'), introduces contrast, issues warnings, and expresses amazement/indignation (Вот дура́к! 'what an idiot!'). pp.506-507, 511. |
| да (particle) | of course, certainly (taken-for-granted); (in self-exoneration/consolation/indefinite answers) | particle | colloquial | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §470(3), §473(5): distinct from да 'yes' and the conjunction да; formally identical to a conjunction per §468(4). pp.507, 512-513. |
| же | now, really (categorical emphasis) | particle | colloquial | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §470(4), §473(7): introduces categorical/insistent emphasis, imparts a peremptory nuance to interrogatives, pins down a place/time precisely (тогда́ же 'at that very point'), marks identity/similarity with demonstratives (тот же 'the same'), intensifies imperatives, and appears in the fixed exclamation на́до же! 'well I never!'. A remarkably productive single particle covering at least six distinct functions. pp.507, 513-514. |
| -то (particle) | (marks a previously-referenced topic; diffidence; emphasis; negative-strengthening) | particle (enclitic) | colloquial | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §470(5), §473(11): distinct from the -то of indefinite pronouns/adverbs (§138, §395); expresses diffidence/hedging, refers back to something already mentioned (a topic-marking function — "I mean..."), adds emphasis to adverbs, and strengthens a negative (не так-то про́сто 'not so simple, actually'). pp.507, 515-516. |
| уж (particle) | definitely, for sure (ruling out contradiction); resignation; condescension | particle | colloquial | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §470(6), §473(12): distinct from the adverb уж 'already' (§389) though formally identical per §468(4); ranges across confident assertion, resigned acceptance, reassurance, and condescension — a genuinely wide emotional range for one small word. pp.507, 516-517. |
| а (particle) | (prompting an answer; making a request; stating the obvious; conversational-exchange filler) | particle | colloquial | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §473(1): formally identical to the adversative conjunction а (§456) but functioning here as a discourse particle with no logical-contrast meaning at all — a clean example of one surface form spanning two entirely different grammatical categories (conjunction vs. particle). pp.510-511. |
| бы́ло | (marks an action begun/intended, then immediately cancelled or reversed) | particle | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §473(2): a genuinely unusual grammaticalized function — appears almost exclusively with perfective verbs (or the imperfectives собира́ться/хоте́ть + a following perfective infinitive), and marks that an action was begun, intended, or nearly completed, and then aborted/reversed (Он подня́л бы́ло го́лову и сно́ва опусти́л 'he raised his head and lowered it again') — a dedicated grammatical marker for "false start" actions, worth flagging as a genuinely rare cross-linguistic category any invented-language aspect system could borrow directly. Can also combine with perfective participles/gerunds. pp.511-512. |
| -ка | come on, do (softening an imperative); mild resolve; indignant challenge | particle (enclitic) | colloquial | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §473(9): attaches to a 1st-person perfective future to denote mild resolve (пойду́-ка домо́й 'I think I'll head home') or softens/intensifies an imperative depending on intonation (gentle exhortation, admiration/scorn, or indignant challenge). pp.514-515. |
| ну | well, come on (exclamation; emphasis; grudging consent; impatience; peremptory command) | particle | colloquial | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §473(10): a maximally polysemantic discourse particle, ranging from enthusiastic exclamation through sarcasm to grudging consent (with a following perfective future) to bare impatience — precise sense is carried almost entirely by intonation, exactly the kind of item the source's own introductory §468(3) example (Петь так петь) illustrates. pp.515. |
| хоть | at least; for example; readiness to indulge; intensity/extreme degree | particle | colloquial | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §473(13): of verbal origin per §468(4); covers a minimum-requirement sense, an exemplifying sense, a permissive/indulgent sense, and (with imperatives) an intensifying sense (хоть отбавля́й 'more than enough, up to here'). Also functions as the concessive conjunction 'even if' (§463(2)). pp.516-517. |
| что (particle) | what, is that so (emphasizing a preceding noun/pronoun in a question; energetic denial in ну что вы!) | particle | colloquial | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §473(14). pp.517. |
| ещё (particle) | (outrage; emphatic affirmation; emphatic denial; warning/threat) | particle | colloquial | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §473(6): formally identical to the temporal adverb ещё (§390) but here purely a discourse-emphasis particle — ещё как! 'you bet!' (affirmation) vs. ещё чего! 'as if!' (denial) are near-opposite readings of the same word, disambiguated entirely by the question it answers. pp.513. |
| и (particle) | even, also, too; (in negatives) either; (emphatic) indeed | particle | colloquial | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §473(8): formally identical to the connective conjunction и (§455) but here a discourse particle — another instance of one word spanning conjunction and particle categories. pp.514. |
| ли | (yes/no question marker; uncertainty; rhetorical questions) | particle (enclitic, interrogative) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §472(5): attaches after the specific word bearing logical stress (not necessarily the verb), including in reported yes/no questions where it follows the "operative" element; omitting ли from a direct question does not trigger word-order inversion — unlike many European languages' question-formation strategies. pp.508-509. |
| ра́зве / неуже́ли | surely (not)? (doubt-marking question particles) | particle (interrogative, doubt-marking) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §472(5): both imply the speaker doubts the statement or believes the opposite is true; неуже́ли is markedly more emphatic and more common in speech than ра́зве, which can also convey simple hesitancy ('I wonder if I should...'). pp.509. |
| де / деска́ть / мол | (particles marking quoted/reported direct speech) | particle (evidential, quotative) | colloquial | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §472(6): a dedicated quotative-evidential particle family with no single-word English equivalent — marks that the speaker is reporting someone else's words rather than asserting their own, roughly "as if to say..." — directly relevant to any invented-language evidentiality system since this is exactly the kind of grammaticalized "reported speech" marker many real languages build as an obligatory category. pp.509-510. |
| вря́д ли / едва́ ли | hardly likely (improbability) | particle (modal, improbability) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §472(7). p.510. |
| бу́дто / как бу́дто / как бы / сло́вно | as if, seemingly (comparison particle use) | particle (comparative) | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §472(8): the same word family already documented as comparative/explanatory conjunctions (§458(3), §464(2)) shown functioning here as particles instead — the conjunction/particle boundary is genuinely porous throughout this whole word class, a recurring theme the source itself calls out at §468(4). p.510. |
| пря́мо / то́-то / так (particle) | simply, really; that's exactly it; determination (emotional-nuance particles) | particle (emotional-emphatic) | colloquial | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §472(9): пря́мо стра́шно! 'simply terrifying!', то́-то бы́ли ра́дости! 'we were overjoyed!', е́хать так е́хать! 'if we're going, let's go!' — a cluster of emphatic-register particles worth flagging as productive slang/colloquial-register vocabulary. p.510. |
| а ведь / да ведь / но ведь | and yet, you know (aggregated particle emphasis) | particle cluster (aggregated) | colloquial | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §474(1)(i): particles can stack for heightened emphasis — this file's fullest documentation of a genuinely productive particle-aggregation mechanism in the language. p.517-519. |
| ещё бы / ещё как | I'll say!, you bet! (aggregated emphatic confirmation) | particle cluster (aggregated) | colloquial | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §474(1)(vi). p.518. |
| не то что́бы уж | not exactly, not quite what you'd call | particle cluster (aggregated, hedging) | colloquial | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §474(1)(viii): a triple-particle hedge softening a description (Клавдия была не то чтобы уж красавица '...wasn't exactly what you'd call a beauty'). p.518. |
| ну и / ну уж / ну уж и / ну-ка / ну что ж | well now! (aggregated ну-particle exclamations) | particle cluster (aggregated) | colloquial | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | §474(1)(ix): the source's final, richest aggregation cluster, all built on ну. p.518-519. |

### §468 The particle — introductory comments

Particles add semantic/emotional nuance to other words or whole utterances without (usually) carrying
independent meaning of their own; a genuine minority are themselves polysemantic (§473). They are
overwhelmingly a colloquial-register phenomenon, frequently stacking with other emotive intensifiers
like diminutives for expressive effect. Crucially, **the same intonation-neutral string can express
opposite pragmatic stances depending purely on intonation** — the source's own example, Петь так петь,
can mean either eager enthusiasm or reluctant resignation depending on how it's said, with no lexical
difference at all. Formally, particles overlap heavily with other word classes: some are identical to
conjunctions (а, да, же), some to adverbs (ещё, то́лько, уж), some to pronouns (то), and some derive from
verbs (ведь, мол, пусть, хоть) — and particles shade into interjections at the edges. This
category-porousness (the same surface form serving as conjunction/adverb/particle depending on syntactic
function) is one of the more striking structural facts in the whole book, worth flagging as a design
principle any invented slang-synthesis system could exploit: a small closed set of short function words
doing heavy pragmatic/emotional lifting via combination and intonation rather than via a large dedicated
vocabulary. p.505-506.

### §469 Particle position in the sentence

No single fixed rule: some particles always precede their target word (да здра́вствует 'long live', ну
пое́хали 'right, let's go'), some always follow it (расскажи́ же, помолчи́-ка), some can appear
sentence-initially, medially, or (occasionally) finally (ведь), and a few (так) can stand between two
repeated forms of the same word (пить так пить 'if we're drinking, let's drink') — a genuinely
distinctive doubling construction with no direct English equivalent. p.506.

### §470 One phrase, six particles: a worked minimal-set illustration

The source's single most efficient illustration of what particles actually do: it takes one fixed base
sentence (Э́то не подлежи́т сомне́нию 'that's beyond doubt') and shows six different particles (ведь, вот,
да, же, -то, уж) each producing a distinct pragmatic shading of the identical propositional content — a
genuinely excellent worked model for how an invented language's particle system could be designed and
documented (one semantically-neutral carrier sentence + a paradigm of particle substitutions, each
independently glossed). pp.506-507.

### §471 Principal meanings expressed by particles

A cross-cutting functional taxonomy independent of any one particle: pointing-out (вот), precision/
narrowing (и́менно, ра́вно, как раз), approximation (почти́, едва́ не, чуть не — note чуть не/едва́ не combine
mainly with verbs), and restriction/exclusion (то́лько, which must immediately precede the word it
qualifies — a strict word-order constraint worth flagging, since misplacement changes what's being
restricted). p.507-508.

### §472 Modal functions of particles

A further functional taxonomy covering: desirability (отдохну́ть бы!), command/exhortation (дава́й), 
confirmation (ещё бы!), negation (не — which precedes exactly the word it negates, and can shift the
logical stress/scope of negation onto a non-verbal constituent: Не кни́гу он чита́ет 'it's not a BOOK he's
reading', with rising intonation marking the negated word — a genuinely important scope-of-negation
mechanism), interrogative marking (ли, ра́зве, неуже́ли — fully tabled above), quotative/reported-speech
marking (де/деска́ть/мол — fully tabled above, a genuine evidentiality category), probability/improbability
(вря́д ли, едва́ ли, пожа́луй), comparison (бу́дто/как бу́дто/как бы/сло́вно), and emotional nuance (пря́мо,
то́-то, так, уж — fully tabled above). Note also: 'yes' in answer to a negative question is rendered by
нет, not да (Вы не лю́бите ко́шек? — Нет, люблю́! 'Don't you like cats? — Yes, I do!') — a systematic
polarity-reversal trap for anyone calquing from English, worth flagging prominently for the
mechanics-analysis phase. pp.508-510.

### §473 The meanings of individual particles

A particle-by-particle catalog (а, бы́ло, ведь, вот, да, ещё, же, и, -ка, ну, -то, уж, хоть, что) — each
entry fully captured in the vocabulary table above, since each of these fourteen particles is itself a
genuine, distinct, high-frequency lexical item central to colloquial register, exactly the kind of
compact-but-loaded function word most valuable for any invented slang-synthesis system modeling register
and stance-marking economically. Бы́ло's "cancelled/aborted action" function (§473(2)) is the single most
typologically distinctive item in this whole set. pp.510-517.

### §474 Aggregation of particles for increased emphasis

Particles stack productively for heightened emphasis — the source's own catalog of 9 documented
aggregation patterns (а ведь/да ведь/но ведь; а ещё; бы уж; вот ещё/вот уж; да и/да уж; ещё бы/ещё как;
та́к э́то; не то что́бы уж; ну и/ну уж/ну уж и/ну-ка/ну что ж) is captured via its most productive/
frequent representatives in the vocabulary table above. This aggregation mechanism — small particles
compounding for cumulative pragmatic force, well beyond what any single one carries alone — is a
directly transferable design pattern for an invented slang register wanting compact, combinable
intensifiers. pp.517-519.

## Word Order (§475-484)

**No new vocabulary table** — this chapter is pure syntax/discourse-structure mechanism; every example
sentence reuses ordinary vocabulary already documented elsewhere in this file or its sibling.

### §475 Word order — introductory comments

Russian's case-marking morphology means word order is far freer than English's — a case ending, not
sentence position, identifies a noun's grammatical role (Ма́шу лю́бит Ива́н still unambiguously means
"Ivan loves Masha," because the accusative -у on Ма́шу fixes her as the object regardless of where she
sits in the sentence). This freedom is not license for arbitrary ordering, though: departing from the
neutral/default order always throws the displaced element into emphatic relief, and word order choices
are frequently governed by the surrounding narrative context, not the sentence in isolation. p.521.

### §476 "New" and "given" information — the master principle governing Russian word order

The single organizing principle behind everything else in this chapter: neutral Russian word order
places GIVEN information (already known, presumed known, previously mentioned, or purely incidental)
first, and NEW information (the actual point of the utterance) last — the reverse of English's more
front-loaded new-information tendency. This has a genuinely elegant real-world test: swapping two
superficially similar sentences' word order changes which question each one answers (На столе́ ва́за
'There's a vase on the table' answers "what's on the table?"; Ва́за на столе́ 'The vase is on the table'
answers "where's the vase?" — same words, same case-marking, opposite information structure). In
connected narrative, each sentence's new information routinely becomes the NEXT sentence's given
information, driving a chain of default topic-shifts across a paragraph — the source's own worked
three-sentence example (a town on a river bank, sailing steamers) demonstrates this chaining explicitly.
This given→new engine is, in effect, a discourse-level grammaticalization of "what's the point" — a
genuinely powerful design idea for structuring an invented language's default constituent order around
information status rather than syntactic role. pp.521-524.

### §477 Relative position of subject and verb

Subject-before-verb order signals the subject is given information (Оте́ц у́мер 'Father has died' — we
already knew who "father" is; the new information is that he died). Verb-before-subject order instead
signals the SUBJECT is the new information, and recurs systematically across a specific, well-defined
set of construction types: impersonal/weather statements, verbs of existence/coming-into-being/
beginning/ending, verbs of occurrence/state/process, direct-speech-quotation framing verbs, and
interrogative-word questions. The interrogative-word + subject + predicate order is grammatically
COMPULSORY with a pronoun subject but merely optional with a noun subject — a fine distinction on
exactly which subject types force strict ordering. Yes/no questions with no interrogative word either
keep declarative order (relying purely on intonation) or insert ли directly after the "operative"
element under question — the same ли-particle behavior already documented in the Particle chapter
(§472(5)), now shown governing an entire clause-level word-order choice, not just a single word's
placement. pp.524-525.

### §478 Subject, verb, object order

Plain S-V-O is default for the vast majority of three-argument sentences. A pronoun object can appear
either before or after the verb. S-O-V order (object before verb) places unusual emphasis on the verb or
object itself, and is predominantly a spoken-register phenomenon. Critically, **S-V-O order becomes
grammatically MANDATORY, not just neutral, whenever the subject and object nouns are morphologically
ambiguous** — i.e., whenever their accusative form is identical to their nominative form (as with many
feminine и-stem or masculine animate nouns in certain declension classes) — because in that case word
order becomes the ONLY available disambiguator of who is doing what to whom, and reversing it genuinely
reverses the meaning (Мать лю́бит дочь 'the mother loves the daughter' vs. Дочь лю́бит мать 'the daughter
loves the mother' — case-marking gives no help here at all, so Russian falls back on a strict
English-style S-V-O convention exactly in the cases where its usual case-marking safety net is absent).
This is a genuinely important typological point: Russian's famous word-order freedom is conditional on
its case system actually doing disambiguating work, and snaps back to rigid ordering the moment that
work isn't available — directly relevant to any invented-language design balancing a case system against
word-order freedom. Object-verb-subject order (Кни́гу купи́л Пётр) foregrounds the subject as the answer
to an implicit "who did it?" and corresponds to an English passive or cleft ("it was Peter who...");
this order is also default with inanimate subjects of a "something happened to me" construction (Меня́
разбуди́ла гроза́ 'I was awakened by a thunderstorm'), with certain qualified-noun set phrases (Больш́ое
значе́ние име́ет уче́бный проце́сс 'the teaching process is of great significance'), and with impersonal
3rd-plural constructions. pp.525-527.

### §479-481 Position of adjectives, adverbs, and multiple adverbial phrases

A long (attributive) adjective normally precedes its noun (exceptions: menu/stock-list registers, generic
descriptions, and predicative use, where it follows) — circumstantial detail can be inserted between the
adjective and noun (mirroring the same insertion pattern already documented for long-form participles at
§361(2)(iii)), and an appositive adjective can follow the noun, comma-separated. A short (predicative)
adjective normally follows its noun as the sentence's actual predicate. Adverbs generally precede the verb
they modify UNLESS they themselves carry the sentence's new information, in which case they move to
final position — the same given/new engine from §476 governing adverb placement specifically. When a
sentence contains multiple adverbs/adverbial phrases of different types simultaneously, a fixed relative
sequence applies: time-adverbials first, then place-adverbials, then manner/cause/other-type adverbials
last — a genuinely useful, concretely orderable rule (unlike many "it depends on emphasis" guidelines
elsewhere in this chapter) directly reusable as a default multi-adverbial ordering convention for an
invented language. pp.527-530.

### §482-483 Position of nouns/pronouns in impersonal constructions; particle position

The accusative/dative experiencer in an impersonal construction (already documented in the Aspect and
Impersonal-Constructions sections of this file, §295 etc.) occupies initial position as given
information, with the new information (the state/quality itself) in final position — the same
нра́виться/ну́жен-type constructions already covered lexically now confirmed to follow the identical
given→new ordering principle. Reversing this order throws the experiencer into contrastive relief
(Фильм понра́вился взро́слым(, но не де́тям) 'the ADULTS liked the film (but not the children)').
Particle position was already fully treated at §469, cross-referenced rather than repeated. pp.530-531.

### §484 Word order in "expressive" (emotionally charged, spoken-register) styles

A systematic catalog of word-order INVERSIONS relative to every neutral-order rule established earlier
in this chapter, each one marking heightened emotional/expressive register rather than a change in
literal meaning: short predicative adjectives (and short-form participles) can precede their noun instead
of following it (Лёгок вопро́с... 'simple [is] the question...' — an almost poetic-sounding inversion);
attributive adjectives can follow their noun instead of preceding it (жара́... стоя́ла невероя́тная 'the
heat... was unbelievable' — the adjective held back for dramatic emphasis); a verb can be inserted
between an attributive adjective and its noun (Уда́чная была́ охо́та! 'that was a successful hunt!');
verb+subject order can invert to put new information first instead of last, reversing §476's whole
governing principle for deliberate emphasis (У меня́ голова́ боли́т, foregrounding "MY head" rather than
the mundane fact of a headache); adverb order can likewise invert (Хо́лодно сего́дня 'cold, today [is]');
and a personal pronoun can follow its predicate instead of preceding it, with an accompanying emphasis
shift (То́лько поёте вы её пло́хо 'except that YOU sing it badly'). The unifying pattern across every one
of these devices: expressive/emotional register in Russian is marked structurally, via a systematic,
rule-governed INVERSION of whatever the neutral-register word-order rule would otherwise produce — not
via new vocabulary, new morphology, or discourse particles, but purely via reordering already-existing
material. This is arguably the single most important structural finding in this file's entire back half
for the eventual mechanics-analysis and slang-synthesis phases: an entire register distinction (neutral
vs. emotionally-charged/colloquial) implemented as a productive, general SYNTACTIC TRANSFORMATION (invert
the default linear order) rather than as a lexical or morphological difference. Any invented slang
register wanting a "marked/heightened" register distinct from its "neutral" register could adopt exactly
this mechanism: define the neutral word-order rules, then define the marked register as their systematic
inversion. pp.531-532.

---

## Back matter (PDF pages ~568-632) — excluded, out of scope

Checked and confirmed to contain no extractable target-language grammar/vocabulary content: Glossary of
grammatical terminology (English metalanguage, not Russian lexical items), Bibliography, Subject Index,
and Word Index. These are navigational/reference apparatus for the book itself, not source content per
the coverage rule.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes, dialogue
blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`.


