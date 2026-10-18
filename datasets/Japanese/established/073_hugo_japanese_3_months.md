# Japanese — Established Vocabulary/Grammar: Hugo Japanese in Three Months (full-course extraction)

**Source:** John Breen, Ph.D. (Cantab), *Japanese in Three Months* (Hugo's Simplified System), new and
enlarged edition, Dorling Kindersley, London, 1998 (ISBN 0 85285 314 9). Pages 8–270 (Pronunciation
guide through Appendix 2), 138 PDF pages total. `source_reference/languages/Japanese/03.Audio
Courses, Textbooks/Hugo Japanese in 3 Months/Hugo Japanese in 3 Months.pdf`.

**Coverage note:** This is a full-course extraction (Wave 3, Audio Courses/Textbooks) covering all
20 chapters plus the Pronunciation section and both Appendices. **Confirmed font-cipher-corrupted
text layer** — `pdftotext` produces scrambled Latin symbol soup with no recoverable 1:1 substitution
(tested, not a keyboard/offset cipher — true garbage), so this entire extraction is vision-read from
rendered page images (150dpi, via `pdftoppm`). **Page-spread gotcha confirmed**: each PDF page image
is a scanned two-printed-page spread, not one page per image (PDF page *n* ≥ 4 shows printed pages
`2n−4` (left) and `2n−3` (right); verified empirically against the printed page numbers rather than
assumed). No handwritten marginalia was found anywhere in this copy — all content vision-read is
clearly typeset/printed, consistent throughout.

**Script note:** this book romanizes all Japanese in the main chapters (the author's own stated
design choice, see Introduction, p.5) — no kanji/hiragana/katakana appears in the chapter body text
itself. Hiragana is introduced only in Appendix 1 and a katakana/kanji selection in Appendix 2; those
are captured separately below. The `Term` column therefore gives the **romaji** form for all
chapter-vocabulary rows; a `Script form` is added only for Appendix 1/2 entries where the source
itself supplies kana/kanji.

**Mini-dictionaries (pp. 238–266, English–Japanese and Japanese–English) are a consolidated A–Z
recompilation of vocabulary already introduced chapter-by-chapter** (the author's own stated
intent, p. 6: "All the vocabulary is placed for convenience at the end of the book"). Per the
extraction spec's "comprehensive-but-not-exhaustive" coverage rule and copyright discipline (never
bulk-reproduce a vocabulary list), this extraction captures vocabulary from its primary context (the
chapter/dialogue it's introduced in) rather than re-keying the ~2,000+-entry mini-dictionaries
verbatim; the mini-dictionaries were spot-checked across several letter-ranges and found to be
consistent with (not adding materially beyond) the chapter-sourced vocabulary already captured here,
with any genuinely new item found during spot-checking folded into the relevant table below and
flagged as `Notes: from mini-dictionary spot-check`.

**Vision Reading Confidence:** this entire file is vision-read (no usable text layer). Default is
`plausible_unverified` for romaji vocabulary read directly off a clean, well-lit, legible printed
page (the overwhelming majority of this source); `verified` is used where a word recurs legibly
elsewhere in the same chapter; `low_confidence` is flagged per-row where a specific gutter-shadow,
faded-print, or unusual-kerning issue created genuine doubt.

---

## Pronunciation (p. 8–11)

Japanese is described as syllable-based rather than phoneme-based (see p. 8). The book gives a full
syllabary table (rows 1–15 × columns 1–5: a/i/u/e/o combined with k-, g-, s-, z-, t-, d-, n-, h-,
b-, p-, m-, y-, r-, w-, plus bare n) matching the standard gojūon ordering, with English-approximation
pronunciation notes for each vowel and several consonants (e.g. Japanese **r** falls between English
'r' and 'l', closer to a tapped 'd'; **fu** is a soft bilabial fricative, not an English 'f'; the
single true consonant **n** occurs only syllable-finally, pronounced like English 'ng' in *sing*).
Vowel combinations (**ai**, **ei**, etc.) and long-vowel/double-consonant conventions are introduced
here (p. 9–11) as pronunciation groundwork, not vocabulary — no distinct lexical items to table.

---

## Chapter 1 — Some useful expressions (p. 12–14)

### Grammar points

#### Basic greetings and set phrases introduced as unanalyzed wholes
Chapter 1 is explicitly pre-grammatical: a block of fixed social-formula phrases/dialogue lines is
front-loaded before any sentence structure is taught, on the premise that survival phrases are
needed immediately. Grammatical decomposition of these (e.g. the *-masu* polite verb ending) comes
from Chapter 2 onward.

#### Honorific name-suffixes (p. 14, Notes 1–3)
- **-san**: added to a family name (or, as shown, a first name) to mean Mr/Mrs/Miss/Ms and show mild
  respect; **never used of oneself**. Girls' given names frequently end in **-ko** (noted as an
  aside, not a suffix rule per se).
- **sensei**: used to address/refer to teachers of anything, and professionals such as doctors; can
  attach to a family name or first name (**Tanaka-sensei**, **Jon-sensei**).
- **-kun**: added to boys' first or family names by a superior, as a sign of affection.

#### Dōzo yoroshiku is a fixed untranslatable social formula (p. 14, Note 4)
Glossed as literally untranslatable — used to request another person's favorable consideration,
typically on first meeting (cross-referenced forward to Chapter 2's introduction conversations).

#### Paired set-phrase exchanges with a family-role/register logic (p. 13, Notes 7–11)
Several phrase-pairs are explicitly tied to a social routine rather than freely substitutable:
- **O-hairi kudasai** ("come in") is used for entering a room/Western-style house; entering a
  Japanese-style house instead uses **O-agari kudasai** (noted but not tabled as its own headword —
  given only as a contrastive aside).
- **Itte kimasu** ("I'm off now") is said by a family member leaving for work/shopping; the stock
  reply is **Itte (i)rasshai** ("see you later").
- **Tadaima** ("I'm back") is the same person's return-formula; the stock reply is **O-kaeri nasai**
  ("hello"/"welcome back").
- **O-jama shimasu** literally "I'm going to make a nuisance of myself," said on entering as a guest.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| o-namae wa nan to osshaimasu ka | what is your name? | phrase | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | honorific o- prefix + osshaimasu (honorific "to say") |
| ...to mōshimasu | my name's... (lit. "I am called...") | phrase | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | humble-register self-naming verb |
| konnichi wa | hello / good afternoon | interjection/phrase | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | verified | recurs across chapters |
| o-hayō gozaimasu | good morning | interjection/phrase | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| konban wa | good evening | interjection/phrase | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| o-yasumi nasai | good night | interjection/phrase | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| sayōnara | goodbye | interjection/phrase | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | verified | used both for routine parting and "but I must be off" context |
| shitsurei shimasu | excuse me (but I must be off) | phrase | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| hajimemashite | pleased to meet you (on first meeting) | phrase | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| dōzo yoroshiku | pleased to meet you (too) / please treat me favorably | phrase | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | explicitly flagged by source as untranslatable, see grammar note |
| go-kigen ikaga desu ka | how are you? (formal) | phrase | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| o-kagesama de | very well, thank you | phrase | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | lit. "thanks to you/your shadow," idiomatic |
| genki? / genki yo | how are you? (informal) / fine | phrase | colloquial | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | source notes this is a much more informal version of go-kigen ikaga desu ka |
| o-hisashiburi desu ne | it's been a long time, hasn't it? | phrase | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | alt. gloss given: "I haven't seen you for ages!" |
| dōmo arigatō gozaimasu (gozaimashita) | thank you very much (past/present) | phrase | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| dō itashimashite | it's a pleasure / you're welcome | phrase | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| arigatō gozaimasu (gozaimashita) | thank you | phrase | core/formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kochira koso | no, thank you (lit. "this side too"/"likewise") | phrase | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| dōmo | thanks (casual) | interjection | colloquial | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| īe | not at all / no | interjection | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| gomen nasai | I'm sorry | interjection/phrase | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| ii desu | that's all right | phrase | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| hai, dōzo | here you are! | phrase | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| o-saki e dōzo | after you | phrase | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| sumimasen | thank you / excuse me / sorry (multi-use) | interjection/phrase | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | verified | shown used as a "thank you" response to o-saki e dōzo as well as an apology — genuinely multi-functional, matches source's broader usage across chapters |
| o-hairi kudasai | come in (Western-style room/house) | phrase | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | contrastive note: Japanese-style house instead uses o-agari kudasai |
| o-jama shimasu | thank you (lit. "I'm going to make a nuisance of myself") | phrase | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | said entering as a guest |
| itte kimasu | I'm off now | phrase | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | said by a family member leaving for work/shopping |
| itte (i)rasshai | see you later | phrase | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | stock reply to itte kimasu |
| tadaima | I'm back | phrase | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| o-kaeri nasai | welcome back / hello | phrase | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | stock reply to tadaima |
| gomen kudasai | excuse me, is anyone there? | phrase | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | said e.g. by a customer entering a shop with no visible assistant |
| chotto matte kudasai | just a minute, please | phrase | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kanpai | cheers! | interjection | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | toast |
| -san | Mr/Mrs/Miss/Ms (name suffix) | suffix | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | never used of oneself; see grammar note |
| sensei | teacher/doctor (title) | noun | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | see grammar note |
| -kun | affectionate name suffix (boys, from a superior) | suffix | colloquial | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | see grammar note |

---

## Chapter 2 — Statements; questions: is/isn't...?; answering questions; possession (p. 15–24)

### Grammar points

#### 1. Nouns have no gender/number/article
Japanese nouns mark neither masculine/feminine/neuter nor singular/plural, and have no equivalent of
*a/an/some/the*. **shinkansen** alone covers "a bullet train," "the bullet train," "bullet trains,"
etc.; context disambiguates (p. 16).

#### 2. Personal pronouns are used sparingly
Pronouns (**watashi** "I/me," **anata** "you," **kare** "he/him," **kanojo** "she/her," plural forms
via **-tachi**) exist but are used far less than in English since context usually makes the referent
clear (p. 16).

#### 3. The particle *wa*
**Wa** marks the topic ("as for..."); with rising intonation alone, "**A wa?**" broadly means "what
about A?" (p. 16). It also marks the grammatical subject of the basic **A wa B desu** ("A is B")
sentence pattern (p. 17).

#### 4. Verbs (i): the copula *desu* / negative *de wa arimasen*
"**A** is/isn't **B**" = **A wa B desu** / **A wa B de wa arimasen** (colloquially **ja arimasen**),
literally "as for A, it is/isn't B." The subject + **wa** is routinely dropped once context makes it
clear. Verbs come sentence-finally and are invariant for person/number — one word, **desu**, covers
"(I) am," "(you) are," "(he/she/it) is," "(we) are," etc. (p. 17).

#### 5. Questions with the particle *ka*
Questions are formed by placing **ka** after the verb: **A wa B desu ka** / **A wa B de wa arimasen
ka** ("is/isn't A B?"). Two questions can be juxtaposed as an "or" question (**Koko wa Kōbe desu ka
Ōsaka desu ka** "is this Kobe or Osaka?") (p. 18).

#### 6. Answering questions
**sō desu** = "that's right/so," **chigaimasu** = "that's wrong/I disagree," **chotto wakarimasen** =
"I'm not sure," **sō desu ne** / **etto** = "umm..." (hedging fillers) (p. 18).

#### 7. Sentence-final particles *yo* and *ne*
**Yo** after the main verb adds emphasis ("you know"); **ne** is a tag-question-like softener,
compared explicitly by the source to French *n'est-ce pas?* (p. 19–20). Note: **Hai** used in reply
to a negative-tag question confirms the *statement*, not the English yes/no logic — the source
explicitly flags this as a trap ("the Japanese use 'Yes' to mean 'what you say is correct'") (p. 20).

#### 8. Possessives — the particle *no* (i)
**B no A** broadly marks possession/association: "B's A," "A of B," "A which is B," "A from B," "A
in B" (p. 20). Pronoun + **no** alone means "mine/yours/his/hers/etc." (p. 21). **No** also converts
certain nouns and color-nouns into prenominal adjectives (**hontō no** "real," **cha-iro no**
"brown," **ki-iro no** "yellow," **midori-iro no** "green") — flagged as only used this way when the
adjective precedes a noun (p. 21).

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| watashi | I, me | pronoun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| anata | you (sing.) | pronoun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | source notes Japanese avoids this pronoun where possible |
| kare | he, him | pronoun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kanojo | she, her | pronoun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| watashi-tachi | we, us | pronoun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | -tachi pluralizes pronouns |
| anata-tachi | you (pl.) | pronoun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| ano hito-tachi | they | pronoun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | lit. "those people" |
| kore | this / it | pronoun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | near speaker |
| sore | that / it (near hearer) | pronoun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| are | that / it (near neither) | pronoun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| koko / kochira | here (this place) | pronoun/adverb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | kochira more respectful, used for people (see note on Emura-sensei vs. kore) |
| soko / sochira | there (near hearer) | pronoun/adverb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| asoko / achira | there (near neither) | pronoun/adverb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| shinkansen | bullet train | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | used as the running example for number/article-less nouns |
| biru | beer | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| desu | to be (copula) | verb (copula) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | invariant for person/number |
| de wa arimasen / ja arimasen | to not be (copula, neg.; latter more colloquial) | verb (copula) | core/colloquial | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| Amerikajin | American (person) | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | -jin "person of a country" productive suffix, see note |
| sararīman | businessman (salaryman) | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | loanword from English "salary(man)" |
| gakusei | student | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| Nihonjin | Japanese (person) | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | Nihon "Japan" + -jin |
| Kankokujin | Korean (person) | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| Chūgokujin | Chinese (person) | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| Igirisujin | English/British (person) | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | Igirisu "England" |
| shufu | housewife | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| sō desu | that's right / is that so? | phrase | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | lit. "is that so" per note |
| chigaimasu | that's wrong / I disagree | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| chotto wakarimasen | I'm not sure | phrase | colloquial | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| etto | umm... | interjection | colloquial | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | filler word |
| hoteru | hotel | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | English loanword |
| shuto | capital (city) | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| chizu | map | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kanai | (my) wife | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | humble term for one's own wife |
| kuruma | car | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| bukka | cost of living / prices | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| o-kane | money | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | honorific o- prefix |
| ie | house | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| hontō no | real | adjective | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | no-adjective, see grammar note 8 |
| ima no | present (adj.) | adjective | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| cha-iro no | brown | adjective | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| ki-iro no | yellow | adjective | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| midori-iro no | green | adjective | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kōhī | coffee | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | English loanword |
| kaban | bag | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| Tōkyō Daigaku | Tokyo University | proper noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | dialogue proper noun |
| musuko | (my) son | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| shōgakusei | primary/elementary school pupil | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| Eigo | English (language) | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| Rondon daigaku | University of London | proper noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| Nihon gakubu | Japanese department/faculty | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kaishain | company employee | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| naruhodo | I see | interjection | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| shitsurei desu ga | excuse me for asking, but... | phrase | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| meishi | business/name card | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| de irasshaimasu | to be (honorific of desu, of others only) | verb (copula) | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | never used of oneself, see note |
| o-mizu | (drinking) water | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | listed by source as an o- noun with "no particular respect involved" |
| o-tearai | toilet | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| o-cha | (Japanese) tea | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| mo | too / also / (neg.) neither | particle | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | A mo B mo = "both A and B"; negative = "neither...nor" |

---

## Chapter 3 — Questions: who/where/what...?; location expressions; particles to/from/with (p. 25–36)

### Grammar points

#### 9. Interrogatives: who/where/what/which/when/how
**dare** "who?" (politer: **dochira-sama**), **doko**/**dochira** "where?", **nani** "what?" (often
**nan** before syllables of table rows 6/7/8, i.e. before t-/d-/n- sounds), **dochira** "which (of
two)?", **dore** "which (of three+)?", **itsu** "when?", **dō** "how/what's...like?/how about?"
(politer: **ikaga**) (p. 25).

#### 10. Possessives — the particle *no* (ii)
**No** also combines with the interrogatives **dare, doko, nan, itsu**: **dare no** "whose,"
**doko no hito** "a person of where (= where's he from)," **nan no hon** "a book of what (= what's
the book about)," **itsu no shinbun** "a newspaper of when (= which day's paper)" (p. 27).

#### 11. Demonstrative adjectives: this/that/which + "this sort of"
Distinct from the pronoun series (kore/sore/are): the adjective series is **kono** "this," **sono**
"that (near hearer)," **ano** "that (not near either)," **dono** "which/what." A parallel "sort of"
series exists: **konna** "this sort of," **sonna**/**anna** "that sort of," **donna** "which/what
sort of" (p. 27).

#### 12. Locational nouns + the particle *no*
A set of locational nouns (**mae** "front," **temae** "before/this side of," **ushiro** "back,"
**naka** "inside," **soto** "outside," **ue** "top," **shita** "bottom," **chikaku** "near,"
**tonari** "beside," **mukō** "beyond," **mukai** "opposite") combine with **no** to link to other
nouns (**kissaten no mae** "in front of the coffee shop"), and with a second **no** act as full
adjectives (**mae no hito** "the person in front") (p. 28–29). These slot into the basic **A wa B
desu** pattern like any other predicate.

#### 13. Verbs: plain and polite (masu) forms
Every verb has a plain (dictionary) form and a polite **-masu** form; the two differ in politeness
only (**suru/shimasu** "do"). The course teaches the **-masu** form throughout and recommends
learners stick to it. The sole exception is **desu** ("be," equational), which has no **-masu** form
of its own — it already corresponds in politeness to a masu-form verb; its plain form is **da**
(p. 30).

#### 14. Existential "be": aru/arimasu (inanimate) vs. iru/imasu (animate)
Distinct from the equational **da/desu** ("A is B"), **aru/arimasu** and **iru/imasu** mean "be (in a
place)/there is/are/exist" — **aru/arimasu** for inanimate subjects, **iru/imasu** for animate ones.
Negative of **-masu** is **-masen**. The plain **-masu** form also covers the future tense (no
separate future morphology) (p. 30).

#### 15. Honorific/humble existential-verb pair: irassharu/irasshaimasu vs. oru/orimasu
**Irassharu/irasshaimasu** is an honorific "be" verb exalting its subject — used to address or refer
to someone of superior/equal-but-respected status; never used of oneself, one's family, or
intimates. **Oru/orimasu** is the humble counterpart, lowering the speaker/speaker's in-group out of
deference to the hearer. The source explicitly flags these honorific forms as used with real
flexibility/inconsistency in practice, "a guide only" (p. 31–32) — and notes that among status-equal
speakers (e.g. two students discussing a professor) the plain **iru** is used instead of the
honorific (p. 32).

#### 16. The particle *ni*: location, "in," "to"
**Ni** + **aru/iru** (or variants) expresses static location ("in/at"). **Ni** (or **e**) expresses
direction, "to/towards" (p. 32).

#### 17. "From" (kara) and other particles: made, de; wa/mo on particles
Japanese word order is fairly free; the element marked by **wa** tends to come first. **kara** =
"from" (place or time); "from A to/until B" uses **made** for the "to" endpoint. **De** marks "in/at"
when an action (not mere static existence) occurs there, and also covers instrument/means ("by
bus," "with chopsticks," "in English"). Any particle (**kara, made, de, ni**) can itself be followed
by **wa** (implying contrast) or **mo** ("both...and"/negative "neither...nor") (p. 33–34).

#### Dialogue notes (Conversations 3A–3C, p. 34–35)
- **ga**: a conjunction meaning "but," though frequently (as in these dialogues) carrying no real
  adversative force at all — cross-referenced forward to Chapter 4.
- **nomi ni ikimasu/kimasu**: strip **-masu** from any verb, add **ni**, then **iku/ikimasu** "go" or
  **kuru/kimasu** "come," to form "go/come and do [verb]."
- **-mashō**: change **-masu** to **-mashō** for "let's..."; add **ka** for "shall I/we...?"
  (**Pabu ni ikimashō** "let's go to a pub").
- **kuruma** is used colloquially in the dialogue to mean "taxi," not just "car."

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| dare | who? | pronoun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| dochira-sama | who? (polite) | pronoun | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| doko / dochira | where? | pronoun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| nani / nan | what? | pronoun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | nan allomorph before certain syllables, see grammar note |
| dochira | which one (of two)? | pronoun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| dore | which one (of three+)? | pronoun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| itsu | when? | pronoun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| dō | how? / what's...like? / how about? | adverb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| ikaga | how about? (polite) | adverb | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kashu | singer | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| deguchi | exit | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| gaijin tōrokushō | alien registration card | noun | technical | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | real-world bureaucratic-register term for foreign residents in Japan |
| yakyū | baseball | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| shiai | match/game | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| ashita | tomorrow | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kyō | today | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| tenki | weather | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| māmā | so-so / all right | adverb | colloquial | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| dame | no good | adjectival noun | colloquial | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| Toyota | Toyota (car brand) | proper noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| futsū no | ordinary | adjective | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kono | this (adj.) | adjective | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | demonstrative-adjective series, distinct from kore |
| sono | that (adj., near hearer) | adjective | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| ano | that (adj., not near either) | adjective | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| dono | which/what (adj.) | adjective | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| konna | this sort of | adjective | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| sonna | that sort of (near hearer) | adjective | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| anna | that sort of (not near either) | adjective | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| donna | which/what sort of | adjective | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| mae | front / in front of | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | locational noun series, grammar note 12 |
| temae | before / this side of | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| ushiro | back / behind | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| naka | inside | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| soto | outside | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| ue | top / on top of | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| shita | bottom / under | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| chikaku | near | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| tonari | beside | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| mukō | beyond | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| mukai | opposite | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kissaten | coffee shop | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| depāto | department store | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | English loanword (department) |
| kōban | police (sub)station/box | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | culturally specific institution (neighborhood koban) |
| eki | (train) station | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| isu | chair | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| tēburu | table | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | English loanword |
| doa | door | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | English loanword |
| hikidashi | drawer | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| o-mise | shop | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| sunakku | (small) bar/snack bar | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | English loanword "snack" used for a type of Japanese bar |
| kadoi/kadota | (as shown; on the corner) | adjective/phrase | colloquial | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | low_confidence | dialogue word ("Kadota desu ne") — gloss context-inferred as "on the corner," not independently defined by the source on this page; flagged low confidence |
| aru/arimasu | to be/exist (inanimate) | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | see grammar note 14 |
| iru/imasu | to be/exist (animate) | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| irassharu/irasshaimasu | to be (honorific, of others) | verb | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | see grammar note 15 |
| oru/orimasu | to be (humble, of self/in-group) | verb | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| jisho | dictionary | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| heya | room | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kaisha | company/office | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| arukimasu (aruku) | to walk | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| yasumi | holiday(s) | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| hajimarimasu (hajimaru) | to begin (intr.) | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| asa | morning | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| ban | evening | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| uchi | home/house | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| machimasu (matsu) | to wait | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| basu | bus | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | English loanword |
| ikimasu (iku) | to go | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| hashi | chopsticks | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| tabemasu (taberu) | to eat | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| hanashimasu (hanasu) | to speak | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| o-kyaku-san | guest/customer | noun | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | honorific o- + -san |
| Honkon | Hong Kong | proper noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kimasu (kuru) | to come | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | irregular verb |
| iimasu (iu) | to say | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| pasupōto | passport | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | English loanword |
| tsugi | next | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| Shinjuku / Shibuya | (Tokyo districts/station names) | proper noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | dialogue proper nouns |
| pabu | pub | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | English loanword |
| ukagaimasu (ukagau) | to visit (humble) | verb | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | humble register, see dialogue note |
| nochi hodo | later on | adverb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| soretomo | or | conjunction | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |

---

## Chapter 4 — Verbs and subjects (wa/ga); verbs and objects (wa/o/ni); the past tense (p. 37–48)

### Grammar points

#### 18. wa vs. ga as subject-marking particles
**Ga** marks the grammatical subject and often signals that the referent is *new* to the
conversation — roughly English indefinite "a/some" vs. **wa**'s definite "the." **Ga** (and only
**ga**) follows question words (**dare ga...**, **doko ga...**) and must also be used in a reply to
such a question (**watashi ga...**). **Wa** more broadly marks "what we're discussing," frequently
implies contrast, and is used more often in negative sentences than **ga** (p. 37–39).

#### 19. Verbs and their objects (i): direct object particle *o*
Direct objects take **o**; a question-word object (**nani, dare**) is still marked by **o**, never
**wa** (p. 39). **Mo** ("also"/"both...and"/"even") can replace **o** for emphasis; **wa** commonly
replaces **o** in negative sentences and in contrastive sentences, and in replies to a question
already containing **wa** (p. 39–40). The source notes that in casual speech, **wa, ga,** and **o**
are all very frequently dropped entirely (p. 40).

#### 20. Verbs and their objects (ii): "extended" object uses of *o*
Some verbs take **o** where English would use "over/along/around/at" or nothing (**michi o
watarimashō** "let's cross the road," **michi o ikimasu** "go along the road," **kado o magarimashō**
"let's turn at the corner"). Verbs of requesting/offering/thanking (**kudasai, dōzo, arigatō
gozaimasu**) also require **o** before their object (p. 40).

#### 21. Verbs and their objects (iii): indirect object particle *ni*
Indirect objects take **ni** (**kare ni denwa o kakemasu** "I'll phone him," lit. "to him") (p. 40).

#### 22. "And," "or," "with"
- **to** joins nouns exhaustively ("A and B, that's all"); **ya** joins nouns non-exhaustively ("A
  and B amongst other things"), often paired with **nado** ("etcetera") or in the pattern **...toka
  ...toka...nado**. With a single item, either **toka** or **nado** alone can still appear.
- "Or" = **ka** or **mata wa**.
- "With" = **to**, sometimes **to issho ni** (lit. "together with").
- "And then" (joining clauses/sentences) = **sore kara** (or **soshite**) (p. 41–43).

#### 23. "But," "and" (joining clauses)
"But" = **ga** or **keredomo**; **ga** very often carries no real adversative force (mentioned
already at Ch.3 dialogue note) and frequently ends a sentence to indicate hesitation/trailing off,
implying an unstated continuation (**Arimasu ga...** "we have [some], [would you like it?]") (p. 42).

#### 24. The past tense (i)
Past of **desu** is **deshita**. Past of a **-masu** verb is **-mashita**. Past negative of **desu**
is **de wa (ja) arimasen deshita**; past negative of other verbs is **-masen deshita**. The source
flags explicitly that **-masen deshita** is NOT used for the perfect ("have not done") — a distinct
construction follows in Chapter 8. The plain **-mashita** form, conversely, does double duty for
simple past *and* perfect ("have done") (p. 43–44).

#### 25. "Now," "already," "not yet" — ima, mō, mada
**Ima** = "now" (with a **-masu**/**-mashō** verb) or "just now" (with a past-tense verb). **Mō**
means both "already" and (idiomatically) "now" in questions like "are you going to bed already?."
**Mada** + negative = "not yet"; **Mada desu** alone is the all-purpose "not yet" response. **Sugu
(ni)** "immediately/straight away" combines with **ima** for "at this very moment" and with **mō**
for "soon/in a minute" (p. 44–45).

#### Dialogue notes (Conversations 4A–4B, p. 46–48)
- **Irasshaimase**: stock greeting from shop/café/restaurant staff on entry; no reply is needed.
- **itashimashō** (humble form of suru/shimasu): "shall I do...?" in service register.
- **mōningu**: abbreviation of **mōningu sābisu**, a cheap light breakfast set sold at Japanese coffee
  shops.
- **de gozaimasu** (politer/humbler than da/desu) and **gozaimasu** (politer/humbler than
  aru/arimasu) extend the politeness-register system already seen with irassharu/oru.
- **sore ja**: abbreviation of **sore de wa**, "well, then."
- **...ga yoroshii desu ka**: polite form of **...ga ii desu ka**, lit. "is it good?"
- **kashikomarimashita**: polite "I have understood" (service register).
- **shōshō o-machi kudasai**: politer form of chotto matte kudasai.
- **o-matase shimashita**: "sorry to have kept you waiting," set service-register apology.
- **oroshite kudasai**: "please let me off here" (said to a taxi driver).
- **kekkō desu**: "that's unnecessary/no thank you" — used here to decline change; the source notes
  tipping is not customary in Japan except a few coins to a taxi driver.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| terebi | television | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | English loanword |
| mimasu (miru) | to see/watch | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| o-sake | alcohol/sake | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| nomimasu (nomu) | to drink | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| asa-gohan | breakfast | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| tōsuto | toast | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | English loanword |
| yobimasu (yobu) | to invite/call | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| sashimi | sashimi (raw fish) | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | culturally specific dish term |
| nattō | fermented soybeans | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | culturally specific dish term |
| gohan | cooked rice / meal | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| Mainichi | (name of a newspaper) | proper noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | real Japanese newspaper used as example |
| kaimasu (kau) | to buy | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| nyūsu | (the) news | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | English loanword |
| shinbun | newspaper | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| pan | bread | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | loanword, ultimately from Portuguese pão |
| Ryōanji | Ryōanji (temple name) | proper noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | real Kyoto temple used as example |
| shingō | traffic lights | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| michi | road | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| watarimasu (wataru) | to cross | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| massugu | straight (ahead) | adverb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kado | corner | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| hidari | left | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| magarimasu (magaru) | to turn | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| hana | flower(s) | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| denwa | telephone | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kakemasu (kakeru) | to make (a call) | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| tegami | letter | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kakimasu (kaku) | to write | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| pātei | party | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | English loanword |
| hirakimasu (hiraku) | to open/hold (an event) | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| hanbāgā | hamburger | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | English loanword |
| furaido poteto | French fries | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | English loanword ("fried potato") |
| wain | wine | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | English loanword |
| kōra | cola | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | English loanword |
| yuka | floor | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| zasshi | magazine | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| chōshoku | breakfast (formal term) | noun | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | more formal register than asa-gohan |
| issho ni | together | adverb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| keredomo | but | conjunction | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| saifu | wallet | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| yūbe | last night | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kinō | yesterday | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| yomimasu (yomu) | to read | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| sushi | sushi | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| owarimasu (owaru) | to finish | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| dekakemasu (dekakeru) | to go out | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| nemasu (neru) | to go to bed/sleep | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| sugu (ni) | immediately / straight away | adverb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| dekimasu (dekiru) | to be able to / can do | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| mōningu | breakfast set (café) | noun | colloquial | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | abbreviation of mōningu sābisu, see dialogue note |
| tamago | egg | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kōcha | black tea | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| yappari | after all / as expected | adverb | colloquial | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| miruku-tei | milk tea | noun | colloquial | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | English loanword blend "milk" + tē "tea" |
| Asahi | (name of a newspaper) | proper noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | real Japanese newspaper |
| Eiji-shinbun | English-language newspaper | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| o-kanjō | the bill (restaurant) | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| takushī noriba | taxi rank | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| basu tei | bus stop | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| hen | area/vicinity | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| untenshu-san | driver | noun | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | -san suffix even for an occupational address term |
| tsukimasu (tsuku) | to arrive | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| o-tsuri | change (money) | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kekkō desu | that's fine / no thank you | phrase | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | see dialogue note on tipping custom |

---

## Chapter 5 — Numbers; time; dates; numeral expressions (p. 49–62)

### Grammar points

#### 26. Two parallel number systems: Chinese-origin vs. Japanese-origin
Japanese has two full counting systems in daily use side by side — a **Chinese-origin** series (used
alone for counting upward with no concrete referent, in mathematics, and for telephone numbers; also
combined with "counters" for specific object classes) and a separate **Japanese-origin** series (used
up to 10/12 only, almost always suffixed with **-tsu**, for objects with no dedicated counter of
their own). This dual system is a genuinely distinct typological feature worth flagging for the
morphological-typology profile (p. 49, p. 55).
- Chinese numbers 11–19 are formed transparently as "ten-one," "ten-two," etc.; 20 = "two-ten," and
  so on.
- Irregularities: 4 = **shi** or **yon** (yon far more common in practice), 7 = **shichi** or
  **nana**, 9 = **ku** or **kyū**; 40 = **yonjū** (not *shijū*), 70 = **nanajū** (not *shichijū*), 90
  = **kyūjū** (not *kujū*).
- Hundreds show predictable sound changes at 3/6/8-hundred (**sanbyaku, roppyaku, happyaku**) and
  thousands at 3/8-thousand (**sansen, hassen**); 10,000 = **ichiman**, 100,000 = **jūman**,
  1,000,000 = **hyakuman**.

#### 27. Telling the time
"O'clock" = time counter **-ji** (irregular: 4 o'clock = **yoji**, not *yonji*). "Half past" = **han**
after the hour. "Minute" = **-fun**, with its own sound changes (**ippun, nifun, sanpun, yonpun,
gofun, roppun, nanafun, hachifun/happun, kyūfun, juppun**). Minutes past the hour follow the hour
(**ichiji sanpun** "3 min. past 1"); minutes before the hour add **mae** after the minute count
(**yoji gofun mae** "5 min. to 4"). **Ni** marks "at" a given time. "What time" = **nanji**.

#### 28. Counters for specific object classes (money, people, cylindrical objects, cupfuls, flat
objects, books, times/floors)
A representative, non-exhaustive sample of Japanese's productive counter-word system, each with its
own sound-change pattern and its own "how many" interrogative form:
- Money: counter is implicit in the yen-numeral itself (**-en**); "how much" = **ikura**.
- People: **hitori** "one person," **futari** "two people," then **-nin** from three up (**yonin**
  "four people," irregular — not *sannnin*-pattern); "how many people" = **nannin**.
- Cylindrical objects (bottles, pencils, legs): counter **-hon** (**ippon, nihon, sanbon, yonhon,
  gohon, roppon, nanahon, hachihon/happon, kyūhon, juppon**); "how many" = **nanbon**.
- Cupfuls/spoonfuls: counter **-hai**, same sound changes as **-hon**; "how many" = **nanbai**.
- Flat things (paper, stamps, slices): counter **-mai**; "how many" = **nanmai**.
- Books/magazines: counter **-satsu**, with its own sound changes at 1/11 (**issatsu, jūissatsu**)
  and 10/20 (**jussatsu, nijussatsu**); "how many" = **nansatsu**.
- Times/floors of a building: counter **-kai**, sound changes at 1/6/10 (**ikkai, rokkai, jukkai**);
  "how many times/floors" = **nankai**.
- The source explicitly notes Japanese speakers may use the generic Japanese-numeral system even for
  objects that do have their own counter.

#### 29. The Japanese-origin number series and its uses
**hitotsu, futatsu, mittsu, yottsu, itsutsu, muttsu, nanatsu, yattsu, kokonotsu, tō** (1–10), then
**jūichi, jūni** (11–12, Chinese-pattern beyond 10). Used for counting generic objects without a
counter of their own, and for age (alternative to the **-sai** counter below) up to **hatachi** "20
years old." "How many" = **ikutsu**; "how old" = **(o-)ikutsu**.

#### Age counter *-sai*
Chinese-system age counter with sound changes at 1/8/10 (**issai, hassai, jussai**); "how old" =
**nansai**.

#### 30. Ordinal numbers
Formed by adding **-me** to any counter (**futatsu-me** "the second one," **mittsu-me** "the
third").

#### 31–32. Dates (i)/(ii): days of the month, weekdays, months, years
Days 1st–10th use dedicated Japanese-origin forms (**tsuitachi, futsuka, mikka, yokka, itsuka,
muika, nanoka, yōka, kokonoka, tōka**); 11th–31st switch to the Chinese system + counter **-nichi**,
with irregularities at 14th/24th (**jūyokka, nijūyokka**), 17th/27th (**jūshichinichi,
nijūshichinichi** — not the *-nana* allomorph here), and 20th (**hatsuka**, an opaque/irregular
form). "What day/date" = **nannichi**. Days of the week are built transparently on a 7-element set
(**getsuyōbi** Mon ... **nichiyōbi** Sun); "what day of the week" = **nanyōbi**. Months use the
counter **-gatsu** on the Chinese numeral (**ichigatsu** Jan ... **jūnigatsu** Dec; irregular reading
for April **shigatsu**, not *yongatsu*); "what month" = **nangatsu**. Years use counter **-nen**
("what year" = **nannen**).

#### 33. "Only" — shika vs. dake
**Shika** (always with a negative verb) and **dake** (neutral) both mean "only"; **shika** is more
common and triggers omission of **wa/ga/o**. The two together (**shika...dake**) are emphatic.

#### 34. Miscellaneous numeral expressions: "about," "a little"/"a lot," "some more"
**Goro** = "about" (time only); **gurai** = "about" (more general, incl. cost). **Sukoshi** and
**chotto** = "a little"; **takusan** = "a lot"; **amari (takusan)** + negative = "not much." **Mō** +
quantity = "some/a little more."

#### Dialogue notes (Conversations 5A–5C, p. 60–62)
- **nannen umare**: set phrase, "what year were you born in?"
- **kōkūbin** "by air(mail)"; **funabin** "by sea(mail)"; **earogramu** "aerogram" (English
  loanword).
- **-yuki** suffix on a place name = "(train/bus) bound for..." (**Kyōto-yuki**).
- **nanji nanpun-hatsu**: "at how many minutes past what hour does it leave?"
- **ato** + counter often means "...[of X] left" (**ato jūgofun arimasu** "there are 15 min. left").
- Ticket-counter convention: the word for "ticket" itself is often omitted once a counter makes the
  referent clear (**otona nimai** "two adult [tickets]").
- **bansen** is the platform counter; **nanbansen** "which platform."
- **haiken itasu/itashimasu** (humble, "to look at/see," here of tickets) — cross-referenced forward
  to Chapter 20's politeness-language summary.
- **Shimatta!**: an exclamation of dismay ("damn it!"/"oh no!") shown in the dialogue after boarding
  the wrong train — distinctly more colloquial/emotive register than the rest of the course's
  phrasebook-style content.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| ichi, ni, san, shi/yon, go, roku, shichi/nana, hachi, kyū/ku, jū | 1–10 (Chinese-origin) | numeral | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | base of the Chinese-origin system, see grammar note 26 |
| hitotsu, futatsu, mittsu, yottsu, itsutsu, muttsu, nanatsu, yattsu, kokonotsu, tō | 1–10 (Japanese-origin) | numeral | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | see grammar note 29; distinct typological system from Chinese-origin numerals |
| hyaku / sen / ichiman / hyakuman | 100 / 1,000 / 10,000 / 1,000,000 | numeral | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | base units, see grammar note 26 |
| -ji | o'clock (time counter) | suffix | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| han | half (past) | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| -fun/-pun | minute (counter) | suffix | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| nanji | what time? | pronoun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| -en | yen (money counter) | suffix | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| ikura | how much? | pronoun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| hitori / futari / -nin | one/two/three+ people (counter) | counter | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| nannin | how many people? | pronoun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| -hon/-bon/-pon | counter: cylindrical objects | suffix | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| enpitsu | pencil | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| -hai/-bai/-pai | counter: cupfuls/spoonfuls | suffix | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| satō | sugar | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| iremasu (ireru) | to put in | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| -mai | counter: flat objects | suffix | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kami | paper | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| -satsu | counter: books/magazines | suffix | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| karimasu (kariru) | to borrow | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| -kai | counter: times/floors | suffix | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| o-mocha uriba | toy department | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| -sai | counter: age | suffix | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| hatachi | 20 years old | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | irregular age-reading, not derivable from itsutsu-pattern |
| (o-)ikutsu | how old? / how many? | pronoun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| -me | ordinal suffix | suffix | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | see grammar note 30 |
| sūtsukēsu | suitcase | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | English loanword |
| bāgen sēru | (bargain) sale | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | English loanword |
| tsuitachi...tōka | 1st–10th of the month | numeral | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | dedicated non-derivable forms, see grammar note 31 |
| hatsuka | 20th of the month | numeral | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | irregular/opaque form |
| -nichi | counter: day of the month (11th+) | suffix | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| nannichi | what day/date? | pronoun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| getsuyōbi...nichiyōbi | Monday...Sunday | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| nanyōbi | what day of the week? | pronoun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| -gatsu | counter: month of the year | suffix | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | shigatsu "April" is an irregular reading |
| nangatsu | what month? | pronoun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| -nen | counter: year | suffix | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| nannen | what year? | pronoun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| umaremasu (umareru) | to be born | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kotoshi | this year | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| shika | only (+ negative) | particle | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | see grammar note 33 |
| dake | only | particle | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| Nara | Nara (city) | proper noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| ichinen | one year | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| goro | about (time) | particle | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | see grammar note 34 |
| gurai | about (general) | particle | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| sukoshi | a little | adverb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| chotto | a little | adverb | colloquial | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| takusan | a lot | adverb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| amari | not much (+ negative) | adverb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| itadakimasu | to receive/eat (humble) | verb | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | humble register verb |
| mikan | orange (mandarin) | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| tanjōbi | birthday | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| raishū | next week | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| onaji | same | adjectival noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kitte | (postage) stamp | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| hagaki | postcard | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| Furansu | France | proper noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kōkūbin | airmail | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| funabin | surface/sea mail | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| earogramu | aerogram | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | English loanword |
| zenbu | all / altogether | noun/adverb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| azukarimasu (azukaru) | to receive/take charge of (humble) | verb | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | service-register humble verb, used of receiving payment |
| -yuki | bound for... (suffix on place name) | suffix | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| hatsu | departure (suffix) | suffix | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| ato | remaining / after | noun/adverb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| otona | adult | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| katamichi | one way (ticket) | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| ōfuku | round trip (ticket) | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| o-kaeshi | the change (money) | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | synonym-register pair with o-tsuri (Ch.4) |
| bansen | platform (counter) | suffix | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| jōshaken | (train) ticket | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | formal term, vs. kippu |
| haiken itasu/itashimasu | to look at / see (humble) | verb | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | cross-referenced forward to Ch. 20 |
| densha | (electric) train | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| machigaemasu (machigaeru) | to mistake / get wrong | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| shimatta! | damn it! / oh no! | interjection | colloquial | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | notably more colloquial/emotive register than surrounding phrasebook content |
| kippu | ticket | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kakarimasu (kakaru) | to cost / take (time) | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| tomodachi | friend | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |

---

## Chapter 6 — Adjectives; adverbs (p. 63–73)

### Grammar points

#### 35–37. Adjectives A: the i-adjective class is grammatically verbal
Japanese's first adjective class (all end in **-i**) are, the source stresses, **strictly verbs**:
**hayai** means not "fast" but "is fast," with no person/number inflection of its own ("I am/you
are/.../we are fast" all = **hayai**). Before a noun, **desu** is never added even in polite speech
(**omoshiroi tokoro** "an interesting place" = lit. "a place which is interesting" — no relative
pronoun exists in Japanese; the adjective-as-verb does that work directly).

**Conjugation paradigm** (p. 64–66): present negative = replace final **-i** with **-ku** + **nai**
(**hayai → hayaku nai**); past positive = replace final **-i** with **-katta** (**hayai → hayakatta**);
past negative = change **nai → nakatta** on the present-negative stem (**hayaku nakatta**). **Desu**
added to any of these forms is purely a politeness marker with no semantic content of its own; **nai**
is itself the plain form of **arimasen**, so **hayaku arimasen/arimasen deshita** are interchangeable
with **hayaku nai desu/nakatta desu** — and **de wa (ja) nai desu / de wa (ja) nakatta desu** are the
more common spoken alternants of **de wa (ja) arimasen / arimasen deshita**. One suppletive
irregularity: **ii** "good" uses its old form **yoi** for all derived forms (**yokatta, yoku
nakatta**), never *iikatta. **totemo** = "very" in positive sentences; **amari** = "very" in negative
sentences (i.e., "not very").

#### 38–40. Adjectives B: the na-adjective class is grammatically closer to English adjectives
The second adjective class requires a supplied copula (**da/desu**) and is called "na adjectives"
because, uniquely, **before a noun in the present positive only**, they take the linking particle
**na** (**hen na hito** "a strange person"). In every other position/tense they take the ordinary
plain/polite forms of **da/desu** (present neg. **de wa (ja) nai**, past **datta**, past neg. **de wa
(ja) nakatta**, politeness added via **desu/deshita** as with any other **da/desu** phrase). Three
**i**-adjectives are irregular in belonging to *both* classes with slightly different stems: **ōkii**/
**ōki na** "big," **chīsai**/**chīsa na** "small," **okashii**/**okashi na** "funny/strange" (in
sentence-final position, however, all three only ever surface as plain i-adjectives). **(to) onaji**
"same (as)" is irregular: it never takes **na** before a noun, but otherwise behaves exactly like a
na-adjective.

#### 41. Intensifier suffix "too..." — sugiru/sugimasu
Strip the final **-i** from an i-adjective (or attach directly to a na-adjective, no **na**) and add
**sugiru/sugimasu**: **kitsusugimasu** "it's too tight." **Amari (ni mo)** can precede for added
emphasis. The source notes the same **sugiru/sugimasu** suffix also attaches productively to verbs
(**tabesugimashita** "I've eaten too much," often paired with **takusan** "a lot").

#### 42–43. Adverb formation from each adjective class; "become"
From i-adjectives: replace final **-i** with **-ku** (**hayai → hayaku** "quickly/early"; irregular
**ii → yoku** "well," which also idiomatically means "often"). From na-adjectives: add **ni**
(**kirei → kirei ni** "prettily/cleanly"). **naru/narimasu** "become" + an adverb gives "get/become
[adjective]" (**samuku narimasu** "it's going to get cold(er)"; also usable with **suru/shimasu** for
a transitive "make [X adjective]": **kirei ni shimashō** "let's tidy up," lit. "let's make [it]
clean"). A second small adverb set pairs with **to** (**chan to** "properly," **hakkiri** "clearly,"
**yukkuri** "leisurely/slowly"). A closed paradigm of manner-demonstrative adverbs also exists: **dō
(yatte)** "how?," **kō (yatte)** "in this way," **sō (yatte)** "in that way (near hearer)," **ā
(yatte)** "in that way (not near either)" — paralleling the kore/sore/are and kono/sono/ano series
already seen.

#### Dialogue notes (Conversations 6A–6B, p. 72–73)
- **o-jōzu**: "you're good at..." — honorific **o-** added out of respect for the addressee (never
  used of oneself); **jōzu** itself formally introduced in Chapter 12.
- **-nikui** / **-yasui** suffixes on a verb's **-masu** stem (replacing **-masu**) productively form
  "difficult to..." / "easy to..." (**wakarinikui** "difficult to understand," **wakariyasui** "easy
  to understand") — a genuinely productive derivational pattern worth flagging for the
  morphological-typology profile.
- **-ppoi** suffix attaches to several adjectives with a meaning that varies by base adjective (e.g.
  **ki-iroppoi** "yellowish," **yasuppoi** "cheap(o)" — a pejorative/diminutive-flavored
  derivational suffix).
- **ironna**: a very common contraction of **iroiro na** "various."
- **-sō (desu)** "looks like..." (e.g. **oishisō desu** "it looks tasty") — cross-referenced forward
  to Chapter 13.
- **hajimete**: "the first time," a frequently useful standalone word.
- Food-register vocabulary cluster (bento box contents) appears here with notably more specific,
  real-world cultural vocabulary than earlier chapters' generic phrasebook content (see table below).

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| takai | high / expensive | adjective (i) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| hikui | low | adjective (i) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| yasui | cheap | adjective (i) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| ōkii | big | adjective (i/na) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | dual-class irregular, see grammar note 38-40 |
| chīsai | small | adjective (i/na) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | dual-class irregular |
| nagai | long | adjective (i) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| mijikai | short | adjective (i) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| hayai | fast / early | adjective (i) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | running example throughout grammar notes 35-37 |
| osoi | slow / late | adjective (i) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| omoshiroi | interesting / funny | adjective (i) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| tsumaranai | boring / tiresome | adjective (i) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| yasashii | easy / kind | adjective (i) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | two distinct senses noted by source |
| muzukashii | difficult | adjective (i) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kitsui | tight | adjective (i) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| yurui | loose | adjective (i) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| katai | hard | adjective (i) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| yawarakai | soft | adjective (i) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| amai | sweet | adjective (i) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| karai | spicy / hot (taste) | adjective (i) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| samui | cold (weather) | adjective (i) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| atsui | hot | adjective (i) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| warui | bad | adjective (i) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| ii / yoi | good / nice | adjective (i) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | suppletive paradigm, see grammar note |
| totemo | very (+ positive) | adverb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| oishii | tasty | adjective (i) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| wakai | young | adjective (i) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kashikoi | clever | adjective (i) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| sakana | fish | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kantan | simple | adjectival noun (na) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kirai | disliked | adjectival noun (na) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| yūmei | famous | adjectival noun (na) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| suki | liked | adjectival noun (na) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| hitsuyō | necessary | adjectival noun (na) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| teinei | polite | adjectival noun (na) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kirei | pretty / clean | adjectival noun (na) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| shitsurei | rude | adjectival noun (na) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | also used as a standalone apology phrase, cf. Ch.1 shitsurei shimasu |
| byōki | ill / sick | adjectival noun (na) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| hen | strange | adjectival noun (na) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| baka | stupid | adjectival noun (na) | colloquial | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| iya | unpleasant | adjectival noun (na) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| dame | useless / no good | adjectival noun (na) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | recurs from Ch.3 |
| iroiro (na) | various | adjectival noun (na) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | contracted colloquially to ironna, see dialogue note |
| okashii | funny / strange | adjective (i/na) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | dual-class irregular |
| onaji | same (as) | adjectival noun (irregular) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | never takes na before noun, see grammar note |
| kamera | camera | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | English loanword |
| sugiru/sugimasu | too (much)... (suffix) | verb (suffix) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | productively attaches to adjectives and verbs, see grammar note 41 |
| naru/narimasu | to become | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| oshiemasu (oshieru) | to teach | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| oto | sound | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| chan to | properly | adverb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| batan to | with a bang | adverb/onomatopoeia | colloquial | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | onomatopoeic adverb |
| mado | window | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| shimemasu (shimeru) | to shut/close | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| hakkiri | clearly | adverb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| setsumei shimasu (suru) | to explain | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| yukkuri | leisurely / slowly | adverb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| dō/kō/sō/ā (yatte) | how? / this way / that way / that way (not near either) | adverb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | manner-demonstrative paradigm, see grammar note |
| gakkō | school | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | from Exercise 10, item 1 |
| ōkisa | size | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | nominalized form of ōkii, from Exercise 10 |
| sukī | skiing | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | English loanword, from Exercise 10 |
| o-jōzu | good at... | adjectival noun (na) | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | honorific o-, never used of oneself; see dialogue note |
| hatsuon | pronunciation | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kawarimasen (kawaru) | to differ/change | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kurō shimasu (suru) | to have a hard time / take trouble | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| wari to | relatively | adverb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| bunpō | grammar | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| yayakoshii | complicated | adjective (i) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| yomikaki | reading and writing | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | compound of yomu + kaku |
| katakana / hiragana / kanji | (the three Japanese writing systems) | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | named explicitly in-dialogue as a source of learner difficulty |
| hijō ni | extremely | adverb | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| oboenikui | difficult to remember | adjective (i, derived) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | -nikui productive suffix, see dialogue note |
| wakariyasui | easy to understand | adjective (i, derived) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | -yasui productive suffix |
| Ōsaka-ben | Osaka dialect | noun | regional | — | contemporary (source published 1998) | Osaka | regional | grammar_reference | n/a | plausible_unverified | explicit regional/dialectal reference |
| kioku | memory | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| mondai | problem | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| erai | great / good for you | adjective (i) | colloquial | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | two senses given by source, see dialogue note |
| maku-no-uchi | (type of boxed lunch / bento) | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | culturally specific food-register term |
| sabazushi | mackerel sushi | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| unagibentō | eel boxed lunch | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| o-nomimono | a drink | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| tsumetai | cold (to the touch) | adjective (i) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | distinct from samui "cold (weather)" |
| hajimete | the first time | noun/adverb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | flagged by source as a very useful standalone word |
| oishisō | looks tasty | adjective (derived, -sō) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | -sō "looks like" suffix, cross-referenced to Ch.13 |
| mazu | first (of all) | adverb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| ki-iroppoi | yellowish | adjective (derived, -ppoi) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | -ppoi productive suffix, see dialogue note |
| takuwan | pickled daikon radish | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | culturally specific food term |
| tsukemono | Japanese pickles | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| akai | red | adjective (i) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| ebi | shrimp/prawn | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| iro | color | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| tsukemasu (tsukeru) | to attach/apply | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| hosonagai | long and thin | adjective (i, compound) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | compound of hoso(i) "thin" + nagai "long" |
| ebi furai | fried shrimp | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | English loanword "fry" |
| sōsu | sauce | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | English loanword |
| kuroppoi | blackish | adjective (derived, -ppoi) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| konbu | kelp | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| aji | taste/flavor | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| onaka | stomach | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| ippai | full | adjectival noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| umeboshi | pickled (salted) plum | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | culturally specific food term |
| shōkafuryō | indigestion | noun | technical | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | medical-register term |
| saikō | best / highest | adjectival noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| suppai | sour | adjective (i) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |

---

## Chapter 7 — The te form of verbs and adjectives: formation and applications (p. 74–84)

### Grammar points

#### 44–45. The te form: three verb classes and their formation
The **te form** (a non-finite verb form with many applications) requires first classifying every
verb into one of three types:
- **Group 1** ("ichidan"-type, though the source doesn't use that term): plain form ends in **-ru**,
  masu-form made by dropping **-ru** and adding **-masu** (**taberu → tabe → tabemasu**). Te form:
  replace **-ru** with **-te** (**taberu → tabete**).
- **Group 2** ("godan"-type): plain form ends in **-u, -ku, -gu, -su, -tsu, -nu, -bu, -mu** (plus a
  subset of **-ru** verbs whose masu-form is **-rimasu**, distinguishing them from Group 1). Te-form
  sound changes depend on the final syllable: **-u/-tsu/-ru → -tte** (kau→katte, matsu→matte,
  kiru→kitte); **-ku → -ite** (kaku→kaite); **-gu → -ide** (oyogu→oyoide); **-su → -shite**
  (dasu→dashite); **-nu/-bu/-mu → -nde** (shinu→shinde, yobu→yonde, yamu→yande).
- **Irregular te forms**: **da(desu)→de**, **iku(ikimasu)→itte** (note: iku is otherwise Group-2-
  regular, irregular only in its te and ta forms — ta form at Ch.9), **kuru(kimasu)→kite**,
  **suru(shimasu)→shite**.
- **Negative te forms**: two exist, both built on the negative plain (**-nai**) form. First: replace
  final **-i** of **-nai** with **-kute** (**tabenai → tabenakute**). Second (available for every verb
  except **nai** and **de wa (ja) nai** themselves): add **-de** to the **-nai** form
  (**kawanai → kawanaide**).

#### 46. Te-form use (i): requests — "please..." / "would you be kind enough to...?"
Te form + **kudasai** = "please..."; te form + **itadakemasen ka** (lit. "can't I get you to...?") =
a politer "would you be kind enough to...?" In the negative, only the **-naide** form (not **-nakute**)
is used for negative requests (**hanasanaide kudasai** "please don't talk").

#### 46 (ii–iii)/49. Te-form use: clause-joining "and (then)" / "and so" / "after doing..."
The te form joins two clauses where English uses "and (then)" — tense is supplied only by the final
verb, regardless of the tense implied by the earlier clause(s) in English. It can also carry the
sense "and so" (cause-result). "After doing X" = **te kara** added to the te form. The negative te
form (**-nakute**) parallels the positive for "not...and so/instead"; **-naide** instead means
"not...instead"/"without...ing" — but requires the main clause and the **-naide** clause to share the
same subject. Adjectival te forms (i-adjective: **takai→takakute**/negative **takaku nakute**;
na-adjective: **kantan→kantan de**/negative **kantan de wa (ja) nakute**) work the same way for
joining descriptive clauses ("and"/"and so").

#### 46 (iv)/47–48. Te-form use: adverbial clauses; -te kuru/iku idioms
The te form used adverbially expresses manner ("by/while ...ing": **aruite ikimashita** "we went on
foot," lit. "walking, we went"). **-te kuru/kimasu** and **-te iku/ikimasu** form a large family of
idiomatic expressions built on "come" and "go": roughly, an action performed before returning
(**-te kuru**: "go and do X, [then come back]") vs. before departing (**-te iku**: "do X and then
go"). Within this family, **motte kuru/iku** ("bring/take," of inanimate objects) is lexically
distinct from **tsurete kuru/iku** ("bring/take," of people/animate beings) — a systematic
animacy-based lexical split worth flagging for the morphological-typology profile.

#### Dialogue notes (Conversations 7A–7B, p. 82–84)
- **-kata** suffix on a verb's -masu stem = "the way to/of ...ing" (**tsukaikata** "way of using,"
  **hanashikata** "way of speaking," **hashirikata** "way of running") — another productive
  derivational suffix.
- **warui desu ga**: "I'm sorry, but..." softening formula.
- **hanashichū**: "engaged" (telephone); the suffix **-chū/-jū** productively attaches to many nouns
  for "during/throughout X": **kaigichū** "at a conference," **shigotochū** "in the middle of work,"
  **ichinichijū** "all day long," **hitobanjū** "all night long," **ichinenjū** "all year long,"
  **karadajū** "all over the body," **iejū** "the whole house."
- **-te miru/mimasu**: "try doing X"/"do X and see" — another productive te-form-based
  construction, distinct from the requests/clause-joining uses above.
- **moshimoshi**: "hello," used specifically for answering/starting a phone call.
- **machiawase suru/shimasu** "arrange to meet" exemplifies a large, productive class of verbs formed
  by noun + **suru/shimasu** (e.g. **benkyō suru/shimasu** "to study," from the noun **benkyō**
  "study") — a derivational pattern the source flags as large and productive.
- **tanoshimi ni shite imasu**: "I'm looking forward to it," a fixed idiom built on the te-form +
  iru/imasu construction formally introduced in Chapter 8.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| taberu/tabemasu | to eat | verb (Group 1) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | te form: tabete |
| miru/mimasu | to see/watch/look at | verb (Group 1) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | te form: mite |
| deru/demasu | to go out | verb (Group 1) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | te form: dete |
| neru/nemasu | to sleep | verb (Group 1) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | te form: nete |
| kaeru/kaerimasu | to go home | verb (Group 2) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | te form: kaette; homophonous with kaeru/kaemasu (change, below) but different conjugation group |
| kaeru/kaemasu | to change (vt.) | verb (Group 1) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | te form: kaete |
| arau/araimasu | to wash | verb (Group 2) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | te form: aratte |
| isogu/isogimasu | to hurry (vi.) | verb (Group 2) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | te form: isoide |
| tatsu/tachimasu | to stand (vi.) | verb (Group 2) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | te form: tatte |
| tateru/tatemasu | to stand up (vt.) | verb (Group 1) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | te form: tatete |
| kau/kaimasu | to buy | verb (Group 2) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | te form: katte |
| kaku/kakimasu | to write | verb (Group 2) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | te form: kaite |
| oyogu/oyogimasu | to swim (vi.) | verb (Group 2) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | te form: oyoide |
| dasu/dashimasu | to take out (vt.) | verb (Group 2) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | te form: dashite |
| matsu/machimasu | to wait for (vt.) | verb (Group 2) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | te form: matte |
| shinu/shinimasu | to die (vi.) | verb (Group 2) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | te form: shinde |
| yobu/yobimasu | to call/invite (vt.) | verb (Group 2) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | te form: yonde |
| yamu/yamimasu | to stop (vi.) | verb (Group 2) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | te form: yande |
| kiru/kirimasu | to cut (vt.) | verb (Group 2) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | te form: kitte |
| iku/ikimasu | to go | verb (irregular te/ta) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | te form: itte (irregular, otherwise Group 2); ta form at Ch.9 |
| kuru/kimasu | to come | verb (irregular) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | te form: kite |
| suru/shimasu | to do/make | verb (irregular) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | te form: shite |
| hashiru/hashirimasu | to run | verb (Group 2) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| rajio | radio | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | English loanword |
| mainichi | every day | adverb/noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| tsukiatari | the end (of a street) | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| migi | right (direction) | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kaze o hiku/hikimasu | to catch a cold | verb (idiom) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | idiomatic collocation, lit. "to pull wind" |
| akiramemasu (akirameru) | to give up | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| tsuku/tsukimasu | to arrive (on foot) | verb (Group 2) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | distinct homophone from tsuku "arrive" (Ch.4, vehicle) |
| kasa | umbrella | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| motte kuru/iku | to bring/take (inanimate) | verb (idiom) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | animacy-split lexical pair, see grammar note |
| tsurete kuru/iku | to bring/take (person/animate) | verb (idiom) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| chichi | (my) father | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | humble term for one's own father |
| jikan | time | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| samishii | lonely | adjective (i) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| o-furo | bath | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| hairu/hairimasu | to enter / get in | verb (Group 2) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| harau/haraimasu | to pay | verb (Group 2) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| hiroi | spacious / wide | adjective (i) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| hanashi | story / talk | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| tsukaikata | the way to use (something) | noun (derived) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | -kata productive suffix, see dialogue note |
| jūen dama | 10-yen coin | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| komakai | small (of change/detail) | adjective (i) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kuzusu/kuzushimasu | to break (a note into coins) | verb (Group 2) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| juwaki | (telephone) receiver | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| toru/torimasu | to take/pick up | verb (Group 2) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| bangō | number | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| mawasu/mawashimasu | to turn/dial | verb (Group 2) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| hanashichū | engaged (phone line) | adjectival noun (na, derived) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | -chū/-jū productive suffix, see dialogue note |
| kaigichū | at a conference | noun (derived) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | -chū derived example |
| shigotochū | in the middle of work | noun (derived) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| ichinichijū | all day long | adverb (derived) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| hitobanjū | all night long | adverb (derived) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| ichinenjū | all year long | adverb (derived) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| karadajū | all over the body | noun (derived) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| iejū | the whole house | noun (derived) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| karada | body | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| itai | painful | adjective (i) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kitanai | dirty | adjective (i) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| moshimoshi | hello (on the phone) | interjection | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | restricted register: telephone-only greeting |
| o-taku | (your) house/home | noun | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | honorific register |
| mōshiwake gozaimasen | I'm very sorry (formal) | phrase | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | more formal than gomen nasai/sumimasen |
| asatte | the day after tomorrow | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| hima | free time / leisure | adjectival noun (na) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| tokoro de | by the way | phrase | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | topic-change discourse marker |
| mawaru/mawarimasu | to go round (to places) | verb (Group 2) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | takes o, see dialogue note |
| machiawase | an arranged meeting | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | base noun of machiawase suru |
| basho | place | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kimeru/kimemasu | to decide | verb (Group 1) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| chūguchi | central entrance | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| tanoshimi ni shite imasu | I'm looking forward to it | phrase (idiom) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | built on te-form + iru, formally introduced Ch.8 |
| benkyō (suru/shimasu) | to study | verb (noun + suru) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | example of productive noun+suru verb class, see dialogue note |

---

## Chapter 8 — Is/are doing; has/have done, had done; has/have been doing; duration of time (p. 85–95)

### Grammar points

#### 50. "Is/are doing" — te form + iru/imasu (or irassharu/oru)
Ongoing action/state is expressed by te form + **iru/imasu** (honorific **irassharu/irasshaimasu**,
humble **oru/orimasu**). Unlike English, Japanese uses this continuous form even for states that
English expresses with a simple present (**aishite imasu** "I love you," **sunde imasu** "I live
(am living)," **hataraite imasu** "he works (is working)," **oboete imasu** "I remember (lit. am
remembering)"). **Shitte imasu** "know" is a unique irregular case: its negative is not
*shitte imasen but the suppletive **shirimasen**. **Motte imasu** (lit. "is holding") is the standard
way to say "have got." A distinct sub-use: the te-iru form of certain intransitive verbs (**shimaru**
"be closed," **aku** "be open," **suku** "be hungry/empty," **kawaku** "be thirsty," **komu** "be
crowded," **tsukareru** "be tired") expresses a resulting passive state, not an ongoing action
(**shimatte imasu** "is closed," **suite imasu** "is hungry/empty").

#### 51. "Has/have done," "had done" — perfect tense, with an intransitive-verb exception
The plain **-mashita** form already covers both simple past and perfect for most verbs (Ch.4). A
specific set of **intransitive motion/change-of-state verbs**, however, require the **te iru/imasu**
form for their *perfect* sense specifically — **iku, kuru, deru, hairu, dekakeru, tsuku, kaeru, neru,
okiru** — e.g. "he's gone to Nagasaki (and is there)" = **Nagasaki e itte imasu**, distinct from plain
**ikimashita** "he's left for/went to Nagasaki," which doesn't imply he's still there. Negative
perfect = te-iru/imasu form, generally with **mada** "not yet" (**mada mite imasen yo** "I haven't
seen it yet"). "Is in [place]" = **(no naka) ni haitte imasu** (lit. "having entered, is in").

#### 52. Duration of time
A set of duration-counters distinct from the point-in-time counters of Chapter 5:
- Years: **-nen** or **-nenkan**.
- Months: Chinese system + counter **-kagetsu** (not **-gatsu**), with sound changes at 1/6/8/10
  (**ikkagetsu, rokkagetsu, hakkagetsu [alt. of hachikagetsu], jukkagetsu**).
- Weeks: counter **-shūkan**, sound changes at 1/8/10 (**isshūkan, hasshūkan, jusshūkan**); "how
  many weeks" = **nanshūkan**.
- Days: uses the **same** day-of-month forms as Ch.5 (futsuka, mikka...) **except** "one day" uses
  **ichinichi**, not *tsuitachi (which is reserved for "the 1st of the month" only) — a genuine
  form/function split within a single paradigm.
- Hours/minutes: hour-duration = o'clock reading + **-kan** (**ichijikan** "one hour," **nijikan han**
  "two and a half hours"); minute-duration generally doesn't take **-kan**.
- "Ago" = duration expression + **mae** ("before").

#### 53. "Has/have been doing," "had been doing" — durative/progressive perfect
Expressed either with a duration expression alone, or duration + **mae kara** ("since...ago"); "how
long" = **dore gurai** or **itsu kara** (lit. "since when"). "Had been doing" changes **-masu** to
**-mashita** on the te-iru form (**matte imashita → matte imashita**, e.g. **Rokujikan mo matte
imashita** "I had been waiting for six hours," with **mo** adding emphasis to the duration). "Since
X" = **X kara**. Crucially, **da/desu** and **iru/imasu** themselves have **no te-imasu form** — "how
long have you been ill" instead uses a bare duration expression with desu (**Tōka gurai (mae kara)
desu**). "Have you ever been to..." requires a different construction entirely, deferred to Ch. 15.

#### Dialogue notes (Conversations 8A–8B, p. 92–95)
- **kiite mite kudasai**: "ask and see"/"try asking" — combines the Ch.6 **-te miru** construction
  with a request.
- **chotto ukagaimasu ga**: "I'd just like to ask you..." (**ukagau/ukagaimasu**, humble, "ask/
  visit/call on" — recurs from Ch.3's dialogue).
- **Dai Ichi Kangin**: real-world abbreviation of Dai Ichi Kangyō Ginkō, described by the source as
  the largest street bank in Japan at time of writing.
- **komaru/komarimasu**: "be stuck/awkward," base verb of the idiom **komarimashita** "that's a
  nuisance."
- The productive **-go** suffix on a country name gives that country's language (**Chūgoku** "China"
  → **Chūgokugo** "Chinese"), with **Eigo** "English" as a lexicalized exception (not *Igirisugo).
- **irassharu n'desu ka**: the plain form + **n'desu** is flagged as a common spoken alternative to
  the **-masu** form, especially in questions — cross-referenced forward to Ch. 9.
- **Gaijin tōrokushō** (full form **Gaikokujin Tōroku Shōmeishō**, "Alien Registration Card"): real
  legal/bureaucratic requirement explicitly noted by the source — all non-naturalized foreign
  residents in Japan over 90 days are legally required to carry one.
- **yaru/yarimasu**: flagged explicitly as a common but **somewhat colloquial** alternative to
  **suru/shimasu** — a genuine register distinction worth flagging for later slang-mechanics work.
  — **mite mimasu**: "I'll have a look and see" (another -te miru use).
- **bakari**: "nothing but..."
- **kyōmi wa nai desu**: "I'm not interested," lit. "as for interest, there isn't any."
- **mo** in **gohan mo tabenaide** means "even" (not "also/too") — a context-dependent sense-shift of
  the same particle seen in earlier chapters.
- **dokoka e**: "(to) somewhere" — one of a family of indefinite expressions (studied fully in
  Ch. 14).

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| aisuru/aishimasu | to love | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| sumu/sunde imasu (sumimasu) | to live (reside) | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| hataraku/hatarakimasu | to work | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| oboeru/oboemasu | to remember | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kodomo | child(ren) | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| sakka | writer | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| ikiru/ikimasu | to be alive / live | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| shitte imasu / shirimasen | to know / not know | verb (irregular neg.) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | suppletive negative, see grammar note 50 |
| zenzen | (not) at all | adverb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | used with negative |
| motte imasu | to have (got) | verb (idiom) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| shimaru/shimarimasu | to be closed | verb (intransitive) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | passive-state te-iru use, grammar note 50 |
| aku/akimasu | to be open | verb (intransitive) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| suku/sukimasu | to be hungry / be empty | verb (intransitive) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | two senses noted by source |
| nodo | throat | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kawaku/kawakimasu | to be thirsty / be dry | verb (intransitive) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| komu/komimasu | to be crowded | verb (intransitive) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| tsukareru/tsukaremasu | to be/get tired | verb (intransitive) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| poketto | pocket | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | English loanword |
| atarashii | new | adjective (i) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| okiru/okimasu | to get up | verb (intransitive) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | perfect requires te-iru form, see grammar note 51 |
| kozutsumi | parcel | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| niwa | garden | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| saikin | recently | adverb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| -nenkan | duration: years | suffix | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| -kagetsu | duration: months (counter) | suffix | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | distinct from point-in-time -gatsu, see grammar note 52 |
| -shūkan | duration: weeks (counter) | suffix | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| tsuzuku/tsuzukimasu | to continue | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| ichinichi | one day (duration) | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | form/function split from tsuitachi, see grammar note 52 |
| sugosu/sugoshimasu | to spend (time) | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| -jikan | duration: hours (suffix) | suffix | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| mae (ni) | ago | adverb (suffix use) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | duration-expression + mae, see grammar note 52 |
| dore gurai | how long? | pronoun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| itsu kara | since when? / how long? | phrase | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kekkon suru/shimasu | to get married | verb (noun + suru) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kara | since (temporal) | particle | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | distinct temporal sense from "from" use, Ch.3 |
| ginkō | bank | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| sagasu/sagashimasu | to look for | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| keisatsukan | police officer | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| ukagau/ukagaimasu | to ask / visit (humble) | verb | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | recurs from Ch.3, humble register |
| komaru/komarimasu | to be stuck / be in trouble | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | base of idiom komarimashita "that's a nuisance" |
| -go | (a country's) language (suffix) | suffix | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | productive except Eigo (lexicalized exception) |
| kuni | country | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| Kanada | Canada | proper noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| n'desu | explanatory copula (colloquial) | suffix/particle | colloquial | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | common spoken alternative to -masu, esp. in questions; cross-ref Ch.9 |
| gaijin | foreigner (colloquial) | noun | colloquial | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | informal register vs. formal gaikokujin, per full legal term in note |
| gaikokujin tōroku shōmeishō | Alien Registration Card | noun | technical | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | real legal/bureaucratic term, legally required for foreign residents over 90 days (per 1998 law) |
| miseru/misemasu | to show | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| sengetsu | last month | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kenkyū suru/shimasu | to research | verb (noun + suru) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| o-sumai | (your) residence | noun | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | honorific register |
| ima no tokoro | for the time being | phrase | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| ryō | dormitory | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| apāto | apartment | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | English loanword |
| yaru/yarimasu | to do (colloquial) | verb | colloquial | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | explicitly flagged by source as a colloquial alternative to suru/shimasu |
| kuizu | quiz (show) | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | English loanword |
| dokyumentarī | documentary | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | English loanword |
| bangumi | (TV/radio) program | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| bakari | nothing but / only | particle | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| jidaigeki | period drama | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | culturally specific TV-genre term |
| kyōmi | interest | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| eigakan | cinema | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| namae | name | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| dekoka e | somewhere (to) | pronoun (indefinite) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | one of a family of indefinites, full paradigm at Ch.14 |

---

## Chapter 9 — Plain forms; idiomatic usages: why/because, probably, I wonder, may/might, intend/plan to, should (p. 96–105)

### Grammar points

#### 54–55a. Formation of all plain forms
The plain (dictionary) present-positive form of every verb is given alongside its **-masu** form
throughout the course's vocabularies. Present negative was covered at Ch.7. **Past positive (the ta
form)**: for all verbs but one, change the **-te/-de** of the te form to **-ta/-da**
(taberu→tabeta, yobu→yonda, kaku→kaita, kuru→kita). The sole irregularity is **da(desu)**, whose
plain present is **da**, te form **de**, and ta form **datta**. **Past negative**: change **-nai** to
**-nakatta** on the present-negative plain form (**inai→inakatta**, **konai→konakatta**). Plain forms
of the te-iru/imasu progressive are built by plugging in the plain forms of iru/imasu at each tense
(tabete imasu→tabete iru; owatte imasen→owatte inai; yasunde imashita→yasunde ita; nete imasen
deshita→nete inakatta).

#### 56–57. "Why...?"/"because..." — naze/dōshite + plain form + n'desu; kara vs. no de
"Why" = **naze** or **dōshite**. The expected answer pattern uses the **plain form + n'desu** (less
commonly unabbreviated **no desu**) — n'desu here carries a literal "it is because/the thing is"
explanatory force, and is used not only in why-questions/answers but generally for explanatory or
emphatic statements (sometimes merely to break up a monotonous run of **-masu** forms). Before
**n'desu**, a na-adjective or da/desu takes **na**, not **da** (**Dame nan'desu**, with the vowel
elided to **nan'desu**). Separately, "because/so" = **kara** or **no de** (te form of no desu): the
two are near-equivalent, but **no de** is generally preceded by a plain form even in otherwise polite
speech, while **kara** is generally preceded by the **-masu** form in polite speech.

#### 58. "Probably" — deshō (plain darō)
**Deshō**, often paired with **tabun** "perhaps" or **osoraku** "presumably," means "probably"; it
can never be preceded by **da**. With rising intonation it functions almost identically to **ne**
(a tag-question softener). **Deshō ka (ne)** = "I wonder if/whether..."; combined with a question
word, "I wonder who/where/etc....?"

#### 59. "May possibly be" — ka mo shiremasen
Attached to a plain form or a noun, **ka mo shiremasen** = "may possibly be," often paired with
adverbs **hyotto suru to** or **moshi ka suru to** ("maybe").

#### 60. "Intend to"/"plan to" — tsumori da/desu vs. yotei da/desu
**Tsumori da/desu** = "intend/mean to"; **yotei da/desu** = "plan to" (more concrete/scheduled than
tsumori). Negatives: **tsumori wa nai/arimasen**, **yotei wa nai/arimasen**.

#### 61. "Should"/"ought" — beki (ja nai) vs. hazu
English "should/ought" covers two distinct senses the source is careful to split: **obligation**
("you shouldn't say that") uses **beki (ja nai)**; **expectation** ("the shop ought to be open by
now") uses **hazu**, which also covers "expected to/due to/supposed to." Negative of hazu: **hazu ga
(wa) nai/arimasen**.

#### Dialogue notes (Conversations 9A–9B, p. 102–105)
- **o-taku**: polite word for "house" (vs. plain **ie**); as an adjective **o-taku no...** can mean
  "your..."
- **o-machi shite orimashita**: humble-register pattern (verb stem + **o-** + **suru/shimasu**),
  formally covered at Ch.20; the source notes Mrs. Inoue's speech throughout these dialogues uses
  notably more polite language than the male speakers, flagged as typical of women's speech in this
  era/register (**no yo** sentence-final particle and the imperative abbreviation **'rasshai** <
  irasshai are both explicitly flagged by the source as characteristic of women's speech).
- **ka nanika**: "or something or other."
- **nasaru/nasaimasu**: honorific form of suru/shimasu; **go-** (like **o-**) is a productive
  honorific prefix on certain (often Sino-Japanese) nouns.
- **-hajimeru/-hajimemasu** suffix on a verb's -masu stem = "begin to..." (**mochihajimeta** "began
  to have (an interest)," **kenkyū shihajimeru** "begin to research") — another productive
  derivational pattern.
- **Plain vs. polite kinship terms**: Japanese systematically distinguishes **plain terms** (used to
  refer to one's *own* family members) from **polite terms** (used to refer to *others'* family
  members); several polite terms double as address terms for one's own family too. Full paradigm
  given by the source (p. 105–106): father **chichi**/**o-tō-san**\*, mother **haha**/**o-kā-san**\*,
  parents **ryōshin**/**go-ryōshin**, husband **shujin**/**go-shujin**, wife **kanai**/**oku-san**,
  siblings **kyōdai**/**go-kyōdai**, older brother **ani**/**o-nī-san**\*, older sister
  **ane**/**o-nē-san**\*, younger brother **otōto**/**otōto-san**, younger sister
  **imōto**/**imōto-san**, son **musuko**/**musuko-san**, daughter **musume**/**musume-san**,
  grandfather **sofu**/**o-jī-san**, grandmother **sobo**/**o-bā-san**, uncle **oji**/**oji-san**,
  aunt **oba**/**oba-san** (\* = also usable addressing one's own family member directly). **oji-san**
  and **oba-san** also double as informal generic words for "(older) man" and "(older) woman"
  respectively. A Japanese speaker counting their own siblings **includes themselves** in the count
  (**kyōdai wa sannin desu** "I've got two brothers," lit. "siblings are three"). Birth-order terms:
  **chōnan** "eldest son," **jinan** "second son," **chōjo** "eldest daughter," **jijo** "second
  daughter."

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| naze / dōshite | why? | adverb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | see grammar note 56 |
| n'desu / no desu | explanatory copula | suffix/particle | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kaigai | abroad | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| ashi | leg / foot | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| sugoku | really / terribly | adverb | colloquial | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | intensifier, colloquial register |
| shigoto | work / job | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| sorosoro | soon / gradually | adverb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| gaishoku suru/shimasu | to eat out | verb (noun + suru) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| suteru/sutemasu | to throw away | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| shōtai suru/shimasu | to invite | verb (noun + suru) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| tabun | perhaps | adverb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | often paired with deshō |
| osoraku | presumably | adverb | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| deshō/darō | probably | copula (idiomatic) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | darō is plain form; never preceded by da |
| ka mo shiremasen | may possibly be | phrase | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| hyotto suru to / moshi ka suru to | maybe | adverb (phrase) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| shumi | hobby / taste | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| utsu/utte imasu (uru/urimasu) | to sell | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| tsumori da/desu | intend to / mean to | phrase (idiom) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | see grammar note 60 |
| yotei da/desu | plan to | phrase (idiom) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| wasureru/wasuremasu | to forget | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| shuppan suru/shimasu | to publish | verb (noun + suru) | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| beki (ja nai) | should (obligation) | phrase (idiom) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | see grammar note 61 |
| hazu | should (expectation) / due to / supposed to | phrase (idiom) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| hikōki | airplane | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kaigi | meeting | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kōshō suru/shimasu | to break down (mechanical) | verb (noun + suru) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| o-taku | house (polite) | noun | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | polite for ie; o-taku no = "your..." |
| kurabu katsudō | club activities | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| o-agari kudasai | please come in (Japanese-style house) | phrase | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | verified | contrastive pair with o-hairi kudasai, Ch.1 — now directly attested in dialogue |
| mugicha | barley tea | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | culturally specific beverage term |
| shidai | depends on... | suffix/noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | o-kane shidai "depends on the money," tenki shidai "depends on weather," anata shidai "depends on you" |
| go-kenkyū nasaru/nasaimasu | to do research (honorific) | verb | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | go- + nasaru honorific pattern |
| kindaishi | modern history | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| mochihajimeta (mochihajimeru) | began to have (interest) | verb (derived) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | -hajimeru productive suffix, see dialogue note |
| fukuzatsu | complicated | adjectival noun (na) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| eikyō | influence | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kigaeru/kigaemasu | to change clothes | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| ryōshin | parents (plain) | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | plain/polite kinship pair, see dialogue note |
| otoko | man / male | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kōkūgaisha | airline company | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| tsutomeru/tsutomemasu | to work for / be employed at | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| futaritomo | both (of two people) | adverb/noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| rainen | next year | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| itsuka | someday | adverb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| muri | impossible / unreasonable | adjectival noun (na) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kowai | frightening / scary | adjective (i) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |

---

## Chapter 10 — Verbs of giving and receiving; doing things for people; having things done (p. 107–118)

### Grammar points

#### 62–65. The giving/receiving verb system is governed by relative social/emotional distance, not just grammatical person
Japanese's giving/receiving verbs are **not freely substitutable synonyms** — the choice encodes the
speaker's perceived social/in-group closeness between giver and receiver, and misuse "can result in
impoliteness" (explicit source warning, p. 107). Four grammatical slots, each with a plain/respectful
pair:
- **Giving, 1st-person-identified-with-giver**: **ageru/agemasu** (neutral-to-lower-status receiver,
  or higher-status receiver if absent) vs. **sashiageru/sashiagemasu** (more respectful; used for a
  present, higher-status receiver, especially if that person or someone expecting deference to them
  is actually present). Family members don't normally need the more respectful form even when
  discussed with outsiders.
- **Giving, 1st-person-identified-with-receiver**: **kureru/kuremasu** and **kudasaru/kudasaimasu**
  (the latter more respectful) — **these two can never take a 1st-person-giver subject**; used when
  someone else gives to the speaker or to someone the speaker identifies with more closely than the
  giver.
- **Receiving**: **morau/moraimasu** (receiver of equal/higher status than giver, or lower status if
  the giver is absent/no respect-expecting party present) vs. **itadaku/itadakimasu** (more
  respectful; receiver deems themselves humbler than giver, or giver warrants special respect). The
  person given-from takes **ni** or **kara**. The source explicitly notes that in practice, Japanese
  speakers favor **morau/moraimasu** and **itadaku/itadakimasu** over **kureru/kuremasu** and
  **kudasaru/kudasaimasu** even in situations where either would be grammatical — i.e. "I received it
  from him" (moraimashita) is preferred in practice over "he gave it to me" (kuremashita).
- In every pair, which member to use depends on **who is present and would expect deference shown** —
  the same proposition can take either member of a pair depending purely on who else is listening,
  not on any change in the underlying relationship.

#### 66–66a. Having things done — te form + itadaku/morau
Te form of a verb + **itadaku/itadakimasu** or **morau/moraimasu** = "have something done"/"get
somebody to do something"; the person made to perform the action takes **ni**. Ambiguous between
"get somebody to do X" and "somebody was kind enough to do X for me" — disambiguated by context.

#### 67–68. Doing things for others — te form + kureru/kudasaru vs. te form + ageru
Te form + **kureru/kuremasu** or **kudasaru/kudasaimasu** = "(be kind enough to) do something for
somebody," recipient takes **ni**. Te form + **ageru/agemasu** = "do something for others," but the
source gives an explicit usage warning: **avoid te ageru/agemasu except with a very close friend or
a child**, since it can sound patronizing — a genuine register/pragmatics trap for learners, worth
flagging for later slang-mechanics work (a well-intentioned "I'll help you" can misfire socially).

#### 69. Doing things for others/having things done, masu-alone vs. humble-verb alternative
"Professor, shall I help you?" can use the plain **-masu** form alone (**tetsudaimashō ka**) or,
more respectfully, a dedicated or derived **humble verb**. Dedicated humble-verb pairs: **suru→itasu/
itashimasu** "do," **iku→mairu/mairimasu** "go," **kuru→mairu/mairimasu** "come" (go and come share
one humble form), **iu→mōsu/mōshimasu** "say." Verbs with no dedicated humble form are made humble
periphrastically: strip **-masu** from the verb stem, add **o-** before and **shimasu** after
(**oshiemasu → o-oshie shimasu**, **miseru → o-mise shimasu**) — a fully productive pattern, distinct
from the handful of lexically dedicated humble verbs.

#### Dialogue notes (Conversations 10A–10B, p. 115–117)
- **kashira** and sentence-final **wa** (as a softener, not the topic particle) are both flagged as
  characteristic of women's speech, alongside **sō ne** (a more familiar variant of sō desu ne used
  between close friends, here with some plain forms too) — a recurring pattern across this course's
  dialogues of marking register/gender-associated speech explicitly.
- **-teki** suffix on a noun productively derives a na-adjective (**seiji** "politics" →**seijiteki**
  "political"; **keizai** "economics" → **keizaiteki** "economic/economical"; **Nihon** →
  **Nihonteki** "Japanese(-style)").
- **tanjōbi o-medetō gozaimasu** "Happy Birthday" is one instance of a general congratulatory formula
  **o-medetō gozaimasu**, reused for other occasions (**akemashite o-medetō gozaimasu** "Happy New
  Year").
- **-tachi**: plural suffix, here on a person's name + -san (**Inoue-san-tachi** "the Inoues") —
  recurs from the pronoun pluralization already seen (Ch.2's **watashi-tachi**).
- **kite kudasatte arigatō gozaimasu** / **-te itadaite arigatō gozaimasu**: both attested as "thank
  you for coming" — the te-form-based gratitude construction can draw on either the kudasaru or
  itadaku side of the giving/receiving system interchangeably in this specific idiom.

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| ageru/agemasu | to give (1st-person giver, neutral/lower-status receiver) | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | see grammar note 62-65 |
| sashiageru/sashiagemasu | to give (respectful) | verb | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kureru/kuremasu | to give (to speaker/in-group, neutral) | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | never takes 1st-person giver subject |
| kudasaru/kudasaimasu | to give (to speaker/in-group, respectful) | verb | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| morau/moraimasu | to receive (neutral) | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | source notes this is preferred in practice over kureru even where both are grammatical |
| itadaku/itadakimasu | to receive (respectful) | verb | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | also "to eat/drink" humbly, recurs from Ch.5 |
| shachō | company president | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| tetsudau/tetsudaimasu | to help | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| shio | salt | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| itasu/itashimasu | to do (humble) | verb | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | dedicated humble form of suru, grammar note 69 |
| mairu/mairimasu | to go / come (humble) | verb | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | shared humble form of both iku and kuru |
| mōsu/mōshimasu | to say (humble) | verb | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | cf. Ch.1's ...to mōshimasu self-naming idiom |
| purezento | present (gift) | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | English loanword |
| nihonteki (na) | Japanese(-style) | adjectival noun (na, derived) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | -teki productive suffix, see dialogue note |
| seiji | politics | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | base of seijiteki, dialogue note example |
| keizai | economics | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | base of keizaiteki |
| sensu | folding fan | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | culturally specific item |
| furoshiki | wrapping cloth | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | culturally specific item |
| kōkōjidai | high school days | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| baito (arubaito) suru/shimasu | to work part-time | verb (noun + suru) | colloquial | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | baito is a common clipped form of the German-derived loanword arubaito |
| nandemo | anything / everything | pronoun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| kanpai | cheers! (toast) | interjection | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | verified | recurs from Ch.1 |
| supīchi | speech | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | English loanword |
| suteki (na) | lovely / wonderful | adjectival noun (na) | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| pātei | party | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | verified | recurs from Ch.4 |
| go-chisō | a feast / treat (food) | noun | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | honorific go- |
| tsukuru/tsukurimasu | to make | verb | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| himitsu | secret | noun | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | |
| o-medetō gozaimasu | congratulations | phrase | formal | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | general congratulatory formula, reused across occasions |
| -tachi | plural suffix | suffix | core | — | contemporary (source published 1998) | — | — | grammar_reference | n/a | plausible_unverified | recurs from Ch.2 pronoun pluralization |
