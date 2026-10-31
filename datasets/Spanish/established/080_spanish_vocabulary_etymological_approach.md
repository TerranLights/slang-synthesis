# Spanish — Established Vocabulary: Spanish Vocabulary, An Etymological Approach (Brodsky)

**Source:** David Brodsky, *Spanish Vocabulary: An Etymological Approach* (University of Texas
Press, 2007), 655 pp. Clean text-layer PDF (`pdftotext`/`pdftotext -layout` cross-checked, no
vision reading needed). Structured in four parts plus four annexes: Part I (background on Spanish
as a Romance language); Part II (Classical Vocabulary — "learned" Latin and Greek words, little
changed in form); Part III (Popular Vocabulary — words that underwent systematic sound changes
during the Latin-to-Spanish evolution, organized by the specific phonological pattern); Part IV
(Selected Topics — Goths/Germanic contact, Arabs/Muslims, Numbers, Time, *Ser*/*Estar*, Food and
Animals, Religion, the Family, Body/Spirit/Mind, Romance languages and Politics); and four annexes
of additional word lists (gender-rule exceptions, "not-so-easy" words, *-cer* verbs, "100 relatively
easy words").

**Coverage decision: REPRESENTATIVE SAMPLING, not full extraction.** At 655 pages with a density
of roughly 15-30 cognate pairs per page in its list sections, full extraction is infeasible and
would mostly duplicate raw vocabulary already in this corpus's dictionaries (`047`, `048`, `050`)
and the Practice Makes Perfect series. What this book uniquely offers — and what this file
prioritizes — is not the vocabulary itself but **the derivational mechanism**: the specific sound
correspondences that turned Latin into Spanish, and the specific historical contact layers
(Germanic/Visigothic, Arabic/Andalusi) that seeded vocabulary strata still visible in the modern
language. This is exactly the kind of "mechanics" data a conlang-derivation pipeline needs — not
just *that* a word exists, but *the rule* that predictably produces whole families of words, and
the *contact-situation story* behind a borrowed stratum (directly comparable to the convergent
Hungarian gyerek→dzserek contact-sound-change finding from this project's Hungarian Phase 1).

This file therefore samples, for each of the book's organizing patterns, a representative
selection of word pairs (roughly 10-30 per pattern, chosen to show the rule's range and its most
memorable/productive examples) rather than the book's full lists (which run into the hundreds per
section). Each sampled section's header documents the pattern/rule itself, since the rule is the
real finding. Skipped entirely: Part I (pure background prose, no vocabulary), Part II (classical
Latin/Greek "learned" words whose Spanish form barely differs from English — essentially the
English word with a Spanish ending, low mechanism value, and heavily overlaps with dictionary-style
cognate lists already in this corpus), most of Part IV's thematic sections (Numbers, Time,
*Ser*/*Estar*, Food/Animals, Religion, Family, Body/Mind, Romance languages/Politics — these are
standard thematic word lists, redundant with `009`/`047`/`048`/`050`/`079`), and Annexes A, B, and
D (gender-rule exceptions and generic word lists without a distinct derivational mechanism). Kept:
all of Part III's five sound-change sections (the heart of the book's method), Part IV's two
historical-contact sections (Goths/Germans, Arabs/Muslims — genuine loanword-stratum content), and
Annex C (the *-cer* inceptive-verb family, a closed, self-contained morphological pattern with a
documented English cognate link via Old French *-ish*).

Source Type throughout: `grammar_reference`. Transcription Confidence: `verified` (clean digital
text layer; a handful of OCR ligature artifacts — "fi g" for "fig", stray accent/diacritic noise
in Latin-letter special symbols — were normalized during extraction). Vision Reading Confidence:
`n/a`. Attested Era: `contemporary (source published 2007)` throughout, per this project's
Historical/Geographic Context convention that `Attested Era` records when a form is *currently in
use*, not its etymological depth — the deep diachronic story (Latin root, date of sound change,
historical period of borrowing) is recorded in each row's Notes instead. Attested Region/Geographic
Scope: `—` unless the book ties a form to a specific country/region.

---

## Part III.1 — Addition of a "helping" e: Latin s+consonant → Spanish es+consonant

**The rule:** Vulgar Latin grammarians never allowed a syllable to begin with s+consonant; this
restriction, originally internal to words, was extended to word-initial position by adding a
prothetic *e-*. Italian later dropped the *e-*; French kept the *e-* but dropped the *s-*; Spanish
alone kept both, yielding the systematic correspondence Latin/English *sC-* → Spanish *esC-*.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| espina | thorn, spine | noun | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *spina*; the book's lead example of the es- pattern, cf. Fr. *épine* (dropped s), It. *spina* (kept s, dropped e) |
| escala | ladder, scale; (flight) stopover | noun | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *scala*; family: escalera (staircase), escalar (to climb/scale), escalón (step; cf. Eng. "echelon") |
| escudo | shield; escudo (currency) | noun | core | medium | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *scutum*; cf. Fr. *écu*, It. *scudo* |
| espíritu | spirit | noun | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *spiritus* |
| esposa | wife, spouse | noun | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *sponsa* |
| estado | state | noun | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *status* |
| esclavo | slave | noun | taboo | medium | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | From medieval Latin *sclavus* ("Slav"/"slave" — the ethnonym became an ethnic slur-turned-common-noun since so many enslaved people in the early medieval Mediterranean were Slavic); doublet with *eslavo* "Slav" |
| chao | bye, ciao | interjection | colloquial | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Traces through the *sclavus* family: Venetian dialect shortened *schiavo* ("your humble servant") to *ciao*, exported into Spanish as a farewell only — genuinely surprising etymological link between "slave" and the everyday greeting *chao/ciao* |
| escolar / escuela | scholastic / school | adjective/noun | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *schola* |
| escribir | to write | verb | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *scribere*; family: escritor (writer), escritorio (desk), escritura (handwriting/Scripture) |
| escrutar / escrutinio | to scrutinize / scrutiny, vote count | verb/noun | formal | medium | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *scrutari* |
| esmoquin | tuxedo | noun | core | medium | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Direct English loan "smoking (jacket)" fitted to the es- pattern rather than inherited from Latin — shows the pattern remaining productive for modern loanwords |
| esnob | snob | noun | colloquial | medium | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | English loanword, gives the section its title; same loanword-fitting-the-pattern phenomenon as *esmoquin* |
| esqueleto | skeleton | noun | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Gk. via Lat. |
| esquina | corner | noun | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Cognate obscured in English (cf. "shin, chine") |
| estrella | star | noun | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Likely a blend of Gk.-derived *astro-* with Lat. *stella*; family: constelación (constellation), estrellarse (to crash/smash) |
| estrategia | strategy | noun | formal | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Gk. via Lat.; family: estratega (strategist), estratagema (stratagem) |
| estudiante / estudiar | student / to study | noun/verb | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *studere* |

---

## Part III.2 — Initial f → (silent) h: Latin f- → Spanish h-

**The rule:** Word-initial Latin *f-* became (unpronounced, but written) Spanish *h-*, one of the
most distinctive features setting Spanish apart from Portuguese, Catalan, French, and Italian,
which all generally kept the *f-*. (Spanish later re-added *h-* in spelling-only to many *learned*
Latin borrowings that had also lost it, e.g. *habitante*, *heroísmo*, *honesto* — those are a
separate, later layer, not part of this popular-vocabulary sound change.)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| halcón | falcon | noun | core | medium | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *falco(n)*; cf. Port. *falcão*, Fr. *faucon*, It. *falco* (all keep f-) |
| harina | flour | noun | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *farina*; idiom *harina de otro costal* = lit. "flour from a different sack," i.e. "a horse of a different color" |
| higo / higuera | fig / fig tree | noun | core | medium | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *ficus*; the section's title example |
| hablar | to speak | verb | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *fabulari*; family: habla (speech), hablador (talkative/gossipy), fábula (fable, keeps f- as a learned borrowing) |
| hacer | to do, to make | verb | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *facere*; family: hecho (fact, p.p.), hacienda (ranch/public finance), rehacer (to redo), cohecho (bribery) |
| hambre | hunger | noun | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *faminem* (acc.) |
| harto / hartar | fed up / to satiate, to glut | adjective/verb | colloquial | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *fartus*; family: infarto (heart attack) |
| hastío / hastiar | weariness, boredom / to annoy | noun/verb | core | medium | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *fastidium*; doublet fastidiar/fastidioso (learned form, kept f-) |
| hado / hada | fate, destiny / fairy | noun | core | medium | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *fatum*; family: hada madrina (fairy godmother), cuento de hadas (fairy tale) |
| hembra / femenino | female (animal, n.) / feminine (adj.) | noun/adjective | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *femina*; shows the popular/learned split within one root (hembra = popular, femenino/feminista = learned, keep f-) |
| heno | hay | noun | core | medium | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *fenum*; fiebre del heno = hay fever |
| herir / herida | to wound / wound | verb/noun | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *ferire* |
| hierro | iron | noun | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *ferrum* |
| hervir / hervor | to boil / boiling | verb/noun | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *fervere*; learned doublet fervor/ferviente keep f- |
| hilo / hilar | thread / to spin | noun/verb | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *filum* |
| hija / hijo | daughter / son | noun | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *filia*/*filius*; learned doublet filial keeps f- |
| hoja / hojear | leaf, sheet (of paper) / to leaf through | noun/verb | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *folia* |
| hormiga / hormiguero | ant / anthill | noun | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *formica*; family: hormigueo (pins-and-needles), hormigón (concrete) |
| hermoso | beautiful | adjective | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *formosus*; cognate obscured in English (cf. place name Formosa) |
| huir / fugitivo | to flee / fugitive | verb/noun | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *fugere*; learned doublet fugitivo/prófugo keep f- |
| humo / fumar | smoke / to smoke (a cigarette) | noun/verb | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *fumus*; shows popular (humo) vs. the verb fumar retaining f- as a separate, later development |

---

## Part III.3 — Vowel changes: Latin e → ie, o → ue, and six other shifts

**The rule:** Spanish's vowel inventory has changed remarkably little since Classical Latin, but
in certain "popular" words the *stressed* vowel diphthongized or shifted on its way from Latin —
always with spelling following pronunciation. The two diphthong changes (e→ie, o→ue) are the most
frequent and are the source of Spanish's large class of "diphthong" (stem-changing) verbs: the
diphthong appears only when stress falls on that syllable, so related non-diphthong forms of the
same root exist alongside the diphthong form (*tiempo* vs. *temporal*; *pienso* vs. *pensamos*).

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| menos | minus, less | adverb | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Change type 1: i→e; < Lat. *minus* |
| sirviente | servant | noun | core | medium | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Change type 2: e→i; < Lat. *servientem* |
| cerca / acercar / cercano | near, close / to approach / nearby | adverb/verb/adjective | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Change type 3: e→ie (unstressed form, no diphthong since stress isn't on this syllable); < Lat. *circa* |
| ciento / cien | hundred | numeral | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Change type 3: e→ie (stressed, diphthongized); < Lat. *centum* |
| tiempo / temporal / temporario | time / temporal / temporary | noun/adjective | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *tempus*; textbook example of the stress-conditioned diphthong: *tiempo* (stressed, diphthongizes) vs. *temporal/temporario* (stress elsewhere, no diphthong) |
| pienso / pensamos | I think / we think | verb | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | *pensar* ("to think") as the canonical e→ie "diphthong verb" — diphthong appears only when the stem syllable is stressed |
| trecho | stretch, distance | noun | core | medium | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Change type 4: a→e; < Lat. *tractus* |
| puerco | pig, pork | noun | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Change type 5: o→ue; < Lat. *porcus* |
| muevo / movemos | I move / we move | verb | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | *mover* ("to move") as the canonical o→ue "diphthong verb" |
| cumplir | to complete, to accomplish | verb | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Change type 6: o→u; < Lat. *complere* |
| tronco | trunk | noun | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Change type 7: u→o; < Lat. *truncus* |
| toro | bull, Taurus | noun | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Change type 8: au→o; < Lat. *taurus* |
| entrada | entry, entrance | noun | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *intrata*; book notes English "entry" underwent the same au/other-vowel shift via French, making this a rare case where the Spanish and English cognate forms both shifted identically |

---

## Part III.4 — Consonant changes: Latin stop consonants p/b, t/d, c/g, and double consonants

**The rule:** In the shift from Latin to the Romance languages, interior stop consonants (p, b, t,
d, c, g) either survived, voiced, or disappeared, with each Romance language following a different
pattern. Spanish: b→[v] (spelling kept as b); the other five (p, t, c, d, g) either changed (p, t,
c) or frequently vanished entirely (d, g). French: p and b both became v; the other four vanished.
Separately, Latin's distinction between single and double consonants (preserved in Italian, e.g.
*papa* "Pope" vs. *pappa* "baby food") was eliminated in native Spanish words for seven of the nine
double-consonant types — Spanish b, d, f, g, p, s, t are never doubled in native words; only cc
(before e/i, in three specific word-groups), ll, mm, nn, and rr survived doubling (rr becoming the
distinct trilled-r phoneme).

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| saber | to know | verb | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *sapere*; shows p surviving as b; cf. Fr. *savoir*, It. *sapere* (keeps p) |
| moneda | coin, money | noun | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *moneta*; shows t surviving as d; cf. Fr. *monnaie* (t vanished) |
| seguro | sure, secure, safe | adjective | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *securus*; shows c surviving as g; cf. Fr. *sûr* (c vanished) |
| probar | to prove, to try/taste | verb | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *probare*; b became [v] in pronunciation, spelling kept as b |
| cruel | cruel | adjective | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *crudelis*; shows d vanishing entirely (same outcome as French *cruel*) |
| liar | to tie, to bind | verb | core | medium | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *ligare*; shows g vanishing entirely (cf. Eng. "ligament," which kept the learned Latin g) |
| abreviar | to abbreviate | verb | formal | medium | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *abbreviare*; double bb simplified to single b, as happens to all native Spanish double consonants except cc/ll/mm/nn/rr |
| acusar | to accuse | verb | formal | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *accusare*; cc before a/o/u/consonant simplifies to c (contrast acceso below) |
| acceso / accesible | access / accessible | noun/adjective | formal | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *accessus*; one of only three word-groups where cc before e/i is kept double in Spanish |
| año | year | noun | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *annus*; double nn survives as the ñ sound/letter — the Spanish ñ itself is historically a written "nn" ligature |
| letra | letter | noun | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *littera*; double tt simplified to single t |
| irritar | to irritate | verb | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *irritare*; double rr survives as the trilled-r phoneme, distinct from single r |
| masa | mass, dough | noun | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *massa*; double ss simplified to single s |
| valle | valley | noun | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *vallis*; double ll survives as a distinct Spanish phoneme/letter |

---

## Part III.5 — Other distinctive consonant changes: pl/fl/cl → ll, ct → ch, and related shifts

**The rule:** A further set of less-common but highly recognizable consonant changes further
obscures some Spanish/English cognate pairs from each other — e.g. the same Latin root can surface
in Spanish as both an easily-recognizable "learned" form and a heavily-altered "popular" form
(*reverso*/*revés*, both < Lat. *reversus*; *parábola*/*palabra*, both < Gk./Lat. *parabola*).

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| llamar | to call; ¿Cómo te llamas? (what's your name?) | verb | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Change: Lat. cl→ll; < Lat. *clamare* (cf. Eng. "claim," "clamor"); cf. Port. *chamar*, It. *chiamare* (different outcomes of the same Latin cluster) |
| llave | key | noun | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Change: Lat. cl→ll; < Lat. *clavis*; learned doublet *clave* ("key" in the figurative/password sense) keeps the cl- |
| llama | flame | noun | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Change: Lat. fl→ll; < Lat. *flamma*; learned doublet *flama*/*inflamar* keeps fl- |
| llaga | sore, ulcer | noun | core | medium | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Change: Lat. pl→ll; < Lat. *plaga*; learned doublet *plaga* ("plague," reborrowed later) keeps pl- |
| llegar | to arrive | verb | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Change: Lat. pl→ll; < Lat. *plicare* (cf. Eng. "ply," "implicate"); cf. Port. *chegar*, It. *piegare* |
| palabra | word | noun | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Change: r...d → ...l (metathesis+lenition); < Lat./Gk. *parabola*, learned doublet *parábola* ("parable, parabola") shows the same root barely altered |
| revés | reverse (adj./n.), setback | noun/adjective | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Change: rs→s; < Lat. *reversus*; learned doublet *reverso* keeps the cluster |
| varón | man, male | noun | core | medium | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Change: b→v (written); < Lat./Germanic *baro*; cf. Eng. "baron" |
| trecho (trajectory sense) / trecho | stretch, distance | noun | core | medium | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Change: ct→ch; < Lat. *tractus* (cf. Eng. "tract") — same ct→ch pattern already seen in Part III.2's hecho/dicho/pecho/estrecho/techo family |

---

## Part IV.1 — Goths and other Germans (5th-8th c. Germanic contact layer)

**Historical context:** Germanic tribes (Vandals, then Visigoths) controlled Iberia for roughly
three centuries (5th-8th c.) before the Arab conquest. The Visigoths were already largely
Latinized by the time they crossed into Spain, so they left proper names (Alfonso, Álvaro, Elvira,
Fernando, Gonzalo, Rodrigo) more than everyday vocabulary. Two systematic patterns mark the
Germanic-origin word layer: (1) the Germanic *h-* sound was usually dropped from Spanish spelling
(the reverse of the Latin *f-*→*h-* pattern in Part III.2, and the reverse of Latin *h-* words,
which had their *h-* spelling restored though not pronounced); (2) Germanic *w-* generally surfaces
in Spanish as *gu-*, since Classical Latin's own [w] sound had vanished by the time these words were
borrowed, leaving *gu-* ([gw]) as the closest available sound — the same mechanism produced the
English doublets guard/ward, guardian/warden, guarantee/warranty (Normal French kept [w], "central"
French/Spanish used [gw]).

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| vándalo / vandalismo | Vandal / vandalism | noun | core | medium | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | The Vandals' brief 5th-c. passage through Spain en route to Africa is credited as the origin of the place name "Andalucía" (< "Portus [V]andalus") |
| godo / gótico | Goth / Gothic | noun/adjective | formal | medium | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Visigoths ruled most of Spain from Toledo, 5th-8th c., until the 711 Arab invasion |
| bregar | to toil, to struggle | verb | colloquial | medium | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Believed Visigothic-origin word (cf. Eng. "break") |
| brotar / brote | to sprout, to break out (fire, disease) / outbreak, bud | verb/noun | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Believed Visigothic-origin |
| espía / espiar | spy / to spy | noun/verb | formal | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Believed Visigothic-origin; espionaje = espionage |
| gaita | bagpipes | noun | core | medium | contemporary (source published 2007) | Spain (esp. Galicia/Asturias) | Spain | grammar_reference | verified | n/a | Believed Visigothic-origin (cf. Eng. "goat" — bagpipes traditionally made from goatskin) |
| ganso | goose | noun | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Believed Visigothic-origin |
| tregua | truce | noun | formal | medium | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Believed Visigothic-origin; sin tregua = without a break, nonstop |
| albergar | to harbor, to lodge | verb | core | medium | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | General Germanic-origin word; h-dropping pattern |
| arpa / arpón | harp / harpoon | noun | core | medium | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | General Germanic-origin; h-dropping pattern |
| yelmo | helmet | noun | formal | low | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | General Germanic-origin; h-dropping pattern, plus a ye-/ie- diphthong spelling rule at word-initial position |
| guardar / guardia | to guard, to keep / guard, watch | verb/noun | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Germanic w-→gu- pattern; la Guardia Civil = Spain's rural police force; family: vanguardia (vanguard), retaguardia (rear guard), guardaespaldas (bodyguard) |
| guerra / guerrero / guerrilla | war / warlike, warrior / guerrilla warfare | noun/adjective | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Germanic w-→gu- pattern; guerrilla itself was reborrowed into English as "guerrilla" |
| guiar / guía | to guide / guide, guidebook | verb/noun | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Germanic w-→gu- pattern |
| guiño / guiñar | wink / to wink | noun/verb | colloquial | medium | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Germanic w-→gu- pattern; guiñol = puppet show (< Fr. Grand Guignol) |
| guisa | manner, mode | noun | formal | low | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Germanic w-→gu- pattern (cf. Eng. "guise," "-wise" as in "likewise" — English got this word-family twice, once via Norman French with [w] intact, once via central French/Latin with [gw]→[g]) |

---

## Part IV.2 — Arabs and Muslims (8th-15th c. Andalusi Arabic contact layer)

**Historical context:** Arab forces crossed into Iberia in 711 and controlled most of the
peninsula within a decade; the centuries-long Reconquista wasn't complete until 1492 (fall of
Granada), meaning some regions were under Muslim rule for longer than they had been under Roman
rule. The resulting Arabic influence on Spanish vocabulary is far greater than on any other Romance
language. The single most distinctive pattern: Spanish frequently absorbed the Arabic definite
article *al-* as a fused part of the borrowed noun itself (so *el atún* literally doubles up as
"the the-tuna") — a phenomenon only occasional in French/Italian borrowings from Arabic, producing
systematic contrasts like Sp. *algodón* vs. Fr. *coton*/It. *cotone* ("cotton") or Sp. *azúcar* vs.
Fr. *sucre*/It. *zucchero* ("sugar," itself from Arabic but without the fused article).

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| algodón | cotton | noun | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Fused Arabic article al- + root; cf. Fr. *coton*, It. *cotone* (no fused article) |
| alminar | minaret | noun | formal | low | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Fused Arabic article al- + root |
| alquitrán | tar (road surface) | noun | technical | medium | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Fused Arabic article al- + root |
| azafrán | saffron | noun | core | medium | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Fused Arabic article a(l)- + root (l dropped before "solar" consonants in Arabic phonology) |
| azúcar | sugar | noun | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Fused Arabic article a(l)- + root |
| arroz | rice | noun | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Ultimately from a Greek word (itself from India/Persia) that reached Spanish via Arabic, rather than directly via Latin — a three-hop borrowing chain |
| atún | tuna | noun | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Same Greek→Arabic→Spanish chain as *arroz*; French/Italian got the word straight from Greek/Latin without the Arabic detour |
| aceite / aceituna | oil, olive oil / olive | noun | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Replaced the expected Latin-derived form (which would have become *ojo*, already taken by "eye" < Lat. *oculus*) — a borrowing motivated by avoiding a homophone collision; learned doublet *olivo* (olive tree) and *óleo* (oil paint/religious oil) preserve the Latin root directly |
| albaricoque | apricot | noun | core | medium | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | "Globe-trotting apricot": Lat. *persicum praecoquum* ("precocious/precooked peach") → Greek *praikokion* → Arabic *al-barquq* → Spanish *albaricoque* → French *abricot* → English "apricot" — a five-hop chain through four languages, a genuinely striking etymological story for a loanword-chain finding |
| acequia | irrigation ditch/canal | noun | regional | medium | contemporary (source published 2007) | southwestern United States (via early Spanish missions) | regional | grammar_reference | verified | n/a | The term for the still-functioning irrigation system introduced into the southwestern US by Spanish missions — a documented transnational transplant of the word along with the technology |
| alcalde / alcaldía | mayor / mayoralty, city hall | noun | formal | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Fused Arabic article al- + root |
| alcantarilla / alcantarillado | sewer / sewage system | noun | technical | medium | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Fused Arabic article al- + root |
| ahorrar / ahorro | to save (money) / savings | verb/noun | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Arabic-origin, no fused article in this case |
| albañil | mason | noun | technical | medium | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Fused Arabic article al- + root |
| ademán | gesture, attitude | noun | core | medium | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Arabic-origin |
| adobe | adobe | noun | technical | medium | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Arabic-origin; reborrowed into English unchanged as a building-material term |
| alcatraz | pelican, gannet | noun | core | low | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Fused Arabic article al- + root; cognate obscured in English (cf. "albatross," and the island/prison name Alcatraz) |

---

## Annex C — Verbs ending in -cer: the Latin inceptive (*-scere*) verb family

**The rule:** A large class of Spanish *-cer* verbs descends from Latin "inceptive" verbs, formed
by adding *-scere* to a base verb to mean "to begin to [verb]" (e.g. *florere* "to bloom" →
*florescere* "to begin to bloom"). Over time the inceptive sense weakened to just "the process
itself," and new inceptive verbs were coined from nouns and adjectives (*noble* → *ennoblecer*).
The same inceptive-verb explosion, via Old French, is the direct source of the English *-ish* verb
suffix (abolish, cherish, establish, finish, flourish [< *florescere*], nourish, perish, polish,
vanish, etc.) — a genuinely useful "mechanism echo" for a conlang pipeline, since it shows the same
derivational morpheme surfacing as a verb-class marker in two daughter traditions (Spanish *-cer*,
English *-ish*) from one Latin source.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| abastecer | to supply, to provide | verb | formal | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Family: bastante (enough), bastar (to suffice) |
| aborrecer | to abhor | verb | formal | medium | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Family: aburrir (to bore); note *es aburrido* ("he is boring," ser) vs. *está aburrido* ("he is bored," estar) — a ser/estar minimal pair riding on this same root |
| acontecer / acontecimiento | to happen, to occur / event, happening | verb/noun | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Cognate obscured in English (cf. "contact," "contingency") |
| adolecer | to suffer from, to be afflicted with | verb | formal | medium | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Family: dolor (pain), doler (to hurt), duelo (grief/mourning — note unrelated homonym duelo "duel") |
| adormecer | to make sleepy, to lull | verb | core | medium | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Family: dormir (to sleep), dormilón (sleepyhead), dormitorio (bedroom) |
| agradecer | to be grateful for | verb | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Family: agradecimiento (gratitude), agradable (pleasant), desagradecido (ungrateful), grato/ingrato, persona non grata — all from Lat. *gratus* ("pleasing") |
| amanecer | to dawn | verb | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Family: amanecer (n., dawn), mañana (tomorrow/morning) |
| ennoblecer | to ennoble | verb | formal | low | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | Cited by the book as an example of the inceptive pattern extended to adjectives (noble → ennoblecer) rather than inherited directly from a Latin inceptive verb |
| florecer | to bloom, to flourish | verb | core | high | contemporary (source published 2007) | — | — | grammar_reference | verified | n/a | < Lat. *florescere*, the book's opening example of the inceptive pattern; direct morphological cognate of English "flourish" (via Old French) |

---

## Copyright discipline reminder

This file samples selected cognate-pair examples and historical/etymological commentary from a
single copyrighted reference work, following this project's established non-redundant-supplement
and representative-sampling conventions for large-scale sources. Given the book's extreme density
(hundreds of word pairs per chapter), only a representative subset illustrating each documented
sound-change rule or contact-layer pattern is reproduced, not the book's full word lists. No
exercise content or substantial prose passages beyond brief rule-statements are reproduced.
