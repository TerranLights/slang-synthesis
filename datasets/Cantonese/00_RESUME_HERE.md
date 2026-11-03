# Cantonese Phase 1 Extraction — Resume Point

**Status, 2026-11-02: Wave 1 COMPLETE (dispatched manually, not via cron — see incident log). Waves 2-5 not started.**

**Pacing constraint (explicit, user-set 2026-10-30):** ONE WAVE PER DAY, no exceptions, due to
token-burn concerns — see memory `cantonese_extraction_plan`. **Do not dispatch more than one wave
in a single day. After a wave completes and is verified, STOP for the day** — even though this
project's general `wave_dispatch_no_confirmation` convention normally says to chain into the next
wave once authorized. This Cantonese plan is the standing exception to that default.

**Source:** `/media/kuroskalacs/Home-Theater/w-lang/Cantonese/` (external drive — confirm mounted
before dispatch; confirmed mounted as of 2026-11-02 12:11 MST).

**Triage reference:** `datasets/Cantonese/00_Book_Triage_Catalog.md` — full file list, exclusions,
duplicate resolution, OCR status, and the 5-tier priority order this wave plan maps from.

**This is Cantonese's first-ever Phase 1 extraction.** No `established/` folder exists yet —
sibling numbering starts at `001`.

---

## Wave plan (one tier per wave, per the triage catalog's existing priority order)

| Wave | Tier | Files | Status |
|---|---|---|---|
| **1** | Tier 1 — flagship | `09.A Dictionary of Cantonese Slang.pdf` (sampled), `07.Cantonese A Comprehensive Grammar.djvu` (full) | **DONE (2026-11-02) — 28 files, 001-028, ~123,229 words** |
| 2 | Tier 2 — high priority, clean text | `04.Basic Cantonese A Grammar and Workbook.pdf`, `03.Colloquial Cantonese 2010.pdf`, `06.Cantonese - Languages of the World.pdf` | NOT STARTED |
| 3 | Tier 3 — medium-high, vision course/grammar supplements | `05.Intermediate Cantonese A Grammar and Workbook.pdf`, `01.Teach Yourself Cantonese.pdf`, `11.Gateway to Cantonese.djvu` | NOT STARTED |
| 4 | Tier 4 — medium, academic/sociolinguistic | `13.Language Relations in Guangzhou.pdf`, `12.Hong Kong (Language and National Identity in Asia).pdf` | NOT STARTED |
| 5 | Tier 5 — low priority | `08.Lonely Planet Cantonese Phrasebook.pdf`, `00.Cantonese I Reading Booklet.pdf`/`.doc`, 1994 Colloquial Cantonese (non-redundant supplement only) | NOT STARTED |

---

## Wave 1 — exact task definition

**Files (2):**
1. `09.A Dictionary of Cantonese Slang.pdf` (Hutton & Bolton, 509pp, image-only scan, vision-read).
   **Representative A-Z sample, not exhaustive** — same discipline as Korean's/Spanish's/Hawaiian's
   oversized dictionaries. Content-type note from the triage catalog: this is conceptually
   `language_corpus/Cantonese/` material (a slang dictionary), routed the same way Hungarian's
   *Magyar Szlengszótár* and Korean's register-tagged dictionary entries were handled — flag/tag
   accordingly in the extracted file's frontmatter even though it physically lands in
   `established/`.
2. `07.Cantonese A Comprehensive Grammar.djvu` (Matthews & Yip, 226 djvu page-units, **each unit is
   a 2-printed-page spread** — confirmed by direct render, ~450 actual printed pages). **Use the
   djvu, not the lower-fidelity `.pdf` twin** (the pdf packs 4 printed pages per image and has
   effectively zero real text). Full extraction, not sampled — this is the sibling
   TepenianHawaiian project's named flagship grammar reference.

**Guardrails (standard, apply to every dispatch):**
- Anti-forking / merge-ownership: each dispatched subagent owns a disjoint file range; no subagent
  should create, rename, or merge another subagent's output files.
- Subagents in this environment cannot use the Write tool — must write incrementally via
  `cat > FILE << 'EOF' ... EOF` bash heredocs.
- 12-column `established/` table header is mandatory. Verify after every subagent returns with
  `grep -m1 "^|---" FILE | awk -F'|' '{print NF-2}'` — must print 12. Do not trust a subagent's own
  "done" self-report without this check.
- Placeholder-residue grep after every file (`TODO`, `TBD`, `XXX`, `[fill in]` — guard against the
  Spanish false-positive where "todo" is also a real Spanish word).
- Sibling-number reservation: this is the first wave for this language, so reserve `001` onward
  sequentially per dispatched file/part; if a file needs splitting into letter-suffixed parts
  (likely for the 509pp dictionary sample and the ~450pp grammar), reserve the full block up front
  before dispatching.
- `07`'s djvu needs `ddjvu` rendering at the confirmed 2-pages-per-image density — do not assume a
  different density without re-verifying empirically per the project's running pages-per-image
  gotcha list.

**Also create during Wave 1 (per the triage catalog's "Open items" note):** a native-speaker query
folder for Cantonese — no such folder exists yet, and this project's standing convention is to
create it at Phase 1 start, for prosody/tone-sandhi/register judgments only a speaker can settle
(the Comprehensive Grammar's tone-sandhi content in particular is likely to generate real candidate
questions for it).

**After Wave 1 completes and is structurally verified:**
- Update this file's Wave 1 row to DONE, with actual file count/word count.
- Update `datasets/Cantonese/00_Extraction_Checklist.md` (create if it doesn't exist yet, same
  format as every other language's checklist).
- **Do NOT update `LANGUAGE_INDEX.md` / `00_Analysis_Index.md` / `ROADMAP.md` / the Language Ledger
  artifact yet** — those get updated once Cantonese reaches full Phase 1 complete (all 5 waves),
  not after a single wave, consistent with how every other language's cross-tracking-doc updates
  have been timed in this project.
- **Do NOT commit or push without asking the user first.**
- **Do NOT dispatch Wave 2.** Stop for the day — one wave per day is a hard constraint here, not the
  project's usual no-pause-between-waves default.

---

## Incident log

1. **Cron job didn't fire; dispatched manually instead.** A one-shot cron job was scheduled for
   ~5:03pm 2026-11-02. By 5:58pm it still hadn't fired (still listed pending in `CronList`, ~55 min
   late with no explicit lateness bound documented for one-shot jobs). User asked to trigger
   manually; the cron job was cancelled and Wave 1 was dispatched directly in the live session
   instead. No root cause determined — flagging in case this recurs for a future scheduled wave.
2. **5 of the first 20 dispatched subagents (all 5 dictionary-sample chunks) stopped prematurely**,
   having started the `pdftoppm`/render command and then waiting for a "background monitor
   notification" that would never arrive — subagents don't have the same task-notification
   mechanism the orchestrating session does. All 5 were resumed via `SendMessage` with an explicit
   instruction to run the render as a normal foreground/blocking call and continue synchronously;
   all 5 then completed successfully. **For future dispatches: explicitly instruct subagents that
   render commands must run as a normal foreground bash call they wait on directly, not something
   to background and poll/monitor for.**
3. **`ddjvu -format=png` is not supported by the installed djvulibre version** in this environment
   (confirmed by multiple independent subagents) — only pbm/pgm/ppm/pnm/rle/tiff/pdf are. Workaround:
   render to `-format=ppm`, then convert to PNG via Python/PIL. **Promote this to the project's
   running gotcha list** (alongside the pages-per-image density gotcha) for any future djvu-based
   dispatch.
4. **Shared scratchpad render-directory collisions between parallel subagents**, recurring across
   at least 3 Batch 1 agents (units 11-20, 31-40, 51-60) — sibling subagents rendering into the same
   generic filename pattern in the shared scratchpad overwrote/consumed each other's intermediate
   files. All 3 self-recovered by rendering into an isolated subdirectory and re-verifying content
   before extraction; no data was lost, but one agent (units 31-40) briefly deleted another's
   intermediate `.ppm` files during cleanup (confirmed harmless — their `.png` conversions already
   existed). **Fixed for Batch 2**: every dispatch prompt explicitly assigned each chunk its own
   isolated render subdirectory up front. No collisions recurred in Batch 2. **Promote this to the
   project's standing dispatch-guardrail language for any future multi-chunk vision-render wave.**

**Wave 1 outcome:** 28 files (`001`-`028`), ~123,229 words, all passing the 12-column structural
check with no placeholder residue, verified independently by the orchestrating session (not just
trusted from subagent self-reports). Dictionary sample: 5 files, ~506 entries across a representative
spread (front matter/A-section, D-E, J-section, NG-P, back matter). Grammar: 23 files covering the
entire book front-to-back (front matter → Ch.1 Phonology → ... → Ch.21 Numerals/Times → Appendix →
Notes → Glossary → References → Index), each with real grammatical-analysis prose plus a vocabulary
table, and several flagship slang/register findings worth carrying into the `analysis/` layer later
(classifier-mismatch register inversion, the *gwái*/*séi* taboo-intensifier system, the "water" =
money slang register, several book-flagged idioms). The native-speaker query folder was created
(`grammar_logic/native_speaker_queries/README.md`, copied from the project template) but is still
empty — no actual query sheets written yet. The grammar's tone-sandhi/register material flagged
throughout Wave 1 (e.g. the particle-tone pragmatic-force mapping in units 171-180, the *jēk*
age/gender-register note in 181-190) are good candidates for the first real query sheets once the
`analysis/` layer starts.
