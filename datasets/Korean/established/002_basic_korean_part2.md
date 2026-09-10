# Korean — Established Vocabulary/Grammar: Units 16–25 (second half)

**Source:** Andrew Sangpil Byon, *Basic Korean: A Grammar and Workbook* (Routledge, 2009), PDF
pages 134–257 of 257 (printed pages 125–206, i.e. Units 16 through 25 plus the book's own "Key to
Exercises" and "Index" back matter). A sibling subagent covers PDF pages 1–130 (through the tail of
Unit 15).

**Boundary decision.** The dispatch's nominal split point (PDF page 131) falls mid-exercise inside
Unit 15 (exercises 15.3–15.5, printed p. 122–124) — pure fill-in-the-blank drills reusing the
Unit 15 vocabulary list already printed on p. 119–121 (presumably captured by the sibling chunk),
introducing no new vocabulary or grammar of their own. Rather than split a unit's exercise block
across two files, this file starts at the next clean boundary: **PDF page 134 / printed page 125**,
where **Unit 16 ("Special particles 2")** begins. Pages 131–133 (the tail of Unit 15's exercises)
are therefore intentionally not re-extracted here — they carry nothing beyond what the coverage
rule already directs a subagent to skip (see `00_Reference_Extraction_Spec.md`, "repeated drill
exercises... that don't introduce new vocabulary or grammar").

**Scope of what follows.** This file covers **Units 16–25** in full — every grammar point and
every distinct vocabulary item, per the spec's comprehensive-but-not-exhaustive rule. After Unit 25
(PDF page ~226 / printed page 206), the book's own back matter — a **"Key to Exercises"** answer
key (PDF p. 227–243, printed p. 207–244) and an **Index** (PDF p. 244–246) — is **not** extracted:
the answer key is pure drill-solution material reusing vocabulary already captured in each unit's
own "key vocabulary for exercises" list, and the Index is a page-locator list for the *English*
edition's own pagination, not source content in the sense this project extracts. The remaining PDF
pages (247–257) are publisher advertisements for other Routledge titles (*Colloquial Korean*,
*Korean: An Essential Grammar*) and contain no Basic Korean content at all.

**PDF text-layer decoding — font-substitution cipher (important for any other subagent touching
this same PDF file).** This PDF *does* have a genuine embedded text layer (`pdftotext` extracts
real, non-garbled text), but the embedded font remaps Hangul (and the CJK-range companion
punctuation the typesetter used for curly quotes, etc.) through a **non-standard, fixed
Unicode-codepoint offset** rather than a normal cmap: every character `pdftotext` extracts in the
codepoint range `[U+0080, U+FFFF]` decodes to its intended character by computing
`real_codepoint = (extracted_codepoint + 0x8DAA) mod 0x10000`. This was verified by decoding known
words in context (e.g. the extracted "앤지는" for a name glossed "Angie," extracted "이나" for the
particle glossed "ina" in the chapter's own romanization) and cross-checking dozens of resulting
words against the book's own English glosses on the same page — all resolved to well-formed,
contextually correct Hangul. A handful of **standalone consonant/vowel jamo letters** used inline
in the irregular-verb discussion (e.g. "ㄹ" in "ㄹ-irregular") fall outside this offset's correct
range and were instead identified individually from grammatical context (confirmed by the
paradigm examples given alongside each one) rather than via the offset formula — these are
resolved correctly in the prose below, but a future subagent applying only the raw offset formula
mechanically to this same PDF should double check any standalone jamo letter it encounters rather
than trust the arithmetic blindly. ASCII text (including the English glosses and romanizations) is
untouched by this cipher. This is a **different failure mode** from the previously-documented
Cyrillic font-substitution cipher (see `00_Reference_Extraction_Spec.md`'s PDF-gotchas section) —
same general phenomenon (a fixed, decodable glyph substitution baked into a subset font), different
script and different concrete offset — and is being promoted there as a second confirmed instance
worth checking for on any future Korean PDF that "has a text layer" but extracts as CJK-ideograph
soup instead of Hangul.

**Register/honorific findings (flagged per the dispatch's explicit request).** Unit 25 is this
chunk's single richest register source: it introduces the **subject-honorific suffix -(으)시** as a
grammatically distinct, independent system from **speech-level choice** (deferential/polite/
intimate — introduced piecemeal across this range via example sentences, e.g. Unit 18's fourfold
declarative/interrogative/imperative/propositive negation paradigm at the deferential level, and
Unit 25's own intimate-level honorific example). The book is explicit that speech level tracks the
*addressee* while the honorific suffix tracks the sentence's *subject* (which may or may not be the
addressee) — these two axes are independent and can combine freely, except that **a speaker never
honors themselves** (a rule stated outright, with a minimal-pair example). A closed set of
suppletive honorific verbs (잡수시다/주무시다/계시다) already lexicalize the suffix. See the Unit 25
grammar-point entry below for the full writeup and example.

**Morpheme-breakdown discipline.** Korean's agglutinative typology (see
`00_Word_Concept_and_Morphological_Typology_Guide.md` and this language's own
`00_Extraction_Checklist.md`) means several of this range's "endings" are themselves stacks of 2–4
separable morphemes with individually traceable meanings (the double past marker 았었/었었; the
three-part -(으)ㄹ 거예요; the honorific+speech-level stack -시+-ㅂ니다). These get explicit morpheme
breakdowns in the Grammar points section below rather than being treated as atomic "endings" — this
matters directly for later `morphological_play` analysis (per the typology guide, ordinary
agglutinative productivity must be distinguished from anything genuinely slang-specific).

---

## Vocabulary

Each subsection lists the **key vocabulary for [Unit N]'s exercises** as printed in the book,
in the book's own alphabetical order, at the vocabulary's first appearance in this file's unit
range — a term repeated in a later unit's own list is not re-tabulated but is cross-referenced in
that first row's Notes column ("also reused in Unit(s) ..."). Unit 19's seven irregular-verb
paradigm tables (its actual grammar content, not just its own "key vocabulary" list) are also
tabulated as their own subsections, since they introduce dozens of distinct verbs/adjectives used
nowhere else in the book. Unit 22's closed-class prenouns and Unit 23's four adverb-type word lists
are likewise tabulated as their own subsections. A handful of grammar-point particles that never
appear in any unit's own "key vocabulary" list (이나/나, 부터, 까지) are added under Unit 16, where
they are introduced.

### Unit 16 — Special particles 2 (key vocabulary)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 이나 / 나 | "or something (like that)" / "or" / "as many as" / "about" (special particle, two-form: 이나 after consonant, 나 after vowel) | particle | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 grammar-point particle (not part of the key-vocabulary list). Four distinct construals depending on context — see Grammar points. |
| 부터 | "from" (marks a starting temporal point) | particle | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 grammar-point particle. Contrasts with the case particle 에 (simple "at"). |
| 까지 | "to/until/as far as/even" (marks an ending point, or, with a non-time/non-place noun, "including (even)") | particle | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 grammar-point particle. Often paired with 부터 ("from... to...") or 에서 ("from [place] to [place]"). |
| 가방 | bag | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary; also reused in Unit(s) 19. |
| 가족 | family | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary. |
| 강 | river | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary. |
| 경찰서 | police station | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary. |
| 고장 | out of order | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary. |
| 공항 | airport | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary; also reused in Unit(s) 21. |
| 교회 | church | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary. |
| 국수 | noodles | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary. |
| 기차역 | train station | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary. |
| 꽃 | flower | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary. |
| 날씨 | weather | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary; also reused in Unit(s) 21, 25. |
| 남자 | man | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary. |
| 덥다 | to be hot (weather) | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary; also reused in Unit(s) 19(ㅂ-irr), 21, 25. |
| 드라마 | drama | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary. |
| 딸 | daughter | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary. |
| 라면 | ramen (instant noodle) | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary. |
| 마시다 | to drink | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary; also reused in Unit(s) 18, 20, 21. |
| 만나다 | to meet | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary; also reused in Unit(s) 18, 20, 22, 24. |
| 맥주 | beer | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary. |
| 물 | water | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary; also reused in Unit(s) 18, 19, 20, 24. |
| 바꾸다 | to change | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary. |
| 밤 | night | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary; also reused in Unit(s) 17, 24. |
| 백화점 | department store | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary; also reused in Unit(s) 21, 22. |
| 병원 | hospital | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary; also reused in Unit(s) 18, 20. |
| 비누 | soap | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary. |
| 빨래 | laundry | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary. |
| 빵 | bread | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary. |
| 사다 | to buy | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary; also reused in Unit(s) 18, 20, 21, 24. |
| 산 | mountain | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary; also reused in Unit(s) 19. |
| 샴푸 | shampoo | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary. |
| 설거지 | dishwashing | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary. |
| 소파 | sofa | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary. |
| 슈퍼마켓 | supermarket | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary. |
| 숟가락 | spoon | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary. |
| 신발 | shoes | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary. |
| 아들 | son | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary. |
| 아침 | morning | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary; also reused in Unit(s) 17, 21, 24. |
| 약국 | pharmacy | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary. |
| 양복 | suit | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary; also reused in Unit(s) 17. |
| 여자 | woman | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary. |
| 연필 | pencil | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary. |
| 영화 | movie | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary; also reused in Unit(s) 22, 24, 25. |
| 오다 | to come | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary; also reused in Unit(s) 17, 21, 22. |
| 오전 | a.m. | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary; also reused in Unit(s) 24. |
| 오후 | p.m. | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary; also reused in Unit(s) 17, 24. |
| 우체국 | post office | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary; also reused in Unit(s) 20. |
| 운전하다 | to drive | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary; also reused in Unit(s) 20. |
| 은행 | bank | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary. |
| 음식점 | restaurant | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary. |
| 의자 | chair | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary. |
| 저녁 | evening/dinner | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary; also reused in Unit(s) 18, 25. |
| 젓가락 | chopsticks | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary. |
| 쥬스 | juice | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary. |
| 지갑 | wallet | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary. |
| 집 | house | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary; also reused in Unit(s) 17, 20, 21, 22, 24, 25. |
| 친구 | friend | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary; also reused in Unit(s) 17, 19, 20, 24, 25. |
| 카드 | card | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary. |
| 커피숍 | coffee shop | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary; also reused in Unit(s) 22. |
| 케이크 | cake | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary. |
| 펜 | pen | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary. |
| 포도주 | wine | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary; also reused in Unit(s) 17. |
| 학교 | school | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary; also reused in Unit(s) 24. |
| 할아버지 | grandfather | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary. |
| 할머니 | grandmother | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary; also reused in Unit(s) 20. |
| 호텔 | hotel | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 16 key vocabulary. |

### Unit 17 — Past tense and double past tense (key vocabulary)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가게 | store | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 17 key vocabulary. |
| 나가다 | to go out | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 17 key vocabulary; also reused in Unit(s) 20. |
| 냉장고 | refrigerator | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 17 key vocabulary. |
| 닫다 | to close | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 17 key vocabulary; also reused in Unit(s) 19(ㄷ-reg), 24. |
| 도서관 | library | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 17 key vocabulary; also reused in Unit(s) 18, 23, 24. |
| 뜨다 | to float | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 17 key vocabulary; also reused in Unit(s) 19(으-irr). |
| 마치다 | to finish | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 17 key vocabulary; also reused in Unit(s) 25. |
| 매다 | to hang/to tie | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 17 key vocabulary; also reused in Unit(s) 18. |
| 모자 | hat | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 17 key vocabulary; also reused in Unit(s) 19. |
| 배우다 | to learn | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 17 key vocabulary; also reused in Unit(s) 20, 21, 23. |
| 버리다 | to throw away | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 17 key vocabulary; also reused in Unit(s) 18. |
| 비싸다 | to be expensive | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 17 key vocabulary; also reused in Unit(s) 18, 21, 25. |
| 빌리다 | to borrow | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 17 key vocabulary; also reused in Unit(s) 18, 20. |
| 서점 | bookstore | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 17 key vocabulary. |
| 손 | hand | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 17 key vocabulary; also reused in Unit(s) 20, 24. |
| 수박 | watermelon | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 17 key vocabulary. |
| 식탁 | dining table | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 17 key vocabulary. |
| 쓰다 | to write/to use | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 17 key vocabulary; also reused in Unit(s) 18, 19(으-irr). |
| 쓰레기 | garbage | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 17 key vocabulary; also reused in Unit(s) 18. |
| 씻다 | to wash | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 17 key vocabulary; also reused in Unit(s) 18, 19(ㅅ-reg), 20, 24. |
| 야구 | baseball | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 17 key vocabulary; also reused in Unit(s) 22. |
| 약사 | pharmacist | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 17 key vocabulary; also reused in Unit(s) 21. |
| 옷 | clothes | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 17 key vocabulary; also reused in Unit(s) 21. |
| 요리 | cooking | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 17 key vocabulary. |
| 일 | work | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 17 key vocabulary; also reused in Unit(s) 20, 21, 25. |
| 입다 | to wear (clothes) | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 17 key vocabulary; also reused in Unit(s) 19(ㅂ-reg), 20. |
| 자전거 | bike | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 17 key vocabulary. |
| 좋다 | to be good | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 17 key vocabulary; also reused in Unit(s) 19(ㅎ-reg), 25. |
| 좋아하다 | to like | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 17 key vocabulary; also reused in Unit(s) 21, 22. |
| 타다 | to ride | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 17 key vocabulary; also reused in Unit(s) 18, 20, 21, 23, 25. |
| 팔다 | to sell | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 17 key vocabulary; also reused in Unit(s) 18, 19(ㄹ-irr), 24, 25. |
| 해 | the sun | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 17 key vocabulary. |
| 화장실 | restroom | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 17 key vocabulary. |

### Unit 18 — Negation (key vocabulary)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가다 | to go | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary; also reused in Unit(s) 20, 21, 22, 24. |
| 구두 | shoes | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary. |
| 건너다 | to cross/to go over | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary; also reused in Unit(s) 25. |
| 길 | road | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary; also reused in Unit(s) 19, 23, 25. |
| 김치 | kimchi | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary. |
| 낮잠 | nap | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary. |
| 내일 | tomorrow | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary; also reused in Unit(s) 23(time adv), 23, 25. |
| 넣다 | to insert | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary; also reused in Unit(s) 19(ㅎ-reg). |
| 넥타이 | necktie | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary. |
| 노래 | song | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary; also reused in Unit(s) 19, 20, 24. |
| 늦게 | lately | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary. |
| 담배 | cigarettes | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary; also reused in Unit(s) 25. |
| 동전 | coin | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary. |
| 말하다 | to speak | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary; also reused in Unit(s) 20. |
| 먹다 | to eat | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary; also reused in Unit(s) 23, 24, 25. |
| 문 | door | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary; also reused in Unit(s) 24, 25. |
| 바쁘다 | to be busy | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary; also reused in Unit(s) 19(으-irr), 21. |
| 방 | room | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary; also reused in Unit(s) 21, 25. |
| 보내다 | to send | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary. |
| 부르다 | to call out/to sing | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary; also reused in Unit(s) 19(르-irr), 20, 24. |
| 비행기 | airplane | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary. |
| 술 | liquor | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary. |
| 쉬다 | to rest | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary; also reused in Unit(s) 20. |
| 식당 | cafeteria | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary. |
| 신다 | to wear (shoes) | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary. |
| 아버지 | father | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary; also reused in Unit(s) 20, 24. |
| 안경 | eye-glasses | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary. |
| 약 | medicine | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary. |
| 얼굴 | face | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary; also reused in Unit(s) 19, 20. |
| 열다 | to open | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary; also reused in Unit(s) 19(ㄹ-irr), 24. |
| 야채 | vegetables | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary. |
| 오늘 | today | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary; also reused in Unit(s) 21, 23. |
| 요가 | yoga | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary. |
| 운동 | sport/exercise | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary; also reused in Unit(s) 20, 22, 25. |
| 운전 | driving | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary. |
| 음식 | food | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary; also reused in Unit(s) 20, 21, 22, 23, 25. |
| 일어나다 | to get up | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary; also reused in Unit(s) 24. |
| 전화하다 | to make a phone call | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary; also reused in Unit(s) 21, 24, 25. |
| 주말 | weekend | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary. |
| 짜다 | to be salty | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary. |
| 청소하다 | to clean up | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary. |
| 춥다 | to be cold | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary; also reused in Unit(s) 19(ㅂ-irr), 21, 25. |
| 크게 | aloud | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary. |
| 크다 | to be big | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary; also reused in Unit(s) 19(으-irr). |
| 편지 | letter | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary; also reused in Unit(s) 20, 24. |
| 피우다 | to smoke | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 18 key vocabulary. |

### Unit 19 — Irregular verbs (key vocabulary)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 강아지 | puppy | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 key vocabulary. |
| 건물 | building | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 key vocabulary. |
| 고기 | meat | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 key vocabulary. |
| 공 | ball | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 key vocabulary. |
| 공책 | notebook | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 key vocabulary. |
| 기분 | feeling/mood | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 key vocabulary. |
| 껌 | gum | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 key vocabulary. |
| 꽃병 | flower vase | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 key vocabulary; also reused in Unit(s) 24. |
| 돈 | money | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 key vocabulary; also reused in Unit(s) 20, 24. |
| 목 | throat | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 key vocabulary. |
| 바람 | wind | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 key vocabulary; also reused in Unit(s) 25. |
| 배 | stomach/ship | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 key vocabulary. |
| 색 | color | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 key vocabulary; also reused in Unit(s) 22, 24. |
| 선생님 | teacher | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 key vocabulary; also reused in Unit(s) 25. |
| 어머니 | mother | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 key vocabulary. |
| 이야기 | story | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 key vocabulary; also reused in Unit(s) 24. |
| 자동차 | car | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 key vocabulary; also reused in Unit(s) 20. |
| 줄 | line | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 key vocabulary. |
| 짐 | load/burden | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 key vocabulary. |
| 책 | book | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 key vocabulary; also reused in Unit(s) 20. |
| 하늘 | sky | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 key vocabulary. |

### Unit 19 — ㄷ-irregular verbs (paradigm)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 묻다 | to ask | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㄷ-irregular) key vocabulary. |
| 걷다 | to walk | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㄷ-irregular) key vocabulary. |
| 깨닫다 | to realize | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㄷ-irregular) key vocabulary. |
| 듣다 | to listen | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㄷ-irregular) key vocabulary; also reused in Unit(s) 20, 21, 22. |
| 싣다 | to load | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㄷ-irregular) key vocabulary. |

### Unit 19 — regular ㄷ-final verbs (contrast set)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 받다 | to receive | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (regular ㄷ-final, contrast set) key vocabulary; also reused in Unit(s) 20. |
| 믿다 | to believe | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (regular ㄷ-final, contrast set) key vocabulary; also reused in Unit(s) 20, 21, 24, 25. |
| 얻다 | to gain | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (regular ㄷ-final, contrast set) key vocabulary. |

### Unit 19 — ㅂ-irregular verbs/adjectives (paradigm)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 굽다 | to roast | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㅂ-irregular) key vocabulary. |
| 눕다 | to lie down | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㅂ-irregular) key vocabulary. |
| 돕다 | to help | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㅂ-irregular) key vocabulary; also reused in Unit(s) 20, 21, 24. |
| 줍다 | to pick up | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㅂ-irregular) key vocabulary. |
| 가볍다 | to be light | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㅂ-irregular) key vocabulary. |
| 고맙다 | to be thankful | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㅂ-irregular) key vocabulary. |
| 곱다 | to be pretty | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㅂ-irregular) key vocabulary. |
| 그립다 | to be longed-for | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㅂ-irregular) key vocabulary. |
| 더럽다 | to be dirty | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㅂ-irregular) key vocabulary. |
| 두렵다 | to be scary | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㅂ-irregular) key vocabulary. |
| 뜨겁다 | to be heated | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㅂ-irregular) key vocabulary. |
| 맵다 | to be spicy | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㅂ-irregular) key vocabulary; also reused in Unit(s) 23. |
| 무겁다 | to be heavy | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㅂ-irregular) key vocabulary. |
| 무섭다 | to be fearful | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㅂ-irregular) key vocabulary. |
| 밉다 | to be hateful | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㅂ-irregular) key vocabulary. |
| 사랑스럽다 | to be lovely | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㅂ-irregular) key vocabulary. |
| 쉽다 | to be easy | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㅂ-irregular) key vocabulary; also reused in Unit(s) 23, 25. |
| 싱겁다 | to be tasteless | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㅂ-irregular) key vocabulary. |
| 어둡다 | to be dark | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㅂ-irregular) key vocabulary. |
| 어렵다 | to be difficult | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㅂ-irregular) key vocabulary; also reused in Unit(s) 25. |
| 아름답다 | to be beautiful | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㅂ-irregular) key vocabulary; also reused in Unit(s) 23. |
| 어지럽다 | to be dizzy | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㅂ-irregular) key vocabulary. |
| 즐겁다 | to be delightful | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㅂ-irregular) key vocabulary. |
| 차갑다 | to be cold | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㅂ-irregular) key vocabulary. |

### Unit 19 — regular ㅂ-final verbs (contrast set)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 뽑다 | to extract | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (regular ㅂ-final, contrast set) key vocabulary. |
| 씹다 | to chew | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (regular ㅂ-final, contrast set) key vocabulary. |
| 업다 | to carry (on the back) | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (regular ㅂ-final, contrast set) key vocabulary. |
| 잡다 | to catch | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (regular ㅂ-final, contrast set) key vocabulary. |
| 접다 | to fold | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (regular ㅂ-final, contrast set) key vocabulary. |
| 좁다 | to be narrow | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (regular ㅂ-final, contrast set) key vocabulary; also reused in Unit(s) 25. |
| 집다 | to pick up | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (regular ㅂ-final, contrast set) key vocabulary. |

### Unit 19 — ㅅ-irregular verbs (paradigm)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 긋다 | to draw (a line) | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㅅ-irregular) key vocabulary. |
| 낫다 | to get better | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㅅ-irregular) key vocabulary. |
| 붓다 | to swell | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㅅ-irregular) key vocabulary. |
| 잇다 | to connect | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㅅ-irregular) key vocabulary. |
| 젓다 | to stir | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㅅ-irregular) key vocabulary. |
| 짓다 | to build | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㅅ-irregular) key vocabulary. |

### Unit 19 — regular ㅅ-final verbs (contrast set)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 벗다 | to take off | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (regular ㅅ-final, contrast set) key vocabulary; also reused in Unit(s) 20. |
| 빗다 | to comb | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (regular ㅅ-final, contrast set) key vocabulary. |
| 빼앗다 | to take (by force) | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (regular ㅅ-final, contrast set) key vocabulary. |
| 웃다 | to laugh | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (regular ㅅ-final, contrast set) key vocabulary. |

### Unit 19 — ㅎ-irregular adjectives (paradigm)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 까맣다 | to be black | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㅎ-irregular) key vocabulary. |
| 노랗다 | to be yellow | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㅎ-irregular) key vocabulary. |
| 빨갛다 | to be red | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㅎ-irregular) key vocabulary. |
| 파랗다 | to be blue | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㅎ-irregular) key vocabulary. |
| 하얗다 | to be white | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㅎ-irregular) key vocabulary. |
| 그렇다 | to be that way | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㅎ-irregular) key vocabulary. |
| 어떻다 | to be how | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㅎ-irregular) key vocabulary. |
| 이렇다 | to be this way | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㅎ-irregular) key vocabulary. |
| 저렇다 | to be that way | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㅎ-irregular) key vocabulary. |

### Unit 19 — regular ㅎ-final verbs/adjectives (contrast set)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 놓다 | to place | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (regular ㅎ-final, contrast set) key vocabulary. |

### Unit 19 — 르-irregular verbs/adjectives (paradigm)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가르다 | to divide | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (르-irregular) key vocabulary. |
| 고르다 | to choose | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (르-irregular) key vocabulary; also reused in Unit(s) 24. |
| 구르다 | to roll (over) | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (르-irregular) key vocabulary. |
| 기르다 | to foster | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (르-irregular) key vocabulary. |
| 나르다 | to carry | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (르-irregular) key vocabulary. |
| 누르다 | to press | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (르-irregular) key vocabulary. |
| 두르다 | to put around | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (르-irregular) key vocabulary. |
| 마르다 | to dry (up) | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (르-irregular) key vocabulary. |
| 모르다 | to not know | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (르-irregular) key vocabulary. |
| 바르다 | to paste | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (르-irregular) key vocabulary. |
| 앞지르다 | to get ahead of | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (르-irregular) key vocabulary. |
| 어지르다 | to disarrange | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (르-irregular) key vocabulary. |
| 엎지르다 | to spill | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (르-irregular) key vocabulary. |
| 오르다 | to go up | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (르-irregular) key vocabulary. |
| 자르다 | to cut (off) | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (르-irregular) key vocabulary. |
| 찌르다 | to pierce | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (르-irregular) key vocabulary. |
| 흐르다 | to flow | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (르-irregular) key vocabulary. |
| 게으르다 | to be lazy | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (르-irregular) key vocabulary. |
| 다르다 | to be different | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (르-irregular) key vocabulary. |
| 배부르다 | to be full | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (르-irregular) key vocabulary. |
| 빠르다 | to be fast | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (르-irregular) key vocabulary. |
| 서투르다 | to be unskillful | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (르-irregular) key vocabulary. |

### Unit 19 — regular 르-final verbs (contrast set)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 다다르다 | to arrive at | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (regular 르-final, contrast set) key vocabulary. |
| 따르다 | to follow | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (regular 르-final, contrast set) key vocabulary; also reused in Unit(s) 19(으-irr). |
| 치르다 | to pay off | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (regular 르-final, contrast set) key vocabulary. |

### Unit 19 — ㄹ-irregular verbs/adjectives (paradigm)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 갈다 | to grind | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㄹ-irregular) key vocabulary. |
| 걸다 | to hang | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㄹ-irregular) key vocabulary. |
| 날다 | to fly | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㄹ-irregular) key vocabulary. |
| 놀다 | to play | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㄹ-irregular) key vocabulary; also reused in Unit(s) 20, 21. |
| 달다 | to hang (up) | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㄹ-irregular) key vocabulary. |
| 달다 | to be sweet | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㄹ-irregular) key vocabulary. Homograph of 달다 "to hang (up)" directly above — a distinct lexical item that happens to share the same stem shape and irregularity class. |
| 돌다 | to turn (around) | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㄹ-irregular) key vocabulary. |
| 떠들다 | to make a noise | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㄹ-irregular) key vocabulary. |
| 떨다 | to tremble | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㄹ-irregular) key vocabulary. |
| 만들다 | to make | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㄹ-irregular) key vocabulary; also reused in Unit(s) 20, 24. |
| 말다 | to roll up | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㄹ-irregular) key vocabulary. |
| 물다 | to bite (at) | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㄹ-irregular) key vocabulary. |
| 밀다 | to push | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㄹ-irregular) key vocabulary. |
| 벌다 | to earn | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㄹ-irregular) key vocabulary; also reused in Unit(s) 20. |
| 불다 | to blow (up) | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㄹ-irregular) key vocabulary; also reused in Unit(s) 25. |
| 빌다 | to beg | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㄹ-irregular) key vocabulary. |
| 살다 | to live | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㄹ-irregular) key vocabulary; also reused in Unit(s) 20, 21, 24. |
| 쓸다 | to sweep | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㄹ-irregular) key vocabulary. |
| 알다 | to know | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㄹ-irregular) key vocabulary. |
| 얼다 | to freeze | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㄹ-irregular) key vocabulary. |
| 울다 | to cry | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㄹ-irregular) key vocabulary. |
| 털다 | to shake off | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㄹ-irregular) key vocabulary. |
| 풀다 | to untie | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㄹ-irregular) key vocabulary. |
| 헐다 | to destroy | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㄹ-irregular) key vocabulary. |
| 흔들다 | to shake | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㄹ-irregular) key vocabulary. |
| 길다 | to be long | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㄹ-irregular) key vocabulary. |
| 가늘다 | to be thin | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㄹ-irregular) key vocabulary. |
| 멀다 | to be far | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㄹ-irregular) key vocabulary. |
| 질다 | to be watery | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (ㄹ-irregular) key vocabulary. |

### Unit 19 — 으-irregular verbs/adjectives (paradigm — no regular counterpart exists)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 끄다 | to put off (extinguish) | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (으-irregular) key vocabulary. |
| 담그다 | to soak (in) | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (으-irregular) key vocabulary. |
| 고프다 | to be hungry | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (으-irregular) key vocabulary. |
| 기쁘다 | to be happy | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (으-irregular) key vocabulary. |
| 나쁘다 | to be bad | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (으-irregular) key vocabulary. |
| 슬프다 | to be sad | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (으-irregular) key vocabulary. |
| 아프다 | to be sick | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (으-irregular) key vocabulary; also reused in Unit(s) 23. |
| 예쁘다 | to be pretty | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 19 (으-irregular) key vocabulary. |

### Unit 20 — Desire -고 싶다 and progressive -고 있다 (key vocabulary)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가르치다 | to teach | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 20 key vocabulary; also reused in Unit(s) 21, 25. |
| 기다리다 | to wait | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 20 key vocabulary; also reused in Unit(s) 22, 24, 25. |
| 교수님 | professor | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 20 key vocabulary; also reused in Unit(s) 22. |
| 끝내다 | to finish | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 20 key vocabulary. |
| 끓이다 | to boil | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 20 key vocabulary. |
| 다니다 | to attend | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 20 key vocabulary. |
| 대학교 | university/college | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 20 key vocabulary; also reused in Unit(s) 21. |
| 되다 | to become | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 20 key vocabulary. |
| 모으다 | to collect/to save | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 20 key vocabulary. |
| 바지 | pants | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 20 key vocabulary. |
| 밖 | outside | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 20 key vocabulary. |
| 부엌 | kitchen | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 20 key vocabulary; also reused in Unit(s) 24. |
| 부치다 | to mail out | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 20 key vocabulary; also reused in Unit(s) 24. |
| 사귀다 | to make (friends) | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 20 key vocabulary; also reused in Unit(s) 24. |
| 사람 | person/people | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 20 key vocabulary. |
| 시키다 | to order | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 20 key vocabulary; also reused in Unit(s) 24. |
| 영어 | English | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 20 key vocabulary. |
| 의견 | opinion | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 20 key vocabulary. |
| 의사 | medical doctor | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 20 key vocabulary; also reused in Unit(s) 21. |
| 자다 | to sleep | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 20 key vocabulary; also reused in Unit(s) 21, 23, 24, 25. |
| 하다 | to do | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 20 key vocabulary; also reused in Unit(s) 25. |
| 한국 | Korea | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 20 key vocabulary. |

### Unit 21 — -(으)ㄹ 거예요 and -(으)ㄹ까요? (key vocabulary)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가수 | singer | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 21 key vocabulary. |
| 간호사 | nurse | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 21 key vocabulary. |
| 거리 | road/street | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 21 key vocabulary. |
| 그만두다 | to quit | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 21 key vocabulary. |
| 기자 | journalist | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 21 key vocabulary. |
| 기차 | train | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 21 key vocabulary. |
| 깨끗하다 | to be clean | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 21 key vocabulary; also reused in Unit(s) 25. |
| 다음 | next | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 21 key vocabulary. |
| 맛있다 | to be delicious | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 21 key vocabulary; also reused in Unit(s) 25. |
| 목수 | carpenter | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 21 key vocabulary. |
| 배우 | actor | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 21 key vocabulary. |
| 붐비다 | to be congested | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 21 key vocabulary. |
| 생일 | birthday | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 21 key vocabulary; also reused in Unit(s) 22. |
| 요리하다 | to cook | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 21 key vocabulary. |
| 일본 | Japan | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 21 key vocabulary; also reused in Unit(s) 24. |
| 조용하다 | to be quiet | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 21 key vocabulary; also reused in Unit(s) 25. |
| 주 | week | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 21 key vocabulary. |
| 축구 | soccer | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 21 key vocabulary. |
| 친구들 | friends | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 21 key vocabulary. |
| 한국어 | the Korean language | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 21 key vocabulary; also reused in Unit(s) 24. |
| 형 | older brother | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 21 key vocabulary. |
| 화장품 | cosmetics | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 21 key vocabulary. |
| 회사원 | office worker | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 21 key vocabulary. |
| 흐리다 | to be cloudy (weather) | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 21 key vocabulary; also reused in Unit(s) 25. |

### Unit 22 — Prenouns (closed class)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 옛 | old | prenoun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 22 (prenoun closed class) key vocabulary. |
| 새 | new | prenoun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 22 (prenoun closed class) key vocabulary. |
| 헌 | used | prenoun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 22 (prenoun closed class) key vocabulary. |
| 맨 | the very | prenoun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 22 (prenoun closed class) key vocabulary. |
| 딴 | another | prenoun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 22 (prenoun closed class) key vocabulary. |
| 순 | pure | prenoun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 22 (prenoun closed class) key vocabulary. |

### Unit 22 — Prenouns (key vocabulary)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 교통 수단 | means of transportation | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 22 key vocabulary. |
| 나라 | country | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 22 key vocabulary. |
| 농구 | basketball | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 22 key vocabulary. |
| 선물 | present | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 22 key vocabulary. |
| 시계 | watch | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 22 key vocabulary. |
| 신문 | newspaper | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 22 key vocabulary. |
| 여행하다 | to travel | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 22 key vocabulary. |
| 음악 | music | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 22 key vocabulary. |
| 이용하다 | to use | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 22 key vocabulary. |
| 자주 | often | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 22 key vocabulary. |
| 장미 | rose | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 22 key vocabulary. |
| 중국 | China | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 22 key vocabulary. |
| 지하철 | subway | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 22 key vocabulary; also reused in Unit(s) 23, 25. |

### Unit 23 — Sentential adverbs

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가령 | if/supposing | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (sentential adverbs) key vocabulary. |
| 만일 | if | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (sentential adverbs) key vocabulary. |
| 설령 | even if | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (sentential adverbs) key vocabulary. |
| 설마 | surely (not) | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (sentential adverbs) key vocabulary. |
| 아마 | perhaps | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (sentential adverbs) key vocabulary. |
| 하여튼 | anyway | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (sentential adverbs) key vocabulary. |
| 반드시 | certainly | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (sentential adverbs) key vocabulary. |

### Unit 23 — Conjunctional adverbs

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 그러나 | but | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (conjunctional adverbs) key vocabulary. |
| 그리고 | and | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (conjunctional adverbs) key vocabulary. |
| 그러니까 | therefore | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (conjunctional adverbs) key vocabulary. |
| 그래서 | so | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (conjunctional adverbs) key vocabulary. |
| 그러므로 | since it is so | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (conjunctional adverbs) key vocabulary. |
| 그런데 | by the way | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (conjunctional adverbs) key vocabulary. |
| 그렇지만 | however | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (conjunctional adverbs) key vocabulary. |
| 그럼 | if so | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (conjunctional adverbs) key vocabulary. |
| 또 | also | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (conjunctional adverbs) key vocabulary. |
| 또한 | moreover | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (conjunctional adverbs) key vocabulary. |
| 또는 | or | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (conjunctional adverbs) key vocabulary. |
| 혹은 | or | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (conjunctional adverbs) key vocabulary. |
| 따라서 | accordingly | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (conjunctional adverbs) key vocabulary. |
| 즉 | in other words | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (conjunctional adverbs) key vocabulary. |
| 더군다나 | besides | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (conjunctional adverbs) key vocabulary. |
| 더우기 | moreover | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (conjunctional adverbs) key vocabulary. |

### Unit 23 — Manner adverbs

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 빨리 | fast/early/soon | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (manner adverbs) key vocabulary. |
| 천천히 | slowly | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (manner adverbs) key vocabulary. |
| 멀리 | far | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (manner adverbs) key vocabulary. |
| 가까이 | shortly/nearly | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (manner adverbs) key vocabulary. |
| 매우 | very/exceedingly | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (manner adverbs) key vocabulary. |
| 제일 | the first | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (manner adverbs) key vocabulary. |
| 가장 | most | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (manner adverbs) key vocabulary. |
| 아주 | quite/very (much) | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (manner adverbs) key vocabulary; also reused in Unit(s) 23(degree adv). |
| 너무 | too much | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (manner adverbs) key vocabulary; also reused in Unit(s) 23(degree adv). |
| 잘 | well/often | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (manner adverbs) key vocabulary. |
| 혼자서 | alone | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (manner adverbs) key vocabulary. |
| 함께 | together | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (manner adverbs) key vocabulary. |
| 많이 | much | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (manner adverbs) key vocabulary; also reused in Unit(s) 23, 25. |
| 열심히 | diligently | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (manner adverbs) key vocabulary; also reused in Unit(s) 25. |
| 안녕히 | at peace | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (manner adverbs) key vocabulary. |

### Unit 23 — Time adverbs

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 막 | just at the moment | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (time adverbs) key vocabulary. |
| 방금 | right now | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (time adverbs) key vocabulary. |
| 벌써 | long ago | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (time adverbs) key vocabulary. |
| 아까 | some time ago | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (time adverbs) key vocabulary. |
| 아직 | yet/still | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (time adverbs) key vocabulary. |
| 이미 | already | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (time adverbs) key vocabulary. |
| 요즈음 | recently | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (time adverbs) key vocabulary. |
| 지금 | now | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (time adverbs) key vocabulary. |
| 현재 | present | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (time adverbs) key vocabulary. |
| 이따 | later | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (time adverbs) key vocabulary. |
| 모래 | the day after tomorrow | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (time adverbs) key vocabulary. |
| 갑자기 | suddenly | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (time adverbs) key vocabulary. |
| 냉큼 | immediately | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (time adverbs) key vocabulary. |
| 당분간 | for a while | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (time adverbs) key vocabulary. |
| 밤낮 | night and day | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (time adverbs) key vocabulary. |
| 줄곧 | all the time | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (time adverbs) key vocabulary. |
| 드디어 | finally | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (time adverbs) key vocabulary. |
| 마침내 | at last | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (time adverbs) key vocabulary. |
| 먼저 | ahead | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (time adverbs) key vocabulary. |
| 언제나 | all the time | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (time adverbs) key vocabulary. |
| 일찍 | early | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (time adverbs) key vocabulary. |
| 늘 | always | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (time adverbs) key vocabulary. |
| 항상 | at all times | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (time adverbs) key vocabulary. |
| 보통 | usually | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (time adverbs) key vocabulary. |
| 가끔 | sometimes | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (time adverbs) key vocabulary. |

### Unit 23 — Degree adverbs

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 참 | really | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (degree adverbs) key vocabulary. |
| 조금 | a bit | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (degree adverbs) key vocabulary. |
| 주로 | mainly | adverb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 (degree adverbs) key vocabulary. |

### Unit 23 — Adverbs and adverbials (key vocabulary)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 값 | price | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 key vocabulary; also reused in Unit(s) 25. |
| 경치 | scenery | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 key vocabulary. |
| 공부하다 | to study | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 key vocabulary; also reused in Unit(s) 24, 25. |
| 궁금하다 | to be curious | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 key vocabulary. |
| 귤 | tangerine | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 key vocabulary. |
| 느리다 | to be slow | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 key vocabulary. |
| 맛없다 | to be tasteless | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 key vocabulary. |
| 머리 | head | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 key vocabulary. |
| 복잡하다 | to be complex | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 key vocabulary. |
| 부드럽다 | to be soft/to be tender | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 key vocabulary. |
| 시간 | time | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 key vocabulary. |
| 시원하다 | to be cool/refreshing | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 key vocabulary. |
| 시험 | test | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 key vocabulary; also reused in Unit(s) 25. |
| 싸다 | to be cheap | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 key vocabulary. |
| 씩씩하다 | to be manly | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 key vocabulary. |
| 연락 | contact | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 key vocabulary. |
| 외롭다 | to be lonely | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 key vocabulary. |
| 우습다 | to be funny/laughable | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 key vocabulary. |
| 위험하다 | to be dangerous | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 key vocabulary. |
| 유명하다 | to be famous | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 key vocabulary. |
| 작다 | to be small | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 key vocabulary. |
| 전화 | telephone | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 key vocabulary. |
| 주다 | to give | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 key vocabulary; also reused in Unit(s) 24. |
| 피곤하다 | to be tired | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 23 key vocabulary. |

### Unit 24 — -(으)ㄹ래요 and -(으)ㄹ게요 (key vocabulary)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 내다 | to pay | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 24 key vocabulary. |
| 누나 | older sister (of a male) | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 24 key vocabulary. |
| 미국 | USA | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 24 key vocabulary. |
| 방학 | vacation | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 24 key vocabulary. |
| 보다 | to see | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 24 key vocabulary; also reused in Unit(s) 25. |
| 즐기다 | to enjoy | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 24 key vocabulary. |
| 차 | car | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 24 key vocabulary. |
| 창문 | window | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 24 key vocabulary. |

### Unit 25 — Suffixes -겠 and -(으)시 (key vocabulary)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 거실 | living room | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 25 key vocabulary. |
| 고등학교 | high school | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 25 key vocabulary. |
| 교통 | traffic | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 25 key vocabulary. |
| 금요일 | Friday | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 25 key vocabulary. |
| 꼭 | surely | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 25 key vocabulary. |
| 끊다 | to quit | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 25 key vocabulary. |
| 내리다 | to fall/to drop | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 25 key vocabulary. |
| 두드리다 | to knock (door) | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 25 key vocabulary. |
| 막히다 | to be held up | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 25 key vocabulary. |
| 매일 | everyday | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 25 key vocabulary. |
| 미끄럽다 | to be slippery | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 25 key vocabulary. |
| 비 | rain | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 25 key vocabulary. |
| 약속 | promise | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 25 key vocabulary. |
| 에어로빅 | aerobics | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 25 key vocabulary. |
| 열쇠 | key | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 25 key vocabulary. |
| 재미있다 | to be interesting | adjective | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 25 key vocabulary. |
| 점심 | lunch | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 25 key vocabulary. |
| 준비하다 | to prepare | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 25 key vocabulary. |
| 지키다 | to keep | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 25 key vocabulary. |
| 찾다 | to find | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 25 key vocabulary. |
| 치다 | to play/to hit | verb | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 25 key vocabulary. |
| 품질 | quality | noun | core | — | contemporary (source published 2009, 1st ed.) | — | — | grammar_reference | n/a | n/a | Unit 25 key vocabulary. |

## Grammar points

### Unit 16 — Special particles 2: 이나/나, 부터, 까지 (PDF p. 134–142, printed p. 125–132)

**(이)나 / 나** is a two-form special particle (이나 after a consonant-final noun, 나 after a
vowel-final one) with four distinct construals depending on context: (1) "or something (like
that)" after a single noun (완지에서 텔레비전이나 볼 거예요 "I'll watch TV or something"); (2) plain
"or" between two nouns (사과나 오렌지 주세요 "give me apples or oranges"); (3) "as many as / as much
as," expressing the speaker's surprise at an unexpectedly large quantity (네 시간이나 운전했어요 "I
drove as many as four hours"); (4) "about/approximately," when attached to a quantity question
word such as 몇 "how many" or 얼마 "how much" (얼마나 줬어요? "about how much did you give?"). The
particle can also attach to question words (어디 "where" → 어디나 "anywhere"; 누구 "who" → 누구나
"anyone/everyone"; 무엇 "what" → 무엇이나 "anything"), generalizing their interrogative meaning.

**부터** "from" marks a starting temporal point, contrasting with the simple locative/temporal
particle 에 ("at"). **까지** marks an ending point ("to/until/as far as"), used with both temporal
and locational nouns, and — with a non-time, non-place noun (a person, an item) — shifts to mean
"including (even)" (바바라까지 서울에 갔어요 "even Barbara went to Seoul"). 부터 and 까지 are frequently
paired to express "from X to Y" (오전 11시부터 오후 3시까지 "from 11 a.m. to 3 p.m."), and 에서 pairs
with 까지 the same way for locations (서울에서 동경까지 "from Seoul to Tokyo").

### Unit 17 — Past tense 었/았 and double past tense 었/았었 (PDF p. 143–152, printed p. 133–140)

Korean predicate endings split into **final endings** (speech-level endings like polite -어/아요 or
deferential -습니다) and **pre-final endings** (inserted between the stem and the final ending,
such as the past-tense marker or the honorific suffix). The **past tense marker 았/었** is a
two-form pre-final ending: 았 follows a stem whose vowel is a "bright" vowel (아 or 오), 었 follows
every other vowel; e.g. 가다 "go" → 가+았+어요 → 갔어요 "went" (with vowel contraction), 먹다 "eat" →
먹+었+어요 → 먹었어요 "ate." The irregular verb 하다 "do" changes its stem to 해 before the past marker
(했어요). Unlike English, the Korean past tense marks not just pastness but also whether the
action/state is a **complete, still-relevant result** — 집에 왔어요 can mean either "I came home" or
"I am home (as a result)."

The **double past tense marker 았었/었었** (past marker + 었 again) pushes the event further into the
past and signals it is **no longer relevant to the present** — 집에 왔었어요 "I came home (but am no
longer there)," contrasted with the single-past 왔어요 ("I am home"). This double marking is a
genuinely agglutinative stacking of two instances of the same past-tense morpheme onto one stem;
see the morpheme breakdown below.

> **갔었어요** = 가- (go, verb stem) + -았- (past, bright-vowel allomorph) + -었- (past, second layer,
> "remoteness/no-longer-relevant") + -어요 (polite speech-level ending) — a triple-stacked ending
> that would require a full English clause ("went, but am no longer there") to translate the
> semantic content packed into four bound morphemes on one stem.

### Unit 18 — Negation: 안/못, the long form -지 않다/-지 못하다, and 말다 (PDF p. 153–162, printed p. 141–150)

Korean has two negation strategies. The **short form** places 안 "not" (general negation, from 아니
"no") or 못 "cannot" (negation of ability/volition) directly before the predicate (안 봐요 "don't
see," 못 팔아요 "can't sell"). 못 cannot combine with adjectives describing inherent states/quantities
(못 비싸요 "*cannot-expensive" is ungrammatical), and a handful of verbs that already have a
suppletive negative counterpart (알다 "know" / 모르다 "not know"; 있다/없다; 맛있다/맛없다) never take
either short-form negative. For a noun+하다 compound verb, the negative attaches to 하다 alone
(요리 안 해요, not *안 요리해요).

The **long form** adds -지 to the stem, followed by the negative auxiliary 않다 (general) or 못하다
(ability): 먹지 않아요 "don't eat," 먹지 못해요 "can't eat." The two forms are interchangeable in
meaning, though the long form skews more formal/written. Notably, in the long form only, 못 can
combine with a few desire-related adjectives (충분하다 "abundant," 행복하다 "happy," 건강하다 "healthy,"
유능하다 "competent") to convey disappointment rather than inability (그 아이는 건강하지 못했어요 "[too
bad] that child wasn't healthy"). Both short and long forms are restricted to declarative and
interrogative sentence types — imperative/propositive negation instead requires the auxiliary verb
**말다** "stop" (stem + -지 말다): 가지 마십시오 "don't go," 가지 맙시다 "let's not go." 말다 is itself a
ㄹ-irregular verb, losing its final ㄹ before an ending beginning with ㄴ, ㅂ, or ㅅ (마십시오, 맙시다)
but retaining it before the polite ending -아요 (말아요).

### Unit 19 — Seven irregular predicate classes (PDF p. 163–172, printed p. 151–159)

Korean predicates are **regular** (stem never changes) or **irregular** (stem changes shape
depending on the following suffix's initial sound). This unit catalogs seven classes, each defined
by what happens to the stem-final consonant/vowel when a vowel-initial suffix (like polite -어/아요)
follows, versus a consonant-initial suffix (like deferential -습니다):

- **ㄷ-irregular**: stem-final ㄷ → ㄹ before a vowel-initial suffix (묻다 "ask" → 물어요, not
  *묻어요). Only some ㄷ-final predicates behave this way; 닫다 "close," 받다 "receive," 믿다
  "believe," 얻다 "gain" stay regular.
- **ㅂ-irregular**: stem-final ㅂ → 우 (or, for a couple of predicates, 오) before a vowel-initial
  suffix — 춥다 "cold" → 춥+어요 → 추우+어요 → 추워요. This is the single largest irregular class in
  the unit (26 items catalogued), including most "physical/emotional state" adjectives (무겁다
  "heavy," 아름답다 "beautiful," 어렵다 "difficult," 쉽다 "easy," etc.). A smaller regular-ㅂ set (뽑다,
  씹다, 입다, 잡다, 좁다, …) does not undergo the change.
- **ㅅ-irregular**: stem-final ㅅ is simply deleted before a vowel-initial suffix (긋다 "draw" →
  그어요, not *긋어요). Regular counterexamples: 벗다, 빗다, 빼앗다, 씻다, 웃다.
- **ㅎ-irregular**: stem-final ㅎ is deleted *and* the vowel that follows changes quality before a
  vowel-initial suffix — nearly all of Korean's basic color adjectives fall here (까맣다 "black" →
  까매요, 노랗다 "yellow" → 노래요, 하얗다 "white" → 하얘요), plus the demonstrative-linked adjectives
  그렇다/이렇다/저렇다/어떻다 ("be that/this/that-other way," "be how"). Regular ㅎ-final predicates
  (넣다, 놓다, 좋다) keep ㅎ throughout.
- **르-irregular**: the vowel 르 drops and a doubled ㄹ is inserted, but *only* before a suffix
  beginning with 어 or 아 specifically (not before other vowel-initial suffixes) — 다르다 "different"
  → 다르+아요 → 달ㄹ+아요 → 달라요. This is the largest class by count (23 items), covering many
  common verbs (모르다 "not know," 부르다 "sing/call," 자르다 "cut") and adjectives (빠르다 "fast," 다르다
  "different"). A tiny regular set (다다르다, 따르다, 치르다) does not undergo the change.
- **ㄹ-irregular**: stem-final ㄹ is deleted before a suffix beginning with ㄴ, ㅂ, or ㅅ (살다 "live"
  → 사는 not *살는; 만들다 "make" → 만드는; the deferential-imperative-related 말다 case from Unit 18
  is this same class). ㄹ is retained before other suffixes, including the polite -어/아요 (살아요,
  not *사아요). 31 items are catalogued, including several common verbs (알다 "know," 팔다 "sell,"
  열다 "open") and a few adjectives (길다 "long," 멀다 "far").
- **으-irregular**: the vowel 으 of the stem drops before a vowel-initial suffix, and (per the note
  under Unit 19's own examples) the preceding consonant surfaces with a match to whichever of 아/어
  the following suffix vowel is (담그다 "soak" → 담가요; 쓰다 "write/use" → 써요; 아프다 "sick" → 아파요;
  크다 "big" → 커요). All 으-final predicates in Korean are irregular this way — there is no regular
  counterpart set for this class (unlike the other six).

> **추워요** = 춥- (cold, adjective stem, ㅂ-irregular) + [ㅂ→우 alternation] + -어요 (polite,
> non-bright-vowel allomorph) — the alternation is conditioned purely by the initial sound of the
> following suffix, not by anything in the stem itself; the same root surfaces as 춥- unaltered
> before a consonant-initial suffix (춥습니다 "is cold," deferential).
>
> **달라요** = 다르- (different, adjective stem, 르-irregular) + [르-drop + ㄹ-insertion, triggered
> only by an 아/어-initial suffix] + -아요 — contrast **다르니까** "since it's different," where the
> suffix -니까 does not begin with 아/어, so the stem surfaces unchanged as 다르니까, not *달니까.

**Note on typology relevance:** this unit is itself the clearest illustration in the book of why
Korean's agglutinative morphology matters for slang-mechanics analysis (see
`00_Word_Concept_and_Morphological_Typology_Guide.md`) — the *same* suffix (e.g. polite -어/아요)
surfaces in visibly different shapes purely as a function of the preceding stem's final segment,
which is ordinary grammatical productivity, not slang-specific play. Any future finding of
"irregular-conjugation-like" behavior in slang data needs to be checked against this baseline before
being called a novel mechanism.

### Unit 20 — Desire -고 싶다 and progressive -고 있다 (PDF p. 173–180, printed p. 161–168)

**-고 싶다** ("connector -고 + auxiliary adjective 싶다") expresses the **first person's** desire/wish
(한국어를 배우고 싶어요 "I want to learn Korean") and can be used in **second-person questions** (어디에
가고 싶어요? "where do you want to go?") but never in a bare second- or third-person statement — a
third person's wish instead requires the auxiliary **싶어하다** (수지가 한국에 가고 싶어해요 "Suzie wants
to go to Korea"). Past tense attaches to 싶다/싶어하다's own stem (싶었어요, 싶어했어요), and the
honorific suffix likewise attaches there (싶으세요 "would you like...?"). -고 싶다/싶어하다 cannot combine
with the copula 이다 — "want to be a teacher" instead uses 되다 "become" (선생님이 되고 싶어요, not
*선생님이 이고 싶어요), unlike English, where "be" and "become" are both idiomatic.

**-고 있다** is the progressive, built the same way (connector -고 + 있다 "exist"): 배우고 있어요 "is
learning." Past progressive adds 었/았 to 있다's stem (배우고 있었어요 "was learning"). To honor the
subject, 계시다 replaces 있다 (전화를 하고 계세요 "the professor is making a phone call"). Both short-
and long-form negation can apply to the progressive (안 열고 있어요 / 열고 있지 않아요, "isn't opening").

### Unit 21 — -(으)ㄹ 거예요 (probable future) and -(으)ㄹ까요? (wondering/seeking opinion) (PDF p. 181–192, printed p. 169–176)

**-(으)ㄹ 거예요** is Korean's most common future-referring ending, but the book stresses it marks a
*probable*, not definite, future — an event the speaker expects to happen is instead expressed with
plain present tense plus a time adverb (내일 한국에 가요 "I go to Korea tomorrow" = a scheduled,
near-certain event), while -(으)ㄹ 거예요 explicitly lowers the certainty (내일 한국에 갈 거예요 "I will
(probably) go to Korea tomorrow"). Morphologically it is three parts: the prospective/uncertainty
modifier -(으)ㄹ + the bound noun 거 (colloquial for 것 "thing/fact") + 예요 (polite copula ending). It
has three allomorphs: -을 거예요 after a consonant-final stem, -ㄹ 거예요 after a vowel-final stem,
-거예요 after a ㄹ-irregular stem (which has already lost its ㄹ). With a first-person subject it can
also read as intention ("will," in the volitional sense); with a non-1st/2nd-person subject it reads
as the speaker's conjecture about someone/something else (수잔은 바쁠 거예요 "I guess Susan will be
busy"); with the copula 이다 it marks probable *present* identity (에린은 한국사람일 거예요 "Erin is
probably Korean").

**-(으)까요?** (politely -(으)ㄹ까요?) expresses the speaker's own wondering, or solicits the
listener's opinion — with a speaker-inclusive subject it's "I wonder whether..." (어디로 갈까요? "I
wonder where we should go"); with a third-person subject it becomes "do you think that...?" (수잔이
어느 대학을 갈까요? "which university do you think Susan will go to?"). It can be repeated across two
clauses to form an alternative question (한국 음식을 먹을까요? 중국 음식을 먹을까요? "shall we eat Korean or
Chinese food?" — note Korean repeats the predicate where English uses it once), and when combined
with 하다/생각하다 it means "I'm thinking of doing X" (저녁을 6시에 먹을까 해요 "I'm thinking of having
dinner at 6").

> **갈 거예요** = 가- (go) + -ㄹ (prospective modifier, vowel-stem allomorph) + 거 (bound noun,
> "thing/fact," colloquial form of 것) + -예요 (polite copula ending) — three separate morphemes
> fused into one functional "probable future" unit; not decomposable as a single suffix the way
> English "will" is a single word.

### Unit 22 — Prenouns (PDF p. 193–199, printed p. 177–182)

Korean **modifiers** include prenouns, adjectives, and relative clauses; this unit's focus,
**prenouns**, are nouns that only ever modify a following noun and are never inflected — unlike
adjectives, which are predicates subject to conjugation. The book's diagnostic example: 딴 학교
"another school" (prenoun 딴) vs. 다른 학교 "different school" (the conjugated noun-modifying form of
the adjective 다르다). Four subtypes are catalogued: (1) a small closed class of quality/status
prenouns (옛 "old," 새 "new," 헌 "used," 맨 "the very," 딴 "another," 순 "pure" — each combining freely
with a following noun, e.g. 옛 이야기 "old story," 새 신발 "new shoes," 헌 옷 "used clothes"); (2)
numbers used attributively before a counter or noun (한 사람 "one person," 두 살 "two years old");
(3) the three-way demonstrative system 이/그/저 ("this [near speaker]" / "that [near listener]" /
"that over there [away from both]" — a genuine three-term system where English collapses to two),
which (unlike English "this"/"that") can never stand alone and must always precede a noun, often the
bound nouns 것/거 "thing" or 곳/여기·거기·저기 "place"; and (4) question prenouns 어느 "which" and
무슨/어떤 "what kind of," equally unable to stand alone.

### Unit 23 — Adverbs and adverbials (PDF p. 200–206, printed p. 183–189)

Korean adverbs split into three functional types: **sentential** adverbs modify a whole sentence
(하여튼 "anyway," 아마 "perhaps," 반드시 "certainly" — 7 catalogued); **conjunctional** adverbs link two
sentences (그리고 "and," 그러나 "but," 그래서 "so," 그런데 "by the way" — 16 catalogued, many built on
the demonstrative root 그- "that"); and **componential** adverbs modify one specific constituent,
further split by relation into **manner** (빨리 "fast," 천천히 "slowly," 열심히 "diligently" — 15),
**time** (벌써 "long ago," 아직 "yet," 갑자기 "suddenly," 드디어 "finally" — 26), and **degree** (아주
"very," 너무 "so much," 조금 "a bit" — 5). When multiple componential adverbs co-occur in one
sentence, they surface in the fixed order **time → degree → manner** (항상 아주 많이 마셔요 "always
drinks very much," where 항상=time, 아주=degree, 많이=manner).

Distinct from true (invariant) adverbs are **adverbials** — adjective stems given a morphological
adverb-forming suffix **-게** (맛있다 "delicious" → 맛있게 "deliciously"; 아름답다 "beautiful" → 아름답게
"beautifully"). This is itself a small, closed, productive derivational pattern worth flagging for
later morphological-play comparison: -게 attaches to essentially any adjective stem to yield its
manner-adverbial counterpart, a genuinely regular (non-lexicalized) process.

> **맛있게** = 맛있- (delicious, adjective stem) + -게 (adverbializer) — a fully productive
> derivational suffix, distinct from the closed-class adverb list above; any adjective in the
> language can take -게, which is why the book treats "adverbial" as its own grammatical category
> rather than folding these forms into the adverb vocabulary list.

### Unit 24 — -(으)ㄹ래요 (intention) and -(으)ㄹ게요 (willingness/promise) (PDF p. 207–213, printed p. 191–197)

**-(으)ㄹ래요** expresses the speaker's own intention or immediate desire ("will/intend to"),
restricted to verbs (not adjectives) and to colloquial registers, and — like -고 싶다 in Unit 20 — is
grammatical only for first- and second-person subjects (A: 뭐 마실래요? "what will you have?" — B:
커피 주세요 "coffee, please"). It contrasts with -고 싶어요/싶어해요 (Unit 20) in that the latter is a
mere wish, while -(으)ㄹ래요 signals the speaker has already made up their mind; it also overlaps with
-(으)ㄹ 거예요 (Unit 21) for first-person intention, but -(으)ㄹ 거예요 additionally covers third-person
conjecture, which -(으)ㄹ래요 cannot.

**-(으)ㄹ게요** expresses a promise or willingness *for the listener's benefit*, is likewise
verb-only, but unlike -(으)ㄹ래요 is restricted to the **first person only** (no second-person
question use) — A: 몇 시에 올 거예요? "what time will you come?" — B: 9시까지 갈게요 "I'll (promise to)
be there by 9." The functional difference from -(으)ㄹ래요 is illustrated with minimal pairs:
공항에 제가 갈래요 "I intend to go to the airport" vs. 공항에 제가 갈게요 "I('ll promise to) go to the
airport" (volunteering). Both endings are three-form (-을래요/-ㄹ래요/-래요 and -을게요/-ㄹ게요/-게요,
by consonant-final / vowel-final / ㄹ-irregular stem, mirroring the -(으)ㄹ 거예요 pattern from Unit 21).

### Unit 25 — The suffixes -겠 (inference/intention) and -(으)시 (subject honorific) (PDF p. 214–220, printed p. 199–206)

**-겠** is a pre-final ending (stem + 겠 + final ending, e.g. 하겠습니다 "will do") with two readings
depending on the subject: for a first-/second-person subject it expresses intention/asks the
listener's intention ("will," formal register — contrasted explicitly with the more colloquial
-(으)ㄹ래요 from Unit 24); for a third-person or non-person subject it expresses the speaker's
**conjecture** ("I guess that...") or solicits the listener's conjecture. This conjecture use is the
register the book flags as typical of **formal/broadcast contexts** such as weather forecasts and
news reports (오늘 밤부터 눈이 오겠습니다 "snow will fall from tonight [weather-forecast register]").

**-(으)시**, the **subject honorific suffix**, is this unit's — and the book's — most explicit
register/politeness marker: a pre-final ending (으시 after a consonant-final stem, 시 after a
vowel-final stem) that grammatically encodes deference toward the sentence's subject, independent of
which speech-level ending is chosen. The book is explicit that the choice of *speech level*
(deferential/polite/intimate, etc.) depends on the **addressee**, while the honorific suffix -(으)시
depends on the **subject being honored** (who may be the addressee, as in 어디에 가세요? "where are
you going?," or a third-person referent being discussed, as in 김 교수님이 오세요 "Professor Kim is
coming") — the two systems are independent and can combine, e.g. an intimate-level sentence can still
carry -(으)시 when its subject (not its addressee) merits honor (어머니는 어디에 가셔? "where's mother
going?," intimate level, honorific subject suffix). Social variables triggering the honorific include
age, kinship seniority, and esteemed occupation/rank. A closed set of **suppletive honorific verbs**
(먹다→잡수시다 "eat," 자다→주무시다 "sleep," 있다→계시다 "exist/stay") already lexically contain 시 and
do not additionally suffix it. Critically, **speakers never apply -(으)시 to themselves** — 어디에
가세요? "where are you going?" (asked, honorific) is answered 집에 가요 "I'm going home" (no honorific
on the speaker's own action), a self-effacement rule worth flagging for any later slang-register
comparison (e.g. slang that violates or plays with self-honorification would be a marked departure
from this baseline norm).

> **가십니다** = 가- (go, verb stem) + -시- (subject-honorific pre-final suffix) + -ㅂ니다
> (deferential-speech-level final ending) — three functionally distinct layers (root, honorific
> register marker, addressee-directed speech-level marker) stacked on one stem, illustrating how
> Korean's honorific system is woven directly into verb morphology rather than expressed only
> through separate lexical choices (as in, e.g., French tu/vous or Spanish tú/usted, which affect
> pronoun and agreement but not a dedicated verb-internal honorific slot).


---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`. All example
sentences above are individually short, illustrative fragments selected to demonstrate a specific
grammar point (the book's own stated pedagogical purpose for printing them), not a reproduction of
any vocabulary box, dialogue, or exercise set in bulk; the "key vocabulary for exercises" lists are
tabulated (term + gloss only, the minimum needed for this project's own vocabulary schema) rather
than reproducing the book's surrounding exercise prompts, example sentences, or answer keys.
