# Japanese — Established Vocabulary/Grammar: JBridge Series, part 2 (JBridge to Intermediate Japanese + answers)

**Source:** Satoru Koyama (小柳かおる), *JBridge to Intermediate Japanese* (Bonjinsha, ~2010, 121
scanned PDF pages, each page a two-printed-page spread — see pagination note below) and its
companion *JBridge to Intermediate Japanese — answers* booklet (15 pp., 解答編・聴解スクリプト
"Answer Key and Listening Scripts"). Continues from `076_jbridge_series.md` (JBridge for
Beginners). Both PDFs are scanned, image-only (no text layer); vision-read via rendered page
images (`pdftoppm`).

**Pagination gotcha confirmed on this source** (the same class of issue the extraction spec already
flags for other vision-only sources): *JBridge to Intermediate Japanese*'s main PDF page size
(1753×1275 pt, nearly 2:1 landscape) scans **two facing printed pages per PDF page**, not one
printed page per PDF page — e.g. PDF page 9 contains printed pages "2" (left) and the facing page
(right) as a single wide image. The answer booklet, by contrast, scans as ordinary single printed
pages per PDF page. This was caught by direct inspection (not assumed from `pdfinfo` alone),
consistent with the extraction spec's instruction to verify spread-vs-single-page empirically
before trusting any page-range arithmetic.

**Marginalia found and excluded — flagged per the vision-reading guard.** This specific scanned copy
of *JBridge to Intermediate Japanese* carries a previous owner's extensive handwritten annotation:
pencil/pen fill-ins for blank exercises, pink highlighter marks on the vocabulary list, and marginal
translation glosses into what appears to be Romanian (e.g. "reuniune de clasă," "navetă," "asigurare,"
"companie de asigurări," "actriță," "mândri") interleaved with occasional English glosses in the same
hand. **None of this handwritten content was extracted.** It was clearly distinguishable from the
book's own printed typeface and was excluded per the extraction spec's vision-reading guard — the
printed vocabulary list and printed grammar-box content (which this handwriting merely annotates or
highlights, without altering) were extracted normally. The answer booklet showed no marginalia.

**Coverage note / sampling strategy.** Per dispatch instructions, this book was sampled lightly —
only its first lesson (出 Lesson 1, "Introducing") was vision-read for its own pages (vocabulary
list, grammar-focus boxes, composition exercise), while Lessons 2–4's grammar points were captured
at a fuller level than a bare skeleton by cross-checking the **answer booklet**, which usefully
restates each lesson's grammar points as exercise answers with enough context to reconstruct the
rule (e.g. distinguishing ～ようだ from ～そうです with an explicit side-by-side explanation). Lessons
5–8 are captured only at the Contents-page skeleton level (topic/step titles and grammar-point
names), not independently vision-read or cross-checked against the answer booklet this pass — flagged
explicitly below so the gap is auditable.

---

## Vocabulary

Unless noted otherwise: **Usage Tier** = `core`; **Weight/Frequency** = `—`; **Attested Era** =
"contemporary (source published c. 2010)"; **Attested Region** / **Geographic Scope** = `—`;
**Source Type** = `grammar_reference`; **Transcription Confidence** = `n/a`; **Vision Reading
Confidence** = `plausible_unverified` unless noted.

### Lesson 1, Step 1 — 同窓会の写真 (Alumni Reunion Photo) — full end-of-lesson vocabulary (語彙1-1)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 相手 (あいて) | partner; the other party | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| ～合う (あう) | to do [verb] to/with each other | suffix (verb) | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | reciprocal-action suffix |
| アウトドア | outdoor (activities) | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | loanword |
| 明るい (あかるい) | bright; cheerful | i-adjective | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | verified | cross-checked vs. Step 3 personality-adjective matching exercise (明るい↔おとなしい pair) |
| 頭がいい (あたまがいい) | smart; clever; bright | expression | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | verified | cross-checked vs. Beginner-book L.1 same expression |
| 居酒屋 (いざかや) | izakaya; Japanese-style pub | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | culturally-specific term |
| 居間 (いま) | living room | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 今でも (いまでも) | still, even now | adverb | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| イラストレーター | illustrator | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | loanword, occupation term |
| いわゆる | so-called | prenominal | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 印象 (いんしょう) | impression | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | verified | lesson's own recurring topic term; cross-checked across multiple exercise pages |
| お互いに (おたがいに) | each other; mutually | adverb | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| お互いの (おたがいの) | mutual; each other's | prenominal | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| おとなしい | quiet; well-behaved | i-adjective | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | verified | cross-checked vs. Step 3 personality-adjective exercise |
| 温泉 (おんせん) | hot spring | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| ～課 (か) | counter for textbook lessons | counter | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | book's own structural metalanguage term |
| 書き換える (かきかえる) | to rewrite | verb (ichidan) | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 学習(する) (がくしゅう) | learning / to learn | noun+する-verb | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 感じる (かんじる) | to feel | verb (ichidan) | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 完成(する) (かんせい) | completion / to be completed | noun+する-verb | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 気が短い (きがみじかい) | short-tempered | expression | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | idiomatic 気+が+adjective construction |
| 記者 (きしゃ) | journalist | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 旧姓 (きゅうせい) | one's former/maiden name | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | culturally relevant to the lesson's own reunion-photo dialogue (旧姓木村さん) |
| 教師 (きょうし) | teacher | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| クラブ | club; student society | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | loanword |
| 繰り返し～(する) (くりかえし) | to repeat; repeatedly | noun+する-verb | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| グレー | grey | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | loanword |
| 詳しく (くわしく) | in detail | adverb | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 経営(する) (けいえい) | management / to manage | noun+する-verb | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 建築(する) (けんちく) | architecture / to construct | noun+する-verb | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 合コン (ごうコン) | "goukon," a group matchmaking/mixer party | noun | colloquial | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | culturally-specific social-practice term, clipped compound (合同コンパ) |
| 国語 (こくご) | (Japanese) National Language [school subject] | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 子供ができる (こどもができる) | to become pregnant | expression | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | euphemistic idiom, explicitly glossed by source rather than literal "a child becomes possible" |
| 幸せ(な) (しあわせ) | happiness; happy | な-adjective | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 自己紹介(する) (じこしょうかい) | self-introduction / to introduce oneself | noun+する-verb | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| システムエンジニア | systems engineer | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | loanword, occupation term |
| 自慢(する) (じまん) | to boast of; to be proud of | noun+する-verb | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 地元 (じもと) | home town; local | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 市役所 (しやくしょ) | city office | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 出版社 (しゅっぱんしゃ) | publishing company | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 主婦 (しゅふ) | housewife | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | verified | cross-checked vs. Beginner-book L.1 |
| 証券 (しょうけん) | securities; bond | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 助詞 (じょし) | (grammatical) particle | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | metalinguistic term |
| 女優 (じょゆう) | actress | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | source cross-refers to 俳優 "actor" as the gender-neutral/male counterpart |
| 知り合う (しりあう) | to get acquainted with | verb (godan) | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 数字 (すうじ) | number; numeral | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 政治家 (せいじか) | politician | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | verified | cross-checked vs. ～そう1 grammar-box example sentence (「あの人は政治家そうだ」, itself flagged by the source as an *incorrect* usage — see Grammar points) |
| 成績 (せいせき) | grade; (academic) record | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 専業主婦 (せんぎょうしゅふ) | full-time housewife | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | more specific than plain 主婦 |
| それぞれ | respectively; each | adverb | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 第一印象 (だいいちいんしょう) | first impression | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 通勤(する) (つうきん) | commuting to work / to commute | noun+する-verb | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | verified | cross-checked as a worked example of 〜ている's habitual-action sense in the lesson's own grammar box |
| つなぐ | to link; to connect | verb (godan) | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| デザイナー | designer | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | verified | cross-checked vs. Beginner-book L.1 (occupation set) |
| デザイン(する) | design / to design | noun+する-verb | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 動詞 (どうし) | verb | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | metalinguistic term |
| 同窓会 (どうそうかい) | alumni/class reunion | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | lesson's own title term |
| ～年生 (ねんせい) | …th-year student | counter | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | verified | cross-checked vs. Beginner-book L.1 |
| 残り (のこり) | the rest; remainder | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| ビジネススクール | business school | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | loanword |
| 一目ぼれ(する) (ひとめぼれ) | love at first sight | noun+する-verb | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | idiomatic compound (一目 "one glance" + 惚れ "falling for") |
| 表現(する) (ひょうげん) | expression / to express | noun+する-verb | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | metalinguistic term, recurs as a Focus-on-Language section header throughout the book |
| ひょっとして | possibly; perhaps; by any chance | adverb | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 不動産屋 (ふどうさんや) | real estate agency | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| ペア | pair | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | loanword, book's own pedagogical metalanguage (cf. PAIR WORK section) |
| 弁護士 (べんごし) | lawyer | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | verified | cross-checked vs. Beginner-book L.1 |
| 保険 (ほけん) | insurance | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| ほら | Look! (attention-getting interjection) | interjection | colloquial | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 間違っている (まちがっている) | to be mistaken; to be wrong | verb (godan, resultative) | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | used as the lesson's own grammar-exercise label ("Q4. 5〜7は間違っています") |
| 見習う (みならう) | to learn by example; to follow a model | verb (godan) | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 持って行く (もっていく) | to take (something) along | verb (godan) | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| モデル | model (fashion, or exemplar) | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | loanword |
| 役割 (やくわり) | role; part | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 奴 (やつ) | guy; fellow | noun | colloquial | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | explicitly casual/familiar register — used of a male friend in the lesson's own dialogue (「明るくて楽しい奴でね」) |
| 様態 (ようたい) | mode; state; appearance | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | metalinguistic term naming the lesson's ～そう1 grammar point |
| 離婚(する) (りこん) | divorce / to get divorced | noun+する-verb | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 例外 (れいがい) | exception | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 連体修飾節 (れんたいしゅうしょくせつ) | noun-modifying clause | noun | technical | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | metalinguistic term naming the lesson's own grammar point 1 |
| 論文 (ろんぶん) | (academic) paper; thesis | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |

### Lesson 1 — supplementary occupation/company/personality terms (VOCABULARY BUILDING box, not in the alphabetized list above)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 公務員 (こうむいん) | civil servant | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | verified | cross-checked vs. Beginner-book L.1-area occupation set |
| 警察官 (けいさつかん) | police officer | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 新聞記者 (しんぶんきしゃ) | newspaper reporter | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | compound of 新聞 (Beginner L.2) + 記者 (this lesson) |
| 旅行会社 (りょこうがいしゃ) | travel agency | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 保険会社 (ほけんがいしゃ) | insurance company | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 証券会社 (しょうけんがいしゃ) | securities company | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 広告会社 (こうこくがいしゃ) | advertising company | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 建築会社 (けんちくがいしゃ) | construction company | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 貿易会社 (ぼうえきがいしゃ) | trading company | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 不動産会社 (ふどうさんがいしゃ) | real estate company | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | company-name variant of 不動産屋 above |
| こわい (怖い) | scary | i-adjective | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | personality-impression term |
| きれい(な) | pretty; neat | な-adjective | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | verified | cross-checked vs. Beginner-book L.7 |
| 楽しい (たのしい) | fun; enjoyable | i-adjective | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | personality-impression term |

### Lesson 1, Step 3 — あなたはどんな性格？ (What's Your Personality?) — personality-adjective set (from the answer booklet's matching exercise, p. 2)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 物静か(な) (ものしずか) | quiet; composed | な-adjective | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | the answer key pairs this with 神経質 ("nervous/high-strung") in a matching exercise, though the exact relation (near-synonym vs. paired-contrast) wasn't independently confirmed from the exercise's own prompt text this pass |
| 神経質(な) (しんけいしつ) | nervous; high-strung; neurotic | な-adjective | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 社交的(な) (しゃこうてき) | sociable; outgoing | な-adjective | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 努力家 (どりょくか) | a hard worker; diligent person | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 気難しい (きむずかしい) | hard to please; difficult (personality) | i-adjective | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 温厚(な) (おんこう) | mild-mannered; gentle | な-adjective | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 前向き(な) (まえむき) | positive; forward-looking | な-adjective | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| だらしない | sloppy; slovenly | i-adjective | colloquial | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| わがまま(な) | selfish; willful | な-adjective | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| おおざっぱ(な) | careless; rough; broad-brush | な-adjective | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| おしゃべり(な) | talkative | な-adjective/noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 感受性豊か(な) (かんじゅせいゆたか) | highly sensitive/perceptive | な-adjective | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 人当たりがいい (ひとあたりがいい) | personable; pleasant to deal with | expression | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 協調性がない (きょうちょうせいがない) | not a team player; lacking cooperativeness | expression | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 負けず嫌い (まけずぎらい) | hates to lose; competitive | noun/な-adjective | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 思いやりがある (おもいやりがある) | considerate; thoughtful (of others) | expression | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | |
| 寂しがり屋 (さびしがりや) | a person who gets lonely easily | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | ～がり屋 "a person prone to feeling X" productive suffix |
| 恥ずかしがり屋 (はずかしがりや) | a shy person | noun | core | — | contemporary (c. 2010) | — | — | grammar_reference | n/a | plausible_unverified | same ～がり屋 suffix pattern as 寂しがり屋 |

---

## Grammar points

### Lesson 1, Step 1 — 同窓会の写真: noun-modifying clauses, ～ている (1), ～そう (様態/visual appearance)

1. **連体修飾節 (Noun-modifying clause)**: a predicate (verb, adjective, or clause) directly
   precedes and modifies a following noun, turning a full sentence about a referent into an
   embedded relative-clause description of that referent — e.g. (友だちは)東京に住んでいます
   ("[My friend] lives in Tokyo") → 東京に住んでいる友だちに電話した ("I called my friend who lives
   in Tokyo"). The lesson's own exercises extend this across a range of predicate types: かばんの中
   に入っている財布 ("the wallet that's in the bag"), 私に時計をくれた友だち ("the friend who gave me
   a watch"), 鈴木さんが勉強している東西大学 ("Tozai University, where Suzuki studies"). This is
   presented as a markedly more systematic treatment than the simple possessive/attributive の
   covered in the Beginner volume's Lesson 2.
2. **～ている (1) — three distinct senses distinguished explicitly by the source**: (a) an action
   in progress ("見ている" = currently watching); (b) a habitual/repeated action ("毎朝バスで通勤し
   ている" = commutes by bus every morning — a repeated action, not literally in-progress at the
   moment of speaking); (c) a resultative state ("このラジオは壊れている" = "this radio is [in a
   state of being] broken" — the breaking event is over, what remains is the state). The answer
   booklet is explicit that distinguishing these three requires attending to whether the verb
   describes a momentary action vs. an ongoing/repeated one vs. a state-change — notably it flags
   「住んでいる」や「勤めている」 as belonging to the long-duration/habitual class (3) rather than
   class (1), a distinction the source considered non-obvious enough to call out directly.
3. **～そう (1), 様態 ("seeming," based on direct visual/sensory impression)**: attaches to an
   i-adjective stem (おいしい→おいしそう), a na-adjective stem (きれい→きれいそう), or a verb stem
   (降り→降りそう) to express "looks like/seems like" based on what the speaker directly observes —
   雨が降りそうでしょう ("looks like it's going to rain, doesn't it") said while looking at the sky.
   The source explicitly contrasts this with a *different*, homophonous ～そう (伝聞, "hearsay,"
   reported later in the book at Lesson 6) which instead reports what the speaker heard from someone
   else, and flags a specific trap: ～そう (様態) **cannot attach directly to a noun** — 「あの人は
   政治家そうだ」("that person seems like a politician") is marked explicitly ungrammatical by the
   answer key, with the corrected form given as 政治家のようだ／政治家らしい instead. Two further
   corrections given by the same answer key: きれいな奥さんですね (な-adjective ようだ-pattern, not
   a bare そう attachment) and 元気じゃなさそう (そう attaching to the *negative* stem of a
   na-adjective, not the plain stem).

### Lesson 1, Step 2 — あのころ、そのころ: こそあ (distal demonstratives in reported speech), ～という, recollection-formulas [light cross-check only]

1. **こそあ (distal-demonstrative choice across speaker roles)**: the answer key's own diagram
   shows that when a speaker reports something another named person (課長, 吉田, 鈴木 in the
   example) is associated with, the referent is called あ（の店）from the reporting speaker's own
   distant vantage, but becomes そ（の店）once picked up by the *next* speaker in the conversation —
   i.e. こ／そ／あ choice tracks whose conversational "territory" the referent currently belongs to,
   not fixed physical distance. This is a more discourse-pragmatic treatment of こそあ than the
   simple physical-distance demonstratives taught in the Beginner volume's Lesson 2–3.
2. **～という ("the said/so-called …")**: used when the speaker believes the listener may not know
   the referent being introduced — explicitly glossed by the answer key as appropriate "when you
   think the listener doesn't know that thing/person."
3. **Recollection-trigger formulas**: the lesson teaches a small cluster of expressions used when a
   speaker is in the process of trying to recall something — たしか ("if I recall correctly"), ～っけ
   (sentence-final "wasn't it…?/was it…?", marking an uncertain memory check), and そういえば ("now
   that you mention it," signaling a sudden recollection prompted by the conversation).

### Lesson 1, Step 3 — あなたはどんな性格？: expressions for describing personality [light cross-check only]

Two numbered "expressions commonly used when discussing personality" grammar points are named by
the book's own Contents page but not independently re-sampled for their explanatory text this pass;
the personality-adjective vocabulary set itself (captured above) and the matching-exercise answer
key are the only material actually cross-checked.

### Lesson 2 (ベトナムへ行こう！, Taking a Trip) — existence sentences, conditionals, と-nominalizer, hedged recommendation, resultative/preparatory ～てある/～ておく, もう/まだ, comparison/contrast, 〜なる family [p. 4–5 of answer booklet]

1. **存在文 (existence sentences)**: 場所＋に＋モノ／人＋が＋ある／いる (for things/animates
   respectively) — e.g. 郵便局は病院のとなりにある ("the post office is next to the hospital").
2. **～たら／～なら (conditionals)**: distinguished by context in the exercises, though the specific
   semantic split (hypothetical sequence vs. topic-conditional) wasn't independently re-derived from
   the lesson's own explanatory text this pass — only the answer key's selections were observed.
3. **というのは～のことです ("what is meant by … is …")**: a formal definitional construction for
   explaining an unfamiliar term.
4. **～たほうがいい／～といい (soft recommendation)**: the answer key explicitly explains *why* a
   given recommendation phrasing is preferred in one exercise item: "北海道に行くのはどう？" or "北海
   道に行かない？" is marked as the better choice over a direct suggestion, specifically because no
   one has yet proposed a destination at that point in the conversation and the utterance also
   doesn't carry a "be careful" nuance — i.e. the choice of recommendation-formula depends on
   whether a destination/topic has already been established or is being proposed for the first time.
5. **～てある／～ておく (resultative-preparation vs. deliberate-preparation)**: both mark that
   something has been arranged in advance (買ってある "has been bought [and is ready]" vs. 買って
   おく "to buy [in preparation] for later"), distinguished by whether the focus is the current
   prepared state or the deliberate forward-looking act of preparing.
6. **もう～／まだ～ ("already"/"still, not yet")**: polarity-sensitive adverb pair tracking
   completion status.
7. **比較・対比の表現 (comparison/contrast expressions)**: より, のほうが, に対して, それに対して,
   比べて, も, ほど — the answer booklet's Step 2/Lesson 3 pages show these used to compare one
   group's traits against another's (the exercise explicitly contrasts "Filipino" vs. "Japanese"
   trait-attributions across a list of 13 personality/value items, e.g. 信仰心が強い "strongly
   religious" marked P[hilippine], 上下関係を大切にする "values hierarchical relationships" and
   恋愛について保守的 "conservative about romance" both marked JP — i.e. shared across both
   groups rather than exclusive to one).
8. **～ようだ vs. ～そうだ, explicitly distinguished by the answer key**: "～そうです is used only
   when talking about a directly seen 'impression'; ～ようです is used when talking about something
   the speaker has personally observed and then *inferred/surmised* (推測) from it" — a sharper,
   explicitly contrastive restatement of the same ～そう(様態) vs. ～ようだ distinction introduced in
   Lesson 1.
9. **～ような気がする ("I have a feeling that …")** — a hedged-impression construction.
10. **自動詞・他動詞 (intransitive/transitive verb pairs)**: named as a dedicated vocabulary-section
    topic for this lesson (cf. Lesson 4, Step 3's スクリプト reference to the same topic) — not
    independently sampled for its paired-verb list this pass.

### Lesson 3 (フィリピンでの留学生活, Cross Culture) — potential form, ～なる, ～なってくる, ～ばかり [p. 5–6]

1. **可能形 (potential form)**: the answer key explicitly flags that two items in one exercise (2
   and 5) are actually **尊敬語 (honorific)** constructions rather than true potential forms, and two
   others (3 and 4) are **受け身 (passive)** rather than potential — i.e. this lesson's own exercises
   are deliberately testing the learner's ability to distinguish three *formally similar* verb
   patterns (potential, honorific, passive) that are easy to conflate at this level, not just
   introducing the potential form in isolation.
2. **～なる (change-of-state, attaching to adjective/noun stems)**: い-adjective stem＋くなる,
   な-adjective stem＋になる, noun＋になる, and dictionary-form verb＋ようになる (change in
   capability/habit) are given as four parallel sub-patterns. The answer key explains why verbs like
   減る ("to decrease") resist being combined with ～なる a second time: "these verbs already contain
   the meaning of 'becoming' built in" — 減る itself already paraphrases as 少なくなる ("to become
   fewer"), so a further ～なる would be redundant.
3. **～なってくる ("becoming … [and the change is ongoing/approaching]")**: marks a change in
   progress or approaching, distinct from the completed change of plain ～なった.
4. **～ばかり ("just did X"; nothing-but-X)**: the answer key gives an explicit rule for choosing
   between ～たばかり and ～たところ: "～たばかり can be used if the speaker feels the event happened
   'recently,' while ～たところ can only be used when the event happened 'immediately after' another
   event" — i.e. ～たばかり has a looser recency window than ～たところ's strict immediacy
   requirement.

### Lesson 4 (それぞれの夢, Future) — desire/intention cluster [p. 7]

1. **～たい／～てみたい ("want to do / want to try doing")**: the answer key corrects a common
   confusion directly in its own exercise answers — 飲みたそうです／飲みたがっています is given as
   the fix for an item, and 子供に弁護士になってほしいです／なってもらいたいです as the fix for
   another, demonstrating the learner-facing distinction between describing one's *own* desire
   (～たい) vs. describing or inferring *someone else's* desire, which in Japanese cannot use plain
   ～たい for a third party and instead requires ～たがっている (observed desire) or ～てほしい／
   てもらいたい ("want [someone] to do X for me/us").
2. **～（よ）うと思う／～ことにする ("intend to"/"decide to")**: volitional-intention pair.
3. **～ことになる ("it has been decided/arranged that …", often agentless/passive-feeling)**: the
   answer key's own Q3 ranks three example sentences by perceived formality/distance (高←2→3→1→低
   "high to low"), suggesting this lesson treats ～ことになる as carrying a register/formality
   gradient worth drilling explicitly, not just a single fixed meaning.

### Lessons 5–8 — [skeleton only, from the book's own Contents page, not independently vision-read or cross-checked this pass]

- **Lesson 5, Mystery (ミステリー)**: STEP1 殺人事件現場 — 受け身 (passive), ～ている3, ～ている／
  ～てある; STEP2 目撃者の証言 — ～時, の／こと, 疑問詞＋か／～かどうか; STEP3 3億円事件 — expressions
  for making deductions/inferences, ～はずだ.
- **Lesson 6, Best Partner (ベスト・パートナー)**: STEP1 理想の結婚 — ～てあげる／～てもらう, ～てくれる;
  STEP2 ひとこと言ってあげる — ～そう (伝聞, hearsay — the counterpart to Lesson 1's 様態 そう), ～のに,
  ～てくれない／～てもらえない, ～てあげてください／～てもらってください; STEP3 国際結婚 — ～さえ～ば,
  たとえ～ても, 必ずしも～とは限らない.
- **Lesson 7, Food and Health (食と健康)**: STEP1 スターの健康法 — 尊敬語 (honorifics), ～ようにしている,
  ～ように／～ために; STEP2 アロマテラピー — 謙譲語 (humble language), connective conjunctions; STEP3
  あなたは知らせますか？ — ～べきだ, ～に対して／～にとって, ～としたら／～としても, ～も／～にすぎない.
- **Lesson 8, Education (教育)**: STEP1 日本の大学 — 使役1 (causative); STEP2 親の立場、子の立場 —
  使役2／使役受け身／使役＋てもらう, 使役形＋てほしい／使役形＋てもらいたい; STEP3 学校へ行かない子供
  たち — かえって, ～のでしょうか／～のではないでしょうか／確かに～かもしれません, ～わけ.

These four lessons' own vocabulary sections (カルチャーショック, 持ち物, 都市の特徴, 地理/宗教/気候,
社会の問題, 自動詞／他動詞, ミステリー, 性格 [2nd pass], 調理法／調味料／味, 教育問題) are named by the
Contents page but were not vision-read this pass.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `../../00_Reference_Extraction_Spec.md`. Example
sentences quoted above are the book's own short illustrative sentences (one line each), used to
evidence a specific grammar point rather than reproducing a dialogue or passage at length; the
personality-adjective and vocabulary lists are condensed term+gloss extractions, consistent with how
glossary-style material has been treated throughout this project.
