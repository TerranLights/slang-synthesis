# Japanese — Established Vocabulary/Grammar: *Remembering the Kanji 3* (Heisig) — Representative Sample Across the Full Volume

**Source:** James W. Heisig (preface/editorial contribution by Tanya Sienko), *Remembering the Kanji,
Volume 3: Writing and Reading the Japanese Characters for Upper-Level Proficiency* (Japan
Publications Trading Co.; embedded PDF metadata: created 2001, last modified 2002 — see note on
edition dating below). 474 pages, covering the roughly 1,000 kanji needed for full literacy beyond
the ~2,042/2,200 "general-use" characters taught in Volumes 1–2 (frames ≈2068–3201+ in this volume's
own numbering, which continues directly from Volume 1/2's frame count). **Representative sampling**
was used given the book's scale (per dispatch instructions) — not exhaustive extraction of all
~1,000 characters.

**Sampling methodology.** Sixteen pages were sampled at roughly even intervals across the book's
full structure, hitting every one of its 13 realized chapters (Part One "Writing," chapters 1–6, and
Part Two "Reading," chapters 7–13): printed pp. 20, 50, 90, 130, 150, 161, 163, 170, 191, 216, 246,
276, 311, 349, 358 (one page per chapter target; p. 50 and the partial top-of-page entry on p. 90
were cross-checked but trimmed — see gotchas below). Every frame entry appearing on a sampled page
was extracted in full (not sub-sampled further) to preserve each page's complete context.

**PDF extraction gotchas found on this source:**
- **Cosmetically corrupted text layer for kanji glyphs specifically, confirmed clean for everything
  else.** `pdftotext -layout` reliably extracts the frame number, Heisig keyword, primitive-element
  composition gloss (e.g. "father … metal"), and stroke count for every entry — this was cross-
  checked against rendered page images on every sampled page and matched exactly, word for word. The
  one field `pdftotext` cannot recover is the actual kanji character glyph itself, which renders as
  unrelated single-glyph mojibake (e.g. "ß", "Î", "›") due to a font-substitution encoding in the
  embedded font — **not** a fixed decodable 1:1 cipher checked here (no attempt was made to brute-
  force a mapping since vision-reading the headline glyph on each sampled page was fast and fully
  reliable). **Every kanji character in this file's Term column was read directly from a rendered
  page image (`pdftoppm`), not from the corrupted text layer.** English keywords, frame numbers,
  primitive glosses, and stroke counts came from the (reliable) text layer, cross-verified against
  the same images.
- **Printed-page-to-PDF-page offset is +4 through most of the book but breaks down near the end.**
  `pdf_page = printed_page − 4` held consistently through chapter 13 (verified at printed pp.
  20/50/90/130/150/161/163/170/191/216/246/276/311/349/358, i.e. PDF pages 16/46/86/.../353). It does
  **not** hold past that point.
- **The table-of-contents-listed "14 Supplementary Kanji" chapter (printed pp. 359–370) could not be
  located in the actual page-content flow.** Chapter 13 ("Readings of Old & Alternate Forms") content
  is still running at printed p. 358 (PDF p. 353); the very next PDF page (354) is already the
  "INDEX 1 / NUMBER OF STROKES" section-title page, and PDF p. 355 is printed p. 372 — i.e. Index 1
  itself begins at printed p. 371, one page after where the TOC says Chapter 13 ends (p. 358) and
  twelve pages before where the TOC says Chapter 14 begins and ends (pp. 359–370). A full-text search
  of the entire extracted document for "Supplementary Kanji" as a running head returned zero matches
  outside the Contents listing itself. **This looks like a genuine discrepancy between this PDF's
  actual pagination and its own printed table of contents** (possibly a different print run/edition
  than the one the TOC was typeset for) rather than a sampling artifact — flagged here rather than
  silently working around it. No content was extracted "from" Chapter 14 since no such chapter
  appears to exist in this file's actual page sequence.
- **Edition/printing year is not pinned down precisely.** The PDF's own embedded metadata gives
  CreationDate 2001 and ModDate 2002 (Acrobat Distiller 4.05), and the Introduction/Preface text
  refers to the publisher as "Japan Publications Trading Company" (the 1994 1st-edition / pre-2008
  University of Hawai'i Press publisher), consistent with this being the 2001 2nd printing/edition
  rather than the later (2008+) University of Hawai'i Press edition. Used here as "contemporary
  (source dated 2001–2002 per embedded PDF metadata)" per the extraction spec's coarse whole-book
  dating allowance — no more precise claim is made.

**No vision-reading marginalia found.** All sampled pages were clean, consistently typeset print —
no handwritten annotation was present on any page inspected.

---

## Vocabulary

Chapters 1–6 (Part One: Writing) teach isolated kanji via Heisig's primitive-composition mnemonic
method — keyword + primitive-element breakdown + stroke count, with no reading taught yet (readings
are the subject of Part Two). Chapters 7–13 (Part Two: Reading) group previously-written kanji by
shared on'yomi reading and supply real compound words/readings/glosses, which is where genuine
lexical (word-level) content appears. The **Notes** column records each entry's frame number,
Heisig's own primitive-composition gloss, and (for Part Two entries) the on'yomi/kun'yomi reading —
this project's extraction spec has no dedicated "reading" column, so it is folded in there.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 艘 | small craft (boat counter) | noun | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2068, p. 20. Primitives: boat … mortar … walking stick … crotch [15 strokes]. |
| 犀 | rhinoceros | noun | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2069, p. 20. Primitives: flag … I Ching … walking stick … cow [12 strokes]. |
| 皐 | lunar month | noun | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2070, p. 20. Primitives: white dove … I Ching … needle [11 strokes]. |
| 脊 | spinal column | noun | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2071, p. 20. Primitives: I Ching … umbrella … flesh [10 strokes]. |
| 畷 | rice-field footpath | noun | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2072, p. 20. Primitives: field … stitching [13 strokes]. Text cross-refs paddy-ridge 畔 (I.1204) and paddy-field ridge 畦 (frame 2571). |
| 弥 | more and more | adverb | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2241, p. 50. Primitives: bow … reclining … small [8 strokes]. |
| 弛 | loosen | verb | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2242, p. 50. Primitives: bow … scorpion [6 strokes]. |
| 粥 | rice gruel | noun | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2243, p. 50. Primitives: rice between two bows [12 strokes]. |
| 挽 | lathe | noun/verb | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2244, p. 50. Primitives: fingers … rabbit [11 strokes]. |
| 撞 | bump into | verb | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2245, p. 50. Primitives: fingers … juvenile [15 strokes]. |
| 扮 | disguise | verb | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2246, p. 50. Primitives: fingers … part [7 strokes]. Cross-check: reappears as the base character for the real word 扮装 (フンソウ, "get-up; disguise") at frame 2678/p. 276 — same frame number cited both places, confirming internal consistency. |
| 棉 | raw cotton | noun | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2512, p. 90. Primitives: tree … white … towel [12 strokes]. |
| 楯 | escutcheon | noun | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2513, p. 90. Primitives: tree … shield [13 strokes]. |
| 榎 | hackberry | noun | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2514, p. 90. Primitives: tree … summer [14 strokes]. Also reappears at frame 2514/p. 349 as kun'yomi word 榎 (えのき, "thackberry; lotus tree") — same frame number, confirming cross-chapter consistency. |
| 樺 | birch | noun | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2515, p. 90. Primitives: tree … splendor [14 strokes]. |
| 槍 | lance | noun | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2516, p. 90. Primitives: tree … godown [14 strokes]. |
| 柘 | wild mulberry | noun | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2517, p. 90. Primitives: tree … rock [9 strokes]. |
| 麺 | noodles | noun | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2752, p. 130. Primitives: barley … mask [16 strokes]. |
| 麹 | malt | noun | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2753, p. 130. Primitives: barley … bound up … rice [15 strokes]. |
| 釦 | button | noun | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2754, p. 130. Primitives: metal … mouth [11 strokes]. |
| 銚 | keg | noun | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2755, p. 130. Primitives: metal … portent [14 strokes]. |
| 鋤 | plow | noun | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2756, p. 130. Primitives: metal … help [15 strokes]. Book notes this is specifically the plow whose blades doubled as a meat-grilling surface. |
| 夷 | ebisu (archaic ethnonym) | noun | archaic | — | contemporary (source dated 2001–2002) | Japan (historical, north of present-day Tokyo) | national | grammar_reference | n/a | verified | Frame 2881, p. 150. Primitives: great … bow [6 strokes]. Cultural note: *ebisu* is a Japanization of the Ainu word *enchu* ("person"); historically denoted the "uncivilized" peoples north of present-day Tokyo. |
| 戚 | relatives | noun | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2882, p. 150. Primitives: uncle … parade [11 strokes]. |
| 嚢 | cyst | noun | technical.medical | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2883, p. 150. Primitives: needle … middle … crown … eight … celery … scarf [19 strokes] — one of the most complex single primitives chains sampled. |
| 丼 | domburi (rice bowl) | noun | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2884, p. 150. Primitives: well … drop [5 strokes]. |
| 暢 | carefree | adjective | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2885, p. 150. Primitives: monkey … piggy bank [14 strokes]. |
| 廻 | circling | verb | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2886, p. 150. Primitives: stretch … -times [9 strokes]. |
| 畿 | capital suburbs | noun | regional | — | contemporary (source dated 2001–2002) | Kyoto–Osaka area | regional | grammar_reference | n/a | verified | Frame 2887, p. 150. Primitives: two cocoons … field … fiesta [15 strokes]. Reappears at p. 191 in real compound 近畿 (キンキ, "region around Kyoto–Osaka"). |
| 噸 | ton | noun | archaic | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2949, p. 161. Phono-semantic compound: mouth (sound marker, pronounced like the English "ton") + immediate [16 strokes]. Book notes this device — adding "mouth" purely to signal a foreign-sound reading — is borrowed from written Chinese convention. |
| 哩 | mile | noun | archaic | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2950, p. 161. Primitives: mouth … one *ri* [10 strokes]. "Mouth" marks a foreign (Western) unit of measurement distinct from the native *ri*. |
| 浬 | nautical mile | noun | archaic | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2951, p. 161. Primitives: water … one *ri* [10 strokes]. Japan had no native unit for nautical *ri*, so this character was coined for the Western nautical mile. |
| 吋 | inch | noun | archaic | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2952, p. 161. Primitives: mouth … glue [6 strokes]. |
| 呎 | feet | noun | archaic | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2953, p. 161. Primitives: mouth … *shaku* [6 strokes]. |
| 菩 | bo tree (bodhi tree) | noun | literary | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2957, p. 163. Primitives: flowers … vase … mouth [11 strokes]. Buddhist-loanword phonetic character. |
| 唖 | babble | verb | literary | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2958, p. 163. Primitives: mouth … Asia [10 strokes]. Keyword sense: a baby's "oooing and aaaing." |
| 迦 | Sanskrit "ka" | phonetic syllable | literary | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2959, p. 163. Primitives: add … road [8 strokes]. Used to transliterate the Sanskrit sound "ka" in Buddhist terms. |
| 那 | interrogative (classical particle) | particle | archaic | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2960, p. 163. Primitives: sword … two … city walls [7 strokes]. Classically an interrogative part of speech; used chiefly today for its sound. |
| 牟 | moo | interjection | archaic | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2961, p. 163. Primitives: elbow … cow [6 strokes]. Classical character representing a cow's sound. Book notes the two frames immediately after this one (not sampled directly) are the Chinese phonetic transliteration of "coffee." |
| 聾 | deafness [old form] | noun | archaic | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2983, p. 170. Primitives: dragon [old] … ear [22 strokes]. |
| 慾 | longing [old form] | noun | archaic | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2984, p. 170. Primitives: longing … heart [15 strokes]. Differs from standard form 欲 (I.92) only by the added "heart" element at the bottom. |
| 瓦 | span [old form] | noun | archaic | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2985, p. 170. Primitives: tile … floor [6 strokes]. Standard form 亙 (I.32) is also the form used when this element serves as a primitive elsewhere; e.g. old form 恆 → modern abbreviation 恒 (I.620). |
| 躯 | body [old form] | noun | archaic | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2986, p. 170. Primitives: somebody … ward [11 strokes]. Standard form 身 (I.1248) has largely replaced this older character today. |
| 嶽 | Point [old form, placename element] | noun | archaic | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2987, p. 170. Primitives: mountain … prison [17 strokes]. The abbreviated modern form 岳 (I.1330) moves "mountain" to the bottom — an unusual transformation per the book's own note. |
| 磯 (いそ) | rocky beach | noun | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2594, p. 191, "Old Pure Groups" ch. 7. On'yomi キ (pure-group reading, shared with 幾/機). |
| 近畿 (キンキ) | region around Kyoto–Osaka | noun | regional | — | contemporary (source dated 2001–2002) | Kyoto–Osaka area | regional | grammar_reference | n/a | verified | Frame 2887, p. 191. On'yomi キ. Real compound built on the isolated-kanji 畿 entry above. |
| 嬬 (つま) | wife | noun | archaic | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2203, p. 191. On'yomi ジュ (pure-group reading shared with 需/儒). |
| 濡首 (じゅしゅ) | dead drunk | noun | colloquial | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2329, p. 191. On'yomi ジュ. |
| 濡れる (ぬれる) | to become wet; to be impassioned | verb | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2329, p. 191. Kun'yomi form of 濡, listed alongside 濡首 on the same frame. |
| 鍬 (くわ) | hoe | noun | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2762, p. 191. On'yomi シュウ (pure-group reading shared with 秋/愁). |
| 萩 (はぎ) | Japanese bush clover | noun | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2351, p. 191. On'yomi シュウ. |
| 杖罪 (ジョウザイ) | flogging; caning | noun | archaic | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2504, p. 216, "New Pure Groups" ch. 8. On'yomi ジョウ (pure-group reading shared with 丈). |
| 杖 (つえ) | cane; walking stick | noun | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2504, p. 216. Kun'yomi form, same frame as 杖罪. |
| 垢塵 (コウジン) | dirt; filth | noun | formal | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2187, p. 216. Reading コウ・ク (semi-pure group with exceptions, shared with 后). |
| 無垢 (ムク) | immaculate; undefiled | adjective | formal | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2187, p. 216. Same frame as 垢塵/垢. |
| 垢 (あか) | stain | noun | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2187, p. 216. Kun'yomi form, same frame. |
| 筑前 (チクゼン) | old name for northwest Fukuoka Prefecture | proper noun | regional | — | contemporary (source dated 2001–2002) | northwest Fukuoka Prefecture | regional | grammar_reference | n/a | verified | Frame 2637, p. 216. On'yomi チク (pure-group reading shared with 筑/築). Historical provincial name (*kuni*), not current administrative usage. |
| 斬首 (ザンシュ) | decapitation | noun | formal | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2092, p. 216. On'yomi ザン (pure-group reading shared with 斬/暫). |
| 斬る (きる) | to cut down; to behead | verb | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2092, p. 216. Kun'yomi form, same frame as 斬首. |
| 愚昧 (グマイ) | stupidity; ignorance | noun | formal | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2445, p. 246, "Semi-Pure Groups" ch. 9. On'yomi マイ (group shared with 未/味/魅/妹). |
| 柿 (かき) | persimmon | noun | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2481, p. 246. On'yomi シ (group shared with 市/姉/肺). |
| 樽 (たる) | cask; keg | noun | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2506, p. 246. On'yomi ソン (group shared with 尊/遵). |
| 鱒 (ます) | trout | noun | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2814, p. 246. On'yomi ソン, same reading group as 樽. |
| 綺麗 (キレイ) | beautiful; clean | adjective (na-adjective) | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2667, p. 246. On'yomi キ (group shared with 奇/寄/騎). High-frequency everyday word (not a rare literary term, despite the character's complexity). |
| 綺 (あや) | — (used in given names only) | proper-noun element | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2667, p. 246. Kun'yomi name-reading, same frame as 綺麗. |
| 醇化 (ジュンカ) | refinement; sublimation | noun | formal | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2751, p. 276, "Mixed Groups" ch. 10, Group A. On'yomi ジュン. |
| 醇い (あつい) | warm; cordial | adjective | literary | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2751, p. 276. Kun'yomi form, same frame as 醇化. |
| 惇い (あつい) | warm; cordial | adjective | literary | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2279, p. 276. Reading ジュン・トン (mixed-group — shares a character shape with the ジュン group but takes a second, divergent on'yomi). |
| 敦厚 (トンコウ) | simplicity; naivete | noun | literary | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2931, p. 276. On'yomi トン, same mixed group as 惇. |
| 扮装 (フンソウ) | get-up; disguise | noun | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2246, p. 276. On'yomi フン. Same frame number as the isolated-kanji 扮 "disguise" entry from p. 50, confirming cross-chapter internal consistency. |
| 開衿 (カイキン) | open collar | noun | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2623, p. 311, "A Potpourri of Readings" ch. 11. On'yomi キン. |
| 衿 (えり) | collar | noun | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2623, p. 311. Kun'yomi form, same frame. |
| 沃地 (ヨクチ) | fertile land | noun | formal | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2079, p. 311. On'yomi ヨク. |
| 妖女 (ヨウジョ) | fairy; enchantress | noun | literary | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2078, p. 311. On'yomi ヨウ. |
| 妖しい (あやしい) | dubious; fishy; suspicious | adjective | colloquial | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2078, p. 311. Kun'yomi form, same frame as 妖女 — everyday colloquial register distinct from its literary on'yomi compound. |
| 濾過 (ロカ) | filtering | noun | technical | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2328, p. 311. On'yomi ロ. |
| 怯れる (おそれる) | to fear | verb | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2275, p. 311. On'yomi キョウ (kun'yomi form shown). |
| 劫火 (ゴウカ) | world-destroying fire | noun | literary | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2857, p. 311. On'yomi ゴウ. Buddhist-cosmology term (*kalpa*-fire). |
| 厨子 (ズシ) | miniature household shrine | noun | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2152, p. 311. Reading ズ・チュウ. |
| 厨房 (チュウボウ) | kitchen; galley | noun | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2152, p. 311. Same frame as 厨子, alternate on'yomi チュウ. |
| 赳 (たけ/たけし) | — (used in given names only) | proper-noun element | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2936, p. 311. On'yomi キュウ; both listed readings are name-only kun'yomi. |
| 榎 (えのき) | thackberry; lotus tree | noun | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2514, p. 349, "Kanji with Japanese Readings Only" ch. 12 — this chapter's kanji have no on'yomi at all, only kun'yomi. |
| 苅る (かる) | to mow (grass) | verb | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2387, p. 349. Kun'yomi only. |
| 鱈 (たら) | codfish | noun | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2819, p. 349. Kun'yomi only. |
| 鮪 (まぐろ) | tunny; tuna | noun | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2816, p. 349. Kun'yomi only. |
| 鮒 (ふな) | carp | noun | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2825, p. 349. Kun'yomi only. |
| 囁く (ささやく) | to whisper | verb | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2157, p. 349. Kun'yomi only. |
| 孕む (はらむ) | to conceive; to get pregnant | verb | colloquial | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2208, p. 349. Kun'yomi only. |
| 做す (なす) | to cause to happen | verb | literary | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2132, p. 349. Kun'yomi only. |
| 苺 (いちご) | strawberry | noun | core | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2350, p. 349. Kun'yomi only. |
| 埜心 (ヤシン) | wild; undomesticated | adjectival noun | literary | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2979, p. 358, "Readings of Old & Alternate Forms" ch. 13. On'yomi ヤ; 埜 is an old/alternate form. |
| 埜 (の) | field | noun | archaic | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2979, p. 358. Kun'yomi form, same frame as 埜心; old/alternate form of 野. |
| 亙り (わたり) | crossing | noun | archaic | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2985, p. 358. On'yomi コウ; 亙 is the old/alternate form cross-referenced from the 瓦 "span [old form]" entry above (frame 2985, same frame number, p. 170). |
| 亙る (わたる) | to cross over | verb | archaic | — | contemporary (source dated 2001–2002) | — | — | grammar_reference | n/a | verified | Frame 2985, p. 358. Kun'yomi form, same frame as 亙り. |

---

## Grammar points

### Primitive-composition mnemonic method (Part One, chs. 1–6)

Heisig's method (continued identically from Volumes 1–2) never teaches a kanji as an unanalyzed
pictograph. Every character is instead decomposed into a small set of recurring "primitive"
elements — some of which are kanji in their own right, some of which are Heisig-invented shape-
chunks with no independent existence (e.g. the unnumbered "I Ching" and "stitching" primitives
introduced on p. 20 purely to help decompose 犀/皐/畷 and similar characters) — and the student
builds an imaginative "story" linking the primitives to the assigned English keyword. The book's own
running gloss for each frame (e.g. "pack of wild dogs … skeleton" for 2335 "sly") *is* the primitive
breakdown, not a definition in the usual dictionary sense; multiple keywords can share nearly
identical glosses (e.g. frames 2360/2361/2362 for 蓮/芙/蓉, all "flowers … X," are explicitly noted
by the book as nearly synonymous, with the author flagging 蓮 as simply the most common of the
three).

### Old/alternate-form correspondence (chs. 6, 13)

Pre-reform or variant kanji forms are taught as a labeled category distinct from their standard
modern equivalents, e.g. 瓦 "span [old]" vs. standard 亙 (I.32); 躯 "body [old]" vs. standard 身
(I.1248); 嶽 "Point [old]" vs. the abbreviated modern 岳 (I.1330), which the book flags as unusual
because the "mountain" element moves from top to bottom in the simplification. Chapter 13 supplies
the reading side of this same old/alternate-form set (e.g. 亙 reappearing with its real readings
亙り/亙る), demonstrating that "old form" status is about the *character shape*, not about the
word/reading being obsolete — 亙る "to cross over" is a live, usable verb written with a
pre-reform character shape.

### Reading groups: pure, semi-pure, and mixed (chs. 7–10)

Part Two organizes previously-learned kanji by shared **on'yomi reading**, graded by reliability:
- **Pure groups** (chs. 7–8): every kanji sharing a given phonetic/primitive shape takes the *same*
  on'yomi with no exceptions (e.g. 幾/機/磯/畿 all read キ; 丈/杖 both read ジョウ).
- **Semi-pure groups** (ch. 9): the shared reading holds for most but not all members, or the shared
  element covers kanji with a documented sound-shift (e.g. 后/垢 sharing コウ but with 垢 also taking
  an alternate ク reading).
- **Mixed groups** (ch. 10): kanji that look related by shape nonetheless diverge into genuinely
  different on'yomi within the same "group" (e.g. 醇/惇 sharing ジュン, but 惇/敦 sharing a second,
  different reading トン) — the book's own "Groups A & B" framing exists specifically to flag this
  reduced reliability.
- **Kanji with Japanese readings only** (ch. 12) is the opposite extreme: a dedicated chapter for
  kanji that were never assigned a Sino-Japanese on'yomi at all and are only ever read with a native
  kun'yomi (e.g. 鮪 まぐろ "tuna," 苺 いちご "strawberry") — mostly nature/foodstuff vocabulary.

### Phono-semantic coinage for foreign loanwords (chs. 4–5)

Chapters 4–5 document a distinct kanji-formation device: adding a semantically "empty" marker
element (typically 口 "mouth," sometimes 氵 "water") to a phonetic component purely to signal "this
character's reading represents a foreign sound, not its native Chinese/Japanese meaning" — e.g. 哩
"mile" (mouth + a phonetic element resembling 里 "ri," the native distance unit) and 噸 "ton" (mouth
+ a phonetic element read like English "ton"). The same device, with different donor radicals,
produced ateji for Buddhist Sanskrit transliteration (菩 "bo[dhi]," 迦 "Sanskrit ka") and even a
two-character Chinese phonetic transliteration of the English word "coffee" (noted but not directly
sampled here, immediately following frame 2961 on p. 163).

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`.
