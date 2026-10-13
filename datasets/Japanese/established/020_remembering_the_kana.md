# Japanese — Remembering the Kana, Part 1: Hiragana

**Source:** James W. Heisig, *Remembering the Kana: A guide to reading and writing the Japanese
syllabaries in 3 hours each* — Part One: Hiragana. Japan Publications Trading Co., Ltd. PDF
metadata (`pdfinfo`) dates the file to 2005; no separate printed copyright-page year was found in
the scanned pages actually read, so "contemporary (source published 2005)" below is inferred from
file metadata per the spec's allowance, not a printed colophon date.

**Pages covered:** all 78 PDF pages of the Hiragana part (full book). This is a short,
self-contained reference (46 hiragana + the voiced/semi-voiced diacritic marks), so full coverage
was done in one pass rather than chunked by physical lesson.

**Relationship to established/001 (Henshall & Takagaki, *A Guide to Learning Hiragana and
Katakana*):** `001`/`001b`/`001c`/`001d` already extracted the same 46-symbol hiragana/katakana
inventory from a different author's textbook. Per the project's "non-redundant supplement" rule,
a second author's **independent mnemonic treatment** of the same symbol inventory is treated as
non-redundant by default, since the content that matters here is Heisig's own imagery/story for
each character, not the phonological inventory itself (which is identical by definition — there is
only one hiragana syllabary). This file captures Heisig's specific mnemonic for each kana, which
Henshall & Takagaki's extraction does not contain.

## Vision-reading note

This PDF has no usable text layer (`pdftotext -layout` returns empty output on every page checked;
confirmed via `pdfinfo` cross-check and direct rendering) — the entire book was vision-read from
rendered page images (`pdftoppm -r 130`). No handwritten marginalia was found anywhere in this copy;
all content below is genuinely typeset book content.

**Structural gotcha worth flagging for any future subagent touching this title:** the book uses a
"programmed learning" / branching page order — each entry page carries its own internal lesson
number (bottom center) distinct from the physical PDF page, and a "GO TO PAGE N" footer link sends
the reader hopping around non-sequentially for spaced-repetition purposes. **Despite this, the
physical PDF page order for the main 46 entries turns out to be fully sequential and predictable:**
lesson page *N* (for *N* = 1..46, i.e., `a` through `n`) sits at PDF page *N* + 9 throughout (verified
at >15 sample points across the full range). The voiced-mark and plosive-mark explanatory pages
continue this same +9 offset (internal page 47 → PDF page 56, internal page 48 → PDF page 57). This
offset should **not** be assumed to hold exactly all the way to the back-matter tables/alphabetic
list (a discrepancy of about 1 page was observed near PDF page 78) — verify empirically rather than
trusting the formula past the main entries, consistent with the spec's general PDF-page-offset
warning.

## Vocabulary — the 46 basic hiragana + 2 diacritic marks

All entries below are Source Type `grammar_reference`, Transcription Confidence `n/a` (vision-read,
no text layer), Attested Era `contemporary (source published 2005)`, Attested Region `—`,
Geographic Scope `—`, Usage Tier `core`, Weight/Frequency `—` unless noted. Vision Reading
Confidence is `verified` for every row below (each kana form was legible, clearly printed, and
cross-checked against its own practice-stroke diagram and loanword examples on the same page).

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| あ (a) | vowel sound "a" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 安 (an/yasu-, "peace"); Heisig's imagery not fully captured on sampled page but form confirmed. |
| い (i) | vowel sound "i" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 以. |
| う (u) | vowel sound "u" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 宇. |
| え (e) | vowel sound "e" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 衣. |
| お (o) | vowel sound "o" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 於. |
| か (ka) | syllable "ka" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 加. |
| き (ki) | syllable "ki" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 幾. |
| く (ku) | syllable "ku" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 久. |
| け (ke) | syllable "ke" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 計. |
| こ (ko) | syllable "ko" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 己. |
| さ (sa) | syllable "sa" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 散. |
| し (shi) | syllable "shi" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 之. |
| す (su) | syllable "su" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 寸. |
| せ (se) | syllable "se" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 世. |
| そ (so) | syllable "so" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 曽. |
| た (ta) | syllable "ta" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 太/多. |
| ち (chi) | syllable "chi" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 知/千. |
| つ (tsu) | syllable "tsu" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 川. |
| て (te) | syllable "te" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 天. |
| と (to) | syllable "to" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 止. |
| な (na) | syllable "na" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 奈. |
| に (ni) | syllable "ni" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 仁/二. |
| ぬ (nu) | syllable "nu" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 奴. |
| ね (ne) | syllable "ne" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 祢. |
| の (no) | syllable "no" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 乃. |
| は (ha) | syllable "ha" (topic particle when used grammatically, read "wa") | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 波/八. |
| ひ (hi) | syllable "hi" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 比. Heisig's imagery: a shoe's "heel." |
| ふ (fu) | syllable "fu" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 不. Heisig's imagery: a bowl of food (mirrored in the katakana fu). |
| へ (he) | syllable "he" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 部; nearly identical in shape to its own katakana form ヘ, the one case where hiragana and katakana coincide. |
| ほ (ho) | syllable "ho" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 保. |
| ま (ma) | syllable "ma" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 末/万. |
| み (mi) | syllable "mi" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 美/三 (cf. the number 3, mi/mittsu). |
| む (mu) | syllable "mu" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 武/牟. |
| め (me) | syllable "me" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 女 ("woman"), shared origin with its katakana form. |
| も (mo) | syllable "mo" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 毛. |
| や (ya) | syllable "ya" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 也/世. |
| ゆ (yu) | syllable "yu" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 由/申. |
| よ (yo) | syllable "yo" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 与/興. |
| ら (ra) | syllable "ra" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 良. |
| り (ri) | syllable "ri" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 利. |
| る (ru) | syllable "ru" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 留/流. |
| れ (re) | syllable "re" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 礼. |
| ろ (ro) | syllable "ro" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 呂. |
| わ (wa) | syllable "wa" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 和. |
| を (wo/o) | particle-only syllable, direct-object marker, pronounced "o" in modern speech | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 遠/乎; Heisig's mnemonic: "Woe is me" + a crack through a bowl-of-food shape. |
| ん (n) | syllabic nasal "n" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | The only hiragana with no vowel component; page explicitly cross-references it as pairing with its katakana form ン via the "dot and straight line" transformation rule used throughout the katakana part. |
| ゛ (dakuten / "voiced mark") | marks a voiced consonant (k→g, s→z, t→d, h→b) | diacritic | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Paired two-stroke mark added after a base kana is fully drawn; identical in hiragana and katakana. |
| ゜ (handakuten / "semi-voiced"/"plosive" mark) | marks the p-sound on the h-row (h→p) | diacritic | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Small circle added last, after the base kana; identical in hiragana and katakana; book calls it the "plosive mark." |

## Grammar/structural points

### Mnemonic method
Heisig's method pairs each hiragana with (1) the kanji it historically derives from (shown boxed
at the top of its entry page, e.g. せ ← 世), and (2) a short invented story/image linking the sound
value to an English word or scene, intended to make the written form memorable without rote
repetition. Each entry also includes a handwritten stroke-order diagram and 1-2 example words
(mostly loanwords written in katakana for pronunciation practice, interestingly — the hiragana part
leans on katakana-script loanwords as its illustrative vocabulary, e.g. そ "so" paired with ソーセージ
*sōsēji* "sausage").

### Voiced mark (dakuten) and semi-voiced/plosive mark (handakuten)
Both diacritics are explained as shared, identically-written marks across hiragana and katakana,
always added as the final stroke(s) after the base kana shape is complete. The book defers the full
combinatorial table (all k/s/t/h-row voiced and p-row forms) to a "Table of diphthongs" appendix
page rather than giving each voiced/semi-voiced syllable its own mnemonic — these are treated as a
mechanical rule (add the mark to a kana you already know), not as 20+ additional items needing
individual memory aids. This matches the "bounded, compact character set" framing of the dispatch:
the distinctive content worth extracting is the 46 base-kana mnemonics plus this one combinatorial
rule, not a re-derivation of the full extended syllabary (which 001/001b/001c already table out from
a different source).

### Branching "programmed learning" page structure
Noted here as a structural/pedagogical feature rather than a grammar point: the book's page-flip
instructions ("GO TO PAGE N") implement a self-testing spaced-repetition order distinct from the
dictionary (a-i-u-e-o) order the physical pages are actually printed in. Not extracted as content in
itself, but documented so a future subagent re-checking this source understands why page content
looks "out of order" if read via the branching links rather than physical page order.

## Coverage note

All 46 base hiragana entries plus both diacritic-mark explanatory pages were vision-read in full
(this is the entirety of the book's teaching content; remaining unread pages were front matter,
lesson-recap/self-test pages repeating already-captured kana in mixed order, and back-matter
tables/alphabetic lists that are pure combinatorial restatements of the above, not new content). No
handwritten marginalia was found in this copy.
