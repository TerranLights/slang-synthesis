# Swedish Phase 1 Extraction — Resume Point

**Started 2026-11-04 (overnight, unattended), per the user's explicit "full complete data-extraction
on the Scandinavian languages, continue through without me" instruction.** Scope is the "clearly in
scope" English-medium pool from `00_Book_Triage_Catalog.md` §6-§7 (Tiers 2-5) — **NOT** the §5
"flagged for your ruling" Swedish-medium-of-Swedish pile (37 files, incl. the flagship slang title
*Svenska idiom*). That pile is intentionally left unextracted pending the user's explicit ruling —
this is a standing project rule ("flag, don't guess"), not something overridden by tonight's
"continue through without me" instruction, which authorizes proceeding without pausing for
process questions, not resolving an explicitly-flagged open decision unilaterally.

**If this file still says "IN PROGRESS" when you read it, the extraction was interrupted — check
disk state in `established/` before re-dispatching anything; don't assume a wave didn't happen just
because the orchestrating session's context ended.**

## Status: FULLY COMPLETE (2026-11-04) — extraction, graphify, checklist, and cross-language
tracking docs all done. Not committed/pushed — awaiting the user's return per the standing
"ask before git operations" rule, not overridden by tonight's "continue without me" instruction.

## Wave plan (Tiers 2-5 of the triage catalog, ~67 net-unique in-scope files)

- [x] Wave 1 — Tier 2 reference grammars/dictionaries + In-Flight Swedish (text-layer titles first) — DONE, 5 files (001-005), verified 12-column + placeholder clean
- [x] Wave 2 — the two large EN-SV dictionaries (Norstedts 951p, Prismas 945p) — DONE, files 006-007,
      representative sample, verified clean. Flagship finding: cross-dictionary register-tag
      disagreement on skit-/skita cluster; jävla only cross-referenced in one dictionary, absent as
      headword in the other's sampled range — candidate for deeper follow-up later.
- [x] Wave 3A — Tier 3 courses, originally briefed as text-layer (Colloquial Swedish x2, TY Speak
      Swedish with Confidence + Booklet, Glossika 1-3, Beginning Swedish 1939) — DONE, files
      010, 011a-c, 012-014, 017a-c, 018a-c (renumbered from 008/009, see incident log), verified
      12-column + placeholder clean. Two of the seven sources turned out NOT to have real text
      layers despite the brief (TY Speak Swedish with Confidence main book, all 3 Glossika
      levels) — handled via vision-reading (full 75-page read for Confidence; representative
      ~100-180-triplet samples per Glossika level, each sample spread evenly across the full
      ~368-page range). See incident log for the new PDF-gotcha and the renumbering collision.
      Flagship findings: Colloquial Swedish 1996 & 2007 both have dedicated, explicitly-labeled
      "Slang" glossary sections (2007's especially rich — ~49 items incl. a derogatory-tagged
      term and taboo-intensifier-prefix calibration notes); Beginning Swedish (1939) preserves a
      full pre-1940s-reform literary plural verb conjugation plus a productive e-subjunctive mood,
      both essentially extinct in modern standard Swedish and not found in any other source
      extracted so far; the "Confidence Booklet" turned out to be the same book's own print-
      imposition front/back matter, not an independent companion phrasebook as briefed.
- [x] Wave 3B — Tier 3 courses, vision-required (Teach Yourself Swedish Croghan 1995/96 → 008,
      Teach Yourself Swedish McClean 1947 → 009, FSI Swedish Basic Course 703p → 015a-c, Advanced
      Spoken Swedish 85p → 016) — DONE, verified 12-column + placeholder clean by the orchestrating
      session directly (ran concurrently with 3A; no separate self-report captured, but files
      checked independently). FSI (015a-c) is an honestly-flagged non-redundant-supplement sample,
      not exhaustive — its grammar overlaps almost entirely with 008/009 already extracted;
      captured only FSI's distinctive sociolinguistic commentary, false-friend warnings, and
      genuinely new vocabulary. **Note: "Beginner's Swedish" (136p) from the original wave brief
      does not appear to have been extracted — check for a gap before closing out this language.**
- [x] Wave 4A — Tier 4 culture/history (Historical Dictionary of Sweden, Culture and Customs of
      Sweden) — DONE, files 035-036 (both confirmed real text layers, no vision-reading, no
      font-substitution cipher), verified 12-column + placeholder clean. Neither book has a
      dedicated language/dialect chapter (035 is an A-Z historical/biographical encyclopedia;
      036 is an 8-chapter cultural narrative with no language chapter) — content was found via
      targeted search + the Literature/Performing Arts chapters, not a chapter-by-chapter read.
      Flagship findings: 035's SWEDISH LANGUAGE entry explicitly names the Svea-dialect-of-
      Stockholm + Göta-dialect basis of the written standard (first source in this pass to name
      specific standard-forming dialects) plus a clean Latin→German→French→English loanword-wave
      timeline with lexical examples; 036 found the Rinkebysvensk/förortsvenska/shobresvenska
      immigrant-multiethnolect cluster (named, literarily controversial per the source) and a
      skånska-as-performer-identity dialect marker in hip-hop. Neither source contains any taboo/
      profanity vocabulary (checked directly, no hits) or naming-custom content beyond a single
      "name day" mention — both absences recorded as confirmation these are not slang sources.
- [x] Wave 4B — Tier 5 graded readers/native literature (Lindgren x9, Moomin, Holmström, Wallström,
      Alander x2, The Svenssons) — DONE, 2026-11-04. All 15 files (020-034) written and independently
      verified by the orchestrating session (not just subagent self-report): 12-column vocabulary
      tables confirmed on every file, zero leftover template placeholders, total **42,916 words**.
      Only one of the 15 sources (031, Wallström) had a real text layer; the other 14 were vision-read
      (DJVU via `ddjvu`+PIL, PDF via `pdftoppm`) via representative sampling, not exhaustive
      line-by-line transcription, per the usage-corpus extraction approach. Several two-printed-
      pages-per-image spread scans were found and empirically confirmed rather than assumed (020-028,
      030, 032); no genuinely printed/handwritten-marginalia confusion survived into any file (a few
      were found — Pippi (023) and The Svenssons (034) — and correctly excluded, flagged in-file).
      Two sources turned out not to be what their filenames implied: 029 is a 1990s TV-tie-in
      picture-book adaptation of the Moomin story, not Jansson's original novel (flagged in-file,
      scope corrected); 031 ("Då hon dog") is a first-person grief memoir, not a crime novel as
      briefed (flagged in-file, extraction reoriented to what the source actually offers).
      - 020 Lillebror och Karlsson på taket — 2,838w. Productive "världens bästa [X]" self-praise
        template; coined insult compounds (*lilla snaskgris*, *tjurbock*); eye-dialect "me'" for
        *med* in Karlsson's dialogue only. Marginalia found (library stamp, pencil underline,
        handwritten page-count note) and excluded.
      - 021 Karlsson på taket flyger igen — 2,636w. "Världens bästa tallrikskastare"-type pattern
        confirmed recurring; *husbocken* triple-pun nickname; consistent `dom`/`sej`/`mej`/`dej`
        spoken-register spelling in the narration itself, with an apostrophe-clipping escalation
        device ("me'") reserved for Karlsson's peak agitation.
      - 022 Karlsson på taket smyger igen — 2,715w. Self-praise catchphrase confirmed a third time,
        near-verbatim across 3 sampled pages — now a confirmed productive cross-book pattern, not a
        one-off. Karlsson's self-aware word-mangling tic caught explicitly ("Tirritera och filura
        och figurera"). Rich insult/nickname register (*flygande tunna*) and closing nonsense-song
        fragment.
      - 023 Pippi Långstrump går ombord — 3,680w. Nonce word-coinage as Pippi's idiolect marker
        (*pluttifikation*, "U buj uje muj!"); ironic register-inversion comedy; archaic plural-verb
        grammar fossilized only inside a quoted song; outdated colonial-era term *negerkung*
        flagged taboo/archaic. Two marginalia instances found and excluded.
      - 024 Kalle Blomkvist och Rasmus — 2,158w. Gang-rivalry pun nickname *rödingar* ("chars," vs.
        *röd* "red") for the first time; invented nonce word *Stormumriken*; productive `-unge`/
        `-valp` dismissive diminutives; villain's mild taboo oath *Jag ger tusan i...*.
      - 025 Mästerdetektiven Blomkvist — 3,142w. **Flagship finding**: "Vita Rosen"/"Röda Rosen" gang
        rivalry with sustained mock-military register (*spanare*, *högkvarter*, *kringgående
        rörelse*, *överrumpling*) — register-inversion mechanism, kids using earnest institutional
        jargon at play. Dialectal/phonological layering (*Di Röa kommer!*) beyond the baseline
        `mej`/`dej`/`dom` tier. Productive *tjuv-* "secretly/illicitly" slang-forming prefix.
      - 026 Mästerdetektiven Blomkvist lever farligt — 2,668w. Gang-rivalry/mock-military register
        **confirmed recurring a third time** (now a genuine productive series-wide pattern, not
        isolated) — *högkvarter*, *trupper*, *anfall*, *retirerade*, mock-legal war-declaration
        parody. Insult *luspudel*; euphemistic exclamations (*sjutton*, *sabla*, *Du store
        Nebukanesar*).
      - 027 Emil i Lönneberga — 2,699w. **Flagship regional finding**: narrator explicitly
        self-names Smålandsdialekt ("Och så talade han småländska... Det gör man i Småland") — one
        of the cleanest self-marked dialect passages found anywhere in the project. Phonetic dialect
        spelling in quoted speech (*mi mysse*, *te pojk*) vs. standard narration. Idiom *leva
        loppan*; flagship epithet *illbatting*.
      - 028 Vi på Saltkråkan — 3,281w. Explicitly in-text-flagged child slang (*bongalo*, called
        "fånigt" by an adult character). Clean age-graded register ladder across 4 distinct voices
        (blunt child / ironic teen / performative adult / old-fashioned rural-elderly). Archipelago/
        nautical vocabulary cluster (*havsbandet*, *mistlur*, *stäva*) distinct from Alander's later
        maritime cluster in 033.
      - 029 Mummintrollets första vinter — 1,942w. **Scope-corrected**: this is a short 1990s
        TV-tie-in picture-book adaptation ("Kronböckerna" series, after Jansson, not Jansson's own
        novel text) — flagged explicitly, not treated as primary Jansson prose. Productive vocative
        insult frame "din fegis!" (din + noun, cf. din idiot); comic-book-style onomatopoeia
        register shift ("SVISCH! KRASCH! BANG!").
      - 030 Johanna Holmström — Tvåsamhet — 2,149w. First genuinely contemporary/adult-register
        source in the wave (2005 short-story collection, Finland-Swedish). Taboo/colloquial cluster
        from a bar-fight scene (*fega jävel*, *kärring*, *hagga*); frozen archaic-subjunctive oath
        *förbanne mig* still live as a modern intensifier; title word itself is a productive
        *-samhet* abstract-noun derivation coined on a numeral.
      - 031 Tord Wallström — Då hon dog — 4,021w. **Genre-corrected**: a grief memoir, not a crime
        novel as briefed — flagged explicitly. Hospital/hospice institutional register (definite-
        article ward names, two-tier nursing titles); a striking unpunctuated delirious-dialogue
        passage capturing real spoken discourse particles (*jaha*, *jodå*, *jättefint*); death-
        euphemism idiom *andra stranden* / *gå över* recurring across two speakers.
      - 032 Rainer Alander — Små stycken av Stockholm — 2,639w. Genuine Stockholm slang/drug argot
        in naturalistic dialogue (*lapplisa*, *pundare*, *rövslickeri*); explicit cross-language
        commentary on Finnish *rakas* sounding "like a crow" to a Sweden-Swedish ear; mixed register
        confirmed (literary narration vs. taboo/regional dialogue, explicitly named *norrländska*).
      - 033 Rainer Alander — Mellan Stockholm och Åbo — 3,452w. **Flagship Finland-Swedish finding**:
        explicit narrator metalinguistic commentary distinguishing Finland-Swedish intonation from
        the Sweden-Swedish "finsk brytning" outsider label. Productive taboo-intensifier family
        (*jävla*, *din jävel*); maritime/shore-leave vocabulary cluster distinct from 028's
        archipelago set; deliberately archaic plural copula *äro* used ironically alongside now-
        dated ethnonyms (flagged, not normalized).
      - 034 The Svenssons (Texts 1-22) — 2,896w. Pedagogically-controlled graded reader, as briefed
        (mostly `core` tier) — but one genuine colloquial-register spike found: Text 11 clusters
        youth slang built on productive intensifying prefixes *ur-*/*sten-* (*urtrist*, *stenkul*,
        *uruselt*), plus an explicit in-text register-correction exchange (child says "jumpa," adult
        corrects to "gymnastik"). One marginalia fragment found and excluded.
      **Cross-book pattern (highest-confidence finding of the whole wave)**: Karlsson's "världens
      bästa [X]" self-praise template recurs near-verbatim across all 3 trilogy books (020-022) —
      confirmed independently by 3 separate subagents who hadn't seen each other's output, making
      this a genuine productive character-idiolect pattern rather than a coincidental one-off
      read. Second-strongest cross-book pattern: the "Vita Rosen"/"Röda Rosen" gang-rivalry mock-
      military register recurs across all 3 Blomkvist books (024-026).
- [x] Wave 4A — DONE (files 035-036, see above)
- [x] Wave 4B — DONE (files 020-034, 15 titles, 42,916 words, see sub-agent report)
- [x] Structural verification of every file (12-column + placeholder check) — DONE by the
      orchestrating session directly across all 44 established/ files, zero defects found
      (two grep hits on "Lesson XXX/XXXI/XXXII" Roman numerals confirmed benign false positives)
- [x] `/graphify datasets/Swedish` rebuild — DONE. 481 nodes, 389 edges, 6 hyperedges, 111
      communities. Health check clean: 0 missing/dangling/self-loop edges, 2 negligible undirected
      collapses out of 389 raw edges. HTML export, manifest, cost tracker, cleanup all done.
- [x] Extraction checklist created (`00_Extraction_Checklist.md`)
- [ ] Cross-language tracking docs updated (LANGUAGE_INDEX.md, 00_Analysis_Index.md, ROADMAP.md) —
      pending, will batch with Norwegian/Danish at the end of the overnight run
- [ ] Commit (do NOT push without asking — standing rule, not overridden by tonight's instruction)

## SWEDISH IS FULLY DONE (extraction + graphify). Moving to Norwegian next.

## Final totals (2026-11-04)

**44 established/ files, ~335,000 words.** Every file independently structurally verified by the
orchestrating session. Flagship findings across the whole extraction: dedicated "Slang" glossaries
in both Colloquial Swedish editions; a cross-dictionary register-tag disagreement on the skit-/
skita cluster (Wave 2); a pre-1940s-reform literary plural verb conjugation and e-subjunctive mood,
both extinct in modern standard Swedish (Johnson 1939); the Rinkebysvensk/förortsvenska immigrant
multiethnolect register, explicitly named and politically contentious per Culture and Customs of
Sweden; the recurring "världens bästa [X]" self-praise idiolect template across all three Karlsson
books, independently confirmed by three different subagents; genuine Stockholm slang/drug argot in
Alander's travel essays. The §5 Swedish-medium pile (37 files, incl. the flagship *Svenska idiom*
slang dictionary) remains un-extracted pending the user's ruling — see above.

## Explicitly NOT extracted this pass

- §5's 37 Swedish-medium-of-Swedish files (incl. flagship slang title *Svenska idiom: 3.500
  vardagsuttryck*) — needs the user's explicit ruling first.
- Old Swedish (Noreen 1904 grammar) — different historical stage, German-medium, excluded on both
  grounds per the triage catalog §1b.
- Archer's *Till varje pris* — copyrighted commercial translation, held per §6's copyright note.
- Harry Potter Swedish translation + its audiobook — copyrighted, excluded in triage §3.
- All excluded/non-content/audio items per the triage catalog §1-§3.

## Incident log

- **2026-11-04, Wave 3A numbering collision with a concurrently-running Wave 3B.** Wave 3A's
  dispatch brief said to start numbering at `008` (correct per the state of `established/` at
  dispatch time). A separate, concurrently-running process (apparently Wave 3B, not coordinated
  with Wave 3A in real time) independently also started at `008`/`009` for *Teach Yourself Swedish
  Croghan* and *Teach Yourself Swedish McClean 1947*. No files were actually overwritten (Wave 3A's
  Colloquial Swedish 1996/2007 extractions split into `a`/`b`/`c` parts immediately, which happened
  to avoid an exact filename clash), but two different titles briefly shared each of the `008` and
  `009` number prefixes. **Resolved by renumbering Wave 3A's own files** (the less invasive fix,
  since Wave 3B's plain `008`/`009` files were already complete and untouched): `008a/b/c_colloquial_
  swedish_1996.md` → `017a/b/c_colloquial_swedish_1996.md`; `009a/b/c_colloquial_swedish_2007.md` →
  `018a/b/c_colloquial_swedish_2007.md` (all internal self-references between the two editions'
  files updated to match; verified no stale `008`/`009` references remain). **Takeaway for future
  multi-wave dispatches on this project: check the full `established/` directory listing
  immediately before dispatching, not just trust a previously-read file count, when more than one
  wave for the same language may be in flight at once** — this is the first time two waves for the
  same language actually overlapped in real time.
- **2026-11-04, new PDF-extraction gotcha found (candidate addition to
  `00_Reference_Extraction_Spec.md`'s gotcha catalog): vector-outline text with no character/
  ToUnicode mapping at all.** Found independently on *TY Speak Swedish with Confidence* (main
  book) and all three *Glossika Swedish* levels. Distinct from every PDF gotcha already documented:
  not a decodable font-substitution cipher (no character mapping exists to decode — `pdffonts`
  shows fonts present but unmapped), and not the "target-language content embedded as per-word/
  per-page raster images" pattern either (`pdfimages -list` returns zero images on content pages).
  `pdftotext` returns near-empty output despite `pdfinfo` reporting the PDF as having fonts/text
  objects. The content is visually clean and fully legible when pages are rendered to images via
  `pdftoppm` — it is genuinely drawn as vector outline paths, with no recoverable character data at
  all. **Diagnostic recipe to confirm this specific case**: `pdftotext` near-empty AND `pdfimages
  -list` empty AND `pdftoppm` render shows real legible content → vision-reading is the only option,
  don't waste time hunting for a decode table.
