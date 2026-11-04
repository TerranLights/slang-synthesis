# Norwegian Slang Mechanics — Extraction Checklist

**Purpose:** analyze the actual mechanics of how Norwegian slang forms and works, using the
corpus collected in `language_corpus/Norwegian/` and, where useful, the grammar/vocabulary
reference in `source_reference/languages/Norwegian/`. Findings here are what eventual synthesis
work (deriving invented slang for the sci-fi setting) will be grounded in.

**This is research only — nothing here is canon** until worked into actual setting material by
explicit decision.

**Status legend:** `[x]` analyzed and written into its output file · `[ ]` not yet done.

**Project-relevance note.** Norwegian is a "second-era" (Tepenian-stage) contributing-language
candidate for the sibling `TepenianLanguage` project — its associated domain idea there is
"technical studies," grouped with Scandinavian languages generally. Triaged and extracted
2026-11-03/04. See `00_Book_Triage_Catalog.md` for the full triage and `00_RESUME_HERE.md` for the
full wave-by-wave detail, incident log, and flagship findings.

**Phase 1 status: extraction complete for the clearly-in-scope English-medium + native-literature
pool (2026-11-04).** **A standing open item blocks full Phase 1 closure: the triage catalog's §5
flags 41 Norwegian/German/Portuguese-medium-of-Norwegian files (incl. THREE flagship slang/idiom
candidates: `Hva vi sier - og hva vi mener`, `Katta i sekken og andre uttrykk`, `Sånn kan du si
det`) that need the user's explicit ruling before extraction — not extracted this pass per this
project's "flag, don't guess" rule. If that ruling goes against extraction, this project ends up
with zero Nynorsk-standard material, since the only Nynorsk-medium sources in the whole Norwegian
stash sit inside that same flagged pile.**

---

## Morphological typology

**Norwegian: fusional, North Germanic**, closely related to Swedish and Danish, both already in
this project. Shares the double-definiteness system (bound suffix + preposed article when
adjective-modified) and the historical 3-to-2 noun-gender collapse trend documented for Swedish,
though Norwegian's two written standards (Bokmål and Nynorsk) complicate any single typological
statement — Bokmål is closer to Danish in its written conventions, Nynorsk closer to the western
dialects' own historical forms. The tonal pitch-accent system (Accent 1 / Accent 2) is shared with
Swedish; see `established/003_phonology_of_norwegian.md` for the fullest academic treatment in this
corpus. **This project's Norwegian corpus is almost entirely Bokmål** — see the standing Nynorsk gap
noted above.

---

## Output files — Markdown, sharded by numbered file, not JSON

**Storage model.** All extracted content — raw reference data, mechanics analysis, synthesized
results — lives as **Markdown** (occasionally `.txt`), not hand-authored JSON.

| Directory | Contents | Numbering |
|---|---|---|
| `established/` | The real Norwegian baseline — vocabulary/grammar tables extracted per lesson/chapter/section, per `00_Reference_Extraction_Spec.md` | `001_<label>.md`, `002_<label>.md`, ... |
| `analysis/` | Mechanics findings, one file per mechanism (or closely related group), narrative writeup + examples table | `001_<mechanism>.md`, ... |
| `synthesized/` | Derived in-universe slang output, one file per batch. **Explicitly provisional** — revise via each term's own Revision History subsection, never silent overwrite | `001_<batch>.md`, ... |

**Output files table:**

| File(s) | Contents |
|---|---|
| `established/001-003_*.md` | Reference grammars: Norwegian Verbs and Essentials of Grammar (Janus), Practical Norwegian Grammar (Strandskogen, cross-checked against the Essential Grammar edition), The Phonology of Norwegian (Kristoffersen). |
| `established/004-006_*.md` | Dictionaries: Norwegian-English Dictionary (Haugen, Bokmål+Nynorsk, sampled), Engelsk-Norsk Ordbok (Kirkeby, Bokmål-only, sampled), Berlitz Language 30 phrase dictionary. Flagship: cross-dictionary register-tag systems (pop./dial./derog./fam. vs. S/RS/T/neds./vulg.), incl. a double-tagged ethnic slur the dictionary itself flags as offensive. |
| `established/007-017_*.md` | Courses: reading booklets, Teach Yourself ×3, Colloquial Norwegian (flagship — full Lesson 18 taboo/swearing set), Norwegian in Three Months, Norwegian in 10 Minutes a Day, Linguaphone Norsk Kurs+Handbook, Instant Norwegian, Self-instruction in Bokmål, Så snakker vi Norsk. |
| `established/018-022_*.md` | Native literature: Norske Folke-Eventyr (Asbjørnsen & Moe) vol. I/II, Jomfruen på Glassberget (confirmed a 1909/1943-revised selection, not raw 19th-c. text), Kurt blir grusom (Erlend Loe — flagship modern-register source), Framtidslandet (unexpected Bokmål/Nynorsk code-switching anthology). |
| `established/023_*.md` | Historical Dictionary of Norway — the LANGUAGE entry covers the Aasen/Landsmål vs. Knudsen/Riksmål debate and the full 1885-2005 reform timeline. |

**Phase 1 totals: 36 files (`001`-`023`, incl. lettered sub-parts), ~370,700 words**, every file
independently verified (12-column structural check + placeholder-residue grep) by the orchestrating
session. Full wave-by-wave detail and the complete incident log (a 10-file Faroese
misidentification caught at triage, marginalia exclusions, source-text-layer corrections) are in
`00_RESUME_HERE.md`.

**NOT extracted — the §5 Norwegian/German/Portuguese-medium pile (41 files)**, pending the user's
ruling. This includes all three flagship slang/idiom candidates named above, the VOX/Cappelen
NFU/SFI immigrant-course ladder, the major academic reference grammar (*Norsk
Referansegrammatikk*), and all of this stash's Nynorsk-medium material.

---

## Field/column conventions

Same shared conventions as every other language in this project — see
`../00_Usage_Tier_Taxonomy.md`, `../../language_corpus/00_Source_Reliability_Guide.md`,
`../00_Historical_and_Geographic_Context_Guide.md`, and
`../00_Word_Concept_and_Morphological_Typology_Guide.md`.

## Graphify

This language gets its own graph, scoped to `datasets/Norwegian/`. Run `/graphify datasets/Norwegian`
next. **Before running: `cd` into `datasets/Norwegian/` first**, don't run graphify's own Python
calls from the repo root with only a `root=` argument.

## Mechanisms examined

- [ ] *(none yet — Phase 1 is reference extraction only; mechanics analysis (`analysis/`) hasn't
      started. Strong candidate mechanisms already surfaced incidentally during extraction and are
      ready to seed this work — see "Suggested next-session order" below)*

## Suggested next-session order

1. **Resolve the §5 Norwegian/German/Portuguese-medium ruling** — the single largest open item for
   this language, and the one with the highest stakes of any Scandinavian-family language in this
   project: it gates all three flagship slang/idiom dictionaries AND all Nynorsk-standard coverage.
2. Create real native-speaker query sheets in `grammar_logic/native_speaker_queries/` (folder does
   not yet exist) — candidates already flagged: the Fante- root's real-world ethnic-slur weight
   (flagged twice in the folktale corpus, worth a sensitivity check before any synthesis use);
   whether Framtidslandet's unmarked Bokmål/Nynorsk code-switching is a stylistic choice or
   something a Nynorsk-speaking reader would read differently.
3. Begin `analysis/` mechanics work. Strong candidates already surfaced: the full Lesson 18
   taboo/swearing set in Colloquial Norwegian plus its note on Norwegians using borrowed English
   obscenities unaware of their offensiveness; the register-tag systems in both big dictionaries;
   Kurt blir grusom's `kjempe-` intensifier prefix and taboo/slang verb set; the cross-folktale
   stock-epithet naming system (Mikkel=fox, Bamse=bear, Askeladden=hero).
4. Run `/graphify datasets/Norwegian` once the above has produced real `analysis/` content worth
   graphing alongside `established/`.
