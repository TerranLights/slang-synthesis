# Korean — Established Vocabulary/Grammar: Elementary Korean, Lessons 1–4 (partial, of assigned 1–215)

**Source:** Ross King and Jae-Hoon Yeon, *Elementary Korean* (Tuttle Publishing), SOAS/Harvard
Yale-romanization-based course. Source file `source_reference/languages/Korean/06.Elementary
korean.djvu`, 429 pages total, no text layer (confirmed via `djvutxt` — vision-read from rendered
page images throughout).

**Assigned range vs. actual coverage — read this before using this file.** The dispatch assigned
printed pages 1–215 of 429 (the book's first half). This file covers **printed pages 1–50 only**
(front matter Lesson 1 "Basic Expressions," Lesson 2 "Korean Names," and Lesson 3–4 "Korean
Writing and Basic Pronunciation," through §4.10 Long and Short Vowels), plus a brief unstructured
look at the opening grammar of Lessons 5–6 (pages ~65, 85) taken while scouting the page-offset
formula, captured below as short notes rather than full extraction. **Pages 51–64 (rest of Lesson
4) and pages 51/65–215 (Lessons 5 onward in full) were NOT extracted and remain open** — a
follow-up dispatch should continue from printed page 51. This is stated explicitly per the
check-first/no-fake-completion discipline in `00_Reference_Extraction_Spec.md`; do not treat this
file as satisfying the full 1–215 assignment.

**Page-offset gotcha (worth recording for any follow-up dispatch on this book).** This djvu is
scanned as one page-image per physical page, not two-pages-per-spread. Empirically verified across
8+ sample points: **PDF/djvu page N shows printed page (N − 20)** for the whole range checked (PDF
21 → printed 1, PDF 25 → printed 5, PDF 30 → printed... — note an apparent sliver of the *facing*
page's running head is sometimes visible at the image's outer edge from ordinary book-scan
photography, which can look like a second page at a glance; the primary, fully-legible page content
on each image is what the formula above refers to). Front matter (roman-numeral pages, cast of
characters, preface) does not follow this formula and was not needed for this dispatch. Verify
empirically before trusting the offset in a follow-up — render a page and check its printed footer
number, the same discipline used here.

**Vision-reading confidence.** All pages in this range are clean, typeset, print-quality textbook
scans — no handwritten marginalia, no scan artifacts obscuring text, found anywhere in pages 1–50.
All entries below are Vision Reading Confidence `verified` unless individually flagged.

**Non-redundant-supplement note (checked against `established/001_basic_korean_part1.md`,
Byon's *Basic Korean*).** Lessons 1–2 (basic greeting formulas, honorific/polite-style
distinctions, Korean naming conventions) cover broadly the same territory as Byon's Units 1–2 but
with a genuinely different author's example set and phonetic-transcription-first pedagogy (this
book teaches basic expressions in Yale-style phonetic transcription *before* Hangul, per its own
stated design) — kept in full per the spec's "different author's independent examples are not
redundant by default" rule. Lesson 2's Korean-naming-conventions section (surname table, gendered
given-name syllables, the 씨/선생님/사모님 title system, the child-name diminutive -이 suffix) is
**new content not previously captured** in `established/`. Lessons 3–4 (Hangul/pronunciation) are
**mostly redundant** with Byon's Unit 1 "Reading Hangul" for the plain alphabet chart itself (not
re-transcribed here) — but this book's systematic phonological-rule treatment (batchim/final-
consonant neutralization "Gang of Seven," nasalization, the peculiarities of ㄹ, automatic post-
obstruent tensification, ㅎ-aspiration "leap-frogging," vowel length) is **more systematic and
explicit than anything captured from Byon**, so those rules are captured in full below as new
grammar points, while the raw consonant/vowel letter inventory itself is only summarized (already
fully covered by `established/001`).

---

## Vocabulary

### Lesson 1 — Basic Expressions I (p. 1–9)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 네 / 예 | yes | interjection | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Two free variants for "yes." |
| 아니오 | no | interjection | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 안녕하세요? | how are you / hello | phrase (Honorific Polite) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Lit. "are you at peace?"; used after a name+title, e.g. 김 선생님, 안녕하세요? |
| ...입니다 | I'm ... | phrase (Formal copula) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Self-introduction frame. |
| 만나서 반갑습니다 | nice to meet you | phrase (Formal) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Lit. "I meet you, so I am pleased." |
| 안녕히 가세요 | good-bye (to one leaving) | phrase (Honorific Polite) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Lit. "go in peace." Contrast next entry — the leaving/staying distinction is grammatically obligatory, not optional style. |
| 안녕히 계세요 | good-bye (to one staying) | phrase (Honorific Polite) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Lit. "stay in peace." |
| 수고하십니다 | hello (to someone working) | phrase (Formal) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | 수고 "hard work." |
| 수고하세요 | good-bye (to someone working) | phrase (Honorific Polite) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 수고하셨어요 | thank you for helping me / well done | phrase (Honorific Polite, past) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 처음 뵙겠습니다 | pleased to make your acquaintance | phrase (Formal, humble) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Lit. "I see you for the first time (formally)." 뵙- is the humble suppletive form of "see/meet." |
| 또 뵙겠습니다 | see you later (FORMAL) | phrase (Formal, humble) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | 또 "again" + 뵙겠습니다 "will humbly see." |
| 고맙습니다 / 감사합니다 | thank you | phrase (Formal) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Two free variants. |
| 천만에요 / 괜찮아요 | you're welcome / don't mention it | phrase (Polite) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Lit. "it's one of ten million (words)" — i.e. not worth mentioning. |
| 어서 오세요 | welcome! | phrase (Honorific Polite) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Lit. "come (in) right away." |
| 들어오세요 | come in! | phrase (Honorific Polite) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 앉으세요 | please take a seat | phrase (Honorific Polite) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 실례합니다 | excuse me (for what I am doing) | phrase (Formal) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Lit. "I am committing a discourtesy." Part of a 3-way tense set (see next 2 rows). |
| 실례했습니다 | excuse me (for what I did) | phrase (Formal, past) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 실례하겠습니다 | excuse me (for what I'm about to do) | phrase (Formal, prospective) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 미안합니다 / 죄송합니다 | I'm sorry / excuse me | phrase (Formal) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Lit. "I feel uneasy." 죄송 is the more deferential of the pair (not glossed as distinct register in-text but implied by later-lesson usage notes). |
| 아니오, 괜찮아요 | not at all, it's all right | phrase (Polite) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 여보세요 | hello! / hey there! | interjection | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Used on the telephone or peering into a dark house; also "look here!" |
| 시간이 다 됐습니다 | it's time (to begin/stop) | phrase (Formal) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | 시간 "time" + 다 "all, completely" + 됐습니다 "has become." |
| 또 봐요 | see you later! (POLITE) | phrase (Polite) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Less formal than 또 뵙겠습니다. |
| 그래요? / 그래요. | is that so? really? / that's so, really | interjection/phrase | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 용서하세요 | please forgive me | phrase (Honorific Polite) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 책을 보세요 | please look at your books | phrase (Honorific Polite) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Illustrates the -세요 polite-request ending attaching to a different verb base (보다 "see/look"). |
| 책 | book | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Explicitly noted in-text as translating variously as "book/a book/the book/books" — Korean nouns are not obligatorily marked for definiteness or number. |
| 질문 | question | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 영어 | English (language) | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |

### Lesson 2 — Classroom expressions & Korean Names (p. 15–23)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 첫 페이지를 보세요 | please look at the first page | phrase (Honorific Polite) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 책을 보지 마세요 | please don't look at your books | phrase (Honorific Polite, negative) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | -지 마세요 negative-imperative pattern. |
| 다음 페이지를 보세요 | please look at the next page | phrase (Honorific Polite) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 듣기만 하세요 | just listen, please | phrase (Honorific Polite) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 따라 하세요 | please repeat | phrase (Honorific Polite) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 다 같이 | all together | phrase | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 다시 한번 | one more time | phrase | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 대답하세요 | please answer | phrase (Honorific Polite) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 말하세요 | please say it | phrase (Honorific Polite) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 다시 말씀해 주세요 | please say it for me again | phrase (Honorific Polite, benefactive) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | 말씀 is the honorific noun for "words/speech"; 해 주세요 benefactive "do for me." |
| 크게 말씀해 주세요 | please say it loudly | phrase (Honorific Polite) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 천천히 말씀하세요 | please say it slowly | phrase (Honorific Polite) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 한국말로 하세요 | please say it in Korean | phrase (Honorific Polite) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 영어로 하지 마세요 | please don't say it in English | phrase (Honorific Polite, negative) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 알겠어요? / 네, 알겠어요 | do you understand? / yes, I understand | phrase (Polite) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 아니오, 모르겠어요 | no, I don't understand | phrase (Polite, negative) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 질문 있어요? | any questions? | phrase (Polite) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 네, 있어요 / 아니오, 없어요 | yes I have / no I haven't | phrase (Polite) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | First appearance of the 있다/없다 existential pair. |
| 십분만 쉽시다 | let's rest for ten minutes | phrase (Propositive) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | -읍시다 "let's" propositive ending. |
| 늦어서 죄송합니다 | sorry I'm late | phrase (Formal) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | |
| 먹었어요 | I've eaten | verb (past, Polite) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Cited as an example of a Korean sentence consisting of nothing but a verb — grammatically complete with no subject/object. |
| 선생님 | teacher / Mr./Mrs./Ms. (honorific title) | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | 선생 "teacher" + honorific particle 님; used as a title after a name, never with one's own name. |
| 씨 | Mr./Ms./title particle | particle/title | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Attaches after full name or given name only (not surname alone); the peer-register title. |
| 사모님 | Mrs./Madam | noun (honorific) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | Elegant Seoul usage; lit. "one's teacher's wife," extended to any superior's/prominent man's wife. |
| 미세스 김 / 미스 김 | Mrs. Kim / Miss Kim | noun (loanword phrase) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | verified | English-loanword workaround for specifying marital status, since 선생님 itself is unmarked for it. |
| 김 | Kim (surname) | proper noun | core | — | contemporary (source published 2000) | South Korea | national | grammar_reference | n/a | verified | Most common Korean surname; part of a surname-table sample (이, 박, 최, 장, 남, 홍, 허, 서, 배, 조, 노, 정, 전, 임, 오, 강, 안, 한, 심, 윤, 송, 신, 문 also listed). |
| 황보 / 독고 | Hwangbo / Tokko | proper noun | core | — | contemporary (source published 2000) | South Korea | national | grammar_reference | n/a | verified | Cited as rare two-syllable surnames. |
| 철수 / 철민 / 진호 / 호철 / 석헌 / 태호 | (male given names) | proper noun | core | — | contemporary (source published 2000) | South Korea | national | grammar_reference | n/a | verified | Sample male given names built from typically-masculine syllables 철, 호, 태, 석, 준, 훈, 섭, 식, 범. |
| 수미 / 미나 / 경애 / 진희 / 희정 / 민희 | (female given names) | proper noun | core | — | contemporary (source published 2000) | South Korea | national | grammar_reference | n/a | verified | Sample female given names built from typically-feminine syllables 미, 희, 나, 애, 자, 혜, 선, 경, 숙. |
| 복동이 | (diminutive child-name form) | proper noun | core | — | contemporary (source published 2000) | South Korea | national | grammar_reference | n/a | verified | 김복동 [kimbokton] → 복동이 [poktoŋi]: diminutive suffix -이 added to a consonant-final given name when addressing/referring to a child; vowel-final names (e.g. 진희) take no suffix. |

---

## Grammar points

### Lesson 1

**1.1 Styles of speech.** Korean marks the social relationship between speaker and addressee
directly on the verb ending (not, as in English, only through vocabulary/register choice). Two
independent axes are introduced: (1) speaking *to* a person — verb endings vary by the
relationship between speakers; (2) speaking *about* a person — separate honorific vocabulary/word
parts are used to show respect toward the person being discussed (never used for the speaker's own
actions). This book's "Major Speech Styles" chart crosses **Regular vs. Honorific** with **Polite
vs. Formal**: 해요 (Polite/Regular), 하세요 (Polite/Honorific), 합니다 (Formal/Regular), 하십니다
(Formal/Honorific) — the four styles the course teaches as its everyday-conversation core, using
the verb 하다 "do" as the paradigm example (해요/하세요/합니다/하십니다 differ only in ending, not
base).

**1.2 Word classes.** Korean verbs (which the source notes come at the **end** of nearly every
basic sentence) are inflected words: an invariant BASE plus variable ENDINGS carry all the
grammatical/social meaning (illustrated with 하- "do" + -ㅂ니다/-ㅆ습니다/-겠습니다 etc.). Korean
nouns, by contrast, are uninflected; PARTICLES (functionally comparable to English prepositions,
but postposed) optionally mark a noun's relationship to the rest of the sentence. Korean nouns
carry no obligatory number or definiteness marking (책 = "book/a book/the book/books" depending on
context) — flagged explicitly as a systematic typological difference from English.

### Lesson 2

**2.1 Korean sentence patterns (word order by informational weight, not grammatical role).** The
verb is the one obligatory sentence element and always comes last; a bare verb form (e.g. 먹었어요
"I've eaten") is a grammatically complete sentence. The source frames Korean constituent order as
governed by *importance/newness of information* rather than fixed grammatical slots: elements
closer to the sentence-end are more essential, and old/already-established information is
routinely dropped rather than re-stated with a pronoun (contrasted directly with English, which
obligatorily reintroduces *he/it* — a Korean reply to "John bought a new suit" can simply be "When
bought?" with both subject and object omitted). New information (especially a new object) clusters
near the verb.

**2.2 Korean names.** Family name precedes given name (reverse of common English order); a title
always comes after the full name or after just the given name (선생님) or surname (also possible
with 선생님) — contrast 김 선생님 "Mr. Kim" where the title follows a bare surname. Most family
names are one syllable (a minority, e.g. 황보, 독고, have two); given names are usually two
syllables when the surname is one (rarely one syllable, e.g. 허웅, 백철, 김구). Certain syllables
skew strongly to one gender in given names (masculine: 철, 호, 태, 석, 준, 훈, 섭, 식, 범; feminine:
미, 희, 나, 애, 자, 혜, 선, 경, 숙) though this is only a rule of thumb — 희 [hiy] occurs in names of
both genders. The title 씨 attaches to a full name or a given name alone (peer register); 선생님
attaches to a full name or surname alone and is explicitly marked as increasingly preferred over
bare 선생 in contemporary usage. Explicit **caution box**: Western names may use either order
(애니 스미스입니다 or 스미스 애니입니다, both acceptable for "I'm Annie Smith"), but Korean names
must always use Korean order (only 김복동입니다, never *복동김입니다).

### Lessons 3–4 (Korean Writing and Basic Pronunciation) — phonological rules

The raw Hangul consonant/vowel letter inventory and syllable-block writing system are not
re-transcribed here (redundant with `established/001`'s Unit 1 treatment). The following rules,
however, are more systematically laid out here than previously captured and are kept in full:

**4.1 Three-way stop contrast.** Korean plain stops each have three phonation types, illustrated
with true minimal sets: 불 "fire" (lax) / 풀 "grass" (lax aspirated) / 뿔 "horn" (tense
unaspirated) for p; 달 "moon" / 탈 "mask" / 딸 "daughter" for t; 개 "dog" / 캐 "digs out" / 깨
"sesame" for k; 자요 "sleeps" / 차요 "is cold" / 짜요 "is salty" for č. This three-way laryngeal
contrast (not a voicing contrast, as the source stresses) is comparable in unfamiliarity for
English speakers to French's or Spanish's accent-driven distinctions.

**4.2 Non-release of final consonants ("batchim").** Korean never releases a syllable-final
consonant unless required to by a following vowel-initial particle/ending or by the copula -이에요.
Unreleased p/t/k are notoriously hard for English speakers to hear ("swallowed" consonants).

**4.3–4.4 "The Gang of Seven" — final-consonant neutralization.** Only seven consonant sounds can
ever be pronounced syllable-finally: ㄹ ㅁ ㄴ ㅇ (l, m, n, ŋ) and ㅂ ㄷ ㄱ (p, t, k). Any other
syllable-final consonant letter is neutralized to one of these seven **even when a vowel-initial
non-particle word follows** (this is the key rule: neutralization is not just a pre-pause
phenomenon). A concrete mapping table: ㅂ,ㅍ,ㅃ → ㅂ; ㄱ,ㅋ,ㄲ → ㄱ; ㄷ,ㅌ,ㅈ,ㅊ,ㅅ,ㅆ,ㅎ → ㄷ. The source
flags that most "unreleased t" sounds heard in Korean are actually a final ㅅ (s) in disguise —
e.g. 옷 "garment" → [ot]. Worked example: 닭고기 "chicken (as meat)" → [닥꼬기] takkogi (ㄺ → ㄱ, plus
automatic tensification, see 4.7).

**4.5 Nasalization ("the Gang of Seven gets up your nose").** When an unreleased p/t/k precedes a
following m or n (including an l that has itself become n per 4.6), it surfaces as the
corresponding nasal: p→m, t→n, k→ŋ. Examples: 합니다 [hamnida] "does it," 먹는다 [məŋnɨnda] "eats
it," 독립 → 독닙 → [동닙] tongnip "independence," 합리 → 합니 → [함니] hamni "rationality." The rule
is explicitly noted to also apply to any t that itself derives from tʰ, čʰ, č, s, ss, or even h
(e.g. 있었네 → [이썬네] issənne "she had it!").

**4.6 Peculiarities of ㄹ.** (1) n adjacent to l (either order, across a syllable break) surfaces
as a doubled ll: 일년 → [일련] illyən "one year," 신라 → [실라] Silla. (2) l preceded by a consonant
other than l or n surfaces as n: 심리 → [심니] šimni "psychology." (3) In Sino-Korean words, l
followed by t/č/s doubles that following consonant to tt/čč/ss: 철도 → [철또] čʰoltto "railway,"
결정 → [결쩡] kyəlččəŋ "decision," 설사 → [설싸] səlssa "diarrhea" — flagged as unpredictable from
spelling alone (no way to tell which words are Sino-Korean), so the book commits to bracketing
actual pronunciation in square brackets at first occurrence of any affected word throughout the
rest of the course.

**4.7 Automatic (post-obstruent) tensification.** After a syllable-final p, t, or k, a following
plain ㅂㄷㅈㄱㅅ automatically tensifies to ㅃㄸㅉㄲㅆ: 약방 → [약빵] yakppang "drugstore," 작다 →
[작따] čaktta "is little," 십삼 → [십쌈] šipssam "thirteen."

**4.8 "Leap-frogging" ㅎ.** ㅎ (h) can combine with an adjacent plain ㅂㄷㅈㄱ (in either order) to
produce the corresponding aspirated consonant ㅍㅌㅊㅋ: 좋고 "is good, and..." is pronounced 조코
čʰoko; 좋다 "is good" is pronounced 조타 čʰota.

**4.9 ㅌ before 이.** Morpheme/word-final aspirated ㅌ (tʰ) palatalizes to ㅊ (č) before 이: 같이
"together" is pronounced 가치 kačʰi; 밭이 "field" + subject particle 이 is pronounced 바치 pačʰi.

**4.10 Long and short vowels.** Standard modern spelling does not mark vowel length, and this
textbook does not mark it either, but many speakers still distinguish minimal pairs by vowel
length alone (length is suppressed especially away from phrase-initial position). True minimal
pairs cited: 밤 "evening" (short) vs. 밤̄ "chestnut" (long); 굴 "oyster" vs. "cave"; 말 "horse" vs.
"words, speech"; 눈 "eye" vs. "snow." (일 "one" vs. 일̄ "affair, work" also cited earlier in the
same discussion.) This is a genuinely new lexicographic/phonological finding not previously
captured in `established/` — several established core-vocabulary homophone pairs in this project's
existing Korean vocabulary tables (e.g. 눈 "eye"/"snow", 말 in other entries) may be distinguishable
in careful/citation-form speech by vowel length alone even though ordinary orthography never shows
it.

### Brief forward-look (Lessons 5–6, NOT fully extracted — captured only incidentally)

Seen only in passing while verifying the page-offset formula (pages ~65, ~85); **not** a systematic
extraction and should be redone properly by a follow-up dispatch:
- **Lesson 5** (copula/equational sentences): the negative copula 아니에요 (with optional subject
  particle 이~가 on the preceding noun, "It isn't a newspaper" 신문(이) 아니에요); negative
  equational sentences can host two subject-marked noun phrases where English would use subject +
  complement. The particle 도 "too, also, even" — always attaches with one invariant shape
  regardless of preceding vowel/consonant, and in a negative sentence still does the "too" work
  where English switches to "either."
- **Lesson 6**: a three-way functional breakdown of the topic particle 은~는 — **stage-setting**
  (introduces what the sentence is about), **contrast** (two noun phrases marked 은~는 in parallel
  clauses to set up an explicit contrast, e.g. 왼편에는...오른편에는... "on the left...on the
  right..."), and **old business** (a subject already introduced with 이~가 reverts to 은~는, or
  drops out entirely, on subsequent mention) — a clean three-part pedagogical framing of 은~는's
  function not seen articulated this explicitly in prior `established/` Korean grammar files.
  Also: answering negative questions in Korean uses 네/아니오 to agree/disagree with the
  *negativity* of the question, the reverse of English yes/no logic.
