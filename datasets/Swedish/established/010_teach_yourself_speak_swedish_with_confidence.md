# Swedish — *Speak Swedish with Confidence* (Regina Harkin, Teach Yourself / Hodder Education, 2010; first published 2006 as *Teach Yourself Swedish Conversation*)

## Source note and IMPORTANT correction to the original task brief

This file covers **two PDF source files** for the same physical course package, and both turned
out to behave differently from what was originally assumed:

1. **Main course book** — `01.Teach Yourself Speak Swedish with Confidence.pdf` (97.9 MB, 75 PDF
   pages). **This source was originally flagged as having a real text layer. That is false.**
   `pdftotext` on the full 75-page file returns only 129 characters total, and `pdffonts` shows just
   3 decorative cover-art font instances with no usable character-to-glyph mapping. This is a
   genuine PDF gotcha, not a workaround-able one: the file is visually a clean, legible,
   born-digital-quality scan (not a degraded photocopy or used copy), but it carries **no real text
   layer at all**. **All content from this file below was vision-read**, by rendering all 75 PDF
   pages to PNG at 150dpi (`pdftoppm -png -r 150`) and reading each page image directly. All 75
   pages were read in full — not a sample.

2. **Companion "booklet"** — `01.Teach Yourself Speak Swedish with Confidence Booklet.pdf` (662 KB,
   40 PDF pages). This one does have a real, clean text layer (`pdftotext -layout` extracts ~186,700
   characters) — but **it is not a separate phrasebook/companion volume**, contrary to the original
   task brief. Internal running headers in the extracted text (e.g. `103403 TY SPEAKING SWEDISH.indd
   Spread 14 of 40 - Pages(6, 59)`) reveal this PDF is actually **the InDesign print-imposition
   ("signature") file for the front and back matter of the exact same book** — Title page, Copyright,
   Contents, Track listing, Cast, the "Listening skills: survival phrases" section, the full
   Swedish–English and English–Swedish glossaries, the "Essential vocabulary" tables (numbers,
   months, seasons, days of the week), the Subject index, and the Credits — laid out as 40 printer's
   spreads (each PDF page = two non-adjacent physical book pages, paired for saddle-stitch/perfect
   binding) rather than as sequential reading pages. Vision-reading the main book's own back-matter
   pages (PDF pages 57–75) confirmed this is the *same* content, not a distinct companion text —
   the two sources describe the same ~72-page book.

   **A new font-substitution PDF gotcha was found and decoded in this text layer**: the Swedish
   letter **å renders as a broken glyph pair, lowercase `a` + a degree sign (`°`)** — e.g. `tva°`
   for *två* (two), `ma° ndag` for *måndag* (Monday), `na°got` for *något* (something). Verified
   against 20+ known word/gloss pairs and cross-checked against the clean vision-read of the same
   words on the main book's own pages (where å renders perfectly, confirming this is a text-layer
   artifact specific to the booklet PDF, not an error in the book itself). Decoded throughout this
   file's Part 2.

Given finding #2, **Part 2 below is retitled "back matter (real text layer)"** rather than
"companion booklet," and its Vocabulary table presents the aggregated end-of-book glossary +
Essential Vocabulary tables, cross-validated against vision-reading the same material directly in
the main book (PDF pages ~57–72). Per the spec's non-redundant-supplement principle, **Part 1's
vocabulary table does not re-transcribe the full aggregated glossary a second time** — it covers the
vocabulary and phrases that surface specifically in the conversations, grammar "Insight" boxes, and
front-matter overview sections, which is where the colloquial/register material concentrates. Part 2
is the complete word-list coverage.

### Vision-reading guard note

No handwritten marginalia of any kind was found on any of the 75 pages — this is a clean
born-digital scan with no evidence of prior reader annotation. One recurring visual artifact **was**
found and is flagged per the spec's guard discipline so it is not mistaken for anything else: many
pages show a **faint ghosted duplicate of other printed page content bleeding through** behind the
page's own text (e.g. behind "Conversation 1" on p.6/PDF12, behind the Cast/Introduction pages).
This is consistently the same typeset font as the surrounding real content, at uniform low opacity,
and is judged to be a scan/registration artifact (likely bleed-through from a double-sided source
scan) — **not** handwriting, and not extracted as separate content. Printed page 50 (between
Conversation 3/10 and the "Listening skills" section) is genuinely blank in the book.

### Page-numbering note

PDF page number and the book's own printed page number diverge (PDF page 8 = printed "1"; PDF page
12 = printed "6"; etc., with the offset increasing slightly through the back matter because printed
page 50 is blank). Citations below use the book's own printed page numbers, as visible on each page.

---

## PART 1: Main Course Book (vision-read, all 75 PDF pages / printed pp. i–72ish)

### Coverage note

This part covers: the Introduction and "Only got 5/10 minutes?" overview essays (pp. 1, 3–5), all
ten numbered Conversations with their Parts 1–2 (pp. 6–29), all ten "Conversation 3/N" extended
dialogues (pp. 30–49), the "Listening skills: survival phrases" section (p. 51), and all ~16
grammar "Insight" boxes embedded throughout. Repeated/near-identical drill exchanges across parallel
dialogues (e.g. the many near-identical "What's your name? / Where do you come from?" exchanges)
are not separately tabulated beyond their first occurrence.

### Vocabulary (Part 1 — dialogue, overview-essay, and survival-phrase vocabulary not already
covered by Part 2's aggregated glossary)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| slang | slang | noun | core | — | contemporary (source published 2006/2010) | — | — | grammar_reference | n/a | verified | Cited by the source itself as an English loanword into Swedish, in the "Only got 5/10 minutes?" overview essay (p. 3–4). |
| snob | snob | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | verified | Same passage; English loanword into Swedish. |
| smart | smart | adjective | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | verified | Same passage; English loanword into Swedish. |
| pilsner | pilsner (lager beer) | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | verified | Same passage; cited as a German loanword into Swedish. |
| pudel | poodle | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | verified | Same passage; German loanword into Swedish. |
| ombudsman | ombudsman | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | verified | Cited as a Swedish word borrowed INTO English ("the political ombudsman"), p. 3–4. |
| smörgåsbord | smörgåsbord | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | verified | Same passage; Swedish word borrowed into English ("the more culinary smörgåsbord"). |
| pratar | talk(s)/speak(s) (present tense, all persons) | verb | core | — | — | — | — | grammar_reference | n/a | verified | Used to illustrate that Swedish present-tense verbs do not inflect for person/number. |
| en katt | a cat | noun phrase | core | — | — | — | — | grammar_reference | n/a | verified | Worked example of an *en*-word, p. 4–5. |
| ett bord | a table | noun phrase | core | — | — | — | — | grammar_reference | n/a | verified | Worked example of an *ett*-word, p. 4–5. |
| Hej då! | bye, bye | interjection | colloquial | — | — | — | — | grammar_reference | n/a | verified | Glossed in-text as a casual farewell, closing both the 5- and 10-minute overview essays. |
| vit tröja / vitt hus / vita tröjor | white top / white house / white tops | adjective phrase | core | — | — | — | — | grammar_reference | n/a | verified | Worked example of *en/ett* adjective agreement (-t for ett-words, -a for plurals), p. 16. |
| en gång till | one more time, again | phrase | core | — | — | — | — | grammar_reference | n/a | verified | Survival phrase list, p. 51. |
| är du snäll | please (lit. "are you kind") | phrase | core | — | — | — | — | grammar_reference | n/a | verified | Survival phrase list, p. 51; politeness marker appended to a request, e.g. "kan du öppna dörren, är du snäll?" |
| för sent | too late | phrase | core | — | — | — | — | grammar_reference | n/a | verified | Survival phrase list, p. 51. |
| vad kan jag hjälpa till med? | how can I help? | phrase | core | — | — | — | — | grammar_reference | n/a | verified | Survival phrase list, p. 51; also spoken in-dialogue by the policeman, p. 34–35. |
| förstår du? | do you understand? | phrase | core | — | — | — | — | grammar_reference | n/a | verified | Survival phrase list, p. 51. |
| vill du ha hjälp? | do you want help? | phrase | core | — | — | — | — | grammar_reference | n/a | verified | Survival phrase list, p. 51. |
| jag förstår inte | I don't understand | phrase | core | — | — | — | — | grammar_reference | n/a | verified | Survival phrase list, p. 51. |
| jag är inte säker | I'm not sure | phrase | core | — | — | — | — | grammar_reference | n/a | verified | Survival phrase list, p. 51. |
| är det gratis? | is it free (not paying)? | phrase | core | — | — | — | — | grammar_reference | n/a | verified | Survival phrase list, p. 51; source explicitly distinguishes this from "unoccupied." |
| är det ledigt? | is it free (unoccupied)? | phrase | core | — | — | — | — | grammar_reference | n/a | verified | Survival phrase list, p. 51; contrastive pair with the entry above. |
| det är upptaget | it's occupied/taken | phrase | core | — | — | — | — | grammar_reference | n/a | verified | Survival phrase list, p. 51. |
| Glad Påsk | Happy Easter | phrase | core | — | — | — | — | grammar_reference | n/a | verified | Survival phrase list, p. 51; fixed seasonal greeting. |
| Gott Nytt År | Happy New Year | phrase | core | — | — | — | — | grammar_reference | n/a | verified | Survival phrase list, p. 51; fixed seasonal greeting. |
| schysst | fair, nice, cool, decent | adjective/interjection | **colloquial** | — | — | — | — | grammar_reference | n/a | verified | Dialogue p. 20: Lars exclaims "Schysst!" when Anders offers to sort out his missing towel/trunks. Appears a second time in the glossary paired with *snäll*/*vänlig* for "kind." A well-known everyday Swedish colloquialism (ultimately from German *gerecht*), explicitly used here as a one-word approval interjection, not just an adjective. |
| nå't | contraction of något ("something") | pronoun | **colloquial** | — | — | — | — | grammar_reference | n/a | verified | Dialogue p. 20–21: "Ska vi göra nå't ikväll?" — spoken-register clipped form, not used in the written/citation-form glossary entries. |
| tja | well, hmm (hesitation/filler) | interjection | **colloquial** | — | — | — | — | grammar_reference | n/a | verified | Dialogue p. 21: "Tja, vi kan gå på bio eller ta en öl?" — discourse filler opening a suggestion. |
| löning | payday, wages (casual) | noun | **colloquial** | — | — | — | — | grammar_reference | n/a | verified | Dialogue p. 24: "Ja, det är löning idag. Alla vill gå ut." The formal glossary headword is *lön*; *löning* is explicitly bracketed as the colloquial variant (see Part 2). |
| Nämen hej! | well hey!/oh hi! (surprised greeting) | interjection | **colloquial** | — | — | — | — | grammar_reference | n/a | verified | Spoken twice in dialogue (p. 25, p. 36) as a warm surprised greeting between friends. |
| fika / fikar / fikabröd / fikapaus | to have coffee (and a snack) / coffee break pastry / coffee break | verb/noun | **colloquial** | — | — | — | — | grammar_reference | n/a | verified | Insight box (~p. 40) explicitly glosses this as informal/everyday language: "ett fik" (a coffee place), "gå på fik" (go for coffee), "fikabröd" (something to eat with your coffee), "en fikapaus" (a coffee break). One of Swedish's best-known culturally loaded colloquialisms — the institution of a scheduled coffee/social break. |
| [sitteru] | colloquial fused pronunciation of "sitter du" (are you sitting) | — | **colloquial (pronunciation)** | — | — | — | — | grammar_reference | n/a | verified | Bracketed phonetic respelling in-dialogue (p. 46), showing casual enclitic fusion of verb + "du." |
| [eru] | colloquial fused pronunciation of "är du" (are you) | — | **colloquial (pronunciation)** | — | — | — | — | grammar_reference | n/a | verified | Bracketed phonetic respelling in-dialogue (p. 46), same enclitic-fusion pattern as above. |
| [blirunte] | colloquial fused pronunciation of "blir du inte" (won't you be) | — | **colloquial (pronunciation)** | — | — | — | — | grammar_reference | n/a | verified | Bracketed phonetic respelling in-dialogue (p. 44), same pattern. |
| [regnare] | colloquial fused pronunciation of "regnade det" (did it rain) | — | **colloquial (pronunciation)** | — | — | — | — | grammar_reference | n/a | verified | Bracketed phonetic respelling in-dialogue (p. 46). |
| [ståre] | colloquial fused pronunciation of "står det" (does it say/stand) | — | **colloquial (pronunciation)** | — | — | — | — | grammar_reference | n/a | verified | Bracketed phonetic respelling in-dialogue (p. 46). |
| [dåmme] | colloquial fused pronunciation of "de är" (they are) | — | **colloquial (pronunciation)** | — | — | — | — | grammar_reference | n/a | verified | Bracketed phonetic respelling in-dialogue (p. 42); cross-validated against the identical bracketed form found independently in Part 2's real-text-layer source, raising confidence to `verified`. |
| [svärje] | colloquial/connected pronunciation of "Sverige" (Sweden) | — | colloquial (pronunciation) | — | — | — | — | grammar_reference | n/a | verified | Bracketed pronunciation guide in the glossary, cross-validated across both sources. |
| [ajö] | pronunciation of "adjö" (goodbye) | — | colloquial (pronunciation) | — | — | — | — | grammar_reference | n/a | verified | Bracketed pronunciation guide, cross-validated across both sources. |
| snabel-a | the "@" symbol, spoken (lit. "trunk-a," i.e. elephant's-trunk A) | noun | core | — | — | — | — | grammar_reference | n/a | verified | Spoken-aloud email address in dialogue, p. 32: "annapettersson@svbuss.se" is read as "...snabel-a svbuss punkt se." |
| punkt | dot/period (in a spoken email or web address) | noun | core | — | — | — | — | grammar_reference | n/a | verified | Same spoken email-address convention, p. 32. |

### Grammar points

#### 1. Hard vs. soft g, k, sk (pronunciation)
Two paired Insight boxes (pp. 8, 13) state the core allophony rule of Swedish orthography: **g, k,
and sk are "hard"** (g as in *go*, k as in *kitchen*, sk as in *sky*) before the back vowels **a, o,
u, å** (e.g. *god*, *kan*, *ska*), but **"soft"** (g as the y in *yellow*; k as the sh in *shower*)
before the front vowels **e, i, y, ä, ö** (e.g. *gör*, *kör*). A third box (p. 21) walks through the
articulatory mechanics of the soft **sk** sound specifically (start articulating k, stop before full
closure, "imitate a soft breeze"), pointing to *skönt* as the example to listen for.

#### 2. å, ä, ö pronunciation
p. 10: the three extra Swedish vowel letters are anchored to memorable example words: **å** as in
*går* (walks), **ä** as in *här* (here), **ö** as in *öl* (beer).

#### 3. r + consonant retroflex rule
p. 12: **r followed by s is pronounced as a single sound** (the *sh* in *shower* — demonstrated with
"Anders"). The same one-sound rule extends to **r + d, l, n, t**, which fuse into thick
retroflex *d, l, n, t* sounds (examples: *bord*, *Karl*, *barn*, *vart*) rather than a separately
pronounced r.

#### 4. Two-gender noun system (en-words / ett-words)
p. 5: Swedish nouns fall into two grammatical genders/declension classes, **en-words** (e.g. *en
katt*, "a cat") and **ett-words** (e.g. *ett bord*, "a table"). The glossary's own front matter
(found in Part 2) states its indicating convention explicitly: an *en*-word's entry is left
unmarked (just the noun), while an *ett*-word is marked with `-et` or `-t` after the headword.

#### 5. Adjective agreement
p. 16: a predicate/attributive adjective modifying an **ett-word** takes a **-t** ending (*ett vitt
hus*, "a white house," vs. *en vit tröja*, "a white top"). **Plural** nouns of either gender take an
**-a** ending on the adjective (*två vita tröjor*, "two white tops"; *många vita hus*, "many white
houses").

#### 6. Modal + infinitive construction
p. 16: when a sentence has two verbs in sequence (e.g. after *kan*, *ska*, *vill*, *skulle*), the
**second verb stays in the infinitive**, not the present tense — contrasted explicitly: **Jag kan
inte simma** (not *simmar*) is the correct form ("Simma, of course!").

#### 7. går vs. åker (motion verbs)
p. 18 Insight box: **går** specifically means moving under one's own legs (walking), while **åker**
covers any form of vehicular transport (*åker bil/tåg/båt/flygplan/buss* — by car/train/boat/
plane/bus). The example given: if someone says **Jag åker hem nu**, you know for certain they are
not walking home. This distinction recurs as a glossary dual-entry (*går* = go/walk vs. *åker* = go/
travel) in Part 2.

#### 8. Reciprocal -s verbs
p. 20 Insight box: Swedish marks a reciprocal ("each other") sense by adding **-s** to certain verb
stems rather than an r-ending: **träffas** (meet each other), **ses** (see each other — "Vi ses!" =
"see you around"), **hörs** (hear from each other — "Vi hörs!" = "we'll be in touch"), and **kramas**
(hug each other).

#### 9. Imperative formation
p. 22 Insight box: the imperative is formed by stripping the present-tense ending. **-ar verbs**
drop the **r** (*pratar* → *prata!*, "talk!"). **-er verbs** drop the **er** (*svänger* → *sväng!*,
"turn!").

#### 10. Street-address word order
p. 34 Insight box: in a Swedish address, **the house/building number follows the street name**
rather than preceding it (*Bondegatan 51*, not *51 Bondegatan*).

#### 11. Day-of-the-week preposition (future vs. past)
p. 36 Insight box: to refer to a specific day **coming up**, use the preposition **på** (*på
lördag*, "this coming Saturday"). To refer to a day **already past**, switch to **i** and add an
**-s** suffix to the day name (*i lördags*, "last Saturday").

#### 12. Telephone-number pairing convention
p. 30 Insight box: Swedish phone numbers are read aloud **in pairs of digits**, not one digit at a
time. A six-digit number like 256871 is both written and spoken as **25 68 71** (*tjugofem
sextioåtta sjuttioett*). A leading odd digit in a seven-digit number is read as a three-digit group
first: 7443564 → **744 35 64** (*sjuhundrafyrtiofyra trettiofem sextiofyra*).

#### 13. Loanwords as a learnability cue
pp. 3–5 (the "Only got 5/10 minutes?" overview): the source explicitly uses loanword direction as a
pedagogical hook — English loans *into* Swedish (*slang*, *snob*, *smart*), German loans *into*
Swedish (*pilsner*, *pudel*), and Swedish loans *into* English (*ombudsman*, *smörgåsbord*) — framed
as evidence that an English speaker already has partial vocabulary access.

#### 14. Verbs do not inflect for person or number
pp. 3–5: explicitly stated as a learnability simplification — the present tense of *prata* (talk) is
always **pratar**, regardless of grammatical subject (I/you/he/she/it/we/you-plural/they).


---

## PART 2: Back Matter — Aggregated Glossaries, Essential Vocabulary, and Subject Index (real text layer)

### Coverage note

As explained above, this is **not** a separate phrasebook — it is the same book's own back matter
(Swedish–English glossary, English–Swedish glossary, "Essential vocabulary" tables, Subject index,
Track listing, Cast, Credits), extracted from the one source file among the two that has a genuine
PDF text layer. The glossary is the book's own aggregation of **every word used across all twenty
conversations** (ten main Conversations + ten "Conversation 3/N" extended dialogues), so it
substantially supersets Part 1's own vocabulary coverage; Part 1 intentionally did not re-list the
~290 words already captured below, per the spec's non-redundant-supplement guidance. All terms below
were cross-validated by also vision-reading the book's own equivalent back-matter pages (PDF pages
~57–72, printed pp. ~53–69), which independently confirmed spelling accuracy — the only discrepancy
found was the "a°"-for-å text-layer cipher described above, now decoded. The glossary's own front
matter (p. ~53) states its *en*/*ett* marking convention directly: an unmarked noun is an *en*-word;
`-et` or `-t` after the headword marks an *ett*-word (e.g. *en adress*, but *namn, -et*).

Administrative front/back matter not relevant to vocabulary or grammar (Credits, Cast, Track
listing, the CEFR self-assessment chart, ordering/legal boilerplate) is intentionally **not**
tabulated — out of scope per the coverage rule.

### Vocabulary — Essential vocabulary tables (numbers, months, seasons, days, clock time)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| ett, första | one, first | numeral | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Cardinal/ordinal pair; real text layer, no vision-reading needed for this entry. |
| två, andra | two, second | numeral | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Text-layer rendered this as "tva°"; decoded to *två*. |
| tre, tredje | three, third | numeral | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| fyra, fjärde | four, fourth | numeral | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| fem, femte | five, fifth | numeral | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| sex, sjätte | six, sixth | numeral | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| sju, sjunde | seven, seventh | numeral | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| åtta, åttonde | eight, eighth | numeral | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Decoded from "a° tta"/"a° ttonde". |
| nio, nionde | nine, ninth | numeral | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| tio, tionde | ten, tenth | numeral | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| elva, elfte | eleven, eleventh | numeral | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| tolv, tolfte | twelve, twelfth | numeral | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| tretton…nitton (13–19) | thirteen…nineteen | numeral | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Regular pattern, -ton suffix; not enumerated row-by-row (regular/predictable formation, per coverage-rule drill-skipping). |
| tjugo, tjugonde | twenty, twentieth | numeral | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| tjugoett [tjuett] | twenty-one | numeral | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Bracketed colloquial-contraction pronunciation note in the source itself. |
| trettio, fyrtio, femtio, sextio, sjuttio, åttio, nittio | thirty, forty, fifty, sixty, seventy, eighty, ninety | numeral | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Regular -tio decade pattern. |
| hundra | hundred | numeral | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| tusen | thousand | numeral | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| januari–december | January–December | noun (12 items) | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Standard Latinate month names, transparent cognates; not individually row-listed. |
| vår, -en | spring | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| sommar, -en | summer | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| höst, -en | autumn/fall | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| vinter, -n | winter | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| måndag [månnnnnda] | Monday | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Bracketed form shows casual elided/drawled pronunciation, dropping the written -dag syllable's clarity. |
| tisdag [tiiiiista] | Tuesday | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Same colloquial-pronunciation bracketing convention. |
| onsdag [onnnnnsta] | Wednesday | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| torsdag [tooooorsta] | Thursday | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| fredag [freeeeeda] | Friday | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| lördag [lööööörda] | Saturday | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| söndag [sönnnnnda] | Sunday | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| kvart över/i; halv; fem över/i halv | quarter past/to; half past; five past/to the half-hour | time-telling phrase | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Full clock-reading system tabulated 3.00–4.00 in five-minute steps on p. 67; Swedish counts toward the *next* half-hour/hour (e.g. "fem i halv fyra" = 3.25, lit. "five to half four"), a genuinely different clock-reading logic from English. |

### Vocabulary — Aggregated Swedish–English / English–Swedish glossary (pp. ~53–66)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| adjö [ajö] | goodbye | interjection | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Bracketed pronunciation note. |
| adress, -en | address | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| aldersgräns, -en | age limit | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| apotek, -et | pharmacy | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | ett-word. |
| äpple, -t | apple | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| bar, -en | bar | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| barn, -et | child | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| båt, -en | boat | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| behöver | need(s) | verb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| berg- och dalbana, -n | rollercoaster | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Lit. "mountain-and-valley track." |
| beställer | order(s) | verb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| betalar; får jag betala? | pay(s); can I pay? | verb/phrase | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| bild, -en | picture | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| biljett, -en | ticket | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| bio: gå på ~ | cinema; go to the cinema | noun/phrase | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| biograf, -en | cinema theatre (building) | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Distinct headword from *bio* above — the glossary itself distinguishes the institution/event sense from the building. |
| blir: det ~ 180 kronor | is/becomes; that'll be 180 kronor | verb/phrase | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | *bli* used idiomatically for stating a price. |
| blomma, -n | flower | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| blå, -tt | blue | adjective | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| blåser: det ~ | wind; it's windy | verb/phrase | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Impersonal weather construction. |
| bokningsbekräftelse, -n | booking confirmation | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| Bankomat, -en | cash/ATM machine | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Originally a Swedish bank-cooperative trademark, now the generic everyday word for "ATM." |
| bord, -et | table | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| borta: här ~; där ~ | away; over here; over there | adverb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| bråttom | (in a) hurry | adjective/predicate | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| bulle, -n | bun | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| buss, -en | bus | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| busschaufför, -en | bus driver | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| både … och … | both … and … | conjunction | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| bär | carr(ies) | verb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| centrum, -et | centre | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| cigarrett, -en | cigarette | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| cola, -n | cola | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| dagens rätt | chef's special / dish of the day | noun phrase | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Lit. "today's dish"; fixed menu-ordering phrase, heard in-dialogue as "Två 'dagens rätt' tack!" |
| dans, -en | dance | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| den här | this (one) | pronoun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| dotter, -n | daughter | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| drink, -en | (a) drink | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| drömmer | dream(s) | verb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| då | then, in that case | adverb/conjunction | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| där | there | adverb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| efteråt | afterwards | adverb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| eftermiddag, -en | afternoon | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| efternamn, -et | surname | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| efterrätt, -en | dessert | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| epostadress, -en | email address | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| familj, -en | family | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| film, -en | film, camera film | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| fin, -t | nice | adjective | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| flaska, -n | bottle | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| flicka, -n; tjej, -en | girl | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Glossary gives two near-synonyms; *tjej* is the more everyday/colloquial of the two in actual modern usage, though the source does not explicitly register-tag it. |
| följer; ~ med | follow(s); come(s) along | verb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| för; för långt | for, to; too far | preposition/adverb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| för … sen | … ago | postposition phrase | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| förlåt | pardon, I'm sorry | interjection | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| förmiddag, -en | morning (before noon) | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| förra: ~ året | last; last year | adjective | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| förresten | by the way | adverb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| försenad | delayed | adjective | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| först | first, at first | adverb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| förut | before | adverb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| förälder, -n; mina föräldrar | parent; my parents | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| från | from | preposition | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| frukost, -en | breakfast | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| frukt, -en | fruit | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| full, -t | full, fully booked | adjective | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Dual sense ("I'm full" / "the hotel is fully booked"). |
| gata, -n | street | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| glas, -et | glass | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| glass, -en | ice cream | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Minimal pair with *glas* above (gender/spelling distinguish "glass" from "ice cream"). |
| god kväll | good evening | phrase | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| gör: det ~ inget | do(es); it doesn't matter | verb/phrase | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| går | go(es), walk(s) (on foot) | verb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | See Part 1 Grammar point 7 — contrastive with *åker*. |
| går över | cross(es), go(es) over | verb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| gärna: jag skulle ~ | gladly; I'd love to | adverb/phrase | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| grad, -en: nittio ~ | degree; ninety degrees | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Used of sauna temperature in-dialogue. |
| grattis på födelsedagen [fölsedan] | happy birthday | phrase | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Bracketed form shows the casual run-together pronunciation dropping internal syllable clarity, parallel to the day-of-week bracketing pattern. |
| gravlax, -en | marinated/cured salmon | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Named Swedish dish. |
| grön, -t | green | adjective | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| grönsak, -en | vegetable | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| gul, -t | yellow | adjective | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| halvtimme, -n | half an hour | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| hallå | hello (specifically answering the phone) | interjection | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Glossary distinguishes this register-specific greeting from plain *hej*. |
| handduk, -en | towel | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| hej då | goodbye, bye | interjection | colloquial | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Everyday casual farewell, used throughout every dialogue in the book. |
| hel, -t | whole | adjective | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| här | here | adverb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| höger: till ~ | right; to/on the right | noun/adverb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| hotell, -et | hotel | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| timme, -n | hour | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| hus, -et; hemma hos Anna | house; at/in Anna's house | noun/phrase | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| hur är det? | how are you? | phrase | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| huvudvärkstablett, -en | paracetamol/headache tablet | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Lit. "headache tablet." |
| igår | yesterday | adverb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| ikväll | tonight | adverb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| ingår | is included | verb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| inträde, -t | entrance fee | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| istället | instead | adverb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| jämnt: det är ~ | even; keep the change | adjective/phrase | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Idiomatic use of "even" for "no change needed." |
| jättetrevlig, -t | very pleasant/enjoyable | adjective | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | *jätte-* is a productive colloquial intensifying prefix ("really/super-"), though the glossary tags the whole compound as a plain headword rather than flagging the prefix's register. |
| journalist, -en | journalist | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| kaffe, -t | coffee | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| kall, -t | cold | adjective | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| kanelbulle, -n | cinnamon bun | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| kasse, -n | shopping bag | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| kassa, -n: i kassan | cash register; at the register/till | noun/phrase | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| ketchup, -en | ketchup | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| kexchoklad, -en | chocolate wafer bar | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| kille, -en | guy | noun | colloquial | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Everyday informal word for "guy/boy," used throughout dialogue (e.g. "tjugofem för killar"). |
| kjol, -en | skirt | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| klass, -en | class | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| klocka, -n | clock, (the) time | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| kläder: barnkläder | clothes; children's clothes | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| kommer ihåg | remember(s) | verb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| kompis, -en | friend, mate, buddy | noun | colloquial | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Everyday informal register for "friend" — the glossary's own English gloss ("friend, mate") signals this, though the usage-tier tag isn't explicit in-source. |
| konditori, -et | tea shop/café (pastry café) | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| korsning, -en | crossing, junction | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| kort, -et | card | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| krona, -n | crown, krona (currency) | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Compare *spänn* (colloquial), below. |
| kudde, -n | pillow | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| kväll, -en | evening | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| kvällstidning, -en | evening paper | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| kvinna, -n | woman | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| kö, -n | queue | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| köper | buy(s) | verb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| kör: kan du köra mig till …? | drive(s); can you drive me to …? | verb/phrase | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| körkort, -et | driver's licence | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| köttbulle, -n | meatball | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| laxfilé, -n | salmon fillet | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| ledig, -t, -a | free, unoccupied | adjective | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| lite: det var så ~ så | little; "you're welcome"/"don't mention it" | adverb/phrase | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Idiomatic fixed response, lit. "it was so little so." |
| lön, -en (löning) | wages (payday) | noun | core / **colloquial (löning)** | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Glossary itself parenthesizes the colloquial variant *löning*, confirmed in dialogue usage (Part 1). |
| länge: så ~ | long; in the meantime | adverb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| lägger | put(s) (lying down) | verb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| lämnar: ~ in | leave(s); hand(s) in | verb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| läser | read(s), stud(ies) | verb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| låter | sound(s) | verb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| lunch, -en | lunch | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| lust: ha ~ att göra något | feel like doing something | noun/phrase | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| mamma, -n | mum, mother | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| mat, -en | food | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| match, -en | match (sport) | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| meter, -n | metre | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| middag, -en | dinner | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| midsommarafton, -en [missommarafton] | Midsummer's Eve | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Bracketed casual assimilated pronunciation; Midsummer's Eve is a major Swedish cultural holiday, cross-referenced with the "dans på bryggan" folk-custom idiom noted below. |
| mjölk, -en | milk | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| mobil, -en | mobile phone | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| mobilnummer, -ret | mobile number | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| mot: AIK ~ Djurgården | against; AIK against Djurgården | preposition | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Example uses two real Stockholm sports-club names. |
| mål, -et | goal | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| många: ~ gånger | many; many times | adjective | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| måste | must | modal verb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| mätt: jag är ~ | full (from eating); I'm full | adjective/phrase | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| natt, -en (pl. nätter) | night | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Irregular plural explicitly noted by the glossary. |
| nej; nä | no | interjection | core / **colloquial (nä)** | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Glossary gives both forms as a pair; *nä* is the casual everyday variant (parallel to English "no"/"nah"). |
| någon, något, några | some(one/thing) | pronoun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Three-way en-word/ett-word/plural pronoun set. |
| något annat? | anything else? | phrase | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| nyckel, -n | key | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| när | when, at what time | adverb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| och [å, åck] | and | conjunction | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Bracketed casual-pronunciation variants of "och." |
| också | also, too | adverb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| ojdå | oh dear | interjection | colloquial | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| ostsmörgås, -en | cheese sandwich | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| paket, -et | packet | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| pappa, -n | dad, father | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| person, -en | person | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| pizzeria, -n | pizzeria | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| plånbok, -en | wallet | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| pojke, -n | boy | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| polis, -en | policeman | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| potatis, -en | potato | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| på | on | preposition | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| påtår, -en | refill (of coffee) | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Culturally specific — free coffee refill, tied to the *fika* custom. |
| päron, -et | pear | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| promenad, -en: ta en ~ | walk (noun); go for a walk | noun/phrase | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| radiobil, -en | bumper car | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| restaurang, -en | restaurant | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| ris, -et | rice | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| rolig, -t | fun | adjective | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Comparative *roligare* ("more fun") seen in-dialogue. |
| röd, rött | red | adjective | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| rödvin, -et | red wine | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| räcker | is enough, lasts | verb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| rätt, -en | course (of a meal) | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| saffran, -et | saffron | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| säger [säjer] | say(s) | verb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Bracketed form shows the standard colloquial/connected pronunciation dropping the written -g-. |
| säljer | sell(s) | verb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| schysst; snäll, -t; vänlig, -t | kind | adjective | core / **colloquial (schysst)** | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | See Part 1 flagship colloquial finding — *schysst* used as a one-word exclamation of approval in dialogue, not just "kind" in the glossed sense. |
| sen: vi är ~a | late; we're late | adjective | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| senap, -en | mustard | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| sida, -n | side | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| sill, -en | herring | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| simhall, -en | swimming pool (building) | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| simmar: gå och simma | swim(s); go for a swim | verb/phrase | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| skål | cheers | interjection | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Drinking toast. |
| skålar | toast(s) (verb) | verb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| skåp, -et | locker, cupboard | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| skinksmörgås, -en | ham sandwich | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| skön, -t | nice, comfortable | adjective | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| skola, -n | school | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| smak, -en | taste, flavour | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| snaps, -en | snaps (schnapps/aquavit) | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| snäll, -t | kind | adjective | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Also used as a politeness-marker tag, "är du snäll" (see Part 1). |
| snöar: det ~ | snow(s); it's snowing | verb/phrase | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| sol, -en | sun | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| solig, -t | sunny | adjective | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| som | as, like | conjunction | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| sommar, -en | summer | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Duplicate headword with the Essential Vocabulary season table; both occurrences kept since both are source-attested. |
| son, -en | son | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| sort, -en | type, species | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| spänn | krona (currency), "buck(s)" | noun | **colloquial/slang** | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Glossary itself explicitly labels this `(informal)` — the single clearest source-marked slang item found across the whole book. Direct functional parallel to English "buck(s)" for dollars. Confirmed in dialogue usage, p. 24: "räcker det med hundra spänn?" ("will a hundred bucks be enough?"). |
| stannar | stop(s) | verb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| station, -en | station; stop | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| stängd, stängt | closed | adjective | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| stänger | close(s) | verb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| står: vad ~ det | stand(s); what's the score | verb/phrase | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Idiomatic sports-score usage. |
| står: det ~ på borden | stand(s); it's on the tables | verb/phrase | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| Sverige [svärje] | Sweden | proper noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Bracketed connected-speech pronunciation. |
| svår, -t | difficult | adjective | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| svänger | turn(s) | verb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Imperative *sväng!* cited in Part 1 Grammar point 9. |
| syster, -n | sister | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| så | so, therefore | adverb/conjunction | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| stycke, -t: tjugo ~n | piece; twenty of us/of them | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Counting-people idiom. |
| ta°g, -et → tåg, -et | train | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| tack för senast | thanks (fixed phrase used after a party/dinner/last time you met) | phrase | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | No direct one-word English equivalent — a culturally specific fixed-phrase gratitude convention. |
| tack så mycket | thanks a lot | phrase | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| tandkräm, -en | toothpaste | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| tänker | think(s), contemplate(s) | verb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| tar | take(s) | verb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| tappar | drop(s), lose(s) | verb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| taxichaufför, -en | taxi driver | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| t-bensstek, -en | T-bone (steak) | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| te, -t | tea | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| telefonnummer, -ret | telephone number | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| thriller, -n | thriller | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | English loanword, unmodified. |
| tidning, -en | newspaper | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| tja (in subject index) | well, yes (hedging) | interjection | **colloquial** | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Cross-referenced in Part 1 (dialogue) and listed as a subject-index entry here. |
| nja | yes (hesitant) | interjection | **colloquial** | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Hedging particle, distinct headword from *tja*; both appear in the Subject index and in-dialogue (e.g. the hotel receptionist's "Nja, det kanske blir svårt"). |
| toa: gå på ~ | toilet, loo; go to the toilet | noun/phrase | **colloquial** | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | *Toa* is the everyday clipped form of *toalett*. |
| toalett (full form, implied) | toilet | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Full/formal form, inferred from the *toa* clipping above — not separately headworded by the glossary, included here for completeness of the clipping pair. |
| torg, -et | square (place) | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| trappa, -n | stairs | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| träffar, träffas | meet(s), meet (each other) | verb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | See Part 1 Grammar point 8. |
| tröja, -n | top, sweater | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| tung, -t | heavy | adjective | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| tunnelbana, -n | metro, underground | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| tusenlapp, -en | thousand-krona note | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| tyvärr | unfortunately | adverb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| typiskt | typical | adjective | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| under | under | preposition | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| undrar | wonder(s) | verb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| ursäkta | excuse me | interjection | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| vacker, -t | beautiful | adjective | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| vad: ~ heter du?; ~ blir det?; ~ är det? | what; what's your name?; what will that be?; what is it? | pronoun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| väder: vad är det för ~? | weather; what's the weather like? | noun/phrase | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| vågar | dare(s) | verb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| vanlig, -t | normal, ordinary | adjective | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| välkomna | welcome | adjective/interjection | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| vänlig, -t | kind | adjective | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| vänster: till ~ | left; to/on the left | noun/adverb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| varför | why | adverb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| väntar | wait(s) | verb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| varifrån, var … ifrån | from where; where do you come from? | adverb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| åker | go(es), travel(s) (by vehicle) | verb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | See Part 1 Grammar point 7. |
| åkkupong, -en | ride ticket (for a funfair/theme park) | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| åt | for | preposition | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| varsågod, -a | here you are | phrase | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| är | am, are, is | verb (copula) | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| äter – åt – ätit | eat – ate – eaten | verb (principal parts) | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Strong/irregular verb conjugation set. |
| vecka, -n | week | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| öl: ta en ~ | beer; have a beer | noun/phrase | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| ögonblick, -et | moment | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| öppen, öppet | open | adjective | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| öre, -t | öre (1/100 krona, Swedish subunit currency) | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| över | over, above | preposition | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| vit, -t | white | adjective | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| vitvinssås, -en | white wine sauce | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| vispgrädde | whipped cream | noun | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | |
| vägen/vänster/höger (directional set) | (the) way / left / right | noun/adverb | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Directional vocabulary cluster, cross-referenced with Conversation 8's direction-giving dialogue (Part 1). |
| windy: det blåser, blåsig | windy, it's windy | adjective/phrase | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Duplicate cross-listing with *blåser* above; kept because both headword forms are independently source-attested (adjective vs. impersonal-verb construction). |
| whole: hel, -t | whole | adjective | core | — | contemporary (2006/2010) | — | — | grammar_reference | n/a | n/a | Cross-listing, see *hel* above. |

### Grammar points

Part 2's source material is a glossary, a Subject index, and administrative front matter — it does
not itself contain paraphrasable grammar explanations (those live in Part 1's "Insight" boxes). Two
things are worth recording here as genuine grammar-adjacent content found specifically in this
back-matter material:

#### 1. The glossary's own *en*/*ett* notation convention
The glossary's front matter (p. ~53) states explicitly how it marks noun gender: an entry with no
suffix marking is an **en-word** (e.g. *adress, -en* is still written as *en adress* in running
text); an entry suffixed `-et` or `-t` is an **ett-word** (e.g. *namn, -et*). This is the glossary
documenting its own lexicographic convention, not a grammar rule being taught — but it doubles as a
usable at-a-glance gender marker for every noun in both glossary tables above.

#### 2. Subject index as a grammar-topic map (not explanations)
The Subject index (p. ~69) is a pure page-reference index of grammar/usage topics covered across the
whole book — pronouns (I/you/he…; me/you/him…; my/your/his…), adjectives, agreeing/disagreeing,
colours, currency, days of the week, false friends, gender, "jo," "man," "the," "then," "there
is/are," "think," verb past tense, "what," "when," "where," "which," "who," "why," word order, and
several pronunciation topics (long sounds, long words, reduction, voiceless "s"). This is useful as a
**map of what grammar the book teaches** (most of which is already captured as individual Insight
boxes in Part 1), not as new explanatory content in its own right — the index gives page numbers, not
explanations.

### Colloquial/register findings — consolidated callout

Collecting every explicit or clearly spoken-register item found across both Parts, for visibility:

- **spänn** — explicitly glossary-tagged `(informal)` for *krona* (currency); the single clearest
  source-marked slang item in the whole book, directly parallel to English "bucks."
- **schysst** — used in-dialogue as a one-word exclamation of approval ("Schysst!" = "Nice!/Cool!"),
  in addition to its glossary sense "kind, fair."
- **nä** — casual/clipped variant of *nej* ("no"), explicitly paired in the glossary.
- **löning** — colloquial variant of *lön* ("wages/payday"), glossary-parenthesized and
  dialogue-confirmed.
- **tja**, **nja**, **jadå**, **nämen**, **jaså** — a small cluster of spoken-register discourse
  particles/interjections (hesitation filler, hesitant-yes, emphatic-yes, surprised greeting,
  "really?/oh?") found across dialogue and the Subject index.
- **nå't** — clipped spoken contraction of *något* ("something"), used only in dialogue, never in the
  glossary's citation-form headwords.
- **fika / fikar / fikabröd / fikapaus** — explicitly flagged by the source itself as informal
  language; Sweden's best-known everyday coffee-break institution-word.
- **kille**, **tjej**, **kompis** — everyday informal-register nouns for "guy," "girl," and
  "friend/mate," used throughout dialogue in preference to more neutral alternatives.
- **toa** — clipped colloquial form of *toalett* ("toilet").
- A cluster of **bracketed spoken-pronunciation respellings** showing casual connected-speech
  phenomena not reflected in standard orthography: enclitic subject-pronoun fusion (*sitter du* →
  "[sitteru]", *är du* → "[eru]", *blir du inte* → "[blirunte]"), verb-final consonant/vowel
  reduction (*regnade det* → "[regnare]", *står det* → "[ståre]", *de är* → "[dåmme]"), and
  day-name/word-internal syllable reduction (*måndag* → "[månnnnnda]", *grattis på födelsedagen* →
  "[fölsedan]", *midsommarafton* → "[missommarafton]"). These are a genuinely rich, systematic
  window into casual spoken Swedish phonology that a citation-form glossary would otherwise hide
  entirely.

