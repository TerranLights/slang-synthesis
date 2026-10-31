# Spanish — Established Vocabulary/Register: Diccionario de Sinónimos, Antónimos, Parónimos (representative sample)

**Source:** *Diccionario Polifuncional: Sinónimos, Antónimos, Parónimos, Usos de la Lengua Española*
(Arquetipo Grupo Editorial / Lexus Editores, Lima, Perú, 1st ed. February 2008), 879 pages, 14.5 MB.
Per its own introduction this is a composite 8-part reference work: (1) **the core synonym/antonym/
paronym dictionary** (>16,000 entries, >100,000 synonyms, 8,000 antonyms — pages roughly 1–382,
confirmed by sampling: p.20 = "adquisición," p.375 = "veteranía-vidrio," p.385 begins the next part's
own intro), (2) a Spanish→English/French/German/Italian basic vocabulary (~5,000 words, pages
~385–680), (3) grammar (verb paradigms, morphology — pages ~680+), (4) orthography/syllabification,
(5) Latin/foreign loan phrases and locutions (confirmed at p.750), (6) famous quotations, (7)
linguistics/discourse/oratory, and (8) a usage-correction guide ("Dudas del idioma y guía para la
corrección," confirmed at p.820). This extraction, per the task's scope, covers **only part (1), the
synonym/antonym/paronym dictionary proper** — parts (2)-(8) are out of scope here (part 3's verb
paradigms would be redundant with this language's existing grammar coverage anyway; parts 5-8 may be
worth a separate look in a future wave but were not sampled).

**Text layer:** clean, single-column, genuine text layer (PDFlib+PDI 6.0.3) — `pdftotext` reads it
directly with no reflow/interleaving noise (unlike the McGraw-Hill encyclopedic dictionary sampled
alongside this one, which has a two-column layout). Transcription confidence is `verified` throughout.

**Methodology — representative sampling, not exhaustive transcription.** The core dictionary section
(≈372 pages, ≈16,000 headwords) was sampled, not transcribed exhaustively, per this project's standing
convention for large reference dictionaries. **Important structural note: this dictionary does NOT
tag register or dialect at all** — no `fam.`/`coloq.`/`vulg.`/regional abbreviations anywhere in the
entries sampled (confirmed by grepping all samples for those tags: zero hits). Entries are flat lists
of synonyms (and, where applicable, antonyms marked `Ant.` and paronyms marked `Par.`) with no
register annotation whatsoever. This means the "register distinctions between near-synonyms" the task
asked to prioritize had to be **identified by the extractor's own judgment** (a working fluent-Spanish
read of which listed synonyms are elevated/literary vs. everyday vs. colloquial/slang), not read off
an abbreviation key the way McGraw-Hill's entries could be. This is flagged explicitly in every row's
Notes field below so downstream users know the register call is an inference, not a dictionary-stated
fact.

**Sampling coverage:** 23 page-pairs pulled across the ~372-page dictionary section, landing on
headwords spread through the alphabet — **pp. 20 (A), 50 (B), 63, 73 (C), 80 (C), 108, 120 (D), 150
(E), 170 (F), 190 (I), 220 (J), 230 (L), 240, 250 (M), 260 (N), 290 (P), 329 (R), 330 (R), 355 (T), 360
(T), 375 (V)** — i.e. 46 of ~372 dictionary pages (~12%), biased toward headwords for semantically
"rich" everyday concepts (money, jail, theft, foolishness, filth, deceit, laziness) where register
spread across synonyms is most likely, per the task's framing.

**Non-redundancy check:** existing Spanish established/ files already cover idiom/blunder-style
register content (033 Correct Your Spanish Blunders, 034 business Spanish) and basic vocabulary
(Practice Makes Perfect Vocabulary). Nothing below duplicates those — every row here draws on a
specific synonym cluster from this source and calls out a within-cluster register gradient (formal/
literary word vs. everyday word vs. colloquial/slang word for the same concept) that those other
sources don't cover in this form.

## Flagship findings

- **This source dictionary's complete absence of register tagging is itself a useful negative
  finding** for the project: it means a plain synonym dictionary is a *register-blind* source — useful
  for vocabulary breadth, useless on its own for telling a learner which synonym is safe in formal
  writing vs. only used in slang. The register judgment calls below had to be supplied externally.
- **cárcel ("jail/prison")** — synonym list spans from neutral/legal (*prisión, penal, correccional,
  penitenciaría*) straight to unmarked slang (*chirona, gayola*) with zero tag distinguishing them —
  a learner using this dictionary alone would have no way to know *gayola* is slang and *penitenciaría*
  is formal/legal register; they're presented as interchangeable.
- **moneda ("money/currency")** — synonym list includes the everyday *dinero, efectivo* alongside the
  distinctly bookish/archaic-flavored *pecunio* and *metálico* (literally "the metallic," an old-
  fashioned way to say "cash"), again presented flat with no register signal.
- **roñoso ("stingy/dirty")** — doubles as both a literal-filth adjective (*sucio, cochino, puerco,
  mugriento* — several of these themselves colloquial) and, in its second sense, a colloquial
  personality insult (*tacaño, miserable, avaro, mezquino*) for "cheap/stingy" — the dictionary
  correctly splits the two senses with `//` but doesn't register-flag either.

## Extraction table

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| capricho (syn. cluster) | whim, caprice | noun (m) | core, with one colloquial synonym | — | contemporary (source 2008) | — | Pan-Hispanic | grammar_reference | verified | n/a | Synonym list: *antojo, deseo, manía, voluntad, gusto* (neutral) plus **chifladura** (colloquial "craze/obsession") and *desvarío* (more literary "delirium"); dictionary lists all flat, no register tag — register call is the extractor's own. |
| cárcel (syn. cluster) | jail, prison | noun (f) | core + slang | high | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | Flagship find: *prisión, penal, correccional, penitenciaría* (neutral/legal) vs. **chirona, gayola** (unmarked slang for "jail/clink") listed in the same undifferentiated line. |
| descarado (syn. cluster) | shameless, insolent person | adj. | core + colloquial | moderate | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | *desvergonzado, atrevido, maleducado, grosero, insolente* (neutral-to-formal) vs. **zafado, desfachatado, procaz** (more colloquial/vivid); again flat, no register markers. |
| descaro (syn. cluster) | nerve, insolence, cheek | noun (m) | core + colloquial | moderate | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | *desvergüenza, osadía, insolencia* (formal) vs. **tupé, desfachatez** (more colloquial, "tupé" borrowed metaphor from "toupée/hairpiece" for brazen nerve). |
| desbocado (syn. cluster) | foul-mouthed; (of a horse/person) out of control | adj. | core + colloquial | moderate | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | *desvergonzado, malhablado, sinvergüenza, deslenguado* — colloquial-insult register throughout, no formal alternative offered in this sense. |
| desatino (syn. cluster) | blunder, foolish mistake | noun (m) | core + colloquial | high | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | *error, equivocación, desacierto, yerro* (neutral) vs. **disparate, barbaridad, necedad** (stronger, more colloquial-flavored for "nonsense/outrage"). |
| descamisado (syn. cluster) | poor, ragged person | adj. | core, politically loaded | low | contemporary (also historical Argentine political term, unremarked by this source) | Pan-Hispanic (also historically Argentina) | transnational | grammar_reference | verified | n/a | *pobre, andrajoso, harapiento, indigente*; note (external to the dictionary) that *descamisado* has a specific loaded political history in Argentina (Peronist "shirtless ones") not mentioned by this source at all — a gap worth flagging. |
| lío (syn. cluster) | bundle; mess/jam; lie, gossip | noun (m) | core, triple-sense | high | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | Three senses split by `//`: literal "bundle" (*fardo, bulto, paquete*), figurative "mess/trouble" (*enredo, embrollo, complicación*), and colloquial "lie/gossip" (**mentira, embuste, chisme, cuento**) — the last sense is the most colloquial-register of the three but isn't marked as such. |
| listo (syn. cluster) | quick, clever; ready | adj. | core | high | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | "Inteligente, astuto, sagaz, avisado, despabilado, perspicaz" vs. antonym **tonto, torpe** — shows the formal register end of the smart/dumb polarity; *despabilado* itself leans colloquial ("sharp/switched-on"). |
| lisonja / lisonjear (syn. cluster) | flattery; to flatter | noun/verb | core, literary-leaning | moderate | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | *alabanza, halago, adulación, zalamería* — all fairly literary/formal register for "flattery," notably without a crude slang equivalent offered (a possible gap — Spanish has cruder terms like "lamber/lambiscón" in some regions, not surfaced by this dictionary). |
| llorón (syn. cluster) | crybaby, whiner | adj./noun | core + colloquial | moderate | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | *lloroso, plañidero, quejoso, sollozante, gemebundo* (mostly formal/literary) vs. **quejica** (clearly colloquial diminutive-pejorative for "whiner"), unmarked. |
| mojigato (syn. cluster) | prudish, sanctimonious person | adj./noun | core + colloquial | moderate | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | *santurrón, gazmoño, puritano* (formal/literary) vs. **beato** (also used very colloquially as "goody-goody"), *pazguatería* for the related noun form is itself a fairly colloquial-sounding coinage. |
| moneda (syn. cluster) | money, currency | noun (f) | core, formal-to-archaic spread | high | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | Flagship find: *dinero, efectivo* (everyday) vs. **pecunio** (bookish/jocular-archaic) and **metálico** (dated "hard cash" sense); no register distinction drawn by the source. |
| mondongo (syn. cluster) | belly, guts | noun (m) | colloquial | moderate | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | *intestinos, vientre, tripas, vísceras, panza, barriga* — the headword *mondongo* itself is a colloquial/informal body-term (also a culinary term for tripe dishes in several countries, not mentioned here), listed with no register flag at all. |
| monigote (syn. cluster) | puppet, dummy; (fig.) ignorant/dim person | noun (m) | colloquial, insult sense | moderate | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | Literal "puppet/rag doll" (*muñeco, títere, fantoche, pelele, marioneta*) vs. figurative insult "ignorante, rudo, torpe, tosco" — the figurative sense is a common colloquial put-down for a foolish/unsophisticated person. |
| robar / robo (syn. cluster) | to steal / theft | verb/noun | core + colloquial | high | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | *hurtar, sustraer, despojar, usurpar* (formal/legal register) vs. **timar, pillar, ratería, pillaje** (more colloquial/everyday); again undifferentiated by the source. |
| roña / roñoso (syn. cluster) | grime, filth; stingy, miserly | noun/adj. | colloquial, double sense | moderate | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | Flagship find: literal-filth sense (*mugre, suciedad, cochambre, pringue* — several already colloquial) correctly split with `//` from the personality-insult sense (*tacaño, miserable, avaro, mezquino*) for "stingy" — source splits by meaning but not by register. |
| rollo (syn. cluster, "bore/drag" sense) | a bore, a tedious thing/situation | noun (m) | colloquial | high | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | Literal senses "cylinder, roll, bundle" (*cilindro, rulo, ovillo, madeja*) vs. the clearly colloquial figurative sense **lata, pesadez** ("what a drag/bore") — a very common everyday usage the dictionary buries as a minor `//` sub-sense with no register note. |
| descalabro (syn. cluster) | disaster, setback, misfortune | noun (m) | core | moderate | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | *revés, calamidad, desastre, contratiempo, desventura, quebranto* — mostly formal/literary register, no colloquial equivalent surfaced in this entry. |
| caqui / caquéctico (morphology note) | khaki (color); cachectic (medically wasted/emaciated) | adj. | technical/formal | low | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | Not a register case but a distinctive morphological cluster: *caquéctico* (medical Greek-derived term, "flaco, débil, consumido, debilitado") sits alphabetically right next to the unrelated color term *caqui* — a reminder that visual alphabetic proximity in a dictionary can mask etymologically unrelated words. |
| modorra (syn. cluster) | drowsiness, grogginess | noun (f) | core + colloquial-leaning | moderate | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | *somnolencia, letargo, sopor* (formal/medical-ish) vs. **flojera** (clearly colloquial, "laziness/sluggishness," widely used across Latin America as an everyday word for "not feeling like doing anything"). |
| mofa / mofarse (syn. cluster) | mockery; to mock | noun/verb | core + colloquial | moderate | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | *burla, broma, befa, escarnio* (neutral-formal) vs. **chasquear, chancearse** (more colloquial verb forms for "to tease/joke around"). |
| mohíno (syn. cluster) | sulky, sullen, in a bad mood | adj. | core | moderate | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | *enojado, enfadado, contrariado, airado, cabizbajo* — overlaps with McGraw-Hill's *cabizbajo* entry (047), cross-referencing confirms consistent core meaning "downcast/crestfallen" across both sources. |
| mollera (syn. cluster) | brains, wits (colloquial "noggin"-adjacent sense) | noun (f) | colloquial | moderate | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | *seso, sesera, meollo, cacumen, caletre, inteligencia, talento* — *sesera* and *caletre* both lean colloquial/folksy for "brains/wits," contrasted with antonym **torpeza, necedad**. |
| liviandad / liviano (syn. cluster, "sexual" sense) | promiscuity/looseness; promiscuous, loose (person) | noun/adj. | formal-register euphemism for a taboo concept | low | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | *deshonestidad, incontinencia, desenfreno, lubricidad, lascivia, impudicia, lujuria* — an entirely Latinate/formal vocabulary set for describing sexual looseness, with zero crude/vulgar equivalent surfaced; notable as a case where the dictionary's register ceiling for a taboo topic stays politely elevated throughout. |
| riqueza (syn. cluster, wealth sense) | wealth, riches | noun (f) | core | high | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | Second `//` sense ("hacienda, caudal, dinero, tesoro, medios") reuses *dinero* and *caudal*, cross-referencing the *moneda* cluster above — shows the dictionary's internal vocabulary network for the wealth/money semantic field. |
| litera (syn. cluster) | bunk bed; litter/stretcher (historical) | noun (f) | core, two distinct referents | low | contemporary (modern sense); historical (litter/palanquin sense) | — | Pan-Hispanic | grammar_reference | verified | n/a | Splits a modern everyday object ("cama, camastro, catre") from a historical conveyance ("palanquín, angarillas, andas, silla de manos") under one headword — a clean example of semantic drift the dictionary preserves without any era/historical flag (added here as Attested Era by the extractor). |
