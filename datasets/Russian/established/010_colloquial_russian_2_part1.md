# Russian — Established Vocabulary/Grammar: Colloquial Russian 2, Units 1–9 (Part 1 of 2)

**Source:** Svetlana Le Fleming and Susan E. Kay, *Colloquial Russian 2: The Next Step in
Language Learning* (Routledge, first published 2003; this edition Taylor & Francis e-Library,
2006), ISBN 0-415-26116-3. PDF: `source_reference/languages/Russian/Russian Learning Pack
[up-to-date as of 2012]/Vol 1 of 3/23.Colloquial Russian 2.pdf`. This file covers PDF pages 1–180
(front matter through Unit 9 *Демография* "Demography", printed pages iii–171, breaking mid-unit
at the numerals/fractions grammar point — the book's own page numbering runs roughly nine pages
behind the PDF page count throughout this range). A sibling subagent covers PDF pages 181–353
(rest of Unit 9 onward) as a separate file; no overlap with that range is intended here.

**Register note:** despite the "Colloquial" series title, this is an intermediate-to-advanced
*general* course (revision grammar + six newspaper/magazine-themed units: transport, tourism,
migration, sport, cultural life, mass media), not a slang/register-annotated reference. It carries
no explicit register tags (no `[B]`/`[C]`/`[S]`-style annotation, no per-word "colloquial" vs.
"formal" marking) — register is conveyed only by the book's own framing (a few explicitly informal
collocations around youth subculture and job-hunting are flagged `slang` below; everything else is
undifferentiated `core` vocabulary of the kind a fluent adult reader of Russian newspapers would
need).

## PDF-extraction gotcha: fixed font-substitution cipher (Latin-lookalike glyphs for Cyrillic)

**This source has a genuine text layer, but `pdftotext` does not recover real Cyrillic from it.**
Every Russian word in the book — dialogues, texts, grammar tables, vocabulary boxes — extracts as
a string of Latin letters and ASCII symbols that looks at first glance like scrambled
transliteration (e.g. `Rossiq i russkij qzyk` for `Россия и русский язык`; `Kul;turnaq 'izn;` for
`Культурная жизнь`). This is exactly the "fixed, decodable font-substitution cipher" case flagged
in `00_Reference_Extraction_Spec.md`'s PDF-extraction-gotchas section: the substitution is a
**consistent 1:1 character map**, not random OCR garbling, and it was decoded and verified against
25+ known Russian word pairs spread across many pages before being trusted (e.g. `Rossiq`→`Россия`,
`russkij`→`русский`, `Moskvá`→`Москва`, `revol[´ciq`→`революция`, `Ob]estvo`→`Общество`,
`kompeténtnyx`→`компетентных`, `poddér'ki`→`поддержки`, `s#ezd`→`съезд`, `ob#edinq́t;`→`объединять`).
The recovered map (lowercase; case is preserved on the output letter):

| cipher | Cyrillic | cipher | Cyrillic | cipher | Cyrillic | cipher | Cyrillic |
|---|---|---|---|---|---|---|---|
| a | а | k | к | x | х | ] | щ |
| b | б | l | л | c | ц | y | ы |
| v | в | m | м | h | ч | `;` | ь |
| g | г | n | н | w | ш | `\` | э |
| d | д | o | о | ' | ж | `[` | ю |
| e | е | p | п | @ | ж (uppercase acronyms only, e.g. `ВНЖ`) | q | я |
| z | з | r | р | # | ъ | ë | ё |
| i | и | s | с | | | | |
| j | й | t | т | | | | |

An acute accent (´) over a Latin vowel marks Russian lexical stress and was preserved on the
decoded Cyrillic vowel (e.g. `mósqc` → `ме́сяц`); it is not part of the cipher itself. All terms
below have been decoded to real Cyrillic script using this map — a small Python script performed
the mechanical substitution after the map was hand-verified, and the two-obvious-typo-in-source
cases found (`nefqnáq` for `neftqnáq` = нефтяна́я, and a stray space inside `ka[´ ty` /
`povs[´ du` / `\t[´d` artefacts of the extraction) were silently corrected to the evidently-intended
form. This is **not** a vision-reading situation (no scanned images were read) and no handwritten
marginalia was encountered — the book's own text layer, once decoded, is fully machine-legible.

## Coverage note

Every grammar point and every distinct vocabulary item from the assigned range is included below:
all 21 boxed **Vocabulary ♦** lists across Units 1–9 (382 headword entries), plus a supplementary
table of idiomatic/set-phrase glosses drawn from the book's own **N.B.** footnotes (118 entries) —
these are genuinely distinct lexical items (fixed collocations, acronyms, set expressions) the book
itself calls out as noteworthy, not incidental example-sentence vocabulary, so they are included
per the coverage rule rather than skipped as drill material. Repeated drill exercises and
translation/fill-in sentences that recycle already-captured vocabulary are not reproduced (per
copyright discipline and the coverage rule). No explicit dialectal/regional annotation appears
anywhere in this range (this course does not mark regional variants), so `Attested Region` /
`Geographic Scope` are `—` throughout. `Attested Era` is set to the book's own coarse whole-source
default, "contemporary (source published 2003)", per the extraction spec — no finer per-word era
data is supported by this source.

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| вы́брать | to choose | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1 (Russia and the Russian Language), vocab box 1 — Moscow text |
| князь (m) | prince | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1 (Russia and the Russian Language), vocab box 1 — Moscow text |
| летопи́сное упомина́ние | chronicle reference | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1 (Russia and the Russian Language), vocab box 1 — Moscow text |
| основа́тель (m) | founder | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1 (Russia and the Russian Language), vocab box 1 — Moscow text |
| остава́ться | to remain | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1 (Russia and the Russian Language), vocab box 1 — Moscow text |
| относи́ться к | to date from | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1 (Russia and the Russian Language), vocab box 1 — Moscow text |
| перенести́ | to transfer | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1 (Russia and the Russian Language), vocab box 1 — Moscow text |
| расти́ | to grow | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1 (Russia and the Russian Language), vocab box 1 — Moscow text |
| строи́тельство | construction | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1 (Russia and the Russian Language), vocab box 1 — Moscow text |
| бы́вший | former | adjective | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 2 — 1991 coup text |
| вну́тренний | domestic | adjective | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 2 — 1991 coup text |
| вы́ступить про́тив | to act, come out, against | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 2 — 1991 coup text |
| га́зовая и нефтяна́я промы́шленность | gas and oil industry | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 2 — 1991 coup text |
| госуда́рственный | state | adjective | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 2 — 1991 coup text |
| де́йствие | action | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 2 — 1991 coup text |
| за́говор / загово́рщик | plot / plotter | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 2 — 1991 coup text |
| повыше́ние | increase | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 2 — 1991 coup text |
| подде́ржка | support | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 2 — 1991 coup text |
| попы́тка | attempt | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 2 — 1991 coup text |
| прави́тельство | government | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 2 — 1991 coup text |
| причи́на | reason | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 2 — 1991 coup text |
| провали́ться | to fail | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 2 — 1991 coup text |
| произойти́ | to happen, take place | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 2 — 1991 coup text |
| распа́д | collapse | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 2 — 1991 coup text |
| реши́тельно | resolutely | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 2 — 1991 coup text |
| собы́тие | event | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 2 — 1991 coup text |
| сомне́ние | doubt | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 2 — 1991 coup text |
| сора́тник | comrade-in-arms | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 2 — 1991 coup text |
| уве́рены в успе́хе | conﬁdent of the success | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 2 — 1991 coup text |
| член Политбюро́ | member of the Politburo (political bureau of the Central Committee of the Communist Party) | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 2 — 1991 coup text |
| в голове́ проно́сятся мы́сли | thoughts run through (my) mind | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 3 — coup eyewitness account |
| винова́т | guilty, to blame | adjective (short form) | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 3 — coup eyewitness account |
| де́йствовать | to act | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 3 — coup eyewitness account |
| неуже́ли | really? is it possible? | particle | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 3 — coup eyewitness account |
| обраща́ться к | to address | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 3 — coup eyewitness account |
| переда́ча по телеви́дению | television broadcast | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 3 — coup eyewitness account |
| после́днее сообще́ние | latest report | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 3 — coup eyewitness account |
| прика́з / прика́зывать | order / to order | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 3 — coup eyewitness account |
| присоедини́ться к | to join | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 3 — coup eyewitness account |
| стреля́ть | to shoot | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 3 — coup eyewitness account |
| суди́ть по | to judge by | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 3 — coup eyewitness account |
| часть | part | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 3 — coup eyewitness account |
| нереши́тельность | indecision | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 4 — instrumental case example text |
| оде́ржана побе́да | victory was achieved | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 4 — instrumental case example text |
| руково́дство | leadership | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 4 — instrumental case example text |
| твёрдая уве́ренность | unshakeable conﬁdence | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 4 — instrumental case example text |
| заседа́ть | to sit (of parliament) | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 5 — prepositional case example |
| возника́ть / возни́кнуть | to arise | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 6 — USSR collapse text |
| догово́р | treaty | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 6 — USSR collapse text |
| исто́к | source | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 6 — USSR collapse text |
| недово́льство | dissatisfaction | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 6 — USSR collapse text |
| перегово́ры | negotiations | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 6 — USSR collapse text |
| по по́воду | on the subject of | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 6 — USSR collapse text |
| повсю´ду | everywhere | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 6 — USSR collapse text |
| подпи́сывать / подписа́ть соглаше́ние | to sign an agreement | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 6 — USSR collapse text |
| предложе́ние | proposal | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 6 — USSR collapse text |
| примене́ние си́лы | use of force | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 6 — USSR collapse text |
| приноси́ть / принести́ успе́х | to bring success | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 6 — USSR collapse text |
| случи́ться | to happen | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 6 — USSR collapse text |
| созда́ние | creation | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 6 — USSR collapse text |
| Содру́жество Незави́симых Госуда́рств | Commonwealth of Independent States | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 1, vocab box 6 — USSR collapse text |
| добра́ться до | to get to | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2 (Transport), vocab box 1 — airport dialogue |
| зара́нее | in advance | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2 (Transport), vocab box 1 — airport dialogue |
| маршру́тное такси́ | minibus | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2 (Transport), vocab box 1 — airport dialogue |
| междунаро́дный | international | adjective | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2 (Transport), vocab box 1 — airport dialogue |
| нало́г | tax | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2 (Transport), vocab box 1 — airport dialogue |
| ночно́й рейс | night ﬂight | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2 (Transport), vocab box 1 — airport dialogue |
| опозда́ть на (+ acc) | to be late for | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2 (Transport), vocab box 1 — airport dialogue |
| отправля́ться | to set off, depart | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2 (Transport), vocab box 1 — airport dialogue |
| поверну́ть | to turn | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2 (Transport), vocab box 1 — airport dialogue |
| пожа́луй | perhaps | particle / adverb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2 (Transport), vocab box 1 — airport dialogue |
| ре́йсовый авто́бус | regular bus | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2 (Transport), vocab box 1 — airport dialogue |
| сто́имость (f) | cost | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2 (Transport), vocab box 1 — airport dialogue |
| стоя́нка | (taxi) rank, stop | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2 (Transport), vocab box 1 — airport dialogue |
| то́лько что | just | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2 (Transport), vocab box 1 — airport dialogue |
| бу́дучи | being | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2, vocab box 2 — Russian railways text |
| ведь | you see; after all (emphatic particle) | particle | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2, vocab box 2 — Russian railways text |
| визи́тная ка́рточка | visiting card | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2, vocab box 2 — Russian railways text |
| вре́дное вещество́ | harmful substance | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2, vocab box 2 — Russian railways text |
| выбра́сывать | to emit | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2, vocab box 2 — Russian railways text |
| выруба́ться | to be cut down | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2, vocab box 2 — Russian railways text |
| высокоскоростна́я магистра́ль | high-speed railway | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2, vocab box 2 — Russian railways text |
| дви́гаться | to move | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2, vocab box 2 — Russian railways text |
| движе́ние поездо́в | rail trafﬁc | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2, vocab box 2 — Russian railways text |
| двухме́стные кре́сла | double seats | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2, vocab box 2 — Russian railways text |
| желе́зная доро́га | railway | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2, vocab box 2 — Russian railways text |
| земля́ | land | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2, vocab box 2 — Russian railways text |
| колесо́ | wheel | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2, vocab box 2 — Russian railways text |
| коро́че | shorter | adverb (comparative) | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2, vocab box 2 — Russian railways text |
| курси́ровать | to run | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2, vocab box 2 — Russian railways text |
| мя́гкий | soft | adjective | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2, vocab box 2 — Russian railways text |
| надёжный | reliable | adjective | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2, vocab box 2 — Russian railways text |
| напомина́ть | to resemble | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2, vocab box 2 — Russian railways text |
| направле́ние | trend | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2, vocab box 2 — Russian railways text |
| обору́дование | equipment | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2, vocab box 2 — Russian railways text |
| обслу́живаться | to be served | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2, vocab box 2 — Russian railways text |
| остава́ться зада́чей | to remain the task | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2, vocab box 2 — Russian railways text |
| проводни́к | train attendant | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2, vocab box 2 — Russian railways text |
| ско́рость (f) | speed | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2, vocab box 2 — Russian railways text |
| скоростно́й электропо́езд | express train | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2, vocab box 2 — Russian railways text |
| созда́ние | creation | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2, vocab box 2 — Russian railways text |
| сто́имость (f) прое́зда | cost of the journey | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2, vocab box 2 — Russian railways text |
| столи́чный | capital | adjective | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2, vocab box 2 — Russian railways text |
| строи́тельство | construction | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2, vocab box 2 — Russian railways text |
| труд рабо́чих | labour | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2, vocab box 2 — Russian railways text |
| уничтожа́ться | to be destroyed | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2, vocab box 2 — Russian railways text |
| у́ровень (m) обслу́живания | standard of service | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2, vocab box 2 — Russian railways text |
| услу́га | service | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2, vocab box 2 — Russian railways text |
| чи́ще | cleaner | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2, vocab box 2 — Russian railways text |
| электри́чка | local (electric) train | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2, vocab box 2 — Russian railways text |
| предложи́ть | to offer | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 3 (Tourism), vocab box 1 — travel agent dialogue |
| пока́ | for a while | adverb / conjunction | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 3 (Tourism), vocab box 1 — travel agent dialogue |
| потряса́ющий | stunning, fantastic | adjective | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 3 (Tourism), vocab box 1 — travel agent dialogue |
| семидне́вный тур | seven-day tour | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 3 (Tourism), vocab box 1 — travel agent dialogue |
| теплохо́д | boat | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 3 (Tourism), vocab box 1 — travel agent dialogue |
| выходны́е дни | weekend | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 3, vocab box 2 — Volga cruise text |
| закуси́ть | to have a bite to eat | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 3, vocab box 2 — Volga cruise text |
| ключ от каю´ты | cabin key | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 3, vocab box 2 — Volga cruise text |
| на́бережная | embankment | adjective | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 3, vocab box 2 — Volga cruise text |
| нос теплохо́да | bow of the ship | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 3, vocab box 2 — Volga cruise text |
| отплы́тие | departure (by boat) | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 3, vocab box 2 — Volga cruise text |
| отча́лить | to set sail | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 3, vocab box 2 — Volga cruise text |
| па́луба | deck | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 3, vocab box 2 — Volga cruise text |
| па́мятник | monument | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 3, vocab box 2 — Volga cruise text |
| пешехо́дная экску́рсия | walking tour | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 3, vocab box 2 — Volga cruise text |
| позагора́ть | to sunbathe | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 3, vocab box 2 — Volga cruise text |
| прича́лить | to moor | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 3, vocab box 2 — Volga cruise text |
| подходя́щий | suitable | adjective | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 3, vocab box 2 — Volga cruise text |
| походи́ть на (+ acc) | to look like | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 3, vocab box 2 — Volga cruise text |
| размеща́ться | to be accommodated | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 3, vocab box 2 — Volga cruise text |
| реши́ться | to make up one's mind | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 3, vocab box 2 — Volga cruise text |
| соверша́ть рейс | to sail | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 3, vocab box 2 — Volga cruise text |
| стоя́нка | stop | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 3, vocab box 2 — Volga cruise text |
| удиви́ть | to surprise | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 3, vocab box 2 — Volga cruise text |
| хво́йный бор | coniferous forest | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 3, vocab box 2 — Volga cruise text |
| шашлы́к | kebab | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 3, vocab box 2 — Volga cruise text |
| беспоко́иться | to be worried | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4 (Migration), vocab box 1 — journalist/sociologist dialogue |
| бла́го | good | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4 (Migration), vocab box 1 — journalist/sociologist dialogue |
| боя́ться (+ gen) | to be afraid | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4 (Migration), vocab box 1 — journalist/sociologist dialogue |
| грани́ца | border | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4 (Migration), vocab box 1 — journalist/sociologist dialogue |
| кита́ец, Кита́й | Chinese, China | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4 (Migration), vocab box 1 — journalist/sociologist dialogue |
| наде́жда | hope | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4 (Migration), vocab box 1 — journalist/sociologist dialogue |
| населе́ние | population | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4 (Migration), vocab box 1 — journalist/sociologist dialogue |
| о́бщество | society | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4 (Migration), vocab box 1 — journalist/sociologist dialogue |
| опа́сный | dangerous | adjective | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4 (Migration), vocab box 1 — journalist/sociologist dialogue |
| оправда́ться | to be justiﬁed | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4 (Migration), vocab box 1 — journalist/sociologist dialogue |
| остава́ться | to remain, stay | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4 (Migration), vocab box 1 — journalist/sociologist dialogue |
| охраня́ться | to be guarded | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4 (Migration), vocab box 1 — journalist/sociologist dialogue |
| приня́ть зако́н | to pass a law | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4 (Migration), vocab box 1 — journalist/sociologist dialogue |
| середи́на ве́ка | the middle of the century | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4 (Migration), vocab box 1 — journalist/sociologist dialogue |
| сократи́ться | to decrease, reduce, be reduced | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4 (Migration), vocab box 1 — journalist/sociologist dialogue |
| сотру́дничать с (+ inst) | to cooperate with | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4 (Migration), vocab box 1 — journalist/sociologist dialogue |
| укрепля́ться | to become stronger | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4 (Migration), vocab box 1 — journalist/sociologist dialogue |
| уменьша́ться | to decrease | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4 (Migration), vocab box 1 — journalist/sociologist dialogue |
| число́ | number | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4 (Migration), vocab box 1 — journalist/sociologist dialogue |
| безвозвра́тный хара́ктер | of a permanent character | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4, vocab box 2 — emigration/immigration text |
| бе́женец, бе́женство | refugee, refugee problem | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4, vocab box 2 — emigration/immigration text |
| волнова́ть | to disturb | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4, vocab box 2 — emigration/immigration text |
| вре́менный | temporary | adjective | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4, vocab box 2 — emigration/immigration text |
| вы́звать | to cause | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4, vocab box 2 — emigration/immigration text |
| вы́ходец из (+ gen) | of . . . origin | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4, vocab box 2 — emigration/immigration text |
| до́ля | share | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4, vocab box 2 — emigration/immigration text |
| жильё | accommodation | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4, vocab box 2 — emigration/immigration text |
| зави́сеть от (+ gen) | to depend on | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4, vocab box 2 — emigration/immigration text |
| заме́тный | noticeable | adjective | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4, vocab box 2 — emigration/immigration text |
| заяви́ть | to declare | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4, vocab box 2 — emigration/immigration text |
| иностра́нный граждани́н | foreign citizen | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4, vocab box 2 — emigration/immigration text |
| каза́х | Kazakh | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4, vocab box 2 — emigration/immigration text |
| каса́ться (+ gen) | to concern | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4, vocab box 2 — emigration/immigration text |
| наде́яться на (+ acc) | to hope for | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4, vocab box 2 — emigration/immigration text |
| о́бласть (f) | province, oblast | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4, vocab box 2 — emigration/immigration text |
| о́бщее число́ | total number | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4, vocab box 2 — emigration/immigration text |
| отка́зываться принима́ть | to refuse to accept / take | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4, vocab box 2 — emigration/immigration text |
| постоя́нное ме́сто жи́тельства | permanent residence | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4, vocab box 2 — emigration/immigration text |
| превраща́ться в (+ acc) | to turn into | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4, vocab box 2 — emigration/immigration text |
| рассма́тривать | to regard as | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4, vocab box 2 — emigration/immigration text |
| ре́зко | sharply | adverb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4, vocab box 2 — emigration/immigration text |
| составля́ть | to constitute | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4, vocab box 2 — emigration/immigration text |
| трудоустро́йство | placement in work | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4, vocab box 2 — emigration/immigration text |
| увели́чиваться | to increase | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4, vocab box 2 — emigration/immigration text |
| уси́ливаться | to intensify | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4, vocab box 2 — emigration/immigration text |
| уте́чка мозго́в | brain drain | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4, vocab box 2 — emigration/immigration text |
| чи́сленность (f) | numbers | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4, vocab box 2 — emigration/immigration text |
| заня́тие пла́ванием | swimming lesson | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5 (Sport), vocab box 1 — fitness club dialogue |
| испо́льзовать | to use | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5 (Sport), vocab box 1 — fitness club dialogue |
| клу́бная ка́рта | membership card | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5 (Sport), vocab box 1 — fitness club dialogue |
| обяза́тельно | necessary, obligatory | adverb / adjective | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5 (Sport), vocab box 1 — fitness club dialogue |
| о́пытный | experienced | adjective | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5 (Sport), vocab box 1 — fitness club dialogue |
| приобрести́ | to acquire | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5 (Sport), vocab box 1 — fitness club dialogue |
| проводи́ть заня́тия | to conduct lessons | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5 (Sport), vocab box 1 — fitness club dialogue |
| разрабо́тать програ́мму | to work out a programme | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5 (Sport), vocab box 1 — fitness club dialogue |
| спо́соб снять стресс | means to relieve stress | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5 (Sport), vocab box 1 — fitness club dialogue |
| тренажёр | training equipment | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5 (Sport), vocab box 1 — fitness club dialogue |
| ба́нковский слу́жащий | bank employee | adjectival phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5, vocab box 2 — extreme sport/biker text |
| волна́ | wave | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5, vocab box 2 — extreme sport/biker text |
| воспринима́ть всерьёз | to take seriously | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5, vocab box 2 — extreme sport/biker text |
| го́нки (pl) | race | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5, vocab box 2 — extreme sport/biker text |
| горнолы́жный склон | ski slope | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5, vocab box 2 — extreme sport/biker text |
| го́рный велосипе́д | mountain bike | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5, vocab box 2 — extreme sport/biker text |
| грунт | soil, ground | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5, vocab box 2 — extreme sport/biker text |
| жа́ловаться на (+ acc) | to complain about | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5, vocab box 2 — extreme sport/biker text |
| иску́сственный | artiﬁcial | adjective | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5, vocab box 2 — extreme sport/biker text |
| испы́тывать прито́к адренали́на | to experience an adrenaline surge | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5, vocab box 2 — extreme sport/biker text |
| кайф | kicks, high | noun | slang | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5, vocab box 2 — extreme sport/biker text |
| кру́глый год | all-year-round | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5, vocab box 2 — extreme sport/biker text |
| круто́й склон | steep slope | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5, vocab box 2 — extreme sport/biker text |
| лы́жа, лы́жник | ski, skier | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5, vocab box 2 — extreme sport/biker text |
| многочи́сленный | numerous | adjective | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5, vocab box 2 — extreme sport/biker text |
| объединя́ть | to unite | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5, vocab box 2 — extreme sport/biker text |
| пережи́ть | to experience | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5, vocab box 2 — extreme sport/biker text |
| побли́зости | nearby | adverb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5, vocab box 2 — extreme sport/biker text |
| поми́мо (+ gen) | apart from | preposition | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5, vocab box 2 — extreme sport/biker text |
| по́ртить | to damage | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5, vocab box 2 — extreme sport/biker text |
| потребля́ть нарко́тики | to use drugs | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5, vocab box 2 — extreme sport/biker text |
| представля́ть | to represent | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5, vocab box 2 — extreme sport/biker text |
| пры́гать | to jump | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5, vocab box 2 — extreme sport/biker text |
| пуга́ть | to frighten | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5, vocab box 2 — extreme sport/biker text |
| развлече́ние | entertainment | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5, vocab box 2 — extreme sport/biker text |
| разреша́ть (+ dat) | to allow | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5, vocab box 2 — extreme sport/biker text |
| располо́жен | situated | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5, vocab box 2 — extreme sport/biker text |
| слеза́ть с (+ gen) | to get (climb) down from | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5, vocab box 2 — extreme sport/biker text |
| сро́дни (+ dat) | akin to | preposition | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5, vocab box 2 — extreme sport/biker text |
| съезд | congress; convention | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5, vocab box 2 — extreme sport/biker text |
| трюк | stunt | noun | slang | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5, vocab box 2 — extreme sport/biker text |
| тусо́вка | get-together | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5, vocab box 2 — extreme sport/biker text |
| устра́ивать соревнова́ния | to hold competitions | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5, vocab box 2 — extreme sport/biker text |
| утвержда́ть | to claim | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5, vocab box 2 — extreme sport/biker text |
| благотвори́тельный пока́з | charity show | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6 (Cultural Life), vocab box 1 — film festival dialogue |
| впервы́е | for the ﬁrst time | adverb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6 (Cultural Life), vocab box 1 — film festival dialogue |
| выпуска́ть | to release | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6 (Cultural Life), vocab box 1 — film festival dialogue |
| вы́явить | to discover | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6 (Cultural Life), vocab box 1 — film festival dialogue |
| досту́пный | accessible | adjective | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6 (Cultural Life), vocab box 1 — film festival dialogue |
| евре́йский | Jewish | adjective | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6 (Cultural Life), vocab box 1 — film festival dialogue |
| ко́нкурс | competition | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6 (Cultural Life), vocab box 1 — film festival dialogue |
| мирово́й зри́тель | world audience | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6 (Cultural Life), vocab box 1 — film festival dialogue |
| отли́чие | difference | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6 (Cultural Life), vocab box 1 — film festival dialogue |
| оце́нивать, оце́нщик | to judge (in a competition); judge | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6 (Cultural Life), vocab box 1 — film festival dialogue |
| ошиба́ться | to be mistaken | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6 (Cultural Life), vocab box 1 — film festival dialogue |
| поколе́ние | generation | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6 (Cultural Life), vocab box 1 — film festival dialogue |
| получи́ть призна́ние | to receive recognition | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6 (Cultural Life), vocab box 1 — film festival dialogue |
| режиссёр | producer | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6 (Cultural Life), vocab box 1 — film festival dialogue |
| веду́щий | leading | adjective | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6, vocab box 2 — director Lev Dodin text |
| вое́нный | wartime | adjective | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6, vocab box 2 — director Lev Dodin text |
| вспо́мнить | to remember | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6, vocab box 2 — director Lev Dodin text |
| го́рдость (f) | pride | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6, vocab box 2 — director Lev Dodin text |
| же́ртвовать (+ inst) | to sacriﬁce | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6, vocab box 2 — director Lev Dodin text |
| завоева́ть пре́мию | to win a prize | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6, vocab box 2 — director Lev Dodin text |
| заменя́ть | to replace | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6, vocab box 2 — director Lev Dodin text |
| за́дний план | background | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6, vocab box 2 — director Lev Dodin text |
| зарубе́жные гастро́ли | foreign tour | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6, vocab box 2 — director Lev Dodin text |
| заслу́женный | deserved | adjective | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6, vocab box 2 — director Lev Dodin text |
| избежа́ть (+ gen) | to avoid | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6, vocab box 2 — director Lev Dodin text |
| и́менно | namely, actually | adverb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6, vocab box 2 — director Lev Dodin text |
| исчеза́ть / исче́знуть | to disappear | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6, vocab box 2 — director Lev Dodin text |
| мастерска́я | workshop, studio | adjective | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6, vocab box 2 — director Lev Dodin text |
| мастерство́ | skill | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6, vocab box 2 — director Lev Dodin text |
| подо́бный | similar to | adjective | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6, vocab box 2 — director Lev Dodin text |
| постано́вка | production | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6, vocab box 2 — director Lev Dodin text |
| потрясе́ние | sensation | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6, vocab box 2 — director Lev Dodin text |
| преврати́ться в (+ acc) | to turn into | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6, vocab box 2 — director Lev Dodin text |
| превраще́ние | transformation | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6, vocab box 2 — director Lev Dodin text |
| просла́виться (+ inst) | to become famous | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6, vocab box 2 — director Lev Dodin text |
| репети́ровать | to rehearse | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6, vocab box 2 — director Lev Dodin text |
| руководи́ть (+ inst) | to lead | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6, vocab box 2 — director Lev Dodin text |
| совреме́нный | modern | adjective | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6, vocab box 2 — director Lev Dodin text |
| состоя́ть из (+ gen) | to consist | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6, vocab box 2 — director Lev Dodin text |
| сохрани́ть | to preserve | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6, vocab box 2 — director Lev Dodin text |
| торго́вая ма́рка | trade mark | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6, vocab box 2 — director Lev Dodin text |
| тру́ппа | company | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6, vocab box 2 — director Lev Dodin text |
| управля́ть (+ inst) | to manage | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6, vocab box 2 — director Lev Dodin text |
| учрежде́ние | institution | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6, vocab box 2 — director Lev Dodin text |
| худо́жественный, худо́жественность | artistic merit, quality | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6, vocab box 2 — director Lev Dodin text |
| цени́ть | to appreciate | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6, vocab box 2 — director Lev Dodin text |
| этю´д | sketch | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6, vocab box 2 — director Lev Dodin text |
| явле́ние | phenomenon | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6, vocab box 2 — director Lev Dodin text |
| владе́лец | owner | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7 (Mass Media), vocab box 1 — press freedom dialogue |
| выступле́ние | speech | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7 (Mass Media), vocab box 1 — press freedom dialogue |
| выража́ть | to express | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7 (Mass Media), vocab box 1 — press freedom dialogue |
| зави́сим/ость (f), -ый | dependence, dependent | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7 (Mass Media), vocab box 1 — press freedom dialogue |
| издава́ть / изда́тель | to publish / publisher | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7 (Mass Media), vocab box 1 — press freedom dialogue |
| ме́стные о́рганы вла́сти | local government | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7 (Mass Media), vocab box 1 — press freedom dialogue |
| опа́сность (f) | danger | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7 (Mass Media), vocab box 1 — press freedom dialogue |
| отража́ть | to reﬂect | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7 (Mass Media), vocab box 1 — press freedom dialogue |
| по́лностью незави́симый | fully independent | adjectival phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7 (Mass Media), vocab box 1 — press freedom dialogue |
| подве́ргнуться кри́тике | to be subject to criticism | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7 (Mass Media), vocab box 1 — press freedom dialogue |
| признава́ть | to acknowledge | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7 (Mass Media), vocab box 1 — press freedom dialogue |
| реда́кция | editorial ofﬁce | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7 (Mass Media), vocab box 1 — press freedom dialogue |
| ры́ночное пра́вило | rule of the market | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7 (Mass Media), vocab box 1 — press freedom dialogue |
| свобо́да пре́ссы | freedom of the press | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7 (Mass Media), vocab box 1 — press freedom dialogue |
| содержа́ть | to keep | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7 (Mass Media), vocab box 1 — press freedom dialogue |
| статья́ | article | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7 (Mass Media), vocab box 1 — press freedom dialogue |
| телеведу́щий | television presenter | adjective | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7 (Mass Media), vocab box 1 — press freedom dialogue |
| ча́стный кана́л | private channel | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7 (Mass Media), vocab box 1 — press freedom dialogue |
| а́вторская програ́мма | personal programme | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7, vocab box 2 — Russian television text |
| ве́сти (pl) | news | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7, vocab box 2 — Russian television text |
| вмеша́тельство | interference | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7, vocab box 2 — Russian television text |
| воскре́сная програ́мма | Sunday programme | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7, vocab box 2 — Russian television text |
| дополни́тельный | additional | adjective | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7, vocab box 2 — Russian television text |
| зе́ркало | mirror | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7, vocab box 2 — Russian television text |
| иску́сство | art | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7, vocab box 2 — Russian television text |
| ито́ги (pl) | summing up, total; results | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7, vocab box 2 — Russian television text |
| кома́нда | team | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7, vocab box 2 — Russian television text |
| ку́кла | doll, puppet | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7, vocab box 2 — Russian television text |
| музыка́льно-развлека́тельный | musical entertainment | adjective | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7, vocab box 2 — Russian television text |
| мы́льная о́пера | soap opera | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7, vocab box 2 — Russian television text |
| нау́чно-познава́тельный | popular science | adjective | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7, vocab box 2 — Russian television text |
| общенациона́льный кана́л | national channel | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7, vocab box 2 — Russian television text |
| отдава́ть предпочте́ние | to give preference | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7, vocab box 2 — Russian television text |
| поки́нуть | to leave | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7, vocab box 2 — Russian television text |
| похо́жий на (+ acc) | similar to | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7, vocab box 2 — Russian television text |
| распра́виться с (+ inst) | deal with | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7, vocab box 2 — Russian television text |
| сме́на | team | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7, vocab box 2 — Russian television text |
| то́чка зре́ния | point of view | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7, vocab box 2 — Russian television text |
| цифрово́й | digital | adjective | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7, vocab box 2 — Russian television text |
| аге́нтство по трудоустро́йству | employment agency | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 (Labour Market), vocab box 1 — job search text |
| актуа́льный | current | adjective | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 (Labour Market), vocab box 1 — job search text |
| безрабо́тица / безрабо́тный | unemployment / unemployed | adjectival phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 (Labour Market), vocab box 1 — job search text |
| буква́льно | literally | adverb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 (Labour Market), vocab box 1 — job search text |
| ве́рный спо́соб | sure way | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 (Labour Market), vocab box 1 — job search text |
| дипломи́рованный специали́ст | a qualiﬁed specialist | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 (Labour Market), vocab box 1 — job search text |
| доверя́ть (dat) | to trust | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 (Labour Market), vocab box 1 — job search text |
| до́лжность (f) | post | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 (Labour Market), vocab box 1 — job search text |
| исключе́ние | exception | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 (Labour Market), vocab box 1 — job search text |
| ка́чество | quality | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 (Labour Market), vocab box 1 — job search text |
| круг лиц | circle of people | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 (Labour Market), vocab box 1 — job search text |
| Комите́т труда́ и за́нятости | Labour and Employment committee | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 (Labour Market), vocab box 1 — job search text |
| ме́неджер по прода́жам | sales manager | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 (Labour Market), vocab box 1 — job search text |
| насто́йчивость (f) | persistence | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 (Labour Market), vocab box 1 — job search text |
| общи́тельность (f) | sociability | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 (Labour Market), vocab box 1 — job search text |
| объявле́ние о рабо́те | job advertisement | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 (Labour Market), vocab box 1 — job search text |
| о́трасль (f) | branch | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 (Labour Market), vocab box 1 — job search text |
| перехо́д к ры́нку | transition to the market | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 (Labour Market), vocab box 1 — job search text |
| подбира́ть ка́дры | to select personnel | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 (Labour Market), vocab box 1 — job search text |
| преиму́щество | advantage | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 (Labour Market), vocab box 1 — job search text |
| прили́чная рабо́та | decent job | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 (Labour Market), vocab box 1 — job search text |
| работода́тель | employer | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 (Labour Market), vocab box 1 — job search text |
| самостоя́тельно | independently | adverb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 (Labour Market), vocab box 1 — job search text |
| сообщи́ть | to inform | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 (Labour Market), vocab box 1 — job search text |
| (в) сре́днем | on average | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 (Labour Market), vocab box 1 — job search text |
| спи́сок | list | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 (Labour Market), vocab box 1 — job search text |
| тогда́ как | while | conjunction | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 (Labour Market), vocab box 1 — job search text |
| труди́ться | to work | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 (Labour Market), vocab box 1 — job search text |
| удовлетвори́ть спрос на (+ acc) | to satisfy demand on | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 (Labour Market), vocab box 1 — job search text |
| устро́иться на рабо́ту | to ﬁx oneself up with a job | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 (Labour Market), vocab box 1 — job search text |
| устро́йство на рабо́ту | ﬁnding work | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 (Labour Market), vocab box 1 — job search text |
| зада́ть вопро́с | to ask a question | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8, vocab box 2 — job interview dialogue |
| заявле́ние на рабо́ту | application for work | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8, vocab box 2 — job interview dialogue |
| испыта́тельный срок | probation | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8, vocab box 2 — job interview dialogue |
| ме́неджер по ка́драм (по персона́лу) | personnel manager | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8, vocab box 2 — job interview dialogue |
| отве́тственный | responsible | adjective | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8, vocab box 2 — job interview dialogue |
| осво́ить програ́мму | to master a programme | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8, vocab box 2 — job interview dialogue |
| перемени́ть рабо́ту | to change job | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8, vocab box 2 — job interview dialogue |
| подпи́сывать контра́кт | to sign a contract | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8, vocab box 2 — job interview dialogue |
| приступи́ть к рабо́те | to start work | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8, vocab box 2 — job interview dialogue |
| реализова́ть себя́ (свой потенциа́л) | to realise one's potential | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8, vocab box 2 — job interview dialogue |
| сопровожда́ть | to accompany | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8, vocab box 2 — job interview dialogue |
| спра́виться с тру́дностями | to cope with difﬁculties | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8, vocab box 2 — job interview dialogue |
| уважи́тельная причи́на | good reason | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8, vocab box 2 — job interview dialogue |
| уча́стие | participation | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8, vocab box 2 — job interview dialogue |
| бра́чный ста́тус | marital status | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 9 (Demography), vocab box 1 — male over-mortality text |
| жена́тый | married (man) | adjective | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 9 (Demography), vocab box 1 — male over-mortality text |
| злоупотребле́ние алкого́лем | alcohol abuse | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 9 (Demography), vocab box 1 — male over-mortality text |
| идти́ о́бщим путём | to follow the general trend | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 9 (Demography), vocab box 1 — male over-mortality text |
| куре́ние, кури́ть | smoking, to smoke | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 9 (Demography), vocab box 1 — male over-mortality text |
| малоподви́жный о́браз жи́зни | sedentary way of life | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 9 (Demography), vocab box 1 — male over-mortality text |
| нау́чный | scientiﬁc | adjective | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 9 (Demography), vocab box 1 — male over-mortality text |
| осозна́ть | to realise | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 9 (Demography), vocab box 1 — male over-mortality text |
| пе́репись (f) | census | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 9 (Demography), vocab box 1 — male over-mortality text |
| превы́сить | to exceed | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 9 (Demography), vocab box 1 — male over-mortality text |
| преиму́щественно | chieﬂy | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 9 (Demography), vocab box 1 — male over-mortality text |
| приме́рно | approximately | adverb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 9 (Demography), vocab box 1 — male over-mortality text |
| разведённый | divorced | adjective | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 9 (Demography), vocab box 1 — male over-mortality text |
| разры́в | gap | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 9 (Demography), vocab box 1 — male over-mortality text |
| рассчи́тывать на (+ acc) | to count on | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 9 (Demography), vocab box 1 — male over-mortality text |
| рожда́емость (f) | birthrate | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 9 (Demography), vocab box 1 — male over-mortality text |
| сле́довательно | consequently | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 9 (Demography), vocab box 1 — male over-mortality text |
| сме́ртность (f) | mortality | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 9 (Demography), vocab box 1 — male over-mortality text |
| снижа́ться, сниже́ние | to fall; fall | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 9 (Demography), vocab box 1 — male over-mortality text |
| сре́дняя продолжи́тельность (f) жи́зни | average life span | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 9 (Demography), vocab box 1 — male over-mortality text |
| сро́чные ме́ры | urgent measures | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 9 (Demography), vocab box 1 — male over-mortality text |
| у́мственный труд | intellectual work | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 9 (Demography), vocab box 1 — male over-mortality text |
| упа́сть | to fall | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 9 (Demography), vocab box 1 — male over-mortality text |
| биле́т туда́ и обра́тно | return ticket | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2 idiom (N.B., airport dialogue) |
| плати́ть нали́чными | to pay cash | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2 idiom (N.B., airport dialogue) |
| всё бу́дет в поря́дке | everything will be OK | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2 idiom (N.B., airport dialogue) |
| с друго́й стороны́ | on the other hand | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2 idiom (N.B., railways text) |
| всё ещё | still | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2 idiom (N.B., railways text) |
| вре́мя в пути́ | travel time | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2 idiom (N.B., railways text) |
| са́мое гла́вное | the most important thing | adjectival phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 2 idiom (N.B., railways text) |
| Золото́е кольцо́ | Golden Ring (route of ancient Russian towns) | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 3 idiom (N.B., travel agent dialogue) |
| пое́здка займёт | the trip will take | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 3 idiom (N.B., travel agent dialogue) |
| в настоя́щий моме́нт | at the present moment | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 3 idiom (N.B., travel agent dialogue) |
| одно́ удово́льствие | pure pleasure | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 3 idiom (N.B., travel agent dialogue) |
| счастли́вого пути́ | have a good trip! | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 3 idiom (N.B., travel agent dialogue) |
| на борту́ теплохо́да | on board ship | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 3 idiom (N.B., Volga cruise text) |
| по во́здуху и по су́ше | by air and land | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 3 idiom (N.B., Volga cruise text) |
| <ОТ> И <ДО> | inside out | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 3 idiom (N.B., Volga cruise text) |
| на́чал отплыва́ть | set sail | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 3 idiom (N.B., Volga cruise text) |
| быть в восто́рге | to be delighted | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 3 idiom (N.B., Volga cruise text) |
| же | exactly (emphatic particle) | particle | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 3 idiom (N.B., Volga cruise text) |
| жемчу́жина | pearl | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 3 idiom (N.B., Volga cruise text) |
| водопа́д | waterfall | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 3 idiom (N.B., Volga cruise text) |
| чу́до све́та | wonder of the world | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 3 idiom (N.B., Volga cruise text) |
| как пра́вило | as a rule | adverbial phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4 idiom (N.B., migration dialogue) |
| в основно́м | mainly | adverbial phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4 idiom (N.B., migration dialogue) |
| россия́нин | citizen of Russia (any ethnicity) | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4 idiom (N.B., migration dialogue) |
| бли́жнее зарубе́жье | the near abroad (former USSR republics) | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4 idiom (N.B., migration dialogue) |
| да́льнее зарубе́жье | the far abroad (other foreign countries) | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4 idiom (N.B., migration dialogue) |
| возвра́тная ссу́да | loan | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4 idiom (N.B., migrant housing report) |
| слабозащищённый | vulnerable | adjective | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4 idiom (N.B., migrant housing report) |
| как-то | somehow | adverb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4 idiom (N.B., migrant housing report) |
| обнадёжить | to reassure | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4 idiom (N.B., migrant housing report) |
| присво́ить статус | to confer status | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4 idiom (N.B., migrant housing report) |
| ВНЖ (вид на жи́тельство) | registration permit | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4 idiom (N.B., immigration advert glossary) |
| ПМЖ (постоя́нное ме́сто жи́тельства) | permanent residence | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4 idiom (N.B., immigration advert glossary) |
| брак | marriage | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4 idiom (N.B., immigration advert glossary) |
| недви́жимость | property | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4 idiom (N.B., immigration advert glossary) |
| гражда́нство | citizenship | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4 idiom (N.B., immigration advert glossary) |
| пропи́ска | residence registration | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 4 idiom (N.B., immigration advert glossary) |
| пра́во свобо́дного посеще́ния | right of free attendance | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5 idiom (N.B., fitness club dialogue) |
| соверше́нно согла́сна | fully agree | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5 idiom (N.B., fitness club dialogue) |
| силовы́е уро́ки | weight training lessons | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5 idiom (N.B., fitness club advert) |
| ги́бкость | ﬂexibility | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5 idiom (N.B., fitness club advert) |
| мы́шца | muscle | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5 idiom (N.B., fitness club advert) |
| та́нец живота́ | belly dancing | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5 idiom (N.B., fitness club advert) |
| боевы́е иску́сства | martial arts | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5 idiom (N.B., fitness club advert) |
| програ́мма для бере́менных | programme for pregnant women | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5 idiom (N.B., fitness club advert) |
| новоро́жденный | new born | adjective | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5 idiom (N.B., fitness club advert) |
| ски́дка | discount | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5 idiom (N.B., fitness club advert) |
| подво́дное пла́вание | underwater swimming | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5 idiom (N.B., fitness club advert) |
| на пе́рвый взгляд | at ﬁrst glance | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5 idiom (N.B., extreme sport text) |
| на све́те | in the world | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5 idiom (N.B., extreme sport text) |
| на краю´ опа́сности | on the brink of danger | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5 idiom (N.B., extreme sport text) |
| высо́кий сезо́н | high season | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5 idiom (N.B., extreme sport text) |
| счита́ется | it is considered | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5 idiom (N.B., extreme sport text) |
| каскадёр | stunt man | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5 idiom (N.B., stuntmen advert) |
| смерте́льно опа́сный | deadly dangerous | adjectival phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5 idiom (N.B., stuntmen advert) |
| сте́пень ри́ска | level of risk | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5 idiom (N.B., stuntmen advert) |
| заверша́ть | to ﬁnish | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5 idiom (N.B., stuntmen advert) |
| мероприя́тие | event | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5 idiom (N.B., stuntmen advert) |
| звезда́ ро́ка | rock star | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5 idiom (N.B., stuntmen advert) |
| убеди́ться | to be convinced | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 5 idiom (N.B., stuntmen advert) |
| в том-то и де́ло | that's (just) the point | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6 idiom (N.B., film festival dialogue) |
| всего́ | in all | adverb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6 idiom (N.B., film festival dialogue) |
| ему́ удало́сь | he succeeded | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6 idiom (N.B., Dodin text) |
| не случа́йно | not by chance | adverbial phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6 idiom (N.B., Dodin text) |
| звезда́ | star | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6 idiom (N.B., film ratings feature) |
| так себе́ | so-so | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6 idiom (N.B., film ratings feature) |
| отврати́тельно | repulsive | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6 idiom (N.B., film ratings feature) |
| в по́льзу | in favour | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6 idiom (N.B., film ratings feature) |
| впечатли́тельный | impressionable | adjective | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6 idiom (N.B., film ratings feature) |
| си́льный ду́хом | strong in spirit | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6 idiom (N.B., film ratings feature) |
| де́йствующее лицо́ | character | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6 idiom (N.B., film ratings feature) |
| злоде́йка | female villain | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6 idiom (N.B., film ratings feature) |
| вы́ходка | trick | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6 idiom (N.B., film ratings feature) |
| пятни́стая соба́ка | spotty dog | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6 idiom (N.B., film ratings feature) |
| живо́тное | animal | adjective | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6 idiom (N.B., film ratings feature) |
| заба́вный | amusing | adjective | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6 idiom (N.B., film ratings feature) |
| наоборо́т | the other way round | adverb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 6 idiom (N.B., film ratings feature) |
| существу́ет мне́ние | there is an opinion | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7 idiom (N.B., press dialogue) |
| де́ло в том, что | the thing is that | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7 idiom (N.B., press dialogue) |
| за счёт | at the expense of | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7 idiom (N.B., press dialogue) |
| положи́тельно | positively | adverb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7 idiom (N.B., opinion poll) |
| отрица́тельно | negatively | adverb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7 idiom (N.B., opinion poll) |
| затрудни́ться с отве́том | to ﬁnd it difﬁcult to answer | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7 idiom (N.B., opinion poll) |
| сомнева́ться | to doubt | verb | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7 idiom (N.B., opinion poll) |
| предста́вить но́вости под свои́м угло́м | to present news from one's own viewpoint | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7 idiom (N.B., television text) |
| к тому́ же | in addition | conjunctive phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7 idiom (N.B., television text) |
| куда́ бо́лее лоя́льна | much more loyal | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7 idiom (N.B., television text) |
| по отноше́нию к | towards | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7 idiom (N.B., television text) |
| э´то уже́ перебо́р | that is too much | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7 idiom (N.B., channel-numbers debate) |
| сетево́й кана́л | cable channel | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7 idiom (N.B., channel-numbers debate) |
| худо́жественный фильм | feature ﬁlm | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 7 idiom (N.B., TV listings) |
| по за́падным ме́ркам | by Western standards | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 idiom (N.B., job search text) |
| свой челове́к | one of our own people | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 idiom (N.B., job search text) |
| брать на рабо́ту с у́лицы | to hire someone off a public advertisement | verb phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 idiom (N.B., job search text) |
| по бла́ту | using personal connections | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 idiom (N.B., job search text) |
| хорошо́ подве́шенный язы́к | a smooth tongue | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 idiom (N.B., job search text) |
| вне́шние да́нные | appearance | adjectival phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 idiom (N.B., interpreter job advert) |
| командиро́вка | business trip | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 idiom (N.B., interpreter job advert) |
| обя́занность | duty | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 idiom (N.B., interpreter job advert) |
| владе́ние компью´тером | computer literacy | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 idiom (N.B., interpreter job advert) |
| води́тельские права́ | driving licence | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 idiom (N.B., interpreter job advert) |
| резюме́ | C.V. | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 idiom (N.B., interpreter job advert) |
| с отли́чием | with distinction | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 idiom (N.B., interpreter job advert) |
| по́льзователь ПК | computer user | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 idiom (N.B., interpreter job advert) |
| уме́ние рабо́тать в кома́нде | ability to work in a team | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 idiom (N.B., interpreter job advert) |
| собесе́дование | interview | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 idiom (N.B., interpreter job advert) |
| аккура́тный | neat | adjective | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 idiom (N.B., interpreter job advert) |
| ну что же | well | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 idiom (N.B., job interview dialogue) |
| вас э´то устра́ивает? | Does that suit you? | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 idiom (N.B., job interview dialogue) |
| меня́ не устра́ивают усло́вия | the conditions do not suit me | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 idiom (N.B., job interview dialogue) |
| у нас нет прете́нзий | we have no complaints | adjectival phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 idiom (N.B., job interview dialogue) |
| придётся | (you) will have to | verb (impersonal) | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 idiom (N.B., job interview dialogue) |
| мне приходи́лось | I had to | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 8 idiom (N.B., job interview dialogue) |
| по сравне́нию с | in comparison with | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 9 idiom (N.B., demography text) |
| и т.д. (и так да́лее) | and so on | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 9 idiom (N.B., demography text) |
| вверху́ оши́блись | mistakes were made at a high level | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 9 idiom (N.B., demography text) |
| устано́влено | it has been established | noun | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 9 idiom (N.B., demography text) |
| Центр статисти́ческого управле́ния | Centre for Statistical Management | phrase | core | — | contemporary (source published 2003) | — | — | grammar_reference | n/a | n/a | Unit 9 idiom (N.B., demography text) |

## Grammar points

Russian is fusional/six-case per `datasets/Russian/00_Extraction_Checklist.md`'s morphological
typology note; none of the grammar below involves agglutinative morpheme-stacking, so no morpheme
breakdown rows are needed for this source's vocabulary (each headword is a single non-composed
lexical item in the sense the typology guide means).

### Unit 1 (revision unit) — spelling rules and the six-case system (pp. 2–38)

**Spelling rules** (p. 2): after г, к, х, ж, ч, ш, щ, replace ы→и; after ж, ч, ш, щ, ц replace
unstressed о→е, я→а, ю→у. These four rules govern noun/adjective/verb endings throughout the
language and recur constantly in the paradigms below.

**Nominative** (pp. 2–5): subject of the verb; complement of "to be" after это/вот; occasionally
after the past tense of быть for a permanent state (Пушкин был великий поэт). Three genders,
distinguished by the nominative singular ending; a small set of -а/-я nouns denoting male humans
(мужчи́на, дя́дя) decline as feminine but take masculine agreement.

**Accusative** (pp. 8–10): direct object; after motion prepositions в/во, за, на, о/об/обо, по,
под (place/time); expresses duration without a preposition (всю неде́лю). Masculine animate nouns
take genitive-identical accusative endings, both singular and plural.

**Genitive** (pp. 10–17): possession/"of"; after a long list of prepositions (без, вдоль, вне,
внутри́, впереди́, ме́сто, вме́сто, во вре́мя, в тече́ние, для, до, из, из-за, из-под, кро́ме, ми́мо,
напро́тив, о́коло, от, по́сле, про́тив, ра́ди, с/со, среди́, у); the "have" construction (у + genitive
+ была́); after о́ба/о́бе, два/две, три, четы́ре and their compounds (genitive singular) vs. genitive
plural after all other numerals; after мно́го/ма́ло/не́сколько/ско́лько/большинство́ and as a bare
partitive genitive ("some"); in negative constructions (нет/не́ было/не бу́дет; не ви́дно/не слы́шно/
не заме́тно; as direct object of a negated verb — with accusative preferred if the object is
concrete); as direct object of certain verbs (жела́ть, достига́ть/дости́гнуть, боя́ться, ждать,
иска́ть, ожида́ть, проси́ть, тре́бовать, хоте́ть — genitive for abstract objects, accusative for
concrete ones). Some masculine nouns have an alternative partitive genitive in -у/-ю (купи́ ча́ю).

**Dative** (pp. 17–20): indirect object; after ве́рить, помога́ть/помо́чь, сле́довать, сове́товать,
угрожа́ть/грози́ть; with certain reflexive verbs; the impersonal "needed/necessary" construction and
verbs of liking/interest are covered further in Unit 5 (verbs with the dative, p. 108: ве́рить,
грози́ть/угрожа́ть, доверя́ть, зави́довать, меша́ть, подходи́ть/подойти́, позволя́ть/позво́лить,
помога́ть/помо́чь, прика́зывать/приказа́ть, ра́доваться, сле́довать, сове́товать, сочу́вствовать,
удивля́ться/удиви́ться; идёт "it suits" (Вам идёт); принадлежа́ть "to belong" takes bare dative for
possession but к + dative for club/group membership).

**Instrumental** (pp. 22–25): "by/with" the instrument (писа́ть карандашо́м); after verbs of body
movement (маха́ть руко́й, кива́ть голово́й, пожима́ть плеча́ми); after за, ме́жду, над, пе́ред, под, с;
as complement of быть in past/future/infinitive; after a large set of verbs (see Unit 6 below,
where the full list is given); in adverbial time expressions (у́тром, ве́чером, весно́й, ле́том,
о́сенью, зимо́й, це́лыми дня́ми) and manner expressions (шёпотом, бего́м); in dimension expressions
(высото́й, длино́й, ро́стом, ширино́й).

**Prepositional** (pp. 26–28): only case that never occurs without a preposition — в, на, о/об/обо,
при. A handful of masculine nouns take stressed -у́ after в/на specifically (в лесу́, на берегу́, на
полу́, в саду́, в углу́, в про́шлом году́, в шкафу́, в Крыму́).

**Reflexive/emphatic pronouns** (p. 28): себя́ (no nominative) declines the same in all genders;
свой parallels мой/твой in declension but refers back to the subject of its own clause (contrast
eго́, which would mean someone else's). сам is the emphatic "-self" pronoun.

**Short-form (predicative) adjectives** (pp. 28–29): used only as the predicate, separated from
the noun by "to be"; formed by dropping -ый/-ий (masc.), adding -а (fem.), -о (neut.), -ы (plur.);
a linking vowel is sometimes inserted before two final consonants. Adjectives in -ский generally
lack a short form. Adverbs are formed identically to the neuter short-form adjective.

**Verb conjugation** (pp. 29–33): two conjugations — 1st typically -ать/-ять infinitives (endings
-ю/-ешь/-ет/-ем/-ете/-ют), 2nd typically -ить/-еть (-ю/-ишь/-ит/-им/-ите/-ят), with a residue of
1st-conjugation verbs in -ить/-еть/-ти and 2nd-conjugation verbs in -ать/-ять. Present-tense stems
can diverge from the infinitive stem (мыть→мою; писать→пишу; идти→иду); -авать drops -ав-, -овать
replaces -ов- with -у-, -евать replaces -ев- with -ю- in the present. A handful of consonant
mutations occur only in the 1st-person singular of 2nd-conjugation verbs (води́ть→вожу́ but во́дишь).
Irregular verbs: мочь, бежа́ть, хоте́ть, есть. Reflexive verbs add -ся after a consonant/-ь/-й,
-сь after a vowel.

**Aspect** (pp. 33–37): imperfective/perfective infinitive pairs (де́лать/сде́лать), differentiated
by prefix (вы-, за-, на-, о-, от-, пере-, по-, под-, при-, про-, с-, у-), by suffix (реша́ть/реши́ть),
or by an imperfectivizing infix -ыв-/-ив- (подпи́сывать/подписа́ть); a few pairs are suppletive
(говори́ть/сказа́ть, брать/взять, покупа́ть/купи́ть, станови́ться/стать). Imperfective future =
future of быть + imperfective infinitive; perfective future is conjugated directly like a present
tense. Past tense generally replaces infinitive -ть with -л/-ла/-ло/-ли, with irregular classes for
-ере́ть, some -нуть verbs (dropping -ну- in the masculine), -сти́, -ти́, -чь verbs. Imperfective use:
unfinished/continuous or habitual/repeated actions, emphasis on process, and always after начина́ть/
станови́ться, конча́ть, продолжа́ть. Perfective use: emphasis on completion/result (single action or
a completed sequence); a по- prefixed perfective can imply "for a short while."

**Subjunctive & imperative** (p. 37): subjunctive = particle бы + past tense. Third-person
imperative is introduced here in outline; full formation is given in Unit 2 below. Дава́й(те) + 1st
person plural future perfective forms a "let's" construction.

### Unit 2 (Transport, pp. 39–56)

**Imperative formation** (pp. 41–42): strip the last two letters of the 3rd-person plural
(они́ form); add -и after a consonant stem or -й after a vowel stem; -ь if the stem is
single-consonant and stem-stressed throughout. Plural/polite adds -те. Reflexive ending is -сь
after -й/-ь, -ся after -и/-те. Irregular: -авать verbs (дава́й(те)), есть→е́шь(те), пить→пей(те).
Stress matches the 1st-person-singular present. Imperfective imperative = general injunction
(often negative); perfective imperative = one specific occasion.

**Comparatives** (pp. 48–52): long (attributive) comparative = бо́лее/ме́нее + unchanging long
adjective, "than" = хем + comma. Four adjectives (большо́й, ма́ленький, плохо́й, хоро́ший) have a
single-word declinable comparative (бо́льший, ме́ньший, ху́дший, лу́чший) used instead of the бо́лее
form; four more (молодо́й, ста́рый, высо́кий, ни́зкий) have a one-word comparative used only in
figurative/personal senses (мла́дший, ста́рший, вы́сший, ни́зший) alongside the literal бо́лее form.
Short (predicative) comparative = stem + -ее/-ей (invariable across gender/number), preferred when
"to be" separates the compared noun from the comparative, and mandatory in "it is ...-er" sentences;
a sizeable list of adjectives instead take a short comparative in -е with a stem-consonant mutation
(дешёвый→деше́вле, до́рого́й→доро́же, у́зкий→у́же, etc.). After the short comparative, "than" is
rendered by putting the compared noun into the genitive — but only if that noun is in the
nominative and is a genuine noun/pronoun (otherwise хем + comma is used, as with the long form).
Comparative constructions: как мо́жно + comparative "as ... as possible"; хем ... тем "the ...er the
...er"; горазд/наmно́го/куда́ "much ...er"; всё "ever ...er" (repeatable: всё доро́же и доро́же).

**Preposition corner — на + accusative/prepositional** (pp. 53–56): на + accusative for motion "to"
with compass points, nouns denoting originally-open institutions (вокза́л, стадио́н, по́чта), open
spaces, rivers/islands/some mountain ranges, and activity nouns (конце́рт, рабо́та); also many time
expressions (на Рождество́, на друго́й день) and set verb + на collocations (влия́ть на, жа́ловаться
на, наде́яться на, назнача́ть на, опа́здывать на, отвеча́ть на, полага́ться на, походи́ть на,
соглаша́ться на, тра́тить на). На + prepositional mirrors the same noun classes for static "at/on"
location, plus means of transport (на метро́, на авто́бусе) and further time/verb expressions
(на э́той/про́шлой/бу́дущей неде́ле; на дняx; игра́ть на + instrument; жени́ться на "to marry," said
of a man; наста́ивать на; ска́зываться на; сосредото́чиваться на).

### Unit 3 (Tourism, pp. 57–74)

**Verbs of motion** (pp. 65–72): е́здить/е́хать/пое́хать "go by vehicle" and ходи́ть/идти́/пойти́
"go on foot" are the two core pairs. Multidirectional (е́здить, ходи́ть) = repeated/round-trip
journeys, generalisations, or non-specific direction; unidirectional (е́хать, идти) = a single
journey in one direction, even if habitually repeated on a fixed schedule (bus/train timetables use
идёт/е́дет); trains/buses/boats as grammatical subject take ходи́ть/идти́, while е́здить/е́хать serve
cars and passengers. Perfectives пое́хать/пойти́ mark setting off, or a completed one-directional
trip; ездить/ходить (imperfective) mark a completed round trip. Figurative uses are always
imperfective (дождь идёт, дела́ иду́т хорошо́). Prefixed verbs of motion (въезжа́ть/въе́хать,
выезжа́ть/вы́ехать, доезжа́ть/дое́хать, заезжа́ть/зае́хать, объезжа́ть/объе́хать, отъезжа́ть/отъе́хать,
переезжа́ть/перее́хать, подъезжа́ть/подъе́хать, приезжа́ть/прие́хать, проезжа́ть/прое́хать,
разъезжа́ться/разъе́хаться, уезжа́ть/уе́хать — note the -ъ- hard sign after a consonant-final prefix)
each have only one imperfective and are typically followed by a preposition reinforcing the
direction; the same prefix set attaches to -ходи́ть/-йти́ for foot-motion. Other two-imperfective
motion-verb pairs: носи́ть/нести́, вози́ть/везти́, води́ть/вести́, бе́гать/бежа́ть, лета́ть/лете́ть,
пла́вать/плыть, ла́зить/лезть, по́лзать/ползти́, броди́ть/брести́, таска́ть/тащи́ть, гоня́ть/гнать,
ката́ть/кати́ть — prefixed forms shift stems (-плыва́ть, -леза́ть, -та́скивать, -бреда́ть, -ка́тывать,
stress-shifted -бега́ть/-полза́ть). Figurative prefixed-motion idioms: выходи́ть/вы́йти из кри́зиса,
сходи́ть/сойти́ с ума́, приходи́ть/прийти́ в го́лову, проходи́ть/пройти́ регистра́цию, вводи́ть/ввести́
зако́н, заводи́ть/завести́ часы́, наноси́ть/нанести́ уще́рб, переводи́ть/перевести́, расходи́ться/
разойти́сь, разводи́ться/развести́сь; a further set has lost any literal motion sense: происходи́ть/
произойти́ "to happen," приходи́ться/прийти́сь "to have to," находи́ться "to be situated."

**Word-building on the root -ход-** (p. 67): вход/вы́ход/дохо́д/расхо́ды/перехо́д (prefixes shift
direction/meaning); ходи́ть/входно́й/похо́дка/ходьба́/выходно́й are suffix-differentiated by part of
speech; compounded with other roots: парохо́д ("steam" + ход), теплохо́д ("warm" + ход),
пешехо́д(ный) ("foot" + ход), судохо́дный ("vessel" + ход).

**То́же / та́кже** (p. 73): то́же repeats an existing circumstance ("me too"); та́кже = "in addition,"
especially after а/но; то́же can generally be replaced by та́кже but not vice versa.

### Unit 4 (Migration, pp. 75–91)

**Particle ли** (pp. 78–79): frames a yes/no question by fronting the key word (often the verb)
followed by ли (Оправда́лись ли э́ти прогно́зы?); frequently combined with a negative (Не ка́жется
ли вам э́то опа́сным?); the fronted element need not be a verb.

**Reflexive verbs** (pp. 82–84): true reflexives act on the subject itself (одева́ть/одева́ться);
many intransitive verbs take -ся to contrast with a transitive counterpart of identical root
(закры́ть/закры́ться, конча́ть/конча́ться, превраща́ть/превраща́ться, распространя́ть/
распространя́ться, собира́ть/собира́ться, увели́чивать/увели́чиваться, сокраща́ть/сокраща́ться); only
the transitive member may take a following infinitive. Intransitive -ся forms also serve a passive
function (Грани́цы пло́хо охраня́ются), competing with the 3rd-person-plural-as-passive construction
(Пло́хо охраня́ют грани́цы). Some -ся verbs mark reciprocal action (целова́ться "to kiss each other");
others (станови́ться, стара́ться) carry no synchronic reflexive/passive sense at all.

**Ordinal numerals and dates** (pp. 84–86): ordinals are adjectives agreeing with their noun; in a
compound ordinal only the last element inflects (на двадцать четвёртом ме́сте). Trétij has an
irregular declension (given in the grammar summary). Date expressions: пе́рвое ма́я "1st May"
(nominative when it is the date itself), пе́рвого ма́я "on 1st May" (genitive), в две ты́сячи
пе́рвом году́ "in 2001," в девяно́стые го́ды / в девяно́стых года́х "in the 1990s" (note plural
годо́в as genitive plural of год specifically in this construction — otherwise the genitive
plural of "year" after a numeral is лет).

**Preposition в — expressions of place and time** (pp. 88–90): в + accusative "to/into" mirrors the
"на = to" category boundary from Unit 2 (everything not on the на-list takes в); в + prepositional
"in/inside" for the same noun set. Time uses of в + accusative: в како́й день?, в понеде́льник,
в пе́рвый раз, два ра́за в день, and dimension idioms (длино́й в четы́ре ме́тра); за + accusative is
an alternative for "how long it took" (contrast в два часа́ "at 2 o'clock" vs. за два часа́ "in two
hours"). Verb + в + accusative collocations: броса́ть в, ве́рить в, вступа́ть в па́ртию, игра́ть в
(sport), поступа́ть в (institution), превраща́ться в, смотре́ть в окно́/зе́ркало, стреля́ть в,
стуча́ть в дверь. В + prepositional time idioms: в э́том/про́шлом/бу́дущем году́, в XX ве́ке (but
в сре́дние века́), в де́тстве/мо́лодости/ста́рости, в нача́ле/середи́не/конце́; verb collocations:
нужда́ться в, обвиня́ть в, ошиба́ться в, признава́ться в, сомнева́ться в, убежда́ться в,
уча́ствовать в.

### Unit 5 (Sport, pp. 92–110)

**Кото́рый** (pp. 99–100): relative pronoun "which/that/who," declines like a hard adjective; its
number/gender come from its antecedent, its case from its role in its own clause. Кто/что (not
кото́рый) introduce a relative clause referring back to a pronoun rather than a noun (те, о ком
идёт речь; всё, что зна́ю).

**Superlatives** (pp. 100–102): the general construction is са́мый + adjective, agreeing with the
adjective in every respect. The eight one-word comparatives from Unit 2 form superlatives variously
(бо́льший → са́мый большо́й; лу́чший → са́мый лу́чший or bare лу́чший; вы́сший → са́мый высо́кий
(literal) vs. вы́сший (figurative), etc.). A separate synthetic superlative in -е́йший/-а́йший
(after г/к/х stems, which mutate to ж/ч/ш) gives emphatic rather than strictly-superlative force
(нове́йший, велича́йший, глубоча́йший, ближа́йший). Adverb/short-adjective superlative = comparative
+ всего́ ("of anything") or всех ("of anyone/everyone").

**Genitive after cardinal numerals** (p. 99): numerals above one govern the genitive (up to "four"
singular, "five" and above plural) when in the nominative/inanimate-accusative — fully detailed in
Unit 9 below.

**Preposition corner — с, от, из "from"** (pp. 103–108): с + genitive mirrors на's noun-class
boundary for "from" (place, and time: с апре́ля, с трёх часо́в); it can express cause (со ску́ки)
though от is the less-colloquial choice there (от ра́дости); combines with сторона́ (с одно́й
стороны́ ... с друго́й стороны́); with сда́ча "change" (сда́ча с рубля́); + instrumental separately
means "with, together with" or "by means of" without a preposition (writing "with" an instrument
uses the bare instrumental: ре́зать ножо́м). От + genitive = "from a person," "away from" (often
with от- prefixed verbs), and in time ranges с ... до .... От ... до ... measures distance; от can
also mark cause (у́мереть от го́лода) and the set phrase от и́мени "on behalf of." С ... по ...
+ accusative means "up to and including" (contrast с ... до ..., exclusive). Из + genitive = "from"
for the в-class of nouns (place of origin), also source/material (сде́лать из ста́ли) and cause
(из не́нависти).

**Stress on masculine nouns** (pp. 108–110): four patterns — fixed stress throughout; fixed-final
stress moving onto the case ending from the nominative singular on; and two/three types of "mobile"
stress distinguishing stem-stressed singular from ending-stressed plural (with sub-variants on
which plural cases are affected).

### Unit 6 (Cultural Life in Russia, pp. 111–127)

**Alternatives to "to be"** (p. 119): явля́ться/яви́ться + instrumental ("to be/seem," the most
formal substitute); представля́ть (собо́й) + accusative ("to represent, to be" — used with явля́ться
цель́ю, явля́ться сле́дствием, явля́ться ча́стью as set collocations); быва́ть ("to be, frequent,"
used for recurring/habitual presence, "as often happens").

**Verbs governing the instrumental** (p. 120): control verbs (по́льзоваться, руководи́ть,
управля́ть, торгова́ть, владе́ть, занима́ться/заня́ться, злоупотребля́ть, рискова́ть); attitude verbs
(горди́ться, интересова́ться, любова́ться, увлека́ться/увле́чься); state/appearance verbs
(каза́ться,ока́зываться/оказа́ться, станови́ться/стать, счита́ться, остава́ться/оста́ться); others
(же́ртвовать, сла́виться, боле́ть "to be ill with").

**Participles** (pp. 120–125): verbal adjectives replacing кото́рый-clauses. Present active =
3rd-plural present stem minus -т + -щий (получа́ют → получа́ющий), declines like хоро́ший, always
keeps -ся regardless of the preceding letter; can stand in for a кото́рый-clause in the past tense
too, if simultaneous with the main clause. Past active = masculine past tense minus -л + -вший
(получи́л → получи́вший), or bare + -ший where there is no -л (исче́з → исче́зший); irregular
forms for идти́ (ше́дший) and вести́ (ве́дший); always -ся, never -сь. Many active participles have
lexicalised as adjectives (блестя́щий, веду́щий, де́йствующий, сле́дующий, теку́щий, бу́дущий,
бы́вший, реша́ющий, потряса́ющий) or nouns (куря́щий "smoker," слу́жащий "employee," управля́ющий
"manager," учащийся "student," трудя́щийся "worker").

**Preposition corner — о / про** (p. 126): о + prepositional "about, concerning" (becomes об before
vowels, о́бо before certain consonant clusters — о́бо мне, о́бо всём); о + accusative "against, on,
upon" (опира́ться о сте́ну, бок о́ бок); про + accusative is the more colloquial equivalent of о.

**Stress on feminine nouns** (pp. 126–127): fixed-stress class plus five mobile-stress patterns,
paralleling the masculine-noun stress typology from Unit 5 but with different plural-vs-singular
stress-shift points for each type.

### Unit 7 (Mass Media, pp. 128–145)

**-то / -нибудь** (pp. 131–132): both attach to что, кто, како́й (and to gde, куда́, как, когда́).
-то marks an unidentified but existing referent (кто́-то стучи́т "someone [definitely] is
knocking"); -нибудь marks a hypothetical/uncertain referent and can translate "any-" (Кто́-нибудь
хо́чет э́то? "Does anyone want this?"; е́сли кто́-нибудь позвони́т "if someone [should] ring").

**Друг дру́га** (p. 137): "one another" — only the second element declines, like the noun друг;
a governing preposition is inserted between the two halves (отлича́ться друг от дру́га).

**Что/кто as relative pronouns** (pp. 138–140): то, что links clauses corresponding to English
"what"/"that which," with то's case set by the main clause and что's case set by the subordinate
clause; also renders "the fact that" and appears in the fixed frames де́ло в том, что; беда́ в том,
что; пробле́ма заключа́ется в том, что (and other question words can fill the same "в том" slot:
де́ло в том, как/куда́ ...). Тот, кто / те, кто = "the one(s) who," with the same
main-clause/subordinate-clause case split; кто can detach from тот to open its own clause (Кто не
рабо́тает, тот не ест).

**Time and causal conjunctions vs. prepositions** (pp. 141–142): по́сле (preposition) vs. по́сле
того́ как (conjunction); с (preposition) vs. с тех пор как (conjunction) "since"; до vs. до того́
как "before"; пе́ред (+ instr.) vs. пе́ред тем как / пре́жде хем "before." Causal: благодаря́ тому́,
что "thanks to the fact that" (positive reasons) vs. bare благодаря́ + dative "thanks to"; из-за
того́, что "owing to, because of the fact that" (negative circumstances) vs. bare из-за + genitive.

**Stress on neuter nouns** (pp. 143–145): fixed-stress class plus three mobile-stress patterns
(ending-stressed singular/stem-stressed plural; stem-stressed singular/ending-stressed plural,
including most -мя nouns; and a small forward-shifting-in-the-plural class).

### Unit 8 (The Labour Market, pp. 146–162)

**Past passive participles** (pp. 157–160): formed from the perfective verb only (transitive verbs
only). -нный: 1st-conjugation -ать/-ять verbs drop -ть and add -нный (зарабо́тать →
зарабо́танный). -енный/-ённый: 2nd-conjugation -ить/-еть and 1st-conjugation -сти/-зти verbs take
-енный, or -ённый if the future-perfective ты-form is end-stressed (реши́ть → реши́т → решённый);
consonant mutations in the future-perfective я-form carry over (пригласи́ть → приглашу́ →
приглашённый). -тый: a small set of mostly-monosyllabic 1st-conjugation verbs and verbs in -оть,
-уть, -ыть, -ере́ть (взять → взя́тый, приня́ть → при́нятый, закры́ть → закры́тый, запере́ть →
за́пертый, losing the -е-). Participles decline like adjectives and agree with their noun; a short
form (one -н-, short-adjective endings) forms the passive voice (Ко́нтракт бу́дет подпи́сан за́втра),
with stress shifting to the ending in -ённый participles; the agent is expressed by the bare
instrumental (Пье́са была́ поста́влена ру́сским режиссёром). Some past passive participles function
as ordinary adjectives (образо́ванная же́нщина, дипломи́рованный специали́ст) or as nouns (да́нные
"data," заключённый "a prisoner").

**Preposition за + accusative/instrumental** (pp. 160–162): за + instrumental = "behind/beyond"
(за до́мом, за угло́м, за грани́цей "abroad," зá городом "out of town" — note the shifted stress on
за before certain nouns when used with a following motion verb + accusative: зá гору, зá город) and
"at" an activity (за рулём, за обе́дом, за столо́м, за компью́тером). За + accusative = "during the
course of" (за три го́да), "before" with до (за час до нача́ла), "for" after verbs/nouns of payment,
thanks, praise, criticism, voting (благодари́ть за, хвали́ть за, плати́ть за, критикова́ть за,
голосова́ть за; благода́рность за); за + instrumental = "(to go) for, to fetch" (посыла́ть за
врачо́м, идти́ за по́мощью) and "to look after" (смотре́ть за детьми́).

**Word-building on the root труд-** ("labour, hard work," p. 151): труди́ться, трудово́й,
тру́женик/тру́женица (d→ж before -ник/-ница), трудя́щийся (Soviet officialese for "worker," now
usually replaced by рабо́чий/рабо́тник); prefix с-/со- "with, co-" gives сотру́дник "colleague,"
-ство gives сотру́дничество "cooperation"; compounded with other roots: трудоустро́ить(ся)/
трудоустро́йство "to fix (oneself) up with work / job-placement," трудоспосо́бный/
трудоспосо́бность "fit/fitness for work." Set phrase: с трудо́м "with difficulty."

### Unit 9 (Demography, pp. 163–172 — partial; continues in the sibling file)

**Cases after cardinal numerals** (pp. 168–169): оди́н/одна́/одно́ (plural одни́ for plurale-tantum
nouns) is a true agreeing adjective; два/две, три, четы́ре, о́ба/о́бе take genitive singular
noun + genitive plural (masc./neut.) or nominative plural (fem.) adjective; пять and above take
genitive plural for both noun and adjective; a compound numeral's case-government is set by its
last element. These noun/adjective-case rules hold only when the numeral itself is nominative or
inanimate-accusative — a numeral in any other case (e.g. after a preposition) throws the following
noun and adjective into the plural of that same case. Only два/две, три, четы́ре, о́ба/о́бе have a
distinct animate accusative, and it is not used within compound numerals. All elements of a
compound numeral decline when the numeral itself is declined (с пятидесяти́ пяти́ до шести́десяти
четырёх; в во́зрасте пяти́десяти восьми́ лет), including telling the time (в два часа́; с двух
часо́в).

**Collective numerals** (p. 169): дво́е, тро́е, че́тверо (genitive plural following; extending to
пя́теро–де́сятеро for five–ten) are used with plurale-tantum nouns lacking a genitive singular
(тро́е часо́в, че́тверо су́ток) and commonly with animate masculine nouns and with лю́ди/лицо́/де́ти
(дво́е мужчи́н, тро́е люде́й, пя́теро дете́й); they cannot form compounds (use па́ра/шту́ка instead:
два́дцать три па́ры часо́в). Set phrases: нас бы́ло тро́е; мы/нас дво́е; ко́мната на двои́х; на
свои́х двои́х "on foot."

**Quantitative nouns** (p. 169): едини́ца, дво́йка, тро́йка, четвёрка, пятёрка, шестёрка, семёрка,
восьмёрка, девя́тка, деся́тка — used for playing cards and for Russia's five-point school marking
scale (тро́йка "satisfactory," пятёрка "excellent"); семёрка also renders "the Seven" (G7-style
groupings).

**Other numerical expressions** (p. 169): вдво́е/втро́е бо́льше "twice/three times as much" vs.
в два/три ра́за бо́льше "twice/three times as big"; вдвоём/втроём "the two/three of them together"
is a distinct construction from the collective numerals above.

**Indefinite numerals** (pp. 171): не́сколько "several," ско́лько/сто́лько "how many/so many"
decline like plural adjectives; мно́го/немно́го decline in both numbers; ма́ло does not decline.
Челове́к is used as the genitive plural after не́сколько/ско́лько/сто́лько and after a bare numeral
with no following adjective; люде́й is used after ма́ло/мно́го/немно́го and is more usual once an
adjective is present (де́сять хороши́х люде́й).

**Fractions and decimals** (pp. 171–172): a feminine ordinal expresses a fraction (words часть/
до́ля understood): одна́ шеста́я "one sixth"; треть and че́тверть are used instead of the regular
ordinal fraction for "a third"/"a quarter." Decimals use the ordinal-fraction words for tenths/
hundredths/thousandths and always take a genitive singular noun (69,6 го́да); Russian uses a comma
where English uses a decimal point.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `../../00_Reference_Extraction_Spec.md`. The vocabulary
table above restructures the book's own boxed headword/gloss pairs (2–4 word glosses) into this
project's standard schema rather than reproducing any vocabulary box's own layout, footnote
numbering, or surrounding explanatory prose; the grammar-points section paraphrases the book's
explanations in original wording throughout, with only isolated short illustrative phrases quoted
directly.
