# English — Established Vocabulary/Grammar: CMOS Ch. 11, "Foreign Languages," pt. 5 (§§11.93–11.116: Transliteration general rules — Proofreading, Diacritics, Italics; Arabic; Chinese and Japanese; Hebrew)

**Source:** *The Chicago Manual of Style*, 16th edition (University of Chicago Press, 2010), Chapter
11, "Foreign Languages," PDF pp. 1455–1478 (§§11.93 through 11.116).

**Coverage note:** This chunk picks up within the "Languages Usually Transliterated (or Romanized)"
section, continuing from an earlier part's endpoint (§11.92, "Character sets for non-Latin
alphabets"). It covers the closing general-rules trio for transliterated languages (§§11.93–11.95:
proofreading caution, diacritics specialized-vs-general, italics-vs-roman), the full Arabic subsection
(§§11.96–11.101: transliteration systems, hamza/ʿayn, spelling of well-known names, the definite
article, capitalization, word division), the full Chinese and Japanese subsection (§§11.102–11.110:
Pinyin/Wade-Giles romanization, exceptions, apostrophes/hyphens/tone marks, a reference list of common
Chinese names, Japanese romanization, the modified Hepburn system, capitalization and italics, titles
of works, and inclusion of native characters), and the Hebrew subsection through §11.116
(§§11.111–11.116: romanization systems, diacritics, prefixes, capitalization/italics, word division,
unromanized Hebrew phrases). The next part picks up at §11.117 ("A note on Hebrew vowels"), which
begins the chapter's transition toward Russian transliteration (§11.118).

Per the dispatch note, this chapter is treated as genuine English-register content — CMOS's own
apparatus for how English-language publications absorb, mark, and typeset foreign-language material —
not as a source of Arabic, Chinese, Japanese, or Hebrew vocabulary in their own right. Several entries
in this range are pure cross-reference stubs or near-stubs with minimal independent content; none of
that kind appears in this particular range (unlike pt01's Albanian/Croatian capitalization stubs),
since every section here either states a genuine language-specific rule or gives worked examples.

The source has a genuine clean text layer; per dispatch instruction, Vision Reading Confidence is
`n/a` throughout and Transcription Confidence is `n/a` throughout (reference-book extraction). No
handwritten marginalia was present. Per dispatch instruction, Attested Era is set to "contemporary
(source published 2010)" throughout and Attested Region to "American English (United States)"
throughout, since the entirety of this CMOS edition is an American-English usage/style reference —
this applies even to rows discussing Arabic, Chinese, Japanese, or Hebrew terms, since the entries
describe *CMOS's own English-publishing convention* for handling that material, not an independent
attestation of the foreign language itself.

**Mojibake gotcha, confirmed repeatedly in this chunk exactly as flagged in the dispatch — and
confirmed non-uniform even within single pages, consistent with the spec's documented pattern.** This
section's subject matter (transliteration diacritics and romanization systems) is unusually dense with
non-ASCII characters, and the UTF-8-decoded-as-Latin-1 corruption pattern appeared on roughly half the
pages while the identical character on a neighboring page rendered perfectly — e.g. §11.97's sidebar
heading shows a clean "The hamza and the ʿayn," while the §§11.98–11.101 sidebar headings for the same
section title show "The hamza and the Ê¿ayn" on every subsequent page. Confirmed corrections, all
cross-checked against the correctly-rendered instances of the same characters elsewhere on
nearby/parallel pages or against standard orthographic facts:

- `â€”` (recurring in sidebar breadcrumbs, e.g. "alphabetsâ€”a warning," "Diacriticsâ€”specialized,"
  "Japaneseâ€”capitalization") → an **em dash (—)**; the standard three-byte UTF-8-as-Latin-1 mojibake
  pattern for U+2014, already documented in pt01.
- `Ê¿` (e.g. "the Ê¿ayn," "Ê¿Abd al-Rahman," "Ê¿AjaÊ¾ib") → **ʿ** (U+02BF, modifier letter left half
  ring — the Arabic/Hebrew ʿayn mark). Two-byte UTF-8 (CA BF) read as Latin-1 produces exactly this
  `Ê¿` sequence; confirmed against the clean "ʿayn" rendering on §11.97's own first occurrence.
- `Ê¾` (e.g. "the hamza (Ê¾)," "AjaÊ¾ib") → **ʾ** (U+02BE, modifier letter right half ring — the hamza
  mark). Same mechanism (UTF-8 CA BE), confirmed against §11.97's clean "hamza (ʾ)" rendering.
- `á¹` (§11.101, "iá¹-baq") → **ṭ** (U+1E6D, t with dot below) followed by an invisible soft hyphen;
  the three-byte UTF-8 sequence E1 B9 AD decodes under Latin-1 to "á¹" plus a non-printing C1 control
  character, so the garbled form and the correct form ("iṭ-baq," the underdotted-second-letter example
  the surrounding sentence is explicitly illustrating) look almost identical except for the missing
  diacritic dot — recovered from context, not a fixed table lookup.
- `Ã¼` (§11.105, "YÃ¼an," "Lu HsÃ¼n") → **ü** (U+00FC); recovered as the standard Wade-Giles spellings
  "Yüan" (dynasty name) and "Hsün" (as in Lu Xun).
- `Å` standing alone before a consonant (§11.106, "rÅmaji," "hyÅjun") → **ō** (U+014D, o with macron);
  the two-byte UTF-8 sequence C5 8D decodes to "Å" plus an invisible C1 control character under
  Latin-1, so only the "Å" is visible. Recovered as "rōmaji" and "hyōjun," cross-checked against the
  correctly-rendered "Tōkyō, Hokkaidō, Kōbe, shōgun, daimyō" one page later (§11.107), which shows the
  identical macron-o rendering cleanly — the same character corrupts on one page and not the next,
  confirming the non-uniformity pattern.
- `Å«` (§11.106, "KenkyÅ«sha's"; §11.99, "AbÅ« 'l-Muhallab") → **ū** (U+016B, u with macron); same
  two-byte mechanism as the ō case above, this time with the second byte (AB → «) printable. Recovered
  as "Kenkyūsha's" (the dictionary publisher) and "Abū 'l-Muhallab."

**Distinct extraction-tooling artifact, not mojibake:** §11.94's Sanskrit example ("Vishnu" vs.
"Viṣṇu") lost its two underdotted consonants (ṣ and ṇ) entirely in the plain-text layer — the raw
extraction reads "Vi u" with a bare gap, no garbled bytes at all, unlike every case above. This looks
like a ligature/composite glyph with no ToUnicode entry rather than a decodable substitution. The
correct form was recovered by viewing the rendered page image directly (the glyphs display correctly
there) and cross-checked against standard Sanskrit-transliteration orthography ("Viṣṇu" is the
universally standard spelling). Per dispatch instruction Vision Reading Confidence stays `n/a` (the
source has a genuine text layer and this was a targeted recovery for two characters, not a page vision-
read), but the recovery method is flagged here per the spec's per-row confidence discipline.

**No non-decodable non-Latin-script content was found in this chunk.** The embedded Chinese and
Japanese characters in §11.110 (日本研究と文化研究, 思想, 華林甫, 清代以來三峽地區水旱災害的初步硏究,
中國社會科學, 敎育勅語) and the Hebrew phrase in §11.116 (איכה ישבה בדד) all extracted cleanly via the
genuine text layer with correct, legible codepoints — a positive contrast to the chapter's own warning
in §11.93 about the dangers of proofreading unfamiliar non-Latin scripts. (Hebrew's right-to-left
embedding within the English sentence does reorder in a naive linear text dump, as the chapter's own
§11.116 discussion explicitly describes and warns about — this is the source's own subject matter, not
an extraction bug.)

---

## Vocabulary

CMOS is a style/usage reference, not a vocabulary-teaching text. Its "vocabulary" in this chunk is the
specialized romanization/transliteration terminology English-language publishing uses, plus a compact
reference list of Chinese proper names the source itself presents as a named table (§11.105) —
transformed here into this project's own schema and paraphrased rather than reproduced as a copied
box. All entries: Attested Era `contemporary (source published 2010)`, Attested Region `American
English (United States)`, Source Type `grammar_reference`, Transcription Confidence `n/a`, Vision
Reading Confidence `n/a`, unless noted.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| hamza (ʾ) | the glottal-stop mark in transliterated Arabic (and, by the same convention, Hebrew's ʾalef); represented by U+02BE, distinct from the actual Arabic hamza character | noun | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | transnational | grammar_reference | n/a | n/a | §§11.96–11.97; often represented by an apostrophe in nonspecialized works (e.g. *Qur'an*) and dropped at the start of a word (*anzala* not *ʾanzala*) |
| ʿayn (ʿ) | the pharyngeal-consonant mark in transliterated Arabic (and, by the same convention, Hebrew's ʿayin); represented by U+02BF, distinct from the actual Arabic ʿayn character | noun | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | transnational | grammar_reference | n/a | n/a | §§11.96–11.97; sometimes represented by a single opening quotation mark, which CMOS flags as risky since ʿayn often opens a word |
| al- (Arabic definite article) | the Arabic definite article, joined to its noun with a hyphen in Chicago's recommended style (*al-Islam*, *al-Nafud*); the *l* assimilates in speech to *d, n, r, s, sh, t, z*, optionally shown in transliteration (*an-Nafud*) | article | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | transnational | grammar_reference | n/a | n/a | §11.99; some authors drop the *a* and substitute an apostrophe after a long syllable or a particle (*Abū 'l-Muhallab*, *wa 'l-layl*) |
| ALA-LC Romanization Tables | the Library of Congress's detailed romanization-system reference, cited by CMOS as one acceptable standard for Arabic, Chinese, and Hebrew transliteration alike, with a caution to use it carefully if unfamiliar with the language | proper noun | technical.publishing | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §§11.96, 11.102, 11.111; recurs across all three transliterated-language subsections in this chunk |
| Hanyu Pinyin (Pinyin) | the Chinese-introduced (1950s) romanization system that has supplanted Wade-Giles as the standard for romanizing Chinese, including in Library of Congress cataloging since 2000 | proper noun | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | transnational | grammar_reference | n/a | n/a | §§11.102–11.104; CMOS "joins librarians in urging that Pinyin now be used in all scholarly writing" |
| Wade-Giles | the older Chinese romanization system Pinyin has largely supplanted; still sometimes added parenthetically after a Pinyin spelling for reader context, or retained by scholars not yet converted | proper noun | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | transnational | grammar_reference | n/a | n/a | §§11.102–11.105 |
| Postal Atlas (romanization) | a third, older place-name spelling system (from the *Postal Atlas of China*, last updated in the 1930s), now effectively superseded alongside Wade-Giles by Pinyin for geographic names | proper noun | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | transnational | grammar_reference | n/a | n/a | §§11.102, 11.105 |
| tone marks (Pinyin) | the system of accents over certain vowels prescribed by the 1962 Hanyu Pinyin system, used to mark Chinese tones; explicitly not included in the Library of Congress's own Pinyin romanization system | noun phrase | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | transnational | grammar_reference | n/a | n/a | §11.104; distinguished from the apostrophe sometimes used to disambiguate syllable boundaries (*Xi'an* vs. *Xian*) |
| rōmaji | the general term for romanized Japanese, introduced into Japan in the sixteenth century; several systems have been developed since | noun | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.106 |
| modified Hepburn system (hyōjun) | the romanization system in common use since the early Meiji period (1868–1912), named for James Curtis Hepburn (1815–1911); used by *Kenkyūsha's New Japanese–English Dictionary* and almost universally outside Japan | proper noun | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §§11.106–11.107; a syllabic *n* before a vowel or *y* takes a following apostrophe (*Gen'e*, *San'yo*) |
| kanji | the Chinese characters used as one component of the standard written form of Japanese | noun | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.106 |
| kana | either of the two Japanese syllabaries (a syllabary being a set of written characters each representing a syllable), used alongside kanji in standard written Japanese | noun | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.106 |
| macron (Japanese long-vowel marker) | a bar placed over a vowel to mark vowel length in modified-Hepburn-romanized Japanese, used for all long vowels except in well-known place-names (*Tokyo*, *Hokkaido*, *Kobe*) and fully English-assimilated words (*shogun*, *daimyo*) | noun | technical.publishing | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.107; when pronunciation matters to readers, the fuller forms (*Tōkyō*, *Hokkaidō*, *Kōbe*, *shōgun*, *daimyō*) may be used instead |
| Hebrew prefixes | prepositions, conjunctions, and the article that attach as prefixes in Hebrew; romanized text may or may not mark the join with an apostrophe or hyphen, with no equivalent marker in the Hebrew script itself | noun phrase | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | transnational | grammar_reference | n/a | n/a | §11.113; either marking convention is acceptable if used consistently |
| ʾalef and ʿayin (Hebrew) | the two Hebrew letters conventionally represented, in transliteration, with the same marks used for the Arabic hamza and ʿayn | noun | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | transnational | grammar_reference | n/a | n/a | §11.112; CMOS explicitly cross-references its own Arabic hamza/ʿayn convention (§11.97) rather than giving Hebrew-specific marks |

**Chinese proper-name reference list (§11.105 — "Some common Chinese names," transformed from the
source's own three-part table into this project's schema).** Wade-Giles forms are the older
romanization; Pinyin is Chicago's recommended current standard (see the Pinyin/Wade-Giles rows above).

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Zhou | dynasty name; Wade-Giles *Chou* | proper noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.105, Dynasties |
| Qin | dynasty name; Wade-Giles *Ch'in* | proper noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.105, Dynasties |
| Qing | dynasty name; Wade-Giles *Ch'ing* | proper noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.105, Dynasties |
| Song | dynasty name; Wade-Giles *Sung* | proper noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.105, Dynasties |
| Tang | dynasty name; Wade-Giles *T'ang* | proper noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.105, Dynasties |
| Yuan | dynasty name; Wade-Giles *Yüan* | proper noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.105, Dynasties; see mojibake note (`YÃ¼an` → *Yüan*) |
| Fang Lizhi | personal name; Wade-Giles *Fang Li-chih* | proper noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.105, Personal names |
| Hua Guofeng | personal name; Wade-Giles *Hua Kuo-feng* | proper noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.105, Personal names |
| Lin Biao | personal name; Wade-Giles *Lin Piao* | proper noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.105, Personal names |
| Lu Xun | personal name; Wade-Giles *Lu Hsün* | proper noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.105, Personal names; see mojibake note (`Lu HsÃ¼n` → *Lu Hsün*) |
| Mao Zedong | personal name; Wade-Giles *Mao Tse-tung* | proper noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.105, Personal names |
| Deng Xiaoping | personal name; Wade-Giles *Teng Hsiao-p'ing* | proper noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.105, Personal names |
| Sun Yat-sen; Chiang Kai-shek | two personal names explicitly noted as exceptions that usually retain their old (non-Pinyin) spellings even in Pinyin-standard writing | proper noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.105; the chapter's own named exception to its general Pinyin-preference rule |
| Guangdong | geographic name; Wade-Giles *Kuang-tung*, Postal Atlas *Kwangtung* | proper noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.105, Geographical names |
| Beijing | geographic name; Wade-Giles *Pei-ching* (also *Pei-p'ing*), Postal Atlas *Peking* (also *Peiping*) | proper noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.105, Geographical names |
| Shanghai | geographic name; identical across Wade-Giles, Postal Atlas, and Pinyin (*Shang-hai* / *Shanghai* / *Shanghai*) | proper noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.105, Geographical names; the one entry where all three systems converge |
| Suzhou | geographic name; Wade-Giles *Su-chou*, Postal Atlas *Soochow* | proper noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.105, Geographical names |
| Dalian | geographic name; Wade-Giles *Ta-lien*, Postal Atlas *Dairen* | proper noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.105, Geographical names |

## Grammar points

### Proofreading non-Latin alphabets (§11.93)

A general caution opening the transliterated-languages section: anyone unfamiliar with a non-Latin
alphabet should proofread such text with extreme caution, since visually similar characters are easily
mistaken for each other. CMOS recommends editors query the author when in doubt and, when referring to
a specific character or diacritic, cite its Unicode number and description (per §11.2, covered in an
earlier part).

### Diacritics — specialized versus general contexts (§11.94)

Nearly every transliteration system in this part of the chapter (macrons, underdots, overdots, and
more) requires diacritics. For nonspecialized works, CMOS recommends using as few diacritics as needed
to aid pronunciation, favoring the undiacritic-marked forms listed in current Merriam-Webster
dictionaries. The illustrative example contrasts a general-audience preference for "Shiva" and "Vishnu"
against a specialist's preference for the fully marked "Śiva" and "Viṣṇu," which distinguish Sanskrit
*Sh* from *sh* as genuinely separate letters (see the extraction-artifact note above on how "Viṣṇu" was
recovered here).

### Italics versus roman for transliterated terms (§11.95)

Transliterated terms that are not proper names and have not been absorbed into English are italicized;
a term used repeatedly through a work may be italicized only on first appearance and then set in roman
thereafter. Terms already listed in the dictionary are normally set in roman. CMOS illustrates the
distinction with the Greek-derived pair *agapē* and *erōs*: italicized and marked with macrons while
still treated as foreign terms, but set roman and unmarked ("agape," "eros") once absorbed into English
usage — the same preacher's-sermon example works either way depending on how assimilated the author
judges the terms to be.

### Arabic transliteration systems (§11.96)

No transliteration system for Arabic is universally accepted. CMOS cites the ALA-LC Romanization
Tables as one detailed option and the *International Journal of Middle East Studies*'s own system as
another, recommending an author pick one system and minimize exceptions. Within the chapter's own
examples, only the hamza and ʿayn marks are used (see next point); letters with underdots and other
special characters appear in the chapter's own Table 11.2.

### The hamza and the ʿayn (§11.97)

These two marks appear constantly in transliterated Arabic and must be kept visually distinct by the
author on every occurrence (by coding or explicit instruction to the typesetter), since the Unicode
characters used for transliteration are not the same as the actual Arabic letters they stand for. In
nonspecialized writing the hamza is sometimes informally rendered as an apostrophe (*Qur'an*) and the
ʿayn as a single opening quotation mark — a convention CMOS flags as risky, since the ʿayn frequently
opens a word, inviting confusion with ordinary quotation punctuation. Most transliteration systems drop
a word-initial hamza entirely (*anzala*, not *ʾanzala*).

### Arabic spelling of well-known names (§11.98)

Isolated references to well-known people or places should use the form already familiar to
English-speaking readers rather than a strict transliteration: *Avicenna* (not *Ibn Sina*), *Damascus*
(not *Dimashq*), *Mecca* (not *Makkah*).

### The Arabic definite article (§11.99)

Chicago recommends joining the Arabic definite article *al* to its noun with a hyphen (*al-Islam*,
*al-Nafud*, *Bahr al-Safi*, *al-Qaeda* or *al-Qaida*). In speech the *l* of *al* assimilates to the
sounds *d, n, r, s, sh, t,* and *z*; this assimilation is sometimes shown in transliteration where
rendering actual pronunciation matters (e.g. transliterating poetry: *an-Nafud*, *Bahr as-Safi*), but
is usually left unmarked otherwise. Some authors drop the *a* of *al* and substitute an apostrophe
after a long syllable (*Abū 'l-Muhallab*) or when the article connects to a particle (*wa 'l-layl*).

### Arabic capitalization (§11.100)

Because the Arabic alphabet itself has no case distinction, capitalization of transliterated Arabic
varies across publications. CMOS applies its general sentence-style rule (§11.3, from an earlier part):
capitalize only the first word and proper nouns, for titles of works, journal names, and organization
names alike. Like English "the," *al* is capitalized only when it opens a sentence or title, as shown
in the chapter's worked title example (a biographical/historical work title, cited with author name,
title, and English gloss).

### Arabic word division (§11.101)

Breaking a transliterated Arabic word across a line-end hyphen should be avoided where possible. If
unavoidable, a break may follow *al* or *Ibn*, or follow two letters where the second carries an
underdot. Breaks must never fall between the digraphs *dh, gh, kh, sh,* or *th* unless both letters
carry underdots, and never immediately before or after a hamza. Otherwise, ordinary English
word-division rules apply (cross-referencing §§7.31–43, covered elsewhere in the manual).

### Chinese romanization (§11.102)

Hanyu Pinyin, introduced by the Chinese in the 1950s, has largely supplanted both the older Wade-Giles
system and the *Postal Atlas of China*'s place-name spellings, and is now the standard for teaching
Chinese as a second language. The Library of Congress converted its Chinese-collection catalog records
to Pinyin as of 2000, and CMOS joins librarians in urging Pinyin's use in all scholarly writing about
China. Some scholars long accustomed to Wade-Giles have not converted; adding the Wade-Giles spelling
parenthetically after a first Pinyin use can help readers in such cases. The ALA-LC Romanization
Tables are again cited, with a caution to use them carefully if unfamiliar with Chinese.

### Exceptions to Pinyin (§11.103)

Certain place-names, personal names, and other proper nouns long familiar in an older form may keep
that familiar English-text spelling, or the old spelling may be added parenthetically after the Pinyin
form for consistency. When in doubt, CMOS recommends consulting the latest Merriam-Webster's
Collegiate Dictionary; forms not listed there in an older spelling should default to Pinyin. An editor
who wants to change an author's spelling choice should consult the author first.

### Apostrophes, hyphens, and tone marks in Chinese romanization (§11.104)

Pinyin spellings often differ visibly from older ones. Personal names are usually spelled without
apostrophes or hyphens, but an apostrophe is sometimes inserted to prevent ambiguous syllable merging
(*Xi'an*, distinguishing it from *Xian*) — except where tone marks are already in use. The Library of
Congress's own Pinyin romanization system does not include tone marks, the accent system the 1962
Hanyu Pinyin standard itself prescribes for Chinese tones.

### Some common Chinese names (§11.105)

A reference list (reproduced in this project's own Vocabulary schema above, not as a copied box) of
dynasty names, personal names, and geographic names in both Wade-Giles and Pinyin forms (with Postal
Atlas forms added for geographic names), illustrating how divergent the two romanization systems can
look for the same referent. Two personal names — Sun Yat-sen and Chiang Kai-shek — are explicitly
flagged as usually keeping their old spellings regardless of the general Pinyin-preference rule.

### Japanese romanization (§11.106)

Standard written Japanese mixes Chinese-derived kanji characters with two kana syllabaries. Romanized
Japanese (rōmaji) dates to the sixteenth century; several romanization systems have since been
developed. The modified Hepburn system (hyōjun), in common use since the early Meiji period
(1868–1912), is used by *Kenkyūsha's New Japanese–English Dictionary* and most other Japanese–English
dictionaries, underlies the Library of Congress's own Japanese romanization tables, and is used almost
exclusively outside Japan, notably in Asian-collection libraries worldwide.

### Modified Hepburn system (§11.107)

Named for James Curtis Hepburn (1815–1911). An apostrophe follows a syllabic *n* when it precedes a
vowel or *y* (*Gen'e*, *San'yo*). A macron marks long vowels in Japanese words generally, except in
well-known place-names (*Tokyo*, *Hokkaido*, *Kobe*) and English-assimilated words ("shogun,"
"daimyo") that are consequently not italicized either; where pronunciation matters to readers, the
fuller macron forms (*Tōkyō*, *Hokkaidō*, *Kōbe*, *shōgun*, *daimyō*) may be used instead. Hyphens
should be used sparingly in Japanese romanization, as the chapter's compound-phrase examples
illustrate.

### Chinese and Japanese — capitalization and italics (§11.108)

Since neither Chinese nor Japanese distinguishes capital letters, capitalization is introduced only in
the romanized form, following normal English conventions (cross-referencing chapter 8, covered
elsewhere). Personal names and place-names are capitalized; in hyphenated names, only the first
element is capitalized in romanized Chinese, while Japanese may capitalize both elements. Common nouns
and other words used within an English sentence are lowercased and italicized. Names of institutions,
schools of thought, and religions are capitalized when set in roman but lowercased when set in italics
— the chapter's worked examples contrast a formally named institution/movement pair set in roman with
italicized common-noun uses of terms like *bingbu* (Board of War) and *genrō* (elder statesmen of
Japan, noted as grammatically both singular and plural).

### Titles of Japanese and Chinese works (§11.109)

As with English titles, book and periodical titles are italicized while article titles are set in
roman inside quotation marks (cross-referencing §§8.154–95, covered elsewhere). The first word of a
romanized title is always capitalized, as are many proper nouns, especially in Japanese. The chapter
gives four worked bibliographic-citation examples (two Chinese book/article titles, two Japanese
book/article titles), each with a bracketed English gloss of the title's meaning — illustrative
citation format only, not reproduced here beyond this description per copyright discipline.

### Inclusion of Chinese and Japanese characters (§11.110)

Native-script characters may follow a romanized citation item to help readers identify the reference,
most often confined to bibliographies and glossaries; in running text they are parenthetical. Unicode
has made including such characters in manuscripts easier, but CMOS notes publishers still need warning
if a publication will require particular non-Latin fonts. Three worked citation examples pair romanized
and native-character forms of Japanese and Chinese journal/article/term citations — all three extracted
with fully legible native-script text (see the "no non-decodable content" note above).

### Hebrew transliteration systems (§11.111)

Several acceptable Hebrew romanization systems exist, including the ALA-LC Romanization Tables; any
may be used, but the author is responsible for applying it consistently throughout a given work.

### Diacritics in transliterated Hebrew (§11.112)

Transliterated Hebrew sometimes requires underdots (Ḥḥ, Ḳḳ, Ṭṭ, Ṿṿ), macrons (Āā, Ēē, Īī, Ōō, Ūū), an
acute accent (Śś), hačeks/carons (at least Ěě is clearly legible in this extraction; a second
haček-marked pair preceding it did not extract cleanly from the text layer — inferred with
`low_confidence` as Čč by pattern, paralleling the Croatian/Bosnian Č already documented in an earlier
part — flagged rather than silently assumed), and a superscript ə (schwa) for a reduced vowel. The
ʾalef and ʿayin may be marked the same way as the Arabic hamza and ʿayn (§11.97); some systems also use
a prime (soft sign).

### Hebrew prefixes (§11.113)

Several Hebrew prepositions, conjunctions, and articles attach as prefixes, with no marker for this in
the Hebrew script itself. In romanized text, authors may mark the join with an apostrophe or hyphen, or
not; either convention is acceptable if used consistently.

### Hebrew capitalization and italics (§11.114)

The Hebrew alphabet has no capital letters and no universally used romanized-capitalization system.
Writers may follow normal English capitalization practice for proper names and titles (cross-referencing
§§11.3, 11.9, covered elsewhere), or eschew capitalization altogether — internal consistency is the
only hard requirement. Italics in romanized Hebrew likewise follow normal English usage
(cross-referencing §11.5).

### Hebrew word division (§11.115)

For romanized Hebrew, or Hebrew words absorbed into English, the general English word-division
principles (§§7.31–43) apply, with one addition: when a double consonant falls at the point of
division, one consonant goes with each half (*Rosh Ha-shana*, *Yom Kip-pur*).

### Unromanized Hebrew phrases (§11.116)

Hebrew reads right to left; when an English sentence embeds an unromanized Hebrew phrase, the Hebrew's
own internal word order is preserved within the sentence (modern software can generally mix
left-to-right and right-to-left text in the same line). If a line break falls within the Hebrew phrase,
the words must still read right to left on each line — which can make the words appear reordered
relative to an unbroken rendering, as the chapter demonstrates with the same short Lamentations phrase
broken two different ways. As a safeguard, CMOS recommends the author highlight all Hebrew-script words
and give the typesetter detailed line-break instructions.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes, dialogue
blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`. The Chinese names table and the
Japanese/Chinese title-citation and character-inclusion examples (§§11.105, 11.109, 11.110) were
transformed into this project's own schema/paraphrase rather than reproduced as copied source boxes.
