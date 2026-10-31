# Spanish — Established Vocabulary/Grammar: Collins Easy Learning Spanish Grammar (full-book extraction)

**Source:** *Collins Easy Learning Spanish Grammar*, HarperCollins, 1st Edition 2004. 163 PDF pages.

**IMPORTANT text-layer finding, corrected from the project's original triage:** this file's 161MB
size (anomalous for 163 pages) is explained — it is a 300dpi-scanned book whose nominal "text layer"
is a LOW-QUALITY OCR pass full of character-level errors (confirmed repeatedly: "Grammar"→"Crammar",
"Glasgow"→"clasgow", "ISBN"→"rsBN", "If"→"lf", "Pronouns"→"Pnonourus"/"PRoruourus"/"Vrnes"/"Venes"/
"VEnBs"). The OCR text was unreliable for exact vocabulary spelling/diacritics and was used only as a
rough section-boundary navigation aid; **all actual Vocabulary-table and grammar-point content below
was vision-read from the rendered page images** (150dpi `pdftoppm` renders), which were a clean, sharp
commercial scan — fully legible on direct inspection (Vision Reading Confidence = `verified`
throughout, per entries below). No handwritten marginalia was found anywhere in the book across all
four dispatch chunks.

**Second important layout finding:** the book's main body is scanned as **two-printed-pages-per-PDF-
page landscape spreads** throughout (not one PDF page = one printed page as initially assumed from a
front-cover-only spot check) — confirmed empirically by each chunk subagent against the book's own
visible printed page numbers, with the mapping varying piecewise by section (main body pp.1–163 of
the book's own front-matter numbering runs across PDF pp.8–123; the Verb Tables/Verb Index appendix
restarts its own page numbering from 1 around PDF p.117). Printed page ranges stated in each Part
below were independently verified by direct inspection, not assumed from arithmetic.

**Coverage note:** every grammar point and every distinct vocabulary item from the book's Nouns,
Articles, Adjectives, Pronouns, Verbs, Negatives, Questions, Adverbs, Prepositions, Conjunctions,
Spelling, Stress/Accentuation, Numbers, and Time/Date chapters, plus a curated selection from the
Verb Tables/Verb Index appendix and the full Alphabet/IPA pronunciation table, plus every explicit
dialectal/regional annotation the source marks (this book explicitly contrasts Peninsular Spain vs.
Latin America usage throughout, e.g. vosotros vs. ustedes, and the [θ] vs. [s] c/z pronunciation
split). Full verb-paradigm conjugation tables in the appendix were sampled rather than exhaustively
reproduced (see Part 4's own scope note) since that content is fully redundant with this corpus's
existing `007`/`008`(b/c) verb-tense files.

**Non-redundant-supplement handling (applies across all four parts):** this Spanish corpus already
has 15+ base established files (001–015, plus 016 where cited) covering standard pedagogical grammar
comprehensively. Each part below states explicitly what was treated as "previously covered, not
re-extracted" versus kept in full. A particularly thorough redundancy audit in Part 2 found this
book's entire "Verbs" chapter topically overlaps `007`/`008`(b/c)'s dedicated verb-tense reference at
equal or greater systematic depth, and documents that audit topic-by-topic rather than silently
skipping the chapter.

**Outside-source background flagged (not structured as sourced data):** *coger* carries a well-known
taboo sense ("to screw"/"to fuck") in much of Latin America vs. its neutral Peninsular meaning
("to take/catch") — flagged for future Phase 3 cross-check, consistent with the same finding
independently surfacing in `019`'s Chapter 30 (Latin American vs. Peninsular Spanish).

---

## Spanish — Established Vocabulary/Grammar: Collins Easy Learning Spanish Grammar — Nouns, Articles, Adjectives, Pronouns

**Source:** Collins Easy Learning Spanish Grammar, HarperCollins, 1st Edition 2004. Printed pages
1–67 (Nouns, Articles, Adjectives, Pronouns chapters, ending immediately before the Verbs chapter
at printed p.69). PDF pages 8–41 of the source file.

### PDF structure note (confirmed empirically, not assumed)

This source is **scanned as two-printed-pages-per-PDF-page landscape spreads**, the same gotcha
flagged in `00_Reference_Extraction_Spec.md` for the verb-table appendix (pp.124–163) — but it is
**also true of the entire main body**, not just the appendix. PDF page N renders printed pages
`(2N−16)` and `(2N−15)`. Verified directly by rendering and reading PDF pages 8 and 9: PDF p.8's
right-hand side is printed p.1 ("NOUNS — Using nouns"), PDF p.9 shows printed pp.2–3 ("Gender").
PDF pages 1–7 are front matter (title/copyright/TOC/foreword/introduction/glossary of grammar
terms, pp. i–xii) and were skipped per the dispatch instruction. This chunk's actual PDF range
read was **8–41** (not the nominally assigned 1–41) to land exactly on printed p.1 and stop at
printed p.67, which is where the Pronouns chapter ends and the Verbs chapter begins — a clean
chapter-boundary match confirmed against the book's own table of contents.

### Vision-reading note

Confirmed per the dispatch: this PDF has a text layer, but it is **low-quality, character-corrupted
OCR** (e.g. "Grammar"→"Crammar", "Glasgow"→"clasgow"), unreliable for exact vocabulary spelling or
diacritics. All vocabulary and grammar content below was **vision-read from the rendered page
images** (150dpi), not taken from `pdftotext`, which was used only for initial navigation (finding
the TOC/chapter boundaries). Vision Reading Confidence is marked per spec scale below rather than
`n/a`. Print quality was uniformly clear and high-contrast throughout this range (clean scan, sharp
blue/black sans-serif text) — nearly everything is `verified` or `plausible_unverified`; the handful
of `low_confidence` rows are flagged individually.

**Marginalia guard:** actively checked every one of the 34 rendered spreads for handwritten
pencil/pen marks (previous-owner notes, underlines, filled-in exercise answers) distinct from the
printed typeface, per the spec's vision-reading guard. **None found.** This appears to be an
unmarked/clean copy — every mark on every page (including the "Tip"/"Key points"/"Grammar Extra"
boxes) is part of the book's own printed design, not reader annotation.

### Non-redundant-supplement scope decision

Spanish already has 15+ established base-grammar files. Skimmed `005_practice_makes_perfect_basic_spanish_grammar.md`
(comprehensive lesson-by-lesson beginner coverage of articles/adjectives/pronouns across its first
~14 lessons) and `015_schaums_outline_of_spanish_grammar.md` (which already has dedicated grammar-point
subsections on *leísmo*, *usted/ustedes* etymology/abbreviations, gender-changing/irregular-gender
nouns, and a full *voseo* paradigm) before extracting. Also checked `016_student_grammar_of_spanish.md`,
which explicitly notes it treated the vosotros/ustedes (Spain vs. Spanish-America) address-system
contrast as already covered by 015 and skipped re-extracting it.

**Treated as redundant and not re-extracted in full:** the basic -o/-a gender rule for people, basic
singular→plural -s/-es pluralization, the basic el/la/los/las and un/una/unos/unas paradigms, basic
adjective agreement (-o→-a), and the bare fact that Spain uses *vosotros* where Spanish America uses
*ustedes* (already documented in 015/016) — these are standard beginner-grammar content present in
multiple existing files. Noted briefly in the Grammar points below as "(previously covered, not
re-extracted in full)" with only the paradigm skeleton given for reference/linking.

**Kept and extracted in full, because not clearly covered elsewhere or genuinely deeper/more
systematic than existing coverage:**
- The **full "Ways of saying 'you'" synthesis** (pp.44–45) that ties together tú/usted/vosotros/
  ustedes selection criteria (familiarity × number) in one place, cross-referenced from five
  different chapters (possessive adjectives, subject pronouns, possessive pronouns) — this
  cross-referencing density itself suggests the book treats it as a structurally central point.
- A **prescriptive note on Spanish-Spain leísmo** (p.53): the book explicitly advises learners *not*
  to copy the Spain usage of *le/les* for direct objects referring to men, calling it "probably...
  incorrect in some varieties of Spanish, particularly Latin American ones" — a judgment-call framing
  distinct from 015/016's more neutral descriptive treatment of the same phenomenon.
- The **gender-meaning-shift noun set** (el capital/la capital, el cura/la cura, el cometa/la cometa,
  el guía/la guía) and the **plural-mismatch clothing-noun set** (una braga, un slip, un pantalón —
  singular in Spanish, plural in English) — specific vocabulary classes not seen flagged elsewhere.
- The **dual-position-meaning-shift adjective table** (antiguo, diferente, grande, medio, mismo,
  nuevo, pobre, viejo) — a systematic 8-adjective comparison table, more exhaustive than a typical
  beginner grammar's passing mention of antes/después-position adjectives.
- The **article *lo*** system in full (lo + masc. adjective/participle = abstract noun; lo que; lo de;
  lo + adj/adv + que; common fixed phrases a lo mejor/por lo menos/por lo general) — Collins treats
  *lo* as its own named article class, which is a more systematic treatment than scattered mentions.
- The **systematic list of definite-article-used-in-Spanish-but-not-English contexts** (general
  statements, abstract qualities, colors, body parts, titles-when-talking-about-not-to, institutions,
  meals/games/sports, days/dates, time, prices/rates) as one consolidated rule set.
- Full **indefinite/relative/interrogative/demonstrative pronoun paradigms**, including the formal
  *el cual/la cual* register-alternative to *el que*, *cuyo/cuya* (whose), and the *qué es/cuál es*
  distinction — not confirmed present in the skimmed files.
- All distinct **indefinite pronoun vocabulary** (algo, alguien, alguno, cada uno, cualquiera, nada,
  nadie, ninguno, otro, poco, tanto, todo, varios, uno...el otro) as a vocabulary set.

---

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| el hombre / la mujer | man / woman | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | basic masculine/feminine-by-sex pair (p.2) |
| el estudiante / la estudiante | (male/female) student | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | same form, gender shown only by article (p.2) |
| el belga / la belga | Belgian (man/woman) | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | same form, gender shown only by article (p.2) |
| la persona | person (male or female) | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | always feminine grammatically regardless of referent's sex (p.2) |
| la víctima | victim (male or female) | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | always feminine grammatically regardless of referent's sex (p.2) |
| el camarero / la camarera | waiter / waitress | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | -o/-a pair (p.2) |
| el inglés / la inglesa | Englishman / Englishwoman | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | consonant+a feminine, lowercase nationality noun (p.2) |
| el toro / la vaca | bull / cow | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | wholly distinct words for male/female animal (p.3) |
| el perro / la perra | (male) dog / (female) dog, bitch | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | -o/-a animal pair (p.3) |
| el sapo | toad | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | invariable-gender animal noun (p.3) |
| el hámster | hamster | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | invariable-gender animal noun (p.3) |
| la cobaya | guinea pig | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | invariable-gender animal noun (p.3) |
| la tortuga | tortoise | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | invariable-gender animal noun (p.3) |
| el libro / el periódico | book / newspaper | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | -o masculine ending examples (p.4) |
| la mano | hand | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | feminine EXCEPTION to -o=masculine rule (p.4) |
| la foto | photo | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | feminine exception (clipped form of fotografía) (p.4) |
| la moto | motorbike | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | feminine exception (clipped form of motocicleta) (p.4) |
| la radio | radio | noun | regional | — | contemporary (source published 2004) | Spain (feminine) vs. parts of Latin America (el radio, masculine) | transnational | grammar_reference | n/a | verified | explicit dialectal gender split flagged by source itself (p.4) |
| el inglés / el español | English (language) / Spanish (language) | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | language names are masculine (p.4) |
| el Ebro / el Everest / el Atlántico | the Ebro / Everest / the Atlantic | proper noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | rivers/mountains/seas masculine (p.4) |
| la casa / la cara | house / face | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | -a feminine ending examples (p.4) |
| el día / el mapa / el planeta / el tranvía | day / map / planet / tram | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | masculine EXCEPTIONS ending in -a (p.4) |
| el problema / el programa / el sistema / el clima | problem / programme / system / climate | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | masculine nouns ending in -ma (p.4) |
| la lección / la estación / la expresión | lesson / station / expression | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | -ción/-sión feminine ending (p.4) |
| la ciudad / la libertad / la multitud | city / freedom / crowd | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | -dad/-tad/-tud feminine ending (p.4) |
| el capital / la capital | capital (money) / capital (city) | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | gender changes the MEANING, not just the referent (p.5) — kept per non-redundant-supplement scope |
| el cometa / la cometa | comet / kite | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | gender-meaning-shift pair (p.5) |
| el cura / la cura | priest / cure | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | gender-meaning-shift pair (p.5) |
| el guía / la guía | guide (man) / guidebook or guide (woman) | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | gender-meaning-shift pair, one feminine sense is a person, other an object (p.5) |
| el rey / la reina | king / queen | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | wholly distinct masc/fem words (p.5) |
| el viudo / la viuda | widower / widow | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | -o/-a pair (p.5) |
| el dentista / la dentista | (male/female) dentist | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | -ista nouns, same form both genders, only article distinguishes (p.5) |
| el deportista / la deportista | sportsman / sportswoman | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | -ista noun, same form (p.5) |
| un inglés / una inglesa | an Englishman / an Englishwoman | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | accented masculine drops accent in feminine form (p.6) |
| un francés / una francesa | a Frenchman / a Frenchwoman | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | accented masculine drops accent in feminine form (p.6) |
| el jersey / los jerseys | jersey / jerseys | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | foreign loanword ending in consonant takes plain -s plural (p.7) |
| el jabalí / los jabalíes | boar / boars | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | accented-vowel noun takes -es plural (p.8) |
| el café / los cafés | café / cafés | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | accented-vowel noun taking plain -s (irregular vs. jabalí pattern) (p.8) |
| la canción / las canciones | song / songs | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | accent dropped when -es plural added (p.8) |
| el examen / los exámenes | exam / exams | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | multi-syllable -en noun gains accent in plural (p.8) |
| la luz / las luces | light / lights | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | -z → -ces plural spelling change (p.9) |
| el abrelatas | tin-opener | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | compound noun, invariable in plural (los abrelatas) (p.8) |
| el hombre rana | frogman | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | compound noun, DOES pluralize (los hombres rana) (p.8) |
| una braga / un slip / un pantalón | (a pair of) knickers / underpants / trousers | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | clothing nouns: plural in English, singular in Spanish (p.9) |
| un mueble / unos muebles | a piece of furniture / some furniture | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | mass-noun-in-English counted differently in Spanish (p.9) |
| al cine / al hospital | to the cinema / to the hospital | prepositional phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | a + el → al contraction (p.12) |
| del departamento / del autor | of/from the department / of/from the author | prepositional phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | de + el → del contraction (p.12) |
| tener hambre / sin duda / con cuidado | to be hungry / no doubt / carefully | idiom | idiomatic | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | set phrases where Spanish omits the article it would otherwise require (p.12) |
| el agua / el hacha | the water / the axe | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | el before stressed-a/ha feminine singular nouns to avoid a-a clash (p.11) |
| la misma agua / la mejor hacha | the same water / the best axe | noun phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | la restored once an adjective intervenes before the noun (p.11) |
| un ave | a bird | noun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | un before stressed-a feminine singular noun (p.15) |
| otro libro / cierta calle / cien soldados / mil años | another book / a certain street / a hundred soldiers / a thousand years | noun phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | words that never take the indefinite article (p.16) |
| lo único / lo importante / lo bueno | the only thing / the important thing / the good thing | noun phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | lo + masc. adjective forms an abstract noun (p.17) |
| a lo mejor | maybe, perhaps | adverbial phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | fixed lo phrase (p.17) |
| por lo menos | at least | adverbial phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | fixed lo phrase (p.17) |
| por lo general | generally | adverbial phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | fixed lo phrase (p.17) |
| lo de tu hermano | that business with your brother | noun phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | lo de + noun phrase referring to shared-knowledge topic (p.17) |
| un gesto burlón / una sonrisa burlona | a mocking gesture / a mocking smile | noun phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | -ón→-ona feminine adjective (p.21) |
| un hombre parlanchín / una mujer parlanchina | a chatty man / a chatty woman | noun phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | -ín→-ina feminine adjective (p.21) |
| mejor / peor | better/best / worse/worst | adjective | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | irregular comparative/superlative, invariable for gender (p.21, p.27) |
| mayor / menor | older/oldest / younger/youngest | adjective | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | irregular comparative/superlative, invariable for gender (p.21, p.27) |
| superior / inferior / exterior / posterior | upper / lower / outside / rear | adjective | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | -or adjectives that do NOT change in the feminine (p.21) |
| azul marino / naranja | navy blue / orange | adjective | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | invariable adjectives, never change for gender/number (p.22) |
| bueno→buen, malo→mal | good, bad (shortened) | adjective | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | drop final -o before masc. singular noun (p.22) |
| alguno→algún, ninguno→ningún | some, none (shortened) | adjective | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | drop -o and add accent before masc. singular noun (p.22–23) |
| uno→un, primero→primer, tercero→tercer | one, first, third (shortened) | adjective | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | drop -o before masc. singular noun (p.22) |
| grande→gran | big, great (shortened) | adjective | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | shortens before ANY singular noun (masc. or fem.) (p.23) |
| ciento→cien | a hundred (shortened) | adjective | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | shortens before all plural nouns and before mil/millones (p.23) |
| cualquiera | any, anybody | indefinite adjective/pronoun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | drops final -a before any noun (cualquier día) (p.23) |
| antiguo (antes: former / después: old, ancient) | former / old, ancient | adjective | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | position-dependent meaning shift, part of 8-adjective comparison table (p.25) |
| diferente (antes: various / después: different) | various / different | adjective | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | position-dependent meaning shift (p.25) |
| grande (antes: great / después: big) | great / big | adjective | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | position-dependent meaning shift (p.25) |
| medio (antes: half / después: average) | half / average | adjective | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | position-dependent meaning shift (p.25) |
| mismo (antes: same / después: self, very, precisely) | same / self, very, precisely | adjective | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | position-dependent meaning shift (p.25) |
| nuevo (antes: new to owner / después: brand new) | new (to me) / brand new | adjective | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | position-dependent meaning shift (p.25) |
| pobre (antes: wretched / después: not rich) | poor (wretched) / poor (not rich) | adjective | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | position-dependent meaning shift (p.25) |
| viejo (antes: long-standing / después: aged) | old (long-standing) / old (aged) | adjective | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | position-dependent meaning shift (p.25) |
| delgadísimo / carísimo / facilísimo / rapidísimo | really thin / really expensive / extremely easy / extremely fast | adjective | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | -ísimo absolute superlative, with accent-drop (fácil→facilísimo) (p.29) |
| riquísimo / ferocísimo | extremely rich / extremely fierce | adjective | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | -ísimo with spelling change (c→qu, z→c) to preserve sound (p.29) |
| este/esta/estos/estas | this/these (near speaker) | demonstrative adjective | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | three-way distance system, near-speaker term (p.30) |
| ese/esa/esos/esas | that/those (near listener, not far) | demonstrative adjective | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | mid-distance term; also used for a definite past date/year per Grammar Extra (p.30–31) |
| aquel/aquella/aquellos/aquellas | that/those (further away) | demonstrative adjective | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | far-distance term; used for an indefinite/non-dated past per Grammar Extra (p.30–31) |
| mi/tu/su/nuestro/vuestro/su | my/your/his-her-its-your/our/your/their | possessive adjective (short form) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | short possessive paradigm, cross-referenced to "Ways of saying you" (p.35) |
| mío/tuyo/suyo/nuestro/vuestro/suyo | mine/yours/his-hers-theirs-yours/ours/yours/theirs | possessive adjective (long form) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | long/stressed possessive paradigm, goes AFTER the noun (p.37) |
| algún día / el mismo día / otro coche / mucha gente / otra manzana / pocos amigos | some day / the same day / another car / a lot of people / another apple / few friends | indefinite adjective | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | algún/cada/mismo/mucho/otro/poco/tanto/todo/varios indefinite-adjective set (p.39) |
| yo / tú / él / ella / usted (Vd.) | I / you / he / she / you (formal) | subject pronoun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | singular subject-pronoun paradigm (p.42) |
| nosotros/nosotras / vosotros/vosotras / ellos/ellas / ustedes (Vds.) | we (m/f) / you-pl (m/f) / they (m/f) / you (formal pl.) | subject pronoun | core | — | contemporary (source published 2004) | Spain uses vosotros/vosotras for familiar plural "you"; Latin America uses ustedes instead | transnational | grammar_reference | n/a | verified | plural subject-pronoun paradigm; vosotros/ustedes split explicit in source (p.42, p.44) — basic fact previously covered by 015/016, full cross-referenced synthesis kept here |
| me/te/lo/la — nos/os/los/las | me/you/him-it-you — us/you/them-you | direct object pronoun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | DO pronoun paradigm (p.46) |
| me/te/le — nos/os/les | me/you/him-her-it-you — us/you/them-you | indirect object pronoun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | IO pronoun paradigm (p.49) |
| se lo / se las | it to him-her-you-them / them to him-her-you-them | combined object pronoun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | le/les→se before lo/la/los/las (p.52) |
| mí/ti/él/ella/usted/sí — nosotros/vosotros/ellos/ellas/ustedes/sí | me/you/him/her/you/himself(etc.) — us/you/them/them/you/themselves | prepositional pronoun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | pronouns used after prepositions; mí/ti/sí differ from subject forms (p.54) |
| conmigo / contigo / consigo | with me / with you / with himself-herself-themselves | prepositional pronoun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | con + mí/ti/sí fuse into single words (p.54–55) |
| entre tú y yo | between you and me | prepositional phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | entre/hasta/menos/salvo/según exceptionally take SUBJECT pronouns yo/tú, not mí/ti (p.55) |
| el mío/la mía/los míos/las mías | mine | possessive pronoun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | possessive-pronoun paradigm, agrees with thing owned not owner (p.56) |
| el suyo / el de usted / el de ellos | his-hers-yours-theirs / the one belonging to you / theirs | possessive pronoun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | el suyo is ambiguous; el/la/los/las de + pronoun/noun disambiguates (p.57) |
| algo | something, anything | indefinite pronoun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | closed-class indefinite pronoun set (p.58) |
| alguien | somebody, anybody | indefinite pronoun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | takes personal a when object of verb (p.58) |
| alguno/alguna/algunos/algunas | some, a few | indefinite pronoun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | agrees for gender/number (p.58) |
| cada uno/cada una | each one, everybody | indefinite pronoun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | (p.58) |
| cualquiera | anybody, any | indefinite pronoun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | (p.58) |
| mucho/mucha/muchos/muchas | much, many | indefinite pronoun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | (p.58) |
| nada | nothing, anything | indefinite pronoun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | used alone to answer, or with no for "not...anything" (p.59–60) |
| nadie | nobody, anybody | indefinite pronoun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | takes personal a as object (p.59) |
| ninguno/ninguna | none, any | indefinite pronoun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | (p.59) |
| otro/otra/otros/otras | another one, others | indefinite pronoun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | never preceded by un/una (p.59) |
| poco/poca/pocos/pocas | little, few | indefinite pronoun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | (p.59) |
| tanto/tanta/tantos/tantas | so much, so many | indefinite pronoun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | (p.59) |
| todo/toda/todos/todas | all, everything | indefinite pronoun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | (p.59) |
| uno...el otro / unos...los otros | one...the other / some...the others | indefinite pronoun pair | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | correlative pair construction (p.59–60) |
| varios/varias | several | indefinite pronoun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | (p.60) |
| que | who, which, that | relative pronoun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | universal relative pronoun for people/things; can NEVER be omitted in Spanish unlike English "that" (p.61–62) |
| el que/la que/los que/las que — quien/quienes | who, which, that (after a preposition) | relative pronoun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | required after a preposition, in place of bare que; el que agrees for gender/number, quien only for number (p.61) |
| el cual/la cual/los cuales/las cuales | who, which, that (formal register) | relative pronoun | literary | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | explicitly flagged as "a more formal alternative" found in written/literary register, after a preposition (p.64) |
| cuyo/cuya/cuyos/cuyas | whose | relative adjective | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | agrees with the noun it describes, NOT with the possessor — same logic as possessive adjectives (p.64) |
| lo que | what, which (referring to a whole clause) | relative pronoun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | neuter relative referring back to an entire previous idea (p.63) |
| ¿qué? | what? | interrogative pronoun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | (p.65) |
| ¿cuál?/¿cuáles? | which (one/s)?, what? | interrogative pronoun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | used for choice among options; never used directly before a noun (use qué instead) (p.65–66) |
| ¿quién?/¿quiénes? | who? | interrogative pronoun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | ¿a quién? for object/whom, ¿de quién? for whose (p.66) |
| ¿cuánto?/¿cuánta?/¿cuántos?/¿cuántas? | how much?/how many? | interrogative pronoun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | (p.66) |
| éste/ésta/esto / ése/ésa/eso / aquél/aquélla/aquello | this one / that one (near) / that one (far) | demonstrative pronoun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | pronoun forms kept the accent mark distinguishing them from the adjective forms in this 2004 edition (pre-2010 RAE orthography) — flagged for Attested Era as edition-specific spelling convention |

### Grammar points

#### Chapter: Nouns (pp.1–9)

##### Gender basics (p.1–3) — *previously covered, not re-extracted in full*

Covered comprehensively in 005 and other beginner books: nouns referring to people/animals/things
are masculine or feminine; -o usually masculine, -a usually feminine; gender affects adjectives,
articles, pronouns. Kept here only as the skeleton other rows below build on.

##### Gender-invariant nouns (p.2)

A small closed set of nouns referring to people (persona, víctima) have only one grammatical gender
regardless of the sex of the person referred to — "the male or female victim" is always *la víctima*.

##### Gender-meaning-shift nouns (p.5)

A handful of Spanish nouns change their actual *meaning*, not just agreement, when the article's
gender changes: el capital (money) vs. la capital (city); el cometa (comet) vs. la cometa (kite); el
cura (priest) vs. la cura (cure); el guía (male guide) vs. la guía (guidebook, or a female guide).
This is a distinct phenomenon from ordinary -o/-a gender pairs and is not reducible to "look up the
gender" advice given elsewhere in the book.

##### Gender endings tables (p.4–5)

Systematic endings lists: **masculine** by default — -o (el libro); also all days/months, language
names, and river/mountain/sea names are masculine regardless of ending (el lunes, el español, el
Ebro). **Feminine** by default — -a (la casa, with named exceptions el día/el mapa/el planeta/el
tranvía and most -ma words like el problema/el programa); also -ción/-sión, -dad/-tad, -tud are
reliably feminine (la lección, la ciudad, la libertad). A "Grammar Extra" box separately notes the
el capital/la capital-type meaning-shift class above as a named exception category.

##### Consonant-ending nouns and masculine→feminine -a formation (p.6)

Many masculine nouns ending in a consonant simply add -a for the feminine (el español→la española,
el profesor→la profesora). If the final vowel of the masculine form carries a written accent, that
accent is dropped in the feminine (un inglés→una inglesa, un francés→una francesa) — the accent was
there only to mark stress on a now-non-final syllable.

##### Plural formation (p.6–9) — *basic rule previously covered, kept: the exception/spelling-change
layer*

Basic add-s-to-vowel / add-es-to-consonant rule is standard beginner content. Collins adds a fuller
exception layer: (1) nouns ending in an *unstressed* -s don't change in the plural (el lunes→los
lunes, el paraguas→los paraguas); (2) nouns ending in an accented vowel split unpredictably between
adding -es with the accent then dropped (el jabalí→los jabalíes) and simply adding -s (el café→los
cafés, el sofá→los sofás) — "it is always best to check in a dictionary to see what the plural is";
(3) nouns ending in an accented vowel + -n or -s drop the accent when -es is added (la canción→las
canciones, el autobús→los autobuses); (4) nouns of more than one syllable ending in unaccented -en
*gain* a written accent in the plural to preserve stress (el examen→los exámenes); (5) -z changes to
-ces (la luz→las luces). Compound nouns (noun+noun) behave unpredictably: el abrelatas stays
invariable in the plural (los abrelatas) while el hombre rana does pluralize (los hombres rana) — "it
is always best to check in a dictionary."

##### Plural-vs-singular mismatches with English (p.9)

A small set of clothing nouns are grammatically singular in Spanish but conventionally plural in
English: una braga (a pair of knickers), un slip (a pair of underpants), un pantalón (a pair of
trousers). Conversely, some mass/collective-ish nouns are countable as singular "a piece of X" items
in Spanish where English treats them as uncountable: un mueble (a piece of furniture) vs. unos
muebles (some furniture); una noticia (a piece of news); un consejo (a piece of advice).

---

#### Chapter: Articles (pp.10–18)

##### Definite article el/la/los/las: basic paradigm — *previously covered, not re-extracted in full*

Standard beginner content (el/la singular, los/las plural by gender) present in multiple existing
files.

##### a+el→al, de+el→del contractions (p.12)

Mandatory fusions: a + el always becomes al (al cine, "Vio al camarero"); de + el always becomes del
(del departamento, "of/from the department"). These are the only two such contractions in Spanish
article usage covered in this section.

##### el before stressed a-/ha- feminine singular nouns (p.11)

A feminine singular noun beginning with a stressed a- or ha- sound takes el instead of la purely to
avoid two "a" sounds colliding (el agua, el hacha) — "la sounds wrong before the 'a' sound." The
underlying noun is still grammatically feminine (adjectives agreeing with it stay feminine: *el agua
clara*), and if an adjective is inserted before the noun, la returns (la misma agua, la mejor hacha)
since the two a-sounds no longer touch. The same rule and the same trigger-and-reversal logic applies
to the indefinite article (un ave, p.15).

##### Definite article used in Spanish but not in English: consolidated rule set (p.12–14)

A systematic list of eight contexts where Spanish requires an article that English omits: (1)
general statements about people/animals/things (Me gustan los animales — "I like animals"); (2)
abstract qualities (El tiempo es oro); (3) colors (El azul es mi color favorito); (4) parts of the
body, where Spanish uses the article + reflexive/object pronoun instead of a possessive (Tiene los
ojos verdes — "He's got green eyes," not "his green eyes" — cross-referenced to Personal pronouns at
p.42); (5) someone's title when talking *about* rather than *to* them (El doctor Vidal no está); (6)
institutions like school/university/church/hospital/prison (en el colegio, en la cárcel); (7) meals,
games, sports (La cena es a las nueve, Me gusta el tenis); (8) days of the week/dates where English
uses "on" (Te veo el lunes) and telling the time (Es la una, Son las tres). A separate note flags
that the article is conversely *absent* in certain fixed phrases built from tener + noun or after
certain prepositions (tener hambre, sin duda, con cuidado).

##### Indefinite article un/una/unos/unas — *basic paradigm previously covered, kept: usage exceptions*

Basic un/una/unos/unas-by-gender paradigm is standard content. Kept: the indefinite article is NOT
used in Spanish for stating someone's job/profession (Es profesor — "He's a teacher") unless the noun
is qualified by an adjective (Es un buen médico); NOT used after tener/buscar/llevar(puesto) when
referring to one of a class of thing you're only likely to have/seek/wear one of (No tengo coche,
¿Llevaba sombrero?); NOT used with otro, cierto, cien, mil, sin, qué (otro libro, mil años, ¡Qué
sorpresa!); but conversely IS used (unlike English) when an abstract noun like inteligencia or tiempo
is modified by an adjective (Posee una gran inteligencia).

##### The article *lo* (p.17–18)

Unlike every other Spanish article, *lo* is never used directly with a noun. Two distinct functions:
(1) lo + a masculine singular adjective or past participle forms an abstract noun (lo único, lo
importante, lo bueno, lo ocurrido — "what happened"); (2) lo que means "what" in the sense of "that
which" (Vi lo que pasó). A related but separate construction, lo + adjective/adverb + que, intensifies
("how small/nice/much" — No sabíamos lo pequeña que era la casa). lo de + a noun phrase refers back to
a shared topic both speaker and listener already know about (Lo de tu hermano me preocupa mucho). lo
also appears in several fixed idiomatic phrases: a lo mejor (maybe), por lo menos (at least), por lo
general (generally).

---

#### Chapter: Adjectives (pp.19–40)

##### Basic agreement and word order — *previously covered, not re-extracted in full*

The core rule (Spanish adjectives usually agree for gender/number and usually follow rather than
precede the noun, unlike English) is standard beginner content covered in 005 and elsewhere.

##### Feminine-formation exceptions beyond -o→-a (p.20–21)

Beyond the basic -o→-a rule: adjectives ending in any vowel other than -o, or in an accented vowel,
don't change for the feminine (el vestido verde/la blusa verde; un médico iraquí/una familia iraquí).
Adjectives ending in a consonant normally don't change either, EXCEPT: (1) nationality/place
adjectives ending in a consonant add -a, dropping any accent on the final vowel in the process (un
periódico inglés→una revista inglesa) — and the book notes these don't capitalize in Spanish, unlike
English; (2) adjectives ending in -or change to -ora (un niño encantador→una niña encantadora), except
a short closed list of comparative-derived -or adjectives (mejor, peor, mayor, menor, superior,
inferior, exterior, posterior) which stay invariable; (3) adjectives ending in -án/-ón/-ín change to
-ana/-ona/-ina without an accent (un gesto burlón→una sonrisa burlona).

##### Plural adjective formation and spelling changes (p.21–22)

Standard -s/-es-by-ending-type rule, plus: an accent on the FINAL syllable of a consonant-ending
singular adjective is lost in the plural (un chico muy hablador→unos chicos muy habladores); an
accented-vowel-ending adjective instead *gains* -es (un médico iraní→unos médicos iraníes); -z changes
to -ces (feliz→felices, mirroring the noun rule). A mixed-gender group of nouns takes the masculine
plural adjective form by default (El pan y la fruta son baratos).

##### Invariable adjectives (p.22)

A small class of adjectives — usually multi-word (azul marino) or derived from a noun (naranja,
"orange") — never change for gender or number at all.

##### Short (apocopated) adjective forms (p.22–23)

Seven adjectives drop their final -o before a masculine singular noun only: bueno→buen, malo→mal,
alguno→algún, ninguno→ningún, uno→un, primero→primer, tercero→tercer (algún and ningún additionally
gain a written accent). grande shortens to gran before ANY singular noun regardless of gender, with a
meaning shift (gran = "great," grande after the noun = "big," per the position-meaning table below).
ciento shortens to cien before all plural nouns and before mil/millones specifically, but stays
ciento before any other number word (ciento tres). cualquiera drops its final -a before any noun
(cualquier día) regardless of gender.

##### Word order with adjectives: the categories that precede the noun (p.24)

While most descriptive adjectives follow the noun, several whole *categories* of Spanish adjective
instead go before it as a rule: demonstrative adjectives (este sombrero), possessive adjectives (mi
padre), numbers (tres días), interrogative adjectives (¿qué hombre?), adjectives in exclamations
(¡qué lástima!), indefinite adjectives (cada día), and the shortened forms above (mal tiempo). When
two or more descriptive adjectives follow a noun together, y ("and") joins the last two (un hombre
alto y delgado).

##### Position-dependent meaning-shift adjectives (p.25)

A closed set of eight adjectives change their actual meaning depending on whether they're placed
before or after the noun, tabulated systematically in the source: antiguo (before=former, after=old/
ancient), diferente (before=various, after=different), grande (before=great, after=big), medio
(before=half, after=average), mismo (before=self/very/precisely, after=same), nuevo (before=new to
the owner, after=brand new), pobre (before=wretched, after=not rich), viejo (before=long-standing,
after=aged/elderly). This is presented as a discrete, closed phenomenon distinct from the simple
"most adjectives go after" rule.

##### Comparatives and superlatives (p.26–29) — *basic más/menos...que previously covered, kept:
irregular/absolute-superlative layer*

más/menos + adjective + que is standard beginner content. Collins adds: a true superlative uses
el/la/los/las (+noun) + más/menos + adjective, with de (not in) translating "in" after a superlative
(el hombre más alto del mundo); tan...como for "as...as" with adjectives, but tanto...como (agreeing
for gender/number) when the compared quantity is a noun rather than an adjective (Pablo tiene tanto
miedo como yo); irregular comparative/superlative pairs bueno/mejor, malo/peor, grande/mayor,
pequeño/menor, which don't change for gender (but do pluralize: mejores, peores); a distinct
*absolute* superlative formed with -ísimo (not a true comparison, just intensification — delgado→
delgadísimo), which requires dropping any existing vowel/accent first (fácil→facilísimo, rápido→
rapidísimo) and triggers spelling changes to preserve consonant sound (rico→riquísimo, feroz→
ferocísimo). más grande/más pequeño are flagged as used mainly for literal physical size, while mayor/
menor are used mainly for age — a usage-register distinction not reducible to the raw
bigger/smaller-vs-older/younger glosses.

##### Demonstrative adjectives: este/ese/aquel (p.30–31) — *basic three-way paradigm previously
covered, kept: the ese-vs-aquel usage rule and the date-related Grammar Extra*

The basic este/ese/aquel three-way proximity paradigm (near speaker / near listener / far from both)
is standard content found in multiple basic grammars. Kept as a genuine nuance: a dedicated Grammar
Extra specifies that ese/esa/esos/esas should be used when referring to a *definite* date, month, or
year (¿1999? No me acuerdo de dónde pasamos las vacaciones ese año), while aquel/aquella/aquellos/
aquellas is used for something in the past without a definite date attached (aquellas vacaciones que
pasamos en Francia) — a temporal-definiteness rule layered on top of the physical-distance rule.

##### Interrogative adjectives: qué and cuánto (p.32–33)

¿qué? (which/what) is invariable for gender and number. ¿cuánto?/¿cuánta?/¿cuántos?/¿cuántas? (how
much/how many) agrees with the noun — including a specific note that gente ("people"), though it
refers to a plural concept, is grammatically feminine singular and so takes cuánta (¿Cuánta gente ha
venido?). A separate Grammar Extra notes qué and cuánto/cuánta/cuántos/cuántas are also used to report
indirect/embedded questions (Dime qué hora es — "Tell me what time it is"; No sé qué vestido escoger).

##### Adjectives used in exclamations: ¡qué...! (p.34)

¡qué...! corresponds to "What a...!" (¡Qué lástima! "What a pity!"). It can combine with tan or más
before the adjective to mean "What a (very)...!" (¡Qué día tan bonito!). ¡cuánto/cuánta/cuántos/
cuántas...! separately means "What a lot of...!" (¡Cuánto dinero! "What a lot of money!").

##### Possessive adjectives: two parallel systems (p.35–38)

Spanish has two distinct possessive-adjective sets. The **short form** (mi/tu/su/nuestro/vuestro/su)
precedes the noun, as in English, and agrees with the thing owned, not the owner — explicitly flagged
with a cross-reference to "Ways of saying 'you'" (p.44) since the choice of tu vs. su directly encodes
the tú/usted address register of the person being spoken to, and su/sus is genuinely ambiguous (his/
her/its/your/their) — disambiguated where needed with de él/de ella/de usted/de ellos/de ellas/de
ustedes rather than su. Possessive adjectives are NOT normally used with parts of the body or clothing
(the definite article is used instead — cross-referenced to the article rule above). The **long form**
(mío/tuyo/suyo/nuestro/vuestro/suyo) instead goes AFTER the noun and translates "(of) mine," "(of)
yours," etc. (un amigo mío, "a friend of mine"); it also appears in exclamations and forms of address,
where it simply means "my" (¡Dios mío! "My God!"; Muy señor mío, "Dear Sir").

##### Indefinite adjectives (p.39–40)

Unlike English, most Spanish indefinite adjectives (algún/alguna, cada, mismo, mucho, otro, poco,
tanto, todo, varios) change for gender/number and always precede the noun. otro is explicitly flagged
as never combinable with un/una (¿Me das otra manzana? not "una otra"). todo/toda/todos/todas can be
followed by a definite article, a demonstrative adjective, a possessive adjective, or a place name
(Lo sabe todo Madrid, "The whole of Madrid knows it").

---

#### Chapter: Pronouns (pp.41–67)

##### Personal pronouns: subject — paradigm and usage restriction (p.42–43)

Full subject-pronoun table given (yo/tú/él/ella/usted — nosotros/nosotras/vosotros/vosotras/ellos/
ellas/ustedes). Key structural point: unlike English, Spanish normally *omits* subject pronouns
entirely, since the verb ending alone identifies the subject (hablo español can only mean "I speak
Spanish"). Subject pronouns are used only for emphasis, for contrast/clarity, after ser ("Soy yo" —
"It's me"), in comparisons after que/como, standing alone without a verb to answer a question, and
after certain prepositions. usted/ustedes are the exception — they're routinely included even though
not strictly needed, as a politeness marker. It (as subject) and "they" referring to things are NEVER
translated into Spanish at all (¿Qué es? — Es una sorpresa, "What is it? — It's a surprise").

##### "Ways of saying 'you'" in Spanish — full synthesis (p.44–45)

This is the book's own dedicated named subsection, cross-referenced from five separate chapters
(possessive adjectives p.35/37, subject pronouns p.42, possessive pronouns p.56). The choice of
"you"-word depends on two independent axes: (1) one person vs. more than one, and (2) familiar
relationship (friend/young person/relative) vs. unfamiliar/formal (teacher, boss, stranger). This
yields: **tú** — one person, familiar. **usted** — one person, formal/unfamiliar. **vosotros/
vosotras** — more than one person, familiar, *used in Spain*; **ustedes** is used *instead*, for the
same familiar-plural meaning, in Latin America. **ustedes** — more than one person, formal/unfamiliar
(everywhere). Adjectives describing tú/usted take the gender of the person addressed; adjectives
describing ustedes are feminine plural only if addressing women/girls exclusively. For plural
subject-pronoun gender selection specifically: nosotros/vosotros/ellos (and masculine ustedes-forms
of agreement) are used for male-only groups AND for mixed-gender groups; nosotras/vosotras/ellas only
for female-only groups. (The core vosotros-vs-ustedes regional split itself was flagged as previously
covered by 015/016; this entry captures the fuller cross-chapter address-selection logic layered
around it, which was not confirmed present elsewhere.)

##### Personal pronouns: direct object (p.46–48)

Full DO pronoun table (me/te/lo/la — nos/os/los/las). DO pronouns normally precede the conjugated
verb (¿Lo has visto?) but join onto the end of the verb, forming one word, in affirmative commands
(Ayúdame — "Help me"; not in negative commands: No los toques). With an infinitive or gerund following
another verb, the pronoun can either attach to the end of the infinitive/gerund or move before the
first verb (Vienen a vernos / Nos vienen a ver) — either is correct; a written accent is often needed
to preserve the original stress when a pronoun is appended. DO pronouns cannot stand alone without a
verb or after a preposition like a/de (use the prepositional-pronoun set instead, p.54).

##### Personal pronouns: indirect object (p.49–51)

Full IO pronoun table (me/te/le — nos/os/les). The book gives an explicit diagnostic for
distinguishing direct from indirect objects using English "what/who...to/for" questions (He gave me a
book → "who did he give the book to?" → me = indirect; "what did he give me?" → a book = direct). IO
pronouns replace a + noun (Estoy escribiendo a Teresa → Le estoy escribiendo) and are required even
when the noun object is ALSO stated, if the noun comes before the verb (A tu hermano lo conozco bien,
literally "Your brother I know him well"). Same word-order and attachment rules as DO pronouns apply.

##### Order of object pronouns and the se substitution (p.52–53)

When both an indirect and a direct object pronoun appear together, indirect always precedes direct
(Ana os lo mandará mañana). Critically, le/les must be replaced by se whenever immediately followed by
lo/la/los/las, to avoid *le lo*: Se lo di ayer ("I gave it to him/her/you/them yesterday") — the
resulting se is genuinely ambiguous as to referent, disambiguated if needed with a él/a ella/a usted/
a ellos/etc.

##### Prescriptive note on Spanish leísmo (p.53) — supplement to 015/016's descriptive leísmo
coverage

The book explicitly flags, as a usage note rather than a rule: "in Spain, you will often hear le and
les used instead of lo and los as direct object pronouns when referring to men and boys. It is
probably better not to copy this practice since it is considered incorrect in some varieties of
Spanish, particularly Latin American ones." This is a value judgment/learner-advice framing (describing
the phenomenon as something to specifically *avoid* reproducing) distinct from 015's and 016's more
neutral, descriptive treatment of the same leísmo phenomenon.

##### Further notes on object pronouns (p.53)

When a noun object stands before the verb, the corresponding pronoun must still be used too (A María
la vemos algunas veces — "We sometimes see María," literally "María we see her sometimes"). Indirect
object pronouns are often used together with the definite article (rather than a possessive adjective)
to indicate whose body part or clothing item is affected (La chaqueta le estaba ancha — "His jacket
was too loose"; Me duele el tobillo — "My ankle's sore") — this ties back to the definite-article rule
above (p.13) and shows the same body-part convention expressed through the pronoun side of the
grammar.

##### Pronouns after prepositions (p.54–55)

A dedicated pronoun set is used after most prepositions, identical to the subject-pronoun set except
for three special forms: mí (me), ti (you), and sí (himself/herself/yourself/themselves) — each
carries a written accent to distinguish it from a same-spelled different word (mí vs. mi "my"; sí vs.
si "if"; a separate note that tú itself needs no distinguishing accent here since there's no clash).
con fuses with these three to form single words: conmigo, contigo, consigo. A closed list of five
prepositions — entre, hasta, menos, salvo, según — are an explicit EXCEPTION: they take the ordinary
subject pronouns yo/tú rather than mí/ti (entre tú y yo, "between you and me"; todos menos yo,
"everybody except me").

##### Possessive pronouns (p.56–57)

Full paradigm (el mío/la mía/los míos/las mías, etc. — "mine," "yours," and so on) tabulated by
gender/number of the *thing owned*, cross-referenced again to "Ways of saying you." A specific Tip
notes el suyo (and its forms) is genuinely ambiguous — it can mean his/hers/yours/theirs — and is
"only used to replace a masculine singular noun" in that ambiguous sense; el/la/los/las + de + usted/
ustedes/ellos/ellas/a name is used instead for clarity (mi libro y el de usted, "my book and yours").

##### Indefinite pronouns (p.58–60)

A closed set of indefinite pronouns, each tabulated with example usage: algo, alguien, alguno/alguna/
algunos/algunas, cada uno/cada una, cualquiera, mucho/mucha/muchos/muchas, nada, nadie, ninguno/
ninguna, otro/otra/otros/otras, poco/poca/pocos/pocas, tanto/tanta/tantos/tantas, todo/toda/todos/
todas, uno...el otro/una...la otra, unos...los otros/unas...las otras, varios/varias. Usage rule:
algo, alguien, and alguno can NEVER be used together with a negative like no — nada, nadie, and
ninguno must be used instead in a negative sentence, and if nada/nadie/ninguno comes *before* the verb,
no must NOT also be used (Nada lo asusta — not "No nada lo asusta"), whereas if they come after the
verb, no IS required (No veo a nadie). alguien, nadie, and alguno/ninguno (when referring to people)
take the personal a as object of a verb (¿Viste a alguien?).

##### Relative pronouns (p.61–64)

que serves as the universal relative pronoun for both people and things (el hombre que vino ayer; la
novela que ganó el premio) and — unlike English "that," which is routinely dropped — can NEVER be
omitted in Spanish. When a relative pronoun is the object of a preposition, que alone cannot be used;
instead, for people, el que/la que/los que/las que or quien/quienes (el que agrees for gender and
number, quien only for number); for things, el que/la que/los que/las que specifically (not quien). de
+ el que fuses to del que; a + el que fuses to al que — mirroring the article contractions. A more
formal/literary register alternative, el cual/la cual/los cuales/las cuales, is explicitly flagged as
something "you may come across in your reading" as an alternative to el que after a preposition.
cuyo/cuya/cuyos/cuyas ("whose") is grammatically an adjective, not a pronoun, and — critically — agrees
with the noun it describes (the thing possessed), NOT with the possessor, exactly paralleling the
logic already established for possessive adjectives (la mujer, cuyo hijo..., "the woman whose son...").
lo que is the neuter relative referring to an entire preceding clause rather than a specific noun (Vi
lo que pasó). Prepositions can NEVER be stranded at the end of a Spanish clause the way English allows
("the man she was talking to" must become el hombre con el que/con quien estaba hablando).

##### Interrogative pronouns (p.65–67)

¿qué? = "what?"; ¿cuál?/¿cuáles? = "which (one/s)?," used specifically when choosing among two or
more things, and explicitly flagged as never placed directly before a noun (use qué instead: ¿Qué
libro...? not ¿Cuál libro...?). A further usage distinction: ¿qué es...?/¿qué son...? is used
specifically when asking someone to define, explain, or classify something (¿Qué son los genes? —
"What are genes?"), while ¿cuál es...?/¿cuáles son...? is used when asking for one particular detail,
number, or name among known options (¿Cuál es la capital de España?). ¿quién?/¿quiénes? = "who?" as
subject or after a preposition; ¿a quién?/¿a quiénes? = "who(m)?" as direct object; ¿de quién?/¿de
quiénes? = "whose?". ¿cuánto?/¿cuánta?/¿cuántos?/¿cuántas? = "how much?/how many?".

##### Demonstrative pronouns (p.66–67)

Paradigm: éste/ésta/esto (this one), ése/ésa/eso (that one, near), aquél/aquélla/aquello (that one,
further away) — plural éstos/éstas, ésos/ésas, aquéllos/aquéllas. In this 2004 edition, the pronoun
forms are printed *with* a written accent to distinguish them from the otherwise-identical
demonstrative *adjective* forms (este/ese/aquel, no accent) — a now-obsolete convention the RAE
dropped in its 2010 orthography reform; flagged here as an edition-dated spelling fact rather than a
live grammar rule, relevant for Attested Era purposes. Usage mirrors the demonstrative adjectives:
ése/ésa and so on for things/people not far from the listener, aquél/aquélla for things further away.
Neuter forms esto/eso/aquello refer to an idea or an unidentified thing rather than a specific named
noun. (Coverage of this chunk ends here, at printed p.67, immediately before the Verbs chapter opens
at p.69.)

---


---

## Spanish — Established Vocabulary/Grammar: Collins Easy Learning Spanish Grammar, "Verbs" chapter (full chapter — present/imperative/reflexive/future/conditional/preterite/imperfect/perfect/pluperfect/passive/gerund/impersonal/subjunctive/infinitive)

**Source:** Collins, *Easy Learning Spanish Grammar*, 1st Edition (HarperCollins, 2004), PDF pages
42–82 of the scanned file, which (see note below) correspond to **printed pages 68–149** — the entire
"Verbs" chapter plus the tail end of the preceding "Pronouns" chapter (demonstrative pronouns, printed
pp. 68–69) and the start of "The Infinitive" section (printed pp. 144–149).

### Coverage note — chunking, text-layer, and non-redundant-supplement scoping

**Page-range correction (two-page-spread gotcha, confirmed per the extraction spec's documented
pattern):** this PDF is scanned as **one spread (two printed pages) per PDF page**, not one-to-one.
Verified empirically by rendering PDF pages 42–43 at 150dpi: each image is ~1530×1158px at 150dpi,
almost exactly double the single-page dimension implied by `pdfinfo`'s 365.76×555.84pt page size
(762×1158px expected for one page). Printed page numbers visible in the rendered images confirm the
formula `printed_left_page = 2×PDF_page − 16` (PDF 42 → printed 68; PDF 82 → printed 148) holds
consistently across the whole assigned range — spot-checked at PDF pages 42, 43, 50, 60, 70, 80, 82, all
matching exactly. My assigned "PDF pages 42–82" therefore cover **printed pages 68–149**, i.e. the
entire Verbs chapter, not a partial slice.

**Text layer is unusable — vision-read throughout, as warned in the dispatch.** `pdftotext` output is
badly character-corrupted (e.g. "Pronouns"→"Pnoruourus", "Verbs"→"Vrnes"/"Venes"/"VEnBs" inconsistently
across the same chapter, "número"-type words scrambled) — confirmed consistent with the dispatch's
warning. I used `pdftotext -f 42 -l 82 ... | grep` only as a rough section-boundary/keyword locator (to
confirm chapter structure: present tenses → ser/estar → imperative → reflexive verbs → future →
conditional → preterite → imperfect → perfect → pluperfect → passive → gerund → impersonal verbs →
subjunctive → infinitive), never as a source of actual vocabulary or grammar-point text. All actual
content below was vision-read from `pdftoppm -r 150` renders of all 41 two-page spreads (PDF pp. 42–82).
**No handwritten marginalia was found on any rendered page** — every page viewed showed clean, consistent
printed typeface matching the rest of the book; nothing excluded on marginalia grounds.

**Non-redundant-supplement scoping — this chapter is almost entirely redundant with prior Spanish
`established/` files, confirmed by direct comparison, not assumption.** Spanish already has
`007_practice_makes_perfect_spanish_irregular_verbs.md` (full irregular-verb morphology, principal-parts
method) and `008_/008b_/008c_practice_makes_perfect_spanish_verb_tenses.md` (a 3-part, ~2000-line series
that is itself a dedicated full-book verb-tense reference — present, past tenses, future, conditional,
perfect tenses, imperative, subjunctive, passive, plus two appendices). I read `008c`'s own "Grammar
points" subsections for the imperative, present subjunctive, and imperfect subjunctive in full (not just
skimmed) before extracting, and spot-checked `008c` Appendix B (the ~150-entry verb+preposition
governance table) against Collins' own "verb followed by preposition + infinitive" tables. Every grammar
point in my range — present simple (regular -ar/-er/-ir, stem-changing, common irregulars), ser/estar,
present continuous, the imperative (regular + irregular, all persons, pronoun placement/RID rule), common
reflexive verbs, the future/conditional (regular + irregular stems), the preterite (regular, irregular,
spelling-change -car/-gar/-zar verbs, i→y verbs), the imperfect (regular + the 3 irregulars ser/ir/ver),
the perfect/pluperfect (formation + irregular past participles), the passive (formation + ways of
avoiding it), the gerund (formation, irregular forms, uses), the present/imperfect subjunctive (formation,
irregular stems, the full "8 triggering categories" logic, tenses-with-subjunctive sequencing, aunque/
cuando/hasta que mood-switching) — **was confirmed already present, at equal or greater depth, in
007/008/008b/008c and is not re-extracted here.** `008c`'s imperative section in particular already
states the same "only 8 tú-irregulars" fact Collins presents as a full table, and its 8-category
subjunctive-trigger taxonomy is more systematic than Collins' own looser bullet-list presentation — so
Collins adds no deeper paradigm here, unlike some other non-redundant-supplement chunks in this project.

**What WAS kept, because it is genuinely new relative to 007/008/008b/008c/014/015 (checked via targeted
grep against those files before inclusion, not assumed):**
1. A set of **ser/estar idiomatic set phrases** (printed p. 82) not found via grep in any prior
   established file: `estar de pie/vacaciones/viaje/moda`, `estar claro`, `es igual`/`es lo mismo`,
   `es para ti`.
2. An **explicit European-Spanish-only usage permission**: "In European Spanish you CAN use the
   perfect/pluperfect tense in the negative with `desde`/`desde hace`/`desde hacía`" (printed pp.
   118, 121) — stated as a genuine regional exception to the book's own general rule (elsewhere stated
   flatly as "don't use the perfect/pluperfect with desde... use the present/imperfect instead"). This
   is exactly the kind of explicit dialectal annotation the extraction spec flags as high-priority.
3. A **contrastive typological note** on the passive (printed p. 124): "In Spanish, an indirect object
   can NEVER become the subject of a passive verb" — contrasted explicitly with English, which allows
   both objects of a ditransitive verb (`gave me a book`) to become a passive subject (`I was given a
   book` / `A book was given to me`). Spanish only allows the latter.
4. Five **verb+preposition/infinitive governance entries not present** in `008c`'s ~150-entry Appendix B
   table (checked line-by-line against that table's `a`/`con`/`de`/`en`/`para`/`por` groups): `probar a
   hacer algo`, `amenazar con hacer algo`, `tener ganas de hacer algo`, plus two idiomatic
   verb+infinitive/noun set-phrases not structured as governance patterns at all: `querer decir`, `dejar
   caer`.
5. Three **movement-verb + gerund idiom patterns** (`salir corriendo`, `entrar corriendo`, `irse
   cojeando` type constructions) and the **llevar/pasar(se) + time expression + gerund** duration
   constructions (printed pp. 126–127) — not found via grep in prior files.
6. The **"seguir/continuar haciendo algo"** (to go on/continue doing something) gerund-complement
   pattern (printed p. 125).

Everything else in the printed-page-68–149 range is explicitly marked "previously covered, not
re-extracted" rather than silently omitted — see the Grammar points section below for the full,
auditable per-topic list.

---

### Vocabulary

Column defaults for every row below: **Attested Era** = "contemporary (source published 2004)";
**Geographic Scope** = `national` where Attested Region is filled in, else `—`; **Source Type** =
`grammar_reference`; **Transcription Confidence** = `n/a`; **Vision Reading Confidence** = `verified`
unless noted otherwise (all entries below were read from clearly legible, high-contrast printed text at
150dpi with no scan artifacts in the relevant area).

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| estar de pie | to be standing | verb phrase (ser/estar idiom) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | p. 82. Ex.: *Juan está de pie* "Juan is standing." |
| estar de vacaciones | to be on holiday | verb phrase (ser/estar idiom) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | p. 82. |
| estar de viaje | to be on a trip | verb phrase (ser/estar idiom) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | p. 82. |
| estar de moda | to be in fashion | verb phrase (ser/estar idiom) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | p. 83. Ex.: *Las pantallas de plasma están de moda* "Plasma screens are in fashion." |
| estar claro | to be obvious | verb phrase (ser/estar idiom) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | p. 83. Ex.: *Está claro que no entiendes* "It's obvious that you don't understand." |
| es igual / es lo mismo | it's all the same | verb phrase (ser idiom) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | p. 82. Presented as interchangeable set phrases. |
| es para ti | it's for you | verb phrase (ser idiom) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | p. 82. |
| probar a hacer algo | to try to do something | verb + a + infinitive | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | p. 148. Governance pattern not in `008c`'s Appendix B "a" group (which has llegar a "manage to" but not probar a). |
| amenazar con hacer algo | to threaten to do something | verb + con + infinitive | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | p. 149. Ex.: *Amenazó con denunciarlos* "He threatened to report them." Not in `008c`'s Appendix B "con" group. |
| tener ganas de hacer algo | to want to do something | verb + de + infinitive (idiom) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | p. 149. Not in `008c`'s Appendix B "de" group. |
| querer decir | to mean | idiomatic verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | p. 147. Ex.: *¿Qué quiere decir eso?* "What does that mean?" |
| dejar caer | to drop | idiomatic verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | p. 147. Ex.: *Dejó caer la bandeja* "She dropped the tray." |
| seguir haciendo algo | to go on doing something, to keep doing something | verb + gerund (periphrasis) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | p. 125. Interchangeable with continuar haciendo algo per the source. |
| continuar haciendo algo | to continue doing something | verb + gerund (periphrasis) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | p. 125. Ex.: *Siguió cantando* / *Continuó cantando* "He went on singing." |
| llevar + time expression + gerund | to have been doing something (for a stated duration) | periphrastic construction | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | p. 126. Ex.: *Lleva dos años estudiando inglés* "He's been studying English for two years." Equivalent in meaning to English have/has been + -ing. |
| pasar(se) + time expression + gerund | to spend time doing something | periphrastic construction | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | p. 126. Ex.: *Pasé/Me pasé el fin de semana estudiando* "I spent the weekend studying." |
| salir corriendo / entrar corriendo / irse cojeando (pattern: movement verb + gerund) | to run out / to run in / to limp off (motion-manner gerund pattern) | verb + gerund (manner-of-motion construction) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | p. 126. Verbs of movement (salir, entrar, irse) + a manner gerund (corriendo "running," cojeando "limping") — the English equivalent restructures as "to run out/in," "to limp off," not a literal gerund translation. |

### Grammar points

#### European-Spanish-only permission: perfect/pluperfect + negative desde

The book's general rule (stated twice, for the perfect on p. 114/118 and the pluperfect on p. 119/121)
is: don't use the perfect tense with `desde`, `desde hace`, `hace ... que`; use the present tense instead
(and symmetrically, don't use the pluperfect with `desde`/`desde hacía`/`hacía ... que`; use the
imperfect instead) — e.g. *Está enfermo desde julio* "He has been ill since July" uses present tense, not
perfect. **However, both pages carry an explicit exception**: "In European Spanish you CAN use the
perfect tense in the negative with `desde` and `desde hace`" — e.g. *No lo he visto desde hace mucho
tiempo* "I haven't seen him for a long time" — and the identical exception for the pluperfect negative
with `desde`/`desde hacía` (p. 121). This is presented as a genuinely regional (Peninsular Spanish)
permission, not available in the book's general-case Latin American-unmarked default rule.

#### Passive voice: indirect objects cannot become passive subjects (contrastive note)

Collins' "Avoiding the passive" discussion (p. 124) includes an explicit English/Spanish contrast: in
English, a ditransitive sentence like *He gave me a book* lets either object become the subject of a
passive (*I was given a book* OR *A book was given to me*). **In Spanish, an indirect object can NEVER
become the subject of a passive verb** — only the direct-object-promotion pattern (*A book was given to
me* equivalent) is grammatical. This is framed as a reason Spanish leans more heavily than English on its
three passive-avoidance strategies (active 3rd-person-plural, reflexive `se` construction, impersonal
`se`), which are themselves already covered in `008c`'s passive-voice chapter.

#### Everything else in this range: previously covered, not re-extracted

Per-topic redundancy decisions, auditable against `007_practice_makes_perfect_spanish_irregular_verbs.md`
and `008_/008b_/008c_practice_makes_perfect_spanish_verb_tenses.md` (the latter checked directly, section
by section, during this extraction — not assumed):

- **Demonstrative pronouns** (tail of the Pronouns chapter, pp. 68–69): éste/ésta/éstos/éstas, ése/ésa/
  ésos/ésas, aquél/aquélla/aquéllos/aquéllas, neuter esto/eso/aquello — general grammar topic, not
  verb-specific, out of scope for this verb-chapter chunk; not extracted here (belongs to a Pronouns
  chunk, not this one).
- **Present simple of regular -ar/-er/-ir verbs** (pp. 70–77): identical formation rules and endings to
  `008` Ch. 1 (present simple regular conjugation); same model verbs (hablar/comer/vivir).
- **Stem-changing verbs** (pp. 74–76: encontrar, recordar, poder, dormir, cerrar, pensar, entender,
  perder, preferir, pedir, servir): same o→ue/e→ie/e→i patterns as `008` Ch. 8 (Stem-changing verbs);
  same example verbs, all already present as core vocabulary across 007/008/009.
- **tener, hacer, ir present tense; common irregular verbs** (pp. 77–79): matches `008` Ch. 4 (Tener)
  and Ch. 6 (Common irregular verbs) and `007`'s principal-parts entries for the same verbs.
- **ser vs. estar** (pp. 80–83, excluding the idiom list captured above): matches `008` Ch. 2 exactly —
  permanent vs. temporary-quality distinction, the same worked examples structure (joven/delgado/
  cansado/aburrido pairs).
- **Present continuous** (p. 84): matches `008` Ch. 12 exactly (estar + gerund formation).
- **The imperative** (pp. 85–99, regular forms, the 8 tú-irregulars, usted/vosotros/nosotros forms,
  object-pronoun placement): `008c`'s "The imperative (Ch. 19)" section already states the identical "8
  tú-irregulars" fact (di/no digas, haz/no hagas, ve/no vayas, pon/no pongas, sal/no salgas, sé/no seas,
  ten/no tengas, ven/no vengas) plus the RID object-pronoun-ordering rule and the vosotros-is-Spain-only /
  ustedes-is-pan-American-formal-and-informal notes — equal or greater systematicity than Collins' own
  spelled-out tables, so not re-tabulated.
- **Common reflexive verbs and reflexive-verb formation** (pp. 90–97: acostarse, afeitarse, bañarse,
  dormirse, ducharse, enfadarse, lavarse, levantarse, llamarse, secarse, sentarse, vestirse, plus
  position-of-pronoun rules): confirmed via grep already present in 6+ established files (004/004b/005/
  008/008c/010b/014/029).
- **Future tense** (regular formation + irregular stems, pp. 100–103) and **conditional** (pp. 104–105,
  shares the future's irregular stems): matches `008` Ch. 15 and Ch. 16 (same irregular-stem verb set:
  the standard caber/decir/haber/hacer/poder/poner/querer/saber/salir/tener/valer/venir list).
- **Preterite** (regular, pp. 106–107; irregular — caer/construir/leer accent-and-y pattern, p. 108;
  -zar/-gar/-car spelling changes — cruzar/empezar/pagar/sacar, p. 109; reflexive preterite, p. 109):
  matches `008b` Ch. 13 (The preterite tense) at equal depth.
- **Imperfect** (regular + the 3 irregulars ser/ir/ver, pp. 110–114): matches `008b` Ch. 14 (The
  imperfect tense) exactly, including the same 3-irregular-verb list.
- **Perfect tense** (formation, irregular past participles — abrir/cubrir/decir/escribir/freír/hacer/
  morir/oír/poner/romper/ver/volver, reflexive perfect, pp. 115–117) and **pluperfect** (pp. 118–121,
  minus the European-Spanish exception captured above): matches `008c` Ch. 17/18 and `008c`'s passive
  Ch. 26 cross-references; the irregular past-participle list is the standard set already present in
  `007`'s principal-parts data (6th form = past/passive participle).
- **Impersonal verbs** (pp. 128–133: llover/nevar weather verbs; hacer frío/calor/sol/viento; hacer
  falta; hay/había/hubo; ser + de día/de noche; basta con; (me) parece que; vale la pena; se cree/dice/
  puede/trata de): checked via grep — `hace falta`, `hay que`, `vale la pena`, and `basta con` already
  appear in established files 001/004b/011h/017/025/035/035e/035g; not re-extracted.
- **Present subjunctive** (formation, irregular stems — dar/estar/haber/ir/saber/ser, stem-changing -ir
  verbs in nosotros/vosotros, pp. 136–139) and **imperfect subjunctive** (formation via 3rd-plural
  preterite minus -ron, -ra/-se alternation, pp. 141–143): matches `008c` Ch. 20/21 at equal or greater
  systematicity — `008c`'s 8-category trigger taxonomy (desire/doubt/emotion/impersonal-opinion/
  pending-action/indefinite-antecedent/quizá/aunque) is a more organized presentation of the same set of
  "when to use the subjunctive" cases Collins covers as a looser bullet list across pp. 134–140.
- **si + present indicative vs. imperfect subjunctive** (p. 143): matches `008c`'s "hypothetical vs.
  information-seeking si-clause" distinction exactly.
- **Infinitive uses and verb+infinitive linking** (pp. 144–149, excluding the governance entries captured
  above): the no-preposition category (poder/saber/querer/deber + infinitive; gustar/encantar/apetecer
  + infinitive; ver/oír + infinitive; hacer/dejar + infinitive) uses verbs that are already extensively
  covered as core vocabulary throughout 007/008/009/010–013; the `a`/`de`/`con`/`en` governance tables
  overlap 90%+ with `008c` Appendix B's ~150-entry table (same verbs: aprender a, comenzar/empezar a,
  decidirse a, llegar a, volver a, ayudar/enseñar/invitar a alguien a, aburrirse/acabar/acordarse/
  alegrarse/dejar de, soñar con, quedar en) — only the five genuinely-missing entries above were kept.

---


---

## Spanish — Established Vocabulary/Grammar: Collins Easy Learning Spanish Grammar, pp. 150-219 (Verbs+Prepositions through Verb Tables Appendix A-C)

**Source:** Collins, *Easy Learning Spanish Grammar* (HarperCollins, 1st edition, 2004). PDF pages
83-123 (163-page scan), corresponding to the book's own printed pages 150-211 for the main grammar
text, plus printed pages 2-15 of the book's separately-numbered **Verb Tables** appendix (PDF pages
117-123; the appendix restarts its own page numbering at 1, it does not continue the main text's
150-211 sequence).

**Vision-reading note.** This PDF reports a text layer, but `pdftotext` output is heavily corrupted
character-level OCR garbage (e.g. "Venes" for "Verbos", accented vowels rendered as stray digits) —
confirmed consistent with the dispatch's warning. However, the underlying 150dpi page **images**
themselves are a clean, sharp, modern commercial typeset scan with no legibility problems at all —
every page read below was fully legible on direct inspection, with internal cross-checks (the same
particle/word recurring across different sections, e.g. "no" and "nunca" appearing consistently in
both the Negatives chapter and the later common-adverbs list) confirming the reading. **Vision
Reading Confidence = `verified` throughout** — the OCR-text-layer problem described in the dispatch
affects `pdftotext`'s automated extraction only, not the actual image content, which required no
guesswork. **No handwritten marginalia was found anywhere in this range** — this is a clean modern
scan, not a used/annotated copy.

**Correction to a sibling chunk's page-boundary estimate.** The dispatch note (passed down from a
sibling subagent covering PDF pp. 124-163) stated the book's Verb Tables appendix begins at PDF page
124 as two-printed-pages-per-image spreads. Direct inspection found this is **off by 7 pages**: the
appendix actually begins at **PDF page 117** (printed appendix page 1, verb "abolir"), not 124 — and
every appendix page *is* a two-printed-page spread (confirmed: PDF p.120 alone contains both "aunar"
pg.8 and "avergonzar" pg.9 side by side), consistent with the sibling's spread observation, just
starting earlier than estimated. This chunk's own range (PDF 83-123) therefore already captures the
appendix's first 14 entries (printed pp. 2-15, verbs abolir through coger, alphabetically A-C) in
addition to the main-text chapters. Worth flagging to the orchestrator in case the sibling's own
range was dispatched assuming the 124 starting point.

**Non-redundant-supplement scope decision.** Skimmed `006_practice_makes_perfect_advanced_spanish_grammar.md`,
`007_practice_makes_perfect_spanish_irregular_verbs.md`, and `008_practice_makes_perfect_spanish_verb_tenses.md`
(+ `008b`/`008c`) before extracting, per the non-redundant-supplement rule.
- **Skipped as redundant:** the basic `no` + verb negation mechanic and the three basic
  question-formation strategies (voice-rise / word-order inversion / question word) — both already
  captured in `008`'s Ch. 1 "Negation" and "Question formation" grammar points. Also skipped:
  re-deriving full six-person conjugation paradigms for the 14 Verb Tables appendix verbs in this
  range — the paradigm *mechanics* (regular -ar/-er/-ir endings, stem changes, irregular-stem
  patterns) are already covered systematically by `007` and `008c`'s own appendices; this file
  instead captures each verb as a vocabulary item with its specific irregularity type and one
  illustrative example, not the full paradigm table (also avoids bulk-reproducing a copyrighted
  conjugation chart verbatim).
- **Kept in full, as genuinely new:** (1) the double-negative word system beyond plain `no`
  (nunca/jamás/nada/nadie/tampoco/ni…ni/no…más/ningún) and negative word order; (2) the fuller
  question system (qué vs. cuál vs. quién fine distinctions, de quién, indirect questions, negative
  questions, ¿verdad?/¿no? tags) — `008` only covered the coarse three-way split; (3) the complete
  "verbs followed by a specific preposition" idiom system (a/de/con/en/por) and the full gustar-type
  verb list (gustar/encantar/faltar/quedar/doler/interesar/importar/hacer falta with all tenses) —
  `006` only flagged gustar-type pronoun behavior in one line, without the verb list; (4) **Adverbs,
  Prepositions, Conjunctions, Spelling, Stress/accentuation, Numbers, and Time/Date** — none of
  these have a systematic prior established file in this Spanish corpus, so all are extracted in
  full; (5) the 14 Verb Tables appendix entries, as vocabulary items with irregularity notes.
- **Explicit dialectal annotation found and kept:** the Spelling chapter explicitly marks that
  **c/z before e/i is pronounced [θ] ("th") in European Spanish vs. [s] in Latin American Spanish**
  (the seseo/distinción split) — this is the book's own explicit regional marking, not an inference,
  and is exactly the kind of content the extraction spec flags as highest-priority. Captured as a
  grammar point below.

---

### Vocabulary

**Column values held constant across this entire table unless a row states otherwise:**
Usage Tier = `core`; Weight/Frequency = `—` (no frequency-dictionary data in this source); Attested
Era = "contemporary (source published 2004)"; Attested Region = `—`; Geographic Scope = `—`; Source
Type = `grammar_reference`; Transcription Confidence = `n/a`; Vision Reading Confidence = `verified`.

#### Verbs + fixed preposition idioms (pp. 150-153)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| oler a algo | to smell of something | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | takes **a** |
| parecerse a alguien/algo | to look like somebody/something | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | takes **a** |
| subir(se) a un autobús/un coche | to get on a bus/into a car | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | takes **a** |
| subir(se) a un árbol | to climb a tree | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | takes **a** |
| tener miedo a alguien | to be afraid of somebody | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | takes **a**; contrast `tener miedo de algo` (below) |
| dar/decir/enviar/escribir/mostrar algo a alguien | to give/say/send/write/show something to someone | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | **a** marks indirect object; unlike English, **a** can never be omitted even though English can drop "to" (p. 150) |
| asistir a algo | to attend something, to be at something | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | takes **a** |
| dirigirse a (un lugar) | to head for (a place) | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | takes **a** |
| dirigirse a alguien | to address somebody | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | takes **a** |
| jugar a algo | to play something (sports/games) | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | takes **a** |
| llegar a (un lugar) | to arrive at (a place) | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | takes **a** |
| acordarse de algo/alguien | to remember something/somebody | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | takes **de** |
| alegrarse de algo | to be glad about something | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | takes **de** |
| bajarse de un autobús/un coche | to get off a bus/out of a car | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | takes **de** |
| darse cuenta de algo | to realize something | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | takes **de** |
| depender de algo/alguien | to depend on something/somebody | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | takes **de** |
| despedirse de alguien | to say goodbye to somebody | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | takes **de** |
| preocuparse de algo/alguien | to worry about something/somebody | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | takes **de**; a variant with **por** also exists (below) |
| quejarse de algo | to complain about something | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | takes **de** |
| reírse de algo/alguien | to laugh at something/somebody | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | takes **de** |
| salir de (un cuarto/un edificio) | to leave (a room/a building) | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | takes **de** |
| tener ganas de algo | to want something | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | takes **de** |
| tener miedo de algo | to be afraid of something | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | takes **de** |
| trabajar de (camarero/secretario) | to work as (a waiter/secretary) | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | takes **de** |
| tratarse de algo/alguien | to be a question of something/to be about somebody | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | takes **de** |
| comparar algo/a alguien con algo/alguien | to compare something/somebody with something/somebody | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | takes **con** |
| contar con alguien/algo | to rely on somebody/something | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | takes **con** |
| encontrarse con alguien | to meet somebody (by chance) | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | takes **con** |
| enfadarse con alguien | to get annoyed with somebody | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | takes **con** |
| estar de acuerdo con alguien/algo | to agree with somebody/something | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | takes **con** |
| hablar con alguien | to talk to somebody | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | takes **con** |
| soñar con alguien/algo | to dream about somebody/something | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | takes **con** |
| entrar en (un edificio/un cuarto) | to enter, go into (a building/a room) | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | takes **en** |
| pensar en algo/alguien | to think about something/somebody | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | takes **en** |
| trabajar en (una oficina/una fábrica) | to work in (an office/a factory) | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | takes **en** |
| interesarse por algo/alguien | to ask about something/somebody | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | takes **por** |
| preguntar por alguien | to ask for/about somebody | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | takes **por** |
| preocuparse por algo/alguien | to worry about something/somebody | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | takes **por**; variant of the `de` form above |
| mirar algo/a alguien | to look at something/somebody | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | **no preposition** in Spanish other than personal **a** (direct object), unlike English "look AT" |
| escuchar algo/a alguien | to listen to something/somebody | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | no preposition other than personal **a** |
| buscar algo/a alguien | to look for something/somebody | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | no preposition other than personal **a** |
| pedir algo | to ask for something | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | no preposition |
| esperar algo/a alguien | to wait for something/somebody | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | no preposition other than personal **a** |
| pagar algo | to pay for something | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | no preposition |

#### Verbal idioms — gustar-type verbs (pp. 154-156)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| gustar | to please (= "to like" when subject/object inverted) | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | `Me gusta el chocolate` = lit. "chocolate pleases me"; endings agree with the **liked thing**, not the person; the liker is marked with an indirect object pronoun (me/te/le/nos/os/les); usable in any tense (`gustó`, `va a gustar`, `ha gustado`) |
| encantar | to love (something) | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | same gustar-type pattern, e.g. `Me encanta el flamenco` |
| faltar | to be missing, lacking | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | gustar-type, e.g. `Le faltaba un botón` ("he had a button missing") |
| quedar | to have left, remaining | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | gustar-type, e.g. `No les queda nada` |
| doler | to hurt | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | gustar-type, e.g. `Le dolía la cabeza` |
| interesar | to interest | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | gustar-type, e.g. `Te interesará el libro` |
| importar | to matter (to someone), to mind | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | gustar-type, e.g. `No me importa la lluvia` |
| hacer falta | to need | verb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | gustar-type, e.g. `Nos hace falta un ordenador` |

#### Negatives (pp. 158-159) — beyond basic `no`

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| nunca | never, not...ever | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | `no...nunca` or `nunca` alone before the verb |
| jamás | never, not...ever | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | synonym of `nunca`; also usable alone before the verb |
| nada | nothing, not...anything | pronoun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | `no...nada` or `nada` alone before the verb |
| nadie | nobody, not...anybody | pronoun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | `no...nadie` or `nadie` alone before the verb |
| tampoco | not...either, neither | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | `Yo no la vi. — Yo tampoco` ("I didn't see her — neither did I") |
| ni...ni | neither...nor | conjunction (split) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | `No vinieron ni Carlos ni Ana` |
| no...más | no longer, not...any more | adverb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | `No te veré más` |
| ningún/ninguna + noun | no, not...any | determiner | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | `No tiene ningún interés en ir` |

#### Questions (pp. 160-165)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| qué | what, which | interrogative | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | always accented; used before a noun for "which" (`¿Qué chaqueta...?`); also used for "what" when asking for a definition with `es`/`son` |
| cuál/cuáles | which (one/ones) | interrogative pronoun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | used instead of **qué** when not directly before a noun; also used for "what" (`¿Cuál es la capital...?`) when not asking for a definition |
| quién/quiénes | who | interrogative pronoun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | singular/plural distinction; takes personal **a** when object (`¿A quién viste?`) |
| de quién/de quiénes | whose | interrogative phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | `de quién` = one likely owner, `de quiénes` = more than one |
| cuándo | when | interrogative | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | always accented, incl. in indirect questions |
| cuánto/cuánta/cuántos/cuántas | how much/how many | interrogative | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | agrees in gender/number with the following noun |
| dónde | where | interrogative | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | always accented |
| adónde | where...to | interrogative | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | always accented |
| por qué | why | interrogative phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | two words, accented on **qué**; contrast `porque` (because, one word, unaccented) |
| para qué | what for | interrogative phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| cómo | how | interrogative | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | also used instead of **qué** when asking someone to repeat what they said (`¿Cómo?` = "What (did you say)?") |
| ¿verdad? | isn't it?, don't you? (tag) | tag phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | added to the end of a statement to check a fact, like English tag questions |
| ¿no? | isn't it? (tag) | tag phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | especially after positive comments, e.g. `Hace calor, ¿no?` |
| sí/no | yes/no | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | direct answers; a negative answer to a negative question can mean saying `no` twice (`No lo has hecho, ¿verdad? — No` = "you haven't done it, have you? — No, I haven't") |

#### Adverbs (pp. 166-177)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| lentamente / normalmente | slowly / normally | adverb (-mente) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | regular formation: **-mente** added to the feminine singular adjective form (lento→lenta→lentamente) |
| bien | well | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | irregular adverb from `bueno` (good) |
| mal | badly | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | irregular adverb from `malo` (bad) |
| alto | high, loud(ly) | adverb/adjective | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | identical to masc. sg. adjective; never agrees when used as adverb |
| bajo | low, quiet(ly) | adverb/adjective | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | identical to masc. sg. adjective |
| barato | cheap(ly) | adverb/adjective | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | identical to masc. sg. adjective |
| claro | clear(ly) | adverb/adjective | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | identical to masc. sg. adjective |
| derecho | right, straight | adverb/adjective | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | identical to masc. sg. adjective |
| fuerte | loud(ly), hard | adverb/adjective | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | identical to masc./fem. adjective (ends in -e) |
| rápido | fast, quick(ly) | adverb/adjective | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | identical to masc. sg. adjective |
| mejor | better | adverb (comparative) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | irregular comparative of `bien` |
| peor | worse | adverb (comparative) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | irregular comparative of `mal` |
| más | more; (the) most | adverb/adjective | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | irregular comparative/superlative of `mucho`; never changes ending even as adjective |
| menos | less, fewer; (the) least | adverb/adjective | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | irregular comparative/superlative of `poco`; never changes ending |
| tanto como | as much as | adverb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | alternative comparison construction |
| tan...como | as...as | adverb phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | alternative comparison construction, e.g. `Vine tan pronto como pude` |
| ahí | there | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| ahora | now | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| allá | there (further away) | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| allí | there | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| anoche | last night | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| anteanoche | the night before last | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| anteayer | the day before yesterday | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| antes | before | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| apenas | hardly | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| aquí | here | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| arriba | above, upstairs | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| atrás | behind | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| aun | even | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | no accent; contrast `aún` below (mnemonic in source: "Even **aun** doesn't have an accent") |
| aún | still, yet | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | has accent; contrast `aun` above |
| ayer | yesterday | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| casi | almost | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| cerca | near | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| claro | clearly | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | also listed above as dual adjective/adverb |
| debajo | underneath | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| dentro | inside | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| despacio | slowly | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| después | afterwards | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| detrás | behind | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| enfrente | opposite | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| enseguida | straightaway | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| entonces | then | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| hasta | even | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | also a preposition (see Prepositions below) |
| hoy | today | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| jamás | never | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | also listed under Negatives above |
| lejos | far | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| luego | then, later | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| muy | very | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| no | no, not | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| nunca | never | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | also listed under Negatives above |
| pronto | soon, early | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| quizás | perhaps | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | present subjunctive required after `quizás` when referring to the future |
| sí | yes | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| siempre | always | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| sólo | only | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| también | also, too | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| tampoco | either, neither | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | also listed under Negatives above |
| tan | as, so | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| tarde | late | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| temprano | early | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| todavía | still, yet, even | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| ya | already | adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| bastante | enough, quite, a lot | adjective/adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | as adjective, agrees (bastante/bastantes); as adverb, invariable |
| demasiado | too much/too many; too | adjective/adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | as adjective, agrees (demasiado/demasiada/demasiados/demasiadas); as adverb, invariable |
| tanto | as much/as many; so often | adjective/adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | as adjective, agrees (tanto/tanta/tantos/tantas); as adverb, invariable |
| mucho | a lot (of), much/many | adjective/adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | as adjective, agrees (mucho/mucha/muchos/muchas); as adverb, invariable |
| poco | little, not much/not many; not very | adjective/adverb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | as adjective, agrees (poco/poca/pocos/pocas); as adverb, invariable; contrast `un poco` ("a little/a bit") |
| a veces | sometimes | adverb phrase (multi-word) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| a menudo | often | adverb phrase (multi-word) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| de vez en cuando | from time to time | adverb phrase (multi-word) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| todo el tiempo | all the time | adverb phrase (multi-word) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| hoy en día | nowadays | adverb phrase (multi-word) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| en seguida | immediately | adverb phrase (multi-word) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | written as two words here vs. `enseguida` above — source gives both spellings in different sections |

#### Prepositions (pp. 178-191)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| a | to, at, onto, into, from (after certain verbs) | preposition | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | merges with `el` → `al`; used for destinations, indirect objects, times, prices/rates, ages, distances, and after certain adjectives/verbs; personal **a** precedes a specific person/pet direct object (NOT after `tener`) |
| de | of, from, belonging-to, made-of/for, in (superlatives) | preposition | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | merges with `el` → `del`; `de...a` = "from...to"; used in comparisons with a number (`más/menos de 100`, no `que`) |
| en | in, at, on, by (transport), into, in (languages) | preposition | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| para | for (person/destination/purpose/time), (in order) to | preposition | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | `para mí` can mean "in my opinion" |
| por | for (benefit/exchange), by (passive, transport-freight), along, through, around, vaguely-at, per/rate, time-of-day, because-of, via | preposition | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | combines with other prepositions/adverbs for movement: `por encima de`, `por debajo de`, `por delante de` |
| antes de | before | preposition (multi-word) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | used before infinitives where English uses -ing |
| bajo | below, under | preposition | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | `debajo de` more common than `bajo` for literal physical position |
| con | with | preposition | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | used after certain adjectives/phrases: `enfadado con`, `un café con leche` |
| contra | against | preposition | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| debajo de | under | preposition (multi-word) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | more common than `bajo` for literal position |
| delante de | in front of | preposition (multi-word) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| desde | from, since | preposition | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | present tense used with `desde` for actions started in the past and still ongoing (`Estoy aquí desde las diez`) |
| desde hace / hace...que | for (duration) | preposition phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | used with present tense for ongoing duration; perfect tense + `desde`/`desde hace` for negative duration in European Spanish |
| después de | after | preposition (multi-word) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | used before infinitives where English uses -ing |
| detrás de | behind | preposition (multi-word) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| durante | during, for | preposition | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| entre | between, among | preposition | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| hacia | towards, around | preposition | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | combines with adverbs: `hacia arriba/abajo/adelante/atrás` |
| hasta | until, as far as, to, up to | preposition | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | common farewell phrases: `¡Hasta luego!`, `¡Hasta mañana!` |
| sin | without | preposition | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | used before infinitives where English uses -ing; no indefinite article after `sin` (`sin sombrero` not `sin un sombrero`) |
| sobre | on, about | preposition | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | also means "about" with approximate numbers/times |
| a causa de | because of | preposition (multi-word) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| al lado de | beside, next to | preposition (multi-word) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| cerca de | near, close to | preposition (multi-word) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| encima de | on, on top of | preposition (multi-word) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| por encima de | above, over | preposition (multi-word) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| en medio de | in the middle of | preposition (multi-word) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| junto a | by | preposition (multi-word) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| junto con | together with | preposition (multi-word) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| lejos de | far from | preposition (multi-word) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |

#### Conjunctions (pp. 192-196)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| y | and | conjunction | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | becomes **e** before words starting with `i`/`hi` (not `hie`) |
| o | or | conjunction | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | becomes **u** before words starting with `o`/`ho`; becomes **ó** between numerals (to avoid confusion with 0) |
| pero | but | conjunction | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| sino | but (rather) | conjunction | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | used in direct contrasts after a negative, e.g. `No es escocesa, sino irlandesa` |
| porque | because | conjunction | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | never used at the start of a sentence — use `como` instead there; contrast `por qué` (why, two words) |
| como | as, because (sentence-initial) | conjunction | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| que | that | conjunction | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | can never be omitted in Spanish, unlike optional "that" in English |
| si | if, whether | conjunction | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | no accent (contrast `sí` = yes) |
| cuando | when | conjunction | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| pues | then, well | conjunction | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| mientras | while (time) | conjunction | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| mientras que | whereas | conjunction | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| aunque | although, even though; even if | conjunction | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | "even if" sense triggers the subjunctive |
| ni...ni | neither...nor | conjunction (split) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | requires `no` before the verb if placed after it |
| o...o | either...or | conjunction (split) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |

#### Numbers (pp. 206-208)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| uno/dos/tres...treinta | 1-30 | number (cardinal) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | 16-19, 21-29 are single words (dieciséis...veintinueve); `veintiún/veintiuna` before a noun |
| uno, un, una | one | number | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | `uno` alone when counting; `un`/`una` before masc./fem. nouns (incl. plural compounds like `treinta y un días`) |
| cuarenta/cincuenta/sesenta/setenta/ochenta/noventa | 40/50/60/70/80/90 | number | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | tens, combine with `y` + units (e.g. `cuarenta y uno`) |
| cien, ciento | one hundred | number | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | `cien` before nouns and before `mil`/`millones`; `ciento` before other numbers (`ciento cincuenta`); no "and" translated in `ciento uno` etc. |
| doscientos/trescientos/cuatrocientos/quinientos/seiscientos/setecientos/ochocientos/novecientos | 200-900 | number | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | agree in gender with the noun (doscientos/doscientas); `setecientos`/`novecientos` are irregular (no -i-, -o- not -ue-) |
| mil | one thousand | number | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| un millón | one million | number | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| primero/primer, segundo, tercero/tercer, cuarto, quinto, sexto, séptimo, octavo, noveno, décimo | 1st-10th | number (ordinal) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | `primero`→`primer`, `tercero`→`tercer` before masc. sg. noun; figures written 1º/1ª/1er, 2º/2ª, 3º/3ª/3er |
| centésimo, milésimo | 100th, 1000th | number (ordinal) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| Carlos tercero / Alfonso trece | Charles the Third / Alfonso the Thirteenth | number usage | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | ordinals used only up to **décimo**; cardinal numbers used for higher royal/papal numbering |

#### Time and Date (pp. 209-211)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| ¿Qué hora es? | What time is it? | phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | `Es la una` (one o'clock) but `Son las dos/tres...` for all other hours |
| menos cuarto / y cuarto / y media | quarter to / quarter past / half past | phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| lunes, martes, miércoles, jueves, viernes, sábado, domingo | Monday-Sunday | noun (m.) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | days of the week; **not capitalized** in Spanish |
| enero, febrero, marzo, abril, mayo, junio, julio, agosto, septiembre, octubre, noviembre, diciembre | January-December | noun (m.) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | months; **not capitalized** in Spanish |
| el dos de mayo | the second of May | phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | cardinal numbers used in dates (not ordinals, except optionally "the first" = `el 1`/`el uno`) |
| hoy, esta mañana, esta tarde, esta noche | today, this morning, this afternoon, this evening | phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| ¿Con qué frecuencia? todos los días, cada dos días, una vez por semana, dos veces por semana, una vez al mes | How often? every day, every other day, once/twice a week, once a month | phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | frequency expressions |
| anteayer, ayer, ayer por la mañana/tarde/noche, anoche | the day before yesterday, yesterday, yesterday morning/afternoon/last night | phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | overlaps with Adverbs list above; included here as the book's own "useful phrases" grouping |
| hace una semana, hace quince días, la semana pasada, el año pasado | a week ago, two weeks ago, last week, last year | phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| mañana, mañana por la mañana/tarde/noche, pasado mañana | tomorrow, tomorrow morning/afternoon/night, the day after tomorrow | phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |
| dentro de dos días, dentro de una semana, dentro de quince días, el mes/año que viene | in two days'/a week's/two weeks' time, next month/year | phrase | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified |  |

#### Verb Tables appendix — verbs A-C (printed appendix pp. 2-15; PDF pp. 117-123)

Full six-tense/mood paradigm charts (present, present subjunctive, preterite, imperfect, future,
conditional, imperative, past participle, gerund) are given per verb in the source; not reproduced
here per copyright discipline — only the verb, its irregularity type, and the page's own
illustrative example are captured. Paradigm mechanics for these irregularity types are already
covered systematically by `007_practice_makes_perfect_spanish_irregular_verbs.md`.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| abolir | to abolish | verb (defective) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | present tense only exists in the `nosotros`/`vosotros` forms (no present subjunctive at all) — a genuine defective verb, distinct from ordinary irregularity |
| abrir | to open | verb (-ir, regular except participle) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | irregular past participle `abierto` |
| actuar | to act | verb (-uar, stress-shift) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | `ú` takes a written accent in forms where stress falls on it: actúo, actúas, actúa... |
| adquirir | to acquire | verb (i→ie stem change) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | adquiero, adquieres, adquiere... (stressed syllable only) |
| almorzar | to have lunch | verb (o→ue stem change + z→c spelling) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | almuerzo/almuerzas/almuerza...; z→c before e (almorcé, almuerce) per the Spelling chapter's rule |
| andar | to walk | verb (irregular preterite stem) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | preterite `anduve, anduviste, anduvo...` (not regular -é/-aste) |
| aunar | to join together | verb (-uar, stress-shift) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | `ú` accented where stressed: aúno, aúnas... |
| avergonzar | to shame, embarrass | verb (o→üe stem change + z→c spelling + g→gü) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | avergüenzo (note diéresis on ü to keep the [gw] sound before e); reflexive `avergonzarse de` = "to be ashamed of" |
| averiguar | to find out | verb (gu→gü spelling before e) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | preterite/subjunctive `averigüé/averigüe` (diéresis keeps the [gw] sound before e) |
| bendecir | to bless | verb (irregular, decir-pattern) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | present `bendigo`, preterite `bendije` (decir-type irregular preterite stem); idiom `Dios te bendiga` ("God bless you") |
| caber | to fit | verb (highly irregular) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | present `quepo`, preterite `cupe`, future `cabré` (irregular future stem) |
| caer | to fall | verb (yo-form + preterite 3rd-person irregularity) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | present `caigo` (yo only); preterite 3rd person `cayó/cayeron` (y-insertion) |
| cocer | to boil, cook | verb (o→ue stem change + c→z spelling) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | cuezo/cueces/cuece...; c→z before a/o (cozamos, cueza) |
| coger | to catch, take, pick up, get (a train/bus) | verb (g→j spelling before a/o) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | present `yo cojo` but `tú coges`; **register note, not from this source:** this verb is well documented outside this book as carrying a vulgar/taboo sense ("to have sex") in much of Latin America (e.g. Mexico, Argentina), while the Peninsular-Spanish-authored Collins glosses only the neutral "to take/catch/get" sense throughout — flagged here as a candidate for independent cross-check during Phase 3 corpus collection, not verified against any source in this extraction |

### Grammar points

#### Verbs that take a fixed preposition, and the gustar-type reversal (pp. 150-156)

Spanish has many verb+preposition idioms where the preposition doesn't match English, organized by
which preposition they take (a/de/con/en/por). A separate small system — gustar and seven verbs
that behave the same way (encantar, faltar, quedar, doler, interesar, importar, hacer falta) —
grammatically inverts the English subject/object relationship: the liked/needed thing is the
grammatical subject (and controls verb agreement, singular `gusta` vs. plural `gustan`), while the
person doing the liking is marked with an indirect object pronoun. This is distinct from, but related
to, the leísmo/pronoun-choice note already captured in `006`.

#### Double negatives and negative word order (pp. 158-159)

Beyond plain `no`, Spanish has a set of negative words (nunca, jamás, nada, nadie, tampoco, ni...ni,
ningún) that can either combine with `no` (verb sandwiched between them, `No lo he visto nunca`) or
stand alone before the verb without `no` (`Nunca lo he visto`). Unlike English, these negative words
can freely stack without cancelling each other out: `Nunca viene nadie` = "No one ever comes" (not a
double negative that becomes positive, as in formal English). A hard syntactic rule: never insert a
negative word (or anything else) between a perfect-tense auxiliary (he/has/ha/había) and the past
participle.

#### The qué/cuál/quién question-word system (pp. 160-165)

Beyond the three basic question-formation strategies, Spanish draws finer distinctions English
doesn't mark as clearly: **qué** is mandatory directly before a noun ("which jacket"); **cuál/cuáles**
otherwise for "which (one/ones)"; and when asking "what is X" there's a three-way split — use **cómo**
(not qué) when asking someone to repeat what they said, **¿cuál/cuáles es/son...?** when not asking
for a definition (e.g. "what's the capital of France"), and **¿qué es/son...?** only when genuinely
asking for a definition (e.g. "what are genes"). Question words always carry an accent, including in
indirect and reported questions (`No sé qué hacer`) and after expressions of uncertainty — this
doesn't change even though the sentence itself isn't a direct question.

#### Adverb formation and position (pp. 166-177)

Regular adverbs are formed by adding **-mente** to the feminine singular form of an adjective
(lenta→lentamente); when two or more -mente adverbs are joined by y/pero, only the last one keeps
the suffix (`lenta pero eficazmente`). A closed set of adjectives (alto, bajo, barato, claro,
derecho, fuerte, rápido) double as invariable adverbs with no ending change. Comparatives/
superlatives of adverbs use `más`/`menos` exactly like adjectives, with two irregular pairs
(bien→mejor, mal→peor). Position: adverbs normally follow the verb, can precede it for emphasis, but
can never separate a perfect-tense auxiliary from its past participle — the same "never interrupt
haber + participle" rule that applies to negative words above.

#### Spelling changes to preserve pronunciation, incl. the European/Latin American c-z split (pp. 196-199)

Because **c** sounds [k] before a/o/u but [θ]("th")/[s] before e/i, and **g** sounds [g] before a/o/u
but [x]("ch" as in loch) before e/i, verbs ending in **-car/-gar/-zar/-cer/-cir/-ger/-gir/-guir** must
alter their spelling before certain endings to keep the original sound: -car→qu (saqué), -gar→gu
(pagué), -zar→c (crucé), -cer/-cir→z (hizo), -ger/-gir→j (cojo), -guir drops u (sigo). The same z→c
shift applies to plural nouns/adjectives ending in -z (una vez → dos veces). **Explicit regional
annotation (highest-priority content per this project's extraction spec):** the source states
directly that **c/z before e or i is pronounced [θ] ("th", as in English "pith") in European Spanish,
but [s] (as in "sing") in Latin American Spanish** — e.g. `centro` is [then-tro] in Spain vs.
[sen-tro] in Latin America, `cita` is [the-ta] vs. [see-ta]. This is the standard distinción/seseo
phonological split, confirmed here as explicitly marked by the source itself (not inferred).

#### Accent/stress rules, incl. diacritical accent pairs (pp. 200-205)

Spanish words ending in a vowel, -n, or -s are stressed on the second-to-last syllable by default and
need no accent if they follow that rule; words ending in any other consonant default to final-syllable
stress. A written acute accent is only needed when a word's actual stress breaks the applicable
default rule. Beyond pure stress-marking, the acute accent is also used purely to distinguish
otherwise-identical word pairs with different meanings/functions: mi/mí, tu/tú, te/té, si/sí, el/él,
de/dé, solo/sólo, mas/más — and on demonstrative pronouns (éste/ésta, aquél/aquélla) to distinguish
them from the otherwise-identical demonstrative adjectives (este/esta, aquel/aquella). Question words
and exclamation words (¡Qué asco!) always carry an accent regardless of the general stress rules.

#### Numbers, dates, and European punctuation conventions (pp. 206-211)

Ordinal numbers (primero...décimo, centésimo, milésimo) are rarely used past "tenth" in practice —
cardinal numbers substitute even for things English would ordinalize, e.g. `Alfonso trece` ("Alfonso
the Thirteenth"), and royal/papal numbering always uses cardinals past ten. Dates use cardinal
numbers throughout (`el dos de mayo`), unlike English's ordinal convention. The source also flags a
European-vs-English punctuation-convention difference worth noting for any future numerals-in-corpus
work: Spanish uses a full stop (not a comma) to separate thousands/millions in figures (`700.000`)
and a comma (not a decimal point) for decimals (`0,5`).

#### Verb Tables appendix — irregularity patterns across abolir-coger (printed appendix pp. 2-15)

This slice of the appendix's alphabetical verb list (14 verbs, abolir through coger) illustrates
several distinct irregularity mechanisms in a single short stretch: a genuinely **defective** verb
with no present subjunctive at all (abolir); **stress-shift diphthong-breaking** in -uar verbs
(actuar, aunar — not a stem CHANGE but an accent placed on the u/i that would otherwise form a
diphthong with the following vowel); ordinary **stem-changing** verbs (adquirir i→ie, almorzar/cocer
o→ue, avergonzar o→üe); the **spelling-preservation** changes from the Spelling chapter in action
across real paradigms (almorzar/avergonzar z→c, averiguar/avergonzar gu→gü, cocer c→z, coger g→j);
and **genuinely irregular stems** unrelated to any spelling rule (andar's preterite `anduve`,
bendecir's decir-pattern preterite `bendije`, caber's `quepo`/`cupe`, caer's yo-form `caigo` and
3rd-person preterite y-insertion `cayó`).

---


---

## Spanish — Established Vocabulary/Grammar: Collins Easy Learning Spanish Grammar — Verb Tables, Verb Index, The Alphabet (final chunk)

**Source:** Collins, *Easy Learning Spanish Grammar* (HarperCollins, 1st Edition, 2004), PDF pages
124–163 of 163 total (final chunk of this book's extraction). This source has **no usable text
layer for this range** — it is a 300dpi scan with a low-quality, heavily character-corrupted OCR
layer (e.g. "6" for "é", "1"/"l" confusion, random symbol substitution). `pdftotext` output was used
only as a rough navigation aid to locate content boundaries; all content below was read from
rendered page images (`pdftoppm -r 150`).

**Page-mapping note (spread gotcha confirmed):** each PDF page in this range renders as **two
printed pages side by side** (a left/right spread within one image), not one PDF page per printed
page, despite `pdfinfo` reporting 163 total PDF pages uniformly. Verified empirically: PDF page 124
shows printed pages 16–17 ("Verb Tables" section), PDF page 158 shows printed pages 84–85, PDF page
161 shows printed pages 90–91, PDF page 162 shows printed page 92 (single page, "The Alphabet" —
right-hand facing page blank), and PDF page 163 is the book's **back cover** (publisher blurb +
ISBN barcode, no extractable grammar/vocabulary content — confirmed by direct inspection, correctly
treated as true end-of-book rather than assuming more content follows).

**Actual content range:** printed pages 16–92 (the book's "Verb Tables" + "Verb Index" + "The
Alphabet" back-matter appendix; this book's own page numbering restarts at this appendix). No
prepositions/conjunctions/word-order/numbers chapters were found in this range — contrary to the
dispatch's initial guess, those topics must fall earlier in the book (outside this chunk's
assignment). The appendix consists of:
- Printed pp. 16–84: **84 individual full-page verb conjugation tables**, one per "model" verb
  (alphabetical by infinitive: *comer* table 16 → *zurcir* table 84), each giving all 6 finite
  tenses + subjunctive + imperative + past participle + gerund + 2–3 example phrases.
- Printed pp. 85–91: **the Verb Index** — an alphabetical list of roughly 700+ Spanish verb
  infinitives, each mapped only to a pattern number (1–84) pointing back to its model verb's table.
  No English glosses are given in the source for index entries.
- Printed p. 91 (bottom): three numbered footnotes on defective/irregular verbs.
- Printed p. 92: "The Alphabet" — a letter-by-letter Spanish pronunciation guide (IPA + English
  approximation).

**Marginalia check:** sampled roughly 20% of this range (PDF pp. 124–125 / printed 16–19; PDF pp.
158–163 / printed 84–92 + back cover) by direct visual inspection. **No handwritten marginalia
found anywhere sampled** — this copy's scan is clean of reader annotation (pen/pencil marks,
underlining, owner notes) in every page checked. The only scan artifact noted is ordinary light
print bleed-through from the facing page (visible faintly on printed p. 92's blank right-hand side,
showing ghost text from p. 91's footnotes) — not marginalia, not re-extracted as separate content.

**Vision Reading Confidence:** `verified` throughout the Vocabulary table below — every entry was
read directly from a clearly legible, high-contrast rendered page image (not inferred from the
corrupted OCR layer).

### Non-redundant-supplement scope decision (read before the tables below)

Per `00_Reference_Extraction_Spec.md`'s non-redundant-supplement rule, I skimmed
`005_practice_makes_perfect_basic_spanish_grammar.md` and, most relevantly,
`007_practice_makes_perfect_spanish_irregular_verbs.md` (125+ verbs, full 6-principal-parts
paradigms) and `008_practice_makes_perfect_spanish_verb_tenses.md` (492 rows, systematic tense-
formation coverage) before extracting.

**Treated as redundant and skipped (not re-extracted):**
- **All 84 individual full-page verb conjugation tables (printed pp. 16–84).** Every finite-tense
  paradigm this appendix shows (present, preterite, imperfect, future, conditional, present
  subjunctive, imperative, gerund, past participle) for model verbs like *comer*, *conducir*,
  *construir*, *contar*, *hacer*, *ir*, *jugar*, *leer*, *sacar*, *salir*, *satisfacer*, *seguir*,
  *tener*, *traer*, *venir*, *ver*, *volver*, *zurcir*, etc. is the exact same information already
  captured, in equal or greater systematic depth, by 007 (irregular-verb principal-parts method)
  and 008 (full verb-tenses paradigm tables). Reproducing ~84 more full paradigm tables here would
  be pure duplication, not new information.
- **The bulk of the ~700-entry Verb Index (printed pp. 85–91).** This is a bare infinitive →
  pattern-number cross-reference with **no English glosses supplied by the source itself** — it is
  explicitly a lookup tool ("find which of the 84 model-verb patterns this verb follows"), not a
  glossed vocabulary list. The overwhelming majority of its ~700 infinitives are ordinary core-tier
  verbs (*abandonar*, *acabar*, *decidir*, *limpiar*, *preparar*, etc.) already attested across
  Spanish's existing vocabulary-focused established files (009, 010–013, 014, 015 and others).
  Bulk-tabulating all ~700 would add volume without adding real lexical information.

**Kept, and why (genuinely new content):**
- The **3 footnote grammar points** on defective verbs (weather/time-of-day verbs, *pudrir*,
  *soler*) — specific usage-restriction facts not obviously covered by 007/008's principal-parts
  framing, which doesn't flag defective paradigms as such.
- **The weather/time-of-day defective-verb set itself**, as vocabulary entries with their
  restriction explicitly noted (not previously captured as a *set* anywhere in Spanish's
  established files, as far as this extraction's skim found).
- **A curated sample (~20 items) of genuinely distinctive, less-core verbs spotted while visually
  scanning the Verb Index pages** (sound/sensory verbs, register-marking verbs, idiomatically
  colorful ones) — picked because they are less likely to already be covered and carry real
  standalone lexical/sociolinguistic value for this project (e.g. *tutear*, directly relevant to
  register/address-form slang mechanics). This is a deliberately non-exhaustive sample, not a
  systematic re-pass of the full index — explicitly flagged as such rather than silently presented
  as complete.
- **"The Alphabet" page (printed p. 92)** in full — a letter-by-letter Spanish pronunciation guide
  with IPA, not previously captured by any skimmed prior Spanish established file.
- A couple of short illustrative example phrases, quoted selectively per copyright discipline.

---

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| amanecer | to dawn; to wake up (at a given time/place) | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | Defective/impersonal verb (Verb Index footnote 1, p. 91): used almost exclusively in the infinitive and 3rd-person-singular forms. |
| anochecer | to get dark (nightfall) | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | Same defective-verb footnote as amanecer. |
| atardecer | to get dark (dusk falling) | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | Same defective-verb footnote. |
| granizar | to hail (weather) | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | Same defective-verb footnote; weather verb. |
| helar | to freeze (weather) | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | Same defective-verb footnote; weather verb. |
| llover | to rain | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | Same defective-verb footnote; weather verb. |
| nevar | to snow | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | Same defective-verb footnote; weather verb. |
| nublarse | to cloud over | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | Same defective-verb footnote; weather verb. |
| tronar | to thunder | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | Same defective-verb footnote; weather verb. |
| pudrir | to rot | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | Verb Index footnote 2 (p. 91): irregular past participle is *podrido* (not the expected regular *pudrido*). |
| soler | to usually/habitually (do something) | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | Verb Index footnote 3 (p. 91): defective verb, used only in the present and imperfect indicative — no future/preterite/subjunctive forms in normal use. |
| tutear | to address someone using *tú* (informal "you") | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | Verb Index, p. 91, pattern 39 (regular). Flagged specially here: directly names the T/V informal-address mechanism (tú vs. usted) as a lexicalized verb — high relevance for register/politeness slang mechanics. |
| regatear | to haggle, bargain | verb | colloquial | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | Verb Index, p. 90, pattern 39. Culturally flavored (market/street-bargaining register). |
| tararear | to hum (a tune) | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | Verb Index, p. 91, pattern 39. |
| tartamudear | to stammer, stutter | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | Verb Index, p. 91, pattern 39. |
| zambullirse | to dive, plunge (into water) | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | Verb Index, p. 91, pattern 4. Reflexive. |
| ronronear | to purr | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | Verb Index, p. 90, pattern 39. Onomatopoeic sound verb. |
| ruborizarse | to blush | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | Verb Index, p. 90, pattern 21. Reflexive. |
| vitorear | to cheer, acclaim | verb | formal | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | Verb Index, p. 91, pattern 39. |
| vituperar | to vituperate, revile | verb | formal | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | Verb Index, p. 91, pattern 39. Notably literary/elevated register for an everyday grammar-book index. |
| tergiversar | to twist, distort (words/facts) | verb | formal | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | Verb Index, p. 91, pattern 39. |
| chapotear | to splash about | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | Verb Index, p. 86, pattern 39. |
| chirriar | to screech, squeak | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | Verb Index, p. 86, pattern 31. Onomatopoeic sound verb. |
| crujir | to creak, crunch | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | Verb Index, p. 86, pattern 81. Onomatopoeic sound verb. |
| cuchichear | to whisper | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | Verb Index, p. 86, pattern 39. |
| fisgar | to snoop, pry | verb | colloquial | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | Verb Index, p. 88, pattern 53. |
| gruñir | to grunt, growl; (colloquial) to grumble | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | Verb Index, p. 88, pattern 37 — **this is itself a model verb (its own pattern)**, shown in bold in the source. Also one of the individual full-page verb tables found within this chunk's range. |
| machacar | to crush, pound; (colloquial) to go on and on (about something) | verb | colloquial | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | Verb Index, p. 88, pattern 68. Figurative colloquial sense noted from general Spanish knowledge, not spelled out by the bare index entry itself. |
| zurcir | to darn, mend (clothing) | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | verified | Model verb, pattern 84 (alphabetically last model-verb table in the appendix, printed p. 84). Example phrase quoted below. |

**Model-verb catalog note:** the appendix's 84 model-verb tables were not individually re-tabulated
above (see redundancy decision) — the pattern numbers run 1 ("abolir") through 84 ("zurcir"),
alphabetically. A handful of bold-marked model verbs spotted while sampling the index pages beyond
those already listed: *abrir* (3), *adquirir* (5), *almorzar* (6), *andar* (7), *aunar* (8),
*avergonzar* (9), *averiguar* (10), *bendecir* (11), *caber* (12), *caer* (13), *cocer* (14), *coger*
(15), *estar* (35), *erguir* (32), *errar* (33), *escabullirse* (37 — same number shown for gruñir
in one sampled page, likely an OCR/sampling misread; not independently resolved), *freír* (36),
*gruñir* (37), *haber* (38), *hablar* (39 — by far the most common pattern number, the regular -ar
paradigm), *hacer* (40), *hay* (41, impersonal "there is/are"), *ir* (42), *jugar* (43), *leer*
(44), *lucir* (46), *morir* (47), *mover* (48), *nacer* (49), *negar* (50), *oír* (51), *oler* (52),
*pagar* (53), *pedir* (54), *pensar* (55), *poder* (56), *poner* (57), *resolver* (63), *rogar*
(65), *romper* (66), *saber* (67), *sacar* (68), *salir* (69), *satisfacer* (70), *seguir* (71),
*sentir* (72), *ser* (73), *tener* (74), *torcer* (75), *traer* (76), *valer* (77), *vencer* (78),
*venir* (79), *ver* (80), *vivir* (81), *volcar* (82), *volver* (83), *zurcir* (84). This list is
provided as a structural reference to the appendix's own organization, not as a re-extraction of
each paradigm (all already covered via 007/008).

### Grammar points

#### The 84-pattern conjugation classification system (Verb Tables + Verb Index)

This appendix organizes Spanish verb conjugation around 84 numbered "patterns," each represented
by one full model-verb table (printed pp. 16–84). Every other Spanish verb is assigned to whichever
pattern it conjugates like; the separate Verb Index (pp. 85–91) is purely a lookup — verb →
pattern number — with the model verbs themselves shown in bold within the index. For example,
*acampar* ("to camp") is index-listed under pattern 39, meaning it conjugates exactly like the
model verb *hablar*. This is a pedagogical organizing device rather than a new grammatical fact
about Spanish (the underlying conjugation classes themselves are already covered via 007/008's
irregular-verb analysis), but the specific pattern-number mapping is a reusable practical reference
not present in those earlier extractions.

#### Defective verbs restricted to infinitive + third-person-singular: weather and time-of-day verbs

Per Verb Index footnote 1 (p. 91), the verbs *amanecer*, *anochecer*, *atardecer*, *granizar*,
*helar*, *llover*, *nevar*, *nublarse*, and *tronar* are "used almost exclusively in the infinitive
and third person singular forms." These are impersonal weather verbs (*llover* "to rain," *nevar*
"to snow," *granizar* "to hail," *helar* "to freeze," *tronar* "to thunder," *nublarse* "to cloud
over") plus time-of-day verbs describing the natural transition of light (*amanecer* "to dawn,"
*anochecer*/*atardecer* "to get dark"). Structurally these behave like English weather verbs
("it rains," never "*I rain"): the implied subject is the ambient world/sky itself, not a true
grammatical agent, so first/second-person and plural forms are grammatically well-formed but
essentially never used (except in figurative/idiomatic extension, e.g. *amanecer* can take a
personal subject meaning "to wake up at [place/time]," which the footnote's "almost exclusively"
hedge is implicitly acknowledging).

#### Irregular past participle: *pudrir* → *podrido*

Per Verb Index footnote 2 (p. 91): the past participle of *pudrir* ("to rot") is irregular —
*podrido*, not the regular-formation *pudrido* a learner might predict by analogy with other
-ir verbs. Worth noting that the irregular participle's stem vowel (*podr-*) doesn't even match the
infinitive's stem vowel (*pudr-*) — an o/u stem alternation unique to this verb's participle.

#### Defective verb restricted to present/imperfect: *soler*

Per Verb Index footnote 3 (p. 91): *soler* ("to usually/habitually do something," always followed
by an infinitive, e.g. *suelo levantarme temprano* "I usually get up early") is used only in the
present and imperfect indicative — it has no standard preterite, future, conditional, or
subjunctive forms in normal usage. This is a stronger defectiveness than the weather-verb set above
(restricted by *tense*, not by *person*).

#### The Spanish alphabet (pronunciation guide, printed p. 92)

A letter-by-letter table giving each letter's IPA value and an English-approximation respelling,
with a few comparative notes (e.g. *g* and *j* both compared to "ch" in Scottish "loch" — the
voiceless velar/uvular fricative [x]). Full table, paraphrased from the source's own three-column
layout (letter — IPA — English-approximation respelling):

| Letter(s) | IPA | English-approx. respelling | Note |
|---|---|---|---|
| A, a | [a] | ah | like "a" in "la" |
| B, b | [be] | bay | |
| C, c | [θe] | thay | |
| Ch, ch | [tʃe] | chay | |
| D, d | [de] | day | |
| E, e | [e] | ay | |
| F, f | [ˈefe] | efay | |
| G, g | [xe] | chay | like "ch" in Scottish "loch" |
| H, h | [ˈatʃe] | atshay | |
| I, i | [i] | ee | |
| J, j | [ˈxota] | chota | like "ch" in Scottish "loch" |
| K, k | [ka] | ka | |
| L, l | [ˈele] | elay | |
| Ll, ll | [ˈeʎe] | elyay | |
| M, m | [ˈeme] | emay | |
| N, n | [ˈene] | enay | |
| Ñ, ñ | [ˈeɲe] | enyay | |
| O, o | [o] | oh | |
| P, p | [pe] | pay | |
| Q, q | [ku] | koo | |
| R, r | [ˈere] | eray | |
| Rr, rr | [ˈere] | erray | |
| S, s | [ˈese] | esay | |
| T, t | [te] | tay | |
| U, u | [u] | oo | |
| V, v | [ˈuβe] | oobay | |
| W, w | [ˈuβeˈdoble] | oobaydoblay | |
| X, x | [ˈekis] | ekees | |
| Y, y | [iˈɣrjeɣa] | ee-griayga | |
| Z, z | [ˈθeta] | thayta | |

Note: this is a standard-Peninsular-leaning IPA/respelling (θ for *c*/*z*, distinct *ll* [ʎ]) — the
book does not flag this as a dialectal choice, but it is worth noting for this project that this
pronunciation does not match Latin American *seseo* (where *c*/*z* before e/i merge with *s*, [s]
not [θ]) or *yeísmo* (where *ll* merges with *y*), both extremely widespread across Latin American
Spanish. The source presents this single pronunciation as "the" Spanish alphabet without regional
qualification — a gap worth flagging rather than silently reproducing as neutral/universal.

#### Illustrative example phrases (selective quotes, copyright discipline)

- *zurcir* ("to darn"): "¡Que te zurzan!" — idiomatic, glossed by the source as "Get lost!" (literal
  "may they darn you" — a colloquial dismissal/curse expression built on this otherwise mundane
  verb; genuinely slang-adjacent and worth flagging for the synthesis phase).
- *construir* ("to build"): "Yo solo construí el puzzle." — "I did the jigsaw puzzle on my own."
  (illustrates *solo* as "alone/by myself" rather than "only," a common learner confusion point).

---


---


## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`.
