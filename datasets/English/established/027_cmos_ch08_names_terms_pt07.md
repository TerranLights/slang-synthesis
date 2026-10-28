# English — Established Vocabulary/Grammar: Chicago Manual of Style, Ch. 8 "Names and Terms," Part 7 (§§8.151–8.176)

**Source:** The Chicago Manual of Style (16th edition), University of Chicago Press Staff, 2010.
Chapter 8, "Names and Terms" — sections 8.151 ("Metric units") through 8.176 ("Collected works"),
spanning the end of the "Scientific Terminology" subsection, the full "Brand Names and Trademarks"
subsection, and the opening of the "Titles of Works" subsection (through its "Capitalization,
Punctuation, and Italics" and "Books and Periodicals" sub-subsections, up to "Articles in
Periodicals and Parts of a Book"). PDF pages 1155–1180 of the source file. This is a digital/online
edition layout (sidebar navigation, no printed page numbers visible on the page images themselves),
so citations below use CMOS's own section numbers (§x.xxx) rather than printed page numbers.

**Coverage note:** every grammar point and every distinct vocabulary item from this range, plus the
handful of editorial-terminology terms the text itself introduces (e.g. "midcaps," "reverse
italics"). This chunk is almost entirely a dense sequence of short numbered rules (26 sections) with
very few example lists that qualify as genuine "vocabulary" in the usual sense — the real vocabulary
content here is the set of trademark names CMOS uses to illustrate the brand-name/generic-term
distinction, plus a few style-terminology nouns. Repeated restatement of the same example across
cross-references was skipped per the coverage rule. Source has a genuine text layer (confirmed via
`pdftotext`); no vision-reading was needed for any entry.

**PDF mojibake gotcha — two instances found and decoded, per this dispatch's known-gotcha warning:**
1. §8.163's example "non-Latin letters such as *Ï€* or *Î³*" is UTF-8-encoded text that was decoded
   as Latin-1 and re-encoded, producing visible mojibake. Byte-level reconstruction: `Ï€` = Latin-1
   misread of UTF-8 bytes `CF 80`, which is the correct UTF-8 encoding of Greek **π** (pi); `Î³` =
   Latin-1 misread of UTF-8 bytes `CE B3`, the correct UTF-8 encoding of Greek **γ** (gamma). Decoded
   with high confidence (clean byte-level correspondence, consistent with "non-Latin letters" framing
   a Greek-letter example) to: "non-Latin letters such as *π* or *γ*."
2. §8.175's fourth example, `"Schiller's â€˜Ode to Joy' in Beethoven's Ninth Symphony,"` shows the
   same pattern: `â€˜` = Latin-1 misread of UTF-8 bytes `E2 80 98`, the correct UTF-8 encoding of the
   left single quotation mark **'** (U+2018). Decoded to: `"Schiller's 'Ode to Joy' in Beethoven's
   Ninth Symphony"` — consistent with the passage's own point that a title-within-a-title normally in
   quotation marks must switch to single quotation marks when nested inside a double-quoted title.

Both decodes verified against surrounding visible context (Greek-letter example in a sentence
explicitly about non-Latin letters; single-quote mark needed exactly where CMOS's own rule requires
one) rather than guessed; no entries required a `low_confidence` fallback.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Bufferin | generic equivalent: buffered aspirin | proper noun (trademark) | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.152 example list of trademarks CMOS says should be capitalized, with the generic term substituted "when available." |
| Coca-Cola | generic equivalent: cola | proper noun (trademark) | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.152. |
| Google | generic equivalent: search engine; also "search." Note: *Webster's* now enters the lowercase verb *google* (to search online) despite trademark-owner discouragement of verbing. | proper noun (trademark); also cited as a verb | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.152; cross-references §7.76 for computer-related names/terms. |
| Jacuzzi | generic equivalent: whirlpool bath | proper noun (trademark) | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.152. |
| Kleenex | generic equivalent: (facial) tissue — CMOS specifically recommends "Kleenex facial tissue," not bare "Kleenex," when a generic term is wanted alongside the brand name. | proper noun (trademark) | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.152. |
| Levi's | generic equivalent: jeans | proper noun (trademark) | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.152. |
| Ping-Pong | generic equivalent: table tennis | proper noun (trademark) | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.152. |
| Pyrex | generic equivalent: heat-resistant glassware | proper noun (trademark) | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.152. |
| Scrabble | (listed without a generic equivalent in the source — board game trademark) | proper noun (trademark) | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.152; the one item in the list with no paired generic term. |
| Vaseline | generic equivalent: petroleum jelly | proper noun (trademark) | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.152. |
| Xerox | generic equivalent: photocopier; copy. Note: *Webster's* also enters the lowercase verb *xerox* (to photocopy). | proper noun (trademark); also cited as a verb | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.152. |
| eBay | example of a brand/company name spelled with a lowercase initial letter followed by a capital letter; need not be capitalized at the start of a sentence/heading, though some editors reword to avoid it. | proper noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.153; example sentence given: "eBay posted strong earnings." |
| iPod | same lowercase-initial-then-capital naming pattern as eBay; cf. iPhone. | proper noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.153. |
| midcap | an internal capital letter inside a brand/company/product name beyond the initial letter (e.g. the "B" in eBay, the "P" in iPod, the internal capitals in GlaxoSmithKline) — informal term the source says is "sometimes called" this. | noun (editorial/publishing terminology) | technical | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.153; CMOS directs that such internal capitals should be "left unchanged." |
| GlaxoSmithKline | example of a company name with additional internal capitals ("midcaps") that should be left unchanged in text. | proper noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.153. |
| HarperCollins | same midcap-preservation example as GlaxoSmithKline. | proper noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.153. |
| LexisNexis | same midcap-preservation example as GlaxoSmithKline. | proper noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.153. |
| headline style (headline-style capitalization) | the capitalization convention for titles in which the first and last words and all "major" words (nouns, pronouns, verbs, adjectives, adverbs, some conjunctions) are capitalized, while articles, most prepositions, and coordinating conjunctions are lowercased. | noun phrase (editorial/style terminology) | technical | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §§8.155, 8.157–8.159; CMOS's default style for titles mentioned/cited in text and notes. |
| sentence style (sentence-style capitalization) | the capitalization convention in which only the first word of a title, the first word of a subtitle, and proper names are capitalized — the style common in library catalogs, some journals' reference lists, and most foreign-title citation. | noun phrase (editorial/style terminology) | technical | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.156. |
| reverse italics | the convention of setting a term that would normally itself be italicized (a foreign word, a genus name, a ship's name) in roman type specifically because it falls inside an already-italicized title, so it reads as the "non-italic" element against the italic background. | noun (editorial/typesetting terminology) | technical | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.171; example given: *From Tyrannosaurus rex to King Kong: Large Creatures in Fact and Fiction* (the genus-species name set in roman inside the italic title). |

## Grammar points

### §8.151 — Metric spellings: American vs. European
CMOS prefers the traditional American spellings *meter*, *liter*, etc., over European variants
(*metre*, *litre*), even though some American business/government/professional organizations have
adopted the European forms. Abbreviations for SI units are covered elsewhere (§§10.54–62).

### §8.152 — Trademarks: capitalize, or better, genericize
Trademarked brand names (often flagged as such in dictionaries) should be capitalized if used at
all, but CMOS's preferred fix is to substitute a generic term instead when one is available (e.g.
"buffered aspirin" rather than "Bufferin"). The ® and ™ symbols that often accompany trademarks on
packaging carry no legal requirement to appear in running prose and should generally be omitted; if
either symbol must appear, it goes before any following punctuation mark. Some trademark owners
discourage use of their brand name as a verb (e.g. turning "Xerox" into "to xerox"), and while
corporate style guides may bind in-house documentation, this isn't legally binding on outside
writers — in fact *Webster's* itself enters the lowercase verbs *google* and *xerox*. Computer-related
brand names/terms are covered separately (§7.76).

### §8.153 — Brand names with an initial lowercase letter ("eBay," "iPod")
Brand/company names styled with a lowercase initial letter followed by a capital (eBay, iPod,
iPhone) need not be capitalized even at the start of a sentence or heading — though some editors
prefer to reword around the problem instead. This departure from CMOS's older practice is justified
both by owner preference and by the fact that such names are already partly capitalized (on the
second letter). Internal capitals elsewhere in a name ("midcaps," e.g. GlaxoSmithKline, HarperCollins,
LexisNexis) should likewise be left unchanged. In text set fully in capitals, these lowercase-initial
distinctions are normally overridden (EBAY, IPOD, HARPERCOLLINS); in small-capitals/mixed-capitals
text they are preserved (e.g. "eBay" rendered with the "e" in regular case and "Bay" in small caps).

### §8.154 — Titles of works: scope of the following guidelines
The rules that follow in this part of the chapter govern how titles are treated when *mentioned or
cited in running text or notes* — covering books, journals, newspapers, websites, short works
(stories, poems, articles), divisions of longer works (parts, chapters, sections), unpublished works
(lectures), plays and films, radio/TV programs, musical works, and artworks. Full bibliographic
citation format for these same titles is handled separately, in chapters 14 and 15.

### §8.155 — General principle: headline style by default
Titles mentioned or cited in text and notes are normally capitalized headline-style (see §8.157).
Titles as they appear on a book's own cover or title page, or at the head of an article/chapter, may
deviate from CMOS's rules for aesthetic reasons without needing to be "corrected" when reproduced
that way. Capitalization of foreign-language titles is handled separately (§11.3).

### §8.156 — Sentence-style capitalization: principle and uses
Under sentence style, only the first word of the title, the first word of a subtitle, and any proper
names are capitalized. This is standard in library catalogs and in the reference lists of some
journals (§15.13), and is CMOS's recommended style for most foreign-language titles (§11.3). It's also
useful for certain subheadings (§2.17), including ones containing terms (like species names) that
carry their own required internal capitalization — note that under sentence style the specific
epithet of a binomial species name stays lowercase even though it would also stay lowercase under
headline style's rule 7 (see §8.157). Examples given: *The house of Rothschild: The world's banker,
1849–1999* and "Crossing *Magnolia denudata* with *M. liliiflora* to create a new hybrid: A success
story."

### §8.157 — The seven rules of headline-style capitalization
CMOS frames headline style as governed "mainly by emphasis and grammar," via seven numbered rules
(occasionally arbitrary, but meant to keep title styling consistent):
1. Capitalize the first and last words of a title and subtitle (subject to rule 7), and capitalize
   all other "major" words — nouns, pronouns, verbs, adjectives, adverbs, and *some* conjunctions.
2. Lowercase the articles *the*, *a*, *an*.
3. Lowercase prepositions regardless of length, *except* when used adverbially or adjectivally (*up*
   in "Look Up," *down* in "Turn Down," *on* in "The On Button," *to* in "Come To") or when the
   preposition is part of an adjectivally-used Latin phrase (*De Facto*, *In Vitro*).
4. Lowercase the coordinating conjunctions *and*, *but*, *for*, *or*, *nor*.
5. Lowercase *to* as an infinitive marker ("to Run," "to Hide") in any grammatical function, and
   likewise lowercase *as* in any grammatical function.
6. Lowercase the part of a proper name that would be lowercased in ordinary running text, such as
   *de* or *von*.
7. Lowercase the second part of a two-word species name (the specific epithet), such as *fulvescens*
   in *Acipenser fulvescens*, even when it falls as the last word of the title/subtitle (an explicit
   override of rule 1's "capitalize the last word" instruction).

### §8.158 — Worked examples of headline-style capitalization
A representative list of titles illustrating rule 1 (always) plus whichever of rules 2–7 the
parenthetical numbers flag, e.g. "A Little Learning Is a Dangerous Thing" (rule 2: article
lowercased); "Sitting on the Floor in an Empty Room, *but* Turn On, Tune In, and Enjoy" (rules 2, 3,
and 4, with *but* itself staying lowercase as a coordinating conjunction while *On*/*In* stay
capitalized as adverbial particles, not prepositions); "From *Homo erectus* to *Homo sapiens*: A
Brief History" (rules 3, 7); "Progress in In Vitro Fertilization" (rule 3 — the Latin phrase *In
Vitro* used adjectivally keeps its preposition capitalized).

### §8.159 — Capitalizing hyphenated compounds within a headline-style title
Four additional rules govern hyphenated terms inside a headline-style title (Chicago no longer
carves out exceptions for awkward-looking results, for consistency's sake — though display settings
like a book cover may still deviate):
1. Always capitalize the first element of the hyphenated compound.
2. Capitalize any subsequent element unless it's an article, a preposition, a coordinating
   conjunction (*and*, *but*, *for*, *or*, *nor*), or a modifier like *flat*/*sharp* following a
   musical key symbol.
3. If the first element is only a prefix or combining form that couldn't stand alone as a word (e.g.
   *anti-*, *pre-*), don't capitalize the second element unless it's a proper noun/adjective — hence
   "Anti-intellectual Pursuits."
4. Capitalize the second element of a hyphenated spelled-out number (*Twenty-First*) or a hyphenated
   simple fraction (*Two-Thirds* in "Two-Thirds Majority") — a departure from older Chicago practice,
   recognizing the two halves' functional equality around the hyphen.
Worked examples include "A History of the Chicago Lying-In Hospital" (rule 2; note *In* here
functions as an adverb, not a preposition, so it stays capitalized) and "Does E-mail Alter Thinking
Patterns?" (rule 3).

### §8.160 — Titles that are themselves a direct quotation
When a direct quotation of a full sentence or independent clause is used as a title, CMOS still
imposes headline-style capitalization on it — even for a fairly long quotation — because doing so
aids identification of the words as a title. (Cross-reference: §14.104.) Example: "'We All Live More
Like Brutes Than Like Humans': Labor and Capital in the Gold Rush."

### §8.161 — Italics vs. quotation marks: which titles get which
Whether a cited title is set in italics or enclosed in quotation marks depends on the type of work.
Books and periodicals are italicized (§8.166); articles, chapters, and other short/subordinate works
are set in roman and enclosed in quotation marks (§8.175). The section lists the specific
cross-references governing each work type: book series/editions (§8.174), poems and plays
(§§8.179–82), unpublished works (§8.184), movies/TV/radio (§8.185), websites and blogs (§§8.186–87),
musical works (§§8.188–92), artworks and exhibitions (§§8.193–95), and foreign titles (§§11.3–8).

### §8.162 — A subtitle always starts with a capital letter
Regardless of whether the overall title uses sentence style or headline style, the subtitle's first
word is always capitalized, even in sentence style where it otherwise wouldn't be. A subtitle is
conventionally separated from the main title by a colon when cited in text, even if the title page
itself distinguishes them only by typeface. When an em dash rather than a colon separates the two
parts in the original, what follows the dash is *not* treated as a true subtitle, and its first word
isn't automatically capitalized — illustrated by the contrast between "'Manuals of Style: Guidelines,
Not Strangleholds'" (headline-style subtitle after a colon) and "*Chicago—a Metropolitan Smorgasbord*"
(lowercase word after an em dash, not treated as a capitalized subtitle). (Cross-reference: §14.98.)

### §8.163 — What may (and may not) be changed when citing a title
When a title is cited in text, notes, or a bibliography/reference list, its **original spelling**
(including non-Latin letters, such as *π* or *γ* — see the mojibake note above) **and hyphenation
must be preserved** regardless of the surrounding text's own style. What *may* be changed: (1)
capitalization, to either headline style (§8.157) or sentence style (§8.156), as appropriate for
context; (2) an ampersand may, at editorial discretion, be changed to *and* — or, more rarely, a
numeral spelled out (§14.96); (3) a comma dropped from a title-page line-ending for aesthetic
layout reasons should be restored when the title is cited, including before a date that originally
sat alone on its own line (serial commas are added only if their use elsewhere in the work confirms
the author's practice; §6.18); (4) if title and subtitle are distinguished on the title page by
typeface alone, a colon must be inserted between them when the full title is cited; a dash actually
present in the original should be kept, but a semicolon between title and subtitle may usually be
changed to a colon (two-subtitle cases: §14.98; older titles: §14.106). Four worked examples show
normal title/subtitle punctuation and headline-vs.-sentence capitalization choices, the fourth being
a periodical-article citation with a title-within-a-title (for which see §§8.171, 8.175).

### §8.164 — A title's own punctuation vs. the surrounding sentence's punctuation
A title functions grammatically as a singular noun and always takes a singular verb regardless of
whether the title itself is plural in form (e.g. "*The Waves* is not a typical novel"). The title's
internal punctuation doesn't affect how the surrounding sentence is punctuated, with one exception: a
sentence-ending period is omitted after a title that itself ends in a question mark or exclamation
point (§6.118). Examples: "Her role in *Play It Again, Sam* confirmed her stature" (no comma is added
after *Sam* just because the surrounding sentence structure might otherwise call for one); "Three
stories she never mentioned were 'Are You a Doctor?,' 'The Library of Babel,' and 'Diamond as Big as
the Ritz.'" (a comma is still added after the first title's own question mark, since the comma belongs
to the surrounding list, not the title). (Cross-references: §§6.23, 6.119, 8.172.)

### §8.165 — Old-fashioned double titles joined by "or"
Older double titles (title-and-subtitle pairs joined by *or*, sometimes as "...; or, ...") are
traditionally rendered with a semicolon, comma, and lowercase *or*: "*England's Monitor; or, The
History of the Separation*." A simpler, less traditional alternative drops the semicolon and
following comma: "*England's Monitor, or The History of the Separation*." CMOS prefers the first
(traditional) form, but accepts either as long as it's used consistently.

### §8.166 — How book and periodical titles are treated
Titles and subtitles of books and periodicals, when mentioned in text, notes, or a bibliography, are
italicized and capitalized headline-style (§8.157) — though some publications may call for sentence
style in their own reference lists (§§8.156, 15.13). A title cited in full in notes/bibliography may
be shortened when mentioned again in running text (e.g. dropping the subtitle); short-title
conventions for notes are covered separately (§14.25).

### §8.167 — Dropping (or keeping) an initial "a," "an," or "the" in a book title
An initial article at the start of a book title may be dropped from running text if doing so doesn't
disrupt the surrounding sentence's syntax. When in doubt, or when the article feels indispensable to
the title's identity, it should be retained. Contrast: "Fielding, in his introduction to *The History
of Tom Jones, a Foundling*, announces himself..." / "Fielding's *History of Tom Jones*..." (article
dropped, fits the possessive construction) vs. "In *The Old Curiosity Shop*, Dickens..." (article kept,
since dropping it would read awkwardly directly after "In").

### §8.168 — An initial "the" in periodical titles is usually lowercased, not dropped
Unlike book titles, when a newspaper or periodical is mentioned in text, an initial *the* — even when
it's technically part of the periodical's official name — is lowercased (unless it begins the
sentence) and *not* italicized: "She reads the *Chicago Tribune* on the train." Foreign-language
periodical titles retain their own article in the original language, but only when that article is
truly an official part of the title (e.g. "We read *Le Monde* and *Die Zeit*..."; "...the review in
the *Frankfurter Allgemeine*?"). In citation form (bibliography/notes), an initial *the* is dropped
from periodical titles altogether, though foreign-language articles are kept (§§14.210–11).

### §8.169 — "Magazine," "journal," "review" as part of a title vs. as a descriptive label
A generic word like *magazine*, *journal*, or *review* is italicized only when it's genuinely part of
a periodical's official name; when the same word is merely added afterward as a descriptive label
(not part of the actual title), it's set in roman as ordinary surrounding text. Contrast: "...the
*Partisan Review*" (the word is part of the official title, italicized) vs. "I read it...in *Time*
magazine" (here *magazine* is a descriptive add-on, not italicized) — but "...reprinted in the *New
York Times Magazine*" (here *Magazine* genuinely is part of that publication's official name, so it's
italicized).

### §8.170 — Periodical names embedded in the name of something else
When a newspaper or periodical's name becomes part of the name of a building, organization, prize, or
similar entity, it is *not* italicized in that context — e.g. "Los Angeles Times Book Prize,"
"Chicago Defender Charities," "Tribune Tower." The periodical name has effectively become a proper
name of something else, not a reference to the publication itself.

### §8.171 — Reverse italics for a term that would itself be italic, inside an italic title
Any term that would normally be italicized in ordinary running text (a foreign word, a genus name, a
ship's name) is instead set in roman type ("reverse italics") when it occurs inside a title that is
itself italicized — so the italic/roman contrast still signals "this word is special" even though
the title's overall italic setting would otherwise swallow that distinction. If a shorter work's
title (set in roman, inside quotation marks) is itself nested within another italicized title, it
stays in italics and keeps its quotation marks. Examples: "From *Tyrannosaurus rex* to King Kong:
Large Creatures in Fact and Fiction" (the genus-species name reverts to roman inside the italic
title); "*The Big E: The Story of the USS* Enterprise" (the ship's name *Enterprise* reverts to roman);
"*A Key to Whitehead's 'Process and Reality'*" (a quoted shorter-work title nested inside an italic
title keeps its own italics and single quotation marks). (Cross-references: §§8.163, 8.115, 8.119,
14.103.)

### §8.172 — A work's title isn't interchangeable with a description of its subject
CMOS cautions against using a work's own title as a stand-in for a plain description of what the work
is about — e.g. write that Dostoevsky wrote a book *about crime and punishment*, not that he wrote a
book *about Crime and Punishment* (which would misleadingly imply the book is about its own title).
Two further contrastive examples show how this distinction plays out when another author's book
title happens to echo the subject being discussed, and when a nested quoted phrase ("not") clarifies
which reading is intended.

### §8.173 — Multivolume works are treated like single-volume titles
Titles of multivolume books follow the same rules as single-volume titles, as do the individually
named titles of particular volumes within a multivolume set. The word *volume* is capitalized (and
never abbreviated) only when it's actually part of the title itself; otherwise it may be abbreviated
in parenthetical citations and notes (full treatment: §§14.121–27; see also §8.174). Examples: "*The
Day of the Scorpion*, volume 2 of *The Raj Quartet*"; "*Art in an Age of Counterrevolution,
1815–1848* (vol. 3, *A Social History of Modern Art*)"; "the fourth volume of *Encyclopaedia
Britannica*."

### §8.174 — Book series and editions: capitalize, don't italicize
Titles of book series and particular editions are capitalized but set in roman type (not
italicized). The words *series* and *edition* are themselves capitalized only when they're actually
part of the official series/edition name (full treatment: §§14.128–32). Examples: "the Loeb Classical
Library"; "a Modern Library edition" (lowercase *edition*, not part of the official name); "*Late
Editions: Cultural Studies for the End of the Century*" (here *Editions* is part of an italicized
book title, a different case); "the Crime and Justice series"; "a book in the Heritage of Sociology
Series" (capitalized *Series*, since it's part of that series' actual name).

### §8.175 — Articles, short stories, essays, and chapter/part titles take quotation marks
Titles of periodical/newspaper articles and features, book chapter and part titles, and titles of
short stories or essays are set in roman type and enclosed in double quotation marks. If the original
title itself already contains quotation marks, those inner marks must be converted to single
quotation marks, as in the fourth example (see the mojibake note above for the decoded form):
"The article 'Schiller's 'Ode to Joy' in Beethoven's Ninth Symphony' received unexpected attention."
Titles of regular recurring departments or columns within a periodical, however, are set in roman
type with no quotation marks at all (cross-references: §§14.202, 14.205) — e.g. "In this week's Talk
of the Town, Lizzie Widdicombe features..."

### §8.176 — Collected-works volumes are italicized, not quoted
When two or more works that were originally published separately are later gathered into a single
volume — often as part of an author's "collected works" — the individual work titles inside that
volume are best italicized rather than placed in quotation marks, even though the same titles might
otherwise be treated as shorter/subordinate works. Example: "The introduction to the *Critique of
Pure Reason* in Kant's *Collected Works*..."

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`.
