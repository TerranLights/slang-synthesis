# English — Established Vocabulary/Grammar: CMOS Ch. 11, "Foreign Languages," pt. 6 (§§11.117–11.140: closing Hebrew note; Russian transliteration, capitalization, titles, punctuation, and word division; South Asian special characters; Classical Greek transliteration, typesetting, breathing/accent marks, punctuation, numbers, and word division)

**Source:** *The Chicago Manual of Style*, 16th edition (University of Chicago Press, 2010), Chapter
11, "Foreign Languages," PDF pp. 1479–1502.

**Coverage note:** This chunk continues the multi-part split of Chapter 11 (`041_..._pt06.md`), picking
up mid-way through the "Languages Usually Transliterated (or Romanized)" subsection. It opens on the
tail end of Hebrew (§11.117, "A note on Hebrew vowels" — a single short section; the fuller Hebrew
treatment, §§11.113–11.116 covering Hebrew special characters, capitalization, word division, and
unromanized phrases, falls in an earlier part not covered here), then covers Russian in full
(§§11.118–11.128: transliteration systems, capitalization, titles, quotations/dialogue, suspension
points, dash usage, and five word-division rules), South Asian languages' special characters
(§11.129), and Classical Greek through the end of its two-or-more-consonants word-division rule
(§§11.130–11.140: transliteration, typesetting, breathing marks, accent marks, unaccented words,
vowels, punctuation, numbers, and the first three of Greek's word-division rules). The range ends
cleanly at the close of §11.140; Greek's remaining word-division rule (§11.141, compound words) and
the start of Old and Middle English (§11.142 onward) belong to the next part.

Per dispatch instruction, Attested Era is "contemporary (source published 2010)" and Attested Region
is "American English (United States)" throughout; Source Type is `grammar_reference`; Transcription
Confidence is `n/a` throughout (reference-book extraction); Vision Reading Confidence is `n/a`
throughout (the source has a genuine clean text layer — no page in this range required true
vision-reading as a fallback). No handwritten marginalia was present anywhere in this range.

**Mojibake gotcha, confirmed repeatedly in this chunk exactly as flagged in the dispatch — including
one instance precise enough to verify by byte arithmetic.** This chunk's subject matter (Russian and
Greek transliteration/typesetting detail) is as dense with non-ASCII characters as pt01's, and the
same UTF-8-bytes-decoded-as-Latin-1 pattern recurred:

- `radio-priyÃ«mnik` (§11.127, a compound-word division example) → **radio-priyëmnik**. Byte check:
  `Ã«` = Latin-1 bytes C3 AB, which as UTF-8 decode to U+00EB (ë) — a clean, confident decode,
  consistent with the "linguistic"-style transliteration (diacritics permitted) the surrounding prose
  itself describes at §11.118.
- `naÃ¯f` (§11.133, the French comparison example for diaeresis) → **naïf**. Byte check: `Ã¯` = Latin-1
  bytes C3 AF → UTF-8 decode U+00EF (ï). Same mechanism as pt01's already-documented `führer` example.
- `Â«Bozhe, bozhe, bozhe!>> govorit Boris.` and the surrounding prose `guillemets (Â« >>)` (§11.121) →
  **«Bozhe, bozhe, bozhe!» govorit Boris.** / **guillemets (« »)**. Byte check: `Â«` = Latin-1 bytes C2
  AB → UTF-8 decode U+00AB (left guillemet «), the exact same pattern pt01 already documented for
  §11.4. As in that earlier instance, the *right* guillemet mojibake-decodes incompletely — it renders
  as a literal `>>` rather than legible mojibake for » — read with reasonable confidence from context
  (the sentence is explicitly about guillemets functioning as a quotation-mark pair) rather than a
  clean 1:1 byte decode.
- `oxia (á¿½)` (§11.133, naming the Greek acute-accent mark) → **oxia (´)**, i.e., U+1FFD GREEK OXIA.
  This one is verifiable by exact byte arithmetic rather than just contextual guessing: U+1FFD encodes
  in UTF-8 as the three bytes E1 BF BD, and decoding those same three bytes as Latin-1 individually
  gives exactly á (E1), ¿ (BF), ½ (BD) — i.e., precisely the garbled string visible on the page. The
  fact that the byte math reproduces the observed mojibake exactly, independent of context, is about as
  confident as a decode can get without a hex dump in hand.
- `varia (á¿ˆ)` (§11.133, naming the Greek grave-accent mark) → almost certainly **varia (`)**, i.e.,
  U+1FEF GREEK VARIA, by the same mechanism (UTF-8 bytes E1 BF AF, which Latin-1-decode to á, ¿, and
  U+00AF MACRON — a thin horizontal mark that a cramped parenthetical rendering could plausibly be
  misread as a small raised `ˆ`-like glyph). Flagged `low_confidence` on the *exact* third character
  specifically — the visual read of that one glyph is less certain than the oxia case above — but the
  semantic identity (this names the grave accent) is unambiguous from the surrounding prose itself,
  independent of the mojibake question.
- `(~or^)` (§11.133, describing the circumflex's two possible shapes) is read as **(˜ or ˆ)** — a
  small tilde and a small modifier-circumflex glyph rendered without surrounding spaces, not a
  byte-substitution cipher in the Â-prefixed sense above, just two narrow free-floating spacing-modifier
  characters compressed against the word "or" by the page's text extraction. `plausible_unverified`.
- `(l‡)` (§11.136, naming the single mark Greek uses for both colon and semicolon) — genuinely
  **not** confidently recoverable as a specific character in this pass; flagged `low_confidence` and
  left undecoded rather than guessed, per the spec's explicit instruction for this case. The prose
  itself is unambiguous (a single midlevel dot serves double duty for colon and semicolon), so the
  grammar point below states that plainly; only the precise glyph is in doubt.

All vocabulary-table rows and grammar-point prose below reflect the corrected forms where a decode was
made; none of the garbled forms is reproduced as if authoritative.

---

## Vocabulary

CMOS is a style/usage reference, not a vocabulary-teaching text. This chunk's "vocabulary" is the
specialized terminology English-language publishing uses for Russian transliteration/typesetting and
for Classical Greek transliteration, accentuation, and punctuation — the chapter's own technical
apparatus, not a foreign-language lexicon in the ordinary sense. All entries below: Attested Era
`contemporary (source published 2010)`, Attested Region `American English (United States)`, Source
Type `grammar_reference`, Transcription Confidence `n/a`, Vision Reading Confidence `n/a`, unless
noted.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| United States Board on Geographic Names (USBGN) system | the Russian-transliteration system Chicago recommends for general-audience use, as opposed to the diacritic/ligature-heavy "linguistic" system | proper noun | technical.publishing | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.118; the chapter's remaining Russian word-division rules (§§11.124–11.128) are explicitly adapted from this same system |
| "linguistic" transliteration system | the Russian-transliteration system preferred by journals of Slavic studies, making free use of diacritics and ligatures; contrasted with USBGN | noun phrase | technical.publishing | — | contemporary (source published 2010) | American English (United States) | transnational | grammar_reference | n/a | n/a | §11.118; CMOS advises avoiding diacritics/ligatures in general-audience works even though this system permits them |
| ligature | a typographic character combining two letterforms into one glyph; cited (with diacritics) as a feature of the "linguistic" Russian-transliteration system that general-audience works should avoid | noun | technical.publishing | — | contemporary (source published 2010) | American English (United States) | transnational | grammar_reference | n/a | n/a | §11.118; not separately defined in the chapter's earlier general-rules section (§11.12), which only names it in passing alongside diacritics — this is its first standalone mention |
| kursiv | the Russian-language term for italic type; original Cyrillic typesetting uses it more sparingly than English italics and never for book titles, unlike transliterated Russian titles (which do take italics) | noun | technical.publishing | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.120; a transliterated Russian word appearing directly in CMOS's own prose, distinct from the generic "roman type"/"italic type" pair already defined in pt01 |
| suspension points | CMOS's term for ellipsis points as used in Russian to mark interruptions or breaks in thought, following the French convention; an exclamation point or question mark may substitute for one dot in the original, though English publications may regularize this to three plain dots | noun phrase | technical.publishing | — | contemporary (source published 2010) | American English (United States) | transnational | grammar_reference | n/a | n/a | §11.122 |
| oxia | the Greek-language name for the acute accent mark (one of three Greek accent marks) | noun | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | transnational | grammar_reference | n/a | n/a | §11.133; see mojibake note above — this is the verified-by-byte-arithmetic decode |
| varia | the Greek-language name for the grave accent mark | noun | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | transnational | grammar_reference | n/a | low_confidence | §11.133; see mojibake note above — semantic identity certain from context, exact mojibake glyph less certain |
| perispomeni (circumflex) | the Greek-language name for the circumflex accent, rendered either tilde-shaped or rounded depending on typeface; occurs only on one of a word's last two syllables | noun | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | transnational | grammar_reference | n/a | plausible_unverified | §11.133; see mojibake note above on the "(˜ or ˆ)" shape description |
| dasia (rough breathing) | the Greek term for the rough-breathing mark; transliterated as an "h" preceding the affected vowel/diphthong, or following the letter rho (as in English "rhythm") | noun | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | transnational | grammar_reference | n/a | n/a | §§11.130, 11.132; one of two breathing marks every initial vowel, diphthong, or rho must carry when Greek is set in the Greek alphabet |
| psili (smooth breathing) | the Greek term for the smooth-breathing mark; not transliterated at all, since it represents only the absence of the "h" sound | noun | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | transnational | grammar_reference | n/a | n/a | §11.132 |
| proclitics | short, monosyllabic Greek words — forms of the definite article, certain prepositions, certain conjunctions, and the negative adverb — that attach closely to the following word and carry no accent of their own | noun | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | transnational | grammar_reference | n/a | n/a | §11.134; one of two named exceptions to "every Greek word carries an accent" |
| enclitics | short Greek words pronounced as if part of the preceding word; they usually lose their own accent, and under certain conditions cause the preceding word to gain a second accent | noun | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | transnational | grammar_reference | n/a | n/a | §11.134; the second named exception alongside proclitics |
| iota subscript | a small iota written beneath certain long vowels in ancient Greek; transliterated as an "i" on the line, following the vowel it is attached to | noun phrase | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | transnational | grammar_reference | n/a | n/a | §11.130 |
| stigma, koppa, sampi | three obsolete Greek letters retained solely as numerals (respectively 6, 90, and 900) alongside the ordinary alphabet when Greek numbers are written out in letters | noun | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | transnational | grammar_reference | n/a | n/a | §11.137 |
| Greek numeral sign / Greek lower numeral sign | two distinct Unicode-defined diacritical marks (U+0374 and U+0375 respectively) that flag a Greek letter-string as a number rather than a word; the first (resembling a prime) marks values under 1,000, the second marks thousands | noun phrase | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | transnational | grammar_reference | n/a | n/a | §11.137; U+0374 is added to a standalone sign or the last sign in a series (ρια′ = 111), U+0375 precedes the first sign of a thousands value (͵α = 1,000) |
| South Asian transliteration diacritics | the set of special diacritic Latin letters (macrons, subscript dots, acutes, tildes, and similar marks on vowels and consonants) needed to transliterate the principal South Asian languages | noun phrase | technical.linguistics.regional | — | contemporary (source published 2010) | American English (United States) | regional | grammar_reference | n/a | plausible_unverified | §11.129; representative forms include Ā/ā (a-macron), Ḍ/ḍ (d with subscript dot), and Ś/ś (s-acute) — the full listed set was not reproduced glyph-for-glyph here, both for copyright reasons and because the small italicized glyphs were hard to render with full fidelity (same caveat pt01 flagged for the Hausa/Albanian rows); CMOS itself notes writers increasingly simplify this set in practice (substituting "sh" for various s-sounds, omitting subscript dots and macrons) |
| diaeresis (Greek usage) | a mark placed over the second of two successive vowels to indicate they are voiced separately rather than forming a diphthong, appearing in transliteration whenever present in the Greek original | noun | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | transnational | grammar_reference | n/a | n/a | §11.133; CMOS illustrates the same function with the French example naïf — see mojibake note above |
| midlevel dot (Greek colon/semicolon mark) | the single punctuation mark that represents both the colon and the semicolon in Greek, as opposed to English's two distinct marks | noun phrase | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | transnational | grammar_reference | n/a | low_confidence | §11.136; the specific glyph rendered illegibly in this extraction pass — see mojibake note above; the question mark is instead represented by a semicolon, and the apostrophe doubles as an elision mark |

---

## Grammar points

### A note on Hebrew vowels (§11.117)

Most Hebrew vowels are not separate letters but marks attached to the (mostly consonantal) letters of
the Hebrew alphabet, along with dots that modify how certain consonants are pronounced. These vowel
and pronunciation marks rarely appear in ordinary printed Hebrew text; CMOS names prayer books, printed
Bibles, and poetry as the main genres where they do show up.

### Russian transliteration (§11.118)

CMOS summarizes the many systems for transliterating Russian (in its own Table 11.3) by contrasting
two poles: the "linguistic" system preferred by journals of Slavic studies, which makes free use of
diacritics and ligatures, versus plain general-audience use, where CMOS recommends avoiding both and
instead following the United States Board on Geographic Names (USBGN) system. Regardless of which
transliteration system a given work otherwise follows, CMOS directs that proper-name spellings
default to whatever *Merriam-Webster's Biographical Dictionary* and *Merriam-Webster's Geographical
Dictionary* already use — the chapter's example list includes a monarch's name, an author's name, a
river, a city, a composer's name, and a city name with two accepted spellings, illustrating that this
override applies across different categories of proper noun, not just place names.

### Russian capitalization (§11.119)

Russian capitalization conventions in Cyrillic closely resemble French (cf. §11.9's general "most
languages capitalize less than English" rule) and should be preserved as-is in transliteration:
pronouns, days of the week, months, and most proper adjectives are lowercased. Geographic designations
are capitalized specifically when they refer to formal institutions or political units, and lowercased
otherwise — CMOS's examples contrast a capitalized provincial-government unit against a lowercase
rural-administrative term, and a capitalized university name against a lowercase generic noun phrase
("a Russian composer").

### Titles of Russian works (§11.120)

Only a title's first word and any proper nouns within it are capitalized — the same sentence-style
rule already established generally at §11.3. CMOS adds a typographic note specific to Russian: in the
original Cyrillic, titles are set in ordinary (non-italic) type, and Cyrillic *kursiv* (italic) is used
more sparingly than English italics and never for book titles. In transliteration, however, italic
should be used for book titles as it would be for any other language under §11.5's general rule.

### Russian quotations and dialogue (§11.121)

Russian generally follows French practice (cross-referenced to the chapter's general punctuation
rules) in using guillemets for dialogue and quoted material, and dashes to introduce dialogue lines —
CMOS's example shows four successive dialogue turns each introduced by a leading dash with no
attribution. Guillemets may also be used, as in French, to set off a quotation nested within a speech.

### Russian suspension points (§11.122)

Suspension points (ellipsis points) function as in French, marking an interruption or break in
thought. A Russian-specific wrinkle: an exclamation point or question mark often stands in for one of
the three dots in the original — CMOS's example shows an exclamation point immediately followed by two
literal dots. English-language publications may choose to regularize this pattern to a plain run of
three dots instead.

### Russian uses of the dash (§11.123)

Two distinct uses are given. First, a dash with a space on either side may stand in for an omitted
form of "is"/"are" between a subject and its complement (CMOS's example translates roughly as "Moscow
— [is] the capital of Russia"). Second, a dash (again spaced) may replace a verb omitted because it
would otherwise repeat a verb already used earlier in the same sentence — CMOS's example has two
subjects performing two different implied actions, the second introduced only by the dash where the
verb would have been identical to the first.

### Russian word division — general (§11.124)

Transliterated Russian should be divided following the word-division rules of the Cyrillic original,
not generic English line-break conventions. The specific rules that follow (§§11.125–11.128) are
adapted from the transliteration system of the United States Board on Geographic Names.

### Combinations not to be divided in Cyrillic transliteration (§11.125)

Letter combinations that together transliterate a single Cyrillic letter — CMOS lists *ch*, *kh*, *sh*,
*shch*, *ts*, *ya*, *ye*, *yo*, *yu*, and *zh* — should never be split across a line break, since
splitting them would misrepresent a single underlying letter as two. The same rule applies to a vowel
followed by a short *i* (transliterated *y*, representing the Cyrillic "yod" glyph): combinations like
*ay*, *ey*, and *yey* must likewise stay together.

### Division between Russian consonants (§11.126)

Ordinarily, words may be divided between two single consonants or between a consonant and a following
consonant cluster. CMOS then lists a substantial set of consonant combinations that are *not* normally
divided (including *bl*, *br*, *dr*, *fl*, *gl*, *kr*, *pl*, *skr*, *str*, *tr*, *vl*, *zhd*, among
others) — these may still be split, but only where they straddle the boundary between a prefix and a
root (or a similar morpheme boundary), illustrated with a prefix-plus-root example.

### Division of Russian words after prefixes or between parts (§11.127)

A word may be divided immediately after a prefix, but the prefix itself should not be split internally
— illustrated with five short prefixed examples. Separately, compound words should be divided at the
boundary between their component parts, illustrated with three examples including the already-noted
"radio-priyëmnik" mojibake case (see note above).

### Division of Russian words after vowel or diphthong (§11.128)

A word may be divided after a vowel or diphthong, immediately before a single following (Cyrillic)
consonant — illustrated with four short examples, one of them a transliterated proper name (a Soviet
leader's surname). Division after a vowel is also permitted before a consonant *combination*, not just
a single consonant, illustrated with four further examples.

### South Asian special characters (§11.129)

Transliterating the principal South Asian languages draws on a substantial set of special diacritic
Latin letters (cross-referenced to the chapter's own Table 11.2) — see the vocabulary entry above for
representative forms; the full set was not reproduced verbatim here. CMOS notes a real and increasing
countertrend, however: writers working with South Asian languages are moving toward a simplified style
that drops diacritics altogether — substituting plain "sh" for the various transliterated s-sounds,
omitting the subscript dots marking dental consonants, and leaving out macrons entirely.

### Transliterating Greek (§11.130)

Isolated Greek words and phrases, in works not specifically about ancient Greece, are usually
transliterated rather than set in the Greek alphabet (CMOS's own master reference for this is Table
11.4, giving the Greek alphabet with Unicode numbers alongside corresponding Latin letters). All Greek
accents are dropped in transliteration. A macron distinguishes the long vowels eta and omega from the
short vowels epsilon and omicron. The iota subscript is transliterated as an on-the-line "i" following
its vowel. Rough breathing becomes an "h" preceding the vowel/diphthong (or following rho, as in
English "rhythm"); smooth breathing is simply dropped, since it marks only the absence of that "h"
sound. A diaeresis in the Greek original carries over into the transliteration. Transliterated Greek is
normally italicized, unless the same word/phrase recurs often enough that CMOS allows italicizing only
at first mention and setting it in roman thereafter.

### Typesetting Greek (§11.131)

When Greek itself (not a transliteration) must be presented, authors should use a Unicode-enabled font
wherever possible (cross-referenced to §11.2's general Unicode guidance). Publishers must ensure a
Greek font is actually available for the final publication; Greek type sometimes needs to be set at a
slightly different point size than the surrounding type to visually match it. Extra white space is
occasionally needed wherever a vowel carries more than one diacritic at once.

### Greek breathing marks (§11.132)

When Greek is set in its own alphabet, every initial vowel, diphthong, or rho must carry a breathing
mark — either rough (dasia) or smooth (psili). The mark sits over the initial lowercase vowel (or the
second vowel of a diphthong), and to the left of a capital letter. CMOS notes a specific typesetting
pitfall: an ordinary single quotation mark cannot substitute visually for a breathing mark, because it
is the wrong size and does not sit close enough to the letter it modifies.

### Greek accent marks (§11.133)

Three accent marks exist: acute (oxia), circumflex (perispomeni — tilde-shaped or rounded depending on
typeface), and grave (varia); see the mojibake note above for the specific decoded forms. Accents occur
only over vowels. The circumflex is restricted to one of a word's last two syllables; the grave occurs
only on the very last syllable. Like breathing marks, accents sit over lowercase vowels (over a
diphthong's second vowel) and to the left of capital vowels. A diaeresis indicates that two successive
vowels are voiced separately rather than forming a diphthong — CMOS draws the direct parallel to French
"naïf" (see mojibake note above).

### Unaccented Greek words (§11.134)

With two exceptions, every Greek word carries an accent — usually one, occasionally two. The first
exception is proclitics: short monosyllabic words (forms of the definite article, certain prepositions,
certain conjunctions, and the negative adverb) that attach closely to the word following them. The
second exception is enclitics: short words pronounced as if part of the *preceding* word; enclitics
usually lose their own accent, and in certain circumstances cause the word before them to pick up a
second accent.

### Greek vowels (§11.135)

Every vowel-plus-breathing-plus-accent combination is treated as a baseline requirement for any Greek
publishing font — CMOS specifies this explicitly for lowercase and uppercase eta as a representative
case, implying the same completeness for the other six vowels. Scholarly work dealing with ancient
manuscripts or papyri may require additional symbols beyond this baseline, for which CMOS directs
readers to consult current Unicode character charts for the Greek alphabets.

### Greek punctuation (§11.136)

Greek punctuation diverges from English in three ways: the period and comma are identical to their
English counterparts, but the colon and semicolon are both represented by a single midlevel dot (see
mojibake note above on the exact glyph); the question mark is represented by what looks almost like a
semicolon; and the apostrophe, which closely resembles a smooth-breathing mark, doubles as an elision
mark when a word's final vowel is dropped before a following vowel-initial word. A final rule governs
English-language context specifically: quoted Greek-alphabet words or passages, however long, should
not be enclosed in quotation marks when appearing within English text.

### Greek numbers (§11.137)

When not spelled out, Greek numbers are represented using the ordinary alphabet's letters, supplemented
by three obsolete letters retained purely as numerals (stigma = 6, koppa = 90, sampi = 900). A
diacritical mark resembling a prime (Unicode's Greek numeral sign, U+0374) distinguishes a letter
sequence as a number; it is appended to a standalone numeral sign or to the last sign in a multi-letter
sequence — CMOS's example shows a three-letter sequence reading as 111. Thousands use a different,
Unicode-defined mark (the Greek lower numeral sign, U+0375), illustrated with three further examples
reading as 1,000, 1,111, and 2,222 respectively; CMOS's own Table 11.5 is the fuller reference.

### Greek word division — consecutive vowels (§11.138)

Diphthongs (CMOS lists nine two-letter combinations) are never divided across a line break. Two
consecutive vowels that do *not* form a diphthong, however, are divided — illustrated with four short
examples.

### Greek word division — single consonants (§11.139)

When a single consonant falls between two vowels, the word is divided immediately before that
consonant — illustrated with five short examples.

### Greek word division — two or more consonants (§11.140)

Three sub-rules are given. First, a doubled consonant, or a mute consonant immediately followed by its
corresponding aspirate (CMOS lists six such mute-plus-aspirate pairs), is divided after the first
consonant of the pair — illustrated with two examples. Second, when a consonant cluster of two or more
begins with a liquid or a nasal, the division falls after that liquid/nasal — illustrated with one
example, plus a named exception for a specific nasal-plus-consonant sequence that divides differently.
Third, every other two-or-more-consonant combination simply *follows* the normal division point rather
than being split itself — illustrated with seven further examples covering a range of cluster types.
This range ends here; Greek's remaining word-division rule (§11.141, governing compound words) belongs
to the next part of this split.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes, dialogue
blocks, or explanatory passages. All illustrative examples above are drawn selectively (one or a
handful per rule) from CMOS's own fuller example lists, which in several sections (word-division rules
especially) ran to five or more drill-style items each; the remainder were treated as the coverage
rule's "repeated drill" category and not individually reproduced.
