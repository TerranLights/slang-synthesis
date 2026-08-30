# Hungarian — Reference Material Triage Catalog

**Status: tentative — second pipeline test run, applying the refined methodology from the
Serbian/Croatian/Bosnian run.** See
`../../methodology-observations/hungarian_test_run.md` for process notes.

**Scope decision, made explicitly rather than by default:** `source_reference/languages/Hungarian/`
has **131 files, 2.6GB** — an order of magnitude larger than Serbian/Croatian/Bosnian's 9 files.
Full triage of every file was deliberately **not** attempted for this pass. The folder splits into
two clearly different kinds of content:

- **35 top-level loose files** — curated individual reference works (grammars, dictionaries,
  linguistics papers, a slang dictionary, historical works). Triaged below.
- **6 subfolders** (`Colloquial Hungarian/`, `FSI Basic Hungarian/`, `Glossika/`, `Hungarian
  Language Learning Pack (Updated)/`, `Hungarian language resources/`, `TY`/`TY Hungarian/`) — these
  look like structured audio-course packages (companion PDFs + many audio files per course) based
  on folder naming conventions, not individually triaged this pass. **Deferred, not ignored** — flag
  for a dedicated triage pass before this language's Phase 1 is considered complete.

---

## Top-level loose files — triaged

| File | Pages | Text layer? | Priority | Notes |
|---|---|---|---|---|
| `Hungarian-An-Essential-Grammar-Second-Edition-.pdf` | 317 | **Yes** (clean) | **Highest** | Rounds, *Hungarian: An Essential Grammar* (2nd ed., Routledge, 2009). Modern academic-standard grammar, explicit chapters on vowel harmony and the case system — directly agglutinative-relevant. First extraction target. |
| `ON-HUNGARIAN-MORPHOLOGY.pdf` | 158 | **Yes** (clean) | High | Academic paper specifically on Hungarian morphology — directly useful for grounding this language's typology profile beyond a generic characterization. |
| `750-Hungarian-proverbs.pdf` | 58 | **Yes** (clean) | Medium-high | Proverbs are a `literary`/idiomatic register source distinct from the grammar textbooks — useful once `established/` needs `usage_tier` variety beyond `core`. |
| `A-complete-practical-grammar-of-the-Hungarian-language-...-Historical-sketch...pdf` | 504 | **Yes** (clean) | Medium | Older (likely 19th-century) grammar — useful `attested_era` contrast against the 2009 Rounds grammar once era-dating is worth pursuing. |
| `Hungarian-An-Essential-Grammar.pdf` (1st ed.) | 269 | **No** — sampled, empty text layer even mid-document | Low | Superseded by the 2nd edition above, which has a clean text layer. Not worth vision-reading when a clean equivalent exists. |
| `Hungarian Verbs.pdf` | 140 | **No** — sampled, empty | Low-medium | Needs vision-based reading; deferred behind the Rounds grammar's own verb chapter (Chapter 4), which has a usable text layer. |
| `Magyar Szlengszótár.pdf` / `Magyar-Szlengsz-t-r.pdf` (duplicate filenames, mangled-encoding twin) | 170 | **No** — sampled, empty | **High priority despite needing vision-reading** | **This is a Hungarian slang dictionary** ("Magyar Szlengszótár" = "Hungarian Slang Dictionary") — actual slang content sitting in `source_reference/`, not a grammar reference. See the scope note below. |
| Remaining ~27 top-level files (linguistics papers on syntax/word order/intonation, historical works, an etymological dictionary, a trilingual dictionary, etc.) | — | not checked | Not triaged this pass | Deferred — flag for a follow-up triage pass. `ON-HUNGARIAN-MORPHOLOGY.pdf` and the linguistics-paper cluster (`Configurationality-in-Hungarian.pdf`, `Word-Order-in-Hungarian...pdf`, `The-Syntax-of-Hungarian...pdf`) are likely worth a look once the grammar-textbook baseline is further along. |

## Scope note: a slang dictionary inside `source_reference/`

**This is a real, unanticipated wrinkle in the Phase 1/Phase 2 boundary.** The pipeline's phases
assumed `source_reference/` holds grammar/vocabulary reference (Phase 1) and `language_corpus/`
holds slang collected via web research (Phase 2) — two cleanly separated content types. A slang
dictionary sitting in the reference folder doesn't fit either bucket cleanly: it's not
grammar/vocabulary baseline, but it's also not web-research-collected corpus. **Decision for this
pass:** treat it as a `language_corpus/Hungarian/` source once extracted (its content belongs
there, not in `established/`), but extract it from `source_reference/` where it physically lives —
the phase distinction is about *content type*, not strictly about *which folder something sits in*.
Flagged in `methodology-observations/hungarian_test_run.md` as a finding worth generalizing: check
every language's reference folder for corpus-type material hiding among grammar references, not
just at Hungarian.

## OCR/scan status

4 of the 8 individually-checked top-level files (50%) had no usable text layer, consistent with the
~56% rate found in the Serbian/Croatian/Bosnian test run — this looks like a genuine, recurring
pattern rather than a one-off. See `ROADMAP.md` Phase 1.

## Priority order chosen for this test run

1. `Hungarian-An-Essential-Grammar-Second-Edition-.pdf` — **extraction started this pass**,
   subagent-parallelized per `../00_Reference_Extraction_Spec.md`
2. `ON-HUNGARIAN-MORPHOLOGY.pdf` — deferred to a follow-up pass, flagged as directly useful for the
   typology profile below
3. `Magyar Szlengszótár.pdf` — deferred (needs vision-reading approach decided first), but flagged
   as high-value and belonging conceptually to `language_corpus/Hungarian/` once extracted
4. Everything else — deferred
