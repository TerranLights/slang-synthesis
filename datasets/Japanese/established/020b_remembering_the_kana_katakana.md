# Japanese — Remembering the Kana, Part 2: Katakana

**Source:** James W. Heisig, Helmut Morsbach, and Kazue Kurebayashi, *Remembering the Kana: A
guide to reading and writing the Japanese syllabaries in 3 hours each* — Part Two: Katakana. Japan
Publications Trading Co., Ltd. PDF metadata (`pdfinfo`) dates the file to 2005 (same publisher and
year as the Hiragana part); no separate printed copyright-page year was found in the scanned pages
actually read, so "contemporary (source published 2005)" below is inferred from file metadata per
the spec's allowance, not a printed colophon date. Note the author byline order differs slightly
from Part One's cover (Morsbach/Kurebayashi/Heisig vs. Heisig/Morsbach/Kurebayashi on the title
page) — both are the same three-author team.

**Pages covered:** all 75 PDF pages of the Katakana part (full book) were rendered and inspected;
the 46 base katakana (PDF pages 7–46, printed pages 1–46) and the three shared diacritic/length
marks (PDF pages 47–49, printed pages 47–49: voiced mark, plosive/semi-voiced mark, long vowel
mark) were vision-read in full as the book's distinctive mnemonic content. The back matter (Lessons
1–6 spaced-repetition re-teaching pages, Afterword, Alphabetic List of the Kana, Table of
Diphthongs, Table of the Kana) was sampled and confirmed to be pure combinatorial/index restatement
of the same 46 symbols plus their already-tabulated voiced/semi-voiced/extended-digraph forms — no
new mnemonic content — consistent with how `020`'s Hiragana extraction treated its own equivalent
back matter.

**Relationship to established/001 (Henshall & Takagaki, *A Guide to Learning Hiragana and
Katakana*) and 020 (Heisig Part 1, Hiragana):** `001`/`001b`/`001c`/`001d` already extracted the
full katakana phonological inventory from a different author's textbook, and this is the second
Heisig-authored Remembering-the-Kana file in this project (the first, `020`, covered Part One). Per
the project's "non-redundant supplement" rule, this file captures a *second, independent* author
treatment's specific mnemonic imagery for each katakana symbol — the content that is new here is
Heisig/Morsbach/Kurebayashi's own invented story/image per character (e.g. "a bowl of noodles" for
ヌ *nu*, "a naval disaster" for ネ *ne*), which neither `001` nor `020` contains (`020` covers only
the hiragana half of this same book).

## Vision-reading note

This PDF has no usable text layer (`pdftotext -layout` returns empty output on every page checked)
— the entire book was vision-read from rendered page images (`pdftoppm -r 130`). No handwritten
marginalia was found anywhere in this copy; all content below is genuinely typeset book content.

**Page-offset gotcha, consistent with the project's standing PDF-offset warning:** like `020`'s
Hiragana part, this book uses a "programmed learning" branching page order (each entry carries its
own internal printed page number distinct from the physical PDF page, with a "GO TO PAGE N" footer
link for spaced-repetition navigation). The physical PDF-to-printed-page offset for the 46 main
entries plus the 3 diacritic-mark pages is a flat **+6** (PDF page = printed page + 6, verified at
10+ sample points from printed page 1 through printed page 49), which is a *different* constant
from Part One's own +9 offset — confirming the spec's warning that an offset must be re-verified per
source rather than assumed to carry over, even between two parts of the same physical book. The
offset **breaks down past printed page 49** (entering the back-matter "Lessons" section) exactly as
Part One's own note anticipated: printed page 53 (start of Lesson 1) lands at PDF page 59, not the
naively-expected 59 — this actually still matches +6 at that specific point, but by the Afterword
(printed 68) the correspondence had drifted to PDF page 72 (+4), and the Alphabetic List (printed
69) to PDF page 73 (+4), while the Table of Diphthongs (printed 70) landed at PDF page 74 (+4) and
the Table of the Kana (printed 71) at PDF page 73 — i.e., the offset is not even monotonically
consistent across the last few back-matter pages, confirming this part of the book should never be
located by arithmetic alone.

## Vocabulary — the 46 basic katakana + 3 diacritic/length marks

All entries below are Source Type `grammar_reference`, Transcription Confidence `n/a` (vision-read,
no text layer), Attested Era `contemporary (source published 2005)`, Attested Region `—`,
Geographic Scope `—`, Usage Tier `core`, Weight/Frequency `—` unless noted. Vision Reading
Confidence is `verified` for every row below (each katakana form was legible, clearly printed, and
cross-checked against its own practice-stroke diagram and loanword examples on the same page).

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| ア (a) | vowel sound "a" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 阿. Mnemonic: the final stroke stretches into a long "arm," pictographically a bent elbow with a kimono sleeve dangling from it. |
| イ (i) | vowel sound "i" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 伊. Mnemonic: same as the Roman letter "i," with the hiragana's dot lengthened into a short stroke since katakana use no dots. |
| ウ (u) | vowel sound "u" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 宇. Mnemonic: a *chawan* (tea bowl, the shared ウ/ワ base shape) with something "oozing" in drop by drop from the ceiling — "ooze = chawan + a drop from above." |
| エ (e) | vowel sound "e" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 江. Mnemonic: the "air" filling the space between heaven and earth (the two horizontal strokes), with the vertical stroke indicating the filling. |
| オ (o) | vowel sound "o" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 於. Mnemonic: taught as a couplet with ホ (ho) — オ is ホ with the final stroke dropped, reflecting that "o" lacks ho's aspirated "h" sound. |
| カ (ka) | syllable "ka" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 加. Mnemonic: the hiragana か with its final rightward stroke dropped — "the easiest way to do it." |
| キ (ki) | syllable "ki" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 幾. Mnemonic: the hiragana き simplified by dropping its last stroke, exactly as with カ. |
| ク (ku) | syllable "ku" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 久. Mnemonic: associates sound "ku" with "scoop" — an ice-cream scoop dropping vanilla ice cream into a bowl of rice. |
| ケ (ke) | syllable "ke" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 介. Mnemonic: a postbox's top opening all the way up to "take the cake" mailed by an aunt for a birthday. |
| コ (ko) | syllable "ko" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 己. Mnemonic: draw the hiragana こ's cursive flow first, then square the second stroke into a "corner" for the block katakana form. |
| サ (sa) | syllable "sa" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 散. Mnemonic: the Biblical story of King Solomon and the two feuding mothers — the king's arm (1st stroke) holds an infant (2nd stroke) threatening to cut it in half, with the final stroke being wise old King Solomon himself. |
| シ (shi) | syllable "shi" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 之. Mnemonic: formed virtually the same as ツ (tsu), differing only in position/direction — learn as a pair with ツ. |
| ス (su) | syllable "su" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 須. Mnemonic: continues the "bowl" image (shared with ヌ/ワ/ラ) as a bowl of soup, with the final dropping stroke as its carrying handle. |
| セ (se) | syllable "se" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 世. Mnemonic: the hiragana せ with its second stroke dropped; explicitly notes the "hook" runs down in katakana vs. up in hiragana. |
| ソ (so) | syllable "so" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 曽. Mnemonic: as with キ and カ, simply the hiragana's final stroke dropped. |
| タ (ta) | syllable "ta" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 多. Mnemonic: the ク "ice-cream scoop" shape with a little "towel" stuck to the side — used to wipe the ice cream off one's face. |
| チ (chi) | syllable "chi" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 千 ("1,000"). Mnemonic: ties to the word for 1,000 as in Chiba Prefecture ("1,000 leaves") and sumō wrestler Chiyonofūji. Example word ナチ (*nachi*) glossed in the source itself as "nazi," a loanword. |
| ツ (tsu) | syllable "tsu" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 川. Mnemonic: break the single flowing hiragana つ stroke into the "broken line" first two strokes, then straighten the final stroke. |
| テ (te) | syllable "te" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 天. Mnemonic: nationally used as the postal symbol 〒; pictured as a U.S. rural postbox reaching out to "take the post," final stroke swinging left (unlike the straight postal symbol). |
| ト (to) | syllable "to" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 止. Mnemonic: a "tow-rope" (the horizontal stroke) pulling something (the vertical stroke). |
| ナ (na) | syllable "na" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 奈. Mnemonic: the hiragana な missing its final 2 strokes, with the first two strokes repositioned down and to the center. |
| ニ (ni) | syllable "ni" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 二 ("2"). Mnemonic: written exactly like the kanji for the number 2 (also read *ni*), stripped of brush-cursive trace into block form. |
| ヌ (nu) | syllable "nu" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 奴. Mnemonic: the recurring "bowl" shape holding noodles, with the final stroke as a single noodle dangling out and slipping from the side. |
| ネ (ne) | syllable "ne" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 祢. Mnemonic: described by the book as "possibly the most difficult" katakana — a 4-stroke "naval disaster" story: the captain (stroke 1) stands on the ship's brow (stroke 2), an underwater reef (stroke 3) causes the ship to break into pieces (stroke 4). |
| ノ (no) | syllable "no" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 乃. Mnemonic: the first stroke of hiragana の, doubling as the diagonal slash of a "No Smoking"/"No Parking" sign. |
| ハ (ha) | syllable "ha" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 八 ("8"). Mnemonic: *ha* is the first syllable of *hachi* ("8"), written exactly as the kanji for 8, squared off. |
| ヒ (hi) | syllable "hi" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 比. Mnemonic: the "heel" of a shoe, matching the same heel-of-a-shoe imagery `020` recorded for the hiragana ひ. |
| フ (fu) | syllable "fu" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 不. Mnemonic: a mirror image of ウ's "bowl of food," intentionally left visually blank until the viewer's imagination "fills in" the bowl. |
| ヘ (he) | syllable "he" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 部. Explicitly flagged by the book as the *only* katakana that is visually identical to its hiragana equivalent in most typefaces — confirms the cross-reference `020` made from the hiragana side. |
| ホ (ho) | syllable "ho" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 保. Mnemonic: "Home Sweet Home" cross-stitched in a frame — the katakana is one of the little decorative criss-crosses in the design, with two extra strokes at the bottom. |
| マ (ma) | syllable "ma" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 万. Mnemonic: commonly confused with ム (mu) — taught by drawing the hiragana ま once, then quickly drawing マ before "the feelings leave the tip of your pencil." |
| ミ (mi) | syllable "mi" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 三 ("3"). Mnemonic: written from the kanji for 3 (*mi*/*mittsu*), the same numeral appearing in the Mitsubishi (三菱, "three diamonds") brand name, which the book cites directly. |
| ム (mu) | syllable "mu" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 牟. Mnemonic: draw hiragana む first, then immediately follow with ム, since both share the same final-stroke flow. |
| メ (me) | syllable "me" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 女 ("woman") — shared kanji origin with hiragana め, as `020` also noted from the hiragana side. Mnemonic: drawing the hiragana's second stroke alone leads the hand directly into the katakana stroke order. |
| モ (mo) | syllable "mo" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 毛. Noted by the book as easy to learn despite looking quite different from hiragana も; can be decomposed as the hiragana し plus the katakana ニ. |
| ヤ (ya) | syllable "ya" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 也. Mnemonic: as with セ, the second stroke of hiragana や is dropped for the simplified katakana form. |
| ユ (yu) | syllable "yu" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 由. Mnemonic: a "U-boat," with the first stroke as its periscope sticking up out of the ocean's surface (second stroke). |
| ヨ (yo) | syllable "yo" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 與. Mnemonic: a crude drawing of a "yoke" of two oxen — draw circles between the prongs to see the ox-heads, then erase them. |
| ラ (ra) | syllable "ra" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 良. Mnemonic: the recurring "bowl" filled to overflowing with *rāmen* noodles — eat the whole bowl in imagination to get to "ra" (unlengthened, unlike *rāmen* itself). |
| リ (ri) | syllable "ri" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 利. Mnemonic: nearly identical to hiragana り, but with no connecting line between the two downward strokes — katakana are block letters, no cursive flow. |
| ル (ru) | syllable "ru" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 流. Mnemonic: Rumpelstiltskin — the dwarf's pointed-shoe foot (right side) and the peg-leg driven into the ground in anger (left side) after his name was discovered. |
| レ (re) | syllable "re" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 礼. Mnemonic: the right half of ル — a one-legged creature hopping/racing along, continuing the Rumpelstiltskin-adjacent imagery. |
| ロ (ro) | syllable "ro" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 呂. Mnemonic: a mass of fish eggs/"roe," square rather than round because katakana square off all rounded shapes. |
| ワ (wa) | syllable "wa" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 和. Mnemonic: the recurring "bowl" as a tea-bowl (*chawan*) with a little red arrow painted on it showing where to put one's lips to drink. |
| ヲ (wo/o) | particle-only syllable, direct-object marker, pronounced "o" in modern speech | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 乎. Mnemonic: "Woe is me!" — a great crack runs through the middle of one's only bowl of food. Mirrors `020`'s own "woe"/cracked-bowl imagery recorded for hiragana を, confirming the two authors reuse the same core pun. |
| ン (n) | syllabic nasal "n" | kana (syllabogram) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Derived from kanji 尓. The only katakana with no vowel component; the book has the reader derive it themselves from hiragana ん via the "dot and straight line" transformation, the same technique `020` cross-referenced from the hiragana side. |
| ﾞ (voiced mark / dakuten) | marks a voiced consonant (k→g, s→z, t→d, h→b) | diacritic | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Identical in hiragana and katakana, written last after the base kana shape; book defers the full combinatorial table to the "Table of Diphthongs" (printed p. 70) rather than giving each voiced syllable its own mnemonic. |
| ﾟ (plosive/semi-voiced mark / handakuten) | marks the p-sound on the h-row (h→p) | diacritic | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Identical in hiragana and katakana, written last; same deferred-combinatorial treatment as the voiced mark. |
| ー (long vowel mark / chōonpu) | lengthens the preceding vowel sound | diacritic | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Katakana-specific mechanism with no hiragana equivalent: hiragana lengthens a vowel by writing an extra vowel kana (e.g. すもう), while katakana add a dash the length of one full character after the vowel instead (e.g. リリー *riri*). This is new content relative to `020`, which never needed to cover this since it is exclusive to katakana's loanword-transcription role. |

## Grammar/structural points

### Mnemonic method and shared kanji-derivation technique
Like `020`'s Hiragana coverage, each katakana entry pairs (1) the kanji the symbol historically
derives from, boxed beside the hiragana equivalent at the top of the entry page, and (2) an
invented English-language story/image. A number of these stories explicitly reuse recurring motifs
across several katakana as a deliberate mnemonic device: a "bowl" shape recurs across ウ, フ, ス, ヌ,
ワ, and ラ (bowl of food → bowl of soup → bowl of noodles → tea-bowl → bowl of rāmen), and the
dwarf-with-a-peg-leg image from Rumpelstiltschen spans both ル and レ (the latter explicitly built
as "the right half of ル"). This deliberate motif-chaining across multiple characters is a technique
not seen called out explicitly in `020`'s own Hiragana notes, though the hiragana part does share
one of the same bowl-based images (ふ).

### Katakana-specific loanword framing
Nearly every entry's example-word pair is a foreign loanword transliterated into katakana (e.g. エレ
ベーター *erebētā* "elevator," サラリーマン *sarariman* "salaried man," コカコーラ *Kokakōra* "Coca-
Cola"), reflecting katakana's real-world function for transcribing foreign words, proper nouns, and
onomatopoeia — distinct from `020`'s hiragana part, whose own illustrative examples, as that file's
notes already flagged, were themselves mostly katakana-script loanwords used as pronunciation aids.

### Long vowel mark (chōonpu) — katakana's own distinct length-marking convention
Documented above in the vocabulary table as its own row: unlike hiragana, which lengthens a vowel
by writing a second vowel kana, katakana use a dedicated dash-shaped mark (ー) the length of one
character, placed after the vowel to be lengthened. This is genuinely new content relative to `020`,
since the mechanism doesn't exist in the hiragana writing system at all.

### Voiced mark (dakuten) and plosive/semi-voiced mark (handakuten)
As in `020`'s treatment of the hiragana side, both diacritics are explained as shared, identically-
written marks across hiragana and katakana, always added as the final stroke(s) after the base kana
shape is complete. The book again defers the full combinatorial table (all k/s/t/h-row voiced and
p-row forms, plus the full set of katakana-only extended digraphs used for representing foreign
sounds not native to Japanese, e.g. ヴァ/ヴィ/ヴ/ヴェ/ヴォ for "va/vi/vu/ve/vo," ティ/ディ for "ti/di",
ファ/フィ/フェ/フォ for "fa/fi/fe/fo") to the "Table of Diphthongs" appendix (printed page 70) rather
than giving each form its own individual mnemonic — consistent with the "bounded, compact character
set" framing of this dispatch: the distinctive content worth extracting is the 46 base-katakana
mnemonics plus the three shared/distinct diacritic-mark mechanics, not a re-derivation of the full
extended inventory (which 001/001b/001c already table out from a different source, and which this
book's own appendix tables restate combinatorially without new mnemonic content).

### Branching "programmed learning" page structure
As in `020`, documented here as a structural/pedagogical feature rather than new content: the book's
"GO TO PAGE N" footer links implement a self-testing spaced-repetition order distinct from the
dictionary (a-i-u-e-o) order the physical pages are printed in. The 6 numbered "Lessons" (printed
pages 53–65) walk the reader through this non-sequential order in planned stages (Lesson 1 starts
with katakana that visually resemble their hiragana counterparts; Lesson 6, the last, covers 9
katakana "that fall into no particular group" and have no relation to hiragana at all) — this
staging logic was inspected and confirmed to be pure re-sequencing of the same 46 entries, not new
mnemonic content, so it was not separately extracted entry-by-entry.

## Coverage note

All 46 base katakana entries plus the voiced-mark, plosive-mark, and long-vowel-mark explanatory
pages (49 total entries) were vision-read in full — this is the entirety of the book's distinct
teaching content. The remaining ~26 pages (Introduction, the 6 "Lessons" spaced-repetition re-visits
of the same 46 entries in a different order, the Afterword, the Alphabetic List of the Kana, the
Table of Diphthongs, and the Table of the Kana) were sampled directly and confirmed to be pure
combinatorial restatement, cross-reference indexing, or motivational/pedagogical framing text with
no new mnemonic content, consistent with how `020` treated the equivalent back matter in Part One.
No handwritten marginalia was found anywhere in this copy.
