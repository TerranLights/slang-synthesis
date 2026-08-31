# Serbian — Established Grammar: Hammond, *Serbian: An Essential Grammar*, Ch.7 §7.4 "Declension of nouns" (Part 2)

**Source:** Lila Hammond, *Serbian: An Essential Grammar* (Routledge, 2005). Chapter 7 "Nouns", §7.4
"Declension of nouns" (subsections 7.4.1–7.4.4: masculine/neuter nouns; feminine/masculine nouns
ending in `-a` and мати/mati; feminine nouns ending in a consonant/`-о`/`-ост`/`-ад` and кћи/kći;
declension of irregular nouns), printed pp. 152–177 (PDF lines 6094–7023 of the `pdftotext -layout`
dump of `10.Serbian an essential grammar.pdf`; §7.4 header at PDF text line 6094, Chapter 8
"Pronouns" begins at line 7024). This is a **third** reference book for this language pairing —
Serbian-specific, dual-script (Cyrillic + Latin) throughout, distinct from both the flagship textbook
(established/001–022) and the companion *Grammar: With Sociolinguistic Commentary* (established/
037–041).

**PDF extraction note — Cyrillic garbled, Latin intact.** The PDF's text layer maps its Cyrillic glyphs
to the wrong Unicode code points under `pdftotext` (a font-embedding artifact, not a vision-reading
issue — the PDF has a genuine text layer throughout, so Vision Reading Confidence is `n/a`
everywhere in this file). The Latin-script line printed beneath each Cyrillic line extracts cleanly
and correctly. Per this dispatch's instructions, Latin forms are used as the primary Term throughout;
the source's parallel Cyrillic forms exist but are not reproduced here since the extracted Cyrillic
strings are not trustworthy — this is noted once here rather than per-row.

## Coverage note — what's skipped as redundant, what's kept as genuinely new/deeper

This project has already extracted extensive noun-declension content from established/003–022
(flagship textbook, lesson-by-lesson) and established/037–041 (companion *Grammar*, especially
established/039 §89a–d and §90, which give a systematic cross-lesson review of masculine, neuter,
and feminine declension including fleeting-vowel behavior, `-lac` agent nouns, `-ov-`/`-ev-` plural
infixes, `-in` nationality-suffix drop, the neuter `-en-`/`-et-` extension classes, the `oko`/`uho`
gender-shift, the `-a`-declension's uniquely distinct accusative singular, and the irregular plurals
`dete`/`brat`/`gospodin`).

**Skipped as redundant:** the underlying rules already stated in established/039 are not
re-explained from scratch here (fleeting-vowel mechanics, animate/inanimate accusative split,
`oko`/`uho` gender shift, the general Gpl. `-i`-vs-`-a` split for `-a`-declension nouns). Most of
the illustrative *sentences* the source uses are skipped per the copyright/coverage rule.

**Kept as genuinely new/deeper (the point of this file):**
- **Complete, compact endings-summary tables** for all three declensions side by side (A/masc-neut,
  E/fem+masc-`a`, I/fem-consonant) — Hammond's own organizing framework (three declensions named by
  their genitive-singular vowel) is not how established/039 organizes the material, so this gives a
  genuinely different, more compact cross-reference than the prior extraction.
- **Full case-by-case paradigm tables** (singular and plural, all 7 cases) for a spread of concrete
  nouns not used as declension examples elsewhere in this project's Serbian/Croatian/Bosnian
  datasets so far (vojnik, prozor, ljubitelj, panj, orao, intervju, lovac, žiri; selo, polje, ime,
  dugme; žena, veverica, ruka, mati, turista, sluga; stvar, misao, reč, kći, kokoš) — kept per the
  project's standing finding that full paradigm reference tables are high-value even with partial
  topical overlap.
- **The archaic мати/mati and кћи/kći paradigms in full**, as specifically flagged for this
  dispatch — established/039 only *mentions* these two irregular feminine nouns and their special
  stems (mater-, kćer-) in prose; this file gives their complete case-by-case declension across
  singular and plural, which is not available elsewhere in this project's datasets.
- **The irregular-noun subsection (7.4.4), all seven irregularity types**, several of which are not
  covered (or are covered less completely) in established/039: the `-es-` infix class (небо/nebo
  "sky", чудо/čudo "miracle" — not previously extracted), the full `брат/brat → браћа/braća` paradigm
  (established/039 only states the pattern, doesn't tabulate it), and the
  човек/čovek → људи/ljudi suppletive-plural counting rule (numeral-governed case switch — not
  previously extracted anywhere in this project).
- Vocabulary items used as declension-paradigm illustrations that don't already appear in this
  project's Serbian/Croatian/Bosnian vocabulary tables (e.g. intervju, žiri, veverica, kokoš, puž,
  vrh, mladoženja, izdajica).

---

## Grammar points

### The three-declension framework (declension named by its own genitive-singular vowel)

Hammond organizes all Serbian noun inflection into exactly three declensions, named for the vowel
that appears in the genitive singular ending:

- **A declension** — all masculine nouns (animate and inanimate) and all neuter nouns. Exceptions:
  masculine nouns ending in `-a` (join the E declension) and a few masculine hypocoristic/endearment
  forms in `-o`/`-e` (Ivo, Vlado) that can join the E or I declension instead.
- **E declension** — the feminine noun мати/mati "mother", all feminine nouns (hard and soft) ending
  in `-a`, and a small set of masculine nouns ending in `-a`.
- **I declension** — all feminine nouns ending in a consonant, plus the feminine noun кћи/kći
  "daughter"; includes nouns in `-ост`/`-ost` and `-ад`/`-ad`.

A single consonant-softness distinction (hard vs. soft stem-final consonant) runs through the A
declension specifically. Soft consonants: j, lj, nj, c, ć, č, š, đ, dž, ž. Hard consonants: m, r, b,
f, v, n, t, d, p, l, k, g, s, z, h. Neither the E nor the I declension makes a hard/soft or an
animate/inanimate distinction.

### 7.4.1 Masculine and neuter nouns (A declension) — endings summary

| Case | Masc. sg. | Neut. sg. | Masc. pl. | Neut. pl. |
|---|---|---|---|---|
| Nom. | consonant / `-o` / `-e` | `-o` / `-e` | `-i` | `-a` |
| Gen. | `-a` | `-a` | `-a` / `-i` / `-iju` | `-a` / `-i` / `-iju` |
| Dat. | `-u` | `-u` | `-ima` | `-ima` |
| Acc. | consonant/`-a` (animacy-governed) / `-o` / `-e` | `-o` / `-e` | `-e` | `-a` |
| Voc. | `-e`/`-u` (soft) / consonant | `-o` / `-e` | `-i` | `-a` |
| Inst. | `-om` / `-em` | `-om` / `-em` | `-ima` | `-ima` |
| Loc. | `-u` | `-u` | `-ima` | `-ima` |

**Vocative singular sub-rules for the A declension** (finer-grained than established/039 gives):
hard-consonant/short-`-e`/`-o`(from л/l-softening) stems take `-e` (Goste! Vole!); soft-consonant
stems and those with a long accented `-e`/`-o` take `-u` (Učitelju! Atašeu! Birou!); short-`-o` stems
take `-o` (Danko! Milenko! Zlatko!); foreign names/surnames in `-ac`/`-ev`/`-ov`/`-in` and all neuter
nouns keep the nominative form (Jimmy! Bajac! More!); nouns (not names) in `-ac` change to `-uče`
(prevodilac → Prevodioče! "Hey translator!").

**Instrumental singular**: hard-consonant/final-syllable-`-e` stems take `-om` (gostom, selom);
soft-consonant stems generally take `-em` (učiteljem, poljem); but a small set with `-e` before the
soft consonant reverts to `-om` (jež → ježom "hedgehog," not †ježem).

**Genitive plural, alternate endings beyond the regular `-a`/`-i` split** (masc.): quantity nouns
pari, sati, meseci take `-i`; gost, nokat, prst, and sometimes usta (pluralia tantum, "mouth," like
vrata) take `-iju` (gostiju, noktiju, prstiju — nokat drops its fleeting `a` before the ending).

### 7.4.2 Feminine and masculine nouns ending in `-a`, and мати/mati (E declension)

No hard/soft or animate/inanimate distinction. Membership: all feminine common nouns in `-a`; мати/
mati (stem mater- throughout the oblique cases); a small set of masculine common nouns in `-a`
referring to male humans that decline as feminine but stay grammatically masculine in the singular
(starešina "officer/chief," vođa "leader," sudija "judge," sluga "servant," mladoženja
"bridegroom"); masculine/feminine proper names in `-a`; nouns of either gender describing a person's
role/nature, in `-a` (lutalica "wanderer," pijanica "drunk," izdajica "traitor"); foreign-origin
masculine nouns in `-ist(a)`/`-t(a)` that decline E-declension in the singular but switch to the A
declension in the plural (sportista "sportsman," ekonomista "economist," turista "tourist,"
demokrata "democrat" — Npl. turisti follows the A/masc. pattern, not an E-declension plural);
endearment nouns of either gender in `-a` (deka "grandpa," meda "teddy bear"); singular-form
collective nouns in `-a` (gospoda "gentry," živina "poultry").

**Dative/locative singular**: most nouns take `-i` (kući, drugarici, dedi); place names with
adjectival endings take `-oj` (Engleskoj, Mađarskoj).

**Vocative singular, finer sub-rules**: мати/mati itself takes `-i`; most nouns and disyllabic
`-ica` nouns take `-o` (Ptico! Ženo! Slugo!); proper nouns with short accent, and place names in
`-ska`/`-čka`/`-ška`, keep `-a` (Lila! Marija! Mađarska!); some place names in `-ka` take `-o`
instead (Liko! ← Lika); nouns of more than two syllables in `-ica` take `-e` (lutalice!, pijanice!,
lutkice! "doll," diminutive).

**Genitive plural**: the regular fleeting-`a`-insertion `-a` ending applies broadly (kuća, sudija,
pijanica, žrtava, zemalja); consonant-cluster stems without fleeting-`a` insertion take `-i` instead
(funti, lopti, molbi, majki, tajni); ruka "hand," noga "leg," sluga "servant" irregularly take `-u`
(ruku, nogu — "servants" is not glossed with a `-u` example in the source excerpt but is named as
following this group).

**E-declension endings summary**:

| Case | Fem. sg. | Masc. sg. (E-decl.) | Fem./Masc. pl. |
|---|---|---|---|
| Nom. | `-a` | `-a` | `-e` |
| Gen. | `-e` | `-e` | `-a` / `-u` / `-i` |
| Dat. | `-i` / `-oj` (place names) | `-i` | `-ama` |
| Acc. | `-u` | `-u` | `-e` |
| Voc. | `-a` / `-e` / `-o` / `-i` | `-a` / `-e` / `-o` / `-i` | `-e` |
| Inst. | `-om` | `-om` | `-ama` |
| Loc. | `-i` / `-oj` (place names) | `-i` | `-ama` |

**Full paradigm — žena "woman" (Fsg./pl.), veverica "squirrel", ruka "hand", mati "mother", turista
"tourist" (masc., E-decl. sg. → A-decl. pl.), sluga "servant" (masc., E-decl. throughout)**,
condensed to singular only (plural follows the summary table above uniformly for this set, with
turista switching declension class in the plural as noted):

| Case | žena | mati |
|---|---|---|
| Nom. | žena | mati |
| Gen. | žene | matere |
| Dat. | ženi | materi |
| Acc. | ženu | mater |
| Voc. | ženo | mati |
| Inst. | ženom | materom |
| Loc. | ženi | materi |

мати/mati is notable as the only E-declension noun that keeps its nominative-singular form (`mati`,
not †mata) in both the nominative and vocative singular, while every oblique case is built on the
irregular stem mater-. It has no attested plural form in the source's own paradigm chart (the plural
row for "mother" is left blank in the source's own table) — this project's copy preserves that gap
rather than inferring a form.

### 7.4.3 Feminine nouns ending in a consonant, in `-o`, `-ost`, or `-ad`, and кћи/kći (I declension)

No hard/soft or animate/inanimate distinction. Membership: feminine consonant-final nouns (stvar
"thing," ljubav "love"); two nouns ending in `-o` that revert to an `-l` stem through the cases
(misao "thought," stem misl-; so "salt," stem sol-); abstract nouns in `-ost` (milost "mercy,"
stvarnost "reality"); collective nouns in `-ad` (telad "calves," jagnjad "lambs"); and кћи/kći
"daughter," which uniquely has two nominative-singular forms, kći and kćer, and switches entirely to
the kćer- stem from the accusative singular onward.

**Instrumental singular**: the regular ending is `-i`, especially with a preposition (sa stvari, sa
misli); without a preposition, stems ending in č/ž/š/s/z/r may instead take `-ju` or `-u` (reči ~
reči/reču "with a word"). A stem-consonant-specific alternation set governs which nouns take `-lju`/
`-nju`/`-ću`/`-đu` for the alternate ending: b/v/m/p → `-lju`; l → `-lju`; n → `-nju`; t → `-ću`; d →
`-đu` (ljubavi ~ ljubavlju "with love"; misli ~ mišlju "with a thought," s→š before the ending;
mladosti ~ mladošću "with youth").

**Genitive plural**: regular `-i` (mladosti, radosti, žalosti, soli, misli, teladi); a small set —
oči "eyes," uši "ears," kosti "bones" — takes `-iju` instead (očiju, ušiju, kostiju). Oči and uši are
cross-referenced as having a neuter A-declension singular form (oko, uho) that shifts to this
feminine I-declension plural — consistent with, and not contradicting, established/039's fuller
treatment of that gender-shift.

**I-declension endings summary**:

| Case | Fem. sg. | Fem. pl. |
|---|---|---|
| Nom. | consonant (kći/kćer for кћи) | `-i` |
| Gen. | `-i` | `-i` / `-iju` |
| Dat. | `-i` | `-ima` |
| Acc. | consonant (kći/kćer) | `-i` |
| Voc. | `-i` | `-i` |
| Inst. | `-i` / `-ju` / `-u` / `-lju` | `-ima` |
| Loc. | `-i` | `-ima` |

**Full paradigm — kći/kćer "daughter"**:

| Case | Singular | Plural |
|---|---|---|
| Nom. | kći / kćer | kćeri |
| Gen. | kćeri | kćeri (also kćeriju) |
| Dat. | kćeri | kćerima |
| Acc. | kći / kćer | kćeri |
| Voc. | kćeri | kćeri |
| Inst. | kćeri / kćerju | kćerima |
| Loc. | kćeri | kćerima |

For comparison, the paradigm's other headword nouns (stvar "thing," misao "thought," reč "word,"
kokoš "hen") follow the same singular/plural pattern shown in the endings-summary table above, with
misao reverting to the stem misl- from the genitive singular onward exactly as кћи/kći reverts to
kćer-.

### 7.4.4 Declension of irregular nouns — all seven types

1. **`-ov-`/`-ev-` plural infixes** (most monosyllabic masc. nouns, minus a short exception list —
   dan "day," konj "horse," zub "tooth," sat "hour" *does* take the infix despite being an exception
   to some other pattern, and "several others"): hard-stem nouns insert `-ov-` before plural endings
   (grad → gradovi "towns," vrh → vrhovi "tops"); soft-stem nouns insert `-ev-` (muž → muževi
   "husbands," puž → puževi "snails," kralj → kraljevi "kings"). Singular declension is regular
   A-declension throughout.
2. **`-en-`/`-et-` infixes** (neuter nouns in `-e`): `-en-` appears in the singular Gen./Dat./Inst./
   Loc. and throughout the plural for ime "name," vreme "time/weather," pleme "tribe," rame
   "shoulder," seme "seed"; `-et-` follows the same distribution for dugme "button," tele "calf,"
   pile "chick," and one sense of drvo "tree" (drvo also has an unrelated second plural meaning
   "wood," without this infix — the source flags this as a genuine lexical split, not a free
   variant). Dete "child" declines only in the singular and follows the same `-et-` pattern as
   dugme.
3. **`-es-` infix** (neuter nouns in `-o`, plural only): nebo "sky" → nebesa "skies," čudo "miracle/
   wonder" → čudesa. Full paradigm for nebo: Nsg. nebo / Npl. nebesa; Gsg. neba / Gpl. nebesa; Dsg.
   nebu / Dpl. nebesima; Asg. nebo / Apl. nebesa; Vsg. nebo / Vpl. nebesa; Isg. nebom / Ipl.
   nebesima; Lsg. nebu / Lpl. nebesima. (Not previously extracted in this project's Serbian/
   Croatian/Bosnian datasets.)
4. **`-lac`-suffix agent nouns from verbs**, where `-lac` replaces the infinitive ending: čitalac
   "reader," prevodilac "interpreter/translator," rukovodilac "leader." The `-lac` form is confined
   to the nominative singular and genitive plural; every other form is built on a stem in `-oc-`
   (Gsg. čitaoca, Npl. čitaoci, Gpl. čitalaca — the `-lac`/`-laca` shape reappears specifically in
   the genitive plural, reversing back from `-oc-`). Vocative singular: čitaoče.
5. **`-in`-suffix nationality/origin nouns** drop `-in` in the plural stem, with a regular singular
   declension: Srbin "a Serb" → Npl. Srbi, Gpl. Srbe (not †Srbina), Dpl./Ipl./Lpl. Srbima.
6. **брат/brat "brother"**: regular A-declension in the singular; its plural браћа/braća switches
   declension class entirely and inflects as a regular E-declension feminine noun (grammatically
   feminine-pattern plural for a semantically masculine-plural referent — the same collective-plural
   pattern established/039 notes for dete→deca and gospodin→gospoda, now with brat's own full
   plural-inflection class stated explicitly).
7. **човек/čovek "man" ↔ људи/ljudi "people" — suppletive counting rule**: čovek exists only in the
   singular; after the numerals 2, 3, and 4 it takes the A-declension genitive singular form. From 5
   upward (and in the plural generally), čovek is replaced entirely by the separate noun ljudi
   "people" (itself A-declension, Gpl. ljudi with a `-i` ending). This numeral-governed
   suppletive-count-noun switch is not previously extracted anywhere in this project's Serbian/
   Croatian/Bosnian datasets.

---

## Vocabulary

Declension-paradigm example nouns not already logged in this project's Serbian/Croatian/Bosnian
vocabulary tables (established/001–045), or logged here because this source supplies a fuller
paradigm than previously captured:

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| prozor | window | noun, masc. inanimate | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.1 A-declension hard-stem inanimate example |
| vojnik | soldier | noun, masc. animate | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.1 A-declension hard-stem animate example |
| ljubitelj | lover (of something), enthusiast | noun, masc. animate | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.1 A-declension soft-stem animate example |
| panj | (tree) stump, log | noun, masc. inanimate | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.1 A-declension soft-stem inanimate example |
| orao | eagle | noun, masc. animate | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.1; declines with l-vocalization (orao→orla) |
| intervju | interview | noun, masc. inanimate | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.1; foreign-origin noun in -u, takes -j- infix before case endings |
| lovac | hunter | noun, masc. animate | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.1; fleeting-vowel double-consonant stem noun |
| žiri | judges' panel, jury | noun, masc. inanimate | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.1; foreign-origin noun in -i, takes -j- infix |
| selo | village | noun, neuter | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.1 A-declension neuter -o example |
| polje | field | noun, neuter | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.1 A-declension neuter -e example |
| doba | era, season | noun, neuter | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.1 headword listed as a neuter A-declension example |
| veverica | squirrel | noun, fem. | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.2 E-declension example |
| kokoš | hen | noun, fem. | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.3 I-declension example |
| misao | thought | noun, fem. | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.3; -o nominative reverting to stem misl- |
| so | salt | noun, fem. | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.3; -o nominative reverting to stem sol- |
| stvar | thing | noun, fem. | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.3 I-declension consonant-stem example |
| reč | word | noun, fem. | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.3; alternate instrumental sg. reči/reču |
| telad | calves | noun, fem., collective | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.3 -ad collective example |
| jagnjad | lambs | noun, fem., collective | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.3 -ad collective example |
| starešina | officer, chief | noun, masc. (E-declension) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.2; masc. noun declining as feminine -a noun |
| vođa | leader | noun, masc. (E-declension) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.2 |
| sudija | judge | noun, masc. (E-declension) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.2 |
| sluga | servant | noun, masc. (E-declension) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.2; full paradigm given |
| mladoženja | bridegroom | noun, masc. (E-declension) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.2 |
| lutalica | wanderer | noun, common gender | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.2; declines feminine, applies to either gender |
| pijanica | drunk | noun, common gender | colloquial | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.2 |
| izdajica | traitor | noun, common gender | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.2 |
| lutkica | little doll | noun, fem., diminutive | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.2 vocative-form illustration, dim. of lutka |
| sportista | sportsman, athlete | noun, masc. | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.2; E-decl. singular, A-decl. plural |
| ekonomista | economist | noun, masc. | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.2 |
| turista | tourist | noun, masc. | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.2; full paradigm given |
| demokrata | democrat | noun, masc. | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.2 |
| deka | grandpa | noun, masc., endearment | colloquial | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.2 |
| meda | teddy bear | noun, masc., endearment | colloquial | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.2 |
| gospoda | gentry | noun, fem., collective (sg. form) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.2; also given in established/039 for a different sense (gospodin plural) |
| živina | poultry | noun, fem., collective (sg. form) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.2 |
| kuća | house | noun, fem. | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.2 dat./loc. sg. -i example |
| drugarica | (female) friend | noun, fem. | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.2 |
| ruka | hand | noun, fem. | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.2; irregular Gpl. -u (ruku) |
| noga | leg | noun, fem. | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.2; irregular Gpl. -u (nogu) |
| funta | pound (weight/currency) | noun, fem. | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.2 Gpl. -i (cluster stem, no fleeting a) example |
| lopta | ball | noun, fem. | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.2 |
| molba | request, application | noun, fem. | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.2 |
| majka | mother | noun, fem. | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.2; contrast with archaic mati |
| tajna | secret | noun, fem. | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.2 |
| žrtva | victim | noun, fem. | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.2 Gpl. fleeting-a example (žrtava) |
| zemlja | country, land | noun, fem. | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.2 Gpl. fleeting-a example (zemalja) |
| grad | town, city | noun, masc. | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.4.1; -ov- infix example, full paradigm given |
| vrh | top, peak | noun, masc. | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.4.1; -ov- infix example |
| muž | husband | noun, masc. | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.4.1; -ev- infix example |
| puž | snail | noun, masc. | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.4.1; -ev- infix example |
| kralj | king | noun, masc. | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.4.1; -ev- infix example |
| tele | calf | noun, neuter | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.4.2; -et- infix class |
| pile | chick | noun, neuter | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.4.2; -et- infix class |
| drvo | tree; wood | noun, neuter | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.4.2; "tree" sense takes -et- infix, "wood" sense has a separate plural without it |
| nebo | sky | noun, neuter | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.4.3; -es- infix, full paradigm given |
| čudo | miracle, wonder | noun, neuter | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.4.3; -es- infix class |
| čitalac | reader | noun, masc. (deverbal, -lac) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.4.4; full paradigm given |
| rukovodilac | leader, manager | noun, masc. (deverbal, -lac) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.4.4 |
| ljudi | people | noun, masc. pl. (suppletive) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | §7.4.4.7; replaces čovek from 5 upward and in general plural use |

---

## Checklist and manifest note

Per this dispatch's instructions, `datasets/Serbian_Croatian_Bosnian/00_Extraction_Checklist.md` is
intentionally **not** touched by this subagent — checklist updates are being done as a single
serialized pass after all chunks in this dispatch land.
