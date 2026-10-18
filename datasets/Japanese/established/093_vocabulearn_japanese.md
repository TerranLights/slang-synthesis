# Japanese — Established Vocabulary/Grammar: VocabuLearn Japanese Complete (Levels 1-3), representative sample

**Source:** *VocabuLearn® Japanese, English/Japanese*, Levels I, II, III (Penton Overseas-style
audio-cassette vocabulary-drill program; no printer's copyright/ISBN page present — back cover of
Level 1 reads "Printed in Mexico", catalog code `Z-WDL-JAP 1 1403`). Each level ships as a DjVu file
and a same-named "booklet N.pdf" in `source_reference/.../VocabuLearn Japanese Complete/Level {1,2,3}/`.

**Structural finding (DjVu vs. booklet — not double content):** The `.djvu` and `booklet N.pdf` for
each level are **the identical scanned booklet**, not complementary materials — confirmed by
rendering matching pages from both files at Level 1 p.10 and Level 3 p.20/44 and finding pixel-identical
layouts (same OCR-free raster scan in both container formats, same page counts: Level 1 = 48pp,
Level 2 = 48pp, Level 3 = 52pp). **Only the DjVu was used for extraction**; the booklet PDF was
consulted solely to cross-check a page that looked scan-damaged (see gotcha below). No audio content
exists in `source_reference/` for this item — the "Disc N" subfolders alongside each DjVu are empty
(audio tracks were not retained), so nothing beyond the booklet text is available to extract.

**Booklet internal structure (same across all 3 levels):** p.1 = English-language program
introduction; p.2 = "Notes About the Vocabulary Lists" (format legend, no actual vocabulary). The
remaining pages are organized as 4 "CD"/section blocks per level — **Nouns**, **Adjectives &
Adverbs**, **Expressions**, **Verbs** — and **each section is itself printed twice**: once
English-term-first ("ENGLISH/JAPANESE" header) and once Japanese-term-first ("JAPANESE/ENGLISH"
header, reversed-direction drill for recall practice), per the program's own stated design (p.1: "the
first half...introduces the English word/expression first...The second half is reversed"). **The
two directions are the same vocabulary list reordered, not new content** — confirmed by inspecting
the EN-first and JA-first halves of the same section (e.g. Level 1 Expressions, Level 2 Adj/Adv). To
avoid double-extracting identical word pairs under this project's non-redundant-supplement
discipline, this file draws from **both directions across different sections** (so the full
thematic range of each section is sampled) but never re-transcribes the same section's reversed half.

**Coverage note — representative sampling, not exhaustive:** This is a flat flashcard-drill
vocabulary series with no exercises, grammar explanation, or annotation beyond the format legend —
thousands of word/phrase pairs across the 3 levels (48-52 pages/level, ~35-40 pairs/page). Per this
dispatch's instruction, **representative sampling** was used instead of exhaustive transcription:
2-3 full pages were vision-read per section per level (Nouns / Adj-Adv / Expressions / Verbs ×
Levels 1-3 = 12 section-slots, ~30 pages total), spanning the opening, middle, and closing portion of
each section so the thematic range (concrete nouns → abstract/technical nouns from L1→L3; basic
descriptors → idiomatic/literary adjectives from L1→L3; practical travel phrases → literary/
emotional idioms from L1→L3) is represented rather than exhausted. Levels increase in register and
abstraction as advertised (Level 1 = concrete/everyday; Level 3 = abstract nouns, literary
adjectives, and some adult-topic vocabulary e.g. 売春婦 "prostitute", 犯す "to rape" appearing
alongside ordinary verbs with no register annotation from the source itself).

**Vision-reading guard:** No text layer in either the DjVu or the PDF (`djvutxt` returns empty
output; both are raster scans) — all entries below were vision-read from rendered page images
(DjVu pages rendered via `ddjvu -format=ppm`, converted with `ffmpeg`). No handwritten marginalia was
found on any page inspected; all content read is clearly typeset/printed.

**Scan-defect gotcha (flag, not used as primary data):** Level 3 DjVu/PDF page showing internal
page number "18" (file page 20) has its **left margin cut off in the original scan** — the first
1-3 characters of every Japanese term on that page are physically missing in both the DjVu and the
booklet PDF (confirmed identical crop in both containers, so it's a defect in the original scanned
booklet itself, not a rendering artifact). English glosses and romaji are intact; only the Japanese
script column is affected. This page was **not** used for extraction below — an adjacent, uncropped
page (internal p.16) was used instead for Level 3's Adjectives/Adverbs sample. Worth flagging for any
future deeper pass into Level 3's Adj/Adv section, since the defect may recur on other pages in that
run.

**Attested Era / Region:** No publication year, publisher name, or edition statement is printed
anywhere in the booklet (checked front matter and back page) — left as `—` rather than guessed.

---

## Vocabulary

### Level 1 — Nouns (p.1-2, 8 of the DjVu; English-first direction)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 草 (Kusa) | the grass | noun | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD1 Nouns, p.1. |
| 月 (Tsuki) | the moon | noun | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD1 Nouns, p.1. |
| 音 (Oto) | the sound | noun | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD1 Nouns, p.1. |
| 空港 (Kūkō) | the airport | noun | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD1 Nouns, p.1. |
| 12月 (Jūnigatsu) | December | noun | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD1 Nouns, p.1. |
| 希望 (Kibō) | the hope | noun | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD1 Nouns, p.1. |
| 火 (Hi) | the fire | noun | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD1 Nouns, p.1. |
| ウール (Wūru) | the wool | noun | core | — | — | — | — | dictionary | n/a | verified | Katakana loanword from English "wool." Level 1, CD1 Nouns, p.1. |
| 愛 (Ai) | the love | noun | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD1 Nouns, p.1. |
| 冬 (Fuyu) | the winter | noun | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD1 Nouns, p.1. |
| 出口 (Deguchi) | the exit | noun | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD1 Nouns, p.1. |
| ほうれん草 (Hōrensō) | the spinach | noun | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD1 Nouns, p.1. |
| 木曜日 (Mokuyōbi) | Thursday | noun | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD1 Nouns, p.1. |
| アイスクリーム (Aisukurīmu) | the ice cream | noun | core | — | — | — | — | dictionary | n/a | verified | Katakana loanword. Level 1, CD1 Nouns, p.1. |
| 山 (Yama) | the mountain | noun | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD1 Nouns, p.1. |
| ハンドバッグ (Handobaggu) | the purse | noun | core | — | — | — | — | dictionary | n/a | verified | Katakana loanword "handbag." Level 1, CD1 Nouns, p.1. |
| 勘定書 (Kanjōgaki) | the bill (restaurant) | noun | core | — | — | — | — | dictionary | n/a | verified | Parenthetical context note is the source's own disambiguation convention (per booklet's "Notes About the Vocabulary Lists" item 1). Level 1, CD1 Nouns, p.1. |
| 生命 (Seimei) | the life | noun | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD1 Nouns, p.2. |
| 学生 (Gakusei) | the student | noun | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD1 Nouns, p.2. |
| 友達 (Tomodachi) | the friend | noun | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD1 Nouns, p.2. |
| 言語 (Gengo) | the language | noun | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD1 Nouns, p.2. |
| 姉妹 (Shimai) | the sister | noun | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD1 Nouns, p.2. |
| 実業家 (Jitsugyōka) | the businessman | noun | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD1 Nouns, p.2. |
| 誤り (Ayamari) | the mistake | noun | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD1 Nouns, p.2. |
| 馬 (Uma) | the horse | noun | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD1 Nouns, p.2. |
| ファッション (Fasshon) | the fashion | noun | core | — | — | — | — | dictionary | n/a | verified | Katakana loanword. Level 1, CD1 Nouns, p.2. |
| タバコ (Tabako) | the tobacco | noun | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD1 Nouns, p.2. |
| 手段 (Shudan) | the means | noun | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD1 Nouns, p.2. |
| 映画館 (Eigakan) | the movie theater | noun | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD1 Nouns, p.2. |
| 自動車 (Jidōsha) | the automobile | noun | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD1 Nouns, p.2. |
| プログラム (Puroguramu) | the program | noun | core | — | — | — | — | dictionary | n/a | verified | Katakana loanword. Level 1, CD1 Nouns, p.2. |
| 売手 (Urite) | the seller | noun | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD1 Nouns, p.2. |
| 雑誌 (Zasshi) | the magazine | noun | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD1 Nouns, p.2. |
| 場所 (Basho) | the place | noun | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD1 Nouns, p.2. |
| 子供 (Kodomo) | the child | noun | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD1 Nouns, p.2. |
| 鍵 (Kagi) | the key | noun | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD1 Nouns, p.8. |
| 切手 (Kitte) | the postage stamp | noun | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD1 Nouns, p.8. |
| 工場 (Kōjō) | the factory | noun | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD1 Nouns, p.8. |
| 仕事 (Shigoto) | the work — the job | noun | core | — | — | — | — | dictionary | n/a | verified | Source itself lists both English synonyms (per "Notes" item 2). Level 1, CD1 Nouns, p.8. |
| 石鹸 (Sekken) | the soap | noun | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD1 Nouns, p.8. |
| 飛行機 (Hikōki) | the airplane | noun | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD1 Nouns, p.8. |
| 灰皿 (Haizara) | the ashtray | noun | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD1 Nouns, p.8. |
| 女中 (Jochū) | the maid | noun | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD1 Nouns, p.8. |
| 牛肉 (Gyūniku) | the beef | noun | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD1 Nouns, p.8. |
| 城 (Shiro) | the castle | noun | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD1 Nouns, p.8. |
| 郵便 (Yūbin) | the mail | noun | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD1 Nouns, p.8. |
| 歯医者 (Haisha) | the dentist | noun | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD1 Nouns, p.8. |
| 警察官 (Keisatsukan) | the policemen | noun | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD1 Nouns, p.8. |
| 毛布 (Mōfu) | the blanket | noun | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD1 Nouns, p.8. |
| 大聖堂 (Daiseidō) | the cathedral | noun | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD1 Nouns, p.8. |

### Level 1 — Adjectives & Adverbs (p.12-13; both halves of the section sampled)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| とてもおいしい (Totemo oishii) | delicious | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD2 Adj/Adv, p.13. |
| 長い (Nagai) | long | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD2 Adj/Adv, p.13. |
| 甘やかされた (Amayakasareta) | spoiled | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD2 Adj/Adv, p.13. |
| 著しい (Ichijirushii) | striking | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD2 Adj/Adv, p.13. |
| 賢い (Kashikoi) | wise | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD2 Adj/Adv, p.13. |
| 暗い (Kurai) | dark | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD2 Adj/Adv, p.13. |
| 前もって (Maemotte) | in advance | adverb | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD2 Adj/Adv, p.13. |
| 神経質な (Shinkeishitsu na) | nervous | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD2 Adj/Adv, p.13. |
| 怒った (Okotta) | angry | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD2 Adj/Adv, p.13. |
| 清潔な (Seiketsu na) | clean | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD2 Adj/Adv, p.13. |
| 幸いに (Saiwai ni) | fortunately | adverb | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD2 Adj/Adv, p.13. |
| まっすぐな (Massuguna) | straight | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD2 Adj/Adv, p.13. |
| 野心のある (Yashin no aru) | ambitious | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD2 Adj/Adv, p.13. |
| 途方もない (Tohō mo nai) | tremendous | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD2 Adj/Adv, p.13. |
| 多情の (Tajō no) | amorous | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD2 Adj/Adv, p.13. |
| 利己的な (Rikoteki na) | selfish | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD2 Adj/Adv, p.13. |
| 突然 (Totsuzen) | suddenly | adverb | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD2 Adj/Adv, p.13. |
| 大きい (Ōkii) | big, large, fat | adjective | core | — | — | — | — | dictionary | n/a | verified | Source itself lists all three English synonyms together. Level 1, CD2 Adj/Adv, p.13. |
| ～の最中に (~no saichū ni) | in the middle of | adverbial phrase | core | — | — | — | — | dictionary | n/a | verified | `～` marks a bound particle phrase attaching to a preceding noun — booklet's own notation. Level 1, CD2 Adj/Adv, p.12. |
| とうとう (Tōtō) | finally | adverb | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD2 Adj/Adv, p.12. |
| 誰？ (Dare?) | who? (subject) | pronoun | core | — | — | — | — | dictionary | n/a | verified | Question-particle usage marked by the source itself with "(subject)". Level 1, CD2 Adj/Adv, p.12. |
| どこにでも (Doko ni demo) | everywhere | adverb | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD2 Adj/Adv, p.12. |
| なぜ？ (Naze?) | why? | adverb | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD2 Adj/Adv, p.12. |
| それゆえに (Soreyue ni) | therefore, so | conjunction/adverb | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD2 Adj/Adv, p.12. |
| けれども (Keredomo) | however | conjunction | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD2 Adj/Adv, p.12. |
| 怠慢な (Taiman na) | lazy | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD2 Adj/Adv, p.12. |
| きれいな (Kirei na) | pretty | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD2 Adj/Adv, p.12. |
| 金持ちの (Kanemochi no) | rich | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD2 Adj/Adv, p.12. |
| 死んだ (Shinda) | dead | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD2 Adj/Adv, p.12. |
| それは何ですか？ (Sorewa nandesuka?) | what is that? | phrase | core | — | — | — | — | dictionary | n/a | verified | Full-sentence entry (not a single word) — reflects the source's own mix of lexical items and short set phrases within Adj/Adv. Level 1, CD2 Adj/Adv, p.12. |
| 柔かい (Yawarakai) | soft | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD2 Adj/Adv, p.12. |
| 忘れがたい (Wasure gatai) | unforgettable | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD2 Adj/Adv, p.12. |

### Level 1 — Expressions (p.23, 25; English-first direction)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 御免なさい。(Gomennasai.) | I'm sorry | expression | colloquial | — | — | — | — | dictionary | n/a | verified | Level 1, CD3 Expressions, p.23. |
| 今日は何月何日ですか？ (Kyō wa nangatsu nan nichi desuka?) | what's the date today? | expression | colloquial | — | — | — | — | dictionary | n/a | verified | Level 1, CD3 Expressions, p.23. |
| 十分です。(Jūbun desu.) | that's enough | expression | colloquial | — | — | — | — | dictionary | n/a | verified | Level 1, CD3 Expressions, p.23. |
| ところで (Tokorode) | by the way | expression | colloquial | — | — | — | — | dictionary | n/a | verified | Level 1, CD3 Expressions, p.23. |
| あなたの車は何色ですか？ (Anata no kuruma wa naniiro desuka?) | what color is your car? | expression | colloquial | — | — | — | — | dictionary | n/a | verified | Level 1, CD3 Expressions, p.23. |
| 私が勝ちました！ (Watakushi ga kachi mashita!) | I won! | expression | colloquial | — | — | — | — | dictionary | n/a | verified | Level 1, CD3 Expressions, p.23. |
| これはいくらですか？ (Kore wa ikura desuka?) | how much is it? | expression | colloquial | — | — | — | — | dictionary | n/a | verified | Level 1, CD3 Expressions, p.23. |
| こんなに沢山の物 (Konna ni takusan no mono) | so many things | expression | colloquial | — | — | — | — | dictionary | n/a | verified | Level 1, CD3 Expressions, p.23. |
| 私のスーツケースはどこですか？ (Watakushi no sūtsu kēsu wa doko desuka?) | where is my suitcase? | expression | colloquial | — | — | — | — | dictionary | n/a | verified | Level 1, CD3 Expressions, p.25. |
| 道を案内してください。(Michi o an'naishite kudasai.) | show me the way | expression | colloquial | — | — | — | — | dictionary | n/a | verified | Level 1, CD3 Expressions, p.25. |
| 私は彼女に夢中です。(Watakushi wa kanojo ni muchū desu.) | I am crazy about her | expression | colloquial | — | — | — | — | dictionary | n/a | verified | Level 1, CD3 Expressions, p.25. |
| あなたがおられなくなると寂しくなります。(Anata ga orarenaku naruto sabishiku nari masu.) | I'll miss you | expression | colloquial | — | — | — | — | dictionary | n/a | verified | Level 1, CD3 Expressions, p.25. |
| 貸室あり (Kashishitsu ari) | for rent | expression | colloquial | — | — | — | — | dictionary | n/a | verified | Level 1, CD3 Expressions, p.25. |
| タイヤがパンクする (Taiya ga panku suru) | to have a flat tire | expression | colloquial | — | — | — | — | dictionary | n/a | verified | "パンク" (panku) is a katakana loanword from English "puncture." Level 1, CD3 Expressions, p.25. |
| 彼の運転は速過ぎます。(Kare no unten wa hayasugi masu.) | he drives too fast | expression | colloquial | — | — | — | — | dictionary | n/a | verified | Level 1, CD3 Expressions, p.25. |
| 少しずつ (Sukoshi zutsu) | little by little | expression | colloquial | — | — | — | — | dictionary | n/a | verified | Level 1, CD3 Expressions, p.25. |
| 殆ど (Hotondo) | for the most part | expression | colloquial | — | — | — | — | dictionary | n/a | verified | Level 1, CD3 Expressions, p.25. |

### Level 1 — Verbs (p.37; English-first direction)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 捜す (Sagasu) | to search | verb | core | — | — | — | — | dictionary | n/a | verified | Same Term/reading given for both "to search" and "to hunt" in this list — source treats them as synonyms without separate entries. Level 1, CD4 Verbs, p.37. |
| ささやく (Sasayaku) | to whisper | verb | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD4 Verbs, p.37. |
| 逃げる (Nigeru) | to escape | verb | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD4 Verbs, p.37. |
| 破壊する (Hakai suru) | to ruin | verb | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD4 Verbs, p.37. |
| 信じる (Shinjiru) | to believe | verb | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD4 Verbs, p.37. |
| 話す (Hanasu) | to talk, to speak | verb | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD4 Verbs, p.37. |
| 食べる (Taberu) | to eat | verb | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD4 Verbs, p.37. |
| 輸入する (Yunyū suru) | to import | verb | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD4 Verbs, p.37. |
| 降参する (Kōsan suru) | to give in | verb | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD4 Verbs, p.37. |
| 祝う (Iwau) | to celebrate | verb | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD4 Verbs, p.37. |
| 過ごす (Sugosu) | to spend | verb | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD4 Verbs, p.37. |
| 表現する (Hyōgen suru) | to express | verb | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD4 Verbs, p.37. |
| ためらう (Tamerau) | to hesitate | verb | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD4 Verbs, p.37. |
| 虐殺する (Gyakusatsu suru) | to slaughter | verb | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD4 Verbs, p.37. |
| 修理する (Shūri suru) | to fix | verb | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD4 Verbs, p.37. |
| 歩く (Aruku) | to walk | verb | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD4 Verbs, p.37. |
| アイロンをかける (Airon o kakeru) | to iron | verb phrase | core | — | — | — | — | dictionary | n/a | verified | "アイロン" is a katakana loanword from English "iron." Level 1, CD4 Verbs, p.37. |
| 掃除をする (Sōji o suru) | to clean | verb phrase | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD4 Verbs, p.37. |
| けがをさせる (Kega o saseru) | to injure | verb phrase | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD4 Verbs, p.37. |
| 引きつける (Hikitsukeru) | to attract | verb | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD4 Verbs, p.37. |
| 拾い上げる (Hiroi ageru) | to pick up | verb | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD4 Verbs, p.37. |
| 感謝する (Kansha suru) | to thank | verb | core | — | — | — | — | dictionary | n/a | verified | Level 1, CD4 Verbs, p.37. |

### Level 2 — Nouns (p.1; English-first direction)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| レジ (Reji) | the cashier | noun | core | — | — | — | — | dictionary | n/a | verified | Katakana clipping of "register." Level 2, CD1 Nouns, p.1. |
| 腕 (Ude) | the arm | noun | core | — | — | — | — | dictionary | n/a | verified | Level 2, CD1 Nouns, p.1. |
| 娯楽 (Goraku) | an entertainment | noun | core | — | — | — | — | dictionary | n/a | verified | Level 2 uses indefinite articles "a"/"an" alongside "the" per the booklet's own stated design (Level 1 uses only "the"). Level 2, CD1 Nouns, p.1. |
| 弁護士 (Bengoshi) | the lawyer | noun | core | — | — | — | — | dictionary | n/a | verified | Level 2, CD1 Nouns, p.1. |
| 図書館 (Toshokan) | the library | noun | core | — | — | — | — | dictionary | n/a | verified | Level 2, CD1 Nouns, p.1. |
| 知人 (Chijin) | an acquaintance | noun | core | — | — | — | — | dictionary | n/a | verified | Level 2, CD1 Nouns, p.1. |
| 節/パラグラフ (Setsu/Paragurafu) | the paragraph | noun | core | — | — | — | — | dictionary | n/a | verified | Two near-synonymous terms listed together per "Notes" item 2 (native term + katakana loanword). Level 2, CD1 Nouns, p.1. |
| 雇用主 (Koyōnushi) | an employer | noun | core | — | — | — | — | dictionary | n/a | verified | Level 2, CD1 Nouns, p.1. |
| トランプ (Torampu) | the playing cards | noun | core | — | — | — | — | dictionary | n/a | verified | Katakana loanword from English "trump(s)." Level 2, CD1 Nouns, p.1. |
| ボール/まり (Bōru/Mari) | the ball | noun | core | — | — | — | — | dictionary | n/a | verified | Loanword + native synonym pair. Level 2, CD1 Nouns, p.1. |
| 所有者/持ち主 (Shoyūsha/Mochinushi) | an owner | noun | core | — | — | — | — | dictionary | n/a | verified | Level 2, CD1 Nouns, p.1. |
| 口紅 (Kuchibeni) | the lipstick | noun | core | — | — | — | — | dictionary | n/a | verified | Level 2, CD1 Nouns, p.1. |
| 湖 (Mizuumi) | the lake | noun | core | — | — | — | — | dictionary | n/a | verified | Level 2, CD1 Nouns, p.1. |
| 独身男性 (Dokushin Dansei) | the bachelor | noun | core | — | — | — | — | dictionary | n/a | verified | Level 2, CD1 Nouns, p.1. |
| 人形 (Ningyō) | the doll | noun | core | — | — | — | — | dictionary | n/a | verified | Level 2, CD1 Nouns, p.1. |
| 気分 (Kibun) | the mood | noun | core | — | — | — | — | dictionary | n/a | verified | Level 2, CD1 Nouns, p.1. |
| かど (Kado) | the turn (curve) | noun | core | — | — | — | — | dictionary | n/a | verified | Parenthetical sense-disambiguation is the source's own convention. Level 2, CD1 Nouns, p.1. |
| ノート/注 (Nōto/Chū) | the note | noun | core | — | — | — | — | dictionary | n/a | verified | Level 2, CD1 Nouns, p.1. |
| 怒り (Ikari) | the anger | noun | core | — | — | — | — | dictionary | n/a | verified | Level 2, CD1 Nouns, p.1. |

### Level 2 — Adjectives & Adverbs (p.18; Japanese-first direction)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 見事な (Migoto na) | admirable | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 2, CD2 Adj/Adv (reversed half), p.18. |
| 失業した (Shitsugyō shita) | unemployed | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 2, CD2 Adj/Adv (reversed half), p.18. |
| 女らしい (Onna rashii) | feminine | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 2, CD2 Adj/Adv (reversed half), p.18. |
| 込み合った (Komiatta) | crowded | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 2, CD2 Adj/Adv (reversed half), p.18. |
| 激しい (Hageshii) | fierce | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 2, CD2 Adj/Adv (reversed half), p.18. |
| ハンディキャップのある (Handikyappu no aru) | handicapped | adjective | core | — | — | — | — | dictionary | n/a | verified | Katakana loanword base "handicap." Level 2, CD2 Adj/Adv (reversed half), p.18. |
| カジュアルな (Kajuaru na) | casual | adjective | core | — | — | — | — | dictionary | n/a | verified | Katakana loanword. Level 2, CD2 Adj/Adv (reversed half), p.18. |
| 誤った (Ayamatta) | wrong | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 2, CD2 Adj/Adv (reversed half), p.18. |
| 歴史的に有名な (Rekishiteki ni yūmei na) | historic | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 2, CD2 Adj/Adv (reversed half), p.18. |
| 両方の (Ryōhō no) | both | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 2, CD2 Adj/Adv (reversed half), p.18. |
| 勇敢な (Yūkan na) | courageous | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 2, CD2 Adj/Adv (reversed half), p.18. |
| 人造の (Jinzō no) | artificial | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 2, CD2 Adj/Adv (reversed half), p.18. |

### Level 2 — Expressions (p.18, 33; mixed directions, taken from section-boundary pages)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 第2のチャンス (Dai ni no Chansu) | a second chance | expression | colloquial | — | — | — | — | dictionary | n/a | verified | Level 2, CD3 Expressions, p.18. |
| 彼はひどく腹を立てました。(Kare wa hidoku hara o tate mashita.) | he hit the roof | expression | colloquial | — | — | — | — | dictionary | n/a | verified | Idiom gloss, not literal; matches the source's own stated idiom-matching convention ("Notes" item 5). Level 2, CD3 Expressions, p.18. |
| 最も有効に利用しなさい。(Mottomo yūkō ni riyō shinasai.) | make the best of it | expression | colloquial | — | — | — | — | dictionary | n/a | verified | Level 2, CD3 Expressions, p.18. |
| 楽しんで下さい！ (Tanoshinde kudasai!) | enjoy yourself! | expression | colloquial | — | — | — | — | dictionary | n/a | verified | Level 2, CD3 Expressions, p.18. |
| 静かにしなさい。(Shizuka ni shinasai.) | keep quiet | expression | colloquial | — | — | — | — | dictionary | n/a | verified | Level 2, CD3 Expressions, p.18. |
| 注意を払いなさい。(Chūi o harainasai.) | pay attention | expression | colloquial | — | — | — | — | dictionary | n/a | verified | Level 2, CD3 Expressions (reversed half), p.33. |
| 標識にそって行って下さい。(Hyōshiki ni sotte itte kudasai.) | follow the signs | expression | colloquial | — | — | — | — | dictionary | n/a | verified | Level 2, CD3 Expressions (reversed half), p.33. |
| 彼は度忘れをしました。(Kare wa dowasure o shimashita.) | he had a memory lapse | expression | colloquial | — | — | — | — | dictionary | n/a | verified | Level 2, CD3 Expressions (reversed half), p.33. |
| ぶどう酒のあたり年。(Budōshu no atari-doshi.) | a vintage year | expression | colloquial | — | — | — | — | dictionary | n/a | verified | Level 2, CD3 Expressions (reversed half), p.33. |
| 見通しはいいです。(Mitōshi wa iidesu.) | things are looking good | expression | colloquial | — | — | — | — | dictionary | n/a | verified | Level 2, CD3 Expressions (reversed half), p.33. |
| やみ夜の中で。(Yamiyo no nakade.) | in the dark of night | expression | colloquial | — | — | — | — | dictionary | n/a | verified | Level 2, CD3 Expressions (reversed half), p.33. |
| 思い出せません。(Omoi dasemasen.) | it had slipped my mind | expression | colloquial | — | — | — | — | dictionary | n/a | verified | Level 2, CD3 Expressions (reversed half), p.33. |
| クリスマス気分になる。(Kurisumasu kibun ni naru.) | get in the Christmas spirit | expression | colloquial | — | — | — | — | dictionary | n/a | verified | "クリスマス" katakana loanword "Christmas." Level 2, CD3 Expressions (reversed half), p.33. |
| 面目喪失。(Menboku sōshitsu.) | a loss of face | expression | colloquial | — | — | — | — | dictionary | n/a | verified | Level 2, CD3 Expressions (reversed half), p.33. |
| それには関係しないように。(Soreniwa kankei shinai yōni.) | stay out of it | expression | colloquial | — | — | — | — | dictionary | n/a | verified | Level 2, CD3 Expressions (reversed half), p.33. |

### Level 2 — Verbs (p.40; Japanese-first direction)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 宣伝する (Senden suru) | to advertise | verb | core | — | — | — | — | dictionary | n/a | verified | Level 2, CD4 Verbs (reversed half), p.40. |
| 働く (Hataraku) | to labor | verb | core | — | — | — | — | dictionary | n/a | verified | Level 2, CD4 Verbs (reversed half), p.40. |
| 一般化する (Ippanka suru) | to generalize | verb | core | — | — | — | — | dictionary | n/a | verified | Level 2, CD4 Verbs (reversed half), p.40. |
| 存在する (Sonzai suru) | to exist | verb | core | — | — | — | — | dictionary | n/a | verified | Level 2, CD4 Verbs (reversed half), p.40. |
| 名をつける (Na o tsukeru) | to name | verb phrase | core | — | — | — | — | dictionary | n/a | verified | Level 2, CD4 Verbs (reversed half), p.40. |
| 賭ける (Kakeru) | to bet | verb | core | — | — | — | — | dictionary | n/a | verified | Level 2, CD4 Verbs (reversed half), p.40. |
| 保険をかける/保証する (Hoken o kakeru/Hoshō suru) | to insure | verb phrase | core | — | — | — | — | dictionary | n/a | verified | Two near-synonymous phrasings listed together. Level 2, CD4 Verbs (reversed half), p.40. |
| 目まいがする (Memai ga suru) | to feel dizzy | verb phrase | core | — | — | — | — | dictionary | n/a | verified | Level 2, CD4 Verbs (reversed half), p.40. |
| ～なしでする (~Nashi de suru) | to do without | verb phrase | core | — | — | — | — | dictionary | n/a | verified | `～` is the booklet's bound-particle notation for an attaching noun slot. Level 2, CD4 Verbs (reversed half), p.40. |
| 説得する (Settoku suru) | to persuade | verb | core | — | — | — | — | dictionary | n/a | verified | Level 2, CD4 Verbs, p.40. |
| だます (Damasu) | to deceive | verb | core | — | — | — | — | dictionary | n/a | verified | Level 2, CD4 Verbs, p.40. |
| マニキュアをする (Manikyua o suru) | to manicure | verb phrase | core | — | — | — | — | dictionary | n/a | verified | Katakana loanword base "manicure." Level 2, CD4 Verbs, p.40. |
| 戦う (Tatakau) | to fight | verb | core | — | — | — | — | dictionary | n/a | verified | Level 2, CD4 Verbs, p.40. |
| 苦しむ (Kurushimu) | to suffer | verb | core | — | — | — | — | dictionary | n/a | verified | Level 2, CD4 Verbs, p.40. |
| 成し遂げる (Nashi togeru) | to achieve | verb | core | — | — | — | — | dictionary | n/a | verified | Level 2, CD4 Verbs, p.40. |
| 鍵をかける (Kagi o kakeru) | to lock | verb phrase | core | — | — | — | — | dictionary | n/a | verified | Level 2, CD4 Verbs, p.40. |
| 否認する (Hinin suru) | to contradict | verb | core | — | — | — | — | dictionary | n/a | verified | Level 2, CD4 Verbs, p.40. |
| 通知する (Tsūchi suru) | to notify | verb | core | — | — | — | — | dictionary | n/a | verified | Level 2, CD4 Verbs, p.40. |

### Level 3 — Nouns (p.1; English-first direction)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 功績 (Kōseki) | an accomplishment | noun | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD1 Nouns, p.1 — level 3 nouns skew toward abstract/institutional vocabulary vs. Levels 1-2's concrete everyday nouns. |
| 状況 (Jōkyō) | a situation | noun | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD1 Nouns, p.1. |
| 社員 (Shain) | the personnel | noun | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD1 Nouns, p.1. |
| 増加 (Zōka) | an increase | noun | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD1 Nouns, p.1. |
| 論理 (Ronri) | the logic | noun | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD1 Nouns, p.1. |
| 人口 (Jinkō) | the population | noun | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD1 Nouns, p.1. |
| 領収書 (Ryōshūsho) | a receipt | noun | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD1 Nouns, p.1. |
| (専門)技師 ((Senmon) Gishi) | the technicians | noun | core | — | — | — | — | dictionary | n/a | verified | Parenthetical modifier is the source's own convention. Level 3, CD1 Nouns, p.1. |
| 化学製品 (Kagaku seihin) | the chemical | noun | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD1 Nouns, p.1. |
| 教科書 (Kyōka-sho) | the text book | noun | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD1 Nouns, p.1. |
| 方式 (Hōshiki) | the formula | noun | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD1 Nouns, p.1. |
| 記念碑 (Kinenhi) | a memorial (monument) | noun | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD1 Nouns, p.1. |
| 蛇口 (Jaguchi) | the faucet | noun | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD1 Nouns, p.1. |
| 施設 (Shisetsu) | the facilities (equipment) | noun | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD1 Nouns, p.1. |
| 競争相手 (Kyōsō aite) | the competitor | noun | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD1 Nouns, p.1. |
| 売春婦 (Baishunfu) | a prostitute | noun | core | — | — | — | — | dictionary | n/a | verified | Direct/clinical register term, not euphemistic slang — appears plainly in this list with no register annotation from the source itself; flagged here as a topically notable item for later taboo/register mechanics analysis, not reclassified as `taboo` tier absent source support. Level 3, CD1 Nouns, p.1. |
| 書類入れ (Shorui-ire) | the portfolio | noun | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD1 Nouns, p.1. |
| 行き先 (Yukisaki) | the destination | noun | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD1 Nouns, p.1. |
| 世論調査 (Yoron chōsa) | a survey | noun | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD1 Nouns, p.1. |
| 監察官 (Kansatsu-kan) | the censor | noun | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD1 Nouns, p.1. |
| 人格 (Jinkaku) | the personality | noun | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD1 Nouns, p.1. |
| 勝ち目のない者 (Kachime no nai mono) | an underdog | noun | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD1 Nouns, p.1. |

### Level 3 — Adjectives & Adverbs (p.16; English-first direction; note the scan-defect page at p.18 was skipped, see coverage note above)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 不都合な (Fu-tsugō na) | amiss | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD2 Adj/Adv, p.16. |
| 信じがたい (Shinji-gatai) | incredible (unusual) | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD2 Adj/Adv, p.16. |
| 軽薄な (Keihaku na) | frivolous | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD2 Adj/Adv, p.16. |
| 流行の (Ryūkō no) | fashionable | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD2 Adj/Adv, p.16. |
| 悲観的な (Hikan-teki na) | pessimistic | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD2 Adj/Adv, p.16. |
| 伝統的な (Dentō-teki na) | traditional | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD2 Adj/Adv, p.16. |
| 恥知らずの (Haji-shirazu no) | shameless | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD2 Adj/Adv, p.16. |
| 急進的な (Kyūshin-teki na) | radical (revolutionary) | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD2 Adj/Adv, p.16. |
| 妊娠している (Ninshin shite iru) | pregnant | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD2 Adj/Adv, p.16. |
| 法外な (Hōgai na) | outrageous | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD2 Adj/Adv, p.16. |
| 性不道徳の (Sei fu-dōtoku no) | promiscuous | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD2 Adj/Adv, p.16. |
| 頑固な (Ganko na) | headstrong, stubborn | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD2 Adj/Adv, p.16. |
| 不規則な (Fu-kisoku na) | irregular | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD2 Adj/Adv, p.16. |
| 嘆かわしい (Nagekawashii) | deplorable | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD2 Adj/Adv, p.16. |
| 献身的な (Kenshin-teki na) | dedicated (zealous) | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD2 Adj/Adv, p.16. |
| 奉献された (Hōken sareta) | hallowed (sanctified) | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD2 Adj/Adv, p.16. |
| 憂うつな (Yūutsu na) | melancholy | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD2 Adj/Adv, p.16. |
| 近づきやすい (Chika-zuki-yasui) | accessible | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD2 Adj/Adv, p.16. |
| 黙想している (Mokusō shite iru) | pensive | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD2 Adj/Adv, p.16. |
| 理解できる (Rikai dekiru) | understandable | adjective | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD2 Adj/Adv, p.16. |

### Level 3 — Expressions (p.33; Japanese-first direction)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| まっすぐ行けばそう遠くない。(Massugu ikeba sō tōku nai.) | not far, as the crow flies | expression | literary | — | — | — | — | dictionary | n/a | verified | Idiom gloss (English idiom supplied for the Japanese, per the source's own idiom-matching convention). Level 3, CD3 Expressions, p.33. |
| 彼女は悲嘆した。(Kanojo wa hitan shita.) | she was heartbroken | expression | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD3 Expressions, p.33. |
| それを提案するのはばかばかしい。(Sore o teian suru no wa bakabakashii.) | that's silly to suggest | expression | colloquial | — | — | — | — | dictionary | n/a | verified | Level 3, CD3 Expressions, p.33. |
| 彼等は私たちを尾行しようとした。(Karera wa watashi-tachi o bikō shiyō to shita.) | they tried to spy on us | expression | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD3 Expressions, p.33. |
| 配達人はけっして時間通りに来ない。(Haitatsu-nin wa kesshite jikan-dōri ni konai.) | the delivery man is never on time | expression | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD3 Expressions, p.33. |
| 我々は用心深くなった。(Wareware wa yōjinbukaku natta.) | we became wary | expression | literary | — | — | — | — | dictionary | n/a | verified | "我々" (wareware) is a more formal/literary first-person-plural pronoun than the colloquial 私たち seen elsewhere in this same page's entries. Level 3, CD3 Expressions, p.33. |
| 生まれた時からの孤児。(Umareta toki kara no koji.) | an orphan since birth | expression | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD3 Expressions, p.33. |
| さあ、想像してみて。(Sā, sōzō shite mite!) | well, fancy that! | expression | colloquial | — | — | — | — | dictionary | n/a | verified | Level 3, CD3 Expressions, p.33. |
| 綴りの試験はとても難しい。(Tsuzuri no shiken wa totemo muzukashii.) | the spelling test is quite difficult | expression | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD3 Expressions, p.33. |
| 彼女は皆に愛された。(Kanojo wa mina ni ai-sareta.) | she was beloved by all | expression | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD3 Expressions, p.33. |
| 一日ずつ。(Ichinichi zutsu.) | one day at a time | expression | colloquial | — | — | — | — | dictionary | n/a | verified | Level 3, CD3 Expressions, p.33. |

### Level 3 — Verbs (p.42; English-first direction)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 割り当てる (Wari-ateru) | to apportion | verb | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD4 Verbs, p.42. |
| そらす (Sorasu) | to deflect | verb | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD4 Verbs, p.42. |
| しいたげる (Shiitageru) | to oppress (subjugate) | verb | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD4 Verbs, p.42. |
| 間違える (Machigaeru) | to err (be wrong) | verb | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD4 Verbs, p.42. |
| 否定する (Hitei suru) | to deny | verb | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD4 Verbs, p.42. |
| 描く (Egaku) | to illustrate | verb | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD4 Verbs, p.42. |
| 陳列する (Chinretsu suru) | to display | verb | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD4 Verbs, p.42. |
| ひっぱたく (Hippataku) | to spank | verb | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD4 Verbs, p.42. |
| 正当化する (Seitō-ka suru) | to justify | verb | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD4 Verbs, p.42. |
| 生き延びる (Iki-nobiru) | to survive | verb | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD4 Verbs, p.42. |
| 犯す (Okasu) | to rape | verb | core | — | — | — | — | dictionary | n/a | verified | Plain/clinical verb listed with no register annotation (犯す more broadly covers "to violate/commit (a crime)"; this specific sense-gloss "to rape" is the source's own choice) — flagged as a topically notable item for taboo/register mechanics analysis, not reclassified as `taboo` tier absent source support. Level 3, CD4 Verbs, p.42. |
| 取り乱す (Tori-midasu) | to upset (disturb) | verb | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD4 Verbs, p.42. |
| 放棄する (Hōki suru) | to renounce | verb | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD4 Verbs, p.42. |
| 屈辱を与える (Kutsujoku o ataeru) | to degrade | verb phrase | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD4 Verbs, p.42. |
| 消える (Kieru) | to vanish | verb | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD4 Verbs, p.42. |
| 模索する (Mosaku suru) | to grope | verb | core | — | — | — | — | dictionary | n/a | verified | Gloss sense is figurative ("to grope/fumble for," e.g. a solution), not physical contact — note to avoid conflating with the unrelated physical-contact sense in English. Level 3, CD4 Verbs, p.42. |
| 爆発する (Bakuhatsu suru) | to explode | verb | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD4 Verbs, p.42. |
| 値下げる (Ne-sageru) | to mark down (reduce) | verb | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD4 Verbs, p.42. |
| 美化する (Bika suru) | to beautify, to embellish | verb | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD4 Verbs, p.42. |
| 曲芸をする (Kyokugei o suru) | to juggle | verb phrase | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD4 Verbs, p.42. |
| 移住する (Ijū suru) | to immigrate | verb | core | — | — | — | — | dictionary | n/a | verified | Level 3, CD4 Verbs, p.42. |

---

## Grammar points

This source carries no grammar explanation of its own beyond the one-page "Notes About the
Vocabulary Lists" format legend (paraphrased throughout the coverage note and per-row Notes above:
parenthetical sense-disambiguation, synonym-pairing, Level 1's definite-article-only vs. Levels 2-3's
definite+indefinite convention, and the idiom-matching rule for the Expressions sections). There is
no paradigm table, conjugation drill, or syntax discussion to extract as a distinct grammar point —
this is a pure vocabulary-drill flashcard series, consistent with its stated non-grammar purpose
("VOCABULEARN...is not, however, meant to be a course in grammatical structure").

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`.
