# Korean — Established Reference: The Sounds of Korean: A Pronunciation Guide

**Source:** Young-mee Yu Cho, Sang-Oak Lee, Stephen Wright Horn, Sung-Ock Sohn, & William
O'Grady (Korean Studies Program/University of Hawai'i team), *The Sounds of Korean: A
Pronunciation Guide* (includes companion CD, ~2010; scanned copy shows a 2011 CanoScan/Adobe
Paper-Capture-OCR date). Part I ("Description"), all of it: Ch. 1 "Learning to Pronounce Korean,"
Ch. 2 "Vowels," Ch. 3 "Consonants," Ch. 4 "Adjustments," Ch. 5 "Prosody," plus References and
Glossary. Printed pages 1–110 (PDF pages 5–62 of 141). Part II ("Practice Exercises," printed pp.
111–255, PDF pp. ~63–141) is drill material tied to the companion audio CD — not extracted, per
the coverage rule (repeated drill exercises with no new phonological content beyond what Part I
already establishes).

**This is a dedicated phonology reference** — like Kornai's *On Hungarian Morphology* was for
Hungarian, this book's own analytical value is in its systematic description of the Korean sound
system and its worked examples, not in a large vocabulary sample. Per the dispatch instructions,
grammar-point prose is prioritized heavily over a flat vocabulary table; the table below is
intentionally small, capturing only the handful of items that are lexically distinctive in their
own right (minimal pairs, the one dialectal item found) rather than re-listing the hundreds of
single-use example words used throughout the adjustment-rule sections (담요, 무릎, 학생, etc.) —
those live instead inside the grammar-point writeups and morpheme-breakdown notes below, cited by
their own worked-example role rather than as independent lexical entries.

**PDF-quality note (a new gotcha for this project, distinct from the font-substitution-cipher
pattern already documented from Korean's Wave 1 books).** This PDF's metadata shows it was
produced via `CanoScan LiDE 210` + `Adobe Acrobat 9.0 Paper Capture Plug-in` — i.e., a flatbed-
scanned book run through an old, low-quality OCR engine, not a genuine digital-born text layer.
`pdftotext` output is badly garbled for *both* the English prose and the Hangul (e.g., "THE SOUNDS
OF KOREAN" decodes as fragments like "111\· S(II INIl" ni, 1'~ (lIl1i\'N" — this is authentic bad
OCR noise, not a fixed-offset cipher of the kind found on 4 of Korean's Wave-1 PDFs, and the
`+36266`-style offset decode does not apply here). Every page in this file was therefore read via
direct vision-reading of 170dpi page renders (`pdftoppm`), not `pdftotext`. **Scan-format gotcha
confirmed on this book, worth flagging for any future Korean vision-reading dispatch:** the PDF's
own page-rotation metadata is 270°, and each PDF page is a scanned two-printed-page spread (left +
right physical pages side by side in one image), not one printed page per PDF page — verified
directly by rendering and reading spreads rather than assumed from `pdfinfo`. The offset
`printed_page ≈ 2×PDF_page − 8` (left page) / `2×PDF_page − 7` (right page) was empirically
confirmed against the book's own printed running-header page numbers at multiple points across the
whole assigned range (PDF pages 5–62), not just once. **No marginalia risk found** — every spread
in the assigned range is clean printed book content; no handwritten annotation was present in any
image inspected.

**Vision Reading Confidence.** All entries and grammar points below are `verified` — every Hangul
form and its bracketed `[pronunciation]` was read directly from a clear, high-resolution page
render, and the vast majority of examples are independently cross-checked by the book's own device
of giving multiple related examples per rule (e.g., multiple `ㅂ>ㅃ`-type tensing examples on the
same page). No `low_confidence` rows were needed anywhere in this range — scan quality was uniformly
good (a clean flatbed scan, just poorly OCR'd by the old Acrobat plugin, which is why vision-reading
rather than text-extraction was used throughout).

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 니 / 니 | 'your' (colloquial pronunciation) | pronoun | colloquial | — | contemporary (source ~2010) | — | — | grammar_reference | n/a | verified | 니 [니] is the colloquial pronunciation of the possessive 네 'your', arisen specifically to keep it distinct from 내 'my' now that the 에/애 (e/ae) distinction has been lost for most speakers; source's own worked case for a phonological merger driving a synchronic lexical split. p. 12 |
| 에 / 애 (몌 'bell' vs. 애플 'apple' spelling pair) | 'bell (loanword)' / 'apple' | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | not independent words but the source's own minimal-pair illustration that English loanword spelling still distinguishes ㅔ vs. ㅐ even though the two have merged in actual pronunciation for virtually all speakers. p. 13 |
| 의사 / 의자 | 'doctor' / 'chair' | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | word-initial 의 diphthong citation forms, showing its full [ɰi]-type pronunciation only in careful word-initial speech. p. 18 |
| 미국의 수도 | "America's capital" | noun phrase | core | — | contemporary | — | — | grammar_reference | n/a | verified | 의 functioning as the possessive suffix is pronounced as simple 에, distinct from both its word-initial and post-consonantal pronunciations — the book's three-way conditioned-allomorphy example for a single spelled vowel. p. 18 |
| 발 / 벌 | 'foot' / 'bee' | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | ㅏ/ㅓ minimal pair cited to justify the phonemic contrast. p. 15 |
| 다 / 더 | 'all' / 'more' | adverb | core | — | contemporary | — | — | grammar_reference | n/a | verified | ㅏ/ㅓ minimal pair. p. 15 |
| 위기 / 의기 | 'crisis' / 'spirits, vigor' | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | 위 vs. ㅢ diphthong minimal pair, cited as a genuinely difficult contrast for L2 learners (ㅜ+ㅣ glide sequence vs. ㅡ+ㅣ). p. 20 |
| 바닷가 / 바다 + 가 | 'seaside' / 'sea' + 'side' | noun / noun + bound root | core | — | contemporary | — | — | grammar_reference | n/a | verified | the source's own step-by-step 사이 시옷 ("in-between ㅅ") worked derivation: /s/-insertion between a vowel-final native root and a following root, itself then triggering downstream tensing/nasalization. p. 90 |
| 같이 / 가치 | 'together' / 'value' | adverb / noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | the source's key example that its own palatalization rule (ㄷ,ㅌ→ㅈ,ㅊ before a suffix-initial ㅣ/야-type glide) can produce two etymologically unrelated words with identical surface pronunciation, [가치]. p. 93 |
| 닫혀요 / 다쳐요 | 'It's being closed' / 'You're going to be hurt' | verb | core | — | contemporary | — | — | grammar_reference | n/a | verified | source's most elaborate single derivation: ㄷ+ㅎ aspirates to ㅌ, then that ㅌ palatalizes to ㅊ before the following 여, converging with 다쳐요's own ㅊ — two distinct verbs made homophonous by the ordered interaction of two adjustment rules. p. 93 |
| 나밖에 / 너밖에 | 'except me' / 'except you' | particle phrase | core | — | contemporary | — | — | grammar_reference | n/a | verified | -밖에 'except' as the source's example of optional nonpredictable tensing of a suffix-initial lax consonant, plus (separately) as a thought-group-boundary minimal pair distinguishing "aren't you going outside?" from "is no one but you going out?" depending on pause placement. pp. 89, 106 |

### Morpheme breakdown

> **꽃무늬** ("floral design") = 꽃 (flower, orthographic-final ㅊ) + 무늬 (design/pattern). Fully
> traced adjustment cascade: the word-final ㅊ of 꽃 first undergoes **full closure** (obligatory
> before a following consonant/word boundary), giving it the same unreleased [ㄷ]-type realization
> as ㅌ, ㅅ, ㅆ, ㅈ, ㅉ all share in that position; that [ㄷ] then undergoes **nasalization** before
> the following ㅁ of 무늬, surfacing as [ㄴ] — yielding the fully adjusted pronunciation [꼰무니]. A
> further, optional step is noted: the ㄴ itself can regressively re-trigger a labial-place shift so
> that the ㅁ of 무늬 conditions it toward an [ㅁ]-like articulation in fast speech, i.e. some
> speakers produce something closer to [꼼무니]. This is the book's single most fully worked
> multi-rule cascade and is presented explicitly as a teaching case for how the individually-simple
> adjustment rules chain together in real connected speech. p. 82

> **정신력** ("mental strength") = 정신 (mind, Sino-Korean bound-root compound) + 력 (strength/power,
> bound root). Because 정신 and 력 form one tight semantic/prosodic unit (both Chinese-origin
> roots), the ㄴ-final syllable combines *directly* with the following ㄹ-initial syllable, so the
> **ㄴ+ㄹ → [ㄹ+ㄹ]** adjustment (rather than the reverse ㄹ-conditions-ㄴ pattern) applies, giving
> [정신녁] — contrasted explicitly against 신문로 ("Shinmun street") [신문노], where the ㄴ-final
> syllable instead combines first with the syllable to its *left*, blocking that same adjustment
> and forcing the opposite nasalized-ㄹ-as-ㄴ outcome instead. The source's point: this particular
> adjustment is sensitive to a word/compound's *internal semantic bracketing*, not just its linear
> phoneme sequence — a genuinely morphosyntax-conditioned phonological rule. pp. 74–75

> **입력** ("power input") = 입 (input, bound root) + 력 (power/strength, bound root). A
> two-step derivation given in full by the source: (1) the ㄹ of 력 is first nasalized to [ㄴ]
> because it follows the ㅂ of 입 (a consonant other than ㄴ/ㄹ) — see the "ㄹ after a
> non-ㄴ/ㄹ consonant → pronounced as if ㄴ" rule; (2) that newly-derived [ㄴ] then itself triggers
> nasalization of the preceding ㅂ (→[ㅁ]), because [ㄴ] is one of the two nasal triggers for that
> separate rule. Net result: [임녁]. This is the source's worked demonstration that its adjustment
> rules can **feed** one another in sequence (rule 2's output becomes rule 1's — here, actually
> rule-2's-trigger-created-by-rule-1 — input), not just apply once each in isolation. p. 79

> **막일** ("manual labor") = 막 (rough/crude, bound root) + 일 (work, independent word). Because 일
> begins with plain ㅣ and 막 ends in a consonant, **ㄴ-addition** inserts a ㄴ at the start of 일 (→
> 막[닐]); that inserted ㄴ then itself **nasalizes** the preceding ㄱ of 막 (→[ㅇ]), giving the final
> pronunciation [망닐]. Cited alongside 나뭇잎 ("tree leaf") = 나무 + 잎, which independently combines
> *two different* processes — **ㅅ-insertion** (사이 시옷, since 나무 ends in a vowel) *and*
> **ㄴ-addition** (since the resulting 나뭇 now ends in a consonant before 잎's plain ㅣ) — cascading
> to [나문닙]. Both are the source's central illustrations that its individually-simple adjustment
> rules chain into genuinely multi-step derivations once a real compound is involved. pp. 83, 91–92

> **끝이 / 솥이 / 밭이** ("end/kettle/farm-field" + subject marker) — noun-final ㅌ regularly
> palatalizes to ㅊ before a suffix-initial ㅣ (yielding [끄치], [소치], [바치] under the ㄷ/ㅌ
> palatalization rule, §4.14), but each of these forms can undergo a *further*, optional
> "consonant weakening" step in which that derived ㅊ is itself weakened all the way to ㅅ, giving
> the alternate pronunciations [끄시], [소시], [바시]. This double-step (palatalize, then optionally
> weaken further) is presented as the source's clearest case of two of its named adjustment
> processes feeding each other in the noun-suffix environment specifically — contrasted with 같아요
> "it's the same," where ㅌ is a *verb* stem-final consonant (not a noun root), so neither
> palatalization nor weakening applies and ㅌ keeps its plain aspirated pronunciation, [가타요].
> pp. 92–95

---

## Grammar points

### 1. Overall organization and the spelling-vs.-pronunciation gap (Ch. 1)

The book frames its whole project around one core problem: Korean's alphabet (한글) is highly
systematic, but a word's *spelling* frequently diverges from its actual *pronunciation* once
regular, rule-governed "adjustment" processes (Ch. 4) apply in connected speech. Ch. 1 previews the
book's own three-part structure (Vowels, Consonants, Adjustments) and stresses a pedagogical point
relevant to any learner-facing phonology source: many of the pronunciation adjustments that make
Korean sound natural are *not* reflected in standard spelling at all, so a learner reading Korean
literally, syllable-by-syllable from the Hangul, will systematically mispronounce many everyday
words unless the adjustment rules are separately learned. pp. 3–7

### 2. Vowel system: three-feature harmonic-adjacent contrasts, and two ongoing mergers (Ch. 2)

The **simple vowel inventory** is presented through paired minimal contrasts rather than a bare
IPA chart, mirroring how the book teaches each sound relative to its nearest phonetic neighbor:
ㅗ vs. English "o" (Korean ㅗ lacks the English off-glide /w/ found in "low"); ㅓ vs. ㅏ (produced with
tongue further back/higher for ㅓ, more forward/lower for ㅏ); ㅜ vs. ㅡ (rounded/unrounded
counterparts at the same backness). Two **ongoing sound mergers** are explicitly documented as
synchronic facts about contemporary Korean, not historical background:
- **ㅔ vs. ㅐ (e vs. ae):** "essentially merged" for virtually all speakers today, even though the
  spelling distinction is fully maintained (including in English loanword spelling — 벨 'bell' vs.
  애플 'apple'). One synchronic lexical consequence is directly cited: the possessive 네 'your' has
  developed a distinct colloquial pronunciation [니] specifically to stay distinguishable from 내
  'my', now that the *written* 에/애 distinction no longer reliably signals a *pronunciation*
  distinction.
- **ㅚ vs. ㅟ vs. 웨-type sequences:** a three-way convergence, where the diphthongs ㅚ, ㅞ, and (in
  careful speech only) ㅙ are "routinely pronounced alike," collapsing toward [we]-type
  pronunciation; the source notes there are correspondingly few minimal pairs testing these
  contrasts in the language, since the merger has already reduced functional load there.

**Diphthongs** are organized into two symmetric families — six 'y'-initial (야, 여, 요, 유, 얘, 예) and
six 'w'-initial (와, 워, 왜, 웨, 위, 외) — each formed by combining the glide with an independently-
attested simple vowel, except **의**, which the source treats as structurally exceptional (the glide
follows rather than precedes the vowel). **의 itself is shown to have three conditioned
pronunciations** depending purely on position, independent of any surrounding-consonant
conditioning: word-initial → full diphthongal [ɰi] (careful speech; often reduced further in fast
speech); as the possessive suffix → simple [e]; everywhere else (i.e., after an onset consonant in
a non-suffix position) → simple [i]. This three-way split from one written vowel is presented as
the single richest positional-allophony case in the vowel system. pp. 9–20

### 3. Consonant system: a three-way laryngeal contrast unlike English's two-way one (Ch. 3)

Korean's obstruents contrast in **three** manners at each place of articulation — **lax** (ㅂㄷㄱㅈㅅ),
**tense** (ㅃㄸㄲㅉㅆ), and **aspirated** (ㅍㅌㅋㅊ) — rather than English's two-way voiced/voiceless
distinction. This is the book's central typological point about the consonant system, developed
identically across the labial (ㅍ/ㅂ/ㅃ), coronal (ㅌ/ㄷ/ㄸ), velar (ㅋ/ㄱ/ㄲ), and affricate (ㅊ/ㅈ/ㅉ)
series: **lax consonants are not the same thing as English voiced consonants** — Korean lax
stops/affricates are actually voiceless (with mild aspiration) in word-initial position, and only
become voiced allophonically between voiced sounds (see Adjustments, §4.2). Tense consonants
involve extra "muscular effort"/glottal constriction with no accompanying aspiration puff, and are
articulated with a noticeably higher, tenser pitch onset on the following vowel — a cue the source
recommends L2 learners actually rely on more than tenseness itself, since the auditory "tenseness"
sensation is hard to reproduce directly.

ㅅ/ㅆ (fricatives) pattern slightly differently from the stop/affricate series: **there is no
aspirated member of the ㅅ series** — only a lax/tense two-way contrast (ㅅ vs. ㅆ) — one of the
few systematic gaps in the otherwise-symmetric three-way system, and the source flags ㅅ's phonetic
realization as unusually variable (ranging toward [ɕ]/[s] depending on the following vowel).

**ㅎ** is treated as a special case with no lax/tense/aspirated set-mate at all — a single laryngeal
fricative whose behavior (frequent weakening/deletion between voiced sounds, and its role as an
aspiration trigger — see §4.7) is developed almost entirely in the Adjustments chapter rather than
here.

**Nasals (ㅁ, ㄴ, ㅇ)** and **ㄹ** (a flap [ɾ] in onset position, a lateral [l] in coda position) are
treated as sonorants outside the three-way laryngeal system, but ㄹ and the nasals turn out to be
the single most active class of triggers for the Adjustments chapter's rule set (nasalization,
ㄴ-as-if-ㄹ, ㄹ-as-if-ㄴ, tensing exemptions). An appendix (§3.9) gives further phonetic-mechanics
detail (VOT measurements, aspiration duration) explicitly marked as optional background not
required for the practice exercises. pp. 21–57

### 4. Full closure — the single mechanism explaining several "same pronunciation, different
   spelling" surprises

**Full closure** (glossed formally in the book's own Glossary) is the generalization that any
consonant occurring immediately before another consonant, or at the absolute end of an utterance,
loses its release and its aspirated/lax/tense distinctiveness, merging toward one of three coda
categories: [ㅂ], [ㄷ], or [ㄱ]-type unreleased stops. The book's own count: **eleven distinct
consonant letters — ㅍ, ㅂ, ㅌ, ㄷ, ㅊ, ㅈ, ㅅ, ㅆ (all converge to [ㄷ]-type), plus ㅋ, ㄲ (both converge
to [ㄱ]-type), plus ㅂ/ㅍ to [ㅂ]-type** — "come down to just three sounds" once full closure applies,
and this three-way collapsed set is exactly what then feeds the nasalization rule (§4.9) as its
class of "ordinary consonants" input. This single generalization is presented as the anchor
explaining why so many superficially different spellings converge on identical pronunciation once
a following consonant or word-boundary triggers it. p. 77 and throughout Ch. 4

### 5. The Adjustments chapter's rule inventory (Ch. 4) — Korea's system of connected-speech sandhi

This is the book's largest and most information-dense chapter, systematically covering fifteen
named adjustment processes. Each is presented with the same template (rule statement, a small
table of examples with "before/after" pronunciations, a boxed formal summary, and a note on whether
the rule can apply *across a word boundary* — a recurring, explicitly-flagged property of Korean
connected speech that has no equivalent teaching point in English). The processes, in the book's
own order:

- **4.1 Consonant relinking** — a coda consonant is re-syllabified onto a following vowel-initial
  syllable (언어 'language' → [어너]), the general "resyllabification" mechanism that several later
  rules build on.
- **4.2 Voicing** — lax consonants (ㅂ,ㄷ,ㄱ,ㅈ) become voiced between voiced sounds (시간 'time' →
  [ㄱ] realized as [g]-like); shown in Ch. 5 to be blocked by an intervening high-pitch/focus break.
- **4.3 Diphthong reduction**, **4.4 Contraction**, **4.5 Special vowel changes** — fast-speech
  vowel-sequence simplifications.
- **4.6 ㅎ reduction** — ㅎ is weakened/dropped between voiced sounds (영화 'movie' → [영와]); also
  shown in Ch. 5 to interact with focus/pitch placement.
- **4.7 Aspiration** — a lax consonant adjacent to ㅎ (in either order) surfaces as its aspirated
  counterpart (ㄷ+ㅎ→ㅌ, etc.) — directly feeds the palatalization cascade in the 닫혀요/다쳐요 example
  above.
- **4.8 ㄴ-as-if-ㄹ / ㄹ-as-if-ㄴ** — a genuinely bidirectional, morphology-sensitive assimilation
  between ㄴ and ㄹ (see the 정신력/신문로 morpheme breakdown above for the key semantic-bracketing
  finding).
- **4.9 Nasalization** — ordinary (fully-closed) consonants become nasal before a following nasal
  (ㅁ/ㄴ); a distinct sub-case nasalizes ㄹ specifically after a non-ㄴ/ㄹ consonant.
- **4.10 ㄴ-as-if-ㅁ-or-ㅇ** — ㄴ optionally assimilates in place to a following labial or velar.
- **4.11 Addition of ㄴ** — an epenthetic ㄴ appears at the start of certain compounds/phrases before
  ㅣ or a y-diphthong; the source gives a systematic **three-way compound-type typology** (classic
  compounds of two independent words; semi-compounds of a word + bound root; compounds of two bound
  roots) with addition of ㄴ typical in the first two types but essentially absent in the third —
  a genuinely graded, compositionality-sensitive phonological rule, not a uniform one. Explicit
  lexical exceptions are flagged (독약 'poisonous drug' never gets ㄴ; the verb 있다 never triggers
  it).
- **4.12 Tensing**, split into **predictable** (fully regular after any non-ㄹ/non-nasal consonant,
  including across word boundaries; regular but more restricted after ㅎ, where only ㅅ tenses) and
  **nonpredictable** (lexically-specified tensing after a vowel or after ㅁ/ㄴ/ㅇ/ㄹ — e.g. 시가
  'market price' [시까] vs. homographic 시가 'city streets' [시가], with no general rule
  distinguishing them). A footnoted sub-regularity is captured: the bound noun 것 (contracted to
  기) tenses after a future-tense modifier (-을 것 → [-을 껏]) but not after present/past modifiers —
  a genuinely fine-grained morphosyntactic conditioning environment.
- **4.13 ㅅ-insertion (사이 시옷)** — a native-Korean-component-only compounding rule, see the
  바닷가/나뭇잎 morpheme breakdowns above.
- **4.14 Modifications to ㄷ and ㅌ** — palatalization before a suffix-initial ㅣ or 여 (ㄷ→ㅈ, ㅌ→ㅊ);
  restricted specifically to the suffix boundary (마디 'knuckle', with root-internal ㅣ, never
  palatalizes).
- **4.15 Consonant weakening** — two sub-processes specific to noun roots before a vowel-initial
  suffix: ㅍ/ㅋ optionally weaken (and voice) to ㅂ/ㄱ; ㅌ/ㅊ optionally weaken further to ㅅ. Both are
  explicitly noted as *not yet fully established* / still variable across speakers — a rare
  explicit in-progress-sound-change flag from the source itself, and lexically exempted in a
  handful of common nouns (앞 'front', 옆 'side', 잎 'leaf' — the last one specifically flagged as
  resisting weakening to avoid a homophony clash with 입 'mouth'). pp. 58–96

### 6. Prosody: pitch/length instead of English-type stress, and a "first-syllable-high" default
   (Ch. 5)

This chapter is the book's second major typological claim, parallel in importance to the three-way
laryngeal contrast in Ch. 3: **Korean has no English-type lexical stress system at all.** Where
English marks prominence through loudness at roughly regular intervals (content words stressed,
function words unstressed; stress can even be lexically contrastive, *REcord* vs. *reCORD*),
**Korean syllables are pronounced with roughly equal loudness**, and prominence instead comes from
**pitch** (the first syllable of a word tends to carry slightly higher pitch by default) and
**length** (the final syllable of a phrase/sentence is characteristically longer/more audible than
the others — the opposite end-weighting from English, where sentence-final syllables are typically
short and weak). The source explicitly frames this as a common source of foreign-accent unnaturalness
for English-speaking learners, who tend to import English's stress-on-a-middle-syllable pattern
onto longer Korean words and under-articulate Korean's own prominent final syllable.

**Focus** (§5.2) is the mechanism for marking new/important information via extra-high pitch,
usually on the first syllable of the focused word — largely parallel to English focal stress, with
two Korean-specific complications the source highlights: (1) the copula -이다 cannot itself carry
focus (it can never stand alone as an independent word), so emphasis is redirected onto the word it
attaches to; (2) Korean's *wh*-words (누구 'who', 뭐 'what', 어디 'where', etc.) are **structurally
ambiguous between interrogative and indefinite-pronoun readings** ('who' vs. 'someone', 'where' vs.
'somewhere', etc.), and **focus placement alone disambiguates which reading is intended** — 어디
가? with focus on 어디 asks "where are you going?"; with focus shifted onto 가 instead, the very same
string becomes a yes/no question, "are you going somewhere?" This is presented as a genuinely
distinct grammatical function for pitch/focus that has no direct English parallel (English
disambiguates the same ambiguity via sentence stress *and* often word choice, not pitch placement
alone).

**The pitch-focus/adjustment-rule interaction (§5.2, "effect of pitch on adjustments")** is a
cross-cutting finding tying Ch. 4 back into Ch. 5: a high pitch placed on the *second* word of a
two-word sequence creates a prosodic "break" that **blocks** three otherwise-regular adjustment
processes from applying across that word boundary — ㅎ-reduction, tensing, and voicing all fail to
apply when the second word carries focal high pitch, even though they would apply freely if the
same two words were pronounced without that focus. This means the same segmental string can
surface with measurably different consonant realizations purely as a function of where sentence
-level pitch/focus falls — a genuinely prosody-conditions-segmental-phonology finding, worth noting
for any future analysis of playful/marked pronunciation in Korean slang (a speaker manipulating
focus placement is, among other things, manipulating whether these adjustment rules apply at all).

**Intonation (§5.3)** functions specifically to distinguish sentence types that are *structurally
identical* in Korean (unlike English, which usually also moves an auxiliary verb for questions):
falling/flat = neutral statement; rising = yes/no question; *wh*-questions can go either way (rising
= softer/friendlier, falling = curter/more demanding — itself a register-like pragmatic distinction
carried by intonation alone); commands can be falling (blunt) or a prolonged rising contour (softer,
explicitly noted as more typical of women's speech than men's — a sourced gendered-register
observation); strong conjecture (-걸 ending) takes rising intonation; exclamation/surprise takes
"dramatic tone" (extra pitch range); and a boastful/close-friend -다 statement sharing new
information takes rising intonation specifically in that pragmatic context, contrasting with -다's
otherwise-neutral falling default.

**Intonation and emotion (§5.4)** is presented as inherently non-rule-governed: the same lexical
material can shift between admiration, sarcasm, resentment, regret, etc., purely via pitch contour,
and the source explicitly declines to offer any simple formula for this, unlike the more
categorical sentence-type generalizations in §5.3. Two same-ending minimal-function-pairs are
flagged as needing intonation to disambiguate: -지 can mark either a gentle suggestion or an
expression of regret; -걸 can mark either regret or strong conjecture (this is the same -걸 as the
§5.3 "strong conjecture" case — the source is explicit that ending choice alone underdetermines
meaning and intonation carries the rest of the semantic weight).

**Thought groups (§5.5)** are the level above the individual word: longer sentences are chunked into
prosodic units (marked by a short pause and a lengthened final syllable per group), and — critically
— **thought-group boundary placement is not free variation; it can change a sentence's meaning
outright.** The book's central example: 너 밖에 안 나가? (pause after 너) means "Aren't you going
outside?" (밖에 read as a locative phrase, 'outside'), while 너밖에 안 나가? (pause after 밖에, or no
pause at all) means "Is no one but you going out?" (-밖에 read as the exclusive particle 'except').
The two readings additionally correlate with the Ch. 4 adjustment-rule findings: because -밖에 (the
particle reading) is itself a focused word with high pitch on its first syllable in the first
parse, it blocks voicing of its own ㅂ in that reading but not in the particle-final reading — tying
together prosody, thought-group segmentation, and segmental adjustment as one coherently
interacting system, which is exactly the picture Ch. 5 as a whole is built to establish. pp. 96–107

---

## Relevance to Korean's morphological/phonological typology profile

This source is the strongest phonological-typology input Korean has received in this project so
far, and several findings are worth flagging explicitly for the language's typology profile
(`../00_Extraction_Checklist.md`) alongside its established agglutinative-morphology
characterization:

1. **The three-way lax/tense/aspirated laryngeal contrast** (Ch. 3) is the single most
   phonologically distinctive feature of Korean relative to virtually every other language this
   project has covered so far (Hungarian, Serbian/Croatian/Bosnian, Dutch) — none of those languages
   have a three-way manner contrast at every obstruent place of articulation. Any future
   `morphological_play`/slang-mechanics analysis involving consonant substitution or exaggeration in
   Korean slang should be checked against this three-way system specifically (e.g., a slang
   intensifier that shifts a lax consonant to its tense counterpart, parallel to the source's own
   note that optional tensing of native adjective-initial consonants — 세다 vs. 쎄다 — independently
   signals intensity, 'it's strong' vs. 'it's very strong').
2. **A rich, ordered cascade of connected-speech sandhi rules** (Ch. 4's fifteen adjustment
   processes) sits on top of the agglutinative morphology already documented for this language —
   meaning many "words" in the sense of the project's Word-Concept guide undergo real segmental
   change at their own internal morpheme boundaries (stem+suffix) *and* at word-boundary junctures
   in a compound or connected phrase, with these two levels sometimes feeding each other (as in the
   막일/나뭇잎 morpheme-breakdown cascades above). This is a genuinely different flavor of
   "agglutinative surface complexity" than Hungarian's vowel-harmony-driven suffix alternation or
   Finnish's stem-final consonant gradation — Korean's complexity is much more about *sequential,
   rule-ordered segmental adjustment* than about feature-harmony-driven suffix selection.
3. **Pitch/prosody (not stress) as the locus of information-structure marking** (Ch. 5) is a new
   typological dimension not previously documented for any language in this project — worth
   recording as its own axis alongside morphological typology, since a future Korean
   slang-mechanics analysis of emphasis/exaggeration effects will need to reason about pitch
   placement and thought-group boundaries, not stress placement, as the relevant mechanism.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — no bulk reproduction of the source's own example
tables, boxed rule summaries, or explanatory prose beyond the short illustrative fragments needed
to make each finding concrete. Practice-exercise content (Part II) was not read or extracted at all,
consistent with the coverage rule. See `../../00_Reference_Extraction_Spec.md`.
