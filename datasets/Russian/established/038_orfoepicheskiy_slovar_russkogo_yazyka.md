# Russian — Established Vocabulary/Grammar: Pronunciation/Stress Sampling Across the Alphabet

**Source:** С. Н. Борунова, В. Л. Воронцова, Н. А. Еськова (под ред. Р. И. Аванесова),
*Орфоэпический словарь русского языка: произношение, ударение, грамматические формы* [*Orthoepic
Dictionary of the Russian Language: Pronunciation, Stress, Grammatical Forms*], 4th stereotype
edition, Moscow, "Русский язык," 1988. ~63,500 headwords. Representative sample drawn from pages
21, 30, 100, 180, 220, 260, 300, 340, 380, 420, 460, 500, 540, 580, 620, 650, and the phonological
appendix at pp. 665–702 (§§ 169–176 read directly, in Roman-numeral djvu page ≈680).

**Coverage note:** This is a large, single-purpose reference dictionary (pronunciation/stress norms
only, no bilingual glossing, no example sentences to speak of) — per the coverage rule's own carve-
out for large reference dictionaries, this file uses **representative sampling across the
alphabet** rather than exhaustive transcription. Roughly one full two-column dictionary page was
read per major letter-region (А, Н, К, П×2, Т, plus a scattered accent-mark spot-check on Р/С via
the text layer), selecting entries with genuinely informative stress/pronunciation content —
variant stresses, "incorrect"-vs-"recommended" stress pairs, non-obvious soft/hard consonant
notations, and homographs distinguished only by stress or pronunciation — over routine entries.
This is deliberately a much smaller slice than the ~63,500-word dictionary as a whole; it is meant
to characterize the *kind* of phonological/normative information this source records, not to
enumerate its contents.

**Critical extraction gotcha — stress marks are entirely absent from the DjVu text layer.**
`djvutxt` on this file produces clean, correctly-decoded Cyrillic (verified against 20+ known
words — no font-substitution cipher, unlike several other Russian sources in this corpus) with
correct paragraph/entry structure. However, the printed dictionary marks stress with a combining
acute accent over the stressed vowel — the single most important piece of information in a
*pronunciation* dictionary — and this diacritic is **silently dropped by `djvutxt` on every single
entry** (confirmed via codepoint-by-codepoint inspection of extracted text: no combining accent
character, U+0301 or otherwise, survives anywhere in the output). This is a new variant of gotcha
#3 in `00_Reference_Extraction_Spec.md` ("stress-mark-only corruption") but stronger: not corrupted
into a stray artifact, just **completely erased**, with no textual trace that a mark was ever
there. **Fix used here:** rendered specific pages to PNG images via `ddjvu -format=ppm` (converted
to PNG with Pillon/PIL, since `ddjvu` has no native PNG output and ImageMagick was unavailable) and
read stress placement directly from the page images. All vocabulary rows below reflect
vision-confirmed stress; the source's own bracketed pronunciation annotations (soft/hard consonant
notation, e.g. `[дэ]`, `[сьть]`) come through cleanly in the text layer and did not need
vision-reading, except where a superscript-letter softness marker (e.g. a raised **ь** over a
consonant, rendered in print as a breve-like diacritic) was cross-checked against the image because
`djvutxt` renders these inconsistently (sometimes as literal `[cᵇmᵇ]`-style superscripts, sometimes
as corrupted symbol soup like `[<^иь]` — this second form was **not** used for extraction; only
image-verified readings were kept). **Any future extraction from this same source must render page
images rather than trust the raw text layer for anything stress-related** — text-layer-only
extraction from this book would silently produce a stress dictionary with no stress information at
all, which would defeat the source's entire purpose.

**No handwritten marginalia observed** on any of the sampled/rendered pages — this appears to be a
clean library/scan copy with only printed content.

**Symbols and abbreviations used below** (per the dictionary's own "Условные сокращения" front
matter, pp. 13–20, and its notation key): `!` = a following form is **неправ.** (incorrect,
non-normative) or **не рек.** (not recommended); `доп.` = admissible/acceptable variant; `△`
(printed as a triangle in-source) introduces additional inflected forms with their own
pronunciation note; `□` introduces a brief sense-disambiguating gloss for homographs; `⋄` introduces
a fixed idiomatic phrase. Bracketed notation like `[дэ]`, `[сэ]`, `[ре]` marks that a normally
soft/iotated consonant before this particular instance of `е` is pronounced **hard** (a loanword
feature); bracketed notation with a raised **ь** (e.g. `[сьть]`) marks a **soft**-consonant cluster
pronunciation for a written combination that might otherwise be read hard.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| аргуме́нт (loc. sg. аргуме́нте) | argument | noun, m. | core | — | contemporary (source published 1988) | — | — | dictionary | n/a | verified | Dictionary flags `! неправ. а́ргумент` — stress-on-first-syllable is explicitly marked incorrect; correct is final-syllable-stressed аргуме́нт. Classic norm-vs-common-error pair. |
| арбу́з (gen. pl. арбузо́в) | watermelon | noun, m. | core | — | contemporary (source published 1988) | — | — | dictionary | n/a | verified | Two flagged non-normative forms at once: `! неправ. арбуза́` (wrong gen.sg. stress) and `неправ. а́рбуз` (wrong nominative stress) — shows the dictionary tracking mis-stressing at multiple points in a single paradigm. |
| апелля́нт (loc. sg. апелля́нте) | appellant (legal) | noun, m. | technical.legal | — | contemporary (source published 1988) | — | — | dictionary | n/a | verified | Bracketed `[льть]`-type note marks the soft-л/soft-cluster pronunciation of the stem before the locative ending; source's own `Л`-style additional-forms marker used to show the declined form's own separate pronunciation note. |
| апо́лог / аполо́г | fable, allegorical tale | noun, m. | literary | — | contemporary (source published 1988) | — | — | dictionary | n/a | verified | Listed with two co-equal accepted stress positions (`и`-conjunction between the two headword spellings-with-stress, not a normative/non-normative pair) — a genuine free-variation case, distinct from the неправ./не рек. pairs elsewhere. |
| аре́довы ве́ки | as old as Methuselah / ancient (idiom) | idiomatic phrase | archaic | — | contemporary (source published 1988); idiom itself far older | — | — | dictionary | n/a | verified | Fixed idiomatic collocation `аре́дов: аре́довы ве́ки` — headword listed under the otherwise-unused possessive-adjective form аре́дов, only ever occurring in this phrase (biblical/legendary-longevity reference). |
| ток¹ | (electric) current; flow (of liquid/gas) | noun, m. | technical.physics | — | contemporary (source published 1988) | — | — | dictionary | n/a | verified | One of 4 same-spelled headwords (ток¹⁻⁴) distinguished purely by sense via `□`-marked glosses; ток¹ takes optional partitive genitive `род.₂ -у`. |
| ток²⁻³ | threshing floor; place where birds display/mate (lekking ground) | noun, m. | core / technical.agriculture | — | contemporary (source published 1988) | — | — | dictionary | n/a | verified | Same spelling as ток¹ but distinct declension note (`предл.₂ на току́`, `мн. тока́, -о́в` — stress shifts to the ending in the plural, unlike ток¹); shows the dictionary using inflectional-stress-pattern differences, not just semantics, to keep homographs apart. |
| ток⁴ | a type of headwear (a toque) | noun, m. | technical.clothing | — | contemporary (source published 1988) | — | — | dictionary | n/a | verified | Fourth homograph in the same entry cluster, plural `-и, -ов` (unlike ток²⁻³'s `-а́, -о́в`) — again disambiguated by paradigm shape as much as gloss. |
| то́, союз | that / so that (conjunction, weak-stress use) | conjunction | core | — | contemporary (source published 1988) | — | — | dictionary | n/a | verified | Explicit phonological note: "Произносится без удар. и без редукции" (pronounced without stress and without vowel reduction) — one of several function words the dictionary marks as normally stress-less in running speech even though the headword itself carries a citation-form stress mark. |
| то́, частица | that (particle, weak-stress use) | particle | core | — | contemporary (source published 1988) | — | — | dictionary | n/a | verified | Separate homograph entry from the conjunction above, same "Произносится без удар." note. |
| тка́ть (impf.) | to weave | verb, impf. | core | — | contemporary (source published 1988) | — | — | dictionary | n/a | verified | `! не рек. ткало́` — flags the theoretically-possible neuter past-tense stress ткало́ as not recommended (standard is тка́ло, root-stressed), an example of the dictionary policing verb past-tense stress-shift patterns. |
| проли́ть (pf.) | to spill, to shed (blood/tears) | verb, pf. | core | — | contemporary (source published 1988) | — | — | dictionary | n/a | verified | Extensive past-tense paradigm with a stress-mobile pattern: проли́л/пролила́/про́лило/проли́ло (both neuter variants accepted)/проли́ли — feminine past tense shifts stress to the ending (a common Russian verb-stress-mobility pattern) while other forms stay root-stressed; also flags `не рек. проли́та`/`не рек. проли́та` (short-form participle stress) vs `неправ. проли́ла` for the wrong form entirely. |
| не́льма / не́льмовый | nelma (a whitefish, *Stenodus leucichthys*) / adj. of the same | noun, f. / adjective | technical.zoology | — | contemporary (source published 1988) | — | — | dictionary | n/a | verified | Bracketed `[нэ и не́]` shows both a hard- and soft-н pronunciation of the -не- syllable are accepted, independent of the stress question — one of several loanword-style hard/soft consonant variants recorded alongside stress. |
| нена́висть | hatred | noun, f. | core | — | contemporary (source published 1988) | — | — | dictionary | n/a | verified | `! неправ. не́навись` flagged directly beneath the headword — a first-syllable-stress error common enough to warrant explicit correction. |
| немудрёный / немудрено́ | uncomplicated, simple / it's no wonder (predicative) | adjective / predicative | core | — | contemporary (source published 1988) | — | — | dictionary | n/a | verified | Short-form paradigm shows a stress-position split across forms: немудрён, немудрена́, немудрено́, немудрены́ (and a `доп. устар.` — admissible-archaic — alternate немудрёна/немудрено/немудрены with fixed root stress) alongside the separate adverbial/predicative form немудрено́, illustrated in-source with the example «Употр. с инф. Запу́таться немудрено́» (paraphrased, not quoted at length). |
| ко́нюх (gen. pl.) | groom, stableman | noun, m. | core | — | contemporary (source published 1988) | — | — | dictionary | n/a | verified | `! не рек. мн. конюха́, -о́в` — flags the colloquially-common end-stressed plural конюха́ as not recommended; standard plural is initial-stress ко́нюхи. |
| копна́ | haystack, shock (of grain) | noun, f. | core | — | contemporary (source published 1988) | — | — | dictionary | n/a | verified | Genitive plural given with two accepted stress variants (копён and допcopен — final-syllable both ways) plus a stress-shifted accusative singular ко́пну — a fusional-language paradigm where case/number changes move the stress. |
| нельзя́ | it is forbidden / impossible (predicative) | predicative | core | — | contemporary (source published 1988) | — | — | dictionary | n/a | verified | End-stressed, no variant given — included as a baseline contrast case against the free-variation and error-flagged entries above. |
| кроме, предлог | except, besides | preposition | core | — | contemporary (source published 1988) | — | — | grammar_reference | n/a | verified | From the phonological appendix (§170): cited as a two-syllable preposition that **always** carries secondary/weak stress (по́бочное ударе́ние), unlike most disyllabic prepositions with `о`-insertion (подо, надо, обо), which are always unstressed. |
| для, предлог | for | preposition | core | — | contemporary (source published 1988) | — | — | grammar_reference | n/a | verified | §171: uniquely among Russian prepositions, для is unstressed but still triggers a different vowel-reduction pattern than usual — the following я is realized as [a] rather than the expected reduced [иᵉ] in the first pretonic syllable (e.g. для на́с, contrasted with мясно́й's normal [иᵉ]-type reduction). |
| чтобы, союз | so that, in order to | conjunction | core | — | contemporary (source published 1988) | — | — | grammar_reference | n/a | verified | §171: functions as a proclitic with no stress of its own — «сказа́л, чтобы пришли́» is pronounced as a single stress-group [сказа́л штъбыпришли́], contrasted explicitly with что бы (pronoun+particle) which is NOT reduced this way. |
| хоть, союз/частица | even though; even (conjunction/particle) | conjunction/particle | core | — | contemporary (source published 1988) | — | — | grammar_reference | n/a | verified | §171: normally unstressed like что, with the pretonic vowel realized as reduced [ъ] (book-style pronunciation allows [о]) but never the full [a] a stressed о/а would take — «хоть видит око» → [хот⁠ᵇвидит]. |
| мол / так / да, частицы и союзы | (reportative particle) / so / and | particles/conjunctions | core | — | contemporary (source published 1988) | — | — | grammar_reference | n/a | verified | §171: same reduced-vowel-without-full-stress behavior as хоть/что extends to these; example given «мол, он не виноват» → [мьлон] (paraphrased from source). |
| быть / стать (связка) | to be / to become (as a copula) | verb (copula use) | core | — | contemporary (source published 1988) | — | — | grammar_reference | n/a | verified | §175: as a linking copula (вечер был сухой, брат стал учителем) these verbs are normally weak-stressed (слабоударяемы), unlike their full lexical-verb uses — a register/function-based stress distinction, not a lexical one. |
| бы́ло / быва́ло (в опред. синт. употр.) | (auxiliary marking an interrupted/incomplete or habitual past action) | particle-like auxiliary use of a verb | core | — | contemporary (source published 1988) | — | — | grammar_reference | n/a | verified | §176: in this specific syntactic function (я пошёл было вчера в театр; придёт, бывало, ко мне и говорит) было can lose its stress entirely (realized as [пашо́лбыл] or even [пашо́лбыль]), while быва́ло keeps a weaker secondary stress rather than losing it outright, "due to its greater phonetic bulk" (paraphrased from source, p. 682). |

## Grammar points

### Secondary ("weak"/"побочное") stress as a distinct category (§169)

The dictionary's phonological appendix distinguishes ordinary lexical word-stress from a weaker,
secondary stress it calls **побочное ударение** ("weak" or "secondary stress"), notated in its own
transcriptions with a grave accent (`` ` ``) as opposed to the acute (`´`) used for primary stress.
This is presented as a systematic property of certain function-word classes (prepositions,
conjunctions, particles, numerals, and the copula), not a marginal or exceptional phenomenon —
worth noting for slang-synthesis purposes since function-word stress-weakening/loss is exactly the
kind of phonological reduction that colloquial cliticized forms (contractions, fused function
words) often build on.

### Prepositions split into three stress classes (§170)

1. **Always unstressed:** compound prepositions like `из-за`, `из-под`, and the `o`-epenthesis
   disyllabic/trisyllabic set (`подо`, `надо`, `обо`, `изо`, `перед` as `передо`) — e.g. `из-за
   ле́са` → `[иззалéсъ]`.
2. **Optionally secondary-stressed:** most other disyllabic/trisyllabic prepositions (`перед`,
   `между`, `через`) can go either way depending on register/emphasis — `перед отхо́дом` vs. `пѐред
   отхо́дом`.
3. **Always secondary-stressed:** `кроме`, and any disyllabic/trisyllabic preposition that
   derives from an adverb (`ско́лько по́сле уро́ка`, `сиде́ли о́коло до́ма`) — these retain enough of
   their adverbial "weight" that they can't fully cliticize. The monosyllabic preposition `сквозь`
   also normally carries secondary stress (`скво̀зь о́блака`).

### Weakly-stressed pronoun/numeral/copula classes (§§173–176)

Beyond prepositions and conjunctions, the appendix identifies several other classes that regularly
lose or weaken their stress in connected speech: certain pronouns used as enclitics after
interrogatives in colloquial speech (`кто-то` realized as `[кто́-ть]`), simple cardinal numerals in
counted-noun phrases unless a stress-pulling preposition intervenes (`пя́ть рубле́й` weak-stressed
vs. `на́ пять рубле́й` where the preposition pulls the stress), the copula uses of `быть`/`стать`,
and syntactically-specific incomplete/habitual-aspect uses of `бы́ло`/`быва́ло`. This is a
substantially richer picture of Russian function-word cliticization/stress-loss than any prior
Russian `established/` extraction in this corpus has captured — worth cross-referencing against
Timberlake's *Reference Grammar* material (already extracted) for overlap, though no check against
those files was performed here since this file's dispatch was scoped to this source alone.

### Homograph disambiguation via inflectional-stress pattern, not just gloss (sampled throughout)

A recurring structural feature: when two or more headwords share identical spelling and are listed
as numbered homographs (e.g. `ток¹⁻⁴`), the dictionary frequently distinguishes them not just by
a `□`-marked sense gloss but by giving each homograph a *different* inflectional paradigm with its
own stress-shift pattern (`ток¹`'s plural stays root-stressed if it even takes one, while `ток²⁻³`'s
plural shifts entirely to the ending: `тока́, -о́в`). This means stress-pattern-of-paradigm is
functioning as a disambiguating feature in its own right, independent of the citation-form stress —
a mechanic worth keeping in mind for any conlang slang-synthesis work that wants to model
homograph/homophone splitting via paradigm shape rather than spelling alone.

### Normative vs. non-normative stress marking uses a graded, not binary, scale

The dictionary consistently distinguishes at least three tiers of acceptability rather than a
simple correct/incorrect binary: **доп.** (admissible variant, fully acceptable alongside the
primary form), **не рек.** (not recommended — understood but discouraged), and **неправ.**
(outright incorrect). A `доп. устар.` (admissible-but-archaic) sub-tier also appears (seen on
не. немудрёный's short forms). This three-to-four-way gradient is itself useful reference data for
this project's `Usage Tier` taxonomy discipline — real normative dictionaries do not treat
"non-standard" as a single flat category.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — no bulk reproduction of vocabulary boxes or
explanatory prose. All quoted fragments above are single words/short phrases used as illustrative
evidence; the appendix's grammatical explanations (§§169–176) are paraphrased in this file's own
words rather than reproduced verbatim.
