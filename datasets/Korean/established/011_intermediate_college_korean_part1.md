# Korean — Established Vocabulary/Grammar: *Intermediate College Korean*, Part 1 (Lessons 1-16 + partial Lesson 17)

**Source:** Clare You and Eunsu Cho, *Intermediate College Korean* (University of California Press,
2002), PDF pages 1-190 of 376 (front matter + Lessons 1-16 in full, Lesson 17 through its vocabulary
and grammar notes 1-4 — grammar note 3's forward-referenced "40 most common causative verbs" chart
and grammar notes 5+ fall past PDF page 190 and are reserved for the part-2 dispatch). Printed-page-
to-PDF-page offset verified by direct inspection: printed p. 1 (Lesson 1's start) = PDF p. 21
(offset +20), confirmed against the book's own Table of Contents lesson-start listing. **Note: the
offset drifts by one page somewhere between Lesson 1 and Lesson 17** (PDF p. 190 is printed p. 169,
i.e. offset +21 there, not +20) — likely an extra unnumbered/blank page inserted partway through;
flagged here for the part-2 dispatch rather than assumed away, since a fixed-offset estimate for
locating Lesson 17's remainder should be re-verified by direct inspection rather than arithmetic
alone, per the spec's page-range-verification guidance.

**PDF gotcha — a new type, distinct from the Wave-1 `+36266` cipher.** This PDF's Korean text uses
~20 separate `KHMyungjoRegularXX`-named embedded Type 1C font subsets (not a single CID/Identity-H
font), each apparently covering a different jamo/glyph range with its own (bogus) `ToUnicode` CMap.
`pdftotext`/PyMuPDF's text layer decodes every Hangul glyph into unrelated Latin-1-supplement/Mac-OS-
Roman-range punctuation and symbol characters (e.g. `Ü‘À f∑√L` for what is actually a Lesson title),
not CJK codepoints — so the Wave-1 fixed-offset decode does not apply here (verified: extracted
codepoints fall in `U+00A1`-`U+2265`, nowhere near the Hangul syllable block, ruling out any single
additive offset). English prose extracts cleanly via the text layer (used to locate section
boundaries and lesson page ranges). All Korean content — vocabulary, dialogue, grammar-note example
sentences — was vision-read from 220dpi page-image renders instead. No handwritten marginalia found
anywhere in this range.

**Coverage-scope note (comprehensive-but-not-exhaustive, per the spec).** Given this chunk's real
size (170 rendered pages across 16+ lessons), full narrative/dialogue prose, the optional "reading"
passages, and all exercise sections (drills, comprehension questions, pattern-practice prompts) were
**not** vision-read line-by-line — per the coverage rule these are the book's pedagogical padding
and don't introduce vocabulary/grammar beyond what the lesson's own Vocabulary and Patterns and
Grammar Notes sections already state. Lesson 1 (short, 8 pages total) was read in full as a
calibration pass and confirms this: its exercises introduced no vocabulary beyond the lesson's own
vocabulary list. For Lessons 2-16, the extraction targets **every lesson's full Vocabulary list**
(the book's own bounded "단어 VOCABULARY" box) plus **every lesson's full Patterns and Grammar Notes
section** (그 문형과 문법), which is where the coverage rule's "every grammar point" and "every
distinct vocabulary item" content actually lives. Where a lesson has a supplementary "optional
reading" with its own separate vocabulary box, that is captured too and marked as such.

**Non-redundant-supplement dispatch note.** `established/001` (Byon, *Basic Korean*) and
`established/003`/`004` (Byon, *Intermediate Korean*) were skimmed first. This book (You & Cho,
UC Berkeley/Michigan, 2002) is an independently authored third source covering overlapping
elementary/intermediate grammatical territory (case particles, tense, sentence endings, honorifics)
but with its own vocabulary selection oriented toward "college- and adult-level words... rather than
daily survival words" (the book's own stated design goal, Preface p. x) and a distinctive
narrative-driven format (a Korean-American student's year in Korea) that surfaces different concrete
vocabulary (computer terms, martial-arts terms, current-events/social-issue vocabulary) than the
Byon books' more conventional unit structure. Per the spec's "a third independently-authored source
is not redundant by default" guidance, vocabulary and grammar notes are extracted in full per
lesson rather than skipped or merely sampled; grammar-point notes that are functionally identical
in substance to what `001`/`003`/`004` already documented (e.g. basic case particles, `-았/었-` past
tense) are captured briefly with a cross-reference rather than re-explained at length, while
grammar points/sentence patterns not previously documented get full treatment.

---

## Lesson 1 — 비행기에서 (On the Airplane) — printed pp. 1-7, PDF pp. 21-27

Full lesson read (narrative, dialogue, vocabulary, grammar notes, exercises) as a calibration pass;
exercises introduced no vocabulary beyond the list below.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가지고 오다 | to bring | verb (compound, 가지다 "to hold/have" + 오다 "to come") | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 2. |
| 거의 | almost, mostly | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 2. |
| 곧 | immediately | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 2. |
| 공항 | airport | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 2. |
| 괜찮다 | to be all right; 괜찮아요 "That's OK, no problem" | verb (descriptive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 2. |
| 구름 | cloud | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 2. |
| 길 | way, street; 가는 길 "on the way to" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 2. |
| 날다 | to fly | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 2. |
| 낮잠 | noon nap | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 2. |
| 넓다 | to be wide; 넓은 "wide" | verb (descriptive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 2. |
| 답답하다 | to be frustrated | verb (descriptive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 2. |
| 대 | to, versus (ratio marker); 천 대 일 "1000:1" | dependent noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 2. |
| 도착하다 | to arrive; 도착 "arrival" | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 2. |
| 바꾸다 | to change, to exchange | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 2. |
| 밖 | outside | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 2. |
| 받다 | to receive | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 2. |
| 배우다 | to learn | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 2. |
| 백 | hundred | numeral | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 2. |
| 보이다 | to be seen; 보다 "to look at, to watch" | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 2. |
| -불; 달러 [딸러] | dollar | counter/noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 2. Loanword (딸러/달러 from English "dollar"); 불 is the Sino-Korean counter. |
| 비행기 | airplane | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 2. |
| 빈 | empty; 비다 "to be empty" | adjective/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 2. |
| 서울 | city of Seoul | proper noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 2. |
| 세관 | customs office | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 2. |
| 시끄럽다 | to be loud, to be noisy | verb (descriptive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 2. |
| 시작하다 | to begin, to start; 시작 "beginning, starting" | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 2. |
| 아기 | baby (애기 colloquial variant) | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 2. Source itself flags 애기 as the colloquial register variant of 아기. |
| 아뇨 | contraction of 아니오 | interjection | colloquial | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 2. |
| 아름답다 | to be beautiful | verb (descriptive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 2. |
| 아주 | very | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 2. |
| 아직 | still, yet | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 2. |
| 앉다 [안따] | to sit | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 3. |
| 여름 방학 | summer vacation | noun (compound) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 3. |
| 여행 | travel | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 3. |
| 여행자 수표 | traveler's check | noun (compound) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 3. |
| 오른쪽; 바른쪽 | right side | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 3. Two synonyms given. |
| 왼쪽 | left side | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 3. |
| 우선 | first of all, before other things | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 3. |
| 울다 | to cry | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 3. |
| 이렇게 | like this | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 3. |
| 자기 | self, one's own | pronoun/noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 3. |
| 자리 | seat, place, room | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 3. |
| 젊은 [절믄] | young; 젊다 "to be young" | adjective/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 3. |
| 좌석 | seat | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 3. |
| 중년 | middle age | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 3. |
| 착하다 [차카다] | to be good-natured, to be good-hearted | verb (descriptive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 3. |
| 창; 창문; 유리창 | window | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 3. Three synonyms given (plain/compound/"glass window"). |
| 처음 | first; 처음으로 "for the first time" | noun/adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 3. |
| 출발하다 | to start, to depart; 출발 "starting, departure" | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 3. |
| 크다 | to be big, to be large | verb (descriptive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 3. |
| 타다 | to ride, to get on | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 3. |
| 태어나다 | to be born | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 3. |
| 택시 | taxi | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 3. Loanword (English). |
| 통과하다 | to pass, to pass through | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 3. |
| 편히 | comfortably; 편하다 "to be comfortable" | adverb/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 3. |
| 필요하다 | to be needed, to be necessary | verb (descriptive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 3. |
| 하늘 | sky | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 3. |
| 한- | about; 한 이삼일 "about two or three days" | prefix | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 3. |
| 현금 | cash | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 3. |
| 현배 | Hyun-bae (man's name) | proper noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 3. The book's recurring protagonist. |
| 환율 [환뉼] | exchange rate | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 3. |
| 환전소 | exchange office | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 3. |

### Grammar points

**1. N. + (이)라(서)** — "as ... being," "since it is," "because it is." Similar to `-(이)기 때문에`
or `-(이)어서`; more colloquial than either. p. 3-4.

**2. A.V. + (으)려고 하다** — "to intend to," "to plan to," "going to." Indicates intention or plan;
the source cross-references its own companion beginner volume (*College Korean*, L17 GN5). p. 4.

**3. Sentence ending V. + 네요** — informal ending marking the speaker is making an observational
remark, not soliciting information or a response. p. 4.

**4. V. + ㄹ/을 거예요** — "I think/expect it will..." A colloquial form of `-을 것이에요`; an
intimate-register statement ending for a future/expected event, carrying an implication of the
speaker's own expectation. Formal counterpart: `-ㄹ/을 겁니다`; intimate-short counterpart:
`-ㄹ/을 거야`. p. 4-5.

**5. V. + 어/아야 하다 / V. + 어/아야 되다** — "must," "have to," "should." Both forms indicate
obligation or requirement; presented as interchangeable. p. 5.

**6. Special use of -이/가 and -을/를** — A dedicated note on Korean transitivity mismatches with
English: some English-transitive-seeming verbs are grammatically intransitive in Korean and take the
subject marker -이/가 (필요하다 "to need," 되다 "to become," 있다 "to have"); conversely, some
English-intransitive-seeming verbs take the direct-object marker -을/를 in Korean (가다 "to go," 걷다
"to walk," 날다 "to fly," 다니다 "to attend"). p. 5-6. This is a genuinely useful explicit
cross-linguistic mismatch note not seen phrased this way in `established/001`/`003`/`004`.

---

## Lesson 2 — 서울 (Seoul) — printed pp. 9-19, PDF pp. 29-39

Vocabulary and grammar-notes pages vision-read in full, including the lesson's own "Extra Reading"
(읽기: 서울 이야기, "The Story of Seoul") passage and its separate vocabulary box (p. 13-14).
Narrative/dialogue and exercises not separately transcribed (no new vocabulary found beyond the
lists below).

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가깝다 | to be close, to be near; 가까운 "near" | verb (descriptive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 10. |
| 같이 [가치] | together (with) | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 10. |
| 걱정하다 | to worry; 걱정 "concern, worry" | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 10. |
| 건물 | building | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 10. |
| 걷다 | to walk | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 10. Irregular ㄷ-verb (cf. `established/002`'s irregular-predicate class treatment). |
| 걸리다 | to take (time) | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 10. |
| 굉장히 | very, enormously, wonderfully; 굉장하다 "to be grand" | adverb/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 10. |
| 교통 | traffic, transportation | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 10. |
| 구경하다 | to see, to sightsee; 구경 "sightseeing" | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 10. |
| 그래 | Yes, Sure, I'll do so; 그래? "Is that so?" | interjection | colloquial | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 10. Nonpolite/intimate-register response particle. |
| 그럼 | Yeah, Sure, Certainly, Of course, If so, Well then | interjection | colloquial | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 10. |
| 기다리다 | to wait (for) | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 10. |
| 날 | day (used only with modifiers, as in 생일날 "birthday") | noun (bound) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 10. |
| 날씨 | weather | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 10. |
| 남산 | Nam-san Mountain | proper noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 10. |
| 너무 | too (much, little) | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 10. |
| -네 | family (of someone); 홍부네 "Hŭngbu's family/home" | suffix | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 10. |
| 다니다 | to come and go, to walk around, to go around | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 10. |
| 멀다 | to be far | verb (descriptive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 10. |
| 모르다 | not to know | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 11. Irregular 르-verb. |
| 별로 | (not) very, (not) much (followed by negative verb) | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 11. |
| 복잡하다 | to be complex, to be crowded | verb (descriptive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 11. |
| 비 | rain; 비가 오다 "to rain" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 11. |
| 빨리 | quickly, hurriedly | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 11. |
| 서울역 | Seoul Station; 역 "stop, station" | proper noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 11. |
| 서투르다 | to be clumsy, to be unskilled; 서투른 영어 "broken English" | verb (descriptive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 11. |
| 수도 | capital city (Sino-Korean, the formal word for a nation's capital) | noun | formal | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 11. Source itself flags this as the Sino-Korean/formal register term. |
| 시대 | time, age | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 11. |
| 신발; 신 | shoes | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 11. Two synonyms given. |
| 아마 | maybe | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 11. |
| 여기 저기 | here and there | adverb (phrase) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 11. |
| 옛날 [옌날] | ancient times, old days | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 11. |
| 오래되다 | to be old, to be a long time (since) | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 11. |
| 오후 | p.m., afternoon | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 11. |
| 은영 | Eun-young (woman's name) | proper noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 11. |
| 잊어버리다 | to forget (completely); 잊다 "to forget" | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 11. |
| 정말 | really, indeed | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 11. |
| 좋다 [조타] | to be good | verb (descriptive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 11. |
| 지금 | present time, now | noun/adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 11. |
| 지하철 | subway | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 11. |
| -쯤 | about | suffix | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 11. |
| 편한 | comfortable; 편한 신 "comfortable shoes"; 편하다 "to be comfortable" | adjective/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 11. |
| -하고 | with (colloquial for 와/과) | particle | colloquial | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 11. Source itself flags 하고 as the colloquial counterpart of the formal 와/과 conjunctive-comitative particle. |
| 혼자 | alone, by oneself | adverb/noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 11. |
| 힘들다 | to be difficult, to be hard | verb (descriptive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 11. |

**Extra Reading vocabulary (읽기: 서울 이야기, p. 13-14):**

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가운데 | in the middle (of) | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 13. |
| 강 | river | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 13. |
| 계속 | continuously; 계속하다 "to continue"; 계속되다 "to be continued" | adverb/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 13. |
| 넘다 [넘따] | to exceed, to be more than | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 13. |
| 다르다 | to be different | verb (descriptive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 13. Irregular 르-verb. |
| 다리 | bridge; leg | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 13. Homonym pair. |
| 도시 | city | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 13. |
| 만들다 | to make | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 13. |
| 모습 | appearance, figure, look | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 13. |
| 박물관 [방물관] | museum | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 13. |
| -번째 | rank or position in a series; 첫 번째 "first place," 두 번째 "second place" | suffix (ordinal counter) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 13. |
| 산 | mountain | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 13. |
| 살다 | to live, to be inhabited | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 13. |
| 세계 | world | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 13. |
| 스무(개) | twenty (items) | numeral (native counting series) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 13. |
| 약 | approximate, about | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 14. |
| 어렵다 | to be hard, to be difficult | verb (descriptive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 14. Irregular ㅂ-verb. |
| 여러 가지 | different kinds, various kinds | noun phrase | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 14. |
| 운전하다 | to drive (a car) | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 14. |
| 이야기 | story, tale; 이야기하다 "to converse" | noun/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 14. |
| 조선 | Chosŏn dynasty (1392-1910) | proper noun | core | — | contemporary (source published 2002) | attested (historical, 1392-1910) | Korea | national | grammar_reference | n/a | verified | p. 14. |
| 천만 | ten million | numeral | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 14. |
| 한강 | Han River | proper noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 14. |
| 현재 | present (time), currently | noun/adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 14. |
| 흐르다 | to flow, to run | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 14. Irregular 르-verb. |

### Grammar points

**1. Nonpolite (intimate or plain) style of speech** — A dedicated systematic treatment (p. 14-16)
of the register `established/003`'s Unit 1 already introduced as one of Korean's speech levels, but
here given a full cross-tabulated paradigm the sibling files didn't reproduce in this form: a
"Sentence Type × Tense" chart (statement/question/"let's"/command/exclamation × present/past/future)
giving every nonpolite sentence-ending allomorph in one table (p. 15, reproduced structurally below,
examples paraphrased per copyright discipline). Nonpolite style = intimate/plain style, used among
social equals, superiors to subordinates, and in intimate relationships.

  - Statement: `-(어/아)`/`-(이)야` (present); `V.+었/았어`, `N.+이었어/였어` (past); `-ㄹ/을거야`,
    `N.+ㄹ/일거야` (future).
  - Question: `-(어/아)?`/`-니?(-냐?)` (present, also `V.+니?`/`N.+(이)니?`); past and future forms
    mirror the statement paradigm with a question intonation/particle.
  - "Let's" (청유문): `-자` (present only; no past/future — semantically incoherent for a
    proposal).
  - Command (명령문): `-(어/아)`, `-(어/아)라`, `-너라/-거라` (present only).
  - Exclamation (감탄문): `-구나!` (present, also `V.+(는)구나!`); `V.+었/았구나!`/`V.+었/았다!`
    (past); `V.+겠구나!`/`V.+겠다!` (future/conjectural).

**2. V. + ㄹ/을까(요)?** — "would it...?," "do you think it will...?" A single ending covering three
distinct pragmatic functions depending on grammatical subject: (a) subject *we* → inviting a
yes/no answer, "shall we...?"; (b) subject third person → asking for the listener's opinion, "do you
think...?"; (c) subject *I* → asking for advice, "shall I...?" p. 16-17.

**3. V. + (으)니까** — "because," "since," "as," "for." Causal connective, often reduced by omitting
까 to `-(으)니`; used specifically with a question or a "let's"-type sentence (distinguishing it
functionally from other causal connectives like `-어서`, which don't combine as freely with commands/
proposals). p. 17-18.

**4. A.V. + ㄹ/을게(요)** — "I/we will..." Informal/colloquial ending indicating the speaker's own
intention specifically (not a shared or listener intention). p. 18.

**5. V. + ㄴ/은/는/ㄹ/을 것** — "-ing," "to...," "the fact that..." The nominalizing modifier-plus-
것 construction shown across all three tenses (배우는 것/배운 것/배울 것 = "thing(s) being
learned/learned/to learn"). Explicitly notes the colloquial contraction 것이 → 게 (단어를 배우는 게
많다). p. 18.

**6. V. + 지 알다 / V. + 지 모르다** — "to know if/whether" / "not to know if/whether." 알다/모르다
combine with `-지` to mean "how to" or "if/whether"; when preceded by a question word (언제/어디/왜/
누가/어떤/무슨/무엇), the construction asks specifically when/where/why/who/which/what. A full verb-
type × tense paradigm table (descriptive verb / action verb / noun, × present/past/future) is given
on p. 19, each with its own connecting-morpheme allomorph (-ㄴ/은지, -는지, -ㄹ/을지 for descriptive
verbs by tense; -는지, -었/았는지, -ㄹ/을지 for action verbs; -ㄴ/인지, -(이)었는지, -ㄹ/일지 for
nouns). p. 18-19.

---

## Lesson 3 — 첫날 (The First Day of Class) — printed pp. 23-30, PDF pp. 43-49

Vocabulary (main + Extra Reading "한국 대학의 연수 프로그램," "Korean Universities' Study/Training
Programs for Foreigners") and full grammar notes vision-read; narrative/dialogue/exercises not
separately transcribed.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 간단히 | briefly, simply; 간단하다 "to be simple" | adverb/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 24. |
| 강의 | lecture | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 24. |
| 강의실 | lecture hall, classroom | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 24. |
| 같다 | to be identical, to be equal; -것 같다 "it seems, it looks" | verb (descriptive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 24. |
| 개학식 | orientation; 개학하다 "to begin (semester)" | noun/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 24. |
| 교수 | professor | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 24. |
| 기웃기웃 | craning, peeking in; 기웃기웃하다 "to crane, to peek in" | adverb (onomatopoeic/mimetic)/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 24. Mimetic (의태어) form. |
| 남미 | South America | proper noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 24. |
| 늦다 | to be late | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 24. |
| 대화 | dialogue, conversation | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 24. |
| 들여다 보다 | to look into, to peek in | verb (compound) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 24. |
| 모두 | all, in all, all together | adverb/noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 24. |
| 물어 보다 | to try asking; 묻다 "to ask" | verb (compound) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 24. 묻다 is an irregular ㄷ-verb. |
| 밥 | cooked rice, meal | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 24. |
| 북미 | North America | proper noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 24. |
| 샤워하다 | to take a shower | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 24. Loanword (샤워 < English "shower"). |
| 설명 | explanation; 설명하다 "to explain" | noun/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 24. |
| 소개하다 | to introduce; 소개 "introduction" | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 24. |
| 수업 | instruction, lessons, class | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 24. |
| 실례이다 | to not follow proper etiquette; 실례지만 "Excuse me,..." | verb | formal | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 24. Politeness-formula lexical item. |
| 아시아 | Asia | proper noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 24. |
| 어디 | where | pronoun (interrogative) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 24. |
| -에 대해(서) | about, concerning | particle (compound) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 24. |
| 연수 | study and training | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 24. |
| 유럽 | Europe | proper noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 24. |
| 이용하다 | to utilize, to make use of, to use; -을/를 이용하여 "by utilizing" | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 24. |
| 주고 받다 | to share, to exchange (literally, to give and take) | verb (compound) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 24. |
| 중요한 | important; 중요하다 "to be important" | adjective/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 24. |
| 참 | very; "By the way," "Say" | adverb/interjection | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 24. |
| 참석하다 | to attend, to participate; 참석 "attendance" | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 25. |
| 첫- | first; 첫날 "first day" | prefix | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 25. |
| -층 | floor; 3층 "third floor" | counter | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 25. |
| 프로그램 | program | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 25. Loanword (English). |
| -호실 | room number; 2호실 "room 2" | counter | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 25. |
| 호주 | Australia | proper noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 25. |
| 회화 | conversation; 회화 시간 "conversation class" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 25. |

**Extra Reading vocabulary (읽기: 한국 대학의 연수 프로그램, p. 25):**

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 각자 | each person, individual, individually | noun/adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 25. |
| 교포 | Koreans residing abroad, overseas Koreans | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 25. |
| 국제 | international; 국제 학생 기숙사 "international student dormitory" | noun (modifier) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 25. |
| 기간 | time period | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 25. |
| 끝마치다 [끈마치다] | to finish, to complete (transitive) | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 25. |
| 대개; 대개는 | mostly, in general | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 25. |
| 머물다 | to stay (from 머무르다) | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 25. |
| 물론 | of course | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 25. |
| 문화 | culture | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 25. |
| 민박 | homestay; 민박하다 "to stay with a family" | noun/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 25. |
| 보통 | ordinary, common, usual, average | adjective/adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 25. |
| 생활하다 | to live, to exist; 생활 "life, livelihood" | verb/noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 25. |
| 알아 보다 | to find out, to look up, to check out | verb (compound) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 25. |
| 여가 | leisure | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 25. |
| 오전 | a.m., morning | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 25. |
| 외국인 | foreigner; 외국 "foreign country" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 25. |
| 위하여 | for (the sake of) | adverb (connective) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 25. |

### Grammar points

**1. 첫 + N.** — "first," "beginning." Prefix/modifier meaning "first" or "beginning" (첫 번째
"first place," 첫날 "first day," 첫눈 "first snow," 첫사랑 "first love," 첫째 "first (of all)").
p. 26.

**2. A.V. + 고 나서** — "after doing...," "having done..." Colloquial connective marking completion
of an action followed by another; close in meaning to `-ㄴ/은 후에`. p. 26.

**3a. V. + 거나** / **3b. N. + (이)나** — "either (do this)... or (do that)..." / "either (this)...
or (that)..." `-거나` links two or more events/actions; `-(이)나` links two or more alternative
items/nouns. p. 26-27.

**4. A.V. + ㄹ/을래(요)?** — "Will you...?," "Are you...?" (question, rising tone) / **A.V. + ㄹ/을래
(요).** — "I will..." (statement, level tone). Used in casual/intimate conversation; the same ending
serves as both question and statement depending on intonation alone. p. 27.

**5. V. + (어/아)도 돼요?** — "Is it all right if/to...?," "Is it okay if/to...?" Informal/casual
permission-request construction. Source explicitly contrasts the full positive/negative response
paradigm: `네, ...-(어/아)도 돼요`/`네, ...-(어/아)도 괜찮아요/좋아요` ("yes, it's fine") vs.
`아니오, ...-(으)면 안 돼요` ("no, one must not..."). p. 27-28.

**6. V. + ㄴ/은/는/ㄹ/을 것 같다** — "it seems/appears...," "it is/looks as though..." Sentence
ending expressing the speaker's own opinion/inference, often translating as English "I think...".
p. 28.

---

## Lesson 4 — 아르바이트 (Part-Time Job) — printed pp. 32-37, PDF pp. 52-57

Vocabulary (main + Extra Reading "영어를 가르치는 법," "How to Teach English") and full grammar notes
vision-read; narrative/dialogue/exercises not separately transcribed.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가르치다 | to teach, to instruct | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 33. |
| 갑자기 | suddenly | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 33. |
| 교내 | on campus; 교내 식당 "campus cafeteria" | noun (modifier) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 33. |
| 금연 | no smoking | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 33. |
| 급한 [그판] | urgent; 급하다 "to be urgent" | adjective/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 33. |
| 끝 | end point; 끝까지 "to the end" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 33. |
| 끝나다 [끈나다] | (Vi.) to end, to be over; 끝내다 (Vt.) "to finish" | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 33. Transitive/intransitive pair. |
| 끝마치다 [끈마치다] | (Vt.) to finish, to complete | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 33. |
| 나머지 | the rest, the remaining | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 33. |
| 담배 피우다 | to smoke a cigarette | verb (compound) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 33. |
| 보람있다 | to be rewarding; 보람 "worthwhile, rewarding" | verb/noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 33. |
| 사귀다 | to make (a friend) | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 33. |
| 생기다 | to happen, to occur | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 33. |
| 섞다 | to mix (with) | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 33. |
| 소리 지르다 | to yell, to shout | verb (compound) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 33. |
| 손 들다 | to raise a hand | verb (compound) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 33. |
| 아르바이트 | student's part-time job; 아르바이트하다 "to work part-time" | noun/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 33. Loanword (via Japanese from German *Arbeit*). |
| 아무 | any; 아무 질문 "any question" | determiner | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 33. |
| 알아 듣다 | to understand | verb (compound) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 33. Irregular ㄷ-verb (듣다). |
| 얼마나 | so (good, bad, hard, or the like), how much | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 33. |
| 열심히 | diligently, hard | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 33. |
| 오전 | a.m., morning | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 33. |
| 이야기하다 | to have a conversation; 이야기 "story, conversation" | verb/noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 33. |
| 일어나다 | to get up (from seat or bed); to happen, to occur, to break out | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 33. |
| 절대로 [절때로] | never, don't ever, absolutely (not) | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 33. |
| 점심 | lunch | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 33. |
| -중 | during; 수업 중 "during class" | dependent noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 33. |
| 짐작하다 [짐자카다] | to guess, to estimate; 짐작으로 "by guessing" | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 33. |
| 커피 | coffee | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 33. Loanword (English). |
| 하지만 | but | conjunction | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 33. |
| 회사원; 사원 | company employee | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 33. |

**Extra Reading vocabulary (읽기: 영어를 가르치는 법, p. 34):**

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 내용 | content | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 34. |
| 문법 | grammar | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 34. |
| 방법; 법 | method, means | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 34. |
| 실력 | knowledge; 영어 실력 "command of English" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 34. |
| 적절한 | appropriate; 적절하다 "to be appropriate" | adjective/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 34. |
| 주로 | mainly, mostly | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 34. |
| 힘들어 하다 | to feel difficult, to have difficulty with | verb (compound) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 34. |

### Grammar points

**1. A.V. + 기로 하다** — "to decide to." Indicates a decision or plan, usually used in past tense;
the source cross-references its own beginner volume (*College Korean*, L11 GN1). p. 34.

**2a. A.V. + 자** — "as," "soon after" / **2b. A.V. + 자마자...** — "as soon as." Near-synonyms;
`-자마자` carries more immediacy than `-자`. `-자` cannot be used in a command or "let's" construction
— a restriction not noted for `-자마자`. p. 34-35.

**3. N. + (이)나** — "just," "nothing else but..." A distinct sense of the same `-(이)나` particle
from Lesson 3's grammar point 3b: here it conveys "nothing better to do, so (I) will just..." rather
than "either...or." p. 35.

**4a. 얼마나/어찌나 D.V. + ㄴ/은지 (또는 -았/었던지)** / **4b. 얼마나/어찌나 (ADV.) A.V. + 는지 (또는
-았/었던지)** — "It is/was so D.V. that...," "It is/was such (ADV.) A.V. that..." An emphatic
construction; 얼마나 and 어찌나 are generally interchangeable. p. 35-36.

**5a. N. + 밖에 모르다** — "to know/care about only," "to know nothing but" / **5b. V. + ㄴ/은/는
것밖에 모르다** — "to know nothing but —ing." Source explicitly distinguishes two ways to express
"only" in Korean: `-만` (neutral) vs. `-밖에` (which *must* co-occur with a negative — `-안`, `-못`,
`-지 않다`, `없다`, or `모르다`) — flagged with an explicit ungrammaticality note (`비타민 C밖에를
먹지 않아요` is incorrect; `비타민 C밖에 먹지 않아요` or `비타민 C만을 먹어요` are the only correct
forms). p. 36-37.

**6. V. + (어/아)도** — "even if," "although," "even though." Supposes a real or hypothetical event/
situation and draws a conclusion; combined with 아무리...(어/아)도 it means "no matter how...".
p. 37.

---

## Lesson 5 — 친구와의 대화 (Conversation with Friends) — printed pp. 40-47, PDF pp. 60-67

Full vocabulary and grammar notes vision-read (single vocabulary list, no separate Extra Reading
this lesson); narrative/dialogue/exercises not separately transcribed.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가끔 | sometimes, once in a while | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 41. |
| 건수 | Geon-su (man's name) | proper noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 41. |
| 결정하다 | to decide, to decide on; 결정 "decision" | verb/noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 41. |
| 관심 | interest; 관심 있다 "to be interested" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 41. |
| 교환 학생 | exchange student; 교환하다 "to exchange" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 41. |
| 그런데 | by the way | adverb/conjunction | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 41. |
| 나타나다 | to appear | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 41. |
| 남자 | man, male | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 41. |
| 낯익다 [난닉따] | to be familiar with (a face) | verb (descriptive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 41. |
| 농담 | joke | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 41. |
| 돌아 오다 | to return, to come back; 돌아 가다 "to return, to go back" | verb (compound) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 42. |
| 뜻밖에 [뜯빠께] | unexpectedly | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 42. |
| 말다 | not to do; 하지 말아 "Don't do"; 가지 마세요 "Don't go" | verb (auxiliary, prohibitive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 42. |
| 맞선 | meeting prospective mate face to face; (맞)선보다 "to meet face to face (for marriage purposes)" | noun/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 42. Sociocultural term for a formal matchmaking meeting. |
| 반갑게 | gladly; 반갑다 (Vi.) "to be glad (to see, to hear, or to meet)" | adverb/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 42. |
| 분위기 [부뉘기] | ambience, atmosphere | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 42. |
| 빼다 | to pull out; 점잔을 빼다 "to act dignified" | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 42. |
| 서로 | mutually, to each other | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 42. |
| 석 달 | three months | noun (numeral phrase) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 42. |
| 수줍어하다 [수주버하다] | to feel shy; 수줍다 "to be shy" | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 42. |
| 시키다 | to order (food); to make (a person do); 알아서 시키다 "to figure out and order (food); to make (a person do)" | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 42. |
| 약속 | promise, appointment | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 42. |
| 얌전하다 | to be well-mannered, to be poised, to be demure | verb (descriptive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 42. |
| 어른 | adult, older person | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 42. |
| 어머! | expression of surprise (usually used by female) | interjection | colloquial | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 42. Source itself flags this as a gendered (typically-female-use) interjection. |
| 어색하다 | to be unfamiliar, to be unnatural, to be awkward | verb (descriptive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 42. |
| 여자 | woman, female | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 42. |
| 연락 [열락] | connection, contact; 연락하다 "to get in touch, to contact" | noun/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 42. |
| 예절 | etiquette, manners; 예절 바르다 "to have good manners" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 42. |
| 윗사람 | superior person, elderly person | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 42. |
| 유미 | Yu-mi (woman's name) | proper noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 42. |
| 이모 | mother's sister; 고모 "father's sister" | noun (kinship) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 42. Paternal/maternal aunt lexical distinction. |
| 인류학 [일류학] | anthropology | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 42. |
| 일찍 | early | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 42. |
| 자연스럽다 | to be natural; 자연 "nature" | verb (descriptive)/noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 42. |
| 장소 | place; 약속장소 "appointment place" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 42. |
| 전공하다 | to major in; 전공 "major, specialty" | verb/noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 42. |
| 점잔을 빼다 | to put on dignified air | verb (idiom) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 42. |
| 정하다 | to decide on, to choose | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 42. |
| 조심하다 | to be careful; 조심 "caution, prudence" | verb/noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 43. |
| 존경하다 | to respect; 존경 [종경] "respect" | verb/noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 43. |
| 좀 | a little; please | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 43. |
| 죄송하다 | to be or feel sorry; 죄송하지만 "Excuse me, but..." | verb (descriptive) | formal | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 43. |
| 주문하다 | to order (food) | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 43. |
| 주일 | week; 이 주일 "two weeks" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 43. |
| 친하다 | to be close to (as a friend) | verb (descriptive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 43. |
| 카페 | cafe, coffee shop; 다방, 찻집 "tearoom" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 43. Loanword (French "café"), with two native/Sino-Korean synonyms given. |
| 특히 [트키] | especially | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 43. |
| 풍속 | custom | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 43. |
| 한참 | for a long while | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 43. |
| 행동 | behavior, act; 행동하다 "to behave, to act"; 말과 행동 "words and deeds" | noun/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 43. |
| 흔히 | frequently, commonly | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 43. |

### Grammar points

**1. (하마터면) A.V. + ㄹ/을 뻔하다** — "almost," "nearly," "a close call." When paired with
하마터면, intensifies the near-occurrence of an event that could have happened. p. 43.

**2. Indirect statements** — A systematic treatment of Korean reported/indirect speech (the basic
ending `-다고 하다`), tabulated by tense and by descriptive-verb/action-verb/noun predicate type:
present (`D.V.+다고 하다`, `A.V.+ㄴ/는다고 하다`, `N.+(이)라고 하다`), past (`V.+었/았다고 하다`,
`N.+(이)었다고 하다`), future (`V.+ㄹ/을 거라고 하다`, `N.+일 거라고 하다`). The source explicitly
cross-references its own later coverage: L6 GN4 for indirect command/question/"let's" types, L9 GN5
for a summary of indirect-speech endings, L20 GN1 for their short/contracted forms — confirming
`established/006`'s sibling-file finding that this book's own Lesson 27-equivalent material (there,
*Continuing Korean*'s reduction continuum) recurs across many lessons as a running thread. p. 43-45.

**3a. D.V. + (어/아)지다** — "is becoming...," "is getting..." / **3b. A.V. + (어/아)지다** — "is
be—ed," "is (happening)..." A helping verb with two functions: with a descriptive verb, marks a
change of state (쉽다→쉬워지다 "is getting easy"); with an action verb, forms a passive or marks
spontaneous/automatic occurrence (쓰다→써지다 "writes well [of a pencil]"). p. 45-46.

**4. Person N. + (이)셔 or (이)세요** — "This is... (HON.)" The casual/intimate ending `-(이)셔` is a
contraction of `-(이)시어`, "this is so-and-so (HON.)" — an honorific introduction formula. p. 46.

**5a. 아무 N. + (이)나** — "any N." / **5b. 아무/누구/무엇/어디/언제 + (이)나** — "anyone,"
"everyone," "anything," "anyplace/everywhere," "anytime." When 아무 precedes a noun and `-(이)나`
follows, it means "any" (아무 책이나 "any book"). When `-(이)나` attaches directly to a question word
(아무/누구/무엇/어디/언제), it becomes pronoun-like: 아무나 "anyone," 누구나 "everyone," 무엇이나
"anything/everything," 어디나 "anyplace/anywhere," 언제나 "anytime/whenever." Cross-referenced to
L10 GN4 for further coverage. p. 46-47.

**6a. N. + 인가요?** — "is it...?" / **6b. D.V. + ㄴ/은가요?** — "is it... (adjective)?" / **6c.
A.V. + 나요?** — "is it... (action verb)?" Confirmatory yes/no question endings. Source flags an
irregularity: 있다 and 없다 both take `-나요?` (있나요?/없나요?) rather than the D.V. pattern one
would otherwise expect from their descriptive-verb-like behavior. p. 47.

---

## Lesson 6 — 추석 (Ch'usŏk) — printed pp. 50-58, PDF pp. 70-78

Full vocabulary and grammar notes vision-read. This lesson is a cultural-holiday-explanation lesson
(Korean Thanksgiving) with rich sociocultural vocabulary; no separate Extra Reading vocabulary box
(a short in-narrative folk legend, "Rabbits Making Rice Cake under the Cinnamon Tree," is glossed
inline rather than boxed separately). Narrative/dialogue/exercises not separately transcribed.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가을 | autumn | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 52. |
| 가장; 제일 | the most | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 52. |
| 강릉 [강능] | city of Kangnŭng in Kangwŏn Province | proper noun | core | — | contemporary (source published 2002) | Kangwŏn Province, Korea | regional | grammar_reference | n/a | verified | p. 52. |
| 거리 | streets; 서울 거리 "streets of Seoul" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 52. |
| 게다가 | in addition, moreover (short form of 거기에다가) | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 52. |
| 경치 | scenery | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 52. |
| 곡식 | grains, food | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 52. |
| 과일 | fruit | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 52. |
| 근처 | vicinity, nearby place | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 52. |
| 꼼짝 못하다 | can't move a bit; 꼼짝 하다 "to budge, to stir" | verb (compound) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 52. |
| 꽉 | fully, tightly | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 52. |
| 꽤 | quite, rather | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 52. |
| 내려 가다 | to go down; 올라 오다 "to come up, to rise" | verb (compound) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 52. |
| 늦어지다 | to become late | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 52. |
| 단풍이 들다 | to change to fall colors | verb (idiom) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 52. |
| 달 | month | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 52. |
| 등 | et cetera, and so on | dependent noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 52. |
| 떠나다 | to leave | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 52. |
| -마다 | each, every | particle | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 52. |
| 막히다 | (Vi.) to be blocked; 막다 (Vt.) "to block, to stop" | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 52. |
| 맞이하다 | to welcome, to face | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 52. |
| 명절 | holiday | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 52. |
| 무덥다 | to be humid and hot | verb (descriptive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 52. |
| 비슷하다 | to be similar, to be alike | verb (descriptive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 52. |
| 산소 | graves, cemetery (HON.) | noun | formal | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 52. Source itself flags this as the honorific term. |
| 새해 | new year | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 52. |
| 생각이 나다 | to occur to one, to think of, to remember; 생각 "thoughts" | verb (idiom)/noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 52. |
| 설; 설날 | New Year's Day | noun | core | — | contemporary (source published 2002) | Korea | national | grammar_reference | n/a | verified | p. 52. Major Korean traditional holiday. |
| 설악산 | Sŏrak Mountains on the eastern coast | proper noun | core | — | contemporary (source published 2002) | eastern Korea | regional | grammar_reference | n/a | verified | p. 52. |
| 성묘하다 | to visit grave to pay respect to ancestor | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 52. |
| 송편 | rice cake (sweet-filled); 떡 "rice cake (any kind)" | noun | core | — | contemporary (source published 2002) | Korea | national | grammar_reference | n/a | verified | p. 52. Traditional Ch'usŏk food. |
| 신난다! | Exciting! Super! Cool!; 신난다 "to be excited" | interjection/verb | colloquial | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 52. |
| 양력 [양녁] | western calendar | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 52. |
| 음력 [음녁] | lunar calendar | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 52. |
| -(이)나 | either-or, and, as well | particle | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 53. |
| 정월; 일월 | January | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 53. Two synonyms (Sino-Korean lunar-calendar term vs. ordinary "first month"). |
| 준비하다 | to get ready, to prepare | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 53. |
| 지방 | local area, region, the country | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 53. |
| 차례 | memorial service for ancestors on New Year's Day and Ch'usŏk; 차례 지내다 "to have memorial service on New Year's Day and Ch'usŏk"; 제사 "memorial service (in general)"; 제사 지내다 "to have memorial service" | noun/verb | core | — | contemporary (source published 2002) | Korea | national | grammar_reference | n/a | verified | p. 53. Two related ancestral-rite terms distinguished by occasion-specificity. |
| 초하루 | first day of the month | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 53. |
| 추석 | Harvest Festival Day (August 15 on lunar calendar) | proper noun | core | — | contemporary (source published 2002) | Korea | national | grammar_reference | n/a | verified | p. 53. |
| 추수 | harvest; 추수하다 "to harvest" | noun/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 53. |
| 추수감사절 | Thanksgiving | proper noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 53. |
| 친척 | relative, family member | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 53. |
| 큰아버지 | father's older brother | noun (kinship) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 53. |
| 텅 비다 | totally or completely empty | verb (idiom) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 53. |
| 특별한 | special; 특별하다 "to be special"; 특별히 "specially" | adjective/verb/adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 53. |
| 풍부하다 | to be plentiful, to be abundant | verb (descriptive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 53. |
| 한 두 달 | one or two months | noun (numeral phrase) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 53. |
| 행사 | event | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 53. |

### Grammar points

**1a. V. + (으)므로** — "because," "as," "for," "since," "for being..." / **1b. N. + (이)므로** —
"because it is..." Source explicitly flags this causal connective as rarely used colloquially
(distinguishing it from the spoken-register causal connectives `-(으)니까`, `-기 때문에`, `-(어/아)서`,
`-(으)니`, which are not always interchangeable with each other or with `-(으)므로`). p. 53-54.

**2. 내려가다 versus 올라가다** — "to go down" versus "to go up." A distinctive Korean directional-
metaphor convention: one "goes up" (올라가다) to the capital Seoul and "goes down" (내려가다) from
Seoul to any other region — paralleled by 들어 가다 "goes into" a city center and 나가다 "goes out"
to a suburb. A genuinely useful sociolinguistic/geographic-metaphor point not seen in
`established/001`/`003`/`004`. p. 54.

**3. Adverb 꼼짝** — "a tiny bit (of motion)." A negative-polarity adverb: normally requires a
negative context (안/못, or the negators 없다/말다/-지 않다), though it may appear in a plain
question. Cross-referenced to L20 GN2 for more on this negative-polarity-adverb class. p. 55.

**4. More on indirect speech types: command, question, and "let's"** (cross-referenced to L9 GN5 for
a full summary):
  - **4a. Indirect commands** — `A.V.+(으)라고 하다` ("tells/orders to do...") / `A.V.+지 말라고 하다`
    ("tells/orders not to do..."). When the indirect command itself ends in `-(어/아) 주다`/`드리다`
    (honorific)/`달라다`, the speaker must track the full three-way relationship among speaker,
    addressee, and the person spoken of — illustrated with contrastive worked examples. p. 55-56.
  - **4b. Indirect questions** — `D.V.+(으)냐고 하다`, `A.V.+(느)냐고 하다`, `N.+(이)냐고 하다`.
    Notes 으/느 may be optionally dropped for some verbs (길이 좁냐고 하다 = 길이 좁으냐고 하다).
    p. 56-57.
  - **4c. Indirect "let's"** — `A.V.+자고 하다`; used only with action verbs, with no tense changes.
    p. 57.

**5. A.V. + ㄴ/은/는 김에** — "while one is at it/doing it," "since/because." Colloquial "while we're
at it, might as well..." construction; verbal modifier ㄴ/은 or 는 chosen by tense. p. 57.

**6a. D.V. + ㄴ/은 편이다** / **6b. A.V. + ㄴ/은/는 편이다** — "to be kind of," "to be rather," "to be
relatively." With descriptive verbs, softens a quality claim ("relatively/kind of good/big/many");
with action verbs, typically co-occurs with an adverb (빨리 읽는 편이다 "to read kind of fast").
p. 57-59.

---

## Lesson 7 — 강원도와 신사임당 (Kangwŏn-do and Lady Shin) — printed pp. 61-69, PDF pp. 81-89

Vocabulary (main + an in-narrative historical-biography section on 신사임당/Shin Saimdang, plus an
Extra Reading "설악산 관광객이 점점 늘어요," "Growing Numbers of Tourists at Sŏrak Mountain") and full
grammar notes vision-read. This is a historically/biographically rich lesson: a footnoted historical
note on Yi Yul-gok (1536-1584) and Yi Hwang (T'oe-gye), described as the two finest scholars of the
Chosŏn dynasty. Narrative/dialogue/exercises not separately transcribed.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 고속 버스 | express bus | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 62. |
| 관광 | tour, tourism; 관광 산업 "tourist industry" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 62. |
| 그리다 | to draw, to paint | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 62. |
| 그림 | drawing, painting | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 62. |
| 글 | writing | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 62. |
| 글쎄 | Well, Let me see | interjection | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 62. |
| 기르다 | to raise (a child), to grow | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 62. Irregular 르-verb. |
| 나오다 | to come out | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 62. |
| 남편 | husband; 부인 "wife" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 62. |
| 단풍 | fall colors; maple (leaves); 단풍철 "fall season" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 62. |
| 달 | moon; 달이 뜨다 "the moon rises" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 62. Homonym with Lesson 6's 달 "month." |
| 당시 | at that time | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 62. |
| -댁 | house, residence (HON.) | suffix | formal | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 62. |
| 돕다 | to help; 도움 "help, aid" | verb/noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 62. Irregular ㅂ-verb. |
| 뛰어나다 | to be outstanding | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 62. |
| 뜨다 | to rise, to come up, to float | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 62. |
| 모범 | model, good example | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 62. |
| 바닷가; 해변 | beach | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 62. Native/Sino-Korean synonym pair. |
| 바로 | just, exactly; 바로 이것 "exactly this one"; 곧바로 "immediately" | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 62. |
| 반가워하다 | (Vt.) to be glad, to rejoice; 반갑다 (Vi.) "to be glad" | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 63. |
| 발달하다 [발딸하다] | to develop; 발달되다 "to be developed"; 발달 "development" | verb/noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 63. |
| 사이 | between, gap; relationship | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 63. |
| 산업 | industry; 수산업 "marine industry" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 63. |
| 소나무 | pine tree | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 63. |
| 솜씨 | skill (mostly manual skills) | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 63. |
| 수영 | swimming; 수영하다 "to swim" | noun/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 63. |
| 시 | poem, poetry | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 63. |
| 아이 | child, kid | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 63. |
| 양반 | *yangban* class, nobility | noun | core | — | contemporary (source published 2002) | attested (historical, Chosŏn dynasty) | Korea | national | grammar_reference | n/a | verified | p. 63. Historical Chosŏn-dynasty aristocratic class term. |
| 얘기 | story, tale, talk, news (short form of 이야기); 얘기하다 "to say" | noun/verb | colloquial | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 63. Source itself flags 얘기 as the colloquial contraction of 이야기. |
| 어렸을 때 | when one was young | phrase | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 63. |
| 역사적으로 | historically | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 63. |
| 예쁜 | pretty; 예쁘다 "to be pretty" | adjective/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 63. |
| 외동딸 | only daughter; 외동아들/외아들 "only son" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 63. |
| 유명하다 | to be famous | verb (descriptive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 63. |
| 인상적 | impressive | noun/adjective | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 63. |
| 자연 | nature | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 63. |
| 자유롭게 | freely; 자유 "freedom"; 자유롭다 "to be free" | adverb/noun/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 63. |
| 재주 | talent; 재주가 있다 "to be talented" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 63. |
| 지도 | map | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 63. |
| -처럼 | like; 남자처럼 "like a man" | particle | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 63. |
| 터미널 | bus terminal; 고속 버스 터미널 "express-bus terminal" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 63. Loanword (English "terminal"). |
| 포도 | grapes | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 63. |
| 풀벌레 | plant insect/bug; 쌀벌레 "rice bugs" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 63. |
| 학문 [항문] | learning, study, scholarship, academic studies, academic learning | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 63. |
| 학자 | scholar | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 63. |
| 한창이다 | to be in the prime of, to be in full (bloom, color) | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 63. |
| 현모양처 | wise mother and good wife | noun (four-character idiom) | core | — | contemporary (source published 2002) | attested (traditional Confucian ideal) | Korea | national | grammar_reference | n/a | verified | p. 63. Traditional Confucian gender-role ideal, explicitly the descriptor applied to Shin Saimdang in the lesson's biography. |
| 호수 | lake | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 63. |
| 효도 | filial piety | noun | core | — | contemporary (source published 2002) | attested (traditional Confucian value) | Korea | national | grammar_reference | n/a | verified | p. 63. |

**Extra Reading vocabulary (읽기: 설악산 관광객이 점점 늘어요, p. 65):**

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 공사 | construction work | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 65. |
| 관광객 | tourist | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 65. |
| 관광지 | tourist place | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 65. |
| 그 동안 | in the mean time | phrase | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 65. |
| 늘다 | to increase; 늘리다 "to widen, to make it increase" | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 65. |
| 도로 | (paved) road | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 65. |
| 보통이다 | to be usual, to be common | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 65. |
| 불편하다 | to be uncomfortable, to be inconvenient | verb (descriptive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 65. |
| 영동 고속 도로 | Yŏngdong Expressway (from Seoul to Kangnŭng) | proper noun | core | — | contemporary (source published 2002) | Korea (Seoul-Kangnŭng) | regional | grammar_reference | n/a | verified | p. 65. |
| -이상 | more than, above, over | suffix | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 65. |
| 좁다 | to be narrow | verb (descriptive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 65. |
| 줄 | lane, line; 두 줄 "two lanes, two lines" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 65. |
| -중에 | among, between | particle | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 65. |
| 피하다 | to avoid | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 65. |
| 휴가(철) | vacation (season) | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 65. |

### Grammar points

**1. A.V. + (어/아) 봐야지요** — "should (try)...," "must (try to)..." Expresses the speaker's
intention to try to do something ("I will certainly try..."/"I should try..."). Also notes that the
informal ending `-지(요)` alone can serve as either statement or question depending purely on
intonation/context. p. 65-66.

**2a. N. + ㄹ/일 텐데(요)** / **2b. V. + ㄹ/을 텐데(요)** — "I imagine," "I would think," "it must
be." A short connective form of `-을/일 터인데`, derived from the noun 터 "expectation/place" + 이다
+ the connective `-ㄴ/는데`, expressing the speaker's expectation/anticipation. Related form V.+ㄹ/을
테니(까) means "since/because (it is expected to)," combining the same 터이다 base with the causal
connective `-(으)니까`. p. 66-67.

**3. D.V. + ㄴ/은가 봐요 / A.V. + 나 봐요** — "I think it is," "it seems." Expresses the speaker's
supposition/guess, tabulated across present/past/future. Irregularity flagged: 있다 and 없다 behave
as action verbs here too and take `-나 봐요` rather than the descriptive-verb pattern. p. 67-68.

**4. Adverb-forming suffix -적으로** — A genuinely productive two-step Sino-Korean word-formation
rule, directly relevant to morphological-play analysis: `-적` first derives an adjective from a
Sino-Korean noun (역사 "history" → 역사적 "historical"), then `-으로` derives an adverb from that
adjective (역사적으로 "historically"). Explicitly restricted to Sino-Korean nouns — native Korean
nouns cannot take this pattern (인간 "human being" → 인간적으로 "as a human being" is grammatical,
but 사람 "person" → *사람적으로 is not). Source's own worked set: 역사/역사적/역사적으로,
세계/세계적/세계적으로, 전통/전통적/전통적으로, 인상/인상적/인상적으로, 지리/지리적/지리적으로,
기계/기계적/기계적으로. p. 68.

**5. N. + (이)(라)면 누구/무엇 + (이)나** — "if... is, then whoever/whatever...," "any (person/
thing) would..." Literally "if (one is)..., then (he/she does)...". Other question words (어디,
언제, 어떤, 누구) can substitute. Cross-referenced to `-든지` at L10 GN4. p. 68-69.

**6a. N. + 처럼** — "like." / **6b. V. + ㄴ/은/는 것처럼** — "as," "as though," "as well as."
Attached to a noun, means "someone/something is like some other person or thing," close in meaning
to `-같이`; attached after `-ㄴ/는 것`, means "as if" or "like doing." p. 69.

---

## Lesson 8 — 과학 도시 대전 (Taejŏn, the City of Science) — printed pp. 74-80, PDF pp. 94-100

Vocabulary (main + Extra Reading "대전에 대하여," "About Taejŏn") and full grammar notes vision-read.
Narrative/dialogue/exercises not separately transcribed.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 과학 | science | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 75. |
| 광고 | advertisement; 광고하다 "to advertise" | noun/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 75. |
| 근무 시간 | work hour | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 75. |
| 남다 | to be left over | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 75. |
| 단지 | complex, compound; 마산 공업 단지 "Masan Industrial Park" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 75. |
| 대덕 | city of Taedŏk (south of Seoul, next to Taejŏn); 대덕 과학 연구 단지 "Taedŏk Science Town" | proper noun | core | — | contemporary (source published 2002) | south-central Korea | regional | grammar_reference | n/a | verified | p. 75. |
| 대전 | city of Taejŏn (south of Seoul) | proper noun | core | — | contemporary (source published 2002) | south-central Korea | regional | grammar_reference | n/a | verified | p. 75. |
| 도시 | city | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 75. |
| 돈 | money | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 75. |
| 맞아. [마자] | You are right. | interjection | colloquial | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 75. |
| 매진이다; 매진되다 | to be sold out; 매진 "sold-out" | verb/noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 75. |
| 매표원 | ticket agent; 매표구 "ticket window"; 매표소 "box office" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 75. |
| 미래 | future | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 75. |
| 백제 | Paekche (one of the Three Kingdoms) | proper noun | core | — | contemporary (source published 2002) | attested (historical, Three Kingdoms period) | Korea | national | grammar_reference | n/a | verified | p. 76. |
| 벌다 | to earn; 돈을 벌다 "to make money" | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 76. |
| 보내다 | to spend (time) | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 76. |
| 부여 | city of Puyŏ | proper noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 76. Former capital of Paekche. |
| 상대하다 | to deal with | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 76. |
| 선배 | senior classmate; 후배 "junior classmate" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 76. |
| 심리학 | psychology; 심리 "state of mind, mentality" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 76. |
| 연구 | research; 연구 단지 "research complex" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 76. |
| 왕복표 | round-trip ticket | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 76. |
| 월급 | monthly salary | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 76. |
| 이틀 | two days | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 76. |
| 자랑 | pride, boast, self-conceit; 자랑하다 "to be proud of, to show off" | noun/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 76. |
| 전자 공학 | electronic engineering | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 76. |
| 졸업하다 | to graduate | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 76. |
| 주식; 주 | stock; 주가 [주까] "stock price" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 76. |
| 지루하다 | to be boring, to be tedious | verb (descriptive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 76. |
| 짧다 [짤따] | to be short | verb (descriptive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 76. |
| 찾아 보다 | to find, to look for, to search | verb (compound) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 76. |
| 취직하다 | to get a job; 취직 "getting a job" | verb/noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 76. |
| 투자 | investment; 투자 회사 "investment company" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 76. |
| 표 | ticket | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 76. |
| 하루 | one day | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 76. |
| 흥미 | interest; 흥미 있다 "to be interested, to be interesting" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 76. |

**Extra Reading vocabulary (읽기: 대전에 대하여, p. 76-77):**

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 기술 | technology, skill; 과학 기술 대학 "institute or college of science and technology" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 77. |
| 따라서 | therefore | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 77. |
| 새로 | newly | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 77. |
| 실리콘 밸리 | Silicon Valley | proper noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 77. Loanword. |
| 엑스포 | exposition | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 77. Loanword (English "expo"); refers to the real 1993 Taejŏn Expo. |
| 연구소 | research institute | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 77. |
| 열리다 | to be held | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 77. |
| 정보 | information | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 77. |
| 중심지 | central region, core area | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 77. |
| 편리하다 | to be convenient | verb (descriptive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 77. |
| 하이테크 | high-tech | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 77. Loanword (English). |

### Grammar points

**1. D.V. + (어/아)하다** — "to feel..." Most emotion descriptive verbs become action (transitive)
verbs by attaching `-(어/아)하다`, turning an intransitive adjectival state into a transitive
feeling-verb (기쁘다 "to be happy" → 기뻐하다 "to feel happy"; 좋다 "to be good" → 좋아하다 "to
like"; also applies to the desiderative `-고 싶다` → `-고 싶어하다`). Source's full worked set:
기쁘다/기뻐하다, 슬프다/슬퍼하다, 괴롭다/괴로워하다, 재미있다/재미있어하다, 좋다/좋아하다,
싫다/싫어하다, 즐겁다/즐거워하다, -고 싶다/-고 싶어하다. p. 77-78.

**2. A.V. + ㄴ/은 지(가) ... 되다** — "it's been... since..." Marks elapsed time since an action/
event (한국에 온 지(가) 10년 됐어요 "it's been ten years since I came to Korea"). p. 78.

**3. Polite suggestions: -(으)면 어때요?** — "How about...?" A five-step politeness-gradient list
for suggestions, from least to most polite/formal/honorific: `-(으)면 어때?` (nonpolite) →
`-(으)면 어때요?` (polite but informal) → `-(으)면 어떨까요?` (more polite) →
`-(으)면 어떻겠습니까?` (polite and formal) → `-(으)면 어떠시겠습니까?` (polite, formal, and
honorific). A clean, explicit five-tier politeness cline not tabulated this way in
`established/001`/`003`/`004`. p. 78-79.

**4a. V. + ㄴ/은/는 것이 아니라** — "it is not (the fact) that," "not... but..." / **4b. N. + 이/가
아니라** — "it is not N. but...," "not N. but..." Amends a first action/event/noun with a second,
corrective one. p. 79.

**5a. A.V. + 는 중(에)** — "in the middle/midst of doing..." / **5b. N. + 중(에)** — "among," "in
the midst of..." p. 79-80.

**6. -다고/라고 그래(요)** — "it's said (so)," "it is called..." Colloquial expression similar to
the indirect-speech forms `-고 해(요)` and `-래(요)` (cross-referenced to L5 GN2). Source explicitly
distinguishes this from bare 그래(요), which has separate, context-dependent meanings (a plain
affirmative response "Yeah"/"I agree," or agreement with a statement) — a genuine same-string,
different-construction ambiguity worth flagging for later slang-mechanics analysis. p. 80.

---

## Lesson 9 — 무엇이 될까? (What Shall I Be?) — printed pp. 84-91, PDF pp. 104-111

Vocabulary (main + Extra Reading "현대 사회와 남녀 평등," "Modern Society and Gender Equality") and
full grammar notes vision-read. Narrative/dialogue/exercises not separately transcribed.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 경영학 | study of business administration; 경영 "business administration" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 85. |
| 경찰관 | police officer | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 85. |
| 계획 | plan | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 85. |
| 고등학교 | high school | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 85. |
| 교육학 [교유칵] | study of education; 교육 "education" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 85. |
| 그냥 | for no reason, as it is, as it stands | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 85. |
| 꿈 | dream; 꿈꾸다 "to dream" | noun/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 85. |
| 남녀 평등 | gender equality, women's equality | noun (phrase) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 85. |
| 당연하다 | to be expected, natural; 당연히 "naturally, justly" | verb/adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 85. |
| 뚜렷하다 [뚜려타다] | to be clear, to be sure | verb (descriptive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 85. |
| -만큼 | to the extent, as much as, as well as | particle | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 85. |
| 맞다 | to fit, to be suitable, to be correct | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 85. |
| 매일 | everyday | noun/adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 85. |
| 배우 | actor or actress | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 85. |
| 법관 | judge | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 85. |
| 법대 | law school | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 85. |
| 법학 [버팍] | study of law | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 85. |
| 변하다 | to change, to become different, to turn into | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 85. |
| 변호사 | lawyer | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 85. |
| 분야 [부냐] | field | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 85. |
| 불다 | (Vt.) to blow (trumpet, bugle), to play on (flute); (Vi.) to blow; 바람이 불다 "The wind blows." | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 85. Irregular ㄹ-verb. |
| 붙이다 [부치다] | to acquire, to glue; 취미를 붙이다 "to find pleasure in" | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 85. |
| 사라 | Sarah | proper noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 85. |
| 살아 계시다 | to be alive (HON.) | verb | formal | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 85. |
| 식구 | immediate family member | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 85. |
| 어리다 | to be very young, to be immature; 어려서부터 "from the time of youth" | verb (descriptive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 85. |
| 엘샛 | LSAT | proper noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 86. Loanword/acronym (English). |
| 여성 | female; 남성 "male" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 86. |
| 연극 | drama, play | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 86. |
| 유학 오다 | to come to study abroad; 유학하다 "to study abroad" | verb (compound) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 86. |
| 음악 | music; 음악가 "musician" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 86. |
| 의학 | medical study, medicine | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 86. |
| 자주 | frequently, many times | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 86. |
| 장래 | future | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 86. |
| 적성 | aptitude | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 86. |
| 중학교 | middle school | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 86. |
| 직업 [지겁] | profession, occupation; 직업 여성 "professional woman" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 86. |
| 진학하다 | to move on (to next level of school) | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 86. |
| 찾다 | to find | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 86. |
| 초등학교 | elementary school (formerly 국민학교) | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 86. Source notes the older Japanese-colonial-era term 국민학교 ("citizens' school") this replaced — a real terminology-change/register note. |
| 취미 | interest, hobby | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 86. |
| 트럼펫 | trumpet | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 86. Loanword (English). |
| 평등 | equality | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 86. |
| 훌륭한 | great; 훌륭하다 "to be great" | adjective/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 86. |

**Extra Reading vocabulary (읽기: 현대 사회와 남녀 평등, p. 86-87):**

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가족 | family | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 86. |
| 결혼하다 | to marry | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 86. |
| 경우 | occasion, case | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 86. |
| 관습 | custom, usual practice | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 86. |
| 구하다 | to look for, to seek | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 86. |
| 그만두다 | to quit | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 86. |
| 기회 | opportunity, chance | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 87. |
| 남아 있다 | to still exist, to remain | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 87. |
| 돌보다 | to look after | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 87. |
| 맞벌이 부부 | working couple | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 87. |
| 불평등 | inequality | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 87. |
| 사회 | society | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 87. |
| 없어지다 | to disappear, to vanish | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 87. |
| 예 | example; 예를 들면 "for example" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 87. |
| 예외 | exception | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 87. |
| 적다 | to be few (in number), to be little (in quantity) | verb (descriptive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 87. |
| 점점 | gradually | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 87. |
| 직장 | job, employment, workplace | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 87. |
| 차별하다 | to discriminate against | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 87. |
| 현대 | present age, modern times | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 87. |

### Grammar points

**1. V. + 기 위해(서)/기 위하여 / N. + 을/를 위해(서)/위하여** — "for," "for the sake of," "in order
to" / "for," "for the benefit of." Standard purpose construction. p. 87.

**2a. N. + 만큼** — "(almost) as much as," "as well as" / **2b. V. + ㄴ/은/는/ㄹ/을 + 만큼** — "do
as much as," "is enough to..." Marks a comparison of near-equal degree; tense-marked by the usual
verbal modifiers (`-는` present, `-ㄴ/은` past, `-ㄹ/을` future). p. 87-88.

**3a. V. + ㄹ/을수록** — "the more one does..., the more..." / **3b. V. + (으)면, V. + ㄹ/을수록** —
same meaning with stronger emphasis via the added conditional `-(으)면`. p. 88.

**4. V. + ㄴ/은/는/ㄹ/을 모양이다.** — "it looks...," "it seems...," "it appears..." Expresses the
speaker's opinion/inference about an action or event, based on observed evidence. p. 89.

**5. Indirect speech: polite informal forms** — `-대요, -래요, -(으)래요, -ㄴ대요, -재요` are the
colloquial short forms of `-다고 해요/합니다`, `-라고 해요/합니다`, `-자고 해요/합니다`, and
`-냐고 해요/합니다` respectively. The source provides a full **Indirect speech endings chart**
cross-tabulating Sentence Type (Statement-verb/Statement-noun/Command/Question/"Let's") × Plain Form
× Polite Informal Short Form × Polite Formal Short Form — the single most complete summary table for
this grammar area across the whole book, gathering together the `-다고 하다` family first introduced
at Lesson 5 GN2 and extended piecemeal through Lesson 6 GN4. Polite formal short forms
(`-답니다/-랍니다/-(으)랍니다/-납니다/-잡니다`) are cross-referenced forward to L20 GN1. p. 89-91.

**6. N. + 같은** — "like," "same as." Simple noun-modifying comparative (신사임당 같은 여자 "a woman
like Lady Shin Saimdang"). p. 91.

---

## Lesson 10 — 경주와 건국 신화 (Kyŏngju and the Foundation Myth of Silla) — printed pp. 95-103, PDF pp. 115-123

Vocabulary (main, including an in-narrative retelling of the Silla foundation myth of Pak
Hyŏkkŏse) and full grammar notes vision-read; no separate Extra Reading box this lesson.
Narrative/dialogue/exercises not separately transcribed.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 건국 | founding a nation; 건국하다 "to found a nation" | noun/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 97. |
| 경주 | city of Kyŏngju (Silla's capital city) | proper noun | core | — | contemporary (source published 2002) | attested (Silla capital) | southeastern Korea | regional | grammar_reference | n/a | verified | p. 97. |
| 고려 | Koryŏ dynasty (918-1392) | proper noun | core | — | contemporary (source published 2002) | attested (historical, 918-1392) | Korea | national | grammar_reference | n/a | verified | p. 97. |
| 국가 | state, nation | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 97. |
| 국립 [궁닙] | national, government-established | noun (modifier) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 97. |
| 굴 | grotto, cave | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 97. |
| 귀걸이 | earring; 목걸이 "necklace" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 97. |
| 금반지 | gold ring | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 97. |
| 기억나다 | to recall, to remind; 기억 "memory" | verb/noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 97. |
| 기원 전 | B.C.; 기원 후 "A.D." | noun (phrase) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 97. |
| 깨끗하다 | to be clean | verb (descriptive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 97. |
| 깨다 | (Vt.) to break; (Vi.) to wake up; 깨우다 (Vt.) "to wake up" | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 97. |
| 꼭 | for sure | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 97. |
| 다방 | tearoom | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 97. |
| 데려다가 | having brought | verb (bound, requires connective) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 97. |
| 마을 | village | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 97. |
| 마치 | as if, just as | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 97. |
| 말 | horse | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 97. |
| 멋있다 [머시따] | to be stylish, to be cool, to be chic | verb (descriptive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 97. |
| 모셔 놓다 | to set up, to place (respectfully); 모시다 "to serve" | verb (honorific compound) | formal | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 97. |
| 무겁다 | to be heavy; 가볍다 "to be light" | verb (descriptive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 97. Irregular ㅂ-verb. |
| 무덤 | grave, tomb | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 97. |
| 무척 | very, immensely, highly | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 97. |
| 문화 | culture | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 97. |
| 미소 | smile | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 97. |
| 발전하다 | to make progress; 발전 "progress, advancement" | verb/noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 97. |
| 보통 | ordinary, common, usual, average | adjective/adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 97. |
| 부처님 | the Buddha (HON.) | proper noun | formal | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 97. |
| 불교 | Buddhism | noun | core | — | contemporary (source published 2002) | attested (introduced Three Kingdoms period) | Korea | national | grammar_reference | n/a | verified | p. 97. |
| 불국사 | Pulguk-sa temple in Kyŏngju | proper noun | core | — | contemporary (source published 2002) | attested (built 535 CE per lesson text) | Kyŏngju, Korea | regional | grammar_reference | n/a | verified | p. 97. |
| 불상 | Buddha statue | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 97. |
| 빵집; 제과점 | bakery | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 97. Native-loanword-compound/Sino-Korean synonym pair. |
| 사내 | man; 사내 아이 "boy" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 98. |
| 삼국 | Three Kingdoms (Silla, Koguryŏ, Paekche) | proper noun | core | — | contemporary (source published 2002) | attested (historical, Three Kingdoms period) | Korea | national | grammar_reference | n/a | verified | p. 98. |
| 석굴암 | Sŏkkuram Grotto (where stone Buddha was built) | proper noun | core | — | contemporary (source published 2002) | attested (Silla, 8th century, per lesson caption) | Kyŏngju, Korea | regional | grammar_reference | n/a | verified | p. 98. |
| 석탑 | stone pagoda; 탑 "tower"; 시계탑 "clock tower" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 98. |
| 성(姓) | last name | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 98. |
| 세기 | century; 2세기 "second century" | noun (counter) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 98. |
| 세우다 | to erect, to build, to found | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 98. |
| 숲 | forest | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 98. |
| 신라 [실라] | Silla dynasty | proper noun | core | — | contemporary (source published 2002) | attested (57 BCE-935 CE per lesson text) | southeastern Korea | national | grammar_reference | n/a | verified | p. 98. |
| 신화 | myth, mythology | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 98. |
| 알 | egg | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 98. |
| 언덕 | hill | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 98. |
| 역사 | history | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 98. |
| 왕관 | (royal) crown | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 98. |
| 왕릉 [왕능] | king's grave | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 98. |
| 왕비 | queen | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 98. |
| 용감하다 | to be brave | verb (descriptive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 98. |
| 이름 | name | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 98. |
| 임금님 | king | noun | formal | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 98. |
| 장수 | warrior, general | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 98. |
| 절 | Buddhist temple | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 98. |
| 정돈 | order, proper arrangement; 정돈되다 "to be put in order" | noun/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 98. |
| 촌장 | village chief | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 98. |
| 칼 | sword, knife | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 98. |
| 커다란 | large, big, gigantic; 커다랗다 "to be large, to be gigantic" | adjective/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 98. Irregular ㅎ-verb. |
| 허리띠 | waistband, belt | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 98. |
| 훨씬 | much more, by far | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 98. |

### Grammar points

**1. N. + (으)로 유명하다 / V. + ㄴ/은 것으로 유명하다 / V. + 기로 유명하다** — "is famous for" /
"is famous for —ing..." `-기로 유명하다` often pairs with a descriptive verb (좋다, 많다, 크다, 넓다).
p. 98-99.

**2. V. + 더라** — "I'd say...," "(I remember) something..." Intimate/casual sentence ending
combining the retrospective particle 더 + 라, reporting the speaker's own past experience or
firsthand information; restricted to addressing an equal or lower-rank, close-relationship listener.
Polite form: `-던데요`. p. 99.

**3. N. + (이)라는** — "(so) called...," "known as..." Short form of `-(이)라고 하는`. p. 99-100.

**4a. Question word + (이)든지** — "whoever/whatever/whenever/wherever..." / **4b. Question word
V. + 든지** — same, applied to a full clause ("whoever comes," "whatever you see"). `-(이)든지` is
interchangeable with `-(이)나` (cross-referenced to L5 GN5). Full worked set: 누구든지 "whoever,"
무엇이든지 "whatever," 어디든지 "wherever," 언제든지 "whenever," 얼마든지 "any amount," 어떻게든지
"no matter how." p. 100-101.

**5a. V. + 잖아(요)?** — "right?," "doesn't it?" (+ past `-았/었잖아(요)?`) / **5b. N. + (이)잖아
(요)?** — "isn't it?" (+ past `-(이)었잖아(요)?`). Informal short form of `-지 않아(요)`, functioning
like a tag question; source lists the range of expected listener responses (그래(요) "That's right,"
맞아(요) "You're right," 글쎄(요) "Maybe," 아니(오) "Not really," or a further question 그래(요)?/
왜요?). p. 101-102.

**6a. N. + 을/를 데려다가** — "after bringing" / **6b. N. + (을/를)데리고** — "bringing/taking with."
데려다 is never used as a bare verb — always requires a connective (`-다가`, `-고`). Distinguishes
동물/사람 ("bringing" a person/animal: 데려다가, 데리고) from inanimate objects (가져다가, 가지고,
as in 점심을 가지고 오세요 "please bring your lunch") — a genuine grammatical animacy distinction.
Honorific forms: 모셔다가 ("after accompanying [someone], HON."), 모시고 ("accompanying, HON.").
p. 102-103.

---

## Lesson 11 — 항구 도시를 찾아서 (Calling on the Port City) — printed pp. 106-111, PDF pp. 126-131

Vocabulary (main + Extra Reading "부산에 대하여," "About Pusan") and full grammar notes vision-read.
Narrative/dialogue/exercises not separately transcribed.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 고기; 물고기 | fish; 고기 잡다 "to fish" | noun/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 107. |
| 고속 페리 | high-speed ferry | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 107. |
| 관공서 | government or public office | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 107. |
| 기선 | liner, large ship, steamship | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 107. |
| 끊임없이 | endlessly; 끊다 "to sever, to cut off" | adverb/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 107. |
| 논밭 | rice paddy and fields; 논 "rice paddy"; 밭 "field, farm" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 107. |
| 놀라다 | to be surprised, to be startled | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 107. |
| 닿다 | to arrive at, to reach | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 107. |
| 드나들다 | to go in and out | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 107. |
| 러시아 | Russia | proper noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 107. |
| 무섭게 | awfully; 무섭다 "to be awful, to be fearful, to be terrible"; 닿기가 무섭게 "as soon as it arrives" | adverb/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 107. |
| 보내다 | to send | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 107. |
| 부지런하다 | to be diligent | verb (descriptive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 107. |
| 새벽 | dawn, early in the morning | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 107. |
| 생선 | (caught food) fish; 물고기 "live fish" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 107. |
| 선박 | boat, ship | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 107. |
| 순간 | moment, instant | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 107. |
| 싱싱하다 | to be fresh | verb (descriptive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 107. |
| 어디 가나 | wherever one goes | phrase | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 107. |
| 어선 | fishing boat | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 107. |
| 어시장 | fish market | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 107. |
| 왕복 | round-trip; 왕복하다 "to make a round trip" | noun/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 107. |
| 인구 | population | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 107. |
| 인천 | city of Inch'ŏn | proper noun | core | — | contemporary (source published 2002) | northwestern Korea | regional | grammar_reference | n/a | verified | p. 107. |
| 전국 | the whole country (nation) | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 107. |
| 종류 [종뉴] | kind, sort, variety | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 107. |
| 중국 | China | proper noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 107. |
| 찾아서 | in search of; 찾다 "to search for" | verb (compound) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 107. |
| 학원 | tutoring school | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 107. |
| 항구 | port; 항구 도시 "port city" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 107. |
| 해산물 | seafood, marine product | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 107. |

**Extra Reading vocabulary (읽기: 부산에 대하여, p. 108):**

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 경부 고속 도로 | Seoul-Pusan Expressway | proper noun | core | — | contemporary (source published 2002) | Korea (Seoul-Pusan) | national | grammar_reference | n/a | verified | p. 108. |
| 대부분 | almost all, for the most part, mostly | noun/adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 108. |
| 대여섯 | about five or six; 한두 시간 "a couple of hours"; 두세 명 "two or three persons"; 서너 집 "three or four houses" | numeral (approximative) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 108. A productive approximative-numeral compounding pattern (N-and-N+1), illustrated with four parallel examples. |
| 수산업 | marine industry | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 108. |
| 수입품 | import (trade goods) | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 108. |
| 수출품 | export (trade goods) | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 108. |
| 신발업 | shoe industry | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 108. |
| 인상 | impression; 인상을 주다 "to give an impression" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 108. |
| 조선업 | shipbuilding industry | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 108. |
| 최대 | biggest, largest, most | noun/adjective | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 108. |
| 통해서 | by way of, through; 통하다 "to pass through" | adverb/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 108. |
| 피서객 | summer visitor, summer tourist | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 108. |
| 해수욕장 | beach (swimming area) | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 108. |
| 해운대 | Haeundae Beach in Pusan | proper noun | core | — | contemporary (source published 2002) | Pusan, Korea | regional | grammar_reference | n/a | verified | p. 108. |

### Grammar points

**1. N. + (으)로(서)** — "as," "for," "being (in the position of)." Indicates a noun's qualification
or status (뉴욕은 항구도시로서, 무역이 발달됐다 "As a port city, New York is advanced in the
commercial trades"). p. 108-109.

**2a. N. + (이/가) 없이** — "without (something/someone)" / **2b. V. + ㄴ/은/는/ㄹ/을 것 없이** —
"without —ing..." / **2c. V. + ㅁ/음 없이** — "without —ing..." Source appends a dedicated note on
the **nominalizer -ㅁ/음** ("to do/be," "—ing"): turns a verb into a noun (싸우다 "to fight" → 싸움
"fighting"; 끝나다 "to finish" → 끝남 "the ending"), restricted to specific syntactic contexts — as
subject of intransitive verbs (필요하다, 중요하다, 있다, 없다) or direct object of transitive verbs
(보다, 찾다, 알다, 생각하다). Cross-referenced to L15 GN1 for comparison with the nominalizer `-기`.
Flags that some -ㅁ/음-derived forms have lexicalized into ordinary nouns: 잠 "sleep," 춤 "dance,"
기쁨 "joy," 아름다움 "beauty." A genuinely important morphological-derivation point for later slang-
mechanics analysis (a second, competing nominalizer alongside `-기`, each with different syntactic
privileges). p. 109-110.

**3. A.V. + ㄴ/은/는 순간** — "the moment," "at the moment of." Expresses the exact instant an
action/event occurs. p. 110.

**4. V. + ㄴ/은 적이 있다/없다 (also V. + 어/아본 적이 있다/없다)** — "there has/has never been,"
"to have/have never done." Experiential-aspect construction; 적 "occasion" often co-occurs with
`(어/아)보다`. Alternate form: `-ㄴ/은 일이 있다`. p. 110.

**5. V. + 지 않을 수 없다** — "could not help but," "there is no way but." Conveys a sense of
involuntary/obligatory action. p. 111.

**6. A.V. + 기(가) 무섭게** — "as soon as," "immediately (after)." Idiomatic, vivid-immediacy
construction (배가 부두에 닿기가 무섭게 선원들이 내려 왔다 "Immediately after the ship reached the
pier, the crew got off"). p. 111.

---

## Lesson 12 — 예술의 도시 광주 (Kwangju, the City of Arts) — printed pp. 114-119, PDF pp. 134-139

Full vocabulary and grammar notes vision-read (single vocabulary list, no separate Extra Reading
this lesson). Narrative/dialogue/exercises not separately transcribed.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가락 | tune, melody, song (archaic expression of 곡) | noun | literary | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 115. Source itself flags this as an archaic register variant of 곡. |
| 겹겹이 | in many layers (of mountains, fabric, clothes) | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 115. |
| 교환 교수 | exchange professor | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 115. |
| 기름 | gas, oil | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 115. |
| 기분 | feeling, mood | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 115. |
| 내다보다 | to look out from | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 115. |
| 농부 | farmer | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 115. |
| 놓치다 | to miss, to fail to catch | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 115. |
| 대신 | instead of, substitution, substitute; 대신하다 "to take the place of, to replace" | noun/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 115. |
| 도로 | road | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 115. |
| 동양화 | Oriental painting; 동양 "the Orient, Oriental" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 115. |
| 들르다 | to drop by, to stop by | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 115. Irregular 르-verb. |
| 비교 | comparison; 비교하다 "to compare" | noun/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 115. |
| 사랑하다 | to love | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 116. |
| 상 | table | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 116. |
| 성악가 | concert singer | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 116. |
| 셀 수 없이 | innumerably, countlessly | adverb (phrase) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 116. |
| 소설가 | novelist, fiction writer | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 116. |
| 시인 | poet | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 116. |
| 시장하다 | to be hungry (HON.); 배가 고프다 "to be hungry (plain)" | verb (descriptive) | formal | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 116. Honorific/plain register pair explicitly given. |
| 예술 | art; 예술적 "artistic" | noun/adjective | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 116. |
| 오페라 | opera | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 116. Loanword (English/Italian). |
| -을/를 빼고 | without, except, leaving out; 빼다 "to take out, to leave out" | particle (compound)/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 116. |
| 음식 | (cooked) food; 음식 솜씨 "cooking skill" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 116. |
| 전라도 | Chŏlla Provinces | proper noun | core | — | contemporary (source published 2002) | southwestern Korea | regional | grammar_reference | n/a | verified | p. 116. |
| 전통 | tradition | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 116. |
| -점 | piece (of artwork); 그림 한 점 "one painting" | counter | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 116. |
| 정도 | extent, degree | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 116. |
| 주유소 | gas station | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 116. |
| 즐기다 | to enjoy, to have fun | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 116. |
| 초대하다 | to invite; 초대 "invitation" | verb/noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 116. |
| 출신 | origin, birth; graduate; 출신이다 "to come from; to be a graduate of" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 116. |
| 판소리 | *p'ansori* (traditional Korean song) | noun | core | — | contemporary (source published 2002) | Korea | national | grammar_reference | n/a | verified | p. 116. Named traditional Korean performing-art genre. |
| 평화스러운 | peaceful; 평화스럽다 "to be peaceful"; 평화 "peace" | adjective/verb/noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 116. |
| 한정식 | Korean full-course meal | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 116. |
| 해남 | city of Haenam in South Chŏlla Province | proper noun | core | — | contemporary (source published 2002) | South Chŏlla Province, Korea | regional | grammar_reference | n/a | verified | p. 116. |
| 화가 | painter, artist | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 116. |
| 휴게소 | rest area | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 116. |

### Grammar points

**1. V. + ㄹ/을까 봐** — "(because)... afraid that," "in anticipation of." Explains the reason for
the main clause's action/event, motivated by apprehension of a possible outcome. p. 116-117.

**2. A.V. + (어/아) 있다** — "to be in the state/place of," "to be still..." Resultant-state
construction, typically with 오다/가다/앉다/서다/남다/비다/붙다/쌓이다/뜨다-class verbs (가 있다,
서 있다, 붙어 있다, 쌓여 있다, 떠 있다). Cross-referenced to the helping-verb chart at L14 GN7.
p. 117.

**3. A.V. + 느라(고)** — "for doing...," "(in order) to do..." Indicates the reason for or purpose
of an action, often implying a resulting negative consequence (회사 일을 하느라고 바빴다 "I was busy
working on company business"). Compare `established/006`'s sibling coverage of this same connective
in *Continuing Korean*. p. 117-118.

**4. Idiomatic use of 을/를 빼고 "without"** — Literally "subtracting"/"taking out," but translates
as "without" (비빔밥에 고기를 빼고 주세요 "Please make my *bibimbap* without meat"). p. 118.

**5. V. + ㄴ/는/었/았단다** — "(I am telling you)...," "(I say)..." Intimate sentence ending marking
the speaker informing the listener of a fact, glossed by the source as equivalent to English
colloquial "you know"/"I am telling you." p. 118.

**6. N. + (이)라면서요? / D.V. + 다면서요? / A.V. + ㄴ/는다면서요?** — "is it true that...?," "is
(what I heard) true?" Casual question asking the listener to confirm something the speaker heard or
was told. p. 118-119.

**7. Reading mathematical terms** — A compact reference paradigm for reading arithmetic aloud:
더하기 "addition" (이 더하기 삼은 오, "2+3=5"), 빼기 "subtraction," 곱하기 "multiplication," 나누기
"division," 분수 "common fraction" (삼분의 일 = 1/3, read as "of-three, one"), 소수 "decimal
fraction" (이점 삼사 = 2.34), and the terms 짝수 "even number" / 홀수 "odd number." A genuinely
useful, compact numerical-register table not found elsewhere in the Wave 1/2 Korean corpus so far.
p. 119.

---

## Lesson 13 — 제주도 (Cheju Island) — printed pp. 124-130, PDF pp. 144-150

Full vocabulary and grammar notes vision-read (single vocabulary list, no separate Extra Reading
this lesson). Narrative/dialogue/exercises not separately transcribed. This lesson touches on Cheju's
distinctive regional culture (the 해녀 women-diver tradition, dialect/lifestyle divergence from the
mainland noted in-narrative, though not tagged with the book's explicit dialect markers).

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 경유하여 | through, by way of; 경유하다 "to pass through, to go by way of" | adverb/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 125. |
| 경험 | experience; 경험하다 "to experience" | noun/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 125. |
| 다행이다 | to be fortunate | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 125. |
| 돌 | stone, rock | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 125. |
| 둘러싸다 | to surround, to wrap around | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 125. |
| 따오다 | to pick off (a tree) and bring; 따다 "to pick off" | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 125. |
| 몽고군 | Mongolian army; 몽고 "Mongolia" | noun | core | — | contemporary (source published 2002) | attested (13th-century Mongol invasions) | — | — | grammar_reference | n/a | verified | p. 125. |
| 뭐하러 | for what | adverb (phrase) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 125. |
| 미리 | ahead, in advance | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 125. |
| 바람 | wind; 바람이 불다 "wind blows" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 125. |
| 밥하다 | to cook | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 125. |
| 방식 | way, method, manner; 생활 방식 "way of life" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 125. |
| 본토 | mainland | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 125. |
| 봐 두다 | to inspect, to see ahead | verb (compound) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 125. |
| 뿐만 아니라 | not only; 뿐 "only" | adverb (phrase) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 125. |
| 새로운 | new; 새롭다 "to be new, to be fresh" | adjective/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 125. |
| 섬 | island | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 125. |
| 식물 [싱물] | plants | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 125. |
| 신혼여행 | honeymoon | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 125. |
| 언어 | language | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 125. |
| -에 의하면 | according to; 의하다 "to be based on" | particle (compound)/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 125. |
| -에 의해서 | by means of, in accordance with | particle (compound) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 125. |
| 여행하다 | to travel | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 125. |
| 요새; 요즘 | these days | noun/adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 125. Two synonyms given. |
| 육지 | land, shore | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 125. |
| 이미 | already | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 125. |
| 점 | point, issue; 다른 점 "different point"; 좋은 점 "good point" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 125. |
| 정복하다 | to conquer | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 125. |
| 제주도 | Cheju Island (south of Korean Peninsula), Cheju Province | proper noun | core | — | contemporary (source published 2002) | Cheju Island, Korea | regional | grammar_reference | n/a | verified | p. 126. |
| 제주시 | city of Cheju (on Cheju Island) | proper noun | core | — | contemporary (source published 2002) | Cheju Island, Korea | regional | grammar_reference | n/a | verified | p. 126. |
| 직행 [지캥] | direct route, nonstop route; 직행 표 "express ticket, nonstop ticket" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 126. |
| 집안 일 | housework | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 126. |
| 처녀 | maiden, virgin | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 126. |
| 총각 | bachelor, single man | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 126. |
| 침략하다 [침냑하다] | to invade | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 126. |
| 타원형 | oval shape; 둥글다 "to be round" | noun/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 126. |
| 특이하다 | to be unique, to be peculiar | verb (descriptive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 126. |
| 파도 | waves | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 126. |
| 푸른 | blue, azure; 푸르다 "to be blue, to be azure" | adjective/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 126. |
| 한- | right; 한가운데 "right in the middle of" | prefix | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 126. |
| 한라산 [할라산] | Mount Halla | proper noun | core | — | contemporary (source published 2002) | Cheju Island, Korea | regional | grammar_reference | n/a | verified | p. 126. Korea's highest peak, a dormant volcano. |
| 할 수 없이 | having no choice, without any other choice; 할 수 없다 "can't help it" | phrase/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 126. |
| 해녀 | woman sea diver | noun | core | — | contemporary (source published 2002) | Cheju Island, Korea | regional | grammar_reference | n/a | verified | p. 126. Distinctive Cheju regional occupation/tradition, explicitly discussed in-dialogue as a declining tradition among young women. |
| 홀로 | alone | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 126. |
| 화산 | volcano (volcanic mountain) | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 126. |
| 힌트 | hint | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 126. Loanword (English). |

### Grammar points

**1. A.V. + (어/아) 두다** — "...and keep." Helping verb (like `-보다`, `-버리다`, `-놓다`) marking
preservation of the main verb's result for future use (봐 두다 "to see and keep the knowledge for
future use," 사 두다 "to buy and keep"). Cross-referenced to the full helping-verbs chart at L14
GN7. p. 126-127.

**2. A.V. + (어/아) 대다** — "to keep on doing," "to do repeatedly." Helping verb marking continuing
or repeated action (웃어 댄다 "they keep laughing," 떠들어 댔다 "talked loudly on and on"). Also
cross-referenced to the L14 GN7 helping-verbs chart. p. 127.

**3a. V. + 었/았던** — "used to do," "was doing..." / **3b. N. + (이)었던** — "used to be." Verbal
modifier marking a habitually-performed-in-the-past or uncompleted past activity (화산이었던 산
"[a] former volcanic mountain," 해녀였던 여자 "a woman who used to be a sea diver"). p. 127-128.

**4a. V. + ㄹ/을 뿐만 아니라** — "not only... but also," "as well as" / **4b. N. + 뿐만 아니라 /
N. + 도** — "not only N. but also N...." Marks both conjuncts as equally important. p. 128.

**5a. 할 수 없이...** — "having no choice," "without an alternative" / **5b. 할 수 없다** — "can't
help it," "can't do." Typically preceded by a clause in `-(어/아)서`, `-지만`, `-(으)므로`, or
`-어/아도`; with no connected clause, preceded by 그래서. p. 129.

**6. V. + 게 되다** — "it turns out that," "it happens that," "it becomes that." Marks an action/
event occurring without the actor's/subject's volition — a genuinely important middle-voice-like
construction, typically preceded by an explanatory/causal `-(어/아)서` or `-기 때문에` clause.
p. 129-130.

---

## Lesson 14 — 설날 (New Year's Day) — printed pp. 132-139, PDF pp. 152-159

Vocabulary (main + Extra Reading "설날 지내기," "Observing New Year's Day," a rich sociocultural/
folk-custom passage) and full grammar notes vision-read, including the book's own comprehensive
**helping verbs chart** (this lesson's standout content). Narrative/dialogue/exercises not
separately transcribed.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 건강한 | healthy; 건강하다 "to be healthy"; 건강 "health" | adjective/verb/noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 133. |
| 결심하다 | to determine; 결심 "determination" | verb/noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 133. |
| 국제 전화 | international phone call | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 133. |
| 귀국하다 | to return to one's home country | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 133. |
| 그믐날 | the last day of the month | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 133. |
| 깜빡 | momentarily, in an instant of time | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 133. |
| 대강 | roughly, generally | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 133. |
| 떡국 | rice-cake soup | noun | core | — | contemporary (source published 2002) | Korea | national | grammar_reference | n/a | verified | p. 133. Traditional New Year's Day dish. |
| 마음 | heart, mind, thought | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 133. |
| 매년; 매해 | every year | noun/adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 133. |
| 몸 | body | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 133. |
| 미루다 | to postpone, to put off | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 133. |
| 바꿔 주다 | to change (for someone); 전화를 바꿔 주다 "to put (someone) on the phone" | verb (compound) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 133. |
| 별 일 | strange event, unexpected thing; 별- "strange, unexpected" | noun/prefix | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 133. |
| 복 받다 | to be blessed; 복 "blessing" | verb (compound)/noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 133. |
| 사촌 | cousin | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 133. |
| 세배 | *sebae* (formal bow of respect to elders on New Year's Day); 세배 가다 "to pay visit of respect on New Year's Day"; 세배 드리다/세배하다 "to perform *sebae*" | noun/verb | core | — | contemporary (source published 2002) | Korea | national | grammar_reference | n/a | verified | p. 134. Named traditional Korean New Year's ritual. |
| 습관 | habit, custom | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 134. |
| 시차 | time difference | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 134. |
| 신년 계획 | New Year's plan | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 134. |
| 쓸쓸히 | lonely; 쓸쓸하다 "to be lonely" | adverb/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 134. |
| 아차 | Oops! | interjection | colloquial | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 134. |
| 연락하다 | to contact, to get in touch with; 연락 "contact" | verb/noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 134. |
| 웬만큼 | tolerably, acceptably; 웬만하다 "to be at an acceptable level" | adverb/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 134. |
| 윷놀이하다 | to play *yut* game; 윷놀이 "*yut* game, Four-Stick Game" | verb/noun | core | — | contemporary (source published 2002) | Korea | national | grammar_reference | n/a | verified | p. 134. Named traditional Korean board game. |
| 이제; 인제 | by now, now | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 134. |
| 인사 | greeting; 새해 인사 "New Year's greeting"; 인사하다 "to greet" | noun/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 134. |
| 튼튼한 | strong, healthy; 튼튼하다 "to be strong, to be healthy" | adjective/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 134. |

**Extra Reading vocabulary (읽기: 설날 지내기, p. 134-135):**

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 갈아 입다 | to change clothes | verb (compound) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 134. |
| 눈썹 | eyebrows | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 134. |
| 동지 | winter solstice | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 134. |
| 밀가루 | flour | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 134. |
| -살 먹다 | to get to be... years old (colloquial) | verb (compound) | colloquial | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 134. |
| 뿌리다 | to scatter | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 134. |
| 새우다 | to stay up; 밤을 새우다 "to stay up all night" | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 135. |
| 섣달 그믐날 | the year's last month's last day, New Year's Eve | noun (phrase) | core | — | contemporary (source published 2002) | Korea | national | grammar_reference | n/a | verified | p. 135. |
| 설 쇠다 | to celebrate New Year's Day | verb (compound) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 135. |
| 설빔 | New Year's Day attire | noun | core | — | contemporary (source published 2002) | Korea | national | grammar_reference | n/a | verified | p. 135. |
| 졸리다 | to be sleepy; 졸다 "to doze off" | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 135. |
| 팥죽 | red bean porridge | noun | core | — | contemporary (source published 2002) | Korea | national | grammar_reference | n/a | verified | p. 135. Traditional winter-solstice dish. |
| 하얘지다 | to turn white; 까매지다 "to turn black or dark" | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 135. |
| 함께 | together | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 135. |

### Grammar points

**1. V. + ㄹ/을 것** — "one should/must (do)." Used for memos, short instructions, and to-do lists;
marks an order or imperative voice (오늘 방 청소 할 것 "Clean my room today"). p. 135.

**2. A.V. + (어/아) 버리다** — "to end up doing...," "to do... (completely)." Helping verb for
emphasis, marking a completely finished action or an unintended/inevitable outcome. Cross-referenced
forward to the full helping-verbs chart at GN7 below. p. 135.

**3. A.V. + ㄹ/을 만하다** — "it is worth doing," "it is doable," "to be deserving." (한국어는 배울
만하니? "Is Korean learnable?"). p. 136.

**4. N. + (이)랑** — "and," "with." Colloquial and dialectal equivalent of `-와/과` (more written) and
`-하고` (more colloquial) — source explicitly frames `-(이)랑` as carrying its own regional/dialectal
color distinct from the other two near-synonyms. p. 136.

**5. Plural marker -들** — Korean nouns don't always require number-marking; `-들` can attach to
adverbs and some connectives (not just nouns) to indicate plurality of the subject — a genuinely
distinctive typological point (재미있게들 놀아라! "Have a good time [you all]!"; 여기서들 기다리세요
"Please [you all] wait here"). p. 136-137.

**6. Epenthetic ㅅ: 사이 시옷** — "-'s," "of." Many compound nouns take `ㅅ` after the first noun to
mark a possessive/genitive relationship (동짓날 ← 동지+ㅅ+날 "winter solstice + 's + day"). Full
worked set: 빗물 "rainwater," 빗방울 "raindrop," 햇빛 "sunshine," 바닷가 "seashore," 촛불
"candlelight," 기찻길 "train track." Explicitly flags that not all genitive compounds take ㅅ (머리말
"preface," not 머릿말; 낚시터 "fishing place"; 담배벌레 "tobacco hornworm") — a real, non-fully-
predictable orthographic/morphophonological rule directly relevant to compound-word slang formation.
p. 137.

**7. Helping verbs chart** — The single most comprehensive helping-verb reference table in the book:
a full **Main Verb type × Verb-Base allomorph × Helping Verb × Aspect × Example × Gloss** grid
covering 17 distinct helping-verb constructions and their aspectual meanings: `-어/아 버리다`
(completion), `-어/아 내다` (willful action), `-어/아 나다` (spontaneous), `-어/아 주다`/`-어/아
드리다` (benefactive, HON.), `-어/아 보다` (experience/"try —ing"), `-어/아 대다` (repetition),
`-어/아 두다` (accumulation), `-어/아 넣다` (placing into), `-어/아 놓다` (placing/keeping), `-어/아
가지다` (possession), `-어/아 지다` (automatic change of state, D.V. & some A.V.), `-어/아 가다`¹
("take away"), `-어/아 오다` ("bring"), `-어/아 가다`² ("is about to"), `-어/아 있다` (resultant
state), `-고 있다` (continuation), `-고 싶다` (wish), `-게 하다`/`-게 만들다` (causative, D.V. &
A.V.), and the supposition/guessing family `-ㄴ/은가 보다/싶다`, `-는가 보다/싶다`, `-ㄹ/을까 싶다`,
`-나 보다`. This single table gathers together and cross-references many helping-verb constructions
already documented piecemeal in earlier lessons/sibling books (e.g. L12 GN2's `-(어/아) 있다`, L13
GN1-2's `-(어/아) 두다`/`-(어/아) 대다`) — genuinely the most systematic helping-verb reference found
across the Korean corpus so far, directly useful for later morphological-play mechanics analysis.
p. 137-138.

---

## Lesson 15 — 노래 자랑 (Song Contest) — printed pp. 141-151, PDF pp. 161-171

Vocabulary (main + Extra Reading "가고파," lyrics of a second traditional song) and full grammar
notes vision-read, including the book's own comprehensive **passive-verbs suffix chart** (this
lesson's standout content). This lesson's own body text reproduces two full traditional Korean song
lyric sets (고향의 봄 "Spring in My Hometown," 우리의 소원 "Our Wish") with their own vocabulary
glosses — a distinct literary/poetic register with archaic forms (그리워라, 잊으리오, 보고파라,
살고 지고, 온갖) not seen in the book's ordinary prose. Per copyright discipline, only representative
lines/vocabulary are captured below, not the full song texts. Narrative/dialogue/exercises not
separately transcribed.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가고파 | "Longing to Go" (song title) | proper noun | literary | — | contemporary (source published 2002) | Korea | national | grammar_reference | n/a | verified | p. 142. |
| 가사 | lyrics | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 142. |
| 각; 각각 | each | determiner/adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 142. |
| 곡 | tune, piece (of music) | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 142. |
| 기회 | opportunity, chance | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 142. |
| 노래자랑 | song contest | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 142. |
| 다수결 | majority decision; 다수 "majority" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 142. |
| 대회 | meeting, conference, competition | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 142. |
| 독창 | solo (singing) | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 142. |
| -등 | place (in contest); 일 등 "first place"; 이 등 "second place" | counter | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 143. |
| 맡다 | to be in charge of, to take on (responsibility) | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 143. |
| 모임 | meeting, gathering | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 143. |
| -못지 않게 | as good as | particle (compound) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 143. |
| 박수 | applause; 박수 치다 "to applaud" | noun/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 143. |
| 반 | class | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 143. |
| 반주 | accompaniment (in music); 반주하다 "to accompany (in music)"; 반주자 "accompanist" | noun/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 143. |
| 발표하다 | to present, to announce; 발표 "presentation, announcement" | verb/noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 143. |
| 벗기 | taking off; 벗다 "to take off"; 옷을 벗다 "to take off clothes" | noun (nominalized)/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 143. |
| 뽑히다 [뽀피다] | (Vi.) to be selected; 뽑다 (Vt.) "to select" | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 143. |
| 상 | prize, award; 상을 받다 "to win a prize" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 143. |
| 시합 | competition, match | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 143. |
| 심사 위원 | judge (for contest); 심사하다 "to judge, to assess" | noun/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 143. |
| 연습 | exercise, practice; 연습하다 "to practice" | noun/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 143. |
| 외우다 | to memorize, to recite | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 143. |
| 이기다 | to win | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 143. |
| 인기이다; 인기가 있다 | to be popular; 인기 [인끼] "popularity" | verb/noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 143. |
| 작곡 | composition (music), composed by; 작곡하다 "to compose" | noun/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 143. |
| 작사 | writing lyrics, lyrics by; 작사하다 "to write lyrics" | noun/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 143. |
| 지휘 | direction (music); 지휘하다 "to conduct (in music)"; 지휘자 "conductor" | noun/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 143. |
| 청중 | audience | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 143. |
| 충고 | advice; 충고하다 "to advise" | noun/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 143. |
| 크게 | largely, remarkably, loudly | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 143. |
| 투표하다 | to vote, to take a ballot; 투표 "voting, balloting, a vote" | verb/noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 143. |
| 틈 나다 | to have spare time; 틈 "spare time" | verb (compound)/noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 143. |
| -편 | side, party; 우리 편 "our side" | noun (counter) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 143. |
| 피아노 | piano; 피아노를 치다 "to play piano" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 143. Loanword (English). |
| 한턱 내다 | to treat (to a meal); 한턱 "a treat (colloquial)" | verb (compound)/noun | colloquial | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 143. |
| 합창 | chorus, choir; 합창하다 "to sing in a choir" | noun/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 143. |
| 후보 | candidate | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 143. |

**Song-lyric vocabulary (고향의 봄/"Spring in My Hometown" and 가고파/"Longing to Go," representative
sample, p. 144-146):**

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 고향 | hometown | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 144. |
| 그립다 | to long for, to miss | verb (descriptive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 144. |
| 울긋불긋 | colorful, variegated | adverb (mimetic) | literary | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 144. From song lyrics. |
| 그리워라 | (I) miss, (I) long for | verb (archaic/poetic exclamatory form) | literary | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 146. Archaic/poetic sentence-final form (그립다 + archaic exclamatory -어라), found only in song-lyric register. |
| 잊으리오 | how (can I) forget | verb (archaic/poetic rhetorical-question form) | literary | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 146. Archaic rhetorical-question ending, song-lyric register only. |
| 보고파라 | (I) wish to see, (I) miss seeing | verb (archaic/poetic form) | literary | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 146. |
| 어이타가 | why, what (went wrong) (short form of 어찌 하다가) | adverb (archaic contraction) | literary | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 146. |
| 얼리다 | to join, to mingle (short form of 어울리다) | verb (archaic contraction) | literary | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 146. |
| 온갖 | all kinds | determiner | literary | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 146. |
| 통일 | unification; 통일되다 "to be unified" | noun/verb | core | — | contemporary (source published 2002) | Korea | national | grammar_reference | n/a | verified | p. 145. From "Our Wish," a real Korean-unification-themed song; sociopolitically loaded vocabulary item. |
| 겨레 | (nation's) people | noun | literary | — | contemporary (source published 2002) | Korea | national | grammar_reference | n/a | verified | p. 145. Poetic/nationalistic register term for "the (Korean) people." |

### Grammar points

**1. Nominalization with -기 versus -ㅁ/음 (and -는 것)** — A genuinely important, systematic
comparison the sibling `established/011` earlier chunk (L11 GN2) only partially covered:
`-기` attaches directly to a verb stem and indicates "the act of doing"; `-ㅁ/음` attaches to a verb
stem/tense marker and indicates "the fact of doing" or "the state of being," and is more limited in
distribution. `-기` is generally preferred with 좋다/재미있다/싫다/나쁘다/쉽다/어렵다/편하다/불편하다.
`-는 것` can substitute for `-기` with a subtle meaning shift toward emphasizing "the fact of."
`-ㅁ/음` is additionally used for note-taking/journal-style cryptic statements (오늘 수업시간에 제
15과를 배웠음 "Today I/we learned Lesson 15"). Several `-ㅁ/음`-derived forms have fully lexicalized
into ordinary nouns: 웃음 "laugh," 울음 "cry," 기쁨 "joy," 슬픔 "sadness," 춤 "dance," 잠 "sleep," 꿈
"dream," 도움 "help," 어둠 "darkness." p. 147-148.

**2. A.V. + (어/아) 가지고** — "having done...," "after doing..." Colloquial equivalent of `-ㄴ/은
후에` or `-(어/아)서`. p. 148.

**3. V. + ㄹ/을 때마다** — "whenever," "every time." `-ㄹ/을` always precedes `때마다` regardless of
tense. p. 149.

**4. Making passive verbs with 이, 히, 리, and 기** — A major grammar point: roughly 150 transitive
verbs form their passive via one of four suffixes. The source's own full **Passive verbs chart**
tabulates the most frequent examples by suffix group: **이**-passives (보다→보이다 "to be seen,"
나누다→나뉘다 "to be divided," 덮다→덮이다 "to be covered," 섞다→섞이다 "to be mixed," 쌓다→쌓이다
"to be piled," 씹다→씹이다 "to be chewed," 치다→치(이)다 "to be run over"); **히**-passives
(뽑다→뽑히다 "to be selected," 잡다→잡히다 "to be caught," 박다→박히다 "to be pegged," 닫다→닫히다
"to be closed," 밟다→밟히다 "to be stepped on," 씹다→씹히다 "to be chewed," 읽다→읽히다 "to be
read"); **리**-passives (끌다→끌리다 "to be pulled," 듣다→들리다 "to be heard," 밀다→밀리다 "to be
pushed," 열다→열리다 "to be open," 누르다→눌리다 "to be pressed"); **기**-passives (감다→감기다 "to
be wound," 끊다→끊기다 "to be cut," 빼앗다→빼앗기다 "to be deprived," 안다→안기다 "to be held [in
the arms]," 쫓다→쫓기다 "to be chased"). Notes these suffixes overlap with the causative suffixes on
some verbs (cross-referenced forward to L17 GN3 and GN7). A second passive strategy, `-(어/아)지다`,
is cross-referenced back to L5 GN3. This is a genuinely major morphological-derivation reference for
later mechanics analysis — the clearest single-page catalog of Korean's lexical (suffix) passive
system found in the Korean corpus so far. p. 149-150.

**5. A.V. + ㄹ/을 줄 알다 / A.V. + ㄹ/을 줄 모르다** — "to know/not to know (how to)." p. 150.

**6. N. 못지 않게** — "as good/well as," "(even) better/more than." Marks the subject as equaling or
exceeding the compared noun; cross-referenced to `-만큼` at L9 GN2. p. 150-151.

---

## Lesson 16 — 발렌타인 데이 (Saint Valentine's Day) — printed pp. 154-161, PDF pp. 174-181

Vocabulary (main + Extra Reading "신세대 이야기," "The New Generation Story") and full grammar notes
vision-read. **This lesson's Extra Reading is directly relevant to the project's slang-mechanics
purpose**: it explicitly describes Korea's post-1970s-economic-growth "신세대" (New Generation) youth
cohort as distinguished by freer thinking/behavior that surprises older generations, and states
outright that "그들은 특이한 유머 감각으로 새로운 낱말과 언어를 만들어 낸다" ("they create new words
and language with their unique sense of humor") — the book's own explicit acknowledgment of youth
neologism/slang-coining as a named generational phenomenon, not just an incidental register note.
A footnote also explicitly describes the real gendered Valentine's Day (Feb. 14, women give gifts to
men) / White Day (March 14, men give gifts to women) custom split. Narrative/dialogue/exercises not
separately transcribed.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 고객 | customer | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 155. |
| 궁금하다 | to be curious about | verb (descriptive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 155. |
| 그대로 | as it is | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 155. |
| 그저께 | the day before yesterday | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 155. |
| -끼리 | together with, in a group, by themselves; 우리끼리 "by ourselves" | particle | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 155. |
| 남 | others, other person, stranger | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 155. |
| 낭비하다 | to waste; 낭비 "waste" | verb/noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 155. |
| 너도나도 | everyone | pronoun (idiom) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 155. |
| 따라가다 | to follow, to go with, to accompany, to follow in one's steps | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 155. |
| 또래 | of the same age group, of the peer group | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 155. |
| 모레 | the day after tomorrow | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 155. |
| 무늬 | pattern, figure; 꽃무늬 "floral pattern" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 155. |
| 바람에 | as the result of, because of | particle (compound) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 155. |
| 발렌타인 데이 | Saint Valentine's Day | proper noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 155. Loanword. Footnote: in current Korean custom, Feb. 14 is for women to give gifts to men, while March 14 ("White Day") is for men to give gifts to women — an explicit real sociocultural gender-role note. |
| 백화점 [배콰점] | department store | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 155. |
| 붐비다 | to be crowded | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 155. |
| 생신 | birthday (HON.); 생일 "birthday (plain)" | noun | formal | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 155. |
| 서양 | occidental, the Occident, Western world; 동양 "Orient" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 156. |
| 선물 | gift, present | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 156. |
| 손님 | customer | noun | formal | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 156. |
| 쉽게 | easily | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 156. |
| 스카프 | scarf | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 156. Loanword (English). |
| 실수하다 | to make a mistake; 실수 "mistake, blunder" | verb/noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 156. |
| 애인 | girlfriend or boyfriend, lover | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 156. |
| 유행 | trend, fashion; 유행이다/유행하다 "to be trendy, to be in fashion" | noun/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 156. |
| 이유 없이 | without reason; 이유 "reason" | adverb (phrase)/noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 156. |
| 점원 | shop clerk | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 156. |
| 판매원 | salesperson | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 156. |
| 편리하다 | to be convenient | verb (descriptive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 156. |
| 평소 | ordinary times; 평소에 "usually, ordinarily" | noun/adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 156. |
| 풍습 | custom, practices | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 156. |
| -한테 | to (a person) (indirect object marker in colloquial and intimate speech) | particle | colloquial | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 156. |
| 휩쓸리다 | to be swept up, to be seized, to be overrun; 휩쓸다 "to sweep, to seize, to overrun" | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 156. |

**Extra Reading vocabulary (읽기: 신세대 이야기, p. 156-157):**

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 감각 | sense; 유머 감각 "sense of humor" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 156. |
| 경제적 | economical | adjective | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 156. |
| 나이 든 | old; 나이 들다 "to mature or get old" | adjective/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 156. |
| 낱말 [난말] | word, vocabulary | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 156. |
| 성장 | growth; 성장하다 "to grow, to expand"; 경제 성장 "economic growth" | noun/verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 156. |
| 신세대 | new generation | noun | core | — | contemporary (source published 2002) | Korea (post-1970s cohort) | national | grammar_reference | n/a | verified | p. 157. Named sociolinguistic generational cohort, explicitly linked in-text to slang/neologism creation — directly relevant to this project's slang-mechanics purpose. |
| 어려움 | difficulty, hardship | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 157. |
| 유머 | humor; 유머(가) 있다 "to be humorous" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 157. Loanword (English). |
| 이후 | after this (point), since | noun/adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 157. |
| 자라다 | to grow up, to be raised | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 157. |

### Grammar points

**1. A.V. + 느니 (차라리)** — "(I) would rather," "it is better to..." Often paired with 차라리 for
emphasis, and often followed by `-는게 낫다` ("it's preferable to do... than..."). Source gives two
popular sayings using this pattern: 앓느니 죽는다 ("I would rather die than be sick," i.e., suffer
from illness) and 시키느니 내가 한다 ("I would rather do it myself than have someone else do it") —
genuine proverbial/idiomatic material. p. 157.

**2. N. + 와/과(는) 달리 / V. + ㄴ/은/는 것과(는) 달리** — "unlike," "different from." Appends a
dedicated note on Korean verbs that take `-와/과` or `-하고` in senses English would mark differently
("from," "with," "to," or as a direct object): 다르다 "differs from," 같다 "equals," 비슷하다 "is
similar to," 결혼하다/약혼하다 "marries/is engaged to," 사귀다 "goes out with," 싸우다 "fights
against/with each other," 만나다 "meets with." p. 157-158.

**3. -말이에요 as a question and a statement** — "do you mean...?," "I mean." Colloquial ending
whose question/statement function is disambiguated purely by intonation (rising = question, level/
falling = statement) — the same intonation-only ambiguity pattern already seen at L4 GN4. Common
contractions: `-(이)라는 말이에요` → `-(이)란 말이에요`; `-다는 말이에요` → `-단 말이에요`. p. 158-159.

**4. A.V. + 는 바람에** — "as the result of," "because of." Literally "in the midst of the (whirl)
wind" — an idiomatic causal connective, usually used in a negative context. p. 159-160.

**5. Many uses of -대로** — a. `N. + 대로` / b. `V. + ㄴ/은/는/ㄹ/을 대로` — "as is," "as (someone)
does/says"; c. `A.V. + 는 대로` — "as soon as." Three distinct senses of the same suffix depending on
attachment: bare-noun "as-is" (이대로 쓰세요 "please write like this"), reported-manner "as X does/
says" (형이 시키는 대로 해라 "do as your older brother tells you"), and temporal "as soon as"
(서울에 가는 대로 편지할게 "I'll write as soon as I get to Seoul"). p. 160.

**6. 그대로** — "as (it) is," "the way (it) is." Frequently used in a request/command (그대로
두세요 "please leave it alone"); cross-referenced to the `-대로` connective at GN5 above. p. 160-161.

**7. A.V. + 곤 하다 / A.V. + 곤 했다** — "from time to time, it does," "now and then" (present) /
"used to" (past). Marks repeated/habitual action. p. 161.

---

## Lesson 17 — 대통령 선거 (Presidential Election) — printed pp. 165-169, PDF pp. 185-190 (partial — through GN4; GN3's causative-verbs chart and GN5 onward reserved for part 2)

Vocabulary (main; no Extra Reading reached within this chunk's page range) and grammar notes 1-4
vision-read. Narrative/dialogue/exercises not separately transcribed. This lesson's topic (a real
Korean presidential election, National Assembly/Congress comparison) is itself sociopolitical-
register content distinct from earlier lessons' cultural/travel topics.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가능성 | possibility | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 166. |
| 곤란하다 [골란] | to be difficult, to be hard, to be tough | verb (descriptive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 166. |
| -에 관한 | regarding, concerning, about | particle (compound) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 166. |
| 국회 의원 | member of the Korean National Assembly | noun | core | — | contemporary (source published 2002) | Korea | national | grammar_reference | n/a | verified | p. 166. |
| 다가오다 | to approach, to near | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 166. |
| 당선되다 | to be elected, to win election | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 166. |
| 대통령 | president | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 166. |
| 맡기다 | to entrust, to charge with a duty | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 166. |
| 붙어 있다 | to be stuck on, to be fastened to, to be posted | verb (compound) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 166. |
| 뽑다 | to choose, to select, to elect | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 166. |
| 사진 | photo | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 166. |
| 상원 의원 | senator | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 166. U.S.-specific term, used contrastively with Korean 국회 의원. |
| 선거 | election; 선거 운동 "election campaign" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 166. |
| 신중하게 | prudently, cautiously, discreetly | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 166. |
| 아이구 | My goodness! Oh my! | interjection | colloquial | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 166. |
| 오래간만에 | after a long time | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 166. |
| 온통 | all, entirely, altogether | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 166. |
| 올해; 금년 | this year | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 166. Native/Sino-Korean synonym pair. |
| 이해하다 | to understand; 이해 "understanding" | verb/noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 166. |
| 정치 | politics | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 166. |
| 집중되다 | to be focused; 집중하다 "to concentrate" | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 167. |
| 하원 의원 | congressman, congresswoman | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 167. U.S.-specific term, used contrastively with Korean 국회 의원. |
| 후보; 후보자 | candidate | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | p. 167. |

### Grammar points

**1a. N. + 에 관해(서)/관하여** — "about," "concerning" (followed by a verbal clause) / **1b. N. +
에 관한** — "about," "on" (followed by a noun/noun phrase). p. 167.

**2. Verbs with 가다 and 오다: V. + (어/아) 오다 / V. + (어/아) 가다** — "to do... and bring" / "to
do... and take," "to progress/go... (ADV.)." Korean has no single-word verb for "to take" or "to
bring" — these meanings are built compositionally from a main verb + directional helping verb
(가져 가다 "to have and go" = "to take," 가져 오다 "to have and come" = "to bring"; similarly 사 오다
"to buy and bring," 캐 오다 "to dig up and bring"). Cross-referenced to the L14 GN7 helping-verbs
chart. The source's own extensive worked list (20 pairs): 잘 해 오다/가다, 요약해 오다/가다, 가져
오다/가다, 사 오다/가다, 물어 오다/가다 ("to bring/carry by mouth, of an animal"), 알아 오다/가다,
집어 오다/가다, 씻어 오다/가다, 싸 오다/가다, 찾아 오다 ("to come to visit")/찾아 가다 ("to go to
visit"), 끌어 오다/가다. For some verbs `-어/아 가다` additionally marks an action/event as
"progressing" (well/slowly/fast): 잘 되어 간다 "it is going well." A genuinely productive
directional-compounding system directly relevant to later morphological-play mechanics analysis.
p. 167-168.

**3. Causative suffixes 이, 히, 리, 기, 우, 구, and 추** — Suffixes that turn certain (intransitive
or otherwise non-causative) verbs into causative verbs ("cause"/"make X happen"): 대통령에게 나라를
맡긴다 "the president is entrusted with the nation," 학생에게 책을 읽혔다 "(I) made the students
read books," 부모님이 재산을 늘리셨다 "my parents increased their assets," 동생에게 심부름을 시켰다
"(I) sent my little brother on an errand." Source states roughly 132 verbs form a causative this
way, with the 40 most common tabulated in a forward-referenced chart (GN7, past this chunk's page
range — reserved for the part-2 dispatch). Explicitly cross-references two alternative
causative-forming strategies: `-게 하다` ("make someone do...," works for all verbs, detailed at L25
GN2) and `-시키다` (works for some verbs, detailed at L22 GN6). **Important morphological note**:
the four suffixes 이/히/리/기 are the *same* surface forms as the passive suffixes documented at L15
GN4 — a genuine causative/passive syncretism in Korean's verbal morphology, worth flagging for
mechanics analysis (surface-ambiguous derivational suffixes are a natural site for slang
reanalysis/wordplay). p. 169.

**4. A.V. + 기에(는)** — "as," "as for." Frequently used with 보다/듣다/알다/생각하다 to mark the
speaker's own subjective experience or opinion (제가 보기에는 이 책은 학생들에게 좋은 것 같아요 "In
my view, this book seems good for the students"; 제가 알기에는... "As far as I know..."). p. 169.

---

## Summary

This chunk fully extracts Lessons 1-16 (vocabulary + grammar notes) and Lesson 17's vocabulary and
grammar notes 1-4, of *Intermediate College Korean* — roughly 820 vocabulary entries and 100+
grammar points/subpoints across 17 lessons. Standout non-redundant content relative to
`established/001`/`003`/`004` (the Byon *Basic*/*Intermediate Korean* books already extracted):
the full nonpolite/plain-speech-level paradigm table (L2 GN1), the directional-metaphor
올라가다/내려가다 convention (L6 GN2), the five-tier politeness gradient for suggestions (L8 GN3),
the `-적으로` Sino-Korean adverb-formation rule (L7 GN4), the `-ㅁ/음` vs. `-기` nominalizer contrast
(L11 GN2, L15 GN1), the comprehensive helping-verbs chart (L14 GN7) and passive-verbs suffix chart
(L15 GN4), the directional-compound-verb system with 가다/오다 (L17 GN2), the causative-suffix system
and its surface overlap with the passive suffixes (L17 GN3), the mathematical-terms reading paradigm
(L12 GN7), and the explicit "New Generation" (신세대) youth-neologism sociolinguistic note (L16
Extra Reading) — this last one bearing directly on the project's own slang-mechanics purpose.
Register/regional findings: `-(이)나` as dialectal/regional-flavored, explicit gendered-interjection
flags (어머!, 세상에-class), honorific/plain lexical doublets (시장하다/배가 고프다, 생신/생일), and
archaic/literary-register song-lyric vocabulary (그리워라, 잊으리오, 온갖) distinct from the book's
ordinary prose register.

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `../../00_Reference_Extraction_Spec.md`.
