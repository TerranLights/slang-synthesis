# Russian — Established Vocabulary/Grammar: The Big Silver Book of Russian Verbs, Verbs 382–555 (Part 3 of 3)

**Source:** Jack E. Franke, Ph.D., *The Big Silver Book of Russian Verbs: 555 Fully Conjugated Verbs*
(McGraw-Hill, 2004/2007 printing). PDF pages 451–647 of `55.The Big Silver Book of Russian Verbs.pdf`,
covering the book's own printed pages 382–555 (verbs #382 through #555, the final third of the
555-verb main body). PDF pages 648–673 (the book's own pages ~642–667, comprising the "Exercises"
drill section, the English-Russian Verb Index, the Irregular Verb Index, and the Russian Verb Index)
were inspected and **excluded as back matter** per the coverage rule — see the note below.

**Coverage note.** Sibling chunks cover PDF pages 1–225 (`established/016`) and 226–450
(`established/017`); this chunk covers the tail, PDF pages 451–647 (printed pages 382–555), the last
174 of the book's 555 fully conjugated verbs, one verb per printed page. Every one of the 174 verbs
in this range is captured in the Vocabulary table below (verified against the source: pages 382–555
with zero gaps). Grammar content in this range is overwhelmingly the *continued application* of a
conjugation-class-numbering system (types 1–6 plus "irregular") that this book establishes in its own
front matter, almost certainly already captured by `016_big_silver_book_of_russian_verbs_part1.md`;
this file does not re-derive that system, and instead lists in the **Grammar points** section only the
handful of genuinely distinctive grammatical phenomena that recur across this specific page range
(defective/3rd-person-only verbs, bi-aspectual verbs, imperfectiva tantum verbs, the motion-verb
indeterminate/determinate/perfective triple, a reflexive-meaning-shift footnote, and the book's own
"Top 50 Verb" frequency flag). Per copyright discipline, full paradigm tables (present/past/future/
subjunctive/participle/verbal-adverb/imperative forms) and the extensive Usage/Idioms/Proverbs example
sentences on each page are **not reproduced** — the Vocabulary table below captures the aspectual
pair, gloss, conjugation class, and stem, which is the reusable lexical/morphological data; illustrative
examples are paraphrased or omitted, never bulk-quoted.

**Back matter excluded (checked directly, not assumed):**
- PDF 648–653 — "Exercises" (fill-in-the-blank present/past/future drills). Skipped per the coverage
  rule's instruction to skip repeated drill exercises that introduce no new vocabulary/grammar.
- PDF 654–659 — "English-Russian Verb Index" (alphabetical-by-English-gloss cross-reference back to
  the 555 verbs already conjugated in the book's main body — not new content).
- PDF 660–662 — "Irregular Verb Index" (a page-number lookup list for irregular forms, again a
  cross-reference into content already captured on its home page, not new vocabulary/grammar).
- PDF 663–673 — "Russian Verb Index" (the master alphabetical-by-Russian-infinitive index with English
  glosses and page numbers — again a pure navigational index of the same 555 verbs).

None of this back matter was extracted as vocabulary; it is pure index/drill material with no content
beyond what its own home page in the main body already provides.

**PDF-extraction note (font-substitution/stress-mark cipher, confirmed).** This PDF has a genuine text
layer (`pdftotext` works cleanly, no Cyrillic-glyph-substitution cipher of the ЙЦУКЕН-keyboard or
cp1251-as-latin1 kind was found in this range). However, a **stress-mark-only corruption** was found:
the printed book places an acute stress mark over the stressed vowel of many headwords (standard
practice in Russian-as-a-foreign-language texts), and `pdftotext` extracts these as raw C0 control
characters (observed code points include U+0010, U+0011, U+0012, U+001D) inserted directly into the
Cyrillic word, immediately after the stressed vowel — e.g. `рабо<U+0011>тать` for рабо́тать (stress
on second o), `тре<U+0011>бовать` for тре́бовать, `говори<U+0011>ть` for говори́ть. This was verified
against more than 20 known standard Russian stress placements across this page range (работать,
требовать, говорить, видеть, плакать, печь, нести — all book-internal "stem: ... (like X)"
cross-reference forms — plus dozens of individual verb headwords) and is fully consistent: every
occurrence sits exactly where the standard stress mark belongs, never elsewhere. This is a corrupted
diacritic, not corrupted lexical content, so **all control characters were stripped from Term/Notes
text below**; no stress information is retained in this file (the source's own stress marks can be
recovered from any standard Russian dictionary if needed later). No handwritten marginalia was found
in this range — the source PDF text layer is a clean digital typeset extraction, not a scan, so the
vision-reading guard does not apply here.

**"TOP 50 VERB" flag (genuine source-marked frequency data).** The book itself flags 11 of these 174
verbs with an explicit "TOP 50 VERB ☞" banner and repeats their full conjugation page a second time
with an added "Idioms" (or "Other Uses") section of extra idiomatic examples. This is real
source-supplied frequency-tier information (not inferred from lesson ordering), so these 11 verbs are
marked `high (book's own "Top 50 Verb" list)` in the Weight/Frequency column: проходить/пройти (396),
пускать/пустить (401), сбивать/сбить (438), сидеть/посидеть (441), смотреть(ся)/посмотреть(ся) (450),
собирать(ся)/собрать(ся) (453), стоять/постоять (478), убивать/убить (505), учить(ся)/научить(ся)
(539), хватать/хватить (542), ходить/идти/пойти (543). (The duplicate repeat page for each was not
double-counted in the table below — one row per verb.)

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| провожать/проводить | to accompany, guide | verb (impf./pf. aspectual pair) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.382; type 1 verb in imp./perf. form type 2; stem провожай-/проводи- |
| продавать(ся)/продать(ся) | to sell | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.383; irregular verb in imp. & perf.; stem продавай+(ся)/irreg. |
| продолжать(ся)/продолжить(ся) | to continue | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.384; type 1 verb in imp./perf. form type 2; stem продолжай+(ся)/продолжи+(ся) |
| проезжать/проехать | to drive past, ride (past, through) | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.385; type 1 verb, perf. form irregular; stem проезжай-/irreg. |
| проигрывать/проиграть | to lose | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.386; type 1 verb (like работать); stem проигрывай-/проиграй- |
| производить/произвести | to produce | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.387; type 2 verb, д-ж stem change / perf. form type 5; stem производи-/произвёд- |
| произносить/произнести | to pronounce, utter | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.388; type 2 verb, с-ж stem change / perf. form type 5; stem произноси-/произнёс- |
| происходить/произойти | to happen, occur | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.389; type 2 verb, perf. form irregular; stem происходи-/irreg. |
| пропадать/пропасть | to disappear, be missing | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.390; type 1 verb, perf. form type 5; stem пропадай-/пропад-; idiom «Пропади ты пропадом!» flagged colloquial |
| пропускать/пропустить | to miss, leave out; to let | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.391; type 1 verb, perf. form type 2; stem пропускай-/пропусти- |
| просить/попросить | to request, ask | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.392; type 2 verb (like видеть); stem проси-/попроси- |
| простывать/простыть | to get cold | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.393; type 1 verb, perf. form irregular; stem простывай-/irreg. |
| простужаться/простудиться | to catch a cold | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.394; type 1 verb, perf. form type 2; stem простужай+ся/простуди+ся |
| просыпаться/проснуться | to wake up | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.395; type 1 verb, perf. form type 3; stem просыпай+ся/просну+ся |
| проходить/пройти | to go (through, past), pass (on foot) | verb | core | high (book's own "Top 50 Verb" list) | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.396; type 2 verb, perf. form irregular; stem проходи-/irreg. |
| прощать/простить | to forgive, excuse | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.397; type 1 verb, perf. form type 2; stem прощай-/прости- |
| прыгать/прыгнуть | to jump | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.398; type 1 verb, perf. form type 3; stem прыгай-/прыгну- |
| прятать(ся)/спрятать(ся) | to hide | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.399; type 3 verb (like плакать); stem прята+(ся)/спрята+(ся) |
| пугать(ся)/испугать(ся) | to scare, frighten | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.400; type 1 verb (like работать); stem пугай+(ся)/испугай+(ся) |
| пускать/пустить | to allow, let; to shoot | verb | core | high (book's own "Top 50 Verb" list) | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.401; type 1 verb, perf. form type 2; stem пускай-/пусти- |
| путешествовать | to travel | verb (imperfective only) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.402; type 4 verb (like требовать), no perf.; stem путешествова- |
| пытаться/попытаться | to attempt, try | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.403; type 1 verb (like работать); stem пытай+ся/попытай+ся |
| работать/поработать | to work | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.404; type 1 verb, the book's own paradigm-class exemplar ("like работать"); stem работай-/поработай- |
| радовать(ся)/обрадовать(ся) | to please, make happy | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.405; type 4 verb (like требовать); stem радова+(ся)/обрадова+(ся) |
| разбивать(ся)/разбить(ся) | to break | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.406; type 1 verb, perf. form irregular; stem разбивай+(ся)/раз|бьй+(ся) |
| развивать/развить | to develop | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.407; type 1 verb, perf. form irregular; stem развивай-/раз|вьй- |
| разводить(ся)/развести(сь) | to take, mix; to divorce | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.408; type 2 verb, perf. form type 5 |
| разговаривать | to converse, discuss, talk | verb (imperfective; perf. rarely used) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.409; type 1 verb (like работать); stem разговаривай- |
| раздаваться/раздаться | to be heard; to ring out | verb (3rd person only) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.410; irregular verb in imp. & perf., 3rd person only (defective verb — see Grammar points); stem раздавай+(ся)/irreg. |
| раздевать(ся)/раздеть(ся) | to undress, get undressed | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.411; type 1 verb, perf. form irregular; stem раздевай+(ся)/разден+(ся) |
| разделять(ся)/разделить(ся) | to divide | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.412; type 1 verb, perf. form type 2; stem разделяй+(ся)/раздели+(ся) |
| разрабатывать/разработать | to work out, cultivate | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.413; type 1 verb (like работать); stem разрабатывай-/разработай- |
| разрешать/разрешить | to allow, permit | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.414; type 1 verb, perf. form type 2; stem разрешай-/разреши- |
| разрушать/разрушить | to destroy | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.415; type 1 verb, perf. form type 2; stem разрушай-/разруши- (note: source's own aspectual-pair header line mislabels this "разрешать/разрешить," an apparent source typo — the stem and gloss unambiguously match разрушать/разрушить, "to destroy") |
| ранить/ранить | to wound, injure, hurt | verb (bi-aspectual — see Grammar points) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.416; type 2 verb (like говорить); stem рани-/рани- (identical imp./pf. stem) |
| рассказывать/рассказать | to tell, say | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.417; type 1 verb, perf. form type 3; stem рассказывай-/рассказа- |
| рассматривать/рассмотреть | to examine | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.418; type 1 verb, perf. form type 2; stem рассматривай-/рассмотре- |
| расспрашивать/расспросить | to question, inquire | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.419; type 1 verb, perf. form type 2; stem расспрашивай-/расспроси- |
| расстраиваться/расстроиться | to be upset, break down | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.420; type 1 verb, perf. form type 2; stem расстраивай+ся/расстрой+ся |
| рассчитывать/рассчитать | to calculate | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.421; type 1 verb (like работать); stem рассчитывай-/рассчитай- |
| расти/вырасти | to grow, grow up | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.422; type 5 verb (like нести); stem irreg./irreg. |
| расходиться/разойтись | to disperse, separate | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.423; type 2 verb, perf. form irregular; stem расходи+(ся)/irreg. |
| рвать(ся)/порвать(ся) | to tear; to vomit; to crave | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.424; type 3 verb (like плакать); stem рва+(ся)/порва+(ся) |
| ревновать/приревновать | to be jealous | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.425; type 4 verb (like требовать); stem ревнова-/приревнова- |
| регистрировать/зарегистрировать | to register | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.426; type 4 verb (like требовать); stem регистрирова-/зарегистрирова- |
| резать/разрезать | to cut | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.427; type 3 verb (like плакать), з-ж stem change; stem реза-/разреза- |
| рекомендовать/порекомендовать | to recommend | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.428; type 4 verb (like требовать); stem рекомендова-/порекомендова- |
| ремонтировать/отремонтировать | to repair | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.429; type 4 verb (like требовать); stem ремонтирова-/отремонтирова- |
| решать/решить | to decide, solve | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.430; type 1 verb, perf. form type 2; stem решай-/реши- |
| рисковать/рискнуть | to risk, take chances | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.431; type 4 verb, perf. form type 3; stem рискова-/рискну- |
| рисовать/нарисовать | to draw | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.432; type 4 verb (like требовать); stem рисова-/нарисова- |
| рождать(ся)/родить(ся) | to bear, be born | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.433; type 1 verb, perf. form type 2; stem рождай+(ся)/роди+(ся) |
| рубить/срубить | to chop | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.434; type 2 verb (like говорить); stem руби-/сруби- |
| ругать/отругать | to swear, curse, scold | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.435; type 1 verb (like работать); stem ругай-/отругай- |
| садиться/сесть | to sit down | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.436; type 2 verb, perf. form irregular, type 5 endings; stem сади+(ся)/irreg. |
| сажать/посадить | to plant, seat | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.437; type 1 verb, perf. form type 2; stem сажай-/посади- |
| сбивать/сбить | to knock down, reduce | verb | core | high (book's own "Top 50 Verb" list) | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.438; type 1 verb, perf. form irregular; stem сбивай-/с|бьй- |
| сдавать(ся)/сдать(ся) | to hand over, deliver; to surrender | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.439; irregular verb in imp. & perf.; stem сдавай+(ся)/irreg. |
| сердиться/рассердиться | to anger, get angry | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.440; type 2 verb (like говорить); stem серди+ся/рассерди+ся |
| сидеть/посидеть | to sit, be sitting | verb | core | high (book's own "Top 50 Verb" list) | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.441; type 2 verb (like говорить); stem сиде-/посиде- |
| скрывать/скрыть | to hide | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.442; type 1 verb, perf. form irregular; stem скрывай-/скрой- |
| скучать/поскучать | to miss | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.443; type 1 verb (like работать); stem скучай-/поскучай- |
| следовать/последовать | to follow | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.444; type 4 verb (like требовать); stem следова-/последова- |
| служить/послужить | to serve | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.445; type 2 verb (like видеть); stem служи-/послужи- |
| случаться/случиться | to happen, occur | verb (3rd person only) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.446; type 1 verb, perf. form type 2, 3rd person only (defective verb — see Grammar points); stem случай+ся/случи+ся |
| слушать(ся)/послушать(ся) | to listen | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.447; type 1 verb (like работать); stem слушай+(ся)/послушай+(ся) |
| слышать/услышать | to hear, be heard | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.448; type 2 verb (like видеть); stem слыша-/услыша- |
| смеяться/посмеяться | to laugh | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.449; type 3 verb (like плакать); stem смея+ся/посмея+ся |
| смотреть(ся)/посмотреть(ся) | to watch, look at | verb | core | high (book's own "Top 50 Verb" list) | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.450; type 2 verb (like говорить); stem смотре-/посмотре- |
| смущать(ся)/смутить(ся) | to embarrass, confuse | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.451; type 1 verb, perf. form type 2; stem смущай+(ся)/смути+(ся) |
| снимать(ся)/снять(ся) | to take, remove; to rent | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.452; type 1 verb, perf. form irregular; stem снимай+(ся)/сним+(ся) |
| собирать(ся)/собрать(ся) | to gather, collect; to plan | verb | core | high (book's own "Top 50 Verb" list) | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.453; type 1 verb, perf. form irregular; stem собирай+(ся)/соб/ра+(ся) |
| совать(ся)/сунуть(ся) | to stick, thrust | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.454; type 4 verb, perf. form type 3; stem суй+(ся)/суну+(ся) |
| совершать/совершить | to commit, perform | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.455; type 1 verb, perf. form type 2; stem совершай-/соверши- |
| советовать(ся)/посоветовать(ся) | to advise, suggest | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.456; type 4 verb (like требовать); stem советова+(ся)/посоветова+(ся) |
| соглашаться/согласиться | to agree | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.457; type 1 verb, perf. form type 2; stem соглашай+ся/согласи+ся |
| соединять/соединить | to unite, connect | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.458; type 1 verb, perf. form type 2; stem соединяй-/соедени- |
| создавать/создать | to create | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.459; irregular verb in imp. & perf.; stem создавай-/irreg. |
| сомневаться | to doubt | verb (perf. form not used) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.460; type 1 verb, perf. form not used (imperfectiva tantum); stem сомневай+ся |
| сообщать/сообщить | to report, inform | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.461; type 1 verb, perf. form type 2; stem сообщай-/сообщи- |
| составлять(ся)/составить(ся) | to put together, assemble | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.462; type 1 verb, perf. form type 2; stem составляй+(ся)/состави+(ся) |
| состоять(ся) | to consist of; to take place | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.463; type 2 verb (like говорить), no perf.; stem состоя+(ся); source's own footnote: non-reflexive = "to consist of," reflexive = "to take place" — see Grammar points |
| сохранять/сохранить | to preserve, maintain | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.464; type 1 verb, perf. form type 2; stem сохраняй-/сохрани- |
| спасать/спасти | to save | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.465; type 1 verb, perf. form type 5; stem спасай-/спас- |
| спать/поспать | to sleep | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.466; type 2 verb (like говорить); stem irreg./irreg. |
| спешить/поспешить | to hurry, rush | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.467; type 2 verb (like говорить); stem спеши-/поспеши- |
| спорить/поспорить | to argue | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.468; type 2 verb (like говорить); stem спори-/поспори-; fixed expression «не спеша» (unhurriedly) listed under "Other Uses" |
| спрашивать/спросить | to ask (a question) | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.469; type 1 verb, perf. form type 2; stem спрашивай-/спроси- |
| спускать(ся)/спустить(ся) | to lower, descend | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.470; type 1 verb, perf. form type 2; stem спускай+(ся)/спусти+(ся) |
| сравнивать(ся)/сравнить(ся) | to compare | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.471; type 1 verb, perf. form type 2; stem сравнивай+(ся)/сравни+(ся) |
| ссориться/поссориться | to argue, quarrel | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.472; type 2 verb (like говорить); stem ссори+ся/поссори+ся |
| ставить/поставить | to place (upright) | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.473; type 2 verb (like говорить); stem стави-/постави- |
| становиться/стать | to become; to begin | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.474; type 2 verb, perf. form irregular; stem станови+(ся)/стан- |
| стараться/постараться | to attempt, try | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.475; type 1 verb (like работать); stem старай+ся/постарай+ся |
| стесняться/постесняться | to be shy, feel awkward | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.476; type 1 verb, perf. form type 2; stem стесняй+ся/постесняй+ся |
| стоить | to be worth | verb (imperfective only) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.477; type 2 verb (like говорить), no perf.; stem стои- |
| стоять/постоять | to stand, be standing | verb | core | high (book's own "Top 50 Verb" list) | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.478; type 2 verb (like говорить); stem стоя-/постоя- |
| страдать/пострадать | to suffer | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.479; type 1 verb (like работать); stem страдай-/пострадай- |
| стрелять(ся)/стрельнуть | to shoot | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.480; type 1 verb, perf. form type 3; stem стреляй+(ся)/стрелну- |
| стремиться | to strive | verb (imperfective only) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.481; type 2 verb (like говорить), no perf.; stem стреми+ся |
| строить(ся)/построить(ся) | to build, be built | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.482; type 2 verb (like говорить); stem строй+(ся)/построй+(ся) |
| стучать/постучать | to knock | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.483; type 2 verb (like говорить); stem стуча-/постуча- |
| судить(ся) | to judge; to be judged | verb (imperfective only) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.484; type 2 verb (like говорить), д-ж stem change, no perf.; stem суди+(ся) |
| существовать | to exist | verb (imperfective only) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.485; type 4 verb (like требовать), no perf.; stem существова- |
| схватывать(ся)/схватить(ся) | to seize | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.486; type 1 verb, perf. form type 2; stem схватывай+(ся)/схвати+(ся) |
| сходить(ся)/сойти(сь) | to go down, descend | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.487; type 2 verb, perf. form irregular; stem сходи+(ся)/irreg. |
| считать/посчитать | to consider | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.488; type 1 verb (like работать); stem считай-/посчитай- |
| съездить | to make a trip | verb (perfective only) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.489; type 2 verb (like говорить), perf. only; stem съезди- |
| танцевать/станцевать | to dance | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.490; type 4 verb (like требовать); stem танцева-/станцева- |
| таскать/тащить/потащить | to pull | verb (indeterminate/determinate/perfective triple — see Grammar points) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.491; type 1 verb in indef./def. & perf. forms type 2; stem таскай-/тащи-/потащи- |
| терпеть/потерпеть | to endure | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.492; type 2 verb (like говорить); stem терпе-/потерпе- |
| терять/потерять | to lose | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.493; type 1 verb (like работать); stem теряй-/потеряй- |
| течь/потечь | to flow | verb (3rd person only) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.494; type 6 verb (like печь), 3rd person only (defective verb — see Grammar points); stem irreg./irreg. |
| тонуть/утонуть | to sink, drown | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.495; type 3 verb (like плакать); stem тони-/утони- |
| торопиться/поторопиться | to hurry, rush | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.496; type 2 verb (like говорить); stem торопи+ся/поторопи+ся |
| тошнить/затошнить | to be nauseous | verb (3rd person only) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.497; type 2 verb (like говорить), 3rd person only (defective verb — see Grammar points); stem тошни-/затошни- |
| тратить/потратить | to spend | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.498; type 2 verb (like говорить), т-ч stem change; stem трати-/потрати- |
| требовать/потребовать | to demand, insist | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.499; type 4 verb, the book's own paradigm-class exemplar ("like требовать"); stem требова-/потребова- |
| тренировать/натренировать | to train | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.500; type 4 verb (like требовать); stem тренирова-/натренирова- |
| трудиться/потрудиться | to labor, work | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.501; type 2 verb (like говорить); stem irreg./irreg. |
| тянуть(ся)/потянуть(ся) | to pull; to extend | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.502; type 3 verb (like плакать); stem тяну+(ся)/потяну+(ся) |
| убегать/убежать | to run away | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.503; type 1 verb, perf. form irregular; stem убегай-/irreg. |
| убеждать(ся)/убедить(ся) | to convince | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.504; type 1 verb, perf. form type 2; stem убеждай+(ся)/убеди+(ся) |
| убивать/убить | to kill | verb | core | high (book's own "Top 50 Verb" list) | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.505; type 1 verb, perf. form irregular; stem убивай-/убьй- |
| убирать/убрать | to remove, clean | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.506; type 1 verb, perf. form irregular; stem убирай-/уб|ра- |
| уважать | to respect | verb (imperfective only) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.507; type 1 verb (like работать), no perf.; stem уважай- |
| увеличивать(ся)/увеличить(ся) | to increase | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.508; type 1 verb, perf. form type 2; stem увеличивай+(ся)/увеличи+(ся) |
| увлекать(ся)/увлечь(ся) | to interest, be keen on | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.509; type 1 verb, perf. form type 6; stem увлекай+(ся)/увлёк+(ся) |
| увольнять/уволить | to dismiss, fire | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.510; type 1 verb, perf. form type 2; stem увольняй-/уволи- |
| угадывать/угадать | to guess | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.511; type 1 verb (like работать); stem угадывай-/угадай- |
| уговаривать/уговорить | to persuade | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.512; type 1 verb, perf. form type 2; stem уговаривай-/уговори- |
| угощать/угостить | to treat | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.513; type 1 verb, perf. form type 2; stem угощай-/угости- |
| удаваться/удаться | to succeed | verb (3rd person only) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.514; irregular verb in imp. & perf., 3rd person only (defective verb — see Grammar points); stem удавай+ся/irreg. |
| ударять/ударить | to strike, hit | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.515; type 1 verb, perf. form type 2; stem ударяй-/удари- |
| удивлять(ся)/удивить(ся) | to amaze, be surprised | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.516; type 1 verb, perf. form type 2; stem удивляй+(ся)/удиви+(ся) |
| уезжать/уехать | to leave (by car) | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.517; type 1 verb, perf. form irregular; stem уезжай-/irreg. |
| ужинать/поужинать | to have supper | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.518; type 1 verb (like работать); stem ужинай-/поужинай- |
| узнавать/узнать | to recognize | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.519; irregular verb in imp., perf. form type 1; stem узнавай-/узнай- |
| указывать/указать | to point, indicate, mention | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.520; type 1 verb, perf. form type 3; stem указывай-/указа- |
| улыбаться/улыбнуться | to smile | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.521; type 1 verb, perf. form type 3; stem улыбай+ся/улыбну+ся |
| уменьшать(ся)/уменьшить(ся) | to reduce, decrease | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.522; type 1 verb, perf. form type 2; stem уменьшай+(ся)/уменьши+(ся) |
| уметь/суметь | to know how, be able | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.523; type 1 verb (like работать); stem умей-/сумей- |
| умирать/умереть | to die | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.524; type 1 verb, perf. form irregular; stem умирай-/умр- |
| умолять/умолить | to implore | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.525; type 1 verb, perf. form type 2; stem умоляй-/умоли- |
| умываться/умыться | to wash up | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.526; type 1 verb, perf. form irregular; stem умывай+ся/умой+ся |
| уничтожать/уничтожить | to destroy, annihilate | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.527; type 1 verb, perf. form type 2; stem уничтожай-/уничтожи- |
| употреблять/употребить | to use | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.528; type 1 verb, perf. form type 2; stem употребляй-/употреби- |
| управлять(ся) | to rule, operate, govern | verb (imperfective only) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.529; type 1 verb (like работать), no perf.; stem управляй+(ся) |
| успевать/успеть | to have time, manage, make progress | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.530; type 1 verb (like работать); stem успевай-/успей- |
| успокаивать(ся)/успокоить(ся) | to calm down | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.531; type 1 verb, perf. form type 2; stem успокаивай+(ся)/успокой+(ся) |
| уставать/устать | to get tired | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.532; irregular verb in imp./perf., stem change to -ай; stem уставай-/устан- |
| устанавливать(ся)/установить(ся) | to install, determine | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.533; type 1 verb, perf. form type 2; stem устанавливай+(ся)/установи+(ся) |
| устраивать(ся)/устроить(ся) | to place, arrange, suit | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.534; type 1 verb, perf. form type 2; stem устраивай+(ся)/устрой+(ся) |
| уступать/уступить | to yield, give in, hand over | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.535; type 1 verb, perf. form type 2; stem уступай-/уступи- |
| ухаживать/поухаживать | to date, look after, care for | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.536; type 1 verb (like работать); stem ухаживай-/поухаживай- |
| уходить/уйти | to leave (on foot) | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.537; type 2 verb, perf. form irregular; stem уходи-/irreg. |
| участвовать/поучаствовать | to participate | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.538; type 4 verb (like требовать); stem участвова-/поучаствова- |
| учить(ся)/научить(ся) | to teach; to study, learn | verb | core | high (book's own "Top 50 Verb" list) | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.539; type 2 verb (like говорить); stem учи+(ся)/научи+(ся) |
| фотографировать/сфотографировать | to photograph | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.540; type 4 verb (like требовать); stem фотографирова-/сфотографирова- |
| хвалить/похвалить | to praise | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.541; type 2 verb (like говорить); stem хвали-/похвали- |
| хватать/хватить | to grab, seize; be enough, suffice | verb | core | high (book's own "Top 50 Verb" list) | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.542; type 1 verb, perf. form type 2; stem хватай-/хвати- |
| ходить/идти/пойти | to go (on foot), walk, wear | verb (indeterminate/determinate/perfective triple — see Grammar points) | core | high (book's own "Top 50 Verb" list) | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.543; type 2 verb in indef./def. & perf. forms irregular; stem ходи-/irreg./irreg. |
| хотеть(ся)/захотеть(ся) | to want | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.544; irregular verb in imp. & perf.; stem irreg./irreg. |
| хранить(ся) | to keep, store, save, preserve | verb (imperfective only) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.545; type 2 verb (like говорить), no perf.; stem храни+(ся) |
| целовать/поцеловать | to kiss | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.546; type 4 verb (like требовать); stem целова-/поцелова- |
| чинить/починить | to fix, repair | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.547; type 2 verb (like говорить); stem чини-/почини- |
| чистить/почистить | to clean | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.548; type 2 verb (like говорить), ст-щ stem change; stem чисти-/почисти- |
| читать/прочитать | to read | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.549; type 1 verb (like работать); stem читай-/почитай- |
| чихать/чихнуть | to sneeze | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.550; type 1 verb, perf. form type 3; stem чихай-/чихну- |
| чувствовать/почувствовать | to feel | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.551; type 4 verb (like требовать); stem чувствова-/почувствова- |
| шить/сшить | to sew | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.552; irregular verb in imp. & perf.; stem шьй-/с|шьй- |
| шуметь | to make noise, be noisy | verb (imperfective only) | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.553; type 2 verb, м-мл stem change, no perf.; stem шуме- |
| шутить/пошутить | to joke | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.554; type 2 verb (like говорить), т-ч stem change; stem шути-/пошути- |
| являться/явиться | to show up, appear, turn out to be | verb | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | p.555; final verb (#555) of the book's main body; type 1 verb, perf. form type 2, в-вл stem change; stem являй+ся/яви+ся |

## Grammar points

### Defective ("3rd person only") verbs

Several verbs in this range are marked by the source as usable only in the 3rd person (i.e., they
lack a full personal paradigm because their subject is typically an impersonal/inanimate "it" or
event, not a human agent): раздаваться/раздаться "to be heard, ring out" (p.410), случаться/
случиться "to happen, occur" (p.446), течь/потечь "to flow" (p.494, 3rd person only "like печь"),
тошнить/затошнить "to be nauseous" (p.497), удаваться/удаться "to succeed" (p.514). This is a
recurring defective-verb category distinct from ordinary full-paradigm verbs and worth tracking
separately from the type-1–6 conjugation classes, since it constrains which persons/numbers a slang
derivative of these verbs could plausibly take.

### Bi-aspectual verbs

ранить/ранить "to wound, injure, hurt" (p.416) is explicitly marked bi-aspectual: the identical form
serves as both the imperfective and perfective, distinguished only by context/other markers, not by a
distinct perfective stem. This is a small, closed class in Russian (other members appear in the
sibling files' page ranges) worth flagging whenever it recurs.

### Imperfectiva tantum ("no perf.") verbs

A number of verbs in this range have no perfective partner at all (imperfectiva tantum), marked "no
perf." by the source: путешествовать "to travel" (p.402), уважать "to respect" (p.507), стоить "to be
worth" (p.477), стремиться "to strive" (p.481), судить(ся) "to judge" (p.484), существовать "to
exist" (p.485), управлять(ся) "to rule/operate/govern" (p.529), хранить(ся) "to keep, store" (p.545),
шуметь "to make noise" (p.553), сомневаться "to doubt" (marked "perf. form not used", p.460). These
verbs denote states, ongoing activities, or conditions rather than bounded events — a semantic pattern
consistent with why they resist perfectivization.

### Motion-verb indeterminate/determinate/perfective triple

Two verbs in this range showcase Russian's distinctive **three-way** motion-verb aspect system
(beyond the ordinary two-way imperfective/perfective split): ходить/идти/пойти "to go (on foot), walk,
wear" (p.543) and таскать/тащить/потащить "to pull" (p.491). The first member of each triple is the
*indeterminate* (habitual/repeated/multidirectional) imperfective, the second is the *determinate*
(single-direction, in-progress) imperfective, and the third is the perfective. This three-way split is
a genuinely distinct grammatical mechanism from the two-way aspectual pairs that dominate the rest of
the vocabulary table, and is worth treating as its own morphological category for the mechanics-
analysis phase, since it constrains how "going"/"pulling"-type slang derivatives could be aspectually
marked.

### Reflexive-suffix meaning shift: состоять vs. состояться

The source's own footnote at p.463/464 (reproduced here paraphrased, not verbatim) explains that
состоять(ся) is one verb whose reflexive (-ся) and non-reflexive forms carry genuinely different
meanings rather than the more usual reflexive-as-voice-marker pattern: the non-reflexive состоять
means "to consist of," while the reflexive состояться means "to take place." This is a clean, source-
flagged example of the -ся suffix shifting lexical meaning rather than just voice/reciprocity — worth
noting alongside any other -ся meaning-shift pairs found elsewhere in this book's page range (e.g.
разбираться "to understand/sort out" vs. разбирать "to take apart," captured in the sibling chunks).

### "TOP 50 VERB" frequency flag and its paired "Idioms"/"Other Uses" supplement

The book itself designates 11 of the 174 verbs in this range as belonging to its own "Top 50 Verb"
list (see the coverage note above for the full list and page numbers) and gives each a second,
immediately-following page of extra idiomatic usage beyond the first page's own Usage/Proverbs
section — e.g. the second страдать... no, the second "стоять/постоять" TOP-50 page adds an "Idioms"
block (Он крепко стоит на ногах "He is well situated in life"; Не стой у меня над душой! "Stop
breathing down my neck!"; Мы за ценой не постоим "Money is no object with us" — paraphrased, not
quoted in bulk). This is genuine source-marked frequency-tier data (captured in the Weight/Frequency
column above), not an inference from lesson placement, and the paired idiom supplement is a real
additional layer of register/collocation data for these specific 11 high-frequency verbs that a slang-
derivation pass may want to revisit directly in the source PDF (pages listed above) rather than via
this summary file, given the copyright-discipline limit on reproducing idiom lists in bulk.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `../../00_Reference_Extraction_Spec.md`. This file
extracts only the aspectual-pair/gloss/conjugation-class/stem data (the reusable lexical layer) for
all 174 verbs in its range; it does not reproduce any of the source's full conjugation paradigms,
Usage example sentences, Idioms, or Proverbs/Sayings blocks, all of which remain in the source PDF.
