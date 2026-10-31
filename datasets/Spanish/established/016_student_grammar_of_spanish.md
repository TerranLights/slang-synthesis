# Spanish — Established Vocabulary/Grammar: A Student Grammar of Spanish (non-redundant supplement)

**Source:** Ronald E. Batchelor, *A Student Grammar of Spanish*, Cambridge University Press, 2006.
354 PDF pages, real text layer confirmed (no vision-reading needed). PDF-page-to-printed-page
offset verified empirically at three separate points (Unit 1 start, Unit 2 start, Unit 30 start):
**PDF page = printed page + 24** (not +20 as initially estimated from front-matter arithmetic).
`pdftotext -layout` was run across the whole book once to a scratch working file and grepped for
page-tagged tag occurrences; chapter-level close reads then done via `pdftotext -layout -f N -l M`
on the ranges below.

**Note on the dialectal tag itself:** the table of contents uses bracket notation `[M]` (e.g.
"antecopretérito [M]"), but the actual **body text of the book overwhelmingly uses parenthetical
`(M)`** — 404 raw occurrences of `(M)` vs only 16 of `[M]` (and the 16 `[M]` hits are almost all
inside TOC chapter-title lines or two body instances that happen to use the bracket style
inconsistently). **The real "highest-value dialectal annotation" to hunt for in this book is `(M)`,
not `[M]`.** This is flagged explicitly since a future re-check searching only for the bracket style
could otherwise undercount by a factor of ~25.

## Coverage note — non-redundant-supplement scope decision

This is the 8th Spanish reference book extracted into `established/`. Per the project's
non-redundant-supplement rule, this extraction did **not** re-extract:
- Basic verb-tense paradigms (present, preterit, imperfect, future, conditional, perfect, imperative,
  progressive) — fully covered by 007/008/008b/008c/014.
- Basic ser/estar, basic articles/gender, basic possessives/comparatives — covered by 005/006.
- Subjunctive mood mechanics (present, past, clause triggers) — covered by 014/015.
- Object pronouns, leísmo, reflexive-verb meaning classes, gustar-type verbs — covered by
  006/014/015.
- Full irregular-verb morphology tables — covered by 007.
- Basic alphabet/pronunciation/stress/diphthong rules — covered by 009/009b-d (though Unit 1 was
  skimmed for `(M)`-tagged letter-naming conventions, see Vocabulary table).
- The vosotros/Uds. address-system contrast itself (the book repeatedly drills vosotros-form vs.
  ustedes-form conjugation pairs tagged `(M)`) — this specific *system* (Spain vosotros vs.
  Spanish-America ustedes) is already well documented in 015 (Schaum's). Not every repeated
  verb-conjugation instance of this pattern (there are dozens) was added as its own vocabulary row;
  only the pattern itself is noted once as a grammar point.
- **Skipped entirely:** the "Model Answers / Soluciones y modelos" section — confirmed empirically to
  begin at **PDF page 309** (printed page ~285), running to near the end of the book. This boundary
  was verified directly rather than trusting TOC-order arithmetic (the TOC lists "Subjunctive index"
  before "Model answers," but in actual page order Model Answers begins immediately after Unit 30
  ends at PDF page 308). Several dozen `(M)`-tagged lines an initial whole-book grep caught (PDF
  pages 309–336) were excluded from the vocabulary table below for this reason — they are answer-key
  restatements of exercises already seen in the units themselves, not new content. Also skipped: the
  "Glossary of grammatical terms" (metalinguistic definitions, pp. xi-xix front matter) and the two
  back-of-book indexes.

**What was kept and why** (genuinely new or deeper than the 7 prior books):
1. **Every `(M)` Spain-vs-Mexico dialectal/lexical annotation found in actual chapter content** (PDF
   pages 25–308) — this book's single biggest unique contribution. ~70 distinct lexical/idiomatic
   items, deduplicated from ~350 raw occurrences (most repeats are the same word reused across
   different drill exercises).
2. **Unit 30, Augmentatives and diminutives** — not covered by any prior book; directly relevant to
   slang morphology (-ito/-ecito, -illo/-ecillo, -uelo, -ón, -azo, -ote, -ucho productive suffix
   system).
3. **Unit 22, Personal/distinctive "a"** — goes well beyond the basic rule already captured from 008
   Ch.5: personification, omission-to-avoid-ambiguity, the subject/object-both-inanimate
   disambiguation rule, nadie/alguien/quien, and disjunctive-pronoun confusion are all new nuance.
4. **Unit 29, Word order** — systematic verb-subject inversion conditions, bien/mal placement,
   adjective-position meaning shift (with the "contrastive stress" explanation), otros/as+number,
   date-order — fuller and more systematic than 014/006's treatment.
5. **Unit 21 Level 2 (Adjectives)** — invariable color/descriptive adjectives, lo+adjective,
   el+adjective constructions — not seen in prior books.
6. **A handful of grammar-adjacent sociolinguistic notes** the book makes explicitly: the "coger
   (not in M)" taboo-avoidance note, the Spain/Mexico time-telling system difference, the
   "jugar + sport" without "al" construction difference, and a genuine gender-variation case (el
   radio (M, masc.) vs la radio (Spain, fem.)).

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| carro (M) | car | noun | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Spain equivalent: coche. Extremely frequent (M) tag throughout the book (p.24 and dozens more). |
| recámara (M) | bedroom | noun | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Spain: habitación / dormitorio (p.6, 98, 143, 198) |
| foco (M) | light bulb | noun | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Spain: bombilla (p.14, 119) |
| hora pico (M) | rush/commute hour | noun phrase | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Spain: hora punta (p.23, 249) |
| bolsa (M) | handbag/purse | noun | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Book contrasts with "bolso" implied as the other usage (p.24) |
| plata (M) | money (colloquial sense) | noun | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Also means "silver" generally; (M)-tagged specifically for the colloquial "money" sense (p.25) |
| chamaca / chamaco (M) | girl / boy, kid | noun | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Spain: chica/chico. Recurs very frequently (p.29, 309, and many drill exercises) |
| doctor (M) | doctor (used as the default noun/address form) | noun | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Spain: médico preferred as the plain noun; both exist in Mexico but "doctor" is the (M)-tagged default (p.29, 285) |
| papá / papás (M) | dad / parents (colloquial register) | noun | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Spain: padre/padres. Extremely frequent throughout (p.31, 32, 68, 71...) |
| piyama (M) | pajamas | noun | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Spelling variant of Spain's "pijama" (p.35) |
| rentar (M) | to rent | verb | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Spain: alquilar (p.39 and many) |
| timbre (M) | postage stamp | noun | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Spain: sello. Note: timbre also means "doorbell" in general Spanish — (M) sense is specifically "stamp" (p.39, 175) |
| platicar (M) | to talk / chat | verb | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Spain: hablar. One of the most recurrent (M) items in the book (p.39 and dozens more) |
| manejar (M) | to drive | verb | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Spain: conducir (p.39 and dozens more) |
| alberca (M) | swimming pool | noun | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Spain: piscina (p.40 and dozens more) |
| boleto (M) | ticket | noun | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Spain: billete / entrada (p.42, 131, 155) |
| plomero (M) | plumber | noun | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Spain: fontanero (p.42, 72, 141) |
| descomponerse (M) | to break down (of a machine/vehicle) | verb | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Spain: estropearse / averiarse (p.50, 72, 291) |
| cuate (M) | buddy, pal, close friend | noun | slang | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Spain: amigo. High-value slang/colloquial item, recurs constantly from p.50 onward |
| camión (M) | bus | noun | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Spain: autobús. Note the semantic shift — "camión" means "truck" in Spain (p.50 and dozens more) |
| departamento (M) | apartment | noun | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Spain: piso / apartamento (p.54, 185, 273) |
| hallar (M) | to find | verb | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Used preferentially over "encontrar" in M; Spain prefers encontrar (p.59, 72, 141) |
| pluma (M) | pen | noun | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Spain: bolígrafo (p.64, 167) |
| pandillero (M) | gang member, delinquent | noun | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Spain: gamberro (p.71, 78) |
| rasurar(se) (M) | to shave (someone/oneself) | verb | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Spain: afeitar(se) (p.74, 107) |
| el radio (M, masc.) | radio (the set) | noun | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | GENDER VARIATION: masculine in Mexico vs. feminine "la radio" in Spain (p.75, 215) |
| agujetas (M) | shoelaces | noun | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Spain: cordones (p.82) |
| garage (M) | garage | noun | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Spelling variant of Spain's "garaje" (p.119, 145) |
| regadera (M) / regaderazo (M) | shower (noun) / to take a (quick) shower | noun / verb-phrase | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Spain: ducha / darse una ducha (p.119, 298) |
| computadora (M) | computer | noun | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Spain: ordenador (p.122 and several more) |
| pueblito (M) | small village (diminutive) | noun | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Book notes Mexican speakers prefer -ito over -ecito (pueblecito is the Spain-leaning alternative) (p.126, 276) |
| estacionamiento (M) | parking lot | noun | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Spain: aparcamiento (p.131) |
| pachanga (M) | party (colloquial) | noun | slang | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Spain: fiesta. Explicitly colloquial register (p.131) |
| ahorita (M) | right now / immediately | adverb | regional | — | contemporary (source published 2006) | Mexico / Central America | transnational | grammar_reference | n/a | n/a | Book: "pervasive use in Mexico and all Central America of ahorita... the present author has never heard the Peninsular ahora in Mexico" (p.134, 278) |
| abusado (M) | clever, smart, sharp | adjective | slang | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Spain: listo. Colloquial register (p.182, 195, 260) |
| jitomate (M) | tomato | noun | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Spain: tomate (p.103) |
| papa (M) | potato | noun | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Spain: patata (p.98, 181, 194) |
| sarape (M) | traditional Mexican blanket/shawl | noun | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Cultural item with no direct Spain equivalent given by the book (p.191, 198) |
| tope (M) | speed bump / traffic retarder | noun | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Mexican-specific term; no Spain equivalent given. Example: "El tope obliga a la gente a manejar lento" (p.192) |
| desarmador (M) | screwdriver | noun | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Spain: destornillador (p.206) |
| mesero (M) | waiter | noun | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Spain: camarero (p.207, 230) |
| azucarera (M, fem.) | sugar bowl | noun | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | GENDER VARIATION: feminine "azucarera" in Mexico vs. masculine "azucarero" in Spain (p.208) |
| cobijas (M) | blankets | noun | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Spain: mantas (p.194) |
| lentes (M) | eyeglasses | noun | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Spain: gafas (p.183, 227) |
| agarrar (M) | to catch / grab | verb | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | HIGH-VALUE sociolinguistic note: the book explicitly glosses the alternative "coger" as "(not in M)" in this sense — "coger" carries a taboo/vulgar sexual connotation in Mexican Spanish and is avoided for the plain sense "to catch/grab" there. Example: "El gato agarra (M) / coge (not in M) un ratón" (p.197) |
| rebasar (M) | to overtake (on the road) | verb | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Spain: pasar / adelantar (p.202) |
| pizarrón (M) | blackboard | noun | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Spain: pizarra. Recurs often in classroom-activity instructions (p.202, 265, 270) |
| jovencito (M) | young lad / young guy | noun | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Paired in the text with Spain's "chaval" (p.243) |
| cuarto para las X (M) / veinte para las X (M) | quarter to X / twenty to X (time-telling) | idiom (time) | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Systematic time-telling difference: Mexico counts forward "para" (to/until) the upcoming hour; Spain uses "[hour] menos cuarto/veinte." The book has an explicit NB: "Note the difference between M and Spain with respect to times to the hour." (p.248-249) |
| carrazo (M) | big car (augmentative) | noun | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | -azo augmentative suffix; Unit 30. General Spain equivalent given in the same list is "cochazo" (p.280) |
| golpazo (M) | big blow, thump (augmentative) | noun | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | -azo augmentative suffix; Unit 30, paired with general "codazo" (elbow blow) (p.280) |
| jugo (M) | juice | noun | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Spain: zumo (p.291) |
| luego luego (M) | right away, immediately (reduplicated idiom) | adverbial idiom | slang | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Reduplication idiom contrasted with "últimamente" (lately) in a vocabulary list (p.232) |
| ordenar (M) | to order (food, at a restaurant) | verb | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Spain: pedir (p.300) |
| auto (M) | car (alternate to carro) | noun | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Used interchangeably with carro in some examples (p.161, 185) |
| chamarra (M) | jacket | noun | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Spain: chaqueta (p.160, 169, 171) |
| visor (M) | swim goggles | noun | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Paired with Spain's "gafas (de nadar)" in a negative-sentence drill (p.243) |
| domingo (M) | pocket money, allowance | noun | slang | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Idiomatic extension from "Sunday" — the book glosses it inline: "¿Te dio tu domingo (M = pocket money) tu padre?" (p.195) |
| endomingarse (M) | to dress up (in one's Sunday best) | verb | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Transparent etymology from "domingo" (Sunday); appears in a "getting ready" narrative exercise alongside "pulir" (p.116) |
| zacate (M) | loofah / scouring sponge | noun | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Etymology note of interest for mechanics analysis: ultimately from Nahuatl "zacatl." Appears paired with "tallar" (to scrub) (p.116) |
| rulos (M) / tubos (M) | hair curlers | noun | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Both forms tagged (M) in the same passage, contrasted implicitly with a general "rulos" elsewhere (p.116) |
| chofer (M, stress on final syllable) | driver, chauffeur | noun | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Stress/orthography variant vs. Spain's "chófer" (stress on first syllable) (p.77) |
| híjole (M) | wow!, jeez!, heavens! (exclamation of surprise/dismay) | interjection | slang | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Spain-only equivalents given: ¡Jolín!/¡Jolines! Recurs at p.5, 228, 236 |
| chava (M) | girl (colloquial) | noun | slang | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | p.3, 5 |
| chévere (M) | cool, great (colloquial) | adjective | slang | — | contemporary (source published 2006) | Mexico (per book's own attribution) | national | grammar_reference | n/a | n/a | Book attributes this to Mexican colloquial usage; flagging a discrepancy rather than silently following this book's claim: other sources commonly treat "chévere" as more strongly associated with Caribbean/Venezuelan/Colombian Spanish (p.3) |
| durazno (M) | peach | noun | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Appears in the book's seseo pronunciation example ("durazno = durasno"); Spain: melocotón (not given directly in this passage but durazno itself is the lexical item) (p.3) |
| b grande (M) / b chica (M) | names for the letters "b" and "v" in recitation | metalinguistic term | regional | — | contemporary (source published 2006) | Mexico | national | grammar_reference | n/a | n/a | Mexican convention for distinguishing b/v when spelling aloud, contrasted with Spain's "b alta/baja" naming style (Unit 1) |
| estadounidense (M) / estadunidense | American (of the US) | adjective/noun | core | — | contemporary (source published 2006) | — | — | grammar_reference | n/a | n/a | Spelling variant (M) drops the "o" — minor orthographic note, not dialectal-lexical in the same sense as the rest of this table (p.16) |

## Grammar points

### Unit 22 — Personal/distinctive "a" (printed pp.198-204)

Deeper than 008 Ch.5's basic treatment. The book frames the whole topic as Spanish's only device for
marking a noun as direct object when word order alone (as in Latin, and much more than in
English/French) can't do it, since the same preposition "a" also marks indirect objects — a source
of real ambiguity for native speakers themselves, not just learners.

- **Core rule:** personal "a" before direct objects that are determinate/known persons (Veo a
  Pedro), collective-noun referents (Llaman a la policía), and "public figures" treated as persons
  (Leo a Cervantes).
- **Animals:** required when the animal is "regarded as intelligent or rational," especially a
  family pet (Llaman al perrito) — but explicitly *not* used for an "insignificant animal" or
  inanimate object (El gato agarra (M) un ratón — see the agarrar/coger vocabulary note above for
  the taboo-avoidance angle on this exact example sentence).
- **Personification:** frequently (not always) used with personified nouns, especially patria,
  nación, pueblo — "Estos soldados honran a la patria." NB from the book: countries/towns used to be
  included in this category but no longer are.
- **Omission to avoid ambiguity/clash:** dropped when it would collide with a genuinely prepositional
  "a" already in the sentence (El general convocó los oficiales a una conferencia), and dropped from
  the direct object specifically when a sentence also has an indirect object, so the two don't both
  compete for "a" (Recomendó al gobernador su hijo, Don José). "a" is ALWAYS used before
  direct-object nadie/alguien/quien, even though these suggest an unknown/uncertain referent (¿Vas a
  invitar a alguien?) — an apparent exception to the "known person" rule that the book flags
  explicitly.
- **Thing-vs-thing disambiguation:** when both subject and object are inanimate, "a" is added to the
  object to resolve otherwise-genuine ambiguity about which is doer/done-to — worked with 4 paired
  sentences reversing subject/object roles around "seguir" (follow) and "alcanzar" (overtake/catch
  up to): e.g. "El silencio sigue al ruido" vs "Al ruido sigue el silencio" both mean "Silence
  follows the noise," only distinguishable by which noun carries "a."
- **Verbs of naming/calling/considering with two objects** (llamar, considerar): the "true object or
  thing asserted" gets the personal "a" to distinguish it from the other object — "¿Llaman música a
  este jaleo?" (Do they call this ruckus music?).
- **Disjunctive pronoun confusion:** fronted disjunctive pronouns for stress (A él le interesa el
  libro) create the same direct/indirect-object ambiguity problem all over again at the pronoun
  level; the reflexive "se" can be used specifically to dispel it (Se le vio al hombre en el espejo =
  "The man was seen in the mirror," disambiguated from "the man saw himself").

### Unit 21 Level 2 — Adjectives beyond basic agreement/placement (printed pp.193-197)

- **Invariable adjectives:** a small closed set that doesn't inflect for gender/number because
  they're really nouns/other parts of speech functioning adjectivally — escarlata, hembra, macho,
  malva, modelo, naranja, rosa, tabú, violeta (e.g. "los elefantes hembra," not "hembras").
- **Adjectives used adverbially:** common in speech — hablar alto/bajo/claro/fuerte, trabajar duro,
  and notably rápido/lento as adverbs (Habla rápido instead of the "correct" hablar rápidamente) —
  book flags this as a colloquial practice not to imitate in early learning, with the (M)-tagged
  "manejar lento" example (tope sentence above) as its illustration.
- **Two adjectives together become invariable**, especially colors in compound form: "una falda azul
  pálido" (not "azul pálida").
- **Position-dependent meaning shift:** a short closed list of adjectives (antiguo, cierto,
  diferente, distinto, grande, medio, nuevo, pobre, único, ligero) carry a different sense before vs.
  after the noun, generally with the post-nominal position carrying more weight/emphasis — e.g. "un
  gran escritor" (a great writer) vs "una casa grande" (a big house). Cross-referenced by the book
  itself to Unit 29 (word order) for the fuller theoretical treatment.
- **Lo + adjective** ("what is X," "the X thing") has no direct English equivalent and must be
  paraphrased: "Lo importante es que venga hoy" (The important point is that he come today). The
  book notes one culturally interesting example: "Lo curioso es que los mexicanos no usan esta
  palabra" (The funny thing is that Mexicans don't use this word) — self-aware Spain/Mexico framing
  even outside the explicit (M)-tag system.
- **El + adjective** (= "the [size] one"): "Prefiero el chico (M) / pequeño" — note the dialectal pair
  embedded directly in this construction's own example.

### Unit 29 — Word order (printed pp.269-273)

Deeper/more systematic than existing coverage. Core claims, each illustrated by the book with
minimal-pair examples:

- **Subject-verb inversion for emphasis:** "El amigo se va" vs "Se va el amigo" — both grammatical,
  differ only in which element gets initial-position emphasis.
- **Verb precedes subject when:** (a) the subject phrase is markedly longer than the verb (balance);
  (b) the verb is one of a small set that doesn't take a direct object — doler, faltar, gustar,
  quedar, sobrar (Me duele la cabeza; Faltan dos tenedores); (c) a plural subject appears without an
  article, especially with reflexive/intransitive verbs (En el mercado se venden peras).
- **Bien/mal placement:** immediately follows the verb UNLESS modified by another adverb, in which
  case it moves after the object for balance — "Habla bien el chino" vs "Habla el chino
  estupendamente bien."
- **Adjective position and contrastive stress:** a post-nominal adjective carries a "distinctive"
  nuance signaled by rising terminal intonation (Es una casa pequeña, with pequeña stressed) — the
  book gives a genuinely nuanced worked example: "Las hojas secas caen" (some leaves, the dry ones,
  fall) vs "Las secas hojas caen" (all the leaves, which are dry, fall) — a real meaning difference
  from word order alone, not just a stylistic one.
- **Adjective-length-sensitive flexibility:** "largo" normally precedes its noun and sounds odd after
  it (un largo paseo), but adding an intensifier (muy) frees it to go either side.
- **Always-postnominal adjectives:** nationality, political/religious affiliation, and basic colors
  almost never precede the noun — "un carro (M) / coche francés," "el partido socialista," "una casa
  amarilla."
- **otros/as precedes the number it quantifies:** "otros cuatro hombres" (another four men), not
  "cuatro otros."
- **primero/último flexibility with numerals:** "los dos primeros años" and "los primeros dos años"
  are both acceptable.
- **Date order:** definite article + day-name + numeral + de + month — "Hoy es el sábado 5 de enero."

### Unit 30 — Augmentatives and diminutives (printed pp.278-284)

Genuinely new territory for this project's Spanish corpus — no prior established file covers this
chapter. High relevance to slang morphology since these suffixes are extremely productive and carry
register/attitude information beyond literal size.

- **-ito/a, -ecito/a** — the two dominant diminutive suffixes, "especially in Spanish America, and
  therefore Mexico." Not necessarily about literal smallness — frequently just affectionate tone.
  Book states Mexican speakers lean toward -ito/a over -ecito/a (carrito over cochecito, pueblito
  over pueblecito, cuentito over cuentecito — all three also carry the explicit (M) tag, already in
  the vocabulary table above). Also used for genuine affection especially in child-directed speech
  (Dale un besito a Papá), and can intensify rather than diminish (un café calentito = "nice and hot
  coffee," not "a small hot coffee"). Extends even to adjectives/past-participles/adverbs used
  adjectivally (dormidito = "sound asleep," hablar bajito = "speak really quietly" — the latter also
  carries the platicar (M) tag).
- **Register note the book makes explicitly:** heavy use of -ito/a is perceived by some Spaniards as
  "too sentimental," while Mexicans may perceive Peninsular Spanish as "aggressive or harsh-sounding"
  by comparison — framed by the author as a genuine two-way mutual-perception difference in register
  norms, not just a one-directional judgment.
- **-illo/a, -ecillo/a** — diminutive, and "almost exclusively pejorative" in Spanish America, though
  not always pejorative in Spain (cursillo = "short course," no negative connotation; hombrecillo =
  "insignificant little man," pejorative). An alternative to -ito/a for some nouns (cucharita/
  cucharilla) with genuine regional variation in which is "correct."
- **-uelo/a, -(e)juelo/a, -chuelo/a, -ete, -ecete, -oleto** — diminutive, context-dependently
  pejorative or neutral (riachuelo = "brook," not pejorative; regordete = "chubby," neutral/fond).
- **-ón/a (augmentative)** — most often picks up a pejorative overtone since "largeness or excess is
  often thought to be bad": cabrón/ona, solterón/ona (confirmed bachelor/spinster), dulzón
  (sickly-sweet). Can also derive pejorative adjectives from nouns (cabezón = stubborn) and pejorative
  nouns/adjectives from verbs (llorón = cry-baby, empollón = swot/grind — book notes empollón is "not
  in M").
- **-azo (augmentative)** — similar to -ón but less common; two distinct senses: (1) plain
  augmentative (bigotazo = big mustache, cochazo/carrazo (M) = big car, exitazo = big hit); (2) "a
  blow with X" (codazo = elbow blow, mazazo = cudgel blow, golpazo (M) = big blow/thump, puñetazo =
  punch).
- **-ote/a (augmentative + pejorative)** — librote (dull book), palabrota (swearword), cabezota
  (stubborn), brutote (clumsy/dumb) — but the book flags one exception: amigote = "buddy/mate," is
  familiar/affectionate rather than pejorative despite the same suffix.
- **-ucho/a, -acho/a, -uco/a, -aco (clearly pejorative)** — casucha (hovel), cuartucho (squalid room),
  populacho (rabble), ricacho (filthy rich), frailuco (stupid little monk); the chapter continues past
  this point with further examples (mujeruca, pajarraco, picacho) not transcribed in full here per
  copyright discipline (one of the longer closed-list sections of the chapter).

### Minor grammar notes (scattered, (M)-adjacent)

- **"Jugar + sport" without "al":** the book marks the Mexican construction "Juego fútbol (M)" /
  "jugué béisbol (M)" as dropping the "al" that Spain usage requires ("jugar al fútbol"). Appears at
  least twice (fútbol, béisbol, golf) so treated as a real construction-level pattern, not a one-off
  lexical note.
- **Spain/Mexico time-telling systems (Unit 27, printed pp.246-249):** systematic, not just a couple
  of lexical substitutions — Mexico counts forward to the next hour using "para" ("veinte para las
  diez" = twenty to ten), where Spain subtracts from the hour using "menos" ("las diez menos
  veinte"). The book gives its own explicit NB flagging this as a genuine M/Spain structural
  difference worth separate attention, not merely vocabulary.
- **Seseo note (Unit 1):** the book's own pronunciation illustration "zapato = sapato, durazno =
  durasno (M)" for how c/z merge with s in Spanish-America (and southern Spain) speech — included
  here mainly because durazno itself is also a genuine M-tagged lexical item (see vocabulary table);
  the seseo phenomenon itself is a general Spanish-America-wide pattern already likely known to the
  project from other sources, so only briefly noted rather than treated as a new finding.

---

## PDF extraction notes

- **Real text layer confirmed, no vision-reading needed.** `pdftotext -layout` on the whole 354-page
  book produced clean, directly usable text throughout every page touched.
- **Page-offset gotcha (same genus as the spec's documented TOC-undercounting/offset issues):** a
  naive printed-page + 20 estimate was wrong. Empirically verified at three independent chapter-start
  points (Unit 1, Unit 2, Unit 30) that **PDF page = printed page + 24**, consistently.
- **"Model Answers" boundary is NOT where the TOC's listed order implies.** The TOC lists
  "Subjunctive index, Model answers..., Index..." in that order, which would suggest Model Answers
  comes well after a separate subjunctive-specific index section. In actual page order, "Model
  Answers / Soluciones y modelos" begins immediately after Unit 30 ends, at **PDF page 309** (verified
  by direct per-page read of PDF pages 306-309) — no separate standalone "Subjunctive index" section
  was located before it; it may be positioned elsewhere in the final ~45 pages, not needed since both
  are excluded from extraction. This boundary matters practically: an initial whole-book grep for
  `(M)` tags caught ~40 hits in PDF pages 309-336 that are pure answer-key restatements of exercises
  already seen in the units themselves — these were correctly excluded from the vocabulary table
  above after catching the discrepancy by direct-reading the boundary pages, rather than trusting
  page-range arithmetic.
- **Bracket-vs-parenthesis tag-style mismatch** between TOC (`[M]`) and body text (`(M)`) — see the
  note at the top of this file. Not a corruption/scrambling issue, just worth flagging so a future
  pass searching only for `[M]` doesn't undercount by a factor of ~25.
- No multi-column vocabulary-box scrambling, no font-substitution cipher, no raster-image-embedded
  target-language text, and no non-monotonic page ordering were observed anywhere in this book.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes, dialogue
blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`. All grammar-point explanations
above are paraphrased in the extractor's own words; illustrative examples quoted are short
(single-sentence) and drawn from the book's own worked examples, not reproduced wholesale lists. The
Unit 30 suffix catalog was deliberately truncated at a representative sample for -ucho/a rather than
transcribed in full.
