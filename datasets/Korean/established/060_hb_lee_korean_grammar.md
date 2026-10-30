# Korean — Established Vocabulary/Grammar: H.B. Lee, *Korean Grammar* (Oxford University Press, 1989) — Chapters I–VII (complete)

**Source:** Hyun Bok Lee (H.B. Lee), *Korean Grammar*, Oxford University Press, 1989 — a reference grammar by the (then) Professor of Phonetics and Linguistics, Seoul National University. Full-book coverage: Chapter I Introduction, Chapter II Phonetics and Phonology, Chapter III Word and Word Classes, Chapter IV Structure of the Verb, Chapter V Phrase, Chapter VI Clause, Chapter VII Sentence (printed pp. 1–194), followed by a Bibliography, an Appendix ("Index of Grammatical Suffixes and Endings"), and a general subject Index (printed pp. 195–216, not extracted — see the closing note below).

**Source file:** PDF, 117 pages (A4, scanned). Confirmed via `pdfinfo`/`pdffonts`/`pdftotext` across the **entire file**: zero embedded fonts, zero text layer anywhere — a pure raster scan from cover to cover, not a font-substitution cipher of any kind (there are no font glyphs at all to attempt decoding). Every page of actual content was vision-read from 150 DPI renders (`pdftoppm -r 150`). Each PDF page past the front matter is a two-printed-page spread; the mapping `PDF_page = 9 + floor(printed_page/2)` was verified empirically against the visible running headers/page numbers at every chapter boundary in the book (Ch. I/II start, II/III, III/IV, IV/V, V/VI, VI/VII, and VII/Bibliography) and held exactly throughout — no drift, no non-monotonic page ordering found. **No handwritten marginalia was found anywhere in the book** — every page is clean typeset print only, with no previous-owner annotation to exclude.

**Extraction history.** This file merges six extraction passes against the book's seven chapters. A prior dispatch split the book into six chunks (Chapters I–II combined, then III, IV, V, VI as individual chunks, plus a sixth chunk intended for Chapter VII) and completed five of the six before failing silently without producing the sixth chunk or merging anything. This file is the product of a recovery pass that (1) verified all five surviving chunks for structural correctness (12-column Vocabulary headers, no placeholder text — all five passed without needing any correction), (2) extracted the missing Chapter VII "Sentence" directly via vision-reading (confirmed via `pdftotext -f 1 -l 3`/`pdffonts` that the whole file, not just this chapter, has no text layer to decode — see above), and (3) merged all six pieces into this single file. Each chapter section below retains its own independent non-redundant-supplement scope-decision note, explaining what was skipped as already covered by this project's other established Korean sources and what was kept as genuinely new — see `00_Reference_Extraction_Spec.md` for the general coverage rule this follows.

---

## Chapter I: Introduction and Chapter II: Phonetics and Phonology

**Source range:** H.B. Lee, *Korean Grammar* (Oxford University Press, 1989), Chapter I "Introduction" (§1.1–1.4) and Chapter II "Phonetics and Phonology" (§2.1–2.10). PDF pages 9–27 of the scanned source (printed pp. 1–36). Confirmed empirically: PDF page 9 = printed p.1 (right side only, left blank); each subsequent PDF page = one two-printed-page spread (`PDF_page = 9 + floor(printed_page/2)`), verified against running headers/page numbers at every page checked in this range. No cipher attempted or needed — `pdffonts`/`pdftotext` confirm **zero embedded fonts and zero text layer**: this is a pure raster scan, not a font-substitution case. All content vision-read from 150dpi renders. **No handwritten marginalia found anywhere in this range** — all pages are clean typeset print.

**Non-redundant-supplement scope decision.** Checked against `013_sounds_of_korean_pronunciation_guide.md` (Korean's dedicated phonology reference — vowel system, three-way laryngeal consonant contrast, connected-speech sandhi rules, pitch/length prosody) before extracting.
- **Skipped as substantially redundant with 013:** the full per-phoneme phonetic-description subsections (§2.3.1.1–2.3.1.9 vowels, §2.3.2.1–2.3.2.4+ consonants) — these are IPA-cardinal-vowel-chart style articulatory descriptions with extensive minimal-pair word lists covering the same vowel/consonant inventory and three-way (plain/aspirated/glottalized) laryngeal contrast 013 already documents in comparable depth. Only a small representative vocabulary sample is kept below rather than the full lists. Also skipped: most of Chapter I's historical/genetic-classification prose (Altaic theory, speaker counts, etc.) as scene-setting with no grammar/vocabulary content.
- **Kept as genuinely new:** §1.2's morphemic-vs-phonemic spelling-principle analysis (with the 목/모기 homophone-spelling contrast) and §1.2.3's explicit link between the Hunminjŏngŭm consonant-letter system and Firthian "Prosodic Analysis" (digraph/gemination = phonematic unit + prosody, not arbitrary shapes) — a distinctive theoretical framing not seen in any prior Korean extraction. §1.4's full worked rank-hierarchy example (Sentence > Clause > Phrase > Word > Morpheme, with upward/downward rank shift) using one fully glossed and morpheme-segmented sentence. §2.4's explicit syllable-structure formula and coda-consonant restriction (only 7 consonants permitted in coda position). §2.6 "Stress Group" — Lee's own distinctive rhythmic-unit concept (a stressed syllable plus any adjacent unstressed syllables), **not found in 013 or any other established Korean file** (`grep -li "satellite"` across all 59 prior files returned zero hits for Lee's broader Nucleus/Satellite terminology too, confirming this book's specific theoretical apparatus is new to the corpus). §2.7 Juncture — the plus/tentative/terminal three-way juncture system, including the compound-word-vs-phrase juncture test (보리쌀 'barley grains' vs 보리 쌀 'barley and rice'). §2.8–2.9 Intonation/Intonemes — the 17-tune attitudinal intonation inventory reduced to 4 syntactically-relevant "intonemes" (LF/HF/R/L), a genuinely distinct grammatical (not just phonetic) use of intonation not covered elsewhere in this corpus. §2.10 Transcription — the 15-rule systematic derivation of phonemic from orthographic (morphophonemic) spelling, including the 사이시옷 (saisiot) linking-consonant phenomenon in compounds (냇가 /nedka/ < 내 + 가, 옷안 /odan/ < 옷 + 안) — kept as a named rule-set with representative examples rather than reproducing all 15 rules' full example lists.

---

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 기다리던 / gidalidʌn | '(that I) have been waiting for' | verb (adjectival clause form) | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | full rank-hierarchy worked example, §1.4 p.8 |
| 눈 / nu:n | 'snow' | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | §1.4 worked example, p.8 |
| 많이 / ma:ni | 'in plenty' | adverb | core | — | contemporary | — | — | grammar_reference | n/a | verified | §1.4, p.8 |
| 오니 / oni | 'as it comes/falls' | verb (non-final clause form) | core | — | contemporary | — | — | grammar_reference | n/a | verified | §1.4, p.8 |
| 나 / na | 'I' | pronoun | core | — | contemporary | — | — | grammar_reference | n/a | verified | §1.4, p.8 |
| 의 / e (< ii) | 'of' (genitive particle) | particle | core | — | contemporary | — | — | grammar_reference | n/a | verified | §1.4, p.8; written 의 but pronounced /e/ |
| 기분 / gibun | 'mood' | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | §1.4, p.8 |
| 좋다 / jo:ta | 'is good, feels fine' | verb (descriptive) | core | — | contemporary | — | — | grammar_reference | n/a | verified | §1.4, p.8-9 |
| 목 / mog | 'neck' | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | §1.2.1 p.4, morphemic-spelling homophone-contrast example vs. 모기 'mosquito' |
| 모기 / mogi | 'mosquito' | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | same homophone-spelling pair, p.4 |
| 벼 / bʌl / [bʌl] | 'bee' | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | vowel-quantity minimal pair vs. 벌 'punishment', §2.2.4.1 p.13 |
| 벌 / bʌl | 'punishment' | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | same minimal pair, p.13 |
| 눈 / nu:n | 'eye' | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | §1.2 syllable-block example (contrasts with 눈 'snow' above — vowel length distinguishes them in full phonemic transcription though spelled identically) |
| 모자 / ' mo:ja | 'mother and son' | noun phrase | core | — | contemporary | — | — | grammar_reference | n/a | verified | long/short-vowel minimal pair vs. 모자 'cap, hat', §2.5 p.22 |
| 모자 / ' moja | 'cap, hat' | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | same minimal pair, p.22 |
| 보리쌀 / bo'lišal | 'barley (grains)' | noun (compound) | core | — | contemporary | — | — | grammar_reference | n/a | verified | compound-word-vs-phrase juncture test, §2.7 p.28-29 |
| 보리 쌀 / bo'li + šal | 'barley and rice' | noun phrase | core | — | contemporary | — | — | grammar_reference | n/a | verified | contrasts with compound above via plus-juncture, p.29 |
| 산길 / sankil | 'mountain path' | noun (compound) | core | — | contemporary | — | — | grammar_reference | n/a | verified | same juncture-contrast pattern, p.29 |
| 산 길 / san + gil | 'mountain and path' | noun phrase | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.29 |
| 냇가 / nedka | 'bank of a stream' | noun (compound) | core | — | contemporary | — | — | grammar_reference | n/a | verified | 사이시옷 (saisiot) linking-consonant example, §2.10 p.33; < 내 'stream' + 가 'side, edge' |
| 옷안 / odan | 'inside of clothes' | noun (compound) | core | — | contemporary | — | — | grammar_reference | n/a | verified | irregular 사이시옷-type compound, §2.10 p.33; < 옷(< 옫) 'clothes' + 안 'inside' |
| 빛 / bic | 'light' | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | spelling-vs-pronunciation contrast pair with 빗 'comb' (both /bid/ in isolation), §2.10 p.32 |
| 빗 / bid~bis | 'comb' | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | same pair, p.32 |
| 왜 / we | 'why?' | interrogative adverb | core | — | contemporary | — | — | grammar_reference | n/a | verified | intoneme contrast example (Low-Fall vs Rise reading), §2.8 p.30-31 |
| 가심시요 / gasibšijo | 'please go!' | verb (honorific imperative) | formal | — | contemporary | — | — | grammar_reference | n/a | verified | stress-group/intonation example, §2.8 p.31 |

**Morpheme breakdown.**

> **기다리던** = 기다리 (gidali-, "to wait for") + 더 (-dʌ-, retrospective tense suffix) + ㄴ (-n, adjectival clause ending) — full §1.4 worked example of a word's own internal morpheme composition, p.9.

> **냇가** = 내 (nɛ, "stream") + ㅅ (saisiot linking /d/, unexplainable by the general transcription rules — an irregular morphophonemic addition) + 가 (ga, "side, edge") — illustrates that 사이시옷 is not predictable from the 15 general transcription rules and must be learned per-compound, §2.10 p.33.

### Grammar points

#### 1. Morphemic vs. phonemic spelling principle (§1.2.1, p.4)

Modern Korean orthography (since the 1933 "Unified Spelling System") is morphemic: every morpheme keeps one base written form regardless of how it's actually pronounced in context. Lee's example: 목 /mog/ "neck" and 모기 /mogi/ "mosquito" are pronounced identically in some environments but spelled to reflect their different underlying morpheme shapes (목 vs 모기), not their surface pronunciation. Prior to 1933 Korean spelling was mainly phonemic. This is the same underlying mechanism later illustrated at much greater length in §2.10's transcription-rule chapter (빛/빗 pair).

#### 2. The Korean alphabet as a Prosodic-Analysis-style system (§1.2.3, p.5-6)

Lee argues the Hunminjŏngŭm/modern Hangul consonant-letter system isn't an arbitrary set of shapes but structurally parallels J.R. Firth's "Prosodic Analysis" framework: letters are organized along two independent axes — (a) five "phonematic units" (place of articulation: bilabial/alveolar/velar/post-alveolar-affricate/alveolar-fricative) and (b) up to three "prosodies" layered onto a base letter via added strokes or geminations (aspiration, glottalization, nasality). E.g. ㅂ/b/ is the phonematic-unit base; ㅍ/p/ = ㅂ + aspiration prosody; ㅃ/p̓/ = ㅂ + glottal prosody; ㅁ/m/ = ㅂ + nasal prosody. This reframes the familiar "Korean letters are iconic/systematic" observation in explicit linguistic-theory terms not found elsewhere in this corpus.

#### 3. Grammatical rank hierarchy and rank shift (§1.4, p.7-9)

Lee sets up five hierarchically ranked syntactic units for the whole book's analysis: Sentence > Clause > Phrase > Word > Morpheme (Morpheme is the only one not itself analyzable into smaller meaningful units). Each unit normally consists of one or more of the unit immediately below, but "rank shift" lets a unit bypass its expected level: **upward rank shift** — a word functions directly as a clause constituent, skipping the phrase level (his example: /jota/ "is good" standing alone as a clause's predicate); **downward rank shift** — a whole clause is embedded inside a phrase structure (his example: the adjectival clause /gidalidʌn nu:n/ "snow that I have been waiting for" functioning as a word-level adjective modifying within a nominal phrase). Recursive rank shift (a unit re-occurring within an expansion of the same unit, e.g. a phrase containing another phrase) is also diagrammed. This five-level rank scaffold and its rank-shift terminology govern the rest of the book's chapter structure (Chapters IV-VII correspond to Word, Phrase, Clause, Sentence).

#### 4. Syllable structure formula and coda restriction (§2.4, p.20-21)

Korean syllable structure is formalized as (Cⁱ) V (Cᶠ) — an optional initial consonant, an obligatory vowel/diphthong nucleus, and an optional final consonant. Any consonant may fill the initial-consonant slot except /ŋ/ and /l/, which cannot occur syllable-initially after a pause (only word-medially). Critically, **only seven consonants can occupy the final (coda) slot**: /b, d, g, m, n, ŋ, l/ — every other consonant that would otherwise end a syllable is neutralized to one of these seven in actual pronunciation (this coda-neutralization fact is the same phenomenon 013 covers under "full closure," but Lee's formal (Cⁱ)V(Cᶠ) notation and explicit 7-consonant coda inventory statement is a cleaner, more systematic restatement worth keeping as a reference point).

#### 5. Stress Group — a rhythmic unit above the syllable (§2.6, p.23)

Lee defines "Stress Group" (also "Rhythmic Unit") as the basic unit of Korean rhythm: one strongly stressed syllable, optionally preceded and/or followed by weakly stressed or unstressed syllable(s). A single utterance may consist of one, two, three, or more stress groups in sequence (examples given up to three: "하나 둘 셋" /ha'na 'du:l 'se:d/ "one, two, three" = three separate stress groups, one per number word). This concept is the foundation for his subsequent treatment of juncture and intonation (every stress group boundary coincides with a juncture boundary — plus, tentative, or terminal). No equivalent "stress group" unit was found anywhere else in the 59 prior established Korean files; it is Lee's own distinctive prosodic apparatus.

#### 6. Juncture: plus, tentative, and terminal (§2.7, p.27-29)

Three juncture types mark boundaries between stress groups, each with a different phonetic and distributional profile: **terminal juncture** (sentence-final, with the most extensive pitch excursion and usually the longest pause); **tentative juncture** (marks sub-sentence structure — clause, phrase, or word boundaries — notated with a comma in running text); **plus juncture** (the weakest boundary, notated with a space between stress groups in phonemic transcription). The plus juncture is the key diagnostic separating a phrase from a surface-identical compound word: 보리쌀 /bo'lišal/ "barley (grains)" (one compound word, no juncture) contrasts with 보리 쌀 /bo'li + šal/ "barley and rice" (a phrase, plus-juncture present) — same segments, different juncture, different meaning and grammatical status. The same test distinguishes 산길 "mountain path" (compound) from 산 길 "mountain and path" (phrase).

#### 7. Intonation: 17 attitudinal tunes reduced to 4 grammatical intonemes (§2.8-2.9, p.29-32)

Lee's intonation system (drawn from his own earlier 1964 dissertation) catalogs 17 distinct pitch-contour "tunes" realized over a stress group (falling, rising, falling-rising, rising-falling, falling-rising-falling, rising-falling-rising, and level tunes, each in low/high/full variants). Of these 17 attitudinally-distinct tunes, only **four are grammatically/syntactically relevant** and are reclassified as "Intonemes": **Intoneme LF** (Low Fall — statement-like/declarative information), **Intoneme HF** (High Fall — wh-question reading), **Intoneme R** (Rise — yes/no-question reading), **Intoneme L** (Level — incomplete/continuing). His worked example: 누가 가 /nuga.ga/ with Intoneme LF = "Someone is going" (declarative) vs. the same string with Intoneme HF = "Who is going?" (wh-question) vs. with Intoneme R = "Is anyone going?" (yes/no question) — segmentally identical sentences, disambiguated purely by which of the four intonemes is applied. This is a genuinely grammatical (not merely attitudinal/paralinguistic) use of intonation, distinct from anything else captured in this corpus so far.

#### 8. Transcription: 15 rules deriving phonemic from orthographic form, and 사이시옷 (§2.10, p.32-36)

Korean orthography is morphophonemic (base-form spelling, §1.2.1 above), while Lee's own transcription throughout the book is phonemic (actual pronunciation). §2.10 gives 15 numbered general rules for mechanically deriving the phonemic form from the written form (consonant-cluster simplification before another consonant, obstruent voicing/devoicing by environment, assimilation of nasals/liquids, palatalization of d/t before i, compound-final coda neutralization, etc. — a systematic connected-speech sandhi rule-set broadly in the same territory as 013's "Adjustments" chapter, not re-extracted rule-by-rule here). The one genuinely distinct mechanism flagged explicitly by Lee as **not** predictable from these general rules is **사이시옷 (saisiot)**, the "linking-s" phenomenon in compound nouns: an extra consonant (phonemically /d/, orthographically marked with an extra ㅅ) is inserted between the two compounding elements, e.g. 냇가 /nedka/ "bank of a stream" (< 내 "stream" + 가 "side/edge" — note also the irregular 가→ka consonant shift) and 옷안 /odan/ "inside of clothes" (< 옷/옫 "clothes" + 안 "inside," itself an irregular outcome Lee notes doesn't match what the general rules alone would predict, i.e. not */osan/*). Lee explicitly states this must be learned compound-by-compound rather than derived from a general rule.


---

## Chapter III: Word and Word Classes

**Source range:** H.B. Lee, *Korean Grammar* (Oxford University Press, 1989), Chapter III "Word and Word Classes," printed pp. 37-75 (PDF pages 27-46 of the scanned source, confirmed empirically against the visible running header/page numbers — the `PDF_page = 9 + floor(printed_page/2)` two-page-spread formula held exactly across this whole range, no non-monotonic ordering found).

**Vision-reading note.** The entire PDF has zero embedded fonts and zero text layer (confirmed via `pdffonts`/`pdftotext` — pure raster scan), so this whole chunk was vision-read from 150 DPI page renders. No cipher decode was applicable (nothing to decode — there are no font glyphs at all, just page images). No handwritten marginalia, underlining, or pencil annotation was found anywhere in this range — all pages are clean typeset print.

**Non-redundant-supplement scope decision.** Checked against `047_korean_loas_library.md` (+ `067`-`069`, Suk-Jin Chang's structural-linguistic description), `048_korean_cambridge_surveys.md`, and `019_korean_grammar_intl_learners_part2.md` for word-class-taxonomy overlap, plus the broad teaching-course corpus (001-029, 035-046) for basic lexical overlap.
- **Skipped as redundant:** the bulk of basic open-class vocabulary used purely as illustrative examples (native/Sino-Korean numerals 1-10 and their compound/ordinal forms, the core personal pronoun paradigm, common adverbial nouns like 오늘/내일/어제, common animate/inanimate noun examples) — these same items are already taught repeatedly across the teaching-course corpus. Only a representative sample is kept below, flagged `redundant-sample` in Notes, for completeness of the paradigm shape.
- **Kept as genuinely new:** Lee's own distinctive classification framework is not duplicated anywhere else in this project (no other established file uses this terminology or this exact division). Specifically kept in full: the Adjective-vs-Descriptive-Verb distinction (a narrow closed-class "true adjective" category that most teaching grammars fold into "descriptive verb" without separating); the exhaustive 21-item auxiliary verb inventory with its three-way processive/descriptive/both split; the 4-type auxiliary-verb taxonomy (plain auxiliary, post-nominal, post-adjectival, sentence auxiliary) with their full member lists; the complete 9-way particle sub-classification (subject/complement, object, agent, adverbial [directive + quotative], vocative, conjunctive [nominal + clausal], sentence, adjectival, modifying) with every named particle in each sub-class — this particle taxonomy, especially the 12-item directive-particle set, the 11-item modifying-particle set, and the 2-item sentence-particle set, is more systematically complete than any prior Korean established file; the honorific/plain noun pairing system (paired table); the classifier inventory; the animate/inanimate noun test (the `ege`/`e` directive-particle collocation diagnostic); and the adverb sub-classification (processive/descriptive/processive-descriptive/interrogative/sentence/conjunctive), which is a finer-grained split than the teaching-grammar corpus's usual flat "adverb" treatment.

---

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 새 se | 'new' | adjective (true, pre-nominal only) | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | p.59; member of the small closed "qualitative adjective" class, distinct from descriptive verbs like 길다 'to be long' |
| 헌 hʌn | 'old, worn out' | adjective (true, pre-nominal only) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.59 |
| 온 on | 'entire, whole' | adjective (true, pre-nominal only) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.59 |
| 외 we | 'only, lone' | adjective (true, pre-nominal only) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.59 |
| 이 i | 'this' | adjective (deictic) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.60; proximate to speaker(s); doubles as a pronoun |
| 그 gi | 'that' | adjective (deictic) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.60; proximate to listener(s) or absent from discourse scene; doubles as pronoun meaning 'he, she' |
| 저 jʌ | 'that (yonder)' | adjective (deictic) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.60; remote from both speaker(s) and listener(s) |
| 어느/어떤 ʌni/ʌttʌn | 'which' (interrog.) / 'some, certain' (non-interrog.) | adjective (interrogative) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.61; dual meaning depending on sentence type |
| 무슨 musin | 'what' (interrog.) / 'some, certain' (non-interrog.) | adjective (interrogative) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.61 |
| 웬 wen | 'what kind of' (interrog.) / 'some, certain' (non-interrog.) | adjective (interrogative) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.61 |
| 어떤 ʌttʌn | 'what sort of' (interrog.) / 'some sort of' (non-interrog.) | adjective (interrogative) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.61; distinct second entry alongside 어느/어떤 pairing on same page |
| 한 han | 'one' | numeral adjective | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.59; positionally free (can precede another adjective) |
| 두 du | 'two' | numeral adjective | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.59 |
| 세/서/석 se/sʌ/sʌk | 'three' | numeral adjective | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.59; three collocational alternants — sʌ with mal/dwe 'measure' nouns, sʌk with jan/sam 'cup/sack' nouns, se elsewhere |
| 네/너/넉 ne/nʌ/nʌk | 'four' | numeral adjective | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.59; same 3-way collocational split as se/sʌ/sʌk |
| 닷 das | 'five' | numeral adjective | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.59; restricted to collocating with mal/dwe only |
| 엿 jʌs | 'six' | numeral adjective | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.59; restricted to collocating with mal/dwe only |
| 첫 cʌs | 'first' | numeral adjective | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.59; irregular ordinal-like member of the numeral adjective sub-class |
| 하나-열 (1-10) | native Korean cardinal numerals | numeral (noun) | core | — | contemporary | — | — | grammar_reference | n/a | verified | pp.50-51; redundant-sample — full paradigm already covered extensively in teaching-course corpus |
| 일-십 (1-10) | Sino-Korean cardinal numerals | numeral (noun) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.51; redundant-sample |
| 나/내 na/ne | 'I' (plain) | pronoun (1st person) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.53; redundant-sample — ne is the alternant before particle ga |
| 저/제 jʌ/je | 'I' (formal/humble) | pronoun (1st person) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.53; redundant-sample |
| 너/네 nʌ/ne | 'you' (low plain) | pronoun (2nd person) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.53; redundant-sample |
| 당신 dansin | 'you' (low formal) | pronoun (2nd person) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.53; redundant-sample |
| 이분/그분/저분 ibun/gibun/jʌbun | 'he, she, this/that person' (polite) | pronoun (3rd person, honorific) | formal | — | contemporary | — | — | grammar_reference | n/a | verified | p.53 |
| 이이/그이/저이 i i/gi i/jʌ i | 'he, she, this/that person' (plain) | pronoun (3rd person) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.53 |
| 누/누구 nu/nugu | 'who' (interrog.) / 'someone' (non-interrog.) | noun (interrogative) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.54 |
| 무엇(무어/뭐) muʌ(s) | 'what' (interrog.) / 'something' (non-interrog.) | noun (interrogative) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.54 |
| 몇 mjʌc | 'how many' (interrog.) / 'a few, several' (non-interrog.) | noun (interrogative) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.54 |
| 언제 ʌnje | 'when' (interrog.) / 'sometimes' (non-interrog.) | noun (interrogative, also adverbial) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.54; dual-class member of both interrogative and adverbial noun sub-classes |
| 오늘/내일/어제 onil/neil/ʌje | 'today/tomorrow/yesterday' | noun (adverbial) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.54; redundant-sample |
| 지금/여기/거기 jigim/jʌgi/gʌgi | 'now/here/there' | noun (adverbial) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.54; redundant-sample |
| 마리 mali | classifier: '[head(s) of] animal' | noun (classifier, non-independent) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.55; agreement-restricted to animal-referent nouns only |
| 장 jaŋ | classifier: '[sheet(s) of] paper' | noun (classifier, non-independent) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.55 |
| 권 gwʌn | classifier: '[volume(s) of] book(s)' | noun (classifier, non-independent) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.55 |
| 그루 gilu | classifier: '[number of] trees' | noun (classifier, non-independent) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.55 |
| 대 de | classifier: '[a set of] machines' | noun (classifier, non-independent) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.55 |
| 명 mjʌŋ | classifier: '[number of] person(s)' | noun (classifier, non-independent) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.55 |
| 것 gʌs | 'thing' | noun (post-modifier, non-independent) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.55; combines with preceding adjectival clause |
| 줄 jul | 'ability, guess, the fact that' | noun (post-modifier, non-independent) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.56; two distinct senses depending on which adjectival-clause ending precedes it |
| 때문 tʼemun | 'reason, because of' | noun (post-modifier, non-independent) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.55 |
| 만큼/만치 mankim/manci | 'as (much) as' | noun (post-modifier, non-independent) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.55 |
| 말씀 malsim : 말 mal | 'word, speech' — honorific : plain pair | noun (honorific/plain pair) | formal / core | — | contemporary | — | — | grammar_reference | n/a | verified | p.57; honorific nouns lexically concord with honorific verbs |
| 진지 jinji : 밥 bab | 'meal, food' — honorific : plain pair | noun (honorific/plain pair) | formal / core | — | contemporary | — | — | grammar_reference | n/a | verified | p.57 |
| 성함 saŋham : 이름 ilim | 'name' — honorific : plain pair | noun (honorific/plain pair) | formal / core | — | contemporary | — | — | grammar_reference | n/a | verified | p.58 |
| 옥체 ogce : 몸 mom | 'body' — honorific : plain pair | noun (honorific/plain pair) | formal / core | — | contemporary | — | — | grammar_reference | n/a | verified | p.58 |
| 아버님 abʌnim : 아버지 abaji | 'father' — honorific : plain pair | noun (honorific/plain pair) | formal / core | — | contemporary | — | — | grammar_reference | n/a | verified | p.58 |
| 할머님 halmʌnim : 할머니 halmani | 'grandmother' — honorific : plain pair | noun (honorific/plain pair) | formal / core | — | contemporary | — | — | grammar_reference | n/a | verified | p.58 |
| 하느님 hanɨnim | 'god' | noun (honorific) | formal | — | contemporary | — | — | grammar_reference | n/a | verified | p.57 |
| 좋- jo- | 'to be good' | descriptive verb (V.d.) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.42; illustrates descriptive-verb sub-class, not a "true adjective" in Lee's framework |
| 길- gil- | 'to be long' | descriptive verb (V.d.) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.42 |
| 젊- jʌlm- | 'to be young' | descriptive verb (V.d.) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.43 |
| 밝- balg- | '(a) to dawn, become bright (V.p.) / (b) to be bright (V.d.)' | verb (dual processive/descriptive) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.43; one of 5 verbs Lee lists as behaving as both processive and descriptive |
| 늦- nij- | '(a) to become late (V.p.) / (b) to be late (V.d.)' | verb (dual processive/descriptive) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.43 |
| 크- ki- | '(a) to grow (V.p.) / (b) to be big (V.d.)' | verb (dual processive/descriptive) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.43 |
| 있- is- | '(a) to stay (V.p.) / (b) to be, to exist (V.d.)' | verb (dual processive/descriptive) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.43 |
| 계시- gesi- | '(a) to stay (V.p.) / (b) to be, to exist (V.d.)' — honorific of 있- | verb (dual processive/descriptive, honorific) | formal | — | contemporary | — | — | grammar_reference | n/a | verified | p.43 |
| 잡수시- jabsusi- : 먹- mʌg- | 'to eat' — honorific : plain pair | verb (honorific/plain pair) | formal / core | — | contemporary | — | — | grammar_reference | n/a | verified | p.44 |
| 주무시- jumusi- : 자- ja- | 'to sleep' — honorific : plain pair | verb (honorific/plain pair) | formal / core | — | contemporary | — | — | grammar_reference | n/a | verified | p.44 |
| 보 bo- | 'to try [doing]' | auxiliary verb (processive) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.45; #1 of Lee's 21-item auxiliary verb list; also doubles as full verb 'to see' |
| 주 ju- | 'to do something as a favour' | auxiliary verb (processive) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.45; #2 |
| 드리 dili- | honorific counterpart of 주- | auxiliary verb (processive, honorific) | formal | — | contemporary | — | — | grammar_reference | n/a | verified | p.46; #3 |
| 대 de- | '[action/event] repetition' | auxiliary verb (processive) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.46; #4 |
| 쌓 sah- | 'repetition, continuation' | auxiliary verb (processive) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.46; #5 |
| 버리 bʌli- | '[to do something] completely or thoroughly' | auxiliary verb (processive) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.46; #6; also doubles as full verb 'to throw' |
| 지 ji- | '(a) passive voice [after V.tr.] / (b) unintentional [after V.intr.] / (c) progression or becoming [after V.d.]' | auxiliary verb (processive, voice formative) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.46; #7; also doubles as full verb 'to wither or fall' |
| 되 dwe- | '(a) unintentional [after V.p.] / (b) "to become" [after V.d.]' | auxiliary verb (processive) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.46; #8 |
| 가 ga- | '(a) progression toward a goal/future or away from speaker / (b) near-completion' | auxiliary verb (processive) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.46; #9; also doubles as full verb 'to go' |
| 오 o- | 'progression toward a goal from past to present or toward the speaker' | auxiliary verb (processive) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.46; #10 |
| 놓 noh- | 'completion, retention' | auxiliary verb (processive) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.46; #11; also doubles as full verb 'to place/put down' |
| 나 na- | 'progression, completion' (intransitive) | auxiliary verb (processive) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.46; #12 |
| 내 ne- | 'progression, completion' (transitive) | auxiliary verb (processive) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.46; #13 |
| 두 du- | 'retention, preservation' | auxiliary verb (processive) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.46; #14 |
| 하 ha- | '(a) causative [after V.p.] / (b) causative + processive [after V.d.]' | auxiliary verb (processive, causative formative) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.46; #15 |
| 만들 mandil- | same function as 하- | auxiliary verb (processive, causative formative) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.46; #16 |
| 있 is- | '(a) retention / (b) progressive tense formative [after V.p.]' | auxiliary verb (descriptive) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.46; #17 |
| 싶 sip- | 'to want to, to wish to' | auxiliary verb (descriptive) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.46; #18 |
| 아니하 aniha- | negation | auxiliary verb (processive & descriptive) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.46; #19 |
| 못하 mosha- | 'negation, to be unable to' | auxiliary verb (processive & descriptive) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.46; #20 |
| 말 mal- | negation in imperative/propositive sentences only | auxiliary verb (processive & descriptive) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.46; #21, the full list of 21 ends here |
| 직하 jigha- | 'is likely to, is worth [doing]' | auxiliary verb (post-nominal, descriptive) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.47; always preceded by a nominal clause in -m/-im with a processive predicate |
| 하 ha- (post-nominal) | 'admission or recognition of the preceding action/event' | auxiliary verb (post-nominal) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.48; always preceded by a -gi nominal clause |
| 듯하 disha- | 'to seem or appear' | auxiliary verb (post-adjectival, descriptive) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.49 |
| 만하 manha- | 'to be worth [doing]' | auxiliary verb (post-adjectival, descriptive) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.49 |
| 법하 bʌbha- | 'to be likely to' | auxiliary verb (post-adjectival, descriptive) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.49 |
| 양하 janha- | 'pretending to' | auxiliary verb (post-adjectival, processive) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.49 |
| 척하/체하 cʌgha-/ceha- | 'pretending to' | auxiliary verb (post-adjectival, processive) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.49; two free variants for one meaning |
| 번하 bʌnha- | 'nearly [did]' | auxiliary verb (post-adjectival, processive) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.49 |
| 싶 sip- (sentence aux.) | presumption, conjecture | auxiliary verb (sentence auxiliary) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.49; occurs only after a final interrogative clause ending in -ninga/-na/-lka |
| 보 bo- (sentence aux.) | presumption, conjecture | auxiliary verb (sentence auxiliary) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.49; identical in form to the processive auxiliary bo- but a distinct functional item |
| 잘 jal | 'well, nicely' | adverb (processive, Adv.p.) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.62 |
| 천천히 cancanhi | 'slowly' | adverb (processive, Adv.p.) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.62 |
| 얼른 ʌllin | 'quickly' | adverb (processive, Adv.p.) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.62 |
| 매우 meu | 'very' | adverb (descriptive, Adv.d.) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.62 |
| 대단히 dedanhi | 'very, greatly' | adverb (descriptive, Adv.d.) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.62 |
| 참 cam | 'extremely, very' | adverb (descriptive, Adv.d.) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.62 |
| 가장 gajaŋ | 'most' | adverb (descriptive, Adv.d.) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.62 |
| 너무 namu | 'too much' (Adv.p.) / 'too...' (Adv.d.) | adverb (processive-descriptive, Adv.pd.) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.63; dual meaning by syntactic position, a Lee-specific sub-class not flagged in the teaching-grammar corpus |
| 굉장히 gwenjaŋhi | 'very much' (Adv.p.) / 'very...' (Adv.d.) | adverb (processive-descriptive, Adv.pd.) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.63 |
| 아주 aju | 'for good, definitely, completely' (Adv.p.) / 'very, extremely' (Adv.d.) | adverb (processive-descriptive, Adv.pd.) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.63 |
| 상당히 saŋdaŋhi | 'remarkably/fairly much' (Adv.p.) / 'quite, fairly' (Adv.d.) | adverb (processive-descriptive, Adv.pd.) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.63 |
| 확실히 hwagsilhi | 'definitely, clearly' | adverb (processive-descriptive, Adv.pd.) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.63 |
| 왜 we | 'why' (interrog.) / 'by the way, as you know' (non-interrog.) | adverb (interrogative) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.63; dual meaning |
| 어떻게 ʌttʌke | 'how' (interrog.) / 'somehow' (non-interrog.) | adverb (interrogative) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.63 |
| 그러나 gilʌna | 'but, however' | adverb (sentence, Adv.z.) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.64 |
| 또 to | 'and, furthermore' | adverb (sentence, Adv.z.) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.64 |
| 그러니 gilani | 'therefore' | adverb (sentence, Adv.z.) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.64 |
| 더구나 dʌguna | 'furthermore, on top of that' | adverb (sentence, Adv.z.) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.64 |
| 하물며 hamilmjʌ | 'furthermore, in spite of that' | adverb (sentence, Adv.z.) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.64 |
| 아니 ani | 'by the way, why' | adverb (sentence, Adv.z.) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.64; also doubles as a vocative-phrase-initial filler in example on p.69 |
| 그리고 giligo | 'and' / 'afterward' | adverb (conjunctive, Adv.conj.) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.64 |
| 또는 tonin | 'or' | adverb (conjunctive, Adv.conj.) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.64 |
| 곧 god | 'namely, in other words' | adverb (conjunctive, Adv.conj.) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.64 |
| 가/이 ga/i | subject/complement marker | particle (subject/complement, V/C-form) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.65; the two allomorphs split by vowel-final/consonant-final host |
| 께서 kesʌ | honorific main-subject marker | particle (subject/complement, honorific) | formal | — | contemporary | — | — | grammar_reference | n/a | verified | p.66 |
| 에서 esʌ | subject marker for institutional/group inanimate nouns | particle (subject/complement) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.66; e.g. after hwesa 'company', haggjo 'school' |
| 를/을 lil/il | object marker | particle (object, V/C-form) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.66 |
| 에 e | agent marker after inanimate noun | particle (agent) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.66; marks Agent in passive/causative clauses |
| 에게 ege | agent marker after animate noun | particle (agent) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.66 |
| 한테 hante | agent marker after animate noun, colloquial | particle (agent) | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | p.66 |
| 께 ke | agent marker after animate honorific noun | particle (agent, honorific) | formal | — | contemporary | — | — | grammar_reference | n/a | verified | p.66 |
| 에/에게/한테/께 e/ege/hante/ke | 'to, toward' (directive particle set #1) | particle (adverbial, directive) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.67; same four forms double as agent particles |
| (에)서 (e)sʌ | 'at, from' after inanimate noun (directive #2) | particle (adverbial, directive) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.67 |
| 에게서 egesʌ | 'from' after animate noun (directive #3) | particle (adverbial, directive) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.67 |
| 한테서 hantesʌ | 'from' after animate noun, colloquial (directive #4) | particle (adverbial, directive) | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | p.68 |
| 로/으로 lo/ilo | 'to, toward, as, with, by' after inanimate noun (directive #5) | particle (adverbial, directive, V/C-form) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.68 |
| 에게로 egelo | 'to, toward' after animate noun (directive #6) | particle (adverbial, directive) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.68 |
| 한테로 hantelo | 'to, toward' after animate noun, colloquial (directive #7) | particle (adverbial, directive) | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | p.68 |
| 로서/으로서 losʌ/ilosʌ | 'as' after animate noun (directive #8) | particle (adverbial, directive, V/C-form) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.68 |
| 로써/으로써 losǒ/ilosǒ | 'with, by' after inanimate noun (directive #8b) | particle (adverbial, directive, V/C-form) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.68 |
| 와/과 wa/gwa | 'with' (directive #9) | particle (adverbial, directive, V/C-form) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.68; same form reused as nominal conjunctive particle (3.4.5.6.1) |
| 하고 hago | 'with', colloquial (directive #10) | particle (adverbial, directive) | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | p.68; same form reused as nominal conjunctive particle |
| 처럼 cʌlʌm | 'as, like' (directive #11) | particle (adverbial, directive) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.68 |
| 보다 boda | 'than' (directive #12) | particle (adverbial, directive) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.68 |
| 라고 lago | quotative particle after a vowel-final quotation (not ending in /a/) | particle (adverbial, quotative) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.69 |
| 이라고 ilago | quotative particle after a consonant-final quotation | particle (adverbial, quotative) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.69 |
| 고 go | quotative particle after a clause/sentence ending in /a/ | particle (adverbial, quotative) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.69 |
| 야/아 ja/a | vocative particle, low plain style | particle (vocative, V/C-form) | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | p.69 |
| 여/이여 jʌ/ijʌ | vocative particle, formal style | particle (vocative, V/C-form) | formal | — | contemporary | — | — | grammar_reference | n/a | verified | p.69 |
| 와/과 wa/gwa (conj.) | nominal conjunctive particle, 'and' | particle (conjunctive, nominal, V/C-form) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.70; coordinates nouns/NPs only, distinct distribution from the homophonous directive particle |
| 나/이나 na/ina | nominal conjunctive particle, 'or' | particle (conjunctive, nominal, V/C-form) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.70 |
| 만(은) man(in) | clausal conjunctive particle, 'although, but' | particle (conjunctive, clausal) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.70 |
| 시피 sipi | clausal conjunctive particle, 'as' | particle (conjunctive, clausal) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.71; restricted to a few processive verbs (알-, 모르-, 느끼-, 듣-, 보-, 짐작하-) in low plain declarative, neutral present tense only |
| 그려 giljʌ | sentence particle, exclamator | particle (sentence) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.71; occurs only after a major sentence, renders it exclamatory |
| 요 jo | sentence particle, speech-style modulator | particle (sentence) | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | p.71; elevates medium/high-plain endings to low-formal style; also occurs mid-sentence after S/O/P, especially in women's speech |
| 의 ii | 'of' | particle (adjectival) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.73; only member of the adjectival-particle sub-class |
| 는/은 nin/in | emphasis, contrast | particle (modifying, V/C-form) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.73 |
| 만 man | 'only, solely' | particle (modifying) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.73 |
| 도 do | 'also, too, as well' | particle (modifying) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.74 |
| 마다 mada | 'every, each' | particle (modifying) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.74 |
| 부터 butʌ | 'first, from, beginning with' | particle (modifying) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.74 |
| 까지 kaji | 'even, as far as' | particle (modifying) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.74 |
| 조차 joca | 'even, up to' | particle (modifying) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.74 |
| 야말로/이야말로 jamallo/ijamallo | 'as for, in particular' | particle (modifying, V/C-form) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.74 |
| 라도/이라도 lado/ilado | 'for lack of anything better, even though unsatisfactory' | particle (modifying, V/C-form) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.74 |
| 나/이나 na/ina (modifying) | 'even though unsatisfactory, as much/many as' | particle (modifying, V/C-form) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.75; same surface form as the nominal conjunctive particle but a distinct modifying-particle item |
| 든지/이든지 dinji/idinji | 'any, no matter what' | particle (modifying, V/C-form) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.75 |
| 네 ne | 'Yes' (formal style) | interjection (response) | formal | — | contemporary | — | — | grammar_reference | n/a | verified | p.75 |
| 그래 gilɛ | 'Yes' (plain style) | interjection (response) | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | p.75 |
| 글쎄 gilse | 'well, presumably, possibly' | interjection (response) | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | p.75 |
| 어 ʌ | 'er' (hesitation filler) | interjection (response) | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | p.75 |
| 응 iŋ | 'yes, that's right; really, is that so?' | interjection (response) | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | p.75; three phonetic variants given: [ɯŋ]/[ɯ̃ŋ]/[ɯ̃] |
| 무어 mwʌ | 'what!?' | interjection (response) | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | p.75 |
| 허허 hʌhʌ | 'ha ha' (laughter, pleasure or pity) | interjection (response) | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | p.75 |
| 음 im | 'mm, yes' | interjection (response) | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | p.75 |
| 흠 him | 'hum' (distaste, sneer) | interjection (response) | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | p.75; explicitly glossed as an expression of distaste/sneer — a register-marked affective interjection |
| 아 a | 'Ah!' | interjection (introductory) | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | p.75 |
| 아이구 aigu | 'Oh!, Ouch!, Goodness!' | interjection (introductory) | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | p.75 |
| 자 ja | 'Well, now!' | interjection (introductory) | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | p.75 |
| 쉬 swi | 'Hush!' | interjection (introductory) | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | p.75 |
| 야/허 ja/hja | 'Hey!' | interjection (introductory) | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | p.75 |
| 여보 jʌbo | 'Hey, you!' | interjection (introductory) | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | p.75 |
| 여보세요 jʌbosejo | 'Hello, you!' | interjection (introductory) | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | p.75 |

### Grammar points

#### 3.1 Definition of word (three-criterion test)

Lee defines "word" by three joint criteria rather than a single test: (i) relative fixity of internal structure (morpheme order within a word cannot be rearranged, no intra-morphemic interruption by other forms/junctures is possible), (ii) freedom of positional mobility (illustrated with a single verb, 가다 'to go,' shown functioning as sentence predicate, non-final clause, adjectival clause, and nominal clause without changing form beyond its own inflection), and (iii) independence (any word may stand alone as a minor sentence, preceded/followed by terminal juncture — except adjectives and particles, which rarely occur alone, p.38). A supplementary phonological criterion (stress on one of the first two syllables in citation form) is noted but explicitly downgraded to merely "supplementary," since stress is inconsistent in connected speech (p.39).

#### 3.2 Simple vs. compound words

A simple word consists of a single free morpheme (with or without bound morphemes); a compound word consists of more than one free morpheme uninterrupted by juncture at the morpheme boundary, e.g. 나팔꽃 napalkod 'morning-glory' < napal 'bugle' + kod 'flower' (p.39). Three-or-more-morpheme compounds are noted as rare, e.g. 여우꼬리풀 jʌukolipul (a plant species name) < jʌu 'fox' + koli 'tail' + pul 'plant, grass' (p.39).

#### 3.3 The six word classes and the inflected/uninflected split

Six word classes are set up: Verb, Noun, Adjective, Adverb, Particle, Interjection — of which only Verb is inflected; the other five are uninflected (p.39). The class-defining tests are purely distributional (what a word may precede/follow), not semantic.

#### 3.3.3/3.4.3 — the Adjective vs. Descriptive-Verb split (standout finding)

This is the chapter's most theoretically distinctive point relative to every other Korean source in this project's corpus. Lee's "Adjective" class word is defined narrowly: a word that *exclusively* precedes a noun or another adjective, never occurs alone, and forms "a very small class" (p.40) — e.g. 새 se 'new', 헌 hʌn 'old', 어느 ʌni 'which'. This excludes the large set of predicative "descriptive" meanings (e.g. 길다 gilda 'to be long', 좋다 jota 'to be good') that most teaching grammars in this project's corpus simply call "adjectives" or "descriptive verbs" without separately flagging a true closed-class pre-nominal adjective category — Lee classifies those predicative items as verb sub-class V.d. (Descriptive Verb), not as Adjective at all. The Adjective class itself then sub-divides into four closed sub-classes (3.4.3): Numeral Adjectives, Deictic Adjectives (이/그/저, a 3-way proximate-to-speaker / proximate-to-listener / remote-from-both system), Interrogative Adjectives, and Qualitative Adjectives (a residual small set: 새/헌/온/외).

#### 3.4.1.1 Processive vs. descriptive verbs

Verbs are classified as processive (inflectable for imperative/propositive mood, suffixable by the -n/-nin- present tense suffix) or descriptive (neither of these). A handful of verbs genuinely behave as both, taking on two related but distinct meanings depending on which function they're used in (e.g. 밝- balg- '(a) to dawn, become bright' as V.p. vs. '(b) to be bright' as V.d., p.43) — Lee lists exactly five such dual-behavior verbs: 밝-, 늦-, 크-, 있-, 계시-.

#### 3.4.1.2 Transitive vs. intransitive verbs (alternative cross-classification)

As a second, independent cross-classification, verbs split into transitive (can take an object, lends itself to passive formation) and intransitive (cannot). Lee states the correlation explicitly: all transitive verbs are processive, but intransitive verbs may be either processive or descriptive; conversely, descriptive verbs are always intransitive (p.50) — a clean implicational hierarchy not spelled out this explicitly in the other Korean established files checked.

#### 3.4.1.3 Full vs. auxiliary verbs, and the four-way auxiliary typology

Verbs cross-classify a third way into Full (can stand alone as a sentence) vs. Auxiliary (requires a preceding full verb or other element). Lee then subdivides auxiliary verbs into four distinct functional types based on what they attach after: (i) plain Auxiliary Verbs (after a verb in concatenating form — the ordinary V+V auxiliary construction, 21 members listed exhaustively, see Vocabulary table), (ii) Post-nominal Auxiliary Verbs (only after a nominal phrase/clause — 직하- 'worth doing', 하- 'admission/recognition'), (iii) Post-adjectival Auxiliary Verbs (only after an adjectival clause — 듯하-, 만하-, 법하-, 양하-, 척하-/체하-, 번하-), and (iv) Sentence Auxiliary Verbs (only after a final clause — 싶- and 보-, both restricted to following specific interrogative-ending final clauses, expressing presumption/conjecture). Several auxiliary verbs are noted as formally identical to full verbs but functionally/distributionally distinct (지-, 보-, 버리-, 놓-, 가- each have both a full-verb and an auxiliary-verb reading, p.47) — a point worth flagging for mechanics analysis since this is exactly the kind of grammaticalization pathway (full verb > auxiliary > bound suffix) that can seed slang/informal-register extensions.

#### 3.4.2 Noun sub-classification: independent/non-independent, animate/inanimate, honorific/plain

Independent nouns (the majority) can stand alone as a sentence; non-independent nouns (classifiers, post-modifiers) cannot. A clean distributional diagnostic is given for the animate/inanimate split: animate nouns collocate with the directive particle allomorph 에게 ege, inanimate nouns with 에 e (p.56) — a testable syntactic criterion rather than a semantic one. Honorific nouns are defined as those that lexically concord with honorific verbs when the noun is subject/object of a sentence; Lee notes this concord is "not as binding" as grammatical agreement in European languages — it's a usage tendency, not an obligatory rule, and a plain noun can still take an honorific verb when the speaker wants to show respect for extralinguistic reasons (p.58).

#### 3.4.5 The nine-way particle sub-classification

Particles — Lee's term for what other sources often call postpositions/case markers — are exhaustively divided into nine functional sub-classes: Subject/Complement, Object, Agent, Adverbial (itself split into Directive, with 12 enumerated members, and Quotative, with 3 members), Vocative, Conjunctive (split into Nominal, coordinating nouns/NPs, and Clausal, subordinating two final clauses), Sentence (2 members: 그려 'exclamator' and 요 'speech-style modulator'), Adjectival (1 member: 의 'of'), and Modifying (11 enumerated members covering emphasis/contrast, exclusivity, inclusivity, distributivity, starting-point, endpoint, concession, and free-choice meanings). Several particle forms are explicitly noted as homophonous-but-distinct across sub-classes — e.g. 와/과 and 하고 serve as both Directive ('with') and Nominal Conjunctive ('and') particles with different distributions; 나/이나 serves as both Nominal Conjunctive ('or') and Modifying ('even though unsatisfactory') particles (pp.68, 70, 75) — a systematic homophony pattern worth flagging for mechanics analysis as a likely source of historical particle-grammaticalization splits.

#### 3.4.6 Interjection sub-classification: response vs. introductory

Interjections split into Response Interjections (reference the preceding sentence/context — includes the register-marked 흠 him 'hum', explicitly glossed by Lee as expressing "distaste, sneer") and Introductory Interjections (initiate a new sentence with no backward reference, e.g. 아이구 aigu, 쉬 swi, 여보 jʌbo).


---

## Chapter IV: Structure of the Verb

**Source:** H.B. Lee, *Korean Grammar* (Oxford reference grammar, Professor of Phonetics and Linguistics, Seoul National University). Chapter IV "Structure of the Verb," printed pp. 76–111 (PDF pages 47–64 of 117). Whole-book Attested Era: contemporary (source published 1989 — Preface/copy details not independently dated beyond the book's own internal era framing; treated per spec as "contemporary (source published 1989)" pending confirmation from another chunk's title-page read).

**Text layer / vision-reading note:** Confirmed via `pdffonts` and `pdftotext`: this PDF has **zero embedded fonts and zero text layer whatsoever** — a pure raster scan, not a font-substitution cipher (no fonts exist to decode). All content in this chunk was vision-read from 150 DPI page renders. Each PDF page is a two-printed-page spread; printed pp. 76–111 map to PDF pages 47–64 (confirmed empirically against the printed page numbers and chapter headers visible on the rendered pages, not assumed from arithmetic alone — boundaries were visually verified against the Chapter III→IV transition at PDF p.47 and the Chapter IV→V transition at PDF p.65). **No handwritten marginalia was found anywhere in this range** — all pages are clean typeset print.

**Coverage note — non-redundant-supplement scope decision.** This chapter (verb-suffix structure: voice, honorific, tense, humble suffixes, and all three classes of inflectional ending) is the single highest topical-overlap chunk in the whole book, since honorific/tense/causative-passive/stem-class territory is already covered by several dedicated prior extractions. Checked against:
- `031_korean_honorifics_and_politeness.md` (Lucien Brown, 329pp dedicated academic treatment) — **§4.3.2 Honorific Suffix is skipped as substantially redundant**; only a one-line structural note is kept (Lee's chapter cross-references the Final Endings paradigm below, which is new).
- `051_tense_and_aspect_in_korean.md` (194pp dedicated treatment) — **§4.3.3 Tense Suffixes' discursive 11-subtype direct-tense / 7-subtype retrospective-tense exposition is skipped as redundant**; only the compact suffix-morpheme inventory is kept below (the five tense-suffix morphemes themselves, not the full discursive tense-category taxonomy, since a bare morpheme table is not the kind of content a dedicated tense/aspect monograph would omit, but the full discursive treatment plausibly is already covered there in more depth).
- `047_korean_loas_library.md`/`067`/`068`/`069` (Chang, LOALL) and `052_korean_semantic_pragmatic_grammar.md` — checked for voice/causative/passive and stem-class overlap; these are theoretical treatments but at a different grain (word-formation/compounding typology rather than Lee's own V-stem/C-stem phonologically-conditioned-allomorph classification). **Kept**: Lee's full systematic stem-class typology (§4.2) was not found duplicated at this level of systematicity in 047/067-069 or 052.
- `049_history_of_korean_language.md`/`053` — checked for humble-suffix historical treatment; that material is historical/diachronic, Lee's §4.3.4 is synchronic/structural with explicit social-register example sentences (child-to-teacher vs. child-to-friend), so **kept as distinct**.

**Kept as genuinely new:** the full V-stem/C-stem phonologically-conditioned stem-class typology with its irregular-verb subclasses (§4.2 — i-dropping, u-dropping, l-doubling, l-dropping, s-dropping, d-final, b-final, ha-stem coalescence) and the derivational "class-maintaining" verb-prefix set (confirmed via corpus grep: no prior file documents this prefix set); the passive/causative voice-suffix phonological-conditioning-environment paradigm (§4.3.1, fuller than typical teaching-grammar treatment); the humble-suffix system with its explicit social-register examples (§4.3.4); the complete Final-Endings paradigm — five speech styles × four moods, each cell's exact morpheme (§4.3.5.1, a single systematic table not found assembled this way elsewhere in the corpus); the Non-Final Endings (nominal/adjectival/adverbial clause endings) and the four Concatenating Endings, which is Lee's own distinctive category (confirmed via corpus grep: "concatenating ending"/"satellite" terminology does not appear in any prior extraction); and the 21-item numbered adverbial-clause-ending (connective-ending) inventory, a genuinely valuable systematic connective list not assembled this completely in any prior Korean established file. **Skipped as redundant:** the discursive tense-category taxonomy (§4.3.3 body text) and the Honorific Suffix section body (§4.3.2).

---

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 짓 jis- | 'at random, violently' | derivational prefix | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | class-maintaining verb prefix; e.g. 짓밟 jidbab- 'to trample down' < jis- + balb- 'to stamp on'. p.77 |
| 엿 jʌs- | 'secretly' | derivational prefix | core | — | contemporary | — | — | grammar_reference | n/a | verified | e.g. 엿듣 jʌdtid- 'to overhear' < jʌs- + did- 'to hear'. p.77 |
| 시 si- | 'deep, very' | derivational prefix | core | — | contemporary | — | — | grammar_reference | n/a | verified | e.g. 시퍼렇 sipʌlʌ- 'deep blue' < si- + pʌlʌh- 'blue'. p.77 |
| 올 ol- | 'early' | derivational prefix | core | — | contemporary | — | — | grammar_reference | n/a | verified | e.g. 올되 oldwe- 'to be precocious' < ol- + dwe- 'to become'. p.77 |
| 치 ci- | 'up, upward' | derivational prefix | core | — | contemporary | — | — | grammar_reference | n/a | verified | e.g. 치밀 cimil- 'to push up, to well up' < ci- + mil- 'to push'. p.77 |
| 보살피 bosalpi- | 'to look after' | verb (compound stem) | core | — | contemporary | — | — | grammar_reference | n/a | verified | compound stem < bo- 'to see' + salpi- 'to observe'. p.78 |
| 오가 oga- | 'to come and go' | verb (compound stem) | core | — | contemporary | — | — | grammar_reference | n/a | verified | < o- 'to come' + ga- 'to go'. p.78 |
| 검붉 gʌmbulg- | 'to be dark red' | verb (compound stem) | core | — | contemporary | — | — | grammar_reference | n/a | verified | < gʌm- 'dark' + bulg- 'red'. p.78 |
| 붙잡 butjab- | 'to grab' | verb (compound stem) | core | — | contemporary | — | — | grammar_reference | n/a | verified | < but- 'to stick' + jab- 'to catch'. p.78 |
| 잠그 jamgi- | 'to lock' | verb (irregular: i-dropping V-stem) | core | — | contemporary | — | — | grammar_reference | n/a | verified | i-less allomorph before ʌ-initial suffix. p.79 |
| 쓰 sɨ- | 'to use or write' | verb (irregular: i-dropping V-stem) | core | — | contemporary | — | — | grammar_reference | n/a | verified | e.g. 써도 sʌdo 'even if you write' < sɨ- + -ʌdo. p.79 |
| 크 ki- | 'to grow, to be big' | verb (irregular: i-dropping V-stem) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.79 |
| 이르 ili- | 'to arrive or reach' | verb (irregular: l-doubling V-stem) | core | — | contemporary | — | — | grammar_reference | n/a | verified | ll-final allomorph before ʌ-initial suffix: 이르러 ililʌ 'on arriving'. p.80 |
| 부르 buli- | 'to call' | verb (irregular: l-doubling V-stem) | core | — | contemporary | — | — | grammar_reference | n/a | verified | 불러라 bullala 'Call [him].' p.80 |
| 호르 hili- | 'to flow' | verb (irregular: l-doubling V-stem) | core | — | contemporary | — | — | grammar_reference | n/a | plausible_unverified | listed form; small print. p.80 |
| 가르 gali- | 'to divide' | verb (irregular: l-doubling V-stem) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.80 |
| 푸 pu- | 'to draw (water)' | verb (irregular: u-dropping V-stem) | core | — | contemporary | — | — | grammar_reference | n/a | verified | only verb of this type per the source; 퍼라 pʌla 'Draw!' < pi-/pu- + -ʌla. p.80 |
| 하 ha- | 'to do, to say' | verb (irregular: ha-stem) | core | — | contemporary | — | — | grammar_reference | n/a | verified | allomorph hʌj- before a/ʌ-initial suffixes, colloquial coalescence hʌjʌ > hɛ. p.80-81 |
| 되 dwe- | 'to become' | verb (irregular: ha-adjacent coalescing stem) | core | — | contemporary | — | — | grammar_reference | n/a | verified | colloquial coalesced form dwe for dweʌ. p.81 |
| 짖 cij- | 'to tear' | verb (invariable C-stem) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.81 |
| 심 sim- | 'to sow' | verb (invariable C-stem) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.81 |
| 벗 bʌs- | 'to take off, to undress' | verb (invariable C-stem) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.81 |
| 적 jʌg- | 'to be small' | verb (invariable C-stem, descriptive) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.81 |
| 눕 nub- | 'to lie down' | verb (irregular: b-final C-stem) | core | — | contemporary | — | — | grammar_reference | n/a | verified | u-final allomorph before V-initial suffix: 누워 nuwʌ. p.83 |
| 돕 dob- | 'to help' | verb (irregular: b-final C-stem) | core | — | contemporary | — | — | grammar_reference | n/a | verified | 도와 dowa; dou- allomorph triggers V-form ending selection. p.83 |
| 가깝 gakab- | 'to be near' | verb (irregular: b-final C-stem, descriptive) | core | — | contemporary | — | — | grammar_reference | n/a | verified | 가까와 gakawa. p.83 |
| 짓 jis- (v.) | 'to build' | verb (irregular: s-dropping C-stem) | core | — | contemporary | — | — | grammar_reference | n/a | verified | homophonous with but distinct from the derivational prefix 짓 jis- above; s-less allomorph: 지어라 jiʌla 'Build it.' p.82 |
| 붓 bus- | 'to pour' | verb (irregular: s-dropping C-stem) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.82 |
| 듣 did- | 'to hear' | verb (irregular: d-final C-stem) | core | — | contemporary | — | — | grammar_reference | n/a | verified | l-final allomorph before V-initial suffix: 들어라 dilʌla. p.82 |
| 깨닫 kɛdad- | 'to understand or realize' | verb (irregular: d-final C-stem) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.82 |
| 묻 mud- | 'to ask' | verb (irregular: d-final C-stem) | core | — | contemporary | — | — | grammar_reference | n/a | verified | 물어라 mulʌla 'Ask!'. p.82 |
| 걷 gʌ:d- | 'to walk' | verb (irregular: d-final C-stem) | core | — | contemporary | — | — | grammar_reference | n/a | verified | p.82 |
| 덮이 dʌpi- | 'to be covered' | verb (passive, -i- allomorph) | core | — | contemporary | — | — | grammar_reference | n/a | verified | < dʌp- 'to cover' + -i-. p.85 |
| 업히 ʌbhi- | 'to be carried [on the back]' | verb (passive, -hi- allomorph) | core | — | contemporary | — | — | grammar_reference | n/a | verified | < ʌb- 'to carry [on the back]' + -hi-. p.85 |
| 꽂히 kojhi- | 'to be inserted' | verb (passive, -hi- allomorph) | core | — | contemporary | — | — | grammar_reference | n/a | verified | < koj- 'to insert' + -hi- (pronounced /koci/). p.85 |
| 끌리 killi- | 'to be drawn' | verb (passive, -li- allomorph) | core | — | contemporary | — | — | grammar_reference | n/a | verified | < kil- 'to draw' + -li-. p.85 |
| 감기 gamgi- | 'to be wound' | verb (passive, -gi- allomorph) | core | — | contemporary | — | — | grammar_reference | n/a | verified | < gam- 'to wind' + -gi-. p.85 |
| 비우 biu- | 'to empty' | verb (causative, -u- allomorph) | core | — | contemporary | — | — | grammar_reference | n/a | verified | < bi- 'to be empty' + -u-. p.85 |
| 새우 sɛu- | 'to keep vigil' (lit. 'to cause dawn to break') | verb (causative, -u- allomorph) | core | — | contemporary | — | — | grammar_reference | n/a | verified | idiomatic causative; < sɛ- 'to dawn' + -u-. p.85 |
| 남기 namgi- | 'to leave behind, to make remain' | verb (causative, -gi- allomorph) | core | — | contemporary | — | — | grammar_reference | n/a | verified | < nam- 'to remain' + -gi-. p.86 |
| 맡기 matgi- | 'to cause to undertake' | verb (causative, -gi- allomorph) | core | — | contemporary | — | — | grammar_reference | n/a | verified | < mat- 'to undertake' + -gi-. p.86 |
| 넓히 nʌlbhi- | 'to widen' | verb (causative, -hi- allomorph) | core | — | contemporary | — | — | grammar_reference | n/a | verified | < nʌlb- 'to be wide' + -hi-. p.86 |
| 읽히 ilghi- | 'to make read' | verb (causative, -hi- allomorph) | core | — | contemporary | — | — | grammar_reference | n/a | verified | < ilg- 'to read' + -hi-. p.86 |
| 날리 nalli- | 'to fly [something]' | verb (causative, -li- allomorph) | core | — | contemporary | — | — | grammar_reference | n/a | verified | < nal- 'to fly' + -li-; contrasts with passive 날린다 nallinda 'it is flown' by object presence alone — form is identical. p.86-87 |
| 맞히 majhi- / 맞후 majhu- | 'to get [something] correct' | verb (causative, -hi-/-hu- allomorph) | core | — | contemporary | — | — | grammar_reference | n/a | verified | < maj- 'to be correct' + -hi-/-hu-. p.86 |

**Morpheme breakdown (agglutinative composition — representative examples from the chapter's own worked illustrations).**

> **잡히시었겠사옵니다 japisiʌskɛsaomnida** = jab- ('to catch', V.st.) + -hi- (passive voice sfx.) + -si- (honorific sfx.) + -ʌsges- (past+future-presumptive compound tense sfx.) + -sao- (humble sfx.) + -bnida (high formal declarative infl.end.) — 'He may have been captured.' Lee's own maximal six-element worked example, illustrating the full obligatory-plus-optional verb-element ordering (stem → voice → honorific → tense → humble → inflectional ending). p.76

> **가까와 gakawa** = gakab- ('to be near', irregular b-final C-stem) + -a (a/ʌ-form ending) — the b-final stem's u-final allomorph (gakau-) regularly contracts uʌ→wa before an a/ʌ-initial ending, with the Korean spelling adapted accordingly; demonstrates how an irregular stem-class membership and a general vowel-contraction rule interact. p.83

### Grammar points

#### Elements within the verb (§4.1)

Lee analyzes the Korean verb as built from up to six ordered elements: Verb Stem, Voice Suffix, Honorific Suffix, Tense Suffix(es), Humble Suffix, and Inflectional Ending — in that fixed order. Only the stem and the inflectional ending are obligatory; every element between them is optional. Stem and voice suffix jointly determine predicate/clause type (transitive, intransitive, passive, causative); inflectional endings determine the clause's syntactic function. p.76

#### Stem structure and stem classes (§4.2)

Verb stems are simple (a single root, optionally preceded by one of a closed set of class-maintaining derivational prefixes — see the five prefixes in the Vocabulary table) or compound (two verb roots concatenated directly, with no formal element joining them).

Stems are classified on a purely phonological basis into **V-stems** (vowel-final) and **C-stems** (consonant-final), each further split into **Invariable** and **Variable** sub-classes depending on whether the stem's shape changes before suffixes. The variable sub-classes are a systematic inventory of Korean's traditionally "irregular" verbs, each defined by its own conditioning environment:
- V-stems: i-dropping (crwa before ʌ/a-initial suffixes), u-dropping (one verb only: 푸 pu- 'to draw water'), l-doubling (ll-allomorph before ʌ/a-initial suffixes), and the ha-stem (hʌj- allomorph before a/ʌ-initial suffixes, with a colloquial hʌjʌ>hɛ coalescence).
- C-stems: l-dropping (before suffixes beginning /n/, /s/, /b/, /o/), s-dropping, d-final (l-allomorph before V-initial suffixes), and b-final (u-final allomorph before V-initial suffixes, triggering a knock-on V/C-form ending selection change and a uʌ→wa contraction).

This is a compact, fully systematic restatement of Korean verb-stem morphophonemics; its value for slang-synthesis mechanics is that every irregular-conjugation pattern slang might exploit or regularize is named with its exact triggering environment here, in one place. pp.77-83

#### Voice suffix system (§4.3.1)

Korean voice is a three-term system (Active [unmarked] / Passive / Causative, mutually exclusive — only one voice suffix per stem at a time). The passive voice suffix has four phonologically-conditioned allomorphs (-i- after p/t/k/h/V-final stems, -hi- after b/d/g/j-final stems, -li- after l-final/l-doubling/d-final stems, -gi- after m/n/s/c/nh-final stems). The causative voice suffix shares most of the same allomorph shapes plus -u- (after i/ɛ-final stems) and -hi-/-hu- (after j-final stems), which is why many causative/passive pairs are formally homophonous — in running speech, voice value is then disambiguated only by the presence/absence of an object (passive verbs take none; causative verbs take at least one). Not every active stem has a suffix-derived passive/causative counterpart; gaps are filled periphrastically with auxiliary verbs (cross-referenced but not detailed in this chapter). pp.84-87

#### Honorific suffix (§4.3.2) — skipped as redundant

Lee describes a single honorific suffix -si-/-isi- expressing subject-directed respect. This is covered far more thoroughly in `031_korean_honorifics_and_politeness.md`; not re-extracted here beyond this cross-reference.

#### Tense suffixes (§4.3.3) — compact morpheme inventory only (discursive tense-category exposition skipped as redundant with `051_tense_and_aspect_in_korean.md`)

Direct tense suffixes: Zero (neutral, diary/monologue style), -n-/-nin- (present, V/C-form), -aš-/-ʌš- (past, a/ʌ-form), -geš- (future). Retrospective tense suffix: -di-/-dʌ- (combinable with any of the above except the present suffix). The past suffix may reduplicate and/or combine with the future suffix to derive compound tense suffixes (past perfect -ašʌš-/-ʌšʌš-, past presumptive -ašgeš-/-ʌšgeš-, past perfect presumptive -ašʌšgeš-/-ʌšʌšgeš-). Four compound (all-progressive) direct tenses are built periphrastically with V.st. + -go + auxiliary iš- + a direct tense suffix. pp.87-96

#### Humble suffix (§4.3.4)

Distinct from the honorific suffix: the honorific suffix directs respect *to the subject*; the humble suffix lowers *the speaker's own status*, thereby increasing respect shown *to the addressee*. Four allomorphs: -o-/-io- (before most inflectional endings), -ob-/-iob- (before a narrower ending set), -sao- and -saob- (C-form variants used after a tense suffix co-occurs). Lee notes it is largely obsolete in ordinary speech but persists in religious and literary registers. Social-context worked examples (child-to-teacher vs. child-to-friend vs. servant-to-mistress) make explicit how honorific and humble marking can stack to express respect toward two different referents (subject and addressee) simultaneously in one verb form. pp.96-98

#### Final endings — the five-speech-style × four-mood paradigm (§4.3.5.1)

Lee gives a single complete paradigm of Korean's final (sentence-ending) inflectional endings, organized as five speech styles (High Formal, Low Formal, High Plain, Low Plain, Medium) crossed with up to four moods (Declarative, Interrogative, Imperative, Propositive), plus assorted interjectival/suspective/promissive/retrospective sub-endings. High Formal endings are componentially built from three ordered sub-morphs: style marker -b-/-ib-, a mood marker (-ni- indicative / -si- volitive / -di- retrospective), and -da (declarative/propositive). Lower styles use single-morpheme portmanteau endings instead. Selected cells: High Formal declarative -(s)ibnida; Low Formal declarative -o/-io (V/C-form) or -so (after Zero-tense C-stems); High Plain declarative -ne / -mse(promissive)/-de(retrospective); Low Plain declarative -da; Medium declarative -a/-ʌ (a/ʌ-form). Imperative and declarative/propositive endings at the same style are frequently homophonous, disambiguated mainly by intonation (a higher, more abrupt pitch contour) and stress rather than segmental form. pp.98-105

#### Non-final endings (§4.3.5.2)

Three types, none of which vary by speech style (unlike final endings): **Nominal clause endings** -m/-im (abstract/general) vs. -gi (emphasizes ongoing process or descriptive degree) — a genuine semantic contrast, not free variation. **Adjectival clause endings** -nin (present), -n/-in (past/present, V/C-form), -l/-il (future/presumptive) — each with its own distinct distributional and tense-interaction restrictions. **Adverbial clause endings**: Lee catalogs 21 distinct connective/subordinating endings in one numbered list, each glossed with its core meaning — among them -go 'and', -mjʌ/-imjʌ 'and' (simultaneous), -myʌnsʌ 'while', -ja 'as soon as', -dolog/-ge 'until, so that', -(i)lsulog 'the more... the more', -(i)ljʌgo/-goja 'in order to', -(l)pundʌlʌ 'not only... but also', -gana/-din(ji)/-na/-ina 'whether... or', -mjʌn/-gʌdin 'if, when', -laja 'only if', -ado/-(dʌl)ado 'even if/though', -jiman/-gʌnman/-na/-ina 'although/but', -ljʌnman 'might/would... but', -asʌ/-ʌsʌ 'and then; since, because', -dolog 'until/so that' (numeral-listed separately from its synonym -ge above), -milo/-imilo 'as, since, because', -ni(ka)/-ini(ka) 'when/because', -ninde/-nde/-inde 'and (topic introducer)', -dwe 'may/might... but'. This is the single most complete connective-ending inventory found in the Korean corpus to date — a strong candidate resource for later slang-mechanics work on which connectives most often get phonetically reduced or repurposed in casual registers. pp.105-110

#### Concatenating endings (§4.3.5.3)

A fourth, distinct ending category — Lee's own term, not found replicated under this name in any other established Korean file in this corpus. Four concatenating endings link a verb to a following verb within the head of a verbal phrase (cross-referenced to Chapter V, not detailed there in this chunk's range): -a/-ʌ (Concatenating Ending I, a/ʌ-form), -go (II), -ge (III), -ji (IV). Processive verbs may take any of the four; descriptive verbs are restricted to -a/-ʌ, -ge and -ji. None of the four may be preceded by a tense suffix. p.111


---

## Chapter V: Phrase

**Source:** Hyun Bok Lee, *Korean Grammar* (Oxford University Press, reference grammar). Chapter V "Phrase," printed pp. 112–147 = PDF pages 65–82 of the scanned source. Attested Era for all entries below: `contemporary (source published 1989, per publisher record)`.


**Text layer / vision-reading note:** confirmed via `pdffonts`/`pdftotext` — this PDF has **zero embedded fonts, zero text layer at all** (pure raster scan, not even a font-substitution cipher to attempt). Every row below was vision-read from pages rendered at 150 DPI. Each PDF page is a two-printed-page spread; empirically verified PDF page 65 = printed pp. 112–113, and the chapter boundary was directly confirmed by reading the "Chapter VI / CLAUSE" header starting at PDF page 83 (printed p. 148) — so this chunk's range (PDF 65–82) is exact, not estimated. **No handwritten marginalia found anywhere in this range** — all pages are clean typeset print, no previous-owner annotation.

**Coverage note — non-redundant-supplement scope decision.** Checked against `047_korean_loas_library.md`/`067`/`068`/`069` (Suk-Jin Chang, also a theoretical/structural description) and `048_korean_cambridge_surveys.md` for phrase-structure overlap.
- **Skipped/compressed as redundant or low-value drill:** the bulk of §5.2.1.1.2.3 (pp. 138–141), which is a near-exhaustive combinatoric drill walking every possible X/x/Y/y auxiliary-verb-chain permutation (two-, three-, four-, and five-auxiliary-verb sequences) — this is the same underlying rule repeated ~25 times with different example sentences; only representative examples are kept below, not the full drill. Basic nominal-phrase vocabulary (jib 'house', koc 'flower', etc.) is not re-tabulated — these are extremely common items already present dozens of times across the existing 59-file corpus.
- **Kept as genuinely new — this chunk's flagship finding:** the entire §5.2 "Verbal Phrase" Nucleus/Satellite head-structure framework and especially §5.2.1.1.2.1's **four-group auxiliary-verb classification by the concatenating form (-a/ʌ, -go, -ge, -ji) each group imposes on the immediately preceding verb** — confirmed via corpus-wide grep that the terms "Nucleus"/"Satellite" appear nowhere else in this project's Korean extractions. No prior Korean extraction organizes Korean's auxiliary-verb system this way (by morphosyntactic concatenation-class rather than by semantic function alone), and the full 20-item auxiliary-verb inventory with per-item collocational restrictions is captured in full below — auxiliary-verb chaining is a strong candidate for later slang-synthesis mechanics work (productive chain-stacking, e.g. the attested 5-verb chain 웃어 넘겨 버려 지지 않게 하여 주어라). Also kept: the Nominal Phrase's formal IC-tree / embedding-ambiguity treatment (§5.1.4, the *alimdaun jʌjaii mogšoli* worked example showing two distinct bracketings yield two distinct meanings) and the three-way structural distinction between coordinator-linked nouns, paratactically-linked nouns, and nouns-in-apposition (§5.1.2.2, each has different diagnostic properties — coordinator-insertability, order-reversibility — not spelled out this explicitly elsewhere); the Relational Phrase chapter (§5.3) as a whole, since no prior extraction treats Korean's postpositional/particle-final phrases as their own exocentric Axis+Relatum phrase type.

---

### Vocabulary

The closed-set auxiliary-verb inventory (the chapter's central content) is given in full. Other vocabulary is a representative sample of non-basic items — basic nouns/adjectives already well-attested elsewhere in the corpus are not re-tabulated per the non-redundant-supplement note above.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| bo- | 'to try [doing], to see how it is' | auxiliary verb | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | Group I aux. (concat. form -a/ʌ on preceding verb). p.132 |
| ju- | 'to do something for someone as a favor' | auxiliary verb | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | Group I aux. p.132 |
| dili- | 'to do something for someone as a favor (honorific)' | auxiliary verb | honorific | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | Group I aux.; honorific counterpart of ju-. p.132 |
| dɛ- | 'repetition, continuation' | auxiliary verb | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | Group I aux.; limited collocability vs. šah- (collocates with mʌg- 'eat', ul- 'cry', nolli- 'tease', kabul- 'behave flippantly', bul- 'blow', etc.). p.132 |
| šah- | 'repetition, continuation' | auxiliary verb | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | Group I aux.; broader collocability than dɛ-. p.132 |
| bali- | 'to do something completely/thoroughly' | auxiliary verb | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | Group I aux. p.133 |
| ji- | '(a) passive-voice formative (after V.tr.); (b) unintentional/independent-of-will action (after V.intr.); (c) processive-verb formative, "to become" (after V.d.)' | auxiliary verb | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | Group I aux.; three distinct functions conditioned by preceding verb type. p.133 |
| ga- | 'progression toward a goal, from present to future, or away from the speaker; near-completion' | auxiliary verb | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | Group I aux. p.133 |
| o- | 'progression from past to present, or toward the speaker' | auxiliary verb | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | Group I aux.; directional contrast pair with ga-. p.133 |
| noh- | 'completion, retention [of a resulting state]' | auxiliary verb | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | Group I aux.; usually preceded by V.tr. only. p.133 |
| na- | 'progression, completion' | auxiliary verb | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | Group I aux.; limited to specific V.intr. (pi- 'blossom', sos- 'rise/soar', jala- 'grow', sal- 'leave'). p.134 |
| nɛ- | 'progression, completion' | auxiliary verb | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | Group I aux.; limited to specific V.tr. (gjʌndi- 'endure', ha- 'do', igi- 'win', jis- 'devise/compose/make'). p.134 |
| iš- | progressive-tense formative | auxiliary verb | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | Group II aux. (concat. form -go). p.134 |
| sip- | 'to want to, to wish to' | auxiliary verb | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | Group II aux. (desiderative); V.d.aux. p.135 |
| ha- | '(a) causative-voice formative (after V.p.); (b) causative-voice and processive-verb formative (after V.d.)' | auxiliary verb | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | Group III aux. (concat. form -ge); whole verbal head becomes transitive, up to two objects possible. p.135 |
| mandil- | causative (more emphatic than ha-, otherwise identical) | auxiliary verb | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | Group III aux. p.135-136 |
| dwe- | '(a) unintentional/independent-of-the-subject's-will (after V.p.); (b) "to become" processive-verb formative (after V.d.)' | auxiliary verb | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | Group III aux. p.136 |
| aniha- | simple negation | auxiliary verb | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | Group IV aux. (concat. form -ji); declarative/interrogative sentences only (except interrogatives with 1st-person subject). p.136-137 |
| mosha- | 'to be unable to' — inability/incapability (animate subject) or regret (speaker's judgment that something is unfavorable) | auxiliary verb | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | Group IV aux.; semantically distinct from aniha- (simple negation). p.137 |
| mal- | negation | auxiliary verb | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | Group IV aux.; imperative/propositive sentences only (complementary distribution with aniha-/mosha-). p.136-137 |
| jando | 'degree, extent' | noun | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | head of the jando-lo relational phrase (verbal-expansion use); e.g. nollal jandolo 'to a surprising degree'. p.142, 144 |
| mankim/manci | 'as ~ as, to the degree that' (postmodifier) | particle/postmodifier | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | heads a nominal phrase used as verbal expansion; e.g. imankim 'this much'. p.143-144 |
| sandaŋhi | 'quite, considerably' | adverb | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | descriptive adverb example. p.143, 145 |
| namu | 'too much, excessively' | adverb | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | processive-descriptive adverb, occurs with either processive or descriptive verbal heads. p.143 |
| meu | 'very' | adverb | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | descriptive adverb. p.143 |

### Grammar points

#### Nominal Phrase: Head + Expansion structure (§5.1, §5.1.1)

A nominal phrase (NP) is an endocentric construction — syntactically identical to a single noun — consisting of a Head (the noun or noun-equivalent) and an Expansion (one or more subordinate modifying elements). The unmarked order is Expansion-then-Head; the reverse order (Head-then-Expansion) occurs only in careless/informal speech. p.112.

#### Nominal Head types (§5.1.2)

Four exponents can fill the nominal-head position:
- **Single noun** — any noun, independent or non-independent, simple or compound. p.113.
- **Two or more nouns**, which may be linked in three structurally distinct ways, each with different diagnostics:
  - *Coordinator-linked* (wa/gwa 'and', na/ina 'or', or the conjunctive adverbs giligo 'and', ionin 'or') — theoretically unlimited nouns, in practice rarely more than three. p.114.
  - *Paratactically-linked* (no overt coordinator, nouns joined purely by intonation pattern — every noun but the last takes Intoneme LF or R) — these retain the *potential* to take a coordinator between every pair of member nouns (but only wa/gwa and giligo, never na/ina or ionin). p.114.
  - *Nouns in apposition* (N¹ = typically family/given name, N² = title or descriptive noun) — diagnostically distinct from paratactic nouns in two ways: (i) cannot take a coordinator between N¹/N², while paratactic nouns can; (ii) N¹/N² order is freely reversible (N² + N¹ also grammatical, e.g. *jaŋgun gaŋ gamcan* ~ *gaŋ gamcan jaŋgun* 'General Gang Gamchan'), while paratactic-noun order is fixed. A two-stress-group apposition sequence marks N¹ with Intoneme L. p.114-117.
- **Nominal group** — N¹N²...Nⁿ, right-headed (last N = head, all preceding = subordinate, itself recursively analyzable). Differs from apposition: every member but the last can take the adjectival particle *ii* 'of' (yielding an adjectival-phrase paraphrase), which apposition cannot; member-noun order is fixed, unlike apposition's reversibility. *ii* has a tendency to drop in a chain, in casual speech. p.116-118.
- **Compound numeral** — two or more numeral nouns, optionally + classifier forming a "Compound Numeral Expression" (itself an endocentric NP headed by the classifier). The first element must be a compound numeral *adjective* (not noun) if the numeral's last digit is 1-4 (e.g. *sasibo wʌn* 'forty-five won' < *sasibo* compound-numeral-adjective 'forty-five' + *wʌn* classifier). p.117. The most frequent construction for quantifying a noun's referent is N + Compound Numeral Expression, treated as a special type of appositional construction; a less frequent alternative is Compound-Numeral-Expression + *ii* + N. p.117-118.

#### Nominal Expansion (§5.1.3)

Up to three adjectives, up to two adjectival clauses, one or more adjectival relational phrases, or any combination of up to three adjectives plus an adjectival clause, may fill the expansion slot.
- **Adjectives**: deictic and interrogative adjectives are mutually exclusive with each other (cannot co-occur, and no two deictic/interrogative adjectives co-occur at once); no fixed ordering except a qualitative adjective, if present, must come last (immediately before the head). p.118.
- **Adjectival clauses**: up to two, linked by coordinator (giligo/ionin) or parataxis; coordinator/parataxis-linked adjectival clauses are far less frequent than the semantically equivalent single adjectival clause formed by simply concatenating the two predicates. p.118-119.
- **Adjectival relational phrase(s)** (N + *ii*, cf. §5.3.2): up to three in practice, though theoretically unlimited; IC structure is a nested left-branching tree (N¹+ii, [N²+ii], [N³+ii]...Nⁿ). p.120.

#### Nominal Phrase embedded in a larger Nominal Phrase (§5.1.4)

A complex NP may have another NP as its head, giving the formula NP → Exp. + Exp.¹ + H¹ (where NP¹ → Exp.¹ + H¹ is itself embedded as H). A tentative juncture very often separates Exp. from Exp.¹ in speech. Crucially, a sequence of this Exp.+Exp.¹+H¹ structure can carry **genuine structural ambiguity** depending on where the first IC (immediate-constituent) cut is made: *alimdaun jʌjaii mogšoli* 'the beautiful woman's voice' bracketed as [alimdaun] + [jʌjaii mogšoli] means '(the) voice of the beautiful woman', but bracketed as [alimdaun jʌja] + [ii] + [mogšoli] means 'the woman's voice which is beautiful' — the two parses correspond to different real-world claims (whether it's the woman or the voice that is beautiful). p.121-122.

#### Verbal Phrase: Nucleus/Satellite head structure (§5.2, §5.2.1) — flagship finding

The verbal phrase (VP) consists of an obligatory Head and an optional Expansion (adverb/adverbial phrase), in that order (Expansion precedes Head, matching the general Korean modifier-before-modified pattern). The Head itself is further analyzed into two constituents:
- **Nucleus**: one to three full verbs (obligatory) — the semantically central but *syntactically peripheral* element.
- **Satellite**: one or more auxiliary verbs (optional) — semantically peripheral but **syntactically central**, since it is the satellite's last auxiliary verb that determines the external syntactic distribution of the entire verbal head/phrase (e.g. whether the whole VP behaves as processive or descriptive type, transitive or not).

Lee explicitly frames this Nucleus-subordinate-to-Satellite relationship as unusual relative to the general Korean pattern where the modifier (Satellite, here analogous to a subordinate) normally cannot stand alone — but here it is the nucleus, not the satellite, that can occur independently; the satellite's dependent auxiliary verbs cannot function alone without a preceding nucleus. p.122-124.

**Nucleus structure** (§5.2.1.1.1): one to three processive verbs, each (except the last) inflected in concatenating form I (-a/ʌ). A one-verb nucleus is most frequent, two-verb less frequent, three-verb rare. Descriptive verbs can only form a one-verb nucleus — multi-verb nuclei cannot include or consist entirely of descriptive verbs, *except* a two-verb nucleus whose second verb is *boi-* 'to be seen/shown/seem' (a passive verb derived from *bo-* 'to see'). The nucleus is further split into **transitive** vs. **intransitive** type by the verb(s) it contains, each inheriting the same syntactic behavior as a single transitive/intransitive verb would. p.124-126.

#### Satellite / auxiliary-verb system: four-group concatenating-form classification (§5.2.1.1.2, §5.2.1.1.2.1) — flagship finding

The satellite consists of one or more auxiliary verbs, each (except the last) inflected in the concatenating form required by the *immediately following* auxiliary verb. Theoretically unlimited in number (one auxiliary, e.g. *anh-* negation, can in principle repeat indefinitely), but in practice rarely exceeds five. Lee classifies **all Korean auxiliary verbs into four groups**, by which of the four concatenating forms (cf. §4.3.5.3) each group requires of the immediately preceding verb:

- **Group I** (requires concat. form I, *-a/ʌ*): 12 members — *bo-*, *ju-*, *dili-*, *dɛ-*, *šah-*, *bali-*, *ji-*, *ga-*, *o-*, *noh-*, *na-*, *nɛ-* (see Vocabulary table for individual glosses/restrictions).
- **Group II** (requires concat. form II, *-go*): 2 members — *iš-* (progressive), *sip-* (desiderative).
- **Group III** (requires concat. form III, *-ge*): 3 members — *ha-*, *mandil-*, *dwe-* (causative/processive-formative cluster).
- **Group IV** (requires concat. form IV, *-ji*): 3 members — *aniha-*, *mosha-*, *mal-* (negation cluster).

General principles governing the satellite (p.126-129): (i) every auxiliary verb determines the concatenating form of whatever immediately precedes it (full verb or another auxiliary); (ii) every auxiliary adds to or modifies the meaning of the verb(s) in the nucleus; (iii) some auxiliary verbs determine whether the whole verbal head is of **processive or descriptive type** — e.g. a descriptive-verb nucleus + *ji-* behaves as a processive-type head and can then take further auxiliaries (such as *iš-*) that a bare descriptive verb could never take directly; (iv) some auxiliaries extend the morphological voice/tense system (e.g. *ji-* as passive-voice formative, *iš-* as progressive-tense formative).

**The type-propagation (processive/descriptive) rule** is formalized (p.130-131) with X = processive full verb(s), x = processive auxiliary, Y = descriptive full verb(s), y = descriptive auxiliary: a nucleus X or Y may be followed by x¹ or y¹, which may in turn be followed by x² or y² (or y¹/x¹ respectively) — all four satellite positions (x¹,y¹,x²,y²) combine freely in any order/direction (vertically, horizontally, diagonally per Lee's diagram), yielding attested sequences like x¹y¹, x¹y², y¹x¹, x¹y¹x²y²x¹x², etc. Two key restrictions: (i) **if a descriptive verb (full or auxiliary) is followed by a processive auxiliary, that processive auxiliary must be one of the processive-verb-formatives *ji-*, *ha-*, *dwe-*, etc.** — i.e. a bare arbitrary processive auxiliary cannot follow a descriptive chain, only a type-converting one; (ii) if a descriptive verb/auxiliary is followed by one or more further descriptive auxiliaries, the first of these (y¹) must be *mosha-* or *aniha-* (unless preceded by *sip-*, in which case *mosha-* is excluded), and subsequent ones (y²,y³...) must be *aniha-*.

**Attested chain depth**: the book exemplifies verbal heads with two, three, four, and (at maximum) **five** chained auxiliary verbs, e.g. the 5-auxiliary chain *usʌnʌmgja bʌljʌjiji anke haja juʌla* 'Do not allow [it] to be laughed away [for her sake]' (X-x-x-x-x-x pattern) and *japjʌgaji anke he jugo sipʌ handa* 'She wants to make him not to be arrested and taken away [for his sake]' (X-x-x-x-y-x). This confirms auxiliary-verb stacking as a genuinely productive, multi-slot morphosyntactic process in Korean — not limited to the two- or three-verb chains most teaching grammars illustrate. p.138-142.

#### Expansion of the Verbal Phrase (§5.2.1.2)

Six possible fillers for the (optional) verbal-phrase expansion slot, occurring before the Head:
1. **Processive adverb** — occurs with a processive-type verbal head. p.142.
2. **Descriptive adverb** — occurs with a descriptive-type head, or one ending in *boi-* 'to seem'. p.143.
3. **Processive-descriptive adverb** — occurs with either type (e.g. *namu* 'too much', *meu* 'very'). p.143.
4. **Nominal phrase** headed by the postmodifier *mankim/manci* 'as ~ as, to the degree that' — occurs mainly before descriptive-type heads, less often processive. p.143-144.
5. **Relational phrase** of the structure Adj./adj.cl. + *jando* 'degree, extent' + *lo* 'to/as/by' — same distribution as (4). p.144.
6. **Adverbial phrase** (cf. §5.2.1.2.6) — itself an endocentric construction: a processive adverb as head, with a descriptive adverb / processive-descriptive adverb / nominal phrase / relational phrase as its own subordinate, occurring before a processive-type nucleus, e.g. *sandaŋhi cancanhi ogo idʼa* '[They] are coming quite slowly' (sub. *sandaŋhi* + H *cancanhi*). p.144-145.

#### Relational Phrase (§5.3)

A relational phrase is an **exocentric construction** (its distribution matches *neither* constituent alone — contrast the endocentric NP/VP above) consisting of Axis (most often N/NP, but can itself be another relational phrase or a clause) + Relatum (a particle), in that fixed order. Two types, by syntactic function:

- **Adverbial Relational Phrase** (§5.3.1): relatum is a directive particle, a quotative particle, or a clausal conjunctive particle; functions as a minor sentence alone or (more commonly) as a clause-level Adjunct. May itself take a further modifying particle.
- **Adjectival Relational Phrase** (§5.3.2): relatum is specifically the adjectival particle *ii* 'of'; syntactically equivalent to an adjective (subordinate to a following noun/NP). The axis may be N, NP, or — notably — an **adverbial relational phrase**, in which case the whole construction ends in *two* particles stacked (since the axis itself already ends in a particle), e.g. *sʌulesʌ ii sosig* 'the news [of] from Seoul' (axis = *sʌulesʌ*, an adverbial rel. phrase ending in the directive particle *esʌ* 'from', + adjectival relatum *ii*). p.145-147.


---

## Chapter VI: Clause

**Source range:** H.B. Lee, *Korean Grammar* (Oxford University Press, 1989), Chapter VI "Clause," printed pp. 148-185 (PDF pages 83-101 of the scanned source — confirmed empirically: PDF p.83 = printed pp.148-149 showing the "VI / CLAUSE" chapter-opening header; PDF p.102 = printed pp.186-187 showing the "VII / SENTENCE" chapter-opening header, so the chapter boundary is exact, no drift). Zero text layer anywhere in the source PDF (confirmed via `pdffonts`: no embedded fonts at all — a pure raster scan, not even a font-substitution cipher to attempt) — every page in this range was vision-read directly from 150 DPI renders. No handwritten marginalia found anywhere in pp.148-185; all pages are clean typeset print with only the book's own running headers/page numbers/footnote.

**Non-redundant-supplement scope decision.** This chapter is a systematic structural-grammar description of Korean clause types, substantially overlapping in topic (though not in theoretical framework) with several already-extracted structural/academic sources. Checked specifically against `047_korean_loas_library.md`/`067`/`068` (Chang, LOALL), `048_korean_cambridge_surveys.md`, `049_history_of_korean_language.md`/`053`, and `052_korean_semantic_pragmatic_grammar.md` for passive/causative-clause and adverbial-clause-classification overlap (grep for "causative" and "concentric"/"eccentric" across all 66 prior established files).
- **Skipped as redundant:** the bare existence of passive/causative morphology (suffixal and phrasal `ha-`/`mandil-` causatives) — already well documented across 20+ prior files including the four sources above. Individual example sentences illustrating ordinary transitive/intransitive clauses with common vocabulary (공 'ball', 책 'book', 개 'dog', etc.) were not added to the vocabulary table below — these words are near-certain to already be present across the 29-plus beginner/intermediate course files (001-029, 035-046).
- **Kept as genuinely new:** this is the only source in the Korean corpus so far to present a fully systematic, author-original **clause-element algebra** — a six-element inventory (P/S/O/C/Ag./A) with explicit positional-formula notation (e.g. `(S)+(O)+P`, `(S)(Ag.)P`, `(S)+(O¹/Ag.)+(O²)+P.caus.`) for every clause type and every permitted marked/unmarked word-order variant. No prior Korean source in this corpus notates clause structure this way. Also kept: the **"Split Object"** phenomenon (a transitive clause may take two objects in a whole-part or unit-quantity relation, freely combinable into one NP via the adjectival particle *ii* 'of') — not found in any prior extraction (grep "split object" returns zero hits); the **two-way split of Descriptive Clause into Type I/II** (type I = C and S freely combine into a single NP, parallel to split objects; type II = a small, listable closed class of psych-predicates where this combination is structurally blocked — kept as a vocabulary list below); the full **five-way causative-clause typology** derived transformationally from each of the five non-causative clause types, including **double causativity** (a phrasal causative stacked on top of a morphological one); the explicit **Non-Final Clause positional restriction** (P must occupy clause-final position, unlike the final clause where all orders are possible) as the single structural difference between final and non-final clauses; the author's point that Korean's lack of relative pronouns is compensated by **Adjectival Clauses performing the same syntactic work via verbal inflection** (a non-redundant framing not seen stated this way elsewhere in the corpus); and the **Concentric vs. Eccentric Adverbial Clause** classification by subject-sharing with the following clause (distinct from `052`'s unrelated "concentric" tense-scope metaphor — confirmed by direct comparison, a false-positive grep match, not real overlap) together with a systematic 17-item inventory of adverbial clause endings grouped by this criterion, kept in full below as a vocabulary table since no prior file in this corpus tabulates Korean's connective/adverbial-clause-ending inventory this exhaustively or with this particular semantic/syntactic classification.

---

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 그립- (gilib-) | 'to miss, long for' | descriptive verb (psych-predicate) | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | Descriptive Clause Type II closed-class member; p.159 |
| 싫- (silh-) | 'to dislike' | descriptive verb (psych-predicate) | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | Type II; p.159 |
| 무섭- (musab-) | 'to be afraid of' | descriptive verb (psych-predicate) | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | Type II; p.159 |
| 반갑- (bangab-) | 'to be happy to meet/hear from' | descriptive verb (psych-predicate) | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | Type II; p.159 |
| 좋- (joh-) | 'to be good, fond of' | descriptive verb (psych-predicate) | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | Type II; p.159 |
| 서운하- (saunha-) | 'to be sorry, sad, regrettable' | descriptive verb (psych-predicate) | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | Type II; p.159 |
| 아쉽- (aswib-) | 'to miss (someone/something)' | descriptive verb (psych-predicate) | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | Type II; p.159 |
| 슬프- (silpi-) | 'to be sad over' | descriptive verb (psych-predicate) | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | Type II; p.159 |
| 억울하- (agulha-) | 'to be unjust, to feel robbed/wronged' | descriptive verb (psych-predicate) | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | Type II; p.159 |
| 근심스럽- (ginsimsilab-) | 'to be worried' | descriptive verb (psych-predicate) | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | Type II; p.159 |
| 궁금하- (gungimha-) | 'to be anxious, concerned' | descriptive verb (psych-predicate) | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | Type II; p.159 |
| 고서 (-gosa) | 'and then, afterward' | verb ending (adverbial clause, concentric) | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | ending #1 of 17; p.179 |
| 며/으며 (-mjʌ/-imjʌ) | 'and' (S¹≠S²) / 'while' (S¹=S²) | verb ending (adverbial clause, concentric-eccentric) | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | ending #2; meaning depends on subject-sharing; p.180 |
| 아(서)/어(서) (-a(sʌ)/-ʌ(sʌ)) | 'as, since, because' (S¹≠S²) / 'and then' (S¹=S²) | verb ending (adverbial clause, concentric-eccentric) | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | ending #2 of the concentric-eccentric pair; p.180-181 |
| 다(가) (-da(ga)) | 'interruption, transference' | verb ending (adverbial clause, concentric) | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | ending #3; p.180 |
| 려/으려, 려고/으려고, 고자 (-l(j)ʌ/-il(j)ʌ, -ljʌgo/-iljʌgo, -goja) | 'in order to' | verb ending (adverbial clause, concentric) | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | ending #4, 3 allomorph/variant forms given as one semantic group; p.180 |
| 고/요-조 (-go / -jo) | 'and' | verb ending (adverbial clause, concentric) | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | ending #3 of concentric group (numbered independently from the eccentric list); p.181 |
| 자 (-ja) | 'as soon as' | verb ending (adverbial clause, eccentric) | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | ending #4 of eccentric list; p.181 |
| 도록/게 (-dolog / -ge) | 'until, so that' | verb ending (adverbial clause, eccentric) | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | ending #5; p.181 |
| ㄹ수록/을수록 (-lsulog/-ilsulog) | 'the more ... the more' | verb ending (adverbial clause, eccentric) | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | ending #6; p.182 |
| ㄹ뿐더러/을뿐더러 (-lpundʌlʌ/-ilpundʌlʌ) | 'not only ... but also' | verb ending (adverbial clause, eccentric) | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | ending #7; p.182 |
| 거나/든(지)/나(으나) (-gʌna / -din(ji) / -na/-ina) | 'whether ... or' | verb ending (adverbial clause, eccentric) | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | ending #8, 3 variant forms as one semantic group; p.182 |
| 면/으면, 거든 (-mjʌn/-imjʌn, -gʌdin) | 'if, when' | verb ending (adverbial clause, eccentric) | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | ending #9; p.183 |
| 아야/어야, 라야 (-aja/-ʌja, -laja) | 'only if, only when' | verb ending (adverbial clause, eccentric) | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | ending #10; p.183 |
| 더라도/어도, ㄹ지언정/을지언정, ㄹ지라도/을지라도, ㄹ망정/을망정, ㄴ들/은들 | 'even if/though' | verb ending (adverbial clause, eccentric) | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | ending #11, 5 variant forms as one semantic group; p.183 |
| 지만/건만/언만/나(으나) (-jiman/-gʌnman/-ʌnman/-na/-ina) | 'although ..., ...but' | verb ending (adverbial clause, eccentric) | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | ending #12; p.184 |
| 런만/으런만 (-ljʌnman/-iljʌnman) | 'might/would ... but' | verb ending (adverbial clause, eccentric) | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | ending #13; p.184 |
| 므로/으므로 (-milo/-imilo) | 'as, since, because' | verb ending (adverbial clause, eccentric) | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | ending #14; p.184 |
| 니(까)/으니(까) (-ni(ka)/-ini(ka)) | 'when, as' (time) / 'because, as, since' (clause) | verb ending (adverbial clause, eccentric) | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | ending #15, dual-function; p.185 |
| 는데/ㄴ데/은데 (-ninde / -nde/-inde) | 'and' (topic introducer) | verb ending (adverbial clause, eccentric) | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | ending #16; p.185 |
| 되 (-dwe) | '[may/might] ... but' | verb ending (adverbial clause, eccentric) | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | ending #17, final item of the inventory; p.185 |

### Grammar points

#### 6.1 Final vs. Non-Final Clause

Every clause is either Final (predicate takes a final inflectional ending; can stand alone as a major sentence) or Non-Final (predicate takes a non-final ending; functions as a minor sentence or, more commonly, as a constituent of a larger sentence). This binary split is the single organizing axis for the whole chapter. (p.148-149)

#### 6.2 Elements of the Clause — the P/S/O/C/Ag./A framework

Lee analyzes every Korean clause as an endocentric construction with six possible elements: **Predicate (P)** — the only obligatory element — plus five optional elements: **Subject (S)**, **Object (O)**, **Complement (C)**, **Agent (Ag.)**, and **Adjunct (A)**. Each clause type is given an explicit algebraic structure formula using these six symbols (e.g. a transitive clause is `(S)+(O)+P`). Two groupings are drawn: by obligatoriness (P alone vs. the other five), and by cohesion-with-P (O/C/Ag. cohere more tightly with P than S/A do, since O/C/Ag. are selected by the particular verb while S/A are freely compatible with any P). (p.148-155)

- **6.2.1 Predicate** has six subtypes, each defined by the verb(s) composing it: Transitive, Intransitive, Descriptive, Equational, Passive, Causative. A VP's subtype is determined by its nucleus verb plus any voice-formative in its satellite (e.g. a VP is "passive type" if it contains the passive suffix *-ji-* in the satellite, or if a transitive nucleus combines with *-ji-*). (p.150-151)
- **6.2.2-6.2.4 Subject/Object/Complement**: each is commonly marked by its particle (S: *ga/i*, *kesʌ*, *esʌ*; O: *lil/il*; C: unmarked after copula *i-*, otherwise like S) or a modifying particle, but in spoken Korean the bare N/NP alone (no particle) is frequent for all three. (p.152-153)
- **6.2.5 Agent (Ag.)**: occurs only in passive and causative clauses. In passive clauses the agent particle is obligatory; in causative clauses the agent may take the agent particle, a modifying particle, or no particle at all. (p.153)
- **6.2.6 Adjunct (A)**: expressed by an adverbial noun, an interrogative adverb, an adverbial relational phrase, or a nominal phrase of distance/duration (optionally with *lil/il* for emphasis). Unlike O, A cannot be passivized into S. Multiple adjuncts of different types may co-occur in one clause. (p.153-154)

#### 6.3 Types of Final Clause

Six types, distinguished by predicate type and co-occurring elements:

- **6.3.1 Transitive Clause** `(S)+(O)+P`. Marked (emphatic, less frequent) orders: `(O)(S)P`, `P(S)(O)`, `P(O)(S)`.
  - **6.3.1.1 Split Object.** A transitive clause may take two objects (O¹, O²) standing in a whole-part relation (e.g. 'gentleman — his foot') or a unit-quantity relation (e.g. 'book — ten volumes'). O¹ and O² are freely interchangeable with a single unified object formed via the adjectival particle *ii* 'of' (e.g. 'the gentleman's foot' as one NP). Split-object structures read as semantically more emphatic than the single-object paraphrase. Several marked word-order permutations are given: `(O¹)(O²)P(S)`, `(S)(O²)P(O¹)`. (p.155-156)
- **6.3.2 Intransitive Clause** `(S)+P`, no O or C possible. Marked order: `P(S)`. (p.156-157)
- **6.3.3 Descriptive Clause**, split into two structurally and semantically distinct subtypes sharing the surface formula `(S)+(C)+P`:
  - **Type I**: S and C stand in a relation (mostly possession/part-whole) such that they can combine into a single unified subject NP, exactly parallel to the split-object phenomenon (e.g. 'the woman's hands were small' ↔ a combined subject 'the woman's hands'). Lee reformulates Type I's structure as `(S¹)+(S²)+P` where S² corresponds to the original C. Four marked orders given: `(S¹)P(S²)`, `P(S¹)(S²)`, `(S²)P(S¹)`, `P(S²)(S¹)`.
  - **Type II**: S and C *cannot* combine this way — it is a small, closed, listable class of predicates (the 11-item psych-predicate list in the Vocabulary table above: 'to miss', 'to dislike', 'to be afraid of', etc.) taking an experiencer S + stimulus/cause C. Lee notes this distinction can be explained transformationally: Type I descriptive clauses derive (by "C-inserting") from an intransitive kernel `S+P`, while Type II derives (by "Detransitive" transformation) from a transitive kernel `S+O+P` — i.e. Type II's C was historically/underlyingly an object. Four marked orders given: `(S)P(C)`, `P(S)(C)`, `(C)P(S)`, `P(C)(S)`. (p.157-160)
- **6.3.4 Equational Clause** `(S)+C+P`, predicate is copula *i-* 'to be' or *dwe-* 'to become'. When P is *i-*, C takes no particle. Marked order: `CP(S)`. (p.160-161)
- **6.3.5 Passive Clause**, two subtypes, each with an explicit transformational derivation diagram from a non-passive underlying clause:
  - **Type I**, derived from a plain transitive clause `(S)+(O)+P.tr.`: S→Ag., O→S, giving `(S)+(Ag.)+P.pasv.`. Five marked orders given (e.g. `(Ag.)(S)P`, `P(Ag.)(S)`).
  - **Type II**, derived from a split-object transitive clause `(S)+(O¹)+(O²)+P.tr.`: S→Ag., O¹→S, O² stays as C/O, giving `(S)+(Ag.)+(C/O)+P.pasv.`. Four marked orders given. Lee notes the passive Agent, unlike the transitive-clause S it derives from, may freely be inanimate (e.g. 'the paper is flown by wind') — many inanimate-Agent passives have no natural corresponding active transitive clause at all. (p.161-163)
- **6.3.6 Causative Clause**, with up to five structural subtypes depending on which non-causative clause type underlies it, each given its own transformational-derivation formula:
  1. `(S)+P` → `(S)+(O)+P.caus.` (from intransitive, descriptive, or passive `(S)+P` clauses) — the causative S is "invented," not present in the underlying clause.
  2. `(S)+(C)+P.equ.` → `(S)+(O/C¹)+(C)+P.caus.` (from equational clauses with *dwe-*).
  3. `(S¹/S)+(S²/C)+P.des.` → `(S)+(O/C)+(O¹/C¹)+P.caus.` (from either descriptive-Type-I or -Type-II clauses).
  4. `(S)+(O)+P.tr.` → `(S)+(O¹/Ag.)+(O²)+P.caus.` (from a single-object transitive clause).
  5. `(S)+(O¹)+(O²)+P.tr.` → `(S)+(Ag.)+(O¹)+(O²)+P.caus.` (from a split-object transitive clause).
  6. `(S)+(Ag.)+(O/C)+P.pasv.` → `(S)+(O¹/C¹)+(Ag.)+(O²/C²)+P.caus.` (from a Type-II passive clause).
  - **6.3.6.7 Double Causativity**: a causative clause can itself be re-causativized, but only if the underlying causative clause used a *morphological* (suffixal) causative — a phrasal causative (formed with *ha-*/*mandil-*) can never itself serve as the input to a further causativization. (p.164-169)

#### 6.4 Types of Non-Final Clause

- **6.4.1 Internal Structure**: identical to the corresponding final clause type in every respect except one positional restriction — P must occupy absolute clause-final position (no element may follow it), whereas a final clause permits P in any position relative to its other elements. This single restriction is why non-final clauses show far less word-order variety than final clauses. (p.170)
- **6.4.2 Nominal Clause**: P suffixed with *-m/-im* or *-gi*; functions like a noun but with a narrower distribution than a true noun — it cannot be preceded by a nominal expansion, and cannot be directly followed by the adjectival particle *ii* 'of' (both of which an ordinary noun permits). *-m/-im*-suffixed nominal clauses occur frequently standing alone as minor sentences in official documents, diaries, and advertisements (a register-specific usage note). Functions covered: as S, O, C within a clause; as axis of an adverbial relational phrase; as H (head) of a larger construction. (p.170-173)
- **6.4.3 Adjectival Clause**: P suffixed with *-nin*, *-n/-in*, or *-l/-lil*; functions like the nominal expansion slot an adjective fills. Lee makes an explicit, non-redundant typological point: Korean is often described as "lacking relative pronouns" (no equivalent of English who/whom/which/that), which is accurate as a surface-inventory fact but misleading as a claim about expressive power — Korean instead expresses the same relative-clause function through ordinary verbal inflection (the adjectival clause), with the European *adjective* corresponding structurally to a Korean adjectival clause whose predicate is of the *descriptive* type, and the European *relative clause with pronoun* corresponding to one whose predicate is of the *processive* (action-verb) type. The adjectival clause's head (H) may be drawn from any of: S/S¹, O/O¹, O¹/Ag., O², or A of the final clause the adjectival clause is transformationally related to — or alternatively may be an "extra-clausal" element with no such underlying-clause relation at all (e.g. 'the fact that people gather', 'the time when the war broke out' — abstract head nouns like 'fact'/'time'/'case' bound to the clause only semantically). (p.173-177)
- **6.4.4 Adverbial Clause**: P suffixed with one of 17 distinct adverbial-clause endings (full inventory in the Vocabulary table above). Functions either alone as a minor sentence or, more frequently, as a subordinate to a final or non-final clause (typically separated by a tentative juncture). Lee makes a second explicit typological point, paralleling the relative-pronoun one above: Korean expresses *both* subordination ('if', 'when', 'because'...) *and* coordination ('and') of clauses by the same mechanism — a bound verbal inflectional ending — whereas English uses a free-standing conjunction for both; consequently English's syntactic subordinate/coordinate distinction has no clean formal correlate in Korean surface structure, so Lee classifies Korean adverbial clauses by a different criterion entirely:
  - **Concentric Adverbial Clauses**: the adverbial clause's subject must also function as the subject of the clause it is subordinate to (obligatory subject-sharing).
  - **Concentric-Eccentric (= Eccentric) Adverbial Clauses**: the subject may either be shared with the following clause or be an independent subject of its own. Two of the 17 endings (*-mjʌ/-imjʌ* and *-a(sʌ)/-ʌ(sʌ)*) are explicitly noted as **polysemous on this exact axis** — each ending means something different depending on whether its subject is shared (S¹=S²) or not (S¹≠S²): *-mjʌ/-imjʌ* = 'and' when S¹≠S², but 'while' when S¹=S²; *-a(sʌ)/-ʌ(sʌ)* = 'as/since/because' when S¹≠S², but 'and then' when S¹=S². This is a genuinely findable systematic ambiguity-resolution mechanism — the same bound morpheme's meaning is disambiguated purely by whether its subject NP is coreferential with the following clause's subject, not by any overt marking. (p.177-185)

---

## Chapter VII: Sentence

**Source range:** H.B. Lee, *Korean Grammar* (Oxford University Press, 1989), Chapter VII "Sentence," printed pp. 186–194 (PDF pages 102–105 of the scanned source, 117 total). Boundary confirmed by direct inspection: PDF page 101 = printed pp. 184–185, ending Chapter VI (the "VI / CLAUSE" running header is on p.184); PDF page 102 = printed pp. 186–187, opening with the "VII / SENTENCE" title page and the "Chapter VII" running header starting on p.187; the chapter ends mid-page at printed p.194 (PDF page 106, left side), where the Bibliography begins (p.195, right side of the same spread). Extracted directly by the recovery/merge pass completing this book's extraction (the prior dispatch produced chunks A–E covering Chapters I–VI and died before this final chapter).

**Text layer / vision-reading note:** confirmed via `pdfinfo`/`pdffonts`/`pdftotext` on the whole 117-page file: **zero embedded fonts and zero text layer anywhere in this PDF** — a pure raster scan throughout, not a font-substitution cipher (nothing to decode). All content in this section was vision-read from 150 DPI page renders (`pdftoppm -r 150`). No handwritten marginalia found anywhere in pp. 186–194 — all pages are clean typeset print, consistent with every other chapter of this book.

**Non-redundant-supplement scope decision.** This chapter is Lee's sentence-level capstone: it defines "sentence" phonologically (via his own Intoneme/juncture apparatus from Chapter II, already captured in the Chapter I/II section above) and classifies major/minor sentence types and simple/compound sentences. Checked against the whole-book coverage already assembled in Chapters I–VI above (no external established file needed re-checking here, since this chapter's content is entirely Lee's own closing synthesis of apparatus introduced earlier in this same book) and against a targeted grep across the full 69-file established Korean corpus for "Intoneme" (zero hits outside this book, confirming the term is unique to Lee), "propositive" (widely covered — ordinary propositive-mood teaching-grammar content, so the *basic* existence of a propositive mood is not re-extracted here), and "minor sentence" (two hits, both in Chang's *LOALL* — `067`/`069` — but Chang's "minor sentence type" means something different: a fifth/sixth *sentence-final-ending* category alongside declarative/interrogative/imperative/propositive, e.g. suspective *-ci*, exclamatory *-kwun*, promissory *-(u)ma*. Lee's "minor sentence" is a structurally different concept — any sentence that does *not* include a final clause at all — so this is not actually redundant, just a terminology false-positive, confirmed by direct comparison).
- **Skipped as redundant:** the bare existence of the four sentence moods (declarative/interrogative/imperative/propositive) and of simple/compound sentence as categories — these are standard teaching-grammar content covered extensively across the beginner/intermediate course corpus (001-029, 035-046) and are not re-explained here in their generic form.
- **Kept as genuinely new:** Lee's phonological (not semantic or syntactic) definition of "sentence" itself, hinging entirely on his own Intoneme/juncture apparatus (a definition not found framed this way in any other established Korean file); the explicit major-sentence structure formula `(Adv.z.) + (vocat.ph.) + (adv.cl.) + Final Clause + (Pcl.z.)` with its three enumerated marked word-order variants; the finding that **intonation, not just inflectional morphology, is the primary mood-marking channel for modally-neutral endings** (several endings across all five speech styles are ambiguous between two or more moods on form alone, resolved only by which of the four Intonemes accompanies them); the specific, counter-intuitive **exception for the medium-style `-ji` ending**, where the general Q-type/Yes-No-type intonation-marking rule is reversed; the reclassification of many traditionally-labelled "compound sentences" as structurally simple (since Lee's definition counts final clauses, not surface clause count); the register observation that compound sentences correlate with speaker "impatience"/"anxiety" and frequently express semantic contrast between two final clauses; and the Elliptical/Initiating two-way split of minor sentences, with the explicit (and non-obvious) rule that an elliptical minor sentence containing an interrogative element is marked by Intoneme LF/HF (the same as a Q-type major interrogative), not by Intoneme R, even though the general rule for minor sentences otherwise mirrors major-sentence mood-intonation marking.

---

### Vocabulary

Chapter VII is almost entirely Lee's own closing structural/intonational apparatus rather than a source of new lexical items — most of its example sentences reuse vocabulary already captured in the Chapter I–VI sections above or are common items well-attested across the broader teaching-course corpus (skipped here as redundant-sample per the non-redundant-supplement note). Only the genuinely new items — new interjection/vocative-register examples and sentence-final-ending forms not previously tabulated — are kept below.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 저런 jʌlʌn | 'Good gracious!' | interjection (exclamatory, introductory) | colloquial | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | §7.5.2 Exclamatory Type (Initiating minor sentence) worked example, p.194; not present in this same book's own Ch. III interjection inventory (Chapter III section above), a genuinely new item within this book |
| 복동아 bogdoŋa | '(calling to) Bogdong!' — personal name + vocative particle | proper noun + particle (vocative type example) | colloquial | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | §7.5.2 Vocative Type worked example, p.194 — plain-style vocative (personal name + -아 particle, the particle itself already tabulated in the Chapter III section above) |
| 님이여 nim.ijʌ | 'My dear!' | noun (honorific suffix -님) + particle (vocative, formal) | formal | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | §7.5.2 Vocative Type worked example, p.194; register-contrasts directly with 복동아 above — honorific -님 + formal vocative -이여 vs. plain name + -아 |
| -지 -ji (sentence-final) | medium-style sentence-final ending, modally neutral between declarative and interrogative readings on form alone | verb ending (final, medium style) | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | §7.3.2.1 and §7.3.2.2.1, pp.189, 191; extends the Final-Endings paradigm captured in the Chapter IV section above (§4.3.5.1) with the specific exception-to-the-general-intonation-marking-rule behavior detailed in the Grammar points below, not covered there |
| -소 -so | low formal declarative/interrogative/imperative ending, restricted to a Zero-tense C-stem verb; modally neutral | verb ending (final, low formal) | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | §7.3.2.1.1, p.189; a C-stem-conditioned allomorph of the low formal style not separately itemized in the Chapter IV Final-Endings overview |
| -오/-이오 -o/-io | low formal ending, modally neutral across declarative/interrogative/imperative readings | verb ending (final, low formal) | core | — | contemporary (source published 1989) | — | — | grammar_reference | n/a | verified | §7.3.2.1.1, p.189 |

---

### Grammar points

#### 1. Definition of the sentence (§7.1, p.186)

Lee defines "sentence" **phonologically rather than syntactically or semantically**: a stretch of speech that ends with one of the 17 intonation tunes of his own Korean intonation system (cf. the Chapter I/II section's §2.8 Intonation discussion above) and has the potential to be immediately preceded and followed by terminal juncture (cf. §2.7 Juncture, also above). He states this exclusively phonological criterion is deliberately chosen because it is the *only* one uniformly applicable to both major and minor sentence types alike. Under this definition a sentence may consist of a single word, phrase, or clause (final or non-final), or any combination of these — his own example list runs from a bare noun (*dal* 'the moon') through a verb phrase, an adverbial relative clause, and a non-final clause combined with a final clause.

#### 2. Major vs. Minor Sentence (§7.2, p.186)

A **Major Sentence** consists of or includes a final clause; a **Minor Sentence** does not consist of or include a final clause. A major sentence's minimal possible form is a single verb inflected with a final ending (since a lone inflected verb can itself constitute a final clause, cf. §6.1 in the Chapter VI section above).

#### 3. Structure of the Major Sentence (§7.3.1, p.186–188)

A major sentence may optionally include, around its one obligatory Final Clause, up to four further elements in the unmarked order **(Adv.z.) + (vocat.ph.) + (adv.cl.) + Final Clause + (Pcl.z.)** — a sentence adverb, a vocative phrase, a non-final adverbial clause, and a sentence particle, respectively (each cross-referenced to its own earlier chapter: Adv.z. to §3.4.4.5, vocat.ph. to §3.4.5.5, adv.cl. to §6.4.4.1, Pcl.z. to §3.4.5.7 — all already captured in the Chapter III/VI sections above). Three marked (less frequent) orderings are given, each permuting the position of the adverbial clause, sentence particle, or vocative phrase relative to the final clause. Critically, the non-final adverbial clause slot in this formula is not limited to one clause — Lee's own examples show two and three adverbial clauses stacking in sequence before a single final clause (adv.cl.₁, adv.cl.₂, adv.cl.₃), each itself able to carry its own further non-final structure.

#### 4. Major Sentence Categories: four moods and their Intoneme exponents (§7.3.2–7.3.2.4, p.189–191)

Major sentences fall into four categories by the inflectional mood ending on P: **Declarative**, **Interrogative**, **Imperative**, **Propositive** (the endings themselves were tabulated in the Chapter IV section's Final-Endings paradigm, §4.3.5.1). The chapter's genuinely new contribution is cataloguing exactly which endings are **modally ambiguous on form alone** and therefore rely on intonation (the Intoneme system, cf. above) as the real disambiguating signal:

- **Declarative**: marked by Intoneme LF or HF on the sentence's last stress group, with one exception — the medium-style **-ji** ending, which is marked by LF only (never HF) when declarative.
- **Sentences neutral in mood** (§7.3.2.1.1): three identified ending-sets are modally ambiguous without intonation — **-o/-io and -so** (low formal style, ambiguous across declarative/interrogative/imperative), **-a/-ʌ** (medium style, ambiguous across all four moods), and **-ji** (medium style, ambiguous between declarative and interrogative only).
- **Interrogative** (§7.3.2.2): two structurally distinct subtypes. **'Q'-type** includes an overt interrogative element (an interrogative noun like *nu/nugu* 'who', an interrogative adjective like *ʌni* 'which', or an interrogative adverb like *we* 'why' — all already tabulated in the Chapter III section above) and is normally marked by a falling Intoneme (LF/HF). **'Yes/No'-type** has no such interrogative element and is normally marked by Intoneme R (Rise).
- **The -ji exception** (§7.3.2.2.1, a standout finding): for sentences whose P takes the medium-style **-ji** ending specifically, the general Q-type/Yes-No-type intonation assignment is **reversed** — a -ji sentence is marked by Intoneme R when it is Q-type (contrary to the general falling-intonation rule for Q-type), and by Intoneme HF when it is Yes/No-type (contrary to the general Rise rule for Yes/No-type). Lee's minimal pair: *nani 'nʌnjegaji* ('When are you going?', Q-type, Rise) vs. *nani, nʌnjegani* ('When are you going?', segmentally near-identical but a different ending, ordinary falling intonation) — the -ji ending is the one case in the whole mood/intonation system where the normal pairing of interrogative subtype to intonation contour is inverted.
- **Imperative** (§7.3.2.3): also marked by Intoneme LF/HF, like the declarative — distinguished from a declarative reading of the same intoneme by (a) a higher, more abrupt pitch contour and (b) stronger stress, particularly noticeable on the modally-neutral -a/-ʌ ending; where intonation alone fails to disambiguate, situational context is the final arbiter.
- **Propositive** (§7.3.2.4): intonationally **indistinguishable** from the imperative (both take LF/HF plus the same pitch-stress profile) — only context distinguishes them. As a soft cue, Lee notes a modally-neutral propositive sentence frequently includes the pronoun *uli* 'we' as its subject.

#### 5. Simple vs. Compound Sentences (§7.4, p.192–193)

A **simple sentence** consists of a single final clause; a **compound sentence** includes more than one. Lee flags an analytical consequence of his own final-clause-counting definition: many sentences *traditionally* labelled "compound" in other Korean grammars are reclassified here as simple, because they contain only one final clause even when they contain several non-final clauses strung together (e.g. a sentence with three chained adverbial non-final clauses followed by one final clause is, by this definition, simple — not compound). Because of this redefinition, the majority of actual Korean sentences turn out to be simple sentences under Lee's system. True compound sentences (2+ final clauses) are, per Lee, mostly coordinate: the constituent final clauses are linked paratactically in quick succession, joined by either a plus juncture or a tentative juncture (never a terminal juncture, which would instead mark the end of the whole compound sentence) — cf. §2.7 Juncture in the Chapter I/II section above. Lee characterizes most compound sentences as semantically/pragmatically marked by "impatience" or "anxiety" on the speaker's part, and notes that interrogative-type compound sentences in particular frequently set their two final clauses in explicit semantic contrast or opposition (his example: *kuminja, sɛŋsinja* 'Is it a dream or reality?' — two final interrogative clauses juxtaposed without an overt coordinator).

#### 6. Minor Sentences: Elliptical and Initiating types (§7.5–7.5.2, p.193–194)

Minor sentences (lacking any final clause, cf. point 2 above) split into two types:

- **Elliptical type** (§7.5.1): referable back to an implied major sentence containing the same word, phrase, or non-final clause — typically a conversational response to a prior utterance, and paraphrasable by the fuller major sentence it stands in for (Lee's worked examples pair each elliptical minor sentence with its "cf." full major-sentence equivalent, e.g. *sinmun* 'A newspaper.' standing in for *sinmunil bonda* 'I am reading the paper.'). The declarative/interrogative mood distinction still operates in elliptical minor sentences, with intonation as its sole exponent: Intoneme LF/HF for declarative, Intoneme R for interrogative — **except** that an elliptical minor sentence that itself contains an interrogative element (i.e., a Q-type reading) is marked by Intoneme LF/HF, exactly parallel to a Q-type major interrogative sentence, not by Intoneme R. This is the same Q-type/Yes-No-type asymmetry already established for major interrogative sentences (point 4 above), now shown to extend to minor sentences as well — a systematic consistency across major and minor sentence types that Lee makes explicit.
- **Initiating type** (§7.5.2): used to open a discourse and *not* referable to any implied major sentence. Two subtypes: **Exclamatory Type**, expressed by an introductory interjection (cf. §3.4.6 in the Chapter III section above for the response/introductory interjection split; new item 저런 'Good gracious!' tabulated above), and **Vocative Type**, expressed by a personal name, a title, or both, with or without an accompanying vocative particle (cf. §3.4.5.5, also in the Chapter III section — new worked examples 복동아 and 님이여 above illustrate the plain-vs-honorific register contrast within this construction).

---

## Content not extracted: Bibliography, Appendix, and Index (printed pp. 195–216)

The remainder of the physical book was read and deliberately **not** extracted as vocabulary/grammar content, each for the same reason: it is a pure reference-locator or citation list with no glosses, explanations, or example sentences of its own to extract.

- **Bibliography** (printed pp. 195–~208): a standard academic bibliography of secondary sources on Korean and general linguistics (author/title/publisher/year citations only, grouped by topic — Korean Linguistics, English/general-linguistics references, etc.). No extractable linguistic content.
- **Appendix — "Index of Grammatical Suffixes and Endings"** (printed pp. 209–211): a bare locator index pairing each grammatical suffix/ending form (in the book's own Yale-derived romanization, no Hangul, no gloss) with the page number(s) where it is discussed in the body chapters. Every item in this index is already sourced to a specific page captured in one of the seven chapter sections above (Chapters I–VII); the index adds page-location metadata only, not new linguistic content, so it was not separately tabulated.
- **General Index** (printed pp. 213–216): an ordinary English-language subject index (topic + page number), equally a pure locator list with nothing further to extract.

This closes out the book: all narrative/expository content (Chapters I–VII, the entirety of Lee's actual grammatical description) is now captured across this file; only non-prose reference-locator matter remains, by design, unextracted.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes, dialogue blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`.
