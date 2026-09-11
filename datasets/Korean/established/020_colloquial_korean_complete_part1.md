# Korean — Established Vocabulary/Grammar: Colloquial Korean, Introduction + Lessons 1–11 (first half)

**Source:** In-Seok Kim, *Colloquial Korean* (Routledge, "The Colloquial Series," 2000), PDF pages
1–145 of 289 (printed pages i–x, 1–135, covering front matter + Introduction: Korean sounds and
Hangul (Units 1–6) + Lessons 1–11: Greetings; Introducing friends; In an office; Asking for
directions; Where are you going?; What is this?; Going out for lunch; Making an appointment;
Taking a taxi; Shopping; Weekend trip — the last through its two dialogues and full grammar-point
content only, see the boundary note below). This is the primary/full "Colloquial Korean" edition in
this project's source folder (the longer of two).

**Assigned range and a pre-existing sibling file found on inspection.** The dispatch specified PDF
pages 1–145; PDF page 145 (printed p. 135) falls mid-way through Lesson 11 (Lesson 11 runs printed
pp. 128–137, Lesson 12 "In the bank" begins printed p. 138 = PDF p. 148). Before extracting, this
dispatch checked for existing sibling files per the project's check-first duplicate-prevention
discipline and found `established/021_colloquial_korean_complete_part2.md` already exists, already
declares this file's own intended scope as "printed pages 1–135, Units 1–11 through the start of
Unit 11's exercises," and already contains a dedicated "Unit 11 tail (printed 136–137) — reading
passage + key words only" section. This file's Lesson 11 coverage was therefore capped at printed
p. 135 (its two dialogues + full grammar-point content) to match that pre-existing split exactly,
rather than re-extracting the reading passage — see Lesson 11's own boundary note below for detail.
Lesson 12 onward is `021`'s scope, not this file's.

**No text layer — vision-read throughout.** `pdftotext -f 1 -l 10` on this PDF returns zero output
(genuinely no text layer at all, confirmed empirically before starting, not assumed) — `pdffonts`
likewise reports no font objects for the sampled range. All content in this file, Korean and
English alike, was extracted by rendering PDF pages to PNG images (`pdftoppm`, 130–150dpi) and
reading them visually.

**Page-offset gotcha, verified empirically per this project's standing discipline (not assumed from
a fixed formula).** This scan is **one printed page per PDF image**, not a two-pages-per-spread
scan (verified by direct inspection of the Contents, Preface, and several lesson-opening pages).
The offset is **PDF_page = printed_page + 10** across the full assigned range — verified at four
widely separated points: printed p. v/vi/vii/viii (Contents/Preface) = PDF pp. 5/6/7/8 (roman-numeral
front matter, offset +0 against the numeral itself); printed p. 1 (Introduction title) = PDF p. 11;
printed p. 2 (Unit 1: Vowels) = PDF p. 12; printed p. 27 (Lesson 1 start) = PDF p. 37; printed p. 135
(Lesson 11, deep in its exercises) = PDF p. 145; printed p. 138 (Lesson 12 start) = PDF p. 148. No
drift was found anywhere in the range checked.

**Vision-reading confidence.** Every page inspected in this range is genuinely typeset, clean
print-quality textbook content — no scan artifacts, no ambiguous glyphs, and **no handwritten
marginalia found anywhere** in the pages read for this file. All Korean-language entries below are
marked Vision Reading Confidence `verified` unless individually flagged otherwise.

**Coverage note.** The Introduction chapter (Units 1–6: simple vowels, 9 basic consonants, batchim/
final-consonant neutralization, aspirated consonants, double (tensed) consonants, and combined
vowels/diphthongs) is a pure Hangul-alphabet phonics primer — letter shapes, stroke order, and
syllable-reading/writing drills with no distinct lexical content beyond isolated CV syllables and a
handful of illustrative single-letter "words" (강 "river," 눈 "eyes," 집 "house"). This close mirrors
`established/001_basic_korean_part1.md`'s treatment of Byon's equivalent Hangul-reading unit and
`established/016_active_korean_1.md`'s skip of its own Hangul unit — per the coverage rule, this is
represented by grammar-point summaries of the phonics system (especially the batchim neutralization
rule, useful for Korean's morphophonology) rather than an exhaustive per-syllable vocabulary table.
Each of Lessons 1–11's two dialogues, vocabulary lists, language points, and culture points are
extracted in full; repeated drill-exercise sentences that reuse already-captured vocabulary/grammar
are not individually transcribed, per the spec's coverage rule — only new vocabulary/grammar payload
introduced inside an exercise (if any) is captured.

**Non-redundant-supplement note.** This is the third *Colloquial*-style / from-scratch beginner
course extracted for Korean (after `established/016_active_korean_1.md` and the Wave-1 grammar
series). Given this dispatch's own scope (a large vision-read book), a full skim-first pass against
every sibling file was not performed; instead, standard beginner-grammar territory (topic/subject
particles, basic sentence types, the polite -세요 ending, personal pronouns) is captured in full
here since `Colloquial Korean` is independently authored with its own example sentences, its own
distinctive **다섯 sentence type inventory (declarative/interrogative/request/command/exclamation)**
framing (not phrased this way in the Byon or Active Korean series), and — most notably — extensive
**Culture point** boxes with concrete sociolinguistic content (Confucian basis of the honorific
system, the mechanics of Korean-style introductions, business-card exchange norms, taxi-hailing and
weekend-trip etiquette, etc.) that do not duplicate prior extractions.

---

## Grammar points — Introduction: Korean sounds and Hangul (Units 1–6, PDF pp. 11–36, printed pp. 1–26)

### Unit 1 — Simple vowels
Eight simple vowels (아, 어, 오, 우, 으, 이, 에, 애) are introduced with English approximations and
stroke-order writing drills. Vowel symbols are arranged top-to-bottom (오, 우, 으) or left-to-right
(아, 어, 이, 에, 애) around a zero consonant ㅇ placeholder — every vowel letter requires this empty
consonant when written standalone.

### Unit 2 — Nine (basic) consonants
그, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ (romanized by the source as "gi-yuk," "ni-un," "di-gut," "ri-ul,"
"mi-um," "bi-up," "si-os," "i-ung," "ji-us") are each introduced with a full CV syllable set against
the eight Unit 1 vowels, an English-approximation pronunciation guide per syllable, and a stroke-order
diagram. ㅇ is explicitly identified as an "empty consonant" that converts to a syllable-final "ng"
sound (as in English "ink") when it closes a syllable — the first mention of batchim (final-consonant)
behavior, expanded in Unit 3.

### Unit 3 — Batchim (syllable-final consonants) and neutralization
Presents the classic Korean batchim-neutralization system via four worked syllable-set examples,
without yet using the term "batchim" itself:
1. ㄹ in syllable-final position is pronounced like English "l" (달, 불, 골).
2. ㄱ, ㄷ, ㅂ in final position are unreleased, as in English "took"/"pop"/"boot" (벽, 적, 목, 벋, 만,
   곧, 법, 접, 몹).
3. ㅅ, ㅈ in final position are both pronounced as ㄷ (벗, 맛, 곳, 빗, 낮, 젖 all surface with a final
   [t]-like unreleased stop).
4. ㅇ in final position is pronounced "ng" (병, 명, 정).
This is functionally the same 7-representative-consonant batchim system documented in other Korean
sources in this project (e.g. `established/016`'s "7-representative-sound batchim-neutralization
table") but presented here as worked minimal examples rather than a consolidated table.

### Unit 4 — Aspirated consonants
ㅊ, ㅋ, ㅌ, ㅍ ("chi-us," "ki-uk," + two more) are derived by adding an aspiration stroke (ㅎ) to the
plain consonants ㅈ, ㄱ, ㄷ, ㅂ respectively. English contrast pairs illustrate the aspirated/plain
distinction (aspirated "car/take/paid/church" vs. plain "*gar/date/bade/judge" — heavy puff of air
vs. none), the same three-way lax/tense/aspirated obstruent contrast independently documented as
Korean's most distinctive phonological feature in `established/013_sounds_of_korean_pronunciation_guide.md`.

### Unit 5 — Double (tensed) consonants
ㄲ, ㄸ, ㅃ, ㅆ, ㅉ are formed by doubling five of the plain consonants. Minimal-pair listening drills
(e.g. 달-딸, 가다-까다, 자다-차다-짜다) train the three-way plain/aspirated/tensed contrast across
consonant series, directly exercising the same phonological system Unit 4 introduces structurally.

### Unit 6 — Combined vowels (diphthongs) and full syllable-block structure
Covers glide-initial combined vowels (오, 우, 으-based diphthongs realized with a ㅣ/ㅗ/ㅜ glide onset
— 와, 워, 왜, 웨, etc.) and the full three-part syllable-block structure (consonant + vowel + final
consonant), including double-consonant batchim clusters (앉, 돎, 없, 값) where only one representative
consonant is actually pronounced (앉→안, 돎→돌, 없→업, 값→갑) — directly reinforcing Unit 3's
neutralization rule at the level of consonant clusters rather than single finals. A short closing
note states Korean has no English-style word or sentence stress (unlike English "hístory" or
emphatic sentence stress), and describes three sentence-final intonation contours (falling for
statements, rising for questions, sustained-then-falling for requests) that recur as a named grammar
point throughout the lesson series (see Lesson 1's -세요 ending, below).

---

## Vocabulary and grammar — Lesson 1: 인사 (Greetings), pp. 27–34 (PDF 37–44)

### Vocabulary (Dialogue 1, p. 28)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 안녕 | peace | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Root of the greeting idiom below. |
| 하다 | do | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Highly productive light verb, as in other Korean sources. |
| 안녕하세요? | How are you? | idiom (greeting) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Literally "Are you in peace?"; source flags as a set phrase not to be parsed compositionally by learners. |
| 미스터 | Mr. | noun (loanword, title) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | English loanword; restricted register — see Grammar points. |
| 미스 | Ms./Miss | noun (loanword, title) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | English loanword; restricted register — see Grammar points. |
| 예 | yes | interjection | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 오래간만 | long time (since last meeting) | noun/idiom | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Used in 오래간만입니다 "it's been a long time." |
| 입니다 | is/are (copula) | copula | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 어떻게 | how | adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 지내다 | get along | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 잘 | well | adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 은/는 | (topic marker) "as for..." | particle | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | See Grammar points: topic case marker. |
| 요즈음 | these days | adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |

### Vocabulary (Dialogue 2, p. 32)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 바쁘세요 | (are you) busy | adjective (honorific form) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | From stem 바쁘다. |
| 좀 | a little | adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 별로 | particularly (not) | adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Collocates obligatorily with negation — see Grammar points. |
| 안 | not | negator | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Short-form negation, placed before the verb. |
| 가세요 | go (honorific) | verb (honorific form) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | From stem 가다. |
| 갑니다 | go (plain declarative) | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 지금 | now | adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 어디 | where | pronoun/adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 식당 | restaurant | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 그럼 | well, then | discourse connective | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 안녕히 | peacefully | adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Used in both leave-taking idioms — see Lesson 2 Grammar points. |
| 저는 | as for me | pronoun + topic particle | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Humble-register 1sg 저 + 는; source glosses the combination as a set humble expression. |
| 우체국 | post office | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |

### Grammar points

**Asking "How are you?"** 안녕하세요? is a fixed idiomatic greeting (literally "are you at peace?"),
to be learned as a set phrase rather than parsed.

**Addressing Korean adults.** Koreans rarely address someone by bare name. A job-related title
(선생님 "teacher," 교수님 "professor," 의사 선생님 "doctor," 김박사님 "Dr. Kim," 과장님 "section
chief," 사장님 "president") or a title + surname (김선생님 "Mr. Kim") is standard; when the title is
unclear, 선생님 + surname is the default-safe form. English-loanword titles 미스터 (male) / 미스
(female) are restricted to a senior addressing a junior employee (esp. a recent hire) — explicitly
flagged as inappropriate toward people one isn't close to or who outrank/outage the speaker (Lesson
1's own Culture point elaborates this).

**Writing Korean names.** Korean full names take surname-first order (김달수 = "Dal Soo Kim").

**Polite "how are you?"** 안녕하십니까? is the more formal/first-meeting variant of 안녕하세요?,
typically paired with a title+님 form of address.

**Topic case marker -은/는.** Attaches to a noun introducing a new topic relative to previous
discourse; -은 after a consonant-final noun, -는 after a vowel-final noun. Glossed "as for..."

**Sentence ending -세요.** Attached to a verb stem; expresses a statement (falling intonation), a
question (rising intonation), or a request (sustained-then-falling intonation) — the same
three-contour system introduced in the Introduction's Unit 6. The honorific element -세- marks
respect toward an addressee who outranks or is older than the speaker.

**The negative marker 안.** Placed directly before the verb, negates most Korean verbs (identity/
copula verbs are excluded, per the source, and introduced separately later).

**The manner adverb 별로.** Obligatorily co-occurs with negation (안 or -지 않다) — "not particularly/
not very."

**The postposition -에.** Attaches directly to a place noun, used with 가다 "go"/오다 "come" or their
compounds, to mark a specific goal/direction (교회에 갑니다 "I am going to church").

**Culture point (p. 31): the Confucian basis of Korean honorifics.** The source explicitly frames
Korean's honorific system as rooted in Confucian ethics recognizing three axes of asymmetry — greater
power, greater age, higher social rank — each of which the language marks through corresponding
honorific/deferential speech; the text states outright that "Koreans do not usually honor equality in
their daily interpersonal relationships."

---

## Vocabulary and grammar — Lesson 2: 친구 소개하기 (Introducing friends), pp. 35–42 (PDF 45–52)

### Vocabulary (Dialogues 1–2, p. 36, 40)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 덕택에 | thanks (to you) | idiom/adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 친구 | friend | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 소개하다 | introduce | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 제 | my (humble possessive) | pronoun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | 저 + 의 contracted; matches `established/001`'s 제. |
| 이분 | this person | pronoun (honorific) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 처음 | first time | noun/adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Used in 처음 뵙겠습니다 "nice to meet you" (lit. "first time I humbly see you"). |
| 뵙다 | see (humble form) | verb (humble) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Humble-register suppletive verb for "see/meet." |
| 씨 | Mr./Miss (name-suffix title) | noun suffix | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Attaches directly after a full name or given name; neutral-polite register, distinct from 님. |
| 알다 | know | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 아니요 | no | interjection | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 인사하다 | greet | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 가 보다 | try to go | verb (auxiliary compound) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | 가다 + exploratory auxiliary 보다. |
| 계십시오 | (please) stay | verb (honorific request form) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Used in 안녕히 계십시오, addressed to the person remaining — see Grammar points. |
| 모르다 | do not know | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Suppletive negative of 알다, not 안 알다. |
| 다음에 | next time | adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 또 | again | adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |

### Grammar points

**Five forms of sentence expression.** The source frames all Korean sentences as one of five types —
declarative, interrogative, request, command, exclamation — distinguished by verb ending and
intonation. -입니다/-습니다 is exclusively declarative; -입니까?/-습니까? exclusively interrogative;
-십시오 exclusively a request form; -요 is ending-flexible, distinguished only by intonation (this
directly cross-references the Introduction's Unit 6 intonation-contour note and Lesson 1's -세요
point).

**Linking verb -입니다.** The Korean equivalent of English copula "to be," obligatorily suffixed
directly onto the preceding noun (이분이 강기수씨입니다 "This person is Ki Soo Kang").

**Subject case markers -이/가.** -이 after a consonant-final noun, -가 after a vowel-final noun;
source explicitly flags the full case-marking system as complex and to be built up gradually across
lessons (consistent with how it is introduced piecemeal in other Korean sources in this project).

**Future tense marker -겠.** Inserted between verb stem and ending; marks a future action, or a
future-referring condition/quality (내일 오겠어요 "I'll come tomorrow"). Also used non-literally in
processed set-phrase in 처음 뵙겠습니다 (Lesson 2 Dialogue 1) — a formulaic "nice to meet you" that
morphologically contains the future-tense marker but is functionally present-tense idiomatic.

**Basic Korean sentence structure.** Subject + predicate order, with the verb always sentence-final;
subjects are freely omitted when recoverable from context (a discourse-pragmatic ellipsis pattern,
illustrated by several elided-저 example sentences).

**Personal pronouns — full paradigm (p. 41).**

| Person | Level | Singular | Plural |
|---|---|---|---|
| 1st | familiar | 나/내 "I" | 우리 "we" |
| 1st | humble | 저/제 | 저희 |
| 2nd | familiar | 너/네 "you" | 너희 "you (pl.)" |
| 3rd | familiar | 그 사람 "he/she" | 그 사람들 "they" |
| 3rd | honorific | 그분 | 그분들 |

첫/저/너 (unmarked-final forms) obligatorily take -는 as subject particle; 내/제/네 (already
particle-fused forms) obligatorily take -가 (내가, 제가, 네가) — an allomorphy rule not stated this
explicitly in the Wave 1/2 sibling files, worth flagging as this book's own distinct pedagogical
framing of the same underlying case-marking behavior.

**Saying goodbye — asymmetric departure idiom.** Korean distinguishes the remaining party's farewell
(안녕히 계세요, lit. "stay in peace") from the departing party's farewell (안녕히 가세요, lit. "go in
peace") — unlike English's symmetric "goodbye." When both parties are leaving simultaneously, both
use 안녕히 가세요.

**Culture point (p. 38–39): the mechanics of introduction and probing personal questions.** When a
Korean introduces someone to a third party, the introduction is normally made *to* the senior/older/
more powerful person. That senior person's first questions to the newly introduced person are
typically personal (age, occupation, marital status, children) — the source frames this as a
socially standard way of establishing relative social rank and the corresponding register to use,
not intrusiveness, and suggests deflecting with tact rather than treating the questions as rude.

---

## Vocabulary and grammar — Lesson 3: 사무실에서 (In an office), pp. 43–49 (PDF 53–59)

### Vocabulary (Dialogues 1–2, p. 44, 47)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 수고하십니다 | Hello (lit. "you are working hard") | idiom (greeting) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Used specifically to interrupt someone at work — see Grammar points. |
| 누구 | who | pronoun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 사업 | business | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 잠깐 | a moment | adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 들어가다 | enter | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 기다리다 | wait | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 이리 | this way | adverb (directional) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 앉다 | sit | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 감사하다 | thank | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 바쁘게 | busily | adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Derived via -게 from 바쁘다 — see Grammar points. |
| 장사 | business (commerce) | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 기분 | mood, spirits | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Root of 기분(이) 좋다/나쁘다 idioms. |
| 좋다 | good | adjective | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 잘 되다 | doing well | verb (compound) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 오래간만 | long time | noun/idiom | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Recurs from Lesson 1; here also attested in informal -이에요 form 오래간만이에요. |
| 요즘 | lately | adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Contracted variant of 요즈음 (Lesson 1). |
| -이에요/입니다 | is/are | copula | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | See Grammar points: informal ending -이에요. |
| 예/네 | yes | interjection | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 여기 | here | pronoun/adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 커피 | coffee | noun (loanword) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 한 잔 | one cup | numeral classifier phrase | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 괜찮다 | OK, fine | adjective | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 참/정말로 | really | adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |

### Grammar points

**Two different forms of honorifics — short vs. long.** Korean politely-marked statements,
questions, and requests each have a short form (-세요/-세요?/-세요) and a longer, slightly more
formal/polite form (-십니다/-십니까?/-십시오). The two are nearly interchangeable in meaning; the
source notes the short form is used more commonly by women than men — an explicit gendered-register
flag, comparable to gendered-register notes in other Korean sources in this project (e.g.
`established/005`'s "used by women" flag on 세상에!).

**Built-in (suppletive) honorific verbs — full lesson paradigm.**

| Plain stem | Honorific form | Gloss |
|---|---|---|
| 있다 | 계시다 | to exist/be |
| 자다 | 주무시다 | to sleep |
| 먹다 | 잡수시다 | to eat |
| 말하다 | 말씀 드리다 | to say/tell/speak |
| 보다 | 뵙다 | to see |
| 주다 | 드리다 | to give |
| 묻다 | 여쭙다 | to ask |

This is a fuller suppletive-honorific-verb table than either Lesson 1 or Lesson 2 individually
supplied and directly parallels the suppletive-verb systems documented in Wave 1/2 Korean sources
(e.g. `established/007`'s humble suppletive verbs 뵈-/말씀 드리-).

**Interrupting someone at a job site — 수고하십니다.** Literally "you're engaged in hard work,"
used as a greeting-substitute specifically to interrupt someone who is working; the source flags it
as inappropriate for referring to a third party absent from the scene.

**The informal ending -이에요.** A colloquial pronunciation/spelling of -입니다, favored by female
speakers and schoolchildren; male speakers tend to prefer -입니다 itself — a second explicit
gendered-register note in this same lesson. After a vowel-final noun, 이 contracts into the
preceding vowel (e.g., 예 from 이 + 에).

**The adverbial ending -게.** Converts certain adjectives into adverbs (빠르다→빠르게 "quickly,"
느리다→느리게 "slowly," 바쁘다→바쁘게 "busily") — the same -게 adverbializer documented at greater
systematic depth in `established/003_intermediate_korean_part1.md` and `established/011`.

**The causal conjunction -아(어/여)서.** Attaches directly to the first verb's stem to mark a causal
relationship between two clauses (오늘은 바빠서, 도서관에 안 가요 "Since I'm busy today, I'm not
going to the library").

**The possessive marker -의.** Marks possession (equivalent to English "'s"/"of"); the source notes
it is usually dropped in casual speech (친구(의) 책 "friend's book").

**Culture point (p. 46): 기분/"kibun" and Korean self-esteem.** The source glosses 기분 ("kibun") as
a difficult-to-translate concept of personal emotional equilibrium/self-esteem (loosely likened to
"karma" by the source, though this is an imprecise gloss), and states that once a Korean's kibun
turns negative in an interaction, reaching agreement becomes very difficult — framed as a caution to
foreign learners about social sensitivity rather than a prescription to flatter.

---

## Vocabulary and grammar — Lesson 4: 길 묻기 (Asking for directions), pp. 50–61 (PDF 60–71)

### Vocabulary (Dialogues 1–2, p. 51, 57)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 실례합니다 | excuse me | idiom | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 서울역 | Seoul Station | proper noun | core | — | contemporary (source published 2000) | South Korea | local | grammar_reference | n/a | verified | |
| 감사합니다 | thank you | idiom | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 아니다 | not to be | copula (negative) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | See Grammar points: negating identification sentences. |
| 저기 | (over) there | pronoun/adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Away from both speaker and hearer — see Grammar points. |
| 곧장 | right away, straight | adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 조심하다 | be cautious | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 여기 | here | pronoun/adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Near speaker — see Grammar points. |
| 지하철역 | subway station | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 저쪽으로 | that way | adverb (directional) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 돌다 | turn around | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 천만에요 | you're welcome | idiom | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 왼쪽으로 | to the left | adverb (directional) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 건너다 | cross | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 길 | street | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 잃어 버리다 | to get lost | verb (compound) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | 잃다 "lose" + completive auxiliary 버리다. |
| 골목 | alley | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 걸리다 | to take (time) | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 걸어서 | by foot | adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 멀다 | far | adjective | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 차로 | by car | noun + postposition | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | See Grammar points: postposition -(으)로. |
| 타다 | to ride | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 별로 | particularly | adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Recurs from Lesson 1. |
| 미국대사관 | U.S. Embassy | proper noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 지나가다 | pass by | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 아마 | probably | adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 많이 | much, many | adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 면 | if | conjunction (bound) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | See Grammar points: -(으)면. |
| 택시 | taxi | noun (loanword) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 시간 | time | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 아무튼 | anyway | adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |

### Grammar points

**Expressing location and direction — two full three-way deictic paradigms.**

| Location | Gloss |
|---|---|
| 여기 | here — near the speaker |
| 저기 | there — away from both speaker and hearer |
| 거기 | there — near the hearer |

| Direction | Gloss |
|---|---|
| 이리 | this way — toward the speaker |
| 저리 | that way — away from both speaker and hearer |
| 그리 | that way — toward the hearer's own direction of travel |

This is a clean, source-diagrammed three-way speaker/hearer/away deictic system for both stative
location and directional motion — presented with the book's own two labeled triangle diagrams.

**Two ways of negating Korean sentences.** (1) Identification sentences (A 이/가 B입니다) are
negated by promoting the complement to subject status (with 이/가) and using the negative copula
아니다/아닙니다: 이분이 한국사람입니다 → 이분이 한국사람이 아닙니다 "This person isn't Korean." (2)
All other verb types are negated with the preposed marker 안 (as in Lesson 1).

**More polite question forms for asking directions.** 말씀 좀 묻겠습니다 "May I ask you something?"
and 뭐 좀 물어봐도 될까요? "Would you mind if I asked you something?" are given as more deferential
alternatives to a bare question, useful specifically when approaching a stranger.

**Contracted forms in casual speech.** 바로 여기입니다 can contract to 바로 여깁니다; 바로 저기입니다
to 바로 저깁니다 — a 이 + 입니다 → 입니다 contraction pattern.

**The consonant ㅎ carrying over in pronunciation.** In 어떻게, the batchim ㅎ carries over into the
next syllable's onset, yielding the pronunciation 어떠케; the same happens in 이렇게→이러케,
그렇게→그러케 — a live phonological-liaison rule building on the Introduction's batchim material.

**Informal verb ending -아(어/여)요.** Used with an already-acquainted hearer; usable for statements,
questions, or commands depending on intonation. Insertion vowel depends on the stem's own vowel: 아/오
stems → 아요 (가요, 자요, 앉아요); 우/으/이 stems → 어요 (바빠요, 먹어요); 하다 stems → 해요 (일해요,
운전해요). This is the same "informal polite" -요 ending system documented in depth elsewhere in this
project's Korean sources, here introduced with the book's own worked vowel-harmony rule.

**Informal sentence ending -ㄹ/을 거예요.** Marks probability/likelihood; an informal counterpart of
-ㄹ/을 것이예요 (기차가 역에 도착할 거예요 "The train'll probably arrive at the station soon").

**Conjunction of condition/stipulation -(으)면.** Attached to a verb's present stem, marks "if"/
"when"; -면 after a vowel or ㄹ-final stem, -으면 after a consonant-final stem. The dependent clause
precedes the main clause (unlike English's free ordering). Source-flagged irregular forms: 그러면,
쉬우면, 그으면.

**Sentence ending of obligation -야 하다.** Equivalent to English "have to"/"must"/"should."
Vowel-insertion rule: 아 after 아/오-stems, 어 after 어/으/이-stems (with a consonant-final base), 해
after 하다 itself; no insertion after a vowel-final stem. Tense marking occurs on the final verb 하다.

**The postposition -(으)로 (instrumental/means-of-motion).** Marks the means by which one travels or
acts (기차로 "by train," 버스로 "by bus," 비행기로 "by plane," 배로 "by ship," 고속버스로 "by express
bus"); -로 after a vowel-final noun, -으로 after a consonant-final noun (무엇으로 "by what").

**Irregular verb stem 잃 (읽 in some editions' analog).** The source flags 잃 specifically: its
second (medial) consonant becomes silent in pronunciation, so 잃 is pronounced 일 — a small,
source-specific batchim-simplification note building on the Introduction's Unit 3/6 neutralization
material.

**Culture point (p. 55): downtown Seoul landmark map.** The source includes a hand-drawn tourist map
of central Seoul (City Hall, KNTC, Sejong Cultural Center, Kyobo Building, U.S. Embassy,
Kyŏngbokkung Palace, and four deluxe hotels — Chosun, Plaza, Lotte, President) as concrete
sociocultural/geographic content tied directly to the lesson's direction-giving vocabulary.

---

## Vocabulary and grammar — Lesson 5: 어디 가세요? (Where are you going?), pp. 62–72 (PDF 72–82)

### Vocabulary (Dialogues 1–2, p. 63, 68)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 주말 | weekend | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 있다 | to be, exist | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | See Grammar points: the verb of existence. |
| 뉴욕 | New York City | proper noun (loanword) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 기차 | train | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 돌아오다 | return | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 뭐로 | by what | pronoun + postposition | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 집에 | (to) home | noun + postposition | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 언제 | when | pronoun/adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 다음 | next | noun/adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 잘 | well | adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 다녀오다 | go and come back (honorific) | verb (compound, honorific) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Used in 잘 다녀오세요 "have a nice trip." |
| 아버님 | father (honorific) | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 기차역 | train station | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 고향 | hometown | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 자주 | frequently | adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 가끔 | sometimes | adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 내일 | tomorrow | noun/adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 생일 | birthday | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 모레 | the day after tomorrow | noun/adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |

### Grammar points

**Honorific markers 시/세 — subject restriction.** Explicitly not usable when the speaker is the
grammatical subject (어디 가십니까? "where are you going?" is fine, but a first-person response
*집에 가십니다* is flagged ungrammatical) — reinforces that honorific marking tracks the referent's
social status, not the speaker's own register choice.

**The postposition -에 (place vs. time).** As a place marker (see Lesson 1/3), it marks a
destination with 가다/오다. As a time marker (attached after a time word), it is equivalent to
English "at/on/in" (주말에 "over the weekend," 오후에 "in the afternoon," 정오에 "at noon").

**The verb of existence 있다.** Marks existence, location, or possession; when following a place
word it conveys location (도서관은 어디에 있습니까? "Where is the library?"). Explicitly distinguished
from the equational copula 이다 (introduced in the next lesson).

**The pronoun 누구 ("who") — allomorphy under case-marking.** With subject marker -가, the second
syllable 구 is dropped (누구+가 → 누가). With the copula 이다 or object markers -을/를, the full form
누구 is retained (이분이 누구입니까? "Who is this person?").

**Deletion of the postposition -에 (location).** In simple sentences, -에 marking a destination is
freely dropped (한국(에) 가요). This deletion does **not** apply to -에 marking time — 주말 어디에
가세요? cannot drop 에 without becoming ungrammatical, an explicit exception flagged by the source.

**Deletion of subject case markers.** The -이/가 subject markers introduced in Lesson 2 are likewise
freely deletable in casual speech (뉴욕 어디 있습니까? without 이/가).

**Honorific subject case marker -께서.** Replaces plain -이/가 when the subject is an honorific-
referent noun, stacking with (and intensifying) honorific marking already on the verb (아버님께서
오셨습니다 "Father came"; 어머님께서 고향에서 오십니다 "Mother is coming from my hometown").

**Sentence ending -거든요.** Marks astonishment/delight, or (in another use) a minor causal
justification roughly translatable as "because X!" (친구가 오거든요 "Because my friend's coming!").
This is the same -거든(요) form independently documented as "graduating" from clausal conjunction to
a colloquial spoken-register indirection device in `established/003`'s Units 9/12 treatment — worth
cross-referencing as a register-relevant recurring form across this project's Korean sources.

**The postposition -에서 (origin, extending the Lesson 1 locative use).** Beyond marking the location
of an event (Lesson 1), -에서 before 오다 "to come" marks the point of origin (어머님께서 서울에서
오셨습니다 "My mother came from Seoul"; 편지가 고향에서 왔어요 "A letter came from my hometown").

**Honorific/non-honorific verb-form system — the book's own consolidated paradigm table (p. 69–71).**
This is presented explicitly as a synthesis of every ending introduced piecemeal in Lessons 1–5:

| Expression type | Non-honorific | Honorific |
|---|---|---|
| statement (long) | stem -(습)니다 | stem -(으)십니다 |
| question (long) | stem -(습)니까? | stem -(으)십니까? |
| request (long) | N/A | stem -(으)십시오 |
| statement (short) | stem -(아/어)요 | stem -(으)세요 |
| question (short) | stem -(아/어)요? | stem -(으)세요? |
| request (short) | stem -(아/어)요 | stem -(으)세요 |

Four numbered rules accompany the table: (1) vowel-final stems take no extra 으 before honorific
endings; (2) consonant-final stems insert 습 before non-honorific long endings (vowel-final stems
instead take just ㅂ); (3) the short non-honorific ending's vowel choice (아/어/여) follows the
dark/bright vowel-harmony split detailed in Lesson 4, with explicit lexical exceptions listed —
이다→이에요, 아니다→아니에요, 바쁘다→바빠요, 쓰다→써요, 기다리다→기다려요, 말하다→말해요; (4) built-in
suppletive honorific verbs (있다→계시다, 자다→주무시다, from Lesson 3) don't take -시/-세 insertion at
all, instead supplying their own separate lexical honorific paradigm (계시다/계세요/계십니까?,
주무시다/주무세요/주무십니다).

**Culture point (p. 66): Seoul Railroad Station.** Built in 1926 in Renaissance style with a
Byzantine dome, serves as the hub of Korea's national rail network (~100,000 daily passengers),
now connected to Seoul's subway system — presented alongside a period photograph.

---

## Vocabulary and grammar — Lesson 6: 이것이 무엇입니까? (What is this?), pp. 73–85 (PDF 83–95)

### Vocabulary (Dialogues 1–2, p. 74, 81)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 이것 | this thing | pronoun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Near speaker. |
| 그것 | that thing | pronoun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Near hearer or mutually understood. |
| 저것 | that thing | pronoun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Away from both speaker and hearer. |
| 무엇 | what | pronoun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 책 | book | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 책상 | desk | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 이다 | to be | copula | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 아니다 | not to be | copula (negative) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 한국어 책 | Korean language book | noun phrase | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 아니오 | no | interjection | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 스테플러 | stapler | noun (loanword) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 있어요 | have | verb (informal) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 없습니다 | not have | verb (negative) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 옆방 | next room | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 고맙다 | to be thankful | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 클립 | paper clips | noun (loanword) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 가져다 주다 | fetch | verb (compound) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | 가져다 (bring) + 주다 (give-benefactive). |
| 좀 | (polite marker) | particle | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Softens a request; recurs from Lesson 1's manner-adverb 좀 but functioning here as a discourse softener. |
| 그렇게 | that way, so | adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 잠깐 | for a moment | adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 천만에요 | you're quite welcome | idiom | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 몇 개 | some (a few items) | numeral classifier phrase | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |

### Grammar points

**Sentence expressing an identity.** The linking verb -입니다/-입니까? (Lesson 2) identifies a
subject with a predicate noun: A(이/가) B입니다 "A is B."

**The linking verb 아닙니다 and the double-subject construction.** The negative counterpart of
입니다 requires the complement noun to be promoted into subject position with its own -이/가 marker,
yielding two subject-marked nouns in one clause (A(이/가) B(이/가) 아닙니다) — explicitly named by
the source as a "double subject construction."

**Full four-way demonstrative pronoun system — "thing" and "person" categories.**

| Thing | Gloss | Person | Gloss |
|---|---|---|---|
| 이것 | this (near speaker) | 이분 | this person (near speaker) |
| 그것 | that (near hearer/mutual) | 그분 | that person (near hearer/mutual) |
| 저것 | that (away from both) | 저분 | that person (away from both) |

This is the same three-way speaker/hearer/away deictic structure as Lesson 4's location/direction
pointers, now extended to "thing" and "person" categories with the book's own two further triangle
diagrams (including an explicit "Third Person" labeled diagram for 저분/그분).

**Casual contraction of thing-pointers.** 이것/그것/저것 can lose their final consonant in speech
(이거/그거/저거); when the subject marker -이 follows, it further contracts (이거+이 → 이게, 그거+이 →
그게, 저거+이 → 저게).

**Demonstrative modifiers 이/그/저.** Combine directly with common nouns as prenominal modifiers (이
책상 "this desk," 저 볼펜 "that pen," 그 학생 "the student near you").

**The informal ending -이에요/아니에요.** As in Lesson 3, -입니다 has a colloquial variant -이에요
(contracting to 예 after a vowel-final noun), favored by women/schoolchildren over men. Its negative
counterpart is specifically -아니에요 (not a further-modified 아니다 form) — an explicit lexical
pairing flagged by the source.

**Topic case marker -은/는 — expanded worked paradigm.** Building on Lesson 1's introduction, this
lesson supplies a fuller worked table contrasting consonant-final nouns (창문은, 분필은, 책은) against
vowel-final nouns (지도는, 의자는, 지우개는), and shows the marker contracting to -건 when a
demonstrative thing-pronoun precedes it (이것은→이건, 그것은→그건, 저것은→저건) — paralleling the
이거/그거/저거 contraction above.

**The verb 있습니다 (있다) — polysemy across location/existence/possession.** Beyond marking simple
location (Lesson 5), 있다 also covers "there is/are" (여기에 연필 있어요 "Here is a pen") and "do you
have" (지우개 있어요? "Do you have an eraser?"). Its negative counterpart 없다 covers both "there
isn't/aren't" and "doesn't have."

**The postposition -에 (existential locative, extending Lesson 3/5).** Co-occurs specifically with
existential verbs 있다/계시다/없다/많다 ("to be many/much")/살다 ("to live"), glossable as "at/in"
(책상이 교실에 있습니다 "Desks are in the classroom"; 휴게실에 사람이 많습니다 "There are lots of
people in the lounge").

**Sentence ending -는데요.** Attached to a verb stem, conveys "but..." and implicitly invites a
follow-up comment or request from the hearer (여기에 한국어 사전이 없는데요 "There's no Korean
dictionary here, but..." — implying "what should I do?").

**Culture point (p. 80): vertical office hierarchy and its linguistic marking.** Korean office
relationships are explicitly vertical, expressed through a fixed title ladder (사장 "president," 전무
"director," 상무 "managing director," 부장 "division chief," 과장 "section chief," 대리 "assistant
section chief," 신입사원 "new employee"). A colleague addresses a junior by surname + title, and a
senior by surname + title + honorific -님. The source explicitly notes visible submissiveness from
low-rank to high-rank staff (including routine requests for office-supply fetching, as dramatized in
Dialogue 2) and flags that a female employee's role is generally treated as minor relative to a male
employee's, though higher rank can override this — a directly stated gender-and-rank interaction
worth flagging for register-mapping purposes.

---

## Vocabulary and grammar — Lesson 7: 점심식사 (Going out for lunch), pp. 86–96 (PDF 96–106)

### Vocabulary (Dialogues 1–2 + reading passage, p. 87, 91–92, 96)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 점심하다 | have lunch (plain) | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 식사하다 | have meals (honorific) | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 아직(도) | yet | adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 밖에서 | outside | adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 같이 | together | adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 구내식당 | refectory | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 어떻다 | (be) how | adjective | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 값이 싸다 | cheap | idiom/adjective phrase | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 음식 | meal | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 괜찮다 | OK | adjective | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 어서 | quickly | adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Used in 어서 오세요 "welcome, please come in" (restaurant/store entry formula). |
| 감사합니다 | thank you | idiom | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 무엇(뭘) | what | pronoun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | 뭘 is the further-contracted colloquial form — see Grammar points. |
| 들다 | take | verb (irregular, honorific-capable) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | See Grammar points: irregular verb 들다. |
| 차례 | (one's) turn | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 내다 | pay/treat | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 계산서 | guest check | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 아주머니 | waitress (married) | noun (address term) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Conventional address term for a married female server, not a job title per se. |
| -도 | also | particle | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | See Grammar points: emphatic marker. |
| 알다 | know | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 비빔밥 | rice and beef with mixed vegetables and hot paste | noun (dish name) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 사다 | buy | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 둘 | two | numeral (native Korean) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 시키다 | order | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 냉면 | cold noodles | noun (dish name) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 맛 | taste | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 맵다 | hot and spicy | adjective | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 다 | all of it | adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |

### Grammar points

**Past tense — full stem-final-vowel-conditioned paradigm.** Formed by inserting 았/었/였 between
the verb stem (or honorific stem+시) and the ending. Rule 1: 아/오-final stems take -았 (가다→갔습니다,
좋다→좋았습니다, 많다→많았습니다). Rule 2: any other stem-final vowel takes -었 (기다리다→기다렸습니다,
쓰다→썼습니다, 배우다→배웠습니다, 가르치다→가르쳤습니다, 먹다→먹었습니다). Rule 3: 하다-verbs take -였
(공부하다→공부했어요/공부하였어요, both forms given as equivalent). Honorific past tense inserts -시-
before the past-tense marker (읽으시었다 pattern).

**Suggestion ending -실까요?.** Attached to a verb stem, equivalent to "Shall we...?"/"Shall I...?"
(여기 앉으실까요? "Shall we sit here?").

**Suggestion ending -(ㅂ)시다.** A stronger suggestion/proposal form, equivalent to "Let's...". -시다
after a vowel-final stem (ㅂ inserted), -읍시다 after a consonant-final stem (점심 밖에서 합시다 "Let's
have lunch outside"; 의자에 앉읍시다 "Let's sit on the chair"). Explicitly contrasted with -실까요? as
stronger/more assertive rather than a mere suggestion.

**Object case marker -을/를.** Marks the object of a transitive verb; -을 after a consonant-final
noun, -를 after a vowel-final noun; freely deletable in speech (커피(를) 하셨어요? "Did you have
coffee?").

**The coordinate conjunction -고.** Connects two clauses/phrases as "and"; conjoined clauses may have
different subjects while sharing one discourse topic (오늘은 바람이 불고 비가 와요 "Today is windy
and rainy").

**Topic case marker -은/는 — contrastive/comparative use.** Beyond simple topic-introduction (Lesson
1/6), this lesson highlights -은/는's contrastive nuance: 저 비빔밥 하지요 (plain statement) vs. 저는
불고기 백반 하지요 (implies "unlike you, I'll have X"). The topic marker can replace either the
subject markers -가/이 or the object markers -을/를.

**Emphatic marker -도 ("also/too").** Attaches to nearly any sentence element, replacing subject/
object particles when it does (저도 가겠습니다 "I'll go also"; 저도 불고기 백반을 하지요 "As for me,
I'll have the Pulgogi dinner also").

**Less polite informal ending -지요.** Used in statements/questions/suggestions inviting the
listener's confirmation, equivalent to English tag questions ("...isn't it?", "...won't you?") — 저
사람은 한국분이지요? "He's Korean, isn't he?"

**The irregular verb 들다.** Has a built-in honorific sense ("take"/"eat" in an eating context); its
final ㄹ consonant is dropped before a following ㅅ (식사 많이 드세요 "Please eat a lot").

**The contracted form 뮐.** From 무엇을 (what + object marker) → 무얼 (ㅅ drops before a vowel) → 뭘
(further colloquial contraction) — three-stage contraction chain for a single frequent interrogative
object phrase.

**Native Korean cardinal numbers 1–100 — full paradigm table (p. 93).**

| 1 | 하나 | 11 | 열하나 | 30 | 서른 |
|---|---|---|---|---|---|
| 2 | 둘 | 12 | 열둘 | 40 | 마흔 |
| 3 | 셋 | 13 | 열셋 | 50 | 쉰 |
| 4 | 넷 | 14 | 열넷 | 60 | 예순 |
| 5 | 다섯 | 15 | 열다섯 | 70 | 일흔 |
| 6 | 여섯 | 16 | 열여섯 | 80 | 여든 |
| 7 | 일곱 | 17 | 열일곱 | 90 | 아흔 |
| 8 | 여덟 | 18 | 열여덟 | 100 | 백 |
| 9 | 아홉 | 19 | 열아홉 | | |
| 10 | 열 | 20 | 스물 | | |

The numbers 하나/둘/셋/넷/스물 shorten irregularly when immediately followed by a counter noun:
한(1)/두(2)/세(3)/네(4)/스무(20) + 분 "person(s)" or 개 "piece(s)" (한분 "one person," 두개 "two
pieces," 스무분 "twenty people"). This is the native-Korean numeral system, distinct from the
Sino-Korean system (not covered in this chunk's range).

**Culture point (p. 90): Korean restaurant culture.** Restaurants specializing in fire-grilled meats
(Pulgogi, Kalbi) vs. rolled-rice dishes (Kimpap) are both common; grilled-meat restaurants are
pricier and often require a minimum two-serving order; a shared Pulgogi meal typically comes with
rice and 6-7 side dishes; tipping is not expected at most restaurants unless otherwise stated.

**Reading passage (p. 95) and menu (p. 96): concrete lexical/pricing content.** A short narrative
reading passage (Mr. Goldsmith ordering 비빔냉면 that turns out too spicy for him, 매워서 다 먹지
않았다 "it was too spicy, so he didn't finish it all") functions as reading-comprehension practice
built entirely from already-introduced vocabulary/grammar. A reproduced restaurant menu (차림표) gives
five named dishes with 1998-era won prices (불고기 백반 10,000원, 갈비 13,000원, 갈비탕 5,000원, 냉면
5,000원, 비빔밥 5,000원) — genuine period price-point sociocultural content.

---

## Vocabulary and grammar — Lesson 8: 약속하기 (Making an appointment), pp. 97–106 (PDF 107–116)

### Vocabulary (Dialogues 1–2 + reading passage, p. 97–98, 102, 106)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 저녁 | night/evening | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 친구 집 | friend's house | noun phrase | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 텔레비젼 | TV | noun (loanword) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 프로그램 | program | noun (loanword) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 아주 | very, much | adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 재미있다 | interesting | adjective | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 보다 | see | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 무얼 | contraction of 무엇을 | pronoun + object marker | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | See Lesson 7's fuller three-stage contraction chain. |
| 미식축구 | American football | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 가끔 | sometimes | adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 별로 | particularly | adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 거친 운동 | violent sports | noun phrase | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 싫어하다 | dislike | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 어제 | yesterday | noun/adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 야구 | baseball | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 시간 | time | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 하고 | with | postposition | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | See Grammar points. |
| 약속 | appointment | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 저녁식사 | supper | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 명동 | Myongdong | proper noun | core | — | contemporary (source published 2000) | South Korea | local | grammar_reference | n/a | verified | Seoul neighborhood. |
| 일 | work | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 전화하다 | make a phone call | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 끝나다 | finish (intransitive) | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 내일 | tomorrow | noun/adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 아파트 | apartment | noun (loanword) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 축구 | soccer | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 시계 | watch | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 팀 | team | noun (loanword) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 시합하다 | compete | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 경기 | game, match | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 무승부 | draw | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 다치다 | get hurt | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |

### Grammar points

**Four types of Korean verb — the book's own explicit taxonomy.** Action verbs (indicate an
action/movement: 보다 "see," 먹다 "eat"), adjectival verbs (indicate quality/condition, equivalent to
English predicate adjectives: 좋다 "good," 바쁘다 "busy," 많다 "many/much"), existential verbs
(indicate existence/location/possession: 있다, 없다), and linking verbs (copula, indicating
identity/equation: 이다, 아니다). This four-way taxonomy is presented explicitly as an organizing
framework the book will build on going forward (noun modifiers from action/existential verbs are
flagged as reserved for Lesson 11).

**The conjunction -는데.** Usable only with an action verb or 있다; glosses flexibly as "and"/"but"
depending on context (어제 저녁에 텔레비젼 봤는데, 별로 재미 없었어요 "I watched TV last night, but it
wasn't that interesting").

**The conjunction -지만.** A contrastive conjunction usable with any verb type, glossed "although"/
"but," connecting two clauses in direct contrast (내일은 날씨가 나쁘지만, 공원에 나가겠어요 "Tomorrow's
weather will be bad, but I'll go to the park anyway").

**The noun modifier -ㄴ(은).** Functions like an English adjective; attaches to a descriptive-verb
stem to premodify a noun (싸다→싼 물건 "cheap merchandise," 크다→큰 식당 "big restaurant," 좋다→좋은 책
"good book"). Explicitly flagged as covering only descriptive-verb-derived modifiers here; noun
modifiers from action verbs and 있다/없다 are deferred to Lesson 11.

**Culture point (p. 101): Korean short-notice appointment norms.** Koreans, unlike Americans/
Europeans, rarely schedule social/business appointments far in advance — typically only a few hours
to a couple of days ahead. The source frames this explicitly as face-saving: it avoids having to
explain a cancellation if higher-priority business arises later, particularly relevant for a junior
staff member who might be pulled into a superior's request that conflicts with an earlier personal
engagement.

**Echoing the question in Korean.** Appending -요 to a repeated word/phrase functions as a
clarification-request ("Do you mean...?") — 서울에요? "Do you mean Seoul?", 소련에요? "Do you mean
Russia?"

**The verb-stem particle -는 (for 있다/없다).** Attaches to 있다/없다's stem to form a location-
identifying modifier clause (명동에 있는 식당 "the restaurants located in Myongdong"; 저기 있는 모자
"the hat over there") — functions similarly to the -ㄴ(은) modifier above but specifically for the
existential-verb class, foreshadowing Lesson 11's fuller modifier-clause system.

**Sino-Korean cardinal numbers 1–100 — full paradigm table (p. 103), contrasted with Lesson 7's
native system.** 영(0)/일(1)/이(2)/삼(3)/사(4)/오(5)/육(6)/칠(7)/팔(8)/구(9)/십(10), with the tens
built regularly (이십 20, 삼십 30 ... 구십 90, 백 100) and teens/twenties-etc. formed by simple
concatenation (십일 11, 이십일 21, 삼십일 31). The source explicitly frames this second numeral system
as used specifically for telling time (in combination with native numbers — see below) — the same
native/Sino-Korean numeral split documented as a general Korean-typology feature elsewhere in this
project's sources.

**Reading hours and minutes — mixed-system time-telling rule.** Hours use native Korean numbers +
the counter -시 (with numbers 1-4 losing their final consonant before -시: 한 시 "1 o'clock," 두 시,
세 시, 네 시); "half past" adds 반 directly after the hour (여섯 시 반 "six thirty"). Minutes use
Sino-Korean numbers + 분 (일곱 시 십분 전 "ten to seven," lit. "seven o'clock ten-minutes before," using
전 "before" for the 45-59-minute range as an alternative to counting minutes past the hour). This
mixed native-hour/Sino-minute system is a genuinely distinctive Korean time-telling convention worth
flagging for the project's typology purposes.

**The postposition -하고 ("with").** Attaches to a noun, comitative sense (오늘 저녁에 친구하고 극장에
가요 "I'll go to the cinema with my friend tonight"). Distinct from -와/과 (not covered in this
chunk's range) as an alternative "with/and" particle.

**Reading passage (p. 106): World Cup viewing anecdote.** A short narrative (Miss Johnson and Mr.
Lee watch a Korea-vs-Spain World Cup match on TV that ends in a draw, with players getting injured,
leaving both viewers in a poor mood despite the interesting game) built from already-introduced
vocabulary/grammar as reading-comprehension practice — datable content (World Cup, pre-2000
publication) worth noting for the book's own contemporary-register framing.

---

## Vocabulary and grammar — Lesson 9: 택시잡기 (Taking a taxi), pp. 107–117 (PDF 117–127)

### Vocabulary (Dialogues 1–2 + reading passage, p. 108, 112, 117)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 까지 | up to | postposition | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | See Grammar points. |
| 동대문 | Dongdaemoon | proper noun | core | — | contemporary (source published 2000) | South Korea | local | grammar_reference | n/a | verified | Seoul neighborhood/gate. |
| 타다 | get on | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 손님 | passenger | noun (address term) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 운전기사 | driver | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 지하철역 | subway station | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 멀다 | far | adjective | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 아마(도) | probably | adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 아저씨 | driver, uncle | noun (address term) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Generic respectful address for an adult male stranger (here, the taxi driver); same address-term pattern as 아주머니 for a married woman (Lesson 7). |
| 40분 | 40 minutes | numeral + counter | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Sino-Korean. |
| 정도 | about (roughly) | noun/degree word | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | See Grammar points. |
| 걸리다 | take (of time) | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | See Grammar points. |
| 건물 | building | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 오른쪽 | right side | noun/adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 교보빌딩 | Building Kyobo | proper noun | core | — | contemporary (source published 2000) | South Korea | local | grammar_reference | n/a | verified | |
| 왼쪽 | left side | noun/adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 세종문화회관 | King Sejong Cultural Center | proper noun | core | — | contemporary (source published 2000) | South Korea | local | grammar_reference | n/a | verified | |
| 내리다 | get off | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 앞으로 | forward | adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 좀더 | a little further | adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 네거리(사거리) | intersection | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Two synonymous forms given side by side by the source. |
| 내려주다 | let someone off (junior) | verb (compound, honorific-graded) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | See Grammar points: composite verb pair. |
| 신호등 | traffic signal | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 수고하세요 | goodbye (to someone still working) | idiom | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Parallels Lesson 3's 수고하십니다 greeting-substitute, here used as a closing formula toward the driver. |
| 지나다 | go by | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 요금 | fare | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 얼마 | how much | pronoun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 원 | won | noun (currency unit) | core | — | contemporary (source published 2000) | South Korea | national | grammar_reference | n/a | verified | |
| 제과점 | bakery | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 사업차 | on business | adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 방문하다 | visit | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 거리 | street | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 모르다 | do not know | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Suppletive negative of 알다, as noted in Lesson 2. |
| 공항 | airport | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 길을 잘못 들음 | to enter the wrong way | idiom (verb phrase) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 택시비 | taxi fare | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 두배 | twice | adverb/numeral phrase | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 지불하다 | pay | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |

### Grammar points

**The particle -에서(부터) ("from").** Attaches to time or place words to mark a starting point
(아침 일곱 시부터 공부합시다 "Let's study from seven in the morning"; distinguish from -에서's earlier
locative/origin senses in Lessons 1/5).

**The particle -까지 ("until/up to/as far as").** Marks an endpoint for time or place (어디까지
가십니까? "Up to where do you go?"; 두시 반까지 집에 오세요 "Please come to my home by 2:30").

**Correlational pattern -에서(부터)...까지 ("from...to...").** Combines the two particles above (세
시부터 다섯 시까지 회의했어요 "We had a meeting from 3 to 5"; 서울에서 부산까지 비행기로 한 시간
걸려요 "It takes one hour by airplane from Seoul to Pusan").

**The verb -걸리다 ("takes," of time).** Used with time-related nouns, typically co-occurring with a
transportation-mode phrase (차로 몇 시간 걸립니까? "How many hours does it take by car?"; 10분 정도
걸립니다 "It takes about 10 minutes").

**The coordinate conjunction -이고.** A subtype of Lesson 7's -고, used specifically when the first
clause takes the linking verb -이다 (이것은 책이고, 저것은 공책이다 "This is a book and that's a
notebook").

**The degree word 정도 ("about/around").** Follows a time expression to approximate it (삼십 분
정도면 됩니다 "About 30 minutes will do").

**The auxiliary verb -ㄹ(을) 수 있다 ("can/be able to").** -ㄹ 수 있다 after a vowel-final stem, -을 수
있다 after a consonant-final stem; negative counterpart -ㄹ(을) 수 없다 (그 책을 읽을 수 없었다 "I
couldn't read the book").

**Large Sino-Korean numbers and Korean currency — full paradigm table (p. 113).** Extends Lesson 8's
Sino-Korean 1-100 system: 백(100)/천(1,000)/만(10,000)/십만(100,000), with hundreds (이백 200 ... 구백
900), thousands (이천 2,000 ... 구천 9,000), and ten-thousands (이만 20,000 ... 구만 90,000) built by
regular concatenation, up to 천만 (10,000,000). The basic monetary unit is 원 (won), written with the
symbol ₩ before Arabic numerals; the source illustrates period (1998-era) coins (십원 ₩10, 오십원
₩50, 백원 ₩100, 오백원 ₩500) and bills (천원 ₩1,000, 오천원 ₩5,000, 만원 ₩10,000), with photographs of
the actual 1,000-won and 10,000-won notes (front/back, featuring historical portrait figures) as
concrete sociocultural/numismatic content.

**The conjunction -아/어서 (movement/posture-verb subtype, distinct from Lesson 3's causal -아/어서).**
Connects two actions with close temporal/causal relation; restricted to a specific class of
movement/posture verbs (가다, 오다, 지나다, 일어나다, 앉다) — contrasted explicitly with -고 (Lesson
7), which connects any two actions with a looser "after" sense and no such verb-class restriction.
Tense is marked only on the second verb, never the first, regardless of which tense the whole
sentence is in (도서관에 가서 공부합시다/공부했습니다/공부하겠습니다 — present/past/future, same
first-verb form throughout).

**The composite verb pair 내려주다 vs. 내려드리다 — explicit addressee-honorific benefactive
contrast.** 내려주다 ("let out of the car") is used toward a junior addressee; 내려드리다 toward a
senior addressee — directly parallel to the 주다/드리다 benefactive-honorific alternation documented
project-wide (e.g. `established/003`'s Unit 5 obligatory addressee-honorific substitution), here
concretely illustrated with a single everyday taxi-context verb pair.

**The contracted sentence ending -시죠.** The colloquial contraction of the less-polite informal
ending -시지요 (Lesson 7): -지 and the following 요's 이 fuse into -죠 (여기서 내리시지요? → 여기서
내리시죠? "You get off here, don't you?").

**Culture point (p. 111): Seoul taxi-hailing culture.** Seoul taxis frequently stop wherever hailed
rather than only at taxi-stands, and drivers may decline a fare heading a different direction; "Mobum
Taxi" (deluxe/exemplar taxis) offer guaranteed point-to-point service akin to American limousine
service, at a premium, for anyone prioritizing punctuality. Most ordinary taxis practice ride-sharing,
picking up additional same-direction passengers, sometimes without the first passenger's consent.
Driver smoking while driving is common; passengers may ask a driver to stop, but the source explicitly
cautions this risks lowering the driver's 기분 ("kibun," cross-referencing Lesson 3's culture point).

**Reading passage (p. 117): a real-world naturalistic taxi-fare grievance.** Edward Moon's taxi
driver takes a wrong route (길을 잘못 들어) to Hotel Shinra, doubling both the travel time (1 hour →
2 hours) and the fare (두배 많이 지불해야 했다 "had to pay twice as much") — framed explicitly as a
reading-comprehension exercise (readers are asked to infer why he was unhappy) built from
already-introduced vocabulary/grammar, and a concrete illustration of a genuine consumer-experience
narrative distinct from the lesson's scripted dialogues.

---

## Vocabulary and grammar — Lesson 10: 물건사기 (Shopping), pp. 118–127 (PDF 128–137)

### Vocabulary (Dialogues 1–2 + reading passage, p. 118–119, 124, 127)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 오후 | afternoon | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 쇼핑 | shopping | noun (loanword) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 남대문 시장 | Namdaemoon Market | proper noun | core | — | contemporary (source published 2000) | South Korea | local | grammar_reference | n/a | verified | |
| 보다 더 | (better or worse) than | comparative marker | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | See Grammar points. |
| 값 | price | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 비싸다 | expensive | adjective | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 질 | quality | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 대체로 | in general | adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 물건 | merchandise | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 신세계 백화점 | Sinsaekye Department Store | proper noun | core | — | contemporary (source published 2000) | South Korea | local | grammar_reference | n/a | verified | |
| -지 않다 | not (long negation form) | negator (bound) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | See Grammar points. |
| 백화점 | department store | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 어서 | quickly | adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Recurs from Lesson 7's 어서 오세요 formula. |
| 찾다 | look for | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 짐가방 | luggage bag | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 빨간(것) | red (thing) | adjective/pronoun phrase | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | ㅎ-irregular stem 빨갛다 — see Grammar points. |
| 파란(것) | blue (thing) | adjective/pronoun phrase | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | ㅎ-irregular stem 파랗다. |
| 노란(것) | yellow (thing) | adjective/pronoun phrase | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | ㅎ-irregular stem 노랗다. |
| 여러 가지 | many kinds | noun phrase | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 값이 싸다 | cheap | idiom/adjective phrase | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 디자인 | design | noun (loanword) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 튼튼하다 | sturdy | adjective | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 너무 | too much | adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 내다 | pay | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Recurs from Lesson 7's "treat/pay" sense. |
| 크레디트카드 | credit card | noun (loanword) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 받다 | accept | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 현금 | cash | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 물론 | of course | adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 깎다 | cut down (price) | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Bargaining verb, central to this lesson's culture point. |
| 가만있자 | let me see | idiom (filler) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Hesitation/thinking-pause discourse filler. |
| 점원 | salesperson | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 이태원 | Itaewon | proper noun | core | — | contemporary (source published 2000) | South Korea | local | grammar_reference | n/a | verified | Seoul shopping district, named in this lesson's own culture point as a haggling hotspot. |
| 한국 가게 | Korean store | noun phrase | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 양말 | socks | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 켤레 | pair | noun (counter) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 값을 깎다 | cut the price | verb phrase | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 넥타이 | necktie | noun (loanword) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |

### Grammar points

**The long negative form -지 않다.** An alternative to Lesson 1's short negation -안, attached
directly to a verb stem (분명하다→분명하지 않다 "unclear," 말하다→말하지 않다 "not speak," 놀다→놀지
않다 "not play"). Most verbs accept either form, but certain verbs — especially ones already
carrying complex morphology, e.g. past-tense 공부했습니다 or a progressive construction like 서
있다 — only accept the long form (안 공부했습니다 and 안 서 있다 are both explicitly marked
ungrammatical by the source, with 공부하지 않았습니다/서 있지 않다 as the only correct forms).

**The particle -만큼 for base comparison ("as much as").** Attaches to a noun used as a comparison
baseline (이 가방은 저 가방만큼 크다 "This bag is as big as that bag"; 내 친구는 나만큼 키가 커요 "My
friend is as tall as I am").

**The comparison particle 보다 (더) ("than").** Marks the standard of comparison; 더 is optional (한국
말이 영어보다 (더) 쉬워요 "Korean is easier than English"). Directly used in Dialogue 1's department-
store-vs-market comparison (신세계 백화점이 남대문 시장보다 더 좋을 것 같아요 "Sinsaekye seems better
than Namdaemoon Market").

**Superlative words 제일/가장.** Mark the greatest degree among three or more compared items (이것이
제일(가장) 비싸요 "This is the most expensive"; 롯데백화점이 가장 좋아요 "Lotte Department Store is
the best"). 제일 and 가장 are given as freely interchangeable.

**The sentence ending -ㄹ(을) 것 같다 ("seems/is likely to be").** Usable with any verb type; -ㄹ 것
같다 after a vowel-final stem, -을 것 같다 after a consonant-final stem (이것이 비쌀 것 같다 "This
thing seems to be expensive"; 여기가 시청일 것이다 "This place seems to be City Hall" — note the
copula-final variant 것이다).

**The irregular adjectival verb 어떻다.** Means "to be (some way)/(how)"; irregular across present/
past/future (어떻다→present 어때요, past 어땠어요, future 어떻겠어요) — a distinct irregular-conjugation
pattern flagged explicitly as such by the source.

**Culture point (p. 123): price haggling as a Korean market norm.** Bargaining is standard at
markets like Itaewon; the source explicitly cautions that shopkeepers often inflate prices in
advance of an expected discount, so a "discount" may only return the item to its true price (or
worse, still leave the buyer paying above the original price); department stores, by contrast, do
not haggle and sell at marked price, with occasional seasonal sales promotions instead.

**The ㅎ-irregular verb class.** Certain adjectival-verb stems (빨갛다 "red," 파랗다 "blue/green,"
노랗다 "yellow") drop their final ㅎ when forming a noun-modifier (빨갛다→빨간 가방/빨간 것; 파랗다→파란
가방/파란 것; 노랗다→노란 가방/노란 것). Once already established in context, the modified noun 가방
can be replaced by the pronoun 것 ("thing"). This is the ㅎ-irregular predicate class also documented
project-wide in the Basic/Intermediate Korean series, here illustrated specifically through color
terms.

**The contrastive conjunction -(으)나.** A less-colloquial alternative to Lesson 8's -지만, connecting
two clauses with contrasting values; -나 after a vowel-final stem, -으나 after a consonant-final stem
(이 물건은 좋으나 사지 않겠어요 "Although this merchandise is good, I won't buy it").

**The exclamatory ending -ㄴ(은/는)데요.** Marks interest/surprise/delight shared by speaker and
hearer; -ㄴ(은)데요 after adjectival verbs and the copula 이다, -는데요 after other (action) verbs (이
책은 값이 싼데요! "This book is cheap!"; 이것은 한국어책인데요! "This is a Korean book!"; 내 동생이 거기에
가는데요! "My younger brother goes there!"). This is a distinct grammatical function from the
-는데(요) conjunction/discourse-indirection device documented at length in `established/003`, `006`,
and Lesson 6 of this book — worth flagging as a case where the same surface morpheme -는데요 carries
two functionally distinct uses across sources.

**The exclusivity particle 만 ("only").** Attaches to nearly any sentence element (그 책만 주세요
"Give me only that book"; 동물원은 오늘만 문을 닫아요 "The zoo closes only today").

**The sentence ending -ㄹ(을)게요.** Attached to an action-verb stem or 있다, expresses the speaker's
intention in casual conversation (오늘 저녁은 제가 낼게요 "I'll treat you tonight"; 이 가방은 현금으로
지불할게요 "I'll pay for this bag in cash").

**Reading passage (p. 127): a haggling-outcome comparison anecdote.** Min Soo and John buy the same
kind of socks at different Itaewon stores for different negotiated prices (5,000원 vs. 4,000원 after
haggling), and separately, Min Soo fails to talk down an expensive watch's price while John
successfully haggles a necktie down to 12,000원 paid in cash — framed as a reading-comprehension
exercise (readers infer who got the better deal and who couldn't buy anything) directly illustrating
this lesson's own haggling culture point in a naturalistic narrative.

---

## Vocabulary and grammar — Lesson 11: 주말여행 (Weekend trip), pp. 128–135 (PDF 138–145)

**Boundary note (check-first duplicate-prevention applied).** This dispatch's assigned range ends
at PDF page 145 (printed p. 135), landing mid-way through Lesson 11 — its two Exercises blocks and
Reading passage (printed pp. 135–137, PDF 145–147) were found, on inspection, to already be covered
by the sibling `established/021_colloquial_korean_complete_part2.md` (its own header states it
covers "printed pages 1–135, Units 1–11 through the start of Unit 11's exercises" as this file's
scope, and its own body has a dedicated "Unit 11 tail (printed 136–137) — reading passage + key
words only" section). This file therefore stops at the two dialogues + full grammar-point content
through printed p. 135, matching the pre-existing sibling split exactly, rather than re-extracting
the reading passage — avoiding the exact kind of duplicate-extraction race the project's spec warns
against.

### Vocabulary (Dialogues 1–2, p. 129, 132–133)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 이번에 | this time | adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 토요일 | Saturday | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 일요일 | Sunday | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 설악산 | Mount Sorak | proper noun | core | — | contemporary (source published 2000) | South Korea | national | grammar_reference | n/a | verified | |
| 비행기 | airplane | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 기차 | train | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 편하다 | comfortable | adjective | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 안전하다 | safe | adjective | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 떠나다 | leave | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 새벽 | at dawn | noun/adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 늦게 | late | adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 돌아오다 | return | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 다녀오다 | go and come back (honorific) | verb (compound, honorific) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Used in 잘 다녀 오세요 "have a nice trip," echoing Lesson 5's usage. |
| 글쎄요 | let me see | idiom (filler) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Hesitation discourse filler, distinct lexeme from Lesson 10's 가만있자 but same function. |
| 무엇으로 | by what | pronoun + instrumental marker | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 실례합니다 | excuse me | idiom | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 기차표 | train ticket | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 팔다 | sell | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 매표구 | ticket booth | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 설악산행 | bound for Mt. Sorak | noun (destination-marked) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | See Grammar points: dependent noun -행. |
| 표 | ticket | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 장 | counting unit for tickets | noun (counter) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | See Grammar points. |
| 열차 | train | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Synonym of 기차, more formal/technical register (used for scheduled/named trains). |
| (플랫트)홈 | platform | noun (loanword, partly clipped) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 출발하다 | leave | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Synonym pair with 떠나다, given together by the source. |
| 잘 알았습니다 | understood well | idiom | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 들어오다 | enter | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |

### Grammar points

**The sentence ending -ㄹ(을)까 하다.** Marks a speaker's tentative plan; always used with action
verbs and 있다; -ㄹ까 하다 after a vowel-final stem, -을까 하다 after a consonant-final stem (일요일에
시내구경을 나갈까 합니다 "I'm planning on touring downtown on Sunday").

**The particle -(이)나 ("or").** Attaches to a noun to indicate a selection between options (부산이나
경주에 가겠어요 "I'll go to either Pusan or Kyongju").

**The conjunctive postposition -하고 ("and," noun-connecting).** Connects two or more nouns (오늘하고
내일은 비가 올겁니다 "Today and tomorrow it rains") — distinct from the comitative "-하고" ("with")
already introduced in Lesson 8, illustrating that the same particle covers both functions depending
on context.

**The compound verb 갔다 오다 ("have been to/have come back from").** Literally "went to a place and
came back from there"; tense is marked only on the second element 오다 (어디 갔다 오세요? "Where've
you been?"; 롯데백화점에 갔다 왔어요 "I've been to Lotte Department Store").

**Days of the week — full paradigm.** 월요일 (Mon) / 화요일 (Tue) / 수요일 (Wed) / 목요일 (Thu) / 금요일
(Fri) / 토요일 (Sat) / 일요일 (Sun) — each formed from a Sino-Korean weekday-element (월 "moon,"
화 "fire," 수 "water," 목 "wood," 금 "gold," 토 "earth," 일 "sun") + 요일 "day."

**Culture point (p. 132): Mount Sorak as a national tourist destination.** Granite peaks, valleys,
and autumn foliage draw both domestic and foreign tourists; designated a National Park with hotels,
inns, camp sites, and a 3,610-foot (1,100m) cable car connecting the park entrance to the summit;
Pisondae Plateau (legendary site of an angel's ascension) and Osaek mineral water (believed to
relieve digestive ailments) are named nearby points of interest — concrete sociocultural/folk-belief
content. About one hour from Seoul by air, four hours by train.

**The dependent noun -행 ("bound for").** Attaches directly to a destination noun (부산행 기차표
"ticket to Pusan," 서울행 기차표 "ticket to Seoul," 미국행 비행기표 "ticket to America").

**The noun counter -장.** Counts flat/paper items including tickets ("a piece of"); combination of
numeral + counter follows the counted noun (종이 한 장 "one piece of paper," 열차표 세 장 "three train
tickets," 비행기표 두 장 "two airline tickets").

**The relative clause marker -ㄴ(은)/는/ㄹ(을) — full tense-conditioned system.** Extends Lesson 8's
adjectival-verb noun modifier -ㄴ(은) to a complete relativization system covering all three tenses
and both action and adjectival verbs. Past tense: the relative marker attaches to the action-verb
stem itself (지나갔다+버스→지나간 버스 "the bus which passed"; 책을 읽었다+학생→책을 읽은 학생 "the
student who read the book"). Present tense: -는 attaches to the action-verb's dictionary stem
(지나가다+버스→지나가는 버스 "the bus that passes"; 책을 읽다+학생→책을 읽는 학생 "the student who reads
the book"). Future tense: -ㄹ(을) applies to both action and adjectival verbs alike (지나가다+버스→지나갈
버스 "the bus which will pass"; 도서관에서 공부하다+학생→도서관에서 공부할 학생 "the student who will
study at the library"). This is the fullest, most systematic relative-clause paradigm in the book so
far, explicitly built as a generalization of Lesson 8's narrower adjectival-only modifier.

**The progressive tense form -고 있다.** Preceded by an action verb, expresses ongoing action/process;
tense is marked on the auxiliary 있다, not the main verb (학생들이 지금 도서관에서 공부하고 있어요
"Students are now studying at the library" / 공부하고 있었어요 past-progressive "were studying").

**The sentence ending -(으)면 됩니다 ("all you have to do is...").** Usable with any verb type, offers
a suggestion for an appropriate action in context; -면 after a vowel-final stem, -으면 after a
consonant-final stem (지금 열차에 타시면 됩니다 "You only have to get on the train now"; 저를 따라
오시면 됩니다 "You only have to follow me").

Lesson 11's Exercises and Reading passage (printed pp. 135–137) are covered by the sibling
`established/021_colloquial_korean_complete_part2.md` — see this section's boundary note above.
