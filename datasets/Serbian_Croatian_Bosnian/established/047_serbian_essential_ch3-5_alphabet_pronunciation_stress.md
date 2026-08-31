# Serbian — Established Grammar: Chapter 3 "Alphabet," Chapter 4 "Pronunciation," Chapter 5
"Stress"

**Source:** Lila Hammond, *Serbian: An Essential Grammar* (Routledge, 2005), Chapter 3 "Alphabet"
(printed pp. 13–16), Chapter 4 "Pronunciation" (printed pp. 17–30), Chapter 5 "Stress" (printed pp.
31–34). PDF page boundaries located via `pdftotext -layout` search for the "Chapter 3"/"Chapter 6"
heading text (front-matter offset confirmed: printed-page numbers run roughly 12 pages behind PDF
page numbers). Chapter 3 begins at PDF text-line ~744 of the full-book extraction, Chapter 6
("Verbs") begins at PDF text-line ~1463 — Chapters 3–5 span that range. Source has a real text
layer; `pdftotext -layout` was used directly. **Important extraction caveat:** this PDF's embedded
Cyrillic font uses a private/custom glyph encoding that `pdftotext` cannot map to correct Unicode —
Cyrillic text throughout the book extracts as visual gibberish (e.g. "rjkf" instead of "кола"), and
critically **the same corruption also silently affects diacritic Latin letters** (č, ć, đ, š, ž)
even in the book's own "clean" Latin-transliteration column (e.g. "aekati" = čekati, "teEka" =
teška, "falostan" = žalostan). This was decoded by cross-referencing corrupted forms against known
Serbian words and the book's own English glosses, not read directly. Anywhere this decoding
involved a genuine judgment call rather than an unambiguous match, it is flagged below with
`Vision Reading Confidence: low_confidence` even though the source technically has a text layer, in
the same spirit as the extraction spec's vision-reading confidence scale (the corrupted-glyph
problem is functionally the same kind of not-directly-legible-text risk). No handwritten marginalia
was found in this chunk.

**Coverage note — what was skipped as redundant vs. kept as new/deeper.** This book's Chapters 3–5
overlap heavily with two already-extracted companion-source files covering the same ground from a
different book (Ronelle Alexander's *Bosnian, Croatian, Serbian: A Grammar*): `044_grammar_
ch19_clitic_accent.md` (accent/stress mechanics, PLACE-vs-FORM shifts, the four-accent system) and
`045_grammar_ch20_phonology.md` (palatalization, l→o shift, voicing assimilation, cluster
simplification, fleeting/inserted vowels). Per this dispatch's instruction, only genuinely new or
deeper material from Hammond's own treatment is extracted here; where content is substantially the
same phenomenon already captured in 044/045, only a brief cross-reference is given rather than a
re-extraction.

**Skipped as redundant** (already fully covered in 044/045, no material addition here beyond a
different worked example or two): the basic four-accent system (long/short × rising/falling);
morphophonemic PLACE-vs-FORM accent shifts generally; the l→o word-final shift's core mechanism
(rekao/rekla, topao/topla — 045 §167d covers this with its own example set); voicing assimilation's
core mechanism (sladak/slatka, svat/svadba — same phenomenon as 045 §167e); consonantal
contraction/cluster-simplification's core mechanism (bezvučan-type double-consonant drop, the naj-
exception — same as 045 §167f, which also documents the naj- exception); the general fleeting-a
mechanism and its role in Nsg./L-participle forms (covered by 045 §167g); proclitic-triggered
stress shift as a phenomenon (Section 5.2 here is the same mechanism as 044 §166c's
prefix/preposition accent retraction, including the same "increasingly archaic outside Bosnia"
framing Hammond doesn't state explicitly but which matches 044's `skakanje` discussion).

**Kept as new/deeper:**
- A full, cleanly reconstructed Cyrillic↔Latin alphabet correspondence table (Chapter 3) — no prior
  file in this dataset has this as a clean standalone reference, per the dispatch's explicit
  encouragement to keep it even given some conceptual overlap elsewhere.
- Hammond's own consonant-classification framework (obstruent/resonant; labial/dental/palatal/
  velar; the 14 voiced/unvoiced pairs plus the seven voiced-only and three voiceless-only
  "unpaired" consonants) — a taxonomy not present in 045's treatment.
- A complete, explicit consonant-mutation table for what happens when /j/ follows each consonant
  (d+j→đ, t+j→ć, l+j→lj, etc.) plus its lexical exceptions (koza/kozji, klas/klasje) — 045 only
  describes this class of change abstractly ("Type C softenings, triggered by /j/") without
  itemizing the full pairing table or the exceptions.
- The first/second-palatalization-before-e/i alternation with its own worked verb paradigms
  (peći/pečem/peku; vući/vučem/vuku; strići/strižem/strigu) and, notably, an explicit exception
  list for the dative/locative-singular-feminine pattern (baka/baki, Anka/Anki, Olga/Olgi,
  Beograđanka/Beograđanki, Bosanka/Bosanki, frizerka/frizerki — occupational names in general don't
  undergo the change) that 045 does not give.
- An exhaustive itemized list of word-final consonant clusters (traditional four vs. the wider
  modern eight), which 045 discusses only in the abstract.
- /r/ functioning as a syllabic (vowel-like) sixth "vowel" between two consonants (hrt "greyhound,"
  trg "market square") — not mentioned in 045's chunk at all.
- Specific instances of the o→e-after-soft-consonant alternation in grammatical categories 045
  doesn't itemize: the possessive-adjective suffix (-ov/-ev), the -ovati/-evati verb-formation
  suffix, and the instrumental-case -om/-em noun ending.
- A beginner-level "which syllable gets the stress" heuristic (2-syllable words: first syllable;
  3-syllable words: first or second syllable) — a simplified rule 044's more rigorous PLACE/FORM
  treatment doesn't state in this form.
- An explicit regional-register note on vowel length in unstressed syllables: Belgrade speech keeps
  unstressed vowels short (length concentrated on the stressed syllable), while more classical
  pronunciations, "and certainly... the speech of people from Bosnia," can retain several long
  vowels in a word even where none of them is stressed — a geographic/register observation not in
  044 or 045.
- Sentence-level (as opposed to lexical) stress: the more semantically important a word is in
  context, the heavier its stress — a pragmatic dimension 044's chapter (which is about
  morphophonemic/lexical accent) does not address.

---

## Alphabet: Cyrillic ↔ Latin correspondence (Chapter 3, printed pp. 13–16)

Serbian uses two parallel 30-letter alphabets, ћирилица/ćirilica (Cyrillic, adopted from Greek
during the Byzantine era) and латиница/latinica (Latin, adopted in the 14th century by Serbs in the
western regions that became Croatia — the same Latin base as English plus five extra letters/eight
extra sounds). Every letter in both alphabets is pronounced; there is no silent-letter ambiguity.
Reconstructed here (the source's own printed Cyrillic glyphs did not survive `pdftotext` extraction
intact — see the extraction caveat above — so the table below uses standard Unicode Cyrillic,
cross-checked letter-by-letter against the book's own Latin-equivalent and English-sound-example
columns, which did extract legibly and confirm the standard 30-letter Vuk Karadžić ordering):

| Cyrillic | Latin | Approx. English sound reference (per source) |
|---|---|---|
| А а | A a | "Assam" |
| Б б | B b | "bench" |
| В в | V v | "victim" |
| Г г | G g | "good" |
| Д д | D d | "desk" |
| Ђ ђ | Đ đ | "due" (as pronounced in British English) |
| Е е | E e | "let" |
| Ж ж | Ž ž | "pleasure" |
| З з | Z z | "Zen" |
| И и | I i | "he" |
| Ј ј | J j | "yoyo" |
| К к | K k | "club" |
| Л л | L l | "liver" |
| Љ љ | Lj lj | "million" (pronounced as one simultaneous sound, not two) |
| М м | M m | "man" |
| Н н | N n | "no" |
| Њ њ | Nj nj | "minion" (also one simultaneous sound) |
| О о | O o | "operate" |
| П п | P p | "pen" |
| Р р | R r | "Ferrero" (rolled) |
| С с | S s | "stop" |
| Т т | T t | "top" |
| Ћ ћ | Ć ć | "tube" (British pronunciation) |
| У у | U u | "room" |
| Ф ф | F f | "futon" |
| Х х | H h | "Henry" |
| Ц ц | C c | "lots" (i.e. "ts") |
| Ч ч | Č č | "chocolate" |
| Џ џ | Dž dž | "juke-box" |
| Ш ш | Š š | "shoulder" |

Notes from the source: the English letters q, w, x, and y do not exist in the Serbian alphabet.
Cyrillic у/u has two handwritten forms (with and without a crossbar); handwritten Cyrillic л/l
similarly has two forms (tail up vs. tail down). The Latin alphabet's collation order (as opposed
to the Cyrillic order above) places the digraphs and diacritic letters as their own single
alphabetic units immediately after their base letter: ...C, Č, Ć, D, Dž, Đ, E... and ...L, Lj, M, N,
Nj, O... and ...S, Š, T... and ...Z, Ž — i.e. Lj, Nj, Dž, Č, Ć, Đ, Š, Ž each sort as one letter, not
as a two-letter sequence, exactly like the Cyrillic single-glyph letters they correspond to.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| maturant | high-school graduate | noun (m) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Ch.5 (p.31); given as the book's example of an exception to "stress never falls on the last syllable" — a different lexical example of the same non-initial-stress-exception phenomenon 044 documents with `absolvent`/`poljoprivreda`. |
| baka / baki | grandmother (nom./dat.-loc. sg.) | noun (f) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Ch.4 §4.1.8 (p.28); cited as an exception to the k→c/g→z/h→s dative-locative palatalization rule — the final consonant does NOT change here. |
| Anka / Anki | Anka (woman's name), nom./dat.-loc. sg. | proper noun (f) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Same exception list as baka/baki. |
| Olga / Olgi | Olga (woman's name), nom./dat.-loc. sg. | proper noun (f) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Same exception list. |
| Beograđanka / Beograđanki | woman from Belgrade, nom./dat.-loc. sg. | noun (f) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | low_confidence | Same exception list; đ-diacritic reconstructed via the font-corruption decoding described in the header note. |
| Bosanka / Bosanki | Bosnian woman, nom./dat.-loc. sg. | noun (f) | core | — | contemporary (source published 2005) | Bosnia (referent, not a dialect tag) | — | grammar_reference | n/a | n/a | Same exception list; source notes other female occupational names also don't undergo the change. |
| frizerka / frizerki | hairdresser (f.), nom./dat.-loc. sg. | noun (f) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Same exception list; explicitly generalized in the source to "other female occupational names" as a class. |
| hrast | oak | noun (m) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Ch.4 §4 point 6 (p.18); illustrates the -st word-final consonant cluster, one of the traditional four "legal" word-final clusters. |
| park | park | noun (m) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Same list; illustrates the newer, wider -rk cluster (not one of the traditional four). |
| princ | prince | noun (m) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Same list; illustrates -nc. |
| disk | disc | noun (m) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Same list; illustrates -sk. |
| vožd | leader/duke (archaic/historical title) | noun (m) | archaic | — | contemporary (source published 2005) | Serbian | national | grammar_reference | n/a | low_confidence | Same list; illustrates -žd. Ž-diacritic reconstructed via font-corruption decoding — cross-checked against the known historical Serbian title (used e.g. of Karađorđe) rather than read directly. |
| hrt | greyhound | noun (m) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Ch.4 §4.2 (p.28); illustrates /r/ functioning as a syllabic sixth vowel between two consonants, with no written vowel letter at all. |
| trg | (market) square | noun (m) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Same point as hrt; second illustrative example of syllabic /r/. |
| grad (long vowel) / grad (short vowel) | city / hail | noun (m) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Ch.4 §4.2.1 (p.29); minimal pair distinguished purely by vowel length — same word spelled identically in Latin script, disambiguated only by pronunciation/accent-mark convention. |
| ugao / uglovi / ugla | corner (nom.sg. / nom.pl. / gen.sg.) | noun (m) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Ch.4 §4.1.6 point 3 (p.23-24); l→o word-final shift paradigm, distinct lexical item from 045's posao/posla and čitalac/čitaoca examples. |
| deo / delovi / dela | part (nom.sg. / nom.pl. / gen.sg.) | noun (m) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Same paradigm family as ugao; -eo nominative singular with -el- in oblique forms. |
| vo / volovi / vola | ox (nom.sg. / nom.pl. / gen.sg.) | noun (m) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Same l→o paradigm family. |
| so / soli | salt (nom.sg. / gen.sg.) | noun (f) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Feminine counterpart in the same l→o paradigm family (only feminine noun in this set). |
| koza / kozji | goat / goat's (adj.) | noun (f) / adjective | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Ch.4 §4.1.7 (p.26); explicit lexical exception where /j/ does NOT palatalize a preceding з/z. |
| klas / klasje | ear of grain / ears of grain | noun (m) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Same exception class as koza/kozji — /j/ does not palatalize a preceding с/s here either. |

**Vocabulary note:** most of the illustrative words scattered through Chapters 3–5's phonology
drills (consonant-pair charts, voicing-assimilation minimal pairs, general fleeting-a examples,
etc.) restate mechanisms already fully captured in 044/045 with their own example sets, so per the
coverage rule those repeated drill items are not re-tabled here — only lexical items tied to a
genuinely new grammar point (a new exception list, a new cluster-list item, a new paradigm family
not previously captured) are included above.

## Grammar points

### Consonant classification framework (Ch.4 §4.1)

Hammond organizes Serbian's 25 consonants along two independent axes not used by 045's treatment:
(1) **obstruent** (restricted airflow — the majority of consonants) vs. **resonant** (airflow
continuous, vowel-like: v, r, j, l, lj, n, nj, m); (2) place of articulation — **labial** (b, p, f),
**dental** (d, t, z, s, c, n, r, l), **palatal** (đ, ć, č, dž, ž, š), **velar** (g, k, h). Of the 25
consonants, 14 form voiced/voiceless pairs (voiced: b, g, d, đ, ž, z, dž; voiceless: p, k, t, ć, š,
s, č); the remaining 11 are unpaired — seven are voiced with no voiceless counterpart (j, l, lj, r,
m, n, nj) and three are voiceless with no voiced counterpart (h, f, c).

### Voicing-assimilation spelling exception (Ch.4 §4.1.1)

Same core rule as 045 §167e (regressive voicing assimilation across a consonant cluster). One
specific spelling exception Hammond states explicitly that 045's chunk doesn't itemize with this
prefix/suffix list: д/d does not change to т/t **in spelling** even though it does devoice in
**pronunciation**, specifically before с/s or ш/š, in words prefixed with над-/nad-, од-/od-,
пред-/pred-, под-/pod-, or suffixed with -ски/-ski or -ство/-stvo (e.g. gradski "city [adj.]",
predsednik "president" — both pronounced with a devoiced [t] but spelled with d).

### Soft vs. hard consonants (Ch.4 §4.1.2)

A classification axis independent of voicing: consonants are **soft** if the tongue is raised to
the palate during articulation (c, č, ć, dž, š, ž, j — the palatal consonants above), and **hard**
otherwise. Notably, ц/c is phonetically hard (not palatal) but is treated as grammatically soft in
declensional endings — a mismatch between phonetic and grammatical classification worth flagging.
Separately, the dental consonants t, d, n, l are phonetically hard but become "palatalized" softer
consonants (ć/đ/nj/lj respectively) whenever /j/ is added and the two sounds merge into one.

### The /j/-mutation table (Ch.4 §4.1.7)

A complete pairing of what each consonant becomes when /j/ follows it and the two merge into one
sound: d+j→đ, t+j→ć, l+j→lj, n+j→nj, z+j→ž, s+j→š, p+j→plj, b+j→blj, v+j→vlj, m+j→mlj, k+j→č, h+j→š,
g+j→ž, st+j→šć, zd+j→žd. This is used in forming (a) comparative adjectives (sladak→slađi
"sweeter"), (b) past passive participles (nositi→nošen "carried", osloboditi→oslobođen "liberated"),
(c) nouns from verbal adjectives/other nouns via -je/-ja suffixes (oslobođen→oslobođenje
"liberation"; kap→kaplja "a drop"), and (d) the feminine instrumental-singular -ju ending
(ljubav→s ljubavlju "with love"). Explicit lexical exceptions where a following /j/ does *not*
trigger the s/z change: koza→kozji ("goat's," not *kožji), klas→klasje ("ears of grain," not
*klaše).

### Palatalization before e and i (Ch.4 §4.1.8)

Two related but distinct consonant-alternation patterns before front vowels, presented with fuller
worked paradigms than 045's abstract treatment:

1. **k/g/h → č/ž/š** before the vocative-case ending -e and before the present-tense/imperative -e-
   stem vowel: vojnik→vojniče ("soldier," vocative); Bog→Bože ("God," vocative); duh→duše ("ghost,"
   vocative); and verb-stem alternations peći ("to bake," stem pek-) → pečem (1sg.) but peku
   (3pl.); vući ("to pull," stem vuk-) → vučem (1sg.) but vuku (3pl.); strići ("to shear," stem
   strig-) → strižem (1sg.) but strigu (3pl.) — the 3rd-plural -u ending does not trigger the
   change, only the -e-containing endings do.
2. **k/g/h → c/z/s** before the vowel и/i, occurring in (a) the plural declension of masculine/
   neuter nouns except masc. gen./acc. and neuter nom./gen./acc. (vojnik→vojnici "soldiers";
   bubreg→bubrezi "kidneys"; duh→duhi/duši "ghosts"), (b) the dative/locative singular of feminine
   nouns ending in these consonants (ruka→ruci "hand/arm"; noga→nozi "leg"), and (c) the
   imperative (seći→seci! "cut!"). Pattern (b) has a notable exception class the source flags
   explicitly: some feminine nouns keep the consonant unchanged in dative/locative singular —
   baka/baki, Anka/Anki, Olga/Olgi, Beograđanka/Beograđanki, Bosanka/Bosanki, frizerka/frizerki —
   with occupational female names generalized as not undergoing the change as a class.

### Word-final consonant clusters (Ch.4 §4 point 6, and §4.1.5)

The traditional Serbian view holds only four consonant clusters can legally end a word: -st, -št,
-zd, -žd (e.g. hrast "oak"). Modern Serbian in practice also tolerates word-final -rk, -nc, -nt,
-sk (park, princ, maturant, disk) and others (bicikl "bicycle," film "film," dirigent "conductor").
Any word ending in a consonant cluster outside these patterns generally has a fleeting a inserted
before the final consonant instead (same underlying mechanism as 045 §167g, not re-derived here).

### /r/ as a syllabic sixth vowel (Ch.4 §4.2)

Alongside Serbian's five written vowels (a, e, i, o, u), the consonant /r/ functions as a
vowel-like syllable nucleus when it stands between two consonants, with no vowel letter written at
all — hrt "greyhound," trg "market square." This point does not appear in 045's chunk.

### O/e alternation after soft consonants — additional grammatical categories (Ch.4 §4.2.2)

045 §167c already documents the general o→e shift after soft/palatal consonants in grammatical
endings (citing selo/polje, gradom/mužem as its examples). Hammond's chapter gives three additional
specific grammatical categories where the same underlying alternation applies, not itemized in 045:
(1) the possessive-adjective suffix -ов/-ov becomes -ев/-ev after a soft consonant (čovekov sat "a
man's watch" vs. vodičev auto "a guide's car"); (2) the verb-forming suffix -овати/-ovati sometimes
becomes -евати/-evati after a soft consonant (bičevati "to whip," alongside an also-acceptable
bičovati); (3) the masculine/neuter instrumental singular ending -ом/-om becomes -ем/-em after a
soft consonant, except in most loanwords, which keep -ом/-om (sa majmunom "with a monkey" vs. sa
slončićem "with a little elephant," but sa Radom "with Rade" — a personal name treated as a
loanword-pattern exception here).

### Beginner stress-placement heuristic and register note on vowel length (Ch.5 §5.1)

Two points not present in 044's more technical PLACE/FORM treatment: (1) a simplified pedagogical
rule — stress never falls on the last syllable (with rare lexical exceptions like maturant); in a
two-syllable word it falls on the first syllable; in a three-syllable word it falls on the first or
second syllable; (2) a regional/register observation on vowel length: in common Belgrade speech,
unstressed syllables are almost always short, with length concentrated on the stressed syllable,
whereas "in more classical pronunciations, and certainly in the speech of people from Bosnia,"
multiple long vowels can occur in the same word even when they are not the stressed one. This
geographic contrast is not stated in 044 or 045.

### Sentence-level stress (Ch.5 §5.3)

Beyond a word's own fixed lexical accent, the more semantically important a word is within its
sentence, the heavier its stress becomes in practice — offered as the explanation for why the
"same" word can seem to carry different stress weight depending on context. This pragmatic,
sentence-level dimension of stress is outside the scope of 044's chapter (which treats accent as a
lexical/morphophonemic property of words and clitic groups, not of discourse emphasis).

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — grammar explanations above are paraphrased in this
extractor's own words; illustrative example words/short phrases are reproduced only as needed to
show the alternations themselves, never as continuous explanatory prose, consistent with
`../../00_Reference_Extraction_Spec.md`'s copyright discipline rule.
