# English — Established Vocabulary/Grammar: CMOS Ch. 11, "Foreign Languages," pt. 4 (§§11.69–11.92: Languages Using the Latin Alphabet — Polish special characters through Turkish/Azeri; opening of Languages Usually Transliterated)

**Source:** *The Chicago Manual of Style*, 16th edition (University of Chicago Press, 2010), Chapter
11, "Foreign Languages," PDF pp. 1431–1454 (sections 11.69 through 11.92).

**Coverage note:** This chunk picks up mid-"Languages Using the Latin Alphabet," beginning at Polish
special characters (§11.69) and running through the close of the Latin-alphabet language-by-language
roster at Turkish and Azeri (§§11.88–11.90), then into the opening two sections of the next major
subsection, "Languages Usually Transliterated (or Romanized)" — the general transliteration
discussion (§11.91) and character-set guidance for non-Latin alphabets (§11.92). The languages
individually covered here are Polish (special characters only — Polish capitalization and word
division precede this page range), Portuguese, Romanian and Moldavian, Serbian and Montenegrin,
Spanish (the chapter's longest single-language treatment in this range, spanning additional resources,
capitalization, question/exclamation punctuation, guillemets and quotation marks, dialogue
conventions, suspension points, and word division for both vowels and consonants, plus compound-word
division and special characters), Swedish, and Turkish/Azeri. As in prior parts of this split, several
entries are pure cross-reference stubs pointing back to the chapter's general rules at §§11.3 and 11.9
(Portuguese capitalization §11.70, Romanian/Moldavian capitalization §11.72, Serbian/Montenegrin
capitalization §11.74, Swedish capitalization §11.86 in part, Turkish/Azeri capitalization §11.89 in
part) — these are summarized briefly in Grammar points but not treated as independent vocabulary
entries, consistent with the "skip repeated/non-novel content" coverage rule and the precedent set in
pt01 (036) for the Albanian/Croatian-Bosnian/Czech stubs.

**Relationship to prior parts of this split:** This is sequential, first-pass coverage of a page range
not previously extracted (pt01/036 covered §§11.1–11.20; the intervening §§11.21–11.68 belong to
pt02/pt03, not yet present in `established/` at the time of this dispatch). One genuine point of
topical overlap with pt01 is worth flagging explicitly: the Serbian and Montenegrin special-characters
list at §11.75 (Ć ć, Č č, Đ đ, Š š, Ž ž) is letter-for-letter identical to the Croatian and Bosnian list
already captured at pt01's §11.19, since all four standard languages descend from the shared
Serbo-Croatian Latin orthography. This chunk does not re-list those five letters as a "new" vocabulary
entry — instead the vocabulary table below captures only what's genuinely new in this section: the
explicit note that Montenegro now uses both Cyrillic and Latin as co-official alphabets for its
standard language (whereas Serbia's official standard uses Cyrillic, with Latin as the common but
non-official alternative), a distinction §11.19's Croatian/Bosnian discussion did not make since
neither of those languages has an official-Cyrillic form.

The source has a genuine clean text layer; per dispatch instruction, Vision Reading Confidence is
`n/a` throughout and Transcription Confidence is `n/a` throughout (reference-book extraction). No
handwritten marginalia was present. Per dispatch instruction, Attested Era is set to "contemporary
(source published 2010)" throughout and Attested Region to "American English (United States)"
throughout, since the entirety of this CMOS edition is an American-English usage/style reference. Per
the dispatch note, this chapter is treated as genuine English-register content — CMOS's own apparatus
for how English-language publications absorb, mark, and typeset foreign-language material — not as a
source of any of the foreign languages it discusses.

**Mojibake gotcha, confirmed once in this chunk, exactly the pattern flagged in the dispatch and
previously documented in pt01 (036).** Swedish's special-characters line (§11.87) rendered as UTF-8-
bytes-decoded-as-Latin-1/cp1252 mojibake rather than legible accented letters. Recovered by decoding
the byte pattern and cross-checking against the single most basic, unambiguous fact about Swedish
orthography (the Swedish alphabet has exactly three letters beyond the unmodified 26-letter Latin
set — ä, å, ö — a fact independently verifiable from any Swedish-language reference, not something
inferred or guessed from the garbled render):

- The rendered string decoded, byte-for-byte, to the expected UTF-8-as-cp1252 mojibake for "Ä ä, Å å,
  Ö ö" (e.g., Ä = U+00C4 = UTF-8 `C3 84` → read as cp1252 `Ã` + `„`, the cp1252 glyph at 0x84; Å =
  U+00C5 = `C3 85` → `Ã` + `…`, cp1252's horizontal-ellipsis glyph at 0x85; Ö = U+00D6 = `C3 96` →
  `Ã` + `–`, cp1252's en-dash glyph at 0x96 — the same "two-byte UTF-8 character becomes two garbled
  Latin-1-family characters sharing a `Ã` prefix" mechanism already documented for this book). This is
  recorded as **Ä ä, Å å, Ö ö** in the vocabulary table below, flagged `plausible_unverified` in the
  row's Notes despite Transcription/Vision Reading Confidence both being `n/a` per the reference-book
  convention — the one row in this chunk that needed the mojibake-recovery discipline rather than a
  clean direct read.

No other mojibake was found in this chunk; the Polish, Portuguese, Romanian/Moldavian, Serbian/
Montenegrin, Spanish, and Turkish/Azeri special-character lines all rendered as clean, directly legible
accented Latin text.

---

## Vocabulary

CMOS is a style/usage reference, not a vocabulary-teaching text. Its "vocabulary" in this chunk is
overwhelmingly the per-language special-character inventories the chapter tabulates for Latin-alphabet
languages, plus a handful of named external resources and typographic/punctuation conventions
(concentrated in the Spanish sections, by far the longest single-language treatment in this range).
All entries below: Attested Era `contemporary (source published 2010)`, Attested Region `American
English (United States)`, Source Type `grammar_reference`, Transcription Confidence `n/a`, Vision
Reading Confidence `n/a`, unless noted.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Polish special characters (Ą ą, Ć ć, Ę ę, Ł ł, Ń ń, Ó ó, Ś ś, Ź ź, Ż ż) | the nine diacritic letters needed for Polish orthography | noun phrase | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.69; the chunk notes Ą, Ę, and Ń never occur word-initially, so capitalized forms of those three are needed only when an entire word is capitalized |
| Portuguese special characters (À à, Á á, Â â, Ã ã, Ç ç, È è, É é, Ê ê, Ì ì, Í í, Ï ï, Ò ò, Ó ó, Ô ô, Õ õ, Ù ù, Ú ú, Ü ü) | the full set of accented/cedilla letters needed for Portuguese orthography | noun phrase | technical.linguistics | — | contemporary (source published 2010) | American English (United States); regional note: European Portuguese does not use Ü/ü | regional | grammar_reference | n/a | n/a | §11.71; explicit dialectal/regional annotation distinguishing Brazilian from European Portuguese orthography — the chunk also notes that accented capitals, though sometimes dropped in Portuguese running text itself, should always be retained when Portuguese is presented in an English-language context |
| Romanian and Moldavian special characters (Â â, Ă ă, Î î, Ş ş, Ţ ţ) | the five diacritic letters needed for the Latin orthography now shared by Romanian and Moldavian | noun phrase | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.73; Ş/ş and Ţ/ţ (comma-below diacritic) are frequently rendered instead with a cedilla in practice, though the comma-below form is the orthographically correct one |
| Â/Î orthographic variation | a documented case of the same Romanian sound (â/î) having two historically distinct letters whose relative use has been restricted, eliminated, and partly reinstated across successive 20th-century orthographic reforms | noun phrase | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.73; CMOS advises writers/editors to determine whether a given spelling is conditioned by the period it was written in or should instead follow the current norm — the same era-sensitivity caution repeated for Turkish spelling below |
| Montenegro's co-official biscriptal status | the explicit note that modern standard Montenegrin, uniquely among Serbo-Croatian's successor languages in this chunk's range, treats both the Latin and Cyrillic alphabets as officially co-equal, whereas Serbian's official standard uses Cyrillic with Latin as a common but non-official alternative | noun phrase | technical.linguistics.regional | — | contemporary (source published 2010) | American English (United States); regional note: Montenegro vs. Serbia | regional | grammar_reference | n/a | n/a | §11.75; genuinely new content relative to pt01/036's Croatian-and-Bosnian treatment at §11.19, which covers the same shared five-letter special-character set (Ć ć, Č č, Đ đ, Š š, Ž ž, not re-listed here as a separate entry) but does not address Montenegro's current biscriptal status specifically |
| María Moliner, *Diccionario de uso del español* / Real Academia Española | the two additional-resources CMOS recommends for Spanish capitalization, punctuation, and other matters, given the considerable regional variation across Spanish-language publishing worldwide | proper noun | technical.publishing | — | contemporary (source published 2010) | American English (United States) | transnational | grammar_reference | n/a | n/a | §11.76 |
| el Sr. / el señor (title abbreviation rule) | the Spanish convention that a title preceding a proper name is normally lowercased when spelled out (el señor Jaime López) but capitalized when abbreviated (el Sr. López) | noun phrase | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.77; CMOS examples also given for señora and doña (la señora Lucía Moyado de Barba, doña Perfecta) |
| nationality nouns/adjectives vs. country names (Spanish capitalization) | the rule that nouns and adjectives denoting membership in a nation are lowercased in Spanish (los mexicanos, la lengua española) while the country name itself remains capitalized (Inglaterra) | noun phrase | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.77 |
| inverted question/exclamation marks (¿ ¡) | the Spanish convention of preceding a question or exclamation with an inverted mark and following it with the regular mark | noun phrase | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.78; retained even when Spanish is quoted within an English-language context, per the cross-referenced general punctuation rule at §11.10 |
| vocative/dependent-construction punctuation placement | the rule that when a vocative or dependent clause precedes a Spanish question or exclamation, the inverted mark is placed at the start of the question/exclamation proper, not at the start of the whole sentence (e.g., "Amigo, ¿qué pasa?") | noun phrase | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.78 |
| guillemets (Spanish usage) | Spanish's traditional quotation marks (« »), with only punctuation belonging to the quoted matter placed inside the closing guillemet and other punctuation following; em dashes may set off a speaker-identifying clause within a quotation | noun phrase | technical.publishing | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.79; CMOS notes English-style curly quotation marks are increasingly seen in Spanish publications in place of guillemets, especially in electronic contexts; single quotation marks are reserved for glosses (cross-ref §7.50) |
| em-dash spacing around speaker tags (Spanish guillemet quotations) | the convention that, within a guillemet-set quotation, an opening em dash identifying the speaker is preceded by a space and a closing em dash is followed by a space unless immediately followed by punctuation; such spaces are unnecessary in an English-language context | noun phrase | technical.publishing | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.79 |
| em-dash dialogue convention (Spanish) | the Spanish practice of introducing each successive speech in dialogue with an em dash (or, less often, a guillemet), with any narrative matter following the quoted speech in the same paragraph preceded by a dash or comma | noun phrase | technical.publishing | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.80 |
| suspension points (Spanish) | Spanish's unspaced ellipsis-style dots indicating an interruption or break in thought, generally spaced in the English manner only when appearing in an English-language context; omitted material is indicated with bracketed dots | noun phrase | technical.publishing | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.81; parallel to the same convention in French and Italian per the general cross-reference at §11.10 |
| word division after a vowel (Spanish) | the default Spanish word-division rule: divide after a vowel whenever possible (ca-ra-co-les, mu-jer, re-cla-mo); a diphthong or triphthong forming a single syllable is never divided (cam-bias, fue-go, miau), while adjacent vowels belonging to separate syllables are divided between them (ba-úl, cre-er, pa-ís, te-a-tro) | noun phrase | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.82 |
| word division between consonants (Spanish) | the rule that two adjacent consonants forming a combination that would not normally occur word-initially in Spanish are divided between them (ac-cio-nis-ta, ad-ver-ten-cia); the pairs bl, br, cl, cr, dr, fl, fr, gl, gr, pl, pr, and tr are inseparable since they can begin a Spanish word, unless each belongs to a different element of a compound | noun phrase | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.83 |
| three-consonant cluster division rule (Spanish) | the rule that a group of three consonants not ending in one of the inseparable two-consonant pairs always contains a medial s and is divided immediately after that s (cons-pi-rar, ins-tan-te, obs-cu-ro) | noun phrase | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.83 |
| ch, ll, rr — Spanish alphabetization and indivisibility | Spanish ch and ll were long alphabetized as single letters and never divided; the Real Academia Española has since reclassified both as two-letter sequences for alphabetization purposes, a convention adopted in newer publications, but ch, ll, and rr remain indivisible across a line break in all cases since each represents a single sound (ci-ga-rri-llo, mu-cha-cho) | noun phrase | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.83; cites the Real Academia Española's *Ortografía de la lengua española* |
| dividing Spanish compounds | Spanish compound words are often, but not always, divided between their component parts (des-igual, in-útil, mal-estar, trans-al-pi-no, semi-es-fe-ra, bien-aven-tu-ra-do, sub-lu-nar, sub-ra-yar), with exceptions such as no-so-tros, which is divided by ordinary syllabification rather than at its historical compound boundary | noun phrase | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.84 |
| Spanish special characters (Á á, É é, Í í, Ñ ñ, Ó ó, Ú ú, Ü ü) | the seven diacritic/tilde letters needed for Spanish orthography | noun phrase | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.85 |
| Ni / Er lowercasing (Swedish) | the former practice of capitalizing the Swedish second-person pronouns Ni and Er in correspondence, now lowercased in all contexts under current Swedish usage | noun phrase | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.86 |
| Swedish special characters (Ä ä, Å å, Ö ö) | the three diacritic letters beyond the unmodified 26-letter Latin alphabet needed for Swedish orthography | noun phrase | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | plausible_unverified | §11.87; recovered from UTF-8-as-cp1252 mojibake in the source render — see mojibake note above; the text layer is otherwise genuine (Vision Reading Confidence column stays `n/a` per the reference-book convention, since no vision-reading of a scanned page was involved), but this specific row's underlying render required byte-level decoding rather than a direct legible read, hence the explicit `plausible_unverified` flag here despite the `n/a` columns |
| Turkish orthographic reform history | the note that modern Turkish has undergone multiple spelling reforms since its 1928 switch from the Arabic to the Latin alphabet, such that the spelling of a given name or word can depend on which time period it dates from | noun phrase | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.88; writers/editors are advised to determine whether a spelling is era-conditioned or should follow the current norm — directly parallel to the Romanian Â/Î caution above |
| Turkish and Azeri capitalization of months/days | the explicit exception, unlike most other languages covered in this chapter's default-lowercase rule (§11.9), that Turkish — like English — capitalizes the names of months and days of the week; Azeri follows the same pattern except for the differences noted in its special-characters section | noun phrase | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.89 |
| Turkish special characters (Â â, Ç ç, Ğ ğ, İ ı, Ö ö, Ş ş, Û û, Ü ü) | the diacritic letters needed for Turkish orthography | noun phrase | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.90 |
| Azeri special characters (Ç ç, Ə ə, Ğ ğ, İ ı, Ö ö, Ş ş, Ü ü) | the diacritic letters needed for the modern Azeri (Azerbaijani) Latin alphabet in use since 1992, which is identical to Turkish's except for adding Q/q and X/x (absent from Turkish), lacking Turkish's circumflex-marked vowels, and adding the schwa (Ə/ə) | noun phrase | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.90 |
| dotted/dotless i (Turkish and Azeri) | the orthographic distinction, found in both Turkish and Azeri, between a dotted and an undotted variety of both capital and lowercase i; a dotted lowercase i retains its dot when capitalized (İ), distinguishing it from the undotted capital I | noun phrase | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.90 |
| transliteration (romanization) | the practice, customary in nonspecialized English-language works, of converting words/phrases from a non-Latin-alphabet language into the Latin alphabet | noun | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | transnational | grammar_reference | n/a | n/a | §11.91; CMOS names Arabic, Chinese, Hebrew, Japanese, Russian, and other living languages, plus ancient languages such as Greek and Sanskrit, as languages customarily transliterated rather than reproduced in their native script |
| Peter T. Daniels and William Bright, eds., *The World's Writing Systems* | the resource CMOS recommends for discussion and illustration of the many alphabets/writing systems touched on in the transliteration section | proper noun | technical.publishing | — | contemporary (source published 2010) | American English (United States) | transnational | grammar_reference | n/a | n/a | §11.91 |
| ALA-LC Romanization Tables (Library of Congress) | the Library of Congress publication CMOS identifies as the most comprehensive resource for alphabetic (romanization) conversion, available online | proper noun | technical.publishing | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.91; CMOS explicitly cautions against attempting to transliterate from a language unfamiliar to the writer/editor |
| character sets for non-Latin alphabets | the chapter's note that modern word-processing software readily supports keying non-Latin alphabets (e.g., Cyrillic, Greek, Hebrew) directly, though a given alphabet may have multiple available character sets across typefaces, making consultation with the publisher and preference for correct Unicode characters advisable | noun phrase | technical.publishing | — | contemporary (source published 2010) | American English (United States) | transnational | grammar_reference | n/a | n/a | §11.92; cross-references the chapter's own Unicode discussion (§11.2) and a further general-manual cross-reference (§2.15) |

## Grammar points

### Polish special characters (§11.69)

Polish requires nine diacritic letters beyond the unmodified Latin alphabet: Ą/ą, Ć/ć, Ę/ę, Ł/ł, Ń/ń,
Ó/ó, Ś/ś, Ź/ź, and Ż/ż. Because Ą, Ę, and Ń never occur at the beginning of a Polish word, their
capitalized forms are needed only when an entire word is being set in capitals.

### Portuguese (§§11.70–11.71)

Capitalization (§11.70) is a cross-reference to the chapter's general rules (§§11.3, 11.9), with
titles and nouns/adjectives of nationality specifically following the same pattern as Spanish
(§11.77). Portuguese's special characters (§11.71) are extensive — eighteen accented forms spanning
grave, acute, circumflex, tilde, cedilla, and (for Brazilian Portuguese only) trema/diaeresis marks —
with the explicit regional note that European Portuguese does not use Ü/ü. CMOS further advises that
accented capitals, though sometimes dropped in running Portuguese text itself, should always be
retained when Portuguese material is presented within an English-language context.

### Romanian and Moldavian (§§11.72–11.73)

Capitalization (§11.72) is again a pure cross-reference to §§11.3 and 11.9. Romanian and Moldavian now
share the same Latin orthography, requiring five special characters: Â/â, Ă/ă, Î/î, Ş/ş, and Ţ/ţ. CMOS
flags two orthographic nuances: Ş/ş and Ţ/ţ are correctly marked with a comma below (not a cedilla,
though the cedilla form is frequently substituted in practice), and Â/â and Î/î — which represent
identical sounds but have different etymological origins — have been restricted, eliminated, and
reinstated in whole or in part across successive orthographic reforms, so writers and editors should
determine whether a given spelling reflects the period in which it was used or should instead follow
the current norm.

### Serbian and Montenegrin (§§11.74–11.75)

Capitalization (§11.74) is a cross-reference to §§11.3 and 11.9. The historical Serbo-Croatian
language used both Latin and Cyrillic alphabets; in the modern Montenegrin standard language, both
versions remain officially co-equal, while in the modern Serbian standard language, the Cyrillic
version is official (Latin remaining the common non-official alternative). The Latin-script special
characters needed are Ć/ć, Č/č, Đ/đ, Š/š, and Ž/ž — the same five letters already needed for Croatian
and Bosnian (pt01/036, §11.19), since all four languages share the same Serbo-Croatian-derived Latin
orthography. As with Croatian and Bosnian, the informal digraph substitution of "dj" for đ is
sometimes seen (e.g., in informal correspondence), but standard orthographic practice across all the
successor languages of Serbo-Croatian consistently distinguishes the two.

### Spanish — additional resources (§11.76)

Because Spanish-language publishing practice varies considerably across the many countries where
Spanish is published, CMOS points readers toward two further resources for capitalization,
punctuation, and other matters: María Moliner's *Diccionario de uso del español*, and the extensive
online resources of the Real Academia Española.

### Spanish capitalization (§11.77)

Beyond the cross-reference to §§11.3 and 11.9, Spanish has two specific capitalization rules of its
own. A title preceding a proper name is normally lowercased when spelled out (el señor Jaime López, la
señora Lucía Moyado de Barba, doña Perfecta), but capitalized when abbreviated (el Sr. López). Nouns
and adjectives denoting membership in a nation are lowercased (los mexicanos, la lengua española), but
the name of the country itself remains capitalized (Inglaterra).

### Spanish question marks and exclamation points (§11.78)

A Spanish question or exclamation is preceded by an inverted mark (¿ or ¡) and followed by the regular
mark (¿Qué pasa, amigo? ¡Olvídalo en ese caso!). When a vocative or dependent construction precedes the
question or exclamation itself, the inverted mark is placed at the start of the question/exclamation
proper rather than at the start of the whole sentence (Amigo, ¿qué pasa? En ese caso, ¡olvídalo!).
Because the opening marks are integral to Spanish punctuation, CMOS directs that they be retained even
when Spanish is quoted within an English-language context (cross-ref §11.10).

### Spanish guillemets and quotation marks (§11.79)

Spanish traditionally uses guillemets (« ») for quotation marks, with only punctuation belonging to
the quoted matter placed inside the closing guillemet and any other punctuation following it. Within a
quotation, em dashes may set off words identifying the speaker; in Spanish publications the opening
dash is usually preceded by a space, and the closing dash followed by a space unless immediately
followed by punctuation (such spacing is unnecessary in an English-language context; cross-ref
§11.10). The chapter's own example: «Vino el negocio a tanto —comenta Suárez—, que ya andaban muchos
tomados por el diablo». Single quotation marks are reserved for glosses (cross-ref §7.50). CMOS also
notes that English-style curly quotation marks, rather than guillemets, are increasingly encountered
in Spanish publications, especially in electronic contexts.

### Spanish dialogue (§11.80)

In dialogue, an em dash (or, less commonly, a guillemet) introduces each successive speech. Any
narrative matter that follows the quoted speech within the same paragraph should be preceded by a dash
or a comma (cross-ref §11.79). Examples: "—Esto es el arca de Noé, afirmó el estanciero." and
"—¿Por qué estás aquí todavía?—preguntó Juana alarmada."

### Spanish suspension points and ellipses (§11.81)

As in French, Spanish uses suspension points to indicate interruptions or breaks in thought; these
dots are generally unspaced in Spanish publications, though in an English-language context they may be
spaced in the English manner (cross-ref §§13.48–56). Omitted material (i.e., a true ellipsis) is
indicated by enclosing the dots in brackets (cross-ref §11.10).

### Spanish word division — vowels (§11.82)

Spanish division is made after a vowel whenever possible (ca-ra-co-les, mu-jer, re-cla-mo,
se-ño-ri-ta; cross-ref §11.11). Two or more vowels forming a single syllable — a diphthong or
triphthong — may not be divided (cam-bias, fue-go, miau, tie-ne, viu-da). When adjacent vowels belong
to separate syllables, however, they are divided between syllables (ba-úl, cre-er, pa-ís, te-a-tro).

### Spanish word division — consonants (§11.83)

If two adjacent consonants form a combination that would not generally occur at the beginning of a
Spanish word, the word is broken between them (ac-cio-nis-ta, ad-ver-ten-cia, al-cal-de, an-cho,
efec-to, is-le-ño). The consonant pairs bl, br, cl, cr, dr, fl, fr, gl, gr, pl, pr, and tr — all pairs
that can begin a Spanish word — are inseparable, unless each belongs to a different element of a
compound (cross-ref §§11.84, 11.11); examples given include ci-fra, co-pla, im-po-si-ble, le-pra,
li-bro, ma-dre, ne-gro, no-ble, pa-tria, re-fle-jo, re-gla, se-cre-to, te-cla. Groups of three
consonants not ending in one of those inseparable pairs always contain a medial s and are divided
immediately after it (cons-pi-rar, cons-ta, ins-tan-te, obs-cu-ro, obs-tan-te). Spanish ch and ll were
long treated as single alphabetized letters and never divided; the Real Academia Española has since
reclassified them as two-letter sequences for alphabetizing purposes, a convention newer publications
have adopted, but ch, ll, and rr all remain indivisible across a line break in every case, since each
represents a single sound (ci-ga-rri-llo, mu-cha-cho) — for details CMOS cites the Real Academia
Española's *Ortografía de la lengua española*.

### Dividing Spanish compounds (§11.84)

Compound words are often, but not always, divided between their component parts: des-igual, in-útil,
mal-estar, trans-al-pi-no, semi-es-fe-ra, bien-aven-tu-ra-do, sub-lu-nar, sub-ra-yar. The exception
given is no-so-tros, divided by ordinary syllable rules rather than at its historical compound
boundary.

### Spanish special characters (§11.85)

Spanish requires seven special characters: Á/á, É/é, Í/í, Ñ/ñ, Ó/ó, Ú/ú, and Ü/ü.

### Swedish (§§11.86–11.87)

Capitalization (§11.86) is a cross-reference to §§11.3 and 11.9, plus one Swedish-specific note: the
second-person pronouns Ni and Er, traditionally capitalized in correspondence, are now lowercased in
all contexts under current usage. Swedish's special characters (§11.87) are Ä/ä, Å/å, and Ö/ö — see the
mojibake-recovery note at the top of this file for how this row was reconstructed from a garbled
source render.

### Turkish and Azeri (§§11.88–11.90)

Turkish spelling (§11.88) has undergone multiple orthographic reforms since the original 1928 switch
to the Latin alphabet, so the spelling of a given name or word can depend on the period it dates from;
writers and editors should determine whether to follow a period-conditioned spelling or the current
norm (the same caution given for Romanian's Â/Î variation above). Capitalization (§11.89) is a
cross-reference to §§11.3 and 11.9 with one notable exception to the chapter's general default-lowercase
pattern: Turkish, like English, capitalizes the names of months and days of the week. Azeri follows the
same pattern as Turkish except for the differences given in the special-characters section. Turkish's
special characters (§11.90) are Â/â, Ç/ç, Ğ/ğ, İ/ı, Ö/ö, Ş/ş, Û/û, and Ü/ü. The modern Azeri
(Azerbaijani) standard alphabet, in use since 1992, is identical to Turkish's except that it adds Q/q
and X/x (both absent from Turkish), lacks Turkish's circumflex-marked vowels, and adds the schwa
(Ə/ə) — giving Ç/ç, Ə/ə, Ğ/ğ, İ/ı, Ö/ö, Ş/ş, and Ü/ü. Both Turkish and Azeri distinguish dotted and
undotted varieties of both the capital and lowercase i; a dotted lowercase i retains its dot when
capitalized (İ), distinguishing it from the plain, undotted capital I.

### Transliteration (§11.91)

Opening the chapter's next major subsection, "Languages Usually Transliterated (or Romanized)," CMOS
describes transliteration (romanization) as the customary practice, in nonspecialized works, of
converting words or phrases from a non-Latin-alphabet language into the Latin alphabet. Languages
named as customarily transliterated include Arabic, Chinese, Hebrew, Japanese, Russian, and other
living languages, as well as ancient languages such as Greek and Sanskrit. For a discussion and
illustration of the many writing systems involved, CMOS recommends Peter T. Daniels and William
Bright's edited volume *The World's Writing Systems*; for alphabetic conversion specifically, it
recommends the Library of Congress's ALA-LC Romanization Tables, available online, as the most
comprehensive resource. CMOS explicitly cautions against attempting to transliterate from a language
unfamiliar to the writer/editor.

### Character sets for non-Latin alphabets (§11.92)

Modern word-processing software readily supports keying text directly in several of the non-Latin
alphabets this chapter's languages use — Cyrillic, Greek, and Hebrew among them. Because a given
alphabet may have multiple available character sets across different typefaces, authors who want to
include such copy should, after consulting their publisher, opt for the correct Unicode characters
whenever possible (cross-ref §11.2; see also §2.15).

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes, dialogue
blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`.
