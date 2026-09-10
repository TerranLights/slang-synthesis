# Korean — Established Vocabulary/Grammar: Units 1–15 (first half)

**Source:** Andrew Sangpil Byon, *Basic Korean: A Grammar and Workbook* (Routledge, 2009), PDF
pages 1–130 of 257 (printed pages 1–121, covering Preface + Units 1–15: Reading Hangul;
Characteristics of the Korean Language; Nouns; Predicates and Endings; The Deferential and Polite
Speech Levels; The Subject Case Particle 이/가; The Special Particle 은/는; Pronouns; Numbers,
Ordinals, and Plural Marker 들; Counters, Question Word 몇, and Time Expressions; The Copula
이다/아니다 and 있다/없다; Case Particles 1 을/를 and (으)로; Case Particles 2 의, 에, 와/과, (이)랑,
하고; Case Particles 3 에서, 에게, 한테, 께, 에게서, 한테서; Special Particles 1 도 and 만 (into its
exercises)). This is the first extraction for Korean.

**PDF text-layer gotcha found and worked around.** `pdftotext`/`pdfminer` both report a real text
layer for this PDF, but the Korean-language font (`Batang-KSCms-UHC-H-Identity-H`, `pdffonts`
confirms `emb: no` — not embedded, `Identity-H` encoding with no `ToUnicode` map) is **not
embedded**, so extracting the Hangul glyphs as text produces either unrelated Unicode characters
(scrambled to Sinhala-range codepoints via a fallback substitute font) or bare unresolved
`(cid:NNNN)` codes, depending on the extraction tool — a variant of the "fixed font-substitution
cipher" gotcha in `00_Reference_Extraction_Spec.md`, except here the corruption is not a stable
1:1 substitution and could not be decoded. **All Korean-language content in this file was
extracted by rendering PDF pages to images and reading them visually** (the Read tool's built-in
PDF-to-image rendering), not from the corrupted text layer. English explanatory prose in the PDF
*does* have a clean, directly-extractable text layer (embedded Latin-script fonts render fine) —
only the Hangul is affected. This is worth flagging for every future Korean-source dispatch in
this project: **check `pdffonts` for the Korean-script font's `emb`/`uni` columns before trusting
`pdftotext` on any Korean PDF; if the CJK font isn't embedded with a Unicode map, vision-read
instead, even when English portions of the same PDF extract cleanly.**

**Vision-reading confidence.** Every page in this range is genuinely typeset, print-quality
textbook content — no scan artifacts, no handwritten marginalia, no ambiguous glyphs were found
anywhere in pages 1–130. All Korean-language entries below are marked Vision Reading Confidence
`verified` (Hangul renders cleanly and unambiguously at the resolution provided; most vocabulary
items also recur across multiple pages/units, e.g. 먹다 "eat," 가다 "go," 책 "book," corroborating
the reading). No entries required a `plausible_unverified` or `low_confidence` flag.

**Coverage note.** Every grammar point and every distinct vocabulary/particle item in Units 1–15
(through the start of Unit 15's exercises) is captured below. Repeated drill-exercise sentences
that reuse already-captured vocabulary/grammar without introducing anything new are not
individually transcribed (per the spec's coverage rule) — only their vocabulary payload is
captured once, in the unit's "Key vocabulary for exercises" table. Unit 1's loanword/toponym
reading drills (Exercises 1.5–1.11: Korean spellings of borrowed English words, world cities,
countries, and people's names) are represented by a **selective sample** rather than exhaustively
transcribing all ~90 items, since they are phonological-reading drill material (how Hangul spells
loanword syllables) rather than distinct lexical/grammatical content — the phonological pattern
itself (which the sample illustrates) is the extractable finding, not each individual toponym.

---

## Vocabulary

### Unit 1 — Reading Hangul (loanword-spelling sample, p. 5–7)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 커피 | coffee | noun (loanword) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | English loanword; Hangul spelling drill (Ex. 1.5, p. 5). |
| 택시 | taxi | noun (loanword) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | English loanword (Ex. 1.5). |
| 스타벅스 | Starbucks | proper noun (loanword) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | English loanword; brand name (Ex. 1.5). |
| 컴퓨터 | computer | noun (loanword) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | English loanword (Ex. 1.11). |
| 텔레비전 | television | noun (loanword) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | English loanword (Ex. 1.11). |
| 샴푸 | shampoo | noun (loanword) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | English loanword (Ex. 1.11). |
| 서울 | Seoul | proper noun | core | — | contemporary (source published 2009) | South Korea | national | grammar_reference | n/a | verified | Toponym reading drill (Ex. 1.7). |
| 한국 | South Korea | proper noun | core | — | contemporary (source published 2009) | South Korea | national | grammar_reference | n/a | verified | Toponym reading drill (Ex. 1.8). |

### Unit 3 — Nouns (key vocabulary for exercises, p. 19–20)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가 | the edge | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 개 | dog | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 계란 | egg | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 고기 | meat(s) | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 고무 | rubber | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 고무신 | rubber shoes | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Compound: 고무 "rubber" + 신 "shoes." |
| 나물 | greens | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 돌 | stone/pebble | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 문 | door | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 물 | water | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 물개 | seal (animal) | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Compound: 물 "water" + 개 "dog." |
| 바늘 | needle | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 바다 | sea | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 바닷가 | seaside | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Compound: 바다 "sea" + 가 "edge." |
| 방 | room | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 빵 | bread | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 빵집 | bakery | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Compound: 빵 "bread" + 집 "house." |
| 벽 | wall | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 벽돌 | brick | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Compound: 벽 "wall" + 돌 "stone." |
| 부채 | fan (hand fan) | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 사업 | business | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 산나물 | wild edible greens | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Compound: 산 "mountain" + 나물 "greens." |
| 새 | bird | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 신 | shoes | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 앞 | front | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 앞문 | front door | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Compound: 앞 "front" + 문 "door." |
| 음악 | music | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 철 | season | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 철새 | migratory bird | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Compound: 철 "season" + 새 "bird." |
| 책 | book | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 책방 | book store | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Compound: 책 "book" + 방 "room." |
| 코 | nose | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 코피 | blood from the nose | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Compound: 코 "nose" + 피 "blood." |
| 피 | blood | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |

### Unit 3 — derivational affix examples (p. 16–17)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 맏아들 | the first son | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | 맏 (native prefix, "first") + 아들 (son). |
| 맏딸 | the first daughter | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | 맏 (first) + 딸 (daughter). |
| 신학기 | a new semester | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | 신 (Sino-Korean prefix, "new") + 학기 (semester). |
| 신인 | a new comer | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | 신 (new) + 인 (person). |
| 장사꾼 | businessman | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | 장사 (business) + 꾼 (native suffix, "doer"). |
| 일꾼 | worker | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | 일 (work) + 꾼 (doer). |
| 한국학 | Korean studies | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | 한국 (Korea) + 학 (Sino-Korean suffix, "study"). |
| 수학 | mathematics | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | 수 (number) + 학 (study). |
| 벌이 | income | noun (deverbal) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | 벌 (earn) + 이 (nominalizing suffix, "act"). |
| 먹기 | eating | noun (deverbal) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | 먹 (eat) + 기 (nominalizing suffix, "act"). |
| 크기 | size | noun (deadjectival) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | 크 (big) + 기 (nominalizing suffix, "quality"). |
| 길이 | length | noun (deadjectival) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | 길 (long) + 이 (nominalizing suffix, "quality"). |
| 눈물 | tears | noun (compound) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | 눈 "eye" + 물 "water." |
| 곱슬머리 | curly hair | noun (compound) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | 곱슬 "curved" (adverb) + 머리 "hair." |
| 산들바람 | gentle breeze | noun (compound) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | 산들 "gentle" (adverb) + 바람 "wind." |
| 목걸이 | necklace | noun (compound) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | 목 "neck" + 걸 "hang" (predicate) + 이 (nominalizer). |
| 본보기 | model/example | noun (compound) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | 본 "example" + 보 "look" (predicate) + 기 (nominalizer). |
| 늦잠 | oversleeping | noun (compound) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | 늦 "late" (predicate) + 잠 "sleeping." |
| 부모 | parents | noun (compound) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Sino-Korean: 부 "father" + 모 "mother." |
| 천지 | universe | noun (compound) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Sino-Korean: 천 "heaven" + 지 "earth." |

### Unit 4 — Vowel-/consonant-based verb & adjective stems (p. 24–25)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가다 | go | verb (vowel-based stem 가) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 먹다 | eat | verb (consonant-based stem 먹) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Recurs throughout the book as the canonical example verb. |
| 배우다 | learn | verb (vowel-based stem 배우) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 요리하다 | cook | verb (vowel-based stem 요리하) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 나쁘다 | bad | adjective (vowel-based stem 나쁘) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 작다 | small | adjective (consonant-based stem 작) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 좋다 | good | adjective (consonant-based stem 좋) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 아름답다 | beautiful | adjective (consonant-based stem 아름답) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 가르다 | divide | verb (vowel-based) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 가지다 | have | verb (vowel-based) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 가르치다 | teach | verb (vowel-based) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 만지다 | touch | verb (vowel-based) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 보다 | see | verb (vowel-based) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 타다 | ride | verb (vowel-based) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 닫다 | close | verb (consonant-based) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 신다 | wear (shoes) | verb (consonant-based) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 받다 | receive | verb (consonant-based) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 살다 | live | verb (consonant-based) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 앉다 | sit | verb (consonant-based) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 읽다 | read | verb (consonant-based) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 팔다 | sell | verb (consonant-based) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 시다 | sour | adjective (vowel-based) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 싸다 | cheap | adjective (vowel-based) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 쓰다 | bitter | adjective (vowel-based) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 짜다 | salty | adjective (vowel-based) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 크다 | big | adjective (vowel-based) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 흐리다 | cloudy | adjective (vowel-based) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 희다 | white | adjective (vowel-based) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 가볍다 | light (weight) | adjective (consonant-based) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 가깝다 | near | adjective (consonant-based) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 괜찮다 | fine/OK | adjective (consonant-based) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 넓다 | wide | adjective (consonant-based) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 많다 | many | adjective (consonant-based) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |

### Unit 5 — key vocabulary for exercises (p. 32–35)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가게 | store | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 가르치다 | to teach | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 건너다 | to cross over | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 공 | ball | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 구두 | shoes (formal) | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 그리다 | to draw | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 그림 | painting | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 기다리다 | to wait | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 기분 | feeling | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 기차 | train | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 기회 | chance | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 길 | road | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 깨끗하다 | to be clean | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 날씨 | weather | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 내려가다 | to go down | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 느리다 | to be slow | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 닫다 | to close | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 달다 | to be sweet | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 담배 | cigarette | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 대학생 | college student | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 던지다 | to throw | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 두드리다 | to knock | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 따르다 | to follow | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 뜨겁다 | to be hot (water) | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 마시다 | to drink | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 마치다 | to finish | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 매일 | everyday | adverb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 멀다 | to be far | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 문 | door | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 물고기 | fish | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 믿다 | to believe | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 밑 | bottom | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 바쁘다 | to be busy | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 받다 | to receive | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 방 | room | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 배 | stomach | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Homophone of 배 "pear"/"boat," not distinguished in source. |
| 배우다 | to learn | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 버리다 | to throw away | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 버스 | bus | noun (loanword) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 보내다 | to send | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 보다 | to see/watch | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 빌리다 | to borrow | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 선생님 | teacher | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | 님 is the honorific title suffix (see Grammar points). |
| 손 | hand | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 숙제 | homework | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 쉽다 | to be easy | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 쓰레기 | garbage | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 시험 | test | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 시끄럽다 | to be noisy | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 신다 | to wear (shoes) | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 싱싱하다 | to be fresh | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 씻다 | to wash | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 아니다 | to not be | adjective/copula | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 아침 | morning | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 아프다 | to be hurt/sick | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 앉다 | to sit | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 야채 | vegetable | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 어디 | where | pronoun/adverb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 언제 | when | pronoun/adverb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 여기 | here | pronoun/adverb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 열다 | to open | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 영어 | English (language) | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 영화 | movie | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 일 | work | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 일어나다 | to get up | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 일찍 | early | adverb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 읽다 | to read | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 입다 | to wear (clothes) | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 자다 | to sleep | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 잡다 | to catch | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 재미있다 | to be interesting/fun | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 점심 | lunch | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 좋다 | to be good | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 주다 | to give | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Plain-register "give"; contrast honorific 드리다 introduced in Unit 14. |
| 지갑 | wallet | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 집 | house | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 찾다 | to find | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 춥다 | to be cold (weather) | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 친구 | friend | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 커피 | coffee | noun (loanword) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 코메디 | comedy | noun (loanword) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 코트 | coat | noun (loanword) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 크게 | aloud/loudly | adverb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 타다 | to ride | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 택시 | taxi | noun (loanword) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 팔다 | to sell | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 편지 | a letter | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 피우다 | to smoke | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 하늘 | sky | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 하다 | to do | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Highly productive light verb (see Unit 12 grammar points, noun+을/를+해요). |
| 학교 | school | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 한국 사람 | Korean(s) (person) | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Compound: 한국 "Korea" + 사람 "person." |
| 한국어 | the Korean language | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 헤어지다 | to be separated/break up | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 흐리다 | to be cloudy | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |

### Unit 6 — key vocabulary for exercises (p. 41–43)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가깝다 | to be near | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 가격 | price | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 가수 | singer | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 간호사 | nurse | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 강아지 | puppy | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 국 | soup | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 귀엽다 | to be cute | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 기자 | journalist | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 김치 | kimchi | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 넓다 | to be spacious | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 달다 | to be sweet | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 더럽다 | to be dirty | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 덥다 | to be hot (weather) | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 도서관 | library | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 뜨겁다 | to be hot (water) | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 레몬 | lemon | noun (loanword) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 많다 | to be many | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 맛없다 | to be tasteless | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Negative compound: 맛 "taste" + 없다 "not exist/have." |
| 맛있다 | to be delicious | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | 맛 "taste" + 있다 "exist/have." |
| 맵다 | to be spicy | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 머리 | head | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 목수 | carpenter | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 미지근하다 | to be lukewarm | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 비싸다 | to be expensive | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 싸다 | to be cheap | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 설탕 | sugar | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 성격 | personality | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 소금 | salt | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 쉽다 | to be easy | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 스케줄 | schedule | noun (loanword) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 쓰다 | to be bitter (taste) | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Homograph with 쓰다 "to write/use." |
| 시다 | to be sour | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 시험 | test | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 싱겁다 | to be bland | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 아름답다 | to be beautiful | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 앵커우먼 | anchorwoman | noun (loanword) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 약 | medicine | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 약사 | pharmacist | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 어렵다 | to be difficult | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 어지럽다 | to be dizzy | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 엔지니어 | engineer | noun (loanword) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 영화 배우 | movie star | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Compound: 영화 "movie" + 배우 "actor." |
| 위험하다 | to be dangerous | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 음식 | food | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 의사 | medical doctor | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 자동차 | car | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 짜다 | to be salty | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 짧다 | to be short | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 재미있다 | to be interesting | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 조용하다 | to be quiet | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 차 | tea | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 차갑다 | to be cold (water) | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 초콜릿 | chocolate | noun (loanword) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 캠퍼스 | campus | noun (loanword) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |

### Unit 7 — key vocabulary for exercises (p. 50–51)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 계절 | season | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 꽃 | flower | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 과목 | subject/course | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 색 | color | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 소설 | novel | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 역사 | history | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 운동 | sport | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 이탈리아 | Italy | proper noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 자동차 | automobile | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 장미 | rose | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 코미디 | comedy | noun (loanword) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 과랑 (파랑) | blue (color) | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Rendered 과랑 in the source table but glossed with 파랑색 "blue" elsewhere in the same unit's exercises — likely the same word; flagged rather than silently normalized. |
| 필리핀 | Philippines | proper noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 한국 | South Korea | proper noun | core | — | contemporary (source published 2009) | South Korea | national | grammar_reference | n/a | verified | |
| 호주 | Australia | proper noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |

### Unit 8 — Pronouns and kinship terms (p. 55–60)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 나 | I (plain, singular) | pronoun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Plain 1sg; contrast humble 저. Used toward equals/lower-status addressees. |
| 내 | my (plain, singular possessive) | pronoun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | 나 + 의 (possessive particle) contracted. |
| 우리 | we/our (plain, plural/possessive) | pronoun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Widely used for communal possessions even in singular reference due to collectivistic usage (e.g. 우리 집 "my/our house"). |
| 저 | I (humble, singular) | pronoun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Honorific-register 1sg; safe default toward adults one doesn't know well; collocates with honorific elements. |
| 제 | my (humble, singular possessive) | pronoun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | 저 + 의 contracted. |
| 저희 | we/our (humble, plural/possessive) | pronoun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Preferred over 우리 in +power/formal contexts. |
| 너 | you (plain, singular) | pronoun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Restricted to children, childhood friends, younger siblings, one's own children. |
| 네 | your (plain, singular possessive) | pronoun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 너희 | you (plain, plural) | pronoun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 당신 | you (polite, singular) | pronoun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Mostly restricted to use between spouses; sounds confrontational toward strangers — Korean has no true polite 2nd-person pronoun for general use. |
| 당신의 | your (polite, singular possessive) | pronoun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 당신들 | you (polite, plural) | pronoun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 그 | that/he/she (as demonstrative + omitted noun) | pronoun (demonstrative) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Korean has no true 3rd-person pronoun; demonstrative + noun substitutes (그 사람 "that person," 그 분 "that esteemed person"). |
| 그들 | they | pronoun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 여보 | darling | address term | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Spousal address term. |
| 오빠 | older brother (said by a female) | kinship/address term | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Also used by a wife to address a husband older than her. |
| 아빠 | dad | kinship/address term | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 아버지 | father | kinship term | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 어머니 | mother | kinship term | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Also used to address a friend's mother, non-kin, per collectivistic extension. |
| 할아버지 | grandfather / (extended) elderly stranger | kinship/address term | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Used to address an unrelated elderly stranger (over ~60s). |
| 할머니 | grandmother / (extended) elderly stranger | kinship/address term | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 장인 | father-in-law (of a male) | kinship term | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Gender-of-speaker-specific kinship term (Group 1). |
| 시아버지 | father-in-law (of a female) | kinship term | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 장모 | mother-in-law (of a male) | kinship term | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 시어머니 | mother-in-law (of a female) | kinship term | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 형 | older brother (said by a male) | kinship term | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Gendered sibling terms: distinct words depending on both the speaker's and sibling's gender. |
| 누나 | older sister (said by a male) | kinship term | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 언니 | older sister (said by a female) | kinship term | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 부모 | parents | kinship term | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 아들 | son | kinship term | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 딸 | daughter | kinship term | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 손주 | grandchild(ren) | kinship term | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 남동생 | younger brother | kinship term | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Ungendered-by-speaker term (Group 2, used by both genders). |
| 여동생 | younger sister | kinship term | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 삼촌 | paternal uncle (unmarried, younger than father) | kinship term | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Korean kinship terms mark relative age and marital status far more granularly than English. |
| 외삼촌 | maternal uncle | kinship term | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 고모 | paternal aunt | kinship term | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 이모 | maternal aunt | kinship term | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 사위 | son-in-law | kinship term | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 며느리 | daughter-in-law | kinship term | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 사촌 | cousin | kinship term | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 가방 | bag | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 가족 | family | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 경찰 | police | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 고등학생 | high-school student | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 남편 | husband | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 사무실 | office | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 신발 | shoes | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 전공 | major (academic) | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 지갑 | wallet | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 초등학교 | elementary school | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 회사 | company | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 회사원 | office worker | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |

### Unit 9 — Numbers (Sino-Korean vs. native, p. 65–68)

Korean has two full parallel number systems rather than a vocabulary list per se; the numerals
1–20 in both sets (with irregular modified forms for 1,2,3,4,20 before a counter) are captured
here as a single comparative table rather than individual rows, per the spec's guidance not to
force atomization on what is really one paradigm.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 일, 이, 삼, 사, 오, 육, 칠, 팔, 구, 십 | 1–10 (Sino-Korean) | numeral | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Borrowed from Chinese; used for math, dates, money, and all numbers ≥100. |
| 하나(한), 둘(두), 셋(세), 넷(네), 다섯, 여섯, 일곱, 여덟, 아홉, 열 | 1–10 (native Korean) | numeral | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Native set has no "zero"; parenthesized forms are the modified forms used directly before a counter (한 명, not 하나 명). |
| 스물(스무) | 20 (native Korean) | numeral | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | 스무 is the modified pre-counter form (스무 살 "20 years old"), one of only 5 native numbers with a modified counter-form (1,2,3,4,20). |
| 영/공 | 0 | numeral | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Sino-Korean only — native Korean has no word for zero. |
| 첫 번째 | the first (native ordinal) | ordinal | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Irregular: native ordinals normally add 번째 to the cardinal (다섯 번째 "the fifth"), but "one" uniquely uses 첫, not the expected 한. |

### Unit 10 — Counters used with native Korean numbers (Table 10.1, p. 73–74)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 명 | counter: persons | counter/classifier | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | 한 명 "one person"; can also take Sino-Korean numbers above 20. |
| 사람 | counter: persons (alt.) | counter/classifier | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 마리 | counter: animals | counter/classifier | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 쌍 | counter: couples (people/animals) | counter/classifier | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 송이 | counter: flowers | counter/classifier | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 다발 | counter: bunches (of flowers) | counter/classifier | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 그루 | counter: trees | counter/classifier | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 조각 | counter: slices | counter/classifier | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 개 | counter: items/units | counter/classifier | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Most general-purpose counter. |
| 상자 | counter: boxes | counter/classifier | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 대 | counter: machines, cars | counter/classifier | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 채 | counter: houses, buildings | counter/classifier | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 시 | counter: o'clock | counter/classifier | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 시간 | counter: hours (duration) | counter/classifier | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 달 | counter: months (duration) | counter/classifier | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 해 | counter: years | counter/classifier | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Rarely used beyond 두 해. |
| 살 | counter: years of age | counter/classifier | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 번 | counter: times/occurrences | counter/classifier | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 잔 | counter: cupfuls | counter/classifier | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 병 | counter: bottles | counter/classifier | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 봉지 | counter: paper bags | counter/classifier | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 장 | counter: pieces of paper | counter/classifier | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 권 | counter: books | counter/classifier | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 군데 | counter: places | counter/classifier | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 켤레 | counter: pairs of shoes | counter/classifier | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 벌 | counter: clothes | counter/classifier | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 가지 | counter: kinds | counter/classifier | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |

### Unit 10 — Counters used with Sino-Korean numbers (Table 10.2, p. 74)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 일 | counter: days | counter/classifier | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 월 | counter: month names | counter/classifier | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | June is irregularly 유월, not 육월; October is irregularly 시월, not 십월. |
| 개월 | counter: months (duration) | counter/classifier | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Sino-Korean counterpart to native 달. |
| 년 | counter: years | counter/classifier | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 분 | counter: minutes | counter/classifier | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Paired with native-number 시 "o'clock" in telling time — a mixed-system compound (e.g. 두 시 십오 분, native+Sino). |
| 초 | counter: seconds | counter/classifier | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 층 | counter: floors (of a building) | counter/classifier | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 달러 (달라) | counter: dollars | counter/classifier | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Loanword counter; loanword counters default to Sino-Korean numbers. |
| 파운드 | counter: pounds sterling | counter/classifier | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 마일 | counter: miles | counter/classifier | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 몇 | question word: "how many" | interrogative | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Cannot stand alone — must precede a counter (몇 명 "how many people?"). |

### Unit 11 — key vocabulary + location nouns (p. 82, 84–85)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 위 | above | noun (postpositional location) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Location nouns follow the object noun (책상 위 "table-above"), unlike English prepositions. |
| 아래 | below | noun (postpositional location) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 밑 | under | noun (postpositional location) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 뒤 | behind | noun (postpositional location) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 앞 | front | noun (postpositional location) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 안 | inside | noun (postpositional location) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 밖 | outside | noun (postpositional location) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 옆 | side | noun (postpositional location) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 오른쪽 | right side | noun (postpositional location) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 왼쪽 | left side | noun (postpositional location) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 간호사 | nurse | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 개 | dog | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 경찰 | police | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 계산기 | calculator | noun (loanword-derived) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 고양이 | cat | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 과학자 | scientist | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 그림 | painting | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 기자 | journalist | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 꽃 | flower | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 대학생 | college student | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 디자이너 | designer | noun (loanword) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 모자 | hat | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 볼펜 | ball-point pen | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 빵 | bread | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 사업가 | businessman | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 신문 | newspaper | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 엔지니어 | engineer | noun (loanword) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 열쇠 | key | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 외교관 | diplomat | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 우산 | umbrella | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 의사 | medical doctor | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 의자 | chair | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 자전거 | bike | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 책상 | desk | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 침대 | bed | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 회계사 | accountant | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 휴지통 | waste basket | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Compound: 휴지 "tissue/waste paper" + 통 "container." |

### Unit 12 — key vocabulary for exercises (p. 92–94)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 과일 | fruit | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 게임 | game | noun (loanword) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 공부하다 | to study | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 국수 | noodle | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 기숙사 | dormitory | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 담배 | cigarette | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 도서관 | library | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 만나다 | to meet | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 먹다 | to eat | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 문화 | culture | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 바꿔주다 | to change (for someone) | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | 바꾸다 "change" + benefactive 주다 "give." |
| 비행기 | airplane | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 빨래 | laundry | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 사진 | picture | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 산책 | stroll | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 설거지 | dish washing | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 세수 | face washing | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 약속 | promise | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 얼굴 | face | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 외식 | eating out | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 외우다 | to memorize | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 요리 | cooking | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 이기다 | to win | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 이야기 | talking/story | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 젓가락 | chopsticks | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 지키다 | to keep (a promise) | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 찍다 | to take (a photograph) | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 청소 | cleaning | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 하얀색 | white color | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 흔들다 | to shake | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |

### Unit 13 — key vocabulary for exercises (p. 103–104)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가을 | autumn | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 공항 | airport | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 교실 | classroom | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 교회 | church | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 기름 | oil | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 땅 | earth | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 반지 | ring | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 병원 | hospital | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 봄 | spring | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 불 | fire | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 사자 | lion | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 시계 | watch | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 약국 | pharmacy | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 옷 | clothes | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 전쟁 | war | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 책방 | bookstore | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 캔디 | candy | noun (loanword) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 평화 | peace | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 호텔 | hotel | noun (loanword) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 것/거 | (bound noun) thing | bound noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Cannot stand alone; 거 is the colloquial contraction. See grammar points, possessive 의. |

### Unit 14 — key vocabulary for exercises (p. 111)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 도착하다 | to arrive | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 말하다 | to speak | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 미국 | America/USA | proper noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 드리다 | to give (honorific) | verb | honorific | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Suppletive honorific counterpart of plain 주다 "give," used toward an esteemed indirect object marked by 께. |

### Unit 15 — key vocabulary for exercises (p. 120–121)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 고기 | meat | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 노래 | song | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 녹차 | green tea | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 돕다 | to help | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 바지 | pants | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 부르다 | to call/to sing | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 손님 | customer | noun | honorific | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | 님 honorific-title suffix attached to 손 "guest." |
| 쉬다 | to rest | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 여권 | passport | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 좋아하다 | to like | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 청바지 | jeans | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | Compound: 청 "blue/denim" + 바지 "pants." |
| 추다 | to dance | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 축구 | soccer | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 치다 | to play (instrument/sports) | verb | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |
| 화장실 | restroom | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | |

---

## Grammar points

### Unit 1 — Reading Hangul (p. 1–7)

Hangul (21 vowel + 19 consonant symbols) was invented in 1443 under King Sejong during the Chosun
dynasty. 11 basic vowels + 10 double-vowels; the double-vowels either add an extra stroke (the *y*
glide, e.g. ㅏ "a" → ㅑ "ya") or combine two basic vowels (ㅗ+ㅏ → ㅘ "wa"). Not all combinations
occur: Korean's **vowel harmony principle** groups vowels as "bright" (ㅏ, ㅗ and their derived
forms ㅐ, ㅘ, ㅑ, ㅛ), "dark" (ㅓ, ㅜ and derived ㅝ, ㅞ, ㅕ), and "neutral" (ㅣ, ㅡ) — bright and
dark vowels historically could not combine in the same word. (Byon doesn't develop this further
in this chapter — it is stated as the historical reason certain double-vowel glyphs don't exist,
not as a productive modern harmony rule; contrast the fully worked Hungarian vowel-harmony system
already extracted for that language, where the rule is still fully synchronically active.)

19 consonants form a systematic three-way series at several places of articulation: plain/lax
(ㅂ,ㄷ,ㄱ,ㅈ — "relaxed"), aspirated (ㅍ,ㅌ,ㅋ,ㅊ), and tense/fortis (ㅃ,ㄸ,ㄲ,ㅉ — "with puffs of
air" vs. no puff vs. tense). Every Korean syllable-block must begin with a consonant symbol even
when there is no actual initial consonant sound — the zero-value placeholder ㅇ fills this role
word-initially (아 "a," not a bare ㅏ). Five syllable-block shapes exist: V-only (using placeholder
ㅇ), CV, VC, CVC, and CVCC. Hangul spelling is **morphophonemically conservative**: spelling
doesn't change just because pronunciation shifts in context (parallel to English not respelling
words to match casual pronunciation).

### Unit 2 — Characteristics of the Korean language (p. 9–13)

- **Word order (SOV).** Korean is verb-final (subject-object-verb), unlike English's SVO. Because
  case particles mark grammatical role directly, word order is comparatively free — Byon
  demonstrates six different orderings of 앤드류가 집에서 점심을 먹어요 ("Andrew eats lunch at
  home") that all remain grammatical, since 가/에서/을 fix each noun's role regardless of position.
  Word order becomes meaningful mainly when particles are dropped (common in colloquial speech).
- **Context-oriented language.** The most important sentence elements cluster at the very end
  (verbs/adjectives); the further a word sits from the end, the more omissible it is. A bare verb
  with no subject or object (e.g. 먹어요 "eat[s]") is fully grammatical and natural — subject/object
  pronouns are routinely dropped when recoverable from context, unlike the near-mandatory English
  subject.
- **General-to-specific ("big-to-small") ordering.** Family name precedes given name; addresses go
  country → province → city → street → house number → recipient name; dates go year → month → day
  — the reverse of English convention in all three cases.
- **Honorific language — the single most register-relevant finding in this chunk.** Korean
  grammaticalizes social meaning (speaker's respect, humility, formality toward the addressee or
  referent) directly into sentence structure via: (1) hierarchical address/reference terms and
  multiple speech levels: hearer-oriented; (2) humble first-person pronoun forms 저/저희 (vs. plain
  나/우리); (3) the honorific suffix -(으)시 attached to a verb/adjective stem to show respect
  toward a *subject* of higher status; (4) euphemistic/suppletive honorific words (e.g. 드리다
  "give" honorific vs. 주다 plain, introduced fully in Unit 14). Byon's own minimal-pair
  illustration: 어제 우리 모임에 와 주어서 고마워 ("I appreciated that you came to our meeting
  yesterday," -power/intimate register: plain 우리, no honorific suffix, intimate ending -어) vs.
  어제 저희 모임에 와 주시어서 고맙습니다 (+power/formal register: humble 저희, honorific suffix
  -시 added to 주다→주시다, deferential ending -습니다) — same referential meaning, entirely
  different social meaning. Byon's own gloss: **"how an utterance is said is more important than
  what is said."**

### Unit 3 — Nouns (p. 15–21)

Korean word classes: nouns, pronouns, particles, numbers/counters, verbs, adjectives, copula
(이다 "be" / 아니다 "be not"), adverbs, prenouns. Words split into **inflected** (verbs, adjectives
— take endings for tense/aspect/speech level/person) and **uninflected** (nouns, pronouns,
numbers, adverbs, prenouns) categories.

Korean nouns derive from three sources: **native Korean** (~35%), **Sino-Korean** (~60%,
historically borrowed from Chinese), and **loanwords** (~5%, mostly English). Multi-morpheme
nouns form via **derivation** (prefix or suffix attachment — native prefix 맏- "first," Sino-Korean
prefix 신- "new," native suffix -꾼 "doer," Sino-Korean suffix -학 "study/-ology," deverbal/
deadjectival nominalizers -이/-기) or **compounding** (noun+noun, adverb+noun, noun+predicate+
nominalizer, predicate+noun, clause+noun, and Sino-Korean+Sino-Korean word combinations). See the
worked morpheme breakdowns in the Unit 3 vocabulary table above.

Korean nouns carry **no grammatical number**: a bare noun like 연필 "pencil" is ambiguous between
"a pencil," "the pencil," "some pencils," "the pencils," and "pencils" — the plural suffix 들 (see
Unit 9) is optional and used only to *emphasize* plurality, not obligatorily. **Prenouns** (e.g.
무슨 "what kind of," 이/그/저 "this/that") always precede the noun they modify, paralleling English
demonstratives; a subclass of **bound nouns** (이 곳 "this place," 그 분 "that esteemed person,"
저 것 "that thing") can never appear without a preceding prenoun (detailed later in Unit 22, outside
this dispatch's range).

Korean nouns show **noun-verb collocation restrictions** distinct from literal translation: 농구를
해요 "plays (lit. does) basketball" is correct where 놀아요 "plays" (the more literal cognate of
English "play") is not; piano/guitar instead take 쳐요 "plays/hits." This is a lexical-collocation
constraint, not a general grammar rule, and Byon flags it as something KFL learners get wrong via
native-language transfer.

### Unit 4 — Predicates and endings (p. 23–28)

Korean verbs/adjectives = **stem + ending(s)**; stems never stand alone. The citation/dictionary
form always ends in -다, which is stripped to find the stem (가다 → 가; 먹다 → 먹). Stems split into
**vowel-based** (end in a vowel, e.g. 가) and **consonant-based** (end in a consonant, e.g. 먹) —
this distinction conditions which allomorph of nearly every subsequent ending attaches (parallel in
function, though not in phonological content, to Hungarian's vowel-harmony-driven allomorphy or
Finnish's stem alternation already documented for other languages in this project).

Korean draws no sharp structural line between verbs and adjectives — Korean grammarians call
adjectives "descriptive verbs" since both inflect identically and both can serve as the sole
predicate of a sentence (unlike English, which requires a copula before a predicate adjective).
Semantically, verbs denote actions/processes; adjectives denote states/qualities (size, weight,
quality, quantity, shape, appearance, perception, emotion).

**Endings** are two structural types: **pre-final endings** (inflectional slots between the stem
and the final ending — the honorific suffix -(으)시, the past-tense marker -았/었, etc.) and
**final endings**, themselves split into **non-sentence-final** (clausal conjunctives: -고 "and
then," -어/아서 "because," -으면서 "while," -지만 "although," -도록 "in order to") and
**sentence-final** endings.

**The six Korean speech levels — the central register-system finding for this project.** Every
sentence-final ending encodes not just sentence type (declarative/interrogative/imperative/
propositive) but also one of six **speech levels**, ranked by formality:

| # | Level | Declarative | Interrogative | Imperative | Propositive |
|---|---|---|---|---|---|
| 1 | Deferential | -습니다/-ㅂ니다 | -습니까/-ㅂ니까 | -(으)십시오 | -(으)십시다 |
| 2 | Polite | -어요/-아요 | -어요/-아요 | -어요/-아요 | -어요/-아요 |
| 3 | Blunt | -(으)오 | -(으) 오 | — | — |
| 4 | Familiar | -네 | -나/-는가 | -게 | -세 |
| 5 | Intimate | -어/-아 | -어/-아 | -어/-아 | -어/-아 |
| 6 | Plain | -(느)ㄴ다 | -(으)니/-냐 | -어라/-아라 | -자 |

Byon explicitly notes that levels 3 (Blunt) and 4 (Familiar) are declining among younger
generations and are deliberately **not covered further in this book** — a source-internal
register-obsolescence note worth flagging for the sci-fi-conlang synthesis phase (a live language
can shed whole formality strata over a generation; a designed slang register system could
plausibly mirror or invert this kind of stratum-loss). The book's own pedagogical focus is levels
1, 2, 5, and 6 (deferential, polite, intimate, plain), which it says remain "widely used for all
Koreans regardless of age." Critically: **the same referential stem + same referential meaning
maps to radically different social meaning purely via which speech-level ending is chosen** —
Byon's own four-way example, applying 먹 "eat" to all four question endings (먹습니까?/먹어요?/
먹어?/먹나?), differing only in "possible social setting" (formal / to an adult colleague / to an
adolescent friend / to a child), not in what is being asked.

### Unit 5 — The deferential and polite speech levels (p. 29–38)

Full worked morpheme breakdown for the two speech levels this unit focuses on:

> **Deferential declarative:** stem + **-습니다** (after a consonant-final stem, e.g. 먹+습니다 =
> 먹습니다 "[someone] eats") / stem + **-ㅂ니다** (after a vowel-final stem, e.g. 가+ㅂ니다 = 갑니다
> "[someone] goes"). Formulaic deferential expressions recur in fixed social routines: 처음
> 뵙겠습니다 "nice to meet you" (lit. "I meet you for the first time"), 감사합니다 "thank you" (lit.
> "I do gratitude"), 실례합니다 "excuse me" (lit. "I do discourtesy") — the deferential ending is
> the default register of Korean politeness formulas, not just formal-occasion speech.
>
> **Deferential interrogative:** stem + **-습니까** (consonant-final) / stem + **-ㅂ니까**
> (vowel-final) — 먹습니까? "(do you) eat?"; 갑니까? "(do you) go?"
>
> **Deferential imperative:** stem + **-(으)십시오** — consonant-final stems take -으십시오 (먹+
> 으십시오 = 먹으십시오 "eat"), vowel-final stems take -십시오 (가+십시오 = 가십시오 "go").
>
> **Deferential propositive:** stem + **-(으)십시다** — 먹으십시다 "(let us) eat"; 가십시다
> "(let us) go."
>
> **Polite (all four sentence types share one ending pair):** stem + **-아요** (after a stem
> ending in ㅏ or ㅗ) / stem + **-어요** (after any other vowel-final ending). Vowel contraction is
> pervasive here: 가다 "go" → 가+아요 → 가요 (not *가아요); 오다 "come" → 오+아요 → 와요; 보다 "see"
> → 보+아요 → 봐요; 배우다 "learn" → 배우+어요 → 배워요; 기다리다 "wait" → 기다리+어요 → 기다려요.
> Consonant-final stems attach without contraction: 받다 "receive" → 받아요; 살다 "live" → 살아요;
> 넣다 "put in" → 넣어요; 묶다 "tie" → 묶어요; 먹다 "eat" → 먹어요. The copula 이다/아니다 and the
> verb 하다 "do" are irregular exceptions: 이다 → 이에요 (not *이어요); 아니다 → 아니에요; 하다 →
> 해요 (not *하아요). Because the same -어/아요 ending covers declarative, interrogative,
> imperative, and propositive alike, sentence type is disambiguated purely by context and
> intonation (rising for a question) — a genuine syncretism in the polite register that the
> deferential register's four distinct endings do not have.

**Mixed-register code-switching within a single interaction is normal, not marked usage.** Byon
notes Koreans frequently open an interaction (e.g. a first meeting) in the deferential register
and then switch to the polite register once acquainted — the polite ending's use "generates an
effect of making a dialogue sound less formal, even in formal conversational contexts." This is a
directly relevant finding for slang/register synthesis: register in Korean is not a single fixed
choice per conversation but a live, shiftable social signal within one exchange.

### Unit 6 — The subject case particle 이/가 (p. 39–46)

Korean particles split into **case particles** (indicate syntactic role: 이/가 subject, 을/를
object, etc.) and **special particles** (add meaning like topic-marking or emphasis, e.g. 은/는,
만, 도 — Units 7 and 15). Particles can be omitted in colloquial speech when context disambiguates
role (never in formal writing), and because case particles carry the syntactic-role information
that English relies on word order for, Korean word order can be freely scrambled without changing
meaning.

**이/가** is a two-form particle: 이 after a consonant-final noun, 가 after a vowel-final noun
(mnemonic: opposite pattern from English a/an, which conditions on the *following* word's onset
rather than the marked noun's own coda). Beyond marking grammatical subjects, 이/가 also marks the
non-subject argument of a negated sentence (사라는 한국 사람이 아니에요 "As for Sara, she is not
Korean" — 한국사람, not 사라, bears 이, yet is not the sentence's subject) and permits
**double-subject constructions** (친구가 세 명이 왔다 "three friends came," 토마스가 손이 크다
"Thomas's hands are big" — a possessor-possession relationship expressed as two 이/가-marked
nouns, not literally two subjects).

### Unit 7 — The special particle 은/는 (p. 47–54)

은/는 is a **topic particle**, not a case particle — it does not indicate syntactic role, only
that the marked noun is the sentence's topic (은 after consonant-final nouns, 는 after
vowel-final). Korean sentences are canonically **topic-comment** structures. 은/는 has four core
functions: (1) marking the topic of a topic-comment sentence, with the topic droppable in
subsequent sentences about the same referent; (2) **compare-and-contrast** when used on two
parallel sentences (저스틴은 캐나다 사람이에요. 그렇지만 치에꼬는 일본 사람이에요. "As for Justin,
he's Canadian. However, as for Chieko, she's Japanese."); (3) **topic-switching**, used when a
speaker moves from one topic to another mid-conversation (e.g. a shopper asking sequential prices:
이 바지 얼마예요? → 그럼, 이 치마는 얼마예요? "then, as for this skirt, how much is it?"); (4)
appearing on any sentence-initial element to make it the topic, with the least-known/most-topical
information at the front and the most important information (predicates) at the end.

**Interplay between 이/가 and 은/는 in question-answer pairs.** A question word (누구, 무엇, etc.)
introducing brand-new information is marked with 이/가 (전공이 뭐예요? "what is your major?"), but
once that referent becomes the established topic, the answer marks it with 은/는 (제 전공은
한국어예요 "as for my major, it's Korean") — a live discourse-status distinction, not free
variation. Interrogative words themselves (누구, 무엇, 언제, 어느) are grammatical only with 이/가,
never with 은/는 (누가 아니라 *누구는).

### Unit 8 — Pronouns (p. 55–64)

Korean pronoun usage is far more restricted than English's — contextually recoverable subjects/
objects (including pronouns) are routinely omitted. **First-person pronouns** have a plain/humble
split: 나(내)/우리 (plain) vs. 저(제)/저희 (humble); the humble register is the safe default toward
unfamiliar adults and typically collocates with other honorific elements (deferential endings, the
-(으)시 suffix, euphemistic vocabulary). 저희/우리 also serve as a **collectivistic possessive**
even for individually-owned things tied to a group (one's family, school, household) — Byon notes
both 저희(우리) 형이... and 제(내) 형이... are grammatical, but the group-inclusive form is
preferred.

**Second-person pronouns** (plain 너/네/너희; polite 당신/당신의/당신들) have a critically narrower
scope than English "you": 너 is restricted to children, childhood friends, younger siblings, and
one's own children; 당신 is mostly restricted to spousal address and sounds confrontational
otherwise. **There is no general-purpose Korean second-person pronoun for an adult equal or
senior** — the socially safe strategies are (a) using an **address term** keyed to the addressee's
title/rank/relationship (e.g. 과장님 "Section Chief" + honorific title 님, from a junior colleague;
김 과장 "Section Chief Kim," last name + title, from a boss; 김 선배 "Senior Kim," from a junior
alumnus of the same school; 김영수씨, full name + neutral title 씨, between adult acquaintances of
similar status) or (b) using no pronoun at all and instead attention-getting phrases like 여기요
"here" or 실례합니다 "excuse me" in service settings.

**Korean has no true third-person pronoun** — demonstrative (그 "that") + noun (사람 "person," 분
"esteemed person," 남자/여자 "man/woman") substitutes, or a kinship term is extended to a
non-kin referent (e.g. addressing/referring to a friend's mother as 어머니, or an elderly stranger
as 할아버지/할머니).

**Kinship terms are highly stratified**, marking the referent's gender, the speaker's own gender,
relative age, and marital status all simultaneously (see the Unit 8 vocabulary table's two groups:
Group 1 splits by the speaker's own gender for spouse/sibling terms; Group 2 is used identically
by both genders). Kinship extension to non-kin (addressing a stranger as 할머니/할아버지, or a
friend's parent as 어머니/아버지) is described as arising from Korean's "collectivistic and
hierarchical values."

**Indefinite pronouns are homophonous with question words**, disambiguated purely by intonation:
a rising-intonation 누가 와요? is the question "who is coming?"; the identical string with falling
intonation, 누가 와요, means "someone is coming."

### Unit 9 — Numbers, ordinals, and plural marker 들 (p. 65–72)

Korean has **two parallel, fully-productive number systems**: Sino-Korean (borrowed from Chinese,
regular/decimal, used for all numbers ≥100, dates, money, phone numbers, and math) and native
Korean (irregular multiples-of-ten forms — 스물 "20," 서른 "30," etc. — with no word for zero, used
mainly for counting small quantities of objects with a counter, and for telling the hour). Five
native numbers (하나/한 "1," 둘/두 "2," 셋/세 "3," 넷/네 "4," 스물/스무 "20") have a **distinct
modified form used directly before a counter** (학생 한 명 "one student," not *학생 하나 명).
Ordinals differ by system too: Sino-Korean ordinals prefix 제- (제 일 "the first"); native
ordinals suffix -번째 (다섯 번째 "the fifth"), with one irregularity — "the first" is 첫 번째, not
the expected *한 번째.

**The plural marker 들** is optional, not obligatory — Korean nouns carry no inherent grammatical
number, so 학생이 와요 is ambiguous between "a student comes" and "students come"; 들 is added only
to *emphasize* plurality (학생들이 와요 "students [specifically, plural] come"), and can even
attach to an already-plural pronoun purely for emphasis (우리들 "we," redundantly pluralizing 우리
"we").

### Unit 10 — Counters, question word 몇, and time expressions (p. 73–80)

Counters classify nouns by semantic type for counting purposes (noun + number + counter, e.g.
학생 다섯 명 "five students"); most take native-Korean numbers below 20 and either system above
20. 몇 "how many" cannot stand alone and must always precede a counter (몇 명? "how many people?").
**Telling time mixes both number systems within a single expression**: hours use native-Korean
numbers + 시 counter, minutes use Sino-Korean numbers + 분 counter (e.g. 두 시 십오 분 "2:15" —
native 두 for the hour, Sino 십오 for the minutes) — a genuinely mixed-system compound within one
grammatical unit, not a free choice. Counting days, months, and years each have their own
regular/irregular-form conventions (native-Korean day-counting is irregular up to 20, e.g. 하루
"one day," 이틀 "two days," then regularizes; June and October are lexically irregular month names,
유월/시월 rather than the expected 육월/시월). Full dates are read largest-unit-first (year → month
→ day → time), mirroring the general-to-specific ordering principle from Unit 2.

### Unit 11 — The copula 이다/아니다 and the verb of existence and location 있다/없다 (p. 81–88)

Korean splits what English collapses into "be" into two distinct predicates: **이다/아니다**
(equational "X is Y" / negation "X is not Y") and **있다/없다** (existential/locative "there
is/exists" / "there is not," also used for possession "have/not have"). The copula's polite form
is irregular-looking but rule-governed: 이다 stem 이 + polite ending → 이에요 after a consonant-
final noun (선생님이에요 "is a teacher"), or contracts to 예요 after a vowel-final noun (의사예요
"is a doctor"). Negation of an equational sentence keeps the subject-marking pattern: the negated
noun itself is marked with 이/가 before 아니에요 (니콜은 한국사람이 아니에요 "As for Nicole, she is
not Korean").

있다/없다 requires a **locative particle 에** on the location noun (존이 런던에 있어요 "John is in
London"). Ten postpositional location nouns (위/아래/밑/뒤/앞/안/밖/옆/오른쪽/왼쪽) can specify a
more precise location and, unlike English prepositions, **follow** the object noun rather than
preceding it, and are themselves ordinary nouns taking 에 (책상 위에 "on [top of] the table," lit.
"table-above-at"). **있다 and 이다 are not interchangeable for location**: 서울이 한국에 있어요
"Seoul is in (exists in) Korea" (correct) vs. 서울이 한국이에요 "Seoul is Korea" (wrong — asserts
identity, not location). 있다/없다's other core meaning is **possession** ("have/not have"), where
KFL learners (per Byon) commonly mis-mark the possessed thing with the object particle 을/를 by
transfer from English "have + object," when Korean instead marks it with the subject particle
이/가 (피터는 애플 컴퓨터가 있어요 "Peter has an Apple computer," lit. "as for Peter, an Apple
computer exists").

### Unit 12 — Case particles 1: 을/를 and (으)로 (p. 89–97)

**을/를** (two-form: 을 after consonant, 를 after vowel) marks the direct object, but can
exceptionally also mark the goal of an intransitive motion verb (가다 "go," 오다 "come") in place
of the expected locative 에 — 학교에 가요 and 학교를 가요 both mean "goes to school," a genuine
particle-choice free variation on intransitive motion goals specifically.

**The productive light-verb construction Noun + 을/를 + 해요.** 하다 "do" combines with an
action-denoting noun to form a de facto verb (사인을 해요 "signs," lit. "does signing"; 청소를 해요
"cleans," lit. "does cleaning"). The object particle can be dropped, collapsing the phrase into
what reads as a single compound verb with no meaning difference (사인을 해요 = 사인해요). This
construction can even accommodate two grammatical objects at once when the base noun already has
one (계약서를 사인을 해요 "signs the contract," with both 계약서를 and 사인을 marked, or either
particle optionally dropped) — a genuinely productive, "any semantically-fitting noun + 하다"
derivational pattern, distinct from ordinary lexical verbs, and likely a fertile site for slang
formation (new nonce action-nouns can be verbed via 하다 at will).

**(으)로** (으로 after consonant, 로 after vowel or ㄹ) is a one-form-pair particle covering five
distinct meanings: (1) **means/instrument** ("by/with," 펜으로 사인하세요 "sign with a pen"); (2)
**direction** (more general than the specific-destination 에 — 왼쪽으로 가세요 "go toward the left"
vs. 학교에 가세요 "go to [the] school" specifically); (3) **selection among options** (스몰로
주세요 "give me the small [one]," implying other sizes exist); (4) **change of state** (result of
a transformation — 피터가 회장으로 선출됐다 "Peter was elected as chairman," 물이 얼음으로 변했다
"water changed into ice"); (5) **reason** (차 사고로 다리를 다쳤어요 "I got hurt in the leg due to
the car accident"). One particle covering five distinct semantic roles is itself a notable
polysemy pattern for a mechanics-analysis pass to track.

### Unit 13 — Case particles 2: 의, 에, 와/과, (이)랑, and 하고 (p. 99–107)

**의** marks possessor+possession (제임스의 방 "James's room") — a one-form particle regardless of
the preceding noun's final sound. Unlike English 's, Korean disallows a possessor-final
construction without an overt possessed noun; the bound noun 것(거) fills that role (스티브의 것이
에요 "it's Steve's [thing]," not *그것은 스티브의예요). The first-person possessives 내/제 are
lexicalized contractions of pronoun+의 (나+의→내, 저+의→제). In colloquial/informal registers, 의
is frequently dropped entirely (수잔 가방 for 수잔의 가방), leaving a bare noun-noun juxtaposition —
this is the same construction type independently used for productive noun-noun compounding
(Unit 3), so possessive-marker omission and true compounding are formally indistinguishable at the
surface.

**에** is a one-form particle covering four meanings: (1) static location ("in/at/on" — 집에
있어요 "is at home"); (2) the goal of an action when that goal is inanimate (은행에 돈을
부쳐주세요 "please send money to the bank" — contrasts with animate goals, which instead require
한테/에게, Unit 14); (3) time nouns ("at/in/on" — but *not* with certain deictic time nouns like
어제/오늘/내일 "yesterday/today/tomorrow," which never take 에); (4) a distributive "per" sense
(하루에 몇 시간...? "how many hours per day...?").

**와/과, (이)랑, 하고** are three near-synonymous "and/with" conjunctive particles differing only in
register: 와/과 (two-form, 와 after vowel/과 after consonant) is the most formal/written-register
choice; (이)랑 (two-form) is the most informal/colloquial; 하고 (one-form, works after any final
sound) sits in between — "less informal than (이)랑 but more formal than 와/과." All three can drop
an omittable subject and shift to meaning "with" rather than "and" (토마스와 커피를 마셔요 "[Susan]
drinks coffee with Thomas"). This is a clean three-way formality gradient across otherwise
near-synonymous particles — directly relevant register data for the slang-mechanics phase.

### Unit 14 — Case particles 3: 에서, 에게, 한테, 께, 에게서, 한테서 (p. 109–115)

**에서** (one-form) covers (1) the dynamic location where an activity-type verb's action takes
place (학교에서 만나요 "meets at school" — required, not optional, whenever the verb denotes an
activity like meeting/studying/working, as opposed to static 에 with existential/locative verbs)
and (2) the inanimate source of an action ("from" — 보스턴에서 뉴욕까지 가요 "goes from Boston to
New York").

**한테/에게/께 mark the animate indirect object** ("to," used only for persons/animals — inanimate
goals instead take 에, per Unit 13). 한테 is the colloquial default; 에게 is used in more formal/
written registers; **께 is a distinct, dedicated honorific indirect-object particle**, substituted
for 한테/에게 specifically when the indirect object is an esteemed person (a boss, teacher, parent)
— and Byon notes 께's use should be **collocated with other honorific elements**, illustrated by
께 pairing with the suppletive honorific verb 드리다 "give (honorific)" rather than plain 주다
(선생님께 가방을 드렸어요 "[I] gave a bag to the teacher," honorific register throughout, vs. plain
집에 가방을 줬어요). This is a second clean case (after Unit 8's 저/저희 and Unit 4/5's speech-level
endings) of Korean marking honorific register redundantly across multiple grammatical
sub-systems simultaneously (particle choice + verb suppletion) rather than via one single "polite
switch" — a structurally important finding for any conlang register design drawing on Korean as a
model, since it means honorific marking is *distributed* across the sentence, not localized to one
morpheme.

**한테서/에게서** mark an animate source ("from a person"), mirroring the colloquial/formal split
of 한테/에게 (한테서 colloquial, 에게서 formal): 토니한테서 책을 받았어요 "received the book from
Tony" (colloquial) vs. 존에게서 가방을 선물로 받았습니다 "received the bag as a present from John"
(formal, also co-occurring with the deferential ending -습니다 — register agreement across
particle and verb ending again).

### Unit 15 — Special particles 1: 도 and 만 (p. 117–120, into exercises)

This unit generalizes the case-vs.-special-particle distinction from Units 6–7: a **case particle**
marks only syntactic role; a **special particle** adds meaning (only/also/even) *or* marks
topic-hood, and — critically — **special particles can appear in three distinct structural
positions**: (1) in place of a case particle entirely (수잔이 → 수잔은/만/도, replacing 이/가); (2)
**stacked after** an existing case particle that isn't a "core" one, such as 에, 에서, 으로
(도서관에서 → 도서관에서도/서만); (3) after an adverb (빨리 "fast" → 빨리만, 빨리도). This
three-position flexibility means **no fixed slot exists where "the" particle always goes** — a
learner (or, for this project's purposes, a slang-mechanics analysis) cannot memorize one
position per particle; the position is a function of which other particle (if any) is already
present, layering compositionally rather than substitutively for non-core particles.

**만** ("only/just") replaces 이/가 or 을/를, or stacks onto 에/에서/adverbs, always narrowing to a
single exhaustive-exclusive referent (나오꼬만 커피를 마셔요 "only Naoko drinks coffee" vs. 나오꼬가
커피만 마셔요 "Naoko drinks only coffee" — same two lexical items, particle placement alone flips
which noun is being exclusively selected).

**도** ("also/too/even") likewise replaces 이/가 or 을/를, or stacks onto existing particles/
adverbs, and additionally: functions as a list-continuation device across separate sentences (집에
파스타가 있어요. 그리고 와인도 있어요 "there's pasta at home. And there's wine too"); carries an
emphatic "even" reading (큰 집이 있어요. 그리고 빌딩도 있어요 "they have a big house. And they even
have a building"); and in a negative sentence is obligatorily glossed "either" rather than "also"
(차가 없어요. 자전거도 없어요 "I don't have a car. I don't have a bicycle either").

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — no bulk reproduction of vocabulary boxes, dialogue
blocks, or explanatory prose beyond short illustrative phrases. See `../../00_Reference_Extraction_Spec.md`.
