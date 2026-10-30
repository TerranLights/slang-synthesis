# Korean — Established Vocabulary/Grammar: *Integrated Korean: Beginning 1*, Introduction Unit

**Source:** Young-mee Cho, Hyo Sang Lee, Carol Schulz, Ho-min Sohn, Sung-Ock Sohn, *Integrated
Korean: Beginning 1* (KLEAR Textbooks in Korean Language, University of Hawai'i Press, 2000),
Introduction: "What Kind of Language Is Korean?", pp. 1–15 (PDF pp. 9–23 of the scanned file;
confirmed offset: printed page = PDF page − 8, verified at three independent points).

**Filename note (resolved):** at extraction time, `035` was transiently occupied by a rogue
duplicate file (`035_lets_learn_korean_northern_dialect_full.md`) produced by an unrelated
agent's scope violation during item 033's extraction — this extraction correctly self-detected
the collision and wrote to `036_...` instead to avoid overwriting existing content. That rogue
file has since been moved to a backup location and the collision resolved by the orchestrating
session, restoring this file to its originally-intended path/number, `035`. See
`00_RESUME_HERE.md`'s "Incident: rogue sub-forking..." section for the full account.

## Coverage note — non-redundant-supplement scope (most of this book skipped as redundant)

Korean already has 35 established files (001–035) covering beginner grammar/vocabulary in depth,
including several other true-beginner courses (`001_basic_korean_part1`,
`024_elementary_korean_part1`/`025_elementary_korean_part2`, `016_active_korean_1`,
`015_korean_through_english_1`, `014_teach_yourself_korean`), a dedicated pronunciation/phonology
source (`013_sounds_of_korean_pronunciation_guide`, which already covers the vowel system,
3-way laryngeal consonant contrast, full-closure/unrelease sandhi, and connected-speech rules —
the same territory as this book's "Han'gul and Pronunciation" chapter), and a deep academic
honorifics source (`031_korean_honorifics_and_politeness`, which already covers the six-way
speech-style system, subject/object honorifics, and a 29-pattern address-term typology in far
more depth than this textbook's treatment).

Given that, and given this is *Beginning 1* — the most elementary level in the series — the
following was checked and **skipped as redundant, not extracted**:

- **Lessons 1–7** (Greetings, The University Campus, Korean Language Class, At School, My Day,
  The Weekend, In Seoul; pp. 43–269): sampled Lesson 1's vocabulary/grammar pages directly. Content
  is standard A1-level material (copula ~이에요/예요, basic particles, campus/classroom nouns,
  proper-name conventions) that duplicates ground already covered by the other beginner-level
  sources listed above. No chunk sampled produced content absent from the existing corpus.
- **"Han'gul and Pronunciation" chapter** (pp. 16–39): sampled directly (syllable-final
  closure/unrelease rule, consonant/vowel inventory, syllable structure) — this is the same
  mechanism `013` already documents in more systematic form (its "Full closure" and "Adjustments"
  sections). Not re-extracted.
- **Appendices 1–6** (pp. 270–289: copula/adjective/verb conjugation tables, honorific/humble
  word-pair table, kinship terms, color terms, numbers, counters): sampled directly. The
  conjugation-paradigm table (Appendix 1-1/1-2) is also the single most OCR-garbled content in
  the book (see gotcha note below) and cross-references grammar patterns from lessons 8–15 of the
  wider series, not this volume's own lessons. The honorific/humble pair list duplicates (in much
  shallower form) what `031` already covers; kinship/color/number/counter vocabulary duplicates
  14+ existing files. Not re-extracted.
- **Grammar Index and Korean–English/English–Korean glossaries** (pp. 290–331): reference
  apparatus, not original content; not extracted.

**Kept as genuinely new** — the Introduction unit, "What Kind of Language Is Korean?" (pp. 1–15),
which precedes the lessons in every book in this series and was never captured from any prior
Korean source (grepped `established/*.md` for "macro-to-micro", "situation-oriented",
"free word order", "35 percent"/"60 percent" vocabulary-composition figures, and the specific
7-dialect name list — zero hits on all of these before this extraction). This chapter is a
synthesis essay rather than a lesson, giving demographic/dialectological data, an explicit
3-way vocabulary-composition split, and named typological framings (word order, pro-drop,
naming-order) not found elsewhere in this project's Korean corpus. It is extracted in full below.

### PDF/OCR gotcha: Hangul renders as non-decodable OCR noise, distinct from this project's known Hangul font-substitution ciphers

This file is a scanned book (`Creator: CanoScan LiDE 210`, `Producer: Adobe Acrobat 9.0 Paper
Capture Plug-in`) with a real OCR'd text layer. **English prose extracts cleanly** (aside from
ordinary OCR noise: broken ligatures, stray spaces, occasional letter swaps like "ofHawai'i").
**The book's own McCune-Reischauer romanization also extracts legibly.** But **embedded Hangul
glyphs are not recoverable at all** — they come out as unrelated Latin/symbol soup (e.g. "꽃은"
rendering as `~ 2.`) with no consistent 1:1 or fixed-offset pattern across samples checked. This
is **true OCR misrecognition, not a decodable cipher** — distinct from the fixed-offset Hangul
font-substitution pattern documented elsewhere in `00_Reference_Extraction_Spec.md`
(`real_codepoint = (extracted_codepoint + 36266) mod 65536`), which does not apply here (verified
by testing it against several known words from this file; it does not decode them). Rather than
fall back to vision-reading 15 pages for a handful of vocabulary items, Hangul forms quoted below
were **supplied from independent, confident knowledge of standard Korean vocabulary** (cross-
referenced against the book's own clean romanization and English gloss in every case), not
transcribed from this source's garbled text layer. Flagged per-row in the `Notes` column.
**One specific OCR error caught and corrected this way:** the book's plain-vs-honorific pair for
'age' romanized as plain `nal` / honorific `yonse` — but `nal` 날 means 'day', not 'age', and
cross-referencing against standard Korean confirms the intended plain form is `nai` 나이 'age'
(honorific `yonse` 연세 is correct and well-attested). The printed `i`→`l` substitution is a
classic OCR letter-confusion; corrected in the table below with the error flagged in Notes rather
than silently fixed.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 중부 방언 (central dialect) | Central dialect (Seoul and vicinity); basis of South Korea's p'yojun-o 'Standard Language' | noun phrase (dialect name) | regional | — | contemporary (source published 2000) | Seoul and vicinity | regional | grammar_reference | n/a | n/a | p.2. Hangul supplied from independent knowledge, not from this source's garbled OCR text layer (see gotcha note above) — romanization "chungbu" is the book's own legible text. |
| 충청 방언 (Ch'ungch'ong dialect) | spoken in the Ch'ungch'ong province area, between the central and southern dialect zones | noun phrase (dialect name) | regional | — | contemporary (source published 2000) | Ch'ungch'ong provinces | regional | grammar_reference | n/a | n/a | p.2. Hangul supplied independently; romanization "Ch'ungch'ong" is the book's own legible text. |
| 전라 방언 (Cholla dialect) | spoken in the southwest | noun phrase (dialect name) | regional | — | contemporary (source published 2000) | southwest Korea (Cholla) | regional | grammar_reference | n/a | n/a | p.2. |
| 경상 방언 (Kyongsang dialect) | spoken in the southeast | noun phrase (dialect name) | regional | — | contemporary (source published 2000) | southeast Korea (Kyongsang) | regional | grammar_reference | n/a | n/a | p.2. |
| 평안 방언 (P'yongan dialect) | spoken in P'yongyang and vicinity; basis of North Korea's munhwa-o 'Cultured Language' | noun phrase (dialect name) | regional | — | contemporary (source published 2000) | P'yongyang and vicinity (North Korea) | regional | grammar_reference | n/a | n/a | p.2. |
| 함경 방언 (Hamgyong dialect) | spoken in the northeast | noun phrase (dialect name) | regional | — | contemporary (source published 2000) | northeast Korea/North Korea (Hamgyong) | regional | grammar_reference | n/a | n/a | p.2. |
| 제주 방언 (Cheju dialect) | spoken on the island of Cheju | noun phrase (dialect name) | regional | — | contemporary (source published 2000) | Cheju island | regional | grammar_reference | n/a | n/a | p.2. |
| 오렌지 주스 (orenji jusu) | orange juice | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | p.5, loanword phonologically adapted from English; Hangul supplied independently (unambiguous common loanword), romanization is the book's own legible text. |
| 스포츠 (s'up'och'u) | sports | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | p.5, loanword from English "sports." |
| 스트레스 (s'ut'uresu) | stress | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | p.5, loanword from English "stress." |
| 수퍼 (syupo) | super(market) | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | p.5, loanword clipped from English "supermarket." |
| 택시 (t'aeksi) | taxi | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | p.5, loanword from English "taxi." |
| 텔레비전 (t'ellebijon) | television | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | p.5, loanword from English "television." |
| 영화 (yonghwa) | movie | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | p.4, Sino-Korean word coined in Japan from Chinese characters, borrowed into Korean via Japanese. |
| 일요일 (iryoil) | Sunday | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | p.4, same borrowing pattern as above. |
| 과학 (kwahak) | science | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | p.4, same borrowing pattern as above. |
| 입구 (ipku) | entrance | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | p.4, same borrowing pattern as above. |
| 약속 (yaksok) | promise | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | p.4, same borrowing pattern as above. |
| 편지 (p'yonji) | letter | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | p.4, contrast case: Sino-Korean word coined independently by Koreans with Chinese characters as building blocks (not borrowed from Japanese). |
| 식구 (sikku) | family members | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | p.4, same native-Sino-Korean-coinage pattern. |
| 삼촌 (samch'on) | uncle | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | p.4, same native-Sino-Korean-coinage pattern. |
| 일기 (ilgi) | weather | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | p.4, same native-Sino-Korean-coinage pattern; distinct from the homophonous/near-homophonous native word for 'diary'. |
| 외상 (oesang) | on credit | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | p.4, same native-Sino-Korean-coinage pattern. |
| 한국 (han-guk) | Korea | proper noun | core | — | contemporary (source published 2000) | — | transnational (comparative) | grammar_reference | n/a | n/a | p.3–4, book's 3-way comparative table of the same Chinese-character compound's divergent pronunciation: Mandarin "han-kwo", Korean "han-guk", Japanese "kan-koku" — illustrates independent sound-change divergence of a shared Sino-character word across three languages. |
| 대학 (tae-hak) | college | noun | core | — | contemporary (source published 2000) | — | transnational (comparative) | grammar_reference | n/a | n/a | p.3–4, same comparative table: Mandarin "ta-she", Korean "tae-hak", Japanese approx. "dai-gaku" — the Japanese form is OCR-corrupted in the source ("ciai-galw") and reconstructed by inference; flagged low_confidence for that one form specifically (the Korean/Mandarin forms are legible and not in question). |
| 밥 / 진지 (pap / chinji) | meal (plain / honorific) | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | p.9, plain-vs-honorific lexical suppletion pair. Hangul supplied independently; romanization is the book's own legible text. |
| 집 / 댁 (chip / taek) | house (plain / honorific) | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | p.9, same pattern. |
| 이름 / 성함 (irum / songham) | name (plain / honorific) | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | p.9, same pattern. |
| 나이 / 연세 (nai / yonse) | age (plain / honorific) | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | p.9. **OCR correction applied**: source romanizes the plain form as "nal" (날 'day'), which is almost certainly an OCR i→l misread of "nai" (나이 'age') — corrected here; see gotcha note above for reasoning. |
| 먹다 / 잡수시다 (mokta / chapsusida) | eat (plain / honorific) | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | p.9, same suppletion pattern, applied to verbs rather than nouns. |
| 자다 / 주무시다 (chada / chumusida) | sleep (plain / honorific) | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | p.9, same pattern. |
| 있다 / 계시다 (itta / kyesida) | stay, exist (plain / honorific) | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | p.9, same pattern. |
| 주다 / 드리다 (chuda / tirida) | give (plain, to a junior / humble, to a senior) | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | p.9, humble (not honorific) suppletion — the humble form lowers the speaker rather than raising the referent; distinguished explicitly from the honorific pairs above by this source. |
| 보다 / 뵙다 (poda / pwepta) | see (plain, a junior / humble, a senior) | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | p.9, same humble-suppletion pattern. |
| 나 / 저 (na / ce) | I (plain / humble 1st-person pronoun) | pronoun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | p.9. |
| 우리 / 저희 (uri / ce-hoe) | we (plain / humble 1st-person pronoun) | pronoun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | p.9. |
| 님 (-nim) | honorific address/title suffix ("Mr./Ms.", lit. "honorable") | suffix | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | p.7, gender-neutral; attaches to an occupational title (optionally preceded by the full/family name), e.g. kyosu-nim 'Professor'. |
| 씨 (ssi) | title noun used among young adult equals/colleagues or to an adult junior | noun (title) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | p.8, attaches to a full name or given name alone. |
| 아 / 야 (-a / -ya) | child-address particle (after consonant / after vowel) | particle | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | p.8, attaches to a bare given name when addressing a child — a bare name is otherwise never used to address an adult except by that adult's own parent or teacher. |

## Grammar points

### 1. Demographics and the seven-dialect taxonomy (pp. 1–2)

The source gives specific population figures not found elsewhere in this project's Korean
corpus: Korean is spoken natively by ~67 million people on the peninsula (23 million North, 44
million South), as a heritage language by ~5.6 million overseas Koreans (2M China, 2M US, 0.7M
Japan, 0.5M former Soviet Union), and is ranked 11th among the world's ~3,000 languages by
speaker count. It names seven geographically based dialects (Central, Ch'ungch'ong, Cholla,
Kyongsang, P'yongan, Hamgyong, Cheju — see Vocabulary table) and layers a sociopolitical
North/South division on top of the geographic one: North Korea replaced many Chinese-character-
based words with newly coined native words and uses Communist-ideology-laden expressions, while
South Korea has borrowed heavily from English in recent decades. The source explicitly notes
P'yongyang's "Cultured Language" and Seoul's "Standard Language" share enough elements that the
North/South linguistic divergence is "not as great as often claimed" — a direct editorial claim
worth flagging as a single source's position, not independently corroborated here.

### 2. Vocabulary composition: a named three-way split (p. 4)

The source gives an explicit, citable composition for the Korean lexicon as a whole: **native
words and affixes ≈ 35%**, **Sino-Korean words ≈ 60%**, **loanwords ≈ 5%**. It characterizes each
layer functionally rather than just numerically: native stock covers daily necessities (food,
clothing, shelter), locations, basic actions/states, lower-level numerals, body parts, natural
objects/animals, sound-symbolic (onomatopoeic/mimetic) vocabulary, and most particles/affixes;
Sino-Korean covers higher-register/abstract vocabulary built from Chinese characters (including
items coined independently in Korea, e.g. p'yonji 'letter', sikku 'family members', samch'on
'uncle' — and items coined in Japan from Chinese characters and borrowed via Japanese, e.g.
yonghwa 'movie', iryoil 'Sunday', kwahak 'science'); loanwords are predominantly from English
since WWII, with an earlier layer of Japanese words (and Japanese-mediated Western words) borrowed
during the 35-year Japanese occupation. **Per the frequency-column rule, this is whole-lexicon
composition data from a single named source, not a corpus-frequency dictionary — it should be
treated as a citable claim about the language in general, not a frequency value for any
individual word.**

### 3. Sino-character cognate divergence across Korean/Japanese/Chinese (pp. 3–4)

The source gives a direct comparative example of how a single Chinese-character-based word
diverges in pronunciation across the three languages that inherited it: 'Korea' is Mandarin
*han-kwo*, Korean *han-guk*, Japanese *kan-koku*; 'college' is Mandarin *ta-she*, Korean *tae-hak*,
Japanese (reconstructed; see Vocabulary table note) *dai-gaku*. This is framed explicitly as
evidence that "since identical words and characters evolved independently in the three countries,
their current pronunciations are considerably different" — useful, low-noise evidence for this
project's eventual sound-change/divergence modeling, precisely because it's the same morpheme
lineage split three ways rather than a cross-language coincidence.

### 4. Loanword phonological adaptation (pp. 4–5)

The source states the adaptation principle directly: loanwords have their source-language sounds
"slightly modified... according to the available sound pattern of Korean," and explicitly
distinguishes this from code-switched **foreign words** — if a word is pronounced the way native
speakers of the donor language normally pronounce it, it is not (yet) a loanword. The worked
examples (see Vocabulary table: *orenji jusu*, *s'up'och'u*, *s'ut'uresu*, *syupo*, *t'aeksi*,
*t'ellebijon*) show vowel epenthesis breaking up English consonant clusters and syllable-final
consonants that don't fit Korean's syllable template — the same general mechanism the source
later illustrates with the single-syllable English word "strike" becoming the five-syllable
loanword *su.t'u.ra.i.k'u*.

### 5. Word order: SOV, postpositional particles, and a named "free word order" scrambling property (p. 5)

Korean (like Japanese) is verb/adjective-final: subject and object both precede the predicate,
and all grammatical particles (the functional equivalent of English prepositions) are
**postpositions** — they follow the noun they attach to, never precede it. The source names
Korean explicitly as a **"free word order" language**: because only the clause-final verb/
adjective position is fixed, every other element may be scrambled for emphasis or stylistic
effect, and the source walks through multiple valid reorderings of one sentence ("John plays
tennis with Mary at school" → "John school-at Mary-with tennis plays" → "school-at Mary-with John
tennis plays" → "Mary-with tennis John school-at plays" → "tennis John school-at Mary-with
plays") to demonstrate the scrambling is genuinely multi-directional, not just one alternate
order. This specific named typological label ("free word order") was not found in any of the
other 35 established Korean files.

### 6. "Situation-oriented language": pro-drop as a named typological property (pp. 5–6)

The source names Korean explicitly as a **"situation-oriented language"**: contextually/
situationally understood elements — crucially, including the **subject**, not just the object —
are omitted more often than not. It gives three short worked examples (*annyonghaseyo?* 'how are
you', *komapsumnida* 'thank you', *odi kaseyo?* 'where are you going') where English requires an
explicit subject/pronoun and the Korean original has none, and notes explicitly that inserting the
2nd-person pronoun into any of these would sound awkward unless that pronoun were itself being
emphasized or contrasted. This framing — pro-drop as a *named, general property of the language*
rather than an incidental feature of individual sentences — was not found elsewhere in the
existing Korean corpus.

### 7. "Macro-to-micro language": a named ordering convention across three domains (p. 6)

The source names Korean (again, like Japanese) explicitly as a **"macro-to-micro" language**: the
whole (macro) is represented before its members (micro) consistently across three unrelated
domains it enumerates together as instances of one underlying pattern:
- **Personal names**: family name first, given name second, optional title last (*Kim Minsu
  kyosu-nim* 'Prof. Minsu Kim').
- **Addresses**: country → province → city → street → house number → personal name (the reverse
  of standard English address order).
- **Dates**: year → month → day (*2000-nyon il-wol i-il* '2000-year 1-month 2-day' = January 2,
  2000).

Framing these three independently-familiar facts as expressions of one named general principle is
the genuinely new contribution here — none of the other 35 Korean established files name or
generalize this pattern, even though individual pieces of it (e.g. date format) are presumably
implicit in other sources' example sentences.

### 8. Honorific/humble lexical suppletion as a distinct mechanism from honorific morphology (pp. 7–9)

Separately from (and prior to) the morphological honorific-suffix system that `031` already
documents in depth, this source isolates a smaller, closed set of **whole-word suppletion pairs**
— nouns, pronouns, and verbs that have an entirely distinct plain-register lexeme and
honorific/humble-register lexeme, with no morphological derivation connecting the two forms (see
Vocabulary table for the full list: *pap/chinji*, *chip/taek*, *irum/songham*, *nai/yonse*,
*mokta/chapsusida*, *chada/chumusida*, *itta/kyesida*, plus the humble-specific pair *chuda/tirida*
and *poda/pwepta*, plus the pronoun pairs *na/ce* and *uri/ce-hoe*). The source draws an explicit
distinction within this set between **honorific** forms (which raise the referent — used for an
adult equal or senior) and **humble** forms (which lower the speaker — used when the speaker is
addressing a senior about their own actions, e.g. "give"/"see"), a distinction worth preserving
since the two mechanisms are often collapsed under a single "honorifics" label. It also gives the
morphological address-formation rules in brief: the honorific suffix *-nim* (gender-neutral,
attaches to an occupational title), the title noun *ssi* (used among young adult equals), and the
child-address particle *-a/-ya* (attaches to a bare given name — bare names are otherwise never
used to address an adult except by that adult's own parent or teacher).

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`.
