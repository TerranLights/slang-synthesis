# Korean — Established Vocabulary/Grammar: *A Korean Grammar on Semantic-Pragmatic Principles* (Keedong Lee, full book)

**Source:** Keedong Lee, *A Korean Grammar on Semantic-Pragmatic Principles* (Hankook Munhwasa
[한국문화사], Seoul; no printed publication year was found anywhere in the scanned front matter,
copyright page, or References section — left blank throughout rather than guessed). 561 printed
pages (Preface + Chapters 1–9 + References) scanned as a 284-page PDF with **no text layer at
all** (`pdftotext`/PyMuPDF return zero characters across every one of the 284 pages — confirmed
programmatically, not just spot-checked) and **no decodable font-substitution cipher** (there is
no garbled-but-consistent glyph mapping to decode, unlike several other Korean sources in this
project — the PDF embeds the text as raster images with no character layer whatsoever). The entire
book was therefore vision-read in full, one PDF page at a time, rendered at 100dpi via `pdftoppm`.

**Scan format:** each PDF page is a **two-printed-page spread** (the physical book was scanned open
flat, left+right pages captured together in one landscape image), confirmed empirically and
holding consistently across the whole book: `printed_page = 2×(PDF_page) − 2` (left side) /
`2×(PDF_page) − 1` (right side), verified against the book's own running headers at the start,
middle, and end of the file (PDF p.17 → printed p.33 Ch.2 TOC; PDF p.135 → printed p.269 Ch.5 TOC;
PDF p.281 → printed p.561 References) with zero drift anywhere in between.

**Romanization:** the author's own Yale-like system (`ey`/`ay`/`yey` digraphs, doubled consonants
`ss`/`kk`/`tt`/`pp`/`cc`, no macrons) — reproduced as printed throughout.

**Dispatch structure (for auditability):** given the book's length (9 chapters, 561 pages), this
extraction was split into 12 page-range chunks — Chapter 1 (sentence-enders) was read directly by
the orchestrating agent; the remaining 11 chunks (Chapters 2–3, three sub-chunks of Chapter 4, and
Chapters 5–9, with Chapter 9 split into two halves) were each dispatched to a separate scratch-only
subagent with the exact page range, book context, and this project's extraction spec, then
merged into this single file by the orchestrator. Every chunk's own coverage note (kept below,
chapter by chapter) documents its own redundant-vs-new judgment call against the 46 established/
Korean files that predate this dispatch — summarized at a high level here:

**Aggregate coverage note.** This monograph is a theoretical, pragmatics-focused academic grammar
(minimal-pair contrastive analysis of near-synonymous forms, speaker-attitude/assumption modeling,
force-dynamics explanations) — categorically different in kind from the pedagogical textbooks that
make up most of the prior 46-file Korean corpus. Across all 9 chapters, the **bare pedagogical-level
facts already captured elsewhere were explicitly skipped** (e.g. "에 marks location," "만 means
only," "-지만 means but/although," "-었-/-겠-/-고 있- are the past/future/progressive morphemes,"
"-기/-음 are nominalizer suffixes," the basic morphological passive pattern, the basic 안/-지 않다
negation pair) — but the overwhelming majority of this book's actual content survives that filter,
because its entire project is explaining the semantic-pragmatic *why* behind forms that pedagogical
sources only ever teach as surface facts. Three chapters are close to 100% new regardless of topic
overlap: **Chapter 5 (Passives)**, whose two-passive-system theoretical argument has no prior
coverage at all; **Chapter 7 (Nominalization)**, which the author's own preface names as a central
motivation for writing the book (the -음/-기 choice); and **Chapter 8 (Tense-Aspect-Modality)**,
extracted fully and independently per this project's non-redundant-supplement rule even though a
different, independently-authored tense/aspect monograph for Korean was being extracted in parallel
elsewhere in this same dispatch wave (destined for `established/051`, per
`00_RESUME_HERE.md` — though see the numbering note below).

**Marginalia.** The vast majority of this scan is a clean, undamaged library/publisher copy with
zero handwritten content. **One exception was found and correctly excluded**: a stray
handwritten (orange/reddish ink) annotation in the right margin near the bottom of printed page
127 (within §4.2 *cwuta*, Chapter 4) — excluded entirely from the extraction per this project's
vision-reading guard, noted here rather than silently dropped.

**A numbering note, for the record.** While this dispatch was in flight, a sibling dispatch for
*A History of the Korean Language* (`established/049`) briefly occupied `established/051` with its
own overflow Part 2 content, colliding with that slot's Wave K4 reservation for *Tense and Aspect
in Korean* — the sibling dispatches self-corrected before this file was written: `051` now
correctly holds `051_tense_and_aspect_in_korean.md` and the History-of-Korean overflow was moved to
`053_history_of_korean_language_part2.md`. This dispatch's own target number, `052`, was free
throughout and unaffected.

---
## Korean — Established Vocabulary/Grammar: *A Korean Grammar on Semantic-Pragmatic Principles*, Chapter 1 "Sentence-Enders"

**Source:** Keedong Lee, *A Korean Grammar on Semantic-Pragmatic Principles* (Hankook Munhwasa [한국문화사], Seoul; publication year not visible in the scanned front matter), Chapter 1 "Sentence-Enders," printed pp.7-32 (PDF pages 4-18 of the scanned file — this source has no text layer at all and was fully vision-read; PDF pages are two-printed-page spreads). Romanization is the author's own Yale-like system (ey/ay/yey digraphs, doubled consonants ss/kk/tt/pp/cc, no macrons).

**Coverage note — non-redundant-supplement dispatch.** This is a theoretical, pragmatics-focused monograph — not a pedagogical textbook — and sentence-enders/speech-act markers of this specific semantic-pragmatic kind are not covered by any of the 46 prior established/ Korean files at this depth. Prior textbook sources establish `-다/-어/-지` etc. as plain-style sentence endings at a purely morphological level (which ending attaches to which stem) and 031 (honorifics) covers the six-level *speech-style* system (formality tiers: hapsyochey, hayyochey, etc.) — a completely different axis from what this chapter analyzes. This chapter is about a **second, orthogonal system**: within a single speech level (plain style, -ta/-ci/-e/-kwuna/-ney/-tela), the *pragmatic* choice of sentence-ender encodes the speaker's epistemic stance (prior awareness/commitment, assumed addressee bias, evidentiality, committal vs. noncommittal reporting). No prior established/ file analyzes this distinction at all. Everything in this chapter is kept as new. Vocabulary is sparse (as expected for an academic source per the extraction spec's allowance) since the chapter's content is almost entirely about six grammatical morphemes and their pragmatic semantics, illustrated with a small, repeated set of example-sentence content words.

No handwritten marginalia was found on any page in this chapter's range; this is a clean, undamaged library scan throughout pp.7-32.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| -ta (다) | neutral assertive sentence-ender | sentence-ender (bound morpheme) | core | — | contemporary (source published, undated) | — | — | grammar_reference | n/a | verified | Speaker thinks he is imparting something new to the addressee and that the addressee is not biased in any way. The simplest/most neutral ender; normal conversation-starter. Children boasting of something they believe their addressee doesn't know typically use `-ta`. |
| -e (어) | emphatic/contrastive sentence-ender | sentence-ender (bound morpheme) | core | — | contemporary (source published, undated) | — | — | grammar_reference | n/a | verified | Used when the speaker thinks the addressee holds some resistance or disbelief toward what is being said, and the speaker finds it necessary to emphasize the proposition. Same pragmatic meaning across statement, question, and imperative moods (unlike most of the other enders, whose meaning can shift with mood). |
| -ci (지) | ender presupposing shared belief/agreement | sentence-ender (bound morpheme) | core | — | contemporary (source published, undated) | — | — | grammar_reference | n/a | verified | Speaker believes the proposition is true AND assumes/expects the addressee will agree. In questions, implies the question is "too obvious to ask" (a challenge/rebuke reading) rather than a genuine information request. As a proposative ("let's..."), presupposes the addressee is already willing — contrasts with `-ca`, which does not presuppose willingness; from a social superior, a `-ci`-suggestion therefore reads as a stronger command than a `-ca`-suggestion. |
| -kwuna (구나) | mirative/surprise ender (new, unthought-of discovery) | sentence-ender (bound morpheme) | core | — | contemporary (source published, undated) | — | — | grammar_reference | n/a | verified | Speaker was entirely unaware of a state of affairs until noticing some perceptual evidence or consequence (smell, sight, physical trace, etc.) pointing to it; signals surprise at an unexpected, previously-unthought-of discovery. Can report the speaker's own unconscious actions (e.g. realizing upon waking that he must have slept). Works identically after past (`-ass-`) or present (`-nun-`) tense morphemes. |
| -ney (네) | mirative/surprise ender (expectation-contradicted) | sentence-ender (bound morpheme) | core | — | contemporary (source published, undated) | — | — | grammar_reference | n/a | verified | Speaker already held a prior belief/commitment about a proposition and then encounters evidence contradicting that specific prior belief — surprise arises from the conflict between expectation and new evidence (distinct from `kwuna`'s surprise-from-first-ever-discovery). Can also be used to project surprise onto the addressee's perspective. Compatible with negative sentences and with past/present/future tense. |
| -tela (더라) | noncommittal/retrospective-witness ender | sentence-ender (bound morpheme) | core | — | contemporary (source published, undated) | — | — | grammar_reference | n/a | verified | Reports something the speaker personally witnessed/experienced directly in the past, while remaining noncommittal about whether the state of affairs still holds now. Can stack after `-ta` (`-ass-ta-tela`, e.g. `wasstatela` "I heard that he came, but I'm not sure he's still here") to report hearsay while retaining the same noncommittal evidential stance. |
| Chelswu (철수) | (male personal name, used as a generic example-sentence subject throughout the book) | proper noun | core | — | contemporary (source published, undated) | — | — | grammar_reference | n/a | verified | Recurring placeholder name across nearly all example sentences in the book, comparable to "John" in English textbooks. |
| tampay phiwuta (담배 피우다) | to smoke (cigarettes) | verb phrase | core | — | contemporary (source published, undated) | — | — | grammar_reference | n/a | verified | Used repeatedly as an evidentiality example (smelling smoke → inferring `kwuna`). |
| swul masita (술 마시다) | to drink alcohol | verb phrase | core | — | contemporary (source published, undated) | — | — | grammar_reference | n/a | verified | — |
| issta (있다) | to exist / be located / have | existential verb | core | — | contemporary (source published, undated) | — | — | grammar_reference | n/a | verified | Used throughout the chapter's minimal pairs (e.g. `iss-kwuna` vs `iss-ney` vs `iss-tela`) to isolate the sentence-enders' contrast while holding the predicate constant. |

## Grammar points

### -ta (다): the neutral assertive ender

The speaker treats the propositional content as new information for the addressee and assumes the addressee holds no bias toward it. This is the default, least-marked sentence-ender — a plain conversation-opener. By contrast, the author shows that `-ci` or `-e` are normally *not* used to open a conversation, since both presuppose something about the addressee's prior stance that `-ta` does not (p.11).

### -e (어): the addressee-resistance ender

Used when the speaker assumes the addressee is resistant to, or disbelieving of, the proposition, and therefore finds it necessary to emphasize it. Unlike the other enders in this chapter, `-e`'s pragmatic meaning is constant across statement, question, and imperative moods — e.g. a plain imperative (`ppalli oala` "come quickly") versus a second, emphatic repetition after the addressee fails to comply (`ppalli oa` "DO come quickly," p.14-15) illustrates the same underlying "addressee is not complying/accepting" meaning recurring across an imperative use.

### -ci (지): the shared-belief/agreement ender

The speaker both believes the proposition and expects the addressee's agreement. The book works through this across three moods:
- **Statement:** implies the questioner "should already know" the answer, which can read as mild rebuke (pp.16-17) — contrasted directly against a neutral `-na` question, which carries no such implication.
- **Question:** not a genuine information request but a request for *confirmation*, since the speaker is already biased toward believing the proposition is true.
- **Suggestion/proposative:** `-ci` presupposes the addressee's willingness to comply, in contrast with the dedicated proposative ender `-ca`, which does not. This yields a pragmatic asymmetry: from a social superior to a subordinate, "icey kuman kaci" (더 이상 가지 — roughly "you want to go now, don't you?") is read as a *stronger* command than the `-ca`-form "icey kuman kaa," precisely because `-ci` forces the addressee's acceptance into the presupposition rather than leaving it open (pp.17-18).

The chapter also previews (pp.18-19) that `-ci` plays a distinct, separate role in negation (`V-ci anhta`), where a negative sentence built on `-ci` implies the speaker is actively correcting a belief the addressee is assumed to hold — contrasted with the plain negator `an`, which carries no such corrective implicature. (Negation is Chapter 6's own topic and is extracted separately and more systematically there.)

### -kwuna (구나): mirative ender for wholly new discoveries

Marks the speaker's realization of a state of affairs he was entirely unaware of until perceiving some sensory evidence or consequence pointing to it (smell, sight, a physical trace like wet clothing). The book models this with a two-part diagram: "Part A" is the unobserved process/event, "Part B" is the perceived consequence; perceiving B licenses an inference about A, and because A was wholly unanticipated, the inference carries a surprise reading (pp.20-21). Notably, `-kwuna` can also report the speaker's own actions performed unconsciously (e.g., realizing upon waking that he must have dozed off, p.22) — the "unawareness" condition applies to the speaker's own prior mental state, not only to external facts. The ender attaches identically after past (`-ass-kwuna`) and present (`-nun-kwuna`) tense morphemes with no change in its pragmatic meaning (p.23).

### -ney (네): mirative ender for expectation-contradicted discoveries

Marks surprise that arises specifically from new evidence *contradicting* a proposition the speaker already held a belief or commitment about — as opposed to `kwuna`'s surprise at something never previously considered at all. The book gives an explicit minimal-pair contrast (p.27): `kwuna`'s surprise is "discovery of unexpected/unthought-of state of affairs," while `ney`'s surprise is "discovery of a state of affairs contrary to [prior] expectation." `-ney` also works from a projected addressee-perspective (the speaker anticipates that the addressee, not the speaker, will be the one surprised, pp.25-26) and freely combines with negation and with past/present/future tense (unlike `kwuna`, whose use was only illustrated with past/present in this chapter).

### -tela (더라): noncommittal retrospective-witness ender

Used when the speaker is noncommittal about the current validity of a proposition he nonetheless directly witnessed or experienced in the past. The book's running example: asked "where is Chelswu?", answering with plain `issta`/`isse` ("he's there") overcommits if the speaker's information is stale, while `-tela` ("he was there [last I saw, not sure now]") correctly signals the information is time-bound personal testimony rather than a current-status claim (pp.29-30). `-tela` can stack onto an already-tensed `-ta` form (`-ass-ta-tela`) to report hearsay while retaining the same noncommittal evidential stance, e.g. `wasstatela` "I heard he came, but I'm not sure [he's still here]" (p.30-31).

### Cross-ender summary (speaker-attitude map)

Taken together, Chapter 1 establishes that Korean plain-style sentence-enders are not interchangeable stylistic variants but each encode a distinct epistemic/evidential stance: `ta` (neutral, no bias assumed), `e` (addressee assumed resistant, emphasis needed), `ci` (speaker believes + expects addressee agreement), `kwuna` (surprise from wholly new discovery), `ney` (surprise from expectation-contradicting discovery), `tela` (noncommittal, witnessed-but-not-asserted-as-current). This six-way system sits on a different axis entirely from the six-level speech-style/formality system already captured in `established/031` — that system governs *who* you are speaking to (social register), while this one governs the speaker's *epistemic relationship to the proposition and the addressee's presumed stance toward it*, independent of formality level.

---

## Korean — Established Vocabulary/Grammar: *A Korean Grammar on Semantic-Pragmatic Principles* (Keedong Lee), Chapter 2 "Postpositions"

**Source:** Keedong Lee, *A Korean Grammar on Semantic-Pragmatic Principles*, Hankook Munhwasa
(한국문화사), Seoul (no printed publication year visible in this page range). Chapter 2
"Postpositions," printed pages 35-53 (scanned-image PDF, vision-read — no text layer, no
font-substitution cipher; image files `page-018.png` through `page-028.png`, two-printed-pages-
per-image spreads). Covers §2.1 *ey* (에), §2.2 *eykey* (에게), §2.3 *eyse* (에서), §2.4 *ulo*
(으로) with subsections §2.4.1 *kilo* (기로), §2.4.2 *umulo* (음으로), §2.4.3 *kesulo* (것으로),
§2.4.4 *ulose* (으로서). Chapter 2 runs from p.35 (image `page-018.png`, right side) through the
chapter-summary paragraph on p.53 (image `page-028.png`, left side); the next image
(`page-028.png`, right side) is Chapter 3 "Particles"'s own table of contents, confirming the
chapter boundary. No handwritten marginalia was found anywhere in this range — this is a clean
library scan and every mark checked was consistent typeset print matching the surrounding page.

**Coverage note — non-redundant supplement.** Korean already has 46 established/ extraction files,
many pedagogical (Integrated Korean, College Korean, the SNU course series, Korean Grammar for
International Learners, etc.) that already cover the bare pedagogical facts about these four
postpositions — "에 marks location/time," "에게 marks an animate recipient of giving-type verbs,"
"에서 marks the location of an action," "으로 marks means/direction/material." **Those bare facts
are treated as already captured and are deliberately NOT re-extracted here.** What this chapter
contributes beyond that level, and what is kept below, is Lee's genuinely distinctive
semantic-pragmatic apparatus:

- a unified **figure-ground** account of *ey* (rather than listing "location" and "goal" as
  separate unrelated meanings) and its metaphorical extension to abstract reference points, cause,
  evaluation-standard, and rate;
- the **source-vs-goal derivation** of *eykey*'s meaning from verb semantics rather than the
  postposition itself (the 배우다/가르치다 and 사다/팔다 minimal pairs);
- the direct **minimal-pair contrast of *ey* vs. *eyse*** (container-relation vs.
  activity-background: 냄비에/*에서 vs. *에/부엌에서) and the **살다 "reside" vs. "make a living"**
  contrast, plus *eyse*'s striking extension to an **institutional-subject/agentive marker** (회사
  에서, 나라에서) — this last point is rarely covered even in advanced pedagogical grammars;
- the **unified "accompaniment" account of *ulo*** deriving path/direction/goal/speed/means/
  material/resultant-state/attendant-property/cause readings from one abstract core meaning
  depending on what noun fills its argument, rather than listing these as unrelated senses;
  - all four §2.4 subtypes (*kilo*, *umulo*, *kesulo*, *ulose*), which are explicitly advanced,
    morphologically-composed forms (nominalizer + *ulo*, or *ulo* + *se*) not covered at
    introductory level in any of the 46 prior extractions — including the *kesulo* vs. *kes-ul*
    **epistemic-certainty minimal pair** (knowledge already on target vs. directed toward but
    uncertain), which is a genuinely subtle finding.

A short aside on *ey* used with the nominalizer *ki* (page 40, labeled "kiey (기에)" in the source)
is also captured under §2.1, since it is not covered by any prior pedagogical extraction either.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| ey (에) | locative/goal postposition — relates a figure (x) to a ground/reference-point (y) | postposition | core | — | — | — | — | grammar_reference | n/a | verified | Core postposition of the chapter; appears dozens of times across pp.35-53, cross-checked. |
| eykey (에게) | marks an animate participant other than the subject (source or goal, per verb semantics) | postposition | core | — | — | — | — | grammar_reference | n/a | verified | Glossed by the source itself as *ey* + *key* (animacy marker); morpheme breakdown below. |
| key (게, bound) | animacy-marking bound morpheme, combines with *ey* to form *eykey* | bound postposition morpheme | core | — | — | — | — | grammar_reference | n/a | verified | Not used independently in this chapter; only ever cited as a component of *eykey*. |
| eyse (에서) | denotes a general background/location for a situation or process (vs. *ey*'s object-relation); also an institutional/collective-agent marker | postposition | core | — | — | — | — | grammar_reference | n/a | verified | — |
| ulo (으로) | general "accompaniment" postposition; surface sense (path/direction/goal/means/material/cause/etc.) derived contextually from the noun it attaches to | postposition | core | — | — | — | — | grammar_reference | n/a | verified | — |
| ki (기, nominalizer) | nominalizes a predicate, denoting the existence of a state, activity, or event | bound nominalizer | core | — | — | — | — | grammar_reference | n/a | verified | Combines with *ey* ("kiey," p.40 aside) and with *ulo* (§2.4.1 *kilo*). |
| um (음, nominalizer) | nominalizes a predicate, denoting an abstract proposition (contrasted explicitly with *ki*) | bound nominalizer | core | — | — | — | — | grammar_reference | n/a | verified | Combines with *ulo* in §2.4.2 *umulo*. |
| kes (것) | dependent noun "fact/reality," used with epistemic verbs | dependent noun | core | — | — | — | — | grammar_reference | n/a | verified | Contrasted as *kes-ul* (object marker) vs. *kes-ulo* (§2.4.3) for a certainty distinction. |
| se (서, bound) | bound morpheme combining with *ulo* to emphasize a present/resultant capacity reading | bound postposition morpheme | core | — | — | — | — | grammar_reference | n/a | verified | Same *-se* element also appears bound to *ey* in *eyse*; the source does not spell out whether these are historically the same morpheme, so no claim is made here beyond what's printed. |
| kilo (기로) | *ki* + *ulo*; marks a not-yet-realized action as the attendant goal of a promise/decision | postposition (compound) | core | — | — | — | — | grammar_reference | n/a | verified | See morpheme breakdown below. |
| umulo (음으로) | *um* + *ulo*; marks the ground/basis of a judgment or assertion | postposition (compound) | core | — | — | — | — | grammar_reference | n/a | verified | See morpheme breakdown below. |
| kesulo (것으로) | *kes* + *ulo*; marks an assumption/inference (uncertain knowledge), contrasted with *kes-ul* (certain knowledge) | postposition (compound) | core | — | — | — | — | grammar_reference | n/a | verified | See morpheme breakdown below. |
| ulose (으로서) | *ulo* + *se*; emphasizes a present or future capacity/role of the subject, where bare *ulo* reads as tool/means instead | postposition (compound) | core | — | — | — | — | grammar_reference | n/a | verified | See morpheme breakdown below. Source marks tool-reading *ulose* examples (펙스로써, 망치로써) as degraded with a `?`. |

**Morpheme breakdown.**

> **eykey** = ey (locative/reference-point postposition) + key (animacy marker) — the source
> explicitly glosses this composition (p.40): "the postposition *eykey* is made up of two
> morphemes: *ey*... and *key*... a marker of animacy."

> **kilo** = ki (nominalizer: existence of a state/activity/event) + ulo (accompaniment) — the
> not-yet-realized action nominalized by *ki* is treated as "attendant upon" the promise/decision,
> i.e. accompanying it in the sense *ulo* generally marks.

> **umulo** = um (nominalizer: abstract proposition) + ulo (accompaniment) — the abstract
> proposition nominalized by *um* serves as the ground/basis *ulo* marks for an assertion.

> **kesulo** = kes (dependent noun "fact/reality") + ulo (accompaniment, here marking an inferred
> rather than directly known ground) — contrasts with **kes-ul** = kes + ul (object marker),
> which marks the same fact as directly/certainly known.

> **ulose** = ulo (accompaniment) + se (bound morpheme emphasizing present/resultant capacity) —
> demonstrates that *ulo*'s general meaning survives composition while *se* narrows it to a
> specific capacity reading.

## Grammar points

### 2.1 *ey* (에) — figure-ground postposition, and its metaphorical extensions

Lee frames *ey*'s core meaning through a figure-ground contrast: the figure (x) is smaller,
weaker, nearer, and clearer than the ground (y), and tends to be mobile while the ground tends to
be static (p.35). In locative expressions, the antecedent of *ey* (y) is the reference point with
regard to which x's location is specified ("Chelswu is in the room," 철수가 방에 있다). This
figure-ground relation is normally asymmetric and not reversible (hand/fingers: 손가락이 손에
있다 is fine but the reverse reading doesn't hold the same way), except when the two entities
aren't clearly distinguished from one another (fence/house: either "there is a house inside the
fence" or "there is a fence around the house" works, p.35-36).

In movement expressions, x is dynamic and y (marked by *ey*) is the static goal the movement is
specified against (e.g. "He went to Pusan," p.36). But *ey* can also mark a **dynamic y that
influences x** — i.e. a cause — when y is something capable of exerting force: wind blowing down
a tree or blowing away a hat and a boat, cold making a child shiver, beer making someone drunk,
lies deceiving people (p.37-38; e.g. 그는 맥주에 취해 있다 "He is drunk from too much beer"). Lee
extends the same figure-ground logic metaphorically to **abstract reference points** — an
abstract location for an abstract interest (관심이 정구에 있다, "her interest lies in tennis"),
and to **evaluation standards** (이 음식은 건강에 좋다, "this food is good for health") and
**rates/frequency** (fish priced "per ten fish," 열마리에). The antecedent of *ey* can also be a
**point or duration in time** specifying when a situation exists (그는 작년에 왔다 "he came last
year"; 육게월에 걸쳐서, "over a six-week period," p.39).

**Aside: *ey* with the nominalizer *ki* ("kiey," p.40).** When *ey* is used with *ki* (which
marks the existence of a situation), the figure and the ground are both situations rather than
objects: "아이가 길에서 울기에, 내가 집으로 데리고 왔다" ("As the child was crying on the road, I
took him home") — the figure-situation (taking the child home) is specified in relation to the
ground-situation (the child crying).

### 2.2 *eykey* (에게) — source/goal derived from verb semantics, not from the postposition itself

Morphologically *eykey* = *ey* (the postposition of §2.1) + *key* (an animacy marker), so *eykey*
marks an animate participant other than the subject, where bare *ey* would mark an inanimate one
(나는 그 돈을 회사에/?에게 보냈다 "I sent the money to the company" vs. 친구에게/?에 "to the
friend," p.41). Lee's key point: *eykey*'s more specific reading as **source** vs. **goal** is
"not inherent in the postposition, but is derived from the meaning of the postposition and that
of the verb" (p.42). The minimal pair 배우다 "learn" / 가르치다 "teach" both take *eykey* for the
other conscious participant, but it reads as source with 배우다 ("나는 그 분에게 영어를 배웠다,"
I learned English *from* him) and goal with 가르치다 (*to* him). Likewise 사다 "buy" / 팔다 "sell"
both take 그 여자에게, read as source ("bought a car from the woman") or goal ("sold the car to
the woman") purely from the verb. *Eykey* can also mark an animate **reference point for
evaluation**, parallel to *ey*'s non-animate use for the same function: "이 문제는 그 아이에게
어렵다" ("this problem is difficult for the boy," p.42).

### 2.3 *eyse* (에서) — general background for a situation, contrasted directly with *ey*

Where *ey* relates two entities in a figure-ground (often container/object) relation, *eyse*
denotes "a general background for a situation" (p.43). Lee's central minimal pair: 어머니가
냄비에/*에서 밥을 짓는다 (a pot can hold the rice being cooked, so *ey* is fine, but a pot cannot
be a "general location for cooking," so *eyse* is rejected) vs. 부엌에서/*에 밥을 짓는다 (a
kitchen can be the general location of the cooking activity, so *eyse* is fine, but a kitchen
"cannot be thought of as a utensil for cooking," so *ey* is rejected).

With some intransitive verbs, the same noun can take either marker with a real meaning
difference: 그는 서울에/에서 산다 — with *ey*, "he resides in Seoul" (plain location); with
*eyse*, "he makes a living in Seoul" (Seoul as the venue of his activity, p.43-44).

With locomotion verbs specifically, *eyse* denotes a **source** (starting point), distinguished
from manner-of-locomotion verbs where *eyse* just denotes the activity's general background:
운동장에서 뛰고 있다 ("jumping in the playground," background) vs. 학교에서 왔다 ("came from
school," source, p.44). This source sense extends to **range starting points**: ages "ranging
from ten to fifteen" (열살에서 열다섯살 사이), money "deducted from" a salary (봉급에서 그 돈을
빼었다, p.44-45). *Eyse* also marks **abstract/mental locations or motivations**: beating someone
"out of jealousy" (질투심에서), opening a door "out of curiosity" (호기심에서), doing work "from
a sense of responsibility" (책임감에서, p.45).

Most strikingly, *eyse* can function **like a subject/agentive marker** for institutional or
collective agents: "이 비용은 회사에서 부담한다" ("the firm bears these expenses") and "이 법은
나라에서 정했다" ("the government made the law," p.45-46). Lee's explanation ties this back to the
source concept: an agent in a situation is an energy source, and the source is also "a location
from which energy flows" — so agent and source are semantically close enough that *eyse* can mark
either.

### 2.4 *ulo* (으로) — a unified "accompaniment" account

Lee proposes a single abstract core meaning for *ulo*: "something x accompanies another thing y
when x co-occurs/is co-present with y" (p.46). The specific readings traditionally taught as
separate meanings (path, direction, goal, speed, means of locomotion, material, instrument,
resultant state, attendant property, cause) are all presented as contextual specifications of this
one vague "accompaniment" meaning, driven by what noun fills *ulo*'s argument slot — "it is not
easy to tell what *ulo* exactly means because the postposition simply tells us that y accompanies
some movement... the general and vague meaning... is made more specific when y is replaced by a
noun" (p.46-47).

Illustrated categories, each read as a type of "accompaniment":
- **Locomotion path/direction/goal/speed/means**: 신작로로 갔다 ("went along a path"), 북쪽으로
  갔다 ("went north"), 빠른 걸음으로 ("with a quick pace"), 버스로 ("by bus") — Korean collapses
  distinctions English splits across different prepositions into one postposition (p.46-47).
- **Body parts / mental states as accompaniment of the agent**: caught a ball "with his left
  hand" (왼손으로), welcomed someone "with a warm heart" (즐거운 마음으로) — body parts and
  states of mind/feelings both treated as accompanying the agent (p.47).
- **Tools/instruments**: directly-controlled tools (hammer, saw) and indirectly-controlled
  "tools" used for linguistic convenience (ship, mail: "sent by ship," "sent by mail") are both
  marked with *ulo* (p.47-48).
- **Materials**: what the agent uses to make something accompanies the making process — "made
  bread out of flour" (밀가루로), "made rice cake out of rice" (쌀로, p.48).
- **Resultant state**: the new state an affected object undergoes accompanies its original
  state — "broke the pencil into two pieces" (두 동강으로), "tore the clothes into many pieces"
  (여러 갈래로, p.49).
- **Attendant properties/characteristics** with mental-activity verbs: "we regard him as a
  genius" (천재로), "he regards us as liars" (거짓말쟁이로) — the property ascribed is treated as
  accompanying the object (p.49).
- **Cause**, when the subject is non-agentive and doesn't directly control the "tool": "down with
  a cold" (감기로), "stood up again with her friend's help" (도움으로, p.49) — parallel to how
  *eyse* extends from source to agent-marking (§2.3), Lee notes the agent and the source/cause are
  semantically close, so the *ulo*-phrase can denote cause.

Lee notes *ulo* retains this general "accompaniment" meaning even when it combines with the
nominalizers *ki* and *um* and the dependent noun *kes* (p.50) — covered as the four numbered
subsections:

#### 2.4.1 *kilo* (기로)

*Ki* nominalizes an adjective/verb into a nominal denoting "the existence of states, activities,
or events." With futurity verbs ("promise," "decide"), the not-yet-realized action functions as a
direction/goal attendant on the promise or decision: "우리는 내일 가기로 약속했다" ("we promised
to go tomorrow"), "그는 담배를 안 피우기로 결심했다" ("he decided not to smoke," p.50).

#### 2.4.2 *umulo* (음으로)

*Um*, unlike *ki* (existence of states/events), nominalizes a predicate as an **abstract
proposition**. Combined with *ulo*, *umulo* marks the ground/basis of a judgment or assertion —
not a description of the event itself, but an attendant element the speaker's assertion rests on,
parallel to how materials/tools accompany a concrete making-process: "그는 열심히 했으므로
시험에 합격을 했다" ("as he worked hard, he passed the exam" — his working hard is the asserted
basis); "날씨가 좋지 않으므로, 농사가 잘 안되겠다" ("the weather being bad, we may not have good
crops," p.50-51).

#### 2.4.3 *kesulo* (것으로)

The dependent noun *kes* ("fact"/"reality") used with epistemic verbs can take either the object
marker *ul* or *ulo*, with a genuine certainty contrast: "나는 그가 온 것을 안다" (*kes-ul*, "I
know that he came" — the knowing is already on its target, i.e. certain) vs. "나는 그가 온
것으로 안다" (*kes-ulo*, "I assume that he came" — the knowing is directed toward but not
certainly on its target, p.51-52). Lee states this generalizes: *kes-ul* implies certain
knowledge, *kes-ulo* implies uncertain/inferred knowledge (믿는다 "believes" pairs with *kes-ulo*
the same way, p.52).

#### 2.4.4 *ulose* (으로서)

*Ulo* can combine with *se* as *ulose*, which the source glosses as emphasizing a **present (or
future) capacity** reading over the general accompaniment reading. Lee marks tool/means-type
*ulose* examples as degraded relative to *ulo*: "?나는 뻬스로써 학교에 갔다" ("I went to school by
bus," tool reading rejected with *-se*), "?나는 망치로써 그것을 만들었다" ("I made it with a
hammer," also rejected) — but "장교로써/?장교로서 되었다" ("he became an officer") requires *ulo*
over *ulose* when the capacity is a **resultant** state just coming into being, while "장교로서
그는 무능하다" ("as an officer, he is incompetent") uses *ulose* fine for an **already-held**
capacity (p.52-53). So *ulose* is reserved specifically for capacities already in force, not for
tool/means readings and not for a capacity's point of becoming.

### Chapter summary (p.53, source's own recap)

Lee's own closing summary: *eyse* provides a background for a situation; *ey* provides a
reference point for location or locomotion in a situation; *eykey* expresses a conscious
participant other than the subject in a situation; *ulo* expresses accompaniments or attendants.

---

## Korean — Established Vocabulary/Grammar: Keedong Lee, *A Korean Grammar on Semantic-Pragmatic Principles*, Chapter 3 "Particles"

**Source:** Keedong Lee, *A Korean Grammar on Semantic-Pragmatic Principles*, Hankook Munhwasa
(한국문화사), Seoul. No printed publication year was visible anywhere in the assigned page range
(pp. 56-106, i.e. scratch images page-028.png through page-054.png) — the book's copyright/front-matter
page evidently lies outside this chapter's pages, so Attested Era is left as "—" rather than guessed.
Covers Chapter 3 "Particles," full chapter: 3.0 Introduction, 3.1 cocha (조차), 3.2 lato (라도), 3.3 mace
(마저), 3.4 man (만), 3.5 nama (나마), 3.6 na (나), 3.7 to (도) [incl. 3.7.1 to+amwu, 3.7.2 to+acik], 3.8
ya (야). Printed pages 57-105 (confirmed via running headers; printed page 106 is a blank leaf followed
by the Chapter 4 "Auxiliary Verbs" table of contents, so Chapter 3's actual content ends at page 105,
one page short of the book's own TOC listing of "106" as the chapter boundary). Source has no text
layer; vision-read from rendered page-spread images.

**Coverage note:** This is the fourth Korean reference source for this language (after Integrated
Korean, College Korean, and the SNU Korean course materials, per the existing 46 `established/`
files), but those are all pedagogical textbooks that at most introduce the bare surface forms of 만
("only") and 도 ("also/even") at beginner level, and possibly 야 as a vocative/address-term particle —
never as a focus/delimiter particle with scalar semantics. **Nothing in this chapter was skipped as
redundant.** Every one of the eight delimiter/focus particles this chapter covers is treated here as
genuinely new content: the book's entire project is to draw fine-grained semantic-pragmatic contrasts
between near-synonyms that textbooks never distinguish (조차/라도/마저/만/나마/나/도 all gloss roughly as
"even"/"only"/"also" in English but differ sharply in Korean scalar-expectation pragmatics), and 나, 마저,
나마, 조차 in particular are advanced forms essentially absent from beginner/intermediate pedagogical
material. All grammar points and the minimal-pair argumentation are captured as new. No handwritten
marginalia was found anywhere in this page range — this is a clean, unmarked library-style scan; every
page was checked against the vision-reading guard and all content is typeset print.

Per the morphological-typology guide, Korean is agglutinative — compound/fused particle forms (ciman,
kiman, amwu-compounds) get a morpheme breakdown beneath their vocabulary row rather than being treated
as atomic.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| cocha (조차) | "even" (unexpected-side-of-scale focus particle) | particle | core | — | — | — | — | grammar_reference | n/a | verified | Positive-sentence choice on unexpected side of speaker's expectation scale; negative-sentence choice is on the expected side but the expectation still fails. Less specific than mace — doesn't require the extreme edge of the scale. p.57-59. |
| lato (라도) | "even; at least" (sole-remaining-second-choice delimiter) | particle | core | — | — | — | — | grammar_reference | n/a | verified | Used when exactly one second-best alternative is available (contrast na, used when 2+ second-bests exist); implies determination/urgency/desperation, and can carry a concessive reading ("even a blockhead could do this"). Also attaches to interrogatives as indefinite pronouns (nwukwulato "whoever"). p.60-65. |
| mace (마저) | "even" (extreme-edge-of-scale focus particle) | particle | core | — | — | — | — | grammar_reference | n/a | verified | Like cocha, sensitive to sentence polarity, but more specific: the referent is at the extreme edge of the expectation scale, not just somewhere on the unexpected side. Can mark subject or object (object marker ul/lul is dropped when mace attaches). p.66-69. |
| mace (마저, adverb) | "to the end; to the last, without leaving any" | adverb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | Distinct word class from the particle mace above but related in meaning; e.g. "ku ilul macehako kassta" = "he went after finishing the work (to the end)." p.68. |
| man (만) | "only" (restrictive delimiter) | particle | core | — | — | — | — | grammar_reference | n/a | verified | Used when the addressee has/tends to have/is believed to have a bigger expectation than the speaker's, and the speaker restricts it. Word-order note: precedes subject/object markers i/ka, ul/lul, but follows other postpositions (ey, eyse, ulo, etc.). p.69-75. |
| ciman (지만) | "but, although" (partial-acceptance connective) | particle/connective | core | — | — | — | — | grammar_reference | n/a | verified | Fused from suspective marker ci + man; used when the addressee accepts only part of a two-clause causally-linked proposition. Works with any connective (se, ko, etc.) underlying the base clause-link. p.74-75. |
| kiman (기만) | "only V-ing" (restrictive on nominalized predicate) | particle construction | core | — | — | — | — | grammar_reference | n/a | verified | Nominalizer ki + man; meaning is the ordinary restrictive man, but the construction can carry a sarcastic/understatement overtone (e.g. "i kwaca talkiman haney" ≈ "this cookie just keeps being sweet," i.e. "boy, is this sweet") — the sarcasm is derived from, not separate from, man's core meaning. p.72-73. |
| nama (나마) | "even if not ideal; at least" (settle-for-second-best delimiter) | particle | core | — | — | — | — | grammar_reference | n/a | verified | Marks an item that is not the speaker's true want but is accepted with contentment since nothing better is available — softer/less urgent than lato. Combines with postpositions ulo, ey, eyse. p.75-77. |
| na (나) | "or; some random second-best" (delimiter over multiple alternatives) | particle | core | — | — | — | — | grammar_reference | n/a | verified | Used when the choice is a second-best picked at random among 2+ possible alternatives (contrast lato, used when only one second-best exists). Also expresses numeric approximation (myech calwuna "about how many pencils," vs. exact myech calwu) and attaches to interrogatives as indefinite pronouns (nwukwuna "anybody," etisena "anywhere," muesina "anything"). Softens proposals/commands into more easily-refusable suggestions. p.77-83. |
| to (도) | "even, also, too" (bidirectional scalar-increment delimiter) | particle | core | — | — | — | — | grammar_reference | n/a | verified | Marks a referent as an increment relative to another point on a scale — direction (more vs. less) is speaker-relative and only one direction is licensed per exchange. Extends to cumulative addition when repeated across conjuncts (X-to Y-to Z-to). Used with amounts, degrees, and implicit scales (speed, price). p.83-98 (through 3.7.2). |
| mullon (물론) | "of course" (bidirectional to-increment adverb) | adverb | core | — | — | — | — | grammar_reference | n/a | verified | Co-occurs with to; signals that the preceding/compared item is taken for granted and marks increment in either direction (works whether the to-marked item is of greater or lesser value than the compared item). p.86-87. |
| khenyeng (커녕) | "not to speak of; let alone" (unidirectional negative-increment adverb) | adverb | core | — | — | — | — | grammar_reference | n/a | verified | Co-occurs with to; unlike mullon, only licensed when the to-marked item is clearly LESS valuable/desirable than the compared item (e.g. *papun khenyeng ttekto is ungrammatical because cake outranks rice; mullon is required there instead). p.86-87. |
| amwu (아무) | "any-" (indefinite base) | pronoun/prefix | core | — | — | — | — | grammar_reference | n/a | verified | Base form combining productively with to to form "no X at all" negative-polarity items; see compounds below. p.92-94. |
| amwuto (아무도) | "no one at all" | pronoun + particle | core | — | — | — | — | grammar_reference | n/a | verified | amwu (any) + to (even) → "not even anyone," i.e. "no one at all." p.92. |
| amwukesto (아무것도) | "nothing at all" | pronoun + particle | core | — | — | — | — | grammar_reference | n/a | verified | amwu (any) + kes (thing, nominalizer) + to (even) → "not even anything," i.e. "nothing at all." p.92-93. |
| amwuteyto (아무데도) | "nowhere at all" | pronoun + particle | core | — | — | — | — | grammar_reference | n/a | verified | amwu (any) + tey (place) + to (even) → "not even anywhere," i.e. "nowhere at all"; explicitly noted to include locations like "on top of the table," i.e. true universal negation over locations. p.92, 94. |
| amwulayto (아무래도) | "in no way at all" / "however one tries" | pronoun + particle | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | amwu (any) + lay (manner-ish element) + to (even) → "not even in any way," i.e. "in no way at all." Listed in the particle's combinatory paradigm (p.92) but not illustrated with its own worked example in this chapter — read with reasonable confidence but not independently cross-checked against a second occurrence. |
| acik (아직) | "still; yet" | adverb | core | — | — | — | — | grammar_reference | n/a | verified | Co-occurs with to to express that the subject has not reached an expected point in time (comparison with a reference point); also usable alone in negative sentences ("acik an-" = "not yet"). p.94-95. |
| ya (야) | "indeed; of course; naturally" (emphatic/contrastive-matter-of-fact particle) | particle | core | — | — | — | — | grammar_reference | n/a | verified | Marks an item the speaker emphasizes either because it conflicts with the addressee's assumption (contrastive reading) or because the speaker is reinforcing an idea already taken for granted (matter-of-fact reading) — same particle, context determines which reading surfaces. Attaches to subject, object, other sentence elements, and nominalized or bare predicates; also licenses a granting/concessive X-ya-elmana-Y-keyss-e "granting X, how much could Y really be" pattern, and extends from interpersonal to intrapersonal force-dynamics (overcoming one's own reluctance). p.95-105. |

**Morpheme breakdown (agglutinative compound forms):**

> **ciman (지만)** = ci (suspective marker — the speaker's believed/expected proposition) + man
> (restrictive "only") — literally "only [accepting] that it is the case that," yielding the
> contrastive "but" reading when the addressee accepts just part of a two-clause claim.

> **kiman (기만)** = ki (nominalizer) + man (restrictive "only") — turns a verb/adjective into a
> nominalized predicate before restricting it, e.g. talk- "be sweet" → talki "being sweet" → talkiman
> "only being sweet" (hence the sarcastic "that's ALL this cookie does — be sweet" overtone).

> **amwuto (아무도)** = amwu (any-) + to (even) — "not even anyone."

> **amwukesto (아무것도)** = amwu (any-) + kes (thing) + to (even) — "not even anything."

> **amwuteyto (아무데도)** = amwu (any-) + tey (place) + to (even) — "not even anywhere."

> **amwulayto (아무래도)** = amwu (any-) + lay (manner element) + to (even) — "not even in any way."

## Grammar points

### 3.0 Introduction

The chapter's stated purpose: particles are a word class used to express the speaker's attitudes
toward elements within the sentence. Lee frames the whole chapter as an examination of particle
meaning in exactly this sense — not case-marking function, but speaker-attitude/expectation
encoding. (p.57)

### 3.1 cocha (조차) — "even," unexpected side of the expectation scale

The speaker uses cocha when a referent is thought to lie on the unexpected side of a scale of
expectation. In a positive sentence, cocha marks something that happened contrary to the speaker's
expectation that it would NOT happen (e.g. "Changswucocha wassta" — "Even Changswu, who wasn't
expected to come, came"). Lee diagrams this explicitly as a two-point scale with an "unexpected" and
an "expected" pole, and shows that several referents (a person, cheese, snow) can be plotted on it
relative to a contrasting referent that behaved as expected.

Crucially, cocha reverses in negative sentences: the expectation flips, so cocha in a negative
sentence marks a referent that WAS expected to happen/be true, but the expectation failed — "Boy,
not even Changswu (who was expected to come) came." The particle's core meaning (expectation-scale
placement, contrary-to-expectation outcome) stays constant; only the direction flips with polarity.
(pp.57-59)

### 3.2 lato (라도) — "even, at least," the sole remaining second-choice

lato marks a choice that is not the speaker's primary choice but is understood to be the only one
left available given the circumstances. Lee builds this from a conversational scenario: a speaker
wants a bus or subway, neither is available, so he settles for a taxi — "kulem, taksilato thako
kaca" ("then let's go by taxi at least"). The "last available choice" framing produces implications
of determination, urgency, or desperation.

A key contrast with na (3.6): when more than one second-best choice is genuinely available, lato is
inappropriate and na must be used instead (demonstrated with a bar scenario: when only soju is left,
"socwulato" is fine, but when both soju and cengcong remain, only "socwuna" works, not *socwulato).

lato vs. the plain object marker ul/lul: using the object marker simply names the item; using ilato
implies the item is not the addressee's primary choice but the only one available given a
constraint (e.g. limited money), producing a humility/modesty implicature on the speaker's part.

lato is also usable in questions, where it loses the usual presupposition of the referent's
existence that a plain question would carry (contrast "musun cohun ili issupnikka?", which
presupposes something good exists, with "...ililato issupnikka?", which doesn't) — signaling the
speaker's detachment/low investment in the matter. lato attaches productively to interrogative
words to form indefinite pronouns meaning "whoever/whatever is available regardless of
qualification" (nwukwulato, etilato), and can carry a concessive meaning: "i ilun papolato hal swu
issta" ("Even a blockhead can do this") — the person capable of the task is the second-best point on
an intelligence scale, which is how the concessive flavor arises. The expectation scale itself can be
reversed depending on context (demonstrated with a "genius cannot solve this" example where lato still
marks the second-best/edge point, just on the opposite end). (pp.60-67)

### 3.3 mace (마저) — "even," the extreme edge of the scale

mace shares cocha's sensitivity to sentence polarity (speaker's choice on the unexpected side in
positive sentences, expected side in negative sentences) but is more specific: mace's referent sits
at the EXTREME EDGE of the expectation scale, not merely somewhere on the unexpected side. Lee
contrasts a minimal pair directly: "Changswucocha kassta" merely places Changswu on the unexpected
side, while "Changswumace kassta" specifically marks Changswu as the LAST person expected to go (the
extreme edge) — and he went anyway. The same sharpening of specificity holds in negative sentences
("Changswumace oci anhassta" marks Changswu as the FIRST person expected to come, among those
who, in the end, failed to).

mace extends to objects (dropping the object marker, e.g. "kunun cipmace phalapeliessta" — "he sold
even his house [the last thing expected to go]"). A related but distinct adverb mace ("to the end,
without leaving any") shares the root but belongs to a different word class and simply intensifies
completeness of an action rather than marking scalar extremity of a referent. (pp.66-69)

### 3.4 man (만) — restrictive "only"

man is used when the addressee has, tends to have, or is believed to have an expectation that is
larger than the speaker's actual claim, and the speaker uses man to restrict/narrow that expectation
down. Lee illustrates with a question assuming study of two languages, answered with a restriction to
one: "aniyo, hankukeman kongpuhapnita" ("No, I'm studying only Korean"). This is formalized with a
nested-circle diagram: an outer circle (addressee's larger expectation) and an inner circle (the
speaker's narrower actual claim), with man marking the gap between them.

Positionally, man precedes the subject/object markers i/ka and ul/lul but follows other postpositions
(ey, eyse, ulo, etc.) — e.g. "yekinun haksayngtulman tulekal swu issupnita" (subject) vs.
"...haksayngtulmanun..." (man + topic marker nun stacking). man also attaches after the nominalizer
ki (kiman), keeping its ordinary restrictive meaning even on a nominalized predicate, though this
construction frequently carries a sarcastic/understatement overtone (e.g. "i yenphil cohkiman haney"
≈ "well, if this pencil is good for nothing else, at least it's good," read ironically as "boy, this
pencil really is good").

man also combines with the suspective marker ci to form ciman, used when the addressee accepts only
part of a causally-linked two-clause proposition the speaker has offered — regardless of which
connective (se, ko, etc.) links the underlying clauses, ciman signals a partial-acceptance "but"
relation. Finally, man combines with ya (3.8) to mark a unique/sole necessary condition: X-ya-man,
e.g. "i yakul mekeyaman cal swu issta" ("You can sleep only if/when you take this medicine"). (pp.69-75)

### 3.5 nama (나마) — settling for a less-than-ideal second-best, with contentment

nama marks an item that is not exactly what the speaker wants but that the speaker accepts with
satisfaction because no better alternative is available — e.g. "pwuchaynama hana issessumyen
cohkeyssta" ("I'd be happy if there were even just a hand-fan [not ideal, but better than nothing]").
Lee is explicit that nama's referents are not rejected outright despite falling short of the
speaker's true want; the attitude is mild contentment rather than lato's urgency/desperation — the
chapter frames this as the key pragmatic contrast between the two "at least" particles. nama
combines with postpositions ulo, ey, and eyse. (pp.75-77)

### 3.6 na (나) — a randomly-chosen second-best among several alternatives

na marks a choice that is a second-best selected at random from among two or more possible
alternatives — the key structural contrast with lato (which requires exactly one remaining
second-choice). Lee's diagram: a set of X's (plural second-best choices) with na attaching to mark
an arbitrary pick from that set, presupposing a contrast between a best choice and the undifferentiated
collective of second-bests.

This "random pick among several" semantics extends naturally to numeric approximation: "yenphilul
myech calwuna sasikeysseyo?" asks for an approximate quantity of pencils (contrast the exact-quantity
question without na). The reference point for what counts as "more/less than expected" can be either
speaker's or addressee's expectation, and in some contexts the "more than expected" reading shifts to
"more than necessary" (e.g. "ku iley yelmyengina puwtheiss-ta" — "ten people, more than needed, are
working on it").

na also attaches to interrogative-derived indefinite pronouns (nwukwuna "anybody," etisena
"anywhere," muesina "anything") — compatible because both na and the indefinite pronoun carry
indeterminacy of reference. Pragmatically, na softens a proposal or command, since marking a choice
as merely "one of several second-bests" lets the addressee refuse more politely/easily (contrast
"cha hancan hapsita" with the milder "chana hancan hapsita"). (pp.77-83)

### 3.7 to (도) — bidirectional scalar increment, extending to cumulative addition

to marks a referent as an increment relative to another point on a scale, in either the positive
(more) or negative (less) direction — which direction counts as "increment" is relative to the
speaker's own goal. Lee's worked example: in a price negotiation, the seller treats higher prices as
the increment direction (wanting more), while the buyer treats lower prices as the increment
direction (wanting to pay less); each speaker's own to-marked amount only makes sense relative to
their own goal, and a single exchange cannot mix two different directions from two different
speakers.

Beyond money, to applies to any gradable/numeric scale (temperature in degrees, speed, price, size)
and to implicit scales without inherent numeric values. The increment idea generalizes to addition:
repeating to across a list of conjuncts ("nanun oto sako sakwato sako chaykto sassta" — "I bought
clothes, and apples, and books [too]") marks cumulative addition, and this addition can be
distributed across different speakers successively adding items to a running total in a
conversation. to-marking is also sensitive to a presupposed sequence toward a goal: asking whether
one has "finished" (a later point) presupposes a start; answering with X-to ("I haven't even
started yet") places the subject below even the starting point on that sequence, generalizing to
"hasn't even gotten as far as washing/eating/dressing" scenarios ordered toward a "going out" goal.

Two adverbs specify to's direction: mullon ("of course") works for increment in either direction —
it signals the compared item is taken for granted, regardless of whether the to-marked item is
objectively better or worse. khenyeng ("not to speak of, let alone") works only for the negative
direction — it is only grammatical when the to-marked item is clearly of LESSER value than what it's
compared to (Lee gives an explicit ungrammaticality: *"papun khenyeng ttekto cwukeyssta" fails
because rice cake outranks rice in value, so khenyeng cannot apply there; mullon is required
instead). (pp.83-91, continuing through the subsections below)

#### 3.7.1 to and amwu (도와 아무) — universal negative-polarity "no X at all"

to combines productively with the indefinite base amwu ("any") to build strong negative-polarity
items: amwuto "no one at all," amwukesto "nothing at all," amwuteyto "nowhere at all," amwulayto "in
no way at all." Lee illustrates the reference-point-relative reading of amwukesto with a conversation
about cigarette brands: when neither of two options (Arirang, then the pricier Sol) is available, the
response "amwukesto epseyo" denotes that nothing is available in EITHER direction (cheaper or more
expensive) relative to what was asked — i.e., amwu-to compounds inherit to's reference-point/direction
machinery, they aren't simply flat universal negators. amwuteyto is explicitly glossed as including
even very local/contained locations (e.g. "on top of the table"), underscoring its true
universal-negation-over-locations force. (pp.92-94)

#### 3.7.2 to and acik (도와 아직) — "still," with an implied comparison point

The adverb acik ("still") commonly co-occurs with to to imply comparison against a second,
later/expected point in time — e.g. "kunun acikto cako issta" ("he's still sleeping") implies a
reference point (when he was supposed to get up) against which the ongoing state is measured as an
increment (he's past that point and still asleep). Lee diagrams this as a timeline with a reference
point X (e.g. 7:00) and a presupposed-but-unreached point Y (e.g. 8:00), with Y-to marking the
continuation past Y. acik can also occur without to in purely negative sentences ("acik an-" = "not
yet"), and aciktо in a negative sentence extends the same comparison machinery to show the subject
hasn't even reached a point beyond the reference (e.g. "hasn't even started breakfast yet," read
against an implied later deadline). (pp.94-95)

### 3.8 ya (야) — emphatic particle: contrastive-with-addressee or matter-of-fact-reinforcing

ya marks a sentence element the speaker wants to emphasize, and Lee identifies two related readings
that fall out of the same underlying mechanism depending on context: (1) a CONTRASTIVE reading, used
when the speaker's idea differs from the addressee's (the speaker pushes back against or corrects an
assumption); and (2) a MATTER-OF-FACT reading, used when the speaker is reinforcing something the
addressee already takes for granted, underscoring it as obviously/naturally true (e.g. "maykcwuya
mullon masici" — "[of course] he drinks beer, naturally" — reinforcing an already-expected fact
rather than contesting one).

ya attaches to subjects and objects alike, and to other sentence elements including nominalized
predicates (verb/adjective + nominalizer, then ya) and bare/unnominalized forms directly (e.g. "i
sikye cal kaney" vs. the ya-marked "kakiya cal kaci. kulena moyangi ancoha" — "Of course it runs
well. But the style isn't good," conceding one point while pivoting to another). Parallel to na
(3.6), ya can mark a number as a confirmed/certain figure in explicit contrast to a prior vague
estimate (e.g. "seysikaniya kellici" — "of course it'll take three hours," correcting an earlier
approximate "about three hours").

ya also appears in a granting/concessive construction, X-ya elmana Y-keyss-e ("granting X, how much
could Y really be?"), used to accept the addressee's premise with explicit reservation and then
rhetorically undercut it (e.g. "ppallaya elmana ppalukeyss-e?" — "Granting that it's fast, how fast
can it really be?", expressing skepticism about the addressee's claim). Lee contrasts ya directly
with the connective myen in near-identical frames: myen is used when there's no conflict between the
speakers' views, while ya is reserved specifically for when the speaker's proposition conflicts with
the addressee's.

ya figures prominently in leave-taking exchanges: "icey kuman kayakeyssupnita" ("Now I really must
go") ordinarily presupposes the addressee wants the speaker to stay and will respond accordingly —
but when that presupposition fails to hold (the addressee actually wants the speaker to leave), the
addressee can sneeringly exploit the mismatch: "kaci. nwuka moskalako hayssna?" ("Go on then — who
said you couldn't?"), rejecting the leave-taking's built-in assumption.

Finally, ya's opposition semantics extend from the interpersonal to the INTRAPERSONAL: a single
speaker can use ya to show an internal conflict between reluctance and obligation within themselves,
e.g. "nanun kaya hay" ("I have to go," glossable as "[despite not wanting to,] I have to go") —
expanded as "kaki silhciman aitul ttaymuney nanun kaya hay" ("I don't want to go, but because of the
children, I have to"), which makes the two opposing internal forces explicit. The same mechanism
covers overcoming reluctance against eating despite poor appetite, studying despite not wanting to,
and overriding personal preference for the sake of social/religious/moral obligations (e.g. helping
the poor despite not wanting to). (pp.95-105)

---

## Korean — Established Vocabulary/Grammar: Chapter 4 "Auxiliary Verbs," §4.1 cita – §4.3 hata

**Source:** Keedong Lee, *A Korean Grammar on Semantic-Pragmatic Principles*, Hankook Munhwasa
(한국문화사), Seoul (publication year not visible anywhere in this page range — no printed year
appears on the Chapter 4 table-of-contents page or any of the chapter-opening pages read). Printed
pages 109–160 (§4.1 cita, §4.2 cwuta, §4.3 hata, stopping immediately before §4.4 issta begins).
Source rendered as vision-only PNG page-spread images (`page-054.png` through `page-081.png`),
two printed pages per image; no text layer, no decodable font cipher.

**Coverage note.** This is a theoretical/pragmatics-focused monograph, not a pedagogical textbook,
and the orchestrating agent's dispatch identified that Korean already has 46 `established/` files
drawn mostly from pedagogical textbooks that cover **only the bare surface forms** of -아/어지다
("become"), -아/어 주다 ("do for someone," benefactive), and 하다 as a light verb (typically one or
two beginner-level example sentences each). Per that guidance:

- **Skipped as redundant:** the bare "cita/-ecita = become," "cwuta/-e cwuta = do for someone," and
  "hata = do, light-verb-forming hata" glosses themselves are not re-tabulated as if new — those
  core senses are already covered elsewhere (e.g. `035_integrated_korean_beginning_1.md`,
  `044_college_korean_part1.md`, and others). The basic Korean honorific-verb-pair list (이다/계시다,
  먹다/잡수시다, 자다/주무시다, 묻다/여쭈다, 보다/뵈다, 주다/드리다) is also likely already captured in
  `031_korean_honorifics_and_politeness.md` and is not re-extracted as new vocabulary here — only
  the book's own pragmatic *selection rule* for when 드리다 (vs. 주다) is required is kept, since that
  conditioning rule is not typically spelled out in a basic honorific table.
- **Kept as new (the bulk of this file):** cita's force-dynamics (agonist/antagonist) semantic
  analysis as a main verb and as four distinct auxiliary-verb subtypes (§4.1.1–4.1.4), its
  comparison against the morphological /Ci/-passive system (§4.1.5, with the full passive-verb
  paradigm table); cwuta's idiosyncratic affectedness/controllability constraints, its valence-
  altering and meaning-shifting compound forms, its directive-politeness function, and the full
  honorific-selection logic including the little-documented contrastive form 다오/tao (§4.2); and
  virtually all of §4.3 hata, which textbooks essentially never treat systematically — concrete-noun
  incorporation, the dependent-noun -질/cil agentive/instrumental nominalizer (including its
  pejorative-connotation agentive use), deverbal-noun formation, onomatopoeia + hata, Sino-Korean
  verb/adjective formation, feeling-adjective pairs, the emphatic construction, the causative
  construction, and hata with mental-activity connectives (§4.3.1–4.3.9).

**Vision-reading guard.** The scan is a clean library copy and the overwhelming majority of this
range is unambiguous typeset print, with hangul and explicit Yale-style romanization printed
side-by-side for nearly every lexical item — this pairing itself serves as an internal cross-check,
so most entries below are marked `verified`. **One instance of apparent handwritten marginal
annotation (orange/reddish ink, cursive, in the right-hand margin near the bottom of printed page
127) was found and is excluded entirely** — it sits in the margin outside the printed text block,
is inconsistent with the page's typeface, and was not transcribed or treated as source content, per
the extraction spec's vision-reading guard. No other marginalia was observed in this range.

**Source-internal note (not a reading-confidence issue):** §4.3.3 (p.143) states deverbal nouns are
"formed by the following three suffixes" but then prints a list of **four** — `-ki`, `-um`, `-i`,
`-key`. This is a discrepancy in the source's own printed text (clearly typeset, read with
confidence), not a vision-reading error. The visible portion of §4.3.3 within this page range goes
on to discuss only `-ki`, `-um`, and `-i` individually; `-key` is listed but not elaborated before
the section transitions into §4.3.4 (onomatopoeia). Flagged here for the record.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 지다 cita | (main verb) to fall/set/go out/lose — prototypical physical process of a steady state giving way to a change of state | verb | core | — | — | — | — | grammar_reference | n/a | verified | Anchor term for the book's force-dynamics analysis; bare auxiliary "-어지다 = become" sense already covered pedagogically elsewhere, kept here only as the term this section's semantic analysis is built on. |
| 꽃이 지다 kkochi cita | the flower fell/fell off the stem | example phrase | core | — | — | — | — | grammar_reference | n/a | verified | p.109; prototypical cita-process: agonist (flower) has a tendency to fall, antagonist (stem) holds it back — steady state → change of state when the restraining force is removed/weakens. |
| 해가 지다 hayka cita | the sun set | example phrase | core | — | — | — | — | grammar_reference | n/a | verified | p.109; cita extended to astronomical motion. |
| 싸움에 지다 ssawumey cita | to be defeated in a fight | example phrase | core | — | — | — | — | grammar_reference | n/a | verified | p.109; metaphorical extension of cita to a non-physical "contest of forces" (argument/quarrel), the weaker force "goes down." |
| 불이 지다 pwuli cita | the fire went out | example phrase | core | — | — | — | — | grammar_reference | n/a | verified | p.109; change-of-state extension: visible→invisible / continuity→discontinuity. |
| malk-ta → malka cinta | clear (adj.) → becomes clear | adjective + inchoative auxiliary | core | — | — | — | — | grammar_reference | n/a | verified | §4.1.2 adjective-e cita; stative-adjective + cita = change toward the adjective's state. |
| tattushata → tattushay cinta | warm (adj.) → becomes warm | adjective + inchoative auxiliary | core | — | — | — | — | grammar_reference | n/a | verified | §4.1.2; p.112. |
| hulita → hulie cinta | cloudy (adj.) → becomes cloudy | adjective + inchoative auxiliary | core | — | — | — | — | grammar_reference | n/a | verified | §4.1.2; p.112. |
| chakapta → chakawe cinta | cold (adj., of hands) → becomes cold | adjective + inchoative auxiliary | core | — | — | — | — | grammar_reference | n/a | verified | §4.1.2; p.112. |
| casta → caciessta | to sleep → managed to sleep (fit into a crowded space) | verb + potentiality auxiliary | core | — | — | — | — | grammar_reference | n/a | verified | §4.1.3 verb-e cita with intransitive verbs; denotes potentiality tied to the speaker's prior (defeated) expectation. p.114. |
| kassta → kaciessta | went → managed to go (cover a distance in time) | verb + potentiality auxiliary | core | — | — | — | — | grammar_reference | n/a | verified | §4.1.3; p.114–115, distance-vs-time force-dynamic example. |
| cinakassta → cinaka ciessta | crossed (over ice) → managed to cross | verb + potentiality auxiliary | core | — | — | — | — | grammar_reference | n/a | verified | §4.1.3; p.115, ice-strength-vs-truck-weight example. |
| makassta → *makaciessta (ungrammatical) / kangmwuli makaciessta (grammatical) | blocked (transitive) vs. became blocked (intransitive-subject reading only) | verb + cita-compound | core | — | — | — | — | grammar_reference | n/a | verified | §4.1.4 transitive verb-e cita; object of the transitive verb must become the subject of the cita-compound — ungrammatical if the original subject/agent stays as subject. p.116. |
| cis-ta → cieciessta | to build → managed to get built | verb + cita-compound | core | — | — | — | — | grammar_reference | n/a | verified | §4.1.4; p.116–117, same valence-flip pattern as makassta; cipi Changswueykey ciecessta 'the house managed to get built for Changswu' shows the agent cannot be re-added except as a forced dative/beneficiary reading, never a true agent. |
| cie nayessta (nayta-compound) | managed to build (agent's own capability was the opposing force) | verb + nayta-compound | core | — | — | — | — | grammar_reference | n/a | verified | p.117; contrasted with the plain cita-compound — when the agent's own ability is one of the two opposing forces (rather than an external force), the auxiliary nayta is used instead of cita. |
| ppop-ta / ppop-hi-ta | to pick/pull out / (its morphological passive) | verb pair | core | — | — | — | — | grammar_reference | n/a | verified | §4.1.5 morphological passive paradigm (/Ci/ → -hi- allomorph), p.120–121; subject of the passive corresponds to the object of the active transitive verb, paralleling the cita-compound's valence flip but syntactically distinct from it (see ppophiessta vs. ppopaciessta note below). |
| kulk-ta / kulk-hi-ta | to scratch / passive | verb pair | core | — | — | — | — | grammar_reference | n/a | verified | §4.1.5, -hi- allomorph, p.120. |
| ccik-ta / ccik-hi-ta | to imprint / passive | verb pair | core | — | — | — | — | grammar_reference | n/a | verified | §4.1.5, -hi- allomorph, p.120. |
| mak-ta / mak-hi-ta | to block / passive | verb pair | core | — | — | — | — | grammar_reference | n/a | verified | §4.1.5, -hi- allomorph, p.120. |
| cip-ta / cip-hi-ta | to pick up / passive | verb pair | core | — | — | — | — | grammar_reference | n/a | verified | §4.1.5, -hi- allomorph, p.120. |
| pak-ta / pak-hi-ta | to drive in / passive | verb pair | core | — | — | — | — | grammar_reference | n/a | verified | §4.1.5, -hi- allomorph, p.120. |
| ilk-ta / ilk-hi-ta | to read / passive | verb pair | core | — | — | — | — | grammar_reference | n/a | verified | §4.1.5, -hi- allomorph, p.120. |
| ttwulh-ta / ttwulh-li-ta | to drill / passive | verb pair | core | — | — | — | — | grammar_reference | n/a | verified | §4.1.5, -li- allomorph, p.120. |
| kkal-ta / kkal-li-ta | to spread / passive | verb pair | core | — | — | — | — | grammar_reference | n/a | verified | §4.1.5, -li- allomorph, p.120. |
| kel-ta / kel-li-ta | to hang / passive | verb pair | core | — | — | — | — | grammar_reference | n/a | verified | §4.1.5, -li- allomorph, p.120. |
| mil-ta / mil-li-ta | to push / passive | verb pair | core | — | — | — | — | grammar_reference | n/a | verified | §4.1.5, -li- allomorph, p.120. |
| yel-ta / yel-li-ta | to open / passive | verb pair | core | — | — | — | — | grammar_reference | n/a | verified | §4.1.5, -li- allomorph, p.120. |
| phwul-ta / phul-li-ta | to untie / passive | verb pair | core | — | — | — | — | grammar_reference | n/a | verified | §4.1.5, -li- allomorph, p.121. |
| tut-ta / tul-li-ta | to hear / passive ("to be heard") | verb pair | core | — | — | — | — | grammar_reference | n/a | verified | §4.1.5, -li- allomorph, p.121. |
| po-ta / po-i-ta | to see / passive ("to be seen") | verb pair | core | — | — | — | — | grammar_reference | n/a | verified | §4.1.5, -i- allomorph, p.121. |
| ssu-ta / ssu-hi-ta | to write / passive | verb pair | core | — | — | — | — | grammar_reference | n/a | verified | §4.1.5, -hi- allomorph, p.121. |
| kam-ta / kam-ki-ta | to wind / passive | verb pair | core | — | — | — | — | grammar_reference | n/a | verified | §4.1.5, -ki- allomorph, p.121. |
| ccic-ta / ccic-ki-ta | to tear / passive | verb pair | core | — | — | — | — | grammar_reference | n/a | verified | §4.1.5, -ki- allomorph, p.121. |
| nalssika phulliessta (*phuleciessta ungrammatical) | the weather became warm (morphological passive only, cita-compound blocked) | example phrase | core | — | — | — | — | grammar_reference | n/a | verified | §4.1.5, p.122; natural/accidental processes with no human exertion implied take the morphological passive, not the cita-compound. |
| wuni yelliessta (*yeleciessta ungrammatical) | fortune turned in his favor (morphological passive only) | example phrase | core | — | — | — | — | grammar_reference | n/a | verified | §4.1.5, p.122; same constraint as above. |
| dative/instrument postposition 으로 ulo vs. 에 ey (with cita-compounds) | "actively/dynamically wielded instrument" vs. "fixed-in-place instrument" | postposition contrast | core | — | — | — | — | grammar_reference | n/a | verified | §4.1.3, p.118–119; 송곳으로 뚫었다 songkosulo ttwulhessta (drilled WITH a gimlet, dynamically wielded) vs. 송곳에 뚫었다 songkosey ttwulhessta (drilled AT a fixed gimlet) — the ulo-marked instrument is understood as under the agent's direct dynamic control. |
| 다오 tao | (contrastive directive) "give (it) to me" | auxiliary/defective verb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | §4.2, p.133; book notes its own base form is unclear, possibly tul-ta. Used specifically when the beneficiary is the speaker AND the agent is socially inferior to the speaker — a distinct contrastive counterpart to 드리다/tulita, not typically covered in basic honorific tables. e.g. 보여 다오 poye tao 'show me', 다려 다오 talye tao 'please iron (it) for me'. |
| 가르치다 kaluchita | to teach | verb | core | — | — | — | — | grammar_reference | n/a | verified | §4.2, p.126–127; idiosyncratic affectedness verb — when compounded with cwuta (가르쳐 주다), additionally entails the recipient actually learned, not merely that teaching occurred. |
| 알리다 alukhita | to inform | verb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | §4.2, p.126; same idiosyncratic-affectedness class as kaluchita. |
| 일깨우다 ilkkaywuta | to awaken (someone, to an idea) | verb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | §4.2, p.126; same idiosyncratic-affectedness class. |
| 빌리다 pillita → 빌려 주다 pillye cwuta | to borrow → to lend (meaning shift, not mere benefaction) | verb + cwuta-compound | core | — | — | — | — | grammar_reference | n/a | verified | §4.2, p.129; one of the cases where the cwuta-compound's meaning diverges from its simple counterpart rather than just adding "for someone." |
| 들리다 tullita / 들려 주다 tullye cwuta | passive "to be heard" vs. causative "to let (someone) hear" | verb + cwuta-compound | core | — | — | — | — | grammar_reference | n/a | verified | §4.2, p.129; tullita/poita are one-argument passives of tutta/pota, while their cwuta-counterparts are two-argument causatives — a valence-restoring, not just benefactive, function of cwuta here. |
| 드리다 tulita (superior-beneficiary selection rule) | honorific "give"/benefactive, obligatory when the beneficiary (not the subject) is socially superior to the speaker | grammar rule | formal | — | — | — | — | grammar_reference | n/a | verified | §4.2, p.131–132; the specific conditioning rule — tulita is selected based on the beneficiary's status relative to the speaker, independent of the subject's own status — is the book's distinctive contribution beyond the bare honorific-pair list. |
| cil (-질) | dependent nominal suffix: "the typical activity involving an agent or tool," never used alone | dependent noun / derivational suffix | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.2, p.140–143; combines with agent nouns (often pejorative connotation) or tool/instrument nouns (neutral connotation) to form atemporal activity-nouns, which then take hata for a positive temporal profile. |
| 도둑 totwuk → 도둑질 totwukcil | thief → stealing | noun → -cil derived noun | colloquial | — | — | — | — | grammar_reference | n/a | verified | §4.3.2, p.141; agentive -cil, carries unfavorable/derogatory connotation per the source's own note. |
| 순사 swunsa → 순사질 swunsacil | policeman → "working as a policeman" | noun → -cil derived noun | colloquial | — | — | — | — | grammar_reference | n/a | verified | §4.3.2, p.141; derogatory agentive -cil. |
| 선생 sensayng → 선생질 sensayngcil | teacher → "teaching" (derogatory) | noun → -cil derived noun | colloquial | — | — | — | — | grammar_reference | n/a | verified | §4.3.2, p.141; derogatory agentive -cil — notable since "teacher" is an otherwise-respected role; the -cil suffix itself carries the derogation. |
| 면장 myencang → 면장질 myencangcil | mayor/township head → "administrating" (derogatory) | noun → -cil derived noun | colloquial | — | — | — | — | grammar_reference | n/a | verified | §4.3.2, p.141; derogatory agentive -cil. |
| 칼 khal → 칼질 khalcil | knife → cutting (with a knife) | noun → -cil derived noun | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.2, p.142; instrumental -cil, no pejorative connotation (contrast with agentive -cil above). |
| 삽 sap → 삽질 sapcil | shovel → shoveling | noun → -cil derived noun | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.2, p.142; instrumental -cil. |
| 망치 mangchi → 망치질 mangchicil | hammer → hammering | noun → -cil derived noun | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.2, p.142; instrumental -cil. |
| 가위 kawi → 가위질 kawicil | scissors → cutting with scissors | noun → -cil derived noun | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.2, p.142; instrumental -cil. |
| 바늘 panul → 바늘질 panulcil | needle → needling/sewing | noun → -cil derived noun | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.2, p.142; instrumental -cil. |
| 젓가락 ceskalak → 젓가락질 ceskalakcil | chopstick → using chopsticks | noun → -cil derived noun | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.2, p.142; instrumental -cil. |
| 손가락 sonkalak → 손가락질 sonkalakcil | finger → "fingering" (pointing at, as a gesture) | noun → -cil derived noun | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.2, p.142; instrumental -cil; glossed only as 'finger' in the table but the compound sonkalakcil is a well-known idiom for accusatory finger-pointing — worth a native-speaker check later for whether this sense carries any pejorative shading despite the book's general "instrumental = neutral" claim. |
| 솔 sol → 솔질 solcil | brush → brushing | noun → -cil derived noun | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.2, p.142; instrumental -cil. |
| 비 pi → 비질 picil | broom → sweeping | noun → -cil derived noun | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.2, p.142; instrumental -cil. |
| 걸레 kelley → 걸레질 kelleycil | mop/rag → mopping | noun → -cil derived noun | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.2, p.142; instrumental -cil. |
| 부채 pwuchay → 부채질 pwuchaycil | fan → fanning | noun → -cil derived noun | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.2, p.142; instrumental -cil. |
| 다리미 talimi → 다리미질 talimicil | iron → ironing | noun → -cil derived noun | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.2, p.142; instrumental -cil. |
| el-ta → elum | to freeze → ice (concrete noun) | verb → -um deverbal noun | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.3, p.143; -um not fully productive/predictable — this instance yields a concrete object, contrast ssaum below (abstract process). |
| ssau-ta → ssaum | to fight → fighting (abstract process noun) | verb → -um deverbal noun | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.3, p.143; abstract-process reading of -um, usable with hata (쌈/싸움을 하다). |
| 싸움 ssaum / 말다툼 maltathwum + hata | fighting / quarreling (did some fighting/quarreling) | deverbal noun + hata | colloquial | — | — | — | — | grammar_reference | n/a | verified | §4.3.3, p.144; deverbal nouns contain their source verb's relationship but lack positive temporal profile until combined with hata. |
| 달맞이 talmaci / 윷놀이 yuchnoli + hata | viewing the first full moon (traditional custom) / playing yut (traditional board game) | deverbal noun + hata | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.3, p.144; culturally specific deverbal-noun + hata examples. |
| 쿵쿵 khwungkhwung | thumping noise | onomatopoeia | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.4, p.144; sound-class onomatopoeia, combines with hata (쿵쿵 하다) to denote a sound occurring in time. |
| 바스락바스락 pasulakpasulak | rustling sound | onomatopoeia | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.4, p.144. |
| 드문드문 tumuntumun | sparsely, thinly | onomatopoeia (shape class) | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.4, p.144. |
| 촘촘 chomchom | dense, compact | onomatopoeia (shape class) | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.4, p.145. |
| 따끈따끈 ttakkunttakkun | warm | onomatopoeia (feeling class) | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.4, p.145. |
| 미지근 micikun | lukewarm | onomatopoeia (feeling class) | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.4, p.145. |
| 따끔따끔 ttakumttakum | prickly | onomatopoeia (sensation class) | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.4, p.145. |
| 간질간질 kancilkancil | ticklish | onomatopoeia (sensation class) | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.4, p.145. |
| 행복 hayngpok → 행복하다 hayngpok-hata | happiness → to be happy | Sino-Korean noun → imperfective hata-verb | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.5, p.147; abstract-state Sino-Korean group — derived verb is imperfective, incompatible with present-tense marker -nun (*hayngpok-ha-nun-ta ungrammatical). |
| 건강 kenkang → 건강하다 kenkang-hata | health → to be healthy | Sino-Korean noun → imperfective hata-verb | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.5, p.147. |
| 친절 chincel → 친절하다 chincel-hata | kindness → to be kind | Sino-Korean noun → imperfective hata-verb | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.5, p.147. |
| 침착 chimchak → 침착하다 chimchak-hata | calmness → to be calm | Sino-Korean noun → imperfective hata-verb | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.5, p.147. |
| 관대 kwantay → 관대하다 kwantay-hata | generosity → to be generous | Sino-Korean noun → imperfective hata-verb | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.5, p.147. |
| 광범 kwangpem → 광범하다 kwangpem-hata | expanse → to be expansive | Sino-Korean noun → imperfective hata-verb | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.5, p.147. |
| 명백 myengpayk → 명백하다 myengpayk-hata | obviousness → to be obvious | Sino-Korean noun → imperfective hata-verb | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.5, p.147. |
| 동일 tongil → 동일하다 tongil-hata | same(ness) → to be uniform | Sino-Korean noun → imperfective hata-verb | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.5, p.147. |
| 공헌 konghen → 공헌을 하다/공헌하다 konghen-hata | contribution → to contribute | Sino-Korean noun → perfective hata-verb | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.5, p.148–149; abstract-process Sino-Korean group — derived verb is perfective; object marker optional, and its presence/absence changes adverb placement and syntax (object marker present = true transitive object; absent = noun-incorporated single verb). |
| 과로 kwalo → 과로하다 kwalo-hata | overwork → to overwork | Sino-Korean noun → perfective hata-verb | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.5, p.148. |
| 고민 komin → 고민하다 komin-hata | worry → to worry | Sino-Korean noun → perfective hata-verb | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.5, p.148. |
| 연구 yenkwu → 연구하다 yenkwu-hata | research → to research | Sino-Korean noun → perfective hata-verb | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.5, p.149–150; can take a true object with object marker retained (연구를 하다/물리학을 연구하다). |
| 조사 cosa → 조사하다 cosa-hata | investigation → to investigate | Sino-Korean noun → perfective hata-verb | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.5, p.150–151. |
| 침략 chimlyak → 침략하다 chimlyak-hata | attack/invasion → to attack | Sino-Korean noun → perfective hata-verb | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.5, p.150. |
| 관리 kwanli → 관리하다 kwanli-hata | control/management → to control | Sino-Korean noun → perfective hata-verb | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.5, p.150. |
| 구금 kwukum → 구금하다 kwukum-hata | confinement → to confine | Sino-Korean noun → perfective hata-verb | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.5, p.150. |
| 기쁘다 kipputa / 기뻐하다 kippehata | glad (1st-person adj.) / to feel glad (transitive, any person) | adjective + derived hata-verb pair | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.6, p.152–153; feeling-adjective pattern — the bare adjective is one-argument, restricted to describing the speaker's own (1st-person) feeling; the hata-derived verb is two-argument, usable of anyone's feelings. |
| 즐겁다 culkepta / 즐거워하다 culkewehata | enjoyable / to be fond of | adjective + derived hata-verb pair | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.6, p.153. |
| 예쁘다 yepputa / 예뻐하다 yeppehata | pretty / to find (someone) pretty, dote on | adjective + derived hata-verb pair | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.6, p.153. |
| 싫다 silhta / 싫어하다 silhehata | disagreeable / to dislike | adjective + derived hata-verb pair | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.6, p.153. |
| 귀찮다 kwichanhta / 귀찮아하다 kwichanahata | troublesome / to feel annoyed (by) | adjective + derived hata-verb pair | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.6, p.153. |
| 놀랍다 nollapta / 놀라워하다 nollawehata | frightening / to feel frightened (by) | adjective + derived hata-verb pair | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.6, p.153. |
| 싶다 siphta / 싶어하다 siphehata | want (as in -고 싶다) / to feel like -ing (3rd person) | adjective + derived hata-verb pair | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.6, p.153. |
| 고프다 kophuta / 고파하다 kophahata | hungry / to feel hungry | adjective + derived hata-verb pair | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.6, p.153. |
| 아프다 aphuta / 아파하다 aphahata | hurting, in pain / to feel hurt | adjective + derived hata-verb pair | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.6, p.153. |
| 그립다 kulipta / 그리워하다 kuliwehata | longing for / to feel homesick (for), to miss | adjective + derived hata-verb pair | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.6, p.153; book's own test sentence: ?kunun kohyangi kulipta (3rd person + bare adjective) marked degraded/awkward vs. fully grammatical kunun kohyangul kuliwehanta. |
| predicate-ki + nun/man/to + hata(nun)-ta | emphatic construction: "X indeed is / X is ONLY / X indeed is (too)" | syntactic construction | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | §4.3.7, p.154–156; nominalizes the predicate with -ki, attaches a focus particle, then re-supplies positive temporal profile via hata — used to counter a prior doubt about whether a state/process genuinely holds (dialogue example: 가기는 잘 간다 kakinun cal kanta, "it DOES run well," countering a prior "does this watch even run?"). |
| predicate-key hata | causative construction: "to make/cause X to (become) ___" | syntactic construction | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.8, p.156–158; book analyzes -key as ki (nominalizer, turns a process/state into a temporal noun) + ey (goal/locative marker), reducing the whole construction to a transitive-motion-verb pattern parallel to nohta 'to put' (mover is caused to "arrive at" the key-marked state). hata itself stays vague about the causing act; object-marked causee implies a push/pull-type verb (milta, tangkita) while dative-marked causee implies a speech-act verb (malhata, myenglyenghata). |
| 생각하다 sayngkakhata | to think | verb | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.9, p.159; mental-activity hata-verb; book shows hata's vague "a relationship exists, physical or mental" meaning gets narrowed to a specific mental-activity reading by the attached verbal connective (-myen = supposing, -nunka = doubting, -na = tentative assumption, -lyeko = intending, -ya = obligation). |
| 결심하다 kyelsimhata | to decide | verb | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.9, p.159. |
| 의심하다 uisimhata | to doubt | verb | core | — | — | — | — | grammar_reference | n/a | verified | §4.3.9, p.159. |

---

## Grammar points

### 4.1 cita as a main verb: force-dynamic (agonist/antagonist) semantics

cita's prototypical main-verb meaning (p.109–110) is analyzed in force-dynamic terms: a "mover"
(agonist) force and a restraining "stem/support" (antagonist) force are in a **steady state**
(e.g. a flower held up by its stem). cita denotes the **change of state** that results when the
steady state collapses — either the antagonist is removed or it weakens relative to the agonist —
producing (typically downward) motion. The prototype (꽃이 지다, "the flower fell") extends
metaphorically to: discontinuous visibility/existence (해가 지다 "the sun set," 불이 지다 "the fire
went out"), and to abstract "contests" with no physical movement at all (싸움에 지다 "to be defeated
in a fight" — the losing side is the force found to be weaker after the "steady state" of an even
contest gives way).

### 4.1.1–4.1.2 cita as an auxiliary verb; adjective-e cita

As an auxiliary, cita combines with stative adjectives and with verbs to denote **inchoation** — a
change from a static state into a dynamic process. With stative adjectives (identified
syntactically by incompatibility with the present-tense marker -nun, p.111), the resulting
adjective-e cita compound denotes change-of-state ("becomes ___"). Two structural points the book
stresses (p.113): (1) the antagonist counterforce is never syntactically expressed in these
sentences, only inferable from world knowledge; (2) the identity of any agent behind the change is
systematically irrelevant/backgrounded — the whole event is framed purely as an interaction between
two non-agentive forces, not as someone's action.

### 4.1.3 verb-e cita (intransitive verbs): potentiality against expectation

With intransitive verbs, the cita-compound denotes **potentiality** realized against the speaker's
prior expectation that the two opposing (non-physical, "mental-expectation") forces would NOT
resolve the way they did. The diagnostic pattern throughout §4.1.3: a bare sentence (e.g. "the many
people slept in the room," p.114) simply reports a fact, while its -e cita counterpart additionally
implies the speaker had estimated the weaker force (room capacity, distance-per-hour, ice strength)
would lose, yet in actuality the process went through anyway. The instrumental postposition choice
tracks this: -ulo marks an instrument understood as actively/dynamically wielded by the agent, while
-ey marks it as a fixed, passively-involved location/object (p.118–119) — contrasted directly with
송곳으로 뚫었다 vs. 송곳에 뚫었다, both glossed "I drilled it with/at a gimlet" in English but
semantically distinguished in Korean by this postposition choice.

### 4.1.4 transitive verb-e cita: valence flip, similar to a passive

With transitive verbs, the cita-compound obligatorily promotes the **object** of the base transitive
verb to subject position — syntactically parallel to a passive (p.116). The original agent cannot
surface as subject (*salamtuli kangmwulul makaciessta is ungrammatical); at most it can appear as a
forced dative/beneficiary reading via NP-eykey (지었다 → Changswu-eykey ciecessta, "managed to get
built *for* Changswu," never "*by* Changswu"). When the agent's own capability (rather than an
external force) is the relevant opposing force, the auxiliary nayta is used instead of cita (지어
냈다 cie nayessta, "managed to build," implying the agent doubted their own ability).

### 4.1.5 Comparison with morphological (/Ci/) passives

Korean's morphological passive is formed with the morpheme /Ci/, realized as four allomorphs
(-hi-, -li-, -i-, -ki-) conditioned by the base verb (full paradigm table above, p.120–121). Both
this morphological passive and the cita-compound share the valence-flip property (object of the
active verb → subject), but they are semantically distinct: a bare morphological passive (그 못이
뽑히었다, "the nail was removed") is a neutral description, while the corresponding cita-compound
(그 못이 뽑아졌다, "the nail managed to get removed") additionally carries the speaker's prior doubt
that it would come out (p.122). Natural/accidental processes with no implied human exertion take
**only** the morphological passive, never the cita-compound (날씨가 풀리었다 "the weather became
warm" / *풀어졌다 is ungrammatical; 운이 열리었다 "fortune turned in his favor" / *열어졌다 is
ungrammatical) — because the instrumental postposition -ulo (which licenses a cita-compound reading)
implies the instrument is under an agent's direct control, and these natural processes have no such
controlling agent. A fuller contrast between the morphological passive and a periphrastic/compound
passive is deferred by the source itself to its Chapter 5 (out of this chunk's scope).

### 4.2 cwuta as a main verb and as a benefactive auxiliary

As a main verb, 주다 cwuta 'to give' takes a recipient marked NP-eykey (animate) or NP-ey
(inanimate), and the thing given can be concrete or abstract, good or bad (p.123). As an auxiliary
(verb-e cwuta), it denotes that the subject performs the action **for the sake of** someone else —
and crucially, that someone-else beneficiary is not limited to the NP marked by -eykey/-ey; it can
be the speaker, the addressee, or an unexpressed third party, disambiguated where needed by NP-ul
wihayse "for the sake of" or NP-taysiney "in place of" (p.124–125).

**Controllability constraint.** Only verbs denoting agent-controllable processes combine felicitously
with cwuta; verbs denoting uncontrollable processes are marked degraded with it (p.126, ?나는
머리가 아파 주었다). For verbs ambiguous between a controlled and uncontrolled reading, combining
with cwuta forces the intentional reading — an adverb like 우연히 "accidentally" becomes
ungrammatical once cwuta is added, and normally-involuntary verbs like "lost (money gambling)" shift
to an intentional "lost on purpose, for someone's benefit" reading when cwuta-compounded (p.127).

**Idiosyncratic affectedness verbs.** A small class of instructional/informational verbs —
가르치다 'teach', 알리다 'inform', 일깨우다 'awaken' — additionally entail, only when
cwuta-compounded, that the recipient was actually successfully affected (가르쳐 주었다 implies the
students actually learned; the simple 가르쳤다 only means teaching took place, p.127–128).

**Valence/meaning-shifting compounds.** A handful of cwuta-compounds diverge from "simple verb +
benefaction" in syntax or meaning (p.128–129): 들리다/보이다 (one-argument passives of 듣다/보다) have
causative two-argument cwuta-counterparts 들려 주다/보여 주다 ("let hear"/"show"); 빌리다 'to borrow'
has the cwuta-counterpart 빌려 주다 meaning 'to lend' — an outright meaning shift, not mere added
benefaction.

**Directive politeness.** The cwuta-compound is also used in commands/requests, where it is more
polite than the bare imperative/request form because it frames the addressee's compliance as a favor
to someone else, not a bare imposition (앉아라! vs. 앉아 주어라, p.130). With causative directive verbs
specifically, the implied beneficiary can default to the speaker, making sentences like 밥을 먹여
주세요 genuinely ambiguous between "feed me" and "feed someone else, for my sake" (p.131) — the same
ambiguity recurs with 입혀 주세요 'dress (me/someone)', 신겨 주세요 'put shoes on (me/someone)', 끼워
주세요 'put gloves on (me/someone)'.

**Honorific selection.** Korean marks an honorific counterpart for several verbs including cwuta
(→ 드리다 tulita). The book's specific contribution is the **conditioning rule**: tulita is selected
when the *beneficiary* (not the grammatical subject) is socially superior to the speaker (p.131–132)
— tulita also functions as an auxiliary paralleling cwuta (신문을 읽어 드렸다 "read the paper for
Grandma"). A separate, less commonly documented contrastive form 다오 tao (base form itself unclear
in the source, possibly from 들다 tul-ta) is used specifically when the beneficiary is the speaker
**and** the agent/addressee is socially inferior to the speaker (p.133) — functioning as a
"give-me"-type directive distinct from both cwuta and tulita.

### 4.3 hata: schematic meaning and its instantiations

The book frames 하다 hata as maximally schematic — a near-content-free verb that supplies positive
**temporal profile** (the "unfolding in time" that distinguishes verbs/processes from atemporal
nouns/things) to whatever atemporal relation it combines with (p.133–136, following a Langacker-1987
cognitive-grammar-style diagrammatic analysis). Because it is a schema for virtually every verb and
adjective (except issta, ita, and the motion verbs ota/kata, p.133), hata's concrete meaning in any
given sentence is supplied almost entirely by what it combines with and by context/convention, not
by hata itself.

**§4.3.1 Concrete nouns + hata.** The verb-forming relationship between a concrete noun and hata is
not semantically predictable from the noun alone but fixed by convention/culture: 나무(를) 했다
"[he] collected firewood" (not any other plausible relationship to wood) is the conventionalized
reading for 나무 + hata, similarly 산나물(을) 하다 'collect wild herbs' and 물건(을) 하다 'buy things'
(p.137–138). Some such pairings remain genuinely ambiguous out of context — (밥, 술, 저녁, 점심)을
했다 can mean cooked-or-ate-rice, brewed-or-drank-rice-wine, prepared-dinner, prepared-lunch,
disambiguated only by context (p.139).

**§4.3.2 Agentive/instrumental nouns via the dependent noun -질 cil.** -질 cil never stands alone; it
attaches to an agent-denoting or tool-denoting noun to form an atemporal "typical activity involving
X" noun, which then combines with hata for temporal profile. The source explicitly notes that
agentive -cil compounds (도둑질 'stealing', 순사질, 선생질, 면장질 — thief/policeman/teacher/mayor +
cil) carry an **unfavorable/derogatory connotation**, while instrumental -cil compounds (knife,
shovel, hammer, scissors, needle, chopstick, finger, brush, broom, mop, fan, iron + cil) do **not**
(p.140–143). This derogatory-agentive-nominalizer pattern is a notable slang-adjacent finding —
worth flagging for the mechanics-analysis phase as a productive pejoration strategy.

**§4.3.3 Deverbal nouns.** Four suffixes are listed (-ki, -um, -i, -key — though the source's own
prose says "three," see the discrepancy note above). -ki is fully general/productive on any
verb/adjective, yields atemporal nouns, and is used with hata in the emphatic construction (deferred
by the source to its own Chapter 5). -um and -i are not productive and their derived meanings are
unpredictable — el-ta 'freeze' → elum 'ice' (concrete) vs. ssau-ta 'fight' → ssaum 'fighting'
(abstract process), both via -um (p.143–144).

**§4.3.4 Onomatopoeia + hata.** Sound-, shape-, feeling-, and sensation-class onomatopoeic words
(table above) lack inherent temporal structure on their own; hata supplies the temporal realization
needed to describe them as actually occurring/holding (물결이 출렁출렁 한다 "the waves are rolling,"
p.144–146). Some derived predicates are perfective, some imperfective, some both, depending on the
specific word (p.146).

**§4.3.5 Sino-Korean words + hata.** Sino-Korean words (and, by the same pattern, English loan verbs
and adjectives) are grammatically nouns in Korean regardless of their source-language category, and
need hata to function as predicates (p.146–147). Two subgroups behave differently: abstract-location/
-state nouns (행복, 건강, 친절...) yield **imperfective** hata-verbs, incompatible with the present
marker -nun; abstract-activity/-process nouns (공헌, 연구, 조사...) yield **perfective** hata-verbs
that can additionally take a genuine object (with the object marker retained: 물리학을 연구하다) or
incorporate the noun into a single intransitive-looking compound (object marker dropped: 연구하다) —
the two forms differ in whether an adverb can be inserted between the noun and hata (p.148–150).

**§4.3.6 Adjectives + hata.** Korean adjectives are inherently imperfective, homogeneous, one-argument
predicates restricted (in practice) to describing the speaker's own (1st-person) feeling; combining
with hata (기쁘다 → 기뻐하다, full pair list above) derives perfective, two-argument transitive verbs
usable of anyone's feelings, not just the speaker's — demonstrated by the source's own
grammaticality-judgment pair: ?그는 고향이 그립다 (3rd person + bare adjective, degraded) vs. 그는
고향을 그리워한다 (3rd person + derived hata-verb, fully acceptable) (p.151–153).

**§4.3.7 Emphatic construction.** predicate-ki + a focus particle (-nun/-man/-to) + hata(-nun)-ta
re-asserts that a state or process genuinely holds, typically to counter a prior doubt — demonstrated
with a watch-running dialogue where "does this watch even run?" is answered with 가기는 잘 간다
"it DOES run well" (p.154–156). Structurally: the -ki nominalization backgrounds the predicate's
temporal structure while foregrounding its individual sub-stages; hata then re-supplies positive
temporal structure, yielding the emphatic "it's really the case that..." reading.

**§4.3.8 Causative construction.** predicate-key hata is Korean's hata-based causative. The source
decomposes -key itself as ki (the same nominalizer as above, turning a process/state into a temporal
noun) + ey (a goal/locative marker), reducing the whole construction, structurally, to the pattern of
a transitive motion verb like 놓다 nohta 'to put' — the causer is understood to "move" the causee to
/toward the state named by the key-marked predicate (p.156–158). hata itself in this construction
stays maximally vague (merely "intentionally or unintentionally brought about"); the specific manner
is recoverable from the case-marking on the causee: object-marker causees imply a push/pull-class
verb is meant (밀었다/당기었다), while dative-marker causees imply a speech-act verb is meant
(말했다/야단쳤다) (p.158–159).

**§4.3.9 Mental activities.** hata combines with clauses headed by various connectives to denote
specific mental activities (생각하다 'think', 결심하다 'decide', 의심하다 'doubt' as the general verb
class, p.159–160) — the connective itself, not hata, supplies the specific reading: -(u)myen =
supposing, -(u)nunka = doubting, -na = tentative assumption, -(u)lyeko = intending, -(u)ya =
obligation.

---

## Korean — Established Vocabulary/Grammar: *A Korean Grammar on Semantic-Pragmatic Principles* — Chapter 4 "Auxiliary Verbs," §§4.4–4.6 (issta, kata/ota, nayta)

**Source:** Keedong Lee, *A Korean Grammar on Semantic-Pragmatic Principles*, Hankook Munhwasa
(한국문화사), Seoul (publication year not visible in this page range's running headers — left
blank per instructions). Printed pages 160–196 (§4.4 issta 있다), 197–211 (§4.5 kata/ota 가다·오다),
212–219/220 (§4.6 nayta 내다). Vision-read from PDF page images page-080.png through page-111.png
(no text layer; genuinely vision-only source).

**Coverage note.** This is a theoretical, pragmatics-focused monograph, not a pedagogical textbook —
each auxiliary gets systematic aspectual/semantic classification far beyond beginner-grammar
treatment. Korean already has 46 prior `established/` extractions, many pedagogical (Integrated
Korean, College Korean, SNU courses, etc.), which cover the *bare* contrasts:
- `-고 있다` (progressive) vs. `-아/어 있다` (resultative state), including the standard "wearing verb"
  exception list (입다/쓰다/끼다/매다 use `-고 있다` not `-아/어 있다` for "is wearing") — see
  `established/003_intermediate_korean_part1.md`.
- `-고 있다` as the ordinary progressive marker with a sentence or two of illustration — see
  `established/002`, `020`, `023`, and others.
- 가다/오다 as plain directional "go"/"come" verbs and as `-아/어 가다`/`-아/어 오다` continuative
  auxiliaries, at beginner level.

**These bare pedagogical-level contrasts are NOT re-extracted here.** What follows is this book's
distinctive contribution, which is nearly all new: the formal aspectual classification of Korean
predicates (perfective/imperfective, accomplishment/activity, verbs with/without inherent end
points), the cooccurrence restrictions governing each aspect, the systematic ambiguity analysis of
"verbs of wearing/contact" in the progressive (process vs. resultant-state readings) together with
their causative counterparts, the full deictic-center formalization of kata/ota (spatial, temporal,
change-of-state, change-of-feeling, and the "desirable state" pragmatic principle), and nayta as an
advanced auxiliary (completion + achieved-with-difficulty implicature) that no beginner textbook in
this corpus treats at all. No handwritten marginalia was found anywhere in this page range — this is
a clean library/publisher scan; all content below is genuinely printed source material.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 있다 (issta) | to exist; (aux.) resultative state / progressive state | verb | core | — | — | — | — | grammar_reference | n/a | verified | Headword of §4.4; both main-verb (existential/locative/possessive) and auxiliary senses — see Grammar points. |
| 가다 (kata) | to go | verb | core | — | — | — | — | grammar_reference | n/a | verified | Headword of §4.5; deictic locomotion verb — movement away from the deictic center. |
| 오다 (ota) | to come | verb | core | — | — | — | — | grammar_reference | n/a | verified | Headword of §4.5; deictic locomotion verb — movement toward the deictic center. |
| 내다 (nayta) | to take (something) out; (aux.) to complete (with effort/difficulty) | verb | core | — | — | — | — | grammar_reference | n/a | verified | Headword of §4.6; main-verb and auxiliary senses — see Grammar points. |
| 놓다/두다 (nohta/twuta) | to put down / to put, leave | verb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | Used extensively (not as headwords) throughout §4.4.3 in the `V-e nohta/twuta` compound that marks a *maintained* resultative state; nohta is itself the headword of the book's next section (§4.7, out of this chunk's assigned range). |
| 어리다 | to be young | adjective | core | — | — | — | — | grammar_reference | n/a | verified | Example imperfective predicate (cannot take present-tense marker -nunta: *어린다 is ungrammatical). |
| 작다 | to be small/short | adjective | core | — | — | — | — | grammar_reference | n/a | verified | Example imperfective predicate. |
| 똑똑하다 | to be smart | adjective | core | — | — | — | — | grammar_reference | n/a | verified | Example imperfective predicate. |
| 일하다 | to work | verb | core | — | — | — | — | grammar_reference | n/a | verified | Example perfective (imperfective-class, present-marker-taking) predicate; also used later for the habitual/temporary-habit contrast. |
| 웃다 | to laugh | verb | core | — | — | — | — | grammar_reference | n/a | verified | Example perfective predicate that takes the present-tense marker. |
| 자다 | to sleep | verb | core | — | — | — | — | grammar_reference | n/a | verified | Example perfective predicate; also used in §4.6 to show nayta's incompatibility with non-intentional activities (*한 시간을 자내었다 is anomalous). |
| 앉다 | to sit | verb | core | — | — | — | — | grammar_reference | n/a | verified | "Verb with end-point" (change-of-position subclass) — compatible with perfect aspect V-e issta. |
| 서다 | to stand | verb | core | — | — | — | — | grammar_reference | n/a | verified | Verb with end-point (change of position). |
| 눕다 | to lie down | verb | core | — | — | — | — | grammar_reference | n/a | verified | Verb with end-point (change of position). |
| 일어나다 | to rise, get up | verb | core | — | — | — | — | grammar_reference | n/a | verified | Verb with end-point (change of position). |
| 엎드리다 | to prostrate oneself | verb | core | — | — | — | — | grammar_reference | n/a | verified | Verb with end-point (change of position). |
| 구부리다 | to bend | verb | core | — | — | — | — | grammar_reference | n/a | verified | Verb with end-point (change of position). |
| 비틀리다 | to twist | verb | core | — | — | — | — | grammar_reference | n/a | verified | Verb with end-point (change of position). |
| 펴다 | to straighten | verb | core | — | — | — | — | grammar_reference | n/a | verified | Verb with end-point (change of state). |
| 지치다 | to tire | verb | core | — | — | — | — | grammar_reference | n/a | verified | Verb with end-point (change of state). |
| 크다 | to become big | verb | core | — | — | — | — | grammar_reference | n/a | verified | Verb with end-point (change of state). |
| 흐르다 | to flow | verb | core | — | — | — | — | grammar_reference | n/a | verified | Verb with end-point (change of state). |
| 부풀다 | to swell | verb | core | — | — | — | — | grammar_reference | n/a | verified | Verb with end-point (change of state). |
| 살다 | to live | verb | core | — | — | — | — | grammar_reference | n/a | verified | Verb with end-point (change of state). |
| 낫다 | to recover, become well | verb | core | — | — | — | — | grammar_reference | n/a | verified | Verb with end-point (change of state). |
| 놀다 | to play | verb | core | — | — | — | — | grammar_reference | n/a | verified | Verb WITHOUT end-point — incompatible with perfect aspect. |
| 떨다 | to shiver | verb | core | — | — | — | — | grammar_reference | n/a | verified | Verb without end-point. |
| 망설이다 | to hesitate | verb | core | — | — | — | — | grammar_reference | n/a | verified | Verb without end-point. |
| 쉬다 | to rest | verb | core | — | — | — | — | grammar_reference | n/a | verified | Verb without end-point. |
| 지껄이다 | to chatter | verb | core | — | — | — | — | grammar_reference | n/a | verified | Verb without end-point. |
| 떠들다 | to make noise | verb | core | — | — | — | — | grammar_reference | n/a | verified | Verb without end-point. |
| 치다 | to hit | verb | core | — | — | — | — | grammar_reference | n/a | verified | Instantaneous verb; progressive aspect yields a repetitive reading (a series of hits), since a single hit is too point-like for an internal viewpoint. |
| 차다 (kick sense) | to kick | verb | core | — | — | — | — | grammar_reference | n/a | verified | Instantaneous verb, same repetitive-progressive behavior as 치다. (Distinct from 차다 "cold," not covered here.) |
| 깜박이다 | to blink | verb | core | — | — | — | — | grammar_reference | n/a | verified | Instantaneous verb. |
| 쓰다 (headwear) | to put on (a cap) | verb | core | — | — | — | — | grammar_reference | n/a | verified | "Verb of wearing" — ambiguous in progressive (in-process vs. already-wearing); already partly covered at pedagogical level (established/003), but this source gives the full process-vs-result ambiguity analysis plus the causative counterpart 씌우다. |
| 신다 | to put on (shoes) | verb | core | — | — | — | — | grammar_reference | n/a | verified | Verb of wearing; causative counterpart 신기다. |
| 입다 | to put on (clothes) | verb | core | — | — | — | — | grammar_reference | n/a | verified | Verb of wearing; causative counterpart 입히다. |
| 끼다 | to put on (gloves) | verb | core | — | — | — | — | grammar_reference | n/a | verified | Verb of wearing; causative counterpart 끼우다. |
| 매다 | to put on (a belt/band) | verb | core | — | — | — | — | grammar_reference | n/a | verified | Verb of wearing/tying; ambiguity depends on whether the tied object is placed on the subject's own body (머리에 띠를 매고 있다, ambiguous) or elsewhere (기둥에 빨래줄을 매고 있다, not ambiguous) — new finding beyond the bare pedagogical exception list. |
| 이다 | to carry (on the head) | verb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | Verb of wearing/carrying; causative counterpart 이우다. Not seen in prior Korean established/ extractions. |
| 지다 | to carry (on the back) | verb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | Verb of wearing/carrying; causative counterpart 지우다. |
| 메다 | to carry (on the shoulders) | verb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | Verb of wearing/carrying. |
| 쥐다 | to grasp | verb | core | — | — | — | — | grammar_reference | n/a | verified | "Contact verb," instantaneous subtype — NOT ambiguous in progressive (only the continuing-resultative reading is available), contrasted directly with 입다's cumulative/ambiguous behavior. |
| 짚다 | to lean on | verb | core | — | — | — | — | grammar_reference | n/a | verified | Contact verb, instantaneous subtype. |
| 잡다 | to catch, grasp | verb | core | — | — | — | — | grammar_reference | n/a | verified | Contact verb, instantaneous subtype; also used earlier (§4.4.2) in the transitive/passive perfect-aspect cooccurrence-restriction examples (잡다 vs. passive 잡히다). |
| 달다 | to hang, attach, tie on | verb | core | — | — | — | — | grammar_reference | n/a | verified | Contact verb, non-instantaneous/cumulative subtype — ambiguous in progressive like the wearing verbs. |
| 걸치다 | to hang/drape over | verb | core | — | — | — | — | grammar_reference | n/a | verified | Contact verb, non-instantaneous subtype. |
| 걸다 | to hang | verb | core | — | — | — | — | grammar_reference | n/a | verified | Contact verb, non-instantaneous subtype. |
| 붙이다 | to stick, affix, post | verb | core | — | — | — | — | grammar_reference | n/a | verified | Contact verb, non-instantaneous subtype. |
| 좁다 | to be narrow | adjective | core | — | — | — | — | grammar_reference | n/a | verified | Used to illustrate two distinct "become X" derivational patterns: 좁아지다/좁아져 있다 (via auxiliary 지다) vs. 좁게 되다/좁게 되어 있다 (via auxiliary 되다). |
| 좋다 | to be good | adjective | core | — | — | — | — | grammar_reference | n/a | verified | Same "become X" derivational-pattern illustration as 좁다. |
| 아름답다 | to be beautiful | adjective | core | — | — | — | — | grammar_reference | n/a | verified | Listed as a sample Korean adjective — adjectives as a class cannot take perfect aspect (already inherently stative, issta would be superfluous). |
| 어렵다 | to be difficult | adjective | core | — | — | — | — | grammar_reference | n/a | verified | Sample adjective, same class argument. |
| 예쁘다 | to be pretty | adjective | core | — | — | — | — | grammar_reference | n/a | verified | Sample adjective; also independently used (§4.4.3) to show *예뻐 있다/*예쁘고 있다/*예쁘고 있다 are all ungrammatical, confirming adjectives cannot take any issta-based aspect. |
| 옳다 | to be right | adjective | core | — | — | — | — | grammar_reference | n/a | verified | Sample adjective. |
| 적다 | to be few | adjective | core | — | — | — | — | grammar_reference | n/a | verified | Sample adjective. |
| 젊다 | to be young | adjective | core | — | — | — | — | grammar_reference | n/a | verified | Sample adjective. |
| 걷다 | to walk | verb | core | — | — | — | — | grammar_reference | n/a | verified | Manner-of-motion verb — unbounded in time/space, cannot cooccur with a goal expression (*서울에 걸었다), cannot take perfect aspect alone. |
| 날다 | to fly | verb | core | — | — | — | — | grammar_reference | n/a | verified | Manner-of-motion verb, same class as 걷다. |
| 기다 | to crawl | verb | core | — | — | — | — | grammar_reference | n/a | verified | Manner-of-motion verb. |
| 뛰다 | to run/jump | verb | core | — | — | — | — | grammar_reference | n/a | verified | Manner-of-motion verb; boundedness can be imposed on it by a distance expression (10리를 뛰었다 "ran 10 li," now bounded and perfect-aspect-compatible) — illustrates that telicity is partly compositional, not purely lexical. |
| 달리다 | to run | verb | core | — | — | — | — | grammar_reference | n/a | verified | Manner-of-motion verb. |
| 나다 | to move out, emerge | verb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | Directional (not manner) verb — compounds with manner-of-motion verbs (e.g. 뛰어나다 "run out") to supply the missing end point/direction; parallel function to 들다. |
| 들다 (directional) | to move in | verb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | Directional verb, compounds with manner verbs (e.g. 날아들다 "fly in"). |
| 희비 (thoypi) | manure, night soil | noun | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | §4.6 main-verb example for nayta's "take X out of bounded source Y" meaning; faded/compressed small print made this entry slightly less crisp than surrounding text, flagged accordingly. |
| 허가 | permit, license | noun | core | — | — | — | — | grammar_reference | n/a | verified | §4.6 main-verb nayta example (허가를 내다 "to get/take out a license"). |
| 세금 | tax | noun | core | — | — | — | — | grammar_reference | n/a | verified | §4.6 main-verb nayta example (세금을 내다 "to pay tax" — lit. "take out tax"). |
| 끌다 | to drag | verb | core | — | — | — | — | grammar_reference | n/a | verified | Example "means of extraction" verb compounding with nayta (V-e nayta) to express taking something out by a specific manner. |
| 밀다 | to push | verb | core | — | — | — | — | grammar_reference | n/a | verified | Means-of-extraction verb, same construction. |
| 당기다 | to pull, drag | verb | core | — | — | — | — | grammar_reference | n/a | verified | Means-of-extraction verb, same construction. |
| 찾다 | to look for | verb | core | — | — | — | — | grammar_reference | n/a | verified | Contrasted directly with 찾아내다 "manage to find" to demonstrate nayta's added completion + achieved-with-difficulty meaning (시계를 찾았다 "looked for the watch" [outcome unclear] vs. 찾아내었다 "succeeded in finding it"). |
| 심다 | to plant | verb | core | — | — | — | — | grammar_reference | n/a | verified | Used in §4.6's cooccurrence-restriction examples (나무를 심어내었다, bounded by an explicit quantity/time frame, is grammatical; an unbounded planting-activity reading is not). |

**Morpheme breakdown.** Korean's agglutinative morphology is covered by the project's standing
Korean typology profile; the items above are mostly monomorphemic verb/adjective stems as cited by
the source, so no additional per-row breakdown is needed. Two derivational chains worth noting
explicitly (both discussed under the 좁다/좋다 rows above):

> **좁아져 있다** = 좁- (narrow, stem) + -아지- (become, inchoative auxiliary 지다) + -어 (connective) +
> 있다 (exist, resultative aux.) — "is [in the state of having become] narrow."

> **좁게 되어 있다** = 좁- (narrow, stem) + -게 (adverbializer) + 되- (become, auxiliary 되다) + -어
> (connective) + 있다 (exist, resultative aux.) — a near-synonymous alternate "become X" pattern built
> on 되다 instead of the -아/어지다 inchoative.

## Grammar points

### §4.4.1 — issta as a main verb (existential/locative/possessive) — brief, largely redundant

issta covers the semantic range of existential, locative, and possessive verbs in other languages
(책상 위에 책이 있다 "there is a book on the table"; 그에게 돈이 많이 있다 "he has a lot of money," lit.
"money exists at him"). Possession is expressed as something existing at/with a person — a familiar
locative-possessive analysis also found in prior pedagogical extractions, so not elaborated further
here. One distinction the book draws that basic textbooks don't: issta's **stative** existential use
cannot take the present-tense marker -nunta (책이 책상 위에 있다, not *있는다), but when issta describes
an animate subject's intentional, temporary *process* of staying somewhere, the nonstative form
있는다 becomes possible (나는 오늘 집에 있는다 "I will [deliberately] stay home today," vs. plain 있다
"I will be home today" with no implication of intent).

### §4.4.2 — issta as an auxiliary: the two base constructions and a transitivity restriction

As an auxiliary, issta forms two constructions: **V-e issta** (called the *perfect* aspect — denotes
an existing resulting state from a completed process) and **V-ko issta** (the *progressive* aspect —
denotes an internal, ongoing view of a process). The book immediately flags a restriction beginner
sources don't cover: **transitive verbs generally cannot appear directly in V-e issta.** 그는 그
책을 지어 있다 ("he has built a book"-type construction) is ungrammatical; only the corresponding
**passive** is grammatical (책이 지어져 있다, lit. "the book is in a built state"). The explanation
offered is viewpoint-based: with transitive verbs the speaker takes the agent's viewpoint, which is
incompatible with the perfect aspect's end-point/goal orientation; with passives (or some
intransitives) the speaker takes the patient's viewpoint, which the perfect aspect requires. Several
transitive/passive minimal pairs are tabulated (접다/접히다 "fold/be folded," 막다/막히다
"stop/be blocked," 얹다/얹히다 "place/be placed," 닫다/닫히다 "close/be closed," 묻다/묻히다
"bury/be buried") — all transitive forms starred as ungrammatical in V-e issta, all passive forms
grammatical.

### Aspectual classification: imperfective vs. perfective predicates

The book sets up a formal two-way split of Korean predicates using the present-tense marker -nunta
as the diagnostic. **Imperfective predicates** (mostly adjectives: 어리다 "young," 작다 "short,"
똑똑하다 "smart") cannot take -nunta and also cannot appear in imperative mood, the perfect aspect, or
the progressive aspect. **Perfective predicates** (ordinary action verbs: 일하다 "work," 웃다
"laugh," 자다 "sleep") can take -nunta, and the present-tense form of a perfective verb is actually
ambiguous between an on-going-process reading and a generic/habitual reading (see the habitual-vs-
temporary-habit grammar point below).

### Accomplishment vs. activity predicates; locomotion vs. manner-of-motion verbs

Within the perfective class, the book (following Vendler, with an explicit caveat that Korean's
categories don't map 1:1 onto English ones) distinguishes **accomplishment predicates** (processes
with an inherent end point) from **activity predicates** (processes with no end point, simply
continuation through time). The clearest illustration is motion verbs: **locomotion verbs** (가다
"go," 오다 "come") have source and goal, so they're bounded and accomplishment-class; **manner-of-
motion verbs** (걷다 "walk," 날다 "fly," 기다 "crawl," 뛰다 "run/jump") describe only the manner of
continuing motion, are unbounded, and cannot cooccur with a goal expression at all (*그는 서울에
걸었다/날았다/기었다 is ungrammatical, while 그는 서울에 갔다/왔다 is fine). Manner-of-motion verbs can be
promoted into accomplishment status by compounding with a locomotion verb (서울에 걸어/날아/뛰어
갔다(왔다) "went to Seoul by walking/flying/running") or, independently, by an explicit distance
expression that imposes a terminus (10리를 뛰었다 "ran 10 li," now compatible with the perfect aspect,
unlike bare 뛰었다 or 운동장에서 뛰었다 "ran in the playground," which are unbounded and incompatible).
The same boundedness-from-context effect is shown with objects: 노래 한 곡을 부르고 있다 ("singing one
song," object-bounded) vs. 노래를 부르고 있다 ("singing" in general, unbounded) — the telicity of a
predicate is therefore not purely a property of the verb in isolation but can be imposed by
cooccurring arguments.

### Verbs with vs. without inherent end points — governs perfect-aspect compatibility

Beyond the locomotion/manner-of-motion split, the book extends the with-/without-end-point
distinction to intransitive verbs generally, with two subtypes of "verbs with end-points"
(change-of-position: 앉다 "sit," 서다 "stand," 눕다 "lie," 일어나다 "rise," 엎드리다 "prostrate oneself,"
구부리다 "bend," 비틀리다 "twist"; change-of-state: 펴다 "straighten," 지치다 "tire," 크다 "become big,"
흐르다 "flow," 부풀다 "swell," 살다 "live," 낫다 "become well") versus "verbs without end points" (웃다
"laugh," 울다 "cry," 졸다 "doze," 놀다 "play," 떨다 "shiver," 망설이다 "hesitate," 쉬다 "rest," 일하다
"work," 지껄이다 "chatter," 떠들다 "make noise"). Only the end-point class can take V-e issta; schematic
diagrams represent the suffix -e as a goal marker (parallel to the postposition ey) whose end state
issta then gives temporal extension to — i.e. the perfect aspect is analyzed as structurally a
*locative* sentence, with the completed process's end point treated as an abstract location the
subject now occupies.

### §4.4.3 — The progressive aspect: incompletion, and instantaneous verbs' repetitive reading

With accomplishment verbs, V-ko issta gives a meaning of **incompletion** — the subject is neither at
the beginning nor the end of the bounded process, but somewhere in between (그는 집을 짓고 있다 "he is
building a house" — not yet finished). With activity verbs (no inherent end point), the progressive
does not carry this incompletion meaning, since there's no end point to be short of.

A separate subclass, **instantaneous verbs** (치다 "hit," 차다 "kick," 깜박이다 "blink"), denote
processes too brief to have an internal viewpoint at all when performed once. In the progressive,
these verbs instead acquire a **repetitive** reading — a single instant can't be "viewed from inside,"
but a sequence of instantaneous events has duration and so permits an internal viewpoint, yielding
"he is hitting [repeatedly]" rather than a single ongoing hit. The book identifies three distinct
sources of this repetition: a single agent repeatedly acting on a single object, a single agent
acting on multiple objects in sequence, or multiple agents acting on one or more objects.

### Ambiguity in the progressive: "verbs of wearing" and the two subtypes of contact verbs

A systematic ambiguity analysis goes well past the bare pedagogical exception list (입다/쓰다/끼다/매다
"use -고 있다 not -어 있다"). The book identifies a semantically coherent class, **verbs of contact**,
whose progressive aspect is genuinely ambiguous between a **process** reading and a **resultant-state**
reading, because the process-to-result transition is cumulative/gradual rather than sharply
instantaneous — e.g. 입고 있다 can mean either "in the process of putting clothes on" or "already
wearing them." This class subdivides further by what counts as "ambiguous": **verbs of wearing**
(쓰다/신다/입다/끼다/이다/지다/메다 — put on cap/shoes/clothes/gloves/carry-on-head/carry-on-back/carry-
on-shoulders) are ambiguous specifically because the object ends up *on the subject's own body*,
making the subject simultaneously agent and patient; if the same verb's object is placed somewhere
other than the subject's body, the ambiguity disappears (머리에 띠를 매고 있다 "tying/wearing a band on
one's own head," ambiguous, vs. 기둥에 빨래줄을 매고 있다 "tying a clothesline to a post," unambiguous
process-only reading, since the post is not part of the subject). A second subclass, non-instantaneous
**contact verbs** (달다/걸치다/걸다/붙이다 — attach/drape/hang/affix), shows the same ambiguity whenever
the object ends up on the subject (문에 명찰을 달고 있다 "attaching/wearing a name tag," ambiguous) but
not when it doesn't (봉투에 우표를 붙이고 있다 "posting/affixing a stamp on an envelope," unambiguous —
only the in-process reading). By contrast, **instantaneous contact verbs** (쥐다 "grasp," 짚다 "lean
on," 잡다 "catch") are never ambiguous in the progressive — because the contact is reached
instantaneously rather than built up cumulatively, V-ko issta for these verbs denotes only the
continuing resultative state, never the brief instant of making contact itself.

### Disambiguating via nohta/twuta compounds, and causative counterparts that resolve ambiguity differently

To force the "maintaining a resultant state" reading explicitly, almost any of the above verbs can
compound with the auxiliary 놓다 (nohta) or 두다 (twuta): 문패를 달아 놓고 있다 unambiguously means "has
put up the nameplate and is maintaining that state," distinct from plain 달고 있다's two-way ambiguity.
Separately, the **causative** counterparts of the wearing verbs (쓰이우다, 신기다, 입히다, 끼우다,
이우다, 지우다, 채우다 — "put [something] on [someone else]") are never ambiguous in the progressive at
all, because the object is placed on someone other than the agent-subject, so only the in-process
reading is available (e.g. 애기에게 모자를 씌우고 있다 only means "is [in the process of] putting the hat
on the baby," never "the baby is already wearing it").

### Viewpoint explanation: agent/dynamic vs. patient/stable

The book offers a unified viewpoint-based account for several of the contrasts above using a
transitive/passive minimal pair (명찰을 달다 "attach a name tag," transitive, perfect-aspect-
incompatible but progressive-compatible, vs. passive 명찰이 달리다 "a name tag is attached,"
perfect-aspect-compatible). The transitive/agentive viewpoint is inherently dynamic and therefore
compatible with the progressive (which denotes an ongoing, changeable process the subject is actively
maintaining) but incompatible with the perfect aspect (which denotes a stable state the subject
cannot unilaterally change, e.g. 그가 개를 잡고 있다 "holds the dog captive," controllable, vs. 개가
잡혀 있다 "the dog is [in the state of being] caught," not under the dog's own control).

### Habitual readings of perfective verbs: generic present vs. temporary progressive-habit

A perfective verb's bare present-tense form (e.g. 먹는다 "eats") is ambiguous between an on-going-
process reading and a **generic habitual** reading, and this generic-habit reading is treated as a
kind of state composed of a homogeneous series of distinct perfective events. Separately, the
**progressive aspect itself** can also denote habit, but with a different flavor: because the
progressive's internal viewpoint only ever shows a limited slice of a process, a habit expressed via
V-ko issta reads as **temporary/subject-to-change** rather than settled (그는 버스로 학교에 다닌다 "goes
to school by bus [as a settled habit]" vs. 그는 버스로 학교에 다니고 있다 "is [currently, temporarily]
going to school by bus [this may change]"). The same temporariness nuance extends to mental-activity
verbs as a meaning of **tentativeness**.

### Tentativeness with mental-activity verbs in the progressive

With verbs like 믿다 "believe" and 알다 "know," the present tense denotes a firm, settled belief the
subject isn't expected to revise (그는 이 사실을 믿는다 "he believes this firmly"), while the
progressive denotes a tentative, provisional belief liable to change (그는 이 사실을 믿고 있다 "he is
[currently, tentatively] believing this"). The same contrast is shown with 알다/알고 있다 ("knows it as
settled fact" vs. "currently holds it to be fact") and 생각하다/생각하고 있다 ("thinks" vs. "is
[currently] thinking").

---

### §4.5.1 — kata/ota: the deictic center and spatial movement (brief — basic directionality largely redundant)

가다/오다 are deictic locomotion verbs requiring a deictic center for interpretation — typically the
speaker's location, but (as shown below) sometimes the addressee's. When the deictic center is fixed,
오다 marks movement **toward** it and 가다 marks movement **away**. Plain directional use (내려가다/
올라가다 "go down/up," etc.) is standard textbook material and not re-extracted here; the deictic-
center *formalization* and the finer pragmatic effects below are the book's distinctive contribution.

### Tense restriction: only kata is possible when the speaker is in transit

With present or future tense referring to the speaker's own upcoming movement, **only 가다 is
grammatical, never 오다** (나는 지금 학교에 가고 있다, not *오고 있다; 내일 나도 그 모임에 가겠습니다, not
*오겠습니다), even in contexts where 오다 would otherwise fit the destination. The book's explanation:
a speaker who is in the midst of (or about to start) moving cannot simultaneously serve as the fixed
deictic center the verb's interpretation requires.

### Addressee-based deictic center in questions, and resulting ambiguity

In statements, the deictic center defaults to the speaker's location. In **questions**, however, the
asker has two options: use their own present location as the deictic center, or adopt the
**addressee's** location instead. 기홍, 거기 와있나? ("Has Kihong come there?") uses 오다 even though
"there" (거기) refers to the addressee's location, not the speaker's — showing the question-asker
assumed the addressee's location as deictic center. Using 가다 instead (기홍, 거기 가 있나?) makes 거기
ambiguous between the addressee's location and some third place. Past-tense questions can be doubly
ambiguous for the same reason: 기홍 그 모임에 왔더냐? ("did Kihong come to the meeting?") can mean either
that the speaker attended the meeting but didn't see Kihong there (speaker's own past location is
deictic center), or that the speaker didn't attend but the addressee did (addressee's past location is
deictic center).

### Compound V-e kata/ota with manner-of-locomotion and directional verbs

가다/오다 compound as `(V-e)★ kata/ota` (the book's own asterisk notation marks an element that can
recur more than once in a sentence) with manner-of-locomotion verbs (걷다 "walk," 뛰다 "run," 날다
"fly," 기다 "crawl" — supplying the manner) or with purely directional verbs (나다 "move out," 들다
"move in" — supplying direction without manner), e.g. 새들이 둥지로 날아들어 갔다 "the birds flew into
their nests," 아이들이 집 안으로 뛰어들어 왔다 "the children ran into the house." This compounding
converts an otherwise-unbounded manner-of-motion verb into a bounded, accomplishment-class predicate
by supplying it with 가다/오다's inherent goal/source structure.

### §4.5.2 — Temporal deixis: time as a moving entity

The spatial meaning of 가다/오다 extends figuratively to the passage of time, with time conceptualized
as flowing from past through present to future and the speaker's present moment as the deictic center.
Movement **toward** the present (continuation from the past up to now) is expressed with 오다 (창우는
작년부터 열심히 돈을 모아오고 있다 "Changwu has been saving money [continuously] since last year");
movement **away** from the present (continuation from now into the future) is expressed with 가다. The
same pattern extends to abstract "moving" subjects like vehicles approaching/time periods elapsing
(택시 한 대가 다가오고 있다 "a taxi is approaching" / 여름이 지나갔다 "summer is over, [has] passed away").

### §4.5.3 — Change of state: the normal/desirable state as deictic center

Change of state is patterned directly on change of location: a "normal" or "desirable" state serves
as the deictic center, with **오다 marking change toward** that normal/desirable state and **가다
marking change away** from it. Food going bad (맛이 갔다, kata — moving away from the normal/edible
state) vs. regaining consciousness (정신이 돌아왔다, ota — toward the normal state) vs. losing one's mind
(혼수상태에 들어갔다, kata) are given as parallel examples, as is body-part shape (normal mouth shape
restored = ota; distorted = kata) and body temperature relative to the normal 36°C baseline (moving
away from normal = kata regardless of direction of change; moving back toward normal = ota). Crucially,
the "normal state" baseline can be replaced by a **desirable state** that varies by speaker
perspective: grain prices rising is described with 오다 by a farmer (for whom high prices are the
desired/deictic-center state) but with 가다 by an ordinary consumer (for whom high prices are a move
away from their desired state) — the same objective price movement, opposite verb choice, purely as a
function of whose desirability-baseline is taken as the deictic center. The same farmer/consumer-style
contrast is shown with a room's floor cooling off (식어온다 by someone who wants it cool, 식어간다 by
someone who wants it warm).

### §4.5.4 — Change of feelings and sensations

Abstract feelings and bodily sensations are treated as entities that "arrive" at the experiencer when
the person becomes aware of them, consistently using 오다 (not 가다) for their onset: 손발이 시려온다
"hands and feet are becoming cold," 배가 고파온다 "becoming hungry," 마음이 서글퍼 온다 "becoming sad." No
가다-counterpart construction for the *departure* of a feeling is given in this section.

---

### §4.6 — nayta as a main verb: taking something out of a bounded source

The core meaning of 내다 (nayta) is that the subject takes some object X out of a place/source Y — and
critically, **the source Y is frequently left unexpressed but still semantically present and
recoverable from context** (창우는 퇴비를 내었다 "Changwu took out the manure [from the pile]"; 창우는
세금을 내었다 "Changwu paid his taxes," understood as "took the tax money out of himself/his funds").
This "always an understood source" property distinguishes nayta from a simple transitive "take" and
sets up its later auxiliary meaning. nayta also compounds as `V-e nayta` with "means of extraction"
verbs (끌다 "drag," 밀다 "push," 차다 "kick," 당기다 "pull") to specify the manner by which something was
taken out (책장을 끌어/밀어/차/당기어 내었다 "took the bookcase out by dragging/pushing/kicking/pulling
it").

### Two classes of motion verbs, and nayta's role converting manner-verbs into locomotion verbs

The book restates and extends the locomotion-vs-manner-of-locomotion distinction from §4.5 here:
manner-of-locomotion verbs (끌다, 차다, 날다, 뛰다, 걷다, 달리다 — drag/kick/fly/run/walk/run) cannot
cooccur with source expressions (*그는 책상을 방에서 밀었다 "pushed the desk from the room" is
ungrammatical with a bare manner verb), while nayta compounded onto them (V-e nayta) licenses the
source expression (그는 책상을 방에서 밀어 내었다 "pushed the desk out of the room," now grammatical) —
i.e. nayta grammatically promotes a manner-of-locomotion verb into a locomotion-class predicate, the
same mechanism (supplying the missing end-point/source structure) seen with 가다/오다 in §4.5.

### nayta as an auxiliary: completion plus "achieved with difficulty" implicature

As an auxiliary, V-e nayta means the subject carries the object of the verb out of (completes) the
process denoted by that verb, and nayta is used **only with bounded predicates** (those with a clear
beginning and ending) accordingly. Beyond bare completion, nayta carries a distinctive added
implicature the book is explicit about: **the task was not easy, and the subject managed to
accomplish it [despite the difficulty]**. This is shown by contrasting 그는 그 책을 읽었다 "he read the
book" (ambiguous: may or may not have finished) with 그는 그 책을 읽어내었다 "he managed to read the
book [all the way through, with effort]" (unambiguous completion + effortful-achievement reading, not
merely synonymous with the simple completed reading of the first sentence). A second pair makes the
"achieved despite difficulty" sense even sharper: 시계를 찾았다 "looked for the watch" (outcome
unresolved — can be felicitously followed by "...으나 못찾았다 but failed to find it") vs. 시계를
찾아내었다 "managed to find the watch" (felicitously followed by failure is now **awkward**, because
찾아내다 already asserts successful, effortful completion).

### §4.6.1 — Cooccurrence restrictions on the auxiliary nayta

Three restrictions are identified: (1) **Bounded predicates only** — nayta combines only with
predicates that have a terminus; 뛰었다 alone (no terminus) cannot take nayta, but 10리를 뛰었다
(distance-bounded) can (10리를 뛰어내었다 "managed to run 10 li"). (2) **Intentional/controllable
activities only** — nayta is anomalous with processes the subject cannot carry out by deliberate
effort (?그는 한 시간을 자내었다 "he managed to sleep for an hour" sounds odd, since one cannot sleep
*intentionally* for a set duration). (3) **Agent viewpoint only, never patient/passive** — nayta cannot
combine with intransitive verbs or with the passive forms of transitive verbs, even when those forms
are independently bounded (*나무 100그루가 한 시간만에 심기어내었다 "100 trees were managed to be
planted," passive, ungrammatical, vs. 그는 나무 100그루를 한 시간만에 심어내었다 "he managed to plant 100
trees in an hour," active/transitive, grammatical) — because nayta's "achieved with effort" meaning is
inherently agent-viewpoint, incompatible with the patient-viewpoint passive construction, paralleling
the agent/patient viewpoint argument made for issta in §4.4.

---

## Korean — Established Vocabulary/Grammar: *A Korean Grammar on Semantic-Pragmatic Principles*, Chapter 4, §§4.7–4.12 (nohta, pelita, pota, ssahta, tayta, twuta)

**Source:** Keedong Lee, *A Korean Grammar on Semantic-Pragmatic Principles*, Hankook Munhwasa (한국문화사), Seoul (no printed publication year visible in this page range). Chapter 4 "Auxiliary Verbs," §4.7 nohta (놓다, p.220) through §4.12 twuta (두다, p.257–267). Chapter 4 ends at printed p.267; Chapter 5 "Passives" table of contents begins on the facing page. Vision-read from scanned page images (no text layer, no decodable font cipher — genuinely vision-only source); pages 110–135 of the rendered page-spread set (printed pp.218–267 visible across that range).

**Coverage note:** This is the last third of Chapter 4, covering six auxiliary-verb entries: 4.7 nohta (놓다), 4.8 pelita (버리다), 4.9 pota (보다), 4.10 ssahta (쌓다), 4.11 tayta (대다), 4.12 twuta (두다). The language's 46 prior `established/` files are mostly pedagogical textbooks that already cover **-아/어 버리다** ("completive, with a nuance of regret/relief") and **-아/어 보다** ("try doing") at a beginner level with one or two example sentences each — that bare pedagogical-level gloss is **treated as redundant and skipped here** (not re-extracted). What is extracted instead, for pelita and pota, is **only this book's deeper pragmatic/semantic analysis**: for pelita, the author's split into two genuinely distinct subsenses (speaker-expectation-spoiling vs. psychological-hindrance-removal, including the ambiguity between them) and the detailed non-factivity/intentionality/imperative-softening/interrogative-ambiguity argumentation for pota that goes well beyond "try doing something." **nohta, ssahta, tayta, and twuta are kept in full** as genuinely new content — these four advanced resultative/repetitive auxiliary constructions are essentially absent from beginner/intermediate Korean textbooks in this corpus and receive no prior coverage at all. No handwritten marginalia, underlining, or pencil annotation of any kind was found anywhere in this page range — the scan is a clean, unmarked library copy throughout.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 놓다 (nohta) | to let go of/release (main verb); as auxiliary: to complete an action and set it aside; to put/place something outside one's sphere of control | verb (main + auxiliary) | core | — | — | — | — | grammar_reference | n/a | verified | Prototypical sense: releasing an object held in the hand from a controlled to an uncontrolled state; see Grammar points §4.7 |
| 버리다 (pelita) | to throw away, discard (main verb); as auxiliary: marks the speaker's regret/disappointment OR relief that an event occurred | verb (main + auxiliary) | core | — | — | — | — | grammar_reference | n/a | verified | Beginner "regret/relief" gloss already covered elsewhere; this entry retained only for the book's split into two distinct subsenses, see §4.8 |
| 보다 (pota) | to see, to look at (main verb); as auxiliary: to try doing something (ambiguous between testing one's ability and testing a result) | verb (main + auxiliary) | core | — | — | — | — | grammar_reference | n/a | verified | Beginner "try doing" gloss already covered elsewhere; retained only for internal/external-trying distinction and pragmatic softening uses, see §4.9 |
| 쌓다 (ssahta) | to pile up, stack (main verb); as auxiliary: (with adjectives) excessive degree; (with verbs) excessive/irritating repetition | verb (main + auxiliary) | core | — | — | — | — | grammar_reference | n/a | verified | Not covered in any prior Korean established/ file; see §4.10 |
| 대다 (tayta) | to bring into contact with (main verb); as auxiliary: constant/continuous repetition of an action, usually irritating to the speaker | verb (main + auxiliary) | core | — | — | — | — | grammar_reference | n/a | verified | Not covered in any prior Korean established/ file; see §4.11 |
| 두다 (twuta) | to put something at a place under one's control; to leave something undisturbed (main verb); as auxiliary: resultative state maintained/preserved for future use | verb (main + auxiliary) | core | — | — | — | — | grammar_reference | n/a | verified | Not covered in any prior Korean established/ file; see §4.12 |
| 입다 (ipta) | to put on/wear (clothing) | verb | core | — | — | — | — | grammar_reference | n/a | verified | Part of the explicit "verbs of dress" set (p.236) shown as incompatible with nohta |
| 쓰다 (ssuta, "to wear a hat/cap") | to put on/wear (hat, cap) | verb | core | — | — | — | — | grammar_reference | n/a | verified | Homophonous with ssuta "to write"/"to use" — disambiguated by the book itself as a separate dress-verb entry; part of the "verbs of dress" set |
| 신다 (sinta) | to put on/wear (shoes, socks) | verb | core | — | — | — | — | grammar_reference | n/a | verified | Part of the "verbs of dress" set |
| 끼다 (kkita) | to put on (gloves) | verb | core | — | — | — | — | grammar_reference | n/a | verified | Part of the "verbs of dress" set |
| 입히다 (iphita) | causative of ipta: to put clothes on (someone else) | verb | core | — | — | — | — | grammar_reference | n/a | verified | Causative counterpart that, unlike the base dress-verb, IS compatible with nohta (p.237) |
| 씌우다 (ssuiuta) | causative of ssuta: to put a hat on (someone else) | verb | core | — | — | — | — | grammar_reference | n/a | verified | Causative counterpart compatible with nohta |
| 신기다 (sinkita) | causative of sinta: to put shoes/socks on (someone else) | verb | core | — | — | — | — | grammar_reference | n/a | verified | Causative counterpart compatible with nohta |
| 끼우다 (kkiuta) | causative of kkita: to put gloves on (someone else) | verb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | Causative counterpart compatible with nohta; romanization of the causative form itself (vs. base kkita) was not independently cross-checked elsewhere on the page |
| 있다 (iss-ta, resultative) | resultative/progressive auxiliary marking a state as holding (e.g. of a passive verb) | verb (auxiliary) | core | — | — | — | — | grammar_reference | n/a | verified | Cited contrastively (p.235) as the auxiliary used for the resultative aspect of passives, which does not combine with nohta |

**Morpheme breakdown:** not applicable to this chunk — the vocabulary items here are simple, non-composed verb stems (or, for the dress-verb causatives, a single transparent causative suffix each: iph-, ssuiw-, sink-, kkiw- + -i-/-u- causative morphemes); none require a multi-morpheme compositional breakdown beyond what the gloss already states.

## Grammar points

### 4.7 nohta (놓다) — main verb: release from the hand

The main verb nohta denotes the change from a steady state of *holding* something in the hand to a steady state of *releasing* it, so that the object changes its place or state and comes out from under the subject's control (p.220). The book diagrams this as three stages — holding, releasing, reaching — and notes that nohta compounds can realize either the releasing aspect or the reaching aspect, or both. The releasing sense is extended metaphorically the way English "out of hand"/"in hand" idioms work (p.221).

**4.7.1 Some cooccurrence restrictions (main verb).** nayta "to take something out" (discussed just before this section) combines only with *bounded* predicates — e.g. "Changswu ran in the playground" (unbounded) cannot take nayta, but "Changswu ran 10 li" (bounded by the distance) can (p.218–219). nayta also requires an intentionally-carried-out activity (sleeping for an hour cannot combine with nayta) and cannot combine with intransitive verbs, including the passive forms of transitives (p.219).

**4.7.1 Releasing aspect (main verb).** Concrete objects: picking up and putting down a thing, releasing a caught bird (p.221). Extended to abstract objects: leasing a house out of one's own use (censey nohta), lending money out of one's possession, releasing children or animals "to grow/roam wildly" without supervision, relieving oneself of a worry, or "releasing the speed" of a car (i.e., letting it speed up) — in each case nohta marks something moving out of the subject's control (p.222–223).

**4.7.2 Reaching aspect (main verb).** When the released object reaches a new place and enters a steady resting state there — e.g. putting a vase on a table, setting a trap in a path, installing a telephone, laying a bridge across a river. The subject need not be the one who physically did the releasing; it can be an indirect agent (p.223–224) — e.g. "he had a telephone installed" or "they had a bridge put across the river" need not mean the grammatical subject personally did the installing.

**4.7.2.1 nohta as an auxiliary verb — releasing aspect.** V-e nohta between two clauses linked by -ko/-ese marks that the first action is finished and "off the subject's hands" before the second begins, contrasted with the bare connective which simply lists two events in sequence. "He ploughed and ate lunch" (simple) vs. "He finished ploughing [and set that task aside] and ate his lunch" (nohta compound) — the latter adds the nuance of a completed, dispensed-with first task (p.225–226, examples 10–12).

**4.7.2.2 nohta as an auxiliary verb — reaching aspect.** V-e nohta marks that a process has come to an end and a resultant object/state now exists and remains, out of the agent's active control unless disturbed further. Compatible with verbs of creation (ssuta "write," mantulta "make," kulita "draw/paint" — p.227) and verbs of change (kochita "repair," pwuswuta "break," kalta "sharpen" — p.228), because these produce a persisting changed object. Also compatible with verbs of mental activity (saynggakhata "think," pota "see," tulta "hear," ilkta "read") when the result is thought to remain in the mind (p.228–230): e.g. saynghakhay nohassta "have thought out [a plan, and it persists in mind]." **Not** compatible with pure instrumental-use verbs (chita "play [piano]," ssota "shoot [an arrow]") because using an instrument does not leave the instrument itself in any new changed state (p.228).

**4.7.3 Comparison of the simple verb and the nohta compound.** Four diagnostics (p.230–234):
- With the connective **-ese**: a nohta compound disallows the same-subject reading across the two clauses it links (the baker-and-eater must be different people), because nohta's "released from control" meaning conflicts with "coming into the agent's own possession" (mek-ta "eat").
- With the conative connective **-eto** ("no matter how hard..."): the simple form denotes mere conation/attempt and can be felicitously negated afterward ("no matter how hard I push, it doesn't move"); the nohta compound denotes *successful completion* and cannot be negated afterward without contradiction.
- With the simultaneity suffix **-myense** ("while ...-ing"): incompatible with the nohta compound, because -myense denotes an ongoing process while nohta denotes a process already brought to completion.
- With the discontinuation connective **-taka** ("...but stopped partway"): likewise incompatible with the nohta compound for the same reason — -taka presupposes an interrupted, incomplete process.

**4.7.4 Cooccurrence restrictions (auxiliary).** (i) nohta is an inherently agentive verb and is therefore incompatible with nonagentive intransitive verbs — the resultative aspect of such predicates (including passives) is instead expressed with the auxiliary **iss-ta** (p.234–235). (ii) nohta is incompatible with the specific set of "verbs of dress" — ipta "put on clothes," ssuta "put on a hat," sinta "put on shoes/socks," kkita "put on gloves" — because nohta's meaning (removing something from oneself) directly contradicts dressing (putting something onto oneself); example: *"Thomun osul ipe nohassta* ("?Tom has put on the clothes [off himself]") is anomalous. Their **causative** counterparts (iphita, ssuiuta, sinkita, kkiuta) are fully compatible with nohta, however, because the causative agent is putting the item on *someone else*, not on himself (p.236–237). (iii) As already established in §4.7.2.2, nohta is incompatible with pure instrumental verbs.

### 4.8 pelita (버리다) — main verb and two auxiliary subsenses

Main verb: the subject throws object X out of some domain Y of his own possession or influence; X and Y can each range from fully concrete (a thing, a physical area) to fully abstract (hope, a state of use) — illustrated with "Changswu threw away the waste" through to "Changswu gave up his hope" (p.238–239). As an auxiliary, pelita's meaning is not unrelated to the main verb but figuratively extends it in two directions:

**4.8.1 Spoiling the speaker's expectation.** V-e pelita adds a layer of meaning absent from the simple form: the speaker's regret or disappointment that the described event occurred — "kunun kassta" ("he went") is neutral, but "kunun kapeliessta" ("he went, to my regret") additionally conveys that the going disappointed the speaker's expectation (p.240). The author analyzes this as a chain: the event happened → it was not what the speaker wanted → therefore the event "spoiled" the speaker's expectation, parallel to how concrete things can be spoiled (p.241). Verbs denoting processes that lead to inherently undesirable outcomes (michita "go crazy," cwukta "die," manghata "get ruined") commonly appear in the pelita compound, but this is not a restriction — a verb describing an objectively *desirable* outcome can still take pelita if that outcome disappoints the speaker, e.g. "ku salamuy pyengi napeliessta" ("to my regret, he recovered") used by a speaker who had wanted the subject to die (p.241).

**4.8.2 Removing psychological hindrance.** The complementary extension: when an unwanted or burdensome thing is thrown away/gotten rid of, the speaker may instead feel *relieved*. "Nanun ku kaylul phalapeliessta" ("To my relief, I sold the dog") — illustrated with a scenario where an oversized, troublesome dog's sale relieves its owner of a burden (p.242). Because both subsenses (regret vs. relief) derive from the same underlying "thing thrown out of a domain" meaning, pelita sentences can be genuinely ambiguous between them depending on context — e.g. "kutuli nay kwacalul mekepeliessta" can mean either "to my regret, they ate my cookies" or "to my relief, they ate my cookies" (p.243, example 10).

### 4.9 pota (보다) — main verb: eight conventionalized senses of visual perception

Main verb: to perceive with the eyes, with or without purpose. Purposeless seeing is simply visual perception that occurs incidentally (p.243). Purposive seeing has (at least) eight conventionalized extended senses the book catalogs (p.243–245):
(a) **to gain knowledge** — seeing/reading books, newspapers, magazines;
(b) **to consult or meet** — seeing a lawyer, doctor, druggist, fortune-teller;
(c) **to protect or care for** — watching over a child, a house, a warehouse, a school;
(d) **to attend to/work on** — looking after housework, business, schoolwork;
(e) **to assess or estimate** — "he sees me as easy" (manmanhi ponta);
(f) **to attend as an observer** — seeing a movie, a festival, a market;
(g) **existence entailment** — since only things that exist can be seen, "seeing" a new family member (daughter, son, son-in-law, daughter-in-law, new husband) implicates that person's existence/arrival has newly come about;
(h) **abstract nouns treated as concrete** — "seeing" an end, a dissolution, an agreement/conclusion.

**pota as an auxiliary verb.** V-e pota is genuinely ambiguous between two readings (p.245): (i) "to try to see if one has the ability to do V" (ability is *not* presupposed), labeled **internal trying**; and (ii) "to try doing V to see the results or consequences" (ability *is* presupposed), labeled **external trying**. Example: "kele poassta" out of context is ambiguous between "I tried [to see if I could] walk" (e.g. after having a cast removed, ability genuinely in doubt) and "I tried walking [to see what effect it would have]" (e.g. to relieve indigestion, ability taken for granted) — p.245–247.

**Non-factivity.** The pota compound, unlike the simple past form, does not presuppose successful completion. "?nanun ku chaykul ilkessta, ilkci moshayessta" ("?I read the book but I did not read it") is contradictory, because ilk-ess- ("read") already asserts successful completion; but "nanun ku chaykul ilke poassuna ilkci moshayessta" ("I tried to read the book, but I could not read it") is unproblematic, because the pota compound only asserts an attempt (p.247–248).

**Intentionality requirement.** Unlike the simple form, which can describe either an accidental or a deliberate act (kkayta "to break," ambiguous between accidental and on-purpose), the pota compound only allows the intentional reading — "changswuka hwapunul kkaye poassta" can only mean Changswu broke the vase on purpose, and the unintentional adverb silswulo ("by mistake") cannot combine with it (p.248).

**Imperative and proposative softening.** The bare imperative (V-ela, e.g. "i chayk ilke" "read this book") presupposes the addressee's ability and is direct/imposing; the pota-compound imperative (V-e poala, e.g. "i chayk ilke poa" "try to read this book") does not presuppose ability and leaves the addressee room to decline, functioning as a milder, less direct directive (p.248–249). The same contrast holds for proposative ("let's") sentences: V-ca presupposes feasibility and is more imposing, while V-e poca merely proposes trying and is correspondingly less imposing (p.249–250).

**Interrogative ambiguity.** V-ess-na ("have you V-ed?") presupposes the addressee's ability; V-e poassna ("have you tried V-ing?") is genuinely ambiguous between two readings: the speaker, unsure whether the addressee is even capable, asking whether they attempted it at all; or the speaker, already assuming the addressee's ability, asking for their resulting impression/evaluation after doing it (p.250).

### 4.10 ssahta (쌓다) — piling up; excessive degree / excessive repetition

Main verb: to put things on top of one another (stacking bricks, firewood, books — p.251). Used as an auxiliary with both adjectives and verbs.

**4.10.1 Adjective-e ssahta.** Adjectives are inherently stative, but ssahta is dynamic; the compound denotes that a goal/resultant state has been reached *and* that this state is excessive — more than necessary relative to some purpose the speaker has in mind. "ku muulun ttukepta" ("the water is hot") is a neutral description; "ku mulun ttukewe ssahassta" ("the water became hotter than necessary") adds the speaker's judgment that it exceeds a purpose-relative threshold (p.251–252). The excessiveness reading is argued to derive directly from the main verb's "piling up" image.

**4.10.2 Verb-e ssahta.** Denotes that a process is repeated excessively/continuously — the image is of piling up repeated instances of the same event, one on top of another, and the compound typically expresses the speaker's irritation at the repetition. "ku kayka sikkulepkey cicnunta" ("the dog barks noisily") is neutral; "...cice ssahnunta" adds "...irking the speaker" (p.252–253). Cooccurrence restriction: ssahta cannot combine with predicates whose process has an inherent, non-repeatable end point once reached — "?he repeats drinking the [one particular] bottle" is awkward because a specific bottle can only be emptied once, but "he kept on drinking [wine, unbounded]" is fine (p.254).

### 4.11 tayta (대다) — bringing into contact; constant/continuous repetition

Main verb: the subject brings object X into contact with something else Y — holding a telephone receiver to the ear, a glass to the lips, a ship to the shore (p.255).

**As an auxiliary verb**, V-e tayta means the subject brings one occurrence of an action into contact with another occurrence of the same type — i.e., constant, uninterrupted repetition, with no gap between instances. Like ssahta, it typically expresses the speaker's negative attitude toward the repeated action: "ku aika mopsito wuletaynta" ("the child keeps on crying excessively"), and similarly for constant making-noise, smoking, snoring, drinking — the compound conveys that the speaker is bothered even though this attitude is not literally translatable (p.255–256).

**Comparison with ssahta.** Both auxiliaries denote repetition and both commonly express the speaker's irritation, but they differ in the underlying image: ssahta conceives of the repetition as discrete instances piled vertically on top of one another (diagrammed as a stack of circles); tayta conceives of it as a continuous, unbroken chain of linked instances with no gap between them (diagrammed as a horizontal row of touching circles) — p.256–257.

### 4.12 twuta (두다) — control-retaining placement; resultative-for-future-use

Main verb has two major subsenses (p.257):

**(i) To put something at a place under the subject's own control.** Contrasted directly with nohta: both can mean "put something at a place," but with nohta the place is understood as *outside* the subject's sphere of interest/control (ownership or responsibility relinquished), while with twuta the place is *inside* the subject's sphere (ownership/control retained). Minimal pairs: leasing a room out (sey nohta, releasing a tenant relationship from oneself) vs. taking a tenant in (sey twuta, keeping it under one's management) — p.258–259; releasing animals to grow up wild (nohta) vs. keeping domesticated animals or servants under one's charge (twuta) — p.259; keeping money/porcelain in a safe or closet (twuta, one's own possessions) vs. simply putting them down (nohta) — p.260. nohta is additionally altogether unacceptable (only twuta is possible) when the "place" in question is not really separable from the subject at all — a bank's own local branch, a school's own night session, one's own office, one's own head — because such parts cannot coherently be construed as outside the subject's own sphere (p.260–261).

**(ii) To leave something where it is, undisturbed, without removing it.** Contrasted with nohta's "put something down," which presupposes a prior event of picking the thing up: twuta can describe a state of non-disturbance that never involved any handling event at all — "look at the picture after putting it down" (nohko, presupposes it was being held) vs. "look at the picture without moving it" (twuko, it was already resting there) — p.261–262. This sense extends further to "leave something alone without touching it" (261, ex. 13) and, extended again, to **keeping something in reserve for future use**: "keep this book well and use it later" (twuesstaka, not *nohasstaka*) — nohta lacks this future-use-preparatory extension entirely (p.263). twuta is also used of distance or time "kept" or "allotted" between/for something — "100 li between [the two armies]," "three hours allotted for discussion" (p.263). Despite these real differences, nohta and twuta are interchangeable in a handful of fixed/formulaic expressions — placing game pieces in chess/baduk, padding clothing with cotton, putting grain into rice (p.263).

**4.12.1 twuta as an auxiliary verb.** Compared directly against the nohta compound (p.264): both can mark a resultant state following a completed process, but **nohta** implies the subject is no longer concerned with maintaining that result (it is "off his hands"), while **twuta** implies the subject remains concerned with preserving the result for future use. "nanun ku phyencilul sse nohassta" ("I have finished writing the letter [and set it aside]") vs. "...sse twuessta" ("I have written the letter, to keep for future use") — diagrammed as two nested-circle figures, with twuta's "subject's concern" circle fully encompassing the process→result, while nohta's is drawn as a separate, non-overlapping circle.

**Animacy/sentience restriction.** When the subject is inanimate or insentient (e.g. a cat), the twuta compound sounds distinctly odd, because such a subject cannot coherently be understood as having forward-looking concern for a result's future use — "the cat has dug up the flower bed [for future use]" and "the cat has caught a mouse [for future use]" are both marked awkward with twuta, while the plain nohta versions are natural (p.264–265). The same dichotomy is reflected in fixed proverbial expressions: an arrow, once shot, is irrevocably out of the archer's control, so only nohta (not twuta) is used of it; likewise spilled water (p.265–266).

**Change-of-state implication.** The nohta compound always implies that a change of state has taken place; the twuta compound does not always carry this implication. Example: "he had broken my car" with nohta implies the breaking itself is the salient change, while with twuta it additionally (oddly) implies the broken state is being deliberately preserved for future use, which is normally pragmatically odd (p.266). For a window "left open as it was," both nohta and twuta are grammatical but differ: the nohta version is compatible with the idea that the subject actively did something to produce that state, while the twuta version is more neutral, simply describing leaving things be (p.266–267). Similarly, "let's look at the picture after hanging it" (nohko) implies the picture is not yet hung at the moment of speaking, while "let's look at the picture, hanging it [as it already is]" (twuko) is more natural when no further change is involved (p.267).

---

## Korean — Established Grammar/Vocabulary: *A Korean Grammar on Semantic-Pragmatic Principles*, Chapter 5 "Passives"

**Source:** Keedong Lee, *A Korean Grammar on Semantic-Pragmatic Principles*, Hankook Munhwasa
(한국문화사), Seoul (publication year not visible anywhere in this chapter's pages; front matter
with a copyright page was outside this dispatch's assigned range, so left blank rather than
guessed). Chapter 5 "Passives," printed pp. 269–309 (plus blank p. 310), covering §5.0–§5.3 in
full. Vision-read from page-image renders (this PDF has no text layer and no decodable font
cipher — genuinely vision-only). PDF page → printed page mapping confirmed empirically:
`printed_left = 2×PDF_page − 2`, `printed_right = 2×PDF_page − 1` (verified at PDF pp. 136 → printed
270/271 and PDF p. 157 → printed 312/313, where printed 313 is already Chapter 6 "Negation" §6.0,
confirming Chapter 5 itself ends at printed p. 309's §5.3 Summary). The chapter opens with its own
internal table of contents (PDF p. 135, printed p. 269) — a recurring per-chapter structure in this
book, not the book's main front-matter TOC.

**Vision-reading confidence / marginalia check.** This is a clean library-quality scan throughout —
consistent typeset serif print, with only ordinary scan artifacts (binding-gutter shadow, faint
background show-through from the facing page) visible in the margins. **No handwritten marginalia,
underlining, or pencil annotation of any kind was found anywhere in this chapter's page range.**
Nearly every vocabulary item below was cross-checked across 2+ clearly legible occurrences (the
book's own argumentative method is to re-test the same verb pair across several numbered examples),
so most entries are marked `verified`; a handful of single-occurrence items, and the one `calu-ta`
'cut' instance where a 르-irregular citation form had to be reconstructed from an inflected form
rather than read directly off an isolated citation-form table, are marked `plausible_unverified`
and flagged individually in the Notes column.

**Coverage note — what was skipped as redundant vs. kept as new.** Korean's existing 46
`established/` files are dominated by pedagogical textbooks (`001`–`017` core series plus others)
that mention Korean's morphological passive infixes (-이/히/리/기-) and briefly the periphrastic
-아/어지다 passive at a beginner level — typically "this verb takes passive suffix X, here is one
example sentence." **None of that bare pedagogical-level content is re-extracted here.** This
chapter's entire actual content was treated as new, because it is not a vocabulary/pattern
inventory at all but a sustained 40-page theoretical argument never attempted at that depth in any
prior source: the systematic two-passive-system analysis (infix/"simple" passive vs.
auxiliary-`cita`/"compound" passive), the agentive-actant and instrumental-actant distinctions
(showing Korean passives structurally disallow true agent phrases, unlike the textbook-level
"X was done by Y" framing), the "passives with no active counterparts" argument, the
autonomous-vs-nonautonomous process distinction, and the final Simple-Passives-vs-Compound-Passives
and Passives-vs-Intransitives justification arguments (§5.2.4.1–5.2.4.2). Per the spec's
"incidental content words inside illustrative example sentences are not tabulated one-by-one"
convention (established in `018_korean_grammar_intl_learners_part1.md`), the vocabulary tables below
capture (a) the book's own systematic verb-formation classification table in full (§5.2.1.a, every
pair) and (b) every verb/noun/adverb/postposition that the author analyzes in depth across multiple
numbered examples as part of building the chapter's argument — not every single noun or proper name
that appears once inside a throwaway example sentence testing an already-established point.

---

## Vocabulary

### §5.0–§5.1 — Illustrative verb pairs establishing the agentive/instrumental-actant argument (printed pp. 271–284)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 잡다 / 잡히다 | capture / be captured | verb (transitive / morphological passive) | core | — | — | — | — | grammar_reference | n/a | verified | capta/caphita (book's romanization); opening example pair (p.271) establishing the active→passive object-to-subject schema. |
| 감다 / 감기다 | wind (e.g. rope around something) / be wound | verb (transitive / morphological passive) | core | — | — | — | — | grammar_reference | n/a | verified | kamta/kamkita; central example throughout §5.1.1–5.1.4 (agentive-actant, instrumental-actant tests). |
| 쏟다 / 쏟기다 | spill / be spilled | verb (transitive / morphological passive) | core | — | — | — | — | grammar_reference | n/a | verified | ssotta/ssotkita; used to test NP-eykey as locative rather than agentive in the passive. |
| 적다 / 적히다 | write down / be written down | verb (transitive / morphological passive) | core | — | — | — | — | grammar_reference | n/a | verified | cekta/cekhita. |
| 박다 / 박히다 | drive in (a nail) / be driven in | verb (transitive / morphological passive) | core | — | — | — | — | grammar_reference | n/a | verified | pakta/pakhita; also reused later (p.295, p.301) with extended senses ("penetrate," "be studded (with stars)," "be uprooted" via a different root ppop-). |
| 자르다 / 잘리다 | cut (e.g. a string) / be cut | verb (transitive / morphological passive) | core | — | — | — | — | grammar_reference | plausible_unverified | calu-ta/calli-ta; 르-irregular stem (잘랐다/잘리었다 shown inflected, not in isolated citation form) — citation form reconstructed, flagged for lower confidence than directly-read-citation-form entries. |
| 베다 / 베이다 | cut (with a blade, e.g. grass with a scythe) / be cut | verb (transitive / morphological passive) | core | — | — | — | — | grammar_reference | n/a | verified | peyta/peyiessta; used in the acceptability-asymmetry test between phul 'grass' and sonkalak 'finger' as subjects of the passive with nasey 'with a scythe'. |
| 쓰다 / 쓰이다 | use / write (homophonous pair) — be used / be written | verb (transitive / morphological passive) | core | — | — | — | — | grammar_reference | n/a | verified | ssuta/ssuyessta; author notes suta is homophonous standing for two distinct verbs 'to use' and 'to write', disambiguated only by the postposition (-lo forces 'use', -ey forces 'write(ten on)'). |
| 우히하다 (NP-에 의해서) | by means of / through (NP) | postpositional phrase | core | — | — | — | — | grammar_reference | n/a | verified | NP-ey uyhayse; §5.1.3's dedicated test case — looks like a true by-phrase but still fails to rescue clean agentivity in the passive, and creates ambiguity (ex. 12c) about who performs the action. |
| 풀리다 (cf. 풀다) | be thawed / be released (no acceptable active counterpart) | verb (morphological passive) | core | — | — | — | — | grammar_reference | n/a | verified | phullyessta; central example for §5.1.5 "Passives with no active counterparts" — nalssika phullyessta 'the weather turned warm' has no acceptable corresponding active sentence. |
| 달리다 | depend on / hang (no acceptable active counterpart) | verb (morphological passive) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | tallyessta; single-occurrence example (p.280) illustrating the same no-active-counterpart pattern. |
| 잠기다 | be sunk / be submerged (used metaphorically) | verb (morphological passive) | core | — | — | — | — | grammar_reference | n/a | verified | camkiessta; mauli etwumey camkiessta 'the village was sunk in darkness' — a metaphorical extension unavailable to the corresponding active camkwuta. |
| 뜨이다 | be seen / be noticed | verb (morphological passive) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | ttuinta; kunun yocuum nwuney an ttuinta 'he has not been seen lately'. |
| 묻히다 | be buried / be tied up (with), figuratively | verb (morphological passive) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | mwuthiessta; kunyenun kacengey mwuthiessta 'she is tied up with housekeeping' — another metaphorical-only passive use. |
| 박히다 (하늘에 별이 박히다) | be studded (with), of stars in the sky | verb (morphological passive) | core | — | — | — | — | grammar_reference | n/a | verified | pakhiessta; same root as 박다/박히다 above but this abstract/natural-phenomenon sense has no acceptable active counterpart (pakta cannot describe natural star patterns, only artificial placement e.g. in a planetarium). |
| 달리다 (성공은 노력에) | depend on (effort) | verb (morphological passive) | core | — | — | — | — | grammar_reference | n/a | verified | talliessta; sengkongun nolyekey talliessta 'success depends upon effort' — no acceptable active counterpart. |
| 틀리다 | be wrong | verb (morphological passive) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | thulliessta; Changswuuy taytapun thulliessta 'Changswu's answer was wrong' — no acceptable active counterpart (*twistled the answer' is ungrammatical/odd). |
| 씹다 / 씹히다 | chew / be chewed | verb (transitive / morphological passive) | core | — | — | — | — | grammar_reference | n/a | verified | ssipta/ssiphita; central example for §5.1.6 Negation, contrasting an and mos across voice. |
| 안 | (preverbal) negation marker | negator / particle | core | — | — | — | — | grammar_reference | n/a | verified | an; in the active it negates the agent's intention/habit; in the passive it questions whether the subject undergoes the process/quality at all — the meaning of the same marker shifts with voice. |
| 못 | (preverbal) negation marker, denotes inability/absence of process due to an external circumstance | negator / particle | core | — | — | — | — | grammar_reference | n/a | verified | mos; can occur in the active (kunun ku kokilul mos ssipnunta 'he cannot chew the meat (no teeth)') but is shown ungrammatical/odd in the corresponding passive (?ku kokinun mos ssiphinta), because mos presupposes an external responsible force that conflicts with the passive's own agentlessness. |
| 부지런히 | diligently | adverb (manner, volitional) | core | — | — | — | — | grammar_reference | n/a | verified | pwucilenhi; manner-adverbial compatibility test (§5.1.2) — acceptable with the active agentive subject, unacceptable with the corresponding passive subject. |
| 열심히 | enthusiastically / diligently | adverb (manner, volitional) | core | — | — | — | — | grammar_reference | n/a | verified | yelsimhi; same test, also reused as an example of an adverb that superficially co-occurs with both voices but shifts which participant it describes (ex. 11). |
| 고의적으로 | intentionally | adverb (volitional) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | kouycekulo; listed alongside capalcekulo as additional volitional adverbs incompatible with passive subjects. |
| 자발적으로 | voluntarily | adverb (volitional) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | capalcekulo. |
| 재빨리 | quickly | adverb (manner) | core | — | — | — | — | grammar_reference | n/a | verified | cayppalli; describes the manner of the agent's action in the active, but a different participant's manner in the passive (ex. 11). |

### §5.2.1.a — Systematic transitive-verb classification table (printed pp. 287–290)

The book's own organizing device: four classes of transitive verbs by derivational source, plus a
fifth class with no derivational relatives at all. This table is the chapter's single densest piece
of genuinely new, systematically presented vocabulary and is captured in full.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 쩍다 / 적히다 | chop / be chopped | verb (transitive / morphological passive) | core | — | — | — | — | grammar_reference | n/a | verified | ccikta/ccikhita; class (a), transitives with corresponding passives. |
| 집다 / 집히다 | pick up / be picked up | verb (transitive / morphological passive) | core | — | — | — | — | grammar_reference | n/a | verified | cipta/ciphita; class (a). |
| 끌다 / 끌리다 | draw / be drawn | verb (transitive / morphological passive) | core | — | — | — | — | grammar_reference | n/a | verified | kkulta/kkullita; class (a). |
| 막다 / 막히다 | block / be blocked | verb (transitive / morphological passive) | core | — | — | — | — | grammar_reference | n/a | verified | makta/makhita; class (a); this is the verb used repeatedly as the central example across §5.2.1–5.2.4 (kwulttwuki makhiessta vs. makaciessta). |
| 굴리다 / 구르다 | roll (transitive) / roll (intransitive) | verb (transitive / corresponding intransitive) | core | — | — | — | — | grammar_reference | n/a | verified | kwullita/kwuluta; class (b), transitives derived from intransitives — no passive form. |
| 끓이다 / 끓다 | boil (transitive) / boil (intransitive) | verb (transitive / corresponding intransitive) | core | — | — | — | — | grammar_reference | n/a | verified | kkulhita/kkulhta; class (b). |
| 올리다 / 오르다 | raise / rise | verb (transitive / corresponding intransitive) | core | — | — | — | — | grammar_reference | n/a | verified | ollita/oluta; class (b). |
| 녹이다 / 녹다 | melt (transitive) / melt (intransitive) | verb (transitive / corresponding intransitive) | core | — | — | — | — | grammar_reference | n/a | verified | nokita/nokta; class (b). |
| 좁히다 / 좁다 | narrow (transitive) / narrow (adjective) | verb / adjective (derived transitive / base adjective) | core | — | — | — | — | grammar_reference | n/a | verified | cophita/copta; class (c), transitives derived from adjectives — no passive, no intransitive. |
| 넓히다 / 넓다 | widen / wide | verb / adjective | core | — | — | — | — | grammar_reference | n/a | verified | nelphita/nelpta; class (c). |
| 굽히다 / 굽다 | bend (transitive) / bent | verb / adjective | core | — | — | — | — | grammar_reference | n/a | verified | kwuphita/kwupta; class (c). |
| 늦추다 / 늦다 | slacken (transitive) / slack | verb / adjective | core | — | — | — | — | grammar_reference | n/a | verified | nucchwuta/nukta; class (c). |
| 신기다 / 신다 | put shoes on (someone), causative / put on shoes | verb (causative / base transitive) | core | — | — | — | — | grammar_reference | n/a | verified | sinkita/sinta; class (d), causatives derived from transitives — no passive, no intransitive, but freely combines with auxiliary cita (ex. sinkieciessta 'could be put on', p.295). |
| 입히다 / 입다 | put clothes on (someone), causative / put on clothes | verb (causative / base transitive) | core | — | — | — | — | grammar_reference | n/a | verified | iphita/ipta; class (d). |
| 읽히다 / 읽다 | make (someone) read, causative / read | verb (causative / base transitive) | core | — | — | — | — | grammar_reference | n/a | verified | ilkhita/ilkta; class (d) classification entry — note this is distinct from the §5.2.4.1 example "ilkhiessta/ilkecyessta" (be read (simple) / be read (compound)), which is the morphological-passive pair of the same root, not this causative pair. |
| 씻기다 / 씻다 | make (someone) wash, causative / wash | verb (causative / base transitive) | core | — | — | — | — | grammar_reference | n/a | verified | ssiskita/ssissta; class (d). |
| 닮다 | resemble | verb (transitive, no passive/intransitive relative) | core | — | — | — | — | grammar_reference | n/a | verified | talmta; class (e). |
| 좋아하다 | like | verb (transitive, no passive/intransitive relative) | core | — | — | — | — | grammar_reference | n/a | verified | cohahata; class (e). |
| 섬기다 | respect / serve | verb (transitive, no passive/intransitive relative) | core | — | — | — | — | grammar_reference | n/a | verified | semkita; class (e); note this is a distinct lexeme from 신기다 sinkita above despite superficial romanization similarity. |
| 달래다 | soothe | verb (transitive, no passive/intransitive relative) | core | — | — | — | — | grammar_reference | n/a | verified | tallayta; class (e). |
| 다루다 | deal with / handle | verb (transitive, no passive/intransitive relative) | core | — | — | — | — | grammar_reference | n/a | verified | talwuta; class (e). |

### §5.2.2–5.2.4 — Autonomous/nonautonomous process vocabulary and the simple-vs-compound-passive argument (printed pp. 291–309)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 트다 / 트어지다 | break open (autonomous) / break open (nonautonomous, by external force) | verb (base / compound with auxiliary 지다) | core | — | — | — | — | grammar_reference | n/a | verified | thu-ta/thu-e cita; central minimal pair for §5.2.2 "Two kinds of processes" — ssaki/tongi 'bud/daybreak' (animate-adjacent, self-originating) take thu-ta only; congki/swutokwan 'boil(ailment)/water pipe' (require an external force) take thu-e cita only. See morpheme breakdown below. |
| 쌕 | bud | noun | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | ssak(i); subject of thu-ta 'the bud broke open' — an autonomous process. |
| 통 | daybreak | noun | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | tong(i); subject of thu-ta 'the day broke' — an autonomous process. |
| 종기 | boil (skin ailment) | noun | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | congki; subject of thu-e cita only — a nonautonomous process requiring an external responsible force. |
| 수도관 | water pipe | noun | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | swutokwan; subject of thu-e cita only — inanimate, not thought responsible for its own breaking (an external force such as freezing water is implied). |
| 먹다 / 먹히다 / 먹어지다 | eat / be eaten (simple passive) / be eaten (compound passive) | verb (transitive / infix passive / auxiliary-cita passive) | core | — | — | — | — | grammar_reference | n/a | verified | mek-ta/mek-hi-ta/mek-e-cita; the book's primary three-way paradigm case opening §5.2.4.1, used to introduce the simple-vs-compound meaning contrast before the larger set of minimal pairs. See morpheme breakdown below. |
| 굴뚝 | chimney | noun | core | — | — | — | — | grammar_reference | n/a | verified | kwulttwuk; repeated subject across the simple/compound-passive minimal pairs (makhiessta 'naturally blocked' vs. makaciessta 'blocked through effort', pp.285, 294–295, 308). |
| 긁히다 / 긁어지다 | be scratched (simple) / be scratched (compound) | verb (infix passive / compound passive) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | kulkhiessta/kulkecyessta; namu kaciey elkwuli kulkhiessta 'the face is scratched from the tree branch' (accidental) vs. compound (implies intent/effort). |
| 박히다 / 박아지다 | penetrate / be penetrated into (compound) | verb (infix passive / compound passive) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | pakhiessta/pakacyessta; kasika soney pakhiessta 'a thorn penetrated into the hand' — same root as 박다/박히다 above, extended sense "penetrate." |
| 걸리다 / 걸어지다 | be caught (simple) / be caught (compound) | verb (infix passive / compound passive) | core | — | — | — | — | grammar_reference | n/a | verified | kelliessta/kelecyessta; umsiki mokey kelliessta 'a piece of food was caught in the throat' (natural, nobody intends this — compound sounds very awkward here) vs. yeni cenkicwuley kelliessta/kelecyessta 'a kite was caught on a telephone line' (both acceptable: can happen by accident or on purpose). |
| 읽히다 / 읽어지다 | be read (simple) / be read (compound) | verb (infix passive / compound passive) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | ilkhiessta/ilkecyessta; i cakun kulssinun hwaktaykyengulo ilkhiessta/ilkecyessta 'this small letter was/managed to be read with a magnifying glass'. |
| 닦이다 / 닦아지다 | be cleaned/wiped (simple) / be cleaned (compound) | verb (infix passive / compound passive) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | ttakkiessta/ttakkacyessta; ku ttaynun kilumulo/kilumey takkiessta 'the dirt was cleaned with/onto oil'. |
| 밀어지다 | be pushed (attested only as compound in this example) | verb (compound passive) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | milecyessta; ku tolun cileyntey milecyessta 'the stone was pushed to the lever'. |
| 열리다 / 열어지다 | open (simple) / be opened (compound) | verb (infix passive / compound passive) | core | — | — | — | — | grammar_reference | n/a | verified | yelliessta/yelecyessta; wuni yelliessta 'we are in fortune's way' (simple only — fortune cannot be controlled, compound sounds awkward) vs. mwuni yelliessta/yellecyessta 'the door opened/has managed to be opened' (both acceptable — a door can open spontaneously or by an agent's effort). |
| 뽑히다 / 뽑아지다 | be uprooted (simple) / be uprooted (compound) | verb (infix passive / compound passive) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | ppophiessta/ppopacyessta; palamey khun namwuka ppophiessta 'because of the wind, the big tree was uprooted' (wind = a natural force, so simple passive is natural; compound sounds awkward since no other deliberate agent is implied). |
| 꺾이다 / 꺾어지다 | be broken / be down (of one's spirit), simple / compound | verb (infix passive / compound passive) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | kkekkiessta/kkekkecyessta; ku salamuy kika ceyphwuley kkekkiessta 'the man's spirit is down on itself' — paired with the spontaneity adverb ceyphwuley. |
| 풀리다 / 풀어지다 | dissolve (simple, generic/habitual) / dissolve (compound) | verb (infix passive / compound passive) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | phwullinta/phwulecinta; i pinwunun patasmwuley cal phwullinta 'this soap dissolves well in seawater' (nature of the soap) vs. compound (can be made to dissolve, implies an external causer's effort). |
| 깎이다 / 깎아지다 | sharpen (simple, generic) / sharpen (compound) | verb (infix passive / compound passive) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | kkakkinta/kkakkacinta; ku yenphilun cal kkakkinta 'the pencil sharpens well' (nature of the pencil) vs. compound ('can be made to sharpen well'). |
| 엉키다 | entangle itself (spontaneous) | verb (infix passive, no compound needed for this sense) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | elkhiessta; sili elkhiessta 'the thread entangled itself' — key example for §5.2.4.2 showing a simple passive patterning with intransitives (spontaneous, no implied agent). |
| 붙다 | stick / cling (intransitive) | verb (intransitive) | core | — | — | — | — | grammar_reference | n/a | verified | pwuthnunta; ku osun momey ccekccek pwuthnunta 'the dress sticks to the body clammily' — compared directly against the passive kamkiessta (of kamta 'wind') to show both denote equally spontaneous processes. |
| 깔리다 | be spread (of fallen leaves, over a road) | verb (infix passive) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | kkalliessta; nakyepi kiley kkalliessta 'the dead leaves spread themselves over the road' — spontaneous, no external agent implied. |
| 나가다 | go out (of a light/flame) | verb (intransitive) | core | — | — | — | — | grammar_reference | n/a | verified | nakassta; cenkipwuli nakassta 'the electric light went out' — compared against the passive pakkwiessta (of pakkwuta 'change', of a traffic signal) in §5.2.4.2's final argument; both equally resist a true agentive NP-eykey phrase. |
| 바뀌다 (cf. 바꾸다) | be changed (of a traffic signal) | verb (infix passive) | core | — | — | — | — | grammar_reference | n/a | verified | pakkwiessta (base pakkwuta 'change'); sinhotungi pakkwiessta 'the traffic signal changed' — paired with nakassta above as the chapter's closing argument that simple/infix passives function like intransitives, not like agent-demoted syntactic passives. |
| 저절로 | by itself / of its own accord | adverb (spontaneity) | core | — | — | — | — | grammar_reference | n/a | verified | cecello; one of three near-synonymous spontaneity adverbs shown compatible with simple passives but not compound passives (§5.2.4.1), e.g. kwulttwuki cecello makhiessta (acceptable) vs. ?kwulttwuki cecello makacyessta (awkward). |
| 저풀에 | of its own accord | adverb (spontaneity) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | ceyphwuley; near-synonym of cecello, same distributional test. |
| 저물에 | spontaneously | adverb (spontaneity) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | ceymwuley; third of the three spontaneity adverbs listed together (p.304); gloss and exact Hangul reconstructed from a single clearly legible but brief listing — lower-confidence entry among the three. |
| -으로 / -에 | instrumental postposition (-ulo, "active"/manipulated instrument) vs. locative/dative postposition (-ey, "static" instrument or location) | postposition / particle | core | — | — | — | — | grammar_reference | n/a | verified | -ulo vs. -ey; the chapter's key diagnostic pair for §5.1.4 and again for §5.2.4.1 — -ulo is shown to require an implied agent (hence compatible with compound passives, awkward with simple passives), while -ey denotes a static/locative relation (compatible with simple passives). Tested via swuchpuley/swuchpullo 'with/using the charcoal fire' and yenphillo/yenphiley 'with a pencil/on a pencil'. |

**Morpheme breakdown — representative compound-passive formations (agglutinative structure the
atomic gloss would otherwise hide; see `00_Word_Concept_and_Morphological_Typology_Guide.md`).**

> **먹어지다 (mek-e-cita)** = 먹- (mek-, root "eat") + -어- (-e-, connective vowel) + 지다 (cita,
> auxiliary verb "become/get") — the "compound"/periphrastic passive, glossed by the author as
> denoting a non-spontaneous process with an implied hidden agent, in contrast to the "simple"/infix
> passive 먹히다 (mek-hi-ta = mek- + -hi- passive infix + -ta).

> **막아지다 (mak-a-cita)** = 막- (mak-, root "block") + -아- (-a-, connective vowel) + 지다 (cita)
> — same compound-passive template as above; contrasted throughout the chapter against the simple
> passive 막히다 (mak-hi-ta = mak- + -hi- + -ta).

> **신기어지다 (sin-ki-e-ci-essta)** = 신- (sin-, root "wear (shoes)") + -기- (-ki-, causative infix)
> + -어- (connective vowel) + 지- (ci-, auxiliary "become") + -essta (past tense) — shows the
> compound-passive auxiliary 지다 stacking directly onto an already-causativized verb (신기다
> sinkita "put shoes on someone") that has no infix-passive or intransitive form of its own (class
> (d) in the §5.2.1.a table), which the author gives as evidence that 지다 is a fully general,
> productive mechanism while the infix passive is not.

> **굴리다 (kwul-li-ta)** = 굴- (kwul-, bound root related to "roll") + -리- (-li-, causative/
> transitivizing infix) + -ta — a class-(b) transitive derived from the intransitive 구르다
> (kwulu-ta "roll (itself)"); illustrates why this pairing has no further infix-passive form of its
> own — the intransitive already fills the "autonomous process" function the passive would
> otherwise supply.

## Grammar points

### 5.0 Introduction

The chapter opens by stating the traditional active↔passive relationship for Korean in two
generalizations: (i) the object of the active sentence becomes the subject of the passive sentence,
and (ii) the subject of the active sentence need not be expressed in the passive. The author
situates this against 1960s transformational-grammar attempts (citing work applying Chomsky's
syntactic-structures framework to Korean) to derive passive sentences from active ones by a formal
transformational rule — and states up front that the chapter's purpose is to show such a derivation
cannot be made to work "without an ad-hoc […] method" (p.271), using 순경이 도둑을 잡았다 'The
policeman captured the thief' / 도둑이 순경에게 잡히었다 'The thief was captured by the policeman'
as the opening illustrative pair.

### 5.1.1 Agentive actant

Working from Song's (1967) classification of passive sentences into those that admit agentive
phrases and those that don't, the author argues Korean passives systematically **do not** allow true
agentive phrases, which means Korean passive sentences cannot simply result from switching the
actants of the corresponding active sentence. Example: 창수가 새끼줄로 나무 둥치를 감았다 'Changswu
wound the tree trunk with a straw rope' (active, with instrumental saykkicwullo and the apparent
agentive phrase Changswueykey) has a passive 나무 둥치가 창수에게 감기었다, but Changswueykey here is
never actually interpreted as an agentive phrase — only as a locative phrase (what the sentence
denotes is "the tree trunk is wound around Changswu," a highly improbable but still what's denoted
reading). The same NP-eykey-as-locative-not-agentive pattern is confirmed across four more verb
pairs (쏟다/쏟기다, 적다/적히다, 박다/박히다, with a three-way 박다/박히다/박히다-with-wall contrast
at (5) showing that adding a second locative creates unacceptability when both postpositional
phrases compete for the same "goal" role).

### 5.1.2 Manner adverbials

Volitional manner adverbs (부지런히 'diligently', 고의적으로 'intentionally', 자발적으로
'voluntarily') that are perfectly natural in the active sentence (describing the agent's volition)
become unacceptable in the corresponding passive sentence, because the passive's subject is not
agentive and such adverbs are semantically incompatible with a non-agentive subject. Some manner
adverbs (e.g. 재빨리 'quickly') can occur in both voices, but the author shows their function
differs: in the active it describes the manner of the agent's action, while in the passive it
describes the manner of a different event altogether (e.g. the thief's own quickness in giving
himself up, not the policeman's quickness in catching him).

### 5.1.3 uyhayse

It might be argued that the passive sentence can still express an agent via the phrase NP-ey
uyhayse ('through/by means of NP'), paralleling English's by-phrase. The author tests this with 그
실이 창수에 의해서 잘리었다 'The string was cut through Changswu' and shows the uyhayse-phrase does
not behave like a clean agent-introducer: while the corresponding plain-active sentence 창수가 그
실을 잘랐다 unambiguously has Changswu as the one doing the cutting (he is the topic), the
uyhayse-passive version is genuinely ambiguous — Changswu could be the one doing the cutting, or
only indirectly involved. This ambiguity is taken as further evidence against treating Korean
passives as simple agent-demoted transformations of actives.

### 5.1.4 Instrumental actant

Instrumental phrases marked with -ulo in active sentences do not transfer cleanly into the
corresponding passive. The chapter's key diagnostic: 연필로/연필에 (yenphillo/yenphiley) — with the
verb 쓰다 (homophonous between 'use' and 'write'), -lo forces the 'use (as an instrument)' reading
while -ey forces the 'write (on)' / locative reading, and -ey is never interpreted as instrumental.
The same test is repeated with 망치로/망치에 (hammer) and 새끼줄로/새끼줄에 (straw rope), and with an
acceptability asymmetry test between 풀이 낫에 베이었다 (grass + scythe-locative, awkward, marked ?)
versus 손가락이 낫에 베이었다 (finger + scythe-locative, fully natural) — explained by whether the
subject is something that can plausibly move into incidental contact with the instrument (a finger
can; grass, fixed in place, cannot), rather than by true instrumentality. **Conclusion: with an
agent absent (as in all Korean passives), NP-lo is never interpreted as instrumental, and NP-ey is
locative, not instrumental** — instrumental interpretation of -lo requires an agent to be present or
implied in the sentence.

### 5.1.5 Passives with no active counterparts

Beyond the agentive-actant restriction, the author shows many Korean passive sentences have **no
acceptable corresponding active sentence at all** — not even with the agent slot left blank (marked
with an underscore in the source's own examples). Concrete-to-abstract/metaphorical extension cases:
날씨가 풀리었다 'the weather turned warm' (cf. 풀다 'untie', whose active sense is purely concrete —
"untying weather" is meaningless) is argued to be the general pattern: **the passive verb's semantic
range is systematically wider than its corresponding active verb's**, because passive verbs are
"more freely used metaphorically" (p.281). Additional cases: 마을이 어둠에 잠기었다 (village sunk in
darkness — metaphorical use of camkita), 그는 요즈음 눈에 안 뜨인다 (not seen lately), 그녀는 가정에
묻히었다 (buried/tied up with housekeeping), and 하늘에 별이 총총 박히었다 (sky studded with
stars — contrasted with the related verb pakta, which can describe artificial star-placement, e.g.
in a planetarium, but never natural night sky).

### 5.1.6 Negation

The preverbal negator 안 (an) is shown to shift meaning depending on the voice of the verb it
attaches to: in the active, 안 negates the agent's **intention or habit** ("he does/will not chew
the meat" — a choice); in the corresponding passive, 안 instead questions **whether the subject
undergoes the process at all**, with no implication about anyone's intention. The second negator 못
(mos), which denotes the absence of a process due to an external circumstance (e.g. "he cannot chew
the meat because he has no teeth"), is grammatical in the active but **ungrammatical/odd in the
corresponding passive** — because 못 presupposes some external force responsible for the absence,
which directly conflicts with the passive's own built-in exclusion of an expressible agent.

### 5.1.7 Summary

The chapter's first half closes with four stated findings: (1) the agentive actant cannot occur in
the passive, although it occurs freely in the corresponding active; (2) the active-passive
relationship is not one-to-one — many passives lack corresponding actives and vice versa; (3) the
range of meanings denoted by an active verb is generally far narrower than that of its corresponding
passive verb; (4) the negator 못 can occur in the active but not in the corresponding passive,
while 안 occurs in both but with different meanings depending on voice.

### 5.2 Meanings of the two passives in Korean

The chapter's second half states its central thesis: Korean has two passive-forming mechanisms — the
unproductive infix passive (-이/히/리/기-) and the fully productive periphrastic passive formed with
the auxiliary verb 지다 (cita) — which have traditionally been treated as synonymous but which the
author argues are **not**. The infix passive denotes spontaneous/accidental processes; the auxiliary
(-아/어지다) passive denotes processes carried out intentionally / brought about with effort. This is
introduced with the central minimal pair 굴뚝이 막히었다 ('the chimney was blocked up [naturally]')
vs. 굴뚝이 막아졌다 ('the chimney was managed to be blocked [through some effort]').

### 5.2.1.a Transitive Verbs

To set up the distributional argument, the author first classifies Korean transitive verbs by
derivational source into five classes (full vocabulary captured in the table above): (a) transitives
with a corresponding infix passive; (b) transitives derived from an intransitive verb (no passive of
their own); (c) transitives derived from an adjective (neither passive nor intransitive); (d)
causatives derived from a transitive verb (neither passive nor intransitive, but freely combinable
with the auxiliary 지다); (e) transitives with no passive and no intransitive relative at all.

### 5.2.1.b Distribution

Restricting attention to the first three classes, the author tabulates a complementary-distribution
pattern: a transitive verb either has a passive OR a corresponding intransitive, essentially never
both (table (2), p.290: 막다 has a passive 막히다 but no intransitive; 굴리다 is derived from the
intransitive 구르다 but has no passive; 좁히다 is derived from the adjective 좁다 and has neither).
Crucially, the auxiliary verb 지다 can combine with **all** of these transitive types regardless of
which slot (passive or intransitive) is independently available — setting up the question pursued in
§5.2.2–5.2.3: is this distributional gap systematic, or accidental?

### 5.2.2 Two kinds of processes

The author proposes the gap reflects a deeper semantic split between **autonomous processes**
(believed to take place "in itself," attributable to the nature of the subject — no external force
needed) and **nonautonomous processes** (believed to require an outside agent or force). The
diagnostic case: 트다 (thu-ta, 'break open') is compatible with 싹 'bud' and 동 'daybreak' (both
treated as self-originating, hence autonomous) but **not** with 트어지다 (thu-e cita); conversely 종기
'boil (ailment)' and 수도관 'water pipe' require 트어지다 and reject plain 트다, because these are
not thought capable of responsibility for their own "breaking" — an external force (e.g. freezing
water pressure, for the pipe) is implied. A further nuance: 손이 트었다 'the hand is chapped' uses
plain thu-ta even though chapping has an external cause (cold weather), because the *result* is
attributed to the hand's own nature, whereas 손이 트어졌다 implies the break was brought about by a
separate external force such as being struck.

### 5.2.3 A new pattern

Building on §5.2.2, the author reorganizes the earlier distribution table (2) into a new table (5)
with three columns — **Transitive / Autonomous / Nonautonomous** — collapsing the earlier separate
"Passive" and "Intransitive" columns into one shared "Autonomous" column, since both the infix
passive and the corresponding intransitive are now understood to perform the same function (denoting
an autonomous process). Causative-derived transitives like 신기다 (sinkita, class (d)) have **no**
Autonomous-column entry at all — only a Nonautonomous (지다-compound) entry — because a causative
event, by definition, inherently requires an external causer and can never be construed as
autonomous.

### 5.2.4 Justification

A short transitional section stating the plan for the remainder of the chapter: directly compare the
simple (infix) and compound (auxiliary 지다) passives of the *same* verb, in the cases where both
forms independently exist, to justify the autonomous/nonautonomous distinction with systematic
minimal-pair evidence rather than the isolated cases given so far.

### 5.2.4.1 Simple Passives and Compound Passives

The chapter's longest and most argument-dense section (pp.294–306). Central paradigm: 먹다/먹히다/
먹어지다 ('eat'/simple passive/compound passive) — syntactically near-identical (both take the
transitive's object as their subject), but the author builds a dense set of minimal pairs (full list
in the vocabulary table above: 긁히다/긁어지다, 박히다/박아지다, 걸리다/걸어지다, 읽히다/읽어지다,
닦이다/닦아지다, 열리다/열어지다, 뽑히다/뽑아지다, 틀리다/틀다, 풀리다/풀어지다, 쌓이다/쌓아지다,
보이다/보아지다, 들리다/들어지다, 꺾이다/꺾어지다) to show the compound passive systematically
implies **(1)** the speaker wants the process to occur, **(2)** some difficulty in bringing it about,
and **(3)** a hidden agent responsible for it — while the simple passive implies none of these,
denoting a spontaneous process for which the subject itself is treated as responsible.

Three independent lines of evidence are offered. First, **acceptability with natural-phenomenon and
perception predicates**: 운이 열리었다 'we are in fortune's way' is natural but the compound ?운이
열어졌다 is awkward, because fortune cannot be deliberately controlled — the same split is shown for
바람에 나무가 뽑히다 (wind uprooting a tree, natural force, simple-only) and for perception verbs 보다
'see'/들다 'hear' (눈 앞에 큰 산이 보이었다 vs. awkward compound), on the grounds that humans cannot
control what they perceive. Agentive readings of the same verbs (보다 used as "read (for two
hours)," 듣다 as "listen attentively") *do* admit natural compound passives (책이 두 시간 만에 다
보아졌다 'the book was managed to be read in two hours'), confirming the agent-implication claim
directly.

Second, **spontaneity adverbs**: 저절로/저풀에/저물에 ('by itself'/'of its own accord'/
'spontaneously') can modify simple passives but not compound passives (굴뚝이 저절로 막히었다 natural
vs. ?굴뚝이 저절로 막아졌다 awkward) — because these adverbs are semantically redundant/contradictory
with a process the compound passive already marks as non-spontaneous.

Third, **the instrumental postposition test**, directly reusing the -ulo/-ey distinction from
§5.1.4: -ulo (an "active instrument," implying an agent manipulating it) is shown more natural with
compound passives, while -ey (a "static instrument," not requiring an agent) is more natural with
simple passives — tested via 숯불로/숯불에 (charcoal fire) and 모래주머니로/모래주머니에 (sandbags),
directly linking the hidden-agent claim about compound passives back to the instrumental-actant
machinery built up in §5.1.4.

The section concludes with the chapter's clearest summary statement (ex. 19, p.300): **simple
passive = denotes a spontaneous process, subject regarded as responsible for it; compound passive =
denotes a non-spontaneous process, with some hidden agent regarded as responsible for it.**

### 5.2.4.2 Passives and Intransitives

The final argument (pp.306–309) reframes the simple/infix passive as functionally closer to an
**intransitive verb** than to a "true" syntactically-derived passive. Evidence: 실이 엉키었다 'the
thread entangled itself' and 치마가 몸에 친친 감기었다 'the skirt wound itself on the body' (a
morphological passive of 감다) are both spontaneous, agentless processes despite one being
morphologically plain and the other morphologically passive — paralleled directly against the
intransitive 붙다 'stick/cling' (그 옷은 몸에 적적 붙는다 'the dress sticks to the body clammily'),
which patterns identically. The closing pair — intransitive 나가다 'go out (of a light)' vs. passive
바뀌다 'be changed (of a traffic signal, from 바꾸다)' — shows both resist a true agentive NP-에게
phrase in exactly the same way (?전기불이 순경에게 나갔다 and ?신호등이 순경에게 바뀌었다 are both
rejected), the chapter's final piece of evidence that the simple/infix passive belongs functionally
with intransitives rather than with agent-demoted syntactic passives.

### 5.3 Summary

Korean has two kinds of passives: one formed with the infix (-이, -히, -기, -리) and the other with
the auxiliary verb 지다. The main difference is that the infix passive denotes spontaneous processes
and the 지다-passive denotes non-spontaneous processes; it is further shown that the infix passive is
functionally close to intransitive verbs in nature.

---

## Korean — Established Vocabulary/Grammar: Chapter 6 "Negation"

**Source:** Keedong Lee, *A Korean Grammar on Semantic-Pragmatic Principles*, Hankook Munhwasa
(한국문화사), Seoul (publication year not visible in this chapter's pages — no printed year appeared
in the printed-page-313-337 range; front matter would need to be checked separately if needed).
Chapter 6 "Negation," printed pages 313-337 (covers §6.0 Introduction, §6.1 *an* and *mos*
contrasted, §6.2 Two negation constructions [§6.2.1 post-verbal construction, §6.2.2 *ci* and its
basic meaning — §6.2.2.1 matrix sentence, §6.2.2.2 embedded sentence, §6.2.2.3 post-verbal negation],
§6.3 Distinction between pre-verbal and post-verbal negation [§6.3.1 Assertion, §6.3.2 Question,
§6.3.3 Imperative, §6.3.4 Delimiters], §6.4 Summary). Source is a vision-only scan (no text layer);
read from rendered page images `page-156.png` through `page-170.png` (the last confirming Chapter 7
"Nominalization" begins at printed p.339, so Chapter 6 runs cleanly through p.337 with p.338 blank).

**Coverage note — non-redundant supplement.** Korean already has 46 established/ extraction files,
mostly pedagogical textbooks that cover the *beginner-level* 안 (short-form, preverbal) vs. -지 않다
(long-form, postverbal) distinction, and 못/-지 못하다 for inability. That bare pedagogical framing
("there are two ways to say 'not'; here's how to conjugate them") is **not** re-extracted here — it
adds nothing. What **is** new and kept in full is this book's distinctive theoretical content: (1)
the systematic semantic account of *an* vs. *mos* as "internal" vs. "external" negation markers,
including the subtler preverbal-stative restriction and its pragmatic explanation; (2) the central
and genuinely novel claim that the morpheme *ci* itself carries one unified basic pragmatic
meaning — "speaker assumes the listener is aware of / inclined to accept the propositional
content" — across three superficially different environments (matrix speech-act marker, embedded
complementizer/dependent noun, and post-verbal negation), which most Korean grammarians treat as
unrelated homophones; and (3) the resulting claim that pre-verbal and post-verbal negation are *not*
free variants but differ systematically across assertion, question, imperative, and delimiter
(particle co-occurrence) contexts. Essentially all of this chapter's argumentative content is treated
as new; only the opening schematic ("there are two markers, two positions") is standard and not
belabored. **No handwritten marginalia was found anywhere in the vision-read page range (images
page-156 through page-170) — all pages were clean, consistently typeset printed source.**

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| an (안) | not (negation marker) | adverb/negation particle | core | — | — | — | — | grammar_reference | n/a | verified | Preverbal negation marker; argued to mark "internal"/agent-willed absence of state or process; can occur with any predicate preverbally; incompatible with imperatives; incompatible with delimiters like -to in negation (*anto poassta ungrammatical); pp.313-337 passim. |
| mos (못) | cannot / not (due to external factors) | adverb/negation particle | core | — | — | — | — | grammar_reference | n/a | verified | Preverbal/postverbal negation marker; argued to mark "externally"-caused absence; preverbal use with stative predicates is marked marginal/questionable (?mos yeypputa) though not flatly ungrammatical; fully acceptable postverbally with statives (nekulepci moshata) for subjective value judgments; compatible with negative imperatives, unlike an; pp.313-337. |
| ci (지) | post-verbal negation morpheme; complementizer; dependent noun; "suspective" speech-act marker | bound morpheme/particle | core | — | — | — | — | grammar_reference | n/a | verified | Central term of the chapter. Author argues all occurrences of ci (matrix speech-act marker, embedded complementizer/dependent-noun, and the ci of V-ci an/mos hata postverbal negation) share one basic pragmatic meaning: speaker assumes the listener is aware of, or inclined to accept, the propositional content. Most Korean grammarians treat these as unrelated homophones; this chapter argues against that. pp.319-327. |
| kes (것) | fact, the case that... (nominalizing dependent noun) | dependent noun | core | — | — | — | — | grammar_reference | n/a | verified | Appears in the V-un kes an/*mos ita construction, negating a nominalized ("it is not the case that...") clause; only an occurs in this construction, mos does not (?...kesi mos ita flagged questionable); p.313. |
| anita (아니다) | is not, be not | negative copula | core | — | — | — | — | grammar_reference | n/a | verified | Used in the kes-anita construction and, broken out structurally, as the speaker's explicit denial component of post-verbal ci-negation (e.g. "그는 간 것이 아니다" analyzed as [listener's presumed belief] + [speaker's denial]); pp.313, 326-327. |
| hata (하다) | do (support/light verb) | verb | core | — | — | — | — | grammar_reference | n/a | verified | Support verb following ci in the post-verbal negation schema VERB-ci an/mos hata; p.313. |
| ita (이다) | be (copula) | copula | core | — | — | — | — | grammar_reference | n/a | verified | Grouped with issta and hata as modality verbs expressing differing degrees of certainty about the relation between a proposition and reality; ita denotes the stronger certainty of the three. p.327. |
| issta (있다) | exist, be (located/present) | verb | core | — | — | — | — | grammar_reference | n/a | verified | Grouped with ita/hata as a modality-bearing verb (see above); p.327. |
| -ta (다) | assertive sentence-final marker | speech-act suffix | core | — | — | — | — | grammar_reference | n/a | verified | Used when the speaker imparts information assumed unknown to the listener; part of a 5-member speech-act-marker set (-ta/-ci/-na/-la/-ca) the author uses to situate ci's meaning; p.320-321. |
| -na (나) | dubitative marker | speech-act suffix | core | — | — | — | — | grammar_reference | n/a | verified | Marks that the speaker himself does not know whether a proposition is true; contrasted with -ta and -ci; p.320-321. |
| -la (라) | imperative marker | speech-act suffix | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | Listed in the chapter's speech-act-marker inventory; not elaborated further within this chapter (imperative negation is instead treated via mos/an + malla, see Grammar points). p.321. |
| -ca (자) | propositive (hortative) marker | speech-act suffix | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | Listed in the same inventory; not elaborated further in this chapter. p.321. |
| -nun / -un (는/은) | topic delimiter | delimiter particle | core | — | — | — | — | grammar_reference | n/a | verified | One of the delimiters (-nun/-to/-man/-na) shown to co-occur with post-verbal but not pre-verbal negation; p.334. |
| -to (도) | also, even | delimiter particle | core | — | — | — | — | grammar_reference | n/a | verified | Marks the element it attaches to as being in focus; shown incompatible with preverbal an (*그는 그것을 안도 보았다 "anto poassta" flagged ungrammatical) but freely compatible with postverbal ci-negation (pocito moshaysseyo); this co-occurrence asymmetry is used as direct syntactic evidence that postverbal negation, unlike preverbal, can put a non-verb element in focus. pp.334-336. |
| -man (만) | only | delimiter particle | core | — | — | — | — | grammar_reference | n/a | verified | Shown co-occurring with postverbal negation in imperative-like delimiter examples (e.g. cwukci/man malala "please don't [even] die"); p.334. |
| mekta (먹다) | eat | verb (action) | core | — | — | — | — | grammar_reference | n/a | verified | Worked example contrasting an meknunta ("won't eat," internally caused) vs. mos meknunta ("can't eat," externally caused, e.g. no food/no time/discomfort) — both fully grammatical with an action verb; p.316. |
| elta (얼다) | freeze | verb (process, non-agentive) | core | — | — | — | — | grammar_reference | n/a | verified | Process-verb example; an elessta is fully grammatical, ?mos elessta is flagged marginal even though freezing is externally caused (temperature, location, etc.) — author notes preverbal an instead attributes the non-freezing to the water itself; p.317. |
| yeypputa (예쁘다) | be pretty | adjective (stative) | core | — | — | — | — | grammar_reference | n/a | verified | Stative-predicate example: an yeypputa is fully grammatical, ?mos yeypputa is marked marginal preverbally — core evidence for the "mos resists statives preverbally" distributional claim; pp.313-314. |
| kkaykkushata (깨끗하다) | be clean | adjective (stative) | core | — | — | — | — | grammar_reference | n/a | verified | Parallel stative example to yeypputa (an kkaykkushata vs. ?mos kkaykkushata); p.314. |
| maypta (맵다) | be hot/spicy | adjective (stative) | core | — | — | — | — | grammar_reference | n/a | verified | Stative example (quality of a pepper) used to probe the preverbal an/mos contrast further — both an and mos are allowed but marked with differing acceptability in the text; p.316. |
| chata (차다) | be cold | adjective (stative) | core | — | — | — | — | grammar_reference | n/a | verified | Paired stative example with maypta (quality of beer); p.316. |
| nekulepta (너그럽다) | be generous (of heart/disposition) | adjective (stative) | core | — | — | — | — | grammar_reference | n/a | verified | Used to show mos becomes fully acceptable postverbally with a stative predicate (nekulepci moshata) for a subjective value judgment, even though ?mos nekulepta is marginal preverbally; pp.317-318. |
| pwucilenhata (부지런하다) | be diligent | adjective (stative) | core | — | — | — | — | grammar_reference | n/a | verified | Same preverbal-marginal/postverbal-acceptable pattern as nekulepta; p.318. |
| cohta (좋다) | be good | adjective (stative) | core | — | — | — | — | grammar_reference | n/a | verified | Same pattern; author notes the postverbal mos-forms here are glossed "according to the speaker's opinion," framing postverbal stative negation as inherently subjective/evaluative; p.318. |
| ceyal (제발) | please (pleading) | adverb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | Appears once in a delimiter example: "ceyal cwukci/man malala" ("please don't [even] die"); p.334. |
| cwukta (죽다) | die | verb (action) | core | — | — | — | — | grammar_reference | n/a | verified | Used in negative-imperative/delimiter examples; p.334. |
| malta (말다) | stop (doing), don't (negative-imperative auxiliary) | auxiliary verb | core | — | — | — | — | grammar_reference | n/a | verified | Forms the postverbal negative imperative together with ci (V-ci malla, "don't V"), contrasted with the preverbal-style mos-imperative (V-ci moshay / mos V); author argues V-ci malla is pragmatically less abrupt because it's grounded in the listener's own expressed/assumed intention rather than direct observable evidence. pp.332-334. |

No morpheme-breakdown entries were needed for this chunk: the chapter's own content is already
analyzed at the morpheme level (individual particles/markers), so none of the vocabulary items above
are composed forms whose atomic gloss would hide further internal structure.

## Grammar points

### 6.0 Two negation markers, two positions (overview)

Korean has exactly two negation markers, *an* and *mos*, each of which can appear in either of two
structural positions: **preverbal** (`an`/`mos` VERB) or **postverbal** (`VERB-ci an`/`mos hata`).
The chapter's stated purpose is twofold: (1) distinguish the *meanings* of `an` vs. `mos`, and (2)
distinguish the *functions* of the preverbal vs. postverbal constructions — which the literature has
generally treated as free variants without a serious semantic account. (p.313)

### 6.1 *an* and *mos* contrasted: internal vs. external negation

The two markers have different co-occurrence restrictions: `an` can combine with any predicate, but
`mos` cannot comfortably combine preverbally with **stative** predicates (adjectives of quality, e.g.
*yeypputa* "be pretty," *kkaykkushata* "be clean") — `?mos yeypputa` is marked marginal, not fully
ungrammatical. With **nonstative** (action/process) predicates, both markers freely occur preverbally
with no such restriction.

The author's semantic account: both markers imply **absence** (of state, process, or action), but
they differ in how the absence is attributed. `an` is the **internal negation marker** — it is used
when the nonoccurrence is attributable to factors internal to/controllable by the agent (the agent's
own will or decision). `mos` is the **external negation marker** — it marks nonoccurrence caused by
factors external to the agent's will (e.g. lack of resources, physical inability, outside
circumstance). This explains the action-verb data: *an meknunta* "won't eat" (agent's choice) vs.
*mos meknunta* "can't eat" (prevented by circumstance) — both grammatical, genuinely different
meanings, not free variants.

This also explains the *stative*-predicate restriction: a stative predicate (a quality like
prettiness or cleanliness) is inherently a property of the entity itself, not something an outside
factor straightforwardly "prevents" — so `mos`, whose semantics requires an external causer, fits
awkwardly with statives preverbally. The non-agentive process verb *elta* "freeze" is presented as a
test case: although freezing is plausibly externally caused (temperature, wind, location), `?mos
elessta` is still marked marginal — the author argues preverbal `an` instead attributes the
nonoccurrence to the water itself (treating it as quasi-inherent), which is why `an` rather than
`mos` is the natural choice even for an externally-triggered process like freezing. (pp.313-317)

Crucially, in the **postverbal** position, `mos` loses this restriction and freely combines with
statives: *nekulepci moshata*, *pwucilenhaci moshata*, *cohci moshata* are all fully acceptable. The
author explains these as **value judgments** — the absence of the quality is measured against the
*speaker's own subjective norm or standard*, not the entity's inherent nature, which is why the
postverbal mos-statements are consistently glossed "...according to the speaker's opinion." (p.318)

### 6.2.1 The post-verbal construction

Postverbal negation is built with the morpheme `ci` plus `an`/`mos` plus `hata`: VERB-`ci` `an`/`mos`
`hata` (e.g. *yeyppuci anhta* "is not pretty"). Korean grammarians have generally treated this `ci`
simply as a complementizer, without noticing that the same morpheme shows up in other, superficially
unrelated environments — which the rest of §6.2 sets out to unify. (p.319)

### 6.2.2.1 *ci* as a matrix speech-act marker

The chapter situates `-ci` among a small set of Korean sentence-final morphemes tied to speech acts:
`-ta` (assertive — speaker imparts information assumed unknown to listener), `-ci` (treated as
partly assertive, partly dubitative), `-na` (dubitative — speaker doesn't know if the proposition is
true), plus `-la` (imperative) and `-ca` (propositive), listed for completeness but not elaborated
further here.

`-ci` sits between the assertive and dubitative poles: the speaker uses it when he assumes the
**listener** already believes, or is leaning toward believing, the propositional content — it can be
used as either a question or an answer. Example: *Chelswu ne ecey yenghwa kwukyeng kassci?* ("Chelswu,
you went to see a movie, didn't you?") is not a neutral question but a **biased** one, used to confirm
a suspicion the speaker already holds, contrasted directly with the neutral `-ni` question *...
kassni?* ("did you go...?"), which carries no such listener-assumption. The book represents this with
a balance/scale diagram (Figure 1): the speaker's assumption is weighted toward the positive
proposition (+P) and toward the listener (L) also holding that belief.

A second worked example (*ne swukcey ta hassna?* / *kulem ta hassci* "Of course I did, as you
assume") and its accompanying diagram (Figure 2) generalizes the pattern: `-ci` is used when the
speaker assumes the addressee of the original question already knows/believes the answer, making the
question itself in some sense superfluous — summarized as: **the speaker uses the suspective `ci`
form when he assumes the listener already believes in the truth of the information conveyed.**
(pp.320-323)

### 6.2.2.2 *ci* as complementizer / dependent noun in embedded sentences

`ci` also appears in embedded sentences, either as a complementizer (*ku salami onunci
molukeyssta* "I don't know whether he is coming") or as a dependent noun (*ku salami onci samnyeni
toyessta* "three years have passed since he came"). Despite the different syntactic distribution from
the speech-act-marker use, the author argues the **pragmatic function is the same**: in both cases
`ci` signals that the speaker assumes the listener is already aware of the particular
information/propositional content being conveyed. Evidence: sentences built on this `ci` (e.g. "three
years have passed since he came") are not natural discourse-initial utterances — they presuppose the
listener already knows the embedded fact ("he came") and are typically used as *answers* rather than
opening statements, exactly paralleling the listener-awareness presupposition found in the matrix
speech-act use. (pp.323-325)

### 6.2.2.3 *ci* in post-verbal negation, unified with the other uses

The chapter then explicitly connects the negation-construction `ci` back to the two uses just
established. Its claim: the pragmatic function of `ci` in post-verbal negation is not different from
its function as a matrix speech-act marker. The speaker uses post-verbal negation (with `ci`) when he
himself believes the negative information, *and* assumes the listener is already aware of, and likely
committed to the truth of, the corresponding **affirmative** proposition — i.e., postverbal negation
characteristically denies something that has supposedly already been affirmed, assumed, or believed by
the listener (sometimes erroneously).

The author formalizes this by splitting a postverbal negative sentence into two parts: (a) the
propositional content the speaker thinks the listener firmly believes (e.g. *kunun kan kesi* "that he
went"), and (b) the speaker's denial of that belief (*anita*, "is not [the case]" / "you're wrong").
This is explicitly compared to the parallel case with `hata`/`issta` vs. `ita`: the three verbs *ita*
"be," *issta* "exist," and *hata* "do" are used to express modality (the relation between a
proposition and reality) with differing degrees of certainty, `ita` denoting the strongest. (pp.325-327)

### 6.3.1 Assertion: preverbal negation presupposes nothing, postverbal negation presupposes/denies

In assertions, preverbal negation does **not** presuppose any assumption about the listener's
knowledge/awareness — it simply reports new information. Postverbal negation **does** carry such a
presupposition, specifically that the listener holds (or might hold) a contrary belief, which the
speaker is denying.

Worked examples: a student unable to read a professor's blackboard writing, where "not being visible"
is wholly new information to the professor, naturally uses the preverbal form (*kulssika an
poipnita*) — no presupposition is appropriate. But if the professor *writes something specifically
and asks the student to read it*, the postverbal form (*poici ansupnita*) becomes more appropriate,
because the professor's request presupposes he assumed the student *could* read it, and the student is
denying that assumption. A second example (a stopped watch taken to a repair shop) makes the same
point: the preverbal form (*an kase*) reports new information to the repairman; the postverbal form
(*kaci anase*) presupposes the repairman's prior claim/belief that the watch worked, and denies it.
General rule stated: **preverbal negation is used in monologue-like contexts where the speaker is not
assuming anything about the listener's prior belief**; postverbal negation denies an assumption
already attributed to the listener. (pp.327-329)

### 6.3.2 Question: diverging illocutionary force

Unlike in assertions, the two negation types are easy to tell apart in questions because they carry
genuinely different illocutionary force. A preverbal negative question (*ne onul hakkyoey an kani?*
"Aren't you going to school today?") expresses the speaker's own doubt or surprise at a conflict
between his prior expectation and present evidence — it genuinely seeks to know whether the negative
proposition holds. A postverbal negative question (*...kaci anhni?* "You're going to school today,
aren't you?") is **not** seeking to know the truth of the negative at all — instead it solicits the
listener's acceptance or rejection of a proposition the speaker is already inclined to believe is
true, much like the `-ci` suspective pattern from §6.2.2.1.

A retort example makes the asymmetry vivid: told to study (*ne kongpwuhayla*), a listener who is
already studying retorts with postverbal negation (*na kongpwuhako isscanha!* "I AM studying, aren't
I?"), presupposing the speaker should already know this — contrasted with the preverbal retort (*na
kongpwu an hako isse!*), which does not carry that presupposition. Several further matched pairs
(e.g. "stop eating"/"I'm not eating" exchanges) reinforce the same pattern: a double-negative
response using *an* twice in a row (`?an mekko an isse`) is flagged unacceptable, underscoring that
the two forms are not interchangeable repair strategies. (pp.329-333)

### 6.3.3 Imperative: *mos* is compatible with negative imperatives, *an* is not

`mos` can form a negative imperative (*mos kaa!* "Don't go!", *kaci moshay!* "You can't go!"); `an`
cannot be used this way (*an ka* / *kacianha* are statements, not imperatives, even though
grammatically well-formed). The author ties this directly back to the internal/external semantic
account: imperatives impose the speaker's will upon the listener from the outside — i.e., an
externally-sourced constraint — which is compatible with `mos`'s "external" semantics but
incompatible with `an`'s "internal/agent-willed" semantics (an imperative cannot coherently claim the
addressee's own internal will is the source of the prohibition).

Comparing the two postverbal-style negative imperatives, the preverbal-flavored *mos kaa!* sounds
markedly more abrupt than the postverbal *kaci malla* (don't go), because *mos kaa!* is grounded in
direct observable evidence of the listener's action, while *kaci malla* is grounded in the speaker's
assumption about the listener's own already-expressed or inferred intention — paralleling the
assertion/question asymmetry from §6.3.1-2. A worked scenario (a father forbidding his son from
reading D.H. Lawrence's *Sons and Lovers*) is used to illustrate when each form is pragmatically
appropriate: the abrupt direct-command form when there's no prior claim at issue, versus the
postverbal form when rebutting a claim the son has already made (e.g. "I'm old enough to read it").
(pp.332-334)

### 6.3.4 Delimiters: postverbal negation, not preverbal, allows focus particles

A clear syntactic diagnostic separating the two constructions: delimiter particles such as `-nun`,
`-to`, `-man`, `-na` can attach inside the postverbal negation construction (*pocito/nun moshaysseyo*
"didn't even/also see it") but **cannot** attach to the preverbal construction — `*kukesul anto
poassta` is flagged ungrammatical. The explanation given: `-to` marks the element it attaches to as
being **in focus**, but the verb cannot be put in focus under preverbal negation, so preverbal
negation is only natural when some element *other than* the verb is in focus (demonstrated with
quantifier-focused question/answer pairs like *hanato mos phalassupnita* "I haven't sold even one" vs.
plain preverbal answers *hanmyengto an oasseyo* "not even one person came").

This delimiter-compatibility asymmetry is also exploited pragmatically to **deny a presupposition**
implied by an interlocutor's prior utterance — several conversational-exchange examples show a
speaker using `V-ci-to moshay(ss)eyo` ("I haven't even V-ed") specifically to reject a chain of
assumptions embedded in the first speaker's question (e.g. denying "ate candy" by denying the even
more basic presupposed step "saw it" at all), something the preverbal construction cannot do in the
same context. (pp.334-337)

### 6.4 Summary

Korean negation works in four interacting dimensions: (1) two negation morphemes, `an` (internal —
absence determined by the agent/entity itself) vs. `mos` (external — absence caused by outside
factors); (2) two structural positions, preverbal and postverbal, which the literature generally
treats as synonymous but which this chapter argues are systematically different — the postverbal
construction being "more involved" both semantically and pragmatically, and commonly used specifically
to deny something the addressee holds or is thought to hold. (p.337)

---

## Korean — Established Grammar/Vocabulary: Keedong Lee, *A Korean Grammar on Semantic-Pragmatic Principles*, Hankook Munhwasa (한국문화사), Seoul (publication year not visible on any page in this chunk) — Chapter 7 "Nominalization," pp. 341–377

**Source:** Keedong Lee, *A Korean Grammar on Semantic-Pragmatic Principles*. Vision-read from scanned
page images (no text layer, no decodable font cipher — genuinely vision-only). Chapter 7 covers
§7.0 Introduction, §7.1 Review of relevant studies, §7.2 Types of nominalizations (§7.2.1 -ki,
§7.2.2 -um), §7.3 Some grammatical morphemes with ki (kela, ketun, kena, key, key-adverbializer),
§7.4 Some further justifications (verb-ki verb-ta, -ki hata). Chapter ends at printed p. 377 (p.
378 appears blank; Chapter 8 "Tense-Aspect-Modality" begins its own section with a title/TOC page
immediately after). Romanization is the book's own Yale-like system (ey/ay/yey digraphs, doubled
consonants, no macrons), reproduced as printed.

**Coverage note — non-redundant supplement.** This language already has 46 established/ files, many
of them pedagogical textbooks that mention -기(-ki) and -음(-um) as nominalizer suffixes at a beginner
level with a bare rule-of-thumb ("-기 is used before certain verbs, -음 before others") but essentially
no real semantic account of *why* one is chosen over the other. **That bare pedagogical rule-of-thumb
is treated as already covered and is NOT re-extracted here.** What this chapter contributes that is
genuinely new and is extracted in full:

- The book's central theoretical claim (explicitly flagged in its own preface as one of the hardest
  problems motivating the whole book): Korean's three nominalizers (-i, -ki, -um) map onto Lyons'
  (1978) three-way ontological classification of entities (first-/second-/third-order), independently
  corroborated by Givon (1979) and Vendler (1968) — not previously captured anywhere in this dataset.
- The full review-of-relevant-studies argument (§7.1), including the diagnostic predicate tests used
  to tell first-/second-/third-order nouns apart.
- The semantic characterization of -ki as an "existence marker" (actual or potential existence of a
  second-order entity — action/process/event/state) versus -um as marking "propositional content"
  (a third-order entity, outside space and time, assertable/deniable) — this is the actual mechanism,
  not a rule-of-thumb, and is new.
- The full set of co-occurrence-restricted predicate lists that diagnose -ki vs -um compatibility
  (§7.2.1–7.2.2) — not elsewhere in this dataset.
- The grammaticalized ki-morpheme family (§7.3): kela, ketun, kena, key (causative/goal), and key
  (adverbializer), each analyzed as containing the same existence-marker -ki fused with another
  morpheme (-ela, -etun, -una, -ey respectively) — a genuinely novel grouping not found in any prior
  Korean extraction in this project.
- §7.4's further justification data (the verb-ki verb-ta emphatic-dispute construction; the -ki hata
  vs -um...cil hata distinction; compound-noun-formation constraints based on nominal order).

**Vision-reading guard:** all 19 page-images read for this chunk (pages 341–377, plus boundary checks
at the chapter-7 TOC page and the chapter-8 TOC page) show consistent, clean, legible typeset print
throughout. **No handwritten marginalia, underlining, or pencil annotation of any kind was found on
any page in this range.**

---

## Vocabulary

Note on morpheme breakdowns: Korean is agglutinative, so many "vocabulary items" below are themselves
composed forms (stem + nominalizer, or nominalizer + further suffix). Per the morphological-typology
convention, a breakdown is given beneath any row where the atomic gloss would hide real compositional
structure; simple underived lexical stems are not broken down.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| salta (살다) / sali (살이) / salki (살기) / salm(삶) | 'live' / 'utensil' / 'to live' / 'life' | verb / noun / nominalized verb / noun | core | — | — | — | — | grammar_reference | n/a | verified | §7.2, ex.(10): first-order (-i, lexicalized), second-order (-ki, productive), third-order-like lexicalized (-um) forms of one root, illustrating the 3-way split |
| tatta (닫다) / mitati (미닫이) / tatki (닫기) / tatum (닫음) | 'close' / 'sliding door' / 'to close' / 'closure' | verb / noun / nominalized verb / noun | core | — | — | — | — | grammar_reference | n/a | verified | ex.(11) |
| usta (웃다) / usey (웃에) / uski (웃기) / usum (웃음) | 'laugh'(V) / 'laughable act' / 'to laugh' / 'laugh'(N) | verb / noun / nominalized verb / noun | core | — | — | — | — | grammar_reference | n/a | verified | ex.(12) |
| mitta (믿다) / miti (믿이, gloss not given) / mitki (믿기) / mitum (믿음) | 'believe' / (source marks gloss as unclear/"?") / 'to believe' / 'belief' | verb / noun / nominalized verb / noun | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | ex.(13); source itself leaves the -i form's gloss as "?" — not a reading-confidence issue, the book marks it uncertain |
| ssota (쏘다) / ssoi (쏘이, gloss not given) / ssoki (쏘기) / ssoum (쏨/쏨, 'shooting') | 'shoot' / (source marks "?") / 'to shoot' / 'shooting' | verb / noun / nominalized verb / noun | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | ex.(14); -i form gloss left "?" by the source itself |
| mas poki (맛 보기) | 'taster' | compound noun | core | — | — | — | — | grammar_reference | n/a | verified | ex.(15); lexicalized -ki compound (mas 'taste' + poki 'seeing/trying') referring to a first-order entity (an institutionalized object/role), contrasted with productive sentential -ki |
| mos ppayki (못 빼기) | 'nail puller' | compound noun | core | — | — | — | — | grammar_reference | n/a | verified | ex.(15), same pattern |
| ttwim ttwiki (뜀 뛰기) | 'jumping' | compound noun | core | — | — | — | — | grammar_reference | n/a | verified | ex.(16); lexicalized -ki compound combining with a second-order entity |
| talliki (달리기) | 'running race' | compound noun | core | — | — | — | — | grammar_reference | n/a | verified | ex.(16) |
| phwul ppopki (풀 뽑기) | 'weeding' | compound noun | core | — | — | — | — | grammar_reference | n/a | verified | ex.(16) |
| cwultaliki sihap (줄다리기 시합) | 'tug-of-war (contest)' | compound noun | core | — | — | — | — | grammar_reference | n/a | verified | ex.(16) and again ex.(89); cwul 'rope' + taliki 'pulling' (< tali- + -ki) + sihap 'match/contest' |
| elta (얼다) / elum (얼음, lexicalized) / elum (어름, productive) | 'freeze' / 'ice' / 'freezing' | verb / noun / nominalized verb | core | — | — | — | — | grammar_reference | n/a | verified | ex.(17); the book notes Korean orthography distinguishes the lexicalized (b) and productive (c) forms even though both romanize "elum" |
| cwukta (죽다) / cwukem (주검) / cwukum (죽음) | 'die' / 'death' / 'dying' | verb / noun / nominalized verb | core | — | — | — | — | grammar_reference | n/a | verified | ex.(18) |
| iluta (이르다) / ilum (이름, lexicalized) / ilum (일음, productive) | 'inform/name' / 'name' / 'informing' | verb / noun / nominalized verb | core | — | — | — | — | grammar_reference | n/a | verified | ex.(19); same lexicalized-vs-productive orthographic split as elum above |
| mwutta (묻다) / mwutem (무덤) / mwutum (묻음) | 'bury' / 'grave' / 'burying' | verb / noun / nominalized verb | core | — | — | — | — | grammar_reference | n/a | verified | ex.(20) |
| sicakhata (시작하다) | 'begin' | verb | core | — | — | — | — | grammar_reference | n/a | verified | ex.(34); predicate compatible with -ki nominalization |
| cohahata (좋아하다) | 'like' | verb | core | — | — | — | — | grammar_reference | n/a | verified | ex.(34) |
| silhehata (싫어하다) | 'dislike' | verb | core | — | — | — | — | grammar_reference | n/a | verified | ex.(34) |
| wenhata (원하다) | 'want' | verb | core | — | — | — | — | grammar_reference | n/a | verified | ex.(34) |
| palata (바라다) | 'hope / expect' | verb | core | — | — | — | — | grammar_reference | n/a | verified | ex.(34) |
| tumwulta (드물다) | 'rare / infrequent' | adjective/verb | core | — | — | — | — | grammar_reference | n/a | verified | ex.(35); -ki-compatible predicate list, extended beyond the "traditional" list in (34) |
| ilswuta (일쑤다) | 'frequent / customary' | adjective/verb | core | — | — | — | — | grammar_reference | n/a | verified | ex.(35) |
| elyepta (어렵다) | 'difficult' | adjective | core | — | — | — | — | grammar_reference | n/a | verified | ex.(35) |
| swipta (쉽다) | 'easy' | adjective | core | — | — | — | — | grammar_reference | n/a | verified | ex.(35) |
| tetita (더디다) | 'be slow / take time' | adjective | core | — | — | — | — | grammar_reference | n/a | verified | ex.(35) |
| papputa (바쁘다) | 'be busy' | adjective | core | — | — | — | — | grammar_reference | n/a | verified | ex.(35) |
| cengsini epsta (정신이 없다) | 'be engrossed' | idiomatic predicate | core | — | — | — | — | grammar_reference | n/a | verified | ex.(35); lit. 'spirit is absent' |
| kwichanhta (귀찮다) | 'be annoying' | adjective | core | — | — | — | — | grammar_reference | n/a | verified | ex.(35) |
| ccacwungi nata (짜증이 나다) | 'fret' | idiomatic predicate | core | — | — | — | — | grammar_reference | n/a | verified | ex.(35) |
| kkuthnata (끝나다) | 'end' | verb | core | — | — | — | — | grammar_reference | n/a | verified | ex.(35) |
| iluta (이르다) [verb 'come to', distinct sense from the nominalization-paradigm iluta above] | 'come to' | verb | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | ex.(35); same romanized form as the 'inform/name' verb in ex.(19) — book treats as separate entries, flagged for disambiguation |
| malyenita (마련이다) | 'be set to' | predicate | core | — | — | — | — | grammar_reference | n/a | verified | ex.(35) |
| kwenhata (권하다) | 'urge / encourage' | verb | core | — | — | — | — | grammar_reference | n/a | verified | ex.(35) |
| kecelhata (거절하다) | 'refuse' | verb | core | — | — | — | — | grammar_reference | n/a | verified | ex.(35) |
| cakcenghata (작정하다) | 'make up one's mind' | verb | core | — | — | — | — | grammar_reference | n/a | verified | ex.(35) |
| kyelsimhata (결심하다) | 'decide' | verb | core | — | — | — | — | grammar_reference | n/a | verified | ex.(35) |
| kitalita (기다리다) | 'wait for' | verb | core | — | — | — | — | grammar_reference | n/a | verified | ex.(35); also used in running example (32)-(33) demonstrating -ki/-um incompatibility with abstract objects |
| alta (알다) | 'know' | verb | core | — | — | — | — | grammar_reference | n/a | verified | ex.(41); predicate compatible with -um nominalization (propositional-content objects) |
| kkaytatta (깨닫다) | 'realize' | verb | core | — | — | — | — | grammar_reference | n/a | verified | ex.(41) |
| icta (잊다) | 'forget' | verb | core | — | — | — | — | grammar_reference | n/a | verified | ex.(41) |
| sayngkakhata (생각하다) | 'think' | verb | core | — | — | — | — | grammar_reference | n/a | verified | ex.(41) |
| nukkita (느끼다) | 'feel' | verb | core | — | — | — | — | grammar_reference | n/a | verified | ex.(41) |
| mitta (믿다) [sense: 'believe' as -um-compatible predicate] | 'believe' | verb | core | — | — | — | — | grammar_reference | n/a | verified | ex.(41) |
| palkhita (밝히다) | 'make clear' | verb | core | — | — | — | — | grammar_reference | n/a | verified | ex.(41) |
| ttwulyeshata (뚜렷하다) | 'be clear' | adjective | core | — | — | — | — | grammar_reference | n/a | verified | ex.(41) |
| thullimi epsta (틀림이 없다) | 'be correct / be true' | idiomatic predicate | core | — | — | — | — | grammar_reference | n/a | verified | ex.(41); lit. 'there is no mistake' |
| incenghata (인정하다) | 'admit' | verb | core | — | — | — | — | grammar_reference | n/a | verified | ex.(41) |
| puinhata (부인하다) | 'deny' | verb | core | — | — | — | — | grammar_reference | n/a | verified | ex.(41) |
| ceneyhata (전제하다) | 'presuppose' | verb | core | — | — | — | — | grammar_reference | n/a | verified | ex.(41) |
| mullonita (물론이다) | 'to be sure' | predicate | core | — | — | — | — | grammar_reference | n/a | verified | ex.(41) |
| pwunmyenghata (분명하다) | 'be evident' | adjective | core | — | — | — | — | grammar_reference | n/a | verified | ex.(41) |
| calanghata (자랑하다) | 'boast' | verb | core | — | — | — | — | grammar_reference | n/a | verified | ex.(41) |
| ipcunghata (입증하다) | 'attest' | verb | core | — | — | — | — | grammar_reference | n/a | verified | ex.(41) |
| cungmyenghata (증명하다) | 'certify' | verb | core | — | — | — | — | grammar_reference | n/a | verified | ex.(41) |
| hwakinhata (확인하다) | 'make sure' | verb | core | — | — | — | — | grammar_reference | n/a | verified | ex.(41); also appears in ex.(42) |
| sangkihata (상기하다) | 'recall' | verb | core | — | — | — | — | grammar_reference | n/a | verified | ex.(41) |
| cachaykhata (자책하다) | 'accuse oneself' | verb | core | — | — | — | — | grammar_reference | n/a | verified | ex.(41) |
| kela (거라) | imperative sentence-ender, variant of -ela | grammatical morpheme (bound) | core | — | — | — | — | grammar_reference | n/a | verified | §7.3.1; analyzed as ki + ela |
| > **kela** = ki (existence marker) + ela (imperative) — the imperative "names" an action when -ela is used, but presupposes/reminds of an already-in-progress or already-understood action when -kela is used | | | | | | | | | | | |
| ketun (거든) | 'when' (conditional connective, presupposing) | grammatical morpheme (bound) | core | — | — | — | — | grammar_reference | n/a | verified | §7.3.2; contrasts with (u)myen 'if' (merely suggests an action) and with tunci 'whether...or' |
| > **ketun** = ki (existence marker) + etun — analyzed as containing -ki even though not synchronically segmentable; contrasts with myen by presupposing the named action/idea | | | | | | | | | | | |
| kena (거나) | 'whether...or' (disjunctive connective, presupposing) | grammatical morpheme (bound) | core | — | — | — | — | grammar_reference | n/a | verified | §7.3.3; contrasts with -una (names alternative actions not yet mentioned) |
| > **kena** = ki (existence marker) + una — used when the disjoined actions have already been mentioned/implied in context, unlike plain -una | | | | | | | | | | | |
| key (게) [causative/goal morpheme] | causative-construction connector, traditionally treated as unanalyzable adverbializer/complementizer | grammatical morpheme (bound) | core | — | — | — | — | grammar_reference | n/a | verified | §7.3.4; analyzed as ki + ey |
| > **key** = ki ('existence', temporal existence marker) + ey (postposition, goal marker 'to') — marks the goal-state an agent's action (via a causative verb like mantulta 'make', naypelye twuta 'leave alone', ttaylita 'beat', kwuuta 'roast', mallita 'dissuade') brings into existence | | | | | | | | | | | |
| key (게) [adverbializer] | manner adverb suffix implying a resulting change of state, contrasted with -(h)i | grammatical morpheme (bound) | core | — | — | — | — | grammar_reference | n/a | verified | §7.3.5; same -key morpheme as the causative connector, here forming adverbs from adjectives |
| kkaykkushata (깨끗하다) / kkaykkushi (깨끗이) / kkaykkushakey (깨끗하게) | 'clean' / 'cleanly' / 'to be clean (causing a state)' | adjective / adverb (-hi) / adverb (-key) | core | — | — | — | — | grammar_reference | n/a | verified | ex.(73); -hi form describes manner only, -key form additionally implies a resulting change of state |
| malkkumhata (말끔하다) / malkkumhi (말끔히) / malkkumhakey (말끔하게) | 'tidy' / 'tidily' / 'to be tidy (causing a state)' | adjective / adverb (-hi) / adverb (-key) | core | — | — | — | — | grammar_reference | n/a | verified | ex.(74) |
| ttoktokhata (똑똑하다) / ttoktokhi (똑똑히) / ttoktokhakey (똑똑하게) | 'clear' / 'clearly' / 'to be clear (causing a state)' | adjective / adverb (-hi) / adverb (-key) | core | — | — | — | — | grammar_reference | n/a | verified | ex.(75) |
| kkyalkkumhata (깔끔하다) | 'neat' | adjective (stative predicate) | core | — | — | — | — | grammar_reference | n/a | verified | ex.(87); -um + hata stative predicate (um-nominal base compounded with hata) |
| > **kkyalkkumhata** = kkyalkkum (an -um-nominal, no independent gloss given) + hata ('to do/be') | | | | | | | | | | | |
| kyalumhata (갸름하다) | 'slender' | adjective (stative predicate) | core | — | — | — | — | grammar_reference | n/a | verified | ex.(87) |
| kemukkulumhata (거무끄름하다) | 'blackish' | adjective (stative predicate) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | ex.(87); longer compound form, legible but not independently cross-checked elsewhere on the page |
| mitumcikhata (믿음직하다) | 'reliable' | adjective (stative predicate) | core | — | — | — | — | grammar_reference | n/a | verified | ex.(88); -um-nominal + cik + hata pattern |
| > **mitumcikhata** = mit- ('believe') + -um (nominalizer) + cik (suffix forming stative predicates) + hata ('to do/be') | | | | | | | | | | | |
| palamcikhata (바람직하다) | 'desirable' | adjective (stative predicate) | core | — | — | — | — | grammar_reference | n/a | verified | ex.(88) |
| issumcikhata (있음직하다) | 'likely to exist' | adjective (stative predicate) | core | — | — | — | — | grammar_reference | n/a | verified | ex.(88) |
| mekumcikhata (먹음직하다) | 'good to eat' | adjective (stative predicate) | core | — | — | — | — | grammar_reference | n/a | verified | ex.(88) |
| iwus topki wuntong (이웃 돕기 운동) | 'neighbor-helping campaign' | compound noun | core | — | — | — | — | grammar_reference | n/a | verified | ex.(89); -ki compound whose second element (wuntong 'campaign') is a second-order noun — illustrates the constraint that a ki-first compound requires a second-order second element |
| twimtwiki wuntong (뜀뛰기 운동) | 'jumping exercise' | compound noun | core | — | — | — | — | grammar_reference | n/a | verified | ex.(89) |
| iummay (이음매) | 'manner of connection' | noun | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | ex.(90); -um compound whose second element denotes 'manner/nature/tendency' — illustrates the reverse constraint (um-first compounds require a first- or third-order, manner-type second element); somewhat faint print on this line |
| pwuthimseng (붙임성) | 'affability' | noun | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | ex.(90) |
| olumsay (오름새) | 'tendency to rise' | noun | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | ex.(90) |
| ancumsay (앉음새) | 'manner of sitting' | noun | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | ex.(90) |
| cakela (자거라) | 'sleep' (kela-imperative) | verb form | core | — | — | — | — | grammar_reference | n/a | verified | ex.(45),(52); non-instantaneous verb, freely compatible with -kela |
| swikela (쉬거라) | 'rest' (kela-imperative) | verb form | core | — | — | — | — | grammar_reference | n/a | verified | ex.(52) |
| kakela (가거라) | 'go' (kela-imperative) | verb form | core | — | — | — | — | grammar_reference | n/a | verified | ex.(45),(49),(52) |
| isskela (있거라) | 'stay' (kela-imperative) | verb form | core | — | — | — | — | grammar_reference | n/a | verified | ex.(45),(52) |
| nolkela (놀거라) | 'play' (kela-imperative) | verb form | core | — | — | — | — | grammar_reference | n/a | verified | ex.(52) |
| capkela (잡거라) | 'catch/hold' (kela-imperative, marked awkward: "?") | verb form | core | — | — | — | — | grammar_reference | n/a | verified | ex.(46)-(50); instantaneous verb, kela-form judged awkward/questionable by the source itself (its own in-text "?" judgment, not a reading-confidence flag) |
| chikela (치거라) | 'hit' (kela-imperative, marked "?") | verb form | core | — | — | — | — | grammar_reference | n/a | verified | ex.(50) |
| chakela (차거라) | 'kick' (kela-imperative, marked "?") | verb form | core | — | — | — | — | grammar_reference | n/a | verified | ex.(50) |
| kamkela (감거라) | 'close (the eye)' (kela-imperative, marked "?") | verb form | core | — | — | — | — | grammar_reference | n/a | verified | ex.(50) |

**On the "?"/"*" judgments throughout:** several vocabulary/example rows above carry a source-internal
grammaticality judgment (e.g., ?capkela, *pokela) rather than a reading-confidence flag — these
diacritics are the author's own acceptability markers (questionable vs. fully ungrammatical),
reproduced as printed, not markers of my own uncertainty about the scan.

## Grammar points

### 7.0 Introduction — three types of nominalization

Korean has three major nominalizers deriving nouns from verbs/adjectives: -i (이), -ki (기), and -um
(음). The book's stated purpose for the whole chapter is to work out the actual semantic distinction
between -ki and -um in particular — the -i nominalization is comparatively clear-cut (it is
non-productive, forming first-order/concrete nominals, largely lexicalized) and poses little
difficulty, but no prior study, in the author's assessment, had adequately differentiated -ki from
-um (p. 341).

### 7.1 Review of relevant studies — the three-order ontological classification

The chapter's theoretical foundation is Lyons' (1978) three-way classification of nominal entities,
which the author treats as corroborated independently by Givon (1979) and Vendler (1968):

- **First-order entities** (physical objects): relatively constant over time, located in
  (psychologically) three-dimensional space, can be pointed to and have properties ascribed to them.
- **Second-order entities** (events, processes, states of affairs): located in time, occur or take
  place, can be identified/referred to as individuals, but are more obviously perceptual/conceptual
  constructs than first-order entities, with no sharp line between an individual and a generic
  situation.
- **Third-order entities** (propositions): outside space and time altogether; unobservable; cannot be
  said to occur or be located; are "true" rather than "real"; can be asserted, denied, or forgotten;
  and can serve as reasons rather than causes (pp. 341-342).

Givon's parallel three-way feature system — concrete (exists in space, = first-order), temporal
(exists in time, = second-order), abstract (exists outside space and time, = third-order) — is
presented as restating the same classification in terms of space/time (p. 343).

**Diagnostic predicate tests.** The book works through a battery of English example sentences (pp.
343-345, examples 1-9) testing which predicate types can take which noun category as subject/object:
"nontemporal/nonspatial" predicates (be the same as, be different, be similar, be important) accept
all three categories (chair/event/idea) interchangeably; "temporal" predicates specific to temporal
nouns (begin, occur, take place) are grammatical with second-order nouns (earthquake, meeting,
class) but degrade with first-order (chair) or third-order (mind) nouns — e.g. "?The chair/mind
begins at ten o'clock" is marked questionable; a third, narrower predicate class (realize a
mistake/meaning) accepts abstract/third-order nouns but rejects concrete ones ("?He realized the
chair/war" is marked ungrammatical). This predicate-compatibility methodology is then imported
directly into the Korean analysis in §7.2 and used throughout the chapter as the diagnostic for
testing -ki vs -um compatibility.

The author concludes (p. 346) that this threefold division is both applicable to and necessary for
Korean nouns and predicates, and maps it directly onto the three nominalizers: -i (and its
lexicalized variants) → first-order/concrete; -ki → second-order/temporal; -um → third-order/
abstract.

### 7.2 Types of nominalizations: paradigm data and the -i nominalization

Paradigms like salta/sali/salki/salm 'live'/'utensil'/'to live'/'life' (ex. 10) and four similar
sets (tatta, usta, mitta, ssota; exx. 11-14) are presented to show the -i, -ki, and -um
nominalizations of the same root side by side. The -i nominalization is noted as unproductive — it
may have been productive earlier in the language's history, attaching to verbs to create words
referring to institutionalized objects, but is not productive now. Some -ki nominalizations are
similarly lexicalized rather than productive: ex. (15) mas poki 'taster' and mos ppayki 'nail puller'
refer to first-order entities (institutionalized objects/roles); ex. (16) ttwim ttwiki 'jumping',
talliki 'running race', phwul ppopki 'weeding', cwultaliki sihap 'tug-of-war' combine -ki forms with
second-order entities as compound-noun elements. Korean orthography itself distinguishes lexicalized
from productive -um forms that happen to romanize identically (elum 'ice' vs. elum 'freezing', ilum
'name' vs. ilum 'informing' — exx. 17, 19) by using different underlying spellings, even though both
pairs romanize the same in this book's system. From this point forward the book sets aside
nonproductive lexicalized nominals and focuses on the productive sentential nominalizations (p. 349).

### 7.2.1 Second-order nominalization: -ki

**Morphological placement.** -ki attaches after the verb stem or after the past/remote-tense marker
-ess (exx. 21-23: kaki/kasski, ka isski/ka issesski, kako isski/kako issesski for compound verbs with
or without the past marker on the second verb). -ki (and the aspect marker -un) cannot attach after
the present-tense marker (ex. 24: *kanunki is rejected in favor of kanki). The author flags the form
kim (which appears to combine -ki and -um) as not fully understood at this point in the analysis (p.
349, ex. 25-26 — the construction "iwang on kimey" 'since we came here').

**Syntactic distribution.** -ki nominalizations function as subject, object, or an appositive to a
following noun such as ttaymun 'because' (ex. 27, p. 350).

**The core semantic claim: -ki is an existence marker.** The verb stem alone designates only a *type*
of situation (a cover term for a process, event, action, or state) without indicating whether that
situation is actually realized. Tense markers in a main (non-nominalized) clause carry that existence
information: -ess marks that the action took place in the past and does not exist now (or, in another
reading, marks irrealis); the present/actual tense marker -nun marks that the action's realization
falls within the actual world (pp. 350-351, worked through example 28-30 with a formal diagram at ex.
29 breaking the sentence into propositional content + remote/nonremote (ess/nun) + assertion (-ta)).

The -ki nominalizer is argued to carry exactly this existence-marking function when a clause is
nominalized: it marks the resulting nominal as a second-order nominal designating the **existence
(actual or potential) of an action, process, event, or state** (formal diagram at ex. 31, p. 352).
Because -ki nominalizations refer to existence of an action/process/event but never to an abstract
concept, they are compatible with verbs like kitalita 'wait for' (ex. 32a: nanun [kuka oki]l
kitalinta 'I wait for him to come' is grammatical) but incompatible when the -um nominalization is
substituted (ex. 32b: *...omul kitalinta is ungrammatical) — because waiting requires something that
can move or change location/state, which only second-order (not third-order/abstract) entities can
do (p. 352).

The past-tense marker -ess within a -ki nominalization indicates remoteness/precedence relative to
another event (ex. 33: pika oki ttaymuney... 'because it is raining' vs. pika oassiki ttaymuney...
'because it rained' — in the first, the raining is simultaneous with the resulting muddy road; in the
second, the raining preceded it). The author credits Martin (1969:226-233) as "very insightful" for
noting that -ki denotes 'act' or 'state' depending on the preceding verb (e.g., ttwi-ki 'an act of
jumping' vs. iss-ki 'a state of being'), but subsumes both under the single general category of
**existence** (actual or potential, of a process/action/event/state) — and notes that Martin lists
compatible predicates without explaining *why* they are compatible, which this chapter's analysis
supplies (p. 353).

A large predicate-compatibility list is given (exx. 34-35, pp. 354-355) of predicates that take -ki
(not -um) complements because they concern the existence, frequency, or ease of a situation rather
than a proposition about it: begin, like, dislike, want, hope/expect (the "traditional" list), plus a
much longer list the author adds — rare, frequent, difficult, easy, slow, busy, engrossed, annoying,
fret, end, come to, be set to, urge, refuse, make up one's mind, decide, wait for. The reasoning given
(p. 355): neither concrete objects nor abstract concepts/propositions can be said to be frequent,
infrequent, easy, or difficult — only things that exist in time (actions, processes, events) can.
Three worked examples (ex. 36-37) show -ki forms specifically (weeding, being late, solving a
problem, bursting) take these predicates naturally while -um substitution is predictably rejected.

### 7.2.2 Third-order nominalization: -um

-um attaches to the verb stem or to the past-tense morpheme (ex. 38-39: kam/kassum 'going'/'having
gone'; ka issum/ka issessum). Like -ki, -um nominalizations can function as subject or object of a
verb/postposition (ex. 40).

**-um and -ki share distribution but differ completely in meaning.** Unlike -ki, -um nominalization
does not carry temporal-existence meaning; it conveys only **propositional content** — it corresponds
to Lyons' third-order entities: unobservable, not locatable in space or time, but assertable, denied,
remembered, or forgotten (p. 357).

A predicate list is given (ex. 41, p. 357) of predicates compatible with -um because they take
propositions as objects: know, realize, forget, think, feel, believe, make clear, be clear, be
correct/be true, admit, deny, presuppose, to be sure, be evident, boast, attest, certify, make sure,
recall, accuse oneself. Minimal-pair contrasts (ex. 42-44, pp. 358) show -um is required (or strongly
preferred) over -ki with verbs like mitnunta 'believe', hwakinhayssta 'confirmed', and reporting verbs
— because one can believe or confirm a *fact* about a process/event, but not the temporal existence
of the process/event itself. Conversely (ex. 43), predicates compatible with third-order
nominalizations concern whether something can be true/untrue, not whether it can be real/unreal —
"what can occur or is occurring can be real or unreal, but not true or untrue" (p. 358). The same
reporting-verb asymmetry (one can report a fact about an event but not the event itself) is confirmed
with alliessta 'informed' (ex. 44).

**Summary of §7.2 (p. 359):** -ki nominalizations correspond to Lyons' second-order nominals
(entities existing in time); -um nominalizations correspond to third-order nominals (entities
existing neither in time nor space). Co-occurrence restrictions between each nominalizer and various
predicate classes are consistent and predictable from this single semantic distinction.

### 7.3 Some grammatical morphemes with ki

The author identifies several Korean grammatical-morpheme pairs where one member "contains" -ki and
the other does not, traditionally treated as free variants with no meaning difference. The chapter
argues all of them actually contain the -ki existence marker and differ from their ki-less
counterparts precisely in presupposing the existence of the action/situation in question (p. 359).

### 7.3.1 kela (거라)

Korean has two imperative forms, -ela and its variant -kela (ex. 45 gives full paradigms: cata/cala/
cakela 'sleep', kata/kala/kakela 'go', issta/issela/isskela 'stay', ilkta/ilkela/ilkkela 'read',
pota/poala/*pokela 'see' [note: pokela is marked ungrammatical, an irregular gap], capta/capala/
capkela 'hold'). Although traditionally treated as synonymous, the book argues they differ
pragmatically: -ela is used when the speaker *names* an action for the first time; -kela is used when
the speaker reminds or prompts the addressee about an action already presupposed to be happening or
intended (p. 361). A worked scenario: if A is asleep and B arrives, waking A, who starts to get up but
still looks sleepy — "cakela" (not "cala") is the natural prompt, because the continuous existence of
the ongoing sleep-process, not the bare naming of the action, is what's relevant (p. 361).

A further restriction: **instantaneous verbs are awkward in the -kela form** (ex. 50: ?capkela
'catch', ?chikela 'hit', ?chakela 'kick', ?kamkela 'close the eye' — all marked questionable), but
their *progressive* forms (capko isskela, etc., ex. 51) sound natural, because a continuous
(non-instantaneous) action is what -kela's presupposed-existence meaning requires. **Non-instantaneous
verbs take -kela freely** (ex. 52: cakela, swikela, kakela, isskela, nolkela — all natural, p. 364).
Two further worked scenarios (ex. 48-49, p. 363) show -kela preferred over -ela when the departure/
going is already contextually understood (e.g., a guest leaving after a visit, or a second reminder
after someone has forgotten to act on a first suggestion).

### 7.3.2 ketun (거든)

Two conditional connectives, -(u)myen and -ketun, can both be glossed 'if'/'when' (exx. 53-55). -myen
merely puts forward the idea of an action for consideration without committing to whether it's
realized; -ketun is used when the action's realization is pragmatically presupposed — already
mentioned, or recoverable from context without needing to be newly named — and what the speaker cares
about is whether that already-understood action actually occurs (p. 365). Worked examples: a
give-and-take where speaker A first raises the idea of a trip to Hawaii (-myen) and speaker B, taking
that idea as given, asks about its realization (-ketun, ex. 56); a promise already mentioned in a
prior sentence, picked up with -ketun in the follow-up (ex. 57); a doctor's prescription scenario
where "getting well" is pragmatically presupposed by context even without prior linguistic mention
(ex. 58, p. 366). -ketun also contrasts formally and semantically with -tunci 'whether or not' (ex.
54): "?kuka oketun malketun nanun sangkwan epsta" is marked questionable, because -ketun's
presupposed-specific-action meaning clashes with -tunci's disjunctive 'whether or not' sense.

### 7.3.3 kena (거나)

Parallel to the ketun/myen contrast, -kena contrasts with -una (both roughly 'or'/'whether'). -una
names alternative actions without any presupposition that they've been previously mentioned or
realized; -kena is used when the alternatives have already been pragmatically presupposed — mentioned
or implied by prior context (p. 366-368, exx. 60-67). Worked contrast: ex. 62 — when "coming or going"
has neither been mentioned nor implied, only -una (onakana) is possible; ex. 63 — once a specific
action (Chelswu's coming) has been mentioned, the disjunctive follow-up ("coming or not") takes
-kena (okena malkena), and -una is not usable there. Further examples (64-67) show -una used for
genuinely new alternative suggestions not presupposed by the preceding utterance.

### 7.3.4 key (게) — causative/goal construction

Traditionally -key is treated as a single unanalyzable, meaningless morpheme functioning as an
adverbializer/complementizer. The chapter argues it is actually two morphemes: -ki 'existence' +
-ey, a postposition functioning as a goal marker ('to') (p. 369). Evidence: comparing nanun (kuka
oki)lul palanta 'I expect him to come' (-ki alone, ex. 68a) with nanun (kuka okey) mantulessta 'I
made him come' (-key, ex. 68b) — what's expected in (a) is the temporal existence of his coming
(marked by -ki); what's brought about in (b) is likewise the existence of his coming (-ki again),
with -ey marking the *goal* toward which the causative verb's action (mantulta 'make') is directed.
The goal-postposition -ey is argued to denote the final state of a change-of-state process: an entity
moves from state 1 to state 2, and -ey marks the final state (ex. 71, p. 371: naypelye twuta 'leave
alone' + key — 'I let him go', where his not-going was state 1 and his going, marked by key, is state
2). The construction generalizes to any causative verb that can be understood as bringing about a
change of state, event, or situation — not just mantulta: examples include ttaylita 'beat' (ex. 72a),
kwuuta 'roast' (72b), anhkey hata (calm so as to not cry, 72c), mallita 'dissuade' (72d) (pp.
370-371). The first-order/second-order object distinction from §7.2 recurs here: first- and
second-order entities can undergo change and so can be objects of mantulta, but a third-order/
abstract entity cannot (ex. 70: *nanun (ku aika wulum)ey mantulessta is ungrammatical, rejecting an
-um nominalization as the causee of mantulta) — paralleling Lyons' own definition of causativity,
quoted briefly: the causative predicate "takes a first-order nominal in its subject and a second-order
nominal as its object... reflect[ing] the notion of causality, according to which agents are seen as
the causes of the situation which by their actions they bring into existence" (p. 370).

### 7.3.5 key (게) — adverbializer

Korean adjectives form adverbs two ways: with -(h)i or with -key (ex. 73-75: kkaykkushata/kkaykkushi/
kkaykkushakey 'clean'; malkkumhata/malkkumhi/malkkumhakey 'tidy'; ttoktokhata/ttoktokhi/
ttoktokhakey 'clear'). The chapter's -ki+-ey analysis of causative -key is extended here: the -hi
form simply describes the manner of the agent's action without implying any change of state; the
-key form, built on the same existence-marking -ki plus the goal postposition -ey, additionally
implies a change in an accompanying (concomitant) situation (p. 372). Minimal-pair test: kunun
sulphukey wulessta ('he cried, [causing the people around him to be] sad') vs. kunun sulphi wulessta
('he cried sorrowfully') — in extended context the two are not freely interchangeable (ex. 76-78,
pp. 373): "kunun yephey issnun motun salami sulphukey/?sulphi wulessta" ('he cried, making the
people around him sad') only accepts the -key form, because the sentence requires the
change-of-state reading (the people around him becoming sad), not mere manner. The same distinction
is shown to extend to sentential adverbs (tahaynghi vs. tahaynghakey, ex. 78): -hi conveys only the
speaker's evaluation that an outcome is fortunate; -key additionally implies that some change of
state in the world resulted from it.

### 7.4 Some further justifications

### 7.4.1 verb-ki verb-ta (emphatic existence-dispute construction)

A special emphatic construction — a -ki nominalization of a verb followed by a repeated finite form
of the same verb (verb-ki verb-ta) — is used specifically when the existence of a state, process, or
event is in dispute, directly supporting the chapter's core claim that -ki is an existence marker (p.
374). Example: i sikyeyta mangkacyessta 'this watch is completely broken' implies the watch is not
running, and a listener who disputes that can respond kulayto kakinun kanta 'nevertheless, it does
go' — emphasizing, against the prior assertion, that the running does exist (ex. 79). The construction
requires a delimiter particle (showing contrast/addition/delimitation) and is only used when there is
a presupposed dispute about existence, not in neutral contexts (p. 375, confirmed by ex. 80: a
speaker presumes someone slept poorly; a second speaker contradicts with khwulkhwul cakiman cal
catela 'he slept very soundly', emphasizing the disputed existence of sound sleep).

### 7.4.2 -ki hata vs. -um ...cil hata

-ki nominalizations (kinominals) can serve directly as objects of hata 'do' (ex. 81-83: cwul[nemki]ul
cal hanta 'the children are skipping rope'; [talliki]ul hanta 'engaged in a tug of war';
kong[chaki]ul hanta 'kicking balls' — alternative -um forms marked ungrammatical/questionable with
"?" in each case). -um nominalizations (umnominals) generally **cannot** serve as direct objects of
hata unless the noun cil 'act' is inserted as an intermediary (ex. 84-86: emenika [talim/?taliki]cilul
hanta 'mother is ironing'; soka [saykim/?saykiki]cilul hanta 'the cow is regurgitating'; nwuika
[kkapwum/?kkapwulki]cilul hanta 'sister is winnowing' — here the -um forms with cil are correct and
the -ki forms are marked questionable, the reverse pattern from exx. 81-83). Some -um nominals combine
directly with hata to form stative predicates without cil (ex. 87: kkyalkkumhata 'neat', kyalumhata
'slender', kemukkulumhata 'blackish'); others require an intervening -cik- suffix (ex. 88:
mitumcikhata 'reliable', palamcikhata 'desirable', issumcikhata 'likely to exist', mekumcikhata 'good
to eat').

**Compound-noun formation constraint (p. 376-377).** Deriving a compound noun from a ki- or
um-nominal plus a second noun is productive but constrained by nominal order: when the first element
is a ki-nominal, the second element must be a second-order noun (ex. 89: cwultaliki sihap 'tug-of-war
contest', iwus topki wuntong 'neighbor-helping campaign', twimtwiki wuntong 'jumping exercise' — sihap
and wuntong are both second-order nouns). When the first element is an um-nominal, the second element
must instead be either a first-order or third-order noun, specifically ones denoting 'manner',
'nature', or 'tendency' (ex. 90: iummay 'manner of connection', pwuthimseng 'affability', olumsay
'tendency to rise', ancumsay 'manner of sitting'). This compounding constraint is presented as a
further, independent piece of evidence for the chapter's overall second-order/third-order split
between -ki and -um.

---

## Korean — Established Vocabulary/Grammar: Chapter 8, "Tense-Aspect-Modality"

**Source:** Keedong Lee, *A Korean Grammar on Semantic-Pragmatic Principles*, Hankook Munhwasa
(한국문화사), Seoul (publication year not visible in this chapter's pages — front matter not in this
chunk's assigned range). Chapter 8 "Tense-Aspect-Modality," printed pages 381-433 (p.380 and p.434
are blank; Chapter 9 "Verbal Connectives" begins immediately after on the next printed page). Source
has no text layer; vision-read from rendered page images.

**Coverage note:** This is a theoretical, pragmatics-focused monograph, not a pedagogical textbook —
its "vocabulary" in this chapter consists almost entirely of grammatical morphemes and dependent
nouns (the chapter's actual subject matter), not general lexical items drawn from illustrative
sentences, so the Vocabulary table below is scoped to those morphemes/dependent nouns rather than
every content word appearing in example sentences (which recur as incidental filler across dozens of
examples and would not meet the "distinct vocabulary item" bar in any useful sense). Every grammar
point in the assigned range (8.0-8.4) is covered.

**Redundancy assessment:** This language already has substantial pedagogical coverage of the bare
-었-(past)/-겠-(future-presumptive)/-고 있-(progressive) morphemes at a beginner level from other
established/ files, and a *separate, independently-authored* tense/aspect monograph is being
extracted in parallel for established/051. Per the project's non-redundant-supplement rule, this
chapter is treated as **essentially all new** rather than suppressed for topical overlap, because:
(1) its central framing — an Actual/Remote tense opposition instead of past/present/future, defined
via "epistemic distance" from a speaker's Ground rather than clock time — is a different theoretical
analysis than any beginner-level treatment; (2) the ess-ess "remote tense of remote tense" construction
(8.1.3) is not covered by pedagogical sources at all; (3) the aspect-in-modifying-clauses system
(8.2.2: un/ten/nun/ul on relative clauses) is a distinct grammatical domain from matrix-sentence
aspect that beginner textbooks rarely treat systematically; and (4) the entire Modality section (8.3)
— analyzing "dependent noun + i/iss/al-molu/ha" nominal-predicate constructions as a graded
epistemic-certainty system, including the striking claim that the suffix -겠다 (keyssta), traditionally
treated as a single indivisible morpheme, actually decomposes as kes (fact) + i (be) + ess (remote) —
is wholly new theoretical content with no pedagogical-source precedent in this project. Nothing in
this chapter was skipped as redundant; only repeated illustrative example sentences that reuse
already-captured morphology without adding new grammatical content were skipped, per the standard
coverage rule.

**Marginalia check:** No handwritten marginalia, underlining, or pencil annotation was found anywhere
in the 29 page-images read for this chapter (printed pages 379/380 front-matter TOC through 434/435,
Chapter 9 TOC start). All content is clean, consistently typeset print.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| -nun/-un (는/은) | actual-tense marker (allomorphs: -nun after vowel-final stem, -un after consonant-final stem) | verbal suffix | core | — | — | — | — | grammar_reference | n/a | verified | p.383-384; e.g. kanta 'go' (consonant stem + nun→ n), capnunta 'catch' (vowel-final-stem-like pattern + un) |
| ess (었) | remote-tense marker I; situation absent from / separated from the actual-reality area | verbal suffix | core | — | — | — | — | grammar_reference | n/a | verified | p.388; also used for counterfactual/hypothetical conditions, not only past |
| essess (었었) | remote-tense marker II ("remote tense of remote tense"); situation viewed from a surrogate platform set up in the past reality, further removed from actual reality than plain ess | verbal suffix (compound) | core | — | — | — | — | grammar_reference | n/a | verified | p.392-394; author's own superscript notation distinguishes ess¹ (remote viewed from a past platform) vs ess² (remote viewed from the actual platform) |
| -e iss(ta) (어/아 있다) | resultative/perfective-with-resultative-meaning: process has reached its endpoint, subject located at end of process | verbal construction (goal marker -e + existential verb iss) | core | — | — | — | — | grammar_reference | n/a | verified | p.394-395; cwuke issta 'is dead/in the state of being dead' |
| -ko iss(ta) (고 있다) | imperfective (I): subject located at a point within a process (not yet at its end) | verbal construction (partitive marker -ko + existential verb iss) | core | — | — | — | — | grammar_reference | n/a | verified | p.395; ttwiko issta 'is jumping' |
| te (더) | imperfective aspect marker (matrix sentence): speaker saw a process at a midway point, not committed to its beginning/end or subsequent outcome | verbal suffix | core | — | — | — | — | grammar_reference | n/a | verified | p.396; conveys a non-committal attitude/reservation on the speaker's part |
| tela (더라) | te + sentence-ender la; imperfective report with a nonchalant/non-committal sentence-final flavor | verbal suffix (compound: aspect marker te + sentence-ender la) | core | — | — | — | — | grammar_reference | n/a | verified | p.396; la itself not further analyzed in this chapter beyond noting it pairs with imperative markers ke/ne (-kela, -nela) |
| ess-te / -esste (었더) | combined completion + imperfective: a perfective (completed) situation is but one link observed within a wider, still-open process | verbal suffix (compound) | core | — | — | — | — | grammar_reference | n/a | verified | p.398-399; e.g. haysstela — one completed part (English homework) viewed as part of a larger uncompleted series (all assignments) |
| essul (었을) | completion-unspecified compound marker | verbal suffix (compound) | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | p.394, listed in the chapter's own morpheme inventory; not separately exemplified within this chapter's range beyond the inventory list |
| un (은/ㄴ) | perfective aspect marker in modifying/relative clauses: situation viewed as a single unanalyzable whole (beginning, middle, end as one unit) | adnominal (relativizer) suffix | core | — | — | — | — | grammar_reference | n/a | verified | p.401-405; mekun 'eaten', capun 'caught' |
| ten (던) | imperfective (I) marker in modifying clauses: situation viewed in its middle, neither endpoint visible, process may have continued past the observed portion | adnominal (relativizer) suffix | core | — | — | — | — | grammar_reference | n/a | verified | p.406-410; cisten cip 'the house (we) were building' |
| nun (는) | imperfective (II) marker in modifying clauses: situation synchronous with a reference time (usually utterance time, but can be a past reference point) | adnominal (relativizer) suffix | core | — | — | — | — | grammar_reference | n/a | verified | p.411-413; thanun pwun 'the person getting in (a taxi)' |
| ul (을/ㄹ) | unrealized/unspecified aspect marker in modifying clauses: situation yet to be realized, typically after utterance time | adnominal (relativizer) suffix | core | — | — | — | — | grammar_reference | n/a | verified | p.413-416; mekul sakwa 'the apple (I am) to eat'; idiosyncratic combination with ttay 'time' (ul ttay) can refer to past OR future |
| ess-ten (었던) | completion-imperfective compound in modifying clauses: a completed (perfective) situation presented as one link in a wider chain of situations, giving a broader perspective | adnominal suffix (compound) | core | — | — | — | — | grammar_reference | n/a | verified | p.416-417; salassten cipita 'the house (we) had lived in (as one among several)' |
| kes (것) | dependent noun: 'fact'/'thing' — situation related to reality/fact | dependent (bound) noun | core | — | — | — | — | grammar_reference | n/a | verified | p.417-423; central to the modal construction [[clause-(AM)] kes] + i, and to the proposed decomposition of keyssta |
| pa (바) | dependent noun: mental reality — a situation held in the speaker's own private/mental consciousness rather than public/factual reality | dependent (bound) noun | core | — | — | — | — | grammar_reference | n/a | verified | p.424-426; e.g. iey kiphun kamsalul tulinun paita 'for that I offer my deep thanks' |
| kkatalk (까닭) | dependent noun: 'reason' | dependent (bound) noun | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | p.419, 425; author notes it has a "clear meaning" and explicitly excludes it from deeper semantic analysis in this chapter |
| ttaymun (때문) | dependent noun: 'cause' | dependent (bound) noun | core | — | — | — | — | grammar_reference | n/a | plausible_unverified | p.419, 425; likewise excluded from deeper analysis as having a transparent meaning |
| the (터) | dependent noun, listed as a member of the i-class ('be') dependent-noun set | dependent (bound) noun | core | — | — | — | — | grammar_reference | n/a | verified | p.419; listed in the inventory of nouns used with i but not examined further within this chapter's assigned pages |
| tey (데) | dependent noun, listed as a member of the i-class ('be') dependent-noun set | dependent (bound) noun | core | — | — | — | — | grammar_reference | n/a | verified | p.419; listed in the inventory of nouns used with i but not examined further within this chapter's assigned pages |
| cek (적) | dependent noun: 'occasion' — used with existential verb iss, roughly corresponds to the English perfect ("has happened") | dependent (bound) noun | core | — | — | — | — | grammar_reference | n/a | verified | p.427; yelumey nwuni on ceki issta 'it has snowed in summer' |
| ttay (때) | independent/dependent noun: 'time'; used with iss when the unrealized aspect marker ul requires modalization | noun | core | — | — | — | — | grammar_reference | n/a | verified | p.427; also appears pervasively as an independent noun throughout 8.2.2 ("...ul ttay" = 'when...') |
| swu (수) | dependent noun: 'way'/potential means — connection between potentiality and reality is possible because no physical/external obstacles exist; contrasts with cwul (mental capacity) | dependent (bound) noun | core | — | — | — | — | grammar_reference | n/a | verified | p.428-429; wuncenhal swuka issta 'I can drive' (physical/legal ability) |
| cwul (줄) | dependent noun: used with al/molu 'know/not know' — denotes mental capacity/cognitive ability, contrasts with swu's physical-ability sense | dependent (bound) noun | core | — | — | — | — | grammar_reference | n/a | verified | p.429-430; wuncenhal cwul anta 'I know how to drive' |
| ci (지) | dependent noun, listed as a member of the al-class ('know') dependent-noun set | dependent (bound) noun | core | — | — | — | — | grammar_reference | n/a | verified | p.419; listed in the inventory alongside cwul, pa, kes as nouns used with al, not separately exemplified within this chapter's range |
| tus (듯) | dependent noun: 'appearance'/'expression'/'effect' — judgment based on appearance/feeling rather than reasoned evidence; can pair with siph 'seem' instead of ha | dependent (bound) noun | core | — | — | — | — | grammar_reference | n/a | verified | p.430-431; pika on/onun/ol tus hata 'it looks like it rained/is raining/will rain'; doubled contrastive form X tus Y tus hata expresses a fifty-fifty uncertainty (e.g. 'it looks as if it rained, but then again it doesn't look like it rained') |
| ppen (뻔) | dependent noun: 'point' (of/near an event) — used only with the unrealized marker ul; situation was on the verge of happening but did not actually occur | dependent (bound) noun | core | — | — | — | — | grammar_reference | n/a | verified | p.431; nemecil ppen haysta 'he was on the point of falling down' |
| man (만) | dependent noun: 'norm' — the designated situation almost, but not quite exactly, measures up to a speaker-set norm; used only with ul | dependent (bound) noun | core | — | — | — | — | grammar_reference | n/a | verified | p.432; yocuum salman hata 'he is fairly well off nowadays'; kapolman hata 'fairly worth visiting' |
| chey (체) | dependent noun: 'make-believe'/pretense — used with un (did X but pretended) and nun (is currently pretending to do X) | dependent (bound) noun | core | — | — | — | — | grammar_reference | n/a | verified | p.432; can chey hanta 'pretends that he slept' vs canun chey hanta 'pretends that he is sleeping' |
| i (이) | verb: 'be' (copula) — one of four verbs forming the modality-marking closed set; most certain end of the certainty continuum | copula/verb | core | — | — | — | — | grammar_reference | n/a | verified | p.417; heads the kes/pa/kkatalk/the/tey/ttaymun dependent-noun constructions |
| iss (있) | verb: 'exist' — second verb in the modality closed set | verb | core | — | — | — | — | grammar_reference | n/a | verified | p.417, 427-429; heads cek/ttay/swu constructions |
| al (알) | verb: 'know' — third verb in the modality closed set, between i and ha on the certainty continuum | verb | core | — | — | — | — | grammar_reference | n/a | verified | p.417, 429-430; heads cwul/pa/kes/ci constructions |
| ha (하) | verb: 'do' — fourth verb in the modality closed set; least certain/stable end of the continuum | verb | core | — | — | — | — | grammar_reference | n/a | verified | p.417, 430-432; heads tus/ppen/man/chey constructions |
| ani (아니) | verb: 'not be' — negative counterpart of i, part of the four-pair modal-verb continuum (not separately developed beyond being named in this chapter's range) | copula/verb (negative) | core | — | — | — | — | grammar_reference | n/a | verified | p.417 |
| eps (없) | verb: 'not exist' — negative counterpart of iss | verb (negative) | core | — | — | — | — | grammar_reference | n/a | verified | p.417 |
| molu (모르) | verb: 'not know' — negative counterpart of al; also functions as the governing verb in the pa-with-ul pattern, implying puzzlement/helplessness | verb (negative) | core | — | — | — | — | grammar_reference | n/a | verified | p.417, 425-426; nanun pappase ecci hal palul molunta 'being too busy I do not know what to do' |
| keyssta / keyss (겠다/겠) | traditionally analyzed as a single indivisible future/presumptive morpheme; this chapter argues it is actually a phonologically contracted form of kes + i + ess ('fact' + 'be' + remote-tense), i.e. the kes-i-kesita modal construction with no overt aspect marker (Ø) between clause and kes | verbal suffix (author's proposed trimorphemic decomposition of a conventionally monomorphemic form) | core | — | — | — | — | grammar_reference | n/a | verified | p.422-424; contraction chain kesiessta → keyessta → keyssta, independently supported by the author via a phonological parallel (stem-final y + immediately following first vowel of ess drops, e.g. meyessta→meyssta, seyessta→seyssta); nanun nayil kal kesita 'I am probably going tomorrow' vs nanun nayil kakessta 'I will go tomorrow (determination)' — contrasted as externally-confirmed potentiality vs. speaker-alone-determined potentiality |

## Grammar points

### 8.0 Introduction — framework and key terms

The chapter sets out to analyze Korean tense-aspect-modality (TAM) "from a different angle,"
drawing on Langacker (1978) on the English auxiliary. Five terms recur throughout and are defined up
front (p.381-383): **Tense** relates the time of a situation to some other time (usually the speech
moment), but the chapter's own thesis is that tense meaning is *derived*, not basic — Joos's (1968)
remote/actual tense distinction is adopted as the real primitive. **Aspect** follows Comrie
(1976): perfective views a situation as a single unanalyzable whole; imperfective views it from
inside, mid-process. **Modality** (after Joos 1968) is a specific relation between a situation and
"the real world," with no truth value attached — Langacker's "epistemic distance" is treated as
roughly equivalent. **Reality** is split into a broad sense (past + present circumstances together)
and a narrow sense (just the present — "actual reality"), contrasted with potentiality and
unreality. **Ground** is the platform/perspective from which a situation is viewed — normally the
speaker's own, but an embedded sentence can set up a surrogate ground. The chapter commits to a
"basic meaning" methodology throughout: each grammatical morpheme is assumed to have one prototypical
meaning from which all other (inferential/contextual) readings are derived — explicitly contrasted,
in the chapter's closing summary, with what the author calls the unproductive reverse procedure
"commonly practiced by Korean grammarians."

### 8.1.1 Actual Tense

Korean has two basic tenses: actual and remote. The actual tense (-nun/-un) indicates that a
situation exists in an area that includes the speaker's platform (Ground). Unlike the traditional
view of "referring to a point in time," the author treats the actual tense as covering a *flexible,
relative area* — a higher platform commands a wider area, a lower one a narrower perspective
(diagrammed as concentric circles around the Ground). In its narrow use the actual tense marks
synchronicity with the speech moment (e.g. a live demonstration: "이 뚜껑을 열고 새를 넣는다" / i
ttwukkengul yelko saylul nehnunta, "Now I open this lid and put the bird in"). A derived, wider use
covers habits, general truths, and scheduled/certain future events — illustrated with sun-rise,
water-boiling-point, and scheduled-travel examples (p.386-388) — all valid as long as they fall
within the area the actual tense's platform commands.

### 8.1.2 Remote Tense (I): ess

ess marks that a referenced situation is *not currently taking place*: it is separated from, and not
contiguous with, the actual-tense area. This explains the typical "past" reading (케 어제 일본에 갔다 /
kunun ecey ilponey kassta, "He went to Japan yesterday") without treating ess as inherently a
past-tense marker. The separation can be of any distance — five hours or five years — as long as
speaker and listener agree the situation and the actual reality are separated (examples with "just
now" vs. "five hours ago," p.388-389). In colloquial speech ess can also mark *future* events when
paired with a conditional adverb like nayil(i)myen 'if tomorrow' (p.390), which the author explains
via two possible mechanisms: (a) a shift of the speaker's Ground to a future point, from which the
event is viewed as an already-established fact; or (b) a broader actuality/non-actuality split in
which *all* non-actual situations — past, hypothetical, or future — are uniformly marked by the
remote tense, a cross-linguistically unremarkable pattern the author compares to a hypothetical
future-world SF example sentence. ess likewise marks *counterfactual/hypothetical unreality*
("우리도 갔으면 좋겠다" / wulito kassumyen cohkeyssta, "It might be good if we went," contrasted with the
neutral open-condition "우리도 가면 좋겠다" / wulito kamyen cohkeyssta, "It might be good if we go" — only
the first presupposes we are *not* going). The chapter's own summary diagram (Figure 4, p.392)
places reality and irreality as two separate planes, each independently able to host a "remote" point
relative to the speaker's Ground.

### 8.1.3 Remote Tense (II): ess-ess

When ess-ess is used, the speaker sets up a second, surrogate platform at a point in the *past*
reality, and views the situation as remote *from that past platform* — not from the actual (present)
platform directly. The author distinguishes the two ess's by superscript: ess¹ (remote viewed from a
platform in the past) vs. ess² (remote viewed from the actual/present platform), so ess¹-ess²
compounds to mean "removed from a past platform which is itself removed from the actual area" — a
doubly remote construction. Minimal pair (p.393): "그 때 한강물은 맑았다" (ku ttay hankangmulun malkassta,
"At that time the water of the Han River was clear," plain ess) vs. "그 때 한강물은 맑았었다" (...malkassessta,
"...had been clear," ess-ess). Though the objective temporal distance may be identical, ess-ess
produces a markedly greater *psychological/epistemic* distance for native speakers, because a
surrogate ground is set up looking backward at a discontinuous earlier world-state (the author's
worked example: the Han River's present heavy pollution makes its earlier clean state feel like a
different, disconnected world, licensing ess-ess). A related but distinct case is also noted: a
speaker narrating a past event so vividly that they "forget" their actual-reality platform and
project themselves into the described scene may instead *use the actual tense* for past narration
(p.394) — the mirror-image phenomenon to ess-ess.

### 8.2.1.1 Resultative and Imperfective (matrix sentence): -e iss vs. -ko iss

Two aspectual constructions in main clauses: **-e issta** (goal marker -e, like English 'to,' + the
existential verb iss) is resultative/perfective-with-resultative-meaning — the subject is located at
the end of a completed process (그 개구리는 죽어 있다 / ku kaykwulinun cwuke issta, "The frog is
dead/in the state of being dead"). **-ko issta** (partitive marker -ko + iss) is imperfective — the
subject is located at a midpoint within an ongoing process (그 개구리가 뛰고 있다 / ku kaykwulika ttwiko
issta, "The frog is jumping").

### 8.2.1.2 Imperfective (II): te / tela

te (as a sentence-ender form, tela) marks that the speaker observed a process at just one
midpoint, with no knowledge of its beginning, end, or what happened afterward — diagrammed as a
dashed/incomplete circle at a surrogate platform G′, distinct from the current G. This yields a
non-committal, "I'm not sure what happened since" flavor, contrasted directly against plain ess
(definite past-completion) and plain actual tense (ongoing-now) in a three-way minimal set answering
"Where is Chelswu now?" (p.397): "도서관에 있었다" (issessta, was there, now unknown) vs. "도서관에 있다"
(issta, is there now) vs. "도서관에 있더라" (isstela, saw him there, can't speak to now — judged the most
pragmatically appropriate answer of the three, since it is neither overclaiming nor underclaiming).
tela can also impose a processual/imperfective reading onto an event normally construed as a complete
whole (e.g. commenting on a movie one has fully seen, 제미있었다/caymiissessta "it was interesting" vs.
제미있더라/caymiisstela "it was interesting [on my part, as one viewing among many]," p.398) by
reframing a single complete viewing as one instance within a repeatable, ongoing process (many
screenings, many viewers' opinions).

### 8.2.1.3 Imperfective (III): ess-te

ess (perfective/completion) and te (imperfective/ongoing-process) look incompatible but combine
productively: the speaker treats one *completed* event as just one link within a larger, still-open
*process* made up of a series of sub-events. Example (p.399-400): "영어 숙제만 다 했더라" (yenge
sukceyman ta haysstela), "He finished only the English assignment [but I can't speak to the rest]" —
the English assignment alone is a completed whole, but it is only one item within the larger,
unfinished series of "all his homework assignments."

### 8.2.2 Aspect in Modifying Clauses (overview)

The modifying/relative clause in Korean uses a distinct four-way aspect-marker system (un, ten, nun,
ul), illustrated throughout with mekta 'eat': mekun (perfective), mekten (imperfective I), meknun
(imperfective II), mekul (unrealized/unspecified). Notably, ten and ul can co-occur with the remote
tense marker ess (ess+un/essten/essnun(?)/essul), though the author flags that essun and essnun sound
questionable (marked with "?") while esste(n) and essul are fully natural — the shared final -n across
three of the four combinable forms is noted as a possible (but not pursued) common semantic thread of
"realized."

### 8.2.2.1 Perfective: un

un presents a situation as a single unanalyzable whole, beginning-middle-end collapsed into one unit
— requiring the observer to stand at a distance (diagrammed, p.403, as a building seen whole from
outside vs. only partially from within). Perfective/imperfective choice is not inherent to the
situation but is the *speaker's choice of viewpoint* — the same partially-read book can be called
either "내가 읽은 책" (the book I read, perfective) or "내가 읽던 책" (the book I was reading, imperfective)
depending on how the speaker frames it (p.403). The author distinguishes how un behaves across verb
classes: with **accomplishment** verbs (build, write, knit) un means the process's logical goal has
been reached (지은 집 'the house [someone] built,' p.404); with **achievement** verbs (catch, find,
hit) un likewise denotes goal-reached, but instantaneously rather than cumulatively (잡은 토끼 'the
rabbit I caught,' p.404); with **activity** verbs that lack an inherent terminal point (make noise,
sing, work) — including instrument-object transitives like 쓴 톱 'the saw we used' — un's perfective
form simply denotes that the activity took place at all, regardless of any goal (떠든 학생 'the student
who made noise,' p.404-405): "as soon as he made a noise, we can say that he made a noise."

### 8.2.2.2 Imperfective (I): ten

ten views a situation from within, seeing only a shaded middle portion and excluding both endpoints —
diagrammed (p.406) as a dashed outer rectangle (the whole process) with a shaded inner band (the
observed portion) and a dotted triangle below marking the observer's restricted vantage point G′.
With accomplishment verbs, ten means the situation was mid-process and had not reached its goal at
the time of observation (지은 집 'the house that was built' vs. 짓던 집 'the house [we] were building,
[that later] collapsed,' p.406). A head noun can itself be structurally ambiguous between a specific
referent and a generic type, and ten resolves differently for each: "우리가 짓던 집들" (cisten ciptul,
p.407) can mean either a single specific under-construction house, or — more interestingly — a *type*
of house a group was producing, where ten marks that the group's production-period is only part of
that type's longer overall history (its production may have started before, or continued after, by
other builders) — illustrated also with a sweater-knitting-factory example (p.407). With
consumption/experience verbs (drink, search-for, eat) ten yields genuine two-way ambiguity: 마시던 술
(masiten swul, p.408-409) can mean either "the remaining portion of a specific drink I was partway
through" or "a generic type of drink I used to [habitually] drink [but no longer do]" — diagrammed
(Figure 14, p.409) as a bottle with the consumed portion shaded. The same dual reading extends to
locative and temporal head nouns: 묵던 여관 ('the inn we were staying at') can be viewed either
mid-stay or after departure (p.410), and 산 해/살던 해 ('the year we lived there' vs. '...were living
there') frames a single year either as a whole or as one portion within the speaker's longer life
(p.411).

### 8.2.2.3 Imperfective (II): nun

nun marks synchronicity between the situation and a reference time — usually the utterance moment,
but sometimes a past reference point instead. Near-synchronous, in-progress situations observed live
are the clearest case (저기 택시를 타는 분 'the man who is getting in a taxi [right now],' p.410-411). nun
also covers situations the speaker judges to be definitely/currently scheduled, even if not literally
happening at the instant of speech (내일 떠나는 분 'those who leave tomorrow,' p.412), and habitual/
generic facts valid at utterance time even though not actively occurring right then (아침 일찍 일어나는
사람들 'people who get up early in the morning,' p.412-413). When the reference time is a past point
rather than the utterance time, nun still marks synchronicity with *that* past point rather than with
now (그 때 자는 아이를 깨웠다 'they woke up a child who was sleeping then,' p.413).

### 8.2.2.4 Unrealized or Unspecified Aspect: ul

ul marks that a situation is yet to be realized, with the reference point usually (but not always) at
utterance time, situation time following it (diagrammed p.414 as a timeline: utterance-time ... then
situation-time). 이것이 내가 먹을 사과이다 'this is an apple that I am going to eat' (p.413). The
reference point need not be "now": 지난 학기에 쓸 책이 이제 왔다 'the book I was to use last semester has
come now' (p.414) places the reference point before last semester, not before the utterance. A
notable idiosyncratic use: ul combined with the noun ttay 'time' (ul ttay, 'when...') can describe
either future or *past* events (나는 그를 작년에 미국 갈 때 만났다 'I saw him on my way to America last
year,' p.414) — the construction denotes the time *during which* a situation develops/unfolds,
regardless of whether that interval itself lies in the speaker's past or future. A compound form,
-ess-ul ttay, additionally contrasts with plain ul ttay by viewing the situation as a completed whole
rather than mid-development: 서울 갈 때 만났다 'I saw him when I was on my way to Seoul [en route]' vs.
서울 갔을 때 만났다 'I saw him when I had arrived in Seoul [already there]' (p.415).

### 8.2.2.5 Completion-Imperfective: ess-ten

ess (perfective) and ten (imperfective) again combine, this time within modifying clauses: a
perfective/completed situation is presented as merely one link in a wider chain, broadening the
speaker's frame beyond that single completed situation. Three-way contrast (p.416): 이것이 우리가 어릴
때 산 집이다 'the house we lived in [bought] when young' (un, whole history viewed as the identifying
fact) vs. ...살던 집이다 'the house we were living in when young' (ten, viewed from inside, incomplete)
vs. ...살았던 집이다 'the house we had lived in when young' (ess-ten, one completed residence situated
among a wider series of houses the speaker has lived in over a lifetime).

### 8.3 Modality — overview and the four-verb continuum

Modality expresses the relation between a situation and reality/fact, via varying degrees of
epistemic distance, using the general construction: **[[[clause](-Aspect Marker)][dependent-noun
head]] (Case Marker) verb**. The clause attaches to its head dependent noun via one of the four
clausal aspect markers (un/ten/nun/ul), except for one pattern (8.3.1.1.e) that uses none at all. The
verb is drawn from a closed set of four positive/negative pairs forming a certainty continuum
(diagrammed p.417-419, Figures 10-11): **i** 'be' (most certain) > **al** 'know' ≈ **iss** 'exist' >
**ha** 'do' (least certain/stable), with negative counterparts **ani** 'not be', **eps** 'not exist',
**molu** 'not know'. Separately, within any one dependent-noun-plus-verb combination, the choice among
the four *aspect* markers (nun > un > ten > ul) forms its own certain-to-uncertain scale. The
dependent nouns themselves cluster by which verb they typically pair with, forming four lexical
classes (i-class: kes, pa, kkatalk, the, tey, ttaymun; iss-class: cek, ttay, swu; al-class: cwul, pa,
kes, ci; ha-class: tus, ppen, chey, man) — note that kes and pa each straddle two classes.

### 8.3.1.1 kes + i: the certainty-scale paradigm and the keyssta decomposition

Across the five sub-patterns ([modifying clause]-nun/un/ten/ul/essten/essul + kesita, plus the
zero-aspect-marker pattern [clause]-Ø + kesiessta), the presence, absence, and identity of the aspect
marker linking clause to kes systematically encodes different degrees of confirmed-vs-unconfirmed
relation to reality. **-nun kesita** (p.420) marks that the situation can be checked against reality
*as the utterance is being made* — e.g. a live demonstration of how to cut a pineapple. **-un kesita**
(p.420) marks that the speaker has *already personally checked* the situation against fact — contrasted
directly with plain ess (그것을 훔치었다 'he stole it,' speaker is the personal source/witness) vs. 훔친
것이다 (hwumchin kesita, 'it is a fact that he stole it,' speaker presents it as independently
verifiable/factual rather than personal testimony) (p.421). **-ul kesita** (p.421-422) marks that the
relation is *not yet confirmed*, but the speaker has already judged the underlying situation to be
real and is confident it will eventually be confirmed (존은 곧 올 것이다 'John will probably come soon') —
the author notes this is one reason ul is often mislabeled a future-tense marker, when it is really an
aspect marker about confirmation-status, not clock time. **-essul kesita** (p.422) places the
situation in *past* reality specifically, with confirmation of the past-reality relation still
pending (존은 왔을 것이다 'John must have come'). **The zero-marker pattern, [clause]-Ø kesiessta /
keyssta** (p.423-424), is the chapter's most striking individual finding: traditionally treated as one
indivisible morpheme, the author argues it is phonologically and semantically decomposable as **kes**
('fact') + **i** ('be') + **ess** (remote/dissociation-from-fact), i.e. the absence of any aspect
marker before kes itself signals dissociation from established fact — paralleling ess's own
dissociative meaning. The phonological case: kesiessta contracts first to keyessta (y absorbs the
stem-final vowel sequence) and then to keyssta, a contraction pattern independently cross-verified
against four other unrelated verb stems ending in -y- + ess (meyessta→meyssta 'carried',
tteyessta→tteyssta 'removed', seyessta→seyssta 'counted', heyessta→heyssta 'rinsed') (p.423).
Semantically, keyssta as a modal marker implies the speaker alone determines/casually judges the
likelihood of a situation, explaining its common "determination" reading with first-person subjects —
minimal pair (p.424): 나는 내일 가겠다 (nanun nayil kakessta) 'I will go tomorrow' (speaker-determined
resolve) vs. 나는 내일 갈 것이다 (...kal kesita) 'I must/am going to go tomorrow' (potentiality anchored
in external reality, not the speaker's own will).

### 8.3.1.2 kkatalk, ttaymun, and pa (mental reality)

kkatalk 'reason' and ttaymun 'cause' are noted as having transparent meanings and are explicitly
excluded from further semantic analysis in this chapter (p.425). **pa** (p.425-426) is analyzed more
fully: it requires a concept of *mental reality* — private, personal consciousness/knowledge, distinct
from both factual (public) reality and unreality. Four sub-patterns: nun pa + i ('as I am telling
you...'), un pa + kath ('be the same as,' a relational verb that — unlike i — requires the perfective
marker un; used when the speaker assumes information already stated may not be in the listener's
awareness and re-presents it, even though it is technically "old" information: 말씀 드린 바와 같이 'as I
told you'), ul pa + molu ('not know,' implying puzzlement/helplessness since the situation is
unrealized and the agent has neither personal knowledge nor a way to decide: 어찌 할 바를 모른다 'I do not
know what to do'), and ul pa + ey (postpositional phrase marking a judgment made from the speaker's
own [unrealized-situation] viewpoint: 마실 바에야 'if (we) are going to drink [it anyway]...').

### 8.3.2 Nouns used with iss 'exist': cek, ttay, swu

**cek** 'occasion' pairs only with the perfective marker un + iss, and the whole construction
corresponds roughly to the English perfect ("has happened") — a completed event whose exact location
within the actual-reality sphere is left unspecified (여름에 눈이 온 적이 있다 'it has snowed in summer,'
p.427). **ttay** 'time' requires explicit modalization with ul (...ul ttayka isskeyssci) when combined
with the unrealized marker (p.427). **swu** 'way'/potential-means (8.3.2.1, p.428-429) marks that a
potential situation can connect to reality because no *physical or external* obstacle stands in the
way — explicitly contrasted with cwul, which concerns *mental* capacity instead (이 문제를 쉽게 푸는
수가 있다 'there is a way to solve this problem,' using the present-imperfective nun form; 나는 운전할 수가
있다 'I can drive,' using ul — indicating ability/permission in the sense that no physical or legal
obstacle exists, without necessarily demonstrating it).

### 8.3.3 Nouns used with al/molu 'know/not know': cwul

**cwul** (8.3.3, p.429-430) denotes *mental* ability/capacity, contrasting directly with swu's
physical-ability sense. 나는 운전할 줄 안다 'I know how to drive' (mental ability applied to an activity
the subject-of-the-matrix-clause performs themself) is contrasted with 나는 그가 간/가는/갈 줄로 안다 'I
know that he went/is going/will go' (p.429), where cwul instead concerns a *cognitive judgment* about
someone else's situation rather than the speaker's own physical/mental performance capacity — the
author notes that although both uses share cwul's basic "mental" meaning, the two subjects differ (the
matrix-clause and embedded-clause subjects coincide in the ability-reading but differ in the
judgment-reading), which is what drives the different interpretations from the same basic meaning.
(ci, the fourth al-class noun named in the 8.3's opening inventory on p.419, is not separately
developed within this chapter's assigned pages.)

### 8.3.4 Nouns used with the verb ha 'do': tus, ppen, man, chey

Modal constructions built on ha are described as the weakest/least stable end of the certainty
continuum (p.430). **tus** 'appearance'/'expression'/'effect' (8.3.4.1) pairs with all three aspect
markers un/nun/ul (+ ha, or siph 'seem' as an alternative governing verb — tus + siph specifically
yields a 'vague feeling' sense): 비가 온/오는/올 듯 하다 'it looks like it rained/is raining/will rain'
(p.431). A doubled contrastive construction, X-tus Y-tus hata (with opposite-polarity clauses X and
Y), expresses a roughly fifty-fifty uncertainty: 비가 온 듯 만 듯 하다 'it looks as if it rained, but then
again it doesn't look like it raned [sic — rained]' (p.431). The author explicitly notes that any tus
judgment is grounded in appearance/feeling rather than evidence like reason or cause. **ppen** 'point
(of/near)' (8.3.4.2) occurs only with ul, marking that an event came close to but did not actually
happen: 그는 넘어질 뻔 했다 'he was on the point of falling down [but didn't]' (p.431). **man** 'norm'
(8.3.4.3) likewise occurs only with ul, marking that a situation almost — but not quite exactly —
meets a speaker-set (and therefore speaker-variable) standard: 그는 요즈음 살만 하다 'he is fairly well off
nowadays'; 그 곳은 가볼만 하다 'the place is fairly worth visiting' (p.432). **chey** 'make-believe'/
pretense (8.3.4.4) pairs with un (완료: pretended to have done — 잔 체 한다 'he pretends that he slept')
and nun (현재진행: currently pretending to do — 자는 체 한다 'he pretends that he is sleeping') (p.432).

### 8.4 Summary

The chapter's own closing summary (p.433, paraphrased) states its two central reframings: (1) tense
is reanalyzed via *remoteness* (absence of a situation from actual reality — covering both ordinary
past meaning and counterfactual-condition uses of ess) and *actuality* (presence/existence of a
situation), rather than a three-way past/present/future split; "tense" itself is redefined as simply
the absence-or-presence of a situation relative to the actual-reality area. (2) Aspect recognizes
three primary values — perfective, imperfective, and unrealized — with imperfective further splitting
into a one-platform type and a two-platform type, and all compound aspect markers' meanings are shown
to derive compositionally from their individual component morphemes' basic meanings. (3) Modality is
defined as epistemic distance between a designated situation and reality, expressed by the general
[Modifying Clause-(Aspect Marker)+Dependent Noun+Verb] construction, with the degree of epistemic
distance a product of the aspect marker's presence/absence/identity, the particular dependent noun
chosen, and the particular verb chosen. The author highlights the keyssta = kes+i+ess decomposition as
the chapter's single most significant individual finding, and frames the whole chapter's method
(postulating one basic meaning per morpheme, then deriving inferential/contextual meanings from it) as
a deliberate departure from what the author describes as an unproductive meaning-first, form-second
tradition among prior Korean grammarians.

---

## Korean — Established Vocabulary/Grammar: *A Korean Grammar on Semantic-Pragmatic Principles* — Chapter 9 "Verbal Connectives" (first half), sections 9.1–9.10

**Source:** Keedong Lee, *A Korean Grammar on Semantic-Pragmatic Principles*, Hankook Munhwasa (한국문화사), Seoul (publication year not visible anywhere in the pages read for this chunk — no printed copyright/printing date appears on pages 437–497; left blank per instructions rather than guessed). Pages 437–496 (printed page numbers; PDF page images 219–249, read as two-printed-pages-per-image spreads). Section 9.10 *myense* runs to the bottom of printed p.496; section 9.11 *una* begins cleanly at the top of printed p.497 (confirmed via image page-249's right-hand page) — the sibling chunk ch9b_connectives2.md begins exactly there, so this chunk and that one meet without overlap or gap.

**Coverage note.** Like the sibling chunk, this is a theoretical, pragmatics-focused monograph, not a pedagogical textbook — its "vocabulary" in this stretch is almost entirely the verbal-connective morphemes themselves (plus their compound/combinatorial forms and a handful of auxiliary-verb constructions built on them), not general lexicon. Ordinary content words recurring across the chapter's illustrative sentences (오다 "come", 비 "rain", 담배 "cigarette", 책 "book", etc.) are common beginner-level vocabulary already well attested elsewhere in this language's `established/` corpus and are not re-tabulated here.

**Non-redundant-supplement scoping, per the dispatch instructions:** four of the ten connectives covered here — 9.1 ciman (지만, "but/although"), 9.8 ko (고, "and"), 9.9 myen (면, "if"), and 9.10 myense (면서, "while") — already appear across this language's beginner/intermediate textbook extractions (confirmed via a grep of the existing `established/` corpus: 24 files mention 지만, 17 mention 려-forms, 17 mention 거나/거든/어다) at a bare gloss-plus-one-example level. **That bare pedagogical framing is explicitly NOT re-extracted here.** What *is* kept as new, and is this book's genuinely distinctive contribution: ciman's full "partial acceptance/partial rejection" semantic-pragmatic analysis and its extended treatment under Grice's four Cooperative-Principle maxims (quantity, quality, relevance, politeness) — a search of the existing corpus for any mention of Grice or the cooperative principle returned zero hits, so this is wholly new; ko's sequential-vs-coextensive ambiguity analysis, its five auxiliary-verb combinatorial constructions (ko issta/nata/malta/siphta, lyeko hata), and its two explicit minimal-pair contrasts against ese and myense; myen's six-way irrealis/realis paradigm (bare-stem, past-tense, future-tense -keyssumyen, counterfactual -telamyen, reported-proposition -tamyen, and the copula's irregular -ilamyen) and its degree-of-realizability argument; and myense's same-agent constraint, its "single force/cause behind two situations" licensing condition, its static-quality "common goal" use, and its moral-obligation/accusation reading under negation. The remaining six connectives — 9.2 le (러), 9.3 lye (려) and its five compounds (lyeko/lyemyen/lyenikka/lyenuntey/lyetaka), 9.4 ese (어서), 9.5 eta (어다), 9.6 kena (거나), and 9.7 ketun (거든) — are treated as essentially new: le/lye's restrictive locomotion-verb-only distribution and the fine le-vs-lye split is not covered at beginner level at all, eta is rarely taught, and kena/ketun's morphemic decomposition (ke + na / ke + tun) and their minimal-pair contrasts against myen and telato go well beyond the bare "or" / basic-conditional glosses that do appear in a few textbook files. **Vision reading:** this is the same clean, legible library scan as the sibling chunk; no handwritten marginalia, underlining, or pencil annotation was found anywhere in the assigned page range (pages 437–496).

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 지만 (ciman) | "although/but" — used when the speaker partially accepts and partially rejects the content of an utterance (the ciman-clause is what's accepted, the main clause what's rejected) | verbal connective suffix | core | — | — | — | — | grammar_reference | n/a | verified | p.437–446. 9.1. Distinct from a simple coordinate/causal conjunction: with coordinated assumptions (e.g. "cheap and durable"), either part alone can be accepted/rejected; with causally-linked assumptions, either the cause or the result part can be independently accepted/rejected (p.438–439). Also used to accept an overt statement while rejecting its covert implication (e.g. accepting a reported command while rejecting the speaker's authority to give it, p.440–441). The chapter's most distinctive content is its back half (p.441–446): ciman is reanalyzed under Grice's (1967) four Maxims of Conversation — Quantity (forestalling "you're repeating yourself"), Quality (flagging insufficient evidence for an assertion), Relevance (flagging a topic shift/non sequitur), and Politeness (flagging an imposition on the addressee) — in each case the ciman-clause preemptively signals the speaker's own awareness of violating the maxim, forestalling the addressee's negative reaction. |
| 러 (le) | purposive connective: "in order to" — restricted to locomotion verbs in the main clause | verbal connective suffix | core | — | — | — | — | grammar_reference | n/a | verified | p.447. Used only when a verb of locomotion (e.g. 오다 "come", 가다 "go", 다니다 "go about") appears in the main clause; with a non-locomotion main verb (e.g. existential 있다 "be at"), le is ungrammatical and lyeko (9.3.1) is required instead. |
| 려 (lye) | bound intention/purpose morpheme — never occurs alone, only fused onto following connective morphemes | bound verbal morpheme | core | — | — | — | — | grammar_reference | n/a | verified | p.448. The broader, less main-verb-restricted counterpart to le; combines productively with ko, nuntey, nikka, taka, and myen (see compounds below), each combination retaining the meaning already established for that connective. |
| 려고 (lyeko) | "intending to / for the purpose of" — the subject does E for the purpose of P | compound verbal connective (lye + ko) | core | — | — | — | — | grammar_reference | n/a | verified | p.448–449. 9.3.1. ko here contributes only its general contiguity meaning; used freely with non-locomotion main verbs where bare le is blocked (e.g. "intending to withdraw money, he came to the bank," unlike le's restriction). |
| 려면 (lyemyen) | "if (the subject) intends to..." — conditional used when the speaker is unsure of an agent's intention and tentatively assumes a world in which the agent intends the action | compound verbal connective (lye + myen) | core | — | — | — | — | grammar_reference | n/a | verified | p.449–450. 9.3.2. Frequent in directive/suggestion contexts: "if you want to learn Korean, keep company with Koreans" — the speaker doesn't know the addressee's actual intention but frames advice conditionally on it. |
| 려니까 (lyenikka) | "while intending to do A, B happens (unexpectedly)" | compound verbal connective (lye + nikka) | core | — | — | — | — | grammar_reference | n/a | verified | p.451. 9.3.3. The subject meets unexpectedly with event B while in the process of intending/about to do A — e.g. "I was about to read a book when a friend came," "I was about to swim when I got a stomachache." B is consistently something the subject did not expect. |
| 려는데 (lyenuntey) | "while intending to do A, [background:] B" — the nuntey-clause supplies background the addressee is to draw an inference from | compound verbal connective (lye + nuntey) | core | — | — | — | — | grammar_reference | n/a | verified | p.451–452. 9.3.4. Composes lye's intention meaning directly with nuntey's general background-introducing function (independently treated at length in sibling chunk ch9b's §9.14): the agent's intention to do A is presented as background against which the addressee is to interpret B — e.g. "while I was about to leave home, he came to see me" invites the inference that the visit was perhaps inconvenient. |
| 려다가 (lyetaka) | "intended to do A, but [changed mind/was interrupted and did not carry it out]" | compound verbal connective (lye + taka) | core | — | — | — | — | grammar_reference | n/a | verified | p.452–453. 9.3.5. Represents an intention that is NOT carried through to action (contrast with lye-ko, where the intention typically precedes actual pursuit) — diagrammed as intention connected to Ø (null) rather than to action. E.g. "I was intending to speak in English, but spoke in Korean"; "I was intending to go to work, but changed my mind." |
| 어서 (ese) | "and then / because" — connects two sequential events where the second takes place in the resultant location, posture, or (metaphorically) state produced by the first | verbal connective suffix | core | — | — | — | — | grammar_reference | n/a | verified | p.453–460. 9.4. The chapter's central argument: ese's meaning is not reducible to bare temporal sequence (contrast with ko, which can also denote sequence but without this resultant-state/location component). Illustrated across locomotion verbs (reaching a market → buying there), posture verbs (lying down → reading in that posture), and metaphorically extended to abstract "container" states (being sick → going home "in"/"out of" that state) and causation (heavy rain → flooding). Can be genuinely ambiguous between a "state container" reading and a stronger causal reading depending on context (p.456–457, worked old-age/death example). Minimal-pair contrasted against ko at length (p.458–460): swapping ese for ko in the same sentence either changes the meaning (reclining-posture reading disappears) or produces an awkward sentence (when the two events "should" be causally related but ko merely lists them). |
| 어다(가) (eta / etaka) | "do A [at one place] and transfer the result to a different place" — contrasted directly against ese, which requires the same place for both events | compound/variant verbal connective (eta, optionally extended etaka) | core | — | — | — | — | grammar_reference | n/a | verified | p.460–462. 9.5. Minimal pair with ese: "cieta tulyessupnita" (cooked the rice [here] and gave it [elsewhere]) vs. "ciese tulyessupnita" (cooked and gave it, same place) — eta explicitly marks that the object is carried to a place different from where the first action occurred; ese implies same-place. Also used for a directional "shift of viewing angle" sense with motion/perception verbs: naylyeta "look down[ward, from above]," cyeta "look up[ward]," nayta "look out[ward]," tulyeta "look in[ward]," tolata "look around" (p.462) — a small closed paradigm of directional-viewpoint compounds. |
| 거나 (kena) | "whether...or (it doesn't matter to the speaker)" — marks indifference between two or more named alternatives | compound verbal connective (ke + na) | core | — | — | — | — | grammar_reference | n/a | verified | p.463–464. 9.6. Morphemically decomposed: ke marks the existence of a situation (the speaker believes the named event is/was occurring), na marks a choice among non-primary/secondary alternatives of no real concern to the speaker. E.g. "whether he is fighting or not, I don't care" — the speaker believes the fighting is real (ke) but treats the choice as irrelevant to him (na). |
| 거든 (ketun) | conditional connective used only in imperative/hortative sentences: marks a future condition that is likely to occur, because it is determined by or results from an already-in-progress or scheduled prior situation | compound verbal connective (ke + tun) | core | — | — | — | — | grammar_reference | n/a | verified | p.464–469. 9.7. Morphemically decomposed: ke = existence, tun = likelihood. Three explicit minimal-pair contrasts structure this section: **vs. myen** (p.464–467) — myen's condition is purely hypothetical with no presupposed prior situation, while ketun's condition is grounded in a prior situation already underway that makes the outcome likely (e.g. "when you are hungry [from already fasting], eat" vs. the purely hypothetical "if you are hungry, eat"); also usable with past tense, same likelihood-vs-hypothetical split. **vs. telato** (p.467) — ketun is used when the speaker judges the named condition likely to occur, telato (9.16, treated in sibling chunk ch9b) when judged unlikely. |
| 고 (ko) | "and" — the basic meaning is contiguity between two or more events/situations; sequential, coextensive, and (inferred, not intrinsic) consequential readings all derive from this one general meaning plus verb semantics and world knowledge | verbal connective suffix | core | — | — | — | — | grammar_reference | n/a | verified | p.469–484. 9.8. Two readings are structurally distinguished and diagrammed: **sequential** (event B follows event A, boxes side by side) vs. **coextensive** (event/state A's result is carried over and coexists with event B, boxes stacked) — which reading obtains is determined by verb type and world knowledge, not by ko itself (worked examples: 모자를 쓰고 나갔다 "put on a hat and left" is genuinely ambiguous between "wearing the hat" and "without it," turning on whether "putting on" is construed as a contact verb whose resultant state persists). A further "consequential" sense (e.g. "beat his wife and ran away" implying the running-away was to avoid retaliation) is explicitly argued to be an addressee-side inference from world knowledge, not an intrinsic meaning of ko (p.474). | 
| -고 있다 (ko issta) | progressive aspect: "is [in the middle of] V-ing" | compound construction (verb-ko + existential issta) | core | — | — | — | — | grammar_reference | n/a | verified | p.475. 9.8.1.1. The activity is construed as an abstract place/location, and the subject is said to exist "in" it — same location/container metaphor independently argued for ese (9.4) and ko's coextensive reading. |
| -고 나다 (ko nata) | "to be done with / through with V-ing" — the subject comes out of (moves out of) the activity, construed as an abstract location | compound construction (verb-ko + nata "come out") | core | — | — | — | — | grammar_reference | n/a | verified | p.475. 9.8.1.2. Directly mirrors -ko issta but in the "coming out of" direction, confirming the location-metaphor reading of ko's coextensive sense. |
| -고 말다 (ko malta) | "end up V-ing [despite resistance/against the subject's wish]" or, with intended actions, "finally fail to resist and V" | compound construction (verb-ko + malta "stop/come to an end") | core | — | — | — | — | grammar_reference | n/a | verified | p.475–478. 9.8.1.3. Two distinguished sub-uses, diagrammed with +/- intention and +/- realization features: (i) "before-going" sense — a pre-existing intention/likelihood comes to an end upon the event's unwanted realization (e.g. "the plane finally took off [against my wish]"); (ii) a resistance-based sense — a prior resistance to doing something comes to an end upon being forced/giving in (e.g. "I was trying not to laugh, but gave in and laughed") — a sense of regret or reluctant concession is derived from the resistance reading. |
| -고 싶다 (ko siphta) | "want to V" — the named action/activity is construed as part of the subject's desire | compound construction (verb-ko + siphta "want") | core | — | — | — | — | grammar_reference | n/a | verified | p.478–479. 9.8.1.4. With a third-person subject, the normally-stative siphta must be converted to a nonstative form (a morphosyntactic agreement fact noted but not elaborated in depth here); no such change needed with first-person subjects. |
| -려고 하다 (lyeko hata) | "intend to V" — one's intention to do something construed as part of one's mental activity | compound construction (lye + ko + hata, the maximally schematic verb covering both mental and physical activity) | core | — | — | — | — | grammar_reference | n/a | verified | p.479–480. 9.8.1.5. hata's own abstractness/schematic quality is the explicit mechanism argued to let it host both the physical sense of "doing" and the mental sense of "intending." |
| 면 (myen) | "if" — presents events in the non-real world (encompassing both uncertainty and outright hypothetical/irrealis conditions), contrasted against uni and ese, which present events in the real world | verbal connective suffix | core | — | — | — | — | grammar_reference | n/a | verified | p.484–490. 9.9. Six combinatorial environments distinguished, each covered as its own subsection: bare-stem-myen (ambiguous between an uncertain-but-possibly-true reading and a known-false hypothetical reading, diagrammed as myen spanning both "uncertainty" and "irrealis" regions, p.484–486); past-tense-myen (same ambiguity, used when the speaker judges the condition less likely than the bare-stem form would imply, p.486–487); -keyssumyen (future-tense-marked conditional, used when the speaker is unsure of the addressee's intention and frames a suggestion around it, p.486–487); -telamyen (te + la + myen, a genuinely counterfactual conditional — the speaker is committed to knowing the condition did NOT hold, p.487–489, sharply distinguished from the merely-ambiguous bare/past forms); -tamyen (ta + myen, used when the speaker has reservations about the truth of a reported proposition someone else has just asserted, p.489–490); and the copula ita's irregular conditional form -ilamyen (not the expected *-itamyen*, p.490). |
| 면서 (myense) | "while" — expresses that two situations take place at the same time | verbal connective suffix | core | — | — | — | — | grammar_reference | n/a | verified | p.491–496. 9.10. Four distinctive constraints/extensions argued beyond the bare "simultaneity" gloss: **same-agent requirement** — both situations connected by myense must be performed by the same subject, unlike ko (p.492); **single-force/cause licensing** — myense is only acceptable connecting two dynamic situations when a single underlying cause/force can be construed behind both (wind blowing + thunder = both from one storm-force, acceptable; wind blowing + trees shaking by some unrelated cause = unacceptable, p.492–493); **static-quality "common goal" use** — myense can link two static qualities of a thing when both tend toward one shared, more-encompassing goal (e.g. cheap-and-good socks both serving the goal of being worth buying, p.494); **moral-obligation/accusation reading under negation** — when the speaker believes A and B should coexist (e.g. making a promise and keeping it) but the main clause is negated, myense implies an accusation of discrepancy between words/intent and deeds, with the negator 안 (internal, subject's own choice) producing a sense of willful accusation and 못 (external, forces beyond the subject) producing a sense of sympathy instead (p.494–496). |

**Morpheme breakdown (agglutinative compound connectives).**

> **려고 (lyeko)** = 려 (lye, intention/purpose) + 고 (ko, contiguity connective) — "doing E for the purpose of intended P" (9.3.1).

> **려면 (lyemyen)** = 려 (lye, intention) + 면 (myen, conditional) — "if [the agent] intends to..." (9.3.2).

> **려니까 (lyenikka)** = 려 (lye, intention) + 니까 (nikka, "upon/while") — "while intending A, B happens unexpectedly" (9.3.3).

> **려는데 (lyenuntey)** = 려 (lye, intention) + 는데 (nuntey, background-introducing connective) — "intending A, [against that background:] B" (9.3.4).

> **려다가 (lyetaka)** = 려 (lye, intention) + 다가 (taka, interruption/reversal connective — see sibling chunk ch9b §9.15 for taka's independent, fuller treatment) — "intended A but it was interrupted/abandoned before being carried out" (9.3.5).

> **거나 (kena)** = 거 (ke, marks existence of a situation) + 나 (na, marks indifferent choice among secondary alternatives) — "[A exists,] but choosing among A/not-A (or A/B) doesn't matter to me" (9.6).

> **거든 (ketun)** = 거 (ke, existence) + 든 (tun, likelihood) — "given an existing/in-progress prior situation, [this future condition] is likely" (9.7).

> **려고 하다 (lyekohata)** = 려 (lye, intention) + 고 (ko, contiguity) + 하다 (hata, maximally schematic verb covering mental and physical activity) — "to intend to [do]," built from already-established lye+ko plus a verb whose own semantic schematicity licenses both a physical "do" and mental "intend" reading (9.8.1.5).

## Grammar points

### 9.1 ciman (지만) — partial acceptance/partial rejection, and Grice's Maxims

Lee's central claim is that ciman is used whenever a speaker partially accepts and partially rejects the content of a prior utterance: what's accepted is packaged in the ciman-clause, what's rejected in the main clause. With a coordinate pair of assumptions ("cheap and durable"), either assumption can independently be accepted or rejected (p.437–439, VW gas-mileage and price/durability examples); with a causally-linked pair, either the cause-part or the result-part can be independently accepted or rejected (rain→good harvest example, p.439). Ciman also operates over covert implications, not just overt content: accepting a reported promise's literal content while doubting the speaker's sincerity in making it (p.440–441), or accepting an order's content while rejecting the order-giver's authority to issue it (p.441). The chapter's most distinctive move is reanalyzing ciman under Grice's (1967) four Maxims of Conversation (p.441–446): **Quantity** (a speaker about to repeat already-known information uses a ciman-clause to preemptively acknowledge "you may know already, but..."); **Quality** (a speaker lacking adequate evidence for an assertion flags this with a ciman-clause before making the claim anyway); **Relevance** (a speaker introducing an off-topic point uses ciman to flag the deviation, "this isn't directly relevant, but..."); **Politeness** (a speaker imposing a request on the addressee uses ciman to acknowledge the imposition beforehand, "I know this may bother you, but..."). In each maxim, the structural logic is the same: the speaker anticipates a negative reaction from the addressee for violating a conversational norm and uses the ciman-clause to forestall it.

### 9.2 le (러) and 9.3 lye (려) — purposive/intentive, and lye's five compounds

Le denotes purpose but has a narrow distribution: it is used only when the main clause contains a locomotion verb (ota "come," kata "go," tanita "go about," etc., p.447) — with a non-locomotion main verb such as existential issta "be at," le is ungrammatical and lyeko must be substituted instead (worked minimal pairs, p.448). Lye is the broader counterpart — a bound morpheme that never surfaces alone, only fused onto other connectives — and five such compounds are treated in turn (p.448–453): **lyeko** (9.3.1, "intending to," unrestricted to locomotion verbs, e.g. "intending to buy a car, he is saving money"); **lyemyen** (9.3.2, "if [the agent] intends to...," a conditional used when the speaker is unsure of the addressee's actual intention, frequent in advice/suggestion contexts like "if you want to learn Korean, keep company with Koreans"); **lyenikka** (9.3.3, "while intending A, B happens unexpectedly," e.g. "I was about to read when my friend came"); **lyenuntey** (9.3.4, intention + the background-introducing function of nuntey — the agent's unrealized intention is presented as context the addressee is to interpret a following event against); and **lyetaka** (9.3.5, "intended to do A, but [changed mind/was interrupted]" — diagrammed explicitly as intention-connected-to-Ø rather than intention-connected-to-action, contrasting with lyeko's intention-connected-to-action pattern, p.452–453).

### 9.4 ese (어서) — the location/state-container metaphor, and contrast with ko

Ese connects two sequential events where the second takes place "in" the resultant location, posture, or (by metaphorical extension) abstract state produced by the first — not bare temporal sequence. Lee builds this up from concrete to abstract: locomotion verbs (reaching a market, then buying bread "there," p.454), posture verbs (lying down, then reading "in" that reclining posture, p.454–455), then abstract mental/physical states treated as containers one is "in or out of" (being sick → going home "in"/"out of" that state; being afraid → being unable to go outside "in" that state, p.455–456). With time expressions, ese can be genuinely ambiguous between this container reading and a stronger causal reading (being old → dying either "in that state" or "because of" it, p.456–457), and with concrete object-transfer verbs the two events connected by ese share a single object carried from the first action into the second (broiling a fish, then eating "the broiled fish," not some other fish, p.457–458). The section closes with an explicit, systematic minimal-pair comparison against ko (p.458–460): substituting ko for ese in the same sentence can change the meaning (the "in that posture" reading vanishes, leaving just two listed events) or produce an awkward/ungrammatical-feeling sentence (when the two events are conceptually too close to be merely "listed" rather than resultatively linked, e.g. "lay down and slept" sounds odd with ko because lying-down-then-sleeping aren't independent listed events).

### 9.5 eta / etaka (어다) — transfer connective, contrasted with ese; directional-viewpoint compounds

Where ese implies the two connected events happen at the same place, eta explicitly marks that the object of the eta-clause is carried to a *different* place for the second event — the chapter's central minimal pair is "cieta tulyessupnita" (cooked [here] and gave it [elsewhere]) vs. "ciese tulyessupnita" (cooked and gave it, same place, p.460–461). This place-shift meaning holds across several worked examples (writing a letter vs. broiling fish, each paired against its ese counterpart, p.461). A second use is treated separately: with verbs of seeing/motion, eta marks a shift of viewing direction or vantage point, yielding a small closed set of directional compounds — naylyeta "look down(ward, from above)," cyeta "look up(ward)," nayta "look out(ward)," tulyeta "look in(ward)," tolata "look around" (p.462) — glossed collectively as downward/upward/outward/inward/around.

### 9.6 kena (거나) — indifference connective

Morphemically decomposed as ke (marking the speaker's belief that a named situation exists/is occurring) + na (marking a choice among secondary alternatives the speaker regards as unimportant). The paradigm example: "ku nyesek ssawukena malkena nayka mwusun sangkwaniya" ("whether he's fighting or not, what's it to me") — ke commits the speaker to believing the fighting is actually happening, while na signals that resolving which alternative holds (fighting vs. not) is simply not the speaker's concern (p.463–464). The same pattern recurs across several worked examples (drinking/not drinking, singing/not singing, standing/not standing) all glossed with the same "I don't care whether..." indifference frame (p.464).

### 9.7 ketun (거든) — conditional with presupposed-likelihood, contrasted with myen and telato

Morphemically decomposed as ke (existence) + tun (likelihood). Restricted to imperative/hortative main clauses, ketun marks a future condition judged likely because it's grounded in a prior situation already underway or scheduled — contrasted at length against myen, whose condition is purely hypothetical with no such grounding (p.464–467): "payka kophumyen mekela" ("if you're hungry, eat") assumes a merely hypothetical hunger, while "payka kophuketun mekela" ("when you're hungry [from an ongoing fast], eat") presupposes the addressee is already fasting, making the hunger-condition a likely near-future outcome rather than a bare hypothetical. The same likelihood-vs.-hypothetical split is shown to persist with past-tense marking (p.467–469, doctor/patient medication example) and the chapter closes this section with a second contrast, against telato (p.467): ketun is used when the speaker judges a condition likely, telato (treated independently in sibling chunk ch9b §9.16) when judged unlikely.

### 9.8 ko (고) — contiguity, sequential vs. coextensive readings, five auxiliary constructions, and two minimal-pair contrasts

Ko's single general meaning — contiguity between two or more listed events — is argued to underlie several apparently distinct readings that are actually derived, not intrinsic: **sequential** (event B simply follows event A) vs. **coextensive** (event/state A's result persists and coexists alongside event B), diagrammed respectively as side-by-side vs. stacked boxes (p.470–473) — which reading obtains depends on verb semantics (contact/dress verbs like ssuta "put on a hat" license the coextensive "still wearing it" reading; verbs with no lasting resultant state like seswuhata "wash one's face" force the sequential reading) and world knowledge, never ko itself. A further "consequential" sense some sentences seem to carry (beating a wife, then running away — implying the running away was to escape retaliation) is explicitly argued to be an addressee-side pragmatic inference, not something ko itself encodes (p.473–474). Five auxiliary-verb constructions built on verb-ko are each given their own subsection (9.8.1.1–9.8.1.5, p.475–480): **-ko issta** (progressive, "the activity construed as a place the subject exists in" — the same container metaphor independently argued for ese); **-ko nata** ("to be through with," the mirror-image "coming out of" the activity-as-place); **-ko malta** ("end up V-ing" / "finally give in and V," with two sub-readings diagrammed by +/- intention and +/- realization — an unwanted intended event finally being realized, or a resistance finally breaking down, both yielding a sense of regret); **-ko siphta** ("want to," the activity framed as part of the subject's desire, with an agreement-driven stative-to-nonstative shift required for third-person subjects); and **-lyeko hata** ("intend to," built from lye+ko plus hata's own schematic abstractness, which the author argues is what licenses hata to host both a "do" and an "intend" sense). The section closes with two systematic minimal-pair contrasts (9.8.2.1–9.8.2.2, p.480–484): **ko vs. ese** — ko's coextensive reading can connect a static resultant state with a dynamic following event (mouth left open while sleeping, acceptable with ko), while ese requires the second event to plausibly follow from/depend on the first (opening the mouth "in order to" sleep is semantically odd, so ese is unacceptable there) — but the acceptability pattern reverses in other cases, turning on how conceptually close the two situations are construed to be (lying-down-then-sleeping: ko sounds odd, ese is natural, because the two are "too close" to be merely listed, p.481–482); **ko vs. myense** — myense requires both connected situations to be genuinely simultaneous *and* for both to be either dynamic or static (never one of each, and not two dynamic actions that structurally can't overlap, like getting into a moving taxi and the taxi's movement), where ko in its coextensive sense tolerates pairing a static state with a dynamic action (p.482–483, worked harmonica/singing and taxi examples).

### 9.9 myen (면) — the real/non-real world distinction, and six combinatorial environments

Lee contrasts myen against uni and ese (both of which present events as holding in the real world) by arguing myen presents events in the non-real world — a world that itself spans a spectrum from mere uncertainty to outright impossibility/counterfactuality (p.484). Six environments are worked through in turn: **bare-stem-myen** (p.484–486, genuinely ambiguous between "I don't know if it's true, but assuming it is..." and "I know it's false, but imagining a world where it were..." — diagrammed as myen spanning both the "uncertainty" and "irrealis" regions of a scale that also includes "realis"); **past-tense-myen** (p.486–487, the same two-way ambiguity, but used when the speaker judges the condition markedly less likely than the bare-stem form implies — explicit minimal pair: "if they go now" vs. "if they [had] gone now," the latter used when the speaker thinks going is basically off the table); **-keyssumyen** (p.486–487, future-tense-marked, used in conditional suggestions where the speaker doesn't know the addressee's intention, e.g. "if you'd like to go, please go"); **-telamyen** (p.487–489, te [retrospective/remoteness marker] + la [noncommittal sentence-ender] + myen — unlike the merely-ambiguous bare/past forms, this one is unambiguously counterfactual: the speaker is committed to the belief that the condition did NOT actually hold, e.g. "if he had worked hard, he'd be well-off now" implies he did not); **-tamyen** (p.489–490, used when the speaker has personal reservations about the truth of a proposition someone else has just asserted — a report-plus-doubt conditional, distinguished from telamyen's own stronger, speaker-internal counterfactual commitment); and the copula's irregular conditional **-ilamyen** (not the expected *-itamyen*, p.490, e.g. "if it's true that he's a doctor...").

### 9.10 myense (면서) — simultaneity with a same-agent requirement, single-force licensing, and an accusatory extension under negation

Myense's basic meaning is straightforward simultaneity (chewing gum while reading, p.491), but Lee argues for three further constraints/extensions that distinguish it from superficially similar connectives. **Same-agent requirement** (p.492): both myense-connected situations must share the same subject — a minimal pair against ese shows ese tolerates the "sat down, then turned off the light" sequential reading regardless of agent identity, while myense's simultaneous "turned off the light while sitting down" reading requires one and the same person doing both. **Single-force/cause licensing** (p.492–494): myense is only acceptable connecting two genuinely dynamic situations when a single underlying cause can be construed behind both — "the wind was blowing and the trees were shaking" is acceptable (one storm-force behind both), but is explicitly predicted to become unacceptable if the trees' shaking were caused by something unrelated to the wind; blazing flames and a strong smell (one fire) or a parting sea and an exposed seabed (one divine act, in the book's own stated example) both satisfy this constraint. **Static-quality "common-goal" use** (p.494): myense can connect two static qualities of a thing when both tend toward one shared, more-encompassing purpose — cheap-and-good socks, convenient-and-quiet neighborhoods — with the more general/encompassing quality typically given first. **Accusatory extension under negation** (p.494–496): when the speaker believes two things ought to co-occur (e.g., making a promise and keeping it) but the main clause is negated, myense carries an implication of discrepancy between words/intent and deeds — and the choice of negator matters: internal 안 ("not choosing to") yields a sense of willful accusation (e.g. "he's not working even though he's starving [and could]"), while external 못 ("not able to, due to outside forces") yields sympathy instead of accusation for the structurally identical sentence.

---

## Korean — Established Vocabulary/Grammar: *A Korean Grammar on Semantic-Pragmatic Principles* — Chapter 9 "Verbal Connectives" (second half), sections 9.11–9.19

**Source:** Keedong Lee, *A Korean Grammar on Semantic-Pragmatic Principles*, Hankook Munhwasa (한국문화사), Seoul (publication year not visible anywhere in the pages read for this chunk — front matter with a copyright/printing date was not in the assigned page range and none of pages 490–561 carries a printed year; left blank per instructions rather than guessed). Pages 497–560 (printed page numbers; PDF page images 246–281, read as two-printed-pages-per-image spreads). Chapter 9 ends at printed p.560 (blank verso page); the book's References section begins at printed p.561 and was correctly excluded as out of scope.

**Coverage note.** This is a theoretical, pragmatics-focused monograph, not a pedagogical textbook — its "vocabulary" in this chapter consists almost entirely of the verbal-connective morphemes themselves (and their combinatorial/compound forms), not general lexicon. Ordinary content words recurring across the chapter's illustrative sentences (의사 "doctor", 비 "rain", 춥다 "cold", 책 "book", etc.) are common beginner-level vocabulary already well attested elsewhere in this language's `established/` corpus and are not re-tabulated here — including them would just be padding, per the spec's "repeated drill" skip rule.

**Non-redundant-supplement scoping, per the dispatch instructions:** four of the nine connectives covered here (9.14 nuntey/는데, 9.15 taka/다가, 9.18 tolok/도록, 9.19 tunci/든지) already appear in this language's beginner/intermediate textbook extractions at a bare gloss-plus-one-example level ("but/and", "in the midst of", "so that/until", "whether...or"). **That bare pedagogical-level framing is explicitly NOT re-extracted here.** What *is* kept as new: this book's full semantic-pragmatic argumentation for each — e.g. nuntey's two-way introductory/suggestive-inference function (9.14.1–9.14.2, not a beginner-level distinction at all), taka's accomplishment-vs-activity-verb aspectual split and its combination with the perfective (`-e nohta-taka`) and intention (`lyetaka`) forms, tolok's resultative-vs-purpose dual viewpoint and its explicit minimal-pair contrast against the near-synonymous connective `-key`, and tunci's use across verbs/nouns/postpositions. The remaining five connectives (9.11 una, 9.12 ni/uni, 9.13 nu+ni/lako/myen, 9.16 telato, 9.17 to) are treated as essentially new — a search of this language's existing `established/` files turned up no coverage of these forms at all, consistent with the dispatch note that they are unlikely to appear in beginner textbooks. **Vision reading:** this is a clean, legible library scan; no handwritten marginalia, underlining, or pencil annotation was found anywhere in the assigned page range.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 으나 (una) | contrastive connective: "but/although" — contrasts qualities, or contrasts the speaker's expectation/belief against reality | verbal connective suffix | core | — | — | — | — | grammar_reference | n/a | verified | p.497–503. Three uses distinguished: (1) contrast between two qualities of a thing evaluated toward a shared purpose (9.11.1); (2) contrast between the speaker's preconceived knowledge and actual reality, glossable as "contrary to expectation" (p.498); (3) contrast used to flag a violated appropriateness/felicity condition of a speech act (asking, promising, asserting) — the speaker signals that an assumed condition (e.g. "the addressee doesn't already know the answer") turned out false (p.500–503). |
| 니/으니 (ni / uni) | connective marking a tentative causal relation the speaker notices/infers for the first time: "and so, (tentatively) because" | verbal connective suffix | core | — | — | — | — | grammar_reference | n/a | verified | p.503–514. Surface alternation: *-ni* after vowel-final stems, *-uni* after consonant-final stems (parallel to una's own 으-epenthesis). Covers three structural cases: (i) two near-simultaneous events where the causal link is only suspected (adverbs like 이상하게 "strangely", 뜻밖에 "unexpectedly", 갑자기 "all of a sudden" co-occur naturally, p.505); (ii) one event realized, the second not yet known (p.506–507); (iii) one event realized in the past, with an unresolved gap before the second (p.508–510, including a sub-case combined with the retrospective marker *-te-*, i.e. `-teni`, p.510). Also used to justify a proposal/command/question "from the addressee's assumed viewpoint" (9.12, p.510–514) — contrasted directly with the connective *ese*, which marks a definite, well-established (not tentative) causal relation; using *uni* where *ese* is expected implies the addressee is slow to grasp an obvious link (p.512–514). |
| 느 (nu) | bound comparison morpheme: marks that of two contrasted actions/activities, the one following is what the speaker prefers | bound verbal morpheme (combines only with following elements, never stands alone) | core | — | — | — | — | grammar_reference | n/a | verified | p.515. Does not occur independently — combines with *-ni*, *-lako*, and *-myen*; see morpheme breakdowns below. |
| 느니 (nuni) | "rather than A, B (is preferable)" | compound verbal connective (nu + ni) | core | — | — | — | — | grammar_reference | n/a | verified | p.516. 9.13.1. [A-nuni B]: B is more desirable/preferable than A. Notably cannot co-occur with past tense in the main clause (p.517, *kassta "went" is ungrammatical where *kakeyssta* "will go" is required). |
| 느라고 (nulako) | "at the expense of / doing A, with the (often undesired) side effect/cost B" | compound verbal connective (nu + la + ko) | core | — | — | — | — | grammar_reference | n/a | verified | p.517–519. 9.13.2. *la* = speaker's nonchalant-attitude marker, *ko* = contiguity connective. [A-nulako B] frames A and B as two inseparable sides of one situation — having A costs having B; also has a secondary reading where A and B are simultaneous and B is caused by A, but A is judged "not worth" B. |
| 느라면 (nulamyen) | "if one keeps on doing A (minor), one will come to B (major)" | compound verbal connective (nu + la + myen) | core | — | — | — | — | grammar_reference | n/a | verified | p.519. 9.13.3. *myen* = conditional marker; compositional meaning built directly from the nu+la+myen parts already established. |
| 는데 (nuntey) | background-information-providing connective: "and/but, against the following background..." | verbal connective suffix | core | — | — | — | — | grammar_reference | n/a | verified | p.519–529. Two functions distinguished, both going well beyond the beginner-level "but/and" gloss: **introductory function** (9.14.1, p.519–522) — draws the addressee's attention to an entity/event not yet in their consciousness, frequently opening folk tales and used to pivot topics in speeches/lectures; and **suggestive function** (9.14.2, p.522–529) — the *nuntey* clause is juxtaposed with an assertion, request, question, or directive so the addressee can draw an implicit inference the speaker wants conveyed but does not state directly (e.g. providing an unstated justification that softens an imperative, p.527–528, or blocking a listener's skepticism by pre-supplying evidential grounds, p.523). The author notes some *nuntey* clauses appear to encode contrast or causation, but argues the connective itself is semantically empty of that meaning — any contrastive/causal flavor is inferred from shared world-knowledge, not from *nuntey* (p.524–525). |
| 다가 (taka) | interruption/takeover connective: an ongoing process is interrupted, stopped short, or taken over by another action | verbal connective suffix | core | — | — | — | — | grammar_reference | n/a | verified | p.529–537. With present-tense-form verbs: splits by verb type — "accomplishment verbs" (have a goal/terminus) → stopped short of the goal; "activity verbs" (no terminus) → simply interrupted (p.529–531). With past-tense accomplishment verbs, denotes that an already-reached resultant state is itself broken/reversed by a later, often unexpected, event (p.531–533) — requires the action to be conceptually reversible. Also combines with the intention morpheme *lye* → *lyetaka*, "an intention/plan is abandoned before being carried out" (p.533–535), and with the perfective `verb-e nohta` → `verb-e nohsstaka`, denoting a resultant state that persisted for some time before being undone (p.536), contrasted with the bare past `verb-ess-taka`, where the undoing follows immediately (p.536). |
| 더라도 (telato) | strong concessive: "even if (an unlikely/extreme/counterfactual condition held)" | compound verbal connective (te + la + to) | core | — | — | — | — | grammar_reference | n/a | verified | p.537–539. 9.16. *te* + *la* = remoteness from present reality/validity; the added *to* (see next entry) layers in a comparison between a weaker/normal and a stronger/extraordinary condition. Explicitly contrasted with the plain concessive *to* (하다 → 해도 vs. 하더라도): *telato* presupposes the condition is less likely or realized to a lesser degree than what *to* alone would imply (p.538, minimal pair 4a/4b). Can combine with past tense to yield fully counterfactual conditionals (p.539, "even if the doctor had come earlier he would not have survived"). |
| 도 (to) | concessive/incremental particle used with verbs and adjectives (parallel to its use with nouns): "even though/even if"; with reduplication, intensifies a sense of unresolved increment | particle (used as a verbal connective when attached to verb/adjective forms) | core | — | — | — | — | grammar_reference | n/a | verified | p.540–549. Reduplicated forms (가도 가도, V-redup) intensify the "no matter how much..." increment reading, usable with verbs or adjectives, in either the positive or negative direction (p.540–541). In non-reduplicated conversational use, *to* marks an incremental comparison between two speakers' estimates, requests, or proposed courses of action — e.g. one speaker's guess/permission/suggested method is positioned as more/less extreme than another's on an implicit scale (p.542–548, several worked number-line and effectiveness-scale diagrams). The chapter closes this section (9.17) with examples where differing *to*-marked assumptions about a threshold condition (e.g. whether rain is sufficient grounds to cancel going out) produce two speakers' divergent real-world decisions (p.548–549). |
| 도록 (tolok) | "so that/until" — has two distinct viewpoints: a resultative ("gradually up to an end point") and a purposive ("toward a not-yet-reached goal") | verbal connective suffix | core | — | — | — | — | grammar_reference | n/a | verified | p.549–558. **Resultative viewpoint** (9.18, p.549–553): the *tolok* clause marks the degree/duration a process reached, incidental to the main clause; requires durative predicates in the main clause — instantaneous verbs (e.g. 깨다 "wake up") are ungrammatical unless negated or made durative, though plural subjects can license an otherwise-instantaneous verb if individual occurrences are spread over time (p.552–553). **Purpose viewpoint** (p.553–555): the main-clause event precedes/contributes toward the *tolok*-clause's (possibly unrealized) goal; ambiguity between the two readings is structurally regular, not accidental (worked example, p.554). **Minimal-pair contrast with -key** (p.554–558): *tolok* foregrounds the gradual process leading to a result/goal, while *-key* foregrounds only the resultant state itself, with no implication of duration or effort — tested across five near-identical sentence pairs (dough-softening, potato-frying, room-warming, persuasion, meeting-attendance). |
| 든지 (tunci) | "whether...or" / "no matter which" — marks the speaker's lack of preference among alternatives | particle/connective (usable with verbs, nouns, and postpositions; this section covers the verbal use) | core | — | — | — | — | grammar_reference | n/a | verified | p.558–559. 9.19. With present-tense verb forms, signals the speaker has no preference among the listed (often reduplicated A-tunci B-tunci) future actions and leaves the choice fully to the addressee — the defining feature is that the action is not yet realized, still "being contemplated." |

**Morpheme breakdown (agglutinative compound connectives).**

> **느니 (nuni)** = 느 (nu, comparison marker) + 니 (ni, connective) — base of the "rather A than B" reading (9.13.1).

> **느라고 (nulako)** = 느 (nu, comparison marker) + 라 (la, speaker's nonchalant-attitude marker) + 고 (ko, contiguity connective) — "A and B as two sides of one coin; having A costs B" (9.13.2).

> **느라면 (nulamyen)** = 느 (nu, comparison marker) + 라 (la, attitude marker) + 면 (myen, conditional marker) — "keep doing minor A, come to have major B" (9.13.3).

> **더라도 (telato)** = 더 (te, retrospective/remoteness marker) + 라 (la, attitude marker) + 도 (to, concessive/incremental particle) — stacks remoteness-from-reality onto the plain concessive to yield "even under an unlikely/extreme condition" (9.16).

> **느라타카 (lyetaka)** = 려 (lye, intention/futurity marker) + 다가 (taka, interruption connective) — "an intended-but-not-yet-carried-out plan is itself interrupted/abandoned," distinct from *taka* interrupting an already-ongoing action (p.533–535).

## Grammar points

### 9.11 una (으나) — contrastive connective

The connective *una* denotes contrast, used in three argued sub-patterns: contrast between two qualities of the same thing evaluated against a shared purpose (e.g. socks that are good-quality *una* overpriced, p.497); contrast between the speaker's prior expectation/general-world-knowledge and the actual observed state of affairs ("it should be warm in May, *una* it's still cold," p.498–499, glossable as "contrary to expectation"); and — the book's most distinctive contribution — contrast flagging a violated felicity/appropriateness condition on a speech act. Lee lays out explicit numbered felicity conditions for asking a question (the speaker doesn't already know the answer, believes the addressee might, etc., p.500) and for making an assertion (the speaker believes P, has evidence for P, etc., p.501), then shows *una* is the connective used when the speaker flags that one of these background conditions did not actually hold — e.g. "I asked Chelswu about it, *una* [=but, contrary to the implicit assumption that he'd know,] he said he didn't know" (p.500–501). The same logic extends to promises (p.502–503): *una* flags a violated felicity condition for promising, such as the speaker's actual intent to carry it out, or the addressee's actual desire for the promised act.

### 9.12 ni / uni (니/으니) — tentative-causation connective

*Uni* (after consonant stems) / *ni* (after vowel stems) is used when the speaker notices for the first time, tentatively, that event A leads to or is associated with event B, without having had time to verify the causal link — hence it naturally co-occurs with adverbs like 이상하게 "strangely," 뜻밖에 "unexpectedly," 갑자기 "all of a sudden" (p.505). The book works through a graded set of structural cases where this tentativeness arises: near-simultaneous events (p.504–505); one realized event with the second not yet known (p.506–507, "since he did well on the exam, he may have passed" — critically, the main clause here cannot be the past tense, only a tentative/future-oriented prediction); one realized past event with the second realized but of unverified connection (p.508–509); and a construction combining *uni* with the retrospective evidential *-te-* (`teni`), where the speaker reports something personally observed in the past without committing to its present relevance (p.510). Lee also argues *uni* can be deployed "from the addressee's assumed viewpoint" — the speaker personally knows a well-established relation but uses *uni* (rather than the "stronger" connective *ese*) to introduce it gently, as if it were new information to the listener, which extends to giving reasons for proposals, commands, and questions (p.510–514). The explicit contrast with *ese* is the chapter's clearest minimal-pair argument in this stretch: *ese* presupposes a definite, objectively well-established relation between two events, while *uni* presupposes only a suspected/tentative one from the speaker's (or addressee's) subjective vantage — using *uni* where the relation is actually obvious reads as unnecessarily explaining the obvious to the addressee (p.513–514).

### 9.13 nu (느) and its compounds: nuni, nulako, nulamyen

*Nu* is a bound comparison morpheme — it never occurs alone, only fused onto following elements (*-ni*, *-lako*, *-myen*). [A-nuni B] marks B as preferable to A (p.516, e.g. "I'd rather go into business than teach" — crucially disallowing a past-tense main clause, p.517). [A-nulako B] frames A and B as two sides of a single situation that cannot both hold — having A costs/is paid for by B, with a secondary reading where A and B co-occur but A is judged "not worth" the cost of B (p.517–519). [A-nulamyen B], compositionally built from the already-established *nu* + *la* + *myen* (conditional) parts, denotes "if one persists in doing the less-important A, one eventually arrives at major consequence B" (p.519).

### 9.14 nuntey (는데) — introductory and suggestive background connective

Lee argues *nuntey* has no inherent contrastive or causal meaning of its own (any such flavor readers perceive is inferred from shared world-knowledge, not encoded by the connective itself, p.524–525) — its real job is managing what is and isn't yet in the addressee's consciousness. In its **introductory function** (9.14.1), a *nuntey* clause draws the addressee's attention to an entity or event not currently in their mental focus, which the book notes explains its frequent appearance opening Korean folk tales ("Once upon a time, in this village there was a tavern, *nuntey*...", p.521) and its use in speeches/lectures to pivot topics. In its **suggestive function** (9.14.2), the speaker juxtaposes a *nuntey* clause (background) against a main-clause assertion/request/directive so the addressee can draw an unstated inference — e.g. providing evidential grounds that preempt skepticism toward a claim (p.523), or supplying an implicit justification that makes an otherwise blunt imperative milder and more reasonable-sounding (worked contrast: "Go to school quickly" vs. "It's already 8 o'clock, *nuntey* go to school quickly," p.527–528). The book is explicit that not every *nuntey* clause succeeds at this: a pair of facts with no shared inferential premise leaves the addressee unable to draw any conclusion at all and the sentence reads as merely odd (p.526).

### 9.15 taka (다가) — interruption and state-reversal connective

With present-tense verb forms, *taka*'s exact meaning is sensitive to verb type: "accomplishment verbs" (verbs with an inherent goal/terminus, e.g. 가다 "go [to a destination]") yield a "stopped short of the goal" reading, while "activity verbs" (no terminus, e.g. 뛰다 "jog") yield a plain "interrupted/taken over" reading (p.529–530). With past-tense accomplishment verbs, *taka* denotes that an already-completed resultant state is itself later broken or reversed by a new, often unexpected, event — explicitly restricted to actions the author characterizes as conceptually reversible (knitting/unknitting a sweater is the worked example, p.531). The connective also combines productively: with the intention morpheme *lye* → *lyetaka*, "a plan is abandoned before being carried out" (p.533–535, e.g. "I was intending to go to Seoul, *lyetaka* it rained and I couldn't"), and with the perfective `verb-e nohta` → `verb-e nohsstaka`, denoting a resultant state that persisted for some stretch of time before being undone — contrasted directly with the bare past `verb-ess-taka`, where the undoing follows immediately after completion with no persisting interval (p.536, minimal pair: "built a house and tore it down" vs. "had built a house [for a while] and then tore it down").

### 9.16 telato (더라도) — strong/counterfactual concessive

Built from *te* (remoteness from present reality/validity) + *la* (attitude marker) + *to* (concessive/incremental particle, see 9.17), *telato* expresses an additional condition judged unlikely or impossible to realize — layering an explicit comparison between a weaker/normal condition and a stronger/extraordinary one onto the plain concessive meaning of *to* (p.537). The book's central minimal pair is *-to* vs. *-telato* attached to the same verb: "Don't trust him even when he promises" (*hayto*) implies the promise may or may not happen, while "...even if he promises" (*hatelato*) presupposes the subject likely won't even make the promise at all — i.e. *telato* sits further out on a realizability scale than bare *to* (p.538). *Telato* combined with past tense yields genuinely counterfactual conditionals: "He would not have survived even if the doctor had come earlier" presupposes, and explicitly contradicts, the known fact that the doctor did not come in time (p.539).

### 9.17 to (도) — verbal/adjectival concessive-incremental particle

Parallel to its well-known nominal particle use, *to* attaches to verbs and adjectives with an incremental "even though/even if" meaning, intensified by reduplication (가도 가도 "keep on going and going, [yet] no end," usable toward either a positive or negative increment direction, p.540–541). Beyond the reduplicated idiom, the bulk of this section (p.542–549) is built from worked conversational exchanges in which two speakers' *to*-marked statements are placed on an explicit comparative scale — one speaker's price/age/time estimate versus another's more extreme alternative (several number-line diagrams, p.542–543), or one speaker's suggested method versus another's judgment of its (in)sufficiency, represented as points on an easy–difficult or less-effective–more-effective scale (p.546–548). The section closes by showing how two speakers' differing *to*-marked thresholds for the same real-world condition (e.g., is rain sufficient reason not to go out) predict their divergent subsequent decisions (p.548–549).

### 9.18 tolok (도록) — resultative/purposive connective, contrasted with -key

*Tolok* supports two distinguishable viewpoints on the same morpheme. The **resultative viewpoint** (looking back from the end point) marks the degree or duration a process reached gradually, incidental to the main clause (e.g. "wrote letters until my wrist ached," p.549–551) — this reading requires durative main-clause predicates; genuinely instantaneous verbs (e.g. 깨다 "wake up") are ungrammatical unless negated (turning the predicate into a durative state) or the subject is plural, in which case individually-staggered instantaneous events can still satisfy the durative requirement (p.552–553). The **purpose viewpoint** treats the *tolok*-clause's end state as a goal not yet reached, with the main clause's action understood as contributing toward or preceding it (p.553–555); the book notes this creates a structural, non-accidental ambiguity between the two readings in many sentences (worked diagram, p.554). The most distinctive content here is an explicit, sentence-by-sentence minimal-pair comparison against the near-synonymous connective *-key* (p.554–558): across five matched pairs (softening dough, frying potatoes crisp, warming a room, persuading/encouraging someone, securing meeting attendance), *tolok* consistently foregrounds the gradual process or duration leading to the result, while *-key* foregrounds only the resultant state itself, with no durational or effort implication — the book concludes *tolok* reads as more natural than *-key* whenever the underlying process is understood to take real time.

### 9.19 tunci (든지) — indifference/no-preference connective

*Tunci* marks that the speaker has no particular preference among the (often paired, reduplicated A-tunci B-tunci) alternatives named, leaving the choice to the addressee — "whether you boil or roast it, do as you like" (p.558). The author notes the particle is also usable with nouns and postpositions, though only its verbal use is treated in this section; the defining semantic feature is that the named action is not yet realized — it is still being weighed/contemplated at the moment of utterance, not a report of a completed choice (p.558–559).
---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`.
