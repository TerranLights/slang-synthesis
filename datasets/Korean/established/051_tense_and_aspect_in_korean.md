# Korean — Established Grammar: Sung-Ock S. Sohn, *Tense and Aspect in Korean* (1995)

**Source:** Sung-Ock S. Sohn, *Tense and Aspect in Korean*, Center for Korean Studies Monograph No.
18 (University of Hawai'i Press, 1995). Full book, printed pp. 1–181 (front matter and literature
review in Ch.1 §§1.1–1.2 skipped as pure historiography — see coverage note). PDF page offset:
printed page N = PDF page N + 11, confirmed empirically and holding across the entire book.

**Vision-reading note:** this PDF has no usable text layer at all (pure scanned CCITT bitmap images,
zero embedded fonts). All content vision-read from rendered page images across six parallel passes.
No decoding/cipher issue: the book cites every Korean example in italicized Yale romanization (plain
Latin script), never Hangul, so the scan is ordinary legible printed text throughout. No handwritten
marginalia found anywhere in the book — nothing excluded on vision-reading-guard grounds. Vision
Reading Confidence is `verified` for all entries below unless noted otherwise.

**What kind of source this is.** Unlike this project's existing ~46 Korean files (pedagogical
textbooks), this is a formal linguistics dissertation/monograph. It is vocabulary-sparse (no
graded lesson vocabulary) but extremely grammar-dense — a single integrated theoretical account of
the entire Korean tense/aspect/mood/modality system, built on a Government-and-Binding-style
"tense as a referring expression" analysis (overt **-ess** patterns like a name/R-expression subject
to Binding Principle C; null **-Ø** patterns like the empty pronoun *pro*, able to be anaphorically
bound or read deictically). This central mechanism, stated in Chapter 1, is then applied uniformly
across the rest of the book: Ch.2 lays out the descriptive inventory (tense/aspect/mood/modality
forms, conjunctive suffixes, temporal adverbials, lexical aspect); Ch.3 formalizes the binding
mechanism; Ch.4 applies it to conjunctive (biclausal) sentences; Ch.5 applies it to nonconjunctive
embedded clauses (relative, noun-complement, verbal-complement, quotative, nominalized); Ch.6
summarizes and flags open problems. Formal syntactic apparatus (X-bar trees, binding-principle
proofs) is described in plain language below rather than reproduced — not useful for this project's
goal, which needs descriptive grammar facts for conlang slang-synthesis, not generative-syntax
formalism.

**Novelty relative to this project's existing Korean corpus.** Essentially the entire theoretical
apparatus here is new: no existing established/ file analyzes Korean tense morphology as a binding-
theoretic name/pronominal split, none systematically classifies conjunctive suffixes by a
[±temporal]/[±anaphoric]/[±perfective] feature system, and — confirmed via grep across the whole
corpus (only one incidental hit) — **none covers lexical aspect/aktionsart verb classification at
all**, making Ch.2 §2.6 probably the single most novel section in this entire file. The explicit,
evidenced argument that **Korean has no future tense** (the "future" suffixes -keyss and -(u)l(i),
and the "future" adnominal -(u)l, are all purely modal/predictive, not tense) is likewise a specific
theoretical claim not found in any teaching grammar already extracted for this project.

**Coverage note.** §§1.1–1.2 (pure literature review of prior approaches — Choi 1965, Nahm 1978,
Suh 1976, generative-semantics debates) are skipped as purely historiographic, with no extractable
grammar facts beyond what's already summarized in §§1.3–1.4. All formal rule-feature notation,
X-bar trees, and step-by-step binding-principle derivations are described in plain language rather
than reproduced in their original formal notation.

---

## Vocabulary / Morpheme Inventory

This is a grammar monograph, not a lesson-vocabulary source — the "vocabulary" worth tracking here
is the inventory of named tense/aspect/mood/modal/conjunctive suffixes and a handful of semantically
load-bearing lexical items (defective nouns, auxiliary verbs, diagnostic adverbials) the author uses
as evidence. Usage Tier is `core` throughout (these are all grammatical-core morphemes, not slang or
marked-register vocabulary); Attested Era is `contemporary (source published 1995)`; Attested
Region/Geographic Scope are `—`/`South Korea` (standard Korean, no dialectal variants marked except
where the book itself flags Kyengsang dialect, noted below); Source Type is `academic_paper`;
Transcription Confidence is `n/a` (not a subtitle/transcript source); Vision Reading Confidence is
`verified` throughout.

| Term | Gloss | Part of Speech | Notes |
|---|---|---|---|
| -ess (-ass, -ss) | past tense AND perfective aspect (dual function) | verbal suffix | Behaves like a binding-theory R-expression (fixed reference); allomorphs -ass after a/o-stem syllables, -ss after ha(y)- 'do'; categorically banned in [+temporal] conjunctive clauses and in verbal-complement clauses |
| -Ø (null) | nonpast tense; in embedded clauses also covers past via anaphoric binding | verbal suffix (zero) | Behaves like pronominal *pro*: deictic (free, defaults nonpast) or anaphoric (bound to a matrix/antecedent tense) |
| -ess-ess | pluperfect (past perfective): first -ess = perfective aspect, second -ess = past-tense reference time | verbal suffix (reduplicated) | Invariably past, never perfective, in its second occurrence; banned with future/present-time adverbs; occurs freely and productively in quotative clauses (rare/marginal everywhere else) |
| -te / -ti | retrospective mood suffix: marks the speaker's/hearer's past PERCEIVING of an event, not tense of the event itself | verbal suffix (mood) | Requires an obligatory "reporter" (perceiver) argument; compatible with future-time adverbs, proving its "pastness" ≠ ordinary past tense; embedded and matrix uses are the same morpheme |
| -keyss | modal: speaker's (statement)/hearer's (question) volition, evidential inference, or circumstantial presumption | verbal suffix (modal) | NOT future tense — freely cooccurs with past -ess with no futurity sense, refuting the traditional "future tense" label |
| -(u)l(i) | modal: speaker's/hearer's prediction | verbal suffix (modal) | NOT future tense/prospective aspect — same refutation as -keyss |
| -(u)n | adnominal/relativizer complementizer; analyzed as underlying -ESS-Ø-N; dual past+perfective reading, genuinely 3-way ambiguous in context | verbal suffix (adnominal) | Conventionally called "past" adnominal; archaic/dialectal (Kyengsang) fuller surface form -ess-nun confirms the analysis; also forced by defective nouns *ci*/*tey* |
| -nun | adnominal/relativizer complementizer; indicative suffix + complementizer, no inherent tense | verbal suffix (adnominal) | Conventionally "present" adnominal; purely aspectual/habitual in effect, not a tense category |
| -(u)l | adnominal/relativizer complementizer; predictive/prospective MODAL + nonpast -Ø | verbal suffix (adnominal) | Conventionally "future" adnominal — explicitly argued to be no such thing (can combine with -ess for past-oriented readings) |
| -ko[1] | 'and then' — sequential, subordinating | conjunctive suffix | [+temporal]; bans overt -ess in its own clause; freely substitutable with -kose with meaning preserved; subordinate S-structure (fails Coordinate Structure Constraint tests) |
| -ko[2] | 'and' — coordinating | conjunctive suffix | [-temporal]; homophonous pair with -ko[1]; freely allows overt -ess with no meaning change; true coordinate (CP-conjoined) S-structure |
| -ese | 'and then, and so, as' | conjunctive suffix | [+temporal] anterior, +perfective, +anaphoric-only; bans overt -ess |
| -kose | 'and then' | conjunctive suffix | [+temporal] anterior, +perfective, +anaphoric-only; bans overt -ess |
| -umyense[1] | 'while (doing)' | conjunctive suffix | [+temporal] overlapping, −perfective, +anaphoric-only; equi-subject constraint; bans overt -ess and any perfective marker |
| -umyense[2] | 'although' | conjunctive suffix | [-temporal]; homophonous pair with -umyense[1]; ±anaphoric |
| -ulyeko | 'in order to' | conjunctive suffix | [+temporal] posterior, −perfective, genuinely ±anaphoric (true grammatical ambiguity, not vagueness) |
| -tolok | 'so that, to the extent that, in order that' | conjunctive suffix | [+temporal] posterior, ±anaphoric |
| -taka | 'while, and then' (transferentive) | conjunctive suffix | [+temporal] anterior but exceptionally −perfective-marked-optionally: the ONE anterior suffix that allows overt -ess in its own first clause (argued to be perfective ASPECT, not tense, there — compatible with future adverbs); carries an equi-subject constraint; four rival characterizations in the literature (interruptive/transferentive/durative/contiguity) |
| -nulako | 'while doing' | conjunctive suffix | [+temporal] overlapping, −perfective, +anaphoric |
| -ca | 'as soon as' | conjunctive suffix | [+temporal]-like; bans first-clause -ess (Condition C) |
| -camaca | 'as soon as' | conjunctive suffix | [+temporal] anterior, non-gapped/consecutive subtype (only one time adverbial allowed, events immediately consecutive) |
| -teni | 'after' | conjunctive suffix | [+temporal] anterior, gapped subtype (two separate adverbials allowed, temporal distance between events permitted) |
| -ule | 'to, for the purpose of' | conjunctive suffix | [+temporal] posterior |
| -koca | 'intending to' | conjunctive suffix | [+temporal] posterior; also classed as a verbal complementizer (Ch.5) allowing both anaphoric+deictic null tense |
| -key(kkum) | 'so that' | conjunctive suffix | [+temporal] posterior (Ch.4); also a verbal complementizer/causative-resultative (Ch.5), future-oriented, allows both anaphoric+deictic readings |
| -ulako | 'so that' | conjunctive suffix | result-type, Kwon's traditional semantic classification |
| -una | 'but' | conjunctive suffix | [-temporal], deictic-only; freely allows overt -ess |
| -ciman | 'but, however' | conjunctive suffix | [-temporal], deictic-only; freely allows overt -ess |
| -kenman | 'even though' | conjunctive suffix | [-temporal]; freely allows overt -ess |
| -nikka / -unikka | 'because, since, so' | conjunctive suffix | [-temporal], ±anaphoric; imposes no inherent temporal ordering, but when -ess appears in its first clause it starts behaving as anterior-ordered — because that -ess is perfective aspect, not tense, there (parallel to -taka) |
| -kena | 'or (else)' | conjunctive suffix | [-temporal], deictic-only |
| -eto | 'although, even if' | conjunctive suffix | [-temporal], deictic-only |
| -umye | 'and' | conjunctive suffix | Kwon's traditional coordinating/connection class |
| -keniwa | 'as well as' | conjunctive suffix | Kwon's traditional coordinating/connection class |
| -uni | 'since, as' | conjunctive suffix | Kwon's traditional cause-effect class |
| -nulako (cause sense) / -uto | 'but, although' | conjunctive suffix | Kwon's traditional contrast class |
| -umyen | 'if, when' | conjunctive suffix | Kwon's traditional condition class; exceptionally allows overt -ess (cross-ref Ch.5 verbal-complement exceptions) |
| -ketun | 'if, provided that' | conjunctive suffix | Kwon's traditional condition class |
| -eya | 'if only, on the condition that' | conjunctive suffix | Kwon's traditional condition class; exceptionally allows overt -ess, denoting obligation/counterfactual perfective rather than ordinary past (cross-ref Ch.5) |
| -untul | 'even if' | conjunctive suffix | Kwon's traditional condition class |
| -tasiphi | 'as, in the same way that' | conjunctive suffix | Kwon's traditional evaluation class |
| -kentay | 'judging from' | conjunctive suffix | Kwon's traditional evaluation class |
| -tus(i) | 'as if, in the same way' | conjunctive suffix | Kwon's traditional addition class |
| -ulswulok | 'the more... the more' | conjunctive suffix | Kwon's traditional addition class |
| -man(un) | 'but' | conjunctive particle (not a suffix) | Uniquely permits a full sentence-type ender inside its own "embedded" clause, unlike every true conjunctive suffix |
| -n tey | 'in the circumstance that, and, but, although' | clausal connective (adnominal -n + defective noun *tey*) | [-temporal], ±anaphoric but behaves like coordinate -ko[2]: first clause always deictic even with -ess present, hosts the coordinate-only sentence-ender -yo |
| -ki cen-ey | 'before' | clausal temporal connective | Posterior to matrix time; categorically bans overt -ess, even though the same -ki nominalizer in a nontemporal construction (e.g. -ki ttaymwun-ey 'because') freely allows it |
| -ki-ey aphse | 'preceding the time when, before' | clausal temporal connective | |
| -n twi-ey / -n hwu-ey | 'after' | clausal temporal connective | Anterior to matrix time; entails the matrix event actually occurred (unlike 'before' clauses) |
| -n taum-ey | 'following the time when, after' | clausal temporal connective | |
| -ul cek-ey | 'at the time when' | clausal temporal connective | Simultaneous with matrix time |
| -ul ttay-ey | 'when' | clausal temporal connective | |
| -ul mwulyep-ey | 'around the time when' | clausal temporal connective | |
| -ki wihaye | 'for the purpose of' | clausal temporal connective | [+temporal] posterior |
| -n cuksi | 'at the moment when' | clausal temporal connective | [+temporal] anterior, non-gapped/consecutive subtype |
| -e / -a | infinitive verbal complementizer (vowel-harmony pair) | verbal complementizer | Overt -ess categorically banned in the complement clause |
| -ko (desiderative, e.g. -ko siphta 'wish to') | gerundive/desiderative verbal complementizer | verbal complementizer | Future-oriented; allows both anaphoric and deictic null-tense readings (an exception among verbal complements) |
| -key (resultative/causative) | 'so that' | verbal complementizer | Future-oriented; allows both anaphoric and deictic null-tense readings |
| -ci | suspective verbal complementizer | verbal complementizer | Overt -ess banned |
| -umyen (verbal-complement use) | 'if' | verbal complementizer | Exceptionally allows overt -ess |
| -eya (verbal-complement use) | 'if only' | verbal complementizer | Exceptionally allows overt -ess, denoting obligation/counterfactual perfective |
| ko | indirect quotative particle, 'that' | particle | Freely allows both overt past -ess and overt perfective -ess, including the normally-marginal -ess-ess |
| hako / lako | direct quotative particles, 'saying that' | particle | Syntactically ordinary (treated like an unquoted sentence) |
| -ki | nominalizer | nominalizing suffix | Associated with NONFACTIVITY (wishes, intentions, abilities not presupposed true); allows the -ess system to operate normally inside it |
| -um | nominalizer | nominalizing suffix | Associated with FACTIVITY (presupposed true); allows the -ess system to operate normally inside it |
| -ki sicakha- | inchoative lexical aspect ('start to V') | auxiliary-verb construction | Complementizer -ki |
| -e iss- | perfective lexical aspect (resultant state) | auxiliary-verb construction | Complementizer -e (infinitive) + existential verb iss- 'to exist/be'; restricted to a limited set of intransitive verbs; emphasizes the final/resulting stage of a situation, contrasting with suffixal -ess's "totality" emphasis |
| -e tay- | iterative lexical aspect | auxiliary-verb construction | Complementizer -e |
| -hay tay- | iterative lexical aspect (alternate citation form) | auxiliary-verb construction | Possible terminological overlap with -e tay- — flagged for cross-check, not resolved in-source |
| -ko iss- | progressive lexical aspect (also stative/resultant-state reading) | auxiliary-verb construction | Complementizer -ko; diverges from English be+-ing: occurs with stative verbs, occurs in imperatives, genuinely ambiguous between progressive and resultant-state readings for many action verbs |
| -kon ha- | habitual lexical aspect | auxiliary-verb construction | |
| ci | 'whether' | defective noun | Forces the fuller -ess-nun surface form in noun-complement clauses |
| tey | 'circumstance/place' | defective noun | Also forces fuller -ess-nun form; base of the connective -n tey |
| kes | 'fact, thing' | defective noun | Heads noun-complement clauses (e.g. ... -ESS-Ø-N kes), contrasting structurally with -um-nominalized headless clauses of equivalent meaning |
| twi / hwu | 'after' | head noun | As a noun-complement head, allows ONLY the -(u)n (-ESS-N) complementizer, since 'after' semantically requires the embedded event to precede the matrix event |
| caki | 'self' (reflexive) | pronoun | Diagnostic for unambiguous indirect quotation (vs. 1st-person na 'I', which permits a direct-quotation reading) |
| cikum / icey | 'now' | temporal adverb | Point-of-time; forces present reading of nonpast -Ø |
| onul | 'today' | temporal adverb | Point-of-time |
| nayil | 'tomorrow' | temporal adverb | Point-of-time; forces future reading of nonpast -Ø; banned with the pluperfect -ess-ess |
| ecey | 'yesterday' | temporal adverb | Point-of-time; strictly incompatible with nonpast forms; the classic past-adverb diagnostic throughout the book |
| hangsang | 'always' | temporal adverb | Duration; forces generic reading of nonpast -Ø; unrestricted across anterior/simultaneous/posterior and past/nonpast |
| mak | 'just' | temporal adverb | Relative time; unrestricted across anterior/simultaneous/posterior and past/nonpast/nonpast-perfective — the least restricted adverbial in Sohn's cooccurrence table |
| pelsse | 'already' | temporal adverb | Relative time; compatible with past, nonpast, and nonpast-perfective but not posterior-only time |
| pangkum | 'just now' | temporal adverb | Relative time; compatible with past and nonpast-perfective but not simultaneous/posterior or plain nonpast |
| alta, mitta, kkaytatta | 'know', 'believe', 'recognize' | stative verbs | Cited as freely taking -ko iss- in Korean, unlike the equivalent English stative-verb progressive restriction |
| ip-, sin-, tul- | 'wear [clothes]', 'wear [shoes]', 'carry' | resultative action verbs | Illustrate -ko iss- progressive/resultant-state ambiguity, contrasting with plain action verbs like ilk- 'read' (unambiguously progressive under -ko iss-) |

---

## Grammar points

### Chapter 1 — Theoretical foundations

#### Reichenbach's tense system, as a starting point (§1.3, pp.8–11)
Reichenbach (1947) analyzes tense via three primitives: speech time (S), event time (E), and
reference time (R), with English tenses as positional configurations of the three (e.g. past
perfect = E-R-S; simple past = E,R-S; present = S,R,E; future = S-R-E). R functions as an
independent "point of view" distinct from both S and E, useful for adverbial-anchored readings
("At sunrise Mabel had had breakfast" places R at sunrise, E before it). Sohn adopts this as a
starting framework but substantially modifies it for Korean (below).

#### Sohn's own model: tense as a relation, not a label for event time (§1.4.1, pp.12–15)
The book's central definitional move: **tense is a grammatical category naming a relation between
event time and speech time** — not a label referring directly to the event time itself. Past tense
= event precedes speech time; nonpast = event follows or is simultaneous with speech time. This
breaks from the more common view (Hornstein, Soga, Comrie) under which tense categories name event
times standing in some relation to speech time (which would allow indefinitely many tense values).
On Sohn's view Korean has exactly **two** formal tense values — past and nonpast (nonpast subsuming
both present and future) — with the actual event time filled in pragmatically/lexically (context,
adverbs like *ecey* 'yesterday'), never grammatically. The two realizing forms are **-ess** (always
names "the past relation," argued to behave like a name/R-expression under Binding Theory: fixed,
inherent reference) and **-Ø** (a pronominal: variable reference, bindable by an antecedent or
interpretable deictically/freely — direct parallel to overt vs. covert pronoun construal). This
name/pronominal split is the dissertation's central theoretical claim, argued via Government &
Binding-style parallels not found in any teaching-grammar source in this project's Korean corpus.

#### The name/pronominal distinction predicts grammaticality (pp.13–17)
Worked minimal pairs: *John-un cip-ey ka-Ø-se, Mary-lul manna-ss-ta* 'John went home and then met
Mary' (embedded clause null-marked) is grammatical, but the same sentence with overt -ess in the
embedded clause before -ese 'and then' is ungrammatical; the same pattern holds for -(u)myense
'while'. Sohn's account: -ess is barred because an R-expression cannot be bound by a c-commanding
antecedent (parallel to a proper name being unable to corefer with a c-commanding NP), whereas -Ø
(pronominal) can be freely bound by the matrix tense. This is a principled syntactic constraint, not
a descriptive gap-filling rule, and explains *why* certain conjunctive suffixes categorically
exclude overt -ess in their first conjunct. Relative clauses behave differently: their null tense is
genuinely ambiguous between a deictic and an anaphoric reading (e.g. 'the book that John is/was
reading, Mary read' is ambiguous between 'is reading' and 'was reading'), whereas conjunctive
clauses with suffixes like -ese/-umyense allow ONLY the anaphoric (bound) reading, never deictic —
a systematic asymmetry developed in full in Chapters 3–5.

#### Typological characteristics of Korean relevant to tense/aspect (§1.5.1, pp.17–18)
SOV language with relatively free nominal order but a clause-final verb (matrix or embedded); all
modifying elements (adjectival, adverbial, conjunctive, quotative) precede what they modify
(left-branching/head-final); agglutinative, with grammatical categories (subject honorific, aspect,
tense, modal, addressee honorific, mood, clause-type) attaching to the verb stem as an ordered
sequence of inflectional suffixes; a "discourse-oriented language" (citing Sohn 1994) where topic is
as important a notion as subject and any major constituent can be freely omitted if recoverable from
context. Five embedded-clause types exist in Korean complex sentences: conjunctive (coordinate +
subordinate), adnominal (relative + noun-complement), verbal complement, quotative, and nominal/
nominalized clauses — this taxonomy maps directly onto Chapters 3–5.

#### Korean verbal inflectional template (p.24)
```
VERB → STEM + INFLECTIONAL CATEGORIES
INFL. CAT. → (SUBJECT HONOR) + (ASPECT) + TENSE + (MODAL) + (ADDRESSEE HONOR) + MOOD + CLAUSE-ENDER
CLAUSE-ENDER → COMPLEMENTIZER | S-TYPE
COMPLEMENTIZER → Conjunctive (-ese, etc.) | Adverbial (-key, -e, etc.) | Adnominal (-n, etc.) | Nominal (-ki, -um)
ASPECT → Perfective (-ess)
TENSE → Past (-ess, -Ø) | Nonpast (-Ø)
MODAL → Volitive (-keyss) | Presumptive (-keyss) | Predictive (-(u)l(i))
MOOD → Indicative (-(n)un/-ni) | Retrospective (-te/-ti) | Requestive (-si, -Ø)
```
Parenthesized categories (subject honor, aspect, modal, addressee honor) are optional; tense and
mood are obligatory. A clean, citable formal statement of Korean verbal morphotactics — more
systematic than any informal slot-ordering chart in this project's existing pedagogical Korean
files.

#### No tense agreement in complex sentences (§1.5.2, pp.18–22)
A genuine typological claim: Korean has **total lack of tense agreement** in complex sentences,
contrasted explicitly with English (embedded tense morphologically backshifts to match matrix tense:
"I believed that the sun *was* out," even for an ongoing truth) and even with Japanese (Kuno 1978:
Japanese allows *some* divergence between embedded and matrix tense, but not totally freely). Sohn
argues Korean goes further — there is no construction where tense agreement holds at all. Worked
contrastive pairs: *John-un [pro chayk-ul ssu-ko iss-Ø-ta]-ko malhay-ss-ta* 'John said that he
was/is writing a book' (embedded null tense, ambiguous, no agreement with matrix past) versus
*...iss-ess-ta-ko malhay-ss-ta* 'John said that he had been writing a book' (the embedded -ess here
is NOT tense agreement — it independently asserts that the book-writing was complete before the
saying-event). A specific sub-rule: certain temporal conjunctive suffixes (-ese 'and then',
-umyense 'while') categorically forbid any overt tense marker in the first conjunct — the temporal
relation between clause-events is carried entirely by the suffix's own lexical semantics, with only
the clause-final (matrix) verb carrying overt tense. Sohn's explanation ties this to Korean's
SOV word order and discourse-orientedness: non-final clauses are syntactically/semantically unable
to carry an independent temporal interpretation without the matrix clause — the matrix tense is
*obligatorily* the reference time for a dependent null tense. This justifies treating the matrix-
clause event time as literally equivalent to Reichenbach's reference time (R = the matrix-clause
event, throughout the study) — Sohn's deliberate simplification of Reichenbach's independent R
notion for complex sentences.

---

### Chapter 2 — Temporal categories: the descriptive inventory

#### -ess: past tense AND perfective aspect, a dual function (§2.2.1, pp.26–29)
Prior scholarship splits three ways: -ess is purely perfective aspect with no tense category (Na
1971, Huh 1987, Nahm 1978); -ess is purely past tense, not perfective (most traditional grammarians,
e.g. Choi 1965); or -ess is a single fused "tense-aspect" category (Suh 1976 claims 17 distinct
meanings). Sohn's position: -ess has two genuinely separate functions that happen to share one
surface form — it is the sole exponent of an optional PERFECTIVE ASPECT category, and separately (or
simultaneously) the overt exponent of PAST TENSE. Evidence: past-time adverbials (*ecey*
'yesterday', *opwun cen-ey* 'five minutes ago') are compatible only with -ess-marked predicates,
never the null form, while *cikum* 'now' forces the null/nonpast form — showing -ess names a past
relation. Separately, -ess contrasts an uncompleted vs. completed reading independent of past/
nonpast (*Kkoch-i [e phi-taka] ci-ess-ta* 'the flowers died while blooming' [uncompleted blooming]
vs. *Kkoch-i [e phi-ess-taka] ci-ess-ta* 'the flowers bloomed and died' [completed blooming] — same
past time reference, but perfective vs. non-perfective within the embedded clause). -ess also
cooccurs with present-time adverbials for a present-perfect-like reading (*Icey cip-ey ta
wa-ss-ta* 'we are almost home now'), and even with future-time adverbials in limited constructions
(*naynyen-ey...ka-ss-ul ttay* 'next year when I will have gone') — impossible if -ess were purely
past tense. Ambiguity between the past and perfective readings is disambiguated by whichever
temporal adverbial is present.

#### -ess-ess: pluperfect, not a separate "discontinuous" morpheme (§2.2.2, pp.30–38)
Three prior definitions: a distinct "ceasing/discontinuous" aspect marker unrelated to -ess (Nahm
1978, C. Lee 1985); "past-in-the-past" (Martin 1954); "past perfective" (Choi 1965, Na 1971).
Sohn's synthesis: -ess-ess is genuinely PLUPERFECT, uniting the latter two — the first -ess marks
perfective aspect, the second sets a past reference time that "insulates" the event from current
relevance. Aspect-before-tense ordering is cross-linguistically supported (children acquire aspect
before tense; in Ancient Greek, aspect is morphologically more central than tense than periphery-
positioned tense, per Lyons 1977/Matthews 1974), independently predicting first-ess=aspect,
second-ess=tense. The "ceasing/discontinuity" reading (*Ku salam-i cwuk-ess-ess-ta* 'that person had
been dead but may be alive now', vs. plain *cwuk-ess-ta* with no such implicature) is argued to be a
pragmatic consequence of the insulating past reference time, not a separate lexical meaning — so a
third, unrelated morpheme need not be posited. -ess-ess is categorically incompatible with
future-time adverbials (*nayil*, *naynyen*) or the present-time adverb *mak* 'just now' — only
single -ess allows these — because the second -ess invariably marks PAST, never perfective, so
there is no "double perfectivity" category in Korean. -ess-ess and single -ess are mutually
replaceable when both describe a genuinely past event (not a future one). Claimed counterexamples
where -ess-ess looks ungrammatical become fully natural once an explicit past-time adverb like *imi*
'already' is added. With the same time adverb, -ess-ess vs. single -ess can differ purely in
subjective framing: single -ess objectively states the event happened at a given past time;
-ess-ess subjectively frames it as having no current relevance.

#### -Ø (null tense): nonpast by default, inherits past when anaphoric (§2.2.3, pp.37–40)
Sohn argues there is no imperfective aspectual subcategory in Korean at all — lack of -ess always
and only signals non-perfectivity, which is semantically contentless beyond "not perfective." The
real two-way split is in TENSE, not aspect: past (-ess or, when anaphoric, -Ø) vs. nonpast (-Ø
only). The null form's range is broader than -ess's: it covers present, future, and generic/
timeless readings with the identical bare form (*Yeyswul-un kil-Ø-ko, insayng-un ccalp-Ø-ta* 'art is
long, life is short' [generic]; *John-i ceki o-Ø-n-ta* 'there comes John' [present]; *John-i nayil
o-Ø-n-ta* 'John will come tomorrow' [future]). In embedded clauses, -Ø has two distinct functions
— DEICTIC (nonpast reading relative to speech time, free reference) vs. ANAPHORIC (temporal value
copied from an antecedent/reference time elsewhere in the sentence, which can make it read as past
when the antecedent is past, e.g. *John-un [Mary-ka wu-Ø-nun] kes-ul po-ass-ta* 'John saw Mary
crying', where the embedded -Ø is interpreted as past because it's anaphoric to the matrix past
tense). Most conjunctive suffixes and verbal-complement clause-enders permit only -Ø, never overt
-ess — the empirical basis formalized as a categorical binding-theoretic ban in Chapters 3–4. Full
system summary (p.40): 7 sequential inflectional suffix slots, aspect in slot 2 (optional, single
member: perfective -ess), tense in slot 3 (obligatory, two disjunctive members: past/nonpast).
Combinations: past alone = -ess or anaphoric -Ø; nonpast alone = -Ø; pluperfect (past perfective) =
-ess-ess or -ess-Ø; nonpast (present/future) perfective = -ess-Ø.

#### Retrospective mood suffix -te/-ti: an evidential mood, not tense (§2.3.1, pp.41–45)
Sohn classifies -te as MOOD (alongside indicative), not tense or aspect — against analyses calling
it retrospective "tense" (Choi 1965, Na 1971), retrospective "aspect" (Martin 1954), or "manner"
(S. Chang 1973). Three component semantic units (following Sohn 1986): PAST, REPORTER, PERCEIVE.
-te is compatible even with a future-time adverb (*Suni-nun nayil hakkyo-ey ka-Ø-te-la* '(I found
that) Suni is going to school tomorrow') — proof that its "pastness" is not ordinary past tense
(which would clash with a future adverb) but rather pastness of the PERCEIVING event itself,
functioning as an independent reference time distinct from both event time and speech time (a
genuine 3-way Reichenbachian split that ordinary indicative mood collapses to S=R). When -te
cooccurs with overt past -ess, the -ess-marked event necessarily precedes the perceiving time
(pluperfect-like layering: *Suni-nun hakkyo-ey ka-ss-ess-te-la* 'I noticed that Suni had once gone
to school'). When -te cooccurs with bare -Ø, the event may be simultaneous with or after the
perceiving time but never before it — producing genuine structural ambiguity resolved only by
context. -te requires an obligatory "reporter" argument (the perceiver: the speaker in statements,
the addressee in questions), behaving, in the author's words, like "a miniature version of a matrix
clause with the speaker/hearer as the subject," despite being morphologically just a suffix. -te's
apparent progressive/durative flavor in some prior accounts is actually just the absence of -ess
(non-perfectivity), not an inherent property of -te itself. Embedded-clause -te behaves identically
to matrix-clause -te, against claims (Nahm 1978) that they are distinct morphemes.

#### Modal suffixes -keyss and -(u)l(i): purely modal, NOT future tense (§2.3.2, p.46)
The most specific, citable theoretical claim in the book for conlang-synthesis purposes. Most
traditional grammarians (and Martin 1954/1963) treat -keyss as future tense and -(u)l(i) as a
prospective aspect. Sohn explicitly rejects both labels (citing Sohn 1986): -keyss denotes the
speaker's (statement) or hearer's (question) volition, evidential inference, or circumstantial
conjecture/presumption; -(u)l(i) denotes the speaker's/hearer's prediction. The apparent "futurity"
of both is an illusion created by their cooccurrence with the independently nonpast-leaning null
tense -Ø, not an inherent feature of the modal suffixes themselves. Decisive evidence: both freely
cooccur with the PAST-tense suffix -ess with no futurity sense whatsoever (*Ecey Seoul-ey pi-ka
manhi wa-ss-keyss-ta* '(I presume that) it rained a lot in Seoul yesterday' — a past-time
presumption; *Ku i-nun cwuk-ess-ul salam i-ta* 'that person is a person who was presumed dead' —
-ess + -ul with clearly past reference). If -keyss/-ul(i) were future markers, cooccurrence with
explicit past time and -ess would be contradictory; instead it is fully grammatical.

#### Conjunctive suffixes: a temporality-based typology replacing the traditional semantic one (§2.4, pp.46–50)
Sohn rejects the traditional coordinating/subordinating semantic classification (Kwon 1985's 8-way
split: connection, contrast, cause-effect, condition, purpose, evaluation, result, addition — the
full list is in the Vocabulary table above) as syntactically unsupported — the same suffix form
(e.g. -ko) is used for both coordinate- and subordinate-like clauses, the key counterexample.
Instead she proposes a **temporality-based** classification with real syntactic consequences:
**[+temporal]** suffixes (-ese, -ko[1], -kose, -ulyeko, -tolok, -taka, -umyense[1], etc.) encode a
sequential or overlapping time-relationship between the embedded and matrix event times;
**[-temporal]** suffixes (-ko[2], -ciman, -una, -kenman, -nikka, -umyense[2], etc.) carry no such
constraint. Suffixes with both a [+temporal] and [-temporal] sense (like -ko and -umyense) are
treated as **homophonous pairs** with genuinely different meanings, not one polysemous item. The key
syntactic diagnostic: [+temporal] suffixes categorically forbid overt -ess in their clause — even
when the embedded event is interpreted as past, only -Ø is allowed — while [-temporal] suffixes
freely allow overt -ess. This is offered as independent syntactic evidence for a split earlier
scholars had only motivated semantically. The [±temporal] split also maps onto an **anaphoric
(endophoric) vs. deictic (exophoric)** tense-interpretation distinction (citing D. Yang 1977):
[+temporal] suffixes force an anaphoric reading of the embedded null tense; [-temporal] suffixes
allow a deictic reading. With -ko specifically: the sequential 'and then' sense ([+temporal], -ko[1])
only allows -Ø in its embedded clause; the coordinating 'and' sense ([-temporal], -ko[2]) allows
both -Ø and -ess with no change of meaning — and [+temporal] -ko is proposed to be syntactically
**subordinate**, [-temporal] -ko syntactically **coordinate** (full syntactic proof given in Ch.4).

#### Temporal adverbials: types and their disambiguating function (§2.5, pp.50–55)
Two general types: **lexical** (time adverbs/phrases) and **clausal** (temporal connectives: head
noun + particle *-ey*, listed in the Vocabulary table above). Lexical adverbials fall into four of
Sohn's own semantic subclasses: points of time (*cikum/icey* 'now', *onul* 'today', *nayil*
'tomorrow', *ecey* 'yesterday', etc.), duration (*hangsang* 'always', *seysi-kan* 'for three hours',
etc.), relative time (*pelsse* 'already', *acik* 'still/yet', *pangkum* 'just now', etc.), and
repetition/frequency (*nalmata* 'everyday', *cacwu* 'frequently', etc.). A genuinely systematic
contribution not present in any teaching grammar: a **relation-to-speech-time × tense/aspect
cooccurrence table** (ex. 50, p.51) classifying adverbials by whether they are anterior, simultaneous,
or posterior to speech time, and which of past/nonpast/nonpast-perfective they can cooccur with
(pluperfect patterns identically to simple past). Sample findings: *ecey* 'yesterday' is strictly
incompatible with any nonpast form; *mak* 'just' is wholly unrestricted; *onul* 'today' allows past
and nonpast but not nonpast-perfective; *nayil* 'tomorrow' allows nonpast and nonpast-perfective but
not past. Clausal temporal adverbials carry relational values with regard to the *matrix-event time*
rather than speech time — e.g. *-ki cen-ey* 'before' is posterior to matrix time, *-n twi-ey* 'after'
is anterior to it, *-ul cek-ey* 'at the time when' is simultaneous. Sohn identifies three concrete
disambiguation functions for temporal adverbials: (1) disambiguating the readings of unmarked
nonpast -Ø (generic/present/future) on an otherwise-identical verb form; (2) disambiguating simple
past (-ess) from present perfective (-ess-Ø), e.g. *ecey* 'yesterday' forcing simple past vs.
*pangkum* 'just now' forcing present-perfective 'has just left'; (3) disambiguating anaphoric vs.
deictic readings of unmarked null tense in an embedded clause — a bare relative clause with null
tense can be genuinely ambiguous ('child who was working'/'child who is working'), resolved by
inserting *ku ttay* 'at that time' (forces anaphoric/past) or *cikum* 'now' (forces deictic/
present); a parallel case with retrospective -te/-ti is even 3-way ambiguous absent a disambiguating
adverbial. The [+temporal] ban on overt -ess extends to clausal connectives too: *-ki cen-ey*
'before' disallows overt -ess in its clause even though the identical *-ki* nominalizer in a
nontemporal construction (*-ki ttaymwun-ey* 'because') freely allows it — showing it's specifically
the [+temporal] feature, not the -ki morpheme itself, that triggers the ban. *-n hwu-ey* 'after'
(unlike 'before' clauses) entails the matrix clause actually happened, an anterior-vs-posterior
semantic asymmetry even within [+temporal] clausal connectives.

#### Lexical aspect: the most novel section of the book for this project (§2.6, pp.55–59)
Sohn distinguishes **inflectional aspect** (the suffixal -ess, already covered above) from **lexical
aspect**, expressed via aspectual auxiliary-verb constructions, each with its own fixed
complementizer on the preceding main verb: *-ki sicakha-* (inchoative, complementizer -ki); *-e
iss-* (perfective, complementizer -e + existential verb *iss-* 'to exist/be'); *-e tay-* (iterative,
complementizer -e); *-ko iss-* (progressive, complementizer -ko + *iss-*). Her classification:
Perfective = *-e iss-* (lexical) / *-ess* (suffixal); Imperfective = Progressive *-ko iss-*,
Inchoative *-ki sicakha-*, Habitual *-kon ha-*, Iterative *-hay tay-*. **-e iss- vs. -ess are not
equivalent** despite both being able to translate a completed event in English: *-e iss-* emphasizes
the final/resulting stage of a situation (a resultant state), while *-ess* emphasizes the
situation's totality (viewed as a single whole). *-e iss-* is restricted to a limited set of
intransitive verbs (historically claimed by other scholars — Huh 1987, K. Lee 1981, Gim 1980b — to
be the historical source of -ess via contraction); -ess carries no such restriction, and the two are
in near-complementary distribution for many verbs. **-ko iss- (progressive) is NOT a direct analog
of English be+-ing** — three concrete divergences, none likely to appear in a teaching grammar: (1)
Korean freely allows progressive aspect in imperative sentences (marked marginal-but-structurally-
allowed by the author), where English disallows progressive imperatives almost entirely; (2) -ko
iss- occurs freely with stative verbs (*alta* 'know', *mitta* 'believe', *kkaytatta* 'recognize'),
where the equivalent English statives categorically reject the progressive; (3) -ko iss- is itself
genuinely ambiguous between progressive and stative/resultant-state readings with many action verbs
— resultative action verbs like *ip-* 'wear [clothes]', *sin-* 'wear [shoes]', *tul-* 'carry' give
both an "in the process of" and an "in the state of" reading simultaneously under -ko iss-, unlike
plain action verbs (*ilk-* 'read', *cis-* 'build'), which stay unambiguously progressive. -ko iss-
and -e iss- share this "resulting state" sense even though -ko iss- additionally covers true
progressive meaning that -e iss- lacks. Closing methodological note: Sohn flags that aspectual
notions like stativity/progressivity/iteration involve genuine speaker subjectivity (citing Lyons
1977a) — the same objective situation can be construed as a bounded "event" or an ongoing "process"
depending on speaker intent, and Korean is not exceptional in this regard.

---

### Chapter 3 — Tense indexing and binding (formal mechanism)

#### The R-expression/pronominal parallel, made literal (§3.1–3.2, pp.61–66)
-ess is argued to behave exactly like the proper name "John": both keep a fixed, inherent reference
regardless of syntactic position; both are barred from certain coreferential repetitions (banned
from an embedded clause when c-commanded by a coreferential matrix instance); both *can* repeat in
definable contexts (coordinate structures, see Ch.4 below). -Ø is argued to behave exactly like
Korean's empty pronoun *pro*: it can get its value anaphorically from a tautosentential antecedent
(the matrix tense) or deictically/freely from context — a direct parallel to overt vs. covert
pronoun construal.

#### A finer-grained, three-way classification of null-tense readings per suffix (§3.2, p.65)
A different cut than the [±temporal] classification from Chapter 2: suffixes allowing **only** the
anaphoric interpretation of their embedded null tense (-ese, -kose, -umyense, -taka); suffixes
allowing **both** anaphoric and deictic (-tolok); suffixes allowing **only** the deictic
interpretation (-eto 'although', -ciman 'but', -kena 'or'). Default rule for deictic -Ø: "the
deictic interpretation of the null form is nonpast, unless otherwise specified" (p.67) — absent a
constraining suffix/adverbial/context, a free-floating null tense defaults to nonpast.

#### Coindexing is not event-identity (§3.2, pp.67–70)
Two coindexed tense categories are claimed to share only the same [±past] *relation to speech time*
— never the same actual event time, a deliberate break from "the more common/traditional view" that
coindexed tenses imply cooccurring events. Demonstrated with a *-ceney* 'before' example where the
embedded event can be read as happening before OR after speech time even though it's fixed as
temporally prior to the matrix-clause event: *-ceney* forces a relative ordering between the two
clause-events while leaving the absolute placement of that ordering (past vs. future) ambiguous — a
pattern a naive "same event time" analysis could not capture. In multi-embedding, anaphoric null
tense is coindexed right-to-left across a whole chain of conjuncts, each ultimately coindexed with
the single matrix tense.

#### Formal apparatus, substantive (non-tree) claims (§3.3, pp.72–77)
Korean INFL is treated as bundling tense together with aspect, honorifics, and modal marking
(richer than English INFL); the matrix COMP hosts sentence-type enders (declarative -ta, etc.),
while conjunctive suffixes occupy the embedded-clause COMP position. Crucially, null tense is argued
to assign NOMINATIVE CASE to its clause's subject the same way overt tense does — used as
independent evidence that null-tense embedded clauses are genuinely *tensed*, not tenseless
infinitivals, against some earlier analyses. A further named suffix joining the [+temporal],
-ess-banning class: *-ca* 'as soon as'.

#### Deletion vs. base-generation: why base-generation wins (§3.4, pp.78–85)
Two competing analyses of the embedded null tense. **Deletion analysis** (I. Yang 1972, D. Yang
1981): embedded clauses start with a full tense/mood form at deep structure (identical to the
matrix), deleted transformationally whenever coreferential with the matrix. Sohn raises three
objections: it posits elements that never surface, adding needless complexity given Korean's
seven-slot inflectional template; deletion rules still need coindexing to know what's deletable, so
no real economy is gained over the alternative; and, most seriously, it predicts synonymy between a
full-form and null-form variant of the "same" sentence that demonstrably don't mean the same thing
— e.g. V-ess-ko reads two events as independent/unrelated (no cause-effect, no precondition), while
V-Ø-ko is ambiguous between sequential and simultaneous readings AND carries a cause-effect/
precondition relation the -ess-ko form lacks; a meaning-preserving deletion rule cannot produce this
asymmetry. **Base-generation analysis** (the one Sohn adopts): the null tense is base-generated
directly under Tense inside INFL at every level of structure (not derived by deleting a fuller
form); its coreference with an antecedent is established by a semantic/interpretive rule applying at
LF rather than a syntactic deletion transformation. This lets the two sentence types have genuinely
different D-structures from the start, directly capturing their meaning difference. The resolving
generalization: tense coreference means only "same relation to speech time," never "same event
time" — the key move that lets base-generation succeed where deletion fails. A flagged exception:
matrix tense is *always* deictic "except for the -Ø tense before the retrospective mood" (-te) —
noted but not elaborated further in this book's treatment.

---

### Chapter 4 — Temporality in conjunctive sentences (full construction typology)

#### Master classification table (§4.2, p.94)
Conjunctive suffixes cross-classified by [+temporal: anterior/overlapping/posterior] vs.
[-temporal], and by [±perfective]/[±anaphoric]:

| | [+temporal] Anterior | [+temporal] Overlapping | [+temporal] Posterior | [-temporal] |
|---|---|---|---|---|
| **+perfective, +anaphoric** | -ese 'and then/so', -kose 'and then' | — | — | — |
| **−perfective, +anaphoric** | -taka 'while doing' (transferentive) | -umyense[1] 'while', -nulako 'while doing' | — | — |
| **−perfective, ±anaphoric** | — | — | -ulyeko 'in order to', -key 'so that' | -ko 'and', -umyense[2] 'although', -nikka 'because' |
| **−perfective, −anaphoric** | — | — | — | -ciman 'but', -kena 'or else', -eto 'but/even if' |

Posterior suffixes are inherently [±anaphoric] because of their built-in futurity/prospectiveness.
Anterior suffixes split into a "gapped" subtype (two separate time adverbials allowed, temporal
distance between events permitted: -ese, -kose, -teni 'after') versus a "non-gapped/consecutive"
subtype (only one adverbial allowed, events must be immediately consecutive: -camaca 'as soon as',
-n cuksi 'at the moment when'). Perfectivity (§4.2.3, pp.92–93): all nontemporal suffixes and overt
tense itself freely allow a perfective marker; most temporal suffixes don't (it would be redundant
with their built-in ordering semantics) — the single exception is -taka, inherently [-perfective]
and so able to optionally take -ess for an added "completed" reading, which is why perfectivity is
treated as a genuinely distinctive rather than merely implied feature.

#### Anterior constructions (§4.3, pp.94–105)
First-clause event precedes second-clause event. *-kose*/*-ko* with change-of-state verbs is
semantically ambiguous between a plain sequential reading and a "resultative/manner" reading (e.g.
"put on his coat and left" vs. "left wearing his coat"). **Transferentive -taka** is the one
anterior suffix allowing overt -ess in its own first clause. The literature offers four rival
characterizations Sohn surveys and partly reconciles: "interruptive" (one action interrupted/
replaced by another), "transferentive" (a shift in action/direction/recipient), "durative" (focus on
an event's duration), and "contiguity" (Song 1983's proposed unifying core sense, treated as
subsuming the others); Song further distinguishes three senses of -taka itself — interruption,
concurrence, condition. -taka uniquely carries an equi-subject constraint other anterior suffixes
lack. Its embedded -ess is argued to be pure perfective ASPECT rather than tense — evidenced by its
compatibility with future-time adverbs like *nayil* 'tomorrow' — yielding a four-way typology of
aspect/tense combinations across embedded vs. matrix clauses, each producing a distinct reading
(pure anaphoric past; present perfective; nonpast perfective anaphoric; past perfective via a
non-coindexed embedded -ess).

#### Overlapping constructions (§4.4, pp.106–108)
*-umyense[1]* 'while' and *-nulako* 'while doing' both categorically ban -ess and any perfective
marker in the first clause, are always anaphoric, are generally subject to an equi-subject
constraint (rare counterexamples exist), and forbid two distinct time adverbials since the two
events must genuinely overlap.

#### Posterior constructions (§4.5, pp.108–111)
Despite the surface "in order to X, [matrix happened]" word order, the X-event is logically
posterior to (occurs after) the matrix event. Because of this inherent futurity/prospectiveness,
this is the one suffix class that is genuinely [±anaphoric] in a real grammatical-ambiguity sense
(not mere pragmatic vagueness) — demonstrated by forcing each reading unambiguously with conflicting
time adverbials in the same sentence (e.g. "tomorrow ... in order to go to school ... the day before
yesterday, John met Mary" is fully acceptable).

#### Nontemporal constructions (§4.6, pp.111–131)
Deictic clauses (-kena 'or else', -ciman 'but', -una 'but', -eto 'even if') behave like independent/
matrix clauses with no restriction on -ess/perfective, requiring the general indexing principle to
be restated: a deictic tense has *disjoint reference (or no indexing at all)*, not merely "optional"
coindexing. **The -ko clause discussion (§4.6.2)** is the book's most fully worked-out case study:
the well-known two-way ambiguity of -ko ("and," coordinating or sequential) is argued to correspond
to two grammatically distinct suffixes, [-temporal] -ko[2] (coordinating) vs. [+temporal] -ko[1]
(subordinating), via three converging kinds of evidence. (1) **Semantic**: coordinating-reading
("Group A") sentences allow -ess in the first conjunct to be freely included or omitted with no
change in meaning or grammaticality (the two events are conceptually independent, symmetric, order-
swappable with no truth-condition change); subordinating-reading ("Group B") sentences forbid -ess
in the first conjunct (or force reinterpretation into Group A if added), require the first-conjunct
event to precede the second and typically supply its precondition/cause, and change meaning or
become ungrammatical if conjunct order is swapped. (2) **Morphological**: subordinating -ko[1] can
always be freely substituted with the unambiguously [+temporal] -kose 'and then' with meaning
preserved (consistent with -ko being historically/functionally a contracted form of -kose in this
use); coordinating -ko[2] categorically cannot take -kose substitution. This substitutability test
also sorts a third, surface-ambiguous "Group C" class (three simultaneous readings: independent/
sequential/simultaneous) into Group B or Group A as appropriate. (3) **Syntactic**: subordinating
-ko[1] clauses have a genuine subordinate structure; coordinating -ko[2] clauses have a true
coordinate (two CPs conjoined as sisters) structure, tested via Ross's (1967) Coordinate Structure
Constraint — Group A (coordinate) resists extracting an element out of either conjunct and patterns
with true coordination under across-the-board parallel wh-extraction; Group B (subordinate) shows no
such extraction restriction at all. The formal upshot: the two -ko's get different S-structures
(symmetric CP-conjoined vs. subordinate CP-embedded-under-IP), which independently derives the -ess
facts via Binding Principle C — in the subordinate structure the embedded INFL is c-commanded by the
matrix INFL, so a coreferential embedded -ess is bound and ungrammatical; in the coordinate
structure the first conjunct's own IP blocks c-command from the second conjunct's INFL, so a
coreferential -ess in the first conjunct is never bound and remains grammatical even though both
tokens share the same past-relation referent and do get coindexed. A side finding on coordinate
chains: when a tense value is shared across a coordinate chain, the OVERT form surfaces in the LAST
conjunct, not an earlier one — Sohn draws an explicit cross-categorial parallel to how nominative/
accusative case marking and the plural marker *-tul* in Korean NP-coordination show the identical
last-conjunct-surfacing pattern, suggesting a general fact about where "shared" morphology is
realized in Korean coordination, not something specific to tense. Finally, *-unikka* 'because/since'
and the connective *-n tey* are also ambivalently [±anaphoric] like -ko but differ in detail:
*-unikka* imposes no temporal ordering by default even on its anaphoric reading, yet whenever -ess
appears in its first clause it starts behaving as if anterior-ordered — because that -ess is
perfective aspect, not tense, there (directly parallel to -taka), not because -unikka itself has two
temporal statuses. *-n tey*, by contrast, shows no such effect at all: even with -ess present, no
ordering is imposed, and its first clause is always deictic (never anaphoric), patterning like a
coordinate -ko[2] clause — confirmed by its ability to host the coordinate-only sentence-ender *-yo*.

---

### Chapter 5 — Tense in nonconjunctive embedded clauses

#### Organizing claim and cross-cutting generalizations (§5.1, pp.133–134)
Every nonconjunctive embedded-clause type (adnominal/relative, noun-complement, verbal-complement,
quotative, nominalized) follows the same tense machinery developed in Chapters 1–4 without
modification. Four generalizations stated up front: temporal conjunctive suffixes and verbal
complementizers both disallow overt -ess in their clause; null tense is anaphoric-only in anterior/
overlapping conjunctive clauses AND in verbal complements (except future-oriented ones like -key);
both conjunctive clauses and verbal complements allow null-form tense interpreted as either
anaphoric or deictic for a narrow suffix set (-ulyeko, -koca; -ko as in -ko siphta 'wish to', -key
'so that'); nominalized clauses (-ki, -um) are ambiguous anaphoric/deictic, rejecting -ess when
anaphoric and accepting it when deictic (paralleling -umyense 'while/although'); adnominal and
quotative constructions pattern with -ko clauses — both [±anaphoric], allowing both overt past and
perfective.

#### Adnominal/relativizer complementizers reanalyzed (§5.2.1, pp.134–136)
Unlike other clause types (which use -ess/-Ø tense suffixes before a complementizer), adnominal
clauses use a different morphological system: three complementizer sets conventionally tied to
past/present/future, which Sohn argues is an oversimplification. **-(u)n** (action verbs,
conventionally "past") is analyzed as underlyingly -ESS-n, evidenced by (a) Kyengsang dialect
(archaic-retaining) allowing the fuller -ess-nun surface form in relatives, and (b) defective-noun
constructions (*ci* 'whether', *tey* 'circumstance') forcing the fuller form; it has a dual
past+perfective interpretation, the same dual function as matrix -ess. **-nun** (action verbs) /
**-(u)n** (stative verbs) (conventionally "present") is treated as containing NO tense category at
all — a conflation of an indicative suffix (-n/-nu/-nun) plus complementizer. **-(u)l** (action
verbs, occasionally stative; conventionally "future") is, per the book's central claim, NOT a future
tense marker but a predictive/prospective MODAL suffix combined with the nonpast-tense marker -Ø —
evidenced by its ability to combine with -ess for past-oriented readings (*ecey ka-ss-ul salam* 'a
person who may have gone yesterday').

#### Relative clauses: genuine anaphoric/deictic ambiguity (§5.2.2, pp.142–147)
Relative-clause tense can be EITHER anaphoric (coindexed with matrix tense) or deictic (interpreted
relative to speech time) — genuinely ambiguous by default, against earlier claims (Yang 1977, Lee
1985) that it's "basically anaphoric." The ambiguity resolves whenever the relative clause contains
a speech-time-oriented deictic expression (*ku ttay* 'then', *cikum* 'now', *ittaka* 'later', *ecey*
'yesterday', *akka* 'a while ago') — such an indexical forces the deictic reading and blocks the
anaphoric one; absent such an indexical, matrix-verb semantics or discourse context can still
disambiguate. Noun-complement clauses share the same three complementizers and the same ambiguity
in principle, but are more restricted in practice: tighter embedded/matrix cooccurrence
restrictions, less frequently ambiguous — e.g. a noun-complement clause with matrix verb *pota* 'to
see' (which semantically entails perceiving a prior-or-concurrent event) allows only -nun,
exclusively anaphoric; a complement headed by defective noun *twi/hwu* 'after' allows only the
-(u)n (-ESS-N) form, never -Ø-l or -Ø-nun, because 'after' semantically requires the embedded event
to precede the matrix event.

#### Verbal complements: overt -ess categorically banned (§5.3, pp.151–154)
Verbal-complement complementizers: infinitive -e/-a, gerundive -ko, resultative -key, suspective
-ci, desiderative -ko, conditional -umyen. **No overt tense form (-ess) is allowed in verbal
complement clauses at all** — stated as following from Principle C, not a surface cooccurrence
quirk. Exceptions where -ess does surface: the conjunctive suffix -taka and the verbal
complementizers -eya 'if only' and -umyen 'if'. For the ordinary (non-exception) complementizers,
null-tense interpretation is governed by matrix-clause tense (past matrix → embedded read as past;
nonpast matrix → embedded read as nonpast) — mostly anaphoric-only, unlike the ambiguous adnominal
clauses. Two future-oriented complementizers break this pattern and allow both anaphoric and deictic
null-tense readings: -key 'so that' and desiderative -ko 'to' (disambiguated by an explicit deictic
time adverb inside the complement clause). Where -ess does surface in the exception class, it
denotes perfective aspect layered under obligation ('had to have gone') or subjunctive/
counterfactual sense ('wished X had gone'), not ordinary past tense.

#### Quotative constructions: the most tense-permissive embedded type (§5.4, pp.154–157)
Quotative particles: indirect *ko* 'that', direct *hako*/*lako* 'saying that' (direct quotation is
syntactically identical to an ordinary unquoted sentence and not analyzed further). Two
distinguishing features: (1) quotative clauses freely allow BOTH overt past -ess AND overt
perfective -ess, unlike verbal complements (which ban -ess outright) and unlike relative/noun-
complement clauses (where it's only marginally allowed in restricted contexts); (2) they retain full
sentence-type enders (declarative/interrogative/propositive/imperative), but these are "speech-
level-neutral," lacking the addressee-honorific distinctions a matrix-clause ender would carry.
Worked example: *John-i na-eykey [Mary-ka yeki o-Ø-n-ta-ko] malhay-ss-ta* 'John told me that Mary
would/is/will come here' — the null tense inside the quoted clause is genuinely ambiguous between
anaphoric (coindexed with matrix past → 'would come', relative-future-in-the-past) and deictic
(independent of matrix, read against actual speech time → 'is/will come', still true now). This
directly refutes an earlier claim (N. Kim 1984) that an "unambiguous indirect quotation" forces
agreement with matrix tense — Sohn shows even clearly indirect quotations (marked by reflexive
*caki* 'self' instead of 1st-person *na* 'I', ruling out a direct-quotation reading) retain the
anaphoric/deictic ambiguity. Indirect quotative clauses therefore pattern like relative clauses for
tense purposes, not like verbal complements. A reported-speech-specific finding, likely genuinely
novel for this project's purposes: the double-perfective -ess-ess, marginal/unacceptable almost
everywhere else in the language, occurs freely and productively inside quotative clauses (and,
Sohn notes, probably also after the retrospective mood suffix) — e.g. *John-i [Mary-ka
ttena-ss-ess-Ø-ta]-ko malhay-ss-ta* 'John said that Mary had once left,' a "stacked perfective"
reading. Sohn flags this as a genuinely unresolved analytical puzzle and offers two unadopted
alternative analyses (treat -ess-ess as a true pluperfect-in-the-perfective morpheme; or treat the
whole quotative as two independently-tensed clauses glued together) without committing to either.

#### Nominalized constructions: -ki (nonfactive) vs. -um (factive) (§5.5, p.157)
Nominalizing suffixes -ki and -um turn a clause into a nominal. Traditional distinction (credited to
I. Yang 1972, not original to Sohn): -ki associated with NONFACTIVITY (events/states not presupposed
true — wishes, intentions, abilities), -um with FACTIVITY (presupposed true). Both allow the -ess
tense/aspect system to operate normally inside them, unlike verbal complements, which ban overt
-ess. A -um-nominalized headless embedded clause (*John-i hakkyo-ey ka-ss-Ø-um* 'that John had gone
to school') is structurally a headless nominalized clause dominated directly by NP, in contrast to a
superficially similar noun-complement construction using defective head noun *kes* 'thing' (same
meaning, different structure: NP dominating a CP with complementizer -(u)n plus overt head noun
*kes*). Nominalized clauses with null-form tense admit both anaphoric and deictic readings (like
relative clauses, unlike verbal complements) — against D. Yang (1977), who claimed complement-clause
tense is obligatorily anaphoric; Sohn shows this holds only when the matrix verb's semantics force a
specific temporal relation (e.g. *sicakhata* 'to begin' requires strict simultaneity with its
complement, forcing anaphoric-only; *palata* 'to hope/want' carries irrealis mood and allows the
ambiguity).

#### A restrictiveness hierarchy across embedded-clause types
Synthesizing Chapter 5: from most tense-flexible to most tense-restricted — quotative/relative
clauses (fully ambiguous, allow overt -ess and even -ess-ess) > noun-complement clauses (restricted
by matrix-verb semantics) > verbal complements (overt -ess banned outright, tense usually just
copies the matrix clause, except a couple of future-oriented complementizers). Combined with the
Chapter 2–5 modal-suffix findings, this supports the book's single most citable typological claim
for this project: **Korean has no future tense** — the "future" adnominal -(u)l, and the "future"
suffixes -keyss and -(u)l(i), are all nonpast tense combined with a genuinely separate predictive/
volitional/evidential MODAL category, never a dedicated future-tense form.

---

### Chapter 6 — Summary and theoretical implications

#### The book's own compressed claim list (§6.1, pp.161–162)
Sohn's own numbered summary of the monograph's contributions: Korean has both tense (obligatory) and
aspect (optional) as distinct categories; tense names a relation between event time and speech time,
not the event time itself; Korean tense has only two values, past and nonpast; -ess patterns like a
name/R-expression (Binding Principle C), -Ø like a pronominal (*pro*); the deictic reading of -Ø
defaults to nonpast; coindexed tenses share only their [±past] value, not event identity; an overt
tense form coindexed AND c-commanded by another tense category is ungrammatical (Principle C),
explaining why embedded past forms often surface as null rather than doubly marked; this mechanism
holds across subordinate, coordinate, relative, complement, and nominalized clause types.
Additional findings: -ess-ess marks past perfective/pluperfect; the retrospective suffix -te marks
neither tense nor aspect as such, yet still conveys pastness via its reference-time-setting function;
conjunctive suffixes split into [+temporal]/[−temporal], determining anaphoric vs. deictic null-
tense readings; transferentive -taka lacks inherent perfectivity and so uniquely allows overt -ess;
-ko has dual subordinating/coordinating functions, with overt -ess in either use still required to
be free of binding under Principle C; temporal adverbials disambiguate otherwise-ambiguous tense/
aspect readings and supply reference times.

#### Theoretical contribution and residual problems (§6.2, pp.162–166)
The core theoretical move — treating tense as a referring expression — lets Binding Theory explain
two parallels that look unrelated at first glance under one principle: overt tense as R-expression
(Principle C) and null-form tense as *pro*. A further benefit: positing an abstract tense category
in INFL (overt or null) explains why nominative case is still assigned to the subject of so-called
"tenseless" clauses in Korean — even a morphologically tenseless-looking clause has an abstract
tense category driving case assignment. Three residual problems the author flags herself (useful as
"open questions/theoretical nuance" framing rather than settled fact): (1) **Relative-clause tense**
— the adnominal -(u)n, analyzed as underlying -ESS-N, is "rarely actualized in phonetic form" as
such, creating an analytical gap; a worked example shows three possible readings (had read/has
read/read) that a simple -(u)n-as-ESS-N analysis doesn't fully predict, fixed by reanalyzing -(u)n
as -(ESS)-Ø-N (optional aspect -ESS, then null tense -Ø, then -N), correctly yielding exactly 3 of 4
logically possible combinations as grammatical (a null-tense-in-relative-clause NOT coindexed with
a past matrix tense is independently disallowed, since -(u)n inherently conveys completion). (2)
**Syntactic position of *ttay* 'time' adjunct clauses** — argued to attach at CP (not lower) because
they can take the topic marker -nun; two tense forms across a *ttay*-clause and its matrix can be
coindexed even across clauses because the second clause's IP blocks true c-command of the first
clause's tense, avoiding an apparent Principle C violation. (3) **Quotative-construction -ess-ess
behavior** — explicitly flagged as "not discussed in detail in this study," future-work territory:
two possible analyses (a genuine double-perfective reading unique to quotative clauses; or
quotative constructions as structurally two independently-tensed coordinated sentences, parallel to
the nontemporal coordinate -ko) are floated without full resolution. A fourth open issue: the
past-time adverb *ecey* 'yesterday' can cooccur with a null-form tense whose deictic interpretation
is still nonpast (*[John-i ecey ka-Ø-se] cikum o-Ø-n-ta* "John went yesterday and is coming back
now" — matrix tense nonpast/present despite the embedded clause referencing yesterday), supporting
the broader claim that the deictic reading of -Ø can be shifted by indexical/semantic context,
flagged as needing further study. The author explicitly names extending this integrated framework
to aspectual phenomena (currently comparatively underdeveloped relative to tense) as the single
biggest open avenue for follow-up research.

#### Conclusion (§6.3, p.166)
Sohn frames the monograph as providing the first comprehensive, unified framework for Korean tense
and aspect — more integrated than any prior account — by combining a tense/aspect theory with
contemporary Binding Theory (Principle C for overt -ess, the *pro* parallel for null -Ø). She
acknowledges other Korean linguists addressed pieces of these issues before, but presents this work
as the first fully integrated treatment, while acknowledging no linguistic theory explains every
phenomenon perfectly.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `../../00_Reference_Extraction_Spec.md`.
