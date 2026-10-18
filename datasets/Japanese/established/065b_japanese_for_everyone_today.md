# Japanese — Established Vocabulary/Grammar: *Japanese for Everyone* (Gakken, 1990), representative sample

**Source:** Nagara, Susumu et al., *Japanese for Everyone: A Functional Approach to Daily
Communication* (Gakken, copyright 1990, ISBN 0-87040-853-4), DJVU scan, 390 pages. 25 lessons
(第1課–第25課, one-page-per-image layout, unlike the sibling `065` source), each organized around
numbered "Function" sections (communicative functions rather than pure grammar points) plus
Vocabulary boxes and bilingual (Japanese/English) dialogues. Appendices include a full inflectional-
morphology reference table and an alphabetized English-to-Japanese index/glossary running to ~375
pages.

**Coverage note — REPRESENTATIVE SAMPLING, not full extraction.** This DJVU source has no usable
`pdftotext`-equivalent text layer and was vision-read page-by-page from rendered images. Combined
with sibling source `065` (593 pages total between the two books), full-book extraction was
infeasible in one subagent pass. This file covers:
- **Front matter:** authorship/copyright page and the book's full table of contents (used to confirm
  25-lesson structure and each lesson's Function-section topics, even for lessons not directly
  sampled).
- **Introduction / pronunciation section:** consonant/syllable/accent notes, extracted from sampled
  pages.
- **Lesson 1:** extracted in full (complete numbered vocabulary box, Dialogues I–III including the
  customs-declaration scene, Function I grammar, Function V "requests" grammar) as the deepest
  sample.
- **Lesson 2:** sampled (Function I-2 "question word + の", a dialogue, additional vocabulary).
- **Lessons 5, 6, 9, 12, 16, 19, 21, 24:** sampled — specific spreads read for vocabulary and/or one
  Function's grammar point each, chosen to span beginner through advanced register (L24's regret
  construction, L21's honorific/humble request forms).
- **Appendix 1 (Inflectional Endings):** extracted in full — a compact, complete paradigm table
  covering all verb/adjective/copula inflections used throughout the book, genuinely higher
  information-density than any single lesson's drill content.
- Lessons 3–4, 7–8, 10–11, 13–15, 17–18, 20, 22–23, 25 were **not sampled** in this pass.

**Vision-reading guard:** no handwritten marginalia was found on any page examined; this is a clean
library/personal-archive scan of a commercially printed book, and all extracted content below is
genuinely typeset source material.

**Gotcha note:** unlike sibling source `065` (*Japanese for Today*), this DJVU is **one printed page
per image** (confirmed: page 1 is a title page, not a two-page spread; printed page numbers run
roughly `printed_page = djvu_page − 3` once past the front matter, e.g. djvu page 30 = printed page
27, djvu page 34 = printed page 31 — verified by direct inspection of multiple sampled pages, not
assumed from a fixed formula). `ddjvu -format=ppm` + Pillow conversion was needed to render pages to
PNG, since `ddjvu` does not support `-format=png` directly on this system.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| パスポート pasupooto | passport | noun (loanword, katakana) | core | — | contemporary (source published 1990) | — | — | grammar_reference | n/a | verified | Lesson 1 vocabulary box |
| しごと shigoto | business, job, work | noun | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 1 |
| かんこう kankoo | sightseeing | noun | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 1 |
| スーツケース suutsukeesu | suitcase | noun (loanword, katakana) | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 1 |
| くすり kusuri | medicine | noun | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 1 Dialogue II, customs scene |
| はちみつ hachimitsu | honey | noun | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 1 Dialogue II — the declared item turns out to be honey, not medicine |
| ハム hamu | ham | noun (loanword, katakana) | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 1 Dialogue II; punchline item — officer rules it not allowed (だめですよ) |
| いい ii | good, all right, no problem | i-adjective | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 1 |
| だめ(な) dame (na) | not good, not allowed | na-adjective | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 1; だめですよ used by customs officer refusing the ham |
| みせて misete | show me (て-form request base, from 見せる miseru "to show") | verb, て-form | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 1 vocab; glossed explicitly as て-form of ru-verb 見せる |
| あけて akete | open (て-form request base, from 開ける akeru "to open") | verb, て-form | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 1 vocab; て-form of ru-verb 開ける |
| ください kudasai | please (do ...) — polite request marker after て-form | grammatical word | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 1 vocab; cross-referenced to Function V |
| さん san | Mr./Mrs./Ms. — honorific name suffix | grammatical word (suffix) | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 1 vocab, explicitly glossed "respect and a certain degree of familiarity" |
| ね ne | tag-question marker ("huh?", "right?", "aren't you?") | particle | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 1 vocab |
| よ yo | emphatic sentence-final particle | particle | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 1 vocab, glossed "emphasize what the person is saying" |
| どれ dore | which one (of three or more) | interrogative pronoun | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 1 vocab, cross-referenced Function III |
| じつは jitsu wa | to tell the truth, the fact is | expression | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 1 Dialogue II, Barbara's hedging confession before revealing the ham |
| すみません sumimasen | excuse me / I'm sorry / (also used to get attention, or thanks) | expression | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 1 vocab; source dedicates a boxed note ("すみません") to this word's multiple functions — pardon me / thank you / excuse-me-but / I'm-sorry-but, illustrated with 4 distinct use-case cartoons |
| ちょっと chotto | a bit, a little (also used as a stalling/hedging filler) | adverb | core / colloquial (as filler) | — | — | — | — | grammar_reference | n/a | verified | Lesson 1 vocab; also appears in the "stalling" functional set (あの、ちょっと… "well, you see...") |
| もうしわけないんですが mooshiwake nain desu ga | I am awfully sorry, but... | expression | formal | — | — | — | — | grammar_reference | n/a | verified | Lesson 1, Function V "Stalling/refusal" register set — more formal than すみません or わるいけど |
| わるいけど waruikedo | sorry, but... | expression | colloquial | — | — | — | — | grammar_reference | n/a | verified | Lesson 1, same refusal-register set as もうしわけないんですが — explicit register contrast (casual vs. formal apology) on the same page |
| いやです iya desu | no way, I refuse | expression | colloquial | — | — | — | — | grammar_reference | n/a | verified | Lesson 1, "outright refusal" register set, paired with いいえ、だめです |
| 本やのとなり hon-ya no tonari | next to the bookstore | noun phrase | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 2 Dialogue II, directions scene |
| だれの dare no | whose | interrogative + possessive | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 2, Function I-2 |
| なんの nan no | of what kind, what sort of | interrogative + possessive | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 2, Function I-2 |
| どこの doko no | from where | interrogative + possessive | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 2, Function I-2 |
| スペイン supein | Spain | proper noun (loanword, katakana) | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 2 additional vocabulary |
| ビール biiru | beer | noun (loanword, katakana) | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 5 Dialogue I, sushi-bar scene |
| トロ toro | fatty tuna | noun | technical.culinary | — | — | — | — | grammar_reference | n/a | verified | Lesson 5 Dialogue I |
| えび ebi | shrimp | noun | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 5 Dialogue I |
| きゅうりょう日 kyuuryoo-bi | payday | noun | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 5 Dialogue II |
| ひっこす hikkosu | to move to another residence | verb (u-verb) | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 6 vocabulary box |
| ほしがる hoshigaru | to appear to want (said of a third party) | verb (u-verb) | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 6, explicitly contrasted with 1st-person ほしい in the vocab note |
| サイズ saizu | size | noun (loanword, katakana) | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 6 |
| アイロン airon | (clothes) iron | noun (loanword, katakana) | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 6 |
| けっこうです kekkoo desu | sense ①: that's fine then, no thank you (polite refusal) / sense ②: fine, I'll take it (acceptance) | expression | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 6 vocab box, explicitly glosses both opposite-polarity senses side by side — same ambiguity independently confirmed in sibling source `065` |
| いらっしゃいませ irasshaimase | welcome! (shopkeeper's greeting) | expression | formal | — | — | — | — | grammar_reference | n/a | verified | Lesson 6 vocab |
| 切手 kitte | postage stamp | noun | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 9 Dialogue I, stamp-collection gift scene |
| ともだちにもらったんです tomodachi ni moratta n desu | I got it from a friend (explanatory のだ/んです form) | sentence pattern | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 9 Dialogue I |
| むすこ musuko | son | noun | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 9 Dialogue I |
| しょうよ shooyo | (seasonal work bonus) | noun | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 19, same bonus/soy-sauce (しょうゆ) near-homophone teaching moment independently confirmed in sibling source `065` — this book's version has the listener (Michael) actually mishear it as しょうゆ on the page, making the confusion explicit in-dialogue rather than just footnoted |
| 働きすぎ hataraki-sugi | overwork | noun (deverbal compound) | colloquial / core | — | — | — | — | grammar_reference | n/a | verified | Lesson 19 Dialogue I, Michael's complaint 「働きすぎなんじゃない、日本人は」 — casual inverted-word-order register (see Grammar Note I below) |
| 電気代 denki-dai | electricity bill/charges | noun (compound) | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 21, -dai "charge/fee for X" productive suffix |
| 窓口 madoguchi | (teller) window, counter | noun (compound) | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 21 Dialogue II |
| じろじろ見る jirojiro miru | to stare | verb phrase (mimetic adverb + verb) | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 24 vocab box; じろじろ is a giongo/gitaigo-style mimetic adverb |
| さっそく sassoku | at once, right away | adverb | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 24 vocab box |
| ひしょ hisho | secretary | noun | core | — | — | — | — | grammar_reference | n/a | verified | Lesson 24; also appears in Appendix index p.296 |

**Morpheme breakdown (agglutinative compounds, per Japanese's typology note in
`00_Extraction_Checklist.md`).**

> **働きすぎ hataraki-sugi** = 働き hataraki (stem of 働く hataraku, "to work") + すぎ -sugi ("too much,
> excess") — productive V-stem+すぎる derivational pattern, formally tabulated in Appendix 1's I-stem
> pattern chart (see Grammar below); the same compound independently appears in sibling source `065`.

> **電気代 denki-dai** = 電気 denki ("electricity") + 代 -dai ("charge/fee") — Sino-Japanese
> N+suffix compound, same productive type as 働きすぎ above but nominal rather than deverbal.

## Grammar points

### Introduction §I.1(b) Consonants requiring special note

The source flags five consonant sounds as needing explicit explanation for learners: [ts] (rare
word-initially/medially in English, common before [u] in Japanese), [g] (optionally pronounced [ŋ]
mid-word — "either pronunciation is fine"), [w] (pronounced without lip-rounding, unlike English),
[h]/[f] (allophonic split: f before [u], h before [a,i,e,o,y]), and [r] (a single light alveolar tap,
explicitly contrasted with both English [r] and [l] articulation). (Introduction, p.12.)

### Introduction §I.2 Syllable-sequence vowel pronunciation

When two or more vowels of the same quality occur in sequence, each is held for its own mora/beat
(おかあさん o-ka-a-sa-n). Two exceptions: the sequences [ei] and [ou] are both commonly leveled to
long [ee] and [oo] respectively in modern speech, and the book deliberately romanizes them that way
throughout (けいざい romanized "keezai" not "keizai"). This is presented as a *normalizing editorial
choice* by the book's authors, not merely a phonetic footnote — worth flagging since it means this
source's own romanization will not literally match a strict Hepburn transliteration. (Introduction,
p.12.)

### Introduction §D "Styles of speech"

Three-way distinction: (1) polite speech (です/〜ます forms) — used in business, classroom, addressing
superiors/strangers; (2) plain speech — informal, used among family/friends/equals or toward
subordinates, and explicitly described as the form "most thinking is done in" and the base for most
grammatical derivations; (3) respect language (honorific terms for others, humble terms for oneself)
— layered on top of polite speech for further deference. (Introduction §E, p.17.) This three-tier
model (plain / polite / respect-language) is a direct register-taxonomy source worth cross-referencing
against this project's own Usage Tier taxonomy.

### Lesson 1, Function I: Identifying things (A は B です)

Equivalent core pattern to `065`'s §1 — same N₁ は N₂ です/ではありません paradigm, with ちがいます
"[that's] wrong" given as an additional possible negative-answer form not seen in the `065` sample.
(Lesson 1, p.23.)

### Lesson 1, Function V: Asking someone to do something (1) — みせてください

Request chain of increasing politeness built on the て-form: V-te (bare, "[do], please" — casual) →
V-te ください (standard polite request) → V-te くださいませんか (more polite, literally "won't you
please...", negative-question softening). The lesson also tabulates a full **register set for
complying, refusing, and stalling** on a request: はい/ええ/うん (compliance, formality descending)
through いいですよ、はい、どうぞ (compliance + handover) to いいえ、だめです/いいえ、いやです (outright
refusal) to あの、ちょっと…／わるいけど…／すみません。／もうしわけないんですが… (stalling/hedging,
ranked from casual to very formal). This is a genuinely useful **pragmatics/politeness-gradient**
table, not just vocabulary — directly relevant to future slang-mechanics analysis of
refusal/hedging registers. (Lesson 1, p.27.)

### Lesson 2, Function I-2: Question word + の

だれの/どなたの "whose", なんの "of what kind", どこの "from where" — の attaches after an interrogative
pronoun to form a possessive/attributive question, paralleling ordinary N1のN2 possession. (Lesson 2,
p.32.)

### Lesson 19, Grammar Note I: Inverted word order

Flagged explicitly as a feature of casual spoken register: 働きすぎなんじゃない、日本人は "they're
overworked, aren't they, the Japanese" — the topic (日本人は) is moved to sentence-final position
after the predicate, an afterthought/emphasis construction common in informal speech but marked
"inverted" relative to the book's normal SOV teaching order. (Lesson 19, p.233, Dialogue I context.)

### Lesson 24, Function III: Expressing regret that things are not otherwise (conditional + いい/よかった + のに)

Conditional-form + いい/よかった + のに laments an unrealized state: こんなにおいしい水が、東京でも飲めた
らいいのに "if only it were possible to drink such delicious water in Tokyo too"; もっと早く、お医者さん
に見てもらえばよかったのに "if only you'd had the doctor examine you sooner." **Explicit restriction
noted by the source:** のに in this regret construction cannot be used about the speaker's own
completed actions — 「もっと、ゆっくり走ればよかった」(no のに) is correct for self-directed regret, while
のに is reserved for regret about someone/something else or an unrealized hypothetical. (Lesson 24,
p.297.)

### Appendix 1: Inflectional endings (full paradigm reference)

A single consolidated table of every verb/adjective/copula inflection pattern used across the book,
organized by **how the ending attaches to the root** — this is the clearest single-page grammar
reference in either sampled book and is reproduced here as structure (not verbatim text):

1. **Plain non-past pattern** (ending attaches directly to the root): 6 endings tabulated across
   u-verbs, ru-verbs, be-verb, い-adjectives, and negative ない — covering plain non-past (〜u/ru),
   imperative (〜e/ro), volitional/probability (〜oo/yoo), conditional (〜eba/reba), potential
   (〜eru/rareru), passive (〜areru/rareru), and causative (〜aseru/saseru).
2. **Negative pattern** (an [a] is inserted between a u-verb root and the ending): 〜ない (negative),
   〜ずに ("without doing").
3. **I-stem pattern** (endings attach to the continuative/i-stem — [i] added to u-verb roots,
   ru-verb roots unchanged): 〜ます (polite non-past), 〜たい ("want to"), 〜たがる ("appears to want
   to" — third-person want, same form as はほしがる seen in Lesson 6 above), 〜なさい (polite command),
   〜ながら ("while doing"), 〜すぎる ("too much" — the source of 働きすぎ above), 〜出す／〜はじめる
   ("start doing").
4. **て-form pattern** (root shape altered, initial [t] sometimes voiced to [d]): 〜て (て-form),
   〜た (past), 〜たら (conditional, "if/when"), 〜たり ("and so forth, do things like X and Y").
5. **Auxiliaries built on the て-form**: 〜ている (progressive/resultative, "am doing" / "have
   done" / "the result is still in effect"), 〜てある ("has been done [and the result persists]"),
   〜てほしい ("I want you to..."), 〜てみる ("try doing"), 〜ておく ("do in preparation"), 〜てしまう
   ("do completely, end up doing"), 〜てください (polite request), 〜てあげる/〜てさしあげる ("do for
   someone", the latter more polite), 〜てやる ("do for/to an inferior, or do despite resentment" —
   explicitly glossed with the double sense "I'll write for you" / "I'll write, and thereby cause you
   grief!", a genuine register/pragmatics note on a single grammatical form carrying opposite social
   connotations depending on context), 〜てくれる/〜てくださる ("do for me", the latter more polite).

(Appendix 1, p.334.)

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `../../00_Reference_Extraction_Spec.md`. Vocabulary and
grammar above are drawn from a representative sample of pages (not the whole 390-page book);
grammar explanations are paraphrased in this file's own words, and only short illustrative example
sentences are quoted directly from the source, consistent with that discipline.
