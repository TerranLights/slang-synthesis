# Korean — Established Vocabulary/Grammar: Units 16-24 (Noun-Modifying Endings Through Quotation)

**Source:** Andrew Sangpil Byon, *Intermediate Korean: A Grammar and Workbook* (Routledge, 2010),
printed pages 137-227 (PDF pages 146-227 of the 289-page scanned/text-layer edition), covering Unit
16 ("The noun-modifying endings") through Unit 24 ("Direct and indirect quotation"). A sibling
subagent covers PDF pages 1-145 (printed pages 1-136, Units 1-15). The boundary was verified by
direct inspection of the table of contents and page-offset checking (see below), not assumed from
arithmetic: printed page 137 is exactly where Unit 16 begins and printed page 136 is the last page
of Unit 15's exercises — a clean unit boundary.

**Page-offset finding:** `PDF_page = printed_page + 9` holds consistently throughout this book
(verified at four independent points spanning the assigned range: printed p. 1 = PDF p. 10, printed
p. 142 = PDF p. 151, printed p. 192 = PDF p. 201, printed p. 242 = PDF p. 251).

## Critical methodology note: this PDF's Hangul is encoded via a decodable font-substitution cipher

**This is a "clean text layer" PDF in the sense that `pdftotext`/PyMuPDF extract real, consistent
character data for every page — but the Hangul-bearing font (`Batang-KSCms-UHC-H-Identity-H`, a
CID-keyed embedded font with `Identity-H` encoding and *no ToUnicode CMap*) has no correct
CID→Unicode mapping, so naive extraction renders Korean text as a wall of unrelated-looking CJK
symbols/Latin-Extended glyphs (e.g. "가다" extracts as "Ṗ┺").** This matches the "fixed,
decodable font-substitution cipher" gotcha in `00_Reference_Extraction_Spec.md`. English text on
the same pages extracts perfectly — only the Hangul is affected.

**The cipher decodes with a single additive Unicode-codepoint shift, confirmed and applied across
this entire chunk:** for any extracted character `c`, if `ord(c) + 36266` falls inside the Hangul
Syllables block (`U+AC00`-`U+D7A3`), the correct character is `chr(ord(c) + 36266)`; otherwise the
character (ASCII, standard punctuation, typographic quotes/dashes) is left as-is. A small blacklist
of typographic characters that happen to fall in the same numeric range as shifted Hangul (curly
quotes, en/em dash, ellipsis, bullet, prime marks) must be explicitly excluded from the shift or
they get corrupted into spurious Hangul-looking glyphs. This was verified against 15+ known
word/gloss pairs across four widely separated pages (Unit 1, Unit 16, Unit 21, Key to Exercises) and
produces fully coherent, grammatical Korean throughout — confidence is high, not merely
"plausible." **This finding applies to the whole book, not just this chunk** — worth flagging to
whichever subagent(s) handle PDF pages 1-145 and any future Korean-language re-extraction of this
same source file, so the cipher does not need to be independently rediscovered.

A minor, unrelated residual artifact: an isolated capital "G" occasionally appears standing in for
a lost space character between a Hangul word and the following English gloss (e.g. "신혼여행Ghoneymoon"
→ "신혼여행 honeymoon") — this looks like a separate non-breaking-space encoding glitch in an
English-language font used for the vocabulary-list layout, not part of the Hangul cipher. It was
corrected wherever it appeared in this chunk's vocabulary lists.

Given the above, **Vision Reading Confidence is `n/a` throughout this file** (the source had a real
text layer; the decode is a character-remapping of that machine-extracted text, not a vision
reading of page images) — but the decode methodology is documented here in full so any downstream
consumer can audit or independently re-derive it.

## Coverage note

Extracted per `00_Reference_Extraction_Spec.md`'s comprehensive-but-not-exhaustive rule:

- **Every grammar point** from Units 16-24 (see Grammar points below) — paraphrased, with a small
  number of illustrative examples per point rather than the book's full example sets.
- **Every distinct vocabulary item** from each unit's own "Key vocabulary for Unit N exercises"
  list — the book's own deliberately curated new-vocabulary list per unit, 649 entries total. This
  is the appropriate "distinct vocabulary item" source per unit: exercise *drill items* (the
  numbered translation/transformation exercises themselves) were not separately mined for
  additional incidental vocabulary, per the spec's explicit license to skip "repeated drill
  exercises... that don't introduce new vocabulary or grammar beyond what's already been captured
  from this same chunk" — the drills overwhelmingly reuse the unit's own key-vocabulary list in
  varied sentence positions rather than introducing new lexical content.
- **"Key to Exercises" (printed pages 228-278, within this chunk's PDF-page range) was *not*
  re-extracted.** It is the answer key for all 24 units' drill exercises (Units 1-15's answers
  physically fall inside this chunk's assigned PDF-page range even though Units 1-15's own grammar
  content is the sibling subagent's territory). Its content is, without exception, complete
  sentences built from vocabulary already captured either here (Units 16-24) or in the sibling's
  vocabulary tables (Units 1-15) — extracting it again would be pure duplication, not new distinct
  vocabulary. Flagged here explicitly per the spec's "state explicitly what was skipped as
  redundant" rule.
- **The Index (printed pages 279-280) was not extracted** — it is a page-reference index only (e.g.
  "particle 까지 21"), containing no new vocabulary, gloss, or grammar explanation beyond a page
  pointer.
- No explicit dialectal/regional annotation (comparable to B/C/S-style tags) appears anywhere in
  this chunk — this book teaches standard contemporary Korean without marking regional variants, so
  Attested Region/Geographic Scope are `—` throughout, per the column rules (don't infer regionality
  from a book's own publisher/title).

---

## Grammar points

### Unit 16 — The noun-modifying endings ~는, ~(으)ㄴ, ~(으)ㄹ (p. 137-140)

Korean modifiers always precede the noun they modify (unlike English relative clauses), and any
predicate becomes a modifier by attaching a noun-modifying ending to its stem.

- **~는** — attaches to a **verb** stem for present-tense modification (자다 "sleep" → 자는 학생
  "the student who sleeps"). A few 있다/없다-final adjectives (맛있다, 맛없다, 멋있다, 재미있다) also
  take ~는 rather than ~(으)ㄴ.
- **~(으)ㄴ** — with **adjectives/copulas**, present meaning (작다 → 작은 책상 "small desk"); with
  **verbs**, past meaning (먹다 → 저녁을 먹은 사람 "the person who ate dinner"). Adding the past-tense
  marker 었/았 together with ~(으)ㄴ on a verb is explicitly flagged as ungrammatical (내가 먹은 음식
  is correct, *내가 먹었은 음식 is not).
- **~(으)ㄹ** — prospective/future meaning on verbs or adjectives (읽다 → 내일 읽을 책 "the book I
  will read tomorrow"); when combined with the past tense marker (~었/았을), the meaning shifts from
  prospective to **conjecture** ("might have"): 먹었을 사람 "the person who might have eaten," a
  distinct nuance from the plain past (~은), present (~는), and prospective (~을) readings of the
  same verb.

> **Morpheme breakdown — 먹었을 사람** "the person who might have eaten": 먹- (eat, verb stem) +
> -었- (past tense marker) + -을 (prospective/conjectural noun-modifying ending) + 사람 (person,
> noun) — four morphemes stacked onto one surface form, illustrating Korean's agglutinative
> tense/aspect + modification layering discussed in
> `../00_Word_Concept_and_Morphological_Typology_Guide.md`.

### Unit 17 — Describing the appearance of actions or states of affairs (p. 146-156)

Five constructions expressing conjecture/appearance, all built by combining one of the Unit 16
noun-modifying endings with a dependent noun/verb:

- **~는/(으)ㄴ/(으)ㄹ 것 같다** "(it) seems/looks like" — 것 "the fact/one" (colloquially **거**) +
  같다 "be the same."
- **~는/(으)ㄴ/(으)ㄹ 모양이다** "appears/looks like" — 모양 "appearance/form" + copula 이다.
- **~는/(으)ㄴ/(으)ㄹ 듯하다** "seems/appears" — 듯 "seeming appearance" + 하다.
- **~나/(으)ㄴ가 보다** "(I) guess that" — verbs take ~나 보다; adjectives/copulas take ~(으)ㄴ가 보다
  (은가 보다 after a consonant, ㄴ가 보다 after a vowel); past tense always uses ~나 보다 after the
  past marker (었/았나 보다) regardless of predicate type. The main verb 보다 itself does not
  normally carry a tense marker in this construction — adding one produces a different, literal
  "checked whether" meaning instead of "guess."
- **~어/아 보이다** "looks/appears to be" — adjectives only; in the past tense, only 보이다 takes the
  tense marker, not the preceding adjective stem (기분이 나빠 보였어요, not *나빴어 보였어요).

### Unit 18 — Post modifiers I (p. 157-165)

Seven idiomatic noun-modifying-ending + noun combinations ("post modifiers"):

- **~는 길(에)** "on the way to/from," used with movement verbs (가다/오다).
- **~(으)ㄴ 적/일 (이) 있다/없다** "have/have never (done something)," an experiential perfect;
  often combined with ~어/아 보다 "try doing" (서울에 가 본 적이 있어요 "I have been to Seoul").
  Recent time expressions (지난 주에, 어제) are noted as pragmatically odd with this construction,
  which implies a temporally distant experience.
- **~는 동안(에)** "while/during," expressing temporal overlap.
- **~는 도중(에)** "on the way to/from, in the middle of."
- **~는 중이다** "in the process of" — similar to progressive ~고 있다 but foregrounds the ongoing
  process itself.
- **~는/(으)ㄴ 편이다** "tends to/kind of" — verbs take ~는, adjectives take ~(으)ㄴ.

### Unit 19 — Post modifiers II (p. 166-177)

- **~는/(으)ㄴ 대로** "as soon as / in accordance with" (대로 "according to").
- **~(으)ㄴ 후에** "after" (후 "after" + particle 에); 다음 or 뒤 can substitute for 후 with similar
  meaning.
- **~는/(으)ㄴ 척/체하다** "pretend" — 는 for present-tense verb pretense, (으)ㄴ for past-tense verb
  pretense or present adjective/copula pretense.
- **~는 바람에** "as a result of/because of" (바람 "wind") — restricted to **negative or unpleasant**
  incidental consequences (늦게 일어나는 바람에 학교에 못 갔어요 "couldn't go to school because of
  getting up late").
- **~는/(으)ㄴ 것이다** "the fact is that / what happened is that" (것, colloquially 거, + copula).
- **~(으)ㄹ 뻔했다** "almost/nearly" (뻔 "almost, about to" + 했다).
- **~(으)ㄹ 때** "when" — a subtle tense-marking rule: if only the main clause carries past tense,
  the 때-clause action co-occurred with the main clause's; if **both** clauses carry past tense, the
  때-clause action happened **prior to** the main clause's action.

### Unit 20 — Ability and possibility (p. 178-185)

- **~(으)ㄹ 수 있다/없다** "can/cannot, (it) is possible/not possible to" — with adjectives,
  expresses possibility of a state rather than ability. Distinguished from negation with 못: 못
  emphasizes plain inability, while ~(으)ㄹ 수 없다 additionally frames the *possibility* of the
  action. The particles 도 ("also"), 만 ("only"), and 밖에 ("except/but") can attach to the
  intervening noun 수 for added nuance; ~(으)ㄹ 수밖에 없다 specifically means "have no choice but
  to/can't help (doing)."
- **~(으)ㄹ 줄 알다/모르다** "know/not know how to" (줄 "the way how to"); with a third-person
  subject, indicates the speaker's presumed expectation ("I thought/didn't think that...").
- **~(으)ㄹ 리가 없다** "there is no possibility that / it can't be that" (리 "possibility" + subject
  particle 가 + 없다).

### Unit 21 — Indirect question form ~는/(으)ㄴ/(으)ㄹ지 (p. 186-194)

Built from a noun-modifying ending + the dependent noun 지 ("whether/given the state of
being/since"). ~는지 (verb, present), ~(으)ㄴ지 (adjective/copula, present), ~(으)ㄹ지 (verb or
adjective/copula, unrealized/prospective); past tense uniformly uses ~었/았는지 for all predicate
types. Commonly follows 알다/모르다/궁금하다. In a non-interrogative sentence it marks the speaker's
own speculative/uncertain mindset rather than forming a literal question. The adverb 얼마나 ("how
much/many") added to this construction can lend an exclamatory sense. Two derived expressions:
**~어/아야 할지 모르다** "not know what one must do," and **~(으)ㄴ지 . . . 되다/지나다** "it has been
[amount of time] since," expressing elapsed time.

### Unit 22 — The retrospective suffix ~더 (p. 195-204)

Several forms built on the retrospective suffix 더, marking the speaker's own direct past
observation/experience:

- **~더라구요** — sentence-final ending; **the book explicitly labels this "primarily used in
  spoken communication"** — a register marker distinguishing it from written registers. Stresses
  the authenticity of the speaker's own witnessed experience ("I am telling you," "you know").
- **~던** — retrospective noun-modifying ending: habitual past action with verbs (만나던 여자 "the
  woman I used to meet"), a state that no longer holds with adjectives (조용하던 방 "the room that
  used to be quiet"). Combining with the past marker (었/았던) pushes the recollection further into
  the past ("a long time ago").
- **~더니** — clausal conjunctive, "but (now)/as a result," based on the speaker's own direct past
  observation; only the main clause is normally tense-marked even when the ~더니 clause describes a
  past event, though ~었/았더니 is available for a more temporally distant reading.
- **~었/았더라면** — "if (something had/had not been the case)," expressing regret or counterfactual
  supposition (담배를 안 피웠더라면 더 건강했을 거예요 "if I hadn't smoked, I would have been
  healthier").
- **~더라도** — "even though (it may be the case)," acknowledging a clause's content while
  emphasizing that the main clause must hold regardless.

### Unit 23 — Nominalizing endings ~기 and ~(으)ㅁ (p. 205-214)

**~기** turns a verb into "the act of ~ing" or an adjective into "the state of being ~" and is the
base for a long list of derived expressions, each combining ~기 with a following particle/noun/verb:
~기는 커녕 "far from ~ing" (emphatic negation); ~기 전에 "before ~ing"; **~기는요** "what do you
mean...?/no way!" — **explicitly a politeness/humility marker**, used to deflect a compliment or
mildly contest another speaker's claim (책이 좋아요 "your car is nice" → 좋기는요, 싸게 샀어요 "no
way, I got it cheap"); ~기에는 "as for ~ing"; ~기 때문에 "because of ~ing"; ~기 위해서 "in order
to"; ~기로 하다 "decide/plan to" (결정하다/결심하다/정하다 can substitute for 하다); ~기 시작하다
"begin to"; a family of ~기가 + adjective forms ("~기가 어렵다/쉽다/힘들다/좋다/편하다/싫다/재미있
다/귀찮다" — difficult/easy/laborious/good/convenient/unwilling/fun/bothersome to do); and ~기도
하다 "also does (a less typical activity)."

**~(으)ㅁ** is far more restricted than ~기: used only when the predicate's activity/state has
already been actualized/confirmed (존이 서울에 갔음을 몰랐어요 "we didn't know John had gone to
Seoul"). A number of ordinary Korean nouns are lexicalized from this ending (살다→삶 "life,"
죽다→죽음 "death," 웃다→웃음 "smile/laughter," 울다→울음 "weeping," 자다→잠 "sleep," 아프다→아픔
"pain," 기쁘다→기쁨 "joy," 즐겁다→즐거움 "gladness," 어렵다→어려움 "hardship"). **~(으)ㅁ can also
stand alone as a terse sentence-final ending** in concise notice/memo-style registers — the book's
own examples read like written notices or texted status updates rather than spoken sentences
(저녁 안 먹었음 "Did not eat dinner," 오늘 수업 없음 "No class today," 친구 찾았음 "Found a
friend") — a distinct register worth flagging alongside ~더라구요's spoken-register marking above.

> **Morpheme breakdown — 좋기는요** (humility/mild-contention response to a compliment): 좋- (be
> good, adjective stem) + -기 (nominalizing ending) + -는 (topic particle) + -요 (politeness
> marker) — the nominalized "goodness" is topicalized and then, via intonation/context rather than
> further morphology, read as ironic/deflecting rather than affirming.

### Unit 24 — Direct and indirect quotation (p. 215-227)

- **Direct quotation**: quoted utterance + particle (이)라고 + a quoting verb (말하다, 대답하다,
  묻다, 부탁하다, etc.). When quoting mimetic/onomatopoeic expressions or reproducing exact tone,
  하고 replaces (이)라고 (땡땡 하고 울렸다 "rang 'ding-dong'").
- **Indirect quotation** is markedly more frequent than direct quotation in Korean, and always
  **downgrades the quoted utterance to the plain speech level** (introduced in Unit 1, the sibling
  chunk's territory) regardless of the original utterance's own speech level — a clear point of
  contact between the honorific/speech-level system and the quotation system. The plain-speech-level
  ending selected depends on the quoted sentence's type: declarative ~(느)ㄴ다고 (verbs) / ~다고
  (adjectives) / ~라고 (copulas); interrogative ~냐고 (하다/묻다); imperative ~(으)라고 (note: not
  the plain-level ~어라/아라, a specific substitution for quotation); propositive ~자고. First-person
  pronouns and tense are likewise adjusted to the reporting speaker's perspective (저 "I" (humble) →
  자기 "self" when reporting a third party's self-reference).
- **Colloquial contraction of indirect-quotation endings** — explicitly flagged by the book as a
  conversational-register phenomenon: ~(느)ㄴ다고 하다 → **~(느)ㄴ대요**; ~라고 하다 → **~래요**;
  ~(으)라고 하다 → **~(으)래요**; ~자고 하다 → **~재요**.
  This is a register-marked morphological fusion (quotation particle + 하다 collapsing into a single
  suffix) distinct from the fuller, more formal/written forms.
- **Reporting one's own thoughts/feelings** uses the same indirect-quotation machinery (고 + 생각하다
  "think" / 느끼다 "feel") to report internal speech rather than another speaker's utterance.

> **Morpheme breakdown — 좋아한대요** (colloquial contraction, "they say [he] likes [it]"): 좋아하-
> (like, verb stem) + -ㄴ다 (plain-level declarative ending) + -고 (quotation particle) + 하- (say)
> + -어요 (polite present ending), fully written out as 좋아한다고 해요, contracting to 좋아한대요 —
> five underlying morphemes/words compressed into one colloquial surface form, a clear case of
> register-conditioned morphological fusion worth noting for later `analysis/` work on Korean slang
> mechanics (contraction as a marker of colloquial register, distinct from ordinary agglutinative
> stacking).

---

## Register and honorific notes (summary)

This chunk (Units 16-24) does not introduce the core speech-level system itself (that is Unit 1,
in the sibling chunk's territory), but several unit-specific constructions carry their own explicit
register marking, gathered here for visibility:

- **~더라구요** (Unit 22) — book explicitly labels this "primarily used in spoken communication."
- **~기는요** (Unit 23) — a humility/mild-contention marker for responding to compliments or
  another speaker's claim; a social/politeness function layered on top of the plain ~기는 negation.
- **~(으)ㅁ as a sentence-final ending** (Unit 23) — a terse, notice/memo-style register, distinct
  from ordinary spoken sentence endings.
- **Colloquial contraction of indirect-quotation endings** (~대요/~래요/~(으)래요/~재요, Unit 24) —
  explicitly framed by the book as a conversational-register phenomenon, contrasted with the fuller
  written/formal quotation forms.
- **것 vs. 거** (Units 17, 19) — 거 is repeatedly noted as the colloquial variant of the dependent
  noun 것 across multiple constructions (~는 것 같다/~는 거 같다; ~는 것이다/~는 거예요).
- **Indirect quotation's forced plain-speech-level downgrade** (Unit 24) — every quoted utterance,
  regardless of its original speech level, is re-encoded in the plain speech level before the
  quotation particle 고/(이)라고 attaches; this is a structural (not merely stylistic) register
  fact worth carrying into later `analysis/` work on how Korean's honorific system interacts with
  reported speech.

---

## Vocabulary

Each unit's own "Key vocabulary for Unit N exercises" list, in the book's own order. All entries are
citation-form (dictionary) headwords — plain verb/adjective stems ending in ~다, bare nouns — so no
morpheme breakdown is needed for these vocabulary-table rows themselves (breakdowns for the
agglutinative example forms discussed in the Grammar points sections above are given inline there).

### Unit 16 — The noun-modifying endings (~는, ~(으)ㄴ, ~(으)ㄹ) (Key vocabulary for exercises, p. 137-145)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가다 | to go | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 갈아타다 | to change (car/train)/to transfer | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 결혼하다 | to marry (a person) | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 과일 | fruits | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 기차 | train | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 내일 | tomorrow | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 내 | I/my | pronoun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 네 | you | pronoun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 노래 | song | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 높다 | to be high | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 누나 | older sister | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 다음 | next | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 동료 | colleague | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 듣다 | to listen | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 만나다 | to meet | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 만들다 | to make | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 미국 | U.S.A. | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 받다 | to receive | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 방 | room | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 버리다 | to throw away | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 빌리다 | to borrow | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 사다 | to buy | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 사람 | person/people | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 산 | mountain | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 살다 | to live | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 선물 | gift/present | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 섬 | island | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 싸다 | to be cheap/to wrap up | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 쓰다 | to use | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 쓰레기 | trash | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 아름답다 | to be beautiful | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 아침 | morning/breakfast | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 아파트 | apartment | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 양복 | suit/dress | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 어제 | yesterday | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 옷 | clothes | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 음식 | food | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 이사가다 | to move (into a new address) | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 일하다 | to work | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 입다 | to wear (a dress) | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 작년 | last year | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 제일 | the first/most | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 조용하다 | to be quiet | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 주 | week | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 지난 | last | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 집 | house | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 책 | book | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 친구 | friend | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 학교 | school | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 형 | older brother | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |
| 회사 | company | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 16's own "Key vocabulary for exercises" list. |

### Unit 17 — Describing the appearance of actions or states of affair (Key vocabulary for exercises, p. 146-156)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가격 | price | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 가난하다 | to be poor | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 가다 | to go | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 가르치다 | to teach | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 가볍다 | to be light | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 건너다 | to cross/to go over | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 결혼하다 | to marry | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 겸손하다 | to be humble | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 고치다 | to fix/to repair | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 공항 | airport | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 귀걸이 | earring | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 기다리다 | to wait | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 기숙사 | dormitory | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 김치 | kimchi vocabulary for Unit 17 exercises | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 깨끗하다 | to be clean | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 끊다 | to quit | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 날씨 | weather | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 노래 | song | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 노트북 | notebook | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 눈 | snow/eyes | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 다리 | bridge/leg | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 다음 | next | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 달 | month | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 담배 | cigarette | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 대학원생 | graduate student | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 덥다 | to be hot | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 도착하다 | to arrive | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 돈 | money | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 돌아가다 | to return | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 돕다 | to help | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 똑똑하다 | to be smart | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 많다 | to be many/to be much | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 맛없다 | to be tasteless | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 맛있다 | to be delicious | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 매일 | everyday | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 머리 | head/hair (of one’s head) | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 바쁘다 | to be busy | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 별로 | not in particular | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 병원 | hospital | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 봄 | spring | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 부르다 | to sing/to call out | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 부엌 | kitchen | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 부지런하다 | to be diligent | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 부치다 | to send | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 비싸다 | to be expensive | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 빌리다 | to borrow | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 사다 | to buy | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 사람 | person/people | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 살다 | to live | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 성실하다 | to be earnest | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 수요일 | Wednesday | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 슬프다 | to be sad | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 시키다 | to order (something)/to force (a person to do) | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 신혼여행 | honeymoon | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 싱겁다 | to be watery | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 싸다 | to be cheap/to be inexpensive | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 아프다 | to be sore | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 안 | inside | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 안경 | glasses | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 애플파이 | apple pie | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 없다 | not have/not exist | verb/adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 영어 | English | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 예쁘다 | to be pretty | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 오다 | to come/to precipitate/to drop | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 오후 | afternoon/p.m. | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 요리하다 | to cook | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 음식 | food | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 인기 | popularity | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 일본 | Japan | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 일하다 | to work | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 잘 | well/expertly/nicely | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 젊다 | to be young | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 좋아하다 | to like | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 지갑 | wallet | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 집 | house | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 짜다 | to be salty | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 찌개 | pot stew | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 차 | car | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 출발하다 | to depart | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 춥다 | to be cold | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 친구 | friends | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 편지 | letter | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 학기 | semester | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 한국 | Korea | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 형 | older brother | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |
| 흐리다 | to be cloudy | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 17's own "Key vocabulary for exercises" list. |

### Unit 18 — Post modifiers I (길, 적/일, 동안, 도중, 중, 편) (Key vocabulary for exercises, p. 157-165)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가다 | to go | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 나가다 | to go out | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 날씨 | weather | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 내 | I/my | pronoun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 다투다 | to quarrel/to argue | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 돼지고기 | pork | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 맥주 | beer | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 모자 | hat vocabulary for Unit 18 exercises | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 받다 | to receive | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 배우다 | to learn | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 사다 | to buy | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 슈퍼마켓 | supermarket | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 스키 | ski | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 시키다 | to order/to ask (someone to do) | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 시험 | test/exam | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 싸다 | to pack | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 썰다 | to cut up/to slice | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 쓰다 | to use | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 아내 | wife | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 양복 | suit/dress | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 어렵다 | to be difficult | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 어머니 | mother | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 오늘 | today | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 요리 | cooking | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 음식 | food | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 이야기하다 | to talk | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 일요일 | Sunday | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 일하다 | to work | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 입다 | to wear/to put on | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 자다 | to sleep | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 자리 | seat | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 잔소리 | useless talk/scolding/preaching | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 잘 | well/expertly | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 장학금 | scholarship | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 조깅 | jogging | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 좋아하다 | to like/to be fond of/to rejoice | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 중국 | China | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 짐 | loads/packages | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 찾다 | to look for/to seek for | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 치다 | to play (tennis or piano)/to strike | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 친구 | friend | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 타다 | to ride | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 태권도 | Taekwondo | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 한국 | Korea | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 형 | older brother | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 화장실 | toilet | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |
| 흐리다 | to be cloudy | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 18's own "Key vocabulary for exercises" list. |

### Unit 19 — Post modifiers II (대로, 후에, 척/체하다, 바람에, 것이다, 뻔했다, 때) (Key vocabulary for exercises, p. 166-177)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가다 | to go | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 감기 걸리다 | to catch a cold/flu | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 갑자기 | suddenly | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 건너다 | to cross/to go over | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 결혼식 | wedding ceremony | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 경기 | game | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 경찰 | police | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 고장이 나다 | to get out of order/to break down | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 골다 | to snore | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 공부 | study/learning | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 관심이 없다 | to be uninterested | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 기분 | feeling/mood | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 길 | road/street | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 끄다 | to switch off/to extinguish | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 끓이다 | to boil | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 나쁘다 | to be bad/to be wrong | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 날씨 | weather | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 남자 | man | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 넣다 | to put (something) into/to insert | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 노래 | song | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 늦게 | late | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 다치다 | to hurt (oneself)/to be wounded | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 닫다 | to close | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 대학 | college | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 덥다 | to be hot | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 도움 | help | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 돈 | money | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 돌려주다 | to return (a thing)/to give (a thing) back | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 돌아가다 | to return/to go back | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 되다 | to become | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 듣다 | to listen/to take (a class) | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 라면 | ramyon/instant noodle | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 마시다 | to drink | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 마치다 | to finish/to accomplish | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 많다 | to be many/to be much | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 많이 | a lot | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 맥주 | beer | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 먹다 | to eat | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 모자 | hat | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 문 | door | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 물 | water | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 미끄러지다 | to slide | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 바지 | pants | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 받다 | to receive | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 보다 | to see/to watch | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 부르다 | to sing | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 비 | rain | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 빠지다 | to fall into/to be drowned | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 사고가 나다 | to have an accident | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 사무실 | office | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 새벽 | dawn | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 생일 | birthday | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 서류 | documents | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 서점 | bookstore | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 선물 | gift/present | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 소금 | salt | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 수업 | class | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 숙제 | homework | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 스트레스 | stress | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 시간 | hour/time | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 시작하다 | to start | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 시키다 | to order (something from a person)/to force (a person to do) | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 식사 | meal | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 싫어하다 | to dislike | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 심심하다 | to be bored | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 싸우다 | to quarrel/to fight | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 아이들 | children | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 약속 | promise/appointment | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 양복 | suit/dress | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 어리다 | to be juvenile/to be childish | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 연락 | contact | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 열쇠 | keys | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 영화 | movie | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 오다 | to come | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 옷 | clothes | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 와인 | wine | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 우산 | umbrella | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 운동 | exercises | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 월급 | salary | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 음식 | food | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 음악 | music | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 의사 | doctor | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 이기다 | to win/to overcome | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 이메일 | e-mail | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 일 | work | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 일어나다 | to get up | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 일하다 | to work | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 잃다 | to lose | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 입다 | to wear/to put on | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 잊다 | to forget | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 자다 | to sleep | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 잠 | sleeping | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 잠그다 | to lock | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 전등 | electric lamp | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 전화 | telephone | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 젖다 | to get wet | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 좋다 | to be good/to be nice | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 준비 | preparation | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 졸업하다 | to graduate | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 지각하다 | to be late/to be tardy | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 지다 | to lose/to get defeated | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 집 | house | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 짜다 | to be salty | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 짧다 | to be short | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 차 | car/tea | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 창문 | window | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 찾다 | to look for/to seek for | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 취직 | employment | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 친구들 | friends | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 코 | nose | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 필요하다 | to be in need of | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 행복하다 | to be happy | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 화내다 | to get angry | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 허리 | waist | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 회사 | company | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |
| 흐리다 | to be cloudy | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 19's own "Key vocabulary for exercises" list. |

### Unit 20 — Ability and possibility (Key vocabulary for exercises, p. 178-185)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가게 | store | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 20's own "Key vocabulary for exercises" list. |
| 가다 | to go | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 20's own "Key vocabulary for exercises" list. |
| 갈아타다 | to change (cars/trains) | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 20's own "Key vocabulary for exercises" list. |
| 같이 | together | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 20's own "Key vocabulary for exercises" list. |
| 골프 | golf | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 20's own "Key vocabulary for exercises" list. |
| 김치 | kimchi | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 20's own "Key vocabulary for exercises" list. |
| 노래 | song | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 20's own "Key vocabulary for exercises" list. |
| 느끼다 | to feel | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 20's own "Key vocabulary for exercises" list. |
| 닫다 | to close | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 20's own "Key vocabulary for exercises" list. |
| 대학 | college | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 20's own "Key vocabulary for exercises" list. |
| 더위 | the heat/sun stroke | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 20's own "Key vocabulary for exercises" list. |
| 디자인 | design | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 20's own "Key vocabulary for exercises" list. |
| 떠나다 | to depart/to take leave of | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 20's own "Key vocabulary for exercises" list. |
| 마시다 | to drink | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 20's own "Key vocabulary for exercises" list. |
| 만들다 | to make | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 20's own "Key vocabulary for exercises" list. |
| 미국 | U.S.A. | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 20's own "Key vocabulary for exercises" list. |
| 부르다 | to sing/to call out | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 20's own "Key vocabulary for exercises" list. |
| 사귀다 | to make friends | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 20's own "Key vocabulary for exercises" list. |
| 생활 | living/life | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 20's own "Key vocabulary for exercises" list. |
| 수영하다 | to swim | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 20's own "Key vocabulary for exercises" list. |
| 쉽다 | to be easy | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 20's own "Key vocabulary for exercises" list. |
| 싸다 | to be cheap | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 20's own "Key vocabulary for exercises" list. |
| 어떻게 | how | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 20's own "Key vocabulary for exercises" list. |
| 예쁘다 | to be pretty | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 20's own "Key vocabulary for exercises" list. |
| 오늘 | today | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 20's own "Key vocabulary for exercises" list. |
| 와인 | wine | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 20's own "Key vocabulary for exercises" list. |
| 요금 | fee | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 20's own "Key vocabulary for exercises" list. |
| 운동 | exercise/sports | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 20's own "Key vocabulary for exercises" list. |
| 운전하다 | to drive | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 20's own "Key vocabulary for exercises" list. |
| 월요일 | Monday | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 20's own "Key vocabulary for exercises" list. |
| 일본 | Japan | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 20's own "Key vocabulary for exercises" list. |
| 일찍 | early | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 20's own "Key vocabulary for exercises" list. |
| 잘 | well/expertly | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 20's own "Key vocabulary for exercises" list. |
| 재미있다 | to be interesting | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 20's own "Key vocabulary for exercises" list. |
| 지하철 | subway | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 20's own "Key vocabulary for exercises" list. |
| 치다 | to play (tennis/golf/piano) | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 20's own "Key vocabulary for exercises" list. |
| 친구 | friend | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 20's own "Key vocabulary for exercises" list. |
| 토요일 | Saturday | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 20's own "Key vocabulary for exercises" list. |
| 트럭 | truck possibility | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 20's own "Key vocabulary for exercises" list. |
| 편하다 | to be convenient/to be comfortable | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 20's own "Key vocabulary for exercises" list. |
| 한국 | Korea | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 20's own "Key vocabulary for exercises" list. |
| 형 | older brother | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 20's own "Key vocabulary for exercises" list. |
| 회사 | company | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 20's own "Key vocabulary for exercises" list. |

### Unit 21 — Indirect question form (Key vocabulary for exercises, p. 186-194)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가게 | store | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 가다 | to go | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 감기 | cold/flu | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 공부 | study | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 기다리다 | to wait | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 길 | road | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 날씨 | weather | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 눈 | snow | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 늦다 | to be late | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 닫다 | to close question form | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 덥다 | to be hot | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 도착하다 | to arrive | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 떠나다 | to leave/to depart | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 마시다 | to drink | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 막히다 | to be blocked/to be held up | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 많이 | a lot | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 먹다 | to eat | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 문제 | problem | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 방 | room | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 번호 | number | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 보다 | to see/to watch/to read | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 비행기 | airplane | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 살 | age/one’s years | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 시끄럽다 | to be noisy | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 시작하다 | to begin | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 시험 | test/examination | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 싸다 | to be cheap/to be inexpensive | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 어렵다 | to be difficult | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 여자 친구 | girlfriend | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 영화 | movie | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 오다 | to come | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 요즈음 | nowadays | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 운동 | exercise/sports | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 음식 | food | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 이틀 | two days | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 일하다 | to work | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 재미있게 | interestingly | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 저녁 | dinner | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 전화 | telephone | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 점심 | lunch | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 집 | house | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 짜다 | to be salty | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 차 | car | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 취직하다 | to get employed | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 층 | floor | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 타다 | to ride | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 팔다 | to sell | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 편지 | letter | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 풀다 | to solve | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 학교 | school | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 헤어지다 | to break up | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 화장실 | toilet | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |
| 회사 | company | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 21's own "Key vocabulary for exercises" list. |

### Unit 22 — The retrospective suffix ~더 (Key vocabulary for exercises, p. 195-204)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가다 | to go | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 가져오다 | to bring | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 같이 | together | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 고기 | meat | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 교복 | school uniform | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 기다리다 | to wait | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 기분 | feeling/mood | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 꼭 | surely | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 나쁘다 | to be bad/to be wrong | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 나오다 | to come out | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 대학교 | college | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 돈 | money | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 동료 | colleague | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 드라마 | drama | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 떠나다 | to depart/to take leave of/to leave | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 마시다 | to drink | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 만나다 | to meet | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 맥주 | beer | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 머리 | head | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 먹다 | to eat | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 무겁다 | to be heavy | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 반지 | (a finger) ring | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 배우다 | to learn | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 병원 | hospital | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 보다 | to see/to watch/to read | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 부지런하다 | to be diligent | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 사귀다 | to make friends/to go out with | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 사다 | to buy | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 사람 | person/people | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 사장 | president (of company)/CEO | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 살다 | to live | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 소설책 | novel | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 슬프다 | to be sad | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 시끄럽다 | to be noisy | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 아침 | morning/breakfast | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 아파트 | apartment | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 아프다 | to be sore | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 약 | medicine | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 어제 | yesterday | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 여자 | woman | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 영화 | movie | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 오빠 | older brother | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 오후 | afternoon | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 요리하다 | to cook | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 울다 | to cry | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 웃다 | to smile | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 음식 | food | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 이번 주 | this week | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 재미없다 | to be uninteresting | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 전에 | before | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 조용하다 | to be quiet | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 졸다 | to doze off | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 중학교 | middle school | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 즐겨 | willingly/frequently | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 지난 주 | last week | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 집 | house | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 차 | car | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 책 | book | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 친구 | friend | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 토요일 | Saturday | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 피곤하다 | to be tired | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 한국어 | the Korean language | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |
| 회사 | company/firm | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 22's own "Key vocabulary for exercises" list. |

### Unit 23 — Nominalizing endings (~기, ~(으)ㅁ) (Key vocabulary for exercises, p. 205-214)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가끔 | sometimes | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 가다 | to go | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 감기 걸리다 | to catch a cold | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 같이 | together | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 개 | dog | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 결혼하다 | to marry | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 경기 | game/competitive sport | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 고치다 | to fix/to repair | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 교수님 | professor | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 구경 | sightseeing/looking around | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 구하다 | to seek | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 기간 | period | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 기숙사 | dormitory | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 기차 | train endings | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 까맣다 | to be black/dark | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 끊다 | to quit | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 나가다 | to go out | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 날씨 | weather | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 내년 | next year | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 내일 | tomorrow | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 너무 | too (much)/ever so much | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 노래 | song | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 농구 | basketball | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 느리다 | to be slow | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 늦게 | late | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 늦다 | to be late | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 다운로드 | download | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 다음 | next | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 달 | month | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 담배 | cigarette | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 도서관 | library | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 돈 | money | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 돌아오다 | to return/to come back | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 듣다 | to take (a class)/to listen | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 들르다 | to stop by | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 등산 | mountaineering | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 마시다 | to drink | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 만나다 | to meet | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 만들다 | to make | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 많다 | to be many/to be much | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 많이 | a lot | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 매다 | to wear (a tie) | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 매일 | everyday | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 머리 | hair (from a head)/head | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 먹다 | to eat | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 멀다 | to be far | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 모자라다 | to be short of | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 받다 | to receive | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 배우다 | to learn | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 보관하다 | to keep/to take custody of | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 보다 | to see/to read/to watch | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 봄 | spring | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 부르다 | to sing/to call out | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 불편하다 | to be inconvenient/to be uncomfortable | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 비 | rain 비 | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 싸다 | to be expensive | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 빨래 | laundry/washing (clothes) | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 사다 | to buy | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 사람 | person/people | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 살을 빼다 | to lose weight | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 살다 | to live | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 상담하다 | to consult | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 새 | new | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 생일 | birthday | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 선물 | gift/present | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 선생님 | teacher | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 손 | hand | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 수업 | class/course | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 수영 | swimming | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 시간 | time/hour | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 시험에 떨어지다 | to fail a test | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 시험을 보다 | to take a test | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 신문 | newspaper | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 심심하다 | to be bored | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 씻다 | to wash | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 아버지 | father | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 아침 | morning/breakfast | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 어리다 | to be juvenile/to be childish | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 연습하다 | to practice | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 열심히 | earnestly | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 영화 | movie | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 예약하다 | to reserve | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 오전 | a.m. | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 옷 | clothes | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 요가 | yoga | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 요리하다 | to cook | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 운동하다 | to exercise | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 운전하다 | to drive | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 음식 | food | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 의과 대학 | medical college | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 의논하다 | to consult | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 이기다 | to win | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 이사하다 | to move into/to change one’s residence | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 이용하다 | to use | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 일하다 | to work | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 잃다 | to lose | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 자르다 | to cut off | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 자다 | to sleep | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 작다 | to be small | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 잠 | sleeping endings | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 재미없다 | to be uninteresting | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 저녁 | dinner/evening | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 전공 | major | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 전화하다 | to make a phone call | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 점심 | lunch | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 정비소 | repair shop | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 정하다 | to decide | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 조금 | little | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 주다 | to give | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 주말 | weekend | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 준비하다 | to prepare | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 지갑 | wallet | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 지하철 | subway | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 진학하다 | to go on to next stage of education | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 집 | house | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 차 | car | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 찾다 | to look for/to seek for | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 출근하다 | to leave home for work | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 춥다 | to be cold | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 충분히 | sufficiently | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 취소되다 | to be canceled | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 치다 | to play (tennis/golf/piano)/to hit | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 친구 | friend | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 침대 | bed | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 키 | height | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 타다 | to ride | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 토요일 | Saturday | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 팔다 | to sell | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 표 | ticket | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 한국어 | the Korean language | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 학기 | semester | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 학교 | school | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 혼자 | alone | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |
| 화장 | makeup | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 23's own "Key vocabulary for exercises" list. |

### Unit 24 — Direct and indirect quotation (Key vocabulary for exercises, p. 215-227)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가다 | to go | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 같이 | together | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 계절 | season | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 공부하다 | to study | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 그만두다 | to quit/to stop (doing) | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 금요일 | Friday | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 끝 | an end/the tip | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 나중 | next time | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 내려오다 | to come down | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 내리다 | to get off/to come down | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 내일 | tomorrow | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 놀다 | to play | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 다시 | again | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 돌아가다 | to go back | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 돕다 | to help | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 들르다 | to stop by | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 따라오다 | to follow | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 마시다 | to drink | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 만나다 | to meet | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 만들다 | to make | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 맵다 | to be spicy | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 먹다 | to eat | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 밤 | night | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 보다 | to see/to watch/to read | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 빨래 | laundry | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 빨리 | fast/immediately | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 소나기 | a passing rain/shower | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 수업 | class | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 시간 | time/hour | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 시작하다 | to begin | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 열쇠 | keys | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 열심히 | earnestly/enthusiastically/hard | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 영화 | movie | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 오늘 | today | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 오르다 | to climb/to go up | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 오후 | p.m. | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 우유 | milk | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 이따 | after a while | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 일어나다 | to get up | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 일찍 | early | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 잘 | well/expertly | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 저녁 | dinner/evening | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 전화하다 | to make a phone call | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 정말 | really | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 제발 | please/for heaven’s sake | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 주말 | weekend | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 지내다 | to spend (time)/to get along | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 직장 | one’s place of work | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 집 | house | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 집세 | house rent | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 찌개 | pot stew | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 찾다 | to look for/to seek for | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 친구 | friends | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 타다 | to ride (a train/car/bus/airplane) | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 한국어 | the Korean language | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |
| 화내다 | to get angry | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | From Unit 24's own "Key vocabulary for exercises" list. |

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `../../00_Reference_Extraction_Spec.md`. All example
sentences quoted in the Grammar points section above are short (single-sentence) illustrative
examples selected from the book's own larger example sets, not verbatim reproduction of its
exercises or drill content.
