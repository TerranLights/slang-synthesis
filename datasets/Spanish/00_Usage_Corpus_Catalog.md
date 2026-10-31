# Spanish — Usage Corpus Catalog

**This material is NOT for Phase 1 extraction.** It is a **usage corpus**: authentic text not written
to teach Spanish, used to check what writers actually do rather than what grammars claim. See
"Two kinds of corpus" in
`../../supplementary_diagrams/grammar_logic_diagrams/00_Diagram_Notation_and_Methodology.md`.

**Usage corpora are SEARCHED against a specific question, never extracted wholesale.**

Location: `/media/kuroskalacs/Home-Theater/w-lang/Spanish/additional stash/`
(external drive — confirm mounted before use)

---

## Inventory

### Literature — compressed collections

| Archive | Size | Entries | Format | Notes |
|---|---|---|---|---|
| `Books/Libros 6000.rar` | 1.78 GB | 6,467 | mixed — pdf, doc.zip, rtf.zip, **nested archives** | alphabetized by author; messiest to process |
| `Books/3180_libros_.zip` | 385 MB | ~3,180 | not yet inspected | |
| `Books/Libros_2480.zip` | 247 MB | ~2,480 | not yet inspected | |
| `Books/1145 Libros en fb2.rar` | 291 MB | 1,140 | **FB2 (XML)** | **easiest to convert — XML, trivial text extraction. Start here.** |

Nominal total ~13,000 entries, but **expect heavy overlap between the four collections** — dedupe by
author+title before any counting.

### Literature — loose

Named authors present in `Books/`: **Gabriel García Márquez** (*Cien años de soledad*), **Carlos
Fuentes**, **Ramón del Valle-Inclán**, **Antonio Gala**, **Almudena Grandes**, Stanisław Lem
(translated). Plus `libros_ninos/` (children's), `astronomia/`, `Historia/`, `Dictionaries/`.

### Journalism — `Magazines/` (55 PDFs, 1.4 GB)

*Historia y Vida* (2009 run), *Muy Interesante*, *Quo*, *Newton*, *National Geographic Viajes*,
*Saber Vivir*, *Psychologies*, *Mosaico*. **Journalistic register — distinct from the literary
material; do not pool counts across the two.**

### Short-form — `Articles/` (22 files, .doc)

News pieces, a formal letter, a complaint letter (*carta de reclamación*), everyday texts. Small but
the closest thing here to **functional/transactional register**.

---

## Caveats — read before using any count

1. **TRANSLATION CONTAMINATION — the most important one.** The collections are sorted by author and
   freely mix works *written in* Spanish with works *translated into* it. Already visible in the
   `Libros 6000` listing: Douglas Adams, Edwin Abbott, Villiers de l'Isle-Adam, Stanisław Lem.
   Translated prose carries source-language interference and is **unsafe evidence about native
   patterning**. **Tag original vs translated before counting**; prefer originals for any claim about
   what Spanish does.
2. **Register is not uniform.** Literary / journalistic / children's / correspondence behave
   differently. A pooled count answers no question clearly. Keep the subdivisions.
3. **Era.** Valle-Inclán (d. 1936) is not evidence about contemporary usage. Date what you can.
4. **Dialect.** Peninsular vs Latin American matters for this project specifically — the Spanish
   entry in `LANGUAGE_INDEX.md` covers Spain, Mexico, Argentina, Chile and Uruguay. Author
   nationality is the cheapest proxy available.
5. **Edited prose under-represents speech.** It will not show colloquial reduction or slang at
   natural rates. **For the slang work (Phase 3) this corpus is the wrong instrument on its own** —
   it is good for grammar-logic falsification, weaker for spoken slang.

---

## What this corpus is good for

- **Stage-3 falsification** in the grammar-logic work: does a construction a grammar treats as
  central actually occur in natural writing, and at what rate?
- **Testing "manufactured example" claims** — the Spanish analogue of Rubin's 象は鼻が長い charge.
- **Register placement** — where a form actually turns up.
- **Frequency of competing forms** where both are grammatical.

## What it is NOT good for

- Grammaticality of constructed forms that happen not to occur (absence is weak evidence)
- Prosody, speaker intuitions, marginal-form judgments → `grammar_logic/native_speaker_queries/`
- Spoken/colloquial slang at natural rates

---

## Status

**Catalogued only. Nothing unpacked, nothing extracted.** Next step when needed: unpack the FB2
collection first (XML → plain text is trivial), tag original-vs-translated, and build a searchable
index. The other three archives are lower priority and messier.
