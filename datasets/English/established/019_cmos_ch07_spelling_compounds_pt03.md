# English — Established Vocabulary/Grammar: Chapter 7, "Spelling, Distinctive Treatment of Words, and Compounds," Part 3 (§§7.47–7.70)

**Source:** University of Chicago Press Staff, *The Chicago Manual of Style* (16th edition, 2010),
Chapter 7, "Spelling, Distinctive Treatment of Words, and Compounds" — "Italics, Capitals, and
Quotation Marks" (Emphasis, Foreign Words, Highlighting Key Terms and Expressions, Words and Letters
Used as Words) through the start of "Music: Some Typographic Conventions," PDF pages 954–977
(continues from Part 2, which ended at §7.46/p. 953).

**Coverage note:** every grammar point (§§7.47–7.70, 24 numbered rules, one section per PDF page in
this range) and every distinct illustrative vocabulary item from this page range. As in Part 2, this
stretch of the chapter is predominantly mechanical/typographic convention (italics vs. roman,
capitals, quotation marks, letter names, musical notation) rather than a general vocabulary list —
the vocabulary table captures the distinct illustrative words/terms/phrases CMOS uses, not full
example sentences. Repeated example sentences within a rule that don't introduce a new term are
skipped per the coverage rule. This source has a clean text layer throughout (no vision-reading was
required); Vision Reading Confidence is `n/a` for every row below.

**Mojibake gotcha — found and corrected in this chunk.** Several non-ASCII characters in this page
range render as UTF-8-bytes-read-as-Windows-1252/Latin-1 mojibake, baked into the PDF's own visible
glyphs (not just a text-layer artifact under `pdftotext` — the rendered page images themselves show
the corrupted sequence). All instances below were corrected against context and cross-checked where
possible; corrections are flagged per row.

- `ComÃ©die-FranÃ§aise` → **Comédie-Française** (p. 958)
- `Ãngel de la Independencia` / `El Ãngel` → **Ángel de la Independencia** / **El Ángel** (p. 958)
- `pÃ©cher` / `pÃªcher` → **pécher** (to sin) / **pêcher** (to fish) (p. 957)
- `recherchÃ©` → **recherché** (p. 959)
- `Ã©pater les bourgeois` → **épater les bourgeois** (p. 959)
- `mise en scÃ¨ne` → **mise en scène** (p. 959)
- `grÃ¨ve du zÃ¨le` → **grève du zèle** (p. 956)
- `mead â€˜a beverage' and mead â€˜a meadow'` → the mojibake here is only curly single quotation
  marks (U+2018/U+2019 read as Latin-1); the underlying text ("mead 'a beverage' and mead 'a
  meadow'") was already correct once the quote marks are normalized — included for completeness
  since it's the same decoding mechanism (p. 957).
- `Gâ„¢¯` / `Bâ„¢­` → **G♯** (sharp) / **B♭** (flat) — these are a musical-symbol variant of the same
  UTF-8-as-Latin-1 mechanism (♯ = U+266F, ♭ = U+266D) rather than a letter/diacritic (p. 974).
- The Sanskrit/Prakrit terms in §7.50 (*majjao*, *marjaro*, *madjaro*, *mrij*) show no visible
  mojibake artifact, but given this source's confirmed pattern of silently dropping diacritics
  elsewhere in the project (see memory note on silent-diacritic-dropping), it is plausible the
  printed CMOS originally carried macrons/underdots (e.g., *mārjāra*, *mṛj*) that this PDF's
  rendering simply omits rather than corrupted. Flagged `low_confidence` on the affected rows rather
  than guessing at the diacritic placement.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| full caps | setting an entire word/phrase in capital letters | noun (typographic term) | technical.typography | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.48: distinguished from "capitalizing" (initial letter only). |
| small caps (small capitals) | capital letters set at roughly lowercase height | noun (typographic term) | technical.typography | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.48: CMOS's preferred alternative to full caps for emphasis, called "more graceful." |
| grève du zèle | a work slowdown achieved by excessively literal rule-following ("strike of zeal"/work-to-rule) | noun phrase (French idiom) | literary | — | — | — | — | grammar_reference | n/a | n/a | §7.49 example of an unfamiliar foreign phrase requiring italics; mojibake-corrected (see header note). Cited in English prose, not claimed as naturalized English vocabulary. |
| Honi soit qui mal y pense | "Shame on him who thinks evil of it" | phrase (Anglo-Norman French motto) | literary | — | — | — | — | grammar_reference | n/a | n/a | §7.49: motto of the Order of the Garter, given as an example of a foreign sentence set in italics. |
| pécher | to sin | verb (French) | — | — | — | — | — | grammar_reference | n/a | n/a | §7.50 example distinguishing a translator's word choice by accent mark; mojibake-corrected. |
| pêcher | to fish | verb (French) | — | — | — | — | — | grammar_reference | n/a | n/a | Paired contrast with *pécher* in §7.50; mojibake-corrected. |
| majjao | "the tomcat" | noun (Prakrit) | — | — | — | — | — | grammar_reference | n/a | n/a | §7.50 example of a linguistic-studies definition set off by single quotation marks; `low_confidence` — possible dropped diacritic (see header note). |
| marjaro | "the cat," from the verb for "to wash" (the cat's self-cleaning habit) | noun (Sanskrit) | — | — | — | — | — | grammar_reference | n/a | n/a | §7.50; `low_confidence` — likely corresponds to a macroned form (e.g. *mārjāra*) with diacritics dropped by this source's rendering. |
| madjaro | "my lover" | noun (Sanskrit) | — | — | — | — | — | grammar_reference | n/a | n/a | §7.50, offered as the other candidate Sanskrit etymon for *majjao*; `low_confidence`, same diacritic caveat. |
| mrij | "to wash" | verb (Sanskrit) | — | — | — | — | — | grammar_reference | n/a | n/a | §7.50; root cited as the source of *marjaro* ("the cat"); `low_confidence`, likely *mṛj* with the underdot dropped. |
| Compendio de i secreti rationali | "Compendium of rational secrets" | title (Italian/Latin) | literary | — | — | — | — | grammar_reference | n/a | n/a | §7.50: Leonardo Fioravanti's bestselling work, example of a title with its English translation parenthesized. |
| mead (beverage) | fermented honey-based alcoholic drink | noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.50: homograph pair illustrating single-quote definition style; curly-quote mojibake normalized (see header note). |
| mead (meadow) | archaic/poetic word for a meadow or grassy field | noun | archaic | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | Second sense of the same homograph pair, §7.50. |
| Comédie-Française | the French national theater | proper noun | literary | — | — | — | — | grammar_reference | n/a | n/a | §7.51 example of a foreign proper noun left unitalicized in English context; mojibake-corrected (see header note). |
| Ángel de la Independencia | Mexico City's Independence Angel monument, familiarly "El Ángel" | proper noun | regional | — | — | Mexico | city (Mexico City) | grammar_reference | n/a | n/a | §7.51; mojibake-corrected (see header note). |
| Leghorn | English exonym for the Italian port city of Livorno | proper noun | archaic | — | — | — | — | grammar_reference | n/a | n/a | §7.51: cited as an example of an anglicized foreign place-name that is itself not italicized. |
| pasha | a high-ranking title in the Ottoman political/military system | noun | literary | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.52: listed as a *Webster's*-naturalized foreign word set in roman type, not italics. |
| weltanschauung | a comprehensive personal or cultural worldview | noun | formal | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.52: German loanword; CMOS notes German nouns kept lowercase even when naturalized, unlike German's own capitalization convention. |
| in vitro | occurring in a lab vessel rather than a living organism | adverb/adjective phrase (Latin) | technical | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.52 example of a naturalized Latin phrase. |
| a priori | reasoned from theoretical deduction rather than observation | adverb/adjective phrase (Latin) | formal | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.52 example. |
| recherché | elegantly refined, sought-out, or rarefied in taste | adjective | formal | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.52; French-derived, naturalized per *Webster's*; mojibake-corrected (see header note). |
| the kaiser | the German emperor's title, used generically | noun | historical | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.52: cited specifically to show naturalized German nouns are lowercased in English, unlike "Kaiser" in German. |
| de novo | starting anew, from the beginning | adverb phrase (Latin) | technical | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.52 example. |
| eros | passionate/romantic love | noun (Greek) | literary | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.52, paired with *agape* as a naturalized Greek term for a type of love. |
| agape | selfless, unconditional love | noun (Greek) | literary | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.52, paired with *eros*. |
| épater les bourgeois | to deliberately shock or scandalize conventional/middle-class sensibilities | verb phrase (French idiom) | literary | — | — | — | — | grammar_reference | n/a | n/a | §7.52: given as a *contrast* example — explicitly NOT in *Webster's*, so it stays italicized even in the same discussion as naturalized terms; mojibake-corrected (see header note). |
| mise en scène | the staging/visual arrangement of a theatrical or film scene | noun (French, naturalized) | technical | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.52: familiar/*Webster's*-listed, roman type; mojibake-corrected (see header note). |
| mise en bouteille | "bottled" (of wine) | noun phrase (French, not naturalized) | — | — | — | — | — | grammar_reference | n/a | n/a | §7.52: explicit contrast with *mise en scène* — not in *Webster's*, stays italicized; CMOS's rule is that when a familiar and unfamiliar foreign term co-occur, both or neither should be italicized for consistency. |
| ibid. | "in the same place" — citation abbreviation referring to the immediately preceding source | abbreviation (Latin) | technical | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.53: commonly used Latin abbreviation, set in roman (not italics). |
| et al. | "and others" | abbreviation (Latin) | technical | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.53. |
| ca. | "about, approximately" (circa) | abbreviation (Latin) | technical | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.53. |
| passim | "throughout, in various places" (of citations) | adverb (Latin) | technical | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.53. |
| sic | "thus, so" — editorial marker flagging a quoted error as reproduced faithfully | adverb/interjection (Latin) | technical | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.53: exception to the roman-Latin rule — kept italicized because of its "peculiar use in quoted matter." |
| obstructionism | the deliberate tactic of blocking or delaying a process | noun | formal | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.54 example of a first-occurrence-italicized key term. |
| misinformation | false or inaccurate information, especially spread unintentionally | noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.54, paired with *obstructionism* as a key term requiring careful analysis. |
| scare quotes | quotation marks used to flag a term as nonstandard, ironic, slang, or otherwise not the writer's own usual word | noun | technical.typography | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.55: CMOS's own nickname for this device; explicitly tied to slang/ironic/special-sense usage. |
| so-called | preceding a word/phrase to signal irony or doubt about it | adjective/adverb | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.56: CMOS notes the word itself does the ironic work, so quotation marks around the following term are usually redundant. |
| techies | people enthusiastic about or skilled in technology | noun (plural, informal) | slang | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.57 example sentence ("Only techies will appreciate this joke"), cited by CMOS as an instance of common/slang-adjacent phrasing needing no quotation marks. |
| critical mass | the minimum threshold of something (people, momentum, material) needed to become self-sustaining | noun phrase | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.58: CMOS notes it's more often used metaphorically than in its literal (nuclear-physics) sense. |
| neurobotics | the engineering field combining neuroscience and robotics | noun (technical coinage) | technical | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.58 example of a word discussed as itself (italicized), not used functionally. |
| mind your p's and q's | be careful about your behavior/manners | phrase (idiom) | colloquial | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.59: one of two idioms CMOS flags as a traditional exception kept in roman type (no apostrophe-marked plural italics). |
| dotting the i's and crossing the t's | attending carefully to every last detail | phrase (idiom) | colloquial | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.59, the second roman-type idiom exception. |
| the three Rs | reading, writing, and arithmetic — the basics of elementary education | noun phrase (idiom) | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.61 example of a capital-letter plural needing no apostrophe. |
| S curve | a curve shaped like the letter S | noun (compound) | technical | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.63 example of a letter used to denote a shape. |
| L-shaped | shaped like the letter L | adjective (compound) | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.63, paired example ("an L-shaped room"). |
| bee | name of the letter *b* | noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.64: letter names drawn from *Webster's Collegiate*, set in roman without quotation marks. |
| cee | name of the letter *c* | noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.64. |
| dee | name of the letter *d* | noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.64. |
| ef | name of the letter *f* | noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.64. |
| gee | name of the letter *g* | noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.64. |
| aitch | name of the letter *h* | noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.64. |
| jay | name of the letter *j* | noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.64. |
| kay | name of the letter *k* | noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.64. |
| el | name of the letter *l* | noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.64. |
| em | name of the letter *m* | noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.64. |
| en | name of the letter *n* | noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.64. |
| pee | name of the letter *p* | noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.64. |
| cue | name of the letter *q* | noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.64. |
| ar | name of the letter *r* | noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.64. |
| ess | name of the letter *s* | noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.64. |
| tee | name of the letter *t* | noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.64. |
| vee | name of the letter *v* | noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.64. |
| double-u | name of the letter *w* | noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.64: the only polysyllabic/compound letter name in the set. |
| ex | name of the letter *x* | noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.64. |
| wye | name of the letter *y* | noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.64. |
| zee | name of the letter *z* (American English; British "zed" not mentioned by CMOS here) | noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.64. |
| rhyme scheme | the pattern of end rhymes in a poem, denoted by lowercase italic letters | noun phrase | technical.literary | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.65 example: the Shakespearean sonnet's scheme *abab, cdcd, efef, gg*. |
| middle C | the C note at roughly the center of a piano keyboard, used as a reference pitch | noun | technical.music | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §§7.67–7.68. |
| sharp (♯) | raised by a half step; also the symbol itself | adjective/noun | technical.music | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.67; the ♯ symbol itself was mojibake (`Gâ„¢¯`) in this PDF's rendering of the "G-sharp or G♯" example — corrected (see header note). |
| flat (♭) | lowered by a half step; also the symbol itself | adjective/noun | technical.music | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.67; the ♭ symbol was similarly mojibake (`Bâ„¢­`) in the "B-flat minor or B♭ minor" example — corrected. |
| natural (♮) | canceling a previous sharp or flat | adjective/noun | technical.music | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.67, named alongside *sharp* and *flat* as a term set in roman and preceded by a hyphen when spelled out. |
| augmented triad | a three-note chord with two major thirds stacked, raising the fifth | noun phrase | technical.music | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.67 example: "an F augmented triad." |
| A 440 | the standard reference pitch (A above middle C tuned to 440 Hz) | noun phrase | technical.music | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.68 example of a letter-plus-number pitch designation. |
| octave | the interval between a note and the next note of the same name at double/half frequency | noun | technical.music | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.68: CMOS describes several competing octave-register notation systems (C/C₁/C₂ vs. c/c¹/c² vs. scientific C₀–C₈₈). |
| dominant seventh chord | a major chord on the fifth scale degree with an added minor seventh | noun phrase | technical.music | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.69 example, notated V⁷. |
| mediant | the third degree of a musical scale, or a chord built on it | noun | technical.music | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §7.69 example, notated with lowercase roman numeral *iii* (minor-quality chord). |

**Morpheme breakdown:** not applicable — English in this chunk is non-agglutinative, and no term
above has internal compositional structure that an atomic gloss would obscure. (The foreign-language
items — French, Sanskrit, Prakrit, German, Latin, Greek, Italian — are glossed as whole lexical
items per the source's own treatment; no cross-linguistic morpheme analysis was attempted, since
that is out of scope for an English-chapter extraction.)

## Grammar points

### 7.47 Italics for emphasis

Italics for emphasis should be an occasional device, not habitual — overuse dilutes their force, and
a whole passage should essentially never be italicized for emphasis. A sentence's natural end
position can already carry dramatic weight without needing italics; italics become necessary only
when the emphasis genuinely depends on them, as in distinguishing "It *was* Leo!" from a neutral
statement (p. 954).

### 7.48 Capitals for emphasis

Full capitalization of a word/phrase for emphasis is now read as either ironic or, in dialogue/signage
representation, simply loud (e.g. "WATCH OUT!"). CMOS distinguishes "capitalizing" a word (only the
initial letter) from "full caps" (the whole word) and recommends small capitals over full capitals
when emphasis is genuinely wanted, since small caps look more graceful; headline-style representation
(e.g. "POLAR ICE CAP RETURNS") is one accepted use of full caps (p. 955).

### 7.49 Italics for unfamiliar foreign words and phrases

An isolated foreign word or phrase likely to be unfamiliar to readers is italicized; once it becomes
familiar through repeated use in a single work, only its first occurrence needs italics. A foreign
sentence or longer passage is instead set in roman and enclosed in quotation marks (p. 956).

### 7.50 Parentheses and quotation marks for foreign words and phrases

A translation following a foreign word/phrase/title is enclosed in parentheses or quotation marks.
In linguistic/phonetic writing specifically, a definition is conventionally enclosed in single
quotation marks with no intervening punctuation, and any punctuation that follows goes after the
closing quotation mark (p. 957).

### 7.51 Proper nouns

Foreign proper nouns are not italicized when used in an English context, even when they retain
foreign spelling, accents, or an anglicized form (p. 958).

### 7.52 Roman for familiar foreign words

A foreign word or phrase that has become familiar to most readers — defined operationally as being
listed in *Webster's* — is set in roman type, spelled exactly as *Webster's* gives it; German nouns
that have been so naturalized are lowercased, departing from German's own capitalization convention.
When a familiar (roman) and unfamiliar (italic) foreign term occur in the same context, CMOS
recommends treating both consistently — either both italicized or neither — to avoid an inconsistent
look (p. 959).

### 7.53 Roman for Latin words and abbreviations

Commonly used Latin words and abbreviations (*ibid.*, *et al.*, *ca.*, *passim*) are set in roman,
not italics. *Sic*, despite being Latin, is an exception kept in italics because of its specialized
editorial function inside quoted matter, where it flags that an apparent error is being faithfully
reproduced rather than introduced by the current author (p. 960).

### 7.54 Italics for key terms

A key term central to a particular discussion is often italicized on its first occurrence within
that discussion and set in roman thereafter — a distinct convention from the general foreign-word
rule, applying to any term (including ordinary English words like *obstructionism* or
*misinformation*) singled out as newly central (p. 961).

### 7.55 "Scare quotes"

Quotation marks are frequently used to signal that a term is being used in a nonstandard, slang,
ironic, or otherwise special sense — nicknamed "scare quotes." CMOS cautions that, like italics for
emphasis, the device loses force and irritates readers if overused. In philosophical writing, single
quotation marks sometimes serve a similar function, but CMOS discourages that practice outside
contexts where it's essential to clarity of argument (p. 962).

### 7.56 "So-called"

A word or phrase already preceded by "so-called" generally doesn't also need quotation marks, since
"so-called" itself signals the irony or doubt. Quotation marks remain useful, however, when only part
of a longer phrase needs to be singled out for that ironic emphasis (p. 963).

### 7.57 Common expressions and figures of speech

Ordinary idioms and figures of speech — including slang — rarely need quotation marks. CMOS reserves
them for cases where a phrase is quoted verbatim from a different context, or used pointedly ironic,
giving "for whom the bell tolls" (quoted from its literary source) as a contrast case against plainly
idiomatic phrases like "I grew up in a one-horse town" or "Only techies will appreciate this joke,"
which need no quotation marks at all (p. 964).

### 7.58 Words and phrases used as words

When a word or term is discussed as the word itself rather than used functionally, it's set in
italics or enclosed in quotation marks; a proper noun used this way is usually left in roman. Italics
are the traditional default, but quotation marks can be more practical in electronic contexts, and
are also useful for conveying the idea of reported speech, as opposed to setting off a foreign term
from its English gloss (p. 965).

### 7.59 Letters as letters

Individual letters of the Latin alphabet, discussed as letters, are usually italicized (e.g. "the
letter *q*"); their plurals are formed with an apostrophe-plus-*s*, and the *s* itself stays roman
even when the letter is italic. Two idioms — "mind your p's and q's" and "dotting the i's and
crossing the t's" — are a traditional exception kept fully in roman type. Roman type is also always
used for phonetic symbols, for which CMOS points readers to Pullum and Ladusaw's *Phonetic Symbol
Guide* (p. 966).

### 7.60 Scholastic grades

Letter grades are usually capitalized and set in roman; their plural needs no apostrophe (e.g. "three
As, one B, and two Cs") (p. 967).

### 7.61 Plurals of letters

For legibility, the plural of a single lowercase letter takes an apostrophe before the *s* (to avoid
misreadings like confusing "two as" with "two a's"); the *s* stays roman even when the letter itself
is italic. Capital letters don't normally need the apostrophe in their plural (e.g. "the three Rs"),
though CMOS advises avoiding a sentence-initial plural of "A" or "I" specifically, since those could
misread (p. 968).

### 7.62 Letters standing for names

A letter substituting for an actual name (e.g. to anonymize a party in a hypothetical, as in "A sues
B") is capitalized, set in roman, and takes no period, since it bears no formal relation to a real
name. A genuine single-initial abbreviation of a real name takes a period; if the initial is instead
used to conceal an actual name, it may be followed by a 2-em dash with no period (and a following
space if no other punctuation follows). When two or more initials stand in for an entire name with no
periods (e.g. "JFK," "LBJ"), none are needed (p. 969).

### 7.63 Letters as shapes

A letter used to describe a shape (an "S curve," an "L-shaped room") is capitalized and set in roman.
CMOS notes that mixing a sans serif letterform into otherwise serif body text, sometimes done for
this purpose, doesn't necessarily help comprehension and can look clumsy unless the two typefaces
genuinely complement each other (p. 970).

### 7.64 Names of letters

Because a letter's spoken/written name (e.g. "a cue, not a gee") can't always be inferred from
context, CMOS gives a standard roman-type, non-quotation-marked spelling for each consonant, drawn
from *Webster's Collegiate* — the full set (*bee, cee, dee, ef, gee, aitch, jay, kay, el, em, en,
pee, cue, ar, ess, tee, vee, double-u, ex, wye, zee*) is tabulated above. Vowels aren't individually
named in standard dictionaries; CMOS recommends illustrating a vowel instead by example ("*a* as in
*apple*"). Names for non-Latin/special characters are covered separately in chapter 11 (p. 971).

### 7.65 Rhyme schemes

Lowercase italic letters, run together with no space, denote a poem's rhyme scheme or similar
repeating pattern — e.g. the Shakespearean sonnet's *abab, cdcd, efef, gg* (p. 972).

### 7.66 Suggested reference for music publishing

Music publishing is specialized enough that CMOS only touches on it briefly, pointing readers to D.
Kern Holoman's *Writing about Music* for detailed guidelines, an illustration of typeset music in the
manual's own figure 3.5, and *The New Grove Dictionary of Music and Musicians* (available via Oxford
Music Online) as a fuller reference (p. 973).

### 7.67 Musical pitches

Letters denoting musical pitches (and, by extension, keys and chords) are set as roman capitals.
"Sharp," "flat," and "natural," when spelled out rather than symbolized, are set in roman and
preceded by a hyphen (e.g. "G-sharp" or "G♯"). CMOS flags that editors unfamiliar with musicological
convention should proceed cautiously — in harmonic analysis, a hyphenated "C-major triad" may be
understood as based on the *note* C rather than the *key* of C. A series of pitches in sequence is
joined by en dashes (p. 974).

### 7.68 Octaves

Several competing systems exist for designating octave register in technical/scientific writing:
lowercase letters for the octave below middle C (c, c♯, d...); lowercase letters with superscript
numbers or primes for octaves above middle C (c¹, c², or c′, c″); capital letters with subscript
numbers, in descending order, for lower octaves (C, C₁, C₂); and a "scientific" system using capital
letters and subscripts starting at C₀ (middle C = C₄) up to C₈₈ at the top of a full piano
keyboard. Because the systems vary, CMOS recommends flagging early in a text which system is in use.
Simultaneously sounding pitches (chords) are listed from lowest to highest, sometimes joined by plus
signs (e.g. "C + E + G") (p. 975).

### 7.69 Chords

In harmonic analysis, chords are denoted by roman numerals indicating which scale degree they're
built on (e.g. V = a chord on the fifth/dominant degree; iii = a chord on the third/mediant degree).
Harmonic progressions are shown as a sequence of capital roman numerals joined by en dashes (e.g.
"IV–I–V–I"). For more technical writing, minor-quality chords are distinguished with lowercase roman
numerals, and additional symbols/arabic numerals indicate further chord-quality distinctions (e.g.
V⁷ for a dominant seventh chord) (p. 976).

### 7.70 "Major" and "minor"

In musical writing that discusses many keys, an alternative convention uses capital letters for major
keys and lowercase for minor keys; when this convention is followed, the words "major" and "minor"
themselves are typically omitted as redundant (p. 977).

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `../../00_Reference_Extraction_Spec.md`.
