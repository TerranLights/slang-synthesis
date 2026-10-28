# English — Established Grammar/Vocabulary: A Guide to Old English (Mitchell & Robinson)

**Source:** Bruce Mitchell and Fred C. Robinson, *A Guide to Old English* (5th edition; Basil
Blackwell), Part One ("The Language"), chapters 1–5 (Preliminary Remarks, Orthography and
Pronunciation, Inflexions, Word Formation, Syntax), plus a small sample of the end Glossary —
`source_reference/languages/Old English Language Learning Pack/03 A Guide to Old English.doc`.

**Attested Era (whole file):** Old English.

## Coverage note — extraction method and scope (read before using this file)

This source is a legacy Microsoft Word `.doc` file (96 MB) with **no usable text layer**: its own
embedded OLE metadata reports "Number of Words: 28, Number of Characters: 160," and
`soffice --headless --convert-to txt` produces only a 17-byte output (a byte-order-mark and blank
lines). The 96 MB size comes entirely from embedded page-scan images — the `.doc`/OLE Compound
Document container was used purely as a shell around a scanned book, no real authored text at all.

**Extraction method:** The `.doc`'s OLE Compound-File binary was scanned at the raw byte level for
JPEG SOI (`FF D8`) / EOI (`FF D9`) marker pairs (the standard OLE "embedded object" structure
doesn't expose a clean image-stream API for this kind of ad-hoc embedding, so a raw scan was the
practical extraction route). This recovered **173 genuine embedded JPEG images** (3 additional
`FF D8...FF D9` matches were confirmed false positives — tiny ~1KB non-image binary fragments, not
pictures — and discarded). Each image is a **two-printed-page spread** (left+right book pages in
one JPEG, consistent with the page-spread-scan gotcha already documented in
`00_Reference_Extraction_Spec.md`), so the 173 images cover roughly 346 printed pages: the book's
full front matter, Part One (the grammar, pp. 1–139), the start of Part Two (texts), and the
Glossary (pp. ~301–366).

**This extraction covers Part One (the grammar) comprehensively** — every major paradigm table and
grammar-point section was vision-read and extracted below. It does **not** cover Part Two (the
annotated primary-text readings, pp. ~140–297) or the Glossary (pp. 301–366) beyond a small
illustrative sample. Rationale: Part One is where this book's actual mechanics payload lives — a
complete, systematic inflectional and syntactic description of Old English. Part Two is a
primary-text reader with notes (similar territory to the already-extracted
`078_reading_old_english_texts_pt01.md`, from a different book), and a full page-by-page
vision-read of a ~65-page dense four-column dictionary glossary would mean bulk-reproducing a
reference dictionary, which the spec's copyright-discipline rule forbids regardless of effort
budget. If a future pass wants Part Two or the full Glossary, the extracted image set is at
`/tmp/claude-1000/.../scratchpad/oe_extract/images/` only for the duration of this session — it was
**not** persisted anywhere in the repo, so a future extraction would need to re-run the same
OLE/JPEG byte-scan against the original `.doc` to regenerate the image set.

**Vision-reading confidence:** All images were clean, high-resolution (roughly 2000×1500px),
sharply legible scans of a printed book — not a degraded photocopy. Nearly everything below is
`plausible_unverified` (read with high confidence, not independently cross-checked against a second
source) rather than `low_confidence`; a handful of entries that appear identically on two separate
pages are marked `verified`.

### Handwritten marginalia found and excluded (per the spec's vision-reading guard)

This is a used copy with a previous owner's **pencil markings** on several pages — underlines under
printed sentences and circles around printed headers/words. Checked against every page used below:
- pp. 14–15: pencil underlines under "Short vowels must be distinguished from long vowels" and
  "All consonants must be pronounced" / "Double consonants must be pronounced double or long"; a
  pencil circle around the diphthong-equation box (ēo = ē+o, etc.).
- p. 20: a pencil bracket in the margin beside the §13 paragraph ("OE nouns are traditionally
  divided into two groups...").
- p. 33: pencil circle around "-ra, -ost" and an underline under "The comparative is declined weak."
- p. 52: a pencil circle around the printed running header "Inflexions."
- p. 19: a pencil circle around one *þē* form in the 2nd-pers. pronoun table.

**None of this is extracted content** — every marking found was emphasis (underline/circle) added
by a reader on top of already-printed text, not separate handwritten notes, a student's own answer,
or anything that could be mistaken for the book's own material. All vocabulary/grammar content below
reflects only the printed text underneath these marks.

---

## Vocabulary

Illustrative paradigm words and representative Glossary entries (not an exhaustive wordlist — a
reference grammar's paradigm words are a closed, small set, exhaustively covered here; the end
Glossary itself is a ~65-page dictionary and was only lightly sampled, per the coverage note above).

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| se / þæt | 'the, that' (demonstrative, masc./neut.) | determiner/pronoun | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | full paradigm given (sg. masc./neut./fem., pl. all genders); doubles as the definite article — OE has no dedicated article (§15–16, p.18; §193, p.106) |
| þēs | 'this' (demonstrative) | determiner/pronoun | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | full paradigm (§17, p.18) |
| hwā / hwæt | 'who?' / 'what?' (interrogative; also indefinite 'anyone/something') | pronoun | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | not a relative pronoun in OE (§20, p.19) |
| iċ / þū / wē / ġē | 'I' / 'thou' / 'we' / 'ye, you' | pronoun | core | — | Old English | — | — | grammar_reference | n/a | verified | 1st/2nd person paradigm; also appears correctly cross-referenced on p.36 (§89.3) |
| wit / ġit | 'we two' / 'you two' | pronoun (dual) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | OE preserves a dual number only in 1st/2nd pers. pronouns, used with plural verb agreement (§11, p.18; §21, p.19) |
| nama | 'name' | noun (weak masc.) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | base paradigm for all weak nouns; oblique cases in -an except gen.pl. -ena, dat.pl. -um (§22, p.19) |
| sunne | 'sun' | noun (weak fem.) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | declined exactly as *nama* apart from nom.sg. (§23, p.20) |
| ēage | 'eye' | noun (weak neut.) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | nom./acc.sg. identical, as in all neuters (§24, p.20) |
| stān | 'stone' | noun (strong masc.) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | the principal strong-masc. declension paradigm, referenced constantly throughout the book as the "endings of *stān*" |
| scip | 'ship' | noun (strong neut.) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | principal strong-neut. paradigm; *sc* pronounced like MnE *sh* (§9, p.16) |
| word | 'word' | noun (strong neut., long-stemmed) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | second principal strong-neut. paradigm (vs. short-stemmed *scip*) |
| ġiefu | 'gift' | noun (strong fem.) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | principal strong-fem. paradigm |
| scōh | 'shoe' | noun (masc., h-stem) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | gen.sg. *scōs* shows regular loss of intervocalic *h* + vowel absorption: *scōhes > scōes > scōs* (§37, p.24) |
| mearh | 'horse' | noun (masc., h-stem) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | loses *h* with compensatory lengthening between *r*/*l* and a vowel (§39, p.24); full paradigm given |
| wealh | 'foreigner, Welshman, slave' | noun (masc., h-stem) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | same pattern as *mearh*; paradigm given (§39, p.24) — source of the ethnonym "Welsh" |
| bearu | 'grove' | noun (masc., -u stem) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | stem alternates *bearw-* before vowel endings (§40, p.25) |
| searu | 'device, equipment, trick' | noun (neut., -u stem) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | stem alternates *searw-*; identical nom./acc. sg.=pl. pattern of neuter -u stems (§40, p.25) |
| cyning | 'king' | noun (masc.) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | regular dissyllable, type (a), follows *stān* with no stem variation (§41, p.25) |
| hēafod | 'head' | noun (neut., dissyllable) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | loses medial vowel when an ending beginning with a vowel is added (dat.pl. *hēafdum*, NOT *hēafodum*) (§42, p.25) |
| engel | 'angel' | noun (masc., dissyllable) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | same medial-vowel-loss pattern as *hēafod*; dat.pl. *englum* (§42, p.25) |
| mann | 'man, person' | noun (masc., i-mutation) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | nom./acc.pl. *menn* — the mutated vowel appears in dat.sg. and nom./acc.pl. with no inflexional ending; source of MnE 'man'/'men' (§58, p.28) |
| bōc | 'book' | noun (fem., i-mutation) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | nom./acc.pl. *bēċ*; most i-mutation fem. nouns went regular in MnE except a handful (goose/geese, louse/lice, mouse/mice, tooth/teeth) (§58–59, p.29) |
| frēond / fēond | 'friend' / 'enemy' | noun (masc., i-mutation) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | formed from present participles of verbs ('loving one' / 'hating one'); can follow *stān* or show i-mutated *īe* in dat.sg./nom.-acc.pl. like *mann* (§59, p.29) |
| fæder / brōþor / mōdor / dohtor / swēostor | 'father' / 'brother' / 'mother' / 'daughter' / 'sister' | noun (r-stem kinship terms) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | an irregular, heavily-analogical subclass; regular in gen./dat.pl. (-a, -um) but resist systematic rules otherwise (§60, p.29) |
| glæd | 'glad' | adjective (short-stemmed, æ-stem) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | principal paradigm for strong-declension æ/a-fluctuating monosyllabic adjectives: æ in closed syllable/front-vowel ending, a in open syllable + back-vowel ending (§70, p.32) |
| gōd | 'good' | adjective | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | varies only nom.sg.fem. *gōd* vs. *tilu*-type pattern; irregular comparison *betera/sēlra, betst/sēlest* (§67, p.32; §76, p.33) |
| hālig | 'holy' | adjective (long-stemmed dissyllable) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | medial vowel retained before consonant-initial endings, often lost before vowel-initial ones, with common analogical doublets (§68, p.32) |
| ġearo | 'ready' | adjective (-u stem) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | stem alternates *ġearw-* before vowels, parallel to the noun *bearu* (§71, p.33) |
| blīþe | 'happy, gentle' | adjective (-e stem) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | drops -e and takes the endings of *til* (§73, p.33) |
| lēof → lēofra → lēofost | 'dear → dearer → dearest' | adjective (regular comparison) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | regular -ra/-ost comparison pattern (§74, p.33) |
| eald → ieldra → ieldest | 'old → older → oldest' | adjective (i-mutated comparison) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | comparative/superlative show i-mutation of the stem vowel, a pattern also seen in *ġeong/ġingra/ġingest*, *lang/lengra/lengest*, *strang/strengra/strengest*, *hēah/hīerra/hīehst* (§75, p.33) |
| lȳtel → lǣssa → lǣst | 'little → less → least' | adjective (suppletive comparison) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | with *miċel/māra/mǣst* 'great', *yfel/wiersa/wierst* 'bad' — irregular/suppletive comparison (§76, p.33), ancestors of MnE little/less/least, good/better/best |
| ān | 'one' (also 'alone' when weak) | numeral (cardinal) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | declined strong = 'one'; declined weak (*āna*) usually = 'alone' (§83, p.35) |
| twēġen / bēġen | 'two' / 'both' | numeral (cardinal) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | declined identically; full gender paradigm given (§84, p.35) |
| þrīe | 'three' | numeral (cardinal) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | gen. *þrēora*, dat. *þrīm* (§85, p.35) |
| forma / ōþer / þridda / fēorþa ... tēoþa | 'first' / 'second' / 'third' / 'fourth' ... 'tenth' | numeral (ordinal) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | ordinals declined weak except *ōþer* 'second', always strong (§82–83, p.34) |
| singan, sang, sungon, sungen | 'sing, sang, sang(pl.), sung' | verb (strong, class III) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | the book's full worked conjugation example — present/preterite indicative and subjunctive, imperative, infinitives, participles (§111, p.43) |
| scīnan, scān, scinon, scinen | 'shine' | verb (strong, class I) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | recognition symbol ī+one cons.; class exemplar (§93, p.37) |
| crēopan, crēap, crupon, cropen | 'creep' | verb (strong, class II) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | recognition symbol ēo+one cons.; class exemplar, ancestor of MnE 'creep/crept' (§93, p.37) |
| brūcan, brēac, brucon, brocen | 'enjoy, use' | verb (strong, class II) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | recognition symbol ū+one cons. (§93, p.37) |
| breġdan, bræġd, brugdon, brogden | 'pull, draw (a weapon)' | verb (strong, class III) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | class III gradation is the most sound-law-affected of all seven classes (§95, p.37) |
| beran, bær, bæron, boren | 'bear, carry' | verb (strong, class IV) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | ancestor of MnE 'bear/bore/born(e)' (§93, p.37) |
| tredan, træd, trædon, treden | 'tread' | verb (strong, class V) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | class V later merged into class IV in the history of English (§107–108, p.43) |
| faran, fōr, fōron, faren | 'go, travel, fare' | verb (strong, class VI) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | ancestor of MnE 'fare/fared' (now weak) |
| healdan, hēold, hēoldon, healden | 'hold' | verb (strong, class VII, reduplicating) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | class VII(a) exemplar |
| hātan, hēt, hēton, hāten | 'command, be called' | verb (strong, class VII, reduplicating) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | class VII(b) exemplar; *hātte* 'is/was called' is OE's one surviving true synthetic passive form (§89.5, p.36) |
| fremman | 'do, perform' | verb (weak, class 1a) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | short-vowel + double-consonant subtype; full conjugation given (§116–117, p.46–47) |
| nerian | 'save' | verb (weak, class 1a) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | nearly all verbs in -rian belong here, not class 2 (§132, p.52) |
| hīeran | 'hear' | verb (weak, class 1b) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | long-vowel-stem subtype; i-mutated vowel throughout the stem (§117, p.47) |
| lufian | 'love' | verb (weak, class 2) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | the class-2 paradigm verb; -ian infinitive ending (§124–125, p.50) |
| habban, libban, secgan, hycgan | 'have', 'live', 'say', 'think' | verb (weak, class 3) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | only four members of class 3 remain; irregular/contracted conjugations given in full (§126, p.50) |
| bēon / wesan | 'be' | verb (anomalous) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | two historically distinct stems supply one paradigm (*eom/eart/is* vs. *bēo/bist/biþ*); distinct present-tense semantic nuance discussed at §196 (§127, p.51) |
| dōn | 'do' | verb (anomalous) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | i-mutation in 2nd/3rd sg. pres. ind. (*dēst, dēþ*) (§128, p.51) |
| gān | 'go' | verb (anomalous) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | suppletive preterite *ēode* (§128, p.51) |
| willan | 'wish, will' | verb (anomalous) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | preterite *wolde*; ancestor of the MnE modal 'will/would' (§129, p.51) |
| āgan | 'possess, own' | verb (preterite-present) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | ancestor of MnE 'owe/own/ought' (§130, p.52) |
| cunnan | 'can, know how to' | verb (preterite-present) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | ancestor of MnE modal 'can' (§130, p.52) |
| magan | 'be able' | verb (preterite-present) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | ancestor of MnE modal 'may/might' (§130, p.52) |
| mōtan | 'be allowed to, may' | verb (preterite-present) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | ancestor of MnE modal 'must' (semantic shift from permission to obligation) (§130, p.52) |
| sculan | 'be obliged to' | verb (preterite-present) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | ancestor of MnE modal 'shall/should' (§130, p.52) |
| þurfan | 'need' | verb (preterite-present) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | ancestor of archaic MnE 'needs not/dare not' pattern (§130, p.52) |
| witan | 'know' | verb (preterite-present) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | ancestor of MnE 'wit/wot' (obsolete) and 'wise/wisdom' family; cf. Latin *novi* 'I know' as the IE parallel the book cites (§130, p.52) |
| hwælweġ | 'whale-way' (kenning for 'the sea') | noun (compound, masc.) | literary | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | kenning — condensed metaphor without the point of comparison made explicit; set-phrase formula usable after *on, ofer, ġeond* for alliterative "across the sea" (§137, p.57) |
| ȳþhenġest | 'wave-horse' (kenning for 'a ship') | noun (compound, masc.) | literary | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | kenning example (§137, p.57) |
| hleahtorsmiþ | 'laughter-smith' (kenning for 'a minstrel') | noun (compound, masc.) | literary | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | kenning example (§137, p.57) |
| wulfhēafodtrēo | 'wolf-head-tree' (i.e. 'gallows, cross') | noun (3-element compound, neut.) | literary | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | rare 3-element compound (§137, note, p.56) |
| wanhāl | 'not whole, ill' | adjective (prefixed, *wan*- deprivative) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | prefix *wan*- = deprivative/negative (§138, p.59) |
| wiþċēosan | 'reject' | verb (prefixed, *wiþ*- 'against') | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | prefix *wiþ*- = 'against' (§138, p.59) |
| ymbgang | 'circuit, circumference' | noun (prefixed, *ymb*- 'around') | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | prefix *ymb*- = 'around' (§138, p.59) |
| Hǣlend | 'Healer, Saviour' | noun (masc., agentive *-end* suffix) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | suffix *-end* ≈ MnE '-er', from the present participle ending *-ende* (§138, p.59) |
| wīsdōm | 'wisdom' | noun (masc., abstract *-dōm* suffix) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | (§138, p.58) |
| frēondscipe | 'friendship' | noun (masc., abstract *-scipe* suffix) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | (§138, p.58) |
| cildhād | 'childhood' | noun (masc., *-hād* suffix) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | *-hād* ≈ MnE '-hood' (§138, p.59) |
| cræftiġ | 'powerful, mighty' | adjective (*-iġ* suffix) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | *-iġ* ≈ MnE '-y' (§138, p.60) |
| hēofonliċ | 'heavenly' | adjective (*-liċ* suffix) | core | — | Old English | — | — | grammar_reference | n/a | plausible_unverified | *-liċ* ≈ MnE '-ly, -like' (§138, p.60) |
| mōd | 'spirit, courage, mind' (→ MnE 'mood') | noun (neut.) | core | — | Old English | — | — | dictionary | n/a | verified | Glossary sample, p.339; semantic narrowing to MnE 'mood' noted by the glossary itself |
| mihtiġ | 'mighty, powerful' | adjective | core | — | Old English | — | — | dictionary | n/a | verified | Glossary sample, p.339, compar. *meahtigra* |
| mildheort | 'merciful' (→ MnE 'mildhearted') | adjective (compound) | core | — | Old English | — | — | dictionary | n/a | verified | Glossary sample, p.339 |
| middangeard | 'world, middle earth' | noun (masc., compound) | literary | — | Old English | — | — | dictionary | n/a | verified | Glossary sample, p.339 — the direct etymon of Tolkien's "Middle-earth" |
| mearcstapa | 'wanderer in the wasteland, border-haunter' | noun (masc., compound) | literary | — | Old English | — | — | dictionary | n/a | verified | Glossary sample, p.338 — the *Beowulf* epithet for Grendel |

## Grammar points

### Orthography and Pronunciation (§5–9, pp. 13–16)

Long vowels are marked with a macron throughout the book. OE's seven short/long vowel pairs
(*a/ā, æ/ǣ, e/ē, i/ī, o/ō, u/ū, y/ȳ*) are given approximate Received-Pronunciation equivalents, with
*y/ȳ* glossed as "front rounded" via French *tu*/*ruse* comparisons. Three diphthongs are
distinguished as short/long pairs (*ea/ēa, eo/ēo, ie/īe*) and explicitly treated as unitary nuclei,
not vowel sequences — the book stresses that OE *heall*, *hēold*, *hielt* are monosyllables despite
the two-letter vowel digraphs, parallel to MnE 'meat' or 'fine'. A footnote flags that *ie/īe*'s
original pronunciation is uncertain, and that by Alfred's time *īe* had likely already monophthongized.

All consonants are pronounced (no silent letters), and doubled consonants are genuinely geminate
(long), not a spelling convention — *biddan* is pronounced with an actually-held /d/, compared to
"red D" vs. "ready" in MnE. The letters *f, s, þ/ð* are **allophonically** voiced between vowels/voiced
sounds and voiceless elsewhere (not separate phonemes as in MnE) — this single rule explains the
MnE alternations 'path'/'paths', 'loaf'/'loaves'. Initial *ġe-* does not trigger voicing. *h* is
pronounced [h] word-initially before a vowel, but [ç]/[x] (German *ich*/*ach*) elsewhere, depending on
front/back vowel context. *c* and *g* split into "hard" (*k*, MnE-"good"-*g*) before back vowels
and "soft" (*ch*-ish, *y*-ish — marked with a dot, *ċ*/*ġ*, in the book's Part One) before front
vowels; the digraphs *sc* and *cg* are usually pronounced like MnE *sh*/*dge* (so *scip* 'ship' and
*ecg* 'edge' sound the same in OE and MnE), though *sc* is pronounced *sk* in a handful of words
like *ascian* 'ask'. Intervocalic/post-back-vowel *g* is a velar fricative [ɣ].

### Pronouns (§10–21, pp. 17–19)

OE distinguishes number (singular/plural, **plus a dual** in 1st/2nd person pronouns only — *wit*
'we two', *ġit* 'you two'), four main cases (nominative, accusative, genitive, dative) with an
instrumental surviving only in parts of the adjective/pronoun system (the dative substitutes
elsewhere), and three grammatical genders. Grammatical gender frequently conflicts with natural sex
(*se wīfmann* masc. 'the woman', *þæt wīf* neut. 'the woman') — one of the sources of the eventual
loss of grammatical gender in English. Compounds take the gender of their second element.

Full paradigms are given for: the demonstrative *se/þæt* (doubling as the definite article — OE has
no true article), the demonstrative *þēs* 'this', the interrogative *hwā/hwæt*, the 3rd person
pronoun (*hē/hit/hēo*, plural *hīe*), and the 1st/2nd person pronouns with their dual forms. A noted
ambiguity: the indeclinable 3rd-person genitive forms *his/hire/hira* contrast with the fully
declinable 1st/2nd-person genitives, which can function as true possessive adjectives agreeing in
case/number/gender with the noun they modify — so a form like *min* can be ambiguous between
'my' (possessive adjective) and 'of me' (possessive pronoun).

### Noun declension (§13, §22–62, pp. 19–30)

Nouns are traditionally divided into **weak** (*-an* stem, recognizable chiefly by nom.sg. *-a*
masc.) and **strong** declensions; nom.sg. endings themselves often signal gender (e.g. strong masc.
agent nouns in *-end*/*-ere*, strong fem. abstracts in *-ing*/*-ung*). The weak paradigm (*nama*,
*sunne*, *ēage*) is comparatively simple and regular. The strong declension has many subtypes keyed
to stem shape:

- **Monosyllables and dissyllables** are divided by syllable weight (short- vs. long-stemmed), which
  determines whether a following unstressed medial vowel survives or is dropped when an ending is
  added (e.g. *hēafod* → dat.pl. *hēafdum*, not *†hēafodum*) — the book frames this as a systematic
  "closed syllable keeps the vowel, open syllable loses it" rule with real predictive power.
- **h-stem nouns** (*scōh*, *eoh*, *feoh*, *mearh*, *wealh*) show a regular sound change: loss of
  intervocalic *h* with compensatory lengthening or vowel absorption in the oblique cases.
- ***-u*-stem nouns** (*bearu*, *searu*) show a stem alternation (*bearu* ~ *bearw-*) conditioned by
  whether the following ending begins with a vowel.
- **i-mutation nouns** (*mann*, *bōc*, *frēond*/*fēond*) show the mutated vowel appearing specifically
  in the dat.sg. and nom./acc.pl. with no overt ending — this is the direct historical source of MnE
  irregular plurals like man/men, foot/feet, tooth/teeth, goose/geese, mouse/mice, louse/lice.
- **r-stem kinship nouns** (*fæder, brōþor, mōdor, dohtor, swēostor*) are a small, heavily analogical
  class resistant to full systematization; regular only in gen./dat.pl.

### i-Mutation (§52–60, pp. 28–30)

A pervasive sound change (described, not merely tabulated) foundational to OE's nominal and verbal
morphology: when a stressed syllable was followed by /i/ or /j/, the stressed vowel was pulled toward
that high-front articulation — low front vowels (*æ, e*) were raised, back vowels (*a, o, u*) were
fronted, and the triggering /i/ or /j/ was itself usually lost (sometimes surviving as *e* or *i*).
The book gives a full correspondence table: *æ:e, e:i, a(+m/n):e(+m/n), ă:ǣ, ŏ:ē, ŭ:ȳ, ĕa:ĭe, ĕo:ĭe*.
Thirteen distinct sounds are affected in total. The book explicitly recommends using the strong
verbs' infinitive-vs.-2nd/3rd-sg.-present-indicative vowel alternation as a self-study source of
i-mutation examples (the mutating /i/ of the old 2nd/3rd sg. ending has since disappeared or become
*e*, leaving only the mutated vowel as evidence) — i.e. the strong-verb gradation system and the
i-mutation system are two independently-visible traces of the same underlying historical mechanism.

### Adjective declension and comparison (§63–76, pp. 30–33)

Adjectives have **weak** (used after a demonstrative/possessive, roughly "definite") and **strong**
("indefinite") declensions, closely paralleling the strong-noun/pronoun endings (§79–81 catalogue the
systematic overlaps: neut. nom.=acc.sg. always; masc. nom.=acc.sg. always; nom.=acc.pl. always;
gen.=dat.fem.sg. always, etc.). Stem-shape rules parallel to the noun system apply (medial-vowel
loss in long-stemmed dissyllables like *hālig*; *-u*-stem alternation in *ġearo* ~ *ġearw-*, parallel
to the noun *bearu*). Comparison is regular (*-ra, -ost*: *lēof/lēofra/lēofost*) for most adjectives,
but a sizeable subclass shows an **i-mutated** stem vowel in the comparative/superlative
(*eald/ieldra/ieldest*, *strang/strengra/strengest*, *hēah/hīerra/hīehst*), and a few are fully
suppletive (*lȳtel/lǣssa/lǣst*, *miċel/māra/mǣst*, *yfel/wiersa/wierst*, *gōd/betera,sēlra/betst,sēlest*)
— the direct ancestors of MnE's irregular little/less/least and good/better/best. The comparative is
always declined weak; the superlative may be either weak or strong.

### Numerals (§82–86, pp. 34–35)

Only the first three cardinals (*ān, twēġen/bēġen, þrīe*) are regularly declined with full
case/gender paradigms; beyond 'three', numerals are largely indeclinable and their meaning is
"obvious" or will be glossed in context, per the book. Ordinals are declined weak except *ōþer*
'second', which is always strong. *ān* means 'one' when strong but typically 'alone' when weak.

### The strong verb system (§87–114, pp. 35–45)

OE verbs are either **weak** (preterite/past participle via a dental suffix) or **strong** (via a
stem-vowel change, "gradation") — cf. MnE 'laugh/laughed' (weak) vs. 'sing/sang/sung' (strong). New
or borrowed verbs always join the weak system (e.g. the 13th-c. borrowing 'strive' joined the strong
pattern only because its infinitive happened to rhyme with 'drive'; 'jive' went weak). OE strong
verbs distinguish **four** principal parts (infinitive, two distinct preterites — singular and
plural — and a past participle) versus MnE's maximum of three, organized into **seven numbered
classes**, each with a "recognition symbol" (a characteristic infinitive vowel+consonant shape, e.g.
class I = *ī* + one consonant, class II = *ēo*/*ū* + one consonant) that lets a reader predict a
verb's class — and hence its full principal-part set — from the infinitive alone. Class III's
gradation series is the most sound-law-disrupted of the seven (discussed at length); classes V and
VI are historically regular. Two major diachronic drifts are noted as already visible in OE data:
the eventual MnE collapse from distinct gradation series to fewer vowel classes (e.g. class V merging
into class IV: OE *specan/tredan/wefan* → MnE 'speak/tread/weave' now pattern like class IV *beran*),
and the eventual collapse of the two distinct OE preterite-singular/preterite-plural vowels into one
(already starting in OE *cuman* IV and *etan* V, where the 2nd-preterite vowel has spread into the
1st preterite).

**Grimm's Law and Verner's Law** (§105–109, p. 42–43) are explained as the mechanism behind
otherwise-unpredictable medial-consonant alternations within a single strong verb's principal parts
(e.g. *snīþan, snāþ, snidon, sniden* — þ in the infinitive/1st-preterite vs. historically-expected d
in the 2nd-preterite/past-participle). Verner's Law outcomes depended on where Proto-Indo-European
stress fell (cf. Greek *patēr*, stressed on the second syllable, giving a **voiced** reflex in
Primitive OE, vs. Greek *phrátēr* = Latin *frāter*, stressed on the first syllable, giving a
**voiceless** reflex — explaining why OE has *fæder* 'father' rather than the expected *†fæþer*
alongside *brōþor* 'brother'). The book notes Verner's-Law alternants are sometimes later
"levelled" away by analogy (eliminated in favor of one form throughout the paradigm) — this
levelling process is framed as an early, OE-internal instance of the same regularizing pressure that
later eliminated most of the English strong-verb system's internal vowel-count distinctions.

A full conjugation is worked through for *singan* 'sing' III (present/preterite indicative,
subjunctive, imperative, both infinitives, both participles) as the canonical exemplar, with general
rules: OE verbs have 2 tenses (present/preterite — no synthetic future), 3 moods
(indicative/subjunctive/imperative) plus 2 infinitives (plain and inflected "to"-infinitive), 2
numbers (plus the pronoun-conditioned dual), distinguish person **only** in the singular
present/preterite indicative, and have only **one true surviving synthetic passive form** in the
whole language: *hātte* 'is/was called'.

### The weak verb system (§115–126, pp. 46–50)

Three classes, each adding a dental suffix for preterite/past participle. **Class 1** splits into two
subtypes: (a) short-vowel-plus-doubled-consonant verbs like *fremman* 'do' and *nerian* 'save', and
(b) long-vowel verbs like *hīeran* 'hear'. All three show a historically-conditioned "loss" pattern
in the 2nd/3rd sg. present indicative, imperative singular, the whole preterite, and the past
participle (*fremman* loses an *m*, *nerian* loses its *i*, *hīeran* loses an *e*) — explained (§117
note) as the regular phonological outcome of an original /-j-/-suffixed infinitive (*framjan* →
*fremman*, etc.), not an arbitrary irregularity. Class-1(b)-type verbs carry an i-mutated vowel
throughout their entire stem. **Class 2** (*lufian* 'love') is the regular, productive class — verbs
borrowed from Latin default into it (e.g. *declinian* < *declināre*). Verbs ending in *-rian* mostly
follow class 1(a) *nerian*, not class 2, despite the surface similarity; this is flagged as a common
point of confusion. **Class 3** contains only four surviving members — *habban* 'have', *libban*
'live', *secgan* 'say', *hycgan* 'think' — each independently irregular/contracted, given full
individual paradigms.

### Anomalous and preterite-present verbs (§127–130, pp. 51–52)

Four verbs don't fit the strong/weak system cleanly: *bēon*/*wesan* 'be' (two historically distinct
stems supplying one suppletive paradigm — *eom/eart/is* vs. *bēo/bist/biþ* — with a real semantic
distinction between the two present-tense stems discussed later at §196), *dōn* 'do' and *gān* 'go'
(each with i-mutation in 2nd/3rd sg. present and a suppletive preterite, *gān*'s being *ēode*), and
*willan* 'wish, will' (preterite *wolde*). Separately, the **preterite-present verbs** — a closed set
including *āgan, unnan, cunnan, dugan, durran, ġemunan, magan, mōtan, sculan, þurfan, witan* — have an
old strong **preterite** form repurposed as a **present-tense** meaning (parallel to Latin *novi* 'I
[have come to] know' = 'I know'), with a newly-built **weak** preterite layered on top. This class is
the direct historical source of the entire MnE modal-auxiliary system (can, may/might, must, shall/
should, dare, owe/own/ought, wot/wit), making it one of the single most consequential grammatical
subsystems in the book for anyone modeling how a modal/auxiliary system can emerge diachronically
from a verbal-aspect reanalysis.

### Adverbs (§135, pp. 53–54)

Formed with characteristic endings *-e* (*hraþe* 'quickly'), *-līċe* (*hrædlīċe* 'quickly'), and
*-unga* (*eallunga* 'entirely'); directional adverb pairs distinguish static vs. source-of-motion
sense via an *-an* suffix (*norþ* 'north(wards)' vs. *norþan* 'from the north'). Comparison is
regular (*-or, -ost*: *oft/oftor/oftost*) or i-mutated (*lange/leng/lengest*, *feorr/fierr/fierrest*)
— the same two-pattern split seen in adjective comparison.

### Word formation: compounding (§136–137, pp. 55–57)

OE acquired new words three ways: borrowing, compounding, and affixation. Compounding is
systematically productive — nouns from noun+noun, adjective+noun, adverb+noun; adjectives from
noun+adjective, adjective+adjective, adverb+adjective, adjective+noun — with the first element
normally uninflected. Loanword-translation ("calquing") is discussed as a major OE strategy for
absorbing foreign/learned concepts natively: *godspel* 'good news' for *evangelium* ('gospel'),
Ælfric's grammatical calques *foresetnes* 'preposition' (lit. 'fore-set-ness') and *betwuxāleġednes*
'interjection' (lit. 'between-laid-ness'), and *sundorhalgan* 'apart-holies' / *ǣlārēowas*
'law-teachers' for 'Pharisees'. The book observes that many native OE compounds of this kind
(*tungolcræft* 'star-craft' = astronomy, *lārhūs* 'lore-house' = school) didn't survive into MnE, and
contrasts this unfavorably-received replacement strategy with German's continued comfort with native
compounds like *Fernsprecher* 'far-speaker' for 'telephone'. The **kenning** — a compressed metaphor
with the point of comparison left implicit (*hwælweġ* 'whale-way' for 'the sea', *ȳþhenġest*
'wave-horse' for 'a ship', *hleahtorsmiþ* 'laughter-smith' for 'a minstrel') — is specifically
identified as a poetic device serving the practical need for alliterative synonyms in formulaic
oral-derived verse; fixed kenning-based "oral formulae" (several synonymous *weġ*-compounds for 'the
sea', interchangeable depending on which consonant needed to alliterate) are given as a concrete
example of vocabulary generated to serve a metrical/poetic system — directly relevant to how a
register-specific vocabulary layer can be mechanically generated from a compounding system plus a
formal constraint (alliteration).

### Word formation: affixes (§138, pp. 57–60)

A substantial catalogue of OE derivational prefixes (*ā-, ǣġ-, be-, for-, ġe-, on-/an-, or-, tō-,
un-, wan-, wiþ-, ymb-*) and suffixes — nominal (*-aþ/-oþ, -end, -hād, -ing, -mæl, -ræden, -þ(o)/-þ(u),
-ung/-ing*) and adjectival (*-en, -full, -isċ, -lēas, -dōm, -ere, -sċipe, -nes/-nis/-nys, -iġ, -līċ,
-mæl, -sum*) — each glossed with its semantic function and modern-English reflex where one survives
(e.g. *-hād* → '-hood', *-sċipe* → '-ship', *-dōm* → '-dom', *-iġ* → '-y', *-līċ* → '-ly'/'-like').
Several prefixes are polysemous and the book catalogues the distinct senses separately (e.g. *be-*:
(1) literal 'about/around', (2) deprivative, (3) transitivizing an otherwise-intransitive verb;
*ġe-*: (1) 'together', (2) perfective aspect marker on verbs, hence its frequent appearance on past
participles; *on-/an-*: (1) negative/reversative, (2) 'against'; *or-*: (1) deprivative, (2)
'early/original/primaeval'; *tō-*: (1) directional 'to', (2) separative 'apart'; *un-*: (1) plain
negative, (2) pejorative intensifier). This prefix/suffix inventory, paired with the compounding
section above, gives a fairly complete picture of OE's derivational-morphology toolkit for
word-formation mechanics.

### Syntax: word order (§139–147, pp. 61–65)

The book frames OE word order as "recognizably English" in places and "wrestling with a foreign
language" in others, attributing some of the difficulty to inherited Germanic syntax and some to
early OE prose still being a developing medium for complex narrative (citing the breathless,
paratactic *ond*-chained Battle-of-Ashdown annal in the *Anglo-Saxon Chronicle*, and stilted,
Latin-periodic-structure-influenced translated prose like Alfred's Orpheus-and-Eurydice passage).
Three principal clause-level word orders are catalogued: **S.V.** (increasingly the norm, foreshadowing
MnE), **S...V.** (subject-early, verb-final or near-final — most common in subordinate clauses, but
also occurs in principal clauses, so **S...V. order alone does not certify subordination**), and
**V.S.** (used in non-dependent questions, after an initial negative, in subordinate clauses of
concession/condition, and after certain adverbs — paralleling the modern German verb-second
pattern). Negative *ne* always sits immediately before the verb in all three orders, and unstressed
pronoun objects characteristically sit between S and V even where a full-noun object would follow V
(*wē hīe ondrēdon* 'we feared them'). A historically important observation: OE's loss of distinct
nominative/accusative marking in some paradigms already creates real word-order-dependent ambiguity
in attested texts (*Þās seofon hī ġecuron...*, where only context shows *hī* is the subject) — the
book frames the **gradual rise of fixed S.V.O. order** as directly driven by this erosion of case
marking, i.e. word order and inflection are presented as functionally substitutable mechanisms for
encoding grammatical relations, with OE caught mid-transition between the two systems.

### Syntax: concord (§187, pp. 103–105)

Nouns/pronouns and their modifiers agree in number, gender, and case; participles in a participial
phrase usually (but not always) agree with what they modify; after *habban* a past participle may
agree with the object or stay uninflected. Pronoun-antecedent agreement in number/gender is
generally solid but agreement **in case** between a relative pronoun and its antecedent is "a matter
of chance, not principle" — a direct correction the book makes to a claim in Quirk & Wrenn's *An Old
English Grammar*. Subject-verb agreement is in number and person, with dual pronouns taking plural
verb forms; collective nouns and indefinite pronouns cause the same number-agreement wobbles in OE
that they do in MnE.

### Syntax: uses of the cases (§188–194, pp. 105–107)

**Nominative** marks subject, complement, and vocative address. **Accusative** marks the direct
object, plus duration of time and extent of space (*ealne dæg* 'all day', *flēon fōtes trym* 'to flee
one foot's pace'). **Genitive** covers possession, subjective vs. objective genitive (*þæs cyninges
bebod* 'the king's command' = 'the king commanded' vs. *mētodes eġe* 'fear of the Lord' = 'we fear the
Lord'), descriptive/defining use, partitive use, adverbial use (*dæġes ond nihtes* 'by day and
night'), and use after certain adjectives/verbs. **Dative** covers the indirect object, possession,
time, a Latin-influenced "dative absolute" construction (imitating the Latin ablative absolute), use
after certain adjectives (comparatives) and verbs, and — crucially — **substitutes for the
instrumental wherever no distinct instrumental form exists**. **Instrumental**, where it does survive
as a distinct form, covers means/manner, accompaniment, and time. Articles/pronouns/numerals: OE has
no true articles (*se*/*þēs* do the work), and both definite and indefinite "articles" are frequently
simply **omitted** where MnE would require one (*wælstōwe ġewald* 'command of the battlefield' — no
article on either noun); *ān* 'one' and *sum* 'a certain' serve indefinite-article-like functions
without being grammaticalized articles.

### Syntax: tense, mood, and the rise of periphrastic ("resolved") tenses (§195–204, pp. 108–109)

OE morphologically distinguishes only two tenses (present, preterite), but the book stresses these
two simple tenses routinely express complex temporal relationships that MnE marks with periphrastic
("resolved") tenses — the **present** covers continuing state, immediate utterance (vs. MnE's
present-continuous 'say now'), simple future, and future perfect; the **preterite** covers a single
completed past act, a continuing past act, the perfect, and the pluperfect, context alone
disambiguating. The subjunctive expresses commands, wishes, and prayers in independent clauses, and
the book notes an explicit case of genuine temporal ambiguity in *Beowulf* (ll. 960–1) where a
preterite subjunctive could be read as referring to past, present, or future unreality with roughly
equal plausibility — framed as evidence that "unreality is timeless" in OE grammar. **Resolved
(periphrastic) tenses** — participle/infinitive + *bēon*, *habban*, or a modal — are identified as
already incipient in OE (MnE 'he is coming' / 'he is come' / 'he has come' / 'he will come' all have
OE-attested beginnings), marking the historical starting point of the entire MnE auxiliary-verb
tense/aspect system that later fully supplants the old synthetic preterite-subjunctive machinery
described just above.

---

## Not extracted (scope boundary, for a future pass if ever wanted)

- **Syntax §148–186** (noun clauses, adjective clauses, adverb clauses, parataxis, pp. 66–103) —
  skimmed for context (word order, concord, case, and tense/mood sections above were prioritized as
  the highest mechanics payoff) but not individually extracted point-by-point.
- **Syntax §205–214** (uses of the infinitives, further verb syntax, prepositions, pp. 109–139) —
  not reached.
- **Part Two** (annotated primary-text readings — Cynewulf and Cyneheard, Alfred, Ælfric, *The
  Wanderer*, *The Seafarer*, four *Beowulf* excerpts, etc., pp. ~140–297) — not extracted; this is
  primary-text-with-notes territory similar to the already-extracted
  `078_reading_old_english_texts_pt01.md` (different book).
  - "A Note on the Punctuation of Old English Poetry" (p. 297) — not reached.
- **Glossary** (pp. 301–366) — only a 6-entry illustrative sample taken (pp. 338–339); this is a
  ~65-page dense four-column dictionary and a full extraction would mean bulk-reproducing a
  reference dictionary, which the spec's copyright-discipline rule forbids.
- **Indexes to Part One** (Index of Subjects, Index of Words, pp. 367–371) — navigational aids only,
  not extraction-worthy content.
