# Russian — Established Vocabulary/Grammar: *Troika: A Communicative Approach to Russian Language, Life, and Culture*

**Source:** Dawson, Middlebrook, Lynn Visson, Nadia Peterson (various editions cite Dawson/Mills/et
al.), *Troika: A Communicative Approach to Russian Language, Life, and Culture* — full text, all 18
lessons (Уроки 1–18) plus back-matter Grammar Reference, Russian-English Glossary, and
English-Russian Glossary, pp. 1–628 (whole book scanned/sampled for this pass).

**Coverage note — non-redundant-supplement pass, applied aggressively.** *Troika* is a standard
mainstream first-year-college communicative-approach Russian textbook: 18 thematic lessons each
covering a THEMES/CULTURE/STRUCTURES trio (see Contents, pp. xvi–xxix), a consolidated Grammar
Reference (pronouns, prepositions+cases, location/direction, numbers, time expressions, verb
conjugations, pp. 531–548), and full bidirectional glossaries (pp. 549–600). Its grammar scope
(cases, verbal aspect, motion verbs, comparatives, imperative, dative/instrumental constructions,
short adjectives, etc.) is comprehensively duplicated by the ~30 already-extracted first-year/
intermediate Russian courses in this corpus (Wave 1 grammars `001`–`029`, Wave 2/3 courses
including `049` Colloquial Russian Complete Course, `053` Let's Talk About Life, `068` Survival
Russian, `073` New Penguin Russian Course, `076` Ultimate Russian Advanced, among others).

Given this, extraction here used **full-corpus cross-checking rather than page-by-page
re-transcription**: the book's text layer was dumped in full (`pdftotext -layout` and `-raw`, both
clean — see gotcha below) and searched for every explicit register/dialect annotation
(`coll.`, "colloquial", "informal", "regional", "dialect", "slang", "жарг", "разг"), every
grammar-point candidate not already attested in `established/`, and every genuinely distinctive
idiom/cultural-pragmatic item, rather than assuming redundancy wholesale. **Confirmed redundant and
skipped in full:** the case system, verbal aspect, motion-verb prefixation, comparative/superlative,
imperative, dative/instrumental/genitive constructions, collective numerals (двое/трое/четверо/
пятеро — independently cross-checked against `001f/001j/001k/001l`, `004`, `006`, `010`, `024`,
`025`, `052`, `053`, `062f/062k`, `067`, `070`, `077`, all of which already document this),
formal/informal ты/вы address (documented pervasively elsewhere), and the two back-matter
glossaries (549–600), whose ~1,000+ entries duplicate vocabulary already captured verbatim from
other full-course glossaries (`019`–`021`, `044`, `060`, `068`). No dialectal/regional tags of any
kind were found anywhere in the book (`grep`'d for explicit markers — none). No genuine
slang/argot register beyond a handful of `coll.`-tagged glossary entries, documented below. **Kept:**
the small set of genuinely new items below, plus one PDF-extraction and one glossary-notation
gotcha worth flagging.

### PDF extraction gotcha (new, not previously catalogued for Russian)

`pdftotext` (both `-layout` and `-raw`) produces a genuine, clean, readable text layer for this
source — bolded core vocabulary lists extract perfectly. However, **pedagogically stressed vowels
inside exercise/dialogue prose (not inside bolded vocabulary-list terms) render as the uppercase
version of that same Cyrillic letter substituted mid-word**, e.g. `шахматИст` for шахмати́ст
(stress on и), `нИзкая` for ни́зкая, `РодИтели` for роди́тели. Verified via codepoint inspection:
these are literal capital-letter codepoents (U+0418 И, etc.), not combining accent marks or a
substitution cipher — the source's stress-indicator font style maps a stressed lowercase vowel to
its uppercase form. This is fully decodable (lowercase the mid-word capital to recover the correct
spelling; the capital's position marks the stress syllable) and did not block vocabulary extraction,
since bolded vocabulary-box terms are apparently typeset without this stress-marking style and
extract clean. One isolated, non-systematic exception was found (`недовбльны` for недовольны, о→б)
in a single drill sentence — inconsistent elsewhere in the same sentence pattern, likely an
unrelated one-off scan/font glitch rather than a cipher; not worth decoding since it falls in
skipped drill material.

### Glossary-notation ambiguity

The back-matter glossaries and in-lesson vocabulary boxes use the abbreviation **`coll.`** for two
unrelated things without visually distinguishing them: (1) grammatical **collective/uncountable
noun** (виноград "grapes," картофель "potatoes," морковь "carrot" — mass nouns with no natural
plural), and (2) genuine **colloquial register** (парень "guy," попа "buttocks," euphemistic/
informal). Only sense (2) is relevant to this project's register tracking; sense (1) was excluded
as redundant grammatical trivia already covered by this corpus's noun-class documentation.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| попа | buttocks (child-friendly/euphemistic) | noun, f. | colloquial | — | contemporary (source published, various eds. 1990s–2000s) | — | — | grammar_reference | n/a | n/a | Source's own glossary explicitly tags this `coll.` (colloquial register, distinct from the same abbreviation's grammatical-collective-noun sense used elsewhere in the same glossary — see gotcha note above); not previously captured as a distinct headword in this corpus |
| парень | guy, fellow | noun, m. | colloquial | — | contemporary (source published) | — | — | grammar_reference | n/a | n/a | Source's own translation-exercise key explicitly glosses this "guy (coll.)"; example sentence in text: "Саша, он очень хороший парень." |
| до дна | "to the bottom" / "bottoms up" (drink a toast completely) | idiom (adverbial phrase) | colloquial | — | contemporary (source published) | — | — | grammar_reference | n/a | n/a | From the Урок 16 toasting-culture note: at a formal toast, guests may be expected to drink "до дна," especially with vodka; not found elsewhere in this corpus's established/ files via full-text search |

## Grammar points

### Toast-formula construction: за + genitive

Урок 16 (p. 419) presents a closed set of toast formulas built on `за` + genitive case: *за нас/за
тебя* ("to us/to you"), *за здоровье* ("to health"), *за счастье* ("to happiness"), *за успехи* ("to
success"), *за дружбу и мир* ("to friendship and peace"), *за нашу встречу* ("to our meeting"), *за
наше знакомство* ("to our acquaintance"), *за любовь* ("to love"). The accompanying culture note
(p. 465) frames Russian toasting as closer to a short speech than a simple "cheers" — hosts propose
the first toast, guests stand and make eye contact while clinking glasses, and everyone customarily
takes a bite of food after each toast. This specific formula inventory and framing were not found
duplicated verbatim elsewhere in the corpus, though the general toast/speech-etiquette topic is
already well covered by `063_10_urokov_russkogo_rechevogo_etiketa.md` (a dedicated speech-etiquette
phrasebook) — this entry supplements that source's coverage rather than replacing it.

### `coll.` glossary-tag ambiguity (metalinguistic note, not a Russian-grammar point per se)

See "Glossary-notation ambiguity" above — worth flagging for any future extraction sourcing from
this same book's glossaries, since a naive scrape of `coll.`-tagged entries without checking context
would conflate collective/mass nouns with genuinely colloquial-register vocabulary.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `../../00_Reference_Extraction_Spec.md`.
