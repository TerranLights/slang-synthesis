# Japanese — Established Vocabulary/Grammar: The Complete Idiot's Guide to Conversational Japanese — Part 1 (Chs. 1-3) and Part 2 (Chs. 4-7)

**Source:** Naoya Fujita, Ph.D., *The Complete Idiot's Guide to Conversational Japanese* (Alpha
Books/Penguin, 2002), pp. 1-90 (Chapters 1-7: "Can I Really Learn Japanese on My Own?", "Behind
the Language", "Japanese Sounds", "Speak Like Yoda: Basic Sentence Structure", "Everything You
Need to Know About Conjugation", "Other Grammar Essentials", "Numbers"). Source file:
`source_reference/languages/Japanese/07.Dictionaries, Phrasebooks/The Complete Idiots Guide to
Conversational Japanese.pdf`, 433 pages, genuine clean text layer confirmed via `pdftotext`
(no vision-reading needed for this file).

**Numbering note.** The dispatch instruction for this book specified output path
`098_complete_idiots_guide.md`, but `098`/`098b`/`098c` were already in use on disk for a
different, unrelated Wave 4 book ("More Making Out In Japanese") by the time this subagent ran —
a genuine numbering collision between concurrently dispatched Wave 4 chunks, not a duplicate of
this book. Per the spec's check-first duplicate-prevention rule, this subagent did not overwrite
that file; it used the next free number on disk (`102`) instead. Flag this for whoever does the
serialized checklist pass, since the Output files table will need `102`/`102b`/etc., not `098`.

**Coverage note — heavy redundancy with the existing Japanese grammar corpus, handled as a
non-redundant supplement.** This book's Parts 1-2 (phonology, sentence structure, particles,
conjugation, numbers) cover exactly the same beginner-grammar territory as dozens of
already-extracted Japanese sources (Waves 1-3: the 18-file particle dictionary series `032*`, the
12-file Barron's grammar series `035*`, `029`/`030`/`031` basic/intermediate/advanced grammar
dictionaries, `042`/`043` verb references, the phonology-focused `001`-`003` kana/writing files,
etc.). Per the extraction spec's "non-redundant supplement" dispatch pattern, this file does
**not** re-tabulate basic particle functions, verb/adjective/noun conjugation paradigms, or the
kana sound-inventory chart in full — all of that is already captured elsewhere in more systematic
detail. What is extracted here is only the genuinely new content this particular book
contributes:

- An explicit **three-tier politeness/register example** for a single verb ("I'm going") that this
  book gives as a worked illustration of Japanese formality gradients — concise and directly
  useful for register-tier modeling.
- The **loanword ("gairaigo") phonological-adaptation rules** (how English sounds get substituted
  when borrowed into Japanese) plus the worked example table — this is a genuine **mechanism**
  (not just vocabulary) directly relevant to how slang/loanwords get phonologically naturalized,
  and isn't duplicated in the grammar-dictionary corpus already extracted.
- The **full Numbers chapter vocabulary** (0-10, 11-20, tens, hundreds, thousands, ten-thousands,
  plus the counter system) — numbers are vocabulary items in their own right and this book's
  table is complete and compact.
- A few isolated sentence-final-particle and sociolinguistic notes (ne/yo, TPO, "nail that sticks
  out" proverb) that add color but aren't systematically covered elsewhere.

Repeated conjugation drill exercises, the full kana syllabary chart (already covered exhaustively
by `001`-`003` and others), and routine particle-function restatements are skipped as redundant.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Iku. | "I'm going." | verb (plain/casual form) | colloquial | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | n/a | p.15. Book's own 3-way register ladder for the same proposition, explicitly glossed casual→polite→very formal. |
| Ikimasu. | "I'm going." | verb (polite/-masu form) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | n/a | p.15. Middle tier of the same register ladder. |
| Mairimasu. | "I'm going." | verb (humble/formal register) | formal | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | n/a | p.15. Top (most formal/humble) tier — book explicitly labels this "very formal." |
| Deru Kui-wa Utareru | "A nail that sticks out is pounded down." | proverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | n/a | p.16. Cited as the proverb underlying Japanese group-conformity norms; directly relevant to understanding social pressure against standing out, a recurring theme in slang/in-group marking generally. |
| burū | adapted loanword "blue(s)" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | n/a | p.27. Illustrates the L→r substitution rule (English l → Japanese r); "blues" and "Bruce" both become burūsu. |
| sādo | adapted loanword "third" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | n/a | p.27. Illustrates TH→s/z substitution; "third" → sādo. |
| zatto | adapted loanword "that" | demonstrative (loanword use) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | n/a | p.27. Illustrates TH→z substitution; "that" → zatto. |
| saNkyū | "Thank you" (loanword, casual) | interjection | colloquial | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | n/a | p.27. Explicitly flagged by the book as a casual/young-people's loanword form of "thank you," used alongside domo. |
| baioriN | adapted loanword "violin" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | n/a | p.27. Illustrates V→b substitution; "violin" → baioriN. |
| besuto | adapted loanword "best"/"vest" (homophonous pair) | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | n/a | p.27. Both "vest" and "best" collapse to besuto under the V→b rule — a genuine merger/homophony created by the adaptation rule itself. |
| faN | adapted loanword "fan" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | n/a | p.27. Illustrates the Japanese f (breathy, non-labiodental) standing in for English f. |
| kafe | adapted loanword "café" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | n/a | p.27. |
| fōku | adapted loanword "fork"/"folk" (homophonous pair) | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | n/a | p.27. Book notes certain English dialects' "wh" (as in "what") also approximates this same Japanese f sound. |
| bīru | adapted loanword "beer" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | n/a | p.28. From the "Japanizing English food words" table; vowel-lengthening pattern bi-i-ru. |
| haNbāgā | adapted loanword "hamburger" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | n/a | p.28. |
| suteki | adapted loanword "steak" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | n/a | p.28. |
| sūpu | adapted loanword "soup" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | n/a | p.28. |
| sarada | adapted loanword "salad" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | n/a | p.28. |
| doresshiNgu | adapted loanword "dressing" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | n/a | p.28. |
| naifu | adapted loanword "knife" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | n/a | p.28. |
| supūN | adapted loanword "spoon" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | n/a | p.28. |
| pureeto | adapted loanword "plate" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | n/a | p.28. |
| menyū | adapted loanword "menu" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | n/a | p.28. |
| jūsu | adapted loanword "juice" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | n/a | p.28. |
| kōhī | adapted loanword "coffee" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | n/a | p.28. |
| kōra | adapted loanword "cola" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | n/a | p.28. |
| dezāto | adapted loanword "dessert" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | n/a | p.28. |
| kēki | adapted loanword "cake" | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | n/a | p.28. |
| karaoke | "empty orchestra" (kara "empty" + oke, shortened from okesutora "orchestra") | noun (compound) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | n/a | p.24. Worked example of a clipped-compound coinage; also cited as a model for dejikame (dejitaru kamera, "digital camera") and hebimeta (hebī metaru, "heavy metal") — i.e. this book explicitly identifies the same clipping-compound mechanism as productive for at least 3 separate loanword coinages. |
| zero / ichi / ni / saN / yoN (shi) / go / roku / nana (shichi) / hachi / kyū (ku) / jū | 0-10 | numeral | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | n/a | p.81-82. 4 is avoided as shi because it's homophonous with "death" (死) — book explicitly flags this taboo-avoidance substitution (yoN preferred); similarly 7 has two readings (shichi/nana) and 9 has two (kyū/ku). |
| jū ichi ... jū kyū | 11-19 | numeral | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | n/a | p.82. Formed as "ten-one," "ten-two," etc. |
| ni-jū / saN-jū / yoN-jū / go-jū / roku-jū / nana-jū / hachi-jū / kyū-jū | 20/30/40/50/60/70/80/90 | numeral | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | n/a | p.83. |
| hyaku / ni-hyaku / saN-byaku / yoN-hyaku / go-hyaku / rop-pyaku / nana-hyaku / hap-pyaku / kyū-hyaku | 100/200/300/400/500/600/700/800/900 | numeral | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | n/a | p.84. 300/600/800 take irregular euphonic forms (saN-byaku, rop-pyaku, hap-pyaku) explicitly flagged by the book as avoiding tongue-twister sequences. |
| seN / ni-seN / saN-zeN / yoN-seN / go-seN / roku-seN / nana-seN / has-seN / kyū-seN | 1,000-9,000 | numeral | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | n/a | p.85. 3,000 and 8,000 take irregular forms (saN-zeN, has-seN). |
| ichi-maN ... jū-maN | 10,000-100,000 | numeral | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | n/a | p.86-87. Japanese counting restarts a new unit every 4 digits (10,000 = man), not every 3 as in English — book notes this convention originated in China. |
| -mai | counter: thin, flat objects (paper, CDs, plates, T-shirts) | counter suffix | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | n/a | p.88-89. Full 1-10 paradigm given (ichi-mai...jū-mai, naN-mai "how many?"). |
| -satsu | counter: bound objects (books, magazines) | counter suffix | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | n/a | p.89. |
| -hoN | counter: long objects (pens, carrots, sticks) | counter suffix | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | n/a | p.89. |
| -ko | counter: small objects (fruits, erasers, marbles) | counter suffix | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | n/a | p.89. |
| -dai | counter: machinery (cars, computers) | counter suffix | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | n/a | p.89. |
| -hiki | counter: small animals (dogs, cats, rabbits) | counter suffix | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | n/a | p.89. |
| -tō | counter: large animals (lions, elephants, horses) | counter suffix | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | n/a | p.89. |
| -niN | counter: people | counter suffix | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | n/a | p.89. Irregular for 1 and 2 (hitori, futari — see the Part 3 companion file for the full counting-people paradigm). |

## Grammar points

### The three-type conjugation system (verb/adjective/noun predicates)

The book organizes all Japanese predicates into exactly three conjugation classes — verb
predicates, adjective (i-adjective) predicates, and noun predicates — each with its own affirmative/
negative × present/past paradigm (pp.45-56). This is standard material covered in exhaustive detail
by the existing particle/grammar-dictionary corpus (`029`-`031`, `035*`, `042`-`043`); not
re-tabulated here. One point worth flagging: the book frames Japanese tense as a strict
past/non-past binary (present tense covers both present and future meaning, e.g. mi-masu = "watches"
or "will watch," p.48) — a clean, explicit statement of this typological point that's useful to have
on record even though it's implicit elsewhere.

### Loanword phonological adaptation rules (gairaigo)

Pp.27-28. When English words are borrowed into Japanese, systematic sound substitutions apply
because Japanese has a smaller phoneme inventory:

- **L → r**: English l is replaced by Japanese r (burūsu for both "blues" and "Bruce").
- **TH → s/z**: th becomes s or z depending on voicing (sādo "third," zatto "that").
- **V → b**: English v is replaced by b (baioriN "violin"; besuto covers both "vest" and "best,"
  a genuine homophony created by the substitution).
- **F → Japanese f**: the Japanese f is produced without lower-lip contact (closer to a breathy h/f
  blend); the book notes this is close to the "wh" sound in some English dialects (e.g. Southern
  American "what").
- Three general output rules the book states explicitly: use only Japanese sounds, attach a vowel
  to every consonant (since Japanese syllables are open), and drop English stress accent.

This is a genuine, extractable **mechanism** for phonological nativization of loanwords —
directly useful for modeling how a conlang/slang register would adapt borrowed terms, distinct from
a simple vocabulary list.

### Topic-comment sentence structure (-wa) and free word order

Pp.33-44. Briefly noted for completeness since it's this book's own framing device ("Speak Like
Yoda"): Japanese marks grammatical roles with postpositional particles (-ga subject, -o object,
-ni/-kara/-made/-de/-to locational/directional) rather than fixed word order, and treats "topic"
(marked by -wa) as a structurally distinct slot from "subject" — a sentence is framed as
TOPIC + COMMENT, and any previously established topic/understood referent can be dropped entirely
(zero-anaphora), which the book contrasts directly with English's obligatory pronoun retention.
Fully redundant with the particle-dictionary corpus already extracted; recorded here only as a
pointer, not re-tabulated.

### Sentence-final particles ne ("agreement-seeking") and yo ("information-giving")

P.108-109 introduces these two pragmatic particles with exactly those functional labels (the
book's own terminology, not a standard linguistics term) — ne invites listener agreement/
confirmation, yo asserts new information to the listener. Useful shorthand terminology if later
mechanics-analysis work wants a quick functional gloss for these two particles.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`.
