# Korean — Established Vocabulary/Grammar: Continuing Korean, Lessons 22-27

**Source:** Ross King & Jae-Hoon Yeon, *Continuing Korean* (Tuttle Publishing), PDF pages 151-300
of 451 (of `source_reference/languages/Korean/07.Continuing Korean.pdf`). This range covers the
back half of Lesson Twenty-two (vocabulary + grammar notes 22.1-22.8, picking up mid-vocabulary-list
where a sibling chunk covering PDF pages 1-150 leaves off), all of Lesson Twenty-three (23.1-23.9),
all of Lesson Twenty-four (24.1-24.9), Lesson Twenty-five ("Review 4," a pure pattern-review lesson
with no new grammar), all of Lesson Twenty-six (26.1-26.8: the Plain Style, Intimate Style, and
adjunctive -느라(고)), and all of Lesson Twenty-seven (27.1-27.9: direct/indirect quotation and the
particle 으로's further meanings), through the end of Lesson 27's exercises at PDF page 300.

**Boundary verification:** Direct inspection (`pdftotext -layout` page-by-page) confirmed PDF page 150
ends mid-entry inside Lesson 22's "Verbs That Take Objects" vocabulary list (cutting off after
사진(을) 찍- "take photos"), and PDF page 151 resumes with 삶- "boil it" continuing the same list.
This chunk begins there.

**Coverage note — OCR quality warning (important).** This PDF has a genuine text layer
(`pdftotext` produces real text, no vision-reading was needed), but the underlying ABBYY
FineReader OCR is **badly corrupted for a large fraction of Hangul**, especially in vocabulary
boxes: jamo are frequently split apart, swapped for Latin lookalikes, or reordered within a line
(e.g. 것가락 for 젓가락, 것 대- for 뭐라- fragments, A20- for 삶-, whole vocabulary blocks reduced to
glyph soup such as the "Things"/body-vocabulary set opening Lesson 27's vocabulary section). This
is functionally the same risk the spec's vision-reading guard describes for scanned sources, just
from OCR corruption rather than a missing text layer. Per entry below:
- Where the Korean spelling is legible and unambiguous from the raw extraction, it is given
  normally with no confidence flag (**Transcription Confidence**/**Vision Reading Confidence** are
  both `n/a`, per the spec's rule that these columns are for corpus/vision-read sources, not
  reference-book text-layer extraction).
- Where the Korean spelling had to be reconstructed from severely garbled OCR by cross-referencing
  the (clearly legible) English gloss against common Korean vocabulary, this is flagged explicitly
  in the entry's Notes with **"OCR severely corrupted; Korean reconstructed from gloss, not
  directly read."** Treat these as `low_confidence` in spirit even though the column is `n/a` on a
  technicality (real text layer existed, it was simply wrong).
- A handful of entries in Lesson 27's "Things"/body-related vocabulary box were too corrupted to
  reconstruct with any confidence and are omitted rather than guessed (the box's English glosses
  alone — e.g. "regular customer," "president (of country)," "fool; idiot; dummy," "cheek(s)," "flesh,"
  "get fat, gain weight," "lose weight," "skin," "scholar" — are recoverable and are given below with
  their most likely Korean forms flagged low-confidence; where even a plausible Korean form could not
  be reconstructed, the row is omitted per the spec's "default to the riskier assumption when
  uncertain" principle).

**Lesson 25 ("Review 4") is intentionally near-empty below.** It is a pure pattern-review lesson
consisting of a vocabulary drill (antonym-pairing exercise, no new vocabulary) and a numbered
recap (25.1.1-25.1.27) of grammar points already taught in Lessons 22-24 (this chunk) or in
earlier lessons outside this chunk's range, illustrated with new example sentences but no new
rules. Per the coverage rule ("skip repeated drill exercises... that don't introduce new
vocabulary or grammar beyond what's already been captured from this same chunk"), Lesson 25 is
summarized rather than re-extracted.

**Register/speech-level note (flagged per dispatch instructions):** Lesson 26 is this chunk's
single richest source of honorific/speech-level material — it introduces the **Plain Style**
(반말의 문어체 statement/question/command/suggestion endings, used in writing, between intimates,
or from a social superior to an inferior) and the **Intimate Style** (반말, formed by stripping the
polite 요 particle from Polite Style forms) as named, systematic register categories alongside the
Polite and Formal/honorific styles already established earlier in the book. This is exactly the
kind of explicit register annotation the coverage rule prioritizes, and is captured in full in the
Grammar Points section below.

See `../../00_Reference_Extraction_Spec.md` for the full coverage rule and column rules, and
`../../00_Word_Concept_and_Morphological_Typology_Guide.md` for the morpheme-breakdown convention
used below (Korean is agglutinative).

---

## Vocabulary

### Lesson 22 (continued) — Verbs, adjectives, color terms (p. 151-153)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 삶- | boil it | verb (transitive) | core | — | contemporary (source published, Tuttle ed.) | — | — | grammar_reference | n/a | n/a | Continues from p. 150's cut-off list. 계란을 삶- "boil an egg," 감자를 삶- "boil potatoes." |
| 삼키- | swallow it | verb (transitive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 생각(을) 하- | think | verb (transitive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 씹- | chew it | verb (transitive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 껌(을) 씹- "chew gum." |
| 염려(를) 하- | worry | verb (transitive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 염려 마십시오 "Don't worry." |
| 찌- | steam it | verb (transitive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 찐 만두 "steamed dumplings." |
| 출근(을) 하- | go/come to work; report for work | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 출근시간 "the time when one leaves home for work." |
| 켜- | turn on, switch on (a light) | verb (transitive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 퇴근(을) 하- | go/come home from work; leave the office | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 출퇴근(을) 하- "commute to work"; 퇴근시간 "the time when one gets off work." |
| 튀기- | deep-fry it | verb (transitive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 그저 그렇- | be so-so | descriptive verb (ㅎ-irregular) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 그저 그랬어요 "It was so-so." |
| 날씬하- | be thin, slim | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 넓- | be wide, broad; spacious | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 독하- | be strong (of drinks, e.g. coffee, alcohol) | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 딴- | be different | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 딴 것 "something different"; 딴 세상에 온 것 같아요 "I feel like I'm in a different world." |
| 맑- | be clear | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 맑은 공기, 물, 날씨, 소리, 정신 "clean air, clear water, weather, sound, spirits." |
| 매콤하- | be somewhat spicy-tasting | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 못 되- | be bad, bad-natured, evil, wicked, good-for-nothing | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 못 된 사람 "a bad person"; 그 사람은 못 됐어요 "He's a bad guy." |
| 못 쓰- | be no-good, worthless (lit. "be useless") | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 반가워- | be pleased to see/hear someone/something | descriptive verb (ㅂ-irregular) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | OCR rendered as "반가 W-"; reconstructed with high confidence (common vocabulary item). |
| 부지런하- | be diligent | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 속(이) 나쁘- | have a sore stomach, feel sick in the stomach | descriptive verb phrase | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 싱거워- | be bland, not salted enough | descriptive verb (ㅂ-irregular) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 진하- | be thick (of liquid or makeup) | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 커피가 너무 진해요 "The coffee is too strong." |
| 짜- | be (too) salty | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 넘어지- | fall down | verb (intransitive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 놀러 가- | go on an outing, excursion or picnic; go to visit | verb phrase | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 밀리- | be backed up, congested (cars, traffic) | verb (intransitive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 차가 많이 밀리네요 "My, traffic is quite backed up." |
| 불(이) 나- | a fire breaks out | verb phrase | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 서두르- | hurry, hasten, make haste | verb (intransitive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 큰일(이) 나- | something serious happens; get in big trouble | verb phrase | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 큰일 났군요! 어떡하지요? "Now we're in big trouble! What should we do?" — illustrative of the -군요 sudden-realization ending. |
| 혼(이) 나- | have a hard time of it, have an awful experience | verb phrase | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Contrast with 혼(을) 내- "give a person a hard time" (causative counterpart, Lesson 23 vocab below). |
| 까맣- / 까매요 | be black, dark | descriptive verb (ㅎ-dropping, color) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 새까맣- "be jet-black." See ㅎ-dropping paradigm in Grammar points (22.4). |
| 노랗- / 노래요 | be yellow | descriptive verb (ㅎ-dropping, color) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 새노랗- "be vivid yellow." |
| 빨갛- / 빨개요 | be red | descriptive verb (ㅎ-dropping, color) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 새빨갛- "be bright red." |
| 파랗- / 파래요 | be blue | descriptive verb (ㅎ-dropping, color) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 새파랗- "be vivid deep blue." |
| 하얗- / 하얘요 | be white | descriptive verb (ㅎ-dropping, color) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 새하얗- "be bright white." |
| 이러-/이래요, 그러-/그래요, 저러-/저래요, 어떠-/어때요 | does it this/that/that(remote) way; does it how? | verb (processive, ㅎ-dropping manner set) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Full paradigm in Grammar points 22.4 (Abbreviated Verbs of Manner and Color); also has descriptive counterparts 이러(ㅎ)-, 그러(ㅎ)-, 저러(ㅎ)-, 어떠(ㅎ)- "is like this/that/how." |
| 이렇게 / 이리, 그렇게 / 그리, 저렇게 / 저리, 어떻게 | like this/way (manner) vs. this way (direction, hither) | adverb pair | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Two parallel adverb sets: -게 forms (manner) vs. -이 forms (direction, often + particle 로); diminutive variants 요러/고러/조러/요리/고리/조리 also noted. |

### Lesson 23 — Overseas Koreans, university life, health, cops-and-robbers (p. 173-181)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 교민 / 교포 | resident overseas Korean(s) | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 캐나다교포 "Korean Canadian." |
| 이민 | immigration | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 이민자 "immigrant"; 이민(을) 가- "emigrate"; 이민(을) 오- "immigrate." |
| 이세 | second generation | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 일점오세 | 1.5 generation | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Sociolinguistically loaded term (immigrants who arrive as children) — see Reading Passage note below; used self-referentially by the passage's narrator 수영이. |
| 재미 / 재미교포 | resident in the US / Korean American | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 재일 / 재일교포 | resident in Japan / Korean Japanese | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 등록 | registration | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 등록(을) 하- "register." |
| 문학 | literature | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 한국문학 "Korean literature"; 영문학/영문과 "English literature/department." |
| 사은회 파티 | party in honor of one's teacher | noun phrase | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Culturally specific (student-to-teacher gratitude event). |
| 성적 | marks, grades | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 성적표 "report card." |
| 종강 파티 | end-of-term party | noun phrase | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 주인공 | the star; the protagonist; person of honor at a party | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 코스 | course | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Loanword (English "course"). |
| 운동 선수 | athlete | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Compound family: 배구/농구/축구/미식축구/수구/아이스 하키 선수 (volleyball/basketball/soccer/American football/water polo/ice hockey player). |
| 수술 | an operation (medical) | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 수술실 "operating theatre"; 수술(을) 하- "perform/have an operation"; 수술(을) 받- "have an operation [as patient]." |
| 신경 | nerve, nerves | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 신경(을) 쓰- / 신경(이) 쓰이- "be nervous, worried." |
| 환자 | patient; a sick person | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 거실 | living room | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 계절 | season | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 사계절 "the four seasons"; 한국은 사계절이 분명해요 "The four seasons are clearly distinguished in Korea." |
| 국회의원 | National Assemblyman, M.P. | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 기사 (아저씨) | driver, chauffeur | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| -네 | -'s place (e.g. "Pete's place") | postnoun/suffix | core | — | contemporary | — | — | grammar_reference | n/a | n/a | See Grammar points 23.4.1 for the full plural/place-noun paradigm; this is the same 네 as in 진영이네, 철수네, 만호네. |
| 동양화 | Oriental painting | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 매월 | every month | noun/adverb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 벨소리 | "bell sound" = ringing | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 아무 NOUN(이)나 | any NOUN at all, any NOUN whatsoever | quantifier construction | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Negative-polarity counterpart: 아무 NOUN도 "no NOUN at all." |
| 영수증 | receipt | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 유전자 | gene | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Used in the Reading Passage's "한국말 유전자가 따로 없잖아요" (there's no separate 'Korean-language gene') — a notable rationalization line about heritage-language fluency not being innate. |
| 팩스 | fax | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 팩스번호 "fax number." Loanword. |
| 표현 | (verbal) expression | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 표현(을) 하- "express." |
| 회의 | conference | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 회의 중입니다 "She's in the middle of a conference." |
| 공평하- / 불공평하- | be fair / be unfair | descriptive verb pair | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 나아- | be preferable, better (than = 보다) | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | OCR rendered "나(시-"; reconstructed as 낫- (ㅅ-irregular) via cross-reference with the same base's Lesson 22/26 forms (나아요/낫다). |
| 분명하- | be clear, obvious | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Adverb 분명히 "clearly, obviously" listed separately below. |
| 조촐하- | be small and neat | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 조촐한 파티 "a 'little party.'" |
| 창피하- | be/feel embarrassed | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 훌륭하- | be great, admirable | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 놀리- | make fun of, tease | verb (transitive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 더듬거리- | stutter or speak haltingly | verb (transitive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 그 사람은 말을 더듬거려요 "He speaks haltingly." |
| 데리- (데려가-/데려오-/데리고 오-/데리고 가-) | take/bring a person along | verb family | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Non-honorific counterpart to 모시- below. |
| 마음(을) 먹- | make up one's mind to, resolve to | verb phrase | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Used with -기로: 사장님께 여쭤보기로 마음을 먹었습니다 "I resolved to ask the boss." |
| 모시- [HUMBLE] | take/accompany a (person) along | verb (humble) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Honorific/humble counterpart to 데리-: 모셔가-/모셔오-/모시고 오-/모시고 가-. Explicit honorific register marking. |
| 잘못 걸- | dials a wrong number | verb phrase | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 잘못 거셨는데요 "I'm afraid you have the wrong number." |
| 포기(를) 하- | give up, give up on | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 혼(을) 내- | give a person a hard time; scold | verb phrase (causative) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Causative counterpart of 혼(이) 나- (Lesson 22 above) — a notable descriptive/causative pair. |
| 나오- | [a subject] comes up | verb (intransitive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 말이 나온 김에... "Seeing as the subject has come up..." — ties to grammar point 22.7. |
| 들리- | stops by, drops in (= 들르-) | verb (intransitive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 실망(을) 하- | be disappointed | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 여쭈- / 여쭤 보- | asks sb esteemed | verb (humble) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Humble/honorific-register verb, used toward a socially superior addressee. |
| 기꺼이 | with pleasure | adverb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 당연히 | naturally, as a matter of course | adverb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Descriptive-verb counterpart 당연하- "stand to reason, be natural." |
| 말하자면 | as it were; so to speak | adverb/discourse marker | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 분명히 | clearly, obviously | adverb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |

### Lesson 24 — International exchange, church, cops-and-robbers, studying (p. 202-217)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 교류 / 국제교류 | interchange / international exchange | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 발전 | development | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 경제발전 "economic development"; 발전(을) 하-/시키- "develops (intr.)/develop it (caus.)" — descriptive-causative-style intransitive/transitive pair. |
| 방문 | a visit | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 방문학자 "visiting scholar." |
| 여권 | passport | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 외무부 | Ministry of Foreign Affairs | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 유학 | study abroad | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 유학(을) 시키- "send somebody to study abroad" (causative); 유학생 "international student." |
| 주- | residing in, resident (in) | prefix | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 주한 미국 대사관 "US embassy in Korea"; 주미 대한민국 대사관 "ROK embassy in the US." |
| 한미간(의) | Korea-US, between Korea and the US | noun/modifier | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Sino-Korean compound abbreviating 한국+미국; 한미간의 문화 교류 "cultural exchange between Korea and the US." |
| 권사 | (church) Elder [female] | noun | technical.religious | — | contemporary | — | — | grammar_reference | n/a | n/a | Explicit church-register vocabulary set — gendered elder titles. |
| 기도 | prayer | noun | technical.religious | — | contemporary | — | — | grammar_reference | n/a | n/a | 기도(를) 하- "pray." |
| 반주 | accompaniment (musical) | noun | technical.religious | — | contemporary | — | — | grammar_reference | n/a | n/a | 반주자 "accompanist"; 반주(를) 하- "accompany musically." |
| 설교 | sermon | noun | technical.religious | — | contemporary | — | — | grammar_reference | n/a | n/a | 설교(를) 하- "give a sermon." |
| 성가대 | (church) choir | noun | technical.religious | — | contemporary | — | — | grammar_reference | n/a | n/a | 성가대원 "choir member." |
| 성경 / 성서 | Bible | noun | technical.religious | — | contemporary | — | — | grammar_reference | n/a | n/a | 성경 공부 "Bible Study." |
| 예배 | church service | noun | technical.religious | — | contemporary | — | — | grammar_reference | n/a | n/a | 예배(를) 드리- "attend a service; worship." |
| 장로 | (church) Elder [male] | noun | technical.religious | — | contemporary | — | — | grammar_reference | n/a | n/a | Paired with 권사 (female Elder) above — an explicit gendered honorific title pair. |
| 지휘자 | conductor, director (of a musical group) | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 집사 | (church) deacon | noun | technical.religious | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 경찰 / 경찰서 | policeman / police station | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 도둑놈 | thief, burglar [usually abusive] "S.O.B." | noun | taboo | — | contemporary | — | — | grammar_reference | n/a | n/a | Explicitly flagged by the source as usually abusive/insulting — cf. 나쁜 놈, 고약한 놈 "S.O.B." (below). |
| 나쁜 놈 / 고약한 놈 | S.O.B. [term of abuse] | noun phrase | taboo | — | contemporary | — | — | grammar_reference | n/a | n/a | The productive 놈 "guy/fellow" (derogatory male classifier) + adjective pattern — a real morphological-play-adjacent slot for abuse terms. |
| 도둑 | thief, burglar | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 도둑(을) 맞- "be burgled, robbed." |
| 과학 | science | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 복습 | review, revision | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 복습(을) 하- "review, revise." |
| 수학 | mathematics, math | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 시간표 | timetable, schedule | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 역사 | history | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 예습 | preparation (of lessons), preview | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 예습(을) 하- "prepare/preview lessons." Antonym pair with 복습 above. |
| 장학금 | scholarship | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 전문 / 전문가 / 전문지식 | specialty / specialist / specialized knowledge | noun family | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 계획 | plan | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Used in prospective-modifier + 계획이다 pattern (grammar 24.8). |
| 그릇 | bowl, dish, vessel, plate | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 노력 | efforts, hard work | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 노력(을) 하- "makes efforts." |
| 눈물 | tears | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 눈물(을) 흘리- "cry, shed tears." |
| 다행 | luck, fortunate | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 다행이네요 "How fortunate!"; 다행히(도) "fortunately." |
| 바닷가 | the seashore, seaside; beach | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 바둑 | game of Go (paduk) | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 바둑(을) 두- "play paduk." Culturally specific board game. |
| 볼륨 | volume | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Loanword. |
| 봉급 | salary, wages | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 불행 | unhappiness, misfortune | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 불행하- "be unfortunate"; 불행히(도)/불행하게(도) "unfortunately." Antonym of 다행 above. |
| 사랑 | love | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 사랑에 빠지- "fall in love"; 첫눈에 "at first sight." |
| 서기 | secretary, clerk | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 아무것도 | nothing at all | pronoun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Negative-polarity item, parallel to 아무 NOUN도 above. |
| 엉망 | a mess, a wreck | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 연봉 | annual salary | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 월급 | monthly salary | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 예정 | plan, prearrangement, schedule | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Used in prospective-modifier + 예정이다 pattern (24.8). |
| 온몸 | one's entire body | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 온 세상 "the whole world" (same 온- "whole" prefix). |
| 입맛 | one's appetite, one's desire to eat | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 입장 | position, standpoint, stand (on an issue) | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 자연 / 대자연 | nature / the Great Outdoors, Mother Nature | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 장기 | Korean chess (changgi) | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 장기(를) 두- "plays changgi." Culturally specific board game, cf. 바둑 above. |
| 전쟁 | war | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 제안 | a suggestion, proposal | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 중심 | center, core, crux | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 서울을 중심으로 "with Seoul as the center"; 중심적으로 "primarily." |
| 직책 | duties, responsibilities of office | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 코피 | nosebleed | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 코피(가) 나- "get a nosebleed." |
| 결국 | ultimately, as a result, in the end | adverb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 구체적으로 | concretely, specifically | adverb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Antonym pair with 소극적으로/적극적으로 below (abstract-vs-concrete, passive-vs-active register). |
| 끝으로 / 둘째로 / 첫째로 | finally / secondly / firstly | adverb (ordinal-discourse) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Discourse-organizing ordinal adverb set. |
| 밤늦도록 | until late in the night | adverb phrase | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 소극적으로 / 적극적으로 | passively / actively, positively | adverb pair | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 싹 | entirely, completely | adverb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 싹 없어졌어요 "It disappeared entirely." |
| 우선 | first, firstly; as a matter of priority | adverb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 우연히 | by chance, by coincidence | adverb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 길을 가다가 수미 씨를 우연히 만났어요 "I was walking down the street and happened to meet Sumi" — illustrates transferentive -다가 from 22.5. |
| 가지- | possess, hold, take | verb (transitive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 가져가-/가져오-, 갖고 있-, 가지고 가-/오-. |
| 거절(을) 하- | refuse somebody/something | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 고치- | fix it, repair it | verb (transitive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 사귀- | make friends with, get to know | verb (transitive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 나쁜 사람들과 사귀어요 "Keeps company with bad sorts" — notable slightly-negative collocation. |
| 선택(을) 하- / 택하- | select, choose | verb pair (Sino-Korean/native-feeling doublet) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 수입(을) 하- / 수출(을) 하- | import / export | verb pair | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 알리- | let somebody know; inform | verb (transitive, causative-flavored) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 잃어버리- | lose something | verb (transitive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 조심하- | be careful about | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 말씀을 조심하세요 "Be careful what you say." |
| 촉진(을) 시키- / 추진(을) 하-/시키- | expedite, promote, facilitate / promote, propel forward | verb pair | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Both use the -시키- causativizing pattern discussed in grammar 24.5's closing note. |
| 취소(를) 하- | cancel it | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 취소(가) 되- "it gets cancelled" (intransitive counterpart). |
| 훔치- | steal it, swipe it | verb (transitive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 흘리- | spill it; shed (tears) | verb (transitive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 커피를 흘렸어요 "I spilled my coffee." |
| 고약하- | be ugly, wicked, nasty, hard to deal with | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 고약한 냄새 "a horrible smell." |
| 어두워- | be dark | descriptive verb (ㅂ-irregular) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 그치- | [rain/snow] stops | verb (intransitive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 기침(을) 하- | cough | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 냄새(가) 나- | it smells | verb phrase | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 맛있는 냄새가 나네요 "Something smells good!" |
| 놀라- | be surprised | verb (intransitive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 깜짝 놀랐지요 "I was so surprised!" |
| 못 생겼- | ugly ("didn't turn out") | descriptive/past-form idiom | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Notable: an inherently-past form (past of 생기- "come about, turn out") functioning as a lexicalized descriptive meaning "ugly" — a fossilized-morphology case worth flagging for mechanics analysis. |
| 배(가) 나오- | get a big belly | verb phrase | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 배탈(이) 나- | get an upset stomach | verb phrase | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 사고(가) 나- | an accident happens/occurs | verb phrase | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 상하- | [food/mood] spoils, goes off, goes bad | verb (intransitive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 친구가 약속을 어겨서 기분이 상했어요 "I've lost my good mood because my friend didn't keep our appointment." |
| 샤워(를) 하- | take a shower | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Loanword base ("shower"). |
| 일어서- | stand up | verb (intransitive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 입원(을) 하- / 퇴원(을) 하- | be/get hospitalized / be discharged from hospital | verb pair | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Antonym pair. |
| 자라- | it grows | verb (intransitive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 지난번보다 많이 자랐네요 "She's grown a lot since last time!" |
| 출발(을) 하- | set off, depart | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 출장(을) 가- | go away on business | verb phrase | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 터지- | it bursts | verb (intransitive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 전쟁이 터졌어요 "War broke out"; 배가 터질 것 같아요 "I think my stomach will burst" — figurative and literal senses both attested. |

### Lesson 26 — Verbs of looking, health/hospital vocabulary, weather, people (p. 240-...)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 구하- | look for [work/a job]; buy, get, obtain | verb (transitive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 그 책은 구하기 힘들어요 "That book is hard to come by." |
| 끌- | drag; pull, draw | verb (transitive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 내다보- | look out (at) | verb (transitive, compound) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Compound built on the -어다 pattern (grammar 26.8.1) — 내(다)+보-. |
| 내려다보- | look down at/upon | verb (transitive, compound) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 들여다보- | look in (through), peep in (through) | verb (transitive, compound) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | OCR rendered "드려다 보-"; reconstructed via cross-reference with the identical compound in grammar point 26.8.1's example list ("들여다 봐요/드려다 봐요" — the source itself is inconsistent, alternating 드려다/들여다 spellings). |
| 비키- | get out of the way | verb (intransitive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 길을 비켜 주세요 "Please clear the way." |
| 쳐다보- | look up at; stare at | verb (transitive, compound) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 추방(을) 하- | expel, drive out, banish | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Used in the Plain Style example "미군을 추방하라!" (protest-poster register, grammar 26.4.1). |
| 토하- | vomit, throw up | verb (transitive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Ties to the Reading Passage's illness narrative. |
| 급하- / 급히 | be urgent / hastily, in a rush | descriptive verb + adverb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 기운(이) 없- | have no energy | descriptive verb phrase | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 달- | be sweet | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Part of the taste-adjective set with 시-/쓰- below. |
| 시- | be sour | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 쓰- | be bitter | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Homophonous with 쓰- "write"/"use" — a genuine homograph set, cf. 22.4's 이러-/이렇- pattern. |
| 착실하- | be steadfast, thorough | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 친절하- / 불친절하- | be kind / be unkind | descriptive verb pair | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 편리하- | be convenient | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 흔하- / 흔히 | be common / often, commonly | descriptive verb + adverb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 문병(을) 가-/하- | to visit (a sick person) | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 애(를) 쓰- | make efforts, try hard | verb phrase | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 애를 썼어 "Well done" (idiomatic, Intimate Style — illustrates register point from 26.6). |
| 회복(을) 하- / 회복(이) 되- | recover (from illness) | verb pair (transitive/intransitive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 간호사 | nurse | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Reading Passage uses the older/alternate form 간호원. |
| 검사 / 피검사 | inspection, test / blood test | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 독감 | flu | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 맥박 | pulse | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 맥(을) 짚- / 맥박(을) 재- "take someone's pulse." |
| 변비 | constipation | noun | technical.medical | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 소화 | digestion | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 소화(가) 안 되- "has indigestion"; 소화제 "digestive tablet(s)." |
| 열 | a fever (high temperature) | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 열(이) 있- "have a fever"; 열(이) 높- "run a high fever." |
| 응급치료 / 응급차 | first-aid treatment / ambulance | noun | technical.medical | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 의과 대학 | medical school | noun | technical.medical | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 인턴 | intern | noun | technical.medical | — | contemporary | — | — | grammar_reference | n/a | n/a | Loanword. |
| 전염병 | contagious disease/illness | noun | technical.medical | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 주사 | a shot, an injection | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 주사(를) 맞- "get a shot" (patient's perspective) vs. 주사(를) 놓- "give a shot" (giver's perspective) — a notable perspective-marking verb pair. |
| 진단 | diagnosis | noun | technical.medical | — | contemporary | — | — | grammar_reference | n/a | n/a | Used in the Reading Passage's plot turn: 진단이 '독감'이었다 "the diagnosis was 'flu'." |
| 진찰 | a check-up, medical examination | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 진찰(을) 받- "have a check-up"; 진찰실 "consultation room." |
| 체온 | body temperature | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 체온(을) 재- "take someone's temperature." |
| 치료 | medical treatment | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 치료(를) 받- "receive/undergo medical treatment." |
| 피 | blood | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 혈압 | blood pressure | noun | technical.medical | — | contemporary | — | — | grammar_reference | n/a | n/a | 혈압(을) 재- "take somebody's blood pressure." |
| 내과 / 산부인과 / 소아과 / 외과 / 이비인후과 / 치과 | internal medicine / OB-GYN / pediatrics / surgery / ENT / dentistry | noun (medical specialties) | technical.medical | — | contemporary | — | — | grammar_reference | n/a | n/a | Full closed set of Sino-Korean "-과" medical department names; 외과의사 "surgeon," 치과 의사 "dentist." |
| 예보 / 일기예보 | forecast / weather forecast | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 온도 / 섭씨 / 화씨 | temperature / Celsius / Fahrenheit | noun | technical | — | contemporary | — | — | grammar_reference | n/a | n/a | -도 "degrees" (with Sino-Korean numbers) is the shared counter. |
| 일기 | the weather | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 가정의 | family doctor | noun | technical.medical | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 개인 / 개인적으로 | individual person / personally | noun/adverb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 독신 / 독신자 | (still) unmarried person / unmarried person (by choice), bachelor | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 저 사람은 아직 독신이에요 "He's still single." |
| 말썽꾸러기 / 장난꾸러기 | troublemaker (child), rascal / mischief-maker, little monkey (child) | noun | colloquial | — | contemporary | — | — | grammar_reference | n/a | n/a | The productive -꾸러기 "person characterized by X" derivational suffix — a real morphological slot worth flagging for slang-formation analysis. |
| 총각 | unmarried young man | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 파출부 | maid | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 가루 | powder | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 고추가루/후추가루 "red/black pepper powder." |
| 거리 / 장거리 / 단거리 | distance / long-distance / short-distance | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 교통사고 | traffic accident | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 문장 | sentence | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 미군 / 미8군 | American army / US Eighth Army | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Historically loaded reference (US Forces Korea). |
| 방해 | a disturbance, obstruction | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 방해(가) 되- "get in the way"; 방해(를) 하- "disturb someone." |
| 시장 | mayor | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | (Homograph of 시장 "market" seen elsewhere in the book — not flagged in-source but worth noting.) |
| 시합 | a match, contest, game (sport) | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 용돈 | pocket money | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Used in the -느라(고) dialogue example about a son spending his pocket money on drinking (grammar 26.7). |
| 인형 | doll | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 줄 | line (of text); line (queue) | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 줄(을) 서- "stand in line." |
| 지갑 | wallet; purse | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 지도 | map | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 허락 | permission | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 허락(을) 받-/하- "get/give permission." |
| 현관 | entrance vestibule | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 미리 | in advance, ahead of time | adverb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 푹 | (sleep) deeply; (rest) soundly | adverb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | OCR rendered as an isolated "ᄑ" glyph; reconstructed from context (paired with "(sleep) deeply; (rest) soundly" gloss, a well-known collocational adverb) — flagged low-confidence per the OCR-corruption note above. |

### Lesson 27 — Quotation-lesson vocabulary: things, words/texts, verbs (p. 271-274)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 단골 / 단골손님 | regular (customer/place) / regular customer | noun | colloquial | — | contemporary | — | — | grammar_reference | n/a | n/a | **OCR severely corrupted; Korean reconstructed from gloss, not directly read.** Confirmed independently by its reappearance, legibly, in Lesson 27's Grammar points (단골손님 "regular customer," 27.1.1 example 5; 단골집 in the Exercise 1 quotation drill). |
| 대통령 | president (of country) | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | **OCR severely corrupted; Korean reconstructed from gloss, not directly read.** Cross-confirmed by its legible appearance in the Exercise 1 drill sentence 13 ("대통령을 모시러 갑니다"). |
| 바보 | fool; idiot; dummy | noun | colloquial | — | contemporary | — | — | grammar_reference | n/a | n/a | **OCR severely corrupted; Korean reconstructed from gloss + common-vocabulary inference, not directly read** — treat as low-confidence. |
| 뺨 | cheek(s) | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | **OCR severely corrupted; Korean reconstructed from gloss, not directly read** — treat as low-confidence. Cross-referenced against 얼굴(을) 붉히- "turn red in the face" elsewhere on the same page, a semantically adjacent term. |
| 살 | flesh | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | **OCR severely corrupted; Korean reconstructed from gloss, not directly read** — treat as low-confidence. |
| 살(이) 찌- | get fat, gain weight | verb phrase | colloquial | — | contemporary | — | — | grammar_reference | n/a | n/a | **OCR severely corrupted; Korean reconstructed from gloss, not directly read** — treat as low-confidence. |
| 살(이) 빠지- | lose weight | verb phrase | colloquial | — | contemporary | — | — | grammar_reference | n/a | n/a | **OCR severely corrupted; Korean reconstructed from gloss, not directly read** — treat as low-confidence. |
| 피부 | skin | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | **OCR severely corrupted; Korean reconstructed from gloss, not directly read** — treat as low-confidence. |
| 학자 | scholar | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | **OCR severely corrupted; Korean reconstructed from gloss, not directly read** — cross-confirmed legibly elsewhere in this same lesson's Grammar points 27.7/27.9 ("유명한 학자," "루시디라는 유명한 작가"). |
| 돌 | stone, rock | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 벌레 | bug, insect | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 바퀴벌레 "cockroach"; 공부벌레 "nerd, someone who does nothing but study" — a notable productive "-벌레" (bug/worm) derogatory-affectionate agentive suffix. |
| 벽 | wall | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 불꽃놀이 | fireworks | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 산꼭대기 | mountain top, peak | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 천장 | ceiling | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 논문 | (academic) paper; thesis | noun | technical.academic | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 뜻 | meaning | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 무슨 뜻이에요? "What does it mean?" |
| 명령 | order, command | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 명령(을) 하- "order, command" — ties directly to the quoted-command grammar in 27.4. |
| 발표 | announcement; public presentation | noun | technical.academic | — | contemporary | — | — | grammar_reference | n/a | n/a | 발표(를) 하- "announce; present (a paper)." |
| 선언 | pronouncement, declaration | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 선언(을) 하- "pronounce, declare"; used in Exercise 1's "파산을 선언했어요" "declared bankruptcy." |
| 추측 | conjecture, guess, inference | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 추측(을) 하- "surmise, guess, infer." |
| NOUN 건너(에) | across from NOUN | postposition phrase | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 소리 / 목소리 | noise, sound / voice | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 소리(를) 지르- "shout, cry out." |
| 소위 NOUN | a so-called NOUN | modifier | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 약간 | some, a little, a few; somewhat | adverb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 자기 | I (myself); he/she (himself/herself) | pronoun (reflexive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Rich set of examples: 자기 일은 자기가 해야 한다 "People should take care of their own problems"; used self-referentially in quoted-speech contexts (그가 자기가 하겠다고 말했다). |
| 장소 | place, venue | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 정부 | government | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 제목 | title (of book/work) | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 직장 | job, work, workplace | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 직장(을) 구하- "look for work." |
| 해결 | solution (to a problem) | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 해결(을) 하- "resolve a problem"; 해결(이) 되- "be/get resolved." |
| 행사 | happening, formal event, function | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 새로 | newly, anew | adverb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 새로 지은 집 "a newly built house." |
| 원래 | originally; actually | adverb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Used in Grammar 27's example about a "campus couple" (캠퍼스 커플) — a loanword-based slang-adjacent term worth flagging even though not glossed as slang tier by the source itself. |
| 그러- | say (so); think (so) | verb (transitive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 그 사람이 뭐라고 그랬어요? "What did she say?" — central quoting-verb of Lesson 27's whole topic. |
| 기르- | breed, raise, grow | verb (transitive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 끊- | break it off; hang up (the telephone) | verb (transitive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 떨어지- | fall; run out of something | verb (intransitive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 설탕이 떨어졌네 "We're all out of sugar." |
| 믿- | believe (also religious sense) | verb (transitive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Explicitly classed by the source as a "verb of quoting" alongside 생각하- and 여기- (grammar 27.1.1 note) — belief/thought verbs pattern like speech verbs for quotation purposes. |
| 여기- | consider | verb (transitive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | See note on 믿- above — also a "verb of quoting." |
| 우물쭈물하- | waffle, prevaricate, beat around the bush | verb (mimetic-derived) | colloquial | — | contemporary | — | — | grammar_reference | n/a | n/a | Reduplicative-mimetic-derived verb — morphologically notable (우물쭈물, an ideophone, + 하-). |
| 제출(을) 하- | turn in, submit, hand in | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 조르- | pester for, keep after for | verb (transitive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Used with quoted-command pattern: 사탕을 사 달라고 졸라요 "pesters [him] to buy candy" — direct tie-in to grammar 27.8. |
| 차리- | prepare, make ready; collect, concentrate | verb (transitive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 음식(을) 차리- "prepare food"; 정신(을) 차리- "collect one's senses." |
| 축하(를) 하- | congratulate | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 축하합니다/축하 드립니다 "Congratulations" — the latter is the honorific-register variant. |
| 밝- / 밝히- | be bright, clear / make bright or clear | descriptive-causative pair | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Explicitly labeled by the source as a "Descriptive-Causative Pair"; 밝히- also used metaphorically for "explain, state clearly" (대통령이... 밝혔습니다 "the president stated..."). |
| 붉- / 붉히- | be red; crimson / make it red, redden it | descriptive-causative pair | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 얼굴(을) 붉히- "turn red in the face" (blush, from embarrassment/anger). |
| 몸조리(를) 하- | take care of one's health; recuperate | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 장가(를) 가- / 시집(을) 가- | get married [of a man] / get married [of a woman] | verb pair (gendered) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Explicitly gender-differentiated marriage verbs — 장가(를) 보내-/시집(을) 보내- are the causative "marry off" counterparts. Worth flagging for register/social-structure analysis. |
| 오래 가- | go/last a long time | verb phrase | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| -(으)로 변하- | change; turn/metamorphose into | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Illustrated by Grammar 27.9's memorable example "큰 바퀴벌레로 변했어요" (turned into a giant cockroach — a Kafka reference). |
| 파산(이) 되- | go bankrupt | verb phrase | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 화(가) 나- / 화(를) 내- | get angry [experiencer/spontaneous] / get angry [agentive] | verb pair (intransitive/transitive-flavored) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Both take 한테 for the target of anger; a classic Korean "experiencer vs. agentive" emotion-verb pair. |
| 점잖- | be well-behaved, decent, respectable | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| 얌전하- | be of good upbringing; be well-behaved and quiet | descriptive verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |

---

## Grammar points

### 22.1. Expressing "while" with -(으)면서(도) (p. 151-152)

A processive-verb ending meaning *while VERBing*, subject to two hard constraints: the action in
the following clause must happen (1) at the same time and (2) performed by the same
subject/topic as the -(으)면서 clause — this is what distinguishes it from -어도 ("even
though"), which allows different subjects across the two clauses. Adding the particle 도 gives
*though/even while*, sometimes shading into a genuine "even" meaning of admiration/emphasis (e.g.
a mother who works and *even while working* looks after the baby).

Morpheme breakdown: 먹으면서 = 먹- (eat, verb root) + -으면서 (simultaneous "while," consonant-base
allomorph); 돈이 없으면서도 = 없- (lack, be absent) + -으면서 (while) + 도 (even/though particle).

### 22.2. Contrasted topics with -(이)면 (p. 152-153)

The conditional copula (-이면 "if it be [noun]") after a noun functions as a substitute for the
topic particle 은/는 specifically in its *contrastive* use: "if X, then A; if Y, then B" — e.g.
낮이면 더워지고 밤이면 추워져요 "It warms up in the daytime and cools off at night" (literally "if
[it be] daytime... if [it be] night...").

### 22.3. Mild exclamations in -네요 (p. 153-154)

A one-shape ending attachable to both processive and descriptive verbs across plain/past/future
bases, making a mild exclamation ("Gee...!", "My...!"). Functionally a talking-to-oneself
register — inappropriate as a direct reply to a question, but used so that a listener notices
one's surprise. L-extending bases drop the ᄅ before this ending.

### 22.4. Abbreviated verbs of manner and color; the ㅎ-dropping class (p. 154-157)

Introduces the paired place-word/manner-verb system: 이/여기, 그/거기, 저/저기, 어느/어디
("this/here," "that(near)/there," "that(remote)/over there," "which/where") each have a
corresponding manner-verb pair — a **processive** verb (이러-/이래요 "does it this way," with an
irregular 하-like infinitive) and a **descriptive** verb of the same shape belonging to the
**ㅎ-dropping** class (이러(ㅎ)-/이래요 "is like this"). ㅎ-dropping bases (also including the
color adjectives 까맣-, 노랗-, 빨갛-, 파랗-, 하얗-) behave irregularly: before endings beginning
with -(으)ㄴ/-(으)ㅁ/-(으)ㅅ/-(으)ㄹ, the (으) is ignored and the ㅎ drops, treating the base as a
vowel base (까맣- + -(으)ㄴ → 까만); before all other endings, they behave as regular consonant
bases (까맣- + -지만 → 까맣지만). Two parallel adverb sets exist: -게 forms (이렇게, manner) and
-이 forms (이리, direction, often + particle 로); the latter have diminutive "light-vowel"
variants (요러, 고러, 조러, 요리, 고리, 조리) especially common in directional use.

### 22.5. Verbs: transferentive -다(가) (p. 157-160)

The ending -다(가) marks a shift or transfer — of the action itself, its direction, or the
recipient of its benefit. On a plain base: "when X happens, [it shifts/is interrupted by
something else]" (e.g. 뛰어가다가 넘어졌어요 "He was running and then fell down"). On a past base
(-었다가): "when X had happened, then [something contradictory/unanticipated followed]" (e.g.
샀다가 팔았습니다 "bought it but then sold it"). Doubled with contrasting forms (present or past)
rounded off by 해요 or 그래요, it expresses repeated back-and-forth action: 왔다 갔다 하세요 "keeps
coming and going." Distinguish the past-tense transferentive 갔다(가) "went, and then..." from the
superficially similar abbreviation 갖다(가) (← 가져다가) "carry/bring and then (shift)" — 갖다
주십시오 "please bring it to me." The transferentive of 있- ("stays and then") has a specialized
meaning "in a little while/later," often respelled 이따(가). The suspective -지 + auxiliary 말-
"desist" combines with transferentive doubling for patterns like 오다 말다 하네요 "it's raining off
and on."

Morpheme breakdown: 갔다가 = 가- (go) + -았- (past) + -다가 (transferentive, "and then shifts");
갔다 왔어요 = 가- + -았- + -다(가) + 오- (come) + -았어요 (past polite) = "went and then came back."

### 22.6. More on the auxiliary verb 말- (p. 160-163)

**22.6.1** Review: suspective -지 + 말아요 makes negative commands/suggestions ("avoid, refrain,
desist from doing"), limited to commands/suggestions (염려 마세요 "Don't worry," dropping 하지
after a verbal noun). **22.6.2** 말고 can function as a *pseudo-particle* directly after a noun (or
noun + particle), meaning "not being..." — without requiring a command/suggestion at the sentence
end (e.g. 차 말고 다른 거 안 마실래요? "Instead of tea, wouldn't you rather drink something else?").
Contrast statement/question -지 않고 ("without/instead of VERBing") with command/suggestion -지
말고 ("don't VERB, [instead]...").

### 22.7. "As long as you're at it..." with -(으)ㄹ/-는 김에 (p. 163-164)

A processive verb's past modifier (-(으)ㄴ) or processive modifier (-는) + 김에 means "incidental
to VERBing, seeing as one is/has VERBed anyway..." Often preceded by 이왕 "anyway, anyhow" for
emphasis (이왕 쓰시는 김에 주소도 써 주세요 "As long as you're at it [writing], write your address
too").

### 22.8. Modifiers with 것 같아요: "seems..." (p. 164-166)

A modifier (processive for in-progress action, or past/future) + 것 같아요 ("is like the fact
of...") means "seems/looks as if." Notably, the source flags that this pattern has become
"extremely popular, especially with younger speakers" and is now often used even with no genuine
uncertainty (e.g. 감기에 걸린 것 같아요 "I seem to have caught a cold," said while visibly coughing,
where a plain 감기에 걸렸어요 would be equally true) — an explicitly marked generational/register
shift worth flagging for slang-mechanics analysis: a hedging construction becoming a default,
non-hedging politeness/softening strategy among younger speakers. 같아요 is sometimes pronounced
같애요.

### 23.1. Imminent Elaboration with circumstantial -는데(요)/-(으)ㄴ데(요) (p. 181-185)

A new three-shape ending category (a modifier + a *restricted* postmodifier 데, usable only after
this modifier-shape and after -지, learned later) — descriptive bases use -(으)ㄴ데, all other
bases (processive, all pasts, all futures, plus 있-/없-) use -는데. Blanket meaning:
"circumstantial" — given the circumstance that... — most naturally rendered as "so," "but," or an
open-ended "...". Carries an **imminent elaboration** nuance: signals either "I may have more to
say" or "feel free to ask for elaboration." Rounded off with polite 요, this becomes a lively,
very common conversational pattern, including as a way to give a polite (often mildly
face-saving) reply to a misguided question, and as a form of polite exclamation ("이 방은 너무
작은데요!" "This room is too small!") — often accompanied by suspensive "..." intonation ("don't
jump in yet, I've still got the floor").

### 23.2. "In spite of...ing" with -는/-(으)ㄴ데도 (p. 185)

The circumstantial construction + 도 ("but"/"even though"). Can be seen as an abbreviation of
"...데도 불구하고" ("disregarding the circumstance that").

### 23.3. Other uses of 데 (p. 185-186)

데 also functions as a quasi-free noun (must be modified, cannot start a sentence) meaning
"place/spot" or "circumstance, occasion" (다른 데 "somewhere else"; 아무 데나 "any place at all").
Distinguish 본 데 "the place [I] saw" (regular modifier) from 봤는데 "given that [I] saw it, so..."
(restricted modifier) — 추운데 is genuinely ambiguous between "cold spot" and "given that it's
cold, so...", with a spacing convention (추운 데 vs. 추운데) sometimes disambiguating in writing.
Specialized lexicalized phrases: 표 파는 데 "ticket window," 옷 벗는 데 "(un)dressing room."

### 23.4. The postnoun -네 and diminutive -이 (p. 186-188)

**23.4.1** -네 makes an explicit plural for person-referring nouns (우리네, 저희네, 당신네, 너희네,
자기네 — can further combine with 들), and, after a personal name, means "and his/her
family"/"'s place" (철수네 집 "Ch'ŏlsu's place"). **23.4.2** The diminutive suffix -이 attaches to
personal names ending in a consonant to mark affection/endearment (수진이 "little Sujin") — but
sounds sarcastic/disparaging when attached to an adult's full name or given name alone (영삼이
"Yŏngsam [that weasel]"). When -네 attaches to a consonant-final name, it typically attaches to
the -이 diminutive form first (수진이네, not *수진네).

### 23.5.-23.6. Prospective modifier -(으)ㄹ and its clauses (p. 188-192)

The two-shape prospective modifier -을/ㄹ ("who/that is to [do/be]") is given a full paradigm
across consonant, vowel, and ㅎ-dropping bases. Phonological note: an initial ㅂ/ㄷ/ㅈ/ㄱ/ㅅ
consonant of a directly-following word is usually reinforced (doubled) in pronunciation but not
spelling (그 사람이 있을 곳 "the place he'll be," pronounced with tensed 곳); a following 이 or y-glide
causes the modifier's own ㄹ to double in pronunciation (할 일, pronounced 할릴). Prospective
modifier clauses pattern into four structural types depending on whether the modified noun is the
subject or object of the embedded clause (worked through with 가르칠 사람/내가 심을 꽃/꽃을 심을
사람/내가 공부를 할 학교 as the four paradigm cases).

### 23.7.-23.8. Plain/past base + -(으)ㄹ 때: "when..." (p. 192-196)

때 ("time") + a prospective modifier means "when" — notably, the modifier is *always*
prospective-shaped regardless of the corresponding English tense (there is no *-(으)ㄴ 때 form).
Past prospective modifiers of descriptive verbs/copula mark specifically past-and-now-over
conditions (어렸을 때 "when [she] was young [and isn't now]"); a past base can still appear with a
processive verb to emphasize pastness (한국에 갔을 때 "when [he] went to Korea"). Extended with 마다
"every" (-(으)ㄹ 때마다 "every time..."), 부터 "starting from" (-(으)ㄹ 때부터 "ever since..."), and
까지 "until" (-(으)ㄹ 때까지 "until...").

### 23.9. "Seems like it will..." with -(으)ㄹ 것 같아요 (p. 196-197)

Extends 22.8's 것 같아요 pattern to the prospective modifier, for "the fact that one/it will
do/be" — future-oriented "seems."

### 24.1.-24.2. Modifier clauses: "after" and "while" (p. 208-210)

**24.1** A processive modifier (-(으)ㄴ) + 후에/뒤에/다음에 = "after (something) happens/happened."
Contrast 전에 "before," which instead requires the different construction -기 전에 (Lesson 17).
Some descriptive verbs (늦어요, 나아요, 흐려요) double as processives ("becomes X"); most
descriptive verbs instead need the infinitive + -어져요 auxiliary to express "gets to be X"
(작아져요 "gets smaller"). **24.2** A processive modifier (-는) + 도중/동안/사이 ("middle,
midst"/"interval") expresses "while (something) is happening"; only 중 combines directly with the
copula for "is in the middle of doing" (공부하는 중이에요), giving fixed phrases like 통화중이에요
"the line is engaged," 회의 중이에요 "is in conference." A few descriptive verbs occur with -는
중 (바쁘신 중에 "in the midst of your being busy").

### 24.3. "Because of...ing" with -(으)ㄴ/-는 바람에 (p. 211)

A processive (-는) or descriptive (-(으)ㄴ) modifier + 바람 ("reason, cause") + 에. Similar in
meaning to -기 때문에 (17.7) but structurally distinct — 바람에 cannot be followed by the copula
(*추운 바람이었어요 is ungrammatical, whereas -기 때문이에요 "it's because..." is fine with 때문). The
consequence in a 바람에 clause is typically adverse/displeasing to the speaker — a genuine
speaker-stance/evaluative marker baked into the grammar, not just a neutral causal connective.

### 24.4.-24.6. Adverbative -게, causatives in -게 해요, and -게 돼요 (p. 211-216)

**24.4** The adverbative ending -게 (only on simple plain/honorific bases, never past/future) forms
adverbs describing how something is done or how a subject/object changes state (라디오 볼륨을
크게 했어요 "I turned up the radio [made it big]"). The copula has no adverbative form of its own;
되게 (from 되- "becomes") substitutes. **24.5** -게 해요 forms a periphrastic causative ("causes/
makes/lets [X] do/be"), semantically neutral between "make" (coercion) and "let" (permission)
readings — the transitive pattern reassigns the original agent to 에게/한테 (어머니가 아이에게 책을
읽게 해요 "the mother makes the child read the book"). Some verbal nouns instead take -시키- in
place of periphrastic 하게 한다 (문화 교류를 촉진시키고 싶습니다 "I want to promote cultural
exchange"). **24.6** -게 돼요 ("becomes/turns out so that...") marks the gradual inception of an
externally-controlled condition, distinct from (though overlapping with) infinitive+져요 and
-기(를) 시작해요; often best translated "happens to," "gets to," "manages to."

### 24.7. "It would be best to..." with -는 게 좋겠어요 (p. 216-217)

A processive plain base + 게 (abbreviated from 것 "thing/fact") + 좋겠어요 ("the fact of VERBing
would be good") = "you'd best VERB."

### 24.8.-24.9. Expressing intentions; -(으)ㄹ 대로 (p. 217-218)

**24.8** Beyond the future tense and -(으)려고 합니다, intention can be expressed via prospective
modifier + a NOUN+copula phrase using 계획 "plan," 예정 "prearrangement," 생각 "thought/idea," or
작정 "intention/decision" (졸업한 후에... 일할 계획입니다 "I plan to work... after graduating").
**24.9** The postmodifier 대 + 로: with a processive modifier (-는대로), "as soon as X happens"; with
any-tense modifier, 대로 alone means "according to, in accordance with, as" (하고 싶은 대로 하세요
"Do as you like"), including after certain bare nouns (마음대로 "as one likes," 사실대로 "stick to
the facts").

### 25.1. Pattern Review (Lesson 25, "REVIEW 4") — summarized, not re-extracted (p. 230-236)

Lesson 25 is a pure review lesson recapping, via new example sentences only, patterns already
covered: conditional -(으)면 (+ 좋겠어요/얼마나 좋겠어요/고맙겠어요/해 주셨으면 합니다/-지 않으면 안
돼요/-(으)면 안 돼요), intentive -(으)려(고), -(으)려면, -(는)군요, -(으)면서(도), mild -네요, ㅎ-dropping
verbs, transferentive -다(가), 말아요, -는/-(으)ㄴ 김에, -(으)ㄹ/-는 것 같아요, adverbative -게, -게
해요, -게 돼요, -는 게 좋겠어요, -(으)ㄹ 예정/생각/작정/계획이다, and -(으)는 대로. No new grammar rule
or nuance beyond what 22.1-24.9 above already capture; per the coverage rule this section is
recorded here only as a pointer, not re-extracted line by line.

### 26.1. The Plain Style (반말체) — register (p. 236-241)

**Central register-marking content of this chunk.** The **Plain Style**'s characteristic endings:
statements -다/-는다/-ㄴ다, Type-1 questions -느냐, Type-2 questions -니, Type-1 commands -(으)라,
Type-2 commands -어라/-아라, suggestions -자. Functions: (a) a neutral, matter-of-fact written
register (newspapers, textbooks, announcements); (b) a spoken register between intimates, or from
a social superior to an inferior (explicitly: "like the father to his son" in this lesson's
dialogue); (c) the foundational building block for reported/quoted speech (Lesson 27). The source
explicitly advises learners to avoid using Type-1 Plain commands in speech (they read as bookish/
written), and notes that Korean children (and sometimes adults) use Plain Style indicatives with a
boastful nuance.

**26.1.1-26.1.2** Statement formation differs by verb class: descriptive verbs take -다 on the bare
base (높다, 좋다, with predictable consonant-cluster sound changes, e.g. 높다 pronounced 놉따);
processive verbs take -ㄴ다 (vowel bases: 산다, 된다) or -는다 (consonant bases: 입는다, 먹는다).
Honorific bases follow the same descriptive/processive split (젊으시다 vs. 들으신다).

**26.1.3** Some bases straddle both categories with different statement endings depending on
sense — 해요-type verbal nouns split into processive-읽는다-type (입원한다 "enters hospital") vs.
descriptive-좋다-type (심하다 "is serious") depending on the noun's own semantics; the negative
auxiliary 않- likewise varies (앉지 않는다 "doesn't sit" vs. 좋지 않다 "isn't good"); 이러다/이렇다
("does/is this way") and 낫는다/낫다, 커요/크다 "gets big/is big" are explicit
processive/descriptive doublets of the same root.

**26.1.4** 있- is tricky: in its "stays" sense it's processive (있는다); in its "exists"/"has"
senses it's descriptive (있다 only). The honorific 계시- ("stays"/"exists") is treated as either,
interchangeably, with no meaning difference (계시다 or 계신다 both occur). 없- "doesn't exist" is
always descriptive (없다 only). The auxiliary 있- in -고 있- (progressive) and resultant-state -어
있- both behave as descriptive (있다, not *있는다).

**26.1.5** Past and future bases of *all* verbs (descriptive or processive alike) take -다:
-었다, -겠다.

### 26.2. Plain Style questions (p. 241-244)

**26.2.1 Type 1** (-(으)냐/-느냐): processive verbs (and 있-/없-) use the processive-modifier shape
-느냐; descriptive verbs use the simple-modifier shape -(으)냐. In colloquial speech the processive
-느냐 is routinely abbreviated to -냐, collapsing the processive/descriptive distinction in casual
speech (어디 갔다왔냐? "Where have you been?"). Past/future of all verbs use -느냐. **26.2.2 Type
2** (-니): a single one-shape ending usable with any base, "widely used (reciprocally) among
intimates or by elders to children" — an explicit peer/elder-to-child register marker. The source
flags a subtle trap: -니 (Type 2 question) is pronounced identically to the sequential ending
-(으)니(까) after vowel bases, but differs after consonant bases (Type-2 question 먹니 vs.
sequential 먹으니). Age/intimacy-register greeting formulas are noted: 잘 있었니?/잘 있었어? instead
of 안녕하십니까?/안녕하세요? when greeting a child; 잘 가거라!/잘 가라!/잘 가! as parting-register
equivalents of 안녕히 가십시오!/안녕히 가세요!.

### 26.3.-26.4. Plain Style suggestions and commands (p. 244-247)

**26.3** Suggestions use the one-shape -자 (processive verbs only), attaching like suspective -지;
common in colloquial speech (사자 "let's buy it"). **26.4.1 Type 1 commands** (-으라/-라) correspond
in meaning to Formal -(으)십시오 but are "hardly ever used in colloquial Korean" — encountered
mainly in textbook exercise instructions or protest-poster/rally slogans (미군을 추방하라! "Throw out
the American Army!" — an explicitly political-register example the source itself chose).
Negative: 말라 (often pronounced 마라). Their real functional home is as the base form for quoted
commands (Lesson 27). **26.4.2 Type 2 commands** (infinitive + 라, e.g. 먹어라, 살아라) are used
constantly in real speech, reciprocally among intimates or elder-to-child. A handful of verbs
(가-, 자-, 되-, 있-, 앉-, 듣-, 오-) take an irregular infinitive ending in -거 before this imperative
(가거라, 자거라...; 오- is irregular differently: 오너라). Negative commands regularly reduce 말아라
→ 마라.

### 26.5. Plain Style: the copula (p. 247)

Statement -이다; past -이었다; future -이겠다; questions -이냐 (no suggestion/command forms exist for
the copula, matching its descriptive-verb-like behavior). Sole negative: 아니다 (no long form
exists).

### 26.6. Intimate Style (반말) — register (p. 247-250)

**The second core register system of this lesson.** Used among intimates (close friends, children
speaking to each other, adults speaking to children); in real colloquial speech, Plain Style forms
(especially statements/suggestions) are routinely mixed in alongside Intimate Style forms in the
same conversation — the two registers are not kept hermetically separate in practice. **Formation
rule:** strip the polite particle 요 from any Polite Style ending (해요→해, 했어요→했어,
하겠어요→하겠어, 하세요→하셔, -이에요→-이야, 할 거예요→할 거야, 하지요→하지, 할까요→할까, 할래요→할래,
하잖아요→하잖아, 할게요→할게, 하네요→하네, 하거든요→하거든, 하는군요→하는군/하는구나) — a small, closed
set of forms deviate from the simple 요-stripping rule and are given as irregular exceptions. Notes:
같아요 → 같애 (not *같아) in the Intimate Style is common; the copula reduces to 이야 (after
consonants) / 야 (after vowels) sentence-finally, but 이어/여 when non-final (책이어도, 책이어서); the
copula can even drop entirely or reduce to a glide in some probable-future forms (-(으)ㄹ 거예요 →
-(으)ㄹ 거야); negative commands 말아라 abbreviate further to 마 in this register (보지 마! "Don't
look!").

### 26.7. "Because of...ing" with -느라(고) — the adjunctive (p. 250-252)

A one-shape ending on processive verbs only, meaning "what with...ing," "on account of the process
of...ing." Same-subject constraint across both clauses (like -(으)면서). The 고 is optional and
freely drops with no meaning change (하느라 = 하느라고). Illustrated heavily with parent-child and
peer dialogue register (어머니: 뭐 하느라고 벌써 용돈을 다 썼니? / 아들: 술 마시느라고 그랬어요 "What have
you been doing to spend all your pocket money already?" / "I spent it all on booze" — Plain/
Intimate-register parent-child exchange).

### 26.8. The copula transferentive: special uses (p. 252-256)

**26.8.1** Infinitive + 다(가) (always pronounced 다, since it follows a vowel-final infinitive)
marks a shift in the direction of an action or the recipient of a benefit, especially before 줘요/
드려요 "does for someone" or 봐요 "looks" — yielding the productive compound-verb family 들여다봐요/
내다봐요/쳐다봐요 ("looks in/out/stares at"). **26.8.2** "Errand-type" favor requests: embellishing
-어/아 주세요 with the transferentive (-어다/아다 주세요) adds emphasis that the favor involves a
spatial shift/errand (우유 좀 사다 주세요ᅳ "please buy milk [on your way]" vs. plain 사 주세요 "please
buy [it for me]"). **26.8.3** The copula transferentive also follows the particle 에 (에다,
에다가) to emphasize a shift of location/purpose (상 위에다 놓으세요 "please put it on the table");
optional throughout, dropping it only removes the emphasis-on-shift nuance, not the core meaning.

### 27.1. Quotations: direct and indirect (p. 274-277)

Korean, like English, has both direct quotation (verbatim) and indirect quotation (gist only), but
uses direct quotation less often than English. **27.1.1 Direct quotations**: the quoted material
(introduced optionally by 말하기를.../묻기를...) is followed by the quoting particle -(이)라고 or
하고, then a quoting verb (말해요, 물어요, 물어봐요). Verbs of *thinking/believing* (생각하-, 믿-, 여기-)
are explicitly grouped with verbs of *saying* for quotation purposes — an important
cross-linguistic point (Korean's quotation grammar covers reported thought, not just reported
speech). 하고 cannot combine with 해요/그래요 as the quoting verb; only -(이)라고 can, in that
specific combination. **27.1.2 Indirect quotations**: require (a) shifting person references, (b)
dropping honorifics inappropriate to the shifted referent, and (c) recasting the quoted verb into
Plain Style (Type 1) — the very register system just taught in Lesson 26, now revealed as
existing largely *to serve* the quotation system. The quotation particle 고 ("saying that...") may
be present (**expanded** quotation, 간다고 해요) or freely drop (**simple** quotation, 간다 해요,
more common in writing than speech), and can further contract by dropping 하- itself
(**contracted** quotation, 간대요) — contracted forms, unlike simple ones, are described as "very
common in spoken Korean." This three-way expanded/simple/contracted continuum recurs identically
across statements, questions, suggestions, and commands in 27.2-27.4 below.

### 27.2.-27.4. Quoted questions, suggestions, and commands (p. 277-282)

**27.2** Quoted questions use the Plain-Style question ending -느냐 (colloquially often abbreviated
to -냐, collapsing with the descriptive-verb question form) + 고, with the same
expanded/simple/contracted continuum (가느냐고 물었어요 / 가느냐 물었어요 / 가느냬요, the last marked
"rare"). Negative quoted questions regularly use the long negative (-지 않-). **27.3** Quoted
suggestions use -자고 (expanded) / -자 (simple) / -재요 (contracted). **27.4** Quoted commands use
only the Plain Style **Type 1** command form (-(으)라고), never Type 2 (-어라/아라) — explicitly
resolving why Type 1 commands, described in 26.4.1 as "hardly ever used" in ordinary speech, matter
at all: their whole functional niche is quotation. Contracted form -(으)래요 (가랬어요/가래요 "told
[me] to go"). The addressee of a quoted command takes 한테/에게 ("to").

### 27.5.-27.6. The copula in quotations (p. 282-284)

The ordinary Plain-Style copula -이다 is *not* used in quotations; it's replaced by 라 (하나
negative-only copula becomes 아니라 in quotations, from 아니다). Present-tense quoted copula is
pronounced 이라. A specialized construction "an A called X" has a full reduction cline: X이라고
하는 A (expanded) → X이라 하는 A (simple) → X이라는 A (usual abbreviated form) → X이란 A (further
reduced, and ambiguously homophonous with "an A that has been called X"). Contrast this "called X"
meaning with plain equational modifiers: X인 A "an A that is X" vs. X이 된 A "an A that has become
X."

### 27.7. "According to..." with -에 의하면 (p. 284)

A noun + 에 의하면 ("according to [the noun]") is typically followed by a quotation construction
(신문에 의하면... 랍니다 "According to the newspaper...").

### 27.8. Using 달라(고) 하- to quote 주세요 "give me" (p. 285-286)

When the original utterance used 주- in its "give **me**"/"do **me** the favor of" sense (as
opposed to "give [it] to someone else"), it cannot be quoted with 주라고 — Korean requires the
switched verb 달라(고) 하- instead (abbreviating to 달래요). This is a genuine suppletive-verb
quotation rule, not a simple morphological transform, and is illustrated with a three-way minimal
contrast: 만호한테 책을 주라고 했습니다 "told [her] to give the book to Manho" vs. 할머니한테 책을
드리라고 했습니다 "...to grandmother" (honorific 드리- for the addressee) vs. (자기한테) 책을 달라고
했습니다 "...to him(self)" (the giving is *to the original speaker*, hence 달라 not 주라).

### 27.9. The particle (으)로: further meanings (p. 286-288)

A "new" meaning surveyed here: (으)로 as a stylistic variant of the copula gerund -이고 ("is X,
and..."), blending into an "as/for [in the capacity of]" sense (대학 교수로 계세요 "He is [there] as
a university professor"). Contrast NOUN 치고는 "for a NOUN" (외국사람 치고는... "for a foreigner...")
which is a *different* pattern despite the superficially similar English gloss. (으)로서 adds 서 to
strengthen the "as/in the capacity of" sense. The lesson closes with a compact taxonomy of (으)로's
other established senses — exchange, direction, time, manner, change of state, means, material,
cause/reason/purpose — collecting uses taught piecemeal across earlier lessons into one summary
table.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `../../00_Reference_Extraction_Spec.md`.
