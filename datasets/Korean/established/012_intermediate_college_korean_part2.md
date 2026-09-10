# Korean — Intermediate College Korean, Part 2 (Lessons 17-end)

**Source:** *Intermediate College Korean* (10.Intermediate college Korean.pdf), PDF pages 191-376
of 376 (second half, through the end of the book). Printed page = PDF page − 21 (verified at
multiple points: PDF 191 = printed 170, PDF 199 = printed 178, PDF 207 = printed 186). A sibling
chunk (`established/011_intermediate_college_korean_part1.md`) covers PDF pages 1-190 — not yet
landed at the time of writing, so no direct cross-check against it was possible; this file's own
internal lesson numbering (Lesson 17 onward) implies the part-1 chunk covers Lessons 1-16 (or
however far the front half reaches).

**PDF gotcha (new type, distinct from the Wave-1 `+36266` cipher):** this book's Hangul is set in
several subsetted Type1/CFF fonts (`KHMyungjoRegularB0`-`B9`, `A4`, etc., one subset font per
glyph-range chunk) with a **per-glyph custom Encoding**, not a fixed numeric codepoint offset —
`pdftotext`/PyMuPDF's default extraction renders every Hangul character as an unrelated Latin
accented-letter/symbol glyph (e.g. printed page 170's text decodes to strings like `œ∑üL Âa Ωg`).
This is not a clean modular-offset cipher like the `+36266` case documented for other Korean books
in this project — it needed per-font glyph-name reverse-engineering that wasn't tractable in the
time available, so **all Hangul content in this file was vision-read from 200dpi page-image
renders**, cross-checked against the book's own parallel English glosses (which decode perfectly
via `pdftotext`, since the English text uses an unaffected Latin font). No handwritten marginalia
was found anywhere in the range.

**Non-redundant-supplement dispatch:** this book covers intermediate/advanced grammar territory
that partially overlaps `established/003`-`004` (*Intermediate Korean*, Byon) and
`established/005`-`007` (*Continuing Korean*). Given the vision-reading cost of this particular
source (see above), this chunk prioritizes **full extraction of every grammar point and vocabulary
item actually encountered** (per the coverage rule) rather than attempting a redundancy diff
against those other 700+-entry vocabulary sets — the grammar constructions and reading-passage
vocabulary here are largely book-specific pattern presentations (own worked examples, own
lesson-numbering, own vocabulary selection) even where the underlying grammatical territory (e.g.
`-거든(요)`, causative-verb suffixes, quotation forms) is familiar ground. Real overlap is flagged
inline where a construction is essentially identical to one already fully tabulated in a sibling
file (e.g. the causative-suffix system, already covered in Basic/Intermediate Korean's `-이/히/리/기`
material — the fuller chart here is kept because it adds several verb-base entries and example
sentences not in the shorter prior treatment). **Exercise/drill sections (교체연습/문형연습 fill-in and
transformation drills) are not transcribed** — per the coverage rule, these reuse vocabulary/grammar
already captured from the same lesson's Vocabulary and Patterns-and-Grammar-Notes sections and add
no new lexical or grammatical content, only more practice instances. Reading-passage dialogue prose
is paraphrased/summarized rather than transcribed in full, per copyright discipline.

---

## Vocabulary

### Lesson 17 — 대통령 선거 "Presidential Election" (tail end: grammar points 5-7, p. 170-172)

No new vocabulary section in this range (Lesson 17's own Vocabulary section falls in the part-1
chunk's page range); grammar points 5-7 (see below) introduce these lexical items via their own
worked examples:

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 동안(에) | while, during | postposition (after noun/modifier) | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 170, grammar pt. 5 (A.V. + -는 동안(에)). |
| 대신(에) | instead of, in place of | noun/postposition | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 170, grammar pt. 6; literally "substitution/proxy/surrogate." |

### Causative verbs chart (Lesson 17, p. 171-172) — morphological supplement

A systematic causative-suffix chart, organized by the suffix added to the verb base: **-이-, -히-,
-리-, -기-, -우-, -구-, -추-**. This is the same general causative system already tabulated in
`established/002_basic_korean_part2.md`/`established/003_intermediate_korean_part1.md`, but this
book's chart adds several base/causative pairs not previously captured:

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 줄이다 | to shrink, to reduce (caus.) | verb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | 줄다 "to shrink" + -이-. |
| 높이다 | to raise, to make tall (caus.) | verb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | 높다 "to be high" + -이-. |
| 녹이다 | to melt (caus.) | verb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | 녹다 "to melt (itself)" + -이-. |
| 넓히다 | to widen (caus.) | verb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | 넓다 "to be wide" + -히-. |
| 익히다 | to cook, to make ripe (caus.) | verb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | 익다 "to be cooked/ripe" + -히-. |
| 식히다 | to cool (something) off (caus.) | verb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | 식다 "to cool off (itself)" + -히-. |
| 알리다 | to let be known (caus.) | verb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | 알다 "to know" + -리-. |
| 돌리다 | to turn (caus.) | verb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | 돌다 "to go around" + -리-. |
| 늘리다 | to increase (caus.) | verb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | 늘다 "to increase (itself)" + -리-; contrast 늘이다 "to lengthen" (Lesson 17 exercise C.4.j). |
| 맡기다 | to entrust, to check (caus.) | verb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | 맡다 "to keep/be in charge of" + -기-. |
| 벗기다 | to undress, to strip (caus.) | verb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | 벗다 "to take off" + -기-. |
| 신기다 | to put shoes on (someone) (caus.) | verb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | 신다 "to put on (shoes)" + -기-. |
| 숨기다 | to hide, to conceal (caus.) | verb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | 숨다 "to hide (oneself)" + -기-. |
| 씻기다 | to let (someone) wash (caus.) | verb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | 씻다 "to wash" + -기-. |
| 빗기다 | to comb (someone's hair) (caus.) | verb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | 빗다 "to comb" + -기-. |
| 재우다 | to put to bed (caus.) | verb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | 자다 "to sleep" + -우-. |
| 깨우다 | to wake (someone) (caus.) | verb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | 깨다 "to be awake" + -우-. |
| 태우다 | to load, to give a ride (caus.) | verb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | 타다 "to ride" + -우-. |
| 세우다 | to stop, to erect (caus.) | verb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | 서다 "to stand/stop" + -우-. |
| 비우다 | to vacate, to empty (caus.) | verb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | 비다 "to be empty" + -우-. |
| 돋구다 | to enhance, to sharpen (caus.) | verb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | 돋다 "to rise/sprout" + -구-; the source's own example: 운동은 밥맛을 돋구어 준다 "Exercise enhances one's appetite." |
| 낮추다 | to lower (caus.) | verb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | 낮다 "to be low" + -추-. |
| 늦추다 | to extend, to defer (caus.) | verb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | 늦다 "to be late" + -추-. |
| 맞추다 | to set, to match, to fit (caus.) | verb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | 맞다 "to fit/be correct" + -추-. |

### Lesson 18 — 홍길동 "Hong Kil-dong" (p. 176-185)

Reading passage retells the classical novel *The Tale of Hong Kil-dong* (Hŏ Kyun, c. 1569-1618),
introduced via a dialogue between two students; the book's own footnote gives brief historical
context (Hŏ Kyun's execution for social criticism, his sister the poet Hŏ Nansŏrhŏn). Paraphrased,
not transcribed, per copyright discipline.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가난하다 | to be poor | verb (descriptive) | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 179. |
| 거절하다 | to refuse | verb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 179. |
| 결국 | finally, in the end | adverb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 179. |
| 관리 [괄리] | bureaucrat, government official | noun | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 179; bracketed pronunciation note for a liaison/assimilation effect. |
| 관직 | government position | noun | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 179. |
| 그러다가 | while doing so, meanwhile | conjunctive adverb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 179. |
| 나누어 주다 | to distribute | verb phrase | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 179. |
| 나쁜 / 나쁘다 | bad, wicked / to be bad | adjective / verb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 179. |
| 다스리다 | to govern, to rule | verb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 179. |
| 데리고 | accompanying | verbal adverb (from 데리다) | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 179. |
| 도둑; 도적 | thief, burglar | noun | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 179; 도둑질하다 "to steal" given as a derived form. |
| 명령 [명녕] | order, command | noun | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 179; 명령을 내리다 "to order, to command." |
| 모아 두다 | to accumulate | verb phrase | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 179. |
| 불만 | discontent | noun | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 179; 불만을 품다 "to be discontent, to harbor a grudge." |
| 빼앗다 | to snatch, to take away | verb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 180. |
| 온 | all, entire | prenoun | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 180; 온 나라 "all over the country," 온 집안 "entire family/home." |
| 옳다 [올타] | to be right, to be correct | verb (descriptive) | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 180. |
| 우두머리 | head, leader, chief | noun | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 180. |
| 의로운 / 의롭다 | righteous / to be righteous | adjective / verb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 180. |
| 재산 | property, asset | noun | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 180. |
| 천대 | mistreatment, ill-treatment | noun | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 180; 천대를 받다 "to be mistreated." |
| 첩 | concubine | noun | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 180; socially/historically loaded term (traditional Korean family structure), relevant to the reading passage's plot (Hong Kil-dong is a concubine's son). |
| 품다 | to bear in mind, to harbor | verb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 180. |
| 학문 | scholarship, academic knowledge | noun | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 180. |
| 혼내 주다 | to reprimand, to teach a lesson | verb phrase | colloquial | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 180; explicitly tagged "(colloquial)" by the source. |

### Lesson 19 — 음악 공연 예약 "Music Concert Reservation" (p. 186-194)

Dialogue: two friends discuss weekend plans (a musical adaptation of the pansori story *The Tale of
Hŭngbu*, 흥부전) and then buy tickets at an advance-sale booth. Extra Reading retells the Hŭngbu
story itself (rich/poor brothers, a swallow's broken leg healed out of kindness, magic gourds).
Both paraphrased above, not transcribed, per copyright discipline.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가능하다 | to be possible | verb (descriptive) | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 187; 가능하면 "if possible." |
| 공연 | performance (music, drama, dance) | noun | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 187. |
| 나란히 | side by side, in a row | adverb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 187. |
| 냉커피 | iced coffee | noun | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 187; 냉수 "iced water" given alongside. |
| 데리고 가다 | to take (someone) along | verb phrase | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 187; 데리고 오다 "to bring (someone) along" given alongside. |
| 마음씨 | mind, heart, disposition | noun | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 187; 마음씨 착한 "good-hearted, good-natured." |
| 뮤지컬 | a musical | noun | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 187. Loanword (English "musical"). |
| 미술전 | art exhibition | noun | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 187. |
| -석 | seat (ticket class) | counter/suffix | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 187; A석 "A-class ticket." |
| 아틀리에 | atelier, studio | noun | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 187. Loanword (French via English/Korean). |
| 앞자리 | front seat | noun | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 188; 자리 "seat" given alongside. |
| 약속 | promise, appointment | noun | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 188; 약속하다 "to promise." |
| 연기 | performance, acting | noun | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 188; 연기하다 "to act." |
| 예매처 | booth for advance ticket sales | noun | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 188. |
| 예매하다 | to sell/buy in advance | verb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 188. |
| 욕심장이 | greedy person | noun | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 188. |
| 의논하다 | to discuss | verb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 188; 의논 "discussion." |
| -잔 | cup (of) | counter | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 188; 커피 한잔 "a cup of coffee." |
| 잠이 들다 | to fall asleep | verb phrase | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 188. |
| -장 | (counter for flat objects, e.g. tickets/paper) | counter | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 188; 표 석장 "three tickets." |
| 죽다 | to die | verb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 188. |
| 지경이다 | to be at the point of | verb phrase | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 188; 죽을 지경이다 "to be about to die (from X)" — see grammar pt. 6. |
| 지불하다 | to pay | verb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 188; 지불 "payment." |
| 착한 [차칸] / 착하다 | good-hearted / to be good-hearted | adjective / verb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 188; bracketed pronunciation shows aspiration assimilation (ㄱ+ㅎ→ㅋ). |
| 카드 | credit card | noun | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 188. Loanword (English "card"). |
| 팬 | fan, admirer | noun | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 188. Loanword (English "fan"). |
| 현대화하다 | to modernize | verb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 188; 현대화 "modernization." |
| 갈등 | conflict, tension | noun | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 189; 갈등(이) 있다 "to have conflict/tension." |
| 구렁이 | boa, large snake | noun | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 189. |
| 꼴 보기 싫다 | to hate the sight of (someone) | idiom | colloquial | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 189. |
| 내쫓다 | to expel, to chase out | verb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 189. |
| 떨어뜨리다 / 떨어지다 | to drop (Vt.) / to drop (Vi.) | verb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 189; explicit transitive/intransitive pair. |
| 박 | gourd | noun | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 189; 박 씨 "gourd seed," 박 꽃 "gourd flower." |
| 부러지다 / 부러뜨리다 | to break (Vi.) / to break (Vt.) | verb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 189; explicit intransitive/transitive pair. |
| 심술쟁이 | grouch, ill-tempered person | noun | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 189. |
| 쏟아지다 [쏘다지다] | to pour out, to gush out | verb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 190. |
| 우애 | brotherly/friendly love | noun | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 190. |
| 유언 | last words, dying wish | noun | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 190; 유언하다 "to express one's dying wish." |
| 하도 | too (much), very | adverb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 190. |
| 화해 | reconciliation | noun | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 190; 화해하다 "to reconcile." |

### Lesson 20 — 조선족 학생과의 만남 "Meeting a Korean-Chinese Student" (p. 196-203+)

**Register/dialect finding — the highest-value content found in this pass.** This lesson's dialogue
and Extra Reading are explicitly about dialectal/diaspora variation in Korean, exactly the kind of
content the coverage rule flags as never-skip. A Korean-American student (현배) meets a 조선족
("Chosŏn-jok," Korean-Chinese) exchange student (만철) from Yŏnbyŏn, China, via a mutual friend.
Paraphrased below, not transcribed, per copyright discipline:

- 만철 reports that Chosŏn-jok Korean ("조선 말") is used at home/in his hometown Yŏnbyŏn but has
  **zero opportunity for use at school** in China — an explicit domain-restriction observation about
  a diaspora variety.
- 준희 asks whether Chosŏn-jok Korean is closer to **North Korean speech** than to Seoul speech;
  만철 confirms it is, and that the **accent** in particular differs from Seoul Korean. He adds that
  North Korean speech would still be broadly intelligible to a Seoul speaker ("전혀 못 알아 들을 정도는
  아닐 거예요," not "to the point of being totally unintelligible").
- 만철 reports being **바wildered/confused (어리둥절)** on first arriving in Seoul by the sheer density
  of Western loanwords (외래어) in South Korean speech — explicitly citing 엘리베이터 "elevator" and
  에어콘 "air conditioner" as words he didn't recognize despite fluent Korean. 현배 (the
  Korean-American) reports the *same* difficulty from the opposite direction — English loanwords as
  used in Korean don't sound like their English source and were hard to parse. **This is a genuine,
  source-marked case of loanword-register divergence being a source of cross-dialect
  miscommunication even between two fluent speakers of "the same language."**
- A closing exchange plays on the stereotype that "빨리, 빨리" ("quickly, quickly") is the first Korean
  phrase foreigners learn, with 준희 crediting Korea's rapid development to precisely that "빨리 빨리"
  cultural trait — an explicit metapragmatic/cultural-stereotype comment on register/speed-of-speech
  as national self-characterization.
- The Extra Reading (읽기) gives real ethnographic/demographic content on the global Korean diaspora's
  naming conventions, distinct from anything captured in prior established/ files: Korean-Chinese are
  called 조선족 (by Chinese usage) but this term is "relatively new" in South Korean usage due to the
  mid-1940s-to-early-1990s communication gap between South Korea and China/North Korea; the reading
  also gives Korean-Americans = 재미 교포, Korean-Japanese = 재일 교포, and (a North Korean usage)
  Korean-Russians = 고려인 — a genuine terminological register split by diaspora population and by
  which Korea (North/South) is doing the naming. Population figures given: ~1.5 million Korean-Chinese
  (mostly Yŏnbyŏn/Yanbian), 1+ million Korean-Americans (concentrated in LA/SF/NYC/Hawaii), ~500,000
  Korean-Russians (mostly Almaty, Kazakhstan and Tashkent, Uzbekistan, following the Soviet-era forced
  relocation from the Far East — not stated explicitly by the source but implied by the geography
  given).

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 교포 | Koreans residing abroad, overseas Koreans | noun | core | — | contemporary (source publication) | — | diaspora (global) | grammar_reference | n/a | verified | p. 197. |
| 마찬가지이다 | to be the same, to be similar | verb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 197; extensive combination paradigm at grammar pt. 6. |
| 발음 | pronunciation | noun | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 197; 발음하다 "to pronounce." |
| 서구 | western Europe (also loosely "the West") | noun | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 197; 서양 "the West," 동구 "eastern Europe" given alongside. |
| 성장하다 | to grow | verb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 197; 성장 "growth." |
| 액센트 | accent | noun | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 198. Loanword (English "accent"); used in-dialogue to describe Chosŏn-jok/Seoul dialect divergence. |
| 어리둥절하다 | to feel confused, bewildered | verb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 198. |
| 에어콘; 냉방기 | air conditioner | noun | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 198; 에어콘 is the loanword, 냉방기 the native-coined alternative — an explicit loanword/native-coinage doublet. |
| 엘리베이터; 승강기 | elevator | noun | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 198; same loanword/native-coinage doublet pattern as 에어콘/냉방기. |
| 연변 | Yŏnbyŏn (Yanbian), NE China near the N. Korean border | proper noun | core | — | contemporary (source publication) | Yanbian, China | regional (Korean-Chinese diaspora) | grammar_reference | n/a | verified | p. 198; the Chosŏn-jok character's hometown; identified in the reading passage as home to the majority of China's 1.5 million ethnic Koreans. |
| 외래어 | word of foreign origin, loanword | noun | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 198; the lesson's central sociolinguistic theme (see dialogue summary above). |
| 전혀 | entirely (not), completely (not) | adverb | core | — | contemporary (source publication) | — | — | grammar_reference | n/a | verified | p. 198; part of the negative-polarity adverb set formally tabulated at grammar pt. 2. |
| 조선족 | Chosŏn nationals, Korean-Chinese | noun (ethnonym) | core | — | contemporary (source publication) | China (Yanbian primarily) | diaspora-specific (ethnic Koreans of China) | grammar_reference | n/a | verified | p. 198; footnoted by the source itself as a term "relatively new" in South Korean usage — see the dialect/diaspora finding above. |

## Grammar points

### Lesson 17, pt. 5 — A.V. + -는 동안(에) "while," "during," "when" (p. 170)

Indicates a duration of time during which an action or event occurs. Example: 한국에서 사는 동안
친구를 많이 사귀었어요 "I made many friends while I was living in Korea."

### Lesson 17, pt. 6 — V. + -ㄴ/은/는 대신(에); N. + 대신(에) "instead of," "but" (p. 170)

대신 literally means "substitution," "proxy," or "surrogate," but functions idiomatically as "in
exchange for" or "as a trade-off." Two subtypes: (a) a concessive/contrastive use ("X, but Y") —
그 물건은 비싼 대신 튼튼해요 "That item is expensive but sturdy"; (b) a literal substitution use ("in
place of") — 전화를 거는 대신 편지를 쓰기로 했다 "Instead of calling, I will write a letter."

### Lesson 17, pt. 7 — Causative verbs chart (p. 171-172)

A systematic presentation of Korean's seven causative-forming suffixes (-이-, -히-, -리-, -기-, -우-,
-구-, -추-), each attached to an intransitive/descriptive verb base to derive a causative
("make/let X happen") counterpart, with a full example sentence per pair. See the Vocabulary
section above for the individual base/causative pairs newly captured here (largely overlapping in
mechanism, though not in full example-set, with the causative-suffix material already documented
in `established/002` and `established/003`).

### Lesson 18, pt. 1 — A.V. + -ㄹ/을 겸 "while doing . . . " (p. 180)

Indicates that a second action serves a dual purpose — taking advantage of a situation to do one
thing while also doing another. Example: 점심도 먹을 겸 집에 갔다 "I went home and also had lunch."

### Lesson 18, pt. 2 — V. + -더니 / V. + -었/았더니 "and then," "since," "but" / "since," "because," "so," "as," "when" (p. 180-181)

-더니 reports a past observation and its contrast/continuation with a present state, and is
**not used with first person (I/we)** as its subject; -었/았더니 (past-tense stem) carries a similar
but not identical range of meanings and does **not** have this person restriction. The source
flags an important structural rule: the subjects of the two clauses joined by -었/았더니 are usually
**not the same person** — 톰은 책방에 갔더니 책을 샀다 ("Tom went to the bookstore and [Tom] bought a
book") is explicitly marked incorrect, while 톰은 책방에 가더니 책을 샀다 (plain -더니, same subject) or
톰이 책방에 갔더니 민수가 와 있었다 (different subjects) are both fine. Example: 아침 일찍 학교에 갔더니
교실이 텅 비어 있었다 "Because I went to school early in the morning, the classroom was completely
empty."

### Lesson 18, pt. 3 — V. + (어/아)서 그런지 "maybe because," "it could be because" (p. 181)

Marks the speaker's own conjecture/reasoning about a cause, rather than a stated fact. Example:
바빠서 그런지 존은 무술에 관심이 없다 "Maybe because he is busy, John is not interested in the martial
arts."

### Lesson 18, pt. 4 — V. + -기는 V. + -지만; N. + (이)기는 하지만 "it is true that . . . , but," "although it is . . . " (p. 181-182)

Concedes a fact while contrasting it with a following clause — signals that the speaker
acknowledges/recognizes the stated fact. Example: 비행기가 빠르기는 하지만 비싸다 "It is true that
airplanes are fast, but they are expensive."

### Lesson 18, pt. 5 — Ending expression 뭐 (p. 182)

A colloquial sentence-final particle with no direct English equivalent, glossed loosely as "what
else?" or "you know" — signals the speaker treats the statement as unremarkable/self-evident.
**Register-restricted:** used only in intimate/informal conversation, and only after the -지(요) or
-나(요) sentence endings. Example: 일종의 스포츠로 하는 거지 뭐 "They are doing it as a kind of sport,
nothing more."

### Lesson 18, pt. 6 — V. + -거든(요) "you know" (p. 182-183)

An intimate-or-polite sentence-final ending presenting a fact as new information/justification to
the listener, glossed "you know" — 무술은 건강에 좋거든 "You know, martial arts are good for your
health." (Register note: this same -거든(요) ending recurs across other Korean grammar references in
this project's corpus as a colloquial spoken-register indirection device — see
`established/003_intermediate_korean_part1.md`'s Units 9/12 findings — consistent with its use here.)

### Lesson 19, pt. 1 — Verbs for involuntary action: 들다, 나다, 걸리다 (p. 190-191)

Many body-related functions are grammatically treated as involuntary/noncontrollable events in
Korean, expressed via one of three light verbs rather than an ordinary active verb: 들다 ("come
under"), 나다 ("arise"), or 걸리다 ("be caught"). The book's own paradigm set: 들다 → 잠이 들다 "to fall
asleep," 감기가 들다/병이 들다 "to catch a cold/get sick," 물이 들다 "to be influenced (lit. to be
colored)"; 나다 → 열이 나다 "to have a fever," 병이 나다 "to get sick," 화가 나다 "to get upset," 땀이 나다
"to perspire"; 걸리다 → 감기에 걸리다/병에 걸리다 "to catch a cold/get sick," 순경에게 걸리다 "to be caught by
a cop." Note 감기 and 병 each pair with two different light verbs (들다 and 걸리다) with no clear
synonymy rule given beyond usage.

### Lesson 19, pt. 2 — Question ending -다지요? "isn't it . . . ?" (p. 191)

An indirect-question sentence-final pattern meaning "don't I hear / don't they say . . . ?" — reports
secondhand information while inviting confirmation. Two morphological subtypes: V. + -다지(요)?/-었/았다지(요)? and N. + (이)라지(요)?/(이)였다지(요)?. Example: 그 분은 오페라를 좋아한다지요? "Don't they say
he likes opera?"

### Lesson 19, pt. 3 — A.V. + -ㄹ/을 걸 그랬다 "should have . . . " (p. 191-192)

A short form of -ㄹ/을 것을 그랬다, expressing mild regret over an unperformed past action. Example:
점심을 미리 먹을 걸 그랬다 "I should have eaten lunch earlier."

### Lesson 19, pt. 4 — V. + (어/아) 봤자/보았자 "even if (I try) doing . . . " (p. 192)

Indicates the speaker's supposition that an action, even if carried out, would be pointless or
would not change the outcome. Example: 지금 후회해 봤자 소용없어 "Even if you are remorseful now, it is
of no use."

### Lesson 19, pt. 5 — A.V. + (으)나 마나 "no use," "not worth doing" (p. 192)

Literally "whether to do it or not," indicating a futile/pointless attempt. Example: 가나 마나 우리는
늦어서 그 영화는 못 봐 "There is no use going; we can't see the movie because we're late."

### Lesson 19, pt. 6 — A.V. + -ㄹ/을 지경이다 "to/at the point of," "almost," "nearly" (p. 192-193)

Often preceded by a verb denoting hardship (포기하다 "give up," 쓰러지다 "collapse," 죽다 "die," 울다
"cry," 꺾어지다 "break/snap," 넘어지다 "fall over") to intensify a description of a difficult state.
Example: 시험이 너무 어려워 울 지경이었다 "The exam was so difficult that I almost cried"; also seen in
this lesson's own dialogue (p. 187): 날씨가 어찌나 더운지 죽을 지경이야 "It's so hot I could die."

### Lesson 20, pt. 1 — Indirect speech: formal short forms (p. 199-200)

A systematic table of the **formal-register** short indirect-quotation endings (contrasted
explicitly by the source with the informal short forms -대요/-(이)래요/-(으)래요/-냬요/-재요, cross-referenced
to Lesson 9's own grammar notes rather than repeated here): statement V. + -답니다 / statement N. +
-(이)랍니다 "they say (that it is)"; command V. + -(으)랍니다 "they tell/ask/order"; question V. +
-냡니다 "they ask/say"; "let's"-proposal V. + -잡니다 "they ask/invite to do." Example: 만철이는 중국에
사는 조선족이랍니다 "(They say) Man-chŭl is a Korean who lives in China."

### Lesson 20, pt. 2 — Adverb with negative (p. 200-201)

A tabulated set of Korean adverbs that co-occur specifically with negation (안/못, 없다, 아니다, -지
않다, -지 못하다, -지 말다, 모르다, or 마세요), each with a distinct shade of "not at all" / "hardly" /
"never" meaning: 전혀 "completely, never at all," 도무지 "not at all," 영 "not at all, none," 결코 "by
no means, never," 꼼짝 "not even a tiny bit (of motion)," 도저히 "not possibly," 좀처럼 "hardly, not
often," 통 "at all," 그리 "not so (much/long/big/good/etc.)," 과히 "not very," 별로 "not especially,"
절대로 "never, ever." This is a finer-grained register/intensity inventory than a simple negation
marker — several of these (절대로, 결코, 도저히) skew toward emphatic/formal registers while others
(별로, 그리) are everyday colloquial hedges, though the source itself does not explicitly tag
individual entries by register.

### Lesson 20, pt. 3 — V. + -다 보니 "while (doing/being)," "as . . . (is doing)," "since" (p. 201-202)

Marks the speaker's realization that, in the course of one action/state continuing, something else
became true — or gives the cause for a following event. Example: 값이 비싸다 보니 아무도 사가는 사람이
없다 "As the price was so high, nobody was buying it."

### Lesson 20, pt. 4 — V. + -ㄹ/을 정도로 "(so) . . . to the extent that," "to the point that" (p. 202)

Expresses a hypothetical or real degree/limit/extent of an action or state. Example: 숨을 쉬지도 못
할 정도로 많이 먹었다 "I ate so much (to the extent) that I can't breathe."

### Lesson 20, pt. 5 — V. + -었/았었다 "it has/had been" (double past) (p. 202)

Distinguishes the simple past -었/았- (marks a completed action, which may or may not still hold —
앉았다 "I sat down" can also mean "I am (now) sitting") from the **double-past** -었/았었-, which
specifically marks an action completed in the past that was *later superseded* or is presented as a
bounded past experience no longer holding. Example: 이모 이름을 잊었었다. 그런데 지금은 생각이 난다 "I had
forgotten my aunt's name. But now I remember [it]" — the double past explicitly signals the
forgetting is now over.

### Lesson 20, pt. 6 — Many uses of 마찬가지 "same thing," "similar thing" (p. 203)

마찬가지(이다) combines productively with connectives, sentence endings, verbal modifiers, and
particles: 마찬가지다 "it is the same," 마찬가지냐? "is it the same?," 마찬가지로 "similarly, in the same
manner," 마찬가지의 "the same kind of," 마찬가지면 "if it's the same," 마찬가지지만 "although it's the
same." Example: 가나 안 가나 마찬가지지만 가겠다 "Whether I go or not is all the same to me, but I'll
go."

### Lesson 20, pt. 7 — N. + 덕택에/덕분에; V. + -ㄴ/은/는 덕택에/덕분에 "thanks to (you) . . . ," "due to (your) generosity" (p. 203)

A polite acknowledgment of a favor or generosity, functioning as an elaborated "thank you" — the
source notes it is used liberally even when no concrete favor was received, e.g. as a stock reply
덕택에 잘 지냅니다 to the greeting 요즘 어떠세요? ("How have you been?"). Example: 아버님께서 열심히 일하신
덕분에 저는 대학을 어렵지 않게 다녔어요 "Thanks to my father's hard work, I went to college without
hardship."

---

## Coverage note

This pass covered PDF pages 191-224 (printed pp. 170-203) in full detail: the tail of Lesson 17
(grammar points 5-7, causative-verb chart), all of Lesson 18 (vocabulary, grammar points 1-6), all
of Lesson 19 (main + Extra Reading vocabulary, grammar points 1-6), and Lesson 20 through grammar
point 7 (vocabulary + the dialogue/Extra Reading's register/dialect content, both summarized above
— see the "highest-value content found in this pass" note). Exercise/drill sections throughout are
not transcribed, per the coverage rule. **The remainder of the assigned range (PDF pages 225-376,
printed pp. 204-355ish, covering the tail of Lesson 20 onward through the book's
Patterns-and-Grammar-Notes Index and Glossary appendices) was not reached in this pass** due to the vision-reading cost of this source (see the PDF gotcha note above — no
decodable text-layer shortcut was found, unlike most other Korean sources in this project). This
file should be treated as a **partial** part-2 extraction; a follow-up dispatch is needed to cover
PDF 208-376. Structural reconnaissance already done for that follow-up (so it doesn't need to
re-derive this): `pdftotext -layout` on PDF 191-376 shows Vocabulary-section headers recurring
roughly every 9-11 pages (consistent with each lesson having a main-text vocabulary list plus a
separate "Extra Reading" vocabulary list); a "PATTERNS AND GRAMMAR NOTES INDEX" back-matter section
begins around printed p. 290 (~PDF 311), followed by a cumulative English-Korean "Glossary"
appendix running to the end of the book (~PDF 324-376) — both are pointer/index apparatus and, per
this project's established pattern for such appendices (see `established/004`'s and `established/009`'s
treatment of similar back matter), warrant only a light sample rather than full transcription.
