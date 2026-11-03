# Slang Source-Type Taxonomy

**Purpose.** A planning reference for *where to look* for slang-rich text material, as distinct
from `00_Usage_Tier_Taxonomy.md` (which categorizes vocabulary *after* it's already been extracted).
This document is about sourcing/acquisition strategy: what kinds of text-based documents naturally
contain slang, organized so coverage can be reasoned about systematically rather than found ad hoc.

**Scope constraint.** Text only — video and audio cannot be processed directly in this pipeline.
Every entry below must be (or reduce to) readable text: a PDF, scanned page, forum HTML, EPUB, etc.
A few genres straddle this (e.g. song lyrics, screenplays) and are included where a textual form
exists independent of the audio/video performance.

**This is a living document**, started 2026-11-01. Add to it as new source types or domains are
identified — don't treat the lists below as closed.

---

## Two independent axes

Reasoning about coverage works best by crossing two axes:

1. **Domain** — *why* the slang exists: what area of life or community generates it.
2. **Source genre** — *what kind of document* captures it, and whether it's a **reference-type**
   source (explicit definitions — cheap to extract, mirrors what's already worked well, e.g.
   *Dirty German Everyday Slang*, *A Dictionary of Cantonese Slang*) or a **usage-type** source
   (authentic running text — searched as an oracle corpus rather than individually extracted, per
   [[usage_corpus_vs_reference_corpus]] / `00_Usage_Tier_Taxonomy.md`'s broader framing).

A given domain (e.g. "gaming") can be fed by either genre type: a reference-type gamer-slang
glossary, or a usage-type gaming forum thread. Both are valid; they trade off extraction cost
against authenticity.

---

## Axis 1 — Domain (why the slang exists)

Grouped into areas of life that recur across most cultures, not just English-speaking ones:

- **Subsistence/trade crafts** — farming, fishing/maritime, hunting, construction, artisan trades
- **Transport & vehicles** — cars/tuner culture, motorcycles, trucking, aviation, rail, naval
- **Military & combat** — by branch, veteran culture, historical vs. modern
- **Law, order & its inverse** — police, courtroom, prison/criminal argot, gangs, smuggling, drug culture
- **Emergency services** — firefighting, EMS/paramedic culture; split out from "Law, order" since its
  slang register is distinct from police/legal
- **Health & body** — medical/nursing, fitness/bodybuilding, beauty/cosmetics, mental health
- **Food & drink** — professional kitchens, bartending, regional cuisine culture
- **Sport & games** — by sport, esports/gaming, tabletop/card games, gambling
- **Outdoor/adventure sports** — climbing, surfing, skiing, extreme sports; split out from "Sport &
  games" since this register is notably rich and often English-origin-but-locally-adapted
- **Youth & education** — school/campus, university/fraternity culture, teen culture broadly
- **Academic/disciplinary culture** — grad-school and lab/discipline-specific slang, distinct from
  general campus slang and from programmer-specific tech slang below
- **Technology & internet** — programmers/hackers, meme/internet culture, crypto/trading
- **Fashion, beauty & appearance** — fashion industry, streetwear/subculture fashion
- **Music & performance subculture** — hip-hop, punk/metal, EDM/rave, theater
- **Fandom & hobbyist communities** — anime/manga, k-pop, sci-fi/fantasy, collecting
- **Work & commerce** — corporate jargon, retail, call-center, gig economy, real estate
- **Sexuality, gender & relationships** — LGBTQ+ subcultures, dating culture, kink communities
- **Religion, ritual & fringe groups**
- **Regional/ethnic/diaspora identity** — code-switching, class-based slang, regional pride
- **Conflict & protest** — political and activist slang
- **Domestic/family life** — parenting culture, household slang
- **Pet/animal-enthusiast culture** — equestrian, dog-sport, and similar communities; surprisingly
  dense jargon, not represented under any other domain above

## Axis 2 — Source genre (what document captures it)

### Reference-type (highest extraction efficiency)

Explicit definitions, already the most proven genre in this project:

- Dedicated slang dictionaries — a recurring genre across many languages' publishing markets
- Academic slang/argot dictionaries (sociolinguistics scholarship)
- Teen-slang pocket dictionaries (commercial, often reissued yearly)
- Rhyming-slang / thieves'-cant historical dictionaries
- Insult/swearing-specific dictionaries
- Military-slang dictionaries (official or academic)
- Drug-slang glossaries (harm-reduction orgs, law-enforcement training texts)
- Trade/profession jargon guides (nursing, firefighting, trucker CB codebooks, aviation glossaries, ham radio Q-codes)
- Corporate-jargon dictionaries (a standard business-book genre)
- Fandom-wiki glossary pages (TV-Tropes-style)
- Lyrics-annotation sites (Genius-style — textual, explains slang in song lyrics without needing audio)
- Glossary appendices in linguistics theses on a language's youth/street register
- **Crowdsourced online slang dictionaries** (the Urban-Dictionary-equivalent genre) — a distinct
  format/reliability profile from published book dictionaries above: web-archived, unmoderated,
  needs its own confidence flagging (same spirit as [[source_reliability]]'s subtitle flags), but
  exists in some form for a surprisingly large number of languages and tends to lead published
  dictionaries on exactly the youth/internet slang they lag behind on
- **Language-academy neologism/slang tracking publications** — many countries have an official
  language authority (Real Academia Española, Académie française, and equivalents elsewhere) that
  publishes annual slang/neologism roundups. Authoritative and well-digitized; the genre recurs
  across many languages even though the specific institutions differ
- **Travel-guidebook "local slang" appendices** — a genre most phrasebook publishers include
  (Lonely-Planet-style); short, but usually curated for exactly the everyday/youth slang a visitor
  would actually hear

### Usage-type (authentic text, searched as an oracle corpus)

- Public internet forums, segmented by domain — this is exactly where the gamer-forum/fashion-forum/
  car-forum contrast falls out naturally; forums exist in nearly every language with meaningful
  internet penetration
- Comment sections / review sites
- Fan fiction archives and web novels (especially strong in Chinese/Korean/Japanese web-fiction cultures)
- Blogs, personal diary-style writing
- Archived text-chat logs (Discord community archives, saved Twitch/game chat)
- Crime fiction / noir (renders criminal argot in dialogue)
- YA fiction (deliberately slang-dense to read as authentic to its target age)
- Military memoirs / war fiction
- True-crime nonfiction
- Oral-history transcripts (same transcription-confidence caveat as subtitle sources — see
  [[source_reliability]])
- Screenplay/stage scripts (text, distinct from the audio/video performance)
- **TV/film scripts and transcripts — in practice, usually one of two sub-forms, not an actual
  production script:**
  - **Closed-caption/subtitle files** (`.srt`/`.vtt`) — pure text regardless of the video, so this
    sidesteps the audio/video limitation entirely. Same source type this project already handles
    for other subtitle-derived material — apply the existing `source_type` +
    `transcription_confidence` tagging convention from [[source_reliability]], since auto-captions
    can be confidently wrong.
  - **Fan-run episode-transcript wikis** — the other common text-native option for popular shows,
    independent of subtitle files.
  - A single show set in a specific world (medical drama, cop procedural, teen drama, military
    show, workplace sitcom) can supply slang for a whole domain at once via its dialogue, mapping
    directly onto Axis 1.
  - **Caveats:** availability is uneven across languages — rich fan-transcript/subtitle ecosystems
    exist for English, anime (Japanese), K-drama, and telenovelas (Spanish/Portuguese); thin for
    smaller languages. For many non-English corpora the only realistic text available may be a
    **dubbed** version of a foreign show rather than an organic local production — dubbing
    translators often sanitize or domesticate slang, so tag dubbed-source transcripts with that
    caveat, the same way translation-artifact/wrong-audience flags are already used elsewhere in
    triage.
- **Podcast transcripts** — the same move as TV subtitles, applied to a different register: many
  podcasts now publish official transcripts for accessibility. Covers long-form conversational
  speech, often topic/domain-specific (true crime, gaming, finance podcasts), with the same
  `transcription_confidence` tagging from [[source_reliability]] applying here too.
- **Court/trial transcripts** — public record in most jurisdictions, text-native. Witness/defendant
  testimony is often genuinely colloquial — a rare source of unscripted criminal-argot and everyday
  speech not filtered through an author's stylistic choices the way fiction dialogue is.
- **Stand-up comedy transcripts** — distinct from "satire and humor writing" below, which leans
  written (columns, parody); stand-up is performed, timing-dependent speech, usually captured via
  the same subtitle/fan-transcript route as TV.
- Satire and humor writing
- Classified ads / marketplace listings (commerce-specific jargon)
- Comics/manga (slang-dense, but vision-read since it's text-in-image)

---

## Cross-language applicability — a practical priority note

Not every genre transfers equally across languages. Genre-culture fit varies:

- **High cross-language universality** (expect these in nearly every literate culture's output —
  treat as the "always look for these" checklist per language): dictionaries/glossaries of slang,
  crime fiction, youth-slang pocket books, military slang references, domain-segmented internet
  forums.
- **Lower universality / culture-specific** (bonus finds, not expected baseline coverage): trucker
  CB-radio culture (fairly Anglo-specific), ballroom/drag slang (originates in a specific
  subculture, globalizing but unevenly), and other narrowly-rooted subcultures whose slang may not
  have a textual tradition outside their culture of origin.

---

## Maintenance rule

When a new source type, domain, or cross-language applicability finding turns up during real
triage/extraction work, add it here in the same session — don't let it stay implicit in one
language's triage catalog only.
