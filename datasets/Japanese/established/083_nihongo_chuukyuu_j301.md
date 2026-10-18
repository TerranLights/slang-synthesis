# Japanese — Established Vocabulary/Grammar: Nihongo Chuukyuu J301 — Overview, Grammar Points, Lesson 1

**Source:** Toki Satoshi, Seki Masaaki, Hiradaka Fumiya, Shinnai Yasuko, Tsuruo Yoshiko, *日本語中級J301 — 基礎から中級へ* (*Nihongo Chuukyuu J301: From Elementary to Intermediate*), English edition, 3A Network (スリーエーネットワーク), first edition 1995, 6th printing 2004. ISBN 4-88319-044-7. Whole book (248 PDF pages): 10 reading-centered lessons (第1課–第10課) plus a `別冊` ("separate booklet") new-vocabulary (新出語) appendix and a kanji-ordered vocabulary index (語彙索引).

**Coverage note:** This is an intermediate reading-skills course (each lesson: 読むまえに pre-reading → 本文 main text → 文章の型 discourse-pattern fill-in → Q&A → Grammar Notes → 練習 drills → ことばのネットワーク word-network → 書いてみよう・話し合ってみよう writing/discussion). The source has **no usable text layer** (`pdftotext` returns ~1 char/page; confirmed scanned-image PDF, "Image Conversion Plug-in" in its metadata) — this entire extraction is vision-read from rendered page images.

**Vocabulary coverage strategy:** The book's own `別冊 新出語` ("new words") appendix is a clean, lesson-by-lesson, English-glossed new-vocabulary list — effectively the publisher's own comprehensive vocabulary index. Rather than vision-reading the full 248-page book cover-to-cover, this extraction transcribes that appendix in full (all 10 lessons, ~26 of its own numbered pages) as the primary vocabulary source, which directly satisfies the spec's "every distinct vocabulary item" coverage rule far more reliably than manual re-transcription of the main lesson text would. Grammar points are **representatively sampled** from the main lesson body's own "Grammar Notes" sections across the lesson progression (Lessons 1, 5, 7, 9, 10 — beginning, two middle, and two end lessons), per this project's standing practice for oversized sources. This file covers the overview, all sampled grammar points, and Lesson 1's vocabulary. Lessons 2–10 vocabulary continues in `083b`–`083f`.

**Gotcha — non-sequential scan order.** The 新出語 booklet's own page numbers (1–26, printed in each page's footer, independent of the main book's page numbers) do **not** run in the same order as the PDF's physical page sequence. Booklet page 1 (Lesson 1) sits at PDF page 223; pages 3–9 (Lessons 2–3 and the start of Lesson 4) sit at PDF pages 242–248 (the very end of the file); pages 10–26 (the rest of Lesson 4 through Lesson 10) sit at PDF pages 224–241; and a single stray page (booklet page 2, the tail end of Lesson 1) is scanned out of place at PDF page 234, in the middle of the Lesson 8 run. This was only caught by reading every page's own footer number directly rather than assuming `booklet_page ≈ PDF_page + fixed_offset` — confirms the extraction spec's standing warning to verify page offsets empirically rather than trust a formula, and shows the same risk can affect an internal sub-document's pagination, not just the whole book's.

**Marginalia found and excluded.** One page of the main lesson body (Lesson 10's Grammar Notes, main-book page 173, covering the ところが grammar point) carries a handwritten cursive annotation in the page's upper-right margin, clearly pen/pencil and inconsistent with the surrounding typeset font. It was excluded entirely, per the extraction spec's vision-reading guard — it is a previous owner's note, not source content, and its content could not be reliably read in any case.

**No explicit register/dialect tags.** The book's own "List of Symbols and Abbreviations" (p.7) defines only structural/grammatical symbols (V/A/Na/N for word class, ○/× for correct/incorrect, etc.) — there is no B/C/S-style register or dialect tagging system in this source, unlike some other languages' comparative references in this project. All vocabulary below is therefore tagged `core` (standard written/intermediate-level Japanese) unless a specific entry's own gloss marks it otherwise (none found). Lesson topics are factual/expository reading passages (a face-photo puzzle, a children's poem, computer form-factors, cherry-blossom-date statistics, queueing impatience, ghost stories, social-obligation customs, whaling, a monkey-vision experiment, children's drawings) rather than registered dialogue, which is why no colloquial/formal split emerged from this source the way it might from a conversation-based course.

---

## Grammar points (representative sample — Lessons 1, 5, 7, 9, 10)

### Lesson 1 (舌を出したアインシュタイン — "Einstein Sticking Out His Tongue")

#### ta-form + あと — "after ~"
A past-tense (ta-form) verb precedes あと. あとで, あとに, and bare あと are near-synonyms but differ in scope: X-あとで allows an unspecified (wide) time span after X before the following action; X-あとに requires a narrowly-specified time immediately after X; bare あと carries neither restriction and is the most common in daily speech. Example: ごはんを食べたあとで、勉強した。("I studied after I had a meal" — the study could start any time after the meal), vs. …あとに…(must be immediately after).

#### volitional form + とする — "to be on the point of ~, to be going to ~"
A verb's volitional form (e.g. 飲もう, 帰ろう) precedes とする to express the imminent-but-not-yet-begun state of an action. 薬を飲もうとしたが、苦くて飲めなかった。("I was going to take some medicine, but I could not take it because of the bitterness" — the drinking never actually started).

#### ~のうち — "among ~"
Expresses a range over a set of persons/things; うち can be swapped for なか in this sense (兄弟4人のうちで、だれがいちばん背が高いですか。"Who is the tallest among the four children?"). But when うち instead expresses a time-limitation ("while ~" / "before ~", e.g. 若いうちに勉強したほうがいい "study hard while you're young"), it cannot be replaced with なか — the two uses of うち are not interchangeable.

#### ~ところ — "time, moment" (vs. "place")
~ところ used as a pseudo-noun means "time/moment", distinct from its ordinary-noun sense "place" (住んでいる所はどこですか。"Where is the place you live?"). これから帰るところです。("I am about to go home now.") / 今帰ったところです。("I have just come home.") show the "about to" / "just did" senses respectively.

### Lesson 5 (待ってイライラ。あなたはどれだけ待てますか？ — "Waiting Frustration: How Long Can You Wait?")

#### N + にとって — "for N"
Marks a judgement/evaluation as "considered from N's position." Must precede an evaluative statement, not a bare action/phenomenon — あなたにとって今いちばん困っていることは何ですか。("For you, what is your biggest problem now?") is fine, but *わたしにとって、遊びに行きます is not, since "going out to play" is a bare action, not an evaluation.

#### S₁。だから、S₂。 — "S₁. So/Therefore, S₂."
だから is the plain-style equivalent of ですから — a causal conjunction linking a preceding reason-sentence to a following result-sentence.

#### Causative-passive form
Combines causative + passive. Group I verbs: nai-form + さ + れる, or nai-form + せ + られる (書かされる/書かせられる "to be made to write"). Group II verbs and the irregular 来る: nai-form + させられる. する → させられる. Carries a strong nuance of being forced/inconvenienced by someone else's will.

#### ~てくる — "the time of the action gets nearer the present" (cross-referenced to Lesson 4's てくる/ていく comparison, p.69)

#### さらに — "further"
Expresses that a state described in a second clause (S₂) is stronger/higher than a state already described in a first clause (S₁) — 寮に1年いましたが、さらに、もう1年いようと思っています。("I stayed at a dormitory for one year; further, I think I will stay another year.")

#### nai-form + ずに — "without doing"
Equivalent to ~ないで (何も言わずに出ていった. = 何も言わないで出ていった. "He left without saying anything."). する's irregular nai-form gives せずに, not *しずに. Near-synonymous with ~なくて/~ないで but with its own usage-limitation profile (the book defers full disambiguation to a following comparison table not captured in this sampling pass).

### Lesson 7 (あのときはどうも — "Thanks for Back Then")

#### ~のも無理はない / ~のも無理はありません — "it is natural/understandable that ~"
Usually follows a negative-leaning statement: あの人が会社を辞めてしまったのも、無理はない。("It is understandable that the person quit.")

#### plain form (V/A/Na-exc./N) + わけではない — "it does not mean that ~"
Denies a prediction the listener/reader would naturally draw from a preceding statement — 田中さんは家もない。車もない。…しかし、お金がないわけではない。("Mr. Tanaka has no house or car… however, this does not mean he has no money.") Cross-referenced forward to Lesson 9's わけです family (p.156).

#### …ほど — "approximate degree" ("so ~ that…")
Expresses degree more concretely than たいへん/とても/少し/ちょっと would alone; interchangeable with …くらい in this use. ことばでは言えないほど苦労した。("I had more troubles than I could express with words.")

#### …より先に — "before ~ / no sooner than ~"
Means …よりまえに or …より早く; can be used rhetorically to stress a reaction even when the literal sequencing is physically implausible — 飛行機の事故があったと聞いて、部屋に入るより先にテレビのスイッチを入れた。("No sooner had I entered my room than I switched on the TV, having heard of a plane crash" — emphasizing haste, not literal physical sequencing).

### Lesson 9 (サルの視力検査 — "A Monkey's Eyesight Test")

#### 欲しい vs. 欲しがる — first-person vs. third-person desire
A speaker reports their *own* desire with plain 欲しい (わたしはカメラが欲しい, never *欲しがります/欲しがっています about oneself, since 欲しがる observes external looks/speech/behavior as evidence of someone *else's* desire). The same first-person/third-person split recurs with other "appearance" predicates, e.g. さびしい ("I am lonely") vs. さびしがる ("[he] is observed to be lonely").

#### plain form (V/A/Na-exc./N) + わけです/わけだ/わけである — "that's why ~, so it means that ~, no wonder"
わけ used alone as a noun means "reason" (訳を話してください。"Please tell me the reason."); the whole construction draws a logical/explanatory conclusion from a preceding statement.

### Lesson 10 (子どもの絵 — "Children's Drawings")

#### ~ような / ~みたいな — "as if ~" (cross-referenced back to Lesson 2's ~ように, p.29)
ガラスが割れたような音がした。／ガラスが割れたみたいな音がした。("There was a noise as of breaking glass.")

#### ところが — "but, while, however" (vs. しかし)
Both show opposition, but ところが is narrower: it requires an actual result/situation that differs from an expectation (もう少し待てば、田中さんはきっと来ると思っていました。ところが、来ませんでした。"I thought Ms. Tanaka would surely come… but she didn't come." — valid), and **cannot** be used when only the speaker's bare judgement/feeling follows an expectation-statement with no realized contrasting event (…しかし、遅いなあ。is fine; *…ところが、遅いなあ。is not). しかし therefore has a broader range of use than ところが. *(The handwritten marginalia noted above sits beside this grammar point's heading in the source scan; it was excluded from extraction.)*

#### X (noun) なりに — "in one's/its own way"
子どもは子どもなりに考える。("Children think in their own ways.") 東京の生活はそれなりに、田舎の生活もそれなりに、大変です。("Life in Tokyo and in the countryside both have their own particular problems.")

#### plain form (V/A/Na-exc./N) + のではないか (spoken: ~んじゃない/~んじゃないですか) — "I have an idea/feeling that ~"
Expresses the speaker's own uncertain judgement, not a denial — despite the surface negative ない, it does not negate the preceding content. 方法に問題があるのではないか。("I have an idea that there may be a problem with that method.")

---

## Vocabulary — Lesson 1 (舌を出したアインシュタイン)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 組み合わせる (くみあわせる) | to combine | verb | core | — | contemporary (source published 1995) | — | — | grammar_reference | n/a | plausible_unverified | 読むまえに section |
| 表情 (ひょうじょう) | expression, look | noun | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | |
| 応じる (おうじる) | to respond | verb | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | |
| 舌 (した) | tongue | noun | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | 本文; title word |
| アインシュタイン | Einstein | proper noun | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | |
| 撮影する (さつえいする) | to take a photo, to shoot a film | verb | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | |
| クラブ | club | noun | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | loanword, katakana |
| 行なう (おこなう) | to carry out, to conduct, to hold | verb | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | |
| 誕生パーティー (たんじょう-) | birthday party | noun | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | hybrid kanji+katakana compound |
| 済む (すむ) | to finish, to come to an end | verb | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | |
| 乗り込む (のりこむ) | to get in (a car) | verb | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | |
| 帰宅する (きたくする) | to go home, to come home | verb | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | |
| そこへ | then, thereupon | conjunction | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | |
| おおぜい | a lot of, many (people) | adverb/noun | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | |
| カメラマン | cameraman | noun | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | loanword |
| 注文をつける (ちゅうもんを-) | to make a special request | expression | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | |
| 向ける (むける) | to turn, to direct | verb | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | |
| 語句 (ごく) | words and phrases | noun | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | 文章の型 section |
| 本文 (ほんぶん) | text | noun | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | also the section-name itself |
| できごと | event | noun | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | |
| 起こる (おこる) | to take place, to happen, to occur | verb | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | |
| 写す (うつす) | to take a photo | verb | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | Q&A section |
| 家 (いえ) | house, home | noun | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | |
| しばらく | for a while | adverb | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | Grammar Notes section |
| 下りる (おりる) | to go down, to descend | verb | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | |
| まちがう | to make a mistake, to err | verb | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | 練習 section |
| 撮れる (とれる) | (a photo) is taken | verb (potential/spontaneous) | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | |
| 印 (しるし) | mark | noun | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | |
| 付ける (つける) | to attach, to give | verb | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | |
| ~ずつ | (one) by (one), (little) by (little) | suffix | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | ことばのネットワーク section (p.2 of appendix, scanned out of sequence at PDF p.234 — see coverage note) |
| 動作 (どうさ) | action, behaviour | noun | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | |
| バイク | motorbike | noun | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | loanword |
| あご | chin | noun | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | face-vocabulary set, fits Lesson 1's face-photo theme |
| ほお | cheek | noun | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | |
| 額 (ひたい) | forehead | noun | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | |
| まゆ毛 (まゆげ) | eyebrows | noun | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | |
| 怒る (おこる) | to get angry, to be offended | verb | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | |
| 出版する (しゅっぱんする) | to publish | verb | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | |
| 意地悪 (いじわる) | spiteful, mean, malicious | na-adjective/noun | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | |
| ユーモラス | humorous | na-adjective | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | loanword |
| 気が強い (きがつよい) | stouthearted | expression (i-adj.) | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | |
| 実際 (じっさい) | reality, actuality | noun | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | 書いてみよう・話し合ってみよう section |
| 教科書 (きょうかしょ) | textbook | noun | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | |
| 友人 (ゆうじん) | friend | noun | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | |
| 書き直す (かきなおす) | to rewrite | verb | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | |
| 話し合う (はなしあう) | to talk with each other | verb | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | |
| なぜ | why | adverb | core | — | contemporary (1995) | — | — | grammar_reference | n/a | plausible_unverified | |

**Morpheme breakdown (illustrative).** Japanese is agglutinative; this lesson's own causative-passive forms sampled in the Lesson 5 grammar point above are the clearest worked example in this chunk:

> **書かされる** (かかされる) = 書く (kak-, "write") + nai-stem change + さ (causative infix) + れる (passive) — "to be made to write." Demonstrates the stacked causative+passive morphology Japanese verb conjugation productively builds; see Lesson 5's Grammar Notes section above for the full Group I/II/III paradigm.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes, dialogue blocks, or explanatory prose. See `../../00_Reference_Extraction_Spec.md`.
