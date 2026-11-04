# Swedish — Colloquial Swedish (1996, 2nd/"Revised" edition) — Part A

**Split-file note:** This extraction grew past the ~150KB single-file guideline, so it is split into `017a_colloquial_swedish_1996.md` (this file: Pronunciation chapter + Lessons 1–5), `017b_colloquial_swedish_1996.md` (Lessons 6–11), and `017c_colloquial_swedish_1996.md` (Lessons 12–18, plus the back-matter spot-check note and final summary). All three share the header/caveats below; only this file (008a) repeats them in full.

**Source citation:** Philip Holmes and Gunilla Serin, *Colloquial Swedish: The Complete Course for Beginners*, Routledge "Colloquial" series, 2nd edition (the title page reads "Second edition"; the book's own "Note on the second edition" dates this revision to **1996**). Scanned/OCR'd PDF (Adobe Acrobat 7.0 "Paper Capture" OCR layer, created 2007), 321 PDF pages. Printed page numbers run `PDF page − 4` from "Using this book" through the end of Lesson 18 (verified against the book's own Contents listing and cross-checked at several lesson boundaries). Page citations below use the book's own printed page numbers.

**Relationship to the 2007 edition:** A later, substantially rewritten 3rd edition (2007, by Ahlgren/Holmes/Serin) of the same title is extracted separately into the sibling file `018_colloquial_swedish_2007.md` by a parallel subagent. Per that file's own note, the 2007 edition's preface states that for the 3rd edition "all Texts and Dialogues and many Factual texts are new" and the unit count was reduced to seventeen — so overlap with this 1996/2nd-edition file is expected in grammar sequencing (both editions share the same two original authors and broadly the same pedagogical skeleton) but *not* in specific vocabulary, dialogue content, or cultural material. This file extracts the 1996 edition fully and on its own terms; no de-duplication against `009` was attempted (per dispatch instructions, the two were run in parallel without coordination).

**Text layer quality — important caveat:** Unlike the 2007 edition's clean text layer, **this PDF's OCR layer is badly degraded**, especially (but not only) on the Swedish diacritics å/ä/ö. The corruption is a genuine many-to-one OCR garbling, not a fixed decodable substitution cipher: the same letter is misread differently in different places (e.g. "å" is variously rendered as `B`, `g`, `s`, `5`, `6`, `8`, `%`, `&`, or dropped entirely, even within the same page), and the pattern was confirmed non-uniform across 15+ check words, ruling out a fixed-offset or fixed-mapping decode per the extraction spec's OCR-gotchas guidance. Recovery for this file was therefore done **by cross-referencing the parallel English translation the book itself prints alongside nearly every Swedish example/dialogue line**, plus ordinary knowledge of standard Swedish vocabulary and grammar — the same "cross-reference context, don't guess a fixed table" principle the spec documents for the UTF-8-as-Latin-1 mojibake case. This worked reliably for dialogue and running-text vocabulary (which always has an English gloss alongside it) but **not** for two specific content types, which are therefore excluded rather than guessed:
- The Pronunciation chapter's long lists of personal names and place names used to illustrate vowel length/stress (no English gloss, severely garbled, and not meaningful vocabulary content in their own right) — general phonological *rules* from this chapter are still captured as grammar points below, just not the specific drill-word lists.
- A small number of individual words elsewhere where the OCR noise was severe enough that no confident reconstruction was possible even with the English gloss as a cross-check — these are explicitly flagged `low_confidence` in the Notes column of the relevant table row rather than silently guessed, per the vision-reading-guard discipline (applied here by analogy even though this is a text-layer, not a vision-read, source).
Since this is a text-layer source (not vision-read), **Vision Reading Confidence is `n/a` throughout** per the spec's column rule; the OCR-reconstruction caveat above is carried per-row in the Notes column instead, only where a specific entry actually needed it.

**Colloquial/register content — flagged up front per dispatch instructions.** This book, true to the "Colloquial" series' purpose, explicitly marks a number of items as informal/spoken register, beyond the baseline conversational framing:
- The book's own vocabulary box explicitly tags **fika** ("to have a coffee break") `(colloquial)` — a flagship, still-current Swedish cultural/linguistic colloquialism (Lesson 1).
- A cluster of spoken-register discourse particles/tags is explained with explicit register commentary: **jaså** ("oh really?/you don't say", registers surprise), **jaha** ("oh really", registers merely that you're listening), **eller hur** (tag question, "don't you", compared explicitly to French *n'est-ce pas*), **jo** (affirmative answer to a negative question, compared to French *si*) (Lesson 2).
- Running "final consonants are dropped" pronunciation notes recur through the early lessons for high-frequency words (*vad→va*, *det→de*, *är→e*, *och→å*, *mig→mej*, *dig→dej*, *honom→konom* etc., *de/dem→dom*), and the book explicitly says *dom* is "sometimes also written" that way — i.e. the book itself flags a written colloquialism, not just a pronunciation note.
- Explicit dialectal variation is flagged for sk- pronunciation ("large variations... depending on dialect and speaker", Pronunciation chapter).
These and further findings are called out per-row in the Vocabulary tables' Notes column with a non-`core` Usage Tier, and summarized again in the final report.

**Coverage approach:** Extracted lesson-by-lesson (18 lessons) plus the preliminary "Pronunciation, stress and accents" chapter. The book's own back-matter (Key to exercises, pp. 227–247; Swedish–English glossary, pp. 248–276; Concise English–Swedish glossary, pp. 277–289; Grammatical index, pp. 290–293 by printed numbering) is a cumulative alphabetical consolidation of the same vocabulary already introduced lesson-by-lesson (the book's own "Using this book" note states "all the words used are to be found in the Swedish-English glossary at the end of the book") — per the spec's non-redundant-supplement principle and the copyright-discipline rule against bulk-reproducing a dictionary-style vocabulary box, this back matter was spot-checked rather than re-transcribed; no genuinely new vocabulary items beyond what the per-lesson boxes already contain were found. Repeated drill/exercise sentences that introduce no new vocabulary or grammar are skipped per the coverage rule.

---

## Pronunciation, stress and accents (pp. 7–19)

**Vocabulary:** none extracted — see the text-layer caveat above; the chapter's content is a set of general phonological/prosodic rules illustrated with name/place-name lists that could not be reliably OCR-reconstructed (no English gloss to cross-check against) and are not meaningful vocabulary items regardless.

### The alphabet

Swedish has 29 letters: the standard 26 plus å, ä, ö, which sort at the *end* of the alphabet (not interleaved with a/o or a/e as a learner might assume). `w` (pronounced like `v`) occurs only in names and loanwords and alphabetizes under `v` in dictionaries.

### Vowel length

Stressed vowels are either long or short, and the distinction is phonemic (meaning-distinguishing), not just a stylistic lengthening. Rules for predicting length from spelling: a vowel before a single consonant letter is long; a vowel before a double consonant or a two-consonant cluster is short (and the following consonant is long); a vowel in an open syllable (no following consonant) is long. Exception: words ending in -m, -n, where the m/n are often already long, so the preceding vowel is short regardless (cf. *den*, *hem*). Unstressed vowels are always short.

### Consonants: soft vs. hard g-, k-, sk-

Pronunciation of word-initial g-, k-, sk- depends on the following vowel. Before e, i, y, ä, ö ("soft" vowels), g- is pronounced like Swedish/English `y` (as in "yell"), k- is pronounced like a softened English "ch", and sk- is pronounced like English "sh" with lip-rounding. Before o, u, a, å ("hard" vowels), g-, k-, sk- are pronounced as in English "gate", "keep", "skill". The book explicitly notes sk- pronunciation shows real dialectal variation beyond this rule. Related: `s` is always unvoiced (never like English "z"); `-rs` sounds like English "sh" with lip-rounding; `-rt` is pronounced with the tongue further back than English "t".

### Sentence stress vs. word stress

Swedish distinguishes words that normally carry sentence stress (content words: nouns, main verbs without a following object/complement, adjectives, numerals, most adverbs of manner/place/time) from words that are normally unstressed (personal/possessive pronouns, most conjunctions, the adverbs *inte, nog, väl, ju*, the infinitive marker *att*). A stressed word's *internal* syllable stress is a separate, second layer ("word stress").

### Two-word stress units

When two words form one unit of meaning (preposition+noun, article+noun, verb+particle, verb+verb, infinitive marker+verb, verb+complement, comparison word+compared word, pronoun+pronoun, time/measurement phrases, numeral+numeral, first name+surname), stress falls on the *second* word of the pair, not the first.

### Accent 1 vs. Accent 2 (word melody)

Beyond ordinary stress, Swedish compounds and many non-compound words carry a distinctive pitch "melody." **Accent 2** (the stereotypical "singsong" quality of spoken Swedish) is a falling tone on the main stressed syllable followed by a rising tone on a later syllable; it is obligatory on compound words and affects many two-syllable simple words too, and the book notes this melody pattern itself varies regionally across Sweden (Central Swedish — Stockholm-area — pattern is the one described as default). **Accent 1** is a single rise with no preceding fall/following rise; it occurs with words made two-syllable only by adding the definite end-article (*-en/-et*) or the present-tense ending *-er*, and with a set of words that must be learned individually (the book cites "sugar, water, bicycle" as Accent-1 examples, alongside "try, park, cigarettes" for words stressed on a non-initial syllable).

---

## Lesson 1 — Vem är det? (Who is it?) (pp. 20–29)

Introduces: present-tense verbs, personal pronouns, noun gender (N-words/en vs. T-words/ett), two question types (yes/no inversion and v-word questions), short answers, dropped final consonants in common words, asking for things and saying thanks, capitalization conventions, compound nouns, quantity expressions without a genitive "of".

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| vem | who | pronoun | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| vad | what | pronoun | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | book notes final -d is dropped in speech ("va") |
| det | it | pronoun | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | book notes final -t is dropped in speech ("de") |
| är | am/is/are | verb (vara, present) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | book notes final -r is dropped in speech ("e") |
| och | and | conjunction | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | book notes final -ch is dropped in speech (approx. "å") |
| jag | I | pronoun | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | pronounced "ja" |
| du | you (sg.) | pronoun | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| han | he | pronoun | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| hon | she | pronoun | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| den | it (N-word antecedent) | pronoun | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| man | one (impersonal) | pronoun | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | pronounced "ma" |
| vi | we | pronoun | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| ni | you (pl.) | pronoun | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| de/dom | they | pronoun | colloquial | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | pronounced, and sometimes also written, "dom" — book flags this as a written-colloquial spelling, not just a pronunciation |
| äta/äter | eat | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| äpple -t -n | apple | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| päron -et - | pear | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| persika -n -or | peach | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| smörgås -en -ar | sandwich | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| liten/litet/lilla | small | adjective | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| stor -t -a | big | adjective | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| hungrig -t -a | hungry | adjective | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| fabrik -en -er | factory | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| högskola -n -or | university/college | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| studera/-r -de | study | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| läsa/-er -te | read, study | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| på | at, in | preposition | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| kafeteria -n -or | cafeteria, café | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| grupp -en -er | group | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| student -en -er | student | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| fika/-r -de | have a coffee break | verb | colloquial | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | book's own vocabulary box explicitly tags this `(colloquial)` — flagship, still-current Swedish cultural term |
| skulle vilja ha | would like | verb phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| vilja/vill ville velat | want (to) | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| ha/-r hade haft | have | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| kaffe -t | coffee | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| kopp -en -ar | cup | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| bulle -n -ar | bun | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| tack | please / thank you | interjection | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| också | also | adverb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| få/-r fick fått | get, may; (here:) take | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| läsk -en | soft drink | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| med | with | preposition | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| ostsmörgås -en -ar | cheese sandwich | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| åtta | eight | numeral | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| lättöl -et | light beer | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | low_confidence on the exact gender/plural ending — OCR rendered this entry very poorly ("lam1 -et"); term itself reconstructed with high confidence from context (dialogue asks for a drink, gets "ja, lättöl har vi") |
| kan jag få | can I have | phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| kunna/kan kunde kunnat | can, be able | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| då | then | adverb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| ägg -et - | egg | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| ansjovis -en -ar | anchovy | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| skinksmörgås -en -ar | ham sandwich | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| krona -n -or | unit of currency (100 öre = 1 krona) | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| glas -et - | glass | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| kosta/-r -de | cost | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| te -et | tea | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| kaka -n -or | cake | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| ta in beställningen | bring in the order | verb phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| beställning -en -ar | order | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| varsågod | here you are / please (do...) | interjection | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | book compares to German "Bitte!"; notes it can also be used curtly/impolitely in a demand |
| tack så mycket | thank you very much | phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| tack ska du ha | thank you so much | phrase | colloquial | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | one of several listed variants on "tack" |
| servering | self-service cafeteria (sign) | noun | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | from the "eating out" cultural-vocabulary exercise |
| korvkiosk -en -er | sausage/hot-dog kiosk | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| varmkorv -en -ar | hot dog | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| gatukök -et - | street-food stand (lit. "street kitchen") | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| konditori -et -er | café/patisserie | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | book gives clipped colloquial variants "kondis", "kafé"/"fik" for this same concept |
| kondis | café (clipped) | noun | colloquial | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | clipping of "konditori"; book-internal register note |
| fik | café (clipped) | noun | colloquial | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | book-flagged informal variant |
| restaurang -en -er | restaurant | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| självservering -en -ar | self-service (restaurant) | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| matsedel -n -sedlar | menu | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| bricka -n -or | tray | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| tallrik -en -ar | plate | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| bestick -et - | cutlery | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| dagens rätt | today's special (set meal) | noun phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| kassa -n -or | till, checkout | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| rökning förbjuden | smoking prohibited (sign) | phrase | formal | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | public-notice register |
| brickinlämning | tray return (sign) | noun | formal | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | public-notice register |
| omfatta/-r -de | comprise | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| svensk -en -ar | Swede | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| tala/-r -de | speak | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| mest | mostly | adverb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| svenska -n | Swedish (language) | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| drottning -en -ar | queen | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| huvudstad -en -städer | capital (city) | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| kung -en -ar | king | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| heta/heter hette hetat | be called | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| mycket | a lot, much | adverb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| skog -en -ar | forest | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| ganska | rather, quite | adverb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| sällan | rarely, seldom | adverb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| sol -en | sun | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| ibland | sometimes | adverb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| både...och... | both...and... | conjunction | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |

### Grammar points

#### Present tense: no person/number agreement
Swedish verbs do not change for person or number — one present-tense form covers I/you/he/she/it/we/you(pl.)/they (e.g. *jag är, du är, han är... de är* all use the single form *är*). Most regular verbs form the present tense in *-r* (stem ends in a vowel) or *-er* (stem ends in a consonant).

#### N-words and T-words (noun gender)
Every Swedish noun is either **N-gender** (takes the indefinite article *en*) or **T-gender** (takes *ett*). About three-quarters of nouns are N-gender, including most nouns for people, higher animals, days, and parts of the day — but gender is not otherwise predictable from meaning and must be learned per noun. The pronoun "it" agrees in gender with its antecedent (*den* for N-words, *det* for T-words) once the noun has been mentioned, but *det* is used regardless of gender when the gender is unknown or the noun itself is given in the same sentence (e.g. "Vad är det? Det är en smörgås" — not *den*, even though *smörgås* is N-gender).

#### Two question types
Yes/no questions invert verb and subject (*Är det en liten pojke?*). V-questions place an interrogative/"v-word" first, then invert verb and subject after it (*Vad är det?*, *Vem är det?*) — most Swedish interrogatives begin with v-, hence the name.

#### Short answers
The pattern is *Ja/Nej, det + verb + subject (+ inte)*, e.g. "Ja, det är det" (yes, it is), "Nej, det är det inte" (no, it isn't). If the question's main verb is not *vara* (be), *ha* (have), or a modal, the short answer substitutes a form of *göra* (do): "Talar du svenska? — Ja, det gör jag" (Do you speak Swedish? — Yes, I do).

#### Dropped final consonants
A handful of very common words drop their final consonant in speech: *vad→va*, *det→de*, *är→e*, *och→å* (roughly). The book also gives *de/dem→dom*, flagged as sometimes written that way too, not just pronounced.

#### No genitive "of" with quantities
Where English uses "of" with a quantity ("a cup of coffee"), Swedish simply juxtaposes the quantity noun and the substance noun with no linking word: *en kopp kaffe*, *ett glas vin*, *en flaska öl*, *ett kilo ost*, *en liter fil*.

#### Compound nouns as an alternative to "med" phrases
"A sandwich with cheese" can be expressed either as *en smörgås med ost* or as the single compound *en ostsmörgås* — note the first noun's final *-a* is dropped when compounding (*skinka* → *skink-smörgås*).

#### How to ask for things; varsågod/tack
Politeness phrases drilled in this lesson: *Har ni/du...?* ("Have you got...?"), *Kan jag få... tack?* ("Can I have... please?"), *Jag skulle vilja ha...* ("I want..."), *Jag tar...* ("I'll have..."), *Vad kostar...?* ("What does... cost?"). *Tack* does double duty as both "thank you" and, sentence-finally, "please." *Varsågod* (compared to German "Bitte!") is used when giving something, holding a door, or inviting someone to do something — and the book notes it can also be used curtly as a command ("Varsågod och gör som jag säger!" — "Do as I say!").

#### Capital letters
Swedish uses lower case where English capitalizes: weekdays, months, festivals (*måndag*, *januari*, *midsommar*); nouns/adjectives of nationality, language, religion, political affiliation (*engelsman*, *svensk*, *katolik*, *socialdemokrat*); and titles used with names (*herr Ek*, *doktor Lind*).

## Lesson 2 — Rebecca, en student (Rebecca, a student) (pp. 30–42)

Introduces: verbs in the infinitive and present tense, noun gender/articles continued, time expressions, straight vs. inverted word order, numerals 1–12, pronunciation of g-/k-/sk- (dialectal variation), how to say yes/no, greetings, v-words, word order in questions.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| en/ett | a, an | article | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| år -et - | year | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| komma/kommer | come | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| från | from | preposition | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| läsa/-er -te | read, study | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| universitet -et - | university | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| men | but | conjunction | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| just nu | at present, right now | adverb phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| bo/-r -dde | live, reside | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| lägenhet -en -er | flat, apartment | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| på morgonen | in the morning | adverb phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | book marks reduced pronunciation "morronen" |
| åka/-r -de | travel (by) | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| tunnelbana -n | tube, underground, metro | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| göra/gör gjorde gjort | do, make | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| gå på | go to, attend | verb phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| föreläsning -en -ar | lecture | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| sitta/-er satt | sit | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| bibliotek -et - | library | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| anteckna/-r -de | make notes | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| skriva/-er skrev skrivit | write | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| uppsats -en -er | essay | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| översättning -en -ar | translation | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| börja/-r -de | begin | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| redan | already, as early as | adverb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| hata/-r -de | hate | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| väckarklocka -n -or | alarm clock | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| ringa/-er -de | ring | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| möte -t -n | meeting | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| va | tag particle ("isn't it", lit. "what") | discourse particle | colloquial | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | spoken-register sentence tag |
| förstå/-r förstod förstått | understand | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| ja visst | of course | phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| lite grann | a little, a bit | adverb phrase | colloquial | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| jaså | oh really?, you don't say, is that so | interjection | colloquial | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | book: "registers surprise" |
| jaha | oh really (neutral acknowledgment) | interjection | colloquial | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | book: "registers merely that you are listening" |
| varifrån | where...from | interrogative | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| eller hur | tag question, "don't you", "isn't that so" | discourse particle | colloquial | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | book compares explicitly to French "n'est-ce pas?" |
| förresten | by the way, incidentally | adverb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| egentligen | actually | adverb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| prata/-r -de | talk, chat | verb | colloquial | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | everyday-spoken register verb for "talk" (contrast more neutral *tala*) |
| ju | discourse particle (roughly "of course", "as you know") | discourse particle | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | book cross-refers to a fuller later treatment (p.125) |
| dig | you (object) | pronoun | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | pronounced "dej" |
| jo | yes (affirmative answer to a negative question) | interjection | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | book compares explicitly to French "si" |
| hej | hi, hello | interjection | colloquial | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | "usual friendly greeting" per book |
| goddag | good day, how do you do | interjection | formal | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | pronounced "godda"; book's formal counterpart to *hej* |
| hej då | bye for now | interjection | colloquial | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| hej hej | bye (casual doubling) | interjection | colloquial | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| hej så länge | see you later, bye for now | interjection | colloquial | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| adjö | goodbye | interjection | formal | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | pronounced "ajö"; book's formal counterpart to the *hej då* family |
| var | where | interrogative | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| vem | who | interrogative | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| hur | how | interrogative | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| när | when | interrogative | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| noll | zero | numeral | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| en/ett (numeral) | one | numeral | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | two forms per N/T-gender when counting things |
| två | two | numeral | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| tre | three | numeral | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| fyra | four | numeral | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| fem | five | numeral | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| sex | six | numeral | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| sju | seven | numeral | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| åtta | eight | numeral | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| nio | nine | numeral | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | pronounced "nia" |
| tio | ten | numeral | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | pronounced "tia" |
| elva | eleven | numeral | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| tolv | twelve | numeral | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| Färöarna | the Faroes | proper noun | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| gång -en -er | time, occasion | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| Norden | Scandinavia/the Nordic region | proper noun | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| skillnad -en -er | difference | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| bara | only | adverb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| mellan | between | preposition | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| invånare -n - | inhabitant | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| till ytan | in area, areawise | adverb phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| del -en -ar | part | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| få (adj.) | few | adjective | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| människa -n -or | person, human being | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| same -n -r | Sami person | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | book's English gloss uses the now-dated exonym "Lapp"; Swedish term itself (*same*) is the standard endonym-derived term, unaffected |
| by -n -ar | village | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| mellersta | central, middle | adjective | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| smal -t -a | narrow | adjective | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| varje | every, each | determiner | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| mörk -t -a | dark | adjective | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| järv -en -ar | wolverine | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| björn -en -ar | bear | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| varg -en -ar | wolf | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| mildare | milder | adjective (comparative) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| rikare | richer | adjective (comparative) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| fjäll -et - | mountain, fell | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| högst -a | highest | adjective (superlative) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| berg -et - | mountain | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| älv -en -ar | river | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| sjö -n -ar | lake | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| största | biggest | adjective (superlative) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| täckt av | covered with | adjective phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| tycka/-er -te | think, consider | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| vacker -t vackra | beautiful | adjective | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |

### Grammar points

#### Verbs: present and infinitive formation
When the verb stem ends in a vowel, add *-r* for present tense (*börja→börjar*); when it ends in a consonant, add *-er* (*skriva→skriver*). Regular infinitives end in *-a* or another vowel. *Vara* (to be) is irregular; *göra* (do/make) already ends in *-r* in the stem so no extra ending is added.

#### Noun gender and the end article
Indefinite articles are *en* (N-words) or *ett* (T-words), placed before the noun. The *definite* article ("the") is instead suffixed to the end of the noun — hence "end article": *en student → studenten*, *ett år → året* (note: only one *-t* is added to T-words already ending in a vowel, e.g. *universitet→universitetet* is regular but a T-word ending in a vowel like *schema* takes *-t*: *schemat*). No article at all is used before a noun of profession/nationality/religion/political affiliation used predicatively ("Nils är lärare" — "Nils is a teacher"), unless the noun is further qualified by an adjective, in which case the indefinite article reappears ("Han är en god katolik" — "He is a good Catholic").

#### Time expressions and clock times
*på morgonen/eftermiddagen/kvällen* ("in the morning/afternoon/evening"), *på natten* ("during the night") all use *på*; but no preposition at all precedes a clock time (*klockan åtta* — "at eight o'clock", not "på klockan åtta").

#### Straight vs. inverted word order
If a sentence begins with its subject, word order is "straight" (subject immediately before the verb). If it begins with something else — commonly a time/place expression — the subject moves to immediately *after* the verb; this is "inverted" word order and is obligatory in Swedish (English allows a fronted time/place phrase without inverting: "Often she begins at 8" stays subject-verb, where Swedish requires *Ofta börjar hon klockan åtta*).

#### Word order in both question types
Both yes/no questions and v-word questions invert verb and subject. In yes/no questions the verb comes first with nothing before it; in v-word questions, the v-word comes first, then the verb, then the subject. Swedish never uses a "do/does" auxiliary the way English questions do (*Läser du svenska?* = "Do you read Swedish?", word for word "Read you Swedish?").

#### Yes/no and related particles
*ja* (yes), *nej* (no), *javisst* (yes, of course — stronger agreement), *jaså* (oh really?/surprise), *jaha* (oh really — neutral, "I'm listening"), *jo* (yes, specifically answering a *negative* question, parallel to French "si" — e.g. "Läser du inte svenska? — Jo, det gör jag!").

## Lesson 3 — Att resa (Travelling) (pp. 43–56)

Introduces: adverbs and their sentence position, the s-genitive, days of the week/parts of the day, numerals 13–1,000, the three negatives (inte/ej/icke), pronunciation of sj-/stj-/skj-/sch-/-si-/-ti-/tj-/kj-, time by the clock, verbs of motion/travel, two-verb (modal) constructions, communications in Sweden.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| representant -en -er | representative | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| engelsk -t -a | English | adjective | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| firma -n -or | firm, company | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| tillverka/-r -de | manufacture, produce | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| plasthandtag -et - | plastic handle | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| sälja/säljer sålde sålt | sell | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| produkt -en -er | product | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| utomlands | abroad | adverb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| resa/-er -te | travel | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| Skandinavien | Scandinavia | proper noun | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| i affärer | on business | adverb phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| nu | now | adverb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| måndag -en -ar | Monday | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| ska i väg till | is off to | verb phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| skola/ska skulle skolat | shall, will | verb (modal) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | book notes older texts spell this "skall" |
| först | first | adverb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| flygplats -en -er | airport | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| utanför | outside | preposition | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| timme -n -ar | hour | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| centrum | town centre | noun | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| sedan | then, after that | adverb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | pronounced "sen" |
| flyga/flyger flög flugit | fly | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| direkt | direct(ly) | adverb/adjective | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| med flyg | by air | adverb phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| resa -n -or | journey | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| hans | his | pronoun | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| väska -n -or | suitcase, bag | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| klockan halv fyra | at half past three | adverb phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| träffa/-r -de | meet | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| företag -et - | company | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| köpa/köper köpte köpt | buy | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| ta(ga) in på | book into, put up at | verb phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| hotell -et - | hotel | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| restaurang -en -er | restaurant | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| för | because, for | conjunction/preposition | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| kläder -na | clothes | noun (plural) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| fortfarande | still | adverb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| Köpenhamn | Copenhagen | proper noun | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| alltid | always | adverb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| aldrig | never | adverb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| biljettlucka -n -or | ticket window | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| enkel (biljett) | single (ticket) | adjective | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | contrasted with "tur och retur" = return |
| röd avgång | cheap-rate departure (lit. "red departure") | noun phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| tyvärr | unfortunately | adverb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| vad synd! | what a pity! | interjection | colloquial | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| sittplatsbiljett -en -er | seat reservation | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| rökare -n - | smoker | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| icke-rökare -n - | non-smoker | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| hur länge | how long | interrogative phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| gälla/-er -de | be valid, apply | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| lågpris | low price | noun | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| bli/blir blev blivit | be, become | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| kort -et - | (credit) card | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| vilken/vilket/vilka | which | pronoun | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | book notes colloquial pronunciation "vicken/vicket/vicka" |
| spår -et - | platform (lit. "track") | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| tåg -et - | train | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| tavla -n -or | (notice)board | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| konduktör -en -er | ticket collector, guard | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| plats -en -er | place, seat | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| stå/står stod stått | stand; (here:) be written | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| biljett -en -er | ticket | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| vagn -en -ar | carriage | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| restaurangvagn -en -ar | restaurant car | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| längre fram | further on, forwards | adverb phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| längre bak | further back | adverb phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| ska till | is going to | verb phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| byte -t -n | change (of train) | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| vara framme | arrive | verb phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| hjälp -en | help | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | pronounced "jälp" |
| järnvägsstation -en -er | railway station | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| bagage | luggage | noun | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | pronounced "bagaasj" |
| effektförvaring -en | left-luggage office | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| inte | not (standard negative) | adverb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | by far the most common negative |
| ej | not (sign/notice register) | adverb | formal | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | book: commonly found on signs |
| icke | not, non- (compound-forming) | adverb | formal | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | book: often found in compounds, e.g. icke-rökare |
| söndag -en -ar | Sunday | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| tisdag -en -ar | Tuesday | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| onsdag -en -ar | Wednesday | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| torsdag -en -ar | Thursday | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| fredag -en -ar | Friday | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| lördag -en -ar | Saturday | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| i måndags | last Monday | adverb phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| nästa måndag | next Monday | adverb phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| vecka -n -or | week | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| månad -en -er | month | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| morgon -en morgnar | morning | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| kväll -en -ar | evening | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| förmiddag -en -ar | later morning | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| afton -en aftnar | early evening | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| eftermiddag -en -ar | afternoon | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| natt -en nätter | night | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| dygn -et - | a full day and night (24h) | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| i morse | (earlier) this morning | adverb phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| igår | yesterday | adverb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| idag | today | adverb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| imorgon | tomorrow | adverb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | pronounced "imorron" |
| imorgon bitti | tomorrow morning (early) | adverb phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| tretton–tusen (13–1000) | thirteen through one thousand | numeral | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | full series: tretton, fjorton, femton, sexton, sjutton, arton, nitton, tjugo, tjugoett, tjugofem, tretti(o), fyrti(o), femti(o), sexti(o), sjutti(o), åtti(o), nitti(o), hundra, tvåhundra, tusen |
| sj-/stj-/skj-/sch-/-si-/-ti-/tj-/kj- | spelling-to-sound correspondences all pronounced like "soft" sk- or "soft" k- | phonology note | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | general rule only; specific drill words not extracted (no English gloss to cross-check against severely garbled OCR) |
| halv nio | half past eight | adverb phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | lit. "half nine" — counts toward the next hour, unlike English |
| kvart i nio | quarter to nine | adverb phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| kvart över nio | quarter past nine | adverb phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| midnatt | midnight | noun | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| hur dags | what time | interrogative phrase | colloquial | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | pronounced "hurdakks" |
| åka/-er -te | go, travel by (general vehicle verb) | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | used with tåg/buss/båt/tunnelbana/bil/skidor/skridskor |
| gå/går gick gått | walk | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | book flags this as a "false friend" (does not mean generic "go" as often assumed from English) |
| måste | must, have to | verb (modal) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| tänka/tänker tänkte tänkt | think, (here:) be thinking of | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| väldig -t -a | enormous | adjective | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| avstånd -et - | distance | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| landsdel -en -ar | part of the country, region | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| nära | almost; near | adverb/preposition | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| väg -en -ar | road | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| köra/kör -de | drive | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| försiktigt | carefully | adverb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| hända/händer hände hänt | happen, occur | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| olycka -n -or | accident | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| ökning -en -ar | increase | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| billig -t -a | cheap | adjective | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| pågatåg | regional train name, Skåne | proper noun | regional | — | contemporary (source published 1996) | Skåne | regional | grammar_reference | n/a | n/a | book explicitly glosses this as "trains named after the best-known word in Skåne dialect, *pig* = *pojke* ('boy')" — explicit dialect annotation |
| spårvagn -en -ar | tram | noun (en) | core | — | contemporary (source published 1996) | Göteborg, Norrköping | local | grammar_reference | n/a | n/a | book notes trams survive only in these two cities nowadays |
| på landet | in the countryside | adverb phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| järnväg -en -ar | railway | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| bro -n -ar | bridge | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| Öresund | the Öresund strait | proper noun | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | book references the then-planned bridge (opened 2000) as a future project |

### Grammar points

#### Adverb position in main clauses
Sentence-modifying adverbs (*alltid, ofta, inte, aldrig, sällan* etc.) go directly after the first verb (VERB1) in a Swedish main clause, unlike English, where such adverbs can precede or follow the first verb. In inverted word order (subject after the verb), the adverb follows the subject, not the verb. More than one such adverb can stack in sequence.

#### The s-genitive
Swedish forms a genitive by adding *-s* directly to the noun, with **no apostrophe** (*Sveriges huvudstad*, *firmans produkter*) — except words already ending in *-s*, which add an apostrophe instead. Swedish s-genitives often correspond to English "of"-genitives rather than English "'s". The genitive *-s* is added after the end article where present, and a noun immediately following an s-genitive noun never itself takes the end article (*firmans representanter*, not *firmans representanterna*).

#### Three negatives: inte / ej / icke
*Inte* is the ordinary, by-far-most-common negator in both speech and writing. *Ej* is characteristic of signage/notices ("Ej rökning", "Ej ingång"). *Icke* mainly forms negated compounds (*icke-rökare*, *icke-våld*, *icke-kristen*).

#### Time by the clock
Half-hours are expressed relative to the *coming* hour, not the one just passed: *halv nio* ("half nine") = 8:30, not 9:30. Quarter-hours use *kvart i*/*kvart över*. Official/written notices use the 24-hour clock read as e.g. "tretton och tjugofem."

#### Verbs of motion
*Åka* is the general verb for going somewhere by a named means of transport (tåg/buss/bil/skidor/skridskor etc.). *Resa* implies longer-distance or foreign/business travel. *Gå* is specifically "to walk" — the book flags this as a "false friend" since it looks like it should mean generic "go." When a modal verb already carries a directional expression, a second infinitive verb of motion can be dropped entirely (*Bill ska till Stockholm* = *Bill ska resa till Stockholm*).

#### Two-verb (modal) constructions
VERB1 is typically a modal (*kan, måste, ska*, or verbs behaving similarly such as *tänker*) which, unlike ordinary verbs, mostly lacks a present-tense *-r* ending; VERB2 is a plain infinitive. Fitted into the sentence pattern, VERB1 occupies the normal verb slot and VERB2 comes after the subject and any adverb.

## Lesson 4 — (Skåne/the Forsberg family holiday) (pp. 57–71)

Introduces: two-verb constructions with adverbs, objects/MPT-expressions in the sentence pattern, possessive pronouns, noun plurals, indefinite adjective declension, pronunciation of s/j/r/-rs/-rg/-lg/-ng, *du* vs. *ni* address, translating "to be" (finnas/ligga), compass points, ordinal numbers, months/dates, centuries/decades, compounding and abbreviation.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| familj -en -er | family | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| bruka/-r -de | usually (do something) | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| semester -n semestrar | holiday | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| juli | July | noun | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| besöka/-er -te | visit | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| landskap -et - | province | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| för...sedan | ago | adverb phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | pronounced "sen" |
| särskild -t -a | special, particular | adjective | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| dialekt -en -er | dialect | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| skånska | the Skåne dialect (of Swedish) | noun | regional | — | contemporary (source published 1996) | Skåne | regional | grammar_reference | n/a | n/a | book's own factual text explicitly states Skåne has "en särskild dialekt" (a distinct dialect) |
| långsamt | slowly | adverb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| längs | along | preposition | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| kust -en -er | coast | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| stanna/-r -de | stop | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| då och då | now and then | adverb phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| vandra/-r -de | wander | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| mysig -t -a | cosy, charming | adjective | colloquial | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | everyday-conversational adjective |
| fiskeby -n -ar | fishing village | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| titta/-r -de | look | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| slott -et - | castle | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| kyrka -n -or | church | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| äta/äter åt ätit | eat | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| lunch -en -er | lunch | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | pronounced "lunsch" |
| traditionell -t -a | traditional | adjective | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| skånsk -t -a | of Skåne, Scanian | adjective | regional | — | contemporary (source published 1996) | Skåne | regional | grammar_reference | n/a | n/a | — |
| gästgiveri -et -er | country inn | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| servera/-r -de | serve | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| god gott goda | good (of food; cf. bra) | adjective | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | distinct sense from generic "bra" |
| mat -en | food | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | no plural |
| böra/bör borde bort | ought to | verb (modal) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| smörgåsbord -et - | smörgåsbord (buffet) | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| portion -en -er | portion, helping | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| son -en söner | son | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| beställa/-er -de | order, book | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| hamburgare -n - | hamburger | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| slätt -en -er | plain | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| gård -en -ar | farm | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| halmtak -et - | thatched roof | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| tänka/-er -te | think, intend | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| övernatta/-r -de | stay the night | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| domkyrka -n -or | cathedral | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| make -n -ar | husband | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| absolut | definitely, really | adverb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| bokhandel -n bokhandlar | bookshop | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| inte alls | not at all | adverb phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| intresserad av | interested in | adjective phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| kultur -en -er | culture | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| leta efter | look for | verb phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| torg -et - | (town) square | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| utmärkt -a | excellent | adjective | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| skivaffär -en -er | record shop | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| skiva -n -or | record | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| hans/hennes/dess/deras | his/her(s)/its/their(s) | possessive pronoun | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | same form serves as possessive pronoun and possessive adjective |
| dubbelrum -met - | double room | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| oss | us | pronoun | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| enkelrum -met - | single room | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| vår/vårt/våra | our | possessive pronoun | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| säkert | certainly | adverb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| dusch -en -ar | shower | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | pronounced "dusch" (as spelled) |
| toalett -en -er | toilet | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| helst | preferably | adverb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| tro/-r -dde | believe | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| teve -n teveapparater | TV | noun (en) | colloquial | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | book notes elsewhere "en teve = en tv = en television" — three register-graded synonyms |
| program -met - | programme | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| kanal -en -er | channel | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| frukost -en -ar | breakfast | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| väckning -en | morning (wake-up) call | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| rätt | right; (here:) quite, rather | adjective/adverb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| tidigt | early | adverb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| postkontor -et - | post office | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| närhet -en | vicinity | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| skicka/-r -de | send | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| vykort -et - | picture postcard | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| precis om hörnet | just round the corner | adverb phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| namn -et - | name | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| adress -en -er | address | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| följa/-er -de | follow | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| hiss -en -ar | lift, elevator | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| pensionat -et - | guesthouse, B&B | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | from the cultural-vocabulary exercise |
| vandrarhem -met - | youth hostel | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| matsal -en -ar | dining room | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| herrtoalett / damtoalett | men's / ladies' toilet | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | signage register |
| garderob -en -er | wardrobe, cloakroom | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| kar -et - | bathtub | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | book's joke: confusing *kar* (bath) with *dusch* (shower) taps gets you wet unnecessarily |
| du / ni | you (sg. informal) / you (pl.; formerly formal sg.) | pronoun | core/formal | — | contemporary (source published 1996) | Sweden | national | grammar_reference | n/a | n/a | book gives a social-history note: the 1960s "du-reform" normalized *du* for nearly everyone; *ni* is now reviving as a polite singular ("Sir/Madam") especially in shops/restaurants and toward older people — a genuine sociolinguistic register fact, not a simple synonym pair |
| vill du/ni vara så snäll och... | would you be so kind as to... | phrase | formal | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | polite request formula |
| finnas/finns fanns funnits | exist, there is/are | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | one of several Swedish equivalents of "to be", used for existence |
| ligga/ligger låg legat | lie, be located | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | used for "to be" when expressing location, often of something lying flat/situated |
| norra/södra/östra/västra | northern/southern/eastern/western | adjective | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | adjectival compass forms |
| nord-/syd-/öst-/väst- | north-/south-/east-/west- | prefix | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | compounding prefix forms, e.g. Sydeuropa |
| i norr/söder/öster/väster | in the North/South/East/West | adverb phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| norrut/söderut/österut/västerut | northwards/southwards/eastwards/westwards | adverb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| tredje, fjortonde, femtonde | third, fourteenth, fifteenth | numeral (ordinal) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | ordinal-forming suffixes: -de for most, -nde for a subset including "20:de" etc. |
| maj | May | noun | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | from the months/dates section |
| bl a (bland annat) | inter alia, among other things | abbreviation | formal | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | book flags abbreviation as characteristic of Swedish factual/journalistic writing |
| kl (klockan) | o'clock | abbreviation | formal | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| t ex (till exempel) | e.g. | abbreviation | formal | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| t o m (till och med) | even, up to and including | abbreviation | formal | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| ca (cirka) | approximately, circa | abbreviation | formal | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| osv (och så vidare) | etc. | abbreviation | formal | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| dvs (det vill säga) | i.e. | abbreviation | formal | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| p g a (på grund av) | because of | abbreviation | formal | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| kr (kronor) | crowns (currency) | abbreviation | formal | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| grunda/-r -de | found | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| biskopssäte -t -n | bishopric, episcopal see | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| besökare -n - | visitor | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| riddare -n - | knight | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| konst -en -er | art | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| trädgård -en -ar | garden | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| friluftsmuseum | open-air museum | noun | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| samling -en -ar | collection | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| byggnad -en -er | building | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| bondstuga -n -or | peasant cottage | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| landsbygd -en | countryside | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| trä(d) | wood (material) | noun | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | compounding element, e.g. "träkyrka" |

### Grammar points

#### Full sentence pattern with objects, verb2, and MPT-expressions
Objects typically follow VERB2 (or the only verb); expressions of manner/place/time (MPT-expressions) typically follow the object, in the default order manner–place–time when more than one occurs together. Any single MPT-expression may instead be fronted (only one at a time), which triggers inversion of verb and subject as usual. The cumulative sentence template is: Front + Verb1 + (Subject) + Adverb + Verb2 + Object/Complement + MPT-expression.

#### Possessive pronouns = possessive adjectives
Unlike English (he/his vs. her/hers), Swedish uses one and the same form for both the possessive adjective and the standalone possessive pronoun: *hennes* = both "her" and "hers". Possessives: hans (his), hennes (her/hers), dess (its), deras (their/theirs).

#### Noun plurals: five main patterns
Based on examples seen so far: en-words typically add *-or* (dropping a final -a: kyrka→kyrkor) or *-ar* (bussar; dropping a final -e: skotte→skottar) or *-er* (turister, maskiner) or just *-r* (sko→skor); ett-words either add *-n* (äpple→äpplen) or take no plural ending at all (tåg, slott); some N-words likewise take no ending (en walesare→walesare); a few nouns (mat) have no plural at all.

#### Indefinite adjective declension
Basic (N-word) adjective form is unmarked; add *-t* for T-words (svenskt); add *-a* for any plural (svenska). A few common adjectives have irregular shortened plural/T-forms (vacker→vackert/vackra, dropping the e; gammal→gammalt/gamla, dropping the a and m). Indeclinable adjectives (e.g. bra) take no endings at all in any form.

#### Du/ni and the "du-reform"
Historically, *ni* could carry a condescending overtone when used in the singular, so the third person with title+name was often the only acceptable polite singular address; the "du-reform" of the late 1960s normalized *du* for nearly all singular address. *Ni* is now re-emerging as a genuinely polite singular equivalent of "Sir/Madam," especially in service contexts and toward older people — this is presented as a real, still-live sociolinguistic distinction, not a dead historical footnote.

#### finnas vs. ligga as "to be"
Beyond *vara*, Swedish uses *finnas* to assert existence ("Is there any beer left?") and *ligga* (literally "to lie") to assert location, especially of something situated/lying ("Lund ligger i Skåne" = "Lund is in Skåne").

#### Compounding and abbreviation
Compound nouns take the gender of their *last* element, and a linking *-s-* is sometimes inserted between elements (universitet+bibliotek→universitetsbibliotek; stad+hus→stadshus), while some compounds instead drop a final vowel on the first element (bonde+stuga→bondstuga). Compounds carry two stresses. Swedish factual/journalistic prose uses abbreviations heavily, and the book notes periods are now usually omitted from them.

#### Centuries, decades, and *-tal*
A century is named by its hundred-number plus "-talet" (1500-talet = the 16th century; note the Swedish number is one less than the English ordinal). *-tal* also forms decade names (40-talet = the 1940s) and approximate round numbers (ett trettital studenter ≈ "about thirty students").

## Lesson 5 — Matlagning (Cooking) (pp. 72–86)

Introduces: fronting, difficult end articles, predicting noun plurals systematically, a recipe ("Jansson's Temptation"), imperatives, pronunciation of dj-/hj-/lj-/gj- (silent initial letter), telephone phrases, object pronouns, indefinite adjective agreement after *någon/ingen/annan/vilken/all*, Stockholm.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| matlagning -en | cooking | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| fiskpinne -n -ar | fish finger | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| pommes frites | (potato) chips, fries | noun (plural) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | pronounced "pom fritt"; French loanword |
| socker -sockret | sugar | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| mjölk -en | milk | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| någon/något/några | some, any | determiner | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| kex -et - | biscuit | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| mumsa/-r -de | nibble, chew | verb | colloquial | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | onomatopoeic everyday-register verb |
| gärna | here: likes to, gladly | adverb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| potatischips | crisps | noun (plural) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | pronounced "-chips" |
| jordnöt -en -nötter | peanut | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| framför | in front of | preposition | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| fet -t -a | fat(ty) | adjective | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| dålig -t -a | bad; (here:) unhealthy | adjective | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| skräpmat -en | junk food | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| dricka/dricker drack | drink | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| sex gånger om dagen | six times a day | adverb phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| bakelse -n -r | pastry, filled cake | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| jämt | all the time | adverb | colloquial | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| smaka/-r -de | taste | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| riktig -t -a | real | adjective | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| visa/-r -de | show | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| hämta/-r -de | fetch | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| förkläde -t -n | apron | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | pronounced "förkle" |
| garderob -en -er | cupboard, wardrobe | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| hjälpa/-er -te | help | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| laga/-r -de | mend; (laga mat:) prepare food | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | book flags the two distinct senses explicitly |
| frestelse -n -r | temptation | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| behöva/-er -de | need | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| potatis -en -ar | potato | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| lök -en -ar | onion | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| burk -en -ar | can, jar | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| tjock -t -a | thick | adjective | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| grädde -n | cream | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| skorpsmulor | breadcrumbs | noun (plural) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| smör -et | butter | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| snaps -en | akvavit, spirits, schnapps | noun (en) | colloquial | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | everyday term; book gives a learned synonym "brännvin" |
| brännvin -et | akvavit, spirits, schnapps | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| ställa/-er -de | put | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| kylskåp -et - | refrigerator | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| sup -en -ar | dram, "tot" (of spirits) | noun (en) | colloquial | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| härlig -t -a | wonderful | adjective | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| husmanskost -en | plain, traditional home cooking | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| recept -et - | recipe; prescription | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| kokbok -en -böcker | cookbook | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| titta på | look at, watch | verb phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| vispgrädde -n | whipping cream | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| muttra/-r -de | mutter, mumble | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| gul -t -a | yellow | adjective | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| skala/-r -de | peel | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| skära/skär skar skurit | cut | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| tunn -t -a | thin | adjective | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| rak -t -a | straight | adjective | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| kant -en -er | edge | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| lägga/lägger lade lagt | lay, put | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| lager/lagret | layer | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| fortsätta/-er -satte -satt | continue | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| upprepa/-r -de | repeat | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| avsluta/-r -de | finish off | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| hälla/-er -de | pour | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| späda/-er -de | dilute; (here:) moisten | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| strö/-r -dde | sprinkle | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| sätta/sätter satte satt | place, set | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| klicka ut | dot with knobs (of butter) | verb phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| grädda/-r -de | bake | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| ugn -en -ar | oven | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| telefonsamtal -et - | telephone call | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| ögonblick -et - | moment | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| be/ber bad bett | ask (someone to do something) | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| viktig -t -a | important | adjective | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| mamma -n -or | mum, mummy | noun (en) | colloquial | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | family-register term for "mother" |
| inte sa väldigt | not so important | adjective phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| bjuda/bjuder bjöd bjudit | invite | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| middag -en -ar | dinner | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| trevlig -t -a | nice | adjective | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| vän -nen -ner | friend | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| vad synd | what a pity | interjection | colloquial | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | pronounced "synn" |
| ingen/inget/inga | no, none | determiner | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| barnvakt -en -er | babysitter | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| det går nog inte | it's probably not possible | phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| soffa -n -or | sofa | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| idé -n -er | idea | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| ses/sågs setts | meet, see each other | verb | colloquial | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | "vi ses" ("see you") is an everyday parting phrase |
| ö -n -ar | island | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| Östersjön | the Baltic (Sea) | proper noun | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| med rätta | justifiably | adverb phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| Gamla stan | the Old Town (Stockholm) | proper noun | core | — | contemporary (source published 1996) | Stockholm | local | grammar_reference | n/a | n/a | — |
| breda ut sig | spread out | verb phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| arbetarkvarter -et - | working-class area | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| förort -en -er | suburb | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| gränd -en -er | alley | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| Kungliga slottet | the Royal Palace | proper noun | core | — | contemporary (source published 1996) | Stockholm | local | grammar_reference | n/a | n/a | — |
| museum (ett museum, museer) | museum | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| familjenöje -t -n | family entertainment venue | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| flytta/-r -de | move | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| djur -et - | animal | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| lo -n -ar / lodjur -et - | lynx | noun (en/ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| älg -en -ar | elk, moose | noun (en) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| krigsskepp -et - | warship | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| bärga/-r -de | salvage | verb | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| ta igen sig | recover, rest | verb phrase | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |
| utekafé -et -er | pavement café | noun (ett) | core | — | contemporary (source published 1996) | — | — | grammar_reference | n/a | n/a | — |

### Grammar points

#### Fronting
Any non-subject word/phrase can be moved to the front of a main clause (not just MPT-expressions); this always forces inverted word order (subject after the verb). Fronting typically either sets a scene/situation (e.g. "I Lund...") or links back to a previous clause (e.g. "Sedan...", "Härefter..."), but can occasionally be used purely for contrast (fronting an object to contrast it with another clause's object).

#### Difficult end articles
N-words ending in unstressed *-el, -er, -or* take only *-n* in the definite singular (not *-en*): *bokhandel→bokhandeln*, *vinter→vintern*, *doktor→doktorn*. These same nouns drop the final vowel before adding a plural ending (*cykel→cyklar*), and T-words of the same shape drop the stem vowel before *-et* (*exempel→exemplet*, *fönster→fönstret*).

#### Predicting noun plurals systematically
Five general rules, usable once gender and stress pattern are known: (1) N-words with stressed final syllable and T-words with stressed final vowel add *-er* (affär→affärer, café→caféer); (2) N-words ending unstressed *-a* drop it and add *-or* (kaka→kakor); (3) N-words ending unstressed *-e* drop it and add *-ar* (pojke→pojkar); (4) T-words ending in an unstressed vowel add *-n* (äpple→äpplen); (5) T-words ending in a consonant take no plural ending (barn→barn). Additional fixed-ending correspondences: *-are* and *-er* (person nouns) take no plural ending; *-(n)ing* adds *-ar*; *-het* adds *-er*.

#### Imperatives and verb-conjugation groups
The imperative is simply the verb stem. Conjugation I (stem ends in -a): imperative = stem, infinitive = stem, present = stem+r (skala/skala/skalar). Conjugations II/IV (stem ends in a consonant): imperative = stem, infinitive = stem+a, present = stem+er (ställ/ställa/ställer). Conjugation III (stem ends in a vowel other than -a): imperative = stem, infinitive = stem, present = stem+r (strö/strö/strör). R-stem and l-stem verbs are conjugation II but take *no* ending in the present tense (skär, kör, mal). Imperatives (used for commands/recipes/instructions) can be softened with a polite tag, literally "and you are kind/nice": *"Skala potatisen, är du bussig!"*, *"Hjälp mig laga middag, är du snäll!"* — i.e. "Please peel...", "Please help...".

#### Object pronouns
Full paradigm: mig/mej (me), dig/dej (you sg.), er (you formal/pl.), honom (him), henne (her), den/det (it), oss (us), er (you pl.), dem/dom (them). The *-ej* spellings are flagged by the book as informal spellings that reflect actual pronunciation; *dom* likewise for *dem*.

#### Indefinite adjective agreement beyond noun+adjective
Besides ordinary noun-adjective agreement, the same indefinite -t/-a agreement pattern is echoed after *någon/något/några* (some/any), *ingen/inget/inga* (no), *en annan/ett annat/andra* (another/different), *vilken/vilket/vilka* (what a/which), and *all/allt/alla* (all). Adjectives also take -t when agreeing with the pronoun *det* (impersonal "it", e.g. weather statements) or with a whole infinitive phrase acting as subject (*Att dansa är roligt* — "Dancing is fun"; Swedish has no "-ing" gerund form to use instead). *Någonting* and *ingenting* ("something/anything", "nothing") behave grammatically like T-words/*det*.

