# Ilocano — Established Vocabulary/Culture: Dictionary Back Matter — "Traditional Ilocano Songs"
Appendix (Kankanta Nga Iloko)

**Source:** Carl R. Galvez Rubino, *Ilocano Dictionary and Grammar: Ilocano-English, English-Ilocano*
(PALI Language Texts, University of Hawai'i Press, © 2000). PDF pages 840–868 of 868 total (the
book's final section). This covers: the tail end of the W–Z English-Ilocano dictionary entries (PDF
pp. 840, finishing "zone"), the Appendixes title page and Grammatical Charts (Tables 1–7, PDF pp.
841–846), three language-distribution maps of the Philippines/Batanes (PDF pp. 847–849), the
**"Traditional Ilocano Songs" / "Kankanta Nga Iloko"** section in full — a table of contents followed
by 44 complete song lyrics (PDF pp. 850–~861, printed pp. 762–~773) — the References/bibliography
(PDF pp. 862–867, printed pp. 774–~779), and the back-cover author blurb (PDF p. 868).

**Scope note, per dispatch instructions:** the dictionary entries (W–Z), Grammatical Charts, and
Maps are **not** tabled here — they belong to the dictionary-body and grammar-appendix dispatches
covering files 002+ in this language's wave, and the Grammatical Charts' verb-focus/aspect tables in
particular visibly continue the morphological paradigms already being captured there (Table 5
"Verbal focus (voice)" and Table 6 "Aspectual morphology of dynamic verbs," PDF pp. 843–845, show
the same ag-/-um-/mang-/-en/-an focus-affix system). This file's vocabulary table is dedicated
entirely to the **"Traditional Ilocano Songs" section**, per the task's explicit culturally-distinctive-
content focus. The References bibliography (PDF pp. 862–867) and the "ABOUT THE AUTHOR" back-cover
blurb (PDF p. 868) are described below but **not tabled**, being purely bibliographic/biographical
front-matter-style content with no lexical content of their own.

**Page-offset confirmation:** the Appendixes section carries its own printed-page footers
("Appendixes · 756" etc.), letting the PDF-to-printed-page offset be verified directly: **PDF page =
printed page + 88** (e.g., printed p. 756 = PDF p. 844; printed p. 763 = PDF p. 851; printed p. 774 =
PDF p. 862), confirmed consistent across the full appendix run.

**Source condition:** `pdftotext` was tried first and the text layer proved clean and directly
readable throughout the songs section — this is a born-digital text layer, not a scan, consistent
with the rest of this dictionary. No vision-reading fallback was needed. Two source-side quirks are
noted rather than silently corrected:

1. **A genuine two-column-layout interleaving artifact** between the songs "Sabong ni Mirasol"
   (Sunflower) and "Ilokana a Nasudi" (Noble, Renowned Ilokana): `pdftotext` read down one printed
   column then jumped into the adjacent column mid-song, so the refrain of one song and the title/
   opening lines of the other appear spliced together in extraction order (visible as the title
   "Ilokana a Nasudi (Noble, Renowned" being interrupted by four lines belonging to a different
   song's refrain before the closing fragment "Tlokana)" — an "I"→"T" misread of "Ilokana" —
   completes it). The two songs' own internal lyrics are each individually legible; only the
   splice point at the column boundary is disordered. Flagged `uncertain` in the table for the two
   directly affected rows.
2. **A block of garbled, duplicate-looking OCR noise** appears in the raw extraction between the
   last song ("Biag Ken Bileg") and the clean "REFERENCES" heading, and again after the clean
   References list before "ABOUT THE AUTHOR." Comparing fragments in this noise (recognizable author
   surnames — Herre, Keesing, Reyes, Rosal — in scrambled order) against the clean References list
   that follows confirms this is a **duplicate, corrupted rendering of the same bibliography page**
   (a leftover secondary OCR text layer stacked under the clean digital one), not additional unseen
   content. It was cross-checked and discarded as noise rather than mined for anything new — the
   same gotcha-class issue as the font-substitution ciphers logged for other languages, but here the
   defect is a stray duplicate text layer rather than a glyph-remapping cipher.

---

## Part 1 — Section overview: "Traditional Ilocano Songs" ("Kankanta Nga Iloko")

The section opens with a two-column table of contents (PDF p. 850) alphabetically listing all 44
song titles with their printed-page locations (pp. 762–771); the raw page-number list itself carries
no lexical content and is not reproduced. The 44 songs that follow are **full lyrics, not glossed
line-by-line** — the book supplies an English translation only for the **song title** (given
parenthetically, e.g. "Pamulinawen (Stone-Hearted Lady)"), not for individual lines. Per the
project's extraction-table convention, Part 2 below tables all 44 titles with their book-given
translations as the highest-confidence lexical data from this section, and Part 3 tables a thorough
(not exhaustive-to-the-token, per copyright discipline) selection of distinct vocabulary items
recurring across the lyrics, glossed from context and standard Ilocano usage where the book itself
gives no line-level translation — flagged accordingly in the Notes column.

**Structural/cultural features observed across the 44 songs (flagship content for this project):**

- **Gendered call-and-response duet structure.** At least three songs are explicitly laid out as
  alternating dialogue between a male and female singer, labeled in the text itself as `Lalaki:`
  ("Man:") and `Babai:` ("Woman:") — **Manang Biday** (a man serenading at a window, the woman
  answering that she is "a lily not yet open"), **Mannamili** ("Potters," a courtship exchange built
  around a broken clay pot as a metaphor/pretext), and **Da Mangngalap ken Agsansana** ("The
  Fisherman and Salt Makers," a similar paired-occupation courtship exchange). This is a recognized
  Ilocano/Philippine folk-song genre convention (a sung courtship debate), not incidental formatting.
- **Refrain/Chorus/Koro labeling.** Repeating sections are explicitly marked in three different
  terms within the same section: English `Refrain:` and `Chorus:` (used interchangeably across
  different songs) and the Spanish-derived `Koro:` (used once, for "Biag Ken Bileg") — all three
  terms for the same structural device, suggesting no single fixed convention was imposed by the
  source's own editorial compilation.
- **Footnoted oral-tradition variants.** Four lines across three songs carry an explicit `alt:`
  footnote giving a second attested wording for the same line (e.g., for "Imdengam O Imnas": main
  text "Ta siksika awan sabali" footnoted `alt: Nagtaud gapu kenka, sika awan sabali`; for "No
  duaduaem pay": main text "Nalawag la unayen a ranggasmo kaniak" footnoted `alt: Nalawag la unayen
  nga ulpitmo ken ranggas`), plus two songs carry an explicit **alternate title** footnote ("Imdengam
  O Imnas" / "Apay, Apay"; "Saguday" / "Ta Nagsaway a Pintasmo"). This is concrete, source-stated
  evidence of genuine oral-tradition textual variation being preserved rather than normalized away —
  directly relevant to this project's interest in how real speech communities carry multiple
  attested forms of the same utterance.
- **Occasion-specific songs, explicitly labeled by the source.** Several titles carry an explicit
  English functional subtitle rather than just a literal translation: **Padapadatayo** "(Ilocos Norte
  Birthday Song)" [explicit regional attestation — recorded below], **Ala Kadin, Inkay Yawat**
  "(Please Give — Christmas Song)," **Panawankan Biagko** "(Farewell, My Love [Deathbed Song])," and
  **Laguerta ti Langit** "(Door of Heaven — Humorous Song)." These function-labels are the book's own
  genre classification, not inferred.
- **Near-duplicate title pair.** The section contains two distinct, back-to-back songs with nearly
  identical titles differing only by a single enclitic: **No Siak ti Agayat** "(If I Were the One to
  Love)" and **No Siakto ti Agayat** "(When I Love)" — both independently listed in the table of
  contents as separate songs with separate lyrics (one built on seasonal/courtship-gift imagery, the
  other on choosing a humble, virtuous bride over wealth) — worth flagging as a genuine minimal-pair
  curiosity in the oral tradition's own naming practice.

---

## Part 2 — Song titles (book-given English translations)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Pamulinawen | Stone-Hearted Lady | song title (noun phrase) | folk song (traditional) | — | traditional (undated; source header "Traditional Ilocano Songs") | — | — | grammar_reference | verified | n/a | one of the best-known Ilocano folk songs nationally; refrain built on "diak kalipatan" (I will not forget) |
| Manang Biday | Older Sister Biday | song title (noun phrase) | folk song (traditional) | — | traditional (undated) | — | — | grammar_reference | verified | n/a | gendered call-and-response courtship duet, labeled `Lalaki:`/`Babai:` in the text |
| Naraniag a Bulan | Shiny Moon | song title (noun phrase) | folk song (traditional) | — | traditional (undated) | — | — | grammar_reference | verified | n/a | serenade addressed directly to the moon as witness/confidant |
| Ti Ayat ti Maysa Nga Ubing | The Love of a Child | song title (noun phrase) | folk song (traditional) | — | traditional (undated) | — | — | grammar_reference | verified | n/a | contrasts a child's love (sweeter than jasmine) with an old man's love (bitter); carries an `alt:` line footnote |
| Bannatiran | Bannatiran Bird | song title (proper/noun) | folk song (traditional) | — | traditional (undated) | — | — | grammar_reference | verified | n/a | shortest lyric in the section (4 lines); addressed to a named bird as confidant, asking where it roosts |
| Imdengam O Imnas | Listen, O Precious One | song title (noun phrase) | folk song (traditional) | — | traditional (undated) | — | — | grammar_reference | verified | n/a | alternate title footnoted: "Also referred to as Apay Apay" (the TOC also cross-references "Apay, Apay (see Imdengam..)") |
| Duayya ni Ayat (Dungdunguenkanto) | Lullaby of Love (I Will Love You) | song title (noun phrase) | folk song (traditional) | — | traditional (undated) | — | — | grammar_reference | verified | n/a | double title given directly in the source; addressed as a lullaby to an adult beloved, not a literal infant |
| No duaduaem pay | If You Still Doubt — Serenade | song title (conditional clause) | folk song (traditional) | — | traditional (undated) | — | — | grammar_reference | verified | n/a | source's own English subtitle explicitly labels this a "Serenade"; carries an `alt:` line footnote |
| Padapadatayo | (Ilocos Norte Birthday Song) | song title (noun phrase) | folk song (traditional) | — | traditional (undated) | **Ilocos Norte** (explicit) | regional (Ilocos Norte, Philippines) | grammar_reference | verified | n/a | the only song in the section with an explicit, source-stated provincial attestation; birthday-greeting song addressed to the celebrant by name (placeholder "(nagan)" left in the lyric for the name to be inserted) |
| Toy Karayo | This Affection | song title (noun phrase) | folk song (traditional) | — | traditional (undated) | — | — | grammar_reference | verified | n/a | — |
| Tagtagainep Laeng | Just a Dream | song title (noun phrase) | folk song (traditional) | — | traditional (undated) | — | — | grammar_reference | verified | n/a | narrates waking from a dream of the beloved to find it untrue |
| Ayat kadagiti Ama ken Ina | Love for Father and Mother | song title (noun phrase) | folk song (traditional) | — | traditional (undated) | — | — | grammar_reference | verified | n/a | filial-devotion song, not a romantic one — a thematic outlier among the mostly courtship-themed set |
| Igid Diay Baybay | Shoreline | song title (noun phrase) | folk song (traditional) | — | traditional (undated) | — | — | grammar_reference | verified | n/a | frames filial debt to parents through a seaside setting |
| Saguday | (Ta Nagsaway a Pintasmo) | Precious Gift | song title (noun phrase) | folk song (traditional) | — | traditional (undated) | — | — | grammar_reference | verified | n/a | alternate title footnoted: "Also called 'Ta Nagsaway a Pintasmo'" |
| No Siak ti Agayat | If I Were the One to Love | song title (conditional clause) | folk song (traditional) | — | traditional (undated) | — | — | grammar_reference | verified | n/a | first of the near-duplicate-title pair (see Part 1); built on seasonal/gift-giving imagery (handkerchief, ring, lemon candy) |
| No Siakto ti Agayat | When I Love | song title (conditional clause) | folk song (traditional) | — | traditional (undated) | — | — | grammar_reference | verified | n/a | second of the near-duplicate-title pair; the singer vows to choose a humble, virtuous woman over wealth |
| Ala Kadin, Inkay Yawat | (Christmas Song) | Please Give | song title (imperative phrase) | folk song (traditional) | — | traditional (undated) | — | — | grammar_reference | verified | n/a | source's own subtitle labels this a Christmas carol/begging-song; references receiving a piglet as a gift |
| Dung-aw | Dirge | song title (noun) | folk song (traditional) | — | traditional (undated) | — | — | grammar_reference | verified | n/a | shortest funerary lyric; a child's lament addressed to a deceased father |
| Pakada | Farewell | song title (noun) | folk song (traditional) | — | traditional (undated) | — | — | grammar_reference | verified | n/a | farewell addressed to a lover, with a kept photograph as a keepsake motif |
| Panagpakada | Farewell | song title (noun, nominalized) | folk song (traditional) | — | traditional (undated) | — | — | grammar_reference | verified | n/a | distinct song from "Pakada" above despite the shared English gloss and root; a child's farewell to parents and childhood home before departure ("Agpakada'kon... Adios Tatang ken Nanang") |
| Panawankan Biagko | Farewell, My Love (Deathbed Song) | song title (clause) | folk song (traditional) | — | traditional (undated) | — | — | grammar_reference | verified | n/a | source's own subtitle explicitly labels this a deathbed song |
| Mannamili | Potters | song title (noun, agentive) | folk song (traditional) | — | traditional (undated) | — | — | grammar_reference | verified | n/a | gendered call-and-response courtship duet built around pottery-making labor and a broken clay pot |
| Duayya | Lullaby | song title (noun) | folk song (traditional) | — | traditional (undated) | — | — | grammar_reference | verified | n/a | addressed to an infant son, imagining his future strength and marriage |
| Nasudi ni Ayat | Love Is Grand | song title (noun phrase) | folk song (traditional) | — | traditional (undated) | — | — | grammar_reference | verified | n/a | reflective/didactic rather than courtship-address lyric; warns against deceitful lovers |
| Da Mangngalap ken Agsansana | The Fisherman and Salt Makers | song title (noun phrase) | folk song (traditional) | — | traditional (undated) | — | — | grammar_reference | verified | n/a | gendered call-and-response courtship duet pairing two coastal occupations (fishing / salt-making) |
| Kanta ti Ulila | Song of an Orphan | song title (noun phrase) | folk song (traditional) | — | traditional (undated) | — | — | grammar_reference | verified | n/a | an orphan's lament, told in first person from childhood |
| Tarong, Kamatis, Paria | Eggplant, Tomato, Bittermelon | song title (noun list) | folk song (traditional) | — | traditional (undated) | — | — | grammar_reference | verified | n/a | personifies three garden vegetables bickering over whose dish is tastiest — a didactic/humorous vegetable-health song for children |
| Laguerta ti Langit | Door of Heaven (Humorous Song) | song title (noun phrase) | folk song (traditional) | — | traditional (undated) | — | — | grammar_reference | verified | n/a | source's own subtitle labels this humorous; a nonsense/animal-character song (owl, cricket, firefly, crab named as characters) |
| Ilokana a Nadayag | Popular Ilocana | song title (noun phrase) | folk song (traditional) | — | traditional (undated) | — | — | grammar_reference | verified | n/a | praise-song addressed to Ilocana women generally as a cultural ideal |
| Kasasaad ti Kinabalasang | Condition of Maidenhood | song title (noun phrase) | folk song (traditional) | — | traditional (undated) | — | — | grammar_reference | verified | n/a | cautionary/didactic song on the risks of marriage for young women |
| As-asug dagiti Kararua | The Complaints of the Souls | song title (noun phrase) | folk song (traditional) | — | traditional (undated) | — | — | grammar_reference | verified | n/a | funerary/vigil lament sung in the voice of the dead, addressing mourning parents directly |
| Bulan Sardam | Evening Moon | song title (noun phrase) | folk song (traditional) | — | traditional (undated) | — | — | grammar_reference | verified | n/a | very short lyric (6 lines), names specific places (San Juan, Bamban) |
| Tontonennaka toy Ayat | My Love Looks for You | song title (clause) | folk song (traditional) | — | traditional (undated) | — | — | grammar_reference | verified | n/a | — |
| Ti Dayaw | Honor | song title (noun) | folk song (traditional) | — | traditional (undated) | — | — | grammar_reference | verified | n/a | didactic song on guarding one's honor/reputation against deceitful suitors |
| Dagiti Mulak | My Plants | song title (noun phrase) | folk song (traditional) | — | traditional (undated) | — | — | grammar_reference | verified | n/a | uses planted crops (katuday tree, tobacco) raided by birds/livestock as an extended courtship-guarding metaphor |
| Toy Datonko | My Offering | song title (noun phrase) | folk song (traditional) | — | traditional (undated) | — | — | grammar_reference | verified | n/a | offers the heart itself, metaphorized as a flower/star necklace, to the beloved |
| Sainita | Ideal Farmer's Wife | song title (proper/noun) | folk song (traditional) | — | traditional (undated) | — | — | grammar_reference | verified | n/a | praises the hardship and virtue of a farmer's wife's daily labor |
| Agdamdamilikami | We Are Potters | song title (verb phrase, 1pl.excl) | folk song (traditional) | — | traditional (undated) | — | — | grammar_reference | verified | n/a | distinct lyric from "Mannamili" above despite the shared pottery theme; explicitly localized "Taga-San Nicolaskami" (we are from San Nicolas) — a named town, though not flagged by the source as a formal regional attestation the way Padapadatayo's subtitle is |
| Umayka ti Eskuela | Come to School | song title (imperative clause) | folk song (traditional) | — | traditional (undated) | — | — | grammar_reference | verified | n/a | a didactic children's song urging school attendance |
| Ngaminen ta Ranggas | Because of Your Cruelty | song title (clause) | folk song (traditional) | — | traditional (undated) | — | — | grammar_reference | verified | n/a | accusatory love-complaint; carries a `Chorus:` section |
| Malaglagipka Laeng | I Just Remember You | song title (verb phrase) | folk song (traditional) | — | traditional (undated) | — | — | grammar_reference | verified | n/a | — |
| Sabong ni Mirasol | Sunflower | song title (noun phrase) | folk song (traditional) | — | traditional (undated) | — | — | grammar_reference | **uncertain** (column-interleaving splice, see Part 0 note) | n/a | lyric compares the beloved to sunflower/lily blossoms |
| Ilokana a Nasudi | Noble, Renowned Ilokana | song title (noun phrase) | folk song (traditional) | — | traditional (undated) | — | — | grammar_reference | **uncertain** (column-interleaving splice, see Part 0 note) | n/a | title itself reconstructed across a page-column splice artifact (fragments "Ilokana a Nasudi (Noble, Renowned" + "Tlokana)"); praise-song to a devoted, faithful Ilocana woman |
| Biag Ken Bileg | Life and Power | song title (noun phrase) | folk song (traditional) | — | traditional (undated) | — | — | grammar_reference | verified | n/a | last song in the section; its repeat-section is labeled `Koro:` (Spanish-derived "coro," rather than the `Refrain:`/`Chorus:` used elsewhere) |

---

## Part 3 — Vocabulary recurring across the lyrics

The book supplies no line-level translation for these — glosses below are drawn from the words'
standard, well-attested Ilocano meanings (several independently cross-checked against this same
dictionary's W–Z English-Ilocano entries read in the same page range, e.g. *dayaw* "to worship/
honor" at the W-page entry for "worship," *pateg* "worth" at the entry for "worth," *balasang* "young
unmarried woman" at the entry for "young," *wen* "yes" at the entry for "yes" — all of which recur
directly in the song lyrics) rather than from any book-given line gloss, and are marked as such.

### Love, courtship & emotion vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| ayat | love | noun/verb | literary/poetic | very frequent (the section's dominant theme word) | — | — | — | grammar_reference | verified | n/a | gloss inferred from context and cross-song consistency (confirmed by nearly every song's own English title, e.g. "Ayat kadagiti Ama ken Ina" = "Love for..."); base of agayat "to love," agayatan, ay-ayaten "beloved/loved" |
| pusok | my heart | noun (possessed) | literary/poetic | frequent | — | — | — | grammar_reference | verified | n/a | puso "heart" + -k (1sg possessive); the section's most common vocative/addressee term, e.g. "Pamulinawen, pusok indengam man" |
| sudi / nasudi | noble, refined, precious | noun/stative adj. | literary/poetic | frequent | — | — | — | grammar_reference | verified | n/a | gloss inferred from context; root of several song titles ("Nasudi ni Ayat," "Ilokana a Nasudi") and the recurring epithet "nasudi a nagan" (a precious/renowned name) |
| imnas | exquisite, precious one | noun/stative adj. | literary/poetic | frequent | — | — | — | grammar_reference | verified | n/a | gloss inferred from context; used as a direct vocative for the beloved ("Imdengam, O Imnas" = "Listen, O Precious One" — the book's own title translation directly confirms this gloss) |
| kasam-itan | sweetest | stative adj. (superlative) | literary/poetic | — | — | — | — | grammar_reference | verified | n/a | sam-it "sweet" + -an suffix in superlative/intensive use; "naganmo nga kasam-itan" (your sweetest name) |
| karayo | affection, fondness | noun | literary/poetic | — | — | — | — | grammar_reference | verified | n/a | gloss inferred from context; title noun of "Toy Karayo" (This Affection) |
| kalipatan / malipatan | to forget | verb | literary/poetic | — | — | — | — | grammar_reference | verified | n/a | gloss inferred from context (Pamulinawen's refrain "Issemmo diak kalipatan," I will not forget your smile) |
| duaduaem | you doubt (it) | verb (reduplicated root) | literary/poetic | — | — | — | — | grammar_reference | verified | n/a | dua-dua (reduplicated "doubt") + -em (2sg patient-focus); title verb of "No duaduaem pay" |
| ranggas | cruelty, harshness | noun | literary/poetic | — | — | — | — | grammar_reference | verified | n/a | gloss inferred from context; title noun of "Ngaminen ta Ranggas" (Because of Your Cruelty); also appears in the `alt:` footnote variant for "No duaduaem pay" alongside ulpit "cruel/merciless" |
| ulbod / naulbod | lie, deceit / deceitful | noun/stative adj. | literary/poetic | — | — | — | — | grammar_reference | verified | n/a | recurs as a standard warning-epithet for false lovers ("naulbod nga agayat," a deceitful lover) in at least two songs ("Nasudi ni Ayat," "Dagiti Mulak") |
| singpet / nasingpet | virtue, good behavior / virtuous, well-behaved | noun/stative adj. | literary/poetic | — | — | — | — | grammar_reference | verified | n/a | recurs as the praised counter-quality to ulbod across several songs |
| liday / leddaang | sorrow, grief | noun | literary/poetic | — | — | — | — | grammar_reference | verified | n/a | two near-synonyms both attested, suggesting a productive sorrow/grief semantic field rather than one fixed term |
| liwliwa | comfort, consolation | noun | literary/poetic | — | — | — | — | grammar_reference | verified | n/a | gloss inferred from context ("Pakada": "Sayamusom nga liwliwa," your constant comfort) |
| gasat | fate, fortune | noun | literary/poetic | — | — | — | — | grammar_reference | verified | n/a | gloss inferred from context, recurs across courtship and didactic songs alike ("Sabong ni Mirasol," "Padapadatayo") |
| dungngo | tenderness, affection | noun | literary/poetic | — | — | — | — | grammar_reference | verified | n/a | paired with ayat in "Igid Diay Baybay": "Ayat dungngoda'y naruay" (their love and tenderness overflowing) |

### Kinship, address terms & social vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Manang | older sister / respectful term of address for an older woman | noun / term of address | core | — | — | — | — | grammar_reference | verified | n/a | title term in "Manang Biday"; used vocatively, not strictly literal kinship |
| Manong | older brother / respectful term of address for an older man | noun / term of address | core | — | — | — | — | grammar_reference | verified | n/a | used vocatively in "Mannamili" and "Da Mangngalap ken Agsansana" courtship duets |
| Ading | younger sibling / affectionate term of address for a younger or beloved person | noun / term of address | core | — | — | — | — | grammar_reference | verified | n/a | widely used as a term of endearment for a (not necessarily literal) younger beloved, e.g. "Denggem ading" (listen, dear) |
| Nanang / Inang | mother (term of address) | noun / term of address | core | — | — | — | — | grammar_reference | verified | n/a | — |
| Tatang | father (term of address) | noun / term of address | core | — | — | — | — | grammar_reference | verified | n/a | — |
| Neneng / Nena | diminutive term of endearment for a girl/young woman | proper noun (hypocoristic) | literary/poetic | — | — | — | — | grammar_reference | verified | n/a | gloss inferred from context; used as a direct vocative in "Pamulinawen" and "Dagiti Mulak" ("Gapuna, Neneng, dika agpuloko") |
| Lelong | grandfather (term of address) | noun / term of address | core/regional (mixed) | — | — | — | — | grammar_reference | verified | n/a | appears in "Ti Ayat ti Maysa nga Ubing" addressed to an old man ("Baybay-am ta ubing, Lelong"); Spanish-contact-derived term of address, cognate with widespread Philippine "Lelong/Lola" grandparent vocabulary |
| balasang | young unmarried woman, maiden | noun | core | — | — | — | — | grammar_reference | verified | n/a | cross-checked directly against this dictionary's own W-page English-Ilocano entry "young unmarried woman: n. balasang"; title noun of "Kasasaad ti Kinabalasang" (Condition of Maidenhood) |
| kinabalasang | maidenhood, the state of being an unmarried young woman | noun (abstract, ki-...-an nominalization) | core | — | — | — | — | grammar_reference | verified | n/a | balasang + ki-...-an abstract-state circumfix |
| ulila | orphan | noun | core | — | — | — | — | grammar_reference | verified | n/a | title noun of "Kanta ti Ulila" |
| asawa | spouse | noun | core | — | — | — | — | grammar_reference | verified | n/a | appears in "Sainita" ("Panagbiag asawa't mannalon," the life of a farmer's wife) |

### Nature, cosmos & place vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| bulan | moon | noun | core | — | — | — | — | grammar_reference | verified | n/a | addressed directly as confidant in "Naraniag a Bulan" (Shiny Moon) and named in "Bulan Sardam" (Evening Moon) |
| baybay | sea, shore | noun | core | — | — | — | — | grammar_reference | verified | n/a | title noun of "Igid Diay Baybay" (Shoreline) |
| sabong | flower, blossom | noun | literary/poetic | — | — | — | — | grammar_reference | verified | n/a | the section's single most common metaphor-vehicle for a beloved woman, e.g. "Sabong ni Mirasol," "Toy Datonko" |
| bituen | star | noun | literary/poetic | — | — | — | — | grammar_reference | verified | n/a | used as a gift-metaphor in "Toy Datonko" ("No daytoy koma ket bituen," if only this were a star) |
| bullalayaw | rainbow | noun | literary/poetic | — | — | — | — | grammar_reference | verified | n/a | simile vehicle in "Saguday" ("Ket ta kidaymo kas bullalayaw iti malem," your eyebrows like an evening rainbow) |
| kannaway | heron / egret (a wading-bird species) | noun | core/regional (mixed) | — | — | — | — | grammar_reference | verified | n/a | gloss inferred from standard Ilocano usage (a well-attested bird name in Ilocano, distinct from the titular "bannatiran"); appears in "Dagiti Mulak" as a crop-raiding bird |
| bannatiran | name of a small bird (species not specified by source) | noun (proper/species name) | literary/poetic | — | — | — | — | grammar_reference | verified | n/a | **not independently glossed by the book beyond the song's own title translation "Bannatiran Bird"** — left unidentified rather than guess-filling a specific species |
| katuday | a cultivated tree (likely *Sesbania grandiflora*, a common Philippine dooryard/forage tree) | noun | core/regional (mixed) | — | — | — | — | grammar_reference | **uncertain** (species identification inferred, not source-confirmed) | n/a | gloss offered cautiously from general Philippine-plant-name knowledge, not confirmed by this source directly |
| tanem | grave | noun | literary/poetic | — | — | — | — | grammar_reference | verified | n/a | recurs as an end-point/finality image across multiple love songs, e.g. "Sagudayko tungpal tanem" (my devotion/longing, until the grave) |

### Death, mourning & fate vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| dung-aw | dirge, funeral lament | noun | literary/poetic (genre term) | — | — | — | — | grammar_reference | verified | n/a | title noun of "Dung-aw" and a named genre of Ilocano funerary song in its own right, distinct from "duayya" (lullaby) despite superficial phonetic similarity |
| as-asug | lament, wailing complaint | noun (reduplicated) | literary/poetic (genre term) | — | — | — | — | grammar_reference | verified | n/a | title noun of "As-asug dagiti Kararua" (The Complaints of the Souls) |
| kararua | soul, spirit | noun | core | — | — | — | — | grammar_reference | verified | n/a | — |
| pakada / panagpakada | farewell / the act of saying farewell | noun / noun (nominalized) | core | — | — | — | — | grammar_reference | verified | n/a | base of two distinct titled songs in the section (see Part 2 note on "Pakada" vs. "Panagpakada") |
| patay | death | noun | core | — | — | — | — | grammar_reference | verified | n/a | — |
| biag | life | noun | core | — | — | — | — | grammar_reference | verified | n/a | title noun of "Biag Ken Bileg" (Life and Power) and recurs constantly throughout as the stakes-term in love/farewell songs ("panawankan biagko," you are leaving my life/love) |
| sililiday | sorrowful, full of grief | stative adj. | literary/poetic | — | — | — | — | grammar_reference | verified | n/a | liday "sorrow" + si-...-an-type affixation ("tanem a sililiday," a sorrowful grave) |

### Folklife, occupations & material-culture vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| mannamili | potter (one who makes pottery) | noun (agentive, mang-/man- + damili) | core/regional (mixed) | — | — | — | — | grammar_reference | verified | n/a | title noun of two distinct songs ("Mannamili," "Agdamdamilikami"); self-described occupational identity sung by the potters themselves ("Taga-awaykami nga agdamdamili," we potters are from the lowland) |
| damili / agdamdamili | to make pottery | verb | core/regional (mixed) | — | — | — | — | grammar_reference | verified | n/a | root of mannamili above |
| banga | clay cooking pot | noun | core | — | — | — | — | grammar_reference | verified | n/a | central courtship-pretext object in "Mannamili" ("Ta nabuong tay banga," the pot is broken) |
| mangngalap | fisherman (one who fishes) | noun (agentive) | core | — | — | — | — | grammar_reference | verified | n/a | title noun of "Da Mangngalap ken Agsansana" |
| agsansana | salt-making (the occupation/activity) | noun/verb | core/regional (mixed) | — | — | — | — | grammar_reference | verified | n/a | gloss inferred from context; paired occupational identity with mangngalap in the same title and duet |
| asin | salt | noun | core | — | — | — | — | grammar_reference | verified | n/a | "Asin ti pagbiaganmi," salt is our livelihood |
| ikan | fish | noun | core | — | — | — | — | grammar_reference | verified | n/a | — |
| kurita | octopus | noun | core | — | — | — | — | grammar_reference | verified | n/a | "Agkalap ikan ken kurita," to fish for fish and octopus |
| tarong | eggplant | noun | core | — | — | — | — | grammar_reference | verified | n/a | title noun of "Tarong, Kamatis, Paria," personified as a speaking character |
| kamatis | tomato | noun | core | — | — | — | — | grammar_reference | verified | n/a | personified character in the same song |
| paria | bitter melon, bittergourd (ampalaya) | noun | core | — | — | — | — | grammar_reference | verified | n/a | personified character in the same song |
| dinengdeng | a mixed-vegetable Ilocano stew | noun | core/regional (mixed) | — | — | — | — | grammar_reference | verified | n/a | named directly by "kamatis" the character as the dish it belongs in — a real, still-current named Ilocano dish, directly useful as culturally-attested food vocabulary |
| mannalon | farmer | noun (agentive) | core | — | — | — | — | grammar_reference | verified | n/a | "Sainita"'s subject is explicitly glossed by the source's own subtitle as "Ideal Farmer's Wife" |

### Spanish-contact loanword layer

A distinct, recognizable layer of Spanish-derived loanwords recurs across the courtship songs,
nearly all naming either imported luxury/gift objects or church/calendar institutions — directly
relevant to this project's interest in contact-driven vocabulary layers.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| eskuela | school | noun (Spanish loan, *escuela*) | core | — | — | — | — | grammar_reference | verified | n/a | title noun of "Umayka ti Eskuela" |
| hardin | garden | noun (Spanish loan, *jardín*) | literary/poetic | — | — | — | — | grammar_reference | verified | n/a | "Manang Biday" ("Ditoy hardinko pagay-ayamak") and "Panagpakada" ("Adios hardin") |
| bentana | window | noun (Spanish loan, *ventana*) | literary/poetic | — | — | — | — | grammar_reference | verified | n/a | "Manang Biday" ("Ta bentana ikalumbabam") |
| kutsilyo | knife | noun (Spanish loan, *cuchillo*) | literary/poetic | — | — | — | — | grammar_reference | verified | n/a | "Manang Biday" ("Alaem dayta kutsilyo") |
| adios | goodbye | interjection (Spanish loan) | literary/poetic | — | — | — | — | grammar_reference | verified | n/a | used directly, untranslated, four times in "Panagpakada" ("Adios hardin," "Adios Tatang ken Nanang") |
| retrato | photograph | noun (Spanish loan, *retrato*) | literary/poetic | — | — | — | — | grammar_reference | verified | n/a | "Pakada" ("Daytoy retratok ipenpenmo," keep this photograph of mine) |
| sampaguita | jasmine (the Philippine national flower) | noun (Spanish-mediated loan, *sampaguita*) | core | — | — | — | — | grammar_reference | verified | n/a | "Biag Ken Bileg" ("Sampaguita nga napusaksak") |
| lirio | lily | noun (Spanish loan, *lirio*) | literary/poetic | — | — | — | — | grammar_reference | verified | n/a | "Manang Biday" ("Sabong ni lirio, dipay nagukrad") and "No Siak ti Agayat" |
| mirasol | sunflower | noun (Spanish loan, *girasol* > *mirasol*) | literary/poetic | — | — | — | — | grammar_reference | verified | n/a | title noun of "Sabong ni Mirasol" |
| marfil | ivory | noun (Spanish loan, *marfil*) | literary/poetic | — | — | — | — | grammar_reference | verified | n/a | simile vehicle for teeth in "Saguday" ("dayta kas marfil a ngipen") |
| aritos | earrings | noun (Spanish loan, *aretes*) | core | — | — | — | — | grammar_reference | verified | n/a | "Duayya" (lullaby) ("tay aritosko nga birilyanti") |
| birilyanti | brilliant-cut (of a gem) | stative adj. (Spanish loan, *brillante*) | literary/poetic | — | — | — | — | grammar_reference | verified | n/a | same line as aritos above |
| diamanti | diamond | noun (Spanish loan, *diamante*) | literary/poetic | — | — | — | — | grammar_reference | verified | n/a | "Duayya": "singsingko nga diamanti" |
| tamburi | a brass-band horn/trumpet instrument | noun (Spanish loan, likely *tambor*/*trompeta*-contaminated form) | core/regional (mixed) | — | — | — | — | grammar_reference | **uncertain** (etymology inferred, not source-confirmed) | n/a | "Duayya": "tay manto kad a tamburi" |
| kabalio | horse | noun (Spanish loan, *caballo*) | core | — | — | — | — | grammar_reference | verified | n/a | "Dagiti Mulak" ("Ni nadawel a kabalio") |
| koro | chorus/refrain (of a song) | noun (Spanish loan, *coro*) | literary/poetic (genre/structural term) | — | — | — | — | grammar_reference | verified | n/a | the structural label used uniquely in "Biag Ken Bileg" where other songs use English `Refrain:`/`Chorus:` — see Part 1 |

---

## Notes on flagship/archaic content

- **Genre-term vocabulary is a direct extraction target in its own right.** This section hands the
  project several named Ilocano song/lament genres as distinct lexical items: *duayya* (lullaby,
  including addressed to adults, not only infants), *dung-aw* (funeral dirge), *as-asug* (lament/
  wailing complaint, specifically in the voice of the dead), and the borrowed *koro* alongside native
  *Refrain:*/`Chorus:` labeling. These are genre-classifying words, not ordinary content vocabulary,
  and are worth cross-referencing against any dedicated Ilocano oral-literature/music source if one
  surfaces later in this project's source material.
- **The vocative/address-term system (Manang, Manong, Ading, Neneng, Lelong) recurs so consistently
  across unrelated songs** that it reads as a fixed sung-courtship register convention rather than
  song-specific flavor — any beloved, regardless of literal kinship, is addressed with a kinship-
  style vocative (ading "younger sibling," Neneng "little girl") rather than a neutral term, directly
  comparable to similar kin-term-as-endearment conventions already flagged in other languages in this
  project (cf. Hawaiian **pet-name** entry notes, Dutch/Hungarian diminutive-address patterns).
- **The Spanish-loanword layer here skews toward luxury/gift objects and church/calendar
  institutions** (eskuela, hardin, retrato, marfil, birilyanti, diamanti, aritos, adios) rather than
  everyday core vocabulary — a different loanword register than the basic-subsistence Spanish layer
  one might expect, and worth comparing against the loanword patterns likely already surfacing in
  this language's main dictionary-body dispatches.
- **bannatiran is left deliberately unglossed beyond its own song's title translation.** The source
  gives no species identification for this bird beyond naming a song after it; rather than guess-fill
  a specific bird species, this is recorded as an open item — a genuinely archaic or highly localized
  bird name candidate worth checking against a dedicated Ilocano natural-history source if one
  surfaces later.
- **The `alt:` footnoted line variants and the two alternate-title footnotes are the single most
  valuable structural finding in this file for the project's synthetic-slang-derivation purpose**:
  they are the source's own explicit acknowledgment that a traditional sung text circulates in more
  than one attested wording — concrete, source-stated evidence of linguistic variation within a
  single speech/song community, rather than inferred or assumed variation.

---

## References and back-cover blurb (not tabled)

**References (PDF pp. 862–867, printed pp. 774–~779):** a conventional academic bibliography of
~60 works on Ilocano, Philippine, and Cordilleran linguistics/folklore (Vanoverbergh, Carro, Rubino's
own prior works, Constantino, Reid, Zorc, Yabes, etc.), confirming the dictionary's own stated sources
(Vanoverbergh 1956 as the base skeleton, itself derived from Carro's 1888 *Vocabulario Iloco-Español*).
No lexical/vocabulary content of its own beyond citation metadata — correctly out of scope for a
vocabulary table per the task's own instruction not to table it.

**Back-cover blurb / "ABOUT THE AUTHOR" (PDF p. 868):** author biography (Carl Rubino, then Senior
Computational Lexicographer at AnswerLogic) and standard back-cover marketing copy describing the
dictionary's own scope and features (root-based entries, English-Ilocano section, pre-Hispanic
syllabary information, language-distribution maps), plus ISBN/publisher imprint and cover-art credit
(Vicente Manansala's 1975 painting "Market scene"). Purely bibliographic/promotional; not tabled, per
task instructions.

---

## Copyright discipline reminder

Song titles and their book-given English translations are reproduced as direct bilingual-lexical data
(the explicit subject of this extraction). Individual lyric lines are quoted only in short fragments
to anchor specific vocabulary glosses or to document the oral-variant footnotes and structural
features described above — never as bulk reproduction of a song's full text. See
`00_Reference_Extraction_Spec.md`.
