# Korean — Established Vocabulary/Grammar: Intermediate Korean, Units 1-15 (Part 1 of 2)

**Source:** Andrew Sangpil Byon, *Intermediate Korean: A Grammar and Workbook* (Routledge, 2010),
PDF pages 1-145 of 289 (front matter through Unit 15 of 24). This is the direct sequel to *Basic
Korean: A Grammar and Workbook* (same series/publisher; extracted in parallel by a sibling
subagent as `established/001-002`).

**PDF decode note — fixed font-substitution cipher, decoded.** The source PDF's embedded Korean
font (`Batang-KSCms-UHC-H-Identity-H`, a CID font with Identity-H encoding) does **not** decode
correctly through `pdftotext -layout`, `mutool`, or PyMuPDF's default text extraction — every
Hangul character comes out as an unrelated CJK Unified Ideograph (e.g. "~어/아" prints as "~㠊/㞚").
This is exactly the "fixed, decodable font-substitution cipher" gotcha flagged in
`00_Reference_Extraction_Spec.md`, not garbled OCR (no vision-reading was involved — a real text
layer exists, it's just mapped through the wrong glyph IDs). The cipher was decoded by
cross-referencing corrupted output against known Korean grammar forms: every corrupted codepoint in
the CJK range is offset by a **constant +36266 (0x8DAA)** from its correct Hangul-syllable Unicode
value. Verified against ten+ independent known words before trusting it at scale (~어/아 → 어/아,
~요 → 요, 찾다 "find" → 찾다, 다 → 다, 지만 → 지만, etc. — all matched exactly with no
exceptions found across the full 145-page range). Applied via a PyMuPDF script that shifts only
the text runs actually set in the Batang CID font (Latin-font runs — Helvetica/TimesTen glosses —
are left untouched), across all 145 pages, then spot-checked for internal consistency (conjugation
paradigms parse correctly; minimal pairs make sense). Treated as a `verified` decode, not a
`plausible_unverified` one, though technically distinct from an untouched "clean text layer."

**Known residual source-PDF defect (not a decode artifact):** three vocabulary-list entries are
missing their initial 비 syllable in the PDF's own content stream (raw glyph inspection shows the
Batang-font span genuinely omits the glyph, not that it decoded wrong) — 키다 for 비키다 "to get
out of the way" (Unit 7), 자 for 비자 "visa" (Unit 9), and a bare "rain" gloss for 비 "rain" (Units
10, 15). Corrected here from grammar-text context; flagged per affected row in the Notes column.

**Coverage note.** This chunk covers the book's front matter (title page, table of contents,
preface — no extractable vocabulary/grammar content there) and **Units 1 through 15 in full**.
Unit 15 ("Passives and causatives," printed pp. 129-136) is the last unit that fits inside PDF
pages 1-145; Unit 16 ("The noun-modifying endings") begins at PDF page 146, just outside this
chunk's range (left for a part-2 dispatch). Per the coverage rule, drill-exercise sentences that
only recombine already-captured vocabulary/grammar are skipped; each unit's own "Key vocabulary for
Unit N exercises" list — the book's own bounded, exhaustive per-unit vocabulary set — is extracted
in full rather than sampled. Grammaticalized/auxiliary verbs introduced in the grammar exposition
itself (보다, 오다/가다, 주다/드리다, 내다, 버리다, 말다, 놓다/두다, 있다, 하다, 지다as
auxiliaries) are documented in the Grammar points section rather than duplicated as vocabulary rows,
since their meaning is the grammar point itself.

**Register/honorific markers found** (flagged per the spec's "never skip register annotation"
rule): Unit 1's intimate-vs-plain speech-level social mapping (child-directed, self-talk, written
registers); Unit 2's optional ~(으)시 honorific insertion into ~지요 suggestions; Unit 5's
~어/아 드리다-vs-~어/아 주다 addressee-honorific substitution (obligatory, not stylistic, when
the favor's beneficiary outranks the speaker); Unit 9's and Unit 12's ~거든(요) / ~는/(으)ㄴ데(요)
sentence-final "graduation" from clausal conjunctive to a colloquial spoken-register
politeness/indirection device (used to leave a dispreferred continuation — a refusal, a complaint —
unstated). No dialectal/regional annotation of any kind appears in this range — Byon writes
entirely in Standard (Seoul) Korean with no B/C/S-style comparative tags — so Attested
Region/Geographic Scope are `—` throughout this file.

**Overlap with Basic Korean (established/001-002):** this is a sequel volume pitched explicitly at
second-year learners; the grammar covered here (speech levels beyond the basic polite/deferential
pair, sentence-final mood endings, comparison/exclusive particles, auxiliary-verb compounding,
the full battery of clausal conjunctives, permission/prohibition/obligation, passives/causatives)
reads as a level up from typical first-year "Basic Korean" content. No direct line-by-line
cross-check against the sibling Basic Korean files was performed (both dispatched in parallel per
this task's instructions) — noting this as a scope decision rather than a confirmed non-overlap.

---

## Vocabulary

Per the book's own structure, each unit's "Key vocabulary for Unit N exercises" list is given as
its own subsection/table (this is the book's bounded, exhaustive per-unit vocabulary set, not a
sample). Repeated core-vocabulary items recur across several units' lists in the source itself
(e.g. 가다, 먹다, 친구) — these are **not** cross-deduplicated here, since each unit's list is
independently the book's own complete exercise-vocabulary set for that unit, and collapsing repeats
would misrepresent which unit's exercises actually draw on which word.

### Unit 1 — The intimate speech level and the plain speech level (pp. 1-9)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가게 | store | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 가방 | bag | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 가르치다 | to teach | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 강의 | lecture | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 건너다 | to cross over | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 경찰관 | police officer | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 과일 | fruits | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 공부하다 | to study | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 공연 | public performance/play | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 그리다 | to draw | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 그림 | painting/picture | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 기다리다 | to wait | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 기분 | feeling/mood | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 깨끗하다 | to be clean | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 나쁘다 | to be bad | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 날씨 | weather | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 내려가다 | to go down | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 누나 | older sister | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 느낌 | feeling/mood | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 느리다 | to be slow/to be sluggish | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 다리 | bridge/legs | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 닫다 | to close/to shut | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 달다 | to be sweet | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 담배 | cigarette | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 던지다 | to throw | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 따뜻하다 | to be warm | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 따르다 | to follow | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 떠나다 | to depart/to take leave of/to leave | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 뜨겁다 | to be hot (water)/to be heated | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 로맨스 | romance | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 마시다 | to drink | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 마치다 | to finish | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 만나다 | to meet | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 머리 | head/hair (of one’s head) | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 먹다 | to eat | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 멀다 | to be far | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 문 | door | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 믿다 | to trust/to believe | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 바쁘다 | to be busy | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 받다 | to receive | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 발 | foot | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 배우다 | to learn | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 버리다 | to throw away | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 버스 | bus | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 범인 | criminal | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 보내다 | to send | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 보다 | to see/to watch/to read | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 빌리다 | to borrow | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 사과 | apple | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 사람 | person | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 사무실 | office | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 사진 | picture | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 소포 | package | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 손 | hand | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 시험 | test/examination | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 신다 | to wear (shoes/socks) | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 신문 | newspapers | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 싱싱하다 | to be fresh | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 쓰레기 | trash/garbage | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 씻다 | to wash | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 아니다 | not be | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 아래 | the base/the lower part | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 아버지 | father | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 아침 | morning | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 아프다 | to be sore/to be painful | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 양말 | socks | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 어렵다 | to be difficult | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 언제 | when | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 열다 | to open | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 열쇠 | keys | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 영화 | movie | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 외치다 | to shout | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 이번 | this time | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 일 | work/matter/errand | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 일본어 | the Japanese language | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 일찍 | early | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 읽다 | to read | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 입다 | to wear (clothes) | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 자다 | to sleep | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 자전거 | bicycle | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 잡다 | to catch/to hold | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 재미있다 | to be interesting | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 접시 | dishes/plates | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 조용하다 | to be quiet | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 좋다 | to be good/to be right/to be beneficial | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 주다 | to give | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 주말 | weekend | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 중국어 | the Chinese language | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 집 | house | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 차 | car | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 찾다 | to look for/to seek for | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 창문 | window | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 책 | book | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 친구 | friend | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 커피 | coffee | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 크게 | aloud | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 타다 | to ride | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 팔다 | to sell | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 프랑스 | France | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 피우다 | to smoke | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 하늘 | sky | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 하다 | to do | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 헤어지다 | to get scattered/to be separated/to break up | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |
| 흐리다 | to be cloudy | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 1 key vocabulary. |

### Unit 2 — Sentence-final endings ~지요, ~군요, ~네요 (pp. 11-18)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가게 | store | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 2 key vocabulary. |
| 경치 | scenery | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 2 key vocabulary. |
| 김치 | kimchi | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 2 key vocabulary. |
| 깨끗하다 | to be clean | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 2 key vocabulary. |
| 날씨 | weather | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 2 key vocabulary. |
| 닫다 | to close | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 2 key vocabulary. |
| 덥다 | to be hot (the weather) | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 2 key vocabulary. |
| 맛있다 | to be delicious | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 2 key vocabulary. |
| 먹다 | to eat | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 2 key vocabulary. |
| 물가 | prices | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 2 key vocabulary. |
| 방 | room | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 2 key vocabulary. |
| 변호사 | lawyer | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 2 key vocabulary. |
| 싸다 | to be expensive | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 2 key vocabulary. |
| 시끄럽다 | to be noisy | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 2 key vocabulary. |
| 신혼 | a new marriage | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 2 key vocabulary. |
| 아름답다 | to be beautiful | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 2 key vocabulary. |
| 어제 | yesterday | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 2 key vocabulary. |
| 없다 | not have/not exist | verb (negative existential) | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 2 key vocabulary. |
| 여행 | trip/travel | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 2 key vocabulary. |
| 오늘 | today | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 2 key vocabulary. |
| 오후 | afternoon | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 2 key vocabulary. |
| 이야기하다 | to talk | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 2 key vocabulary. |
| 일하다 | to work | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 2 key vocabulary. |
| 자다 | to sleep | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 2 key vocabulary. |
| 조용하다 | to be quiet | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 2 key vocabulary. |
| 집 | house | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 2 key vocabulary. |
| 형 | older brother | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 2 key vocabulary. |

### Unit 3 — Particles 보다, 처럼, 같이, 만큼, 마다, 마저, 조차, 밖에 (pp. 19-26)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 기다리다 | to wait | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 3 key vocabulary. |
| 낮잠 | nap | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 3 key vocabulary. |
| 마시다 | to drink | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 3 key vocabulary. |
| 만나다 | to meet | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 3 key vocabulary. |
| 먹다 | to eat | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 3 key vocabulary. |
| 분 | minute | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 3 key vocabulary. |
| 사과 | apple | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 3 key vocabulary. |
| 샐러드 | salad | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 3 key vocabulary. |
| 생각하다 | to think | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 3 key vocabulary. |
| 손님 | customer/guest | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 3 key vocabulary. |
| 시간 | hour | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 3 key vocabulary. |
| 아빠 | dad | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 3 key vocabulary. |
| 어머니 | mother | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 3 key vocabulary. |
| 어제 | yesterday | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 3 key vocabulary. |
| 언니 | older sister | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 3 key vocabulary. |
| 엄마 | mom | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 3 key vocabulary. |

### Unit 4 — Auxiliary verbs I (pp. 27-31)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가다 | to go | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 4 key vocabulary. |
| 가르치다 | to teach | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 4 key vocabulary. |
| 가정 | family | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 4 key vocabulary. |
| 감기 | a cold/flu | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 4 key vocabulary. |
| 고치다 | to fix | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 4 key vocabulary. |
| 끝나다 | to end/to finish | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 4 key vocabulary. |
| 낫다 | to get well/to recover from (illness) | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 4 key vocabulary. |
| 논문 | thesis | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 4 key vocabulary. |
| 늙다 | to grow older | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 4 key vocabulary. |
| 다 | all | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 4 key vocabulary. |
| 도자기 | ceramics | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 4 key vocabulary. |
| 만들다 | to make | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 4 key vocabulary. |
| 먹다 | to eat | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 4 key vocabulary. |
| 물 | water | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 4 key vocabulary. |
| 바꾸다 | to change | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 4 key vocabulary. |
| 병원 | hospital | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 4 key vocabulary. |
| 산 | mountain | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 4 key vocabulary. |
| 살다 | to live | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 4 key vocabulary. |
| 쓰다 | to use/to write | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 4 key vocabulary. |
| 여자 | woman | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 4 key vocabulary. |
| 영어 | English | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 4 key vocabulary. |
| 올라가다 | to climb/to go up | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 4 key vocabulary. |
| 음식 | food | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 4 key vocabulary. |
| 이제 | now | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 4 key vocabulary. |
| 인도 | India | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 4 key vocabulary. |
| 입다 | to wear | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 4 key vocabulary. |
| 전화하다 | to make a phone call | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 4 key vocabulary. |
| 절약하다 | to economize on/to save/to be thrifty | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 4 key vocabulary. |
| 조금씩 | little by little | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 4 key vocabulary. |
| 친구 | friends | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 4 key vocabulary. |
| 한복 | traditional Korean clothes | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 4 key vocabulary. |
| 해 | a year/the sun | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 4 key vocabulary. |
| 행복하다 | to be happy | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 4 key vocabulary. |
| 헤어지다 | to break up | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 4 key vocabulary. |
| 혼자 | alone | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 4 key vocabulary. |

### Unit 5 — Auxiliary verbs II (pp. 33-41)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가게 | store | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 가다 | to go | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 고기 | meat | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 고장이 나다 | to get out of order | phrase (noun + particle + verb) | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. phrase: noun 고장 "malfunction" + subject particle 이 + verb 나다 "occur/arise." |
| 구별하다 | to distinguish | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 굽다 | to roast | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 그리다 | to paint/to draw | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 그림 | painting/picture | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 금 | gold | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 길 | road/street | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 나오다 | to come out | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 남자 | man | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 노래 | song | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 닫다 | to close | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 또 | again | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 만들다 | to make | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 문 | door | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 미끄러지다 | to slide/to glide | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 바꾸다 | to change | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 받다 | to receive | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 부르다 | to sing/to call out | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 밀 | secret | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 시키다 | to order/to force (a person to do) | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 싸우다 | to fight/to dispute (with) | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 쓰다 | to write/to use | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 언니 | older sister | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 열다 | to open | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 옷 | clothes | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 은 | silver | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 읽다 | to read | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 전등 | electric lamp | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 전화기 | telephone | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 점심 | lunch | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 지우다 | to erase | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 차 | car | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 창문 | window | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 책 | book | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 친구 | friend | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 캐다 | to dig into/to unearth | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 켜다 | to light/to switch on | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 파일 | file | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 팔다 | to sell | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 편지 | letter | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 학교 | school | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 헤어지다 | to break up | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 형 | older brother | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |
| 화내다 | to get angry | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 5 key vocabulary. |

### Unit 6 — Auxiliary verbs III (pp. 42-50)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 값 | price/value | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 6 key vocabulary. |
| 고맙다 | to be thankful | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 6 key vocabulary. |
| 궁금하다 | to be curious | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 6 key vocabulary. |
| 기억하다 | to remember/to memorize | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 6 key vocabulary. |
| 까맣다 | to be black | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 6 key vocabulary. |
| 꺼지다 | to be extinguished/to die out | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 6 key vocabulary. |
| 꽃 | flowers | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 6 key vocabulary. |
| 날씨 | weather | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 6 key vocabulary. |
| 눕다 | to lie down | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 6 key vocabulary. |
| 덥다 | to be hot (the weather) | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 6 key vocabulary. |
| 맑다 | to be clear | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 6 key vocabulary. |
| 번호 | number | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 6 key vocabulary. |
| 부럽다 | to be envious | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 6 key vocabulary. |
| 싸다 | to be expensive | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 6 key vocabulary. |
| 신문 | newspapers | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 6 key vocabulary. |
| 씻다 | to wash | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 6 key vocabulary. |
| 아프다 | to be sick | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 6 key vocabulary. |
| 야채 | vegetables | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 6 key vocabulary. |
| 얼굴 | face | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 6 key vocabulary. |
| 예쁘다 | to be pretty | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 6 key vocabulary. |
| 예약하다 | to reserve | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 6 key vocabulary. |
| 오다 | to come | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 6 key vocabulary. |
| 음식 | food | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 6 key vocabulary. |
| 익히다 | to make oneself familiar with | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 6 key vocabulary. |
| 읽다 | to read | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 6 key vocabulary. |
| 좌석 | seat | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 6 key vocabulary. |
| 전등 | electric lamp | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 6 key vocabulary. |
| 전화 | telephone | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 6 key vocabulary. |
| 정원 | garden | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 6 key vocabulary. |
| 지리 | geographical features | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 6 key vocabulary. |
| 집 | house | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 6 key vocabulary. |
| 친구 | friend | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 6 key vocabulary. |
| 침대 | bed | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 6 key vocabulary. |
| 크다 | to be big | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 6 key vocabulary. |
| 키 | height | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 6 key vocabulary. |
| 피다 | to bloom | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 6 key vocabulary. |
| 환자 | patient | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 6 key vocabulary. |

### Unit 7 — Clausal conjunctives — purpose or intention (pp. 51-59)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가다 | to go | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 가족 | family | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 같이 | together | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 고르다 | to select | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 공부하다 | to study | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 공항 | airport | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 기다리다 | to wait | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 기차 | train | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 길 | road/street | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 남자 | man | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 남편 | husband | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 도서관 | library | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 돈 | money | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 떠나다 | to leave/to depart | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 마시다 | to drink | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 만나다 | to meet | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 맞추다 | to set/to put together | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 먹다 | to eat | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 벌다 | to earn | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 비키다 | to get out of the way | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. NOTE: source PDF's own content stream drops the initial 비 glyph for this entry (confirmed via raw glyph inspection, not a decode-cipher or vision-reading artifact); word supplied from grammar-text context. |
| 빌리다 | to borrow | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 빨리 | fast/immediately | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 사다 | to buy | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 생일 | birthday | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 선물 | present/gift | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 시험에 붙다 | to pass a test | phrase (noun + particle + verb) | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. phrase: noun 시험 "test" + locative/dative particle 에 + verb 붙다 "stick/pass." |
| 식당 | restaurant | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 싸게 | at a cheap price | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 씻다 | to wash | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 아르바이트 | a side job | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 아침 | morning/breakfast | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 알람 | alarm (clock) | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 앰블란스 | ambulance | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 야채 | vegetables | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 얼굴 | face | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 여자 | woman | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 역 | station | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 열심히 | eagerly/enthusiastically/hard | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 웃다 | to smile | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 인상 | impression | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 일어나다 | to get up | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 일찍 | early | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 잘 | well/excellently | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 점심 | lunch | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 주다 | to give | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 중국 | China | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 지나가다 | to pass by | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 차 | car | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 책 | book | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 친구 | friend | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 타다 | to ride | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 학교 | school | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 혼내다 | to teach a lesson/to frighten (a person) out of his wits/to scare | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 화장실 | toilet | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |
| 흥정 | buying and selling/making a deal (with) | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 7 key vocabulary. |

### Unit 8 — Clausal conjunctives — reasons and cause (pp. 61-67)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가다 | to go | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 감기 걸리다 | to catch (a cold) | phrase (noun + particle + verb) | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. phrase: noun 감기 "a cold" + verb 걸리다 "to catch/be caught (by an ailment)" — no overt particle in this idiom. |
| 곧 | soon | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 기다리다 | to wait | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 나가다 | to go out | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 내일 | tomorrow | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 넣다 | to insert/to put (something) in | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 놀다 | to play/to enjoy (oneself) | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 눈 | snow/eyes | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 늦다 | to be late | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 다이어트 | diet | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 더 | more | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 덥다 | to be hot/to be warm | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 도서관 | library | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 도착하다 | to arrive | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 돕다 | to help | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 듣다 | to listen | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 뜨겁다 | to be hot/to be heated | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 라디오 | radio | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 마시다 | to drink | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 많이 | a lot/plenty | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 맛있다 | to be delicious | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 머리 | head | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 먹다 | to eat | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 모래 | the day after tomorrow | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 물어보다 | to ask (a person about something) | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 지컬 | musical | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 미안하다 | to be sorry | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 바쁘다 | to be busy | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 밖 | outside | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 밤 | night | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 보다 | to see/to watch/to read | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 사다 | to buy | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 사람들 | people | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 새우다 | to stay up all night | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 생일 | birthday | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 선물 | present/gift | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 소금 | salt | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 소리 | sound | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 숙제 | homework | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 시간 | hour/time | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 식당 | restaurant | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 싱겁다 | to be watery/to be insipid | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 아침 | morning/breakfast | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 아프다 | to be painful/to be sore | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 약 | medicine | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 약속 | appointment | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 어제 | yesterday | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 에어콘 | air conditioner | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 여기 | here | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 오다 | to come | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 오전 | a.m. | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 요리하다 | to cook | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 운동하다 | to do (physical) exercise/sports | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 은행 | bank | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 음식 | food | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 음악 | music | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 이사 | moving (housing) | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 이야기하다 | to talk | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 이제 | now | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 일어나다 | to get up | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 일찍 | early | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 자주 | often | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 재미있게 | interestingly | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 저녁 | dinner/evening | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 전화 | telephone | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 조금 | little | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 좋다 | to be good | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 주다 | to give | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 집 | house | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 찾다 | to look for/to seek for | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 천천히 | slowly | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 초인종 | doorbell | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 친구 | friend | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 크게 | greatly/loudly | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 틀다 | to switch on | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 파티 | party | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 포장하다 | to pack/to wrap | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 학교 | school | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |
| 흥겹게 | merrily/pleasantly | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 8 key vocabulary. |

### Unit 9 — Clausal conjunctives — conditions (pp. 72-83)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가다 | to go | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 가깝다 | to be near | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 가르치다 | to teach | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 건강 | health | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 걱정거리 | source of anxiety | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 공 | ball | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 끊다 | to quit | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 끓이다 | to boil | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 남자 | man | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 남편 | husband | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 날씨 | weather | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 내다 | to pay | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 내일 | tomorrow | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 냄비 | pot | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 너무 | too (much) | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 노래 | song | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 노트북 | notebook | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 놀다 | to play | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 누구 | who | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 늦게 | late | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 다음 | next | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 담배 | cigarette | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 대학 | college | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 덥다 | to be hot (the weather) | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 도움 | help | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 드시다 | to eat | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 들어가다 | to enter | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 따뜻하다 | to be warm/to be mild | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 룸메이트 | roommate | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 말하다 | to speak | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 만나다 | to meet | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 많이 | a lot | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 머리 | head/hair (of one’s head) | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 먹다 | to eat | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 모르다 | do not know | verb (negative existential) | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 모자라다 | to be short of | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 목 | throat | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 묻다 | to ask | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 물 | water | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 미국 | U.S.A. | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 바꾸다 | to change | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 바쁘다 | to be busy | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 받다 | to receive | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 배 | stomach | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 배우다 | to learn | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 법대 | law school | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 병원 | hospital | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 보다 | to see/to watch/to read | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 비자 | visa | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. NOTE: source PDF's own content stream drops the initial 비 glyph for this entry (confirmed via raw glyph inspection, not a decode-cipher or vision-reading artifact); word supplied from grammar-text context. |
| 사다 | to buy | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 사람 | person/people | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 사용하다 | to use | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 사이즈 | size | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 살다 | to live | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 생일 | birthday | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 선물 | present/gift | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 소파 | sofas | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 시험을 보다 | to take tests/exams | phrase (noun + particle + verb) | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. phrase: noun 시험 "test" + object particle 을 + verb 보다 "see" — idiomatic "take a test." |
| 식당 | restaurant | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 식사 | meal | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 심심하다 | to be bored | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 쓰다 | to use | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 아르바이트 | a side job | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 아프다 | to be sore | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 어제 | yesterday | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 약 | medicine | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 여행 | trip/travel | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 연락하다 | to contact | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 열다 | to open | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 예약하다 | to make a reservation | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 오다 | to come | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 요금 | fee | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 유학가다 | to go abroad for study | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 입국하다 | to enter a country | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 일찍 | early | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 자다 | to sleep | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 작다 | to be small | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 잘 | well/expertly | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 저금 | saving | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 저녁 | dinner/evening | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 전화 | telephone | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 제출하다 | to submit | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 조금 | little | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 조심하다 | to be careful/to take care of | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 졸업장 | diploma | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 주일 | week (day) | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 지하철 | subway | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 직장 | one’s place of work | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 집 | house | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 창문 | window | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 책 | book | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 추천서 | recommendation letter | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 춥다 | to be cold | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 취직 | getting employment | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 치다 | to play/to strike | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 친구 | friend | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 켜다 | to switch on | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 타다 | to ride | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 피곤하다 | to be tired | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 필요하다 | to be in need of | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 학기 | semester | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 한국 | Korea | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 화장실 | toilet | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 회사 | company | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |
| 히터 | heater | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 9 key vocabulary. |

### Unit 10 — Clausal conjunctives — listing and choice (pp. 85-91)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가다 | to go | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 갈아입다 | to change (clothes) | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 길다 | to be long | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 꽃 | flowers | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 날씬하다 | to be slim | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 날씨 | weather | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 내다 | to pay out | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 돼지고기 | pork | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 땀 | sweat | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 마시다 | to drink | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 만들다 | to make | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 맛없다 | to be tasteless | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 머리 | head/hair (of the head) | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 먹다 | to eat | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 바닷가 | beach | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 방 | room | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 보다 | to see/to watch/to read | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 보통 | usually | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 비 | rain | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. NOTE: source PDF's own content stream drops the initial 비 glyph for this entry (confirmed via raw glyph inspection, not a decode-cipher or vision-reading artifact); word supplied from grammar-text context. |
| 사다 | to buy | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 산 | mountain | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 살 | age | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 성격 | personality | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 세수 | face washing | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 소고기 | beef | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 소리 | sound/noise | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 숙제 | homework | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 시원하다 | to be cool/to be refreshing | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 신문 | newspapers | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 싸다 | to be cheap | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 쓰다 | to use | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 아침 | morning/breakfast | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 언제 | when | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 얼굴 | face | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 영화 | movie | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 예쁘다 | to be pretty | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 옷 | clothes | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 외식 | dining out | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 울다 | to cry | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 의사 | doctor | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 인터넷 | internet | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 읽다 | to read | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 작다 | to be small | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 저녁 | dinner/evening | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 좋다 | to be good | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 지르다 | to cry out | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 지불하다 | to pay | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 착하다 | to be good/to be kindhearted | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 춥다 | to be cold | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 치다 | to play/to strike | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 친절하다 | to be kind | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 크다 | to be big | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 키 | height | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 현금 | cash | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 흐리다 | to be cloudy | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |
| 흘리다 | to spill/to drop | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 10 key vocabulary. |

### Unit 11 — Clausal conjunctives — time (pp. 95-101)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가다 | to go | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 거지 | beggar | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 걷다 | to walk | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 계단 | stairs | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 계속 | continually | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 골다 | to snore | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 길 | road | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 깨다 | to break/to smash | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 넘어지다 | to fall (down over) | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 노래 | song | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 놀다 | to play/to amuse | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 대학 | college | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 돈 | money | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 되다 | to become/to get to/to elapse | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 떨어지다 | to fall/to drop | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 많이 | a lot | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 먹다 | to eat | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 멈추다 | to stop | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 무언가 | something | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 바꾸다 | to change | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 배탈나다 | to have a stomachache | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 보다 | to see/to watch/to read | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 사다 | to buy | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 살찌다 | to gain weight | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 세수 | face washing | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 시키다 | to order | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 시험 | test/exam | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 신문 | newspapers | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 쓰다 | to use | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 양치질 | brushing teeth | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 열심히 | hard/earnestly/enthusiastically | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 영화 | movie | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 오른쪽 | right side | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 올라가다 | to climb/to go up | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 요리 | cooking | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 울다 | to cry | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 웃다 | to smile | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 이사 (house) moving |  | phrase (noun + particle + verb) | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 이야기하다 | to talk | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 일하다 | to work | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 일어나다 | to get up | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 읽다 | to read | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 자다 | to sleep | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 전에 | before | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 점심 | lunch | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 접시 | dish | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 졸다 | to doze off | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 졸업하다 | to graduate | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 주소 | address | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 중얼거리다 | to mutter/to murmur | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 쫓겨나다 | to be expelled | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 차 | car | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 찾다 | to look for/to seek for | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 책 | book | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 혼자 | alone | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |
| 회사 | company/firm | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 11 key vocabulary. |

### Unit 12 — Clausal conjunctives — background (pp. 105-110)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가다 | to go | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 12 key vocabulary. |
| 가방 | bag/suitcase | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 12 key vocabulary. |
| 같이 | together | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 12 key vocabulary. |
| 금방 | just now/at once | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 12 key vocabulary. |
| 기다리다 | to wait | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 12 key vocabulary. |
| 기타 | guitar | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 12 key vocabulary. |
| 끓이다 | to boil | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 12 key vocabulary. |
| 내일 | tomorrow | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 12 key vocabulary. |
| 너무 | too much | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 12 key vocabulary. |
| 다음 | next | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 12 key vocabulary. |
| 도착하다 | to arrive | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 12 key vocabulary. |
| 돕다 | to help | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 12 key vocabulary. |
| 마시다 | to drink | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 12 key vocabulary. |
| 많다 | to be many/to be much | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 12 key vocabulary. |
| 머리 | head/hair (of one’s head) | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 12 key vocabulary. |
| 먹다 | to eat | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 12 key vocabulary. |
| 목마르다 | to be thirsty | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 12 key vocabulary. |
| 무겁다 | to be heavy | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 12 key vocabulary. |
| 무척 | very much/extremely | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 12 key vocabulary. |
| 물 | water | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 12 key vocabulary. |
| 미국 | U.S.A. | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 12 key vocabulary. |
| 미안하다 | to be sorry | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 12 key vocabulary. |
| 바쁘다 | to be busy | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 12 key vocabulary. |
| 방 | room | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 12 key vocabulary. |
| 배우다 | to learn | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 12 key vocabulary. |
| 백화점 | department store | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 12 key vocabulary. |
| 부엌 | kitchen | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 12 key vocabulary. |
| 부치다 | to send/to mail | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 12 key vocabulary. |
| 싸다 | to be expensive | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 12 key vocabulary. |
| 빌리다 | to borrow | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 12 key vocabulary. |
| 사다 | to buy | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 12 key vocabulary. |
| 사람 | person/people | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 12 key vocabulary. |
| 소리 | sound/noise | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 12 key vocabulary. |
| 소포 | parcel/package | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 12 key vocabulary. |
| 수리하다 | to fix/to repair | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 12 key vocabulary. |
| 시끄럽다 | to be noisy | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 12 key vocabulary. |
| 아프다 | to be sore | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 12 key vocabulary. |
| 약 | medicine | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 12 key vocabulary. |
| 없다 | do not have/do not exist | verb (negative existential) | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 12 key vocabulary. |

### Unit 13 — Clausal conjunctives — although (pp. 113-118)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가깝다 | to be near | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 13 key vocabulary. |
| 가다 | to go | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 13 key vocabulary. |
| 걱정되다 | to be anxious/to feel uneasy | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 13 key vocabulary. |
| 게으르다 | to be lazy | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 13 key vocabulary. |
| 고기 | meat | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 13 key vocabulary. |
| 귀엽다 | to be cute | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 13 key vocabulary. |
| 길다 | to be long | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 13 key vocabulary. |
| 나쁘다 | to be bad/to be wrong | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 13 key vocabulary. |
| 내성적 | introvert | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 13 key vocabulary. |
| 다리 | legs/bridge | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 13 key vocabulary. |
| 등록금 | tuition | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 13 key vocabulary. |
| 똑똑하다 | to be smart | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 13 key vocabulary. |
| 뚱뚱하다 | to be chubby | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 13 key vocabulary. |
| 맛있다 | to be delicious | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 13 key vocabulary. |
| 맵다 | to be spicy | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 13 key vocabulary. |
| 먹다 | to eat | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 13 key vocabulary. |
| 멀다 | to be far | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 13 key vocabulary. |
| 미국 | U.S.A. | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 13 key vocabulary. |
| 보내다 | to send | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 13 key vocabulary. |
| 백화점 | department store | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 13 key vocabulary. |
| 싸다 | to be expensive | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 13 key vocabulary. |
| 사다 | to buy | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 13 key vocabulary. |
| 싸다 | to be cheap | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 13 key vocabulary. |
| 어렵다 | to be difficult | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 13 key vocabulary. |
| 어리다 | to be young/to be juvenile/to be immature | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 13 key vocabulary. |
| 역 | station | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 13 key vocabulary. |
| 영문학 | English literature | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 13 key vocabulary. |
| 영어 | English | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 13 key vocabulary. |
| 오다 | to come | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 13 key vocabulary. |
| 옷 | clothes | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 13 key vocabulary. |
| 유학 | studying abroad | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 13 key vocabulary. |
| 음식 | food | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 13 key vocabulary. |
| 자주 | often | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 13 key vocabulary. |
| 작다 | to be small | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 13 key vocabulary. |
| 잘 | well | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 13 key vocabulary. |
| 재미있다 | to be interesting | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 13 key vocabulary. |
| 전공하다 | to major in | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 13 key vocabulary. |
| 좋아하다 | to like | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 13 key vocabulary. |
| 지하철 | subway | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 13 key vocabulary. |
| 초대장 | invitation | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 13 key vocabulary. |
| 키가 크다 | to be tall | phrase (noun + particle + verb) | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 13 key vocabulary. phrase: noun 키 "height" + subject particle 가 + adjective 크다 "big" — idiomatic "be tall." |
| 편하다 | to be convenient | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 13 key vocabulary. |
| 한국어 | the Korean language | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 13 key vocabulary. |
| 활발하다 | to be active | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 13 key vocabulary. |

### Unit 14 — Permission, prohibition, and obligation (pp. 120-128)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가게 | store | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 가격 | price | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 가방 | bag | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 고등학생 | high-school student | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 공부 | study | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 국 | soup | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 길 | road/street | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 날씨 | weather | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 내다 | to pay | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 내일 | tomorrow | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 눈 | snow/eyes | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 닫다 | to close | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 도서관 | library | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 따다 | to obtain | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 뜨다 | to open (one’s eyes) | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 먹다 | to eat | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 반찬 | side dishes | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 방 | room | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 손 | hands | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 시작하다 | to begin | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 시험 | test/examination/experiment | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 싱겁다 | to be watery | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 싸다 | to pack/to be cheap | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 쓰다 | to use | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 씻다 | to wash | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 아직 | yet/even now | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 아침 | morning/breakfast | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 얼굴 | face | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 여행 | traveling | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 영화 | movie | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 운전면허 | driving license | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 위험하다 | to be dangerous | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 이제 | now/this time | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 일 | work/matter/affair | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 일어나다 | to get up | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 일찍 | early | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 작다 | to be small | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 잡다 | to hold/to capture | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 재미없다 | to be uninteresting/to be dull | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 전기세 | electricity usage bill | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 점심 | lunch | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 좁다 | to be narrow/to be small | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 좋다 | to be good | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 집 | house | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 짜다 | to be salty | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 청소 | cleaning | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 타다 | to ride | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |
| 퇴근하다 | to leave one’s office/to go home | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 14 key vocabulary. |

### Unit 15 — Passives and causatives (pp. 129-136)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 고양이 | cat | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 15 key vocabulary. |
| 곰 | bear | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 15 key vocabulary. |
| 길다 | to be long | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 15 key vocabulary. |
| 껌 | chewing gum | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 15 key vocabulary. |
| 누나 | older sister | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 15 key vocabulary. |
| 다행히 | fortunately | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 15 key vocabulary. |
| 더 | more | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 15 key vocabulary. |
| 덥다 | to be hot | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 15 key vocabulary. |
| 뒤 | back | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 15 key vocabulary. |
| 마시다 | to drink | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 15 key vocabulary. |
| 맛있다 | to be delicious | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 15 key vocabulary. |
| 매일 | everyday | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 15 key vocabulary. |
| 먹다 | to eat | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 15 key vocabulary. |
| 먼저 | first | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 15 key vocabulary. |
| 모기 | mosquito | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 15 key vocabulary. |
| 물고기 | fish | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 15 key vocabulary. |
| 발표 | presentation | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 15 key vocabulary. |
| 밥 | meal | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 15 key vocabulary. |
| 보통 | usually | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 15 key vocabulary. |
| 비 | rain | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 15 key vocabulary. NOTE: source PDF's own content stream drops the initial 비 glyph for this entry (confirmed via raw glyph inspection, not a decode-cipher or vision-reading artifact); word supplied from grammar-text context. |
| 빨래 | laundry | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 15 key vocabulary. |
| 빨래줄 | clothes-line | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 15 key vocabulary. |
| 서재 | a study/library | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 15 key vocabulary. |
| 스웨터 | sweater | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 15 key vocabulary. |
| 시험 | test/exam | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 15 key vocabulary. |
| 싸다 | to be cheap | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 15 key vocabulary. |
| 씹다 | to chew | verb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 15 key vocabulary. |
| 아이 | child | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 15 key vocabulary. |
| 안개 | fog | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 15 key vocabulary. |
| 앞줄 | front row | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 15 key vocabulary. |
| 오늘 | today | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 15 key vocabulary. |
| 자주 | often | adverb | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 15 key vocabulary. |
| 재킷 | jacket | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 15 key vocabulary. |
| 저녁 | evening/dinner | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 15 key vocabulary. |
| 전기 | electricity | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 15 key vocabulary. |
| 전화 | telephone | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 15 key vocabulary. |
| 책 | book | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 15 key vocabulary. |
| 청바지 | jeans | noun | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 15 key vocabulary. |
| 춥다 | to be cold | adjective | core | — | contemporary (source published 2010) | — | — | grammar_reference | n/a | n/a | Unit 15 key vocabulary. |
## Grammar points

### Unit 1 — The intimate speech level and the plain speech level

Korean has multiple speech levels marked by sentence-final endings; this unit covers two.

- **Intimate speech level (~어/아).** Derived from the polite level (~어요/아요) by simply
  dropping 요. Two allomorphs: ~아 after a stem ending in a bright vowel 오/아 (찾다 → 찾아), ~어
  after any other vowel (배우다 → 배워). The copula 이다/아니다 is irregular: ~이야/아니야 rather
  than the expected ~이에/아니에. One ending covers all four sentence types (declarative,
  interrogative, imperative, propositive) — disambiguated only by intonation/context, exactly like
  the polite level's ~어요/아요.
- **Plain speech level.** Blunter/more direct register, used with children, childhood friends,
  younger siblings, self-talk, or in writing (essays, news, diaries, academic prose). Unlike the
  intimate/polite levels, the plain level has a **different ending per sentence type**:
  - Declarative: ~는/ㄴ다 (verbs: 가다→간다) / ~다 (adjectives, copula, unchanged: 춥다→춥다) /
    ~었/았다 (past, all predicates).
  - Interrogative: ~니/(으)냐? for all predicates (좋다→좋니?/좋냐?; the (으)냐 form is also used
    in writing, e.g. 좋으냐?); ~었/았니/(으)냐? in the past.
  - Imperative (verbs only): ~아라 (after 오/아-final stems) / ~어라 (elsewhere); not conjugated
    for tense.
  - Propositive (verbs only): ~자; not conjugated for tense.

  This four-way split (one ending per sentence type, rather than one ending for all types as in the
  intimate/polite levels) is the unit's key structural point about the plain level.

**Register note:** this unit is the clearest register-marking content in the whole chunk — it
explicitly maps social contexts (child-directed, self-talk, written registers) onto grammatical
endings, which is directly relevant to slang-register mechanics (informal/intimate registers as a
possible substrate for slang formation).

### Unit 2 — Sentence-final endings ~지요, ~군요, ~네요

- **~지요** (one-form ending) marks one of four speaker stances depending on intonation/context:
  (i) seeking agreement (rising intonation: "..., right?"), (ii) asking a question the speaker
  believes the hearer can answer, (iii) assuring/asserting information (falling intonation), (iv)
  making a suggestion (falling intonation, "how about ..."). The honorific suffix ~(으)시 can
  optionally combine with ~지요 to soften a suggestion politely (가시지요 "shall we go?").
- **~네요** marks the speaker's spontaneous, unanticipated realization/surprise; declarative only.
  ~겠네요 (with the conjectural pre-final ending 겠) projects that realization onto a future event
  ("I guess ... will/may ..."); ~었/았겠네요 projects it onto a presumed past event ("must have
  ...").
- **~군요** is an exclamatory ending for immediate realization, similar to ~네요 but *without* the
  ~네요 implication that the realized fact is contrary to expectation — just a straightforward "oh,
  I see." Used directly after adjective/copula stems, but after verb stems it requires the
  noun-modifying ending ~는 first (~는군요). Past ~었/았군요; future/conjectural ~겠군요.

### Unit 3 — Particles 보다, 처럼/같이, 만큼, 마다, 마저/조차, 밖에

- **보다** "more than/rather than" marks the standard of comparison; often reinforced by 더
  "more," 덜 "less," 훨씬 "by far."
- **처럼** and **같이** both mean "like/as" (comparison to a standard), near-synonymous.
- **만큼** "as much as/to the extent that" (equative comparison).
- **마다** "every/each."
- **마저** and **조차** both mean "even," but — unlike the neutral 까지 "even" — they carry a
  built-in implication that the included item is unfavorable/unwanted (존의 여자친구까지 만났어요
  "even met John's girlfriend" [neutral] vs. …마저 만났어요 [implies meeting her was undesirable]).
- **밖에** "only/nothing but" is functionally similar to 만 "only" but obligatorily co-occurs with a
  negative predicate (15달러밖에 없어요 lit. "have nothing but 15 dollars," not *있어요).

### Unit 4 — Auxiliary verbs I (structure + 보다/오다/가다)

Korean auxiliary verbs are themselves ordinary verbs that shift meaning when compounded onto a
main predicate via [main verb stem + ~어/아 (or ~고 for a limited set) + auxiliary verb]; ~아 after
아/오-final stems, ~어 elsewhere. Auxiliaries always follow the main verb and carry all tense/mood/
honorific marking themselves.

- **~어/아 보다** "try (doing)/experience" — attempting an action once to see the result (배워
  봅니다 "try learning").
- **~어/아 오다** — continuous action progressing *toward the present* (지금까지 잘 살아 왔어요
  "have lived well until now").
- **~어/아 가다** — continuous action progressing *toward the future* (드라마가 끝나 가요 "the
  drama is coming to an end").

The full auxiliary-verb inventory table given (보다→try, 오다/가다→continue, 주다→favor, 내다→do
completely, 나다→have finished, 버리다→finish up/regret, 놓다→for later, 하다→"be in the state of"
[~어/아하다], 지다→become [~어/아지다], 말다→end up doing [~고 말다]) previews Units 5-6.

### Unit 5 — Auxiliary verbs II (내다, 버리다, 말다, 주다/드리다)

- **~어/아 내다** "do all the way to the very end" — completing a difficult/troublesome task
  despite the difficulty (하루만에 책을 읽어 냈어요 "read the book through, within a day, despite
  the difficulty").
- **~어/아 버리다** "do completely/end up doing" — completeness with an added emotional coloring
  of either **regret** (지갑을 잃어 버렸어요 "lost my wallet [and I regret it]") or **relief**
  (숙제를 끝내 버렸어요 "finished my homework [and I'm relieved]"), read from context; unlike
  ~어/아 내다 it doesn't presuppose the action was inherently difficult.
- **~고 말다** "end up (doing)" — the completed action runs *against* the subject's own will/
  intention (차 사고로 죽고 말았어요 "ended up dying in the car accident").
- **~어/아 주다** "do (something) as a favor for someone" — 위해서 "on behalf of" can optionally
  make the beneficiary explicit.
- **Honorific register point (~어/아 드리다 vs. ~어/아 주다):** when the beneficiary of the favor
  outranks the speaker in age/status, ~어/아 드리다 (드리다 = humble/honorific form of 주다) is
  required instead of ~어/아 주다 — 할머니께 시계를 사 드렸어요 (grandmother, correct) vs. the
  starred/ungrammatical *…사 줬어요. This is a genuine addressee-honorific substitution, distinct
  from a simple stylistic register choice — using the plain form for an esteemed beneficiary is
  marked as flatly wrong (X), not just less polite.
- **~어/아 주세요** (favor + honorific imperative 주세요) is the standard polite-request pattern,
  more polite than a bare imperative.

### Unit 6 — Auxiliary verbs III (놓다/두다, 있다, ~어/아하다, ~어/아지다)

- **~어/아 놓다** (interchangeable with **~어/아 두다**) has two related senses: (i) the state
  resulting from a completed action *persists* (전등을 켜 놓았어요 "turned the lamp on and it's
  still on"); (ii) doing something now *for later use* (물을 마셔 놓았어요 "drank water
  beforehand, for later").
- **~어/아 있다** marks a persisting *resultant state* from an (often intransitive) verb, contrasted
  three ways with the plain verb and the ~고 있다 progressive: 앉아요 (sits) / 앉고 있어요 (is
  [in the act of] sitting down) / 앉아 있어요 (is seated, i.e. in the resulting state). Exception:
  a closed set of "wearing" verbs (입다, 쓰다, 끼다, 매다) use ~고 있다, not ~어/아 있다, for the
  resultant "is wearing" sense (양말을 신고 있어요, not *신어 있어요).
- **~어/아하다** — a grammatical requirement, not a stylistic option: Korean emotive/sensory
  adjectives (슬프다 "sad," 좋다 "like," 무섭다 "scared," etc.) can only describe the speaker's own
  first-hand feeling; describing a **third person's** feeling requires converting the adjective
  into a verb with ~어/아하다 (리사가 슬퍼요 is ungrammatical; 리사가 슬퍼해요 "Lisa grieves" is
  required). Past tense is the one exception — a bare adjective in the past tense (리사가
  슬펐어요) is acceptable for a third person, alongside 슬퍼했어요, since the speaker could have
  learned the fact after the feeling ended. No space is written between the adjective and 하다
  (슬퍼하다, not *슬퍼 하다) — an orthographic convention specific to this compound.
- **~어/아지다** converts an adjective into an intransitive "become ~" verb, expressing gradual
  change (춥다 "cold" → 추워지다 "becomes cold"); also written without an internal space.

### Unit 7 — Clausal conjunctives: general properties + purpose/intention (~(으)러, ~(으)려고, ~도록)

General framework: clausal conjunctives attach to a non-final predicate stem to link two clauses,
and (unlike sentence-final endings) never end a sentence themselves. Individual conjunctives vary
along four independent restriction axes that recur through Units 7-13: (1) **tense agreement** —
whether the conjunctive itself can carry a tense marker, or only the main clause can; (2) **subject
agreement** — whether both clauses must share a subject; (3) **predicate-type restriction** —
verb-only vs. verb/adjective/copula-all; (4) **sentence-type restriction** — usable with all four
sentence types, or only some.

- **~(으)러** "in order to/to" — used with motion verbs (가다/오다) to state the purpose of going/
  coming (편지를 부치러 우체국에 가요). Restrictions: same-subject required; not tense-conjugated;
  verb-only; no sentence-type restriction.
- **~(으)려고** "intending to" — like ~(으)러 but usable with *any* verb, not just motion verbs.
  Restrictions: not tense-conjugated; same-subject; verb-only; declarative/interrogative only (not
  imperative/propositive).
- **~도록** "so that/to the point where" — the least restricted of the three: only restriction is
  that it's not tense-conjugated; any sentence type, any predicate type, subjects need not match.

### Unit 8 — Clausal conjunctives: reasons and cause (~어/아서, ~(으)니까, ~느라고)

- **~어/아서** has two functions: (i) cause-and-effect ("so/because"), and (ii) purely sequential
  linking with no causal claim ("and then"). As a causal connector it cannot be used for imperative/
  propositive sentences; as a sequential connector it has no such restriction. Two-form (아서/어서);
  the copula has two further sub-variants, 이어서/(이)라서 (and negative 아니어서/아니라서), with
  (이)라서 more common in speech. Not conjugated for tense (only the main clause carries tense).
- **~(으)니까** "since/so/because" — similar meaning to ~어/아서 but (i) the reason feels more
  specific/direct, (ii) it *can* be used for any sentence type including imperative/propositive
  (unlike causal ~어/아서), and (iii) it *is* conjugated for tense (unlike ~어/아서).
- **~느라고** "as a result of/because of" — like ~어/아서 and ~(으)니까 but with a built-in negative
  implication: the main clause's action is an *undesirable consequence* of the first clause's action
  (밤새 컴퓨터 게임을 하느라고 학교에 못 갔어요. "couldn't go to school because of gaming all
  night"). Most restricted of the three: verb-only, same-subject, not tense-conjugated, no
  imperative/propositive.

### Unit 9 — Clausal conjunctives: conditions (~(으)면, ~(으)려면, ~(으)ㄹ수록, ~어/아야, ~거든)

- **~(으)면** "if/when" — essentially unrestricted (any tense, predicate type, subject, sentence
  type). Copula sub-forms ~(이)면/(이)라면. After a time word it means "in/at the end of" (한
  학기면 졸업해요 "graduate in one semester"). **~(으)면 하다/좋겠다** "wish/hope" combines it with
  하다 or 좋겠다; adding past tense 었/았 (~았으면 하다/좋겠다) intensifies the wish into a more
  assertive/emphatic register.
- **~(으)려면** "if one intends to" = ~(으)려고 (intending to) + ~(으)면 (if).
- **~(으)ㄹ수록** "the more ... the more" — can optionally co-occur with ~(으)면 for emphasis
  (치면 칠수록 "the more [you] play [it]").
- **~어/아야** "only if" — marks a necessary/prerequisite condition; can be intensified with the
  particle 만 (~어/아야만) for emphasis. Copula sub-forms 이어야/이라야.
- **~거든** "if" — restricted to imperative/propositive main clauses only. **Register note:** in
  spoken Korean, ~거든(요) is also very commonly used as a **sentence-final ending** (not just a
  conjunctive), giving an emphatic "you know/you see (because)" explanatory tag at the end of an
  utterance that answers an implicit "why" — a distinctly colloquial/conversational usage worth
  flagging as a register-marked pattern (spoken register, offering unsolicited justification).

### Unit 10 — Clausal conjunctives: listing and choice (~고, ~(으)며, ~거나, ~든지)

- **~고** "and" / "and then" — links clauses regardless of chronological order for the "and" sense
  (order-neutral), but *does* encode sequence for the "and then" sense (order-changing the clauses
  changes the meaning). Not tense-conjugated (only main clause carries tense).
- **~(으)며** "and"/"while" — same core meaning as ~고 but narrower: only the non-sequential "and"
  sense (never "and then"), and it is a **written-register** conjunctive (register note: ~고 is used
  in both speech and writing; ~(으)며 tends to be writing-only). When both clauses share a subject,
  ~(으)며 additionally means "while" (simultaneity). Not tense-conjugated.
- **~거나** "or" — lists alternatives; can extend to "whether ... or" when the listed alternatives
  are trivial relative to the main clause's real point (날씨가 춥거나 덥거나 매일 뛰어요. "whether
  cold or hot, I run every day").
- **~든지** "or/no matter/regardless" — similar to ~거나's "whether...or" sense but additionally
  implies the speaker's **indifference/lack of enthusiasm** toward the listed options, not just their
  triviality.

### Unit 11 — Clausal conjunctives: time (~(으)면서, ~자마자, ~다가, ~다가는, ~(으)려다가)

- **~(으)면서** "while" — two actions/states by the *same subject* simultaneously; not
  tense-conjugated. **Register/pragmatic note:** frequently used specifically to voice
  disapproval/complaint when the two simultaneous facts are in tension (공부를 안 하면서 A를 받고
  싶어해요. "wants an A while not studying" — a criticizing stance baked into the grammar, not just
  the lexical content).
- **~자마자** "as soon as/immediately after" — verb-only; not tense-conjugated.
- **~다가** marks a **shift** — from one action to another (책을 읽다가 잤어요 "was reading, then
  fell asleep") or one state to another (오전까지 좋다가 지금은 흐립니다 "was clear until this
  morning, now cloudy"). The past-tense marker 었/았 is *optional* before ~다가: omitting it
  emphasizes the shift itself; including it (갔다가, not 가다가) emphasizes that the first action
  was actually completed before the shift occurred — a genuine two-way contrast, not free variation.
- **~다가는** (~다가 + topic particle 는) adds a **warning** sense: continuing the first clause's
  action risks an adverse consequence (매일 술을 마시다가는 건강을 해칠 수 있어요).
- **~(으)려다가** (~(으)려고 "intending to" + ~다가) — the intended action in the first clause is
  never actually carried out; a different action (in the main clause) happens instead (집에
  가려다가 서점에 갔습니다 "intended to go home, [but instead] went to a bookstore").

### Unit 12 — Clausal conjunctives: background (~는/(으)ㄴ데, ~는/(으)ㄴ데도)

- **~는/(으)ㄴ데** provides background/contextual information for a main clause (한국어를
  공부하는데 재미있어요. "I study Korean, and it's interesting"). Verb stems take ~는데
  regardless of shape; adjective/copula stems take ~은데 (consonant-final) / ~ㄴ데 (vowel-final);
  있다/없다-compound adjectives (재미있다, 맛있다 etc.) take ~는데 like verbs. In the past tense,
  *all* predicate types take ~았/었는데 uniformly.
- **Register/pragmatics — ~는/(으)ㄴ데(요) as a sentence-final ender:** in spoken communication,
  the conjunctive can end the utterance on its own, leaving the main clause implicit — a
  politeness/indirection strategy used specifically in face-threatening acts (refusing, declining,
  complaining) so the speaker doesn't have to spell out the dispreferred continuation (이번 주는
  바쁜데요. "I'm busy this week [so I can't come, unstated]"). The politeness marker 요 is
  optional on this sentence-final use. This is the same phenomenon noted for ~거든(요) in Unit 9 —
  a conjunctive "graduating" into an independent, register-marked spoken-language sentence-final
  device is recurring across this book's units and worth tracking as a general pattern.
- **~는/(으)ㄴ데도** (+ 도 "even/also") = "although/despite (the fact that)."

### Unit 13 — Clausal conjunctives: although (~지만)

- **~지만** "but/although" — acknowledges the first clause while contrasting it with the main
  clause. Unusually unrestricted among the conjunctives covered: it *is* tense-conjugated, has *no*
  subject-agreement restriction, and can attach to verb, adjective, or copula stems alike — the
  book uses ~지만 as its worked example of an unrestricted conjunctive (echoing the four-axis
  restriction framework introduced in Unit 7).

*(Coverage note: this unit's vocabulary list overlaps heavily in theme — personality/appearance
adjectives, "although" example sentences — with material a first-year "Basic Korean" text would
likely also cover; no direct cross-check against the sibling Basic Korean established/001-002
files was performed, per this dispatch's scope, but the vocabulary is retained in full since it is
this book's own bounded exercise list, not exercise filler.)*

### Unit 14 — Permission, prohibition, and obligation

- **Permission — ~어/아도 되다** (also 괜찮다/좋다 in place of 되다): "it's all right even if...";
  used interrogatively to *ask* for permission, declaratively to *give* it. In a negative
  construction (~지 않아도/안 ~아도 되다) it means "don't have to."
- **Prohibition — ~(으)면 안 되다** "it would not be all right if.../must not": the combination of
  ~(으)면 "if," negative 안, and 되다.
- **~(으)면 되다** (non-negated counterpart) means "all one has to do is..." — used to stress a
  *minimal* sufficient condition, not permission per se.
- **Obligation** is expressed two ways: (1) 안 ~(으)면 안 되다 (short-form negation) or the
  equivalent long-form ~지 않으면 안 되다 (both "(you) must..."; genuinely interchangeable, differ
  only in negation morphology, not meaning/register); (2) **~어/아야 되다** (or the more formal
  ~어/아야 하다) "must/have to."

### Unit 15 — Passives and causatives

- **Passives:** Korean forms a closed, lexically-restricted set of passive verbs by suffixing ~이,
  ~히, ~리, or ~기 to a (small, memorized) list of transitive-verb stems (보다→보이다 "be seen,"
  닫다→닫히다 "be closed," 열다→열리다 "be opened," 안다→안기다 "be held," etc.) — unlike English,
  where passivization is a fully general, productive process over nearly all transitives. When a
  sentence is passivized, the active object becomes the passive subject, and the active subject is
  marked with 한테/에게 if animate, 에 if inanimate (한국 학생들이 이 책을 읽는다 → 이 책이 한국
  학생들한테 읽힌다).
- **Causatives:** formed with a wider suffix set — ~이, ~히, ~리, ~기 (shared with the passive
  suffixes) plus three causative-only suffixes ~우, ~구, ~추 — again over a closed, memorized list
  of stems (먹다→먹이다 "feed," 입다→입히다 "dress someone," 울다→울리다 "make cry," 웃다→웃기다
  "make laugh," 낮다→낮추다 "lower," etc.). Because the ~이/히/리/기 suffixes are shared between the
  two systems, some derived forms (보이다, 업히다, 안기다) are genuinely ambiguous between a passive
  and a causative reading and must be disambiguated from context alone (아이가 리사한테 업혔어요
  "the child was carried on Lisa's back" [passive] vs. 어머니가 리사한테 아이를 업혔어요 "the
  mother had Lisa carry the child" [causative]).
- **~게 하다** (the long-form/productive causative) is the general-purpose alternative to the
  suffixed causative: attach ~게 하다 after essentially any verb or adjective stem (가다→가게 하다
  "make someone go," 기쁘다→기쁘게 하다 "make someone happy") — unlike the suffixed causative, this
  is fully productive and not restricted to a memorized list, mirroring the passive/causative
  suffix-vs.-productivity asymmetry already seen with English at the start of the unit.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — no bulk reproduction of vocabulary boxes, dialogue
blocks, or explanatory prose. See `../../00_Reference_Extraction_Spec.md`.
