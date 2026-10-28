# English — Established Vocabulary/Grammar: CMOS Ch. 11, "Foreign Languages," pt. 1 (§§11.1–11.20: Overview; Titles and Other Proper Names; Languages Using the Latin Alphabet — general rules through Czech)

**Source:** *The Chicago Manual of Style*, 16th edition (University of Chicago Press, 2010), Chapter
11, "Foreign Languages," PDF pp. 1359–1382 (chapter-opening table of contents plus sections 11.1
through 11.20).

**Coverage note:** This is the start of a multi-part split (`036_..._pt01.md`). This chunk covers the
chapter's Overview (§§11.1–11.2, Scope and organization; Unicode), the "Titles and Other Proper Names"
subsection in full (§§11.3–11.8: capitalization, punctuation, italic/roman treatment, translated
titles, foreign institutions), and the opening of "Languages Using the Latin Alphabet" — the general
cross-language rules (§§11.9–11.13: capitalization, punctuation, word division, special characters,
IPA) plus the first three language-specific entries: African languages (§§11.14–11.15), Albanian
(§§11.16–11.17), and Croatian/Bosnian (§§11.18–11.19), plus the opening cross-reference stub for Czech
(§11.20). Remaining Latin-alphabet languages (Danish onward), the transliterated-language sections
(Arabic, Chinese/Japanese, Hebrew, Russian), Classical Greek, Old/Middle English, and American Sign
Language fall outside this page range and belong to later parts. Per the dispatch note, this chapter
is treated as genuine English-register content — CMOS's own apparatus for how English-language
publications absorb, mark, and typeset foreign-language material — not as a source of a foreign
language itself. Several entries in this range are pure cross-reference stubs with no independent
content of their own (§11.16 Albanian capitalization and §11.18 Croatian and Bosnian capitalization
both read only "See 11.3, 11.9"; §11.20 Czech capitalization is the same pattern, beginning the next
language's stub). These are **not treated as vocabulary/grammar points** — they contain nothing
beyond a pointer back to the general rules already captured at §§11.3 and 11.9, so extracting them
separately would be redundant padding, consistent with the coverage rule's "skip repeated/non-novel
content" instruction.

The source has a genuine clean text layer; per dispatch instruction, Vision Reading Confidence is
`n/a` throughout and Transcription Confidence is `n/a` throughout (reference-book extraction). No
handwritten marginalia was present. Per dispatch instruction, Attested Era is set to "contemporary
(source published 2010)" throughout and Attested Region to "American English (United States)"
throughout, since the entirety of this CMOS edition is an American-English usage/style reference.

**Mojibake gotcha, confirmed in this chunk exactly as flagged in the dispatch.** This chapter's
subject matter (foreign-language material embedded in English prose) means it is unusually dense with
accented and non-ASCII characters, and several instances of UTF-8-bytes-decoded-as-Latin-1 mojibake
were found and corrected by cross-referencing visible context (known book/periodical titles, known
author names, standard orthographic facts about the languages discussed):

- `ZÃ¼rcher` → **Zürcher** (in *Neue Zürcher Zeitung*, §11.5 example)
- `dÃ©mographie` → **démographie** (in *Annales de démographie historique*, §11.5 example)
- `MoliÃ¨re` → **Molière** (§11.7 example)
- `chÃ¢teau` → **château** (§11.7 example)
- `Ã la recherche du temps perdu` → **À la recherche du temps perdu** (Proust; §11.6 example — the
  leading "À" degraded further than the mid-word cases above, consistent with the same cipher acting
  on a capital accented letter at a word boundary)
- `â€"` (recurring in running-head breadcrumbs, e.g. "Capitalizationâ€"English versus other
  languages," "Punctuationâ€"original language versus English context") → an **em dash (—)**; this is
  the standard three-byte UTF-8-as-Latin-1 mojibake pattern for U+2014
- `Â« >>` (§11.4, describing guillemets) → **« »** (French angle quotation marks); the left mark
  mojibake-decodes cleanly (Â« = UTF-8 for «), the right mark rendered as a literal `>>` run rather
  than legible mojibake for » — read with reasonable confidence from context (the sentence explicitly
  says "guillemets ... may be changed to standard quotation marks") but flagged as the one genuinely
  interpretive repair in this chunk rather than a clean 1:1 byte decode

All vocabulary-table rows below reflect the corrected forms; none of the garbled forms is reproduced
as if authoritative.

---

## Vocabulary

CMOS is a style/usage reference, not a vocabulary-teaching text. Its "vocabulary" in this chapter is
the specialized terminology English-language publishing uses to describe and typeset foreign-language
material, plus the handful of language/ethnonym proper nouns the chapter explicitly discusses naming
conventions for (§§11.14–11.15). All entries below: Attested Era `contemporary (source published
2010)`, Attested Region `American English (United States)`, Source Type `grammar_reference`,
Transcription Confidence `n/a`, Vision Reading Confidence `n/a`, unless noted.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Unicode | the widely used standard for encoding the world's written characters, assigning each a unique hexadecimal code point | proper noun | technical.publishing | — | contemporary (source published 2010) | American English (United States) | transnational | grammar_reference | n/a | n/a | §11.2; "code point" and "character set" are the operative sub-concepts |
| code point | a Unicode character's unique identifying hexadecimal number, conventionally written with a "U+" prefix (e.g. U+00E0 for à) | noun phrase | technical.publishing | — | contemporary (source published 2010) | American English (United States) | transnational | grammar_reference | n/a | n/a | §11.2 |
| sentence-style (capitalization) | capitalizing only the first word of a title/subtitle and proper nouns within it, as opposed to capitalizing every major word | adjective (compound) | technical.publishing | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.3; CMOS's default rule for foreign-language titles regardless of script |
| headline-style (capitalization) | capitalizing most words of a title as in an English headline; contrasted with sentence-style | adjective (compound) | technical.publishing | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §§11.6–11.7; used for published English translations standing in for the original title |
| guillemets (« ») | the angled quotation marks standard in French (and some other European) typography, as opposed to English-style curly quotation marks | noun | technical.publishing | — | contemporary (source published 2010) | American English (United States) | transnational | grammar_reference | n/a | n/a | §11.4; CMOS directs that these be converted to standard English quotation marks in an English-language context — see mojibake note above |
| special characters | letters, diacritics, or symbols not part of the unmodified 26-letter English alphabet, needed to render foreign-language material correctly | noun phrase | technical.publishing | — | contemporary (source published 2010) | American English (United States) | transnational | grammar_reference | n/a | n/a | §11.12; the organizing concept for every language-specific "special characters" subsection in the chapter |
| diacritical marks (diacritics) | accent marks and similar marks added to a base letter to indicate pronunciation or distinguish meaning | noun | technical.publishing | — | contemporary (source published 2010) | American English (United States) | transnational | grammar_reference | n/a | n/a | §11.12; cited as one of the two main reasons (with ligatures) a Latin-alphabet foreign language may still need special Unicode characters |
| roman type | upright, non-slanted type, as opposed to italic | noun phrase | technical.publishing | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.5; the choice between roman and italic for foreign titles follows the same book/periodical-vs-article/poem logic as English titles (§8.154–95) |
| italic type | slanted type used by convention for certain classes of titles (books, periodicals) | noun phrase | technical.publishing | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.5 |
| gloss (English gloss) | a parenthetical English translation following a foreign-language title, not itself treated as a title | noun | technical.publishing | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.6; capitalized sentence-style and set in roman, no italics or quotation marks, when the work has not been published in English |
| Latin alphabet | the writing system used (with language-specific modifications) by most Western European languages and many others discussed in this chapter | proper noun | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | transnational | grammar_reference | n/a | n/a | §11.1; organizes the chapter's largest subsection |
| International Phonetic Alphabet (IPA) | the standardized set of phonetic symbols used to represent speech sounds across languages, independent of any particular orthography | proper noun | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | transnational | grammar_reference | n/a | n/a | §11.13; symbols are Unicode-defined; cites Pullum & Ladusaw's *Phonetic Symbol Guide* as further reading |
| word division | the rules governing where a word may be broken across a line-end hyphen | noun phrase | technical.publishing | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.11; general cross-language principles given here (never break single-syllable words, never strand a single letter, break hyphenated/solid compounds at the hyphen or between elements where possible) before language-specific rules in later sections |
| Ge'ez alphabet | the writing system used for Amharic and other Ethiopian Semitic languages (e.g. Tigrinya), distinct from the Latin alphabet used by most other African languages | proper noun | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | regional | grammar_reference | n/a | n/a | §11.14; explicitly noted as "not covered here" — i.e., CMOS's African-languages Latin-alphabet rules don't apply to it |
| click languages | a descriptive term for Xhosa and related southern African languages that use click consonants, noted as not following English capitalization conventions | noun phrase | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | regional | grammar_reference | n/a | n/a | §11.14 |
| Kiswahili | the endonym for Swahili; CMOS's recommended spelling when citing the language's own name (vs. "KiSwahili" or "KISwahili," both rejected) | proper noun | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | regional | grammar_reference | n/a | n/a | §11.14; illustrates CMOS's "capitalize African language names in the traditional way" rule — only the initial letter capitalized, not the internal class-prefix boundary |
| isiXhosa / Isixhosa | two attested spellings of the Xhosa endonym found in English-language publications, the former preserving the internal capital, the latter not; a third variant "Isizhosa" is also noted | proper noun | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | regional | grammar_reference | n/a | n/a | §11.14; CMOS reports usage rather than mandating one form, contrasting with its firmer Kiswahili recommendation |
| hooked letters (Ɓ ɓ, Ɗ ɗ, Ƙ ƙ) | special Latin-alphabet letters with a hook added to the stem, used in Hausa to represent implosive/ejective consonants not found in English | noun phrase | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | regional | grammar_reference | n/a | n/a | §11.15; glyph shapes cross-checked against standard Hausa orthography (independent of the page render) rather than taken purely from the rendered image — see confidence note below |
| y with hook (ƴ) / apostrophe-y substitute | the Hausa letter for glottalized y; the chunk notes that in Nigeria, both cases are conventionally substituted with an apostrophe before/after y ('y, y') rather than the hooked glyph | noun phrase | technical.linguistics.regional | — | contemporary (source published 2010) | American English (United States); regional note: Nigeria | regional | grammar_reference | n/a | n/a | §11.15; explicit regional/orthographic-practice annotation — a genuine case of the "explicit dialectal annotation" the coverage rule calls out as high-value |
| Albanian special characters (ç, ë) | the two diacritic letters needed for Albanian under its unified post-1972 orthography | noun phrase | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.17; see confidence note below — the rendered glyph run was harder to parse cleanly than the Croatian/Bosnian row immediately after it |
| Croatian and Bosnian special characters (Č č, Ć ć, Đ đ, Š š, Ž ž) | the five diacritic letters needed for the Latin-only orthography shared by modern standard Croatian and Bosnian | noun phrase | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.19; this row rendered cleanly, unlike the Albanian row above |
| đ / dj | the Croatian/Bosnian letter đ (voiced palatal affricate) and its informal digraph substitute "dj," explicitly distinguished as non-interchangeable in standard orthography | noun | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.19; "dj" for đ is flagged as an informal-correspondence substitution only, never standard practice |

### Confidence note on small-glyph rows

Two rows above (Hausa's hooked letters and Albanian's ç/ë) were read from a rendered page image
containing very small italic Unicode glyphs that did not render with full fidelity even though the
underlying PDF has a genuine text layer — this is a rendering-legibility issue in the specific tool
used for this extraction pass, not the font-substitution-cipher or OCR-garbling gotcha the spec
describes (both page breadcrumbs and surrounding prose text on the same pages were crisp and
unambiguous). Per dispatch instruction, Vision Reading Confidence stays `n/a` on these rows (the
source itself has a text layer), but the Hausa and Albanian glyph identifications are corroborated
independently against standard, well-documented facts about Hausa and Albanian orthography (Ɓ ɓ, Ɗ ɗ,
Ƙ ƙ, and ƴ are the standard IPA-adjacent hooked letters taught in Hausa pedagogical grammars; ç and ë
are the only two diacritic letters in the Albanian alphabet under its 1972 unification) rather than
read cold from the image alone — this is flagged explicitly rather than silently presented as a
clean, confident read, consistent with the spec's per-row confidence-flagging discipline. The
Croatian/Bosnian row (§11.19) rendered unambiguously and needed no such cross-check.

## Grammar points

### Chapter scope and organization (§11.1)

CMOS Chapter 11 gives general guidelines for presenting foreign-language text within English-language
publications, explicitly aimed at authors/editors who are not fluent in the language in question (who
are advised to seek additional guidance). More than two dozen languages/language groups are covered,
with the most common ones treated most fully. The chapter proceeds from general typographic matters
(capitalization, punctuation, italics — applicable to most of the languages discussed) through
Latin-alphabet languages, transliterated/romanized languages, Classical Greek, Old/Middle English, and
finally American Sign Language, with individual languages presented alphabetically within their
sections.

### Unicode as the chapter's encoding baseline (§11.2)

Unicode is described as the widely supported standard assigning a unique hexadecimal code point and
description to each of tens of thousands of characters, required by standards such as XML. Because
fonts with Unicode mapping typically support only a subset of the full character set, CMOS recommends
determining at the outset which characters a given publication will need. The chapter's own
special-character tables (Table 11.1 for Latin-alphabet languages, Table 11.2 for transliterated
languages, plus separate tables for Russian/Cyrillic and Greek) serve this purpose. Unicode numbers
are conventionally written with a "U+" prefix (e.g., U+00E0 for à).

### Capitalization of foreign titles (§11.3)

Chicago's rule for titles of foreign-language works — in text, notes, or bibliographies — is simple:
capitalize only the words that would be capitalized in normal prose (sentence style): the first word
of title and subtitle, plus all proper nouns. This applies equally to titles in the original Latin
script and to transliterated titles. Named exceptions exist for later-covered cases (French variation
in particular gets its own rule at §11.30).

### Punctuation of foreign titles (§11.4)

When a foreign title appears in English-language context, certain punctuation changes are permissible:
a period (or, more rarely, a semicolon) between title and subtitle may become a colon, with the
subtitle's first word then capitalized; guillemets (« ») may be changed to standard English quotation
marks; and any space before a following punctuation mark may be dropped. Commas, however, should
never be inserted or deleted (even in a series or before dates), and no other mark should be added or
removed beyond what's explicitly permitted.

### Italic versus roman type for foreign titles (§11.5)

Foreign-language titles in Latin-alphabet languages (including transliterated titles) follow the same
italic-vs-roman logic as English titles: books and periodicals are set in italic; poems and other
short works in roman (quoted). Illustrative examples given include Stendhal's *Le rouge et le noir*,
the *Neue Zürcher Zeitung*, the *Annales de démographie historique*, the German carol "Es ist ein'
Ros' entsprungen," and Miguel Hernández's poem "Casida del sediento" (translated in the example as
"Lament of the Thirsting Man").

### Foreign titles with an English translation gloss (§11.6)

An English gloss often follows a foreign title in parentheses. If the work has not been published in
English, the gloss is capitalized sentence-style and appears in neither italics nor quotation marks
(treated as a plain translation, not a title in its own right) — e.g., Leonardo Fioravanti's
*Compendio de i secreti rationali* (Compendium of rational secrets). If a published translation is
being cited, it is instead capitalized headline-style and set in italics or quotation marks per its
own type of work — e.g., Proust's *À la recherche du temps perdu* (*Remembrance of Things Past*).

### Translated titles standing in for the original (§11.7)

Whether to lead with the original title or an English translation depends on context and readership.
In general-audience work, a widely known English translation may be cited first (with the original
following in parentheses), or the original may be omitted entirely; alternatively, an author may
prefer to cite all foreign titles in English throughout, provided the documentation makes clear what
has/hasn't actually been published in English. Translated titles used this way are capitalized
headline-style and treated like ordinary English-language titles. Examples: a Chinese textbook,
*Elementary Learning* (*Xiao xue*); Molière's comedy *The Miser*, said to draw on an obscure
late-medieval French treatise, *The Evils of Greed* (discovered, per the example, in an abandoned
château).

### Foreign institutions (§11.8)

Names of foreign institutions and businesses given in the original language are set in roman type and
capitalized per the usage of the country concerned — which CMOS acknowledges can be difficult to
determine, recommending sentence-style capitalization as a fallback when in doubt. If translated
instead, the name is capitalized per ordinary English usage. A translated/glossed institution name
presented as a gloss (rather than as a formal translation) should not be italicized. Examples: *Société
d'entraide des membres de l'ordre national de la Légion d'honneur* / "the Mutual Aid Society for
Members of the National Order of the Legion of Honor"; the Supreme People's Court of the People's
Republic of China, given with its original-language gloss "Zhonghua renmin gongheguo zuigao renmin
fayuan" left unitalicized.

### Capitalization — English versus other languages (§11.9)

English capitalizes more classes of words than any other Western language CMOS discusses. Unless a
later section states otherwise, the default assumption for every foreign language treated in this
chapter is that it lowercases adjectives (except those functioning as proper nouns), pronouns, months,
and days of the week — all capitalized in English. Capitals are also used more sparingly in other
languages for names of offices and institutions. However, when a foreign term is translated into
English, it follows Chicago's own English capitalization rules (Chapter 8) regardless of the source
language's conventions.

### Punctuation — original language versus English context (§11.10)

This section's remarks point out departures from English punctuation conventions only for the more
obvious/common cases; it applies specifically to true foreign-language contexts (whole books,
articles, or lengthy quotations entirely in the foreign language). In English-language contexts and
translations of foreign works, English-style punctuation generally governs instead: the tightly spaced
ellipsis points used in French, Italian, and Spanish publications convert to English's more widely
spaced convention; English-style quotation marks replace guillemets or whatever the original uses; and
em dashes introducing dialogue need not be followed by a space as they might be in the original. One
exception: Spanish's distinctive opening question/exclamation punctuation (¿ ¡) may be preserved when
an entire sentence is presented in Spanish, but is dropped when the passage is translated.

### Word division (§11.11)

General word-division rules apply across both English and the foreign languages this chapter covers:
single-syllable words should never be broken; no word should be broken after a single letter, nor
should a single letter be carried over to the next line; and hyphenated or solid compounds should be
broken at the hyphen or between their component elements wherever possible (with a further
proper-noun-specific rule cross-referenced elsewhere in the manual). Language-specific word-division
rules follow in each language's own subsection later in the chapter.

### Special characters (§11.12)

Any foreign word, phrase, or title appearing in an English-language work must preserve whatever
special characters (accented letters, ligatures, and in some cases distinct alphabetical forms) occur
in the original — Latin-alphabet languages are no exception. CMOS recommends authors identify needed
special characters early (ideally at the manuscript stage) even when Unicode-compliant software is
available, both to guard against font-support gaps and, for handwritten-manuscript cases, to allow
unambiguous marginal clarification of accents. Table 11.1 is the chapter's master reference for
identifying each character by name and Unicode number (e.g., "Đ" / "đ" as "D with stroke" /
U+0110 / "d with stroke" / U+0111).

### International Phonetic Alphabet (§11.13)

IPA phonetic symbols are Latin-alphabet-based and Unicode-defined. CMOS directs readers to the
International Phonetic Association's website for the current version of the alphabet, and cites
Pullum and Ladusaw's *Phonetic Symbol Guide* as a further resource on phonetic notation generally.

### African capitalization and punctuation (§11.14)

Most African languages — with the notable exception of Arabic — use the Latin alphabet and follow
ordinary English capitalization and punctuation. Swahili is identified as the most widespread of
these, spoken across many ethnic groups in eastern and central Africa; Hausa, Fulfulde, Yoruba, Igbo,
Wolof, and Bambara are also spoken by millions, largely in western Africa, as are Kikongo (Kongo) and
Lingala in the Congo-Zaire region and Amharic and Somali in the Horn of Africa. Amharic and other
Ethiopian Semitic languages (e.g., Tigrinya) use the Ge'ez alphabet instead, which this chapter does
not cover. Xhosa and other southern African click languages do not follow English capitalization
conventions. African-language names themselves vary widely in spelling convention from group to
group; current standard practice capitalizes them in the traditional way (Kiswahili, not KiSwahili or
KISwahili). Xhosa speakers' own name for their language is variously rendered "isiXhosa," "Isixhosa,"
or occasionally "Isizhosa" in English-language publications.

### African special characters (§11.15)

Swahili itself needs no additional letters or diacritics. Many other African languages, however, rely
on diacritics or special letter forms for sounds with no single-letter English equivalent. Hausa in
particular — spoken by millions across western Africa — requires hooked letters: Ɓ/ɓ, Ɗ/ɗ, Ƙ/ƙ, and a
hooked Y (Y̌/ẙ, representing a glottalized y). In Nigeria specifically, the hooked Y is conventionally
replaced in practice with an apostrophe before or after a plain y ('y / y') rather than the hooked
glyph itself — an explicit regional/orthographic-practice note. Additional diacritics needed by other
African languages are too numerous for the chapter to list exhaustively; French, Portuguese, and
Arabic as used in Africa are instead covered under those languages' own dedicated sections elsewhere
in the chapter.

### Albanian (§§11.16–11.17)

Capitalization (§11.16) is a pure cross-reference to the chapter's general rules (§§11.3, 11.9) — no
independent Albanian-specific capitalization rule is given. Since a single, unified Albanian
orthography came into use in 1972, the special characters needed are ç and ë (§11.17).

### Croatian and Bosnian (§§11.18–11.19)

Capitalization (§11.18) is again a pure cross-reference to §§11.3 and 11.9. The historical
Serbo-Croatian language used both the Latin and Cyrillic alphabets; the modern standard Croatian and
Bosnian languages use only the Latin version of that shared alphabet. The special characters needed
are Č/č, Ć/ć, Đ/đ, Š/š, and Ž/ž. The informal substitution of the digraph "dj" for đ is noted as
sometimes seen in informal correspondence, but standard orthographic practice across all of
Serbo-Croatian's successor languages consistently distinguishes the two.

### Czech (§11.20, opening stub)

This range ends at the opening cross-reference for Czech capitalization ("See 11.3, 11.9"), the same
pure-pointer pattern seen for Albanian and Croatian/Bosnian above. Czech's special-characters section
(§11.21) and all subsequent language sections fall into the next part of this split.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes, dialogue
blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`.
