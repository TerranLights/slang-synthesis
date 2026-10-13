# Japanese — *Read Japanese Today* (Len Walsh, Charles E. Tuttle Co., 1969; 39th printing 1989)

Source: `source_reference/languages/Japanese/02.Japanese Writing System/Read Japanese Today.pdf`
(156 PDF pages). Covers: Section One (introductory essay on the history/principles of Japanese
writing, pp. 9–24), Section Two (300 kanji presented with pictographic origin story, modern
meaning, readings, and example compounds, pp. 27–152), Appendix I (a short list of simplified
vs. traditional character forms, p. 153), Appendix II (the kana syllabary, pp. 155–159).

This file covers the first half of Section Two's character sequence (nature, body-part, hand,
and foot/leg/correctness pictograph groups, roughly pp. 27–68 of the book). The second half
(vehicles, money, gates/doors, animals, weapons, buildings, weather, and color/miscellaneous
groups) is in `019b_read_japanese_today.md`.

## Coverage note / extraction method — IMPORTANT

**This PDF has a genuine text layer for its English prose, but the 300 target-language kanji
themselves are embedded page-scan images, not text** — a clean instance of the "metalanguage
prose is real text, target-language content is raster images" gotcha already documented in
`00_Reference_Extraction_Spec.md`. Confirmed via `pdftotext`: every English sentence extracts
perfectly (including the romaji pronunciation guides, e.g. "pronounced HI... NICHI"), but every
kanji glyph in the running text comes back as blank/whitespace.

Because of this, the kanji glyph in the **Term** column below was supplied by cross-referencing
the book's own romaji reading(s) + English gloss + stroke/compound description against standard
joyo-kanji knowledge — this combination is unambiguous for nearly every entry in this book (e.g.
"pronounced HI alone / NICHI in compounds, means sun/day" has exactly one possible kanji: 日).
This was **spot-verified against the actual page-scan images** (via `pdftoppm` render + direct
visual inspection) at three widely-separated points in the book — p. 27 (日, 木 — confirmed exact
match), p. 47 (山, 谷, 石, 田, 川, 水, 油 — all confirmed exact match), and p. 152 (銀, 座 —
confirmed exact match, plus the closing "終" flourish). All three spot-checks matched the
identification method exactly with no discrepancies, which is why the method is used across the
rest of the book rather than vision-reading all ~130 pages individually. Rows carrying a directly
vision-confirmed kanji are marked `verified` below; all other rows are marked
`plausible_unverified` (high-confidence identification, not individually pixel-verified) per the
spec's three-tier scale. No row is marked `low_confidence` — none of the identifications in this
chunk carried genuine doubt.

A handful of entries in the source text itself have a dropped/blank romaji reading (the PDF's OCR
layer skipped a short reading embedded close to a kanji image) — these are flagged individually in
the Notes column rather than silently filled in.

**Coverage approach:** per the spec's "extract in full or representatively sample" guidance for a
bounded pictographic-origin reference — this book's 300 characters are *not* a flat dictionary
list; each has unique narrative (the mnemonic pictographic-origin story) that is real, non-
redundant content. This file + 019b together extract essentially every character the book treats
as an independent lexical item with its own pronunciation. A small number of **non-standalone
radical/pictograph components** that the book introduces only to explain how they combine into a
later character (e.g. the "advance" 辶-type pictograph said explicitly to "never stand alone") are
*not* given their own vocabulary row, since the book itself does not assign them an independent
pronunciation — inventing one would be fabrication. Per copyright discipline, the pictographic
origin story for each character is paraphrased/summarized, not quoted at length.

**Appendix I** (simplified vs. traditional forms) is not given separate rows — it only lists
orthographic variants of characters already captured below (母/毎/海/毒/区/争/学/急/売/焼/悪/社/神/気);
each affected row's Notes column flags that a simplified post-war form also exists.

**Appendix II** (the kana syllabary chart) is skipped as redundant — it is pure chart/table content
(no prose to extract) and this project's Japanese corpus already has a dedicated, far more
thorough hiragana/katakana treatment in `001_guide_to_hiragana_katakana.md` and its siblings.

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 日 (HI alone / NICHI in compounds) | sun; day | noun | core | — | contemporary (source published 1969) | — | — | dictionary | n/a | verified | p.27. Pictograph: a circle with rays, simplified to a dot in a square, then squared to the final form. 日本 NIHON/NIPPON "origin-of-the-sun" = Japan. |
| 木 (KI alone / MOKU in compounds) | tree; wood | noun | core | — | contemporary (1969) | — | — | dictionary | verified | p.27. Pictograph of a tree: horizontal line = branches, vertical = trunk, diagonals = roots. |
| 本 (HON alone or in compounds / also MOTO) | root; origin; book | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.27. Extra roots drawn at the base of 木. Extended to "origin/source" then to "book" (the root/source of knowledge). |
| 東 (HIGASHI alone / TŌ in compounds) | east | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.27–28. Sun 日 rising behind a tree 木. Compounds e.g. 東京 TŌKYŌ, "Eastern Capital." |
| 京 (reading given only as "...or KEI"; first reading dropped by a PDF extraction gap — standard reading is KYŌ) | capital | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.28. From a pictograph of a stone lantern placed at the gates of the Chinese Emperor's residence. Source text itself has a dropped reading here — flagged, not invented. |
| 羽 (HANE) | wing | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.28–29. Pictograph of bird's wings. First character in 羽田 HANEDA, Tokyo's airport, "winged field." |
| 田 (TA, sometimes DA) | rice paddy; field | noun | core | — | contemporary (1969) | — | — | dictionary | verified | p.29. Pictograph of a paddy with internal divisions. Seen in 本田 HONDA, "original paddy." |
| 力 (CHIKARA alone / RYOKU or RIKI in compounds) | strength; power | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.29. A strong hand/arm bearing down, abstracted from a full hand-and-fingers drawing. |
| 男 (OTOKO alone / DAN in compounds) | man (male) | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.29. Power 力 added to rice paddy 田 — the one who works the field. Distinguished from 人 (person, the species). |
| 女 (ONNA alone / JO in compounds) | woman | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.30. Pictograph of a seated figure with arms outstretched. |
| 母 (OKĀSAN in the polite/respectful form alone / BO in compounds) | mother | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.30. Woman 女 with breasts added, then a stabilizing "hat" stroke. Has a post-war simplified form (Appendix I). |
| 人 (HITO alone / NIN or JIN in compounds) | person (species-general, not gendered) | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.30–31. General human-form pictograph. 日本人 NIHONJIN = Japanese (person). |
| 毎 (MAI) | every | adjective/prefix | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.31. Man 人 (reshaped) + mother 母 combined. 毎日 MAINICHI, "every day," also a major newspaper's name. Has a simplified form (Appendix I). |
| 子 (KO) | child | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.31–32. Pictograph of a swaddled baby. Common suffix in girls' names ("sweet little..."). |
| 好 (SUKU/SUKI as verb "to like" / Ī as adjective "good, nice") | love; good; to like | verb/adjective | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.32–33. Woman 女 + child 子 = love/goodness. |
| 大 (ŌKII alone / DAI, TAI in compounds) | big | adjective | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.33. Man with arms stretched as wide as possible. 大田 ŌTA, "big-paddy," a Tokyo ward; 大日本 DAI-NIHON, "Greater Japan." |
| 小 (CHIISAI alone / KO, Ō in compounds/names) | small | adjective | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.33. Same man-pictograph with arms pulled in. |
| 立 (TATSU alone / RITSU, sometimes TACHI, in compounds) | to stand; to rise | verb | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.33–34. Man standing on the ground. 日立 HITACHI, "sun-rise," the electronics maker. |
| 一 (ICHI) | one | numeral | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.34. One horizontal stroke. |
| 二 (NI) | two | numeral | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.34. Two horizontal strokes. |
| 三 (SAN) | three | numeral | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.34. Three horizontal strokes. |
| 五 (GO) | five | numeral | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.34. Five horizontal lines compressed into two verticals plus an open corner for balance. |
| 十 (JŪ) | ten | numeral | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.34. From ten fingers of two crossed hands. |
| 協 (KYŌ) | unite; cooperate | noun/verb-stem | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.34–35. Power 力 tripled, multiplied by ten 十 — "many strengths joined." 協力 KYŌRYOKU = cooperation. |
| 川 (KAWA, sometimes GAWA) | river | noun | core | — | contemporary (1969) | — | — | dictionary | verified | p.35. Pictograph of a flowing river, straightened to three vertical strokes. |
| 水 (MIZU alone / SUI in compounds) | water | noun | core | — | contemporary (1969) | — | — | dictionary | verified | p.35–36. "Squeeze a river and you get water" — a compressed river pictograph. |
| 入 (IRERU transitive / HAIRU intransitive, alone; compounds unclear in source) | to enter; to contain | verb | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.36. A smaller river flowing into a larger one, abstracted to two converging lines. Appears above entrances. |
| 口 (KUCHI alone, sometimes GUCHI for euphony / compound reading given as blank in source) | mouth; opening | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.36. Simple open-mouth pictograph. 入口 IRIGUCHI = entrance; 東口 HIGASHI-GUCHI = east exit/entrance (station signage). |
| 中 (NAKA or compound reading given as blank, standard CHŪ) | middle; inside | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.36–37. Mouth/opening 口 with a line through the middle. Common in family names (中田 NAKADA, etc.). |
| 央 (reading given as blank, standard Ō) | center (the exact middle, distinct from 中's "inside") | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.38. A circle drawn around the center of an outstretched-arms man-figure, later squared and the bottom half dropped. Rarely standalone; 中央 CHŪŌ = "middle-middle," central. |
| 映 (UTSUSU transitive / UTSURU intransitive, alone; EI in compounds) | to reflect; to project (an image) | verb | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.38–39. Sun 日 + center 央. 映画 EIGA = movie (combined with the next entry). |
| 画 (reading given as blank; appears in EIGA) | picture; boundary | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.39. Originally a rice-paddy with a boundary line drawn around it; extended from "draw a boundary around" to "picture." |
| 古 (FURUI alone / KO in compounds) | old | adjective | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.39. Mouth/person-radical 口 topped by ten 十, read as "ten generations" → old. |
| 品 (SHINA alone / HIN in compounds) | goods; things | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.39–40. Three mouths/openings (boxes) stacked, "many boxes" → goods. 品川 SHINAGAWA, a Tokyo ward. |
| 区 (KU) | ward; district | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.40. Three mouths inside a boundary. Has a simplified form (Appendix I). |
| 町 (MACHI, also read as a blank-flagged second reading, standard CHŌ) | town; section of a ward | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.40. Rice paddy 田 + a "sign" marker giving it a name. |
| 丁 (reading given as blank, standard CHŌ) | unit of measure; city block | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.40–41. The "sign" component of 町 used as its own character; numbered city-block subdivisions (一丁目, 二丁目...). |
| 言 (IU alone; compound reading not captured in this chunk — standard GEN) | to say | verb | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.41. Mouth 口 with lines indicating speech issuing from it. |
| 信 (SHIN) | trust | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.41–42. Man 人 (reshaped) + "sayings" 言 — a man standing behind his word. Common in bank/trust-company names. |
| 計 (HAKARU alone / KEI in compounds) | to measure; to count | verb | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.42. "Saying" 言 + ten 十 — counting aloud. Appears over cashier counters and on measuring instruments as "-meter." |
| 舌 (SHITA) | tongue | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.42. Mouth 口 with a forked tongue sticking out. |
| 話 (HANASU alone / WA in compounds) | to talk | verb | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.42–43. Tongue 舌 added to say 言 — "glibness" beyond simply saying. |
| 活 (KATSU) | life; energy; vitality | noun/adjective-stem | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.43. Water 水 (abbreviated) + tongue 舌 — "a moist tongue is a sign of life." 日活 NIKKATSU, a film studio, "sun-life." |
| 語 (GO) | word; language | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.43. Five 五 (→ "many") + mouths 口, i.e. something said by many mouths. 日本語 NIHONGO = Japanese language. |
| 上 (UE alone / JŌ in compounds; AGARU/AGERU as verb) | up; above; on top of | noun/verb | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.43–44. A dot above a centerline, expanded to a vertical stroke with a handle. |
| 下 (SHITA alone / GE in compounds; SAGARU/SAGERU/KUDARU/KUDASU as verb) | down; below | noun/verb | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.44. Mirror construction of 上, dot below the centerline. Source of KUDASAI, "please give me...". |
| 山 (YAMA alone / SAN in compounds) | mountain | noun | core | — | contemporary (1969) | — | — | dictionary | verified | p.45–46. Three-peaked mountain range pictograph, simplified to three vertical strokes. 富士山 FUJISAN = Mt. Fuji; favored in Sumo wrestlers' ring names. |
| 谷 (TANI alone, sometimes YA in proper names) | valley | noun | core | — | contemporary (1969) | — | — | dictionary | verified | p.47. An "opening" in a mountain range. 大谷 (Ōtani) Hotel, "big valley." |
| 石 (ISHI alone / SEKI in compounds) | stone | noun | core | — | contemporary (1969) | — | — | dictionary | verified | p.47. A cliffside with a stone below it. Common in family names (石田 ISHIDA, 石川 ISHIKAWA). |
| 油 (ABURA alone / YU in compounds) | oil | noun | core | — | contemporary (1969) | — | — | dictionary | verified | p.47–48. Field-with-derrick 田-like pictograph + water (abbreviated) radical. 石油 SEKIYU = petroleum, lit. "rock-oil." |
| 月 (TSUKI alone / GETSU or GATSU in compounds) | moon; month | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.48. Quarter-moon pictograph. Months 1–12 are numeral + 月 (GATSU). |
| 夕 (reading given as blank, standard YŪ or SEKI) | evening | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.48–49. Full moon rising behind a mountain in early evening, abstracted from 月. |
| 外 (SOTO or HOKA alone / GAI in compounds) | outside | noun/adjective | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.49. Evening 夕 + a divining rod (diviners were "night people," working outdoors). 外人 GAIJIN = foreigner (abbreviation of 外国人). |
| 名 (NA alone / MEI in compounds) | name | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.49. Evening 夕 + mouth 口 — calling out a name to night sentries before being allowed to pass. |
| 多 (reading given as blank, standard ŌI alone / TA in compounds) | many | adjective | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.49–50. Two "moon rising behind mountain" pictographs stacked — originally "many moons" (cf. counting in moons), narrowed to "many." |
| 明 (AKARUI alone / MEI in compounds) | bright | adjective | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.50. Moon 月 + sun 日. |
| 光 (HIKARU/HIKARI alone / compound reading given as blank, standard KŌ) | light; rays; to shine | noun/verb | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.50–51. Rays pulled together from the original sun-pictograph. 日光 Nikkō, "sun-shine," a resort town. |
| 早 (HAYAI) | early; fast | adjective | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.51–52. Sun at dawn rising over a field of flowers (one flower). Root of OHAYŌ, "good morning," lit. "it is early." |
| 朝 (ASA) | morning | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.52. A second "flower" added above the sun (to distinguish from 早) plus moon 月 — dawn beside the all-night moon. 朝日 ASAHI, "morning sun," a common company name. |
| 土 (TSUCHI alone / TO or DO in compounds) | earth; ground | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.52. A flower sprouting from the earth, simplified. 土木 DOBOKU (pronounced with euphonic shift) = civil engineering, "earth-and-wood." |
| 出 (DERU alone / DE or SHUTSU in compounds) | to come out; to exit | verb | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.52–53. The "earth" flower-pictograph shown in full bloom — emphasis shifts from ground to "coming out." Opposite of 入. 出口 DEGUCHI = exit. |
| 生 (UMU "give birth" / UMARERU "to be born" / NAMA "raw" / SEI "life", ~22 readings per the source) | to give birth; to be born; raw; life | verb/adjective/noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.53. Flower pictured at peak bloom, "ready to give birth to another cycle of life." Source notes ~22 distinct readings, meaning shifting with pronunciation — an unusually heavy reading-load character flagged explicitly by the book itself. |
| 米 (KOME alone / BEI in compounds) | (husked, uncooked) rice; also used to write "America" | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.53–54. Harvested rice-stalks bundled and stacked. BEI reading is also the character the Japanese use for "America" (米国 BEIKOKU). |
| 白 (SHIROI alone / HAKU in compounds) | white | adjective | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.54. A single grain of rice, symbolizing the color white. |
| 林 (HAYASHI) | woods; grove | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.54–55. Two trees 木木 side by side. Common family name. |
| 森 (MORI) | forest | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.54–55. Three trees 木木木. Common family name. |
| 果 (KA) | fruit; result | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.55. A tree bearing fruit. Extended by the book to mean "fruit of your effort, result." |
| 菓 (KA) | confectionery | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.55–56. Plants/bushes radical + fruit 果. 菓子 KASHI = "little confection," sweets/pastries generically. |
| 休 (YASUMU alone; compound reading given as blank, standard KYŪ) | to rest | verb | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.56. Man 人 resting beside a tree 木. Posted on shop doors to mean "closed." |
| 体 (KARADA alone / TAI in compounds) | body | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.56. Man 人 + root 本 — "root of man." By extension, a group/delegation of men. |
| 手 (TE) | hand | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.56–57. Direct hand pictograph. |
| 友 (TOMO, sometimes the compound reading dropped as blank, standard YŪ) | friend | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.57. Two hands reaching to clasp each other. Root of TOMODACHI, "friend." |
| 左 (HIDARI alone / SA in compounds) | left | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.57. A (left) hand holding a carpenter's ruler. |
| 工 (KU, also a reading given as blank) | to build; builder; construction | noun/verb-stem | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.57. The carpenter's-ruler pictograph used as its own character. 大工 DAIKU = carpenter. |
| 右 (MIGI alone / U in compounds) | right (direction only, not "rights") | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.57–58. Hand 手 + mouth 口 — "the hand you eat with." |
| 有 (ARU alone; compound reading given as blank, standard YŪ) | to have; to exist | verb | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.58. Hand holding what looks like the moon but is actually a piece of meat (abbreviated form coincides with 月's shape). 有名 (YŪMEI) "have-name" = famous. |
| 寸 (SUN) | a measure (≈1.13 in. as distance; also "law/justice" as a building-block sense) | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.58. Hand with a dot measuring the pulse-point distance from the wrist. |
| 村 (MURA alone / SON in compounds) | village | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.58–59. "Law" 寸 (justice sense) + tree 木 (symbolizing jungle) — the social organization that brings law out of the jungle. Common in place/family names (中村 NAKAMURA). |
| 守 (MAMORU alone / SHU in compounds) | to guard | verb | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.59. Roof 宀 + law/justice 寸. Seen on guardhouses and sentry posts. Has a simplified-adjacent reading note in the source (not itself in Appendix I). |
| 寺 (TERA alone / JI in compounds) | (Buddhist) temple | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.59. Law/justice 寸 + earth/place 土 — "a place where laws are made." Temple names typically end in this character (東大寺 — the Great Eastern Temple in Nara). |
| 詩 (SHI) | poetry; poem | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.59–60. Temple 寺 + say 言 — "temple-speaking." |
| 時 (TOKI alone / JI in compounds) | time; hour | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.60. Temple 寺 + sun 日 — temples once tracked the sun's travel to keep the calendar. 時計 TOKEI (with a special TO reading for 時 here) = clock. |
| 持 (MOTSU alone / JI in compounds) | to have; to hold; to own | verb | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.60–61. Temple 寺 + hand 手 (reshaped) — only temples could own property in early times. |
| 付 (TSUKU/TSUKERU) | to attach; to hold up against | verb | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.61. Hand (reshaped) held against a man 人. Verb-stem TSUKI appears on menus meaning "with..." (e.g. "with rice"). |
| 受 (UKERU alone / JU in compounds) | to receive | verb | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.61–62. A hand receiving a baton from another hand. 受付 UKETSUKE = reception/receptionist. |
| 争 (SŌ, implied; not explicitly given in this chunk) | to struggle; to dispute | verb | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.62. Same two hands and baton, this time tugging in opposition. Has a simplified form (Appendix I). |
| 共 (KYŌ, implied) | together | adjective/prefix | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.62. Two hands jointly holding up a ball. 共立 (with 立) = cooperative, joint, common. |
| 学 (MANABU alone / GAKU in compounds) | to learn; study | verb | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.62–63. Two hands pouring knowledge (two X's) into a child seated in a building. 学生 GAKUSEI = student; 大学 DAIGAKU = university. Has a simplified form (Appendix I). |
| 支 (SHI) | branch (of an organization); to support | noun/verb-stem | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.63. Hand holding up a branch. 支持 SHIJI = to support. |
| 枝 (EDA) | branch (of a tree) | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.63. Tree 木 added to branch/support 支. |
| 書 (KAKU alone / SHO in compounds) | to write; writing(s) | verb/noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.63. A hand holding a brush, writing on paper. Appears in bookshop names. |
| 事 (KOTO alone / JI in compounds) | thing; affair; happening | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.63–64. Same brush, pointed upward and poised to record events. 人事 JINJI = personnel/human-affairs; 時事 JIJI = current events. |
| 反 (HAN) | oppose; anti- | prefix | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.64–65. Hand + hill — a hand-made barrier-hill piled against an enemy's advance. Seen on protest placards. |
| 坂 (SAKA) | hill; slope | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.65. Earth 土 added to the man-made hill of 反, indicating an actual (natural) hill. |
| 止 (TOMARU/TOMERU alone / SHI in compounds) | to stop | verb | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.66. A foot pictograph, squared off. Appears on traffic stop signs; 中止 CHŪSHI = suspended/cancelled. |
| 足 (ASHI) | leg; foot (the book notes Japanese does not distinguish the two) | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.66–67. Leg pictograph with kneecap resting on a foot. 足立 ADACHI (lit. ASHI-DACHI, contracted), a Tokyo ward name. |
| 正 (TADASHII alone / SEI or a second compound reading given as blank) | correct; righteous; upright | adjective | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.67–68. A foot with a straight line over it — "keep your foot on the straight and narrow." Favored in personal names (正子 MASAKO, etc.). |
| 心 (KOKORO alone / SHIN in compounds) | heart; mind; spirit | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.68–69. Direct heart pictograph. 小心 SHŌSHIN = faint-heartedness. |
| 音 (OTO alone / ON or IN in compounds) | sound | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.69. Sun 日 (rising) + a "life" element — the world's sounds beginning at dawn. 母音 BOIN = vowel, "mother-sound"; 子音 SHIIN = consonant, "child-sound." |
| 急 (ISOGU alone; compound reading given as blank, standard KYŪ) | urgent; sudden; in a hurry | verb/adjective | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.69–70. Two hands held over the heart, tempering excitement. Has a simplified form (Appendix I). |
| 意 (I) | mind; intention; feeling | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.70. Sound 音 over heart 心. |
| 目 (ME) | eye | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.70–71. An eye pictograph stood on end and squared off. |
| 帽 (reading given as blank, standard BŌ) | hat | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.71. Cloth-measuring man shielding his eyes 目 from the sun. 学生帽 = student's cap. |
| 巾 (building-block only in this chunk; standard reading KIN) | cloth | noun (radical) | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.71. The "man measuring cloth" component of 帽, rarely used alone per the source. |
| 見 (MIRU) | to see | verb | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.71. Eye 目 set atop a (reshaped) man 人. 見本 MIHON = sample, "seeing-the-original." |
| 耳 (MIMI) | ear | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.72. Direct ear-with-lobe pictograph. |
| 取 (TORU) | to take | verb | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.72. Hand 手 + ear 耳 — "ripping off an ear," per the book's (grim) mnemonic for ancient trophy-taking. |
| 歯 (HA) | teeth | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.72. Direct teeth pictograph, with a noted modern abbreviated variant. |
| 毛 (KE alone / MO in compounds) | hair; fur | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.72–73. From a pictograph of a wispy beard. |
| 鼻 (HANA) | nose | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.73. Front-view nose pictograph. |
| 自 (JI) | self | noun/prefix | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.73. Nose 鼻 with the nostrils removed — the Chinese pointed to the nose (not the chest) to indicate "myself." |
| 習 (NARAU alone; compound reading given as blank, standard SHŪ) | to learn | verb | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.73–74. Self 自 + wings 羽 — "fly on your own wings." 見習い MINARAI = apprentice/trainee. |
| 公 (KŌ) | public | adjective/noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.74. The "private" nose-side-view radical (ム, not independently listed here since the book gives it no standalone pronunciation) + a "divide/split" pictograph, combined as "private, divided" = not-private = public. |
| 松 (MATSU) | pine (tree) | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.74. Public 公 + tree 木 — "the tree that's everywhere." Common in place/family names (松下 MATSUSHITA). |
| 私 (WATAKUSHI/WATASHI alone / SHI in compounds) | I; me; private | pronoun/adjective | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.75. Nose-as-self/private radical + a rice-stalk pictograph ("my private rice"). 私立 SHIRITSU = privately operated (school, etc.). |
| 和 (WA) | harmony; peace; harmonious | noun/adjective | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.75. Rice stalk (禾, the 私-radical reused) + mouth 口 — "fat and happy." Also an old name/reading for Japan itself (大和 YAMATO). |
| 兄 (reading given only as the honorific O-NĪSAN; no compound reading captured in this chunk, standard KEI) | big brother | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.75–76. Rice stalk being inspected by the tax collector ("big brother with horns"), per the book's mnemonic. |
| 税 (ZEI) | tax | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.76. Rice stalk 禾 + big brother 兄 — the tax collector. |
| 説 (SETSU) | theory; opinion; story; explanation | noun | core | — | contemporary (1969) | — | — | dictionary | plausible_unverified | p.76. Sayings 言 + big-brother-with-horns 兄. 小説 SHŌSETSU = novel; 説明 SETSUMEI = explanation. |

## Grammar points

Section One of this book (pp. 9–24) is not a grammar chapter in the usual sense — it is an essay
on the *history and structural principles* of Japanese writing, aimed at a general reader. Its real
content, paraphrased:

1. **Pictograph → ideograph → character, in three stages** (pp. 10–15). Simple objects (sun, tree,
   mountain) were drawn as direct pictographs; words too abstract for a single picture (power,
   pleasure) were represented by a symbolic scene (a hand holding a stick for "power/authority"; a
   drum for "pleasure"); over roughly 2000 years the Chinese standardized/squared these into the
   modern character forms. The book contrasts this with the Western alphabet's path: Egyptian
   pictographs (e.g. a cow for the sound "A") were stripped of meaning and kept only for sound,
   eventually becoming the Latin alphabet — while Chinese/Japanese characters never made that
   leap and still carry pictorial meaning.
2. **Why Japanese needs kana alongside characters** (pp. 16–18). Classical Chinese had no
   grammatical inflection, so borrowed Chinese characters could write Japanese word-roots but not
   Japanese's own grammatical endings (verb conjugation, case-marking particles, etc.) — Japanese
   morphology required a phonetic system of its own, which is what became kana. The book's analogy:
   a character is like the English root "beaut," and kana supply "-y," "-iful," "-ify" depending on
   part of speech.
3. **On-yomi/kun-yomi alternation, informally** (p. 19 and throughout Section Two). Every character
   in this book is given (at minimum) one reading "by itself" and a separate reading "in
   compounds" — the book does not use the terms kun'yomi/on'yomi, but this is exactly that
   distinction, taught inductively through hundreds of worked examples rather than named as
   grammar.
4. **Characters vs. kana are visually distinguishable** (p. 18): kana are drawn with at most ~4
   strokes (usually 2–3); characters have a minimum of 2 strokes (the character for "one," 一, being
   the sole 1-stroke exception) and typically many more.
5. **Pronunciation basics** (pp. 22–23): five vowels pronounced roughly as in Italian (A as in
   "car," E as in "bed," I as in "medium," O as in "go," U as in "luke"); long vowels are
   phonemically distinct from short ones and change word meaning (the book's own minimal-pair
   examples: obāsan "grandmother" vs. obasan "aunt"; ojisan "uncle" vs. ojiisan "grandfather" —
   given only as romaji pairs, not kanji, in the source); doubled consonants (e.g. KK, PP) mark a
   dropped syllable and are held slightly longer; Japanese stresses syllables roughly evenly, unlike
   English's syllable-stress pattern — illustrated with YOKOHAMA (even stress) vs. the American
   mispronunciation that gave rise to "MERIKEN" as a loanword-origin folk-etymology for both
   "American" and the flour brand name.

No further formal "grammar points" are introduced in Section Two — it is entirely character-by-
character vocabulary/etymology content, captured in the table above.
