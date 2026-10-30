# Korean — Established Vocabulary/Grammar: Full-Book Consolidated Vocabulary List + Scope Notes

**Source:** Suk-in Chang, *Modern Conversational Korean* (Revised Edition, Seoul Press, 5th printing
1995; originally 1982), 378pp scanned PDF, 90 lessons (pp. 1–329) + Appendix/References/Vocabulary
List/Index (pp. 331–352). This file covers the book's own consolidated back-of-book **Vocabulary
List** (printed pp. 343–352 / PDF pp. 364–373), plus a scope-decision note on the book's 90 lessons
of dialogue and grammar notes.

## Coverage note — non-redundant-supplement scope decision

**Text-layer status:** `pdfinfo` reports a real text layer (`pdftotext` extracts cleanly), but this
is a 2008 ScanSnap scan with an OCR'd text layer, not an embedded-font PDF. The book's own
**English** prose (introduction, grammar-note explanations, dialogue translations) extracts
perfectly via `pdftotext`. Every embedded **Hangul** string, however, comes out as non-decodable
glyph soup (e.g. `annyong-haseyo`'s Hangul rendered as `°J^^M].3_`) — this is genuine OCR
mis-recognition (Hangul glyphs matched against a Latin-trained OCR model), **not** a fixed 1:1 or
additive-offset substitution cipher of the kind documented elsewhere in this project's Korean
corpus (verified: the same Korean word recurring across different pages decodes to different,
unrelated Latin-glyph garbage each time — there is no stable mapping to reverse). Per the extraction
spec, this correctly falls back to vision-reading rather than a cipher-decode attempt.

**Scope decision.** This is a 90-lesson, 378-page conversational course — the 50th Korean source
extracted for this project, with 46 established files already on disk covering the ordinary beginner
grammar/particle/honorific/tense territory exhaustively (confirmed by grep: `contraction`,
`speech level`, `retrospective` (evidential -더-), `honorific`, and the drinking idiom `한잔하다` /
`한 잔` all already appear across 8–30+ prior established files each). Rather than vision-read all 90
lessons' individual vocabulary boxes and grammar notes (which would mostly re-derive material
already captured, at very high vision-reading cost), this extraction targets the book's own
**back-of-book Vocabulary List** (PDF pp. 364–373, 10 pages) — a single consolidated,
alphabetically-ordered (by Hangul initial consonant: ㄱ–ㅎ) glossary covering the vocabulary
introduced across *all 90 lessons*, each entry cross-referenced to its introducing lesson's printed
page number. This is the most efficient way to satisfy the spec's "every distinct vocabulary item"
rule for this source without redundant per-lesson vision-reading, and it was fully vision-read
(all 10 pages, rendered at 300dpi via `pdftoppm`, read directly as images — not OCR'd).

**What was kept:** the entire back-of-book Vocabulary List, in full — per this project's established
convention that an independently-chosen example/vocabulary set counts as non-redundant even where
grammar overlaps. This glossary is large (several hundred entries) but compact to extract (10 pages)
and gives complete, book-wide vocabulary coverage in one pass.

**What was skipped as redundant, and why:**
- **Pronunciation-drill lessons 1–40's phonology content** (vowel/consonant articulation, Hangul
  stroke order) — already covered in dedicated depth by `013_sounds_of_korean_pronunciation_guide.md`.
- **Basic particle grammar** (이/가, 은/는, 을/를, -에, -에서, -와/-과 vs -하고 "and"), **honorific
  humble-noun/verb pairing tables** (말씀/말, 진지/밥, 댁/집, 드리다/주다, 여쭙다/묻다, 뵙다/보다,
  주무시다/자다, 잡수시다/먹다, 계시다/있다), **basic tense/aspect** (past -았/었-, future -겠-,
  progressive -고 있다), **the six-level honorific/speech-level system**, and **numbers/counting/
  time-telling** — checked directly against this book's own Introduction (Table 4 "Korean Parts of
  Speech," Table 5 "Examples of Honorific and Humble Speech," Table 6 "Examples of Verb Endings") and
  against representative lesson grammar notes (e.g. Lesson 13's -와/-과 vs -하고 "and" comparison,
  Lesson 58's -고 있다 progressive note). All of this duplicates material already present across
  10–46+ prior established Korean files; re-extracting it here would be pure padding.
- **The retrospective/evidential insert -더-** and **the drinking idiom 한잔하다/"to have one glass"**
  (title of Lesson 64) — both independently confirmed already present in multiple prior established
  files (`retrospective`: 11 files; `한잔`/`한 잔`: 8 files) via direct grep before deciding to skip.
- No explicit dialectal/regional annotation system (no `[B]`/`[C]`/`[S]`-style tags) appears anywhere
  in this book — confirmed by a full-text grep for `dialect`/`regional`/`province`/`Pyongyang`, which
  returned no comparative-dialect markup. There is nothing of that kind to have missed.

**What was kept as genuinely novel** (see Grammar points below): the author's own idiosyncratic
**"insert" terminology** for pre-final verb-stem suffixes (a naming convention distinct from every
other source in this corpus, even though the underlying morphemes — honorific -시-, past -았/었/였-,
future -겠-, retrospective -더- — are standard and already documented elsewhere), and the book's
explicit scholarly citation of three named Korean grammarians for its parts-of-speech taxonomy.

**Vision-reading guard:** all 10 vocabulary-list pages are clean single-owner printed book pages
(crisp 300dpi scans, consistent typeset font throughout, no marginalia, no handwriting of any kind
observed) — no handwritten-annotation exclusion was necessary.

---

## Vocabulary

*(Notes column cites the printed page number(s) given in the book's own Vocabulary List — this is
the page where each term is first introduced/used in a lesson, not a frequency ranking. Several
headwords recur twice in the source's own list with two distinct senses/page citations; both rows
are kept, matching the source. A handful of rows are flagged `low_confidence` where the scanned
glyph and the printed English gloss did not cleanly agree on re-reading, or where the source form
looks like a spelling variant of the modern standard — these are called out explicitly rather than
silently corrected.)*

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가다 | to go | active verb | core | — | contemporary (1982; rev. 1995) | — | — | grammar_reference | n/a | plausible_unverified | p.9 |
| 가깝다 | to be near | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.61 |
| 가게 | a shop | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.75 |
| 가구 | furniture | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.188,259 |
| 가끔 | occasionally | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.205 |
| 가깝다 | to be close | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.161 (2nd glossary entry, distinct page ref) |
| 가득 | full | descriptive verb/adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.258 |
| 가루 | powder | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.230 |
| 가르치다 | to teach | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.63 |
| 가만히 | motionlessly | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.304 |
| 가방 | a bag | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.34 |
| 가볍다 | to be lightweight | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.63 |
| 가운데 | in the center | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.144 |
| 가위 | scissors | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.146 |
| 가을 | autumn | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.302,308 |
| 가장 | most | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.308 |
| 가져가다 | to take (something away) | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.279 |
| 가족 | family | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.103 |
| 간식 | a snack | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.58 |
| 간호원 | a nurse | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.18; older term, modern usage favors 간호사 |
| -감 | stuff, material | noun (bound) | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.168 |
| 감기 | cold (illness) | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.176,322 |
| 감사 | thanks | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.12 |
| -갑 | a case | noun (bound) | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.75 |
| 갑자기 | suddenly | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.314 |
| 값 | cost, price | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.103 |
| 강아지 | puppy | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.44; Lesson 9 title term |
| 강의 | a lecture | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.58 |
| 강의실 | a lecture room | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.58 |
| 같이 | together | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.107 |
| 개 | a dog | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.44 |
| -개 | items, unit | classifier | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.72; general counter |
| 개인 | an individual | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.194 |
| 객지 | a strange land | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.226 |
| 거기 | there | pronoun (demonstrative) | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.56 |
| 거울 | a mirror | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.98 |
| 거짓말 | a lie | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.293 |
| 건강하다 | be in good health | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.266 |
| 건물 | a building | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.197 |
| 걷다 | to walk | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.247 |
| 걸다 | to dial a telephone | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.192 |
| 걸리다 | to be caught; to take time | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.245 |
| 것 | a thing | noun (bound) | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.34 |
| 게으르다 | to be idle | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.316 |
| 겨울 | winter | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.30; Lesson 86 title term |
| 겨자 | mustard | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.230 |
| 결과 | result | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.268 |
| 결혼 | marriage | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.217 |
| 경비실 | guard house | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.197 |
| 경비원 | guard | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.234 |
| 경치 | a landscape | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.119 |
| 곁 | beside | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.145 |
| 계란 | egg | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.167 |
| 계속하다 | to continue | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.317 |
| 계시다 | to be (honorific) | existential verb | formal | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.9,39; honorific of 있다, part of the standard humble/honorific pair system |
| 계절 | season | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.306 |
| 계획 | a plan | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.108,199 |
| 고급 | best grade | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.258 |
| 고기 | meat; fish | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.165,278 |
| 고단하다 | to be tired | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.148 |
| 고등학교 | high school | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.112,215 |
| 고르다 | to choose | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.124 |
| 고무신 | rubber shoes | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.36 |
| 고상하다 | to be noble | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.23 |
| 고양이 | a cat | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.44 |
| 고추 | red pepper | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.230 |
| 고치다 | to repair, fix | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.154 |
| 고프다 | to be hungry | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.182 |
| 고향 | one's native place | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.108; Lesson 63 "Hometown" title term |
| 곧 | immediately; just | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.278 |
| 골동품 | antiques | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.298 |
| 곰 | bear | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.188 |
| 곳 | place | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.112 |
| 공부하다 | to study | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.29 |
| 공일 | a holiday; a day off | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.92 |
| 공중전화 | a public telephone | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.194 |
| 공책 | a notebook | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.23 |
| 공항 | airport | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.258; Lesson 72 title term |
| 공휴일 | holiday | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.92 |
| 과일 | fruit | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.75 |
| 굉장히 | magnificently | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.327 |
| 교과서 | a textbook | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.36 |
| 교수 | professor | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.41 |
| 교실 | a classroom | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.86 |
| 교외 | suburbs | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.238 |
| 교통 | traffic | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.283 |
| 교환수 | a telephone operator | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.194 |
| 교회 | church | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.197 |
| 구경하다 | to sightsee | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.161 |
| 구두 | leather shoes | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.36 |
| 구수하다 | to be tasty | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.327 |
| 국 | soup | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.97 |
| -국 | a telephone exchange | noun (bound) | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.192 |
| 국민학교 | a primary school | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.217; pre-1996 term for elementary school, since replaced by 초등학교 — era-specific usage |
| 국제 | international | noun/adjective | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.209 |
| 국회 | the National Assembly | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.112 |
| 굴 | a tunnel; an oyster | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.217 |
| 굶다 | starve | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.264 |
| -권 | books, volume(s) | classifier | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.74 |
| 귀 | an ear | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.320 |
| 귀국하다 | returning to one's country | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.264 |
| 귤 | an orange | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.75 |
| 그글피 | three days after tomorrow | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.90; part of this book's unusually complete relative-day vocabulary set |
| 그냥 | (just) as it is | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.281 |
| 그다음 | the next | noun/adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.90 |
| 그대로 | like that; as it is | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.279 |
| 그렇다 | to be right; to be so | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.51 |
| 그림 | a picture | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.293 |
| 그만 | enough | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.203 |
| 그믐 | last day of the month | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.288 |
| 그저 | casually; slightly | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.77,291 |
| 그저께 | the day before yesterday | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.90 |
| 그전날 | the day before | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.91 |
| 그그저께 | two days before yesterday | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.90 |
| 극장 | a movie theater | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.149 |
| 근처 | near by; close by | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.209 |
| 글씨 | writing; handwriting | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.289 |
| 글피 | two days after (tomorrow) | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.90 |
| -금 | a line | noun (bound) | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.176 |
| 금년 | this year | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.327 |
| 금요일 | Friday | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.90 |
| 급하다 | to be urgent | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.135 |
| 급행 | express (train or bus) | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.247 |
| 기념 | memory; commemoration | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.179 |
| 기다리다 | to wait | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.39,103 |
| 기도 | to pray | noun/verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.293 |
| 기르다 | to bring up; to raise | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.63 |
| 기름 | grease; oil | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.258 |
| 기분 | feelings | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.112 |
| 기쁘다 | to be glad | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.268 |
| 기사 | an engineer | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.213 |
| 기억하다 | to remember | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.201 |
| 기일 | a fixed date | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.251 |
| 기차 | a train | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.92 |
| 기침 | a cough | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.247 |
| 기회 | an opportunity, chance | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.297 |
| 길 | a street, a road | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.165 |
| 길다 | to be long | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.264 |
| 까맣다 | to be black | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.141 |
| 깨끗하다 | to be clean | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.135 |
| 깨다 | to wake up; to break | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.163 |
| 껍질 | peelings; a shell | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.310 |
| 꼬마 | a small child | noun | colloquial | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.217; informal/affectionate register for a child |
| 꼬리 | tail | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.210 |
| 꼭 | surely; exactly | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.224,140 |
| 꽃 | a flower | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.182 |
| 꽉 | completely | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.276 |
| 꽃꽂이 | flower arrangement | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.63; Lesson 79 "Hobbies" territory |
| 꾸다 | to borrow | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.283 |
| 꿀 | honey | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.325 |
| 끄다 | to turn off | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.200 |
| 끄떡이다 | to nod one's head | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.210 |
| 끊다 | to cut; to buy a ticket | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.170,241; idiomatic extension "cut a ticket" = buy a ticket |
| 끓다 | to boil (intransitive) | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.310 |
| 끓이다 | to make hot; to boil (transitive) | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.323 |
| 끝나다 | to be finished | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.128 |
| 끝내다 | to end; to make an end of | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.214 |
| 나가다 | to go out | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.238 |
| 나다 | to be born; to get sick | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.304 |
| 나무 | a tree | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.306 |
| 나물 | cooked vegetables | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.226 |
| 나쁘다 | to be bad | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.112 |
| 나오다 | to come out | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.177 |
| 나이 | age | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.215; Lesson 58 "Age" title term |
| 나중 | later | noun/adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.195 |
| 낚시 | fishing | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.220 |
| 날 | a day | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.90 |
| 날씨 | weather | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.82 |
| 남다 | to be left over | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.249 |
| 남매 | brother and sister | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.217 |
| 남자 | male | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.22 |
| 남편 | husband | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.36 |
| 낮잠 | a midday nap | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.310 |
| 낳다 | to give birth | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.217 |
| 내과 | internal medicine | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.323; Lesson 87/88 "Hospital"/"Physical Examination" territory |
| 내다 | to hand in; to pay | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.82 |
| 내리다 | to descend; to get off | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.103 |
| 내일 | tomorrow | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.81 |
| 냉수 | cold water | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.53 |
| 냉장고 | a refrigerator | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.163 |
| 너무 | excessive, too much | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.203 |
| 넉넉히 | sufficiently | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.255 |
| 넉넉하다 | to be enough | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.327 |
| 넓다 | to be wide | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.326 |
| 넣다 | to put in | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.228 |
| 년 | year | noun (bound/counter) | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.110 |
| 노랗다 | (is) yellow | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.141 |
| 노래 | a song | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.125 |
| 녹두묵 | green-pea gelatin | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.184; distinctive food-culture item |
| 놀다 | to play | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.203 |
| 농부 | a farmer | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.272 |
| 높다 | to be tall | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.135 |
| 누구 | who | pronoun (interrogative) | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.16 |
| 누나(누님) | older sister (of a male); honorific form in parens | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.125 |
| 눈 | eye; snow | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.149,201 |
| 눈물 | a tear | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.197 |
| 눕다 | to lie down | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.323 |
| 늘 | always | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.84 |
| 늦다 | to be late | descriptive/active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.253 |
| 다 | all; everything | adverb/noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.291 |
| 다과 | tea and cookies | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.201 |
| 다니다 | to attend (school, work) | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.215 |
| 다람쥐 | a chipmunk | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.242 |
| 다르다 | to be different | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.124 |
| 다리 | a bridge; a leg | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.320 |
| 다리미 | an iron (appliance) | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.154 |
| 다방 | tearoom | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.86; Lesson 62 "Tearoom" title term — 1980s Korean tearoom-culture vocabulary |
| 다시 | again | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.84 |
| 닦다 | to polish; to wipe clean | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.296 |
| -단 | a bundle; a bunch | classifier | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.184 |
| 단풍 | a maple (tree) | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.302; Lesson 84 "Autumn" territory |
| 닫다 | to close | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.283 |
| 닫히다 | to get closed; to be shut | active verb (passive) | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.283 |
| 달(월) | moon; month(s) | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.66,74 |
| 달다 | to weigh; to be sweet | descriptive/active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.170 |
| 닭 | a chicken | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.45 |
| 담배 | tobacco, cigarettes | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.53 |
| 당근 | a carrot | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.132 |
| -대 | car(s) | classifier | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.74 |
| 대다 | to touch; to provide | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.197 |
| 대단하다 | to be enormous | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.135 |
| 대단히 | very | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.135 |
| 대답 | an answer; a reply | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.238 |
| 대사관 | embassy | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.85 |
| 대접하다 | to treat; to entertain | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.272 |
| 대화 | conversation, dialogue | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.13 |
| 더 | more | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.177 |
| 더하다 | to add | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.289 |
| 덕분 | grace, favor | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.158 |
| 덜 | less | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.314 |
| 덥다 | to be hot (weather) | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.63 |
| 도서관 | a library | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.210 |
| 도시 | a city | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.136 |
| 도시락 | a lunch basket | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.279 |
| 도착하다 | to arrive | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.128 |
| 독서 | reading | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.279 |
| 돈 | money | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.97 |
| 돌다 | to turn | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.103 |
| 돌아가다 | to return | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.205 |
| -동 | an administrative unit (neighborhood) | classifier | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.253 |
| 동네 | a village | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.205 |
| 동생 | younger sibling | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.63 |
| 동전 | coins | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.131 |
| 되다 | to become | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.181 |
| 돼지고기 | pork | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.167 |
| -되 | a unit of volume | classifier | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.179; traditional Korean dry-measure unit |
| 두다 | to put into; to put | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.297 |
| 두부 | bean curd (tofu) | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.23 |
| 뒤 | later; the back | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.144 |
| 듣다 | to hear | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.118 |
| 들 | field | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.136 |
| 들다 | to eat or drink; to carry | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.97,281 |
| 들르다 | to drop in | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.259 |
| 들어가다 | to go in | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.217 |
| 등산 | mountain climbing | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.108; Lesson 79 "Hobbies" territory |
| 따뜻하다 | to be warm | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.286 |
| 따로 | separately | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.228 |
| 딸 | daughter | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.216 |
| 딸기 | strawberries | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.179 |
| 땀 | sweat | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.304 |
| 땅 | earth | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.310 |
| 땅콩 | a peanut | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.327 |
| 떠나다 | to leave | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.82 |
| 떠들다 | to make a noise | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.326 |
| 떨어지다 | to fall down | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.320 |
| 떫다 | to be puckery (astringent) | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.163 |
| 또 | again | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.12 |
| 뜨다 | to rise | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.200 |
| 뜯다 | to pull out; to pick | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.298 |
| -마 | a yard (91.44 cm) | classifier | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.170; pre-metric unit |
| 마르다 | to dry; to cut out | descriptive/active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.306 |
| -마리 | animal(s), fish (counter) | classifier | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.74 |
| 마지막 | the last; the end | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.238 |
| 마시다 | to drink | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.95 |
| 마중 | meeting; reception (at arrival) | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.262 |
| 막내 | the youngest | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.215 |
| 막차 | the last train or bus | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.251 |
| 만나다 | to meet | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.95 |
| 만년필 | a fountain pen | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.23 |
| 만두 | stuffed dumplings | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.97 |
| 만들다 | to make | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.123 |
| 많다 | to be many | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.96 |
| 맏이 | the firstborn (son) | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.216 |
| 말 | a horse; language | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.123 |
| 맑다 | to be clean, clear | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.308 |
| 말하다 | to speak, say | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.53 |
| 맛 | taste | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.162 |
| 맞다 | to be correct; to be agreeable | descriptive/active verb | core | — | contemporary | — | — | grammar_reference | n/a | low_confidence | pp.224,251; a scan artifact partially obscured the final jamo on re-check — reading is plausible but not fully certain |
| 매진 | sold out | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.249 |
| 맵다 | to be hot, pungent | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.163,219 |
| 머리 | head | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.264 |
| 먹 | Chinese ink (ink stick) | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.61; Lesson 13 "Brush Writing" (calligraphy) territory |
| 먹다 | to eat | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.31 |
| 먼지 | dust (gloss as printed: "head, first") | noun | core | — | contemporary | — | — | grammar_reference | n/a | low_confidence | p.81; printed English gloss ("head, first") does not match the standard meaning of this term (dust) — possible source typo or the Hangul is actually 먼저 "first," flagged rather than silently corrected |
| 멀다 | to be far, distant | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.212 |
| 멀미 | motion sickness | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.268 |
| 멋 | attractive; stylishness | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.161 |
| 며느리 | daughter-in-law | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.320 |
| 며칠 | a few days; day of the month | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.66,110 |
| 면회 | an interview | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.65 |
| 몇 | how many | determiner (interrogative) | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.65 |
| -모 | a cake (block, e.g. of tofu) | classifier | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.184 |
| 모두 | everybody, everything | pronoun/adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.181 |
| 모레 | the day after tomorrow | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.90 |
| 모르다 | to not know, not understand | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.123 |
| 모으다 | to collect | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.293 |
| 모자라다 | to be insufficient | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.255 |
| 목 | a neck | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.320 |
| 목사 | minister (Protestant) | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.115 |
| 목요일 | Thursday | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.91 |
| 목욕탕 | a bathhouse; a public bath | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.146,167 |
| 몸 | body | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.149 |
| 몸살 | general fatigue | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.322; Lesson 87/88 hospital territory |
| 못 | a nail | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.247 |
| 무겁다 | to be heavy | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.220 |
| 무덥다 | hot and humid | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.320 |
| 무엇 | what | pronoun (interrogative) | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.21,29 |
| 묵다 | to stay at (lodge) | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.284; Lesson 77/78 accommodations territory |
| 문 | a gate; a door | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.23 |
| 문장 | a composition | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.234 |
| 묻다 | to ask | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.79,249 |
| 물 | water | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.97 |
| 물건 | goods, things | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.161 |
| 물고기 | fresh-water fish | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.136 |
| 물론 | of course | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.107 |
| 미장원 | a beauty shop | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.167 |
| 믿다 | to believe | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.96 |
| 밀 | wheat | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.184 |
| 밀리다 | to be behind (schedule) | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.253 |
| 밉다 | to be hateful | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.220 |
| 밑 | the very bottom, under | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.144 |
| 바꾸다 | to change, exchange | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.131 |
| 바다 | sea; ocean | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.146 |
| 바닷가 | the seashore | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.108 |
| 바람 | wind, breeze | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.258,304 |
| 바로 | directly; the very | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.84,114 |
| 바른편 | the right-hand side | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.100 |
| 바쁘다 | to be busy | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.53,199 |
| 바지 | trousers | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.41 |
| 박물관 | a museum | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.112 |
| 박사 | doctor (Ph.D.) | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.56 |
| 반 | half | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.65 |
| 반갑다 | to be glad (to meet) | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.118 |
| 반찬 | side dishes | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.45 |
| 받다 | to receive | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.94 |
| 발 | a foot | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.149 |
| 발음 | pronunciation | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.161 |
| 밤 | chestnut; night | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.167 |
| 밥 | boiled rice | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.128 |
| 방 | a room | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.146 |
| 방금 | just now | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.84 |
| 방세 | rent for a room | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.255 |
| 방송국 | a broadcasting station | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.112 |
| 방학 | school vacation | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.108 |
| 배 | a pear; a ship, a boat | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.162 |
| 배달 | delivery (of goods) | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.253; Lesson 69 "Delivery Of Groceries" title term |
| 배우다 | to learn | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.29 |
| 배웅하다 | to see (a person) off | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.262; Lesson 73 "Parting" territory |
| 배표 | boat ticket | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.243 |
| 백반 | white (cooked) rice | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.230 |
| 백화점 | a department store | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.125 |
| 버선 | Korean socks (traditional) | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.220 |
| -번 | number | classifier | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.192 |
| 벌다 | to earn; to make (a profit) | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.226 |
| -벌 | a suit; a set | classifier | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.241 |
| 벌써 | already | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.177 |
| 벗다 | to take off (clothes) | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.140 |
| 벼루 | an inkstone | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.61; Lesson 13 calligraphy territory |
| 변호사 | a lawyer | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.115 |
| 별 | unnecessary; special | descriptive/adnominal | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.203 |
| 별로 | not particularly | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.148 |
| 병 | a sickness | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.320 |
| -병 | bottle(s) | classifier | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.74 |
| 병원 | hospital | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.319; Lesson 87 "Hospital" title term |
| 보내다 | to send; to spend time | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.304 |
| 보다 | to see | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.13 |
| 보람 | usefulness; worth | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.268 |
| 보리쌀 | barley (grain) | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.184 |
| 보리차 | barley tea | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.98 |
| 보통 | ordinary; usual | noun/adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.140 |
| 복숭아 | a peach | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.177 |
| 복습 | review | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.53 |
| 복잡하다 | to be complicated | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.283 |
| 본사 | a main office | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.272 |
| 봄 | spring | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.301; Lesson 82 "Spring" title term |
| -봉 | a paper bag | classifier | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.176 |
| 부끄럽다 | to be embarrassed, shy | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.220 |
| 부럽다 | to be envious | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.61 |
| 부르다 | to call; to be full | active/descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.68,162 |
| 부모 | parents | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.41,217 |
| 부엌 | kitchen | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.58 |
| 부인 | a married woman | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.14 |
| 부자 | rich | noun/adjective | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.182 |
| 부지런히 | diligently | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.167 |
| 부탁하다 | to request | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.51,186 |
| 부치다 | to send | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.268 |
| 부터 | from | particle | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.258 |
| -분 | person (honorific counter) | classifier | formal | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.16,65; honorific counter for people |
| 분필 | chalk | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.132 |
| 불 | fire | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.293 |
| 불고기 | Korean marinated beef | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.168 |
| 불다 | to blow | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.306 |
| 불편하다 | to be inconvenient, uncomfortable | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.161 |
| 붓글씨 | brush writing | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.61 |
| 비 | rain | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.82 |
| 비다 | to be empty | descriptive/active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.281 |
| 비싸다 | to be expensive | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.112 |
| 비서 | secretary | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.36 |
| 비행기 | an airplane | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.79 |
| 빌리다 | to lend | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.283 |
| 빠르다 | to be fast | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.124 |
| 밖 | the outside | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.50 |
| 빨갛다 | to be red | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.141 |
| 빨래하다 | to wash clothes | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.255,317 |
| 빨리 | quickly, fast | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.212 |
| 빵 | bread | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.82 |
| 뽑다 | to pull out; to select | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.63 |
| 뿌리다 | to sprinkle | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.272 |
| 사과 | an apple | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.72 |
| 사다 | to buy | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.41 |
| 사람 | person | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.96 |
| 사랑 | love | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.217 |
| 사무실 | office | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.58 |
| 사무원 | office worker | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.18 |
| 사월 | April | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.111 |
| 사이 | a space; social relationship | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.145 |
| 사장 | president (of a business) | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.18 |
| 사정 | circumstances | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.108 |
| 사진 | photograph; picture | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.96,213 |
| 산 | mountain | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.141 |
| -살 | years of age | classifier | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.215; native-Korean-number age counter |
| 살다 | to live | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.158 |
| 삼월 | March | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.111 |
| 새 | new; a bird | adnominal/noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.35,46 |
| 새다 | to leak out | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.91 |
| 새벽 | daybreak; dawn | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.251 |
| 색 | a color | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.115 |
| 생각 | thinking; thought | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.107 |
| 생강차 | ginger tea | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.229 |
| 생선 | (fresh) fish | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.170 |
| 생일 | birthday (familiar register) | noun | colloquial | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.91; glossary explicitly marks this "(familiar)" — honorific counterpart is 생신 |
| 생활 | life, livelihood | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.158; Lesson 41 "Living In Korea" territory |
| 서늘하다 | to be cool | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.302 |
| 서다 | to stand up | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.95 |
| 서당 | a Confucian (village) school | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.251; traditional-institution term |
| 서류 | a document | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.96 |
| 서양 | the West | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.140 |
| 서예 | brush writing, calligraphy | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.61 |
| 서투르다 | to be unskilled in | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.220 |
| 선물 | gift | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.259 |
| 선배 | one's senior (in school) | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.262 |
| 선불 | advance payment | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.97 |
| 선생 | teacher; sir; ma'am | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.12 |
| 선풍기 | an electric fan | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.154 |
| 설것이 | dishwashing | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.305; printed spelling as-scanned — modern standard orthography is 설거지, kept as the source prints it (older/variant spelling) |
| 설명 | explanation | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.302 |
| 설사 | to have diarrhea | noun/verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.320 |
| 설탕 | sugar | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.287 |
| 성냥 | matches | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.53 |
| 세수 | to wash (one's face and hands) | noun/verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.141 |
| 세우다 | to establish; to stop a car | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.100 |
| 세차 | car wash | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.259 |
| 소개하다 | to introduce | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.118,297 |
| 소금 | salt | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.272 |
| 소문 | rumor | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.205 |
| 소설 | a novel | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.31 |
| 소식 | news; information | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.268 |
| 소풍 | a picnic | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.279 |
| 소화불량 | indigestion | noun | technical.medical | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.174,223,323; Lesson 46 "Buying Medicine" / 87–88 hospital territory |
| 속 | the inside | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.144 |
| 속히 | quickly, rapidly | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.243 |
| 손님 | guest | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.18 |
| 손수건 | a handkerchief | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.146 |
| 쇠고기 | beef | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.167 |
| 수녀 | a Catholic nun | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.298 |
| 수리하다 | to repair | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.201 |
| 수박 | watermelon | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.179 |
| 수속 | procedures, formalities | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.266 |
| 수술비 | charges for surgery | noun | technical.medical | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.58,323 |
| 수업 | teaching; instruction | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.68 |
| 수영 | swimming | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.108 |
| 수요일 | Wednesday | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.91 |
| 수집하다 | to collect | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.298 |
| 수표 | a check (money) | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.132 |
| 숙박하다 | to lodge | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.281,286 |
| 숙제 | homework | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.41 |
| 숟가락 | a spoon | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.268 |
| 쉬다 | to rest | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.108 |
| 쉽다 | to be easy | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.63 |
| 슬프다 | to be sad | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.200 |
| -시 | o'clock | classifier | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.65 |
| 시간 | an hour, time | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.65 |
| 시계 | a watch, clock | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.36 |
| 시골 | countryside | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.136 |
| 시금치 | spinach | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.132 |
| 시내 | downtown | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.86 |
| 시다 | to be sour | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.163 |
| 시설 | equipment; facilities | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.136,281 |
| 시아버지 | father-in-law | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.320 |
| 시원하다 | to be refreshing | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.302 |
| 시월 | October | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.111 |
| 시외 | the suburbs | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.213 |
| 시작하다 | to start | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.82 |
| 시장 | a market; a mayor | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.75 |
| 시키다 | to order (something done) | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.228 |
| 시험 | test | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.277 |
| 식구 | a family; mouths to feed | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.125 |
| 식다 | to cool off | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.162 |
| 식당 | dining room; restaurant | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.86 |
| 식빵 | bread (loaf) | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.132 |
| 식사 | a meal | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.68,97 |
| 식탁 | a dining table | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.259 |
| 신 | shoes | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.217 |
| 신경통 | neuralgia (gloss as printed: "a nervous breakdown") | noun | technical.medical | — | contemporary | — | — | grammar_reference | n/a | low_confidence | p.323; printed English gloss is a loose/period translation that doesn't match the standard clinical meaning (neuralgia); kept as printed with correction noted rather than silently substituted |
| 신다 | to put on one's foot (shoes) | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.217 |
| 신문 | newspaper | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.46 |
| 신부 | a Catholic priest | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.298 |
| 신호 | a signal | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.270 |
| 싣다 | to load; to carry goods | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.250 |
| 싫다 | to dislike | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.141 |
| 실컷 | to one's heart's content | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.325 |
| 심부름 | an errand | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.229 |
| 심심하다 | to be bored | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.306 |
| 싱겁다 | to be insipid (bland) | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.163 |
| 싸다 | to be cheap | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.152 |
| 쌀 | rice (uncooked) | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.184 |
| 쌀쌀하다 | to be chilly | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.302 |
| 썩다 | to go bad; to putrefy | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.201 |
| 썰다 | to cut up, shred | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.168 |
| 쑤시다 | to throb with pain | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.149 |
| 쓰다 | to write; to use | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.276 |
| 쓰레기통 | a garbage can | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.146 |
| -씨 | Mr., Mrs., Miss | suffix (title) | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.114 |
| 씹다 | to chew | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.63 |
| 아가씨 | a young lady | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.228 |
| 아까 | a little while ago | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.166 |
| 아내 | wife | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.40 |
| 아들 | son | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.216 |
| 아름답다 | to be beautiful, pretty | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.119 |
| 아래 | the bottom; under side | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.144 |
| 아마 | perhaps, maybe | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.301 |
| 아무도 | any person (+ negative) | pronoun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.283 |
| 아무튼 | anyhow | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.237 |
| 아버지 | father | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.18 |
| 아이 | child | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.107 |
| 아이들 | children | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.41 |
| 아저씨 | uncle (term of address) | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.13 |
| 아주 | very | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.158 |
| 아직 | yet, as yet, still | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.203 |
| 아침 | morning; breakfast | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.92 |
| 아프다 | to feel pain; to be sick | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.53 |
| 안 | the inside, the interior | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.145 |
| 안경 | glasses; eyeglasses | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.36 |
| 안내 | guidance | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.213,214 |
| 안부 | regard(s) | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.31; Lesson 17 "Greetings And Regards" territory |
| 앉다 | to sit down | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.118 |
| 안심하다 | to feel easy; to feel at rest | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.210 |
| 알다 | to know, to understand | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.123; Lesson 31 "Do You Know Korean?" title term |
| 앞 | the front; the future | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.144 |
| 애기 | baby | noun | colloquial | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.115; colloquial contraction of 아기 |
| 애인 | sweetheart | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.149 |
| 약 | medicine | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.149,174; Lesson 46 "Buying Medicine" title term |
| 약방 | a pharmacy, drugstore (gloss as printed: "buying medicine") | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.174; source glosses this with the Lesson 46 title phrase rather than the dictionary meaning; standard meaning is "pharmacy/drugstore," kept as printed with the discrepancy noted |
| 약속 | promise | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.201 |
| 양말 | socks | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.132 |
| 상치 | lettuce | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.181; printed spelling as-scanned — modern standard orthography is 상추, kept as the source prints it |
| 양파 | an onion | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.167 |
| 어느 | which | pronoun (interrogative) | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.102 |
| 어디 | where; well, now | adverb (interrogative) | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.9 |
| 어떻다 | how, in what manner | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.140 |
| 어떻든 | anyhow; anyway | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.236,237 |
| 어둡다 | to be dark | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.91 |
| 어렵다 | to be difficult | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.119 |
| 어른 | an adult, a grown-up | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.45 |
| 어리다 | to be young | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.217 |
| 어머니 | mother | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.17 |
| 어서 | quickly; please | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.114 |
| 어제 | yesterday | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.90 |
| 언니 | older sister (of a female) | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.63 |
| 언어 | language | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.310 |
| 언제 | when | adverb (interrogative) | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.94 |
| 얻다 | to get, to receive | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.268 |
| 엉터리 | a fake; a quack | noun | colloquial | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.279 |
| 얼마 | how much | pronoun (interrogative) | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.72; Lesson 33 "How Much Is It?" title term |
| 얼음 | ice | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.183 |
| 없다 | to not be; there is not | existential verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.44 |
| 여관 | inn | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.281; Lesson 78 "An Inn" title term |
| 여권 | a passport | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.251 |
| 여기 | here, this place | pronoun (demonstrative) | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.57 |
| 여러 가지 | many, various | determiner/adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.289 |
| 여름 | summer | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.302; Lesson 83 "Summer" title term |
| 여자 | a female, woman | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.136 |
| 여행 | trip, journey | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.271 |
| -역 | a railroad station | classifier/bound noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.213 |
| 역사 | history | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.125 |
| 연락하다 | to contact | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.197,238 |
| 연말 | the year's end | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.279 |
| 연세 | age; years (honorific) | noun | formal | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.215; honorific of 나이 |
| 연습하다 | to exercise, practice | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.13 |
| 연필 | pencil | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.23 |
| 연하장 | a New Year's card | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.179 |
| 열 | temperature (fever) | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.319 |
| 열리다 | to be opened | active verb (passive) | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.283 |
| 열심히 | eagerly | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.268 |
| 열차 | a train | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.247 |
| 염려하다 | to be anxious; to worry | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.226 |
| 엽서 | post card | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.268 |
| 영어 | English | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.41 |
| 영수증 | receipt | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.258 |
| 영한사전 | an English-Korean dictionary | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.46 |
| 옆 | the side; beside, near | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.145 |
| 예매 | advance sale | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.249 |
| 예배 | worship; service | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.247 |
| 예쁘다 | to be pretty | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.170 |
| 예약하다 | to make a booking | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.276; Lesson 76 "Hotel Reservation" title term |
| 오늘 | today | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.90,91 |
| 오다 | to come | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.95 |
| 오락 | recreation | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.136 |
| 오빠 | older brother (of a female) | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.125 |
| 오월 | May | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.110 |
| 오전 | in the morning; A.M. | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.166 |
| 오후 | afternoon; P.M. | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.165 |
| 온도 | temperature | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.286 |
| 온돌방 | ondol (heated-floor) room | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.286; culturally specific Korean architecture term |
| 올해 | this year | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.325 |
| 옷 | clothes, garments | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.267 |
| 완행 | local (train or bus) | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.213 |
| 외국 | foreign country | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.161 |
| 외과 | surgery (dept.) | noun | technical.medical | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.323 |
| 외무부 | the Ministry of Foreign Affairs | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.56 |
| 외우다 | to memorize | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.326 |
| 외출하다 | to go out (of doors) | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.197 |
| 요금 | fee, fare | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.100 |
| 요리 | cooking | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.194 |
| 요일 | day (of the week) | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.90 |
| 요즘 | these days | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.29; Lesson 6 "What?" dialogue opener term |
| 용감하다 | to be brave | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.210 |
| 우리 | we, us | pronoun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.17 |
| 우산 | umbrella | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.34 |
| 우유 | milk | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.287 |
| 우체국 | post office | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.209 |
| 우표 | postage stamp | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.132 |
| 운동 | sports, physical movement | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.31,210 |
| 운동화 | sports shoes | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.41 |
| 운반하다 | to carry | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.255 |
| 운전하다 | to drive | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.213 |
| 울다 | to cry | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.124 |
| -원 | Korean money (won) | classifier | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.72 |
| 원고 | manuscript | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.92 |
| 월말 | the end of the month | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.279 |
| 월요일 | Monday | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.91 |
| 위 | the top side | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.144 |
| 위치 | a position | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.144 |
| 유월 | June | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.111 |
| 유자 | a citron | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.229 |
| 유학 | studying abroad | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.264 |
| 은행 | a bank | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.136 |
| 음료수 | drinking water; a beverage | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.176 |
| 음식 | food; a meal | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.31 |
| 음식점 | a restaurant | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.92 |
| 음악 | music | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.175 |
| 의견 | an opinion; a view | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.108 |
| 의사 | medical doctor | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.18 |
| 의자 | a chair | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.23 |
| 이 | a tooth | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.320 |
| 이다 | to be (identity, copula) | copula | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.16 |
| 이따 | after a while, a little later | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.165 |
| 이렇다 | to be like this | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.53 |
| 이름 | a name | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.112 |
| 이르다 | to be early | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.205 |
| 이맘때 | about this time (of year) | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.322 |
| 이민 | immigration | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.264 |
| 이발 | a haircut | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.259,167 |
| 이사하다 | to move house | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.298 |
| 이사장 | the chairman of a board of directors | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.162 |
| 이상하다 | to be strange | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.317 |
| 이웃 | neighborhood; neighbor | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.149 |
| 이월 | February | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.111 |
| 이유 | reason | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.264 |
| 익숙하다 | to be familiar with; skilled in | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.158 |
| 인사 | greeting | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.9; Lesson 1/2 "Greetings"/"Thanks" territory |
| 인삼 | ginseng | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.194 |
| 일 | day; work | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.56 |
| 읽다 | to read | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.31 |
| 일어나다 | to arise | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.127; Lesson 32 "Getting Up In The Morning" title term |
| 일요일 | Sunday | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.91 |
| 일찍 | early | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.165 |
| 일하다 | to do work | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.95 |
| 입다 | to get dressed; to wear | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.63,214 |
| 입국수속 | formalities for entry | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.268 |
| 있다 | to be; to exist; to have | existential verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.44 |
| 잎 | a leaf | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.306 |
| 자 | a rule (ruler) | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.144 |
| -자 | a unit of length (ca.) | classifier | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.170; traditional unit |
| 자꾸 | continuously | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.270 |
| 자기 | one's self | pronoun (reflexive) | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.118,272 |
| 자다 | to sleep | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.58 |
| 자동차 | a car | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.79 |
| 자두 | plum | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.327 |
| 자랑스럽다 | to be proud | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.293 |
| -자루 | pencil(s), brush(es) | classifier | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.74 |
| 자르다 | to cut off | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.170 |
| 자리 | a seat; one's place | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.188 |
| 자전거 | a bicycle | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.132 |
| 자주 | often | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.203 |
| 작다 | to be small | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.232 |
| 작별 | leave-taking | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.203; Lesson 54 "Farewell" territory |
| 잔 | a cup, a glass | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.74 |
| 잔돈 | small change | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.131 |
| 잘 | carefully; well | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.77 |
| 잠 | sleep | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.58 |
| 잠깐 | a moment | noun/adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.39 |
| 잠옷 | night clothes | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.214 |
| 잡다 | to catch | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.210 |
| 잡담 | small talk | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.325; Lesson 89 "Small Talk" title term |
| 잡비 | sundry expenses | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.289 |
| 잡수시다 | to eat (honorific) | active verb | formal | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.31; honorific of 먹다 |
| 잡지 | magazine | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.23 |
| -장 | sheet(s) | classifier | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.74 |
| 장갑 | gloves | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.46 |
| 장기 | Korean chess (janggi) | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.298; note: the glossary lists 장기 (janggi) rather than 바둑 (paduk/Go) despite Lesson 81's title being "Paduk" — the lesson-specific game term did not appear in this consolidated glossary and was not separately vision-verified |
| 장마철 | the rainy season | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.317 |
| 재미있다 | to be interesting | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.29 |
| 재주 | ability, talent, gifts | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.293 |
| 저기 | over there | pronoun (demonstrative) | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.9 |
| 저녁 | supper; evening | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.67 |
| 저렇다 | to be like that | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.53 |
| 전공 | major course of study | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.234 |
| 전망 | a view; an outlook | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.289 |
| 전보 | telegram | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.96 |
| 전철 | an electric railway | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.243 |
| 전하다 | to convey; to pass on | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.268 |
| 전화 | telephone | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.39,194 |
| 점심 | lunch | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.65 |
| 접시 | a plate | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.310 |
| 정각 | the exact time | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.128 |
| 정구 | tennis | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.31 |
| 정류장 | bus stop | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.212 |
| 정말 | truly | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.203 |
| 정육점 | meat market | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.165; Lesson 44 "Meat Market" title term |
| 젖다 | to get wet | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.310 |
| 조금 | a little | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.51,84 |
| 조용하다 | to be quiet | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.286 |
| 졸다 | to doze, drowse | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.306 |
| 졸리다 | to grow sleepy | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.306 |
| 졸업하다 | to graduate | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.119 |
| 종이 | paper | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.144 |
| 좋다 | to be good | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.95 |
| 좋아하다 | to like | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.219 |
| 주다 | to give | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.72 |
| 주말 | weekend | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.108 |
| 주머니 | a purse; a pocket | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.146 |
| 주무시다 | to sleep (honorific) | active verb | formal | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.79; honorific of 자다 |
| 주문하다 | to order | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.97,255; Lesson 23 "Ordering Dinner" territory |
| 주인 | the owner; the master | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.18 |
| 주일 | Sunday; week(s) | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.92 |
| 주유소 | a gas station | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.258; Lesson 71 "Gas Station" title term |
| 주전자 | a kettle | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.310 |
| 주차장 | a car park | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.213 |
| 죽 | gruel | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.323 |
| 준비 | preparation | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.327 |
| 즐겁다 | to be delighted | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.63 |
| 지갑 | a purse | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.36 |
| 지금 | now; just now | noun/adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.84,94 |
| 지난해 | last year | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.317 |
| 지내다 | to spend one's time | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.77 |
| 지리 | geography | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.82 |
| 지루하다 | to be bored | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.306 |
| 지방 | a locality; a district | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.136 |
| 지사 | a branch office | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.272 |
| 지우개 | eraser | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.144 |
| 지키다 | to watch; to keep (a promise) | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.234 |
| 직업 | one's occupation | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.234 |
| 직원 | the staff | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.148 |
| 직장 | one's place of work | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.233 |
| 직행 | express (bus) | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.213 |
| 진찰하다 | to have a medical examination | active verb | technical.medical | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.319; Lesson 88 "Physical Examination" title term |
| 질문하다 | to question | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.163 |
| 짐 | a load; baggage | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.220 |
| 집 | house, home | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.84 |
| 집다 | to pick up; to take up | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.63 |
| 짜다 | to be salty | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.163 |
| -쪽 | a side; a piece | classifier | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.100 |
| 찍다 | to stamp; to take a photograph | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.96 |
| 찢다 | to tear | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.247 |
| -쯤 | approximately | suffix | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.152 |
| 차 | tea; car | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.228 |
| 차다 | filled up | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.276 |
| 차장 | bus conductor | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.213 |
| 참다 | to endure; be patient | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.112 |
| 참외 | a melon | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.179 |
| 창구 | a (ticket) window | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.241; Lesson 68 "Advance Ticket Sales Window" title term |
| 창문 | window | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.23 |
| 찾다 | to look for; to find | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.114 |
| 채소 | vegetables | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.181; Lesson 48 "Vegetable Market" territory |
| 책 | book | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.16 |
| 책방 | a bookstore | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.259 |
| 책상 | desk | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.23 |
| 책임 | responsibility | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.268 |
| 처음 | the first time | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.118,224 |
| 천천히 | slowly | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.243 |
| 철 | a season | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.308 |
| 첫차 | first train | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.249 |
| 청소 | to clean | noun/verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.51 |
| 체육관 | a gymnasium | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.210 |
| 초대 | invitation | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.199; Lesson 53 "Dinner Invitation" title term |
| 초저녁 | early evening | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.205 |
| 초하루 | the first day (of the month) | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.288 |
| 총장 | president (of a university) | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.39 |
| 추수 | harvesting | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.292; Lesson 84 "Autumn" territory |
| 출국 | departure from a country | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.266 |
| 출근하다 | to go to work | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.128 |
| 출발하다 | to depart, leave | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.245 |
| 출장 | an official (business) trip | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.293 |
| 춤 | a dance | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.220 |
| 춥다 | to be cold (weather) | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.119 |
| 취미 | a hobby, interest | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.291; Lesson 79 "Hobbies" title term |
| 취직하다 | to get a job | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.154 |
| 치다 | to hit; to play (an instrument/game) | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.230 |
| 치료 | a medical treatment | noun | technical.medical | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.322 |
| 치약 | toothpaste | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.115 |
| 친구 | friends | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.134; Lesson 34 "Korean Friends" title term |
| 친절하다 | to be kind | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.289 |
| 친척 | relative(s) | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.232 |
| 칠월 | July | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.111 |
| 칠판 | blackboard | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.146 |
| 침대 | a bed | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.98 |
| 칫솔 | a toothbrush | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.126 |
| 칭찬하다 | to praise | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.317 |
| 켤레 | pair(s) | classifier | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.74 |
| 크다 | to be big | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.200 |
| 코끼리 | an elephant | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.197 |
| 콩나물 | bean sprouts | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.21 |
| 타다 | to ride | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.132 |
| 탑승하다 | to ride; to board | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.266; Lesson 72 "Airport" territory |
| 택시 | a taxi | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.85 |
| 토끼 | a rabbit | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.45 |
| 토요일 | Saturday | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.90 |
| 토큰 | (bus/subway) token | noun | core | — | contemporary | — | — | grammar_reference | n/a | low_confidence | p.213; glossary's printed English gloss reads simply "taken," which looks like a truncation/typo of "token" (this is a Korean loanword from English "token" for bus fare); kept as printed with correction noted |
| 통근버스 | a commuter bus | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.274 |
| 통화 | a phone call | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.270; Lesson 74 "The Line's Busy" territory |
| 퇴근 | leaving one's office | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.68 |
| 특급 | express (train) | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.251 |
| 튼튼하다 | to be strong | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.170 |
| 틈(짬) | spare time; space | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.293 |
| 파 | a green onion | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.205 |
| 파랗다 | to be blue | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.141 |
| 파리 | a fly; Paris | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.123 |
| 팔다 | to sell | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.177 |
| 팔월 | August | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.111 |
| 퍽 | very, quite | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.158 |
| 편이다 | to be on the side of | copula construction | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.314 |
| 편지 | a letter | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.201 |
| 편찮다 | to be unwell (honorific) | descriptive verb | formal | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.319; honorific of 아프다 |
| 편리하다 | to be convenient | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.161 |
| 편하다 | to be comfortable | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.286 |
| 포도 | grapes | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.25 |
| 표 | ticket | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.210 |
| 푹 | deeply | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.322 |
| 풀 | paste; starch | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.136,144 |
| 풀리다 | to warm up; to relax | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.314 |
| 풍습 | customs | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.140; Lesson 36 "Strange Customs" title term |
| 피곤하다 | to be tired | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.51 |
| 피다 | to bloom | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.301 |
| 피리 | a flute | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.63 |
| 피서 | escaping the summer (heat) | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.304 |
| 피우다 | to smoke | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.217 |
| 필요하다 | to be necessary | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.44 |
| 하늘 | sky | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.308 |
| 하다 | to do | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.9 |
| 하숙방 | a rented room (boarding) | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.161 |
| 하얗다 | to be white | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.141 |
| 하품 | yawn | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.271 |
| 학교 | school | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.36 |
| 학생 | a student | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.16 |
| 한가하다 | to have spare time | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.306 |
| 한영사전 | a Korean-English dictionary | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.46 |
| 한자 | a Chinese character | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.82 |
| 한턱내다 | to give a treat | active verb | colloquial | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.238; fixed colloquial idiom ("to foot the bill/treat everyone") |
| 할아버지 | grandfather | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.13 |
| 할머니 | grandmother | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.36 |
| 합승 | riding together (shared taxi/ride) | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.210; 1980s Korean shared-taxi culture term |
| 해결하다 | to solve | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.158 |
| -행 | destined for, headed for | suffix | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.241 |
| 헤어지다 | to part | active verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.266; Lesson 73 "Parting" title term |
| 현관 | entrance hall; lobby | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.119,236 |
| 현금 | cash; ready money | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.132 |
| 형 | older brother (of a male) | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.63 |
| 형제 | brothers and sister(s) | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.216 |
| -호 | a house number | classifier | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.253 |
| 호랑이 | a tiger | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.210 |
| 혼선 | entanglement of telephone wires (crossed line) | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.272; Lesson 52 "Another Phone Call" territory |
| 혼자 | alone | adverb/noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.220 |
| 홍차 | black tea | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pp.188,220 |
| 화가 나다 | to get angry | verb phrase | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.163 |
| 화선지 | Oriental calligraphy paper | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.61 |
| 화요일 | Tuesday | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.91 |
| 화장실 | a restroom | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.115 |
| 횟감 | material for raw fish (sashimi ingredients) | noun | core | — | contemporary | — | — | grammar_reference | n/a | low_confidence | p.170; glossary shows this without the expected sai-siot (printed as 회감); standard orthography is 횟감, flagged rather than silently normalized |
| 회사 | a business company | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.58 |
| 회의 | a meeting | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.56 |
| -후 | after, later | suffix | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.152 |
| 훌륭하다 | to be splendid | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.243 |
| 휘발유 | volatile oil; gasoline | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.259 |
| 휴가 | vacation, furlough | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.107 |
| 휴일 | holiday | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.90 |
| 휴지 | toilet paper | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.53 |
| 휴지통 | wastebasket | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.146 |
| 흉내 | mimicry; imitation | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.243 |
| 흐리다 | to be cloudy | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.283 |
| 힘들다 | to be strenuous | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | p.53 |

## Grammar points

Per the coverage note above, the overwhelming majority of this book's grammar content (particles,
honorific/humble pairing, speech levels, tense/aspect, sentence-final endings) duplicates material
already captured across 10–46+ prior established Korean files and is not re-extracted here. The
following points are the genuinely distinctive content this source adds.

### The author's "insert" terminology for pre-final verb-stem suffixes

Chang's Introduction (Table 6, p.7) explicitly coins his own pedagogical term for what Korean
linguistics conventionally treats as a helping-stem morpheme (the author's own romanization: "ogan")
inserted between the verb stem and the verb ending — he writes that he "has chosen to call it an
**insert**, since it is placed between the main verb stem and the verb ending," rather than use
standard linguistic jargon. The book then names four specific inserts by this label, each discussed
in its own numbered grammar note across the lessons:

- **Honorific insert** -시- (Note 56 and others) — "regardless of the verb stem, when the honorific
  insert is used" it precedes the verb ending; morphologically identical to the honorific -시- already
  documented in every other established Korean source, just under this book's own name for it.
- **Past tense insert** -았/었/였- (Note 70).
- **Future tense insert** -겠- (Note 59) — the grammar note explicitly says the author uses "the term
  insert in order to emphasize the fact that it is inserted" between stem and ending, and separately
  notes scholars have also analyzed this morpheme differently elsewhere.
- **Retrospective insert** -더- (Note, later lessons) — described as used "when the speaker looks back
  on past events," taking the 3rd person as its typical subject in the lesson's examples. This
  retrospective/evidential function is already well documented across 11 prior established files, so
  only the terminology is new here, not the underlying grammar.

This is worth recording specifically because it's an idiosyncratic author-specific framing device —
a single unifying label ("insert") for four morphosyntactically different suffix categories that
other sources in this corpus each name and analyze separately — rather than new grammatical content.

### Simplified three-way sentence-style framework (Formal / Informal / Plain)

The Introduction's Table 6 ("Examples of Verb Endings," p.7) organizes all verb-ending paradigms
under just three labeled columns — **Formal Style**, **Informal Style**, and **Plain Style** — each
further cross-cut by the five sentence moods (declarative, interrogative, imperative, propositive,
exclamatory). This is a coarser three-way simplification than the six-or-more-level honorific/speech
taxonomies used by most other sources in this corpus (already the project's flagship Korean finding).
It's noted here as this particular pedagogical source's own simplification choice for a beginner
audience, not as new grammatical content — the underlying forms it tabulates are standard.

### Scholarly-citation parts-of-speech taxonomy

Table 4 ("Korean Parts of Speech," p.5) is unusual among this project's Korean course-book sources
for citing three named Korean grammarians by year for its 11-category classification: Pak Ch'ang-hae
(1965) for the Active-Verb/Descriptive-Verb/Copula split, Choi Hyon-bae (1971), and Yi Hui-sung
(1955) for the Connectives category, attributed collectively to "the work of the Hakkyo Munbup Simui
Uiwonhoe" (a school-grammar standardization committee). The 11 categories themselves (Nouns,
Pronouns, Numerals, Active Verbs, Adjectives/Descriptive Verbs, Copula, Prenouns, Adverbs,
Particles, Exclamations, Connectives) match the standard Korean school-grammar inventory already
implicit across this project's other sources; what's distinctive is the explicit academic citation
trail, which no other extracted Korean source in this corpus reproduces this directly.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`. The Vocabulary table
above reproduces the book's own back-of-book glossary (headword + short English gloss + page
citation) rather than dialogue or explanatory prose; this is consistent with how every other
established Korean file in this project extracts vocabulary-list content.
