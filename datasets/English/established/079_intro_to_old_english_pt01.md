# English — Established Vocabulary/Grammar: Richard Hogg, *An Introduction to Old English*, Ch. 1 "Origins and sources" & Ch. 2 "The basic elements"

**Source:** Richard Hogg, *An Introduction to Old English* (Edinburgh Textbooks on the English
Language, Edinburgh University Press, 2002), Chapter 1 "Origins and sources" (pp. 1–12) and
Chapter 2 "The basic elements" (pp. 13–25).

**Coverage note:** every grammar point and every distinct vocabulary item from these two chapters,
plus the explicit era annotation the source itself carries (this whole book describes Old English,
tagged throughout as `Attested Era: Old English` per the dispatch instruction — a coarse,
whole-book tag, not a per-word date). This source has a confirmed clean PDF text layer (verified
via `pdftotext -layout` and cross-checked against the Read tool's own page rendering). Repeated
drill exercises that don't introduce new vocabulary or grammar are skipped.

**Redundancy check against `076_beginning_old_english`:** the dispatch for this file stated it
should overlap with an already-extracted `076_beginning_old_english` file and apply the
"non-redundant supplement" pattern. **That file does not actually exist anywhere in this repo** —
checked via `find` across the whole `datasets/` tree before starting, and the `established/`
directory has no file numbered 074–079 prior to this one. There is therefore nothing to
deduplicate against; this extraction proceeds as a full, independent first pass, not a trimmed
supplement. **This is in fact the first Old English grammar-reference source extracted into this
project at all** — a future "second Old English book" dispatch should apply the non-redundant
pattern against *this* file's seven parts once it exists.

**Font-cipher finding (important for any future OE vision/text extraction from this source):**
`pdftotext -layout` on this PDF renders the connected-prose Old English example sentences (the
block-quoted analysis passages, e.g. p. 6's *Hwī stande ge hēr ælne dæg ætige?* and p. 12's
exercise sentences) with a **corrupted, non-fixed substitution for þ and ð**: capital `T` and
lowercase `t` both substitute for `Þ`/`þ`, while `E`/`e` substitutes inconsistently for *both* `Þ`
and `ð` depending on position (e.g. raw `pdftotext` output renders *Þā cwæð* as "Tā cwæe" — `T`→Þ,
final `e`→ð — but renders *Þus* as "eus" — initial `e`→Þ). This is a **many-to-one, context-
dependent garble**, not a clean fixed cipher (distinct from the single-letter homoglyph or
fixed-offset ciphers documented elsewhere in the extraction spec) — it only affects the special
display font used for extended connected-text quotations, not the book's ordinary inline Old
English word citations (which render correctly with proper þ/ð/æ/ǣ/ī/ō unicode throughout). **The
Read tool's own page rendering (used for this entire extraction) reads these same passages
correctly** — e.g. it correctly shows *Þā cwæð sēo hāliġe Agnes ðus* and *Đās martyras nǣron
nǣfre on līfe þurh wīf besmitene* — because it is not relying on the PDF's corrupted
ToUnicode/font-substitution table. **Recommendation for any future extraction of this specific
PDF: always read via rendered page images, never trust a raw `pdftotext` pass on the connected-
prose example blocks.** No marginalia (handwritten annotation) was found anywhere in this source;
it is a clean, professionally typeset modern printing.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Englisc | English (the language); OE self-name for the people, *angelcynn* | noun | core | — | Old English | England | national | grammar_reference | n/a | n/a | the settlers' own name for their language, p. 1 |
| angelcynn | "English-kin", the English people's name for themselves by the 7th c. | noun | core | — | Old English | England | national | grammar_reference | n/a | n/a | p. 4 |
| stān | stone | noun (masc., general masculine declension) | core | — | Old English | — | — | grammar_reference | n/a | n/a | the book's first full noun paradigm: nom./acc. stān~stānas, gen. stānes~stāna, dat. stāne~stānum |
| scip | ship | noun (neut., general neuter declension) | core | — | Old English | — | — | grammar_reference | n/a | n/a | near-identical to the masculine paradigm except nom./acc. plural *scipu* |
| guma | man | noun (masc., N-declension) | core | — | Old English | — | — | grammar_reference | n/a | n/a | paradigm guma~guman~guman~gumena~gumum; illustrates why "the man" has two subject/object forms |
| wyrm | serpent, dragon | noun (masc., general masculine) | core | — | Old English | — | — | grammar_reference | n/a | n/a | from the worked example sentence *Se guma slōh þone wyrm* "the man slew the dragon" |
| talu | tale | noun (fem., general feminine declension) | core | — | Old English | — | — | grammar_reference | n/a | n/a | paradigm talu~tale~tale~tale, pl. tala~tala~tala~talum |
| wīfmann | woman | noun (compound, masc.) | core | — | Old English | — | — | grammar_reference | n/a | n/a | grammatically masculine despite denoting a woman, because the head *mann* is masculine; contrasted with *hlæfdiġe* (fem.) and *wīf* (neut.), all three meaning "woman" |
| hlæfdiġe | woman (lady) | noun | core | — | Old English | — | — | grammar_reference | n/a | n/a | feminine-gender "woman" word, paired contrastively with *wīfmann* (masc.) and *wīf* (neut.) |
| wīf | woman | noun | core | — | Old English | — | — | grammar_reference | n/a | n/a | neuter-gender "woman" word — p.17's example of grammatical gender not matching natural (sexual) gender |
| ēare | ear | noun (masc./weak N-declension, rare neuter exception) | core | — | Old English | — | — | grammar_reference | n/a | n/a | one of only two neuter nouns cited in the otherwise mostly-masculine/feminine N-declension |
| ēaġe | eye | noun (N-declension, rare neuter exception) | core | — | Old English | — | — | grammar_reference | n/a | n/a | paired with *ēare* as the N-declension's neuter exceptions |
| se / þæt / sēo / þā | the, that (demonstrative, masc./neut./fem./plural) | demonstrative | core | — | Old English | — | — | grammar_reference | n/a | n/a | full paradigm given p. 19: se/þone/þæs/þǣm (masc.); þæt/þæt/þæs/þǣm (neut.); sēo/þā/þǣre/þǣre (fem.); þā/þā/þāra/þǣm (plural) — no gender distinction in the plural |
| þes / þis / þēos | this (demonstrative, deictic-near) | demonstrative | core | — | Old English | — | — | grammar_reference | n/a | n/a | fully declinable like *se*, but marks nearness where *se* is neutral/distal — explicit OE deixis contrast |
| iċ | I | pronoun (1st sg.) | core | — | Old English | — | — | grammar_reference | n/a | n/a | paradigm iċ/mē/mē/mīn |
| wē | we | pronoun (1st pl.) | core | — | Old English | — | — | grammar_reference | n/a | n/a | paradigm wē/ūs/ūs/ūre |
| wit | we two | pronoun (1st dual) | core | — | Old English | — | — | grammar_reference | n/a | n/a | dual number — a 3rd pronominal number (beyond sg./pl.) marking reference to exactly two people; paradigm wit/unc/unc/uncer |
| þū | thou (you, singular) | pronoun (2nd sg.) | core | — | Old English | — | — | grammar_reference | n/a | n/a | OE singular/plural 2nd-person split is absolute — unlike French *tu*, never used for informal address to a group |
| ġē | ye (you, plural) | pronoun (2nd pl.) | core | — | Old English | — | — | grammar_reference | n/a | n/a | paradigm ġē/ēow/ēow/ēower; PDE *you* descends from this accusative plural, not the nominative *ġē* (→ *ye*) |
| ġit | you two | pronoun (2nd dual) | core | — | Old English | — | — | grammar_reference | n/a | n/a | paradigm ġit/inc/inc/incer |
| hē | he | pronoun (3rd sg. masc.) | core | — | Old English | — | — | grammar_reference | n/a | n/a | paradigm hē/hine/his/him; all 3rd-person forms historically begin with <h>, unlike PDE's Scandinavian-derived *they/them/their* |
| hit | it | pronoun (3rd sg. neut.) | core | — | Old English | — | — | grammar_reference | n/a | n/a | paradigm hit/hit/his/him — identical nom./acc. |
| hēo | she | pronoun (3rd sg. fem.) | core | — | Old English | — | — | grammar_reference | n/a | n/a | paradigm hēo/hī/hire/hire; note accusative = plural *hī* — a real ambiguity the text flags |
| hī / hȳ | they | pronoun (3rd pl.) | core | — | Old English | — | — | grammar_reference | n/a | n/a | paradigm hī/hī/hira/him; replaced in Middle English by the Scandinavian loan *they* |
| hīene / heora / hēom | him / their / to-them (non-Ælfrician variants) | pronoun (variant forms) | regional | — | Old English | Wessex (variant, pre-Ælfrician / Alfredian texts) | regional | grammar_reference | n/a | n/a | p. 22: *hīene* for *hine*, *heora*/*heom* for *hira*/*him* — evidence Old English had no single fixed spelling standard even among educated writers, a **"focussed" rather than standard language** |
| nū | now | adverb | core | — | Old English | — | — | grammar_reference | n/a | n/a | p. 14, cited as the only common way OE marks futurity (no dedicated future tense) |

## Grammar points

### Orthography: Old English letters vs. present-day English spelling
OE used broadly the same alphabet as today but never used `<j, v>` and only rarely `<k, q, x, z>`;
conversely it had letters PDE lacks or barely uses: `<æ, þ, ð>` (and `<ȝ>`/`<ġ>` conventions for a
palatalized g). A standard correspondence table (p. 4): `æ`→a; `c`→c/k/ch; `f`→f/v; `g`→g/y; `s`→s/z;
`þ, ð`→th; `y`→i. Several digraphs also correspond to single PDE sounds: `cg, gg`→dg(e)/gg;
`sc`→sh/sk; `hw`→wh; `hr, hl, hn`→r/l/n. Editors conventionally place a dot over `<c>` and `<g>`
(`ċ, ġ`) to mark the palatal/affricate pronunciation (≈ PDE *ch*, *y*) and distinguish it from the
velar pronunciation (≈ PDE *k*, hard *g*).

### Vowel length and the macron convention
OE spelling itself did not distinguish long and short vowels; modern editors supply a macron (e.g.
*rīsan* "rise" vs. *risan* "risen" [sic, illustrative]) to mark vowel length, since length alone
can be the only distinguishing feature between otherwise-identical words. Four diphthong pairs
existed: `<ēo>`/`<eo>`, `<ēa>`/`<ea>` (long/short pairs), realized roughly as /eːə/~/eə/ and
/æːə/~/æə/ by the late period, with the unstressed second element reduced to schwa.

### The Old English consonant and vowel system (overview)
Voiceless stops /p, t, k/ had no phonemically distinct voiced counterparts for the fricatives —
/f, θ, x/ were voiced **allophonically** ([v, ð, ɣ]) in complementary distribution, voiced only
medially between voiced sounds, voiceless word-initially/finally — the voiced/voiceless fricative
contrast (as in PDE *ferry* vs. *very*) only emerges in Middle English. OE also had **geminate**
(long) consonants contrastively in medial position (*hoppian* "hop" vs. *hopian* "hope"), a
contrast lost from PDE. Seven long and seven short vowels existed, including a front-rounded pair
/yː, y/ (as in German *dünn*) absent from PDE.

### Three fundamental linguistic features of nouns
Noun paradigms encode three obligatory features: **number** (singular/plural), **case**
(nominative=subject, accusative=object as a rule of thumb — refined later), and **gender**
(masculine/neuter/feminine, assigned to every noun, often with no relation to natural/sexual
gender — see *wīfmann*/*hlæfdiġe*/*wīf* above, all "woman" but three different grammatical genders).

### Declension and the major noun classes
A **declension** is the set of nouns sharing one paradigm of case/number endings. The book names
four major OE noun declensions by the shape of their typical member: **General Masculine** (*stān*-
type, ~35% of nouns), **General Neuter** (*scip*-type, ~25%), **General Feminine** (*talu*-type,
~25%), and the **N-declension** (*guma*-type, remainder — contains all three genders but mostly
masculine/feminine, very few neuter). "Minor declensions" (introduced in Ch. 3) are historically
distinct paradigms that are no longer productive but still contain important core words.

### The demonstrative *se* and the definite/indefinite contrast
*Se* functions both as a true demonstrative ("that") and as the nearest OE equivalent to "the" —
but it is fully inflected for case, number, and (except in the plural) gender, unlike PDE's
invariant *the*. Its presence or absence before a noun establishes a **definite vs. indefinite
context** that later (Ch. 3) determines which adjective declension is used. *Þes* "this" is fully
parallel in declension but contrasts with *se* on the axis of **deixis**: *þes* marks nearness,
*se* is neutral/distal — closer to PDE *this* vs. *that* than *se* alone is to *the*.

### The personal pronoun system
First/second person pronouns show no accusative/dative distinction (unlike German's *mich*/*mir*),
a simplification already underway by the OE period. A separate **dual number** existed for first-
and second-person reference to exactly two people (*wit*/*ġit* etc.) — not always used, and already
optional. Third-person pronouns correspond to the three grammatical genders in the singular, with a
single paradigm for the plural; natural (sexual) gender occasionally overrides grammatical gender
even this early, foreshadowing the later shift to natural-gender-only pronoun reference in PDE.

### Word order and case in a simple sentence
Because case (not word position) marks subject vs. object, OE could place either noun phrase
first without changing which one is the subject — *Se guma slōh þone wyrm* "the man slew the
dragon" and *Þone wyrm slōh se guma* mean the same thing, distinguished from *Se wyrm slōh þone
guma* "the dragon slew the man" purely by case marking on the demonstrative, not by position. This
gives OE a freedom of word order (discussed fully in Ch. 7) that case-loss later removed from
English.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`.
