# Japanese — Established Vocabulary/Grammar: An Introduction to Modern Japanese, Vol. 1 (Grammar Lessons)

**Source:** Richard Bowring & Haruko Uryū Laurie, *An Introduction to Modern Japanese, Book One:
Grammar Lessons* (Cambridge University Press), 498-page scanned DJVU, no text layer (vision-read).
52 numbered lessons (printed pp. 33–467) preceded by a substantial front-matter "Introduction"
(printed pp. 1–30: writing system, phonology, loanwords, dialects, writing styles) and followed by
appendices + index (printed pp. 471–479).

**Coverage note — representative sampling across a 498-page/52-lesson course, per dispatch
instructions.** This is Japanese Wave 3 (Audio Courses, Textbooks). Given the book's scale, full
page-by-page extraction of all 52 lessons was not feasible in one dispatch. Strategy used:
- **Front matter (Introduction):** kept brief — the kana/kanji writing-system material here heavily
  duplicates existing `established/001`–`025`-range files (dedicated hiragana/katakana/kanji
  references). Only non-redundant content is captured: the explicit **Dialects** section (§4,
  printed p. 21–22) per the extraction spec's standing rule to never skip explicit dialectal/
  regional annotation, plus the loanword/katakana table and writing-styles-by-period table, both of
  which are distinctive to this source.
- **Lessons 1, 2, and 6 extracted in full** (the true grammatical bedrock — demonstratives, copula,
  は, の, true vs. descriptive verbs, locative に, negatives). Some of this content (core particle
  functions) also exists in this project's dedicated particle dictionaries (032, 034, 036), but is
  kept here in full per the dispatcher's "extract early lessons more fully" instruction, since this
  source's worked dialogue-based presentation and its explicit grammar-point-by-grammar-point
  numbering differs from those references and the book's own Comment/Key-to-sentences structure is
  distinct source material. Lessons 3–5, 7–8 were not independently read this dispatch (flagged in
  the Lessons 3–8 section below rather than silently skipped).
- **Lessons 9–52: representative sampling**, chosen to hit genuinely new/high-value grammatical
  mechanisms as they're introduced rather than by even spacing. This dispatch's samples: **Lesson
  31** (the giving/receiving verb system — あげる/くれる/もらう family — a flagship Japanese
  mechanism not previously captured anywhere in this project's `established/` set), **Lesson 34.6**
  (potential form), **Lesson 35.1** (the passive, including its adversative/"suffering" use),
  **Lesson 37.3–37.4** (the causative/permissive form), and **Lesson 49.1–49.3** (the book's own
  honorific-language synopsis chapter, including an explicit politeness-vs-honorific two-axis
  terminological distinction). Lessons not sampled are listed by number and topic (from the table of
  contents) in the "Lessons not sampled" note after the Lesson 34.6 section, so the scope gap is
  auditable rather than silent.
- **Vision-reading guard:** no handwritten marginalia was found on any page read for this extraction
  — all content read was clearly typeset. Scan quality was good throughout; no low-confidence reads
  were needed except where noted per-row.
- **Page-offset gotcha (PDF/DJVU):** `djvu_page = printed_page + offset` does **not** hold a single
  constant offset across this source — confirmed empirically, not assumed. Offset = 19 from the
  Introduction through Lesson 2 (djvu20=printed1, djvu52=printed33 the start of Lesson 1); offset
  drifts to 16 by the Lesson 31–49 region (djvu283=printed267, djvu442=printed426); offset returns
  to 19 again near the back (djvu480=printed464 in Lesson 52, djvu495=printed479 the Index). The
  drift is a few pages' worth of unnumbered content inserted somewhere in the first third of the
  book (not identified precisely — not a concern for this extraction, but relevant if a continuation
  dispatch estimates page ranges from the formula alone). **Every page actually used in this file
  was verified against its own printed page number, not computed from the formula** — per the
  extraction spec's standing "verify the offset empirically" rule.

---

## Front matter: Introduction (printed pp. 1–30) — non-redundant supplement only

### Loanwords / katakana (Table 19, p. 21)

The Introduction's loanword table documents the regular phonological adaptation pattern English/
European loanwords undergo in katakana transcription — consonant-final words gain an epenthetic
vowel, /l/ merges with /r/, consonant clusters are broken up:

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| ポテト (poteto) | potato | noun | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | loanword |
| ゲーム (gēmu) | game | noun | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | loanword |
| ナイフ (naifu) | knife | noun | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | loanword |
| ミルク (miruku) | milk | noun | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | loanword |
| サラダ (sarada) | salad | noun | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | loanword |
| テント (tento) | tent | noun | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | loanword |
| チケット (chiketto) | ticket | noun | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | loanword |
| チップ (chippu) | tip (gratuity) | noun | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | loanword |
| ラジオ (rajio) | radio | noun | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | loanword |
| ディスコ (disuko) | disco | noun | colloquial | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | loanword |
| ロケット (roketto) | rocket | noun | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | loanword |
| バケツ (baketsu) | bucket | noun | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | loanword |
| ポケット (poketto) | pocket | noun | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | loanword |

Also tabulated: katakana transliteration of foreign proper names (ルイス *Ruisu* "Lewis", ルノワー
ル *Runowāru* "Renoir", ロンドン *Rondon* "London", ベニス *Benisu* "Venice", ベトナム *Betonamu*
"Vietnam", ベルギー *Berugī* "Belgium", スミス *Sumisu* "Smith", サッチャー *Satchā* "Thatcher") —
illustrating that katakana is the default script for any foreign-origin name, not just common nouns.

### Dialects (§4, printed pp. 21–22) — explicit dialectal/regional content

The book states dialect variation within Japan is comparable in richness to major European
countries, with many dialects "almost mutually unintelligible." Two independent axes of dialect
classification are named:

1. **Vocabulary/verb-inflection East–West split**, running north–south through a line just west of
   Nagoya.
2. **Pitch-accent variation**, described as a "more complicated doughnut situation": the Kyōto/Ōsaka
   accent group differs from a group shared by *both* eastern Japan *and* far-western Japan, which
   show clear similarities to each other despite being geographically distant — i.e. pitch-accent
   isoglosses do not track the same East–West line as vocabulary/inflection.

Historically, the prestige standard shifted from Kyōto (from earliest times to the 18th century) to
Edo/Tōkyō (from the end of the 18th century on). Educated Tōkyō speech is the modern broadcast
standard. The text explicitly notes **social stigma attaches to accents from the north and the far
south**, in rough proportion to how incomprehensible they are to outsiders — a directly
sociolinguistic framing of register/regional stigma that this project's slang-mechanics analysis
phase should find useful (taboo/stigma-driven register dynamics, not just neutral regional
variation).

### Writing styles by era (Table 20, p. 23) — register/style history, not vocabulary

A period-by-period table (Nara 710–94 through post-war) tracks which written registers were used for
which purposes: Classical Chinese for official documents/histories across most of this span; two
intermediate "Sino-Japanese" registers (1 = Chinese-looking but Japanese underlying structure, 2 =
Japanese with heavy Chinese-loanword density); and "Pure Japanese" for poetry/fiction, with kana's
invention in the Heian period enabling female-authored writing for the first time. Cited: a recent
(as of publication) survey found words of Chinese origin made up only ~24% of typical *spoken*
conversation but ~77% of written newspaper language — a striking spoken/written register-density
gap, directly relevant to how a derived slang register might similarly diverge from a "literary"
high register.

**Skipped as redundant:** the Introduction's hiragana/katakana syllable-chart tables (Tables 2, 10,
11, 12) and the stroke-order practice sheets (pp. 26–31) — these duplicate `established/001`
(*A Guide to Hiragana & Katakana*) and `established/020` (*Remembering the Kana*) in full.

---

## Lesson 1 (printed pp. 33–38) — demonstratives, は, copula, yes/no

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| これ (kore) | this (thing, near speaker) | demonstrative pronoun | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | — |
| それ (sore) | that (thing, near listener) | demonstrative pronoun | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | — |
| あれ (are) | that (thing, far from both) | demonstrative pronoun | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | — |
| は (wa) | topic/contrast particle | particle | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | written は (ha), pronounced wa |
| です (desu) | copula ("is", equivalence not existence) | copula | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | final u devoiced: "des" |
| 何 (nan/nani) | what | interrogative noun | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | なん before copula |
| か (ka) | sentence-final question particle | particle | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | — |
| はい (hai) | yes / "I'm following you" | interjection | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | functions more like active-listening token than strict affirmation |
| ええ (ē) | yes (colloquial) | interjection | colloquial | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | more common in daily conversation than はい; noted as more frequent from women speakers |
| そう (sō) | so, correct | adverb/pro-form | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | substitutes for repeating a whole question |
| いいえ (iie) | no | interjection | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | — |
| ではありません (de wa arimasen) | negative copula ("is not") | copula (negative) | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | written では obligatory; see じゃ below |
| じゃありません (ja arimasen) | negative copula, spoken contraction | copula (negative) | colloquial | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | spoken-only contraction of では; text explicitly flags では as obligatory in writing |
| 本 (hon) | book | noun | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | — |
| えんぴつ (enpitsu) | pencil | noun | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | — |
| ペン (pen) | pen | noun | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | katakana loanword |
| ノート (nōto) | notebook | noun | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | katakana loanword |
| かぎ (kagi) | key | noun | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | — |
| ふで (fude) | (writing/calligraphy) brush | noun | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | — |
| めがね (megane) | glasses | noun | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | — |
| いす (isu) | chair | noun | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | — |
| つくえ (tsukue) | desk | noun | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | — |
| ラジオ (rajio) | radio | noun | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | katakana loanword |
| テレビ (terebi) | television | noun | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | katakana loanword, clipped from "television" |
| 木 (ki) | tree | noun | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | — |
| 花 (hana) | flower | noun | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | — |
| かさ (kasa) | umbrella | noun | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | — |
| 山 (yama) | mountain | noun | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | — |
| 川 (kawa) | river | noun | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | — |

### Grammar points

#### 1.1 これ/それ/あれ ("this thing"/"that thing"/"that thing over there")
Demonstrative *pronouns* (stand alone, unlike これ's prenominal cousin この — see 2.3). Three-way
distance system: これ = near speaker, それ = near listener, あれ = far from both. The book notes the
distinction is felt strongly in Japanese and that convention governs cross-turn reference: one
typically *responds* with これ to a question containing それ, and vice versa — the deictic center
shifts with the speaking turn. あれ is used only when both speakers are equally distant from the
referent.

#### 1.2 The particle は
Topic/contrast particle, orthographically irregular (written with the kana for *ha* but pronounced
*wa*). Two functions introduced here: (a) marking the topic/theme of the sentence, (b) implying
contrast. Distinguished explicitly from "subject" — topic/theme is a distinct grammatical category
from subject, elaborated in later lessons.

#### 1.3 The copula です
です translates as "is" but is explicitly *not* the same category as a full Japanese verb — it
cannot stand alone, and its core meaning is **equivalence** (A = B), not existence. This existence/
equivalence split is flagged as a concept English conflates (via "to be") that Japanese keeps
grammatically separate from the start. No particle is needed on the noun immediately preceding です.

#### 1.4 Asking a question
何 ("what") + か (question particle) pattern. Word order: noun–topic marker–noun–copula, unchanged
between statement and question (unlike English subject-auxiliary inversion) — か is simply appended.

#### 1.5 "Yes" (はい/ええ)
Both translate "yes" but function closer to "I understand"/"I'm following you" than strict logical
affirmation — flagged as a common source of listening-comprehension confusion for learners, since
はい/ええ do not always mean straightforward agreement. When responding to a question with content
beyond a yes/no, speakers either repeat the question minus か, or substitute そう ("correct"/"so").

#### 1.6 "No" (いいえ)
Negative responses require the negative copula ではありません (contracted spoken じゃありません).
は here functions as the *contrastive* は (1.2's function (b)), not the topic は.

---

## Lesson 2 (printed pp. 39–44) — の modification, だれ/どなた, この/その/あの, 私/あなた

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| の (no) | possessive/attributive connector particle | particle | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | links noun1→noun2, noun1 modifies noun2 |
| 私 (watakushi) | I, me | pronoun | formal | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | book explicitly warns against overuse — frequent self-reference reads as presumptuous |
| あなた (anata) | you | pronoun | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | book explicitly warns against overuse — name + さん preferred |
| だれ (dare) | who | interrogative pronoun | colloquial | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | more abrupt than どなた |
| どなた (donata) | who (polite) | interrogative pronoun | formal | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | preferred register unless familiarity licenses だれ |
| この (kono) | this (prenoun) | prenoun | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | cannot stand alone, unlike これ; = こ + の historically |
| その (sono) | that (prenoun) | prenoun | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | — |
| あの (ano) | that over there (prenoun) | prenoun | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | — |
| 方 (kata) | person (polite) | noun | formal | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | この方/その方/あの方 "this/that person" — same near/far discipline as こ/そ/あ series applies to people, not just objects |
| さん (san) | polite address suffix | suffix | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | attaches to family name (or given name among close friends) |
| 友達 (tomodachi) | friend | noun | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | — |
| 弟 (otōto) | younger brother | noun | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | — |
| 妹 (imōto) | younger sister | noun | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | — |
| 兄 (ani) | older brother | noun | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | — |
| 先生 (sensei) | teacher | noun | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | — |
| 男の子 (otoko no ko) | boy | noun phrase | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | noted as structurally ambiguous with "man's child" out of context |
| 女の子 (onna no ko) | girl | noun phrase | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | — |
| 車 (kuruma) | car | noun | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | — |
| 絵 (e) | picture, painting | noun | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | — |

### Grammar points

#### 2.1 Noun modification with の
Core rule: *the first noun modifies the second* (N1 の N2). The English gloss varies by relation
type — possession (私の本 "my book") vs. attribution (木のつくえ "a wooden desk") — but Japanese
uses one particle for both. Flagged ambiguity case: 男の子 can mean either "man's child" or "boy"
depending on context, illustrating の's semantic breadth cutting both ways (economy vs. ambiguity).
The second noun can be elided in an answer when recoverable from the question (あれは兄のかさです
→ あれは兄のです, "that's my brother's [umbrella]"), directly parallel to English possessive-of-
omission.

#### 2.2 だれ/どなた ("who"/"whose")
だれ is more abrupt; どなた is the default polite choice. A subtler distinction: だれ is used when
asking an *impersonal* fact (who painted this?), どなた when a *personal relationship* is implicated
(whose is this?) — illustrated with a minimal pair (あれはだれの絵ですか vs これはどなたの絵です
か).

#### 2.3 この/その/あの (prenouns)
A distinct grammatical category from これ/それ/あれ: these **cannot stand alone**, must directly
precede a noun with no intervening particle (unlike の-linked noun+noun). Function as demonstrative
adjectives. With people, こ の方/その方/あの方 follows the *same* proximity discipline as with
objects — illustrated with an extended analogy to the English politeness violation of saying "is
she your sister's teacher?" about someone standing within earshot (その方 would be wrong there; この
方 required).

#### 2.4 "I" and "you" (私/あなた)
Explicit sociolinguistic caution: **both words are structurally nouns in Japanese** (私 literally
"private/secret", あなた literally "that side over there"), not a grammaticalized personal-pronoun
class the way English "I"/"you" are. The general rule given is to **avoid both wherever possible**
— frequent self-reference reads as presumptuous, and Japanese sentences routinely omit an explicit
subject once context establishes it (the book calls these "subjectless" sentences, revisited at
Lesson 45.3). For second-person address, family name + さん is the default, not あなた.

---

## Lesson 6 (printed pp. 72–73) — true verbs いる/ある, particle に, negatives of true verbs

### Grammar points

#### 6.1 True verbs
いる and ある both translate "is/exist" but split on **animacy of the subject/topic**: いる for
animate referents, ある for inanimate — explicitly including **plants**, which the book flags as
grammatically inanimate despite being biologically alive. This is the first "true verb" the course
introduces, contrasted with the copula です (equivalence, not existence) from Lesson 1.3. True verbs
are sentence-final and, like the copula, do not inflect for person or number.

#### 6.2 The particle に
Marks the location *in or at which* something exists (locative), usable with both animate and
inanimate subjects — distinct from the particle で's locative-of-action use introduced later.

#### 6.3 Negatives of true verbs
いません (negative of いる) / ありません (negative of ある) — the full negative-formation system is
deferred to Lesson 15, this is an early preview tied to just these two verbs.

#### 6.4 More on は
Revisits は's contrastive function (1.2(b)) using いません/ありません sentences as the worked
example — contrastive は surfaces naturally once negation is introduced, since "X is not present [in
contrast to Y]" is a canonical contrastive-は context.

---

## Lessons 3–5, 7–8 (printed pp. ~45–71, ~80–93): foundational grammar — summary of scope, not
independently captured this dispatch

Per the TOC, this stretch covers: Lesson 3 (likely further descriptive basics), Lesson 4 (family-
member reference terms, more interrogatives, the subject marker が, numbers), Lesson 5 ("excuse me",
time, asking directions, particle よ, name-card exchange conventions, telephone numbers, は as topic
marker revisited, particle ね), Lesson 7 (clock time, tense/aspect, particles で/を/から/まで/に in
spatial contexts), Lesson 8 (verbal nouns, days of the week, particle で, linking particle や,
orthography note). **These five lessons were not independently vision-read this dispatch** — flagged
here rather than silently skipped, per the spec's auditability requirement. A continuation dispatch
should read these before moving to deeper sampling, since Lesson 4 (が vs は) and Lesson 7
(tense/aspect) are foundational enough to warrant the same full treatment given Lessons 1, 2, and 6.

---

## Lesson 31 (printed pp. 263–267) — giving/receiving verbs (あげる/くれる/もらう family) and keigo subject-raising/lowering

**Flagged as the single highest-value grammar-mechanism gap this dispatch closes**: this project's
`established/` set did not previously contain the donatory/receptive ("giving and receiving") verb
system, one of Japanese grammar's most distinctive and frequently cited mechanisms, tightly bound to
the keigo politeness system (verb choice encodes social direction of the gift, not just literal
"give"/"get"). Captured here via its grammar explanation boxes (31.3–31.7), not the dialogue
practice material, per copyright discipline.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 差し上げる (sashiageru) | to give (humble, "offer up") | verb (group II) | formal | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | used when giving to a social superior |
| 上げる (ageru) | to give (neutral) | verb (group II) | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | used when giving to an equal |
| やる (yaru) | to give (condescending, "offer down") | verb (group I) | colloquial | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | used giving to inferiors, animals, plants — book's own example: 水をやる "give it water" |
| 下さる (kudasaru) | to give to me/us (respectful, "bestow") | verb (group I, irregular) | formal | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | used when a social superior gives to the speaker |
| くれる (kureru) | to give to me/us (neutral, "let have") | verb (group II) | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | used when an equal gives to the speaker |
| いただく (itadaku) | to receive (humble, "receive from above") | verb (group I) | formal | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | used when the speaker receives from a superior |
| もらう (morau) | to receive (neutral, "get") | verb (group I) | core | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | agent marked by に or から |
| 様 (sama) | honorific address suffix | suffix | formal | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | one register above さん |
| 申す (mōsu) | to say (humble) | verb (group I) | formal | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | root of 申し訳ございません "there is no excuse" (lit. humble-say + わけ "reason") |
| おる (oru) | to be/exist (humble, replaces いる) | verb (group I) | formal | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | — |
| でいらっしゃいます (de irasshaimasu) | respectful copula form | copula (respectful) | formal | — | contemporary (source published 1992) | — | — | grammar_reference | n/a | verified | used only referring to the addressee or someone closely connected to them |

### Grammar points

#### 31.2 (context, not separately numbered above) Inside/outside (内/外) governs keigo choice over hierarchy
Worked example: a company employee (Fujimoto) fielding an outside call about her own superior
(Hasegawa) **must not** use an honorific about Hasegawa when speaking to an outsider — "the
'inside' versus 'outside' relationship will always take precedence over the more parochial
relationship [of internal rank]," even though internally she would honor him with さん/honorific
verbs. This is presented as a general principle governing all Japanese honorific choice, not a
one-off exception — relevant for any in-universe conlang slang/register system this project
eventually derives, since it shows register choice is **relational/contextual, not a fixed property
of the referent**.

#### 31.3–31.6 Giving and receiving — a four-direction verb system
The core mechanism: Japanese has **no single neutral verb for "give"/"receive"** the way English
does — verb choice is forced to encode the *social direction* of the gift (up, level, or down) and
*who the speaker's viewpoint is anchored to* (giving out vs. receiving in). Four sub-cases, worked
through a single recurring character's (Tadashi's) social relationships:
- **Giving out** (31.4): subject is "I" — 差し上げる (to a superior, teacher) / 上げる (to an equal,
  a friend) / やる (to a younger sibling, a pet, or a plant — explicitly "he can look down on" these
  three categories linguistically).
- **Giving in** (31.5–31.6): subject is the donor, not "I" (so no passive construction is used,
  despite the English translation sounding passive) — 下さる (a superior gives to me) / くれる (an
  equal gives to me).
- **Receiving** (31.6): subject is "I" again — いただく (receiving from a superior) / もらう
  (receiving from an equal); the agent/donor can be marked with に or から interchangeably.
The same underlying event ("Professor Hara gave me a ticket") is thus grammatically obligatory to
encode from *either* the giving or receiving viewpoint depending on who the sentence's subject is —
原先生が…下さった ("Prof. Hara [superior] gave...") vs. 原先生から…いただいた ("I received... from
Prof. Hara") describe the identical transaction from opposite grammatical vantage points.

#### 31.7 Donatory verbs combined with hope/desire
These same giving/receiving verbs combine with hope/desire expressions (〜たい, covered in Lesson
30) to produce requests — お電話をいただきたい ("I would like to be granted a telephone call" = "I'd
like you to call me") vs. 水をやってほしい ("I'd like you to give the plant water") — illustrating
that a polite request in Japanese is grammatically framed as "I wish to receive X" rather than a
direct imperative, a request-softening strategy distinct from anything captured in this project's
existing particle/grammar references.

---

## Lesson 34.6 The potential form (printed p. 292) — sampled, keigo/ability cluster

Lesson 34 (printed pp. 288–297) covers polite waiting formulas, expressing surprise, further verbs
of respect/humility, and the potential form. The potential form expresses ability ("can do") and is
formed regularly from a verb's citation-form stem; the book cross-references polite-request
constructions built on 34.7's いただける (potential of いただく, "to receive [humbly]"), tying the
potential form directly into the keigo (honorific-language) system rather than treating ability as
an isolated mechanism — i.e. "can you do X for me" as a politeness strategy, not just a literal
capability question.

---

## Lesson 35.1 (printed p. 299) — the passive form

### Grammar points

Regular passive formation by verb-group, keyed to the citation-form ending:

| Citation ending | Passive ending | Example |
|---|---|---|
| -u (group I) | -wareru | 買う "buy" → 買われる |
| -ru (group I) | -rareru | 乗る "ride" → 乗られる |
| -tsu (group I) | -tareru | 待つ "wait" → 待たれる |

All passives behave as group II verbs for further inflection. The book's worked example sentence
(若い男に手さげかばんをひったくられた, "[I] had my bag snatched by a young man") is drawn from a
police-report dialogue (reporting a theft near Ueno Station) — illustrating the Japanese "adversative
passive"/"suffering passive" use, where the passive marks an event the topic was negatively affected
by even when the English equivalent wouldn't use passive voice at all ("I had my bag snatched" /
"my documents were taken from me"). This adversative-passive use is a well-known typological feature
of Japanese not present in the same form in English, and is a strong candidate mechanism for an
eventual derived-slang construction (a grammaticalized "misfortune" marker).

---

## Lesson 37.3–37.4 (printed pp. 317–318) — the causative form

### Grammar points

#### 37.3 Transitive causatives
Formed regularly (する→させる, 来る→来(こ)させる for irregulars; other verbs follow a group-based
pattern parallel to the passive). Meaning spans the whole range from **coercion to mere permission**
— hence the form is also called the "permissive form." With a transitive verb, the underlying agent
(the person made/allowed to act) is normally marked with に: 私は生徒にテキストを読ませた "I made/
let the students read the text" (topic=I, agent=students-に, object=text-を, verb=caused-to-read).
**Exception, explicitly flagged**: when the direct object is omitted as contextually obvious, the
underlying agent switches from に to を (タクシーを待たせます "I'll have the taxi wait", 娘を手伝わ
せましょう "I'll have my daughter help") — but に becomes obligatory again the moment an explicit
direct object is reintroduced (洗いものを娘に手伝わせましょう "I'll have my daughter help you wash
up" — object present, agent reverts to に).

#### 37.4 Intransitive causatives
With intransitive verbs, **both に and を are grammatical for the underlying agent**, and the choice
carries a meaning distinction the book states explicitly: **に marks an agent with complete freedom
of choice/action** (子供達に…泳がせた "let the children swim [as long as they liked]" — permission-
flavored), implying を would instead carry more of a compulsion/coercion flavor for the same verb —
i.e. the two particles aren't free variants here but encode the permission/coercion distinction
directly through particle choice rather than through separate verbs the way giving/receiving does.

---

## Lesson 49.1–49.3 (printed pp. 426–427) — politeness vs. honorific language, explicit synopsis

This is the book's own summary chapter for the entire keigo system, flagged in the dispatch-planning
note above as likely the single highest-value remaining lesson for this project's honorific-language
coverage — confirmed on inspection: it opens with an explicit **terminological distinction this
project's existing keigo-focused established files (041, *Japanese Respect Language*) should be
cross-checked against**:

> **Politeness** is governed by the speaker's *attitude to the addressee* — polite, neutral, or
> rude — achieved mechanically via the 〜ます verb form and です (vs. だ) for the copula.
> **Honorific language**, by contrast, is governed by the speaker's attitude to the *subject/topic
> of discourse*, achieved by either **raising** or **lowering** the grammatical subject's status.
> The two systems overlap when the addressee is also the sentence's subject, but the book insists
> they remain conceptually distinct — a two-axis model (politeness × honorific direction) rather
> than keigo being a single undifferentiated "polite register."

### Grammar points

#### 49.1 でございます and でいらっしゃいます (revision)
でございます = super-polite/deferential copula form (politeness axis). いらっしゃる (without で) =
respectful equivalent of いる "be" (honorific axis, raises the subject). でいらっしゃる = the copula
form used specifically when referring to the addressee or someone closely connected to the addressee
— the book gives an explicit *ungrammatical* example (大山 saying *山川様でございますか about himself
would be a mistake — でございます about oneself, でいらっしゃいます only about the addressee/their
circle) to mark the boundary precisely.

#### 49.3 Forms expressing respect (raising the subject) — two productive patterns
(a) **お + conjunctive stem + になる** (can shorten to お + stem + です for a lighter honorific
touch): お帰りですか "are you going home?" (lit. "is [it] a going-home?"). Can be raised a further
notch by swapping です → でいらっしゃいます: いつお発ちでいらっしゃいますか "when are you leaving?"
— showing a **three-tier gradient** (plain → お+stem+です → お+stem+でいらっしゃいます) within a
single productive pattern, not just a binary polite/plain split.
(b) **The passive form used to indicate respect** (cross-referenced to 32.1, not independently
captured this dispatch): 毛利さんは…移られました "Mr Mōri moved [away]" — the passive morphology
(see Lesson 35 above) doing double duty as a respect-raising device, distinct from its adversative-
passive use in Lesson 35's police-report context. This is a clean example of **one surface form
serving two unrelated grammatical functions** depending on register/context, worth flagging for the
mechanics-analysis phase.

---

## Lessons not sampled this dispatch (9–30, 32–33, 36, 38–48, 50–52)

Beyond the TOC-level topic map already noted in this file's header, the following lessons were not
independently vision-read this dispatch. Topics by lesson number, for a continuation dispatch to
prioritize (richest non-redundant grammar first): Lesson 9 (numerical classifiers, verbal nouns),
Lesson 16–17 (-te form family, stative/dynamic/durative verb distinction — a core aspectual
typology), Lesson 22 (nominalization with の/んです), Lesson 26 (humble verbs, こと constructions),
Lesson 32–33 (further giving/receiving combinations, deferential copula でございます — continues the
Lesson 31 system captured above), Lesson 36 (further passive uses, continues Lesson 35 above),
Lesson 38–43 (not yet topic-mapped from the TOC — a continuation dispatch should re-check this
range), Lesson 44–46 (conditionals -eba/-tara/と/なら compared), Lesson 47–48 (prohibition,
commands), Lesson 50–51 (not yet topic-mapped), Lesson 52 (letter-writing formulas — register-marked
written Japanese, possibly relevant to literary/archaic usage-tier material).

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`. All example sentences
reproduced above are short (1 line), used illustratively, and drawn from a teaching textbook's
practice-dialogue material rather than any substantial original prose passage.
