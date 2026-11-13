# Hermes Research · Rules addendum · slang synthesis

> **PROPOSED, 2026-11-12. Adds to `/home/kuroskalacs/Documents/Doll-Fi/media/HERMES_RULES.md`; never removes a rule there.**
> Read that file first. The numbers below match its numbering.

**This folder:** `/home/kuroskalacs/Documents/Doll-Fi/media/Reference/slang-synthesis/to-be-integrated/Hermes_research/`.
The project collects, analyzes and re-synthesizes slang from real languages (its README describes the pipeline: reference extraction,
frequency-tagged web collection, a curated slang corpus, mechanics analysis, a cross-language pass, then synthesis).

**Mirror the project's folders (rule 3).** `findings/` copies the repository's own layout for the language and stage the data bears
on, for example `findings/datasets/<Language>/...` or `findings/language_corpus/<Language>/...`, using the repository's own spelling
of the language's name. The assignment names the language and the stage.

## 5.5 to 5.9 · Content rules

**Here, slang is the subject, not a thing to keep out.** The Inner Tepenia content rules (stereotypes, slang, comparing cities) do
not carry over. The rules below replace them:

- **5.5 · What may be collected.** Only what an assignment names, for the language and stage it names.
- **5.6 · Describe usage, never a people.** Record what a source says about who uses a term, where and when, with the source named.
  Never generalize a nation or an ethnicity.
- **5.7 · Never invent.** Hermes does not coin slang, gloss a term from memory, or guess at an origin. A term's meaning, origin and
  register are written only as the source gives them, in the source's words or a plain summary with its location. If a source
  gives none, write `not stated`.
- **5.8 · Record the variety.** For every term: the language, the variety or region and the period if the source states them, any
  frequency or usage label the source gives, and the source. Never merge two sources into one entry. Where sources disagree, write
  both.
- **5.9 · Count each source once.** For each language, list each source once, with its URL or book reference, so that the same source
  is never counted twice as separate evidence.

## 5.10 and 5.11 · Facts are dated; books

Slang changes quickly: **write the date of every source next to every term.** For reference books, check what the repository has
already extracted for that language (its `LANGUAGE_INDEX.md` and `datasets/<Language>/established/`) before starting, and report what
exists rather than redoing it.

## 7 · Standing in this project

Hermes files here are research data, UNREVIEWED until Claude reviews them in `reviews/`, and are not inputs to any corpus, analysis
or synthesis until a brief names them and Claude gives them a standing.

## Open questions for the Lead Developer (PROVISIONAL)

1. **Does this repository's operating-hours law bind Hermes?** The repository's own rules limit autonomous or background work to
   3:00 pm to 4:59 am. Hermes is a separate agent running locally, so the law does not obviously apply. *Recommended: no, but
   Claude schedules no work here for Hermes outside the window, and the Lead Developer decides.*
2. **Is `to-be-integrated/` the right permanent home** for Hermes's writing here, or should it later sit beside `datasets/`?
   *Recommended: leave it, because the folder was your choice.*
