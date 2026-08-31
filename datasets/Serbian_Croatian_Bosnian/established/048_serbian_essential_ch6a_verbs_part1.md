# Serbian — Essential Grammar: Chapter 6 "Verbs," §6.1–6.9 (Infinitives through The Conditional)

**Source:** Lila Hammond, *Serbian: An Essential Grammar* (Routledge, 2005). Chapter 6 "Verbs,"
§§6.1–6.9, printed pp. 35–86 (Cyrillic-primary text, with parallel Latin-script transliteration and
English gloss given for essentially every example — this is a Serbian-specific reference, unlike
the comparative B/C/S sources already extracted for this language). PDF has a clean text layer;
`pdftotext -layout` was used on the full 337-page file (Chapter 6 body runs from line 1463 through
line 3551 of that extraction; the table of contents at lines 160–199 gives the authoritative printed
page numbers used to bound this chunk). No vision-reading was required.

**A structural PDF-extraction issue, not a source-content issue:** this copy's Cyrillic text is
extracted as garbled Latin-lookalike glyphs by `pdftotext` (a font-encoding mismatch specific to
this PDF's embedded Cyrillic font — e.g. printed «Морате» extracts as `Vjhfnt`). The parallel
Latin-script transliteration printed alongside every Cyrillic example is **not** affected and reads
cleanly. Per the dispatch instructions, this file uses the clean Latin-script form as the primary
`Term`/example citation throughout and does not attempt to reconstruct the garbled Cyrillic register
of the extraction; where the source visibly also gives a Cyrillic form, that is simply noted as
"Cyrillic form also given in source (not reproduced — PDF font-encoding garbles this copy's Cyrillic
extraction)" rather than guessed at.

**Coverage note — this is a third reference book for the same language, and most of this chapter
overlaps ground already covered in depth by the flagship textbook (`established/003–022`) and its
companion Grammar (`established/037–041`).** Deliberately **skipped as redundant**:
- §6.1 (infinitive classification into Type I/II/III by present-tense vowel) and §6.2 (infinitive
  vs. present-tense stem formation, including the dual-infinitive-ending verb list `dizi/dignuti`
  etc.) — the same information, in more exhaustive form (16 verb-types with class codes), is already
  in `established/024_appendix9_verb_types.md`.
- §6.3 (transitive/intransitive distinction; imperfective/perfective aspect, including the
  infix-`i`/suffix-`va`/suffix-`ava`/suffix-`iva` aspect-pair-formation mechanisms and the full hard-
  consonant-softening correspondence table before `-ava-`) — the same suffixation typology and
  consonant-softening system is already documented in `established/038_grammar_ch4-6_supplementary.md`
  (§53) and `established/039_grammar_ch7-9_supplementary.md` (§112-adjacent material).
- §6.4.1's present-tense personal-ending tables for Type I/II/III conjugations — redundant with the
  16-type present-tense endings already tabulated in `024_appendix9_verb_types.md`.
- The `biti` (to be) short-form present (`sam/si/je/smo/ste/su`), long-form present
  (`jesam/jesi/jest(e)/jesmo/jeste/jesu`), and negated present (`nisam/nisi/nije/nismo/niste/nisu`)
  paradigms — already fully tabled in `established/003_lesson01_complete.md` and
  `established/023_appendices1-6_grammar_reference.md`.
- The negated present of `imati` (`nemam/nemaš/nema...`) and of `hteti` (`neću/nećeš/neće...`) —
  already captured in `established/004_lesson02.md`, `established/023_...`, and
  `established/026_glossary_bcs_english_part1.md`.
- The `zar` negative-interrogative particle itself (general rule) — already documented in
  `established/007_lesson05.md`'s "Negation" grammar point.
- §6.8 Future II's core formation (`budem` + L-participle) and §6.9 the conditional's three
  sentence-types (realizable / potentially realizable / unrealizable) — both already fully covered,
  including worked examples and politeness-formula usage, in `established/015_lesson13.md`
  (conditional) and `established/041_grammar_ch13-16_supplementary.md` (Future II / *futur drugi*).

**Genuinely new/deeper material kept below** — this book's real contribution for this chunk is
exactly what the dispatch flagged: (1) a **fully systematic negative / interrogative / negative-
interrogative paradigm treatment applied uniformly across the present, perfect, future, and aorist
tenses**, spelling out multiple alternative question-formation constructions per tense (something no
prior source in this dataset laid out this systematically — prior sources document `zar` and `da
li`/`li` individually but never walk all four tenses through the full four-way present/negative/
interrogative/negative-interrogative grid); (2) **the aorist tense in real systematic depth** —
full worked person/number paradigms for three different stem-shapes (vowel-stem `-ti` verbs;
consonant-stem `-ći`/`-sti` verbs with their 2nd/3rd-singular consonant mutations; and the small
closed class of verbs with dual aorist forms, `hteti`/`znati`/`imati`), plus its three distinct uses
(immediate-past, narrative-past, immediate-future) and its own negative/interrogative/negative-
interrogative system — `established/014_lesson12.md` gives only prose description and
`established/040_grammar_ch10-12_supplementary.md` §122a gives only a condensed two-verb-type ending
reference with no negative/interrogative treatment at all, so the full worked paradigms and the
neg/interrog system here are new; (3) a few genuinely new procedural/word-order nuances in future-
tense formation (the infinitive-first enclitic-attachment mechanics, the `da li` vs. `hoćeš li`
ambiguity between "will you" and "do you want to" and how the source resolves it); and (4) one new
usage nuance for Future II (its use to express a historical-present passive construction with no
introducing conjunction) not mentioned in the prior Future-II coverage.

---

## Vocabulary

No new headword-level vocabulary items were introduced in this chunk beyond what prior extractions
already cover — every illustrative verb used in these paradigm tables (*uzeti* "take," *vratiti*
"return," *napisati* "write," *moći* "be able to," *reći* "say," *poći* "set off," *hteti* "want,"
*znati* "know," *imati* "have," *biti* "be") is already a tabled headword in
`established/012_lesson10.md`, `established/023_appendices1-6_grammar_reference.md`, or
`established/024_appendix9_verb_types.md`. One new headword:

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| zagrepsti, zagrebem | to scratch (P) | verb | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | p. 78; used as the model consonant-stem (`-sti`) verb in the aorist paradigm table, alongside *moći* and *reći*; not previously tabled in this dataset. Cyrillic form also given in source (not reproduced — PDF font-encoding garbles this copy's Cyrillic extraction). |

## Grammar points

### §6.4.2–6.4.4 — The present tense: negative, interrogative, negative-interrogative

**Negative** (§6.4.2): `ne` + verb, written as two separate words, for all verbs *except* `biti`,
`imati`, and `hteti`, whose negative present is a single fused word (`nisam`, `nemam`, `neću`, etc.
— all three paradigms already tabled elsewhere in this dataset, see coverage note above).

**Interrogative** (§6.4.3): three distinct constructions for a yes/no question in the present tense,
all functionally equivalent: (a) verb first, followed by the interrogative enclitic `li`
(*Volite li pasulj?* "Do you like beans?"); (b) `da li` + verb (*Da li volite pasulj?*); (c) `je li`
+ verb (*Je li volite pasulj?* — here `je` is not itself the enclitic form of "to be" despite the
resemblance, per the source's own note). All three are interchangeable in the present tense; later
sections (below) show that not every tense supports all three variants equally.

**Negative-interrogative** (§6.4.4): `zar` + negative-present verb, e.g. *Zar ne idemo u grad?* "Are
we not going to town?"

### §6.5.2–6.5.4 — The perfect (past) tense: negative, interrogative, negative-interrogative

**Negative** (§6.5.2): the negated short-form `biti` auxiliary (`nisam/nisi/nije...`) + the main
verb's past-adjectival (L-)participle. Unlike the affirmative auxiliary, the negative auxiliary is
**not an enclitic** and does not need to occupy second position. A double-negative note: the negated
perfect combines with a negative adverb like `još` "still, as yet" without contradiction (*Ja još
ništa nisam rekao* "I still haven't said anything," lit. "I still nothing haven't said" — the
negative concord already documented in `established/038_grammar_ch4-6_supplementary.md` §56a, shown
here specifically co-occurring with the negated perfect).

**Interrogative** (§6.5.3): two constructions (not three, unlike the present): (a) the *long* form
of `biti` + `li` + main-verb participle (*Je li razgovarala sa nastavnicom?* "Has she spoken to the
teacher?"); (b) `da li` + the *short* form of `biti` + participle (*Da li si se javila mami?* "Did
you call your mother?"). Note the long/short-form split tracks which construction is used — the
plain verb-first + `li` construction available in the present tense is not used here because the
auxiliary itself, not the participle, carries the person/number marking.

**Negative-interrogative** (§6.5.4): `zar` at the sentence's start, followed by the negated (short-
form) auxiliary, then the participle. Neither the `zar` nor the negated auxiliary is an enclitic, but
the word order must still respect where an enclitic *would* sit (*Zar nije bio kod lekara?* "Has he
not been to the doctor?").

### §6.6 — Future tense: formation mechanics, and negative/interrogative/negative-interrogative

**Formation** (§6.6.1): short-form `hteti` (`ću/ćeš/će/ćemo/ćete/će`) as an enclitic auxiliary +
main verb infinitive. Three word-order variants depending on sentence position:
- Normal (non-initial) position: auxiliary follows the first stressed word, infinitive follows
  normally (*Večeras ću doći u London* "Tonight I will come to London").
- Sentence/clause-initial position only: the infinitive can lead, with the auxiliary **fused onto
  it as one word**, replacing the infinitive's own `-ti` ending (*zvati* → *zva- + ću* → *zvaću*
  "I will call"). For infinitives in `-sti`, the `s` first mutates to `š` before the auxiliary
  fuses on (*jesti* → *ješću* "I will eat"). For infinitives in `-ći`, the two words stay separate
  instead of fusing, with the auxiliary simply taking second (enclitic) position (*doći ću*, not a
  fused form).
- An alternative construction throughout: auxiliary + `da` + main verb in the **present tense**
  instead of the infinitive (*Ja ću da dođem u London večeras*), with the subject pronoun more often
  retained than in the infinitive construction.

**Negative** (§6.6.2): the auxiliary itself is negated (`neću/nećeš/neće/nećemo/nećete/neće`) — and
critically, **only the short form of `hteti` can be negated this way**; there is no such thing as
`*ne hoću` for the future negative (contrast the long-form `hoću` "I want," which negates instead to
mean "I don't want" via ordinary `ne` + long form, a different, still-valid construction with a
different meaning — see below).

**Interrogative** (§6.6.3), two constructions, both usable with either the infinitive or `da` +
present-tense main verb: (a) `da li` + auxiliary + (`da` +) main verb; (b) the **long form** of
`hteti` (`hoću/hoćeš/hoće...`) + `li` + (`da` +) main verb (*Hoćeš li ići sada na spavanje?* "Will
you go to sleep now?"). Construction (b) is flagged as genuinely ambiguous, because the long form of
`hteti` also independently means "to want" — *Hoće li igrati naša ekipa?* could be read as either
"Will our team play?" or, less naturally, a question about the team's willingness. The source's own
disambiguation heuristic: pairing the long-form-`hteti`+`li` construction with the bare **infinitive**
main verb favors the future-tense reading, while pairing it with `da` + present-tense main verb
favors the volition ("want to") reading — though it notes this is not fully reliable and context is
often still needed.

**Negative-interrogative** (§6.6.4): `zar` + negated auxiliary (+ `da` + present, or infinitive). The
same future/volition ambiguity noted above can recur here too.

### §6.7 — The aorist tense: uses, full paradigms, and negative/interrogative/negative-interrogative

**Uses** (§6.7.1): three distinct functions, all narrower than the perfect tense's general past-time
role: (1) an action completed *immediately* prior to the moment of speaking (*Evo ga, stiže* "Here he
is, he has [just] arrived"); (2) narrative past — a terminated action at a specific past point,
common in storytelling register (*Konačno napisah pismo bratu* "I've finally written a letter to my
brother"); (3), notably, an **immediate future** sense (*Sačekaj nas, odosmo po ključeve* "Wait for
us, we're off to get the keys" — a present-tense-feeling errand framed in the aorist). The source
notes the aorist is now mostly a written/literary register form, generally replaced by the perfect
in speech — consistent with what `014_lesson12.md` and `040_...supplementary.md` already say, but
this book is the first in the dataset to spell out these three distinct discourse *uses* rather than
just naming the tense.

**`biti`'s aorist** doubles as the conditional-mood auxiliary (`bih/bi/bi/bismo/biste/biše`) — already
tabled with this exact function in `established/026_glossary_bcs_english_part1.md`; not re-tabled
here, only cross-referenced (source itself cross-references forward to its own §6.9 conditional).

**Full worked paradigms** (§6.7.1, three stem-shape classes — none of the following was previously
given as complete worked forms anywhere in this dataset, only as bare endings in
`040_grammar_ch10-12_supplementary.md` §122a):

*Vowel-stem `-ti` verbs* (endings `-h/–/–/-smo/-ste/-še` added directly after dropping `-ti`), shown
for `uzeti` "take," `vratiti` "return," `napisati` "write":

| | 1sg | 2sg | 3sg | 1pl | 2pl | 3pl |
|---|---|---|---|---|---|---|
| *uzeti* | uzeh | uze | uze | uzesmo | uzeste | uzeše |
| *vratiti* | vratih | vrati | vrati | vratismo | vratiste | vratiše |
| *napisati* | napisah | napisa | napisa | napisasmo | napisaste | napisaše |

*Consonant-stem `-ći`/`-sti` verbs* (endings `-oh/-e/-e/-osmo/-oste/-oše` added to the pre-
assimilation stem), shown for `moći` "be able to," `reći` "say," `poći` "set off," `zagrepsti`
"scratch." In the 2nd/3rd singular, the stem-final consonant mutates before `-e`: `k→č`, `g→ž`,
`h→š`.

| | 1sg | 2/3sg | 1pl | 2pl | 3pl |
|---|---|---|---|---|---|
| *moći* (stem *mog-*) | mogoh | mo**že** | mogosmo | mogoste | mogoše |
| *reći* (stem *rek-*) | rekoh | re**če** | rekosmo | rekoste | rekoše |
| *poći* (stem *poįd-*) | pođoh | pođe | pođosmo | pođoste | pođoše |
| *zagrepsti* (stem *zagreb-*) | zagreboh | zagre**be** | zagrebosmo | zagreboste | zagreboše |

*Verbs with dual aorist forms* — a small closed class (`hteti` "want," `znati` "know," `imati`
"have") that each have **two** valid aorist paradigms: a short vowel-stem-type form, and a longer
form built with an inserted `-d-` before the consonant-stem-type endings:

| | 1sg | 2/3sg | 1pl | 2pl | 3pl |
|---|---|---|---|---|---|
| *hteti* (short) | hteh | hte | htesmo | hteste | hteše |
| *hteti* (long, `-d-`) | htedoh | htede | htedosmo | htedoste | htedoše |
| *znati* (short) | znah | zna | znasmo | znaste | znaše |
| *znati* (long, `-d-`) | znadoh | znade | znadosmo | znadoste | znadoše |
| *imati* (short) | imah | ima | imasmo | imaste | imaše |
| *imati* (long, `-d-`) | imadoh | imade | imadosmo | imadoste | imadoše |

**Negative aorist** (§6.7.2): `ne` + verb in the aorist, written as two separate words — no fused
irregular forms the way the present/future negatives have (*Ja ne odoh u London ove godine* "I have
not gone to London this year").

**Interrogative aorist** (§6.7.3): two constructions — (a) `da li` + aorist verb; (b) aorist verb +
`li` directly (no `da`) — both freely interchangeable (*Da li htedoste da ostanete na večeru?* /
*Htedoste li da ostanete na večeru?*, both "Did you want to stay for dinner?").

**Negative-interrogative aorist** (§6.7.4): two constructions — (a) `zar` + `ne` + aorist verb; (b)
`ne` + aorist verb + `li` (no `zar`) — again interchangeable (*Zar ne htedoste da ostanete na
večeru?* / *Ne htedoste li da ostanete na večeru?*).

**Cross-tense pattern worth flagging for the mechanics-analysis phase:** across present, perfect,
future, and aorist, the number of distinct interrogative/negative-interrogative constructions the
source offers is not uniform — present and aorist each get multiple freely-interchangeable variants,
while perfect and future's variants are tied to which auxiliary form (long vs. short) is used and
carry the disambiguation burdens noted above. This asymmetry (more free variation in the "lighter,"
single-word tenses; more form-constrained variation in the compound tenses) is a structural pattern
this book is the only source in the dataset to lay out explicitly enough to notice.

### §6.8.1 — Future II: one additional usage nuance

Beyond its already-documented core use (an action anterior to or simultaneous with another future
action, introduced by conjunctions like `kad`, `ako`, `dok`, `pošto`, `čim`), the source notes Future
II can also express a **historical-present passive** — a past event narrated with a passive
participle and the Future-II auxiliary, but with *no* introducing conjunction at all (*Krajem te
godine, on bude postavljen za predsednika države* "At the end of that year, he was appointed
president of the country") — a stylistic/narrative use not mentioned in this dataset's prior Future
II coverage (`established/041_grammar_ch13-16_supplementary.md`).

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `../../00_Reference_Extraction_Spec.md`.
