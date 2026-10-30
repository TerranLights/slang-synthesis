# Korean — Established Vocabulary/Grammar: *Korean Course Seoul University Vol. 4* (Lessons 1–35, complete)

**Source:** Language Education Institute, Seoul National University, *Korean Course*, Vol. 4 of a
6-volume bilingual Korean–Chinese series (Chinese-market edition; all glosses/translations in the
source are given in **Chinese**, translated to English below per this project's established
convention for this series — see sibling files `established/039_korean_course_snu_vol2.md` and
`established/040_korean_course_snu_vol3.md`). PDF: `Korean Course Seoul University Vol. 4.pdf`,
381 pages, ABBYY FineReader 10 OCR scan (2010). No title page/copyright colophon with a publication
date appears anywhere in the scan — **Attested Era is left `—` throughout**, matching both sibling
volumes' own finding. This volume continues the series independently of Vol. 2/Vol. 3 — it was not
read for cross-reference per dispatch instructions, and no direct territory overlap with those two
volumes is expected (different lesson content, confirmed during extraction).

**Scope.** All 35 lessons (PDF pp. 1–339) fully extracted — vocabulary + grammar points for every
lesson, following this series' own established "every lesson's vocabulary extracted in full"
policy (an independently-authored source whose own vocabulary selection is not redundant by
default, per `00_Reference_Extraction_Spec.md`). **The book has 35 lessons, not 34** — this was
discovered only during extraction (Lesson 35 is easy to miss, since it immediately precedes the
back matter). Back matter — an alphabetized Korean vocabulary/grammar-pattern index keyed to
lesson number (PDF pp. ~340–349) and a "听力脚本" (Listening Script) appendix giving the text of
each lesson's listening-comprehension audio exercises (PDF pp. ~350–381) — was **not extracted**:
both are pure re-listing/answer-key-adjacent apparatus, consistent with how sibling Korean
dispatches treat equivalent back matter elsewhere in this project.

**Text layer and OCR notes.** `pdftotext` produces a genuine, directly usable text layer for Hangul
throughout — no font-substitution cipher, no vision-reading needed anywhere in this book
(Vision Reading Confidence is `n/a` throughout; Transcription Confidence is `n/a` throughout, this
being a reference-book extraction, not a subtitle/transcript source). Recurring OCR quirks, all
confirmed and worked around the same way as this series' sibling volumes:

1. **Stray corrupted single-glyph noise** (`ᅳ`, `ᄀ`, `^`, stray digits/jamo) scattered through
   running text, especially around section markers and inside drill-exercise grids — filtered
   silently throughout, carries no semantic content.
2. **Fill-in-the-blank drill exercises and answer grids extract badly scrambled** — squarely the
   coverage rule's "repeated drill" case; skipped throughout, confirmed to carry no new vocabulary
   or grammar beyond what each lesson's own dialogue/reading + grammar box + vocabulary box already
   supplied.
3. **End-of-lesson vocabulary boxes are a true multi-column layout** (Term | Korean-definition |
   Chinese-gloss) that `pdftotext`'s plain mode can scramble into separate position-matched blocks
   (all terms, then all Korean definitions, then all Chinese glosses, each in matching relative
   order but no longer on the same line) rather than wrong-interleaved. `pdftotext -layout` resolves
   this cleanly; where plain mode was used instead, the displaced Chinese-gloss block was
   reconstructed by matching its order against the entries missing an inline gloss and cross-checked
   against the Korean-language definition already present — flagged per-entry in the Notes column
   where this reconstruction was needed.
4. A few individual entries had more specific OCR damage (e.g. a single swapped jamo, a vocabulary
   box interrupted mid-paragraph) — each is flagged explicitly in its own Notes-column entry or
   lesson-level note rather than silently corrected or silently dropped.

**No handwritten marginalia** — not applicable; this is a real text layer throughout, not a
vision-read scan. **No explicit dialectal/regional annotation** (bracketed tags, "formal" vs.
"colloquial" source-marked labels) appears anywhere in this volume beyond incidental real-world
place names and the named-regional-song-tradition taxonomy flagged explicitly under Lesson 24
below — standard contemporary Korean throughout, consistent with this series' sibling volumes.

**Merge note.** This file was assembled from four parallel extraction passes (Lessons 1–9, 10–18,
19–25, 26–35), each independently verifying its own lesson boundaries against the source PDF by
direct inspection rather than a fixed page-count formula. Page-range citations below are given to
the best verification achieved; a handful of individual page numbers in the original per-batch
notes proved to be off by a few pages on cross-check (lesson *content* boundaries, not page
numbers, were what mattered and were independently reconfirmed clean — no content gap, overlap, or
duplication exists anywhere across the 35 lessons).

---

## Lesson 1: 인류의 미래에 대해 생각해 본 적이 있어요? (Have You Ever Thought About Humanity's Future?)

PDF pp. 1–11. Dialogue: two students debate whether worrying about humanity's distant future
(life-extension, space travel to the Moon/Mars) is worthwhile "needless worry" or genuine forward
thinking.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 인류 (人類) | humankind, humanity | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 미래 (未來) | the future | noun | core | — | — | — | — | grammar_reference | n/a | n/a | Chinese gloss displaced in OCR, reconstructed |
| 학자 (學者) | scholar | noun | core | — | — | — | — | grammar_reference | n/a | n/a | Chinese gloss displaced, reconstructed |
| 죽음 | death | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 질병 (疾病) | illness, disease | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 암 (癌) | cancer | noun | core | — | — | — | — | grammar_reference | n/a | n/a | Chinese gloss displaced, reconstructed |
| 정복하다 (征服) | to conquer, overcome | verb | core | — | — | — | — | grammar_reference | n/a | n/a | Chinese gloss displaced, reconstructed |
| 인간 (人間) | human being | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 평균 (平均) | average | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 수명 (壽命) | lifespan | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 과학 (科學) | science | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 우주 (宇宙) | universe, outer space | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 화성 (火星) | Mars | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 가능하다 (可能) | to be possible | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 챙기다 | to prepare/pack; to look after | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 쓸데없다 | to be useless, pointless | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | Chinese gloss displaced, reconstructed |
| 최근 (最近) | recently | noun/adverb | core | — | — | — | — | grammar_reference | n/a | n/a | Chinese gloss displaced, reconstructed |
| 논문 (論文) | thesis, research paper | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 생물 (生物) | living thing, organism | noun | core | — | — | — | — | grammar_reference | n/a | n/a | Chinese gloss displaced, reconstructed |
| 유지하다 (維持) | to maintain | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 각각 (各各) | each, respectively | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 공통적 (共通的) | common, shared | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 뒤 | after; behind | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 현실 (現實) | reality | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 기술 (技術) | technology, skill | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 로봇 | robot | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 실용화 (實用化) | practical application, being put to practical use | noun | technical | — | — | — | — | grammar_reference | n/a | n/a | |
| 잔디 | grass, lawn | noun | core | — | — | — | — | grammar_reference | n/a | n/a | incidental exercise vocabulary |

### Grammar points

**-(으)ᆯ 리가 없다.** "There's no way that...", used to flatly reject a possibility as illogical
(p.2: 그 친구가 이렇게 늦을 리가 없는데 이상하네 "There's no way that friend would be this late —
that's strange").

**X에 의하면.** "According to X" (news/a person/a paper), introducing reported information (p.2:
뉴스에 의하면 오늘 밤에 태풍이 온대요 "According to the news, a typhoon is coming tonight").

**-(으)ᆯ지도 모르다.** "Might, perhaps" — marks a speculative possibility (p.2: 이 옷이 내
동생에게는 좀 작을지도 모르겠어요 "This clothing might be a bit small for my younger sibling").

**을/를 챙기다.** "To prepare/pack (something needed)," extended idiomatically to "to look after"
(밖에 나가면 동생 좀 잘 챙겨라 "When you go out, look after your younger sibling").

**쓸데없다.** Idiomatic adjective, "to be useless/pointless" — recurring in the fixed collocation
쓸데없는 걱정 "needless worry," the dialogue's own closing line and this lesson's thematic frame.

---

## Lesson 2: 단군이 조선을 세웠어요 (Dangun Founded Joseon)

**Flagship sociocultural content.** The lesson's main reading is a full narration of the **Dangun
founding myth** — Hwanin's son Hwanung descends to found a kingdom at Baekdu Mountain; a tiger and
a bear each ask to become human; Hwanung tells them to eat only mugwort and garlic in a cave for 100
days without sunlight; the tiger fails and flees, the bear endures and becomes a woman, marries the
temporarily-human Hwanung, and their son Dangun founds Joseon. This is Korea's national origin myth,
presented here as intermediate-level reading material, and closes with an explicit exercise asking
students to tell their own country's founding story — an explicit cross-cultural-mythology framing.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 단군 (檀君) | Dangun (legendary founding king of Korea) | proper noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 조선 (朝鮮) | Joseon | proper noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 세우다 | to found, establish | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 임금 | king, monarch | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 내려가다 | to go down | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 다스리다 | to govern, rule | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 허락하다 (許諾) | to permit, allow | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 부하 (部下) | subordinate | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 백성 (百姓) | the people, subjects (archaic for "citizens") | noun | archaic | — | — | — | — | grammar_reference | n/a | n/a | source's own def. flags this as an old word for 국민 |
| 모으다 | to gather, collect | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 호랑이 | tiger | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 곰 | bear | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 소원 (所願) | wish | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 간절히 (懇切) | earnestly, desperately | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 쑥 | mugwort | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 굴 (窟) | cave | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 햇빛 | sunlight | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 캄캄하다 | to be pitch dark | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 배고픔 | hunger | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 뛰쳐나오다 | to burst/rush out | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 태어나다 | to be born | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 마중 | going out to meet/greet an arriving person | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 슬픔 | sadness | noun | core | — | — | — | — | grammar_reference | n/a | n/a | -(으)ᆷ nominalization of 슬프다, see grammar below |
| 웃음 | laughter | noun | core | — | — | — | — | grammar_reference | n/a | n/a | -(으)ᆷ nominalization of 웃다 |
| 없어지다 | to disappear, vanish | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 신화 (神話) | myth | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 인물 (人物) | (historical/fictional) figure, person | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |

### Grammar points

**~에게 ~도록 허락하다.** "To permit someone to do..." (어머니께서 나에게 그 사람과 결혼하도록
허락하셨어요 "Mother permitted me to marry that person").

**~아/어 달라고 부탁하다 / X을/를 부탁하다.** "To ask someone to do X for me" vs. "to request X
(itself)" as a direct object (나는 친구에게 책을 사 달라고 부탁할 거예요 "I'll ask my friend to buy
the book for me"; 아주머니께 요리를 부탁할 거예요 "I'll ask the lady to make the food").

**-(으)ᆷ nominalizer.** Converts an adjective/verb stem into a noun — 슬프다→슬픔 "sadness,"
웃다→웃음 "laughter," 걷다→걸음 "a step/walking" (동생을 잃어버린 슬픔 때문에... "because of the
sadness of having lost my younger sibling...").

**~만에.** "After (a span of time has passed)" (한국에 온 지 이틀 만에 취직했어요 "I got a job just
two days after coming to Korea").

**~(으)나.** Contrastive connective, "although X, Y" — more literary/formal register than 지만
(값은 좀 비싸나 좋은 물건입니다 "It's a bit expensive, but it's a good product").

---

## Lesson 3: 우물 안의 개구리가 될 거예요 (You'll Become a Frog in a Well)

Dialogue frames avoiding the news as becoming "a frog in a well" (사회적 무지). **Notable finding:**
the lesson's reading section reproduces excerpts of genuine-register Korean newspaper content —
a fatal train collision in India, a Gyeonggi-do tidal-flat habitat-loss story tied to land
reclamation, a stock-market-crash headline, a "cancer and AIDS are now 'mild diseases'"
medical-progress piece, and a summary of a US think-tank's futurist technology-prediction survey for
2003-2025 — distinct in register from the book's own constructed dialogue Korean.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 우물 | well (water) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 개구리 | frog | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 마저 | even, ...as well (marking an extreme/last case) | particle | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 아나운서 | (news) announcer | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 불안하다 (不安) | to be anxious, uneasy | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 순간 (瞬間) | moment, instant | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 각국 (各國) | each country | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 끊임없이 | incessantly, continuously | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 끔찍하다 | to be dreadful, horrific | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 비관적 (悲觀的) | pessimistic | noun/adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 낙관적 (樂觀的) | optimistic | noun/adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 살인 (殺人) | murder | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 유괴 (誘拐) | kidnapping | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 성별 (性別) | gender, sex | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 특징 (特徵) | characteristic, feature | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 묶다 | to tie, bind | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 충돌 (衝突) | collision | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 사망 (死亡) | death, fatality | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 경기도 (京畿道) | Gyeonggi Province (Korean administrative region) | proper noun | core | — | — | Gyeonggi Province | regional | grammar_reference | n/a | n/a | real-world place name, from the embedded newspaper excerpt |
| 갯벌 | tidal flat | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 감소 (減少) | decrease | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 증시 (證市) | stock market (abbreviation of 증권시장) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 폭락 (暴落) | (price) crash | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |

### Grammar points

**우물 안의 개구리 (idiom).** "A frog in a well" — someone of narrow, limited experience/perspective
(cf. English "a big fish in a small pond," though with the opposite evaluative slant — here it's a
criticism of ignorance of the wider world). Explicitly taught as the lesson's central idiom.

**-(으)려던 참이다.** "Was just about to..." (안 그래도 내가 너에게 전화를 하려던 참이었어 "I was
just about to call you anyway").

**~마저.** "Even...; ...as well" — marks the last/most extreme item in a negative scale (오늘 떠나는
마지막 비행기마저 놓쳤으니 어쩌지요 "I even missed the very last flight leaving today, what do I
do").

**-(으)ᆯ 정도이다 / -(으)ᆯ 정도로.** "To the extent/degree that..." (오늘은 잠을 못 잘 정도로
피곤하네요 "I'm tired to the point I can't sleep tonight").

**생각하기에 따라(서) / 보기에[듣기에] 따라(서) (idiom).** "Depending on how you think about/see/hear
it" — a hedge introducing subjective framing (그 문제는 생각하기에 따라 쉬울 수도 있고 어려울 수도
있어요 "That problem can be easy or hard depending on how you think about it").

---

## Lesson 4: 비 올 확률이 높지 않아요 (The Chance of Rain Isn't High)

Dialogue about checking a weather forecast before an outdoor concert. **Notable finding:** the
lesson's reading section includes a letter to a "Lifeline" (생명의 전화) phone/email counseling
service — an anonymous wife's dilemma over her husband wanting to sell their house to start a
business — a genuine Korean media/advice-column genre used as teaching material.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 확률 (確率) | probability | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 골치(가) 아프다 | (idiom) to have a headache over, to be troubled by | expression | colloquial | — | — | — | — | grammar_reference | n/a | n/a | |
| 프로그램 | (TV/radio) program | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 실리다 | to be carried/published/loaded (passive of 싣다) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 면 (面) | page, section (of a newspaper) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 야외 (野外) | outdoors | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 취소하다 (取消) | to cancel | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 남부 (南部) | southern region | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 지방 (地方) | region, locality | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 지역 (地域) | area, zone | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 끼다 | (of clouds/fog/dust) to form, gather | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 매표소 (賣票所) | ticket booth | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 관객 (觀客) | audience, spectator | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 사장 (社長) | company president | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 가구 (家具) | furniture | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 먼지 | dust | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 약하다 (弱) | to be weak | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 베란다 | veranda, balcony | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 꾸다 | to borrow | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 팀 | team | noun | core | — | — | — | — | grammar_reference | n/a | n/a | loanword |
| 시합 (試合) | match, game | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 생명 (生命) | life | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 이메일 | email | noun | core | — | — | — | — | grammar_reference | n/a | n/a | loanword |
| 과장 (課長) | section chief | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 사업 (事業) | business, enterprise | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 당연하다 (當然) | to be natural, obvious | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 채 | counter for houses | counter | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 늘어나다 | to increase, grow | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 실패하다 (失敗) | to fail | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 내 (內) | within | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 대전 (大戰) | great war, world war | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 해결하다 (解決) | to resolve, solve | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |

### Grammar points

**~을/를 확률이 높다/낮다[있다/없다].** "The probability of ~ is high/low" (담배를 안 피우는 사람은
암에 걸릴 확률이 훨씬 낮다고 합니다 "Non-smokers reportedly have a much lower probability of getting
cancer").

**~(이)라고는 ~뿐이다 / ~(이)라고는 X밖에 없다[못 V].** Emphatic exclusivity, "the only ~ is/can...";
the first form softer, the second stronger (내 방에 가구라고는 책상뿐이다 "The only furniture in my
room is a desk"; 친구라고는 너밖에 없는데 "The only friend I have is you").

**골치(가) 아프다 (idiom).** "To have a headache over, to be troubled by" (요즘 회사일이 많아서
골치가 아파요 "I have a headache from all the work at the company lately").

**구름[안개, 먼지]이/가 끼다 (idiom).** "Clouds/fog/dust to gather, form" (안개가 많이 낀 날은
특히 운전할 때 조심해야 해요 "On heavily foggy days, you especially need to be careful driving").

---

## Lesson 5: 환경 문제에 관심이 많아요 (I'm Very Interested in Environmental Issues)

Essay + dialogue on food waste and household garbage. **Notable finding:** a didactic statistical
claim that Korea's discarded food waste over one year, converted to money, "would be enough to build
a high-speed rail line from Seoul to Busan and have money left over" — used to dramatize the scale of
food waste for the reader.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 환경 (環境) | environment | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 수준 (水準) | level, standard | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 점점 (漸漸) | gradually | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 각 (各) | each | determiner | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 쓰레기 | garbage, trash | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 음식물 (飲食物) | food (as material/waste) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 놓다 (길을) | to lay (a road/track), to install | verb | technical | — | — | — | — | grammar_reference | n/a | n/a | |
| 줄이다 | to reduce | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 반찬 (飯饌) | side dish | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 덜다 | to set aside/remove a portion | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 습관 (習慣) | habit | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 처리 (處理) | handling, disposal | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 절약하다 (節約) | to save, economize | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 보호하다 (保護) | to protect | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 이웃 | neighbor | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 더군다나 | moreover, what's more | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 종류 (種類) | kind, type | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| -별 (別) | "by category of ~" | suffix | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 귀찮다 | to be bothersome, annoying | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 주부 (主婦) | housewife | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 실천하다 (實踐) | to put into practice | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 관계되다 (關係) | to be related | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 선진국 (先進國) | developed country | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 양 (量) | amount | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 문화 (文化) | culture | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 싫증(이) 나다 | to get sick/tired of | expression | colloquial | — | — | — | — | grammar_reference | n/a | n/a | |
| 수거하다 (收去) | to collect (for disposal) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 차이 (差異) | difference | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 심각하다 (深刻) | to be serious, grave | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 경제적 (經濟的) | economic | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 분리수거 (分離收去) | separated-waste collection, recycling collection | noun | technical | — | — | — | — | grammar_reference | n/a | n/a | |
| -류 (類) | "category/type of ~" | suffix | core | — | — | — | — | grammar_reference | n/a | n/a | |

### Grammar points

**~에/에게 관심이 있다[없다] / ~에/에게 관심을 가지다.** "To be interested in / to take an interest
in" — the lesson's own title pattern.

**V-고도 남다.** "Even having done V, (something) is/would still be left over" — expresses abundance
(케이크가 너무 커서 10명이 먹고도 남았어요 "The cake was so big that even after 10 people ate, there
was still some left").

**-(으)ᆯ 만큼(만) / ~만큼.** "As much/to the extent as..." (좋아하는 음식을 골라서 먹을 만큼만
가져가세요 "Pick the food you like and take only as much as you'll eat"); also a plain
degree-comparison use (나도 너만큼 수영을 잘했으면 좋겠다 "I wish I could swim as well as you").

**-별(로).** Classifying suffix, "by category of ~" (나이별로 앉아 보세요 "Please sit by age group").

**-지 않으면 안 되다.** "Must (not) do, have to" (세탁기를 고치지 않으면 안 돼요 "The washing
machine has to be fixed").

**X처럼 ~(으)ᆫ/는 X도 없다.** "There's nothing as ~ as X" (이 세상에서 사랑처럼 아름다운 것도
없을 거예요 "There's probably nothing in this world as beautiful as love").

---

## Lesson 6: 일회용품의 사용을 줄입시다 (Let's Reduce the Use of Disposable Products)

Dialogue about recyclables collection at gas stations and the limits of individual effort vs. the
need for government action. **Notable finding:** a self-assessment checklist exercise that scores
the reader's everyday eco-habits (reusing bathwater to water plants, washing out bottles before
disposal, mending socks instead of discarding them) and labels them either a future "leader"
(지도자) or a "thrifty housewife" (알뜰한 주부) — explicitly tying everyday environmentalism to a
gendered domestic-virtue framing.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 일회용품 (一回用品) | disposable product | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| -여 (餘) | "...-odd, more than" | suffix | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 군데 | counter for places | counter | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 주유소 (注油所) | gas station | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 시민 (市民) | citizen | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 편의 (便宜) | convenience | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 재활용품 (再活用品) | recyclable goods | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 신문지 (新聞紙) | newspaper (as material) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 반응 (反應) | reaction, response | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 얻다 | to obtain, get | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 무엇보다도 | above all, more than anything | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 늘다 | to increase | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 지구 (地球) | the Earth | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 온통 | entirely, wholly | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 덮이다 | to be covered (passive of 덮다) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 의식 (意識) | awareness, consciousness | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 한계 (限界) | limit | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 정부 (政府) | government | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 적극적 (積極的) | proactive, positive | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 나서다 | to step forward, take initiative | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 늘리다 | to increase (something) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 휴식 (休息) | rest | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 줄다 | to decrease | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 체육 대회 (體育大會) | sports day, athletic meet | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 사고방식 (思考方式) | way of thinking, mindset | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 오염 (汚染) | pollution | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 원인 (原因) | cause | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 대기 (大氣) | the atmosphere | noun | technical | — | — | — | — | grammar_reference | n/a | n/a | |
| 배기 (排氣) | exhaust (gas) | noun | technical | — | — | — | — | grammar_reference | n/a | n/a | |
| 비닐 | vinyl, plastic | noun | core | — | — | — | — | grammar_reference | n/a | n/a | loanword |
| 봉투 (封套) | bag, envelope | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 화분 (花盆) | flowerpot | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 깨끗이 | cleanly | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 꿰매다 | to sew, mend | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 지도자 (指導者) | leader | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 알뜰하다 | to be thrifty | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |

### Grammar points

**~을/를 줄이다[늘리다] / ~이/가 줄다[늘다].** Transitive "to reduce/increase (something)" vs.
intransitive "for something to decrease/increase" (건강을 위해서는 일하는 시간을 줄이고 휴식 시간을
늘려야 한다 "For your health, you should reduce work time and increase rest time").

**반응을 얻다 (idiom).** "To get a response/reaction" (그 광고는 사람들로부터 좋은 반응을 얻지
못했다 "That ad failed to get a good response from people").

**무엇보다도.** Idiomatic adverbial, "more than anything" (신발은 무엇보다도 발이 편해야 합니다
"Shoes, above all, need to be comfortable for the feet").

**V-다가는.** "If (you) keep doing V (like this), [negative consequence]" (그렇게 열심히 일하다가는
쓰러질 거예요 "If you keep working that hard, you'll collapse").

**X이/가 (으)로 덮이다.** "To be covered with/by X" (산이 눈으로 덮여서 아름답다 "The mountain is
beautiful, covered in snow").

**X이/가 나서다.** "For X (a person/party) to step forward/take action" (쓰레기 문제를 해결하기
위해서는 정부가 나서야 합니다 "The government must step forward to solve the garbage problem").

---

## Lesson 7: 선봤다는 소문을 들었어 (I Heard a Rumor You Went on an Arranged Date)

**The richest idiom/colloquial-register lesson in this volume's first third.** Dialogue between two
friends about an arranged-dating encounter (소개팅-adjacent custom of 선보다, matchmaking meetings),
packed with fixed idiomatic expressions, followed by a dedicated exercise section explicitly teaching
a list of everyday Korean idioms/proverbs.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 이모 (姨母) | aunt (mother's sister) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 집안 | household, family | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 칭찬하다 (稱讚) | to praise, compliment | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 인상 (印象) | impression | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 인간성 (人間性) | character, personality (as moral worth) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 재산 (財産) | property, wealth | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 한편 (便) | on the other hand | adverb/noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 바가지 | gourd dipper, ladle | noun | core | — | — | — | — | grammar_reference | n/a | n/a | base noun for the idiom below |
| 긁다 | to scratch | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 식다 | to cool down, go cold | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 빠지다 | to fall out, come out | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 혹시 (或是) | perhaps, by any chance | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 사투리 | regional dialect | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 자꾸 | repeatedly, continually | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 관용어 (慣用語) | idiom, idiomatic expression | noun | technical | — | — | — | — | grammar_reference | n/a | n/a | metalinguistic term, taught explicitly |
| 속담 (俗談) | proverb | noun | technical | — | — | — | — | grammar_reference | n/a | n/a | metalinguistic term, taught explicitly |
| 양다리 (兩-) | both legs | noun | core | — | — | — | — | grammar_reference | n/a | n/a | base noun for idiom below |
| 걸치다 | to hang/lay across | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 파뿌리 | leek root (white) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | base noun for idiom below |
| 깨 | sesame | noun | core | — | — | — | — | grammar_reference | n/a | n/a | base noun for idiom below |
| 쏟아지다 | to pour out, spill | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 앞두다 | to have ahead of one, to be facing (an upcoming event) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 고민 (苦悶) | worry, agonizing | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 가슴 | chest, heart (seat of emotion) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 떨리다 | to tremble, shake | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 설레다 | to flutter, be excited/nervous | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 운명 (運命) | fate, destiny | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 진실하다 (眞實) | to be sincere, true | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 감정 (感情) | emotion, feeling | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |

### Grammar points

**-다면서(요)? / (이)라면서(요)?** "I heard that...right?" — confirming something heard as hearsay
(설악산은 단풍이 아름답다면서요? "I heard Seoraksan's autumn foliage is beautiful, right?").

**~다고 하더니.** "[Someone] said... and then / but then..." (오늘 흐리겠다고 하더니 날씨가 아주
좋은데요 "They said it'd be cloudy today, but the weather's great!").

**-(으)ᆫ/는 데다가.** "In addition to ~, besides ~ing" (좋은 대학을 나온 데다가 집안도 좋고
잘생겼다고... "On top of graduating from a good university, his family background is good and
he's good-looking too...").

**한번 V-아/어 보기나 하다.** "To at least just try V-ing" (한번 만나 보기나 하세요 "At least give
meeting him a try").

**V-다 보면 / V-다 보니(까).** "If you keep V-ing.../ as a result of having kept V-ing..." (한국
사람들을 만나다 보면 한국말을 잘할 수 있을 겁니다 "If you keep meeting Korean people, you'll become
good at Korean").

**Idioms taught directly in-dialogue:**
- **바가지(를) 긁다** — "to nag" (lit. "to scrape a gourd ladle").
- **그림의 떡** — "pie in the sky, an unattainable thing" (lit. "rice cake in a painting").
- **비행기(를) 태우다** — "to flatter, butter someone up" (lit. "to put someone on a plane").
- **눈 빠지게 기다리다** — "to wait anxiously/eagerly" (lit. "to wait until one's eyes fall out").
- **입이 가볍다 / 입이 무겁다** — "to be loose-lipped, unable to keep a secret" / "to be discreet,
  tight-lipped" — this lesson's dialogue opens on exactly this contrast (지연 complains 무슨 남자가
  그렇게 입이 가벼울까 "what kind of man has such a loose mouth" about a friend who leaked her
  matchmaking-date gossip).

**Proverbs/idioms exercise list (explicitly taught as a set, p.62):**
- **바람맞다** — "to be stood up."
- **양다리(를) 걸치다** — "to two-time, play both sides" (lit. "to straddle both legs").
- **제 눈에 안경이다** — "beauty is in the eye of the beholder" (lit. "it's glasses to one's own
  eyes").
- **국수를 먹다** — euphemism for "to attend someone's wedding" (from the noodles traditionally
  served at Korean weddings).
- **검은 머리 파뿌리 되도록** — traditional wedding-blessing phrase, "[growing old together] until
  black hair turns to white leek-root."
- **깨가 쏟아지다** — "to be a blissfully happy couple" (lit. "sesame seeds spilling out") — describes
  a newlywed or deeply affectionate couple.

---

## Lesson 8: 한국말을 잘한다면서 칭찬해요 (They Compliment Me, Saying I Speak Korean Well)

Dialogue among foreign exchange students comparing first impressions of Seoul and the personal
questions (age, marital status, "why study Korean") Koreans commonly ask foreigners. **Notable
finding:** explicit cross-cultural-pragmatics framing — a Korean character states outright that such
blunt personal questions, even from strangers, are a sign of interest/concern (관심의 표현), not
rudeness, directly addressing a well-known source of culture-shock friction for foreign learners.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 아파트촌 (-村) | apartment-complex neighborhood | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 가득하다 | to be full | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 상상하다 (想像) | to imagine | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 한옥 (韓屋) | traditional Korean house | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 현대식 (現代式) | modern-style | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 당황하다 (唐慌) | to be flustered, embarrassed | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 더듬거리다 | to stammer, speak haltingly | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 엊그제 | the other day, a few days ago | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 세월 (歲月) | time, years passing | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 유창하다 (流暢) | to be fluent | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 다행이다 (多幸) | to be fortunate | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 쏜살같다 | to be as fast as an arrow | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | base for idiom below |
| 정신 (精神) | mind, spirit, attention | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 시설 (施設) | facility | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 작문 (作文) | composition writing | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 기대하다 (期待) | to expect, look forward to | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 조사하다 (調査) | to investigate, survey | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |

### Grammar points

**-다/자/냐/라면서.** Reports an indirect quotation ("saying that...") while simultaneously
expressing the speaker's own reaction — combines declarative/propositive/interrogative/copula
quotation endings with 면서 (아무도 안 다쳐서 다행이라면서 기뻐했어요 "They were happy, saying it
was fortunate no one got hurt").

**-(으)ᆫ 것이 엊그제 같다.** "It feels like just yesterday that..." (고등학교를 졸업한 것이
엊그제 같은데 벌써 10년이 지났네요 "It feels like I graduated high school just yesterday, but
already 10 years have passed").

**세월이 (쏜살같이) 빠르다[지나가다] (idiom).** "Time flies (like an arrow)."

**-(으)로 가득하다.** "To be full of..." (지갑이 동전으로 가득해서 무거워요 "My wallet is full of
coins, so it's heavy").

**-(으)냐든지 -(으)냐든지 (하다).** "Asking things like whether...or whether..." — lists a cluster
of alternative questions (한국말이 어려우냐든지 한국말을 왜 배우느냐든지 하는 질문을 많이 받았어요
"I got a lot of questions like whether Korean is hard, or why I'm learning Korean").

---

## Lesson 9: 친한 친구도 가족처럼 생각해요 (Even Close Friends Are Thought of Like Family)

**Central sociocultural finding of this third of the book.** A landlord is baffled that two close
friends (수지/바바라) each want their own separate room rather than sharing one — the dialogue
explicitly frames this as reflecting a Korean cultural assumption that close friendship implies
family-like intimacy (sharing space, resources, attention) in contrast to the individual-privacy
framing the foreign students bring from their own upbringing. A second thread: a boarding-house
landlady who nursed a sick foreign student "like her own biological mother," which the student
explicitly contrasts against the "burden" (부담) that same closeness can also create.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 흥미롭다 (興味) | to be interesting | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 추억 (追憶) | memory, reminiscence | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 돌아다니다 | to wander around | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 독방 (獨房) | a single room (for one person) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 관습 (慣習) | custom | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 자라다 | to grow up | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 자신 (自身) | oneself | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 갖다 | to have (contraction of 가지다) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 대(對)하다 | to treat, deal with | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 친어머니 (親-) | one's own (biological) mother | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 보살피다 | to look after, care for | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 부담 (負擔) | burden | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 정의롭다 (正義) | to be righteous, just | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 고통 (苦痛) | pain, suffering | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 판단하다 (判斷) | to judge | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 옳다 | to be right, correct | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 예절 (禮節) | etiquette, manners | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 개인 (個人) | individual | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 자유 (自由) | freedom | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 사생활 (私生活) | private life | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 여기다 | to regard, consider (as) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |

### Grammar points

**-롭다/답다 (adjective-forming suffix on a noun).** "To be ...-like" (자유롭다 "free," 정의롭다
"righteous," 평화롭다 "peaceful" — 나는 자유로운 새처럼 되고 싶어요 "I want to be like a free bird").

**그랬더니.** "And then, as a result" — connects a prior stated action to its consequence (배가
아프다고 했어요. 그랬더니 이 약을 주었어요 "I said my stomach hurt. They then gave me this
medicine").

**~을/를 ~게 여기다 / ~을/를 ~(으)로 여기다.** "To regard/consider X as ~" (그 사람은 사생활을
아주 중요하게 여깁니다 "That person considers privacy very important"; 나를 바보로 여기지 마세요
"Don't think of me as a fool").

**V-는 관습[습관, 사고방식].** "The custom [habit, way of thinking] of V-ing" (여자들만 집안일을
하는 관습은 고쳐야 해요 "The custom of only women doing housework should be changed").

**-더군(요).** Expresses a direct, first-hand realization/observation (지난번 시험은 생각보다
어렵지 않더군요 "The last exam wasn't as hard as I thought, [I noticed]").

---

## Lesson 10: 백성들의 도움으로 살아나곤 했대요 ("They say he survived thanks to the people's help")

PDF pp. 81–92. Reading passage recounts the historical/legendary Joseon-era outlaw **임꺽정 (Im
Kkeok-jeong)** — a "righteous bandit" (의적) figure, comparable in folk function to a Robin Hood
archetype, who stole from the corrupt nobility (양반) and helped the poor commoner/lowborn class
(백성/천민) during a period of harsh class rule. Genuine sociocultural/historical content, not
merely grammar drill.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 고려 (高麗) | Goryeo (Korean dynasty, 918–1392) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | historical-period term |
| 조선 (朝鮮) | Joseon (Korean dynasty, 1392–1910) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | historical-period term |
| 세기 (世紀) | century | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 안정(安定)되다 | to be stable, settled | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 시대 (時代) | era, period | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 지배 (支配) | rule, domination | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 계급 (階級) | (social) class | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 양반 (兩班) | yangban (Joseon-era aristocratic class) | noun | core | — | — | Korea | national | grammar_reference | n/a | n/a | historically/culturally specific |
| 국가 (國家) | nation, state | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 덕분 (德分) | favor, thanks (to) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | base of grammar pt. 덕분에 |
| 초 (初) | beginning, early period | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 권력 (權力) | power (political/social) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 함부로 | recklessly, carelessly | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 열중(熱中)하다 | to be absorbed/engrossed in | verb | core | — | — | — | — | grammar_reference | n/a | n/a | base of grammar pt. |
| 경우 (境遇) | case, situation | noun | core | — | — | — | — | grammar_reference | n/a | n/a | base of grammar pt. |
| 의적 (義賊) | righteous bandit, "noble thief" | noun | literary | — | — | — | — | grammar_reference | n/a | n/a | Robin-Hood-type folk archetype |
| 원래 (元來) | originally | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 천민 (賤民) | lowborn/base-class person | noun | historical | — | — | Korea | national | grammar_reference | n/a | n/a | Joseon-era social-class term |
| 비록 | although, even though | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | base of grammar pt. 비록 ~지만 |
| 무식(無識)하다 | to be uneducated, illiterate | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 나누다 | to divide, share | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 결국 (結局) | in the end, eventually | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 사형 (死刑) | death penalty | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 당(當)하다 | to suffer/undergo (a misfortune) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | passive-sense verb, base of 을/를 당하다 |
| 이루다 | to achieve, realize (a dream/goal) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 짜다 | to be salty | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 해고 (解雇) | dismissal, firing (from a job) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 목적 (目的) | purpose, goal | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |

### Grammar points

**-곤 하다** — marks habitual/repeated action ("used to ~, tends to ~").

**(해)에 들어와서** — "once/since entering [a given year/period]," a time-transition marker for marking a turning point ("since the 20th century began...").

**덕분에[으로]** — "thanks to ~," attributing a good outcome to someone's help or favor; also takes a verb modifier, V-(으)ᄂ/는 덕분에.

**-는 데(에) 열중하다[열중이다]** — "to be absorbed/engrossed in (doing) ~."

**경우가 (많이) 있다[없다]** — "there are (often) cases where ~."

**-(으)ᄂ/는/(으)ᄅ 경우(에)(는)** — "in the case/situation that ~."

**비록 ~지만** — "although ~" (concessive, slightly more formal/literary than plain -지만 alone).

**-아/어다(가)** — marks carrying the result/state of one action to perform a second action elsewhere (e.g. borrowing a book *and bringing it* to read elsewhere).

**을/를 당하다** — passive-sense construction for suffering a negative event (예: 유괴를 당했다 "was kidnapped"); the agent of the event can be restated actively in parentheses as a teaching contrast.

---

## Lesson 11: 지역에 따라 차이를 보였습니다 ("[The results] showed differences depending on the region")

PDF pp. 93–102. A simulated radio/news broadcast report (기자 보도 register) on private
after-school tutoring (과외) costs in Seoul, contrasting the affluent **강남 (Gangnam)** district
(69% of students in private tutoring) against **강북 (Gangbuk)** districts (39%) — explicit
socioeconomic/geographic disparity reporting, plus a follow-on survey exercise on travel habits.
Good source of formal broadcast-news register and statistic-citing sentence patterns.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 과외 (課外) | private/after-school tutoring | noun | core | — | — | Korea | national | grammar_reference | n/a | n/a | culturally loaded (Korean education system) |
| 기자 (記者) | reporter, journalist | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 보도 (報道) | news report | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 대상 (對象) | target, object (of a survey/study) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | base of grammar pt. |
| 나타나다 | to appear, emerge, turn out (to be) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 구 (區) | (administrative) district | noun | core | — | — | Korea | national | grammar_reference | n/a | n/a | |
| 강남 (江南) | Gangnam (district south of the Han River, Seoul) | proper noun | core | — | — | Seoul | local | grammar_reference | n/a | n/a | affluent-district connotation flagged by this lesson's own content |
| 강북 (江北) | Gangbuk (district north of the Han River, Seoul) | proper noun | core | — | — | Seoul | local | grammar_reference | n/a | n/a | contrasted against 강남 in-text |
| 상당(相當)히 | considerably, quite | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 근로자 (勤勞者) | worker, laborer | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 실제 (實際)로 | actually, in reality | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 시키다 | to make/have someone do; to order | verb | core | — | — | — | — | grammar_reference | n/a | n/a | base of grammar pt. |
| 대부분 (大部分) | most, the majority | noun/adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 입시 (入試) | entrance examination | noun | core | — | — | Korea | national | grammar_reference | n/a | n/a | |
| 제도 (制度) | system, institution | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 원(願)하다 | to wish, want | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 서비스 | service | noun | core | — | — | — | — | grammar_reference | n/a | n/a | English loanword |
| 주택 (住宅) | housing, residence | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 심부름 | errand | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 실시(實施)하다 | to implement, carry out | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 결과 (結果) | result | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 응답자 (應答者) | respondent (to a survey) | noun | technical | — | — | — | — | grammar_reference | n/a | n/a | survey/statistics register |
| 세면도구 (洗面道具) | toiletries | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 휴대(携帶)폰 | cell phone | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 카세트 | cassette (tape) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | English loanword; dated technology, consistent with book's unknown-but-older publication era |
| 자장면 | jajangmyeon (noodles in black-bean sauce) | noun | core | — | — | Korea | national | grammar_reference | n/a | n/a | popular Korean-Chinese dish |
| 초등학교 (初等學校) | elementary school | noun | core | — | — | Korea | national | grammar_reference | n/a | n/a | |
| 엎드리다 | to lie face down, prostrate oneself | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 통계 (統計) | statistics | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 시기 (時期) | period, time | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 단위 (單位) | unit | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 취업 (就業) | employment, job-hunting | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 적당(適當)하다 | to be appropriate, suitable | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 보름 | 15 days; half a month | noun | core | — | — | — | — | grammar_reference | n/a | n/a | also the lunar-calendar "15th day" sense, relevant again in Lesson 18 |

### Grammar points

**N에 따라 차이를 보이다[차이가 있다/차이가 나다]** — "differs according to N."

**가운데** — "among, in the middle of" (a group); also literally "the middle" (spatial).

**-(으)ᄂ/는 것으로 나타나다[조사되다]** — "according to a survey/investigation, it appears/was found that ~" — the book's own formal reporting-register construction for citing survey results.

**N을/를 대상으로 조사하다[연구하다]** — "to survey/study [with N as the target]."

**-(으)ᄂ/는 셈이다** — "it amounts to ~, can be said to be ~" (a logical-inference/evaluative construction, distinct from literal statement).

**-(으)므로** — "because, since" — more formal/written-register causal connective than -기 때문에/-(으)니까, explicitly glossed by the source as equivalent in meaning but more formal in register.

**N을/를 시키다 / V-(으)라고 시키다** — "to make/have someone do (N / V)."

---

## Lesson 12: 어떻게 생각하느냐에 따라 다르지 ("It differs depending on how you think")

PDF pp. 103–114. Opens with the well-known Korean folktale of the **umbrella-seller and fan-seller
sons** (우산장수와 부채장수): a mother with two sons (one selling fans, one selling umbrellas)
worries on every kind of day because she always imagines the worst for one son or the other, while
her neighbor with the same two trades is happy on every kind of day because she always imagines the
best — a didactic parable about outlook/mindset (cf. "positive thinking," 긍정적 vs. 부정적).
Followed by a dialogue about a student considering repeating a year (재수) before a college
entrance exam.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 생계 (生計) | livelihood | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 잇다 | to connect, continue (without a break) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 한숨 | a sigh | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 놀림 | teasing, mockery | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 웃음거리 | laughing stock | noun | colloquial | — | — | — | — | grammar_reference | n/a | n/a | -거리 "material for ~" suffix, see grammar pt. |
| 끊이다 | to stop, cease (continuously) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 신(이) 나다 | to get excited, be in high spirits | verb (idiom) | colloquial | — | — | — | — | grammar_reference | n/a | n/a | |
| 함박웃음 | a broad/beaming smile | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 터지다 | to burst out (of laughter, etc.) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 재수(再修)하다 | to repeat a year of study to retake an exam | verb | core | — | — | Korea | national | grammar_reference | n/a | n/a | tied to Korea's competitive college-entrance-exam culture |
| 포기(抛棄)하다 | to give up | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 화제 (話題) | topic (of conversation) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 자식 (子息) | children (son(s)/daughter(s)) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 코미디언 | comedian | noun | core | — | — | — | — | grammar_reference | n/a | n/a | English loanword |
| 제목 (題目) | title | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 떨어지다 | to fail (an exam) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 비교(比較)하다 | to compare | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 우거지다 | to be overgrown, lush (of vegetation) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 시절 (時節) | a time, period (of one's life) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 끝 | end | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 긍정적 (肯定的) | positive (outlook, attitude) | adjective/noun | core | — | — | — | — | grammar_reference | n/a | n/a | thematic keyword of this lesson's folktale |
| 부정적 (否定的) | negative (outlook, attitude) | adjective/noun | core | — | — | — | — | grammar_reference | n/a | n/a | thematic keyword of this lesson's folktale |

### Grammar points

**-느냐에 따라 다르다** — "differs depending on how/whether ~" (the question-form nominalizer -느냐 feeding into the N에 따라 다르다 pattern already seen in Lesson 11).

**-거리** — a productive suffix meaning "material/matter for ~": 웃음거리 "laughing matter," 화젯거리 "topic of conversation," 반찬거리 "ingredients for a side dish."

**-(으)나 -(으)나** — "whether ~ or ~" (concessive parallel structure): 비가 오나 눈이 오나 "whether it rains or snows."

**-(으)ᄅ 게 뻔하다** — "it's obviously going to be ~, it's certain that ~" (confident prediction, often of something undesirable).

---

## Lesson 13: 아빠가 밥을 해 준다고 놀려요 ("They tease her that her dad cooks for her")

PDF pp. 115–122. A stay-at-home-cartoonist father in a dual-income household (맞벌이 부부)
routinely cooks for his first-grade daughter; she is teased by classmates for having a father who
cooks rather than a mother. The lesson uses this as a springboard for an explicit discussion of
**Confucian-rooted gender-role expectations** (유교적 사고방식) still dominant (지배적) in Korean
society, and gender equality (남녀평등) vs. gender discrimination (남녀차별). The closing
discussion prompt directly invokes the line "여자로 태어나는 것이 아니라 여자로 만들어진다" ("One
is not born, but rather becomes, a woman" — Simone de Beauvoir, *The Second Sex*) as a discussion
seed, a notable explicit literary/feminist-theory citation for a language-course reading.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 맞벌이 | dual-income (household, both spouses working) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 직장 (職場) | workplace | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 시무룩하다 | to be sullen, sulky | adjective | colloquial | — | — | — | — | grammar_reference | n/a | n/a | |
| 표정 (表情) | facial expression | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 막 | very, exceedingly (intensifier, colloquial) | adverb | colloquial | — | — | — | — | grammar_reference | n/a | n/a | distinct from the more common "just (now)" sense of 막 |
| 부럽다 | to be envious (of) | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | base of grammar pt. |
| 오히려 | rather, on the contrary | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 사실 (事實) | fact; actually | noun/adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 편견 (偏見) | prejudice, bias | noun | core | — | — | — | — | grammar_reference | n/a | n/a | thematic keyword |
| 유교적 (儒敎的) | Confucian | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | explicit sociocultural framing term in-text |
| 지배적 (支配的) | dominant | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 남녀평등 (男女平等) | gender equality | noun | core | — | — | — | — | grammar_reference | n/a | n/a | thematic keyword |
| 한산(閑散)하다 | to be quiet, slack, uncrowded | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 억지로 | forcibly, reluctantly | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 기본적 (基本的) | basic | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 성능 (性能) | performance, function (of a machine) | noun | technical | — | — | — | — | grammar_reference | n/a | n/a | |
| 남녀차별 (男女差別) | gender discrimination | noun | core | — | — | — | — | grammar_reference | n/a | n/a | thematic keyword |
| 사회적 (社會的) | social | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |

### Grammar points

**N와/과 달리** — "unlike N" (= N와/과 다르게).

**N이/가 부럽다 / -(으)ᄂ/는 것이 부럽다** — "to envy N / to envy the fact that ~."

**-고말고(요)** — "of course ~!" — an emphatic affirmation ending, also usable after a noun/adjective base (N(이)고말고(요)).

**오히려** — "rather, on the contrary" (adverb marking an outcome opposite to expectation).

**그렇다고 -(으)ᄂ/는 것은 아니다** — "that doesn't necessarily mean ~" — a hedge against an over-generalized inference from a preceding statement.

**-만 -아/어도 어딘데(요)** — "even just ~ is already pretty great/significant" — a colloquial construction for praising a partial or modest contribution.

---

## Lesson 14: 한국어 가르치는 데에 더 몰두하게 돼요 ("[I've] become more absorbed in teaching Korean")

PDF pp. 123–130. A dialogue with a **한국어 교사 (Korean-as-a-foreign-language teacher)** who
explicitly distinguishes her role from a **국어 교사** (native-Korean-literacy teacher for Korean
students) — the former teaches foreigners and overseas Koreans (교포) to use the language, the
latter refines native speakers' usage. She explains why she finds teaching Korean to foreigners/
heritage learners rewarding. This lesson's content is meta-linguistically notable: it is the
source's own explicit vocabulary and framing for the native-language-instruction vs. foreign/
heritage-language-instruction distinction, directly adjacent to this project's own domain of
language pedagogy and learner material.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 몰두(沒頭)하다 | to be absorbed/engrossed in | verb | core | — | — | — | — | grammar_reference | n/a | n/a | base of grammar pt. |
| 중점 (重點) | emphasis, focal point | noun | core | — | — | — | — | grammar_reference | n/a | n/a | base of grammar pt. |
| 저절로 | automatically, naturally, by itself | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 임무 (任務) | duty, mission | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 대개 | mostly, generally | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 선택 (選擇) | choice, selection | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 폭 (幅) | width, range, scope | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 스스로 | on one's own, voluntarily | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 보람 | a sense of fulfillment/worth (from an effort) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | thematic keyword of this lesson |
| 한마디 | a single word/remark | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 발걸음 | footstep | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 산업 (產業) | industry | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 파괴(破壞)하다 | to destroy | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 전체 (全體) | the whole, entirety | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 꺼지다 | to go out, be extinguished (passive of 끄다) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 다양(多樣)하다 | to be diverse, various | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 내용 (內容) | content | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 필요성 (必要性) | necessity | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |

### Grammar points

**-는 데(에) 몰두하다 / N에 몰두하다** — "to be absorbed in (doing) ~ / to be absorbed in N."

**N에 중점을 두다 / -는 데(에) 중점을 두다** — "to place emphasis/focus on N / on doing ~."

**V-는 사이(에)** — "while ~, during the time that ~."

**N에 의해(서)** — "by/according to N" (agent or basis marker, more formal/written-register than a plain subject particle in this function).

**-다/자/나/라니까** — a quotative-emphasis ending used when reporting one's own prior statement as the reason for a following clause ("since I said ~, ...").

---

## Lesson 15: 약도 좋지만 쉬는 게 제일이야 ("Medicine is good, but rest is best")

PDF pp. 131–142. Opens with a (fictional, in-world) magazine warning of a catastrophic future flu
pandemic, explicitly citing the real 1918 influenza pandemic (~10 million infected, ~20 million
dead within months, more than double the WWI death toll) as historical precedent, followed by a
doctor–patient dialogue about a child's cold. This lesson carries the richest **medicine/pharmacy
vocabulary field** found so far in this volume (해열제/진통제/소화제/안약, etc.) plus register
around illness description.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 최악 (最惡) | the worst | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 재앙 (災殃) | disaster, calamity | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 가능성 (可能性) | possibility | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 조만간 (早晚間) | sooner or later | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 강타(強打)하다 | to strike hard, hit hard | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 최신 (最新) | newest, latest | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 호 (號) | issue (of a periodical) | noun | technical | — | — | — | — | grammar_reference | n/a | n/a | |
| 경고(警告)하다 | to warn | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 불과 (不過) | merely, only | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | base of grammar pt. |
| 억 (億) | hundred million | numeral | core | — | — | — | — | grammar_reference | n/a | n/a | Sino-Korean large-number unit |
| 목숨 | life | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 위력 (偉力) | might, power | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 닥쳐오다 | to approach, draw near (of an impending event) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 전(傳)하다 | to convey, report | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 희생자 (犧牲者) | victim | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 달(達)하다 | to reach, amount to | verb | core | — | — | — | — | grammar_reference | n/a | n/a | base of grammar pt. |
| 중세 (中世) | the medieval period | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 밝히다 | to reveal, state clearly | verb | core | — | — | — | — | grammar_reference | n/a | n/a | base of grammar pt. |
| 습격 (襲擊) | attack, raid | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 인명 (人命) | human life | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 일단 (一旦) | once; for now, first | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | base of grammar pt. |
| 발생(發生)하다 | to occur, arise | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 전 (全) | whole, all | determiner | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 확산(擴散)되다 | to spread, diffuse | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 예방 (豫防) | prevention | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 주사약 (注射藥) | injectable medicine | noun | technical.medical | — | — | — | — | grammar_reference | n/a | n/a | |
| 개발(開發)하다 | to develop | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 소용(所用)없다 | to be useless | adjective (idiom) | core | — | — | — | — | grammar_reference | n/a | n/a | base of grammar pt. |
| 전망(展望)하다 | to forecast, foresee | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 증세 (症勢) | symptom | noun | technical.medical | — | — | — | — | grammar_reference | n/a | n/a | |
| 벌리다 (입을) | to open (one's mouth) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 붓다 | to swell | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| -치 | counter suffix: "a portion/dose (of time)" | suffix | core | — | — | — | — | grammar_reference | n/a | n/a | e.g. 이틀치 "two days' worth [of medicine]" |
| 처방(處方)하다 | to prescribe | verb | technical.medical | — | — | — | — | grammar_reference | n/a | n/a | |
| 지독(至毒)하다 | to be severe, harsh (of an illness, etc.) | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 폭 | deeply, soundly (sleeping) | adverb | colloquial | — | — | — | — | grammar_reference | n/a | n/a | collocates with 자다 "폭 자다" |
| 놀랍다 | to be surprising | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 심장병 (心臟病) | heart disease | noun | technical.medical | — | — | — | — | grammar_reference | n/a | n/a | |
| 상황 (狀況) | situation | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 후회(後悔)하다 | to regret | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 우정 (友情) | friendship | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 딱 | exactly, precisely | adverb | colloquial | — | — | — | — | grammar_reference | n/a | n/a | |
| 풀리다 (피로가) | (fatigue) to be relieved | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 소화제 (消化劑) | digestive medicine | noun | technical.medical | — | — | — | — | grammar_reference | n/a | n/a | part of this lesson's pharmacy-vocabulary field |
| 통증 (痛症) | pain | noun | technical.medical | — | — | — | — | grammar_reference | n/a | n/a | |
| 진통제 (鎮痛劑) | painkiller | noun | technical.medical | — | — | — | — | grammar_reference | n/a | n/a | |
| 안약 (眼藥) | eye drops | noun | technical.medical | — | — | — | — | grammar_reference | n/a | n/a | |
| 해열제 (解熱劑) | fever reducer | noun | technical.medical | — | — | — | — | grammar_reference | n/a | n/a | |

### Grammar points

**불과 N만에** — "in merely/only N (amount of time)."

**N에 달하다** — "to reach, amount to N."

**-다고[라고] 밝히다** — "to state/reveal that ~" (reported-speech, formal/journalistic register).

**일단 -(으)면** — "once ~, if ~" (marks the first step of a conditional sequence).

**-다 하더라도** — "even if/granting that ~."

**소용(이) 없다** — idiomatic "it's useless, no use."

**-더니만** — attaches to an adjective/verb to mark a prior observed state/event as the cause or setup for a following (often contrastive or surprising) result; an intensified variant of -더니.

---

## Lesson 16: 미리 연락을 하면 달려가 발이 되겠습니다 ("If you contact us ahead of time, we'll rush to be your legs")

PDF pp. 143–152. Reading passage describes a volunteer organization's advertisement offering
transportation assistance to disabled people (장애인) who otherwise cannot go out unassisted,
followed by a dialogue critiquing Korea's shortage of disability-accessible public infrastructure
— the source cites a (book's-own-era) statistic that only 28% of Korean public institutions/transit
facilities had disability accommodations installed, and stresses that physical facilities alone are
insufficient without a broader social attitude of ongoing concern for disabled people. Genuine
disability-advocacy sociocultural content.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 외출(外出)하다 | to go out, leave the house | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 장애인 (障碍人) | a person with a disability | noun | core | — | — | — | — | grammar_reference | n/a | n/a | thematic keyword |
| 자원(自願)하다 | to volunteer (oneself) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 봉사 (奉仕) | service, volunteering | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 단체 (團體) | organization, group | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 문구 (文句) | phrase, wording | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 힘 | strength, power | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 운전기사 (運轉技士) | driver | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 역할 (役割) | role | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 미치다 (수에) | to reach, amount to (a number) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | distinct homophone from 미치다 "to go crazy" |
| 공공기관 (公共機關) | public institution | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 설치율 (設置率) | installation rate | noun | technical | — | — | — | — | grammar_reference | n/a | n/a | |
| 지나지 않다 | to be no more than | verb phrase (idiom) | core | — | — | — | — | grammar_reference | n/a | n/a | base of grammar pt. N에 지나지 않다 |
| 겨우 | barely, with difficulty | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 대중 (大衆) | the masses, general public | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 몰라보게 | unrecognizably (so much so one can't recognize it) | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | base of grammar pt. |
| 그리 (-지 않다) | not that/so (much) | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | base of grammar pt., occurs only with a following negative |
| 좀처럼 (-지 않다) | rarely, not easily | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | occurs only with a following negative |
| 자세 (姿勢) | attitude, stance (figurative); posture (literal) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 평범(平凡)하다 | to be ordinary, unremarkable | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 말다툼 | a quarrel, argument | noun | colloquial | — | — | — | — | grammar_reference | n/a | n/a | |
| 가입(加入)하다 | to join (an organization) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 장벽 (障壁) | barrier | noun | core | — | — | — | — | grammar_reference | n/a | n/a | thematic keyword (used metaphorically for social barriers to the disabled) |
| 전용 (專用) | exclusive/dedicated use | noun | core | — | — | — | — | grammar_reference | n/a | n/a | e.g. 장애인 전용 주차장 "disabled-only parking" |

### Grammar points

**-는 데 반해** — "whereas, while [in contrast]" — contrastive connective.

**N에 지나지 않다** — "to be nothing more than N."

**아닌 게 아니라** — idiomatic "indeed, as a matter of fact" (agreement/confirmation opener).

**몰라보게 V** — "so much that one wouldn't recognize it" (used adverbially before a verb of change, e.g. growth, development).

**그리 -지 않다** — "not all that ~" (negative-polarity degree adverb).

**-(으)ᄂ/는 듯하다 / -(으)ᄅ 듯하다** — "it seems that ~ / it seems like it's about to ~."

**-(으)려고만 들다** — "if one is only willing to try to ~" (conditional on sheer willingness/intent).

---

## Lesson 17: 설날은 큰 명절 중의 하나예요 ("Seollal is one of the major holidays")

PDF pp. 153–164. A dedicated sociocultural lesson on **설날 (Seollal, Lunar New Year)** customs:
설빔 (new holiday clothes — 바지저고리/두루마기 for adults, 색동옷 for children), 세배 (New Year's
bow/greeting to elders) and 세뱃돈 (money given to children after 세배), 차례 (ancestral-rite food
offering performed on the holiday morning), and 덕담 (well-wishing words given to younger
visitors). A strong source of Korean holiday-specific sociocultural vocabulary.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 명절 (名節) | a traditional holiday | noun | core | — | — | Korea | national | grammar_reference | n/a | n/a | |
| 풍속 (風俗) | custom, tradition | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 독특(獨特)하다 | to be unique, distinctive | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 정월 (正月) | the first lunar month | noun | core | — | — | Korea | national | grammar_reference | n/a | n/a | lunar-calendar term |
| 설빔 | new clothes worn for Seollal | noun | core | — | — | Korea | national | grammar_reference | n/a | n/a | holiday-specific realia term |
| 저고리 | jeogori (upper garment of hanbok) | noun | core | — | — | Korea | national | grammar_reference | n/a | n/a | |
| 두루마기 | durumagi (traditional long outer coat) | noun | core | — | — | Korea | national | grammar_reference | n/a | n/a | |
| 색동 (色–) | colorful striped fabric pattern | noun | core | — | — | Korea | national | grammar_reference | n/a | n/a | associated with children's holiday clothing (색동옷) |
| 손꼽다 | to count on one's fingers | verb | core | — | — | — | — | grammar_reference | n/a | n/a | base of idiom 손꼽아 기다리다 |
| 섣달 | the twelfth lunar month | noun | core | — | — | Korea | national | grammar_reference | n/a | n/a | lunar-calendar term |
| 그믐날 | the last day of a (lunar) month | noun | core | — | — | Korea | national | grammar_reference | n/a | n/a | |
| 새우다 (밤을) | to stay up all night | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 짓다 (옷을) | to make (clothing) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 세배 (歲拜) | New Year's bow/greeting to elders | noun | core | — | — | Korea | national | grammar_reference | n/a | n/a | thematic keyword |
| 세뱃돈 (歲拜–) | money given to children after 세배 | noun | core | — | — | Korea | national | grammar_reference | n/a | n/a | thematic keyword |
| 조상 (祖上) | ancestor(s) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 차례 (茶禮) | ancestral-rite food offering performed on a holiday | noun | core | — | — | Korea | national | grammar_reference | n/a | n/a | not to be confused with homophone 차례 "turn, order" |
| 내놓다 (음식을) | to put out, serve (food) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 희망 (希望) | hope | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 차다 | to be full (of) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | base of grammar pt. ~에 (가득) 차다 |
| 덕담 (德談) | well-wishing words spoken to a younger/junior person at a holiday | noun | core | — | — | Korea | national | grammar_reference | n/a | n/a | thematic keyword |
| 국립 (國立) | national, state-founded (institution) | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 버선 | beoseon (traditional Korean socks) | noun | core | — | — | Korea | national | grammar_reference | n/a | n/a | |

### Grammar points

**N은/는 N 중의 하나이다 / N은/는 N의 하나이다** — "N is one of N(s)."

**N에 N을/를 입다[신다, 쓰다]** — "to wear/pair N with N" (matching an item of clothing to another).

**손꼽아 기다리다** — idiomatic "to count the days eagerly (looking forward to something)," literally "to wait while counting on one's fingers."

**~에 (가득) 차다** — "to be (fully) filled with ~" (emotion or quality).

---

## Lesson 18: 윷놀이는 아이나 어른 할 것 없이 다 좋아해요 ("Everyone, child or adult, likes playing Yunnori")

PDF pp. 165–169. A dedicated sociocultural lesson on traditional Korean New Year's games:
**윷놀이 (Yunnori)**, the four-stick throwing-and-board game with its five scoring outcomes
(도/개/걸/윷/모) and board terminology (윷판, 윷말), and **연날리기/연싸움** (kite flying and
kite-fighting), including how a traditional Korean kite (대나무 틀에 한지를 붙여 만든 연, in
triangular/square/diamond shapes) differs from kites elsewhere. A listening exercise adds
**대보름 (Daeboreum, the 15th day of the first lunar month)** customs: eating nuts (밤/잣/호두/
땅콩) at dawn (believed to prevent skin problems and to help wishes come true) and crossing a
bridge twelve times in the evening (believed to prevent leg pain through the year).

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 윷놀이 | Yunnori (traditional four-stick board game) | noun | core | — | — | Korea | national | grammar_reference | n/a | n/a | thematic keyword |
| 막대기 | stick, rod | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 평평(平平)하다 | to be flat, level | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 둥글다 | to be round | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 던지다 | to throw | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 바닥 | floor, ground | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 도 | Yunnori throw: 1 flat side up (lowest score) | noun | technical | — | — | Korea | national | grammar_reference | n/a | n/a | game-specific term |
| 개 | Yunnori throw: 2 flat sides up | noun | technical | — | — | Korea | national | grammar_reference | n/a | n/a | game-specific term |
| 걸 | Yunnori throw: 3 flat sides up | noun | technical | — | — | Korea | national | grammar_reference | n/a | n/a | game-specific term |
| 윷 | Yunnori throw: all 4 flat sides up | noun | technical | — | — | Korea | national | grammar_reference | n/a | n/a | also the name of the game pieces/sticks themselves |
| 모 | Yunnori throw: all 4 round sides up (highest score) | noun | technical | — | — | Korea | national | grammar_reference | n/a | n/a | game-specific term |
| 구별(區別)하다 | to distinguish, differentiate | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 매기다 (점수를) | to assign/give (a score) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 판 (板) | board, plank | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 편 (便) | a team, side | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 윷말 | Yunnori game piece/marker | noun | technical | — | — | Korea | national | grammar_reference | n/a | n/a | game-specific term |
| 상대방 (相對方) | the other party, opponent | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 나다 | to come out, result (in an outcome) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 쪽 | side | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 응원(應援)하다 | to cheer for, root for | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 연 (鳶) | kite | noun | core | — | — | Korea | national | grammar_reference | n/a | n/a | |
| 날리다 | to fly (something), let fly | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 대나무 | bamboo | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 틀 | frame | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 한지 (韓紙) | traditional Korean paper | noun | core | — | — | Korea | national | grammar_reference | n/a | n/a | |
| 세모 | triangle | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 네모 | square/quadrilateral | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 마름모 | rhombus, diamond shape | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 얼레 | a spool/reel for kite string | noun | technical | — | — | Korea | national | grammar_reference | n/a | n/a | kite-flying-specific term |
| 조절(調節)하다 | to adjust, regulate | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 농촌 (農村) | farming village, rural area | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 대보름 (大보름) | Daeboreum (15th day of the 1st lunar month) | noun | core | — | — | Korea | national | grammar_reference | n/a | n/a | thematic keyword, lunar-calendar festival |
| 감자 | potato | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 고구마 | sweet potato | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 밤 | chestnut | noun | core | — | — | — | — | grammar_reference | n/a | n/a | homophone of 밤 "night," distinct lexical item |
| 잣 | pine nut | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 호두 | walnut | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 땅콩 | peanut | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 피부 (皮膚) | skin | noun | core | — | — | — | — | grammar_reference | n/a | n/a | tied to the Daeboreum nut-eating folk belief |
| 짓다 (농사를) | to farm, cultivate (fields) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |

### Grammar points

**N(이)(나) N(이)(나) 할 것 없이** — "regardless of whether it's N or N, without exception" (= "no matter who/what").

**V-기에 좋다** — "to be good/suitable for ~ing."

---

## Lesson 19: 마음만 먹으면 생명을 구할 수 있어요 ("If You Set Your Mind to It, You Can Save a Life")

PDF pp. 170–181. Topic: a magazine-style interview about refugee crises (Rwanda, Cambodia) and a
reporter's reflections on humanitarian aid; register is formal spoken/written (기자 interview
frame).

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 구(救)하다 | to save, rescue | verb | core | — | — | — | — | grammar_reference | n/a | n/a | lit. "to help (someone) escape difficulty" |
| 중동(中東) | the Middle East | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 아프리카 | Africa | noun | core | — | — | — | — | grammar_reference | n/a | n/a | loanword |
| 분야(分野) | field, domain | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 난민(難民) | refugee | noun | core | — | — | — | — | grammar_reference | n/a | n/a | def. "a person who lost their home to war or disaster" |
| 르완다 | Rwanda | proper noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 캄보디아 | Cambodia | proper noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 상관(相關) | connection, relation | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 난민촌(難民村) | refugee camp | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 삽시간(霎時間)에 | in an instant | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | OCR renders as "삼시간" — correct form is 삽시간 |
| 번지다 | to spread (to elsewhere) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 떠돌다 | to wander, drift | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 상태(狀態) | state, condition | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 삼키다 | to swallow | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 피해자(被害者) | victim | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 차지하다 | to occupy, account for | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 누군가 | someone | pronoun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 소련(蘇聯) | the Soviet Union | proper noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 대결(對決) | confrontation, standoff | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 사라지다 | to disappear | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 서서(徐徐)히 | gradually, slowly | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 생기(生氣) | vitality, vigor | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 겨우 | barely, only | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 지속적(持續的) | continuous, sustained | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 누워서 떡 먹기 | "a piece of cake" | idiom | core | — | — | — | — | grammar_reference | n/a | n/a | lit. "eating rice cake lying down" — a very easy task |
| 짐작(斟酌)하다 | to guess, surmise | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 꼴찌 | last place | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 통(通) | counter for phone calls/letters | counter | core | — | — | — | — | grammar_reference | n/a | n/a | e.g. 전화 한 통 "one phone call" |
| 소득(所得) | income | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 걷다(돈을) | to collect (money) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | homograph of 걷다 "to walk" |
| 충격(衝擊) | shock, impact | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 아스피린 | aspirin | noun | core | — | — | — | — | grammar_reference | n/a | n/a | loanword |
| 유니세프 | UNICEF | proper noun | core | — | — | — | — | grammar_reference | n/a | n/a | glossed in-source as 국제연합아동기금 |
| 굶주림 | starvation, hunger | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 모금(募金)하다 | to raise funds, collect donations | verb | core | — | — | — | — | grammar_reference | n/a | n/a | from dialogue-box word list; not in end-of-lesson table |
| 시각(時刻) | (point in) time, moment | noun | core | — | — | — | — | grammar_reference | n/a | n/a | from dialogue-box word list; not in end-of-lesson table |

### Grammar points

**-기는커녕 / N은/는커녕 ("far from X — not even Y").** Attached to a verb stem or noun, states
that not only did the expected thing not happen, but something even more basic also failed: 설날에
떡국을 먹기는커녕 밥도 제대로 못 먹었어요 "far from eating rice-cake soup on New Year's, I
couldn't even eat a proper meal."

**-(으)ㄹ 수조차 없다 / V-기조차 / N조차 ("not even able to / not even N").** 조차 ("even")
stacks onto ability-negation (-(으)ᄅ 수조차 없다), a verb nominalized with -기 (V-기조차), or
directly onto a noun, always in a negative-leaning context: 너무 슬퍼서 울 수조차 없어요 "I was so
sad I couldn't even cry."

**-(으)리라(고) 생각하다[믿다, 짐작하다] ("to think/believe/guess that...").** A literary/formal
conjecture ending (-(으)리라) that attaches to the dependent-conjecture verbs 생각하다/믿다/짐작하다
rather than the more colloquial -(으)ᄅ 거라고: 선생님께서는 건강하게 잘 지내시리라 믿습니다 "I
believe the teacher is doing well."

**N은/는 고사(姑捨)하고 ("not to mention N, let alone N").** Functionally parallel to -기는커녕
but attaches to a bare noun: 점심은 고사하고 아직 아침도 못 먹었어요 "not to mention lunch, I
haven't even had breakfast yet."

**-는 한(限) ("as long as, so long as").** Conditional/limiting connective: 전쟁이 있는 한 난민도
사라지지 않을 겁니다 "as long as there is war, refugees won't disappear either."

**N당(當) ("per N").** A bound noun-suffix for rates: 난민 한 사람당 겨우 하루 80원 "a mere 80 won
per refugee per day"; 시간당 "per hour."

---

## Lesson 20: 누가 한잔 사겠다고 안 하나? ("Doesn't Anyone Want to Buy a Drink?")

PDF pp. 182–191. Topic: Korean corporate drinking culture (회식/술자리) explained to a Japanese
expat colleague, Tanaka — a strong sociocultural-register lesson.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 동료(同僚) | colleague, co-worker | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 소리 | talk, words (fig.); sound (lit.) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 직장인(職場人) | office worker | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 퇴근(退勤)하다 | to leave work, get off work | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 술자리 | a drinking occasion/gathering | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 연속(連續) | continuation, succession | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 거래(去來)하다 | to do business, trade | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 상담(相談) | consultation | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 원만(圓滿)하다 | to be smooth, amicable | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 대인 관계(對人關係) | interpersonal relationships | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 맺다 | to form, tie (a bond) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 최고(最高) | best, highest | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 향(向)하다 | to head toward | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 상사(上司) | one's superior/boss | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 친밀감(親密感) | sense of closeness | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 은근(慇懃)히 | subtly, secretly, in one's heart | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 가끔 | sometimes, occasionally | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 실수(失手)하다 | to make a mistake | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 첨잔(添盞) | topping off a glass that isn't empty yet | noun | core | — | — | — | — | grammar_reference | n/a | n/a | explicit Korean-vs-Japanese drinking-etiquette contrast item — see Register note below |
| 지위(地位) | status, rank | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 윗사람 | a senior/superior person | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 따르다 | to pour (liquid) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 웃어른 | an elder, a senior person | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 받치다 | to support, prop up | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 어울리다 | to mix well, get along; to suit | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 음주(飮酒) | drinking alcohol | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 자주 | often | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 인기(人氣) | popularity | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 게시판(揭示板) | bulletin board | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 채우다 | to fill (something) up | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 공장(工場) | factory | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 송별회(送別會) | farewell party | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 예의(禮儀) | etiquette, manners | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |

### Grammar points

**기다렸다는 듯이 ("as if (one) had been waiting for it").** Fixed idiomatic expression describing
an unnaturally prompt reaction: 전화가 오자 기다렸다는 듯이 밖으로 뛰어나갔다 "the moment the call
came, she dashed outside as if she'd been waiting for it."

**주거니 받거니 하다 ("to go back and forth exchanging [drinks/words]").** A reciprocal-exchange
idiom built on 주다 "give" and 받다 "receive" in alternating -거니 form: 술잔을 주거니 받거니 하다
보니 어느새 12시다 "we went back and forth filling each other's glasses, and before we knew it, it
was midnight."

**-(으)ㄴ 채(로) ("while remaining in [an unusual/unexpected] state").** Attaches to a past-tense
modifier form to describe an action performed while still in some incongruous prior state: 옷을 입은
채로 잤다 "I fell asleep with my clothes still on."

**-노라면 ("if one keeps on [doing])").** A literary conditional for habitual/ongoing action leading
to a result: 한국에 사노라면 한국말도 잘하게 되겠지 "if you keep living in Korea, you'll surely get
good at Korean too."

### Register/sociocultural findings (this lesson's main value)

Explicit, source-stated **Korean-vs-Japanese drinking-etiquette contrast**: 한국에서는 일본에서와
달리 첨잔을 안 해요 ("unlike in Japan, Koreans don't top off a glass that isn't empty yet") — a
real cross-cultural etiquette rule, not merely vocabulary. Also explicit pouring-order etiquette:
술을 따를 때는 지위가 높거나 나이가 많은 윗사람부터 차례로 따르고요 ("when pouring, pour in order
starting with whoever outranks others in status or age") — ties directly into this project's
established Korean age/rank-hierarchy material. A third etiquette detail: when drinking with an
elder, a younger person turns their head to the side while holding the cup with both hands — this
is narrated as an observed custom (XV에서 보니까, "I saw it on TV") rather than tagged with a formal
register label, but is exactly the kind of explicit sociocultural annotation the coverage rule
flags as high-value. The lesson's closing exercise on "drinking-culture survey results" (frequency,
companions, and *reasons* people drink — including "to maintain good interpersonal relationships")
reinforces 회식/술자리's institutional-bonding function already noted narratively in the dialogue.

---

## Lesson 21: 어느 쪽이든 일장일단이 있을 거야 ("Either Way, There Are Pros and Cons")

PDF pp. 192–202. Topic: two friends (지영, 은주) discuss a teenage sibling's sudden interest in a
school "popularity vote," branching into a broader discussion of what makes a person attractive —
perfection vs. approachable imperfection.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 일장일단(一長一短) | "one strength, one weakness" — pros and cons | noun/idiom | core | — | — | — | — | grammar_reference | n/a | n/a | Sino-Korean four-character idiom |
| 투표(投票) | voting | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 신경(神經)(을) 쓰다 | to pay close attention to, worry about | verb phrase | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 멋내다 | to dress up, make oneself stylish | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 뒷전 | the back burner, low priority | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 심리학자(心理學者) | psychologist | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 능력(能力) | ability, capability | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 뛰어나다 | to excel, be outstanding | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 하긴 | well, actually — true | adverb/interjection | core | — | — | — | — | grammar_reference | n/a | n/a | discourse marker conceding a point |
| 완벽(完璧)하다 | to be perfect, flawless | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 믿음직하다 | to look trustworthy, reliable | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | part of a derivational family — see grammar point below |
| 매력적(魅力的) | attractive, charming | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 망치다 | to ruin, mess up | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 불안감(不安感) | a feeling of unease/anxiety | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 숨(이) 막히다 | to feel suffocated/stifled | verb phrase | core | — | — | — | — | grammar_reference | n/a | n/a | idiom: lit. "breath is blocked" |
| 외모(外貌) | (outward) appearance | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 살(이) 찌다 | to gain weight | verb phrase | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 먹음직하다 | to look appetizing, delicious | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | part of same derivational family as 믿음직하다/바람직하다 |
| 바람직하다 | to be desirable | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 변화(變化) | change | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 이상형(理想型) | one's ideal type (of romantic partner) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 성실(誠實)하다 | to be sincere, diligent | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 옷차림 | one's attire, how one is dressed | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 공무원(公務員) | civil servant | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 특성(特性) | characteristic, trait | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 장점(長點) | strong point, merit | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 단점(短點) | weak point, flaw | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |

### Grammar points

**N에 신경(을) 쓰다 ("to be concerned about/pay attention to N").** 을 is optionally droppable: 성적에
너무 신경 쓰지 마 "don't worry too much about your grades."

**N도 마 / V-지도 마 ("don't even [N/V]").** An emphatic prohibition stronger than plain 마 (don't):
여행 가는 건 생각도 마! "don't even think about going on a trip!"; 그 사람 이야기라면 꺼내지도 마
"don't even bring up that person."

**-기가 무섭게 ("the moment [X happens]; as soon as").** Near-synonym of -자마자, emphasizing
immediacy: 방학이 되기가 무섭게 고향으로 돌아갔다 "the moment vacation started, he went straight
home."

**-아/어 대다 ("to do [X] intensely/repeatedly").** An intensifying auxiliary verb suffix, often
carrying a critical/exasperated nuance: 매일 술만 마셔 대더니 병원에 입원했대 "he kept drinking
nonstop every day, and apparently ended up hospitalized."

**-는 바람에 ("because of, due to [an unexpected cause] — with negative consequence").**
갑자기 여행을 떠나는 바람에 연락을 못 받았어요 "because he suddenly left on a trip, I couldn't reach
him."

**N은/는 뒷전이다 / N을/를 뒷전으로 하다 ("to put N on the back burner / treat N as low priority").**
일은 뒷전이고 매일 모여서 놀 생각만 한다 "work takes a back seat — all they think about is getting
together to play every day."

**당연히 A/V ("naturally, of course A/V") / -(으)ᄂ/는 것은 당연하다 ("it is only natural that...").**
A free adverb form and a bound nominalized-clause form expressing the same logical-necessity
judgment: 돈을 그렇게 써 댔으니까 돈이 모자라는 건 당연하죠 "having spent money so recklessly, of
course money is short."

**믿음직[먹음직, 바람직]하다 (a shared derivational pattern: "looks V-worthy/-able").** All three
adjectives share the bound element -음직/-암직하다 attached to a verb stem, meaning roughly "gives
the impression that one should/would want to V": 믿다→믿음직하다 "look trustworthy" (should trust),
먹다→먹음직하다 "look appetizing" (want to eat), 바라다→바람직하다 "be desirable" (worth hoping
for). Flagged as a genuinely productive morphological pattern worth tracking across Korean
adjective formation, distinct from any single sibling-file's prior treatment of these three
individually.

---

## Lesson 22: 하고 있는 일이 적성에 안 맞아? ("Doesn't the Work You're Doing Suit You?")

PDF pp. 203–214. Topic: an essay on what makes work meaningful, followed by a dialogue about a
friend (영미) quitting her job over poor fit (적성) rather than pay.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 적성(適性) | aptitude, suitability | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 삶 | life, living | noun | core | — | — | — | — | grammar_reference | n/a | n/a | nominalization of 살다 |
| 명예(名譽) | honor, reputation | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 근무(勤務) | work, duty, service | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 그만하다 | to be about that much, that level | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | idiom: "good enough as-is" |
| 아주 | completely; (with certain verbs) for good | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | see grammar point for the "for good" sense |
| 마지못해 | reluctantly, unwillingly | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 가뭄 | drought | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 식물(植物) | plant | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 말라 죽다 | to wither and die | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 아예 | from the outset, outright | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 그저 | just, simply, merely | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 정성(精誠) | sincerity, devoted care | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 보험(保險) | insurance | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 분위기(雰圍氣) | atmosphere, mood | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 어쨌든 | anyway, in any case | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 규모(規模) | scale, size (of an organization) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 대기업(大企業) | large corporation | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 중소기업(中小企業) | small/medium-sized business | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 여가(餘暇) | leisure time | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 보조(補助) | assistance, subsidy | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 어학연수(語學硏修) | language study-abroad program | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 승진(昇進) | promotion | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 보장(保障) | guarantee | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 기혼(旣婚) | married (status) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 취업난(就業難) | difficulty finding employment | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 무직(無職) | unemployed, jobless | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |

### Grammar points

**N(으)로 인(因)해(서) ("because of, due to N").** 서 is droppable: 그 전쟁으로 인해서 많은 사람들이
목숨을 잃었습니다 "many people lost their lives because of that war."

**-아/어 봤자 ("even if one [does X], it's futile / not worth much").** Attaches to a verb/adjective
stem expressing that the action's result won't matter: 비싸 봤자 얼마나 비싸다고 그래? "even if it's
expensive, how expensive could it really be?"

**아주 V ("[to do V] for good, permanently").** With a narrow set of verbs (가다 "go," 돌아오다
"return," 헤어지다 "break up"), 아주 marks a one-way, final version of the action rather than its
ordinary "very/completely" sense: 이번에 일본에 가신다고요? 아주 가세요? "I hear you're going to
Japan — are you going for good (not coming back)?"

**N에 못지않게 ("no less than N, not inferior to N").** 에 is droppable: 동생이 형에 못지않게 운동을
잘해요 "the younger brother is no less athletic than the older one."

**마지못해 V ("to do V reluctantly, against one's will").** 먹고 싶지 않은데 마지못해 먹는 것
같았습니다 "it looked like he didn't want to eat but was forcing himself to."

**N(이)로구나 (exclamatory copula: "oh, it's N!").** A realization/exclamation ending: 참, 오늘이
공휴일이로구나! "oh right, today's a public holiday!"

**N에 불과(不過)하다 ("to be nothing more than N, merely N").** 그것은 간단한 일에 불과합니다 "that's
nothing more than a simple matter."

---

## Lesson 23: 인터넷은 정말 편리하구나 ("The Internet Is Really Convenient")

PDF pp. 215–225. Topic: a timestamped "day in Jiyeon's internet life" vignette (e-learning,
e-commerce, online banking, virtual cinema), followed by a mother-daughter dialogue about buying
furniture online — a dedicated technology/digital-life vocabulary lesson.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 인터넷 | the Internet | noun | core | — | — | — | — | grammar_reference | n/a | n/a | loanword |
| 접속(接續)하다 | to connect, log on | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 자료(資料) | data, material | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 검색(檢索) | search (n.) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 전송(電送) | transmission | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 전자 우편(電子郵便) | email | noun | core | — | — | — | — | grammar_reference | n/a | n/a | lit. "electronic mail" — formal register vs. 이메일 |
| 보고서(報告書) | (written) report | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 가상(假想) | virtual, imaginary | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 동경(東京) | Tokyo | proper noun | core | — | — | — | — | grammar_reference | n/a | n/a | Sino-Korean reading of the Japanese place name |
| 홈 쇼핑 | home shopping (TV/online) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | loanword compound |
| 홈뱅킹 | home/internet banking | noun | core | — | — | — | — | grammar_reference | n/a | n/a | loanword compound |
| 지출(支出) | expenditure | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 내역(內譯) | itemized details, breakdown | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 붓글씨 | brush calligraphy | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 디자인 | design | noun | core | — | — | — | — | grammar_reference | n/a | n/a | loanword |
| 그래픽 | graphic(s) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | loanword |
| 설계(設計) | design, planning | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 정보(情報) | information | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 안절부절못하다 | to be restless/fidgety with anxiety | verb | core | — | — | — | — | grammar_reference | n/a | n/a | fixed lexicalized idiom-verb |
| 의존(依存)하다 | to depend on, rely on | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 농사(農事) | farming | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 파티 | party | noun | core | — | — | — | — | grammar_reference | n/a | n/a | loanword |
| 지식(知識) | knowledge | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 통신(通信) | communication(s) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 상식(常識) | common sense | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 시청자(視聽者) | (TV) viewer | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 박(泊) | counter for nights (of a stay) | counter | core | — | — | — | — | grammar_reference | n/a | n/a | e.g. 2박 3일 "3 days/2 nights" |

### Grammar points

**A/V-(으)ᄅ지 A/V-(으)ᄅ지 모르다 ("not know whether X or Y").** 백화점이 좋을지 가구점이 좋을지
모르겠구나 "I don't know whether the department store or the furniture shop would be better."

**N을/를 N-는 데 이용하다 / N을/를 N에 이용하다 ("to use N for [purpose]").** Two near-synonymous
frames: 컴퓨터를 자료 정리하는 데 이용하니까 편리하다 "it's convenient to use the computer for
organizing data" vs. 비디오를 외국어 공부에 이용하다 "to use video for foreign-language study."

**N을/를 통해(서) ("through, via N").** 책을 통해서 우리는 많은 지식을 얻게 됩니다 "through books we
gain a lot of knowledge."

**한 N(이)라도 V-(으)면 (안 되다) ("not even one N may [V]").** An emphatic universal-prohibition
frame: 내가 준 책을 한 권이라도 잃어버리면 안 돼 "you may not lose even a single one of the books I
gave you."

**안절부절못하다 (lexical note).** Flagged as a single fixed idiom-verb (not a productive
construction) meaning "to be anxiously restless/at a loss" — 정보의 홍수 속에서 안절부절못하는
사람도 있다 "some people are anxious/overwhelmed amid the flood of information," used here
specifically of information-overload anxiety.

---

## Lesson 24: 아리랑 아리랑 아라리요

PDF pp. 226–236. Topic: an extended cultural-essay-plus-dialogue lesson on the folk song *Arirang*
— its origins, function, and regional variants. The lesson opens with the song's own lyrics quoted
in full (4 lines — short enough to reproduce as the lesson's own stated subject, not
bulk-reproduced source prose).

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 끼우다 | to insert, interpose | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 민요(民謠) | folk song | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 가리키다 | to indicate, refer to | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 널리 | widely, broadly | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 민중(民衆) | the common people, populace | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 일상적(日常的) | everyday, routine | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 논 | (wet) rice paddy | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 밭 | (dry) field | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 혹(或)은 | or, or else | conjunction | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 강(江) | river | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 온갖 | all sorts of, every kind of | determiner | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 어려움 | hardship, difficulty | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 절망(絶望) | despair | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 이렇듯 | thus, like this | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 이르다 | to reach, arrive at | verb | core | — | — | — | — | grammar_reference | n/a | n/a | see grammar point |
| 국외(國外) | abroad, overseas | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 단순(單純)하다 | to be simple | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 가사(歌詞) | (song) lyrics | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 여럿 | several (people) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 부분(部分) | part, portion | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 흔히 | commonly, often | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 무리 | group, crowd | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 나뉘다 | to be divided | verb | core | — | — | — | — | grammar_reference | n/a | n/a | passive of 나누다 |
| 한(恨) | a deep, abiding sorrow/resentment | noun | core | — | — | — | — | grammar_reference | n/a | n/a | culturally loaded Korean concept, explicitly discussed in-lesson — see note below |
| 집단(集團) | group, collective | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 흥(興) | excitement, high spirits | noun | core | — | — | — | — | grammar_reference | n/a | n/a | the explicit counterpart to 한 in this lesson's discussion — see note below |
| 돋우다 | to heighten, raise (a feeling) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 가락 | melody, tune | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 학설(學說) | (academic) theory | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 책임(責任) | responsibility | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 타자기(打字機) | typewriter | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 체험(體驗) | (personal/firsthand) experience | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 국화(國花) | national flower | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 여왕(女王) | queen | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 국물 | broth, soup | noun | core | — | — | — | — | grammar_reference | n/a | n/a | appears only in a grammar-example sentence, not the main vocab box |

### Grammar points

**N(으)로(서) ("as, in the capacity of N").** 나는 한국에 학생으로 왔어요 "I came to Korea as a
student." The related frame **N은/는 N(으)로(서)** marks the same role but as the sentence topic:
추석은 한국인의 가장 큰 명절로서... "Chuseok, as Koreans' biggest holiday, ...".

**N에 이르다 / V-기에 이르다 ("to reach N / to reach the point of V-ing").** 자동차가 매년 늘어나서
100만 대에 이르고 있다 "the number of cars has grown yearly, reaching a million"; 나라가 망하기에
이르자 "once it reached the point that the country was ruined..."

**N(이/에서)든지 N(이/에서)든지 / A/V-든지 A/V-든지 ("whether N or N / whether A or V").** 불고기든지
비빔밥이든지 다 맛있어요 "whether it's bulgogi or bibimbap, both are delicious"; 가든지 말든지 그냥
둡시다 "whether he goes or not, let's just leave him be."

**N이/가 N(으)로 나뉘다 ("N is divided into N").** 지구가 육지와 바다로 나뉘었어요 "the Earth is
divided into land and sea."

**N에 바탕을 두다 ("to be based on N").** 이 영화는 유명한 역사 소설에 바탕을 두고 만들어졌다 "this
film was made based on a famous historical novel."

**N(이)라고 불리다 ("to be called N").** 서울은 옛날에 한성이라고 불렸다 "Seoul used to be called
Hanseong."

### Sociocultural/register findings (this lesson's main value)

This lesson is a dedicated folkloristics essay, not merely a language lesson — directly relevant to
this project's interest in named cultural concepts and regional variation:

- **한(恨) vs. 흥(興)** are presented as an explicit emotional-structural pair underlying Arirang's
  performance style: 개인적으로는 '한'을 풀고 집단적으로는 '흥'을 돋우는 노래 방식 ("a singing style
  that individually releases *han* and collectively raises *heung*"). Both terms are single-
  syllable, culturally loaded Korean concepts without a clean English equivalent (한 ≈ a deep,
  long-held sorrow/resentment; 흥 ≈ communal exuberance/excitement) — worth flagging for this
  project's own mechanics-analysis phase as recurring Korean cultural-affect vocabulary.
- **Explicit regional-variant taxonomy for Arirang itself**: the commonly-sung version is named
  "경기 아리랑" (Gyeonggi Arirang), explicitly described as a modernized, popularized
  (대중가요화된) version of the original folk song; the traditional folk form is explicitly
  subdivided into three named regional traditions — **정선 아리랑** (Jeongseon Arirang), **진도
  아리랑** (Jindo Arirang), and **밀양 아리랑** (Miryang Arirang). This is the clearest explicit
  regional/dialectal-adjacent annotation found anywhere in this volume — not a linguistic dialect
  tag on a word, but a named, geographically-anchored song-tradition taxonomy stated directly in
  the source's own text, which the coverage rule flags as must-not-skip content.
- The lesson states a concrete regional density figure: 정선 지역에서만 400–500개에 이르는 아리랑
  가사가 존재한다 ("in the Jeongseon region alone, 400–500 distinct sets of Arirang lyrics exist").
- 아리랑/아라리 themselves are explicitly flagged as **semantically empty syllables** — the
  dominant scholarly theory (학설) holds they carry no fixed meaning and exist purely to carry the
  song's rhythm (가락이 이어져 나가도록 돕는다), not a word with a literal translation.

---

## Lesson 25: 흥부와 놀부 ("Heungbu and Nolbu")

PDF pp. 237–248. A full scripted stage-play retelling of the classic Korean folktale of two
brothers — kind, impoverished Heungbu and greedy, wealthy Nolbu — and the swallow whose broken leg,
once mended, repays each brother very differently. This is this volume's capstone cultural-
narrative lesson (the counterpart to Vol. 3's 춘향 (Ch'unhyang) folktale treatment). Dialogue
throughout is informal/plain-style, consistent with a children's-theater script register.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 제비 | swallow (bird) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 새끼 | the young/offspring of an animal | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 박 | gourd | noun | core | — | — | — | — | grammar_reference | n/a | n/a | central plot object of the tale |
| 씨 | seed | noun | core | — | — | — | — | grammar_reference | n/a | n/a | homograph of the honorific title suffix -씨 |
| 도깨비 | goblin | noun | core | — | — | — | — | grammar_reference | n/a | n/a | folkloric figure |
| 해설자(解說者) | narrator | noun | core | — | — | — | — | grammar_reference | n/a | n/a | stage-play role name |
| 식구(食口) | family member | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 내쫓다 | to kick out, expel | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 자루 | sack | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 내밀다 | to stick out, poke out | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 큰아버지 | father's older brother (uncle) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | kinship term |
| 지붕 | roof | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 쌍(雙) | pair (counter) | counter | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 강남(江南) | "south of the river" — the warm south the swallows migrate to | noun | core | — | — | — | — | grammar_reference | n/a | n/a | in this folktale context, not the Seoul district |
| 뱀 | snake | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 피(避)하다 | to avoid, evade | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 바퀴 | a turn, revolution (counter) | counter | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 넘어지다 | to fall over | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 부러지다 | to be broken (of a limb) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | intransitive counterpart of 부러뜨리다 |
| 바르다(약을) | to apply (medicine) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 헝겊 | cloth, rag | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 갚다 | to repay | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 은혜(恩惠) | a favor, grace, kindness | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 심다 | to plant | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 벌어지다 | to happen, occur (of an event) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 싹 | sprout | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 열리다(과일이) | to bear fruit | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 조르다 | to pester, nag | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 만지다 | to touch | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 슬근슬근 | (sound/motion of) sawing gently back and forth | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | onomatopoeia |
| 톱 | saw (tool) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| -질 | suffix: repeated/habitual-action nominal-verb former | suffix | core | — | — | — | — | grammar_reference | n/a | n/a | see grammar point |
| 펑 | (sound of) a loud pop/burst | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | onomatopoeia, marks the gourds bursting open |
| 보물(寶物) | treasure | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 금방(今方) | right away, just now | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 욕심(慾心) | greed | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 이러이러하다 | to be "such and such" | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | placeholder-narration verb, paired with 저러저러하다 |
| 저러저러하다 | to be "so and so" | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 부러뜨리다 | to break (something), snap | verb | core | — | — | — | — | grammar_reference | n/a | n/a | transitive counterpart of 부러지다 |
| 강제(強制)로 | by force, forcibly | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 절뚝이다 | to limp | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 두고 보다 | "wait and see" | idiom | core | — | — | — | — | grammar_reference | n/a | n/a | see grammar point |
| 정신(精神)(을) 차리다 | to come to one's senses, pull oneself together | verb phrase | core | — | — | — | — | grammar_reference | n/a | n/a | see grammar point |
| 몽둥이 | club, cudgel | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 때리다 | to hit, strike | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 퇴장(退場)하다 | to exit (the stage) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | stage-direction term |
| 인형(人形) | doll | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 물고기 | fish | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 가치관(價値觀) | values, outlook on life | noun | core | — | — | — | — | grammar_reference | n/a | n/a | used in the lesson's own post-reading discussion prompt (comparing Heungbu's and Nolbu's 가치관) |

### Grammar points

**그러던 어느 날 ("and then, one day...").** A fixed narrative-transition idiom marking a sudden
turning point in a story: 할아버지는 날마다 나무로 인형을 만들었다. 그러던 어느 날 '피노키오'라는
작은 남자 아이를 만들게 되었다 "Grandfather carved dolls from wood every day. Then, one day, he came
to carve a little boy named 'Pinocchio.'"

**-질 (suffix forming a noun/verb for a repeated manual action).** Attaches to a noun naming a tool
or activity to name the repeated action of using it: 톱 "saw" → 톱질(하다) "sawing"; also productive
outside this lesson's own examples — 도둑질 "thieving," 다리미질 "ironing," 낚시질 "fishing." Flagged
as a genuinely productive derivational pattern, distinct from the -질 instance already noted in
Lesson 20's end vocabulary.

**두고 보다 ("wait and see; just you watch").** An idiom used here as a villain's threat after being
wronged: 두고 보자. 다음에는 꼭 내가 이길 테니까 "just wait — next time I'll definitely win."

**정신(을) (못) 차리다 / 정신(이) 없다 (a related idiom family around 정신 "spirit/mind").**
정신(을) 차리다 = "to come to one's senses, pull oneself together" (used of Nolbu's moral
reckoning); 정신(을) 못 차리다 = "to be too dazed/infatuated to think straight"; 정신(이) 없다 = "to
be too busy/overwhelmed to think straight" (a distinct sense from the 못 차리다 form). All three
share the same noun 정신 but diverge in exactly which particle/negation combination is used —
worth tracking together as one lexical family rather than as unrelated idioms.

### Sociocultural findings

This lesson's entire content *is* a sociocultural artifact: the Heungbu/Nolbu tale is one of
Korea's best-known traditional moral folktales, structured as an explicit charity-vs-greed moral
contrast (the lesson's own closing discussion exercise asks students to characterize each
brother's 가치관/성격/생활 태도, i.e. "values, personality, and attitude toward life" — making the
didactic framing explicit rather than merely implicit in the narrative). No dialectal/regional
annotation was found in this lesson (plain narrative/dialogue register throughout, consistent with
a children's-theater script).

---

## Lesson 26: 희생을 무릅쓰고 지도를 완성했어요 ("[He] completed the map at the risk of his life")

PDF pp. 249–258. Reading/dialogue centers on Kim Jeong-ho (김정호), the 19th-century Korean
cartographer who produced the *Daedongyeojido* (대동여지도); the lesson's comprehension questions
ask when the map was made, how long it took, and how it's evaluated today — a biographical/
historical-figure set-piece rather than a conversational dialogue. (Lesson title's first word reads
"회생" in raw OCR but is almost certainly "희생" [sacrifice] — a ㅎ↔ㅈ-adjacent jamo misread recurs
elsewhere in this OCR batch too; the vocabulary box's own first entry is unambiguously 희생(犧牲).)

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 희생(犧牲) | sacrifice | noun | core | — | — | — | — | grammar_reference | n/a | n/a | lit. "giving one's own thing for someone/something else's sake" per source's own Korean-language gloss |
| -을/를 무릅쓰고 | despite, risking (danger/difficulty) | grammatical pattern (postpositional) | core | — | — | — | — | grammar_reference | n/a | n/a | source glosses as 에도 불구하고 "in spite of" |
| 지도(地圖) | map | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 정밀(精密)하다 | precise, exact | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 걸작품(傑作品) | masterpiece | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 평가(評價)하다 | to evaluate | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 동기(動機) | motive, reason | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 너머 | beyond, over (a barrier) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | "the far side of something blocked by height or a boundary" |
| 궁금증(症) | curiosity, itch to know | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 이어지다 | to continue, be connected | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 일생(一生) | one's whole life | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 바치다 | to devote, offer up | verb | core | — | — | — | — | grammar_reference | n/a | n/a | source glosses with 희생하다/드리다 |
| 걸치다 | to take, span (a length of time) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | distinct sense from the common "to wear/drape" meaning |
| 결심(決心) | determination, resolve | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 오죽하다 | to be no ordinary degree, be really something | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | almost always used in the rhetorical-exclamation pattern below |
| 끝내 | finally, in the end | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 보육원(保育院) | orphanage, children's home | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 결(決)코 | never, absolutely (not) | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 과학자(科學者) | scientist | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 한잠 | a nap, a wink of sleep | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 증거(證據) | evidence | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 추위 | the cold | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 자연(自然) | nature | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 에이즈 | AIDS | noun | technical.medical | — | — | — | — | grammar_reference | n/a | n/a | loanword |
| 새해 | New Year | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 존경(尊敬)하다 | to respect | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |

### Grammar points

**V-는 데(에) 일생을 바치다 — "to devote one's (whole) life to V-ing."** Attaches to a nominalized
verb clause (-는 데(에)) plus 일생을 바치다. Example: 암을 치료하는 약을 개발하는 데에 일생을 바친
분 "a person who devoted their life to developing medicine to treat cancer."

**-이/가 다 뭐예요? — dismissive "don't even mention/what do you mean, X?"** A rhetorical-question
idiom that dismisses or downplays the noun it attaches to, implying the opposite of what a literal
reading would suggest. Example: 생일에 좋은 선물 받았어요? — 선물이 다 뭐예요? 생일인 줄도 모르던데요.
"Did you get a nice birthday present? — What present? He didn't even know it was my birthday." Has
a modifier-clause variant, -(으)ㄴ/는 게 다 뭐예요?, for dismissing a whole description rather than
a bare noun: 친한 게 다 뭐예요? 싸워서 한 달째 서로 말을 안 하고 있는데. "Close? We had a fight and
haven't spoken in a month."

**V-겠다는 결심을 하다 — "to resolve/make up one's mind to V."** Nominalizes a future-intention
clause (-겠다는) as the object of 결심을 하다. Example: 수영을 배워야겠다는 결심을 하게 되었습니다
"I resolved that I had to learn to swim."

**-이/가 오죽하겠어(요)? — rhetorical "how [extremely adjective] must X be!"** An exclamatory
rhetorical question implying an extreme degree without stating it outright. Example: 청소를 한
달이나 안 했으니 집이 오죽하겠어? "We haven't cleaned in a month — just imagine how [messy] the
house must be!" Past-tense form -었겠어요 used for a past extreme ("그 가족들의 기쁨이 오죽했겠어요?"
"imagine how overjoyed that family must have been").

**-을/를 무릅쓰고 — "despite, braving (danger/hardship)."** The lesson's titular pattern; attaches
to a noun denoting a risk, danger, or difficulty, framing the main clause's action as happening in
spite of/in defiance of it. Functions similarly to -에도 불구하고 per the source's own gloss, but
specifically connotes bravery/sacrifice rather than mere contrast.

---

## Lesson 27: 말이야말로 그 사람의 인격을 말해 줍니다 ("The way someone talks truly tells you their character")

PDF pp. 259–265. Dialogue: Jiyeon is unsettled after overhearing students cursing crudely on the
bus; Minsu argues coarse language mostly surfaces among close friends and that language itself
reveals character, while slang/trendy words aren't purely bad since they also energize everyday
language. **Sociocultural/register finding:** the dialogue cites a real (in-universe) survey claim
that "no less than 70%" of one middle school's entire student body uses vulgar language, and frames
slang/coarse speech acquisition as coming from peers, parents/adults, and mass media — genuinely
on-topic for this project's slang-mechanics purpose. The lesson closes with a cluster of
**proverbs about speech** worth flagging (paraphrased, not reproduced at length): 발 없는 말이 천
리 간다 ("words with no feet travel a thousand *li*" — words spread fast/far), 가는 말이 고와야
오는 말이 곱다 ("if the words you send are kind, the words you get back are kind"), 말 한마디에
천 냥 빚도 갚는다 ("a single word can repay a debt of a thousand *nyang*" — the right words have
outsized power), and 말이 씨가 된다 ("words become seeds" — words can turn into reality, i.e. a
self-fulfilling-prophecy caution). Also the idiom 개구리 올챙이 적 생각 못한다 ("the frog doesn't
remember its tadpole days" — forgetting one's own humble beginnings), discussed via a comprehension
exercise about a woman who forgot her own early driving struggles.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| -(이)야말로 | truly, indeed (of all things) | grammatical pattern (emphatic particle) | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 인격(人格) | personality, character | noun | core | — | — | — | — | grammar_reference | n/a | n/a | "a person's basic character/dignity" per source |
| 욕(辱) | abusive language, cursing | noun | colloquial | — | — | — | — | grammar_reference | n/a | n/a | glossed as "저속한 말, 욕설" — directly slang-adjacent vocabulary |
| 청소년(靑少年) | adolescent, youth | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 거칠다 | rough, coarse (of speech) | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | glossed via 저속하다 "vulgar" |
| 저속(低俗)하다 | vulgar, low-class | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 친숙(親熟)하다 | familiar, close (relationship) | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 무려(無慮) | no less than, as many/much as | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 비롯하다 | to include, start with | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 대중 매체(大衆媒體) | mass media | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 한동안 | for a while | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 유행어(流行語) | trendy/slang expression | noun | core | — | — | — | — | grammar_reference | n/a | n/a | the term the dialogue itself uses for "slang/buzzword" |
| 무작정(無酌定) | recklessly, without any plan | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 따르다 | to follow | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| -아/어 버릇하다 | to make a habit of V-ing | grammatical pattern (auxiliary) | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 활기(活氣) | vitality, energy | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 대표(代表)하다 | to represent | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 관광지(觀光地) | tourist attraction | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 신사(紳士) | gentleman | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 사치(奢侈)스럽다 | luxurious, extravagant | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 신용 카드(信用카드) | credit card | noun | core | — | — | — | — | grammar_reference | n/a | n/a | loanword "카드" |
| 초보(初步) | beginner, novice | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 양보(讓步)하다 | to yield, give way | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 올챙이 | tadpole | noun | core | — | — | — | — | grammar_reference | n/a | n/a | key word in the "forgets its tadpole days" idiom above |
| 적 | the time (when...) | bound noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 냥(兩) | *nyang* (old Korean currency unit) | noun | archaic | — | — | — | — | grammar_reference | n/a | n/a | survives only in the fixed proverb cited above |
| 빚 | debt | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |

### Grammar points

**-(이)야말로 — "truly, indeed (emphatic 'of all things')."** Emphatic topic/focus particle
stressing that the marked noun is the genuine, quintessential instance of whatever is predicated.
Example: 제주도야말로 한국을 대표하는 관광지입니다 "Jeju Island really is THE tourist attraction
that represents Korea."

**Noun + 스럽다 — "to have the quality/nature of N" (noun→adjective derivation).** A productive
derivational suffix converting a noun into a descriptive adjective expressing that something
exhibits that noun's quality. Examples: 사치스럽다 "extravagant" (사치 "luxury"), 자랑스럽다 "to be
proud of" (자랑 "boasting"), 부담스럽다 "to feel burdened by" (부담 "burden").

**무려 — "as many/much as, no less than" (adverb of surprising quantity).** Precedes a number to
emphasize it is surprisingly large. Example: 그 사고로 무려 10명이나 사망했대요 "The accident
reportedly killed as many as 10 people."

**-을/를 비롯하다/비롯해서 — "starting with X, including X."** Marks a noun as the first/
representative member of a larger set being discussed. Example: 한국을 비롯한 10개국 대표들
"representatives of 10 countries, [starting] with/including Korea."

**무작정 + V — "recklessly, without any plan."** Adverb modifying a verb to indicate the action was
taken with no forethought. Example: 답답한 도시 생활이 싫어서 무작정 떠나왔어요 "I was sick of the
stifling city life, so I just up and left with no plan."

**V-아/어 버릇하다 — "to make a habit of V-ing, get used to V-ing (through repetition)."**
Auxiliary construction marking a habituation that forms through repeated action. Example: 약도
먹어 버릇하면 습관이 될 거예요 "If you get into the habit of taking medicine [casually], it'll
become a habit."

---

## Lesson 28: 찬성하는 쪽이에요? 반대하는 쪽이에요? ("Are you for it, or against it?")

PDF pp. 266–273. Dialogue is a debate about a controversial, sexually explicit film the government
initially banned from release, with Minsu and Jiyeon disagreeing over whether government censorship
of art/performance is ever justified; the dialogue explicitly namechecks *Lady Chatterley's Lover*
and a work called *Maya* as historical examples of art once dismissed as "low-quality" in their own
era. **Sociocultural set-piece (this lesson's main value):** a follow-on reading passage about a
real-feeling news story — two babies' nametags were accidentally swapped at a maternity hospital;
the families discovered the switch six years later; one child had a disability and the other grew
up healthy; public opinion leaned toward "the children should be swapped back" — framed as a debate
between 낳은 정 ("the emotional bond of having given birth to" a child) and 기른 정 ("the emotional
bond of having raised" a child), a real culturally-loaded Korean concept pair for parent-child
attachment distinct from genetic/biological framing. Discussion questions ask learners for their
own country's proverbs about "family bonds" and whether they'd disclose such a swap to the child.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 찬성(贊成)하다 | to approve, be in favor | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 야(冶)하다 | racy, sexually suggestive | adjective | colloquial | — | — | — | — | grammar_reference | n/a | n/a | glossed directly 色情 "erotic/sexual" |
| 야단(惹端)이다 | to be in an uproar, make a fuss | verb/predicate idiom | colloquial | — | — | — | — | grammar_reference | n/a | n/a | |
| 엄청나다 | to be enormous, tremendous | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 상영(上映)하다 | to screen (a film) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 일리(一理)가 있다 | to have a point, make some sense | idiom | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 금지(禁止)하다 | to prohibit | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 간섭(干涉)하다 | to interfere, meddle | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 저질(低質) | low-quality, trashy | noun/adjective | colloquial | — | — | — | — | grammar_reference | n/a | n/a | glossed 劣质的/低劣的, applied to art/media the speaker disdains |
| 취급(取扱)하다 | to treat/handle (as); to deal in (goods) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | two distinct senses — see grammar points below |
| 상업적(商業的) | commercial | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 토론(討論)하다 | to debate, discuss | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 주장(主張) | assertion, argument | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 입장(立場) | position, stance | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 싸구려 | cheap junk, shoddy goods | noun | colloquial | — | — | — | — | grammar_reference | n/a | n/a | |
| 애완동물(愛玩動物) | pet | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 장난감 | toy | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 대담(對談) | a dialogue, a (broadcast) conversation | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 범죄(犯罪) | crime | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 마약(麻藥) | drugs, narcotics | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 자살(自殺) | suicide | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 지나치다 | to be excessive | adjective/verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 출생(出生) | birth | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 주인공(主人公) | protagonist, main character | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 낳다 | to give birth to | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 산부인과(產婦人科) | obstetrics/gynecology department | noun | technical.medical | — | — | — | — | grammar_reference | n/a | n/a | |

### Grammar points

**-다고 야단(들)이다 — "everyone's up in arms saying that..."** Indirect-quotation -다고 plus
야단(들)이다, framing a reported claim as something a group is loudly fussing/complaining about.
Example: 환경 문제가 심각하다고 야단들이에요 "Everyone's making a fuss saying the environmental
problem is serious."

**-아/어서 야단이다[야단났다] — "it's a real problem because..."** A causal clause plus
야단이다/야단났다 marking the resulting situation as a genuine predicament. Example: 길이 막혀서
야단이에요 "The road's jammed, and that's a real problem [since I have to be there by 9]."

**-(ㄴ/는)다느니 -(ㄴ/는)다느니 (하면서) / -(으)니 -(으)니 (하면서) — "arguing over whether X or Y."**
Juxtaposes two (often contradictory) reported claims or options with -느니 and 하면서, describing
people going back and forth debating/arguing. The first form attaches to verb/processive-adjective
plain-style quotations (간다느니 만다느니 "whether to go or not go"); the second to descriptive
adjectives or state predicates (적으니 많으니 "whether it's too little or too much").

**-에(도) 일리가 있다 — "there's something to X too, X has a point."** Marks that the preceding
statement/position, even if one disagrees overall, contains genuine merit. Example: 네 주장에
일리가 있구나 "Your argument does have a point."

**V-는 수가 많다[있다] — "it often happens that V."** Marks a described event as a frequent
occurrence/outcome rather than a one-off. Example: 아이들 싸움이 어른들 싸움이 되는 수가 많이
있다 "It often happens that kids' fights turn into adults' fights."

**-을/를[이/가] ~(으)로 취급하다[취급받다] — "to treat/be treated as X."** Marks the way a person
or thing is regarded or categorized. Example: 애완동물을 장난감으로 취급하면 안 돼요 "You shouldn't
treat pets as toys." A distinct second sense of 취급하다 — "to deal in, handle (as a business)" —
appears without the (으)로 marker: 우리 가게에서는 술을 취급하지 않아요 "Our shop doesn't carry/
sell alcohol."

---

## Lesson 29: 인연이 있으면 언젠가 또 만나게 되겠지 ("If it's fate, we'll meet again someday")

PDF pp. 274–281. Intro essay + dialogue built entirely around **인연** (*inyeon*), the Korean/
Buddhist-inflected concept of a fated or karmic bond between people, including the fixed proverb
옷깃만 스쳐도 인연이다 ("even brushing sleeves [with a stranger] is inyeon") cited and explained as
expressing that even the smallest, most trivial contact between people deserves to be cherished.
Dialogue: Mari (a foreign student) and Youngmi recount how their friendship began by chance
(Youngmi gave Mari directions when she was lost; later Youngmi found and returned Mari's lost
wallet/passport) and reflect on parting now that they've lived together over a year.
**Sociocultural note:** this concept (*inyeon*) is presented as a named, culturally load-bearing
belief system for interpreting coincidental/repeated encounters, not just ordinary vocabulary.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 인연(因緣) | fated bond, karmic connection | noun | core | — | — | — | — | grammar_reference | n/a | n/a | culturally load-bearing concept, see coverage note above |
| 일상생활(日常生活) | everyday life | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 뜻밖에 | unexpectedly | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 옷깃 | collar (of a traditional Korean jacket) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | the key noun in the 옷깃만 스쳐도 인연 proverb |
| 스치다 | to brush past, lightly graze | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 사소(些少)하다 | trivial, minor | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 소중(所重)히 | preciously, dearly | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 소홀(疏忽)히 | negligently, carelessly | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 안타깝다 | to feel sorry/distressed (about) | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 헤매다 | to wander, roam lost | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 줍다 | to pick up (something dropped) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 자매(姊妹) | sisters | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 떼다 | to detach, pull apart | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 섭섭하다 | to feel sorry/wistful (at a parting or loss) | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 사표(辭表) | letter of resignation | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 불행(不幸) | misfortune | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 원수(怨讐) | enemy, foe | noun | core | — | — | — | — | grammar_reference | n/a | n/a | glossed as "a person who has wronged my family" |
| 실향민(失鄉民) | a person displaced from their hometown | noun | core | — | — | — | — | grammar_reference | n/a | n/a | historically tied to Korean-War-era North/South displacement; flagged as sociopolitically loaded vocabulary |
| 그리워하다 | to long for, miss | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 오빠 | older brother (female speaker's term) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | kinship-term vocabulary already well documented elsewhere in `established/`; included here only because this lesson's own box lists it |
| 껌 | chewing gum | noun | core | — | — | — | — | grammar_reference | n/a | n/a | source OCR renders this as "낌"; corrected via its own Chinese gloss 口香糖 "chewing gum" (ㄴ/ㄲ jamo-shape OCR confusion) |

### Grammar points

**인연이 있다[없다] / 인연이다[인연이 아니다] — "to have/not have [be/not be] a fated bond."**
Treats 인연 as a predicate noun describing whether a relationship/encounter is fated. Example:
인연이 있으면 또 만나게 될 거예요 "If it's fate, we'll meet again."

**-아/어서는 안 되다 — "must not be in the state of being..."** Prohibition construction attaching
to the -아/어서 connective form of an adjective/state verb, distinct from the more basic -(으)면
안 되다. Example: 선물은 받는 사람이 부담스러워서는 안 되지요 "A gift shouldn't be something that
makes the receiver feel burdened."

**-았/었더라면 — "if only ... had been the case" (counterfactual past conditional).** Marks a past
counterfactual condition, almost always paired with a regret or hypothetical-outcome main clause.
Example: 돈이 많았더라면 더 오래 여행할 수 있었을 텐데 "If only I'd had more money, I could have
traveled longer."

**-(으)ㄹ 줄 누가[어떻게] 알았겠어요? / -(으)ㄹ 줄이야 — "who could have known...!" / "to think
that...!"** Two related exclamatory constructions expressing surprise at an unforeseen outcome; the
first is explicitly rhetorical-question-shaped, the second a bare exclamation. Examples: 복권이
당첨될 줄 누가 알았겠어요? "Who could have known the lottery ticket would win?"; 서울의 물가가
이렇게 비쌀 줄이야 "To think Seoul's prices would be this high!"

**-(으)ㄹ래야 -(으)ㄹ 수(가) 없다 — "even wanting to V, [I] can't V."** Combines the desiderative/
intentive -(으)ㄹ래 with -(으)ㄹ 수 없다 to stress that an action is impossible no matter how much
one wants to do it. Example: 너무 매워서 먹을래야 먹을 수가 없었다 "It was so spicy that even
though I wanted to eat it, I couldn't."

---

## Lesson 30: 서울은 한국 제일의 도시이다 ("Seoul is Korea's foremost city")

PDF pp. 282–291. A factual/expository essay (not a dialogue-first lesson) on Seoul: population
(10M+), district structure (25 구, 14 north of the Han River/강북, 11 south/강남, linked by 19
bridges), subway system (8 lines and growing), palaces/museums, followed by a dialogue between
Tanaka and Youngsu about why Seoul residents want to leave despite the city's dominance (traffic,
pollution, housing costs) yet can't bring themselves to, tied to Korea's intense centralization of
politics/economy/culture/education and status-driven pressure to live in Seoul for children's
education. **Sociocultural/historical finding (this lesson's main value):** a listening-exercise
timeline tracing Seoul's status across historical moments — becoming capital ~600 years ago (조선
Dynasty), 1945/8/15 (Liberation), the 1950s (6·25/Korean War damage), the 1960s (economic
development), and 1974 (the subway's opening) — plus an explicit comprehension true/false item
comparing North and South Korean population ("북한의 인구는 남한 인구의 4분의 1이다" — "North
Korea's population is a quarter of South Korea's"), a rare instance of this series directly
quizzing North–South demographic/historical facts rather than just language.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 지하철(地下鐵) | subway | noun | core | — | — | — | — | grammar_reference | n/a | n/a | this box's OCR is unusually scrambled (a vocab sidebar interrupted mid-paragraph); term reconstructed from the surrounding 지하철/8호선 discussion, not read with full confidence |
| 중심지(中心地) | center, hub | noun | core | — | — | — | — | grammar_reference | n/a | n/a | reconstructed from context (서울이... 중심지가 된); OCR for this entry is garbled, moderate confidence only |
| 인구 밀도(人口密度) | population density | noun | core | — | — | — | — | grammar_reference | n/a | n/a | reconstructed from context (아시아에서 열 손가락 안에 드는 인구 밀도); OCR garbled, moderate confidence only |
| 손꼽히다 | to be counted among the top/best | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 대도시(大都市) | metropolis, large city | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 수도(首都) | capital city | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 손가락 | finger | noun | core | — | — | — | — | grammar_reference | n/a | n/a | key word in the "top five/ten fingers" idiom below |
| 수(數) | number, count | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 연결하다 | to connect | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 운행(運行)하다 | to operate, run (a transit line) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 궁궐(宮闕) | palace | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 한정(限定)하다 | to limit, restrict | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 여전(如前)히 | still, as before | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 고집(固執)하다 | to insist on, stubbornly stick to | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 자녀(子女) | children, offspring | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 하루빨리 | as soon as possible | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 가격(價格) | price | noun | core | — | — | — | — | grammar_reference | n/a | n/a | exercise-only vocabulary for this lesson, not in the main text |
| 품질(品質) | quality | noun | core | — | — | — | — | grammar_reference | n/a | n/a | exercise-only vocabulary |
| 차차(次次) | gradually | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | exercise-only vocabulary |
| 경력(經歷) | career, work experience | noun | core | — | — | — | — | grammar_reference | n/a | n/a | exercise-only vocabulary |
| 공해(公害) | (environmental) pollution | noun | core | — | — | — | — | grammar_reference | n/a | n/a | also appears in the listening-exercise true/false item above |
| 소음(騒音) | noise | noun | core | — | — | — | — | grammar_reference | n/a | n/a | exercise-only vocabulary |
| 위치(位置) | location, position | noun | core | — | — | — | — | grammar_reference | n/a | n/a | exercise-only vocabulary |
| 기후(氣候) | climate | noun | core | — | — | — | — | grammar_reference | n/a | n/a | exercise-only vocabulary |

### Grammar points

**-(으)로 보나 -(으)로 보나 — "whichever way you look at it, whether from X or Y."** Compares two
criteria to show a conclusion holds regardless of which one is used. Example: 가격으로 보나 품질로
보나 이게 제일 나아요 "Whether you judge by price or by quality, this one's best."

**-(으)로 손꼽히는 N — "N that's counted among the top/best as X."** Modifier construction marking
a noun as widely recognized in a top-tier category. Example: 그 영화배우는 한국에서 최고의 배우로
손꼽히는 사람입니다 "That actor is counted among Korea's very best."

**N임에 틀림없다 / -(으)ㄴ/는 게 틀림없다 — "there's no doubt that N / it's certain that..."**
Asserts strong certainty based on inference. Example: 서울은 역사가 오래된 도시임에 틀림없다 "Seoul
is undoubtedly a city with a long history." The second form attaches to a modifier clause rather
than a bare noun: 값이 너무 비싼 게 틀림없다 "It must be that the price is too high."

**N에서 다섯[열] 손가락 안에 들다 — "to rank in the top five/ten [out of N]."** Idiom literally "to
fall within the five/ten fingers [of counting]," used to express a strong top-tier ranking.
Example: 우리 학교는 세계에서 열 손가락 안에 드는 학교예요 "Our school ranks in the world's top
ten."

**-(으)ㅁ에 따라 — "in accordance with, as X [changes]."** Marks a clause as the changing condition
that the main clause's change tracks. Example: 서울이 발전함에 따라 크기도 커졌어요 "As Seoul
developed, it also grew in size." Also occurs as the near-synonymous bare-noun pattern N에 따라
("depending on N"): 지역에 따라 비가 오는 곳도 있습니다 "Depending on the region, some places get
rain."

**-(으)ㄹ 전망이다[전망이 있다, 전망이 보이다] — "it's forecast/expected that..."** Marks a
prediction about a future trend, typically in formal/news-style register. Example: 서울 인구가
차차 줄어들 전망이다 "Seoul's population is expected to gradually decline."

---

## Lesson 31: 다이어트가 유행처럼 퍼지고 있어요 ("Dieting is spreading like a fad")

PDF pp. 292–300. Dialogue between Jiyeon and Junseok about the dieting craze among young Korean
women, framed as a genuine public-health topic (hypertension/heart disease prevention for the
elderly, contrasted with young women's non-medical fad dieting) rather than purely cosmetic.
**Sociocultural/gender finding (this lesson's main value):** the dialogue cites an in-universe
survey finding that over half of young women surveyed think of themselves as fat, while over half
of young men surveyed think they should gain more weight/muscle — framed by both speakers as
counterintuitive ("if anything, women look too thin and men should lose weight"), a concrete
gendered body-image contrast data point. The lesson closes by reframing the real need as moderate
exercise rather than dieting per se.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 남녀노소(男女老少) | men and women, young and old — everyone | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| -을/를 막론(莫論)하고 | regardless of, irrespective of | grammatical pattern (postpositional) | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 고혈압(高血壓) | high blood pressure, hypertension | noun | technical.medical | — | — | — | — | grammar_reference | n/a | n/a | |
| 요새 | these days | noun/adverb | colloquial | — | — | — | — | grammar_reference | n/a | n/a | glossed as a colloquial synonym of 요즘 |
| 무조건(無條件) | unconditionally, no matter what | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 무리(無理)하게 | unreasonably, excessively | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 부작용(副作用) | side effect | noun | technical.medical | — | — | — | — | grammar_reference | n/a | n/a | |
| 날씬하다 | slim, slender | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 희망 사항(希望事項) | something one hopes for, a wish item | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 끼 | a meal (counter) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 차라리 | rather, might as well | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | also forms the comparative pattern below |
| 절반(折半) | half | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 반면(反面)에 | on the other hand, whereas | adverb/pattern | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 마르다 | to be thin, skinny | adjective/verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 동감(同感) | agreement, same feeling | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 고하(高下) | high and low (of rank/status) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 여하(如何) | how, in whatever way | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 무시(無視) | disregard, disrespect | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 상(傷)하다 | to spoil, go bad (of food) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 체중(體重) | body weight | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 조언(助言) | advice | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 규칙적(規則的)으로 | regularly | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 간식(間食) | snack | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 관련(關聯)하다 | to be related to | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |

### Grammar points

**-을/를 막론하고 — "regardless of, no matter what X."** Marks a noun as a distinction that doesn't
matter for the following claim. Example: 지위의 고하를 막론하고 법을 어기면 안 됩니다 "Regardless
of rank, you must not break the law."

**-다기보다는 — "rather than saying X, [it's more Y]."** Softens/corrects a prior characterization
by reframing it. Example: 싫다기보다는 시간이 없어서 못 읽는 거지요 "It's not so much that I
dislike it — I just don't have time to read."

**V-기까지 하다 — "to even go so far as to V."** Marks an action as an extreme, additional step
beyond what's expected. Example: 돈이 모자란다고 하니까 친구가 돈을 내 주기까지 했어요 "When I said
I was short on money, my friend even went so far as to pay for me."

**V-느니 차라리 / 차라리 (bare adverb) — "rather than V, might as well... / might as well
just..."** Expresses a preference for an alternative viewed as better even if not ideal. Example:
이렇게 무시당하느니 차라리 회사를 그만두는 게 낫다 "Rather than being disrespected like this, I
might as well quit the company." 차라리 alone functions as a general "might as well, preferably"
adverb: 차라리 안 나가는 게 좋겠어 "I'd rather just not go out."

**-(으)ㄴ/는 반면에 — "whereas, while on the other hand."** Contrasts two facts about the same or
related subjects. Example: 남을 가르치는 일은 힘든 반면에 보람도 있다 "Teaching others is hard,
but on the other hand it's also rewarding."

**살이 찌다[빠지다] — idiom, "to gain [lose] weight."** Fixed idiom built on 살 "flesh/body fat" +
찌다 "to pile up" / 빠지다 "to come out, be removed." Example: 살이 찌면 찔수록 건강에 도움이 안
돼요 "The more weight you gain, the worse it is for your health."

---

## Lesson 32: 애완동물이 자식보다 낫다 ("A pet is better than one's own children")

PDF pp. 301–313. Opens with an expository passage on Korea's aging population: medical advances
and rising living standards are increasing the elderly population, while nuclear-familyization
(핵가족화) and dual-income couples mean fewer children are available to care for aging parents,
driving growth in elderly welfare facilities, for-fee nursing homes (유료 양로원), and elder-only
hospitals — explicitly framed against a backdrop of Korea's traditional 경로사상 ("respect-for-
elders ideology") eroding as a formerly central social virtue. **Sociocultural set-piece (this
lesson's main value):** a neighbor dialogue built around the proverb/saying 품안의 자식 ("a child
is only a child while still in your bosom" — i.e. children grow up and leave) and the lesson's own
titular saying 애완동물이 자식보다 낫다 ("a pet is better than your own children"), illustrated
by an elderly grandfather who dotes on a grandchild's dog after his actual children rarely visit;
the dialogue also cites an (in-universe) British research finding that pet ownership helps prevent
and treat illness in the elderly via the psychological comfort of an animal's "loyalty" (충성심).
Closing discussion questions ask learners to define what age counts as "elderly" and to design
their own vision of a happy old age (양로원 vs. living with children vs. a spouse vs. friends,
volunteer work, hobbies, travel).

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 의학(醫學) | medicine (the field of study) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 향상(向上) | improvement, rise | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 고령(高齡) | advanced age, old age | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 증가(增加)하다 | to increase | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 핵가족(核家族) | nuclear family | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 돌보다 | to look after, take care of | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 홀로 | alone, solitarily | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 노후(老後) | one's later/old age | noun | core | — | — | — | — | grammar_reference | n/a | n/a | lit. "after [becoming] old" |
| 복지(福祉) | welfare | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 교외(郊外) | the outskirts, suburbs | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 유료(有料) | fee-charging, paid | noun/adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 양로원(養老院) | nursing home, home for the elderly | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 들어서다 | to be established, spring up (of a building/institution) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 고유(固有) | inherent, native, indigenous | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 미덕(美德) | virtue | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 경로사상(敬老思想) | the ideology/ethic of respecting one's elders | noun | core | — | — | — | — | grammar_reference | n/a | n/a | named sociocultural concept, this lesson's throughline |
| 강아지 | puppy | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 쓸쓸하다 | lonely, desolate | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 고작 | at most, no more than (and the fixed phrase 고작(해야)) | adverb | colloquial | — | — | — | — | grammar_reference | n/a | n/a | frequently signals a dismissive/understating tone — see grammar points |
| 품 | one's bosom/embrace | noun | core | — | — | — | — | grammar_reference | n/a | n/a | key word in the 품안의 자식 proverb above |
| 기르다 | to raise, rear | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 효과(效果) | effect, result | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 충성심(忠誠心) | loyalty, devotion | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 공경(恭敬)하다 | to revere, treat with deference | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 나아가다 | to advance, go forward (also "furthermore") | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 인력(人力) | manpower, human resources | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 활용(活用)하다 | to make use of, utilize | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 황혼기(黃昏期) | the "twilight years" (of life) | noun | literary | — | — | — | — | grammar_reference | n/a | n/a | metaphorical register, lit. "dusk period" |
| 주위(周圍) | surroundings, vicinity | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 위(爲)하다 | to cherish, do for the sake of | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 중고차(中古車) | used car | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 문의(問議)하다 | to inquire | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 셔틀버스 | shuttle bus | noun | core | — | — | — | — | grammar_reference | n/a | n/a | loanword |
| 전시회(展示會) | exhibition | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 의사소통(意思疏通) | communication, mutual understanding | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |

### Grammar points

**V-다 V-다 하면서(도) — "saying/claiming X all along, yet..."** Repeats a plain-style verb form
twice with 하면서(도) to express that someone kept saying they'd do something while not actually
doing it. Example: 집 안 청소를 한다 한다 하면서도 요즘 바빠서 못하고 있다 "I keep saying I'll
clean the house, but I've been too busy lately."

**얼굴(을/만) 내밀다 — idiom, "to [just] show one's face, make a brief appearance."** Example:
얼굴만 내밀고 올 테니까 10분만 기다려 줘 "I'll just show my face and come back, so wait 10
minutes."

**고작(해야) / V-는 게 고작이다 / N이/가 고작이다 — "at most, no more than."** A family of
constructions all expressing that something amounts to a surprisingly small maximum. Example:
손님도 고작해야 다섯 명뿐인데 "There are at most five guests"; 하숙비 내는 게 고작이다 "[the
salary] is barely enough to cover the rent, at most."

**어찌나 Adj/V-(으)ㄴ/는지 — "so [adjective] that..." (exclamatory degree clause).** Marks an
extreme degree leading to the result in the main clause. Example: 날씨가 어찌나 추운지 5분도 서
있을 수 없다 "It's so cold that I can't stand outside for even 5 minutes."

**N에(게) 마음을 붙이다 / V-는 데(에) 마음을 붙이다 — idiom, "to grow fond of, take comfort in."**
Example: 사진 찍는 데에 마음을 붙여서 다행입니다 "I'm glad [they've] taken comfort in [the hobby
of] photography."

---

## Lesson 33: 시와 노래 ("Poems and Songs")

PDF pp. 314–321. **Literary/cultural capstone lesson** (no dialogue, no vocabulary-drill exercise
apparatus) — this series' equivalent of the literary set-piece already flagged as a recurring
pattern in sibling volume `established/040` (Vol. 3). Presents three real, named Korean literary/
musical works in full, each with brief author attribution and (for the song) composer attribution,
without surrounding grammar explanation. **Per copyright discipline, these are not reproduced at
length here — title/author, theme, and at most one short illustrative line each:**

1. **"저녁에" ("In the Evening"), 김광섭 (Kim Gwang-seop)** — a short, widely known modern Korean
   poem using night-sky imagery (a single star looking down, one person looking up at it among a
   crowd) as a metaphor for human connection and eventual parting; its final couplet — loosely,
   "two people this close, / where will we become what, to meet again?" — is one of the most
   frequently quoted lines in modern Korean poetry (also the source of a common rhetorical
   phrase, "어디서 무엇이 되어 다시 만나랴").
2. **"서시" ("Prologue"), 윤동주 (Yun Dong-ju)** — arguably the single most iconic poem in modern
   Korean literature, written under Japanese colonial rule; opens (paraphrased) with a vow to
   live without a speck of shame under the sky until the day of death, moving through guilt over
   even the stirring of leaves in the wind, to a resolve to love all things that are dying and to
   walk the path given to oneself, closing on a star brushed by wind at night. Flagged as
   high-value canonical cultural-literacy content for this project's "writing for men"/story
   reference purposes given the poem's stature, though full text is not reproduced here.
3. **"아침 이슬" ("Morning Dew"), 김민기 (Kim Min-ki), song lyrics** — a Korean folk song (1970)
   that became a defining anthem of Korea's pro-democracy student movement; opens (paraphrased)
   describing dew settling on blades of grass after a long sleepless night. **Sociopolitical/
   historical flag:** this song's real-world status as a protest/democratization-movement anthem
   is itself a significant piece of sociocultural context the source presents without comment —
   worth surfacing explicitly for any later mechanics-analysis work on register/connotation, since
   the bare lyrics alone don't convey this historical loading.
4. **"내 마음" ("My Heart"), 김동명 (Kim Dong-myeong)** — a classical lyric poem built on four
   parallel metaphors across four stanzas, each opening "내 마음은 ___이오" ("my heart is a
   ___") — a lake (asking the beloved to row toward it), a candle (asking the beloved to shut the
   door, as it burns down to nothing in devotion), a wanderer (asking the beloved to play a
   flute, as it listens alone through the night), and a fallen leaf (asking only to rest briefly
   in the beloved's garden before the wind carries it away again) — a sustained-metaphor technique
   worth flagging as a distinct poetic device from the other three works' more direct imagery.

### Vocabulary

Covers poetic/literary vocabulary drawn from across all four works; many entries carry a markedly
more literary register than this series' ordinary dialogue-lesson vocabulary, tagged accordingly.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 정(情)답다 | affectionate, warm, close | adjective | literary | — | — | — | — | grammar_reference | n/a | n/a | from "저녁에" |
| 서시(序詩) | a prologue/preface poem | noun | literary | — | — | — | — | grammar_reference | n/a | n/a | also the title of Yun Dong-ju's poem itself |
| 우러르다 | to look up (with reverence) | verb | literary | — | — | — | — | grammar_reference | n/a | n/a | from "서시" |
| 일다 (바람이) | to arise, rise up (of wind) | verb | literary | — | — | — | — | grammar_reference | n/a | n/a | |
| 이슬 | dew | noun | core | — | — | — | — | grammar_reference | n/a | n/a | title word of "아침 이슬" |
| 지새우다 | to stay up all night (without sleeping) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 맺히다 | to form into droplets, congeal | verb | literary | — | — | — | — | grammar_reference | n/a | n/a | |
| 진주(眞珠) | pearl | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 곱다 | beautiful, lovely (of appearance/texture) | adjective | literary | — | — | — | — | grammar_reference | n/a | n/a | |
| 설움 | sorrow, grief | noun | literary | — | — | — | — | grammar_reference | n/a | n/a | |
| 알알이 | grain by grain, drop by drop | adverb | literary | — | — | — | — | grammar_reference | n/a | n/a | |
| 동산 | a small hill near a village | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 미소(微笑) | a smile | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 태양(太陽) | the sun | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 묘지(墓地) | graveyard | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 떠오르다 | to rise (of the sun/moon) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 찌다 | to be sweltering, steam-hot | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 더위 | heat | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 시련(試鍊) | a trial, an ordeal | noun | literary | — | — | — | — | grammar_reference | n/a | n/a | |
| 광야(廣野) | a vast, open wilderness | noun | literary | — | — | — | — | grammar_reference | n/a | n/a | |
| 호수(湖水) | lake | noun | core | — | — | — | — | grammar_reference | n/a | n/a | central metaphor of stanza 1 of "내 마음" |
| 젓다 | to row, to stir | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 그림자 | shadow | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 옥(玉) | jade | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 부서지다 | to shatter, break into pieces | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 촛불 | candlelight | noun | core | — | — | — | — | grammar_reference | n/a | n/a | central metaphor of stanza 2 of "내 마음" |
| 비단(緋緞) | silk | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 옷자락 | the hem/skirt of a garment | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 떨다 | to tremble, shiver | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 최후(最後) | the very end, the final (moment) | noun | literary | — | — | — | — | grammar_reference | n/a | n/a | |
| 남김 없이 | leaving nothing behind, entirely | adverb | literary | — | — | — | — | grammar_reference | n/a | n/a | |
| 타다 | to burn | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 방울 | a drop (of liquid) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 나그네 | a wayfarer, wanderer, traveler | noun | literary | — | — | — | — | grammar_reference | n/a | n/a | central metaphor of stanza 3 of "내 마음" |
| 피리 | flute | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 기울이다 (귀를) | to lend an ear, listen attentively | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 호젓이 | quietly and lonesomely | adverb | literary | — | — | — | — | grammar_reference | n/a | n/a | |
| 뱃전 | the side/edge of a boat | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |

---

## Lesson 34: 세대 차가 실감 나는구나 ("The generation gap is really hitting home")

PDF pp. 322–329. Dialogue between Minsu and his mother after he gets a job and she raises
marriage; the lesson is built entirely around a generational argument over 현모양처 ("wise mother,
good wife" — a traditional feminine-virtue ideal). **Sociocultural/gender-role finding (this
lesson's main value):** Minsu claims the *meaning* of 현모양처 has itself shifted generationally —
no longer requiring frugal full-time homemaking, but now satisfiable by a woman with her own
career and "economic ability" even if she isn't especially good at housework; his mother calls this
reasoning absurd and states outright that some women using "social life" (사회생활) as an excuse to
neglect the household is "a big mistake," insisting that being a good wife (내조, lit. "inner
help") and raising children properly is what it means to live well. The lesson explicitly glosses
세대 ("generation") as a roughly **30-year age-cohort unit** sharing common consciousness, and
closes with a discussion prompt noting that nowadays even people only 3 years apart in age can
report feeling a "generation gap" (세대 차) — i.e. the source itself frames generational-register
distance as compressing over time, directly relevant to this project's register/slang-change
interests.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 세대 차(世代差) | generation gap | noun | core | — | — | — | — | grammar_reference | n/a | n/a | lit. "generational difference" |
| 실감(實感)(이) 나다 | to really feel/sense (something) as real | idiom | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 이르다 | to be early | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 구체적(具體的) | concrete, specific | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 살림 | housekeeping, household management | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 보수적(保守的) | conservative | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 현모양처(賢母良妻) | "wise mother, good wife" (a traditional feminine-virtue ideal) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | culturally load-bearing term, this lesson's throughline — see coverage note above |
| 세대(世代) | generation | noun | core | — | — | — | — | grammar_reference | n/a | n/a | source explicitly glosses this as a ~30-year age-cohort unit sharing common consciousness |
| 내조(內助) | a wife's support of her husband (lit. "inner help") | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 집사람 | "my wife" (lit. "house person") | noun | core | — | — | — | — | grammar_reference | n/a | n/a | already documented elsewhere in `established/`'s honorific/address-term material; included because this lesson's own box lists it |
| 세일 | a (retail) sale | noun | core | — | — | — | — | grammar_reference | n/a | n/a | loanword |
| 불경기(不景氣) | an economic downturn, recession | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 경영(經營) | management, business administration | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 되돌아보다 | to look back on, reflect on | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 연령층(年齡層) | an age bracket/cohort | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |

### Grammar points

**-(으)ㄴ 감이 있다 — "to have a bit of a feeling that..., to come across as somewhat..."** Softens
an evaluative claim as a subjective impression rather than a flat assertion. Example: 좀 늦은 감이
있지만 더 늦기 전에 지금이라도 고맙다는 전화를 해야겠어요 "It feels a little late, but I should
call to say thanks before it gets even later."

**-(이)야— emphatic topic particle, "as for X (that's the easy/separate part)."** Marks a noun as a
conceded or set-aside point, often implying a contrast with something harder/more important.
Example: 돈이야 벌면 되지만 건강은 잃으면 다시 찾을 수 없어요 "Money, well, you can just earn more
— but health, once lost, you can't get back."

**N만 해도 — "just take N (as an example), even N."** Introduces a representative example to
support a generalization. Example: 내 친구들만 해도 반 정도밖에 직장을 못 얻었어요 "Just take my
friends, for example — only about half of them managed to get jobs."

**-더라고(요) — experiential-retrospective ending, "I noticed/found that..."** Reports something
the speaker personally witnessed or experienced firsthand, distinct from plain -았/었어요. Example:
지난번에 먹어 봤는데 맛있더라고요 "I tried it last time, and [I can tell you] it was good."

---

## Lesson 35: 유럽에 배낭여행 갔다 왔다면서? ("I heard you went backpacking in Europe?")

PDF pp. 330–339 — **the final lesson of the book** (confirmed: content ends here and the back-
matter word index begins immediately after). Intro essay on how travel enriches life by breaking
people out of monotonous routine and letting them discover both differences and unexpected
commonalities with people elsewhere — framed explicitly as a tool for self-reflection via
comparison with others. **Idiom finding:** 다람쥐 쳇바퀴 돌듯(이) ("like a squirrel spinning on its
wheel") for a repetitive, treadmill-like daily routine. Dialogue: Yeonggyeong asks Gyeongsu about
his month-long backpacking trip across five European countries. **Sociocultural/cross-cultural
finding (this lesson's main value):** Gyeongsu reports being startled to learn that European
university students he met become fully financially independent from their parents right after
high school — covering not just tuition but living expenses, to the point of working up to 50
hours a week during school breaks — explicitly contrasted with the Korean 아르바이트 (part-time
job) norm of merely earning spending money (용돈) on top of parent-covered costs; the dialogue
frames this as something that left a real impression ("정말 열심히 살더라" "they really live
hard"). The lesson closes with a structured vocabulary set for discussing travel in general: trip
types (수학여행 school trip, 신혼여행 honeymoon, 무전여행 "moneyless travel"/hitchhiking-and-
begging-style travel, 배낭여행 backpacking, 패키지 여행 package tour), purposes (관광 sightseeing,
휴양 rest/recuperation), transport modes, and lodging types (민박 homestay, 여관 inn, 호텔, 텐트).

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 소감(所感) | one's impressions, thoughts (on an experience) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 물질적(物質的) | material (as opposed to spiritual) | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 유산(遺產) | a legacy, inheritance | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 접(接)하다 | to come into contact with, encounter | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 반복(反復)하다 | to repeat | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 지장(支障) | an obstacle, hindrance (to doing something) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 전공(專攻) | one's (academic) major | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 능통(能通)하다 | to be fluent/proficient (in) | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 통(通)하다 | to get through, communicate successfully | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 꽤 | quite, fairly | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 물려주다 | to pass down, hand down (property/status) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 동해(東海) | the East Sea (Sea of Japan) | proper noun | core | — | — | — | — | grammar_reference | n/a | n/a | Korea's own name for this body of water |
| 목적지(目的地) | destination | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 수단(手段) | means, method | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 수학여행(修學旅行) | a school (educational) trip | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 신혼여행(新婚旅行) | honeymoon trip | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 무전여행(無錢旅行) | "moneyless travel" (traveling by begging/hitchhiking with no funds) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | culturally specific travel-style term with no tidy single-word English equivalent |
| 패키지 (여행) | package (tour) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | loanword |
| 휴양(休養) | rest and recuperation | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 도보(徒步) | going on foot | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 민박(民泊) | a homestay/lodging in a private home | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 여관(旅館) | an inn | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 여행지(旅行地) | a travel destination/area | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 풍요(豐饒)롭다 | abundant, affluent | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 쳇바퀴 | a (hamster/squirrel) wheel | noun | core | — | — | — | — | grammar_reference | n/a | n/a | key word in the idiom below |
| 박히다 (틀에) | to be fixed/set (in a mold or pattern) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 벗어나다 | to escape, break free from | verb | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 평소(平素) | ordinary times, usual circumstances | noun | core | — | — | — | — | grammar_reference | n/a | n/a | |
| 여간(如干) | ordinarily, to a common degree | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | almost always used with negation — see grammar points |
| 윤택(潤澤)하다 | well-off, abundant (lit. "moist and glossy") | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | |

### Grammar points

**다람쥐 쳇바퀴 돌 듯(이) — idiom, "like a squirrel spinning on its wheel" (monotonous
repetition).** Describes a repetitive, treadmill-like routine devoid of variety. Example: 현대인은
다람쥐 쳇바퀴 돌 듯 날마다 같은 생활을 반복하죠 "Modern people repeat the same life every day,
like a squirrel spinning on its wheel."

**여간 -(으)ㄴ N이/가 아니다 / 여간 Adj-지 않다 — litotes, "not just an ordinary N / not just
ordinarily [adjective]" (i.e. extremely N/adjective).** A double-negative-style intensifier:
denying that something is "ordinary" to assert it's extraordinary. Example: 김 선생님은 여간
훌륭한 분이 아닙니다 "Mr. Kim is no ordinary remarkable person" (= Mr. Kim is truly remarkable).
여간 어렵지 않았습니다 "It was far from ordinarily difficult" (= it was extremely difficult).

**V-기는(요) / N은/는(요) — "what do you mean, X?!" (emphatic negation/correction).** A retort
pattern that flatly denies the premise of the previous statement/question, often followed by the
actual truth. Examples: 재미있었니? — 재미있기는. 너무 재미없어서 보다가 잤어 "Was it fun? — Fun?
Please, it was so boring I fell asleep watching it." 이거 새 옷이지요? — 새 옷은요. 언니가 입던
건데 "This is new, right? — New? Hardly — it's my sister's old one."

**N에 지장이 있다[없다, 많다] / V-는 데(에) 지장이 있다[없다, 많다] — "to interfere [not interfere,
interfere a lot] with N/V-ing."** Describes the degree to which something hinders an activity.
Example: 공부에 지장이 많으면 그만두겠어요 "If it interferes with my studies a lot, I'll quit [it]."

**N에 능통하다 — "to be fluent/highly proficient in N."** Example: 그분은 외국어에 능통하기 때문에
쉽게 취직이 됐어요 "Because he's fluent in foreign languages, he found a job easily."

---

## Summary

**35 lessons, PDF pp. 1–339, fully extracted.** Approximate totals: **~930 vocabulary entries**
(L1–9: ~230, L10–18: ~233, L19–25: ~195, L26–35: ~276) and **~175 grammar points** (L1–9: ~45,
L10–18: ~45, L19–25: ~38, L26–35: ~48) across the 35 lessons, plus a substantial number of
explicitly-taught idioms/proverbs concentrated in Lessons 7, 20, 24, 27, 28, and 29.

**No explicit dialectal/regional annotation** (bracketed register tags, "formal" vs. "colloquial"
source-marked labels) was found anywhere in this volume, with one partial exception: Lesson 24's
named regional-variant taxonomy for the folk song *Arirang* (경기/정선/진도/밀양 Arirang) — a
geographically-anchored song-tradition classification stated directly in the source's own text,
not a word-level dialect tag, but flagged per the coverage rule as must-not-skip content.

**Flagship sociocultural/register findings across the volume:** the Dangun founding myth (L2) and
genuine newspaper-register reading excerpts (L3); Korea's collectivist-friendship/family-intimacy
norm vs. individual privacy (L9); the 임꺽정 "righteous bandit" folk-historical narrative (L10) and
the Gangnam/Gangbuk tutoring-cost disparity in formal broadcast register (L11); an explicit
Confucian-gender-role discussion citing Simone de Beauvoir (L13); a meta-linguistic 국어-vs-한국어-
teacher distinction directly adjacent to this project's own domain (L14); disability-accessibility
advocacy content with an in-text statistic (L16); two consecutive Seollal/Yunnori/Daeboreum
holiday-custom lessons (L17–18); an explicit Korean-vs-Japanese drinking-etiquette contrast (L20);
a productive "looks V-worthy" adjective-derivation family (믿음직/먹음직/바람직하다, L21); a
dedicated internet/digital-life vocabulary field (L23); the Arirang folkloristics essay and its
한(恨)/흥(興) affective-concept pair (L24); the Heungbu/Nolbu charity-vs-greed folktale, this
volume's capstone narrative (L25); the Kim Jeong-ho/*Daedongyeojido* cartography biography (L26); a
real speech-register/vulgarity-survey dialogue plus four speech-themed proverbs, directly on-topic
for this project's slang-mechanics purpose (L27); the 낳은 정/기른 정 parent-child-bond concept
pair via a baby-swap news story (L28); the *inyeon* (fated-bond) belief system (L29); a Seoul
historical timeline and an explicit North/South population comparison (L30); gendered body-image
survey data (L31); the 경로사상/품안의 자식 elder-care theme (L32); a four-work literary/song
capstone including Yun Dong-ju's "서시" and the democratization-anthem "아침 이슬" (L33); a
generational 현모양처 gender-role dispute with an explicit ~30-year generation-cohort definition
(L34); and a Korea-vs-Europe student-financial-independence contrast closing the book (L35).

**PDF/OCR summary:** a genuine, usable Hangul text layer throughout all 339 content pages — no
font-substitution cipher, no vision-reading required anywhere in this volume. Recurring but fully
worked-around OCR quirks: stray single-glyph noise, scrambled drill-exercise blocks (skipped per
the coverage rule regardless), and the multi-column end-of-lesson vocabulary-box layout (resolved
via `pdftotext -layout` or by cross-checking a displaced Chinese-gloss block's order against the
Korean-language definitions already present). A handful of individual entries with more specific,
localized OCR damage are flagged in their own Notes-column entries rather than silently guessed
(Lessons 19, 26, 29, 30). No handwritten marginalia anywhere (not applicable to a real text layer).

**Back matter excluded, per the coverage rule:** an alphabetized Korean vocabulary/grammar-pattern
index keyed to lesson number (PDF pp. ~340–349) and a "听力脚本" (Listening Script) appendix giving
the text of each lesson's listening-comprehension audio exercises (PDF pp. ~350–381) — both pure
re-listing/answer-key-adjacent apparatus, not reference content in their own right.

---
