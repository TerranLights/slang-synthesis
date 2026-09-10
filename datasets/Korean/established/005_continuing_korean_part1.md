# Korean — Established Vocabulary/Grammar: *Continuing Korean*, Lessons 16–22 (Part 1)

**Source:** `07.Continuing Korean.pdf` (source_reference/languages/Korean/), PDF pages 1–150 of 451
(clean text layer, confirmed — `pdftotext -layout` produced clean, directly usable Korean and
English text despite font-related `pdftotext` syntax warnings during extraction). This volume is
the third in a graded series after "Basic Korean" and "Intermediate Korean" — its own lesson
numbering continues from 16, confirming it picks up where the prior two volumes leave off rather
than restarting. No title page, author name, or publication year appears anywhere in this
page range (the scan's own page 1 begins mid-lesson, directly with Lesson 16's opening dialogue),
so **Attested Era is left as `—` throughout this file** rather than guessing a "contemporary
(published YYYY)" value the source doesn't actually support here.

**Page range covered:** PDF pages 1–150, corresponding to the book's own Lesson 16 (partial,
picking up mid-lesson) through Lesson 22 (dialogue + partial vocabulary only — Lesson 22's own
grammar notes fall past page 150 and are out of scope for this chunk). Concretely: Lesson 16
(pp. "16/1"–"16/27", finishing out its -고 form and infinitive+서 material), Lesson 17 (pp.
"17/28"–"17/52", infinitive-based compounds and the -기 nominalizer), Lesson 18 (pp. "18/53"–
end, obligation/permission patterns), Lesson 19 (modifiers and postmodifier patterns), Lesson 20
(a **pure pattern-review lesson** — see note below), Lesson 21 (the conditional -(으)면 system),
and Lesson 22 (dialogue + Reading Passage + vocabulary only, cut off mid-vocabulary list at the
page-150 boundary, before its own Lesson Notes section).

**Overlap-check note (sibling dispatch coordination):** at the time this file was written, the
sibling `established/` files for *Basic Korean* and *Intermediate Korean* had not yet landed
(the `established/` directory was empty except for this file), so no direct file-level overlap
check against their content was possible. Judging from internal cross-references in this book's
own text (e.g. explicit "as seen in Lesson Seven," "as seen in Lesson Nine," "you learned already
in Elementary Korean, Lesson Thirteen" callbacks to material clearly from an earlier volume),
this chunk's own content (Lessons 16–22) is new relative to what a Basic/Intermediate-level
volume would cover — the grammar here (compound-verb formation off the infinitive, modifier
clauses, the conditional system, postmodifier idioms) is advanced material building cumulatively
on earlier basics rather than re-teaching them. A later pass should re-verify this once the
sibling files exist.

**OCR/extraction quality note.** The scan's own running-header lesson labels are frequently OCR-
mangled in a way that is diagnostic rather than random: "Lesson Steen" = *Lesson Sixteen* (dropped
"six"), "Lesson iteen" = *Lesson Eighteen* (dropped "Nn"/"E"), "Lesson Twenty-o" = *Lesson
Twenty-one* (dropped "ne"). These are cosmetic (running headers only) and don't affect body text
reliability; lesson identity was cross-checked against each lesson's own internal grammar-section
numbering (e.g. "16.1", "17.1", "21.1"), which is unambiguous. One vocabulary sub-table (a chart
of verbs compatible with the -기 + 가 nominalizer pattern in Lesson 17, §17.6) rendered as
unrecoverable glyph soup in the raw extraction; the surrounding prose describing that chart
was still legible and is paraphrased below without the chart itself.

**Vision Reading Confidence:** `n/a` throughout — this source had a genuine, clean text layer for
this page range; no vision-reading was required.

See `../00_Reference_Extraction_Spec.md` for the full coverage rule and `../../00_Word_Concept_and_Morphological_Typology_Guide.md`
for the morpheme-breakdown convention used below (Korean is agglutinative — see this language's
own `00_Extraction_Checklist.md`).

---

## Register/Honorific Findings Summary

This chunk is unusually dense in explicit honorific/speech-level material — the following
recur as a throughline across Lessons 16–21 and are worth flagging up front for the mechanics
analysis phase:

- **Honorific stacking is productive and the book explicitly flags over-honorification.** §17.1
  documents up to six mathematically possible honorific/negative combinations of a single sensory
  verb compound (e.g. -고 싶어하시지 않으세요), several marked "not common," with the most
  fully-stacked form explicitly called "a bit too fancy for everyday use" by the text itself —
  a rare case of a grammar reference directly annotating a register judgment on a specific derived
  form rather than just presenting a paradigm.
- **Sensory/emotion verbs require a grammatical detour to talk about third parties' feelings**
  (§17.1): Korean does not allow directly stating what another person feels — 좋아요 "[I] like it"
  vs. 좋아해요 "[someone else] likes it" is a first/non-first-person grammatical distinction, not
  just a lexical one, and this asymmetry is itself honorifically marked (하세요 vs 해요).
- **Humble-register lexical suppletion**: 말씀(을) 드리- "tell someone (humble for 말하다)" (L16),
  뵙-/뵈- "humbly see or meet" with its own irregular conjugation (뵈도/뵈어도 not *뵈워도) (L18),
  찾아 뵈- "call on sb. esteemed" vs. plain 찾아 가- (L18) — humble-register verbs are a distinct
  lexical set, not just a suffix layered on plain verbs.
- **-거든요** (L16 §16.6) is explicitly framed by the text as a *politeness strategy* ("grease on
  the skids") rather than a purely grammatical/semantic marker — it exists to keep conversation
  moving and invite a minimal acknowledging response, independent of its literal "because" meaning.
- **-고요/-서요** unfinished-sentence afterthoughts (§16.3) are politeness-register-bound: the
  polite particle 요 is added specifically because the speaker is in Polite Style with their
  interlocutor; the construction doesn't exist independent of register level.
- Honorific bases recur systematically across every new ending introduced in this chunk (조건형
  -(으)시면, 의도형 -(으)시려고, 과거체 -셨- + -고, 회고체 -시던, etc.) — honorification is a
  productive, endpoint-general feature of the verb-base system in this language, not a closed set
  of frozen honorific words.

---

## Lesson 16 (pp. "16/1"–"16/27")

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 거의 | nearly, almost | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | 거의 다 왔어요 "we're almost there." |
| 드디어 | finally, at last | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 또한 | moreover, furthermore | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 어서 | right away, quickly | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | Limited to commands/suggestions. |
| 오래 | for a long time | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 오래간만에 | for the first time in a long while | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | 오래간만 (a long interval) + -에 (locative particle). |
| 오랫동안 | for a long time | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 이리 / 그리 / 저리 | this way / so, to that extent / that way | adverb (deictic triad) | core | — | — | — | — | grammar_reference | n/a | n/a | Three-way deictic set parallel to 이/그/저. |
| 하루종일 | all day long | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | 하루 (one day) + 종일 (all day). |
| 갈비 | ribs | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 김치 | kimchee | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 미용실 | beauty parlor | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 병원 | hospital | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 빨래(를) 하- | wash laundry | verbal noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 욕조 | bathtub | noun | core | — | — | — | — | grammar_reference | n/a | n/a | OCR rendered as "옥조" in raw extraction; corrected by context (bathroom vocabulary set). |
| 육교 | pedestrian overpass | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 컴퓨터 | computer | noun | core | — | — | — | — | grammar_reference | n/a | n/a | English loanword. |
| -후 / 그 후에 | afterwards, later | noun/adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 머리(를) 하- | do one's hair (women) | verbal noun | core | — | — | — | — | grammar_reference | n/a | n/a | See morpheme note below. |
| 머리(를) 자르- / 머리(를) 깎- | cut one's hair | verbal noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 면도(를) 하- | shave | verbal noun | core | — | — | — | — | grammar_reference | n/a | n/a | + 면도칼/칼 "razor," 면도크림 "shaving cream," 면도기 "electric shaver." |
| 목욕(을) 하- | bathe | verbal noun | core | — | — | — | — | grammar_reference | n/a | n/a | + 목욕탕 "public bath." |
| 세수(를) 하- | wash face | verbal noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 이발(을) 하- | get a haircut (usually men) | verbal noun | core | — | — | — | — | grammar_reference | n/a | n/a | + 이발소 "barbershop," 이발사 "barber." |
| 파마(를) 하- | get a perm | verbal noun | core | — | — | — | — | grammar_reference | n/a | n/a | From English "perm(anent)." |
| 화장(을) 하- | put on makeup | verbal noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 강의(를) 하- | give a lecture (in a series) | verbal noun | core | — | — | — | — | grammar_reference | n/a | n/a | Contrasted with 강연 "a special lecture." |
| 말씀(을) 드리- | tell someone (humble) | verb | honorific | — | — | — | — | grammar_reference | n/a | n/a | Humble suppletive form of 말(을) 하-. |
| 설명(을) 하- | explain | verbal noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 약속(을) 하- | make an appointment, promise | verbal noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 식사(를) 하- | eat a meal | verbal noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 연습(을) 하- | practice | verbal noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 운전(을) 하- | drive | verbal noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 위험하- | be dangerous | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 준비(를) 하- | prepare | verbal noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 갈아타- | change (transport) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | 갈- (change) + 아 (infinitive linker) + 타- (ride). |
| 감- | wash (hair) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 건너- | cross | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 나누- | share, divide | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 낳- | give birth to | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 놓치- | miss (bus, plane) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 모으- | gather, collect | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 빌리- | borrow / rent | verb | core | — | — | — | — | grammar_reference | n/a | n/a | Same verb covers both "borrow" (한테) and "rent (a car)." |
| 씻- | wash | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 어기- | break (a promise) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | Antonym of 지키- below. |
| 지키- | keep (a promise), abide by | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 게으르- | be lazy | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 귀찮- | be a nuisance, annoying | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 기쁘- | be happy, content | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 뜨겁- | be hot to the touch | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 뚱뚱하- | be fat, chubby | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 마르- | dry up; get dry | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | 목(이) 마르- "be thirsty" (마르- + throat). |
| 배(가) 고프- | be hungry | descriptive verb (idiom) | core | — | — | — | — | grammar_reference | n/a | n/a | 배가 고파서 죽겠어요 "so hungry I could die" — see §16.4. |
| 부지런하- | be hard-working, diligent | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 속(이) 상하- | be distressing, feel distressed | descriptive verb (idiom) | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 슬프- | feel sad, sorrowful | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 시원하- | be refreshing, feel relieved | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 차갑- | be cold to the touch | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 막히- | get/be blocked, congested | intransitive verb | core | — | — | — | — | grammar_reference | n/a | n/a | 길이 많이 막혔어요 "the roads are congested." |
| 울- | cry, weep | intransitive verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 웃- | smile, laugh | intransitive verb | core | — | — | — | — | grammar_reference | n/a | n/a | |

> **머리(를) 하-** = 머리 (hair, noun) + (를) (object particle) + 하- (do) — a "verbal noun +
> 하-" light-verb construction, the single most productive word-formation pattern in this whole
> vocabulary set (강의(를) 하-, 세수(를) 하-, 준비(를) 하-, 등 all follow the same template):
> a Sino-Korean or native noun paired with the semantically bleached verb 하- "do," carrying all
> of the actual tense/mood/honorific inflection while the noun stays invariant. This is the
> single highest-yield agglutinative/analytic pattern to track for later mechanics analysis, since
> it is exactly the kind of "already-productive standard-language machinery" the typology guide
> warns must be distinguished from slang-specific morphological play.

### Grammar points

**16.1 — Verbs: the -고 form.** A one-shape (invariant) connective ending, attachable to plain,
past, or honorific bases, meaning "and" (simultaneous) or "and then" (sequential). Regular
consonant-cluster pronunciation rules apply at the junction (tensification after certain
consonant classes, aspiration after ㅎ-final bases, etc. — the book gives an extensive table of
these). L-extending bases (파-ㄹ- "sell") take -고 on their extended form (팔고). Negated by
attaching -고 to either the long negative (-지 않고/못하고) or short negative (안/못 + verb + 고);
a command/suggestion negative uses -지 말고 "don't ... instead."

**16.2 — Uses of the infinitive (-아/-어), part I: with the particle 서.** Infinitive + (optional)
서 has two distinct readings depending on context: (a) cause-and-result ("because ..., ..."), and
(b) a tighter purpose-and-sequence reading typically with motion verbs ("[did], so as to ...").
The book contrasts this explicitly against the -고 form: -고 links two loosely-related actions,
while -어서 asserts a causal/purposive link, and the two are not freely interchangeable even where
English "and" would cover both. §16.2.2.3 notes the copula takes a special -이라서 variant (more
colloquial than predictable -이어서). §16.2.2.4 contrasts -어서 (assertion of cause) against the
previously-learned -(으)니까 (a "discovery"/argumentation reading, more conversationally
involving) — a subtle two-way distinction in how Korean expresses causal reasoning that this book
treats as a genuinely new refinement over the plain -어서/-(으)니까 pairing.

**16.3 — Unfinished sentences/afterthoughts with -서요 and -고요.** In natural (unplanned) speech,
a speaker can blurt the main clause first and tack on the causal/coordinate clause afterward as an
afterthought, re-adding the polite particle 요 to it as if it were its own sentence. Marked as a
colloquial, register-bound pattern (see Register Findings above).

**16.4 — Descriptive verb + -어서 죽겠어요: "so ... I could die."** A vivid colloquial
intensifier: infinitive + 서 + 죽겠어요 ("I think I'm going to die") built onto a descriptive/
sensation verb, e.g. 배가 고파서 죽겠어요 "I'm starving."

**16.5 — NOUN-에 대해서 / NOUN-에 관해서: "about, concerning."** Near-synonymous postpositional
phrases; 에 관해서 is marked as more formal/bookish than 에 대해서.

**16.6 — -거든요: "..., you see?"** A one-shape ending (attaches most naturally to plain/past
bases) offering a follow-up rationale for something just said or implied, functioning primarily as
a politeness/conversation-management device (see Register Findings above) rather than a purely
propositional connective; typically carries rising, response-inviting intonation.

---

## Lesson 17 (pp. "17/28"–"17/52")

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 난방 장치 / 냉방 장치 | heating / air-conditioning | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 독방 | single room | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 발코니 | balcony | noun | core | — | — | — | — | grammar_reference | n/a | n/a | English loanword. |
| 숙박(을) 하- / 숙박부 | lodge / lodging registration form | verbal noun / noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 여행(을) 하- | travel | verbal noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 열쇠 / (차)키 | key / (car) key | noun | core | — | — | — | — | grammar_reference | n/a | n/a | Native vs. loanword pair for the same referent class. |
| 요금 | fee, fare | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 욕실 | bathroom (with a bath) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 유럽 / 유럽공동체 | Europe / the European Community | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 전경 | the view | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 체크인(을) 하- | check in | verbal noun | core | — | — | — | — | grammar_reference | n/a | n/a | English loanword. |
| 할인(을) 해 주- / 할인(을) 받- | give a discount / get a discount | verb | core | — | — | — | — | grammar_reference | n/a | n/a | Benefactive 주- vs. receptive 받- pairing on the same noun 할인. |
| 휴가 | holiday, leave from work | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 삼계탕 | Korean ginseng chicken soup | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 서비스 | service; something free/unexpected | noun | core | — | — | — | — | grammar_reference | n/a | n/a | English loanword with an extended local sense ("something extra thrown in"). |
| 육개장 | spicy chopped beef soup | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 한턱(을) 내- | treat, stand treat | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 결혼식 / 결혼식장 | wedding ceremony / venue | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 신랑 / 신부 | groom / bride | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 네거리 | crossroads, intersection | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 대답(을) 하- | answer, respond | verbal noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 비서 | secretary | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 선약 | a prior appointment/engagement | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 성명 | full name (official forms) | noun | core.formal | — | — | — | — | grammar_reference | n/a | n/a | Marked as used specifically on official forms. |
| 소식 | news, word (of somebody) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 시계 | watch, clock | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 얼굴 | face | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 우표 | postage stamp | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 인사 | greeting, formal hello/goodbye | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 정신(이) 없- | be preoccupied, overwhelmed | descriptive verb (idiom) | core | — | — | — | — | grammar_reference | n/a | n/a | 정신없이 "in a daze, absorbed totally" (adverbial). |
| 키(가) 크- | be tall | descriptive verb (idiom) | core | — | — | — | — | grammar_reference | n/a | n/a | 키 "height" as subject-marked noun + 크- "be big." |
| 태도 | attitude | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 기입(을) 하- | fill in (a form) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 다듬- | trim, spruce up | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 돕- | help | verb | core | — | — | — | — | grammar_reference | n/a | n/a | ㅂ-irregular (도와 드릴까요?). |
| 대접(을) 하- | treat somebody (to a meal) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 바르- | apply, smear it | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 보이- | show it | verb | core | — | — | — | — | grammar_reference | n/a | n/a | Causative of 보- "see." |
| 빌려 주- | lend | verb | core | — | — | — | — | grammar_reference | n/a | n/a | 빌리- (borrow) + 어 + 주- (benefactive) compound — distinct headword from plain 빌리-. |
| 세우- | bring to a stop | verb | core | — | — | — | — | grammar_reference | n/a | n/a | Causative of 서- "stand/stop." |
| 연애(를) 하- | fall in love, date | verbal noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 정하- | settle upon, decide | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 포함(을) 하- / 포함(이) 되- | include / be included | verb | core | — | — | — | — | grammar_reference | n/a | n/a | Active/passive-like 하-/되- pairing on the same Sino-Korean noun. |
| 깨- / 깨우- | wake up (intr.) / wake sb up (tr.) | verb pair | core | — | — | — | — | grammar_reference | n/a | n/a | Related transitive-intransitive pair. |
| 나- / 내- | exit, appear / hand in, turn in | verb pair | core | — | — | — | — | grammar_reference | n/a | n/a | 해가 났어요 "the sun's come out." |
| 내리- | get off (vehicle); let sb off | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 궁금하- | be/feel curious | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 부끄럽- | feel embarrassed, ashamed | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | ㅂ-irregular. |
| 부럽- | be envious | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | ㅂ-irregular; see -어해요 compound below (부러워해요). |
| 섭섭하- | feel sad/wistful (esp. about a departure) | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 아름답- | be beautiful | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | ㅂ-irregular. |
| 지루하- | be boring, tedious | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 낙제(를) 하- | fail, flunk | verbal noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 닫히- | get closed/shut | intransitive verb | core | — | — | — | — | grammar_reference | n/a | n/a | Passive counterpart of 닫- "close (tr.)." |
| 돌- | turn, spin, go around | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 열리- | open, be opened | intransitive verb | core | — | — | — | — | grammar_reference | n/a | n/a | Passive counterpart of 열- "open (tr.)." |
| 대단히 / 상당히 / 특히 | very / quite / especially | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 모든 NOUN | all NOUNs | determiner | core | — | — | — | — | grammar_reference | n/a | n/a | |
| NOUN 없이 | without NOUN | adverbial particle | core | — | — | — | — | grammar_reference | n/a | n/a | |
| -짜리 | "worth of" (denomination modifier) | bound suffix | core | — | — | — | — | grammar_reference | n/a | n/a | 3살짜리 아이 "a 3-year-old child." |
| -호 | number (rooms, journal issues) | bound suffix | core | — | — | — | — | grammar_reference | n/a | n/a | Attaches to Sino-Korean numerals. |

> **부러워요 → 부러워해요** = 부럽- (be envious, descriptive base, ㅂ→우 before vowel) + -어요
> (1st/2nd-person present) vs. 부럽- + -어 (infinitive) + 하- (does) + -요 — the productive
> descriptive→processive compounding pattern that is the actual content of Grammar §17.1 below;
> included here as the clearest single worked example of that whole mechanism.

### Grammar points

**17.1 — Uses of the infinitive III: turning descriptive verbs into processive verbs with -어
해요.** Korean grammar does not permit directly asserting a third party's internal emotional
state the way it permits asserting one's own; a closed set of "sensory" descriptive verbs
(좋다, 싫다, 싶다, 기쁘다, 고맙다, 부럽다, etc.) combine with 해요 to externalize the emotion
and convert the verb from descriptive to processive, at which point it also becomes transitive
(takes 을/를). First/second-person 좋아요 "[I] like it" vs. third-person 좋아해요 "[s/he] likes
it" is the paradigm case. Honorification and negation are discussed at length, including the
explicit "too fancy for everyday use" flag on maximal double-honorific stacking (see Register
Findings above).

**17.2 — Uses of the infinitive IV: compound verbs.** General pattern: infinitive + auxiliary verb,
where the auxiliary (not the main verb) carries all tense/polarity/mood marking.
- **17.2.1** Directional compounds with 가- "go" / 오- "come" (돌아가다/돌아오다, 들어가다/들어오다,
  나가다/나오다, 걸어가다/걸어오다, 올라가다/올라오다, 내려가다/내려오다) — a closed, highly
  productive template pairing a manner/path verb with a deictic-direction auxiliary.
- **17.2.2** Resultant states with 있- : infinitive + 있어요 marks a persisting state resulting
  from a prior action (앉아 있어요 "is seated," 열려 있어요 "[door] is open"), distinct from -고
  있어요 (in-progress action) — except for wearing-verbs, which are genuinely ambiguous between
  "is wearing" and "is putting on" under -고 있어요.

**17.3 — The exploratory pattern in -어 보-.** Infinitive + 보- ("tries doing [to see]"), distinct
from an attempt-reading — it means sampling an action to see how it turns out. 물어보- "ask (and
see)" is cited as having become effectively lexicalized as a single unit.

**17.4 — Doing favors with 주- / 드려요.** Infinitive + 주- (benefactive, "does X for [someone]") /
드려요 (honorific benefactive, for an esteemed recipient); the beneficiary, if named, takes 한테/
에게 or its honorific form 께.

**17.5 — Nominalizer form -기.** A one-shape ending (same attachment rules as -고) converting a
verb/clause into a noun ("the act of doing," "the state of being"), usable with particles, as a
noun modifier, in absolute/adverbial position, or (rarely) before the copula. Demonstrated
converting a full clause (여행을 하기) into an embedded direct object of a larger sentence.

**17.6 — Other nounlike uses of -기 forms.** -기 forms function as subject/object with a
grammatically restricted class of predicates (쉽다, 어렵다, 재미있다, 좋다, 싫다, etc. — mostly the
same descriptive/sensory verbs from §17.1); the book explicitly warns this is *not* freely
productive (*이 김치는 먹기가 너무 매워요 is ungrammatical) and that new combinations should not be
assumed without native confirmation — a rare explicit grammaticality-boundary flag.

**17.7 — Plain base + -기 시작하-: "begin to..."** — 기 nominalizer + 시작해요 "begins"; for
adjectives, the same meaning requires first converting via -어지- (§18.4) before 시작하- can apply.

**17.8 — Any base + -기 때문에: "because..."** — a stronger/more formal causal connective than -어서,
usable on plain, past, or (rarely) future bases; also combines with 너무 ADJ to render "so ADJ
that."

**17.9 — Plain base + -기 전에: "before..."** — the -기 form is tense-invariant here; actual tense
comes entirely from the sentence-final verb, regardless of whether the English gloss is
past/present/future "before."

---

## Lesson 18 (pp. "18/53"–end)

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 당장 / 지금 당장 | immediately, straight away | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 따로 / 따로 따로 | separately / each separately | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | Reduplicated form intensifies distributivity. |
| 몹시 | very, awfully | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 아무리 [...-어도] | however much [one VERBs] | adverb (correlative) | core | — | — | — | — | grammar_reference | n/a | n/a | Obligatorily co-occurs with -어도 (§18.2.1). |
| 유창하게 | fluently | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 자연스럽게 | naturally, freely | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 점점 | gradually, by degrees | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 제대로 | properly, as it should be | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 즐겁게 | enjoyably, happily | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| -과 (lesson) | lesson (numbered) | bound noun | core | — | — | — | — | grammar_reference | n/a | n/a | 제1과 "Lesson One" — see 제- ordinalizer below. |
| -과 (department) | department | bound noun | core | — | — | — | — | grammar_reference | n/a | n/a | Homophonous bound noun, distinct sense from "lesson." |
| 과장(님) | department head, chairman | noun | core.formal | — | — | — | — | grammar_reference | n/a | n/a | |
| 단어 | word, vocabulary item | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 동창 / 동기동창 / 동창회 | classmate / same-year classmate / alumni society | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 문법 | grammar | noun | core | — | — | — | — | grammar_reference | n/a | n/a | Pronounced [뭄뻡]. |
| 사전 / 한영사전 / 영한사전 | dictionary / Korean-English / English-Korean | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 동양 / 동양학 / 동양학과 | East Asia / East Asian Studies / that department | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 서양 | the West, Western | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 선배 / 후배 | senior / junior (from school) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | Culturally load-bearing seniority pair, no direct English equivalent. |
| 한자 / 한자어 | Chinese character / Sino-Korean word | noun | core | — | — | — | — | grammar_reference | n/a | n/a | Pronounced [한짜]/[한짜어]. |
| 거리 / 길거리 | street / main thoroughfare | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 공항 | airport | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 기름 / 기름(을) 넣- | oil, gas / get gas | noun / verb | core | — | — | — | — | grammar_reference | n/a | n/a | More colloquial than 휘발유 below. |
| 마일 / 마일수 | mile / mileage | noun | core | — | — | — | — | grammar_reference | n/a | n/a | 마일 + 수 (number/count). |
| 면허증 / 운전면허증 | license / driver's license | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 보증금 | deposit | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 보험 / 보험료 / 보험(을) 들- | insurance / insurance fee / take out insurance | noun/verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 서류 | document | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 설명서 | brochure, explanatory pamphlet | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 주유소 | gas station | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 택시요금 | taxi fare | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 휘발유 | gasoline, petrol | noun | core | — | — | — | — | grammar_reference | n/a | n/a | More formal/technical register than colloquial 기름. |
| 기타 / 기타(를) 치- | guitar / play the guitar | noun/verb | core | — | — | — | — | grammar_reference | n/a | n/a | English loanword ("guitar"). |
| 모임 | gathering, meeting | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 소용(이) 없- | be useless | descriptive verb (idiom) | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 약국 / 약사 | pharmacy / pharmacist | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 오해(를) 하- | misunderstand | verbal noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 이해(를) 하- / 이해(가) 가- | understand / it is understandable | verb (idiom pair) | core | — | — | — | — | grammar_reference | n/a | n/a | 이해가 안 가요 "I just don't get it." |
| 자리 | seat, place | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 제- | ordinalizer (makes "1st," "2nd," ...) | bound prefix | core | — | — | — | — | grammar_reference | n/a | n/a | Attaches to Sino-Korean numerals; see 제1과 above. |
| 하느님 (Catholic) / 하나님 (Protestant) | God | noun | core.religious | — | — | — | — | grammar_reference | n/a | n/a | Denominational register split on the same referent — rare explicitly-marked sectarian lexical variant. |
| 하늘 | heaven, sky | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 결정(을) 하- | decide | verbal noun | core | — | — | — | — | grammar_reference | n/a | n/a | See §18.8 below. |
| 그만하- / 그만두- | quit, stop doing it | verb | core | — | — | — | — | grammar_reference | n/a | n/a | Near-synonym pair. |
| 때리- | hit, strike | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 만나 뵈- | meet sb. esteemed (humble) | verb | honorific | — | — | — | — | grammar_reference | n/a | n/a | 만나- + 뵈- compound. |
| 바꾸- | exchange, trade | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 뵈- | humbly see/meet sb. esteemed | verb | honorific | — | — | — | — | grammar_reference | n/a | n/a | Irregular: 뵈도/뵈어도 (not *뵈워도), 뵐 (not *뵈울). 처음 뵙겠습니다 "how do you do." |
| 야단(을) 맞- / 야단(을) 치- | be scolded / scold | verb pair | core | — | — | — | — | grammar_reference | n/a | n/a | Receptive/agentive pairing on the same Sino-Korean noun. |
| 어울리- | spend time with, hang around with | verb | core | — | — | — | — | grammar_reference | n/a | n/a | Distinct sense from the "fit/match" sense seen in Lesson 21. |
| 외우- | memorize | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 찾아 가- / 찾아 오- / 찾아 뵈- | call on, visit / (humble, esteemed) | verb | core/honorific | — | — | — | — | grammar_reference | n/a | n/a | 찾아- (search-and-go) + directional/humble auxiliary. |
| 길- | be long | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 가난하- | be poor | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 따뜻하- | be warm | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 무덥- | be hot and muggy | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | ㅂ-irregular. |
| 복잡하- | be complicated; crowded | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | Dual sense: abstract complexity or physical crowding. |
| 불쌍하- | be pitiful | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 쌀쌀하- | be cool, chilly | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 유명하- | be famous | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 이르- | be early | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 조용하- | be quiet | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 짧- | be short | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 편찮으시- | be ill (honorific) | descriptive verb | honorific | — | — | — | — | grammar_reference | n/a | n/a | Suppletive honorific, not a regular -시- derivation of a plain base. |
| 흐리- | be cloudy, overcast | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 들르- | drop in, drop by | intransitive verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 없어지- | disappear | intransitive verb | core | — | — | — | — | grammar_reference | n/a | n/a | 없- (not exist) + -어지- inchoative (see §18.4). |

> **없어지-** = 없- (not.exist, descriptive base) + -어지- (inchoative "becomes/gets to be," §18.4)
> — a descriptive verb converted into a processive "becomes X" verb via the same -어지- machinery
> taught explicitly as Grammar §18.4 below; included here because it shows the pattern already
> lexicalized as a single dictionary headword rather than only a live productive construction.

### Grammar points

**18.1 — Uses of the infinitive V: with 야 ("only if").** Obligation ("have to," "must") is
expressed as infinitive + 야 + 해요/돼요, literally "only if [X] does it become [so]." The book
stresses that the *negative* of this pattern is not straightforward negation (see §18.2.4 for the
actual "doesn't have to" construction) — "must not" is a permission-denial pattern, not a negated
obligation pattern. Colloquial contractions 해야〔하〕지요 and 해야〔하〕겠어요 drop the 하-.

**18.2 — Uses of the infinitive VI: with 도 ("even though").**
- **18.2.1** Infinitive + 도 = "even though [X]" — stronger than -지만 "but, although."
- **18.2.2** The copula's special pre-도 form -이라도 ("even though it be...," "at least").
- **18.2.3** Asking/giving permission: infinitive + 도 + 돼요/좋아요/괜찮아요 = "is it all right if I
  ...?"
- **18.2.4** "Doesn't have to...": the negative permission construction (지 않아도 + 괜찮아요 etc.) is
  the actual negation of the §18.1 obligation pattern — not simple negation of -어야 해요.

**18.3 — Idiomatic -어도 expressions with max/min meaning.** 늦어도 "at the latest," 적어도
"at least" — descriptive-verb infinitive+도 forms that have drifted to a specialized idiomatic
sense distinct from their compositional "even though it's late/few" meaning.

**18.4 — Infinitive + 져요 (from 지-): "gets (to be) ADJ."** An inchoative auxiliary attaching to
descriptive-verb infinitives to derive a processive "becomes ADJ" verb (추워요 "is cold" →
추워져요 "gets cold"); the text explicitly flags a spelling rule that 지- must be written flush
against the infinitive with no space. This is the productive source of forms like 없어지-
(vocabulary above) once lexicalized.

**18.5 — Can/cannot: -(으)ㄹ 수 있-/없- [unlabeled in the source's own numbering, occurring
between §18.4 and §18.6].** Prospective modifier -(으)ㄹ + 수 (means, circumstance) + 있어요/없어요
= "can/cannot [VERB]." Uses the same prospective-modifier ㄹ already seen in the probable-future
and -(으)ㄹ래요 "wanna" patterns from earlier volumes. Corresponds to one sense of 못 negation.

**18.6 — Expressing "and" with -(으)며.** A two-shape "and" connective, explicitly marked as
literary/bookish and rare in spoken Korean (unlike colloquial -고); unlike -고, it carries only the
simple "and" meaning, never the "having done, then..." sequential reading.

**18.7 — NOUN(을) 통해(서): "through, by way of."** Built on the verb 통하- ("get through to,"
taught in an earlier volume); typically used with information-source nouns (media, institutions,
people).

**18.8 — Decides/agrees to do with -기로 하-.** -기 nominalizer + particle (으)로 + 해요/약속하다/
결정하다 = "decides/agrees/promises to do"; the -기 form itself stays tense-invariant, with all
tense marking on the following 하-/약속- /결정하-.

---

## Lesson 19 (grammar §19.1–19.8)

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 기억(을) 하- / 기억(이) 나- | remember | verbal noun (idiom pair) | core | — | — | — | — | grammar_reference | n/a | n/a | Agentive vs. spontaneous-recall framing of the same concept. |
| 벌- | earn (money) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 붓- | pour it | verb | core | — | — | — | — | grammar_reference | n/a | n/a | ㅅ-irregular. |
| 불- | blow (wind) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 뽑- | take out, extract | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 싸우- | quarrel, argue | verb | core | — | — | — | — | grammar_reference | n/a | n/a | Takes 하고 for the other party. |
| 짓- | build (house); make (rice) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | ㅅ-irregular. 미소(를) 짓- "smile" is a distinct idiom built on the same verb. |
| 지나가- | pass by | verb | core | — | — | — | — | grammar_reference | n/a | n/a | 지나- (pass) + 가- (go) compound. |
| 진찰(을) 하- | examine (medically) | verbal noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 원하- | want, desire | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 헤어지- | separate, break up (with) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | Takes 하고. |
| 귀엽- | be cute | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | ㅂ-irregular. |
| 깊- / 낮- / 높- | be deep / be low / be high, tall | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | 높다 not used of people's height (키가 커요 instead). |
| 느리- | be slow | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 더럽- | be filthy, dirty | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | ㅂ-irregular. |
| 상관(이) 없- | not to care, be of no concern | descriptive verb (idiom) | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 새롭- | be new | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | ㅂ-irregular; contrast pre-noun 새 (see 19.7). |
| 시끄럽- | be noisy | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | ㅂ-irregular. |
| 얕- | be shallow | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | Extends metaphorically to 얕은 지식 "shallow knowledge." |
| 인기(가) 있- | be popular | descriptive verb (idiom) | core | — | — | — | — | grammar_reference | n/a | n/a | Pronounced [인끼]. |
| 친하- | be close (with a friend) | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 틀리- | be different; be wrong | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | Book explicitly flags the "different" sense as "considered substandard but widespread" — a rare in-text prescriptive/descriptive usage note. |
| [-에] 걸리- | catch (a sickness) | intransitive verb | core | — | — | — | — | grammar_reference | n/a | n/a | 암에 걸렸어요 "caught cancer." |
| 나타나- | appear, show up | intransitive verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 낡- | get old (things) | intransitive verb | core | — | — | — | — | grammar_reference | n/a | n/a | Contrast 늙- below (people). |
| 남- | remain, be left over | intransitive verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 늙- | get old (people) | intransitive verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 서- | stop, come to a stop | intransitive verb | core | — | — | — | — | grammar_reference | n/a | n/a | Also "stand" elsewhere. |
| 연결(이) 되- / 연착(이) 되- / 지연(이) 되- | be connected / be delayed (transport) / be delayed (time/date) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | Three near-synonymous 되- passive-like constructions with distinct scopes. |
| 급행 / 완행 | express / stopping (train, bus) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | + 급행버스/급행열차, 완행버스/완행열차. |
| 도착시간 / 출발시간 | arrival time / departure time | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 무궁화 | Rose of Sharon (Korean nat'l flower) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | Train name (무궁화호), noted as the national flower. |
| 비둘기 | pigeon | noun | core | — | — | — | — | grammar_reference | n/a | n/a | Train name (비둘기호, the slowest class). |
| 새마을 | "New Village" (1960s rural dev't movement) | noun (proper) | core.historical | — | — | — | — | grammar_reference | n/a | n/a | Historically loaded name reused as a train class; flagged since the source itself glosses the historical referent. |
| 속도 | speed | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 식당차 | dining car | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 예약석 | reserved seat | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 통일 | unification | noun | core | — | — | — | — | grammar_reference | n/a | n/a | Train name (통일호); politically loaded term reused as a brand/class name. |
| 나이 드신 분 | old person (respectful) | noun phrase | honorific | — | — | — | — | grammar_reference | n/a | n/a | Contrast 늙은이 below. |
| 늙은이 | old person (somewhat disrespectful) | noun | derogatory-leaning | — | — | — | — | grammar_reference | n/a | n/a | Explicit register contrast pair with 나이 드신 분 — a genuine politeness-tier annotation from the source. |
| 애인 | steady girlfriend/boyfriend | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 어린 아이 / 어린이 | small child | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 젊은이 | young person, youth | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 중년 / 중년들 | middle age / middle-aged people | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 그런/이런/저런 NOUN | that/this/that sort of NOUN | determiner triad | core | — | — | — | — | grammar_reference | n/a | n/a | Deictic triad parallel to 이/그/저. |
| 헌 NOUN / 헌책방 | old/used NOUN / secondhand bookstore | determiner/noun | core | — | — | — | — | grammar_reference | n/a | n/a | See §19.7 — modifier form of 헐어요 "gets worn out," distinct from 낡은. |
| 로비 | lobby | noun | core | — | — | — | — | grammar_reference | n/a | n/a | English loanword. |
| 멋 / 멋지- / 멋(이) 있- | (good) taste, style / be stylish | noun/descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 무식하- / 유식하- | be ignorant / be learned | descriptive verb (antonym pair) | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 바람 / 바람(이) 불- | wind / the wind blows | noun/verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 병 / 병(이) 나- / 눈병 | sickness / get sick / eye disease | noun/verb | core | — | — | — | — | grammar_reference | n/a | n/a | 눈병 pronounced [눈뼝]. |
| 샴푸 | shampoo | noun | core | — | — | — | — | grammar_reference | n/a | n/a | English loanword. |
| 생각 / 생각(이) 나- | thought / it comes to mind | noun/verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 시절 / 학생시절 | era, a time in the past / student days | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 암 | cancer | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 옛날 | old days, in the past | noun | core | — | — | — | — | grammar_reference | n/a | n/a | 옛날 옛날에 "once upon a time." |
| 오페라 | opera | noun | core | — | — | — | — | grammar_reference | n/a | n/a | English loanword. |
| 유행 / 유행하- / 유행이- | fashion, vogue / be in vogue | noun/verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 작가 | writer, author | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 지식 | knowledge | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| NOUN 중(에서) | among NOUNs | postposition | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 최근 / 최근에 / 최근 것 | recent / recently / the latest thing | noun/adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 팝콘 | popcorn | noun | core | — | — | — | — | grammar_reference | n/a | n/a | English loanword. |
| 훨씬 | much (...-er), by far | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | Intensifies comparatives with 보다 (§19.6). |

> **부러워해요** (recap from L17) and the following newly-attested modifier chain both illustrate
> the same underlying two-tier modifier system taught as Grammar §19.1–19.2 below:
> **읽는 사람** = 읽- (read, processive base) + -는 (processive/non-past modifier) + 사람 (person)
> = "the person who is reading," vs. **읽은 사람** = 읽- + -은 (past/simple modifier) + 사람 = "the
> person who read/has read." The same base takes structurally different modifier suffixes
> depending on whether present or past reference is intended — the single most load-bearing
> agglutinative distinction introduced in this lesson.

### Grammar points

**19.1 — The -(으)ㄴ modifier.** A two-shape ending (은 after consonants, ㄴ after vowels;
L-extending bases use their unextended form) that converts a full clause into a prenominal
modifier. With descriptive verbs/copula it has a simple present/equative sense ("that is ADJ/
NOUN"); with processive verbs it carries an inherent *past* sense ("that did/has done") —
consequently this modifier can never attach to an already-past base (no *썼은 편지).

**19.2 — The processive modifier -는.** A one-shape ending, used only with processive verbs
(never descriptive verbs), marking present/ongoing reference ("that is VERBing"). 있다/없다
straddle both classes but pattern with processive verbs for this modifier. Sino-Korean verbal
nouns + 해요 switch modifier behavior depending on whether the verbal noun itself is descriptive
(한 only) or processive (both 하는 and 한 available).

**19.3 — Modifier clauses generally.** Korean modifier clauses always precede the modified noun
(the reverse of English relative-clause order for verbs); the modified noun can correspond to the
underlying subject, object, or an oblique (location/time) of the source sentence, disambiguated by
context and particles.

**19.4 — Postmodifier patterns.** Special nouns placed after a modifier create new grammatical
patterns:
- **19.4.1** 길 ("road/way") after the processive modifier of a motion verb = "on the way to...".
- **19.4.2** 일/적 ("event, experience") + 있-/없- after modifiers give a four-way paradigm: past
  modifier + 있어요 = "has ever done"; past modifier + 없어요 = "has never done"; non-past (-는)
  modifier + 있어요 = "sometimes/occasionally does"; non-past modifier + 없어요 = "never does." This
  pattern is noted as typically co-occurring with the exploratory -어 보- pattern from §17.3.

**19.5 — The retrospective modifier -던.** A one-shape ending marking "that has/had been [doing
so-and-so]" — the modifier-form equivalent of -고 있었어요. Can also attach to a past base
(-었던) with, for some speakers, an added sense of temporal remoteness; the text notes a growing
tendency for -었던 to simply substitute for plain -(으)ㄴ.

**19.6 — The particle 보다.** "More than / rather than" — typically surfaces not next to its own
noun but as the modifier of a comparative elsewhere in the sentence (English -er/"more"); can be
followed by 도 for emphasis or 은/는 for extra contrast; 훨씬 intensifies to "far more...than."

**19.7 — Words for young and old.** A genuinely lexical (not just morphological) register system:
나이가 드셨어요/연세가 많으세요 (respectful, for old age) vs. blunt 늙었어요/늙은이 (disrespectful);
젊어요/젊은이 (young adult) vs. 어려요/어린이 (young child) as absolute (non-relative) age
descriptions, requiring a separate 나이 + 위/아래 + 보다 construction for *relative* age
comparison. Separately, "old" for *things* (not people) is 낡아요/낡은 or 헐어요/헌 (worn with
age/use), opposed by 새 (new, functions as a pre-noun rather than an ordinary descriptive verb —
"it is new" requires 새로워요, not *새요).

**19.8 — Modifiers with 것: "the fact of...ing."** Processive modifier -는 + 것 = "the fact/act of
doing so-and-so"; plain modifier -(으)ㄴ + 것 = the past equivalent. Functions as the object of
verbs like 봐요/알아요/들어요 ("sees/knows/hears that...") and, as subject of 쉬워요/어려워요/좋아요/
싫어요, is sometimes interchangeable with the -기 nominalizer from §17.5–17.6.

---

## Lesson 20 — Pattern Review (no new grammar)

Lesson 20 is explicitly structured by the book itself as a **consolidation/review lesson**: its
entire "Lesson Notes" section (numbered §20.1.1–20.1.26+) is a systematic re-walkthrough of every
pattern already introduced in Lessons 16–19 (the -고 form, infinitive+서, infinitive+해요,
compound verbs, -어 보-, -어 주-, -어서 죽겠어요, -에 대해서, -거든요, -기 때문에, -기 전에, -기
시작하-, -어야, -어도, -어져요, -(으)ㄹ 수 있-/없-, -(으)며, -기로 하-, 통해(서), both modifier
types, postmodifier clauses, 보다 comparisons, -던, and 것-modifier clauses), each restated with
one or two fresh example sentences and no new grammatical content. **No new grammar points or
distinct vocabulary items are extracted from Lesson 20** per the coverage rule's "skip repeated
drill content that doesn't introduce anything new" instruction — its own dialogue/vocabulary
sections belong to the following lesson boundary (the vocabulary that begins right after Lesson
20's exercises, at the "Lesson Twenty-o[ne]" / "Lesson Twenty-one" header, is Lesson 21's own
vocabulary and is tabulated under Lesson 21 below).

---

## Lesson 21 (grammar §21.1–21.9+)

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 계속(해서) / 계속하- | continuously / continue | adverb/verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 곧 | any moment now, at once | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 글피 | 3 days from now | adverb (temporal) | core | — | — | — | — | grammar_reference | n/a | n/a | Part of a fine-grained native Korean relative-day system (오늘/내일/모레/글피). |
| 덜 | less (opposite of 더) | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 매우 | very, exceedingly | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 뭐니뭐니 해도 | say what you like, whatever anyone says | adverbial idiom | colloquial | — | — | — | — | grammar_reference | n/a | n/a | Reduplicated 뭐 + quotative + concessive 해도. |
| 자꾸(만) | incessantly (often annoyingly) | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 잘못 (adv.) | by mistake, wrongly | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | Same form doubles as a noun "mistake" (below). |
| 직접 | directly, in person | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 감기 / 몸살감기(감기몸살) | a cold / severe exhaustion-cold | noun | core | — | — | — | — | grammar_reference | n/a | n/a | 감기에 걸렸어요 "caught a cold." |
| 몸살 / 몸살(이) 나- | general fatigue (overwork) | noun/verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 게으름뱅이 | lazybones | noun | colloquial | — | — | — | — | grammar_reference | n/a | n/a | Pejorative-leaning agentive noun on 게으르- (L16). |
| 거짓말 / 거짓말쟁이 | lie / liar | noun | core | — | — | — | — | grammar_reference | n/a | n/a | -쟁이 agentive/pejorative suffix. |
| 농담(을) 하- / 진담 | joke / something said seriously | noun/verb (antonym pair) | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 멋쟁이 | stylish person | noun | core | — | — | — | — | grammar_reference | n/a | n/a | 멋 (L19) + -쟁이. |
| 신사 / 신사 숙녀 여러분 | gentleman / ladies and gentlemen | noun | core.formal | — | — | — | — | grammar_reference | n/a | n/a | |
| 여러분 | all of you, y'all | pronoun | core | — | — | — | — | grammar_reference | n/a | n/a | Book explicitly notes it lacks the regional connotation of English "y'all." |
| 잘못 (noun) | a mistake, error | noun | core | — | — | — | — | grammar_reference | n/a | n/a | 잘못을 했어요. 용서하십시오 "I made a mistake, please forgive me." |
| 정치가 | politician | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 경치 | scenery | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 공해 | pollution | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 등산(을) 하-/가- | go hiking | verbal noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 매연 | exhaust fumes | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 설악산 | Mount Sŏrak | noun (proper) | core | — | — | — | — | grammar_reference | n/a | n/a | Recurring named referent across this lesson's dialogue and reading passage. |
| 연기 | smoke | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 과자 / 교과서 | biscuit/cookie / textbook | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 단추 / 단추를 잠그-/끼- | button, snap / do up | noun/verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 매년/매달/매주 | every year/month/week | adverb (distributive) | core | — | — | — | — | grammar_reference | n/a | n/a | 매- productive distributive prefix. |
| 모양 | shape, appearance, style | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 불어 | French language | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 사과(apology) / 사과(를) 합니다/드립니다 | apology / I apologize (plain/honorific) | noun/verb | core/honorific | — | — | — | — | grammar_reference | n/a | n/a | 드립니다 form used toward an esteemed addressee. |
| 사이즈 | size | noun | core | — | — | — | — | grammar_reference | n/a | n/a | English loanword. |
| 사탕 | sweets, candy | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 연휴 | a long weekend | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 오자 | typo, misprint | noun | core | — | — | — | — | grammar_reference | n/a | n/a | Pronounced [오짜]. |
| 중 (middle) | during, in the middle of | noun (bound) | core | — | — | — | — | grammar_reference | n/a | n/a | 수업 중 "during class," 회의 중 "in a meeting." |
| 필요 / 필요하- | need, necessity / be necessary | noun/verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 흠 | flaw, defect | noun | core | — | — | — | — | grammar_reference | n/a | n/a | Also used metaphorically of a person's character flaw. |
| 개- (clears up) | it clears up (weather) | intransitive verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 구름 / 끼- | cloud / (clouds/fog) form | noun/verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 선선하- | be cool, fresh | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 소나기 | cloudburst, shower | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 안개 | fog | noun | core | — | — | — | — | grammar_reference | n/a | n/a | 옅은/짙은 안개 "thin/thick fog" — reuses the 옅-/짙- color-depth pair below metaphorically. |
| 태풍 | typhoon | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 갈색/까만(색)/남색/노란(색)/녹색/밤색/보라색/분홍색/빨간(색)/오렌지색/자주색/주황색/파란(색)/푸른(색)/핑크색/하늘색/하얀(색)/회색/흰(색) | brown/black/navy/yellow/green/chestnut brown/purple/pink/red/orange/burgundy/orange/blue-green/blue-green/pink/sky blue/white/grey/white | color terms | core | — | — | — | — | grammar_reference | n/a | n/a | Full basic color-term set of this lesson; 파란/푸른 both cover the blue-green range without a hard boundary (파란 하늘 and 푸른 하늘 both attested for "blue sky"). |
| 색깔/색 | color | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 밤 (chestnut) | chestnut | noun | core | — | — | — | — | grammar_reference | n/a | n/a | Homograph of 밤 "night" — distinct lexeme, noted for disambiguation. |
| 가지고 있- | have, possess | verb (idiom) | core | — | — | — | — | grammar_reference | n/a | n/a | 가지- (hold) + -고 있- (resultant/ongoing state). |
| 당기- / 밀- | pull / push | verb (antonym pair) | core | — | — | — | — | grammar_reference | n/a | n/a | Door-sign imperatives: 당기시오/미시오. |
| 맞추- | order to specification, have made to order | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 배달(을) 하- / 배달부 | deliver / delivery man | verbal noun/noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 잠그- | fasten, lock | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 잡- | catch, grasp, take hold of | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 장(을) 보- | go shopping (for food) | verb (idiom) | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 재- | take measurements of | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 고단하- | be tired, weary | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 심하- | be severe, intense | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 옅- | be light (color) | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | Antonym of 짙- below. |
| 졸리- | be/feel sleepy | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | 졸려서 죽겠어요 "incredibly sleepy" — reuses the §16.4 -어서 죽겠어요 pattern. |
| 중요하- | be important | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 짙- | be deep, rich, dark (color) | descriptive verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 행복하- / 행복 | be happy (in life) / happiness | descriptive verb/noun | core | — | — | — | — | grammar_reference | n/a | n/a | This lesson's Reading Passage is titled 행복 "Happiness" and is a short reflective essay on what happiness requires. |
| 결석(을) 하- | be absent (from school) | verbal noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 마음에 들- | be to one's liking | verb (idiom) | core | — | — | — | — | grammar_reference | n/a | n/a | 마음 (mind/heart) + 에 + 들- (enters). |
| [...에] 어울리- | fit, match, go well with | intransitive verb | core | — | — | — | — | grammar_reference | n/a | n/a | Distinct sense from the "hang around with" 어울리- in Lesson 18 — same headword, two glossed senses across two lessons. |
| 졸- | doze | intransitive verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 그러-/그래요 | do so, do like that | pro-verb | core | — | — | — | — | grammar_reference | n/a | n/a | Referenced already in the Lesson 18 reading-passage notes as "you will learn more in Lesson Twenty-two" — confirms cross-lesson forward-reference structure in this book. |
| 그렇-/그래요 | be so, be that way | pro-adjective | core | — | — | — | — | grammar_reference | n/a | n/a | Distinct headword (descriptive) from processive 그러- above, both surfacing as 그래요 in the present tense — a genuine descriptive/processive homophone pair. |

> **가려면** = 가- (go) + -(으)려 (intentive, §21.6) + -면 (conditional, §21.1) — a fused
> combination meaning "if [one] intends to go," explicitly identified by the text as its own
> named pattern (§21.6's closing example) rather than just a chance stacking of two independently
> taught endings; in fast colloquial speech it further contracts toward -(으)ㄹ래면 by analogy with
> the -(으)ㄹ래요 "wanna" form.
>
> **거짓말쟁이** = 거짓말 (lie, noun) + -쟁이 (agentive/mildly pejorative person-suffix) — the same
> -쟁이 pattern recurs in 멋쟁이 (stylish person) and 게으름뱅이 uses the parallel but distinct
> -뱅이 suffix; both are productive person-naming suffixes worth tracking for later slang-formation
> analysis, since agentive/pejorative person-suffixation is a classic cross-linguistic slang
> mechanism and these are two native examples already active in the standard language.

### Grammar points

**21.1 — Conditional form -(으)면.** A two-shape ending (-으면 after consonants, -면 after vowels;
L-extending bases attach to the extended base). Honorific conditionals attach -(으)면 to the
honorific base (-(으)시면). A past conditional (-었으면) is also available, used for more
hypothetical/counterfactual framing (§21.3).

**21.2 — Uses of -(으)면 (1): if / when(ever).** The baseline conditional/temporal sense.

**21.3 — Uses of -(으)면 (2): hopes and wishes.**
- **-(으)면 좋겠어요** = "I hope/wish..." (literally "it would be good if...").
- **-(었)으면 얼마나 좋겠어요?** = a rhetorical "how wonderful it would be if...!," with the past
  conditional marking a more remote/unlikely hypothetical than the plain conditional.

**21.4 — Uses of -(으)면 (3): polite requests.**
- **-(으)면 고맙겠어요** = "I would be grateful if..." — an oblique, more courteous way of making a
  request than a direct imperative.
- **-어 주셨으면 합니다** = a stiffer, more formal register variant using the past conditional +
  합니다/해요 instead of 고맙겠어요, explicitly compared by the text to a European-language
  subjunctive-of-politeness (French *je voudrais*, etc.).

**21.5 — Other uses of the conditional: obligation and permission-denial.**
- **-지 않으면 안 돼요 / 안 하면 안 돼요** = double-negative obligation ("ought to," milder than -어야
  해요 but stronger than -으면 좋겠어요).
- **-(으)면 안 돼요** = single-negative denial of permission ("may not, must not") — the book flags
  that Koreans avoid the long negative 되지 않아요 here as too cumbersome.
A summary table in the source consolidates the full -(으)면 paradigm (if/when, hope/wish, polite
request, obligation, permission-denial) as one coherent system built off a single conditional
morpheme with varying auxiliary completions.

**21.6 — The intentive -(으)려(고): "intending to...".** A two-shape ending (processive bases
only — no descriptive-verb or copula form exists) usually followed by 하- or 그러- ("intends/
plans/is willing to..."). Has an expanded (-(으)려고 하-), simple (-(으)려 하-), and contracted
form (하렵니다 etc.) register; colloquial speech often doubles the ㄹ (할려고 for 하려고), and the
book notes this doubled form is the historical origin of the -(으)ㄹ래요 "wanna" pattern taught in
an earlier volume. Distinguished from the superficially similar purposive -(으)러 (motion-verb-
only, "in order to"). The combined form **-(으)려면** ("if one intends to...") fuses the intentive
with the conditional (see morpheme note above).

**21.7 [unlabeled continuation, folded into 21.6's closing discussion] — -(으)려면.** See morpheme
breakdown above; treated by the source as an extension of §21.6 rather than a separately numbered
section, but functionally a distinct fused pattern worth tracking on its own.

**21.8 — The adverb 좀.** Two related senses: "a little bit" and a scope-limiting "just, only"
(parallel to the particle 만 on nouns); pragmatically, 좀 also functions to soften a request or
command.

**21.9 — First realizations with -(는)군요!.** A two-shape exclamatory ending marking sudden/
first-time realization ("Oh, I see that...!," "Why, ...!"). Processive bases take -는군요 (built on
the processive modifier -는); descriptive bases, past bases, future bases, and 있-/없- take plain
-군요.

---

## Lesson 22 (dialogue + partial vocabulary only — grammar notes out of range)

Lesson 22's own grammar section falls past PDF page 150 and is **out of scope for this file**; it
will be covered by the next page-range chunk. Its dialogues, reading passage, and the portion of
its vocabulary list that falls within pp. 1–150 are captured here since they were fully legible
within this chunk's page range.

**Dialogue/reading passage note:** Lesson 22's two dialogues (Mr. Murphy's late-arrival apology to
his secretary and a Korean-teacher home visit) and its reading passage on a family day-trip both
make heavy use of the -면(서) simultaneity pattern (e.g. 커피를 마시면서 서류를 읽고 있습니다 "is
reading documents while drinking coffee") and the Imminent Elaboration ending -(으)ㄴ/는데요,
which the book's own dialogue notes twice explicitly flag as "you will learn more about this in a
later lesson" — both patterns are cross-referenced forward rather than taught in this chunk, and
are correctly left unexplained here per that same forward-reference structure.

### Vocabulary (partial — cut off mid-list at the page-150 boundary)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가만히 | quietly, still, cautiously | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 나중에 | later, afterward | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 마음껏 / 실컷 | to one's heart's content | adverb (near-synonym pair) | core | — | — | — | — | grammar_reference | n/a | n/a | 실컷 additionally implies "to the point of being sick of it." |
| 부지런히 | diligently | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | Adverbial form of 부지런하- (L16). |
| 어떤 때는 | sometimes | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 어쨌든 / 어차피 / 하여튼 | anyhow, in any case, at any rate | adverb (near-synonym set) | core | — | — | — | — | grammar_reference | n/a | n/a | Three near-interchangeable discourse adverbs glossed identically by the source — worth noting as a genuine near-synonym cluster. |
| 얼른 | quickly, at once | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 오히려 | rather, on the contrary | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 간 / 간(을) 보- | saltiness (of food) / check the seasoning | noun/verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 간장 | soy sauce | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 계란 / 달걀 | (chicken) egg | noun (near-synonym pair) | core | — | — | — | — | grammar_reference | n/a | n/a | Sino-Korean vs. native doublet for the same referent. |
| 고구마 | sweet potato | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 고추 | (red) pepper | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 만두국/감자국/떡국 | dumpling soup / potato soup / ricecake soup | noun (compounds) | core | — | — | — | — | grammar_reference | n/a | n/a | 만두국 pronounced [만두꾹]. |
| 껌 / 껌(을) 씹- | chewing gum / chew gum | noun/verb | core | — | — | — | — | grammar_reference | n/a | n/a | English loanword ("gum"). |
| 만두 / 찐만두 / 튀긴만두 / 야끼만두 / 물만두 | dumplings (plain/steamed/deep-fried/pan-fried/boiled) | noun (compound set) | core | — | — | — | — | grammar_reference | n/a | n/a | Full cooking-method modifier paradigm on one head noun. |
| 물고기 / 생선 | fish (live) / fish (as food) | noun (near-synonym pair) | core | — | — | — | — | grammar_reference | n/a | n/a | Living-referent vs. food-referent lexical split, parallel to English "cow"/"beef." |
| 소금 / 소금을 뿌리- | salt / sprinkle salt on | noun/verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 숟가락 / 젓가락 | spoon / chopsticks | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 찌개 / 찌개를 끓이- / 김치찌개 / 된장찌개 | stew / make a stew / kimchee stew / soybean-paste stew | noun/verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 포크 / 후추 | fork / (black) pepper | noun | core | — | — | — | — | grammar_reference | n/a | n/a | 포크 an English loanword. |
| 고향 | hometown | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 대기실 / 대합실 | waiting room / waiting room (station/terminal) | noun (near-synonym pair) | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 세상 / 세상에! | the world / "oh my, my goodness!" | noun/interjection | core | — | — | — | — | grammar_reference | n/a | n/a | Interjection sense flagged by the source as "used by women" — an explicit gendered-register annotation. |
| 슈퍼 | supermarket | noun | core | — | — | — | — | grammar_reference | n/a | n/a | Abbreviated loanword from 슈퍼마켓. |
| 응접실 / 접대실 | reception room (home) / reception room (office) | noun (near-synonym pair) | core | — | — | — | — | grammar_reference | n/a | n/a | Domain-restricted near-synonyms (private home vs. institutional office). |
| 공기 | air | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 교통 | traffic | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 기분전환 / 기분전환으로 | a change of mood / for a change of mood | noun/adverbial | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 보고서 / 보고(를) 하- | (written) report / report | noun/verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 섬유 | textiles | noun | core.technical | — | — | — | — | grammar_reference | n/a | n/a | |
| 소풍 / 소풍(을) 가- | school outing/picnic / go on one | noun/verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 수첩 | small notebook, memo-book | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 실수 / 실수(를) 하- | a mistake, blunder / make a mistake | noun/verb | core | — | — | — | — | grammar_reference | n/a | n/a | Near-synonym of 잘못 (L21) but distinct connotation (accidental blunder vs. moral fault). |
| 안색 | one's complexion | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 야유회 / 야유회(를) 가- | company outing, picnic / go on one | noun/verb | core | — | — | — | — | grammar_reference | n/a | n/a | Distinguished from 소풍 (school outing) by the same source. |
| -통 | counter for letters | bound counter | core | — | — | — | — | grammar_reference | n/a | n/a | 편지를 3통이나 썼어요-type usage seen in Lesson 18's dialogue. |
| 끄- | turn off, extinguish | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 끓이- | boil it, make (a stew) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | Causative-shaped counterpart of intransitive 끓- "boil (itself)." |
| 낮잠(을) 자- / 늦잠(을) 자- | take a nap / sleep in, oversleep | verb (idiom pair) | core | — | — | — | — | grammar_reference | n/a | n/a | Same head verb 자- "sleep," distinguished by 낮 "daytime" vs. 늦- "late" modifiers. |
| 무리(를) 하- | overdo it, work/play too hard | verbal noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 볶- / 볶음밥 | fry (in a pan) / fried rice | verb/noun | core | — | — | — | — | grammar_reference | n/a | n/a | OCR-degraded in the raw extraction (rendered as fragmentary glyphs); reconstructed from the surrounding gloss context and the well-known compound 볶음밥. |
| 빨- | wash (clothes), launder | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 뿌리- | sprinkle it | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 사진(을) 찍- | take photos | verbal noun | core | — | — | — | — | grammar_reference | n/a | n/a | List continues past the page-150 boundary; remaining entries belong to the next chunk. |

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — no bulk reproduction of vocabulary boxes, dialogue
blocks, or explanatory prose. See `../../00_Reference_Extraction_Spec.md`.
