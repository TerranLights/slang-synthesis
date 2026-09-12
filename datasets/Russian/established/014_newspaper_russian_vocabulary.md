# Russian — Established Vocabulary/Grammar: Newspaper Russian (full dictionary)

**Source:** John Slatter, *Newspaper Russian: A Vocabulary of Administrative and Commercial Idiom*
(University of Wales Press, Cardiff, 2000, ISBN 0-7083-1634-4). Full book, all 133 PDF pages
covered: front-matter Introduction (pp. v–xii), the main А–Я headword dictionary (pp. 1–114), the
"Acronyms and Abbreviations" appendix (pp. 114–119), and the "Names of Russian Political Parties"
appendix (p. 120).

**Coverage note.** This is a register-specific (journalistic/administrative/commercial idiom)
dictionary, not a graded teaching grammar, so the entire headword list is genuinely the book's
distinct-vocabulary content — there is no drill/exercise padding to skip here, and the coverage rule
("every distinct vocabulary item") is applied to the *whole* dictionary rather than a sampled
subset. This produced an unusually large single vocabulary table: **1,719 rows** (1,565 main
dictionary headwords + 133 acronym/abbreviation entries + 21 political-party/bloc names). Given the
scale, this file is being kept as one output (rather than split across many small
`established/0NN_*.md` files) because the whole thing is one coherent, alphabetically-organized
source that is more useful intact and searchable as a unit; flag if a future pass wants it re-sharded.

**Copyright discipline applied.** Per the extraction spec, the book's own **illustrative Russian
example sentences were not extracted or reproduced** — only the headword, its part-of-speech
marker, and the book's own short bracketed English gloss(es) were kept (a bilingual dictionary's
short definitional glosses are not the "vocabulary box / dialogue block / explanatory prose" the
copyright-discipline rule is protecting; the copyrightable expression — the author's illustrative
sentences drawn from period Russian press, and his introduction's discursive prose — was
paraphrased at most in a sentence or two, never quoted at length). Only a handful of intro passages
are paraphrased in the Grammar/Register points section below, with short (≤1 sentence) illustrative
quotes at most.

**PDF-extraction gotcha — worth recording for future Russian sources from this same "Learning Pack"
scan set.** This PDF has a genuine text layer, but it renders Cyrillic through **two distinct,
non-random corruption mechanisms simultaneously**, both fully decodable:
1. **Lowercase and most uppercase Cyrillic letters are shifted into the Latin-1 (ISO-8859-1)
   0xC0–0xFF range** — i.e. the underlying bytes are genuine Windows-1251 (`cp1251`), but
   `pdftotext` decoded them as Latin-1. Fix: re-encode the string as `latin-1` to recover the raw
   bytes, then decode as `cp1251`. Applied only to runs not touching an adjacent ASCII letter (to
   avoid corrupting genuine Latin-1 diacritics elsewhere in the book, e.g. the Welsh place name
   "Llandybïe" in the printer's colophon, or French loanwords like "cliché"/"élite" — the latter two
   turned out to use a *third*, harmless single-character substitution, `š`→`é`, fixed by direct
   global replacement after confirming all 7 occurrences were exactly this).
2. **A subset of capital Cyrillic letters that are visual homoglyphs of Latin capitals (А, В, С, Е,
   Н, К, М, О, Р, Т, Х, У ↔ Latin A, B, C, E, H, K, M, O, P, T, X, Y) were rendered as the literal
   Latin capital**, not shifted into the Latin-1 range — this mostly affected all-caps Russian
   acronyms in the Abbreviations appendix (e.g. `ÂÏK` → `ВПК`, `ÃKÎ` → `ГКО`) and sentence-initial
   capitals in the (excluded) Russian example sentences. Decoded by converting only all-caps *tokens
   that already contain at least one character in the 0xC0–0xDF range* (a strong signal of genuine
   Cyrillic mojibake) — this specifically avoided corrupting genuine English all-caps strings in the
   same section (`VISA`, `NATO`, `GNP`, `USA`, `MI6`, `FBI`, `CIS`, `SAS`, `TGV`) that would otherwise
   have been partially homoglyph-mangled by a naive blanket substitution (an early pass of this
   script did exactly that to the section's own "ACRONYMS AND ABBREVIATIONS" heading before the
   fix). A handful of residual lowercase homoglyph artifacts (e.g. a stray Latin `a` for Cyrillic `а`
   mid-word) remain uncorrected in a few Abbreviations-appendix cross-reference notes and are too
   sparse/ambiguous to safely auto-fix; none affect a headword or an English gloss.

No handwritten marginalia was found anywhere in this PDF — it renders from a clean digital
source file, not a scan, so the vision-reading guard doesn't apply here (Vision Reading Confidence
is `n/a` throughout).

**Usage Tier assignment methodology.** Given the scale (1,719 entries), per-entry manual register
judgment wasn't feasible; tiers were assigned via an automated keyword pass over each entry's own
English gloss text: entries whose gloss matched banking/market/trade/finance vocabulary were tagged
`technical.commercial`; entries matching government/parliament/police/military/legal vocabulary were
tagged `technical.administrative`; entries where the source's own `fig.` (figurative) label appeared
in the gloss were tagged `technical.journalistic`; everything else defaulted to the parent
`technical` tier (this is a **new subcategory set for the shared taxonomy** — `technical.commercial`,
`technical.administrative`, `technical.journalistic` — surfaced by this language/source; flag for
promotion into `00_Usage_Tier_Taxonomy.md` if a second language's data reaches for the same split).
This heuristic is approximate, not hand-vetted per row — treat any single row's tier as a
best-effort default rather than a verified linguistic judgment, and recheck a row directly against
its `Notes`/gloss text if a later analysis pass depends on its exact tier. The whole book is a
register-specific glossary by design (Slatter explicitly built it to cover only administrative,
commercial, and journalistic idiom, excluding general-vocabulary senses already assumed known — see
his Introduction, p. ix), so `core` doesn't meaningfully apply to any entry here.

**"See also" cross-references** the book itself marks (e.g. "долгосрочный — see also краткосрочный,
среднесрочный") were preserved in the `Notes` column rather than folded into the `Gloss`, since they
are the book's own explicit navigational annotations tying related headwords together — this is the
closest thing this particular source has to the dialectal/register tags other reference books in
this project mark explicitly (Slatter's annotations are cross-reference and figurative/literal
labels, not regional ones — see the Grammar/Register points section below for what this source does
and doesn't mark).

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| ав’анс | advance payment | noun (m.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| авар’ийность | accident rate | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| автоматиз’ация | automation | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| автоотв’етчик | answering machine | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| агрег’ат | units | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ’адрес | aimed at | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ’адресный | appropriate | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ажиот’аж | hoo-ha, hype | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| активиз’ация | activation | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| акт’ивы | assets; de- preciating assets; liquid assets; working assets; net assets | noun (m. pl.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| акцион’ерный | public limited company | adjective | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| акцион’ирование | share-creation | noun (n.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ’акция | shares; act | noun (f.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| амб’иция | ambitions | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| амн’истия | amnesty | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| анал’итик | analysts | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ан’алог | equivalents | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| аннекс’ировать | annexed | verb (impf./pf.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| анн’ексия | annexation | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| аннул’ировать | quash, cancel | verb (impf./pf.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| антид’емпинговый | anti-dumping | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| антимоноп’ольный | cartel-busting, [US] trust-busting | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| апелл’ировать | appeals to; appeal | verb (impf./pf.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | see also обжалование |
| ар’енда | renting of premises | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ар’ест | sequestration | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ассигнов’ание | allocations, appropriations | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| аудит’ория | ‘audience’, i.e. section of the electorate | noun (f.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| аукци’он | auctioning-off; outsiders | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| аффили’ировать | affiliated | impf. only | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| б’азовый | base rate | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| баланс’ировать | have been teetering | impf. only | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| баллот’ироваться | run/stand for | impf. only, r. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| бандформиров’ание | groups of gangsters – short for бандитское формирование | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| банком’ат | cash-dispensing machines, [US] ATMs | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| банкр’отство | bankruptcies | noun (n.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| б’артер | by barter | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| б’егство | escape | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| б’еженец | refugees | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| безв’ольный | spineless | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| безд’ействие | inactivity | noun (n) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| безд’енежье | lack of money | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| безнак’азанно | with impunity | adverb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| безнал’оговый | tax havens | adjective | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| безогов’орочный | unreserved | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| безоп’асность | safety, security | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| безраб’отица | unemployment | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| безуд’ержный | unrestrained | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| бесперспект’ивный | hopeless | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| беспрецед’ентный | unprecedented | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| беспроц’ентный | interest-free | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| биорес’урсы | natural resources | noun (m. pl.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| биржев’ик | [stock]brokers | noun (m.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| благопол’учие | welfare | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| благопри’ятный | favourable | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| благорасполож’ение | favourable attitude | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| благотвор’ительность | charity | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| благоустр’ойство | local services | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| блок | the economics team | noun (m.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| блок’ада | siege; have frozen | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| боев’ой | military activity | adjective | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| боеспос’обность | fighting capacity | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| б’ойня | slaughter | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| бок | side by side with | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| бол’ото | don’t knows, floating voters | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| больн’ой | fig. ‘painful issue’, ‘sore spot’ | adjective | technical.journalistic | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| большинств’о | majority | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| б’омба | cluster bomb; fragmentation bomb; graphite bomb | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| бортов’ой | on-board | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| бр’атский | communal graves | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| бр’ифинг | briefing | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| брож’ение | ferment, unrest | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| б’уква | the letter of the law; one stands strictly by the letter of the law | noun (f.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| бунт | riot | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| бык | ‘gorillas’ | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| бытов’ать | previously current | impf. only | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| бюдж’етник | state pensioners and employees, i.e. those dependent on the state budget; has gone for broke | noun (m.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| вак’ансия | job vacancy | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| валов’ой | gross revenue | adjective | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| введ’ение | introduction | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ввер’ять, вв’ерить | entrusted by law | verb | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ввод | input; typing in of your PIN | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ввод’ить, ввест’и | bring in, introduce | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| в’едомство | departments | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| вербов’ать, завербов’ать | recruited | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| верд’икт | verdict | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| верх’ушка | the tip of the iceberg | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| в’ето | will veto | noun (n.); noun (indecl.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| взаимов’ыгодный | mutually advantageous; mutually profitable | adjective | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| взаимод’ействие | interaction | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| взаимоотнош’ение | mutual relations, interrelations | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| взаимопоним’ание | mutual understanding | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| взбудор’аживать, взбудор’ажить | to work up | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| взб’учка | rebuked, fig. ‘hauled over the coals’; to take on himself the burden of being premier | noun (f.) | technical.journalistic | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| взв’ешанный | balanced | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| взв’инчивать, взв’интить | raise, [US] hike | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| взим’аться | is levied | impf. only, r. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| взнос | contributions | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| вклад | contribution; deposits | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| вкл’адчик | investors | noun (m.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | see also инвестор |
| вкл’адывать, влож’ить | to invest; what they mean by | verb | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| включ’ение | live insert | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| влад’елец | owners; guardians | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| вл’аствующий | ruling houses | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| вл’астный | corridors of power | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| власть | powers that be; will entail | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| влож’ение | investing, i.e. the act of investing, not the funds invested | noun (n.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| вмеш’ательство | state intervention | noun (n.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| вм’ешиваться, вмеш’аться | intervene | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| внедр’ение | implanting | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| внедр’яться, внедр’иться | which have put down roots in | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| внесение | putting forward the candidacy of | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| вн’ешний | external, export | adjective | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| внос’ить, внест’и | moved a resolution; made their contribution | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| вн’утренний | internal | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| военач’альник | military leaders | noun (m.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| военносл’ужащий | of the military/soldiers | noun (m.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| во’енный | military | adjective | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| во’енный | soldiers | m., declines like adj. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| вождь | leader | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| возбужд’ать, возбуд’ить д’ело | has brought a criminal case; canonize | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| возвр’ат | repayment | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| возглавл’ять, возгл’авить | headed [up – US] | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| возд’ействие | pressure | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| возд’ерживаться, воздерж’аться | refrained; abstained | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| возлаг’ать, возлож’ить | laid a wreath; is carried by; imposed the duty of; laid the blame | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| возмещ’ать, возмест’ить | reimburse, indemnify | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| возмущ’аться, возмут’иться | were angry / indignant at | r. + inst. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| возмущение | outrage at | n., + inst. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| возоблад’ать | predominated | verb (pf.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| возобновл’ять, возобнов’ить | renewed, recommenced | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| возрастн’ой ценз | age qualification, voting age | adj. + m. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| вопр’ос | raised the issue of; will perceive | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| восстан’авливать, восстанов’ить | rebuild; has restored; reinstated | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| восстанов’ительный | rebuilding work | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| восстановл’ение | restoration; reconstruction; the G8 | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| недов’ерия | vote of no confidence | — | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| воцар’ение | accession | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| впечатл’ять | is impressive | impf. only | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| впуст’ую | to no purpose | adverb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| вред’ить, повред’ить | damage | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| вруч’ать, вруч’ить | presented | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| вруч’ение | delivery | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| все’общий | universal | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| вспомож’ение | financial aid | noun (n.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| встр’оенный | fitted kitchen; entered into conflict with | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| вступл’ение | accession to the throne | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| вторж’ение | ground invasion | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| втор’ичный | second-round elections | adjective | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| вт’ягивать, втян’уть | will be dragged into | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| вход’ить, войт’и | will not be a member of | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| выбив’ать, в’ыбить | was forced out of | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| в’ыбивки | hard currency bonds | pl. | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| в’ыборы | universal secret direct elections | pl. | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| в’ывод | rescue; withdrawal; output; conclusion | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| в’ыводить, в’ывести | shield from the blow; has been put out of action; was removed from the frame; remove | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| в’ывозить, в’ывезти | export | verb | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| в’ыгодный | advantageous | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| выдав’ать, в’ыдать | make the desire pass for the reality; issued . . . with | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| в’ыдача | extradition; advance, put forward | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | see also план |
| выдвиж’ение | nomination | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| выдел’ение | allocation | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| выдел’ять, в’ыделить | allocate | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| в’ыжженная земл’я | scorched earth | adj. + f. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| вызыв’ать, в’ызвать | summon | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| в’ыкуп | ransom | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| в’ылазка | sorties | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| вылив’аться, в’ылиться | resulted in | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| вымог’ать | extorted | impf. only | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| вынос’ить, в’ынести | pronounced judgment; judicial sentences pronounced | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| в’ыпад | attacks | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| в’ыплата | withdrawals; repayments | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| в’ыполнять, в’ыполнить | carried out, fulfilled | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| в’ыполняться, в’ыполниться | is being carried out | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| в’ыпуск | bond issues; released; issued | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| в’ыработка | devising | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| выраж’ать, в’ыразить | expressed their solidarity | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| выраст’ать, в’ырасти | rose in value | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| выруч’ать, в’ыручить | earned; having helped out with | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| в’ыручка | earnings | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| в’ысадка | landing | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| выск’азывание | pronouncements; statements | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| выск’азываться, в’ысказаться | spoke out against/for | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| высокодох’одный | profitable | adjective | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| высокоп’арный | high-flown | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| высокопост’авленный | ‘high-up’, high-flying | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| выст’аивать, в’ыстоять | stood firm | verb | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| выступ’ать, в’ыступить | is standing as | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| выступл’ение | speeches; adj. + f. + gen.; death penalty – lit. highest degree of punishment | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| в’ытекать | are entailed by; which flow from | impf. only | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| в’ыход | way out | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| в’ыходка | outbursts | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| вышеупом’янутый | aforementioned | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| выясн’ять, в’ыяснить | elucidate | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| в’язкий | tough talks | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| габар’ит | dimension | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| г’алстук | informal meeting, back-room talks | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| гар’ант | guarantor | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| гарант’ийный | act as the guarantor of a liability | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| гар’антия | safeguards; pledges | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| генер’ировать | lit. and fig. generate, create | verb (impf./pf.) | technical.journalistic | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| генштаб’ист | member of the general staff; hyperinflation | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| глав’а | head | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| глаз | face to face | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| глас’ить | announces | impf. only | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| глуб’инка | in the sticks | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| голод’овка | hunger strike | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| г’олос | votes | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| голосов’ание | voting | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| голосов’ать, проголосовать | vote | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| г’онка | race | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| горож’анин | city-dwellers | m., declines like англичанин | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| гор’ячий | fig. hot spot | adjective | technical.journalistic | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| гражд’анский | civil | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| грант | Soros grants | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| гр’афик | timetable | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| гробов’ой | deadly silence, fig. silence of the grave | adjective | technical.journalistic | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| гроз’ить | menaces | + dat. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| гром | like a bolt from the blue | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| гр’уппа | rapid reaction force [of army, police, etc.] | noun (f.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| губерн’атор | governors | noun (m.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| давл’ение | pressure | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| д’альность | medium-range | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| д’ача | to give testimony | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| дв’игать, дв’инуть | motivated; bilateral | + inst. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | see also односторонний, тр¸хсторонний |
| девальв’ация | devaluation | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| дев’аться, д’еться | we shall not be able to avoid | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| дезаву’ирование | repudiation | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| д’ейственный | effective | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| д’ействовать | work, function | in this meaning, impf. only | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| д’ействующий | in force; serving | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| дел’ец | businessmen; sharing-out | noun (m.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| д’ело | files; if it comes to | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| делов’ой | working lunch | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| демократиз’ация | democratization | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| демониз’ировать | s | impf. only | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| демонополиз’ировать | demonopolized | verb (impf./pf.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| д’емпинг | dumping | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| демпингов’ать | are dumping | impf. only | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| депоз’ит | deposit account | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| держ’атель | holder, bearer | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| держ’аться | keep to . . . timetable | impf. only, r., + gen. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| дестабилиз’ировать | are destabilizing | verb (impf./pf.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| дефиц’ит | deficit; shortage; a scarce item | noun (m.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| деф’олт | default; have fallen in price | noun (m.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| д’еятельность | activity | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| диапаз’он | range | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| диз’айн | design | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| диктов’ать, продиктов’ать | are motivated; dictate | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| дир’ектор-распоряд’итель | managing director | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| дисбал’анс | imbalance | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| дисконт’ирование | discounting | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| дискредит’ация | at discrediting | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| дислок’ация | disposition | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| дистанц’ироваться | distances itself from | impf. only, r. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| дл’ительный | lengthy | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| добив’аться, доб’иться | has been striving for; obtained; get my own way; try to get my own way | r., + gen. and от + gen. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| дов’еренный | defender | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| довер’ительность | confidentially; agreement | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| дозн’ание | investigation | noun (n.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| доказ’ательство | produced proof | n. – usually pl. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| долгоср’очный | long-term | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | see also краткосрочный, среднесрочный and перспектива |
| должн’ик | debtor; debtor countries | noun (m.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| должностн’ой | functionaries; official status | adjective | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| докл’адывать, долож’ить | gave a report | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| дополн’ять, доп’олнить | supplement | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| допуск’ать, допуст’ить | admitted; allow; commits | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| дораб’атывать, дораб’отать | finish working on | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| дорож’ать, подорож’ать | increased in price | verb | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| доср’очный | early [i.e. premature]; mid-term elections; early retirement | adjective | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| дост’авка | delivery | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| достов’ерный | accurate | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| д’оступ | access; access to | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| д’осуг | leisure time | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| досяг’аемость | beyond reach | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| дот’ация | state subsidies | noun (f.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| дох’од | income; with fixed and variable yields | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| дох’одность | 10 per cent annual yield | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| д’умец | Duma deputies | noun (m.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| дур’ак | made fools of | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| душев’ой | per capita income | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ду’эль | verbal duelling | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| един’ица | pieces | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| един’ичный | single | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| единовл’астие | autocracy | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| единогл’асный | unanimously | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| единод’ушие | unanimity | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| единод’ушный | unanimous | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| едином’ышленник | followers; like-minded people | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ед’иный | single market; broad; labour-intensive: other words using this suffix include энерго¸мкий, металло¸мкий, науко¸мкий | adjective | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ж’алоба | appeal | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ж’алованье | salary | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ж’аловать, пож’аловать | take to their hearts | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| железобет’онный | iron logic, lit. reinforced concrete; live, fig. in the flesh | adjective | technical.journalistic | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| жизнеспос’обный | viable; adj. + m.; ‘fat cats’ | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| жуч’ок | ‘bugs’ | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| забаст’овка | hunger strikes | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| забаст’овщик | strikers | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| забир’ать, забр’ать | seize, appropriate | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| заблагорасс’удиться | as it sees fit | pf. only, r., impers. + dat. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| завер’ение | assurances | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| заверш’аться, заверш’иться | come to an end | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| завер’ять, зав’ерить | assure | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| завоев’ание | conquest | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| зав’оз | delivery to the northern regions | noun (m.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| з’аговор | conspiracies | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| зад’ержка | delay in payment | noun (f.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| зад’олженность | debt, indebtedness; arrears; loan; borrower countries | noun (f.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | see also должник |
| за’имствование | borrowings | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| заказн’ой | contract murder, ‘hit’ | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| заключ’ать, заключ’ить | concluded | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| заключ’аться, заключ’иться | comes down to this, that | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| заключ’ительный | final | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| законод’ательно | by legislation | adverb | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| законод’ательный | legislative | adjective | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| законод’ательство | legislation | noun (n.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| законом’ерность | rule | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| законопосл’ушный | law-abiding | adjective | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| законопро’ект | draft bill | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| закрепл’ять, закреп’ить | fixed | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| закр’ытый | behind closed doors | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| закуп’ать, закуп’ить | stocked up on | verb | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| зал’амывать, залом’ить | raise the price sky-high | verb | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| зал’ечь | downed tools | pf. only | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| зал’ог | guarantee; on bail | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| зал’оговый | security/guarantee fund | adjective | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| зал’ожник | hostages | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| зам’анить калач’ом | wild horses wouldn’t drag . . . | pf. + m. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| замест’итель | deputy | noun (m.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| замир’ение | peace-making | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| замор’аживать, замор’озить | freeze | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| з’амысел | scheme | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| зан’ятость | employment | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| запасн’ой | a sort of spare | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| запр’ашивать, запрос’ить | officially requested | verb | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| запр’ет | ban on | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| запр’етный | no-fly zone | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| запрещ’ать, запр’етить | bans, forbids; outlawed | + dat. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| запр’ос | official request | noun (m.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| з’апуск | launch | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| заруч’аться, заруч’иться | gain support; had gone too far | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| зар’ыть топ’ор | buried the hatchet | pf. + m. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| зас’ада | ambush | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| засед’ание | session | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| заставл’ять, заст’авить | a reason presented itself before long | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| заступ’аться, заступ’иться | will not stand up for them | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| зат’ея | venture | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| затр’агивать, затр’онуть | concern, touch on | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| затр’ата | expenditures | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| затр’ачивать, затр’атить | expended | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| зат’ягивание | prolongation | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| зат’ягивать, затян’уть | prolong, drag out | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| затяжн’ой | lengthy, protracted | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| захв’ат | occupation | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| захорон’ение | burial of the remains | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| зач’инщик | ringleaders; protection | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| заявл’ение | are handing in an application, are applying; declared | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| за’явка | applications | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| звен’о | weak link | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| зв’ерство | atrocities | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| здравом’ыслящий | right-thinking | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| злок’озненный | treacherous, perfidious | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| злоупотребл’ение | abuse | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| знак | place a question mark over | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| з’она | free economic zone | noun (f.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| зонд | lunar probe | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| зря | counted for nothing | adverb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| зуб | shot itself in the foot | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| игл’а | let ourselves be hurt by | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| игнор’ировать | which take no account of | verb (impf./pf.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| игр’а | take an independent line | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| игр’ок | to avoid | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| избир’атель | voters | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| избир’ательный | electoral | adjective | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| избр’анник | choice, elect | noun (m.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| изб’ыток | surplus | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| изв’естность | keep posted, inform | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| извлеч’ение | extraction | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| изготовл’ение | manufacture | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| изобрет’ать, изобрест’и велосип’ед | without reinventing the wheel | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| изъявл’ять, изъяв’ить | declared, expressed | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| именов’аться | hereafter termed; image; image-maker | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| иммунит’ет | immunity | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| имп’ичмент | impeachment | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| им’ущество | with confiscation of property | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| инаком’ыслящий | dissidents | adj. or m. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| инвал’идность | disability/disablement | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| инвестици’онный | for investment | adjective | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| инвест’иция | investments | noun (f.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| инв’естор | investors | noun (m.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | see also вкладчик |
| индекс’ация | indexation | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| иници’ировать | initiated | verb (impf./pf.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| инст’анция | to higher authorities | noun (f.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| инстит’ут | institution | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| инструм’ент | financial instrument; device; tool | noun (m.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| интегр’ация | integration | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| инфл’яция | inflation | noun (f.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| информ’ация | news – usually pl. | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| инфраструкт’ура | infrastructure | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| инцид’ент | accident | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ипот’ечный | mortgage credit plans | adjective | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| иск | sued; expelled | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| иск’омая с’умма | total | adj. + f. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| искорен’ять, искорен’ить | eradicates | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| исполн’ение | exercise of his functions | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| исполн’ительный | court order | adjective | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| исполн’ять, исп’олнить | acting | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| испыт’ание | testing; trial | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| исп’ытывать, испыт’ать | test the mettle | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| истеблишм’ент | establishment | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ист’ец | plaintiff | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| истеч’ение | expiry | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| исх’од | outcome | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| исход’я из | starting from; based on | prep. + gen. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| исч’ерпывающе | exhaustively | adverb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| исчисл’яться, исч’ислиться | is estimated at | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ит’ог | result | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ит’оги | summed up | noun (m. pl.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ит’оговый | final | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| й’ота | not a jot, not one iota | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| кадр | shots | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| к’адровый | personnel policy; offer of a job; employment agency | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| казн’а | treasury | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| к’амень | hidden dangers – lit. underwater rocks | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| камп’ания | campaign | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| камуфл’яж | camouflage clothes | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| кандидат’ура | candidacy | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| канцел’ярия | chancellery | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| капитул’ировать | surrendered | verb (impf./pf.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| к’арта | reveal its hand; reshuffled all the cards | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| карт’ельный | agreement on cartels | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| к’арточный | rationing; smartcard | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| касс’етный | cluster bombs | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| категор’ически | categorically | adverb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| категор’ично | quorum | adverb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| кв’ота | quotas | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| клев’етник | slanderers | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| клептокр’атия | ‘kleptocracy’, i.e. government by thieves | noun (f.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| клинч | lit. clinch: fig. tussle | noun (m.) | technical.journalistic | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| клип | video clip | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ключев’ой | key | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| кл’ятва | oath of loyalty; m. + m.; carrot and stick; ‘carpet’, give a severe reprimand to | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| к’одекс | Code of Labour Law | noun (m.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| коз’ырь | trump | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| колеб’ание | variations, fluctuations | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| колл’апс | exhaustion | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| колл’изия | legislative conflicts | noun (f.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| кол’ода | pack [lit. of cards] | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ком’анда | team player | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ком’андование | command | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ком’андующий | commander | m. + inst. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| комбин’ация | tricks | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| коммент’арий | no comment | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| коммисси’онные | commission | pl., declines like adj. | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| коммюник’е | communiqué | noun (n.); noun (indecl.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| компенс’ировать | compensate for | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| к’омплекс | defence complex; set of economic issues | noun (m.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | see also ‘Abbreviations’ under ВПК |
| компром’ат | blackmail material | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| компром’исс | compromise | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| конв’ерсия | conversion of military facility to civilian use | noun (f.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| конверт’ация | conversion | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| конверт’ировать | converted | verb (impf./pf.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| конкур’ент | competitor | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| конкур’енция | competition | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| конкур’ировать | compete | intrans. or c + inst. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| к’онкурс | by tendering | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| конс’алтинговый | consulting services | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| констат’ировать | affirmed | verb (impf./pf.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| консульт’ироваться, проконсультироваться | consulted, sounded out | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| континг’ент | peacekeeping force | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| контраф’актный | counterfactual | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| контр’оль | is under the government’s control | noun (m.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| конт’уры | outlines | noun (m. pl.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| конфиск’ация | seizure | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| конфиск’овывать, конфисков’ать | used to sequester, confiscate | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| к’онфликт | conflict | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| конфликтов’ать | the sides in conflict | impf. only | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| конъюнкт’ура | of the economic situation | noun (f.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| координ’атор | party managers | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| координ’аты | details – name and address, etc. | noun (f. pl.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| координ’ация | coordination | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| корд’он | cordon sanitaire | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| коррект’ировать, скоррект’ировать | put right, correct | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| корр’ектный | polite | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| корр’упция | corruption | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| котир’овка | share prices | noun (f.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| край | region; no end of it | noun (m.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | see also область, округ, регион, участок |
| краткоср’очный | credit | adjective | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| кредитов’ание | round of credit | noun (n.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| кредит’ор | creditors | noun (m.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| кр’есло | seats | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| крит’ерий | criterion | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| круг | set of duties | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| кругосв’етный | round-the-world | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| крыл’о | took under his wing | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| кр’ыша | have gone crazy | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| кулу’ар | corridors | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| к’упленный | bribed | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| куп’онный | yield [of a share or bond] | adjective | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| кур’аторство | supervision | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| кур’ировать | look after, take care of | impf. only | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| курс | exchange rate; ‘up to speed [with everything]’ | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| легализ’ация | legalization | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| легит’имность | legitimacy | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| либерализ’ация | liberalization | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| л’идер | leaders | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| л’идерство | leading position: also leadership | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| л’изинг | long-term financing arrangement | noun (m.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ликвид’ировать | to get rid of | verb (impf./pf.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ликв’идность | liquidity | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| лицензи’онная пал’ата | patents office | adj. +f. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| лиц’ензия | recalled/suspended licence to operate | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| лиц’о | legal entity; natural person; character in novel, play etc.; statespersons; functionary; on behalf of; lost face; save face | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| лиш’ение | imprisonment | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| лоб | openly | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| л’обби | lobby | n. indecl. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| лобб’ировать | lobby for | impf. only | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| лобб’ист | lobbyist | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| л’озунг | slogan; loyal | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| льг’ота | allowances, concessions | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ляп | gaffe; brought the matter to a conclusion – lit. brought it out on to the main road | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| макроэкон’омика | macroeconomics | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| манд’ат | mandate | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| манифест’ант | demonstrators; looters | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| марш | protest march | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| масшт’аб | on a large scale | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| матери’альный | material | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| матр’ос | orders are orders, or ours not to question why, ours but to do or die | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| м’аятник | pendulum | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| межэтн’ический | inter-ethnic | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| м’енеджер | one of the best managers | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | see also управленец |
| м’ерка | by world standards | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| меропри’ятие | celebrations; events | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| механ’изм | means | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| микроэкон’омика | microeconomics | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| м’ина | put on a good face | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| миним’альный | minimum wage | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| м’ирный | peace settlement; peaceful | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| миров’ая | go for an amicable agreement | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| миропоним’ание | perception of the world | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| миротвор’ец | peacekeepers | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| миротв’орческий | peacekeeping forces | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| м’иссия | mission | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| м’итинг | meeting, demonstration | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| митингов’ать | are demon- strating; demonstrators | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| митинговщ’ик | demonstrators | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| многопол’ярный | multipolar | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| модел’ировать, смодел’ировать | construct a model | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| мозг’и | rack one’s brains | noun (m. pl.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| монит’оринг | monitoring | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| моноп’ольный | monopolistic – i.e. ‘as a monopoly’ | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| морат’орий | moratorium | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| м’остик | bridge | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| мотивир’овка | motive, motivation | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| муниципалит’ет | local authorities | noun (m.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| мэр | mayor | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| м’эрия | town hall | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| мят’еж | rebellion | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| мят’ежник | rebel; keeps mum/shtum; who picked up; have collected; is gathering strength | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | see also under матрос |
| наблюд’атель | observers | noun (m) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| наблюд’ать | keeps an eye on | за + acc., impf. only | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| навод’ить, навест’и | bridge-building; enforce order | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| нав’язывать, навяз’ать | imposed | + acc., + dat. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| нагнет’ать, нагнест’и | do not pile on the pressure | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| нагр’узка | loading | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| над’авливать, над’авить | put pressure on; sellers’ mark-ups | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| над’елать | make a lot of noise | pf. only | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| нажив’аться, наж’иться | get rich | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| нажим’ать, наж’ать | press the emergency button | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| наз’емный | land war | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| назнач’ать, назн’ачить | appoint | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| назнач’енец | appointee | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| назнач’ение | appointment | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | see also Abbreviations under ОМОН |
| наименов’ание | titles | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| нак’аз | demands | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| нак’аливаться, накал’иться | is hotting up | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| нак’апливаться, накоп’иться | which have accumulated/piled up | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| накл’адывать, налож’ить | impose | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| накопл’ения | savings | noun (n. pl.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| нал’аживание | regulating | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| нал’аживать, нал’адить | keep order; maintain the connection | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| налиц’о | we are facing; the fact is obvious | adverb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| нал’ичные | cash | f. pl., declines like adj. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| налогов’ик | tax inspectors | noun (m.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| нал’оговый | taxation checks | adjective | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| налогооблож’ение | taxation | noun (n.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| налогоплат’ельщик | taxpayers | noun (m.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| намеч’ать, нам’етить | planned; was nominated; set for | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| напл’ыв | influx | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| направл’ять, напр’авить | sent a fax | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| нар’езка | slicing up . . . into tranches | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| наруш’ать, нар’ушить | which infringe; heirs | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| насл’едный | Crown Prince | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| насл’едство | as an inheritance; overtook | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| насто’яние | at the insistence of | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| наступ’ательный | attacking, aggressive | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| наступл’ение | in the event of; attack | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| насыщ’ать, нас’ытить | satisfy | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| нас’ыщенный | full/active day | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| натык’аться, наткн’уться | come up against; walk onto | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| нат’яжка | without stretching a point | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| нат’янутый | strained | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| нац’еливать, нац’елить | is aimed | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| национализ’ация | nationalization | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| невозвр’ат | non-reimbursement | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| недейств’ительный | recognized as invalid; + gen.; will receive less than | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| недопуст’имость | impermissibility | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| недораб’отка | defects | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| недоразум’ение | misunderstanding | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| недост’аток | lack; defencelessness, lack of protection | noun (m.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| неистр’аченный | unexpended | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| нейтралит’ет | neutrality | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| неконкурентоспос’обный | uncompetitive | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| нем’ыслимый | unthinkable | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| необосн’ованность | groundlessness | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| необосн’ованный | unjustified | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| неоднозн’ачно | ambiguously | adverb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| неотврат’имый | irresistibly | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| неотъ’емлемый | integral – lit. unremovable | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| неофици’альный | straw poll | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| неоцен’имый | invaluable; non-payment | adjective | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| неповинов’ение | insubordination | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| неповтор’имый | unique, inimitable | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| непосл’едовательный | inconsistent | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| непредсказ’уемый | unpredictable | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| непри’емлемый | unacceptable | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| неприкоснов’енность | inviolability | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | see also иммунитет |
| непроф’ильный | lit. non-standard: fig. unusually difficult | adjective | technical.journalistic | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| неразбер’иха | muddle | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| нераспростран’ение | non-proliferation | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| нерезид’ент | non-residents | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| несосто’ятельность | insolvency | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| несосто’ятельный | insolvent; baseless | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| нетрудоустр’оенный | to the unemployed | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| неуст’ойка | forfeits | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| неуст’ойчивый | unstable | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| нехв’атка | lack, shortage | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| нецелев’ой | unauthorized | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| нецелесообр’азный | inadvisable | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| низкодох’одный | low-paid | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| номенклат’ура | lit. nomenclature, i.e. strictly, those considered by the CPSU to be fit to occupy listed key administrative posts: more broadly nowadays, former Communist Party and Soviet functionaries | noun (f.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| н’орма | standards | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| нормат’ивный | regulatory | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ньюсм’ейкер | newsmakers | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| обв’ал | collapse | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| обв’альный | lit. avalanche-like: free-fall state | adjective | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| обвин’ение | accusations; indictment | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| обезл’ичивание | absence of responsibility for; will turn out | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| обеспеч’ение | securing of peace | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| обесп’ечивать, обесп’ечить | ensure; supply | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| обесц’ениваться, обесц’ениться | depreciating | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| обж’алование | appeal | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | see also апелляция |
| обж’аловаться | is appealed against; are not levied | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ’область | areas; regions | noun (f.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | see also край, округ, регион, участок |
| облиг’ация | bonds | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| обм’енивать, обмен’ять | exchange | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| обнал’ичивать, обнал’ичить | encash, cash | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| обнар’уживать, обнар’ужить | discovered | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| обнар’уживаться, обнар’ужиться | was revealed | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| обнищ’ание | impoverishment | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| обознач’ать, обозн’ачить | stressed | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| обор’она | defence | noun (f.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| оборон’ительный | defensive | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| обор’онный | defence complex | adjective | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | see also Abbreviations under ÂÏK |
| обор’онщик | lit. defenders, i.e. defence forces | noun (m.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| обор’отный | working capital | adjective | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| обосн’ованность | soundness | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| обосн’овывать, обоснов’ать | substantiated | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| обостр’ение | intensification | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| обостр’яться, обостр’иться | has become more acute | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| об’очина | fig. sidelines – lit. roadside | noun (f.) | technical.journalistic | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| обраб’атывать, обраб’отать | metal-processing industry | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| образц’овый | model | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| обр’атный | retrospective force; return | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| обращ’ение | appeal; circulation | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| обрыв’ать, оборв’ать | break off; break off a deal | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| обрыв’аться, оборв’аться | breaks up | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| обсл’уживание | service; servicing | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| обставл’ять, обст’авить | hedged around with conditions | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| обстан’овка | conditions | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| обузд’ание | restraining | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| обх’одиться, обойт’ись | cost: N.B. не and без in practice form a double negative | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| общ’аться | by mixing with | impf. only | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| общенар’одный | nationalized | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| общ’ественность | the public | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| общ’ественный | public opinion | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| объедин’яться, объедин’иться | merging | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| объ’ект | facilities; sites; targets; export volume | noun (m.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| объявл’ять, объяв’ить | declared a truce; declared . . . open; declared bankrupt; begin an investigation into the accused | + acc. + inst. | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ’обыск | official searches | noun (m.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| обяз’ательный | obligatory | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| обяз’ательство | liabilities; commitments | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| оглаш’ать, оглас’ить | announced | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| огл’ядка | without regard to | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| огов’орка | reservations | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| од’ерживать, одерж’ать | won a victory; called to order | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| од’ин | one on one | — | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| однозн’ачно | unambiguously | adverb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| одноманд’атный | single-member constituencies | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| одностор’онний | unilateral | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | see also двухсторонний, тр¸хсторонний |
| одобр’ять, од’обрить | approved; dogged, determined | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| озаб’оченность | are causing serious concern | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| оздоровл’ение | recovery | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| оказ’ание | rendering of aid | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ок’ошко | find a window | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ’округ | electoral district, constituency; constituencies; environment | noun (m.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | see also край, область, регион, участок |
| окруж’ение | entourage | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| олиг’арх | oligarchs, i.e. the rich and powerful | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| омбудсм’ен | ombudsman | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ом’оновец | security guards | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | see Abbreviations under ОМОН |
| оп’ала | disgrace | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| оп’альный | disgraced | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| опас’ение | reservations | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| операт’ивник | policemen | noun (m.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| операт’ивный | efficiently; operational | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| опер’ация | transactions | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| опереж’ать, оперед’ить | who beat | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| опереж’ение | in anticipation of | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| опер’ировать | makes use of | in fig. sense, impf. only: + inst. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| опознав’ать, опозн’ать | identify | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| оппозицион’ер | oppositionists | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| опр’авдывать, оправд’ать | acquit; justifies | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| опр’ашивать, опрос’ить | surveyed | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| определ’ение | definition; by definition; court judgment | noun (n.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| определ’ять, определ’ить | define | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| опр’обоваться | be tested | verb (reflexive); verb (impf./pf.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| опроверг’ать, опров’ергнуть | denies; overturned | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| опроверж’ение | denial; overturning | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| опр’ос | public opinion surveys | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| оптов’ик | wholesalers | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| опт’овый | wholesale prices; fall | adjective | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ’ордер | warrants, authorizations | m. – pl. ордер’а | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ор’ужие | lit. and fig. weapon | noun (n.) | technical.journalistic | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ос’ада | siege; well-informed | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| освобожд’ать, освобод’ить | relieves; vacate; set free | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| освобожд’аться, освобод’иться | will become available | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| осво’ение | control | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| осмотр’ительный | more cautiously; reinterpreting, rethinking | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| основ’ание | there are grounds for thinking | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| осознав’ать, осозн’ать | became aware of | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| оставл’ять, ост’авить | overlook; retains the right | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ост’анки | the remains | noun (m. pl.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| осуществл’яться, осуществ’иться | was carried out | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| осяз’аемый | palpable | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отбир’ать, отобр’ать | has been removed; removed | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отбыв’ание | serving | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отбыв’ать, отб’ыть | leaves; screwdriver assembly | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отв’етный | answering move | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отв’етственность | responsibility | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отв’етчик | respondent, defendant | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отвеч’ать, отв’етить | answered in kind; be sacked | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отв’од | pulling-out, withdrawal | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отвод’ить, отвест’и | is assigning; have not won back | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отдав’ать, отд’ать | repay | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отдел’ение | departments, divisions | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отд’ельно | socialism in a single country | adverb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отд’ельный | of the individual | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| от’ечественный | domestically produced | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ’отзыв | retracting; opinions | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отзыв’ать, отозв’ать | recalled | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отзыв’аться, отозв’аться | react | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отк’аз | engine failure | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отк’азываться, отказ’аться | repudiate; withdrew his testimony; deny themselves nothing | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отк’алываться, откол’оться | which split off from | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| откл’адываться, отлож’иться | was postponed | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отклик’аться, откл’икнуться | reacted/responded to | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отклон’ять, отклон’ить | rejected | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| откомандир’овывать, откомандиров’ать | assigned | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| открыв’ать к’арты | reveal his hand | impf. + f. pl. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отл’ичие | as distinct from | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отмен’ение | cancellation | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отмен’ять, отмен’ить | overrule | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отм’етка | ‘mark’, level | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отмеч’ать, отм’етить | marking | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отмыв’ание | money-laundering; treats . . . as; intended for | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отнош’ение | in this respect/regard | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отп’ор | repulse the enemy | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отправл’ять, отпр’авить | sacked | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отправн’ая т’очка | starting point | adj. + f. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отпуск’ать, отпуст’ить | has been allowed to; released | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отпускн’ой | factory-gate price; work off their salaries | adjective | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отраж’ение | repelling | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ’отрасль | branch of industry | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отрез’ать, отр’езать | cut off escape | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отрек’аться, отр’ечься | renounces; abdicate | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отреч’ение | abdication | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отреш’ение | suspension | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отр’инуть | jettisoned | pf. only | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отср’очка | postponement | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | see also реструктуризация |
| отст’авка | resignation; resign | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отста’ивать, отсто’ять | advocate | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отстран’ять, отстран’ить | relieved of command | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отступ’ать, отступ’ить | retreat; receded | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отступл’ение | digression from | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отступн’ое | compensation | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отх’оды | waste; report | noun (m. pl.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отч’итывать, отчит’ать | reprimands, tells off | + dat., за + acc. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| отчужд’ать, отчуд’ить | sequestered | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| оформл’ять, оф’ормить | filled in, made out | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| офш’ор | offshore zones | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| офш’орный | offshore accounts; offshore transactions | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| охв’ат | in coverage of the population | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| охв’атывать, охват’ить | Europe is gripped by; area occupied by the fire | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| охлажд’ать, охлад’ить | cooled | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ох’ота | witch-hunt | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| оц’енивать, оцен’ить | evaluate | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| очев’идец | eyewitness | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| очередн’ой | latest; next | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пад’ение | fall | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пак’ет | slate of candidates; holdings of shares; controlling holding; raft of measures; set of agreements | noun (m.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пак’етный | voting by list of policies / slate of candidates | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пал’ата | [assembly/parliament] house | noun (f.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| п’алец | one can count . . . on one’s fingers/on the fingers of one hand | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| паних’ида | held a funeral service; memorial service | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| паразит’изм | welfare sponging | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| парализов’ать | paralysed, stopped | verb (impf.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пар’ировать | parries | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| парит’етный | on a parity basis | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| парк | fleet | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| парк’овка | parking | noun (f) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| парк’овочный | parking | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| парламент’арий | MPs | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| п’артия | political parties; consignment | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пассажировмест’имость | passenger capacity | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| п’ейджер | pager | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пенси’онный | pension fund | adjective | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| п’еня | fine; as a priority | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| перевод’ить, перевест’и | transfer | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| перевор’от | coup | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| перевыполн’ять, перев’ыполнить | overfulfil | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| перегов’орщик | negotiators; negotiating partner | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| перегов’оры | peace negotiations; to the negotiating table; summit talks/negotiations | pl. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| перегр’узка | excess | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| передав’ать, перед’ать | hand over | + acc. + inst. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| передов’ой | front-line troops; progressive, advanced; leading article, ‘leader’ | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пере’игрывать, переигр’ать | overacted | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пере’избранный | re-elected to | p.p. passive | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| перекл’адывать, перелож’ить | shift responsibility onto | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| переключ’ать, переключ’ить | shift | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| переключ’ение | switching | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| перел’ом | alteration, change | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| перем’енный | with variable yields | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| перем’ирие | truce | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| перенац’еливание | retargeting | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| перен’ос | postponement; put off; postpone | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| переобуч’аться, переобуч’иться | be retrained | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| переоформл’ение | restructuring | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| переохлажд’ение | refreezing | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| переоц’енивать, переоцен’ить | overestimate | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| переп’алка | verbal skirmishing | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| переподгот’овка | retraining | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| перераб’атывать, перераб’отать | rework, revise; processes | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| перераб’атывающий | processing factories | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| перераб’отка | waste processing; redrafting | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| перераспредел’ение | reallocation of responsibilities; redistribution of wealth | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| перераспредел’ять, перераспредел’ить | redistribute | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| перераст’ать, перераст’и | expand into | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пересек’ать, перес’ечь | cross | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| перестан’овка | reshuffles; personnel change | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| перетр’яска | shake-up | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| перет’ягивать, перетян’уть | win over to his side | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| перехв’атывать, перехват’ить | took over the initiative | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| перехитр’ить | outwitted | pf. only | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| п’еречень | list | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| переш’агивать, перешагн’уть | will exceed | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| персон’ал | staff | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| персон’альный | one on one | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | see also under один |
| перспект’ива | chances, prospects; in the long term | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пет’иция | petition | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| печ’атный стан’ок | printing press | adj. + m. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пи’аровец | PR persons | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пивн’як | pub | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пик | peak | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пикет’ирование | picketing | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пирам’ида | pyramid | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пит’ание | food | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пл’авающий | floating | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| план | foreground; background – the analogy is with the planes or levels of scenery on a stage or film set and with the areas – front, middle and rear – defined by them | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| план’ировать, заплан’ировать | planned | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пл’ановый | planned | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| плест’ись | are being hatched | r., impf. only | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| плеч’о | within [their] powers; give its support to; drift with the current | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| побежд’ать, побед’ить | won | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| поб’очный | ‘collateral damage’ | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| побужд’ать, побуд’ить | caused | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пов’естка | lit. and fig. agenda; summons, subpoena; lit. and fig. turned/trained its weapons on | noun (f.) | technical.journalistic | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| п’овод | reins | m., pl. -ь’я | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| п’овод | cause, reason; about, in relation to | m., pl. -ы | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| повод’ок | leash | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| поврежд’ение | damage | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| повыш’ать, пов’ысить | increase | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| повыш’ение | promotion; increase | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| погаш’ать, погас’ить | pay off | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| погаш’ение | clearing, cancelling; redeeming | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| погран’ичник | border guards | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| подав’ать, под’ать | against which its creditors brought a court action | verb | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| подавл’ять, подав’ить | crushed | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| подавл’яющий | overwhelming majority | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| под’ача | tabling of amendments | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| подбир’ать, подобр’ать | recruit; select | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| подверг’ать, подв’ергнуть | subjected to; called into question | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| подверг’аться, подв’ергнуться | was subjected to | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| подв’ижка | fig. first moves: lit. breaking the ice; let down; prepared | noun (f.) | technical.journalistic | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | see also итоги |
| подгот’овка | preparations for | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| п’одданный | subjects | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| п’одданство | citizenship | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| подд’ерживать, поддерж’ать | support; m. or f., declines like adj.; client [of defence lawyer] | verb | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| подключ’ать, подключ’ить | attached to | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| подключ’ение | inclusion | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| подкос’ить | did for | verb (pf.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| п’одкуп | bribery | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| подлив’ать, подл’ить | pour oil on the fire | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| подмин’ать, подм’ять | dominate | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| подним’ать, подн’ять | raised the issue of | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| под’обие | come to resemble; something like | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| подозрев’аемый | suspect; m. or f., declines like adj.; charges | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| подох’одный | income tax | adjective | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| подп’исываться, подпис’аться | endorse | r., под + inst. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| подразумев’аться | were implied | r., impf. only | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| подр’обность | without going into details | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| подрыв’ать, подорв’ать | undermined | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| подр’яд | contracts | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| подр’ядчик | contracting firms | noun (n.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| подс’обный, подс’обная | as an ancillary worker | m. or f., declines like adj. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| подставл’ять, подст’авить плеч’о | lend their support | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| подсуд’имый | accused; counting of votes | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| подт’алкивать, подт’олкнуть | will depress the rouble; caused | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| подтвержд’ать, подтверд’ить | affirmed; enthuses; emphasized, stressed; m. or f., declines like adj.; subordinates | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| подчин’ять, подчин’ить | place under the command of | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| подчин’яться, подчин’иться | are under the command of | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| позвол’ять, позв’олить | permit | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| поз’иция | positions, stances | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пойт’и | go for, accept | — | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| показ’ание | evidence, testimony | n., usually pl. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| показ’атель | indices | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| показ’ательный | indicative, symptomatic | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| покварт’альный | quarterly; admirers | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| покуп’ательский | consumer demand | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| покуш’ение | assassination attempt | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| п’оле | area of special attention | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| полз’учий | creeping; political prisoners | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| политик’анство | intrigue | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| полиэтн’ический | multi-ethnic | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| полномасшт’абный | full-scale | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| полном’очие | powers | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| полож’ение | regulations; state of emergency | noun (n.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| полуг’одие | half year; having got its own way; home help | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| понят’ой | come forward as witnesses | m., declines like adj. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| попад’ание | direct missile hits | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| попеч’ительский сов’ет | supervisory board | adj. + m. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| попр’авка | amendments | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пор’ог | verge/edge [lit. threshold] of ruin | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| портф’ель | portfolios | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| поруч’ать, поруч’ить | has instructed | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| поруч’ение | on the personal instructions | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пор’ядок | in the manner stipulated; of an order of magnitude greater than | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| посад’ить маш’ину | land a plane | pf. + f.: impf. сажать | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| посл’едовательный | consistent | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| посл’едствие | with all the consequences which follow from that; clear away the results | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пос’обие | benefit | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| поср’едник | go-between | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| поср’едничество | mediation | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пост | posts | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пост’авка | delivery; direct delivery; supplies | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| поставл’ять, пост’авить | deliver | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| поставщ’ик | suppliers; suppliers | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| постановл’ение | decision; befell | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| посто’янный | with fixed yields | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| постул’ат | assumption | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| поступл’ение | revenues | noun (n.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пост’упок | act | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| посяг’ательство | encroachments; shall encroach upon | n., на + acc. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| потас’овка | brawl | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| потепл’ение | warming; global warming | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пот’ок | revenue streams | noun (m.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| потреб’итель | consumer | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| потребл’ение | consumption | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| потр’ебность | necessity | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| потряс’ать, потряст’и | lit. shook, fig. shocked | verb | technical.journalistic | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| потряс’ение | shocks | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| похищ’ать, похит’ить | embezzled | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| похищ’ение | kidnapping; stealing | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| п’очва | grounds for speculation; honorary; guard of honour | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пош’атываться, пошатн’уться | will be shaken | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| п’ошлина | excise duty; slap in the face | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| поясн’ять, поясн’ить | clarify | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| прав’ительство | government | noun (n.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пр’авить | ruled | impf. only, + inst. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| правл’ение | rule | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пр’аво | right to use force; human rights and freedoms; international law | noun (n.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| правов’ой | legal, related to the law | adjective | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| правоохран’ительные ’органы | forces of law and order | adj. + pl. | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| правопор’ядок | law and order | noun (m.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пр’авящий | ruling party | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пре’амбула | preamble to | f., + gen. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| превал’ирование | domination | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| превент’ивный | preventive strike – fig. and lit. | adjective | technical.journalistic | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| превосход’ить, превзойт’и | exceeded all expectations | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| превыш’ать, прев’ысить | exceeds | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| превыш’ение | exceeding their powers | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| предвар’ительный | preliminary | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| предвар’ять, предвар’ить | precede | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| предв’ыборный | electoral | adjective | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| преддв’ерие | on the threshold of | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | see also порог |
| пред’ельно | extremely, as . . . as possible | adverb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| предлож’ение | supply; proposal | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| предм’ет | purpose | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| предоставл’ение | grant | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| предоставл’ять, предост’авить | supply with | + acc. + dat. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| предостерег’ать, предостер’ечь | warns | + acc. + от + gen. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| предотвращ’ать, предотврат’ить | forestall, stave off | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| предотвращ’ение | prevention | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| предполаг’ать, предполож’ить | presupposed | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| предприним’ательский | entrepreneurial | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| предрасс’удок | prejudice | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| предрек’ать, предр’ечь | were forecasting | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| предск’азывать, предсказ’ать | predict | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| представ’ать, предст’ать | appear before | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| представ’итель | representative | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| представ’ительство | representation | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| представл’ение | concepts | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| представл’ять, предст’авить | under consideration; present themselves for election | verb | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| предсто’ящий | forthcoming | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| предупрежд’ение | warning | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| предусм’атривать, предусмотр’еть | providing for, stipulating | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| предусм’отренный | stipulated, laid down | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| предш’ествовать | preceded | impf. + dat. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| предъявл’ять, предъяв’ить | show; sue; presented with | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| предыд’ущий | previous | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пре’емник | successor | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пре’емственность | continuity | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| преждевр’еменный | premature | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| презент’ация | launch | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| през’умпция | presumption of innocence | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| прекращ’ать, прекрат’ить | cease | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| прекращ’ение | ceasefire line | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пренебрег’ать, пренебр’ечь | disdained | + inst. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пр’ения | discussions | noun (n. pl.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| преодол’ение | overcoming | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| преп’ятствовать, воспреп’ятствовать | which hinders | + dat. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| прерогат’ива | prerogative; lit. cut off at the root: fig. nip in the bud | noun (f.) | technical.journalistic | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пресеч’ение | suppression | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пресл’едовать | pursues fiscal goals; persecuted | impf. only | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пресс | weight of taxation | noun (m.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пр’ессинг | pressure; the Ministry of Foreign Affairs’ press release | noun (m.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| прест’упность | criminality | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| претенд’ент | contender | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| претендов’ать | lays claim to | impf. only, на + acc. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| прет’ензия | grievances; claims | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| прецед’ент | will set a dangerous precedent | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| приближ’аться, приблиз’иться | are coming close to | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| прибр’ежный | territorial waters | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пр’ибыль | profit | noun (f.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| приватиз’ация | privatization | noun (f.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| прив’ерженность | adherence | f., к + dat. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| привлек’ать, привл’ечь | recruitment; involve in; brought the site to a state of military readiness; produce proof; acquit | verb | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| прив’язка | tying of the rouble to a foreign currency | noun (f.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| приглаш’ение | on the invitation of | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пригов’ор | sentence | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пригран’ичный | border regions | adjective | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| придав’ать, прид’ать | endows with | + acc. + dat. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| прид’ерживать, придерж’ать | stockpile | verb | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| прид’ерживаться | sticks/adheres to | impf. only in this sense, + gen. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пр’изванный | intended | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| признав’ать, призн’ать | declared | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пр’изнак | on nationality lines | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| призн’ание | recognition | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| приз’ыв | call for | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| призыв’ать, призв’ать | appeals; called to order | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| прик’идываться, прик’инуться | consider | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| примен’ение | application | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пр’имета | bad omen | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| принадл’ежность | property status | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| приним’ать, прин’ять | take decisions | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| принос’ить, принест’и | presents the draft law for examination | verb | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| принуд’ительный | compulsorily | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| принципи’альный | issues of principle | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| приобрет’атель | purchasers | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| приобрет’ать, приобрест’и | acquired | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| приорит’етный | comes first | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| приостан’авливать, приостанов’ить | suspended | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| приостановл’ение | suspension | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| присм’отр | surveillance | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| присоедин’яться, присоедин’иться | joined in with; adapt | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| приспуск’ать, приспуст’ить | at half-mast | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пр’истав | bailiffs | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| приступ’ать, приступ’ить | set about | к + dat. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| прис’яга | oath of loyalty | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| прит’ок | inflow | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| приур’очивать, приур’очить | is timed to coincide with | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| прич’астный | it has nothing to do with | adj., к + dat. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| прич’ина | causes | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| причин’ять, причин’ить | have caused | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пр’оба | by trial and error; test of strength | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пробив’аться, проб’иться | struggle through | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пр’обный | test balloon | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| проб’ой | cuts | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пров’ал | failure, collapse | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| провед’ение | carrying-out, arrangement | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| провоз’иться | waste time | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| провокаци’онный | provocative | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| провок’ация | provocation | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пр’оволочка | delays | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| прогр’аммный | keynote; software supplies | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| прод’ажный | corrupt, venal | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| продвиж’ение | promotion; progress, forward movement | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| продв’ижка | breakthroughs | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| продов’ольственный | food supply centre | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| продолж’ительность | life expectancy | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| прод’укция | output | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| про’ект | draft | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| про’ектный | financing project-by-project | adjective | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| прож’иточный м’инимум | subsistence minimum | adj. + m. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| прозр’ачность | transparency | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| про’игрывать, проигр’ать | who lost | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| произв’ол | arbitrariness | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пр’оиски | machinations | noun (m. pl.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| происхожд’ение | origin, descent | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пролонг’ирование | extension; not thoroughly/fully worked out/studied | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| прораб’отка | preliminary study | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| прор’очество | prophecies | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| прор’ыв | breakthrough | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| просв’ет | ray/gleam of hope | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| проср’оченный | past their sell-by date | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| простр’анство | single economic area | noun (n.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| просч’итываться, просчит’аться | miscalculated | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| протекцион’изм | nepotism – often also протекция | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| прот’ивиться, воспрот’ивиться | was against | r., + dat. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| противоб’орствующий | opposing force | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| противов’ес | counterweight | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| противод’ействие | opposition, resistance | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| противопол’ожный | opposite | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| противор’ечие | contradictions; dissensions | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| противосто’яние | confrontation | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| проток’ол | declaration of intentions | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| проток’ольный | formal | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| проф’ильный | specialized | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| процед’ура | procedures | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| проц’енты | with interest | noun (m. pl.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| проц’есс | trial, legal proceedings | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| прям’ой | is going out live; live link-up; direct elections; direct missile hits | adjective | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пуленепробив’аемый | bullet-proof | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| пункт | paragraphs | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| п’утать, сп’утать | threw into confusion: lit. shuffled their cards; tickets, places; prep. + gen.; by means of | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| путь | fig. find a way to; got rid of; are working on the off-chance | noun (m.) | technical.journalistic | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| работод’атель | employers | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| раб’очий | working meetings | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| радиоперехв’аты | radio intercepts | noun (m. pl.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| разбир’ать, разобр’ать | analyse | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| разбир’ательство | legal investigation | noun (n.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| разбир’аться, разобр’аться | knows well, is an expert on | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| разб’орка | sifting of debris | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| разбр’ос | spread of prices | noun (m.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| разв’едданные | intelligence | pl. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| разв’едчик | spy, agent; unfolding, development; spread, developed | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| разглаш’ать, разглас’ить | announce publicly | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| разг’он | dispersal | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| разгосударствл’ение | denationalization | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| разд’ача | handing-out | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| раздел’ять, раздел’ить | shares | verb | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| разл’ад | falling-out | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| размещ’ение | placing, depositing | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| размор’аживать, размор’озить | unfreeze | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| размор’озка | unfreezing | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| размышл’ение | for thinking it over | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| разногл’асие | disputes | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| разраб’атывать, разраб’отать | have drawn up; is being developed | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| разраб’отка | exploitation; working-out, development; raw materials workings; devices | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| разраж’аться, разраз’иться | which has broken out | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| разреш’ать, разреш’ить | have not solved | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| разреш’ение | solution; destroyed | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| разр’яд | category | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| р’амочный д’оговор | framework accord | adj. + m. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ранг | above his station | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| р’анняя нефть | crude oil | adj. + f. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| раск’алываться, раскол’оться | are/have split along | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| раск’ачивать, раскач’ать | rock the boat | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| расквартир’овывать, расквартиров’ать | quartered | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| раск’ол | split | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| раскр’учиваться, раскрут’иться | be unleashed | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| расп’ад | break-up | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| распл’ачиваться, расплат’иться | pay off | r., c + inst. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| располаг’ать | when one has at one’s disposal | impf. only in this sense, + inst. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| располаг’ать, располож’ить | win over | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| располз’аться, расползт’ись | is spreading, widening | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| распоряж’аться, распоряд’иться | made arrangements for | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| распр’ава | violence; dealt harshly with | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| распредел’ение | sharing-out; distribution | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| распредел’ять, распредел’ить | distribute | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| рассекр’ечивать, рассекр’етить | open up meetings | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| рассл’едование | investigation | noun (n.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| рассм’атривать, рассмотр’еть | considered; under examination; looked at a series of issues | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| расставл’ять, расст’авить | is positioning | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| расстык’овка | undocking | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| рассужд’ение | discussions | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| рассчитанный | aimed at, intended for | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| рассч’итывать, рассчит’ать | expects; is counting on | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| расс’ылка | distribution | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| расторг’ать, раст’оргнуть | annul | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| растр’ата | squandering | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| расх’од | consumption; expenditures | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| расход’иться, разойт’ись | different from | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| расх’одование | expenditure | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| расх’одовать, израсх’одовать | spent | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| расх’оды | expenditure | noun (m. pl.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| расц’енивать, расцен’ить | assessed; payments | verb | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| расш’иренный | at full strength | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| расшир’ять, расш’ирить | increase | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| р’аунд | stage, round | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| реаг’ирование | rapid response groups [of police] | noun (n.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| реаг’ировать, отреаг’ировать | react to | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| реализ’ация | implementation | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| реализ’овывать, реализов’ать | carry out, stick to; are selling off | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| реаним’ация | intensive care | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| рев’анш | backlash | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| реги’он | regions | noun (m.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | see also край, область, округ, участок |
| регл’амент | rules; regulations | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| регул’ирование | running | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ре’естр | register | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| реж’им | timetable; either in text or graphics mode; round the clock; ordinary prison/labour camp; on automatic pilot | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| резон’анс | response | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| резюм’е | CVs | noun (n.); noun (indecl.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| р’ейтинг | popularity ratings; personnel recruiters | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ремонт’ировать, отремонт’ировать | repair | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| рент’абельность | rate of profit; repatriated persons | noun (f.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| репл’ика | retort | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| репорт’аж | journalists’ reports | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| респонд’ент | respondents | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| рестит’уция | restitution | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| реструктуриз’ация | restructuring; restructured | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| рефер’ендум | referendum | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| рефинанс’ирование | refinancing | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| рецикл’ирование | recycling | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| реципи’ент | recipient | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| речь | gave his keynote speech | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| реш’ение | decision; solution | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| реш’имость | determination | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ри’эльторский | real estate | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| рожд’аемость | birth rate | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| р’озничный | retail prices | adjective | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| р’озыск | police inquiry | noun (m.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| роков’ой | fateful | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| р’оспуск | dissolution; sacking, dismissal; citizens of the Russian Federation, as distinct from ðóccêèe, ‘ethnic Russians’ | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| рост | growth | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| рук’а | at first hand; played into the hands of | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| руковод’итель | leader | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| руков’одствоваться | follow; were guided by | r., impf. only, + inst. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| р’усло | contributed to: lit. русло = ‘channel’: fig. course, state of affairs; by directing into the right channel | noun (n.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| р’усский, р’усская | ethnically Russian, as opposed to россиянин and россиянка | m. and f. adj. | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | see above about this important distinction |
| р’ынок | stock market | noun (m.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | see also финансовый рынок, валютный рынок, убыточный рынок |
| р’ыночный | market economy | adjective | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| рыч’аг | leverage | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| р’экет | organized crime: [US] ‘racket’ | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| рэкет’ир | rank-and-file; fig. will take over, lit. will sit behind the driving wheel | noun (m.) | technical.journalistic | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| сайт | internet site | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| с’аммит | summit | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| самов’ольный | AWOL – absent without leave | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| самозв’анец | pretender | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| самоц’ель | end in itself | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| с’ани | put the cart before the horse; has been promoted above his ability, is out of his depth; sanctions; savings | pl. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| сбив’ать, сбить | beat down; bring down | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| сближ’ать, сбл’изить | bring . . . closer | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| сближ’ение | rapprochement | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| сбор | tax-gathering | noun (m.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| сб’орка | screwdriver assembly, i.e. not manufacture | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| сбыв’аться, сб’ыться | which come true; disposal, sale | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| сбытов’ой | sales network | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| св’аливаться, свал’иться | which befell | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| св’едения | information | noun (n. pl.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| св’етский | social life; reduction; will curtail; settle scores; will come/amount to nothing; come down to . . .; news summaries | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| свой | insists on having his own way; have one’s say; tying himself down | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| сдав’аться, сд’аться | give up | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| сд’ача | hit back at; improvements | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| сд’елка | deal; interest on transactions | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| сд’ерживание | nuclear deterrence | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| сд’ерживать, сдерж’ать | reserved, restrained; contain; keeps his word; cost price | verb | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| секвестр’ирование | seizure; ‘honey trap’, sexual blackmail; sex appeal; G7; ‘the family’ – i.e. Boris Yeltsin’s entourage, including numerous financiers, industrialists, etc. | noun (n.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| сен’атор | senators – i.e. members of the Federation Council, the upper house of the Russian Parliament | noun (m.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| сер’ийный | mass production; serial murders; pf., in this sense, пос’етовать; were lamenting | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| сигнализ’ировать, просигнализ’ировать | acted as a warning | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| с’ила | lies within my power; come into force | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| силовик’и | representatives of the security forces, internal and foreign affairs ministries; power structures; security departments | pl. | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| синдиц’ировать | syndicated; weather forecasters | verb (impf./pf.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ситу’ация | situation | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| сиюмин’утный | immediate | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| сказ’аться | have an effect on | r., pf. only, на + pr. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| скамь’я подсуд’имых | dock | f. + adj. pl. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ск’идка | discount | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| скл’адываться, слож’иться | is turning out | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| скоч’ок | leap | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ск’упка | buying-up | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| слабин’а | will give in | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| сл’амывать, слом’ить | overcome, break down | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| сл’едственный | in solitary for investigation | adjective | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| сл’едствие | investigation | noun (n.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| слив’аться, сл’иться | merging | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| сли’яние | merger; to sum up | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| сл’ушание | hearing; replacement; shift; generation | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| см’ертность | death rate; accounts | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| смир’яться, смир’иться | have become reconciled to | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| смущ’аться, смут’иться | not in the least embarrassed | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| смягч’аться, смягч’иться | relaxed; softening; relaxation; reduction, lowering; removal, lifting | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| собес’едник | interlocutor, partner; collectability of taxes | noun (m.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| собир’ание | process of tax collection; keep to, ensure | noun (n.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | see also сбор налогов |
| соблюд’ение | observance | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| соболезнов’ания | condolences | noun (n. pl) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| с’обственник | property-owner | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| с’обственность | property | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| сов’ет | board of directors | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| сов’етник | advisers | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| совещ’ание | conference; joint enterprises; mutually agreed documents | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| совмещ’ать, совмест’ить | combine; prep. + dat.; in accordance with; have coordinated; be agreed | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| соглаш’ение | agreement | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| сод’ействовать | help | impf. and pf. + dat. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| содерж’ание | for the upkeep; staff costs | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| содерж’ательный | rich in content | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| содерж’ать | maintain | impf. only | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| с’озыв | term; make redundant; cut short; reduce their expenses | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| сокращ’ение | reduction; judgment of Solomon | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| соображ’ать, сообраз’ить | realized what’s what | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| соображ’ение | considerations | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| сообраз’ительный | bright | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| со’общество | international community | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| со’общник | accomplices | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| соотв’етствие | in accordance with | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| соотв’етствующий | appropriate, corresponding | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| соотнош’ение | correlation; rival | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| сопоставл’ять, сопост’авить | comparable | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| сопред’ельный | bordering | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| сопротивл’ение | resistance | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| сор’атник | comrades-in-arms | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| сос’едствующий | neighbouring; fellow-workers, colleagues; will concentrate on; in its new composition | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| составл’ять, сост’авить | came to | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| составл’яющая | part, component | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| состо’яние | is in no state to; wealth tax | noun (n.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| состо’ятельный | wealthy | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| состо’яться | take place; valid | r., perf. only | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| с’отовая связь | cellular communications | adj. + f. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| сотр’удничать | have collaborated | impf. only, c + inst. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| сотр’удничество | collaboration | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| сохр’анность | safety; social expenditures | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| соцобеспеч’ение | social security | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| соцстр’аховский | social insurance; fall in production | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| спас’ательные с’илы | rescue/ emergency forces | adj. + f. pl. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| спектр | spectrum | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| сп’исывать, спис’ать | written off | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| спл’ачивать, сплот’ить | united; calm | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| спос’обность | ability | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| спос’обствовать, поспос’обствовать | furthered, helped | + dat. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| справл’яться, спр’авиться | will cope with, manage | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| спрос | demand for | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| сраб’атывать, сраб’отать | is not working | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| среднеср’очный | finances; mass media | adjective | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| срок | deadlines, time-limits | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| срыв | disruption | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| срыв’ать, сорв’ать | foil, disrupt; loan | verb | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ссыл’ать, сосл’ать | were exiled | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ссыл’аться, сосл’аться | referring to | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| сс’ылка | reference; with years of exile; stabilization | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| стабилиз’ироваться | stabilized; please do not park; will raise the issue of; put to a vote; will keep posted/ informed; signed; dot the i’s; put an end to | verb (reflexive); verb (impf./pf.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ст’авка | base rate; is betting on; also pl.; stakes | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ст’авленник | protégé | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ст’алкиваться, столкн’уться | run up against | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| станд’арт | gold standard | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| становл’ение | coming into being | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| стар’ание | efforts | n., usually pl. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| стартов’ать | started up; status | verb (impf./pf.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| стать’я | clause | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| стеч’ение | gathering | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| стимул’ирование | stimulation; grit our teeth; ‘wild- cat’, spontaneous | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ст’оимость | cost; to a total value of | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| стол | complete, 100 per cent | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| стор’онник | supporters | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| стратег’ический | long-term investors | adjective | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| стр’ахование | social insurance | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| страх’овка | as a safeguard; will deflect popular discontent | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| стык’овка | docking | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| субсид’ирование | subsidizing; component parts | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| суд’ебный | by judicial means; criminal convictions | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| суд’иться | take to court | r., с + inst. | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| суд’я по | going by appearances | + dat. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| сумм’арный | total debt; you can’t have your cake and eat it; the very latest; superpower | adjective | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| сухоп’утный | ground forces | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| схв’атка | rise above the struggle; boils down to the fact that | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| сцен’арий | scenario; making use of; film crew; film clip | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| табл’о | board | n. indecl. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| т’айна | banking confidentiality; adj. + f.; the customs union of Russia, Belarus, Kazakhstan, Kirghizia and Uzbekistan | noun (f.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| тек’ущий | present; current; current expenditures | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| телегр’аф | bush telegraph, grapevine | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| тел’ежка | trolley; or сани; put the cart before the horse | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| телем’ост | satellite link-up | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| тем’атика | subject matter | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| т’емпы | pace – lit. tempo; at an intense rate | noun (m. pl.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| т’ендер | tendering process | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| т’ендерный | tender | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| тенев’ой | shadow economy | adjective | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| тер’акт | terroristic acts, terrorism – abbreviation | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| тер’ять, потер’ять | lose face | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| технокр’ат | of technocrats | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| теч’ение | there is a leak there | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| тир’аж | in a very small print run | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| толков’ание | interpretation | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| т’онус | raise morale | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| т’опливный | fuel | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| торг | deals; trading volume | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| тормоз’ить, затормоз’ить | slowed down; put the brake on | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| т’очка | dotted the i’s; has put an end to; ‘hot spots’; will start moving forward again | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| тракт’овка | interpretation | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| трампл’ин | lit. trampoline: fig. stepping-stone | noun (m.) | technical.journalistic | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| трансл’яция | transmission; broadcast from | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| тр’анспортник | transport workers | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| транш | tranche | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| траст | shareholding | noun (m.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| тр’атить, потр’атить | expended | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| тр’ебование | demands | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| тр’ейдер | [stock] trader | noun (m.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| тр’ения | rows; tripartite | noun (n. pl.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| трудоспос’обный | able-bodied | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| трудоустр’оиться | to get a job | perf. only | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| туп’ик | fig. is leading up a blind alley | noun (m.) | technical.journalistic | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| тур | round | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| турн’е | tour | noun (n.); noun (indecl.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| тус’овка | gatherings | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| т’яжба | rivalry, trial of strength | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| тяжелов’ес | heavyweights | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| тян’уть вр’емя | drag it out; which was trying to persuade | impf. + n. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| убив’ать, уб’ить | killed two birds with one stone | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ’убыль | died down | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| уб’ыток | losses | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| уб’ыточный | loss-making | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| уваж’ительный | for valid reasons | adj | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| увелич’ение | enlargement, increase | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| увел’ичивать, увел’ичить | enlarge, increase | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| увел’ичиваться, увел’ичиться | has increased | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ув’енчиваться, увенч’аться | were crowned with success | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| увольн’ение | sacking | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| угледобыв’ающий | coal-mining | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| уг’ода | as a sop to | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| угол’овник | criminals | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| угол’овный | criminal | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| уг’он | taking cars without the owner’s consent; plane hijacking; strike a bargain | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| уд’ерживать, удерж’ать | hung on to; retain | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| удешевл’яться, удешев’иться | cheapen | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| удовлетвор’ять, удовлетвор’ить | acceded to the request | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| удост’аиваться, удост’оиться | received, was awarded | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ук’аз | decree | noun (m.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| указ’ание | instructions; have settled down; which do not fit | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ультимат’ивный | final demand | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| уменьш’ать, ум’еньшить | reduce | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| уменьш’ение | reduction | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ум’еренный | moderate | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| умил’яться, умил’иться | was moved by | r. + dat. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| уничтож’ение | war of annihilation, war to the death | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| упир’аться, упер’еться | dug their heels in | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| уполном’оченный | authorized; representative | adj.: also m. decl. like adj. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| управл’енец | manager | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| управл’яемость | will be out of control | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| управл’ять, упр’авить | control, manage | + inst. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| упраздн’ять, упраздн’ить | abolished | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| упуск’ать, упуст’ить | lose sight of the fact that | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ур’а-патриот’ический | jingoistic | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| урегул’ирование | settlement | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ур’он | inflicted damage on | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ус’иливать, ус’илить | has reinforced | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ускор’ение | acceleration; agreed | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| усл’уга | services | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| усм’атривать, усмотр’еть | interpreted this as | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| усмотр’ение | at his own discretion/as he sees fit | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| уст’ав | regulations | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| уст’авный | nominal capital | adjective | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| устан’авливать, установ’ить | establish control | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| устан’овленный | in accordance with established procedures; stipulated by law | adjective | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| устр’аивать, устр’оить | did not suit; get her a job | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| устр’аиваться, устр’оиться | got a job as | r., + inst. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| устран’ение | elimination | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| уст’упка | concessions | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| утверд’ительный | confirmatory answer | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| утвержд’ать, утверд’ить | confirmed as | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| утвержд’ение | confirmation | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ут’ечка | brain drain; leaks; has scored off the other | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ухитр’яться, ухитр’иться | is clever enough to | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ух’од | lit. going: here quitting, sacking; supervision of | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ухудш’ение | worsening | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| уцел’евший | unharmed, intact | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| уч’асток | wards; voting station | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | see also край, область, округ, регион |
| уч’ение | training exercises; registered | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| уч’итывать, уч’есть | considering that; taken into consideration | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| уч’итываться, уч’есться | are accounted for; be taken into account | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| учрежд’ать, учред’ить | founded, set up | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ущемл’ять, ущем’ить | infringes the rights of | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | see also нарушать |
| ущ’ерб | harm done; damage | m. + dat. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| уязв’имый | vulnerable | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| федер’алы | federal [i.e. national] authorities | noun (m. pl.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| федер’альный | at the federal level – i.e. nationwide for the Russian Federation as a whole; lit. centre of the [Russian] Federation, i.e. Moscow | adjective | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| фикс’ированный | fixed rate of duty | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| фин’ал | ending | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| фин’ансовый | on the money markets | adjective | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ф’инишная прям’ая | brought the affair to a successful conclusion – lit. to the final straight | adj. + f. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| фонд | trust funds, [US] foundations | noun (m.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ф’ондовый | stock market | adjective | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ф’орвард | forward deals | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| формиров’ание | formation | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| формиров’ать, сформиров’ать | will form | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| формиров’аться, сформиров’аться | being formed, in formation | verb (reflexive) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| формулир’овка | phrases, formulations | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| фото-р’обот | photo-fit | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| фр’акция | factions | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| х’артия | broadcasters’ charter | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| хв’атка | relaxed his grip | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| хищ’ение | misappropriation, embezzlement | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ход | move; course; in full swing | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ходат’айствовать | petition | verb (impf./pf.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| хожд’ение | circulation | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| хоз’яйственник | managers | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | see also менеджер and управленец |
| хоз’яйственный | economic | adjective | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| хоз’яйство | peasants’ private plot | noun (n.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| х’олдинг | holding company | noun (m.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ц’арствовать | both reigned [was king] and ruled | impf. only | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| целев’ой | targeted; earmarked | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| целенапр’авленный | expedient | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| целесообр’азность | sense | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ц’елостность | integrity | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| цель | purpose | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ц’енность | values | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ц’енный | bonds, securities | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| чек’ист | trader | noun (m.) | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| черт’а б’едности | below the poverty line | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| чин’овник | functionaries | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ч’иповый | microchip designs | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ч’исленность | with a strength of | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ч’истка | cleansing, purges | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| чистопл’юйство | puritanism – also чистопл’оство | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| шант’аж | blackmail | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| швы | had cracked open at the seams | noun (f. pl.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ш’ефство | supervision, mentoring | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ш’ирма | lit. screen, fig. ‘front’ | noun (f.) | technical.journalistic | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| шкал’а | scale | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ш’оковый | state of shock; shock therapy | adjective | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| штаб | campaign headquarters; [military] staffs | noun (m.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| штамп | cliché | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| штраф | fines | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| шум’иха | row; shows mercy to | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| щегол’ять, щегольн’уть | show off | verb | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| щекотл’ивый | ticklish | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| эваку’ация | evacuation | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| эваку’ировать | evacuated in good time | verb (impf./pf.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| эг’ида | under the aegis of – N.B. only in this expression | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| эксклюз’ивный | exclusive interview | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| эксперт’иза | provision of expert testimony; expert examination; urgent | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| электор’ат | electorate | noun (m.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| электроснабж’ение | electricity supply | noun (n.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| эл’ита | élite | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| эмб’арго | embargo | noun (n.); noun (indecl.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| эмисси’онный | money-printing | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| эм’иссия | printing of money | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| эмит’ент | issuing authorities | noun (m.) | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| эмит’ировать | issued | verb (impf./pf.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| энергонос’итель | energy resources | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| эскал’ировать | escalate | verb (impf./pf.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| эт’ап | stage | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| этап’ирование | escorting | noun (n.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| эф’ир | airwaves | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| эшел’он | level; anniversary | noun (m.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| юрид’ический | legal; n. + m. gen.; bone of contention | adjective | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| ’явка | turnout | noun (f.) | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| яйцегол’овый | eggheads | m., decl. like adj. | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | — |
| а/я | абонементский ящик (PO Box) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| авиа- | air (e.g. авиалиния, airline; авианал¸т, air attack; авиаписьмо, airmail letter) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| АО | акционерное общество (Co. Ltd) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| АОЗТ | акционерное общество закрытого типа | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| АООТ | акционерное общество ограниченного типа | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| АРБ | Ассоциация российских банков | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| АЭС | атомная электростанция | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| БАБ | Boris Abramovich Berezovskii (a leading ‘oligarch’) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| бензо- | petrol (e.g. бензоколонка, petrol station) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| бомж | без определ¸нного места жительства (of no fixed abode) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| броне- | armoured (e.g. бронежилет, armoured vest) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| ВБ | Всемирный Банк (World Bank) | abbreviation/acronym | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| ВВП | валовая всенациональная продукция (GNP) | abbreviation/acronym | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| ВВС | военно-воздушные силы (Russian Air Force) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| вице- | vice-, e.g. вице-премьер | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| ВМФ | Военно-морской флот (Russian Navy) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| ВПК | военно-промышленный комплекс | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| врио | временно исполняющий обязанности (temporary acting) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| ВС | Верховный Суд | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| ВСМ | высокоскоростная магистраль (Russian TGV) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| ВУЗ | высшее учебное заведение | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| ВЦМК | Всероссийский Центр Медицины Катастроф | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| ВЭБ | Внешне-Экономический Банк | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| г. | год | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| ГАИ | Государственная Автомобильная Инспекция | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| ген- | генеральный (e.g. генпрокуратура, генштаб) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| ГК | Гражданский кодекс | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| ГКО | государственные кратковременные облигации | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| ГКС | Государственный Комитет Связи, Госкомсвязи | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| гор- | городской (e.g. горсуд, горком) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| гос- | государственный (e.g. госрегулирование, госдепартамент, State Department) | abbreviation/acronym | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| Госкомсвязи | Государственный Комитет Связи (State Communications Committee) | abbreviation/acronym | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| Госкомспорт | Государственный Комитет Спорта (State Sports Committee) | abbreviation/acronym | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| Госкомстат | Государственный Комитет Статистики (State Statistics Committee) | abbreviation/acronym | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| губ- | губернский | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| Евро- | Euro- or European (e.g. Еврокомиссия, European Commission; Евровидение, Eurovision; евростандарт, European standard [of design, comfort, quality, strength etc.]; Евросоюз, European Union) | abbreviation/acronym | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| евро | euro (e.g. евростандарт) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| ЕЕВ | единая европейская валюта | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| ЕС | Европейское Сообщество | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| ЗАГС | запись актов гражданского состояния | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| зам- | заместитель (on its own, as in работать замом: in combination, as in зампред, deputy chairman or замминистра, deputy minister) | abbreviation/acronym | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| и. о. | исполняющий обязанности (acting) и т.д., и т.п.   и так далее, и тому подобное (etc., etc.) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| избир- | избирательный (e.g. центризбирком) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| им. | имени (named after/ [US] for) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| кг. | килограмм | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| км. | километр | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| КНР | Kèòàécêàÿ народная республика | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| -ком | комитет, e.g. оргком (= организационный комитет), or комиссия, e.g. избирком (= избирательная комиссия) кор- or -кор     generally, as a prefix, корреспондентский, e.g. корсч¸т; as a suffix, корреспондент, e.g. спецкор | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| KC | Kîícòèòóöèîííûé суд | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| л. | литр | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| МБРР | Международный Банк Реконструкции и Развития (IBRD) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| МВД | Министерство Внутренних Дел (Russian Home Office) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| МВФ | Международный Валютный Фонд (IMF) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| МИД | Министерство Иностранных Дел (Russian Foreign Office) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| Минатом | Министерство Атомной Энергии | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| Мингосимущества | Министерство государственного имущества | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| Минздрав | Министерство здравоохранения | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| Минкульт | Министерство Kóëüòóðû | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| Миннац | Министерство национальностей | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| Минтоп | Министерство топлива и энергетики | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| Минфин | Министерство Финансов млд. or млрд.     1,000,000,000 | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| млн. | 1,000,000 | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| ММББ | Московская Межбанковская Биржа (Moscow Inter- Bank Exchange) | abbreviation/acronym | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| ММВБ | Московский Международный Валютный Банк | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| МПС | Министерство путей сообщения | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| МЧС | Министерство чрезвычайных ситуаций (Ministry for Emergencies) | abbreviation/acronym | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| нарко-: | = drug-, narco- (e.g. наркобизнес, наркоделец, наркокартель, наркокурьер, наркосделка, наркотрафик) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| НАТО | NATO | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| нефте- | oil (e.g. нефтепродукты) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| НИИ | научно-исследовательский институт | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| ОАК | Освободительная армия Kîcîâà (KLA) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| ОАО | ограниченное акционерное обшество | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| обл- | областной | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| ОБСЕ | Организация Безопасности и Сотрудничества в Европе (OSCE) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| ОВВЗ | облигация внешнего валютного займа | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| ОМОН | отряд милиции особого назначения | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| ООН | Организация Объедин¸нных Наций (UN) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| ООО | общество с ограниченной ответственностью | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| ОРТ | Общественное российское телевидение (channel 1 of Russian TV) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| ПВО | противовоздушная оборона | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| ПДД | правила дорожного движения | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| ПО | производственное объединение | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| погранвойска | пограничные войска (border troops) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| полит- | политический (e.g. политдиректор) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| постпред | постоянный представитель | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| ПРО | противоракетная оборона (NMDS, National Missile Defence System, ‘son of Star Wars’) | abbreviation/acronym | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| р. | рубль | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| рай- | районный | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| РАН | Российская Академия Наук | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| РАО | Российское Акционерное Общество | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| РИА | Российское Информационное Агентство | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| РНИСиНП | Российский независимый институт социальных и национальных проблем | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| РСФСР | Российская советская федеративная социалистическая республика (predecessor of the Российская Федерация) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| руб. | рубль | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| РУВД | районное управление внутренними делами | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| РУОП | районное управление органами правопорядка | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| РФ | Российская Федерация | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| СБ | Совет безопасности | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| СВР | Служба внешней разведки (Russian equivalent of MI6) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| СИЗО | следственный изолятор | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| СКВ | свободно конвертируемая валюта (hard currency) | abbreviation/acronym | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| СМИ | средства массовой информации (mass media) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| СНГ | Содружество независимых государств (CIS) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| cîâ- | совет, e.g. Cîâáåç (Совет безопасности) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| соц- | социальный | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| СП | совместное предприятие | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| спец- | специальный, e.g. спецназ (troops) специального назначения (Russian equivalent of the SAS), спецпредставитель (special representative), спецслужбы (secret services) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| СРЮ | Союзная Республика Югославии | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| супер- | super-, e.g. супердержава | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| СФ | Совет Федерации (upper house of Russian parliament) | abbreviation/acronym | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| США | Соедин¸нные Штаты Америки (USA) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| СЭЛТ | система электронных лотовых торгов (electronic share- and currency-dealing system) | abbreviation/acronym | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| т. | тонна (tons) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| т.е. | то есть (i.e.) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| теле- | as in телеобращение (televised address/appeal) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| ТОО | товарищество с ограниченной ответственностью | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| тыс. | тысяча | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| УК | Уголовный Kîäåêc | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| управделами | управляющий делами (business manager) | abbreviation/acronym | technical.commercial | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| ФАПСИ | Федеральное агентство правительственной связи и информации (Russian government information service) | abbreviation/acronym | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| ФБР | Федеральное Бюро Разведывания (FBI) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| ФНПР | Федерация независимых профсоюзов России (Russian TUC) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| ФСБ | Федеральная Служба Безопасности | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| ФСНП | Федеральная Служба Налоговой Полиции | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| ЦБ | Центральный Банк (also sometimes Центробанк) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| центр- | центральный (e.g. центризбирком) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| ЦРУ | Центральное Разведывательное Управление (CIA) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| Чека | abbreviated from the initials of Чрезвычайная Kîìèccèÿ по борьбе с контрреволюцией, саботажем и спекуляцией, the first Soviet political police organization | abbreviation/acronym | technical.administrative | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| ЧП | чрезвычайное происшествие or положение | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| ЧЭС | Черноморский Экономический Союз | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| ЭВМ | электронная вычислительная машина (computer) | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| экс- | ex-, e.g. экс-министр | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| ЮАР | Южно-африканская республика | abbreviation/acronym | technical | — | contemporary (source published 2000) | — | — | dictionary | n/a | n/a | From the book's own 'Acronyms and Abbreviations' appendix (pp. 114-119) |
| Аграрии | party led by Nikolai Kharitonov | proper noun (political party/bloc) | technical.administrative | — | contemporary (source published 2000; parties current as of 1999-2000) | Russia | national | dictionary | n/a | n/a | From the book's 'Names of Russian Political Parties' appendix (p. 120) |
| Впер¸д Россия | party led by Boris Fedorov | proper noun (political party/bloc) | technical.administrative | — | contemporary (source published 2000; parties current as of 1999-2000) | Russia | national | dictionary | n/a | n/a | From the book's 'Names of Russian Political Parties' appendix (p. 120) |
| Вся Россия | party formed from Отечество and Российские регионы | proper noun (political party/bloc) | technical.administrative | — | contemporary (source published 2000; parties current as of 1999-2000) | Russia | national | dictionary | n/a | n/a | From the book's 'Names of Russian Political Parties' appendix (p. 120) |
| Голос России | party headed by Mintimer Shaimiev and Konstantin Titov | proper noun (political party/bloc) | technical.administrative | — | contemporary (source published 2000; parties current as of 1999-2000) | Russia | national | dictionary | n/a | n/a | From the book's 'Names of Russian Political Parties' appendix (p. 120) |
| Духовное наследие | political movement led by Aleksei Podberiozkin | proper noun (political party/bloc) | technical.administrative | — | contemporary (source published 2000; parties current as of 1999-2000) | Russia | national | dictionary | n/a | n/a | From the book's 'Names of Russian Political Parties' appendix (p. 120) |
| Единство | electoral bloc headed by Sergei Shoigu and including a number of provincial governors, supportive of the Russian President | proper noun (political party/bloc) | technical.administrative | — | contemporary (source published 2000; parties current as of 1999-2000) | Russia | national | dictionary | n/a | n/a | From the book's 'Names of Russian Political Parties' appendix (p. 120) |
| КП | Коммунистическая Партия (e.g. КПРФ – Коммунистическая Партия Российской Федерации) | proper noun (political party/bloc) | technical.administrative | — | contemporary (source published 2000; parties current as of 1999-2000) | Russia | national | dictionary | n/a | n/a | From the book's 'Names of Russian Political Parties' appendix (p. 120) |
| КРО | Конгресс Русских Общин (Russian nationalist party) | proper noun (political party/bloc) | technical.administrative | — | contemporary (source published 2000; parties current as of 1999-2000) | Russia | national | dictionary | n/a | n/a | From the book's 'Names of Russian Political Parties' appendix (p. 120) |
| ЛДПР | Либерально-Демократическая Партия России (Russian nationalist party led by Vladimir Zhirinovskii) | proper noun (political party/bloc) | technical.administrative | — | contemporary (source published 2000; parties current as of 1999-2000) | Russia | national | dictionary | n/a | n/a | From the book's 'Names of Russian Political Parties' appendix (p. 120) |
| Народовластие | party led by Nikolai Ryzhkov and Stanislav Govorukhin | proper noun (political party/bloc) | technical.administrative | — | contemporary (source published 2000; parties current as of 1999-2000) | Russia | national | dictionary | n/a | n/a | From the book's 'Names of Russian Political Parties' appendix (p. 120) |
| НДР | Наш Дом Россия (party led by Viktor Chernomyrdin and Aleksandr Shokhin) | proper noun (political party/bloc) | technical.administrative | — | contemporary (source published 2000; parties current as of 1999-2000) | Russia | national | dictionary | n/a | n/a | From the book's 'Names of Russian Political Parties' appendix (p. 120) |
| Новая сила | party of Sergei Kirienko | proper noun (political party/bloc) | technical.administrative | — | contemporary (source published 2000; parties current as of 1999-2000) | Russia | national | dictionary | n/a | n/a | From the book's 'Names of Russian Political Parties' appendix (p. 120) |
| О-ВР | Отечество-вся Россия (pro-Luzhkov electoral bloc) | proper noun (political party/bloc) | technical.administrative | — | contemporary (source published 2000; parties current as of 1999-2000) | Russia | national | dictionary | n/a | n/a | From the book's 'Names of Russian Political Parties' appendix (p. 120) |
| Отечество | party led by Vladimir Luzhkov | proper noun (political party/bloc) | technical.administrative | — | contemporary (source published 2000; parties current as of 1999-2000) | Russia | national | dictionary | n/a | n/a | From the book's 'Names of Russian Political Parties' appendix (p. 120) |
| Правое дело | party of Anatolii Chubais, Egor Gaidar and Boris Nemtsov | proper noun (political party/bloc) | technical.administrative | — | contemporary (source published 2000; parties current as of 1999-2000) | Russia | national | dictionary | n/a | n/a | From the book's 'Names of Russian Political Parties' appendix (p. 120) |
| РНЕ | русское национальное единство (extreme-right party led by Aleksandr Barkash¸v) | proper noun (political party/bloc) | technical.administrative | — | contemporary (source published 2000; parties current as of 1999-2000) | Russia | national | dictionary | n/a | n/a | From the book's 'Names of Russian Political Parties' appendix (p. 120) |
| Российские регионы | party formed by provincial governors and headed by Oleg Morozov | proper noun (political party/bloc) | technical.administrative | — | contemporary (source published 2000; parties current as of 1999-2000) | Russia | national | dictionary | n/a | n/a | From the book's 'Names of Russian Political Parties' appendix (p. 120) |
| Союз правых сил | right-wing electoral bloc headed by Anatolii Chubais, Boris Nemtsov and Sergei Kirienko | proper noun (political party/bloc) | technical.administrative | — | contemporary (source published 2000; parties current as of 1999-2000) | Russia | national | dictionary | n/a | n/a | From the book's 'Names of Russian Political Parties' appendix (p. 120) |
| Честь и родина | party formed by Aleksandr Lebed’ | proper noun (political party/bloc) | technical.administrative | — | contemporary (source published 2000; parties current as of 1999-2000) | Russia | national | dictionary | n/a | n/a | From the book's 'Names of Russian Political Parties' appendix (p. 120) |
| Яблоко | party led by Evgenii Iavlinskii | proper noun (political party/bloc) | technical.administrative | — | contemporary (source published 2000; parties current as of 1999-2000) | Russia | national | dictionary | n/a | n/a | From the book's 'Names of Russian Political Parties' appendix (p. 120) |
| республиканская партия | led by Nikolai Lysenko | proper noun (political party) | technical.administrative | — | contemporary (source published 2000; parties current as of 1999-2000) | Russia | national | dictionary | n/a | n/a | From the book's 'Names of Russian Political Parties' appendix (p. 120) |
**Morpheme breakdown (loanword-adaptation examples only).** Russian is fusional, not agglutinative
(per `00_Extraction_Checklist.md`'s typology note), so ordinary headwords above are not
morpheme-broken. The Introduction (p. x) does flag one genuinely compositional, productive pattern
worth capturing here: English loanwords borrowed with the `-инг` gerund/nominalizing suffix, which
behaves as a real bound morpheme in modern Russian business/media jargon rather than an
inflectional ending:

> **бр’ифинг** = brief (English root, borrowed) + `-инг` (Russian loanword-nominalizer suffix,
> parallel to English `-ing`) — a fully naturalized noun ("briefing"), stress falls on the root.
>
> **л’изинг** = lease (English root, borrowed) + `-инг` — "leasing" (financial term), stress on the
> root.
>
> **монит’оринг** = monitor (English root, borrowed) + `-инг` — "monitoring"; Slatter notes (p. x)
> this one breaks the otherwise-general "stress the syllable before `-инг`" pattern the other two
> follow, restressing onto `-т’ор-` instead — an irregular subcase worth keeping if slang-mechanics
> analysis later looks at how loanword stress placement varies once `-инг` becomes fully
> productive.

## Grammar/Register points

### Register scope: what this source deliberately does and doesn't cover

Slatter states explicitly (Introduction, p. ix) that this is *not* a general Russian dictionary:
many headwords are only defined in the specific sense relevant to press/administrative/commercial
usage, and senses "assumed known" from general vocabulary are deliberately omitted (e.g. арест is
defined only in its less obvious property-related sense, not its ordinary "arrest of a person"
sense). This is itself a register-annotation practice worth flagging for future extraction work:
**absence of a common general sense in this source is not evidence the sense doesn't exist** — it
reflects the book's own scope decision, not incompleteness of the language.

### Explicit `fig.`/`lit.` labeling (the book's real register-annotation system)

Rather than dialectal/regional tags, this source's own explicit annotation system is **figurative
vs. literal sense-labeling** — `fig.` marking an idiomatic/metaphorical reading and `lit.` marking
the literal one, sometimes given side by side for the same headword (e.g. `штаб` glossed literally
as "[military] staffs" and, in a separate cited use, figuratively as "campaign headquarters";
`ширма` "screen" (lit.) vs. "front" (fig., for a money-laundering operation); `подвижка` "first
moves" carries only the fig. sense in the source, with no literal gloss given). This is the
"explicit annotation the source itself marks" the coverage rule prioritizes for this book — every
`fig.`/`lit.` label encountered was preserved in the vocabulary table's `Gloss` column verbatim
(not stripped out), since the label is doing real classificatory work the underlying English
translation alone wouldn't convey.

### Stress-marking convention

The apostrophe (`’`) immediately before a vowel in every headword marks that vowel as the stressed
syllable (Introduction, p. xii) — this is preserved in every `Term` cell of the vocabulary table
above exactly as the source prints it, since Russian stress is unpredictable from spelling and the
book's own marking is real phonological information, not an artifact to clean up.

### Neologism/borrowing pattern noted in the Introduction (pp. vii–viii)

Slatter's own discussion (paraphrased, not quoted at length) identifies three distinct channels by
which post-1985 Russian press vocabulary expanded: (1) direct English/Anglo-Saxon borrowing,
especially for business/finance terms where English is the working international language (e.g.
парламент, спикер, коттедж — though коттедж's actual referent, a suburban house with garages and
staff quarters for a "new Russian" businessman, diverges sharply from the English "cottage" it was
borrowed from — a semantic-shift-on-borrowing case worth flagging for the mechanics-analysis phase);
(2) a later "re-nationalizing" countertrend reviving vocabulary from the pre-Gorbachev Soviet period
(шефство, стихийный) or coining native compounds instead of borrowing (болото, управленец); and (3)
the `-инг` suffix pattern discussed above. This three-channel pattern (borrow / revive-native /
suffix-nativize) is a plausible candidate mechanism for the eventual `analysis/` phase once enough
`established/` content exists to compare it against.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — this file omits the source's own illustrative
Russian example sentences entirely and paraphrases its introduction; only short bracketed
English glosses (the dictionary's core definitional content, not extended prose) were retained
per headword. See `00_Reference_Extraction_Spec.md`.
