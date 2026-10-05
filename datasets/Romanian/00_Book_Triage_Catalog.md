# Romanian — Reference Material Triage Catalog

**Status: full triage complete, 2026-10-04.** Source folder is
`source_reference/languages/Romanian/` (54MB, 5 real files + 1 incomplete torrent-download
fragment). This is the smallest corpus the project has triaged yet — smaller than Spanish's
189MB/133-file corpus by an order of magnitude.

## Scope filtering — excluded entirely

- `~uTorrentPartFile_28E1B743.dat` — a partial/incomplete torrent-download fragment, not a usable
  file.

## In-scope material — grouped by text-layer status

### Group A — Clean text layer (Wave 1)

| File | Pages | Notes |
|---|---|---|
| `01.Colloquial Romanian.pdf` | 172 | Routledge Colloquial series — register-relevant by precedent (Colloquial titles have consistently been this project's richest register/slang sources) |
| `10.Romanian An Essential Grammar.pdf` | 232 | Routledge grammar reference |
| `11.Romanian grammar.pdf` | 183 | Academic grammar reference, heavy on numeral/declension systems per a quick sample |

### Group B — No text layer at all (Wave 2, vision-reading)

| File | Pages | Notes |
|---|---|---|
| `02.Teach Yourself Romanian.pdf` | 140 | Standard course, confirmed no text layer via pdftotext sampling at multiple page ranges |
| `03.Introduction to Romanian.djvu` | 257 | DJVU scan, confirmed no text layer via djvutxt |

## Recommended Phase 1 extraction priority order

Given the small scale (5 files total), dispatch Wave 1 and Wave 2 together rather than in two
separate passes — no need for the staged prioritization larger corpora require.

## Morphological typology (preliminary, per Phase 0 convention)

**Romanian: fusional, Romance language with a retained synthetic case system** — unique among the
Romance languages for preserving a (reduced) case system inherited from Latin, with nominative/
accusative syncretism and a genitive/dative syncretism, marked via a combination of inflection and
a postposed definite article (e.g. `om` "man" → `omul` "the man"). Three genders (masculine,
feminine, neuter — itself unusual among Romance languages, which typically have only two) with a
neuter class that behaves masculine in the singular and feminine in the plural. Significant Slavic,
Turkish, and Hungarian lexical influence from centuries of regional contact, alongside the Latin
core — worth watching for in slang/colloquial vocabulary specifically. Will be refined further once
extraction lands.
