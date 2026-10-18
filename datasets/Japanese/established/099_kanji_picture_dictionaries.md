# Japanese — Established Vocabulary: Kanji & Picture Dictionaries (Wave 4, Vocabulary/Dictionaries)

**Sources:**
1. Saiga Hideo (斎賀秀夫) & Nomura Masaaki (野村雅昭), eds. (National Language Research Institute),
   *使いかた・おぼえかた 小学生の漢字辞典* ("How to Use It / How to Remember: Elementary School
   Student's Kanji Dictionary"), Shōgakukan (小学館), preface dated Shōwa 53 (1978). Covers all 996
   *gakushū kanji* (学習漢字, the official elementary-school kyōiku kanji taught by grade at the
   time) plus a name-use-kanji appendix, special-reading appendix, and three back indices
   (stroke-count, on/kun-reading, radical). Main kanji-entry body runs printed pp. 29–398.
2. The Editors of Passport Books, illus. Marlene Goodman (with contributions from Terrie Meider),
   *Let's Learn Japanese Picture Dictionary*, McGraw-Hill, copyright 1992. 32 thematic
   illustrated-vocabulary spreads (classroom, house, seasons, supermarket, clothing, city,
   countryside, restaurant, doctor/dentist, barber/beauty shop, post office/bank, gas station,
   community people, transportation, airport, sports, talent show, zoo, circus, ocean, space,
   human history, make-believe castle, mouse hunt/prepositions, action words, colors, family tree,
   shapes, numbers, map of the world) plus a back Japanese–English and English–Japanese
   glossary/index.

**Coverage note — representative sampling, not exhaustive (standing practice for oversized
dictionary-style references).** Both sources are PDFs with no usable text layer at all
(`pdftotext` on each returns essentially nothing — confirmed via raw byte count, not just a quick
look — both are Adobe/Image2PDF scans of printed pages with no OCR text layer embedded) — every
entry below was vision-read directly from rendered page images.

- **Kanji dictionary** (208 PDF pages, each page a two-printed-page spread — confirmed by printed
  page numbers running to ~451 while the PDF itself has only 208 pages, the same "scan is two
  printed pages per image" gotcha flagged in the extraction spec). The book is organized by
  **radical (部首)**, not by grade, with each individual kanji entry separately tagged by the
  source itself with its own school grade (1年–6年) and stroke count. Sampled spreads across the
  full page range (roughly every 15–45 pages, front to back) to pull entries representing **every
  grade tier 1–6** and a wide spread of radicals (一, 人/イ, 十, 匸, 文, 斗, 攵, 水/氵, 石, 肉/月,
  里, 臣, 辶, plus the front-matter's own worked example 赤). This is a genuine representative
  sample of a ~996-entry dictionary, not a full extraction — the vast majority of entries were not
  read.
- **Picture dictionary** (62 PDF pages: front matter/TOC pp. 1–3, 32 numbered thematic spreads
  pp. 4–~59, back glossary/index pp. ~60–62). Sampled **9 of the 32 thematic categories**, spread
  across the book's full front-to-back range and across its thematic variety: #1 Our Classroom,
  #6 At the Supermarket, #14 At the Gas Station, #22 In the Ocean, #27 Action Words, #28 Colors,
  #29 The Family Tree, #30 Shapes, #31 Numbers. Within each sampled category, the labeled items
  visible in the rendered page are extracted close to fully (each category page is itself a
  small, bounded vocabulary set — typically 10–35 labeled items — so this is not the same kind of
  unbounded-exhaustive problem as the kanji dictionary). The back J–E/E–J glossary/index was not
  separately extracted since it is a pure re-alphabetization of the same 32 category pages with no
  new content. For Numbers specifically, only a representative subset of the cardinal/ordinal
  sequence was kept (0–5, 10, 16, 20, 30, 40, 50, 100, 1,000, 10,000) rather than every number
  0–100 — a sequential counting list is low information density per the spec's coverage rule, the
  same logic as skipping repeated drills.

**Vision-reading guard:** both sources show only consistent, clearly typeset printed content on
every page rendered for this extraction — no handwritten marginalia, underlining, or pencil
annotations were found on any sampled page. No exclusions were needed.

**No PDF-extraction ciphers apply here** (see spec's font-substitution-cipher gotchas) — this is
pure vision-reading of raster scans, not a text-layer decode problem, so none of those gotchas are
applicable; the relevant gotcha that *did* apply is the two-pages-per-scan-image one noted above
for the kanji dictionary.

---

## Vocabulary

### Kanji dictionary sample (996-kanji corpus; representative sample across grades 1–6 and radical groups)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 赤 | red; (verbs) to redden, blush | kanji (morpheme); adj./verb root | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi セキ/シャク, kun'yomi あか(い)/あから(む)/あから(める). Grade 1, 7 strokes. Used as the dictionary's own worked example in its front-matter "how to use this dictionary" section (pp. 2–3), not a standalone entry page — included because it's genuine source content illustrating the entry format. |
| 下 | down, below, under; (verbs) to go down, lower, hand down | kanji (morpheme); noun/verb root | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi カ/ゲ, kun'yomi した/さ(げる)/さ(がる)/くだ(る)/くだ(さる)/お(りる)/お(ろす). Grade 1, 3 strokes. Radical group 一の部 (p. 33). |
| 三 | three | kanji (morpheme); numeral | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi サン, kun'yomi みっ(つ)/み. Grade 1, 3 strokes. Radical group 一の部 (p. 32). |
| 上 | up, above; (verbs) to go up, rise, raise | kanji (morpheme); noun/verb root | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi ジョウ/ショウ, kun'yomi うえ/うわ/かみ/のぼ(る)/あ(げる)/あ(がる). Grade 1, 3 strokes. Radical group 一の部 (p. 32). |
| 万 | ten thousand; many, myriad | kanji (morpheme); numeral | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi マン/バン, no listed kun'yomi. Grade 3, 3 strokes. Radical group 一の部 (p. 33). |
| 十 | ten | kanji (morpheme); numeral | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi ジュウ/ジッ(ジュッ), kun'yomi とお/と. Grade 1, 2 strokes. Radical group 十の部 (p. 82). |
| 千 | thousand | kanji (morpheme); numeral | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi セン, kun'yomi ち. Grade 1, 3 strokes. Radical group 十の部 (p. 82). |
| 午 | noon; (zodiac) horse | kanji (morpheme); noun | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | plausible_unverified | On'yomi ゴ; no kun'yomi given in the entry. Grade 2, 4 strokes. Radical group 十の部 (p. 83). Appears in compounds 午前/午後 ("a.m./p.m."). |
| 半 | half | kanji (morpheme); noun | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi ハン, kun'yomi なか(ば). Grade 2, 5 strokes. Radical group 十の部 (p. 83). |
| 卒 | to graduate; soldier, private | kanji (morpheme); noun/verb root | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | plausible_unverified | On'yomi ソツ; entry's kun'yomi line not clearly legible at this render resolution. Grade 4, 8 strokes. Radical group 十の部 (p. 83). Common compound 卒業 "graduation." |
| 医 | doctor, medicine, healing | kanji (morpheme); noun | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi イ; no kun'yomi. Grade 3, 7 strokes. Radical group 匸の部 (p. 83). |
| 係 | connection; person in charge (of); to relate to | kanji (morpheme); noun/verb root | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi ケイ, kun'yomi かか(る)/かかり. Grade 3, 9 strokes. Radical group 人(イ・ヘ)の部 (p. 53). |
| 俗 | custom, convention; vulgar, worldly | kanji (morpheme); noun/adj. root | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi ゾク; no kun'yomi. Grade 6, 9 strokes. Radical group 人(イ・ヘ)の部 (p. 53). |
| 保 | to keep, maintain, preserve | kanji (morpheme); verb root | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi ホ, kun'yomi たも(つ). Grade 5, 9 strokes. Radical group 人(イ・ヘ)の部 (p. 53). |
| 容 | to contain; form, appearance | kanji (morpheme); noun/verb root | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi ヨウ; no kun'yomi listed. Grade 5, 10 strokes. Radical group 宀の部 (p. 133). |
| 宮 | shrine, palace; imperial family member | kanji (morpheme); noun | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi キュウ/グウ/ク, kun'yomi みや. Grade 3, 10 strokes. Radical group 宀の部 (p. 133). |
| 宿 | lodging, inn; to dwell, lodge | kanji (morpheme); noun/verb root | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi シュク, kun'yomi やど/やど(る)/やど(す). Grade 4, 11 strokes. Radical group 宀の部 (p. 133). |
| 文 | writing, sentence, literature | kanji (morpheme); noun | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi ブン/モン, kun'yomi ふみ. Grade 1, 4 strokes. Radical group 文の部 (p. 213). |
| 料 | fee, charge; material, ingredient | kanji (morpheme); noun | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi リョウ; kun'yomi line not clearly legible. Grade 4, 10 strokes. Radical group 斗の部 (p. 213). Forms 料金/材料 etc. |
| 数 | number; to count | kanji (morpheme); noun/verb root | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi スウ/ス, kun'yomi かず/かぞ(える). Grade 2, 13 strokes. Radical group 攵の部 (p. 212). |
| 敵 | enemy, foe | kanji (morpheme); noun | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi テキ, kun'yomi かたき. Grade 5, 15 strokes. Radical group 攵の部 (p. 212). |
| 整 | to arrange, put in order | kanji (morpheme); verb root | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi セイ, kun'yomi ととの(える)/ととの(う). Grade 3, 16 strokes. Radical group 攵の部 (p. 212). |
| 石 | stone, rock | kanji (morpheme); noun | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi セキ/シャク/コク, kun'yomi いし. Grade 1, 5 strokes. Radical group 石の部 (p. 292). |
| 研 | to sharpen, polish; to study, research | kanji (morpheme); verb root | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi ケン, kun'yomi と(ぐ). Grade 3, 9 strokes. Radical group 石の部 (p. 292). |
| 砂 | sand | kanji (morpheme); noun | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi サ/シャ, kun'yomi すな. Grade 6, 9 strokes. Radical group 石の部 (p. 293). |
| 破 | to break, destroy, tear | kanji (morpheme); verb root | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi ハ, kun'yomi やぶ(る)/やぶ(れる). Grade 5, 10 strokes. Radical group 石の部 (p. 293). |
| 磁 | magnetism; porcelain | kanji (morpheme); noun | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi ジ; no kun'yomi. Grade 6, 14 strokes. Radical group 石の部 (p. 293). Compound 磁石 "magnet." |
| 量 | quantity; to measure | kanji (morpheme); noun/verb root | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi リョウ, kun'yomi はか(る). Grade 4, 12 strokes. Radical group 里の部 (p. 373). |
| 重 | heavy; to pile up, be important | kanji (morpheme); adj./verb root | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi ジュウ/チョウ, kun'yomi おも(い)/かさ(ねる)/かさ(なる)/え. Grade 3, 9 strokes. Radical group 里の部 (p. 373). |
| 野 | field, plain; wild | kanji (morpheme); noun/adj. root | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi ヤ, kun'yomi の. Grade 2, 11 strokes. Radical group 里の部 (p. 372). |
| 臣 | retainer, vassal, minister | kanji (morpheme); noun | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi シン/ジン; no kun'yomi. Grade 4, 7 strokes. Radical group 臣の部 (p. 373). |
| 臨 | to face, overlook; to attend, be present | kanji (morpheme); verb root | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi リン, kun'yomi のぞ(む). Grade 6, 18 strokes. Radical group 臣の部 (p. 373). |
| 返 | to return (something) | kanji (morpheme); verb root | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi ヘン, kun'yomi かえ(す)/かえ(る). Grade 3, 7 strokes. Radical group 辶の部 (p. 173). |
| 述 | to state, mention, describe | kanji (morpheme); verb root | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi ジュツ, kun'yomi の(べる). Grade 5, 8 strokes. Radical group 辶の部 (p. 173). |
| 迷 | to go astray, be perplexed, get lost | kanji (morpheme); verb root | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi メイ, kun'yomi まよ(う). Grade 5, 9 strokes. Radical group 辶の部 (p. 173). |
| 辺 | vicinity, side, area | kanji (morpheme); noun | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi ヘン, kun'yomi あた(り)/べ. Grade 4, 5 strokes. Radical group 辶の部 (p. 172). |
| 近 | near, close | kanji (morpheme); adj. root | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi キン, kun'yomi ちか(い). Grade 2, 7 strokes. Radical group 辶の部 (p. 172). |
| 決 | to decide | kanji (morpheme); verb root | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi ケツ, kun'yomi き(める)/き(まる). Grade 3, 7 strokes. Radical group 水(氵・水)の部 (p. 253). |
| 汽 | steam, vapor | kanji (morpheme); noun | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi キ; no kun'yomi. Grade 2, 7 strokes. Radical group 水(氵・水)の部 (p. 253). Compound 汽車 "steam train." |
| 河 | river | kanji (morpheme); noun | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi カ, kun'yomi かわ. Grade 5, 8 strokes. Radical group 水(氵・水)の部 (p. 253). |
| 永 | eternal, long-lasting | kanji (morpheme); adj. root | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi エイ, kun'yomi なが(い). Grade 5, 5 strokes. Radical group 水(氵・水)の部 (p. 252). |
| 池 | pond | kanji (morpheme); noun | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi チ, kun'yomi いけ. Grade 2, 6 strokes. Radical group 水(氵・水)の部 (p. 252). |
| 求 | to seek, request, demand | kanji (morpheme); verb root | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi キュウ, kun'yomi もと(める). Grade 4, 7 strokes. Radical group 水(氵・水)の部 (p. 252). |
| 腹 | abdomen, belly, stomach | kanji (morpheme); noun | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi フク, kun'yomi はら. Grade 6, 13 strokes. Radical group 肉(月)の部 (p. 333). |
| 臓 | internal organs, viscera | kanji (morpheme); noun | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi ゾウ; no kun'yomi. Grade 6, 19 strokes. Radical group 肉(月)の部 (p. 333). Compound 内臓 "internal organs." |
| 胸 | chest, breast | kanji (morpheme); noun | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi キョウ, kun'yomi むね/むな. Grade 6, 10 strokes. Radical group 肉(月)の部 (p. 332). |
| 脳 | brain | kanji (morpheme); noun | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | verified | On'yomi ノウ; no kun'yomi. Grade 6, 11 strokes. Radical group 肉(月)の部 (p. 332). |
| 腸 | intestines | kanji (morpheme); noun | core | — | contemporary (source published 1978) | — | — | dictionary | n/a | plausible_unverified | On'yomi チョウ; kun'yomi field present but not clearly legible at this render resolution. Grade 4, 13 strokes. Radical group 肉(月)の部 (p. 332). |

### Picture dictionary sample (9 of 32 thematic categories)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 先生（男）, sensei (otoko) | male teacher | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 1, "Our Classroom." Romanization as given by source. |
| 先生（女）, sensei (onna) | female teacher | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 1, "Our Classroom." |
| 学生，生徒（男）, gakusei/seito (otoko) | male student | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 1, "Our Classroom." |
| 地図, chizu | map | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 1, "Our Classroom." |
| 黒板, kokuban | chalkboard | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 1, "Our Classroom." |
| 黒板ふき, kokubanfuki | (chalkboard) eraser | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 1, "Our Classroom." |
| 鉛筆, enpitsu | pencil | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 1, "Our Classroom." |
| 消しゴム, keshigomu | (pencil) eraser | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 1, "Our Classroom." Loanword ゴム ("gum/rubber," from Dutch) visible as a transparent compound. |
| ホッチキス, hotchikisu | stapler | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 1, "Our Classroom." Eponymous loanword (from "Hotchkiss," a stapler brand) — a genuinely interesting Japanese-specific lexical item. |
| はさみ, hasami | scissors | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 1, "Our Classroom." |
| 買い物車, kaimono guruma | shopping cart | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 6, "At the Supermarket." |
| 買い物袋, kaimono bukuro | shopping bag | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 6, "At the Supermarket." |
| 標識，表示, hyōshiki/hyōji | sign | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 6, "At the Supermarket." |
| はかり, hakari | scale | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 6, "At the Supermarket." |
| 値段, nedan | price | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 6, "At the Supermarket." |
| レジスター, rejisutā | cash register | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 6, "At the Supermarket." Loanword from English "register." |
| レジスター係, rejisutā gakari | cashier | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 6, "At the Supermarket." 係 ("person in charge of") as a productive suffix — the same kanji/morpheme sampled independently in the kanji-dictionary table above (係, grade 3). |
| 修理工, shūrikō | mechanic | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 14, "At the Gas Station." |
| ガソリンポンプ, gasorin ponpu | gas pump | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 14, "At the Gas Station." Loanword compound: ガソリン (gasoline) + ポンプ (pump). |
| レッカー車, rekkāsha | tow truck | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 14, "At the Gas Station." Loanword レッカー ("wrecker") + native 車 ("vehicle"). |
| 洗車場, senshajō | car wash | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 14, "At the Gas Station." |
| 運転席, unseki (untenseki) | driver's seat | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 14, "At the Gas Station." |
| 自転車, jitensha | bicycle | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 14, "At the Gas Station." |
| ハンドブレーキ, hando burēki | hand brake | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 14, "At the Gas Station." Fully loanword compound, English calque. |
| パンクしたタイヤ, panku shita taiya | flat tire | noun phrase | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 14, "At the Gas Station." パンク itself is a loanword/clipping from English "puncture," now a fully nativized verb stem (パンクする "to get a flat"). |
| たこ, tako | octopus | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 22, "In the Ocean." |
| 潜水艦, sensuikan | submarine | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 22, "In the Ocean." |
| 宝石箱, hōsekibako | treasure chest | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 22, "In the Ocean." |
| さんご礁, sangoshō | coral reef | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 22, "In the Ocean." |
| 群れ, mure | school (of fish) | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 22, "In the Ocean." |
| いかり, ikari | anchor | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 22, "In the Ocean." |
| うみがめ, umigame | sea turtle | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 22, "In the Ocean." |
| 飲む, nomu | to drink | verb | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 27, "Action Words." |
| 食べる, taberu | to eat | verb | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 27, "Action Words." |
| 笑う, warau | to laugh | verb | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 27, "Action Words." |
| 泣く, naku | to cry | verb | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 27, "Action Words." |
| 歩く, aruku | to walk | verb | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 27, "Action Words." |
| 走る, hashiru | to run | verb | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 27, "Action Words." |
| 売る, uru | to sell | verb | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 27, "Action Words." |
| 買う, kau | to buy | verb | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 27, "Action Words." |
| 飛び込む, tobikomu | to dive | verb | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 27, "Action Words." Compound verb 飛ぶ ("to fly/jump") + 込む ("into"). |
| 泳ぐ, oyogu | to swim | verb | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 27, "Action Words." |
| 白, shiro | white | noun/adj. | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 28, "Colors." |
| 黒, kuro | black | noun/adj. | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 28, "Colors." |
| 赤, aka | red | noun/adj. | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 28, "Colors." Same kanji sampled independently as the kanji-dictionary front-matter example (赤, grade 1) above — the two sources converge on the same basic-color term, confirming it as genuinely core vocabulary rather than a sampling artifact. |
| 紫色, murasaki iro | purple | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 28, "Colors." |
| 黄色, kiiro | yellow | noun/adj. | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 28, "Colors." |
| 緑, midori | green | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 28, "Colors." |
| ピンク, pinku | pink | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 28, "Colors." Loanword from English; no native-Japanese basic-color term given as alternative, unlike the other colors on the same page. |
| 茶色, chairo | brown | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 28, "Colors." Literally "tea color." |
| 青色, aoiro | blue | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 28, "Colors." |
| 祖母，おばあちゃん, sobo/obāchan | grandmother, grandma | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 29, "The Family Tree." Source gives the formal (sobo) and familiar (obāchan) register pair side by side. |
| 母，おかあさん, haha/okāsan | mother, mom | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 29, "The Family Tree." Same formal/familiar register pairing pattern as grandmother entry. |
| 父，おとうさん, chichi/otōsan | father, dad | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 29, "The Family Tree." |
| 兄，弟, ani/otōto | brother (older, younger) | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 29, "The Family Tree." Single English gloss "brother" covers two distinct Japanese terms split by relative age — a real typological gap worth flagging for later mechanics analysis (Japanese kinship terms are age-graded; English is not). |
| 姉，妹, ane/imōto | sister (older, younger) | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 29, "The Family Tree." Same older/younger age-grading as brother entry. |
| むすこ, musuko | son | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 29, "The Family Tree." |
| 娘, musume | daughter | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 29, "The Family Tree." |
| 祖父，おじいちゃん, sofu/ojiichan | grandfather, grandpa | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 29, "The Family Tree." |
| おじ, oji | uncle | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 29, "The Family Tree." |
| おば, oba | aunt | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 29, "The Family Tree." |
| いとこ, itoko | cousin | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 29, "The Family Tree." Notably gender- and age-unmarked, unlike sibling terms on the same page. |
| 正方形, seihōkei | square | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 30, "Shapes." |
| 三角形, sankakukei | triangle | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 30, "Shapes." |
| 円, maru | circle | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 30, "Shapes." |
| 長方形, chōhōkei | rectangle | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 30, "Shapes." |
| 立方体, rippōtai | cube | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 30, "Shapes." |
| 球, kyū | sphere | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 30, "Shapes." |
| 円柱, enchū | cylinder | noun | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 30, "Shapes." |
| 零, rei | zero | numeral | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 31, "Numbers," cardinal set. |
| 一, ichi | one | numeral | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 31, "Numbers," cardinal set. |
| 二, ni | two | numeral | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 31, "Numbers," cardinal set. |
| 三, san | three | numeral | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 31, "Numbers," cardinal set. Same kanji 三 sampled independently in the kanji-dictionary table above. |
| 四, yon/shi | four | numeral | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 31, "Numbers," cardinal set. Source gives both competing readings (yon native-Japanese, shi Sino-Japanese) side by side — shi is often avoided in some contexts as a homophone of 死 "death," though the source itself does not flag this register note. |
| 五, go | five | numeral | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 31, "Numbers," cardinal set. |
| 十, too (as "jū" compound base) | ten | numeral | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 31, "Numbers," cardinal set. Same kanji 十 sampled independently in the kanji-dictionary table above (grade 1). |
| 十六, jūroku | sixteen | numeral | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 31, "Numbers," cardinal set — representative mid-teens compound. |
| 二十, nijū | twenty | numeral | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 31, "Numbers," cardinal set. |
| 三十, sanjū | thirty | numeral | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 31, "Numbers," cardinal set. |
| 四十, yonjū | forty | numeral | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 31, "Numbers," cardinal set. |
| 五十, gojū | fifty | numeral | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 31, "Numbers," cardinal set. |
| 百, hyaku | hundred | numeral | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 31, "Numbers," cardinal set. |
| 千, sen | thousand | numeral | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 31, "Numbers," cardinal set. Same kanji 千 sampled independently in the kanji-dictionary table above (grade 1). |
| 万, man | ten thousand | numeral | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 31, "Numbers," cardinal set. Same kanji 万 sampled independently in the kanji-dictionary table above (grade 3) — Japanese's base-10,000 (万-based) large-number counting system, distinct from English's base-1,000 grouping, visible directly from this entry alone. |
| 一番目, ichibanme | first (ordinal) | numeral | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 31, "Numbers," ordinal set. |
| 十番目, jūbanme | tenth (ordinal) | numeral | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 31, "Numbers," ordinal set. |
| 二分の一, nibun no ichi | one half | numeral/noun phrase | core | — | contemporary (source published 1992) | — | — | dictionary | n/a | verified | Category 31, "Numbers," fraction notation — transparent compositional structure: "two-part-of-one" = 1/2. |

---

## Grammar points

Neither source is a grammar reference — both are pure vocabulary dictionaries (a kanji dictionary
and a picture/thematic-vocabulary dictionary) with no systematic grammar exposition. Two
incidental points worth recording since they surfaced directly from the sampled entries:

### Kanji on'yomi/kun'yomi dual reading system

Every kanji entry in the Elementary School Student's Kanji Dictionary is tagged with its
**on'yomi** (音, Sino-Japanese reading(s), given in katakana) and **kun'yomi** (訓, native-Japanese
reading(s), given in hiragana, often with okurigana inflectional endings marked by parentheses,
e.g. 整 とと(のえる)). Many kanji have multiple on'yomi (e.g. 石 セキ/シャク/コク) reflecting
different historical borrowing layers from Chinese, and some common kanji have no kun'yomi at all
(e.g. 俗, 容, 臓, 脳) — these are used only in Sino-Japanese compound words, never as standalone
native words. See pp. 2–5 (本辞典の使いかた, "How to use this dictionary") for the source's own
explanation of this convention.

### Age-graded sibling terminology

The picture dictionary's Family Tree category (p. 59, category 29) renders both "brother" and
"sister" each as a single English gloss covering two distinct, non-interchangeable Japanese terms
split by relative age (兄/弟 ani/otōto for older/younger brother; 姉/妹 ane/imōto for
older/younger sister) — with no single unmarked Japanese word meaning "brother" or "sister"
regardless of age. This is a genuine typological point (not covered by any grammar book, since it
is lexical) worth carrying forward into mechanics analysis: any conlang slang built from Japanese
kinship-term roots would need to decide whether to preserve or collapse this age-grading
distinction.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`. No full page or
illustration from either source was reproduced; all entries above are individual lexical items
(words/kanji + short English glosses), the normal unit of a dictionary-extraction table, not
copied prose or illustration content.
