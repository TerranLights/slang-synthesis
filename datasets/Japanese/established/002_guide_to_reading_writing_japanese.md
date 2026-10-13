# Japanese — Established Vocabulary/Grammar: A Guide to Reading and Writing Japanese (Writing System Foundation, Part A)

**Source:** Florence Sakade (comp., 1st ed. 1959); Kenneth Henshall, Christopher Seeley & Henk de
Groot (rev.), *A Guide to Reading and Writing Japanese* (Third Edition, 2003), Tuttle Publishing /
Periplus Editions. Covers: front-matter Introduction (pp. v–xi, PDF pp. 6–12) and Section One,
"The 1,006 Essential Characters," Grade One only (kanji #1–80, pp. 1–17, PDF pp. 14–30).

**Source format note:** this DJVU has no text layer at all — every page in this file was vision-read
from page images rendered via `ddjvu -format=ppm` (converted to PNG with Pillow, since this build of
`ddjvu` does not support `-format=png` directly). No handwritten marginalia was found on any page
read so far; all content is clean, consistently-typeset print matching the surrounding page, so no
exclusions were needed on this pass.

**Coverage note:** this is a kanji dictionary (1,006 "Essential Characters" taught in Japanese
elementary school + 1,945 total "General Use"/Jōyō characters), not a lesson-based grammar textbook
— its "vocabulary" is, by design, exhaustive and extremely dense (ultimately ~3,000 character entries
plus ~3,000 illustrative compounds across 335 pages). Per the extraction spec's "comprehensive but
not exhaustive" coverage rule and the project's own precedent of sampling oversized dictionaries
rather than fully exhausting them in one pass, this dispatch extracts the front matter in full (it is
finite and uniquely valuable — explains the whole writing-system mechanics this project's typological
profile needs) plus **the complete, unabridged first bound chunk of the character dictionary itself:
all 80 "Grade One" kanji** (the Education Ministry's own first-year teaching set), each with its full
reading/meaning data and all three illustrative compounds the source provides. This is a genuinely
complete, bounded unit (grade boundaries are given explicitly by the source itself, see the Layout
Details grammar point below) rather than an arbitrary stopping point. See the continuation note at
the end of this file for exactly where the next dispatch should resume (Grade Two, kanji #81, PDF
page 31).

Stroke-order diagrams themselves (the cell-by-cell stroke progression shown for each kanji) are
described in prose rather than reproduced, per copyright discipline — only the general *rules*
governing stroke order are paraphrased as grammar points below.

---

## Vocabulary

Each kanji character is one row (`Part of Speech` = `character (kanji)`); each of the source's own
illustrative compound words is a further row directly beneath it. On/kun readings for the character
row are given in `Notes` in the source's own notation (CAPS = on-yomi, italics-equivalent lowercase =
kun-yomi, parenthesized tail = okurigana).

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 一 (ichi) | one | character (kanji) | core | — | contemporary (source published 2003, orig. 1959) | — | — | dictionary | n/a | verified | Kanji #1, Grade 1, 1 stroke. Readings: ICHI, ITSU; *hito-*, *hito(tsu)*. |
| 一月 (ichigatsu) | January | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #1 一. |
| 一番 (ichiban) | first, best | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #1 一. |
| 一冊 (issatsu) | one (book, magazine) | counter/noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #1 一; counter for bound volumes. |
| 二 (ni) | two | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #2, Grade 1, 2 strokes. Readings: NI; *futa(tsu)*. |
| 二月 (nigatsu) | February | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #2 二. |
| 二か月 (nikagetsu) | two months | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #2 二. |
| 二回 (nikai) | twice | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #2 二. |
| 三 (san) | three | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #3, Grade 1, 3 strokes. Readings: SAN; *mi-*, *mit(tsu)*. |
| 三月 (sangatsu) | March | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #3 三. |
| 三人 (sannin) | three people | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #3 三. |
| 三日 (mikka) | three days, the third day | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #3 三. |
| 四 (shi/yon) | four | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #4, Grade 1, 5 strokes. Readings: SHI, *yon*, *yo-*, *yot(tsu)*, *yo(tsu)*. |
| 四月 (shigatsu) | April | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #4 四. |
| 四日 (yokka) | four days, the fourth day | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #4 四. |
| 四十 (shijū / yonjū) | forty | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #4 四; two accepted on-based readings. |
| 五 (go) | five | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #5, Grade 1, 4 strokes. Readings: GO; *itsu(tsu)*. |
| 五月 (gogatsu) | May | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #5 五. |
| 五人 (gonin) | five people | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #5 五. |
| 五十 (gojū) | fifty | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #5 五. |
| 六 (roku) | six | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #6, Grade 1, 4 strokes. Readings: ROKU; *mut(tsu)*, *mu(tsu)*. |
| 六月 (rokugatsu) | June | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #6 六. |
| 六か月 (rokkagetsu) | six months | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #6 六. |
| 六十 (rokujū) | sixty | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #6 六. |
| 七 (shichi) | seven | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #7, Grade 1, 2 strokes. Readings: SHICHI; *nana(tsu)*, *nana*. |
| 七月 (shichigatsu) | July | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #7 七. |
| 七か月 (nanakagetsu) | seven months | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #7 七. |
| 七十 (shichijū / nanajū) | seventy | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #7 七; two accepted readings. |
| 八 (hachi) | eight | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #8, Grade 1, 2 strokes. Readings: HACHI; *yat(tsu)*, *ya(tsu)*. |
| 八月 (hachigatsu) | August | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #8 八. |
| 八か月 (hachikagetsu) | eight months | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #8 八. |
| 八十 (hachijū) | eighty | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #8 八. |
| 九 (kyū/ku) | nine | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #9, Grade 1, 2 strokes. Readings: KYŪ, KU; *kokono(tsu)*. |
| 九月 (kugatsu) | September | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #9 九. |
| 九十 (kujū / kyūjū) | ninety | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #9 九; two accepted readings. |
| 九時 (kuji) | nine o'clock | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #9 九. |
| 十 (jū) | ten | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #10, Grade 1, 2 strokes. Readings: JŪ; *tō*. |
| 十月 (jūgatsu) | October | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #10 十. |
| 十日 (tōka) | ten days, the tenth day | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #10 十. |
| 十回 (jikkai) | ten times | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #10 十. |
| 百 (hyaku) | hundred | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #11, Grade 1, 6 strokes. Reading: HYAKU (no kun reading). |
| 二百 (nihyaku) | two hundred | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #11 百. |
| 三百 (sanbyaku) | three hundred | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #11 百; voicing shift byaku. |
| 百貨店 (hyakkaten) | department store | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #11 百. |
| 千 (sen) | thousand | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #12, Grade 1, 3 strokes. Readings: SEN; *chi*. |
| 千円 (sen'en) | a thousand yen | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #12 千. |
| 三千 (sanzen) | three thousand | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #12 千; voicing shift zen. |
| 五千 (gosen) | five thousand | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #12 千. |
| 日 (nichi/hi) | day, sun | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #13, Grade 1, 4 strokes. Readings: NICHI, JITSU; *hi*; *-ka* (day-counting suffix). |
| 日曜日 (nichiyōbi) | Sunday | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #13 日. |
| 昨日 (sakujitsu) | yesterday | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #13 日. |
| 朝日 (asahi) | morning sun | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #13 日. |
| 月 (getsu/tsuki) | month, moon | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #14, Grade 1, 4 strokes. Readings: GETSU, GATSU; *tsuki*. |
| 月曜日 (getsuyōbi) | Monday | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #14 月. |
| 来月 (raigetsu) | next month | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #14 月. |
| 三日月 (mikazuki) | new moon, crescent moon | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #14 月; compound of 三日 "third day" + 月 "moon." |
| 火 (ka/hi) | fire | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #15, Grade 1, 4 strokes. Readings: KA; *hi*. |
| 火曜日 (kayōbi) | Tuesday | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #15 火. |
| 火ばち (hibachi) | charcoal brazier | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #15 火. |
| 火事 (kaji) | fire, conflagration | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #15 火. |
| 水 (sui/mizu) | water | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #16, Grade 1, 4 strokes. Readings: SUI; *mizu*. |
| 大水 (ō-mizu) | flood, inundation | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #16 水. |
| 水力 (suiryoku) | water power | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #16 水. |
| 水兵 (suihei) | sailor | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #16 水. |
| 木 (boku/moku/ki) | tree, wood | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #17, Grade 1, 4 strokes. Readings: BOKU, MOKU; *ki*. |
| 木曜日 (mokuyōbi) | Thursday | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #17 木. |
| 材木 (zaimoku) | lumber | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #17 木. |
| 木製 (mokusei) | made of wood | noun/adj | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #17 木. |
| 金 (kin/kane) | gold, money | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #18, Grade 1, 8 strokes. Readings: KIN (gold), KON (gold); *kane*. |
| 金曜日 (kin'yōbi) | Friday | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #18 金. |
| お金 (o-kane) | money | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #18 金; honorific o- prefix. |
| 金魚 (kingyo) | goldfish | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #18 金. |
| 土 (do/tsuchi) | earth, soil | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #19, Grade 1, 3 strokes. Readings: DO, TO; *tsuchi*. |
| 土曜日 (doyōbi) | Saturday | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #19 土. |
| 土地 (tochi) | ground, plot of land | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #19 土. |
| 土人 (dojin) | native | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #19 土; dated/sensitive term in modern usage, flagged as source-original. |
| 年 (nen/toshi) | year | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #20, Grade 1, 6 strokes. Readings: NEN; *toshi*. |
| 六年生 (rokunensei) | sixth-grade pupil | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #20 年. |
| 年寄り (toshiyori) | old person | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #20 年. |
| 青年 (seinen) | youth | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #20 年; also cross-referenced under #52 青. |
| 左 (sa/hidari) | left | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #21, Grade 1, 5 strokes. Readings: SA; *hidari*. |
| 左派 (saha) | leftist (political), left wing | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #21 左. |
| 左側 (sasoku / hidarigawa) | left side | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #21 左; two accepted readings (on-compound vs. kun-compound). |
| 左手 (hidarite) | left hand | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #21 左. |
| 右 (u/yū/migi) | right | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #22, Grade 1, 5 strokes. Readings: U, YŪ; *migi*. |
| 左右 (sayū) | left and right | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #22 右. |
| 右派 (uha) | right wing (political) | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #22 右. |
| 右側 (usoku / migigawa) | right side | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #22 右; two accepted readings, parallel to 左側. |
| 上 (jō/ue) | top, above, on | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #23, Grade 1, 3 strokes. Readings: JŌ; *ue* (top/above/on), *kami* (upper), *nobo(ru)* (go up/toward Tōkyō), *a(geru)* (raise), *a(garu)* (rise). |
| 上流 (jōryū) | upstream, upper class | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #23 上. |
| 海上 (kaijō) | on the sea, maritime | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #23 上. |
| 川上 (kawakami) | upstream | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #23 上; shares 川 with #59. |
| 下 (ka/ge/shita) | bottom, under, beneath | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #24, Grade 1, 3 strokes. Readings: KA, GE; *shita* (bottom/under), *moto* (base), *shimo* (lower), *kuda(ru)* (go down/away from Tōkyō), *sa(geru)* (hang v.t./lower), *sa(garu)* (hang down), *kuda(saru)* (bestow). Notably rich reading set for a single Grade-1 character. |
| 川下 (kawashimo) | downstream | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #24 下; antonym pair with 川上 above. |
| 下品 (gehin) | vulgar, coarse | noun/adj | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #24 下. |
| 地下鉄 (chikatetsu) | subway | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #24 下. |
| 大 (dai/tai/ōkii) | big, large, great | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #25, Grade 1, 3 strokes. Readings: DAI, TAI; *ō(kii)*. |
| 大学 (daigaku) | university, college | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #25 大. |
| 大変 (taihen) | tremendous, serious | noun/adj | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #25 大. |
| 大広間 (ō-hiroma) | grand hall | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #25 大. |
| 中 (chū/naka) | middle, within, inside | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #26, Grade 1, 4 strokes. Readings: CHŪ; *naka*. |
| 中学校 (chūgakkō) | middle school | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #26 中; shares 校 with #46. |
| 中心 (chūshin) | center, heart (of a city, etc.) | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #26 中. |
| 集中 (shūchū) | concentration | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #26 中. |
| 小 (shō/ko/chiisai) | small, minor | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #27, Grade 1, 3 strokes. Readings: SHŌ; *ko-*, *o-*, *chii(sai)*. |
| 小学校 (shōgakkō) | primary school | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #27 小. |
| 小屋 (koya) | hut | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #27 小. |
| 小説 (shōsetsu) | novel (fiction) | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #27 小. |
| 入 (nyū/iru) | entering | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #28, Grade 1, 2 strokes. Readings: NYŪ; *iri* (entering/attendance), *i(reru)* (put in), *hai(ru)* (enter). |
| 入学 (nyūgaku) | entering school | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #28 入; shares 学 with #45. |
| 輸入 (yunyū) | importation | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #28 入. |
| 入口 (iriguchi) | entrance | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #28 入; shares 口 with #34. |
| 出 (shutsu/deru) | to come out, go out | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #29, Grade 1, 5 strokes. Readings: SHUTSU, SUI; *de(ru)* (come/go out), *da(su)* (put out/take out/bring out/draw out). |
| 出発 (shuppatsu) | departure, starting | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #29 出. |
| 出版 (shuppan) | publishing | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #29 出. |
| 出口 (deguchi) | exit | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #29 出; antonym pair with 入口. |
| 目 (moku/boku/me) | eye | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #30, Grade 1, 5 strokes. Readings: MOKU, BOKU; *me*; also used as ordinal suffix. |
| 横目 (yokome) | side glance | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #30 目. |
| 目的 (mokuteki) | purpose | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #30 目. |
| 目標 (mokuhyō) | mark, target | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #30 目. |
| 見 (ken/miru) | to see, to look | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #31, Grade 1, 7 strokes. Readings: KEN; *mi(ru)* (see/look), *mi(eru)* (be visible/able to see), *mi(seru)* (show/display). |
| 見事 (migoto) | splendid | adj noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #31 見. |
| 見物 (kenbutsu) | sightseeing | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #31 見. |
| 見本 (mihon) | sample | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #31 見. |
| 耳 (ji/mimi) | ear | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #32, Grade 1, 6 strokes. Readings: JI; *mimi*. |
| 早耳 (hayamimi) | keen of hearing | noun/adj | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #32 耳; shares 早 with #56. |
| 耳鳴り (miminari) | ringing in the ears | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #32 耳. |
| 耳が遠い (mimi ga tōi) | deaf | phrase/adj | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #32 耳; idiomatic phrase, literally "ears are far." |
| 音 (on/in/ne/oto) | sound | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #33, Grade 1, 9 strokes. Readings: ON, IN; *ne*, *oto*. |
| 音楽 (ongaku) | music | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #33 音. |
| 発音 (hatsuon) | pronunciation | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #33 音. |
| 母音 (boin) | vowel | noun | core | technical.linguistics | — | contemporary | — | — | dictionary | n/a | verified | Compound of #33 音. |
| 口 (kō/ku/kuchi) | mouth | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #34, Grade 1, 3 strokes. Readings: KŌ, KU; *kuchi*. |
| 口ひげ (kuchihige) | mustache | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #34 口. |
| 入口 (iriguchi) | entrance | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #34 口; duplicate cross-reference, see #28 入. |
| 口論 (kōron) | dispute | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #34 口. |
| 手 (shu/te) | hand | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #35, Grade 1, 4 strokes. Readings: SHU; *te*. |
| 握手 (akushu) | handshake | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #35 手. |
| 手袋 (tebukuro) | gloves | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #35 手. |
| 手紙 (tegami) | letter | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #35 手. |
| 足 (soku/ashi) | foot, leg | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #36, Grade 1, 7 strokes. Readings: SOKU; *ashi* (foot/leg), *ta(riru)* (be sufficient), *ta(su)* (add/supplement). |
| 足跡 (ashi-ato) | footprint | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #36 足. |
| 満足 (manzoku) | satisfaction | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #36 足. |
| 不足 (fusoku) | insufficiency | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #36 足. |
| 立 (ritsu/ryū/tatsu) | to stand | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #37, Grade 1, 5 strokes. Readings: RITSU, RYŪ; *ta(tsu)* (v.i., to stand), *ta(teru)* (v.t., to erect/set up). |
| 独立 (dokuritsu) | independence | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #37 立. |
| 役立つ (yakudatsu) | useful | verb | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #37 立. |
| 立場 (tachiba) | standpoint | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #37 立. |
| 力 (ryoku/riki/chikara) | strength, power | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #38, Grade 1, 5 strokes. Readings: RYOKU, RIKI; *chikara*. |
| 力持ち (chikaramochi) | strong person | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #38 力. |
| 協力 (kyōryoku) | co-operation | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #38 力. |
| 努力 (doryoku) | endeavor | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #38 力. |
| 人 (jin/nin/hito) | person | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #39, Grade 1, 2 strokes. Readings: JIN, NIN; *hito*. |
| 人類 (jinrui) | human race | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #39 人. |
| 人間 (ningen) | human being | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #39 人. |
| 人口 (jinkō) | population | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #39 人. |
| 子 (shi/su/ko) | child | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #40, Grade 1, 3 strokes. Readings: SHI, SU; *ko*. |
| 子ども (kodomo) | child, children | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #40 子. |
| 原子 (genshi) | atom | noun | core | technical.science | — | contemporary | — | — | dictionary | n/a | verified | Compound of #40 子. |
| 様子 (yōsu) | the state of things, appearance | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #40 子. |
| 女 (jo/nyo/onna) | female, woman, girl | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #41, Grade 1, 3 strokes. Readings: JO, NYO; *me* (female), *onna* (woman/girl). |
| 女中 (jochū) | maid | noun | core | archaic | contemporary (source published 2003) | — | — | dictionary | n/a | verified | Compound of #41 女; dated occupational term, flagged by Notes rather than Usage Tier field inference — source gives no explicit register label. |
| 少女 (shōjo) | maiden | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #41 女. |
| 女王 (joō) | queen | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #41 女. |
| 男 (dan/nan/otoko) | man, male | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #42, Grade 1, 7 strokes. Readings: DAN, NAN; *otoko*. |
| 男性 (dansei) | male sex, male | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #42 男. |
| 男子 (danshi) | male, boy | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #42 男. |
| 長男 (chōnan) | eldest son | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #42 男. |
| 先 (sen/saki) | previous, ahead | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #43, Grade 1, 6 strokes. Readings: SEN; *saki*. |
| 先生 (sensei) | teacher | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #43 先; shares 生 with #44. |
| 先日 (senjitsu) | the other day | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #43 先. |
| 行き先 (yukisaki) | destination | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #43 先. |
| 生 (sei/shō/umareru) | birth, life | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #44, Grade 1, 5 strokes. Readings: SEI, SHŌ; *u(mareru)* (be born), *u(mu)* (give birth), *i(kiru)* (live), *ki* (pure/genuine), *nama* (raw), *ha(eru)* (grow/spring up). Notably the richest reading set among the Grade-1 set. |
| 一生 (isshō) | one's (whole) life | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #44 生. |
| 生活 (seikatsu) | livelihood | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #44 生. |
| 大学生 (daigakusei) | college student | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #44 生; shares 大学 with #25. |
| 学 (gaku) | learning, science | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #45, Grade 1, 8 strokes. Readings: GAKU; *mana(bu)*. |
| 学校 (gakkō) | school | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #45 学. |
| 医学 (igaku) | medicine | noun | core | technical.medical | — | contemporary | — | — | dictionary | n/a | verified | Compound of #45 学. |
| 科学 (kagaku) | science | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #45 学. |
| 校 (kō) | school | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #46, Grade 1, 10 strokes. Reading: KŌ (no kun reading listed); meanings also include "to correct, to investigate, to compare, to think." |
| 校正 (kōsei) | proofreading | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #46 校. |
| 校舎 (kōsha) | school building | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #46 校. |
| 校友 (kōyū) | alumnus | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #46 校. |
| 王 (ō) | king | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #47, Grade 1, 4 strokes. Reading: Ō (on reading only, no kun). |
| 王様 (ōsama) | king | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #47 王; honorific -sama suffix. |
| 王子 (ōji) | prince | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #47 王. |
| 王国 (ōkoku) | kingdom, monarchy | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #47 王. |
| 玉 (gyoku/tama) | jewel, round object | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #48, Grade 1, 5 strokes. Readings: GYOKU; *tama*. |
| 水玉 (mizutama) | drop of water | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #48 玉; shares 水 with #16. |
| 目玉 (medama) | eyeball | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #48 玉; shares 目 with #30. Only 2 compounds given for this character (source provides fewer than 3 for some entries). |
| 貝 (kai) | sea shell | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #49, Grade 1, 7 strokes. Reading given only in lowercase as "kai" — per the source's own typographic convention (p. xi) this marks it as having no formal on-reading, kun-only entry. |
| 貝殻 (kaigara) | shell | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #49 貝. |
| 貝拾い (kaihiroi) | shell gathering | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #49 貝. |
| 真珠貝 (shinjugai) | pearl oyster | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #49 貝. |
| 円 (en/marui) | circle, yen | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #50, Grade 1, 4 strokes. Readings: EN (also "yen," Japan's monetary unit); *maru(i)* (round). |
| 円満 (enman) | perfection, satisfaction | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #50 円. |
| 千円札 (sen'ensatsu) | thousand-yen bill | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #50 円; shares 千 with #12. |
| 円盤 (enban) | disc | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #50 円. |
| 赤 (seki/shaku/akai) | red | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #51, Grade 1, 7 strokes. Readings: SEKI, SHAKU; *aka*, *aka(i)* (red), *aka(rameru)* (v.t., to color up/add blush), *aka(ramu)* (to turn red/blush). |
| 赤ちゃん (akachan) | baby, infant | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #51 赤. |
| 赤十字 (sekijūji) | Red Cross | proper noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #51 赤. |
| 赤銅 (shakudō) | alloy of copper and gold | noun | core | technical | — | contemporary | — | — | dictionary | n/a | verified | Compound of #51 赤; traditional Japanese metal alloy term. |
| 青 (sei/shō/aoi) | blue, green | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #52, Grade 1, 8 strokes. Readings: SEI, SHŌ; *ao*, *ao(i)* (blue/green/inexperienced). |
| 青年 (seinen) | youth | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #52 青; duplicate cross-reference, also listed under #20 年. |
| 青白い (aojiroi) | pale | adjective | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #52 青. |
| 青空 (aozora) | blue sky | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #52 青; duplicate cross-reference, also listed under #66 空. |
| 白 (haku/byaku/shiroi) | white | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #53, Grade 1, 5 strokes. Readings: HAKU, BYAKU; *shiro*, *shiro(i)*. |
| 白人 (hakujin) | Caucasian | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #53 白. |
| 白状 (hakujō) | confession | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #53 白. |
| 白鳥 (hakuchō) | swan | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #53 白. |
| 夕 (seki/yū) | evening | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #54, Grade 1, 3 strokes. Readings: SEKI; *yū*. |
| 夕方 (yūgata) | evening | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #54 夕. |
| 夕飯 (yūhan) | supper | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #54 夕. |
| 夕風 (yūkaze) | evening breeze | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #54 夕. |
| 名 (mei/myō/na) | name, fame | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #55, Grade 1, 6 strokes. Readings: MEI, MYŌ; *na*. |
| 名まえ (namae) | name | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #55 名. |
| 有名 (yūmei) | famous, well-known | adj noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #55 名. |
| 名人 (meijin) | an expert | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #55 名. |
| 早 (sō/hayai) | early, fast | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #56, Grade 1, 6 strokes. Readings: SŌ; *haya*, *haya(i)*. |
| 早口 (haya-guchi) | quick speaking | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #56 早. |
| 早春 (sōshun) | early spring | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #56 早. |
| 手早い (tebayai) | quick, nimble | adjective | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #56 早; shares 手 with #35. |
| 草 (sō/kusa) | grass, vegetation | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #57, Grade 1, 9 strokes. Readings: SŌ; *kusa*. |
| 草原 (kusahara / kusawara) | grassy plain | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #57 草; two accepted readings. |
| 草案 (sōan) | draft (of a manuscript) | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #57 草. |
| 草取り (kusatori) | weeding | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #57 草. |
| 山 (san/yama) | mountain | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #58, Grade 1, 3 strokes. Readings: SAN; *yama*. |
| 山道 (sandō / yamamichi) | mountain path | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #58 山; two accepted readings. |
| 山脈 (sanmyaku) | mountain range | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #58 山. |
| 登山 (tozan) | mountain climbing | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #58 山. |
| 川 (sen/kawa) | river | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #59, Grade 1, 3 strokes. Readings: SEN; *kawa*. |
| 谷川 (tanigawa) | mountain stream | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #59 川. |
| 川ばた (kawabata) | riverside | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #59 川. |
| 川口 (kawaguchi) | mouth of a river | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #59 川; shares 口 with #34. |
| 田 (den/ta) | rice field | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #60, Grade 1, 5 strokes. Readings: DEN; *ta*. |
| 田園 (den'en) | fields and gardens, rural districts | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #60 田. |
| 稲田 (inada) | rice field | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #60 田. |
| 田植 (taue) | rice planting | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #60 田. |
| 町 (chō/machi) | town | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #61, Grade 1, 7 strokes. Readings: CHŌ; *machi*. |
| 町外れ (machihazure) | outskirts of a town | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #61 町. |
| 町内 (chōnai) | the neighborhood | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #61 町. |
| 町長 (chōchō) | mayor of a town | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #61 町. |
| 村 (son/mura) | village | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #62, Grade 1, 7 strokes. Readings: SON; *mura*. |
| 村民 (sonmin) | villager | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #62 村. |
| 村長 (sonchō) | village mayor | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #62 村. |
| 農村 (nōson) | a farm village | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #62 村. |
| 車 (sha/kuruma) | wheel, vehicle | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #63, Grade 1, 7 strokes. Readings: SHA; *kuruma*. |
| 自動車 (jidōsha) | automobile | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #63 車. |
| 自転車 (jitensha) | bicycle | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #63 車. |
| 発車 (hassha) | departure of a vehicle | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #63 車. |
| 林 (rin/hayashi) | woods | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #64, Grade 1, 8 strokes. Readings: RIN; *hayashi*. |
| 植林 (shokurin) | reforestation | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #64 林. |
| 密林 (mitsurin) | thick forest | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #64 林. |
| 農林 (nōrin) | agriculture and forestry | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #64 林; shares 農 with #62's 農村. |
| 森 (shin/mori) | forest, grove | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #65, Grade 1, 12 strokes. Readings: SHIN; *mori*. |
| 森林 (shinrin) | forest | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #65 森; shares 林 with #64. |
| 森閑 (shinkan) | silent | adj noun | core | literary | contemporary | — | — | dictionary | n/a | verified | Compound of #65 森. |
| 森厳 (shingen) | solemn, awe-inspiring | adj noun | core | literary | contemporary | — | — | dictionary | n/a | verified | Compound of #65 森. |
| 空 (kū/sora) | sky | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #66, Grade 1, 8 strokes. Readings: KŪ; *sora* (sky), *a(ku)* (become empty), *a(keru)* (vacate), *kara* (emptiness). |
| 青空 (aozora) | blue sky | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #66 空; duplicate cross-reference, see #52 青. |
| 空気 (kūki) | air | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #66 空. |
| 空港 (kūkō) | airport | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #66 空. |
| 天 (ten/ame) | sky, heaven | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #67, Grade 1, 4 strokes. Readings: TEN; *ame*. |
| 天気 (tenki) | weather | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #67 天. |
| 天井 (tenjō) | ceiling | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #67 天. |
| 天才 (tensai) | genius | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #67 天. |
| 気 (ki/ke) | spirit, energy, mind | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #68, Grade 1, 6 strokes. Readings: KI; KE (secondary on reading, no separate kun). |
| 天気 (tenki) | weather | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #68 気; duplicate cross-reference, see #67 天. |
| 元気 (genki) | good spirits, health | noun/adj | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #68 気. |
| 病気 (byōki) | sickness | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #68 気. |
| 雨 (u/ame) | rain | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #69, Grade 1, 8 strokes. Readings: U; *ame*. |
| 大雨 (ō-ame) | heavy rain | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #69 雨. |
| 雨戸 (amado) | rain door, shutter | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #69 雨; illustrates the ame→ama- compound-form reading shift the Introduction specifically calls out (see Grammar Points below). |
| 梅雨 (baiu) | rainy season of early summer | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #69 雨; irregular reading (not a simple on/kun reading of either character — a gikun/jukujikun-type special reading). |
| 花 (ka/hana) | flower | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #70, Grade 1, 7 strokes. Readings: KA; *hana*. |
| 花屋 (hanaya) | flower shop, florist | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #70 花. |
| 花びん (kabin) | vase | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #70 花. |
| 花火 (hanabi) | fireworks | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #70 花; shares 火 with #15. |
| 竹 (chiku/take) | bamboo | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #71, Grade 1, 6 strokes. Readings: CHIKU; *take*. |
| 竹やぶ (takeyabu) | bamboo grove | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #71 竹. |
| 竹細工 (takezaiku) | bamboo ware | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #71 竹. |
| 竹かご (takekago) | bamboo basket | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #71 竹. |
| 石 (seki/koku/shaku/ishi) | stone | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #72, Grade 1, 5 strokes. Readings: SEKI, KOKU, SHAKU; *ishi*. |
| 小石 (ko-ishi) | pebble | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #72 石; shares 小 with #27. |
| 石炭 (sekitan) | coal | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #72 石. |
| 磁石 (jishaku) | magnet | noun | core | technical | — | contemporary | — | — | dictionary | n/a | verified | Compound of #72 石. |
| 犬 (ken/inu) | dog | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #73, Grade 1, 4 strokes. Readings: KEN; *inu*. |
| 小犬 (ko-inu) | puppy | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #73 犬. |
| 番犬 (banken) | watchdog | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #73 犬. |
| 狂犬病 (kyōkenbyō) | rabies | noun | core | technical.medical | — | contemporary | — | — | dictionary | n/a | verified | Compound of #73 犬; shares 病 with #68's 病気. |
| 虫 (chū/mushi) | insect, bug, worm | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #74, Grade 1, 6 strokes. Readings: CHŪ; *mushi*. |
| 害虫 (gaichū) | harmful insect | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #74 虫. |
| 虫歯 (mushiba) | decayed tooth | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #74 虫. |
| 昆虫 (konchū) | insect, bug | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #74 虫. |
| 糸 (shi/ito) | thread | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #75, Grade 1, 6 strokes. Readings: SHI; *ito*. |
| 毛糸 (keito) | woolen yarn | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #75 糸. |
| 糸口 (itoguchi) | clue | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #75 糸; shares 口 with #34. |
| 糸巻き (itomaki) | spool for thread | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #75 糸. |
| 本 (hon/moto) | book | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #76, Grade 1, 5 strokes. Readings: HON (book; also suffix for counting long/slender objects); *moto* (basis, essence, tree-root). |
| 一本 (ippon) | one (bottle, rod, etc.) | counter/noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #76 本; shares 一 with #1, illustrates 本 as a counter suffix. |
| 本箱 (honbako) | bookcase | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #76 本. |
| 日本 (Nihon / Nippon) | Japan | proper noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #76 本; shares 日 with #13. Two accepted readings for the country name itself. |
| 文 (bun/mon/fumi) | writings, a sentence | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #77, Grade 1, 4 strokes. Readings: BUN (writings/sentence); MON (old unit of money); *fumi* (letter/book). |
| 文化 (bunka) | culture | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #77 文. |
| 文学 (bungaku) | literature | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #77 文; shares 学 with #45. |
| 文部大臣 (Monbudaijin) | Minister of Education | proper noun/title | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #77 文; historical cabinet-post title (pre-2001 Ministry of Education name), illustrates MON reading. |
| 字 (ji/aza) | letter, mark | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #78, Grade 1, 6 strokes. Readings: JI; *aza* (section of a village). |
| 字引 (jibiki) | dictionary | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #78 字. |
| 文字 (moji / monji) | letter, character, ideograph | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #78 字; shares 文 with #77; two accepted readings. |
| 数字 (sūji) | number, numeral | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #78 字. |
| 正 (sei/shō/tadashii) | correct, right | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #79, Grade 1, 5 strokes. Readings: SEI, SHŌ; *tada(shii)* (correct/right), *tada(su)* (correct/rectify), *masa(ni)* (surely/truly). |
| 正直 (shōjiki) | honesty | noun/adj | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #79 正. |
| 正方形 (seihōkei) | square (geometrical figure) | noun | core | technical | — | contemporary | — | — | dictionary | n/a | verified | Compound of #79 正. |
| 正月 (shōgatsu) | New Year's | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #79 正; shares 月 with #14. |
| 休 (kyū/yasumi) | rest, vacation | character (kanji) | core | — | contemporary | — | — | dictionary | n/a | verified | Kanji #80, Grade 1 (final character), 6 strokes. Readings: KYŪ; *yasu(mi)* (rest/vacation), *yasu(mu)* (to rest). |
| 休憩 (kyūkei) | rest, intermission | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #80 休. |
| 休日 (kyūjitsu) | holiday | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #80 休. |
| 休養 (kyūyō) | relaxation, recreation | noun | core | — | contemporary | — | — | dictionary | n/a | verified | Compound of #80 休. |

## Grammar points

### The multi-script writing system (2.1–2.2, pp. v–vi)

Modern Japanese uses three co-existing script types: the officially curated kanji corpus (the
*Jōyō kanji* / General Use Characters list, 1,945 characters as of the 1981 revision, which replaced
an earlier 1946 list of 1,850), plus the two kana syllabaries (hiragana, katakana). Of the 1,945
kanji, 1,006 ("Essential Characters") are taught across the six years of elementary school; the
remaining 939 are spread across intermediate/high school. This book is organized around exactly that
official split: Section One = the 1,006; Section Two = the full 1,945. As of 2001, the Japan
Newspaper Association additionally adopted 39 characters beyond the official JK List for newspaper
use (the source lists but does not gloss these: 闇鍋牙瓦鶴玩磯臼脇錦駒詣拳鍵虎虹尻柿餌腫袖腎須誰腺曽酎枕賭瞳頓丼汎斑釜謎妖嵐呂).

### On-yomi vs. kun-yomi (2.2, pp. vi–viii)

Each kanji typically carries two reading classes: *on-yomi* (a Sino-Japanese reading derived from
the Chinese pronunciation at the time the character was borrowed, roughly 2,000 years ago) and
*kun-yomi* (the native Japanese reading, i.e. the pre-existing Japanese word the character was
mapped onto). A character may have multiple on readings (reflecting different historical borrowing
layers) and/or multiple kun readings; context and the presence/absence of okurigana (trailing kana)
disambiguate which applies. Some characters lack one reading class entirely — e.g. 糖 ("sugar") is
on-only (TŌ), while 箱 ("box") is kun-only (*hako*). This book deliberately excludes archaic/rare
readings (e.g. *nagomu* "to soften" for 和) to keep scope pedagogically useful rather than
philologically exhaustive.

**Readings truncate/shift in compounds** — a pattern worth flagging for this project's mechanics
analysis, since it is a systematic phonological alternation triggered purely by compounding, not by
any separate grammatical marker: 学 GAKU → GAK- in 学校 *gakkō*; 雨 *ame* → *ama-* in 雨戸 *amado*;
合 GŌ → GAT- in 合点 *gatten*. The vocabulary table above includes a live example of this (雨戸 under
#69 雨) rather than only the source's own illustrative pair.

### Stroke-order principles (2.3, pp. vii–viii)

Characters should be written at a uniform apparent size regardless of stroke count (a 2-stroke
character like 刀 should occupy the same visual square as a 15-stroke one like 論), and a radical
component is written smaller within a compound character than the same element would be as a
freestanding character (言 alone vs. 言 as the left radical in 論). Seven ordering rules are given,
illustrated with worked kanji in each case:
1. Top to bottom (三, 育, 築).
2. Left to right (川, 村, 湖).
3. When strokes cross, horizontal usually precedes perpendicular (十, 共, 末).
4. Sometimes perpendicular precedes horizontal instead (田, 王, 里) — i.e. rule 3 is a tendency, not
   absolute.
5. Center stroke(s) first, then left and right (小, 承, 楽).
6. A perpendicular line running through the character's center is written last (中, 車, 書).
7. A right-to-left diagonal stroke precedes a left-to-right one where both occur (人, 文, 支).

### Romanization conventions (2.4, pp. ix–x)

This edition uses a modified Hepburn system. Modifications/conventions: (1) syllabic ん is
romanized *n* (not *m*) even before *m*/*b*/*p* — *shinbun* "newspaper," not *shimbun*; *kenpō*
"constitution," not *kempō*; (2) macrons mark vowel length for *o* and *u* (*gakkō* "school," *renshū*
"practice"); (3) a hyphen may separate constituent elements for clarity (*sara-arai* "dishwashing"
vs. ambiguous *saraarai*); (4) an apostrophe follows syllabic ん before a vowel/y- to disambiguate
from a true geminate-reading sequence — *tan'i* "unit" (3 morae, たんい) vs. *tani* "valley" (2 morae,
たに).

### Kana overview (2.5, p. x)

Hiragana and katakana are both full syllabaries (not alphabets — each symbol is a mora, not a single
phoneme) that evolved over centuries into their current standardized forms. **Script choice is
functionally and semantically meaningful, not arbitrary**: katakana today is used first and foremost
for loanwords of European origin (パン *pan* "bread," ビール *biiru* "beer"), while hiragana carries
grammatical particles, verb/adjective inflectional endings, and words whose kanji would be unusual or
overly intricate for ordinary use (鸚鵡 *ōmu* "parrot," 石鹸's *ken* in *sekken* "soap" are both
routinely written in hiragana instead). This is the project's clearest documented case so far of
script-as-register-marker: the same lexical item's *script* carries information independent of its
phonetic content.

### Layout details governing the dictionary's own structure (3, pp. x–xi)

The source itself documents its organizing scheme, which is necessary context for correctly reading
any portion of this dictionary (and for future dispatches continuing this extraction):
- Section One's 1,006 Essential Characters are ordered by the Education Ministry's six-grade
  division, **in running sequence, with explicit grade boundaries**:
  - Grade 1 = kanji #1–80 (fully extracted in this file)
  - Grade 2 = #81–240
  - Grade 3 = #241–440
  - Grade 4 = #441–640
  - Grade 5 = #641–825
  - Grade 6 = #826–1,006
- Within each grade, characters are ordered by the traditional *gojūon* ("50 sounds") sequence —
  **except Grade 1, which is instead ordered by semantic grouping** (confirmed directly from the
  extracted data above: numbers 1–12, calendar/time terms, elements, directions, body parts, kinship
  terms, nature terms, etc. cluster together rather than following kana order).
  Each entry typically gives on-reading(s) in capitals, then kun-reading(s) in lowercase (with
  okurigana in parentheses), then English meaning(s); a bare on-reading followed by a comma (e.g.
  "ZA, seat...") marks it as usable as a standalone word, vs. no comma meaning the on-reading never
  stands alone.
- Section Two (1,945 total characters, i.e. including all 1,006 plus 939 more) is instead ordered by
  stroke count, then by radical within a given stroke count — **and gives on/kun readings and meaning
  only, no stroke diagrams, no illustrative compounds** (to avoid duplicating Section One, each of
  the 1,006 characters' Section Two entry simply cross-references its Section One entry number).
- A final section (not yet reached in this extraction) presents individual hiragana/katakana symbols
  with their own stroke-order diagrams, followed by an alphabetical index of readings for all 1,945
  characters.

This structural information means **later dispatches extracting Section Two should expect much
thinner per-character content** (no compounds) for non-Essential characters, and should cross-check
Section Two's stated cross-references against this file's #1–80 rather than re-extracting duplicate
compound data.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`. Stroke-order diagrams
(the cell-by-cell progression images themselves) were deliberately not transcribed cell-by-cell;
only the underlying *rules* they illustrate were paraphrased above.

---

## Continuation note

**Not yet covered, for a future dispatch:**
- Section One, Grade 2 (kanji #81–240) through Grade 6 (#826–1,006) — resume vision-reading at PDF
  page 31 (kanji #81, printed page 18).
- Section Two (the remaining 939 non-Essential General Use characters, ordered by stroke
  count/radical, no compounds).
- The hiragana/katakana syllabary + stroke-order section near the end of the book.
- The alphabetical index of readings (likely low extraction value — a lookup index, not original
  content).

Given the book's total length (335 PDF pages) and the density confirmed in this first chunk (~5
kanji + ~15 compounds per page), a full Section One extraction alone would span roughly 18 more
files at this granularity. Future dispatches should consider whether later grades/Section Two warrant
the same full-compound treatment or a lighter per-page summary (e.g. one row per kanji with compounds
folded into Notes instead of separate rows), given this project's "comprehensive but not exhaustive"
coverage principle and the precedent of sampling oversized dictionary-type sources.
