# Danish Slang Mechanics — Extraction Checklist

**Purpose:** analyze the actual mechanics of how Danish slang forms and works, using the
corpus collected in `language_corpus/Danish/` and, where useful, the grammar/vocabulary
reference in `source_reference/languages/Danish/`. Findings here are what eventual synthesis
work (deriving invented slang for the sci-fi setting) will be grounded in.

**This is research only — nothing here is canon** until worked into actual setting material by
explicit decision.

**Status legend:** `[x]` analyzed and written into its output file · `[ ]` not yet done.

**Project-relevance note.** Danish is a "second-era" (Tepenian-stage) contributing-language
candidate for the sibling `TepenianLanguage` project — its associated domain idea there is
"technical studies," grouped with Scandinavian languages generally. Triaged and extracted
2026-11-03/04. See `00_Book_Triage_Catalog.md` for the full triage and `00_RESUME_HERE.md` for the
full wave-by-wave detail, incident log, and flagship findings.

**Phase 1 status: extraction complete for the clearly-in-scope English-medium + native-literature
pool (2026-11-04).** **A standing open item blocks full Phase 1 closure: the triage catalog's §5
flags 16 Danish-medium-of-Danish files that need the user's explicit ruling before extraction —
not extracted this pass per this project's "flag, don't guess" rule. Unlike Swedish/Norwegian,
Danish's flagged pile contains NO flagship slang/idiom candidate at all — a real gap in this
corpus regardless of how that ruling goes.**

---

## Morphological typology

**Danish: fusional, North Germanic**, closely related to Swedish and Norwegian, both already in
this project. Two-gender system (common/neuter) with an enclitic definite-article suffix; V2 word
order with a documented seven-slot positional clause schema; no inflected future tense; a genuine
split-intransitive perfect-tense auxiliary selection (har/er, mirroring German/Dutch rather than
Swedish/Norwegian's uniform har); a grammaticalized motion-vs-location adverb contrast (hjem/
hjemme, ud/ude) not inherited from English; and a paternal/maternal kinship-line distinction
(farbror vs. morbror) preserved from Old Norse. See `established/001_danish_an_essential_grammar.md`
for the fullest academic treatment in this corpus.

---

## Output files — Markdown, sharded by numbered file, not JSON

**Storage model.** All extracted content — raw reference data, mechanics analysis, synthesized
results — lives as **Markdown** (occasionally `.txt`), not hand-authored JSON.

| Directory | Contents | Numbering |
|---|---|---|
| `established/` | The real Danish baseline — vocabulary/grammar tables extracted per lesson/chapter/section, per `00_Reference_Extraction_Spec.md` | `001_<label>.md`, `002_<label>.md`, ... |
| `analysis/` | Mechanics findings, one file per mechanism (or closely related group), narrative writeup + examples table | `001_<mechanism>.md`, ... |
| `synthesized/` | Derived in-universe slang output, one file per batch. **Explicitly provisional** — revise via each term's own Revision History subsection, never silent overwrite | `001_<batch>.md`, ... |

**Output files table:**

| File(s) | Contents |
|---|---|
| `established/001-004_*.md` | Reference grammars/dictionaries: Danish An Essential Grammar (1st ed. primary; 2nd ed. confirmed to add nothing new), Danish An Elementary Grammar and Reader, Mini Grammar Book English Danish, Language 30 phrase dictionary. |
| `established/005_*.md` | Colloquial Danish — the flagship slang source for this language: Unit 18's explicit, asterisk-marked coarse-vs-harmless swearword catalog, plus a 5-tier politeness scale, a liking/disliking intensity scale, and a formal/informal greeting table. |
| `established/006_*.md` | Teach Yourself Danish — full 18-unit extraction (a new PDF gotcha was found and resolved here: a text layer that reports present but returns pure unrecoverable noise, now logged in `00_Reference_Extraction_Spec.md`). Flagship: the nok/da/dog/jo/nu/vel/vist unstressed discourse-particle system, independently corroborated across three separate passes. |
| `established/007_*.md` | Danish Course Book — a Pimsleur-branded booklet (corrected from an earlier Univerb misattribution in the triage catalog). |
| `established/008-009_*.md` | Native literature: H.C. Andersen's Eventyr og Historier (representative sample of 5 tales + introduction), Grundtvig's "Danish Popular Tales" (English-medium folklore reference, isolated from its sibling Finnish/Icelandic sections in the same source epub). |

**Phase 1 totals: 9 files, ~150,600 words**, every file independently verified (12-column
structural check + placeholder-residue grep) by the orchestrating session. Full wave-by-wave
detail and the complete incident log (the Teach Yourself Danish text-layer gotcha, a Pimsleur/
Univerb branding correction, a real-time file-rewrite race between two concurrent extraction
passes that resolved cleanly to a single complete version) are in `00_RESUME_HERE.md`.

**NOT extracted — the §5 Danish-medium-of-Danish pile (16 files)**, pending the user's ruling.
This includes the Lisbet Thorborg pronunciation/spoken-language series, Kirsten Ahlburg's Parlør
dansk pair, Lise Bostrup's Aktivt/Intensivt dansk course, and 4 standalone items (incl. Jokeren and
Dansk fonetik i teori og praksis). No flagship slang/idiom title exists among them either.

---

## Field/column conventions

Same shared conventions as every other language in this project — see
`../00_Usage_Tier_Taxonomy.md`, `../../language_corpus/00_Source_Reliability_Guide.md`,
`../00_Historical_and_Geographic_Context_Guide.md`, and
`../00_Word_Concept_and_Morphological_Typology_Guide.md`.

## Graphify

This language gets its own graph, scoped to `datasets/Danish/`. Run `/graphify datasets/Danish`
next. **Before running: `cd` into `datasets/Danish/` first**, don't run graphify's own Python
calls from the repo root with only a `root=` argument.

## Mechanisms examined

- [ ] *(none yet — Phase 1 is reference extraction only; mechanics analysis (`analysis/`) hasn't
      started. Strong candidate mechanisms already surfaced incidentally during extraction and are
      ready to seed this work — see "Suggested next-session order" below)*

## Suggested next-session order

1. **Resolve the §5 Danish-medium ruling** — the largest open item for this language, though
   unlike Swedish/Norwegian it doesn't gate a flagship slang title (none exists in that pile).
2. Create real native-speaker query sheets in `grammar_logic/native_speaker_queries/` (folder does
   not yet exist) — candidates already flagged: whether *kælling* (flagged dated/offensive in
   `002`) carries the same weight in contemporary spoken Danish; the molbohistorier regional-
   mockery genre's real-world currency today.
3. Begin `analysis/` mechanics work. Strong candidates already surfaced: Colloquial Danish's Unit
   18 swearword catalog and its coarse-vs-harmless register ladder; the nok/da/dog/jo/nu/vel/vist
   discourse-particle system (corroborated three times independently — the richest single finding
   in this corpus); the hvad for en/et/nogen colloquial question-word construction; the *mon tro*
   idiom documented in its own folk-tale etymology via Grundtvig's "Mons Tro."
4. Run `/graphify datasets/Danish` once the above has produced real `analysis/` content worth
   graphing alongside `established/`.
