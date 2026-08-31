# Serbian/Croatian/Bosnian — Established Grammar: *A Grammar and Social Commentary*, Chapters 13–16 (supplementary, non-redundant material only)

**Source:** Ronelle Alexander, *Bosnian, Croatian, Serbian, A Grammar with Social Commentary*
(University of Wisconsin Press, 2006), Chapters 13–16, §§131–153, printed pp. 214–301 (PDF pp.
928–1015 of the combined scan, located via `pdftotext -layout` search for the "CHAPTER 13"/"CHAPTER 17"
running-header text — printed page numbers differ from PDF page numbers because of this book's own
front matter).

**Text layer:** Clean text layer throughout this range (`pdftotext -layout` produced fully usable
output); no vision-reading was needed, so the vision-reading/marginalia guard does not apply to this
chunk.

## Scope note — why this file is short relative to the page range it covers

Per the book's own preface, Chapters 1–16 of this *Grammar* track the same lesson-by-lesson sequence
as the companion textbook (*Bosnian, Croatian, Serbian, a Textbook*), which this project has already
fully extracted in `established/003_lesson01_complete.md` through `established/022_lesson20.md`.
Concretely, this chunk's four chapters map onto:

- **Chapter 13 (§131–137)** → overlaps `015_lesson13.md` (conditional mood, politeness formulas,
  indirect discourse, conditional sentence types, conditional of purpose, relative conjunction *koji*).
- **Chapter 14 (§136–143)** → overlaps `016_lesson14.md` (infinitive-as-imperative, active/passive,
  passive/impersonal formation, verbal adverbs, telling time).
- **Chapter 15 (§142–147)** → overlaps `017_lesson15.md` (aspect choice, *sve* + comparative, "each
  other", *stati*, *sav/sve/svi*, infinitive vs. *da* + present).
- **Chapter 16 (§148–153)** → overlaps `018_lesson16.md` + vocab files (formal address, reciprocal
  "each other", B/C/S showcase letters), and is explicitly billed by the book itself as containing
  "full verb paradigms" (§153).

**What was deliberately skipped as redundant:** basic conditional-mood formation and its politeness/
toned-down/repetition/purpose uses (already in `015_lesson13.md` at a pedagogically adequate level);
basic PP-passive vs. *se*-passive formation and impersonal-sentence formation (already in
`016_lesson14.md`); basic verbal-adverb formation (present `-ći`, past `-vši` — already reviewed in
`016_lesson14.md`); the core aspect-choice discussion already given in `017_lesson15.md`. Where this
book's version of one of these topics is markedly more systematic/exhaustive than the textbook's
version (e.g. the full real/potential/unreal conditions taxonomy, or the relative-clause case-marking
notation), that fuller version is captured below rather than skipped, per this dispatch's instructions.

**What was extracted as genuinely new/deeper:** the systematic real/potential/unreal conditional-
sentence taxonomy (§132); the *koji*/*što*/*čiji*/*kakav* relative-clause case-agreement mechanics and
notation (§136); the PP-passive vs. *se*-passive semantic distinction and agent-marking rule (§139);
the full subjectless-sentence taxonomy with dative/genitive logical subjects (§141); the modal-verb
system table (§142); the entire conjunction system (§143, a-k) — compound conjunctions, *kako*,
*da* vs. *što*, doubled/indefinite conjunctions — none of which is covered in comparable depth in any
lesson file; the exact future/aspect-usage summary tables and the backgrounding/foregrounding theory
of narrative aspect use (§144–145); the full prefixation system and aspect-pair typology (§146–147);
verbal nouns in *-će* (§148); the compound/simplex tense review paradigm tables including aorist and
imperfect (§149–150); literary tense usage in 19th-century narrative prose (§151); and — the
headline new content of this chunk — the **complete verb-type paradigm tables for all 16 conjugation
types plus *hteti/htjeti* and *biti*** (§152–153), which is a genuinely new "review grammar" resource
the lesson-based textbook never assembles in one place.

No vocabulary table is included in this file: this chunk of the source is pure grammatical
exposition (no vocabulary boxes), consistent with `023_appendices1-6_grammar_reference.md`'s
precedent for paradigm-table-heavy chunks of this book.

---

## Grammar points

### §132. Conditional sentences: real/potential/unreal, a systematic three-way taxonomy

The textbook lesson gives conditional-sentence examples; this book gives the underlying system in a
single reference chart, genuinely more systematic than the lesson treatment:

| Type | Conjunction | Tense/mood in "if" clause | Tense/mood in "then" clause |
|---|---|---|---|
| **Real** (result fully expected) | `ako` (almost always) | any tense but future | any but conditional |
| **Potential** (may or may not come to pass) | `kad` or `ako` | conditional | conditional |
| **Unreal** (impossible, or hypothetical) | `da` | present or past | conditional |

- **Real conditions** are barely "conditional" grammatically — the conditional mood is *absent*; its
  presence after `ako` in a real-looking sentence signals speaker skepticism about the condition's
  realness. Besides `ako`, `kad` (translatable "since") and `li`/`da li`-style clauses can express
  "if," but if English *if* could be replaced by *whether* without change of meaning, the BCS
  sentence is an embedded question (needs `li`/`da li`), not a conditional, and `ako` must not be used.
- **Potential conditions** put the *entire sentence* — both clauses — in the conditional mood, with no
  tense marking at all; English marks this contrast with a past-tense verb (*If he asked you, would
  you go?*) but BCS marks it purely through the conditional mood, not tense.
- **Unreal conditions** are of two subtypes sharing conjunction `da` + conditional mood in the "then"
  clause: (a) *formerly potential* (`da` + past tense in the "if" clause — the once-realizable window
  has closed) and (b) *purely hypothetical/imaginary* (`da` + present tense — never was realizable).
  Croatian may reinforce pastness with the **past conditional** (`bio bih ìšao`, compound of L-participle
  of *biti* + conditional auxiliary + main-verb L-participle) in either subtype; Bosnian/Serbian tend to
  rely on context/aspect instead and avoid the past conditional.
- A single worked example (having time and money to travel) is run through all four readings
  (real-present, real-future, potential, unreal-once-potential, unreal-hypothetical) to show how the
  same underlying scenario shifts conjunction+mood, not just tense, across the four readings.

### §136. Relative clauses: systematic case/gender/number agreement mechanics

The book gives an explicit four-step procedure and a case-notation convention (`A` for antecedent,
`R` for the relative conjunction, with case/number/gender abbreviations like `Nsg.f`, `Apl.m`) that is
more rigorous than the lesson-level treatment:

1. Identify the antecedent (the noun the relative conjunction refers to).
2. Determine the antecedent's gender and number (ignore its case).
3. Put the *same* gender/number marking on the relative conjunction.
4. Determine the relative conjunction's *own* case from the grammar of *its own* clause.

Beyond *koji* (agreeing with antecedent in gender/number, taking its own clause's case — like English
*who/which/that*, but never omissible in BCS):

- **Personal pronouns as antecedents** — *koji* then agrees in person and number, and the verb after
  *koji* must also agree in person/number (e.g. `Mi kòji žìvimo na sèlu...` "We who live in the
  country...").
- **`čiji`** ("whose") and **`kakav`** (roughly "what kind of") also function as relative conjunctions
  under the same agreement rules, though `čiji` is sometimes substituted for `iz koje/kojega` ("of
  whom"), which can obscure the underlying sentence structure.
- **`što`** as a relative conjunction carries the same meaning as `koji`, but since `što` itself cannot
  take case endings, the sentence must add a *clitic pronoun object* (agreeing with the antecedent in
  gender/number, taking the required case) immediately after `što` to carry the case information —
  e.g. `Je li òvo knjiga što si je spomènula?` ("Is this the book you mentioned?" — lit. "...that you
  [it] mentioned"). If the antecedent is an indefinite pronoun (`jedini`, `nešto`, `sve`), the relative
  is `ko`/`tko` (human) or `što` (non-human), not `koji`.

### §139. PP-passive vs. *se*-passive: the semantic and agent-marking distinction

Two structurally distinct passive types exist, sharing only the underlying logic "object of active
sentence becomes subject of passive sentence":

- **PP-passive**: `biti` + passive participle (participle agrees with subject in gender/number).
  Focuses on the **result** of an action; correlates loosely with perfective aspect.
- **se-passive**: active verb + `se` (verb agrees with subject in number/person as usual). Focuses on
  the **action itself**; correlates loosely with imperfective aspect. This correlation is a tendency,
  not a rule — some verb pairs violate it with no perceptible meaning difference between *se*- and
  PP- versions.
- **The one reliable structural difference**: only PP-passives can specify an agent (as object of `od`,
  or in official/administrative style, `od strane` + genitive) — `Odluka je donesena od strane
  Ministarstva` ("The ruling was adopted by the Ministry"). **BCS grammar does not allow an agent
  phrase with *se*-passives at all.** Agent-specification is itself rare and mostly confined to
  official written registers; many speakers find it stilted.

### §141. Subjectless sentences: full taxonomy, review

The book treats "subjectless" as the broad grammatical category (3sg. verb + neuter singular
L-participle, no nominative subject) and "impersonal" as a narrower semantic subset within it —
useful terminological precision beyond the lesson-level material:

- **True subjectless** (no logical subject at all in any case): three subtypes — impersonal actions by
  unspecified humans (translate with English *one*/*you*), natural states/processes/facts (translate
  with English dummy *it*), and subjectless modal verbs (`treba`, `valja`).
- **Dative logical subject**: experienced states (`Drago mi je...`), inclinational/desiderative verbs
  (`spava mi se`, `peva mi se` — "I feel like singing," reversible per-person: `Meni se nè ide, a bratu
  se ide` "I don't feel like going, but my brother does"), and `činiti se`/`uspeti`-`uspjeti`.
- **Genitive logical subject**: adverbs of measure (`kolìko`, `malo`, `puno`), existentials (`ima`,
  `nema`), and numbers 5+ used as sentence subject.
- Each subtype is drilled in present vs. past to reinforce that the "subjectless" grammatical shape
  (3sg. verb, neuter sg. L-participle) holds across tenses.

### §142. Modal verbs: the full system table

| Verb | Modal meaning | Non-modal meaning |
|---|---|---|
| `moći` | can, be able to, may | — |
| `mòrati` | must, have to | — |
| `smjeti`/`smeti` | dare, be allowed to, may | — |
| `trebati` | ought, should | need |
| `ùmjeti`/`ùmeti` | know how to, be able to | — |
| `vàljati` | ought, should | be worth [something] |
| `znati` | know how to, can, be able to | know |

Notable points not obvious from a single-verb lesson treatment:
- `vàljati`'s modal meaning occurs **only** in subjectless 3sg. usage; `trebati` in its modal meaning
  likewise occurs more often subjectless than conjugated.
- **Negated `morati` vs. negated `moći` reverse the expected English mapping.** Negated `morati` simply
  removes obligation ("doesn't have to"), while the *stronger* meaning "must not" is carried by
  negated `moći` (which also retains its ordinary "not be able to" meaning) — a genuine trap for
  English speakers, worth flagging for any downstream conlang mechanics work on modality inversion.
- `morati` (and the future of `biti`) can express **inference** ("that must be why...") rather than
  obligation — a semantic extension beyond the textbook's coverage.
- `treba` can be omitted in recipes/instructions/manuals, leaving a bare infinitive to carry the whole
  instructive force.

### §143. The conjunction system (a–k) — largely new material, not covered at this depth in any lesson file

This is the single largest genuinely-new grammar block in Chapters 13–16.

**§143a–b. Coordinating "and"/"but" conjunctions, and compound conjunctions.** BCS has multiple words
for "and," each adding a distinct shade: `i` (parallelism), `a` (non-parallelism/contrast), `te`
(addition), `pa` (sequentiality/causation — "and then"/"and so"), `dok` (concurrence, "while"). "But"
splits into `ali` (plain contrast) vs. `već`/`nego` (contrastive "not A but rather B"). Crucially,
**BCS does not allow a bare preposition to double as a subordinating conjunction the way English does**
(*before dinner* vs. *before they serve dinner*): a preposition must be supplemented with a
conjunction-forming element — typically `što`, `toga što`, or `nego` (+ `što`/`li`) — to form a
**compound conjunction**. Table of English preposition/conjunction pairs mapped to BCS
preposition/compound-conjunction pairs: `prije`/`prije nego što` (before), `posle`/`posle toga što`
(or the fused form `pošto`, after), `nakon`/`nakon što` (after), `nego`/`nego što` (than),
`zbog`/`zbog toga što` (because of), `radi`/`radi toga što` (for the sake of), `zato`/`zato što`
(that's why), `tek`/`tek što` (just/the minute), `osim`/`osim [toga] što` (except), `pored`/`pored
toga što` (besides), `tako`/`tako da` (so that), `budući`/`budući da` (being/since), `bez`/`a da ne`
(without — this last pair has no formal relationship at all and must be learned as a lexical item).

**§143c. `kako`** as conjunction ("as, since") is also used after verbs of perception in a way that
trips up English speakers: `gledati kako rade` means "watch them work," not "watch how they work" —
BCS uses `kako` + finite verb where English uses a gerund/object-plus-bare-infinitive. In Bosnian/
Serbian, `kako` can substitute for `da` ("that") only with imperfective ongoing-action verbs; Croatian
allows it with either aspect.

**§143d–f. `da` as "that"/"to"/purpose, and the infinitive-replacement rule.** `da` obligatorily marks
"that"-clauses (never omissible, unlike English *that*), can follow `nema` for emphatic non-existence,
and signals presupposition after subjectless `mora`/`biće`. As "to" (potential action not yet
accomplished), `da` + present replaces an English infinitive whose subject differs from the main
clause's subject — English speakers are advised to mentally reformulate as "that [subject] might/
should..." to build the correct BCS sentence. A standalone `da`-clause alone communicates wish/
request/hope; negated + past tense, it becomes a veiled-threat command (`Da to više nikad nìsi
učìnio!` "Don't you ever do that again!"). **The infinitive-vs-`da`+present choice** (when subjects
match) is conditioned by three factors: geography (Croatian prefers infinitive, Serbian prefers `da`,
Bosnian uses both), whether the infinitive has an explicit subject (favors `da`), and word order
(an intervening word between main verb and infinitive favors `da`).

**§143g–h. `da` (potentiality) vs. `što` (established fact) — a genuine semantic minimal-pair
system**, not just free variation: verbs of *mental action* take `da`; verbs of *emotional state* take
`što` (`Rekli su da ga nema` "they said he wasn't around" vs. `Čudili su se što ga nema` "they were
surprised he wasn't around"). More subtly, in clauses where the *conjunction itself* (not the
governing verb) carries the meaning: `što`-clauses relate established facts, `da`-clauses describe
something not yet fully realized (possibility, imminence, initial stages) — equivalent in force to an
infinitive. This distinction also explains `kao što` (as, like — factual) vs. `kao da` (as if —
hypothetical). Subject/object clauses are almost always introduced by `što` (carrying the "established
fact" reading), often reinforced by a preceding `to` (`to što` = "the fact that," obligatory when the
clause is an object or object of a preposition, optional when it's the subject). `to`/`ono` + `što` can
also function as antecedent + relative pronoun pair, each independently case-marked per the A/R
notation from §136.

**§143j. Doubled comparison conjunctions.** BCS renders English *as...as* (which has no single BCS
equivalent) via rhyming k-/t- word pairs: `kako...tako`, `kad...tad`, `koliko...toliko`, `kud...tud`,
etc. — the rhyme itself signals the equivalence. `kako...tako i` = "both...and" in longer sentences.
English *the...the* (comparative) maps to BCS `što...to` (reviewed at §114a).

**§143k. Indefinite conjunctions/pronouns** (English *-ever*, *no matter...*): particles `bilo` and `ma`
precede the conjunction (BCS-wide vs. Bosnian/Serbian-preferred, respectively; Croatian uses `ma` less);
`god` follows it. Written together as one word (`kadgod`), the meaning is less strongly potential/
non-factual than written separately. Interrogative pronouns after `imati`/`nemati` also convey
indefiniteness with a more poetic register — illustrated with quotations from Dušan Radović and
Desanka Maksimović showing this is a genuine stylistic/literary register choice, not just a grammatical
option.

### §144–144a. Future expression system, and the "exact future"

Beyond the simple future tense (`hteti`/`htjeti` + infinitive), BCS marks a future-within-future
relationship two ways: (1) present-tense perfective verb after conjunctions like `kad`, `ako`, `čim`
(the *only* context where the first future is disallowed), or (2) the dedicated **exact future**
(*futur II*/*futur drugi* — conjugated `budem` + L-participle). Used with an imperfective verb, the
exact future occupies an aspectual middle ground between imperfective and perfective — more
goal-oriented than a plain imperfective present, without full perfective closure. With a perfective
verb it's redundant with the simple present-after-conjunction construction, so it's rarely used that
way in practice. The exact future also appears after relative conjunctions (chiefly *koji*) in an
indefinite "whoever/whichever" sense.

### §145. Aspect usage across all tense/mood combinations — full cross-tabulation

The book gives a systematic present/past/future/imperative × imperfective/perfective grid (not
reproduced verbatim here per copyright discipline) covering: repeated action, action-in-progress,
generic fact, and closure-focused readings for each aspect in each tense. One point of particular
value for slang/conlang mechanics work: **BCS speakers frequently over-translate imperfective verbs
into English progressive tenses** (not just for actions genuinely in progress), while English speakers
must avoid using the English present perfect for BCS past imperfectives (present perfect usually
maps to BCS present-tense imperfective instead, per §106a).

### §145c. Narrative aspect: backgrounding and foregrounding — a genuinely new theoretical framework

Not present in any lesson file. In a BCS past-tense narrative, **perfective verbs relate
"foregrounded" events that move the story forward; imperfective verbs relate "backgrounded" events**
that set the scene/establish context. A narrative can open with a run of imperfective
scene-setting (often triggered by `nalaziti se`) before switching into perfective with a signal
adverbial like `Jednoga dana...` ("One day..."), or it can open abruptly with a foregrounded
perfective event and then shift back into imperfective background-filling. Backgrounded material is
often additionally shifted into **present tense** ("historic present") purely for vividness — and once
in this artificial present, future-tense verbs become usable within the backgrounded material too.
Illustrated with excerpts from a Miro Gavran short story (*U zagrljaju rijeke*) and two brief
present-tense-narration excerpts, one showing foregrounded, one backgrounded historic-present use.
This backgrounding/foregrounding mechanism is a genuinely portable narrative-grammar concept worth
flagging for the project's later mechanics-analysis phase — it is aspect being recruited for a
discourse-structuring function beyond its core temporal/boundedness meaning.

### §146. Prefixation and verbal meaning — the full prefix-meaning system

Not covered at the lesson level. Most BCS verbal prefixes are historically related to prepositions but
diverge from them in meaning; the book gives a systematic prefix-meaning table using motion-verb
partners of *ići* as the base illustration set:

| Prefix | Core spatial meaning | Example (base `ìći` "go") |
|---|---|---|
| `do-` | up to | `dòći` come |
| `iz-` | out from | `ìzaći`/`ìzići` go out |
| `na-` | (irregular/complex — see below) | `nàići` come upon |
| `nad-` | above | `nàdići` surpass |
| `ob-` | around | `òbići` go around |
| `od-` | away from | `òtići` go away |
| `pod-` | under | `podbàciti` throw under |
| `pre-` | across | `prèći` cross |
| `pred-` | before | `prèdvideti` foresee |
| `pri-` | near | `prìći` approach |
| `pro-` | through | `pròći` go through |
| `raz-` | dispersal | `ràzići se` scatter |
| `s-` | down from (also, separately, "with," as `s-`/`sa-`) | `sìći` descend |
| `u-` | into | `ùći` go in |
| `uz-` | up along | `ùzići` ascend |
| `za-` | behind (rare in this literal sense) | `zàći` set [of sun] |

Three prefixes have **no** stable relationship to their look-alike prepositions and must be learned as
independent semantic units: **`po-`** (imparts "for a short period of time"), **`za-`** (imparts
"beginning of an action" — its usual verbal meaning, not "behind/after"), and **`na-`** (most complex:
alone, "a portion of the action brought to completion"; combined with `se`, "action carried through to
total satiation," e.g. `nàpiti se` "drink one's fill," `nàjesti se` "stuff oneself"). `pre-` and `pro-`
don't map to one preposition but share meanings of `preko`. Multi-prefix verbs exist (`izòstati` "be
missing" < `iz-` + `o-` + `stati`) with harder-to-decompose combined meanings. **This prefix-meaning
system is directly relevant to any later synthesized-slang derivational-morphology work** — prefixal
semantic shift is exactly the kind of productive mechanism a derived slang lexicon could exploit.

### §146c–147. Aspect-pair typology: simplex, prefixal, and derived-imperfective

A three-way typology of how perfective/imperfective partners relate formally, useful reference beyond
lesson-level "verbs come in aspect pairs":

1. **Simplex pairs** — neither partner prefixed; differentiated by suffixation/theme-vowel/stem changes
   alone (e.g. `bàciti` (P) / `bàcati` (I) "throw"). Typically type-2 perfective paired with type-1
   imperfective, sometimes type-7 perfective (with the characteristic `-n-` marker) paired with type-1
   imperfective.
2. **Prefixal pairs** — perfective formed by adding an unpredictable prefix to an otherwise-unchanged
   imperfective (`kùpati` → `okùpati` "bathe"). The prefix's identity must be memorized per verb.
   A subtype: prefixing an *existing* simplex pair to derive a *new*, more specific pair sharing the
   same aspectual mechanism (`pasti`/`padati` "fall" → `dòpasti se`/`dòpadati se` "be pleasing,"
   `nàpasti`/`nàpadati` "attack," etc. — same base pair, seven+ distinct derived meanings).
3. **Derived imperfectives** ("iterative imperfectives" in older terminology) — when a prefix changes
   a verb's meaning by more than just adding perfectivity, a *new* imperfective partner must be
   suffixally derived for it (it cannot simply reuse the original durative imperfective). Marked by a
   long-rising vowel immediately before the theme vowel; the two commonest suffixes are `-iva-` (type
   8b, present in `-uj-`) and `-ava-` (type 9, present in `-aj-`). Illustrated with "verb nests" — one
   durative imperfective spinning off multiple prefixed-perfective + derived-imperfective triples, e.g.
   `pìsati` → `napìsati` (write down, no derived imperfective needed — durative already covers it) /
   `opìsati`→`opisìvati` (describe) / `potpìsati`→`potpisìvati` (sign) / `prepìsati`→`prepisìvati`
   (copy) / `propìsati`→`propisìvati` (issue/regulate). Bi-aspectual verbs (single form serving both
   aspects, e.g. `vidjeti`/`videti` "see") still form a distinct *iterative* imperfective (`viđati`)
   when true repetition needs marking, distinct from the bi-aspectual form's momentary/durative
   double duty.

### §148. Verbal nouns in `-će` — an abstract-result noun type not in the lesson files

Beyond the productive `-nje` verbal noun (process/result, reviewed from earlier lessons), a smaller,
closed set of verbs (types 6, 7, 11, and type-15b verbs with the alternate `-nuti` infinitive, plus
type-8 verbs in `-vovati`) form a *result-only* (never process) noun in `-će`, always with a long
vowel before the suffix: `òtkriti` → `otkrìće` "discovery," `piti` → `pìće` "a drink," `podùzeti` →
`poduzèće` "firm/company," `ùčestvovati` → `ùčešće` "participation." Genuinely distinct lexical
resource for any later "make new abstract nouns" mechanics.

### §149–150. Compound and simplex tense paradigms, review — consolidated reference tables

Useful because the textbook's lesson-by-lesson introduction never assembles all six compound tenses
side by side. Full paradigm comparison (1sg.–3pl., model verb `ìći`):

| | first future | compound past | conditional | exact future |
|---|---|---|---|---|
| 1sg. | ìći ću | ìšao sam | ìšao bih | budem ìšao |
| 2sg. | ìći ćeš | ìšao si | ìšao bi | budeš ìšao |
| 3sg. | ìći će | ìšao je | ìšao bi | bude ìšao |
| 1pl. | ìći ćemo | ìšli smo | ìšli bismo | budemo ìšli |
| 2pl. | ìći ćete | ìšli ste | ìšli biste | budete ìšli |
| 3pl. | ìći će | ìšli su | ìšli bi | budu ìšli |

Two additional, rarer compound tenses use *compound* auxiliaries: the **past conditional** (`bio bih
ìšao` — L-participle of *biti* + conditional auxiliary + main-verb L-participle) and the
**pluperfect** (`bio sam ìšao` [compound-past auxiliary] or archaic `bijah ìšao` [imperfect
auxiliary]). Both are more common in Croatian spoken usage and throughout BCS in literary prose than
in everyday Bosnian/Serbian speech, which prefers to convey the same meaning through aspect/context
instead.

The **aorist** and **imperfect** simplex tenses (heard rarely in speech, essential for reading older/
literary texts) get their fullest formal treatment here: aorist for types 1–11 is formed by dropping
infinitival `-ti` and adding aorist endings directly; types 13–16 form it from the 3pl. present stem
(`-e` in 2-3sg., triggering Type B softening in type 15a; `-o` elsewhere). A small closed set of high-
frequency type-1 verbs (`dati`, `stati`, `znati`, `imati`, `smjeti`) has an *alternate* archaic aorist
built on a `-d-`-stem model (`dadoh`, `znadoh`, `ìmadoh`, `smjedoh`) that also feeds a secondary
e-conjugation present (`znadem`, `imadem`) and imperfect. The imperfect uses a long-`a` theme vowel +
endings `-h, -še, -smo, -ste, -hu`; verbs in `-ati` (types 1, 4-5, 8-10) drop `-ati` and add directly,
other types build from the 3pl.-present stem (with Type C softening for types 2-3, 7, 13-16); a
longer variant imperfect with inserted `-ij-` exists for types 2, 10-15.

### §151. Literary tense use in 19th-century narrative prose — genuinely new content

Beyond the modern-language backgrounding/foregrounding-via-aspect system (§145c), older BCS literary
prose used *tense* choice (not just aspect) to mark foreground vs. background: the **aorist** sharply
marked foregrounded action, the **imperfect** marked backgrounded action tied to a specific narrative
time-window, and the **compound past** outlined more diffuse, variably-focused background (roughly
like the English present perfect in force — results still relevant at speech time). Illustrated at
length with annotated excerpts from Ksaver Šandor Đalski's *Na groblju*, Laza Lazarević's *Prvi put s
ocem na jutrenje*, Vuk Karadžić's 1847 New Testament translation, and a Bosnian *sevdalinka* — useful
if the project's later phases ever need to model a "high literary register" tier distinct from
colloquial slang for this language.

### §152. Verb-form inventory — organizing chart

A single categorization chart groups every BCS verb form by syntactic category: `[noun]` = infinitive
+ verbal noun; `[verb]` = present/aorist/imperfect (each with 1-3sg./1-3pl. slots) + the three
imperative forms (singular/plural/inclusive); `[adjective]` = L-participle + passive participle (each
with 6 gender/number slots); `[adverb]` = present + past verbal adverb. Perfective verbs systematically
lack imperfect-tense forms and usually lack present verbal adverbs and verbal nouns; imperfective verbs
often lack past verbal adverbs and sometimes passive participles.

### §153. Full verb paradigms — the headline new content of this chunk

The book gives a complete form-set (infinitive, verbal noun, 6-person present, 6-person aorist,
6-person imperfect, 3-form imperative, 6-form L-participle, 6-form passive participle, present +
past verbal adverb) for one representative verb of **each of the 16 conjugation types**, plus the two
irregular auxiliaries `hteti/htjeti` and `biti`. This is exactly the "full-paradigm reference table in
one place" that the lesson-based textbook, by its incremental design, never assembles. Representative
verbs and each type's genuinely distinctive formation quirk (paraphrased, not the full tables — see
copyright discipline):

| Type | Model verb | Distinctive formation note |
|---|---|---|
| 1 | `gledati` | Most regular type; imperative stem in `-j` with lengthened preceding vowel; `dati`/`znati`/`imati` have archaic alternate simplex-tense forms on a type-13 model (`dadem`, `znadem`, `imadem`) |
| 2 | `nòsiti` | Type C softening in verbal noun/passive participle/imperfect without exception |
| 3 | `videti`/`vidjeti` | Small set of high-frequency + derived "quality" verbs; ekavian/ijekavian differ in infinitive, past verbal adverb, aorist, L-participle |
| 4 | `dr̀žati` | Stems in `-ž,-č,-j,-žd,-št`; rising accent throughout; `stajati` has a suppletive present stem `stojim` |
| 5 | `pìsati` | Type C softening across present/imperfect/imperative/present verbal adverb; `slati` is a three-way type-5/10/6 hybrid |
| 6 | `piti` | Monosyllabic roots (`-i-` or `-u-`); passive participle varies `-t`/`-ven`/`-jen` |
| 7 | `krènuti` | `-ne-`/`-nu-` markers signal punctual/momentary meaning; many verbs share alternate forms with type 15b |
| 8a | `kupòvati` | `-ova-` → `-uj-` in present/imperative/present-verbal-adverb; monosyllabic roots may alternate `-uva-`/`-ova-` in the infinitive |
| 8b | `kazìvati` | Formally identical to 8a but with `-iva-`; always a **derived imperfective** (§147c), so never has a past verbal adverb |
| 9 | `dàvati` | Derived imperfectives of `dati`/`znati` only; `-ava-` → `-aj-` |
| 10 | `brati` | Inserted vowel in present/imperative/present-verbal-adverb (`-e-` most common, also `-o-` as in `zvati`, `-a-` as in `slati`) |
| 11 | `ùzeti` | Infinitive stem in `-e`/`-u`, present stem adds consonant `-m-`/`-n-`/`-p-`; mostly perfective, usually lack imperfect forms |
| 12 | `ùmeti`/`ùmjeti` | Differentiates ekavian/ijekavian throughout every paradigm slot, unlike type 3's more limited split |
| 13 | `jesti` | Stem-final `-d`/`-t` → `-s` in infinitive, lost in L-participle; imperfect has a softened and unsoftened variant |
| 14 | `tresti` | Varied stem-final consonants (`-s`,`-z`,`-b`); `-nes-` root has ekavian/ijekavian infinitive+L-participle split (`doneti`/`donijeti`) |
| 15a | `teći` | Stems in `-k`/`-g` (rarely `-h`); Type A softening in imperative/imperfect, Type B in passive participle/verbal noun/most present forms |
| 15b | `stići` | Shares alternate type-7 forms (`stignuti`) alongside its own type-15a-style past-tense forms; `pasti`/`sesti`-`sjesti` also partly follow this pattern |
| 16 | `dòći` | Restricted to `ići` and its prefixed derivatives; stem-final `-đ` → `-š` in L-participle |
| — | `hteti`/`htjeti` | Distinct clitic/full/negated present-tense triads (`ću`/`hòću`/`nèću`); clitic forms mean future only, full forms mean future-or-want, remaining forms mean want only |
| — | `biti` | Clitic/full/negated present triads (`sam`/`jesam`/`nìsam`) plus the fully separate `budem`-series used after subordinating conjunctions and in the exact future; Montenegro-area expanded negated variants (`nijesam`, etc.) noted |

---

## Copyright discipline reminder

All example sentences and paradigm cells above are paraphrased summaries or minimal illustrative
fragments (single words/short forms), not bulk reproduction of the source's full tables, dialogue
blocks, or explanatory prose. Page/section citations are given so a future reader can go back to the
source for the full paradigm tables, which were deliberately not transcribed cell-by-cell in every
case (only the distinguishing/irregular cells are called out per type) per the extraction spec's
copyright discipline rule.
