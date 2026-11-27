# Australian English (slang focus): Research Plan

**Status: plan only, 2026-11-26.** No material is held yet, nothing is triaged, nothing is extracted.
This plan exists so that the corpus can start the moment there is allotment for it. Until then the
only work it asks for is acquisition, which costs no allotment (see §6).

**Folder:** `datasets/Australian_English/`. When triage starts, copy `../_TEMPLATE/` in around this
file. Source material goes in `source_reference/languages/Australian_English/` (not created yet).

---

## 0. Scope rule: research everything

**The proposed domains are not the scope** (author, 2026-11-26): *"Research everything, and then
we'll pick and choose and decide later."* TepenianLanguage proposes *distance communication* and
*networks and data infrastructure* for Australian slang, but new information may come up and plans
may change. So this corpus covers **every domain of Australian slang** (the full domain axis of
`../00_Slang_Source_Type_Taxonomy.md`, plus the Australia-specific ones in §2). No domain is
deprioritized for being outside the proposed ones; the choosing happens afterward, in
TepenianLanguage, by the author.

## 1. Why this language

- **TepenianLanguage lists Australian slang as a later-stage (Tepenian, 2564 to 2812) source**
  (`TepenianLanguage/synthesis_method/06_Domains_and_Later_Stage.md`; Q-16). Cities named there:
  Casey, Davis, Zukelli, Denison; Mirny's nickname is "Australian."
- **The author's note on "particulars of regional standards"** (Long-Term Progress README,
  2026-11-25) uses it as the worked example: Australians first built Tepenia's radio and
  communications infrastructure, so Australian Comms protocol became the national protocol.
- **It is the only later-stage source with no material at all** (status check, 2026-11-26).

## 2. What is new here, and what isn't

Australian English is a variety of English, and **English is already Phase 1 complete**
(`datasets/English/`, 260 files). That corpus covers the standard grammar; do not re-extract it.
14 of its `established/` files already mention Australian English (a few phonological and lexical
contrasts, mostly from the style manuals): read those first as a finding aid
(`grep -l -i australi datasets/English/established/*.md`).

This corpus covers **everything distinctively Australian**, across all domains. The taxonomy's
domain axis applies in full. Domains with a known Australian character, to make sure none is missed
(examples, not a boundary):

| Domain (taxonomy axis 1) | Australian specifics to look for |
|---|---|
| Subsistence and trade crafts | bush and pastoral work (droving, shearing, stations), mining, fishing, building trades |
| Transport and vehicles | trucking and road trains, outback driving, aviation, rail |
| Military and combat | First and Second World War "digger" slang, later service slang |
| Law, order and its inverse | convict-era "flash language," prison, police, criminal argot |
| Emergency services | bushfire brigades, surf lifesaving, the Flying Doctor |
| Food and drink | pub and drinking culture, barbecue, regional food names |
| Sport and games | Australian rules football, rugby league and union, cricket, two-up and gambling |
| Outdoor and adventure | surf and beach culture |
| Youth and education | school, university and teen slang; contemporary youth slang |
| Technology and internet | programmer and online slang; broadband and telecom forums |
| Communications (proposed domain) | radio voice procedure, outback radio networks (pedal radio, Flying Doctor, School of the Air), CB, amateur radio, telegraph and telecom history, military signals, aviation and maritime radio |
| Remote and polar life (setting analog) | Antarctic expeditioner English: several Tepenian city names (Casey, Davis, Mawson, Denison) are real Australian Antarctic sites |
| Work and commerce | workplace, retail, union and industrial-relations slang |
| Regional, ethnic and diaspora identity | **Aboriginal English and Kriol** (an English-based creole spoken in northern Australia), Torres Strait Creole, migrant-community slang, state-to-state regional words |
| Insult, swearing and humor | Australian swearing, insult and ironic naming |
| Every other taxonomy domain | covered the same way: look for it, record what turns up, including "nothing found" |

Two of these could matter beyond Australian slang itself:
- **Kriol and Torres Strait Creole are real English-based creoles.** TepenianLanguage's first era
  is a pidgin becoming a creole, so they may be useful contact-language evidence there too. That
  is the author's call; this corpus just records them.
- **State-to-state word differences are a real case of regional standards** within one country,
  a working model for the "particulars of regional standards" item.

## 3. Questions the research has to answer

1. **Formation mechanics, in every domain.** How does Australian slang make new words? Starting
   points to test against the sources, not to assume: the *-o* / *-ie* (*-y*) shortenings (*arvo*,
   *servo*, *ambo*, *barbie*), rhyming slang, ironic naming (a red-haired man called "Bluey"),
   borrowing from Aboriginal languages. Which are still productive, and in which domains?
2. **What is actually Australian in radio procedure?** Much real radio procedure is set
   internationally (ITU, ICAO and similar bodies). Separate the international standard from what
   Australia added or changed. Record what is found; how the setting uses it is the author's call.
3. **Distance as a driver.** What vocabulary and habits did Australia's long-distance
   communications history (the Overland Telegraph, pedal radio, the Flying Doctor and School of the
   Air networks) produce?
4. **Antarctic English.** What do Australian expeditioners say, and how much is shared with other
   nations' Antarctic programs?
5. **Contact varieties.** What do Aboriginal English, Kriol and Torres Strait Creole show about
   English-based contact languages?
6. **Australian versus shared.** Which items are Australian only, and which are shared with New
   Zealand, Britain or the US? Sources often blur this.
7. **Era and region.** Tag every item with `attested_era` and `attested_region` (state level where
   the source gives it; null where it doesn't, never guessed). Era bands: convict and colonial;
   gold rush; bush and Federation (1890s to 1910s); the world wars; postwar; contemporary.
8. **Surprises.** Anything that fits none of the above gets recorded too, with a note on where it
   turned up.

## 4. Candidate sources (UNVERIFIED)

**Everything below is recalled, not checked.** Titles, authors, editions, dates and availability
must be confirmed before anything is acquired or cited. A wrong recalled fact is worse than a gap.
The lists are a start, not a limit: any domain in §2 without a title here still gets searched.

### General references (cover all domains)

| Candidate | Type | Check |
|---|---|---|
| *The Australian National Dictionary* (Australian National Dictionary Centre / Oxford) | historical dictionary, dated citations | current edition; whether the online version is free and its terms of use |
| G. A. Wilkes, *A Dictionary of Australian Colloquialisms* | slang dictionary | latest edition and any retitled reissue |
| Sidney J. Baker, *The Australian Language* | historical study | which edition (1945 or the revised one) |
| Bruce Moore, *Speaking Our Language: The Story of Australian English* | history of the variety | edition |
| Pam Peters, *The Cambridge Guide to Australian English Usage* | usage guide | edition |
| The *Macquarie Dictionary* and any Macquarie slang titles | national dictionary | which slang titles exist |
| A Lonely Planet-style Australian language phrasebook | travel slang appendix | current edition |

### Domain-specific references

| Domain | Candidate | Check |
|---|---|---|
| Swearing and insult | Amanda Laugesen, *Rooted: An Australian History of Bad Language* | edition |
| Military | Amanda Laugesen, *Diggerspeak: The Language of Australian Soldiers*; *Furphies and Whizz-bangs* (First World War slang) | editions |
| Antarctic | Bernadette Hince, *The Antarctic Dictionary: A Complete Guide to Antarctic English* | publisher and edition |
| Antarctic | Australian Antarctic Division publications: station newsletters, expeditioner material, oral histories | what is public |
| Communications | official Australian radio operator handbooks (marine, aviation) | which bodies publish them, current versions |
| Communications | Australian UHF CB rules and usage guides; Wireless Institute of Australia publications | what exists and is accessible |
| Communications | histories of the Overland Telegraph, pedal radio, the Royal Flying Doctor Service, School of the Air, the Royal Australian Corps of Signals | titles to be found |
| Contact varieties | grammars and dictionaries of Kriol, Torres Strait Creole and Aboriginal English | titles to be found |
| Convict and criminal | historical dictionaries of convict "flash language" | titles to be found |
| All other domains in §2 | to be found | search each one |

### Usage corpus (searched, not extracted)

| Candidate | Type | Check |
|---|---|---|
| Trove (National Library of Australia): digitized newspapers | very large usage oracle | OCR quality (flag `transcription_confidence`); terms of use for bulk access |
| Public-domain Australian literature (for example C. J. Dennis, *The Songs of a Sentimental Bloke*, with its own slang glossary; Henry Lawson; Banjo Paterson; Douglas Mawson, *The Home of the Blizzard*) | usage text, colonial to early 1900s | public-domain status; clean text copies |
| Australian online forums, one per domain where possible | contemporary usage | which forums, archive access, terms of use |
| Oral history transcripts (national library, Antarctic Division) | spoken usage in text | transcription confidence |

## 5. Search angles, for when the allotment allows

Run every domain in §2 from several angles, log dead ends (including domains where nothing turns
up), and prefer primary and scholarly sources:

- library catalogs and publishers, domain by domain;
- Australian English lexicography (the national dictionary centre's publications and newsletters);
- regulators, training bodies and institutions for each trade and service domain;
- the Antarctic Division and Antarctic history societies;
- public-domain text libraries for the usage corpus;
- this project's own stashes first (`lang transfer bay/`, `xx--stash/`, the external drive): a
  filename search for Australia-related titles. The only hit on 2026-11-26 was an Australia reader
  inside the Mandarin folder (*Introducing Australia*), which is Mandarin-medium and not a source
  here.

## 6. What the author can do now (no allotment needed)

Acquisition is manual and costs nothing from the weekly allotment:

1. **General references first,** because they cover every domain at once: the national historical
   dictionary and a general slang dictionary.
2. **Then domain-specific titles, any domain,** as they turn up.
3. Drop everything into `source_reference/languages/Australian_English/`. Subfolders by domain are
   optional; the triage sorts them either way.

## 7. Processing plan, once there is allotment

1. **Triage** into `00_Book_Triage_Catalog.md`, the usual format (text layer or vision, medium,
   tiers), with each book's domains listed. Verify every §4 candidate that was acquired.
2. **Extraction** to `established/` under `../00_Reference_Extraction_Spec.md`, with `source_type`,
   `transcription_confidence`, `attested_era`, `attested_region` and the domain on every entry.
3. **Usage corpus** kept in `language_corpus/Australian_English/` and searched, not extracted.
4. **Graphify** the folder (by the main session, never by subagents).
5. **Hand off** to TepenianLanguage: everything found, by domain, with the formation mechanics.
   The author picks what the language uses.

## Log

- 2026-11-26: plan written. No sources held. Candidate list from recall only, all unverified; no
  web research run (weekly allotment reserved for other processes).
- 2026-11-26: scope widened at the author's word to every domain (§0); the proposed domains are
  no longer the plan's frame.
