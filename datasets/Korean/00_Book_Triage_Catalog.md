# Korean — Reference Material Triage Catalog

**Status: full triage complete, 2026-09-09.** Korean is one of the 43 Inner Tepenia GDD
Gini-index high-priority languages (South Korea, ~26M effective) — see `../../LANGUAGE_INDEX.md`.
`source_reference/languages/Korean/` is ~532 MB, 17 real files (16 PDFs + 1 DJVU) across a mix of
top-level files and 3 subfolders, all text-oriented (no audio/video — this folder never had any).

**Tooling note:** several files sit inside subfolders (`Colloquial Korean/`, `Teach Yourself
Korean/`, `The Sounds of Korean - A Pronunciation Guide/`) rather than at the top level — use
`find -printf '%p'` (full relative path), not just `%f` (basename), or numbered-prefix files
inside subfolders get misattributed to the wrong title.

---

## Full file list — triaged

| File | Pages | Text layer? | Priority | Notes |
|---|---|---|---|---|
| `04.Basic Korean a grammar and workbook.pdf` | 257 | **Yes** (clean) | **Highest** | Core grammar reference, first of what looks like a graded series (Basic → Intermediate → Continuing, numbered 04/05/07 in this collection). First extraction target. |
| `05.Intermediate Korean a grammar and workbook.pdf` | 289 | **Yes** (clean) | **Highest** | Direct sequel to Basic Korean, same series. |
| `07.Continuing Korean.pdf` | 451 | **Yes** (clean) | High | Third/continuing volume in the same graded series — largest of the three. |
| `11.Using Korean a guide to contemporary use.pdf` | 337 | **Yes** (clean) | **High — register focus** | Title itself signals contemporary/colloquial usage — directly matches this project's stated preference for register-diverse chapters over pure foundational grammar. |
| `12.The Korean language structure use and context.pdf` | 202 | **Yes** (clean) | High | Linguistic-description volume — likely strong for typology profile and structural analysis beyond a teaching grammar. |
| `10.Intermediate college Korean.pdf` | 376 | **Yes** (clean) | Medium-high | Another intermediate-level textbook — likely redundant with Basic/Intermediate Korean's core grammar; apply the non-redundant-supplement pattern. |
| `0.1The Sounds of Korean A Pronunciation Guide.pdf` (in `The Sounds of Korean - A Pronunciation Guide/`) | 141 | **Yes** (clean) | Medium-high | Dedicated phonology reference — pairs with the typology profile the way Siptár & Törkenczy's *Phonology of Hungarian* did for Hungarian. |
| `Teach Yourself Korean.pdf` (in `Teach Yourself Korean/`) | 139 | **Yes** (clean) | Medium-high | Full course, same title-type that worked well for both SCB and Hungarian. A companion 2-page scan (`Pages 110-111 224-225.pdf`, same folder) has no text layer — check whether it's patching pages the main scan is missing/damaged, extract those 2 pages via vision if so. |
| `0.2Korean Through English 1.pdf` | 144 | **Yes** (clean) | Medium | Course book. |
| `0.3Active Korean 1.pdf` | 151 | **Yes** (clean) | Medium | Course book. |
| `15.In Flight Korean.pdf` | 20 | **Yes** (clean) | Low | Very short phrasebook — low yield, quick to finish regardless. |
| `Colloquial Korean.pdf` (in `Colloquial Korean/`) | 143 | No | Medium — vision-read | Course book; a second, apparently different/updated edition sits alongside it (see below) — check for redundancy before extracting both in full. |
| `Colloquial Korean the complete course for beginners.pdf` (in `Colloquial Korean/`) | 289 | No | Medium — vision-read | Longer than the other "Colloquial Korean" file in the same folder — likely a full edition vs. an abridged/older one. Triage which is primary before dispatch. |
| `13.Korean grammar for international learners.pdf` | 230 | No | **High — vision-read** | A dedicated grammar reference despite lacking a text layer; worth the vision-reading cost. |
| `09.Living Language Korean Course.pdf` | 125 | No | Medium — vision-read | Course book. |
| `06.Elementary korean.djvu` | 429 | No | Medium — vision-read | Large course/textbook; djvu, needs `djvutxt`/image-rendering pipeline like SCB and Hungarian's djvu sources. |
| `14.A Korean-English dictionary.pdf` | 962 | No | Medium — vision-read, **sample not exhaustive** | Largest file in the folder by far (222 MB, 962 pages). A pure dictionary — same treatment as Hungarian's *Magyar Szlengszótár* and *Magyar szólások és közmondások*: representative sampling across the alphabet, not full transcription. Dictionary content (not grammar) — flag whether any of it is genuinely slang/informal register once sampled, in which case route it to `language_corpus/Korean/` per the Phase 1/Phase 3 content-type boundary rule. |

**Two apparent duplicate/overlapping titles found, same as prior languages' triage passes:**
- Two "Colloquial Korean" editions in the same subfolder (143pp vs. 289pp) — resolve which is
  primary vs. superseded/abridged before dispatching both.
- The Basic/Intermediate/Continuing Korean trio and Intermediate College Korean likely overlap
  substantially in core-grammar territory — apply the non-redundant-supplement dispatch pattern
  once 2+ of these are extracted, per `../00_Reference_Extraction_Spec.md`.

## OCR/scan status

**6 of 17 files (~35%) have no usable text layer** — lower than SCB's ~56% and Hungarian's ~50%,
but still a substantial minority, consistent with this being the norm rather than the exception
across languages (see `ROADMAP.md` Phase 1).

## Morphological typology (preliminary, per Phase 0 convention)

**Korean: agglutinative.** Grammatical relationships (case, topic-marking, honorifics, tense,
mood, connectives) are marked by stacking particles/suffixes onto a noun or verb stem, broadly
comparable to Hungarian/Japanese/Turkish rather than to English's more isolating/analytic pattern.
Korean additionally has an unusually elaborate **speech-level/honorific system** woven into verb
endings themselves (not just vocabulary choice, as in many European languages) — this is likely to
be a major source of register-relevant slang findings once extraction begins, the same way
Hungarian's te/maga/ön system and Hangul's own agglutinative suffix-stacking mechanisms turned out
to be. Will be refined with a real morpheme breakdown once the first grammar extraction lands.

## Recommended Phase 1 extraction priority order

**Wave 1 — core grammar + register-focused, clean text:**
1. `04.Basic Korean a grammar and workbook.pdf`
2. `05.Intermediate Korean a grammar and workbook.pdf`
3. `07.Continuing Korean.pdf`
4. `11.Using Korean a guide to contemporary use.pdf`
5. `12.The Korean language structure use and context.pdf`

**Wave 2 — remaining clean-text supplements:**
6. `10.Intermediate college Korean.pdf` (non-redundant supplement against Wave 1)
7. `The Sounds of Korean - A Pronunciation Guide/0.1...pdf`
8. `Teach Yourself Korean/Teach Yourself Korean.pdf` (+ the 2-page patch scan)
9. `0.2Korean Through English 1.pdf`
10. `0.3Active Korean 1.pdf`
11. `15.In Flight Korean.pdf`

**Wave 3 — vision-reading:**
12. `13.Korean grammar for international learners.pdf` (highest-value vision-read target — a real
    grammar reference)
13. `Colloquial Korean/` — both editions, resolve redundancy first
14. `09.Living Language Korean Course.pdf`
15. `06.Elementary korean.djvu`
16. `14.A Korean-English dictionary.pdf` (sampled, not exhaustive)
