# Methodology Observations — Index

**Purpose.** A running record of observations, discoveries, and adjustments about the
slang-synthesis *methodology itself* — not language content. This is where we note things like
"the shard-size target felt wrong for this book," "the usage-tier taxonomy needed a category we
didn't anticipate," "the extraction-spec prompt missed X," or "this step took N passes because of
Y." Distinct from `ROADMAP.md` (which tracks phase/task status) and from the per-language
`00_Extraction_Checklist.md` files (which track content progress) — this is specifically about
whether the *process* is working.

**Status legend for entries:** `tentative` (from a test run, not yet reviewed) · `confirmed`
(reviewed and the observation stands) · `superseded` (reviewed and found wrong/outdated — kept for
history, not deleted).

**Everything from the first test run (Serbian/Croatian/Bosnian) is `tentative` by default** — the
developer has explicitly flagged that test-run results and process observations both need a later
double-check pass before being treated as settled. Don't upgrade a tentative entry to confirmed
without that explicit review.

---

## Entries

| File | Covers | Status |
|---|---|---|
| [`serbian_croatian_bosnian_test_run.md`](serbian_croatian_bosnian_test_run.md) | First pipeline test run — Phase 0 triage through initial Phase 1 extraction; also where the Markdown-first storage model and morphological typology guide were decided | tentative |
| [`hungarian_test_run.md`](hungarian_test_run.md) | Second pipeline test run — first real test of subagent-parallelized extraction and the morpheme-breakdown convention (agglutinative language) | tentative |
| [`dutch_test_run.md`](dutch_test_run.md) | Third pipeline test run — third typological data point (analytic/mildly fusional), first direct test of whether a "colloquial register" chapter surfaces non-core usage tiers | tentative |
| [`korean_test_run.md`](korean_test_run.md) | Fourth pipeline test run, third language to reach full Phase 1 completion — first non-Indo-European, non-Latin-script language; found and documented four distinct CJK/Hangul PDF font-corruption mechanisms | tentative |
| [`russian_test_run.md`](russian_test_run.md) | Fifth pipeline test run, fourth language to reach full Phase 1 completion — by far the largest single-language corpus (281 files, ~1.36M words); found 8 distinct Cyrillic PDF-corruption variants; graphify health check caught its first real fabricated edge in four language-scale rebuilds; recovered from three separate usage-limit disruptions | tentative |

---

## Maintenance rule

Add a row here whenever a new observations file is created. Keep observation files scoped to one
test run / one investigation thread each, splitting into a new file rather than letting one file
sprawl across unrelated topics — same discipline as everything else in this repo.
