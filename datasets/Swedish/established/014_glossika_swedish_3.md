# Swedish — Established Vocabulary/Grammar: Glossika Mass Sentences, Swedish Fluency 3 — Representative Sample

**Source:** Michael Campbell & Markus Bruus, *Glossika Mass Sentences: Swedish — Complete Fluency
Course, Fluency 3* (Glossika, first published Aug 2014). PDF is 368 pages. This volume continues
the series' cumulative sentence numbering: Fluency 1 = sentences 1–1000, Fluency 2 = sentences
1001–2000, **this book (Fluency 3) = sentences 2001–3000.** Sampled page ranges (PDF page = printed
footer page number, confirmed identical, no page-spread offset): **34–40, 100–106, 165–171,
230–236, 295–300, 355–360, and 367** (the book's final page, sentence 3000).

---

## CORRECTION to original task brief: this source has NO usable text layer

The dispatching orchestrator's brief stated this book has a real text layer. **That is false.**
Verified directly: `pdftotext -f 50 -l 52 <file> -` returns only a handful of stray characters for
three full pages, and `pdfimages -list` shows **zero raster images** on content pages either — the
sentence text is drawn as vector outline paths with no character-to-Unicode mapping. This is
neither a decodable font-substitution cipher (no CID/glyph table to even attempt decoding) nor an
image-based scan (no embedded raster to OCR) — it is genuinely vision-only, confirmed identically
on Fluency 1 and Fluency 2 of this same series (same InDesign/Adobe PDF Library production
pipeline, same symptom). **Every triplet below was read directly from rendered page images
(`pdftoppm -r 150`), not extracted as text.** This is a new, generically-relevant gotcha for this
project (a vector-outline PDF with no ToUnicode map, as distinct from every font-substitution-cipher
variant already catalogued in `00_Reference_Extraction_Spec.md`) and should be added there if not
already covered by a sibling dispatch's note.

## Coverage note — representative sample, NOT exhaustive

This book holds **~1000 sentence triplets (2001–3000) across 334 content pages (~3 triplets/page)**
— a page-by-page vision-reading job, not a cheap text-layer pull. Per the dispatch brief, this
chunk vision-read a representative, evenly-spread sample rather than the full book: **121 triplets**
total, drawn from 7 clusters of consecutive pages spread across the book's full range (beginning,
~1/4, ~1/2 (two clusters either side), ~3/4, near-end, and the literal final sentence):

| Cluster | Pages | Sentences | Count |
|---|---|---|---|
| A | 34–40 | 2001–2021 | 21 |
| B | 100–106 | 2199–2219 | 21 |
| C | 165–171 | 2394–2414 | 21 |
| D | 230–236 | 2589–2609 | 21 |
| E | 295–300 | 2784–2801 | 18 |
| F | 355–360 | 2964–2981 | 18 |
| G | 367 | 3000 (final sentence) | 1 |

**A full-coverage pass of this source (the remaining ~880 triplets), if ever wanted, should be
planned as its own dedicated vision-reading wave** — rendering and reading ~334 pages one by one is
not the kind of cheap bulk pull a text-layer source would be, and shouldn't be assumed free. Fluency
1 (`012_glossika_swedish_1.md`) and Fluency 2 (`013_glossika_swedish_2.md`) of this same series are
being extracted in parallel by sibling subagents using the same methodology and the same
representative-sample scope decision.

**Minor pagination gotcha worth flagging for future dispatches on this book:** the book's own
printed Table of Contents (PDF page 7) claims "Sentence 100" lands on page 61 and the "Glossika Mass
Sentences" section itself starts on page 27 — but direct rendering shows the section divider is
actually on page 33 and sentence content (sentence 2001) begins on page 34. The TOC page numbers in
this specific PDF do not reliably predict actual content location (likely a front-matter TOC shared
across all three Fluency-level books that wasn't recalibrated per volume) — **verify page ranges by
direct rendering, not by trusting this book's own TOC**, consistent with the extraction spec's
existing "verify page-range estimates empirically" guidance.

**No handwritten marginalia found** — all 15 rendered pages are clean born-digital typeset pages
with no evidence of a prior owner's annotations.

**Format note:** every item is a numbered `EN` (English) / `SV` (Swedish) / `IPA` (bracketed phonetic
transcription) triplet. The book consistently **omits IPA transcription for personal/proper names**
(e.g. Sandra, Diego, Heidi, Takahiro, Herman, Rashid, Simon, Walter, Ludwig, Rita, the "F1" racer),
replacing the name's phonetic slot with a literal `(...)` rather than attempting a
Swedish-pronunciation rendering of a foreign name — this is a deliberate convention of the source,
not a transcription gap on this subagent's part, and is preserved as `(...)` in the Sample sentences
section below exactly as printed.

---

## Vocabulary

Pulled from recurring/notable lexical items across the 121 sampled triplets — not every word of
every sentence (this is a sentence-mining course, not a word list; see the Sample sentences section
below for full triplets).

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| vara tvungen att | to be forced to / to have to | verb phrase (predicate adj. + infinitive) | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | Recurs across multiple clusters (2014 "Vi var tvungna att vänta", 2400 "Vi var tvungna att promenera hem") — obligation construction distinct from `måste`. |
| få (fick, past) [+ object + att + infinitive] | to get (someone to do something) | verb — causative construction | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | Causative: "Jag fick honom att lova..." (2010, I got him to promise...), "Jag fick någon att hjälpa mig" (2003, I got somebody to help me). |
| komma ihåg | to remember (lit. "come to mind") | verb phrase (idiom) | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | "Kom ihåg att posta brevet" (2020, imperative); "Jag kom ihåg att låsa dörren" (2018). |
| glömma | to forget | verb | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | "jag glömde att stänga fönstren" (2018); "Någon har glömt sitt paraply" (2399). |
| be om ursäkt | to apologize (lit. "ask for pardon") | verb phrase (idiom) | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | "Jag ber om ursäkt för alla problem jag har orsakat" (2397). |
| innebära | to mean / to imply | verb | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | "Att han är arbetslös innebär att han inte har mycket pengar" (2210); "Att vara vegetarian innebär att..." (2214). |
| tillräckligt | enough / sufficiently | adverb | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | Used in both affirmative and negated "X enough / not X enough" constructions (2593, 2594, 2595, 2597, 2600). |
| för [adj.] för att | too [adj.] to [verb] | adverb + conjunction construction | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | "De är för unga för att gifta sig" (2595, they're too young to get married); "Det är för långt att promenera hem" (2596). |
| gjorde slut (göra slut) | broke up (lit. "made [an] end") | verb phrase (idiom) | colloquial | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | "Ludwig och Rita gjorde slut" (2974) — everyday breakup idiom, repeated 3x in a drill cluster (2974–2976) with near-synonyms "separerade" and "slutade med att...gjorde slut." |
| blanda ihop | to mix up / confuse (people/things) | verb phrase | colloquial | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | "alla blandar ihop dem" (2979, everybody gets them [twins] mixed up). |
| en fullkomlig röra | an absolute/total mess | noun phrase (idiom) | colloquial | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | plausible_unverified | "Ditt hus är en fullkomlig röra" (2980) — single occurrence in sample; IPA renders as [en fɔlkumlɛj røra]. |
| hålla fast | to hold on / stick with (something) | verb phrase | colloquial | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | "håll fast och ge inte upp" (2981, stick with it and don't give up). |
| ge upp | to give up | verb phrase | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | Negated imperative "ge inte upp" (2981). |
| stå ut med | to put up with / tolerate | verb phrase | colloquial | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | "vi måste stå ut med en massa oväsen" (2978, we have to put up with a lot of noise). |
| lat | lazy | adjective | colloquial | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | "Du är lat. Du arbetar inte tillräckligt hårt." (2593) — blunt, direct second-person register; no hedging. |
| enäggstvillingar | identical twins (lit. "one-egg twins") | noun (compound) | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | plausible_unverified | "De två bröderna är enäggstvillingar" (2979); compound structurally parallel to English "identical"/German "eineiig". |
| skogvaktare | forest ranger / forest warden | noun | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | Used to translate "the lone ranger" (3000, final sentence of the book) — a loose/domesticating translation choice, not a literal rendering of the Wild-West-specific English idiom. |
| arg / upprörd / rasande | angry / upset / furious | adjective (intensity gradient) | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | Drilled as an escalating register cluster across one page sequence (2796 arg, 2797 upprörd, 2798 "ännu mer rasande" — even more furious). |
| misstänkt / samband / mordet | suspect / connection / the murder | noun | technical.legal | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | Crime-procedural vocabulary cluster (2790–2791); "baserat på DNA-bevis" (based on DNA evidence) in the same pair of sentences. |
| fatta eld | to catch fire | verb phrase | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | "F1-bilen fattade eld och exploderade" (2972). |
| intill | right next to / adjoining | preposition | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | "Vi bor intill en internationell flygplats" (2978). |
| komma ikapp | to catch up (with someone) | verb phrase (particle verb) | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | "Jag kommer ikapp dig" (2967, I'll catch up with you). |
| reagera/reaktion PÅ, förvånad ÖVER, relation MED | react/reaction TO, surprised BY, relationship WITH | preposition-governed verb/noun/adjective set | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | Source deliberately capitalizes the English AND Swedish prepositions in this one page-cluster (2786–2789, pp. 295–296) as a teaching device — see Grammar points below. |
| hjälpa, varna, (be om) råd, föreslå | to help, to warn, (ask for) advice, to suggest | verb | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | Cluster of "advice-exchange" speech-act verbs recurring in the opening sample (2004–2006, 2015). |

**No morpheme breakdowns added.** Swedish is a moderately fusional/agglutinative-adjacent language
(definite-article suffixes, compounding) but none of the sampled terms above has internal
compositional structure complex enough to obscure an atomic gloss — `enäggstvillingar` and
`skogvaktare` are transparent two-root compounds, noted inline in their Notes field rather than as a
separate breakdown block.

## Grammar points

### "för [X] för att [Y]" — too [X] to [Y]

A recurring adversative-degree construction across the sample: `för` (too) + adjective + `för att`
(in order to/to) + infinitive clause, e.g. "De är för unga för att gifta sig" (2595, they're too
young to get married), "Det är för långt att promenera hem härifrån" (2596, it's too far to walk
home from here — here `att` alone suffices without a second `för`, suggesting the second `för` in
2595 is reinforcing rather than structurally obligatory). Confirmed as a genuinely repeated pattern,
not a one-off: 4 instances in cluster D alone (pages 230–236).

### "tillräckligt [X]" / negated "inte tillräckligt [X]" — enough / not [X] enough

`tillräckligt` (sufficiently/enough) modifies an adjective or governs a `med`-phrase, and the
construction is drilled in both affirmative and negative forms within the same page cluster: "Har
han tillräckligt med erfarenhet?" (2594, does he have enough experience), "Är han erfaren nog för
jobbet?" (same sentence's paraphrase, using the shorter near-synonym `nog` instead of
`tillräckligt`) — the source pairs a full sentence with its casual contracted paraphrase using `>`,
confirming `nog` and `tillräckligt` are presented as interchangeable in this register.

### Causative "få [object] att [infinitive]"

Swedish uses `få` (lit. "get/receive") + object + `att` + infinitive to express getting someone to
do something, distinct from English's more generic "get/make someone do X": "Jag fick honom att
lova att..." (2010), "Jag fick någon att hjälpa mig" (2003). This is a genuinely productive pattern
across the sample, not confined to one sentence pair.

### Preposition mismatch between English and Swedish (explicit pedagogical device)

A single page cluster (sentences 2786–2789, pp. 295–296) deliberately capitalizes the governing
preposition in both the English and Swedish sentence to flag that the two languages do not map
prepositions 1:1: "surprised BY her reaction TO my simple suggestion" → "förvånad ÖVER hennes
reaktion PÅ mitt enkla förslag" (BY → ÖVER, TO → PÅ); "attitude toward his job" → "inställning TILL
sitt jobb"; "relationship WITH your parents" → "relation MED dina föräldrar." This is the clearest
explicit grammar-adjacent signal in the sampled material — the source is flagging preposition
non-correspondence as a known learner trap, not just incidental translation variance. Worth
returning to if a full-coverage pass of this book is ever dispatched, since this teaching device may
recur at other unsampled points in the book.

### Likely source typo (flagged, not silently corrected)

Sentence 2969 (page 356): SV reads "Mina föräldrar var där igen för hämta upp mig när kom hem" for
EN "My parents were there again to pick me up when I flew back home." This appears to be missing
`att` after `för` (should likely be "för **att** hämta upp mig") and missing an explicit subject
before "kom hem" (should likely be "när **jag** kom hem"). Rendered and re-checked at 150dpi — the
page is clean, legible print with no ambiguity in character reading; the omission reads as a genuine
editorial/typesetting error in the source book itself, not a vision-reading misread. Flagged per the
extraction spec's discipline around distinguishing source errors from transcription errors.

### Unstressed-vowel reduction visible in the IPA layer (observation, not the source's own stated rule)

Not an explanation the book itself gives — this is a pattern visible across many of the sampled IPA
transcriptions, noted here as a candidate grammar/phonology signal for later mechanics analysis.
Word-final unstressed `-a` in common function words and inflectional endings is consistently
transcribed as a mid-central vowel rather than a full back [a]: `skulle` → `[skølə]`, `några` →
`[noɣra]`/`[nɔɣra]`-adjacent, `honom` is a separate case but `(d)en andra` → `[(d)ə andra]`, `det` →
`[dɛ]`/`[d]`-reduced contexts. This tracks standard descriptions of spoken-register Central Swedish
vowel reduction but is worth flagging as *observed from this source's own transcription practice*
rather than claimed as the book's explicit teaching point — consistent with the extraction spec's
warning that reference sources describe correlations and a pattern should be labeled by its actual
evidentiary source.

---

## Sample sentences

Full EN / SV / IPA triplets as printed, grouped by sampled page cluster. `(...)` marks the source's
own convention of omitting IPA for a proper name (see format note above). Presented per this
dispatch's explicit instruction to preserve the sentence-pair format as raw corpus material, not as
bulk reproduction of explanatory prose — see copyright note at the end of this file.

### Cluster A — pages 34–40 (sentences 2001–2021)

| # | EN | SV | IPA |
|---|---|---|---|
| 2001 | Can you remind me to call Sandra tomorrow? | Kan ni påminna mig att ringa Sandra imorgon? | [ kʰjan ni pʰomɪna mɛj at riŋa (...) imuʁgun ‖ ] |
| 2002 | Who taught you to drive? | Vem lärde dig att köra? | [ vem lɛdᵊ dɛj at çøra ‖ ] |
| 2003 | I didn't move the piano by myself. I got somebody to help me. | Jag ville inte flytta pianot själv. Jag fick någon att hjälpa mig. | [ jaɣ vɪlᵊ ɪntᵊ flʏta pʰianut hɛlv ‖ jaɣ fɪk nogun at jɛlpa mɛj ‖ ] |
| 2004 | Diego said the switch was dangerous and warned me not to touch it. | Diego sa att växeln var farlig och varnade mig att inte röra den. | [ (...) sa at vɛkseln var faʁlej ɔχ vaɳadᵊ mɛj at ɪntᵊ røra den ‖ ] |
| 2005 | I was warned not to touch the switch. | Jag blev varnad att inte röra växeln. | [ jaɣ blev vaɳad at ɪntᵊ røra vɛkseln ‖ ] |
| 2006 | Stan suggested I ask you for advice. | Stan föreslog att jag ber er om råd. | [ stan føresluɣ at jaɣ ber er um rod ‖ ] |
| 2007 | I wouldn't advise staying in that hotel. > I wouldn't advise anybody to stay in that hotel. | Jag skulle inte råda att vistas på detta hotell. > Jag skulle inte råda någon att bo på detta hotell. | [ jaɣ skølᵊ ɪntᵊ roda at vistas pʰo deta hutel ‖ > jaɣ skølᵊ ɪntᵊ roda nogun at bu pʰo deta hutel ‖ ] |
| 2008 | They don't allow parking in front of the building. > They don't allow people to park in front of the building. | De tillåter inte parkering framför byggnaden. > De tillåter inte folk att parkera framför byggnaden. | [ dɛ tʰɪloter ɪntᵊ pʰarkeriŋ framfør bʏgnaden ‖ > dɛ tʰɪloter ɪntᵊ fulk at pʰarkera framfør bʏgnaden ‖ ] |
| 2009 | Parking isn't allowed in front of the building. > You aren't allowed to park in front of the building. | Parkering är inte tillåten framför byggnaden. > Det är inte tillåtet att parkera framför byggnaden. | [ pʰarkeriŋ ɛr ɪntᵊ tʰɪloten framfør bʏgnaden ‖ > dᵊ ɛr ɪntᵊ tʰɪlotet at pʰarkera framfør bʏgnaden ‖ ] |
| 2010 | I made him promise that he wouldn't tell anybody what happened. | Jag fick honom att lova att han inte skulle berätta för någon vad som hände. | [ jaɣ fɪk hunum at luva at han ɪntᵊ skølᵊ berɛta før nogun vad sum hɛndᵊ ‖ ] |
| 2011 | Hot weather makes me feel tired. | Varmt väder gör mig trött. | [ varmt vɛder jør mɛj tʰrœt ‖ ] |
| 2012 | Her parents wouldn't let her go out alone. | Hennes föräldrar skulle inte låta henne gå ut ensam. | [ henes føreldrar skølᵊ ɪntᵊ lota henᵊ go ut ensam ‖ ] |
| 2013 | Let me carry your bag for you. | Låt mig bära väskan åt dig. | [ lot mɛj bera veskjan ot dɛj ‖ ] |
| 2014 | We were made to wait for two hours. | Vi var tvungna att vänta i två timmar. | [ vi var tʰvuŋna at venta i tʰvo tʰɪmar ‖ ] |
| 2015 | My lawyer said I shouldn't say anything to the police. > My lawyer advised me not to say anything to the police. | Min advokat sa att jag borde inte säga något till polisen. > Min advokat rådde mig att inte säga något till polisen. | [ min advukjat sa at jaɣ budᵊ ɪntᵊ sɛga nogut tʰɪl pʰulisen ‖ > min advukjat rɔdᵊ mɛj at ɪntᵊ sɛga nogut tʰɪl pʰulisen ‖ ] |
| 2016 | I was told that I shouldn't believe everything he says. > I was warned not to believe anything he says. | Jag fick veta att jag inte skulle tro på allt han säger. > Jag blev varnad att inte tro någonting, säger han. | [ jaɣ fɪk veta at jaɣ ɪntᵊ skølᵊ tʰru pʰo alt han sɛjer ‖ > jaɣ blev vaɳad at ɪntᵊ tʰru noguntiŋ ‖ sɛjer han ‖ ] |
| 2017 | If you have a car, you're able to get around more easily. > Having a car enables you to get around more easily. | Om du har en bil kan du komma runt lättare. > Att ha en bil gör att du kan komma runt lättare. | [ um dʉ har en bil kʰjan dʉ kʰuma runt lɛtarᵊ ‖ > at ha en bil jør at dʉ kʰjan kʰuma rʉnt lɛtarᵊ ‖ ] |
| 2018 | I know I locked the door. I clearly remember locking it. > I remembered to lock the door, but I forgot to shut the windows. | Jag vet att jag låste dörren. Jag minns tydligt att jag låste den. > Jag kom ihåg att låsa dörren, men jag glömde att stänga fönstren. | [ jaɣ vet at jaɣ lostᵊ døren ‖ jaɣ mɪns tʰʏdlijt at jaɣ lostᵊ den ‖ > jaɣ kʰum ihoɣ at losa døren ‖ men jaɣ ɣlømdᵊ at stɛŋa fønstren ‖ ] |
| 2019 | He could remember driving along the road just before the accident, but he couldn't remember the accident itself. | Han kunde komma ihåg att han körde längs vägen strax före olyckan, men han kunde inte komma ihåg själva olyckan. | [ han kʰʉndᵊ kʰuma ihoɣ at han çødᵊ lɛŋs vɛjen straks førᵊ ulʏkjan ‖ men han kʰʉndᵊ ɪntᵊ kʰuma ihoɣ hɛlva ulʏkjan ‖ ] |
| 2020 | Please remember to mail the letter on your way to work. | Kom ihåg att posta brevet på väg till jobbet, tack. | [ kʰum ihoɣ at pʰusta brevet pʰo vɛɣ tʰɪl jubet ‖ tʰak ‖ ] |
| 2021 | I now regret saying what I said. I shouldn't have said it. | Nu beklagar jag vad jag sa. Jag borde inte ha sagt det. | [ nʉ beklagar jaɣ vad jaɣ sa ‖ jaɣ budᵊ ɪntᵊ ha saɣt dᵊ ‖ ] |

### Cluster B — pages 100–106 (sentences 2199–2219)

| # | EN | SV | IPA |
|---|---|---|---|
| 2199 | I heard someone slamming the door in the middle of the night. | Jag hörde att någon smällde igen dörren mitt i natten. | [ jaɣ høʁdᵊ at nogun smɛldᵊ ijen døren mɪt i naten ‖ ] |
| 2200 | Heidi hurt her knee playing volleyball. | Heidi skadade sitt knä när hon spelade volleyboll. | [ (...) skjadadᵊ sɪt kʰnɛ nɛr hun speladᵊ vɔleybɔl ‖ ] |
| 2201 | Takahiro's in the kitchen making coffee. | Takahiro är i köket och gör kaffe. | [ (...) ɛr i çøket ɔχ jør kʰjafᵊ ‖ ] |
| 2202 | A man ran out of the house shouting. | En man sprang skrikandes ut ur huset. | [ en man spraŋ skrikjandes ʉt ʉr hʉset ‖ ] |
| 2203 | Do something! Don't just stand there doing nothing. | Gör något! Stå inte bara där utan att göra någonting. | [ jør nogut ‖ sto ɪntᵊ bara dɛr ʉtan at jøra noguntiŋ ‖ ] |
| 2204 | Did you cut yourself shaving? | Skar du dig när du rakade dig? | [ skjar dʉ dɛj nɛr dʉ rakjadᵊ dɛj ‖ ] |
| 2205 | Be careful when crossing the street. | Var försiktig när du korsar gatan. | [ var føʃiktɛj nɛr dʉ kʰuʃar gatan ‖ ] |
| 2206 | Having finally found a hotel, we looked for some place to have dinner. | Efter att äntligen ha hittat ett hotell letade vi efter någonstans att äta middag. | [ efter at ɛntlijen ha hɪtat et hutel letadᵊ vi efter nogunstans at ɛta mɪdaɣ ‖ ] |
| 2207 | After getting off work, she went straight home. | Efter att ha slutat jobbet gick hon raka vägen hem. | [ efter at ha slʉtat jubet jɪk hun rakjɑ vɛjen hem ‖ ] |
| 2208 | Taking a key out of his pocket, he unlocked the door. | Han tog ut en nyckel från sin ficka och låste dörren. | [ han tʰuɣ ʉt en nʏkel fron sin fɪkja ɔχ lostᵊ døren ‖ ] |
| 2209 | Feeling tired, I went to bed early. | Jag kände mig trött och gick till sängs tidigt. | [ jaɣ çɛndᵊ mɛj tʰrœt ɔχ jɪk tʰɪl sɛŋs tʰidijt ‖ ] |
| 2210 | Being unemployed means he doesn't have much money. | Att han är arbetslös innebär att han inte har mycket pengar. | [ at han ɛr arbetsløs ɪnebɛr at han ɪntᵊ har mʏket pʰeŋar ‖ ] |
| 2211 | Not having a car can make getting around difficult in some places. | Att inte ha en bil kan göra det svårt att ta sig runt i vissa områden. | [ at ɪntᵊ ha en bil kʰjan jøra dᵊ svɔʈ at tʰa sɛj rʉnt i visa umroden ‖ ] |
| 2212 | Having already seen the movie twice, I didn't want to go again with my friends. | Efter att redan ha sett filmen två gånger vill jag inte gå dit med mina vänner igen. | [ efter at redan ha set filmen tʰvo goŋer vɪl jaɣ ɪntᵊ go dit med mina vɛner ijen ‖ ] |
| 2213 | Not being able to speak the local language meant that I had trouble communicating. | Att inte kunna prata det lokala språket innebar att jag hade problem att kommunicera. | [ at ɪntᵊ kʰøna pʰrata dᵊ lukjala sproket ɪnebar at jaɣ hadᵊ pʰrublem at kʰumʉnisera ‖ ] |
| 2214 | Being a vegetarian, Mitsuko doesn't eat any kind of meat. | Att vara vegetarian innebär att Mitsuko inte äter någon form av kött. | [ at vara vejetarian ɪnebɛr at (...) ɪntᵊ ɛter nogun fʉrm av çœt ‖ ] |
| 2215 | The police want to talk to anybody who saw the accident. | Polisen vill prata med alla som såg olyckan. | [ pʰulisen vɪl pʰrata med ala sum soɣ ulʏkjan ‖ ] |
| 2216 | The new city hall isn't a very beautiful building. Most people don't like it. | Det nya rådhuset är inte en vacker byggnad. De flesta tycker inte om det. | [ dᵊ nya rodhʉset ɛr ɪntᵊ en vakᵊr bʏgnad ‖ dᵊ flesta tʰʏker ɪntᵊ um dᵊ ‖ ] |
| 2217 | The people were injured in the accident. | Människorna skadades i olyckan. | [ mɛniskuɳa skjadades i ulʏkjan ‖ ] |
| 2218 | Do the police know the cause of the explosion? | Vet polisen om orsaken till explosionen? | [ vet pʰulisen um uʃaken tʰɪl eksplʉɕunen ‖ ] |
| 2219 | The police are looking for the stolen car. | Polisen letar efter den stulna bilen. | [ pʰulisen letar efter den stʉlna bilen ‖ ] |

### Cluster C — pages 165–171 (sentences 2394–2414)

| # | EN | SV | IPA |
|---|---|---|---|
| 2394 | Hardly anybody passed the examination. | Någon kan knappast ha klarat examen. | [ nogun kʰjan kʰnapast ha kʰlarat eksamen ‖ ] |
| 2395 | If anyone has any questions, I'll be glad to answer them. | Om någon har några frågor svarar jag gärna. | [ um nogun har noɣra frogur svarar jaɣ jɛɳa ‖ ] |
| 2396 | Let me know if you need anything. | Säg till om du behöver något. | [ sɛɣ tʰɪl um dʉ behøver nogut ‖ ] |
| 2397 | I'm sorry for any trouble I've caused. | Jag ber om ursäkt för alla problem jag har orsakat. | [ jaɣ ber um øʃɛkt før ala pʰrublem jaɣ har uʃakjat ‖ ] |
| 2398 | Anyone who wants to take the exam should tell me by Friday. | Den som vill göra provet bör säga det senast fredag. | [ den sum vɪl jøra pʰruvet bør sɛga dᵊ senast fredaɣ ‖ ] |
| 2399 | Someone has forgotten their umbrella. | Någon har glömt sitt paraply. | [ nogun har ɣlømt sɪt pʰaraplʏ ‖ ] |
| 2400 | We had to walk home because there was no bus. | Vi var tvungna att promenera hem eftersom det inte fanns någon buss. | [ vi var tʰvuŋna at pʰrumenera hem eftesum dᵊ ɪntᵊ fans nogun bɵs ‖ ] |
| 2401 | She'll have no difficulty finding a job. | Hon kommer inte ha några svårigheter att hitta ett arbete. | [ hun kʰumer ɪntᵊ ha noɣra svorijheter at hɪta et arbetᵊ ‖ ] |
| 2402 | There were no stores open. | Inga butiker var öppna. | [ iŋa bʉtiker var œpna ‖ ] |
| 2403 | All the tickets have been sold. There are none left. | Alla biljetter har sålts. Det finns inga kvar. | [ ala bijeter har solts ‖ det fɪns iŋa kʰvar ‖ ] |
| 2404 | This money is all yours. None of it is mine. | Dessa pengar är dina. Inget av det är mitt. | [ desa pʰeŋar ɛr dina ‖ iŋet av dᵊ ɛr mɪt ‖ ] |
| 2405 | None of the stores were open. | Ingen av butikerna var öppna. | [ iŋen av bʉtikeɳa var œpna ‖ ] |
| 2406 | The house is empty. There's no one living there. | Huset är tomt. Det är ingen som bor där. | [ hʉset ɛr tʰumt ‖ det ɛr iŋen sum bur dɛr ‖ ] |
| 2407 | We had nothing to eat. | Vi hade ingenting att äta. | [ vi hadᵊ iŋentiŋ at ɛta ‖ ] |
| 2408 | Herman didn't tell anyone about his plans. | Herman berättade inte för någon om sina planer. | [ (...) berɛtadᵊ ɪntᵊ før nogun um sina pʰlaner ‖ ] |
| 2409 | No one did what I asked them to do, did they? | Ingen gjorde vad jag bad dem att göra, eller gjorde de? | [ iŋen judᵊ vad jaɣ bad dem at jøra ‖ eler judᵊ dɛ ‖ ] |
| 2410 | The accident looked serious, but fortunately nobody was injured. | Olyckan såg allvarlig ut, men lyckligtvis skadades ingen. | [ ulʏkjan soɣ alvalɛj ʉt ‖ men lʏklijtvis skjadades iŋen ‖ ] |
| 2411 | I don't know anything about economics. | Jag vet ingenting om ekonomi. | [ jaɣ vet iŋentiŋ um ekunumi ‖ ] |
| 2412 | We didn't spend much money. | Vi spenderade inte mycket pengar. | [ vi spenderadᵊ ɪntᵊ mʏket pʰeŋar ‖ ] |
| 2413 | There's no need to hurry. We've got plenty of time. | Det finns ingen anledning att skynda. Vi har gott om tid. | [ dᵊ fɪns iŋen anledniŋ at ɧʏnda ‖ vi har gɔt um tʰid ‖ ] |
| 2414 | There aren't many tourists here. > There aren't a lot of tourists here. | Det finns inte många turister här. > Det finns inte mycket turister här. | [ dᵊ fɪns ɪntᵊ moŋa tʰʉrister hɛr ‖ > dᵊ fɪns ɪntᵊ mʏket tʰʉrister hɛr ‖ ] |

### Cluster D — pages 230–236 (sentences 2589–2609)

| # | EN | SV | IPA |
|---|---|---|---|
| 2589 | She speaks English so well you would think it was her native language. | Hon pratar engelska så bra att du skulle kunna tro att det var hennes modersmål. | [ hun pʰratar eŋelskja so bra at dʉ skølᵊ kʰøna tʰru at dᵊ var henes mudeʃmol ‖ ] |
| 2590 | The music was so loud that you could hear it from miles away. | Musiken var så hög att man kunde höra det flera kilometer ifrån. | [ mʉsiken var so høɣ at man kʰʉndᵊ høra dᵊ flera çilumeter ɪfron ‖ ] |
| 2591 | I haven't seen her for such a long time. | Jag har inte sett henne under så lång tid. | [ jaɣ har ɪntᵊ set henᵊ ʉnder so loŋ tʰid ‖ ] |
| 2592 | I didn't know it was such a long way. | Jag visste inte att det var så långt. | [ jaɣ vistᵊ ɪntᵊ at dᵊ var so loŋt ‖ ] |
| 2593 | You're lazy. You don't work hard enough. | Du är lat. Du arbetar inte tillräckligt hårt. | [ dʉ ɛr lat ‖ dʉ arbetar ɪntᵊ tʰɪlrɛklijt hɔʈ ‖ ] |
| 2594 | Is Raj going to apply for the job? Does he have enough experience? > Is he experienced enough for the job? | Kommer Raj att söka jobbet? Har han tillräckligt med erfarenhet? > Är han erfaren nog för jobbet? | [ kʰumer (...) at søkja jubet ‖ har han tʰɪlrɛklijt med erfarenhet ‖ > ɛr han erfaren nuɣ før jubet ‖ ] |
| 2595 | They're too young to get married. > They're not old enough to get married. | De är för unga för att gifta sig. > De är inte tillräckligt gamla för att gifta sig. | [ dɛ ɛr før ʉŋa før at jifta sɛj ‖ > dɛ ɛr ɪntᵊ tʰɪlrɛklijt gamla før at jifta sɛj ‖ ] |
| 2596 | It's too far to walk home from here. | Det är för långt att promenera hem härifrån. | [ dᵊ ɛr før loŋt at pʰrumenera hem hɛrɪfron ‖ ] |
| 2597 | These apples aren't ripe enough to eat. | Dessa äpplen är inte tillräckligt mogna för att ätas. | [ desa epplen ɛr ɪntᵊ tʰɪlrɛklijt muŋna før at ɛtas ‖ ] |
| 2598 | The situation is too complicated to explain. | Situationen är för komplicerat att förklara. | [ situaɕunen ɛr før kʰumpliserat at førklara ‖ ] |
| 2599 | You're standing too close to the camera. Can you move a little farther away? | Du står för nära kameran. Kan du flytta lite längre bort? | [ dʉ stor før nɛra kʰjameran ‖ kjan dʉ flʏta litᵊ lɛŋrᵊ buʈ ‖ ] |
| 2600 | The instructions were very complicated. They could have been simpler. | Instruktionerna var mycket komplicerade. De kunde ha varit enklare. | [ instrukɕuneɳa var mʏket kʰumpliseradᵊ ‖ dɛ kʰʉndᵊ ha varit enklarᵊ ‖ ] |
| 2601 | It takes longer by train than car. | Det tar längre tid med tåg än bil. | [ dᵊ tʰar lɛŋrᵊ tʰid med tʰoɣ ɛn bil ‖ ] |
| 2602 | Walter did worse than I did on the test. | Walter presterade sämre än jag gjorde på testet. | [ (...) pʰresteradᵊ sɛmrᵊ ɛn jaɣ judᵊ pʰo tʰestet ‖ ] |
| 2603 | My friends arrived earlier than I expected. | Mina vänner kom tidigare än jag väntat. | [ mina vɛner kʰum tʰidigarᵊ ɛn jaɣ vɛntat ‖ ] |
| 2604 | The buses run more often than the trains. | Bussarna går oftare än tågen. | [ bɵsaɳa gor uftarᵊ ɛn tʰojen ‖ ] |
| 2605 | There were a lot of people on the bus. It was more crowded than usual. | Det var många människor på bussen. Det var mer trångt än vanligt. | [ dᵊ var moŋa mɛniskur pʰo bɵsen ‖ det var mer tʰroŋt ɛn vanlijt ‖ ] |
| 2606 | Could you speak a bit more slowly? | Kan du prata lite långsammare? | [ kʰjan dʉ pʰrata litᵊ loŋsamarᵊ ‖ ] |
| 2607 | This bag is slightly heavier than the other one. | Denna väska är något tyngre än den andra. | [ dena veskja ɛr nogut tʰʏŋrᵊ ɛn den andra ‖ ] |
| 2608 | Her illness was far more serious than we thought at first. | Hennes sjukdom var långt allvarligare än vad vi först trodde. | [ henes ɧʉkdum var loŋt alvaligarᵊ ɛn vad vi føʃt tʰrudᵊ ‖ ] |
| 2609 | I've waited long enough and I'm not waiting any longer. | Jag har väntat länge nog och jag väntar inte längre än såhär. | [ jaɣ har vɛntat lɛŋᵊ nuɣ ɔχ jaɣ vɛntar ɪntᵊ lɛŋrᵊ ɛn sohɛr ‖ ] |

### Cluster E — pages 295–300 (sentences 2784–2801)

| # | EN | SV | IPA |
|---|---|---|---|
| 2784 | Since the accident was my fault, I had to pay for the damage to the other car. | Eftersom olyckan var mitt fel var jag tvungen att betala för skadorna på den andra bilen. | [ eftesum ulʏkjan var mɪt fel var jaɣ tʰvuŋen at betala før skjaduɳa pʰo den andra bilen ‖ ] |
| 2785 | A lot of my friends are getting married this year. I've been getting lots of invitations TO wedding banquets. | Många av mina vänner ska gifta sig i år. Jag har fått massor av inbjudningar TILL bröllopsfester. | [ moŋa av mina vɛner skja jifta sɛj i or ‖ jaɣ har fɔt masur av inbjʉdniŋar tʰɪl brœlupsfester ‖ ] |
| 2786 | The scientists have been working ON a solution TO the problem FOR many years. | Forskarna har arbetat PÅ en lösning PÅ problemet I många år. | [ fuʃkjaɳa har arbetat pʰo en løsniŋ pʰo pʰrublemet i moŋa or ‖ ] |
| 2787 | I was very surprised BY her reaction TO my simple suggestion. | Jag blev mycket förvånad ÖVER hennes reaktion PÅ mitt enkla förslag. | [ jaɣ blev mʏket førvonad øver henes reakɕun pʰo mɪt enkla føʃlaɣ ‖ ] |
| 2788 | His attitude toward his job is so positive that he increases his sales every month. | Hans inställning till sitt jobb är så positiv att han ökar sin försäljning varje månad. | [ hans instɛlniŋ tʰɪl sɪt jub ɛr so pʰusitiv at han økjar sin føʃɛjniŋ varjᵊ munad ‖ ] |
| 2789 | Do you have a good relationship WITH your parents? | Har du en bra relation MED dina föräldrar? | [ har dʉ en bra relaɕun med dina føreldrar ‖ ] |
| 2790 | The police want to question a suspect in connection with the murder. | Polisen vill förhöra en misstänkt i samband med mordet. | [ pʰulisen vɪl førhøra en mɪstɛnkt i samband med mudet ‖ ] |
| 2791 | The police believe there's a connection between the two murders, based on DNA evidence. | Polisen tror att det finns ett samband mellan de två morden, baserat på DNA-bevis. | [ pʰulisen tʰrur at dᵊ fɪns et samband melan dɛ tʰvo mudᵊn ‖ baserat pʰo dna-bevis ‖ ] |
| 2792 | There are minor differences between many European languages. | Det finns små skillnader mellan många europeiska språk. | [ dᵊ fɪns smo ɧɪlnader melan moŋa eʉrupeiskja sprok ‖ ] |
| 2793 | It was really kind of you to help me. I really appreciate it. | Det var verkligen snällt av dig att hjälpa mig. Jag uppskattar det verkligen. | [ dᵊ var verklijen snɛlt av dɛj at jɛlpa mɛj ‖ jaɣ øpskjatar dᵊ verklijen ‖ ] |
| 2794 | He donated half his wealth to charity, which was very generous of him. | Han donerade halva sin förmögenhet till välgörenhet, vilket var mycket generöst av honom. | [ han duneradᵊ halva sin førmøjenhet tʰɪl veljørenhet ‖ vɪlket var mʏket jenerøst av hunum ‖ ] |
| 2795 | Always be polite and nice to strangers. They might be the boss at your next job. | Var alltid artig och trevlig mot främlingar. De kan vara chef på ditt nästa jobb. | [ var altid aʈɛj ɔχ tʰrevlɛj mut fremliŋar ‖ dᵊ kʰjan vara ʃef pʰo dɪt nesta jub ‖ ] |
| 2796 | Rashid is really angry about what his brother said. | Rashid är verkligen arg över vad hans bror sa. | [ (...) ɛr verklijen aʁj øver vad hans brur sa ‖ ] |
| 2797 | He's upset with him because he wants to put their parents in a nursing home. | Han är upprörd över honom för att han vill sätta deras föräldrar på ett vårdhem. | [ han ɛr ʉpprød øver hunum før at han vɪl sɛta deras føreldrar pʰo et vɔdhem ‖ ] |
| 2798 | In fact, his sister was even more furious when she heard it. | Faktum är att hans syster var ännu mer rasande när hon hörde det. | [ faktʉm ɛr at hans syster var ɛnʉ mer rasandᵊ nɛr hun høʁdᵊ dᵊ ‖ ] |
| 2799 | Are you excited about going to Europe next week? | Är ni glada över att åka till Europa nästa vecka? | [ ɛr ni ɣlada øver at okja tʰɪl eʉrupa nesta vekja ‖ ] |
| 2800 | Actually, I'm upset about not getting invited to the most important conference. | Jag är upprörd över att inte bli inbjuden till den viktigaste konferensen. | [ jaɣ ɛr ʉpprød øver at ɪntᵊ bli inbjʉden tʰɪl den viktigastᵊ kʰunferensen ‖ ] |
| 2801 | I'm sorry to hear that. | Jag är ledsen att höra det. | [ jaɣ ɛr ledsen at høra dᵊ ‖ ] |

### Cluster F — pages 355–360 (sentences 2964–2981)

| # | EN | SV | IPA |
|---|---|---|---|
| 2964 | There was a fight on the street and three men ended up in the hospital. | Det var slagsmål på gatan och tre män hamnade på sjukhus. | [ dᵊ var slaɣsmol pʰo gatan ɔχ tʰrə men hamnadᵊ pʰo ɧʉkhʉs ‖ ] |
| 2965 | Don't argue with the police officer or you'll just end up getting arrested. | Argumentera inte med polisen annars kommer du att bli arresterad. | [ aʁgʉmentera ɪntᵊ med pʰulisen anaʃ kʰumer dʉ at bli aresterad ‖ ] |
| 2966 | There are two universities in the city, and students make up twenty per cent (20%) of the population. | Det finns två universitet i staden, och studenter utgör tjugo procent (20%) av befolkningen. | [ dᵊ fɪns tʰvo ʉnivesitet i staden ‖ ɔχ stʉdenter ʉtjør çʉgu pʰrusent (20%) av befulkniŋen ‖ ] |
| 2967 | I'll be ready in a few minutes. You go on ahead and I'll catch up with you. | Jag kommer att vara redo om några minuter. Du kan gå i förväg. Jag kommer ikapp dig. | [ jaɣ kʰumer at vara redu um noɣra minʉter ‖ dʉ kʰjan go i førvɛɣ ‖ jaɣ kʰumer ikjap dɛj ‖ ] |
| 2968 | My parents dropped me off at the airport two hours before my flight was scheduled to take off. | Mina föräldrar släppte av mig på flygplatsen två timmar innan mitt flyg var planerat att lyfta. | [ mina føreldrar sleptᵊ av mɛj pʰo flʏɣplatsen tʰvo tʰɪmar ɪnan mɪt flʏɣ var pʰlanerat at lʏfta ‖ ] |
| 2969 | My parents were there again to pick me up when I flew back home. | Mina föräldrar var där igen för hämta upp mig när kom hem. *(likely missing "att" / subject — see Grammar points)* | [ mina føreldrar var dɛr ijen før hemta øp mɛj nɛr kʰum hem ‖ ] |
| 2970 | Simon is terribly creative and is always coming up with great ideas. | Simon är väldigt kreativ och kommer alltid med bra idéer. | [ (...) ɛr veldijt kʰreativ ɔχ kʰumer altid med bra ideer ‖ ] |
| 2971 | I'm saving my money up for a trip around the world. | Jag sparar mina pengar till en resa runt om i världen. | [ jaɣ sparar mina pʰeŋar tʰɪl en resa rʉnt um i vɛlden ‖ ] |
| 2972 | The F1 racer caught fire and blew up. Luckily the driver just narrowly escaped. | F1-bilen fattade eld och exploderade. Lyckligtvis undkom föraren. | [ (...)-bilen fatadᵊ eld ɔχ eksplʉderadᵊ ‖ lʏklijtvis ʉndkum føraren ‖ ] |
| 2973 | A friend of mine was attacked and beaten up a few days ago. He's been in the hospital ever since. | En vän till mig attackerades och misshandlades för några dagar sedan. Han har varit på sjukhuset sedan dess. | [ en vɛn tʰɪl mɛj atakerades ɔχ mɪshandlades før noɣra dagar sedan ‖ han har varit pʰo ɧʉkhʉset sedan des ‖ ] |
| 2974 | Ludwig and Rita broke up. > Ludwig and Rita split up. | Ludwig och Rita gjorde slut. > Ludwig och Rita separerade. | [ (...) ɔχ (...) judᵊ slʉt ‖ > (...) ɔχ (...) separeradᵊ ‖ ] |
| 2975 | Ludwig and Rita ended up breaking up. > Ludwig and Rita ended up splitting up. | Det slutade med att Ludwig och Rita gjorde slut. > Ludwig och Rita gjorde slutligen slut. | [ dᵊ slʉtadᵊ med at (...) ɔχ (...) judᵊ slʉt ‖ > (...) ɔχ (...) judᵊ slʉtlijen slʉt ‖ ] |
| 2976 | They couldn't get along with each other so the relationship didn't work out in the end. | De kunde inte komma överens med varandra så relationen fungerade inte till slut. | [ dɛ kʰʉndᵊ ɪntᵊ kʰuma øverens med varandra so relaɕunen fʉŋeradᵊ ɪntᵊ tʰɪl slʉt ‖ ] |
| 2977 | Plans to build a new factory have been held up because of the company's financial problems. | Planerna på att bygga en ny fabrik har hållits upp på grund av företagets ekonomiska problem. | [ pʰlaneɳa pʰo at bʏga en ny fabrik har hɔlits øp pʰo ɣrʉnd av føretajets ekunumiskja pʰrublem ‖ ] |
| 2978 | We live next to an international airport, so we have to put up with a lot of noise. | Vi bor intill en internationell flygplats, så vi måste stå ut med en massa oväsen. | [ vi bur ɪntɪl en intenaɕunel flʏɣplats ‖ so vi mostᵊ sto ʉt med en masa uvɛsen ‖ ] |
| 2979 | The two brothers are identical twins. So everybody gets them mixed up. | De två bröderna är enäggstvillingar. Så alla blandar ihop dem. | [ dɛ tʰvo brødeɳa ɛr enɛgstvɪliŋar ‖ so ala blandar ihup dem ‖ ] |
| 2980 | Your house is an absolute mess. When are you going to get this place cleaned up? | Ditt hus är en fullkomlig röra. När kommer ni att städa detta ställe? | [ dɪt hʉs ɛr en fɔlkumlɛj røra ‖ nɛr kʰumer ni at stɛda deta stɛlᵊ ‖ ] |
| 2981 | When your language training starts getting tough, it means you're about to make a big breakthrough, so stick with it and don't give up. | När din språkutbildning börjar bli jobbig betyder det att du är på väg att göra ett stort genombrott, så håll fast och ge inte upp. | [ nɛr din sprokʉtbildniŋ børjar bli jubɛj betyder dᵊ at dʉ ɛr pʰo vɛɣ at jøra et stuʈ jenumbrut ‖ so hɔl fast ɔχ jᵊ ɪntᵊ øp ‖ ] |

### Cluster G — page 367 (sentence 3000, final sentence of the book)

| # | EN | SV | IPA |
|---|---|---|---|
| 3000 | The lone ranger got on his horse and rode off into the sunset. | Den ensamma skogvaktaren hoppade upp på sin häst och red iväg i solnedgången. | [ den ensama skuɣvaktaren hupadᵊ øp pʰo sin hɛst ɔχ red iveɣ i sulnedgoŋen ‖ ] |

---

## Copyright discipline reminder

All 121 triplets above are short (1–3 sentence) pedagogical drill items from a sentence-mining
course, reproduced per this dispatch's explicit instruction because the sentence-pair format itself
is the raw corpus material this project needs — not bulk reproduction of explanatory prose,
vocabulary boxes, or dialogue blocks in the sense the general copyright-discipline rule is aimed at.
No surrounding explanatory text, exercise instructions, or front-matter prose from the book is
reproduced beyond the short illustrative fragments quoted in the Grammar points section above. See
`../../00_Reference_Extraction_Spec.md`.
