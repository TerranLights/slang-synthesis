# English — Established Vocabulary/Grammar: CMOS Ch. 11, "Foreign Languages," pt. 3 (§§11.45–11.68: German word division through compounds; German special characters; Hungarian; Italian; Latin; Norwegian; Polish)

**Source:** *The Chicago Manual of Style*, 16th edition (University of Chicago Press, 2010), Chapter
11, "Foreign Languages," PDF pp. 1407–1430 (sections 11.45 through 11.68).

**Coverage note:** This is part 3 of the chapter's multi-part split (`036_..._pt01.md` covered
§§11.1–11.20; this chunk, numbered `038_..._pt03`, begins at §11.45). **A gap exists between
§11.20 (end of pt01) and §11.45 (start of this chunk): §§11.21–11.44 — the remainder of Czech, plus
Danish, Dutch, Finnish, French, and the opening of German through German quotation marks — were not
covered by pt01 and are not covered here either.** That range presumably belongs to a `pt02` file
this dispatch was not given visibility into (no such file existed in `established/` at the time of
this chunk's extraction); the orchestrator should confirm `pt02`'s existence/dispatch separately
before treating the chapter's Latin-alphabet-language sequence as complete. This chunk itself picks
up mid-German (word division for vowels, consonants, and compounds, then special characters),
continues through the remainder of the Latin-alphabet language sequence in alphabetical order —
Hungarian, Italian, Latin, Norwegian — and ends mid-Polish, at §11.68 (word division), stopping
before §11.69 (Polish special characters), which falls outside this page range.

As in pt01, several entries in this range are pure cross-reference stubs with no independent content
of their own: §11.49 (Hungarian capitalization), §11.65 (Norwegian capitalization), and §11.67
(Polish capitalization) all read only "See 11.3, 11.9" as their opening sentence before any
language-specific addition (Norwegian and Polish each add one further sentence after the pointer, so
those two are captured as partial grammar points below rather than skipped outright; Hungarian's
§11.49 is a pure stub with literally nothing beyond the pointer and is not treated as a separate
grammar point, consistent with pt01's treatment of equivalent stubs).

The source has a genuine clean text layer; per dispatch instruction, Vision Reading Confidence is
`n/a` throughout and Transcription Confidence is `n/a` throughout (reference-book extraction). No
handwritten marginalia was present — every mark on every page in this range is clearly typeset body
text or the sidebar section-navigation list, consistent across all 24 pages. Per dispatch instruction,
Attested Era is set to "contemporary (source published 2010)" throughout and Attested Region to
"American English (United States)" throughout.

**Mojibake gotcha, confirmed again in this chunk, exactly as flagged in the dispatch and consistent
with pt01's findings.** This range is especially dense with the pattern because three of its five
languages (Italian, Norwegian, Polish) are illustrated with native-orthography example sentences
carrying diacritics or non-ASCII punctuation. All instances below were cross-checked directly against
`pdftotext -layout` output of the same page range (not vision-reading alone) and against known,
dictionary-standard word forms in the language being illustrated:

- `Ã¨` → **è** (`Questo non Ã¨ proprio possibile` → "Questo non è proprio possibile," §11.52 Italian
  dialogue example)
- `Ã²` → **ò** (`annunziÃ²` → "annunziò," §11.52 Italian dialogue example)
- `Â«` → **«** (opening guillemet, §11.52); the **closing guillemet renders as a literal `>>`** rather
  than legible mojibake — the exact same asymmetric pattern pt01 already flagged for this chapter's
  `Â« >>` case at §11.4, now recurring at §11.52. Read with the same confidence level: clear from
  context (the sentence is explicitly introduced as a guillemet-quoted example) but noted as an
  interpretive repair rather than a clean 1:1 byte decode.
- `Ã…`/`Ã¥` → **Å**/**å**, `Ã†`/`Ã¦` → **Æ**/**æ**, `Ã˜`/`Ã¸` → **Ø**/**ø** (§11.66, Norwegian special
  characters — the full set decodes cleanly and matches the standard Norwegian/Danish extra-letter
  set exactly, a strong independent confirmation)
- `Å„` → **ń** (not a 2-byte UTF-8-as-Latin-1 case like the others — this is the 2-byte UTF-8 encoding
  of U+0144 "ń" (n with acute) misread one byte as Latin-1 and the other as cp1252, producing the
  "Å" + "„" split; recoverable with full confidence because `PaÅ„stwo` is unambiguously the standard
  Polish word **Państwo**, §11.67)
- `Ã³` → **ó** (`TwÃ³j` → "Twój," §11.67 Polish example, "your")
- `Ä™` → **ę** (`CiÄ™` → "Cię," §11.67 Polish example, "you" accusative)

All vocabulary-table rows and grammar-point prose below reflect the corrected forms; none of the
garbled forms is reproduced as if authoritative.

---

## Vocabulary

CMOS is a style/usage reference, not a vocabulary-teaching text. This chunk's "vocabulary" is
overwhelmingly the publishing/typographic terminology CMOS uses to describe word-division and
special-character rules, which recur structurally across every language subsection in this part of
the chapter (word division, special characters) rather than new conceptual terms per language. All
entries below: Attested Era `contemporary (source published 2010)`, Attested Region `American English
(United States)`, Source Type `grammar_reference`, Transcription Confidence `n/a`, Vision Reading
Confidence `n/a`, unless noted.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| word division | the set of rules governing where a word may legally be broken at a line-end hyphen; this chunk's organizing recurring concept | noun phrase | technical.publishing | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §§11.45–11.47, 11.55–11.57, 11.60–11.63, 11.68; the general cross-language principles were already captured at §11.11 in pt01 — this chunk's entries are the language-specific applications |
| special characters | the diacritic letters, ligatures, or non-ASCII marks a given language's orthography requires beyond unmodified Latin letters | noun phrase | technical.publishing | — | contemporary (source published 2010) | American English (United States) | transnational | grammar_reference | n/a | n/a | §§11.48, 11.50, 11.58, 11.64, 11.66; applies the general concept already captured at §11.12 in pt01 to German, Hungarian, Italian, Latin, and Norwegian in turn |
| eszett / sharp s (ß) | the German letter representing a voiceless alveolar sibilant historically distinct from double-s, used only in roman (not old Gothic/Fraktur) typesetting | noun | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.48; explicitly distinguished from the visually similar Greek beta (β); replaced by *ss* for certain words under the post-1998 spelling reform, and rarely used at all in Swiss German |
| umlaut (umlauted vowel) | a diacritic mark (two dots) over a, o, or u in German, indicating a distinct vowel sound; also the general linguistic term for the vowel-shift phenomenon it marks | noun | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.48; CMOS notes the older convention of substituting an added *e* (ae, oe, ue) for an unavailable umlaut character is now unnecessary given modern text-editing software |
| guillemets (virgolette a caporale) | the angled quotation marks (« ») used in Italian, as in French, to mark quoted matter | noun | technical.publishing | — | contemporary (source published 2010) | American English (United States) | transnational | grammar_reference | n/a | n/a | §11.52; Italian usage differs from French in usually omitting the space between the guillemets and the quoted text |
| scare quotes | quotation marks used to signal a word or phrase is being used ironically, loosely, or with reservation rather than as a direct quotation | noun phrase | technical.publishing | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.52; cross-referenced to §7.55; noted as a secondary use regular quotation marks can carry even within Italian text that otherwise uses guillemets for true quotation |
| suspension points | a run of (typically three) dots indicating an interruption or trailing-off in thought, as distinct from an ellipsis marking omitted material | noun phrase | technical.publishing | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.54; Italian usage parallels French; Chicago's house style spaces the dots in English-language publications even though Italian typographic convention leaves them unspaced |
| grave accent | a diacritic mark (`) over a vowel, used in Italian chiefly to mark stress on a word's final syllable | noun phrase | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.58; CMOS notes it must be retained on a capitalized stressed final vowel even though it is sometimes dropped elsewhere on capitals, since dropping it can create real ambiguity (e.g. CANTÒ "he sang" vs. CANTO "I sing") |
| macron | a diacritic mark (a flat bar) placed over a vowel to indicate it is phonetically long | noun | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | transnational | grammar_reference | n/a | n/a | §11.64; used in elementary Latin pedagogical texts, though CMOS notes ordinary Latin copy requires no special characters at all |
| breve | a diacritic mark (a curved symbol) placed over a vowel to indicate it is phonetically short, used less commonly than the macron in elementary Latin texts | noun | technical.linguistics | — | contemporary (source published 2010) | American English (United States) | transnational | grammar_reference | n/a | n/a | §11.64 |
| sentence style (titles, Latin) | capitalizing only the first word, proper nouns, and proper adjectives of a title — Chicago's rule for ancient/medieval Latin work titles | adjective (compound) | technical.publishing | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.59; the same general concept already captured at §11.3 in pt01, here applied specifically to distinguish ancient/medieval from Renaissance/modern Latin titles |
| headline style (titles, Latin) | capitalizing most words of a title, as in an English headline — Chicago's rule for Renaissance/modern Latin work titles or Latin titles of English works | adjective (compound) | technical.publishing | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §11.59; CMOS's fallback instruction when a title's era is genuinely uncertain is to default to sentence style instead |
| Państwo | the Polish formal second-person-plural address pronoun ("you," formal), capitalized when used this way; also the ordinary noun meaning "state" or (as a form of address) "Mr. and Mrs." | pronoun | formal | — | contemporary (source published 2010) | American English (United States); regional note: Polish-language convention | national | grammar_reference | n/a | n/a | §11.67; see mojibake note above (`PaÅ„stwo` → `Państwo`); illustrates a case where a foreign-language pronoun's capitalization rule diverges from the general §11.9 default of lowercasing pronouns outside English |

## Grammar points

### German word division — vowels (§11.45)

German divides words after a vowel wherever possible (e.g., *Fa-brik*, *hü-ten*, *Bu-ße*). Two vowels
forming a single sound (a diphthong) are never broken (e.g., *Lau-ne*, *blei-ben*).

### German word division — consonants (§11.46)

Two or more adjacent consonants — whether identical or different — are divided before the last one,
unless they belong to different parts of a compound word (e.g., *klir-ren*, *Was-ser*, *Verwand-te*,
*Meis-ter*, but *Morgen-stern*, where the break falls at the compound boundary rather than following
the general rule). The consonant combinations *ch*, *ck*, *ph*, *sch*, and *th* are treated as
indivisible units unless they genuinely belong to separate syllables (e.g., *Mäd-chen*, *Zu-cker*,
*Philo-so-phie*, *rau-schen*, but *Klapp-hut*, *Häus-chen*, where the combination spans a
morpheme/compound boundary and is broken). A historical footnote: before Germany's 1998 spelling
reform, *st* was also subject to the never-divided rule, and the combination *ck* used to be changed
to *kk* and divided between the two k's at a line break — both conventions since retired.

### German word division — compounds (§11.47)

Compound words should be divided between their component elements whenever possible (e.g.,
*Meeres-ufer*, *mit-einander*, *Rasier-apparat*, *Tür-angel*) — the governing principle behind the
"but" exceptions already noted in §11.46 above.

### German special characters (§11.48)

For setting German in roman type (Gothic/Fraktur type being long obsolete), three umlauted vowels
(Ä/ä, Ö/ö, Ü/ü) and the eszett/sharp s (ß) are needed. Omitting the umlaut accent and adding an *e*
instead (*ae*, *oe*, *ue*) is an older convention now unnecessary given standard text-editing
software's umlaut support. The eszett must never be confused with or replaced by the visually similar
Greek beta (β); under Germany's post-1998 spelling reform it is replaced by *ss* in certain words
(readers should consult a German dictionary published after 1998 for which), and in Swiss German
orthography the eszett is rarely used at all, *ss* standing in its place generally.

### Hungarian capitalization (§11.49)

A pure cross-reference stub: "See 11.3, 11.9." No independent Hungarian-specific capitalization rule
is given in this section.

### Hungarian special characters (§11.50)

Hungarian requires several varieties of accented vowels: Á/á, É/é, Í/í, Ó/ó, Ö/ö, Ő/ő, Ú/ú, Ü/ü, and
Ű/ű — notably including the double-acute-accent forms Ő/ő and Ű/ű, which mark long front-rounded
vowels and are distinct from the umlauted Ö/ö and Ü/ü.

### Italian capitalization (§11.51)

Beyond the general cross-reference (§§11.3, 11.9), Italian-specific practice is that a title preceding
a proper name is normally lowercased (e.g., *il commendatore Ugo Emiliano*, *la signora Rossi*).
However, in commercial correspondence the formal second-person pronouns are capitalized in all their
forms: nominative *Lei* (singular) and *Voi* (plural); objective *La* (accusative singular), *Le*
(dative singular), and *Vi* (accusative/dative plural); and the older forms *Ella*/*Le*/*La* and
*Loro*/*Loro*/*Loro*. This capitalization is retained even when the pronoun is suffixed onto a verb in
a combined form (e.g., *Posso pregarLa di farmi una cortesia?* — "May I ask you a favor?"; *Vorrei
darLe una spiegazione* — "I would like to give you an explanation").

### Italian quotations and dialogue (§11.52)

Italian uses guillemets (*virgolette a caporale*, « ») for quoted matter, conventionally without the
space between the guillemets and the quoted text that French typography often includes. Regular
(English-style) quotation marks are also common in Italian, sometimes functioning as scare quotes
within the same text that uses guillemets for true quotations — the closing period is correctly placed
*after* the closing guillemet. In dialogue, em dashes are sometimes used as in French: a dash
introduces each successive speaker's line, and (unlike French practice) a second dash closes the
speech if further narrative matter follows within the same paragraph. Chicago notes the spaces that
typically surround these dashes in Italian-language texts need not be carried over into English-context
usage.

### Italian apostrophes (§11.53)

An apostrophe marks an elided letter. A space follows an apostrophe that itself follows a vowel (e.g.,
*po' duro*, *de' malevoli*), but no space follows one that follows a consonant (e.g., *l'onda*,
*all'aura*).

### Italian suspension points and ellipses (§11.54)

Like French, Italian uses suspension points to mark an interruption or trailing-off in thought; an
actual ellipsis (omitted material) is instead marked with the dots enclosed in brackets. Although
Italian typographic convention leaves the dots unspaced, Chicago's house recommendation for
English-language publications is to space them regardless (cross-referenced to the manual's general
ellipsis guidance at §§13.48–56).

### Italian word division — vowels (§11.55)

Italian divides words after a vowel wherever possible, avoiding one-letter syllables at a line's start
or end (e.g., *acro-po-li*, not *a-cropoli*; *mi-se-ra-bi-le*; *ta-vo-li-no*). Consecutive vowels are
rarely divided, and two vowels forming a single sound (a diphthong) are never divided (e.g., *miei*,
*pia-ga*, *Gio-van-ni*, *Giu-sep-pe*, *pau-sa*, *gio-iel-lo*).

### Italian word division — consonants (§11.56)

Certain consonant groups must never be broken: *ch*, *gh*, *gli*, *gn*, *qu*, *sc*, and an *r* or *l*
preceded by any consonant other than itself (e.g., *ac-qua-rio*, *fi-glio*, *la-ghi*, *na-sce*,
*pa-dre*, *rau-che*, *ri-flet-te-re*, *so-gna-re*). Three groups, by contrast, may be divided: double
consonants, the group *cqu*, and any group beginning with *l*, *m*, *n*, or *r* (e.g., *bab-bo*,
*af-fre-schi*, *ac-qua*, *cal-do*, *cam-po*, *com-pra*, *den-tro*, *par-te*).

### Italian word division — words containing apostrophes (§11.57)

Division should never be made immediately after an apostrophe (an exception to the vowel-division
default at §11.55, though §11.53's apostrophe-spacing rule still governs the apostrophe itself):
*dal-l'accusa*, *del-l'or-ga-no*, *quel-l'uomo*, *un'ar-te*, *l'i-dea*.

### Italian special characters (§11.58)

Italian requires six accented vowel pairs: À/à, È/è, É/é, Ì/ì, Ò/ò, Ù/ù. Although the grave accent on
a capitalized vowel is sometimes dropped, it must be retained on a stressed final syllable to avoid
genuine ambiguity — e.g., CANTÒ ("he sang") versus CANTO ("I sing"), or PAPÀ ("daddy") versus PAPA
("pope"). When an accented capital letter is genuinely unavailable, an apostrophe may substitute for
the accent on a stressed final (or single) vowel instead — e.g., *E'* ("it is") as distinct from *E*
("and"), or *PAPA'* ("daddy").

### Latin capitalization — titles of works (§11.59)

In English-speaking countries, titles of ancient and medieval Latin works are capitalized sentence
style — only the title/subtitle's first word, proper nouns, and proper adjectives (e.g., *De bello
Gallico*, *De viris illustribus*, *Cur Deus homo?*). Renaissance and modern Latin-titled works, or
Latin titles of English-language works, are instead usually capitalized headline style, following
ordinary English title conventions (e.g., *Novum Organum*, *Religio Medici*). When a title's era is
genuinely ambiguous, CMOS directs the author to default to sentence style.

### Latin word division — syllables (§11.60)

A Latin word has as many syllables as it has vowels or diphthongs (*ae*, *au*, *ei*, *eu*, *oe*, *ui*,
and, in archaic Latin, *ai*, *oi*, *ou*), and should be divided between syllables (e.g., *na-tu-ra*,
*cae-li-co-la*, *in-no-cu-us*).

### Latin word division — single consonants (§11.61)

When a single consonant falls between two vowels, the word divides before the consonant unless that
consonant is *x* (e.g., *Cae-sar*, *me-ri-di-es*, *in-iu-ri-or* or *in-ju-ri-or*, but *lex-is*). Note
that *i* and *u* sometimes function as consonants in Latin and, when they do, are sometimes written as
*j* and *v* instead.

### Latin word division — multiple consonants (§11.62)

When two or more consonants come together, division generally falls before the last consonant (e.g.,
*om-nis*, *cunc-tus*), with several named exceptions. The combinations *ch*, *gu*, *ph*, *qu*, and
*th* are treated as single, indivisible consonants (e.g., *co-phi-nus*, *lin-gua*, *ae-qua-lis*). A
further list of consonant groups is never broken at all: *bl*, *br*, *chl*, *chr*, *cl*, *cr*, *dl*,
*dr*, *gl*, *gr*, *phl*, *phr*, *pl*, *pr*, *thl*, *thr*, *tl*, and *tr* (e.g., *pan-chres-tus*,
*li-bris*, *ex-em-pla*, *pa-tris*).

### Latin word division — compounds (§11.63)

Compound words are first separated into their component elements; the foregoing single- and
multiple-consonant rules then apply within each element separately (e.g., *ab-rum-po*, *ad-est*,
*red-eo*, *trans-igo*).

### Latin special characters (§11.64)

Latin requires no special characters for setting ordinary copy. Elementary pedagogical texts, however,
conventionally mark long vowels with a macron and, less often, short vowels with a breve: Ā/ā, Ă/ă,
Ē/ē, Ĕ/ĕ, Ī/ī, Ĭ/ĭ, Ō/ō, Ŏ/ŏ, Ū/ū, Ŭ/ŭ.

### Norwegian capitalization (§11.65)

Beyond the general cross-reference (§§11.3, 11.9), Norwegian-specific practice capitalizes the polite
personal pronouns *De*, *Dem*, and *Deres* — though CMOS notes this usage is becoming ever rarer. Until
the mid-twentieth century, common nouns were also capitalized in Norwegian, as in German, but this is
no longer current practice.

### Norwegian special characters (§11.66)

Norwegian requires the same special characters as Danish: Å/å, Æ/æ, and Ø/ø — see mojibake note above
for the decode.

### Polish capitalization (§11.67)

Beyond the general cross-reference (§§11.3, 11.9), Polish-specific practice capitalizes the formal
second-person-plural address pronoun *Państwo* ("you") and related forms when used this way (e.g.,
*Czekam na Twój przyjazd* — "I await your arrival"; *Pozdrawiam Cię!* — "Greetings to you!" — the
second example actually illustrates the informal singular *Cię*, included alongside the formal-address
rule as the chapter's second Polish example sentence). See mojibake note above for the decode of this
section's three garbled forms.

### Polish word division (§11.68)

Division of Polish words resembles that of transliterated Russian (cross-referenced to §§11.118–28,
outside this chunk's range) and normally follows syllabic structure (e.g., *kom-pli-ka-cja*,
*sta-ro-pol-ski*). One print-specific nicety: the conjunction *i* ("and") should never appear at the
end of a line and must instead carry over to the start of the next — a rule CMOS notes need not be
maintained in electronic publications (e.g., by inserting a nonbreaking space after every instance of
*i* to prevent it from ever falling at a line break).

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes, dialogue
blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`.
