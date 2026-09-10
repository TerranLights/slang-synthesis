# Language Acquisition To-Do

**Purpose.** The 14 languages below are tied to one of the 43 Inner Tepenia GDD Gini-index
high-priority nations (see `LANGUAGE_INDEX.md`) but currently have **zero material** in
`source_reference/languages/` — no grammar, no dictionary, nothing to extract. Phase 1 cannot start
on any of them until real reference material is acquired.

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

## To acquire

| Language | Nation(s) (Gini-adj. effective pop., context only) | Notes |
|---|---|---|
| **Belarusian** | Belarus (~1.5M) | Intermarium bloc member. |
| **Bulgarian** | Bulgaria (~1.2M) | Intermarium bloc member. |
| **Czech** | Czech Republic (~5M) | Source doc flags Czech as having "among the highest per-capita robot-access rates of any nation" — a narrative note, not a priority signal. |
| **Filipino / Tagalog** | Philippines (~5M) | |
| **German** | Germany (~46M), Belgium (partial, trilingual) | |
| **Indonesian** | Indonesia (~16M) | Bahasa Indonesia. |
| **Malay** | Malaysia (~5M) | |
| **Norwegian** | Norway (~3.3M) | |
| **Polish** | Poland (~12M) | Also the political center of the setting's Intermarium/Intermaria meta-nation bloc — check `LANGUAGE_INDEX.md`'s Slavic section for that context. |
| **Portuguese** | Brazil (~17M) | Brazilian Portuguese specifically matters most here, not European Portuguese — the effective-population figure is Brazil's, and Brazilian/European Portuguese slang diverges significantly. |
| **Slovak** | Slovakia (~2.2M) | Intermarium bloc member. |
| **Thai** | Thailand (~8M) | |
| **Ukrainian** | Ukraine (~5M) | Do not substitute Russian material for this — they are different languages and the project already has Russian covered separately. |
| **Vietnamese** | Vietnam (~5M) | |

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
