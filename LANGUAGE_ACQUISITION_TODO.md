# Language Acquisition To-Do

**Purpose.** The languages below are tied to one of the 43 Inner Tepenia GDD Gini-index
high-priority nations (see `LANGUAGE_INDEX.md`) but currently have **zero material** in
`source_reference/languages/` — no grammar, no dictionary, nothing to extract. Phase 1 cannot start
on any of them until real reference material is acquired.

**Updated 2026-10-26 after the external-drive sweep.** Filipino/Tagalog was already removed
earlier (its gap closed 2026-10-19). This pass found real material for 9 more languages on the
external drive at `/media/kuroskalacs/Home-Theater/w-lang/` — they're no longer true acquisition
gaps, just unstaged. See the new "Found externally, needs staging" section below instead of the
acquire list. Only **4 languages now remain genuine zero-material gaps.**

**Listed alphabetically — no dominance hierarchy.** All 43 GINI nations, and the languages tied to
them, are equally valid subjects of study regardless of population. The effective-population
figures below are included as descriptive context from the source census (and, for a couple of
languages, because the source doc itself calls out something narratively notable about that
nation), not as a ranking of which language to acquire first. Acquire in whatever order actually
suits real availability/cost/quality of source material.

**What to look for per language**, same standard as what's already in `source_reference/` for other
languages: a modern comprehensive grammar reference (highest value), a teach-yourself/Assimil-style
course book, a colloquial/informal-register-focused book if one exists, and ideally a dedicated
slang dictionary if the language has one (Hungarian's *Magyar Szlengszótár* is the model — real
slang content sometimes sits labeled as a grammar reference rather than under `language_corpus/`).
Prefer a real text-layer PDF over a scan-only one where a choice exists, though that isn't knowable
until triage.

---

## To acquire — genuine zero-material gaps (4 remain)

| Language | Nation(s) (Gini-adj. effective pop., context only) | Notes |
|---|---|---|
| **Belarusian** | Belarus (~1.5M) | Intermarium bloc member. Confirmed still absent from the external drive in the 2026-10-26 sweep. |
| **Czech** | Czech Republic (~5M) | Source doc flags Czech as having "among the highest per-capita robot-access rates of any nation" — a narrative note, not a priority signal. Confirmed still absent from the external drive in the 2026-10-26 sweep. |
| **German** | Germany (~46M), Belgium (partial, trilingual) | Confirmed still absent from the external drive in the 2026-10-26 sweep. |
| **Slovak** | Slovakia (~2.2M) | Intermarium bloc member. Confirmed still absent from the external drive in the 2026-10-26 sweep. |

## Found externally, needs staging — not acquisition, just triage (9)

**Already possessed, just sitting on `/media/kuroskalacs/Home-Theater/w-lang/`, unstaged and
untriaged** — found in the 2026-10-26 sweep. Nothing to buy or download; these need a Phase 0
triage pass (dedup, metalanguage check, text-layer check) and copying into `source_reference/`,
same as any other triage target.

| Language | Nation(s) | External stash |
|---|---|---|
| **Bulgarian** | Bulgaria (~1.2M) | 1.6G / 53 files |
| **Indonesian** | Indonesia (~16M) | 1.8G / 60 files, combined with Malay in one "Malay-Indonesian" folder — needs splitting |
| **Malay** | Malaysia (~5M) | Same combined "Malay-Indonesian" folder as Indonesian above |
| **Norwegian** | Norway (~3.3M) | 3.0G / 109 files |
| **Polish** | Poland (~12M) | 13G / 1,015 files, combined with Ukrainian in one "Polish and Ukrainian" folder — needs splitting |
| **Portuguese** | Brazil (~17M) | 3.5G / 167 files. Brazilian Portuguese specifically matters most here, not European Portuguese — check which variety the stash actually contains during triage. |
| **Thai** | Thailand (~8M) | 4.4G / 103 files, combined with Lao (not a GINI language) in one "Thai and Lao" folder — needs splitting |
| **Ukrainian** | Ukraine (~5M) | Same combined "Polish and Ukrainian" folder as Polish above. Do not substitute Russian material for this — they are different languages. |
| **Vietnamese** | Vietnam (~5M) | 1.3G / 53 files |

## Separately unresolved — not on the ranked list above

**South Africa** (~3M effective) has 11 official languages, and the source census doesn't specify
which one(s) the setting's South African exile community would carry. Before acquiring material,
this needs a decision on which language(s) actually matter (English and/or Afrikaans are the most
likely candidates given the setting's own "robot-owning, historically privileged emigrant" premise,
but that's an inference, not confirmed) — see `LANGUAGE_INDEX.md`'s South Africa section. English
reference material already exists in this repo regardless.

---

## Maintenance rule

When a language on this list gets real material added to `source_reference/languages/`, remove its
row here and flip its status in `LANGUAGE_INDEX.md` from "Not present — gap" to "Present" (naming
the new folder), in the same commit.
