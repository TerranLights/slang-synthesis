# Serbian/Croatian/Bosnian — Established Grammar: Lila Hammond, *Serbian: An Essential Grammar*, Chapter 8 — Pronouns

**Source:** Lila Hammond, *Serbian: An Essential Grammar* (Routledge, 2005), Chapter 8 "Pronouns"
(§§8.1–8.7: personal, reflexive, possessive, demonstrative, relative, interrogative, universal
pronouns), printed pp. 178–200 (PDF pages 193–215 of the source file; printed-page numbering is
offset from PDF-page numbering by 15 pages of front matter, confirmed via `pdftotext -layout`
search for "Chapter 8"/"Chapter 9" heading text). This is a third, Serbian-specific reference book
for this language (as opposed to the comparative Bosnian/Croatian/Serbian sources already used
elsewhere in this dataset), and the only one of the three that prints Cyrillic alongside Latin
script throughout.

**Coverage note.** Source has a real text layer (`pdftotext -layout` produced clean output — no
vision-reading was needed). **A PDF-extraction gotcha specific to this book: its Cyrillic text is
garbled by `pdftotext`** — the font's Cyrillic glyphs extract as visually unrelated Latin/symbol
characters (e.g. "ja" prints as "√f", "on" as "jy") rather than actual Cyrillic codepoints. The
book's own parallel Latin-script line for every example is unaffected and fully legible, so this
file uses **only the Latin-script forms** throughout (consistent with the dispatch instruction to
treat Latin as the primary Term) and does not attempt to reproduce the garbled Cyrillic. Vocabulary
already established from the flagship textbook (`003_lesson01_complete.md` etc. — the six basic
personal pronouns ja/ti/on-ona-ono/mi/vi/oni) is **not** re-listed as vocabulary rows here; this
file focuses on the pronoun categories/lexical items not previously captured (reflexive, possessive,
demonstrative, relative, interrogative, universal pronouns) and on grammar points, including
declension tables for the basic personal pronouns, that are genuinely new even where the base word
was already known.

**Relationship to prior extraction (clitic-ordering check).** The dispatch flagged §8.1.4 "Order of
unstressed personal pronouns" as a likely overlap with the "XYZ model" of clitic *placement*
already extracted from `037_grammar_ch1-3_supplementary.md` (Ch. 1 §12a-b) and the full
rhythmic-constituent apparatus in `044_grammar_ch19_clitic_accent.md` (Alexander, Ch. 19). On
inspection, **these are complementary, not duplicate, content**: the Alexander-derived files cover
*where in the sentence* the clitic cluster goes (the X-Y-Z / rhythmic-constituent model, and that
`li` comes first within the cluster) but neither file spells out the **internal ordering among the
pronominal-enclitic case forms themselves** when two or more co-occur (dative before genitive
before accusative). Hammond's §8.1.4 gives exactly that missing piece, plus a specific
accusative-clitic allomorphy rule (`ju` vs. `je`) not found in either prior file. **Kept as
genuinely new.** Everything else in §8.1 (personal-pronoun declension tables, stressed/unstressed
distinction, usage contexts) is also kept, since neither prior extraction covers the full personal
pronoun paradigm table. The basic definitional material at the chapter's opening (the 10-way
pronoun taxonomy, which categories "behave as nouns" vs. "replace adjectives/numbers") is
paraphrased briefly rather than reproduced at length, since it is organizational scaffolding rather
than new grammar content.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| sebe / se | oneself (reflexive pronoun; se = enclitic acc. form) | pronoun (reflexive) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §8.2, p.186; sebe has no person/gender/number marker and no Nom./Voc.; enclitic se exists only in Acc. (occasionally Gen.) |
| sam | oneself (emphatic reflexive, used with sebe) | pronoun (reflexive, emphatic) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §8.2, p.186-187; unlike sebe, sam has gender and number and declines as an adjective (sam/samo/sama, sami/sama/same) |
| moj / moje / moja | my, mine | pronoun (possessive) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §8.3, p.189; declines like an indefinite/definite adjective; genitive/dative/locative show alternate short/long forms (mog(a)/mojeg(a), mom(e)/mojem(u)) |
| tvoj / tvoje / tvoja | your (sg.), yours | pronoun (possessive) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §8.3, p.189; declines like moj |
| svoj / svoje / svoja | one's own (reflexive possessive) | pronoun (possessive, reflexive) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §8.3, p.189-190; used specifically when the possessed object belongs to the sentence's own subject (contrast njegov); cannot stand without a subject to trace back to |
| naš / naše / naša | our, ours | pronoun (possessive) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §8.3, p.189; declines like moj but takes soft-consonant endings -eg(a)/-em(u) instead of -og(a)/-om(e) |
| vaš / vaše / vaša | your (pl./formal), yours | pronoun (possessive) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §8.3, p.189; same soft-ending pattern as naš |
| njegov / njegovo / njegova | his | pronoun (possessive) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §8.3, p.189-191; 3rd-person possessives decline as both indefinite and definite adjectives (definite more frequent) |
| njen/njezin (njeno/njezino, njena/njezina) | her, hers | pronoun (possessive) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §8.3, p.189-191; njen and njezin are given as free variants throughout the paradigm (no regional tag given by the source) |
| njihov / njihovo / njihova | their, theirs | pronoun (possessive) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §8.3, p.189 |
| taj / to / ta | that (one) | pronoun (demonstrative) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §8.4, p.192-193; base demonstrative referring to the 2nd person/listener's proximity, or a previously-referenced item; declension paradigm given in full |
| ovaj / ovo / ova | this (one, near speaker) | pronoun (demonstrative) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §8.4, p.192-193; declines like taj; refers to 1st-person/speaker's own proximity |
| onaj / ono / ona | that (one, far/3rd person) | pronoun (demonstrative) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §8.4, p.192-193; declines like taj; refers to 3rd person or a more distant location |
| takav / takvo / takva | such, like that | pronoun (demonstrative, qualitative) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §8.4, p.193-194; declines like an indefinite adjective; full declension table given |
| ovakav / ovakvo / ovakva | such, like this | pronoun (demonstrative, qualitative) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §8.4, p.192; parallels takav for near-deixis |
| onakav / onakvo / onakva | such, like that (over there) | pronoun (demonstrative, qualitative) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §8.4, p.192; parallels takav for far-deixis |
| toliki / toliko / tolika | that big/that much | pronoun (demonstrative, quantitative) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §8.4, p.192 |
| ovoliki / ovoliko / ovolika | this big/this much | pronoun (demonstrative, quantitative) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §8.4, p.192 |
| onoliki / onoliko / onolika | that big/that much (over there) | pronoun (demonstrative, quantitative) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §8.4, p.192 |
| isti / isto / ista | the same | pronoun (demonstrative) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §8.4, p.193 |
| ko | who? / who (relative) | pronoun (relative/interrogative) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §8.5/§8.6, p.195,198; masculine singular, applicable to humans only; declines (full paradigm given) |
| šta | what? / what (relative) | pronoun (relative/interrogative) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §8.5/§8.6, p.195,198; neuter singular, applicable to inanimate nouns; declines |
| (ono) što | that which (relative) | pronoun (relative) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §8.5, p.195,197; indeclinable; as an interrogative separately means "why?" (short for zašto) — §8.6, p.197 |
| koji / koje / koja | which | pronoun (relative/interrogative) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §8.5/§8.6, p.195-196,198; has number/gender/case; declines like a definite adjective; full paradigm given |
| čiji / čije / čija | whose | pronoun (relative/interrogative) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §8.5/§8.6, p.195,198; declines like koji |
| kakav / kakvo / kakva | what kind/quality of | pronoun (relative/interrogative) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §8.5/§8.6, p.196-198; declines like an indefinite adjective; full paradigm given |
| koliki / koliko / kolika | what size/extent of | pronoun (relative/interrogative) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §8.5/§8.6, p.195,198 |
| svako | everybody, everyone | pronoun (universal) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §8.7, p.199; masculine singular, applicable to animates only, declines like a definite adjective; verbs used with it are singular |
| svašta | all kinds of things | pronoun (universal) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §8.7, p.199; neuter singular, declines like šta; also idiomatically means "Really!/Nonsense!" |
| svaki / svako / svaka | every, everybody | pronoun (universal) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §8.7, p.199; the neuter form overlaps in meaning with svako |
| svačiji | everybody's | pronoun (universal) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §8.7, p.199; declines like čiji |
| svakakav | all kinds/types of | pronoun (universal) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §8.7, p.199; declines like kakav; carries a critical/dismissive connotation about the noun's quality per the source's own gloss |
| svi | everybody, all | pronoun (universal) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §8.7, p.199-200; plural-only, has case and gender; verbs used with it are plural |
| sve | all, everything | pronoun (universal) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §8.7, p.199-200; refers to inanimate/mass reference; verbs used with it are singular; full declension paradigm given (dat./inst./loc. show svim/svima variation) |

## Grammar points

### 8.1 Personal pronouns — overview and omission

Personal pronouns mark gender only in the 3rd person (singular and plural each have distinct
masculine/feminine/neuter forms); 1st and 2nd person pronouns are gender-neutral. Because tense
formation (with its person/number/gender-marked auxiliary and participle) already encodes the
subject, personal pronouns are frequently dropped as subject — both in main clauses and in
subordinate clauses when the subject is unchanged/already established from context (p.180-181).
2nd person plural `vi`/capitalized `Vi` is used both for a genuine plural addressee and, singular,
as a formal/respectful address to one person; when a past-tense verb follows a formal-singular
`Vi`, the past participle still takes 2nd-person-plural masculine agreement regardless of the
addressee's actual gender (p.180).

### 8.1.1 Declension of personal pronouns

1st/2nd person (singular and plural) pronouns and the reflexive pronoun se decline like feminine
`-a` nouns (the kuća pattern) in Gen./Dat./Loc./Inst., with no vocative form. 3rd person personal
pronouns (on/ona/ono, oni/one/ona) instead follow the pronominal declension: masculine and neuter
singular forms are identical except in the nominative; across all three genders, the plural
Gen./Acc. forms coincide, and the Dat./Inst./Loc. plural forms coincide (p.181-183) — the same
syncretism pattern documented for regular nouns elsewhere in this dataset, here shown to extend to
pronominal declension too.

### 8.1.2 Stressed (long) personal pronouns

Stressed forms exist for Gen./Dat./Acc. (and a long Inst. form); they can occupy almost any
sentence position and are required specifically: (1) sentence-initially, (2) after the conjunctions
`a`, `i`, `ni`, (3) after a preposition governing dative or genitive, (4) for emphasis/contrast
(p.182-183). The 1st-person and all 3rd-person instrumental-singular forms have two long variants —
a short-looking one (`mnom`, `njim`, `njom`) that is nonetheless not an enclitic and is typically
used with a preposition, and a longer one (`mnome`, `njime`, `njome`) typically used without a
preposition (p.183).

### 8.1.3 Unstressed (enclitic) personal pronouns

The short Gen./Dat./Acc. forms are pronominal enclitics; they cannot begin a sentence and cannot
ordinarily follow a preposition or the conjunctions `i`/`a`, and must follow the general enclitic
word order (cross-referenced by the source to its own Chapter 13 "Enclitics," not part of this
extraction chunk). Feminine accusative has two enclitic allomorphs, `ju` and `je`: **`ju` is used
specifically when the pronominal enclitic is immediately followed by the auxiliary enclitic `je`
("is"), or when the preceding word itself ends in `-je`** — otherwise `je` is used (avoiding a
`je...je` clash: `Ona ju je kupila` "She bought it," not the ambiguous `*Ona je je kupila`, p.184).
Masculine/neuter accusative also has two enclitic forms: `ga` is the default; `nj` is used only
after a preposition governing the accusative, and pulls the stress from the pronoun onto the
preposition itself (p.184-185) — a small-scale instance of the same accent-retraction-onto-a-
preposition mechanism documented at greater depth (and cross-dialectally) in `044`'s §166c.

### 8.1.4 Order of unstressed personal pronouns

**Genuinely new relative to prior extractions** (see coverage note above): when two or more
pronominal enclitics co-occur, they must appear in the fixed order **dative → genitive →
accusative** (p.184-185). Worked examples: `Kupila mu ju je` ("She bought it for him," dat. `mu`
before acc. `ju`); `Dao joj ga je` ("He gave it to her," dat. `joj` before acc. `ga`); `Sećaš li je
se?` ("Do you remember it?," using the genitive-governed enclitic, since the verb `sećati se`
governs genitive). The source notes genitive-case pronominal enclitics specifically occur with verbs
that themselves take the genitive case (p.185). This is an ordering rule *internal to* the
pronominal-enclitic cluster itself, distinct from (and not covered by) the X-Y-Z placement model
already documented in `037`/`044`, which governs where the whole clitic cluster sits in the
sentence rather than the sequence of case-forms within it.

### 8.2 Reflexive pronouns

`sebe`/enclitic `se` express true reflexivity (subject acts on itself) and reciprocity ("each
other" — e.g. `Džon i Anka se vole`, "John and Anka love each other," p.187). `sebe` has no
person/gender/number and no Nom./Voc. case; its enclitic `se` exists only in the accusative
(occasionally genitive). The emphatic reflexive `sam` ("oneself") pairs with either the long or
short form of `sebe` and, unlike `sebe`, does have gender and number, declining as an adjective
(p.186-187). Usage breakdown by case function: direct object (accusative, no preposition, both
long/short forms); indirect object (all cases but accusative, long form only); after prepositions
(all cases, long form only) (p.186-187).

### 8.3 Possessive pronouns

Possessive pronouns behave grammatically as adjectives in Serbian ("adjectives and pronouns" per
the source's own terminology), agreeing in case/number/gender with the noun they modify — cross-
referenced by the source to its own §9.2 (indefinite adjectives) and §9.3 (definite adjectives),
not part of this extraction chunk. 1st/2nd person possessives (moj, tvoj, naš, vaš, and reflexive
svoj) decline as definite adjectives; 3rd person possessives (njegov, njen/njezin, njihov) decline
as either indefinite or definite adjectives, with definite forms more frequent (p.188-189). The
reflexive possessive `svoj` ("one's own") is used specifically when the possessed item belongs to
the sentence/clause's own subject; `On voli svoju ženu` ("He loves his (own) wife") contrasts with
`On voli njegovu ženu` ("He loves his [someone else's] wife") — the latter leaves open that the
wife belongs to a third party, not the subject (p.189-190). A possessive pronoun cannot stand
without a subject to anchor it to (illustrated with an ungrammatical `*On i svoja žena su bili na
večeri`, since "his own" has no antecedent subject when `on` and the possessive share the same
clause without a valid referent, p.190), and can be dropped entirely when ownership is contextually
obvious (`On i žena su bili na večeri`, "He and [his] wife went to dinner," p.190).

### 8.4 Demonstrative pronouns

Demonstratives encode a three-way deictic distinction tied to grammatical person: `ovaj` (this,
near 1st person/speaker), `taj` (that, tied to 2nd person/listener or an already-referenced item),
`onaj` (that, more distant, tied to 3rd person) — the same three-way split extends to compound
demonstratives built on these stems for manner (`ovakav`/`takav`/`onakav`, "such/like this/that")
and extent (`ovoliki`/`toliki`/`onoliki`, "this/that big"). `ovo`, when followed by a verb, functions
like English "this is" (`Ovo je naša soba`, "This is our room," p.191-192). `onaj`/`ovaj` decline
like `taj`; the manner-demonstratives decline like indefinite adjectives (p.192-194).

### 8.5 Relative pronouns

Seven relative pronouns split into two declension groups: (1) `ko` (who, masc. sg., humans only)
and `šta`/`(ono) što` (what/that which, neut. sg.) — `ko` and `šta` decline via their own paradigm
(distinct from, though related to, the interrogative paradigm below); `što` does not decline; (2)
`koji` (which), `čiji` (whose), `kakav` (what kind/quality), `koliki` (what size/extent) — these
carry number/gender/case and decline like definite (`koji`, `čiji`) or indefinite (`kakav`,
`koliki`) adjectives respectively (p.194-197).

### 8.6 Interrogative pronouns

Formally identical in inventory to the relative pronouns (`ko`, `šta`, `koji`, `čiji`, `kakav`,
`koliki`), with one semantic split: `što` as an interrogative instead means "Why?" (a contracted
form of the adverb `zašto`), unlike its relative-pronoun sense "that which" (p.197). Per-pronoun
verb-agreement notes: `ko` triggers a singular verb except with `biti` ("to be"), which may be
singular or plural; `šta` always triggers a singular verb; `koji`/`čiji`/`kakav`/`koliki` may trigger
either singular or plural verb agreement depending on the referent's actual number (p.197-198).

### 8.7 Universal pronouns

Seven universal pronouns, each with its own declension-class assignment and animacy restriction:
`svako` (everybody, animate-only, masc. sg., declines as definite adjective, singular verb
agreement); `svašta` (all kinds of things, inanimate, neut. sg., declines like `šta`; also an
idiomatic exclamation "Really!/Nonsense!"); `svaki` (every/everybody, both animacies, normally
singular, neuter form overlapping with `svako`); `svačiji` (everybody's, both animacies, declines
like `čiji`); `svakakav` (all kinds/types, both animacies, declines like `kakav`, carrying a
critical/dismissive connotation per the source's own gloss); `svi` (everybody/all, plural-only,
plural verb agreement, refers to quantity); `sve` (all/everything, inanimate, singular verb
agreement) (p.198-200). `sve`/`svi` have their own declension table with a Dat./Inst./Loc. plural
allomorphy (`svim`/`svima` both attested, no stated register/regional distinction between the two).

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`.
