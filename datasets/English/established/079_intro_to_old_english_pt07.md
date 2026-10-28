# English — Established Vocabulary/Grammar: Richard Hogg, *An Introduction to Old English*, back-matter "Old English – present-day English glossary" & "Glossary of linguistic terms"

**Source:** Richard Hogg, *An Introduction to Old English* (Edinburgh Textbooks on the English
Language, Edinburgh University Press, 2002), "Old English – present-day English glossary"
(pp. 138–146) and "Glossary of linguistic terms" (pp. 147–153).

**Coverage note — this chunk is handled differently from `pt01`–`pt06`, and the reasoning is
spelled out explicitly below rather than silently applied.**

### Why the OE–PDE glossary (pp. 138–146) is *not* bulk-transcribed
This back-matter glossary is the book's own working dictionary for the specific texts quoted
throughout the book (the Cædmon passage, Ælfric's *Lives of Saints* extracts, the Anglo-Saxon
Chronicle extract, and above all Wulfstan's *Sermo Lupi ad Anglos*, whose vocabulary dominates the
glossary's later pages). It runs to roughly 320–330 distinct headwords across 9 pages. A straight
A-to-Z transcription of the entire thing would functionally recreate the back-of-book dictionary
wholesale — exactly the "bulk reproduction of a vocabulary box" the extraction spec's copyright-
discipline rule prohibits, as distinct from the selective word-gloss extraction the spec's
vocabulary-table format is designed for. It would also be substantially redundant with `pt01`–
`pt06` above, since most of this glossary's entries are words that already appear, in context, as
the worked examples quoted throughout the ten chapters (paradigm words, pronouns, prepositions,
common verbs) — and redundant in advance with a dedicated, purpose-built Old English dictionary
already sitting in this same source folder (`18 A Concise Anglo-Saxon Dictionary.pdf`, not yet
dispatched), which is the right future source for exhaustive A–Z OE lexical coverage, not a
teaching grammar's own back-matter crib-sheet for its own worked examples.

**What was extracted instead:** a curated selection of entries that are genuinely non-redundant
with `pt01`–`pt06` — specifically the glossary's richest vein of *new* content, the dense
sin/vice/crime/moral-failing vocabulary that only appears because it glosses Wulfstan's *Sermo
Lupi ad Anglos* (an apocalyptic sermon on England's moral collapse before the Danish conquest,
quoted in extract at the end of Chapter 7 and again — the opening lines — at the end of Chapter 8,
`pt05`). This register (crime, oath-breaking, sexual/religious transgression, social collapse) is
not otherwise represented in this project's Old English extraction and is directly relevant to
this project's slang-synthesis purpose (taboo/moral-register vocabulary is exactly the kind of
material later mechanics-analysis work will need). A smaller set of closed-class function words
not yet captured in `pt01`–`pt06` is also included for completeness. **Everything else in the
appendix glossary was skipped as redundant** — left for either a dedicated dictionary extraction
pass or recoverable in context from `pt01`–`pt06`'s own worked examples.

### Why the "Glossary of linguistic terms" (pp. 147–153) is not tabulated at all
This second back-matter glossary (~100 entries: *ablaut, accusative case, affix, ... word order,
zero*) is pure English-language metalanguage/terminology for describing *any* language's grammar —
it contains no Old English lexical content at all. Every term in it that actually matters for this
project is already defined in context within the Grammar points sections of `pt01`–`pt06` (ablaut:
`pt03`; i-mutation/umlaut: `pt02`; Verner's Law: `pt03`; bahuvrihi/compounding: `pt05`; etc.), so
tabulating a second, free-standing copy of the same definitions would be pure duplication with no
new information. Not extracted, by deliberate decision, not oversight.

**No marginalia; clean text layer throughout both glossaries; `Attested Era: Old English` for all
vocabulary entries below (whole-book tag per dispatch instruction).**

**Redundancy check:** no prior Old English extraction exists in this repo — independent first pass.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| synn | sin | noun (fem.) | core | — | Old English | — | — | grammar_reference | n/a | n/a | glosses the Wulfstan extract; the general umbrella term the sermon's whole catalogue of specific offenses elaborates |
| mandǣd | crime, evil deed | noun (fem., compound) | core | — | Old English | — | — | grammar_reference | n/a | n/a | — |
| morðdǣd | murder | noun (fem., compound) | core | — | Old English | — | — | grammar_reference | n/a | n/a | — |
| mannsylen | slavery (lit. "man-selling") | noun (fem., compound) | core | — | Old English | — | — | grammar_reference | n/a | n/a | the sale of people into slavery, named among Wulfstan's catalogue of England's social sins |
| manslyht | manslaughter | noun (masc., compound) | core | — | Old English | — | — | grammar_reference | n/a | n/a | — |
| forliger | fornication | noun (neut.) | taboo | — | Old English | — | — | grammar_reference | n/a | n/a | — |
| æwbryċe | adultery | noun (masc., compound: ǣ "law/marriage" + bryċe "breach") | taboo | — | Old English | — | — | grammar_reference | n/a | n/a | one of Wulfstan's several "-bryċe" compound abstractions for specific breaches of sacred/social obligation |
| āðbrīċe | perjury (lit. "oath-breach") | noun (masc., compound) | taboo | — | Old English | — | — | grammar_reference | n/a | n/a | — |
| hādbryċe | priest-killing/violating clerical status (lit. "order-breach") | noun (masc., compound) | taboo | — | Old English | — | — | grammar_reference | n/a | n/a | — |
| wedbryċe | oath-breaking (lit. "pledge-breach") | noun (masc., compound) | taboo | — | Old English | — | — | grammar_reference | n/a | n/a | a near-synonym of *āðbrīċe*, both appearing in the sermon's extended catalogue — evidence of the rhetorical "-bryċe" compounding pattern Wulfstan leans on repeatedly (cf. `pt06`'s note on his rhetorical word-formation) |
| sibleġer | incest (lit. "kin-lying") | noun (neut., compound) | taboo | — | Old English | — | — | grammar_reference | n/a | n/a | — |
| frēolsbriċe | non-observance of church festivals (lit. "freedom/feast-breach") | noun (masc., compound) | core | — | Old English | — | — | grammar_reference | n/a | n/a | — |
| fæstenbryċe | non-observance of fasts (lit. "fast-breach") | noun (masc., compound) | core | — | Old English | — | — | grammar_reference | n/a | n/a | — |
| stalu | theft | noun (fem.) | taboo | — | Old English | — | — | grammar_reference | n/a | n/a | — |
| strūdung | robbery, plunder | noun (fem.) | taboo | — | Old English | — | — | grammar_reference | n/a | n/a | — |
| searacræft | fraud, deceit (lit. "cunning-craft") | noun (masc., compound) | taboo | — | Old English | — | — | grammar_reference | n/a | n/a | — |
| swicdōm | betrayal, treachery | noun (masc., suffixoid *-dōm*, see `pt05`) | taboo | — | Old English | — | — | grammar_reference | n/a | n/a | the same *-dōm* suffixoid already documented in `pt05`, here attached to a betrayal/sin-themed root — direct evidence the pattern was productive across registers, not just the "wisdom/slavery" examples already captured |
| lēasung | lying, falsehood | noun (fem.) | taboo | — | Old English | — | — | grammar_reference | n/a | n/a | — |
| ġītsung | avarice, greed | noun (fem.) | taboo | — | Old English | — | — | grammar_reference | n/a | n/a | — |
| lēodhata | tyrant (lit. "people-hater") | noun (masc., compound) | core | — | Old English | — | — | grammar_reference | n/a | n/a | — |
| ċyriċhata | church-hater | noun (masc., compound, parallel formation to *lēodhata*) | taboo | — | Old English | — | — | grammar_reference | n/a | n/a | — |
| hetol | hostile | adjective | core | — | Old English | — | — | grammar_reference | n/a | n/a | — |
| grim / grimliċ | cruel | adjective | core | — | Old English | — | — | grammar_reference | n/a | n/a | two near-synonymous forms both glossed "cruel" in the same sermon |
| hōcorwyrde | derisive, mocking | adjective (compound) | core | — | Old English | — | — | grammar_reference | n/a | n/a | — |
| dysiġ | foolish | adjective | core | — | Old English | — | — | grammar_reference | n/a | n/a | — |
| unsidu | vice, bad custom | noun (masc., negative prefix un- + sidu "custom") | core | — | Old English | — | — | grammar_reference | n/a | n/a | — |
| unriht | wrong, injustice | noun (neut., un- + riht "right/justice") | core | — | Old English | — | — | grammar_reference | n/a | n/a | — |
| unlagu | illegality, injustice | noun (fem., un- + lagu "law" — note *lagu* itself is the Scandinavian loan documented in `pt05`) | core | — | Old English | — | — | grammar_reference | n/a | n/a | shows the borrowed Scandinavian legal term *lagu* (`pt05`) fully productive as the base of a native negative-prefix derivation within the same generation |
| hetol / grimliċ / unriht cluster — see individual entries | — | — | — | — | Old English | — | — | grammar_reference | n/a | n/a | (grouping note, not a separate entry) |
| cristen | Christian | adjective | core | — | Old English | — | — | grammar_reference | n/a | n/a | — |
| hāðen | heathen | adjective | core | — | Old English | — | — | grammar_reference | n/a | n/a | the sermon's central rhetorical opposition is implicitly *cristen* vs. *hāðen* — Christian England failing to live up to its own faith is Wulfstan's whole argument |
| dēofol | devil | noun (neut.) | core | — | Old English | — | — | grammar_reference | n/a | n/a | — |
| æswiċ | oath-breaking, scandal | noun (masc.) | taboo | — | Old English | — | — | grammar_reference | n/a | n/a | — |
| munuchād | monastic life, "monk-status" | noun (masc., compound with suffixoid -hād, see `pt05`) | formal | — | Old English | — | — | grammar_reference | n/a | n/a | a second attested use of the *-hād* suffixoid beside `pt05`'s *-hood* note |
| worldhād | secular life, "world-status" | noun (masc., compound with -hād, directly contrasting *munuchād*) | formal | — | Old English | — | — | grammar_reference | n/a | n/a | the explicit monastic/secular-life lexical opposition, both built on the same productive -hād pattern |
| ēċe | eternal | adjective | core | — | Old English | — | — | grammar_reference | n/a | n/a | — |
| ēġesliċ | terrible | adjective | core | — | Old English | — | — | grammar_reference | n/a | n/a | — |
| sum | a certain, some | pronoun/determiner | core | — | Old English | — | — | grammar_reference | n/a | n/a | closed-class item not yet captured in `pt01`–`pt06` |
| self | self | pronoun/adjective | core | — | Old English | — | — | grammar_reference | n/a | n/a | — |
| ōðer | other | adjective/pronoun | core | — | Old English | — | — | grammar_reference | n/a | n/a | — |
| oððe | or | conjunction | core | — | Old English | — | — | grammar_reference | n/a | n/a | closed-class coordinator not yet captured |
| swā | so, as | adverb/conjunction | core | — | Old English | — | — | grammar_reference | n/a | n/a | — |
| swā swā | just as | conjunction (doubled form of *swā*) | core | — | Old English | — | — | grammar_reference | n/a | n/a | — |
| hwā / ġehwā | who / everyone, whoever | pronoun / indefinite pronoun (ġe- prefixed, "collective" sense per `pt05`) | core | — | Old English | — | — | grammar_reference | n/a | n/a | *ġehwā* is a second clean example of `pt05`'s *ġe-* "collective/distributive" nominal-prefix sense, here on an interrogative/indefinite pronoun rather than a noun |
| middanġeard | world, "middle-enclosure" | noun (masc., compound) | literary | — | Old English | — | — | grammar_reference | n/a | n/a | the OE ancestor of the cognate Old Norse *Miðgarðr*; literary/elevated register word for "world" |
| ġesċeadwīs | discreet, reasonable | adjective (compound/derived) | core | — | Old English | — | — | grammar_reference | n/a | n/a | — |

## Grammar points

### Why this chunk's grammar is handled as a vocabulary-only supplement
Both back-matter glossaries are reference lists, not expository grammar text — there are no new
grammar *points* here beyond what's already fully covered in `pt01`–`pt06`'s Grammar points
sections. The one genuinely new piece of grammatical information this chunk surfaces is lexical-
semantic rather than morphosyntactic: the productive **sin/vice-compounding register** documented
in the Vocabulary table above (the dense cluster of *-bryċe* "breach" compounds, *un-* negative-
prefix abstractions, and *-dōm*/*-hād* suffixoid derivations all repurposed for moral/legal/social-
collapse vocabulary) is a genuine, previously-uncaptured instance of the word-formation machinery
`pt05` already documents being deployed systematically for a single thematic register — exactly
the kind of "different author's independent examples... in already covered territory" the
extraction spec's non-redundant-supplement pattern is designed to surface, found here internally
within the same book rather than across two different books.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`. **This file in
particular deliberately under-extracts its two back-matter source glossaries relative to their
full content** — see the Coverage note above for the explicit reasoning (avoiding wholesale
dictionary reproduction, avoiding redundancy with `pt01`–`pt06`, and deferring exhaustive OE
dictionary coverage to a dedicated future extraction of `18 A Concise Anglo-Saxon Dictionary.pdf`).
