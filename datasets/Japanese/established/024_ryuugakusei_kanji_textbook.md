# Japanese — Established Vocabulary/Grammar: Ryūgakusei no Tame no Kanji no Kyōkasho Chūkyū 700 — representative sample across the full 700-kanji curriculum

**Source:** Satō Naoko (佐藤尚子) and Sasaki Hitoko (佐々木仁子), *Ryūgakusei no Tame no Kanji no Kyōkasho: Chūkyū 700* (留学生のための漢字の教科書 中級700), Kokusho Kankōkai (国書刊行会). PDF metadata gives a 2009 creation/scan date. 243 PDF pages, no offset between PDF page and printed page number except a consistent `printed_page = pdf_page − 1` (confirmed by cross-checking printed page numbers visible on the scan against the PDF page used to render them, at multiple points through the book). Entirely Japanese-medium with English glosses for every vocabulary item (and, per the book's own stated design in its preface, p.3, also Chinese and Korean glosses alongside the English — only the English is reproduced in this extraction; the preface explains the book targets JLPT-2-kyū-equivalent (roughly N2) intermediate learners and selected its 700 kanji by cross-referencing multiple widely-used elementary/intermediate textbooks).

**Book structure (established by direct inspection, not assumed from page-count arithmetic):** an opening "本書の特徴" (features of this book) section (pp. 5-12) explaining editorial choices (e.g. which readings were excluded as too rare, which elementary-level readings were reclassified as intermediate); **Chapter 1, "初級で学習した漢字の中級での読み方"** (pp. 13-24) — new, intermediate-level readings for kanji the student is assumed to already know from elementary study, **not** a re-teaching of the kanji themselves; **Chapter 2** (pp. 25-221), the main curriculum — 700 kanji numbered sequentially 1-700, generally 20 new kanji per lesson (課) presented 10-to-a-page with stroke count, full stroke-order diagram, on'yomi (katakana)/kun'yomi (hiragana) readings, and 1-2 example compound words each with English/Chinese/Korean glosses, followed by よみましょう (reading) and かきましょう (writing) drill pages — but periodically interrupted by **thematic "application" lessons** that teach register-specific vocabulary without introducing new numbered kanji (confirmed at 16課 "手紙・はがき" (Letters and Postcards, p.117), 24課 "論文" (Thesis/academic writing, p.167), and 32課 "いろいろなニュース・4" (reading news headlines, p.217)); the book ends with a cumulative review ("まとめ問題"), an answer-key reference, and a 音訓索引 (on/kun reading index, confirmed at p.229) that needs no vocabulary-table extraction of its own (it's a lookup table pointing back to kanji numbers already covered).

**Coverage note — representative sampling, not exhaustive, per dispatch instructions.** At 700 kanji across ~32 lessons, exhaustive extraction is out of scope. This file samples broadly across the full numeric/lesson progression rather than any single contiguous block: both pages of Chapter 1's "new readings for known kanji" section (kanji already covered elsewhere in this project's Japanese corpus, e.g. `007_doraemon_kanji_workbook.md`, but with genuinely new intermediate-level readings not previously extracted); regular vocabulary lessons 1, 2, 4, 8, 11, 15, and 19 (sampling kanji #1-8, 21-28, 61-68, 141-159, 209-218, 299-300, and 386-388 respectively, plus the final lesson's closing kanji #698-700) spread across the full 1-700 range; and all three thematic application lessons found (16, 24, 32), which carry register-specific vocabulary (formal correspondence, academic writing, news-headline style) not found in the regular numbered-kanji lessons at all. Drill/exercise pages (よみましょう/かきましょう/練習) were read for context but their sentences are not bulk-reproduced — a small number are cited briefly below as illustrative.

**Relationship to `007_doraemon_kanji_workbook.md` — genuine independent value, not overlap.** 007 is a native-curriculum workbook teaching Japan's own elementary-school Kyōiku-kanji (Grades 1-6, 1006 characters) to Japanese children, with no English glossing at all. This source is the reverse case: an L2/international-student curriculum assuming the learner already knows roughly the elementary set and building a *different*, non-overlapping 700-kanji intermediate list on top of it, with built-in English/Chinese/Korean glosses and explicit register-specific application lessons (letter-writing honorifics, academic hedging language, news-headline compound style) that 007 has no equivalent of. Spot-checked for direct character overlap: several kanji sampled here (馬, 象, 竹, 糸, 貝, 毛, 石 — Lesson 4) are indeed also in 007's Grade-1/2 elementary set, but Chapter 1 of *this* book exists specifically because of that overlap — it is not re-teaching those characters, only their *new, intermediate-level* readings (confirmed genuinely new content, e.g. 下 しも "the second half of the year" and 上 かみ "the first half of the year" are not elementary-level readings). No distinctive string/sentence overlap was found between the two files on inspection.

**Vision-reading confidence.** No text layer (`pdftotext` returns empty output despite `pdfinfo` reporting a tagged PDF — confirmed before vision-reading). Rendered via `pdftoppm` at 100dpi. No handwritten marginalia was found anywhere in the sampled pages — this is a clean, entirely printed scan. All sampled kanji boxes, readings, and compound-word glosses were clearly legible at this resolution; flagged as **verified** throughout except where noted per-row.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 飲 | eat/drink (as a compound element) | verb-stem | core | — | contemporary (source published c.2009) | — | — | grammar_reference | n/a | verified | On: イン. Compound: 飲食「eating and drinking」. Ch.1 "new intermediate readings" section, p.14. |
| 右 | right (direction) | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: ユウ. Compound: 左右「right and left」. Ch.1, p.14. |
| 雨 | rain | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: ウ. Kun: あま-. Compounds: 梅雨前線「a seasonal rain front」, 雨戸「shutters」; 梅雨 glossed with a non-standard reading つゆ (tsuyu, "the rainy season") flagged by the book's own ◯◯ symbol as an irregular/jukujikun-style reading. Ch.1, p.14. |
| 下 | below, under, down | noun/verb-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: ゲ. Kun forms: おーりる「下りる, to go down」, おーろす「下ろす, to lower」, さーがる「下がる, to hang down」, さーげる「下げる, to lower/hang」, くだーさる「下さる, to give」, くだーる「下る, to go down」, しも「下半期, the second half of the year」. Compound: 下宿する「to lodge」. Ch.1, p.14 — this whole reading set is new at intermediate level even though 007's Grade-1 extraction already covered 下's basic した/くだ-さる/お-ろす readings. |
| 外 | outside | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: ゲ. Compound: 外科「surgery」. Kun: はずーれる「外れる, to come off」, はずーす「外す, to take off」. Ch.1, p.14. |
| 学 | study, learning | verb-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | Kun: まなーぶ「学ぶ, to learn」 — new reading; elementary level only taught the ガク on'yomi (学校, 学生). Ch.1, p.14. |
| 間 | interval, room | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: ケン. Compound: 人間「a human being」. Ch.1, p.14. |
| 気 | spirit, air, feeling | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: ケ. Compound: 気配「a sign, indication」. Ch.1, p.14. |
| 休 | rest | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: キュウ. Compound: 休日「a holiday」. Ch.1, p.14. |
| 魚 | fish | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: ギョ. Compound: 金魚「a goldfish」. Kun: うお「魚市場, a fish market」 — alternative kun reading to 007's standard かい/さかな-adjacent forms. Ch.1, p.14. |
| 空 | sky; empty | noun/verb-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | Kun forms: あーく「空く, to be vacant」, あーき「空き, room/vacancy」, あーける「空ける, to empty」, から「空の, empty」. Ch.1, p.14. |
| 言 | word, say | verb-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: ゲン「言語, language」; ゴン「伝言, a message」 — the ゴン reading is the new intermediate item. Ch.1, p.14. |
| 古 | old | adj-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: コ. Compound: 中古の「used, secondhand」. Ch.1, p.14. |
| 後 | after, behind | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: コウ「後半, the second half/latter half」; kun: のち「後, after」. Ch.1, p.14. |
| 語 | word, language | verb-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | Kun: かたーる「物語, a story」 — new kun reading alongside the already-known ゴ on'yomi (日本語 etc.). Ch.1, p.14. |
| 行 | go, conduct | noun/verb-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: ギョウ「行事, an event」; kun: ゆーく「行く, to go」(alternate okurigana form of the more common いく). Ch.1, p.14. |
| 左 | left (direction) | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: サ. Compound: 左折する「to turn left」. Ch.1, p.14. |
| 山 | mountain | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: サン. Compound: 富士山「Mt. Fuji」. Ch.1, p.14. |
| 三 | three | numeral | core | — | contemporary | — | — | grammar_reference | n/a | verified | Kun: み「三日月, a crescent moon」. Ch.1, p.14. |
| 子 | child | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: ス「様子, a state/condition」 — unusual on'yomi for 子, distinct from the common シ. Ch.1, p.14. |
| 小 | small | adj-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | Kun: お「小川, a stream」. Ch.1, p.14. |
| 少 | few, little | adj-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: ショウ. Compounds: 少年「a boy」, 少女「a girl」, 少々「a few/a little」. Ch.1, p.14. |
| 上 | above, up | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | Kun: かみ「上半期, the first half of the year」, あーがる「上がる, to go up」, あーげる「上げる, to raise」, のぼーる「上る, to go up」. Ch.1, p.14. |
| 紙 | paper | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: シ. Compound: コピー用紙「copying paper」. Ch.1, p.17. |
| 試 | try, test | verb-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | Kun: ためーす「試す, to try/to test」. Ch.1, p.17. |
| 自 | self | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: シ「自然, nature」; kun: みずから「自ら, oneself」. Ch.1, p.17. |
| 持 | hold | verb-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: ジ. Compound: 持参する「to bring」. Ch.1, p.17. |
| 写 | copy, photograph | verb-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | Kun: うつーる「写る, to come out (in a photo)」. Ch.1, p.17. |
| 者 | person | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | Kun: もの「者, a person」. Ch.1, p.17. |
| 借 | borrow | verb-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: シャク. Compound: 借金「debt」. Ch.1, p.17. |
| 弱 | weak | adj-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: ジャク. Compound: 弱点「a weakness」. Ch.1, p.17. |
| 主 | main, lord | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | Kun: おも「主な, main」. Ch.1, p.17. |
| 首 | neck, head | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: シュ. Compound: 首相「a prime minister」. Ch.1, p.17. |
| 終 | end | verb-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: シュウ「終了する, to expire/to be finished」; kun: おーえる「終える, to finish」. Ch.1, p.17. |
| 集 | gather | verb-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: シュウ. Compound: 集合する「to gather, to assemble」. Ch.1, p.17. |
| 住 | dwell, live | verb-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | Kun: すーまう「住まい, a house/a home」. Ch.1, p.17. |
| 重 | heavy | adj-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: ジュウ「重力, gravity」, チョウ「貴重な, precious」; kun: かさーなる「重なる, to be piled up」, かさーねる「重ねる, to pile」. Ch.1, p.17. |
| 暑 | hot (weather) | adj-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: ショ. Compound: 暑中見舞い「a summer greeting」 (same formulaic greeting taught again in Lesson 16's letter-writing section — the overlap is deliberate, cross-referencing register). Ch.1, p.17. |
| 乗 | ride | verb-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: ジョウ「乗車する, to get on a train/bus」; kun: のーせる「乗せる, to pick up/help...on」. Ch.1, p.17. |
| 色 | color | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: ショク「〜色, ...colors」, シキ「景色, scenery/a landscape」. Ch.1, p.17. |
| 森 | forest | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: シン. Compound: 森林「forest」. Ch.1, p.17. |
| 親 | parent | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | Kun: おや「親, a parent」, したーしい「親しい, familiar/friendly/close」. Ch.1, p.17. |
| 世 | world, generation | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: セイ「世紀, a century」; kun: よ「世の中, the world」. Ch.1, p.17. |
| 正 | correct | adj-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: セイ. Compound: 正方形「a square」. Ch.1, p.17. |
| 青 | blue | adj-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: セイ「青年, youth」; irregular-reading compound (flagged ◯◯ by the book): 真っ青な「deep blue」. Ch.1, p.17. |
| 赤 | red | adj-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: セキ「赤道, the Equator」; irregular-reading compound: 真っ赤な「bright red」. Ch.1, p.17. |
| 早 | early | adj-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: ソウ「早朝, early morning」, サッ「早速, at once/immediately」. Ch.1, p.17. |
| 村 | village | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: ソン. Compound: 市町村「municipalities」. Ch.1, p.17. |
| 体 | body | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: タイ. Compound: 体重「weight」. Ch.1, p.17. |
| 短 | short | adj-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: タン. Compound: 短期「a short term」. Ch.1, p.17. |
| 池 | pond | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: チ. Compound: 電池「a battery」. Ch.1, p.17. |
| 着 | arrive, wear | verb-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: チャク「到着する, to arrive」; kun: つーける「着ける, to dress」, きーせる「着せる, to dress (someone)」. Ch.1, p.17. |
| 注 | pour | verb-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | Kun: そそーぐ「注ぐ, to pour」. Ch.1, p.17. |
| 級 | grade, class | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: キュウ. Compounds: 中級「intermediate (courses)」, 上級「advanced (courses)」. Lesson 1 (kanji #1), p.26. |
| 予 | in advance | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: ヨ. Compound: 予習する「to prepare one's lessons」. Lesson 1 (#2), p.26. |
| 定 | fix, regular | verb-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: テイ「予定, a plan/a schedule」, ジョウ「定規, a ruler」. Lesson 1 (#3), p.26. |
| 表 | express, surface, table | noun/verb-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: ヒョウ「表, a table」, 表現「expression」, 発表する「to make...public, to announce」; kun: おもて「表, the face」, あらわーす「表す, to express」. Lesson 1 (#4), p.26. |
| 授 | confer | verb-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: ジュ「授業, a class/a lesson」, 教授「a professor」. Lesson 1 (#5), p.26. |
| 宿 | lodge | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: シュク「宿題, homework」; kun: やど「宿, an inn/a hotel/a lodge」. Lesson 1 (#6), p.26. |
| 復 | return to | verb-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: フク「復習する, to review」, 回復する「to recover」. Lesson 1 (#7), p.26. |
| 辞 | word, resign | noun/verb-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: ジ「辞書, a dictionary」; kun: やーめる「辞める, to resign」. Lesson 1 (#8), p.26. |
| 解 | solve | verb-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: カイ「理解する, to understand」, 解答「an answer」, 解決する「to settle」; kun: とーける「解ける, to come out/loosen」, とーく「解く, to answer/solve」. Lesson 2 (#21), p.32. |
| 筆 | brush | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: ヒツ「鉛筆, a pencil」, 筆記試験「a written examination」; kun: ふで「筆, a writing brush」. Lesson 2 (#22), p.32. |
| 違 | differ, violate | verb-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: イ「違反する, to violate」; kun: ちがーう「違う, to differ」, 間違う「to mistake」. Lesson 2 (#23), p.32. |
| 消 | extinguish | verb-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: ショウ「消毒する, to disinfect/sterilize」, 消極的な「negative」; kun: きーえる「消える, to go out/fade」, けーす「消す, to extinguish/turn off」, 消しゴム「an eraser」. Lesson 2 (#24), p.32. |
| 次 | next | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: ジ「目次, a table of contents」, シ「次第に, gradually」; kun: つーぐ「次ぐ, next to...」, つぎ「次, next/following」. Lesson 2 (#25), p.32. |
| 線 | line | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: セン「下線, an underline」, 〜線「...Line (e.g. a train line)」. Lesson 2 (#26), p.32. |
| 最 | most | adv-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: サイ「最初に, at first」; kun: もっとーも「最も, most」. Lesson 2 (#27), p.32. |
| 適 | suitable | adj-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: テキ. Compound: 適切な「appropriate」. Lesson 2 (#28), p.32. |
| 馬 | horse | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: バ「乗馬, horse riding」; kun: うま「馬, a horse」. Lesson 4 (#61), p.44 — also a 007 Grade-2-level elementary character; this entry's intermediate compound 乗馬 is new relative to 007. |
| 象 | phenomenon, elephant | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: ショウ「気象, weather (conditions)」, ゾウ「象, an elephant」, 現象「a phenomenon」. Lesson 4 (#62), p.44. |
| 竹 | bamboo | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | Kun: たけ「竹, a bamboo」. Lesson 4 (#63), p.44 — also a 007 Grade-1 character. |
| 糸 | thread | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | Kun: いと「糸, (a) thread」. Lesson 4 (#64), p.44 — also a 007 Grade-2 character. |
| 貝 | shellfish | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | Kun: かい「貝, a shellfish」. Lesson 4 (#65), p.44 — also a 007 Grade-1 character (identical core gloss). |
| 毛 | hair, wool | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: モウ「羊毛, wool」; kun: け「毛, hair」, 毛糸「knitting wool」. Lesson 4 (#66), p.44. |
| 舟 | boat | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | Kun: ふね「舟, a boat」 — a less-common boat kanji distinct from the more frequent 船. Lesson 4 (#67), p.44. |
| 石 | stone | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: セキ「石油, petroleum」, シャク「磁石, a magnet」; kun: いし「石, a stone」, 石けん「soap」. Lesson 4 (#68), p.44 — also a 007 Grade-1 character; 石油/磁石/石けん compounds are new intermediate content. |
| 越 | go beyond, exceed | verb-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | Kun: こーす「越す, to go over」, こーえる「越える, to go over/pass」, 引っ越す「to move (house)」. Lesson 8 (#141), p.68. |
| 港 | port | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: コウ「空港, an airport」; kun: みなと「港, a port」. Lesson 8 (#142), p.68. |
| 神 | god, spirit | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: シン「神話, a myth」, 神経「a nerve」, ジン「神社, a Shinto shrine」; kun: かみ「神, god」. Lesson 8 (#143), p.68. |
| 美 | beautiful | adj-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: ビ「美容院, a beauty salon」, 美人「a beauty」; kun: うつくしい「美しい, beautiful」. Lesson 8 (#144), p.68. |
| 偉 | great | adj-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: イ「偉大な, great」; kun: えらーい「偉い, great」. Lesson 8 (#145), p.68. |
| 芸 | art, skill | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: ゲイ「園芸, horticulture」, 芸術「art」, 芸能「entertainment, performing arts」. Lesson 8 (#146), p.68. |
| 交 | intercourse, interchange | verb-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: コウ「交通, traffic/transportation」, 交番「a police box」; kun: まーじる/まーざる/まーぜる「交じる/交ざる/交ぜる, to mix」. Lesson 8 (#147), p.68. |
| 差 | difference | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: サ. Compounds: 差「difference」, 交差点「a crossing」. Lesson 8 (#148), p.68. |
| 園 | garden | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: エン. Compound: 公園「a park」. Lesson 8 (#151), p.70. |
| 昔 | old days | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | Kun: むかし「昔, old days」. Lesson 8 (#152), p.70. |
| 城 | castle | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | Kun: しろ「城, a castle」. Lesson 8 (#153), p.70. |
| 警 | police, warn | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: ケイ. Compounds: 警備する「to defend/to guard」, 警告する「to warn」. Lesson 8 (#154), p.70. |
| 察 | presume | verb-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: サツ「警察, police」, 観察する「to observe, to watch」. Lesson 8 (#155), p.70. |
| 署 | government office | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: ショ「消防署, a fire station」, 署名「a signature」. Lesson 8 (#156), p.70. |
| 防 | defend | verb-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: ボウ「予防する, to prevent」; kun: ふせーぐ「防ぐ, to prevent」, 防止する「to prevent」. Lesson 8 (#157), p.70. |
| 橋 | bridge | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: キョウ「鉄橋, an iron bridge」; kun: はし「橋, a bridge」. Lesson 8 (#158), p.70. |
| 容 | content | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: ヨウ. Compounds: 内容「content」, 容器「a container, a vessel」. Lesson 8 (#159), p.70. |
| 薄 | thin | adj-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | Kun: うすーい「薄い, thin」. Lesson 11 (#209), p.89. |
| 量 | quantity | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: リョウ「量, quantity」, 分量「quantity」; kun: はかーる「量る, to measure」. Lesson 11 (#210), p.89. |
| 湯 | hot water | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | Kun: ゆ「湯, hot water/boiled water/a bath」. Lesson 11 (#211), p.90. |
| 沸 | boil | verb-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | Kun: わーく「沸く, to boil」, わかーす「沸かす, to boil (something)」. Lesson 11 (#212), p.90. |
| 軟 | soft | adj-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | Kun: やわーらかい「軟らかい, soft/tender」. Lesson 11 (#213), p.90. |
| 混 | mix | verb-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: コン「混雑する, to be crowded」; kun: まーじる/まーざる/まーぜる「混じる/混ざる/混ぜる, to mix」. Lesson 11 (#214), p.90. |
| 等 | equal, class | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: トウ「〜等, and so on」, 等分する「to divide equally」, 高等の「high class」; kun: ひとーしい「等しい, equal」, 平等な「equal」. Lesson 11 (#215), p.90. |
| 丸 | circle, round | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | Kun: まる「丸, a circle」, まるーい「丸い, round」. Lesson 11 (#216), p.90. |
| 包 | wrap | verb-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: ホウ「包装, wrapping/packing」, 包帯「bandage」; kun: つつーむ「包む, to wrap」, 小包「a parcel, a package」. Lesson 11 (#217), p.90. |
| 巻 | roll | verb-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: カン「〜巻, volume...」; kun: まーく「巻く, to wind/to roll/to reel」. Lesson 11 (#218), p.90. |
| 呼 | call, invite, breathe | verb-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: コ「呼吸する, to breathe」; kun: よーぶ「呼ぶ, to call」. Lesson 15 (#299), p.115. |
| 雲 | cloud | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | Kun: くも「雲, cloud」. Lesson 15 (#300), p.115 — final kanji of Lesson 15. |
| 悲 | sad | adj-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: ヒ「悲劇, tragedy」; kun: かなーしい「悲しい, sad」, かなーしむ「悲しむ, to feel sad」. Lesson 19 (#386), p.141. |
| 王 | king | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: オウ. Compounds: 王「a king」, 女王「a queen」, 王子「a prince」. Lesson 19 (#387), p.141. |
| 想 | think, imagine | verb-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: ソウ. Compounds: 感想「impression」, 思想「thought」. Lesson 19 (#388), p.141. |
| 年賀状 | a New Year's greeting card | noun | formal | — | contemporary | — | — | grammar_reference | n/a | verified | Lesson 16 (application lesson, "手紙・はがき" Letters/Postcards), sample nengajō text, p.117. |
| 合格する | to pass (an exam) | verb | core | — | contemporary | — | — | grammar_reference | n/a | verified | Lesson 16, p.117 — appears in the sample nengajō's "congratulations on passing" text. |
| 様 | Mr./Ms. (honorific address suffix) | suffix | formal | — | contemporary | — | — | grammar_reference | n/a | verified | Lesson 16, p.117 — shown on a sample envelope addressed "川村礼子様皆様". |
| 見舞い | a get-well/sympathy greeting | noun | formal | — | contemporary | — | — | grammar_reference | n/a | verified | Compound 暑中見舞い「a summer (mid-season) greeting」, a formulaic seasonal correspondence genre. Lesson 16, p.117. |
| 忙しい | busy | adjective | core | — | contemporary | — | — | grammar_reference | n/a | verified | Lesson 16 sample letter text, p.117. |
| 順調な | steady, smooth-going | na-adjective | formal | — | contemporary | — | — | grammar_reference | n/a | verified | Lesson 16 sidebar vocabulary list, p.117. |
| 伺う | to ask/visit (humble) | verb | formal | — | contemporary | — | — | grammar_reference | n/a | verified | Lesson 16 sidebar vocabulary list (keigo register), p.117. |
| 御中 | (addressee honorific for organizations/companies) | suffix | formal | — | contemporary | — | — | grammar_reference | n/a | verified | Shown on sample business envelope: "○○会社 △△課 御中". Lesson 16, p.117. |
| 頂く | to receive (humble) | verb | formal | — | contemporary | — | — | grammar_reference | n/a | verified | Sidebar vocabulary list; also appears in the set phrase お返事頂ければ幸いです「It would be a pleasure to receive your reply」. Lesson 16, p.117. |
| 拝見する | to see/look at (humble) | verb | formal | — | contemporary | — | — | grammar_reference | n/a | verified | Set phrase お手紙、拝見しました「I have read your letter」 given as one of the lesson's model formal expressions. Lesson 16, p.117. |
| 占める | to occupy, to account for (a share/percentage) | verb | technical | — | contemporary | — | — | grammar_reference | n/a | verified | Lesson 24 (application lesson, "論文" Thesis/academic writing), used in the model sentence "Aが80%(8割)/大半を占めている". p.167. |
| 大幅に | substantially, by a large margin | adverb | technical | — | contemporary | — | — | grammar_reference | n/a | verified | Model sentence: "AがBを大幅に上回っている" ("A substantially exceeds B"). Lesson 24, p.167. |
| 横ばい | leveling off, flat (no meaningful change) | noun | technical | — | contemporary | — | — | grammar_reference | n/a | verified | Glossed in-book as "上下の変化がほとんどないこと" (little up/down change). Lesson 24, p.167. |
| 比率 | a ratio, a rate | noun | technical | — | contemporary | — | — | grammar_reference | n/a | verified | Used in the model paragraph describing a population-pyramid graph. Lesson 24, p.167. |
| 比較する | to compare | verb | technical | — | contemporary | — | — | grammar_reference | n/a | verified | Lesson 24 sidebar vocabulary, p.167. |
| 述べる | to state, to describe | verb | technical | — | contemporary | — | — | grammar_reference | n/a | verified | Model sentence: "第1章で述べたように..." ("As stated in Chapter 1..."), a standard academic cross-reference formula. Lesson 24, p.167. |
| 傾向 | a tendency, a trend | noun | technical | — | contemporary | — | — | grammar_reference | n/a | verified | Model sentence: "日本の平均寿命は年々長くなる傾向にある" ("Japan's average lifespan tends to lengthen year by year"). Lesson 24, p.167. |
| 仮定する | to assume, to hypothesize | verb | technical | — | contemporary | — | — | grammar_reference | n/a | verified | Model sentence for describing an experiment: "〜の条件のもとで、温度を一定と仮定し、計算を行った。" Lesson 24, p.167. |
| 拡大する | to enlarge, to expand | verb | technical | — | contemporary | — | — | grammar_reference | n/a | verified | Used captioning a figure: "図2-2は図2-1を5倍に拡大した図である". Lesson 24, p.167. |
| 著者 | an author | noun | technical | — | contemporary | — | — | grammar_reference | n/a | verified | Lesson 24's bibliographic-citation sub-section ("参考文献"), listing 著者・本の題・出版社・出版年 as the four mandatory citation elements. p.167. |
| 電柱 | a utility/telephone pole | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | Lesson 32 (application lesson, "いろいろなニュース・4" reading news headlines), headline 1: "◯◯島で台風14号大暴れ" ("柱を倒し..."). p.217. |
| 被害 | damage, harm | noun | formal | — | contemporary | — | — | grammar_reference | n/a | verified | Same typhoon-damage headline, p.217 — a staple of Japanese disaster-reporting register. |
| 濃い | thick, dense | adjective | core | — | contemporary | — | — | grammar_reference | n/a | verified | Headline 2: "濃い霧のため交通機関混乱" ("Traffic disrupted due to thick fog"). Lesson 32, p.217. |
| 混乱する | to become confused/chaotic | verb | formal | — | contemporary | — | — | grammar_reference | n/a | verified | Same headline, p.217; illustrates the news-headline convention of dropping the copula/particles for brevity ("交通機関混乱" rather than "交通機関が混乱する"). |
| 応じる | to respond, to comply | verb | formal | — | contemporary | — | — | grammar_reference | n/a | verified | Headline 3: "工場建設に反対の住民 話し合いに応じる". Lesson 32, p.217. |
| 総理大臣 | the Prime Minister | noun | formal | — | contemporary | — | — | grammar_reference | n/a | verified | Headline 5: "総理大臣 政治経済の基本方針を発表". Lesson 32, p.217. |
| 権利 | a right (legal/civil) | noun | formal | — | contemporary | — | — | grammar_reference | n/a | verified | Headline 7, about a children's-rights international conference: "「子供の権利を守る」国際大会が開かれ……". Lesson 32, p.217. |
| 郊外 | the suburbs | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | Headline 8, art-world news: "世界的画家の絵 パリ郊外で発見". Lesson 32, p.217. |
| 毒 | poison | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: ドク. Compounds: 毒「poison」, 気の毒な「poor, sorry (for someone)」. Lesson 32 (#698, final regular lesson's closing kanji), p.221. |
| 互 | mutual | adj-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: ゴ「相互の, mutual」; kun: たがーい「互いに, each other/mutually」. Lesson 32 (#699), p.221. |
| 刊 | publish | verb-stem | core | — | contemporary | — | — | grammar_reference | n/a | verified | On: カン. Compounds: 〜刊「...edition」, 朝刊「a morning paper」. Lesson 32 (#700) — the book's final numbered kanji, p.221. |

---

## Grammar points

### On'yomi/kun'yomi presentation convention

Throughout the book, on'yomi (Sino-Japanese readings) are printed in katakana and kun'yomi (native Japanese readings) in hiragana, directly beneath the large boxed kanji character, each paired with 1-2 example compounds. A small "◯◯" (double-circle) symbol marks a reading the editors consider irregular or non-compositional (jukujikun-style) rather than a regular on/kun reading — e.g. 梅雨 read つゆ rather than ばいう, and the idiomatic intensifiers 真っ青な/真っ赤な. (pp.14, 17.)

### Chapter 1's core organizing principle: new readings for already-known kanji

Chapter 1 (pp.13-24) is explicitly framed (per its own section headers, "初級レベルの漢字・1" etc.) as teaching *additional* readings for kanji the intermediate-level student is assumed to have already learned at the elementary (初級) level — not re-teaching the characters' basic forms or most common readings. This is confirmed by cross-checking: several of the kanji here (下, 上, 学, 語, 行, 子) already have well-established elementary readings taught in native-curriculum materials like this project's 007 extraction, and the readings given here are consistently the *less common* or *context-specific* ones (e.g. 下 read しも in 下半期, 上 read かみ in 上半期, 子 read ス in 様子) rather than duplicates of the basic readings.

### Lesson structure: 20 kanji per lesson, interrupted by register-specific application lessons

The main curriculum (Chapter 2) generally introduces 20 new numbered kanji per lesson (confirmed explicitly in Lesson 1's own practice page: "一つの課で20字ずつ勉強します", p.29), each followed by よみましょう (fill-in-the-reading) and かきましょう (fill-in-the-kanji) drills referencing a separate answer booklet ("答え➡別冊"). Periodically, however, a lesson instead teaches a real-world register or genre without introducing new numbered kanji at all — confirmed at Lesson 16 (formal letter/postcard writing conventions), Lesson 24 (academic/thesis writing — graph description, hedging, citation format), and Lesson 32 (reading condensed news-headline Japanese). These application lessons are where the book's highest-register, most specialized vocabulary is concentrated, and would be missed entirely by sampling only the numbered-kanji lessons.

### Formal correspondence conventions (Lesson 16)

The lesson teaches genre-specific formulas rather than general grammar: 年賀状 (New Year's cards) follow a fixed opening ("明けましておめでとうございます"), 暑中見舞い (summer greeting cards) follow a different fixed opening tied to the season, and business/formal envelopes use 御中 after an organization's name (never after a person's name, where 様 is used instead) — modeled directly on two sample envelope images on p.117.

### Academic/thesis register (Lesson 24)

The lesson presents three sub-skills as reusable templates rather than vocabulary drill: describing a graph/chart (占める, 大幅に上回る, 横ばい, 縦軸/横軸), describing an experiment or stating a result (仮定する, 表1から〜という傾向があることがわかった), and formatting a bibliography entry (著者・本の題・出版社・出版年, in that fixed order, illustrated with a worked citation example on p.167).

### News-headline compound style (Lesson 32)

Japanese news headlines are shown to systematically drop particles, the copula, and sometimes verb inflection to compress information into noun-compound strings (e.g. "工場建設に反対の住民 話し合いに応じる" rather than a full sentence with である/した forms) — the lesson's own framing device ("どんなニュースでしょう") asks the learner to reconstruct the likely full-sentence meaning from the compressed headline, with 8 worked headline examples spanning disaster, traffic, labor-dispute, legislative, political, military, international-rights, and arts-world news registers (p.217).

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes, dialogue blocks, or explanatory prose. Per `00_Reference_Extraction_Spec.md`, the handful of full headline/model-sentence quotes above are short, genuinely illustrative single lines used to demonstrate register conventions, not bulk reproduction of the source's own practice-exercise pages (whose longer dialogue/essay blocks were read for context but are not transcribed here).
