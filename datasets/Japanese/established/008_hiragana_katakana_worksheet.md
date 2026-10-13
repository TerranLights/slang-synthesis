# Japanese — Established Vocabulary/Grammar: Hiragana & Katakana Worksheet (full 29-page worksheet + answer key)

**Source:** Meguro Language Center, *HIRAGANA and KATAKANA Work Sheets* (Dec. 2005 edition, 29 pp.),
cross-read with its paired *Hiragana Katakana Worksheet (Answers)* (29 pp., same publisher/edition).
Both files have a clean, genuine PDF text layer (confirmed via `pdftotext -layout`) — no vision-
reading was needed for any entry in this file.

**Coverage note:** This is a single, self-contained worksheet booklet, not a chapter excerpted from
a larger grammar — the whole 29-page document is covered in one file per the chunking rule's
"don't split a bounded chunk unnecessarily" guidance, since the real content (46 kana + dakuten/
handakuten + yōon + foreign-sound extensions + ~140 distinct quiz vocabulary items + the writing
rules) is cohesive and not sprawling once stroke-order drill repetition is skipped. Per the coverage
rule, the repeated stroke-order tracing cells (each kana is drawn 5-10 times per worksheet page) are
skipped entirely as pure handwriting-practice padding with zero new information; every *distinct*
quiz word, example sentence vocabulary item, rule-illustration example, and the full kana inventory
itself are captured below. The answer key supplies the actual correct kana forms for every
romaji-only quiz prompt in the worksheet file — entries below combine both files (kana form from the
answer key, English gloss from the worksheet's own parenthetical or its answer-matching column).

**Extraction gotcha found and corrected:** the answer key's rendering of the Hiragana double-
consonant quiz row for *ippon* ("one long object") read as じゅっぽん, which cannot correspond to the
romaji "ippon" (that pronunciation would be "juppon") — almost certainly a `pdftotext`-layout column
bleed from the adjacent *juppun* row above it (both rows are in the same cramped two-column quiz
box). Cross-checking against the double-consonant rule's own pattern (small っ doubling the initial
consonant of the following mora: i-ppon, not ju-ppon) and against how every other small-っ item in
the same quiz resolves, the correct form is **いっぽん**, which is what's recorded in the table below;
the raw じゅっぽん misread is flagged here rather than silently reproduced. The Country/Capital
reference table (pp. 26-27) renders its Romaji column in full-width Unicode Latin characters (e.g.
"Ｉｒａｋｕ") due to a PDF font quirk — these are normalized to ordinary half-width romaji below with
no change in content.

---

## Grammar points

### The kana inventory (p. 1 chart)

The worksheet's own opening page is a full gojūon (50-sound) chart cross-referencing Romaji,
Hiragana, and Katakana side by side, organized by consonant row (a-, ka-, sa-, ta-, na-, ha-, ma-,
ya-, ra-, wa- + the single moraic nasal ん/ン) and vowel column (a/i/u/e/o). It also includes the
five voiced (dakuten, ゛) rows — ga/za/da/ba — and the semi-voiced (handakuten, ゜) pa-row, plus the
contracted yōon sounds (きゃ/きゅ/きょ etc., formed by combining an i-row kana with a small ゃ/ゅ/ょ).
A final block lists katakana-only extended combinations used specifically to represent foreign-
language sounds absent from native Japanese phonology (シェ she, チェ che, ジェ je, ツァ/ツェ/ツォ tsa/
tse/tso, ファ/フィ/フェ/フォ fa/fi/fe/fo, ティ/ディ/デュ ti/di/dyu, ウィ/ウェ/ウォ wi/we/wo, クォ quo,
ヴァ/ヴィ/ヴェ/ヴォ va/vi/ve/vo). This extended set is the clearest structural evidence that katakana
functions as Japanese's loanword-adaptation script: it was expanded specifically to notate sounds
(f-, v-, ti/di, w-initial beyond wa) that the native 50-sound system has no symbol for.

### Why two scripts for the same sounds

The worksheet states katakana's functional domain directly (p. 11): (1) words of foreign origin,
(2) onomatopoeia (e.g. ワンワン *wanwan*, a dog's bark), (3) names of some animals/insects, and (4)
emphasis of a word that would otherwise be written in hiragana or kanji (its own example: それは
ダメです "that's no good" — ダメ written in katakana lands with more force than だめ would). This
functional split is a load-bearing fact for the slang project: deliberately switching a native,
ordinary word into katakana is itself a register move (emphasis/jarring/toughness), independent of
word choice — a mechanism not available in any single-script language the project has extracted so
far.

### Hiragana rule 1 — long vowels

Each vowel's length is marked differently depending on which vowel it follows, and the convention is
partly etymological rather than purely phonetic:
- Long **a** → add あ (おかあさん *okāsan* "mother"; まあまあ *māmā* "so-so")
- Long **i** → add い (おにいさん *oniisan* "older brother"; おじいさん *ojiisan* "grandfather")
- Long **u** → add う (ゆうがた *yūgata* "early evening"; くうき *kūki* "air"; たいふう *taifū*
  "typhoon")
- Long **e** → add え, but *only* in native-Japanese-origin words (おねえさん *onēsan* "older
  sister"); in words of Chinese origin the sequence is written えい instead (えいご *Eigo* "English";
  せんせい *sensei* "teacher"; がくせい *gakusei* "student")
- Long **o** → add う in the ordinary case (さようなら *sayōnara*; びょういん *byōin* "hospital";
  きょう *kyō* "today"), but a small set of words traditionally spell it おお instead (おおきい *ōkii*
  "big"; とお *tō* "ten"; とおり *tōri* "street") — the worksheet flags this as an irregular/
  traditional spelling, not predictable from pronunciation alone.

### Hiragana rule 2 — double consonants (small っ)

Geminate consonants (kk, pp, ss, tt) are marked by inserting a small っ before the consonant being
doubled; it represents a one-beat pause where the mouth holds the next consonant's shape before
releasing it (がっこう *gakkō* "school"; きっぷ *kippu* "ticket"; ざっし *zasshi* "magazine").

### Hiragana rule 3 — ji/zu spelling split (じ/ず vs. ぢ/づ)

The sounds *ji* and *zu* are usually written じ and ず, but a small, traditionally-fixed set of words
write them ぢ and づ instead (ちず *chizu* "map" uses ず; みず *mizu* "water" uses ず; but historical/
compound-internal cases like はなぢ "nosebleed" use ぢ) — the worksheet frames this as a closed,
memorize-by-item exception list rather than a rule with a productive condition.

### Hiragana rules 4-6 — particle spelling fossils (は/を/へ)

Three grammatical particles are pronounced *wa*, *o*, and *e* respectively but are **not** spelled
with the hiragana that match those sounds elsewhere in the syllabary:
- The topic particle *wa* is written は (the regular syllabic value of は is *ha*).
- The direct-object particle *o* is written を (を is otherwise unused in modern orthography outside
  this one grammatical function — the worksheet separately notes katakana ヲ "is not used in modern
  living" at all).
- The directional particle *e* is written へ (the regular syllabic value of へ is *he*).

These are historical spelling fossils preserved specifically for grammatical particles, while the
same sounds elsewhere in ordinary vocabulary use their expected kana. This is a clean example of
orthography encoding grammatical category independent of pronunciation.

### Katakana rule 1 — long vowels use a dash, not a doubled vowel kana

Where hiragana marks vowel length by adding a vowel kana, katakana marks it with a single dash glyph
"ー" regardless of which vowel is lengthened (コーヒー *kōhī* "coffee"; パーティー *pātī* "party").

### Katakana rule 2 — double consonants use small ッ

Same mechanism as hiragana's small っ, just the katakana form (ベッド-style geminates; worksheet's own
examples are the gemination inside loanwords like スイッチ *suicchi* "switch").

### Shape-confusion pairs flagged by the source itself

The worksheet explicitly calls out kana pairs that beginning learners commonly confuse by shape, with
a mnemonic device for two of them:
- Hiragana し (*shi*) / つ (*tsu*) vs. their katakana counterparts シ / ツ — the source gives a visual
  side-by-side memory aid pairing each hiragana with its katakana look-alike.
- Katakana ソ (*so*) / ン (*n*) vs. hiragana そ / ん — same side-by-side aid.
- A dedicated "similar characters" quiz drills easily-confused shapes within each script: hiragana
  あ/お, き/さ, ち/ら, た/な, め/ぬ, い/り, ま/も, る/ろ, け/は/ほ, わ/れ/ね; katakana シ/ツ, ン/ソ, ク/
  タ, マ/ア, ヌ/ス, サ/ナ/メ, フ/ウ/ワ, ヒ/エ/ニ/ミ.

---

## Vocabulary

*Usage Tier is `core` for every entry unless otherwise noted — this is an absolute-beginner literacy
worksheet, not a register-differentiated source. Attested Era is "contemporary (source published
Dec. 2005)" for all entries per the spec's whole-book-date convention. Source Type is
`grammar_reference` throughout (a pedagogical kana-literacy worksheet). Transcription Confidence is
`n/a` (not a subtitle/transcript source); Vision Reading Confidence is `n/a` throughout (clean text
layer, no vision-reading needed).*

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| あか (aka) | red | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.2 a-row quiz |
| あお (ao) | blue | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.2 a-row quiz |
| あき (aki) | autumn | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.2 a-row quiz |
| えき (eki) | station | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.2 a-row quiz |
| いか (ika) | squid | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.2 a-row quiz |
| かお (kao) | face | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.2 a-row quiz |
| いけ (ike) | pond | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.2 a-row quiz |
| こえ (koe) | voice | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.2 a-row quiz |
| いえ (ie) | house | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.2 a-row quiz |
| かき (kaki) | persimmon | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.2 a-row quiz |
| おおきい (ōkii) | big | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.2; illustrates the おお long-o exception |
| うえ (ue) | on top/above | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.2 a-row quiz |
| あさ (asa) | morning | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.3 s-row quiz |
| すし (sushi) | sushi | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.3 s-row quiz |
| しお (shio) | salt | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.3 s-row quiz |
| せき (seki) | cough | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.3 s-row quiz |
| さけ (sake) | rice wine | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.3 s-row quiz |
| あせ (ase) | sweat | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.3 s-row quiz |
| あした (ashita) | tomorrow | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.3 t-row quiz |
| ちかてつ (chikatetsu) | subway | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.3 t-row quiz |
| けいさつ (keisatsu) | police | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.3 t-row quiz |
| とけい (tokei) | watch/clock | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.3 t-row quiz |
| くつ (kutsu) | shoes | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.3 t-row quiz |
| たこ (tako) | octopus | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.3 t-row quiz |
| このねこ (kono neko) | this cat | noun phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.4 n-row quiz |
| あのさかな (ano sakana) | that fish | noun phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.4 n-row quiz |
| なに (nani) | what | pronoun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.4 n-row quiz |
| あなた (anata) | you | pronoun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.4 n-row quiz |
| いぬ (inu) | dog | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.4 n-row quiz |
| にく (niku) | meat | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.4 n-row quiz |
| ふく (fuku) | clothes | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.4 h-row quiz |
| ひと (hito) | person/people | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.4 h-row quiz |
| へそ (heso) | navel | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.4 h-row quiz |
| はこ (hako) | box | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.4 h-row quiz |
| ほし (hoshi) | star | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.4 h-row quiz |
| ふね (fune) | ship | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.4 h-row quiz; は-row quiz also notes は=wa particle, へ=e particle spelling fossils |
| あめ (ame) | rain | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.5 m-row quiz |
| めいし (meishi) | business card | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.5 m-row quiz |
| みそ (miso) | miso | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.5 m-row quiz |
| むし (mushi) | insect | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.5 m-row quiz |
| なまえ (namae) | name | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.5 m-row quiz |
| もしもし (moshi moshi) | "hello" (phone greeting) | interjection | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.5 m-row quiz |
| やすみ (yasumi) | day off/rest | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.5 y-row quiz |
| ふゆ (fuyu) | winter | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.5 y-row quiz |
| ゆき (yuki) | snow | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.5 y-row quiz |
| やきにく (yakiniku) | grilled meat | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.5 y-row quiz |
| ゆうめい (yūmei) | famous | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.5; illustrates long-u-via-う rule |
| おはよう (ohayō) | good morning | interjection | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.5; illustrates long-o-via-う rule |
| くうこう (kūkō) | airport | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.5 |
| ようふく (yōfuku) | Western clothes | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.5 |
| きのう (kinō) | yesterday | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.5 |
| こうこう (kōkō) | high school | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.5 |
| これ (kore) | this (thing) | pronoun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.6 r/w/n quiz |
| それ (sore) | that (thing) | pronoun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.6 r/w/n quiz |
| さようなら (sayōnara) | goodbye | interjection | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.6 r/w/n quiz |
| はる (haru) | spring (season) | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.6 r/w/n quiz |
| よる (yoru) | night | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.6 r/w/n quiz |
| くるま (kuruma) | car | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.6 r/w/n quiz |
| やきとり (yakitori) | grilled chicken skewer | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.6 r/w/n quiz |
| ろうそく (rōsoku) | candle | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.6 r/w/n quiz |
| わたし (watashi) | I/me | pronoun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.6 r/w/n quiz |
| みかん (mikan) | tangerine | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.6 r/w/n quiz |
| すみません (sumimasen) | sorry/excuse me | interjection | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.6 r/w/n quiz |
| せんたく (sentaku) | laundry | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.6 r/w/n quiz |
| まど (mado) | window | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.7 dakuten quiz |
| まだ (mada) | not yet | adverb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.7 dakuten quiz |
| すごいですね！ (Sugoi desune!) | "Great!"/"That's amazing!" | interjection | colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.7 dakuten quiz |
| どうぞよろしく (Dōzo yoroshiku) | "Pleased to meet you" (fixed social phrase) | phrase | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.7 dakuten quiz |
| ありがとうございます (Arigatō gozaimasu) | "Thank you" (polite) | phrase | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.7 dakuten quiz |
| はじめまして (Hajimemashite) | "How do you do"/first-meeting greeting | phrase | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.7 dakuten quiz |
| でんわ (denwa) | telephone | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.7 dakuten quiz |
| こんばんは (Komban wa) | good evening | phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.7; the は here is the same particle-spelling fossil as the topic particle |
| しんぶん (shimbun) | newspaper | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.7 dakuten quiz |
| ともだち (tomodachi) | friend | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.7 dakuten quiz |
| ぎんざ (Ginza) | Ginza (Tokyo district) | proper noun | core | — | contemporary (2005) | Tokyo | local | grammar_reference | n/a | n/a | p.7 dakuten quiz |
| ぎんこう (ginkō) | bank | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.7 dakuten quiz |
| おめでとうございます (Omedetō gozaimasu) | "Congratulations" (polite) | phrase | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.7 dakuten quiz |
| かんぱい (Kanpai!) | "Cheers!" | interjection | colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.7 dakuten quiz |
| とうきょう (Tōkyō) | Tokyo | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p.8 yōon quiz |
| じゅうしょ (jūsho) | address | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.8 yōon quiz |
| かいしゃ (kaisha) | company | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.8 yōon quiz |
| じゃまた (Ja mata) | "See you again" | phrase | colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.8 yōon quiz |
| かのじょ (kanojo) | she/her (also "girlfriend" colloquially) | pronoun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.8 yōon quiz |
| きゅうりょう (kyūryō) | salary | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.8 yōon quiz |
| おきゃくさん (okyakusan) | guest/customer | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.8 yōon quiz |
| しんじゅく (Shinjuku) | Shinjuku (Tokyo district) | proper noun | core | — | contemporary (2005) | Tokyo | local | grammar_reference | n/a | n/a | p.8 yōon quiz |
| しゅうまつ (shūmatsu) | weekend | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.8 yōon quiz |
| しゃしん (shashin) | photo | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.8 yōon quiz |
| さんびゃくえん (sanbyakuen) | 300 yen | numeral phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.8; illustrates hyaku's voiced/unvoiced counter-shift (ひゃく→びゃく) |
| ちゅうかりょうり (chūkaryōri) | Chinese food | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.8 yōon quiz |
| しゅくだい (shukudai) | homework | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.8 yōon quiz |
| ごひゃくえん (gohyakuen) | 500 yen | numeral phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.8 yōon quiz |
| いっぽん (ippon) | one (long, cylindrical object) — counter | numeral/counter | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.9 rule-illustration; **corrected from source's apparent じゅっぽん misprint/extraction artifact — see opening note** |
| いっぴき (ippiki) | one (small animal) — counter | numeral/counter | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.9 rule-illustration |
| じゅっぷん (juppun) | 10 minutes | numeral phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.9 rule-illustration |
| きっぷ (kippu) | ticket | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.9 rule-illustration |
| ざっし (zasshi) | magazine | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.9 rule-illustration |
| いっさつ (issatsu) | one (bound volume) — counter | numeral/counter | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.9 rule-illustration |
| いらっしゃいませ (Irasshaimase) | "Welcome" (shopkeeper's greeting) | phrase | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.10 rule-illustration |
| きって (kitte) | postage stamp | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.10 rule-illustration |
| いってらっしゃい (Itte rasshai) | "See you off" (said to someone leaving) | phrase | colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.10 rule-illustration |
| ちょっとまってください (Chotto matte kudasai) | "Please wait a moment" | phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.10 rule-illustration |
| がんばってください (Ganbatte kudasai) | "Please do your best"/"Good luck" | phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.10 rule-illustration |
| さんじ (sanji) | 3:00 | numeral phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.10; illustrates じ (not ぢ) spelling |
| じしょ (jisho) | dictionary | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.10 rule-illustration |
| ちず (chizu) | map | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.10; illustrates ず (not づ) spelling |
| みず (mizu) | water | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.10 rule-illustration |
| ゆうびんきょく (yūbinkyoku) | post office | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.11 review quiz sentence 1 |
| としょかん (toshokan) | library | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.11 review quiz sentence 2 |
| べんきょうします (benkyō shimasu) | to study (polite, non-past) | verb phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.11 review quiz sentence 2 |
| こうちゃ (kōcha) | black tea | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.11 review quiz sentence 4 |
| かさ (kasa) | umbrella | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.11 review quiz sentence 5 |
| せんしゅう (senshū) | last week | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.11 review quiz sentence 6 |
| でんわばんごう (denwa bangō) | telephone number | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.11 review quiz sentence 6 |
| クッキー (kukkī) | cookie | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.13 katakana k-row quiz |
| キック (kikku) | kick | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.13 katakana k-row quiz |
| コーク (kōku) | Coke | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.13 katakana k-row quiz |
| コケッコッコー (kokekokkō) | cock-a-doodle-doo | interjection (onomatopoeia) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.13; katakana's onomatopoeia function |
| ケーキ (kēki) | cake | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.13 katakana k-row quiz |
| スキー (sukī) | ski/skiing | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.14 katakana s-row quiz |
| ケース (kēsu) | case | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.14 katakana s-row quiz |
| ガス (gasu) | gas | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.14 katakana s-row quiz |
| ソース (sōsu) | sauce | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.14 katakana s-row quiz |
| ソーセージ (sōsēji) | sausage | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.14 katakana s-row quiz |
| ウイスキー (uisukī) | whisky | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.14 katakana s-row quiz |
| コース (kōsu) | course | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.14 katakana s-row quiz |
| テキスト (tekisuto) | textbook | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.15 katakana t-row quiz |
| チーズ (chīzu) | cheese | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.15 katakana t-row quiz |
| タクシー (takushī) | taxi | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.15/22 — appears in both the t-row quiz and QUIZ 2 |
| ドア (doa) | door | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.15 katakana t-row quiz |
| ステーキ (sutēki) | steak | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.15/21 |
| デザート (dezāto) | dessert | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.15 katakana t-row quiz |
| テニス (tenisu) | tennis | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.16 katakana n-row quiz |
| ノート (nōto) | notebook | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.16 katakana n-row quiz |
| ネクタイ (nekutai) | necktie | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.16/24 |
| スピード (supīdo) | speed | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.17 katakana h-row quiz |
| ヒーター (hītā) | heater | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.17/24 |
| パスタ (pasuta) | pasta | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.17 katakana h-row quiz |
| バス (basu) | bus | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.17 katakana h-row quiz |
| ハム (hamu) | ham | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.18 katakana m-row quiz |
| モーター (mōtā) | motor | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.18 katakana m-row quiz |
| メモ (memo) | memo | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.18 katakana m-row quiz |
| メッセージ (messēji) | message | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.18 katakana m-row quiz |
| ガム (gamu) | gum | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.18 katakana m-row quiz |
| ヨット (yotto) | yacht | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.18 katakana y-row quiz |
| ユーザー (yūzā) | user | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.18 katakana y-row quiz |
| メニュー (menyū) | menu | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.21 QUIZ 1 |
| コーンスープ (kōnsūpu) | corn soup | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.21 QUIZ 1 |
| サラダ (sarada) | salad | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.21/25 |
| ビール (bīru) | beer | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.21 QUIZ 1 |
| ワイン (wain) | wine | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.21 QUIZ 1 |
| スパゲッティー (supagettī) | spaghetti | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.21 QUIZ 1 |
| ハンバーグセット (hanbāgu setto) | Hamburg steak set (meal) | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.21 QUIZ 1 |
| ビーフシチュー (bīfu shichū) | beef stew | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.21 QUIZ 1 |
| ピザ (piza) | pizza | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.21 QUIZ 1 |
| ライス (raisu) | rice (plated Western-style) | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.21; distinct loanword from native ごはん, used specifically for Western-plated rice |
| パン (pan) | bread | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.21 QUIZ 1 |
| サンドイッチ (sandoicchi) | sandwich | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.21 QUIZ 1 |
| チョコレートケーキ (chokorēto kēki) | chocolate cake | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.21 QUIZ 1 |
| アイスクリーム (aisukurīmu) | ice cream | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.21 QUIZ 1 |
| レモンティー (remontī) | lemon tea | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.21 QUIZ 1 |
| アイスコーヒー (aisukōhī) | iced coffee | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.21 QUIZ 1 |
| エレベーター (erebētā) | elevator | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.22 QUIZ 2 |
| エスカレーター (esukarētā) | escalator | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.22 QUIZ 2 |
| トイレ (toire) | toilet | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.22 QUIZ 2 |
| インフォメーション (infomēshon) | information (desk/booth) | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.22 QUIZ 2 |
| パーキング (pākingu) | parking | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.22 QUIZ 2 |
| マクドナルド (makudonarudo) | McDonald's | proper noun (loanword) | core | — | contemporary (2005) | — | transnational | grammar_reference | n/a | n/a | p.22 QUIZ 2 |
| レストラン (resutoran) | restaurant | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.22 QUIZ 2 |
| カラオケ (karaoke) | karaoke | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.22 QUIZ 2 |
| セブンイレブン (sebun irebun) | 7-Eleven | proper noun (loanword) | core | — | contemporary (2005) | — | transnational | grammar_reference | n/a | n/a | p.22 QUIZ 2 |
| ゲームセンター (gēmu sentā) | arcade/game center | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.22 QUIZ 2 |
| スポーツクラブ (supōtsu kurabu) | sports club/gym | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.22 QUIZ 2 |
| デパート (depāto) | department store | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.22 QUIZ 2 |
| レンタルビデオ (rentaru bideo) | video rental (shop) | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.22 QUIZ 2 |
| ディズニーランド (dizunīrando) | Disneyland | proper noun (loanword) | core | — | contemporary (2005) | — | transnational | grammar_reference | n/a | n/a | p.22 QUIZ 2 |
| ホテル (hoteru) | hotel | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.22 QUIZ 2 |
| コンビニ (konbini) | convenience store | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.22 QUIZ 2; clipped from コンビニエンスストア *konbiniensu sutoa* — note for synthesis: this is a native-Japanese clipping mechanism applied to a loanword |
| ファッション (fasshon) | fashion | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.23 QUIZ 3 |
| パーティー (pātī) | party | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.23/25 |
| コンサート (konsāto) | concert | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.23/25 |
| デート (dēto) | date (romantic) | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.23 QUIZ 3 |
| ゴルフ (gorufu) | golf | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.23 QUIZ 3 |
| バスケットボール (basukettobōru) | basketball | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.23 QUIZ 3 |
| ビデオカメラ (bideo kamera) | video camera | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.23 QUIZ 3 |
| ビタミンＣ (bitamin C) | vitamin C | noun (loanword) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.23 QUIZ 3 |
| スケジュール (sukejūru) | schedule | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.23 QUIZ 3 |
| キャンセル (kyanseru) | cancel | noun/verb (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.23 QUIZ 3 |
| コンピューター (konpyūtā) | computer | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.23/25 |
| システム (shisutemu) | system | noun (loanword) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.23 QUIZ 3 |
| データ (dēta) | data | noun (loanword) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.23 QUIZ 3 |
| ファックス (fakkusu) | fax | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.23 QUIZ 3 |
| Ｅメール (Ī-mēru) | email | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.23 QUIZ 3 |
| メーカー (mēkā) | maker/manufacturer | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.23 QUIZ 3 |
| ディスカウント (disukaunto) | discount | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.23 QUIZ 3 |
| グラス (gurasu) | glass (drinking) | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.24 QUIZ 4 |
| フォーク (fōku) | fork | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.24 QUIZ 4 |
| ウォークマン (wōkuman) | Walkman | proper noun (loanword) | core | — | contemporary (2005) | — | transnational | grammar_reference | n/a | n/a | p.24 QUIZ 4 |
| エアコン (eakon) | air conditioner | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.24 QUIZ 4; clipped from エアコンディショナー, a loanword-clipping parallel to コンビニ |
| ファイル (fairu) | file | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.24 QUIZ 4 |
| フロッピーディスク (furoppī disuku) | floppy disk | noun (loanword) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.24 QUIZ 4 |
| カーペット (kāpetto) | carpet | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.24 QUIZ 4 |
| オレンジジュース (orenji jūsu) | orange juice | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.24 QUIZ 4 |
| テレビ (terebi) | television | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.24 QUIZ 4; clipped from テレビジョン *terebijon* |
| セーター (sētā) | sweater | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.24 QUIZ 4 |
| ズボン (zubon) | trousers | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.24 QUIZ 4; from French "jupon," not English |
| ソファー (sofā) | sofa | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.24 QUIZ 4 |
| ワイシャツ (waishatsu) | dress shirt | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.24 QUIZ 4; from English "white shirt," reanalyzed as ワイ+シャツ |
| デジタルカメラ (dejitaru kamera) | digital camera | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.25 QUIZ 5 sentence 2 |
| イギリスじん (Igirisu-jin) | British person | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.25 QUIZ 5 sentence 3; -じん "person-of-X-country" suffix on a katakana country name |
| パイナップル (painappuru) | pineapple | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.25 QUIZ 5 sentence 4 |
| ガールフレンド (gārufurendo) | girlfriend | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.25 QUIZ 5 sentence 5 |
| ろっぽんぎ (Roppongi) | Roppongi (Tokyo district) | proper noun | core | — | contemporary (2005) | Tokyo | local | grammar_reference | n/a | n/a | p.25 QUIZ 5 sentence 5 |
| チケット (chiketto) | ticket (event) | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.25 QUIZ 5 sentence 7 |
| ボルボ (Borubo) | Volvo | proper noun (loanword) | core | — | contemporary (2005) | — | transnational | grammar_reference | n/a | n/a | p.25 QUIZ 5 sentence 8 |
| スウェーデン (Suwēden) | Sweden | proper noun (loanword) | core | — | contemporary (2005) | — | transnational | grammar_reference | n/a | n/a | p.25 QUIZ 5 sentence 8; also appears p.26 country list |
| ケンタッキーフライドチキン (Kentakkī Furaido Chikin) | Kentucky Fried Chicken | proper noun (loanword) | core | — | contemporary (2005) | — | transnational | grammar_reference | n/a | n/a | p.25 QUIZ 5 sentence 9 |
| ハンバーガー (hanbāgā) | hamburger | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.25 QUIZ 5 sentence 10; distinct from ハンバーグ "Hamburg steak" (p.21) — a minimal-pair loanword distinction |
| フライドポテト (furaido poteto) | French fries | noun (loanword) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p.25 QUIZ 5 sentence 10 |

### Country/capital reference list (pp. 26-27) — proper nouns in katakana (and 2 native hiragana exceptions)

This closing reference table pairs each country/capital's katakana rendering with its English name;
two culturally-proximate Asian names (China, North/South Korea) are written in **hiragana**, not
katakana, breaking the "foreign name → katakana" pattern that holds for every other entry — worth
flagging as a real exception, not a transcription error (confirmed identically in both the worksheet
and its answer key). Recorded compactly as one table (Usage Tier `core`, Part of Speech "proper noun
(place)" for all, other columns identical to above, omitted per row for space):

| Katakana/Hiragana | Romaji | English |
|---|---|---|
| イラク | Iraku | Iraq |
| バグダッド | Bagudaddo | Baghdad |
| イラン | Iran | Iran |
| テヘラン | Teheran | Tehran |
| インド | Indo | India |
| ニューデリー | Nyūderī | New Delhi |
| インドネシア | Indoneshia | Indonesia |
| ジャカルタ | Jakaruta | Jakarta |
| タイ | Tai | Thailand |
| バンコク | Bankoku | Bangkok |
| ちゅうごく (hiragana, not katakana) | Chūgoku | China |
| ペキン | Pekin | Beijing |
| きたちょうせん (hiragana, not katakana) | Kitachōsen | North Korea |
| ピョンヤン | Pyonyan | Pyongyang |
| かんこく (hiragana, not katakana) | Kankoku | (South) Korea |
| ソウル | Sōru | Seoul |
| フィリピン | Firipin | the Philippines |
| マニラ | Manira | Manila |
| ベトナム | Betonamu | Vietnam |
| ハノイ | Hanoi | Hanoi |
| マレーシア | Marēshia | Malaysia |
| クアラルンプール | Kuararunpūru | Kuala Lumpur |
| アイルランド | Airurando | Ireland |
| ダブリン | Daburin | Dublin |
| イギリス | Igirisu | UK |
| ロンドン | Rondon | London |
| イタリア | Itaria | Italy |
| ローマ | Rōma | Rome |
| オーストリア | Ōsutoria | Austria |
| ウィーン | Wīn | Vienna |
| オランダ | Oranda | Holland |
| アムステルダム | Amusuterudamu | Amsterdam |
| ギリシャ | Girisha | Greece |
| アテネ | Atene | Athens |
| スイス | Suisu | Switzerland |
| べルン | Berun | Bern |
| スウェーデン | Suwēden | Sweden |
| ストックホルム | Sutokkuhorumu | Stockholm |
| スペイン | Supein | Spain |
| マドリード/マドリッド | Madorido/Madoriddo | Madrid |
| デンマーク | Denmāku | Denmark |
| コペンハーゲン | Kopenhāgen | Copenhagen |
| ドイツ | Doitsu | Germany |
| ベルリン | Berurin | Berlin |
| ハンガリー | Hangarī | Hungary |
| ブタペスト | Butapesuto | Budapest |
| フィンランド | Finrando | Finland |
| ヘルシンキ | Herushinki | Helsinki |
| フランス | Furansu | France |
| パリ | Pari | Paris |
| ベルギー | Berugī | Belgium |
| ブリュッセル | Buryusseru | Brussels |
| ポーランド | Pōrando | Poland |
| ワルシャワ | Warushawa | Warsaw |
| ポルトガル | Porutogaru | Portugal |
| リスボン | Risubon | Lisbon |
| アメリカ | Amerika | America |
| ワシントン | Washinton | Washington |
| カナダ | Kanada | Canada |
| オタワ | Otawa | Ottawa |
| メキシコ | Mekishiko | Mexico |
| メキシコシティー | Mekishiko Shitī | Mexico City |
| ブラジル | Burajiru | Brazil |
| ブラジリア | Burajiria | Brasília |
| エジプト | Ejiputo | Egypt |
| カイロ | Kairo | Cairo |
| みなみアフリカ (mixed hiragana+katakana) | Minami-afurika | South Africa |
| プレトリア | Puretoria | Pretoria |
| オーストラリア | Ōsutoraria | Australia |
| キャンベラ | Kyanbera | Canberra |
| ニュージーランド | Nyūjīrando | New Zealand |
| ウェリントン | Werinton | Wellington |
| ロシア | Roshia | Russia |
| モスクワ | Mosukuwa | Moscow |

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`. Grammar explanations
above are paraphrased in this file's own words; the handful of example words/sentences quoted from
the source are short, individually-attributed illustrations of a stated rule, consistent with the
spec's "selective quotes" allowance, not bulk reproduction of the worksheet's pages.
