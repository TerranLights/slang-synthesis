# Norwegian — Established Vocabulary: Norske Folke-Eventyr, vol. II (literature sample)

**Source:** P. Chr. Asbjørnsen og Jørgen Moe, *Norske Folke-Eventyr. Fællessamlingen.* Syvende
Udgave [7th edition] revideret ved Moltke Moe. Bind II. Kristiania: Forlagt af H. Aschehoug & Co
(W. Nygaard), 1904. Scanned source has **no text layer at all** (`pdftotext` returns nothing on
any page); every page used below was vision-read from `pdftoppm -png -r 150` renders. 226 PDF
pages total; printed page numbers run `pdf_page − 10` from PDF page 11 onward (verified by direct
inspection of printed-page-number headers, not assumed from a fixed-offset formula).

**Coverage note.** This is Wave 4 of Norwegian extraction and the first from native-language
literature rather than a grammar/dictionary/phrasebook reference (files 001–017 already cover
Norwegian grammar/vocabulary systematically). Per dispatch, this is a **sample**, not exhaustive
coverage of all 226 pages — 9 of the volume's 26 tales were sampled (2 pages each, except tale 1
at 2 pages and the title/TOC front matter), spread across the early, middle, and late volume, to
capture genuine lexical/idiomatic/register variety rather than read the book cover-to-cover. A
sibling agent extracted Volume I in parallel as file 018; this file focuses on Volume II's own
distinct tales rather than re-describing shared Asbjørnsen/Moe-tradition formulae in depth.

**Tales sampled** (printed page ranges; PDF page = printed page + 10):
- Front matter: title page (PDF p.11→ actually p.5) and table of contents (PDF pp. 7–9)
- Tale 1, *De tre Søstre som blev indtagne i Berget* ("The Three Sisters Taken into the
  Mountain") — printed pp. 2–3
- Tale 6, *De tre Bukkene Bruse* ("The Three Billy Goats Gruff") — printed pp. 46–47
- Tale 7, *Østenfor Sol og vestenfor Maane* ("East of the Sun and West of the Moon") — printed
  pp. 48–49
- Tale 12, *Mestermø* ("Master-Maid") — printed pp. 80–81
- Tale 15, *Per og Paal og Espen Askeladd* — printed pp. 110–111
- Tale 18, *Smørbuk* — printed pp. 133–134
- Tale 21, *Buskebruden* ("The Bushy Bride") — printed pp. 155–156
- Tale 24, *Det blaa Baandet* ("The Blue Belt/Ribbon") — printed pp. 175–176
- Tale 26, *Han Far sjøl i Stua* ("Father Bruin Himself in the Room") — printed pp. 199–200

**Vision-reading guard — marginalia found and excluded.** The title page (PDF p. 5) carries a
handwritten pencil library call-number stack in the top margin ("839.88 / A8 nnrs / 1904 / V.2")
and a handwritten cursive gloss ("Peter Christen...") written above the printed abbreviated
byline "P. CHR. ASBJØRNSEN" — almost certainly a prior owner/librarian spelling out the author's
abbreviated first names. Both are clearly handwritten (inconsistent stroke width, pencil/ink
texture, sit in margins/over printed text) and are **excluded entirely** from extraction; they are
not book content. No other marginalia was observed on any sampled page — all other sampled pages
are clean, consistently typeset print.

**Attested Era (book-level, coarse — see `00_Historical_and_Geographic_Context_Guide.md`):** the
tales themselves are 19th-century Norwegian oral folk material collected and first published by
Asbjørnsen & Moe beginning in the 1840s; **this specific printing is the 7th edition (1904),
revised by Moltke Moe** (P. Chr. Asbjørnsen's and Jørgen Moe's son's generation of editorial
revision). Entries below use `19th c. (oral tradition); this edition 1904` to flag both the
material's origin and the edition actually read. No per-word dating finer than this is supported
by the source.

**Attested Region:** the main narrative text carries no explicit dialect-letter tags or regional
annotation (unlike some comparative grammar sources this project has extracted) — Asbjørnsen &
Moe's editorial practice was to normalize tale language into a literary written Norwegian while
preserving oral-formulaic *style*, not to mark provenance per-tale in this edition. `Attested
Region` is therefore `—` throughout and `Geographic Scope` defaults to `national` per the spec's
column-rules guidance.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Bergmand(en) | mountain-troll, mountain-man (a cave/mountain-dwelling supernatural being) | noun (compound: Berg "mountain" + Mand "man") | literary | — | 19th c. (oral tradition); this edition 1904 | — | national | literary | n/a | verified | Tale 1, p.2. Addresses his captive as "Vil du være Kjæresten min?" ("Will you be my sweetheart?") — the courtship line is played as menacing, not romantic. |
| Hønen tripper i Berget! | "The hen trips/patters in the mountain!" | formulaic phrase (sung/called refrain) | literary | — | 19th c. (oral tradition); this edition 1904 | — | national | literary | verified | verified | Tale 1, p.2–3, repeated near-verbatim by each sister's hen as a magical giveaway cue — classic folk-narrative repetition-with-escalation device. |
| Hvælving | vault, cavern (an underground chamber) | noun | archaic | — | 19th c. (oral tradition); this edition 1904 | — | national | literary | n/a | verified | Tale 1, p.2. Standard modern Norwegian would more likely use "hvelv". |
| Bukken Bruse | "Billy-goat Bruse" — the three goats' shared surname/epithet in the tale | proper-name epithet | literary | — | 19th c. (oral tradition); this edition 1904 | — | national | literary | n/a | verified | Tale 6, p.46–47. "Bruse" independently suggests bristling/blustering; functions as a stock character name, internationally known via "The Three Billy Goats Gruff." |
| tripper / trippe | to patter, trip lightly (light hoofbeats on a bridge) | verb | literary | — | 19th c. (oral tradition); this edition 1904 | — | national | literary | n/a | verified | Tale 6, p.46. Troll's challenge "Hvem er det som tripper paa min Bro?" escalates to "tramper" for the heaviest goat — a deliberate lexical register ladder keyed to size/weight. |
| tramper / trampe | to tramp, stomp heavily | verb | literary | — | 19th c. (oral tradition); this edition 1904 | — | national | literary | n/a | verified | Tale 6, p.47. Paired/contrasted with "tripper" — see above; the escalation is the point, not either verb alone. |
| fin i Maalet | "fine/refined in speech," i.e. smooth-talking, well-spoken (used of the smallest goat's confident lie) | idiom (adjective phrase) | colloquial | — | 19th c. (oral tradition); this edition 1904 | — | national | literary | n/a | verified | Tale 6, p.46: "sagde Bukken, den var saa fin i Maalet" — narrator's aside noting the goat's persuasive tone, not literally about pronunciation. |
| fælt grov i Maalet | "terribly coarse/rough in speech" | idiom (adjective phrase) | colloquial | — | 19th c. (oral tradition); this edition 1904 | — | national | literary | n/a | verified | Tale 6, p.47, of the largest goat — a direct register-contrast pair with "fin i Maalet" above; "Maalet" = "the speech/manner of speaking," not literal mouth size. |
| Snip, Snap, Snude, her er det Eventyr ude | stock closing formula, roughly "Snip, snap, snout, this tale is out" | formulaic phrase | literary | — | 19th c. (oral tradition); this edition 1904 | — | national | literary | n/a | verified | Tale 6, p.48. One of the Asbjørnsen/Moe tradition's best-known fixed closing tags — noted briefly, not dwelt on, since it recurs across the whole collection (vol. I included). |
| Hvidbjørn(en) | the White Bear (polar bear as a transformed-prince figure) | noun (compound: Hvid "white" + Bjørn "bear") | literary | — | 19th c. (oral tradition); this edition 1904 | — | national | literary | n/a | verified | Tale 7, p.48–49. |
| Ragg / Ragget | shaggy coat, pelt/fur (of an animal) | noun | archaic | — | 19th c. (oral tradition); this edition 1904 | — | national | literary | n/a | verified | Tale 7, p.49: "hold dig bare godt fast i Ragget mit" ("just hold on tight to my fur"). Not the ordinary modern word for fur/coat (that would be "pels"); reads as an older/more rustic term. |
| Husmand | cottager, crofter — a landless tenant farmer renting a small plot, the lowest rung of the old rural social hierarchy | noun | archaic | — | 19th c. (oral tradition); this edition 1904 | — | national | literary | n/a | verified | Tale 7, p.48, opening line: "Der var engang en fattig Husmand" — a real socio-historical class term, not just a generic "poor man," signaling a specific pre-industrial Norwegian rural stratum. |
| Risegaard / Risen | the giant's farmstead / the giant (as a distinct folklore being from "Trold") | noun | literary | — | 19th c. (oral tradition); this edition 1904 | — | national | literary | n/a | verified | Tale 12, p.80. Asbjørnsen & Moe's tales keep "Rise" (giant) and "Trold" (troll) as distinct supernatural categories even though both are often translated "ogre"/"troll" in English. |
| snil Husbond | "a kind master" | idiom (ironic understatement) | literary | — | 19th c. (oral tradition); this edition 1904 | — | national | literary | n/a | verified | Tale 12, p.80: the giant describes himself this way immediately before threatening to kill the hero for disobedience — deliberate dramatic-irony register. |
| gjør du det, tager jeg Livet af dig | "if you do that, I'll take your life" | formulaic threat phrase | literary | — | 19th c. (oral tradition); this edition 1904 | — | national | literary | n/a | verified | Tale 12, p.80. A recurring stock threat-formula shape in these tales (compare Smørbuk's troll, Han Far's Kjærring below) — a found pattern worth flagging as a register marker of "supernatural antagonist speech" across the volume. |
| en gild om Truten | roughly "a fine one across the snout/mouth" (a blow to the face) | idiom (noun phrase) | colloquial | — | 19th c. (oral tradition); this edition 1904 | — | national | literary | n/a | plausible_unverified | Tale 12, p.80–81 context (Gutten's boast about what he'd get for tasting the giants' soup). "Trut" = mouth/snout, informal/animal-register word for a human mouth — reads as deliberately crude. |
| Værre og værre! / Ære være! | "Worse and worse!" vs. "Honor be [to it]!" — a mishearing-based pun | wordplay (idiom pair) | colloquial | — | 19th c. (oral tradition); this edition 1904 | — | national | literary | n/a | verified | Tale 12, p.81. The old woman mishears/misspeaks the correct ceremonial phrase "Ære være" (honor be) as "Værre og værre" (worse and worse) when the giant's kettle turns out to hold gold — an explicit in-text folk-etymology/malapropism joke, genuinely interesting for mechanics of comic wordplay. |
| Askeladd(en) | "the Ashlad" — stock epithet for a story's youngest-son hero, literally "one who pokes/sits in the ashes" | proper-name epithet | literary | — | 19th c. (oral tradition); this edition 1904 | — | national | literary | n/a | verified | Tale 15, p.110 (also tale 18's Guldæblet scene uses "Askeladden"). The single most recognizable stock character name in the whole Asbjørnsen/Moe corpus — noted briefly since it recurs heavily across both volumes. |
| Sveltihjel | to starve to death | verb (compound: Svelte "starve" + ihjel "to death") | archaic | — | 19th c. (oral tradition); this edition 1904 | — | national | literary | n/a | verified | Tale 15, p.110: "hjemme hos ham blev det ikke andet end Sveltihjel for dem" ("at home with him there was nothing but starving to death"). Compound verb-plus-adverb fusion pattern ("-ihjel" = "to death," cf. modern "slaa ihjel" = "beat to death") still productive in Norwegian but this specific compound reads as older/literary now. |
| Jonsok-Leg | a Midsummer's-Eve game | noun phrase | regional | — | 19th c. (oral tradition); this edition 1904 | — | national | literary | n/a | plausible_unverified | Tale 15, p.110. "Jonsok" = St. John's Eve/Midsummer (24 June), a named folk-calendar feast day; "Leg" = game/play. Calendar-rooted cultural vocabulary, not transparent without that context. |
| Tro / Utro | "Faithful" / "Unfaithful" used as the two brothers' proper names | proper-name allegory (adjectives used as names) | literary | — | 19th c. (oral tradition); this edition 1904 | — | national | literary | n/a | verified | Tale 15, p.110 context (preceding tale fragment visible on the same page spread, "Tro og Utro"). Character naming directly encodes moral role — common device across the collection. |
| Smørbuk | "Butter-belly" — nickname for a fat, food-loving boy | proper-name epithet (compound: Smør "butter" + buk "belly/paunch") | literary | — | 19th c. (oral tradition); this edition 1904 | — | national | literary | n/a | verified | Tale 18, p.133: "han var saa tyk og fed... og derfor kaldte hun ham Smørbuk." Note: "buk" (belly, single k) is a different lexeme from "Bukk" (billy-goat, double k) in Bukken Bruse above — a near-homophone coincidence across two unrelated tales/words worth flagging for a conlang-slang angle (nickname formation via body/appetite trait + mocking-affectionate compound). |
| Haugkjærring | "mound-wife" — a troll-woman living in a burial mound/hillock | noun (compound: Haug "mound, barrow" + Kjærring "old woman, wife") | literary | — | 19th c. (oral tradition); this edition 1904 | — | national | literary | n/a | verified | Tale 18, p.134. A distinct supernatural-being category from "Bergmand"/"Trold"/"Rise" above — Norwegian folklore keeps several named troll/hag subtypes tied to specific terrain features (mound vs. mountain vs. generic). |
| Gud signe! | "God bless [you]!" | greeting/blessing formula | formal | — | 19th c. (oral tradition); this edition 1904 | — | national | literary | n/a | verified | Tale 18, p.134, exchanged as a doorway greeting between the mother and the disguised troll — formulaic politeness register used even toward a (suspected) supernatural visitor. |
| Pip, pip, her er jeg! | "Peep, peep, here I am!" | formulaic taunt/hide-and-seek phrase | colloquial | — | 19th c. (oral tradition); this edition 1904 | — | national | literary | n/a | verified | Tale 18, p.134, Smørbuk's cheeky reply from his hiding place under the baking-trough — playful, child-register formula embedded in an otherwise tense scene. |
| Vondord | harsh words, ill-natured scolding | noun (compound: Vond "bad, evil, angry" + Ord "word") | colloquial | — | 19th c. (oral tradition); this edition 1904 | — | national | literary | n/a | plausible_unverified | Tale 21, p.155 context ("skjældte og smældte" surrounding text describes the stepmother/stepsister's treatment of the heroine) — a compact compound for sustained verbal abuse. |
| ikke en Times Fred | "not an hour's peace" | idiom | colloquial | — | 19th c. (oral tradition); this edition 1904 | — | national | literary | n/a | verified | Tale 21, p.155: "aldrig havde hun en Times Fred" — a still-transparent, still-natural-sounding Norwegian idiom for constant harassment. |
| der drysser Guld af Haaret | "gold drizzles/sprinkles from the hair" | idiom (magical-token formula) | literary | — | 19th c. (oral tradition); this edition 1904 | — | national | literary | n/a | verified | Tale 21, p.156, one of three enchanted talking heads' predictions of reward for the kind heroine (gold from hair, from a comb's brushing, from the mouth when she speaks) — a triadic reward-formula structure typical of the genre. |
| Fanteri | vagrancy, roguish/thievish behavior; also "a disreputable act" | noun | archaic | — | 19th c. (oral tradition); this edition 1904 | — | national | literary | n/a | plausible_unverified | Tale 24, p.175: mother warns against taking a found blue ribbon, "der kan være Fanteri ved det" ("there could be trickery/ill-luck in it"). Derived from "Fante," historically a term for itinerant/traveling people (including Romani/Tater communities) in Norway and carrying real ethnic-slur baggage in that sense — flagged here because the word's root is historically loaded even though this specific token means "roguery/trickery" in context, not the ethnonym itself. |
| Hosebaand | garter, stocking-band | noun (compound: Hose "stocking" + Baand "band, ribbon") | archaic | — | 19th c. (oral tradition); this edition 1904 | — | national | literary | n/a | verified | Tale 24, p.175. The magical object of the tale's title ("Det blaa Baandet") is specifically this kind of band, not a generic ribbon. |
| Bergtrold | mountain-troll | noun (compound: Berg "mountain" + Trold "troll") | literary | — | 19th c. (oral tradition); this edition 1904 | — | national | literary | n/a | verified | Tale 24, p.176. A near-synonym compound of "Bergmand" (tale 1 above) — the collection uses both "Bergmand" and "Bergtrold" for the same mountain-dwelling-being concept, not fully interchangeably but overlapping. |
| Tiggersæk(ken) | beggar's sack | noun (compound: Tigger "beggar" + Sæk "sack") | archaic | — | 19th c. (oral tradition); this edition 1904 | — | national | literary | n/a | verified | Tale 24, p.176. Concrete prop-vocabulary tied to the itinerant-beggar social role referenced via "Fanteri" above. |
| Mikkel | stock proper-name epithet for the fox (the fox is never just called "Ræv" in dialogue — he's addressed as "Mikkel") | proper-name epithet | literary | — | 19th c. (oral tradition); this edition 1904 | — | national | literary | n/a | verified | Tale 26, p.200: "Er du kommen i Fælden nu, Mikkel?" The Reynard-the-Fox-equivalent stock name in Norwegian folk tradition. |
| Bamse | stock affectionate/epithet name for the bear | proper-name epithet | literary | — | 19th c. (oral tradition); this edition 1904 | — | national | literary | n/a | verified | Tale 26, p.200: "Eia mei da, Bamse!" This exact word survives into everyday Modern Norwegian as the generic word for "teddy bear," a direct lexical throughline from this 19th-century folk-tale epithet to current child-register vocabulary — a strong candidate for cross-era semantic-drift analysis. |
| Graatass / Graaben | "gray-foot" / "gray-leg" — stock epithet for the wolf | proper-name epithet (compound: Graa "gray" + Tass/Ben "paw/foot" / "leg") | literary | — | 19th c. (oral tradition); this edition 1904 | — | national | literary | n/a | verified | Tale 26, p.199–200, both forms used for the same wolf character within a few lines of each other ("til Pas til dig, din Hønsetjuv! — Du og, Graatass?" ... "har du revet Gjed og Sau... din Graaben?"). Variation between the two forms in close proximity suggests they function as interchangeable epithets rather than fixed single name, unlike "Mikkel"/"Bamse" above. |
| Fantekjærring | vagrant/tinker old-woman | noun (compound: Fante + Kjærring) | archaic | — | 19th c. (oral tradition); this edition 1904 | — | national | literary | n/a | verified | Tale 26, p.200, describing the old woman who owns the sheep/hens being menaced by the animals. Same historically-loaded "Fante" root as "Fanteri" above — flagged for the same reason; here it is a descriptor of the character's itinerant social status, not obviously derogatory in context but carries the same real-world baggage. |
| Hønsetjuv | hen-thief | noun (compound: Høne "hen" + Tjuv "thief") | colloquial | — | 19th c. (oral tradition); this edition 1904 | — | national | literary | n/a | verified | Tale 26, p.200, insult hurled at the fox — a transparent, still-natural-sounding compound-insult pattern (trait/crime + "-tyv/-tjuv"). |
| din Mærraflaaer | "you mare-flayer!" (an insult accusing the wolf of skinning horses) | insult (noun phrase, compound: Mærra "mare" + Flaaer "flayer, skinner") | taboo | — | 19th c. (oral tradition); this edition 1904 | — | national | literary | n/a | verified | Tale 26, p.200, the old woman's tirade at the bear/wolf. A vivid archaic trade-vocabulary-based insult (flaying/skinning as a real rural occupation) repurposed as abuse — good candidate evidence for a `technical_leak`-style derivation mechanism (trade jargon → insult). |
| Svirerove | roughly "carousing tail" / wastrel, idler (an insult) | insult (noun, likely compound: Svir(e) "carouse, revel" + Rove "tail") | taboo | — | 19th c. (oral tradition); this edition 1904 | — | national | literary | n/a | low_confidence | Tale 26, p.200: "din Sviverove!" (note: text shows "Sviverove," possibly a period spelling variant of "svirerove" — flagged low_confidence on the exact modern-equivalent segmentation, though the word and its insult function are clearly legible in print). |
| pint og peiset dau | "tortured and beaten dead" | idiom (alliterative verb doublet) | colloquial | — | 19th c. (oral tradition); this edition 1904 | — | national | literary | n/a | verified | Tale 26, p.200: "saa blir du nu pint og peiset dau" — a stock alliterative threat-doublet (compare English "beaten black and blue"); "dau" is a dialect-flavored form of "død" (dead). |
| bardus ned | "bang/thud down" — a sudden, heavy, uncontrolled fall | idiom (sound-symbolic adverbial phrase) | colloquial | — | 19th c. (oral tradition); this edition 1904 | — | national | literary | n/a | verified | Tale 26, p.199–200, repeated three times verbatim ("gjorde han et Hop — bardus ned i Ulvestuen") as each animal falls into the pit trap — a deliberate onomatopoeic refrain parallel to tale 6's "tripper"/"tramper" escalation device. |

## Grammar points

Not applicable — per dispatch, this file is a literature/usage-corpus vocabulary sample, not a
grammar-reference extraction. Norwegian grammar is already systematically covered in files
001–017.

## Cross-cutting observations

- **Stock creature/character epithets form a dense, internally consistent naming system**:
  Mikkel (fox), Bamse (bear), Graatass/Graaben (wolf), Askeladden (youngest-son hero),
  Bukken Bruse (goats) — each is a fixed proper-name-like tag rather than a plain species noun,
  and dialogue consistently addresses characters by epithet rather than by common noun. This is
  the single most "synthesizable" pattern found in this sample: a productive naming convention
  (trait/color/behavior + stock suffix) that a conlang slang layer could repurpose for
  in-universe creature or character nicknaming.
- **A repeated formula shape recurs across at least three sampled tales**: "gjør du det, tager
  jeg Livet af dig" (tale 12), the troll's challenge-and-escalation pattern in tale 6, and the
  triadic "bardus ned" refrain in tale 26 — oral-formulaic repetition-with-variation is a real,
  observable register marker of these tales' antagonist/narrator speech, not just a stylistic
  one-off.
- **The "Fante-" root (Fanteri, Fantekjærring)** is flagged twice above as historically loaded —
  it derives from a real, still-sensitive Norwegian term for itinerant/Traveller (Romani-adjacent
  "Tater"/"Fant") communities, subject to serious historical persecution. In-context here it
  reads as period-ordinary vocabulary for "vagrant/roguish," but any downstream synthesis work
  drawing on this root should carry that real-world baggage forward deliberately, not drop it.
- **Dialect-flavored spelling is present but sparse in this edition**: "dau" for "død" (dead,
  tale 26) is the clearest example in the sampled pages. The 1904 revised edition reads as
  edited literary Norwegian overall (per Moltke Moe's stated revision), not a heavily
  dialect-preserving transcription — consistent with the front matter's description of this as a
  "Fællessamling" (combined/standardized edition) rather than a raw-dialect collection.
- **Recurring whole-tradition formulae** ("Der var engang..." opening; "Snip, Snap, Snude, her
  er det Eventyr ude" closing) were observed and are noted above but intentionally not analyzed
  in depth, per dispatch — they're shared across the whole Asbjørnsen/Moe corpus including
  Volume I (file 018), not distinctive to this volume.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — no bulk reproduction of dialogue blocks or
narrative prose. All illustrative quotes above are single sentences or short phrases cited for
their lexical/idiomatic value, not continuous passages.
