# Danish — Established Vocabulary/Grammar: Non-Redundant Supplement + Reader Survey

**Source:** Elias Bredsdorff, *Danish: An Elementary Grammar and Reader* (Cambridge University
Press; preface to first edition dated Cambridge, 20 May 1958), covering Part I (An Introduction to
Danish, pp.1–17), Part II (Danish Phonetics, pp.18–45), Part III (Grammar: Nouns, Adjectives,
Adverbs, Numerals, Pronouns, Regular Verbs, Irregular Verbs, Conjunctions, Prepositions,
Interjections, Word Order, Word Formation, pp.46–181), Part IV (Useful Words and General
Information, pp.183–199), and Part V (Danish Texts — a literary reader, pp.200–286, of which this
pass samples a representative cross-section rather than all 25 pieces). Part VI (Twenty Texts for
Danish Composition, pp.289+ — English sentences for translation-practice drilling) was not
extracted; it is pure pedagogical drill material with no authentic Danish content, squarely the kind
of repeated-exercise material the extraction spec's coverage rule excludes.

**Non-redundant-supplement scope decision (Parts I–III):** This is this project's **third** Danish
grammar-reference source and its structure (Nouns → Adjectives → Adverbs → Numerals → Pronouns →
Verbs → Conjunctions → Prepositions → Interjections → Word Order → Word Formation) maps almost
one-to-one onto `001_danish_an_essential_grammar.md`'s own chapter sequence, which was extracted
first in this wave and in much greater depth. Per the extraction spec's "non-redundant supplement"
dispatch pattern, **Parts I–III were spot-checked across ~8 representative spreads (Nouns, Regular
Verbs, Irregular Verbs, Adverbs, Word Formation) rather than fully re-extracted**, since the core
grammatical facts (two-gender system, enclitic article, three-way plural formation, adjective
agreement, invariant-by-person present tense, the four-conjugation weak/strong verb split, etc.) are
already captured from `001` and agree completely where compared. **What was kept as genuinely new**
is noted below: (1) this source's own IPA-flavored phonetic transcription system is a **fourth**
independent cross-check of Danish pronunciation within this wave (distinct from `001`'s IPA, `003`'s
informal respelling, and `004`'s American-English-calibrated respelling); (2) a few grammar notes not
seen as explicitly in `001` are recorded in the Grammar points section below (e.g. the "whole phrase
used where English uses a bare infinitive" observation, and the word-formation chapter's fuller
prefix/compounding treatment); (3) Part III's Irregular Verbs chapter gives a **complete alphabetical
paradigm table with full phonetic transcription for every strong verb**, more systematic in
organization (though substantially overlapping in actual verb coverage) than `001`'s
gradation-series presentation — not re-transcribed here in full per copyright discipline, but noted
as a more complete reference resource if exact paradigm detail is needed later.

**What is NOT redundant and is extracted in full below:** Part IV ("Useful Words and General
Information") contains real content not covered by `001`, `003`, or `004` — notably Danish public
holidays, region-specific demonyms (Jutland/Zealand/Funen/Greenland/Faroes), a fuller kinship-term
set distinguishing paternal/maternal relatives, and a pre-decimal-era monetary reference (with 1958
Sterling-equivalent conversions) — and is extracted as genuinely new vocabulary. **Part V (Danish
Texts) is the standout non-redundant content of this entire book** and of this whole four-book wave:
it is the only authentic-register literary reader in the Danish corpus so far, containing actual
folk tales, a named regional-humor genre (*Molbohistorier*), literary excerpts, a fairy tale, a
proverb collection, and canonical poetry/philosophical prose — none of which exists in any other
source extracted this wave. This file focuses its real extraction effort there.

**Vision-reading guard:** This source has no text layer and was fully vision-read via
`pdftoppm -png -r 120`. **Confirmed two-printed-pages-per-scan-image spread layout**, calibrated and
verified against the book's own printed page-footer numbers (image N ≈ printed pages 2N−14 and
2N−13 for N≥8, confirmed exactly at image 30 = printed pp. 46–47, the start of Part III). The book's
source PDF also reports a 270° page rotation (`pdfinfo`), correctly handled transparently by
`pdftoppm`. All content viewed was clearly typeset — no handwritten marginalia was found in any of
the ~25 spreads examined.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Nytårsdag, Fastelavn, Palmesøndag, Skærtorsdag, Langfredag, Påskedag, Befrielsesdagen, Kristi Himmelfartsdag, Pinsedag, Grundlovsdag, Valdemarsdag, Juledag | New Year's Day, Shrovetide, Palm Sunday, Maundy Thursday, Good Friday, Easter Sunday, Liberation Day (5 May), Ascension Day, Whit Sunday, Constitution Day (5 June), Danish Flag Day (15 June), Christmas Day | noun (proper, holiday) | formal/regional | — | 1958 (source publication date) — **Befrielsesdagen specifically dates the whole list to post-1945** | — | national (Danish) | grammar_reference | n/a | verified | full Danish public-holiday list, p.187; Befrielsesdagen commemorates the 1945 liberation from German occupation — a historically dateable entry distinct from the older religious/royal holidays around it |
| Jylland/jysk/jyde; Sjælland/sjællandsk/sjællænder; Fyn/fynsk/fynbo; København/københavnsk/københavner; Grønland/grønlandsk/grønlænder; Færøerne/færøsk/færing | Jutland/adj./inhabitant; Zealand/adj./inhabitant; Funen/adj./inhabitant; Copenhagen/adj./inhabitant; Greenland/adj./inhabitant; the Faroes/adj./inhabitant | noun, adjective | core/regional | — | contemporary (source published 1958) | Denmark (internal regions) + Greenland + Faroe Islands | regional/national | grammar_reference | n/a | verified | region-name/adjective/demonym triples, p.194 — genuinely new regional vocabulary not found in `001`/`003`/`004`; directly corroborates `004`'s claim that Danish extends to Greenland/Faroes with concrete region-specific terms |
| Far/Fader, Mor/Moder, Søn, Datter, Søster, Bror/Broder, Søskende, Forældre, Morfar/Bedstefar, Farfar/Bedstefar, Mormor/Bedstemor, Farmor/Bedstemor, Bedsteforældre, Oldefar, Oldemor, Oldeforældre, Tipoldeforældre, Farbror/Morbror/Onkel, Faster/Moster/Tante | father, mother, son, daughter, sister, brother, siblings, parents, maternal/paternal grandfather, maternal/paternal grandmother, grandparents, great-grandfather, great-grandmother, great-grandparents, great-great-grandparents, paternal/maternal uncle, paternal/maternal aunt | noun | core | — | contemporary (source published 1958) | — | — | grammar_reference | n/a | verified | full kinship-term set, p.189 — notably richer than `003`'s or `004`'s family vocabulary; **distinguishes paternal line (farbror, farmor) from maternal line (morbror, mormor)** the way older Germanic kinship systems do, a genuine morphological-typology feature (compound kinship terms built from far-/mor- + the relative noun) worth flagging for the project's typology checklist |
| en krone = 100 øre; en femkroneseddel, en tikroneseddel, en halvtredskroneseddel, en hundredkroneseddel, en femhundredkroneseddel; en øre, en toøre, en femøre, en tiøre, en femogtyveøre, en enkrone, en tokrone | the krone/øre monetary system and named banknote/coin denominations, with 1958 £-Sterling approximate equivalents given | noun | core/technical | — | **1958 (source publication date) — explicitly dated by its own £-Sterling conversion figures, pre-dating later currency/pricing changes** | — | national (Danish) | grammar_reference | n/a | verified | full monetary-system table, p.195 — this is the single most precisely-dateable vocabulary set in the whole Danish corpus so far, useful as an anchor point if later comparing against a modern source's pricing/currency vocabulary |
| A/S (Aktieselskab), bl.a. (blandt andet), ca. (cirka), d.v.s. (det vil sige), e.Kr./f.Kr. (efter/før Kristi fødsel), f.eks. (for eksempel), gl. (gammel), gldgs. (gammeldags), kgl. (kongelig), kl. (klokken), m.m. (med mere), nr. (nummer), o.s.v. (og så videre), s.k. (såkaldt), St. (Sankt) | Ltd., inter alia, circa, i.e., A.D./B.C., e.g., old, old-fashioned/obsolete, Royal, o'clock, and many others, No., etc., so-called, Saint | abbreviation | formal | — | contemporary (source published 1958) | — | — | grammar_reference | n/a | verified | sample of the ~45-entry common-abbreviations table, p.198–199 (full table not reproduced — bulk vocabulary box; this sample deliberately avoids heavy overlap with `001`'s own, larger and independently-sourced abbreviation sample) |
| Molboerne; Molbohistorier; en skælm | the inhabitants of the Mols peninsula (Jutland), proverbially portrayed as foolish; "Mols stories" — the named genre of Danish folk-humor tales about them; a rogue/trickster | noun (proper + genre term) | regional/folk/humor | — | **folkloric — source itself describes "Molbohistorier" as traditional tales of long standing, no single attestable date; collected/printed form dated 1958** | Mols peninsula, Østjylland (East Jutland) | regional | dictionary/folklore_reader | n/a | verified | **flagged as the single most valuable slang/humor-adjacent finding across the whole Danish wave** — p.205, explicitly glossed by the source as Denmark's direct structural equivalent to English "the wise men of Gotham": a geographically-anchored comic-stupidity stereotype genre, the same narrative mechanism (a real place name repurposed as a byword for foolishness) found cross-linguistically (cf. Polish jokes, Aggie jokes, Irish-bull jokes) — directly relevant to this project's regional/ethnic-stereotype-based humor-derivation mechanisms, a category this project has not yet seen a clean Danish example of |
| en kælling; Skohottentot, Skolinkenlot | an old woman/hag (now a pejorative/taboo-adjacent term in modern Danish, though glossed neutrally as "an old woman, a hag" by this 1958 source); nonsensical invented proper names | noun | taboo (modern)/archaic-neutral (as glossed here) | — | **source glosses this as neutral period (1958) usage; flagged as having since taken on a harsher taboo connotation in contemporary Danish, per general knowledge of the word's semantic drift — not verified against a newer Danish source in this project yet** | — | — | dictionary/folklore_reader | n/a | verified | "Den tykke kat" folk tale, p.200–202, footnoted gloss; **kælling is a strong candidate for a later usage-tier correction once a contemporary Danish slang/taboo source is extracted** — flagged explicitly rather than silently tagged `core`, since a 1958 pedagogical gloss is not sufficient evidence for current register |
| mod nord, syd for, østenvind, søndenvind, nordvest, sydøst | to the north, south of, east wind, south wind, northwest, southeast | noun/adverbial phrase | core | — | contemporary (source published 1958) | — | — | grammar_reference | n/a | verified | cardinal-direction idiom set, p.188 |
| Den er dobbelt arm, som har været rig.; Nød lærer nøgen kone at spinde.; På en rullende sten gror intet mos.; Blind høne finder også et korn.; Fanden er god, når han får sin vilje. | "Doubly poor is he who was once rich."; "Necessity teaches a naked woman to spin."; "A rolling stone gathers no moss."; "Even a blind hen finds a grain."; "The Devil is good-humored when he gets his way." | phrase (proverb) | literary/idiomatic | — | folkloric/traditional (collected 1958) | — | national (Danish) | dictionary/folklore_reader | n/a | verified | sample of the ~25-entry "Danske ordsprog" (Danish proverbs) collection, pp.209–211 — direct figurative/idiomatic-compression source material, genuinely valuable for mechanics-analysis of how Danish compresses meaning into fixed sayings; full list not reproduced per copyright discipline but see Grammar points for more |
| grød, havregrød; en kælling; passe; en madamme; en brændehugger; en stand (plur. stænder) | porridge, oatmeal porridge; an old woman/hag; look after, mind; (old-fashioned) a married woman; a wood-cutter; a social class/estate | noun, verb | archaic/core | — | contemporary to the folk-tale genre (undated) / 1958 gloss | — | — | dictionary/folklore_reader | n/a | verified | footnoted glosses from "Den tykke kat," p.200–201 — several explicitly marked by the source itself as old-fashioned (e.g. *en madamme*, p.202 n.1) |
| værge, Gothen, spejl(=poop/stern), fly(=flygte), hejse, give agt på, brag | weapon/defence (archaic/poetic), "the Swedes" (archaic/poetic ethnonym), stern of a ship, flee (poetic/archaic for "flygte"), hoist, pay attention to, roaring | noun, verb | literary/archaic | — | 1779 (poem's composition date, per source's own footnote) | — | national (Danish) | dictionary/folklore_reader | n/a | verified | vocabulary from "Kong Christian" (Johannes Ewald, 1779), explicitly identified by the source as the Danish national/royal anthem, p.282–283 — a formal/archaic/poetic register sample, genuinely distinct from every other register in this project's Danish corpus so far |
| heftig, bevæget, selvbevidst, sejrrig, forjasket, livsalig, forkærlighed, et bibegreb, smdsnakken, dulgt | impetuous, passionate, self-aware, victorious, slovenly, blessed, partiality/fondness, a subordinate/connotative idea, light chattering, hidden/concealed | adjective, noun | literary/formal | — | 1851 or earlier (Kierkegaard, d.1855) / source gloss 1958 | — | national (Danish) | dictionary/folklore_reader | n/a | verified | sample of ~25 footnoted glosses from Søren Kierkegaard's "Det danske sprog" ("The Danish Language"), pp.278–279 — a dense single-sentence philosophical reflection on the Danish mother tongue itself; the single highest-register literary/abstract vocabulary sample in this project's Danish corpus to date |

## Grammar points

### Parts I–III: spot-checked, largely redundant with `001`

The introductory chapters (Danish Alphabet, Written/Spoken Language) open with a pedagogically
distinctive device not found in `001`, `003`, or `004`: three short, deliberately cognate-rich Danish
texts (including a mock detective story, "En idiotisk kriminalhistorie") presented *before* any
grammar instruction, intended to demonstrate directly to an English-speaking beginner how much Danish
can already be guessed from English-Danish lexical cognates — "90–100 per cent" comprehensible, per
the author's own claim, from fewer than 150 common words. This pedagogical framing device (lead with
cognate-rich authentic text to build confidence, rather than starting from grammar rules) is itself a
worthwhile methodological note, distinct from any content point.

The Phonetics part (Part II) uses its own IPA-flavored bracketed transcription (e.g. *en mand*
[en man?], *et hus* [ed hu:?s] — note the question-mark glyph standing in for the glottal stop/stød
marker) — independently consistent with `001`'s and `003`'s accounts of Danish vowel length,
consonant lenition, and the glottal stop, adding no new phonological claims but serving as a fourth
cross-reference transcription system within this project's Danish corpus.

The Grammar part (Part III) confirms, without contradiction, every major structural point already
documented in `001`: two-gender nouns with enclitic definite article (including the identical
consonant-doubling-before-article and *-el/-en/-er* stem-vowel-drop rules); adjective agreement by
the same zero/-t/-e pattern; invariant-by-person present-tense verb morphology; the weak/strong verb
split with the same broad gradation-series organization (though Part III here presents the full
irregular-verb list in strict alphabetical order with complete phonetic transcription for every verb,
rather than `001`'s grouping-by-stem-vowel approach — a difference in organization, not in underlying
fact). Two points worth recording as genuinely additional detail: (1) the Regular Verbs chapter notes
explicitly that **a whole subordinate phrase is often used in Danish in places where English would be
satisfied with a bare infinitive** (worked example: *Jeg sagde til ham, at han skulle gå* rather than
a more English-like "I told him to go") — a construction-level (not just lexical) divergence not
spelled out this explicitly in `001`; (2) the Word Formation chapter gives a fuller, more systematic
treatment of Danish prefixes (*be-, er-, for-, und-* — identified explicitly as cognate with German
*be-, er-, ver-, ent-*) and of the linking consonants *-s-*/*-e-* in compound nouns (tied to specific
morphological conditioning rules: an *-s-* link after nouns ending in certain derivational suffixes or
that are themselves already compounds; an *-e-* link reflecting a fossilized historical genitive or
plural, or when bridging a consonant-final first element and consonant-initial second element) — more
granular than `001`'s equivalent §162 treatment, worth treating as the fuller reference if exact
compounding rules are needed later.

### Part IV: Useful Words and General Information

This section is a condensed practical-vocabulary appendix, comparable in *function* to `004`'s phrase
dictionary but organized as topic-by-topic word lists rather than full conversational phrase pairs.
Its genuinely new content — not duplicated by `001`, `003`, or `004` — is captured in full in the
Vocabulary table above: the complete Danish public-holiday calendar (with the single historically
dateable entry *Befrielsesdagen*, 5 May, commemorating the 1945 liberation from German occupation,
anchoring this whole word list to the post-WWII era regardless of the book's own 1958 publication
date); a region-name/adjective/demonym vocabulary set covering Jutland, Zealand, Funen, Copenhagen,
Greenland, and the Faroes (the latter two directly corroborating `004`'s claim, from this wave's
Introduction section, that Danish extends as a language of record to Greenland and the Faroe Islands);
a richer kinship-term set than any other source in this wave, notably preserving a paternal/maternal
line distinction in Danish's compound uncle/aunt/grandparent terms (*farbror* "father's brother" vs.
*morbror* "mother's brother," etc.) — a genuine morphological/kinship-typology feature worth flagging
for this language's eventual typology-checklist entry; and a pre-decimal-era monetary-system table
(100 øre = 1 krone, with named banknote and coin denominations) carrying explicit 1958 £-Sterling
conversion figures, making it the single most precisely historically-dated vocabulary set anywhere in
this project's Danish corpus — a useful anchor point for any later diachronic pricing/currency-slang
comparison.

### Part V: Danish Texts (the Reader) — this book's standout contribution

This is a genuine literary anthology spanning folk tale, literary short fiction, a translated fairy
tale, proverbs, essayistic/philosophical prose, and national poetry — a register range not present
anywhere else in this project's Danish material, which otherwise consists entirely of grammar
exposition and travel-phrase content. A representative cross-section (6 of the Reader's 25 pieces,
plus the full proverb collection) was read in full; the remaining pieces (further H. C. Andersen,
Otto Jespersen on language teaching, Ludvig Holberg, Georg Brandes, Johannes V. Jensen, Kaj Munk,
Kjeld Abell, additional patriotic poetry) were not individually sampled given this wave's time budget,
but their presence is noted here for any future session that wants to extract more of this reader —
their authors and topics are listed in full in this file's header source citation.

**"Den tykke kat" ("The Fat Cat")** — an anonymous Danish folk tale (source labels it "Gammelt dansk
folkeeventyr," "an old Danish folk tale") in the cumulative/chain-tale structure found cross-
linguistically (cf. "The Gingerbread Man," "The House That Jack Built"): a cat that has eaten its
owner's porridge keeps eating everyone and everything it subsequently encounters, each time repeating
a formulaic refrain listing everything consumed so far, until a woodcutter cuts it open and
everyone/everything escapes. Notably uses two deliberately nonsensical invented proper names
(*Skohottentot*, *Skolinkenlot*) for characters the cat meets on the road — the source's own footnote
explicitly flags these as meaningless, playful coinages, a clean example of nonsense-name word
formation for comic/folkloric effect.

**"Præsten og hyrden" ("The Priest and the Shepherd")** — another labeled "Gammelt dansk folkeeventyr"
(old Danish folk tale), structurally a wisdom/riddle-contest tale: a king challenges a proud priest to
answer three impossible riddles (how deep is the sea to its bottom; what is the king's worth; what is
the king thinking) on pain of losing his position, and a clever shepherd solves them in the priest's
place with trickster-logic answers (the sea is "one stone's throw" deep "if you measure from the
bottom"; the king is worth 29 pieces of silver, "one less than Christ, who was sold for 30"), is
rewarded by being made priest himself. A classic "clever peasant outwits the powerful" folk-narrative
structure.

**"To Molbohistorier" ("Two Mols Stories")** — see the Vocabulary table's flagged entry on
*Molboerne*/*Molbohistorier* for the full genre explanation. The two sampled stories ("Kirkeklokken,"
The Church Bell, and "Hummerne," The Lobsters) both follow the noodle-head/numbskull-folk comic
structure: in the first, the villagers sink their church bell in the sea to hide it from an advancing
enemy, then carve a notch in the side of their boat to mark the spot — not grasping that the boat (and
thus the notch) will move, while the sunken bell will not; in the second, an old Molbo who has never
seen a Norwegian ship goes aboard an empty Norwegian vessel and mistakes a crawling lobster for the
ship's crew, greeting it formally ("Goddag, Farlil!") before concluding, after it pinches his hand,
that "the Norwegians are small folk, but they have a strong handshake." Both stories are explicitly
sourced by the book to a specific 1950s-era gramophone recording (*Det Danske Selskab*, read by actor
Thorkild Roose) — i.e. this genre had an active audio/oral-performance tradition contemporaneous with
the book's own publication, not just a purely literary existence.

**"En jysk røverhistorie" ("A Jutland Robber Story", Steen Steensen Blicher, 1782–1848)** — a literary
short story (explicitly labeled "Noget omarbejdet," "somewhat adapted," i.e. abridged/simplified for
this reader) about a farmhouse besieged by a gang of robbers on Christmas Eve, foiled by a clever
servant-boy who slips out disguised, raises the neighboring estate, and leads a counter-ambush. Blicher
is identified by the source as a Danish poet and short-story writer whose "subjects are often taken
from his native Jutland" — i.e. explicitly regional literature, paralleling the Molbohistorier's own
regional anchoring in a different register (literary short fiction vs. oral folk humor).

**"Prinsessen på ærten" ("The Princess and the Pea", H. C. Andersen, 1805–75)** — Andersen's own
original-Danish text of this canonical fairy tale, given in full. Notable vocabulary/register point:
Andersen's prose style here is markedly more colloquial and exclamation-heavy than either the older
folk tales or Blicher's literary prose, with frequent first-person-style exclamatory asides even in
third-person narration ("Det er ganske forskrækkeligt!" "It's absolutely dreadful!") — a recognizable
authorial voice distinct from the anonymous folk-tale register.

**"Danske ordsprog" ("Danish Proverbs")** — a ~25-entry proverb collection, the single richest
figurative-language/idiom source in this project's Danish corpus. Beyond the sample already recorded
in the Vocabulary table, structurally notable proverbs include several built on reported-speech
frame constructions unique to Danish proverb style — a fixed pattern of "[proverb statement], sagde
[stock character], han/hun [absurd or ironic action]" (e.g. "Det var een, sagde trolden, han tog to
skræddere" — "That makes one, said the troll, as he took two tailors" — an ironic-counting joke
structure; "Der faldt noget, sagde skrædderen, han trillede under bordet" — "Something fell, said the
tailor, as he rolled under the table" — a euphemism-via-dry-understatement structure). This
attributed-saying-plus-ironic-action template is a distinct Danish proverbial sub-genre worth flagging
explicitly for any later mechanics-analysis of how Danish folk speech encodes irony and dry humor
structurally, not just lexically.

**"Det danske sprog" ("The Danish Language", Søren Kierkegaard, 1813–55)** — a single dense,
multi-clause sentence of philosophical prose reflecting on Kierkegaard's own feeling of being "bound
to a mother tongue" that does not "pant" or sound "strained" even when expressing the inexpressible.
Stylistically the polar opposite of the folk-tale/proverb material: long periodic sentence structure,
abstract/literary vocabulary (see Vocabulary table sample), characteristic 19th-century Danish
philosophical-essay register. Valuable as the clearest "high formal/literary" register anchor point in
this project's Danish corpus, contrasted against the colloquial/practical registers dominating `003`
and `004`.

**"Kong Christian" (Johannes Ewald, 1743–81, composed 1779)** — the Danish national/royal anthem,
given here with its full text and extensive historical footnoting (identifying King Christian IV and
his 1644 naval victory at Kolberger Heide, the admirals Niels Juel and Peter Wessel/"Tordenskjold,"
and the archaic/poetic vocabulary the anthem itself preserves, e.g. *Gothen* as an archaic-poetic term
for "the Swedes," *spejl* in the nautical sense "stern/poop" rather than its modern meaning "mirror").
A formal/archaic/patriotic-register anchor point, textually and historically distinct from every other
piece sampled from this Reader.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`. The full Danish-text
pieces in Part V (several hundred words of running narrative each) were paraphrased/summarized here,
not transcribed; only short illustrative phrases are quoted directly. The abbreviations table (Part
IV) and the irregular-verb paradigm table (Part III) were sampled rather than reproduced in full for
the same reason.
