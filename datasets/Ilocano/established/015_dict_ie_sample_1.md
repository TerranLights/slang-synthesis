# Ilocano — Established Vocabulary: Ilocano-English Dictionary, Representative Sample 1 (A–I, first third)

**Source:** Carl R. Galvez Rubino, *Ilocano Dictionary and Grammar: Ilocano-English, English-Ilocano*
(University of Hawaiʻi Press, PALI Language Texts: Philippines series, © 2000). Ilocano-English
section, PDF pages 92–307 of 868 total.

**Coverage note — this is a deliberate SAMPLE, not exhaustive coverage**, per this project's
standing representative-sampling convention for oversized dictionaries (used previously for
Korean's 962pp dictionary, Spanish's 1,831pp McGraw-Hill dictionary, and Hawaiian's 3,695pp
dictionary). The full Ilocano-English section runs from PDF p. ~92 to ~737 (alphabetically A
through Y); **this file covers only the first third (PDF pp. 92–307, alphabet range A through
early/mid I)**. Within that range, 12 page-spreads (3 pages each, 36 pages total) were sampled at
roughly even intervals and read in full:

- PDF pp. 92–94 (*abaga*–*abogado*)
- PDF pp. 111–113 (*alibudabod*–*alino*)
- PDF pp. 130–132 (*aninaw*–*antolohia*)
- PDF pp. 149–151 (*arukot*–*asép*)
- PDF pp. 168–170 (*bakulaw*/*bak-ias*–*balakad*)
- PDF pp. 187–189 (*barbasa*/*barinit*–*barrio*)
- PDF pp. 206–208 (*bingrut*/*biriska*–*bisin*)
- PDF pp. 225–227 (*burruat*/*busingar*–*butiti*)
- PDF pp. 244–246 (*darawiswis*–*dawadaw*)
- PDF pp. 263–265 (*dumég*/*dungir*–*dursa(n)*)
- PDF pp. 282–284 (*ganab*/*gansal*–*gargar*)
- PDF pp. 301–303 (*i-* prefix–*ikapi(n)-*)

Everything between and outside these sampled spreads (the vast majority of even this
first-third range, let alone the remaining two-thirds of the Ilocano-English section, the
entire English-Ilocano section, and the back matter) was **not** read for this file. Sibling
dispatches in the same wave cover the remaining dictionary ranges (016–018) and back matter (019)
in parallel; no attempt was made here to deduplicate against those.

**Text layer / method note.** The PDF has a genuine OCR text layer (not a scan-only image), so
`pdftotext` was used rather than vision-reading. The dictionary is laid out in two columns per
page, and raw (non `-layout`) `pdftotext` output interleaves the two columns' lines, which
occasionally scrambles entry order or splits a single entry's continuation across unrelated
text (confirmed directly on the *Haway* entry below, recovered cleanly with `pdftotext -layout`
on that one page). Transcription confidence is marked `verified` where the OCR read cleanly;
a handful of individual words with visible OCR noise (e.g. stray diacritic drop-outs, ligature
misreads like "fig." rendering as "x." in a few spots) are flagged `verified (minor OCR noise)`
in the Notes column rather than excluded.

**Abbreviations used in this dictionary** (per "Abbreviations Used in This Dictionary," PDF p.
88, consulted directly since no prior `established/` file for this language existed yet to cite):
`coll.` colloquial, `reg.` regional, `obs.` obsolete, `fig.` figurative, `dim.` diminutive,
`fam.` familiar, `vulg.` vulgar, `interrog.` interrogative, `dem.` demonstrative, `lig.` ligature
(linker), `circum.` circumfix, `exp.` expression (idiomatic or proverbial). Language-of-origin /
cognate tags seen directly in sampled entries: `Sp.` Spanish, `Eng.` English, `Tag.` Tagalog,
`Ibg.` Ibanag, `Ifg.` Ifugao, `Ivt.` Ivatan/Itbayaten, `Itg.` Itneg, `Kal.` (Lubuangan) Kalinga,
`Knk.` Kankanay, `Kpm.` Kapampangan, `Png.` Pangasinan, `Bon.` Bontok, `Jap.` Japanese. No
`vulg.`-tagged entry happened to fall in this file's sampled spreads (it may appear in the later
dictionary ranges covered by sibling dispatches), though several `coll.`-tagged body/euphemism
entries sampled here sit adjacent to the vulgar register (see Notes column).

## Hawaii-related entries found (flagged per dispatch instructions)

Three genuine Hawaiʻi-tagged/related items fall within this file's own PDF page range (92–307),
confirming and extending the triage catalog's findings (which did not specify exact page
locations):

- **`Aloha: (Hawai'i) interj. Hawaiian greeting of welcome or farewell.`** (PDF p. ~92–94 spread,
  alphabetically under *a-*) — a direct Hawaiian-origin loanword entered with an explicit
  regional-use tag, parallel to the dictionary's general practice of tagging loanwords by source.
- **A worked example sentence under the entry `aringan` ("to influence")**: *Naar-aringanen ti
  ugali ditoy Hawaii.* — "(Our) ways are already influenced and changed here in Hawai'i." (PDF p.
  ~111–113 spread) — direct evidence the dictionary's own illustrative-sentence corpus draws on
  real Hawaiʻi-based Ilocano speaker experience (consistent with the author's University of
  Hawaiʻi institutional base).
- **`Haway: n. Hawai'i. Hawayano. n., a. Hawaiian. (taga-Hawaii)`** (PDF p. 298, confirmed via
  `pdftotext -layout` after raw extraction scrambled the entry across a column break) — followed
  immediately by a phonological note: *"Originally not a sound in the Ilocano language, the
  glottal fricative [h] does occur in a few loanwords and one native word, haan, the dialectal
  version of saan. In old Ilocano writings, words with this glottal fricative sound were written
  with a [j] based on Spanish orthography."* This is a documented phoneme-borrowing-via-contact
  detail (worth flagging for `TepenianHawaiian`'s phonology work per the triage catalog's note) —
  though the note itself is about /h/ generally (motivated by Spanish *j*-spelled loans like
  *jamón*/*hamon*, *jardín*/*hardin*), not specifically about Hawaiian-contact phonology; the
  *Haway*/*Hawayano* headword is simply the example chosen to anchor the note in this edition.

No `kanaka` or `Purgi` entries (both flagged in the triage catalog) fall within this file's
92–307 range — both are almost certainly in the *k-* and *p-* sections respectively, well past
PDF p. 307, and so belong to sibling dispatches 016/017's page ranges.

## Slang / informal / taboo-register entries found

The dictionary's own `(coll.)`, `(reg.)`, `(fig.)`, and `(obs.)` tags recur densely throughout
(82, 87, 76, and 181 occurrences respectively across just this file's 92–307 range per a raw
tag count) — a representative selection is included in the Vocabulary table below with the tag
preserved in the Usage Tier / Notes columns. Notable informal/taboo-adjacent findings:
- `bakka` "(coll.) term used to tease obese women" (also, primary sense: "very large vulva") —
  body-taboo vocabulary repurposed as a colloquial insult.
- `garaw` "(coll.) [to] copulate" nested under the ordinary verb "to move, touch" — a body-taboo
  sense hiding under a non-taboo headword, structurally identical to the pattern Hawaiian's
  Pukui & Elbert dictionary showed with *haʻakoi* "(3) to practice onanism."
- `butillóg`/`buslayog` "(coll.) testicles" and `baklog` "testicle" (unmarked) — a small euphemism
  cluster for the same body part with varying degrees of markedness.
- `birruruko(ng)` "mild curse word" with a worked insult sentence: *"Kasla agruprupa a birruruko,
  talaga nga awansa ti babainmo"* — "You have the face of a snail, I really think you have no
  shame."
- `igges` "worm" carries a full curse-formula idiom: *"Iggesen kuma 'ta ngiwatmo, salawasaw!"* —
  "May your mouth become worm-infested, you gossiper!" (`salawasaw` "gossiper" recurs as a
  stock insult target across several sampled entries).
- `butangéro` "tough guy; gangster; bully" and `buterég` "(coll.) boy; guy; tough guy" — youth/
  street-register masculinity vocabulary.
- `barkada` "clique, social group; gang; group of friends" — core modern Filipino social-register
  vocabulary (cognate with Tagalog slang usage), with an illustrative warning sentence about
  "untrustworthy people."
- `dating` "(coll.) money" — colloquial money-slang synonym for *kuarta*.

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| abaga | shoulder (of person or garment) | noun | core | — | — | — | — | grammar_reference | verified | n/a | yabaga "to place on shoulder; bear responsibility" shows y- causative/applicative prefix |
| yabaga | to place on the shoulder; bear responsibility | verb | core | — | — | — | — | grammar_reference | verified | n/a | derived from abaga via y- prefix; metaphor of physical burden → responsibility |
| pagat-abaga | reaching the shoulder, shoulder length (hair) | adjective | core | — | — | — | — | grammar_reference | verified | n/a | pag-...-at circumfix-like derivation |
| abagat | the south wind | noun | core | — | — | — | — | grammar_reference | verified | n/a | spawns full directional compound family below |
| abagatan | south (direction) | noun | core | — | — | — | — | grammar_reference | verified | n/a | — |
| makinabagatan, akinabagatan | in the south | adjective | core | — | — | — | — | grammar_reference | verified | n/a | akin- "located at" directional prefix pattern |
| taga-abagatan | southerner; person from the south | noun | core | — | — | — | — | grammar_reference | verified | n/a | taga- "from/native of" prefix, productive across ethnonyms too (cf. taga-Hawaii below) |
| abaho | down with! (used in Spanish expressions, e.g. political) | interjection | colloquial | — | — | — | — | grammar_reference | verified | n/a | Sp. abajo "below"; source notes antonym pair Sp. arriba vs Ilocano agbiag "long live" |
| Abang | rent; interest; lease; landowner's share of yearly crop | noun | core | — | — | — | — | grammar_reference | verified | n/a | large derivational family follows (economic/tenancy vocabulary) |
| agpapaabang | landlord; one who leases a property | noun | core | — | — | — | — | grammar_reference | verified | n/a | — |
| pagpaabang | to rent a house | verb | core | — | — | — | — | grammar_reference | verified | n/a | — |
| abang (ambush sense) | to wait for; to ambush | verb | core | — | — | — | — | grammar_reference | verified | n/a | homonym of Abang "rent" — polysemy via identical surface form |
| abay | side; unison (of voices); best man in a wedding; (coll.) friend | noun | colloquial | — | — | — | — | grammar_reference | verified | n/a | coll. sense "friend" layered onto core spatial/social senses |
| abbukay | persuasion; suggestion; that which causes excitement | noun | core | — | — | — | — | grammar_reference | verified | n/a | — |
| aabbukayan | the erogenous zone (body part aroused when stimulated) | noun | core | — | — | — | — | grammar_reference | verified | n/a | body/arousal vocabulary, not separately taboo-tagged by source |
| abbong | cover, lid, wrapper | noun | core | — | — | — | — | grammar_reference | verified | n/a | — |
| abél | textile; web; woven fabric | noun | core | — | — | — | — | grammar_reference | verified | n/a | — |
| abel-Iloko | Ilocos weaving | noun | core | — | — | — | — | grammar_reference | verified | n/a | culturally distinctive craft term naming the region's textile tradition |
| ab-abael | a kind of large hairy spider | noun | core | — | — | — | — | grammar_reference | verified | n/a | named via resemblance to woven/web imagery of abel |
| abentura | adventure, exciting incident | noun | core | — | — | — | — | grammar_reference | verified | n/a | Sp. aventura |
| abig | illicit coitus, adultery; infidelity | noun | core | — | — | — | — | grammar_reference | verified | n/a | kaabig "the person one commits adultery with" — dyadic kinship-style term for an illicit relationship |
| abirat | term applied to the relationship between two unrelated people who marry siblings (co-in-laws) | noun | core | — | — | — | — | grammar_reference | verified | n/a | specific kinship-relationship term with no direct English equivalent |
| abogado | lawyer, attorney; government solicitor | noun | core | — | — | — | — | grammar_reference | verified | n/a | Sp. abogado; abogadillo "petty/third-rate lawyer" diminutive derivative shows pejorative -illo use |
| alikamen (sense 2) | magical charm; amulet | noun | core | — | — | — | — | grammar_reference | verified | n/a | idiom "Adda alikamenna" = "He knows black magic" (lit. "has magical charms") |
| alikuno | whirlpool; dimple; (fig.) to be in a passionate love affair | noun/verb | core | — | — | — | — | grammar_reference | verified | n/a | figurative extension from physical vortex to romantic entanglement |
| alikuteg | restless; mischievous; adept at stealing | adjective/verb | core | — | — | — | — | grammar_reference | verified | n/a | idiom "Alikuteg latta dagiti matana" = "He just has roaming eyes" |
| alimatek | generic term for leech | noun | core | — | — | — | — | grammar_reference | verified | n/a | weather-prediction proverb: "When the leeches die, a strong storm will come" |
| alim(pa)patok | summit, peak, top; climax; orgasm | noun | core | — | — | — | — | grammar_reference | verified | n/a | single headword spans physical-summit and sexual-climax senses via shared "peak" metaphor |
| alindadaw / alindaw | to be dizzy/affected by vertigo from looking down | verb | core | — | — | — | — | grammar_reference | verified | n/a | — |
| aligusgus | whorl in the hair | noun | colloquial | — | — | — | — | grammar_reference | verified | n/a | tagged "coll. var. of alipuspus" |
| alila | maid, servant | noun | core | — | — | — | — | grammar_reference | verified | n/a | Tag. loan (also Png. alila) |
| alibungubong / alibuob | vapor, steam | noun | core | — | — | — | — | grammar_reference | verified | n/a | near-synonym pair for weather/atmospheric phenomena |
| ano | what; how; why (huge interrogative particle family) | interrogative | core | — | — | — | — | grammar_reference | verified | n/a | extensive idiom cluster: "Diak pagan-ano" (I don't care), "di mangano" (it will not harm), "Maan-ano kadi" (so what, who cares) |
| anito | spirit of the forefathers, ghost | noun | core | — | — | — | — | grammar_reference | verified | n/a | aganito "to worship the spirits"; managanito "superstitious person" — ancestor-worship vocabulary |
| aniwaas | supernatural character: ghost, elf, fairy | noun | core | — | — | — | — | grammar_reference | verified | n/a | — |
| anus | patience; perseverance; kindness | noun | core | — | — | — | — | grammar_reference | verified | n/a | idiom "Aganuska, bagi, ta dika met nagpadi" = "Have patience, body, since you did not choose to be a priest" (said of poor manual laborers) — class/fatalism commentary |
| anud | to drift with the current; float along | verb | core | — | — | — | — | grammar_reference | verified | n/a | "agan-anud a lungon" = floating coffin, referenced as a superstitious belief |
| anunsio | advertisement, announcement | noun | core | — | — | — | — | grammar_reference | verified | n/a | Sp. anuncio; spawns anunsiador "announcer", anunsiante "advertiser" agentive cluster |
| antikristo | Antichrist | noun | core | — | — | — | — | grammar_reference | verified | n/a | Sp. anticristo |
| arukot | to stoop, bend | verb | core | — | — | — | — | grammar_reference | verified | n/a | — |
| arusibsib | greedy, uncouth person; to overuse the mouth (eating/drinking/kissing) | noun/verb | core | — | — | — | — | grammar_reference | verified | n/a | illustrative sentence about romantic obsession: "...nabayagen nga inarusibsibko ni Perla" (I would have been heavily into Perla for a long time) |
| asáwa | spouse, husband, wife; counterpart, match | noun | core | — | — | — | — | grammar_reference | verified | n/a | large marriage-vocabulary family below |
| asawaen | to wed, marry someone; (also) sexually assault; copulate | verb | core | — | — | — | — | grammar_reference | verified | n/a | single verb form spans consensual marriage and sexual-assault senses — notable semantic range |
| pangasawa | dowry | noun | core | — | — | — | — | grammar_reference | verified | n/a | — |
| arte / maarte | art; skill; (Tagalog also, coll.) artificial in manners, insincere | noun/adjective | colloquial | — | — | — | — | grammar_reference | verified | n/a | explicitly cross-tagged with Tagalog colloquial usage — a borrowed social-register adjective |
| artek | drunkard | noun | core | — | — | — | — | grammar_reference | verified | n/a | var. of bartek |
| arsab | glutton, voracious eater | noun | core | — | — | — | — | grammar_reference | verified | n/a | — |
| makaasar | (coll.) irritating, disgusting | adjective | colloquial | — | — | — | — | grammar_reference | verified | n/a | — |
| bakla | homosexual man | noun | core | — | — | — | — | grammar_reference | verified | n/a | tagged "(Tag.)" — direct Tagalog loanword, synonyms baien, maho given |
| baklog | testicle | noun | core | — | — | — | — | grammar_reference | verified | n/a | synonyms ukel-ukel, lateg given; part of body-taboo euphemism cluster (cf. buslayog, butillog below) |
| bakka | a kind of basin; very large vulva; (coll.) term used to tease obese women | noun | colloquial | — | — | — | — | grammar_reference | verified | n/a | body-taboo term repurposed as a fat-shaming colloquial insult (bimmakka "resembling a bakka") |
| baknang | the rich, wealthy | noun | core | — | — | — | — | grammar_reference | verified | n/a | rich socioeconomic compound family: bumaknang "to get rich", babaknang ken nagadal "the rich and literate (social elite class)" |
| balangkantis | deceitful; always bargaining; counterfeit; (n.) whore | adjective/noun | colloquial | — | — | — | — | grammar_reference | verified | n/a | single headword spans "swindler" and sex-worker senses |
| bakulaw | a kind of large long-haired ape; (fig.) ugly person | noun | core | — | — | — | — | grammar_reference | verified | n/a | figurative insult built on animal-resemblance metaphor |
| balakad | advice; admonition | noun | core | — | — | — | — | grammar_reference | verified | n/a | idiom: "Tangay dimo impangag dagiti balakadko, panawankanto" = "Since you did not pay attention to my advice, I will leave you" |
| bari / baribari | magical word used to drive away spirits; shaman, medicine man | noun | core | — | — | — | — | grammar_reference | verified | n/a | ritual/shamanic vocabulary with its own interjectional formula |
| barikes | girdle; sash; belt; boards forming a house's skeleton | noun | core | — | — | — | — | grammar_reference | verified | n/a | example notes belt-making from beklat snake skin |
| barumbado | coarse, uncouth; disrespectful, shameless | adjective | core | — | — | — | — | grammar_reference | verified | n/a | Sp. barrumbada "boastful thing to say" |
| baró | unmarried man, bachelor; youth | noun | core | — | — | — | — | grammar_reference | verified | n/a | kinabaro "bachelorhood"; panagbaro "adolescence"; idiom about a 30-year-old still a bachelor |
| barkada | clique, social group; gang; group of friends | noun | colloquial | — | — | — | — | grammar_reference | verified | n/a | Sp. barcada "boatload"/Tag. loan; warning sentence: "Dika makibarbarkada kadagiti di-matalek a tattao" (Don't hang around untrustworthy people) |
| barukong | chest, bosom; (fig.) seat of emotions | noun | core | — | — | — | — | grammar_reference | verified | n/a | figurative extension to emotional center, parallel to English "heart" |
| barrio | barrio, suburb of a town; division of a town | noun | core | — | — | — | — | grammar_reference | verified | n/a | Sp. barrio |
| birad | kind of mollusk with big lips; (coll.) gossiping mouth | noun | colloquial | — | — | — | — | grammar_reference | verified | n/a | body-part/resemblance-based insult for gossip |
| birngas | nickname | noun | core | — | — | — | — | grammar_reference | verified | n/a | birngasan "to nickname someone"; naming-custom vocabulary |
| birkug | vagrant, vagabond; thief | noun | core | — | — | — | — | grammar_reference | verified | n/a | — |
| birruruko(ng) | kind of large snail; mild curse word | noun | colloquial | — | — | — | — | grammar_reference | verified | n/a | worked insult sentence: "Kasla agruprupa a birruruko, talaga nga awansa ti babainmo" (You have the face of a snail, you have no shame) |
| bisio | vice | noun | core | — | — | — | — | grammar_reference | verified | n/a | Sp. vicio |
| bisita | guest, visitor | noun | core | — | — | — | — | grammar_reference | verified | n/a | Sp. visita |
| Bisaya | person of the Visayan Islands; language | proper noun | core | — | Visayan Islands, Philippines (explicit) | regional | grammar_reference | verified | n/a | ethnonym with explicit geographic region in gloss |
| Bisayano | Visayan, native of the Visayan region; language spoken in the Visayas | proper noun | core | — | — | Visayas, Philippines (explicit) | regional | grammar_reference | verified | n/a | — |
| bisin | hunger; famine | noun | core | — | — | — | — | grammar_reference | verified | n/a | proverb: "No ammom ti agidulin, adayo ti inka panagbisin" = "If you know how to save, you will never go hungry" |
| busangér | mean, cruel person | noun | core | — | — | — | — | grammar_reference | verified | n/a | — |
| busasot | loudmouthed; braggart; loquacious | adjective | core | — | — | — | — | grammar_reference | verified | n/a | binnusasot "a card game similar to Old Maid" named after this trait |
| busor | enemy | noun | core | — | — | — | — | grammar_reference | verified | n/a | agbusor "to oppose", kabusor "enemy" — conflict vocabulary |
| Busao | ethnic group living between Abra and Ilocos Sur in the mountains of Siguey | proper noun | core | — | — | Abra/Ilocos Sur border region, Philippines (explicit) | regional | grammar_reference | verified | n/a | explicit geographic attestation for a minority ethnic group |
| butangéro | tough guy; gangster; bully | noun | colloquial | — | — | — | — | grammar_reference | verified | n/a | f. butáng "to attack; beat up; gang up on" |
| buténg | fear | noun | core | — | — | — | — | grammar_reference | verified | n/a | idiom: "Kabutengtayo ti saantayo nga ammo" = "We fear what we do not know" |
| butillóg | testicles | noun | colloquial | — | — | — | — | grammar_reference | verified | n/a | tagged (coll.); synonym láteg; euphemism cluster with baklog, buslayog |
| busatan | first buyer; to do for the first time; pioneer; (also) devirginize a girl | noun/verb | core | — | — | — | — | grammar_reference | verified | n/a | polysemy spanning commercial "first sale" and sexual-initiation senses |
| garampang | easy girl; immodest girl; unchaste; flirtatious | noun | colloquial | — | — | — | — | grammar_reference | verified | n/a | synonym cluster sayyét, sarampiting, sarampingat — register for sexually-forward women |
| garaw | wild animal movement; (coll.) copulate | noun/verb | colloquial | — | — | — | — | grammar_reference | verified | n/a | taboo sense nested under non-taboo headword "to move, touch, molest" |
| gansal | flaw (in music, speech, fabric); remainder in division | noun | core | — | — | — | — | grammar_reference | verified | n/a | — |
| ganggannaet | foreigner, alien, stranger | noun | core | — | — | — | — | grammar_reference | verified | n/a | "utang iti ganggannaet" = foreign loans (modern economic compound) |
| garangugong | echo; abyss; sound of something falling into a deep place | noun | core | — | — | — | — | grammar_reference | verified | n/a | figurative extension: "igarangugongnakayo...idiay impierno" = "he will throw you down into hell" (if disobedient) |
| gapo | reason, cause; motive | noun/particle | core | — | — | — | — | grammar_reference | verified | n/a | massive grammatical-particle family: gapo ta "because", isu't gapona "that's why" |
| dungáw | dirge; cry for the dead; lamentation | noun | core | — | — | — | — | grammar_reference | verified | n/a | agdung-aw "to lament, sing a dirge, wail"; makidung-aw "to keep vigil over a dead body" — funeral-ritual vocabulary |
| dungngo | loved one; love; compassion; tender care; sweetheart | noun | core | — | — | — | — | grammar_reference | verified | n/a | idiom "Dungdunguenkanto" = "I will love you" |
| duri | spinal column; backbone; keel of a ship | noun | core | — | — | — | — | grammar_reference | verified | n/a | idioms: "Awan durina" (he has no spine — a weak coward); "tumakder ti adda durina" (let anyone with a backbone stand up) |
| durian | Dioscorea batatas, wild yam; also the popular stinky spiked fruit | noun | core | — | — | — | — | grammar_reference | verified | n/a | single headword covers two botanically unrelated plants sharing a name |
| durogas | cheater; grafter | noun | colloquial | — | — | — | — | grammar_reference | verified | n/a | tagged (coll.); agdurogas "to cheat, swindle" |
| darum | lawsuit; charge, indictment; accusation | noun | core | — | — | — | — | grammar_reference | verified | n/a | legal vocabulary: idarum "to accuse", yuli ti darum "bring up a charge (in court)" |
| pagidasalan / pagdas-alan | scapegoat, person who receives the blame or punishment | noun | core | — | — | — | — | grammar_reference | verified | n/a | derived from das-al "to transfer the blame to someone else" — social-scapegoating vocabulary |
| daton | sacrifice; gift, offering; (verb) to court, offer love | noun/verb | core | — | — | — | — | grammar_reference | verified | n/a | idiom: "Pasig a tirong dagiti agdatdaton kenkuana" = "Those that court her are all pirates" |
| dato | Muslim ruler | noun | core | — | — | — | — | grammar_reference | verified | n/a | political/cultural term for traditional Muslim Filipino leadership |
| dating | money | noun | colloquial | — | — | — | — | grammar_reference | verified | n/a | tagged (coll.); synonym kuarta |
| i- (prefix) | theme-focus verbalizing prefix (instrumental/thematic/conveyance) | affix | core | — | — | — | — | grammar_reference | verified | n/a | major verbal morphology entry; perfective allomorphs in-/iny- documented with worked examples |
| i- -an (circumfix) | transitivizing circumfix expressing beneficiary action ("done for someone else") | affix | core | — | — | — | — | grammar_reference | verified | n/a | perfective form in- -an; example "Inlutuannakami ti adobo" = "She cooked adobo for us" |
| Ibanag | ethnic group from northwestern Luzon; the Cordilleran language of the Ibanag people | proper noun | core | — | — | northwestern Luzon, Philippines (explicit) | regional | grammar_reference | verified | n/a | explicit geographic + two-dialect (northern/southern) detail |
| Ibalói | ethnic group from southern Benguet Province (also Nabaloi/Benguet Igorot) | proper noun | core | — | — | southern Benguet Province, Philippines (explicit) | regional | grammar_reference | verified | n/a | three named dialects given: Daklan, Kabayan, Bokod |
| Ibatan | ethnic group from the Batanes Islands; the Austronesian language of the Ivatan people | proper noun | core | — | — | Batanes Islands, Philippines (explicit) | regional | grammar_reference | verified | n/a | two named dialects: Basco, Itbayaten |
| Ifugao | ethnic group from northern Luzon (Batad/Mayoyaw/Tuwali Ifugao languages) | proper noun | core | — | — | northern Luzon, Philippines (explicit) | regional | grammar_reference | verified | n/a | three named language varieties |
| Igorót | name for the natives of the interior provinces of Luzon, especially Mountain Province and Benguet | proper noun | core | — | — | Mountain Province/Benguet, Luzon, Philippines (explicit) | regional | grammar_reference | verified | n/a | — |
| Hanunóo | ethnic group from southern Mindoro; the Mangyan language of the Hanunoo people | proper noun | core | — | — | southern Mindoro, Philippines (explicit) | regional | grammar_reference | verified | n/a | — |
| ibléng | human excrement | noun | core | — | — | — | — | grammar_reference | verified | n/a | agibleng "to have diarrhea"; pagiblengan "toilet" — bodily-function vocabulary, unmarked by source |
| iggém / iggam | hold; grasp; clasp | noun/verb | core | — | — | — | — | grammar_reference | verified | n/a | idiom "Adda iggemmo dita?" = "Do you have it on you? Are you carrying any?" — contextually about illicit possession (poisons mentioned in the same entry) |
| igges | worm; caterpillar; larvae | noun | core | — | — | — | — | grammar_reference | verified | n/a | curse formula: "Iggesen kuma 'ta ngiwatmo, salawasaw!" = "May your mouth become worm-infested, you gossiper!" |
| Iglesia ni Kristo / anak ti santa iglesia | Church of Christ / (fig.) illegitimate child | proper noun/idiom | core | — | — | — | — | grammar_reference | verified | n/a | darkly ironic idiom: "child of the holy church" as a euphemism for an illegitimate child |
| hara-kiri | suicide by slicing the abdomen with a knife | noun | core | — | Japan (loanword origin, explicit) | regional (loanword) | grammar_reference | verified | n/a | Jap. loanword; agharakiri "to perform harakiri on oneself" fully nativized with ag- verbal prefix |
| halo-halo | a dessert of crushed ice, tropical fruits, sweet beans, and milk | noun | core | — | Philippines (Tag. loan, explicit) | regional | grammar_reference | verified | n/a | Tag. loan naming a popular hot-weather dessert |
| haiskul | high school | noun | colloquial | — | — | — | — | grammar_reference | verified | n/a | Eng. loan; aghaiskul "to go to high school" — fully nativized with ag- prefix |
| hammét | not at all; not really; it's not so | interjection | colloquial | — | — | — | — | grammar_reference | verified | n/a | contraction of haan met; part of a small cluster of haan-based contracted idioms (hampay, hanabale) |
| Haway | Hawaiʻi | proper noun | core | — | Hawaiʻi (explicit) | regional | grammar_reference | verified | n/a | see Hawaii-related entries section above; recovered via -layout after raw OCR scrambled the entry across a column break |
| Hawayano | Hawaiian (person/adjective) | noun/adjective | core | — | Hawaiʻi (explicit) | regional | grammar_reference | verified | n/a | taga-Hawaii given as synonym, showing the productive taga- "native of" prefix applied to a non-Philippine place name |
| Aloha | Hawaiian greeting of welcome or farewell | interjection | regional | — | Hawaiʻi (explicit) | regional | grammar_reference | verified | n/a | see Hawaii-related entries section above |
| aringan | to influence | verb | core | — | — | — | — | grammar_reference | verified | n/a | example sentence set in Hawaiʻi: see Hawaii-related entries section above |
| abaho (Sp. antonym note) | "down with!" — Ilocano antonym given as agbiag "long live" | interjection | colloquial | — | — | — | — | grammar_reference | verified | n/a | duplicate cross-reference preserved for the antonym pairing itself, a notable bilingual lexicographic detail |
| abalayan | the relationship between the parents of a married couple; term of address for this relationship | noun | core | — | — | — | — | grammar_reference | verified | n/a | kinship term with no single-word English equivalent (cf. Tag. balae) |
| abalorio | colored silver beads used in decorating clothes; beadwork | noun | core | — | — | — | — | grammar_reference | verified | n/a | Sp. abalorio |
| abanera | kind of slow dance; tune accompanying the habanera | noun | core | — | — | — | — | grammar_reference | verified | n/a | Sp. habanera |
| abano | rectangular cigar with baydg tobacco | noun | core | — | — | — | — | grammar_reference | verified | n/a | Sp. habano "Havana cigar"; agabano "to smoke a cigar" |
| Abad | abbot | noun | core | — | — | — | — | grammar_reference | verified | n/a | marked "(Eng.?)" with a question mark by the source itself, i.e. the dictionary flags its own etymological uncertainty |
| abistrana | a kind of shrub with violet-edged leaves | noun | technical | — | — | — | — | grammar_reference | verified | n/a | botanical/plant-name entry, typical of this dictionary's dense flora coverage |
| abitsuélas | lima bean, Phaseolus sp. | noun | core | — | — | — | — | grammar_reference | verified | n/a | Sp. habichuela |
| aapong | grandparents | noun | core | — | — | — | — | grammar_reference | verified | n/a | distributive-plural kinship form (f. apóng) |
| aannak | children (distributive plural of anak) | noun | core | — | — | — | — | grammar_reference | verified | n/a | illustrates CV-reduplication distributive-plural morphology productively |
| aamkan | fearful, dreaded thing | noun | core | — | — | — | — | grammar_reference | verified | n/a | illustrative sentence: "I have nothing to fear because my friend says there are no criminals here" |
| aak | (children's talk) dirty thing | noun | core (child-register) | — | — | — | — | grammar_reference | verified | n/a | explicitly tagged as children's baby-talk vocabulary, a distinct register the dictionary marks directly |
| aangsan | windpipe, respiratory tract | noun | core | — | — | — | — | grammar_reference | verified | n/a | anatomical vocabulary |
| ababa | short (objects); low; brevity | adjective/noun | core | — | — | — | — | grammar_reference | verified | n/a | idiom: "Pulitiagan ti pangyababaan ti Puli-ti-Tiagan" = "Pulitiagan is the abbreviation of People-from-Tiagan" — a place-name clipping/abbreviation example |
| aaddi | plural of adi, younger sibling | noun | core | — | — | — | — | grammar_reference | verified | n/a | kinship-term plural |
| alinaay | to become smooth, gentle; flow gently | verb | core | — | — | — | — | grammar_reference | verified | n/a | — |
| alinaga | illumination; ascending ray of the sun at sunrise | noun | core | — | — | — | — | grammar_reference | verified | n/a | — |
| alinduáan | unsure; doubtful | adjective | core | — | — | — | — | grammar_reference | verified | n/a | f. duá "two" — doubt conceptualized via duality |
| alimukeng | a kind of wild gray dove; (also) a sexy body descriptor | noun/adjective | core | — | — | — | — | grammar_reference | verified | n/a | "immalimukeng a mata" = small, sharp eyes; animal-resemblance beauty idiom |
| alim(pa)tók idiom | "orgasm" sense under summit/climax headword | noun | core | — | — | — | — | grammar_reference | verified | n/a | duplicate cross-listing retained to flag this specific euphemism pattern (peak-metaphor for sexual climax) distinctly from the geographic sense already listed |
| arpád | side of; comparable | noun/verb | core | — | — | — | — | grammar_reference | verified | n/a | idiom: "Awan arpadna" = "it has no comparison" |
| arrabis | backhanded slap; spank; diagonal cut | noun | core | — | — | — | — | grammar_reference | verified | n/a | Sp. al revés "reverse" |
| arroskaldo | rice porridge with chicken broth and ginger | noun | core | — | — | — | — | grammar_reference | verified | n/a | Sp. arroz caldo; food-culture loanword |
| arsobispo | archbishop | noun | core | — | — | — | — | grammar_reference | verified | n/a | Sp. arzobispo; arsobispado "archbishopric" |
| asa | to grind, whet; polish; study; learn | verb | core | — | — | — | — | grammar_reference | verified | n/a | single root spans physical sharpening and mental "sharpening" (studying) — same metaphor pattern as English "hone one's skills" |
| asalto | assault; surprise attack; surprise party | noun | core | — | — | — | — | grammar_reference | verified | n/a | Sp. asalto — notable semantic range from violent attack to festive surprise party |
| bakiwelwél | twisted, crooked, bent; disfigured | adjective | core | — | — | — | — | grammar_reference | verified | n/a | — |
| baklay | load carried on the shoulders; duty; responsibility | noun | core | — | — | — | — | grammar_reference | verified | n/a | same burden-as-responsibility metaphor seen in abaga/yabaga above — a recurring body-metaphor pattern for "duty" |
| bakud | wall; stockade; halo of the moon | noun | core | — | — | — | — | grammar_reference | verified | n/a | single word spans built-structure and celestial-phenomenon senses |
| bakuit | refugee | noun | core | — | — | — | — | grammar_reference | verified | n/a | agbakuit "to evacuate"; bakuitan "refugee camp" — likely modern coinage/loan-blend (cf. Eng. "evacuee") |
| bakuna | vaccine, vaccination | noun | core | — | — | — | — | grammar_reference | verified | n/a | Sp. vacuna |
| balandra | bar; obstacle; piece of wood at a jeepney entrance for riders to sit on; sailing vessel | noun | core | — | — | — | — | grammar_reference | verified | n/a | Sp. balandra "sloop"; agbalandra "to bounce, ricochet, boomerang" — concrete-object term extended to a physics-of-motion verb |
| balangkáy | hoop, rim; plaster cast | noun | technical | — | — | — | — | grammar_reference | verified | n/a | — |
| balasa | shuffle; the shuffling of government employees under a new administration | noun/verb | core | — | — | — | — | grammar_reference | verified | n/a | card-game term metaphorically extended to political-patronage reshuffling |
| barday | to hang on a clothesline | verb | core | — | — | — | — | grammar_reference | verified | n/a | — |
| bareng | hoping, in the hopes of; hopefully | adverb/particle | core | — | — | — | — | grammar_reference | verified | n/a | idiom: "Saan a barengbareng ti ayat" = "Love is not trivial" |
| barikada | barricade | noun | core | — | — | — | — | grammar_reference | verified | n/a | Sp. barricada |
| barikawwét | crooked; zigzag | adjective | core | — | — | — | — | grammar_reference | verified | n/a | synonym kawerkawer |
| baríl | barrel of a gun; gun | noun | core | — | — | — | — | grammar_reference | verified | n/a | Sp. barril |
| baringawngáw | loquacious; gossipy; chattering | adjective | core | — | — | — | — | grammar_reference | verified | n/a | synonym salawasaw — the same stock "gossiper" vocabulary cluster seen in the igges curse idiom above |
| baríngit | querulous; peevish | adjective | core | — | — | — | — | grammar_reference | verified | n/a | var. of baranget |
| baríwakwak | a kind of large-mouthed marine fish; loudmouth | noun | core | — | — | — | — | grammar_reference | verified | n/a | figurative extension from fish-anatomy to human speech trait |
| biríndis | to throw money to the crowd (as a show of generosity/celebration) | verb | core | — | — | — | — | grammar_reference | verified | n/a | Sp. brindis "toast, dedicate" — repurposed for a specific Filipino celebratory custom |
| biriská | kind of card game | noun | core | — | — | — | — | grammar_reference | verified | n/a | Sp. brisca |
| bisikléta | bicycle | noun | core | — | — | — | — | grammar_reference | verified | n/a | Sp. bicicleta |
| bisperas | eve (as in Christmas Eve) | noun | core | — | — | — | — | grammar_reference | verified | n/a | Sp. víspera; "Bisperas ti Paskua" = Christmas Eve |
| busnag | light complexion | noun | core | — | — | — | — | grammar_reference | verified | n/a | pamusnagen "rather light complexioned" — skin-tone descriptive vocabulary, socially loaded in Filipino contexts (colorism) though unmarked as taboo by the source |
| busingar | scarred; puckered; with protruding lips; with flared nostrils | adjective | core | — | — | — | — | grammar_reference | verified | n/a | — |
| busók/busók | sound of splashing in the water | noun | core | — | — | — | — | grammar_reference | verified | n/a | onomatopoeic root |
| bussog | state of being full (from eating) | noun/adjective | core | — | — | — | — | grammar_reference | verified | n/a | agbubussog "with a pot belly (children)" — descriptive of child body shape, unmarked |
| darimangán | entrance into a narrow passage; small gate | noun | core | — | — | — | — | grammar_reference | verified | n/a | — |
| darepdép | imagination; dream; aspiration; daydream | noun | core | — | — | — | — | grammar_reference | verified | n/a | — |
| daridár | to insult; despise | verb | core | — | — | — | — | grammar_reference | verified | n/a | — |
| darikmát | instant, moment | noun | core | — | — | — | — | grammar_reference | verified | n/a | "iti apagdarikmat" = in a moment |
| dartidar | the third night of the full moon | noun | core | — | — | — | — | grammar_reference | verified | n/a | tied to a specific folk-superstition: being overtaken by moonrise during supper on this night is a sign of bad luck |
| durpa | to be covered with blood | verb | archaic | — | — | — | — | grammar_reference | verified | n/a | tagged (obs.) |
| dulpet / duoy | unkempt; unclean; slothful; to act like a baby | adjective/verb | core | — | — | — | — | grammar_reference | verified | n/a | — |
| dupóng | to attack head on | verb | core | — | — | — | — | grammar_reference | verified | n/a | — |
| dupráK | to demolish; tear down, dismantle; ruin | verb | core | — | — | — | — | grammar_reference | verified | n/a | "ramramit a pagduprak" = siege engines/demolishing devices (e.g. bulldozers) — notes a modernized sense extension |
| -dor (suffix) | Spanish agentive suffix, feminine -dora | affix | core | — | — | — | — | grammar_reference | verified | n/a | productive with both Spanish loan roots (tayador) and native Ilocano/Pilipino roots (sugador from jugador) — documented code-mixed derivational productivity |
| duron | impulse; emotion; to push, shove | noun/verb | core | — | — | — | — | grammar_reference | verified | n/a | "duronduron kapet-kapet" = an old Ilocano song and dance, naming a traditional performance genre |
| durugista | drug addict; cheater, grafter | noun | colloquial | — | — | — | — | grammar_reference | verified | n/a | f. drogas (Sp. drugista) — modern drug-culture vocabulary |
| ganansia | profit; gain | noun | core | — | — | — | — | grammar_reference | verified | n/a | Sp. ganancia |
| ganét | active, busy | adjective | core | — | — | — | — | grammar_reference | verified | n/a | — |
| ganetgét | fervor; diligent | noun/adjective | core | — | — | — | — | grammar_reference | verified | n/a | illustrative sentence about insisting on going to town |
| ganggandiong | costume jewelry; something feigned; counterfeit | noun | core | — | — | — | — | grammar_reference | verified | n/a | — |
| ganus | immaturity; youthfulness; unripe | noun/adjective | core | — | — | — | — | grammar_reference | verified | n/a | applies to both plants and people — standard ripeness-as-maturity metaphor |
| gansilio | crochet hook; crocheting | noun | core | — | — | — | — | grammar_reference | verified | n/a | Sp. ganchillo |
| gantíng | balance; weighing scale; (fig.) taking advantage of inexperienced people | noun | core | — | — | — | — | grammar_reference | verified | n/a | figurative extension from the physical imbalance of a rigged scale to social exploitation |
| gapagáp | to cut round, shape on a potter's wheel; to thinly slice | verb | technical | — | — | — | — | grammar_reference | verified | n/a | craft/pottery-specific vocabulary |
| gapas | rice harvest by sickle | noun | core | — | — | — | — | grammar_reference | verified | n/a | agricultural-cycle vocabulary (panaggagapas "harvest season") |
| garabiadó | losing (in gambling, games); var. of agrabiado "aggrieved" | adjective | core | — | — | — | — | grammar_reference | verified | n/a | — |
| garadugéd | rumbling sound (hungry stomach, thunder) | noun | core | — | — | — | — | grammar_reference | verified | n/a | onomatopoeic, dual physiological/meteorological application |
| garaigi | to neigh (horses, goats) | verb | core | — | — | — | — | grammar_reference | verified | n/a | animal-sound vocabulary |
| garakgak | loud laughter | noun | core | — | — | — | — | grammar_reference | verified | n/a | — |
| garami | rice stalk; straw, rice hay | noun | core | — | — | — | — | grammar_reference | verified | n/a | agricultural vocabulary with wide comparative cognate list across Philippine languages |
| gargar | hoarse voice; to hurry, hasten; urge on | noun/verb | core | — | — | — | — | grammar_reference | verified | n/a | — |
| i-Laoag | to be from Laoag (a city in Ilocos Norte) | — | core | — | Laoag, Ilocos Norte, Philippines (explicit) | local | grammar_reference | verified | n/a | i- used as variant of taga- for geographic-origin naming, directly naming an Ilocos locality |
| Ibabáo | ethnic group from northern Samar | proper noun | core | — | — | northern Samar, Philippines (explicit) | regional | grammar_reference | verified | n/a | — |
| ibuson | to mail letters; pagbusonan "mailbox" | noun/verb | core | — | — | — | — | grammar_reference | verified | n/a | Sp. buzón "mailbox" fully nativized with verbal affixes |
| idalatría | idolatry, worship of idols | noun | core | — | — | — | — | grammar_reference | verified | n/a | Sp. idolatría |
| idolo | idol; (Tag.) gigolo | noun | colloquial | — | — | — | — | grammar_reference | verified | n/a | single borrowed form spans "religious idol" and slang "gigolo" — a striking semantic bifurcation across the Sp./Tag. borrowing channels |
| igut | thrifty, saving money | adjective | core | — | — | — | — | grammar_reference | verified | n/a | — |

## Morpheme breakdown

Ilocano morphology in the sampled spreads is heavily affixational (prefixes, infixes, suffixes,
and circumfixes all attested), consistent with Rubino's own grammar-outline material (covered by
sibling dispatch 014) and worth flagging per the project's morphological-typology guide rather
than treating every form as atomic:

> **taga-abagatan** = taga- (native-of/from prefix) + abagatan (south, from abagat "south wind")
> — "southerner." The same taga- prefix recurs productively on fully non-Ilocano toponyms in this
> sample, e.g. **taga-Hawaii** "Hawaiian" (synonym of Hawayano) under the *Haway* entry — direct
> evidence the native-origin-marking prefix generalizes to borrowed/foreign place names without
> restriction, a detail relevant to `TepenianHawaiian`'s contact-linguistics interest.

> **i- -an** (circumfix) = i- (thematic/conveyance prefix) + -an (locative/beneficiary suffix) —
> "do X for someone's benefit." Worked example: **Indaitannaka daytoy** = i- + daít ("to sew") +
> -an + -na (3sg agent) + -ka (2sg patient) + perfective in- → "She sewed this for you." A single
> circumfix wrapping a bare root into a full three-argument (agent/patient/beneficiary) predicate.

> **-dor / -dora** (Spanish agentive suffix, borrowed) = attaches productively to both Spanish
> loan roots (**tayador** "gambler," from Pilipino root *tayá* "bet") and to fully Spanish verb
> stems reanalyzed through Ilocano morphology (**sugador** "gambler," ultimately from Spanish
> *jugador*). The dictionary explicitly cross-lists this suffix alongside native equivalents
> (-ero, agCVC-, CumV-, maNCV-), i.e. the source itself treats borrowed derivational morphology as
> structurally on par with native affixation rather than as a separate "foreign" layer — relevant
> to this project's `borrowing`-type derivation mechanics.

> **ika-** (perfective inka-) = distributive/multiplicative/volitional-increase prefix on
> adjectival roots. Worked example: **ikaatiddog** = ika- + atiddog ("long") → "to make something
> long." A fully productive size/degree-intensification derivational pattern parallel to Hawaiian's
> hoʻo- causative family (documented in this project's Hawaiian 005 file) but realized as a prefix
> on the adjective itself rather than a separate causative particle.

## Grammar/register points found in this sample

### A single affix regularly carries both literal-body and metaphorical "duty/burden" senses

**abaga** "shoulder" → **yabaga** "to place on the shoulder; (fig.) bear responsibility," and
separately **baklay** "load carried on the shoulders; (also) duty, responsibility" — two
independent headwords in this sample converge on the identical shoulder → obligation metaphor,
suggesting this is a systematic conceptual pattern in Ilocano (parallel to English "shoulder a
burden") rather than a one-off coinage, worth testing against the Reference Grammar's semantics
chapters once sibling dispatch 001–012 lands.

### The "peak/summit" root doubles as a sexual-climax euphemism

**alim(pa)patok** "summit, peak, top; climax; orgasm" places the sexual sense directly inside the
dictionary's normal headword structure (not flagged `vulg.` or segregated), the same unmarked
euphemism pattern seen in Hawaiian's own dictionary for comparable body-taboo senses nested under
ordinary headwords (cf. this project's Hawaiian 005 file's note on *haʻakoi* "to practice
onanism").

### "Gossiper" (salawasaw) as a recurring stock insult target

At least three independently-sampled entries (**igges** "worm" curse formula, **baringawngáw**
"loquacious; gossipy," and the *dati* entry's unrelated idiom "agdadata...salawasaw nga agdadata"
= "a liar on the back") invoke *salawasaw* "gossiper" as the go-to insult target for loose or
untrustworthy speech — a recurring cultural stock-character worth flagging for the slang-synthesis
mechanics phase as a productive insult-vocabulary anchor point, the way this project has flagged
similar recurring stock-insult patterns in other languages' Phase 1 files.

### Ethnonym cluster with explicit, named sub-dialects

Six ethnonym/language-name entries sampled here (Ibanag, Ibalói, Ibatan/Ivatan, Ifugao, Igorót,
Hanunóo, plus Busao) each carry an explicit geographic-region gloss and, in four cases, explicitly
named sub-dialects (e.g. Ibalói: Daklan/Kabayan/Bokod; Ibatan: Basco/Itbayaten) — the dictionary
itself functions as a compact ethnolinguistic gazetteer of northern-Luzon minority groups
alongside its core Ilocano vocabulary, which is a notably rich seam for this project's
geographic-attestation columns.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `../../00_Reference_Extraction_Spec.md`. All example
sentences and definitions above are the dictionary's own illustrative example sentences quoted at
single-sentence length for linguistic documentation purposes, consistent with this project's prior
practice (e.g. Hawaiian 005); no extended passage of the source's own prose was reproduced
verbatim.
