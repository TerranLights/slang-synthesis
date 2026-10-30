# Korean — Established Historical-Linguistics Extraction: *A History of the Korean Language* (Part 1 of 2)

**Source:** Ki-Moon Lee & S. Robert Ramsey, *A History of the Korean Language* (Cambridge University
Press, 2011), 348 pp. — the first English-language monograph on the subject. This file (Part 1 of 2;
Part 2 is `053_history_of_korean_language_part2.md`) covers the **Introduction** and **Chapters 1–5.3**
(printed pp. 1–168, PDF pp. 13–180 of the source PDF): Origins (genetic hypotheses: Altaic, Japanese),
The Formation of Korean (Old Chosŏn, Puyŏ/Hán, the Three Kingdoms), Old Korean (Silla-based, pre-Hangul),
Early Middle Korean (Koryŏ period), and the opening of Late Middle Korean (sources, the invention of the
Hangul alphabet, and its phonology). Part 2 continues with Late Middle Korean's morphology/syntax/
vocabulary, Early Modern Korean, and Contemporary Korean.

**Why this source, and how it differs from every other Korean `established/` file.** All 46 prior
Korean extractions are synchronic teaching grammars, dictionaries, or usage/register guides. This is
the project's first genuinely **diachronic historical-linguistics** source for Korean: its subject is
sound change, script history, and the staged reconstruction of Old → Early Middle → Late Middle → Early
Modern → Contemporary Korean, not how to use the modern language. Confirmed non-overlapping with all 46
prior files by grepping for historical-linguistics terminology (Hunminjeongeum, idu, hyangga, Old/Middle
Korean, Altaic, Sino-Korean etc.) before this dispatch began — zero hits. The one partial exception is
Chapter 7 ("Contemporary Korean," in Part 2), which touches North/South Korean divergence also covered
pedagogically by `033_lets_learn_korean_northern_dialect.md` — that chapter's own extraction documents
exactly what was checked against 033 and kept as non-redundant.

**How "Vocabulary" and "Grammar points" map onto an academic diachronic source.** Per the extraction
spec's allowance for academic sources, most of this book's real content is historical-linguistic
*argumentation* (sound-correspondence tables, script-design rationale, dated sound-change evidence)
rather than a pedagogical word list. Each chapter section below therefore has a "Grammar points"
section that is the historical-linguistics analog of a conjugation rule — periodization, transcription-
system history, genetic-hypothesis methodology, letter-design rationale, named sound changes — and a
"Vocabulary" table pulling in every reconstructed/attested lexical form the authors actually cite as
evidence, each tagged with a *concrete* Attested Era and (where the source specifies it) Attested
Region/kingdom, since that attribution is this book's entire analytical point rather than incidental
detail. Nearly every vocabulary-table entry is therefore `archaic` register with `—` frequency: these
are historically-attested forms, not synchronic usage data.

**Extraction method.** Produced by eleven parallel chunk-dispatches (one per chapter/sub-chapter range,
each checked first for an existing file before writing, each writing to a scratch-only path), then
merged, verified, and written to this pair of established/ files by a single top-level orchestrator —
no sibling dispatch wrote directly to any established/ path. Section numbering below follows the
source book's own chapter/section numbers (§1.1, §2.1, §3.1, etc.) for easy cross-reference back to the
original PDF.

**Known extraction-quality caveats (apply throughout both parts of this file; flagged per-row where
they bite, not just here):**
- **Hangul syllable/jamo gaps.** `pdftotext` has a clean, genuine text layer throughout this PDF — no
  font-substitution cipher, no vision-reading needed anywhere in the book. However, a handful of
  multi-syllable Hangul headwords (especially in dense comparative word lists) lose one internal
  syllable block in extraction, and several **archaic/obsolete jamo** no longer used in modern Korean
  (ㆍ arae-a, ㅿ semi-voiced s, ㅸ bilabial fricative w, and a few rare pitch-accent diacritics) are
  missing from the PDF's embedded font and render as a dropped/blank glyph rather than a wrong one —
  a font-coverage gap, not a substitution cipher to decode. Wherever this occurs, the **Yale
  romanization is complete and used as the authoritative `Term` form**; the accompanying Hangul is
  reproduced exactly as extracted (gap intact, never guess-filled), flagged "Hangul gap" in the Notes
  column of the specific rows affected.
- **Pitch/tone-marking diacritics.** The Late Middle Korean phonology sections (§5.3, within this
  file) discuss a historical pitch-accent system marked in the original by diacritic "side dots" to
  the left of a syllable; a handful of these combining marks and a few rare Hangul jamo combinations
  did not survive `pdftotext` extraction cleanly. Page citations are preserved throughout so any
  specific passage can be checked against the primary PDF if exact diacritic placement matters later
  — treat this file as a finding aid, per this project's standing extracted-summary-vs-primary-source
  principle, not the final word on exact historical pitch notation.
- No handwritten marginalia of any kind was found anywhere in this source — it is a clean, professionally
  typeset academic monograph throughout.

---

## Korean — Established Vocabulary/Grammar: Introduction + Chapter 1 "Origins"

**Source:** Ki-Moon Lee & S. Robert Ramsey, *A History of the Korean Language* (Cambridge University
Press, 2011), printed pp. 1–30 (Introduction, pp. 1–12; Chapter 1 "Origins," pp. 13–30: 1.1 Genetic
hypotheses, 1.2 Altaic, 1.3 Japanese, 1.4 Toward history).

**Coverage note:** This is a diachronic historical-linguistics monograph, not a synchronic teaching
grammar — confirmed non-overlapping with all existing established Korean files. Per dispatch
instructions, Attested Era/Region are filled in concretely wherever the source specifies a stage or
dialect, since that is the book's central subject. "Grammar points" below are the historical-linguistics
analog of conjugation rules: genetic-hypothesis methodology, sound-correspondence systems, and
morphological comparanda. The source has a clean, real text layer (`pdftotext`, verified, no
font-substitution cipher) — Transcription Confidence and Vision Reading Confidence are `n/a`
throughout. **Known extraction gap:** several multi-syllable Hangul headwords inside the dense
Manchu–Korean comparison lists (pp. 23–26) extracted with one internal Hangul syllable block
silently missing from the PDF text layer (e.g. `tasoli-` rendered as "다리-" with its middle syllable
absent; several other rows show a bare dash `- ` where a Hangul block should sit). This looks like a
rare-jamo CID-font gap distinct from the known Korean additive-offset cipher documented in the
extraction spec — romanized (Yale) forms are reliable throughout and are used as the primary `Term`;
Hangul is reproduced exactly as extracted, gaps and all, never guess-filled. Flagged per-row in Notes
only where the gap is substantive.

---

### Vocabulary

Note: almost all entries below are Korean lexical/morphological forms cited by the authors as
*comparative evidence* for genetic hypotheses (Altaic, Tungusic/Manchu, Japanese) — not independently
attested vocabulary from a dictionary. Proposed foreign cognates are paraphrased in the Notes column
for context; this is comparative-linguistic argumentation, not an endorsement that the etymology is
proven (the chapter itself treats most of these as unresolved hypotheses).

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| hoy (히/ᄒᆡ, as cited) | 'sun' | noun | archaic | — | Korean stage not specified by authors (cited generically as "Korean") | — | — | grammar_reference | n/a | n/a | Compared to Manchu šun, Nanai siú, Solon šigun 'sun'; cited as evidence for Ramstedt's hypothesis that Korean h derives from *s before high front *i (p. 21). |
| holk | 'earth' | noun | archaic | — | as above | — | — | grammar_reference | n/a | n/a | Compared to Nanai siru 'sand,' Solon širuktan 'sand,' Mongolian širuɣai 'earth, dust' — same *s>h hypothesis (p. 21). |
| swusk (숫ᄀ) / swuch | 'charcoal' | noun | archaic | — | Middle Korean (swusk) → modern swuch | — | — | grammar_reference | n/a | n/a | Cited as a complication for the *s>h hypothesis: this non-initial aspirate instead derives from a velar stop (p. 22). |
| twosk (돗ᄀ) / twoch | 'sail' | noun | archaic | — | Middle Korean → modern twoch | — | — | grammar_reference | n/a | n/a | Same velar-stop-to-aspirate pattern as swusk/swuch (p. 22). |
| phosk (ᄀ ) / phath | 'redbean' | noun | archaic | — | Middle Korean → modern phath | — | — | grammar_reference | n/a | n/a | Same velar-stop-to-aspirate pattern (p. 22). |
| phaykki | 'redbean' | noun | regional | — | contemporary (source published 2011) | Northeastern Korea | regional | grammar_reference | n/a | n/a | Explicit dialectal annotation: some northeastern dialects preserve the /k/ reflex that standard Korean lost to aspiration (p. 22). |
| swukk- | 'charcoal' | noun | regional | — | contemporary (source published 2011) | Northeastern Korea | regional | grammar_reference | n/a | n/a | Same explicit northeastern-dialect /k/-preservation annotation as phaykki (p. 22). |
| kwul (굴) | 'chimney' | noun | archaic | — | Middle Korean | — | — | grammar_reference | n/a | n/a | Compared to Manchu hūlan, Ulch kula, Mongolian kulang 'chimney'; cited as evidence that Korean lost a final vowel (syncope: two syllables > one) (p. 20). |
| cap- (잡-) | 'grasp, hold, catch' | verb | core | — | Middle Korean; modern reflex 잡다 japda is identical in meaning | — | — | grammar_reference | n/a | n/a | Cited twice: as a syncope example compared to Manchu jafa- 'grasp' (p. 20), and again in the larger Manchu verb-correspondence list (p. 25). |
| solk ( ) | 'wildcat' | noun | archaic | — | Middle Korean | — | — | grammar_reference | n/a | n/a | Compared to Manchu solohi, Evenki soligā, Mongolian soloŋɣo 'weasel'; cited as evidence for /l/-cluster formation via loss of a medial vowel (p. 20). |
| -ay/-ey (-애/-에) | locative particle | particle | archaic | — | Middle Korean | — | — | grammar_reference | n/a | n/a | Compared to reconstructed Altaic dative *-a/-e (Old Turkic at-ı̈ma 'to my horse'; Mongolian ɣaʒ̂ar-a 'in the land') (p. 22). |
| -lwo (-로) | directional particle | particle | core | — | Middle Korean; modern Korean retains -ro/-euro | — | — | grammar_reference | n/a | n/a | Compared to reconstructed Altaic directional *-ru/-rü (Old Turkic äb-im-rü 'to my house'; Mongolian inaru 'this way') (p. 22). |
| ili (이리) | 'this way' | adverb | archaic | — | Middle Korean | — | — | grammar_reference | n/a | n/a | Compared to Evenki prolative *-li (hokto-li 'along this road'); grouped with kuli, tyeli as a set sharing the same element (p. 22). |
| kuli (그리) | 'that way' | adverb | archaic | — | Middle Korean | — | — | grammar_reference | n/a | n/a | See ili above (p. 22). |
| tyeli (뎌리) | 'that way (there)' | adverb | archaic | — | Middle Korean | — | — | grammar_reference | n/a | n/a | See ili above (p. 22). |
| yelum (여름) | 'fruit' | noun | archaic | — | Middle Korean | — | — | grammar_reference | n/a | n/a | Derived from verb stem yel- 'bear fruit' + nominalizer -(o/u)m; compared to Altaic *-m nominalizer (e.g. Old Turkic öl-üm 'death') (p. 22). |
| kelum (거름) | 'step' | noun | archaic | — | Middle Korean | — | — | grammar_reference | n/a | n/a | Derived from ket/kel- 'walk' + -(o/u)m (p. 22). |
| elum (어름) | 'ice' | noun | core | — | Middle Korean; modern reflex eolum/eoreum is the same word | — | — | grammar_reference | n/a | n/a | Derived from el- 'freeze' + -(o/u)m (p. 22). |
| yelwum (여룸) | 'bearing fruit' (nominalized predicate) | verb-derived nominal | archaic | — | Late Middle Korean only — this predicate-nominalizing use of -(o/u)m did not survive into Contemporary Korean | — | — | grammar_reference | n/a | n/a | Illustrates a dual function (noun-forming and whole-predicate-nominalizing) of -(o/u)m also found in earlier Mongolian texts (p. 22). |
| kelwum (거룸) | 'walking' (nominalized predicate) | verb-derived nominal | archaic | — | Late Middle Korean only | — | — | grammar_reference | n/a | n/a | See yelwum above (p. 22). |
| cwukilq (주길q, cited as 주 ...) | '(person) to be killed' | verb-derived modifier | archaic | — | Late Middle Korean, attested 1459 (Wŏrin sŏkpo 25:75b) | — | — | grammar_reference | n/a | n/a | From cwuki- 'kill' + future-conjecture modifier -(o/u)lq; compared to Altaic *-r future/present modifier (p. 23). |
| taton (다ᄃᆛᆫ, cited as 다 ) | 'closed (door)' | verb-derived modifier | archaic | — | Late Middle Korean, attested 1481 (Tusi ŏnhae 8:61a) | — | — | grammar_reference | n/a | n/a | Past/completed-action modifier -(o/u)n, basically unchanged in function in modern Korean; compared to Altaic *-n (p. 23). |
| alay (아래) | 'lower part' | noun | core | — | Middle Korean; modern reflex is the same word | — | — | grammar_reference | n/a | n/a | < *al-; compared to Evenki alas 'leg, base,' Mongolian ala 'thigh,' Old Turkic al 'lower side' (p. 18, correspondence 1). |
| mol ( ) | 'horse' | noun | archaic | — | Middle Korean; modern reflex mal | — | — | grammar_reference | n/a | n/a | Compared to Manchu/Mongolian morin 'horse' (p. 18, correspondence 2); also flagged separately (p. 25) as a possible early contact loan rather than inherited cognate. |
| wola- (오라-) | 'be a long time' | verb | archaic | — | Middle Korean | — | — | grammar_reference | n/a | n/a | Compared to Evenki uri-pta, Mongolian urida 'before, formerly' (p. 18, correspondence 3). |
| mul (믈) | 'water' | noun | core | — | Middle Korean; modern reflex mul is identical | — | — | grammar_reference | n/a | n/a | Compared to Manchu muke, Evenki mū, Mongolian mören 'river' (p. 18, correspondence 7); also in the larger Manchu mu-ke comparison (p. 26). |
| pwul- / pul- (불-/블-) | 'blow' | verb | core | — | Middle Korean; modern reflex bul-/bulda | — | — | grammar_reference | n/a | n/a | < *pülɔ̈-; compared to Manchu fulgiye-, Mongolian üliye- 'blow' (p. 19, correspondence 8); cited twice as evidence the Korean bilabial *p is preserved where most Altaic branches lost it (p. 21). |
| ilang (이랑) | 'ridge between fields' | noun | archaic | — | Middle Korean | — | — | grammar_reference | n/a | n/a | Compared to Mongolian iraɣa, Manchu irun, Chuvash yə̂ran 'ridge between fields' (p. 19, correspondence 4; repeated p. 19 as liquid-correspondence 14). |
| il / ilu- (일/이르-) | 'early' / 'be early' | adjective/verb | core | — | Middle Korean; modern reflex iru- survives | — | — | grammar_reference | n/a | n/a | Compared to Manchu erde, Mongolian erte, Chuvash ir 'early' (p. 19, correspondence 6). |
| pil- (빌-) | 'pray, beg' | verb | core | — | Middle Korean; modern reflex bil-/bilda | — | — | grammar_reference | n/a | n/a | Compared to Manchu firu-, Evenki hiruge, Mongolian irüge- 'pray, bless' (p. 19, correspondence 9); also cited again in the Manchu firu- verb list (p. 25) and as a *p-preservation example (p. 21). |
| puz- ( -) | 'pour' | verb | archaic | — | Middle Korean | — | — | grammar_reference | n/a | n/a | Compared to Manchu fusu- 'sprinkle (water)'; cited as evidence Korean ᅳ /u/ corresponds to Altaic *ü (p. 19); also cited as a *p-preservation example (p. 21) and again in the Manchu verb list (p. 25). |
| pulk- (븕-) | 'red' | adjective | core | — | Middle Korean; modern reflex bulk-/bulgeo- | — | — | grammar_reference | n/a | n/a | < *pulagān; compared to Manchu fulgiyan, Mongolian ulaɣan 'red' (p. 19). |
| ustum (으ᄉᆟᆻᆷ, cited as 으 ) | 'the head, basis' | noun | archaic | — | Middle Korean | — | — | grammar_reference | n/a | n/a | Noted as the *only* Middle Korean word beginning with the vowel /o/ or /u/ — flagged by the authors as a curious distributional gap worth further research (p. 19). |
| twolh (돓) | 'stone' | noun | archaic | — | Middle Korean; < *tuluh < *tı̈lagu | — | — | grammar_reference | n/a | n/a | Compared to Mongolian cˇilaɣun, Chuvash c´ul, Old Turkic taš 'stone'; cited as evidence Old Korean may have had two liquid phonemes later merged to one in Middle Korean (p. 19, liquid correspondence 16). |
| (nwun)pwola (눈보라) | 'snowstorm' | noun | core | — | Middle Korean; modern reflex nunbora is the same compound | — | — | grammar_reference | n/a | n/a | Compared to Mongolian boroɣan 'rain,' Middle Mongolian boro'an, Yakut burxān 'snowstorm' (p. 19, liquid correspondence 13). |
| nal (날) | 'day' | noun | core | — | Middle Korean; modern reflex is the same word | — | — | grammar_reference | n/a | n/a | Compared to Mongolian naran 'sun' as a Mongolic-branch look-alike (p. 24). |
| nwun (눈) | 'eye' | noun | core | — | Middle Korean; modern reflex is the same word (also means 'snow') | — | — | grammar_reference | n/a | n/a | Compared to Mongolian nidün < *nün-dün 'eye' (p. 24). |
| na (나) | 'I' | pronoun | core | — | Middle Korean; modern reflex is the same word | — | — | grammar_reference | n/a | n/a | Compared to Mongolian first-person pronoun stem *na- (attested in locative nadur, accusative namayi) (p. 24). |
| wo- (오-) | 'come' | verb | core | — | Middle Korean; modern reflex o- | — | — | grammar_reference | n/a | n/a | Compared to Mongolian oru- 'enter' (p. 24). |
| ka- (가-) | 'go' | verb | core | — | Middle Korean; modern reflex ka-/gada is the same word | — | — | grammar_reference | n/a | n/a | Compared to Mongolian ɣar- 'to exit' (p. 24). |
| cec (젖) | 'breasts' | noun | core | — | Middle Korean; modern reflex jeot/jeos | — | — | grammar_reference | n/a | n/a | Compared to Manchu cejen 'upper part of the chest' — one of ~250 proposed Manchu-Korean basic-vocabulary correspondences (p. 24). |
| cwoc (좆) | 'penis' | noun | taboo | — | Middle Korean; modern reflex is the same word, now a vulgar/taboo register term | — | — | grammar_reference | n/a | n/a | Compared to Manchu coco 'penis' (p. 24). |
| -tek (-덕) | 'a rise, high place' | noun/suffix | regional | — | attested only in place names | — | national (attested across Korean place-name corpus) | grammar_reference | n/a | n/a | Compared to Manchu deke/deken 'a rise, high place' (p. 24); explicitly noted by the authors as attested only in toponyms. |
| patang (바당) | 'bottom' | noun | archaic | — | Middle Korean | — | — | grammar_reference | n/a | n/a | Compared to Manchu fatan 'sole of the foot' (p. 24). |
| polk(cwuy) ( (쥐)) | 'bat' | noun | archaic | — | Middle Korean | — | — | grammar_reference | n/a | n/a | Compared to Manchu ferehe(singgeri) 'bat' (p. 24). |
| kolom ( ) | 'river' | noun | archaic | — | Middle Korean | — | — | grammar_reference | n/a | n/a | Compared to Manchu golo 'river bed' (p. 24). |
| kwusul (구슬) | 'gem, precious stone' | noun | core | — | Middle Korean; modern reflex gusul is the same word | — | — | grammar_reference | n/a | n/a | Compared to Manchu gu 'jadite, precious stone' (p. 24). |
| kaci (가지) | 'kind, sort' | noun | core | — | Middle Korean; modern reflex gaji is the same word | — | — | grammar_reference | n/a | n/a | Compared to Manchu hacin 'kind, sort' (p. 24). |
| cakal (자갈) | 'gravel' | noun | core | — | Middle Korean; modern reflex jagal is the same word | — | — | grammar_reference | n/a | n/a | Compared to Manchu jahari 'pebbles and stones found along a river bed' (p. 24). |
| nalah (나랗) | 'country, land' | noun | archaic | — | Middle Korean; -lah analyzed as a suffix | — | — | grammar_reference | n/a | n/a | Compared to Manchu/Nanai na 'earth, land' (the Nanai ethnonym itself means 'local people') (p. 24). |
| pwoli (보리) | 'barley' | noun | core | — | contemporary (source published 2011); crop cultivated on the peninsula since the Mumun period, c. 1500–850 BC | — | — | grammar_reference | n/a | n/a | Flagged by the authors as a *possible* early cultural/contact loan (not inherited cognate) from Manchu bele 'rice'; the Middle Korean form's low-low tone pattern is noted as more typical of loanwords than native vocabulary (p. 25). |
| mil (밀) | 'wheat' | noun | core | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | Flagged as a possible loan from Manchu mere 'buckwheat' (p. 25). |
| mama (마마) | 'smallpox' | noun | archaic | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | Flagged as a "suspicious" (likely loan, not cognate) match with Manchu mama 'id.' (p. 25). |
| tasoli- (다리-, extracted with a syllable gap) | 'rule, govern' | verb | archaic | — | Middle Korean | — | — | grammar_reference | n/a | n/a | One of ~70 proposed Manchu verb-stem correspondences, cited as especially strong evidence because verbs resist borrowing; compared to Manchu dasa- 'rule, correct' (p. 25). Hangul extraction gap: see file header note. |
| tol- ( -, Hangul gap in extraction) | 'go at a gallop' | verb | archaic | — | Middle Korean | — | — | grammar_reference | n/a | n/a | Compared to Manchu dori- 'gallop' (p. 25). |
| et- (얻-) | 'get, obtain' | verb | core | — | Middle Korean; modern reflex eod-/eodda | — | — | grammar_reference | n/a | n/a | Compared to Manchu ete- 'overcome, win' (p. 25). |
| pto- ( -, Hangul gap) | 'pick, pluck, gather' | verb | archaic | — | Middle Korean | — | — | grammar_reference | n/a | n/a | Compared to Manchu fata- 'pinch, pick (fruit)' (p. 25). |
| ptho- ( -, Hangul gap) | 'play on a stringed instrument; beat (cotton) out' | verb | archaic | — | Middle Korean | — | — | grammar_reference | n/a | n/a | Compared to Manchu fithe- 'snap, spring, pluck, play (a stringed instrument)' (p. 25). |
| pola- ( 라-) | 'hope for, expect' | verb | archaic | — | Middle Korean | — | — | grammar_reference | n/a | n/a | Compared to Manchu foro- 'spin, turn, face, turn toward' (p. 25). |
| pozoy- (ᄫᆝᆼᄋᆡ-, Hangul gap) | 'shine' | verb | archaic | — | Middle Korean | — | — | grammar_reference | n/a | n/a | Compared to Manchu foso- 'shine' (p. 25). |
| pwupuy- (부븨-) | 'rub' | verb | archaic | — | Middle Korean | — | — | grammar_reference | n/a | n/a | Compared to Manchu fufu- 'saw' (p. 25). |
| poli- ( 리-) | 'cut with a sharp instrument' | verb | archaic | — | Middle Korean | — | — | grammar_reference | n/a | n/a | Compared to Manchu furu- 'slice finely, grate' (p. 25). |
| psi (씨) | 'seed' | noun | core | — | Middle Korean; modern reflex ssi is the same word | — | — | grammar_reference | n/a | n/a | Compared to Manchu fuse- 'propagate, reproduce' (p. 25). |
| kaci- (가지-) | 'take, keep' | verb | core | — | Middle Korean; modern reflex gaji-/gajida | — | — | grammar_reference | n/a | n/a | Compared to Manchu gai- 'take' (p. 25). |
| kwocwo (고조) | 'device for extracting dregs from oil or wine' | noun | archaic | — | Middle Korean | — | — | grammar_reference | n/a | n/a | Compared to Manchu goci- 'draw, extract, press out' (p. 25). |
| kal- (갈-) | 'change' | verb | core | — | Middle Korean; modern reflex gal-/galda | — | — | grammar_reference | n/a | n/a | Compared to Manchu hala- 'exchange, change' (p. 25). |
| kelu- (거르-) | 'strain, filter' | verb | core | — | Middle Korean; modern reflex georu-/georuda | — | — | grammar_reference | n/a | n/a | Compared to Manchu here- 'ladle out, fish for, take out of water with a net' (p. 25). |
| ket- (걷-) | 'fold up, roll up' | verb | archaic | — | Middle Korean | — | — | grammar_reference | n/a | n/a | Compared to Manchu hete- 'roll up, fold' (p. 25). |
| kolp- (곫-, Hangul uncertain) | 'line up together' | verb | archaic | — | Middle Korean | — | — | grammar_reference | n/a | n/a | Compared to Manchu holbo- 'connect, join, pair' (p. 25). |
| nil(u)- (닐-) | 'come up, stand up' | verb | archaic | — | Middle Korean | — | — | grammar_reference | n/a | n/a | Compared to Manchu ili- 'stand, stop' (p. 25). |
| culki- (즐기-) | 'enjoy' | verb | core | — | Middle Korean; modern reflex jeulgi-/jeulgida | — | — | grammar_reference | n/a | n/a | Compared to Manchu jirga- 'be at ease, enjoy leisure' (p. 25). |
| kulk- (긁-) | 'scratch' | verb | core | — | Middle Korean; modern reflex geulg-/geulgda | — | — | grammar_reference | n/a | n/a | Compared to Manchu karka- 'scrape with chopstick' (p. 25). |
| kalm- (갊-) | 'put away, put in order, conceal' | verb | archaic | — | Middle Korean | — | — | grammar_reference | n/a | n/a | Compared to Manchu karma- 'protect' (p. 25). |
| mal- (말-) | 'cease, refrain from' | verb | core | — | Middle Korean; modern reflex mal-/malda | — | — | grammar_reference | n/a | n/a | Compared to Manchu mara- 'decline, reject, refuse' (p. 25). |
| mulu- (므르-) | 'retreat, go back' | verb | archaic | — | Middle Korean | — | — | grammar_reference | n/a | n/a | Compared to Manchu mari- 'return, go back' (p. 25). |
| mey- (메-) | 'carry on one's shoulder' | verb | core | — | Middle Korean; modern reflex me-/meda | — | — | grammar_reference | n/a | n/a | Compared to Manchu meihere- 'carry on the shoulder' (p. 26). |
| memul- (머믈-) | 'stop, stay' | verb | archaic | — | Middle Korean | — | — | grammar_reference | n/a | n/a | Compared to Manchu momoro- 'sit silently' (p. 26). |
| monci- ( 지-, Hangul gap) | 'finger, handle, stroke' | verb | archaic | — | Middle Korean | — | — | grammar_reference | n/a | n/a | Compared to Manchu monji- 'rub, knead, massage' (p. 26). |
| nem- (넘-) | 'exceed, go over' | verb | core | — | Middle Korean; modern reflex neom-/neomda | — | — | grammar_reference | n/a | n/a | Compared to Manchu neme- 'add, increase' (p. 26). |
| nel- (널-) | 'spread out' | verb | archaic | — | Middle Korean | — | — | grammar_reference | n/a | n/a | Compared to Manchu nerki- 'open out, unroll' (p. 26). |
| selGec- (설엊-) | 'wash dishes' | verb | archaic | — | Middle Korean | — | — | grammar_reference | n/a | n/a | Compared to Manchu silgiya- 'rinse out' (p. 26). |
| sumuy- (스믜-) | 'soak into, permeate' | verb | archaic | — | Middle Korean | — | — | grammar_reference | n/a | n/a | Compared to Manchu sime- 'soak, moisten, seep into' (p. 26). |
| swum- (숨-) | 'hide' | verb | core | — | Middle Korean; modern reflex sum-/sumda | — | — | grammar_reference | n/a | n/a | Compared to Manchu somi- 'hide, conceal, bury' (p. 26). |
| tam- (담-) | 'fill, put in' | verb | core | — | Middle Korean; modern reflex dam-/damda | — | — | grammar_reference | n/a | n/a | Compared to Manchu tama- 'collect scattered thing, fill (a vessel) with' (p. 26). |
| task- (-, Hangul gap) | 'polish, roast (beans or sesame)' | verb | archaic | — | Middle Korean | — | — | grammar_reference | n/a | n/a | Compared to Manchu tasga- 'saute quickly, cook dry' (p. 26). |
| tepul- (더블-) | 'go with, take (a person) with, accompany' | verb | archaic | — | Middle Korean | — | — | grammar_reference | n/a | n/a | Compared to Manchu tebeliye- 'hug, embrace' (p. 26). |
| chŭl | 'Buddhist temple' | noun | archaic | — | cited by Aston, 1879 | — | — | grammar_reference | n/a | n/a | Aston's 1879 comparison to Japanese tera 'temple' — one of the earliest Korean-Japanese comparisons still judged valid today, despite Aston's otherwise weak secondhand knowledge of Korean (p. 27). |
| syěm (셤) | 'island' | noun | core | — | Middle Korean; modern reflex seom is the same word | — | — | grammar_reference | n/a | n/a | Well-attested pair with Japanese sima 'island' — cited as a Korean-Japanese correspondence with no parallel elsewhere in Altaic (p. 29). |
| nat (낟) | 'sickle' | noun | core | — | Middle Korean; modern reflex nat/nas | — | — | grammar_reference | n/a | n/a | Compared to Japanese nata 'hatchet' (p. 29). |
| path (밭) | '(dry) field' | noun | core | — | Middle Korean; modern reflex bat is the same word | — | — | grammar_reference | n/a | n/a | Compared to Japanese pata/patakey 'field' (p. 29). |
| patah (바닿) | 'sea' | noun | core | — | Middle Korean; modern reflex bada | — | — | grammar_reference | n/a | n/a | Compared to Japanese wata (< *bata) 'sea' (p. 29). |

#### Morpheme breakdown

> **yelum** (여름) 'fruit' = **yel-** (여-, "bear fruit," verb stem) + **-(o/u)m** (nominalizer) —
> demonstrates the Middle Korean action/result-nominalizing suffix later compared to a reconstructed
> Proto-Altaic *-m nominalizer; p. 22.

> **kelum** (거름) 'step' = **ket/kel-** (걷/걸-, "walk," verb stem) + **-(o/u)m** (nominalizer) — same
> pattern as yelum; p. 22.

> **elum** (어름) 'ice' = **el-** (얼-, "freeze," verb stem) + **-(o/u)m** (nominalizer) — same pattern,
> and the clearest case where the Middle Korean nominalized form survives unchanged into Contemporary
> Korean; p. 22.

> **cwukilq** (주길q) '(person) to be killed' = **cwuki-** (주기-, "kill," verb stem) + **-(o/u)lq**
> (future/conjectural modifier) — the Altaic-comparandum morpheme the authors consider their strongest
> single piece of morphological evidence for a genetic relationship; attested 1459 (Wŏrin sŏkpo
> 25:75b); p. 23.

> **taton** (다 ) 'closed (door)' = **tat-** (닫-, "close," verb stem) + **-(o/u)n** (past/completed-action
> modifier) — attested 1481 (Tusi ŏnhae 8:61a); the modifier's function is essentially unchanged in
> Contemporary Korean; p. 23.

---

### Grammar points

*(The historical-linguistics analog of grammar points for this diachronic source: periodization,
transcription-system history, and — the chapter's real substance — the methodology and evidence base
for Korean's proposed genetic relationships.)*

#### Periodization of the Korean language

The authors establish five historical stages, each tied to a chapter of the book (p. 4–8): **Old
Korean** (pre-alphabetic, reconstructed largely from fifteenth-century internal reconstruction plus
scattered philological hints; identified specifically with the language of Silla, 57?BC–935AD, because
Silla's military/political unification of the peninsula made its speech the ancestor of all later
Korean); **Early Middle Korean** (the Koryŏ period, beginning roughly in the tenth century when the
capital moved from the southeast to the peninsula's middle — a stage the authors argue began about
500 years before the alphabet, not at the alphabet's invention); **Late Middle Korean** (LMK, the
alphabetic fifteenth–sixteenth century, by far the best-documented stage and the fixed reference point
from which every earlier stage is reconstructed); **Early Modern Korean** (seventeenth–nineteenth
century, a transitional, orthographically unconstrained period disrupted by the Imjin Wars, disease,
and famine, during which reinforcement/aspiration spread, palatalization and spirantization occurred,
/o/ was lost, monophthongization took place, and vowel harmony eroded); and **Contemporary Korean**
(from the late-nineteenth-century "enlightenment period" script reforms and the 1933 orthographic
standard onward). The authors explicitly reject the common English-language convention of calling the
17th–19th-century stage "Modern Korean," finding it confusing to call a centuries-dead stage "modern,"
and coin "Early Modern Korean" instead (p. 8–9).

#### Pre-alphabetic transcription systems

Before 1446, Koreans recorded their own language only indirectly, through Chinese characters used
either phonetically or semantically, "often in combinations" (p. 1). Four methods are named: **idu**,
a scribal technique going back to the Three Kingdoms period, used mainly to annotate Chinese texts and
yielding little phonological information but some grammatical information about particles and verb
endings; **hyangch'al**, the method used to write **hyangga** ("local songs") — a complex interweaving
of Chinese graphs where some hint at meaning and others at sound, comparable to Japanese man'yōgana but
far less well preserved (only ~25 hyangga survive, versus ~5,000 extant man'yōgana poems, and Japan's
poems were further annotated in katakana while Korea's were not) (p. 1–2); **kugyŏl**, simplified
Chinese characters written by hand between the lines of a Chinese text, discovered only in the 1990s;
and **kakp'il**, tiny stylus-made dots and angled lines (not writing at all), discovered only in 2000
under strong angled light — both kugyŏl and kakp'il are described as still-unfolding discoveries with
"the final story... still to be written" (p. 6–7).

#### Sources for reconstructing Early Middle Korean

Four evidentiary sources are named for the Koryŏ-period stage (p. 5–6): the ***Jīlín lèishì*** (Korean:
**Kyerim yusa**), a vocabulary list compiled by a Chinese visitor to the Koryŏ capital in the early
twelfth century, transcribed impressionistically with Chinese phonograms; the ***Hyangyak kugŭppang***,
a thirteenth-century medical treatise listing native plant/product names for herbal cures, only
occasionally phonetic but systematic enough to approach "a kind of rudimentary syllabary" — the
authors speculate a larger corpus of this type could reveal much more; **Mongolian (and Jurchen)
loanwords** borrowed through Yuan-dynasty contact, which inform both phonology and, per a later
section, the timing of a hypothesized "Korean Vowel Shift" between the 13th and 15th centuries; and
the **kugyŏl/kakp'il** interlinear annotation systems described above.

#### Romanization conventions used in this book

The authors use **McCune-Reischauer** for Korean names and general terms in running prose (chosen for
its "esthetically pleasing" appearance to Western readers over the South Korean Ministry of
Education's 2000 revised system), but "Hangul" (not "Han'gŭl") throughout for the alphabet's name
specifically. For linguistic forms, they use a **modified Yale romanization** adapted from Samuel E.
Martin's *Reference Grammar of Korean* (1992), departing from Martin in three ways: always citing the
original Korean/Chinese-character form alongside the romanization; omitting tone marks except where
tonal information bears directly on the analysis; and using the same Yale system for both Middle and
Contemporary Korean forms rather than Martin's practice of italicizing MK forms differently from
Contemporary ones (p. 10–11).

#### Sino-Korean transcription conventions

Two distinct romanization conventions mark different kinds of Sino-Korean evidence (p. 11): readings
codified in the 1447 dictionary *Tongguk chŏngun* (prescriptive readings used in the earliest
alphabetic texts) are transcribed in italic capitals, e.g. 東國正韻 as *TWONG-KWUYK CYENG-NGWUN*; readings
reflecting actual pronunciation from the 1480s onward, called "Eastern Sounds" (東音), are transcribed
the same way but represent a later, less artificial stratum, e.g. 杜詩諺解 as *[TWU-SI EN-HOY]*. Separately,
phonograms written by Koreans (any period) are treated as Eastern Sounds in modified Yale; phonograms
written by Han Chinese are assumed to reflect reconstructed Chinese sound values and romanized per
Pulleyblank (1991) instead.

#### The Three Kingdoms linguistic landscape

Koguryŏ, Paekche, and Silla are identified as "the first states to arise on the Korean peninsula for
which linguistic evidence still exists," mostly recovered from place names preserved in the *Samguk
sagi* (a 1145 Koryŏ-period compilation of older, now-lost records) rather than from direct records (p.
3). The authors argue the three kingdoms spoke "different but closely related languages," noting
Koguryŏ place names in particular carry transcriptional characteristics distinctively marking them as
Koguryŏan — a controversial point they flag as unresolved. Silla's speech specifically is identified
as "Old Korean" proper, because Silla's conquest-driven political unification made its language the
peninsula-wide lingua franca that gave rise to Middle Korean (p. 4). Earlier ethnonyms/toponyms
recorded by Han Chinese visitors (Chosŏn, Suksin, Puyŏ, Hán, Koguryŏ, Okchŏ, Ye, and the "Three Hán":
Mahan, Chinhan, Pyŏnhan) are explicitly flagged by the authors as *not* reliable phonological evidence
— "the sounds and meanings that those characters were intended to represent have long since been
lost," and the romanized forms conventionally given merely reflect modern Korean pronunciations of the
Chinese characters, "nothing more" (p. 3–4) — hence these are not included in the Vocabulary table
above as attested linguistic forms.

#### Criteria for establishing a genetic relationship

The chapter opens by setting a strict methodological bar (p. 13–14): resemblances between languages,
even striking ones, are not sufficient evidence of common origin — they "must occur in interlocking
and systematic sets that banish all possibility of accident or borrowing," and must be *productive*:
a genuine genetic hypothesis should set off a "chain reaction" of further, previously unsuspected
discoveries about the languages' prehistory (the authors cite Indo-European's Grimm's/Verner's/
Grassmann's Laws as the paradigm case). Evidence must also be strictly linguistic — ethnic-migration
records or archaeological findings, however suggestive, "can never serve as substitutes for" linguistic
research, only point toward where it should look. By this standard, no genetic hypothesis for Korean
has yet reached the required "critical mass" of correspondences (p. 14).

#### Genetic hypotheses overview

Two hypotheses are treated as seriously held by specialists today: the **Altaic hypothesis** and the
**Korean-Japanese hypothesis**; "Macro-Altaic" combines both by placing Korean and Japanese inside an
expanded Altaic family (p. 14–15). A footnoted aside (p. 15) describes a minor third proposal: Morgan
Clippinger's 1984 argument for a **Korean-Dravidian** genetic connection, based on 408 proposed cognate
pairs between Middle Korean and Dravidian forms yielding 60 phonological correspondences — professionally
argued, per the authors, and anticipated as early as 1905 by Homer B. Hulbert and echoed in 1980 by Ōno
Susumu's claim that Tamil underlies a lexical stratum in both Japanese and Korean, but the idea was
largely abandoned after the 1980s; the authors nonetheless suggest Clippinger's study "deserves to be
reexamined."

#### Altaic family structure and shared typological features

Altaic comprises three well-established branches — **Turkic, Mongolic, Tungusic** — each internally
well-supported by productive sound correspondences, but the overarching hypothesis uniting the three
branches is itself controversial; skeptics attribute the resemblance to prolonged areal contact and
borrowing rather than common descent (p. 15). Shared typological features cited include **vowel
harmony**, **verb-final word order**, **agglutination**, and especially the **converb** (a verbal
suffix functioning like a relative pronoun or conjunction in a European language — the authors note
this is the one Altaicist term they use elsewhere, with "converb" otherwise avoided in describing
Korean structure, per the Introduction's grammatical-terms note). Converbs are notably absent from
Uralic, once wrongly grouped with Altaic as "Ural-Altaic." Most of these Altaic structural features are
also found in both Korean and Japanese — suggestive, the authors stress, but not proof (p. 15–16).

#### Two methodologies for proving genetic relationship: comparative method vs. Meillet's *fait particulier*

The authors distinguish two approaches comparativists have used for Korean-Altaic (p. 17): the
standard **comparative method** (establishing systematic sound correspondences across the lexicon,
which for Korean-Altaic "has not yet been numerous or systematic enough to convince all skeptics"), and
a **methodological shortcut** proposed by French structuralist Antoine Meillet in the early twentieth
century — proving genetic affinity via a single *fait particulier* ("singular fact"), typically a
shared irregular/suppletive morphological pattern too specific to have been borrowed (Meillet's own
example: English good/better/best paralleling German gut/besser/best-). The authors consider this
second method, applied to Korean's verbal nominalizer/modifier system (below), "the most persuasive"
evidence currently available for Korean-Altaic.

#### Vowel correspondence system (Proto-Altaic ↔ Early Middle Korean ↔ Late Middle Korean)

The chapter's central phonological table (p. 17–18) proposes a 9-way front/back vowel harmony
correspondence, reconstructing Proto-Altaic forms (after Poppe 1960) against Early Middle Korean and
attested Late Middle Korean values:

**Back vowels:** (1) *a : *a : ᅡ [a] /a/ — (2) *o : *ɔ : ᆞ [ʌ] /o/ — (3) *u : *u : ᅩ [o] /wo/.
**Front vowels:** (4) *ı̈ : *i : ᅵ [i] /i/ — (5) *e : *ä : ᅥ [ə] /e/ — (6) *ė : *i : ᅵ [i] /i/ —
(7) *ö : *ɔ̈ : ᅳ [ɨ] /u/ — (8) *ü : *ü : ᅮ [u] /wu/ — (9) *i : *i : ᅵ [i] /i/.

Notably, correspondences (4), (6), and (9) all collapse to Middle Korean /i/, which the authors read as
evidence that Korean's high front vowel /i/ represents a merger of several earlier front-vowel
distinctions — a pattern they note is paralleled by mergers in other Altaic daughter languages (p. 18).
The authors flag real weaknesses in the table themselves (p. 18–19): correspondences (2) and (7) rest
on suspiciously few Korean examples, and the same Korean vowel ᅳ /u/ appears to correspond to at least
three different reconstructed Altaic vowels (*ü, *u, *ö), an unresolved ambiguity. They also note a
curious distributional fact used as supporting context: almost no native Middle Korean word begins
with /o/ or /u/ (the sole exception cited is ustum 'the head, basis'). A competing view (Starostin et
al. 2003, footnoted p. 17) holds Proto-Altaic had no vowel harmony at all and that each branch developed
it independently; the authors call this "implausible" but take no position on the separate, more minor
question of whether Proto-Altaic had distinctive vowel length or pitch.

#### Vowel syncope/apocope as a historical development

Following from the vowel-correspondence table, the authors argue word-final vowels were regularly lost
in Korean's history, reducing two-syllable Altaic-cognate words to one syllable in Middle Korean (e.g.
Manchu hūlan 'chimney' → kwul), and that medial-vowel loss produced Middle Korean's /l/-consonant
clusters (e.g. Manchu solohi 'weasel' → solk 'wildcat') (p. 19–20). This syncope pattern is cross-
supported by internal reconstruction work discussed later in the book (Chapter 4), which traces Middle
Korean's consonant clusters and aspirates independently to the same process of medial-vowel loss.

#### Consonant correspondence system

A parallel consonant table (p. 20, Late Middle Korean values against Poppe's 1960 Proto-Altaic
reconstructions) maps: *p>ᄇ/p, *b>ᄇ/p, *t>ᄃ/t, *d>ᄃ/t, *k>ᄀ/k, *g>ᄀ/k, *c>ᄌ/c, *j>ᄌ/c (obstruents 1–8,
showing Korean has lost any Proto-Altaic voicing distinction), *s>ᄉ/s, *m>ᄆ/m, *n>ᄂ/n, *ŋ>ㅇ/ng (9–12,
the velar nasal attested only non-initially), and four liquids *r1/*r2/*l1/*l2 all merging to ᄅ/l
(13–16) — though Old Korean transcriptions hint two liquids may once have existed, later merging in
Middle Korean. Three specific puzzles are discussed in depth (p. 20–22): (1) **Loss of Proto-Altaic
voicing distinctions** — the conditioning factors for this loss remain unidentified, and finding them
(if they align with Altaic comparisons) would be strong confirming evidence. (2) ***p* preservation**
— comparativists reconstruct Proto-Altaic *p, which survives today only as Korean p and (among Tungusic
languages) Nanai p; every other Altaic branch has weakened or lost it entirely (Manchu f-, Evenki h-,
most Mongolic/Turkic languages have lost it outright) — this is treated as one of Korean's most
distinctive pieces of evidence for the Altaic hypothesis. (3) **The mystery of Korean h** — no glottal
fricative is reconstructed for Altaic, yet h is the morphophonemic/historical source of most Korean
aspiration; Ramstedt's hypothesis is that h derives from *s before high front *i (supported by hoy
'sun' vs. Manchu šun/Nanai siú/Solon šigun, and holk 'earth' vs. Nanai siru/Solon širuktan/Mongolian
širuɣai), complicated by the fact that some non-initial Korean aspirates instead derive transparently
from velar stops (swusk>swuch, twosk>twoch, phosk>phath, with some northeastern dialects still
preserving the /k/: phaykki, swukk-).

#### Methodological shortcut applied I — particle correspondences

Three proposed particle matches (p. 22): a locative -ay/-ey compared to reconstructed Altaic dative
*-a/-e; a directional -lwo compared to Altaic directional *-ru/-rü; and the directional-adverb set
ili/kuli/tyeli ('this way'/'that way'/'that way there') compared to Evenki's prolative *-li.

#### Methodological shortcut applied II — the three verbal nominalizer/modifier endings

This is identified by the authors as the single strongest piece of morphological evidence for
Korean-Altaic (p. 22–23). Middle Korean had three verb endings forming nominals and modifiers:
**-(o/u)m** (general nominalizer — e.g. yel- 'bear fruit' → yelum 'fruit'; also, archaically, used to
nominalize whole predicates, e.g. yelwum 'bearing fruit,' a dual function paralleled in early Mongolian
texts where -m marked present-tense predicates); **-(o/u)lq** (future/conjectural modifier, still
productive today — e.g. cwuki- 'kill' → cwukilq '(person) to be killed,' 1459); and **-(o/u)n**
(past/completed-action modifier, functionally unchanged today — e.g. taton 'closed (door),' 1481). The
reconstructed Proto-Altaic triad is virtually identical: *-m, *-r, *-n, with matching functions
attested across Turkic (present-tense modifiers), Mongolic (nominalizers), and Tungusic (future-tense
modifiers in Evenki, nominalizers via combination in Manchu). Because inflectional morphology of this
kind is unusually resistant to borrowing, the authors treat this three-way match — following Meillet's
*fait particulier* logic — as too structurally specific to be coincidental, though they stress it alone
does not prove the broader genetic hypothesis.

#### Korean and Tungusic (Manchu) lexical correspondences

The authors argue Tungusic — especially Southern Tungusic, the ~10-language branch that includes
Manchu — offers by far the richest body of Korean-Altaic comparative evidence, exceeding both Turkic
(few matches) and Mongolic (p. 23–24). Historical contact is well-attested: the Manchu, descended from
the Jurchen (who left monuments in northeastern Korea itself), ruled both China and Korea during the
Qing dynasty, so some shared vocabulary is a known cultural borrowing. But the authors argue a large
number of the ~250 proposed Manchu-Korean basic-vocabulary correspondences are not explicable as
borrowing, because the richest category — roughly 70 proposed **verb-stem** correspondences — belongs
to a part of the lexicon normally resistant to borrowing (full list extracted into the Vocabulary table
above, pp. 24–26). A handful of noun comparisons are explicitly flagged by the authors themselves as
*possible* cultural/contact loans rather than inherited cognates, based on contextual and tonal
evidence (bele/pwoli 'rice'/'barley', mere/mil 'buckwheat'/'wheat', mama/mama 'smallpox', morin/mol
'horse') — a useful methodological model of how the authors themselves distinguish loan from cognate
rather than treating every resemblance as equally strong evidence. One proposed explanation for the
unusually dense Tungusic correspondence set is that Korean may have branched off from Tungusic *after*
Proto-Altaic unity, or that geographic proximity to Manchu/South Tungusic reinforced shared vocabulary
long after the branches diverged. A separate, more radical "Anti-Altaicist" offshoot hypothesis
(Unger 1990, footnoted p. 26) holds Korean and Tungusic are related to each other and to Japanese but
*not* to Turkic or Mongolic — i.e., rejecting Macro-Altaic's unity while keeping a narrower
Korean-Tungusic-Japanese grouping.

#### History of Korean-Japanese comparative linguistics

The chapter traces this research tradition from its earliest speculative mentions (Arai Hakuseki, 1717;
Fujii Teikan, 1781) through the first serious comparative study: William George Aston's 48-page 1879
article, written despite Aston's own admittedly weak, mostly second-hand knowledge of Korean (sourced
from Japanese interpreters' manuals and a sketch in Dallet's *Histoire de l'Eglise de Corée*) — the
authors note Aston's essay is also marred by overtly racist asides about Korean/Japanese "poverty of
imagination," yet several of his specific comparisons (e.g. chŭl/tera 'temple') remain valid today (p.
27). Japanese scholarship on the question culminated in Kanazawa Shōzaburō's 1910/1929 work arguing
Korean and Ryūkyūan were both branches of Japanese — a position the authors call "baldly political,"
unchallenged until after the Pacific War, after which postwar Japanese comparativists expanded the
search (sometimes fancifully) to Austronesian, Dravidian, Tibetan, and a "mixed-language" hypothesis
(p. 27–28). In the West, Roy Andrew Miller's 1971 *Japanese and the Other Altaic Languages* folded
Korean-Japanese comparison into the broader Macro-Altaic program, especially influential in Russia and
Europe; most North American/Western European linguists instead kept Japanese-Korean comparison
separate from Altaic. The pivotal modern work is **Samuel E. Martin's 1966** article "Lexical Evidence
Relating Korean to Japanese" (Language), which systematized 265 (later 320) proposed cognate pairs into
phoneme-by-phoneme correspondence rules and three confidence categories (perfect-fit-same-meaning,
partial-fit-same-meaning, perfect-fit-divergent-meaning) — criticized by some (including Altaicists) as
overly mechanical, producing an implausibly "rich" 16-vowel reconstructed system and complex consonant
clusters with little independent cross-checking against other Altaic languages, yet broadly influential
on subsequent Korean-Japanese comparative work (p. 28–29).

#### Current assessment of the Korean-Japanese hypothesis

The authors' own view, stated plainly (p. 29–30): the Western field's "single-minded focus" on
Korean-Japanese is "overdone." At the current state of the art they count at most ~200 convincing
lexical pairs and no more than 15 plausible inflectional-morpheme matches between the two languages —
contrasted with the Korean-Tungusic evidence, where of the three strong Middle Korean
nominalizer/modifier endings discussed above, only one (-(o/u)m, paralleling Old Japanese -mi) has even
a partial Japanese reflex. Even so, a handful of Korean-Japanese comparisons exist with no parallel
elsewhere in Altaic (syěm/sima 'island'; nat/nata; path/pata; patah/wata — all tabulated above), and
the authors conclude it is "more likely than not" that Korean and Japanese are related, while stressing
the relationship's time-depth and even existence remain formally unproven — echoing Martin's own 1991
admission that "there is no general agreement on the genetic relationships of either Japanese or
Korean" (p. 29). The chapter (and this chunk) closes by reframing recent scholarly practice: rather than
rushing straight to cross-language comparison, more recent work "first reconstruct[s], then compare[s]"
each language's internal prehistory independently (p. 29–30).

---


---

## Korean — Established Historical-Linguistics Extraction: "The Formation of Korean" (Chapter 2, §§2.1–2.3)

**Source:** Ki-Moon Lee & S. Robert Ramsey, *A History of the Korean Language* (Cambridge University
Press, 2011), printed pp. 31–49 (PDF pp. 43–61). Covers Chapter 2 "The formation of Korean": §2.1
Old Chosŏn; §2.2 The Puyŏ and the Hán (§2.2.1 The Puyŏ languages, §2.2.2 The Hán languages); §2.3
The Three Kingdoms (§2.3.1 The *Samguk sagi*, §2.3.2 Koguryŏ incl. lexical strata and the
Koguryŏ-affiliation debate, §2.3.3 Paekche, §2.3.4 Kaya, §2.3.5 Silla, §2.3.6 Relationships between
the three languages: 'king' and 'city' terminology).

**Coverage note:** This is a diachronic academic monograph, not a teaching grammar — there are no
drill exercises to skip. Per the extraction spec's allowance for academic sources carrying their
real content in argumentative prose rather than vocabulary boxes, every historical-linguistic
argument in this range is captured as a "Grammar point"-equivalent subsection below, and every
actually-cited ancient lexical item / place-name / title form (with its era and kingdom/region
attribution, since that attribution is the entire analytical point of this chapter) is pulled into
the Vocabulary table. Confirmed non-overlapping with all 46 existing Korean `established/` files
(pre-checked by the dispatching orchestrator). Clean text layer (`pdftotext`, no cipher, no vision
reading) — Hangul/Hanja/Yale-romanization render correctly and are preserved as printed.

**A note on what these entries actually are:** almost every "vocabulary" item below is a
*reconstructed ancient morpheme or title*, known only from Chinese/Korean/Japanese historical
transcriptions (phonograms and/or semantic "hun" glosses), not a word in use in any living register
of modern Korean. `Usage Tier` is therefore `archaic` across the board, and `Weight/Frequency` is
`—` throughout (this is the opposite of frequency data — most of these words survive in exactly one
or two attested occurrences in the entire historical record). Reconstructed forms are marked with
`*` exactly as the source marks them.

---

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Chosŏn 朝鮮 | name of the earliest state in Chinese annals; later the dynastic/national name (Yi dynasty 1392–1910; still used by North Korea) | proper noun | archaic | — | Old Chosŏn, legendary founding traditionally dated 2333 BC | Old Chosŏn (near modern Pyongyang) | regional | grammar_reference | n/a | n/a | "Historians usually refer to it as 'Old Chosŏn'" to distinguish from later usages (p. 31–32). Meaning of the name itself is unrecoverable; characters are a Chinese transcription of a local name. |
| Asadal 阿斯達 (asatal) | Tan'gun's capital after moving it from Chosŏn; name of a nearby mountain | proper noun | archaic | — | Old Chosŏn (legendary) | Old Chosŏn | regional | grammar_reference | n/a | n/a | p. 32–33. `-tal` analyzed as a suffix resembling a Koguryŏ word for 'mountain'; `asa-` compared to MK *achom* 아 참 'morning' and Japanese *asa* 'id.' |
| *-tal* | '(suffix resembling) mountain' | suffix | archaic | — | Old Chosŏn / Koguryŏ-era comparison | Old Chosŏn | regional | grammar_reference | n/a | n/a | p. 32. Comparative, not independently glossed beyond the Asadal etymology. |
| wangkem 王儉 | title: 'ruler, sovereign' (used of Tan'gun) | noun (title) | archaic | — | Old Chosŏn (legendary) | Old Chosŏn | regional | grammar_reference | n/a | n/a | p. 33. `wang` 王 = Chinese 'king'; `kem` reasoned to be the native equivalent, "reinforced by its phonological resemblance to a Silla word for 'king'" (cf. Silla *-kan* below). |
| Suksin 肅愼 | ethnonym/language-group name: northern semi-nomadic tribes (incl. Ŭmnu, Mulgil, Malgal) | proper noun | archaic | — | ~3rd c. AD (Wei survey, AD 244); described in *Wei zhi* "Dong Yi zhuan" and *Hou Hanshu* (5th c.) | Manchuria / southern Siberia / northern Korean peninsula | regional | grammar_reference | n/a | n/a | p. 34–35. Not a single word of any Suksin-group language survives; even Tungusic affiliation is unconfirmed, only inferred from geography/appearance. |
| Puyŏ 夫餘 | ethnonym/language-group name; one of the "Puyŏ language group" (with Koguryŏ, Okchŏ, Ye) | proper noun | archaic | — | ~3rd c. AD (Wei survey) | Manchuria / northern Korean peninsula | regional | grammar_reference | n/a | n/a | p. 34–35. Chinese considered the Puyŏ friendly; described as the reference point for describing Koguryŏ, Okchŏ, Ye as linguistically similar. |
| Hán 韓 | ethnonym/language-group name covering the "Three Hán": Mahan, Chinhan, Pyŏnhan | proper noun | archaic | — | ~3rd c. AD (Wei survey) | southern Korean peninsula | regional | grammar_reference | n/a | n/a | p. 34, 35–36. Footnoted as transcribed *Hán* to distinguish the character 韓 from 漢 *Hàn* (the Chinese dynasty/ethnonym). |
| Mahan | one of the Three Hán; most numerous group | proper noun | archaic | — | ~3rd c. AD | southwest peninsula, north to modern Kyŏnggi | regional | grammar_reference | n/a | n/a | p. 35. Territory later became the kingdom of Paekche. *Dong Yi zhuan*: Chinhan language "is not the same as the Mahan." |
| Chinhan | one of the Three Hán | proper noun | archaic | — | ~3rd c. AD | southeast peninsula | regional | grammar_reference | n/a | n/a | p. 35. Silla arose from Chinhan lands. Sources disagree whether Chinhan and Pyŏnhan languages were similar (*Dong Yi zhuan*) or had "differences" (*Hou Hanshu*, 5th c.) — an explicit source-conflict the book flags (p. 35–36). |
| Pyŏnhan (Pyŏnjin) | one of the Three Hán | proper noun | archaic | — | ~3rd c. AD | southeast peninsula, mixed with Chinhan, some communities west of Chinhan beyond the Naktong River | regional | grammar_reference | n/a | n/a | p. 35. Generally identified with the later state of Kaya (Kara). |
| 買忽 *mayhwol* | place name: old name of modern Suwŏn (sound transcription) | proper noun | archaic | — | Koguryŏ period (pre-668); recorded Samguk sagi vol. 37 (compiled 1145) | Koguryŏ | regional | grammar_reference | n/a | n/a | p. 37–38. Paired in the same entry with the semantic (*hun*) transcription 水城 'water city' — the two-transcription method is this chapter's central philological technique for recovering Koguryŏ words. |
| 水城 | 'water city' — meaning-transcription of the same Suwŏn place name | compound (noun) | archaic | — | Koguryŏ period | Koguryŏ | regional | grammar_reference | n/a | n/a | p. 37–38. A *hun* 訓 (Jp. *kun*) reading: characters chosen for meaning, read as native words, not for their Chinese sound. |
| 買 *may/*mi | 'water' | noun | archaic | — | Koguryŏ period; recorded Samguk sagi vol. 37 | Koguryŏ | regional | grammar_reference | n/a | n/a | p. 38–39. Derived by comparing 買忽/水城 and 水谷城郡 一云 買旦忽. Middle Chinese readings reconstructed as *me:j, *mi', or *mji; MK-based estimate *may or *mi. Cognate set: Evenki *mū*, Manchu *muke*, Middle Mongolian *mören* 'lake, river', and (closer) Japanese *mi(du)* 'water' — cited as evidence of a Koguryŏ–Japanese link. |
| 忽 *hwol* | 'city' | noun | archaic | — | Koguryŏ period | Koguryŏ | regional | grammar_reference | n/a | n/a | p. 38–39, 49. Also given with Chinese reading [Chinese *xwət*, MK *hwol* 홀] on p. 49, compared to 溝漊 [Chinese *kəwluə*, MK *kwulwu* 구루] 'fortified city' from the *Wei zhi* as likely an older two-syllable variant of the same word. |
| 旦/頓/呑 *tan/*twon/*thon* | 'valley' | noun | archaic | — | Koguryŏ period | Koguryŏ | regional | grammar_reference | n/a | n/a | p. 39–40, 41. Three different phonograms for the same word across different place-name entries — cited as an example of transcriptional inconsistency. Compared to Old Japanese *tani* 'valley' (p. 41–42). |
| 十 德 *tek* | 'ten' | numeral | archaic | — | Koguryŏ period | Koguryŏ | regional | grammar_reference | n/a | n/a | p. 40, 43. From "Ten Valley District" 十谷縣 一云德頓忽. Also appears in the four-number comparative table with Old Japanese *topo* 'ten' (p. 43) — one of only four Koguryŏ numerals preserved. |
| 翼 於支 *eci* | 'wing' | noun | archaic | — | Koguryŏ period | Koguryŏ | regional | grammar_reference | n/a | n/a | p. 40. From "Wing Valley" 於支呑 一云翼谷 — a rare case where both sound and meaning indicators co-occur outside the standard dual-transcription pattern. |
| 內米 | 'pool' | noun | archaic | — | Koguryŏ period | Koguryŏ | regional | grammar_reference | n/a | n/a | p. 43. Compared to Tungusic reconstructions for 'lake, sea' (*namu, *lamu). |
| 難隱 *nanun* | 'seven' | numeral | archaic | — | Koguryŏ period | Koguryŏ | regional | grammar_reference | n/a | n/a | p. 43. Cognate to Tungusic *nadan* 'seven' and listed in the four-numeral table vs. Old Japanese *nana* 'seven'. |
| 那勿 *namwul* | 'lead (metal)' | noun | archaic | — | Koguryŏ period | Koguryŏ | regional | grammar_reference | n/a | n/a | p. 43. Compared to Old Japanese *namari* 'lead'. |
| 內/那/奴 | '(approx.) earth, dike' | noun | archaic | — | Koguryŏ period | Koguryŏ | regional | grammar_reference | n/a | n/a | p. 43. Three transcriptions of the same word, compared to Manchu *na* 'earth'. |
| 密 *mil* | 'three' | numeral | archaic | — | Koguryŏ period | Koguryŏ | regional | grammar_reference | n/a | n/a | p. 43. One of the four preserved Koguryŏ numerals; cf. Old Japanese *mi* 'three'. Lee & Ramsey call the whole four-number set "most startling of all" the Koguryŏ–Japanese resemblances. |
| 于次 *wucha* | 'five' | numeral | archaic | — | Koguryŏ period | Koguryŏ | regional | grammar_reference | n/a | n/a | p. 43. Cf. Old Japanese *itu* 'five'. |
| 於斯 *esa* | 'horizontal' | adjective/noun | archaic | — | Koguryŏ period | Koguryŏ | regional | grammar_reference | n/a | n/a | p. 44. Cf. MK *es-* 엇- 'crosswise' — one of "at least thirty" Koguryŏ-to-Middle-Korean comparisons the authors call secure. |
| 也次 *yacho* | 'mother' | noun | archaic | — | Koguryŏ period | Koguryŏ | regional | grammar_reference | n/a | n/a | p. 44. Cf. MK *ezi* 어 'mother, parent'. |
| 波兮/波衣/巴衣 *phahyey/phauy* | 'boulder' | noun | archaic | — | Koguryŏ period | Koguryŏ | regional | grammar_reference | n/a | n/a | p. 44. Three transcriptions of the same word. Cf. MK *pahwoy* 바회 'boulder'. |
| 別 *pyel* | 'pile, layer' | noun | archaic | — | Koguryŏ period | Koguryŏ | regional | grammar_reference | n/a | n/a | p. 44. Cf. MK *pol* 'pile, layer'. |
| 首 *sywu* | 'ox' | noun | archaic | — | Koguryŏ period | Koguryŏ | regional | grammar_reference | n/a | n/a | p. 44. Cf. MK *sywo* 쇼 'ox'. |
| 於乙 | 'spring (of water)' | noun | archaic | — | Koguryŏ period | Koguryŏ (compared to Silla) | regional | grammar_reference | n/a | n/a | p. 44. Corresponds to Silla element 乙 'well', while unrelated MK forms (*soym* 'spring', *wumul* 우믈 'well') show the Koguryŏ/Silla pairing is closer than either is to standard MK — cited as evidence the Koguryŏ lexical strata genuinely connect to the Korean mainstream, not just Japanese. |
| 夫里 *puri* | 'plain' | noun | archaic | — | Paekche period (pre-663 conquest); recorded Samguk sagi vol. 36 (post-Silla-unification layer) | Paekche | regional | grammar_reference | n/a | n/a | p. 44–45. Corresponds to Silla *pul* 'plain'; two-character transcription argued to show a preserved syllable-final vowel in Paekchean. |
| kuma 久麻 | 'bear' | noun | archaic | — | Paekche period; transcribed in the Nara-period *Nihon shoki* (720) | Paekche (via Japan) | regional | grammar_reference | n/a | n/a | p. 45. Cf. Japanese *kuma* 'bear' directly. |
| nuri | 'ford' | noun | archaic | — | Paekche period (*Nihon shoki*, 720; some forms via a late-13th-c. katakana compendium) | Paekche (via Japan) | regional | grammar_reference | n/a | n/a | p. 45. |
| sema 斯麻 | 'island' | noun | archaic | — | Paekche period (*Nihon shoki*) | Paekche (via Japan) | regional | grammar_reference | n/a | n/a | p. 45, also listed again p. 46 compared to MK *syem* 셤 'island'. |
| nirimu 爾林 | 'master' | noun | archaic | — | Paekche period (*Nihon shoki*) | Paekche (via Japan) | regional | grammar_reference | n/a | n/a | p. 45. |
| mure 武禮 | 'mountain' | noun | archaic | — | Paekche period (*Nihon shoki*) | Paekche (via Japan) | regional | grammar_reference | n/a | n/a | p. 45. |
| aripisi | 'south' | noun | archaic | — | Paekche period (*Nihon shoki*) | Paekche (via Japan) | regional | grammar_reference | n/a | n/a | p. 45, 46. Compared on p. 46 to MK *alph* 앒 'front', not 'south' directly — the authors note the semantic drift themselves only implicitly via the comparison table. |
| sasi | 'walled city' | noun | archaic | — | Paekche period (*Nihon shoki*) | Paekche (via Japan) | regional | grammar_reference | n/a | n/a | p. 45, 49. Paralleled by Old Japanese *sasi* 'fortification, fort' (p. 49), argued as a loan from the peninsula into Japanese, not the reverse. |
| 熊津 / kwòmá 고마 | old Paekche capital name 'Bear Ford'; transcribed form | proper noun | archaic | — | Paekche period, attested via the Middle Korean text *Yongbi ŏch'ŏn ka* (1447) | Paekche | regional | grammar_reference | n/a | n/a | p. 45–46. `kwòmá` taken as an older form of MK *kwǒm* :곰 'bear' (tone shows regular MK development); compared further to Japanese *kuma* 'bear' (same second-syllable vowel). |
| 珍 (+ 惡 *-ak*) | 'stone' (semantic character + phonetic suffix marker) | noun | archaic | — | Paekche period; recorded Samguk sagi vol. 36 | Paekche | regional | grammar_reference | n/a | n/a | p. 46. From "石山縣本百濟珍惡山縣" ('Stone Mountain Prefecture was originally Paekche "珍惡 Mountain" Prefecture'). Compared to MK *twǒlh* :돓 'stone' — the authors use this to support reconstructing an *-k final in the MK form (*twòlók > twǒlh), citing the modern southern dialect reflex [tok] (North Ch'ungch'ŏng to Cheju) as corroboration. |
| 沙 *sa* | 'new' | adjective | archaic | — | Paekche period | Paekche | regional | grammar_reference | n/a | n/a | p. 46. Cf. MK *say* 새 'new'. |
| 勿居 *mwulke* | 'clear' | adjective | archaic | — | Paekche period | Paekche | regional | grammar_reference | n/a | n/a | p. 46. Cf. MK *molk-* - 'clear'. |
| 毛良 *molyang* | 'high' | adjective | archaic | — | Paekche period | Paekche | regional | grammar_reference | n/a | n/a | p. 46. Cf. MK *molo* 'ridge, ridgepole' (semantic narrowing/shift from 'high' to a specific landform term). |
| arosi | 'below' | adverb/noun | archaic | — | Paekche period (*Nihon shoki*) | Paekche (via Japan) | regional | grammar_reference | n/a | n/a | p. 46. Cf. MK *alay* 아래 'below'. |
| *elaha* 어라하 於羅瑕 | 'king' (title used by the Paekche ruling/Puyŏ elite) | noun (title) | archaic | — | Paekche period; recorded in the *Zhou Shu* 周書 (636) "Description of Strange Lands" | Paekche (elite stratum) | regional | grammar_reference | n/a | n/a | p. 44–45. Explicitly contrasted in the same source with *kenkilci* — direct Chinese-recorded evidence that Paekche's rulers and ruled spoke different languages (Puyŏ superstratum over a Hán substratum). |
| *kenkilci* 건길지 鞬吉支 | 'king' (title used by the Paekche common people) | noun (title) | archaic | — | Paekche period (*Zhou Shu*, 636) | Paekche (commoner stratum) | regional | grammar_reference | n/a | n/a | p. 45, 48–49. The *-kilci* 吉支 element is also attested independently in the *Nihon shoki* (720) as Japanese *kisi*, and compared to MK *kuyco* 긔 'king' (a 1575 gloss in the *Kwangju* edition of the *Thousand Character Classic*) — all three ( *kilci*, *kisi*, *kuyco*) argued to be transcriptions of one lexical item. The prefix *ken* 鞬 is tentatively compared to MK *khun* 큰 'great'. |
| 梁 | 'gate' (Kaya word, transcribed via borrowed Silla sound value) | noun | archaic | — | Kaya period (pre-6th-c. absorption by Silla); recorded Samguk sagi vol. 34 | Kaya | regional | grammar_reference | n/a | n/a | p. 46–47. The ONLY word of the Kaya language preserved anywhere, from an explanatory note on place name 旃檀梁 ("Sandalwood [something]"): "城門名 加羅語謂門爲梁云" ('Name of the fortress gate. In the Kaya language "gate" is called 梁.'). The character 梁 normally transcribes Silla's word for 'ridge' (ancestral to MK *twol* 돌); its sound value was borrowed to represent the unrelated Kaya word for 'gate' — a transcriptional strategy called *kungana* in Japan. Tantalizingly resembles Japanese *to* 'gate, door'. |
| Sŏrabŏl 徐羅伐 / Sŏbŏl 徐伐 *syepel* | name of Silla's founding statelet; also glossed as the word for 'capital' | proper noun | archaic | — | Silla founding period; earliest version in the 13th-c. *Samguk yusa* | Silla | regional | grammar_reference | n/a | n/a | p. 47. Sŏbŏl given explicitly as "an alternate form of the name Sŏrabŏl... the word there for 'capital'" — i.e. the statelet's own name doubled as the common noun for 'capital city'. |
| 皆 *kay* ('king', Koguryŏ) | 'king' | noun (title) | archaic | — | Koguryŏ period | Koguryŏ | regional | grammar_reference | n/a | n/a | p. 48–49. Part of a four-kingdom comparative title table: Koguryŏ 皆 (Chinese *kəɨj*, MK *kay*), Puyŏ 加 (*kaɨ* / *ka*, title suffix), Paekche-elite 瑕 (*ɣaɨ* / *ha*, 'king' suffix), Silla 干 (*kan* / *kan*, 'king' suffix) — argued to be a single cognate set, possibly comparable to Middle Mongolian *qaɤan, qan, qa* 'monarch', reflecting widespread cultural borrowing of a ruler-title root rather than four unrelated words. |
| 加 *kaɨ/ka* (title suffix, Puyŏ) | title suffix, part of the 'king'-root cognate set | suffix | archaic | — | Puyŏ period | Puyŏ | regional | grammar_reference | n/a | n/a | p. 48–49. See 皆 entry above for the full comparative set. |
| 瑕 *ɣaɨ/ha* ('king' suffix, Paekche elite) | 'king' title suffix | suffix | archaic | — | Paekche period | Paekche (elite) | regional | grammar_reference | n/a | n/a | p. 48–49. See 皆 entry above. |
| -干 *kan* ('king' suffix, Silla) | 'king' title suffix | suffix | archaic | — | Silla period | Silla | regional | grammar_reference | n/a | n/a | p. 48–49. Seen in Silla royal titles 居西干 and 麻立干 (Samguk sagi/Samguk yusa). Also compared to Middle Mongolian *qan*. |
| 尼師今 / 尼叱今 | Silla royal title ('king') | noun (title) | archaic | — | Silla period | Silla | regional | grammar_reference | n/a | n/a | p. 49. The element *-今* compared to Early Middle Chinese reconstruction (Pulleyblank 1991) and to the second syllable of MK *nimkum* 님금 'king' (see next entry) — a different etymological strand from the 干 *-kan* titles, showing Silla itself used multiple co-existing title roots. |
| nimkum 님금 | 'king' | noun | archaic | — | Middle Korean period (direct descendant of Silla title vocabulary) | Silla → Old/Middle Korean | national | grammar_reference | n/a | n/a | p. 49. Compound of *nim* 님 'ruler' + the element surviving in Silla 尼師今/尼叱今. Old Japanese *kimi* 'prince, lord' argued to be a direct borrowing of the Silla term. |
| kuyco 긔 | 'king' | noun | archaic | — | 1575 (gloss in the Kwangju edition of the *Thousand Character Classic*); reflects earlier Paekche-linked vocabulary | Korea (national, post-unification) | national | grammar_reference | n/a | n/a | p. 49. See *kenkilci* entry above — part of the *kilci/kisi/kuyco* cognate set. |
| 己 *ki* (Paekche, 'fortified city') | 'fortified city' | noun | archaic | — | Paekche period | Paekche | regional | grammar_reference | n/a | n/a | p. 49. [Chinese *ki'*, MK *ki* 기]. Part of a three-kingdom comparative set for 'city' alongside Koguryŏ 忽/溝漊 and Silla *cas*; argued to show the three kingdoms used three genuinely distinct words for the same fortification concept. |
| cas 잣 (Silla, 'fortified city') | 'fortified city' | noun | archaic | — | Silla period; attested in the 7th-c. poem "Song of the Comet," recorded in the 1285 *Samguk yusa* | Silla | regional | grammar_reference | n/a | n/a | p. 49. Ancestral to MK *cas* 잣. |

**Morpheme breakdown.** `nimkum` 님금 = `nim` 님 ('ruler') + `-kum` 금 (element cognate to the second
syllable of Silla royal titles 尼師今/尼叱今) — a rare case in this chapter where the Middle Korean
reflex itself (rather than the ancient form) shows clear compositional structure, used by the
authors to argue that a Silla title-root survived into the standard Korean lexicon via compounding
rather than being replaced outright (p. 49).

### Grammar points

*(These are the historical-linguistic arguments of the chapter, substituting for the grammatical
rules a teaching text would carry — see the extraction spec's allowance for academic sources. Pages
cited are printed pages.)*

#### Old Chosŏn and the limits of legendary-era etymology (pp. 31–33)

Chosŏn is the earliest state named in Chinese historical annals, central to Korea's foundation myth
(Tan'gun founding it in 2333 BC by traditional reckoning) but occupying only a small part of the
modern Korean peninsula. The authors stress a key methodological point for the whole chapter:
"Chosŏn" itself is unrecoverable as a native word — the characters are almost certainly just a
Chinese phonetic transcription of a local name, and even the most suggestive-looking etymological
clue (that the first character 朝 can mean 'morning', echoing the *asa-* 'morning' comparison in
Asadal) is undercut by the fact that Chinese readings of 朝 in this name context mean only 'tide' or
'court', never 'morning' (p. 33). The lesson generalized across the chapter: proper-name
transcriptions tempt confident etymology but rarely support it without independent corroboration.

#### The three-way Chinese linguistic classification of the peninsula (pp. 34–36)

Following the Wei Empire's ethnographic survey after its AD 244 victory over Koguryŏ (recorded in
the *Wei zhi*'s "Description of the Eastern Barbarians," corroborated by the 5th-century *Hou
Hanshu*), Chinese sources divided the peninsula's indigenous languages into three groups: Suksin
(northern, semi-nomadic, possibly but not provably Tungusic — no words survive at all), Puyŏ
(including Koguryŏ, Okchŏ, and Ye, explicitly described in the sources as similar to each other "in
language and in many things"), and Hán (the "Three Hán": Mahan, Chinhan, Pyŏnhan, in the southern
peninsula, less politically developed and more exotic to Chinese observers). The authors flag an
explicit source disagreement about internal Hán relationships: the *Dong Yi zhuan* says Chinhan and
Pyŏnhan "resemble each other" while Mahan differs, but the *Hou Hanshu* instead says Chinhan and
Pyŏnhan "have differences" — used as a case study in how unreliable ancient outsider-ethnography
can be as linguistic evidence (p. 35–36). Historically, the Three Hán coalesced into Paekche
(from Mahan) and Silla (from Chinhan); Pyŏnhan became Kaya, later absorbed by Silla in the 6th
century.

#### The *Samguk sagi*'s dual-transcription method as a philological recovery technique (pp. 37–39)

Korea's oldest extant history, the *Samguk sagi* (compiled by Kim Pusik, 1145), preserves most of
the chapter's linguistic evidence in its four geography monographs (vols. 34–37). Crucially, a
Koguryŏ place name in vol. 37 was frequently given in two parallel transcriptions: one set of
phonograms approximating the *sound* of the native name, and one set of characters (*hun* 訓
reading; Japanese *kun*) chosen instead to represent its *meaning*. Example: Suwŏn appears as both
買忽 (sound: *mayhwol*) and 水城 (meaning: 'water city'). This bipartite system lets philologists
triangulate both the sound and the gloss of individual Koguryŏ morphemes (e.g. isolating 買 'water'
and 忽 'city'). Vol. 35, by contrast, records the *later* Sillan-standardized versions of these same
place names after King Kyŏngdŏk's 757 reform forced every place name into a two-character,
Sino-Korean-read, Chinese-style form — meaning a name like 水城 could appear in vol. 35 read
Chinese-style (Sino-Korean) even though the structurally identical characters in vol. 37 were a
native-language *hun* gloss. The authors treat this vol. 37/vol. 35 contrast as the single most
important key to recovering Koguryŏ vocabulary at all (p. 37–39).

#### The Koguryŏ-corpus problem: inconsistent, unique, and non-recoverable transcriptions (pp. 39–41)

Even granting the dual-transcription method, roughly 100 Koguryŏ words total have been recovered
from place names, and the corpus is "very much tentative": (1) a single word is not always
transcribed the same way across entries — e.g. 'valley' appears as 旦, 頓, or 呑 in different place
names; (2) some transcriptions are unique, attested exactly once, with no cross-checking
possibility (e.g. 'ten' *tek* 德 and 'wing' *eci* 於支); (3) phonograms alone can never fully
determine a word's phonemic structure, only approximate it via either Middle Chinese or Middle
Korean traditional readings, which can diverge (e.g. 'water' reconstructed as *me:j/*mi'/*mji from
Chinese vs. *may/*mi from the MK-reading tradition) (p. 39–40).

#### The territorial-attribution problem for Koguryŏ place names (pp. 40–42)

A serious methodological objection: place names recorded as "Koguryŏ" were only located within
Koguryŏ's later-controlled territory (in some cases controlled for under 200 years, 475–668) — they
could in principle preserve an earlier, non-Koguryŏ substrate language rather than genuine Koguryŏ
vocabulary (the authors' own analogy: Sapporo is a Japanese city with an Ainu name; Chicago and
Terre Haute aren't English morphemes). The counter-argument the authors endorse rests not on
territorial control but on the *transcription method itself*: the bipartite sound/meaning system is
historically unique to Koguryŏ-sphere writing practice (Paekche records show no such system), so a
hun-transcribed place name implies Koguryŏ scribes devised it for their own language — not that
some other group's name was merely relabeled. Confirming direct evidence remains elusive: no
identifiable morphemes have ever been found in Koguryŏ's own stone inscriptions (e.g. the
Kwanggaet'o Stele), only in the much later, Silla-filtered *Samguk sagi* record (p. 40–42).

#### Koguryŏ's three lexical strata and the Korean/Japanese/Altaic affiliation debate (pp. 42–44)

The ~100 recovered Koguryŏ words split into (at least) three comparative strata: (1) words
resembling Altaic/Tungusic forms (e.g. 'water' vs. Evenki *mū*, Manchu *muke*; 'seven' vs. Tungusic
*nadan*; 'earth' vs. Manchu *na*); (2) words resembling Old Japanese, most strikingly the four
surviving numerals (3, 5, 7, 10) which "look remarkably like Japanese" and which the authors call a
resemblance "hardly accidental" — strong evidence a Japanese-related language was once spoken on
the peninsula; (3) at least thirty words with secure correspondences to Middle Korean, and in one
case ('spring'/'well') an even closer match to the separate Silla corpus than to mainstream MK,
tying Koguryŏ concretely into Korean's own lineage. The authors' own conclusion, stated explicitly:
since all three strata are too large and lexically basic to be mere cultural borrowing layers, "a
more logical conclusion is that Koguryŏan was related not just to Korean or Japanese, but to both"
— possibly a language intermediate between what became Korean and Japanese (p. 43–44). This
directly informs the chapter's running "who were Korean's ancestors" question raised on p. 31.

#### Paekche: a Puyŏ-elite superstratum over a Hán-commoner substratum (pp. 44–46)

Chinese sources (*Liang Shu*, 629) describe Paekche's ruling-class language as "about the same" as
Koguryŏ's, while Paekche's population arose from Mahan (a Hán-group polity). The *Zhou Shu* (636)
gives direct textual proof of a two-tier linguistic situation: the Paekche king's *surname* is
"Puyŏ," he is called *elaha* 於羅瑕 by implication of elite usage, but "the people call him"
*kenkilci* 鞬吉支 — two unrelated words for the same referent recorded in the same source, read by
the authors as decisive evidence that Paekche's Puyŏ-descended rulers and Hán-descended subjects
spoke different languages. Despite this, the handful of surviving Paekche words "strongly resemble
Sillan," implying the ruling language influenced but never displaced the base Hán language —
Paekchean is therefore characterized as fundamentally Hán with a Puyŏ superstratum (p. 44–45).
Paekche's own place-name record is comparatively poor (Samguk sagi vol. 37 rarely gives Paekche
names the dual sound/meaning transcription used for Koguryŏ), so most Paekche lexical evidence
instead comes from vol. 36's post-conquest renamings, from the Japanese *Nihon shoki* (720,
preserving Paekche refugee/envoy vocabulary), and from a single Middle Korean attestation (the 1447
*Yongbi ŏch'ŏn ka*'s transcription of the old capital name 熊津 as *kwòmá*).

#### Kaya: a state known from exactly one surviving word (pp. 46–47)

Kaya (Kara/Mimana), a fourth, smaller Three-Kingdoms-era polity on the lower Naktong River,
ultimately absorbed by Silla in the 6th century, is linguistically almost a complete blank — the
*entire* preserved Kaya lexicon is a single word, 'gate', recoverable only from an explanatory gloss
in *Samguk sagi* vol. 34 that borrows the Silla character 梁 (normally transcribing Silla 'ridge')
purely for its sound value to render the unrelated Kaya word. The authors flag this as a real
transcriptional strategy (*kungana* in Japanese usage) rather than a scribal error, and note the
tantalizing — but entirely unconfirmable from one data point — resemblance to Japanese *to* 'gate,
door' (p. 46–47). Kaya's broader historical relationship (Japanese vassal/colony per the *Nihon
shoki*, vs. a Paekche-aligned client per some Korean historians) is presented as contested and
unresolved by this single word.

#### Silla as the direct lineage-ancestor of Old/Middle Korean (pp. 47–48)

Silla began as the small Chinhan statelet Sŏrabŏl (at modern Kyŏngju) and expanded by conquest —
absorbing Kaya (6th c.), then Paekche and Koguryŏ (both 7th c., Koguryŏ falling in 668) — becoming
the first polity to politically unify the whole peninsula. The authors' central claim: this
political unification is "the most important event in the formation of Korean" because it initiated
(though the pace/completeness is unknowable) linguistic unification around Sŏrabŏl speech as the
lingua franca, explicitly allowing for lingering local substrate traces (Koguryŏ, Paekche, Kaya, or
otherwise-unrecorded languages) possibly surviving into modern regional dialects as an open,
explicitly labeled "romantic" possibility rather than a proven fact (p. 47–48).

#### Comparative title reconstruction: 'king' across the Three Kingdoms + Puyŏ (pp. 48–49)

The authors lay out two parallel, non-overlapping etymological strands for royal titles. Strand 1:
a widely shared ruler-title root appears as Koguryŏ 皆 *kay*, Puyŏ 加 *ka* (suffix), Paekche-elite 瑕
*ha* (suffix), and Silla -干 *kan* (suffix) — argued to be genuinely cognate, and possibly comparable
to Middle Mongolian *qaɤan/qan/qa*, reflecting a borrowed/shared prestige-title vocabulary across
the whole region rather than coincidence. Strand 2: a separate, non-elite Paekche title *kenkilci*
鞬吉支 (specifically contrasted in the sources with the elite term *elaha*) recurs independently in
Japan as *kisi* (*Nihon shoki*, 720) and in a 1575 Middle Korean dictionary gloss *kuyco* — three
transcriptions the authors treat as one lexical item surviving along a completely different line
of descent than Strand 1. Separately, Silla also used *-今* titles (尼師今/尼叱今), argued to be the
direct ancestor of the *-kum* element in standard MK *nimkum* 'king' (itself *nim* 'ruler' + that
element) — meaning Silla alone had (at least) two coexisting, etymologically unrelated title roots
in use simultaneously (-干 *kan* vs. -今). Old Japanese *kimi* 'prince, lord' is proposed as a direct
borrowing of the Silla *-kum*-type term, not an independent Strand-2-type cognate (p. 48–49).

#### Comparative lexical reconstruction: 'fortified city' across the Three Kingdoms (p. 49)

Each of the three kingdoms is shown using a genuinely distinct word for 'fortified city,' treated as
the chapter's closing demonstration that Koguryŏ, Paekche, and Sillan were "representing three
separate corpora" rather than mutually intelligible dialects of one language even where their
vocabularies overlap elsewhere: Koguryŏ 忽/溝漊 (two transcriptions of one word, the two-syllable
form perhaps older), Paekche 己 *ki*, and Silla *cas* 잣 (attested in the 7th-c. "Song of the
Comet," preserved in the 1285 *Samguk yusa*). The authors close the chapter by noting that Old
Japanese independently preserves two words for 'fortification' (*kı̈* and *sasi*) that closely
parallel the Paekche and Silla forms respectively — read as loans into Japanese from the peninsula,
reinforcing the chapter's recurring Korea→Japan contact thread rather than a shared inheritance.

---


---

## Korean — Established Vocabulary/Grammar: A History of the Korean Language, Chapter 3 "Old Korean" (3.1–3.6)

**Source:** Ki-Moon Lee & S. Robert Ramsey, *A History of the Korean Language* (Cambridge University
Press, 2011), printed pp. 50–76 (PDF pp. 62–88). Academic historical-linguistics monograph
(diachronic), not a teaching grammar. Covers §3.1 Sources, §3.2 Transcription methods, §3.3
Phonology, §3.4 Sino-Korean, §3.5 Grammar, §3.6 Vocabulary for the Old Korean period (Silla-based,
roughly 4th–10th c., with the richest attestation from the Unified Silla period, 7th–10th c.).

**Coverage note:** every grammar point and every distinct reconstructed/attested vocabulary item,
morpheme, and particle discussed in this page range, plus every explicit era/region annotation the
source itself makes (Silla vs. broader Three Kingdoms, specific hyangga/idu/stele sources, modern
dialect reflexes such as Cheju). This era is almost entirely pre-Hangul (invented 1446): all forms
below are transcribed via Chinese-character phonograms/logograms (hyangch'al, idu, kugyŏl) and are
reconstructed by the source via Middle Korean reflexes and cross-script comparison (Chinese
transcriptions, Old Japanese loanwords). Hanja is preserved exactly as printed; Middle Korean/Yale
romanized forms and Hangul are preserved as given by the source, including obsolete jamo (ㅿ, ㅸ,
ㆍ, etc.) where the source's text layer rendered them correctly. This source has a clean, confirmed
text layer for this range — no cipher, no vision-reading was needed. Repeated restatements of the
same claim across adjacent paragraphs are not re-extracted as separate items.

---

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 推火 (old name) / 密城 (reformed) | 'push' (place-name element) | noun/place-name morpheme | core | — | Old Korean (Silla, pre-757) | Silla (Milsŏng county) | local | grammar_reference | n/a | n/a | p.52. Old name written with meaning-characters (hun), not phonograms: 密 (reformed) read Chinese-style *mil*, resembling MK *mil-* 'push'; 推 in old name means 'push' — so old transcription is judged semantic, not phonetic. |
| 吉同 (old name) / 永同 (reformed) | 'long' (place-name element) | noun/place-name morpheme | core | — | Old Korean (Silla, pre-757) | Silla (Yŏngdong county) | local | grammar_reference | n/a | n/a | p.52. Opposite case from 推火: 吉 in old name is a *phonogram* read *kil*, matching MK *kil-* 'long'; reformed name 永 'long' confirms the gloss. |
| 一利/里 (old name, in 一利郡/里山郡) / 星山 (reformed) | 'star' | noun/place-name morpheme | core | — | Old Korean (Silla, pre-757) | Silla (Sŏngsan county) / South Ch'ungch'ŏng (modern dialect reflex) | regional | grammar_reference | n/a | n/a | p.52. Reformed 星山 'Star Mountain' suggests 一利 were phonograms for an Old Silla word for 'star,' linked to modern dialect *ili-nay* 'Milky Way' (lit. 'star stream'), still used in South Ch'ungch'ŏng. |
| 朴 (Pak) | 'gourd' | noun | core | — | Old Korean (Silla, legendary/foundational) | Silla | local | grammar_reference | n/a | n/a | p.52–53. Samguk sagi etymology for the Silla royal surname Pak: "the people of [Silla] call a gourd *pak*"; founder was named for the gourd-like egg he was born from. Source flags this kind of foundation legend as unresolvable as literal etymology. |
| 三月中 | 'in the third month' | phrase (locative construction) | archaic | — | Old Korean (Three Kingdoms period, Koguryŏ-crafted, 451) | Koguryŏ (object excavated from a Silla tomb) | regional | grammar_reference | n/a | n/a | p.54. Earliest known idu-type manipulation: engraving on a silver box; 中 is thought to represent a locative particle attached after a Chinese-order time phrase. |
| 必于 | 'although' | particle/conjunction (idu function word) | archaic | — | Early idu tradition (dated example 1395, post-OK but continuous system) | — | — | grammar_reference | n/a | n/a | p.53–54. Read *pilok*; a Korean equivalent substituted for the Chinese concessive, illustrating idu's method of swapping in Korean function words. |
| 乙 (accusative, idu use) | object marker | particle (case) | core | — | Old Korean through idu tradition | — | — | grammar_reference | n/a | n/a | p.53–54, 71. Read *ul*; added after the grammatical object in idu translation. Same phonogram is the main Old Korean accusative particle (see particle table entry below). |
| 爲去乃 | 'do, but' | verb + conjunctive ending (idu) | archaic | — | idu tradition (1395 example) | — | — | grammar_reference | n/a | n/a | p.53–54. Read *hokena*; combines the verb 'do' with a concessive/contrastive ending. |
| 有去乙 | 'exist (there are)...' | verb + ending (idu) | archaic | — | idu tradition (1395 example) | — | — | grammar_reference | n/a | n/a | p.53–54. Read *iskenul*. |
| 之 | sentence-final/verb-ending marker | particle (verb ending, early phonogram) | archaic | — | Old Korean (earliest: Imsin sŏgi sŏk stele, 552 or 612) | Silla | local | grammar_reference | n/a | n/a | p.55. Oldest attested idu function-word marker; in the 758 Karhang-temple inscription probably equates to the morpheme later written 齊, and by late Chosŏn idu readings became *-cyey/-cye*, whose modern reflex is the finite verb ending *-ce* still found in the **Cheju dialect**. |
| 旀 | '-mye, does/says/is and...' | particle (conjunctive verb ending) | core | — | Old Korean (Karhang temple stele, 758) | Silla | local | grammar_reference | n/a | n/a | p.56, 72. Read *mye* in idu; represents the MK (and Contemporary Korean) coordinate conjunctive ending *-mye* 며, formed from nominalizer *-m* + particle *ye*. |
| 在 | adnominal/copular verb 'to be' | verb (bound stem) | core | — | Old Korean (Karhang temple stele, 758) | Silla | local | grammar_reference | n/a | n/a | p.56. Read *kyen* 견 in later texts, functioning like the modern copular adnominal *i.n* 인; the underlying stem *kye-* 겨- survives in MK only as the bound honorific existential *kyesi-* 겨시- (Contemporary *kyeysi-* 계시다). |
| 節 | 'time, occasion' | noun | core | — | Old Korean (South Mountain stele, Kyŏngju, 591) | Silla | local | grammar_reference | n/a | n/a | p.55. Read *tiwuy* 디위 in later idu texts; one of several characters in this inscription (along with 以, 敎, 令, 爲) resembling later idu usage rather than the earlier, sparser Imsin-stone stage. |
| 以 | instrumental particle | particle (case) | core | — | Old Korean (South Mountain stele, 591, onward) | Silla | local | grammar_reference | n/a | n/a | p.55. |
| 者 | (possible) topic marker | particle | core | — | Old Korean (South Mountain stele, 591) | Silla | local | grammar_reference | n/a | n/a | p.55. Source flags this reading as a possibility, not certain. |
| 吏讀 (idu) | the idu writing system itself | proper noun (metalinguistic term) | technical | — | term first attested 1444 (post-Hangul); system itself Three Kingdoms–Chosŏn | Korea (continuous use into 19th c.) | national | grammar_reference | n/a | n/a | p.56. All transcriptions of the word begin with 吏 'clerk'; source rejects the traditional attribution of idu's invention to 7th-c. Sŏl Ch'ong as legend, since earlier idu examples predate him. |
| 鄕歌 (hyangga) | 'local songs' — the Silla vernacular poetic genre | proper noun / literary genre term | literary | — | Old Korean (composed 7th–10th c.; 11 more composed early Koryŏ, 963–967, but counted as Silla poetry) | Silla | national | grammar_reference | n/a | n/a | p.51, 57. Only 25 hyangga survive: 14 in the 13th-c. Samguk yusa, 11 in the biography of the monk Kyunyŏ. |
| 鄕札 (hyangch'al) | 'local letters' — the native Silla writing system used for hyangga | proper noun / metalinguistic term | technical | — | term attested early Koryŏ (retroactive label; no Silla text names the system) | Silla | national | grammar_reference | n/a | n/a | p.57–58. Combines the same transcription strategies already used for place names, idu, and kugyŏl annotation; compared to Japanese man'yōgana use in the Man'yōshū. |
| 建牟羅 | a type of fortification | noun | core | — | Old Korean (per Chinese ethnographic source, Liang shu, 7th c. compilation describing Silla) | Silla | local | grammar_reference | n/a | n/a | p.58. Uninterpretable beyond the gloss given by the Chinese source. |
| 啄評 | Sillans' own villages (vs. outsiders') | noun | core | — | Old Korean (Liang shu) | Silla | local | grammar_reference | n/a | n/a | p.58. Uninterpretable. |
| 邑勒 | villages of outsiders | noun | core | — | Old Korean (Liang shu) | Silla | local | grammar_reference | n/a | n/a | p.58. Glossed by the Chinese source as corresponding to Chinese 郡 'county' / 縣 'prefecture'; uninterpretable as transcription. |
| 遺子禮 | officials' hats | noun | core | — | Old Korean (Liang shu) | Silla | local | grammar_reference | n/a | n/a | p.58. Uninterpretable. |
| 尉解 | jackets | noun | core | — | Old Korean (Liang shu) | Silla | local | grammar_reference | n/a | n/a | p.58. Likely cognate with 16th-c. *wuthuy* 우틔 'clothes' (word still found in North Korean dialects). |
| 柯半 | trousers | noun | core | — | Old Korean (Liang shu) | Silla | local | grammar_reference | n/a | n/a | p.58. Earlier form of 15th-c. *kowoy* 외 < *koWoy; also transcribed 珂背 in the 12th-c. Chinese *Jílín lèishì*. |
| 洗 | boots | noun | core | — | Old Korean (Liang shu) | Silla | local | grammar_reference | n/a | n/a | p.58. Identified with 15th-c. *sin* 신 'shoes.' |
| -今 (phonogram, Silla word for 'king') | 'king' (second syllable of a compound) | noun (bound morpheme) | core | — | Old Korean (loaned into Old Japanese) | Silla | transnational | grammar_reference | n/a | n/a | p.58–59. Phonogram [Chinese *kim*]; cognate with the second syllable of MK *nimkum* 님금 'king.' Source: Old Japanese *kimi* 'prince, lord' is believed borrowed from this Silla form. |
| (Sillan word ancestral to) 잣 cas | 'fortress, fortified city' | noun | core | — | Old Korean → Middle Korean | Silla | national | grammar_reference | n/a | n/a | p.59. Source of Old Japanese loanword *sasi* 'fortified city.' |
| (Silla word for 'county') → 고올 koWol | 'county/district' | noun | core | — | Old Korean → Middle Korean → Contemporary | Silla | national | grammar_reference | n/a | n/a | p.59. Became MK *koWol* 'district, village' → Contemporary *kwoul* 고을 'district.' Source of Old Japanese loanword *kopori* 'county.' |
| 夜音 | 'night' | noun | core | — | Old Korean (Silla hun-reading convention) | Silla | national | grammar_reference | n/a | n/a | p.60–61, 63. 夜 is a meaning-indicator ('night'); 音 (*um*) is a non-syllabic phonogram cueing the final consonant *-m*. MK reflex: *pam* 밤 'night.' |
| 日尸 | 'day' | noun | core | — | Old Korean (Silla) | Silla | national | grammar_reference | n/a | n/a | p.61–62. 日 is the hun meaning-indicator; 尸 marks a syllable-final liquid (*l*/*r*). MK reflex *nal* 날 'day.' |
| 道尸 | 'road' | noun | core | — | Old Korean (Silla) | Silla | national | grammar_reference | n/a | n/a | p.61–62, 72. Same pattern as 日尸; MK reflex *kil* 길 'road.' Also appears in the hyangga "Song in Admiration of the Knight Chukchi" (慕理尸 心未 行乎尸 道尸, 'the road that [my] longing heart follows'). |
| 金 | 'metal' | noun | core | — | Old Korean (Silla hun convention) | Silla | national | grammar_reference | n/a | n/a | p.63. MK reflex *swoy* 쇠 'metal.' |
| 谷 | 'valley' | noun | regional | — | Old Korean (Silla) vs. Middle Korean | Silla (Old Korean reading) / general (Middle Korean reading) | national | grammar_reference | n/a | n/a | p.63. Divergent hun reading: Silla read it as the earlier form of *sil* 실 'valley' (still common in place names), while all Middle Korean texts instead identify 谷 with *kwol* 골 'valley' — a hun reading that changed over time; by MK, *sil* survived only in the compound *sinay* 시내 'brook, valley stream.' |
| -*hoton* / 一等 | 'one' | numeral | core | — | Old Korean (Unified Silla, hyangga: "Song of Sacrifice for a Departed Younger Sister," "Song of Prayer to the Bodhisattva of a Thousand Hands") | Silla | national | grammar_reference | n/a | n/a | p.73–74. 一 is the meaning-character 'one'; 等 (*tung*) is the phonogram cueing the ending. Early MK reflex *hoton*. |
| 홀 holo | 'one day' | noun (frozen numeral compound) | core | — | Middle Korean (cited as a reflex clue for Old Korean *hot-* 'one') | — | — | grammar_reference | n/a | n/a | p.74. From *holol* < *hotol*, composed of *hot* 'one' + *ol* 'day' — morpheme breakdown below. |
| *twupul/*twuWul (二肹 / 二尸) | 'two' | numeral | core | — | Old Korean (hyangga: "Song of Ch'ŏyong," "Song of Prayer to the Bodhisattva of a Thousand Hands") | Silla | national | grammar_reference | n/a | n/a | p.74. 肹 represents *hul; 尸 represents *l/*r — both consistent with an Early MK form *twupul/*twuWul 'two.' |
| 즈믄 cumun (千隱) | 'thousand' | numeral | core | — | Old Korean (hyangga: "Song of Prayer to the Bodhisattva of a Thousand Hands") | Silla | national | grammar_reference | n/a | n/a | p.74. 千 is the meaning-character; 隱 cues the ending. MK reflex *cumun* 즈믄. |
| 井 / 乙 | 'spring, well' | noun | core | — | Old Korean (Silla, foundational place name 蘿井/奈乙) | Silla | local | grammar_reference | n/a | n/a | p.74. Reconstructed as *ul* 을; no trace of this word survives in the Middle Korean corpus — a genuine Old Korean lexical loss. |
| 福 / 卜 / 巴 / 伏 | 'youth' | noun | core | — | Old Korean (Silla, Samguk yusa ch.4 name-gloss) | Silla | local | grammar_reference | n/a | n/a | p.74. Four interchangeable phonograms per the source text itself, reconstructed as *pwok* 복; no trace in Middle Korean. |
| 伐 / 火 | 'community, settlement' | noun | core | — | Old Korean (Silla place names) / Old Korean (Paekche cognate 夫里) | Silla (and Paekche cognate) | regional | grammar_reference | n/a | n/a | p.74–75. 伐 is the regular phonogram (*pel* 벌); 火 is a kun-gana-type transcription borrowing the native reading of 'fire' to write *pul* 블. Only frozen-compound MK traces survive: *koWol* 고올 'town, district, village' and *syeWul* 셔울 'capital' (> Seoul). |
| 徐伐 / 徐伐 (Sŏbŏl, syepel) | 'capital' (also the name of the proto-Silla statelet) | proper noun / noun | core | — | Old Korean (pre-Silla-unification statelet name, per Samguk yusa ch.1) | Silla (Sŏrabŏl) | local | grammar_reference | n/a | n/a | p.75. Most variant names for the early Silla state are held to be variants of this same word for 'capital.' |
| 次次雄 / 慈充 | 'shaman' | noun | regional | — | Old Korean (Silla, royal-title use before 503; per Samguk sagi ch.1, citing Unified Silla scholar Kim Taemun) | Silla | local | grammar_reference | n/a | n/a | p.75. Reconstructed *cochywung* 즛충; glossed in the source itself as a regional/local word. Cognate with MK *susung* 스승 'master, shaman.' Used as an early royal title because the shaman "serves demons and gods." |
| 尼師今 / 尼叱今 / 齒叱今 | 'tooth' | noun | regional | — | Old Korean (Silla royal title, pre-503; per Kim Taemun via Samguk sagi/yusa) | Silla | local | grammar_reference | n/a | n/a | p.75. Reconstructed *nisokum*/*niskum*; explicitly glossed by the source as "a regional word." Cognate with MK *ni* 니 'tooth.' |
| 麻立 | 'post' | noun | regional | — | Old Korean (Silla royal title, pre-503; per Kim Taemun via Samguk yusa) | Silla | local | grammar_reference | n/a | n/a | p.75. Reconstructed *malip* 마립; explicitly glossed "in regional speech." MK reflex *malh* 맗 'post.' |
| 王 (wang) | 'king' | noun | core | — | Sino-Korean, adopted 503 (official replacement of native royal titles) | Silla → national | national | grammar_reference | n/a | n/a | p.51, 75. Formal sinification event: in 503 the state replaced native royal-title words (次次雄/尼師今/麻立 above) with the Chinese title *wang*. |
| 붇 pwut | 'writing brush' | noun | core | — | early Chinese loanword (pre-Sino-Korean-system layer) | — | national | grammar_reference | n/a | n/a | p.76. Phonological shape falls outside regular Sino-Korean rules: its -t coda is anomalous, since Sino-Korean regularly renders original Chinese -t as -l — evidence this loan entered Korean independently of, and earlier than, the systematic Sino-Korean reading-layer. |
| 먹 mek | 'inkstone' | noun | core | — | early Chinese loanword | — | national | grammar_reference | n/a | n/a | p.76. Paired with *pwut* as a well-known early (pre-systematic) Chinese loan, never written with Chinese characters and not treated as Sino-Korean. |
| 居柒 | 'uncultivated, fallow' (glossed 荒/萊) | adjective/verb stem | core | — | Old Korean (Silla place-name transcription) | Silla | local | grammar_reference | n/a | n/a | p.65. MK reading *kechul* 거츨; cited as confirming evidence for a medial aspirate in Old Korean. |
| 異次 / 伊處 | 'dislike, hate' | verb stem | core | — | Old Korean (Silla) | Silla | local | grammar_reference | n/a | n/a | p.65, 66. MK reflex *ich-* 잋-; second character of both transcriptions read with aspirated initial *ch-*, confirming the aspirate. Also cited under terminal-consonant discussion (次 representing *c/*ch in final position). |
| 佛體 | 'body of the Buddha' | noun phrase | literary | — | Old Korean (hyangga: "Song of the Ten Great Vows of the Lord of Truth," Pohyŏn sibwŏn ka) | Silla | national | grammar_reference | n/a | n/a | p.65. Corresponds to MK *pwuthye* 부텨 'Buddha'; cited as confirming evidence for dental aspirates. |
| 折叱可 | 'breaking off' | verb + ending | literary | — | Old Korean (hyangga: "Song of the Presentation of Flowers," Hŏnhwa-ka) | Silla | national | grammar_reference | n/a | n/a | p.66, 73. MK reflex *kes.ke* 것거; 叱 here cues syllable-final *s. Also cited under conjunctive ending -*ka* (-아, 'and'): verb stem *kesk-* 걲- plus the ending 可. |
| 城叱 | 'fortified city' | noun + genitive/final-s marker | literary | — | Old Korean (hyangga: "Song of the Comet," Hyesŏng-ka) | Silla | national | grammar_reference | n/a | n/a | p.66. MK reflex *cas* 잣 'fortified city'; confirms 叱 as syllable-final *s. |
| 枝次 | 'branch' | noun | literary | — | Old Korean (hyangga: "Song of Praise for the Knight Kip'a," Ch'an Kip'a-rang ka) | Silla | national | grammar_reference | n/a | n/a | p.66. MK reflex *kac* 갖 'branch'; 次 here cues a terminal affricate (*c/*ch not distinguished finally). |
| 伊 / 是 | nominative particle | particle (case) | core | — | Old Korean (Silla) | Silla | national | grammar_reference | n/a | n/a | p.71. Read *i* 이; MK form identical. |
| 矣 / 衣 | genitive particle | particle (case) | core | — | Old Korean (Silla) | Silla | national | grammar_reference | n/a | n/a | p.71. Read *-oy/uy* -의; also doubles as a pronoun form (see below). |
| 叱 (genitive use) | genitive particle -s | particle (case) | core | — | Old Korean (Silla) | Silla | national | grammar_reference | n/a | n/a | p.66, 71. Same phonogram used elsewhere for a syllable-final *s (see 折叱可, 城叱 above) — the source notes this dual use is mutually confirming evidence that the graph represented a sibilant. |
| 良 (locative use) | locative particle | particle (case) | core | — | Old Korean (Silla) | Silla | national | grammar_reference | n/a | n/a | p.71. Read *ay/ey* 애/에. (Distinct from the homographic conjunctive-ending use of 良, below.) |
| 中 (locative use) | locative particle | particle (case) | core | — | Old Korean (Silla) | Silla | national | grammar_reference | n/a | n/a | p.71. Read *kuy* 긔. |
| 良中 | locative particle (compound) | particle (case) | core | — | Old Korean (Silla) | Silla | national | grammar_reference | n/a | n/a | p.71. Read *akuy* 아긔; compound of the two preceding locative morphemes. |
| 乙 (accusative, particle table) | accusative particle | particle (case) | core | — | Old Korean (Silla) | Silla | national | grammar_reference | n/a | n/a | p.70–71. Read *-ol/ul* -을/올; the usual transcription for the accusative. |
| 肹 | accusative particle (variant) | particle (case) | core | — | Old Korean (Silla) | Silla | national | grammar_reference | n/a | n/a | p.71. Believed to represent *hul, with the initial *h belonging morphemically to the preceding noun — paralleling MK *hul* 흘. |
| 留 | instrumental particle | particle (case) | core | — | Old Korean (Silla) | Silla | national | grammar_reference | n/a | n/a | p.71. Read *-(o/u)lwo* -(으)로. |
| 隱 / 焉 | topic marker | particle (focus) | core | — | Old Korean (Silla) | Silla | national | grammar_reference | n/a | n/a | p.71–72. Read *(n)on/un* -은/온; also doubles as the modifier/nominalizer ending (see Grammar points). |
| 置 | 'too, also, even' | particle (focus) | core | — | Old Korean (Silla) | Silla | national | grammar_reference | n/a | n/a | p.71. Read *two* 도. |
| 矣 / 矣徒 (pronoun use) | first-person self-reference pronoun | pronoun | core | — | Old Korean (hyangga, idu) → late Chosŏn idu readings | Silla | national | grammar_reference | n/a | n/a | p.71. Read *uy*/*uynoy* 의/의로; comparativists link 矣 to a reconstructed Altaic first-person pronoun *bi. |
| -徒 / -노이 -noy | pseudo-pluralizing suffix 'the group, all of...' | suffix (nominal plural/collective) | core | — | Old Korean → Middle Korean (*emanim-nay* 어마님내 'mothers') → Contemporary *-ney* | Silla | national | grammar_reference | n/a | n/a | p.71. Second syllable of 矣徒; survives into Contemporary Korean as the collective/plural-honorific suffix *-ney*. |
| 吾 | 'I' (1st person singular pronoun) | pronoun | core | — | Old Korean (Silla) | Silla | national | grammar_reference | n/a | n/a | p.71. Chinese graph for 'I' used directly. |
| 吾里 | 'we' (1st person plural pronoun) | pronoun | core | — | Old Korean (Silla) | Silla | national | grammar_reference | n/a | n/a | p.71. Reflex of MK *wuli* 우리 'we.' |
| 汝 | 'you' (2nd person pronoun) | pronoun | core | — | Old Korean (Silla) | Silla | national | grammar_reference | n/a | n/a | p.71. Chinese graph for 'you' used directly. |
| 尸 (modifier/nominalizer use) | prospective modifier/nominalizer ending | suffix (verbal) | core | — | Old Korean (hyangga: "Song in Admiration of the Knight Chukchi," late 7th c.) | Silla | national | grammar_reference | n/a | n/a | p.71–72. MK reflex *-(o/u)lq* -을; doubles as both a noun-modifier ending and a nominalizer. Example: 慕理尸 *kulilq* 그릴 'longing', 行乎尸 *nyewolq* 녀올 'going.' |
| 隱 (modifier/nominalizer use) | past/perfective modifier/nominalizer ending | suffix (verbal) | core | — | Old Korean (hyangga: "Song in Admiration of the Knight Chukchi") | Silla | national | grammar_reference | n/a | n/a | p.72. MK reflex *-(o/u)n* -은; example 去隱春 '(the) spring that passed,' attached to stem *ka-* 가- 'go.' |
| 良 (conjunctive-ending use) | conjunctive ending of 'desire' (-> purposive) | suffix (verbal) | core | — | Old Korean (hyangga: "P'ungyo") | Silla | national | grammar_reference | n/a | n/a | p.72. MK reflex *-la* -라, became Contemporary purposive *-(u)le*. Example: 功德修叱如良來如 'coming in order to beg for food.' |
| 如可 | transferative conjunctive ending 'does and then...' | suffix (verbal, compound) | core | — | Old Korean (hyangga: "Song of Ch'ŏyong") | Silla | national | grammar_reference | n/a | n/a | p.72. MK reflex *-taka* -다가, itself a compound of assertive *-ta* + particle *-ka*. Example: 夜入伊遊行如可 'I enjoyed the night until late, and then...' |
| 遣 | coordinating conjunctive ending 'and...' | suffix (verbal) | core | — | Old Korean (hyangga: "Ballad of the Yam-gathering Youths," Sŏdong-yo) | Silla (and, per legend, Paekche-authored) | national | grammar_reference | n/a | n/a | p.72–73. Usually treated as equivalent to the ending transcribed 古 (below), though its apparent nasal coda is unexplained. Example: 抱遣 'embrace and...' |
| 古 (conjunctive-ending use) | coordinating conjunctive ending 'and...' | suffix (verbal) | core | — | Old Korean (hyangga: "Song of Sacrifice for a Departed Younger Sister," Che-mangmae-ka) | Silla | national | grammar_reference | n/a | n/a | p.73. MK reflex *-kwo* -고. Example: 一等隱枝良出古 'grew from one branch, and...' |
| 可 (conjunctive-ending use) | conjunctive ending 'and' | suffix (verbal) | core | — | Old Korean (hyangga: "Song of the Presentation of Flowers") | Silla | national | grammar_reference | n/a | n/a | p.73. Read *-*ka*; MK reflex *-a* -아. Example: 花肹折叱可 'pick flowers and...' |
| 如 (finite-ending use) | declarative sentence ending | suffix (verbal) | core | — | Old Korean (Silla) | Silla | national | grammar_reference | n/a | n/a | p.73. MK reflex *-ta* -다 (unchanged into Contemporary Korean). |
| 古 (finite interrogative use) | interrogative sentence ending | suffix (verbal) | core | — | Old Korean (Silla) | Silla | national | grammar_reference | n/a | n/a | p.73. Same phonogram as the coordinating conjunctive above; MK reflex also *-kwo* -고 in this function. |
| 之/齊 (finite declarative, idu) | declarative sentence-closing ending (idu) | suffix (verbal) | archaic | — | Old Korean (Silla, via idu) → late Chosŏn idu readings *-cyey/-cye* → modern Cheju dialect *-ce* | Silla → **Cheju dialect (modern reflex)** | regional | grammar_reference | n/a | n/a | p.73. Frequent in both hyangga and idu texts; the modern survival specifically in Cheju dialect is an explicit regional annotation in the source. |
| 俗 (Sino-Korean) / 숗 syoh (native) | 'common, unrefined' (Sino-Korean) vs. 'ordinary person' (native) | noun (doublet pair) | technical | — | Sino-Korean layer (Tang-period-patterned readings) vs. early native Chinese loan, as attested in Middle Korean | — | national | grammar_reference | n/a | n/a | p.69. *sywok* 쇽 (Sino-Korean) vs. *sywoh* 숗 (early native loan) — illustrates the -k/-h doublet pattern from northern-Chinese velar lenition not carried into the formal Sino-Korean reading. |
| 褥 (Sino-Korean) / 유 (native) | 'mattress' (Sino-Korean) vs. 'mat, futon' (native) | noun (doublet pair) | technical | — | Sino-Korean layer vs. early native loan (Middle Korean attestation) | — | national | grammar_reference | n/a | n/a | p.69. *zywok* 욕 vs. *zywoh* 유ㅎ. |
| 笛 (Sino-Korean) / 뎧 tyeh (native) | 'flute' (Sino-Korean) vs. 'flute' (native) | noun (doublet pair) | technical | — | Sino-Korean layer vs. early native loan (Middle Korean attestation) | — | national | grammar_reference | n/a | n/a | p.69–70. *tyek* 뎍 vs. *tyeh* 뎧. |
| 襆 (Sino-Korean) / 봏 pwoh (native) | 'hood' (Sino-Korean) vs. 'wrapping cloth' (native) | noun (doublet pair) | technical | — | Sino-Korean layer vs. early native loan (Middle Korean attestation) | — | national | grammar_reference | n/a | n/a | p.70. *pwok* 복 vs. *pwoh* 봏. |
| 尺 (Sino-Korean) / 잫 cah (native) | '(Chinese) foot' (Sino-Korean) vs. '(Korean) foot' (native) | noun (doublet pair) | technical | — | Sino-Korean layer vs. early native loan (Middle Korean attestation) | — | national | grammar_reference | n/a | n/a | p.70. *chyek* 쳑 vs. *cah* 잫. |
| 勿 | '(place-name element referring to) water' | noun | core | — | Old Korean (Silla/Three Kingdoms place-name transcription) | — | national | grammar_reference | n/a | n/a | p.69. Chinese reading *mut*; used to transcribe the Korean word that became *mul* 믈 'water' in Middle Korean — cited as evidence that Sino-Korean systematically converts Chinese entering-tone -t to Korean -l. |

#### Morpheme breakdown

> **推火/密城 (place name)** = 推 "push" (old transcription, semantic/hun) ↔ 密 *mil* (reformed transcription, phonetic, matches MK *mil-* "push") — a worked example of how the source cross-checks whether an old Silla place-name transcription was phonetic or semantic by comparing it against the Chinese-style reformed name from 757.

> **一利/里山郡 → 星山郡 (place name)** = 一利 (old, phonograms for a lost Silla word for "star") + 山 "mountain" (meaning-character, carried through unchanged) ↔ modern dialect **ili-nay** = *ili* ("star," surviving only in this compound) + *nay* "stream" — "Milky Way," i.e. "star stream." Demonstrates how an opaque modern dialect compound can be etymologized only via the Old Korean place-name record.

> **홀 holo "one day"** = *hot* "one" + *ol* "day" (← *holol* ← *hotol*) — shows that the Old Korean numeral stem *hot-* "one" (attested directly as 一等 *hoton*) survives today only buried inside a frozen numeral-plus-noun compound, not as a free numeral.

> **一等 *hoton* "one"** = 一 "one" (meaning-character) + 等 *tung* (phonogram cueing the final syllable) — the source's own worked example of how Old Korean numerals combine a semantic character with a phonetic cue for the ending, the same two-part method used throughout hyangch'al and idu.

> **徐伐 (Sŏbŏl) "capital" / name of the proto-Silla state** = a single unanalyzed native root per the source (no further internal decomposition given), but the source treats nearly every other recorded name variant for early Silla as a phonetic variant of this same root, making it a name-wide case study in transcription variation rather than a decomposable compound.

### Grammar points

#### §3.1 Sources — overview

The source identifies six independent evidentiary channels for reconstructing Sillan (Old Korean):
(1) the transcription of personal/place/office names in the Samguk sagi and Samguk yusa, cross-
checked against Chinese and Japanese historical sources; (2) idu; (3) hyangch'al; (4) a handful of
Chinese ethnographic transcriptions (the Liang shu); (5) loanwords borrowed into Old Japanese; (6)
the traditional Sino-Korean readings of Chinese characters, preserved in unbroken tradition since
Unified Silla (p.51–52, 59).

#### Decipherment via reformed vs. original place names (§3.1.1)

Because King Kyŏngdŏk's 757 reform replaced native Silla place names with standardized two-
character Chinese-style names, linguists can sometimes recover the meaning or sound of a lost Silla
place-name element by comparing the old transcription against the reformed one — but the source
stresses this requires "informed guesswork," since the reformed name is a *new* name, not
necessarily a different transcription of the same old name, and it is not always clear in advance
whether the old transcription itself was phonetic or semantic (p.52).

#### Idu as a developing scribal system (§3.1.2)

Idu altered Chinese-text word order into Korean syntax and added Korean particles/endings using
Chinese characters phonetically or semantically. The source traces its development across four
dated inscriptions — a 451 Koguryŏ-crafted silver box (minimal syntactic alteration only), the Imsin
sŏgi sŏk stele (552 or 612, fuller reordering but almost no function-word marking beyond 之), the
South Mountain stele (591, transitional, adds 節/以/敎/令/爲), and the Karhang temple pagoda
inscription (758, adds systematic verb-ending marking via 在 and 旀) — reaching its "more or less
fully developed form" only around the 11th century, well after the Old Korean period proper (p.54–
56). The system's own name, *idu* 吏讀, is first attested only in 1444, in Ch'oe Malli's anti-alphabet
memorial, long after the system itself existed.

#### Kugyŏl (p.56)

Characters added to idu-type texts specifically to annotate Korean grammatical elements came to be
called kugyŏl, "oral embellishments." The source notes the convention plausibly originated in the
Old Korean period, but that most of what is actually documented about kugyŏl symbols comes from
later Koryŏ-period texts, not Silla ones.

#### Hyangch'al and the limits of hyangga decipherment (§3.1.3)

Hyangch'al reused the same transcription strategies as place names and idu/kugyŏl, applied to full
literary composition. The source is candid about the limits of current scholarship: "We quite
honestly do not know what some hyangga mean, much less what they sounded like" (p.57). The "Song
of Ch'ŏyong" is unusually well understood only because later Koryŏ/15th-c. versions of the same poem
survive in the Akhak kwebŏm and Akchang kasa music collections, giving independent confirmation of
readings reconstructed from the 8th-century hyangch'al text.

#### Chinese ethnographic transcriptions as a source, with caveats (§3.1.4)

The 7th-century Chinese history Liang shu preserves a handful of directly-heard Sillan words (for
fortification, village, officials' hats, jackets, trousers, boots), several of which are identifiable
via later Middle Korean cognates, but others remain uninterpretable. The source separately flags the
Liang shu's claim that Silla was "without writing" as almost certainly Chinese ethnographic fantasy,
since Silla scribes "most certainly wrote in Chinese" (p.51, 58).

#### Old Japanese loanwords as cross-script evidence (§3.1.5)

A Silla-origin word identified independently in Old Japanese is valuable precisely because it can
supply phonological detail (vowel/consonant quality) that character-based transcription alone
cannot — but only when the same word is independently attested in another Korean-side source too,
since borrowing-direction between the peninsula and the islands is not always certain (p.58–59).

#### Phonograms are generally syllabic (§3.2.1)

Most Sillan phonograms represent a full syllable rather than an individual segment, as seen
consistently across both name transcriptions and hyangga. The source gives a partial list of
reconstructed syllabic values (e.g. *a* 阿, *na* 乃/奈/那, *ko* 古, *mo* 毛, *al* 閼, *kan* 干) and
notes these phonogram sets were shared across Silla, Koguryŏ, and Paekche, and correspond closely to
the Japanese *man'yōgana* ("ongana") system used in the Man'yōshū — a correspondence the source treats
as too systematic to be coincidental, most plausibly reflecting shared/diffused transcription
techniques across the whole region rather than a simple one-directional "who taught whom" story
(p.59–60).

#### Non-syllabic phonograms mark codas (§3.2.2)

A small set of characters were not read as full syllables but used purely to cue a syllable-final
consonant, typically paired with a semantic (hun) character for the root meaning: -m 音, -r/l 尸/乙,
-s 叱, -c 次 (p.60–61).

#### The six problematic phonograms (§3.2.3)

Six specific graphs resist clean phonological interpretation, each discussed individually in the
source: one usually read -ra/la but sometimes -a/e when marking the infinitive; one read -mye marking
the coordinate conjunctive, whose reading implies an unusually archaic Chinese pronunciation; one
whose expected final nasal (from both Chinese and traditional Korean readings) is not reflected in
the Middle Korean form of the same morpheme; and three (尸, 叱, 只) whose status as true phonograms
at all is uncertain — 尸 in particular is "probably the most enigmatic" transcriptional symbol in the
whole corpus, since its presumed sibilant Chinese/Korean reading does not match its apparent function
marking a liquid consonant (p.61–62).

#### Hun (word-gloss) readings (§3.2.4)

Many characters in Sillan texts were read for their meaning as a native word (a *saegim*/hun
reading) rather than their sound — the same mechanism as Japanese kun readings, which the source
notes historically crossed to Japan from the peninsula. Hun associations are largely stable from
Silla through Middle Korean to today (e.g. 夜→*pam* 'night', 日→*nal* 'day', 金→*swoy* 'metal'), but
not always: 谷 'valley' was read as Silla *sil* but all MK texts instead give *kwol*, illustrating
that hun readings themselves could change over the centuries, plausibly because *sil* had already
become non-transparent as an independent word by Middle Korean times (p.62–63).

#### Mixed transcription and the senmyōgaki parallel (§3.2.5)

Hyangch'al's dominant convention was mixed: noun/verb stems written semantically (hun), particles
and endings written phonetically. The source compares this directly to the Japanese *senmyōgaki*
style used for imperial edicts, again flagging probable cultural diffusion while allowing for
independent parallel development given shared underlying writing principles (p.63).

#### Old Korean obstruents and the aspiration question (§3.3.1.1–2)

The source reconstructs a plain series (p, t, c, k) and an aspirated series (ph, th, ch, kh) for
Silla, noting the standard Altaicist hypothesis that an earlier Proto-Altaic voiced/voiceless
contrast merged into Korean's plain series, after which aspiration developed separately — but flags
this as unresolved by direct Old Korean evidence either way (p.64). Evidence for the aspirate series'
gradual emergence comes from Sino-Korean borrowing patterns: Chinese dental aspirates were reliably
borrowed as Korean aspirates, but Chinese labial and especially velar aspirates mostly were *not* —
Chinese *kh was regularly borrowed as plain Korean /k/, with only a handful of exceptions (夬/快/駃/噲,
all read *khwoay*). The source concludes the aspirate series developed in stages: dental first, then
labial, then velar (p.64–65). Medial aspirates, by contrast, are confirmed directly from Silla
transcriptions (居柒 *kechul*, 異次/伊處 *ich-*, 佛體 *pwuthye*) (p.65).

#### Terminal-consonant mergers (§3.3.1.3)

Old Korean kept /t/, /s/, /c/ distinct in final position (though not /ch/ from /c/); by Middle
Korean, /s, c, ch/ had all merged to [s] before a pause; by Contemporary Korean, /t, s, c, ch/ have
further merged to an unreleased [t] — an unbroken multi-century drift toward "implosive" final-
consonant articulation (p.65–66). The source also argues, from distributional and tonal evidence in
Middle Korean l-stem verbs, that MK syllable-final /l/ likely resulted from an earlier merger of two
distinct Old Korean liquids, consistent with the Altaicist *r/*l distinction hypothesis — and that
the Old Korean transcription system (distinct, non-interchangeable use of 尸 vs. 乙 for what later
merge into /l/) is itself evidence that distinction had not yet collapsed in Silla times (p.66–67).

#### Vowels (§3.3.2) and vowel harmony (§3.3.2.1)

Reconstruction of the Old Korean vowel inventory is "especially tentative," relying mainly on
projecting the Early Middle Korean system backward, supplemented by weak phonogram evidence; overall
the source finds no strong evidence of substantial vowel-system change between Old and Early Middle
Korean (p.67). On vowel harmony specifically, the hyangch'al record shows no direct trace of
alternation at all — but the source argues this is a limitation of the poor-quality transcriptional
evidence, not positive evidence of absence, since the harmony system is observably *more* regular the
further back one traces it from Contemporary through Early Modern through Middle Korean, making its
presence (perhaps in a more "palatal" form) in Old Korean a reasonable inference rather than a
documented fact (p.68).

#### Sino-Korean as a borrowed *system*, not a vocabulary (§3.4)

The source's central claim about Sino-Korean ("Eastern Sounds," 東音 *tongŭm*) is that Korea did not
borrow individual Chinese words piecemeal but rather adopted the whole relational structure of
traditional Chinese rime tables/dictionaries, patterned on prestige Tang-period (Chang'an) Middle
Chinese — "Koreans borrowed the system, not individual words" (p.68–69). This is explicitly
distinguished from the separate, smaller layer of genuinely borrowed early Chinese loanwords (e.g.
*pwut* 'brush', *mek* 'inkstone') that are never written with Chinese characters and aren't popularly
recognized as Chinese in origin at all. A specific diagnostic the source develops: Chinese entering-
tone -t codas are *always* rendered as Korean -l in the systematic Sino-Korean layer (e.g. 勿 *mut* →
*mul* 'water'), which the source uses to argue Korean borrowed its readings from a northern Chinese
dialect variety in which -t had already lenited toward [r]; a parallel argument is made for velar
-k lenition, visible in the native-loan doublets (俗/숗, 褥/유 etc.) that preserve the lenited form
where the formal Sino-Korean reading preserves -k (p.69–70).

#### Sources and limits of Old Korean grammatical data (§3.5)

Grammatical information about Old Korean comes only from hyangch'al and idu. The source flags a
genuine methodological asymmetry: most surviving idu documents postdate the Old Korean period
(mostly Chosŏn-era), mixing archaic Silla-period forms indiscriminately with later ones, making exact
dating difficult; hyangch'al data is comparatively more reliably dated to the Old Korean period
itself, but far scarcer and still imperfectly deciphered (p.70).

#### Modifier endings double as nominalizers (§3.5.2)

A structurally important point the source highlights: Old Korean verbal modifier endings (reflexes of
MK -(o/u)n and -(o/u)lq) could also function as nominalizers — the same morphological slot serves
both roles, a typological feature the source says has remained constant "throughout [Korean's]
recorded history" (p.71–72).

#### Finite-ending polysemy (§3.5.2.2)

The source notes that a single phonogram (古) is attested marking two distinct finite-sentence
functions — coordinating conjunctive 'and...' and interrogative — both reflexed as MK -kwo -고,
illustrating how thin the hyangch'al/idu record can be for disambiguating distinct Old Korean
grammatical categories that happen to share a later surface form (p.73).

#### Numerals as a case study in transcription method and lexical loss (§3.6)

The source uses the three directly-attested hyangga numerals ('one,' 'two,' 'thousand') as a worked
example of the standard two-part Old Korean transcription method (meaning-character + phonogram
cueing the ending), while also using several place-name-only words ('spring/well,' 'youth,'
'community/settlement') to make the opposite point: some genuine Old Korean vocabulary left no
surviving trace at all in the Middle Korean lexicon, surviving only in frozen place-name elements, if
that (p.73–75).

#### Sinification of royal titles as a dated vocabulary-replacement event (§3.6)

The source treats the 503 replacement of native Silla royal titles (次次雄/尼師今/麻立, used from the
founder through the 22nd sovereign) with the Chinese title 王 *wang* as a concrete, precisely dated
anchor point for the broader multi-century sinification of Korean vocabulary that continued "up until
modern times" — explicitly tying a single lexical-replacement event to the general historical
process also discussed in Chapter 2 regarding place-name and personal-name sinification (p.75–76).

---


---

## Korean — Established Vocabulary/Grammar: A History of the Korean Language, Ch. 4 "Early Middle Korean"

**Source:** Ki-Moon Lee & S. Robert Ramsey, *A History of the Korean Language* (Cambridge University
Press, 2011), printed pp. 77–99 (PDF pp. 89–111) — Chapter 4: 4.1 The formation of Middle Korean,
4.2 Sources, 4.3 The transcription of Korean, 4.4 Phonology, 4.5 Vocabulary.

**Coverage note:** This is an academic diachronic/historical-linguistics monograph, not a teaching
grammar — "vocabulary" here means *attested forms cited as philological evidence*, not a pedagogical
word list, and "grammar points" means reconstructed phonological/orthographic mechanisms rather than
synchronic rules. Every form the authors actually cite with a transcription or reconstruction in this
page range is captured below; the long systematic explanatory prose connecting them is paraphrased.
Confirmed non-overlapping with all existing `established/` Korean files (pre-checked by the
orchestrator) — this is the project's first extraction touching the pre-Hangul (pre-1446) period.

**Text-layer caveat (not a cipher — a font-glyph gap):** `pdftotext` has a genuine, clean text layer
for this PDF range (Hangul, Hanja, and italic Yale-romanization diacritics all render correctly for
the overwhelming majority of forms). However, a handful of **archaic/obsolete Hangul jamo** — ㆍ
(arae-a), ㅿ (semi-voiced s, "panchios"), and ㅸ (bilabial fricative w) — are missing from the PDF's
embedded font and render as a dropped/blank glyph rather than a wrong one. This is a font-coverage gap
for obsolete letters no longer used in modern Hangul, not a substitution cipher to decode. Where this
occurs, the **Yale romanization is complete and used as the authoritative Term form**; any Hangul
given alongside it may have the obsolete jamo silently missing and should not be treated as the full
orthographic form. No marginalia, no vision-reading was needed anywhere in this range.

---

### Vocabulary

Era shorthand used throughout unless noted otherwise: **EMK** = "Early Middle Korean (Koryŏ period,
~10th–14th c.)". **LMK** = "Late Middle Korean (Chosŏn period, 15th–16th c.)" — cited only as the
*endpoint* evidence used to reconstruct the EMK form, per the source's own comparative method; these
LMK rows are included because the chapter's reconstructions are inseparable from them, but they
properly belong to the Late Middle Korean period, not Early Middle Korean itself.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| *namol (那勿) | 'lead' | noun | archaic | — | Pre-Koryŏ substratum, cited in a 13th-c. source (Hyangyak kugŭppang) | northwestern former-Koguryŏ territory (site of Kaegyŏng) | regional | grammar_reference | n/a | n/a | p. 78. Phonogram 那勿; glossed in the source itself as 俗云 "called in the vernacular." Matched to reconstructed Koguryŏan *namər 'lead' (phonograms 乃勿) — proposed Koguryŏan substratum in Koryŏ-area vocabulary, not an accident per the authors. |
| Koguryŏ word for 'valley' (written 呑/旦/頓) | 'valley' → later 'village' | noun | archaic | — | Three Kingdoms (Koguryŏ) → survives to 1400 | northwestern peninsula | regional | grammar_reference | n/a | n/a | p. 78. Phonogram 呑 (also 旦, 頓) for Koguryŏ 'valley'; the same phonogram 呑 reappears in the 1400 Cháoxiǎn-guǎn yìyǔ glossing the Korean word for 'village,' suggesting survival of the Koguryŏan word into the 15th c. |
| nap (납) | 'lead' | noun | core | — | LMK (15th c., replacing EMK *namol) | — | national | grammar_reference | n/a | n/a | p. 79. Believed to be of Sillan origin; replaced *namol even in the Koryŏ-area central dialect, evidence of continuing southeastern-dialect (Sillan) influence on the central language. |
| mozol (모올) | 'village' | noun | core | — | LMK (15th c., replacing the Koguryŏ-derived "valley" word) | — | national | grammar_reference | n/a | n/a | p. 79. Believed to be of Sillan origin, paired with *nap as the second of two replacement cases cited. |
| katana | '1' | numeral | archaic | — | ~early 12th c. (contemporary with the Jilin leishi) | Japan (Japanese kana source describing Korean) | transnational | grammar_reference | n/a | n/a | p. 80. From the Japanese compendium Nichū-reki; matches reasonably well with Jilin leishi's 河屯 for 'one.' |
| tufuri | '2' | numeral | archaic | — | ~early 12th c. | Japan (source) | transnational | grammar_reference | n/a | n/a | p. 80. Matches reasonably well with Jilin leishi's 途孛 for 'two.' |
| towi / sawi / esusu / hasusu / tarikuni / tirikuni / etari / etu | '3'/'4'/'5'/'6'/'7'/'8'/'9'/'10' | numeral | archaic | — | ~early 12th c. | Japan (source) | transnational | grammar_reference | n/a | n/a | p. 80. Nichū-reki numerals 3–10; the authors flag these as "disappointing" — apparently scrambled in transmission (3↔4, 5↔6, and possibly 7↔8/8↔9 swapped), so not treated as reliable individually. |
| *hoton (河屯) | 'one' | numeral | archaic | — | EMK (Jilin leishi, 1103–4) | — | national | grammar_reference | n/a | n/a | p. 80, p. 94. Phonogram 河屯 [*xɦa-tɦun]. |
| *twuul/twul (途孛) | 'two' | numeral | archaic | — | EMK (Jilin leishi, 1103–4) | — | national | grammar_reference | n/a | n/a | p. 80, p. 91. Phonogram 途孛 [*tɦuə-pɦut]; also cited later as one of the labial-coda transcriptions bearing on EMK *b. |
| nali (나리) | 'stream' | noun | literary | — | EMK, attested in the Koryŏ-period song "Tongdong" (動動), first written down in LMK collections | — | national | grammar_reference | n/a | n/a | p. 81. One of the few EMK-flavored forms surviving in a vernacular song; the authors caution these songs can only be used for reconstruction "with caution" since most other EMK traces were lost in transmission. |
| syem (苫, LMK 셤) | 'island' | noun | core | — | LMK, transliterated in a 1124 Chinese source (Xuānhé fēngshǐ Gāolì tújīng) | — | national | grammar_reference | n/a | n/a | p. 81. Transliterated with 苫 [*ʂiam] by Song envoy Xu Jing, who also glosses it as "smaller than an island, having grass and trees." |
| kwoswom(twoth) (고솜돝) | 'hedgehog' | noun | core | — | EMK/LMK boundary (12th-c. Chinese source + Hyangyak kugŭppang corroboration) | — | national | grammar_reference | n/a | n/a | p. 81–82. Xu Jing transcribes 'hedgehog spines' as 苦笘 [*khuə-ʂiam], matching kwoswom 고솜; LMK form kwoswomtwoth adds twoth 'pig' as a suffix. Corroborated by Hyangyak kugŭppang's "hide of the hedgehog... 苦蔘猪," where 猪 'pig' is a semantic gloss, not a phonogram. |
| 鉛/鷄林類事 numeral-coda set: 蚤曰批勒 (*phi-lək) | 'flea' | noun | core | — | EMK (Jilin leishi) | — | national | grammar_reference | n/a | n/a | p. 85. > LMK pyelwuk 벼룩; cited as a clean velar-coda match. |
| *xɦuat-sak (射曰活索) | 'shoot an arrow' | verb | core | — | EMK (Jilin leishi) | — | national | grammar_reference | n/a | n/a | p. 85. Represented hwal swo- 활 소- 'shoot a bow'; cited as a case with *no* velar coda despite a velar-looking transcription, illustrating irregularity in the coda system. |
| *pɦut (火曰孛) | 'fire' | noun | core | — | EMK (Jilin leishi) | — | national | grammar_reference | n/a | n/a | p. 85, 91 (also cited for the voiced-fricative/labial discussion). > LMK pul 블. |
| *muat (馬曰末) | 'horse' | noun | core | — | EMK (Jilin leishi) | — | national | grammar_reference | n/a | n/a | p. 85, 94. > LMK mol 몰; dental coda *t corresponds to later /l/. |
| *tɦut (猪曰突) | 'pig' | noun | core | — | EMK (Jilin leishi) | — | national | grammar_reference | n/a | n/a | p. 86. > LMK toth 돝. |
| *kut (花曰骨) | 'flower' | noun | core | — | EMK (Jilin leishi) | — | national | grammar_reference | n/a | n/a | p. 86. > LMK kwoc 곶. |
| *kaj/*khat (笠曰蓋音渴) | 'rain hat' | noun | core | — | EMK (Jilin leishi) | — | national | grammar_reference | n/a | n/a | p. 86. > LMK kat 갇; the entry itself notes two pronunciations ("sounds like [*khat]"). |
| *pjit (梳曰苾音必) | 'comb' | noun | core | — | EMK (Jilin leishi) | — | national | grammar_reference | n/a | n/a | p. 86. > LMK pis 빗. |
| *ʔjit-kip (七曰一急) | 'seven' | numeral | core | — | EMK (Jilin leishi) | — | national | grammar_reference | n/a | n/a | p. 86. > LMK nilkwup 닐굽; cited as evidence that Chinese *p codas consistently represent Korean -p. |
| *ʔip (口曰邑) | 'mouth' | noun | core | — | EMK (Jilin leishi) | — | national | grammar_reference | n/a | n/a | p. 86. > LMK ip 입. |
| *tsah (尺曰作) | 'ruler (measuring stick)' | noun | core | — | EMK (Jilin leishi) | — | national | grammar_reference | n/a | n/a | p. 86. > LMK cah 잫; cited for its reconstructed *h coda in Late Middle Chinese. |
| swop-sekun-phul (솝서근플) | 'Scutellaria baikalensis (lit. "inside-rotten grass")' | noun (compound) | technical.botanical | — | EMK (Hyangyak kugŭppang, mid-13th c.) | — | national | grammar_reference | n/a | n/a | pp. 86–87. Transcribed two ways — 精朽草 (all semantic glosses) and 所邑朽斤草 (mixed phonogram/gloss) — both read identically; worked example of the Hyangyak's mixed transcription practice. Morpheme breakdown: swop (솝, 'inside', glossed by 精 or spelled phonetically 所邑) + sekun (서근, 'rotten', 朽, phonetically reinforced by 斤 kun) + phul (플, 'grass', 草 gloss). |
| mah (마) | 'yam' | noun | core | — | EMK (Hyangyak kugŭppang) / LMK | — | national | grammar_reference | n/a | n/a | p. 87. Transcribed 亇支, where 支 [*tʂi] is argued to represent a 12th-c. antecedent of the terminal -h in LMK mah; used to help resolve the long-debated phonetic value of 支 in Old Korean hyangch'al transcriptions. |
| kyezul (겨ᅀᅳᆯ) | 'winter' | noun | core | — | EMK (Hyangyak kugŭppang), type-1 direct semantic gloss | — | national | grammar_reference | n/a | n/a | p. 87–88. Transcribed with 冬 'winter' used directly for its meaning (not sound). |
| kahi (가히) | 'dog' | noun | core | — | EMK (Hyangyak kugŭppang) | — | national | grammar_reference | n/a | n/a | p. 88. 犬 'dog' used as direct semantic gloss. |
| mwoy (뫼) | 'mountain' | noun | core | — | EMK (Hyangyak kugŭppang) | — | national | grammar_reference | n/a | n/a | p. 88. 山 'mountain' direct semantic gloss. |
| mul (믈) | 'water' | noun | core | — | EMK (Hyangyak kugŭppang, separately also Jilin leishi) | — | national | grammar_reference | n/a | n/a | p. 88 (direct gloss 水); cf. also the Jilin leishi's 水曰沒 *mut entry for the same word via phonogram. |
| twutuleki (두드러기) | 'rash' | noun | core | — | EMK (Hyangyak kugŭppang) → attested as LMK form | — | national | grammar_reference | n/a | n/a | p. 88. Transcribed 置等只, four phonograms, the first two (置, 等) reused through an intervening semantic association ("kungana"-style) rather than directly for sound. |
| petul-wos (버들옷) | 'spurge (lit. "willow-lacquer")' | noun (compound) | technical.botanical | — | EMK (Hyangyak kugŭppang) → LMK form cited | — | national | grammar_reference | n/a | n/a | p. 88. Transcribed 楊等柒: 楊 = semantic gloss for petul 'willow', 等 = derived phonogram for tul, 柒 = semantic gloss for wos 'lacquer'. |
| twoskwomali (돗고마리) | 'cocklebur' | noun | technical.botanical | — | EMK (Hyangyak kugŭppang) → LMK form cited | — | national | grammar_reference | n/a | n/a | p. 88. Transcribed 刀古休伊; 刀/古/伊 straightforward phonograms, 休 a kungana-style indirect phonogram. |
| skuytyelkalis-pwulhwuy | 'root of Komarov's bugbane (Cimicifuga heracleifolia)' | noun (compound) | technical.botanical | — | EMK (Hyangyak kugŭppang) | — | national | grammar_reference | n/a | n/a | p. 88. Transcribed 雉骨木; 雉 'pheasant' used indirectly (kungana-style) for the syllable skuy, even though LMK 'pheasant' itself was skweng — an unresolved association the authors flag as "tantalizing." Used medicinally for colds/bowel disorders. |
| skuy-mwolwop | 'pinellia' | noun (compound) | technical.botanical | — | EMK (Hyangyak kugŭppang) | — | national | grammar_reference | n/a | n/a | p. 88. Transcribed 雉矣毛老邑, same indirect 雉 usage as above. Used in moxibustion and cough suppression. |
| stas-twulhwup | 'spikenard (Aralia cordata)' | noun (compound) | technical.botanical | — | EMK (Hyangyak kugŭppang) | — | national | grammar_reference | n/a | n/a | pp. 88–89. Transcribed 虎驚草; 虎 'tiger' used indirectly to transcribe the syllable sta. |
| ton-nezam | 'Astragalus membranaceus' | noun (compound) | technical.botanical | — | EMK (Hyangyak kugŭppang) | — | national | grammar_reference | n/a | n/a | p. 89. Transcribed 甘板麻 (semantic: 甘 'sweet' = ton) or 數板麻 (數 'number' as a kungana-style phonogram for the same ton). The authors connect this Old Korean ton 'number/sweet' to Written Mongolian togan (mod. tō) 'number' and Manchu ton 'number' — one of the chapter's more striking long-range lexical parallels. |
| *posol (菩薩) | '(uncooked) rice' | noun | core | — | EMK (Jilin leishi, 12th c.) | — | national | grammar_reference | n/a | n/a | p. 90. Phonogram 菩薩 [*pɦuə-sat]; cited as evidence that the later-clustered form psol developed through vowel syncope sometime *after* the 12th c. |
| wotwokputuk / wotwoktwoki | 'arbor monkshood (medicinal herb)' | noun | technical.botanical | — | EMK (Hyangyak kugŭppang, mid-13th c.) → later syncopated LMK/16th-c. forms cited | — | national | grammar_reference | n/a | n/a | p. 90. Hyangyak forms 五得浮得/烏得夫得 point to *wotwokputuk (vowel between p and t); the 1613 Tongŭi pogam already shows the syncopated wotwok-ptwoki, dating the syncope to sometime between the two sources. |
| *hota > tha- (轄打) | 'rides' | verb | core | — | EMK (Jilin leishi) → LMK tha | — | national | grammar_reference | n/a | n/a | p. 90. Phonogram 轄打 [*xɦja:t-ta(jŋ)]; cited as the source's worked example of syncope-then-metathesis producing a later aspirate: *hota > *hta > tha. |
| *hukun (黑根) | 'big' | adjective | core | — | EMK (Jilin leishi) → LMK khun | — | national | grammar_reference | n/a | n/a | p. 90, 95. Phonogram 黑根 [*xəək-kən]; same syncope-to-aspirate mechanism as tha-. |
| *potol (寶妲) | 'daughter' | noun | core | — | EMK (Jilin leishi) → LMK stol (not *ptol) | — | national | grammar_reference | n/a | n/a | p. 90. Phonogram 寶妲 [*puaw-dɦat]; the authors flag the LMK outcome stol as irregular/unexpected given the syncope pattern, possibly reflecting an earlier reinforced [tʔɔl]. |
| azo (아ᅀᅵ) | 'younger brother' | noun | core | — | EMK (Jilin leishi) | — | national | grammar_reference | n/a | n/a | p. 91. Phonogram 了兒 [*liaw-ri]; cited as evidence the Jilin leishi's author deliberately chose characters to represent a [z] sound already present in the 12th c. |
| mazon (마ᅀᆩᆫ) | 'forty' | numeral | core | — | EMK (Jilin leishi) | — | national | grammar_reference | n/a | n/a | p. 91. Phonogram 麻刃 [*ma-rin]. |
| nazi (나ᅀᅵ) | 'shepherd's purse (herb)' | noun | technical.botanical | — | EMK (Hyangyak kugŭppang) | — | national | grammar_reference | n/a | n/a | p. 91. Two transcriptions: 豆音矣薺 (薺 = semantic gloss) and 豆衣乃耳 (乃耳 [*naj-ri] = phonograms for the z sound). |
| ezi (어ᅀᅵ) | 'mother, parent' | noun | core | — | EMK (Hyangyak kugŭppang) | — | national | grammar_reference | n/a | n/a | p. 91. Transcribed 漆矣母 (母 'mother' = gloss) and 漆矣於耳 (於耳 [*ʔyă-ri] = phonograms). |
| saysam > sayzam | 'dodder, love vine' | noun | technical.botanical | — | EMK → LMK (change *s>z argued to occur ~14th c.) | — | national | grammar_reference | n/a | n/a | p. 91. Transcribed 鳥伊麻 (鳥 'bird' = say, 麻 'hemp' = sam, both semantic glosses; 伊 = phonogram for the -y glide). Cited as a case where the z is *not* yet present in the 12th-c. form, contrasting with azo/mazon above. |
| nelsam > nezam | 'Sophora angustifolia (lit. "board-hemp")' | noun (compound) | technical.botanical | — | EMK → LMK | — | national | grammar_reference | n/a | n/a | pp. 91, 94. Transcribed 板麻 'board-hemp'; also cited later (p. 94) to show *l* was still retained in the EMK compound (kyezul-sali /nel-sam written with 乙/characters indicating l), only dropping before dentals later. |
| twuze (두ᅀᅥ) | 'several' | numeral/quantifier | core | — | LMK, derived form | — | national | grammar_reference | n/a | n/a | p. 92. Derived from twul 'two' + se 'three' > *twulse > twuze; cited as a *s>z change example. |
| phuzeli (프ᅀᅥ리) | 'overgrown land' | noun | core | — | LMK, derived form | — | national | grammar_reference | n/a | n/a | p. 92. phul 'grass' + seli 'midst' > *phulseli > phuzeli. |
| hanzwum (한ᅀᅮᆷ) | 'sigh' | noun | core | — | LMK, derived form | — | national | grammar_reference | n/a | n/a | p. 92. From han- + swum 'breath'. |
| kozGay > kozay | 'scissors' | noun | core | — | EMK (Jilin leishi) → LMK → 16th-c. kozay | — | national | grammar_reference | n/a | n/a | p. 92. EMK phonogram 割子蓋 [*kat-tsz-kaj], reconstructed *kozgay; derived from koz- 'cut' (attested 1459 Wŏrin sŏkpo) + nominalizer -kay. Traces the full sound-change chain [*zg] > [*zɤ] > [zɦ] > [z]. |
| kezGwuy > kezwuy | 'earthworm' | noun | core | — | EMK (Jilin leishi) → LMK → 16th-c. kezwuy | — | national | grammar_reference | n/a | n/a | p. 92. EMK phonogram 居兒乎 [*kyə-ri-xɦuə]. |
| taliwuli (다리우리) | 'flatiron' | noun | core | — | EMK (Hyangyak kugŭppang) | — | national | grammar_reference | n/a | n/a | p. 92. Transcribed 多里甫里; the phonogram 甫 is argued to transcribe a labial that later lenited to /W/, offered as evidence a bilabial [b]/[β] existed in EMK even without a dedicated transcription symbol. |
| kulWal (글왈) | 'written letter' | noun (compound) | core | — | 1447 (Yongbi ŏch'ŏn ka 26) | — | national | grammar_reference | n/a | n/a | p. 92. Compound of kul 'writing' + nominal suffix -pal; W shows clear lenition from p, used as the chapter's clean example of /W/ arising intervocalically between y/l and a vowel. |
| twothwol-wam (도톨왐) | 'chestnut-oak nut' | noun (compound) | core | — | 1481 (Tusi ŏnhae 5.26) | — | national | grammar_reference | n/a | n/a | p. 93. < twothwol 'acorn' + pam 'chestnut'. |
| kalwem (갈웜) | 'tiger' | noun (compound) | core | — | 1527 (Hunmong chahoe 1.18) | — | national | grammar_reference | n/a | n/a | p. 93. < kal 'reed' + pem 'tiger' (reed-tiger, presumably a tiger that hides in reeds). |
| tayWat (대왓) | 'bamboo field' | noun (compound) | core | — | 1447 (Yongbi ŏch'ŏn ka 5.26) | — | national | grammar_reference | n/a | n/a | p. 93. < tay 'bamboo' + path 'field'. |
| tayWem (대왐) | 'big tiger' | noun (compound) | core | — | 1447 (Yongbi ŏch'ŏn ka 87) | — | national | grammar_reference | n/a | n/a | p. 93. < tay (Sino-Korean 大) 'big' + pem 'tiger'. |
| meyWas- (메왓-) | 'to bare a shoulder' | verb (compound) | core | — | 1447 (Sŏkpo sangjŏl 9.29) | — | national | grammar_reference | n/a | n/a | p. 93. < mey- 'to shoulder' + pas- 'to take off'. |
| *khat-syi (渴翅) | 'skin' | noun | core | — | EMK (Jilin leishi) → LMK kach | — | national | grammar_reference | n/a | n/a | p. 93. Cited as evidence a terminal aspirated affricate [tsh] existed even in isolation (not just before a vowel/subject particle), contra a tempting alternative explanation. |
| *nat-syi (捺翅) | 'face' | noun | core | — | EMK (Jilin leishi) → LMK noch | — | national | grammar_reference | n/a | n/a | p. 93. Parallel case to khat-syi above. |
| nis (닛) | 'rouge (makeup)' | noun | core | — | EMK (Hyangyak kugŭppang) | — | national | grammar_reference | n/a | n/a | p. 94. Transcribed 你叱花: 花 'flower' = semantic gloss, 你叱 = phonograms for nis; the character 叱 shown here doing double duty as both the genitive particle *s and a plain terminal-consonant marker. |
| pyes (벼ᅀᅥㅅ, "cockscomb") | '(chicken's) comb' | noun | core | — | EMK (Hyangyak kugŭppang) → LMK pyes | — | national | grammar_reference | n/a | n/a | p. 94. Transcribed 雞矣碧叱: 雞 'chicken' = gloss, 矣 = phonogram for genitive *uy, 碧叱 = phonograms for pyes. |
| twolac (도랏) | 'bellflower root' | noun | technical.botanical | — | EMK (Hyangyak kugŭppang) | — | national | grammar_reference | n/a | n/a | p. 94. Transcribed 刀次/道羅次; 次 used as a phonogram for a final affricate *[ts], contrasting with 叱 for *[s]. |
| kach (加次, '(roe deer's) skin') | 'skin (of a roe deer)' | noun | core | — | EMK (Hyangyak kugŭppang) | — | national | grammar_reference | n/a | n/a | p. 94. Transcribed (獐矣)加次; here 次 may represent neutralization of the *c/*ch contrast in final position — the authors flag this specific example as "somewhat suspect" evidence since the 次-for-codas convention is itself inherited from Old Korean orthographic habit, not necessarily phonologically live. |
| pulnamwo (블나모) | 'firewood' | noun (compound) | core | — | EMK (Jilin leishi) | — | national | grammar_reference | n/a | n/a | p. 93–94. Transcribed 孛南木 (*pulnamwo); shows the terminal -l of pul 'fire' retained before the following n of namwo — evidence *l had not yet dropped before dentals/nasals in EMK. |
| kyezul-sali (겨ᅀᅳᆺ사리) | 'mistletoe (lit. "winter-living")' | noun (compound) | technical.botanical | — | EMK (Hyangyak kugŭppang) → LMK kyezusali (l dropped) | — | national | grammar_reference | n/a | n/a | p. 94. Transcribed 冬乙沙伊, with 乙 explicitly marking the [l] still present in EMK; contrast with the LMK form, by which point *l had been lost before dentals. |
| *hoton / kolay / koWoy / mol / poy ('pear') / poy ('boat') / noch | 'one' / 'walnut' / 'trousers' / 'horse' / 'pear' / 'boat' / 'face' | numeral/noun (set) | core | — | EMK (Jilin leishi) | — | national | grammar_reference | n/a | n/a | p. 94–95. Jilin leishi phonograms 河屯/渴來/珂背/末/擺/敗/捺翅, cited together as the evidential set for reconstructing the EMK low back vowel *ɔ (LMK ㆍo). |
| pul / mul (孛/沒) | 'fire' / 'water' | noun | core | — | EMK (Jilin leishi) | — | national | grammar_reference | n/a | n/a | p. 95. Cited as evidence for the EMK high unrounded back vowel *ɨ (LMK ㅡ). |
| 稱 (also 珍 in the 1925 ed.) | 'dragon' | noun | archaic | — | EMK (Jilin leishi) | — | national | grammar_reference | n/a | n/a | p. 95. One of several Jilin leishi words the authors identify as real but lost without a surviving later reflex; reading uncertain. |
| 阿尼 | 'Buddhist nun' | noun | archaic | — | EMK (Jilin leishi); also attested earlier in Old Korean (Samguk sagi vol. 39, Samguk yusa vol. 5) | — | national | grammar_reference | n/a | n/a | p. 95–96. Cross-attested in Silla-period bureaucratic-office and place-name contexts (阿尼典, 阿尼帖), strengthening the case that it was a real, continuously-used word rather than a scribal error. |
| 長官 | 'older brother' | noun | archaic | — | EMK (Jilin leishi) | — | national | grammar_reference | n/a | n/a | p. 95. |
| 漢吟 | 'young woman, female' | noun | archaic | — | EMK (Jilin leishi) | — | national | grammar_reference | n/a | n/a | p. 95. |
| 了寸 | 'married woman' | noun | archaic | — | EMK (Jilin leishi) | — | national | grammar_reference | n/a | n/a | p. 95. |
| 訓鬱 | 'mother's older brother' | noun | archaic | — | EMK (Jilin leishi) | — | national | grammar_reference | n/a | n/a | p. 95. |
| 次鬱 | 'mother's younger brother' | noun | archaic | — | EMK (Jilin leishi) | — | national | grammar_reference | n/a | n/a | p. 95. |
| *ki-sai (只沙伊) | 'dried seeds of Citrus aurantium' | noun | technical.botanical | — | EMK (Hyangyak kugŭppang) | — | national | grammar_reference | n/a | n/a | pp. 95–96. Reconstructed as a compound of ki (< 15th-c. reading of 枳) + sai 'seeds'; this word was entirely lost, replaced by LMK thoyngco. |
| *ki-sali (只沙里皮) | 'rind of Citrus aurantium' | noun | technical.botanical | — | EMK (Hyangyak kugŭppang) | — | national | grammar_reference | n/a | n/a | p. 96. Parallel compound to *ki-sai above. |
| thoyngco (틩조) | 'thick-skinned orange (citrus)' | noun | core | — | LMK (15th c. and after) | — | national | grammar_reference | n/a | n/a | p. 96. The replacement word that displaced the *ki-sai/*ki-sali forms. |
| *pwupoyyaki (夫背也只) | 'white grubs' | noun | core | — | EMK (Hyangyak kugŭppang) | — | national | grammar_reference | n/a | n/a | p. 96. Reconstructed using 15th-c. phonemic values; later displaced in LMK by kwumpeng/kwumpengi. |
| kwumpeng / kwumpengi (굼벙/굼벙이) | 'grub, maggot' | noun | core | — | LMK | — | national | grammar_reference | n/a | n/a | p. 96. Replacement for *pwupoyyaki. |
| *mwoli (毛立) | 'taro' | noun | core | — | EMK (Hyangyak kugŭppang) | — | national | grammar_reference | n/a | n/a | p. 96. Replaced by LMK Sino-Korean thwolan. |
| thwolan (토란, 土卵 "earth egg") | 'taro' | noun | core | — | LMK | — | national | grammar_reference | n/a | n/a | p. 96. Sino-Korean replacement for native *mwoli; literal meaning "earth egg." |
| acilkey-mol (아질게말) | 'stallion' | noun | technical | — | attested 1517/1527 (Pŏnyŏk Pak T'ongsa, Hunmong chahoe); borrowed during Yuan-era contact, 1206–1367 | Koryŏ court/military contact zone with Yuan Mongolia | national | grammar_reference | n/a | n/a | p. 96. < Middle Mongolian (MM) aǯirga. First of the equestrian borrowing set. |
| aktay (악대) | 'gelding' | noun | technical | — | 1517/1527 sources; Yuan-era borrowing | — | national | grammar_reference | n/a | n/a | p. 96. < MM agta. |
| celta-mol (절다말) | 'red horse' | noun | technical | — | 1517/1527 sources | — | national | grammar_reference | n/a | n/a | p. 96. < MM ǯe'erde. |
| kala-mol (가라말) | 'black horse' | noun | technical | — | 1517/1527 sources | — | national | grammar_reference | n/a | n/a | p. 96. < MM qara 'black'. |
| kwola-mol (고라말) | 'brownish horse, roan' | noun | technical | — | 1517/1527 sources | — | national | grammar_reference | n/a | n/a | p. 96. < MM qula 'palomino'. |
| kwuleng-mol (구렁말) | 'chestnut horse' | noun | technical | — | 1517/1527 sources | — | national | grammar_reference | n/a | n/a | p. 96. < Written Mongolian (WM) küreng. |
| kwodolkay (고도개) | 'crupper (harness part)' | noun | technical | — | 1517/1527 sources | — | national | grammar_reference | n/a | n/a | p. 96. < WM qudurga. |
| wolang (오랑) | 'girth (harness part)' | noun | technical | — | 1517/1527 sources | — | national | grammar_reference | n/a | n/a | p. 96. < MM olang. |
| kalcikey (갈지게) | 'brown hunting falcon' | noun | technical | — | 1517/1527 sources; Yuan-era borrowing | — | national | grammar_reference | n/a | n/a | p. 97. < MM qarcigai. First of the falconry borrowing set. |
| kwekcin (궉진) | 'old wild falcon' | noun | technical | — | 1517/1527 sources | — | national | grammar_reference | n/a | n/a | p. 97. < WM kögsin. |
| nachin (나친) | 'male Asiatic sparrow-hawk (Accipiter nisus)' | noun | technical | — | 1517/1527 sources | — | national | grammar_reference | n/a | n/a | p. 97. < WM nacin. |
| pwola-may (보라매) | 'immature hunting falcon' | noun | technical | — | 1517/1527 sources | — | national | grammar_reference | n/a | n/a | p. 97. < WM boro. |
| sywongkwol (숑골) | 'falcon (variant term)' | noun | technical | — | 1517/1527 sources | — | national | grammar_reference | n/a | n/a | p. 97. < WM šingqor/šongqor. |
| twolwongthay (도롱태) | 'Asiatic sparrow-hawk (Accipiter nisus)' | noun | technical | — | 1517/1527 sources | — | national | grammar_reference | n/a | n/a | p. 97. < MM turimtai (also WM turimatai/turumtai). |
| thwuykwon (튀곤) | 'white hunting falcon' | noun | technical | — | 1517/1527 sources | — | national | grammar_reference | n/a | n/a | p. 97. < WM tuigun. |
| kwotwoli (고도리) | 'blunt arrow' | noun | technical | — | 1517/1527 sources; Yuan-era borrowing | — | national | grammar_reference | n/a | n/a | p. 97. < MM godoli. First of the military borrowing set. |
| wonwo / wonoy (오노/오뇌) | 'arrow notch, nock' | noun | technical | — | 1517/1527 sources | — | national | grammar_reference | n/a | n/a | p. 97. < WM onu/oni. |
| pawotal (바오달) | 'military camp' | noun | technical | — | 1517/1527 sources | — | national | grammar_reference | n/a | n/a | p. 97. < WM pagudal / MM ba'u- 'make camp'. |
| sawoli (사오리) | 'stool (to stand on)' | noun | technical | — | 1517/1527 sources | — | national | grammar_reference | n/a | n/a | p. 97. < MM sa'uri / WM saguri. |
| thyellik (텰릭) | "officer's uniform" | noun | technical | — | 1517/1527 sources | — | national | grammar_reference | n/a | n/a | p. 97. < WM terlig. |
| chywulachi (츄라치) | 'military musician who blows a triton shell' | noun | technical | — | 1517/1527 sources | — | national | grammar_reference | n/a | n/a | p. 97. < WM curaci. |
| thalak (타락) | 'milk' | noun | core | — | Yuan-era borrowing, attested LMK | — | national | grammar_reference | n/a | n/a | p. 97. < WM talag. |
| sywula (슈라, 水剌) | 'royal meal (honorific term for food served to the king)' | noun | formal | — | Yuan-era borrowing (uncertain), attested LMK+ | royal court | national | grammar_reference | n/a | n/a | p. 97. Possible source: Middle Mongolian šülen 'soup' or a related word; the authors flag this derivation as "sometimes suggested," not certain. |
| aki pathwol (아기바톨, 阿其拔都) | "the child hero" (nickname of a teenage pirate chieftain) | proper noun / phrase | literary | — | ~end of Koryŏ (per Yongbi ŏch'ŏn ka 7.10 commentary) | Unbong, Chŏlla Province | regional | grammar_reference | n/a | n/a | p. 97–98. aki = native Korean 'child'; pathwol = Mongolian loanword glossed in the source itself as "a brave, unconquerable enemy." |
| pathwol (바톨) | 'hero, brave unconquerable warrior' | noun | technical | — | attested via the aki pathwol anecdote, Yongbi ŏch'ŏn ka (1447) | — | national | grammar_reference | n/a | n/a | p. 98. < Middle Mongolian ba'atur 'hero' — the authors note the gloss itself shows the word "was widely used in Korea at the time." |
| Tuman-kang (두만강, 豆滿江) | 'Tumen River' | proper noun | core | — | Jurchen-contact era (12th–15th c.), river name persists to present | boundary of North Korea/China/Russia | regional | grammar_reference | n/a | n/a | p. 97–98. Jurchen-derived place name; glossed in the Yongbi ŏch'ŏn ka commentary itself via the Jurchen word thwumen 'ten thousand' ("because a multitude of streams flowed into it"). |
| thwumen (투먼) | 'ten thousand' | numeral | technical | — | Jurchen, 12th–15th c. | Hamgyŏng Province contact zone | regional | grammar_reference | n/a | n/a | p. 98. Jurchen-language numeral, cited only via the river-name etymology, not as a borrowed Korean word itself. |
| wehe (워허) | 'rock' | noun | technical | — | Jurchen, cited via Yongbi ŏch'ŏn ka (7.23a) place-name gloss | Jurchen-contact zone (Hamgyŏng Province) | regional | grammar_reference | n/a | n/a | p. 98. Explained in-text: "round stones piled up... In the [Jurchen] language 'rock' is wehe." Cross-confirmed by the same word in Manchu (wehe), a closely related language. |
| tungken (퉁컨, 童巾) | 'bell' (originally 'drum') | noun | technical | — | Jurchen, cited via the place name Chongsŏng ("Bell City") | North Hamgyŏng Province (former Jurchen territory) | regional | grammar_reference | n/a | n/a | p. 98. Sejong sillok geographical annals gloss: "the northern barbarians call a bell tungken." Jurchen materials elsewhere (同肯) give the earlier sense 'drum'; Manchu tungken also means 'drum' — authors infer semantic extension drum→bell paralleling Korean's own pwup→swoy-pwup development. |
| pwup (붑) | 'drum' | noun | archaic | — | LMK | — | national | grammar_reference | n/a | n/a | p. 98. Cited as the original LMK word for 'bell' before being refined to swoy-pwup, drawn on as the Korean-side parallel to the Jurchen tungken drum/bell semantic shift. |
| swoy-pwup (쇠붑) | 'iron drum' (= bell) | noun (compound) | archaic | — | LMK (later than plain pwup) | — | national | grammar_reference | n/a | n/a | p. 98. < swoy 'iron' + pwup 'drum'; the later, more specific LMK term for 'bell'. |
| won (온) | '100' | numeral | archaic | — | EMK (Jilin leishi) | — | national | grammar_reference | n/a | n/a | p. 98–99. Transcribed via phonogram 醞 (百曰醞), i.e. still the native Korean numeral in the 12th c., later written won in 15th-c. texts. |
| cumun (즈믄) | '1,000' | numeral | archaic | — | attested LMK (15th c.), displaced earlier during Koryŏ by the Sino-Korean numeral | — | national | grammar_reference | n/a | n/a | p. 99. Contrasted with the Jilin leishi's 千曰千 entry, where '1,000' is rendered only by the Chinese numeral — evidence the native word was already being displaced by Chinese ch'ŏn during the Koryŏ period even though both coexisted into the 15th c.; cumun disappeared completely from the textual record after the 15th c. |

---

### Grammar points

#### Periodization: Early vs. Late Middle Korean

Middle Korean spans the 10th–16th centuries (Koryŏ founding, AD 918, to the 1592 Japanese invasion).
The authors split it at the 14th century into Early Middle Korean (Koryŏ period, 918–1392) and Late
Middle Korean (first two Chosŏn centuries) — a split justified by **phonological** change (particularly
in the vowel system, discussed under 4.4.2 below) rather than political change. The 1392 Koryŏ→Chosŏn
transition itself (Kaesŏng→Seoul, a short move) is explicitly characterized as having had minimal
linguistic effect; the real discontinuity is the advent of a cohesive alphabetic (Hangul) textual record
in the 15th century, versus EMK's sparse, Chinese-character-only attestation. The authors frame EMK as
still "linguistic prehistory" in the sense that most of its facts must be *reconstructed*, not read
directly off a text (p. 77).

#### A Koguryŏan substratum in Koryŏ vocabulary

Kaegyŏng (the new Koryŏ capital) sat on former Koguryŏ territory annexed by Silla in 668 and held for
nearly three centuries before Koryŏ's founding. The authors reason that Sillan (ancestor of Middle
Korean) was the spoken language there by the 10th century, but argue a Koguryŏan *substratum* likely
survived in the local Sillan dialect even after language shift. Evidence is fragmentary but twofold: the
*namol/*namər 'lead' correspondence and the Koguryŏ 'valley'-word phonogram (呑/旦/頓) surviving into a
1400 glossary as the word for 'village' (p. 78). Both of these substratum words were later *replaced* —
by nap and mozol respectively — by forms of Sillan origin, which the authors read as evidence that the
old southeastern (Sillan) dialect continued to exert influence on the central language well after Koryŏ
was established (p. 79), a pattern they note recurs throughout later Korean history as well.

#### Principal philological sources for Early Middle Korean

Because EMK left no alphabetic record, its phonology must be triangulated from a small set of
non-ideal sources (p. 79–83):
- **Jílín lèishì / Kyerim yusa** (鷄林類事, 1103–4) — the single most important source; treated at
  length below.
- **Hyangyak kugŭppang** (鄕藥救急方, mid-13th c.) — the oldest surviving Korean medical treatise;
  also treated at length below.
- **13th-c. Mongolian loanwords** — first written down centuries later, but still informative about
  Korean phonology at the time of borrowing.
- Minor supplementary sources: the Japanese **Nichū-reki**'s kana-transcribed Korean numerals (noisy,
  "disappointing" data per the authors); Koryŏ-period **vernacular songs** preserved in 15th-c.
  collections (Akhak kwebŏm, Akchang kasa), usable "only with caution"; the **Koryŏ-sa** (1454 official
  history, Classical Chinese, but rich in personal/place names and Mongolian loanwords); and Xu Jing's
  **Xuānhé fēngshǐ Gāolì tújīng** (1124), a Song envoy's travelogue containing a few transliterated
  Korean words with explanatory glosses.

#### The Jílín lèishì: compilation, transmission, and name

Compiled 1103–4 by Sūn Mù, a secretary of the Song legation at the Koryŏ court. The original (reportedly
three chapters on customs/government/language plus a supplement) is lost; only excerpts survive, via two
Chinese encyclopedic compilations (a 1726 Qing volume and the Ming-era Shuō fú, itself preserved only
through 1558/1647/1925 Korean/Chinese re-citations). Despite this chain of loss, the authors judge the
surviving "regional language" (方言) section to preserve "much the same form" as Sun Mu's original
(p. 79–80). The curious title ("Assorted Matters of Jílín/Kyerim") borrows an old Silla state name
("Chicken Forest") tied to the Kim royal founding myth — though the authors flag an alternative
possibility that the name itself may transliterate a native Korean word, now unrecoverable (p. 79).

#### The Jílín lèishì's vocabulary-list format and its reconstruction problem

The language section is a vocabulary list of 350+ words/phrases, each given in the schematic form
"X 曰 Y" ("'X' is called [Y]"), with Y a Chinese-phonogram transliteration of the Korean word (p. 80).
Because the phonograms reflect *late-Song Chinese* readings, recovering the Korean sound requires a
two-step reconstruction: first reconstruct the Chinese reading of each character, then reconcile that
with Korean phonological values independently known from 15th-century Hangul texts. The authors are
explicit that "there is much room for guessing and error" in this chain, even though it remains broadly
useful (p. 80–81).

#### The Hyangyak kugŭppang as a source, and why its phonograms differ in kind

An emergency-herbal-medicine compilation, published mid-13th c. by the Koryŏ's Tripitika agency; the
first edition is lost, and the only surviving copy is a 1417 edition held in Japan. It records "local
names" for 180+ medicinal ingredients using **hun transcriptions** (semantic/meaning-based readings),
occasionally supplemented with phonograms (p. 81). Crucially, unlike the Jílín lèishì (written by a
Chinese author using Chinese sound values), this text was written *by Koreans*, so its phonograms
reflect **Korean** readings of Chinese characters — making it doubly useful: it helps reconstruct EMK
phonology, and separately helps reconstruct how Koreans *read* Chinese characters at the time (which
in turn bears on Old Korean reading traditions) — though the authors flag a circularity risk in using
it for both purposes at once (p. 81).

#### Minor sources: Nichū-reki, Koryŏ songs, Koryŏ-sa, and Xu Jing's travelogue

- **Nichū-reki** (二中曆): a later Japanese compendium (components dating to ~early 12th c.) giving
  kana transcriptions of Korean numerals 1–10. Only the first two numerals ('1', '2') line up well with
  the Jílín lèishì; numerals 3–9 show what the authors interpret as transmission-era scrambling
  (3↔4, 5↔6, possibly 7↔8/8↔9 swapped) — treated as weak/unreliable data overall (p. 80–81).
- **Koryŏ vernacular songs** (preserved in 15th-c. Akhak kwebŏm/Akchang kasa): genuinely EMK-era
  compositions but first committed to writing in the LMK period, so "most traces of Early Middle Korean
  have been lost" in transmission; usable "only with caution" (p. 81–82).
- **Koryŏ-sa** (1454): Classical Chinese official history, valuable chiefly for personal/place names,
  bureaucratic titles, and Mongolian loanwords it preserves, despite being written in a language that
  otherwise obscures Korean structure (p. 82).
- **Xuānhé fēngshǐ Gāolì tújīng** (1124), Xu Jing: a Song envoy's firsthand description of Koryŏ,
  notable for directly transliterating a few Korean words (syem 'island'; the hedgehog-name evidence)
  with the author's own explanatory glosses attached (p. 82).

#### Mongolian-loanword sources and their limits

Contact vocabulary from the Mongol-Yuan period is attested almost entirely in **equestrian, falconry,
and military** semantic domains — the Mongols' own pastoral/military culture — rather than broadly
across the lexicon. Most loanwords were first written down only after the 15th century; the most
reliable transcriptions are the 16th-century Hangul sources **Pŏnyŏk Pak T'ongsa** (1517) and
**Hunmong chahoe** (1527). Mongolian-derived *official titles* in the Koryŏ-sa are explicitly flagged as
less useful, since they were copied wholesale from Chinese sources without any record of their actual
Korean pronunciation (p. 82–83, 96).

#### Kugyŏl: interlinear Chinese-reading annotation

Discovered only in 1973 (a Koryŏ-period Buddhist sutra, the Kuyŏk inwang kyŏng) and more extensively
through the 1990s: faint handwritten interlinear annotations in simplified Chinese characters, called
**kugyŏl** (also t'o 吐), added to Chinese Buddhist/Classical texts to show how to re-read the Chinese
syntax as Korean. Virtually all known kugyŏl texts date to the Koryŏ; the markings were deliberately
unobtrusive and had escaped scholarly notice because they're nearly invisible in photocopies (p. 83).
The authors give a worked illustrative analogy using a hypothetical English sentence annotated the same
way, then an actual example from the Tongmong sŏnsŭp primer, where small inserted particles/markers
(e.g. 厓 "at," 伊 subject marker, 爲尼 "does, and so," 隱 topic marker, 羅 "is") convert bare Classical
Chinese into something readable as Korean syntax, without altering the underlying Chinese text itself
(p. 83–84). A key feature: many kugyŏl symbols could be **abbreviated** into simplified graphic forms
that structurally and visually resemble Japanese katakana (several are formally identical, e.g. イ from
伊 = i in both systems) — the historical relationship between the two systems is unresolved, but the
authors note it is widely believed in both Korea and Japan that katakana's orthographic principles owe
something to earlier Korean peninsula practices (p. 84). Functionally, kugyŏl mixed true phonograms with
meaning-based (hun) indicators, the same dual system seen in Old Korean hyangch'al (p. 84).

#### Kakp'il: stylus-point annotation

A second, independently discovered (2000) annotation system: tiny stylus-made depressions (dots and/or
angled lines) in the paper itself, their meaning depending on position relative to the annotated
characters — even less visually obtrusive than kugyŏl, often indistinguishable from ordinary paper
flaws except for their regularity. Known earlier in Japan (kakuhitsu 角筆) from textual records and
surviving physical styluses; only recently confirmed in Korea too, triggering active joint
Korean-Japanese documentation efforts. Like kugyŏl, kakp'il reveals little about phonology directly but
is informative about particle/grammatical-marker usage (p. 84–85).

#### Two transcription traditions: Chinese-sound phonograms vs. Korean hun/phonogram mixing

The chapter's central methodological point (4.3): the Jílín lèishì's transcriptional characters are
**pure phonograms based on Chinese sound values**, chosen by a Chinese author purely to elicit a
Korean-sounding pronunciation — with no intentional semantic contribution, although the authors show
several cases where the chosen character's *meaning* happens to overlap with the transcribed word's
meaning too (e.g. 刀子曰割 '*kat* "knife"', using a character meaning 'cut'; 傘曰聚笠 'umbrella',
second character meaning 'rain hat'; 水曰沒 '*mut* "water"', character also meaning 'sink') — flagged
as a normal feature of Chinese transcriptional practice generally, not semantic intent (p. 85–86).
The **Hyangyak kugŭppang**, by contrast, continues the native Korean tradition of mixing true phonograms
with **hun readings** (semantic glosses used to indicate a native word), sometimes combining both within
a single compound transcription (worked example: swop-sekun-phul 'Scutellaria baikalensis', transcribed
two different ways, one all-semantic and one mixed) (p. 86–87).

#### The Jílín lèishì's coda patterning and its Middle Chinese explanation

A focused puzzle (p. 85–86): Jílín lèishì transcriptions of Korean syllables ending in -p/-t/-k show
odd correspondences. A velar coda sometimes matches cleanly (flea: *phi-lək → pyelwuk), sometimes not
at all (hwal swo- 'shoot an arrow' has no velar in Korean despite a velar-looking transcription). Dental
*t transcriptions correspond not just to later /l/ (pul, mol) but also to -th, -c, -t, and -s outcomes
in different words — while *p transcriptions consistently map to Korean -p. The authors' explanation:
the Chinese codas being used for transcription reflect **12th-century northern Chinese**, a transitional
stage between 7th–8th-c. "Late Middle Chinese" (which still had crisp -p/-t/-k codas) and 14th-c. "Old
Mandarin" (where these had all weakened to a glottal stop). The 12th-century codas were likely
intermediate, weakened values (something like *b, *r, *g) — which is offered as the reason a single
Chinese coda type could correspond to a spread of different Korean outcomes (p. 86).

#### The Hyangyak kugŭppang's elementary syllabary

The Hyangyak kugŭppang's phonogram usage is described as regular enough to constitute "a kind of
elementary syllabary" — a fixed, limited set of characters each reliably representing one Korean
syllable sound, e.g. 加=ka, 居=ke, 斤=kun, 只=ki, 古=kwo, 乃=na, 你=ni, 多=ta, 刀/道=two, 豆=twu, 羅=la,
老=lwo, 里=li, 亇=ma, 毛=mwo, 勿=mul/mol, 朴=pak, 夫=pwu, 非=pi, 沙=sa, 參=sam, 所=swo, 耳=zi, 阿=a, 於=e,
五=wo, 尤=wu, 隱=un, 伊=i, 也=ya, 余=ye (p. 87). This system is explicitly continuous with the one used
in **Silla** — giving indirect evidence about older phonogram readings (e.g. 只 [*tʂi] = ki) — and the
same simplification habits recur across periods (羅 often abbreviated the same way in earlier texts
too). The authors treat a small set of characters (加, 耳) as rare cross-over cases usable for either
sound or meaning, otherwise noting the two functions were "carefully distinguished" in this text.

#### Hyangch'al-derived coda-transcription characters

A fixed small set of characters used specifically to mark **syllable-final consonants**, carried over
unchanged from the Old Korean hyangch'al transcription system (discussed in the book's preceding
chapter): 乙 (ul) = -l, 音 (um) = -m, 邑 (up) = -p, 叱 (cil) = -s, 次 (cha) = -c (p. 87). The reuse of
this exact coda-marking convention is treated as strong continuity evidence linking EMK orthographic
practice directly back to Silla/Old Korean practice, rather than an independent invention.

#### Direct semantic gloss vs. "kungana"-style indirect (derived) phonograms

The Hyangyak kugŭppang's hun (semantic) usages split into two distinct types (p. 87–88):
1. **Direct gloss**: the Chinese character's own meaning directly matches the Korean word being
   transcribed (冬 'winter' → kyezul; 犬 'dog' → kahi; 山 'mountain' → mwoy; 水 'water' → mul).
2. **Derived (indirect) phonogram**: the character is first linked to a Korean word by *meaning*, and
   then reused purely for its *sound* to transcribe any other syllable with that same sound — e.g. 置
   'put, place' is first associated with Korean twu- 'put' by meaning, then becomes a pure phonogram
   for any twu syllable; 火 'fire' (associated with pul) becomes a phonogram for any pul syllable; 等
   'rank, grade' (associated with the postnoun tol/tul 'and others') becomes a phonogram for tol/tul;
   休 'rest, cease' (associated with mal- 'stop doing') becomes a phonogram for mal.

This two-step process is explicitly compared to the Japanese man'yōgana usage called **kungana** (訓假名)
— the same "semantic bridge, then reused for sound" strategy — making this one of the chapter's clearer
cross-linguistic orthographic parallels (p. 88).

#### Consonant clusters and aspirates: both products of vowel syncope

The profusion of initial consonant clusters attested in 15th-century Korean is argued to have developed
**after** the 12th century, through syncope (deletion) of a vowel that had originally separated the two
consonants — demonstrated by comparing psol 'rice' (EMK *posol, with the vowel still present in the
Jílín lèishì transcription) against the later clustered LMK form, and by wotwokputuk (EMK, Hyangyak
kugŭppang, with the medial vowel intact) against the already-syncopated 1613 form wotwok-ptwoki
(p. 90). **Aspiration** is argued to arise through the *same* mechanism in some cases, via syncope
followed by metathesis: *hota (EMK, 'rides') > *hta > tha (LMK), and *hukun ('big') > khun — i.e.
aspirates were "fewer in number" in EMK than later, with some only emerging as a byproduct of this
syncope-plus-metathesis process (p. 90).

#### Reinforced (tensed) consonants: present but not yet phonologically distinctive

Reinforced/tensed obstruents likely already existed in Old Korean as an *automatic* phonetic effect
following the genitive -s or a verb stem ending in the liquid written 尸 (*r) — but it's unclear when
reinforcement became phonologically *distinctive* in initial position. The authors tentatively place
this as having possibly existed as s-cluster variants by the 15th century (citing *potol 'daughter' →
unexpected LMK stol rather than the expected *ptol as suggestive but ambiguous evidence), but state there
is **no philological evidence** for a genuinely distinctive reinforced-consonant series as early as the
12th century (p. 90).

#### Voiced fricative /z/: origin and phonetic environment

Both principal sources show the EMK language already had a voiced sibilant /z/ (later written with the
LMK letter ᅀ) in some words — e.g. azo 'younger brother', mazon 'forty' (Jílín lèishì); nazi 'shepherd's
purse', ezi 'mother' (Hyangyak kugŭppang) — where the transcriber evidently chose characters specifically
to render a [z] sound already present in the 12th century (p. 91). But **not every** later z traces back
to an EMK z: words like saysam 'dodder' and nelsam 'board-hemp' show *no* z in their EMK transcriptions,
only acquiring it later (sayzam, nezam) — leading the authors to date the regular sound change **s > z**
to around the **14th century**, specifically in the environment **between y/l/n and a vowel** (further
supported by twuze, phuzeli, hanzwum, all derived by the same positional rule) (p. 91–92). Separately,
EMK z could also occur **syllable-finally** as part of a consonant cluster (*zg*), as shown by kozGay
'scissors' and kezGwuy 'earthworm' — with the authors tracing a full diachronic chain of lenition:
[*zg] > [*zɤ] > [zɦ] > [z], the [zɦ] stage surviving into 15th-century Yale romanization as /zG/, before
the z itself disappeared entirely by the 16th century (p. 92).

#### Bilabial fricative /W/: absent from transcription but plausibly present

Unlike /z/, the EMK materials give **no direct transcriptional evidence** for the 15th-century bilabial
fricative /W/ (ㅸ) — but the authors argue this is inconclusive rather than disproof, since Chinese-based
transcription of a sound like [b]/[β] is inherently ambiguous (it could easily be rendered with a
character read [p]/[b] instead), and Sino-Korean itself has never distinguished /W/ from /p/, removing a
potential diagnostic. One Hyangyak kugŭppang transcription (taliwuli 'flatiron', 多里甫里) is read as
positive evidence for an EMK [b] that later lenited, even without a dedicated symbol for it (p. 91–92).
The authors then argue /W/ arose through **lenition in the same phonological environment that produced
/z/** — between y/l and a vowel — citing a chain of compound words where an original p clearly lenited to
W intervocalically: kulWal 'written letter' (kul+pal), twothwolwam 'chestnut-oak nut' (twothwol+pam),
kalwem 'tiger' (kal+pem), tayWat 'bamboo field' (tay+path), tayWem 'big tiger' (tay+pem), meyWas- 'to bare
a shoulder' (mey+pas-) (p. 92–93).

#### Terminal consonant inventory in EMK

EMK, like Old Korean, generally preserved consonant distinctions in syllable-final position. Evidence:
Jílín lèishì khat-syi 'skin' and nat-syi 'face' show a terminal aspirated affricate [tsh] even with no
following vowel or particle attached (ruling out an alternative theory that aspiration there was
conditioned by an unwritten subject particle -i, since the subject particle never appears anywhere
in the Jílín lèishì's phrase examples either) (p. 93). The Hyangyak kugŭppang shows terminal
distinctions even more clearly: 叱 doubles as both the genitive particle *s and a plain terminal-s
marker (nis 'rouge', pyes 'cockscomb'); 次 separately marks a terminal affricate *[ts] (twolac
'bellflower root'), contrasting with 叱's *[s] — though one case (kach '(roe deer) skin') suggests the
*c/*ch contrast may already have been **neutralized** in final position by the 13th century, a reading
the authors flag as "somewhat suspect" since the transcriptional convention itself is inherited from
Old Korean and may not reflect a live phonological contrast (p. 93–94). **Conclusion stated by the
authors**: by the mid-13th century, *c/*ch contrast was neutralized in final position, but *s/*c was
not — meaning the full mid-13th-century terminal consonant inventory was */p, t, k, s, z, c, l, n, m,
ng, h/ (p. 94).

#### The liquid *l: retained in EMK, later lost before dentals

In later Korean, *l drops before the dentals *t, *s, *z, *c, *ch, *n — but the authors show this had
**not yet happened** in EMK. Evidence: pulnamwo 'firewood' (Jílín lèishì, 孛南木) retains the coda -l of
pul 'fire' before the following n of namwo; kyezul-sali 'mistletoe' (Hyangyak kugŭppang, 冬乙沙伊) marks
the l explicitly with 乙; nelsam 'board-hemp' similarly still shows the l. By the time these same
compounds surface in LMK texts (kyezusali, nesam), the l has dropped. Conclusion: *l was lost in this
environment sometime before the latter half of the 15th century, "but the process probably began a
little earlier than that" (p. 94).

#### The "Korean Vowel Shift" (13th–15th c.), reconstructed via Mongolian loanwords

A significant vowel-system change is argued to have occurred between the 13th and 15th centuries,
reconstructed primarily from how Korean rendered **Middle Mongolian** vowels. Middle Mongolian had a
front/back vowel-harmony contrast (front ü, ö, e vs. back u, o, a, with i neutral). In 15th–16th-century
Korean transcriptions of Mongolian loanwords, Mongolian front ü maps to Korean ㅜ [u], front ö maps to
ㅝ [wə], and front e maps to ㅓ [ə]; meanwhile *both* Mongolian back vowels u and o are rendered by the
single Korean vowel ㅗ [o] (p. 94). The authors' key inference: if Korean ㅜ had already been a back
vowel [u] in the 13th century, it should have been used to render a Mongolian *back* vowel instead —
the fact that it renders a Mongolian *front* vowel implies Korean ㅜ's ancestor was itself still a
**front** vowel *ü at the time of borrowing, only backing to [u] by the 15th century. By the same logic,
ㅓ's ancestor was a front vowel *e, not yet [ə] (p. 94–95). Separately, Jílín lèishì transcriptions are
used to reconstruct two more EMK vowel values: a back, slightly rounded *ɔ (ancestor of LMK ㆍo, from
the 河屯/渴來/珂背/末/擺/敗/捺翅 word set) and a mid *ə (ancestor of LMK ㅡu, best evidenced by khun 'big'
< *hukun, 黑根) (p. 95). The chapter closes 4.4 with a full reconstructed correspondence table showing
the 13th-century vowel inventory (*i, *ü, *e, *ə, *u, *ɔ, *a) each shifting — via backing, raising, or
lowering — to its 15th-century Hangul-attested outcome (ㅣ/i, ㅜ/wu, ㅓ/e, ㅡ/u, ㅗ/wo, ㆍ/o, ㅏ/a)
(p. 95).

#### Lexical attrition: words attested in EMK that left no later trace

A recurring theme of section 4.5: several Jílín lèishì and Hyangyak kugŭppang entries appear to record
genuine words that **disappeared entirely** soon after, with no LMK or later reflex at all — e.g. 稱/珍
'dragon', 阿尼 'Buddhist nun' (cross-confirmed from Old Korean Silla sources), 長官 'older brother', 漢吟
'young woman', 了寸 'married woman', 訓鬱/次鬱 'mother's older/younger brother' (p. 95–96); and from the
Hyangyak kugŭppang, *ki-sai/*ki-sali ('citrus seeds/rind', replaced by thoyngco), *pwupoyyaki ('white
grubs', replaced by kwumpeng(i)), and *mwoli ('taro', replaced by the Sino-Korean compound thwolan,
literally "earth egg") (p. 96). The authors treat scribal/transcription error as a real possibility for
any single case but judge the pattern as a whole to be genuine lexical turnover, and raise the
possibility that some still-unidentified Jílín lèishì words may be **surviving Koguryŏ vocabulary**
remnants rather than simply lost Koryŏ-period Korean words (p. 96) — tying back to the substratum
discussion in 4.1.

#### Mongolian contact vocabulary: domain-restricted borrowing

Mongolian loanwords entered Korean almost exclusively through **equestrian, falconry, and military**
vocabulary (with one or two food/drink terms), reflecting the specific nature of Koryŏ-Yuan contact: the
Mongols as a pastoral, military people. The authors explicitly contrast this narrow, functionally
motivated borrowing with the separately discussed (and more systemic) Sinitic borrowing wave (below) —
loanwords from Mongolian are "not especially numerous" overall but still phonologically informative
about both languages at the time of borrowing (p. 96–97). The chapter also preserves one vivid
sociolinguistic anecdote illustrating active, spoken use of a Mongolian loanword (pathwol 'hero') as a
nickname applied by Korean soldiers to a teenage pirate chieftain near the end of Koryŏ — explicitly
glossed as such in the contemporary (1447) source text itself, not a modern reconstruction (p. 97–98).

#### Jurchen contact vocabulary: place names as the main evidentiary channel

Jurchen (the language ancestral to/related to Manchu) left traces concentrated in **place names** in
Hamgyŏng Province, where Jurchen speakers lived from the 12th–15th centuries. The two words recovered
here — thwumen 'ten thousand' (via the Tumen River name) and tungken 'drum/bell' (via the city name
Chongsŏng) — both come embedded in **explicit in-text glosses** supplied by 15th-century Korean sources
themselves (the Yongbi ŏch'ŏn ka commentary, the Sejong sillok geographical annals), not from
independent Jurchen texts. Both are cross-confirmed by matching or closely related forms in **Manchu**,
treated as the single strongest form of corroboration available for this contact layer (p. 97–98). The
drum→bell semantic extension for tungken is explicitly compared to an identical semantic shift that
Korean's own vocabulary underwent independently (pwup → swoy-pwup) — offered as a plausible shared
motivation (both communities' contact with "bells," a newly introduced concept) rather than coincidence
(p. 98).

#### Sinitic vocabulary displacement, illustrated through the numeral system

Chinese-derived vocabulary surged into Korean during Middle Korean times, accelerated by King
Kwangjong's reforms (r. 949–75) — specifically the 958 establishment of a Chinese-style civil service
examination, which incentivized the ruling class's engagement with Chinese writing and, as a direct
consequence, imported specialized/literary Chinese terminology that displaced older native vocabulary
(p. 98). The chapter's worked example is the **numeral system**: the Jílín lèishì (12th c.) still
transcribes '100' with a phonogram for the *native* Korean word (醞 → won), but gives '1,000' using only
the plain Chinese character for 'thousand' — direct contemporary evidence that Koreans had, by the 12th
century, already shifted to the **Chinese** word for the larger number in at least some registers. The
native word for '1,000,' cumun, is independently attested as late as the 15th century, so both native and
Sino-Korean numerals for '1,000' evidently coexisted through the Koryŏ period — but the native word had
"already begun to be displaced" during Koryŏ itself, and disappeared from the textual record completely
after the 15th century (p. 98–99).

---


---

## Korean — Established Vocabulary/Grammar: A History of the Korean Language, Ch. 5 "Late Middle Korean" — 5.1 Sources, 5.2 The Korean Alphabet

**Source:** Ki-Moon Lee & S. Robert Ramsey, *A History of the Korean Language* (Cambridge
University Press, 2011), printed pp. 100–126 (PDF pages 112–138; verified offset
PDF_page = printed_page + 12). Covers the chapter-opening overview of Late Middle Korean, section
5.1 "Sources" (5.1.1 Chinese, 5.1.2 Korean — 15th and 16th century texts), and section 5.2 "The
Korean alphabet" (5.2.1 initial sounds through letter shapes/usage/complex initials, 5.2.2 medial
sounds, 5.2.3 terminal sounds, 5.2.4 combining the letters, 5.2.5 tones, 5.2.6 fifteenth-century
orthography, and the opening of 5.2.7 the transcription of Sino-Korean).

**Coverage note:** This is an academic diachronic-linguistics monograph, not a teaching grammar —
there is no drill/exercise padding to skip. Section 5.1 is primarily a bibliographic survey of
surviving Late Middle Korean texts (titles, dates, library holdings); this content is historically
important for dating/provenance but is NOT vocabulary-table material in the usual sense, so it is
summarized in the Grammar points section as historical/textual background rather than tabulated.
Section 5.2 (the alphabet's design) is where the genuine vocabulary-table-worthy content lives: the
seventeen initial letters and their Chinese-character glosses, the seventeen basic/geminate/cluster
symbols (including archaic jamo no longer used in modern Korean — ㆁ, ㆆ, ㅿ, ㆍ, ㅸ, ㆅ, ㅱ, ㆄ, ㅹ),
the eleven medial (vowel) letters, and the illustrative native-Korean example words the Haerye uses
to demonstrate each letter's use. Archaic jamo and their Yale-romanization transcriptions are
preserved exactly as printed, not normalized to modern equivalents. This source has a clean, genuine
text layer — `pdftotext` renders Hangul, Hanja, and Yale-diacritic romanization correctly; no
font-cipher or vision-reading issue was found anywhere in this range. Confirmed non-overlapping with
all 46 prior established Korean files (no prior extraction touches Hunmin chŏngŭm / Hangul-creation
history).

---

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 訓民正音 (Hunmin chŏngŭm) | "The Correct Sounds for the Instruction of the People" — the 1446 promulgation document for the Korean alphabet | noun (proper, title) | literary | — | 1446 (Hunmin chŏngŭm) | — | — | grammar_reference | n/a | n/a | Two parts, both in Classical Chinese: a 4-leaf primer and the 29-leaf Haerye treatise; p. 102 |
| 訓民正音解例 (Hunmin chŏngŭm haerye) | "Explanations and Examples of the Correct Sounds for the Instruction of the People" — the scholarly treatise explaining the alphabet's design | noun (proper, title) | literary | — | 1446 (Hunmin chŏngŭm) | — | — | grammar_reference | n/a | n/a | Primary source for letter shapes/construction/use; only 1 copy of the original edition survives, found 1940 in Andong; p. 102-103 |
| 訓民正音諺解 (Hunmin chŏngŭm ŏnhae) | the Korean-language translation of the Hunmin chŏngŭm | noun (proper, title) | literary | — | Late Middle Korean (15th-16th c.); believed composed during or shortly after Sejong's reign, published 1459 | — | — | grammar_reference | n/a | n/a | Found attached to vol. 1 of the Wŏrin sŏkpo; p. 103 |
| 龍飛御天歌 (Yongbi ŏch'ŏn ka) | "The Song of the Dragons Flying Through Heaven" — epic poem eulogizing the Chosŏn dynasty's founders | noun (proper, title) | literary | — | 1445 (composed), 1447 (published) | — | — | grammar_reference | n/a | n/a | First literary work ever written in Hangul; 125 stanzas, each with Chinese verse translation + commentary; p. 103-104 |
| 釋譜詳節 (Sŏkpo sangjŏl) | "Detailed Articles on the Record of Sakyamuni" — a Buddhist devotional work | noun (proper, title) | literary | — | 1447 | — | — | grammar_reference | n/a | n/a | One of the few texts noted for natural, unstilted Korean prose style, unlike most ŏnhae-genre texts; p. 104-105 |
| 月印千江之曲 (Wŏrin ch'ŏn'gang chi kok) | "Songs of the Moon's Imprint on the Thousand Rivers" — Buddhist hymns composed by King Sejong himself | noun (proper, title) | literary | — | 1447 | — | — | grammar_reference | n/a | n/a | p. 105-106 |
| 月印釋譜 (Wŏrin sŏkpo) | combined later edition merging the Wŏrin ch'ŏn'gang chi kok and Sŏkpo sangjŏl | noun (proper, title) | literary | — | 1459 | — | — | grammar_reference | n/a | n/a | 25 volumes; p. 107 |
| 東國正韻 (Tongguk chŏngun) | "The Correct Rimes of the Eastern Country" — a prescriptive dictionary of Sino-Korean character pronunciations | noun (proper, title) | technical | — | 1447 (completed) | — | — | grammar_reference | n/a | n/a | Six volumes; prescriptive, not descriptive, pronunciations; used throughout the chapter as the standard source for the "character-gloss" pronunciations of the alphabet's initial letters; p. 106-107 |
| 訓蒙字會 (Hunmong chahoe) | "Collection of Characters for Training the Unenlightened" — Ch'oe Sejin's Sino-Korean glossary | noun (proper, title) | technical | — | 1527 | — | — | dictionary | n/a | n/a | 3,360 Chinese characters with Sino-Korean + native readings; source of the modern Hangul alphabetical order and letter names; p. 113-114 |
| 四聲通解 (Sasŏng t'onghae) | "A Thorough Explanation of the Four Tones" — Ch'oe Sejin's dictionary of Chinese character readings | noun (proper, title) | technical | — | 1517 | — | — | dictionary | n/a | n/a | Records over 460 Korean lexical items; p. 112-113 |
| 諺解 (ŏnhae) | "vernacular exegesis" — a genre of Hangul translation/explication of a Chinese text | noun | technical | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Dominant genre of Late Middle Korean Hangul texts; translation-style prose, not natural idiomatic Korean, with Sŏkpo sangjŏl as a partial exception; p. 100 |
| 口訣 (kugyŏl) | glosses/annotation marks inserted into a Classical Chinese text to aid reading | noun | technical | — | pre-Hangul tradition, continuing into Late Middle Korean | — | — | grammar_reference | n/a | n/a | Earlier notational tradition that influenced the ŏnhae genre; p. 100 |
| 字母 (character mother) | the initial consonant of a Chinese syllable, in traditional Chinese phonology | noun | technical | — | — | — | — | grammar_reference | n/a | n/a | Term adapted by Sejong's commissioners for the Hangul initial sounds (初聲); p. 115 |
| 韻母 (rime mother) | everything in a Chinese syllable besides the initial consonant, in traditional Chinese phonology | noun | technical | — | — | — | — | grammar_reference | n/a | n/a | p. 115 |
| 反切 (fănqiè) | "turning and cutting" — the traditional Chinese two-part spelling method for indicating pronunciation | noun | technical | — | — | — | — | grammar_reference | n/a | n/a | Precursor framework Sejong's three-way syllable analysis improved upon; p. 115 |
| 初聲 (ch'osŏng) | "initial sound" — the first of the Hunmin chŏngŭm's three-way syllable division | noun | technical | — | 1446 (Hunmin chŏngŭm) | — | — | grammar_reference | n/a | n/a | p. 115 |
| 中聲 (chungsŏng) | "medial sound" — the vocalic nucleus of the syllable, Sejong's original contribution over the Chinese two-way model | noun | technical | — | 1446 (Hunmin chŏngŭm) | — | — | grammar_reference | n/a | n/a | p. 115-116 |
| 終聲 (chongsŏng) | "terminal sound" — the syllable-final consonant | noun | technical | — | 1446 (Hunmin chŏngŭm) | — | — | grammar_reference | n/a | n/a | p. 115 |
| ㄱ (kiyŏk) | [k] — molar/velar "wholly clear" initial letter, basic shape | letter/phoneme | core | — | 1446 (Hunmin chŏngŭm) | — | — | grammar_reference | n/a | n/a | Glossed by Chinese character 君; basic letter shape depicts "the outline of the root of the tongue blocking the upper palate"; p. 116-117 |
| ㅋ | [kʰ] — molar "partly clear" initial, derived from ㄱ by stroke addition | letter/phoneme | core | — | 1446 (Hunmin chŏngŭm) | — | — | grammar_reference | n/a | n/a | Glossed by 快; "a little more severe" than ㄱ; p. 116-118 |
| ㄲ (geminate kiyŏk) | [k͈] — "wholly muddy" geminate, used to transcribe Chinese rime-book sounds | letter/phoneme | archaic | — | 1446 (Hunmin chŏngŭm) | — | — | grammar_reference | n/a | n/a | Glossed by 虯; not ordinarily used to write native Korean; p. 116, 119 |
| ㆁ (yet ieung) | [ŋ] — "neither clear nor muddy" molar initial, archaic velar nasal letter no longer used | letter/phoneme | archaic | — | Late Middle Korean (15th-16th c.); disappears from texts after mid-16th c. | — | — | grammar_reference | n/a | n/a | Glossed by 業; chosen over ㄱ as the basic molar letter because ㆁ's sound was judged "too similar" to the laryngeal; gradually fell into disuse, gone by late 16th c.; p. 116-119 |
| ㄴ (nieun) | [n] — lingual "neither clear nor muddy" initial, one of the five basic letters | letter/phoneme | core | — | 1446 (Hunmin chŏngŭm) | — | — | grammar_reference | n/a | n/a | Glossed by 那; basic shape "depicts the outline of the tongue touching the upper palate"; p. 116-117 |
| ㄷ | [t] — lingual "wholly clear" initial, derived from ㄴ | letter/phoneme | core | — | 1446 (Hunmin chŏngŭm) | — | — | grammar_reference | n/a | n/a | Glossed by 斗; p. 116-118 |
| ㅌ | [tʰ] — lingual "partly clear" initial, derived from ㄷ | letter/phoneme | core | — | 1446 (Hunmin chŏngŭm) | — | — | grammar_reference | n/a | n/a | Glossed by 呑; p. 116-118 |
| ㅁ (mieum) | [m] — labial basic letter | letter/phoneme | core | — | 1446 (Hunmin chŏngŭm) | — | — | grammar_reference | n/a | n/a | Glossed by 彌; basic shape "depicts the outline of the mouth"; p. 116-117 |
| ㅂ | [p] — labial "wholly clear" initial, derived from ㅁ | letter/phoneme | core | — | 1446 (Hunmin chŏngŭm) | — | — | grammar_reference | n/a | n/a | Glossed by 彆; p. 116-118 |
| ㅍ | [pʰ] — labial "partly clear" initial, derived from ㅂ | letter/phoneme | core | — | 1446 (Hunmin chŏngŭm) | — | — | grammar_reference | n/a | n/a | Glossed by 漂; p. 116-118 |
| ㅅ (siot) | [s] — incisor basic letter | letter/phoneme | core | — | 1446 (Hunmin chŏngŭm) | — | — | grammar_reference | n/a | n/a | Glossed by 戌; basic shape "depicts the outline of the incisor"; also the single symbol used for the neutralized terminal dental sibilant; p. 116-117, 121-122 |
| ㅈ | [c] — incisor "wholly clear" initial, derived from ㅅ | letter/phoneme | core | — | 1446 (Hunmin chŏngŭm) | — | — | grammar_reference | n/a | n/a | Glossed by 卽; p. 116-118 |
| ㅊ | [cʰ] — incisor "partly clear" initial, derived from ㅈ | letter/phoneme | core | — | 1446 (Hunmin chŏngŭm) | — | — | grammar_reference | n/a | n/a | Glossed by 侵; p. 116-118 |
| ㅇ (ieung) | [∅] — laryngeal basic letter, zero-initial | letter/phoneme | core | — | 1446 (Hunmin chŏngŭm) | — | — | grammar_reference | n/a | n/a | Glossed by 欲; basic shape "depicts the outline of the throat"; p. 116-117 |
| ㆆ (yet ieung with dot / glottal stop) | [q] — laryngeal "partly clear" initial, derived from ㅇ; archaic glottal-stop letter no longer used | letter/phoneme | archaic | — | Late Middle Korean (15th-16th c.); artificial, chiefly used for Chinese-character readings | — | — | grammar_reference | n/a | n/a | Glossed by 挹; omitted from native-word usage examples because created mainly for Chinese transcription; used in native Korean only (a) in the prospective modifier -ulq/olq, and (b) sporadically to replace the "genitive s" after a vowel; p. 117-119 |
| ㅎ (hieuh) | [h] — laryngeal "wholly muddy"-position initial, derived from ㆆ | letter/phoneme | core | — | 1446 (Hunmin chŏngŭm) | — | — | grammar_reference | n/a | n/a | Glossed by 虛; p. 116-118 |
| ㆅ (geminate hieuh) | [h͈] — archaic geminate laryngeal, used only for Chinese rime-book "wholly muddy" sounds | letter/phoneme | archaic | — | Late Middle Korean (15th-16th c.); never revived after the mid-15th c. decline of geminates | — | — | grammar_reference | n/a | n/a | Glossed by 洪; unlike ㅆ, this geminate was never revived once geminate spellings fell out of use after 1465; p. 116-122 |
| ㄹ (rieul) | [l] — semi-lingual initial, falls outside the basic/derived stroke-addition pattern | letter/phoneme | core | — | 1446 (Hunmin chŏngŭm) | — | — | grammar_reference | n/a | n/a | Glossed by 閭; its shape is an altered version of the tongue outline, with "no appropriety for adding strokes"; p. 116-118 |
| ㅿ (pan-siot / semi-incisor) | [z] — semi-incisor initial, archaic voiced sibilant letter no longer used | letter/phoneme | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Glossed by 穰; like ㄹ, its shape is an altered incisor outline with no stroke-addition logic; survives as terminal in certain non-neutralized phonological environments even after the general ㅅ-neutralization rule; p. 116-118, 122 |
| ㅅ cluster letters (ㅺ, ㅼ, ㅽ, ㅳ, ㅄ, ㅶ, ㅷ, ㅴ, ㅵ) | sk-, st-, sp-, pt-, ps-, pc-, pth-, psk-, pst- — word-initial consonant clusters | letter/phoneme | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Illustrated by native examples: sta 따 'earth,' pcak 빡 'one of a pair,' pskum 쁘ㅿㄱ 'crack, opening'; p. 118-119 |
| ᄮ (sn- cluster) | anomalous word-initial cluster | letter/phoneme | archaic | — | 1447 (Sŏkpo sangjŏl) | — | — | grammar_reference | n/a | n/a | Extremely rare; e.g. snahoy 소나히 'man' vs. kasnahoy 갓나히 'woman'; p. 119 |
| ㅸ ("light labial" bieup) | [b] — a light/fricative bilabial letter used in native Korean (distinct from the other light-labial letters, which were Chinese-only) | letter/phoneme | archaic | — | Late Middle Korean, 15th c. | — | — | grammar_reference | n/a | n/a | Written as circle below ㅂ; the only "light labial" (ㅱ, ㅸ, ㆄ, ㅹ) actually used for native words; p. 118-119 |
| ㅱ, ㆄ, ㅹ (other light labials) | light-labial consonant letters used only for transcribing Chinese | letter/phoneme | archaic | — | Late Middle Korean, 15th c. | — | — | grammar_reference | n/a | n/a | p. 119 |
| ㆍ (arae-a) | [ʌ] — one of the three basic medial/vowel letters, "Heaven" | letter/phoneme | archaic | — | 1446 (Hunmin chŏngŭm) | — | — | grammar_reference | n/a | n/a | "Tongue retracts, pronunciation deep"; round outline depicts Heaven; member of the "Three Germinants" (三才); p. 120 |
| ㅡ | [ɨ] — one of the three basic medial letters, "Earth" | letter/phoneme | core | — | 1446 (Hunmin chŏngŭm) | — | — | grammar_reference | n/a | n/a | "Tongue retracts a little, neither deep nor shallow"; flat outline depicts Earth; p. 120 |
| ㅣ | [i] — one of the three basic medial letters, "Man"; the vowel-harmony-neutral vowel | letter/phoneme | core | — | 1446 (Hunmin chŏngŭm) | — | — | grammar_reference | n/a | n/a | "Tongue does not retract, pronunciation shallow"; erect outline depicts Man; explicitly noted as having "no station or number" in the Yin/Yang vowel-harmony grouping; p. 120-121 |
| ㅗ | [o] — composite medial letter (ㆍ combined with ㅡ), "Yang" | letter/phoneme | archaic | — | 1446 (Hunmin chŏngŭm) | — | — | grammar_reference | n/a | n/a | "Same as ㆍ, only the mouth is contracted"; p. 120-121 |
| ㅏ | [a] — composite medial letter (ㅣ combined with ㆍ), "Yang" | letter/phoneme | core | — | 1446 (Hunmin chŏngŭm) | — | — | grammar_reference | n/a | n/a | "Same as ㆍ, only the mouth is spread"; p. 120-121 |
| ㅜ | [u] — composite medial letter (ㅡ combined with ㆍ), "Yin" | letter/phoneme | core | — | 1446 (Hunmin chŏngŭm) | — | — | grammar_reference | n/a | n/a | "Same as ㅡ, only the mouth is contracted"; p. 120-121 |
| ㆎ | [ə] — composite medial letter (ㆍ combined with ㅣ), "Yin"; archaic letter no longer used as such | letter/phoneme | archaic | — | 1446 (Hunmin chŏngŭm) | — | — | grammar_reference | n/a | n/a | "Same as ㅡ, only the mouth is spread"; p. 120-121 |
| ㅛ | [yo] — composite medial letter, "arises from ㅣ" version of ㅗ, "Yang" | letter/phoneme | core | — | 1446 (Hunmin chŏngŭm) | — | — | grammar_reference | n/a | n/a | p. 120-121 |
| ㅑ | [ya] — composite medial letter, "arises from ㅣ" version of ㅏ, "Yang" | letter/phoneme | core | — | 1446 (Hunmin chŏngŭm) | — | — | grammar_reference | n/a | n/a | p. 120-121 |
| ㅠ | [yu] — composite medial letter, "arises from ㅣ" version of ㅜ, "Yin" | letter/phoneme | core | — | 1446 (Hunmin chŏngŭm) | — | — | grammar_reference | n/a | n/a | p. 120-121 |
| ㅕ | [yə] — composite medial letter, "arises from ㅣ" version of ㆎ, "Yin" | letter/phoneme | core | — | 1446 (Hunmin chŏngŭm) | — | — | grammar_reference | n/a | n/a | p. 120-121 |
| 三才 (Three Germinants) | Heaven, Earth, and Man — the neo-Confucian philosophical framework underlying the three basic medial letters | noun | literary | — | 1446 (Hunmin chŏngŭm) | — | — | grammar_reference | n/a | n/a | p. 120 |
| 방점 (side dots, 傍點) | diacritic dots placed to the left of a syllable marking its tone | noun | technical | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | One dot = departing/high tone; two dots = rising tone; no dots = level/low tone; p. 122-123 |
| 사이ㅅ (sai-sios, "genitive s") | a linking particle connecting two nouns, conventionally transcribed as s | noun/particle | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Phonetically realized variably as /s/, /z/ (ㅿ, in voiced environments), or as reinforcement (replaced by a homorganic stop or glottal stop ㆆ) depending on environment, per the Yongbi ŏch'ŏn ka and Hunmin chŏngŭm ŏnhae; later texts settle on a uniform morphophonemic s spelling; example: phuls nip 픐닙 'blade of grass'; p. 124-125 |
| 값 (kaps) | 'price, wage' | noun | core | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Illustrates morphophonemic -ps cluster: kap.s_i 갑시 (+subject particle i) vs. kap_two 갑도 (+focus particle two); p. 124 |
| 깊- (kiph-) | 'deep' | verb (stem) | core | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Stem alternation: kiphuni 기프니 vs. kipkwo 깁고; p. 124 |
| 사람 (salom) | 'person' | noun | core | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Illustrates syllable-boundary liaison: salo.m_i 사미, salo.m_ol 사몰 (final -m resyllabifies onto a following vowel-initial particle) — contrasts with modern fixed-shape orthography salam_i 사람이; p. 124 |
| 먹- (mek-) | 'eat' | verb (stem) | core | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | mek.ko 먹고 vs. me.kuni 머그니; p. 124 |
| 홀 (kes)/-ㆆ/-올ㆆ (prospective modifier -ulq/olq) | marks a prospective/future-oriented nominal modification | suffix | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | One of the only native-Korean uses of ㆆ; example hwolq (kes) ᄒᆶ 것 '(something) to be done'; p. 117-118 |
| 쏘다 (ssota) | 'shoot something' | verb | core | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Minimal-pair geminate example from the Haerye, contrasted with 소다 (swota) 'turn something over'; p. 119 |
| 혀 (hye) | 'tongue' | noun | core | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Minimal-pair geminate example contrasted with hhye 혀 'pull' (ㆅ); p. 119 |
| 괴여 (kwoyye) / 괴ᅧ (kwoyGye) | 'loving someone' / 'being loved by someone' | verb | core | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Illustrates ㆀ geminate distinguishing active from passive voice; p. 119 |
| 活 (hwal) | 활 'bow, arc' | noun | core | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Haerye's example of even/level tone; p. 123 |
| 돌 (twŏl) | :돌 'stone' | noun | core | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Haerye's example of rising tone (two dots); p. 123 |
| 갈 (kál) | .갈 'knife, sword' | noun | core | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Haerye's example of departing tone (one dot); p. 123 |
| 붇 (pwut) | 붇 'writing brush' | noun | core | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Haerye's example of entering tone (stop-final syllable); p. 123 |

**Morpheme breakdown.** Korean's agglutinative morphology is already the convention established in
prior extraction files; the items below are specifically script-mechanical/phonological compositions
relevant to this chunk, not ordinary word-formation, so they are noted inline above rather than
broken out separately (e.g. the sai-sios/genitive-s realization, the prospective modifier -ulq/olq,
and the liaison behavior of salom). No new agglutinative *word*-formation patterns beyond what prior
Korean files already document were found in this chunk — this section's compositionality is at the
sub-phonemic (letter/stroke) level, covered under Grammar points below.

### Grammar points

#### The three-way syllable division (초성/중성/종성)

Chinese phonological science had divided the syllable into two parts (the fănqiè "character
mother"/"rime mother" split). Sejong's innovation was a three-way division into initial (初聲),
medial (中聲), and terminal (終聲) sound. Because initials had already been fully worked out within
the Chinese-derived framework, Sejong realized the same set of symbols could represent terminal
consonants too ("for the terminal sounds, one again uses the initial sounds") — leaving only the
medial, the vocalic nucleus, as a genuinely new category requiring new symbols. This discovery of
the vowel as a distinct, symbol-worthy unit is what turned the system into a true alphabet rather
than a syllabary. (p. 115-116)

#### Letter design: articulatory iconicity of the five basic initial letters

Five "basic" initial letters were created by modeling each letter's shape on the articulatory organs
used to pronounce it: ㄱ [k] (molar) depicts the tongue root blocking the palate; ㄴ [n] (lingual)
depicts the tongue touching the palate; ㅁ [m] (labial) depicts the outline of the mouth; ㅅ [s]
(incisor) depicts the outline of the incisor; ㅇ [∅] (laryngeal) depicts the outline of the throat.
These five represented the phonetically "weakest" sound at each place of articulation. (p. 116-117)

#### The basic-vs-derived stroke-addition system

All remaining initial letters are derived from the five basics by adding a stroke, with each added
stroke making the sound more "severe" (roughly, more aspirated/fricated): ㄱ→ㅋ, ㄴ→ㄷ→ㅌ, ㅁ→ㅂ→ㅍ,
ㅅ→ㅈ→ㅊ, ㅇ→ㆆ→ㅎ. This is a fully systematic, featural design — letter shape iconically encodes
phonetic relatedness, not arbitrary convention. Two consonants, ㄹ [l] and ㅿ [z], fall outside this
pattern: their shapes are altered versions of the tongue/incisor outlines, but stroke-addition was
judged inappropriate for them, so they stand as shape-outliers within an otherwise systematic
derivation chart. (p. 117-118)

#### Geminate letters and their restricted native-word distribution

Six initials could be doubled into geminates (ㄲ, ㄸ, ㅃ, ㅉ, ㅆ, ㆅ), primarily to transcribe the
"wholly muddy" (voiced obstruent) series of Chinese rime-book phonology — they were not the ordinary
way of writing native Korean. In native words, geminates mainly arose from doubling an initial
consonant after the prospective modifier -u/olq (with the ㆆ of the modifier itself then left
unwritten), plus a handful of lexically specific minimal pairs the Haerye cites directly (e.g. hye
'tongue' vs. hhye 'pull'; swota 'turn over' vs. ssota 'shoot'). After 1465 (starting with the Wŏn'gak
kyŏng ŏnhae), initial geminates nearly vanish from the textual record — the phonemic plain/reinforced
obstruent distinction stopped being written — only to be restored for ㅆ (but never for ㆅ) in
16th-century texts. (p. 118-120)

#### Complex initial clusters

Two or three initial letters could be written side by side as true consonant clusters (distinct from
geminates): sk-, st-, sp-, pt-, ps-, pc-, pth-, psk-, pst- (ㅺ, ㅼ, ㅽ, ㅳ, ㅄ, ㅶ, ㅷ, ㅴ, ㅵ) are
common word-initially in Late Middle Korean texts, with rarer anomalous clusters like sn- (ᄮ) and
even a one-off "chkh" cluster used to transcribe a Jurchen place name in the Yongbi ŏch'ŏn ka.
(p. 118-119)

#### "Light labial" letters and the ○-under-ㅂ device

A separate symbol-formation device — writing the laryngeal ㅇ directly beneath a labial letter —
produced a family of "light labial" sounds (ㅱ, ㅸ, ㆄ, ㅹ), explained in the Haerye as sounds where
"the lips join only momentarily and the pronunciation is more throatish" (i.e., bilabial fricatives).
Of these four, only ㅸ [b] was ever used to write native Korean words; the rest were reserved for
transcribing Chinese. (p. 119)

#### The medial (vowel) letters: philosophical design and vowel harmony

Eleven medial letters were created, unlike the initials, with no correlate in Chinese phonological
tradition — this was Sejong's genuinely original contribution. Three basic letters (ㆍ, ㅡ, ㅣ) were
devised around neo-Confucian cosmology as the "Three Germinants" (三才: Heaven/Earth/Man), each
justified by both an articulatory description (tongue retraction, "deep" vs. "shallow" pronunciation)
and a graphic/philosophical rationale (round=Heaven, flat=Earth, erect=Man). The remaining eight
medials are composite shapes built by combining the three basics, and are explicitly sorted into
"Yang" (ㅗ, ㅏ, ㅛ, ㅑ — circle/dot above or outside) and "Yin" (ㅜ, ㆎ, ㅠ, ㅕ — circle/dot below or
inside) groups. This Yang/Yin split is not merely philosophical decoration — the authors note it
tracks real vowel harmony oppositions in the language, with ㅣ [i] singled out as having "no station
or number," i.e., standing outside the harmony system as its neutral vowel. This is one of the
earliest attested explicit analyses of vowel harmony as a linguistic system. (p. 120-121)

#### Terminal sounds and the "eight final letters" phonemic decision

Although terminals were formally identified with the initial letters, the Haerye restricts practical
terminal spelling to only eight of the seventeen initial symbols (ㄱ, ㆁ, ㄷ, ㄴ, ㅂ, ㅁ, ㅅ, ㄹ),
explicitly reasoning that word-final dental sibilants (/s, c, z, ch/) are phonemically neutralized to
[s] in that position, so only ㅅ is needed to spell them — a deliberate choice of a phonemic (not
morphophonemic) orthography, which the authors analyze in exactly those terms. This "eight final
sounds" rule holds almost universally in the fifteenth/sixteenth-century textual record, with the
Yongbi ŏch'ŏn ka and Wŏrin ch'ŏn'gang chi kok (both 1447, unusually early) as the only real
exceptions, writing non-neutralized terminal ㅿ, ㅈ, ㅊ, ㅌ, ㅍ in some words — suggesting an early,
soon-resolved scholarly dispute over which orthographic principle to adopt. Terminal clusters (ㄳ,
ㅧ, ㄺ, ㄻ, ㄼ, ㅭ = ks, ns, lk, lm, lp, lq) also occur, distinct from the "genitive s" phenomenon.
(p. 121-122)

#### Combining letters into syllable blocks

The Haerye specifies a positional rule for assembling the three sound-types into a single visual
syllable block: initials sit above or to the left of the medial; "round" and "horizontal" medials
(ㆍ, ㅡ, ㅗ, ㅜ, ㅛ, ㅠ) sit below the initial, while "vertical" medials (ㅣ, ㅏ, ㅑ, ㅓ, ㅕ) sit to the
initial's right; terminals sit below both. This establishes Hangul as alphabetic in its underlying
phonemic inventory but syllabic in its visual composition — letter shapes and stacking rules were
co-designed with this syllable-block constraint from the start. (p. 122)

#### Tone marking via "side dots" (傍點)

The Hunmin chŏngŭm records a full suprasegmental tone system using diacritic dots placed to the left
of a syllable: one dot = departing/high tone, two dots = rising tone, no dots = level/low tone. This
convention borrows Chinese four-tone terminology (including a Chinese-only "entering tone" category
for stop-final syllables), but the Haerye is explicit that Korean's own stop-final syllables are NOT
pitch-neutralized the way Chinese's are — the authors correctly recognized that Chinese terminology
didn't fully map onto Korean facts, and did not force a false equivalence. This tone-marking system
was followed "more or less faithfully" through the end of the Middle Korean period, documenting a
pitch-accent/tone system that later disappeared from the standard language. (p. 122-123)

#### Fifteenth-century orthography: a deliberately phonemic (not morphophonemic) writing system

Beyond the terminal-letter decision above, the chapter argues fifteenth-century Hangul spelling was
generally phonemic throughout: morphophonemic alternations were written as pronounced in context
rather than kept visually constant across a word's different forms (e.g. salom 'person' resyllabifies
its final -m onto a following vowel-initial particle in writing — salo.m_i — unlike modern fixed-form
orthography salam_i). This consistency is argued to reflect real, worked-out orthographic rules
rather than haphazard scribal practice, given how uniformly it is followed across independently
published texts. Some alternation was nonetheless left untranscribed (e.g. nasal assimilation:
mitnun 믿는, not minnun, despite the assimilation being real), and syllable-boundary-ambiguous cases
(e.g. terminal -s before a following onset) produced genuine alternate spellings. (p. 123-124)

#### The "genitive s" (사이ㅅ, sai-sios) as the orthography's one major morphophonemic exception

Unlike the otherwise-phonemic system, the linking particle conventionally called "genitive s" is the
orthography's one systematic morphophonemic holdout: two very early texts (Yongbi ŏch'ŏn ka,
Hunmin chŏngŭm ŏnhae, both close to 1446-47) show it transcribed differently depending on phonological
environment — plain s before most obstruents, ㅿ (z) in voiced environments (after vowels, laterals,
nasals), and replacement by a homorganic stop or the glottal stop ㆆ in certain other environments —
suggesting it was realized phonetically in multiple ways, likely as reinforcement of the following
consonant. This fine-grained phonetic transcription proved too cumbersome for practical use, and
later/other texts settle on a single uniform morphophonemic spelling (s) regardless of environment.
(p. 124-125)

#### Sino-Korean transcription and the Tongguk chŏngun's artificial/prescriptive readings

Sejong's stated purpose for the alphabet (per his own preface, quoted directly: Korean's sounds don't
map onto Chinese characters, and the common people need a way to "express their feelings") was to
write native Korean — but from the start the new letters were also used to transcribe Chinese
character readings, following the deliberately prescriptive, "corrected" pronunciations laid out in
the 1447 Tongguk chŏngun (e.g. geminates, a glottal stop, and a velar nasal were used as Tongguk
chŏngun initials specifically to standardize "wholly muddy" Chinese sounds not naturally occurring
that way in contemporary spoken Korean). The chapter frames this as evidence that the Hunmin
chŏngŭm's own initial-sound framework was explicitly built on, and partly in service of, the
inherited Chinese "character mother" phonological tradition — the two systems (native-Korean
phonemic writing and Sino-Korean prescriptive transcription) coexist throughout the period's texts.
(p. 125-126, continuing into the next chunk)

#### Historical/textual background (section 5.1, summarized, not tabulated)

Late Middle Korean (15th-16th c.) is the earliest fully attested stage of Korean, thanks entirely to
Hangul's invention — pre-1446 records are fragmentary and require reconstruction. The alphabetic
record runs from the 1446 Hunmin chŏngŭm to the 1592 Japanese invasion (Imjin War). Most surviving
texts are government-produced Buddhist or Neo-Confucian ŏnhae translations, overwhelmingly from the
Seoul-area upper-class register (reflecting the court/government offices — e.g. the Vernacular Script
Commission, 諺文廳, and the General Directorate for the Publication of Sūtras, 刊經都監 — that produced
most of them). A pre-Hangul Chinese-government glossary, the Cháoxiān-guǎn yìyǔ (c. 1400, 朝鮮館譯語,
590 entries using Chinese characters as phonograms), supplements the alphabetic record and is
classified as Late Middle Korean by its linguistic features despite predating Hangul. Key named
reigns/text-production periods: Sejong (r. 1418-50, the inventor-king's own reign, source of most of
the foundational texts), Sejo (r. 1455-68, Buddhist-text production boom via the Kan'gyŏng Togam),
Sŏngjong (r. 1469-94, shift toward Neo-Confucian didactic works as Buddhism's influence waned),
Yŏnsan'gun (r. 1494-1506), Chungjong (r. 1506-44), and Sŏnjo (r. 1567-1608, last reign showing genuine
Middle Korean features before the Early Modern transition). Ch'oe Sejin, a Chinese-interpretation
professor, is highlighted as the central figure in non-literary/pedagogical Hangul use (bilingual
dictionaries and colloquial-Chinese textbooks), and his 1527 Hunmong chahoe is specifically credited
as the source of the modern Hangul letter-naming and alphabetical-order conventions still used today
— a direct, traceable link between a 500-year-old glossary and the modern Korean alphabet's everyday
naming. (p. 100-114)

---


---

## Korean — Established Vocabulary/Grammar: A History of the Korean Language, §5.3 "Phonology" (Late Middle Korean)

**Source:** Ki-Moon Lee & S. Robert Ramsey, *A History of the Korean Language* (Cambridge University
Press, 2011), printed pp. 127–168 (PDF pp. 139–180), chapter 5.3 "Phonology," within the "Late Middle
Korean" chapter.

**Coverage note:** This is an academic diachronic-linguistics monograph, not a teaching grammar, and
this particular section is a dense historical-phonology chapter. Per the extraction spec's guidance for
this kind of source, most of the real content lives in the **Grammar points** section below, organized
as one subsection per named phonological phenomenon/sound-change rule (consonant system, vowel system,
vowel harmony, and the Late Middle Korean pitch/tone-accent system). All illustrative example words the
source cites to demonstrate a given sound or change are pulled into the **Vocabulary** table, tagged by
era, with closely related orthographic doublets/variants of the *same* lexical item folded into one row
(variant spellings noted in the Notes column) rather than given a separate row each, to avoid padding
the table with near-duplicate entries for what is really one word. Confirmed non-overlapping with all
46 existing established Korean files (Old/Middle Korean historical-phonology terminology was
grep-checked with zero hits beforehand).

**Extraction-quality caveat:** The source text has a clean, genuine text layer (`pdftotext`, no cipher,
no vision-reading needed) for ordinary prose and most Hangul/Hanja. However, this chapter's special
philological notation — pitch-marking diacritics (acute/grave accents marking Middle Korean tone over
romanized syllables, e.g. à, á, ă), the "side dot" tone notation described in prose (앞 dots to the
left of a Hangul syllable, rendered in the PDF as literal raised dots before the syllable), and a
handful of rare Hangul jamo combinations (e.g. the "double-zero" symbol ㆀ, the doubled-tick vowel
symbols ᆝ/ᆜ/ᆢ) — did not survive `pdftotext` extraction cleanly in all cases; some combining
diacritics and a few Hangul codepoints dropped out of the raw text, leaving gaps or bare base letters.
Where this occurs below, the surrounding prose context and page citation are preserved so the specific
passage can be checked against the original PDF if exact pitch-marking matters. This is noted per the
spec's "extracted summary vs. primary source" principle — treat this file as a finding aid, not the
final word on exact diacritic placement.

---

### Vocabulary

Illustrative example words cited in the source to demonstrate specific Late Middle Korean (LMK) sound
patterns or historical sound changes. All LMK-period forms are tagged Attested Era "Late Middle Korean
(15th-16th c.)" per dispatch instruction; reconstructed pre-LMK forms (marked with `*` in the source)
and modern-dialect comparison forms are tagged accordingly in the Notes/Attested Era columns instead.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| polh → phol | 'arm' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Early example (15th c.) of a plain-initial word developing an aspirated initial; p. 128 |
| kwoh → khwo (코) | 'nose' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Developed aspirated initial in latter half of 16th c.; p. 128 |
| kalh → khal (칼) | 'knife' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Same aspiration development as kwoh/khwo; p. 128 |
| ho- (다) / tha (타) | 'is, do' (contracted with following element) | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Contraction of verb ho- 'do' via h + plain consonant metathesis producing aspirates; p. 128 |
| kwum.k_i (굼기) vs. swumwul kkwum.k_i (수물 꿈기) | 'hole (as subject)' vs. 'hole to hide in' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Reinforcement after the prospective modifier -ulq/olq; cited from 1459 Wŏrin sŏkpo 2:51a; p. 129 |
| CYWONGCYWONG k kwos (種죵種죵 ㄱ 곳) | 'all kinds of flowers' | phrase | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | "Genitive s" replaced by homorganic stop before flower names; 1447 Sekpo sangjŏl 9:22b; p. 129 |
| salom_p seli_'la | 'it is in the midst of people' | phrase | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | 1459 Wŏrin sŏkpo 1:19b; genitive-s replacement evidence; p. 129 |
| mac- (맞-) / yenc- (엱-) / cwoch- (좇-) + -sop- | 'meet' / 'place' / 'chase' + deferential suffix | verb stem | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Forms ma.ccoWi 마, yen.ccopkwo 연고, cwo.ccowa 조와 — only environment where reinforced cc occurs, word-medially; p. 130 |
| nwun.ccozo (눈) | 'pupil of the eye' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Compound of nwun 'eye' + genitive s + cozo 'nucleus, kernel'; also spelled nwunt.cozo/nwuns.cozo/nwun.cozo; p. 130 |
| hhye- (- 'pull') | 'pull' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Only native stem with reinforced hh (ㆅ); compounds spa.hhye- 'extract,' nilu.hhye- 'raise up,' twolo.hhye- 'turn head,' twulu.hhye- 'turn around'; replaced by plain h from 1465; p. 130 |
| kwoyOOye (괴) | 'being loved by someone' | verb form | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Illustrates double-zero symbol ㆀ marking passive/causative morpheme after -Vy stem; from kwoy- 'love'; p. 130 |
| moyOOi.nonila (니라) | 'is bound to, by' | verb form | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | From moy- 'bind, tie'; double-zero ㆀ example; p. 130 |
| sta (earth), pcak (one of a pair), pskum (crack, opening) | 'earth' / 'one of a pair' / 'crack, opening' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Haerye's three canonical examples of the three initial-cluster types (sC-, pC-, psC-); p. 131 |
| spul / stek / skwum | 'horn' / 'rice cake' / 'dream' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | sC- cluster examples; p. 131 |
| ptut / ptho- / psol / pcak | 'intent' / 'pluck' / '(uncooked) rice' / 'one of a pair' | noun/verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | pC- cluster examples; p. 131 |
| pstay / pskwul | 'time' / 'honey' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | psC- cluster examples; p. 131 |
| psol (*posol) | '(uncooked) rice' | noun | archaic | — | Early Middle Korean (reconstructed, c. 1103) | — | — | grammar_reference | n/a | n/a | Jı̄lı́n lèishì (c. 1103) phonograms 菩薩 indicate earlier form *posol, showing later syncope of the medial vowel; p. 131 |
| wotwoktwoki (오독기) | 'arbor monkshood' (medicinal herb) | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Tongŭi pogam (compiled late 16th c., pub. 1613) transcription wotwok.ptwoki; earlier Hyangyak kugŭppang (c. 1250) points to *wotwokputuk; p. 131 |
| pskay- / psketi- / pskey- / psko- / pski- / pskul / pskum / psto.li / pstilG-～pstilo- | 'break' / 'collapse, fall in' / 'thread, stick through' / 'peel, hatch' / 'stick in' / 'chisel' / 'crack, interstice' / 'break, shatter' / 'pierce, gore, stick, poke' | verb/noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Semantic word family ("breaking/cracking/piercing") built on preverb pozo-～poso- 'break, shatter'; p. 131-132 |
| pskwul (honey) / pskwu- (borrow) / pstuli (smallpox) | 'honey' / 'borrow' / 'smallpox' | noun/verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Words with opaque etymologies among the pst-/psk- cluster lexical anomalies; p. 132 |
| cwop-ssal (좁쌀) | 'hulled millet' | noun | archaic | — | contemporary (source published 2011; traced to LMK cluster origin) | — | — | grammar_reference | n/a | n/a | cwo 'millet' + ssal 'rice' — the p is a trace of the original pC- cluster of psol 'rice'; p. 132 |
| chap-ssal (찹쌀) | 'glutinous rice' | noun | archaic | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | < chal- 'sticky' + ssal; same p-trace phenomenon; p. 132 |
| hayp-ssal (햅쌀) | 'new rice' | noun | archaic | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | < hay 'year' + ssal; same p-trace phenomenon; p. 132 |
| pyep-ssi (볍씨) | 'rice seed' | noun | archaic | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | pye 'rice plant' + ssi, showing ssi < psi; p. 132 |
| ip-ccak (입짝) | 'this side' | noun | regional | — | contemporary (source published 2011) | Kangwŏn, Kyŏnggi | regional | grammar_reference | n/a | n/a | Confirms ccak 'side' was once pcak; explicitly marked as regional dialect usage by the source; p. 132 |
| ipttay (입때) / cepttay (접때) | '(until) that time' / 'that time' | noun | archaic | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | i/ce + ttay, preserving earlier p- of pstay 'time'; p. 132 |
| hamkkey (함께) < hon pskuy | 'together' | adverb | archaic | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | From 15th-c. hon pskuy 'at one and the same time'; 16th-c. attested variant hom skuy (1518 Pŏnyŏk sohak 10:6) shows nasal assimilation n>m before labial; p. 132 |
| stol (*potol) | 'daughter' | noun | archaic | — | Koryŏ period (reconstructed) / Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Jı̄lı́n lèishì phonograms 寶妲 point to *potol (labial, not s-), yet LMK texts write only stol; etymological puzzle noted by the authors; p. 132-133 |
| kuz(G)- (그-～-) / skuzu- | 'drag' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Emphatic sC- variant of plain-initial verb, e.g. skuzul ssila (1463 Pŏphwa kyŏng ŏnhae 7:91); p. 133 |
| pipuy- / spipuy- ; twutuli- / stwutuli- | 'rub' / 'beat' (plain vs. emphatic reinforced variants) | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Coexisting plain and sC-emphatic doublets; p. 133 |
| tih- / stih- ; pih- / spih- | 'pound' / 'scatter, sprinkle' (plain vs. emphatic) | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | stih-/spih- variants appear from Kugŭppang ŏnhae (c. 1466); p. 133 |
| ssip- (씹-) / spwupuyl- (븰-) / ssus- (씃-) | 'chew' / 'rub' / 'wash' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | 1527 Hunmong chahoe emphatic-vocabulary forms (ssus- only in first edition); p. 133 |
| skulh- (-) / ssahol- (싸-) | 'boil' / 'chop' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | 1542 Punmun onyŏk ihae pang emphatic forms; p. 133 |
| ccokkum vs. cokum; kkam- vs. kam-; ssey- vs. sey-; kkochwu vs. kochwu | 'a little' / 'wash' / 'strong' / 'chili pepper' (reinforced = more emphatic/intense than plain) | adverb/verb/adjective/noun | contemporary | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | Modern illustration that the plain-to-reinforced emphatic process (footnote 9) is still ongoing today; p. 133 footnote |
| skocang (장) > skoci (지) > kkaci (까지) | 'until, to that extent' | particle | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | From kocang (장, < koz 'brink') + genitive s; historical source of the modern particle kkaci; p. 133 |
| skuy () > kkey (께) | honorific dative particle | particle | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Genitive-s-formed postposition, ancestor of modern kkey; p. 133 |
| stolom () > ttalum (따름) | 'just, only' | particle | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Genitive-s-formed, ancestor of modern ttalum; p. 133 |
| poys kwoc (곶) | 'pear blossom' | noun phrase | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | 1446 Hunmin chŏngŭm; genitive s + kwoc 'flower' producing reinforcement; p. 133 |
| nomol spwulhuy (휘) | 'herb roots' | noun phrase | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | 1587 Sohak ŏnhae 6:133; genitive s + pwulhwuy 'root'; p. 133 |
| snahoy (-) / sonahoy (나) | 'man's' / later form | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Curious sn- cluster attestation, confirmed authentic by later attestation as sonahoy; p. 133-134 |
| ptut () / stut () | 'meaning, intent' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | 1632 reprint of Tusi ŏnhae repeatedly mistranscribes ptut as stut, showing pC-/sC- merger into reinforced consonant essentially complete; p. 134 |
| psketi- (디-) / sketi- (디-) / pketi- (디-) | 'collapse' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Variation across 1461 Nŭngŏm kyŏng, 1447 Yongbi ŏch'ŏn ka, and 1617 Tongguk sinsok samgang haengsil; p. 135-136 |
| pskwul () / skwul () | 'honey' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | 1527 Hunmong chahoe drops the p; p. 135 |
| pskum () / skum () | 'crack, interstice' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Same p-dropping pattern as pskwul/skwul; p. 135 |
| pskul () | 'chisel' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | 1527 Hunmong chahoe retains conservative pskul vs. attested skul (1459 Wŏrin sŏkpo); p. 135 |
| pswuk () / sswuk (쑥) | 'wormwood' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Pak T'ongsa (1677) doublet 1:35; p. 134-135 |
| ptu- () / stu- () | 'cauterize with moxa' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Pak T'ongsa (1677) doublet 1:35; p. 135 |
| ptenasye (나셔) / stenasye (나셔) | 'leave, depart' | verb form | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Ch'ŏphae sinŏ 1676 (5:3, 5:11); compound of ptu- 'float, leave' + na- 'go out'; p. 134-135 |
| pcwoch- (-) / scwoch- | 'drive out' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Waeŏ yuhae (early 18th c.) 1:29; pc- generally replaced by sc- by the 18th c.; p. 135 |
| pcak () / scak () | 'one of a pair' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Waeŏ yuhae 2:33; pc->sc- shift; p. 135 |
| ptelp- (-) / pthelWun () | 'astringent' | adjective | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | 1447 Sŏkpo sangjŏl 19:20; early cluster-to-aspirate development; modern Kyŏngsang reflex thelp-; p. 135 |
| ptel- (-) / pthelusya | 'shake' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | 1461 Nŭngŏm kyŏng ŏnhae 2:29; modern Kyŏngsang (Chinju) reflex thel-; p. 135 |
| ptut- (-) / pthutkwo | 'pluck out' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | 1459 Wŏrin sŏkpo 10:24; p. 135 |
| pto- / thʌ- (Cheju); ptwuy- / thwi- (Cheju); ptey / they- (Cheju) | 'pluck, pick' / 'run' / 'raft' | verb/noun | regional | — | contemporary dialect (source published 2011) | Cheju | regional | grammar_reference | n/a | n/a | Cheju regularly reflexes LMK pt-/pc- as /th/,/ch/; explicit regional dialect correspondence set; p. 135 |
| task- (닷-) | 'cultivate, train' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | tas.ka 닷가 (+infinitive -a) vs. tas.ti 닷디 (+ -ti, stem-final k drops); illustrates medial-cluster stem simplification; p. 135-136 |
| nem.psti- (넘-) ～ nems.ti- (디-) ～ nem.sti- (넘) | 'overflow' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Three spellings across 1461 Nŭngŏm kyŏng, 1459 Wŏrin sŏkpo, no phonemic difference; p. 136 |
| molk.ti (디) / polk.tela (더라) / wolm.kwo (옮고) / kolp.kenmalon (건마) | 'clear' / 'bright' / 'move' / 'line up' | verb/adjective | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | -lk/-lm/-lp stems before consonant-initial endings, producing unreduced three-consonant clusters; p. 136 |
| saWi (사) | 'shrimp' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Haerye example of voiced bilabial fricative W in V_V environment; modern Kyŏngsang reflex [sebi]; p. 136-137 |
| tuWuy (드) | 'rounded-out gourd' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Haerye example of W in V_V environment; p. 136 |
| chiWe (치) / South Hamgyŏng [chibə] | 'cold' | adjective | regional | — | contemporary dialect (source published 2011) | South Hamgyŏng | regional | grammar_reference | n/a | n/a | Peripheral dialect reflex [b] of LMK W; p. 137 |
| tayWem (대) / tayWat (대) | 'big tiger' / 'bamboo field' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | 1447 Yongbi ŏch'ŏn ka; W in y_V environment; p. 137 |
| kulWal (글) / malWam (말) | 'letter' / 'water chestnut' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | 1447/1459 attestations; W in l_V environment; p. 137 |
| wuzWu- (-) | 'funny' | adjective | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | W in z_V environment; p. 137 |
| phywoem/phwowem (표엄/표웜) | 'leopard, panther' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | 1527 Hunmong chahoe 1:9,18; compound of Sino-Korean phywo 'leopard' + pem 'tiger' showing V_V lenition of p>W; restored to phywopem in Early Modern Korean; p. 137 |
| koloWi () | 'drizzle, fine rain' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Compound of kolo 'fog, mist' + pi 'rain'; p. 137 |
| nwup-～nwuW- (눕-～-) / twop-～twoW- (돕-～-) | 'lie down' / 'help' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Irregular verb p～W stem alternation (p before C, W before V); contrasted with non-alternating cap- 'catch'; p. 137-138 |
| meyWas- (메-) | 'remove clothing from one shoulder (sign of respect)' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Compound of mey- 'carry on shoulder' + pas- 'take off (clothing)'; y_V lenition example; p. 138 |
| kalwem (갈웜) / twothwolwam (도톨왐) | 'spotted tiger' / 'acorn' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | l_V lenition compounds with pem 'tiger'/pam 'chestnut'; p. 138 |
| syelwep (셜웝) | 'Buddhist sermon' (Sino-Korean 說法) | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Early 16th-c. Pŏnyŏk Pak T'ongsa (1:75); p. 138 |
| toWoy- (-) / towoy- (외-) | 'become' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | 1447 Yongbi ŏch'ŏn ka retains W only in compounds (UYSIM_toWoy- 'doubt'); otherwise W already gone by 1447 Sŏkpo sangjŏl; p. 139 |
| kapoyyaWi (가야) / cwozoloWi (조) / swuWi (수) / elyeWi (어려) / sawonaWi (사오나) | 'lightly' / 'importantly' / 'easily' / 'with difficulty' / 'harshly' | adverb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | 1464 Amit'a kyŏng ŏnhae / 1467 Moguja susimgyŏl ŏnhae — last texts to regularly use the W letter; p. 139 |
| kulWal (글) > kulwal (글왈); teWe (더) > tewe (더워); sukoWol (스) > sukowol (스올); elyeWun (어려) > elyewun (어려운) | 'letter' / 'hot' / 'the country' / 'difficult' | noun/adjective | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Regular W>w lenition/merger pattern; p. 139 |
| swuWi (수) > swui (수이); kaskaWi (갓가) > kaskai (갓가이); teleWi- (더러-) > telei-/teley-; nwuWi- (누-) > nwui-; saWi (사) > sai (사이) | 'easily' / 'closely' / 'dirty' / 'lay down' / 'shrimp' | adverb/verb/noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | W elided (not merged to w) before /i/; p. 139 |
| chiWi (치) > chiwi (치위); teWi (더) > tewi (더위); -tiWi (-디) > -tiwi (-디위) | 'cold(ness)' / 'heat' / adverbial ending 'but, however' | noun/suffix | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Three counterexamples where Wi>wi rather than eliding; p. 139 |
| azo (아) / nezi (너) | 'younger brother' / 'bustard' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Haerye examples of voiced dental fricative z in V_V environment; p. 140 |
| mozol () / Andong [masɨl] | 'village' | noun | regional | — | contemporary dialect (source published 2011) | Andong | regional | grammar_reference | n/a | n/a | Dialect reflex /s/ of LMK z supports z<*s lenition; p. 139 |
| kozolh () / Pukch'ŏng [kasɨl] | 'autumn' | noun | regional | — | contemporary dialect (source published 2011) | Pukch'ŏng (South Hamgyŏng) | regional | grammar_reference | n/a | n/a | Same z<*s lenition evidence; p. 139 |
| sayzam (새) | 'dodder, love vine' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | y_V environment example; earlier Hyangyak kugŭppang transcription 鳥伊麻 shows *s origin; p. 140, 141 |
| twuze (두) ～ twuse (두서) | 'a couple of' | numeral/quantifier | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | < twul 'two' + se 'three'; *l_V reconstruction, coexisting s-doublet; p. 140 |
| phuzeli (프리) ～ phuseli (프서리) | 'land overgrown with weeds' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | phul 'grass' + seli 'space'; p. 140 |
| hanzwum (한) ～ hanswum (한숨) | 'sigh' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | n_V environment, han 'big' + swum 'breath'; p. 140 |
| hanzam (한) ～ hansam (한삼) | 'a creeper, vine' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | n_V environment doublet; p. 140 |
| swonzwo (손) ～ swoncwo (손조, later) | 'with (his) own hands, personally' | adverb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | n_V env.; later z>c change attested in c.1517 Pŏnyŏk Pak T'ongsa and 1587 Sohak ŏnhae; p. 140, 142 |
| mwomzwo (몸) ～ mwomcwo (몸조, later) | 'in person' | adverb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | m_V env.; z>c later attested in 1617 Tongguk sinsok samgang haengsil; p. 140, 142 |
| kozGay (애) | 'scissors' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | V_G environment linking z and G; Kyŏngsang reflexes kasegi/kaʃige/kasɨge preserve the velar; p. 140, 148 |
| zelzel () / zemzem () | '(appearance of flowing water)' / '(shimmering heat of sun)' | mimetic | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Rare word-initial z- in mimetic/special vocabulary; p. 141 |
| zywus () | 'the Four-Stick Game, yut' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Found only in first edition of 1527 Hunmong chahoe; modern dialect form swus; p. 141 |
| zywoh () | 'mattress, futon' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Chinese loanword for 'mattress'; reflex is modern yo; p. 141 |
| lwongtam (롱담, 弄談) | 'joke' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Sino-Korean/Chinese loan written with initial l- or z-; p. 141 |
| zin.skuy (人氣, ) | 'popularity' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Sino-Korean loan with initial z-; p. 141 |
| zichyen (쳔, 二千) | 'two thousand' | numeral | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Sino-Korean loan with initial z-; p. 141 |
| noyzil (來日) | 'tomorrow' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Cháoxiān-guăn yìyŭ (c. 1400) transcription 餒直ẁ confirms Sino-Korean z pronunciation of "rì (日) character mother"; p. 141-142 |
| nyezin (녀, 女人) | 'woman' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Transcribed 呆忍 in Cháoxiān-guăn yìyŭ; p. 142 |
| inso (인, 人事) | 'greeting' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | z dropped because -zin 'person' morpheme occurs here in word-initial position; p. 142 |
| sozi () > soi () | 'space, interval' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Earliest attestation of z-elision, found in 1481 Tusi ŏnhae; p. 142 |
| moyzyang (每樣) / moyyang (양) | 'every time' | adverb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Doublet in same Tusi ŏnhae text; p. 142 |
| zin () / zil () (1527) vs. noyil (일, lost z) | Sino-Korean readings of 人/日 ('person'/'day') | morpheme | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | 1527 Hunmong chahoe shows z in flux: retained in isolated readings, lost in compound noyil; p. 142 |
| zyang () / soyang (양, 辭讓) | 'yield' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | 1527 Hunmong chahoe 3:11,25; same z-flux pattern; p. 142 |
| yeu (여으) < yezo (여) | 'fox' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Shows z-elision spreading to general intervocalic position by the 1520s; p. 142 |
| aol (아) < azol (아) | 'taking away' | verb/gerund | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Same generalized z-elision evidence; p. 142 |
| mozom () | 'heart, mind' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Late, orthographically conservative use of ㅿ after z had already disappeared from speech; p. 142 |
| za () | emphatic particle | particle | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Same orthographic-conservatism category; p. 142 |
| namcin (남진) | 'man, male' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Possible early z>c example, from Sino-Korean *namzin (男人); p. 142-143 |
| samcil (삼질) | 'the third day of the third lunar month' | noun | contemporary | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | Modern word showing z>c, from Sino-Korean *samzil (三日); the change occurred after a nasal; p. 143 |
| puzep (브) > pwuekh | 'cooking stove' > 'kitchen' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Earliest attested form in Hunmin chŏngŭm; proposed compound pul 'fire' + *sep 'side'; hapax variant pus 'kitchen' (1587 Sohak ŏnhae 6:92) complicates the etymology; p. 141 footnote 10 |
| melGwuy (멀위) / Pukch'ŏng məlgi / Seoul melwu [məru] | 'wild grapes' | noun | regional | — | contemporary dialect (source published 2011) | Pukch'ŏng vs. Seoul | regional | grammar_reference | n/a | n/a | Illustrates [g] reflex of G in non-leniting peripheral dialect vs. Seoul loss; p. 144 |
| pelGey (벌에) / Pukch'ŏng pəlgəji / Seoul pelley [pəlle] | 'insect' | noun | regional | — | contemporary dialect (source published 2011) | Pukch'ŏng vs. Seoul | regional | grammar_reference | n/a | n/a | Same G/[g] dialect-reflex pattern; p. 144 |
| mwolGay (몰애) / Pukch'ŏng molge / Seoul molay [more] | 'sand' | noun | regional | — | contemporary dialect (source published 2011) | Pukch'ŏng vs. Seoul | regional | grammar_reference | n/a | n/a | Same G/[g] dialect-reflex pattern; p. 144, 147 |
| talGay- (달애-) / Pukch'ŏng talge- / Seoul tallay- [talle-] | 'placate' | verb | regional | — | contemporary dialect (source published 2011) | Pukch'ŏng vs. Seoul | regional | grammar_reference | n/a | n/a | Same G/[g] dialect-reflex pattern; p. 144, 147 |
| nwolGay (놀애) | 'song' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | l_V environment G example; later respelled nwollay (1676 Ch'ŏphae sinŏ), then nwolay (18th c.); p. 144, 147, 149 |
| elGuy- (얼의-) | 'curdle' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | l_V environment G example; p. 144 |
| kezGwuy (위) | 'worm' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | z_V environment G example; also attested pre-alphabetically (1250 Hyangyak kugŭppang 居乎/居兒乎); p. 144, 148-149 |
| wuzGi- (이-) | 'make laugh' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | z_V environment G example; p. 144 |
| poyGay (애) | 'Pear Inlet (place name)' | proper noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | i/y_V environment; compound with kay 'inlet'; p. 144, 147 |
| kolayGwol (래올) | 'Walnut Village (place name)' | proper noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | i/y_V environment; compound with kwol 'village'; p. 144, 147 |
| mul_Gwa (믈와) / mul_Gwos (믈옷) / atol_Gwom (아옴) / wuli_Gwos (우리옷) | 'with water' / 'precisely water' / 'each son' / 'precisely us' | noun phrase | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | k-initial particles kwa/kwos/kwom lenited to G after -l/-i/-y; contrasted with namwo_wa (no lenition after other vowels); p. 144-145 |
| alGwo (알오) / alGey (알에) / alGenul (알어늘) | 'knowing and...' / 'so as to know' / 'though knowing' | verb form | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | k-initial verb endings (-kwo, -key, -kenul) lenited to G after al- 'know'; p. 145 |
| yehuyGenul (여희어늘) | 'though bereaved of...' | verb form | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | k- lenition after -y; p. 145 |
| wuskey (웃게) | 'laughingly' | adverb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Counter-example: k- did NOT elide after z-; p. 145 |
| iGwo (이오) / iGenul (이어늘) | 'being...' / 'while it is...' | copula form | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Copula i- induces lenition, suggesting phonemic /iy/; p. 145 |
| :ti.Gwo (디오) | 'make drop, and...' | verb form | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Causative of ti- 'drop' (< .ti- 'fall'); second i-stem inducing lenition; p. 145 |
| swumki- (숨기-) / paski- (밧기-) | 'hide' / 'remove' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | -ki- allomorph of causative/passive postverb after nasal/s-; p. 145 |
| caphi- (자피-) / machi- (마치-) / mekhi- (머키-) / meki- (머기-) | 'get caught' / 'stop something' / 'be eaten' / 'feed' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | -hi- allomorph after p-/t-/c-/sometimes k-; p. 145 |
| nolGi- (이-) / wuzGi- (이-) | 'fly something' / 'make laugh' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | -Gi- allomorph after l-/z-/y-; p. 145 |
| tahi- (다히-) | 'touch something' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | -i- allomorph after h- or sometimes k-; p. 145 |
| syey- (셰-) | 'stand something up' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | -y- allomorph after a vowel; p. 145 |
| nolGi- / Pukch'ŏng nalgi / Seoul nalli- | 'fly (something)' | verb | regional | — | contemporary dialect (source published 2011) | Pukch'ŏng vs. Seoul | regional | grammar_reference | n/a | n/a | Dialect reflex set confirming lenition of /ki/ to -Gi- after l-; p. 145-146 |
| mulGi- / Pukch'ŏng mulgi / Seoul mulli- | 'be bitten' | verb | regional | — | contemporary dialect (source published 2011) | Pukch'ŏng vs. Seoul | regional | grammar_reference | n/a | n/a | Same dialect-reflex set; p. 145-146 |
| skolGi- / Pukch'ŏng kʔalgi- / Seoul kkalli- | 'be spread' | verb | regional | — | contemporary dialect (source published 2011) | Pukch'ŏng vs. Seoul | regional | grammar_reference | n/a | n/a | Same dialect-reflex set; p. 145-146 |
| kwoyOOye (괴) / moyOOi.nonila (니라) / mwuyOOwue (뮈) | 'being loved' / 'is bound to' / 'moving' | verb form | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | The unique double-zero symbol ㆀ, used only to transcribe the causative/passive morpheme's /G/ after a y-final stem; last form from 1459 Wŏrin sŏkpo 14:14; p. 146 |
| alGwoy- (알외-) | 'inform' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | < al- 'know' + causative -Gwoy-; confirmed by Cháoxiān-guăn yìyŭ phonogram 貴 transcription; p. 146, 149 |
| meyGwu- (메우-) | 'cause to shoulder' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | < mey- 'shoulder' + causative -Gwu(y)-; modern Seoul non-standard reflex meykkwu-; p. 146 |
| cipkey / cikey / peykay / ciwukey / sswusikay | 'tweezers' / 'A-frame' / 'pillow' / 'eraser' / 'a pick' | noun | contemporary | — | contemporary (source published 2011) | — | — | grammar_reference | n/a | n/a | Modern -key/kay nominalizing-suffix words, offered as the living reflex of the suffix reconstructed in kozGay 'scissors'; p. 146 |
| kozGay (애) | 'scissors' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Nominalization of koz- 'cut' + instrument suffix -kay, lenited after z-; attested pre-alphabetically as 割子蓋 in 12th-c. Jı̄lı́n lèishì; p. 146, 148-149 |
| tolGay (애) | 'mudguards (on a horse)' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | < tol- 'hang' + -kay, lenited after l-; also attested in Cháoxiān-guăn yìyŭ as 得盖; p. 146, 149 |
| kolGamakwoy (아마괴) / kalGwoy (갈외) | 'jackdaw' / 'blister-beetle' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Compound nouns with lenited /k/>G; < kamakwoy 'crow' / kwoy 'cat'; p. 146 |
| nolo / nwolo (노) / colo () / cyalo (쟈) / silu (시르) | 'ferry' / 'deer' / 'handle' / 'sack' / 'steamer' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Nouns reconstructed with final *k (*nolok etc.) showing G before vowel-initial particles: nol.G_i, nwol.G_uy, col.G_i, cyal.G_oy, sil.G_ul; Pukch'ŏng reflex [nolgɨ] 'deer+obj.'; p. 147 |
| azo (아) / yezu (여) / mwuzwu (무) | 'younger brother' / 'fox' / 'radish' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Reconstructed *azok/*yezuk/*mwuzuk; before vowel-initial particles az.G_i, yez.G_un, mwuz.G_ila; Hamhŭng [akʔi], Pukch'ŏng [yeeŋkʔi]/[mukʔ-]; p. 147 |
| namwo (나모) / kwumwu (구무) / pwulmwu (불무) / nyenu (녀느) | 'tree' / 'hole' / 'bellows' / 'other (person)' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Medial-nasal nouns with unlenited velar before vowel particles (nam.k_on, kwum.k_ul, etc.); modern standard lost the velar entirely (namu, kwumeng); reconstructed *namok/*kwumuk/*pwulmuk/*nyenuk; p. 147 |
| pozo- (-) / kuzu- (그-) / pizu- (비-) | 'break, shatter' / 'drag' / 'dress up' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Medial-z verb stems with G appearing before a vowel after stem-vowel elision: poz.Ga, kuz.Ge, piz.Ge; p. 147 |
| wolo- (오-) / talo- (다-) | 'go up' / 'be different' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | "l-extending" verb class showing lenited velar before vowel-initial endings: wolGa 올아, talGa 달아; South Chŏlla dialect shows labial reflex [talbu-] instead; merged with "l-doubling" verbs in 16th c.; p. 147, 149 |
| kulWal (글) / kulGwal (글왈) | 'letter' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Same word transcribed with W in 1446 Yongbi ŏch'ŏn ka but with G one year later (1447 Sŏkpo sangjŏl, 1459 Wŏrin sŏkpo); p. 148 |
| syelWul (셜) / syelGwul (셜울) | 'sad' | adjective | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Wŏrin sŏkpo (W) vs. Hunmong chahoe (G) transcriptions of the same prospective verbal form; p. 148 |
| solWoni (니) / solGwoni (오니) | 'say respectfully' | verb form | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Same W/G orthographic variation pattern; p. 148 |
| swolGwos (솔옷) > swongkwos | 'awl' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Pre-alphabetic transcriptions 所乙串 (1431) and 所乙古叱 (1541) both read [solgos]; compound of swol- 'narrow' + kwoc 'skewer'; p. 149 |
| wolGa (올아) / wolla (올라, later) | 'goes up' | verb form | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Later (1587 Sohak ŏnhae) orthographic replacement of G-spelling by double-l; standard by 17th c.; p. 149 |
| talGa (달아) / tallwom (달롬, later) | 'is different' / 'being different' | verb form | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Same double-l orthographic replacement pattern; p. 149 |
| nwolGay (놀애) / nwollay (놀래, 1676) / nwolay (노래, 18th c.) | 'song' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Three-stage orthographic evolution G-spelling > double-l > single-l; p. 149 |
| nol.G_i (놀이) / nwol_li (놀리, 1617) | 'deer (+ subject particle)' | noun form | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Same double-l replacement pattern, attested 1617 Tongguk sinsok samgang haengsil; p. 149 |
| etcoWonywo (얻뇨) | deferential verb form | verb form | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | 1447 Sŏkpo sangjŏl 13:16; t+s transcribed as tc, evidence that /c/ was apical [ts] not palatal; p. 149 |
| cang (장) / cyang (쟝) | 'cupboard' / 'soy sauce' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Minimal pair illustrating c/cy contrast before non-front vs. front vowel; p. 149-150 |
| ce (저) / cye (져) | 'oneself' / 'chopsticks' | pronoun/noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Minimal pair, c/cy contrast; p. 150 |
| chwo (초) / chywo (쵸) | 'vinegar' / 'candle' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Minimal pair, ch/chy contrast; p. 150 |
| sem (섬) / syem (셤) | 'stone stairstep' / 'island' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Minimal pair illustrating s/sy contrast, s occurring freely before y in LMK; p. 150 |
| swoh (솧) / sywo (쇼) | 'swamp' / 'ox' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Minimal pair, s/sy contrast; p. 150 |
| tasi (다시) / azi (아) | 'again' / 'first' | adverb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Illustrates s/z as contrasting phonemes, not purely allophonic lenition; p. 150 |
| ni (니) / nima (니마) / niph (닢) / nyelum (녀름) | 'tooth' / 'forehead' / 'leaf' / 'summer' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | n freely occurring before i/y in LMK, unlike modern central dialects where it was later lost; p. 150 |
| syongaci (아지) | 'calf' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | sywo 'ox' + diminutive -ngaci; rare morpheme-initial ng; p. 150 |
| sange (어) | 'shark' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Sino-Korean sa (鯊) + -nge (魚); rare morpheme-initial ng; p. 150 |
| an- (안-) / sin- (신-) | 'embrace' / 'put on (shoes)' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Rare n-final verb stems, related to nouns anh 'inside' and sin 'shoes'; p. 151 |
| ten- (던-) | 'bet, gamble' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Very marginal n-final stem; 1527 Hunmong chahoe 3:8; p. 151 |
| kochwo-～konchwo-～komchwo- (초-～초-～초) | 'hide' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Nasal-epenthesis-before-affricate case; later/Seoul reflex kamchwu-; p. 151-152 |
| kachi (가치) / kkachi (later) | 'magpie' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Nasal-epenthesis case (Pukch'ŏng kanchi preserves an -n- stage); p. 151-152 |
| kwothi-/kwochi- (고티-/고치-) | 'repair' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Original dental-stop stem, so the nasal (konchi-) must be epenthetic, post-affrication; key evidence for the nasal-epenthesis analysis; p. 151-152 |
| nechwul (너출) / nenchwul (넌출, later) | 'vine' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Nasal-epenthesis case; p. 151-152 |
| teti- (더디-) / teci- (더지-, later) | 'throw' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Original dental stop, confirming epenthetic nasal in post-affrication forms; p. 151-152 |
| machi (마치) | 'hammer' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Nasal-epenthesis case (tencimangchi); p. 151-152 |
| mechwu- (머추-) | 'stop (something)' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | < mec- 'stop' + causative -hwu-, no nasal in either source morpheme; key evidence for epenthesis; p. 151-152 |
| ac-～as-～az-～ac- (앉-～앗-～-～앚-) / ancok (안) | 'sit' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Un-nasalized ac- shown older via Cháoxiān-guăn yìyŭ 阿格刺 and 12th-c. Jı̄lı́n lèishì 阿則家囉 (no nasal trace); Cheju reflex ac-; standard mimetic acang-acang preserves unnasalized form; p. 152 |
| yenc-～yec- (엱-～옂-) | 'place' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Un-nasalized yec- older, per same phonogram evidence; Cheju reflex yoc- [yʌʥ-]; p. 152 |
| cachi- (자치-) | 'cause to subside' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | < cac- 'subside' + causative -hi-, no nasal in source morphemes; p. 152 |
| panchywo (반쵸) | 'plantain' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | 1527 Hunmong chahoe, identified with Chinese 芭蕉; neither Mandarin bājiāo nor the Sino-Korean reading contains a nasal — the most conclusive single piece of evidence for epenthesis; p. 152 |
| noyzil / nozil (, ) | 'tomorrow' (來日) | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Initial l- had already changed to n- by the 15th c. in this Sinitic loan, cf. Mandarin láirì; p. 152-153 |
| Ni Sywoza (니쇼, personal name) / nwomwo (노모, 老母) / nyeycel (녜절, 禮節) | '(name)' / 'old mother' / 'etiquette' | proper noun/noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | 16th-c. examples of l->n in Sino-Korean initial position; p. 153 |
| mwolan [moran] (모란, 牧丹) | 'peony' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Lenition of dental stop to [r]; borrowed after northern Chinese had already lost the -k of mwoktan; p. 153 |
| cholyey (례) < chotyey (뎨, 次第) | 'order' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Sino-Korean dental>[r] lenition; p. 153 |
| twolyang (도량) < twotyang (도댱, 道場) | 'Buddhist seminary' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Sino-Korean dental>[r] lenition; p. 153 |
| pwoli (보리) < pwotyey (보뎨, 菩提) | 'Bodhi' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Sino-Korean dental>[r] lenition; p. 153 |
| patah～palol (바닿～바) | 'sea' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Native doublet with [t]/[r] alternation; p. 153 |
| petu-namwo (버드나모) < petul (버들) + namwo (나모) | 'willow tree' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | l-dropping before coronal consonant in compound; p. 153 |
| to-nim (님) < tol () + nim (님) | 'the respected moon' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | 1459 Wŏrin sŏkpo 2:51b; l-dropping compound; p. 153 |
| swucye (수져) < swul (술) + cye (져) | 'spoon and chopsticks' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | 1459 Wŏrin sŏkpo 23:74; l-dropping compound; p. 153 |
| atol-nim (아님) / ato-nim (아님) | 'respected son' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Doublet showing optional l-dropping in compounds; p. 153 |
| hwal-sal (활살) / hwa-sal (화살) | 'bow and arrow, arrow' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Doublet, 1459 Wŏrin sŏkpo vs. 1588 Sohak ŏnhae; p. 153 |
| nac (낫, 낮) | 'daytime' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Written/pronounced nas in isolation; affricate-final neutralization with -s; p. 153 |
| noch (, 녇) | 'face' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Written/pronounced nos in isolation; p. 153 |
| tol () / 得二 | 'moon' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Cháoxiān-guăn yìyŭ transcribes final -l with the Chinese character 二; p. 154 |
| pyel (별) / 別二 | 'star' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Same -l transcription convention; p. 154 |
| kwos (곳, 花/kwoc 곶) / 果思 | 'flower' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | -s coda represented with Chinese character 思 in Cháoxiān-guăn yìyŭ; p. 154 |
| cas (잣, 松子) | 'walled city' / 'pine nuts' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Homophonous -s coda forms; p. 154 |
| nos (, noch , 面) | 'face' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | -s coda, confirms -s vs -t distinction in final position; p. 154 |
| wos (옷, 衣服) / kyep.wos (겹옷, 夾衣) | 'clothing' / 'lined clothes' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | -s coda examples; p. 154 |
| pat (받, 田) / path (밭) | 'rice paddy' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | -t coda went unrepresented in Chinese phonograms (把), contrasting with -s coda's 思; p. 154 |
| pyet (볃, 陽) / pyeth (볕) | 'sunshine' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | -t coda example (character 別); p. 154 |
| pwut (붇, 筆) | 'writing brush' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | -t coda example (character 卜); p. 154 |
| twot (돋, 猪) / 돝 | 'swine' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | -t coda example (character 朶); p. 154 |
| pit.ssota (빋다, 貴) / pit.tita (빋디다) | 'expensive' / 'cheap' | adjective | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | -t coda examples (characters 必色大/必底大); p. 154 |
| kozGay (애) / kezGwuy (위) / wuzWu- (-) | 'scissors' / 'worm' / 'funny' | noun/adjective | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Repeated as the sole evidence for a ninth terminal consonant, z, realized only before another voiced fricative (G or W); p. 154 |
| isnoni (잇니) / innoni (인니, later) | 'is and...' | verb form | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Early 16th c. shows -s>-t neutralization plus regressive nasal assimilation; p. 154-155 |
| ithusnal (이틋날) / ithunnal (이튼날, later) | 'the second day' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Same -s>-t>-n assimilation pattern; p. 155 |
| muysmuys_hota (믯믯다) / muynmuys_hota (믠믯다, later) | 'slippery' | adjective | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Same assimilation pattern; p. 155 |
| nasnachi (낫나치) / nannachi (난나치, later) | 'one by one' | adverb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Same assimilation pattern; p. 155 |
| naks (낛) / neks (넋) | 'hook' / 'spirit' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Rare -ks terminal cluster; unclear if the s was pronounced before a juncture; p. 155 |
| nwoh- (놓-) | 'put, place' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | h-morphophonemics: nwokhwo (놓+-kwo), nwossopkwo, nwotnwoni, showing h>aspirate, h+s>ss, h+n>t rules; p. 155 |
| tyeh (뎧) / tye khwa (뎌콰) | 'flute' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | 1463 Pŏphwa kyŏng ŏnhae 1:221; morphophonemic -h surfaces as aspirate before kwa; dropped in isolation (tye); p. 155 |
| wuz- (-) / wuskwo (웃고) | 'laugh' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | z devoices to s before k (morphophonemic rule 2); p. 155 |
| twoW- (-) / twopkwo (돕고) | 'help' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | W devoices to p before k; p. 155 |
| ketne-/kenne- (걷너-/건너-) | 'cross over' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | t assimilates nasality of following n (rule 3); p. 155 |
| totni-/tonni- (니-/니-) | 'go about' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Same t-nasal-assimilation rule; p. 155 |
| alGwo (알오) / towoyGwo (되오) | 'knowing' / 'becoming' | verb form | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | k->G lenition rule after -l/-y (rule 4); p. 155 |
| ila (이라) / ilwo- (이로-) / ile- (이러-) | copula + indicative/-two-/retrospective | copula form | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | t->l lenition of copula-attached morphemes (rule 5); p. 155-156 |
| cywupyen-towoy- (쥬변외-) / woy-lowoy- (외외-) | 'being free' / 'lonely' | adjective | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Postnominal -toWoy/toW- realized as -loWoy/loW- after l-/y-/vowel (rule 5 continued); p. 156 |
| ㅣi [i] / ㅡu [ɨ] / ㅓe [ə] / ㅏa [a] / ㅜwu [u] / ㅗwo [o] / ㆍo [ʌ] | the seven LMK vowel phonemes | phoneme | core | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Full seven-vowel inventory; ㆍ (o/[ʌ]) is the vowel lost from standard Seoul but preserved in Cheju; p. 156 |
| toy () / tuy (듸) | 'place where...' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | 1459 Wŏrin sŏkpo sporadic early example of o>u merger in non-initial syllable; p. 159 |
| nakonay (나내) / nakunay (나그내) | 'stranger, guest' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | 1481 Tusi ŏnhae, consistent o>u merger; p. 159 |
| kiloma (기마) / kiluma (기르마) | 'packsaddle' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Same o>u merger, Tusi ŏnhae 20:44, 22:8; p. 159 |
| kutoy (그) / kutuy (그듸) | 'thou' | pronoun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | o>u merger, attested more often as kutuy by 1481; p. 159 |
| kakoki (가기) / kakuki (가그기) | 'suddenly, hurriedly' | adverb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | 1489 Kugŭp kani pang doublet; p. 159 |
| mwotun (모든, < mwoton 모) | 'all' | adjective | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | c. 1517 Pŏnyŏk Pak T'ongsa 1:24; o>u merger becomes frequent at start of 16th c.; p. 159 |
| twocuk (도즉, < twocok 도) | 'thief' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Pŏnyŏk Pak T'ongsa 1:35; p. 159 |
| nyenamun (녀나믄, < nyenamon 녀나) | 'other' | adjective | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Pŏnyŏk Pak T'ongsa 1:34; p. 159-160 |
| tamun (다믄, < tamon 다) | 'only, just' | adverb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Pŏnyŏk Pak T'ongsa 1:63; p. 160 |
| kaphul (가플, < kaphol 가) | 'scabbard' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | 1527 Hunmong chahoe; p. 160 |
| mazul (마, < mazol 마) | 'government office' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | 1527 Hunmong chahoe; p. 160 |
| kolochi-/koluchi- (치-/르치-) | 'teach' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | 1587 Sohak ŏnhae shows o>u merger complete by this point; p. 160 |
| mozol/moul (/을) | 'village' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Sohak ŏnhae; p. 160 |
| homolmye/homulmye (며/믈며) | 'much more' | adverb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Sohak ŏnhae; completes 1st stage of /o/ loss in non-initial syllables by latter 16th c.; p. 160 |
| holk () / hulk (흙) | 'earth' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Rare exception: initial-syllable /o/ changed early (1587 Sohak ŏnhae), unlike the general 18th-c. initial-syllable merger; p. 160 |
| somay (매) / swomay (소매, 17th c.) | 'sleeve' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | 1617 Tongguk sinsok samgang haengsil; second early exception to initial-syllable /o/ stability; p. 160 |
| kowol () / kwoul (고을) | 'county' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | 1527 Hunmong chahoe; regressive rounding assimilation, related but distinct change; p. 160 footnote 14 |
| howol () / hwoul (호을) | 'single' | adjective | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Hunmong chahoe 3:14, 33; p. 160 footnote 14 |
| kowoy () / kwouy (고의) | 'lower garment, trousers' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Hunmong chahoe 2:4, 8; p. 160 footnote 14 |
| yele (여러) / yela (여라) (< *yola) | 'several' | adjective | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Vowel-harmony-violating doublet used to internally reconstruct the sound change *yo>ye; Cheju reflex [yʌra]; p. 161-162 |
| yetulp (여듧) / yetolay (여래) (< *yotolp) | 'eight' / 'eight days' | numeral | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Reconstructs *yotolp; modern Kyŏngsang/Chŏlla reflexes [yadal]/[yadap] preserve the a-vocalism; Cheju [yʌdʌp]; p. 161-162 |
| yotolp () | 'eight' (dialect form) | numeral | regional | — | contemporary dialect (source published 2011; cited 1750) | Cheju-adjacent/unspecified "dialect" | regional | grammar_reference | n/a | n/a | Cited in 1750 Hunmin chŏngŭm unhae by Sin Kyŏngjun with unique diphthong symbol ᆢ; explicit source-marked dialect form; p. 161 |
| atol (아) / atul (아들, anomalous) | 'son' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Canonical yang-vowel-harmony word; modern atul form flagged as the kind of combination vowel harmony would have disallowed in LMK; p. 162 |
| petul (버들) | 'willow' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Canonical yin-vowel-harmony word; p. 162 |
| api (아비) / emi (어미) | 'father' / 'mother' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Neutral vowel i co-occurring with yang (api) and yin (emi) vowels respectively; p. 162 |
| salo.m_ol (사) / yelu.m_ul (여르믈) | 'person (object)' / 'summer (object)' | noun+particle | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Accusative particle -ol/-ul alternating by vowel harmony; p. 162 |
| palo.l_ay (바래) / nyelu.m_ey (녀르메) | 'in the sea' / 'in the summer' | noun+particle | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Locative particle -ay/-ey alternating by vowel harmony; p. 162 |
| kaph- (repay) / et- (receive) | 'repay' / 'receive' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Paradigm pair illustrating yang/yin verb-ending alternation across -a/e, -oni/uni, -omyen/umyen; p. 162 |
| kes_man (것만) | 'only (the thing) that...' | particle phrase | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | man is a consonant-initial particle that blocks vowel harmony, attaching unchanged to yin-vowel stems; p. 163 |
| kuchikwo (그치고) / cwukwo (주고) / pwokwo (보고) | 'stopping' / 'giving' / 'seeing' | verb form | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | -kwo gerund ending is invariant regardless of stem vowel harmony class; p. 163 |
| son (손) 'guest' / SON (ㆍ손) 'hand' | 'guest' / 'hand' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Minimal pair distinguished solely by even vs. departing tone marking; p. 163 |
| PAL (ㆍ발) 'foot' / paAL (:발) 'bamboo blind' | 'foot' / 'bamboo blind' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Minimal pair, departing vs. rising tone; p. 163 |
| pi (비) 'stele' / PI (ㆍ비) 'rain' | 'stele' / 'rain' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Minimal pair, even vs. departing tone; p. 163 |
| SOL (ㆍ솔) 'pine' / soOL (:솔) 'brush' | 'pine' / 'brush' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Minimal pair, departing vs. rising tone; p. 163 |
| kaci (가지) 'eggplant' / kaCI (가ㆍ지) 'type' / KACI (ㆍ가지) 'branch' | 'eggplant' / 'type' / 'branch' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Three-way minimal set distinguished by tone pattern across two syllables; p. 163 |
| seLI (서ㆍ리) 'frost' / SELI (ㆍ서리) 'midst' | 'frost' / 'midst' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Two-syllable tone minimal pair; p. 163 |
| kàhí (가.히) > kǎy (:개) | 'dog' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Two-syllable low-high contracting to one-syllable rising tone after h drops, by latter 16th c.; p. 163-164 |
| Kwòmá Nòlò (고.마) | 'Bear Crossing' (place name) | proper noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | 1447 Yongbi ŏch'ŏn ka place name attesting two-syllable origin of kwǒm 'bear'; p. 164 |
| *nàlí > nǎy (:내) | 'stream' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Reconstructed low-high contraction to rising tone, via earlier phonogram transcriptions; p. 164 |
| nwùlí～nwǔy (누.리～:뉘) | 'world' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Doublet showing same contraction pattern; p. 164 |
| twùúl～twǔl (두.을～:둘, < *twuWul) | 'two' | numeral | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Doublet linking tone contraction to the earlier W-loss change; p. 164 |
| màktàhí～màktǎy (막다.히～막:대) | 'staff, stick' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Doublet showing tone contraction; later contrasted with cúkcàhí (which does NOT contract to rising tone); p. 164, 168 |
| cwùúli～cwǔli- (주.우리-～:주리-) | 'go hungry' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Doublet showing tone contraction; p. 164 |
| kù+í > kǔy (:긔) | 'that one (+nom.)' | pronoun+particle | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Nominative particle í incorporated into low syllable, producing rising tone; p. 164 |
| pwùthyé+í > pwùthyěy (부:톄) | 'Buddha (+nom.)' | noun+particle | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Same nominative-incorporation rising-tone rule; p. 164 |
| tòlì+í > tòlǐ (:리) | 'bridge (+nom.)' | noun+particle | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Same rule; also shown with copula below; p. 164-165 |
| tòlì+ílá > tòlǐ'lá (:리.라) | 'it is a bridge' | noun+copula | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Same morphological-contraction rule with the copula; p. 165 |
| nwùùy+ílá > nwùǔy'lá (누:의.라) | 'it is a (boy's) sister' | noun+copula | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Same rule; p. 165 |
| nà- + -í- > nǎy- (:내-) | 'give birth to' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Causative postverb -í- incorporated into low stem-final syllable, producing rising tone; < nà- 'be born'; p. 165 |
| tì- + -í- > tǐ- (:디-) | 'drop' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Same causative-incorporation rule; < tì- 'fall'; p. 165 |
| pwò- + -í- > pwǒy- (:뵈-) | 'show' | verb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Same rule; < pwò- 'see'; p. 165 |
| pwò- + -wó- > pwǒm (:봄) | (volitive form of 'see') | verb form | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | 1459 Wŏrin sŏkpo 1:25; volitive morpheme -wó/wú- also causing rising-tone change; p. 165 |
| kà- + -wó- > kǎlq (:) | (volitive prospective form of 'go') | verb form | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | 1447 Yongbi ŏch'ŏn ka 19; p. 165 |
| pay/páy (pear/belly) | 'pear' / 'belly' | noun | regional | — | contemporary dialect (source published 2011) | Hamgyŏng | regional | grammar_reference | n/a | n/a | Homonyms in isolation in Hamgyŏng but distinguished by accent when followed by a particle: [pe Ga] vs. Pe ga; direct modern reflex of the LMK tone minimal pair pòy/póy; p. 165-166 |
| melí (head) / pwoli (barley) | 'head' / 'barley' | noun | regional | — | contemporary dialect (source published 2011) | Hamgyŏng | regional | grammar_reference | n/a | n/a | Phonetically identical low-high rise but morphophonemically distinct (accented vs. unaccented); p. 166 |
| mwoki (mosquito) | 'mosquito' | noun | regional | — | contemporary dialect (source published 2011) | Hamgyŏng | regional | grammar_reference | n/a | n/a | Reflex of LMK mwókóy; p. 166 |
| kkwóch_i (flower) / kkwoch-kaps_i (price of flowers) | 'flower(+nom.)' / 'the price of flowers' | noun+particle | regional | — | contemporary dialect (source published 2011) | Hamgyŏng vs. Kyŏngsang | regional | grammar_reference | n/a | n/a | Cross-dialect correspondence table showing the Kyŏngsang accent locus one syllable left of the Hamgyŏng locus; p. 166-167 |
| PHWOLI (fly, high-high) / MWUCIkay (rainbow, high-high-low) | 'fly' / 'rainbow' | noun | regional | — | contemporary dialect (source published 2011) | Kyŏngsang (Kimhae) | regional | grammar_reference | n/a | n/a | Illustrates the "no prominent syllable" Kyŏngsang tonal pattern, an innovation not found in Hamgyŏng; p. 166 |
| mwókóy/mwókòy (모./모) | 'mosquito' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Tone on second syllable varies between 1447 Sŏkpo sangjŏl (9:9b) and 1461 Nŭngŏm kyŏng ŏnhae (4:3b) — evidence post-first-high-tone pitches weren't distinctive; p. 167-168 |
| àcómí (아..미) / àcómì (아.미) | 'aunt' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Low-high-low vs. low-high-high variation, 1527 Hunmong chahoe vs. 1447 Yongbi ŏch'ŏn ka; p. 168 |
| twóskàpí/twóskápì (.돗가./.돗.가비) | 'spirit, devil' | noun | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | Further example of post-first-high-tone variation in prototonic patterns; p. 168 |
| cúkcàhí (.즉자.히) / cúkcày (.즉재) / cúkcáy (.즉.재) | 'immediately' | adverb | archaic | — | Late Middle Korean (15th-16th c.) | — | — | grammar_reference | n/a | n/a | 1459/1463/1461 attestations; the second high tone here was NOT distinctive, so contraction did not yield a rising tone (contrast with màktǎy); p. 168 |

### Grammar points

#### Historical orthographic background: Tongguk chŏngun vs. "Eastern Sounds"

The chapter opens (p. 127) by noting that the artificial, prescriptive Sino-Korean readings codified in
the 1447 *Tongguk chŏngun* (a theoretical compromise between Chinese rime-table categories and actual
Korean Sino-Korean pronunciation) could not be sustained past the 1480s. Real Korean readings of
Chinese characters — called "Eastern Sounds" (東音) — gradually replaced the prescriptive orthography,
becoming general by the reign of Prince Yŏnsan (late 15th c.) and universal in Korean-language
publications by the 16th century. The 1527 *Hunmong chahoe* is identified as the chapter's key source
for genuine Sino-Korean pronunciations of this later period.

#### Consonant system overview

Late Middle Korean's consonant inventory (p. 128) comprised: plain stops/affricate p, t, k, c;
aspirated ph, th, kh, ch; reinforced [pp, tt, kk, (cc)], ss, hh; voiced fricatives W (ᄫ), z (ㅿ), G (ㆁ,
graphically ○); nasals m, n, ng; and liquid l. The authors stress this reconstruction is built primarily
from the Hunmin chŏngŭm system, supplemented by philological evidence from 15th-16th-century texts and
constrained by later/modern dialect evidence (p. 128).

#### Aspiration

A primary plain/aspirated distinction existed (/p,t,k,c/ vs. /ph,th,kh,ch/), but aspirates were far
rarer than plain consonants in word-initial position, especially kh and ph (p. 128). Over time, more
words shifted to aspirated initials (e.g., polh>phol 'arm,' kwoh>khwo 'nose,' kalh>khal 'knife'). In
medial position, the glottal fricative h regularly combined with a following plain consonant — often via
metathesis — to yield an aspirate, a pattern still productive in the modern language; contracted forms
of ho- 'do' are the clearest illustration (pp. 128-129).

#### Reinforcement

Modern geminate-spelled tense consonants (ㄲ,ㄸ,ㅃ,ㅉ,ㅆ) existed phonetically in LMK but were not yet a
distinct phonemic series; the Hunmin chŏngŭm provided no native-word symbols for them except ss and hh
(p. 129). Reinforcement was a productive medial process, commonly triggered by the "genitive s" linking
particle, which could surface as a homorganic stop or glottal stop and induce tensing of a following
consonant (s+k→skk, etc.; pp. 129-130). The reinforced cc never occurred initially, found only
word-medially in morphemically complex forms; hh existed only in the single verb stem hhye- 'pull' and
its compounds, later replaced by plain h (p. 130). The curious double-zero symbol ㆀ marked the
passive/causative morpheme's velar after a stem ending in -Vy, since a single zero circle there would
have been read as no consonant at all (p. 130).

#### Initial consonant clusters (sC-, pC-, psC-)

Three types of initial clusters occurred in LMK: sC- (sp-, st-, sk-), pC- (pt-, pth-, ps-, pc-), and
psC- (pst-, psk-) — nine clusters total (pp. 130-131). These are believed to have arisen in Early Middle
Korean (after the 12th c.) through syncope of a medial vowel; the authors trace this concretely via
12th-13th-century Chinese-transcription evidence for psol 'rice' and wotwoktwoki 'arbor monkshood' (pp.
131-132). Most pst-/psk- words belong to a semantic family of "breaking/cracking/piercing" verbs built
on a preverb pozo-/poso- 'break, shatter' (p. 132). These initial clusters became today's reinforced
consonants, with the labial of pC-/psC- clusters leaving a residual /p/ trace in a handful of modern
compounds (cwop-ssal, chap-ssal, hayp-ssal, pyep-ssi, hamkkey; p. 132) and a residual sibilance trace in
others (ip-ccak, ipttay, cepttay — the source explicitly marks ip-ccak as Kangwŏn/Kyŏnggi regional
usage; p. 132). Separately, reinforcement sometimes arose from an *emphatic/expressive* use of sC-
spelling rather than from any etymological cluster at all — an intensifying device still productive
today (footnote 9, p. 133: ccokkum vs. cokum, kkam- vs. kam-, etc.). The historical merger of sC-
clusters into plain reinforced consonants is dated to the 16th century based on textual confusion of sC-
and pC- spellings beginning in the 1632 Tusi ŏnhae reprint (pp. 134-135); reduction of pt-/ps- is placed
around the mid-17th century (p. 135). A handful of clusters instead developed into aspirates rather than
reinforced consonants (pt->th-, etc.), confirmed by their persistence as aspirates in Kyŏngsang and
especially Cheju dialects, where /th/, /ch/ are the regular reflexes of Middle Korean pt-, pc- (p. 135).

#### Medial consonant clusters

Two-consonant clusters were common word-medially; three-consonant clusters occurred when the first
member was /l/ or a nasal preceded an sC cluster (p. 136). A verb stem ending in two consonants dropped
its final consonant before a consonant-initial ending but kept both before a vowel-initial one (e.g.
task- 'cultivate': tas.ka vs. tas.ti). Stems ending in -lk, -lm, -lp retained all three consonants of the
resulting cluster unreduced before a consonant-initial ending (p. 136).

#### The voiced fricatives W, z, G and their loss

LMK had a short-lived series of three voiced fricatives — W (ᄫ, voiced bilabial [b]), z (ㅿ, voiced
dental [z]), and G (represented by the ambiguous "zero" symbol ○, a voiced velar spirant [ɣ]/[ɦ]) — each
restricted to specific voiced environments and each disappearing from the central dialects within a
century or two of the alphabet's invention (pp. 136-149).

**W** alternated morphophonemically with /p/ and occurred in V_V, y_V, l_V, and z_V environments but
never word-initially. Some instances demonstrably lenited from an earlier *p within compounds (e.g.
phywoem < phywo+pem 'leopard'); others (the p~W alternation in irregular verbs like nwup-~nwuW- 'lie
down') resist a clean lenition analysis because parallel non-alternating stems like cap- 'catch' exist
(pp. 137-138). W disappeared almost exactly as the alphabet was invented (c. 1450); by Sejo's accession
(1455) it was nearly gone from texts, usually merging with semivowel /w/, though before /i/ it typically
elided outright rather than weakening (pp. 138-139). Peripheral dialects (Kyŏngsang, South Hamgyŏng)
preserve a /p/ (realized [b] in voiced position) as the reflex, evidence the change originated centrally
(p. 137).

**z** alternated morphophonemically with /s/; its oldest attestations go back to the 12th-century Jī·lín
lèishì. In Sino-Korean, z was a common correspondence of the Chinese "rì (日) character mother" — but
only in non-initial morpheme position; in initial position it dropped (p. 142). Lenition of earlier *s
to z (in voiced environments after y/l/n/m and before a vowel) is independently confirmed by
13th-century Hyangyak kugŭppang transcriptions and by compound etymologies (twuze < *twulse < twul+se;
pp. 141-142). z itself was lost almost entirely without a trace (z > ∅) between the 1470s and
mid-16th-century, with the 1527 Hunmong chahoe catching the change mid-flight (pp. 142-143); modern
dialects in the far north/south where lenition never occurred still show /s/ as the correspondent of
central-dialect z (e.g. mozol : Andong [masɨl]; p. 139-140). A small, later subset instead shows z > c
after a nasal (swonzwo>swoncwo; p. 143).

**G** is the hardest of the three to detect in texts because its symbol (a bare circle ○) was also used
as the "zero consonant" marking a vowel-initial syllable — the authors walk through several pieces of
internal philological evidence (verb-ending behavior after l-final stems, the y-excrescence facts around
the volitive vs. causative suffixes) to establish it as a real phoneme distinct from zero (pp. 143-144).
G arose from lenition of earlier *g in the environments l_V, z_V, and i/y_V, confirmed by peripheral
Hamgyŏng (Pukch'ŏng) dialect reflexes retaining [g] where central dialects show G/zero (p. 144). The
chapter catalogs G's appearance across several separate morphological categories: k-initial particles
(kwa, kwos, kwom) and verb endings (-kwo, -key, -kenul, etc.) lenited to G after -l/-i/-y stems (pp.
144-145); the causative/passive postverb's allomorph set -ki-/-hi-/-Gi-/-i-/-y- is conditioned by the
preceding stem-final segment, with -Gi- appearing after l-, z-, or y- (p. 145); a second causative
allomorph -Gwu(y)- also shows the pattern (p. 146); the nominalizing suffix -kay/-key lenites to -Gay
after l-/z- stems (kozGay 'scissors'; p. 146); and a scattered set of ordinary nouns/verb stems carry a
consistent G reflecting an original *k (including a nasal-stem subclass like namwo 'tree' that shows an
unlenited velar before vowel-initial particles instead; pp. 146-147). Orthographically, G-spellings were
gradually replaced by double-l spellings starting in the late 1500s and standard by the 17th c. (wolGa >
wolla; p. 149).

#### Spirants: affricates c/ch and sibilants s/ss

LMK plain c and aspirated ch were phonetically apical [ts]/[tsh], not palatalized as in modern Seoul
speech — demonstrated by the transcription of t+s sequences as tc, which is only explicable if c was
[ts] (p. 149). Both affricates (and s) occurred freely before i/y, producing contrasts (cang vs. cyang,
sem vs. syem) usually assumed to reflect palatal allophones before i/y — but the authors flag that
northwestern P'yŏngan dialects today show *no* palatalization in that environment at all, leaving the
date of palatalization's onset an open question (pp. 149-150). s was a contrasting phoneme with z in the
15th century (not purely an allophonic lenition relationship), shown by minimal pairs like tasi 'again'
vs. azi 'first' (p. 150).

#### Nasal and liquid distribution

Labial m occurred nearly unrestricted; dental n occurred freely before i/y in LMK (unlike modern central
dialects, where that was lost later in Early Modern Korean); velar ng never occurred word-initially and
only rarely morpheme-initially, and never ended a verb stem at all (pp. 150-151). At the end of verb
stems, m was common but n was rare (only an- 'embrace,' sin- 'put on shoes,' and the marginal ten- 'bet,
gamble'); ng never occurred stem-finally, then or now (p. 151).

**Nasal epenthesis before affricates** is a separate, cross-checked historical puzzle: some LMK words
show a nasal before an affricate (e.g. kochwo- 'hide') where cognate older forms — recoverable via
pre-Hangul phonogram transcriptions, Cheju reflexes, and etymological analysis of related
dental-stop-final or non-nasal source morphemes — show no nasal at all. The most conclusive single piece
of evidence is the Chinese loanword panchywo 'plantain,' where neither the Mandarin source word nor its
regular Sino-Korean reading contains a nasal, so the nasal in the Korean form must be purely epenthetic
(pp. 151-152).

**Liquid l** had two allophones, [r] and [l], as today (per the Haerye's own explicit discussion of
"light" vs. "heavy" semilingual sounds, p. 152). l did not occur in native-word-initial position (only
in Sino-Korean), and even there, initial l- had already shifted to n- in some words by the 15th century
(pp. 152-153). Some medial [r] instances represent lenited dental stops in Sino-Korean loans borrowed
after a Chinese sound change (mwolan 'peony' < mwoktan). A morpheme-final /l/ sometimes elided before a
following coronal consonant (t, c, s, z, n), consistently in verbal inflection and occasionally in noun
compounds (p. 153).

#### Terminal (syllable-final) consonants

A word could end in a vowel, y, or one of eight consonants: p, t, k, m, n, ng, s, l (p. 153). Aspiration
was neutralized finally (ph/th/kh > p/t/k), and by the 15th century the affricates c/ch were no longer
distinct from s in final position (nac 'daytime' spelled/pronounced nas). Crucially, -s remained distinct
from -t finally — confirmed by the Cháoxiān-guăn yìyŭ's use of two different Chinese characters (思 for
-s, versus leaving -t coda unrepresented) to transcribe the two different Korean codas (pp. 153-154). A
ninth terminal consonant, z, existed but only before another voiced fricative (G or W) in the following
syllable; otherwise it neutralized with s (p. 154). By the start of the 16th century, W and G had vanished
and the -t/-s final-position distinction itself neutralized to -t, which then triggered regressive nasal
assimilation before a following nasal (isnoni > innoni; pp. 154-155). The only terminal clusters allowed
began with l (-lm, -lp, -lk); rare -ks clusters (naks 'hook', neks 'spirit') are attested but it's unclear
the s was actually pronounced pre-juncture (p. 155).

#### Morphophonemic replacement rules

The chapter catalogs five systematic replacement rules (pp. 155-156): (1) h combining with p/t/c/k to
form aspirates, with s to form ss, with n to become t, and dropping before a pause; (2) voiced fricatives
z/W devoicing to s/p before k, t, c, or s; (3) t assimilating to a following n's nasality; (4) initial
k- leniting to G- after a morpheme ending in -l or -y (and the particles kwa/kwos/kwom losing k-
entirely after any vowel); (5) initial t- of certain morphemes (notably forms built on the copula i-)
leniting to l- ([r]) after l-, y-, or a vowel.

#### The vowel system

LMK had seven vowel phonemes: i [i], u [ɨ], e [ə], a [a], wu [u], wo [o], and o [ʌ] (written ㆍ) (p. 156).
Six correspond straightforwardly to modern Seoul vowels; the seventh (ㆍ) has vanished from standard
Seoul speech but survives distinctly in Cheju, pronounced [ɔ]/[ʌ] — the chief evidence used to infer its
LMK pronunciation (p. 156). Because the Hunmin chŏngŭm haerye's own descriptive terminology ("deep,"
"shallow," "contracted," "spread") is not fully understood today, the authors rely heavily on
cross-script transcription evidence instead: Chinese Cháoxiān-guăn yìyŭ (c. 1400) phonograms confirm ㅗ
and ㅜ matched [o]/[u] closely to their modern values; 'Phags-pa Mongolian transliterations in Ch'oe
Sejin's 1517 Sasŏng t'onghae and a 1492 Hangul transliteration of the Japanese Iroha poem both
independently show that Korean had *no* vowel symbol then corresponding cleanly to [e] — [yə] (ㅕ) was
used as the nearest available substitute in both cases (pp. 156-159).

#### The vowel /o/ (ㆍ) and its two-stage loss

The vowel /o/ was lost in two historically separate stages (p. 159). **Stage one**: merger with its
higher counterpart /u/ in *non-initial* syllables, beginning sporadically in the 15th century (isolated
cases like toy>tuy 'place') and essentially complete by the later 16th century (Sohak ŏnhae, 1587),
confirmed with a wealth of textual doublets (pp. 159-160). **Stage two**: merger of /o/ with /a/ in
*initial* syllables — a much later change, not completed until the 18th century, with only two very early
isolated exceptions (holk>hulk 'earth'; somay>swomay 'sleeve') noted in 16th-17th-century texts (p. 160).

#### Semivowels and diphthongs

LMK had two semivowel onglides, y and w (p. 160). y combined with four of the seven vowels to form ya,
ye, ywo, ywu; two further y-diphthongs, yo [yʌ] and yu [yɨ], are explicitly described in the Hunmin
chŏngŭm haerye as occurring only in children's speech or "outlying regions" — i.e., as a regional/
register-marked phenomenon the Haerye itself flags, not standard capital speech (pp. 160-161). Internal
reconstruction from vowel-harmony-violating doublets (yele~yela, reconstructing to *yola) demonstrates a
historical *yo>ye sound change had recently swept the central dialects by the time the Haerye was
written, while the diphthong still survives today in Cheju (pp. 161-162). w combined with vowels to form
wa and we (written by combining vowel symbols); the symbol ㅟ was ambiguous between /wuy/ (its normal
value) and /wi/ (only in forms known from the history of the W>w change) — genuine transcriptional
confusion the authors treat as itself evidence (pp. 162-163). y also functioned as an *offglide*,
producing diphthongs oy, ay, ey, woy, wuy, uy and several triphthongs; nearly all later monophthongized,
which the authors flag as one of the largest single differences between the LMK and modern Seoul vowel
systems (p. 163).

#### Vowel harmony

The Hunmin chŏngŭm haerye itself classifies LMK vowels into "Yin" (um) and "Yang" (yang) groups, with i
alone unclassified ("no station or number") (pp. 163-164). The core rule: within a single word, yang
vowels co-occur only with yang vowels and yin vowels only with yin vowels; i is harmonically neutral and
can appear with either group. This governs not just root-internal vowel choice but also the shape of
many particles and verb endings, which alternate in pairs differing by vowel height (accusative -ol/-ul,
locative -ay/-ey, and paradigmatic endings like -a/e-, -oni/uni-, -omyen/umyen-) (p. 164). Harmony is
blocked by any element that begins with a *consonant* (e.g. the particle man and the gerund -kwo are
invariant) — except for a small, phonologically unexplained exception set including the retrospective
-te/ta- and the perfective -ke/ka-, which are consonant-initial yet still harmonically alternate (p. 164).

#### Tone and accent (the Late Middle Korean pitch system)

LMK texts mark three tones via "side dots" placed to the left of a syllable: no dot = even (lowest)
tone; one dot = departing (highest) tone; two dots = rising tone (begins low, rises) (pp. 165-166,
citing the Hunmin chŏngŭm ŏnhae and 1527 Hunmong chahoe's own descriptions). Minimal pairs distinguished
purely by tone are widely attested (son 'guest' vs. SON 'hand'; PAL 'foot' vs. paAL 'bamboo blind'), and
the system could distinguish words across up to three syllables of pitch pattern (pp. 166).

**The rising tone is analyzed as not phonemically basic** but as a historical/synchronic *contraction* of
a low-pitched syllable plus a high-pitched one into a single long syllable — i.e., two moras (low+high)
rather than one simple tone (pp. 167-168). Multiple independent lines of evidence support this: (1)
historical contractions where an intervening consonant (often h) dropped between a low and a high
syllable, fusing them into one rising-toned syllable (kàhí>kǎy 'dog'); (2) productive synchronic
contraction whenever the nominative particle í, the copula í(y)-, the causative postverb -í-, or the
volitive -wó/wú- attaches to a low-pitched final syllable, which regularly surfaces with a rising tone
(pp. 167-168). The authors also note the limits of this analysis: not every rising-tone syllable is
amenable to such parsing, and a nearly identical-looking two-high-syllable sequence does NOT always
contract to a rising tone if the second high tone isn't itself phonemically distinctive (cúkcàhí
'immediately' failing to contract to the expected *cúkcǎy; p. 170/168).

#### Modern dialect reflexes of the Middle Korean tone system

Central dialects (including modern Seoul) have lost all lexical pitch distinctions outright, retaining
only the historical rising tone's vowel *length* as a trace (pp. 169-170). Several peripheral dialect
regions, however, preserve the system morphophonemically as genuine pitch-accent systems: **Hamgyŏng**
(northeast) and **Kyŏngsang** (southeast) are the two best-documented, with Kangwŏn showing it marginally
and some Chŏlla dialects reportedly but not fully verified (p. 170). In **Hamgyŏng**, word/phrase-level
pitch is organized around a single accent locus: pitch rises toward the accented syllable, then falls
immediately after, staying low to the end — meaning monosyllables like pay 'pear' and páy 'belly' are
actually *homonyms* in isolation in this dialect and only distinguished once followed by a particle or
copula (pp. 170-171). Systematic correspondence tables show the Hamgyŏng accent locus falls precisely on
the syllable that carried the LMK *departing* (high) tone (p. 171). **Kyŏngsang** dialects resemble
Hamgyŏng in general shape but show the accent locus shifted consistently *one syllable to the left*
relative to Hamgyŏng — demonstrated via a systematic noun+particle correspondence table — plus an
additional "no prominent syllable" pattern (two level-high initial syllables) not found in Hamgyŏng at
all, interpreted as resulting from the same historical leftward accent shift applied to originally
prototonic (accentless) forms (pp. 172-174). Kyŏngsang dialects (North: vowel length; South, e.g. Kimhae:
a third extra-low pitch level) also still preserve rising-tone distinctions in initial-syllable position,
a distinction Hamgyŏng has lost (p. 174).

#### Reconciling Middle Korean's suprasegmental system with the modern dialects

The authors draw three key contrasts between the reconstructed LMK system and the modern
pitch-accenting dialects (pp. 174-175): (1) LMK syllable tones were apparently fully distinctive even in
monosyllables, unlike a purely morphophonemic accent system; mistakes in the dot-marking are
vanishingly rare in 15th-century texts, which argues against treating the notation as an idealization.
(2) The syllables leading up to the first high tone are marked low in LMK texts, whereas modern
accenting dialects show a rise into the accented syllable — a difference the authors judge non-critical,
since those intermediate pitches aren't distinctive in the modern systems either. (3) Unlike the modern
dialects (where pitch, once it falls after the accent, stays low for the rest of the phrase), LMK tone
after the first high tone could fluctuate in an "automatic sing-song" alternating pattern (citing Martin
1992) — a genuinely different suprasegmental behavior with no modern parallel. The authors conclude that
only the *location of the first high tone* in a word/phrase was clearly phonemically distinctive in LMK;
evidence for any further tonal contrasts beyond that point is inconsistent within the LMK corpus itself
(same words recorded with varying tone patterns on later syllables across different texts) (pp.
175-176).

#### Tone in pre-Late-Middle-Korean stages

Because no text records tone before the 15th century, earlier-stage pitch must be inferred via internal
reconstruction from the LMK corpus itself (p. 176). This internal evidence suggests earlier Korean had
*fewer* pitch distinctions than the elaborated LMK system shows, and that verb forms in particular
likely carried few or no tone distinctions at all. Statistically, LMK monosyllabic nouns show high tone
roughly four times as often as low tone, and two-syllable nouns show low-high roughly three times as
often as low-low and five times as often as high-(high) — leading the authors to conclude the typical
noun in earlier Korean carried a high pitch on its *final* syllable. The tone system's historical
emergence is attributed to both internal (phonological/morphological) causes and an external cause: the
massive borrowing of Sinitic vocabulary, which — unlike in Sino-Japanese — largely preserved the pitch
categories of the original Chinese tones in Korean (the Chinese "even tone" category shows a 96.6% direct
correlation with Korean low tone) (pp. 176-177, continuing past the assigned range's final page).

---


---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `../../00_Reference_Extraction_Spec.md`. All Hanja/Hangul/
Yale-romanized forms throughout this file are preserved as short, individually-cited lexical/
grammatical items (the legitimate "vocabulary" content of a historical-linguistics source), not as
reproduced source prose; longer analytical passages from the book are paraphrased rather than quoted,
and the handful of direct quotations are sentence-length or shorter, used only where the source's own
wording (or a primary-source excerpt it quotes) is the actual evidence under discussion.
