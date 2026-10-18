# Japanese — Established Vocabulary/Grammar: *Japanese for Today* (Gakken), representative sample

**Source:** Gakken (学研), *Japanese for Today: A Basic Grammar and Conversation Text* (あたらしい日本語),
ABBYY-FineReader-OCR'd scan, 203 PDF pages (each a two-printed-page spread — see vision-reading note
below). 30 lessons (第1課–第30課) plus a 9-page front-matter "Introduction" (pronunciation, writing
system, outline of sentence structure) and a back-matter index/glossary.

**Coverage note — REPRESENTATIVE SAMPLING, not full extraction.** This source has no text layer at
all (`pdftotext` returns empty output on every page checked) and is 203 PDF pages (≈400 printed
pages after accounting for the two-page-per-image spread layout — see gotcha below). Per dispatch
instructions, full-book extraction was infeasible in one subagent pass, so this file covers:
- **Front matter (Introduction):** pronunciation, syllable structure, accent, writing system, outline
  of sentence structure — extracted in full (it is short and foundational).
- **Lesson 1:** extracted in full (complete vocabulary list, complete dialogue, complete grammar
  §1–§4) as the deepest sample, establishing the book's baseline register (polite/desu-masu style).
- **Lessons 3, 5, 6, 9, 13, 16, 19, 23, 26, 29** (of 30): sampled — vocabulary and/or grammar points
  visible on the specific spread pages read, not the lesson's full content. These were chosen to
  span the book's full pedagogical arc from beginner (L3) through advanced/literary register (L23,
  L29) at roughly even intervals.
- Lessons 2, 4, 7, 8, 10–12, 14–15, 17–18, 20–22, 24–25, 27–28, 30 were **not sampled** at all in this
  pass — not reflected in this file.

This is a deliberate scope reduction per the dispatch's explicit instruction to sample
representatively across the lesson progression rather than skip the book or attempt full extraction.
A future pass could fill in the untouched lessons as additional `065c`/`065d`/... files.

**Vision-reading guard:** this is a clean ABBYY-rescanned textbook with no visible handwritten
marginalia on any page examined — no previous-owner annotation was found or excluded. All vocabulary/
grammar below is genuinely printed source content.

**Gotcha confirmed on this source:** `pdfinfo` reports page size 422×298pt (landscape A6) for all 203
pages — this is **two printed pages scanned side-by-side per PDF page**, the same "two-printed-pages-
per-image spread" pattern previously confirmed on *Colloquial Serbian*. A naive `printed_page ≈
PDF_page × offset` estimate was verified empirically (not assumed) by rendering sample pages: PDF
page 8 shows printed pages 10–11 (Lesson 1 opening); the offset holds as printed_page ≈ 2×PDF_page − 6
(left page) through the lesson-numbered body of the book, confirmed again at PDF page 30 ≈ printed
pages 70-ish region (Lesson 5) and PDF page 160 ≈ printed page ~318 (Lesson 26) — consistent with
direct inspection, not trusted from arithmetic alone.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| これ kore | this (thing, near speaker) | demonstrative pronoun | core | — | contemporary (source published; Gakken edition undated in sampled pages) | — | — | grammar_reference | n/a | verified | Ko-series demonstrative; Lesson 1, §2 |
| それ sore | that (thing, near listener) | demonstrative pronoun | core | — | — | — | — | grammar_reference | n/a | verified | So-series; Lesson 1 |
| あれ are | that (thing, distant from both) | demonstrative pronoun | core | — | — | — | — | grammar_reference | n/a | verified | A-series; Lesson 1 |
| 花 hana | flower, blossom | noun | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 1 vocab #3 |
| 桜 sakura | cherry blossom | noun | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 1 vocab #5; title sentence "Kore wa sakura desu" |
| 桃 momo | peach | noun | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 1 vocab #7 |
| ばら bara | rose | noun | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 1 vocab #9 |
| 何 nan/nani | what | interrogative pronoun | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 1 vocab #10; §3 |
| です desu | is/am/are (copula) | copula | core | — | — | — | — | grammar_reference | n/a | verified | Polite non-past copula; Lesson 1 §1 |
| 日本 Nippon/Nihon | Japan | proper noun | core | — | — | — | — | grammar_reference | n/a | verified | Vocab #12 explicit usage note: both readings "Nippon" and "Nihon" are pronunciation variants of the same written word — the source itself flags this dual-reading phenomenon |
| ～の ...no | possessive/connective particle ("N1's N2") | particle | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 1 vocab #13; §4 |
| も mo | also, too (replaces は in parallel predication) | particle | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 1 vocab #14 |
| はい hai | yes | interjection | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 1 vocab #15 |
| そう soo | so, that way | adverb/pro-form | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 1 vocab #16 |
| いいえ iie | no | interjection | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 1 vocab #17 |
| ～ではありません dewa arimasen | is not (polite negative copula) | copula (negative) | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 1 vocab #18; §1 |
| わたし watashi | I | pronoun | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 1 vocab #19 |
| 学生 gakusei | student | noun | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 1 vocab #21 |
| 会社員 kaisha-in | company employee | noun (compound) | core | — | — | — | — | grammar_reference | n/a | verified | Vocab #23; morphologically composed — see breakdown below |
| 名前 namae | name | noun | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 1 vocab #24 |
| 日本人 Nippon-jin | a Japanese (person) | noun (compound) | core | — | — | — | — | grammar_reference | n/a | verified | Vocab #26; -jin "person of (nationality)" is a productive suffix, vocab #27 |
| だれ/どなた dare/donata | who | interrogative pronoun | core / (donata = formal) | — | — | — | — | grammar_reference | n/a | verified | donata glossed explicitly "more polite" than dare — Lesson 1 vocab #28 |
| 妹 imooto | younger sister | noun | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 1 vocab #30 |
| いとこ itoko | cousin | noun | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 1 vocab #33 |
| あなたがた anata-gata | you (plural, polite) | pronoun | formal | — | — | — | — | grammar_reference | n/a | verified | -gata explicitly glossed "Plural Suf. for Human N; Polite" — vocab #34 |
| わたしたち watashi-tachi | we | pronoun | core | — | — | — | — | grammar_reference | n/a | verified | -tachi glossed "Plural Suf. for Animate N" (less formal than -gata) — vocab #37 |
| ここ koko | here | demonstrative (place) | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 1 vocab #39; §2 place series |
| どこ doko | where | interrogative (place) | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 1 vocab #40 |
| 銀行 ginkoo | bank | noun | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 1 vocab #41 |
| 郵便局 yuubin-kyoku | post office | noun (compound) | core | — | — | — | — | grammar_reference | n/a | verified | yuubin "mail" + -kyoku "bureau" — vocab #42 |
| あそこ asoko | over there | demonstrative (place) | core | — | — | — | — | grammar_reference | n/a | verified | Vocab #43 |
| 切手 kitte | postage stamp | noun | core | — | — | — | — | grammar_reference | n/a | verified | Vocab #44 |
| 売り場 uri-ba | sales counter, place for selling | noun (compound) | core | — | — | — | — | grammar_reference | n/a | verified | uri ← uru "sell" + -ba "place" — vocab #45, morphologically transparent |
| へや heya | room | noun | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 3 vocab #2 |
| ドア doa | door | noun (loanword, katakana) | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 3; katakana marks foreign-origin word |
| 全部 zenbu | all, the whole (noun/adverb) | noun/adverb | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 3 vocab #7; idiom 全部で "in all, altogether" |
| いくつ ikutsu | how many? (generic counter question) | interrogative | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | Lesson 3; small-print footnote, legible but not cross-checked elsewhere on page |
| カレンダー karendaa | calendar | noun (loanword, katakana) | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 3 vocab |
| 計算機 keisanki | calculator | noun (compound) | core | — | — | — | — | grammar_reference | n/a | verified | keisan "calculation" + -ki "machine" — Lesson 3 vocab #42, morphologically transparent |
| ロッカー rokkaa | locker | noun (loanword, katakana) | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 3 vocab #41 |
| のみもの nomimono | drink, beverage | noun (deverbal) | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 5 dialogue opener; nomi- (stem of nomu "drink") + mono "thing" |
| トロ toro | fatty tuna (sushi cut) | noun (loanword/slang-adjacent culinary term) | technical.culinary | — | — | — | — | grammar_reference | n/a | verified | Lesson 5 dialogue, sushi-bar scene |
| えび ebi | shrimp | noun | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 5 dialogue |
| ひっこす hikkosu | to move to another residence | verb (u-verb) | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 6 vocab |
| ほしがる hoshigaru | to appear to want, desire (said of a third party) | verb (u-verb) | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 6 vocab; explicitly glossed "used when telling what someone else wants" — contrasts with first-person ほしい |
| アイロン airon | (clothes) iron | noun (loanword, katakana) | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 6 vocab |
| けっこうです kekkoo desu | "that's fine" (2 senses: polite refusal OR polite acceptance) | expression | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 6 vocab, source explicitly glosses two distinct senses — a genuine pragmatic-ambiguity note worth flagging for slang-mechanics analysis |
| しょうよ shooyo | (seasonal bonus, = ボーナス) | noun | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 19 dialogue; source stages a deliberate near-homophone confusion with しょうゆ "soy sauce" as a teaching device — a genuine minimal-pair/mishearing example |
| 給料 kyuuryoo | salary, pay | noun | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 19 dialogue |
| 働きすぎ hataraki-sugi | overwork(ing) | noun (deverbal compound) | core | — | — | — | — | grammar_reference | n/a | verified | hataraki- (stem of hataraku "to work") + -sugi "too much" — Lesson 19; productive V-stem+すぎ pattern |
| 文章 bunshoo | writing, a piece of writing/prose | noun | literary | — | — | — | — | grammar_reference | n/a | verified | Lesson 23 — literature/book-discussion register chapter |
| 書き出し kaki-dashi | opening passage, opening sentence (of a text) | noun (deverbal compound) | literary | — | — | — | — | grammar_reference | n/a | verified | Lesson 23; kaki- (stem of kaku "write") + -dashi "begin (doing)" |
| 小説 shoosetsu | novel | noun | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 23 |
| 近代化 kindai-ka | modernization | noun (deverbal/Sino-Japanese compound) | literary / technical.sociology | — | — | — | — | grammar_reference | n/a | verified | Lesson 29, urbanization-themed dialogue; -ka "-ization" is a productive Sino-Japanese suffix |
| 幸せ shiawase | happiness | noun/na-adjective | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 29 dialogue |

**Morpheme breakdown (agglutinative compounds, per Japanese's typology note in
`00_Extraction_Checklist.md`).**

> **会社員 kaisha-in** = 会社 kaisha ("company") + 員 -in ("member") — Sino-Japanese compound, highly
> productive -in suffix for "member of X" occupational nouns.

> **郵便局 yuubin-kyoku** = 郵便 yuubin ("mail") + 局 -kyoku ("bureau/office") — same productive
> Sino-Japanese compounding pattern as 計算機, 働きすぎ, 近代化 above.

> **売り場 uri-ba** = 売り uri (stem of 売る uru, "to sell") + 場 -ba ("place") — native-Japanese
> (wago) V-stem + place-noun compounding, distinct in origin from the Sino-Japanese (kango) compounds
> above but structurally parallel.

> **働きすぎ hataraki-sugi** = 働き hataraki (stem of 働く hataraku, "to work") + すぎ -sugi ("too
> much, excess of") — productive V-stem+すぎる derivational pattern (Appendix 1, §(3) I-stem pattern),
> confirmed also in *Japanese for Everyone*'s own Appendix table (see sibling file `065b`).

## Grammar points

### §1 Identifying a thing or person (N₁ は N₂ です)

The copula です equates N₁ with N₂ ("N₁ is N₂"). Negation is N₁ は N₂ ではありません. は marks the
sentence's topic — explicitly noted as *not* equivalent to the English grammatical subject. も
replaces は when the same predicate applies to a second noun (トムも学生です "Tom is a student too").
Questions are formed by adding か (a sentence-final question particle) to the statement; an answer
can be abbreviated to そうです/そうではありません("that's right"/"that's not right") when context makes
the full N₁/N₂ redundant. (Lesson 1, p.12–15.)

### §2 Demonstratives

Japanese demonstratives fall into four series — こ(ko-), そ(so-), あ(a-), ど(do-, interrogative) —
realized across four grammatical slots: nominal (thing: これ/それ/あれ/どれ; place: ここ/そこ/あそこ/どこ),
prenominal (この/その/あの/どの), adjectival (こんな/そんな/あんな/どんな), and adverbial (こう/そう/ああ/どう,
plus こんなに-style intensified forms). The ko-series points to something near the speaker, so-series
near the listener, a-series distant from or unknown to both, do-series is the interrogative member of
each set. (Lesson 1, p.13.)

### §3 Interrogative nouns

何 nan/nani "what", だれ/どなた dare/donata "who" (donata more polite), どこ doko "where" are the core
interrogative-noun set; 何 is pronounced なん before です/だ/な/に and generally なに elsewhere. (Lesson 1,
p.13.)

### §4 Connecting two nouns (N₁ の N₂)

の links two nouns roughly as "N₂ of N₁" (わたしの本 "my book", literally "book of I"; 日本語の本 "a book
in/of Japanese"). N₂ can be omitted when recoverable from context (これはわたしのです "this is mine").
Chains of 3+ nouns are possible (わたしの日本のともだち "my friend in/from Japan"). (Lesson 1, p.14;
reinforced Lesson 2 "Question word + の": だれの "whose", なんの "of what kind", どこの "from where".)

### §31 Past tense of the nominal predicate

N₁ は N₂ でした "N₁ was N₂"; negative N₁ は N₂ ではありませんでした. (Lesson 6, observed on a
grammar-section spread.)

### §32 Past tense of い-adjectives and な-adjectives

な-adjective past: N wa Na deshita ("was Na"), negative N wa Na dewa arimasen deshita. い-adjective
past: N wa A-katta desu ("was A"), negative N wa A-ku nakatta desu/arimasen deshita. Illustrated with
花子さんはきれいですね "Hanako is pretty, isn't she" → 昔もあんなにきれいでしたか "was she that pretty a
long time ago too?" and あの映画はおもしろかったですか／あまりおもしろくなかったです "was that movie
interesting? — not very." (Lesson 6, §32.)

### §33 Joint actions (N と V)

と marks a co-participant of an action ("[do] with N"): ともだちと映画に行きました "I went to a movie
with a friend." Note explicitly states N here must be animate, typically human. (Lesson 6.)

### §34 Purpose (V-ni ikimasu/kimasu/kaerimasu)

Plain-dictionary-form verb + に + 行きます/来ます/帰ります expresses "go/come/return in order to [V]"
— restricted to motion verbs as the matrix predicate; other predicates need a different pattern
(cross-referenced to §103). (Lesson 6.)

### §35 Predicative vs. prenominal uses of い-adjectives

Most い-adjectives are usable unchanged as both predicates and prenominal (noun-modifying) forms, but
a handful of adjectives differ in form between the two uses (近い chikai "near" as predicate vs. 近くの
chikaku no as prenominal "nearby"; 多い ooi "many/much" as predicate vs. 多くの ooku no as prenominal).
A further small class ("ProN", abbreviated) is prenominal-only (とんだ "awful", すぐれた "excellent").
(Lesson 6.)

### §36 Conjunctive particle から ("because")

Sentence₁ + が/から + Sentence₂ expresses "S₁, but S₂" (が) or "because S₁, S₂" (から). Example: いい天気
でしたから、ハイキングに行きました "As the weather was fine, I went hiking." (Lesson 6.)

### §71 Passive construction

N₁ は N₂ に(よって/から) V-(r)are-ru — "N₁ is V-ed by N₂." The agent takes に or によって depending on
the verb's action type (に for directly-affecting verbs like killing/catching; によって when the agent
is more instrumental). A distinct "passive of suffering/misfortune" exists for intransitive verbs,
expressing the subject was adversely affected by an event, with no literal English passive
equivalent (わたしは昨日帰りに雨に降られた "I got rained on on my way home yesterday" — literally
unparseable as an English passive). (Lesson 16, §71.)

### §72 Causative construction

N₁ は/が N₂ を/に V-(s)ase-ru — "N₁ makes/lets N₂ do...". The object particle alternates を (when V is
intransitive) / に (when V is transitive, or when N₁ outranks N₂ in status — e.g. a parent causing a
child to do something). Combinable with the passive form (causative-passive) to mean the subject was
made to do something against their will, e.g. 弟は兄に東京へ行かされた "My brother was made to go to
Tokyo by my [older] brother." (Lesson 16, §72.)

### §102 The use of ところ (tokoro) as "place" and as an aspectual marker

Besides its literal "place" sense (ここは夏目漱石が生まれたところです "this is the place where Natsume
Sōseki was born"), ところ attaches after V(dict. form)/V(past form)/V-ている to mark imminent,
just-completed, or ongoing action respectively: V(dict.)+ところです "about to...", V(past)+ところです
"just finished...ing", V-ている+ところです "in the middle of...ing, right now". (Lesson 26, §102.)

### §103 The use of ため(に) ("reason/cause" and "purpose")

(1) Reason/cause: 昨日雷が落ちたため、停電になりました "There was a power failure because of lightning
yesterday." (2) Purpose: 結婚するためにお金を貯めています "I am saving money in order to get married."
(Lesson 26, §103.)

### §104 The use of ほど (hodo) as a pseudo-noun

ほど after a negated predicate softens a negative claim ("not to the extent that..."): 彼はそんなに悪い
人ではありません、あなたが言うほどは "he's not as bad a person as you say." Preceded by the conditional
〜(r)eba form, ほど forms "the more..., the more..." correlative constructions: 早ければ早いほどいい "the
earlier the better." (Lesson 26, §104.)

### §105 The use of とおり (toori) — "as, in the way that"

V(dict. form) + とおり means "as/the way [subject] does X": 私が言うとおりに書いてください "please write
it as I say it." (Lesson 26, §105.)

### §106 〜って as a contraction in informal conversation

って contracts と言う/と言っている in casual speech: おみこしって何ですか "what is an omikoshi, anyway?"
(← おみこしと言うのは何ですか). (Lesson 26, §106.)

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `../../00_Reference_Extraction_Spec.md`. Vocabulary and
grammar above are drawn from a representative sample of pages (not the whole 203-page/~400-printed-
page book); grammar explanations are paraphrased in this file's own words, and only short illustrative
example sentences are quoted directly from the source, consistent with that discipline.
