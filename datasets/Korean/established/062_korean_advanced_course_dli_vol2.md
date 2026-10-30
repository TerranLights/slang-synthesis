# Korean — Established Vocabulary/Grammar: Korean Advanced Course, Volume II (Defense Language Institute)

**Source:** *Korean Advanced Course, Volume II* (Defense Language Institute, July 1971). A 20-article
reader for post-Basic-Course continuation training, "drawn from several readers published by the
Ministry of Education of the Republic of Korea in 1970" (per the source's own Preface). Each of the
20 units is a short expository or narrative article followed by 20 comprehension `QUESTIONS` and a
`VOCABULARY` list. Source file: `Korean Advanced Course. Volume II (Defence language Institute).pdf`
(84 PDF pages, no text layer, no embedded fonts at all — `pdffonts` returns an empty table and
`pdfimages -list` shows every page is a plain JBIG2 raster scan). The `+36266` Hangul-cipher decode
was not applicable here (there is no font/ToUnicode layer to decode in the first place); the entire
file was vision-read directly from rendered page images.

**This is NOT a complete scan of the book.** The physical document's own continuous page-stamp
numbering (a bold Arabic numeral centered at the foot of each page, separate from a smaller
secondary page count also present on most pages) jumps from **58 straight to 198** partway through
this 84-page PDF — i.e. this file contains only a *curated excerpt* of the original volume, not
pages 58–197. Cross-referencing against the book's own 20-unit Table of Contents (reproduced on the
file's 4th PDF page) establishes exactly which units survive in this file:

- **Units 1–5** (`Democracy and Capitalism`, `Institutions that Help Industry`, `Telephone`,
  `Visiting the Radio Broadcasting Station`, `A Cotton Plant`) are present **in full** — each unit's
  article text, its 20 Questions, and its Vocabulary list.
- **Units 6–18** (`The Stethoscope` through `The Truth About North Korea`'s own opening) **are
  entirely absent** from this file — not a gap worth re-dispatching for, since the physical PDF
  simply does not contain those pages at all.
- **Unit 19 (`The Truth About North Korea`)** is **partial** — the file picks up mid-sentence
  (discussing separation-of-powers and the absence of real democracy in the North) and includes only
  the article's final two sub-sections (`경제 사정` "Economic conditions" and `일반 사회 생활`
  "General social life") plus the full 20 Questions and full Vocabulary list. The earlier
  sub-sections (on the origin of Communism, the structure of the "People's Assembly," elections, and
  the judiciary) are not in this file at all — though the Questions list itself still names all of
  those missing topics, so the unit's full scope is recoverable even without its missing prose.
- **Unit 20 (`The Chunlima Movement in North Korea`)** is present **in full**.
- The file's final ~7 pages are a **photo supplement** (DPRK propaganda-style photographs with their
  own Korean captions, illustrating industrial/labor themes matching Unit 20) rather than any further
  unit text — the file simply ends there at its own PDF page 84.

**New PDF-production gotcha found on this source (worth flagging for future DLI-series dispatches):**
this is a `PdfCompressor`/CVISION-produced JBIG2 scan (confirmed via `pdfinfo`'s `Creator`/`Producer`
fields), and at least two `VOCABULARY` lists (Unit 2's and Unit 4's) that should plausibly have run
onto a second page instead show a corrupted, largely-blank page with only a vertical sliver of
unrelated bitmap noise bleeding in from the page edge — distinct from the "two-pages-per-image
spread" and "non-monotonic page order" gotchas already documented in the extraction spec, this looks
like the JBIG2 compressor's shared-symbol dictionary losing or misassigning glyphs on specific pages.
**A handful of vocabulary entries at the tail of Units 2 and 4 are likely lost to this corruption**,
not merely unread — flagged here rather than silently treated as "list complete."

**Vision-reading guard note:** every Korean word in every `VOCABULARY` list in this source is
rendered in a consistent hand-lettered/stencil script (the book's own production method for
inserting Hangul into an otherwise typewritten English-metalanguage document — the same convention
seen throughout this DLI series), appearing uniformly across all 84 pages with no stylistic
inconsistency. This was judged to be the book's own printed production method, **not** a previous
owner's handwritten marginalia, and was extracted normally. No actual marginalia (pencil notes,
underlining, answer-key scribbles) was found anywhere in this file.

**Non-redundant-supplement scoping:** this is a civics/current-affairs reading-comprehension course
(biography, economic institutions, a historical legend, DPRK political/economic critique) — a
different genre from every previously-extracted Korean source (grammar references, phrasebooks,
dictionaries, dialect readers). No overlap-skipping was needed; essentially all vocabulary here is
new to the established Korean corpus. (This file does not overlap with `established/061`, the
parallel extraction of *Volume I* of this same series, covering a disjoint page range of a different
physical PDF.)

---

## Vocabulary

### Unit 1 — 민주주의와 자본주의 (Democracy and Capitalism)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 인권 (人權) | human rights | noun | technical.political | — | contemporary (source published 1970–71) | — | — | grammar_reference | n/a | plausible_unverified | |
| 존엄하다 | to be dignified, solemn | adjective | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 보석 | jewel | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 수단 | means | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 위엄 | dignity | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 인격 (人格) | personality, (esp. moral) character | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | source gloss literally "personality, especially" — truncated in source |
| 행사하다 | to exercise (a right) | verb | technical.political | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 침범 | invasion, encroachment | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 이성 (理性) | reason | noun | technical.philosophy | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 합치하다 | to agree with, coincide | verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 구태여 | deliberately, (needlessly) | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 재산 | property | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 개성 | individuality | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 근세 (近世) | recent era, modern times | noun | technical.history | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 박애 | philanthropy, universal love | noun | technical.philosophy | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | glossed in text as one leg of French "liberté, égalité, fraternité" |
| 귀족 | nobility, aristocracy | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 봉건시대 (封建時代) | feudal age | noun | technical.history | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 산업혁명 | industrial revolution | noun | technical.history | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 부강 (富强) | wealth and power (of a nation) | noun | technical.political | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 공헌 | contribution | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 소질 | qualities, aptitude | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 후진국 (後進國) | backward/developing nation | noun | technical.political | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 복지 (福祉) | well-being, welfare | noun | technical.political | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 번영 | prosperity | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 지주 (支柱) | support, prop, pillar | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |

### Unit 2 — 상업을 돕는 기관 (Institutions that Help Industry/Commerce)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 상공회의소 | Chamber of Commerce | noun | technical.economic | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 흥신소 | credit bureau | noun | technical.economic | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 상공장려관 | Commercial and Industrial Museum | noun | technical.economic | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 무역 (貿易) | trade | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 진흥 (振興) | promotion, furtherance | noun | technical.economic | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 공사 (公社) | public corporation | noun | technical.economic | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 공증인 (公證人) | notary public | noun | technical.legal | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 변리사 (辨理士) | patent attorney | noun | technical.legal | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 공인회계사 (公認會計士) | certified public accountant | noun | technical.economic | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 상공업자 (商工業者) | merchants and industrialists | noun | technical.economic | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 개선 (改善) | betterment, improvement | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 조직하다 (組織) | to organize | verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 꾀하다 | to plan, scheme | verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 상대편 | the other party | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 신용 (信用) | credit, trust | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 의뢰하다 (依賴) | to depend on, entrust | verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 인물 (人物) | the quality/caliber of a person | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 재산상태 (財産狀態) | one's financial status | noun | technical.economic | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 보수 (報酬) | recompense, fee | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 품질 (品質) | quality | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 규격 (規格) | standard, norm | noun | technical.economic | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 수출 (輸出) | export | noun | technical.economic | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 진열하다 (陳列) | to display | verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 견본 (見本) | sample | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 박람회 | exhibition, exposition, fair | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | **list likely continues beyond this point — the following page is corrupted (see coverage note); any further Unit 2 vocabulary items are not recoverable from this file** |

### Unit 3 — 전화 (Telephone — the Alexander Graham Bell story)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 맹아 (盲啞) | the blind and the deaf-mute | noun | technical | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 서기 (西紀) | Western calendar / A.D. | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 장난감 | toy | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 성미 (性味) | character, disposition | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 성가시다 | to be troublesome, bothersome | adjective | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 모형 (模型) | model | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 의문 (疑問) | question, doubt | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 입술 | lip | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 궁리하다 (窮理) | to ponder | verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 풀무 | bellows, blower | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 워낙 | by nature, originally | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 진동 (振動) | vibration | noun | technical | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 문득 | suddenly | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 금 | line | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 비웃다 | to sneer at | verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 심지어 (甚至於) | what is more, even | adverb | core | — | contemporary | — | — | grammar_reference | n/a | low_confidence | source's own hand-lettered Hangul read as 십지어; corrected here to the standard form 심지어, which the attached Hanja (甚至於) and gloss both confirm |
| 꾸짖다 | to blame, scold | verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 골몰하다 (汨沒) | to be absorbed (in work) | verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 입김 | breath, steam of breath | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 야단하다 | to fuss about | verb | colloquial | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 어느덧 | before one knows it | adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 우거지다 | to grow thick/lush | verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 시계태엽 | watch spring | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 가냘프다 | to be feeble, thin, slender | adjective | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 다가서다 | to come up close (and stand) | verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |

### Unit 4 — 방송국을 찾아서 (Visiting the Radio Broadcasting Station)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 대목 | the most important occasion/juncture | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 편집실 (編輯室) | editorial department | noun | technical | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 거침없이 | smoothly, unhesitatingly | adverb | core | — | contemporary | — | — | grammar_reference | n/a | low_confidence | source gloss row reads "거침없" — the final 이 appears cropped off the scan edge; restored here |
| 등사 (謄寫) | mimeographing | noun | technical | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 주름 | pleats, wrinkles | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 휘장 (揮帳) | curtain | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 드리우다 | to hang down | verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 양탄자 | rug, carpet | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 잡음 (雜音) | noise | noun | technical | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 반사 (反射) | reflection | noun | technical | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 꾸미다 | to finish up, fix up | verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | polysemous — see also the second 꾸미다 entry below ("to put together") |
| 음향효과 (音響效果) | acoustic/sound effects | noun | technical | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 방송극 (放送劇) | radio drama | noun | technical | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 조정 (調整) | adjustment | noun | technical | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 녹음 (錄音) | sound recording | noun | technical | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 기념 (紀念) | commemoration | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 행사 (行事) | event, function | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 유다르다 | to be uncommon, distinctive | adjective | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 문고리 | door handle/latch | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 물레방아 | water mill | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 꾸미다 | to put together, assemble | verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | second sense of 꾸미다 in the same list — source gives both senses as separate rows |
| 진공관 (眞空管) | vacuum tube | noun | technical | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 유선 (有線) | wired, having wires | adjective | technical | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 송신 (送信) | transmission | noun | technical | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 전파 (電波) | radio wave | noun | technical | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | **list likely continues beyond this point — the following page is corrupted (see coverage note); any further Unit 4 vocabulary items are not recoverable from this file** |

### Unit 5 — 목화 (Cotton Plant — the Mun Ik-jeom legend)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 목화 (木花) | cotton plant | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 하늘거리다 | to dangle, flutter lightly | verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 꽃송이 | blossom | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 눈이부시다 | one's eyes are dazzled | expression | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 열매 | fruit | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 포근하다 | to be soft, cozy | adjective | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 뽑다 | to pull out | verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 짜다 | to weave | verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 무명 | (plain) cotton (cloth) | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 대견하다 | to be gratifying/admirable | adjective | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | source gloss "to be helpful" — likely a loose/approximate rendering of a word that more precisely means "gratifying, impressive" |
| 재배 (栽培) | cultivation | noun | technical | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 수고 | effort, taking trouble | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 선비 | (Confucian) scholar | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 성품 (性品) | nature, disposition | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 효성 (孝誠) | filial piety | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 지극하다 (至極) | to be extreme, utmost | adjective | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 그리다 | to long for, miss | verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 커녕 | to say nothing of | particle | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 삼베 | hemp cloth | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 붓두껍 | brush cap (for a writing brush) | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | the smuggling device in the legend |
| 샅샅이 | everywhere, thoroughly | adverb | core | — | contemporary | — | — | grammar_reference | n/a | low_confidence | source's hand-lettered form read as 살살이; corrected to standard 샅샅이, consistent with the gloss "everywhere" and the body text's search-the-house context |
| 씨앗 | seeds | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 보람이있다 | to be worthwhile, rewarding | expression | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 면포 (綿布) | cotton cloth | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 화폐 (貨幣) | money, currency | noun | technical.economic | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |

### Unit 19 — The Truth About North Korea (partial — article text recovered only from its final two sub-sections)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 실정 (實情) | real/actual condition | noun | technical.political | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 자본가 (資本家) | capitalist | noun | technical.economic | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 빈부 (貧富) | the poor and the rich | noun | technical.economic | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 차이 (差異) | difference | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 폭력 (暴力) | violence | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 쪼들리다 | to be oppressed, hard-pressed | verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 무산자 (無産者) | proletarian | noun | technical.political | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 두목 (頭目) | boss, ringleader | noun | colloquial | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | pejorative framing in context (used of DPRK leadership) |
| 정권을잡다 | to take (political) power | expression | technical.political | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 뒷받침 | (indirect) support, backing | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 독재 (獨裁) | dictatorship | noun | technical.political | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 무조건 (無條件) | unconditional | adjective/adverb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 명령계통 (命令系統) | chain of command | noun | technical.political | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 허울이좋다 | to look good (on the surface), to be a fine-sounding facade | expression | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 헌법 (憲法) | constitution | noun | technical.political | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 주권 (主權) | sovereign power, sovereignty | noun | technical.political | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 노동당 (勞働黨) | (the) Workers'/Labor Party | noun | technical.political | — | contemporary | North Korea (DPRK) | national | grammar_reference | n/a | plausible_unverified | named referent is the DPRK's ruling party |
| 국회의원 (國會議員) | National Assembly member | noun | technical.political | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 선거하다 (選擧) | to elect | verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 정당 (政黨) | political party | noun | technical.political | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 경쟁 (競爭) | competition | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 입후보 (立候補) | candidacy, being a candidate | noun | technical.political | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 투표하다 (投票) | to vote | verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 법정 (法廷) | (law) court | noun | technical.legal | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 천리마 (千里馬) | "thousand-li horse," a legendary swift horse | noun | technical.political | — | contemporary | North Korea (DPRK) | national | grammar_reference | n/a | plausible_unverified | final vocab entry of Unit 19, bridging into Unit 20's topic |

### Unit 20 — 북한의 천리마 운동 (North Korea's Chollima Movement)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 괴뢰 (傀儡) | puppet | noun | technical.political | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | used of the DPRK regime, "puppet regime" framing |
| 도당 (徒黨) | band, clique, gang | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 침략 (侵略) | invasion | noun | technical.political | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 야심 (野心) | ambition | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 들볶다 | to torment, harass harshly | verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 효과 (效果) | effect | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 착취하다 (搾取) | to squeeze out, exploit | verb | technical.political | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 고안하다 (考案) | to plan, devise, design | verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 본받다 | to follow the example of | verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 돌격 (突擊) | assault, charge | noun | technical.military | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 증산 (增産) | increased output/production | noun | technical.economic | — | contemporary | North Korea (DPRK) | national | grammar_reference | n/a | plausible_unverified | named as a Soviet-origin campaign term ("돌격 증산 운동") the article says Chollima copied |
| 약진 (躍進) | advance by leaps, rapid progress | noun | technical.economic | — | contemporary | China (PRC, as named referent) | national | grammar_reference | n/a | plausible_unverified | named as the PRC's "대약진 운동" (Great Leap Forward) the article says Chollima copied |
| 혹독하다 (酷毒) | to be severe, harsh | adjective | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 경마 (競馬) | horse race | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 잔인하다 (殘忍) | to be cruel | adjective | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 악착스럽다 | to be stubbornly relentless | adjective | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 작업반 (作業班) | work party/team | noun | technical.economic | — | contemporary | North Korea (DPRK) | national | grammar_reference | n/a | plausible_unverified | the unit the Chollima title is awarded to |
| 생산 (生産) | production | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 실적 (實績) | record of (actual) performance | noun | technical.economic | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 조작하다 (造作) | to fabricate, manufacture (falsely) | verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | used pejoratively — "fabricate (production figures)" |
| 모범 (模範) | model, exemplar | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 직장 (職場) | place of employment | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 채찍질하다 | to urge/spur on (lit. to whip) | verb | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 초인간 (超人間) | superhuman, superman | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | |
| 영웅 (英雄) | hero | noun | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | the "Labor Hero" title discussed in the article; **list may continue fractionally beyond the visible scan edge — not confirmed complete** |

### Supplementary: North Korean orthography/terminology observed in the photo-caption appendix (pages ~77–84)

These are **not** from any `VOCABULARY` list — they are incidental observations from the Korean
captions printed under a set of DPRK propaganda-style photographs bound in after Unit 20, reproduced
(per the captions' own content — references to specific named "comrades," production quotas, etc.)
as apparently-authentic North Korean source material rather than South-Korean-authored description.
Flagged here because they are a genuine piece of **explicit regional/orthographic contrast data**,
the kind the extraction spec calls out as high-value when a source marks it explicitly:

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 로동자 | worker, laborer | noun | regional | — | contemporary | North Korea (DPRK) | national | grammar_reference | n/a | plausible_unverified | North Korean orthography — initial ㄹ preserved (no 두음법칙), vs. standard South Korean 노동자; same contrastive pattern already flagged as a Phase 1 flagship finding on `established/033` (*Let's Learn Korean, Northern Dialect*) |
| 동무 | comrade (term of address) | noun | regional | — | contemporary | North Korea (DPRK) | national | grammar_reference | n/a | plausible_unverified | caption uses "OOO동무가..." as a personal-name + address-term construction |
| 혁신자 | innovator | noun | technical.political | — | contemporary | North Korea (DPRK) | national | grammar_reference | n/a | plausible_unverified | socialist-labor honorific category, paired with "기능공" (skilled worker) in one caption |
| 생산계획 | production plan/quota | noun | technical.economic | — | contemporary | North Korea (DPRK) | national | grammar_reference | n/a | plausible_unverified | caption cites a specific figure, "1·4분기 생산계획도 140%로 초과수행" ("over-fulfilled the 1st-quarter production plan at 140%") |
| 사회주의경쟁 | socialist competition | noun | technical.political | — | contemporary | North Korea (DPRK) | national | grammar_reference | n/a | plausible_unverified | read directly off a banner/sign visible in one photo ("사회주의경쟁도표" — "socialist competition chart") |

---

## Grammar points

*(This source is a reading-comprehension/civics course, not a grammar-point drill course like most
of the project's other Korean sources — it teaches almost entirely through vocabulary and content,
not through named grammar rules. The observations below are the genuine structural/sociolinguistic
patterns visible across its units, paraphrased rather than any named rule the book itself states.)*

### Fixed unit template: article → 20 comprehension questions → vocabulary list

Every one of the 20 units (confirmed across all 7 present in this file) follows the identical
three-part structure named in the book's own Preface: an expository or narrative article (with
inline photos/illustrations), a set of exactly 20 `QUESTIONS` using wh-question constructions
(누가/무엇을/언제/어디서/왜/어떻게, consistently closed with the formal interrogative `-ㅂ니까?`/
`-습니까?`), and a `VOCABULARY` list glossing the unit's Sino-Korean/technical items into English,
often with the Hanja written beside the Hangul headword. This is a comprehension-and-recall drill
format, not a grammar-point-by-grammar-point teaching format — explaining why this file's Vocabulary
section above is so much larger, proportionally, than its Grammar points section.

### Register split: narrative past-tense essay vs. biographical "-습니다" voice

Units 1, 2, 5, 19, and 20 (civics/institutional/political topics) are written in plain
written-register declarative sentences ending in `-다` (e.g. 그리하여... 지주(支柱)가 되고 있다. —
"and so it has become a pillar [of prosperity]"), the standard register for an impersonal expository
essay. Units 3 and 4 (the Bell biography and the radio-station field-trip account), by contrast, are
written throughout in the polite `-습니다`/`-ㅂ니다` declarative register even in narration (e.g.
두 사람은 기쁨에 못이겨서 서로 껴안고 울었읍니다. — "the two of them, overcome with joy, embraced
each other and wept"), giving those two units a warmer, more personal storytelling voice despite
covering comparably technical content (telephony, broadcast engineering). This is a genuine
register choice tied to genre (biography/first-person field trip vs. impersonal civics essay), not
random variation.

### Sino-Korean compounding density tracks topic abstraction

The vocabulary tables above make this visible directly: institutional/political/economic units
(1, 2, 19, 20) are overwhelmingly Sino-Korean compounds (인권, 자본가, 독재, 천리마 운동 etc., each
glossed with its Hanja), while the two narrative units (3, the Bell story; 5, the cotton legend) mix
in many more native-Korean verbs and descriptive adjectives (하늘거리다, 가냘프다, 우거지다,
포근하다) alongside their Sino-Korean technical terms. This is the same register-tracks-abstraction
pattern documented elsewhere in this project's Korean corpus, here visible within a single small
7-unit sample rather than needing a cross-book comparison to surface.

### A French political loanword transliterated and reglossed

Unit 1's body text transliterates French *bourgeois* directly into Hangul as `부르지와` ('부르지와'
라고 한다, "...is called a 'bourgeois'"), then explicitly notes the word's semantic narrowing in
Korean usage: "이제는 '부르지와'라는 말이 자본가라는 뜻을 가지게 된 것이다" — "and so the word
'bourgeois' came to carry the meaning 'capitalist.'" This is a clean, source-explicit example of a
political loanword's sense narrowing from "(French Revolution-era) urban commoner" to simply
"capitalist" as it entered Korean political vocabulary — not in the Vocabulary table above since it
is a one-off transliteration rather than an established headword, but worth flagging as exactly the
kind of borrowing-and-resemantification datapoint the mechanics-analysis phase will want.

### DPRK-topic units supply contrastive regionally-marked material

Consistent with this project's existing flagship North/South contrastive finding (the
두음법칙-non-application pattern on `established/033`), both Unit 19 and Unit 20 — being
specifically *about* North Korea — supply vocabulary that is either explicitly geo-marked in this
file (노동당, 천리마, 작업반, 증산 as a Soviet-origin term, 약진 as a PRC-origin term the article
says the DPRK copied) or, in the trailing photo-caption appendix, actual reproduced North Korean
orthography (로동자 vs. standard 노동자) and socialist-register address terms (동무). See the
supplementary table above.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`.
