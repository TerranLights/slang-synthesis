# Russian — Ю. Г. Овсиенко, *Русский язык для начинающих* / *Russian for Beginners (for English speakers)*

**Source:** Yu. G. Ovsiyenko (Овсиенко Ю. Г.), *Русский язык для начинающих: Учебник (для говорящих
на английском языке)* / *Russian for Beginners*, 15th ed. stereotype, Moscow: Русский язык. Курсы
(Russky Yazyk Kursy), 2008, 472 pp. (© author 1995, © publisher 2006). 475-page scanned PDF
(`source_reference/languages/Russian/Russian Learning Pack [up-to-date as of 2012]/Vol 2 of 3/
01 - Audio Courses, Textbooks, Manuals/03.Русский язык для начинающих - Russian for Beginners.pdf`).

## Extraction method and scoping note

**No text layer, no OCR, no font cipher — pure image scan.** `pdfinfo`/`pdftotext` confirm zero
extractable text on every sampled page; `pdffonts` reports **no embedded fonts at all** (not even a
substitution-cipher font); `pdfimages` shows each page is a single full-page 1-bit CCITT-G4 fax-style
raster image (`ScanKromsator` scan tool). This rules out every decodable-cipher gotcha documented
elsewhere in this corpus — there is no font to decode. Tesseract is installed in this environment but
only its `eng`/`osd` language data is present (no `rus` traineddata), and installing one was not
possible (no root/dpkg-lock access in this sandbox). This source is therefore genuinely vision-only,
with no cheaper fallback available.

**Scoping decision (non-redundant-supplement pattern, applied aggressively per dispatch
instructions):** This is a standard 33-unit elementary course (Preface states explicitly: ~2,000
words/phrases total vocabulary, built around noun/adjective/pronoun declension in the singular and
plural, verbal aspect, verbs of motion, the conditional mood, direct/indirect speech, participles and
verbal adverbs — see Contents, pp. 5–11). Every one of these grammar points is already documented in
this corpus in substantially greater systematic depth by `002/003` (Wade), `006/007` (Timberlake),
`004` (SEELRC), `069–072` (Dunn & Khairov), `012/013` (Schaum's), and others. Rather than vision-read
all 475 pages (infeasible at this source's page count with no OCR fallback), this extraction:

1. Read the front matter (title page, Preface, full Contents, pp. 1–12) to map the book's actual
   structure and confirm topical overlap.
2. Sampled the phonetics/vowel-reduction introduction (pp. 16–17) — confirmed standard IPA-style
   vowel-reduction description, already covered in comparable or greater depth by `004` (SEELRC) and
   the Timberlake reference grammar. **Skipped as redundant.**
3. Sampled several unit reading texts and their proverb/aphorism call-outs (pp. 130, 250, 367) —
   confirmed standard pedagogical narrative texts and generic proverb sets tied to the unit's grammar
   topic (e.g. motion-verb proverbs at Unit 21, friendship proverbs at Unit 30), not distinct from
   material already captured via other sources' own proverb sections. **Skipped as redundant** (no
   individual proverb sampled was novel enough, or register/dialect-tagged, to justify inclusion).
4. Sampled the back-matter Russian–English glossary tail (pp. 471–472, letters Ф–Я) — a plain
   ~2,000-entry alphabetical word list with no register/dialect tags, no different in kind from the
   glossaries already fully captured in `041`, `044`, `068`, and others. **Skipped as redundant.**
5. Read in full the **"Russian Conventional Speech Clichés"** section (pp. 429–436, a dedicated
   8-part pragmatic-formula appendix) — this is the one section of the book that stood out as a
   genuinely distinct, self-contained register resource, structured differently from this corpus's
   existing address-form material (`041`'s 5-tier address-form scale, `063`'s etiquette phrasebook):
   here each of 8 communicative functions (greetings/leave-taking, forms of address, requests,
   agreement/refusal, apology, regret/sympathy, gratitude, congratulations) is given as an explicit
   **formal-register phrase followed by its informal/friendly counterpart**, consistently labelled
   "(informal, friendly)" — a clean, systematic formal↔informal pairing per pragmatic function rather
   than a single graded scale. **Kept as the extraction's real contribution** — see Vocabulary table
   below.
6. The "Key to the Exercises" (pp. 437–452) is pure drill-answer text with no new
   vocabulary/grammar content of its own (same pattern as `048`'s answer key) — **not extracted**.
   The "Pictorial Vocabulary" (concrete-noun picture dictionary, pp. 28–42) was not sampled in detail;
   it is, per the book's own Preface, low-frequency concrete-object vocabulary of the same kind
   already covered by this corpus's many thematic-vocabulary sources — **treated as low-priority and
   skipped** under this pass's time budget, flagged here as a known, explicit gap rather than silently
   dropped.

**No vision-reading marginalia risk found** in any sampled page — this appears to be a clean
first-print scan (no handwriting, no answer-filling), consistent with the CCITT-G4 fax-style
full-page raster capture.

## Vocabulary

Drawn from the "Russian Conventional Speech Clichés" section (pp. 429–436). Each row is a short,
individually-illustrative fixed formula (not a bulk reproduction of the source's lists — the full
lists under each function run 5–15 lines each; only representative entries are quoted here).

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Здра́вствуйте! | Hello! (formal/plural) | interjection (formula) | core | — | contemporary (source published 1995/2008) | — | — | grammar_reference | n/a | verified | §1 Greetings; formal counterpart of Привет |
| Приве́т! | Hi! | interjection (formula) | colloquial | — | contemporary (source published 1995/2008) | — | — | grammar_reference | n/a | verified | Source itself labels this "(informal, friendly)" |
| До свида́ния! | Goodbye! | interjection (formula) | core | — | contemporary (source published 1995/2008) | — | — | grammar_reference | n/a | verified | §1 Leave-taking, formal |
| Пока́! | Bye! | interjection (formula) | colloquial | — | contemporary (source published 1995/2008) | — | — | grammar_reference | n/a | verified | Source-labeled "(informal, friendly)" counterpart of До свидания |
| Молодо́й челове́к! | Young man! (to attract a stranger's attention) | phrase (address formula) | core | — | contemporary (source published 1995/2008) | — | — | grammar_reference | n/a | verified | §2, addressing a male stranger |
| Де́вушка! | Miss!/Young woman! (to attract a stranger's attention) | phrase (address formula) | core | — | contemporary (source published 1995/2008) | — | — | grammar_reference | n/a | verified | §2, addressing a female stranger |
| Бу́дьте добры́ | Would you be so kind (as to...) | phrase (request formula) | formal | — | contemporary (source published 1995/2008) | — | — | grammar_reference | n/a | verified | §3, formal/polite request opener |
| Бу́дь добр | Would you be so kind (as to...) [singular/informal] | phrase (request formula) | colloquial | — | contemporary (source published 1995/2008) | — | — | grammar_reference | n/a | verified | §3, source-labeled "Informal, Friendly" counterpart |
| С удово́льствием | With pleasure (i.e. "gladly") | phrase (agreement formula) | core | — | contemporary (source published 1995/2008) | — | — | grammar_reference | n/a | verified | §4, agreeing to a request/invitation |
| К сожале́нию, не могу́ | Unfortunately, I can't | phrase (refusal formula) | core | — | contemporary (source published 1995/2008) | — | — | grammar_reference | n/a | verified | §4, polite refusal |
| Винова́т / Винова́та | My fault (m./f. forms) | phrase (apology formula) | colloquial | — | contemporary (source published 1995/2008) | — | — | grammar_reference | n/a | verified | §5, terse self-blaming apology |
| Ты́сячу извине́ний за всё! | A thousand apologies for everything! | phrase (apology formula, emphatic) | core | — | contemporary (source published 1995/2008) | — | — | grammar_reference | n/a | verified | §5, emphatic formal apology |
| Не сто́ит (беспоко́иться) | Don't mention it / No need (to worry) | phrase (reaction formula) | core | — | contemporary (source published 1995/2008) | — | — | grammar_reference | n/a | verified | §5, reaction to an apology; reused verbatim as a reaction to gratitude in §7 |
| Пустяки́! (Каки́е пустяки́!) | Nonsense!/It's nothing! | phrase (reaction formula) | colloquial | — | contemporary (source published 1995/2008) | — | — | grammar_reference | n/a | verified | §5 and §7, dismissive-but-friendly reaction to apology or thanks |
| Мне о́чень жаль | I'm very sorry (about it) | phrase (sympathy formula) | core | — | contemporary (source published 1995/2008) | — | — | grammar_reference | n/a | verified | §6 Expressing regret/sympathy |
| Сочу́вствую вам (тебе́) | I sympathize with you (formal/informal) | phrase (sympathy formula) | core | — | contemporary (source published 1995/2008) | — | — | grammar_reference | n/a | verified | §6 |
| От всей души́ благодарю́ вас | I thank you from the bottom of my heart | phrase (gratitude formula, emphatic) | formal | — | contemporary (source published 1995/2008) | — | — | grammar_reference | n/a | verified | §7, most emphatic register tier of the gratitude set |
| Не́ за что | Don't mention it / You're welcome | phrase (reaction formula) | core | — | contemporary (source published 1995/2008) | — | — | grammar_reference | n/a | verified | §7, reaction to thanks |
| Поздравля́ю вас (тебя́) с пра́здником! | Congratulations on the holiday! | phrase (congratulation formula) | core | — | contemporary (source published 1995/2008) | — | — | grammar_reference | n/a | verified | §8, generic congratulation template, slot-fillable (с Но́вым го́дом, с днём рожде́ния, etc.) |
| Бу́дьте счастли́вы, здоро́вы! | Be happy and healthy! | phrase (good-wishes formula) | core | — | contemporary (source published 1995/2008) | — | — | grammar_reference | n/a | verified | §8, closing well-wish |

## Grammar points

No new grammar points. Every grammatical topic covered by this course (six-case declension in
singular and plural, verbal aspect, verbs of motion, the conditional mood, direct/indirect speech,
participles and verbal adverbs, personal/possessive/demonstrative pronoun declension) duplicates
material already documented — at greater systematic depth, with fuller paradigm tables — by this
corpus's existing flagship grammars (`002/003`, `004`, `006/007`, `069–072`, `012/013`). Consistent
with the coverage rule's non-redundant-supplement instruction, no grammar-point subsections are
repeated here.

### Register mechanism note (for `analysis/`, not canon)

This source's "Russian Conventional Speech Clichés" appendix is structured as a **systematic
formal↔informal binary pairing per pragmatic function**, rather than a single graded formality scale
(contrast `041`'s 5-tier address-form scale). For 7 of its 8 functions, the source gives a fully
formal register version first, then an explicitly source-labeled "(informal, friendly)" counterpart
covering the same communicative act (e.g. Здравствуйте!/Привет!; До свидания!/Пока!; Будьте
добры.../Будь добр...). This is a clean, reusable template for the eventual mechanics-analysis phase:
register variation in Russian civility formulas is not just lexical substitution but a paired-formula
system keyed to a small fixed set of pragmatic functions (greeting, leave-taking, address, request,
agreement/refusal, apology, sympathy, gratitude, congratulation) — worth cross-referencing against
`063`'s two-axis formality×intensity template and `041`'s address-form scale when `analysis/` work on
Russian register mechanics begins.

## Known gaps (explicitly flagged)

- Pictorial Vocabulary section (pp. 28–42, concrete-noun picture dictionary) — not sampled; low
  priority given extensive existing thematic-vocabulary coverage in this corpus, but not confirmed
  redundant by direct inspection either. Flagged as an honest gap, not silently skipped.
- The 33 units' own reading texts, dialogues, exercises, and scattered proverb/aphorism call-outs were
  spot-sampled only (3 pages) rather than read exhaustively; a full read is not expected to be
  cost-effective given the confirmed pattern of standard pedagogical content, but this is a sampling
  decision, not an exhaustive-coverage claim.
- Key to the Exercises (pp. 437–452) — confirmed answer-key-only content by its heading and format,
  not individually vision-read line-by-line.
