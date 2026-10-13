# Japanese — Established Vocabulary/Grammar: A Guide to Learning Hiragana and Katakana (full book)

**Source:** Kenneth G. Henshall with Tetsuo Takagaki, *A Guide to Learning Hiragana and Katakana*
(Charles E. Tuttle Company, 1st ed. 1990, 6th printing 1997), all 119 PDF pages (printed pp. 1–120;
printed page = PDF page + 1 throughout, verified empirically against the printed running head and
page-number footer before committing to the offset).

**Coverage note.** This is Japanese Wave 1 (Writing System foundation), the first extraction for
Japanese and the first source with absolutely no digital text layer in this project to date
(`pdftotext` returns nothing at all — confirmed before starting). The entire book was vision-read
page by page from rendered 150dpi page images, not OCR'd or decoded from any font cipher. Per the
extraction spec's vision-reading guard: page 1 (the half-title) carries a previous owner's
handwritten pencil name ("Troyce A—") at the top and a hand-written katakana scribble (クソス,
plausibly the same owner's name attempt) at the bottom — both are clearly pencil/pen marks
inconsistent with the book's typeset font and are **excluded** as marginalia, not book content.
Page 25 also carries light pencil marginalia (an owner's handwritten "あか" written twice near the
top margin) which is likewise excluded. No other marginalia was found in the remaining 117 pages.

This single source is large enough that its extraction is sharded across four files:

- **001 (this file)** — book-level grammar: "An Explanation of Kana" (the book's own systematic
  description of the kana writing system — function, origin, voicing, combinations, long vowels,
  double consonants, irregularities, katakana-only conventions, repetition marks, punctuation) plus
  the full 46-symbol **hiragana** character inventory (one row per symbol: kana form, romanization,
  pronunciation gloss, and the symbol's historical "parent" kanji origin, which the book gives for
  every hiragana and most katakana symbols).
- **001b** — the **katakana** character inventory (46 symbols, same format) plus all vocabulary
  drilled in the katakana half of the book (Part II).
- **001c** — all vocabulary drilled in the hiragana half of the book (Part I mini-reviews and
  general review).
- **001d** — Part III ("Final Review"): the food/flora-fauna/personal-names quizzes, the *kana*
  word-search bonus vocabulary list, the "About Japan" reading passage, and the *Iroha* verse.

**Morphological/typological note for this language.** Japanese is agglutinative with a unique
multi-script writing system (hiragana + katakana + kanji, normally mixed with no inter-word
spacing). This specific source teaches *only* the two kana syllabaries — no kanji, no verb
conjugation, no particle grammar beyond the three kana-usage irregularities noted below — so there
is little agglutinative *morphology* to break down in this file; that will come from later,
grammar-focused Japanese sources. Per this language's new convention, every vocabulary entry below
records the actual script form the book uses (hiragana or katakana) alongside romanization and
gloss, because the book's own choice of script is itself linguistically meaningful here (katakana
marks loanwords/foreign proper nouns almost without exception; hiragana marks native Japanese
vocabulary) — see the katakana-vs-hiragana contrast documented explicitly in 001d's flora/fauna quiz
findings.

---

## Grammar points

### The two kana systems and their division of labor

*Kana* ("borrowed name," from *karina*) are purely phonetic syllabic symbols — not an alphabet,
since nearly every symbol represents a full consonant+vowel syllable (or a vowel alone), with only
one symbol (ん/ン, *n*) representing a bare consonant. There are two parallel 46-symbol systems,
*hiragana* and *katakana*, covering the same 46 basic sounds in the same traditional order (the
*gojūonjun*, "the fifty sounds order" — nominally fifty but only 46 are in current use; *yi*, *ye*,
and *wu* never existed, and *wi* (ゐ/ヰ) and *we* (ゑ/ヱ) were officially retired in 1946 as redundant
with *i* and *e*, though still occasionally seen). Standard written Japanese mixes *kanji* (meaning-
bearing characters borrowed from Chinese, pronounced in Japanese readings) with *hiragana* for
grammatical endings and particles, and *katakana* almost exclusively for words borrowed from
languages other than Chinese. The rule of thumb the book gives: **katakana for non-Chinese loan
words, hiragana and kanji for the rest.** Hiragana can substitute for an unknown kanji, so a learner
who knows only the ~92 kana symbols can already write functional (if unsophisticated) Japanese.
Historically, *hiragana* (from *hira-*, "ordinary/cursive") derives from full cursive Chinese
characters and was associated with women's writing in the Heian court; *katakana* (from *kata-*,
"partial") derives from taking just one component of a Chinese character and was associated with
men — both associations have long since disappeared. Both systems evolved around the late 8th
century.

### Voiced and half-voiced sounds (*dakuon*/*handakuon*)

Unvoiced consonants *k*, *s*, *t*, *h* voice to *g*, *z/j*, *d/z/j*, *b* respectively when the
diacritic ゛(two short strokes, upper right of the symbol) is added — this is *dakuon* ("voiced/
hardened sound"). *H*-row symbols additionally take a small circle ゜(*handakuon*, "half-voiced
sound") to shift *h*→*p*. *Ji* and *zu* are normally written じ/ず (ジ/ズ) rather than ぢ/づ, except
when a word's etymology clearly derives them from *chi*(ち)/*tsu*(つ) via compounding or
reduplication — e.g. *hanaji* "nosebleed" (*hana* "nose" + *chi* "blood") is written はなぢ, and
*tsuzuku* "continue" (reduplicated *tsutsuku*) is written つづく.

### Contracted sounds (*yōon*) and the extra-small-vowel katakana extensions

A consonant symbol ending in *-i* (き, し, etc., including voiced/half-voiced forms) can be followed
by a small ゃ/ゅ/ょ (*ya/yu/yo*) to form a single contracted syllable — e.g. き+ゃ = *kya*, not
*kiya* (the *i* sound is dropped from romanization; writing the second symbol full-size instead of
small changes the reading back to the two separate syllables). This yields the standard *kya–ryo*
combination charts (also realized for all voiced/half-voiced rows: *gya–byo*, *pya–pyo*). Katakana
additionally extends this same principle — a consonant symbol pairs with a small full vowel instead
of a small *y*-row symbol — to approximate sounds absent from native Japanese phonology, all of
which are recent conventions (some only "very recently" officially sanctioned, especially for
proper nouns): ファ/フィ/フェ/フォ for *fa/fi/fe/fo*, クァ for *qa* (*kwa*), ツァ for a German-style
*tsa* (e.g. Mozart), シェ/チェ/ジェ for *she/che/je*, ウィ/ウェ for *wi/we* (alongside the rarer
retired ヰ/ヱ), ウォ for *wo* (ヲ having become too associated with the grammatical object particle
to reuse), イェ for *ye*, ヴィ/ヴェ for a *v*-initiated syllable (ヴ+small vowel), ティ/ディ for *ti/
di* (supplanting the older unfaithful チ/ジ), テュ/デュ for *tu/du*, and トゥ for *tu*. Official
recognition of an established older form can coexist with a newer, more phonetically accurate one
— e.g. ヴァイオリン and バイオリン both occur for "violin," and the older ミルクセーキ
(*mirukusēki*) is preferred over a more literal rendering of "milkshake," while シェークスピア
("Shakespeare") keeps its established *she-* form. New ad hoc combinations are also freely coined,
e.g. ニェ for the *nye* of Russian *nyet*.

### Double consonants (*sokuon*) and the double *n* trap

Consonants *k*, *s*, *t*, *p* can be geminated by inserting a small っ/ッ (*tsu*) immediately before
them — e.g. がっき *gakki* "school term" (not *gakkii*; the extra mora lengthens the consonant, not
the following vowel). A small っ/ッ can never begin a word. Students commonly mis-apply this logic
to double *n*, which is instead written with ん/ン for the first *n* — *annai* "guide" is あんない,
never あっない.

### Long vowels

Hiragana lengthens *a*, *i*, *u*, *e* by simply repeating the vowel symbol (あ, い, う, え) after the
preceding kana — e.g. おかあさん *okāsan* "mother." Long *o* is the exceptional case: it is usually
formed by adding う (*u*) rather than お — e.g. そう *sō* "so, thus" — with お reserved for a small,
closed list of common words that must be learned case by case (книга: おおきい *ōkii* "big," おおい
*ōi* "many," とおい *tōi* "far," とお *tō* "ten," とおり *tōri* "way, road"). Katakana instead uses a
bar symbol ー (horizontal in normal script, vertical │ in vertical script) for any long vowel,
including in otherwise-unrelated-to-Japanese loanwords — e.g. ラバー *rabā* "rubber." When katakana
is used for native Japanese or Chinese-derived words (for emphasis, in telegrams, or certain
official/military documents), it reverts to the hiragana-style vowel-doubling convention instead of
the bar — e.g. がっこう *gakkō* "school" is written ガッコウ, not ガッコー, in that register.
Transcribing *kana* back to romanization requires checking that an apparent long vowel is not
actually two unlinked vowels across a word boundary — e.g. そう *sou* "go with" (verb) vs. そう *sō*/
*soo* "thus" (a genuine long vowel); further examples: すう *suu* "suck" (not *sū*), きいて *kiite*
"listening" (not *kīte*).

### Repetition marks (*odoriji*) and punctuation

A single kana symbol can be repeated using ゝ (becoming ゞ if the repeat is voiced); in vertical
script only, a multi-symbol repeat uses 〱 (or 〲 if the first repeated sound is voiced), spanning
two character-spaces. These are optional and restricted: they cannot be used where a word's first
symbol coincides with the immediately preceding word's last symbol (*kuroi ishi* "black stone"),
nor in compounds where the second word's first symbol matches the first word's last symbol
(*tama-matsuri* "festival of the dead"), nor where a word-ending's first symbol matches the stem's
last symbol (*ki-kimasu* "listen"). Valid examples given: みゝ *mimi* "ear," かゞみ *kagami*
"mirror," いろ〱 *iroiro* "various," さま〲 *samazama* "various." Basic Japanese punctuation
(*kutōten*): 。(*maru*, full stop), 、(*ten*, comma), 「 」(*kagi*, quotation marks — 「 ⌐ and ⌐」 in
vertical script).

### Three kana-usage irregularities tied to grammatical particles

Three high-frequency particles are written with kana that do not match their current pronunciation,
a historical relic of writing conventions lagging behind sound change: the topic particle *wa* is
written は (notわ, which would be the "expected" kana for *wa*); the object particle *o* is written
を (not お); the directional particle *e* ("to") is written へ (not え). These are the only common
cases of this kind of mismatch in modern standard usage.

---

## Hiragana character inventory (46 basic symbols)

Each entry gives the symbol, its romanization, the book's English-approximation pronunciation
guide, and the historical kanji/proto-form the symbol derives from (as the book's "ORIGIN" field
states it — a reference number into the companion volume *A Guide to Remembering Japanese
Characters* where applicable). Source type `grammar_reference`; vision-read throughout
(`plausible_unverified` unless noted); not real frequency data (`Weight/Frequency` = `—`
throughout); `Attested Era` = contemporary, source published 1990 for all entries (coarse,
whole-book, per the extraction spec).

| Hiragana | Romanization | Pronunciation gloss | Parent-character origin | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|
| あ | a | "a" in "car," but shorter | 安 (AN) | verified | |
| い | i | "ee" in "meet," but shorter | 以 (I) | verified | |
| う | u | "u" in "hula," but shorter | 宇 (U) | verified | |
| え | e | "e" in "get" | 衣 (E/I) | verified | |
| お | o | "o" in "or," but shorter | 於 (O) | verified | |
| か | ka | "ca" in "car," but shorter | 加 (KA) | verified | |
| き | ki | "ki" in "keep," but shorter | 幾 (KI) | plausible_unverified | |
| く | ku | "Ku" in "Kuwait," but shorter | 久 (KU) | verified | |
| け | ke | "ke" in "keg" | 計 (KEI) | plausible_unverified | |
| こ | ko | "co" in "core," but shorter | 己 (KO) | verified | |
| さ | sa | "sa" in "sarcasm," but shorter | 左 (SA) | verified | |
| し | shi | "shee" in "sheep," but shorter | 之 (SHI, part of 1335) | verified | |
| す | su | "Su" in "Susan," but shorter | 寸 (SUN) | verified | |
| せ | se | "se" in "set" | 世 (SE) | verified | |
| そ | so | "so" in "sore," but shorter | 曾 (SO, part of ZŌ 741) | plausible_unverified | |
| た | ta | "ta" in "tar," but shorter | 太 (TA) | verified | |
| ち | chi | "chee" in "cheek," but shorter | 知 (CHI) | verified | |
| つ | tsu | "tsu" in "tsunami" | 川 (SU) | verified | |
| て | te | "te" in "ten" | 天 (TEN) | verified | |
| と | to | "to" in "tore," but shorter | 止 (TO-maru) | verified | |
| な | na | "na" in "narcotic," but shorter | 奈 (NA) | plausible_unverified | |
| に | ni | "nea" in "neat," but shorter | 仁 (NI) | verified | |
| ぬ | nu | "noo" in "noon," but shorter | 奴 (NU/DO) | plausible_unverified | |
| ね | ne | "ne" in "net" | 禰 (NE) | plausible_unverified | |
| の | no | "no" in "north," but shorter | 乃 (NO/NAI) | verified | |
| は | ha | "ha" in "harm," but shorter | 波 (HA) | verified | |
| ひ | hi | "hea" in "heat," but shorter | 比 (HI) | verified | |
| ふ | fu | "foo" in "fool," but with softer "f" | 不 (FU) | verified | the book explicitly flags this as the clearest case of Hepburn-romanization vs. actual sound mismatch — no true English "f" equivalent exists in Japanese |
| へ | he | "he" in "hen" | 部 (HE/BU) | verified | |
| ほ | ho | "ho" in "horn," but shorter | 保 (HO) | verified | |
| ま | ma | "ma" in "mark," but shorter | 末 (MATSU) | verified | |
| み | mi | "mea" in "meat," but shorter | 美 (BI) | plausible_unverified | |
| む | mu | "moo" in "moon," but shorter | 武 (MU) | verified | |
| め | me | "me" in "met" | 女 (ME) | verified | |
| も | mo | "mo" in "more," but shorter | 毛 (MŌ) | plausible_unverified | |
| や | ya | "ya" in "yard," but shorter | 也 (YA, part of CHI 167) | verified | |
| ゆ | yu | "you" in "youth," but shorter | 由 (YU) | verified | |
| よ | yo | "Yo" in "York," but shorter | 与 (YO) | verified | |
| ら | ra | "ra" in "mirage," but shorter | 良 (RA/RYŌ) | verified | |
| り | ri | "ree" in "reek," but shorter | 利 (RI) | verified | |
| る | ru | "ru" in "rule," but shorter | 留 (RU) | plausible_unverified | |
| れ | re | "re" in "red" | 礼 (REI) | verified | |
| ろ | ro | "ro" in "roar," but shorter | 呂 (RO) | verified | |
| わ | wa | "wa" in "watt" | 和 (WA) | verified | |
| を | wo | "o" in "or," but shorter | 遠 (ON/EN) | plausible_unverified | grammatical object-particle kana; see "three kana-usage irregularities" above |
| ん | n | "n" in "sin" | 无 (MU) | verified | the only kana representing a bare consonant; can never start a word; see "double *n* trap" above |

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`. All grammar
explanations above are paraphrased in this file's own words; the handful of bracketed Japanese words
quoted are single illustrative lexical items, not reproduced passages.
