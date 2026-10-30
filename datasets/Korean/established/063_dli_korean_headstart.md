# Korean — Established Vocabulary/Grammar: DLI *Korean Headstart* (complete: Student Guide + Units 1–9 + Keys-excluded + Glossaries + Numbers Appendix)

**Source:** Defense Language Institute Foreign Language Center, *Korean Headstart* (1st edition, November 1984; images were replaced with Creative Commons/public-domain equivalents in Jan 2011 — this does not affect the text). Full book, printed pp. 1–480 of 490 PDF pages (printed_page = PDF_page − 5, verified empirically at many points spanning the entire book). This is a Defense Language Institute audio/tape-based course for US military personnel, parallel in kind to the Tagalog/Japanese Headstart course+cultural-notes pairs already extracted for those languages; its companion *Cultural Notes* booklet is extracted separately into `established/064`.

**Text layer / OCR:** This PDF has no real embedded/born-digital text layer — it is a 1984 scanned book run through Adobe Acrobat's "Paper Capture" OCR plug-in (confirmed via `pdffonts`: `HiddenHorzOCR` CID fonts throughout). `pdftotext` nonetheless returns usable text, because **this entire course is written in romanized Korean only, by design** — it is a tape-based course with no literacy requirement, and uses no Hangul script anywhere except its own dedicated, optional Unit 9 ("Hangul") lesson. This is the legitimate "romanization-only source" case documented in the project's PDF-gotcha list, not a corruption, and the `+36266` Hangul-cipher offset was correctly never needed for the romanized bulk of the book.

**OCR noise (recurring across the whole book):** the OCR systematically mis-renders the McCune-Reischauer breve-vowel diacritic (ŏ, ŭ) as a stray digit — most often `5` or `6`, occasionally `0`, `~`, `B`, or `I` — e.g. `sory5ng` for *soryŏng*, `tas5t`/`tas~t` for *tasŏt*, `ch'irw51` for *ch'irwŏl*, `6tt6k'e` for *ŏttŏk'e*. This is resolved throughout by cross-checking repeated occurrences of the same lexical item elsewhere on the page or in the unit, and by McCune-Reischauer romanization patterns; affected entries are flagged `plausible_unverified` in the Vision Reading Confidence column rather than silently fixed. A handful of other digit/letter swaps and line-wrap word breaks (e.g. "tu1" for "tul," a word split across a page boundary) were resolved the same way with full confidence. Two items could not be fully resolved and are flagged `low_confidence`: a likely-misread "ashippun" (should almost certainly be *oshippun*, "fifty minutes") and the glossary's "yak" for "railroad station," which is consistent across both glossary directions but does not match this project's established *yok* (역) for "station."

**Marginalia:** checked specifically throughout every chunk of this book — **no handwritten pen/pencil annotation was found anywhere**; all noise is attributable to the print-OCR artifacts described above, not a prior owner's markup.

**Unit 9 (Hangul) method:** this optional unit is the one place in the book with actual Hangul script. `pdftotext` is useless for it — not a decodable font-cipher (the `+36266` offset does not apply), just bad OCR of hand-lettered stroke-order diagrams and syllable-writing-practice boxes. All Hangul forms used below were **vision-read directly from `pdftoppm`-rendered page images at 200dpi** (6 representative pages spanning the unit); scan quality was uniformly clean and every such entry is marked `verified`.

## Coverage note — non-redundant-supplement scope (whole-book summary)

Korean already has 59 established reference files (`established/001`–`059`, plus `067`–`069`) covering beginner-through-academic Korean in depth, including several other true-beginner courses, a dedicated pronunciation/phonology source (`013_sounds_of_korean_pronunciation_guide`), and a deep academic honorifics source (`031_korean_honorifics_and_politeness`). This book sits on well-trodden beginner territory (greetings, numbers, shopping, time, directions, food, transportation, basic Hangul). Per this project's established convention (see `established/042_my_korean_1.md`'s coverage note), **all distinct vocabulary is kept in full throughout, regardless of conceptual overlap with other books** — an independently-authored example set is never redundant on its own. **Grammar explanations** are kept where this book's own framing, mechanism, or worked example adds something not already captured elsewhere; skipped/cross-referenced by name where genuinely identical in substance to existing coverage (most often `established/035_integrated_korean_beginning_1.md`, `established/042_my_korean_1.md`, `established/045_korean_for_dummies.md`, `established/031_korean_honorifics_and_politeness.md`, or `established/001_basic_korean_part1.md`/`established/013_sounds_of_korean_pronunciation_guide.md`). Each subsection below documents its own skip/keep decisions explicitly.

**Flagship distinctive finding — the 1984 US-military-oriented register.** Confirmed by grep against all 59 prior established files before extraction began: none contained *taewi, hasagwan, changgyo, sangbyong, yukkun, haegun,* or *konggun*. This book's genuinely new contribution to the corpus is its extensive Republic of Korea / US Armed Forces rank ladder (E-2 through O-6), service-branch vocabulary, military installations and liaison infrastructure (MPs, police substations calling American MPs, named bases near Osan/Tongduch'ŏn/Uijŏngbu, the 2nd Infantry Division), military-social conventions (rank-linked honorifics, one rank title per grade across all ROK services unlike the US system), and the historical "personal hire" Korean-national-employee-doing-laundry-for-US-personnel institution. This register surfaces throughout nearly every unit, not just where expected, and is flagged `technical.military` wherever it appears.

**Register-contrast finding, recurring throughout.** Nearly every lesson closes with a "Conversation for Listening Comprehension" that re-renders the lesson's main **formal** `-(su)mnida/-(su)mnikka` dialogue into the **informal-polite `-yo`** register, with the book explicitly stating students need only *recognize*, not *produce*, this register. This is a deliberate, book-wide didactic device (not a throwaway drill) and is captured as `colloquial`-tier vocabulary plus dedicated grammar points throughout.

**Skipped wholesale, not extracted:** the Student Guide and Tape Index (pure English course-administration text, zero Korean content); the Rank Insignia Charts (illustrations labeled entirely in English — the actual Korean rank terms are captured from the surrounding lesson prose instead); the Keys to the Exercises (printed pp. 339–430) as pure drill-answer repetition of content already captured from the lesson conversations/exercises; the "List of Images" photo-credit appendix (zero linguistic content); pure substitution/repetition drills that recombine vocabulary already captured earlier in the same section with no new lexical content; and, in Unit 9, the full letter-by-letter Hangul alphabet/stroke-order/syllable-block-mechanics pedagogy, which duplicates `established/013_sounds_of_korean_pronunciation_guide.md` and the letter-inventory passages of `001`, `015`, `016`, `024`, `035`, `042`.

**Glossary redundancy finding:** the book's English-Korean glossary (printed pp. 455–478) was confirmed, by full read-through and spot-check, to be the *same* term/gloss/unit-lesson data as the Korean-English glossary (printed pp. 431–454), just reverse-sorted — it was not bulk re-extracted a second time. The one genuinely new content found only in the English-Korean direction — several dozen verbs/adjectives given in bare dictionary-stem form rather than inflected headword form — is captured in its own small supplementary table.

---

## Vocabulary

### Front Matter & Unit 1 — Greetings and Introductions (printed pp. 1–51)

Covers the Student Guide, Tape Index, Introduction to Korean Grammar, Introduction to Korean Sounds, and Unit 1 (Lessons 1–4 + Self-Evaluation Quiz). The Student Guide and Tape Index (pp. 1–8) are pure English meta-text with no Korean content and are not represented below. The Rank Insignia Charts (printed pp. 22–23) are illustrations labeled entirely in English (mapping US insignia to Korean rank equivalents) with no romanized Korean text of their own — the actual Korean rank terms they illustrate are captured below from the surrounding lesson prose/exercises, where they are actually defined.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| sonsaengnim | polite title "Mr./teacher," used with an adult male's family name | noun (title) | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 1 conversation/notes, p. 15. Follows immediately after the family name. |
| annyong | well-being, peace | noun root | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 1 notes, p. 15; root of the standard greeting. |
| annyonghashimnikka | Hello / Good morning / Good afternoon / Good evening (lit. "Are you at peace?") | phrase (greeting, formal question) | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 1 conversation, p. 14. |
| annyonghaseyo | Hello (informal/polite-casual variant of the above) | phrase (greeting) | colloquial | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | plausible_unverified | Appears in the "Conversation for Listening Comprehension" (Ex. 11, p. 21) — the book's own designated slot for less-formal endings students must recognize but aren't tested on. |
| ne | yes (most common form) | interjection | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 1 notes, p. 15. |
| ye | yes (less common alternative) | interjection | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | low_confidence | Lesson 1 notes, p. 15, mentions an alternative to "ne"; the OCR dropped the actual glyph (rendered as "~"). Reconstructed as "ye" (예) from context — not directly visible in the source text. |
| taewi | captain (military rank, ROK O-3) | noun (military rank) | technical.military | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | First a phonology-chart example word (p. 10), then defined as a rank in Lesson 1 notes, p. 15. Corresponds to American O-3; one title used for this grade across all ROK services. |
| -nim | honorific/polite suffix added after a name, title, or rank | suffix | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 1 notes, p. 15; added especially to show respect toward someone senior in rank or position. |
| oraeganmanimnida | It's been a long time | phrase | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 1 conversation, p. 14. Orae = "for a long time," -mnida = statement ending. |
| ottok'e | how | adverb (interrogative) | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 1 conversation, p. 14. |
| chinaeshimnikka / chinaemnida | to get along (honorific question form / plain statement form) | verb | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 1 conversation/notes, pp. 14–15. -shi- honorific infix present only when asking about someone else, absent when stating a fact about oneself (modesty rule). |
| chal | well, fine, satisfactorily | adverb | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 1 conversation, p. 14. |
| pappushimnikka / pappumnida | to be busy (honorific question form / plain statement form) | verb | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 1 conversation/notes, pp. 14–16. Same -shi- honorific-for-others-only pattern as chinae-. |
| pyollo | not really, not particularly (used only in negative sentences) | adverb | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 1 notes, p. 16. |
| yosae | these days, recently, lately, nowadays | adverb | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | First a phonology-chart example word (p. 10), then reused throughout Lesson 1. |
| chunwi | warrant officer (ROK WO1–CW4) | noun (military rank) | technical.military | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 1 Ex. 4, p. 17. |
| sowi | second lieutenant (ROK O-1) | noun (military rank) | technical.military | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 1 Ex. 4, p. 18. |
| chungwi | first lieutenant (ROK O-2) | noun (military rank) | technical.military | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 1 Ex. 4, p. 18. |
| soryong | major (ROK O-4) | noun (military rank) | technical.military | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 1 Ex. 4, p. 18; reused as phonology-chart example on p. 11 (there "sory5ng" due to breve-OCR noise). |
| chungryong | lieutenant colonel (ROK O-5) | noun (military rank) | technical.military | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 1 Ex. 4, p. 18. |
| taeryong | colonel (ROK O-6) | noun (military rank) | technical.military | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 1 Ex. 4, p. 18. |
| sangbyong | specialist fourth class (ROK E-4) | noun (military rank) | technical.military | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 2 conversation/notes, p. 24; also Lesson 2 Ex. 4, p. 27. |
| kujo | just, merely | adverb | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 2 conversation, p. 24 (printed "Kuj6" with breve-OCR noise). |
| kurossumnida | "That's so" (customary modest reply to a casual well-being question) | phrase | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | plausible_unverified | Lesson 2 notes, p. 24. Explicit cultural-modesty convention, see Grammar Points. |
| che | my | pronoun (possessive) | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 2 conversation, p. 24. |
| ch'ingu | friend | noun | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 2 conversation, p. 24. |
| sogae hamnida | to introduce / "I am making an introduction" | phrase (verb) | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 2 conversation/notes, p. 24. |
| ibuni / ibun | this person (usable for either sex; -i is an optional subject marker) | pronoun (demonstrative) | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 2 conversation/notes, p. 24. |
| ch'am pwepsumnida | Pleased to meet you / How do you do? (lit. "[I] am seeing you for the first time") | phrase | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 2 conversation/notes, p. 24. |
| -imnida | copula ending: "am/are/is" (no person or number marking) | suffix (copula) | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 2 notes, p. 24. |
| pyongjang | specialist fifth class / sergeant-equivalent (ROK E-5, any service) | noun (military rank) | technical.military | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 2 conversation/notes, p. 24. |
| sonsaeng | "Mr." (less polite than sonsaengnim; for a familiar adult male equal in age/status) | noun (title) | colloquial | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 2 Ex. 4, p. 27. Book advises using sonsaengnim unless told otherwise. |
| misut'o | "Mr." (loanword from English "Mister," for someone younger/lower-status) | noun (title) | colloquial | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | plausible_unverified | Lesson 2 Ex. 4, p. 27. |
| misu | "Miss" (loanword from English) | noun (title) | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 2 Ex. 4, p. 27. Notes explain Korean women keep their maiden names — no equivalent of "Mrs." in this course's vocabulary. |
| ibyong | private (ROK E-2) | noun (military rank) | technical.military | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 2 Ex. 4, p. 27. |
| ilbyong | private first class (ROK E-3) | noun (military rank) | technical.military | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 2 Ex. 4, p. 27. |
| yukkun | army, ground forces; also "soldier" | noun | technical.military | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 3 conversation/notes, p. 32. Notes specify strictly ground forces, not the military in general. |
| shillejiman | Excuse me, but... | phrase | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 3 conversation/notes, p. 32. |
| kyolhon (hashyossumnikka) | marriage / "Have you gotten married?" | noun / phrase | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 3 conversation/notes, p. 32. |
| ajik | yet, still | adverb | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 3 conversation/notes, p. 32. |
| mihon(imnida) | unmarried, single ("I am not married") | noun + copula | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 3 conversation/notes, p. 32. |
| a | Oh! (casual exclamation) | interjection | colloquial | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 3 conversation/notes, p. 32. |
| kurossumnikka | Is that so? / Really? | phrase | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 3 conversation/notes, p. 32. |
| kunin | military person/serviceman (any branch) | noun | technical.military | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 3 conversation/notes, p. 32. |
| aniyo | no | interjection | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 3 conversation/notes, p. 32. |
| cho(nun) | "I" (polite) + subject/topic marker -nun | pronoun + particle | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | plausible_unverified | Lesson 3 conversation/notes, p. 32. Notes state "I" can usually be dropped entirely. |
| minganin | civilian | noun | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 3 conversation/notes, p. 32; contrastive counterpart to kunin. |
| algessumnida | I see / I understand | phrase | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 3 conversation/notes, p. 32. |
| kurom | well / well then (discourse connector) | adverb/conjunction | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 3 conversation/notes, p. 32. |
| mullon(imnida) | of course / needless to say | adverb + copula | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 3 conversation/notes, p. 33. |
| haegun | Navy | noun | technical.military | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 3 Ex. 4, p. 35. |
| konggun | Air Force | noun | technical.military | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 3 Ex. 4, p. 35. |
| haebyongdae / haebyong | Marine Corps | noun | technical.military | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 3 Ex. 4, p. 35. Full form haebyongdae, shortened to haebyong in compounds/questions. |
| hasagwan | NCO (or petty officer, in Navy usage) — generic rank-category term | noun | technical.military | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 3 Ex. 4, p. 35. |
| changgyo | officer — generic rank-category term | noun | technical.military | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 3 Ex. 4, p. 35. |
| haegun changgyo / haegun hasagwan / konggun hasagwan / haebyong changgyo / yukkun hasagwan | Navy officer / Navy petty officer / Air Force NCO / Marine Corps officer / Army NCO | noun phrase (compound) | technical.military | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 3 Ex. 4, p. 35; branch + rank-category compound pattern. |
| hasa | staff sergeant (ROK E-6) | noun (military rank) | technical.military | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 3 Ex. 8, p. 36. |
| chungsa | sergeant first class (ROK E-7) | noun (military rank) | technical.military | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 3 Ex. 8, p. 36. |
| sangsa | master sergeant (ROK E-8) | noun (military rank) | technical.military | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 3 Ex. 8, p. 36. |
| chuimsangsa | sergeant major / "first sergeant" (ROK E-9 duty title, not a standalone rank) | noun (military duty title) | technical.military | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 3 Ex. 8, p. 36. Normally used without a name attached, parallel to English "Sergeant Major"/"First Sergeant." |
| kagessumnida | I will go | phrase (verb) | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 4 conversation/notes, p. 42. ka- + -gess- + -umnida. |
| waeyo | Why? (so soon) | phrase (interrogative) | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 4 conversation/notes, p. 42. |
| chom | a little | adverb | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 4 conversation/notes, p. 42. |
| annyonghi | in peace | adverb | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 4 conversation/notes, p. 42; root of the paired farewell expressions. |
| kashipshio / kyeshipshio | Please go (in peace) [to person leaving] / Please stay (in peace) [to person remaining] | phrase | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 4 conversation/notes, p. 42; asymmetric farewell pair, see Grammar Points. |
| tto | again, once more, in addition | adverb | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 4 conversation/notes, p. 42. |
| pwepkessumnida | [I] will see [you] again | phrase | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 4 conversation/notes, p. 42. |
| naeil / ittaga / taum chue / taum tare | tomorrow / later / next week / next month | adverb(s) | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Lesson 4 Ex. 4, p. 44. |
| se / iri / oshipshio / kudu | three / this way / Please come / shoe(s) | numeral/adverb/phrase/noun | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Introduction to Korean Sounds, p. 10 (e/i/o/u vowel-chart examples; oshipshio reused as "sh" consonant example p. 11, kudu reused as "k" consonant example p. 10). |
| odi (ŏdi) | where | adverb (interrogative) | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | plausible_unverified | Introduction to Korean Sounds, p. 10 (ŏ vowel example; also "d" consonant example, p. 11). Breve diacritic lost/garbled by OCR both times. |
| kurigo (kŭrigo) | and | conjunction | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | plausible_unverified | Introduction to Korean Sounds, p. 10 (ŭ vowel example). |
| wae / yogi / chok'a / -kkaji / obun / paek / p'al | why / here / nephew / up to / five minutes / hundred / eight | various | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | plausible_unverified | Introduction to Korean Sounds, pp. 10–11 (consonant-chart example words; p'al given twice, first instance OCR'd "pial"). |
| pappumnida (pappŭmnida) / t'ashipshio / ttara / onje / chumal / ch'a / tchamnida / saram / ssamnida / hana / man / nugu | I'm busy / Please board / following / when / weekend / tea / It's salty / person / It's cheap / one / ten thousand / who | various | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Introduction to Korean Sounds, p. 11 (remaining consonant-chart example words, each illustrating one consonant's romanization). |

**Vocabulary count, this section: 101 distinct entries** (several compound/multi-example rows above consolidate adjacent single-use chart-example words from the source table for space; all underlying forms are preserved in the Notes).

### Unit 2 — Numbers and Money & Unit 3 — Shopping (printed pp. 52–121)

OCR gotcha specific to this range: both native-Korean and Sino-Korean numeral lists suffered frequent digit/letter swaps (e.g. "tu1" for "tul"); all resolved via cross-occurrence checking, flagged `plausible_unverified` below. Pure rote repetition/substitution drills recombining numbers already captured (e.g. drilling 21–99 or 1,000–9,999 by substitution) were skipped — only representative base forms and sound-change junctures are captured. Military-register vocabulary (ranks, status categories) surfaces throughout both units' counter/honorific drills, and Unit 2 Lesson 3's flagship conversation is a currency-exchange transaction explicitly framed for a US service member.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| hana / tul / set / net / tasŏt / yosŏt / ilgop / yodŏl / ahop / yŏl | one through ten | numeral (native) | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | plausible_unverified | Unit 2 Lesson 1, native numbers 1–10; several OCR'd with digit/breve noise ("tu1," "tasot/tas5t," "yosot/yos~t," "i1gop," "yodel/yodo1," "yo1"). |
| yŏrhana | eleven (11) | numeral (native) | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | plausible_unverified | OCR "YOlhana"; representative of the ten+digit 11–19 pattern, 12–19 not separately tabulated (fully compositional). |
| il / i / sam / sa / o / yuk / ch'il / p'al / ku / ship | one through ten | numeral (Sino-Korean) | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | plausible_unverified | Unit 2 Lesson 2; several OCR'd ("0" for o, "ch'i1," "p'a1/pial"); ship is this book's own romanization (cf. "sip" elsewhere). |
| shibil | eleven (11) | numeral (Sino-Korean) | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | plausible_unverified | OCR "shibi1"; representative of ship+digit 11–19 formation. |
| iship | twenty (20) | numeral (Sino-Korean) | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | representative of digit+ship tens formation (30–90 fully compositional, not tabulated). |
| paek / ch'ŏn / man / paengman | hundred / thousand / ten thousand / one million | numeral (Sino-Korean) | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | plausible_unverified | man is Korean's base counting unit for 5–8 digit numbers, vs. English's 1,000 — book makes this contrast explicit; paeng- shows nasal assimilation before man. |
| -gae / -saram / -bun / -jan / -byŏng / -gap / -ssik | counters: objects / people (equal-lower status) / people (higher status) / cups-glasses / bottles / packs / each-per | counter/classifier | core (except -saram, -bun: technical.military) | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | plausible_unverified | -saram drilled with yukkun (soldiers), -bun drilled with changgyo (officers); han-/tu-/se-/ne- truncate before -gae. |
| kapshi / ŏlmamnikka | price / how much is it-are they | noun/phrase | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | plausible_unverified | Unit 2 Lesson 2. |
| won / bul / chŏn / hwannyul | won / dollar / cent / exchange rate | noun | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | plausible_unverified | flagship military-currency-exchange conversation, Unit 2 Lesson 3; bul pronounced "bur-" before -e, one OCR instance misread "aul." |
| hanguk / hangukton / miguk / migukton / ton | Korea / Korean money / the United States / American money / money | noun | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | migukton central to the US-military currency-exchange framing. |
| modu | all, altogether | adverb | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | — |
| issŭmnida / issŭmnikka / opsŭmnida | there is/are-I have / is there?-do you have? / there isn't-I don't have | verb (existential) | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | opsŭmnida is an irregular negative, NOT "an issŭmnida" — see Grammar Points. |
| kyeshimnida / kyeshimnikka | there is/are (honorific) / is there-are there (honorific) | verb (existential, honorific) | technical.military | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | used specifically for people of higher rank/status; drilled with officer ranks. |
| chushipshio / ch'ajushimnikka / ch'atsŭmnida | please give me / are you looking for (it)? / I am looking for (it) | verb form | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | ch'aju- → ch'at- stem change; -shi- dropped for 1st person. |
| hapshida / ssage / kollanhamnida / ottossŭmnikka / popshida | let's make it / cheaply / that's difficult (polite refusal) / how about it? / let me see | verb/adverb/phrase | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | the core bargaining vocabulary set, Unit 3 Lessons 2–3; ssage used only with verbs per source note. |
| chom / hago / kŭrigo / mani | a little (politeness softener) / and (nouns only) / and-besides (sentence-initial only) / a lot-many (verbs only) | particle/conjunction/adverb | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | book draws explicit hago-vs-kŭrigo contrast; mani restricted to verbal use per source note. |
| yogi / chogi / igo | here / over there / this (thing) | pronoun/deictic | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | igo = i- "this" + -go "thing"; general item noun precedes igo in Korean word order. |
| kamsahamnida / komapsŭmnida | thank you (more common) / thank you (less common alternative) | phrase | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | book explicitly flags the frequency difference. |
| tto oshipshio / oso oshipshio | please come again / come right in | phrase | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | shopkeeper farewell/greeting pair. |
| sagwa / pae / milgam / shigye / tambae / sol / k'op'i / saida / k'olla / posu | apple / pear / tangerine / watch-clock / cigarette(s) / "Pine" cigarette brand / coffee / lemon-lime soda / cola / bus | noun | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | plausible_unverified | sol is a real cultural/brand detail; posu OCR'd "posti/posIT." |
| ch'imdae / sop'a / t'eibul / tamnyo / ibul | bed / sofa / table / blanket / quilt | noun | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | t'eibul is an English loanword. |
| maekchu / saeng maekchu | beer / draft beer | noun | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | saeng- "raw/fresh." |
| posŏk / panji / mokkŏri / kŭm / paekkŭm | jewelry / ring / necklace / gold / platinum (white gold) | noun | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | panji pronounced "banji" after a preceding -m. |
| ch'ongbaji / baji / saiju | blue jeans / pants (general) / size | noun | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | saiju is an English loanword; book notes pants sizes given in inches. |
| saek / ppalgansaek / ch'oroksaek / hinsaek / kkamansaek / p'aransaek / noransaek / orenjisaek / peijisaek / noksaek | color / red / green / white / black / blue (also "green" for nature) / yellow / orange / beige / green (alternate) | adjective/noun (color) | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | full color set; p'aransaek's nature-green double duty flagged in Grammar Points; noksaek given as an alternate to ch'oroksaek. |
| k'ŭmnida / chaksŭmnida / pissada / chal match'ŭmnida | it's big / it's small / to be expensive / it fits well | adjective/verb (descriptive) | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | chal match'ŭmnida restricted to clothing fit. |
| kŭlsseyo / iboboshipshio | well...-I'm not so sure / try it on (please) | interjection/verb | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | iboboshipshio restricted to clothing per source note — see Grammar Points. |
| changgyo / hasagwan / yukkun | officer / NCO / soldier-army | noun | technical.military | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | drilled with -bun/-saram counters respectively. |
| taeryŏngnim / chungwinim / taewinim | Colonel / First Lieutenant / Captain (honorific address forms) | noun | technical.military | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | plausible_unverified | -nim honorific attaches to rank+name. |
| ilbyŏng | Private First Class | noun | technical.military | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | plausible_unverified | OCR "ilbyang." |

**Vocabulary count, this section: ~95 entries** (several rows above consolidate short related sets from the source for space; all individual forms are named).

### Unit 4 — Time and Dates & Unit 5 — Everyday Conversation (printed pp. 122–191)

OCR gotcha specific to this range: the breve-digit substitution (ŏ → 5/6/B/I) is pervasive in this range's time/date numerals; resolved throughout via cross-checking. One likely genuine OCR misread is flagged `low_confidence` rather than silently corrected: "ashippun" almost certainly should be *oshippun* ("fifty minutes"), since no Sino-Korean numeral prefix matches "a-." The "Conversation for Listening Comprehension" sections (printed pp. 166, 178–179) are kept as a distinct register finding, not skipped as drills. This unit pair surfaces the book's flagship US-military register extensively: honorific rank-address terms, the contrastive pair *migukkunin* "American service member" vs. *minganin* "civilian," general uniform vocabulary, and an entire lesson (Unit 5 Lesson 3) built around the historical "personal hire" Korean-employee-doing-laundry-for-US-personnel institution.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| hanshi / tushi / seshi / neshi / tasotshi / yosotshi / ilgopshi / yodolshi / ahopshi / yolshi / yolhanshi / yoltushi | one through twelve o'clock | noun (time) | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.124–125; native numbers 1–4 truncate before -shi, 5+ do not. |
| chigum / myotshi / -shi / -ban / shigan / myotshigan / kollimnida | now / what time / hour-counter suffix / half-past suffix / hour (duration) / how many hours / it takes (time) | various | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.125–128; -shi (point-in-time) vs. shigan (duration) drawn as a minimal pair. |
| -pun/-bun / obun / shippun / ashippun [likely oshippun, low-confidence] | minute-counter suffix / five minutes / ten minutes / fifty minutes [tentative] | bound suffix/noun | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | low_confidence | p.129; full paradigm in Grammar Point 6. |
| -jon / obunjon / ojon / ohu | "before" suffix / five minutes before / morning-a.m. / afternoon-p.m. | bound suffix/noun | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.132–135. |
| -e (temporal) / oshipshio / kashipshio / kagessumnida | "in/at" particle / please come / please go / I will go | particle/verb forms | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.135; -e is the same particle used for destinations, per the book's own note. |
| yoil / iryoil / woryoil / hwayoil / suyoil / mogyoil / kumyoil (alt. kumnyoil) / t'oyoil / musun yoil / onul | day of the week / Sunday–Saturday / what day of the week / today | noun/phrase | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.135–136; yoil pronounced yoir- before a vowel; kumnyoil flagged by the book as a free variant. |
| -wol / irwol / iwol / samwol / sawol / owol / yuwol (var. yugwol) / ch'irwol / p'arwol / kuwol / shiwol / shibirwol / shibiwol | month suffix / January–December | bound suffix/noun | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.138; yuwol/yugwol flagged by the book as live intergenerational variation (younger speakers may not drop k); p'arwol/shiwol show p/p-drop assimilation. |
| onje / oshyossumnikka / wassumnida | when / did you come (honorific) / I came (also used for spouse) | adverb/verb | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.139, 154. |
| myoch'il / -il (ordinal) / iril / kuil / samshibiril | what date / day-of-month ordinal suffix / the first / the ninth / the thirty-first | interrogative/noun | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.140–143; full 1st–31st paradigm given in Grammar Point 11. |
| -nyon / ch'ongubaek p'alshipsanyon / p'alshipsamnyon | year-counter suffix / 1984 / '83 (two-digit abbreviation) | bound suffix/noun | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | plausible_unverified | p.144–145; full-year numbers never split into two chunks as in English; two-digit abbreviation valid only within the current century. |
| changnyon / kumnyon / naenyon | last year / this year / next year | noun (time) | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.146. |
| hanguge / miguge | to/in Korea / to/in the United States | noun + locative | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.146; -k pronounced -g before -e. |
| saengil / che saengil / -jone / onyonjone | birthday / my birthday / "...ago" suffix / five years ago | noun/suffix | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.146–147; che "my" may be dropped. |
| taewinim / soryongnim | Captain / Major (honorific address forms) | noun (title) | technical.military | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.154, 161, 163; address CPT Harris and MAJ Pak throughout Unit 5. |
| odi / -eso / -so / kohyang / kurossumnikka | where / from (ablative) / hometown / is that so? | various | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.154–155. |
| kyolhon hashyossumnikka / mullon / kach'i | are you married? / of course / together | phrase/adverb | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | plausible_unverified | p.154; kyolhon OCR'd "ky5lhon," normalized. |
| aidul / adul / ttal / -hago / uri | children / son / daughter / "and" (noun connective) / we-our-also "my" | noun/particle/pronoun | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.154–159; book explicitly notes Koreans often say uri where English says "my." |
| pumonim / chip / chibe | parents (honorific) / house-home / to-at home | noun | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.159; chip pronounced chib- before -e. |
| chipsaram / namp'yon / samonim | (one's own) wife, humble / (one's own) husband / (someone else's) wife, honorific | noun | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.160; samonim used alone or with husband's name + sonsaengnim, never with the woman's own surname — Korean women keep their maiden name. |
| kunin / miguksaram / migukkunin / minganin | military service member / American (person) / American service member / civilian | noun | technical.military (migukkunin, minganin, kunin) / core (miguksaram) | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.160; migukkunin explicitly contrasted with minganin. |
| pappumnida/pappushimnikka / chinaemnida/chinaeshimnikka / ch'atsumnida/ch'ajushimnikka | plain/honorific verb pairs: busy / getting along / looking for | verb | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.161, 185. |
| chonun / an / hangae / chushipshio / tambae / pogi | as for me / negation particle / one (object counter) / please give / cigarettes / looking-appearance | various | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.161–164; word-order illustration set. |
| oshyossoyo / wassoyo / kuroseyo / mullonyo | did you come? / I came / is that so? / of course (all informal-polite -yo register, recognition only) | verb/interjection | colloquial | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.166, 178; Listening Comprehension register-contrast set, see Grammar Point 18. |
| chonyok / chonyoge / mwo / halil / pyollo / waeyo | evening-dinner / in the evening / what / things to do / particularly (negation only) / why? | various | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.168. |
| -pshida / hapshida / chossumnida / mannapshida | "let's" suffix / let's do-have / that's good / let's meet | suffix/verb | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.168–169; chossumnida contrasted with choahamnida, see Grammar Point 19. |
| myotshieyo / arassumnida / algessumnida | at what time? / I understand / I will understand (interchangeable) | phrase/verb | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.169; -yo obligatory even on a bare isolated phrase in polite speech. |
| umshik / musun umshik / choahamnida/choahashimnikka / choahaseyo/choahaeyo | (cooked) food / what kind of food / like it (plain/honorific) / like it (informal-polite -yo) | noun/verb | core (colloquial for -yo forms) | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.168–178. |
| pulgogi / kalbi / aju / kimch'i / mashi issumnida / umshikchom | barbecued beef / barbecued ribs / very / kimchi / it's delicious / restaurant | noun/phrase | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.168. |
| kapshida / kuropshida | let's go / let's do that (agreement) | verb | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.168–169. |
| chumare / ibon chumare / taum chumare / kukchang / kugyong / kukchang kugyong | weekend / this weekend / next weekend / theater / watching-sightseeing / watching a movie | noun | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.172. |
| shinae / kashimnikka / kamnida / taum t'oyoire | downtown / are you going? / I am going / next Saturday | noun/verb/phrase | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.174–176; che/uri dropped when talking about going/coming home. |
| misut'o / iri / oseyo | Mister (title for employee) / this way-toward me / please [do] | noun/adverb/verb | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.180; "Mr. Cho," the Korean personal-hire employee. |
| kunbok / kunhwa / kyegupchang / horitti | military uniform / military boots / insignia of rank / belt | noun | technical.military | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.180–184; uniform-accessory vocabulary. |
| ppalli / set'ak/set'akhada / tarida / suson/susonhada / iltchigi | quickly / laundry-to do laundry / to iron / mending-to mend / early (verbal contexts only) | various | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.180–185. |
| kunmu / haeya twemnida / kuronikka / chogo | performing duty-work / have to do / so-therefore / that thing | noun/construction/connective/pronoun | technical.military (kunmu) / core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.180. |
| sugo / sugo haessumnida | hard work / "you have worked hard" (thanks-for-effort formula) | noun/fixed expression | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.180. |
| paji / -ji maseyo / nutke | pants / "don't..." negative imperative / late | noun/suffix/adverb | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.180–185; full -ji maseyo paradigm in Grammar Point 20. |
| pissamnida / nomu / kkamansaek / k'umnida / kudu / hinsaek / ch'oroksaek | expensive / too (excessively) / black / big (of size) / shoes / white / green | various | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.184. |
| omnida / samnida / hamnida / kunmu an hamnida | I'm coming / I'm buying / I'm doing it / I'm not working | verb form | core (technical.military for the last) | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.183; illustrates negation placement with a ha- compound verb. |

**Vocabulary count, this section: ~150 entries** (rows above group tightly-related short sets from the source for space; all individual forms are named).

### Unit 6 — Directions & Unit 7 — Restaurants and Food (printed pp. 193–255)

Cross-checked via both plain and `-layout` `pdftotext` passes; term/gloss pairing confirmed correct throughout, including the Lesson 3 Exercise 5 place-setting/condiment table. One word was split across a page break by the OCR column flow ("Kamsahamnida," resolved with full confidence). Unit 6 Lesson 3 surfaces genuine 1984 US-military-in-Korea infrastructure content (American MPs, police substations with an explicit MP-liaison role, named installations); Unit 7 continues the military-social dining context (MAJ Pak, O.B. beer) without new military-specific vocabulary beyond what's captured here.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| yoboseyo / shillehamnida / mianhamnida / ch'onch'onhi / malssumhae chushipshio / kamsahamnida | "Hey!"-telephone greeting / excuse me / I'm sorry / slowly / please say-tell / thank you | interjection/expression | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Unit 6 L1; kamsahamnida OCR-split across a page break, resolved with full confidence. |
| hwajangshil / odi issumnikka / oruntchok/oruntchoge / wentchok/wentchoge | rest room / where is it? / right side-on the right / left side-on the left | noun/phrase | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | plausible_unverified | Unit 6 L1 Ex. 4; final -k devoices/lenites before a following vowel. |
| wich'ung / araech'ung / tabang / shiktang / pilding / hot'el/hot'ere | upstairs / downstairs / coffee shop / restaurant-dining room-mess hall / building / hotel | noun | core (technical.military for shiktang's mess-hall sense) | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Unit 6 L1 Ex. 4; shiktang distinguished from umshikchom ("restaurant" only). |
| Naija hot'el | the Naija Hotel (named R&R facility, Seoul) | proper noun | technical.military | — | contemporary (source published 1984) | South Korea (Seoul) | national | grammar_reference | n/a | n/a | Unit 6 L1 Ex. 4; explicitly glossed as an R&R facility. |
| pang / ch'otchae / tultchae / setchae / tashi / hanbon | room / first / second / third / again (retry) / once | noun/ordinal/adverb | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Unit 6 L1 Ex. 7; tashi explicitly contrasted with tto ("again" in general). |
| posu t'ominal / ottok'e kamnikka / negori / ttokparo / kuromyon | bus terminal / how do I get to...? / intersection / straight ahead / if you do that, then | noun/phrase/conjunction | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Unit 6 L2; posu t'ominal explicitly flagged by the book as an English loanword. |
| shigan olmana kollimnikka / myotshigan / han (+number) | how much time does it take? / how many hours / "about/approximately" prefix | phrase | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Unit 6 L2; shigan olmana vs. myotshigan drawn as a count/mass quantifier contrast. |
| yok / paekhwajom / shijang / shinhodung / yop'/yap'e / yukkyo / chihado | railroad station / department store / market / traffic light / side-next to / pedestrian overpass / underpass | noun | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Unit 6 L2 Ex. 8. |
| Tongdaemun shijang | Tongdaemun Market (named market, Seoul) | proper noun | core | — | contemporary (source published 1984) | South Korea (Seoul) | national | grammar_reference | n/a | n/a | Unit 6 L2 Ex. 8. |
| chom towa chushipshio / il/irimnikka / kil irossumnida / ibugune | please help me / matter-thing / I'm lost / in this area | phrase/noun | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Unit 6 L3; book notes Americans phrase this as a question, Korean is a direct request. |
| migun emp'i | American MP(s) | noun phrase | technical.military | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Unit 6 L3; military-specific loanword-derived term. |
| nugu / yongo / mot hamnida / chol / ttara (oshipshio) | who / English (language) / cannot / me (object form) / following (please follow) | various | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Unit 6 L3. |
| p'ach'ulso | police substation | noun | technical.military | — | contemporary (source published 1984) | South Korea | national | grammar_reference | n/a | n/a | Unit 6 L3; book explains its duty officer calls an American MP in an emergency — see Grammar Point 7. |
| migunbudae / budae / chigap / chonhwa / pul nassumnida | American military installation / military post (general) / wallet / telephone / "a fire broke out!" | noun/phrase | technical.military (first two) / core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Unit 6 L3 Ex. 4. |
| hagessumnikka (food/drink) / chonun / k'op'i / sagwa jyusu / insamch'a / k'urim / p'iryo (opsumnida) / ch'a | would you like to have? / I-as for me / coffee / apple juice / ginseng tea / cream / need (don't need any) / tea (generic) | various | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Unit 7 L1. |
| -ro (yongoro) / haeboshipshio | "by means of" → "in English" / try it | particle/verb | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Unit 7 L1; haeboshipshio cross-referenced by the book to the earlier iboboshipshio pattern. |
| maekchu / saida / solt'ang / orenji jyusu / hongch'a / songnyang / chaettori / hangungmal/hangungmallo | beer / lemon-lime soda / sugar / orange juice / black tea / matches / ashtray / Korean (language)-in Korean | noun/phrase | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Unit 7 L1 Ex. 1/4. |
| pulgogi / maep-(maepsumnikka) / maewoyo / sogogi / chodo / agassi / pulgogi paekpan / -inbun (saminbun) | pulgogi / spicy (of food) / "is it spicy?" (informal) / beef / I too / miss (address term) / full pulgogi course dinner / counter for food orders | various | core (colloquial for maewoyo) | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Unit 7 L2; maewoyo explicitly book-flagged as "a less formal way to say" maepsumnikka. |
| O.B. maekchu | OB brand beer | proper noun | core | — | contemporary (source published 1984) | South Korea | national | grammar_reference | n/a | n/a | Unit 7 L2; real historical Korean beer brand. |
| kimch'i / kogi / twaejigogi / takkogi / mandukuk / pibimpap / komt'ang / kalbitchim / kyesanso | kimchi / meat / pork / chicken / wonton soup / bibimbap / beef-bone soup with rice / beef rib stew / check-bill | noun | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Unit 7 L2 Ex. 1/4; kogi pronounced -gogi after a vowel. |
| myotpunimnikka / mok-/mokkessumnida / pap / sul / soju / to (chushipshio) / kanjang | how many people? (of others) / to eat-will eat / cooked rice-meal / alcoholic beverage (generic) / soju / more (please give more) / soy sauce | various | core | — | contemporary (source published 1984) | South Korea (soju) | national (soju) | grammar_reference | n/a | n/a | Unit 7 L3; -pun used asking about others, saram when speaking of one's own group. |
| sogum / huch'u / mul / namul / p'odoju / makkolli / p'ok'u / naip'u / naepk'in | salt / black pepper / water / seasoned vegetable side dishes / grape wine / rice wine / fork / knife / napkin | noun | core | — | contemporary (source published 1984) | South Korea (makkolli) | national (makkolli) | grammar_reference | n/a | n/a | Unit 7 L3 Ex. 5; gloss pairing cross-checked via `-layout`. |
| ibun/i-(+noun)/igo — chobun/cho-(+noun)/chogo — yogi/chogi | this (person/noun/thing) — that over there (person/noun/thing) — here/there | pronoun/prefix | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Unit 6 L2 p. 207; four-way person/thing/place demonstrative paradigm, i-/cho- are bound prefixes, never standalone — see Grammar Point 3. |

**Vocabulary count, this section: ~86 entries including the demonstrative paradigm** (rows above group tightly related short sets from the source for space; all individual forms are named).

### Unit 8 — Transportation & Unit 9 — Hangul, Optional (printed pp. 256–338)

Unit 8 is OCR'd romanization throughout, legible apart from scattered breve-digit noise. Unit 9 is the book's own Hangul lesson; all Hangul forms below were vision-read directly from rendered page images (6 representative pages) and are marked `verified`. The full letter-by-letter alphabet/stroke-order pedagogy was skipped as redundant with `established/013`; kept are all vocabulary items introduced via reading/writing-practice exercises (several turning out military/institutional) plus four spelling-pedagogy points not found in `013` (see Grammar Points).

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| t'aekshi / pudae / chongmun / naeri- / paro ap'eso / yogum / olmamnikka / sugo haessumnida / annyonghi kashipshio | taxi / military post / main gate / to get off / right in front of / fare / how much? / thanks-for-effort set phrase / goodbye (to leaver) | various | technical.military (pudae, chongmun) / core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | Unit 8 L1, p.258–259. |
| -kkaji / -eso/-so | up to-as far as-by (dual place/time sense) / at-from | particle | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.262–263; dual sense explicitly flagged by the book — see Grammar Point 1. |
| migunbudae / Songt'an / Osan / kiji / isadan / Uijongbu | American military post / town outside Osan AFB's gate / Osan city/AFB / base / 2nd Division / city between Seoul and Tongduch'ŏn, Camp Red Cloud | noun/proper noun | technical.military | — | contemporary (source published 1984) | South Korea | regional | grammar_reference | n/a | n/a | p.262–263; migun+pudae shows p→b lenition, see Grammar Point 3. |
| posu / posup'yo / maep'yogu / pusanhaeng / tujang / kuronde / ch'ulbal(hamnida) / toch'ak(hamnida) / onu | bus / bus ticket / ticket window / bound for Pusan / two tickets / by the way / departure-it departs / arrival-it arrives / which | various | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.270; -haeng "bound for" in Grammar Point 4. |
| kosokposu / kich'a / yolch'a / t'ukkup / Saemaulho / t'ukshil / pot'ongshil | express bus / train (informal) / train (formal) / express / the Saemaul "Blue Train" / first class / coach class | noun | core | — | contemporary (source published 1984) | South Korea | national | grammar_reference | n/a | n/a | p.274; kich'a/yolch'a book-flagged as an informal/formal register pair; Saemaulho flagged as most popular among US personnel. |
| -pan / t'a- / aigu | "number" counter (Numbers-appendix spelling, possibly OCR for -pon, see Grammar Points) / to board / exclamation | counter/verb/interjection | core (colloquial for aigu) | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.281. |
| ch'ongja / posokham / chagae / notkurut / notchopshi / changgi settu / inhyong / kabang / shilk'u brausu | celadon porcelain / jewelry box / mother-of-pearl / brass bowl / brass plate / chess set / doll-figurine / bag-luggage / silk blouse | noun | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.280–285; souvenir-shopping vocabulary. |
| t'aya twemnida / naeryoya twemnida | have to take/board / have to get off | modal construction | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.286; -(a/o)ya twemnida necessitative, Grammar Point 8. |
| Myongdong / migukpun/migukbun / yumyong(hamnida) | shopping/entertainment district, Seoul / American person (polite) / famous | proper noun/noun/adjective | core | — | contemporary (source published 1984) | South Korea (Seoul) | national | grammar_reference | n/a | n/a | p.291. |
| pumonim / puin/samonim / uri chipsaram / uri namp'yon / uri aidul / adulhago ttal | parents (honorific) / someone else's wife (out-group) / my wife (in-group) / my husband / my children / son and daughter | noun | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.296; in-group/out-group kinship-honorific asymmetry, Grammar Point 7. |
| tamnyo / ibul / panji / mokkori / kum / paekkum / chigap | blanket / quilt / ring / necklace / gold / platinum / wallet | noun | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.297, review-exercise vocabulary. |
| pibimpap / pulgogi / maekchu / umshikchom / hangungmallo / shillejiman | bibimbap / bulgogi / beer / restaurant / "in Korean" / excuse me, but... | noun/phrase | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.280–290, review vocabulary. |
| changnyon/kumnyon/naenyon / inyonjone/samnyonjone / ibon chumare / taum chue/taum tare / naeil ojone/onul ohue | last-this-next year / two-three years ago / this weekend / next week-month / tomorrow morning-this afternoon | time noun/phrase | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | n/a | p.293–295, review vocabulary. |
| 사과 (sagwa) / 버스 (posu) / 아주 (aju) / 모두 (modu) | apple / bus / very / all | noun/adverb | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | verified | Unit 9 L1 reading/writing practice, vision-read p.317. |
| 곳 (kot, "place") / 곧 (kot, "soon") / 곶 (kot, "cape") / 문 (mun) / 맛 (mat) / 빚 (pit) / 집 (chip) / 종이 (chongi) / 불 (pul) / 감자 (kamja) / 벽 (pyok) / 양복 (yangbok) / 강 (kang) / 언제 (onje) | place / soon / cape (promontory) / door / taste / debt / house / paper / fire / potato / wall / man's Western suit / river / when | various | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | verified | vision-read p.322; the kot/kot/kot same-sound-three-spellings set is a spelling-pedagogy worked example, Grammar Point 1. |
| 첩보 (ch'opbo, "intelligence report") / 포병 (p'obyong, "artillery man") / 총장 (ch'ongjang, "university president") / 특전 (t'ukchon, "privilege") / 탈주 (t'alju, "desertion") / 크다 (k'uda, "big") / 한국 (Hanguk, "Korea") / 허가 (hoga, "permit") | various | noun/adjective | technical.military (first 2, and t'alju) / core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | verified | vision-read p.328. |
| 군인 (kunin, "soldier") / 누구 (nugu, "who") | soldier / who | noun/pronoun | technical.military (kunin) / core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | verified | vision-read p.332; kunin is the spelling-rule worked example for Grammar Point 2. |
| 되다 (toeda, "become") / 권위 (kwonwi, "authority") / 전화 (chonhwa, "telephone") / 지뢰 (chiroe, "land mine") / 최고 (ch'oego, "the best") / 조화 (chohwa, "harmony") / 병원 (pyongwon, "hospital") / 대위 (taewi, "captain") | various | verb/noun | technical.military (chiroe, taewi) / core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | verified | vision-read p.331. |
| 왜 (wae, "why") / 궤 (kwe, "box, crate") / 외국 (oeguk, "foreign nation") / 웨이터 (weit'o, "waiter") / 의자 (uija, "chair") / 괭이 (kwaengi, "hoe") / 정의 (chongui, "justice") | various | noun/adverb | core | — | contemporary (source published 1984) | — | — | grammar_reference | n/a | verified | vision-read p.336; weit'o is an English loanword; the ㅚ/ㅙ/웨 set underlies Grammar Point 4. |

**Vocabulary count, this section: 116 entries** (rows above group tightly related short sets from the source for space; all individual forms are named).

---

### Cumulative Glossary — Korean-English (comprehensive pass, printed pp. 431–454)

Organized alphabetically by the glossary's own letter sections (A–Y; no entries under X, Z). Source Type is `dictionary` throughout (the book's own glossary section, distinct from running lesson prose). Attested Era `contemporary (source published 1984)` throughout; Attested Region/Geographic Scope `—` throughout (no explicit regional marking in source); Transcription Confidence `n/a` throughout. This is a comprehensive, not representative-sample, pass (the K-E glossary runs to roughly 460–480 distinct entries, under the project's ~600-entry sampling threshold). The English-Korean glossary (printed pp. 455–478) was confirmed to be the same term/gloss/unit-lesson data reverse-sorted and was not bulk re-extracted; its one genuinely new content (bare verb/adjective stems) is in the next table. Flagship military/rank content: the full enlisted/officer rank ladder plus service-branch and installation vocabulary not found elsewhere in the established corpus.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| a | oh (exclamation) | interjection | colloquial | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/3 |
| adul | son(s) | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | plausible_unverified | 5/1; OCR garbled, resolved via E-K cross-check |
| agassi | miss (address term for young females) | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 7/2 |
| ai / aidul | child / children | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 5/1; aidul listed as ai's sub-entry |
| Aigu! | Oh, wow! Gosh! Oh, no! Ouch! | interjection | colloquial | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 8/3; multi-purpose exclamation |
| ajik | still; yet | adverb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/3 |
| aju | very; very much; really | adverb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 3/3 |
| Algessumnida. | I see; I understand. | phrase | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/3 |
| an | not (used only with verbs) | particle | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/1 |
| aniyo | no | adverb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/3 |
| Annyonghashimnikka? | Hello; Good morning; Good afternoon; Good evening. | phrase | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/1; one formal greeting covering all times of day |
| Annyonghi kashipshio. / Annyonghi kyeshipshio. | Good-bye (to leaver) / Good-bye (to stayer) | phrase | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/4; register split by who is leaving vs. staying |
| apt / -ap'eso/-ap'e | front / in front of | noun/postposition | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 8/1 |
| araech'ung | downstairs; lower level | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 6/1 |
| Arassumnida. | I understand; I see; All right. | phrase | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 5/2; near-synonym of Algessumnida |
| baji | pants; trousers | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 3/3 |
| -ban | half-past (the hour) | counter/suffix | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 4/1; ex. hanshiban |
| -bul / -bun / -byong | dollar(s) / person(s) (polite) / bottle(s) | counter | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 2/1–2/3 |
| ch'a | tea (generic term) | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 7/1 |
| chaettori / chagae | ashtray / mother-of-pearl | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 7/1, 8/3 |
| ch'ajushimnikka / ch'atsumnida | are (you) looking for / (am) looking for | verb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 2/3 |
| chaksumnida | (is) small | verb/adjective | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 3/3 |
| chal | well; fine; satisfactorily | adverb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/1 |
| changgi settu | chess set | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 8/3 |
| changgyo | officer | noun | technical.military | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/3; general term, cf. full rank ladder below |
| changnyon | last year | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 4/3 |
| che | my | pronoun/determiner | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/2; humble/polite possessive, contrasts with uri |
| chigap | wallet | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 6/3 |
| chigum | now | adverb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 4/1 |
| chihado | underpass; underground walkway | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 6/2 |
| ch'imdae | bed | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 2/3 |
| chinaemnida | (am) getting along | verb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/1; ex. Ottok'e chinaeshimnikka? |
| ch'ingu | friend | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/2 |
| chip / chipsaram | house-home / wife (one's own) | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 5/1; chipsaram contrasts with puin/samonim |
| ch'irwol | July | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | plausible_unverified | 4/2; breve-digit OCR gotcha |
| choahamnida | like; enjoy | verb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 5/2 |
| chodo | I, too; me, too | pronoun+particle | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 7/2 |
| chogi / chogo | there-over there / that-that one-those | pronoun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 3/1, 5/3; part of the 3-way deictic system |
| chol / chonun | me (object) / I (subject, humble) | pronoun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 6/3, 1/3 |
| chom | a little; a little bit (also politeness softener) | adverb/particle | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/4; ex. Chom towa chushipshio |
| Ch'am pwepsumnida. | Pleased to meet you; How do you do? | phrase | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/2 |
| -chon | cent(s) | counter | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 2/3 |
| ch'onch'onhi | slowly | adverb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 6/1 |
| ch'ongbaji | blue jeans | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 3/3 |
| ch'ongja | celadon porcelain; item made of celadon | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 8/3 |
| chongmun | main gate; main door | noun | technical.military | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 8/1 |
| chonhwa | telephone | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 6/3 |
| Ch'onmaneyo. | You're welcome. | phrase | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 6/2 |
| chonyok | evening; dinner, supper | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 5/2; ex. Chonyok kach'i hapshida |
| ch'oroksaek | green | noun/adjective | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 3/2 |
| chossumnida | (is) good; great | verb/adjective | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 3/2 |
| ch'otchae / tultchae / setchae | first / second / third | ordinal | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 6/1; native-Korean ordinal series |
| chuimsangsa | E-9; SGM (Army) | noun | technical.military | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/3; Sergeant Major |
| ch'ulbal hamnida | (it) leaves; departs | verb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 8/2 |
| chumare | weekend; during the weekend | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 5/2 |
| chungryong | O-5; LTC (Army) | noun | technical.military | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/1; Lieutenant Colonel |
| chungsa | E-7; SFC (Army) | noun | technical.military | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/3; Sergeant First Class |
| chungwi | O-2; 1LT (Army) | noun | technical.military | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/1; First Lieutenant |
| chunwi | warrant officer | noun | technical.military | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/1; no pay-grade code given |
| chushigessumnikka / chushipshio | will you give / please give me | verb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 8/3, 2/1 |
| -do | too; also | particle | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 5/1 |
| emp'i | military police; MP(s) | noun | technical.military | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 6/3; romanized from the English initialism "MP" |
| -gae / -gap | counter for objects / pack(s) of cigarettes | counter | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 3/1 |
| haebyong / haebyongdae | Marine / Marine Corps | noun | technical.military | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/3; -dae "corps/unit" suffix |
| haegun | Navy; Navy personnel | noun | technical.military | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/3; confirmed absent from rest of established corpus |
| -haeng | bound for; going to | suffix | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 8/2; ex. Pusanhaeng posu |
| haessumnida | did; have done | verb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 5/1 |
| haeya twemnida | have to do; must do | verb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 5/3 |
| hagessumnida | will do; am going to (do); (also, with food/drink referents) will have | verb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 5/3, 7/1 |
| -hago | and (between nouns) | particle | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 3/2 |
| haji maseyo / -ji maseyo | don't (do) | verb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 5/3; ex. Ikunbok tariji maseyo |
| halil | things to do; work to do | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 5/2 |
| hamnida | (am) doing | verb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 3/2 |
| han / hanbon | about-approximately / once-one time | adverb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 6/2, 6/1 |
| hanguk / hangukton / hangungmal | Korea / Korean money / the Korean language | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 2/3, 7/1 |
| hapshida | let's do; let's make | verb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 3/2; ex. Sammanwone hapshida |
| hasa | E-6; SSG (Army) | noun | technical.military | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/3; Staff Sergeant |
| hasagwan | NCO; petty officer | noun | technical.military | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/3; confirmed absent from rest of established corpus |
| haseyo / hashyossumnikka | please do (informal) / have (you) done | verb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 5/3, 1/3 |
| hinsaek | white | noun/adjective | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 3/2 |
| hongch'a / huch'u | black tea / black pepper | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 7/1, 7/3 |
| horitti / hot'el | belt / hotel | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 5/3, 6/1; loanwords |
| hwajangshil | rest room | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 6/1 |
| hwannyul | exchange rate | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 2/3 |
| hwayoil | Tuesday | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 4/2 |
| iboboshipshio | please try on (clothing) | verb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 3/3 |
| ibugune | in this area; around here | adverb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 6/3 |
| ibul | quilt(s) | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 3/2 |
| ibyong | E-2; PV2 (Army) | noun | technical.military | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/2; Private Second Class |
| igo | this; this one; these | pronoun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 2/3 |
| il | matter; thing; problem | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 6/3; ex. Musun irimnikka?; homographic with numeral "il" (1) |
| ilbyong | E-3; PFC (Army) | noun | technical.military | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/2; Private First Class |
| iltchigi | early (verbs only) | adverb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 5/3 |
| -imnida | (I) am; he/she/it is, etc. | copula/suffix | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/2 |
| -inbun / inhyong | order(s)-serving(s) / doll(s)-figurine(s) | counter/noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 7/2, 8/3 |
| insamch'a / iri | ginseng tea / this way-towards me | noun/adverb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 7/1, 5/3 |
| irossumnida | lost; have lost (something) | verb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 6/3; ex. Chigap irossumnida, Kil irossumnida |
| irwol / iryoil | January / Sunday | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 4/2 |
| isadan | second division | noun | technical.military | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 8/1; confirmed absent from rest of established corpus |
| issumnida / opsumnida | there is/are-(I) have / there isn't-(I) don't have (negative) | verb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 2/1, 2/2 |
| ittaga | later | adverb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/4 |
| iwol | February | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | plausible_unverified | 4/2; breve-digit OCR gotcha |
| -jan / -jang | cup(s)-glass(es) / counter for tickets | counter | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 2/2, 8/2 |
| -ji maseyo / -jon | don't (do) / before-ago | verb/postposition | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 5/3, 4/1; ex. tushi shippunjon |
| jyusu | juice | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 7/1; loanword |
| kabang / kach'i / kagessumnida | bag-satchel / together-along / (am) going to go-will go | noun/adverb/verb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 8/3, 5/1, 1/4 |
| kalbi / kalbitchim | beef ribs / beef rib stew | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 5/2, 7/2 |
| kamnida | (am) going | verb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 5/2 |
| Kamsahamnida. / Komapsumnida. / Sugo haessumnida. | Thank you. (three forms) | phrase | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 3/1, 5/2 |
| kanjang / kapshi / kapshida | soy sauce / price / let's go-(to taxi driver) take me to | noun/verb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 7/3, 2/2, 5/2 |
| kashipshio | go; please go | verb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/4 |
| kich'a / kich'ap'yo / yolch'a | train (informal) / train ticket / train (formal) | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 8/2; synonym pair |
| kiji | base (usually Air Force or Navy) | noun | technical.military | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 8/1 |
| kil / kkaji | way-street-road / to-up to-as far as (dest.); by (time) | noun/postposition | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 6/3, 8/1; ex. Kil irossumnida, Seoulkkaji kamnida |
| kimch'i | pickled vegetables, generally cabbage | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 5/2 |
| kkamansaek | black | noun/adjective | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 3/2 |
| kogi / kohyang | meat / hometown | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 7/2, 5/1 |
| k'olla / Kollanhamnida. | cola / "It's difficult; No way!" | noun/phrase | core (colloquial for the phrase) | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 3/1, 3/2 |
| kollimnida / Komapsumnida. | it takes (time) / thank you | verb/phrase | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 4/1, 3/1 |
| komt'ang | rice with thick soup made from beef bones | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 7/2 |
| konggun / konggungiji | Air Force; personnel / airbase | noun | technical.military | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/3; confirmed absent from rest of established corpus |
| k'op'i / kosokposu | coffee / express bus | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 2/2, 8/2 |
| kot | right away; immediately | adverb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 5/3 |
| kudu / kugyong | shoes / watching-sightseeing-browsing-window-shopping | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 5/3, 5/2; broad semantic range of kugyong worth noting |
| kujo / kukchang | just-merely / movie theater | adverb/noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/2, 5/2; ex. Kujo kurossumnida |
| Kulsseyo ... | Well, I'm not so sure ... | phrase | colloquial | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 3/3; hedging discourse marker |
| kum / k'umnida / kumnyon / kumyoil | gold / (is) big-large / this year / Friday | noun/verb/noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 3/3, 3/3, 4/3, 4/2 |
| kunbok / kunhwa | military uniform(s) / military boots | noun | technical.military | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 5/3 |
| kunin | service member (branch-neutral) | noun | technical.military | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/3; contrasts with haebyong/haegun/konggun/yukkun |
| kunmu hamnida | works; performs duty | verb | technical.military | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 5/3; ex. Kunmu haeya twemnida |
| kurigo / kurom / kuromyon / kuronde / kuronikka / kuropshida | and-besides / well-well then / then-if you do that / by the way / so-therefore (sentence-initial only) / let's-let's do so | conjunction/adverb/verb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 3/1, 1/3, 6/2, 8/2, 2/3, 5/2 |
| k'urim | cream | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 7/1; loanword |
| Kurossumnida. / Kurossumnikka? | That's so-correct-right. / Is that so? | phrase | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/2, 1/3 |
| kuwol | September | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | plausible_unverified | 4/2; breve-digit OCR gotcha |
| kyegupchang | insignia of rank | noun | technical.military | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 5/3 |
| kyesanso / kyeshimnida | check-bill / there is/are (honorific, people only) | noun/verb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 7/2, 2/1 |
| kyolhon | marriage | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/3; ex. Kyolhon hashyossumnikka? |
| maekchu / saeng maekchu | beer (generally bottled) / draft beer | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 3/1 |
| maepsumnida / maep'yogu | is hot (spicy) / ticket window | verb/noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 7/2, 8/2 |
| makkoli / malssumhae chushipshio / mandukuk | rice wine (unrefined) / please say-tell me / wonton soup | noun/verb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 7/3, 6/1, 7/2 |
| mani / mannapshida | many (verbs only) / let's meet | adverb/verb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 3/2, 5/2 |
| mashi / mashigessumnida / mashipshida | taste-flavor / will drink / let's drink | noun/verb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 5/2, 7/3, 7/3; ex. Mashi chossumnida, Mashi issumnida |
| matsumnida / Mianhamnida. | (it) fits / I'm sorry | verb/phrase | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 3/3, 6/1 |
| miguk / migukpun / miguksaram / migukton | America / American (person, polite) / American (person) / American money | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 2/3, 8/4, 5/1; two register levels for "American person" are notable |
| migukkunin | American service member | noun | technical.military | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 5/1; compound of miguk + kunin |
| migun / migunbudae | American military; U.S. Armed Forces / American military installation | noun | technical.military | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 6/3; compound of miguk + kun, cf. yukkun/haegun/konggun |
| Mihonimnida. | (I'm) single. | phrase | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/3; from mihon "not married" |
| milgam | tangerine(s) | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 2/1 |
| minganin | civilian (person) | noun | technical.military | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/3; defined relationally against kunin |
| misu / misut'o | miss / mr. (junior address term) | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/2; loanwords, 3-tier address system with sonsaeng/sonsaengnim |
| modu / mogyoil | all; altogether / Thursday | adverb/noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 3/1, 4/2 |
| mokkessumnida / mokkori | (I) will eat / necklace | verb/noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 7/3, 3/3 |
| morugessumnida / mot / mul / mullon | (I) don't know / cannot / water / of course | verb/adverb/noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 6/3, 7/3, 1/3; ex. Chal mot hamnida, Mullonimnida |
| musun / mwe-mwo | what kind of; what / what | determiner/pronoun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 4/2, 2/3 |
| myoch'il | what date | adverb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | plausible_unverified | 4/2; breve-digit OCR noise; ex. Onul myoch'irimnikka? |
| myot / myotshi | how many (base of a productive family) / what time | determiner/adverb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | base for myotbun/myotgae/myotshigan etc. |
| naeil / naenyon | tomorrow / next year | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/4, 4/3 |
| naepk'in / naip'u | napkin / knife | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 7/3; loanwords |
| naerigessumnida / naeryoya twemnida | (I) will get out (vehicle) / (I) have to get out | verb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 8/1 |
| namp'yon / namul | husband (own) / vegetable side dishes | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 5/1, 7/3 |
| ne | yes | adverb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/1; also acknowledges a greeting per source note |
| negori / nomu | intersection / too (excessively) | noun/adverb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 6/2, 3/3 |
| noransaek / notchopshi / notkurut | yellow / brass plate / brass bowl | noun/adjective | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 3/2, 8/3 |
| nugu / nutke / -nyon | who-whom-someone-anyone / late (verbs only) / year(s) counter | pronoun/adverb/counter | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 6/3, 5/3, 4/3 |
| odi | where; what place | pronoun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 5/1; ex. odiso |
| ohu / ojon | afternoon; p.m. / morning; a.m. | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 4/1 |
| olmamnikka / olmana | how much is/are / how much | phrase/adverb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 2/2, 6/2 |
| omnida / onje / onu / onul | (am) coming / when / which / today | verb/adverb/determiner/noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 5/3, 4/2, 8/2, 4/2 |
| opsumnida | there isn't; (I) don't have | verb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 2/2; negative counterpart to issumnida |
| Oraeganmanimnida. | It's been a long time. | phrase | colloquial | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/1 |
| orenji / orenjisaek | orange(s) / orange (color) | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 7/1; loanword |
| oruntchok / oseyo / oshipshio / oshyossumnikka | the right-right side / please come (informal) / please come / did (you) come | noun/verb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 6/1, 5/3, 2/3, 4/2 |
| oso / ottok'e | quickly-right away / how | adverb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | plausible_unverified | 2/3, 1/1; ottok'e OCR breve-digit noise; ex. Oso oshipshio |
| owol | May | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 4/2 |
| p'ach'ulso | police substation | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 6/3 |
| pae / paekhwajom | pear(s) / department store | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 2/1, 6/2 |
| paekkum / -paekpan | platinum; white gold / full-course dinner | noun/counter | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 3/3, 7/2; ex. pulgogi paekpan |
| pang / panji / pap | room / ring / cooked rice | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 6/1, 3/3, 7/3 |
| pappumnida / p'aransaek | (is) busy / blue ("green" for nature) | verb/noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/1, 3/2; p'aransaek's blue/green overlap worth cross-checking against color chapters |
| paro / p'arwol | right; just; exactly / August | adverb/noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | plausible_unverified | 8/1, 4/2; p'arwol breve-digit OCR gotcha |
| peijisaek | beige | noun/adjective | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 3/2; loanword |
| pibimpap / pilding / p'iryo | rice with vegetables and meat / building / need; necessity | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 7/2, 6/1, 7/1; ex. p'iryo opsumnida |
| pissamnida / p'odoju / pogi | (is) expensive / wine / appearance | verb/noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 3/3, 7/3, 3/3; ex. Aju pogi chossumnida |
| p'ok'u / -pon | fork / "number" counter | noun/counter | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 7/3, 8/3; ex. Paekshippon t'ashipshio; -pon possibly OCR-confused with "-pan" in the Numbers appendix, see Grammar Points |
| popshida / posek | let me see; let me look at / jewelry | verb/noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 3/2, 3/3; ex. posokham |
| posu / pot'ongshil | bus / coach (on "the Blue Train") | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 2/2, 8/2; loanword; ex. posup'yo, posu t'ominal, posu yogum |
| ppalgansaek / ppalli | red / quickly | noun/adjective/adverb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 3/2, 5/3 |
| pudae | military installation; post | noun | technical.military | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 6/3 |
| puin | wife (someone else's) | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 5/1; contrasts with chipsaram and samonim |
| pul / pulgogi / pumonim | fire / marinated barbecued beef / parents | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 6/3, 5/2, 5/1; ex. Pul nassumnida! |
| -pun | minutes | counter | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 4/1 |
| pwepkessumnida / pwepsumnida | will see-meet / (I) see-meet | verb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/4, 1/2; ex. Tto pwepkessumnida, Ch'am pwepsumnida |
| p'yo / pyollo | ticket(s) / (not) really-particularly | noun/adverb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | plausible_unverified | 8/2, 1/1; pyollo breve-digit OCR gotcha, negation-only |
| pyongjang | E-5; SGT (Army) | noun | technical.military | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/2; Sergeant |
| Saemaulho | "the Blue Train" | proper noun | core | — | contemporary (source published 1984) | South Korea | national | dictionary | n/a | n/a | 8/2 |
| saeng maekchu / saengil | draft beer / birthday | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 3/1, 4/3 |
| sagessumnida / sagwa | (am) going to buy / apple(s) | verb/noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 3/2, 2/1; ex. sagwa jyusu |
| saida / saiju | lemon-lime soda / size | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 2/2, 3/3; loanwords |
| samnida / samonim / samwol | (am) buying / wife (someone else's, polite) / March | verb/noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 5/3, 5/1, 4/2 |
| sangbyong | E-4; SP4 (Army) | noun | technical.military | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/2; Specialist Fourth Class, confirmed absent from rest of established corpus |
| sangsa | E-8; MSG (Army) | noun | technical.military | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/3; Master Sergeant |
| -saram | person(s) | counter | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 2/1 |
| sashipshio / sawol | buy; please buy / April | verb/noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 8/2, 4/2 |
| set'ak haseyo / setchae | please wash (clothes) / third | verb/ordinal | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 5/3, 6/1 |
| -shi / shigan / shigye / shijang | o'clock / hour(s)-time / watch-clock / market | counter/noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 4/1, 2/1 |
| shiktang | restaurant; dining room; mess hall | noun | technical.military | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 6/1; "mess hall" sense ties it to military-installation vocabulary |
| shibirwol / shibiwol | November / December | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 4/2 |
| shilk'u brausu / Shillehamnida. / Shillejiman, ... | silk blouse / Excuse me. / Excuse me, but ... | noun/phrase | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 8/3, 6/1, 1/3; loanword-compound |
| shinae / shinhodung / shiwol | downtown / traffic signal / October | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 5/2, 6/2, 4/2 |
| sogae hamnida / sogogi / sogum | (am) introducing / beef / salt | verb/noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/2, 7/2, 7/3 |
| soju / solt'ang / songnyang | distilled liquor / sugar / matches | noun | core | — | contemporary (source published 1984) | South Korea (soju) | national (soju) | dictionary | n/a | n/a | 7/3, 7/1, 7/1 |
| sonsaeng / sonsaengnim | mr. (equal-status) / mr.-sir (senior-status) | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/2, 1/1; 3-tier age/status address system with misut'o |
| sop'a | sofa | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 2/3; loanword |
| soryong | O-4; MAJ (Army) | noun | technical.military | — | contemporary (source published 1984) | — | — | dictionary | n/a | plausible_unverified | 1/1; Major; breve-digit OCR gotcha |
| sowi | O-1; 2LT (Army) | noun | technical.military | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/1; Second Lieutenant, lowest officer rank in this ladder |
| ssage / -ssik | cheap (verbs only) / each; per | adverb/counter | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 3/2, 3/2; ex. Igo ssage hapshida, Hanassik chushipshio |
| sul / suson haseyo-susan haseyo / suyoil | alcoholic beverages (generic) / please mend-fix / Wednesday | noun/verb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | plausible_unverified | 7/3, 5/3, 4/2; suson/susan spelled two ways across glossary directions |
| tabang / t'aekshi | coffee shop / taxi | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 6/1, 8/1; loanword |
| taeryong / taewi | O-6; COL (Army) / O-3; CPT (Army) | noun | technical.military | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/1; Colonel / Captain, confirmed absent from rest of established corpus |
| takkgogi / tambae / tamnyo | chicken / cigarette(s) / blanket(s) | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 7/2, 2/2, 2/3 |
| tariseyo / tashi / t'ashipshio | please iron-press / again (try again) / please board | verb/adverb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 5/3, 6/1, 8/3; ex. tashi hanbon |
| taum / t'aya twemnida / t'eibul | next / (I) have to take (bus, train) / table | determiner/verb/noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/4, 8/3, 2/3; loanword |
| to / toch'ak hamnida / ton / toshipshio / t'oyoil | more / (it) arrives / money / turn / Saturday | various | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 7/3, 8/2, 2/3, 6/2, 4/2 |
| ttal / ttara / tto / ttokparo | daughter(s) / following / again-once more / straight ahead | noun/verb/adverb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 5/1, 6/3, 1/4, 6/2 |
| t'ukkup / t'ukshil / tultchae | express / first class / second | noun/adjective/ordinal | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 8/2, 8/2, 6/1 |
| twaejigogi / umshik | pork / prepared food | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 7/2, 5/2; ex. umshikchom |
| uri | we; our; my | pronoun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 5/1; contrasts with che |
| Waeyo? / wassumnida / waya twemnida | Why? / (I) came / (I) have to come | phrase/verb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/4, 4/2, 5/3 |
| wentchok / wich'ung | the left / upstairs | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 6/1 |
| -wol / -won / woryoil | month suffix / Korean monetary unit / Monday | counter/noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 4/2, 2/2, 4/2 |
| -ya twemnida | have to; must (do) | verb suffix | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 5/3; ex. Kunmu haeya twemnida |
| Yoboseyo! | Hello! Say! (attention-getter, not a greeting) | phrase | colloquial | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 6/1; explicitly NOT a greeting |
| yogi / yogum / yoil | here-this place / fare / day of the week | pronoun/noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 2/3, 2/2, 4/2; yogi part of the 3-way deictic set |
| yak | railroad station [tentative] | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | low_confidence | 6/2; identical in both glossary directions, not column-mixing, but doesn't match this project's established "yok" (역) — plausibly an inherited OCR misread, left as printed |
| yolch'a / yongo | train / English (language) | noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 8/2, 7/1; synonym of kich'a; ex. yongoro |
| yap'eso/-yaple / yosae | side-by-next to / these days-nowadays | postposition/adverb | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 6/2–6/3, 1/1 |
| yukkun / yukkyo | Army; Army personnel; soldier(s) / overpass | noun | technical.military (yukkun) / core | — | contemporary (source published 1984) | — | — | dictionary | n/a | n/a | 1/3; flagship finding, confirmed absent from rest of established corpus |
| yumyong hamnida / yuwol | (is) famous / June | verb/noun | core | — | contemporary (source published 1984) | — | — | dictionary | n/a | plausible_unverified | 8/4, 4/2; yuwol breve-digit OCR gotcha |

**Vocabulary count, this section: ~396 distinct headwords** (consolidated into the rows above, which group tightly alphabetically-adjacent or morphologically-related entries for space; every individual term/gloss pair from the chunk's full extraction pass is preserved).

### Cumulative Glossary — bare verb/adjective stems found only in the English-Korean direction (printed pp. 455–478)

The one genuinely non-redundant category found when reverse-checking the English-Korean glossary against the Korean-English one: several dozen verbs/adjectives cited in bare dictionary-stem form (trailing hyphen, as Korean grammars conventionally cite verb stems), where the Korean-English glossary only has the corresponding inflected/polite headword. All Source Type `dictionary`, Attested Era `contemporary (source published 1984)`, Attested Region/Geographic Scope `—`, Transcription Confidence `n/a`, Vision Reading Confidence `n/a`, Usage Tier `core` unless noted.

| Term (stem) | Gloss | Part of Speech | Notes |
|---|---|---|---|
| -i- | to be | copula stem | 1/2; ex. Hasagwanimnida, Changgyoishimnikka? — both using military-rank nouns |
| o- | to come | verb stem | 2/3; cf. oshipshio, oseyo, oshyossumnikka, omnida |
| ha- | to do | verb stem | 1/3; the most productive stem in the book |
| k'u- | (be) big | adjective stem | 3/3; ex. Nomu k'umnida |
| pappu- | (be) busy | adjective stem | 1/1 |
| sa- | to buy | verb stem | 3/2 |
| toch'ak ha- | to arrive | verb stem | 8/2 |
| pissa- | (be) expensive | adjective stem | 3/3; ex. Nomu pissamnida |
| yumyong ha- | (be) famous | verb stem | 8/4; ex. Lotte hot'el yumyong hamnikka? |
| naeri- | to get out/off (a vehicle) | verb stem | 8/1 |
| t'a- | to get on; board | verb stem | 8/1; ex. Paeksamshippon t'ashipshio |
| chu- | to give | verb stem | 2/1 |
| ka- | to go | verb stem | 1/4 |
| tari- | to iron; press (clothing) | verb stem | 5/3 |
| sogae ha- | to introduce | verb stem | 1/2; ex. Che ch'ingu sogae hamnida |
| chinae- | to get along | verb stem | 1/1 |
| choaha- | to like | verb stem | 5/2 |
| manna- | to meet | verb stem | 5/2 |
| mashi- | to drink | verb stem | 7/3 |
| mok- | to eat | verb stem | 7/3 |
| po- | to see; look at | verb stem | 3/2; ex. Ibul chom popshida |
| kolli- | to take (time) | verb stem | 4/1 |
| set'ak ha- | to wash (clothes) | verb stem | 5/3 |
| kunmu ha- (technical.military) | to work; perform duty | verb stem | 5/3 |
| ch'ulbal ha- | to leave; depart | verb stem | 8/2 |

### Numbers Appendix (printed pp. 479–480)

A clean standalone paradigm, extracted essentially in full since it is short and self-contained. Source Type `dictionary`, Attested Era `contemporary (source published 1984)`, Attested Region/Geographic Scope `—`, Transcription Confidence `n/a`, Vision Reading Confidence `n/a`, Usage Tier `core` throughout.

**Native Korean numbers 1–19** (with ㄱ-dropping "counting form" in parens for 1–4, per source): hana (han-) "1", tul (tu-) "2", set (se-) "3", net (ne-) "4", tasot "5", yosot "6", ilgop "7", yodol "8", ahop "9", yol "10" (base for teens), yolhana "11" (yol+hana), yoltul "12", yolset "13", yolnet "14", yoltasot "15", yolyosot "16", yolilgop "17", yolyodol "18", yolahop "19". No counting-form variant given for 5 and up.

**Sino-Korean numbers 1–19**: il "1" (homographic with il "matter/thing/problem" in the main glossary), i "2", sam "3", sa "4", o "5", yuk "6", ch'il "7", p'al "8", ku "9", ship "10" (base for teens), shibil "11" (ship+il), shibi "12", shipsam "13", shipsa "14", shibo "15", shimnyuk "16" (nasal assimilation p→m before y), shipch'il "17", shipp'al "18", shipku "19".

**Sino-Korean tens and higher (20–10,000,000)**: ship "10," iship "20" (i+ship), samship "30," saship "40," oship "50," yukship "60," ch'ilship "70," p'alship "80," kuship "90," paek "100," ch'on "1,000," man "10,000," shimman "100,000" (ship+man, same p→m nasal assimilation as shimnyuk "16" — flagged plausible_unverified only insofar as it departs from a naive "shipman" spelling, but phonologically regular and matches the pattern already attested at 16), paengman "1,000,000" (paek+man, same assimilation), ch'onman "10,000,000" (ch'on+man). Compound 21/22/31/32/41/42/51/52 examples given in source were not separately tabulated — fully predictable from the tens+ones pattern above, no new morphemes.

**Counters, grouped by the source into two number-system blocks:**

| Counter | Used with | Gloss |
|---|---|---|
| -bun / -byong / -gae / -gap / -jan / -jang / -saram / -shi / -shigan / -ssik | native Korean numbers | persons (polite) / bottles / objects (general) / packs (cigarettes) / cups-glasses / tickets / persons (plain) / o'clock / hours / each-per |
| -bul / -chon / -il / -inbun / -nyon / -pan-(-pon, see Grammar Points) / -pun / -wol / -won | Sino-Korean numbers | dollars / cents / dates / orders-servings (food) / years / "number" (flagged OCR ambiguity, see Grammar Points) / minutes / months / Korean money |

---

## Grammar points

### Front Matter & Unit 1 grammar points

**1. Basic word order: verb-final (p. 9).** A Korean sentence always places the verb at the end. Standard typological fact, substantively the same as coverage presumably already in `established/035_integrated_korean_beginning_1.md`. **Skipped as duplicate**, not reproduced in detail.

**2. Context-driven subject-dropping (p. 9).** A Korean sentence can drop its subject whenever context makes it clear, but must include one if there's a risk of ambiguity. **Skipped as duplicate** of `035`, though this chunk's own dialogues (e.g. *cho-nun* "I" explicitly stated as optional, p. 32) are a live illustration.

**3. The three-ending system this course teaches with (p. 9).** The book deliberately simplifies Korean's sentence-ending system to three practical endings: **-mnida** (statement), **-mnikka** (question), **-shipshio** (request) — explicitly presented as a reduced, practical teaching model, not the full six-level formality system `established/031_korean_honorifics_and_politeness.md` documents. **Kept** for this distinctive pedagogical framing, cross-referenced to `031` for the fuller system.

**4. Formal/informal duality and the "recognition-only" informal register (p. 9, reinforced throughout).** Every ending has a formal and informal counterpart. The course actively drills only the formal register; the informal register is exposed only passively, via a dedicated "Conversation for Listening Comprehension" at the end of most lessons — students are explicitly told they will never be tested on producing these forms, only recognizing them, "because many Koreans will mix both styles in the same conversation." **Kept in full** — distinctive course-design choice, and the reason this chunk's vocabulary includes informal variants (`annyonghaseyo`, etc.) alongside formal counterparts.

**5. The -shi- honorific infix is never used for the speaker's own actions (pp. 15–16).** -shi- marks honorific respect toward the person asked about/discussed, but is never applied to a statement about oneself (immodesty). Produces visible minimal pairs: `chinaeshimnikka?` vs. `chinaemnida`; `pappushimnikka?` vs. `pappumnida`. This beginner-level self/other asymmetry is foundational to, but narrower than, the gradient/advanced honorification `031` documents (which explicitly treats basic -(으)시 mechanics as already covered elsewhere). **Kept in full** — the clearest explanation of the rule found in this book.

**6. -nim: rank/title honorific suffix, placed immediately after the family name (p. 18).** `-nim` attaches directly after a rank/title (itself following the family name) to show respect toward someone senior, e.g. `Harris taewinim`. **Kept in full** — flagship content, tied to new rank vocabulary.

**7. One rank title per grade across all ROK armed services (p. 18).** Unlike the US system (different rank names per branch for the same grade), the ROK Armed Forces use one title per grade regardless of branch; the book uses Army-style English translations for simplicity while the Korean terms stay constant across branches. **Kept in full** — exactly the kind of military-cultural fact flagged as non-redundant and high-priority.

**8. Modesty convention in replying to casual well-being questions (p. 24).** Koreans customarily respond to "How are you getting along?"/"Are you busy?" with the deflecting `Kujo kurossumnida` ("Just so-so"), rather than direct positive statements. Stated explicitly as a cultural-pragmatic norm, not just a translation gloss. **Kept** as a distinctive sociolinguistic convention.

**9. Greeting-and-introduction etiquette (pp. 15, 25).** (1) Koreans bow/nod rather than defaulting to a handshake, and the junior person (age/rank/position) speaks first; (2) when introduced, the *senior* person decides whether to initiate a handshake. **Kept in full** — directly relevant to this book's military-rank social context.

**10. -jiman ("but") is a bound suffix, never standalone (p. 32).** `Shillejiman` = `shille` + `-jiman`; `-jiman` cannot be used by itself. **Kept** as a specific, narrow syntactic-constraint note.

**11. -ishimnikka: honorific question form of the copula (p. 32).** Combines honorific -shi- with copula + -mnikka ("are you/is he/are they"); context disambiguates which person. Example: `Yukkunishimnikka?` ("Are you in the Army?"). **Kept** as a clear worked example tied to new military-status vocabulary.

**12. -imnida: the copula carries no person or number marking (p. 24).** Can mean "I am"/"you are"/"he-she-it is"/"they are" with the same suffix. Likely already covered at a basic level in `035`. **Kept briefly** as essential scaffolding for this chunk's rank/identity sentences.

**13. Paired, asymmetric farewell expressions (p. 43).** `Annyonghi kashipshio` ("please go in peace") is said *to* the leaver; `Annyonghi kyeshipshio` ("please stay in peace") is said *to* the stayer. If both are leaving, both say `Annyonghi kashipshio`. **Kept in full** as a concrete pragmatics point.

**14. -gess-: future/intention marker (p. 42).** `Kagessumnida` = `ka-` + `-gess-` + `-umnida` = "I will go." Standard tense/aspect marker, likely covered generally in `035`, but **kept briefly** as load-bearing for this chunk's new farewell vocabulary.

**15. Consonant and vowel positional allophony demonstrated implicitly via the romanization chart's own example-word choices (pp. 10–11).** `taewi`, `odi`, `saram`, and the `l`/`r` realizations of ㄹ are reused across different chart rows in a way that implicitly illustrates lax-stop voicing-between-vowels (the same phenomenon `established/013` documents in IPA terms) without the book ever stating the rule explicitly. **Mechanism skipped as duplicate of 013**; the distinctive, pedagogically interesting *teaching device* itself (implicit illustration via shared example words, rather than an explicit rule statement) is what's kept/flagged here.

### Unit 2–3 grammar points (Numbers and Money; Shopping)

**1. Native vs. Sino-Korean number systems (pp. 54, 66–67).** Native numbers count ordinary small quantities with counters; Sino-Korean numbers (borrowed from Chinese) are required for money and any number ≥100. **Defers to `established/035` and `established/042`** for the mechanism; this book's distinct contribution is pairing the split immediately with military personnel counts and a currency-exchange conversation (point 4).

**2. Counter-triggered truncation of hana/tul/set/net (p. 57).** Before a counter like -gae: hana→han-, tul→tu-, set→se-, net→ne- (e.g. *sagwa han-gae*, not *sagwa hana-gae*). Kept as a concrete irregular-shortening rule with clean examples.

**3. Sound changes in Sino-Korean number combination (pp. 67, 70–71, 78–79).** ship→shib- before -il/-i/-o; ship+yuk→shimnyuk (not shipyuk); paek stays bare except the bound compound form -baek (except yukpaek); zeros never read aloud (1,050 = "ch'ŏn oship," not "ch'ŏn-yŏng-oship"); paek→paeng- before man; ship→shim- before man. **Largely the same mechanism as `established/045`/`050`**; kept here for this book's unusually thorough before/after sequencing at each juncture, useful for cross-checking those files.

**4. Honorific split in existence/possession verbs, tied to military rank (pp. 60, 63).** `issŭmnida`/`issŭmnikka` for objects and equal/lower-status people; `kyeshimnida`/`kyeshimnikka` honorific substitute for higher-rank/status people. The book's worked examples pair -saram (plain) with "yukkun" (soldiers) and -bun (honorific) with "changgyo" (officers) — a direct grammar-to-military-hierarchy mapping, this book's distinctive angle, **kept in full** even though the general honorific-existence-verb system is covered elsewhere.

**5. Irregular negative of issŭmnida (p. 72).** Not formed with the regular an- prefix (taught in Unit 1); instead an irregular stem, `opsŭmnida`. By contrast `kyeshimnida`'s negative *is* regular (`an kyeshimnida`). **Kept** as a specific, nameable irregularity.

**6. -pshida suggestion ending used performatively in bargaining (pp. 100–101, 110).** `po-`+`-pshida`→`popshida` ("let me see"); `ha-`+`-pshida`→`hapshida` ("let's make it..."), the functional core of Unit 3's bargaining language.

**7. -e particle marking the bargaining target, price or quantity (p. 101).** `Sach'ŏnwone hapshida` ("let's make it 4,000 won"); also marks a bulk-quantity target (`Tugaee yungman sach'ŏnwon ottossŭmnikka?`). Kept for this specific price/quantity-marking use in bargaining frames.

**8. hago vs. kŭrigo for "and" (p. 91).** `hago` connects two nouns directly, never sentence-initially; `kŭrigo` connects clauses/utterances, only sentence-initially, never joins two nouns. Explicit book contrast, kept for clarity.

**9. chom as a politeness softener detached from its literal meaning (p. 100).** In a request like `Tamnyohago ibul chom popshida`, *chom* ("a little") adds no literal quantity meaning — purely a softener. Flagged as a distinct, bleached pragmatic use.

**10. Formal vs. semi-formal speech-style alternation shown via paired dialogues (pp. 90–91 vs. 97–98; 100–101 vs. 107–108; 110 vs. 118–119).** Each main Conversation is given twice — formal `-(sh)ipshio/-(sŭ)mnida`, then nearly verbatim in semi-formal `-eyo/-yo` as a "Conversation for Listening Comprehension." **Defers to `established/035`/`042`/`045`** for the mechanism; this book's back-to-back identical-script teaching device is kept as a distinctive, clean worked example.

**11. Bargaining pragmatic script (pp. 100–101, 110, 118–120).** A consistent cultural-pragmatic sequence: shopkeeper states price → customer proposes a lower round number with `hapshida` → shopkeeper softens refusal with `kollanhamnida` and offers a smaller discount → customer leverages bulk purchase to extract a better rate → shopkeeper counters with `ottossŭmnikka` → customer accepts with `chossŭmnida`. Captured as a discrete point since it's the book's central instructional content for Lessons 2–3.

**12. p'aransaek doing double duty for "blue" and "green" (p. 104).** Explicitly used for "green" specifically for grass/trees/leaves (natural referents), while `ch'oroksaek` is the only term for "green" on man-made objects. A genuinely distinct lexical-semantic finding.

**13. iboboshipshio restricted to clothing (p. 111).** `ibo-` ("to try on") used only for clothing; other item categories use different, unspecified verbs. Flagged as a named gap in this book's own coverage.

### Unit 4–5 grammar points (Time and Dates; Everyday Conversation)

**1. "Larger to smaller" time-ordering principle (p. 123).** Korean states dates/times largest-to-smallest (year→month→day→hour→minute), reverse of English. Likely covered elsewhere for Sino-Korean date expressions; kept for the explicit mnemonic framing and full worked example.

**2. Native-Korean numbers 1–4 truncate before a counter (p. 124).** hana→han, tul→tu, set→se, net→ne before -shi; 5+ do not truncate. Kept briefly as the book's own worked hour-counter set.

**3. -imnikka/-imnida drop the initial -i after a vowel-final or -shi-final stem (pp. 125, 147).** E.g. *chigum myotshimnikka?*, generalized by the book to any vowel-final word.

**4. -ban "half past" (p. 126).** Attaches directly after the hour word with no linking element: *hanshiban*, *yolhanshiban*.

**5. shigan (duration) vs. -shi (point in time) (pp. 127–128).** Presented as a minimal semantic pair: *myotshigan kollimnikka?* vs. *chigum myotshimnikka?* — the single teaching point of this section.

**6. Minutes = Sino-Korean number + -pun/-bun (pp. 129–131).** -pun surfaces as -bun after a vowel-final morpheme; the hour phrase always precedes the minute phrase (e.g. *tasotshi oshippun*, never reversed).

**7. -jon "before," attaching to a minutes phrase (pp. 132–133).** *obunjon* "five minutes to [the hour]"; *hanshi obunjon* "five minutes to one." A separate ending, *-jonimnida*, is drilled for full-sentence use.

**8. ojon/ohu + -e attaches to the last time reference only (p. 135).** *Ojon yolshie* "at 10 a.m." — the same -e particle also marks destinations (cf. *hanguge*, *miguge*), so it's polysemous between "at/in" (time) and "to" (goal).

**9. Days of the week = yoil, with Sino-Korean-origin fixed names (pp. 135–136).** A closed lexical set with no etymological breakdown given by the book; treated here as vocabulary rather than re-deriving grammar likely covered in the corpus's general calendar-vocabulary files.

**10. Months = Sino-Korean number + -wol, with assimilation (p. 138).** il→ir- (irwol), yuk drops k (yuwol) — but **the book itself flags this k-drop as not categorical among younger speakers**, who may say yugwol instead — a rare instance of the book documenting live sociolinguistic variation rather than a single fixed rule. ship also drops p before -wol (shiwol).

**11. Day-of-month = Sino-Korean number + -il, same assimilation pattern (pp. 140–143).** Full 1st–31st paradigm given across three exercises (iril, iil, samil ... samshibiril), same il→ir-/ch'il→ch'ir-/p'al→par-/ship→shib- assimilations as elsewhere in the numeral system.

**12. Years = Sino-Korean number + -nyon, read as one whole number (p. 144).** Splitting a year into two chunks the way English does ("nineteen seventy-nine") is explicitly marked **incorrect**; Korean reads the full number as one quantity (*ch'ongubaek p'alshipsanyon* = 1984). Ku→gu after ch'on; yuk's k assimilates before -nyon's n in the worked 1776 example.

**13. Two-digit year abbreviation, and year-before-date ordering (p. 145).** Only the last two digits may be used, only when unambiguously within the current century; when a year appears with a full date, the year is placed first (consistent with Point 1).

**14. Honorific vs. non-honorific verb pairs, with self+spouse+children grouped as non-honorific (p. 161, 199–200 context).** Honorific forms (chinaeshimnikka, etc.) for **other adults**; plain forms (chinaemnida, etc.) for **oneself, one's spouse, and one's children**. Overlaps substantially with `established/031`'s general honorific-infix system; what's distinctive and kept is the explicit social rule grouping a spouse with "self" rather than "other adults" for verb-honorification purposes, even though one might show lexical respect to someone else's spouse (*samonim*).

**15. Korean word order is mostly flexible, with specific fixed-position exceptions (p. 164).** Locative/time phrases can often be reordered freely, but: (a) a number-counter phrase must immediately follow its noun; (b) the negation particle *an* must sit immediately before the verb (or, for *ha-* compound verbs, immediately before the *ha-* element). `Pogi an chossumnida` given as a parallel fixed-order example.

**16. Possible duplicate, skipped in depth: necessity construction V-aya/-eya twemnida (pp. 182–183).** Clean minimal-pair paradigm (omnida/waya twemnida; kamnida/kaya twemnida; samnida/saya twemnida; hamnida/haeya twemnida; kunmu hamnida/kunmu haeya twemnida). Almost certainly already documented elsewhere (`035`/`042`); the plain-vs-obligation paradigm itself is kept in the vocabulary table as the book's own minimal-pair teaching device.

**17. -pshida "let's..." suggestion ending (pp. 168–169).** *hapshida*, *mannapshida*, *kapshida*; *kuropshida* is the fixed agreement response.

**18. Register split: formal `-(s)umnida/-(s)umnikka` vs. informal-polite `-yo`, explicitly recognition-only (pp. 166, 178–179).** Twice in this range, the book reproduces its main dialogue content verbatim but re-renders every sentence ending into the informal-polite `-yo` pattern under "Conversation for Listening Comprehension" — explicit framing: students must **recognize**, not **produce**, this register. A genuine, distinct sociolinguistic/pragmatic finding, independent of the honorific-infix system in Point 14 (the -yo forms here are still polite, just less formal — not impolite/intimate speech).

**19. choahamnida ("I like it") vs. chossumnida ("it is good/that's OK") (pp. 168–169, 172).** The book explicitly separates liking (experiencer-subject *choahamnida*) from a thing being good/tasting good (property predicate *chossumnida*/*mashi chossumnida*). Negative of the taste sense (*mashi an chossumnida*) explicitly distinguished from *an choahamnida*.

**20. Possible duplicate, skipped in depth: -ji maseyo negative imperative (pp. 185–186).** Standard paradigm (kaji maseyo, tariji maseyo, susan hajimaseyo, oji maseyo, kunmu haji maseyo, saji maseyo, set'ak haji maseyo). Likely already covered elsewhere (`035`/`042`/`045`); kept at vocabulary-table depth for the several distinct verb stems it introduces.

**21. iltchigi "early" is restricted to verbal contexts (pp. 180–181).** Can modify a verb (*chom iltchigi oseyo*) but **cannot** modify a noun — "early dinner" cannot be *iltchigi chonyok*. A concrete, falsifiable distributional constraint.

**22. kuronikka as a sentence-initial discourse connective (p. 180).** "So/therefore/accordingly," drawing a consequence from the previous sentence (*Kuronikka, kot haeya twemnida*).

### Unit 6–7 grammar points (Directions; Restaurants and Food)

**1. -eso (dynamic-activity locative) vs. -e (static existential location) (Unit 6 L2, p. 205).** `chonegorieso wentchoguro toshipshio` ("turn left AT that intersection") uses -eso because *toda* is an activity verb, while `negorie issumnida` ("it IS AT the intersection") uses static -e because *issumnida* is existential. -eso also separately marks a source ("from"), as in `Detroiteso wassumnida`. **Skipped as duplicate** of the identical mechanism in `established/001_basic_korean_part1.md`, Unit 14 ("Case particles 3"); only this book's own example sentence is preserved (as vocabulary).

**2. Directional particle -(g)uro ("to"/"toward") (Unit 6 L2, p. 205).** *wentchok*+*-uro*→*wentchoguro*; surfaces as *-guro* (not *-uro*) after a final -k (lenition). Distinct from the "-ro = by means of" sense also seen in this chunk (*yongoro*, Unit 7 L1) — the book never unifies these two uses explicitly, but the data suggests a single polysemous particle rather than two coincidental homophones.

**3. cho- "that" as a bound, never-standalone demonstrative prefix (Unit 6 L2, pp. 205–207).** *cho-* and *i-* only ever combine with a following noun (*chobun*, *chotamnyo*) — contrasted with free-standing *chogi*/*chogo* and *yogi*/*igo*, which can stand alone. Produces the four-way person/thing/place demonstrative paradigm in the Vocabulary table. Not found duplicated verbatim in files sampled for cross-reference; kept in full as potentially new framing (though the underlying 이/저 system is well-attested generally).

**4. shigan olmana vs. myotshigan — "how much time" vs. "how many hours" (Unit 6 L2, p. 205).** A semantic-register distinction between open-ended quantity (*olmana*) and countable-unit (*myot-*+counter) questions on the same noun *shigan*. A useful minimal-pair illustration of Korean's count/mass quantifier split.

**5. han- as an approximative prefix before number expressions (Unit 6 L2, p. 205).** `han` ("one") prefixed to a number/time expression shifts meaning to "about/approximately" (*han shippun* "about 10 minutes"). A distinct, lexically-specific grammaticalization, separate from han's cardinal use.

**6. Register pair: formal vs. casual -yo/-eyo in "Conversation for Listening Comprehension" (Unit 6 L1–3, Unit 7 L1–3; pp. 203, 212, 222, 237, 245, 253).** Every lesson in this range pairs its formal-register conversation with a casual/polite-informal retelling (*issumnida→issoyo*, *chushipshio→chuseyo*, *hagessumnida→hagessoyo*, *mwomnikka→mwoyeyo*, etc.) — a deliberate minimal-pair didactic design. The book itself flags **maewoyo** as "a less formal way to say" *maepsumnikka*/*maepsumnida* (Unit 7 L2, p. 245); "Sesaramyo" is explicitly glossed by the book as *sesaram* + the casual -yo suffix attachable even to a bare noun phrase, not just verb stems.

**7. P'ach'ulso and the American-MP liaison system (Unit 6 L3, p. 215) — military-context finding.** The book's own note states p'ach'ulso (neighborhood police substations) are positioned at strategic points in every town specifically so a duty officer can call an American MP in an emergency involving a US service member — a genuine piece of 1984 US-military-in-Korea infrastructure/liaison-protocol content, not just vocabulary.

**8. Pulgogi paekpan — the shared full-course dinner convention (Unit 7 L2, p. 239).** When ordered for more than one person, the entree and side dishes are shared communally, while rice and soup are served as individual portions per person — an explicitly-stated Korean dining convention, kept as cultural-pragmatics content in its own right.

### Unit 8–9 grammar points (Transportation; Hangul, Optional)

**Unit 8**

**1. -까지 (-kkaji): dual place/time sense (p. 262).** "Up to/to/as far as" with a place noun (*Songt'ankkaji*); "by" with a time expression (*Neshikkaji oshipshio*) — made an explicit NOTE by the book rather than two separate particles.

**2. -에서/-서 (-eso/-so) and its vowel-conditioned shortening (p. 262).** Shortens to -so after a vowel-final noun (*yogi+eso→yogiso*; *odi+eso→odiso*), paralleling the -i-dropping pattern in Point 5.

**3. Compound-initial lenition: migun + pudae → migunbudae (p. 262).** Initial p of *pudae* lenites to b after *migun*. The same general mechanism `established/013` documents as its voicing rule (lax consonants voice between voiced sounds) — a concrete, military-register-specific worked example rather than a new mechanism.

**4. -행 (-haeng) "bound for" (p. 270).** Attaches to a destination place-name (*pusan+haeng→pusanhaeng*), used to specify which bus/train a traveler wants.

**5. Copula-initial -i dropping after a vowel-final stem (p. 272).** *posu+imnida→posumnida*, not *posuimnida* — an explicit book NOTE, paralleling Point 2; both instances of a general vowel-hiatus-avoidance pattern recurring across this book's particle/copula morphology.

**6. The paired formal/polite-informal "Conversation for Listening Comprehension" register device (pp. 267–268, 277–278, 288–289, 297–299).** Each of Unit 8's four lessons closes with a word-for-word register-recast of its opening dialogue (-ㅂ니다/-ㅂ니까/-(으)십시오 → -아/어요/-세요). The general two-style system is documented in `established/031`; this book's true minimal-pair back-to-back device makes the morphological correspondences unusually concrete — useful as a clean worked-example set.

**7. In-group/out-of-group kinship-honorific asymmetry (p. 296).** 우리 집사람/우리 남편 (humble/plain, one's own spouse) vs. 부인/사모님 (honorific, someone *else's* wife/a married woman generally) — presented as a fixed pair rather than derived from a general rule. Same system as `established/031`'s in-group/out-group politeness, applied here to a specific lexical domain (spousal reference) in unusual concrete detail.

**8. -(아/어)야 되다 necessitative ("have to V") (p. 286).** *t'a-*+*-ya twemnida→t'aya twemnida*; *naeri-*+*-oya twemnida→naeryoya twemnida*. Standard necessitative, given brief treatment as core A1 grammar likely covered at length elsewhere.

**Unit 9 (Hangul)**

**Skipped as redundant with `established/013` and other Hangul-inventory sources:** the full letter-by-letter introduction of the 14 base consonants, 8 simple vowels with stroke order, y-/w-vowel systems, double/tense consonants, syllable-block assembly, and the "zero consonant" ㅇ placeholder convention.

**1. "Same final sound, three legitimate spellings" (곳/곧/곶) (p. 322).** *kot* is pronounceable one way but spellable three (곳 "place," 곧 "soon," 곶 "cape," distinct from 꽃 "flower"), with no way to recover the correct spelling from sound alone. The same underlying phenomenon `established/013`'s "Full closure" rule documents mechanistically (eleven consonant letters converging to three coda sounds) — but framed here from the opposite direction, as a *spelling* problem rather than a *pronunciation* rule — a genuinely complementary pedagogical angle.

**2. Morpheme-boundary-preserving spelling — Hangul orthography is morphophonemic, not purely phonemic (pp. 332–333).** Rule 1: a word with identifiable morphemes is spelled so each stays in its own syllable even when connected-speech pronunciation would resyllabify across the boundary (군인 "soldier" = 군+인, spelled 군+인 not 구+닌, though pronounced [구닌]). Rule 2: a word with no smaller meaningful components has its sounds "evenly grouped" instead — a medial consonant joins the *following* syllable's onset (누구 "who" = 누+구, not 눅+우). Genuinely distinct from `established/013` (which documents pronunciation-adjustment rules, not this orthographic convention) — directly comparable to how English "write" keeps its silent *w* to preserve a visible link to "writer"/"wright."

**3. ㅇ's syllable-position-restricted use for /ng/ (p. 333).** As a special case of Rules 1/2 above, ㅇ can represent /ng/ only in syllable-*final* position — word-medial /ng/ must always group with the *preceding* syllable, regardless of which general rule would otherwise apply. The book flags this explicitly as the one systematic exception to its own Rule 1/Rule 2 framework.

**4. A practical spelling heuristic for the ㅚ/ㅙ/웨 merger (p. 335), supplementing `established/013`.** `013` already documents the [we]-type merger of ㅚ/ㅞ/(careful-speech)ㅙ for most speakers; this book adds a concrete fallback `013` doesn't give: when a learner hears "w+e" and can't determine the spelling, **spelling it ㅚ is correct roughly nine times out of ten** — an empirically-pitched, non-rule-governed practical guessing strategy.

**5. Minor aside — tense consonants as the default landing spot for borrowed English voiced stops (p. 336).** Korean speakers transcribing English loanwords beginning g/d/b often use the corresponding Korean "double" (tense) consonant rather than the plain lax one (English "gas" → 까스, not 가스). Connects to (without adding new mechanism to) `established/013`'s finding that Korean lax stops are voiceless word-initially, explaining why tense consonants end up perceptually closer to English's voiced stops in loanword adaptation.

### Glossary & Numbers Appendix grammar points

**1. Dual numeral systems with a split counter inventory.** The Numbers appendix makes explicit what the main glossary only shows piecemeal: two parallel numeral systems, each counter lexically locked to one system or the other — never both. Native-Korean-number counters are for bottles, objects, packs, cups/glasses, tickets, persons, o'clock, hours, "each/per" (concrete everyday things); Sino-Korean-number counters are for dollars, cents, dates, orders/servings, years, minutes, months, Korean currency (calendar/money reckoning). A structural fact of the language, not stylistic choice — the book's own appendix organizes its counter list by exactly this split.

**2. ㄱ-final "counting form" alternation in native-Korean 1–4.** `hana→han-`, `tul→tu-`, `set→se-`, `net→ne-` — the free-standing numeral drops its final segment when combining directly with a following counter/noun (*han bon* "once," *hanshiban* "half-past one"). The source gives this only for 1–4 and is silent on 5+, consistent with how this contraction is typically described as limited to the lowest numerals.

**3. Possible OCR-vs-print ambiguity flagged, not resolved.** The Numbers-appendix counter table's "-pan" entry (grouped with Sino-Korean-number counters, glossed only as part of a "number(s)" pairing) sits suspiciously close to two different real items in the main glossary: `-ban` "half-past" (a native-Korean-number counter — wrong number-system to appear in this block) and `-pon` "number" (a Sino-Korean-number counter, glossed exactly "number" — right system, right gloss). The balance of evidence favors this being `-pon` mis-OCR'd as `-pan`, but a native-speaker check against the original scan would be needed to confirm; flagged here rather than silently corrected.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes, dialogue blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`.
