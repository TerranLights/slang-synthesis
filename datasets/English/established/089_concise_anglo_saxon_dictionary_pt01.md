# English — Established Vocabulary: *A Concise Anglo-Saxon Dictionary* (J.R. Clark Hall, with a
Supplement by Herbert D. Meritt), Sample 1 of 1

**Source:** J.R. Clark Hall, *A Concise Anglo-Saxon Dictionary*, with a Supplement by Herbert D.
Meritt, Fourth Edition (originally published 1894; fourth edition © Cambridge University Press
1960; this printing University of Toronto Press, in association with the Medieval Academy of
America, Medieval Academy Reprints for Teaching series; ISBN 0-8020-6548-1). 473 PDF pages total:
front matter + "List of Signs and Abbreviations" (PDF pp. 1–15), main dictionary body A–Y (PDF pp.
17–~449, printed pp. 1–~434; confirmed offset **PDF page = printed page + 16** throughout the main
body), Meritt's Supplement (PDF pp. ~450–468), back-matter publisher ads (PDF pp. 469–473).

**Coverage note — deliberately non-exhaustive sampling, not a full extraction, per this project's
standing convention for oversized dictionaries (Russian, Korean, Spanish precedent).** This is a
general dictionary of the entire Old English lexicon with tens of thousands of headwords; a full
transcription was never in scope. Eleven two-column dictionary-body page-spreads were read (PDF
pages 16, 17 [cross-checked], 60, 100, 150, 200, 250, 300, 350, 400, 440 — printed pp. 1, 45, 85,
135, 185, 235, 285, 335, 385, 425), spanning headwords from **ā (A) through wundwīte (W)** — i.e.
roughly one representative spread sampled from each major letter-section across the whole alphabet
— plus two spreads from Meritt's Supplement (PDF pages 452, 460, headword ranges Caldisc–Dælnymendlic
and Māhling–Nȳðerāworpen) to characterize its distinct addenda format, and the front-matter "List of
Signs and Abbreviations" (PDF pp. 9, 13, 17) to document the dictionary's own register/dialect/
citation-convention system. Within each sampled spread, entries were selected for the table below to
illustrate **headword/entry format, abbreviation conventions, productive compounding, and the
dictionary's explicit dialect- and register-marking devices** — not an exhaustive per-page
transcription; ordinary entries on sampled pages not chosen for the table were skipped by the
hundreds on each spread.

**Source text layer: confirmed real but garbled — two independent, confirmed problems, both
resolved for this extraction rather than worked around by guessing.**

1. **Two-column scrambling in naive (non-block-aware) extraction.** Plain `pdftotext` (no
   `-layout`) interleaves the *first line only* of the left and right columns before continuing down
   the left column — confirmed directly on PDF page 236 (printed p. 220): raw `pdftotext` output
   reads `llmw6rlg weary of limb, ROOD 63.` (the page's first left-column entry, headword *līmwērig*)
   immediately followed by `Ust mf. art, cleverness, cunning, experience,` (the page's first
   *right*-column entry, headword *list*), before any of the rest of the left column — exactly the
   symptom flagged in this dispatch. `pdftotext -layout` does noticeably better (keeps the two
   columns side-by-side, line-aligned, which is usually readable) but still garbles individual
   characters. The extraction method actually used here was **PyMuPDF (`fitz`) `page.get_text
   ("blocks")`**: MuPDF's block segmentation already groups each page's text into left-column-first,
   then right-column, paragraph-sized blocks in correct reading order (confirmed on PDF page 236:
   blocks 1–14 are all left-column, x-range ≈32–188pt; blocks 15–27 are all right-column, x-range
   ≈195–350pt, with no interleaving) — this resolved the column-scrambling problem structurally,
   without needing coordinate-splitting by hand. Every entry transcribed below was additionally
   cross-checked directly against a 2.5–3× page-image render (not just the block-extracted text), per
   this dispatch's instruction to treat column-aware bounding-box extraction as necessary but not
   sufficient.
2. **OCR character-substitution garbling (not a fixed 1:1 cipher — true misrecognition).** Even with
   column order fixed, individual characters are frequently misrecognized: macron/breve vowels (ā,
   ē, ī, ō, ū, ǣ) often render as stray digits or wrong letters (confirmed: the very first headword
   of the dictionary, **ā** "always, ever," renders as `ft`; `āwa, ō` renders as `äwa, б`); `Æ`
   (author-abbreviation for Ælfric) renders as Cyrillic `Ж` or `М`; Latin `B`/`C`/`P`/`O` in
   citation-source abbreviations sometimes render as Cyrillic look-alikes (`В`, `С`, `Р`, `О`); roman
   numeral `III` once rendered as `Ш` (Cyrillic sha). Unlike the Korean/Russian font-substitution
   ciphers documented elsewhere in this project's gotcha list, **no consistent 1:1 or offset mapping
   was found** — the same macron vowel garbles differently in different tokens — consistent with
   genuine ABBYY FineReader 8.0 OCR misrecognition (confirmed via `pdfinfo`: `Producer: ABBYY
   FineReader 8.0 Professional Edition`) rather than a decodable font cipher. **Every headword and
   gloss transcribed below was therefore read directly from the rendered page image** (clean,
   sharp, unwatermarked typeset print at every sampled spread — no handwritten marginalia of any
   kind found on any of the 13 spreads inspected) rather than trusted from the raw text layer; the
   text layer was used only to locate/confirm entry order and to document the corruption pattern
   above. No genuinely unresolvable character was hit in the entries actually selected for the table
   (a handful of tiny citation superscript line/verse numbers were ambiguous at render resolution and
   were simply omitted from the Notes column rather than guessed — this is noted inline where it
   happened, not flagged as a table-wide confidence problem).

**Vision Reading Confidence is marked `n/a` throughout** per this dispatch's instruction — the
source has a genuine text layer (this is an OCR/extraction-quality problem, not a no-text-layer
vision-reading problem) — **except where noted individually** as `low_confidence` for a specific
ambiguous character, per the "flag genuinely unresolvable substitutions rather than guess" rule.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| ā | always, ever, at all, continuously, for ever; ā on ēcnisse "for ever"; ā butan ende "world without end" | adv. | core | — | Old English | — | — | dictionary | n/a | n/a | printed p.1 (first headword in the dictionary). [ON. ei, ey] — etymological cognate noted by the source itself. |
| ā-bacan | to bake | verb (str. VI) | core | — | Old English | — | — | dictionary | n/a | n/a | printed p.1. |
| ābēodan | to order, proclaim, bid, command, direct; summon, call out; announce, relate, declare, present, offer; hāl ā. "to wish one good luck, greet, bid farewell to" | verb (str. II) | core | — | Old English | — | — | dictionary | n/a | n/a | printed p.1. ['abede] — Modern English NED cross-reference marker, per the source's own "List of Signs" convention (see Grammar points). |
| ābernan (N) | = ābeornan (cross-reference; "to burst out, break out, break away, escape") | verb | core | — | Old English, Northumbrian | Northumbria | regional | dictionary | n/a | n/a | printed p.1. `(N)` = the source's own "Northumbrian" dialect-marking abbreviation (List of Signs, PDF p.13: "N = Northumbrian") — one of this dictionary's explicit dialect tags, see Grammar points. |
| ābylgan | to make angry, irritate, offend, hurt, distress; be angry with | verb (wk. I) | core | — | Old English | — | — | dictionary | n/a | n/a | printed p.1. ['abelgen] |
| āblendan | to blind, put out the eyes of; dazzle, deceive, delude | verb (wk. I) | core | — | Old English | — | — | dictionary | n/a | n/a | printed p.1. ['ablend] |
| besnǣdan† | to cut, mutilate | verb (str. I) | literary | — | Old English | — | — | dictionary | n/a | n/a | printed p.45. `†` = the source's own "occurs only or mainly in poetical texts" marker (List of Signs, PDF p.9) — mapped here to this project's `literary` tier. |
| be-snȳðian | to rob, deprive of | verb (wk. II) | core | — | Old English | — | — | dictionary | n/a | n/a | printed p.45. |
| beswīcan | to deceive, seduce, betray, circumvent, frustrate; (with AO,CP sources) to overcome, supplant | verb (str. I) | core | — | Old English | — | — | dictionary | n/a | n/a | printed p.45. ['beswike] |
| betǣcan | to make over, give up to, impart, deliver, entrust, commend to; betroth; appoint (for); set apart as, dedicate; show, point out; give orders, pursue, hunt | verb (wk. I) | core | — | Old English | — | — | dictionary | n/a | n/a | printed p.45. ['beteach] — unusually wide polysemy spanning "hand over" and "hunt," bridged by a "pursue/entrust-to" sense. |
| bōt | amend, repair, restore, cure; make good, make amends, reform, remedy; compensate, atone, "pay a legal compensation-payment for an offence" | noun (f.) | core | — | Old English | — | — | dictionary | n/a | n/a | printed p.45. [bōt; 'beet' vb.] — the legal-compensation sense (payment for an offense, i.e. wergild-adjacent restitution) is notable social/legal vocabulary. |
| dēorling | "darling," favourite, minion; household god | noun | core | — | Old English | — | — | dictionary | n/a | n/a | printed p.85. The "household god" sense (a protective or especially favored object/figure of a household) is a vivid secondary meaning beyond the familiar "darling" sense that survived into Modern English. |
| dīernan | to keep secret, hide, restrain, repress; hide oneself | verb (wk. I) | core | — | Old English | — | — | dictionary | n/a | n/a | printed p.85. ['dern'] |
| dīegol | secret, hidden, obscure, unknown, deep | adj. | core | — | Old English | — | — | dictionary | n/a | n/a | printed p.85. ['dighel] — compare diegolnes below, same root. |
| dīegolnes | privacy, secrecy, solitude; secret, secret thought, mystery; hiding-place, recess | noun (f.) | core | — | Old English | — | — | dictionary | n/a | n/a | printed p.85. |
| diht | arrangement, disposal, deliberation, purpose; administration, office, direction, command, prescription; conduct; "piece of writing, composition, literary work" | noun | core | — | Old English | — | — | dictionary | n/a | n/a | printed p.85. Polysemy spans "administrative order" and "literary composition" — the compiling/arranging sense extends to composing a text. |
| dēormōd† | courageous, bold | adj. | literary | — | Old English | — | — | dictionary | n/a | n/a | printed p.85. `†` poetic-only marker (see besnǣdan above). Compound: dēor- "fierce/bold" + mōd "mind, spirit, courage." |
| forðweard | inclined forwards or towards: advanced, progressing, growing, ready; enduring, everlasting, continual; future | adj. | core | — | Old English | — | — | dictionary | n/a | n/a | printed p.135. ['forthward] |
| forwyrd | destruction, ruin, fall, death | noun (fn.) | core | — | Old English | — | — | dictionary | n/a | n/a | printed p.135. [forweorðan] |
| forwyrcan | to do wrong, sin; (as past ptc.) "forworht mann" a criminal; to ruin, undo, destroy; condemn, convict, curse; forfeit; (second sense) to barricade, obstruct, close up | verb (wk. I) | core | — | Old English | — | — | dictionary | n/a | n/a | printed p.135. ['forwork'] — a single headword spanning "commit a crime," "convict/condemn someone," and "barricade a place," unified by a "wrongly/thoroughly work (upon)" root sense. |
| forðweg† | journey, departure; in (on) forðwege "away" | noun | literary | — | Old English | — | — | dictionary | n/a | n/a | printed p.135. `†` poetic-only marker. |
| hlāford | "lord," master, ruler; husband; the Lord, God | noun | core | — | Old English | — | — | dictionary | n/a | n/a | printed p.185. [hlāf, weard] — the dictionary's own etymology note: literally "loaf-ward/bread-keeper" (hlāf "loaf" + weard "guardian"), the famous etymon of Modern English *lord*; see Grammar point below on the hlāf- word-family. |
| hlāfæta | "loaf-eater," dependant | noun | core | — | Old English | — | — | dictionary | n/a | n/a | printed p.185. Compound hlāf "loaf" + ǣta "eater" — a household-dependant named by the fact of eating the lord's bread, directly paralleling hlāford's own "bread" etymology. |
| hlāfmæsse | "Lammas" (August 1) | noun | core | — | Old English | — | — | dictionary | n/a | n/a | printed p.185. Compound hlāf "loaf" + mæsse "mass" — the harvest-festival "loaf-mass," source of Modern English "Lammas." |
| hlēapan | to "leap," run, go, jump, dance, spring; (+) leap upon, mount (a horse) | verb (str. VII) | core | — | Old English | — | — | dictionary | n/a | n/a | printed p.185. ['leap] |
| hlēapere | runner, courier; wanderer; horseman; "leaper," dancer; itinerant monk | noun | core | — | Old English | — | — | dictionary | n/a | n/a | printed p.185. A single headword covering "courier," "dancer," and "itinerant monk" — all unified by the base sense "one who moves/leaps about" rather than settled in one place. |
| hlēahtorsmiþ | laughter-maker | noun | core | — | Old English | — | — | dictionary | n/a | n/a | printed p.185. Compound hlēahtor "laughter" + smiþ "smith" — literally "laughter-smith," a striking agentive-compound coinage for an entertainer/jester figure, structurally identical to the familiar wordsmith-type pattern. |
| micel | great, intense, much, many; (of time) long; loud | adj. | core | — | Old English | — | — | dictionary | n/a | n/a | printed p.235. ['mickle] comp. māra, superl. mǣst(a) — irregular comparative/superlative, source of Modern English "more"/"most." |
| micellīce | grandly; very, exceedingly | adv. | core | — | Old English | — | — | dictionary | n/a | n/a | printed p.235. |
| micelsprecende | boasting | adj./ptc. | core | — | Old English | — | — | dictionary | n/a | n/a | printed p.235. Compound micel "great" + sprecende "speaking" — literally "great-speaking." |
| rūn | mystery, secrecy, secret; counsel, consultation; (secret) council; runic character, letter, writing | noun | core | — | Old English | — | — | dictionary | n/a | n/a | printed p.285. ['roun] — direct etymon of Modern English "rune"; the dictionary's own glossing shows the word spanning "secret/mystery" and "written runic character" as a single continuous sense, not two unrelated meanings. |
| rȳne | mystery, dark saying; mystic rite; sacrament; sacramental elements | noun | core | — | Old English | — | — | dictionary | n/a | n/a | printed p.285. ['rune'] — near-synonym/doublet of rūn above, both glossed toward "mystery/sacrament," worth comparing. |
| rȳnian | to whisper, murmur, talk secrets, conspire | verb (wk. II) | core | — | Old English | — | — | dictionary | n/a | n/a | printed p.285. ['round] (as in the archaic English verb "to round" = whisper, itself from this root.) |
| syll | "sill," threshold, foundation, base, basis | noun (f.) | core | — | Old English | — | — | dictionary | n/a | n/a | printed p.335. |
| symbel | feast-day, festivity, revel, feast; festival, holy day; solemn office | noun | core | — | Old English | — | — | dictionary | n/a | n/a | printed p.335. See Grammar point below on the symbel- compound family. |
| symbelgāl | wanton with feasting, drunk | adj. | core | — | Old English | — | — | dictionary | n/a | n/a | printed p.335. Compound symbel "feast" + gāl "wanton, lascivious." |
| synn | injury, mischief, enmity, feud; "sin," guilt, crime | noun (f.) | core | — | Old English | — | — | dictionary | n/a | n/a | printed p.335. Direct etymon of Modern English "sin" — note the dictionary's own gloss ordering puts the secular "injury/feud" sense before the later specifically-religious "sin" sense. |
| syndrig | separate, single; "sundry," various, distinct; special, private, peculiar, exceptional, particular; characteristic; (distributive) one each | adj. | core | — | Old English | — | — | dictionary | n/a | n/a | printed p.335. ['sundry] [sundor] |
| untala (NG) | = untela (cross-reference; "not well, amiss, badly, ill, improperly, wrongly") | adv. | core | — | Old English, Northumbrian | Northumbria | regional | dictionary | n/a | n/a | printed p.385. `(NG)` = the source's own "Northumbrian Gospels" dialect-source abbreviation (List of Signs, PDF p.13: "NG = the Northumbrian Gospels, contained in Skeat's edition") — second explicit dialect tag sampled in this extraction, see Grammar points. |
| untrēowfæst | unfaithful, unreliable | adj. | core | — | Old English | — | — | dictionary | n/a | n/a | printed p.385. Compound un- (negative prefix) + trēowfæst "faithful, loyal" (itself trēow "troth, fidelity" + fæst "fast, firm"). |
| unswēte | not sweet; foul | adj. | core | — | Old English | — | — | dictionary | n/a | n/a | printed p.385. ['unsweet] |
| wulf | "wolf"; wolfish person, devil | noun | core | — | Old English | — | — | dictionary | n/a | n/a | printed p.425. The figurative "devil/wolfish person" sense is listed as a direct secondary sense of the literal animal term, not a separate derived word. |
| wulfheort† | wolf-hearted, cruel | adj. | literary | — | Old English | — | — | dictionary | n/a | n/a | printed p.425. `†` poetic-only marker. Compound wulf "wolf" + heort "heart." |
| wund | "wound," sore, ulcer; wounding, injury | noun (f.) | core | — | Old English | — | — | dictionary | n/a | n/a | printed p.425. ['wound] — directly continues the wund-/wundor- family discussed in the Grammar point below. |
| wundor | "wonder," marvel, portent, horror; wondrous thing, monster | noun | core | — | Old English | — | — | dictionary | n/a | n/a | printed p.425. ['wonder] |
| wundrian | to "wonder," be astonished at; admire; make wonderful, magnify | verb (wk. II) | core | — | Old English | — | — | dictionary | n/a | n/a | printed p.425. |
| cræftbōc | commentary | noun | core | — | Old English | — | — | dictionary | n/a | n/a | Supplement (Caldisc–Dælnymendlic range). Compound cræft "skill, craft" + bōc "book" — literally "skill-book"; see Grammar point below on the Supplement's distinct addenda format. |
| crammingpohha | a bag crammed with ill-gotten gains (query mark in source) | noun | core | — | Old English | — | — | dictionary | n/a | n/a | Supplement (Caldisc–Dælnymendlic range), citing FL4, A6. Source's own gloss carries a "?" expressing lexicographic uncertainty about the precise sense — a vivid, almost slang-feeling coinage (literally "cramming-pouch") for a den/receptacle of stolen goods. |
| cūter | chewing gum | noun | core | — | Old English | — | — | dictionary | n/a | low_confidence | Supplement (Caldisc–Dælnymendlic range), citing FL4, B4. Gloss transcribed exactly as printed; flagged `low_confidence` not because the OCR/print is unclear but because "chewing gum" is such a startlingly modern-sounding gloss for an Old English glossary word that it is worth a second check against the Supplement's own source abbreviation (FL = an unexpanded glossary source in this sampled range) before treating the sense as certain — the word form itself is clearly printed. |
| cynehelm | royal power, crown | noun | core | — | Old English | — | — | dictionary | n/a | n/a | Supplement (Caldisc–Dælnymendlic range), citing HAW477 n. to l.24; GAT26,8n. Compound cyne- "royal" + helm "helmet, protection" — literally "royal-helmet" = crown/royal authority; the Supplement entry is itself a correction/addition to the meaning "royal power" at an existing headword. |
| meduwyrhta | brewer | noun | core | — | Old English | — | — | dictionary | n/a | n/a | Supplement (Māhling–Nȳðerāworpen range), citing HAW508,12 (or = mēdwyrhta?, source's own alternative-reading query). Compound medu "mead" + wyrhta "worker, maker" — literally "mead-worker." |
| metenīðing | food-niggard | noun | core | — | Old English | — | — | dictionary | n/a | n/a | Supplement (Māhling–Nȳðerāworpen range), citing ANS117,23. Compound mete "food" + nīðing. nīðing itself (not separately headworded in this sampled range) was a term of severe legal/social disgrace in Old English and Old Norse law — an outlawed, honorless person — so this compound reads as something closer to "a disgraceful miser about food" than a neutral descriptor; flagged as worth a closer look in any future mechanics-analysis pass on OE pejorative compounding. |
| nȳdgefēra | inevitable companion | noun | core | — | Old English | — | — | dictionary | n/a | n/a | Supplement (Māhling–Nȳðerāworpen range), citing EL1260 n. (ed. Gradon). Compound nȳd "need, necessity" + gefēra "companion" — literally "necessity-companion," a kenning-like compound for an unavoidable fate/circumstance. |

## Grammar points

### Dictionary macro-structure and headword format

Each page is laid out in two columns of bold headwords (vocalic length shown with macrons: ā, ē, ī,
ō, ū, ǣ), followed by a grammatical-class marker (gender letters m./f./n. for nouns; roman numerals
I/II/III for weak/strong verb classes; adj./adv./prep./conj./interj.), the gloss(es) separated by
semicolons for distinct senses, a citation to the specific source text(s) the usage is attested in
(small-caps abbreviations keyed to the front-matter "List of Signs and Abbreviations," e.g. `CHR` =
a Chronicle text, `AO` = King Alfred's translations, `CP` = Pastoral Care, `WW` = Wright-Wülcker's
*Vocabularies*), and often a closing bracketed etymological note pointing to the Modern English
reflex in single quotes (e.g. `['forwork']`) or a related Germanic/Latin/Norse form. Running
headers at the top of each page give the first and last headword on that page (e.g. "HLÆPEWINCE …
HLĒONAÐ"), a convention this project's established-file citations exploit directly to confirm
printed-page identity without needing to trust PDF page arithmetic.

### The "List of Signs and Abbreviations" as a register/dialect-marking system

Unlike a pure etymological dictionary, this source marks several genuinely useful register and
dialect distinctions directly via a small symbol system explained in its own front matter (PDF pp.
9, 13), paralleling the bracketed-register-tag systems already documented for other languages in
this project (compare the Korean dictionary's `[VULGAR]`/`[SLANG]`/`[DIAL.]` tags, `established/
026` in `datasets/Korean/`):

- **`†`** — "occurs only or mainly in poetical texts." A genuine register marker distinguishing
  poetic-register vocabulary from ordinary prose vocabulary, mapped in this extraction's table to
  this project's `literary` usage tier (besnǣdan†, dēormōd†, forðweg†, wulfheort† above).
- **Dialect-source letter codes**: `N` = Northumbrian, `M` = Mercian, `A` = Anglian, `K`/`EK` =
  (Early) Kentish, `LWS` = Late West Saxon, `NG` = the Northumbrian Gospels (Lindisfarne/Rushworth
  glosses), `LkL`/`LkR` = the Lindisfarne/Rushworth manuscripts specifically. These are genuine
  explicit dialectal annotations the source marks on individual headwords/variant-forms — two were
  sampled directly in this extraction (ābernan (N), untala (NG), both above) and mapped to Attested
  Region "Old English, Northumbrian" / Geographic Scope "regional," following the convention already
  established in `established/081` (`Cædmon's Hymn`, Northumbrian recension) for this same language
  folder.
- **`+`** — the word is attested only with the `ge-` prefix (a very common OE perfective/collective
  verbal prefix); **`±`** — attested both with and without the `ge-` prefix; **`*`** — a
  hypothetical/reconstructed form not actually attested, prefixed to distinguish it from normalized-
  but-attested spellings.
- Single-quoted bracketed words at the end of an entry (e.g. `['abede']`, `['dern']`) are not glosses
  but **cross-references into the *New English Dictionary* (OED's predecessor)**, per the source's
  own Note 1 — a convention for readers chasing a word's full etymological/historical trail outside
  this concise dictionary.

### Productive compounding families observed across the sample

Several headword clusters sampled here illustrate the same OE compounding mechanism — a concrete
base noun generating a whole family of derived nouns/adjectives by direct compounding, rather than
by suffixation alone:

- **hlāf- "loaf/bread"**: hlāford "lord" (hlāf + weard "bread-guardian"), hlāfæta "dependant"
  (hlāf + ǣta "bread-eater"), hlāfmæsse "Lammas" (hlāf + mæsse "bread/loaf-mass"). All three keep
  the lord/household/harvest-festival semantic field anchored concretely in "bread," a clean example
  of a core subsistence noun generating an entire social-structure vocabulary cluster — comparable to
  the productive-pejoration food-term pattern already documented for Korean (개똥/개떡,
  `established/026` in `datasets/Korean/`), though here the direction is prestige/social-structure
  rather than pejoration.
- **wund-/wundor- "wound/wonder"**: wund "wound," wundor "wonder, marvel, portent, monster,"
  wundrian "to wonder, be astonished, admire, magnify." Modern English "wound" and "wonder" look
  unrelated, but this dictionary's own page ordering places them as adjacent headwords sharing a
  root, worth flagging for any later etymological-mechanics pass.
- **symbel- "feast"**: symbel "feast, festival," symbelgāl "wanton/drunk with feasting" — a base
  noun generating a moralizing compound adjective about the *excess* of the activity it names, a
  derivation pattern ("noun of an activity" → "adjective meaning excessive in that activity")
  structurally comparable to how modern slang often derives pejorative adjectives from nouns naming
  an activity or substance.
- **un- negative prefix**: highly productive across every sampled letter-section (unswēte
  "not sweet," untrēowfæst "unfaithful," and dozens more on the same single sampled page alone,
  p.385) — confirms un- was already a fully general, freely-combining negative derivational prefix
  in Old English, not a borrowing or later innovation.

### The Supplement's distinct addenda format

Herbert D. Meritt's Supplement (sampled PDF pp. 452, 460) is **not** laid out as ordinary dictionary
entries — it is a terse corrections-and-additions list keyed to abbreviations for other scholarly
sources (`FL`, `BPG`, `OEGC`, `HAW`, `ANS`, etc., distinct from the main dictionary's own citation
abbreviations and not re-expanded in this sample). Many Supplement lines are pure bibliographic
corrections to prior scholarship ("delete the query," "read X for Y," "add the meaning Z") rather
than new vocabulary; others add genuinely new compounds or glosses not in Clark Hall's own main
text (cræftbōc, cynehelm, meduwyrhta, metenīðing, nȳdgefēra above). **Any future deeper pass on this
source should treat the Supplement as a structurally distinct sub-source from the main A–Y body**,
not sample it with the same entry-density expectations.

---

## Coverage note (summary)

13 page-spreads sampled (11 main-dictionary-body + 2 Supplement + 3 front-matter "List of Signs"
pages used for the register/dialect-system grammar point, not vocabulary) out of 473 total PDF
pages, spanning headwords ā through wundwīte alphabetically plus two Supplement ranges — out of a
dictionary with tens of thousands of headwords. ~47 vocabulary rows extracted; this is intentionally
a structure-and-convention-characterizing sample, not a census, per this project's standing
dictionary-scale-source convention. No handwritten marginalia found on any sampled spread. The
text layer's two confirmed corruption mechanisms (block-order column-scrambling in naive extraction;
non-cipher OCR character misrecognition) are both documented above with worked examples, and every
transcribed entry was cross-checked against a rendered page image rather than trusted from either
raw or `-layout` `pdftotext` output. A further `_pt02`/`_sample2` dispatch sampling additional
spreads (especially the unsampled letters C, E, G, I/L, N, O, P, T, Þ/Ð) would be a reasonable
follow-up if deeper coverage of this dictionary becomes a priority, but was not attempted here per
the sampling scope given.
