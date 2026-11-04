# Danish — Established Vocabulary/Grammar: Full-Book Survey (Chapters 1–14)

**Source:** Robin Allan, Philip Holmes, Tom Lundskær-Nielsen, *Danish: An Essential Grammar* (1st
edition, Routledge, 2000; this e-Library edition 2005), whole book, pp. 1–194 (Chapters 1
Pronunciation – 14 Punctuation; the Linguistic Terms glossary, bibliography and index, pp. 195–225,
are metalanguage apparatus and were not extracted as vocabulary).

**Also covers/cross-checks the 2nd edition:** `22 Danish An Essential Grammar 2nd edition.pdf`
(285pp, vision-only, same three authors) was spot-checked against this 1st-edition text-layer copy
(table of contents for chapters 3–11, the first-edition preface, and the final
authorship/chapter-division note). Findings: the 2nd edition's preface and the "authors primarily
responsible for chapters" note are **identical in wording and dated November 1999**, same as the
1st edition's own preface — i.e. no new "Preface to the Second Edition" distinct from the first was
found in the pages checked. Chapter structure, chapter titles, and topic ordering match the 1st
edition one-for-one (e.g. Ch. 3 Adjectives → 3.1 outline, 3.2 indefinite declension, 3.3 definite
declension, 3.4 comparison, matching 1st-edition §§44–63 exactly; Ch. 4 Numerals, Ch. 5 Pronouns,
Ch. 7 Adverbs, Ch. 8 Prepositions, Ch. 9 Interjections, Ch. 10 Conjunctions, Ch. 11 Word order all
align). The only visible difference is cosmetic: the 2nd edition uses **decimal section numbering**
(e.g. "8.2.1 Af") instead of the 1st edition's flat running numbering (1–176), and at least one
subsection is **retitled** — 1st-edition "amplifiers"/"diminishers" (§109.2–3) appears in the 2nd
edition's TOC as "7.6 Uptoners and downtoners" (7.6.1 Uptoners, 7.6.2 Downtoners). The larger page
count (285 vs. 225) is consistent with a smaller physical page size (242×301pt vs. 540×666pt per
`pdfinfo`) reflowing the same content, not added material. **No genuinely new grammar point,
example set, or vocabulary was identified in the portions spot-checked**; this is recorded as the
scope decision per the extraction spec's "non-redundant supplement" pattern — a fuller page-by-page
vision read of all 285 pages was not performed given this finding, and this note makes that scope
decision auditable. If a native-speaker or deeper future pass finds the 2nd edition is a genuine
content revision beyond cosmetic renumbering, this note should be revisited.

**Coverage note:** This is the first-ever Danish extraction for this project (no prior
`established/` content to check for redundancy). Given the book's size (176 numbered grammar
points across 14 chapters plus extensive worked vocabulary embedded in nearly every section), this
file captures **every grammar point** (paraphrased, organized by chapter) and a **comprehensive,
representative sample** of the book's vocabulary — full coverage of every explicit enumerated list
(prepositions, numerals, personal/possessive/demonstrative/interrogative/indefinite pronouns,
nationality words, interjections incl. expletives, coordinating/subordinating conjunctions, strong
verb gradation series) plus representative examples from the noun/adjective/word-formation chapters'
much larger pool of illustrative vocabulary (full reproduction of which would mean bulk-reproducing
the book's own vocabulary boxes — excluded per copyright discipline). The abbreviations list in
§165 is a ~200-entry reference table; only a representative sample is kept here for the same reason.

**Vision-reading guard:** This source has a confirmed, clean text layer (`pdftotext -layout`
extracted the whole book correctly, including æ/ø/å) and was **not** vision-read, so no marginalia
check was needed for the bulk of the book. **One narrow, confirmed exception:** Chapter 1
(Pronunciation/Stress, §§1–21) uses a custom embedded font (`AKGAFJ+Century`) to render
stress-underline marks beneath specific letters in its worked example sentences (e.g. the "Lis has
bought a house" / stress-pattern illustration set under §§13–21). This custom font's glyphs extract
as **empty/invisible characters**, not garbled text — a different failure mode from the font-cipher
and image-embedding gotchas in the extraction spec, closer to the "stress-mark-only corruption"
pattern documented for some Russian sources, but total (whole example sentences vanish, not just
accent marks). The surrounding English translations and rule descriptions extracted fine; only the
bolded/underlined Danish example words in §§13–21 specifically were affected. This was **not**
vision-read as a fallback (narrow in scope, low marginal value relative to the rest of the book);
the grammar points in question are summarized below from the surrounding prose instead. All other
chapters, including the rest of Chapter 1 (phonology proper, §§1–12), extracted cleanly.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| en dreng / en kone / en lærer | a boy / a wife / a teacher | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | common-gender-by-meaning examples, §23 |
| et barn / et menneske / et dyr | a child / a human being / an animal | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | neuter-gender exceptions to the "humans=common gender" rule, §23 |
| en avis — aviser | a newspaper — newspapers | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | 1st-declension (-er) plural model, §24/26 |
| en dag — dage; et hus — huse | a day — days; a house — houses | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | 2nd-declension (-e) plural model, §24/27 |
| en sko — sko; et år — år | a shoe — shoes; a year — years | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | 3rd-declension (zero) plural model, §24/28 |
| en bog — bøger; en hånd — hænder; et barn — børn; en mand — mænd | book(s); hand(s); child(ren); man/men | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | plural with stem vowel change, §29 |
| møbler, furniture; nyheder, news; penge, money; råd, advice; kontanter, cash; oplysninger, information | — | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | singular-in-English/plural-in-Danish nouns, §36 |
| dansk / dansker(e); engelsk / englænder(e); svensk / svensker(e); tysk / tysker(e); amerikansk / amerikaner(e) | Danish/a Dane; English/an Englishman; Swedish/a Swede; German/a German; American/an American | adjective, noun | core | — | contemporary (source published 2000) | — | national | grammar_reference | n/a | n/a | full nationality-word table, §55 (14 countries total; see grammar points) |
| glad — gladere — gladest | happy — happier — happiest | adjective | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | regular -ere/-est comparison model, §57 |
| god — bedre — bedst; dårlig/slem — værre — værst; gammel — ældre — ældst; lille/lidt — mindre — mindst; mange — flere — flest; meget — mere — mest | good/bad/old/small/many/much, comparative, superlative | adjective | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | full irregular-comparison set, §59 |
| nul, en/et, to, tre, fire, fem, seks, syv, otte, ni, ti | 0–10 | numeral | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | cardinal numbers, §64 |
| halvtreds (50), tres (60), halvfjerds (70), firs (80), halvfems (90) | 50/60/70/80/90 | numeral | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | vigesimal (base-20) numeral system — abbreviated forms of halvtredsindstyve etc., "2½×20" etc., §64.4; a simplified commercial alternative (toti, treti, firti…) also given |
| en snes, 20; et par, a pair; et dusin, a dozen; en halv snes, 10 | — | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | count-noun numeral idioms, §65.7 |
| jeg, du, han, hun, den, det, vi, I, de | I, you(sg), he, she, it, it, we, you(pl), they | pronoun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | subject personal pronouns, full paradigm §67 |
| mig, dig, ham, hende, den, det, os, jer, dem | me, you, him, her, it, it, us, you, them | pronoun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | object personal pronouns, §67 |
| De / Dem | you (polite sg./pl.) | pronoun | formal | — | contemporary (source published 2000) | — | national | grammar_reference | n/a | n/a | formal address pronoun, increasingly rare per the book's own note (§68.1: "most people now use the familiar du") |
| min/mit/mine, din/dit/dine, hans, hendes, dens/dets, vores, jeres, deres | my/your/his/her/its/our/your/their | pronoun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | possessive pronoun paradigm, §72 |
| sin/sit/sine | his/her/its own (reflexive possessive) | pronoun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | subject-bound reflexive possessive, contrasts with non-reflexive hans/hendes, §73 |
| hinanden | each other | pronoun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | sole modern reciprocal pronoun; hverandre (more than two) now "very formal and old-fashioned," §71 |
| denne/dette/disse vs. den/det/de | this/these vs. that/those | pronoun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | demonstratives, proximal/distal, §74 |
| hvem, hvad, hvilken/hvilket/hvilke, hvis | who, what, which, whose | pronoun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | interrogative pronouns, §77; hvor/hvordan/hvorfor/hvornår are interrogative adverbs |
| al/alt/alting/alle, begge, hver/hvert/enhver, ingen/intet/ingenting, lidt/få, man, megen/meget/mange, nogen/noget/nogle | all, both, each/every, no/none/nothing, little/few, one/you, much/many, some/any | pronoun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | indefinite pronoun set, §78 |
| arbejde, bygge, elske, forklare, hade, handle, hente, huske, lave, lege, lukke, pakke, prøve, snakke, spille, vaske, vente, åbne | work, build, love, explain, hate, act/shop, fetch, remember, do/make, play, close, pack, try, chat, play, wash, wait, open | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | frequent Conjugation I (weak) verbs, §80 |
| købe, røbe, dele, føle, tale, låne, mene, høre, lære, læse, rejse, vise | buy, betray/(råbe)shout, divide/share, feel, talk, borrow/lend, mean/think, hear, learn/teach, read, travel, show | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | Conjugation II (weak) verbs, §81 |
| have—har—havde—haft, gøre—gør—gjorde—gjort, sige—siger—sagde—sagt | have, do, say (full conjugation) | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | Conjugation III (weak, irregular) verbs, §82 |
| drikke—drak—drukket, drink; give—gav—givet, give; sidde—sad—siddet, sit; finde—fandt—fundet, find; binde—bandt—bundet, bind; springe—sprang—sprunget, jump; vinde—vandt—vundet, win | — | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | Conjugation IV strong verbs, -i- stem gradation series, §86 |
| skrive—skrev—skrevet, write; blive—blev—blevet, become; drive—drev—drevet, drive; gribe—greb—grebet, catch; ride—red—redet, ride; rive—rev—revet, scratch; glide—gled—gledet, glide | — | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | more -i- stem strong verbs, §86.3 |
| bide—bed—bidt, bite; skide—sked—skidt, shit; slide—sled—slidt, toil/wear; smide—smed—smidt, throw | — | verb | core/taboo (skide) | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | -i- stem gradation series i-e-i, §86.4; skide is the base verb behind the taboo expletive prefix skide- noted in §132.9 |
| synge—sang—sunget, sing; flyve—fløj—fløjet, fly; lyve—løj—løjet, lie (deceive); ryge—røg—røget, smoke; krybe—krøb—krøbet, crawl; fryse—frøs—frosset, freeze; skyde—skød—skudt, shoot; nyde—nød—nydt, enjoy | — | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | -y- stem strong verbs (five gradation series), §87 |
| hjælpe—hjalp—hjulpet, help; trække—trak—trukket, pull/draw; bære—bar—båret, carry; skære—skar—skåret, cut; stjæle—stjal—stjålet, steal; være—er—var—været, be | — | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | -æ- stem strong verbs, §88 |
| få—fik—fået, get; gå—gik—gået, go; slå—slog—slået, beat/hit; stå—stod—stået, stand | — | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | -å- stem strong verbs, §89 |
| falde—faldt—faldet, fall; hedde—hed—heddet, be called; holde—holdt—holdt, hold; komme—kom—kommet, come; sove—sov—sovet, sleep; græde—græd—grædt, cry/weep; løbe—løb—løbet, run | — | verb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | strong verbs with unchanging stem vowel, §90 |
| burde, kunne, måtte, skulle, turde, ville | should/ought, can, may/must, must/shall, dare, will/want | verb (modal) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | full modal verb set with irregular present tense, §100 |
| barbere sig, shave; gifte sig, marry; glæde sig til, look forward to; kede sig, be bored; rejse sig, get up; sætte sig, sit down; skynde sig, hurry; ærgre sig, be annoyed; øve sig, practise | — | verb (reflexive) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | reflexive verbs with no reflexive idea in English equivalent, §70/103.5 |
| fattes, findes, længes, lykkes, mindes, synes, trives, ældes | be lacking, exist, long, succeed, recall, seem, do well, age | verb (deponent) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | deponent -s verbs (passive form, active meaning), §104.3 |
| mødes, ses, skilles, skændes, slås, træffes | meet, meet, part, quarrel, fight, meet | verb (reciprocal) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | reciprocal -s verbs, §104.4 |
| ad, af, bag(ved), blandt, efter, for, foran, forbi, for…siden, fra, før, hos, i, (i)gennem, (i)mellem, (i)mod, langs, med, om, omkring, over, på, siden, til, trods, uden, under, ved | at/by, of/by, behind, among, after, before/for, in front of, past, ago, from, before, at (home of), in, through, between, towards, along, with, (a)round/about/in, around, over, on/for, since, until/to, despite, without, under, by/around | preposition | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | full "most common Danish prepositions" list, §113; the 12 asterisked as highest-frequency: af, efter, for, fra, i, med, om, på, til, under, ved, (i)mod |
| Amerika/amerikansk/amerikaner(e), Danmark/dansk/dansker(e), England/engelsk/englænder(e), Finland/finsk/finne(r), Frankrig/fransk/franskmand(-mænd), Grækenland/græsk/græker(e), Holland/hollandsk/hollænder(e), Irland/irsk/irer(e), Island/islandsk/islænding(e), Italien/italiensk/italiener(e), Japan/japansk/japaner(e), Kina/kinesisk/kineser(e), Litauen/litauisk/litauer(e), Norge/norsk/nordmand(-mænd), Rusland/russisk/russer(e), Spanien/spansk/spanier(e), Sverige/svensk/svensker(e), Tyskland/tysk/tysker(e) | country/adjective/inhabitant | noun, adjective | core | — | contemporary (source published 2000) | — | national | grammar_reference | n/a | n/a | full country/adjective/inhabitant table, §55 — note Norge/norsk/nordmand (irregular inhabitant noun) is directly relevant for cross-referencing against this project's existing Norwegian dataset |
| aldrig, da, der, dog, her, ikke, jo, just, kun, lidt, meget, netop, nok, nu, næppe, næsten, ofte, straks, vel | never, then, there, however, here, not, you know, exactly, only, a little, very/much, exactly, probably, now, scarcely, almost, often, immediately, I suppose | adverb | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | simple-adverb list, §107.1; several (jo, nok, vel, da, dog) are unstressed modal/discourse particles with no direct English equivalent, elaborated in §111.4 |
| gerne, ikke, langt/længe, da, dog, jo, lige, nemlig, nok, nu, sgu, skam, vel, vist | willingly/gladly, not, far/for-a-long-time, [modal particles] | adverb | core/colloquial (sgu) | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | "some difficult adverbs" chapter, §111; sgu ("Det ved jeg sgu ikke!", "How the hell should I know!") is explicitly glossed with taboo-adjacent force though the book itself doesn't tag it as a usage tier |
| og, eller, for, men, så | and, or, for/because, but, so | conjunction | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | full coordinating-conjunction set, §133 |
| at, om, når, da, siden, mens, inden, fordi, eftersom, hvis, selvom, skønt, for at, så at | that, whether, when, when(past), since, while, before, because, because, if, even though, though, in order to, so that | conjunction | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | subordinating conjunctions by semantic category (time/cause/condition/concession/intention/result/comparison), §134 |
| ih, åh, bravo, hurra, juhu, hovsa, nå, årh, øv, fy, føj, puh(a), uh(a), øh, av | [positive/negative exclamations, surprise, disgust, pain] | interjection | colloquial | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | Type 1 spontaneous-feeling interjections, §132.2–132.3; spoken-language register per the book's own framing |
| miav, muh, mæh, pruh, vov, øf; bang, ding-dong, plask, tik-tak | cat, cow, sheep, horse, dog, pig [animal sounds]; door/gun, bell, splash, clock [object sounds] | interjection | colloquial | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | onomatopoeia, §132.3 |
| ja, jo, javist/jovist, jamen, jaså, javel, nej, næ(h), tja(h) | yes, yes(countering negative), yes-emphatic, but/well, really(surprise), OK/yes-sir, no, well-no, well-maybe | interjection | colloquial | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | Type 2 formulaic affirmation/denial/uncertainty interjections, §132.5–7 |
| fandens/helvedes/satans, for fanden/helvede/satan, kraftedeme, lort, pis, sateme, sgu, skid, skide- (intensifying prefix, e.g. skidegod), ved gud | [devil/hell/damn-based oaths], shit, piss, [oath], [oath], shit, shit-as-intensifier (e.g. "bloody good"), by god | interjection (expletive) | taboo | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | **flagged explicit taboo-register vocabulary, §132.9** — this project's Danish triage found no dedicated slang/taboo title in the whole stash, so this short expletive list from an otherwise mainstream pedagogical grammar is unusually valuable; book explicitly glosses these as "expletives (mostly names for God, the Devil, diseases and excrement)" |
| for katten/pokker/søren, pokkers, skam, søreme | [euphemistic oaths — lit. "for the cat/the devil (mild)/Søren"] | interjection (euphemism) | colloquial | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | **flagged euphemistic register**, §132.9 — the book pairs these directly as milder substitutes for the taboo set above, a clean minimal-pair taboo/euphemism dataset |
| en strejke (← Eng. "strike"); en cykelhjelm (cykel+hjelm, "cycle helmet"); uven (u-+ven, lit. "un-friend" = enemy); p-pille (← præventiv-pille, "contraceptive pill") | — | noun | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | worked examples of the five word-formation processes (borrowing, compounding, affixation, abbreviation, conversion), §161 |
| LO (Landsorganisationen), bh (brassiere), Nato, Saab, p-plads (parkeringsplads), u-båd (undervandsbåd) | [Danish Trades Union Congress], bra, NATO, [car brand], car park, submarine | noun (abbreviation) | core | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | worked abbreviation-type examples (alphabetism/acronym/hybrid), §164 |
| f.eks. (for eksempel), bl.a. (blandt andet), dvs. (det vil sige), kr. (krone(r)), tlf. (telefon), hr./fru/frk. (herre/fru/frøken), kl. (klokken), m.m. (med mere), osv. is NOT listed but d.s. (det samme), ca. (cirka), vedr. (vedrørende) | e.g., among other things, that is to say, kroner, telephone, Mr/Mrs/Miss, o'clock, et cetera, the same, circa, regarding | abbreviation | formal | — | contemporary (source published 2000) | — | — | grammar_reference | n/a | n/a | representative sample of the ~200-entry common-abbreviations table, §165 (full table not reproduced — bulk vocabulary box, see copyright discipline) |

## Grammar points

### Chapter 1 — Pronunciation (§§1–21)

**Vowel and consonant system.** Danish has a dense vowel inventory distinguishing long/short pairs
across unrounded (i, e, æ, a) and rounded front (y, ø) and back (u, o, å) vowels, several with no
close English equivalent (cited against French/German reference points instead). Consonant letters
have position-dependent values: p/t/k are aspirated stop-initial but reduce to unaspirated [b]/[d]/[g]
elsewhere (producing true homophone pairs, e.g. *lappe*/*labbe*); d has three pronunciations (hard
[d] initially, soft [ð] medially/doubled, silent in clusters like *-ld/-nd/-rd*); g likewise alternates
hard/soft[j]/silent by environment. Several consonant clusters are predictably silent (*-lv*, *-ds*,
*-dt*) (§§4–8).

**Syllable loss and vowel merger (§9).** Unstressed medial *e* (schwa) is frequently dropped in both
nouns (*husene*) and common present-tense verb forms (*beder* → [beð]), and in rapid speech
unstressed *e* can merge entirely with an adjacent vowel.

**The glottal stop/'stød' (§§11–12).** A genuine phoneme, not just an allophonic feature: *stød*
distinguishes otherwise-identical word pairs (*man* "one" vs. *mand'* "man"; *hun* "she" vs. *hund'*
"dog"). It can only occur on stressed, voiced syllables — either a long vowel or a short
vowel+voiced consonant — meaning a word like *let* (short vowel + voiceless consonant) can never
take stød. Absent in some southern Danish dialects — an explicit regional note. Inflection generally
preserves a stem's stød pattern, but the book documents a dense set of systematic exceptions where
stød is gained or lost under specific inflectional/derivational conditions (plural formation,
neuter adjective forms, comparative/superlative, strong-verb past participles, imperatives) — see
§12 for the full conditioned list.

**Stress (§§13–21).** Danish distinguishes clause stress (which word-classes carry sentence-level
emphasis) from word stress (which syllable within a stressed word is prominent). As a default, nouns,
full verbs (except before a subject complement), and MPT (manner/place/time) expressions are
clause-stressed; modal verbs, personal pronouns/hv-words, unstressed object pronouns, and most
conjunctions are not. Two-word semantic units (preposition+noun, indefinite article+noun,
infinitive-marker+verb, etc.) place stress on the final word. Indigenous polysyllables default to
first-syllable stress; a set of derivational prefixes/suffixes are reliably stressed or unstressed
(listed exhaustively in §§18–21). *(Note: the book's own worked example sentences illustrating word-
and syllable-level stress patterns in this chapter did not extract as text — see the file header's
vision-reading-guard note; the rule statements above are drawn from the surrounding prose.)*

### Chapter 2 — Nouns (§§22–37)

**Gender (§§22–23).** Two genders: common gender (*en*-words, ~75%) and neuter (*et*-words, ~25%).
Gender is assigned partly by meaning (humans/animals/plants/rivers/months default common gender,
with a notable exception list of neuter nouns for young/diminished beings like *et barn*, *et lam*;
substances/areas/alphabet-letters/nouns-from-other-word-classes default neuter) and partly by form
(specific suffixes like *-else, -dom, -hed, -ion* reliably predict common gender; *-um, -ri, -ende*
reliably predict neuter; others like *-al, -at, -i* vary). Compound nouns take the gender of their
second element, with named exceptions. Matrimonial/functional feminine suffixes (*-inde, -ske*) are
noted as being curtailed in modern Danish for political-correctness reasons — an explicit
sociolinguistic register note (§23.7).

**Plural formation (§§24–36).** Three declensions by ending: *-(e)r* (~75% of nouns, 1st
declension), *-e* (~15%, 2nd declension), and zero (~10%, 3rd declension) — predictable largely from
syllable count, stress position, and final segment, with a further subclass showing root vowel
change (*tand→tænder*, *bog→bøger*, *mand→mænd*). Loanwords from Latin/Italian often keep source-
language plurals (*faktum→fakta*) while English loans vacillate between retaining *-s* and
Danification. Danish also has true count/non-count distinction with a few nouns showing both a
count and collective plural reading (*en øl→øller* "bottles" vs. *øl* "types"), and systematic
singular/plural mismatches against English in both directions (§36).

**Genitive (§37).** A simple *-s* suffix attaches to the last word of the whole noun phrase ("group
genitive": *Herman Bangs romaner*), not per-word as in some related languages; nouns following a
genitive never take the end article. Two special uses: family/shop-name genitives (*hos Hansens*)
and measurement genitives (*et fyrreminutters program*).

**Articles (§§38–43).** Danish marks definiteness with a bound suffix (*-(e)n/-(e)t* singular,
*-(e)ne* plural) rather than a free-standing word — a "post-posed" or "end" article — but switches to
a preposed front article (*den/det/de*) when the noun is modified by an attributive adjective. Basic
definite/indefinite usage parallels English (first mention indefinite, subsequent/associated mention
definite), but several categorized mismatches are listed: Danish uses the end article where English
has none (abstract/generic nouns, many proverbs, some time/location idioms, §40); Danish omits an
article where English has a definite one (after *samme/næste*, some idioms, with proper nouns, §41);
Danish omits an article where English has an indefinite one (nationality/profession/religion/
political-affiliation predicate nouns, unless modified, §42); and Danish uses the end article where
English uses a possessive pronoun, for body parts/clothing where ownership is obvious (§43).

### Chapter 3 — Adjectives (§§44–63)

Danish adjectives inflect for gender (common/neuter, singular only) and number, both attributively
and predicatively, in the **indefinite declension** (zero/-t/-e by gender+number, §45), with a dense
set of subclasses that deviate from this main rule: neuter-same-as-common-gender adjectives
(those ending in *-(i)sk* or already in *-t*, §46), stem-vowel-drop before inflection (*-el/-en/-er*
adjectives, §47), several irregular/suppletive forms (*lille→små*, §48), consonant-doubling before
the plural ending (§49), and fully indeclinable classes (adjectives in unstressed *-e*, stressed
vowels, or *-s*, §50). A separate **definite declension** (adding *-e* uniformly) is triggered after
front articles/demonstratives, after genitives/possessives, or in certain fixed Type-3 constructions
with no preceding article (titles, place names, officialese, §53). Adjectives can themselves function
as nouns in three distinct ways (noun-ellipsis, understood-noun "adjectival nouns" like *de unge*
"young people", and fully independent nominal use, §54) — notably, Danish prefers true nationality
proper nouns (*englænderne*) over English-style adjectival-noun constructions ("the English") (§55).
**Comparison** has four distinct patterns: regular *-ere/-est* (most adjectives, §57), stem-vowel-
change + *-re/-(e)st* (only four adjectives: *få, lang, stor, ung*, §58), fully irregular/suppletive
(*god→bedre→bedst*, §59), and periphrastic *mere/mest* (participles, most polysyllables, *-isk/-sk*
adjectives, *-et* adjectives, §60) — with a semantic distinction noted between *værre/værst* ("more
of a bad quality") and *dårligere/dårligst* ("less of a good quality") for the same underlying
adjective, §59.2.

### Chapter 4 — Numerals (§§64–66)

Units precede tens (*seksogtyve* = "six-and-twenty" = 26), and numbers under 100 are written as one
word. The 50–100 range is **vigesimal** (base-20): *halvtreds* ("2½×20"=50), *tres* ("3×20"=60),
*halvfjerds* ("3½×20"=70), *firs* ("4×20"=80), *halvfems* ("4½×20"=90) — explicitly flagged by the
book as a source of confusion for learners, especially in telephone numbers. A simplified
commerce/inter-Nordic decimal-style alternative exists (*toti, treti, firti*…) alongside the
traditional system. The numeral *én* "one" takes an acute accent to distinguish it from the
indefinite article *en* and inflects for gender, uniquely among compound numerals. Fractions are
formed from ordinals + *-del(e)*; a comma (not a point) marks the decimal separator, mirroring the
rest of continental Europe against English/American convention. Time-telling uses a "half past the
NEXT hour" system (*halv syv* = "half seven" = 6:30, not 7:30) — a structurally significant
difference from English clock expressions worth flagging for any later mechanics-analysis pass, since
it's a genuine category mismatch rather than just vocabulary.

### Chapter 5 — Pronouns (§§67–78)

Full personal/reflexive paradigm (§67) distinguishes familiar *du* from polite *De* (§68.1 notes
*De* is now largely restricted to strangers, formal/official contexts, and addressing the elderly —
an explicit register/sociolinguistic note, with *du* dominant in school, work, family, and friend
contexts). Danish *den/det/de* serve triple duty as personal pronouns, front articles, and
demonstrative bases, but — unlike English "it/they" for animals — Danish *han/hun* is not used for
"higher animals" or countries (countries default neuter, agreeing with *et land*) (§68.2). *Det* has
an unusually wide idiomatic range beyond simple anaphora: formal subject of *være/blive*+predicate
nominal, formal subject of an infinitive phrase (competing with existential *der*), impersonal
weather/doorbell subject, object of belief/hope/fear verbs (≈English "so"), and echo-answers to
yes/no questions (§69). The **reflexive/non-reflexive possessive distinction** (*sin/sit/sine* vs.
*hans/hendes/dens/dets/deres*, §73) is presented as a genuinely hard point for English-speaking
learners: *sin* marks "own" and refers back to the clause's own subject, cannot itself modify the
subject, and cannot refer to a plural subject (where the non-reflexive *deres* is used instead) — the
book gives two practical disambiguation tests (arrow-to-referent; can you insert "own" in English).
**Demonstratives** (§74) distinguish proximal *denne/dette/disse* from distal *den/det/de*, with an
optional *her*/*der* suffix that the book explicitly marks as making the construction "much more
colloquial" — a register note. **Relative pronouns** (§§75–76) include *der* (subject-only, more
colloquial), *som* (any grammatical role, omissible when non-subject in a restrictive clause, cannot
be preceded directly by a stranded preposition), *hvis* (whose, written register), and *hvem/hvad/
hvilken* (more formal/written, with *hvilken* the only one that still inflects for gender/number).
Danish's restrictive/non-restrictive relative-clause distinction interacts directly with the comma
rules in Chapter 14 (§171). **Indefinite pronouns** (§78) are organized by a rich common/neuter/plural
system with numerous fixed idiomatic phrases (*alle tiders* "fantastic", *en gang for alle* "once and
for all") attached to the most frequent items (*al/alt/alle*, *begge*, *hver/enhver*).

### Chapter 6 — Verbs (§§79–106)

**Four conjugations** (§79): three weak (I *-ede*, II *-te*, III a small irregular group with *-de* +
vowel change, e.g. *have/gøre/sige*) and one strong (IV, ~120 verbs, monosyllabic past tense via zero-
ending/vowel-change or *-t*). Conjugation I takes >80% of weak verbs and is fully productive — "all
new verbs" (§80) join it, a live word-formation channel worth noting for a conlang slang-synthesis
pass (new coinages default to the most regular paradigm). Strong verbs are organized into
**gradation series** by stem vowel (a-, e-, i-, y-, æ-, å-, §§84–90) — e.g. the -i- stem's five series
alone cover ~25 common verbs — with the book noting the past participle's vowel can differ from
*both* the stem and the past-tense vowel in some series. **Infinitive use** (§91) drops the marker
*at* after modals, perception verbs, and *lade/bede*, but requires it before most other verbs and
disallows splitting (no equivalent to the English split infinitive). **Past/present participles**
(§§92–93) can function adjectivally, nominally (even taking an indefinite article in a few cases,
rare for a participle cross-linguistically, §93.3(b)), or adverbially as amplifiers. **Tense system**
(§§94–99): Danish has no formal continuous aspect (periphrastic alternatives exist: *være i gang
med at*, *være ved at*) and the present tense covers instantaneous, timeless, habitual, near-future,
and historic-present uses; the perfect tense (§96) splits its auxiliary by verb class — transitive
and non-motion intransitive verbs (incl. *have/være* themselves) take *har*, while motion/change
intransitives take *er* — a genuine split-intransitivity/unaccusativity pattern. There is **no formal
future tense**; *vil*+infinitive is the default periphrastic equivalent, with *skal*+infinitive
implying arrangement/promise and bare present+time-adverbial also common (§98). **Modal verbs**
(§100) carry heavily polysemous readings per verb (e.g. *skulle* covers rumour, future-in-the-past,
arrangement, promise, command, hypothetical, and uncertainty depending on context) — a rich source of
modal-semantic nuance. **Mood**: imperative = bare stem (§101); the present subjunctive (identical in
form to the infinitive) is "rarely used nowadays," surviving only in fixed wishes/curses/concessive
phrases (*Gud velsigne dig!*) — an explicitly marked archaic/formulaic register (§102). **Verb
transitivity classes** (§103) include a notable set of transitive/intransitive verb *pairs* sharing a
root meaning but differing in form — *lægge*(lay, weak)/*ligge*(lie, strong), *sætte*(set)/
*sidde*(sit), etc. — with the generalization that the transitive member of each pair is weak and the
intransitive member strong. **The -s passive, deponent verbs, and reciprocal verbs** (§104) all share
the same *-s* surface form but differ functionally — this is a three-way syncretism worth flagging for
mechanics analysis (identical morphology, three distinct grammatical functions disambiguated only by
the verb's lexical class and context). **The passive** (§105) has three competing constructions: the
*-s* passive (mainly modal/infinitive and habitual-present contexts), the *blive* passive (default for
single completed actions and all composite tenses), and the *være* passive (marks resultant state
rather than action) — with the book giving explicit minimal-pair examples showing how switching
passive type shifts modal meaning (*kan blive udtaget* "may be picked, it may happen" vs. *kan
udtages* "can be picked, nothing prevents it"). **Compound verbs** (§106) split into inseparable
(stressed-prefix/noun/adjective-initial compounds acting as a single stressed unit) and separable
(particle verbs where compounded vs. separated forms sometimes mean the same thing and sometimes
diverge, with the compounded form typically more formal/figurative and the separated form more
literal) — structurally comparable to German/Dutch separable-prefix verbs and worth a cross-language
note for this project's existing Dutch/German datasets.

### Chapter 7 — Adverbs (§§107–111)

Adverbs form a heterogeneous class: simple underived adverbs, adverbs derived from adjectives (by
adding *-t* to the neuter singular form — meaning the neuter adjective and its corresponding adverb
are frequently homophonous/homographic, §107.2), and adverbs built with a closed set of derivational
suffixes (*-deles, -ledes, -mæssig(t), -s, -sinde, -steds, -vis*). Comparison of adverbs largely
mirrors their source adjective's comparison pattern, with a few independent irregular adverbs
(*gerne→hellere→helst*, §108). Adverbs split functionally into amplifiers (strengthening, e.g. *meget,
ganske, alt for*) and diminishers (weakening, e.g. *lidt, næsten, temmelig*) when modifying an
adjective or another adverb (§109). A structurally distinctive feature is the **motion/location
adverb pairs** (§110): Danish systematically distinguishes a shorter "motion towards" form from a
longer "-e" location form for the same spatial relation (*hjem*/*hjemme*, *ud*/*ude*, *op*/*oppe* —
seven pairs total), a distinction "no longer found in English" per the book's own framing — this is a
genuinely productive grammaticalized motion/location contrast worth flagging prominently for
mechanics analysis. §111 catalogs a dense set of unstressed modal/discourse adverbs (*da, dog, jo,
nemlig, nok, skam, vel, vist*, plus the colloquial *sgu*) whose force the book admits is hard to state
in exact rules — these function similarly to German modal particles and are a strong candidate
source for future slang/colloquial register analysis.

### Chapter 8 — Prepositions (§§112–131)

Prepositions are classed by form (simple/compound/complex/discontinuous, §112.1) and by their
complement type (noun phrase, object pronoun, infinitive phrase, *at*-clause or hv-clause — notably,
unlike English, Danish allows a preposition to directly govern a full *at*-clause, §112.2). A
preposition's position can be pre-complement (majority), post-complement (rare, e.g. *dagen
igennem*), or bracketing/discontinuous (*for ti år siden*, "ten years ago" — the complement is
sandwiched between *for* and *siden*, §112.3). Danish freely **strands** prepositions at clause-final
position in hv-questions, relative clauses, topicalized-complement constructions, and infinitive
phrases (§112.3) — structurally like English stranding, unlike many other European languages.
Stress on monosyllabic prepositions is conditioned by whether their complement itself is stressed
(§112.4). §113 catalogs the twelve highest-frequency prepositions with worked example sets per
preposition (§§114–126: *af, efter, for, fra, i, med, (i)mod, om, over, på, til, under, ved*) — each
preposition shown covering multiple, sometimes unrelated, English-preposition equivalents (e.g. *af*
alone covers "by" (agent), "of/from" (material/source), "with" (cause), and "off" (direction)) — a
clear case of a single source-language form fanning out across several target-language categories,
useful for mechanics-analysis of preposition-based slang/idiom formation later.

### Chapter 9 — Interjections (§132)

Two functional types: **Type 1** spontaneous exclamations/feeling-expressions and onomatopoeia
(organized by the emotion expressed: delight, praise/excitement, surprise, annoyance, disapproval/
disgust, fear, hesitation, pain), explicitly commands given to animals vs. people; **Type 2**
formulaic conventional-situation words (affirmations, denials, uncertainty, greetings/partings/
seasonal greetings/thanks/apologies). Both types are framed by the book as chiefly belonging to
spoken language. **§132.9 Expletives** is the single most slang/taboo-relevant passage found across
this whole book — see the Vocabulary table above for the full list; the book itself labels this
category "mostly names for God, the Devil, diseases and excrement" and pairs it directly with a
matched euphemism set, giving a ready-made taboo/euphemism minimal-pair dataset.

### Chapter 10 — Conjunctions (§§133–136)

Coordinating conjunctions (§133: *og, eller, for, men, så*) never affect word order in the clauses
they join. Subordinating conjunctions (§134) split into "general subordinators" that carry no
independent meaning (*at* for reported speech, *om* for indirect yes/no questions) and meaning-
bearing subordinators organized by semantic category (time, cause, condition, concession, intention,
result, comparison) — each subordinator, like the prepositions above, often covers multiple English
conjunction-equivalents context-dependently (e.g. *når* vs. *da* both translate "when" but split on
repeated/present-future vs. single-past-event reference, §134.2(i), an aspectual distinction encoded
lexically rather than grammatically). §135 notes that interrogative and relative pronouns/adverbs also
introduce subordinate clauses despite not being conjunctions proper. §136 is a dedicated troubleshooting
section mapping ambiguous English conjunctions (after, as, as…as, before, both, but, if, that) onto
their correct Danish equivalents by sense — valuable as a worked set of near-synonym disambiguations.

### Chapter 11 — Word order and clause structure (§§137–160)

This chapter is the book's most structurally distinctive content and should be weighted heavily for
any future grammar-logic diagramming pass. Danish is a **V2 (verb-second) language**: finite-verb
position relative to the subject distinguishes five clause/sentence types by straight vs. inverted
word order (statement, hv-question, yes/no-question, imperative, exclamation, §138). The book
provides an explicit **seven-position main-clause schema** (k–X1–F–v–n–a–V–N–A–X2, fully laid out
with 19 worked examples in §155) that functions as a positional template: F (front) holds exactly one
clause element and is obligatorily filled in statements/hv-questions but vacant in yes/no-questions;
v (finite verb) is always filled; the clausal adverbial (a) — short modal adverbs, negation, etc. —
occupies a fixed slot immediately after the finite verb in main clauses. **Topicalisation** (§149) —
moving any clause element other than the subject into F — is pervasive and systematically shifts the
subject rightward into the n-slot rather than displacing the verb; natural (unstressed, cohesion-
building) topics are distinguished from emphatic/contrastive topicalisation. **Light elements**
(§150) — unstressed object/reflexive pronouns and unstressed *her/der* — obligatorily move leftward
into the n-position when the V-slot (non-finite verb) is empty, giving rise to genuine word-order
minimal pairs distinguishing stressed from unstressed pronominal objects. Crucially, **subordinate
clauses have a different, non-V2 template** (§156: k–n–a–v–V–N–A) where the clausal adverbial
precedes rather than follows the finite verb — the single most load-bearing word-order contrast
between main and subordinate clauses in the whole system, and the source of a common learner error
flagged explicitly in §159.2 (colloquial *at*-clauses sometimes leak main-clause order, "should never
be written"). **Existential sentences** (§153) require a formal subject *der* (when the real subject
is a postponed indefinite noun phrase) or *det* (when it's a postponed infinitive phrase) — structurally
parallel to English "there is/it is" constructions but grammaticalized as a formal two-way split by
real-subject type. **Cleft sentences** (§158) use *Det er/var X som/der…* to front-focus any
constituent, with *der/som* vs. *at* selected by whether the focused element is a non-adverbial noun
phrase/pronoun or a time/place adverbial. §160 closes with an explicit Danish-vs-English word-order
contrastive summary (4 numbered contrast patterns) aimed squarely at English-speaking learners'
typical errors.

### Chapter 12 — Word formation (§§161–165)

Five vocabulary-expansion processes are named: borrowing, compounding, affixation, abbreviation, and
conversion/change-of-class (§161). **Compounding** (§162) allows a wide range of first-element word
classes (noun/adjective/verb/pronoun/numeral/adverb/preposition/phrase) with the second element
usually noun/adjective/verb; compound nouns may link elements directly, via *-e-*, or via *-s-*, with
fairly systematic (though not fully predictable) rules governing which link applies based on the first
element's ending and whether it's itself already a compound. The second element always determines
the whole compound's gender — directly echoing §23.6's noun-gender rule. **Affixation** (§163)
distinguishes productive affixes (still actively coining new, semantically-transparent derivatives,
e.g. *-agtig* "like", *-bar* "-able") from non-productive ones frozen in a closed set of existing words
(*-dom* in *fattigdom/sygdom/ungdom*) — directly relevant to this project's eventual slang-coinage
mechanics, since productive affixes are the ones a synthesized slang layer could plausibly extend
further. **Abbreviation** (§164) has three subtypes: clipping (word-initial or word-final truncation),
blending/telescoping (middle removed, e.g. *moms* ← *merværdiomsætningsafgift*), and acronymy, itself
split into alphabetisms (letter-by-letter pronunciation), true acronyms (pronounced as a word, e.g.
*Nato*), and hybrid forms mixing an abbreviation with a full word (*p-plads*, *u-båd*). §165's ~200-
entry abbreviation table (sampled, not reproduced in full, in the Vocabulary section above) is a dense
register-formal resource (official correspondence, academic citation, commercial/administrative
shorthand).

### Chapter 13 — Orthography (§§166–169)

Danish's alphabet adds Æ/æ, Ø/ø, Å/å after Z; C/Q/W/X are marginal, loanword-only letters. The **1948
spelling reform** (§166) is presented as a significant discrete historical event: it introduced Å/å
(replacing double-*aa*), abolished noun-initial capitalization (previously German-style), and
regularized the modal spellings *kunde/skulde/vilde* → *kunne/skulle/ville*. §167 adds a genuinely
interesting historical-sociolinguistic note: some place names and individuals' surnames (e.g.
*Aabenraa*, *Aage Skovgaard*) retain the pre-reform *aa* spelling by individual/institutional choice
even though local authorities are legally required to use *å* — a live example of orthographic variant
persistence driven by personal/institutional identity rather than linguistic rule, and the new
letter's alphabetical position wasn't even settled until 1955, seven years after its introduction.
§168 catalogs systematic small-vs-capital contrasts with English (lowercase for days/months/
festivals/nationality words in Danish; capitalization patterns in multi-word proper-name phrases and
compound place names).

### Chapter 14 — Punctuation (§§170–176)

Danish underwent its own recent comma-convention reform, paralleling the orthography reform
historically if not in date: a "traditional"/clause-based comma system coexisted with a "pause"
comma until 1996, when Dansk Sprognævn (the Danish National Language Council) introduced a "new
comma" (closer to the old pause-comma) while formally preserving the traditional system (renamed the
"grammatical comma") as a second legitimate option — the book explicitly adopts and teaches the "new
comma" as the nationally recommended standard (§171), with a systematic restrictive/non-restrictive
relative clause-comma distinction mirroring English but inverted at points (no comma before a
restrictive relative clause, but one *after* it when it opens the sentence, §171.1(d)). Danish uses a
**decimal comma** where English uses a decimal point and vice versa for thousands-separators (§172) —
a notational trap for any numeral-heavy slang/measurement-term synthesis later. Direct speech can be
marked by dash, inverted commas, or guillemets, with no single dominant convention identified (§174).
The apostrophe is **not** used for the genitive (unlike English) except after proper nouns already
ending in -s/-x/-z, and otherwise appears only to mark certain abbreviation-plus-inflection boundaries
(*pc'en*, *tv'et*) or after numerals (*1990'erne*) (§175).

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`. The §165 abbreviations
table and the extensive strong-verb gradation tables in Chapter 6 were sampled rather than
reproduced in full for this reason.
