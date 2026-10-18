# Japanese — Established Vocabulary/Grammar: Writing System — Oversized Kanji Character Dictionaries (Curated Sample)

**Coverage note — this file covers two independent oversized dictionary-style sources, each sampled
representatively per this project's rule for oversized dictionaries (same precedent used for Heisig's
*Remembering the Kanji 1–3*, see `021_remembering_the_kanji_1.md`/`022`/`023`): front matter explaining
the dictionary's own organizing system, then a handful of entries spread across the frequency/grade
range (common Jōyō kanji through rarer/non-Jōyō characters), rather than exhaustive entry-by-entry
transcription.**

**Distinctiveness check performed:** grepped prior `established/` Japanese files for "SKIP," "Halpern,"
and "NJECD" — zero hits. Neither source overlaps with the Heisig books (021–023; primitive-element
imaginative-mnemonic method, no readings/compounds) or with Henshall's guide (003; etymological
narrative, no systematic indexing scheme). Both sources below are by the same compiler (Jack Halpern)
and are explicitly linked — the second is stated on its own copyright page to be "based on" the
first — so their shared SKIP indexing system and shared entry-format conventions are described once,
under Source 1, and Source 2's notes focus only on what is genuinely different (condensed compound
selection, added cross-reference columns, Unicode/NJECD-entry-number fields).

**PDF/DjVu extraction gotcha — no text layer in either file.** `djvutxt` was tried first on both
`.djvu` files at multiple widely-spaced pages (page 1, 50, 200, etc.) and returned zero bytes of
extracted text in every case — these are pure image scans with no embedded OCR/text layer at all
(not a font-substitution cipher, since there is no text layer to decode in the first place). Every
entry recorded below was recovered by rendering the exact DjVu page to a raster image (`ddjvu
-format=pnm`, downscaled to ~1000–1200px wide with Pillow) and reading the glyphs directly — i.e.,
vision-confirmed against the actual typeset page. Both are clean commercial typeset scans (consistent
font throughout, no handwriting, no binding-gutter shadows observed on any sampled page) — no
marginalia was found on any page checked, so no exclusions were needed under the vision-reading
guard.

---

## Source 1: NTC's New Japanese-English Character Dictionary

**Source:** Jack Halpern (Editor in Chief), in association with Kenkyusha Limited, *NTC's New
Japanese-English Character Dictionary* (新漢英字典), NTC Publishing Group, copyright © 1993 by Jack
Halpern (published by arrangement with Kenkyusha, Ltd., Tokyo; the dictionary proper — "Japanese–
English Character Dictionary," pp. 1–1696 — was itself first published in Japan by Kenkyusha in
1990), ISBN 0-8442-8434-3. 2,217 DjVu pages total. Source file: `source_reference/languages/
Japanese/07.Dictionaries, Phrasebooks/NTC's New Japanese-English Character Dictionary.djvu`.

**Coverage note — representative sample of a 2,217-page, ~3,600-entry character dictionary.** Sampled:
the title/copyright pages; the Introduction/Outline-of-Writing-System front matter (its own
etymological theory, "the Periodic Table of Chinese Characters"); the Features section (homophone
discrimination); the "System of Kanji Indexing by Patterns" (SKIP) front-matter explanation; the
Guide to the Dictionary's entry-format walkthrough (worked example, entry 706 漸); and ten main
entries spread across the character-number sequence (5, 315–316, 1011, 1725, 2339, 3012–3017,
3555–3556) chosen to show the full Jōyō grade range (Jōyō-1 through Jōyō-6), a non-Jōyō "Reference"-
grade entry, a bare radical/primitive-only entry, and two cross-reference-only entries (a handwritten-
abbreviation redirect and an incorrect-stroke-count redirect) — the dictionary's main-entry format in
full plus the auxiliary entry types that pad out its non-main-entry pages.

### The SKIP indexing system (System of Kanji Indexing by Patterns)

The dictionary's signature organizing scheme, explained in its own front matter (pp. 106a–153a of the
front matter, by page-number convention; see also the Kodansha source below, which reproduces the
identical chart). Characters are classified into exactly **4 top-level geometric patterns** based on
how the whole character visually divides, not by traditional radical: **1 (Left-Right)** — a clear
or conceptual vertical split (e.g. 相, 代, 小); **2 (Up-Down)** — a horizontal split, with four
sub-variants (clear space, conceptual space, horizontal-line split, frame element) (e.g. 示, 言, 寺,
古); **3 (Enclosure)** — one shape wholly or partially enclosing another, with six sub-variants of
enclosure geometry (e.g. 進, 旬, 麻, 間, 医, 回); **4 (Solid)** — a character that resists any such
division, with four further sub-rules (top line, bottom line, through line, or "others") (e.g. 下,
上, 中, 人). Each character then gets a 3-part SKIP code (pattern–stroke count of first part–stroke
count of second part, e.g. 水 = 1-1-3), giving alphabetical-dictionary-like lookup speed without
requiring the learner to already know the traditional 214-radical system. The book's own Introduction
states SKIP's three design goals explicitly: **speed and consistency** (based on how people
*intuitively* perceive a character's parts, validated by computer analysis of pattern-perception data
across many users), **etymological integrity** as a side benefit (SKIP divisions often — not always —
coincide with real radical boundaries; the book gives 勝 as a counterexample, divided as 月+券 by SKIP
but 月+力 by radical), and **uniform distribution** across the four pattern buckets (deliberately
unlike radical-based schemes, where some radicals contain vastly more characters than others).
**Copyright note:** the book's own copyright page states the SKIP system's reproduction/use in
classifying characters is explicitly reserved — "no part of this publication may be reproduced... including
the reproduction or utilization of the SKIP indexing system, particularly the ordering of characters
in dictionaries and reference works on the basis of said system" — recorded here as a paraphrased
description of the system's logic for comparative-linguistics purposes, not a reproduction of the
dictionary's own character ordering.

### The "Atomic Theory of Chinese Characters" (etymological framework)

A second, independent organizing idea presented in the Outline-of-Writing-System front matter (p. 52a
sampled): characters are described as decomposing into "atoms" (indivisible basic elements, e.g. 目
'eye') that combine into "molecules" — recurring basic elements shared across a family of characters
that also share, to varying degrees, **shape**, **reading**, and **meaning** (the book's worked
example: 目 'eye' + 儿 'legs' → 見 ken 'see'; 目 + 木 'tree' → 相 sō 'face each other'; and further
compounding of 相 and 直 into 悳/德-family and 盾-family characters). The book calls this its "Atomic
Theory of Chinese Characters" (citing Halpern's own earlier Japanese-language monograph 漢字の再発見
*Kanji no Saihakken*, Shōdensha, 1987) and distinguishes it explicitly from the traditional six (now
seven) categories of character formation.

### Entry-format architecture (worked example: 漸, entry 706)

The Guide to the Dictionary (front-matter section, p. 162a sampled) walks through one worked main
entry (漸 "gradually," SKIP 1-3-11, radical 氵85, Jōyō grade, frequency rank 1753) to explain the
page layout: an **entry-head data block** (entry character in multiple type styles, entry number,
Chinese simplified-equivalent + Mandarin reading marked "CH", stroke-order diagram, reference-data
box with Radical/Strokes/Grade/Freq fields and the SKIP code), followed by explanatory matter split
into two side-by-side columns separated by a dotted line: a **core-meaning/compounds column**
(bolded core meaning "GRADUALLY," lettered sub-senses, compound words with readings and glosses,
independent-use readings) and a **synonyms/cross-reference column** (a boxed SYNONYMS list of
near-synonym characters each cross-referenced by entry number, e.g. "遍 progressively → 3106," plus a
boxed NOTE flagging easily-confused characters, e.g. "do not confuse with 暫 2864"). The dictionary
distinguishes **main entries** (full treatment, Jōyō/Jinmei/high-frequency unapproved characters) from
three auxiliary entry types that share the main numbering sequence but get abbreviated treatment:
**cross-reference entries** (834 total — 746 single-character + 88 multi-character — placed at a
character's *incorrect*-but-plausible SKIP/stroke-count location, redirecting to the correct entry;
confirmed directly in the sample as both "incorrect classification ⇒ see [entry]" and "incorrect
stroke count ⇒ see [pattern-code]" variants), **handwritten-abbreviation entries** (a character
form seen in informal handwriting, cross-referenced to its standard-form entry, e.g. 事 as a
handwritten abbreviation for 事 3567 — note the sample shows this occurring even for characters not
conventionally thought of as having variant handwritten forms), and **bare radical/primitive
entries** (a component shown with its standard form, variant forms, and a one-line "used in
characters related to X" description, but no compounds/readings of its own, e.g. 《川 "river" and 采
"nogome/separate").

### Homophone-discrimination and kun-homophone features

The Features front-matter section (p. 92a sampled, §5.2 "Discriminating Homophones") singles out
Japanese *on* (Sino-Japanese) vs. *kun* (native) homophones as a distinct pedagogical problem: *on*
homophones (e.g. kōki vs. kikō, each representing roughly a dozen distinct compounds pronounced
identically) are usually easy to tell apart once written in kanji, since the underlying meanings are
unrelated; *kun* homophones (e.g. the three readings of "noboru" — 上る 'go up,' 登る 'climb, scale,'
昇る 'ascend, rise [to the sky]' — all glossed as "easily confused" in the book's own table) are a
much harder problem since a single native word can be written with several characters whose meanings
are close or identical, and conversely a single kun word like *sasu* can be written "in dozens of
ways." Each main entry carries its own boxed HOMOPHONES field listing same-pronunciation words
written with different characters, cross-referenced by entry number (confirmed directly in the 束
entry sample below: "tsuka ⇒ 柄 897," with a NOTE pointing to a fuller usage discrimination at that
other entry).

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 水 (entry 5, SUI/mizu, SKIP 1-1-3) | water | kanji (noun) | core | Freq rank 145 (book's own frequency-rank field) | contemporary (source published 1990/1993) | — | — | dictionary | n/a | verified | Radical 水85, Jōyō grade 1, 4 strokes. Full main-entry example: core meaning WATER with 5 numbered sub-senses (cold water; liquid/watery prefix; hydrogen; "Wednesday" via the five-elements system; "Mercury" the planet), independent reading 【sui 水】"Wednesday; shaved ice; fifth of the five elements," kun reading 【mizu 水】with 3 numbered senses incl. a sumo-specific sense ("mizu-iri no sumō," a sumo match with a break) and an idiomatic sense ("mizu o sasu," lit. "pour water into," idiom for "throw cold water on/estrange"), plus a boxed SYNONYMS list (e.g. 湯 "hot water" → entry 612). |
| 拙 (entry 315, SETSU/tsutanai, SKIP 1-3-5) | clumsy | kanji (adjective/verb stem) | core | Freq rank 1696 (the dictionary's own lowest/last frequency rank observed in this sample) | contemporary (source published 1990/1993) | — | — | dictionary | n/a | verified | Radical 扌64, Jōyō grade. Sense ② is a lexicalized humble-register self-reference prefix ("[humble] my, my poor" — 拙者 sessha "I," 拙宅 settaku "my humble home") — notable as an explicit register/politeness-marking use captured in a kanji dictionary rather than a grammar reference. |
| 招 (entry 316, SHŌ/maneku, SKIP 1-3-5) | invite | kanji (verb stem) | core | Freq rank 715 | contemporary (source published 1990/1993) | — | — | dictionary | n/a | verified | Radical 扌64, Jōyō grade 5. Original/primitive sense flagged explicitly as "beckon (with the hand), call" with the extended "invite" sense derived from it — same original-meaning-vs-derived-meaning convention seen throughout this dictionary's entries. |
| 暖 (entry 1011, DAN/atataka(i), SKIP 1-4-9) | warm | kanji (adjective) | core | Freq rank 1189 | contemporary (source published 1990/1993) | — | — | dictionary | n/a | verified | Radical 日72, Jōyō grade 6. Four distinct kun readings given (atataka, atatakai, atatakaru, atatameru) plus a non-approved reading marked with a dagger (非/▲ symbol per the book's abbreviation key). Carries an explicit boxed USAGE note distinguishing 暖かい atatakai (weather/temperature sense) from the near-homophonous 温かい atatakai (feeling/atmosphere sense) — flagged by the book itself as "easily confused by Japanese and foreigners alike." |
| 慈 (entry 2339, JI/itsuku(shimu), SKIP 2-3-10) | affectionate | kanji (adjective/verb stem) | core | Freq rank 1705 | contemporary (source published 1990/1993) | — | — | dictionary | n/a | verified | Radical 心61, Jōyō grade. Sense ② explicitly marked [Buddhism]: "compassion, active benevolence, universal love, loving kindness" (慈悲 jihi "mercy, compassion"; 慈善 jizen "charity") — one of several entries in this dictionary that carry an explicit religious/doctrinal register tag inline with the ordinary sense breakdown. |
| 銭 (entry 1725, SEN/zeni, SKIP 1-8-6) | money | kanji (noun) | core | Freq rank 1052 | contemporary (source published 1990/1993) | — | — | dictionary | n/a | verified | Radical 金167, Jōyō grade 5. Sense ③ is a historical-currency sense explicitly dated: "sen: monetary unit equiv. to 1/100 of a yen" and an obsolete sub-sense "(b) former monetary unit equiv. to 1/1000 of a kan (貫)" — one of the few entries in the sample carrying genuine historical/monetary attested-era content, though per the column rules this is reported as source content rather than promoted into the Attested Era field (the book's dating is of the referent currency unit, not of word usage). |
| 厭 (entry 3017, EN/iya, SKIP 3-2-12) | disagreeable, averse | kanji (adjective/verb stem) | core | Freq — (field blank in source; Grade marked "Reference," i.e. non-Jōyō) | contemporary (source published 1990/1993) | — | — | dictionary | n/a | verified | Radical 厂27. Explicit example of a non-Jōyō "Reference"-grade entry (as opposed to the Jōyō/Jinmei/Names grades seen in the other sampled entries) — the dictionary's own grade-tier system, distinct from this project's Usage Tier taxonomy; recorded here descriptively. Compound note states the character is "now usu." written with a different, more common kanji (嫌な iya na) for its main modern adjectival use. |
| 匿/區/雇 etc. (entries 3012–3016, cross-reference and handwritten-abbreviation entries, SKIP 2-9/2-10) | conceal / district / hire (abbreviated handwritten forms) | kanji (cross-reference only) | core | — | contemporary (source published 1990/1993) | — | — | dictionary | n/a | plausible_unverified | A run of auxiliary (non-main) entries on a single sampled page, illustrating the dictionary's cross-reference apparatus: "incorrect stroke count ⇒ see [pattern]" redirects (e.g. 道/運 etc. → pattern 3-9), "incorrect classification ⇒ see [entry]" redirects (e.g. 脣 → 2739, flagged as nonstandard for 唇 2737), and "handwritten abbreviation for [entry]" entries (質 → 2808, 區 "nonstandard for" 区 2963, 匿 "nonstandard for" 匿 3011) — confirms the main entry-numbering sequence interleaves full entries with these three auxiliary types rather than numbering them separately. |
| 采 (entry 3555, bare radical entry, SKIP 4-7-3) | *(primitive only: "separate/nogome")* | kanji radical/primitive element | core | — | contemporary (source published 1990/1993) | — | — | dictionary | n/a | verified | Radical 165. Bare-radical entry format: standard form + one named variant (釆 nogomehen, used as a left-side component) + a one-line "used in characters related to separating" description, with zero compounds/readings of its own — structurally the NTC-dictionary analog of the "unnumbered primitive" entries seen in the Heisig sample (021). |

### Grammar points

*(As with the Heisig sample, this source's "grammar points" are its own organizational/pedagogical
system rather than Japanese grammar — paraphrased above under "The SKIP indexing system," "The
Atomic Theory of Chinese Characters," "Entry-format architecture," and "Homophone-discrimination and
kun-homophone features.")*

---

## Source 2: The Kodansha Kanji Learner's Dictionary

**Source:** Jack Halpern (compiler, credited on the title page under the punning kanji rendering of
his name, 春遍雀來, read "Harupen Jakku"), *The Kodansha Kanji Learner's Dictionary* (講談社漢英学習字典),
Kodansha International Ltd./Kodansha America, Inc., First Edition 1999, New Edition 2001, copyright
© 1999 by Jack Halpern, ISBN 978-4-7700-2855-6. Publication assisted by a grant from the Japan
Foundation. 1,054 DjVu pages total. Source file: `source_reference/languages/Japanese/07.Dictionaries,
Phrasebooks/The Kodansha Kanji Learners Dictionary.djvu`.

**Explicitly stated relationship to Source 1 (non-redundant-supplement scoping applied):** this
book's own front matter states directly — "The Kodansha Kanji Learner's Dictionary is based on the
New Japanese-English Character Dictionary, copyright © Jack Halpern, published by Kenkyusha Limited
in 1990 (available outside Japan from NTC)." Both share the same SKIP indexing system (reproduced
here as an identical 4-pattern chart — confirmed by direct visual comparison of the sampled chart
pages from both sources), the same compiler, and overlapping editorial-staff credits (confirmed via
this book's own "Editorial Staff" page, which separately lists "Editorial Consultants for the
Original Work" dated to the 1990 NJECD). **Per the project's non-redundant-supplement rule, the SKIP
system and Atomic Theory are not re-described here** (see Source 1 above) — this section instead
focuses only on what is genuinely new in this condensed "Learner's" edition: its different (smaller,
non-Jōyō-"Reference"-grade-aware) entry count and compound-selection philosophy, its added
cross-reference columns (NJECD entry number, Unicode codepoint, a distinct "level and ranking"
field), and its two-color (red/black) typographic convention for core meanings.

**Coverage note — representative sample of a 1,054-page learner-oriented condensation.** Sampled: the
title/copyright page (confirming the NJECD relationship, edition history, and Japan Foundation grant
credit); the Foreword (explaining the dictionary's own stated rationale: frequent compounds with the
entry character in *any* position, not just initial position, unlike most kanji dictionaries); the
Explanatory Chart (a fully-worked, color-coded entry-layout diagram keyed to guide section numbers);
the System of Kanji Indexing by Patterns chart (confirmed identical in structure/content to the NTC
source's version); the Editorial Staff page; and nine main entries spread across the character-number
sequence (0023–0025, 1258–1260, 2209–2211) chosen to show the Jōyō grade range (Jōyō-2 through
Jōyō-6) plus one "Names"-grade (non-Jōyō) literary entry.

### Entry-format differences from the NJECD (Source 1)

The Explanatory Chart (p. 31a sampled, worked example: 生 entry 2179) shows a reference-data box with
**more fields than the NJECD's equivalent box**: alongside Radical/Grade/Strokes/Kuten (the same
fields as Source 1), this dictionary adds an explicit **"NJECD entry number"** column (direct
cross-reference back to Source 1's own entry numbering — confirmed in the sampled entries, e.g. 加
entry 0023 cross-references NJECD K1835, 氷 entry 0024 cross-references K4125) and a **Unicode
codepoint** column (e.g. U52A0 for 加, U6C37 for 氷) — a cross-reference layer the 1993 NJECD edition,
predating widespread Unicode adoption in consumer dictionaries, does not carry. The "level and
ranking" field (labeled distinctly from Grade in the chart, e.g. "A0150"/"S5-2-3" codes visible in
the sampled entries) is a third ranking system not otherwise explained in the sampled front matter —
recorded here descriptively since its exact derivation wasn't confirmed within the representative
sample's scope. The Foreword's own stated design rationale (p. 11a) is to deliberately include
compounds with the entry character in a *non-initial* position when pedagogically useful — its own
example: most kanji dictionaries list only a few compounds under 話 "speak; story" and omit 電話
denwa "telephone" (電 'electricity' + 話) and 実話 jitsuwa "true story" (実 'true' + 話) because 話 appears
second, not first, in both — a gap this dictionary states it deliberately closes.

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 加 (entry 0023, KA/kuwaeru, SKIP 1-2-3) | add | kanji (verb stem) | core | — (level/ranking code A0150; Kuten S5-2-3) | contemporary (source published 1999/2001) | — | — | dictionary | n/a | verified | Radical 力19, Jōyō grade 4, NJECD cross-ref K1835, Unicode U52A0. Three numbered senses (add/append; affect/influence/inflict; join/participate) each with its own compound sub-list; both transitive 【kuwaeru 加える】"add, include" and intransitive 【kuwawaru 加わる】"join in, participate" kun readings given with the transitivity explicitly marked (vt/vi). |
| 氷 (entry 0024, HYŌ/kōri, SKIP 1-2-3) | ice | kanji (noun) | core | — (level/ranking code C1542) | contemporary (source published 1999/2001) | — | — | dictionary | n/a | verified | Radical 水85, Jōyō grade 3, NJECD K4125, Unicode U6C37. Carries an explicit boxed NOTE disambiguating from the visually similar 永 "eternal" (entry 1230) — the Kodansha-edition analog of the NJECD's "do not confuse with" cross-reference convention. Two separate kun readings given (kōri and hi), the second limited to compounds like 氷雨 hisame "elegant hail; chilly rain (esp. in autumn)" — an unusually literary/seasonal register gloss for a Jōyō-3 (early-elementary-level) character. |
| 以 (entry 0025, I/mot(te), SKIP 1-2-3) | to the...of; by means of | kanji (grammatical/functional) | core | — (level/ranking code A0144) | contemporary (source published 1999/2001) | — | — | dictionary | n/a | verified | Radical 人9, Jōyō grade 4, NJECD K1642. Explicitly glossed as a "directional preposition placed before localizers to indicate the point of reference" (以東 itō "to the east of, eastward") — one of the few sampled entries whose core meaning is grammatical/functional rather than lexical-semantic, confirming the dictionary covers function-word kanji with the same entry format as content-word kanji. |
| 市 (entry 1258, SHI/ichi, SKIP 2-2-3) | city; market | kanji (noun) | core | — (level/ranking code A0049) | contemporary (source published 1999/2001) | — | — | dictionary | n/a | verified | Radical 巾50, Jōyō grade 2, NJECD K2752, Unicode U5E02. Two independently-derived senses under one character (city/municipality vs. market/fair) with distinct compound families for each, plus a 【HOMOPHONES】box for both kun readings (tatsu-family and tateru-family verbs cross-referenced to other entries) carried over from the 2-3 pattern-group page header. |
| 令 (entry 1259, REI, SKIP 2-2-3) | command | kanji (noun/prefix) | core | — (level/ranking code B0844) | contemporary (source published 1999/2001) | — | — | dictionary | n/a | verified | Radical 人9, Jōyō grade 4, NJECD K4665. Entry-head data includes three decorative/archaic kun-style given-name readings (yoshi, ryō, nori) marked with the 图 "name reading" symbol per the Explanatory Chart's key — distinguishing ordinary kun/on readings from name-only readings within the same entry-head line. |
| 写 (entry 1260, SHA/utsu(su), SKIP 2-2-3) | copy | kanji (verb stem) | core | — (level/ranking code B0647) | contemporary (source published 1999/2001) | — | — | dictionary | n/a | verified | Radical 冖14 (marked with a caret/△ indicating a non-standard radical-assignment flag per the book's abbreviations), Jōyō grade 3, NJECD K2844. |
| 甫 (entry 2209, HO/FU, haji(mete), SKIP 4-7-3) | barely | kanji (adjective, literary/archaic) | literary | — (level/ranking "Names" grade; Kuten S7-5-2) | contemporary (source published 1999/2001); cited usage example itself archaic/classical register | — | — | dictionary | n/a | verified | Radical 用101, Grade marked "Names" (non-Jōyō, name-kanji only) rather than a numbered Jōyō grade — direct Kodansha-edition parallel to the NJECD's "Reference" grade tag. Explicitly marked 【literary】on its sole kun reading, with a cited classical-register example sentence ("Waga yowai wa hajimete kokonotsu naru ni," glossed "I was barely nine years old") — one of the few entries in either sampled dictionary carrying an attested archaic/classical usage example rather than a modern one. |
| 求 (entry 2210, KYŪ/motomeru, SKIP 4-7-3) | seek | kanji (verb stem) | core | — (level/ranking code A0245; Kuten S7-5-2) | contemporary (source published 1999/2001) | — | — | dictionary | n/a | verified | Radical 水85, Jōyō grade 4, NJECD K2165. Two numbered senses (seek/pursue/search for vs. request/demand), each with compound sub-lists; kun entry explicitly glossed with a parenthetical scope note "(go in search of) SEEK (for), search, pursue; wish for, desire" showing the dictionary's convention of bracketed disambiguating glosses alongside the bolded core meaning. |
| 来 (entry 2211, RAI/ku(ru), SKIP 4-7-3) | come | kanji (verb stem) | core | — (level/ranking code A0130) | contemporary (source published 1999/2001) | — | — | dictionary | n/a | verified | Radical 木75 (marked △, non-standard radical-assignment flag), Jōyō grade 2, NJECD K4572. Two numbered senses (physical "come/arrive" vs. temporal "the coming, the next, the future") — the temporal sense's compounds (来年 rainen "next year," 未来 mirai "future") show kanji-level semantic extension from spatial to temporal deixis, a pattern noted without further grammatical analysis here since this is a dictionary entry, not a grammar reference. |

### Grammar points

*(As with Source 1, this book's substantive "grammar points" are its own entry-format/cross-reference
conventions, paraphrased above under "Entry-format differences from the NJECD" — repeating the SKIP-
system and Atomic-Theory explanations from Source 1 would be redundant, per this file's stated
non-redundant-supplement scoping.)*
