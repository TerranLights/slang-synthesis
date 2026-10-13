# Japanese — Established Vocabulary/Grammar: Writing System — Kanji Mnemonics via Primitive Elements (Curated Sample)

**Source:** James W. Heisig, *Remembering the Kanji I: A Complete Course on How Not to Forget the
Meaning and Writing of Japanese Characters*, Japan Publications Trading Co., Ltd. (1st ed. 1977;
this printing: 4th edition, September 2001), 522 pages total, ISBN 4-88996-075-9. Source file:
`source_reference/languages/Japanese/02.Japanese Writing System/Remembering the Kanji 1.pdf`.

**Coverage note — representative curated sample, not exhaustive.** This is a 522-page dictionary-
style reference covering 2,042 characters (the ~1,945 Jōyō general-use kanji plus ~60 proper-name
kanji and a handful of convenience primitives), organized as one numbered "frame" per character,
sequenced across 56 lessons in three parts of increasing terseness (Part One "Stories," Lessons
1–12, full narrative mnemonics; Part Two "Plots," Lessons 13–19, skeletal mnemonic outlines; Part
Three "Elements," Lessons 20–56, key word + primitives only, no narrative). Per the project's rule
for oversized dictionary-like references, this was sampled broadly across the frame-number
progression (1 through 2042) rather than transcribing all ~2,042 entries. The book's own
Introduction and "Note to the 4th Edition" (its full stated methodology) were read in full rather
than sampled, since this is relatively short prose and is the book's single most valuable
non-redundant contribution to the corpus — no other kanji reference in this project uses a
primitive-element/imaginative-story method.

**Distinctiveness check performed:** grepped all prior `established/` Japanese files for "Heisig,"
"imaginative memory," and "primitive element" — zero hits. The closest-sounding prior source,
`003_guide_to_remembering_japanese_characters.md` (Henshall's *A Guide to Remembering Japanese
Characters*), is a different author using a wholly different method (on/kun readings, compound-word
examples, historical/etymological paragraphs, one mnemonic sentence per entry) — not a primitive-
element composition system, no reuse of earlier characters as named building blocks the way Heisig's
method does. No redundancy found; this book's coverage is independently valuable.

**PDF extraction gotcha — kanji-specific font-substitution cipher on an otherwise-clean text
layer.** `pdftotext` confirmed a genuine, complete text layer for this PDF (all English prose
extracts perfectly), but **every kanji glyph — both the large frame-display character and inline
parenthetical cross-references in running prose — decodes to an unrelated Latin/symbol glyph**
(e.g. frame 1 "one" 一 extracts as `s`; the zodiac cross-reference list "rat (子), tiger (寅)..."
extracts as "rat ({), tiger (¨)..."). This is a fixed per-glyph substitution in the book's custom
display font, not random OCR garbling, but no quick arithmetic offset was found (unlike the
Korean/CJK offset-cipher cases documented in the extraction spec) and decoding it character-by-character
across 2,042 frames was out of scope for a representative sample. **Resolution used here: every
kanji character recorded below was recovered by rendering the exact PDF page to a PNG image
(`pdftoppm -r 150`) and reading the glyph directly** — i.e., vision-confirmed against the actual
typeset page, not inferred from the cipher text or from memory alone. Page-to-frame correspondence
was verified empirically (book page = PDF page − 2, confirmed at three widely-separated points)
rather than assumed. No handwritten marginalia was found on any rendered page — this PDF appears to
be a clean digital-print scan, not a used/annotated copy.

---

## Vocabulary

Each row is one kanji frame: frame number, Heisig's English key word, stroke count, and the
primitive elements the book composes it from (per its own stated mnemonic). Frames are drawn from
four widely-spaced points in the book's 1–2042 frame sequence to show the method working at
different stages: Lesson 1 frames 1–11 (the simplest pictographs/numerals, Part One, full story
style), Lesson 10 frames 195–199 (the "tree" primitive family — a clean illustration of primitive
reuse/compounding), Lesson 25 frames ~795–818 (the "bone" (歹) primitive family, Part Two "plot"
style — terse single-line mnemonics), and Lesson 56 frames 2038–2042 (the book's final five frames,
Part Three "elements" style — key word + primitives only, no prose at all).

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 一 (frame 1, 1 stroke) | one | kanji (numeral) | core | — | contemporary (source published 1977/2001) | — | — | dictionary | n/a | verified | Primitive meaning (starred note): when used as a building-block in other kanji, discards "one" and means *floor* (if below another primitive) or *ceiling* (if above). |
| 二 (frame 2, 2 strokes) | two | kanji (numeral) | core | — | contemporary (source published 1977/2001) | — | — | dictionary | n/a | verified | Simple reduplication of the "one" stroke; no starred primitive-meaning note given. |
| 三 (frame 3, 3 strokes) | three | kanji (numeral) | core | — | contemporary (source published 1977/2001) | — | — | dictionary | n/a | verified | Triples the "one" stroke; book frames the mnemonic as "1 + 2 = 3" (一 + 二 = 三). |
| 四 (frame 4, 5 strokes) | four | kanji (numeral) | core | — | contemporary (source published 1977/2001) | — | — | dictionary | n/a | verified | Composed of primitives *mouth* 口 + *human legs* 儿 (both introduced as primitives in later frames); story deferred since the keyword is assumed already known. |
| 五 (frame 5, 4 strokes) | five | kanji (numeral) | core | — | contemporary (source published 1977/2001) | — | — | dictionary | n/a | verified | Primitive composition deferred, same as frame 4. |
| 六 (frame 6, 4 strokes) | six | kanji (numeral) | core | — | contemporary (source published 1977/2001) | — | — | dictionary | n/a | verified | Primitives named as *top hat* + *animal legs*; composition deferred to a later lesson. |
| 七 (frame 7, 2 strokes) | seven | kanji (numeral) | core | — | contemporary (source published 1977/2001) | — | — | dictionary | n/a | verified | Distinguished from *spoon* 匕 (frame 444) by the first stroke "cutting through" the second rather than stopping short. Starred primitive meaning: *diced* ("cut" into little pieces), linked forward to the kanji for *cut* 切 (frame 85). |
| 八 (frame 8, 2 strokes) | eight | kanji (numeral) | core | — | contemporary (source published 1977/2001) | — | — | dictionary | n/a | verified | Mnemonic likens the two diverging strokes to the "lazy 8" (∞) infinity symbol → associated meaning "all-encompassing" expanse. |
| 九 (frame 9, 2 strokes) | nine | kanji (numeral) | core | — | contemporary (source published 1977/2001) | — | — | dictionary | n/a | verified | Distinguished by stroke order from *power* 力 (frame 858). Starred primitive meaning: *baseball team*/*baseball* (derived from nine players per team). |
| 十 (frame 10, 2 strokes) | ten | kanji (numeral) | core | — | contemporary (source published 1977/2001) | — | — | dictionary | n/a | verified | Mnemonic: rotate 45° and it resembles the Roman numeral X. Starred primitive meaning: sometimes keeps *ten*, sometimes becomes *needle* (from 針, frame 274). |
| 口 (frame 11, 3 strokes) | mouth | kanji (noun) | core | — | contemporary (source published 1977/2001) | — | — | dictionary | n/a | verified | Pictograph — a square standing in for a circular opening, since the kanji system has no native circular stroke. Starred primitive meaning: also *mouth*, with suggested flexible imagery (cave entrance, river mouth, bottle opening). |
| 木 (frame 195, 4 strokes) | tree | kanji (noun) | core | — | contemporary (source published 1977/2001) | — | — | dictionary | n/a | verified | Pictograph: trunk (vertical stroke), boughs (horizontal stroke), roots (final two downward strokes). Starred primitive meaning: *tree*/*wood*, or *(wooden) pole* when the final two strokes detach from the trunk. |
| 林 (frame 196, 8 strokes) | grove | kanji (noun) | core | — | contemporary (source published 1977/2001) | — | — | dictionary | n/a | verified | = tree 木 + tree 木 (simple reduplication) — first of the book's "tree-family" compounding chain. |
| 森 (frame 197, 12 strokes) | forest | kanji (noun) | core | — | contemporary (source published 1977/2001) | — | — | dictionary | n/a | verified | = tree 木 + tree 木 + tree 木 ("trees, trees everywhere") — second step of the compounding chain, directly building on frame 196. |
| 桂 (frame 198, 10 strokes) | Japanese Judas-tree | kanji (noun) | core | — | contemporary (source published 1977/2001) | — | — | dictionary | n/a | verified | = tree 木 (left) + a right-hand element the book's story glosses as "ivy growing down branches in the shape of a hangman's rope." Deliberately obscure key word chosen because its oddness aids memorability, per the book's own stated technique. |
| 柏 (frame 199, 9 strokes) | oak | kanji (noun) | core | — | contemporary (source published 1977/2001) | — | — | dictionary | n/a | verified | = tree 木 (left) + white-associated right-hand element; mnemonic story invokes the Roman "golden bough" myth (mistletoe berries on a sacred oak). |
| 歹 (unnumbered primitive, before frame 808, 4 strokes) | *(primitive only: "bone")* | kanji primitive element | core | — | contemporary (source published 1977/2001) | — | — | dictionary | n/a | verified | Marked with the book's star (★) convention for a primitive introduced outside the main numbered sequence. Pictograph of a bone attached to a piece of flesh; first stroke distinguishes it from *evening* 夕 (frame 109). Anchors the "bone family" compounding chain below (frames 808–816). |
| 残 (frame 808, 10 strokes) | remainder | kanji (noun/verb stem) | core | — | contemporary (source published 1977/2001) | — | — | dictionary | n/a | verified | = bone 歹 + (parade) float — Part Two "plot" style, one-line mnemonic only ("Bones . . . (parade) float."). |
| 殉 (frame 809, 10 strokes) | martyrdom | kanji (noun) | core | — | contemporary (source published 1977/2001) | — | — | dictionary | n/a | verified | = bone 歹 + decameron (book's name for the right-hand element) — "Bones . . . decameron." |
| 殊 (frame 810, 10 strokes) | particularly | kanji (adverb) | core | — | contemporary (source published 1977/2001) | — | — | dictionary | n/a | verified | = bone 歹 + vermilion — "Bones . . . vermilion." |
| 殖 (frame 811, 12 strokes) | augment | kanji (verb stem) | core | — | contemporary (source published 1977/2001) | — | — | dictionary | n/a | verified | = bone 歹 + straightaway — "Bones . . . straightaway." |
| 列 (frame 812, 6 strokes) | file (row) | kanji (noun) | core | — | contemporary (source published 1977/2001) | — | — | dictionary | n/a | verified | = bone 歹 + saber (knife radical 刂) — book glosses the key word as people/things lined up in a row. |
| 裂 (frame 813, 12 strokes) | split | kanji (verb stem) | core | — | contemporary (source published 1977/2001) | — | — | dictionary | n/a | verified | = file 列 (frame 812) + garment — demonstrates chaining a just-learned *non-primitive* kanji into the next composition. |
| 烈 (frame 814, 10 strokes) | ardent | kanji (adjective) | core | — | contemporary (source published 1977/2001) | — | — | dictionary | n/a | verified | = file 列 + oven fire (灬) — "File . . . oven fire." |
| 死 (frame 815, 6 strokes) | death | kanji (noun/verb stem) | core | — | contemporary (source published 1977/2001) | — | — | dictionary | n/a | verified | = bone 歹 + spoon 匕 (frame 444) — "Bones . . . spoon." First stroke extended to form a "roof" overhead, per the book's own note. |
| 葬 (frame 816, 12 strokes) | interment | kanji (noun/verb stem) | core | — | contemporary (source published 1977/2001) | — | — | dictionary | n/a | verified | = flowers (艹) + death 死 (frame 815) + two hands — book explicitly cross-references *bury* (frame 179) as a related/contrasting entry. |
| 舛 (unnumbered primitive, before frame 817, 7 strokes) | *(primitive only: "sunglasses")* | kanji primitive element | core | — | contemporary (source published 1977/2001) | — | — | dictionary | n/a | verified | Another star-marked out-of-sequence primitive. Book notes this is the unabbreviated full form of the element seen abbreviated in *measuring box* (frame 42) — left half is *evening* 夕, right half a "completely new shape" assigned the arbitrary meaning "sunglasses." Explicitly flagged by the book as an example of an assigned meaning with no semantic motivation. |
| 耳 (frame 818, 6 strokes) | ear | kanji (noun) | core | — | contemporary (source published 1977/2001) | — | — | dictionary | n/a | verified | Pictograph, noted by the book as visually similar to its pictograph for *eye* but distinguished by stroke order. |
| 丹 (frame 2038, 4 strokes) | cinnabar | kanji (noun) | core | — | contemporary (source published 1977/2001) | — | — | dictionary | n/a | verified | Part Three "elements" style — no prose at all, just key word + stroke count. Cross-referenced one paragraph earlier as the book's own example of a primitive cluster whose parts don't reduce to a meaningful sub-story. |
| 潟 (frame 2039, 15 strokes) | lagoon | kanji (noun) | core | — | contemporary (source published 1977/2001) | — | — | dictionary | n/a | verified | The book explicitly singles out the stroke-cluster inside this character (forming 臼) as "a perfect illustration" of a sub-component that is *not* itself a meaningful character or primitive — a rare moment of the book flagging a limit of its own systematic method. |
| 丑 (frame 2040, 4 strokes) | sign of the cow | kanji (noun) | core | — | contemporary (source published 1977/2001) | — | — | dictionary | n/a | verified | One of the book's closing set of Sino-Japanese zodiac signs (12 total, 9 introduced earlier in the book: rat 子, tiger 寅, dragon 辰, horse 午, ram 未, monkey 申, bird 酉, dog 戌, hog 亥). |
| 卯 (frame 2041, 5 strokes) | sign of the hare | kanji (noun) | core | — | contemporary (source published 1977/2001) | — | — | dictionary | n/a | verified | Zodiac sign, second of the book's final three. |
| 巳 (frame 2042, 3 strokes) | sign of the snake | kanji (noun) | core | — | contemporary (source published 1977/2001) | — | — | dictionary | n/a | verified | **The book's final frame** — the last of 2,042 numbered entries, closing Lesson 56 and Part Three. |

## Grammar points

*(This source has no grammar content — see the book's own stated scope below. These subsections
instead paraphrase its pedagogical/mnemonic method, the content that substitutes for "grammar
points" in a kanji-mnemonic reference.)*

### Explicit scope exclusion

The Introduction states directly (p. 1) that the book will **not** cover how kanji combine into
compounds, how characters are pronounced ("readings"), or any matter of grammatical usage — these
are "matters that need specialized treatment in their own right." The book isolates writing +
meaning only. (This matters for this project: it means Heisig's own key words, not on/kun readings
or compound usage, are the book's unit of comparison against other kanji references in this corpus.)

### Imaginative memory vs. visual memory

The book's central methodological claim (pp. 2–4): ordinary visual memory (the kind used for faces,
landscapes, alphabets) is poorly suited to the kanji because the forms have no connection to
familiar visual experience and are far too numerous and non-phonetic to drill by rote. Heisig
proposes substituting **imaginative memory** — "the faculty to recall images created purely in the
mind, with no actual or remembered visual stimuli behind them," the same faculty used in recalling
dreams — deliberately building invented, often absurd mental "stories" strong enough to fix a
character's form.

### Primitive elements

Defined (p. 4) as a restricted "alphabet" of basic strokes and stroke-combinations — some of which
coincide with traditional radicals, but the set is not limited to the ~224 traditional radicals and
is instead drawn from four classes: (1) basic elements that aren't kanji themselves, (2) kanji that
recur as components of other kanji with high frequency, (3) kanji that change meaning when used as a
component, (4) kanji that change shape when used as a component. Primitives are explicitly
distinguished from radicals, which the book calls an etymological/lexical-ordering convention rather
than a mnemonic-construction one.

### Key words

Each of the 2,042 characters is assigned exactly one English "key word" representing a core meaning,
chosen so no two characters share a key word — deliberately coarser than the full semantic range of
the character, so the learner can later layer in nuance once the base association is fixed. The
book warns against ever substituting one's own key word for its assigned one, since later frames
build compositional stories that depend on the exact wording.

### Three-part course structure

The 56 lessons are deliberately graduated in how much mnemonic scaffolding they provide: **Part One
"Stories"** (Lessons 1–12) gives the full narrative mnemonic for each character; **Part Two
"Plots"** (Lessons 13–19) gives only a skeletal outline of primitives in sequence, requiring the
student to supply their own narrative detail (directly observed in the Lesson 25 "bone family"
sample above — e.g. "Bones . . . spoon." for frame 815); **Part Three "Elements"** (Lessons 20–56,
the bulk of the book, 1,850+ of the 2,042 frames) gives only the key word and the primitive
elements, no narrative at all (directly observed in the Lesson 56 closing frames above).

### Order of learning is load-bearing

The book stresses (pp. 5–6) that its fixed frame sequence is not arbitrary: later characters are
built explicitly from earlier ones treated as primitives, so skipping ahead breaks the compounding
chain the method depends on. It explicitly rejects teaching kanji in frequency order or in the order
Japanese schools use, arguing the mnemonically optimal order is a different ordering altogether.

### A self-acknowledged limit of the method

At frame 2039 ("lagoon," 潟), the book itself flags an exception to its own system: not every
visually identifiable stroke-cluster inside a complex character corresponds to a primitive with a
"specific and useful meaning" — some clusters are just visual residue of a character's evolved form,
and the book says so explicitly rather than forcing an artificial primitive story onto them.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`. All mnemonic "stories"
above are paraphrased/summarized to a few words each (e.g. "Bones . . . spoon") rather than
reproducing Heisig's full narrative paragraphs, and the Introduction/Note-to-4th-Edition content
above is summarized rather than quoted at length.
