# Serbian/Croatian/Bosnian — Established Grammar: Colloquial Serbian and Croatian, "Grammar summary"

**Source:** Celia Hawkesworth, *Colloquial Croatian and Serbian: The Complete Course for Beginners*
(Routledge, 1998), "Grammar summary" section, printed pp. 234–255 (PDF pages 242–263 of
`03.Colloquial Serbian and Croatian.pdf`). "Key to main exercises" begins on printed p. 256 (PDF
page 264) and is correctly excluded (drill answers, no content value per the coverage rule).

**Vision-reading guard.** This PDF has no usable text layer for this range — vision-read in full via
`pdftoppm -png -r 150` page images. One page (printed p. 253, PDF 261) is captioned by the book
itself as *"Here is an example of handwritten Cyrillic (See Lesson 20, page 217)"* and reproduces a
full handwritten cursive-Cyrillic letter across printed pp. 253–255 (PDF 261–263). **This was
checked and is the book's own printed/photo-reproduced pedagogical facsimile, not a previous
owner's marginalia** — it is explicitly introduced and captioned as source content, appears as a
clean, consistent single hand across three full pages (not a pencil annotation in a margin or
answer blank), and directly illustrates the cursive-Cyrillic letterforms the "Examples of Cyrillic
script" section (§10) is about. No genuine reader-added marginalia (stray pencil marks, underlining,
answer-key guesses) was found anywhere in the assigned range.

**Non-redundant supplement — scope decision.** This project has already extracted three other
reference grammars for this language cluster (`established/023` and `024` from Alexander &
Elias-Bursać's Textbook appendices; `established/037`–`045` from Alexander's *A Grammar with
Sociolinguistic Commentary*; `established/046`–`058` from Hammond's *Serbian: An Essential
Grammar*), all of which cover the same core-grammar territory a "grammar summary" chapter
necessarily overlaps with. Checked against those files directly before writing this one:

- **Skipped as fully redundant:** full noun declension paradigms (masc./neut./fem., all cases,
  singular and plural — `established/023` already tabulates these in comparable or greater detail);
  full adjective declension paradigms, definite/indefinite forms, and the soft-stem adjective
  pattern (`023`, `038`); personal pronoun declension (`023`, `052`); the verb-type/conjugation-class
  system by infinitive ending (`024` Appendix 9 gives the same three-type present-tense-ending
  system with a fuller ~500-verb classification; this book's version is a shorter restatement using
  the same logic, so only the handful of illustrative pairs not already logged are noted below);
  aorist, imperfect, pluperfect, and future perfect tense formation and the historic-present
  narrative device (`established/041` already gives a fuller formal treatment across verb types,
  including the archaic-aorist alternate set and the aorist-vs-imperfect literary-register
  distinction; `established/064` covers pluperfect/future-perfect drilling); question formation with
  `zar ne` / `je li` / `zar` (already covered in `established/007`, `048`, `049`); basic collective
  numerals (`dvoje`, `troje`... `-oro` series) and number nouns (`dvojica`, `trojica`... in `-ica`)
  (`established/019`, `056` §14.4–14.5 already cover formation, agreement, and use with `deca`); the
  consonant-alternation charts for `k/g/h + i → c/z/s` and `k/g/h + e → č/ž/š` (already covered in
  `established/024`, `045`, `047`, `053`, `009`); the palatal `j`-triggered consonant mutation table
  used in adjective comparison (`p→plj`, `b→blj`, etc. — already covered in `established/038`,
  `045`); voiced/unvoiced consonant assimilation (`established/045` phonology chapter). Section 10
  ("Examples of Cyrillic script") is a Cyrillic-transliteration reading exercise reproducing dialogue
  and reading-passage text that appears in Latin script earlier in the same book (Lesson 1–2
  dialogues; the "Love story" ending; the printed-p.231 reading passage on Croatia/Bosnia/Serbia/
  Montenegro) — no new vocabulary or grammar, so it is not re-extracted; only the section's existence
  and purpose (transliteration practice into Serbian-variant Cyrillic, plus a handwritten-cursive
  facsimile) is noted here for completeness.
- **Genuinely new/deeper, extracted below:** the **"Mobile a"** section (§5) — a named, systematic
  rule for epenthetic `-a-` insertion across nouns and adjectives — was not found anywhere else in
  this project's corpus for this language (checked via grep across all `established/` files) and is
  extracted in full. The **collective/distributive numeral declension paradigms** (§9) go beyond
  `established/019`/`056`'s coverage of formation and agreement: this source gives the actual case
  paradigm tables for masculine collective numerals (`dvojica`-type, obsolescent oblique forms) and
  for the *distributive* adjectival numerals (`dvoji/dvoja/dvoje`, `petori/petora/petore` — full
  M/N/F paradigm, used with pluralia tantum and paired-item nouns like `dvoje cipele` "two pairs of
  shoes"), which neither prior file tabulates. The masculine/feminine `oboje` vs. `obojica` "both"
  distinction (§9) is new — `established/056` only logs `oboje`, not `obojica`. A few `-ati`/`-ivati`/
  `-avati`/`-ci`-infinitive present-tense model pairs not previously logged are added as brief
  grammar-point examples (not a vocabulary table, since these are grammatical illustration, not new
  lexemes).

No morpheme breakdowns are included — BCS is fusional, and no agglutinative/composed forms occur in
this chunk beyond ordinary case/number inflection already conventionally treated as paradigm
declension, not morpheme-by-morpheme composition.

---

## Vocabulary

Only genuinely new lexical items (not already tabulated anywhere else in this project's corpus,
confirmed by direct search) are listed; see the scope note above for what was deliberately skipped.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| legenda | legend | noun (fem.) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | p.240, §5 "Mobile a" — feminine noun taking the alternative -i genitive plural (legendi) instead of mobile-a insertion |
| obojica | both (all-male group) | numeral (collective, masc.) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | verified | p.246, §9 "Both" — contrasts with mixed-gender oboje (already logged in established/056); example: Poznajem njena dva brata, obojica su zgodna |

## Grammar points

### Mobile a (epenthetic -a- insertion)

A rule not previously captured elsewhere in this project's corpus, presented as a named,
systematic pattern (p. 240–241):

- **Masculine nouns** ending in two consonants other than `st`/`zd`/`št`/`žd` insert `-a-` between
  those consonants in the nominative singular and genitive plural (nominative form already has the
  `a`; it drops in other case forms): `momak` → G.sg. `momka`, G.pl. `momaka` ("lad"); `pas` →
  `psa`/`pasa` ("dog"); `borac` → `borca`/`boraca` ("warrior").
- **Masculine nouns** whose stem-final `l` has become `o` in the nominative also show this pattern:
  `ugao` → `ugla`/`uglova` ("corner"); `posao` → `posla`/`poslova` ("work, job").
- **Neuter nouns** with a stem-final consonant cluster may take mobile `a` in the genitive plural
  only: `pismo` → G.pl. `pisama` ("letter"); `društvo` → `društava` ("society").
- **Feminine nouns** in `-a` preceded by two consonants may take mobile `a` in the genitive plural:
  `djevojka` → `djevojaka` ("girl"); `sestra` → `sestara` ("sister") — but the alternative genitive
  plural in `-i` has replaced this in many such nouns, e.g. `legenda` → `legendi`, not `*legenda`.
- **Adjectives** with a stem ending in two consonants (other than `st`/`zd`/`št`/`žd`) may take
  mobile `a` to form the indefinite masculine singular: definite `dobri` / indefinite `dobar`
  ("good"); `kratki`/`kratak` ("short"); `radosni`/`radostan` ("joyous"); `topli`/`topao` ("warm" —
  footnoted rule: *all* adjectives with final `l` derived from `o`, including active past
  participles, fall in this category).
- The `a` in `sav`, `kakav`, `takav`, `nikakav` (etc.) is also mobile by the same pattern.

### Verb-type present-tense prediction (supplementary examples only)

The book's three-type present-tense-ending system (I `-am`/`-aju`, II `-im`/`-e`, III `-em`/`-u`)
duplicates `established/024`'s fuller Appendix-9 classification; only a few specific illustrative
infinitive/present pairs not already logged elsewhere are added here as grammar-point examples: the
`-ivati`/`-ovati` pattern replaces `-iv-`/`-ov-` with `-uj-` before type III endings
(`stanovati`→`stanujem` "to reside"; `pokazivati`→`pokazujem` "to show"); the `-avati` pattern adds
`-j-` to the stem-final `a` before type III endings (`davati`→`dajem` "to give";
`prodavati`→`prodajem` "to sell") — but note the exception where `-av-` is retained as part of the
stem (`pokušavati`→`pokušavam` "to try," not *`pokušajem`). Infinitives in `-ći` always have a
different present-tense stem (`reći`→`reknem`, `pomoći`→`pomognem`, `ići`→`idem`, `doći`→`dođem`).

### Distributive and collective-numeral declension (paradigms beyond established/019, 056)

Building on the collective-numeral (`dvoje`, `troje`...) and number-noun (`dvojica`, `trojica`...)
formation and agreement rules already logged in `established/019` and `established/056` §14.4–14.5,
this source additionally gives:

- The (now largely obsolete, literary-only) **oblique-case declension of neuter collective
  numerals**: genitive `dvoga`, `troga`, `četvorga`; dative/prepositional/instrumental
  `dvomu`/`dvoma`, `tromu`/`troma`, `četvormu`/`četvorma`. These forms are never used after a
  preposition in the modern language but occasionally occur in oblique cases without a preposition
  (`Nama dvoma je govorio` "He spoke to the two of us"). (p. 246)
- **"Both"**: `oboje` is used for a mixed or unspecified-gender pair (`Imam sina i kćer, oboje su
  kod bake` "I have a son and a daughter, they are both at their grandmother's"); `obojica` is used
  specifically for two males (`Poznajem njena dva brata, obojica su zgodna` "I know her two
  brothers, both are good-looking"). (p. 246)
- **Distributive numerals** — adjectival forms of the neuter collective numerals, declined to agree
  in gender/case/number with the noun they qualify. They are obligatory (not merely stylistic) in
  two situations: (a) with nouns that exist only in the plural (*pluralia tantum*), e.g. `dvoja
  vrata` "two doors," `troje novine` "three newspapers"; and (b) with nouns denoting paired items,
  e.g. `dvoje cipele` "two pairs of shoes," `troje čarape` "three pairs of socks," `četvore oči`
  "four eyes' worth" (i.e. two people's worth of wide-open eyes, idiomatically "eyes wide open").
  Full paradigm given for the `dvoji`-type (M `dvoji`/G `dvojih`/D `dvojim`/A `dvoje`/P·I `dvojim`,
  parallel N `dvoja`/`dvoje` for N and F genders) and the `petori`-type (`petori`/`petorih`/
  `petorim`/`petore`/`petorim`, parallel for N `petora` and F `petore`) — the same declension
  pattern extends to all distributive numerals above two. Example: `Čitali smo istu vijest u
  trojim novinama` "We read the same piece of news in three papers"; `Brava na dvojim vratima se
  slomila` "The lock on two doors is broken." (p. 247)

### Section 10, "Examples of Cyrillic script" — not extracted (redundant by design)

This section is explicitly framed by the book as Cyrillic-transliteration reading practice, not new
teaching content: it reproduces (in the Serbian-variant Cyrillic alphabet) dialogue text from
Lessons 1–2, the "Love story" letter conclusion, and the Croatia/Bosnia-Herzegovina/Serbia/
Montenegro reading passage that were all already presented in Latin script earlier in the book. The
section closes with a facsimile handwritten cursive-Cyrillic letter (see the Vision-reading guard
note above) — again illustrative of already-known content (a personal letter, structurally similar
to other correspondence-register text in this book), not new grammar or vocabulary. No portion of
this section met the coverage-rule bar for extraction.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`.
