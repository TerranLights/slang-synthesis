# Danish — Established Vocabulary/Grammar: Teach Yourself Danish (full book)

**Source:** Bente Elsworth, *Danish: A Complete Course for Beginners* (Teach Yourself Books; first
published UK 1994, US edition NTC/Contemporary Publishing 1997). Full book: the Pronunciation guide
and all 18 units, plus the "Strong and irregular verbs" appendix. The "Key to the exercises" and the
end-of-book "Danish–English vocabulary" glossary were deliberately skipped as redundant recap of
material already captured per-unit (see `00_Reference_Extraction_Spec.md`'s coverage rule).

**Critical correction to this book's original cataloguing: it has NO usable text layer**, despite
having been catalogued elsewhere in this project as "confirmed TEXT." Direct inspection during this
extraction pass found that both `pdftotext` and `pdftotext -layout` produce pure OCR-noise garbage
throughout the entire 141-page PDF — not a decodable font-substitution cipher (verified: no fixed
1:1 character mapping recovers it), just garbled noise. The underlying scan itself is clean,
well-printed, and fully legible; only the embedded text layer is broken. **The entire book was
therefore vision-read from page images** rendered at 150 DPI. Each PDF page is a two-printed-page
spread; the PDF-page-to-printed-page mapping was verified empirically (for PDF page N ≥ 3: left
printed page = 2N−6, right printed page = 2N−5) by directly reading several sample pages before
committing to any range, and re-confirmed at multiple unit boundaries during extraction. No
handwritten marginalia was found anywhere in the book — it is a clean, unmarked scan throughout.

**Vision Reading Confidence methodology:** every vocabulary row below was read from a rendered page
image rather than a text layer (hence `n/a` throughout the Transcription Confidence column, which
only applies to subtitle/transcript sources). `verified` marks an item cross-checked against its own
dialogue/commentary context elsewhere on the same or a nearby page; `plausible_unverified` marks an
item read with reasonable confidence but not independently cross-checked; `low_confidence` is
reserved for genuine doubt (faded print, a scan artifact, an unusual font) — none was needed anywhere
in this book, since every rendered page across all extraction passes was clean, legible, typeset
print with zero marginalia.

**Coverage note:** every grammar point and every distinct vocabulary item from the Pronunciation
guide and all 18 units, plus the Strong and irregular verbs appendix, is captured below — full
coverage, closing out the two prior partial-coverage passes (an initial representative sample, then
a follow-up pass that brought Units 1-16 to full coverage) with the remaining gaps in Units 17-18
and the verb appendix now filled and cross-validated against independently-produced duplicate
extractions of that material (reconciled, not concatenated — see per-item notes in Units 17-18 below
for the handful of cases where one pass's reading was kept over the other's). The merged table below
holds **1,832 vocabulary rows** (plus a separate 64-row strong/irregular-verb paradigm table inside
the Grammar points section, which uses its own 4-column infinitive/present/past/past-participle
format rather than the 12-column vocabulary schema). Repeated drill exercises (Øvelser) and duplicate
example sentences that introduce no new vocabulary or grammar are skipped, per the extraction spec's
coverage rule. This is a long, plot-driven course book (following George Wilson, a British
businessman, and his wife Alison, visiting their Danish friends Hans and Lone Petersen in
Copenhagen) — later units' vocabulary and grammar points increasingly presuppose earlier ones, so
earlier-unit cross-references in the grammar section below are the book's own internal structure,
not an artifact of extraction.

**Flagged findings — slang/colloquial/register content.** This book's own vocabulary boxes carry no
explicit "informal"/"formal" register labels (unlike its sibling *Colloquial Danish*, this project's
other Danish course book, which tags register explicitly throughout) — every `colloquial`/`slang`
tag in the vocabulary table below is therefore extractor judgment based on conversational register
and idiomaticity, not a source-marked annotation, flagged per-row in the Notes column. Despite that,
the book's own grammar commentary does explicitly discuss several register-relevant systems:

- **Unit 8's "nok" passage and Unit 16's fuller treatment systematically present Danish's unstressed
  modal/discourse particles — da, dog, jo, nok, nu, vel, vist** — explicitly described by the book
  as adverbs that add "an implied other meaning...a subjective reaction" rather than literal content.
  This is directly relevant to this project's slang-mechanism tracking: a whole closed class of
  particles whose function is almost entirely pragmatic/attitudinal rather than denotational.
- **skat** ("darling") — an intimate spousal/family address term, used between the book's own
  characters (Units 2 and 16).
- **hyggeligt/hygge** — flagged by the book itself as a culturally central, hard-to-translate Danish
  concept word (Unit 2).
- **Unit 7's formal demonstratives denne/dette/disse are noted as replaced by informal den/det/de +
  her/der in everyday speech** — an explicit written-vs-spoken register split.
- **Unit 9's molbohistorie/molboer** — a real Danish folk-tale genre mocking the dialect/intelligence
  of Mols-peninsula peasants (comparable to English "Gotham" tales), flagged as a taboo-adjacent
  regional-mockery naming mechanism worth downstream attention.
- **Unit 4's colloquial "hvad for en/et/nogen"** is the book's own explicit flagged substitute for
  the grammatically formal interrogatives hvilken/hvilket/hvilke.
- A cluster of mild exclamatory/intensifying particles across units: **dog** (impatience), **Men
  dog!**, **vel nok**, **lige** (politeness softener, contrasted explicitly with the more formal "Vil
  De være så venlig at..."), and **gerne** used both as "gladly" and as a frequency adverb.

See the Vocabulary table's `colloquial`/`slang`/`taboo`/`regional` rows throughout for the full set —
these bullets only name the highlights.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
### Pronunciation (printed pp. 6-11)

| det | it | pronoun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | pronunciation example, -t silent, p. 6 |
| bade | bathe | verb | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | long a example, p. 6 |
| kat | cat | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | short a example, p. 6 |
| mand | man | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | glottal stop (stød) minimal-pair example vs. **man**, p. 11 |
| man | one (impersonal pronoun) | pronoun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | minimal pair with **mand** showing the glottal stop, p. 11 |
| mor | mother | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | glottal-stop minimal-pair example vs. **mord**, p. 11 |
| mord | murder | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | minimal pair with **mor**, p. 11 |
| guld | gold | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | silent-d example (ld/nd/rd/ds/dt clusters), p. 10 |
| hund | dog | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | glottal-stop example [hun'], p. 11 |
| hun | she | pronoun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | contrasts with **hund** minus the glottal stop, p. 11 |

**Morpheme/sound note:** the Pronunciation section is a systematic phonology reference (alphabet, 9 vowels long/short, diphthongs, consonant system, the glottal stop, word stress) rather than a vocabulary list — see Grammar points below for the full system. Only a handful of its own illustrative minimal-pair words are tabulated above; the remaining ~40 single-word pronunciation examples (bede, fedt, lide, dit, skole, lokke, pude, kunne, byde, bytte, læse, men, høne, høns, håbe, hånd, mig, jeg, eje, vej, øje, løg, hav, pebber, livlig, og, lov, syv, evne, øvrig, låg, etc.) are purely phonetic illustrations of the vowel/diphthong system already captured structurally in the grammar point below and are not independently glossed here to avoid padding the vocabulary table with single-use phonetic props.

### Unit 1: På banegården — At the railway station

| dav | hi (informal greeting) | interjection | colloquial | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 13; book's commentary groups dav/hej/davs as informal vs. formal goddag |
| hej | hi (informal greeting) | interjection | colloquial | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 13 |
| davs | hi (informal greeting) | interjection | colloquial | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 15, Ordforklaringer; book groups with dav/hej as informal |
| goddag | good day / hello (formal) | interjection | formal | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 15; book's own formal/polite counterpart to dav/hej/davs |
| er | is | verb | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 13 |
| det | it | pronoun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 13 |
| i dag | today | adverb | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 13 |
| jeres | your (plural) | pronoun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 13 |
| venner | friends | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 13 |
| fra | from | preposition | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 13 |
| kommer | are coming, is coming | verb | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 13 |
| på fredag | on Friday | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 13 |
| hun | she | pronoun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 13 |
| flyver | is flying, will fly | verb | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 13 |
| herover | over here | adverb | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 13 |
| min mor | my mother | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 13 |
| også | also | adverb | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 13 |
| med toget | by train | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | lit. "by the train," p. 13 |
| med | with, by | preposition | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 13 |
| Jylland | Jutland | proper noun | core | — | contemporary (1994) | Denmark | national | grammar_reference | n/a | verified | p. 13 |
| skal | is going to | verb (modal) | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 13 |
| bo | stay, live | verb | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 13 |
| hos os | with us | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 13 |
| i en uge | for a week | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 13 |
| Hvad hedder din mor? | What is your mother called? | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 13 |
| og | and | conjunction | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 13 |
| Velkommen til Danmark | Welcome to Denmark! | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 15 |
| Tak! | Thank you! | interjection | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 15 |
| lang | long | adjective | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 15 |
| rejse | journey; to travel | noun/verb | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 15 |
| med båd og tog | by boat and train | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 15 |
| båd | boat | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 15; common gender (en båd) |
| til | to | preposition | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 15 |
| København | Copenhagen | proper noun | core | — | contemporary (1994) | Denmark | national | grammar_reference | n/a | verified | p. 15 |
| men | but | conjunction | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 15 |
| en interessant rejse | an interesting journey | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 15 |
| min nabos mor | my neighbour's mother | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 15; possessive -s example |
| nabo | neighbour | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 15 |
| køre | go, drive, ride, travel | verb | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 15 |
| Holte | Holte (a suburb of Copenhagen) | proper noun | core | — | contemporary (1994) | Denmark | local | grammar_reference | n/a | verified | p. 15 |
| Undskyld, ..? | Excuse me, ..? | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 15 |
| De | you (formal) | pronoun | formal | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 15 |
| fru | Mrs | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 15; abbreviated fru in Mr/Mrs/Miss/Ms table, p. 15 |
| Deres datter | your (formal) daughter | phrase | formal | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 15 |
| hjem | home | noun/adverb | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 15 |
| Mange tak! | Thanks! Many thanks! | interjection | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 15 |
| Jeg synes, ... | I think ... | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 15 |
| sige 'du' til hinanden | to say 'du' (informal you) to each other | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 15; sets up the du/De commentary |
| hinanden | each other | pronoun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 15 |
| Jeg er dus med alle | I say 'du' (informal you) to everybody | phrase | colloquial | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 15; "dus" as a derived informal-register adjective from the pronoun du itself |
| alle | everybody, all | pronoun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 15 |
| hr. | Mr | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | abbreviation of herre, p. 15 |
| frk. | Miss | noun | formal | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | abbreviation of frøken; book notes these titles are spelled lower-case except sentence-initially, p. 15 |
| fr. | Ms | noun | formal | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | book notes this cannot actually be pronounced in Danish — written-only title, p. 15 |
| Undskyld | Excuse me / I am sorry | interjection | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 15; literally "excuse (me)," used both as apology and to introduce a question |
| at være | to be | verb | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 17, infinitive of "er" |
| en turist | a tourist | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 22 |
| mange | many | determiner | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 22 |
| englændere | Englishmen, English people | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 22 |
| en hovedstad | a capital | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 22 |
| eller | or | conjunction | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 22 |
| derover | over there | adverb | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 22 |
| politiske | political | adjective | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 22 |
| et centrum | a centre | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 22 |
| dronningen | the queen | noun | core | — | contemporary (1994) | Denmark | national | grammar_reference | n/a | verified | p. 22-23; Danish monarchy reference |
| på Amalienborg Slot | at Amalienborg Palace | phrase | core | — | contemporary (1994) | Denmark | local | grammar_reference | n/a | verified | p. 23; royal residence in Copenhagen |
| der er | there are | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 23 |
| museer | museums | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 23 |
| parker | parks | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 23 |
| gå i Tivoli | visit the Tivoli Gardens | phrase | core | — | contemporary (1994) | Denmark | local | grammar_reference | n/a | verified | p. 23; Copenhagen's famous amusement park/gardens |
| gå | go, walk | verb | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 23 |

### Unit 2: Tak for mad! — It was a lovely meal!

| Tak skal du have! | Thank you (very much)! | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 24 |
| træt | tired | adjective | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 24 |
| lidt | a little | adverb | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 24 |
| sulten | hungry | adjective | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 24 |
| maden | the food | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 24; definite form of mad |
| næsten | nearly | adverb | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 24 |
| færdig | ready | adjective | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 24 |
| spise | eat | verb | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 24 |
| om et kvarter | in a quarter of an hour | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 24 |
| trænger til | need | verb phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 24 |
| det gør vi alle tre | all three of us do | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | lit. "that do we all three," p. 24 |
| det vil jeg gerne have | I would like (to have) that | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 24 |
| Værsgo! | Here you are! | interjection | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 24; see also Unit 2 grammar note on its dual use (handing something over / inviting to table) |
| stærk | strong | adjective | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 24 |
| Tusind tak! | Thank you very much! | interjection | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | lit. "a thousand thanks," p. 24 |
| have | have | verb | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 25 |
| klar suppe | consommé | noun phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 25 |
| flæskesteg med rødkål | roast pork with red cabbage | noun phrase | core | — | contemporary (1994) | Denmark | national | grammar_reference | n/a | verified | p. 25; traditional Danish dish |
| æblekage | a dessert similar to trifle, made with stewed apples | noun | core | — | contemporary (1994) | Denmark | national | grammar_reference | n/a | verified | p. 25 |
| det lyder godt | that sounds good | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 25 |
| lyde | (to) sound | verb | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 25 |
| jeg holder meget af | I am very fond of | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 25 |
| dansk mad | Danish food | noun phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 25 |
| Har du..? | Do you have..? Have you got..? | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 25 |
| en flaske | a bottle | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 25 |
| rødvin | red wine | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 25 |
| her | here | adverb | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 25 |
| to flasker rødvin | two bottles of red wine | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 25 |
| det bliver hyggeligt | it will be 'cosy' (we shall have a lovely time) | phrase | colloquial | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 25; book flags hyggeligt as a culturally loaded concept word with no exact English equivalent |
| blive | become | verb | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 25 |
| hyggeligt | 'cosy', homely, nice | adjective | colloquial | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 25; see notes above — a culturally central Danish concept word |
| godt | well (not to be translated here) | adverb | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 26; untranslatable discourse-softener use |
| noget mere | some more | pronoun phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 26 |
| Jo tak | Yes please (after a negative question) | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 26; see jo-vs-ja grammar note, Unit 1 |
| det smager så godt | it tastes so good | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 26 |
| man kan godt drikke | one can drink | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 26 |
| man | one (impersonal pronoun) | pronoun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 26 |
| drikke | (to) drink | verb | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 26 |
| til æblekage | with æblekage | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 26 |
| Skål! | Cheers! | interjection | colloquial | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 26 |
| Velbekomme! | (said by the hostess at the end of a meal; no English equivalent — "may it do you good") | interjection | colloquial | — | contemporary (1994) | Denmark | national | grammar_reference | n/a | verified | p. 27; book explicitly notes no equivalent phrase exists in English |
| en kop kaffe | a cup of coffee | noun phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 27 |
| det smagte dejligt | it tasted lovely | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 27 |
| dejligt | lovely | adjective | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 27 |
| skat | darling | noun | colloquial | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 27; intimate spousal/family address term, used by Hans to his wife |
| en familie | a family | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 32 |
| når | when | conjunction | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 32 |
| kommer med | brings | verb phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 32 |
| en dessert | a dessert | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 32 |
| chokoladeis | chocolate ice-cream | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 32 |
| at (+ infinitive) | to (before the infinitive) | particle | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 32, e.g. at spise |
| Jeg vil gerne rejse til København | I would like to travel to Copenhagen | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 27, example of vil gerne + infinitive |
| nul | zero | numeral | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 30, numerals 0-10 |
| en (1) | one | numeral | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 30 |
| to (2) | two | numeral | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 30 |
| tre (3) | three | numeral | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 30 |
| fire (4) | four | numeral | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 30 |
| fem (5) | five | numeral | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 30 |
| seks (6) | six | numeral | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 30 |
| syv (7) | seven | numeral | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 30 |
| otte (8) | eight | numeral | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 30 |
| ni (9) | nine | numeral | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 30 |
| ti (10) | ten | numeral | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 30 |

### Unit 3: På indkøb — Shopping

| God morgen! | Good morning! | interjection | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 33 |
| Har du sovet godt? | Did you sleep well? | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | lit. "have you slept well," p. 33 |
| en sten | a stone | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 33 |
| sove som en sten | sleep like a log | idiom | colloquial | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 33; lit. "sleep like a stone" |
| lige | just | adverb/particle | colloquial | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 33; see also the "Please" commentary (p. 37) flagging lige as the everyday politeness-softener where English would use "please" |
| hen | (indicates movement away from the speaker; no equivalent in modern English) | particle | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 33 |
| en bager | a baker | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 33 |
| til bageren | to the baker's | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 33 |
| efter | for (here) | preposition | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 33 |
| morgenbrød | breakfast rolls | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 33 |
| det skal jeg nok | I'll do that (I shall certainly do that) | phrase | colloquial | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 33 |
| et brusebad | a shower | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 33 |
| først | first | adverb | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 33 |
| jeg ved | I know | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | infinitive at vide, p. 33-34 |
| hvor | where | adverb | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 34 |
| en butik | a shop | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 34 |
| ligge | lie, be situated | verb | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 34 |
| så | then | adverb | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 34 |
| dække bord | lay the table | verb phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 34 |
| et bord | a table | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 34 |
| i mellemtiden | in the meantime | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 34 |
| en ekspeditrice | a (female) shop assistant | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 34 |
| Hvad skulle det være? | Can I help you? (lit. what should it be?) | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 34 |
| et rundstykke | a roll | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 34 |
| 3 stykker wienerbrød | three Danish pastries | phrase | core | — | contemporary (1994) | Denmark | national | grammar_reference | n/a | verified | p. 34 |
| ellers andet | anything else | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 34 |
| en liter letmælk | a litre of semi-skimmed milk | noun phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 34 |
| noget piskefløde | some whipping cream | noun phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 34 |
| hvad koster..? | how much is..? | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 34 |
| koste | cost | verb | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 34 |
| en krone | a crown (Danish currency unit) | noun | core | — | contemporary (1994) | Denmark | national | grammar_reference | n/a | verified | p. 34; book glosses as "roughly the equivalent of 10 pence" at time of writing |
| en halv liter | half a litre | noun phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 34 |
| Hvor meget bliver det? | How much is (all) that? | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | lit. "how much does that become," p. 34 |
| hjælpe | help | verb | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 35 |
| en buket | a bouquet | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 35 |
| blomster | flowers | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 35; singular en blomst |
| roserne | the roses | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 35; definite plural of en rose |
| stor | big | adjective | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 35 |
| 10 røde roser | ten red roses | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 35 |
| det er lidt for dyrt | that is a bit too expensive | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 35 |
| ..synes jeg | ..I think | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 35 |
| lille | small | adjective | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 35; see Unit 3 grammar note on its irregular inflection |
| tulipaner | tulips | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 35; singular en tulipan |
| påskeliljer | daffodils | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 35; singular en påskelilje |
| det er billigt | that is cheap | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 35 |
| her er aftalte penge | here is the exact amount | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 35 |
| penge | money | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 35; plural-only noun |
| Vil De være så venlig at.. | Could you please... (lit. will you be so kind...) | phrase | formal | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 35; book's commentary (p. 37) contrasts this formal request-softener with the informal "lige" |
| sige | tell, say | verb | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 35 |
| hvordan | how | adverb | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 35 |
| Kløvervej | Clover Road (a typical Danish residential street name) | proper noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 35 |
| Hvor bliver George af? | Where has George got to? | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 36 |
| dog | (exclamatory particle conveying slight impatience) | particle | colloquial | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 36; discourse/modal particle, distinct flagged register item |
| bare han ikke er faret vild | I hope he hasn't lost his way | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 36 |
| bare ... | I hope/I do hope... | particle | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 36 |
| fare vild | (to) lose one's way | verb phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 36 |
| i vores villakvarter | in our estate | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 36; et villakvarter = a residential estate |
| Det må I undskylde | I am sorry (lit. you must excuse that) | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 36 |
| det var jeg længe om | that took me a long time | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 36 |
| længe | long, a long time | adverb | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 36 |
| Hvordan er vejret i dag? | What is the weather like today? | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 36 |
| det regner | it is raining | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 36 |
| koldt | cold | adjective | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 36 |
| det blæser | it is windy | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 36 |
| det klarer op | it will brighten up | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 36 |
| i løbet af | in the course of | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 36 |
| formiddagen | the morning (the time between ten and one o'clock) | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 36; book notes this is a narrower sense of "morning" than English's |
| gå en tur | go for a walk | verb phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 36 |
| i eftermiddag | this afternoon | adverb phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 36 |
| hvis | if | conjunction | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 36 |
| solen | the sun | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 36 |
| skinner | shines | verb | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 36 |
| op til Dyrehaven | up to the Deer Park | phrase | core | — | contemporary (1994) | Denmark | local | grammar_reference | n/a | verified | p. 36; a well-known area of parkland and woods near Copenhagen |
| der | there | adverb | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 36 |

### Unit 4: I lufthavnen — At the airport

| en kone | wife | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 46 |
| midt på dagen | in the middle of the day, mid-day | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 46 |
| hvornår? | when? (in a question) | adverb | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 46 |
| afgå | depart | verb | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 46 |
| billetsælger | ticket office clerk | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 46 |
| hver time | each hour | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 46 |
| en time | an hour | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 46 |
| osv. (og så videre) | etc. | abbreviation | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 46 |
| skal | must (here: necessity) | verb (modal) | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 46; distinct sense of skal from "going to" in Unit 1 |
| pladsbillet | seat reservation | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 46 |
| en billet | a ticket | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 46 |
| klokken 12.00 | at 12 o'clock, at 12 noon | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 46; book notes Danish has no word corresponding to "at" here |
| enkeltbillet | single ticket | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 46 |
| returbillet | return ticket | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 46 |
| rygere | smokers | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 46 |
| ikke-rygere | non-smokers | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 46 |
| Det er nemt | It is easy | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 48 |
| nu | now; (here) I must say | adverb/particle | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 48; two distinct senses noted by the book |
| vare længe | take a long time | verb phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 48 |
| Hvor længe varer flyveturen? | How long does the flight take? | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 48 |
| den tager | it takes | verb phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 48 |
| ca. (cirka) | circa, approximately | adverb | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 48 |
| ned | down | adverb | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 48 |
| derfra | from there | adverb | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 48 |
| undergrundsbanen | the Tube, the underground railway | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 48 |
| ud | out | adverb | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 48 |
| rejste | travelled (past tense) | verb | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 48 |
| rejste hjemmefra | left home | verb phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 48 |
| klokken halv seks | at half past five | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 48 |
| i morges | this morning | adverb phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 48 |
| passager | passenger | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 48 |
| har været | has/have been | verb phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 48 |
| et fly | a plane | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 48 |
| jeg tror ikke... | I don't think... | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 48 |
| er kommet | has/have come, arrived | verb phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 48 |
| en funktionær | an employee | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 48 |
| der ankommer et British Airways fly | a British Airways plane arrives | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | lit. "there arrives a British Airways plane," p. 48 |
| har talt | have talked | verb phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 48 |
| tale med | talk to | verb phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 48 |
| ringede til | telephoned (past tense of ringe) | verb | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 48 |
| klokken halv 1 (et) | at half past 12 | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 48 |
| var forsinket | was delayed | verb phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 48 |
| ankom | arrived (past tense of ankomme) | verb | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 48 |
| så sent | so late | adverb phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 48 |
| at (conjunction) | that | conjunction | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 48 |
| kunne | could | verb (modal) | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 48 |
| sagde | said (past tense of sige) | verb | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 48 |
| må | must | verb (modal) | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 48 |
| finde ud af | find out | verb phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 48 |
| lufthavn | airport | noun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 48 |
| Hvad er klokken? | What is the time? | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 49 |
| Klokken er.. | It is .. o'clock | phrase | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 49 |
| hvem | who | pronoun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 52 |
| hvis | whose | pronoun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 52; distinct from conjunction hvis "if" |
| hvilken/hvilket/hvilke | which | pronoun | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 52; agrees with noun gender/number |
| hvad for en/et/nogen | which, what kind of | pronoun | colloquial | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 52; book's own explicit flag: "colloquially, however, people use" this instead of hvilken — see Grammar points |
| tyve (20) | twenty | numeral | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 51 |
| tredive (30) | thirty | numeral | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 51 |
| fyrre (40) | forty | numeral | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 51 |
| halvtreds (50) | fifty | numeral | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 51; see vigesimal grammar note |
| tres (60) | sixty | numeral | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 51 |
| halvfjerds (70) | seventy | numeral | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 51 |
| firs (80) | eighty | numeral | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 51 |
| halvfems (90) | ninety | numeral | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 51 |
| hundrede (100) | a hundred | numeral | core | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 51 |
| halvanden/halvandet | one and a half | numeral | archaic | — | contemporary (1994) | — | — | grammar_reference | n/a | verified | p. 51; book notes still in use, unlike the fully spelled-out halv-sinds-tyve forms, which it flags as outdated |

### Unit 5: Weekend i Nordsjælland — Weekend in North Zealand

| nå | well, ... | interjection | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.58 |
| lave (-ede, -et) | do | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.58 |
| i aften | this evening, tonight | phrase/adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.58 |
| aften (-en, -er) | evening | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.58 |
| invitere (-ede, -et) | invite | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.58 |
| fest (-en, -er) | party | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.58 |
| sankthansaften | St. John's Eve (23 June) | noun/proper_noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.58; cultural term, see grammar notes |
| holde (holdt, holdt) | hold, keep (here: have) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.58 |
| sommerhus (-et, -e) | summer cottage | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.58 |
| hus (-et, -e) | house | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.58 |
| begynde (-te, -t) | begin | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.58 |
| først | not until | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.58, 62; also means "first" — see grammar note |
| Hvad har I lyst til at lave? | What do you feel like doing? | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.58 |
| have lyst til | feel like | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.58 |
| jeg vil meget gerne se | I would like very much to see | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.58 |
| se (så, set) | see | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.58 |
| idé (-en, -er) | idea | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.58 |
| lad os | let us | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.58 |
| lade (lod, ladet or ladt) | let | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.58 |
| frokost (-en, -er) | lunch | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.58 |
| sidst på eftermiddagen | at the end of the afternoon | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.58 |
| besøge (-te, -t) | visit | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.58 |
| tage (tog, taget) | take; (here) go | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.58 |
| derop | up there | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.58 |
| i stedet | instead | adverb/phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.58 |
| få (fik, fået) | get | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.58 |
| forestilling (-en, -er) | performance | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.58 |
| Kronborg Slot | the Castle of Elsinore | proper_noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.58, 62; see cultural note |
| engelsk | English | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.58 |
| teatergruppe (-n, -r) | theatre company | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.58 |
| opføre (-te, -t) | perform | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.58 |
| for tiden | at the moment | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.58 |
| hele året rundt | all year round | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60 |
| år (-et, -) | year | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60 |
| heroppe | up here | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60 |
| lejlighed (-en, -er) | flat | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60 |
| inde midt i København | in the middle of Copenhagen | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60 |
| før | before | preposition/conjunction | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60 |
| vist | probably | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60 |
| derhenne | over there, up there | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60 |
| gul | yellow | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60 |
| håbe (-ede, -et) | hope | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60 |
| finde (fandt, fundet) | find | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60 |
| spørge om vej | ask the way | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60 |
| spørge (spurgte, spurgt) | ask | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60 |
| huske (-ede, -et) | remember | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60 |
| adresse (-n, -r) | address | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60 |
| give (gav, givet) | give | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60 |
| glemme (-te, -t) | forget | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60 |
| Hvor er her smukt! | How beautiful it is here! | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60 |
| tænke på (-te, -t) | think of | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60, 63 |
| farve (-n, -r) | colour | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60 |
| blå | blue | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60 |
| himmel (-en, himle) | sky, heaven | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60 |
| hav (-et, -e) | sea | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60 |
| gammel | old | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60, 64 |
| derovre | over there | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60 |
| skov (-en, -e) | wood, forest | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60 |
| ejer (-en, -e) | owner | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60 |
| måske | perhaps | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60 |
| fornuftig | sensible, reasonable | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60 |
| blive (blev, blevet) | become | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60 |
| mørk | dark | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60 |
| snart | soon | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60, 64 |
| ned | down | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60 |
| strand (-en, -e) | beach | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60 |
| tænde (-te, -t) | light (a fire) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60 |
| bål (-et, -) | bonfire | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60 |
| derned | down there | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60 |
| bare | only | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60, 64 |
| sangstemme (-n, -r) | singing voice | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60 |
| synge (sang, sunget) | sing | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60 |
| sidde (sad, siddet) | sit | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60 |
| omkring | around, round | preposition/adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60 |
| sang (-en, -e) | song | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60 |
| sommer (-en, somre) | summer | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60, 64 |
| først og fremmest | first and foremost | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60 |
| elske (-ede, -et) | love | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60 |
| vort (old neuter form of vores) | our | pronoun | archaic | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60; marked by source as an old/literary form, used only in the quoted folk song |
| land (-et, -e) | country | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60 |
| handle om (-ede, -et) | be about, deal with | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.60 |
| i næste uge | next week | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.65 |
| i morges | this morning | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.65 |
| i eftermiddag | this afternoon | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.65 |
| i mellemtiden | in the meantime | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.65 |
| i løbet af formiddagen | in the course of the morning | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.65 |
| på mandag | on Monday (future) | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.65 |
| i en uge | for a week | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.65 |
| om et kvarter | in a quarter of an hour | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.65 |
| midt på dagen | in the middle of the day | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.65 |
| sulten | hungry | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.64; appears inflected (sultne) in grammar illustration |

### Unit 6: Med toget til Jylland — By train to Jutland

| vinduesplads (-en, -er) | window seat | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.70 |
| Det var heldigt! | How fortunate! (lit. that was lucky) | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.70 |
| glæde sig til (-ede, -et) | look forward to | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.70 |
| tur (-en, -e) | trip, journey | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.70 |
| sætte sig (satte, sat) | sit down | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.70, 74 |
| forkert | wrong | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.70 |
| plads (-en, -er) | place, seat | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.70 |
| få at vide | be told (lit. get to know) | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.70, 86 |
| den ene | one (of them) | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.70 |
| Det må I meget undskylde. | I am very sorry. | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.70 |
| undskylde (-te, -t) | excuse | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.70 |
| begge | both | pronoun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.70, 98 |
| tage fejl | be mistaken, be wrong | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.70 |
| minde (-ede, -et) (om) | remind (of) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.70 |
| engang | once | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.70 |
| kende (-te, -t) | know (a person/place) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.70, 86 |
| fortælle (fortalte, fortalt) | tell | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.71 |
| højskole (-n, -r) | folk high school | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.71; see cultural note |
| tage (et år) fri | take (a year) off | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.71 |
| inden | before | conjunction/preposition | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.71 |
| læse (-te, -t) | read, study | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.71 |
| universitet (-et, -er) | university | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.71 |
| som | who, which, that | pronoun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.71; relative pronoun, see grammar note |
| Det er min mand. | This is my husband. | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.71 |
| mand (-en, mænd) | man, husband | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.71 |
| det gør ikke noget | it does not matter, that's all right | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.71 |
| bliv endelig siddende | do stay | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.71 |
| endelig | (here) an adverb giving same emphasis as English "do" | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.71 |
| som regel | usually, as a rule | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.71 |
| forretningsmøde (-t, -r) | business meeting | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.71 |
| faktisk | in fact | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.72 |
| en måned (-en, -er) | month | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.72 |
| være færdig med | have finished | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.72 |
| kunne tænke sig | feel like | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.72 |
| masser af plads | lots of room | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.72 |
| et par | a few, a couple of | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.72 |
| mægtig sødt | immensely kind (lit. sweet) | phrase | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.72; intensifier use of "mægtig" ("mightily") flagged as colloquial-register |
| Men det er alt for galt! | But you are far too kind! | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.72 |
| tværtimod | on the contrary | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.72 |
| lære at kende | get to know | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.72, 86 |
| leje (-ede, -et) | hire, rent | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.72 |
| bil (-en, -er) | car | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.72 |
| let | easy | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.72 |
| kro (-en, -er) | inn | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.72 |
| dreje (-ede, -et) | turn | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.72 |
| mod | towards | preposition | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.72 |
| kilometer (-en, -) | kilometer | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.72 |
| en blind vej | a cul-de-sac | noun phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.72 |
| blind | blind | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.72 |
| sidst | last | adjective/adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.72 |
| højre | right, right-hand | noun/adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.73 |
| til højre for | to the right of | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.73 |
| venstre | left, left-hand | noun/adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.73 |
| til venstre for | to the left of | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.73 |
| banegård (-en, -e) | railway station | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.73, 79 |
| Vil De være så venlig at... | Would you be so kind as to... | phrase | formal | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.73; polite register formula |
| venlig | kind | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.73 |
| hjælpe (hjalp, hjulpet) | help | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.75 |
| drikke (drak, drukket) | drink | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.75 |
| sige (sagde, sagt) | say | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.75 |
| gøre (gjorde, gjort) | do, make | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.75 |
| sætte (satte, sat) | put, place | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.75 |
| have (havde, haft) | have | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.75 |
| kiosk | kiosk | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.79; from street-map label, not independently glossed |
| boghandel (-en, -er) | bookshop | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.79; from street-map label |
| damefrisør (-en, -er) | ladies' hairdresser | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.79; from street-map label |
| blomsterhandler (-en, -e) | florist | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.79; from street-map label |
| supermarked (-et, -er) | supermarket | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.79; from street-map label |
| bibliotek (-et, -er) | library | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.79; from street-map label |
| park (-en, -er) | park | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.79; from street-map label |
| skole (-n, -r) | school | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.79, 93 |
| hotel (-let, -ler) | hotel | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.80 |
| ikke ret langt | not very far | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.80 |
| for enden af | at the end | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.80 |
| end (-n, -r) | end | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.80 |
| denne/dette | this | pronoun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.80, 88; see grammar note |
| tredje | third | numeral | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.80 |
| gade (-n, -r) | street | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.80 |
| rundt om | round | preposition | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.80 |
| hjørne (-t, -r) | corner | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.80 |
| lige ved siden af | right next to | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.80 |
| hjørneejendom (-men, -me) | corner property | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.80 |
| aldrig | never | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.81, 88 |
| om | about | preposition | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.81; see also "whether" sense, Unit 9 |
| tilbringe (tilbragte, tilbragt) | spend (time, not money) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.81 |
| da | when (single past event) | conjunction | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.81, 86; contrast with colloquial discourse-particle "da," Unit 8 |
| fordi | because | conjunction | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.81 |
| ske (-te, -t) | happen | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.81 |
| kun | only | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.81 |
| marts | March | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.81 |
| slutning (-en, -er) | end | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.81 |
| juni | June | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.81 |
| arbejde (-ede, -et) | work | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.81 |
| onkel (-en, onkler) | uncle | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.81 |
| forretning (-en, -er) | business, shop | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.81 |
| lære (-te, -t) | learn | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.81 |
| sprog (-et, -) | language | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.81, 93 |


---

### Unit 7: Til forretningsmøde — At a business meeting

| vækkeur (-et, -e) | alarm clock | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.82 |
| ringe (-ede, -et) | ring | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.82 |
| vække (-ede, -et) | wake up (someone) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.82 |
| skynde sig (-te, -t) | hurry | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.82 |
| badeværelse (-t, -r) | bathroom | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.82 |
| vaske sig (-ede, -et) | get washed | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.82 |
| klæde sig på (-te, -t) | dress (oneself) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.82 |
| falde i søvn (faldt, faldet) | fall asleep | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.82 |
| allerede | already | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.82 |
| jeg skal nok | I shall (certainly), I will | phrase | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.82; see "nok" as reassurance-marker discourse particle, Unit 8 |
| skænke (-ede, -et) | pour | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.83 |
| må hellere | had better | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.83 |
| hellere | rather | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.83 |
| helt | completely | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.83 |
| barbere sig | shave (oneself) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.83 |
| se (så, set) ... ud | look... | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.83 |
| lækker | delicious | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.83, 101 |
| komme til | will (future sense) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.83 |
| gå til spilde | go to waste, be wasted | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.83 |
| blødkogt | soft-boiled | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.83 |
| derefter | after that | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.83 |
| æg (-get, -) | egg | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.83 |
| riste (-ede, -et) | toast | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.83 |
| franskbrød (-et, -) | loaf of white bread | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.83 |
| marmelade (-n, -r) | jam | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.83 |
| appelsinmarmelade | marmalade | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.83 |
| appelsin (-en, -er) | orange | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.83 |
| til sidst | finally | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.83 |
| efterspørgsel (-en) (efter) | demand (for) | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| luksusvarer | luxury goods | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| luksus (-en) | luxury | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| vare (-n, -r) | article, product | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| nogensinde | ever | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| æske (-n, -r) | box | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| genbrugspapir (-et) | recycled paper | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| dvs. (det vil sige) | that is to say | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| produkt (-et, -er) | product | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| på ingen måde | in no way | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| måde (-n, -r) | way, manner | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| skade (-ede, -et) | harm | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| natur (-en) | nature, countryside | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| vigtig | important | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| miljøbevidst | environmentally aware | adjective | technical | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| prioritetskunde (-n, -r) | priority customer | noun | technical | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| kunde (-n, -r) | customer | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| naturligvis | of course | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| gratis | free | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| display (-et, -/-s) | display unit | noun | technical | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| tilbyde (tilbød, tilbudt) | offer | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| særlig | particularly | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84, 113 |
| favorabel | favourable | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84, 101 |
| om måneden | a month (each month) | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| gave (-n, -r) | present | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| skål (-en, -e) | bowl | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| porcelæn (-et) | porcelain | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| fylde (-te, -t) | fill | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| byde velkommen (bød, budt) | bid welcome | verb | formal | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84; speech-opening formula |
| glas (-set, -) | glass | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| vin (-en, -e) | wine | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| smage på (-te, -t) | taste, sample, try | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| chokolade (-n, -r) | chocolate | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| ord (-et, -) | word | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| jo | discourse particle implying the listener already knows the truth of what is said | adverb/particle | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84, 98; FLAGGED discourse particle — see grammar note |
| almindelig | usual, common, ordinary | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| ny | new | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| opskrift (-en, -er) | recipe | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| ingrediens (-en, -er) | ingredient | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| uden | without | preposition | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| kunstig | artificial | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| tilsætningsstof (-fet, -fer) | additive | noun | technical | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| betyde (betød, betydet) | mean | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| selvfølgelig | of course | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| de fleste | most | pronoun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| andre | other | pronoun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| slags (-en, -) | kind, sort | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| erfaring (-en, -er) | experience | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| folk (-et) | people | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| interessere sig (for) | be interested (in) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| kvalitet (-en, -er) | quality | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| billige priser | low prices | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| pris (-en, -er) | price | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.84 |
| vide (ved, vidste, vidst) | know (fact, clause) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.85-86; contrast with "kende," see grammar note |
| hvornår | when (interrogative) | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.86 |
| når | when, whenever | conjunction | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.86; see grammar note contrasting når/da/hvornår |
| afgå (afgik, afgået) | depart (of trains etc.) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.87, 91 |
| dansker (-en, -e) | Dane | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.93 |
| både...og | both...and | conjunction | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.93, 98 |
| far (faderen/faren, fædre) | father | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.93 |
| mor (moderen/moren, mødre) | mother | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.93 |
| tit | often | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.93 |
| ferie (-n, -r) | holiday | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.93 |
| herovre | over here | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.93 |
| Hvor mange sprog kan du? | How many languages do you know? | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.93 |
| fransk | French | adjective/noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.93 |
| tælle med (talte, talt) | include, count | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.93 |
| god til det | good at it | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.94 |
| desværre | unfortunately | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.94 |
| en masse (ord) | a lot of (words) | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.94 |
| forældre (pl.) | parents | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.94 |
| firma (-et, -er) | firm | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.94 |
| eksportere (-ede, -et) | export | verb | technical | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.94 |
| dengang | then, at that time | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.94, 111 |
| bror (broderen/broren, brødre) | brother | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.94 |
| tosproget | bilingual | adjective | technical | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.94 |
| insistere på (-ede, -et) | insist | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.94 |

---

### Unit 8: På hotellet — At the hotel

| jeg bliver nødt til | I shall have to | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.96 |
| være nødt til | have to, need to | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.96 |
| august | August | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.96 |
| samme | same | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.96 |
| egentlig | actually | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.96 |
| temmelig | rather | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.96, 123 |
| jeg kan lige så godt | I might (just) as well | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.96 |
| bestille (-te, -t) | book | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.96 |
| værelse (-t, -r) | room | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.96 |
| mindre | smaller | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.96 |
| enkeltværelse (-t, -r) | single room | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.96 |
| receptionist (-en, -er) | receptionist | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.96 |
| ledig | vacant | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.96 |
| sjette (6.) | sixth | numeral | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.96 |
| ellevte (11.) | eleventh | numeral | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.96 |
| klare (-ede, -et) | manage | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.96 |
| pr. (per) nat | per night, a night | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.96 |
| nat (-ten, nætter) | night | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.96 |
| bringe (bragte, bragt) | bring | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.96 |
| ønske (-ede, -et) | wish | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.96 |
| mellem | between | preposition | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.96 |
| udmærket | splendid | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.96 |
| nøgle (-n, -r) | key | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.97 |
| tilfredsstillende | satisfactory | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.97 |
| have brug for | want, need | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.97, 99; nuanced against trænge til and være nødt til, see grammar note |
| sige til (sagde, sagt) | say so, let (someone) know | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.97 |
| eventuelt | possibly | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.97 |
| arrangere (-ede, -et) | arrange | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.97 |
| dreje sig om (-ede, -et) | be a matter of, amount to | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.97 |
| størrelse (-n, -r) | size | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.97 |
| bestemt | certain, fixed | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.97 |
| beløb (-et, -) | amount | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.97 |
| forsikring (-en, -er) | insurance | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.97 |
| betale (-te, -t) | pay for | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.97 |
| benzin (-en) | petrol | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.97 |
| forleden | the other (day) | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.97 |
| film (-en, -) | film | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.97 |
| forsømme (-te, -t) | neglect, miss (an opportunity) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.97 |
| forår (-et, -) | spring (season) | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.97 |
| gå (gik, gået) | be on, be shown (of films/plays) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.97 |
| hallo | hello (telephone) | interjection | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.97 |
| udsolgt | sold out | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.97 |
| jamen | well, but | interjection | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.97; conversational filler/softener |
| hvad så med | what about | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.97 |
| navn (-et, -e) | name | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.97 |
| nok | discourse particle softening/reassuring a factual statement ("probably," "I promise") | adverb/particle | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.82, 99; FLAGGED discourse particle — see grammar note |
| da | discourse particle, can signal disagreement with what was just said | adverb/particle | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.98; FLAGGED discourse particle (distinct from temporal "da"), see grammar note |
| dog | discourse particle adding subjective coloring | adverb/particle | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.98; FLAGGED discourse particle, named but not individually elaborated in this chunk |
| nu | discourse particle adding subjective coloring (distinct from temporal "now") | adverb/particle | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.98; FLAGGED discourse particle, named but not individually elaborated in this chunk |
| så | so (before adjective/adverb); then, in that case; so, so that (introducing subordinate clause) | adverb/conjunction | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.99; see grammar note, multi-sense word |
| trænge til | need, want, be in need of (something needing to be put right) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.99 |
| fin | fine | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.101 |
| sød | sweet | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.101 |
| nem | easy | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.101 |
| billig | cheap | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.101 |
| stor | big | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.101 |
| lang | long | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.101 |
| god | good | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.101 |
| lille | small | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.101 |
| meget | much | adjective/adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.101, 113 |
| mange | many | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.101 |
| hyggelig | cosy | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.102 |
| forsinket | delayed | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.102 |
| politisk | political | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.102 |
| nogen | somebody/anybody, some/any (common gender singular; also plural "any") | pronoun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.102-103; see grammar note |
| noget | something/anything, some/any (neuter singular; also quantitative "some, a little") | pronoun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.102-103 |
| nogle | some (plural; pronounced like nogen, distinguished only in writing) | pronoun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.102-103 |
| T.O.M. (til og med) | up to and including | phrase | formal | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.105; abbreviation convention seen on entertainment listings |
| landsby (-en, -er) | village | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.106 |
| scene (-n, -r) | stage, scene | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.106 |
| oplyse (-te, -t) (om) | inform (about) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.106 |
| teater (teatret, teatre) | theatre | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.106 |
| efterårsferie (-n, -r) | autumn half-term holiday | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.106 |
| efterår (-et, -) | autumn | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.106 |
| halvdel (-en, -e) | half | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.106 |
| onsdag (-en, -e) | Wednesday | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.106 |
| spille (-ede, -et) | perform, play | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.106 |
| torsdag (-en, -e) | Thursday | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.106 |
| lørdag (-en, -e) | Saturday | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.106 |
| ballet (-ten, -ter) | ballet | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.106 |
| svane (-n, -r) | swan | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.106 |
| sø (-en, -er) | lake | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.106 |
| voksenbillet (-ten, -ter) | adult/full ticket | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.106 |
| voksen | adult, grown up | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.106 |
| børnebillet/barnebillet | half ticket (child's ticket) | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.106 |
| barn (-et, børn) | child | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.106 |
| afhente (-ede, -et) | collect, fetch | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.106 |
| sur | in a bad mood, cross | adjective | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.107 |
| stille | quiet | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.107 |
| være ked af | be sad about | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.107 |
| være i vejen | be wrong | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.107 |
| helst | preferably | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.107 |
| nægte (-ede, -et) | refuse | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.107 |
| anderledes | different | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.107 |
| prøve (-ede, -et) | try | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.107 |
| person (-en, -er) | person | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.107 |
| føle (-te, -t) | feel | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.107 |
| som om | as if | conjunction | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.107 |
| forskellig | different | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.107 |
| på grund af | because of, on account of | preposition | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.107 |
| udtrykke (-te, -t) | express | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.108 |
| forskellighed (-en, -er) | difference, dissimilarity | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.108 |
| personlighed (-en, -er) | personality | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.108 |
| fødes | are born (passive) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.108; see passive voice grammar note, Unit 9 |
| føde (-te, -t) | bear, give birth to | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.108 |
| kultur (-en, -er) | culture | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.108 |
| forventning (-en, -er) | expectation | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.108 |
| fordom (-men, -me) | prejudice | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.108 |
| Jeg føler mig som dansker. | I feel a Dane. | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.108 |

---

### Unit 9: I sommerhus på Mols — At a cottage in Mols

| område (-t, -r) | area, region | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.109 |
| halvø (-en, -er) | peninsula | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.109 |
| østkyst (-en, -er) | east coast | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.109 |
| fuld | full, complete | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.109 |
| betegnelse (-n, -r) | name, designation | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.109 |
| bjerg (-et, -e) | mountain | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.109 |
| indtryk (-ket, -) | impression | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.109 |
| landskab (-et, -er) | landscape | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.109 |
| kuperet | hilly, undulating | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.109 |
| terræn (-et, -er) | terrain | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.109 |
| sydlig | southern | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.109 |
| del (-en, -e) | part | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.109 |
| vig (-en, -e) | inlet, bay | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.109 |
| tæt | dense | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.109 |
| veksle (-ede, -et) | alternate | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.109 |
| åben | open | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.109 |
| hedebakker | moorland | noun | regional | — | contemporary (source published 1994) | Jutland (Djursland/Mols) | regional | grammar_reference | n/a | verified | p.109; compound (hede + bakker), describes Mols-specific terrain |
| hede (-n, -r) | moor | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.109 |
| bakke (-n, -r) | hill | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.109 |
| levn (-et, -) | relic | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.109 |
| fortid (-en) | the past | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.109 |
| f.eks., for eksempel | for instance | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.109 |
| gravhøj (-en, -e) | burial mound | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.109 |
| vidne om (-ede, -et) | be a sign of, show | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.109 |
| årtusinde (-t, -r) | millennium | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.109 |
| høj | tall, high | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.109 |
| m., meter (-en, -) | metre | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.109 |
| være glad for, at... | be pleased that... | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.110 |
| det lader sig (gøre) | it can be (done) | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.110 |
| lade (lod, ladet/ladt) | let, allow | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.110 |
| gå i vandet | go for a swim | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.110 |
| vand (-et) | water | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.110 |
| senere | later | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.110 |
| ih! | oh! | interjection | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.110 |
| nyde (nød, nydt) | enjoy | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.110 |
| vise (-te, -t) | show | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.110 |
| stille (-ede, -et) | put, place | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.110 |
| for (5 år) siden | (five years) ago | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.111 |
| siden da | since then | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.111 |
| male (-ede, -et) | paint | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.111 |
| indvendig | inside, internally | adjective/adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.111 |
| udvendig | outside, externally | adjective/adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.111 |
| bygge (-ede, -et) | build | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.111 |
| bygge (noget) til (-ede, -et) | add (on something, e.g. a building extension) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.111 |
| leje ud (-ede, -et) | let (a property) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.111 |
| af og til | now and then | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.111 |
| tysk | German | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.111 |
| bagefter | afterwards | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.111 |
| bruge (-te, -t) (til) | use; spend (money) (on) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.111 |
| istandsætte (-satte, -sat) | repair, recondition | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.111 |
| køkken (-et, -er) | kitchen | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.111 |
| stue (-n, -r) | living room | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.111 |
| soveværelse (-t, -r) | bedroom | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.111 |
| det kniber med pladsen | there is not really enough room | phrase | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.111 |
| det kniber med (kneb, knebet) | there is a scarcity of | verb | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.111 |
| hjemme | at home | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.111 |
| på landet | in the country | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.112 |
| rækkehus (-et, -e) | terrace house | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.112 |
| indtil | until | preposition/conjunction | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.112 |
| gård (-en, -e) | farm | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.112 |
| bygning (-en, -er) | building | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.112 |
| jord (-en) | earth (here: land) | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.112 |
| undervise (-te, -t) | teach | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.112 |
| derfor | so, therefore | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.112 |
| bestemme (-te, -t) | decide | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.112; see double-consonant simplification grammar note |
| holde op (holdt op, er holdt op) | stop | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.112 |
| noget (forsømt) | somewhat (neglected, dilapidated) | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.112 |
| beslutte (-ede, -et) | decide | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.112 |
| starte (-ede, -et) | start, set up | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.112 |
| fabrik (-ken, -ker) | factory | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.112 |
| fremstille (-ede, -et) | produce | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.112 |
| før i tiden | formerly, previously | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.112 |
| svinesti (-en, -er) | pig-sty | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.112 |
| have (-n, -r) | garden | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.112 |
| dyrke (-ede, -et) | grow, cultivate | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.112, 113; contrasted with "vokse," see grammar note |
| grøn(t)sager (pl.) | vegetables | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.112 |
| bær (-ret, -) | berry | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.112 |
| frugt (-en, -er) | fruit | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.112 |
| endnu | still | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.112 |
| stuehus (-et, -e) | farmhouse | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.112 |
| overveje (-ede, -et) | consider | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.112 |
| udlejning (-en) | letting | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.112 |
| jordbær (-ret, -) | strawberry | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.112 |
| hindbær (-ret, -) | raspberry | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.112 |
| solbær (-ret, -) | blackcurrant | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.112 |
| æbletræ (-et, -er) | apple tree | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.112 |
| æble (-t, -r) | apple | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.112, 115 |
| træ (-et, -er) | tree | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.112 |
| pæretræ (-et, -er) | pear tree | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.112 |
| pære (-n, -r) | pear | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.112, 115 |
| kartoffel (-en, kartofler) | potato | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.112, 115 |
| ært (-en, -er) | pea | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.112 |
| gulerod (-en, gulerødder) | carrot | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.112, 115 |
| spinat (-en) | spinach | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.112 |
| salat (-en, -er) | lettuce, salad | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.112 |
| græsplæne (-n, -r) | lawn | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.112 |
| drivhus (-et, -e) | greenhouse | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.112 |
| tomat (-en, -er) | tomato | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.112, 115 |
| agurk (-en, -er) | cucumber | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.112, 115 |
| porre (-r) | leek | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.115; from labeled illustration |
| radise (-r) | radish | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.115; from labeled illustration |
| løg (-) | onion | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.115; from labeled illustration |
| vokse (-ede, -et) | grow, become bigger | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.113; perfect tense "er vokset"; contrasted with "dyrke," see grammar note |
| ret | rather, quite | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.113; used with "ikke" for "not very" |
| hvis | if (conditional); whose (interrogative) | conjunction/pronoun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.114; see grammar note on if/whether/whose |
| nord | north | noun/adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.114 |
| nordfra | from the north | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.114 |
| nordpå | northwards | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.114 |
| nord for | (to the) north of | preposition | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.114 |
| syd | south | noun/adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.114 |
| sydfra | from the south | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.114 |
| sydpå | southwards | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.114 |
| syd for | (to the) south of | preposition | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.114 |
| øst | east | noun/adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.114 |
| østfra | from the east | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.114 |
| østpå | eastwards | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.114 |
| øst for | (to the) east of | preposition | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.114 |
| vest | west | noun/adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.114 |
| vestfra | from the west | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.114 |
| vestpå | westwards | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.114 |
| vest for | (to the) west of | preposition | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.114 |
| inde | in (location) | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.116; paired with "ind," see grammar note |
| ud | out (movement) | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.116 |
| ude | out (location) | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.116 |
| op | up (movement) | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.116 |
| oppe | up (location) | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.116 |
| nede | down (location) | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.116 |
| over | over (movement) | adverb/preposition | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.116 |
| ovre | over (location) | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.116 |
| hen | over, along (movement) | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.116 |
| henne | over, along (location) | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.116 |
| hjem | home (movement) | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.116 |
| pund (-et, -) | pound (weight unit) | noun | technical | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.119; from shopping-exercise illustration |
| kilo (-et, -) | kilogram | noun | technical | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.119; from shopping-exercise illustration |
| i krigstid | in time of war | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.121 |
| krig (-en, -e) | war | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.121 |
| tid (-en, -er) | time | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.121 |
| være bange for | be afraid of | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.121 |
| fjende (-n, -r) | enemy | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.121 |
| stjæle (stjal, stjålet) | steal | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.121 |
| kirkeklokke (-n, -r) | church bell | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.121 |
| kirke (-n, -r) | church | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.121 |
| klokke (-n, -r) | bell | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.121 |
| tårn (-et, -e) | tower | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.121 |
| gemme (-te, -t) | hide | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.121 |
| sejle (-ede, -et) | sail | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.121 |
| skjule (-te, -t) | hide | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.121 |
| bund (-en, -e) | bottom | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.121 |
| forbi | past, over | adverb/preposition | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.121 |
| svare (-ede, -et) | answer | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.121 |
| skære (skar, skåret) | cut | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.121 |
| mærke (-t, -r) | mark | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.121 |
| side (-n, -r) | side | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.121 |
| kaste (-ede, -et) | throw | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.121 |
| Hvorfor så I ikke noget til hinanden? | Why did you not see anything of each other? | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.122 |
| se noget til (så, set) | meet, see something of (someone) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.122 |
| (højskole)ophold (-et, -) | stay (at a folk high school) | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.122 |
| hold (-et, -) | class, team, group | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.122 |
| spredes for alle vinde | was scattered to the four winds | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.122 |
| sprede (-te, -t) | spread, scatter | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.122 |
| vind (-en, -e) | wind | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.122 |
| (rejse) til udlandet | (travel) abroad | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.122 |
| (bo) i udlandet | (live) abroad | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.122 |
| så vidt jeg husker | as far as I remember | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.122 |
| stadigvæk | still | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.122 |
| tante (-n, -r) | aunt | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.122 |
| efterhånden | gradually; by now | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.122 |
| blive til noget (blev, blevet) | come off, materialise | verb | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.122 |

### Unit 10: Om bord på færgen — On board the ferry

| bestå af (bestod, bestået) | consist of | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.124 |
| landfast | connected (by land) | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.124 |
| ø (-en, -er) | island | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.124 |
| hvoraf | of which, of whom | adv/pron | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.124 |
| beboet | inhabited | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.124 |
| danne (-ede, -et) | form, constitute | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.124 |
| grænse (-n, -r) | border, frontier | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.124 |
| næststørst | second largest | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.124 |
| million (-en, -er) | million | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.124 |
| indbygger (-en, -e) | inhabitant | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.124 |
| fjerdedel (-en, -e) | quarter | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.124 |
| hvor (man) end (er) | wherever (you are) | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.124 |
| befinde sig (-fandt, -fundet) | be, find oneself | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.124 |
| færge (-n, -r) | ferry | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.124; recurs through the chapter |
| havn (-en, -e) | harbour, port | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.124 |
| fryse (frøs, frosset) | feel cold, freeze | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.125 |
| varm | warm | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.125 |
| bluse (-n, -r) | blouse | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.125 |
| nederdel (-en, -e) | skirt | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.125 |
| ikke engang | not even | adv phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.125 |
| regnfrakke (-n, -r) | raincoat | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.125, recurs p.184/185 pictured |
| låne (-te, -t) | borrow | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.125 |
| tøj (-et) (only sg.) | clothes | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.125 and p.130 Ordforklaringer |
| hente (-ede, -et) | fetch | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.125 |
| bukser (pl.) | trousers | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.125 |
| cardigan (-en, -er) | cardigan | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.125 |
| få igen (fik, fået) | get back | verb phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.125 |
| undvære (-ede, -et) | do without, spare | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.125 |
| sagtens | easily | adv | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.125 |
| stuvende fuld | packed, crammed | adj phrase | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.126; extractor judgment — informal register, no source tag |
| stuve (-ede, -et) | stow, pack, cram | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.126 |
| ingen | nobody | pron | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.126, also Unit14 grammar pt.1 |
| dæk (-ket, -) | deck | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.126 |
| svær | difficult | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.126 |
| siddeplads (-en, -er) | seat | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.126 |
| lykkes (lykkedes, er lykkedes) | succeed, be successful | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.126; impersonal passive-only verb, discussed again p.130-132 |
| øl (-len, -ler) | (a bottle of) beer | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.126 |
| stol (-en, -e) | chair | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.126, recurs p.138, p.157 |
| cafeteria (cafeteriet, -er) | cafeteria | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.126 |
| jeg har ikke noget imod | I don't mind | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.126 |
| gå rundt | walk about | verb phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.126 |
| sted (-et, -er) | place | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.126 |
| over for | opposite; towards, to | prep | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.126, recurs p.158 with a second sense |
| ung | young | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.126; comparison ung/yngre/yngst given p.156 |
| kvinde (-n, -r) | woman | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.126 |
| toilet (-tet, -ter) | toilet | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.126 |
| et stykke tid | some time | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.126 |
| henvende sig til (-te, -t) | address (someone) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.126 |
| holde (holdt, holdt) | hold | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.126 |
| mens | while | conj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.126 |
| bamse (-n, -r) | teddybear | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.126 |
| med det samme | straight away, immediately | adv phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.126, p.150 |
| kort | short (here: shortly) | adv | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.127 |
| ankomst (-en, -er) | arrival | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.127 |
| barnepige (-n, -r) | nanny | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.127 |
| jeg ved ikke rigtig | I am not quite sure | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.127 |
| i land | ashore | adv phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.127 |
| bede (bad, bedt) | ask | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.127 |
| det er lettere sagt end gjort | that is more easily said than done | idiom | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.127; fixed saying, not flagged colloquial |
| om bord | on board | adv phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.127 |
| hår (-et, -) | hair | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.127 |
| brun | brown | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.127 |
| øje (-t, øjne) | eye | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.127 |
| ansigt (-et, -er) | face | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.127 |
| ganske | quite | adv | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.127 |
| køn | pretty | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.127 |
| middelhøjde (-n) | average/medium height | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.127 |
| tynd | thin | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.127 |
| have på (har, havde, haft) | wear | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.127, recurs p.136, p.174 |
| grøn | green | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.127; also in colours table p.129 |
| jakke (-n, -r) | jacket | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.127 |
| kjole (-n, -r) | dress | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.127 |
| kuffert (-en, -er) | suitcase | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.127 |
| taske (-n, -r) | bag | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.127 |
| håndtaske (-n, -r) | handbag | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.128 |
| hånd (-en, hænder) | hand | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.128 |
| det eneste | the only thing | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.128, p.157 |
| efterlade (-lod, -ladt) | leave (behind) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.128 |
| baby (-en, -er) | baby | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.128 |
| barnevogn (-en, -e) | pram | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.128, recurs p.136-137 |
| heldigvis | fortunately | adv | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.128 |
| ble (-en, -er) | nappy | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.128 |
| skifte (ble) (-ede, -et) | change (a nappy) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.128 |
| mor | mother | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.128 kinship table; def. moren/moderen, pl. mødre, def.pl. mødrene |
| far | father | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.128 kinship table; def. faren/faderen, pl. fædre, def.pl. fædrene |
| barn | child | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.128; irregular plural barn/barnet/børn/børnene |
| datter | daughter | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.128; def. datteren, pl. døtre, def.pl. døtrene |
| søn | son | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.128; def. sønnen, pl. sønner, def.pl. sønnerne |
| søster | sister | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.128; def. søsteren, pl. søstre, def.pl. søstrene |
| bror | brother | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.128; def. broren/broderen, pl. brødre, def.pl. brødrene |
| forældre | parents | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.128; plural-only, def. forældrene |
| moder | mother (older form) | noun | archaic | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.128; source itself labels these "Old forms" of mor/far/bror |
| fader | father (older form) | noun | archaic | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.128; source itself labels these "Old forms" |
| broder | brother (older form) | noun | archaic | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.128; source itself labels these "Old forms" |
| bedsteforældre | grandparents | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.128; def. bedsteforældrene |
| bedstemor/bedste | grandmother (either term used) | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.128 |
| mormor | maternal grandmother | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.128 |
| farmor | paternal grandmother | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.128 |
| bedstefar | grandfather | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.128 |
| morfar | maternal grandfather | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.128 |
| farfar | paternal grandfather | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.128 |
| barnebarn | grandchild | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.128; irregular compound plural børnebørn (grammar exception, see Unit10 grammar pt.4) |
| tante | aunt (general) | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.129; def. tanten, pl. tanter, def.pl. tanterne |
| moster | aunt (mother's sister) | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.129 |
| faster | aunt (father's sister) | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.129 |
| onkel | uncle (general) | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.129; def. onkelen, pl. onkler, def.pl. onklerne |
| morbror | uncle (mother's brother) | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.129 |
| farbror | uncle (father's brother) | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.129 |
| kusine | cousin (female) | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.129; def. kusinen, pl. kusiner, def.pl. kusinerne |
| fætter | cousin (male) | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.129, recurs p.146 exercise |
| nevø | nephew | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.129; def. nevøen, pl. nevøer, def.pl. nevøerne |
| niece | niece | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.129; def. niecen, pl. niecer, def.pl. niecerne |
| svigermor | mother-in-law | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.129 |
| svigerfar | father-in-law | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.129 |
| svigerdatter | daughter-in-law | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.129 |
| svigersøn | son-in-law | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.129 |
| svigerinde | sister-in-law | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.129; def. svigerinden, pl. svigerinder, def.pl. svigerinderne |
| svoger | brother-in-law | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.129; def. svogeren, pl. svogre, def.pl. svogrene |
| svigerforældre | parents-in-law | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.129; def. svigerforældrene |
| hvid | white | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.129; neut. hvidt, pl. hvide |
| gul | yellow | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.129; neut. gult, pl. gule |
| rød | red | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.129; neut. rødt, pl. røde |
| blå | blue | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.129; neut. blåt, pl. blå (unchanged) |
| brun | brown | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.129; neut. brunt, pl. brune |
| grå | grey | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.129; neut. gråt, pl. grå (unchanged) |
| sort | black | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.129; neut. sort (unchanged), pl. sorte |
| lyseblå, lysegrøn, lysebrun | pale/light blue/green/brown | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.129; productive lyse- compounding prefix, see grammar note |
| lyserød | pink | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.129; semantically specialized, not just "light red" |
| mørkeblå, mørkegrøn, mørkebrun | dark blue/green/brown | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.129; productive mørke- compounding prefix |
| kirkeklokke | church bell | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.132; compound noun grammar example |
| chokoladefabrik | chocolate factory | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.132; compound noun grammar example |
| afgå | depart | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.132; perfect-tense-with-er verb list |
| ankomme | arrive | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.132; cf. noun ankomst p.127 |
| dreje (intrans.) | turn | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.132 |
| falde i søvn | fall asleep | verb phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.132 |
| holde op | stop | verb phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.132 |
| vokse | grow | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.132 |
| pige (-n, -r) | girl | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.135 |
| slank | slender | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.135 |
| arm (-en, -e) | arm | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.135 |
| ben (-et, -) | leg | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.135 |
| lys | fair (hair colour) | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.135 |
| kind (-en, -er) | cheek | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.135 |
| mund (-en, -e) | mouth | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.135, idiom "munden går i baglås" p.148 |
| ordensmenneske (-t, -r) | tidy person | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.135 |
| rydde op (-ede, -et) | tidy up | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.135 |
| gifte sig (-ede, -et) | marry, get married | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.135 |
| bryllup (-pet, -per) | wedding | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.135 |
| (til) pinse | (at) Whitsun | noun/time expr | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.135; cf. "pinsemorgen" p.147 |
| tyk | fat, thick | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.136 |
| som barn | as a child | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.136 |
| fyr (-en, -e) | fellow | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.136, recurs p.137 "den lille fyr" |
| bevæge sig (-ede, -et) | move | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.136 |
| mave (-n, -r) | stomach | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.136 |
| dobbelthage (-n, -r) | double chin | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.136 |
| hage (-n, -r) | chin | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.136 |
| beskrive (beskrev, beskrevet) | describe | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.136 |
| nærmere | more closely, more precisely, in detail | adv | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.136 |
| gråhåret | grey-haired | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.136 |
| gå med briller | wear glasses | verb phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.136 |
| briller (pl.) | glasses | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.136 |
| næse (-n, -r) | nose | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.136 |
| som sagt | as mentioned (before) | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.136 |

### Unit 11: Hjemme hos Hans og Lone igen — Back at Hans and Lone's house

| det må jeg nok sige! | well, I never! | idiom | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.137; extractor judgment — exclamatory idiom, no source tag |
| sandelig | indeed | adv | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.137 |
| overraskelse (-n, -er) | surprise | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.137 |
| stolt | proud | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.137 |
| spøg til side | joking apart | phrase | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.137; extractor judgment — conversational idiom |
| spøg (-en) (only sing.) | joke | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.137 |
| mærkelig | strange | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.137 |
| historie (-n, -r) | history, story, affair | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.137, recurs p.162 "history" sense |
| love (-ede, -et) | promise | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.137 |
| passe (-ede, -et) | look after, mind | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.137, recurs p.138 "godt passet" |
| dukke op (-ede, -et) | turn up | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.137 |
| stakkels | poor, pitiable | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.137, recurs p.145 exercise, p.156 grammar (adjectives ending -s don't change), p.181 |
| politistation (-en, -er) | police station | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.137 |
| melde (-te, -t) | report | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.137 |
| sag (-en, -er) | matter, case | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.137 |
| politi (-et) | police | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.137 |
| politibetjent (-en, -e) | policeman | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.138 |
| efternavn (-et, -e) | surname | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.138 |
| tage telefonen (tog, taget) | answer the telephone | verb phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.138 |
| telefon (-en, -er) | telephone | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.138, recurs p.141 vækkeur note |
| farvel så længe | see you soon (lit. goodbye so long) | phrase | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.138; extractor judgment — informal parting phrase |
| på vej | on the way | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.138 |
| vej (-en, -e) | road, way | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.138 |
| føle sig dårlig tilpas (-te, -t) | feel ill | verb phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.138 |
| pludselig | suddenly | adv | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.138, recurs p.150, p.157 |
| dårlig | ill, unwell; bad, poor | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.138 |
| svimmel | dizzy, giddy | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.138 |
| have kvalme | feel sick | verb phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.138 |
| kvalme (-n) | nausea | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.138 |
| besvime (-ede, -et) | faint | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.138 |
| vågne (-ede, -et) (intrans.) | wake up | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.138, recurs p.141-142 Ordforklaringer |
| kaj (-en, -er) | quay | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.138, recurs p.142 |
| skib (-et, -e) | ship, boat | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.138 |
| forsvinde (forsvandt, forsvundet) | disappear | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.138 |
| blive siddende | stay (lit. remain sitting) | verb phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.138; cf. "blive boende" p.139, grammar pt.2 p.168 |
| forstå (forstod, forstået) | understand | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.138 |
| hvordan har du det? | how do you feel? | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.138 |
| undersøge (-te, -t) | examine | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.138 |
| læge (-n, -r) | doctor | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.138 |
| over al forventning | beyond all expectation | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.139 |
| interesse (-n, -r) (for) | interest (in) | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.139 |
| dag (-en, -e) | day | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.139; recurs constantly throughout |
| ordre (-n, -r) | order | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.139 |
| blive boende | stay, remain staying | verb phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.139; cf. grammar pt.2 p.168 |
| i fredags | last Friday | adv phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.139; cf. "i mandags, tirsdags" pattern p.142 |
| dame (-n, -r) | lady | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.139 |
| eller rettere | or rather | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.139 |
| utrolig | incredibly | adv | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.139 |
| gæstfri | hospitable | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.139; grammar pt.3 p.145 covers its -t/-e(e) forms |
| juli | July | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.140; also in months table p.142 |
| lægge planer | make plans | verb phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.140 |
| lægge (lagde, lagt) | put, place, lay | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.140; distinguished from sætte p.141 Ordforklaringer |
| plan (-en, -er) | plan | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.140 |
| rest (-en, -er) | rest, remainder | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.140 |
| besøg (-et, -) | visit | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.140 |
| sprogkursus (-et, -kurser) | language course | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.140 |
| undervisning (-en) | tuition, lessons | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.140 |
| uden tvivl | without doubt, undoubtedly | adv phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.140 |
| inden da | before then | adv phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.140 |
| fejre (-ede, -et) | celebrate | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.140 |
| fødselsdag (-en, -e) | birthday | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.140; recurs same page several times |
| engang | once | adv | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.140; cf. "engang imellem" p.171 |
| nøjagtig | exactly | adv | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.140 |
| sprogskole (-n, -r) | language school | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.140 |
| det falder mig ikke naturligt | it does not come naturally to me | idiom | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.140 |
| findes | be found (here: is) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.140 |
| vækkeur (-et, -e) | alarm clock | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.141 |
| vække (-ede, -et) | wake (someone) up (transitive) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.141; contrasted with intransitive vågne |
| mandag, tirsdag, onsdag, torsdag, fredag, lørdag, søndag | Monday ... Sunday | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.142; days not capitalized in Danish, grammar note |
| januar – december (12 months) | January ... December | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.142; months not capitalized in Danish |
| forår | spring | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.143 |
| sommer | summer | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.143; def.pl. somre |
| efterår | autumn | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.143 |
| vinter | winter | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.143; def.pl. vintre |
| i år | this year | adv phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.143, recurs p.172 |
| sidste år, i fjor | last year | adv phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.143 |
| næste år | next year | adv phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.143 |
| hundrede | hundred | numeral | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.144; neuter noun, plural -r after no numeral (hundreder af børn) |
| tusind(e) | thousand | numeral | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.144 |
| million | million | numeral | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.144; common gender, cf. p.124 "indbygger" context |
| milliard | billion | numeral | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.144 |
| fornuftig | sensible, reasonable | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.146; exercise 5(e), new adjective not glossed elsewhere |
| sulten | hungry | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.146; exercise 5(i) |
| udmærket | excellent | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.146 exercise 5(j), recurs p.180 grammar as example |
| studentereksamen (-en, -er/-eksaminer) | school-leaving exam corresponding to A-levels | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.146 |
| medicin | medicine | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.146 |
| køre fast (-te, -t) | get bogged down | verb phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.146 |
| studium (studiet, -er) | study, degree course | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.146; -um noun declension explained p.169 grammar pt.3 |
| koncentrere sig (om) (-ede, -et) | concentrate (on) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.146 |
| bog (-en, bøger) | book | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.146 |
| afbryde (afbrød, afbrudt) | break off | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.146, recurs p.176 "afbryder" (interrupts) |
| lige hvad | just what | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.146 |
| indse (indså, indset) | understand, realise | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.146 |
| lægegerning (-en) | medical profession | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.146 |
| det rigtige | the right thing | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.147 |
| oplevelse (-n, -r) | experience | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.147 |
| allesammen | all of us (or: you, them) | pron | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.147 |
| vi kom godt ud af det med hinanden | we got on well | idiom | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.147; extractor judgment — conversational idiom built on "komme ud af det med" |
| skøn | beautiful | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.147 |
| springe ud (sprang, sprunget) | burst/come into leaf | verb phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.147 |
| allevegne | everywhere | adv | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.147 |
| cykle (-ede, -et) | cycle | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.147; cf. noun "cykel" p.183 |
| danse (-ede, -et) | dance | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.147 |
| pinsemorgen | Whitsun morning | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.147; cf. "pinse" p.135 |

### Unit 12: På sprogkursus — On a language course

| begynderhold (-et, -) | class/group for beginners | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.148 |
| elev (-en, -er) | pupil, student | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.148 |
| der ikke kan dansk | who don't know Danish | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.148 |
| kunne (kan, kunne, kunnet) | here: know (a language) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.148; full modal system covered Unit13 grammar pt.1 |
| udtale (-n, -r) | pronunciation | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.148 |
| grammatik (-ken, -ker) | grammar | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.148 |
| stave (-ede, -et) | spell | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.148 |
| time (-n, -r) | here: lesson, class | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.148 |
| munden går i baglås for dem | they get tongue-tied (lit. their mouths get jammed) | idiom | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.148; extractor judgment — vivid informal idiom |
| svare på et spørgsmål | answer a question | verb phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.148 |
| spørgsmål (-et, -) | question | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.148, recurs p.181 |
| udtale (-te, -t) | pronounce | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.148; distinct from noun "udtale" (pronunciation) above |
| volde (-te, -t) | cause | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.148 |
| kendskab (-et) | knowledge | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.148 |
| diskutere (-ede, -et) | discuss | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.148 |
| novelle (-n, -r) | short story | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.148 |
| skiftes til (skiftedes til, har skiftedes til) | take it in turns | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.148 |
| resumé (-et, -er) | summary | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.148 |
| fortælling (-en, -er) | story | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.148 |
| lege (-ede, -et) | play (children's games) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.148; contrasted with "spille" p.166 |
| leg (-en, -e) | game | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.148 |
| legen går ud på | the idea of the game is | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.148 |
| utilfreds | discontented, dissatisfied | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.148; neut./pl. forms discussed p.169 grammar pt.4 |
| tilværelse (-n) | existence, life | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.148 |
| utilfredshed (-en) | dissatisfaction | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.148 |
| skyldes (skyldtes, har skyldtes) | be due to, be caused by | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.148 |
| især | especially | adv | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.148 |
| beskæftigelse (-n, -r) | occupation, work, employment | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.148 |
| for alles vedkommende | as far as everybody is concerned | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.148 |
| for mit vedkommende | as far as I am concerned | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.148 |
| ideel | ideal, perfect | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.148 |
| stilling (-en, -er) | occupation; position | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.148 |
| stille spørgsmål (-ede, -et) | ask questions | verb phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.148 |
| respektive | respective | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.148 |
| arbejde (-t, -r) | work, employment | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.148 |
| slutte (-ede, -et) | end | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.148 |
| finde frem til (fandt, fundet) | work out | verb phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.148 |
| bytte (-ede, -et) | exchange, swap | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.148, recurs p.150 "bytte job" |
| indendørs | indoors | adv | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.150 |
| udendørs | out of doors | adv | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.150 |
| indendøre | indoors | adv | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.150; variant form of indendørs |
| dør (-en, -e) | door | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.150, recurs p.165 "gå ind ad døren" |
| job (-bet, -) | job | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.150 |
| radio (-en, -er) | radio | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.150, recurs p.183-185 pictured |
| overhovedet ikke | not at all | adv phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.150 |
| frygtelig | terrible | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.150 |
| ekspedere (-ede, -et) | serve (customers) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.150 |
| butik (-ken, -ker) | shop | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.150 |
| kedelig | boring | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.150 |
| provinsby (-en, -er) | provincial town | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.150 |
| mulighed (-en, -er) | possibility | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.150 |
| imellem | among, between | prep | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.150 |
| omsider | at long last, eventually | adv | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.150 |
| spare sammen (-ede, -et) | save up | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.150 |
| åbne (-ede, -et) | open | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.150 |
| udenfor | outside | adv | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.150 |
| ferierejsende | holiday-maker(s) | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.150; form is adjectival (present participle of "rejse"), see grammar note p.156 |
| ønskestilling (-en, -er) | ideal occupation | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.150 |
| have travlt | be busy | verb phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.151, recurs p.158 "Jeg har travlt" |
| skrive (skrev, skrevet) | write | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.151; principal parts listed again p.154 grammar |
| stil (-en, -e) | essay | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.151 |
| lærer (-en, -e) | teacher | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.151 |
| indledning (-en, -er) | beginning, introduction | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.151 |
| vælge (valgte, valgt) | choose | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.151 |
| storby (-en, -er) | city | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.151 |
| larm (-en) | noise | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.151 |
| stærk | here: heavy | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.151 |
| trafik (-ken) | traffic | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.151 |
| går ham på nerverne | get(s) on his nerves | idiom | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.151; extractor judgment — informal idiom |
| nerve (-n, -r) | nerve | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.151 |
| tåle (-te, -t) | tolerate, endure, stand | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.151 |
| forurening (-en) | pollution | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.151 |
| lægge til side | put aside | verb phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.151 |
| leve af (-ede, -et) | live by, make a living by | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.151, recurs p.152 Ordforklaringer (two senses: live by/live on) |
| flytte (-ede, -et) | move (residence) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.151 |
| luft (-en) | air | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.151 |
| ren | clean, pure | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.151 |
| pistol (-en, -er) | pistol | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.151 |
| løbe (løb, løbet) | run | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.151, recurs p.168 "kom løbende" |
| dreng (-en, -e) | boy | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.151 |
| sætning (-en, -er) | sentence | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.151 |
| fredelig | peaceful | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.151 |
| imidlertid | however | conj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.151 |
| motorvej (-en, -e) | motorway | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.151 |
| for enden af | at the end of | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.151 |
| bruge (brugte, har brugt) | use; spend (money) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.152 |
| tilbringe (tilbragte, har tilbragt) | spend (time) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.152 |
| bo (-ede, -et) | live, reside, stay | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.152; distinguished from "leve" (be alive) same page |
| leve (-ede, -et) | be alive, live | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.152 |
| Danmark/dansker/dansk | Denmark/Dane/Danish | proper noun/noun/adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.152; country-inhabitant-language triple |
| England/englænder/engelsk | England/Englishman/English | proper noun/noun/adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.152 |
| Norge/nordmand (nordmænd)/norsk | Norway/Norwegian(person)/Norwegian | proper noun/noun/adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.152; irregular plural nordmænd |
| Sverige/svensker/svensk | Sweden/Swede/Swedish | proper noun/noun/adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.152 |
| Tyskland/tysker/tysk | Germany/German(person)/German | proper noun/noun/adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.152; cf. p.124 "Tyskland" |
| Frankrig/franskmand (franskmænd)/fransk | France/Frenchman/French | proper noun/noun/adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.152; irregular plural franskmænd |
| Italien/italiener/italiensk | Italy/Italian(person)/Italian | proper noun/noun/adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.152 |
| Holland/hollænder/hollandsk | Holland/Dutchman/Dutch | proper noun/noun/adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.152 |
| Belgien/belgier/belgisk | Belgium/Belgian(person)/Belgian | proper noun/noun/adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.152 |
| Spanien/spanier/spansk | Spain/Spaniard/Spanish | proper noun/noun/adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.152 |
| Grækenland/græker/græsk | Greece/Greek(person)/Greek | proper noun/noun/adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.152 |
| hvis | whose | pron | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.153; relative pronoun, grammar pt.1 |
| byde (bød, budt) | bid | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.154; irregular verb paradigm list, group (b) |
| lyde (lød, lydt) | sound | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.154 |
| nyde (nød, nydt) | enjoy | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.154; cf. grammar pt.3 present participle example p.155 |
| tælle (talte, har talt) | count | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.155; irregular verb paradigm list, group (c) |
| irriterende | annoying | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.156; present-participle-as-adjective example |
| lovende | promising | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.156 |
| forsvindende | vanishing | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.156; participle of forsvinde |
| ung/yngre/yngst | young/younger/youngest | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.156; irregular comparison, grammar pt.4 |
| få/færre/færrest | few/fewer/fewest | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.156; irregular comparison, grammar pt.4 |
| vide (ved, vidste, har vidst) | know (a fact) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.158 exercise, recurs throughout as high-frequency verb; distinguished from kende/kunne |
| kende (kendte, har kendt) | know, be acquainted with | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.158 exercise, recurs p.161 "kender faktisk ikke" |
| have lyst til | feel like | verb phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.159, recurs p.170 exercise |
| lyst (-en, -er) | inclination, wish, desire | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.159 |
| hygge sig | have a good time, enjoy oneself | verb phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.159 |
| behøve (-ede, -et) | need (=være nødt til) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.159 |
| høflig | polite | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.159 |
| fremmed | foreign, strange; (as noun) the stranger | adj/noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.159; neut./pl. forms discussed p.180-181 |
| nej da | of course not | phrase | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.159; extractor judgment — spoken discourse particle, no source tag |
| da | of course, certainly, indeed | adv | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.159; extractor judgment — spoken discourse particle; also the tag-question particle after positive questions (grammar pt., p.179) |
| for nylig | recently | adv | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.160 |
| foreslå (foreslog, foreslået) | suggest | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.160 |
| for tiden | at present | adv phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.160 |
| forhandle (-ede, -et) | market, sell | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.160 |
| eje (-ede, -et) | own | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.160 |
| forretning (-en, -er) | shop | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.160 |
| ringe (mig) op (-ede, -et) | call (me) (on the phone) | verb phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.160 |
| præsentere (-ede, -et) | introduce | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.160 |
| invitation (-en, -er) | invitation | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.160 |

### Unit 13: Turister i København — Tourists in Copenhagen

| kongerige (-t, -r) | kingdom | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.162 |
| fin | fine, grand | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.162 |
| (Christian) den fjerde | (Christian) IV | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.162; royal ordinal-title pattern |
| regere (-ede, -et) | rule | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.162 |
| byplanlægning (-en) | town planning | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.162 |
| børs (-en, -er) | stock exchange | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.162 |
| rund | round | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.162 |
| regeringstid (-en) | reign | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.162 |
| omgive (omgav, omgivet) | surround | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.162 |
| vold (-en, -e) | rampart | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.162 |
| 1870erne | the 1870s | date expr | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.162; decade-naming pattern |
| rive ned (rev, revet) | demolish, pull down | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.162 |
| Vesterbro, Nørrebro, Østerbro | districts in Copenhagen | proper noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.162 |
| bro (-en, -er) | bridge | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.162 |
| med rivende fart | at a tremendous speed | idiom | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.162 |
| fart (-en) | speed | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.162 |
| historie (-n) | history | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.162; second sense of "historie" (cf. Unit11 "story, affair" p.137) |
| elleve hundrede tres | 1160 | date expr | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.162 |
| konge (-n, -r) | king | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.162 |
| vikingehavn (-en, -e) | viking harbour | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.162 |
| viking (-en, -er) | viking | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.162 |
| biskop (-pen, -per) | bishop | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.162 |
| borg (-en, -e) | castle | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.162 |
| netop | exactly, precisely | adv | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.162 |
| følgende | following | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.162, recurs p.181 grammar example |
| århundrede (-t, -r) | century | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.162 |
| betydning (-en) | importance; meaning, sense | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.162, second sense discussed p.165 Ordforklaringer |
| beliggenhed (-en) | situation, position | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.162 |
| købmand (-en, købmænd) | merchant; grocer | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.162, both senses discussed p.165 Ordforklaringer |
| fjorten hundrede treogfyrre | 1443 | date expr | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.162 |
| fjorten hundrede nioghalvfjerds | 1479 | date expr | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.162 |
| grundlægge (-lagde, -lagt) | found | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.162 |
| energi (-en) | energy | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.163 |
| spadseretur (-en, -e) | walk | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.163 |
| spadsere (-ede, -et) | walk | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.163 |
| bør (pres. tense of burde) | ought | modal verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.163; full modal system Unit13 grammar pt.1 |
| udpege (-ede, -et) | point out | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.163 |
| værd | worth (a visit) | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.163, recurs p.181 grammar pt.2(f) "unchanged" adjective |
| havfrue (-n, -r) | mermaid | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.163 |
| kongelig | royal | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.163 |
| videre | on, further | adv | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.163 |
| livlig | lively | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.163 |
| kvarter (-et, -er) | quarter, district, part of town | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.163 |
| bar (-en, -er) | bar | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.163 |
| fortovskafé (-en, -er) | pavement café | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.163 |
| fortov (-et, -e) | pavement | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.163 |
| Strøget | the main shopping street in central Copenhagen | proper noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.163 |
| høre (-te, -t) | hear | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.163 |
| gå (gik, gået) | here: run (of a street/road) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.163; distinct sense from ordinary "go" |
| Rådhuspladsen | the City Hall Square | proper noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.163 |
| rådhus (-et, -e) | town/city hall | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.163 |
| plads (-en, -er) | here: square | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.163 |
| afstikker (-en, -e) | detour | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.163 |
| folketinget | the Danish Parliament | proper noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.163 |
| have til huse | be housed | verb phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.163 |
| fortsætte (-satte, -sat) | continue | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.163 |
| have på fornemmelsen | have a feeling, have a hunch | idiom | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.163; extractor judgment — informal idiom |
| fornemmelse (-n, -r) | feeling | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.163 |
| afslutte (-ede, -et) | finish, conclude | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.164 |
| udsyn (-et, -) | view | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.164 |
| top (-pen, -pe) | top | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.164 |
| trappe (-n, -r) | staircase, stairs, steps | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.164 |
| tør (pres. tense of turde) | dare | modal verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.164, recurs p.165 "Jeg tør ikke"; full modal system Unit13 grammar pt.1 |
| ad | at (directed towards); by (with op/ned = up/down the stairs) | prep | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.165; recurs 4x in same Ordforklaringer section |
| spille (-ede, -et) | play (an instrument, cards, football) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.166; contrasted with "lege" (children's games) p.148 |
| måtte (må) | must; may | modal verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.167; full modal system grammar pt.1 |
| burde (bør) | ought to | modal verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.166; infinitive of "bør" p.163 |
| turde (tør) | dare | modal verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.166; infinitive of "tør" p.164 |
| museum (museet, museer, museerne) | museum | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.169; -um noun class, drops -um before endings |
| indrømme (-ede, -et) | admit | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.171 |
| savne (-ede, -et) | miss | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.171 |
| engang imellem | now and then, occasionally | adv phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.171 |
| spille en rolle (-ede, -et) | play a part | verb phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.171 |
| rolle (-n, -r) | part, role | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.171 |
| i nærheden af | near, close to | prep phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.171 |
| nærhed (-en) | proximity, vicinity | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.171 |
| på grøftekanten | at the side of the road/path | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.171 |
| grøftekant (-en, -er) | edge of ditch | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.171 |
| busk (-en, -e) | bush | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.171 |
| egn (-en, -e) | part of the country, area, district | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.171 |
| dyreliv (-et) | fauna | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.171 |
| fugl (-en, -e) | bird | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.171 |
| rede (-n, -r) | nest | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.171 |
| tagrende (-n, -r) | gutter | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.171 |
| tag (-et, -e) | roof | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.171 |
| trækrone (-n, -r) | crown/top of tree | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.171 |
| dø (døde) | die | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.172; "han er død" = he has died |
| på det tidspunkt | then, at that time | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.172 |
| tidspunkt (-et, -er) | time, moment | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.172 |
| grad (-en, -er) | degree | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.172 |
| begravelse (-n, -r) | funeral, burial | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.172 |
| begrave (-ede, -et) | bury | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.172 |
| snestorm (-en, -e) | blizzard | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.172 |
| sne (-en) | snow | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.172 |
| storm (-en, -e) | gale | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.172 |
| fyge (-ede, -et or føg, føget) | drift (of snow) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.172 |
| gravsten (-en, -) | tombstone | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.172 |
| grav (-en, -e) | grave | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.172 |
| kiste (-n, -r) | coffin | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.172 |
| sænke (-ede, -et) | lower | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.172 |
| selv om | even though | conj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.172 |
| syg | ill | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.172 |
| seng (-en, -e) | bed | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.172 |
| influenza (-en) | flu | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.172 |
| flere | several | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.172 |
| komme sig (kom, kommet) | recover | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.172 |

### Unit 14: På restaurant — At a restaurant

| væk | away | adv | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.174 |
| kunne lide | like | verb phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.174; full likes/dislikes system p.178-179 |
| sikkert | very likely, no doubt | adv | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.174 |
| luge (-ede, -et) | weed | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.174 |
| istandsættelse (-n, -r) | repair, restoration | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.174 |
| trist | sad | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.174, recurs p.187 |
| tanke (-n, -r) | thought | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.174 |
| ved tanken om, at... | at the thought that... | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.174 |
| være ved at | be on the point of, be about to | verb phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.174 |
| skjorte (-n, -r) | shirt | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.174 |
| tage (tog, taget) på | put on (clothes) | verb phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.174; distinct sense from "tage telefonen" p.138 |
| slips (-et, -) | tie | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.174 |
| hvad med... | what about... | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.175 |
| hummer (-en, -e) | lobster | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.175, recurs p.177-178 |
| skaldyr (-et, -) | shellfish | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.175 |
| østers (-en, -) | oyster | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.175, recurs p.179 |
| vegetar (-en, -er) | vegetarian | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.175 |
| hverken...eller | neither...nor | conj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.175 |
| kød (-et) | meat | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.175 |
| champignonsuppe (-n) | mushroom soup | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.175 |
| champignon (-en, -er) | mushroom | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.175 |
| suppe (-n, -r) | soup | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.175 |
| skive (-n, -r) | slice | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.175 |
| melon (-en, -er) | melon | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.175 |
| gravad | marinated (in salt, sugar and spices) | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.175 |
| laks (-en, -) | salmon | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.175, recurs p.177 |
| spisekort (-et, -) | menu | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.175 |
| livret (-ten, -ter) | favourite dish | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.175 |
| ål (-en, -) | eel | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.175, recurs p.176 |
| ål i gelé | jellied eels | noun phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.175; recurs p.178 "holder meget af" |
| ..., ikke? | ..., won't you? (positive-question tag) | phrase | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.175; extractor judgment — spoken tag particle, grammar rule given explicitly p.179 (ikke follows positive questions, vel follows negative ones) |
| bryde sig om (brød, brudt) | care for, like | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.175, recurs p.178-179 likes/dislikes system |
| gang (-en, -e) | portion, helping | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.176; distinct sense from "once/time" (cf. "engang" p.140) |
| kylling (-en, -er) | chicken | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.176 |
| agurkesalat (-en) | cucumber salad (sliced, in vinegar/sugar/salt dressing) | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.176 |
| undtagen | except | conj/prep | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.176 |
| omelet (-ten, -ter) | omelette | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.176 |
| have til bords | take in to dinner, sit next to | verb phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.176 |
| hjemmelavet | home-made | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.176 |
| friskplukket | freshly picked | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.176, recurs p.181 grammar example (-et → -ede, -t→-d- rule) |
| hvidvin (-en, -e) | white wine | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.177 |
| forret (-ten, -ter) | first course | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.177 |
| hovedret (-ten, -ter) | main course | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.177 |
| løse (-te, -t) | loosen, release, solve | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.177 |
| løse tungebåndene | loosen the tongues | idiom | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.177 |
| der snakkes livligt | the conversation is lively | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.177 |
| med hensyn til | as regards | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.177 |
| hensyn (-et, -) | consideration | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.177 |
| national | national | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.177 |
| identitet (-en) | identity | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.177 |
| betragte (-ede, -et) | consider | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.177 |
| tosprogethed (-en) | bilingualism | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.177 |
| skabe (-te, -t) | create | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.177 |
| indtage (indtog, indtaget) | take up, assume, fill, occupy | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.177 |
| særstilling (-en, -er) | exceptional position | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.177 |
| forandre sig (-ede, -et) | change (intrans.) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.177 |
| finde sted (fandt, fundet) | happen, take place | verb phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.177 |
| selvtillid (-en) | (self-)confidence | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.177 |
| mangle (-ede, -et) | lack | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.177 |
| inderst inde | deep down | adv phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.177 |
| vel | I suppose; also the tag-question particle after a negative question | adv | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.177, recurs p.179 grammar rule; extractor judgment — spoken-register particle |
| forvirret | confused | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.177 |
| i hvert fald | here: definitely, absolutely | adv phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.177 |
| klog | wise | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.177 |
| borddame (-n, -r) | partner at dinner | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.177 |
| skåle med (-ede, -et) | toast (someone) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.177 |
| skål! | cheers! | interj | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.178; extractor judgment — social-ritual exclamation; book's own Ordforklaringer frames it as a named Danish toasting custom |
| hilse på (-te, -t) | greet; propose a toast (here) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.178 |
| holde af | be fond of | verb phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.178; part of likes/dislikes system, cf. Unit10 "holder meget af" p.136 |
| synes om | like, approve of | verb phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.178 |
| elske | love | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.178, recurs p.175 "jeg elsker skaldyr" |
| mægtig (vældig/rigtig) godt lide | be very fond of | idiom | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.178; extractor judgment — "mægtig" as an intensifier ("terribly/really fond of") is an informal register choice |
| få (fik, fået) | get, obtain, receive | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.179; distinguished here from "have" (possess) — "Kan jeg få et glas vin?" |
| ingen | no, none (common gender/plural) | pron/adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.180; grammar pt.1, also a pronoun "nobody" (cf. p.126) |
| intet | no, none (neuter) | pron/adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.180 |
| ingenting | nothing | pron | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.180; has replaced "intet" as the pronoun "nothing" in modern usage, per source |
| politisk | political | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.181; grammar example, adjectives ending -sk |
| anderledes | different(ly) | adv/adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.181 |
| forhold (-et, -) | condition, circumstance | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.181; "forholdene var anderledes dengang" |
| egen, eget, egne | own | adj | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.182; grammar pt.4, exception to the stressed-vowel-adjective rule |
| gaffel (gafler) | fork | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.183; pictured-vocabulary exercise |
| kniv (-e) | knife | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.183 |
| smykke (-r) | jewel, piece of jewellery | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.183 |
| ur (-e) | watch, clock | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.183 |
| paraply (-er) | umbrella | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.183 |
| fjernsyn (-) | television | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.183, recurs p.184-185 |
| æble (-r) | apple | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | p.183 |
| pære (-r) | pear | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.183, recurs p.184 exercise example |
| cykel (cykler) | bicycle | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.183, recurs p.184-185; cf. verb "cykle" p.147 |
| bil (-er) | car | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | p.183, recurs p.184-185 |

### Unit 15: Da I besøgte os i England — When you visited us in England

| i går | yesterday | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| vel nok | really, actually | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| hovedpine | headache | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| i aftes | last night | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| pille | pill | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| gå over (gik, gået) | pass, wear off | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | this sense distinct from "gå over" = "cross over" seen elsewhere |
| gerne | with pleasure, gladly | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | also means "usually, as a rule" in some sentence positions (p.194) |
| valg | election; choice | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| lukke op for (-ede, -et) | turn on (e.g. the TV) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| fjernsyn | television | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| enten ... eller | either ... or | conjunction | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| partipolitisk | party political | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| udsendelse | broadcast | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| diskussion | discussion | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| politiker | politician | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| parti | (political) party | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| TV-avis | television news | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| meningsmåling | opinion poll | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| spændende | exciting | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| have svært ved | find it difficult (to) | idiom | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| system | system | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| undgå (undgik, undgået) | avoid | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| kaos | chaos | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| virke (-ede, -et) | work, function | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| regering | government | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| opnå (-ede, -et) | get, obtain | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| mandat | seat (in parliament) | noun | technical | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| umulig | impossible | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| enkelt | single | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| flertal | majority | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| samlingsregering | coalition government | noun | technical | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| yderliggående | extreme, radical | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| støtte | support, backing | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| moderat | moderate | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| en lille smule | a little bit | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| stemme på (-te, -t) | vote (for) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| resultat | result | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| skuffe (-ede, -et) | disappoint | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| blive enige om (blev, blevet) | agree on | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| emne | subject, topic | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| virkelig | really | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| underlig | strange | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| holdning | attitude | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| overdrive (overdrev, overdrevet) | exaggerate | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| gal | bad, wrong | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | gal more commonly means "mad/angry" elsewhere; this "så galt" = "so bad" idiomatic sense |
| mene noget alvorligt | be serious (about something) | idiom | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| mene (-te, -t) | mean; think | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| alvorlig | serious | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| for sjov | in jest, as a joke | phrase | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| sjov | fun | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| indbydelse | invitation | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| før eller senere | sooner or later | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| nuværende | present, current | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| lejlighed | flat/apartment; opportunity; occasion | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | triple polysemy explicitly discussed in Ordforklaringer, p.192 |
| være ved at | be about to / be in the process of / be engaged in | idiom | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | followed by infinitive; recurs with specific senses in Units 16 and 18 |
| både ... og | both ... and | conjunction | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| hverken ... eller | neither ... nor | conjunction | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| have det | feel (how are you) | idiom | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| have noget imod | mind, object to | idiom | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| have med | have brought along | idiom | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| have på | wear | idiom | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| have brug for | need | idiom | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| have lyst til | feel like (doing something) | idiom | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| have råd til | be able to afford | idiom | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | cross-referenced again in Unit 16 p.216/223 |
| have travlt | be busy | idiom | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| vis | certain | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| overbevisning | conviction | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| påvirke (-ede, -et) | influence | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| baggrund | background | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| gå op i (gik, gået) | devote oneself to, be interested in | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| derimod | on the other hand | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| styre (-ede, -et) | rule, govern | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| sund | healthy | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| ægtefælle | spouse, partner | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| alting | everything | pronoun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| give ret i (gav, givet) | agree with (someone, on a point) | idiom | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| mening | opinion / sense / intention | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | triple sense ("Giver det nogen mening?" = does it make sense; "Det var meningen" = it was intended) expanded again Unit 17 p.223 |
| hoved | head | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | also in "Legemsdele" body-part list, Unit 18 |
| ligne (-ede, -et) | look like, resemble | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| skriftlig | written | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| te | tea | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| handelshøjskole | commercial college, school of economics and business administration | noun | technical | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| eksamen | examination | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| højere handelseksamen | higher examination in economics and business administration | noun | technical | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| tung | heavy | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| drømme (-te, -t) | dream (verb) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| ubehagelig | unpleasant | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| drøm | dream (noun) | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| bange for | afraid of | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| få fat i (fik, fået) | get hold of | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| af stedet | (untranslated intensifier, lit. "from the place") | idiom | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | book explicitly flags this as not literally translatable |
| lystre (-ede, -et) | obey | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| rykke (-ede, -et) | move | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| dørklokke | door bell | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| mareridt | nightmare | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| rejsebureau | travel agency | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |

### Unit 16: Alison er syg — Alison is ill

| bleg | pale | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| lummer | close, sultry (of weather) | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| tordenvejr | thunderstorm | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| termometer | thermometer | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| temperatur | temperature | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| skat | darling, dear (term of affectionate address) | noun | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | SLANG/COLLOQUIAL FINDING — "Hej, skat!" (George to Alison, p.204) and "Tak, skat!" (Hans to Lone, p.244); not in a vocabulary box, drawn directly from dialogue; affectionate spousal address term, high value for slang-mechanism tracking |
| feber | temperature, fever | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| aftensmad | supper | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| det kan der ikke være tale om | that is out of the question | idiom | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| frikadelle | meat ball | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| kogebog | cookery book | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| det er noget værre noget med dig | you are in a bad way | idiom | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | colloquial sympathetic exclamation |
| tablet | tablet, pill | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| værre | worse | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| slå (feberen) ned (slog, slået) | get (the temperature) down | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| forstå på (forstod, forstået) | gather from | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| smerte | pain | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| nogen steder | anywhere | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| ørepine | earache | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| øre | ear | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| slem | bad | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| kigge (-ede, -et) | look | verb | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | everyday-spoken synonym of "se"/"kikke" |
| hals | neck, throat | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| lytte (-ede, -et) | listen | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| bryst | breast, chest | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| ørebetændelse | inflammation of the ear | noun | technical.medical | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| i første omgang | to begin with | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| omgang | lap, round | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| rask | healthy, fit, well | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| recept | prescription | noun | technical.medical | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | distinguished explicitly from "opskrift" (recipe), p.208 — a confirmable near-cognate trap |
| hver fjerde time | every four hours | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | pattern generalizes: "hvert tredje år" = every three years |
| normal | normal | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| doktor | doctor | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| lov | permission | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | common-gender noun, flagged in source as exceptional |
| ufornuftig | unwise | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | plausible_unverified | small-print gloss box; reading cross-checked against the common root "fornuft" (reason, sense) |
| penicillin | penicillin | noun | technical.medical | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| udsætte (udsatte, udsat) | postpone | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| mavepine | stomach ache | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| tandpine | toothache | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| influenza | flu | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| halsbetændelse | tonsillitis | noun | technical.medical | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| have ondt i | have a pain in, hurt | idiom | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | "Hun har ondt i halsen/hovedet/ryggen", "Han har ondt i foden" |
| opskrift | recipe | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| Solen skinner | the sun is shining | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | weather-expression set, p.208 |
| Det regner | it is raining | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| Det klarer op | it is clearing up | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| Det blæser | it is windy | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| Det stormer | a gale is blowing | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| Det er frostvejr | it is frosty | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| Det sner | it is snowing | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| Det er tøvejr | it is thawing | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| Det er overskyet | it is cloudy/overcast | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| Det er tåget | it is foggy/misty | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| blive af | end up, get to (of whereabouts) | idiom | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | "Hvor bliver George dog af?" — note the "dog" particle co-occurring |
| blive til noget | come off, come of something | idiom | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| blive ved med | continue, keep on (doing something) | idiom | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| blive væk / blive borte | disappear | idiom | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| blive enige | agree, reach agreement | idiom | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| lykkes | succeed | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | one of the "s-only" impersonal-passive-form verbs; see Grammar point below |
| mislykkes | fail | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | opposite of lykkes |
| synes | think, be of the opinion | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| følge (fulgte, fulgt) | follow, accompany | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| følges (ad) | accompany each other, go together | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| møde (-te, -t) | meet (someone) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| mødes | meet (reciprocal, "meet each other") | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| skylde (-te, -t) | owe | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| skyldes | stem from, be due to | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| skiftes til | take something in turns | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| findes | be, exist | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| slå (slog, slået) | hit, strike, beat | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| slås | hit each other, fight | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | past tense "sloges", distinct from slå's own past "slog" |
| da (unstressed discourse adverb) | conveys surprise, or merely used for emphasis / confirmation-seeking | adverb | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | MODAL PARTICLE — see Grammar point "Unstressed adverbs" below for full discussion |
| dog (unstressed discourse adverb) | conveys mild impatience or contrast | adverb | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | MODAL PARTICLE — see Grammar point below |
| jo (unstressed discourse adverb) | signals shared/assumed knowledge ("as you no doubt have noticed") | adverb | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | MODAL PARTICLE — see Grammar point below |
| nok (unstressed discourse adverb) | probably, definitely, I suppose | adverb | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | MODAL PARTICLE — see Grammar point below |
| nu (unstressed discourse adverb, distinct from temporal "nu"=now) | emphatic "I must say" stance marker | adverb | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | MODAL PARTICLE — see Grammar point below |
| vel (unstressed discourse adverb) | I suppose, probably, I hope; tag-question softener | adverb | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | MODAL PARTICLE — see Grammar point below |
| vist (unstressed discourse adverb) | probably (speaker's own inference) | adverb | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | MODAL PARTICLE — see Grammar point below |
| lave om på (-ede, -et) | alter, change | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| stadig | still | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| holde åbent (holdt, holdt) | be open (of a shop/business) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| nummer | number | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| lukke inde (-ede, -et) | lock up | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| under ingen omstændigheder | in no circumstances | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| omstændighed | circumstance | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| råd | piece of advice; means (money) | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | singular-form-for-plural-sense noun, revisited Unit 17 p.225-226 |
| det er ligegyldigt | it does not matter | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| ligegyldig | unimportant | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| sørge for (-ede, -et) | arrange | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| anstrengende | strenuous, tiring | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| bekymre sig om (-ede, -et) | worry about | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| noget som helst | anything at all | pronoun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| for en gangs skyld | for once | phrase | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |

### Unit 17: På indkøb i København — Shopping in Copenhagen

| elendig | miserable | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| væg | wall | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| være ved at male | be (in the process of) painting | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| gå fremad (gik, gået) | improve, make progress | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| langsomt | slowly | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| Ved du hvad ... | Listen ... | idiom | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | conversational attention-getter, listed under "Sådan siger man det" |
| har været os til stor hjælp | has been a great help to us | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| komme an på (kom, kommet) | depend on | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| lampe | lamp | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| stof | material, fabric | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| gardin | curtain | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| gå i gang med (gik, gået) | start (work) on | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| indkøb | purchase, shopping | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| kage | cake | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| smørrebrød | open sandwich(es) | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | book notes plural form used for the general/collective sense; "et stykke smørrebrød" for one open sandwich |
| rugbrød | rye bread | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| ost | cheese | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| vindrue | grape | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| mulig | possible | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| høre til (-te, -t) | belong to, be one of | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| leve i nuet (-ede, -et) | live in the present | idiom | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | "Jeg hører til den slags mennesker, der lever i nuet" — George's self-characterization |
| om man er lykkelig eller ej | whether one is happy or not | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| lykkelig | happy | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| i højere grad | to a larger degree, more | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| omgivelser | surroundings | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | plural-only noun |
| begrænset | limited | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| i hvor høj grad | to what extent | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| bestemme over (-te, -t) | control, decide (over something) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| tilfældig | accidental, random | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| vise sig at ... (-te, -t) | appear to ..., prove to ... | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| mønster | pattern | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| det var meningen, at det skulle ske | it was meant to happen | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| skæbnebegrebet | the concept of fate | noun | literary | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | compound of skæbne (fate) + begreb (concept); philosophical-register dialogue topic (George and Jette's fatalism discussion) |
| vidt (forskellige) | widely (different) | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| forudbestemt | predestined | adjective | literary | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| afdeling | department | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| boligudstyr | furniture and fittings | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| etage | floor, storey | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | distinguished from "sal" (a particular floor's number, in a block of flats) and "stue"/"stueetage" (ground floor) — see Ordforklaringer p.223 |
| sal | floor, storey (used of a specific numbered floor, especially in blocks of flats) | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| stue / stueetage | ground floor | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| guldsmed | jeweller | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| smykke | piece of jewellery | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | plural "smykker" used where English uses the mass-noun singular "jewellery" — see Unit 17 Grammar point on noun number |
| udvalg | selection | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| guldsmedeforretning | jeweller's shop | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| ekspedient | shop assistant | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| broche | brooch | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| armbånd | bracelet | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| halskæde | necklace | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| sølvarmbånd | silver bracelet | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| hylde | shelf | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| yderst | furthest | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| passe til (-ede, -et) | suit | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| beslutte sig (-ede, -et) | make up one's mind | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| passende | suitable | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| hver for sig | separately | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| pakke ind (-ede, -et) | wrap (up) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| bluse | blouse | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| nederdel | skirt | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| kjole | dress | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| skjorte | shirt | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| slips | tie | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| bukser | trousers | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | plural-only noun |
| cowboy bukser | jeans | noun | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | informal register compound, note English loan "cowboy" |
| jakkesæt | suit (men's) | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| spadseredragt | suit (ladies') | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| jakke | jacket | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| frakke | coat | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| regnfrakke | raincoat | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| strømpebukser | tights | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | plural-only noun |
| sok | sock | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| hat | hat | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| gå med (gik, gået) | wear (e.g. glasses, habitually) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | "Han går med briller" — distinct phrasal-verb sense of gå |
| gå ud på (gik, gået) | the idea/point is that | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| gå i vandet (gik, gået) | go swimming | idiom | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| gå til spilde (gik, gået) | be wasted | idiom | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| gå en tur (gik, gået) | go for a walk | idiom | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| komme til at (kom, kommet) | happen to, come to (do something, future/accidental/gradual senses) | idiom | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | book distinguishes future, accidental and gradual-change uses with separate examples |
| komme ud af det med (kom, kommet) | get on well with (each other) | idiom | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| komme sig (kom, kommet) | recover | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| komme med (kom, kommet) | bring along; join in ("kan jeg komme med?") | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| penge | money | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | plural-only in Danish where English can use singular "money" |
| møbler / møbel | furniture / a piece of furniture | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | same singular/plural-mismatch pattern as smykke/smykker |
| værktøj | tools | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | singular-only noun covering English plural "tools", like tøj |
| få øje på (fik, fået) | see, catch sight of | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| bridge | bridge (the card game) | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | English loanword |
| aftale (-te, -t) | arrange, agree | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| nyttig | useful | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| brugsgenstand | article for everyday use | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| salatskål | salad bowl | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| kande | jug | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| kobbergryde | saucepan made of copper | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| gryde | saucepan | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| stormagasin | department store | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| køkkenudstyr | kitchen equipment | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| karaffel | decanter | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| vinglas | wine glass | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| forklæde | apron | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| liggestol | deck chair | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |

### Unit 18: Farvel og på gensyn! — Goodbye, till next time!

| være feberfri | have a normal temperature | idiom | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| det er en skam, at ... | it is a pity that ... | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| ende (-te, -t) | end | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| sådan | like this | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| være til ulejlighed | be a nuisance, cause trouble | idiom | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| Sikke noget pjat! | Nonsense! That's silly! | interjection | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | SLANG/COLLOQUIAL FINDING — dismissive exclamation, listed in "Sådan siger man det" as the way "to express that you think someone is apologising too much"; "pjat" itself = nonsense/silliness, colloquial register |
| hjem | home | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| det kan ikke nytte noget | it is no good (...ing) | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| nytte (-ede, -et) | be of use, help | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| vænne sig til (-ede, -et) | get used to | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| slut | over, finished | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| gå konkurs (gik, gået) | go bankrupt | idiom | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| miste (-ede, -et) | lose | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| arbejdsløs | unemployed | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| være klar over | realise, know | idiom | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| det står dårligt til | things are bad | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| nedgangstid | recession | noun | technical | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| konkurrence | competition | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| skærpe (-ede, -t) | sharpen, tighten, intensify | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| elektronikbranche | electronics industry | noun | technical | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| branche | branch of trade | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| prisfald | fall in price(s) | noun | technical | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| ødelægge (ødelagde, ødelagt) | ruin, destroy | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| profit | profit | noun | technical | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| selskab | company | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| overleve (-ede, -et) | survive | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| uden videre | as a matter of course, just like that | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| afskedige (-ede, -et) | dismiss, sack | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| klare sig (-ede, -et) | manage | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| rent økonomisk | purely financially | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| ansætte (ansatte, ansat) | employ | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| uddannelse | training, education, degree | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| nærmest | almost | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| løn | pay, wage, salary | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| deprimerende | depressing | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| selvmedlidenhed | self-pity | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| føre til (-te, -t) | lead to | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| i årevis | for years | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| beklage sig over (-ede, -et) | complain of | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| alt for | far too | adverb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| dyrke motion | take exercise | idiom | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| motion | exercise | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| lægge om (lagde, lagt) | change, reorganize (one's way of life) | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| kære | dear (letter salutation) | adjective | formal | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| kærlig | loving, affectionate | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | used in letter sign-off "Kærlig hilsen"/"Mange kærlige hilsener" to close relatives/friends |
| hilsen | greeting, regards | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| hjertelig | heartfelt, sincere | adjective | formal | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | used in the less-intimate letter sign-off "Hjertelig hilsen" |
| ansigt | face | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| hår | hair | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | "lyst hår" (singular) = fair hair; "nogle enkelte grå hår" (plural) = a few grey hairs — count/mass contrast explicitly shown |
| pande | forehead | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| øje | eye | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| næse | nose | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| mund | mouth | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| kind | cheek | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| skulder | shoulder | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| arm | arm | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| albue | elbow | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| hånd | hand | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| finger | finger | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| mave | stomach | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| ryg | back | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| ben | leg; also "bone" | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | book explicitly flags the second sense |
| knæ | knee | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| fod | foot | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| tå | toe | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| guld | gold | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| sølv | silver | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| sølvbryllup | silver wedding | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| sølvpapir | foil (lit. "silver paper") | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| bronze | bronze | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| bronzealder | bronze age | noun | technical | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| jern | iron | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| jernbane | railway (lit. "iron track") | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| jernhelbred | an iron constitution | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | metaphorical compound, metal-vocabulary set |
| stål | steel | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| stålværk | a steelworks | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| ståltråd | (steel) wire | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| være færdig med | have finished | idiom | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| være glad for | be fond of; be pleased that | idiom | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| være ked af | be sorry about, be sad about | idiom | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| være længe om | take a long time (to do something) | idiom | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| være nødt til | have to, be obliged to | idiom | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| være i vejen | be wrong, be the matter | idiom | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | "Hvad er der i vejen?" = What is the matter? |
| maskine (flyvemaskine) | machine (aeroplane) | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| pakke | parcel | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| papir | paper | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| forsigtig | cautious, careful, gentle | adjective | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| madlavning | cooking | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| det er synd | it's a pity | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| synd | sin | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| han vil få fornøjelse af gryden | the pan will prove useful to him | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| fornøjelse | pleasure; use | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| Men dog! | I say! | interjection | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | SLANG/COLLOQUIAL FINDING — surprised/mildly-protesting exclamation built on the "dog" modal particle; explicitly glossed "I say!" in the vocab box, p.242 |
| jeg er ikke altid lige nem at være gift med | I'm not always equally easy to be married to | idiom | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | self-deprecating marital-humor idiom, George's farewell-gift line |
| det skal du ikke tænke på | don't worry about that | idiom | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| lige nem | equally easy | phrase | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| sætte pris på (satte, sat) | appreciate, value | verb | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | |
| gensyn | meeting again, reunion | noun | core | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | "på gensyn" = "see you again", title phrase of the unit |
| tak skal I have | thanks to you both | idiom | colloquial | — | contemporary (source published 1994) | — | — | grammar_reference | n/a | verified | plural-address thanks formula ("I" = archaic/formal plural "you") |

## Grammar points

### Pronunciation — Alphabet and vowel length

The Danish alphabet has 29 letters (the 26 Latin letters plus æ, ø, å, alphabetized after z). Danish has nine vowels (a, e, i, o, u, y, æ, ø, å), each with a long and short variant; the short variant is generally more open than the long one. A double consonant generally signals that the preceding vowel is short (mase "grind" vs. masse "mass"); length is tied to stress, so a long vowel shortens when unstressed (læse "read" vs. læse højt "read aloud"). Danish vowels are pure monophthongs, never diphthong-glides the way English vowels often are. (pp. 6-7)

### Pronunciation — Diphthongs

True diphthongs are written as vowel + consonant (usually -g, -j, -v, or -f in the af- prefix), or occasionally as two vowels (au in pause). The first element is pronounced as its normal vowel value; the second element is a reduced i-like or u-like offglide that never reaches a pure /i/ or /u/. Several different spellings can realize the same diphthong sound (e.g. the "ai" sound spelled both -ig and -j: mig, jeg, eje, vej). (p. 8)

### Pronunciation — Consonant system and p/t/k ↔ b/d/g alternation

Danish has 20 consonants; c, q, w, x, z occur only in loanwords. The pairs b-p, d-t, g-k are only distinguished word-initially — medially/finally, k sounds like g (lække "leak" = lægge "lay"), p like b (stoppe "stop" = ebbe "low tide"), t like d (sætte "set" = bredde "width"). The letters p, t, k are also realized as b, d, g after s (spise, stave, skinne). G, in front of unstressed e or word-finally, either combines with the preceding vowel into a diphthong or is silent. H is silent before v and j (hvis, hjem). R's quality varies by position — a back-tongue consonant with little friction at the start of a word/after a consonant, versus a more open, friction-free realization after a vowel, where it also colors the preceding vowel; unstressed -er is pronounced like English "-or" in "mortality." (pp. 8-9)

### Pronunciation — Silent letters and the glottal stop (stød)

In the consonant clusters ld, nd, rd, ds, dt, the d is silent (guld, mand, ord, plads, godt — with exceptions like lærd). The glottal stop (stød) is a distinctive feature of standard Danish (though absent from some dialects), different in mechanism from the English glottal stop that sometimes replaces t (as in "water," "butter"): the Danish stød is an interruption of an already-voiced sound via a narrowing or closing of the vocal cords, producing a brief pause and a small explosive release, e.g. mand [man'] vs. man, mord [mo'r] vs. mor, hund [hun'] vs. hun. The book explicitly says the rules governing which words take the stød are too complex to worry about at an early stage and are best absorbed by imitation. (pp. 10-11)

### Pronunciation — Word stress

Stress usually falls on a word's first syllable; exceptions include many loanwords, words beginning with be-, er-, ge-, for-, and several Danish place names. (p. 11)

### Unit 1 — Noun gender and the indefinite article (en/et)

Danish nouns are either common gender (c) or neuter gender (n); about 75% are common gender, and there are no reliable rules for predicting which — gender must be learned per noun. The indefinite article "a/an" is **en** before a common-gender noun, **et** before a neuter noun (en båd "a boat," et tog "a train"). Most nouns encountered in Unit 1's dialogues are common gender; **et tog** is the unit's only neuter example. (p. 16)

### Unit 1 — Personal pronouns

The subject pronoun set: jeg (I), du/De (you sg. informal/formal), han/hun (he/she), den/det (it, common/neuter), vi (we), I/De (you pl. informal/formal), de (they). De (formal, singular and plural) is spelled with a capital D to distinguish it from de "they." -eg in jeg is pronounced like English "I"; the -t in det is silent; De/de is pronounced with the Danish i-sound. (p. 17)

### Unit 1 — Present tense of "to be": er

Unlike English (am/are/is), Danish "to be" has exactly one present-tense form for every person: **er** (jeg er, du er/De er, han/hun/den/det er, vi er, I er/De er, de er). (p. 17)

### Unit 1 — The present tense in general

Danish present tense is formed by adding **-r** to the infinitive, and — unlike English — the verb form never changes regardless of grammatical person (jeg/du/han/hun/den/det/vi/I/de flyver, all identical). The present tense covers habitual action, action happening right now, and (especially with a time expression like "tomorrow"/"on Sunday") near-future action — a single form doing the job of English's present simple, present continuous, and near-future "going to." (pp. 17-18)

### Unit 1 — skal as a "going to" auxiliary

**Skal** + infinitive expresses a planned/arranged future action ("is/are going to..."): Hun skal bo hos os i en uge ("She is going to stay with us for a week"). After skal, the main verb takes the infinitive form. (p. 18)

### Unit 1 — The infinitive

The infinitive is formed by adding unstressed **-e** to the verb stem. If the one-syllable stem already ends in a stressed vowel, no -e is added (bo "stay/live" stays bo, not *boe), though there are some exceptions. The present-tense -r ending is added to this infinitive form (bo + r = bor; komme + r = kommer). The infinitive of "to be" is irregular: **at være**. (p. 18)

### Unit 1 — Statements and questions (inversion)

A statement becomes a yes/no question by inverting subject and verb (Han kommer fra England → Kommer han fra England?). The answer is ja (yes) or nej (no); but if the question itself is negatively phrased ("Doesn't he live in London?") and the true answer is still affirmative, Danish uses **jo** instead of ja. A question can also be formed with an interrogative word (hvad "what," and others introduced progressively through the book). (p. 19)

### Unit 1 — Possession with -s (no apostrophe)

Danish forms the possessive by adding **-s** directly to the noun, with no apostrophe: min nabos mor ("my neighbour's mother"). (p. 19)

### Unit 2 — The definite article as a suffix

Unlike English "the" as a separate word, Danish attaches definiteness as a suffix: common-gender nouns add **-en** (båd → båden), neuter nouns add **-et** (tog → toget). If a noun already ends in unstressed -e, only **-n** or **-t** is added (rejse → rejsen, uge → ugen). As with plurals, a final consonant after a short stressed vowel is doubled before the suffix (kop → koppen, slot → slottet). The suffix is *not* used when a qualifying word (e.g. an adjective) immediately precedes the noun — that construction is introduced in Unit 5. (p. 28)

### Unit 2 — Object pronouns

The object-pronoun set: mig (me), dig/Dem (you sg. informal/formal), ham (him), hende (her), den/det (it), os (us), jer/Dem (you pl. informal/formal), dem (them). The -ig in mig/dig is pronounced like English "I"; the d in hende is silent. (p. 29)

### Unit 2 — Expressing a wish (vil gerne / vil ikke)

**Vil gerne** ("would like") and **vil ikke** ("don't want to") take an infinitive main verb: Jeg vil gerne have lidt æblekage ("I would like to have a little æblekage"); Jeg vil ikke flyve på mandag ("I don't want to fly on Monday"). (p. 29)

### Unit 2 — Present tense of "to have": har

**Have** is pronounced "ha." Its present tense, like **er**, has only one form across all persons: **har** (jeg har, du/De har, han/hun/den/det har, vi har, I/De har, de har). (p. 30)

### Unit 2 — Negation (ikke)

In a simple main-clause statement, **ikke** ("not") is placed directly after the verb (Hun har en ven i England → Hun har ikke en ven i England). In a construction with **skal** or **vil** + infinitive, ikke goes between the modal and the infinitive (Jeg skal ikke flyve til London på mandag). (p. 30)

### Unit 3 — The three plural patterns, and the definite plural suffix -ne

Danish nouns pluralize three ways: (i) add **-e** (en blomst → blomster), (ii) add **-er** (or just **-r** if the noun already ends in -e), or (iii) take no plural ending at all (en sten → sten, et tog → tog). The definite plural ("the Xs") is formed by adding **-ne** to the plural form regardless of gender (both common and neuter): bådene "the boats," blomsterne "the flowers." If the plural itself has no overt ending, an extra linking **-e-** is inserted before -ne (tog → togene "the trains"). (p. 38)

### Unit 3 — Adjective agreement

After the indefinite article en/et, an adjective takes no extra ending with a common-gender noun, but adds **-t** with a neuter noun (en rød blomst "a red flower" vs. et rødt bord "a red table"). In the plural, adjectives add **-e** regardless of gender (røde blomster, røde borde). When an adjective follows the noun via a form of "to be" (predicative position, e.g. "the rose is red"), it still inflects the same way: Buketten er billig / Bordet er dyrt / Blomsterne er billige. A final consonant after a short stressed vowel doubles before -e (turisterne er trætte). The adjective **lille** ("small") is irregular: it adds no -t for neuter (et lille bord), is singular-only, and is replaced by **små** in the plural — and små itself does not take the regular plural -e ending despite being a plural form. (p. 39)

### Unit 3 — Word order and inversion (expanded)

Danish inverts subject and verb (a) in any main clause that does not open with its own subject (Så dækker jeg bord i mellemtiden — "then shall-I lay the table," lit.), (b) in a main clause that follows a subordinate clause (Hvis solen skinner i eftermiddag, kan vi køre op til Dyrehaven — "if the sun shines..., can we drive..."), and (c) in questions (Bor Hans i Holte?). A main clause is a complete statement containing a subject and verb; a subordinate clause (e.g. "when I come tomorrow") only makes sense attached to a main clause. (pp. 38-39)

### Unit 3 — Possessive pronouns (full paradigm)

Singular "my": min/mit/mine agreeing with the noun's gender/number (min nabo, mit slot, mine venner). Singular "your" (informal): din/dit/dine, same agreement pattern. Third-person singular possessives have two competing forms depending on grammatical relationship: **hans** (his) and **hendes** (her) show no agreement and are used when the possessor is *not* the clause's own subject; but when the subject himself/herself is the possessor, Danish instead uses the reflexive **sin/sit/sine** (agreeing with the possessed noun) — Han hjælper sin mor ("He helps his own mother") vs. Han hjælper hans mor (helping *someone else's* mother). "Its" is **dens** (common gender referent) or **dets** (neuter referent), or sin/sit/sine under the same reflexive condition. Plural possessives show no agreement at all: **vores** (our), **jeres** (your pl.), **deres** (their). The formal "your," **Deres**, likewise shows no agreement in either number. (pp. 40-41)

### Unit 3 — Noun-noun juxtaposition for quantities ("en flaske vin")

Where English inserts "of" (a bottle *of* wine), Danish simply places the two nouns in sequence with no linking word: en flaske vin, en liter mælk, en kop kaffe. (p. 41)

### Unit 4 — Past tense: two regular (weak) conjugation classes

Group (a): the past tense is formed by adding **-ede** or **-te** to the verb stem (ringe→ringede, koste→kostede, bo→boede, tale→talte, spise→spiste, trænge→trængte); no rule predicts which of the two endings a given verb takes — this must be learned per verb (the book indicates it in brackets in its end glossary). Group (b): no ending is added in the past tense; instead the tense is shown by an internal vowel change (hjælpe→hjalp, drikke→drak, være→var), analogous to English strong verbs (drink/drank). A few verbs in this second group change with no vowel shift visible in spelling (hedde→hed, komme→kom). A third, irregular class takes an ending (-de or -te) *and* usually an internal change (sige→sagde, gøre→gjorde, have→havde). (pp. 50-51)

### Unit 4 — Present perfect vs. past tense

Danish uses the present perfect (har + past participle, e.g. hun har ringet "she has telephoned") much like English: the past tense names a specific prior time and stresses that the action was completed then (hun ringede klokken halv 1 "she rang at half past twelve"), while the perfect tense connects a past action's *result* to the present moment. (p. 50)

### Unit 4 — Question words, including the colloquial "hvad for en/et/nogen"

Core interrogatives: hvad (what), hvordan (how), hvornår (when), hvem (who), hvis (whose), hvilken/hvilket/hvilke (which, agreeing with the noun's gender/number). **The book explicitly flags that, colloquially, people substitute hvad for en / hvad for et / hvad for nogen for hvilken/hvilket/hvilke** (Hvad for en buket vil du have? "Which bouquet would you like?") — an explicit register note distinguishing the grammatically "correct" interrogative from the everyday spoken alternative. (pp. 52-53)

### Unit 4 — Numerals 20-100 (vigesimal halv- system)

From 50 upward, Danish numerals are historically vigesimal (base-20) and count in half-units of twenty: halvtreds (50) is a contraction of halvtredsindstyve, literally "half-third times twenty" (i.e. two-and-a-half twenties = 50, since halvtredje = "two and a half"); tres (60) = three times twenty; halvfjerds (70) = three-and-a-half (halvfjerde) times twenty; firs (80) = four times twenty; halvfems (90) = four-and-a-half (halvfemte) times twenty. The book notes the fully spelled-out halv- forms (halvtredsindstyve etc.) are now outdated/archaic; only the contracted forms (halvtreds, tres, halvfjerds, firs, halvfems) are in everyday use. As with the teens, the last digit is spoken first in compounds: 21 is enogtyve ("one-and-twenty"), 35 is femogtredive, up through three-digit numbers (109 = (et) hundrede (og) ni). (pp. 52-53)

### Unit 4 — Telling the time

"What's the time?" is Hvad er klokken?; "it is X o'clock" is Klokken er X. "Past" the hour is **over**; "a quarter" is et kvarter or kvart (kvart over 8 = quarter past 8). "To" the hour is **i** (kvart i 9 = quarter to 9). Crucially, Danish half-hour expressions relate to the *following* hour, not the one just passed: "half past 10" is halv 11 (literally "half eleven"). Minutes 1-20 past the hour, and 1-20 to the next hour, are expressed directly with over/i; the window of minutes 21-29 past the hour is instead expressed as minutes *before* the half-hour (25 past 10 = 5 minutter i halv 11, lit. "5 minutes to half-11"), and minutes 31-39 past the half-hour as minutes *after* it (8 minutter over halv 11 = 22 minutes to 11). Official/transport time (arrivals, departures) uses the 24-hour clock read digit-group by digit-group, e.g. 15.03 = femten nul tre, 21.17 = enogtyve sytten. (pp. 49-50)

### Unit 4 — Omission of the movement verb after skal

When skal is followed by an expression of movement/direction, the verb of motion itself can be omitted, with travel implied by context: Alison skal med toget ned til London (lit. "Alison shall with the train down to London," i.e. "...is going...by train..."). (p. 48)

### Unit 5 — Sankthansaften (cultural note)

Sankthansaften (St. John's Eve, 23 June) is described as the eve of an old saint's day on which an ancient pagan ritual (lighting bonfires) still continues nationwide. The dialogue's sung excerpt (lines by Holger Drachmann, from the song traditionally sung at Danish Midsummer bonfires) is given with its own English paraphrase in the source; it describes lighting bonfires on ancestors' burial mounds to drive off witches and trolls from every town/parish, p.60-61.

### Unit 5 — Kronborg Slot (cultural/historical note)

Kronborg Slot (the Castle of Elsinore) sits where the sound between Denmark and Sweden narrows most. Built in the first half of the 15th century by Danish king Erik of Pomerania when he introduced the Sound Dues (a toll on ships passing Elsinore); he built several castles on both sides of the Sound to enforce payment. The castle has provided the setting for many productions of Shakespeare's *Hamlet*, p.62.

### Unit 5 — synes, tro, tænke ("think")

Three verbs all translate "think" but carry different degrees of certainty: **jeg synes** introduces a personal opinion/judgment; **jeg tror** implies a belief the speaker isn't fully certain of; **jeg tænker** is used for "I think of/about" (ongoing mental attention), p.62.

### Unit 5 — først ("first" or "not until")

**Først** means "first" in a sequence (spise frokost først) but can also mean "not until" (festen begynder først klokken 6 = the party does not start until 6 o'clock), p.62, 65.

### Unit 5 — The word "the" and adjectives

Danish "the" is normally a suffix (-en/-n on common-gender singular nouns, -et/-t on neuter singular, -ne on plurals). But when an adjective sits between the article and the noun, "the" becomes a separate word (den/det/de) instead of a suffix, and the adjective takes an -e ending (den røde blomst, det gule hus, de røde blomster/gule huse), p.63-64.

### Unit 5 — Adjective -e-dropping and vowel-change rules

Adjectives ending in -el, -en, -er drop the e when adding the -e ending (sulten + e = sultne; a preceding double consonant is simplified: gammel + e = gamle). Most one-syllable adjectives ending in a vowel do not add -e at all (blå, små: et blåt hav, det blå hav, små huse), p.64.

### Unit 5 — Plural of nouns

Most nouns ending in -el, -en, -er drop the e before the plural ending (sommer→somre, himmel→himle, with simplification of a preceding double consonant). Nouns for professions/nationalities ending in -er keep the e in the plural (bager→bagere, englænder→englændere) but the plural ending itself disappears before the definite article (bagere→bagerne). **Menneske** ("person") has an irregular plural in -r (mennesker) that loses the -r before the definite ending -ne (menneskene). A few nouns show a vowel change in the plural: datter→døtre, hovedstad→hovedstæder, p.64.

### Unit 5 — Position of "ikke"/"altid"-type adverbs in a main clause

Adverbs meaning *not, never, always, often, seldom, only, soon, probably* are placed immediately after the verb in a main clause — or, if the verb is a perfect-tense auxiliary + past participle, immediately after the auxiliary (jeg har ikke købt billetterne). With modal verbs (skal/vil/må/kan) + infinitive, such adverbs go between the modal and the infinitive (han vil bare se huset), p.64-65.

### Unit 5 — Prepositions in time expressions

A set-phrase list of Danish time expressions is given (i dag, i morgen, i næste uge, i morges, i eftermiddag, i aften, i mellemtiden, i løbet af formiddagen, på mandag [future], i en uge, om et kvarter, midt på dagen, sidst på eftermiddagen, for tiden) illustrating that Danish prepositions for time don't map predictably onto English ones, p.65.

---

### Unit 6 — Position of ikke/altid-type adverbs in a subordinate clause

Unlike in a main clause (where such adverbs follow the verb/auxiliary), in a subordinate clause these adverbs are placed *before* the verb(s), immediately after the subject (e.g. Hvis hun **ikke** har set filmen...; Fordi jeg **ikke** kunne tale dansk...), p.88-89.

### Unit 6 — Demonstrative pronouns

Den/det/de = this/that/these/those with a definite-form noun (den gade, det hus, de blomster); neuter singular is dette, plural is disse. In the spoken language these tend to be replaced by informal alternatives using her ("this... here": den gade her) or der ("that... there": den gade der), p.88. The noun a relative clause defines is often preceded by den/det/de rather than put in the ordinary definite form (det år, du tilbragte i Danmark), p.88.

### Unit 6 — Modal verbs (kunne, måtte, skulle, ville)

Four modal-verb paradigms are given with principal parts and core meanings:
- **kunne/kan** (kunne, kunnet) — possibility or capability ("can")
- **måtte/må** (måtte, måttet) — necessity ("must"); **må ikke** = "must not"
- **skulle/skal** (skulle, skullet) — plans/arrangements, obligation imposed by a rule/law/order, or sometimes simply future tense; used in suggestions
- **ville/vil** (ville, villet) — wanting/intending to do something; **vil gerne** = "would like to"
Fuller treatment promised in Unit 13 (outside this chunk's range), p.89-90.

### Unit 7 — How to translate "know": vide vs. kende

Danish distinguishes two verbs for "know." **Vide** (ved, vidste, vidst) is used when what is known/not known is expressed by a clause (Jeg ved, at hun kommer på fredag) or by "det" (Det ved jeg). **Kende** (kendte, kendt) is used when the grammatical object is a person, a specific thing, or a place (Jeg kender ham ikke; Kender du nogen gode hoteller i Kolding?), p.85-86.

### Unit 7 — How to translate "when": når, da, hvornår

**Når** corresponds to "whenever" and is used for habitual/repeated past actions or for future events, with present or past tense verbs. **Da** is used for a single, completed event in the past. **Hvornår** introduces a question ("when?"), p.86.

### Unit 7 — The Danish word "der" (relative connector and dummy subject)

Besides its relative-clause use (see Unit 6), **der** functions as an adverb of place ("there") and very commonly as a dummy/existential subject introducing a sentence whose real subject is indefinite (Der afgår Inter City tog fra København hver time; Der står en mand derhenne på hjørnet; Der afgår et tog 15.34) — a construction with no exact single-word English equivalent ("there is/are... departing/standing"), p.87.

### Unit 7 — Modal verbs continued (kan, må, skal, vil)

This unit's own Grammatik section gives the fullest treatment in the assigned range: **kan** = possible/capable (Jeg kan flyve...; Jeg kan godt spise lidt mere); **må** = necessary (Det må I undskylde); **må ikke** = "must not"; **skal** = plans/arrangements (Hun skal bo hos os...), obligation from order/law/regulation (Man skal have pladsbillet...), suggestions, or simple future; **vil** = want/intend (Han vil gøre det; Han vil gerne gøre det = "would like to"; Han vil ikke gøre det = "won't"), p.88-90.

### Unit 7 — FLAGGED: discourse particle "jo"

Explicit grammar-box note: **jo**, inserted into a statement, "implies that the listeners are well aware of the truth of what is being said" — used by a speaker to frame a claim as self-evident or already shared common ground with the addressee (Det er **jo** ikke nogen helt almindelig chokolade; Det er **jo** meget vigtigt nu...), p.84, 87.

### Unit 8 — FLAGGED: Danish discourse particles nok, da, dog, jo, nu (the "unstressed adverbs" passage)

This is the single most directly relevant grammar-logic passage in this chunk for the project's slang/pragmatics tracking. The source states explicitly (paraphrased, p.98-99): **"Colloquial Danish uses a number of unstressed adverbs which add an implied other meaning to the literal meaning of the sentence. The inclusion of nok, da, dog, jo or nu (etc.) in a factual statement conveys a subjective reaction to the previous line in a dialogue."** The book gives a worked example contrasting **da**'s two senses: as a neutral temporal conjunction ("when," single past event — see Unit 6-7 above) versus its discourse-particle use, where **da inserted into an otherwise neutral piece of information could signal that the speaker disagrees with what has just been said**. **Nok** is independently illustrated across two dialogues as a softening/reassurance particle roughly meaning "probably" or "I'm sure" (De står **nok** og venter på bagagen = "They are *probably* waiting for their baggage"; Jeg skal **nok** være færdig = "I shall *definitely* (I promise to) be ready"). **Jo** is cross-referenced to its own fuller note (Unit 7, above). **Dog** and **nu** are named in the same list but not individually glossed with worked examples within this chunk's page range — the source states a fuller treatment follows in **Unit 16** (outside this dispatch's assigned range, p.32-64 / printed pp.58-123). **All five particles (nok, da, dog, jo, nu) are tagged `colloquial` in the Usage Tier column above**, since the source itself frames this entire phenomenon as a feature of "colloquial Danish."

### Unit 8 — The Danish word "så"

**Så** is multi-sense: before an adjective/adverb it means "so" (Det smager så godt); at the start of a main clause it means "then"/"in that case" and triggers verb-subject inversion (Så dækker jeg bord...); it can also mean "so, therefore" or "so that," introducing a subordinate clause (Jeg vil leje en bil i Århus, så vi kan køre til Mols — ambiguous between "so I'll hire a car... for that reason we can drive..." and "I'll hire a car... so that we can drive..."), p.99.

### Unit 8 — How to translate "need": trænge til, have brug for, være nødt til

Three near-synonyms are distinguished: **trænge til** is used when something needs to be put right/corrected (a worn coat, a broken watch, needing a walk after sitting too long); **have brug for** is used when a need arises from external circumstances (needing a new coat for a wedding, needing a car because public transport won't do); **være nødt til** (+ at-infinitive, or "det" alone) means "I am forced to," i.e. "need to" in the sense of compulsion (Jeg er nødt til at rejse herover igen), p.98-99.

### Unit 8 — Comparison of adjectives

Regular pattern: add **-ere**/**-est** (fin→finere→finest). Adjectives in **-ig** add only **-st** in the superlative (billig→billigere→billigst). Some adjectives show a vowel change (stor→større→størst; lang→længere→længst). A handful are irregular: gammel→ældre→ældst; god→bedre→bedst; lille→mindre→mindst; meget→mere→mest; mange→flere→flest. Adjectives of three+ syllables (except those ending -lig), and those ending -sk/-et/unstressed -e, generally use periphrastic **mere/mest** instead of endings; adjectives in -el/-en/-er drop the -e before comparative/superlative endings but often use mere/mest instead because of awkward pronunciation (lækker→lækrere/mere lækker→lækrest; sulten→mere sulten→mest sulten). The comparative -ere ending never agrees with the noun; a superlative qualifying a definite-form noun ends in -e (det dejligste sommerhus), p.100-102.

### Unit 8 — Adjectives ending in -et and -sk

When -e is added to an adjective ending in -et (forsinket, udmærket), the -t becomes -d- (det forsinkede tog). Adjectives ending in -sk (politisk, engelsk, dansk) do not add -t when qualifying a neuter noun in the indefinite singular (et engelsk tog), p.102.

### Unit 8 — Nogen, noget, nogle/nogen

These indefinite forms serve as both adjective and pronoun. **Nogen** (common gender singular) = somebody/anybody/some/any, and also serves as the plural "any" (Der kom ikke nogen danskere). **Noget** (neuter singular) = something/anything/some/any, and is also used quantitatively for "some, a little" before both genders (Vil du have noget mælk?). **Nogle** (plural, "some") is pronounced identically to nogen but spelled differently — the written form is the only way to distinguish "some" from "any" in the plural, p.102-103.

### Unit 8 — The missing indefinite article

Danish omits the indefinite article when stating nationality (Hun er dansker = "She is a Dane") or occupation (Han er bager = "He is a baker"), p.103.

### Unit 9 — FLAGGED cultural note: Molbohistorier (regional outsider-mockery narrative)

Direct relevance to the project's taboo/outsider-mockery naming mechanics, as anticipated. The source's own Ordforklaringer note (p.113, paraphrased): Mols was historically an isolated part of Denmark; two hundred years ago its only connection to Århus was by boat, and when the peasants occasionally turned up in Århus speaking their strange dialect, they became an object of ridicule. The townspeople invented stories about the Molbos' supposed stupidity; these stories (**molbohistorier**, "Molbo stories") were later recorded as a folk-tale genre. The Andre tekster section (p.121) then gives an actual specimen tale ("En molbohistorie"), paraphrased here per copyright discipline: during a war, the Molbos feared the enemy would steal their church bell, so they took it down from the tower and sailed out to sea to sink/hide it on the sea floor; one of them asked how they'd find it again after the war, and another answered it was no problem — they would simply cut a mark into the side of the boat at the spot where they threw it overboard. This is a textbook-explicit, named example of a real-world linguistic-prejudice mechanism (an outsider dialect group mocked via invented stupidity-narratives tied to their speech) — directly usable as a model for taboo/outsider-naming slang-derivation mechanics in this project's synthesis phase. No individual Mols-dialect word forms are given by the source (the "strange dialect" is described narratively, not lexically), so no vocabulary row has been tagged `regional` on this basis alone; only "hedebakker" above is tagged `regional` for its Mols-specific-terrain sense, not for any dialect-form reason.

### Unit 9 — How to translate "grow": dyrke vs. vokse

Danish distinguishes grow/cultivate (**dyrke**: Alison dyrker en masse frugt) from grow/become bigger (**vokse**: Grønsagerne vokser hurtigt i det gode vejr; perfect tense er vokset), p.113.

### Unit 9 — How to translate "very" before an adjective, in the negative

**Meget** ("very") cannot be used in a negative statement; instead **ikke** is followed by **særlig** or **ret** (Han er ikke særlig sulten; Han er ikke ret sulten), p.113-114.

### Unit 9 — How to translate "if": hvis vs. om

**Hvis** introduces a conditional clause ("if" = "in the event that"). **Om** introduces an indirect question where "if" could be replaced by "whether" (Jeg ved ikke, om de kan tale engelsk). **Hvis** is also an interrogative pronoun meaning "whose" (Hvis datter rejste til London?), p.114.

### Unit 9 — North, south, east, west

A systematic compass vocabulary set is given, each direction with four forms: the bare direction (nord), "-fra" ("from the north" = nordfra), "-på" ("northwards" = nordpå), and "... for" ("north of" = nord for), repeated for syd, øst, vest, p.114.

### Unit 9 — Adverbs and adverbs of place (two-form system)

Adjectives become adverbs via a **-t** ending (smuk→smukt: Hun er smuk / Hun synger smukt). Separately, many Danish adverbs of place have two distinct forms depending on whether movement or location/locality is meant: a "movement" form (ind, ud, op, ned, over, hen, hjem) versus a "location" form (inde, ude, oppe, nede, ovre, henne, hjemme) — e.g. **derover** (movement, "over there") vs. **derovre** (locality, "over there"). The prefixes **der-** and **her-** can be added to any of these pairs to indicate the speaker's position relative to the place (derovre/herovre, etc.), p.116-117.

### Unit 9 — Simplification of double consonant in verbs

If a double consonant precedes the infinitive ending -e of a regular -te-type verb, the consonant is simplified before the past-tense ending: glemme→glemte; bestemme→bestemte, p.117.

### Unit 9 — The passive voice

Intransitive verbs (no grammatical object: flows, arrive, grow) are distinguished from transitive verbs (has an object: washes the dishes, collects the tickets), which can be active or passive. Danish forms the passive either with an **-s** ending on the verb (infinitive or present tense: billetterne skal **afhentes**; et menneskes personlighed... som vi **fødes** med) or periphrastically with the auxiliary **blive** (not være) + past participle — unlike English, which always uses "to be" + past participle. Fuller treatment promised in Unit 15 (outside this chunk's range), p.116-118.

---


- **Range covered**: PDF pages 32-64 (rendered at 150 dpi), confirmed via direct inspection to correspond to printed pages 58-123 — matching the stated formula (printed pages 2N-6 / 2N-5 for PDF page N) exactly on the first sample page (PDF p.32 → printed pp.58-59). Printed page numbers were also spot-checked at several points through the range and increase monotonically with no evidence of the spread-pagination or non-monotonic-ordering gotchas documented elsewhere in this project.
- **Units covered**: 5 (Weekend i Nordsjælland, pp.58-67), 6 (Med toget til Jylland, pp.69-81), 7 (Til forretningsmøde, pp.82-94), 8 (På hotellet, pp.95-108), 9 (I sommerhus på Mols, pp.109-123). Unit 10 (På bord på færgen) begins at printed p.124 / PDF page 65, outside this assignment.
- **Vision-reading guard**: every one of the 33 rendered page-spreads was visually inspected before extraction. **No handwritten marginalia, pencil notes, underlining, or filled-in exercise answers were found anywhere in this range** — the entire scan is clean, typeset, machine-printed text throughout. No content was excluded on marginalia grounds.
- **Skipped as drill/redundant per the coverage rule**: Rigtigt eller forkert (true/false comprehension) sections throughout; Øvelser (exercise) sections' fill-in-the-blank/translation/transformation items that only recombine already-captured vocabulary and grammar; the repeated "Sådan siger man det" phrase lists that merely re-quote dialogue sentences already captured verbatim elsewhere on the same spread.
- **Copyright discipline**: the Unit 5 folk-song excerpt (sankthansaften verse) and the Unit 9 "En molbohistorie" folk tale are both summarized/paraphrased rather than block-quoted, consistent with the spec's selective-quote-and-paraphrase rule; the source's own English prose summaries (already short) were used as the basis for the paraphrase rather than reproducing the full Danish verse/tale text.

### Unit 10 — Man, en, ens

The word **man** ("one") is used far more frequently in Danish than "one" in English, where it tends to be replaced by "you" or "they" (*man siger, at...* = "they say that..."). Danish also uses an active construction with **man** as subject where English prefers a passive (*man ved, at han er...* = "he is known to be..."). The object form is **en** (*man kan ikke vente, at de tilbyder at hjælpe en* = "you/one cannot expect them to offer to help you/one"), and the possessive form is **ens** (*når ens børn kommer sent hjem* = "when one's children come home late"). If *one* is the subject of the sentence, "one's" instead becomes **sin/sit/sine** (*man vil selvfølgelig hjælpe sine børn* = "one naturally wants to help one's children").

### Unit 10 — 'The' with clothing and parts of the body

Where English uses a possessive pronoun (*his, her*) before a noun denoting clothing or a body part, Danish uses the definite form of the noun instead: *han lagde jakken* = "he took off his jacket"; *han rystede på hovedet* = "he shook his head."

### Unit 10 — Anden, andet, andre

These words mean "other," as in *en anden bil* ("another car"), *et andet værelse* ("another room"), *andre mennesker* ("other people"); *de andre* ("the others") is a pronoun use. The definite singular form does not end in -e (*den anden bil, det andet værelse*). **Anden/andet** also serves as the ordinal "second" — *den anden by* means either "the second town" or "the other town," and *det andet barn* either "the second child" or "the other child."

### Unit 10 — Compound nouns

Danish compound nouns are written as one word (unlike English), e.g. *kirkeklokke* "church bell," *chokoladefabrik* "chocolate factory." The **last** component of the compound determines the gender and plural ending of the whole word (*en kirkeklokke → kirkeklokker*); the first component is unchanged. **Barnebarn** ("grandchild") is a named exception: its plural is *børnebørn*, not *barnebørn*.

### Unit 10 — The perfect tense with 'er'

The auxiliary verb in the perfect tense is not always **har**. **Er** is used with verbs of movement and verbs implying "change," e.g. *afgå* (er afgået), *ankomme* (er ankommet), *begynde* (er begyndt), *blive* (er blevet), *dreje* intrans. (er drejet), *falde i søvn* (er faldet i søvn), *gå* (er gået), *holde op* (er holdt op), *komme* (er kommet), *køre* (er kørt), *lande* (er landet), *lykkes* (er lykkedes), *rejse* (er rejst), *tage* "go" (er taget), *vokse* (er vokset). If a verb of movement implies *prolonged* action, however, the auxiliary reverts to **har**: compare *han har rejst meget i de senere år* ("he has travelled a lot in recent years," ongoing/habitual) with *han er rejst til Sverige* ("he has gone to Sweden," a completed change of location).

### Unit 11 — Ordinal numbers (1st-39th)

Ordinal numbers run første, anden, tredje, fjerde, femte, sjette, syvende, ottende, niende, tiende, ellevte, tolvte, trettende, fjortende, femtende, sekstende, syttende, attende, nittende, tyvende, enogtyvende (21st) ... tyveogtyvende... niogtyvende (29th), tredivte/tredvte (30th), ... niogtredivte/niogtredvte (39th). Ordinal numbers do not change except **anden** (den anden sag / det andet tog — "the second matter/train"). The combination **-ek-** in "sekstende" is pronounced like English "I." Unlike English (which adds letters: *2nd*), Danish puts a full stop after the figure (*d. 2. juli*), and no preposition precedes a date (*han kom den 29. juni* = "he came on the 29th of June").

### Unit 11 — The cardinal numbers above 99

**Hundrede** and **tusind(e)** are neuter nouns; the plural ending is -r, used in expressions like *hundreder af børn* ("hundreds of children") — but after a numeral, no plural ending is added (*tre hundrede* = 300). **Million** and **milliard** are common-gender nouns whose plural -er is used after numerals (*to millioner* = 2,000,000). Where English uses a comma, Danish uses a full stop, and vice versa (English 37.5 = Danish 37,5). Decade names use a plural-article pattern: *i halvtredserne* ("in the fifties"), *han er sidst i tresserne* ("he is in his late sixties"), *i begyndelsen af halvfjerdserne* ("in the early seventies").

### Unit 11 — More about adjectives

Adjectives ending in **-s** do not change at all (*stakkels, anderledes* — *de stakkels forældre*). **Gæstfri** adds -t in the indefinite neuter form; in the plural it may optionally add -e (*de var utrolig gæstfri(e)*).

### Unit 12 — More about relative clauses

When a relative clause relates to the whole of the main clause rather than defining a single noun in it, the relative pronoun is **hvad** (not der/som). If *which* is the subject of such a clause, **hvad** is followed by **der**; if it is the object, **hvad** alone is used (*han fik mange ordrer, hvad der gjorde ham glad*). **Hvilket** can also translate "which" in this construction but is formal, written-only register; many speakers avoid the construction altogether, preferring two main clauses joined by **og** (*han fik mange ordrer, og det gjorde ham glad*). If an antecedent is defined by two relative clauses joined by "and," the second relative pronoun is always **som**, regardless of whether it is subject or object of its clause. The relative pronoun "whose" is **hvis** (*min nabo, hvis datter bor i Amerika...*).

### Unit 12 — More about the past and perfect tenses

Danish verbs fall into three groups: (a) verbs adding -ede or -te in the past tense; (b) verbs that add no ending but usually show tense by a vowel change (e.g. *blive/blev/blevet, drikke/drak/drukket, finde/fandt/fundet, byde/bød/budt, nyde/nød/nydt, hedde/hed/heddet, sove/sov/sovet*); (c) irregular verbs with a past-tense ending (-de or -te) that in most cases also show a different vowel in the past tense and past participle than in the infinitive (e.g. *gøre/gjorde/gjort, sige/sagde/sagt, sælge/solgte/solgt, vide/vidste/vidst, vælge/valgte/valgt*). **Vidste/vidst** are noted as irregular within group (c): they carry an -s- because they are not original forms of the verb — the present tense **ved** is historically the *old past tense*, and when that shifted to become the present tense, a new past tense (*vidste*) had to be created from it.

### Unit 12 — The present participle

The Danish present participle (English -ing) is formed by adding **-ende** to the verb stem (*rejse→rejsende, komme→kommende, gå→gående*). Its use is far more restricted than in English: it is **never** used to form a continuous present tense (English "they are enjoying their holiday" is simply *de nyder deres ferie* in the present tense) and never introduces a participial clause the way English "Entering the room he saw..." does — Danish instead uses a full subordinate clause (*da han gik ind i værelset, så han...*). It is also not used after verbs of perception (see/hear/notice) the way English uses -ing — Danish uses the plain infinitive instead (*jeg så dem gå rundt om hjørnet* = "I saw them walking round the corner"). Its main use in Danish is as an **adjective** (*en irriterende larm, en lovende elev, et forsvindende håb*) — and when used adjectivally it never takes an ending, even on an otherwise-inflecting noun (*et forsvindende håb*, not *-ende-t*). It is also used after the verb **blive** to mean "remain Xing" (*bliv endelig siddende!* = "do stay!" lit. "remain sitting"; *vi blev boende i Århus* = "we stayed [remained staying] in Århus"). The compound noun **ferierejsende** ("holiday-maker") is built from the present participle of *rejse* but functions grammatically as a noun; its definite form is made via the article (*de ferierejsende*), not by inflection.

### Unit 12 — More about the comparison of adjectives

Beyond the already-known vowel-changing comparatives (*stor/større/størst, lang/længere/længst*), this pattern also covers **ung/yngre/yngst** ("young/younger/youngest") and **få/færre/færrest** ("few/fewer/fewest").

### Unit 13 — More about modal verbs

Danish has six modal verbs: **kunne, skulle, ville, burde, turde, måtte**. Their infinitive form is identical to the past tense; the past participle is formed by adding -t to the past tense (*kunnet, skullet, villet, burdet, turdet, måttet*). The present-tense forms are **kan, skal, vil, bør, tør, må**, corresponding to English *can, shall, will, ought to, dare, must/may* — though (apart from "dare") the English modals don't exist in all the forms Danish ones do. (a) **Kan** = can/may, conveying ability or possibility (*han kan køre os ned til færgen*). (b) **Må** covers both "must" and "may"; in the sense of "may" it is usually followed by *gerne* or *godt* (*I må gerne komme i morgen*), and in questions *gerne/godt* is dropped (*Må jeg komme ind?* = "May I come in?"); the necessity sense of **må** often arises from an accident/sudden illness context; **må ikke** expresses a prohibition (*du må ikke sige noget til din søster*). (c) **Skal** implies a different kind of necessity — one due to an external order, office routine, or timetable (*jeg skal være på arbejde klokken 7*) — and can also issue an order (*du skal skrive stilen*) or imply a promise (*jeg skal nok gøre det* = "I'll certainly do that"). It is also used for plans/arrangements and sometimes simply the future. (d) **Vil** implies wish or future (*de vil rejse med toget; vi vil gerne hjælpe dig*). (e) **Bør** implies duty/propriety (*du bør gøre, hvad dine forældre siger*; *han burde gøre det* = "he is likely not to"). (f) **Tør** implies courage (*jeg tør godt gøre det* = "I am not afraid to do it"; *gør det, hvis du tør* = "I dare you to do it").

### Unit 13 — More about the present participle

The present participle can follow the verbs **finde, have, komme** (beyond *blive*, see Unit 12): *jeg fandt hende siddende bag et træ* ("I found her sitting behind a tree"); *vi kan ikke have dem boende* ("we cannot have them staying"); *de kom løbende ind i stuen* ("they came running into the room").

### Unit 13 — Nouns ending in '-um'

When an ending is added to a noun of this class, it drops the **-um**: *et museum → museet, museer, museerne*; *et studium → studiet, studier, studierne*.

### Unit 13 — Adjectives (continued)

The adjective **(u)tilfreds** ("(dis)satisfied") does not add -t in the indefinite neuter singular (*et tilfreds menneske*), but does end in -e in the definite form and plural (*de tilfredse kunder*). Some adjectives ending in **-d** likewise don't add -t in the neuter (*et glad barn, et fremmed fly*), but do end in -e in the plural (*glade børn, fremmede fly*).

### Unit 13 — The adjective 'own'

**Egen, eget, egne** ("own") is an exception to the general rule that adjectives ending in a stressed vowel don't change (*min egen datter, mit eget hus, mine egne bøger*).

### Unit 14 — No, nobody, nothing

**Ingen** is both the plural and the common-gender singular form of the adjective "no" (*jeg har ingen timer om onsdagen*); the neuter singular form is **intet** (*han havde intet slips på*). In practice, **ingen/intet** tend to be replaced in speech by **ikke nogen/ikke noget** (*jeg har ikke nogen timer; han havde ikke noget slips på*). **Ingen** also functions as the pronoun "nobody" (*der var ingen hjemme*); **ingenting** has replaced **intet** as the pronoun "nothing" (*han sagde ingenting*) — and both pronouns likewise tend to be replaced in speech by **ikke nogen/ikke noget**.

### Unit 14 — Adjectives: special cases

(a) Most adjectives ending in a stressed vowel are unchanged in the definite form and plural (*den blå stol, små børn*); **ny** and **fri** may optionally add -e (*de ny(e) bukser*), the two forms being interchangeable. (b) Adjectives ending in an unstressed -e never change (*et lille hus, den følgende dag*). (c) Adjectives ending in **-sk** don't add -t in the indefinite neuter singular (*et politisk spørgsmål, et udmærket svar*) — as is also true, since a final consonant is never doubled in Danish, of adjectives ending in -t, and of a few ending in -d (*glad, fremmed*: *et glad menneske*). (d) Most adjectives ending in **-s** don't change at all (*det stakkels barn, et tilfreds menneske*) — but note *de tilfredse kunder* in the plural, since -s-ending and tilfreds-type behavior differ. (e) When -e is added to an adjective ending in **-et/-t**, the -t becomes **-d-** (*forsinket → det forsinkede tog; friskplukket → de friskplukkede hindbær*). (f) The adjective **værd** ("worth, worthwhile") never changes (*slottene er et besøg værd*).

### Unit 14 — The definite form of the adjective (after possessives)

The definite form of the adjective is also used after possessive pronouns, demonstrative pronouns, and a noun in the possessive: *min gamle onkel* ("my old uncle"), *dette svære spørgsmål* ("this difficult question"), *børnenes lange ferie* ("the children's long holiday").

### Unit 14 — Expressing likes and dislikes

Danish has a cluster of distinct expressions for "like"/"dislike," each with its own idiomatic government: **kunne lide** (*jeg kan godt lide en øl til maden*; comparative *jeg kan bedre lide kaffe end te*; intensified *jeg kan mægtig/vældig/rigtig godt lide ham*); **holde af** (*han holder meget af sine børn*; comparative with *mere/end*: *han holder mere af sin hund end af sin kone*); **synes om** (*synes du om dem?*; *jeg er begyndt at synes bedre om hende*); **elske** (*de elsker hinanden; hun elsker ham højt*); **bryde sig om** (*bryder du dig om ham?* — used in the negative for dislike: *Alison bryder sig ikke om hummer*). Dislike can also be expressed with **kan ikke lide**, **ikke holde af**, **ikke elske**, or **ikke synes om**.

### Unit 14 — How to translate 'to have'

When *have* means "possess," Danish uses **have** (*de har et sommerhus på Mols*). When it means "get/obtain," Danish uses **få** instead (*kan jeg få et glas vin?*; *har I fået nogen kartofler?*).

### Unit 14 — Vel and ikke at the end of questions

A **negative** question is followed by the tag **vel** (*de kommer ikke, vel?* = "they aren't coming, are they?"); a **positive** question is followed by the tag **ikke** (*de kommer da, ikke?* = "they are coming, aren't they?").

### Unit 15 — The passive voice

The book reviews (building on Unit 9) that Danish, like English, can express an action either in
the active voice ("Alison bought the book") or the passive ("The book was bought by Alison"). The
Danish passive is built periphrastically with the auxiliary **blive** + past participle (*blive
købt, blev købt, er blevet købt...*), paralleling the English "be bought" construction across all
five tenses (infinitive, present, past, perfect, pluperfect). A second, Danish-specific option
exists only for the infinitive, present and past tenses: an **-s** suffix added directly to the
verb stem (*købes, købtes*) — there is no **-s** form for the perfect/pluperfect, which must use
**blive**. Verbs whose active past tense already ends in a consonant (*hjalp, drak*) merge their
**-s** passive past with a single form (*blev hjulpet/blev drukket* rather than a separate **-s**
past). The spoken language tends to prefer the **blive**-periphrastic forms generally, but after
modal verbs the **-s** infinitive is required (*Tøjet skal vaskes* = the clothes must be washed),
except after **vil** implying future or **skal** implying a promise, where **blive** is used
instead. Customary or long-duration actions also favor the **-s** forms. The agent ("by X") is
marked with **af** (*Børnene blev hentet af deres far*).

### Unit 15 — Expressions of time

A consolidated reference list (pp.196-197) gathers every time expression used across the book so
far plus new additions: today/tomorrow/yesterday and their "day before/after" extensions (*i
dag, i morgen, i overmorgen, i går, i forgårs*), morning/evening references distinguishing "this
morning referred to later in the day" (*i morges/i formiddags*) from "yesterday morning" (*i går
morges*), week/month/year relative expressions, clock-time expressions ("20 minutter over 7" = 20
past 7; "11 minutter i 9" = 11 to 9; "halv 3" = half past 2 — note Danish "half" counts down to
the coming hour, not up from the previous one), and a preposition-choice rule for "during": **under**
is used unless the following word is itself a time expression, in which case **i** or **i løbet af**
is used instead (*under desserten* "during the dessert" vs. *i løbet af sommeren* "during the
summer").

### Unit 16 — Verbs ending in "-s" (the lykkes class)

A distinct class of Danish verbs end in **-s** in every form but carry no corresponding active
voice and no passive meaning either — **lykkes** (succeed) is the paradigm case, with its past
participle (**lykkedes**) identical to its past tense. When the logical subject of **lykkes** is a
person, Danish requires an impersonal construction: *Det lykkedes (for) ham at skabe et marked* (He
succeeded in creating a market), literally "it succeeded for him to...". Its opposite is
**mislykkes** (fail). A second subgroup consists of otherwise-normal active verbs that *also* have
an **-s** form carrying a distinct, non-passive meaning — not simply the passive of the active verb:
**følge** (follow/accompany) vs. **følges (ad)** (accompany *each other*, i.e. go together);
**møde** (meet someone) vs. **mødes** (meet each other, reciprocal); **skylde** (owe) vs.
**skyldes** (stem from, be due to); **slå** (hit, strike) vs. **slås** (hit each other, i.e. fight —
past tense **sloges**, distinct from slå's own past **slog**). **Skiftes til** (take something in
turns) and **findes** (be, exist) belong to the same family. **Lykkes** and **mislykkes** take
**være** as their perfect-tense auxiliary; the others take **have**.

### Unit 16 — Unstressed adverbs: the modal-particle system (da, dog, jo, nok, nu, vel, vist) — HIGH VALUE FOR SLANG-MECHANISM DESIGN

This is this fragment's single most important grammar point for the project's conlang-slang-
synthesis purposes, and the book explicitly frames it as a register phenomenon: "Just as in English
there is a tendency to qualify a statement by adding *I think, I suppose, you know*, the same is the
case in **colloquial** Danish [emphasis in source's framing]. Here this effect is achieved by means
of unstressed adverbs." The book names seven of these as the most common — **da, dog, jo, nok, nu,
vel, vist** — and stresses that "they have different meanings depending on the context and it is
therefore rather difficult for foreigners to learn to use them." This is a textbook description of a
discourse-particle system encoding subtle speaker stance/attitude toward an utterance, layered on
top of its literal propositional content — exactly the kind of compact, context-dependent,
register-marked mechanism a synthesized slang system could productively borrow or parody. Per-
particle senses attested in the source, each with a worked example:

- **nok** — probably, definitely, or "I suppose": *Han har nok glemt, at vi skal mødes* (He has
  probably forgotten...); *Jeg må nok hellere ringe ham op* (I suppose I had better give him a
  call).
- **da** — conveys surprise, or is used purely for emphasis: *Det var da underligt!* (How
  strange!); *Hun er da 17* (She is 17, you know); *Hun kommer da?* (She is coming, isn't she? —
  here **da** functions as a confirmation-seeking tag).
- **vel** — among other senses, "I suppose", "probably", "I hope": *De kommer vel på søndag* (I
  suppose they are coming on Sunday); *Der er vel ikke sket noget* (I hope nothing has happened);
  *De kommer ikke, vel?* (They aren't coming, are they? — tag-question use).
- **dog** — conveys mild impatience: *Hvor bliver George dog af?* (Where has George got to? —
  implying impatience).
- **jo** — signals that the listener already knows or should have noticed the point: *Det er jo
  ikke nogen helt almindelig chokolade* (It is no ordinary chocolate — "as you no doubt have
  noticed").
- **nu** (in this discourse use, distinct from temporal "now") — an emphatic "I must say" stance
  marker: *Det er nu nemt at flyve fra England til Danmark* (I must say it is easy to fly from
  England to Denmark).
- **vist** — the speaker's own probabilistic inference: *Det er vist det røde hus derhenne* (It is
  probably the red house over there).

Several of the book's own dialogue lines independently stack these particles with other colloquial
markers already flagged above — e.g. "Men dog!" (p.242, glossed "I say!") and "Sikke noget pjat!"
(p.232/239, "Nonsense!") both lean on this same unstressed-adverb mechanism for their expressive
force, and "vel nok" (p.190, "really") is a two-particle stack. This system is a strong candidate
reference point for any derived-conlang slang mechanism built around compact stance-marking
particles layered onto otherwise plain utterances.

### Unit 16 — Adjectives used as adverbs

Building on Unit 9 (adjective → adverb via **-t**: *Han skriver langsomt*, "He writes slowly"),
this point notes an exception: adverbs derived from adjectives ending in **-lig** or **-ig** do
not always take the **-t** ending. They *do* take **-t** when qualifying a verb (*Det blæser
frygteligt* = "It is blowing terribly" — i.e. "It is terribly windy"), but *omit* **-t** when
qualifying an adjective or another adverb (*Det er frygtelig koldt* = "It is terribly cold";
*Bilen kørte frygtelig stærkt* = "The car drove terribly fast").

### Unit 17 — Singular and plural form of nouns (English/Danish mismatches)

A systematic list of nouns whose number disagrees between the two languages. Danish-plural-for-
English-singular: **penge** (money), **smykker** (jewellery, sg. *et smykke*), **møbler**
(furniture, sg. *et møbel*), **råd** (advice/piece of advice, no distinct plural form — the
plural-looking *råd* can mean either "a piece of advice" or "advice" collectively). Danish-
singular-for-English-plural: **tøj** (clothes — *Tøjet er rent* = "The clothes are clean"),
**værktøj** (tools, a compound of *tøj* and therefore also singular-only — *Han ejer ikke et
eneste stykke værktøj* = "He hasn't got a single tool"), **smørrebrød** (sandwiches —
*Smørrebrødet kommer klokken 4* = "The sandwiches will arrive at 4 o'clock", but *et stykke
smørrebrød* for "a sandwich"). A second mismatch area (Grammar point 2, p.240-241) covers cases
where Danish simply omits an indefinite article that English requires — for professions,
nationalities and religions (*Han er ekspedient* = "He is a shop assistant"; *Lotte er dansker* =
"Lotte is a Dane"; *Per er katolik* = "Per is a Catholic") — and cases where Danish omits "of" that
English requires in a partitive/quantity construction (*et glas øl* = "a glass of beer"; *en skive
melon* = "a slice of melon"; *et par sko* = "a pair of shoes"; *2 pund smør* = "2 pounds of
butter"; *øen Fyn* = "the island of Funen").

### Unit 17 — The words etage and sal; the Danish word mening

**Etage** names a floor/storey generically or counts total storeys (*Huset har fem etager* = "The
building has five storeys"); **sal** is used for a specific numbered floor, especially in a block
of flats (*Marianne bor på tredje sal* = "Marianne lives on the third floor"); the ground floor
itself is **stue** or **stueetage**, never "første sal". Separately, **mening** is explicitly
flagged as a three-way false-friend trap: it can mean *opinion* (*vidt forskellige meninger* =
"widely different opinions"), *sense* (*Giver det nogen mening?* = "Does it make any sense?"), or
*intention* (*Det var meningen, at det skulle ske* = "It was meant/intended to happen") — three
senses an English speaker would keep lexically separate.

### Unit 18 — Comparison of adjectives (irregular and vowel-change classes)

Two closed classes of irregular comparison are tabulated. Fully irregular (positive/comparative/
superlative): **gammel/ældre/ældst** (old), **god/bedre/bedst** (good), **lille/mindre/mindst**
(little), **lidt/mindre (less)/mindst (least)**, **meget/mere/mest** (much), **mange/flere/flest**
(many), **slem/værre/værst** (bad). A vowel-change-only class keeps the same root consonant pattern
but mutates the stem vowel: **få/færre/færrest** (few), **lang/længere/længst** (long),
**stor/større/størst** (big), **ung/yngre/yngst** (young). A further one-off irregularity: **nær**
(near) inserts an **-m-** before the **-ere**/**-est** endings — *nærmere, nærmest* — rather than
following either pattern cleanly.

### Unit 18 — Indefinite and definite forms of nouns (abstraction rule)

Abstract nouns — death, fate, time, light, democracy, parliament and similar — tend to appear in
the **definite** form in Danish even where English uses the bare/indefinite noun: *Han er døden
nær* (He is at death's door — lit. "the death"), *Skæbnen var ham blid* (Fate was kind to him —
lit. "the fate"), *Tiden læger alle sår* (Time heals all sorrows — lit. "the time"), *lysets
hastighed* (the speed of light — lit. "the light's speed"), *Demokratiet er i fare* (Democracy is
in danger — lit. "the democracy"), *Folketinget samles på Christiansborg Slot* (Parliament meets
at Christiansborg Castle — lit. "the parliament").

### Strong and irregular verbs appendix (pp. 245-247)

The book closes Unit 18 with a consolidated, alphabetized three-column paradigm table (infinitive /
past tense / past participle, with an irregular present tense shown in square brackets after the
infinitive where applicable) covering every strong/irregular verb that has appeared across the
whole book's dialogues and texts, including prefixed verbs (e.g. **indse**, **tilbringe**) and
compound verbs (e.g. **istandsætte**). Prefixed/compound verbs that conjugate identically to their
base verb are cross-referenced rather than given separate forms (e.g. "afbryde (cf. bryde)") — the
table below tabulates only the entries the book itself spells out with explicit forms; the
cross-referenced-only entries are **afbryde** (cf. bryde), **afgå** (cf. gå), **ankomme** (cf.
komme), **ansætte** (cf. sætte), **befinde** (cf. finde), **beskrive** (cf. skrive), **bestå** (cf.
stå), **efterlade** (cf. lade), **foreslå** (cf. slå), **forlade** (cf. lade), **forstå** (cf. stå),
**fortsætte** (cf. sætte), **fortælle** (cf. tælle), **grundlægge** (cf. lægge), **indse** (cf. se),
**indtage** (cf. tage), **istandsætte** (cf. sætte), **omgive** (cf. give), **tilbringe** (cf.
bringe), **tilbyde** (cf. byde), **udsætte** (cf. sætte), **undgå** (cf. gå), and **ødelægge** (cf.
lægge) — each inflects exactly like its cited base verb, with the prefix carried through unchanged.

### Strong and irregular verbs — full paradigm table (appendix, printed pp. 245-247)

The book's own appendix tabulates principal parts (infinitive / present if irregular / past tense /
past participle) for its strong and irregular verb class, consolidating forms introduced piecemeal
across units into one systematic reference. Reproduced as a 4-column table (distinct from the main
12-column vocabulary schema, since this is a grammatical paradigm reference, not a set of independent
vocabulary entries):

| Infinitive | Present (if irregular) | Past Tense | Past Participle |
|---|---|---|---|
| afhænge | — | afhang | afhængt |
| bede | — | bad | bedt |
| betyde | — | betød | betydet |
| blive | — | blev | blevet |
| bringe | — | bragte | bragt |
| bryde | — | brød | brudt |
| burde | bør | burde | burdet |
| byde | — | bød | budt |
| drikke | — | drak | drukket |
| dø | — | døde | (er) død (adjective) |
| falde | — | faldt | faldet |
| fare | — | farede/for | faret |
| finde | — | fandt | fundet |
| findes | — | fandtes | (har) fandtes |
| flyve | — | fløj | fløjet |
| forsvinde | — | forsvandt | forsvundet |
| fryse | — | frøs | frosset |
| fyge | — | fygede/føg | fyget/føget |
| følge | — | fulgte | fulgt |
| få | — | fik | fået |
| give | — | gav | givet |
| gøre | gør | gjorde | gjort |
| gå | — | gik | gået |
| have | har | havde | haft |
| hedde | — | hed | heddet |
| hjælpe | — | hjalp | hjulpet |
| holde | — | holdt | holdt |
| knibe | — | kneb | knebet |
| komme | — | kom | kommet |
| kunne | kan | kunne | kunnet |
| lade | — | lod | ladet (ladt in prefixed verbs only) |
| ligge | — | lå | ligget |
| lyde | — | lød | lydt |
| lægge | — | lagde | lagt |
| løbe | — | løb | løbet |
| måtte | må | måtte | måttet |
| nyde | — | nød | nydt |
| overdrive | — | overdrev | overdrevet |
| rive | — | rev | revet |
| se | — | så | set |
| sidde | — | sad | siddet |
| sige | — | sagde | sagt |
| skrive | — | skrev | skrevet |
| skulle | skal | skulle | skullet |
| skære | — | skar | skåret |
| slå | — | slog | slået |
| slås | — | sloges | (har) sloges |
| sove | — | sov | sovet |
| springe | — | sprang | sprunget |
| spørge | — | spurgte | spurgt |
| stjæle | — | stjal | stjålet |
| stå | — | stod | stået |
| synge | — | sang | sunget |
| sælge | — | solgte | solgt |
| sætte | — | satte | sat |
| tage | — | tog | taget |
| turde | tør | turde | turdet |
| tælle | — | talte | talt |
| vide | ved | vidste | vidst |
| ville | vil | ville | villet |
| vælge | — | valgte | valgt |
| være | er | var | været |

(**slås**, "fight/hit each other" — see Unit 16 Grammar point above — is included in the appendix
alongside its base verb **slå** because its past tense "sloges" is itself irregular relative to the
expected -s-suffixed pattern.)

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`.
