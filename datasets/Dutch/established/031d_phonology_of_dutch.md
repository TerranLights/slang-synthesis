# Dutch — Established Vocabulary/Grammar: The Phonology of Dutch, Ch.5

**Source:** Geert Booij, *The Phonology of Dutch* (Oxford University Press, 1995). Continues from
`031`/`031b`/`031c_phonology_of_dutch.md`; see `031` for the overall source description and
vision-reading/offset notes (inherited unchanged). Covers Ch.5 "Word Stress" (printed pp. 96–124 /
PDF pp. 107–135).

**Coverage note.** Vision-read throughout, clean typeset print, no marginalia. Vision Reading
Confidence `verified` for all rows. This chapter is heavily theory-internal (extensive back-and-
forth citing competing analyses of secondary-stress weight-sensitivity, grid-vs.-tree formalisms,
Trochaic/Iambic Reversal edge cases) — condensed hard to the empirical generalizations a
conlang-mechanics use would actually need (where does main stress fall, what shifts it, how do
compounds/prefixes/suffixes interact with it), skipping the extended inter-author debate over the
correct formal apparatus. This is genuinely new content relative to 017/017b/017c, which covered
Dutch vowel/consonant *quality* but never systematically addressed stress placement rules.

---

## Vocabulary

Representative forms only; this chapter is rule-driven rather than vocabulary-driven.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| kanón / kánon | "gun" / "canon" | noun | core | — | contemporary (source published 1995) | — | — | grammar_reference | n/a | verified | Rare minimal pair distinguished purely by stress placement (French-pattern final stress vs. Latin-pattern penultimate stress), cited as evidence stress is not wholly unpredictable even though the three historical layers (Germanic-initial, French-final, Latin-penultimate) overlap (§5.2, p.100). |
| pilaar / pijler | "pillar" (etymological doublets) | noun | core | — | contemporary (source published 1995) | — | — | grammar_reference | n/a | verified | Etymologically related doublet showing the French-pattern form keeps final stress and a full vowel, while the Germanic-pattern form shifted stress to the first syllable and reduced the second vowel to schwa, with concomitant diphthongization /i/→/ɛi/ — segmental composition correlates with stress-pattern layer (§5.2, p.100). |
| kankeronderzoek | "cancer research" | noun (compound) | core / technical | — | contemporary (source published 1995) | — | — | grammar_reference | n/a | verified | Three-member compound whose derivation illustrates cyclic application of both the Main Stress Rule and the Compound Stress Rule, with Trochaic Reversal resolving a stress clash between the first two constituents (§5.4, p.116). |
| Bosatlas / tandpasta | (atlas brand name) / "toothpaste" | noun (compound) | core | — | contemporary (source published 1995) | — | — | grammar_reference | n/a | verified | Exceptional compounds that allow Trochaic Reversal to shift stress onto a normally-unstressable final syllable of a bisyllabic second member — explained as lexicalizations that behave as a single prosodic word rather than a true two-word compound (§5.4, pp.116–117). |
| ongrammaticaliteit | "ungrammaticality" | noun | core / technical | — | contemporary (source published 1995) | — | — | grammar_reference | n/a | verified | The chapter's central "bracketing paradox" case study: morphologically, the native prefix *on-* attaches last (outermost), but phonologically the non-native suffix *-iteit* must attach last for stress to come out correctly — resolved by treating *-iteit* as a genuinely cyclic non-native suffix that reapplies the Main Stress Rule even to an already on-prefixed base, since [-native] percolates from the head *grammaticaal* through *ongrammaticaal* (§5.6, pp.123–124). |

## Grammar points

### Stress representation: grids, feet, and the Optimal Grid Principle (§5.1, pp.96–99)

Booij represents stress with a metrical grid (asterisks on successive lines: line 0 = syllable,
line 1 = foot/stressed-syllable, line 2 = word-level main stress, line 3+ = compound levels). Two
governing principles hold across the whole system: the **Schwa Restriction** (a schwa-headed
syllable can never bear stress) and the **Optimal Grid Principle** (a prosodic word prefers an
alternating stressed/unstressed rhythm) — the latter is restricted by the former. A **stress
clash** (two adjacent stress asterisks at consecutive grid lines) is resolved by **Trochaic
Reversal**, which moves the clashing stress one syllable to the right (demonstrated on the compound
*dorpsdominee* "village parson").

### The Main Stress Rule (MSR): a right-to-left, weight-sensitive window rule (§5.2, pp.99–104)

Dutch stress historically layers three inherited patterns — Germanic (initial stress), French
(final stress), Latin (penultimate, or antepenultimate if the penultimate is "light" i.e. open with
a short vowel) — and Booij derives a unified synchronic **Main Stress Rule**: build a left-dominant
foot from the right edge of the word, in a window of the last two (or, with extrametricality, three)
syllables, such that the foot's unstressed member cannot be a closed syllable or contain a
diphthong. In practice: **words ending in a vowel** get penultimate stress by default (*olie* "oil",
*kanárie* "canary"), with exceptions for antepenultimate stress (words in *-ia/-io*: *ária*, *rátio*)
and final stress (words in unstressed *-ie*: *melodíe*, *trofée*). **Words ending in long-vowel/
diphthong+C or short-vowel+CC** get final stress by default (*kanáal* "channel", *perkamént*
"parchment"), with the antepenultimate barred if the penultimate is heavy. **Words ending in
short-vowel+C** get penultimate (or, if that's heavy, antepenultimate) stress (*mólton* "soft
sheet"), never final except in a marked exception set. A rich **extrametricality** apparatus handles
exceptions: certain word-final syllable shapes (VC rhymes generally, or specific known suffix
classes like Latin *-ium, -ia, -icus, -ikus*, the geographic-name ending *-uwe*) are made invisible
to the rule by marking their vowel [extrametrical] — explaining antepenultimate-stress words like
*cálcium* and *ária* — while words ending in *-or* have their final /r/ (not the vowel) made
extrametrical, giving penultimate stress even on an otherwise "light" syllable (*mótor*). A small
residual class of geographic names and Latin-origin words (marked diacritically [+Germanic]) simply
take initial stress by a minor rule that overrides the MSR (*Wágeningen*, *áccusatief*).

### Secondary stress follows a rhythm-based Optimal Grid Rule, not iterated MSR (§5.2.1, pp.105–110)

Secondary stresses fill in an alternating rhythm around the main stress, preferring stress at
prosodic-word *edges* (the "Hammock Principle") over strict binary alternation — demonstrated by
*fonologie*, where secondary stress falls on the word-initial syllable rather than the metrically
"expected" second syllable, because word-edge placement is preferred whenever it avoids adjacent
stresses. Booij's position (contra Kager 1989) is that Dutch secondary stress is **not
weight-sensitive** (syllable closedness/diphthong status doesn't force stress) and applies **from
both word edges simultaneously**, unlike the strictly right-to-left MSR — a genuine cross-linguistic
parameter choice (English is weight-sensitive but single-direction; Spanish is
non-weight-sensitive-but-same-direction as its main-stress rule; Dutch, on this analysis, is
non-weight-sensitive and opposite-direction, patterning like Polish).

### Cyclic vs. non-cyclic ("stress-neutral") suffixes: three classes of native suffixation
(§5.2.2–5.3, pp.109–115)

The MSR applies cyclically to underived words and to words built by non-native (Latinate)
suffixation — reapplying, and erasing the prior stress pattern, at each non-native affixation step
(*profeteer* "to prophesize", *kanaliseer* "to canalize" both get fresh word-initial secondary
stress rather than accumulating stress history). Native suffixes split into three behaviorally
distinct classes: **(a) stress-neutral** (the large majority — *-e, -el, -en, -er, -erd, -erig,
-ing, -nis, -s, -sel, -st, -ster, -t, -te, -tje* as cohering suffixes that fuse with the stem's
existing prosodic word and don't disturb its stress; plus non-cohering *-achtig, -baar, -dom, -heid,
-ling, -loos, -schap*, which form their own separate prosodic word and so likewise leave the base's
stress untouched, subject instead to the Compound Stress Rule as a two-prosodic-word unit); **(b)
stress-bearing** (*-erij, -es, -in, -ij* — a small closed class of four suffixes that always
themselves carry the word's main stress: *schiet-erij* "shooting", *leeuw-in* "lioness"); **(c)
stress-shifting** (*-baar, -end, -ig, -isch, -(e)lijk, -s, -zaam* — all adjectival, and all cyclic:
they force main stress onto the last stressable syllable immediately before the suffix, e.g.
*overdraagbaar* "transferable"). Notably *-baar* only shifts stress when its base is a genuine
separable complex verb (*overdrágen*→*overdráagbaar*), not otherwise.

### Compound Stress Rule (CSR): first constituent wins, with productive exceptions
(§5.4, pp.114–119)

The default pattern for Dutch compounds (overwhelmingly the most productive word-formation type) is
strong-weak: the first constituent's main stress becomes the whole compound's main stress, applied
cyclically as constituents combine (worked derivations given for *onderzoekfonds* "research fund"
and *kankeronderzoek* "cancer research", the latter requiring Trochaic Reversal to resolve a stress
clash between the first two members). A handful of lexicalized exceptions instead put main stress on
the second constituent (*stadhuis* "town hall", *boerenzoon* "farmer's son"). **Adjectival
compounds** split into two patterns: most put main stress on the *second* constituent
(weak-strong: *gastvrij* "hospitable") but shift it back to the first in attributive position
(Iambic Reversal: *een gástvrije ontvangst* "a warm welcome"); a second class where the second
member's lexical meaning has faded (functioning more like a suffix: *zeeziek* "sea-sick",
*kleurrijk* "colourful") instead takes the ordinary strong-weak compound pattern throughout.
**Compound prepositions used intransitively** shift stress to the first constituent (*bovenín* →
*bóvenin de kamer* "at the top of the room").

### Prefix stress: non-native, nativized-non-native, and native prefix classes (§5.5, pp.119–124)

**Non-native prefixes** (*a-, ab-, ad-, ante-, apo-, con-, de-, in-, inter-, per-, post-, pre-, re-,
trans-*) attach to non-native bases/roots and never bear main stress themselves — they get at most
secondary stress, either as their own domain or via the Optimal Grid Rule, since the MSR always
assigns primary stress to a word-final syllable region. Some can lose morphological transparency
entirely and fuse into one prosodic word with the stem (*reageren* "to react" — obligatory glide
insertion between the vowels proves the fusion). **Nativized non-native prefixes** (*anti-, co-,
contra-, des-, ex-, inter-, meta-, non-, para-, pro-, semi-, sub-, super-, ultra-*) behave like true
compound first-members and *do* take main stress under the ordinary Compound Stress Rule
(*ánti-houding* "adverse attitude"), with the same attributive-position stress-shift-to-the-head
pattern as adjectival compounds when the resulting word is an adjective. **Native prefixes** split
into a stressed class that forms an independent prosodic word (*aarts-* "arch-", *oer-* "primeval-",
*on-* "un-", *her-* "re-", *onder-*, *over-" — patterning as ordinary compounds, e.g. *áartsbisschop*
"archbishop") and a fully stressless, always-verbalizing class (*be-, er-, ge-, ont-, ver-*, which
never bear main stress even though most form independent syllabification domains). A further class
of native verb-forming prefixes that also double as prepositions/particles (*aan-, achter-, door-,
her-, mis-, om-, onder-, over-, vol-, voor-, weer-*) are governed by a separate, more specific rule:
assign stress to the *rightmost* prosodic word of a prefixed verb — which for bisyllabic prefixes
correctly predicts stem stress since the prefix's own second syllable is a schwa. Three prefixes
(*her-, over-, onder-*) show **variable stress** conditioned by the base verb's own stress: they
take main stress themselves only when the base verb's *first* syllable is unstressed
(*formuléer*→*hérformuleer*, but ordinary stem-final stress otherwise). The negative prefix *on-*
on adjectives shows genuine speaker variation in predicative position (stress on either the prefix
or the base, with prefix-stress available as an emphatic option) but prefers prefix stress in
attributive position, analyzed as a case of Iambic Reversal.

### Bracketing paradoxes resolved without level-ordering (§5.6, pp.123–124)

The Dutch equivalent of English *ungrammaticality*, *ongrammaticaliteit*, poses a classic mismatch:
morphologically the native prefix *on-* attaches outermost (to already-complete *grammaticaal*), but
phonologically the correct stress pattern only falls out if the non-native suffix *-iteit* is treated
as attaching *after* the prefix, triggering fresh cyclic MSR reapplication across the whole
*on-grammaticaal* string. Booij resolves this without assuming rigid level-ordering (all non-native
morphology strictly before all native morphology) by instead deriving cyclicity from an independent
per-affix [±native]/cyclic marking, plus feature percolation: since *grammaticaal* is the phonological
head of *ongrammaticaal* and is itself [-native], that feature percolates to the whole prefixed word,
correctly licensing attachment of the [-native] suffix *-iteit* afterward — with *-iteit* being
independently marked cyclic (as established in §4.4), it reapplies the MSR to derive the correct
final stress pattern *òngrammàtikàlitéit*.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `../../00_Reference_Extraction_Spec.md`.
