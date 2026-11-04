# Swedish — Established Vocabulary/Grammar: Glossika Mass Sentences, Swedish Fluency 2 — Representative Sample

**Source:** Michael Campbell & Markus Bruus, *Glossika Mass Sentences: Swedish — Complete Fluency
Course, Fluency 2* (Glossika, first published Aug 2014). PDF is 368 pages. This volume continues the
series' cumulative sentence numbering: Fluency 1 = sentences 1–1000, **this book (Fluency 2) =
sentences 1001–2000**, Fluency 3 = sentences 2001–3000. Page offset confirmed empirically by direct
rendering: **PDF page = printed footer page number + 6** (e.g. PDF page 50 shows footer "44";
sentence content begins around PDF page 34–35, i.e. printed page ~28–29). Sampled page ranges (PDF
page numbers): **36–40, 66–70, 96–100, 126–130, 156–160, 186–190, 216–220, 246–250 (gap at 249),
276–280, 306–310, 336–340, 360–364.**

---

## CORRECTION to original task brief: this source has NO usable text layer

The dispatching orchestrator's brief stated this book has a real text layer. **That is false.**
Verified directly: `pdftotext -f 50 -l 52 <file> -` returns essentially nothing (the whole 368-page
book's total extracted character count is only ~6,720 characters — almost certainly just scattered
front-matter/metadata, not body content), and `pdfimages -list` shows **zero raster images** on
content pages either. The sentence text is drawn as vector outline paths with no character-to-Unicode
mapping — this is neither a decodable font-substitution cipher (no CID/glyph table to even attempt
decoding) nor an image-based scan (no embedded raster to OCR). It is genuinely vision-only, and this
volume shares an identical whole-book character-count fingerprint with Fluency 1 and Fluency 3 of the
same series (confirmed by a sibling dispatch on Fluency 3), strongly suggesting the same
InDesign/Adobe PDF Library production pipeline produced all three volumes with this same defect.
**Every triplet below was read directly from rendered page images (`pdftoppm -r 150`), not extracted
as text.** This is a new, generically-relevant gotcha for this project (a vector-outline PDF with no
ToUnicode map at all, distinct from every font-substitution-cipher variant already catalogued in
`00_Reference_Extraction_Spec.md`) and is worth adding there as its own entry if a sibling dispatch
hasn't already done so.

## Coverage note — representative sample, NOT exhaustive

This book holds **~1000 sentence triplets (1001–2000) across roughly 330 content pages (~3
triplets/page)** — a page-by-page vision-reading job, not a cheap text-layer pull. Per the dispatch
brief, this chunk vision-read a representative, evenly-spread sample rather than the full book: **177
triplets** total (somewhat above the ~100–150 target range named in the dispatch brief — page density
ran consistently close to 3 clean triplets/page across every cluster, so once a cluster of pages was
rendered it was cheap to transcribe in full rather than discard legible content), drawn from 12
clusters of mostly-5 consecutive pages spread evenly across the book's full range:

| Cluster | PDF pages | Sentences | Count |
|---|---|---|---|
| 1 | 36–40 | 1007–1021 | 15 |
| 2 | 66–70 | 1097–1111 | 15 |
| 3 | 96–100 | 1187–1201 | 15 |
| 4 | 126–130 | 1277–1291 | 15 |
| 5 | 156–160 | 1367–1381 | 15 |
| 6 | 186–190 | 1457–1471 | 15 |
| 7 | 216–220 | 1547–1561 | 15 |
| 8 | 246–250 | 1637–1651 (gap: 1646–1648 on unread page 249) | 12 |
| 9 | 276–280 | 1727–1741 | 15 |
| 10 | 306–310 | 1817–1831 | 15 |
| 11 | 336–340 | 1907–1921 | 15 |
| 12 | 360–364 | 1979–1993 | 15 |

**A full-coverage pass of this source (the remaining ~820 triplets), if ever wanted, should be
planned as its own dedicated vision-reading wave** — rendering and reading ~330 pages one by one is
not the kind of cheap bulk pull a text-layer source would be, and shouldn't be assumed free. Fluency
1 (`012_glossika_swedish_1.md`) of this same series is being extracted in parallel by a sibling
subagent using the same methodology and the same representative-sample scope decision; Fluency 3
(`014_glossika_swedish_3.md`) has already landed using this same approach.

**No handwritten marginalia found** — all 60 rendered pages are clean born-digital typeset pages with
no evidence of a prior owner's annotations.

**Format note:** every item is a numbered `EN` (English) / `SV` (Swedish) / `IPA` (bracketed
phonetic transcription) triplet. Like the Fluency 3 volume, this book omits IPA transcription for
personal/proper names (e.g. Masaru, Jianhong, Deepak, Lakshmi, Herman, Daisuke, Aiko, Filippa,
Qasim, Zahida, Pablo, Jirou, Kelly, Giovanni, Emilia, Luka, Nadya, Maalik, Jasmine, Michiko, Lucien,
Noboru, Lilianne, Vincent, Valerie, Nikolai, Victoria), replacing the name's phonetic slot with a
literal `(...)` exactly as printed — preserved as such below.

---

## Vocabulary

Pulled from recurring/notable lexical items across the 177 sampled triplets — not every word of
every sentence (this is a sentence-mining course, not a word list; see the Sample sentences section
below for full triplets).

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| arbeta / jobba | to work | verb (register pair) | core / colloquial | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | Both verbs recur throughout the sample with the same meaning; `arbeta` is the neutral/formal default (1098, 1101, 1201, 1281...), `jobba` appears in explicitly casual contexts ("du ska jobba så hårt", 1465) — a genuine formal/colloquial synonym pair, not free variation. |
| studera / plugga | to study | verb (register pair) | core / slang | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | Minimal pair on facing drill lines: "Jag ska studera i kväll" (1469) vs. "Jag måste plugga ikväll" (1470) — identical sentence frame, only the verb swapped, strongly confirming `plugga` is the colloquial/slang register option for `studera`. |
| tycka om / gilla | to like | verb (register pair) | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | `tycka om` (lit. "think about/of") is the idiomatically Swedish construction (1111, 1193); `gilla` is a more direct, English-"like"-shaped verb used interchangeably in later clusters (1553, 1555, 1557, 1990). |
| tänka / tycka / fundera (på) | to think (three distinct senses) | verb (semantic set) | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | plausible_unverified | `tycka` = to hold an opinion ("jag tycker att...", 1462, 1465); `fundera på` = to contemplate/consider ("Funderar du på att köpa en bil?", 1988). `tänka` itself did not surface directly in the sampled triplets but the three-way opinion/contemplation split visible here is a genuine lexical-semantic pattern worth tracking in a fuller pass. |
| sa / sade | said (past of säga) | verb (register pair, same lemma) | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | `sade` (full written form) appears once (1907, "Maalik sade att...") while `sa` (contracted spoken form) is used throughout the rest of the sample (1908, 1909, 1910, 1911...) — consistent with `sa` being the normal spoken-register form and `sade` a more formal/written alternative. |
| kanske | maybe / might | adverb (modal) | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | Governs an unchanged indicative verb rather than a subjunctive form, e.g. "Jag kanske ska åka till Italien" (1367) — modality carried by the adverb, not by verb morphology. |
| bör / borde | should (present / past-conditional) | verb (modal) | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | `bör` = present-tense recommendation ("du bör alltid titta på bollen", 1457); `borde` = softer/conditional "ought to" ("Leopold borde inte gå till sängs så sent", 1460). Both recur across the whole should/ought cluster (1457–1471). |
| måste | must / have to | verb (modal) | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | Strong obligation, contrasted directly with the weaker `bör`/`borde` cluster on the same pages, e.g. "Jag måste plugga ikväll" (1470). |
| i morse | this morning (already past) | adverbial phrase (fixed idiom) | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | "jag var sen i morse" (1289) — distinct from `i morgon` ("tomorrow"); a false-friend-adjacent pair for learners since `morse`/`morgon` look related but point to opposite time directions. |
| i morgon bitti | tomorrow morning | adverbial phrase (fixed idiom) | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | "Han kanske ska vara hemma i morgon bitti" (1377) — `bitti` occurs in this project's sample only inside this fixed collocation, never standalone. |
| ikväll / i kväll | tonight | adverbial (orthographic variants) | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | Both the fused one-word spelling (`ikväll`, e.g. 1100, 1280) and the two-word spelling (`i kväll`, e.g. 1371, 1469, 1552) occur for the identical word across the sample — an orthographic-variation flag, not two different words. |
| imorgon / i morgon | tomorrow | adverbial (orthographic variants) | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | Same fused-vs-split spelling variation as `ikväll`/`i kväll` above (fused: 1200, 1561; split: 1281, 1373). |
| gå på bio | to go to the movies | verb phrase (idiom) | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | `bio` is a clipped/shortened form of `biograf` (cinema); recurs heavily across clusters 6–8 (1469, 1552, 1553, 1558...). |
| gå till sängs | to go to bed | verb phrase (idiom) | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | "Leopold borde inte gå till sängs så sent" (1460) — fixed idiom with a genitive-looking `-s` suffix on `säng` (bed) that doesn't function as a normal possessive. |
| lägga sig | to go to bed / lie down | verb (reflexive) | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | "gå och lägg dig tidigt" (1287, lit. "go and lay yourself early") — reflexive variant alongside the idiom above; both mean "go to bed" but with different literal imagery. |
| gå upp / gå ut / gå sönder | to get up / to go out / to break (particle verbs) | verb (particle-verb set) | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | `gå upp` = get up (1375, lit. "go up"); `gå ut` = go out (1374, 1380, 1639, 1645); `gå sönder` = break/get broken (1106, lit. "go broken") — `gå` + adverbial particle is a productive pattern across the sample, parallel to English phrasal verbs. |
| sätta på / slappna av / bjuda in | to turn on / to relax / to invite | verb (particle-verb set) | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | Further particle verbs: "Ska jag sätta på lite musik?" (1640); "jag sa till henne att slappna av" (1914); "Ska jag bjuda in Sara till middag?" (1458). |
| skynda sig / göra sig redo / gifta sig / bestämma sig / låtsas / födas | to hurry up / to get ready / to get married / to decide / to pretend / to be born | verb (reflexive and deponent s-verbs) | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | `skynda sig`, `göra sig redo`, `gifta sig`, `bestämma sig` are ordinary reflexive verbs (self-directed action, 1913, 1913, 1830, 1372/1988). `låtsas` (1991, 1992) and `födas` (1729) are deponent — they exist **only** in the `-s` form with no corresponding non-`-s` active verb, distinct from the true s-passive described in Grammar points below. |
| mår (må) | to feel (health/wellbeing) | verb | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | "Jag mår inte bra ikväll" (1286, lit. "I fare not well") — a dedicated wellbeing verb distinct from `känna` (to feel/touch/sense, e.g. "Jag känner mig trött", 1551). |
| snälla | please (politeness particle) | interjection / adverb | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | "Jag vill ha lite information om hotell, snälla" (1550) — the adjective `snäll` ("kind") repurposed as a bare politeness marker, parallel to `var snäll och...` ("be kind and...", 1098) as a periphrastic imperative softener. |
| ursäkta | sorry / excuse me | interjection | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | "Är jag? Ursäkta." (1821). |
| verkligen | really | adverb (discourse marker) | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | "Gjorde hon? Verkligen?" (1830) — stand-alone discourse-marker use in an incredulous follow-up question. |
| helt säkert / en hel del / hela tiden / ett tag / så fort som möjligt / på grund av / komma för sent / ha gott om | for sure; a lot/quite a bit; all the time; a while; as soon as possible; because of; to be late; to have plenty of | idiomatic fixed phrases (various) | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | Cluster of recurring fixed phrases: "Han går helt säkert ut" (1379); "jag går på bio en hel del" (1553); "Du tittar på TV hela tiden" (1461); "låt oss vänta ett tag" (1642); "försöka lämna så fort som möjligt" (1979); "vi beslutade att inte gå ut på grund av vädret" (1986); "jag lovade att inte komma för sent" (1987); "De verkar ha gott om pengar" (1989). |
| gå ner i vikt | to lose weight | verb phrase (idiom) | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | "Du verkar ha gått ner i vikt" (1993, lit. "go down in weight"). |
| köra bil | to drive (a car) | verb phrase (verb + bare noun collocation) | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | "Giovanni kan inte köra bil" (1825) — bare singular noun with no article, parallel to English "ride bike"-type collocations. |
| titta på | to watch / look at | verb phrase | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | "Han kan titta på tv" (1378); "du bör inte titta på TV så mycket" (1461). |
| misslyckas (med att) | to fail (to) | verb | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | "Valerie misslyckades med att göra ett gott intryck" (1985) — morphologically transparent negative prefix `miss-` + `lyckas` ("succeed"), parallel to English "mis-" + "succeed" were that a real English word. |
| gick med på (gå med på) | agreed to | verb phrase (particle-verb idiom) | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | "jag gick med på att hjälpa honom" (1983, lit. "went along with on"). |
| tulltjänsteman / anställningsintervju / körkortsprov | customs officer / job interview / driving test | noun (compound) | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | Three transparent multi-root compound nouns: `tull` (customs) + `tjänsteman` (official); `anställning` (employment) + `intervju` (interview); `körkort` (driver's license) + `prov` (test). |
| klara (sitt prov) | to pass (a test) | verb | colloquial | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | "Euna kommer att klara sitt körkortsprov" (1290) — colloquial "manage/pull off" sense extended to "pass [a test]", distinct from the more literal `passera`/`godkännas`. |
| en drink / okej | a (alcoholic) drink / okay | noun / interjection (English loanwords) | colloquial | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | "Jag vill ha en drink" (1549); "Är det okej att ringa dig på kontoret?" (1736) — direct English loanwords fully integrated into Swedish grammar (indefinite article on `drink`). |
| mil | Swedish mile = 10 km | noun (false friend) | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | "Det är 10 (tio) mil från centrum till flygplatsen" (1735) is glossed in the book's own EN line as "It's 10 (ten) kilometers..." — but Swedish `mil` is a fixed unit equal to 10 km, so the literal SV reading is ~100 km, not 10. Flagged as either a genuine EN/SV translation inconsistency in this specific sentence pair, or an instructive false-friend example either way (English "mile" ≠ Swedish `mil`, and neither equals a kilometer) — worth treating `mil` itself as a notable vocabulary item regardless of which explanation is correct. |
| bli + [number] (år) | to turn/become [age] | verb phrase | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | "Han blir tjugofem" (1288, lit. "he becomes twenty-five") — standard age-expression construction using `bli`, not `vara`. |

**No morpheme breakdowns added.** As with the sibling Fluency 3 extraction, Swedish's compounding is
transparent enough in the sampled terms (`tulltjänsteman`, `anställningsintervju`, `körkortsprov`)
that a root-by-root note inline in the Notes field is sufficient; none of the sampled terms needed a
dedicated breakdown block.

## Grammar points

### Two passive constructions: periphrastic (vara/bli + past participle) vs. synthetic (-s suffix)

The sample repeatedly contrasts the two major ways Swedish forms a passive, sometimes within the
same drilled sentence pair. Periphrastic passive with `vara` (state/result): "Kontoret är städat
varje dag" (1010, the office is [in a state of being] cleaned). Periphrastic with `bli` (event/
process, closer to English "get X-ed"): "Kontoret blev städat igår" (1105). Synthetic s-passive
(adds `-s` directly to the verb stem, no auxiliary): "Kontoret städades igår" (also 1105, same
sentence drilled with both forms back to back) and "Två personer fördes till sjukhus" (1021, "were
taken to hospital"), "väcktes upp" (1191, "were woken up"), "Alla biljetterna... såldes ut" (1197,
"were sold out"). Sentence 1105 is the clearest evidence this is a deliberate three-way contrast
drilled by the book itself, not incidental variation: "Kontoret blev städat igår. Kontoret städades
igår." presents the `bli`-passive and s-passive back to back as near-paraphrases of the same event.

### Deponent s-verbs (distinct from the true s-passive above)

Some Swedish verbs exist **only** in the `-s` form, with no corresponding non-`-s` active verb —
these are not passives of anything, just lexically fixed in `-s` shape. Confirmed twice in the
sample: `födas` ("to be born" — "jag föddes" / "han föddes", 1729, there is no active verb `föda
[someone]` meaning the same thing in this context) and `låtsas` ("to pretend" — "Jag låtsades läsa
tidningen", 1992; "Nikolai låtsades inte se mig", 1991). Worth keeping conceptually separate from the
productive s-passive pattern above when this grammar point is revisited in a fuller pass, since
surface `-s` morphology alone doesn't distinguish the two.

### Short-answer echo construction: fronted pro-form + auxiliary + subject

A recurring question-answer pattern across cluster 10 (1817–1831): a short affirmative/incredulous
follow-up answer is formed by fronting either `det` ("that/it") or the original question word, then
the auxiliary verb, then the subject — mirroring the auxiliary of the preceding statement rather than
defaulting to a generic "yes/no". Examples: "Har du någonsin brutit armen? - Ja, **det har jag**."
(1818, lit. "that have I"); "Köpte du något igår? - Ja, **det gjorde jag**." (1819); "Du är sen. -
**Är jag**? Ursäkta." (1821, bare subject-auxiliary inversion with no `det`); "Det regnar igen. -
**Gör det**?" (1823); "Jag talar fyra språk. - **Gör du**? Vilka?" (1828). This is structurally
distinct from English's "I do/I have/I am" short-answer system — Swedish echoes the *specific*
auxiliary (har/gjorde/är/gör) from the stimulus sentence, V2-inverted around the subject, with `det`
present or dropped depending on whether the original statement's main verb needs a dummy pro-form
substitute (`gjorde`/`har` typically get `det`; `är`/modal `kan` typically invert bare). Confirmed as
a systematic pattern, not a one-off, across all 15 sampled items in this cluster.

### Sequence-of-tense backshifting in reported speech (explicitly marked by the source)

Cluster 11 (1907–1921) drills reported-speech backshifting using the book's own `>` notation to show
a present-tense direct quote becoming past tense once embedded under a past-tense reporting verb:
"Jasmine sa att hennes nya jobb **är** ganska intressant. > Jasmine sa att hennes nya jobb **var**
ganska intressant." (1908); "Hon berättade att hon **vill** åka till Sydamerika nästa år. > Hon sa
att hon **ville** åka till Sydamerika nästa år." (1909). This mirrors the English sequence-of-tense
rule shown in the same sentence pairs, suggesting the book is drilling the two languages' parallel
(not divergent) backshifting behavior here, unlike the preposition-mismatch teaching device the
sibling Fluency 3 extraction found in that volume.

### Register pairs: formal/neutral vs. colloquial synonyms for the same concept

Confirmed as a systematic pattern, not isolated word choice: `arbeta`/`jobba` (work), `studera`/
`plugga` (study — with `plugga` specifically slang-register, see Vocabulary table), `tycka om`/
`gilla` (like), and `sa`/`sade` (said, spoken-contracted vs. written-formal). The `studera`/`plugga`
pair is the strongest evidence, since sentences 1469 and 1470 use the identical sentence frame
("I should/have to study tonight...") with only the verb swapped between the two registers.

### Modal verb gradient: bör/borde (recommendation) vs. måste (obligation) vs. kanske + indicative (possibility)

The sample's clusters 6–8 (1457–1651) systematically drill a three-way modal-strength gradient: weak
recommendation with `bör`/`borde` ("du bör alltid titta på bollen", 1457), strong obligation with
`måste` ("Jag måste plugga ikväll", 1470), and simple possibility with the adverb `kanske` governing
an unchanged indicative verb rather than any special mood morphology ("Jag kanske ska åka till
Italien", 1367). This three-way split is drilled extensively enough (30+ sampled sentences across the
two clusters) to be a genuine organizing grammar point of this part of the book, not incidental.

### Possible source errors (flagged, not silently corrected)

Several sentences in the sample show irregularities that read as genuine editorial/typesetting
errors rather than vision-reading misreads (all re-checked at 150dpi on clean, legible print pages):

- **1277**: EN reads "Three days ago she was in **Santiago**" but SV reads "...var hon i
  **Singapore**" — an EN/SV place-name mismatch within the same drilled sentence pair.
- **1464**: SV reads "Ja, **jag det** tycker jag att du borde" — the word order looks scrambled
  (an extra/misplaced `jag`); a grammatical reading would be closer to "Ja, det tycker jag att du
  borde."
- **1918**: SV reads "Vilken buss går **downtown**?" — the English word is left completely
  untranslated where ordinary Swedish would use `till centrum` or similar; likely an editing
  oversight rather than intentional code-switching, since no other sampled sentence leaves an
  English content word untranslated.
- **1919 vs. 1921**: two near-identical "who/to whom do you want to speak" sentences in the same
  cluster — 1919 includes the preposition ("Vem vill du prata **med**?") but 1921 drops it ("Vem
  vill du prata?"), despite the EN line for 1921 ("To whom do you wish to speak?") if anything
  implying the preposition is *more* salient, not less.
- **1979**: SV reads "Ska vi **skjuta lämnar** i dag till i morgon?" for EN "Should we postpone
  leaving today until tomorrow?" — this does not parse as grammatical Swedish; the expected
  construction would be closer to `skjuta upp att lämna` (lit. "push up to leave" = postpone
  leaving). `skjuta` alone does not mean "postpone" without the particle `upp`.
- **1980**: SV reads "Det **håller den går** sönder" for EN "It keeps breaking down" — again does
  not parse smoothly; the expected construction would be closer to `Den håller på att gå sönder`
  (lit. "it holds on to go broken" = it keeps [on] breaking).

These are reported descriptively rather than corrected, consistent with the extraction spec's
discipline around distinguishing source errors from transcription errors — a fuller pass of this
book should re-verify whether these are genuine print errors or (less likely, given the clean
150dpi renders) OCR-adjacent misreads on this subagent's part.

---

## Sample sentences

Full EN / SV / IPA triplets as printed, grouped by sampled page cluster. `(...)` marks the source's
own convention of omitting IPA for a proper name (see format note above). Presented per this
dispatch's explicit instruction to preserve the sentence-pair format as raw corpus material, not as
bulk reproduction of explanatory prose — see copyright note at the end of this file.

### Cluster 1 — PDF pages 36–40 (sentences 1007–1021)

| # | EN | SV | IPA |
|---|---|---|---|
| 1007 | I've seen her a few times, but I've never spoken to her. | Jag har träffat henne några gånger, men har aldrig pratat med henne. | [ jaɣ har tʰrɛfat henə noɣra goŋer \| men har aldrɛj pʰratat med henə ‖ ] |
| 1008 | Have you ever spoken to her? | Har du någonsin pratat med henne? | [ har du nogunsin pʰratat med henə ‖ ] |
| 1009 | I met her at a party last week. She's very nice. | Jag träffade henne på en fest förra veckan. Hon är väldigt trevlig. | [ jaɣ tʰrɛfadə henə pʰo en fest fœra vekjan ‖ hun ɛr vɛldijt tʰrevlɛj ‖ ] |
| 1010 | Somebody cleans the office every day. The office is cleaned every day. | Någon städar kontoret varje dag. Kontoret är städat varje dag. | [ nogun stɛdar kʰunturet varjə daɣ ‖ kʰunturet ɛr stɛdat varjə daɣ ‖ ] |
| 1011 | Somebody cleaned the office yesterday. The office was cleaned yesterday. | Någon städade kontoret igår. Kontoret var städat igår. | [ nogun stɛdadə kʰunturet igor ‖ kʰunturet var stɛdat igor ‖ ] |
| 1012 | Butter is made from milk. | Smör är gjort av mjölk. | [ smør ɛr jut av mjølk ‖ ] |
| 1013 | Oranges are imported into Canada. | Apelsiner är importerade till Kanada. | [ apelsiner ɛr importeradə tʰɪl kʰjanada ‖ ] |
| 1014 | How often are these rooms cleaned? | Hur ofta är de här rummen städade? | [ hur ufta ɛr dɛ hɛr rɵmen stɛdadə ‖ ] |
| 1015 | I'm never invited to parties. | Jag är aldrig bjuden till fester. | [ jaɣ ɛr aldrɛj bjuden tʰɪl fester ‖ ] |
| 1016 | This house was built 100 years ago. | Det här huset var byggt för hundra år sedan. | [ də hɛr huset var bygt før hundra or sedan ‖ ] |
| 1017 | These houses were built 100 years ago. | De här husen var byggda för hundra år sedan. | [ dɛ hɛr husen var bygda før hundra or sedan ‖ ] |
| 1018 | When was the telephone invented? | När var telefonen uppfunnen? | [ nɛr var tʰelefunen ʊpfɵnen ‖ ] |
| 1019 | We weren't invited to the party last week. | Vi var inte bjudna på festen förra veckan. | [ vi var intə bjudna pʰo festen fœra vekjan ‖ ] |
| 1020 | Was anybody injured in the accident? | Var någon skadad i olyckan? | [ var nogun skjadad i ulykjan ‖ ] |
| 1021 | Two people were taken to the hospital. | Två personer fördes till sjukhus. | [ tʰvo pʰɛsuner fødes tʰɪl ɧukhus ‖ ] |

### Cluster 2 — PDF pages 66–70 (sentences 1097–1111)

| # | EN | SV | IPA |
|---|---|---|---|
| 1097 | It hasn't gotten repaired yet. | Den har inte reparerats ännu. | [ den har intə reparerats ɛnu ‖ ] |
| 1098 | Please be quiet. I'm working. | Var snäll och var tyst. Jag arbetar. | [ var snɛl ɔɣ var tʰyst ‖ jaɣ arbetar ‖ ] |
| 1099 | It isn't raining right now. | Det regnar inte just nu. | [ də reŋnar intə just nu ‖ ] |
| 1100 | What are you doing tonight? | Vad ska du göra ikväll? | [ vad skja du jøra ikvɛl ‖ ] |
| 1101 | I was working when she arrived. | Jag arbetade, när hon anlände. | [ jaɣ arbetadə \| nɛr hun anlɛndə ‖ ] |
| 1102 | It wasn't raining, so we didn't need an umbrella. | Det regnade inte, så vi behövde inte något paraply. | [ də reŋnadə intə \| so vi behøvdə intə nogut pʰaraply ‖ ] |
| 1103 | What were you doing at 3:00? | Vad gjorde du vid 3? | [ vad judə du vid 3 ‖ ] |
| 1104 | These offices aren't cleaned every day. | De här kontoren städas inte varje dag. | [ dɛ hɛr kʰunturen stɛdas intə varjə daɣ ‖ ] |
| 1105 | The office was cleaned yesterday. The office got cleaned yesterday. | Kontoret blev städat igår. Kontoret städades igår. | [ kʰunturet blev stɛdat igor ‖ kʰunturet stɛdades igor ‖ ] |
| 1106 | How was the window broken? How did the window get broken? | Hur gick fönstret sönder? Hur gick fönstret sönder? | [ hur jɪk fønstret sønder ‖ hur jɪk fønstret sønder ‖ ] |
| 1107 | I've lived in this house for 10 years. | Jag har bott i det här huset i 10 år. | [ jaɣ har bʊt i də hɛr huset i 10 or ‖ ] |
| 1108 | Dietrich has never ridden a horse. | Dietriech har aldrig ridit på en häst. | [ dietriɛɣ har aldrɛj ridit pʰo en hɛst ‖ ] |
| 1109 | Filippa hasn't been to South America. | Filippa har aldrig varit i Sydamerika. | [ (...) har aldrɛj varit i sydamerikja ‖ ] |
| 1110 | Where have Daisuke and Aiko gone? | Vart har Daisuke och Aiko gått? | [ vaʈ har (...) ɔɣ (...) gɔt ‖ ] |
| 1111 | I like coffee, but I don't like tea. | Jag tycker om kaffe, men jag tycker inte om te. | [ jaɣ tʰyker um kʰafə \| men jaɣ tʰyker intə um tʰe ‖ ] |

### Cluster 3 — PDF pages 96–100 (sentences 1187–1201)

| # | EN | SV | IPA |
|---|---|---|---|
| 1187 | My brother ran in the Boston Marathon last year. Have you ever run in a marathon? | Min bror sprang Boston maraton förra året. Har du någonsin sprungit ett maraton? | [ min brur spraŋ (...) maratun fœra oret ‖ har du nogunsin sprʊŋit et maratun ‖ ] |
| 1188 | Have you told Herman about your new job? | Har du berättat för Herman om ditt nya arbete? | [ har du berɛtat før (...) um dɪt nya arbetə ‖ ] |
| 1189 | We played basketball on Sunday. We didn't play very well, but we won the game. | Vi spelade basket i söndags. Vi spelade inte så bra men vi vann matchen. | [ vi speladə baʃet i søndaɣs ‖ vi speladə intə so bra men vi van matʃen ‖ ] |
| 1190 | I know Masaru, but I've never met his wife. | Jag känner Masaru, men jag har aldrig träffat hans fru. | [ jaɣ çɛner masaru \| men jaɣ har aldrɛj tʰrɛfat hans fru ‖ ] |
| 1191 | We were woken up by loud music in the middle of the night. | Vi väcktes upp av hög musik mitt i natten. | [ vi vɛktes ɵp av høɣ musik mɪt i naten ‖ ] |
| 1192 | Kimiko jumped into the river and swam to the other side. | Kimiko hoppade ner i floden och simmade till den andra sidan. | [ (...) hupadə ner i fluden ɔɣ sɪmadə tʰɪl den andra sidan ‖ ] |
| 1193 | Did you like the movie? Yes, I thought it was very good. | Tyckte du om filmen? Ja, jag tyckte den var väldigt bra. | [ tʰyktə du um filmen ‖ ja \| jaɣ tʰyktə den var vɛldijt bra ‖ ] |
| 1194 | Many different languages are spoken in the Philippines. | Många olika språk talas i Filippinerna. | [ moŋa ulikja sprok tʰalas i filɪpineŋa ‖ ] |
| 1195 | Our vacation cost a lot of money because we stayed in an expensive hotel. | Vår semester kostade mycket pengar därför att vi bodde på ett dyrt hotell. | [ vor semester kʰustadə myket pʰeŋar dɛrfør at vi budə pʰo et dyʈ hutel ‖ ] |
| 1196 | Have you ever driven a very fast car? | Har du någonsin kört en bil väldigt fort? | [ har du nogunsin çøʈ en bil vɛldijt fuʈ ‖ ] |
| 1197 | All the tickets for the concert were sold very quickly. | Alla biljetterna till konserten såldes ut väldigt fort. | [ ala bijeteŋa tʰɪl kʰunseʈen soldes ʉt vɛldijt fuʈ ‖ ] |
| 1198 | A bird flew in through the open window while we were having our dinner. | En fågel flög in genom det öppna fönstret under tiden vi åt middag. | [ en fojel fløɣ in jenum də œpna fønstret ʉnder tʰiden vi ot mɪdaɣ ‖ ] |
| 1199 | Where are Deepak and Lakshmi? — They're playing tennis in the park. | Var är Deepak och Lakshmi? - De spelar tennis i parken. | [ var ɛr (...) ɔɣ (...) ‖ — dɛ spelar tʰenis i pʰarken ‖ ] |
| 1200 | Pavel's playing tennis tomorrow. | Pavel ska spela tennis imorgon. | [ (...) skja spela tʰenis imurgun ‖ ] |
| 1201 | I'm not working next week. | Jag arbetar inte nästa vecka. | [ jaɣ arbetar intə nɛsta vekja ‖ ] |

### Cluster 4 — PDF pages 126–130 (sentences 1277–1291)

| # | EN | SV | IPA |
|---|---|---|---|
| 1277 | Three days ago she was in Santiago. *(SV says "Singapore" — see Grammar points, possible source error)* | För tre dagar sedan var hon i Singapore. | [ før tʰrə dagar sedan var hun i (...) ‖ ] |
| 1278 | At the end of her trip she'll be very tired. | I slutet av hennes resa kommer hon att vara väldigt trött. | [ i slutet av henes resa kʰumer hun at vara vɛldijt tʰrœt ‖ ] |
| 1279 | I'll be at the movies an hour from now. | Jag kommer att vara på biografen om en timme. | [ jaɣ kʰumer at vara pʰo biuɣrafen um en tʰɪmə ‖ ] |
| 1280 | I'll be asleep at midnight tonight. | Jag kommer att sova vid midnatt ikväll. | [ jaɣ kʰumer at suva vid midnat ikvɛl ‖ ] |
| 1281 | I'll be working at 3:00 tomorrow afternoon. | Jag ska arbeta i morgon eftermiddag vid 3:00. | [ jaɣ skja arbeta i murgun eftermidaɣ vid 3 \|00 ] |
| 1282 | I'll be at a new job two years from now. | Jag kommer att vara på ett nytt arbete om två år. | [ jaɣ kʰumer at vara pʰo et nyt arbetə um tʰvo or ‖ ] |
| 1283 | Are you ready yet? — Not yet. I'll be ready in five minutes. | Är du klar än? - Inte än. Jag kommer att vara klar om fem minuter. | [ ɛr du kʰlar ɛn ‖ — intə ɛn ‖ jaɣ kʰumer at vara kʰlar um fem minuter ‖ ] |
| 1284 | I'm going away for a few days. I'm leaving tonight, so I won't be at home tomorrow. | Jag ska resa bort i några dagar. Jag reser ikväll, så jag kommer inte att vara hemma i morgon. | [ jaɣ skja resa buʈ i noɣra dagar ‖ jaɣ reser ikvɛl \| so jaɣ kʰumer intə at vara hema i murgun ‖ ] |
| 1285 | It won't rain, so you don't need to take an umbrella. | Det kommer inte att regna, så du behöver inte ta med dig något paraply. | [ də kʰumer intə at reŋna \| so du behøver intə tʰa med dɛj nogut pʰaraply ‖ ] |
| 1286 | I don't feel very well tonight. | Jag mår inte bra ikväll. | [ jaɣ mor intə bra ikvɛl ‖ ] |
| 1287 | Well, go to bed early and you'll feel better in the morning. | Så gå och lägg dig tidigt så kommer du att må bättre i morgon. | [ so go ɔɣ lɛg dɛj tʰidijt so kʰumer du at mo bɛtrə i murgun ‖ ] |
| 1288 | It's Qasim's birthday next Monday. He'll be 25. | Det är Qasims födelsedag nästa måndag. Han blir tjugofem. | [ də ɛr (...)s fødelsedaɣ nɛsta mondaɣ ‖ han blir çuguфem ‖ ] |
| 1289 | I'm sorry I was late this morning. It won't happen again. | Förlåt att jag var sen i morse. Det kommer inte att hända igen. | [ fœlot at jaɣ var sen i musə ‖ də kʰumer intə at hɛnda ijen ‖ ] |
| 1290 | I think Euna will pass her driver's test. | Jag tror att Euna kommer att klara sitt körkortsprov. | [ jaɣ tʰrur at (...) kʰumer at kʰlara sɪt çørkuʈspruv ‖ ] |
| 1291 | I don't think Jiyeong will pass his driver's test. | Jag tror inte att Jieong kommer att klara sitt körkortsprov. | [ jaɣ tʰrur intə at jiuŋ kʰumer at kʰlara sɪt çørkuʈspruv ‖ ] |

### Cluster 5 — PDF pages 156–160 (sentences 1367–1381)

| # | EN | SV | IPA |
|---|---|---|---|
| 1367 | Where are you going for your vacation? — I'm not sure. I might go to Italy. | Vart ska du åka på din semester? - Jag är inte säker. Jag kanske ska åka till Italien. | [ vaʈ skja du okja pʰo din semester ‖ - jaɣ ɛr intə sɛker ‖ jaɣ kʰjanɕə skja okja tʰɪl italien ‖ ] |
| 1368 | What are you doing this weekend? — I don't know. I might go hiking. | Vad gör du i helgen? - Jag vet inte. Jag kanske ska vandra. | [ vad jør du i heljen ‖ - jaɣ vet intə ‖ jaɣ kʰjanɕə skja vandra ‖ ] |
| 1369 | When will you see Pablo again? — I'm not sure. I might see him this summer. | När kommer du att se Pablo igen? - Jag är inte säker. Jag kanske ska träffa honom i sommar. | [ nɛr kʰumer du at sə (...) ijen ‖ - jaɣ ɛr intə sɛker ‖ jaɣ kʰjanɕə skja tʰrɛfa hunum i sumar ‖ ] |
| 1370 | What are you going to have for dinner? — I don't know. I might have Italian food. | Vad ska du ha till middag? - Jag vet inte. Jag kanske har italiensk mat. | [ vad skja du ha tʰɪl mɪdaɣ ‖ - jaɣ vet intə ‖ jaɣ kʰjanɕə har italiensk mat ‖ ] |
| 1371 | How are you going to get home tonight? — I'm not sure. I might take the bus. | Hur kommer ni att komma hem i kväll? - Jag är inte säker. Jag kanske ska ta bussen. | [ hur kʰumer ni at kʰuma hem i kvɛl ‖ - jaɣ ɛr intə sɛker ‖ jaɣ kʰjanɕə skja tʰa bɵsen ‖ ] |
| 1372 | I hear you won some money. What are you going to do with it? — I haven't decided yet. I might open a restaurant. | Jag hörde att du vann lite pengar. Vad ska du göra med det? - Jag har inte bestämt mig än. Jag kanske ska öppna en restaurang. | [ jaɣ høɖə at du van litə pʰeŋar ‖ vad skja du jøra med də ‖ - jaɣ har intə bestɛmt mɛj ɛn ‖ jaɣ kʰjanɕə skja œpna en restauraŋ ‖ ] |
| 1373 | He's playing tennis tomorrow afternoon. | Han spelar tennis i morgon eftermiddag. | [ han spelar tʰenis i murgun eftermidaɣ ‖ ] |
| 1374 | He might go out tomorrow evening. | Han kan gå ut i morgon kväll. | [ han kʰjan go ʉt i murgun kʰvɛl ‖ ] |
| 1375 | He might get up early. | Han kan gå upp tidigt. | [ han kʰjan go œp tʰidijt ‖ ] |
| 1376 | He won't be working tomorrow. | Han kommer inte att arbeta i morgon. | [ han kʰumer intə at arbeta i murgun ‖ ] |
| 1377 | He might be at home tomorrow morning. | Han kanske ska vara hemma i morgon bitti. | [ han kʰjanɕə skja vara hema i murgun bɪti ‖ ] |
| 1378 | He might watch television. | Han kan titta på tv. | [ han kʰjan tʰɪta pʰo tʰv ‖ ] |
| 1379 | He's going out in the afternoon for sure. | Han går helt säkert ut på eftermiddagen. | [ han gor helt sɛkeʈ ʉt pʰo eftermɪdajen ‖ ] |
| 1380 | He might go shopping, but he's not sure. | Han kanske ska gå och handla, men han är inte säker. | [ han kʰjanɕə skja go ɔɣ handla \| men han ɛr intə sɛker ‖ ] |
| 1381 | I can play the piano. My brother can play the piano, too. | Jag kan spela piano. Min bror kan spela piano också. | [ jaɣ kʰjan spela pʰianu ‖ min brur kʰjan spela pʰianu ukso ‖ ] |

### Cluster 6 — PDF pages 186–190 (sentences 1457–1471)

| # | EN | SV | IPA |
|---|---|---|---|
| 1457 | When you play tennis, you should always watch the ball. | När du spelar tennis, bör du alltid titta på bollen. | [ nɛr du spelar tʰenis \| bør du altid tʰɪta pʰo bɵlen ‖ ] |
| 1458 | Should I invite Sara to dinner? | Ska jag bjuda in Sara till middag? | [ skja jaɣ bjuda in (...) tʰɪl mɪdaɣ ‖ ] |
| 1459 | Should we make something special for dinner? | Ska vi göra något speciellt till middag? | [ skja vi jøra nogut spesielt tʰɪl mɪdaɣ ‖ ] |
| 1460 | Leopold shouldn't go to bed so late. | Leopold borde inte gå till sängs så sent. | [ (...) budə intə go tʰɪl sɛŋs so sent ‖ ] |
| 1461 | You watch TV all the time. You shouldn't watch TV so much. | Du tittar på TV hela tiden. Du bör inte titta på TV så mycket. | [ du tʰɪtar pʰo tʰv hela tʰiden ‖ du bør intə tʰɪta pʰo tʰv so myket ‖ ] |
| 1462 | I think Zahida should buy some new clothes. | Jag tycker Zahida borde köpa lite nya kläder. | [ jaɣ tʰyker (...) budə çøpa litə nya kʰlɛder ‖ ] |
| 1463 | It's late. I think I should go home now. | Det är sent. Jag tror jag ska gå hem nu. | [ də ɛr sent ‖ jaɣ tʰrur jaɣ skja go hem nʉ ‖ ] |
| 1464 | Shall I buy this coat? — Yes, I think you should. *(SV word order unusual — see Grammar points)* | Ska jag köpa denna jacka? - Ja, jag det tycker jag att du borde. | [ skja jaɣ çøpa dena jakja ‖ - ja \| jaɣ də tʰyker jaɣ at du budə ‖ ] |
| 1465 | I don't think you should work so hard. | Jag tycker inte att du ska jobba så hårt. | [ jaɣ tʰyker intə at du skja juba so hɔʈ ‖ ] |
| 1466 | I don't think we should go yet. It's too early. | Jag tycker inte att vi ska gå ännu. Det är för tidigt. | [ jaɣ tʰyker intə at vi skja go ɛnu ‖ det ɛr før tʰidijt ‖ ] |
| 1467 | Do you think I should buy this hat? | Tycker du att jag ska köpa den här hatten? | [ tʰyker du at jaɣ skja çøpa den hɛr haten ‖ ] |
| 1468 | What time do you think we should go home? | Vilken tid tycker du att vi ska åka hem? | [ vɪlken tʰid tʰyker du at vi skja okja hem ‖ ] |
| 1469 | I should study tonight, but I think I'll go to the movies. | Jag ska studera i kväll, men jag tror att jag ska gå på bio. | [ jaɣ skja studera i kʰvɛl \| men jaɣ tʰrur at jaɣ skja go pʰo biu ‖ ] |
| 1470 | I have to study tonight. I can't go to the movies. | Jag måste plugga ikväll. Jag kan inte gå på bio. | [ jaɣ mostə pʰlɵga ikvɛl ‖ jaɣ kʰjan intə go pʰo biu ‖ ] |
| 1471 | I ought to study tonight, but I think I'll go to the movies. | Jag borde studera i kväll, men jag tror att jag ska gå på bio. | [ jaɣ budə studera i kʰvɛl \| men jaɣ tʰrur at jaɣ skja go pʰo biu ‖ ] |

### Cluster 7 — PDF pages 216–220 (sentences 1547–1561)

| # | EN | SV | IPA |
|---|---|---|---|
| 1547 | I'd love to have dinner on Sunday. | Jag skulle tycka mycket om att ha middag på söndag. | [ jaɣ skølə tʰykja myket um at ha mɪdaɣ pʰo søndaɣ ‖ ] |
| 1548 | What would you like to do tonight? | Vad vill du göra ikväll? | [ vad vɪl du jøra ikvɛl ‖ ] |
| 1549 | I'm thirsty. I'd like a drink. | Jag är törstig. Jag vill ha en drink. | [ jaɣ ɛr tʰœʂtɛj ‖ jaɣ vɪl ha en drink ‖ ] |
| 1550 | I'd like some information about hotels, please. | Jag vill ha lite information om hotell, snälla. | [ jaɣ vɪl ha litə infurmaɧun um hutel \| snɛla ‖ ] |
| 1551 | I'm feeling tired. I'd like to stay home tonight. | Jag känner mig trött. Jag skulle vilja stanna hemma ikväll. | [ jaɣ çɛner mɛj tʰrœt ‖ jaɣ skølə vilja stana hema ikvɛl ‖ ] |
| 1552 | Would you like to go to the movies tonight? | Vill du gå på bio i kväll? | [ vɪl du go pʰo biu i kʰvɛl ‖ ] |
| 1553 | Do you like to go to the movies? — Yes, I go to the movies a lot. | Gillar du att gå på bio? - Ja, jag går på bio en hel del. | [ jɪlar du at go pʰo biu ‖ - ja \| jaɣ gor pʰo biu en hel del ‖ ] |
| 1554 | I'd like an orange juice, please. Can I have an orange juice? | Jag vill ha en apelsinjuice, tack. Kan jag få en apelsinjuice? | [ jaɣ vɪl ha en apelsinjuisə \| tʰak ‖ kʰjan jaɣ fo en apelsinjuisə ‖ ] |
| 1555 | I like orange juice. | Jag gillar apelsinjuice. | [ jaɣ jɪlar apelsinjuisə ‖ ] |
| 1556 | What would you like to do next weekend? | Vad vill du göra nästa helg? | [ vad vɪl du jøra nɛsta hej ‖ ] |
| 1557 | What do you like to do on weekends? | Vad gillar du att göra på helgerna? | [ vad jɪlar du at jøra pʰo heljeŋa ‖ ] |
| 1558 | You want to go to the movies tonight. Perhaps Emily will go with you. | Vill du gå på bio ikväll. Kanske Emily kommer att gå med dig. | [ vɪl du go pʰo biu ikvɛl ‖ kʰjanɕə (...) kʰumer at go med dɛj ‖ ] |
| 1559 | Would you like to go to the movies with me tonight? | Vill du gå på bio med mig ikväll? | [ vɪl du go pʰo biu med mɛj ikvɛl ‖ ] |
| 1560 | You want to play tennis tomorrow. Perhaps Wenjie will play, too. | Vill du spela tennis i morgon. Kanske Wenjie kommer att spela också. | [ vɪl du spela tʰenis i murgun ‖ kʰjanɕə (...) kʰumer at spela ukso ‖ ] |
| 1561 | Would you like to play tennis with me tomorrow? | Vill du spela tennis med mig imorgon? | [ vɪl du spela tʰenis med mɛj imurgun ‖ ] |

### Cluster 8 — PDF pages 246–250, gap at 249 (sentences 1637–1651)

| # | EN | SV | IPA |
|---|---|---|---|
| 1637 | I'm tired of arguing. Let's not do it any more. | Jag är trött på att argumentera. Låt oss inte göra det längre. | [ jaɣ ɛr tʰrœt pʰo at argumentera ‖ lot ɵs intə jøra də lɛŋrə ‖ ] |
| 1638 | Would you like to play tennis? — No, let's go for a swim. | Vill du spela tennis? - Nej, låt oss ta en simtur. | [ vɪl du spela tʰenis ‖ - nej \| lot ɵs tʰa en simtʉr ‖ ] |
| 1639 | Do you want to walk home? — No, let's take the bus. | Vill du gå hem? - Nej, låt oss ta bussen. | [ vɪl du go hem ‖ - nej \| lot ɵs tʰa bɵsen ‖ ] |
| 1640 | Shall I put some music on? — No, let's watch a movie. | Ska jag sätta på lite musik? - Nej, låt oss titta på en film. | [ skja jaɣ sɛta pʰo litə musik ‖ - nej \| lot ɵs tʰɪta pʰo en film ‖ ] |
| 1641 | Should we have dinner at home? — No, let's go to a restaurant. | Ska vi äta middag hemma? - Nej, vi går till en restaurang. | [ skja vi ɛta mɪdaɣ hema ‖ - nej \| vi gor tʰɪl en restauraŋ ‖ ] |
| 1642 | Would you like to go now? — No, let's wait a while. | Vill du gå nu? - Nej, låt oss vänta ett tag. | [ vɪl du go nʉ ‖ - nej \| lot ɵs vɛnta et tʰaɣ ‖ ] |
| 1643 | Shall I wait for you? — No, don't wait for me. | Ska jag vänta på dig? - Nej, vänta inte på mig. | [ skja jaɣ vɛnta pʰo dɛj ‖ - nej \| vɛnta intə pʰo mɛj ‖ ] |
| 1644 | Should we go home now? — No, let's not go home yet. | Ska vi gå hem nu? - Nej, låt oss inte gå hem ännu. | [ skja vi go hem nʉ ‖ - nej \| lot ɵs intə go hem ɛnu ‖ ] |
| 1645 | Shall we go out? — No, let's not go out. | Ska vi gå ut? - Nej, vi ska inte gå ut. | [ skja vi go ʉt ‖ - nej \| vi skja intə go ʉt ‖ ] |
| 1649 | Do you want me to turn on the light? — No, leave the light off. | Vill du att jag ska tända ljuset? - Nej, lämna ljuset av. | [ vɪl du at jaɣ skja tʰɛnda juset ‖ - nej \| lɛmna juset av ‖ ] |
| 1650 | Should we take a taxi? — No, let's take a bus. | Ska vi ta en taxi? - Nej, låt oss ta en buss. | [ skja vi tʰa en tʰaksi ‖ - nej \| lot ɵs tʰa en bɵs ‖ ] |
| 1651 | There's a man on the roof. | Det är en man på taket. | [ də ɛr en man pʰo tʰaket ‖ ] |

### Cluster 9 — PDF pages 276–280 (sentences 1727–1741)

| # | EN | SV | IPA |
|---|---|---|---|
| 1727 | When you arrive tomorrow, there will be somebody at the airport to meet you. | När du anländer i morgon, kommer det att finnas någon på flygplatsen för att träffa dig. | [ nɛr du anlɛnder i murgun \| kʰumer də at finas nogun pʰo flyɣplatsen før at tʰrɛfa dɛj ‖ ] |
| 1728 | Ten years ago there were 500 (five hundred) children in the school. Now there are more than a thousand. | För tio år sedan fanns det 500 (femhundra) barn i skolan. Nu finns det mer än ett tusen. | [ før tʰiu or sedan fans də 500 (femhʉndra) baŋ i skulan ‖ nʉ fins də mer ɛn et tʰʉsen ‖ ] |
| 1729 | Last week I went back to the town where I was born. It's very different now. There have been a lot of changes. | Förra veckan åkte jag tillbaka till staden där jag föddes. Det är väldigt annorlunda nu. Det har varit en hel del förändringar. | [ fœra vekjan oktə jaɣ tʰɪlbakja tʰɪl staden dɛr jaɣ fœdes ‖ det ɛr vɛldijt anuɭʉnda nʉ ‖ det har varit en hel del førɛndriŋar ‖ ] |
| 1730 | I think everything will be okay. I don't think there will be any problems. | Jag tror att allt kommer att bli bra. Jag tror inte att det kommer att bli några problem. | [ jaɣ tʰrur at alt kʰumer at bli bra ‖ jaɣ tʰrur intə at də kʰumer at bli noɣra pʰrublem ‖ ] |
| 1731 | Is it true that you're moving to Berlin? | Är det sant att du ska flytta till Berlin? | [ ɛr də sant at du skja flytʰa tʰɪl (...) ‖ ] |
| 1732 | We have to go now. It's very late. | Vi måste gå nu. Det är väldigt sent. | [ vi mostə go nʉ ‖ det ɛr vɛldijt sent ‖ ] |
| 1733 | Is it true that Jirou can fly a helicopter? | Är det sant att Jirou kan flyga en helikopter? | [ ɛr də sant at (...) kʰjan flyga en helikʰupter ‖ ] |
| 1734 | What day is it today? Tuesday? — No, today's Wednesday. | Vilken dag är det idag? Tisdag? - Nej, idag onsdag. | [ vɪlken daɣ ɛr də idaɣ ‖ tisdaɣ ‖ - nej \| idaɣ unsdaɣ ‖ ] |
| 1735 | It's 10 (ten) kilometers from downtown to the airport. *(SV uses `mil` = 10 km — see Vocabulary, false friend)* | Det är 10 (tio) mil från centrum till flygplatsen. | [ də ɛr 10 (tiu) mil fron sentrʉm tʰɪl flyɣplatsen ‖ ] |
| 1736 | Is it okay to call you at the office? | Är det okej att ringa dig på kontoret? | [ ɛr də ukej at riŋa dɛj pʰo kʰunturet ‖ ] |
| 1737 | Do you want to walk to the hotel? — I don't know. How far is it? | Vill du gå till hotellet? - Jag vet inte. Hur långt är det? | [ vɪl du go tʰɪl hutelet ‖ - jaɣ vet intə ‖ hur loŋt ɛr də ‖ ] |
| 1738 | It's Kelly's birthday today. She's 27 (twenty-seven). | Det är Kellys födelsedag idag. Hon är 27 (tjugosju). | [ də ɛr (...)s fødelsedaɣ idaɣ ‖ hun ɛr 27 (çʉguɧʉ) ‖ ] |
| 1739 | I don't believe it! That's impossible. | Jag tror inte det! Det är omöjligt. | [ jaɣ tʰrur intə də ‖ det ɛr umøjlijt ‖ ] |
| 1740 | How far is it from here to the train station? | Hur långt är det härifrån till tågstationen? | [ hur loŋt ɛr də hɛrifron tʰɪl tʰoɣstaɧunen ‖ ] |
| 1741 | How far is it from the hotel to the beach? | Hur långt är det från hotellet till stranden? | [ hur loŋt ɛr də fron hutelet tʰɪl stranden ‖ ] |

### Cluster 10 — PDF pages 306–310 (sentences 1817–1831)

| # | EN | SV | IPA |
|---|---|---|---|
| 1817 | Will you be in Miami tomorrow? — No, I won't. | Kommer du att vara i Miami i morgon? - Nej, det ska jag inte. | [ kʰumer du at vara i (...) i murgun ‖ - nej \| də skja jaɣ intə ‖ ] |
| 1818 | Have you ever broken your arm? — Yes, I have. | Har du någonsin brutit armen? - Ja, det har jag. | [ har du nogunsin brʉtit armen ‖ - ja \| də har jaɣ ‖ ] |
| 1819 | Did you buy anything yesterday? — Yes, I did. | Köpte du något igår? - Ja, det gjorde jag. | [ çøptə du nogut igor ‖ - ja \| də judə jaɣ ‖ ] |
| 1820 | Were you asleep at 3:00 (three) am? — Yes, I was. | Sov du vid 3? - Ja, det gjorde jag. | [ suv du vid 3 ‖ - ja \| də judə jaɣ ‖ ] |
| 1821 | You're late. — I am? Sorry. | Du är sen. - Är jag? Ursäkta. | [ du ɛr sen ‖ - ɛr jaɣ ‖ ʉɕɛkta ‖ ] |
| 1822 | I was sick last week. — You were? I didn't know that. | Jag var sjuk förra veckan. - Var du? Jag visste inte det. | [ jaɣ var ɧʉk fœra vekjan ‖ - var du ‖ jaɣ vistə intə də ‖ ] |
| 1823 | It's raining again. — It is? I was sunny ten minutes ago. | Det regnar igen. - Gör det? Det var soligt för tio minuter sen. | [ də reŋnar ijen ‖ - jør də ‖ det var sulijt før tʰiu minuter sen ‖ ] |
| 1824 | There's a message for you. — There is? Where is it? | Det finns ett meddelande till dig? - Finns det? Var är det? | [ də fins et medelandə tʰɪl dɛj ‖ - fins də ‖ var ɛr də ‖ ] |
| 1825 | Giovanni can't drive. — He can't? I didn't know that. | Giovanni kan inte köra bil. - Kan han inte? Jag visste inte det. | [ (...) kʰjan intə çøra bil ‖ - kʰjan han intə ‖ jaɣ vistə intə də ‖ ] |
| 1826 | I'm not hungry. — You're not? I am. | Jag är inte hungrig. - Är du inte? Jag är. | [ jaɣ ɛr intə hʉŋrɛj ‖ - ɛr du intə ‖ jaɣ ɛr ‖ ] |
| 1827 | Emilia isn't at work today. — She isn't? Is she sick? | Emilia är inte på jobbet idag. - Är hon inte? Är hon sjuk? | [ (...) ɛr intə pʰo jubet idaɣ ‖ - ɛr hun intə ‖ ɛr hun ɧʉk ‖ ] |
| 1828 | I speak four languages. — You do? Which ones? | Jag talar fyra språk. - Gör du? Vilka? | [ jaɣ tʰalar fyra sprok ‖ - jør du ‖ vɪlkja ‖ ] |
| 1829 | Luka doesn't eat meat. — He doesn't? Does he eat fish? | Luka äter inte kött. - Det gör han inte? Äter han fisk? | [ (...) ɛter intə çœt ‖ - də jør han intə ‖ ɛter han fisk ‖ ] |
| 1830 | Nadya got married last week. — She did? Really? | Nadya gifte sig förra veckan. - Gjorde hon? Verkligen? | [ (...) jiftə sɛj fœra vekjan ‖ - judə hun ‖ verklijen ‖ ] |
| 1831 | I've bought a new car. — Oh, you have? | Jag har köpt en ny bil. - Åh, har du? | [ jaɣ har çøpt en ny bil ‖ - oh \| har dʉ ‖ ] |

### Cluster 11 — PDF pages 336–340 (sentences 1907–1921)

| # | EN | SV | IPA |
|---|---|---|---|
| 1907 | Maalik said he had woken up feeling sick, so he hadn't gone to work. | Maalik sade att han hade vaknat illamående, så han hade inte gått till jobbet. | [ (...) sadə at han hadə vaknat ɪlamoendə \| so han hadə intə gɔt tʰɪl jubet ‖ ] |
| 1908 | Jasmine said that her new job is pretty interesting. > Jasmine said that her new job was pretty interesting. | Jasmine sa att hennes nya jobb är ganska intressant. > Jasmine sa att hennes nya jobb var ganska intressant. | [ (...) sa at henes nya jub ɛr ganskja intresant ‖ > (...) sa at henes nya jub var ganskja intresant ‖ ] |
| 1909 | She told me that she wants to go to South America next year. > She told me that she wanted to go to South America next year. | Hon berättade att hon vill åka till Sydamerika nästa år. > Hon sa att hon ville åka till Sydamerika nästa år. | [ hun berɛtadə at hun vɪl okja tʰɪl sydamerikja nɛsta or ‖ > hun sa at hun vɪlə okja tʰɪl sydamerikja nɛsta or ‖ ] |
| 1910 | The doctor told me to stay in bed for a few days. | Läkaren sa till mig att stanna i sängen ett par dagar. | [ lɛkjaren sa tʰɪl mɛj at stana i sɛŋen et pʰar dagar ‖ ] |
| 1911 | I told Lucien not to shout. | Jag sa till Lucien att inte skrika. | [ jaɣ sa tʰɪl (...) at intə skrikja ‖ ] |
| 1912 | Michiko asked me not to tell anybody what had happened. | Michiko bad mig att inte berätta för någon vad som hade hänt. | [ (...) bad mɛj at intə berɛta før nogun vad sum hadə hɛnt ‖ ] |
| 1913 | Noboru was taking a long time to get ready, so I told him to hurry up. | Noboru tog lång tid att göra sig redo, så jag sa till honom att skynda sig. | [ (...) tʰuɣ loŋ tʰid at jøra sɛj redu \| so jaɣ sa tʰɪl hunum at ɧynda sɛj ‖ ] |
| 1914 | Lilianne was nervous about the situation, so I told her to relax and take it easy. | Lilianne var nervös för situationen, så jag sa till henne att slappna av och ta det lugnt. | [ (...) var nervøs før sitʉaɧunen \| so jaɣ sa tʰɪl henə at slapna av ɔɣ tʰa də lɵŋnt ‖ ] |
| 1915 | The customs officer looked at me suspiciously and asked me to open my bag. | Tulltjänstemannen tittade på mig misstänksamt och bad mig att öppna min väska. | [ tʰɵlçɛnstemanen tʰɪtadə pʰo mɛj mɪstɛnksamt ɔɣ bad mɛj at œpna min vɛskja ‖ ] |
| 1916 | What happened to you last night? | Vad hände med dig igår kväll? | [ vad hɛndə med dɛj igor kʰvɛl ‖ ] |
| 1917 | How many people came to the meeting? | Hur många personer kom till mötet? | [ hur moŋa pʰɛsuner kʰum tʰɪl møtet ‖ ] |
| 1918 | Which bus goes downtown? *(SV leaves "downtown" untranslated — see Grammar points, possible source error)* | Vilken buss går downtown? | [ vɪlken bɵs gor duwntuwn ‖ ] |
| 1919 | Who do you want to speak to? | Vem vill du prata med? | [ vem vɪl du pʰrata med ‖ ] |
| 1920 | What was the weather like yesterday? | Hur var vädret igår? | [ hur var vɛdret igor ‖ ] |
| 1921 | To whom do you wish to speak? *(SV drops "med" — see Grammar points)* | Vem vill du prata? | [ vem vɪl du pʰrata ‖ ] |

### Cluster 12 — PDF pages 360–364 (sentences 1979–1993)

| # | EN | SV | IPA |
|---|---|---|---|
| 1979 | Should we postpone leaving today until tomorrow? — No, we should try leaving as soon as possible. *(SV clause reads as ungrammatical — see Grammar points)* | Ska vi skjuta lämnar i dag till i morgon? - Nej, vi bör försöka lämna så fort som möjligt. | [ skja vi ɧʉta lɛmnar i daɣ tʰɪl i murgun ‖ - nej \| vi bør fœʂøkja lɛmna so fuʈ sum møjlijt ‖ ] |
| 1980 | My car isn't very reliable. It keeps breaking down. *(SV word order unusual — see Grammar points)* | Min bil är inte särskilt tillförlitliga. Det håller den går sönder. | [ min bil ɛr intə sɛʂhilt tʰɪlfœɭitliga ‖ det hɔler den gor sønder ‖ ] |
| 1981 | It was very funny. I couldn't stop laughing. | Det var mycket roligt. Jag kunde inte sluta skratta. | [ də var myket rulijt ‖ jaɣ kʰʉndə intə slʉta skrata ‖ ] |
| 1982 | It was late, so we decided to take a taxi home. | Det var sent, så vi beslöt att ta en taxi hem. | [ də var sent \| so vi besløt at tʰa en tʰaksi hem ‖ ] |
| 1983 | Vincent was in a difficult situation, so I agreed to help him. | Vincent var i en svår situation, så jag gick med på att hjälpa honom. | [ (...) var i en svor sitʉaɧun \| so jaɣ jɪk med pʰo at jɛlpa hunum ‖ ] |
| 1984 | How old were you when you learned to drive? | Hur gammal var du när du lärde dig att köra? | [ hur gamal var du nɛr du lɛdə dɛj at çøra ‖ ] |
| 1985 | Valerie failed to make a good impression at the job interview. | Valerie misslyckades med att göra ett gott intryck på anställningsintervju. | [ (...) mɪsslykjades med at jøra et gɔt intryk pʰo anstɛlniŋsintervjʉ ‖ ] |
| 1986 | We decided not to go out because of the weather. | Vi beslutade att inte gå ut på grund av vädret. | [ vi beslʉtadə at intə go ʉt pʰo grʉnd av vɛdret ‖ ] |
| 1987 | I promised not to be late. | Jag lovade att inte komma för sent. | [ jaɣ luvadə at intə kʰuma før sent ‖ ] |
| 1988 | Are you thinking of buying a car? — Yeah, but I still haven't made up my mind. | Funderar du på att köpa en bil? - Ja, men jag har fortfarande inte bestämt mig. | [ fʉnderar du pʰo at çøpa en bil ‖ - ja \| men jaɣ har fʉʈfarandə intə bestɛmt mɛj ‖ ] |
| 1989 | They seem to have plenty of money. | De verkar ha gott om pengar. | [ dɛ verkjar ha gɔt um pʰeŋar ‖ ] |
| 1990 | I like Victoria but I think she tends to talk too much. | Jag gillar Victoria, men jag tror att hon har en tendens att prata för mycket. | [ jaɣ jɪlar (...) \| men jaɣ tʰrur at hun har en tʰendens at pʰrata før myket ‖ ] |
| 1991 | Nikolai pretended not to see me when he passed me on the street. | Nikolai låtsades inte se mig när han passerade mig på gatan. | [ (...) lotsades intə sə mɛj nɛr han pʰaseradə mɛj pʰo gatan ‖ ] |
| 1992 | I pretended to be reading the newspaper. | Jag låtsades läsa tidningen. | [ jaɣ lotsades lesa tʰidniŋen ‖ ] |
| 1993 | You seem to have lost weight. | Du verkar ha gått ner i vikt. | [ du verkjar ha gɔt ner i vikt ‖ ] |

---

## Copyright discipline reminder

All 177 triplets above are short (1–3 sentence) pedagogical drill items from a sentence-mining
course, reproduced per this dispatch's explicit instruction because the sentence-pair format itself
is the raw corpus material this project needs — not bulk reproduction of explanatory prose,
vocabulary boxes, or dialogue blocks in the sense the general copyright-discipline rule is aimed at.
No surrounding explanatory text, exercise instructions, or front-matter prose from the book is
reproduced beyond the short illustrative fragments quoted in the Grammar points section above. See
`../../00_Reference_Extraction_Spec.md`.
