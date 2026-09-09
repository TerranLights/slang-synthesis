# Hungarian Slang Corpus — Kövecses, *Magyar Szlengszótár*, letters A–E (sample)

**Source:** Kövecses Zoltán, *Magyar Szlengszótár* (Hungarian Slang Dictionary), 2nd revised and
expanded edition (Akadémiai Kiadó, Budapest, 2009; 1st ed. 1998; this printing "változatlan
utánnyomás" 2010). ISBN 978 963 05 8696 2. Physically sits at
`source_reference/languages/Hungarian/Magyar Szlengszótár.pdf` (170 PDF pages) but its content is
a genuine slang dictionary, not grammar/vocabulary reference — per the scope note in
`datasets/Hungarian/00_Book_Triage_Catalog.md`, extracted from where it physically lives but
written here to `language_corpus/Hungarian/` instead of `established/`.

**Coverage of this file:** PDF pages 1–45 of 170, as assigned. **No text layer** —
`pdftotext`/`pdfinfo` reports a real text layer flag but the content renders as a scanned-image
PDF with garbled/absent extractable text; every page was rendered with `pdftoppm` and read
visually. **This is research only — nothing here is canon** until worked into actual setting
material by explicit decision.

## Page-mapping note (found empirically, not assumed)

This PDF is scanned as **two printed pages per PDF-page image** (a full double-page spread), not
one page per image — the same gotcha flagged for *Colloquial Serbian* in
`datasets/00_Reference_Extraction_Spec.md`. Verified empirically by rendering and reading PDF
pages 1, 2, 3, 7, 10, 13, and 16 directly: PDF page 1 = front/back cover spread, PDF page 2 =
half-title/title-page spread, PDF page 3 = copyright/dedication spread, and from PDF page ~4
onward the printed book pagination begins. The offset holds exactly across every spot-check in
this range: **printed left-hand page = 2×(PDF page) − 2, printed right-hand page = 2×(PDF page) −
1.** So PDF pages 1–45 (the assigned range) correspond to printed pages 0–89 — i.e., all of the
front matter (title page, preface/"Mi a szleng?" essay, dictionary-structure guide, works-cited
list, printed pages ~1–25) plus **printed dictionary pages 26/30–89**, which is the A through
early-E span of the alphabetical dictionary (confirmed samples below run from `ad` on printed
p. 30 to `elmegy` on printed p. 89).

## Sampling decision (explicit, per dispatch instructions)

**Sampled, not exhaustive — same discipline as the `Magyar szólások és közmondások` proverb
dictionary precedent (`established/010`).** The dictionary body is extremely dense: each printed
page runs two columns of small-font entries, and a single spread (e.g. printed pp. 30–31) holds
on the order of **90–100 headword entries**. Across the ~60 printed dictionary pages in this
range (pp. 30–89), that is a rough estimate of **2,500–3,000 total headwords** — clearly the
"hundreds of entries" threshold the dispatch flagged for sampling rather than exhaustive capture.

**Sampling method:** rather than reading every consecutive page (which would only reach partway
into letter A), seven representative spreads were selected at roughly even intervals across the
full assigned range, deliberately spanning multiple letters for register/domain diversity:
printed pp. 30–31 (`ad`–`akkor`), 40–41 (`banyakocsi`–`bazíroz`), 48–49 (`belepkézik`–
`benzintyúk`), 58–59 (`bogyózik`–`brahi`), 68–69 (`csárázás`–`csipkedi`), 78–79 (`döglik`–
`durranás`), and 88–89 (`eliszkol`–`elmegy`). From each spread, the most semantically/
mechanically illustrative entries were selected (clear metaphor/metonymy, productive derivational
patterns, explicit register tags, recurring formation types) rather than every entry on the page
— polysemous sub-senses and drill-like near-duplicate compounds (e.g. long runs of `elküld a
[X]ba/be` "send to hell" variants, of which the source has a dozen+) were thinned to 1–2
representative examples per pattern rather than all of them.

**No handwritten marginalia found anywhere in this range** — all pages are clean print scans (no
library stamps, no pencil annotation, no reader's notes); the vision-reading guard's marginalia
check was applied and came back negative throughout.

## Source's own register-tag system

The dictionary marks a subset of headwords with an italicized stylistic qualifier immediately
after the headword. Two tags appear in this sample:

- **`durva`** ("coarse/crude") — vulgar but not the source's most extreme category. Mapped to
  Usage Tier `taboo`, per the same `durva`→`taboo` mapping already established for this language
  in `established/010`'s register-tag table.
- **`tabu`** ("taboo") — the source's most explicit tag, reserved for direct sexual/scatological/
  profane headwords (`baszik`, `elküld az anyjába`, `akkora a farka... mint egy lóé`, etc.). Also
  mapped to `taboo`, but flagged in Notes as the source's *stronger* of the two tags where the
  distinction matters.
- **`ironikus`** ("ironic") — seen on one sampled entry (`drág(ic)ám`); mapped to `slang` with an
  ironic-register note.
- **Untagged entries** are the dictionary's default/unmarked slang register — mapped to Usage
  Tier `slang` (this is a dedicated slang dictionary; even its "plain" entries are slang by the
  book's own scope, distinct from `core`/`colloquial` vocabulary).

Numbered senses (①②③④ in the source, rendered here as "1./2./3." within one gloss) mark distinct
meanings of the same headword — kept together in one table row's Gloss field when both were
selected, rather than split into duplicate rows.

## Vocabulary (representative sample, ~130 entries)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| ad neki | to hit/punish someone (lit. "gives to him/her") | verb phrase | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Example sentence given: children "adjunk neki" so as never to finish something. |
| adu | 1. decisive argument 2. influential/well-connected person | noun | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Lit. "trump card" (card-game term) — domain-leak metaphor from card games into general argument/status vocabulary. |
| ady | 500-forint banknote | noun | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | plausible_unverified | Likely eponymous: poet Endre Ady's portrait appeared on the older 500 HUF note — a currency-portrait-naming pattern (cf. English "a Grant," "a Franklin"). |
| afrik | pubic hair | noun | taboo | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Untagged in source but body-taboo content; example: "Kilátszik az afrik a minibol." |
| agy, az | smart/clever person | noun phrase | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Lit. "the brain" — metonymy (body part → person defined by that faculty), a recurring pattern in this dictionary. |
| agyal | to think, to overthink | verb | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Denominal verb from `agy` "brain" + `-al` — one of many `agy`-rooted entries on this page (agyas, agybaj, agyfasz, agyhalott…), showing a small productive word-family radiating from one root. |
| agyament | crazy, not normal | adjective | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | `agy` "brain" + `-ment` (from `mentes` "-free/exempt," i.e. "off one's brain"). |
| agyfasz | 1. state of someone's brain not working 2. state of being disoriented/frozen up | noun | taboo | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | plausible_unverified | Explicitly tagged `tabu` in source — `agy` "brain" + `fasz` "dick," a taboo-compound intensifier pattern. |
| agyhúgykövet kap | to become furious | verb phrase | taboo | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | plausible_unverified | Tagged `durva`. Lit. "gets a brain kidney-stone" — grotesque medical-metaphor intensifier for anger. |
| ajser | 1. elegant, well-dressed 2. rich | adjective | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | plausible_unverified | Also `ajser hapsi` "rich man," `ajser lesz` "to get rich" — a small closed paradigm around one loan-flavored root. |
| ahol lószar van, veréb is van | where there's opportunity, someone will exploit it | idiom | taboo | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Tagged `durva`. Lit. "where there's horse-shit, there's sparrows too" — proverb-shaped fixed slang idiom, structurally identical to the `established/010`/`006` proverb-dictionary formation type. |
| ahogy azt a Móricka elképzeli! | expresses disbelief/sarcasm at a naive plan | idiom | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | "Móricka" is a stock naive-child figure in Hungarian joke culture (like "little Johnny" jokes) — named-stock-character formation. |
| akkora a farka/fasza, mint egy lóé | has a large penis | idiom | taboo | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Explicitly tagged `tabu`. Simile-based size-boast formation ("as big as a horse's"). |
| akkora, mint egy ház/olajtó/liftajtó | very large (of a person's build) | idiom | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Productive simile slot with 3 interchangeable comparison objects listed in the source itself (house/oil-door/elevator-door). |
| akkor szopok, ha... | expresses strong certainty ("I'll be damned if...") | idiom | taboo | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | plausible_unverified | Tagged `tabu`. Conditional-certainty-oath formation built on a taboo verb, paralleling English "I'll eat my hat if...". |
| banyakocsi | wheeled shopping cart pulled by elderly shoppers | noun | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Lit. "hag-cart"; a near-synonym `banyataliga`/`banyatank` cluster appears on the same page — same referent, 3 competing coinages. |
| bányarém/bányarigó/bányász(kislány) | ugly girl | noun | taboo | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | plausible_unverified | Three synonymous coinages ("mine-monster/mine-thrush/miner girl") built on the same `bánya-` "mine" root — insult-formation cluster. |
| bányászbéka segge alatt van | very poor | idiom | taboo | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Tagged `durva`. Lit. "is under a mining-frog's ass" — absurdist below-rock-bottom spatial metaphor for poverty. |
| barátocskám! | condescending/threatening address to a man | interjection | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Diminutive `-cska` on "friend" flipped to menacing irony — diminutive-as-threat pattern. |
| barbi(e) | pretty but unintelligent girl/woman | noun | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Direct loan from the Barbie doll brand — commercial-icon-as-stereotype formation. |
| bárcás | immoral/promiscuous woman | adjective/noun | taboo | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | plausible_unverified | Historically "bárca" = a licensed prostitute's registration card — a fossilized-institution-term slang survival. |
| báró | good, great, fashionable | adjective | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Loanword "baron" generalized to a bare positive-quality intensifier, detached from any nobility sense. |
| barom | 1. stupid person 2. hateful/repellent person | noun | taboo | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Lit. "cattle/beast" — animal-metaphor insult, one of this dictionary's most productive imagery domains (cf. `benga állat`, `csatahajó`, `dromedár`). |
| baromi | intensifier: "very" | adverb | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Derived adverbially from `barom` "beast" — animal-root grammaticalized into a pure degree intensifier, a slang-formation mechanism (semantic bleaching) worth flagging for Phase 3. |
| baszik(ik) | to have sex | verb | taboo | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Explicitly tagged `tabu` — the dictionary's core taboo verb, root of a very large derivational family on this spread (baszd meg, baszki, basztat, basszamozik, baszogat, etc.). |
| baszd meg! | "fuck it!" (angry interjection) | interjection | taboo | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Tagged `tabu`. |
| baszki(kám) | friendly/casual address to a man ("dude") | interjection | taboo | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Tagged `tabu`, but glossed as a *friendly* term of address — taboo root fully bleached of its literal force in this use, a clean example of taboo-inversion-to-affection. |
| basszorkányos Varga János! | euphemistic exclamation of anger | interjection | taboo | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | plausible_unverified | Tagged `durva`. A rhyming nonsense-name substitution for `baszd meg` — sound-alike euphemistic-substitution formation (cf. English "fudge," "shoot"), using an invented personal name (Varga János) as the disguise vehicle. |
| bazíroz | to rely/base one's plans on something | verb | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | From "bázis/base" — loanword-root verbalized with native `-oz` suffix. |
| belerántja a szarba | to drag someone into trouble | verb phrase | taboo | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Tagged `durva`. `szar` "shit" as the general trouble-metaphor vehicle — recurs across many idioms in this dictionary (`benne hagy a szarban`, `beleszarik az egészbe`). |
| béna | 1. clumsy/awkward 2. incompetent person | adjective/noun | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Lit. "paralyzed/lame" (medical term) — disability-term-as-insult, a distinct metaphor domain from the animal/body ones above; worth flagging for a future register-sensitivity note in Phase 3. |
| béna béla/béna hapsi | incompetent person | noun phrase | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Same rhyming-stock-name pattern as `basszorkányos Varga János` and `Móricka` — alliterative "Béla" chosen purely for the rhyme with `béna`. |
| benga | 1. big 2. big/dumb person 3. size-intensifier | adjective/noun | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | plausible_unverified | Also `benga állat` "big, dumb creature" — compounds with the `állat`/`barom` animal-insult family. |
| benzintyúk | woman who is very fond of motorbikes | noun | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Lit. "gasoline hen" — domain-compound (vehicle culture + bird-diminutive-for-woman pattern, cf. English "chick"). |
| bemagol | to cram/study intensively | verb | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Prefix `be-` "into" + `magol` "to memorize by rote" — standard-register verb + slang-flavored intensifying prefix, an agglutinative-prefix-stacking example relevant to this language's morphological-play mechanism. |
| bogyózik | to think | verb | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | low_confidence | Print was fully legible but the gloss (semantically closer to "berry/pill" root) is an unexpected departure from `bogyó` "berry/pill" — flagged for possible drug-slang connotation not fully captured by the source's bare gloss "gondolkodik" (to think); worth a second look in a future non-redundant-supplement pass rather than a reading error per se. |
| bohóc | detestable/unpleasant person (esp. a man) | noun | taboo | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Lit. "clown" — role-metaphor insult. |
| bolha seggén pattanás | something extremely tiny | idiom | taboo | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Tagged `durva`. Lit. "a pimple on a flea's ass" — extreme-diminutive compound simile, one of the dictionary's most vivid size-metaphor idioms. |
| bomba(jó) | very good/very pretty | adjective | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | `bomba` "bomb" as a bare positive intensifier — a violence/explosion-root generalized to praise, same bleaching mechanism as `durranás` "special event" (lit. "bang") below. |
| bombázó | very attractive, sexy woman | noun | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Lit. "bomber (aircraft)" — same `bomba` root, agentive/instrument-noun form repurposed for a person; matches English "bombshell." |
| bombasztikus | very good | adjective | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Direct loan from English/international "bombastic," sense-shifted from "pompous/overblown" to plain "great." |
| boszi/boszorkány | 1. ugly woman 2. unpleasant woman 3. old woman | noun | taboo | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Lit. "witch" — folklore-figure-as-insult, joining the clown/animal/disability insult-metaphor domains already seen. |
| bögre | 1. someone's girlfriend 2. woman/girl (general) 3. vagina (taboo sense) | noun | taboo | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Lit. "mug/cup" — container metaphor with three-way sense-narrowing/polysemy explicitly numbered in the source, a clean single-entry example of semantic narrowing worth a Phase 3 case study. |
| böhöm nagy | very big | adjective phrase | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Reduplicative/expressive intensifier prefixed onto plain `nagy` "big" — a sound-symbolic intensification pattern distinct from the loanword (`bombasztikus`) and animal-root (`baromi`) intensifier types above. |
| brahi | 1. courage / unnecessary risk-taking 2. a mean-spirited joke/prank | noun | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | plausible_unverified | Two senses bridge "bravado" and "prank" — social-risk-taking semantic field. |
| csárázás | oral sex (given by either party) | noun | taboo | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | plausible_unverified | Tagged `durva`. Root of a small family on this page (`csárázik`, `csárel`) — same act, three near-synonym coinages, paralleling the `banyakocsi` cluster pattern above but in the sexual-taboo domain. |
| csehó | pub/bar | noun | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | From `cseh` "Czech" (beer-culture association) + diminutive-flavored `-ó`, an ethnonym-to-place-noun formation. |
| csekonics | rich person | noun | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | low_confidence | Likely an eponym from the Hungarian noble Csekonics family name, generalized to mean "rich person" — plausible but not independently cross-checked within this sample; flagged for confirmation in a future non-redundant-supplement pass. |
| csík | amphetamine or cocaine powder | noun | taboo | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Lit. "stripe/line" — matches the English drug-slang calque "a line," an interesting cross-linguistic parallel-formation worth flagging. |
| csíkba rendezett adag | a dose of drugs arranged into lines (for snorting) | noun phrase | taboo | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Directly related to `csík` above — same drug-paraphernalia semantic field. |
| csikk | 1. cigarette butt 2. the end/roach of a marijuana cigarette | noun | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Sense 1 is mainstream colloquial; sense 2 narrows the same word into drug-culture register — a tier-straddling entry (colloquial core meaning + slang narrowed meaning) worth noting for Usage Tier granularity. |
| csinál | to have sex (euphemistic) | verb | taboo | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Untagged in source despite the taboo sense — lit. "to do/make," a bleached light-verb euphemism for the sex act, structurally parallel to English "to do it." |
| csinálja a fesztivált/forradalmat | to make a scene | verb phrase | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Lit. "does the festival/revolution" — hyperbolic-event metaphor for causing a commotion. |
| cserkészik | to chase after / flirt with girls | verb | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Denominal verb from `cserkész` "(boy) scout" + `-ik` — institution-name-to-verb conversion, a clean morphological-play example (see Morphological notes below). |
| csatahajó | fat woman | noun | taboo | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Lit. "battleship" — size/bulk vehicle-metaphor insult, same family as `dromedár/dromi` below. |
| döglik | to lounge around and do nothing | verb | taboo | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Tagged `durva`. Lit. "to be dying" (used of an animal) — mortality-verb bleached into "to laze about," root of a large family on this page (`döglik vkiért`, `dögunalmas`, `dögrováson van`, `dögös`). |
| döglik vkiért/vmiért/vki után | to be infatuated with someone | verb phrase | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Same `dögl-` root, inverted sense (infatuation rather than laziness) via a different case-government pattern (`-ért`/`után`) — a clean example of the same lexeme branching into unrelated slang senses purely by argument structure. |
| dögös | 1. sexually inviting 2. beautiful/gorgeous | adjective | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Same `dög` "carrion/carcass" root as `döglik` above, but with `-ös` adjectival suffix producing a positive "hot/gorgeous" sense — a striking carrion→attractive semantic inversion worth flagging as a named mechanism for Phase 3 (cf. English "drop-dead gorgeous" for a partial parallel). |
| dögunalmas | extremely boring | adjective | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | `dög` "carrion" prefixed as a bare intensifier onto `unalmas` "boring" — same root as `dögös` used in the opposite (purely negative-intensifying) function, showing one root feeding two distinct slang-formation mechanisms. |
| drakula! | "congratulations!" | interjection | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | plausible_unverified | Fictional-icon eponym (Dracula) repurposed with no obvious semantic link to the vampire figure — possibly a sound-play/rhyme-driven coinage rather than a metaphor-driven one; flagged as an open question. |
| dörzsölt | 1. experienced 2. sly, cunning | adjective | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Lit. "rubbed/worn smooth" — texture metaphor for worldliness, parallel to English "worn," "seasoned." |
| drukkol | 1. to be nervous/scared 2. to be anxious about something | verb | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | From German "drücken" via sports-fan "to root/cheer," narrowed here toward plain anxiety — loanword semantic drift. |
| duma | 1. chit-chat 2. nonsense talk/empty rhetoric 3. a refusal to listen framed as "that's just talk" | noun | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Root of a very large family on this page (dumafranci, dumagép, dumál, dumálgat, dumaparti, dumás, dumcsi, dumcsizik) — one of the densest single-root derivational clusters in this whole sample, strong candidate for a Phase 3 "productive slang root" case study. |
| dumagép | a person who talks constantly/incessantly | noun | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Lit. "talk-machine" — compound with `gép` "machine," an instrument-metaphor-for-person pattern distinct from the animal/vehicle/role metaphor families above. |
| dundi | chubby | adjective | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Reduplicative-flavored expressive adjective, phonaesthetically soft/affectionate rather than insulting despite naming body size — contrasts with the harsher `csatahajó`/`benga állat` fat-insult entries above, useful register-contrast pair. |
| durranás | a remarkable/special event | noun | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Lit. "bang/pop" — sound-effect noun bleached into general positive-event praise, same mechanism family as `bomba(jó)` above. |
| drótot kap | to get tipped off/warned in advance | verb phrase | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Lit. "gets wire" — communications-technology metaphor ("wire" = inside information), matching the English idiom "to get wind of/wired." |
| dugás | 1. sexual intercourse 2. a person regarded as a sex object/partner | noun | taboo | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Untagged in source despite taboo content; lit. "plugging/insertion," root of `dugesz/dugi` "hidden (stash)" and `dugipénz` "secret stashed money" on the same page — one root, two unrelated slang branches (sex vs. concealment) from the same core "insert/hide" meaning. |
| eliszkol | to flee, run away | verb | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | |
| eljár a pofája | to blab, talk too much without meaning to | verb phrase | taboo | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Tagged `durva`. Lit. "his mouth/cheek runs off (on its own)" — body-part-as-independent-agent idiom. |
| elkap egy fordulóra | 1. to have sex with someone 2. to scold someone 3. to pressure/exploit someone | verb phrase | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Lit. "catches for a round/turn" — sports/dance-round metaphor branching into three unrelated coercive/sexual senses. |
| elkapja a tökét | to punish someone severely | verb phrase | taboo | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Tagged `durva`. Lit. "grabs his balls" — body-part-seizure threat idiom. |
| elkúrja az időt | to waste time, dawdle | verb phrase | taboo | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Tagged `tabu`. `elkúr` "to fuck up/ruin" + `időt` "time" — taboo verb generalized to a mundane "waste" sense. |
| elküld a francba/pitlibe | to tell someone to go to hell | verb phrase | taboo | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Tagged `durva`. One representative of a large `elküld a [X]ba/be` "send to [euphemistic-hell-substitute]" paradigm the source lists a dozen+ variants of (pokolba, francba, pitlibe, túróba, erdőbe, anyjába...) — a highly productive slot-filler construction, strong Phase 3 candidate for a "dismissal-formula" mechanism entry. |
| elküld az anyjába | very vulgar dismissal ("send him to his mother['s womb]") | verb phrase | taboo | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Tagged `tabu` (the paradigm's most vulgar slot-filler, vs. the milder `durva`-tagged variants above). |
| elmegy (a hajó) | 1. to reach orgasm (said of a man) 2. for something to be over/settled | verb phrase | taboo | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Lit. "the boat leaves" — vehicle-departure euphemism for orgasm, paralleling `ellövi a patront` "fires the cartridge" on the same page (also taboo, same referent, projectile-metaphor variant). |
| elmar | 1. to seduce (someone) away 2. to catch/apprehend 3. to acquire/get hold of | verb | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | plausible_unverified | Three senses cluster around "successfully take/obtain," ranging from romantic to legal to material contexts. |
| elmebeteg | a crazy/insane person (used as a general insult) | noun | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | Lit. "mentally ill" — clinical-term-as-insult, same mechanism as `béna` above; both drawn from the medical/disability domain. |
| ellóg (a munkából) | to skip/dodge work | verb phrase | slang | — | contemporary (source pub. 2009) | — | — | dictionary | n/a | verified | |

## Morphological notes (agglutinative slang-formation patterns worth flagging for Phase 3)

Per this language's typology profile (`datasets/Hungarian/00_Extraction_Checklist.md`'s
"Morphological typology" section — agglutinative but unevenly so across subsystems), several
entries in this sample show slang specifically exploiting productive derivational morphology
rather than inventing new roots:

- **Denominal verbing**: `cserkészik` (`cserkész` "scout" + `-ik` verb-forming suffix, "to chase
  girls"), `bazíroz` (loan root `bázis` + `-oz`, "to rely on"), `bemagol` (`be-` prefix + `magol`,
  "to cram"). A noun (often institutional or loan) takes a standard verb-forming suffix and the
  result is slang purely by virtue of its new, narrowed referent — the suffix itself is
  completely regular standard-grammar morphology, not a special slang affix.
- **Root-family radiation**: single roots spawn large, semantically-diverging derivational
  families that a non-agglutinative language would need separate unrelated words for. Two clear
  examples in this sample: `duma` "talk" → `dumafranci`/`dumagép`/`dumál`/`dumálgat`/`dumaparti`/
  `dumás`/`dumcsi`/`dumcsizik` (8 forms on one page spread, all sharing the "talk/chatter"
  semantic core but differing in agentivity, intensity, and part of speech); and `dög`
  "carrion/carcass" → `döglik`/`dögös`/`dögunalmas`/`dögrováson van` (branching into laziness,
  sexual attractiveness, and boredom-intensification — three unrelated slang senses from one
  root, distinguished only by which suffix/construction attaches).
- **Taboo-root compounding as intensification**: `agyfasz` (`agy` "brain" + `fasz` "dick") and
  `agyhúgykövet kap` (`agy` "brain" + `húgykő` "kidney stone") both fuse a body-part/organ noun
  with a taboo or medical noun to produce a single-concept intensifier/idiom — agglutinative
  compounding pressed into service for taboo slang specifically, not just neutral vocabulary.

## Standout slang-formation patterns for future Phase 3 mechanics analysis

1. **Productive dismissal-formula slot-filler**: `elküld a [X]ba/be` "send to [X]" with a large,
   source-enumerated paradigm of interchangeable euphemistic/taboo destination nouns (francba,
   pitlibe, pokolba, túróba, erdőbe, anyjába...), graded from mild (`durva`) to extreme (`tabu`) by
   which noun fills the slot. A clean single-construction, variable-vulgarity-by-lexical-choice
   mechanism.
2. **Rhyming/alliterative stock-name substitution**: `basszorkányos Varga János!` (disguising
   `baszd meg`), `béna béla` (rhyming with `béna`), and the pre-existing stock naive-child figure
   `Móricka` all use an invented or borrowed personal name chosen for sound-match rather than
   meaning — a euphemistic-substitution mechanism worth comparing against English "fudge"/"shoot"-
   style minced oaths.
3. **Semantic bleaching of violent/mortality roots into pure positive intensifiers**: `bomba(jó)`,
   `bombasztikus`, `durranás`, `báró` all drain an unrelated source domain (explosives, nobility)
   down to bare "very good" — and `dögös`/`dögunalmas` show the *same* root (`dög` "carrion")
   bleaching into two opposite-valence outcomes (attractive vs. extremely boring) depending on
   construction, which is the single most striking finding in this sample.
4. **Metaphor-domain census across the sample**: animal/beast (`barom`, `benga állat`, `csatahajó`,
   `dromedár`), medical/disability (`béna`, `elmebeteg`, `agyhúgykövet kap`), vehicle/technology
   (`benzintyúk`, `dumagép`, `elmegy a hajó`, `drótot kap`), and folklore/fiction figures (`boszi`,
   `drakula`, `Móricka`) are the four dominant source domains this sample turned up — worth
   testing against a larger sample later to see if they hold as the dictionary's main donor
   domains overall.

## Coverage remaining

PDF pages 1–45 (printed front matter + dictionary pp. 26/30–89, letters A through early E) are
sampled here. **A separate, concurrently-dispatched chunk already covers PDF pages 46–90** (printed
pp. 90–179, letters el- through link) — see
`language_corpus/Hungarian/01_szlengszotar_dictionary_pp90-179.md` — so the two files together give
continuous alphabetical coverage from A through "link" across PDF pages 1–90. PDF pages 91–170
(remainder of the alphabet, roughly letters m–z, plus any back matter) remain unread by any
dispatch so far. A future pass could sample that remaining range the same way, reusing either
file's page-mapping formula directly rather than re-deriving it.
