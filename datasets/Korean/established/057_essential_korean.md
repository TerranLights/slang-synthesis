# Korean — Established Vocabulary/Grammar: *Essential Korean* (full topical vocabulary)

**Source:** Ellen K. Yoon, *Essential Korean* (EKOR, 2010), pp. 1-197 (all 31 topical chapters, the
book's full main content) — plus its front-matter pronunciation guide (pp. x-xv). *Essential Korean
CD contents.pdf* (the 4-page CD1-CD5 track-number index) was checked and found to be a bare track
listing mirroring the book's own Table of Contents, with no vocabulary or grammar content of its own
— not extracted. The book's own Appendix (pp. 199-209: useful telephone numbers, metric conversion,
Seoul subway/city/country maps) and Index (p. 210+, a page locator only) were likewise out of scope —
neither is vocabulary or grammar content.

**Coverage note.** This is a 31-topic general-vocabulary/expression phrasebook (not a grammar
textbook) — it carries almost no explanatory grammar prose. Comprehensive extraction here means
**every distinct vocabulary/expression entry from every topical chapter**, which this file achieves
(1,998 table rows; the book itself repeats some headwords across multiple thematic chapters — e.g.
약국 "pharmacy/drugstore" appears under both "Places" and "Around The Neighborhood" — these are kept
as separate rows, each with its own page citation, since that's how the source itself organizes the
material).

**Vision-reading note — source PDF corruption, a new gotcha for this project.** `Essential Korean.pdf`
has zero embedded fonts and zero text layer (confirmed via `pdffonts`/`pdftotext`) — a pure scanned-image
book, exactly as predicted by the Wave K5 resume note. During reconnaissance, the raw source PDF was
also found to have a **corrupted/ambiguous page tree that causes `pdftoppm` to render the exact same
page index non-deterministically** — repeated single-page renders of PDF page 10/11 returned genuinely
different printed-page content across independent invocations, confirmed via md5sum mismatches across
3+ repeated runs. This is distinct from every previously-documented Korean PDF gotcha (font-substitution
ciphers, CID corruption, scan-order issues) — it is a page-tree-level corruption, likely from the
`pdfsam-console` tool (its own `Creator` metadata tag) having been used at some point to split/rotate/
merge this file's source pages, leaving duplicate or ambiguous object references. **Fix applied:**
`mutool clean -gggg -s` rebuilt a clean, deterministic copy (`repaired.pdf`) — 3 repeated renders of the
same page then matched exactly (md5-verified) — and all vision-reading in this file was done exclusively
from that repaired copy, with every rendered page's printed page number visually cross-checked against
the formula `printed_left_page = 2×pdf_page_number − 22` (verified against 10+ widely-spaced checkpoints
with zero deviation on the repaired copy). **Worth adding to the project's standing PDF-gotcha list**:
when a scanned source reports a real page count via `pdfinfo` but `pdftoppm`/`pdftotext` output for a
given page index is inconsistent across repeated runs, try a `mutool clean -gggg -s` (or equivalent
PDF-repair/re-serialize) pass before trusting any page-range dispatch built on that file's raw page
indices.

**Page-image structure.** Each PDF page in the repaired copy renders as a two-physical-page spread
(scanned book, open to two facing pages per image) — handled throughout.

**Marginalia.** One instance of probable previous-owner marginalia was found and excluded: a faint
stray yellow mark on the blank `<NOTE>` practice page at printed p.169, inconsistent with the book's
own printed black/red typeface — not transcribed as source content. No other marginalia was found
anywhere across the ~200 pages vision-read for this file.

**Redundancy scoping against prior Korean `established/` files (non-redundant-supplement rule).**
This book's only real explanatory-grammar content is (a) a front-matter "Speech Levels & Speech
Styles" essay and (b) a "Numbers & Classifiers" native-vs-Sino-Korean-numeral explanation.
- **(a) Skipped as redundant**: the Speech Levels & Speech Styles essay covers exactly the same
  neutral/honorific/humble speech-level territory and formal/informal/intimate speech-style territory
  already extracted in much greater depth in `established/031_korean_honorifics_and_politeness.md`
  (Lucien Brown's academic treatment) — this book's own treatment is a brief, non-technical summary
  aimed at absolute beginners and adds nothing beyond what 031 already covers.
- **(b) Partially skipped as redundant**: the general native-Korean-vs-Sino-Korean dual numeral system
  with classifiers is already documented across at least 10 prior established Korean files (001, 006,
  009, 010, 018, 020, 033, 034, 042, 045). The *vocabulary itself* (all numeral words, all classifier
  words, the full classifier-by-item chart) is still kept in full in the table below, since vocabulary
  items are never dropped as redundant per this project's convention — only the general explanatory
  grammar point is skipped. Narrower sub-rules this book's own chart/footnotes added that were **not**
  obviously already captured are kept below (the 만-based large-number grouping/omission rule, the
  irregular 유월/시월 month-reading exceptions, and the native-numeral bound-form shortening before a
  classifier).
- **Kept as genuinely new**: every other grammar/usage point below is a narrow morphological or
  pragmatic observation this book's own footnotes made that was not confirmed already present in any
  prior Korean established file (checked via targeted grep against the existing `established/`
  directory before writing this section) — these are the real payoff of this otherwise
  vocabulary-dominated source.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 뭐예요? | What is it? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | muh-eh-yo?; Basic Useful Expressions & Words > Questions With Question-words, p.3 |
| 어디예요? | Where is it? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | uh-dee-eh-yo?; Basic Useful Expressions & Words > Questions, p.3 |
| 언제예요? | When is it? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | uhn-jeh-eh-yo?; Basic Useful Expressions & Words > Questions, p.3 |
| 누구예요? | Who is it? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | noo-goo-eh-yo?; Basic Useful Expressions & Words > Questions, p.3 |
| 얼마예요? | How much is it? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | uhl-mah-eh-yo?; Basic Useful Expressions & Words > Questions, p.3 |
| 어때요? | How is it? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | uht-deh-yo?; Basic Useful Expressions & Words > Questions, p.3 |
| 어떻게요? | How is it so? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | uht-duhk-keh-yo?; Basic Useful Expressions & Words > Questions, p.3 |
| 왜요? | Why? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | weh-yo?; Basic Useful Expressions & Words > Questions, p.3 |
| (a thing)입니까? | Is it (a thing)? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | (a thing)eem-neek-gah?; Basic Useful Expressions & Words > Others, p.3 |
| 네; 예 | Yes. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | neh; yeh; Basic Useful Expressions & Words > Others, p.3 |
| 아니오. | No. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ah-nee-oh; Basic Useful Expressions & Words > Others, p.3 |
| 그래요? | Is that so? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | g_-reh-yo?; Basic Useful Expressions & Words > Others, p.3 |
| 실례합니다; 잠시만요. | Excuse me. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | sheel-leh-hahm-nee-dah; jahm-shee-mahn-yo; Basic Useful Expressions & Words > Others, p.3 |
| 잠시만요. | Just a moment, please. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | jahm-shee-mahn-yo; Basic Useful Expressions & Words > Others, p.3 |
| 죄송합니다; 미안합니다. | I am sorry. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | jweh-sohng-hahm-nee-dah (book marks this variant "humble"); mee-ahn-hahm-nee-dah; Basic Useful Expressions & Words > Others, p.3 |
| 괜찮아요. | It's OK. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gwehn-chah-nah-yo; Basic Useful Expressions & Words > Others, p.3 |
| 아니에요. | Don't mention it; What you said is not true. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ah-nee-eh-yo; Basic Useful Expressions & Words > Others, p.3 |
| 처음 뵙겠습니다. | Nice to meet you. (lit. "It's the first time to meet you.") | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | chuh-_m-bwehp-geht-s_m-nee-dah; Basic Useful Expressions & Words, p.4 |
| 축하드립니다; 축하합니다. | Congratulations. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | choo-kah-d_-reem-nee-dah (book marks this variant "humble"); choo-kah-hahm-nee-dah; Basic Useful Expressions & Words, p.4 |
| 고맙습니다; 감사합니다. | Thank you. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | goh-mahp-s_m-nee-dah; gahm-sah-hahm-nee-dah; Basic Useful Expressions & Words, p.4 |
| 안녕하세요? | How are you? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ahn-nyuhng-hah-seh-yo?; Basic Useful Expressions & Words, p.4 |
| 안녕하셨어요? | How have you been? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ahn-nyuhng-hah-shyuht-suh-yo?; Basic Useful Expressions & Words, p.4 |
| 안녕히 가세요. | Good bye. (lit. "Go in peace.") | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ahh-nyuhng-hee-gah-seh-yo; said by the person staying, to the one leaving; Basic Useful Expressions & Words, p.4 |
| 안녕히 계세요. | Good bye. (lit. "Be well.") | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ahn-nyuhng-hee-geh-seh-yo; said by the person leaving, to the one staying; Basic Useful Expressions & Words, p.4 |
| 다음에 또 봬요. | See you again next time. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | dah-_-meh ddoh bweh-yo; Basic Useful Expressions & Words, p.4 |
| 수고하세요. | Don't work too hard. (lit. "Work hard.") | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | soo-goh-hah-seh-yo; book's footnote explains this is said by a patron leaving a business, or a colleague leaving work early, to those remaining; Basic Useful Expressions & Words, p.4 |
| 미안하지만 한국말 못합니다. | I am sorry, but I can't speak Korean. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | mee-ahn-hah-jee-mahn hahn-goong-mahl moht-tahm-nee-dah; Basic Useful Expressions & Words, p.5 |
| 알아요. | I know. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ah-rah-yo; Basic Useful Expressions & Words, p.5 |
| 몰라요. | I don't know. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | mohl-lah-yo; Basic Useful Expressions & Words, p.5 |
| 알겠습니다. | I see. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ahl-geht-s_m-nee-dah; Basic Useful Expressions & Words, p.5 |
| 모르겠습니다. | I don't understand. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | moh-r_-geht-s_m-nee-dah; Basic Useful Expressions & Words, p.5 |
| 성함이 어떻게 되십니까?; 이름이 뭐예요? | What is your name? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | suhng-hah-mee uht-duhk-keh dweh-sheem-neek-gah? (book marks this variant "honorific"); ee-r_-mee mwuh-eh-yo?; Basic Useful Expressions & Words, p.5 |
| (전화번호/핸드폰 번호)가 어떻게 되세요? | What is your (telephone number/cell phone number)? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | juhn-hwah-buhn-hoh/hehn-d_-pohn-buhn-ho)gah uht-duhk-keh dweh-seh-yo?; Basic Useful Expressions & Words, p.5 |
| 그리고; 하고 | and | conjunction | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | g_-ree-goh; hah-goh; footnote: 그리고 connects sentences and occasionally nouns, 하고 connects only nouns; Basic Useful Expressions & Words > Conjunctions, p.5 |
| 왜냐하면 | because | conjunction | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | weh-nyah-hah-myuhn; Basic Useful Expressions & Words > Conjunctions, p.5 |
| 그렇지만 | but | conjunction | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | g_-ruh-chee-mahn; Basic Useful Expressions & Words > Conjunctions, p.5 |
| 그런데 | by the way | conjunction | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | g_-ruhn-deh; Basic Useful Expressions & Words > Conjunctions, p.5 |
| 그래도 | despite that | conjunction | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | g_-reh-doh; Basic Useful Expressions & Words > Conjunctions, p.5 |
| 그러나 | however | conjunction | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | g_-ruh-nah; Basic Useful Expressions & Words > Conjunctions, p.5 |
| 하나 (한) | one | numeral | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | hah-nah (hahn); native-Korean numeral, bound form 한 used before a classifier; Numbers > Korean Numbers, p.10 |
| 둘 (두) | two | numeral | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | dool (doo); native-Korean numeral, bound form 두 before a classifier; Numbers > Korean Numbers, p.10 |
| 셋 (세) | three | numeral | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | seht (seh); native-Korean numeral, bound form 세 before a classifier; Numbers > Korean Numbers, p.10 |
| 넷 (네) | four | numeral | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | neht (neh); native-Korean numeral, bound form 네 before a classifier; Numbers > Korean Numbers, p.10 |
| 다섯 | five | numeral | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | dah-suht; native-Korean numeral; Numbers > Korean Numbers, p.10 |
| 여섯 | six | numeral | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | yuh-suht; native-Korean numeral; Numbers > Korean Numbers, p.10 |
| 일곱 | seven | numeral | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | eel-gohp; native-Korean numeral; Numbers > Korean Numbers, p.10 |
| 여덟 | eight | numeral | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | yuh-duhl; native-Korean numeral; Numbers > Korean Numbers, p.10 |
| 아홉 | nine | numeral | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ah-hohp; native-Korean numeral; Numbers > Korean Numbers, p.10 |
| 열 | ten | numeral | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | yuhl; native-Korean numeral, also the base of the tens-series below; Numbers > Korean Numbers, p.10 |
| 스물 (스무) | twenty | numeral | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | s_-mool (s_-moo); native-Korean numeral, bound form 스무 before a classifier; Numbers > Korean Numbers, p.10 |
| 서른 | thirty | numeral | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | suh-r_n; native-Korean numeral; Numbers > Korean Numbers, p.10 |
| 마흔 | forty | numeral | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | mah-h_n; native-Korean numeral; Numbers > Korean Numbers, p.10 |
| 쉰 | fifty | numeral | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | shween; native-Korean numeral; Numbers > Korean Numbers, p.10 |
| 예순 | sixty | numeral | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | yeh-soon; native-Korean numeral; Numbers > Korean Numbers, p.10 |
| 일흔 | seventy | numeral | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | eel-h_n; native-Korean numeral; Numbers > Korean Numbers, p.10 |
| 여든 | eighty | numeral | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | yuh-d_n; native-Korean numeral; Numbers > Korean Numbers, p.10 |
| 아흔 | ninety | numeral | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ah-h_n; native-Korean numeral; Numbers > Korean Numbers, p.10 |
| 일 | one | numeral | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | eel; Sino-Korean (Chinese-origin) numeral; Numbers > Chinese-origin Numbers, p.11 |
| 이 | two | numeral | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ee; Sino-Korean numeral; Numbers > Chinese-origin Numbers, p.11 |
| 삼 | three | numeral | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | sahm; Sino-Korean numeral; Numbers > Chinese-origin Numbers, p.11 |
| 사 | four | numeral | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | sah; Sino-Korean numeral; Numbers > Chinese-origin Numbers, p.11 |
| 오 | five | numeral | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | oh; Sino-Korean numeral; Numbers > Chinese-origin Numbers, p.11 |
| 육 | six | numeral | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | yook; Sino-Korean numeral; Numbers > Chinese-origin Numbers, p.11 |
| 칠 | seven | numeral | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | cheel; Sino-Korean numeral; Numbers > Chinese-origin Numbers, p.11 |
| 팔 | eight | numeral | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | pahl; Sino-Korean numeral; Numbers > Chinese-origin Numbers, p.11 |
| 구 | nine | numeral | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | goo; Sino-Korean numeral; Numbers > Chinese-origin Numbers, p.11 |
| 십 | ten | numeral | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | sheep; Sino-Korean numeral; never preceded by 일 eel ("one") when it stands for exactly 10; Numbers > Chinese-origin Numbers, p.11/14 |
| 백 | hundred | numeral | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | behk; Sino-Korean place-value word; Numbers > Chinese-origin Numbers In Chart, p.16-17 |
| 천 | thousand | numeral | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | chuhn; Sino-Korean place-value word; Numbers > Chinese-origin Numbers In Chart, p.16-17 |
| 만 | ten thousand | numeral | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | mahn; Sino-Korean place-value word, base of Korean's 10,000-grouping system; dropped when a smaller 만-scale digit follows (see grammar point); Numbers > Chinese-origin Numbers In Chart, p.16-17 |
| 십만 | hundred thousand | numeral | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | sheep-mahn; Sino-Korean place-value word; Numbers > Chinese-origin Numbers In Chart, p.16-17 |
| 백만 | one million | numeral | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | behk-mahn; Sino-Korean place-value word; Numbers > Chinese-origin Numbers In Chart, p.16-17 |
| 천만 | ten million | numeral | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | chuhn-mahn; Sino-Korean place-value word; Numbers > Chinese-origin Numbers In Chart, p.16-17 |
| 억 | hundred million | numeral | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | uhk; Sino-Korean place-value word, the next grouping unit after 만; Numbers > Chinese-origin Numbers In Chart, p.16-17 |
| 점 | point (decimal) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | juhm; used to read the decimal point; Numbers > Reading Telephone Numbers, Decimals & Scores, p.15 |
| 대 | to; versus | particle | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | deh; used between two sides of a score; Numbers > Reading Telephone Numbers, Decimals & Scores, p.15 |
| 영; 공 | zero | numeral | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | yuhng; gohng — 영 yuhng used for decimal-left/score zero, 공 gohng used for decimal-right and telephone-number zero (see grammar point); Numbers > Reading Telephone Numbers, Decimals & Scores, p.15 |
| 몇 개예요? | How many is it? (generic) | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | myuht-geh-eh-yo?; Numbers & Classifiers > Expressions, p.22 |
| 몇 명이에요?; 몇 분이세요? | How many is it? (people; superiors) | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | myuhn-myuhng-ee-eh-yo?; myuht-boon-ee-seh-yo? (superiors); Numbers & Classifiers > Expressions, p.22 |
| 몇 마리예요? | How many is it? (animals) | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | myuhn-mah-ree-eh-yo?; Numbers & Classifiers > Expressions, p.22 |
| 몇 잔이에요? | How many is it? (drinks: glasses/cups) | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | myuht-jahn-ee-eh-yo?; Numbers & Classifiers > Expressions, p.22 |
| 몇 권이에요? | How many is it? (books/notebooks) | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | myuht-gwuhn-ee-eh-yo?; Numbers & Classifiers > Expressions, p.22 |
| 몇 자루예요? | How many is it? (pens/pencils) | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | myuht-jah-roo-eh-yo?; Numbers & Classifiers > Expressions, p.22 |
| 몇 장이에요? | How many is it? (paper) | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | myuht-jahng-ee-eh-yo?; Numbers & Classifiers > Expressions, p.22 |
| 몇 대예요? | How many is it? (machines, automobiles, etc.) | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | myuht-deh-eh-yo?; Numbers & Classifiers > Expressions, p.22 |
| 몇 시간이에요? | How many is it? (hours) | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | myuht-shee-gahn-ee-eh-yo?; Numbers & Classifiers > Expressions, p.23 |
| 몇 시예요? | What time is it? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | myuht-shee-eh-yo?; Numbers & Classifiers > Expressions, p.23 |
| 몇 호선이에요? | Which line is it? (subway lines) | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | myuht-hoh-suhn-ee-eh-yo?; Numbers & Classifiers > Expressions, p.23 |
| 개 | classifier: generic | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | geh; Numbers & Classifiers > classifier chart (generic classifier), p.23 |
| 살 / 세 | classifier: age (native # / Chinese-origin #) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | sahl / seh; Numbers & Classifiers > classifier chart, p.23 |
| 마리 | classifier: animal | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | mah-ree; Numbers & Classifiers > classifier chart, p.23 |
| 권 | classifier: books, notebooks | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gwuhn; Numbers & Classifiers > classifier chart, p.23 |
| 잔 | classifier: drinks in cup or glass | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | jahn; Numbers & Classifiers > classifier chart, p.23 |
| 층 | classifier: floors | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ch_ng; Numbers & Classifiers > classifier chart (Chinese-origin # only), p.23 |
| 송이 | classifier: flowers (# of stems) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | sohng-ee; Numbers & Classifiers > classifier chart, p.23 |
| 인분 | classifier: food (# of portions) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | een-boon; Numbers & Classifiers > classifier chart (Chinese-origin # only), p.23 |
| 공기 / 그릇 | classifier: food (# of bowls) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gohng-gee / g_-r_t; Numbers & Classifiers > classifier chart, p.24 |
| 접시 | classifier: food (# of plates) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | juhp-shee; Numbers & Classifiers > classifier chart, p.24 |
| 대 | classifier: machines (computer, telephone, cars, etc.) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | deh; Numbers & Classifiers > classifier chart, p.24 |
| 원 | classifier: money, Korean currency | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | wuhn; Numbers & Classifiers > classifier chart (Chinese-origin # only), p.24 |
| 달러 / 센트 | classifier: money, U.S. currency ($/¢) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | dahl-luh / sehn-t_; Numbers & Classifiers > classifier chart, p.24 |
| 장 | classifier: paper | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | jahng; Numbers & Classifiers > classifier chart, p.24 |
| 자루 | classifier: pen, pencil | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | jah-roo; Numbers & Classifiers > classifier chart, p.24 |
| 명 | classifier: people (of equal, younger, or generic status) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | myuhng; Numbers & Classifiers > classifier chart, p.24 |
| 분 | classifier: people (honorific) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | boon; Numbers & Classifiers > classifier chart, p.24 — register-marked classifier pair with 명 above |
| (no classifier) | telephone number | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | just the bare numbers; [eh] may be inserted between digit groups for a pause; Numbers & Classifiers > classifier chart, p.24 |
| 시간 | classifier: time, # of hours | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | shee-gahn; Numbers & Classifiers > classifier chart, p.24 |
| 시 | classifier: time, point of hour | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | shee; Numbers & Classifiers > classifier chart, p.24 |
| 분 | classifier: time, # of minutes & point of minute | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | boon; Numbers & Classifiers > classifier chart (Chinese-origin # only), p.24 — homograph of the honorific people-classifier 분 above, distinct sense |
| 초 | classifier: time, # of seconds & point of second | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | choh; Numbers & Classifiers > classifier chart (Chinese-origin # only), p.24 |
| 일 | classifier: time, # of days & date | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | eel; Numbers & Classifiers > classifier chart (Chinese-origin # only), p.25 |
| 달 / 개월 | classifier: time, # of months | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | dahl / geh-wuhl; Numbers & Classifiers > classifier chart, p.25 |
| 월 | classifier: time, point of month | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | wuhl (Chinese-origin # only; irregular: June=유월 yoo-wuhl not yook-wuhl, October=시월 shee-wuhl not sheep-wuhl); Numbers & Classifiers > classifier chart, p.25 |
| 년 | classifier: time, # of years & naming a year | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | nyuhn; Numbers & Classifiers > classifier chart (Chinese-origin # only), p.25 |
| 호선 | classifier: transportation, subway lines in Seoul | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | hoh-suhn; Numbers & Classifiers > classifier chart (Chinese-origin # only), p.25 |
| 번 | classifier: transportation, bus number | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | buhn; Numbers & Classifiers > classifier chart (Chinese-origin # only), p.25 |
| 몇 시예요? | What time is it? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | myuht-shee-eh-yo?; Time Matters > Expressions, p.29 |
| 오늘 며칠이에요? | What is today's date? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | oh-n_l myuh-cheel ee-eh-yo?; Time Matters > Expressions, p.29 |
| 오늘 무슨 요일이에요? | What day is it today? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | oh-n_l moo-s_n-yo-eel ee-eh-yo?; Time Matters > Expressions, p.29 |
| 몇 월이에요? | Which month is it? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | myuh-dwuhl ee-eh-yo?; Time Matters > Expressions, p.29 |
| 몇 개월이에요?; 몇 달이에요? | How many months is it? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | myuht-geh-wuhl ee-eh-yo?; myuht-dahl ee-eh-yo?; Time Matters > Expressions, p.29 |
| 몇 년이에요? | Which year is it?; How many years is it? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | myuhn-nyuh-nee-eh-yo?; Time Matters > Expressions, p.29 |
| 얼마나 걸려요? | How long does it take? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | uhl-mah-nah guhl-lyuh-yo?; Time Matters > Expressions, p.29 |
| 몇 (초/분/시간/주/달/년) 걸려요? | How many (seconds/minutes/hours/days/weeks/months/years) does it take? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | myuht ... guhl-lyuh-yo?; fill-in-the-blank frame listing choh/boon/shee-gahn/cheel/joo/dahl/nyuhn; Time Matters > Expressions, p.29 — note 며칠/"how many days" is spelled 며칠 not 몇일 (orthographic irregularity flagged by the book itself) |
| 시 | point of the hour | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | shee (native Korean #); Time Matters > Words > Hours·Minutes·Seconds, p.30 |
| 시간 | number of hours | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | shee-gahn (native Korean #); Time Matters > Words > Hours·Minutes·Seconds, p.30 |
| 분 | minutes | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | boon (Chinese-origin #); Time Matters > Words > Hours·Minutes·Seconds, p.30 |
| 반 | half past the hour | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | bahn; Time Matters > Words > Hours·Minutes·Seconds, p.30 |
| 초 | seconds | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | choh (Chinese-origin #); Time Matters > Words > Hours·Minutes·Seconds, p.30 |
| 아침 | morning | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ah-cheem; Time Matters > Words > Parts of the Day, p.30 |
| 오전 | a.m. | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | oh-juhn; Time Matters > Words > Parts of the Day, p.30 |
| 정오 | noon | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | juhng-oh; Time Matters > Words > Parts of the Day, p.30 |
| 오후 | p.m.; afternoon | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | oh-hoo; Time Matters > Words > Parts of the Day, p.30 |
| 저녁 | evening | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | juh-nyuhk; Time Matters > Words > Parts of the Day, p.30 |
| 밤 | night | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | bahm; Time Matters > Words > Parts of the Day, p.30 |
| 새벽 | dawn | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | seh-byuhk; Time Matters > Words > Parts of the Day, p.30 |
| 오전 아홉 시 반 | 9:30am | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | oh-juhn ah-hohp-shee bahn; Time Matters > Words > Reading Time: Examples, p.30 |
| 오후 한 시 십오 분 | 1:15pm | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | oh-hoo hahn-shee sheep oh-boon; Time Matters > Words > Reading Time: Examples, p.30 |
| 저녁 일곱 시 십오 분 | 7:15 in the evening | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | juh-nyuhk eel-gohp-shee sheep-oh-boon; Time Matters > Words > Reading Time: Examples, p.30 |
| 밤 열 시 사십오 분 | 10:45 at night | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | bahm yuhl-shee sah-sheep oh-boon; Time Matters > Words > Reading Time: Examples, p.31 |
| 새벽 두 시 | 2:00 at dawn | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | seh-byuhk doo-shee; Time Matters > Words > Reading Time: Examples, p.31 |
| 월요일 | Monday | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | wuh-ryo-eel (wuhl + yo-eel; short form 월 "wuhl"); Time Matters > Words > Days of the Week, p.31 |
| 화요일 | Tuesday | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | hwah-yo-eel (hwah + yo-eel; short form 화 "hwah"); Time Matters > Words > Days of the Week, p.31 |
| 수요일 | Wednesday | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | soo-yo-eel (soo + yo-eel; short form 수 "soo"); Time Matters > Words > Days of the Week, p.31 |
| 목요일 | Thursday | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | moh-gyo-eel (mohk + yo-eel; short form 목 "mohk"); Time Matters > Words > Days of the Week, p.31 |
| 금요일 | Friday | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | g_m-nyo-eel (g_m + yo-eel; short form 금 "g_m"); Time Matters > Words > Days of the Week, p.31 |
| 토요일 | Saturday | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | toh-yo-eel (toh + yo-eel; short form 토 "toh"); Time Matters > Words > Days of the Week, p.31 |
| 일요일 | Sunday | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ee-ryo-eel (eel + yo-eel; short form 일 "eel"); Time Matters > Words > Days of the Week, p.31 |
| 그제 | the day before yesterday | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | g_-jeh; Time Matters > Words > More Days, p.31 |
| 어제 | yesterday | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | uh-jeh; Time Matters > Words > More Days, p.31 |
| 오늘 | today | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | oh-n_l; Time Matters > Words > More Days, p.31 |
| 내일 | tomorrow | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | neh-eel; Time Matters > Words > More Days, p.31 |
| 모레 | the day after tomorrow | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | moh-reh; Time Matters > Words > More Days, p.31 |
| 일월 | January | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ee-rwuhl (eel + wuhl); Time Matters > Words > Months of the Year, p.32 |
| 이월 | February | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ee-wuhl (ee + wuhl); Time Matters > Words > Months of the Year, p.32 |
| 삼월 | March | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | sah-mwuhl (sahm + wuhl); Time Matters > Words > Months of the Year, p.32 |
| 사월 | April | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | sah-wuhl (sah + wuhl); Time Matters > Words > Months of the Year, p.32 |
| 오월 | May | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | oh-wuhl (oh + wuhl); Time Matters > Words > Months of the Year, p.32 |
| 유월 | June | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | yoo-wuhl (yook + wuhl, irregular — expected *yook-wuhl does not occur); Time Matters > Words > Months of the Year, p.32 |
| 칠월 | July | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | chee-rwuhl (cheel + wuhl); Time Matters > Words > Months of the Year, p.32 |
| 팔월 | August | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | pah-rwuhl (pahl + wuhl); Time Matters > Words > Months of the Year, p.32 |
| 구월 | September | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | goo-wuhl (goo + wuhl); Time Matters > Words > Months of the Year, p.32 |
| 시월 | October | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | shee-wuhl (sheep + wuhl, irregular — expected *sheep-wuhl does not occur); Time Matters > Words > Months of the Year, p.32 |
| 십일월 | November | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | shee-bee-rwuhl (sheep-eel + wuhl); Time Matters > Words > Months of the Year, p.32 |
| 십이월 | December | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | shee-bee-wuhl (sheep-ee + wuhl); Time Matters > Words > Months of the Year, p.32 |
| 천구백팔십오년 일월 오일 | January 5th, 1985 (worked date-reading example) | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | chuhn goo-behk pahl-sheep oh-nyuhn eel-wuhl (pronounced ee-rwuhl) oh-eel; Time Matters > Words > Reading a Date With a Year, p.32-33 |
| 잠깐; 잠시 | a short while | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | jahm-ggahn; jahm-shee; Time Matters > Words > Others, p.33 |
| 오래 | a long time | noun/adverb | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | oh-reh; Time Matters > Words > Others, p.33 |
| 아까 | some time ago | adverb | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ahk-gah; Time Matters > Words > Others, p.33 |
| 오래 전에 | a long time ago | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | oh-reh juh-neh; Time Matters > Words > Others, p.33 |
| 얼마 전에 | a while ago | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | uhl-mah juh-neh; Time Matters > Words > Others, p.33 |
| 얼마 후에 | after a while | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | uhl-mah hoo-eh; Time Matters > Words > Others, p.33 |
| 최근(에) | recently | adverb | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | chweh-g_n(-eh); Time Matters > Words > Others, p.33 |
| 옛날(에) | in old days | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | yehn-nahl(-eh); Time Matters > Words > Others, p.33 |
| 옛날 옛날에 | once upon a time | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | yehn-nahl yehn-nah-reh; Time Matters > Words > Others, p.33 |
| 미래 | future | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | mee-reh; Time Matters > Words > Others, p.33 |
| 현재 | present | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | hyuhn-jeh; Time Matters > Words > Others, p.33 |
| 과거 | past | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gwah-guh; Time Matters > Words > Others, p.33 |
| (a place) 어디 있어요? | Where is (a place)? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | (a place) uh-dee eet-suh-yo?; Places > Expressions, p.37 |
| 여기가 어디예요? | Where are we? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | yuh-gee-gah uh-dee-eh-yo?; Places > Expressions, p.37 |
| 저기가 뭐예요? | What is that place? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | juh-gee-gah muh-eh-yo?; Places > Expressions, p.37 |
| 공항 | airport | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gohng-hahng; Places > Words, p.37 |
| 놀이공원 | amusement park | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | noh-ree-gohng-wuhn; Places > Words, p.37 |
| 아파트 | apartment | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ah-pah-t_; Places > Words, p.37 |
| 은행 | bank | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | _n-hehng; Places > Words, p.37 |
| 이발소 | barber shop | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ee-bahl-soh; Places > Words, p.37 |
| 화장실; 목욕탕 | bathroom | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | hwah-jahng-sheel; moh-gyok-tahng; footnote: 목욕 moh-gyok alone means "bathing"; Places > Words, p.37 |
| 미장원; 미용실; 머리방 | beauty salon | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | mee-jahng-wuhn; mee-yong-sheel; muh-ree-bahng; Places > Words, p.37 |
| 방송국 | broadcasting company | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | bahng-sohng-gook; Places > Words, p.37 |
| 시청 | city hall | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | shee-chuhng; Places > Words, p.37 |
| 편의점 | convenient store | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | pyuh-nee-juhm; Places > Words, p.37 |
| 백화점 | department store | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | behk-kwah-juhm; Places > Words, p.37 |
| 약국 | drugstore | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | yahk-gook; Places > Words, p.38 |
| 초등학교 | elementary school | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | choh-d_ng-hahk-gyo; Places > Words, p.38 |
| 대사관 | embassy | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | deh-sah-gwahn; Places > Words, p.38 |
| 응급실 | emergency room | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | _ng-g_p-sheel; Places > Words, p.38 |
| 주유소 | gas station | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | joo-yoo-soh; Places > Words, p.38 |
| 온실 | greenhouse | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ohn-sheel; Places > Words, p.38 |
| 철물점 | hardware store | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | chuhl-mool-juhm; Places > Words, p.38 |
| 고등학교 | high school | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | goh-d_ng-hahk-gyo; Places > Words, p.38 |
| 집 | home | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | jeep; Places > Words, p.38 |
| 고향 | hometown | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | goh-hyahng; Places > Words, p.38 |
| 병원 | hospital | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | byuhng-wuhn; Places > Words, p.38 |
| 호텔 | hotel | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | hoh-tehl; Places > Words, p.38 |
| 집 | house | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | jeep; homograph with "home" above; Places > Words, p.38 |
| 안내(소) | information (booth) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ahn-neh(-soh); Places > Words, p.38 |
| 중학교 | junior high school | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | joong-hahk-gyo; Places > Words, p.38 |
| 매점 | kiosk | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | meh-juhm; Places > Words, p.38 |
| 도서관 | library | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | doh-suh-gwahn; Places > Words, p.38 |
| 잡지사 | magazine company | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | jahp-jee-sah; Places > Words, p.38 |
| 관리실 | management office | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gwahl-lee-sheel; Places > Words, p.38 |
| 시장 | market | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | shee-jahng; Places > Words, p.38 |
| 박물관 | museum | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | bahng-mool-gwahn; Places > Words, p.38 |
| 신문사 | newspaper company | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | sheen-moon-sah; Places > Words, p.38 |
| 양로원 | nursing home | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | yahng-noh-wuhn; Places > Words, p.38 |
| 사무실 | office | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | sah-moo-sheel; Places > Words, p.38 |
| 과수원 | orchard | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gwah-soo-wuhn; Places > Words, p.38 |
| 고아원 | orphanage | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | goh-ah-wuhn; Places > Words, p.38 |
| 공원 | park | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gohng-wuhn; Places > Words, p.38 |
| 주차장 | parking lot | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | joo-chah-jahng; Places > Words, p.39 |
| 약국 | pharmacy | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | yahk-gook; homograph with "drugstore" above; Places > Words, p.39 |
| 경찰서 | police station | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gyuhng-chahl-suh; Places > Words, p.39 |
| 우체국 | post office | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | oo-cheh-gook; Places > Words, p.39 |
| 학원 | private educational institution | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | hah-gwuhn; Places > Words, p.39 |
| 출판사 | publishing company | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | chool-pahn-sah; Places > Words, p.39 |
| 부동산 소개소 | real estate agency | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | boo-dohng-sahn-soh-geh-soh; Places > Words, p.39 |
| 휴게소 | rest area | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | hyoo-geh-soh; Places > Words, p.39 |
| 레스토랑 | restaurant | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | reh-s_-toh-rahng; Places > Words, p.39 |
| 화장실 | restroom | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | hwah-jahng-sheel; homograph with "bathroom" above; Places > Words, p.39 |
| 학교 | school | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | hahk-gyo; Places > Words, p.39 |
| 문구점 | stationery store | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | moon-goo-juhm; Places > Words, p.39 |
| 가게 | store | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gah-geh; Places > Words, p.39 |
| 지하철역 | subway station | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | jee-hah-chuhl-yuhk; Places > Words, p.39 |
| 수퍼(마켓); 마트 | supermarket | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | soo-puh(-mah-keht); mah-t_; Places > Words, p.39 |
| 극장 | theater | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | g_k-jahng; Places > Words, p.39 |
| 관광지 | tourist attraction | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gwahn-gwahng-jee; Places > Words, p.39 |
| 여행사 | travel agency | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | yuh-hehng-sah; Places > Words, p.39 |
| 기차역 | train station | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gee-chah-yuhk; Places > Words, p.39 |
| 대학교 | university | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | deh-hahk-gyo; footnote: for more school terms, see the "Education & Schools" chapter; Places > Words, p.39 |
| 직장 | work place | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | jeek-jahng; Places > Words, p.39 |
| 동물원 | zoo | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | dohng-moo-rwuhn; Places > Words, p.39 |
| 어디 사세요? | Where do you live? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | uh-dee sah-seh-yo?; In & Out of a House > Expressions, p.43 |
| 여기서 멀어요? | Is it far from here? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | yuh-gee-suh muh-ruh-yo?; In & Out of a House > Expressions, p.43 |
| 여기서 가까워요? | Is it close from here? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | yuh-gee-suh gahk-gah-wuh-yo?; In & Out of a House > Expressions, p.43 |
| (건물종류)입니까? | Is it (type of building)? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | (type of building)eem-neek-gah?; In & Out of a House > Expressions, p.43 |
| 방이 몇 개예요? | How many bedrooms are there? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | bahng-ee myuht-geh-eh-yo?; In & Out of a House > Expressions, p.43 |
| 다락 | attic | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | dah-rahk; In & Out of a House > Makeup Of a House, p.43 |
| 지하(실) | basement (room) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | jee-hah(-sheel); In & Out of a House > Makeup Of a House, p.43 |
| 목욕탕 | bathroom | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | moh-gyok-tahng; In & Out of a House > Makeup Of a House, p.43 |
| 세면대 | sink | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | seh-myuhn-deh; In & Out of a House > Makeup Of a House, p.43 |
| 변기 | toilet | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | byuhn-gee; In & Out of a House > Makeup Of a House, p.43 |
| 욕조 | tub | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | yok-joh; In & Out of a House > Makeup Of a House, p.43 |
| 침실 | bedroom | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | cheem-sheel; In & Out of a House > Makeup Of a House, p.43 |
| 천장 | ceiling | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | chuhn-jahng; In & Out of a House > Makeup Of a House, p.43 |
| 굴뚝 | chimney | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gool-ddook; In & Out of a House > Makeup Of a House, p.43 |
| 문 | door | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | moon; In & Out of a House > Makeup Of a House, p.43 |
| 초인종 | doorbell | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | choh-een-johng; In & Out of a House > Makeup Of a House, p.43 |
| 전기 | electricity | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | juhn-gee; In & Out of a House > Makeup Of a House, p.43 |
| 전기세 | electricity bill | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | juhn-geet-seh; In & Out of a House > Makeup Of a House, p.44 |
| 수도꼭지 | faucet | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | soo-dohk-gohk-jee; In & Out of a House > Makeup Of a House, p.44 |
| 담 | fence (wall-like) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | dahm; In & Out of a House > Makeup Of a House, p.44 |
| 벽난로 | fireplace | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | byuhng-nahl-loh; In & Out of a House > Makeup Of a House, p.44 |
| 현관 | foyer | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | hyuhn-gwahn; In & Out of a House > Makeup Of a House, p.44 |
| 차고 | garage | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | chah-goh; In & Out of a House > Makeup Of a House, p.44 |
| 정원 | garden | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | juhng-wuhn; In & Out of a House > Makeup Of a House, p.44 |
| 대문 | gate | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | deh-moon; In & Out of a House > Makeup Of a House, p.44 |
| 부엌 | kitchen | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | boo-uhk; In & Out of a House > Makeup Of a House, p.44 |
| 거실; 마루 | living room | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | guh-sheel; mah-roo; In & Out of a House > Makeup Of a House, p.44 |
| 우편함 | mailbox | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | oo-pyuhn-hahm; In & Out of a House > Makeup Of a House, p.44 |
| 안방 | master bedroom | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ahn-bbahng; In & Out of a House > Makeup Of a House, p.44 |
| 다용도실 | 'multipurpose room' | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | dah-yong-doh-sheel; In & Out of a House > Makeup Of a House, p.44 |
| 화초 | plants | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | hwah-choh; In & Out of a House > Makeup Of a House, p.44 |
| 연못 | pond | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | yuhn-moht; In & Out of a House > Makeup Of a House, p.44 |
| 화장실 | powder room | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | hwah-jahng-sheel; In & Out of a House > Makeup Of a House, p.44 (same term also glossed "restroom") |
| 화장실 | restroom | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | hwah-jahng-sheel; In & Out of a House > Makeup Of a House, p.44 (duplicate headword, listed separately by the book under two English glosses) |
| 지붕 | roof | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | jee-boong; In & Out of a House > Makeup Of a House, p.44 |
| 옥상 | rooftop | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ohk-sahng; In & Out of a House > Makeup Of a House, p.44 |
| 방 | room | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | bahng; In & Out of a House > Makeup Of a House, p.44 |
| 하수 | sewage | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | hah-soo; In & Out of a House > Makeup Of a House, p.44 |
| 서재 | study | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | suh-jeh; In & Out of a House > Makeup Of a House, p.44 |
| 베란다 | veranda | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | beh-rahn-dah; In & Out of a House > Makeup Of a House, p.44 |
| 벽지 | wallpaper | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | byuhk-jee; In & Out of a House > Makeup Of a House, p.44 |
| 벽 | walls (inside the house) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | byuhk; In & Out of a House > Makeup Of a House, p.44 |
| 수도 | water (system) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | soo-doh; In & Out of a House > Makeup Of a House, p.44 |
| 수도세 | water bill | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | soo-doht-seh; In & Out of a House > Makeup Of a House, p.44 |
| 창(문) | window | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | chahng(-moon); In & Out of a House > Makeup Of a House, p.44 |
| 마당 | yard | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | mah-dahng; In & Out of a House > Makeup Of a House, p.44 |
| 장롱 | armoire | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | jahng-nohng; In & Out of a House > Furniture & Beyond, p.45 |
| 침대 | bed | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | cheem-deh; In & Out of a House > Furniture & Beyond, p.45 |
| 이불; 담요 | blanket | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ee-bool (Korean-style quilt); dahm-nyo (thin wool/fur blanket); In & Out of a House > Furniture & Beyond, p.45, footnote 1 |
| 책장 | bookcase | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | chehk-jahng; In & Out of a House > Furniture & Beyond, p.45 |
| 의자 | chair | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | _ee-jah — underscore is this book's own romanization symbol for the vowel ㅡ, not a transcription gap; In & Out of a House > Furniture & Beyond, p.45 |
| 서랍장 | chest | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | suh-rahp-jahng; In & Out of a House > Furniture & Beyond, p.45 |
| 장(롱) | closet | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | jahng-(nohng); In & Out of a House > Furniture & Beyond, p.45 |
| 탁자 | coffee table | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | tahk-jah; In & Out of a House > Furniture & Beyond, p.45 |
| 책상 | desk | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | chehk-sahng; In & Out of a House > Furniture & Beyond, p.45 |
| 식탁; 상 | dining table | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | sheek-tahk; sahng; In & Out of a House > Furniture & Beyond, p.45 |
| 경대 | dresser | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gyuhng-deh; furniture for storing cosmetics, usually with attached mirror; In & Out of a House > Furniture & Beyond, p.45, footnote 2 |
| 액자 | frame | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ehk-jah; In & Out of a House > Furniture & Beyond, p.45 |
| 램프 | lamp | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | lehm-p_; In & Out of a House > Furniture & Beyond, p.45 |
| (전)등 | light | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | (juhn-)d_ng; In & Out of a House > Furniture & Beyond, p.45 |
| 요; 매트리스 | mattress | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | yo (Korean-style cotton mattress, folded away by day); meh-t_-ree-s_ (Western-style bed mattress); In & Out of a House > Furniture & Beyond, p.45, footnote 3 |
| 거울 | mirror | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | guh-ool; In & Out of a House > Furniture & Beyond, p.45 |
| 그림 | painting | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | g_-reem — underscore is this book's own romanization symbol for the vowel ㅡ, not a transcription gap; In & Out of a House > Furniture & Beyond, p.45 |
| 사진 액자 | photo frame | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | sah-jeen ehk-jah; In & Out of a House > Furniture & Beyond, p.45 |
| 베개 | pillow | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | beh-geh; In & Out of a House > Furniture & Beyond, p.45 |
| 신발장 | shoes storage | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | sheen-bahl-jahng; In & Out of a House > Furniture & Beyond, p.45 |
| 소파 | sofa | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | soh-pah; In & Out of a House > Furniture & Beyond, p.45 |
| 휴지통 | waste basket | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | hyoo-jee-tohng; In & Out of a House > Furniture & Beyond, p.45 |
| 에어컨 | air conditioner | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | eh-uh-kuhn; In & Out of a House > Household Appliances, p.46 |
| 알람시계 | alarm clock | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ahl-lahm-shee-geh; In & Out of a House > Household Appliances, p.46 |
| 전구 | bulb | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | juhn-goo; In & Out of a House > Household Appliances, p.46 |
| 시계 | clock | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | shee-geh; In & Out of a House > Household Appliances, p.46 |
| 컴퓨터 | computer | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | kuhm-pyoo-tuh; In & Out of a House > Household Appliances, p.46 |
| 식기 세척기 | dishwasher | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | sheek-gee seh-chuhk-gee; In & Out of a House > Household Appliances, p.46 |
| 건조기 | dryer | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | guhn-joh-gee; In & Out of a House > Household Appliances, p.46 |
| 선풍기 | fan | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | suhn-poong-gee; In & Out of a House > Household Appliances, p.46 |
| 냉동고 | freezer | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | nehng-dohng-goh; In & Out of a House > Household Appliances, p.46 |
| 가습기 | humidifier | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gah-s_p-gee; In & Out of a House > Household Appliances, p.46 |
| 다리미 | iron | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | dah-ree-mee; In & Out of a House > Household Appliances, p.46 |
| 전자레인지 | microwave | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | juhn-jah-reh-een-jee; In & Out of a House > Household Appliances, p.46 |
| 오븐 | oven | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | oh-b_n; In & Out of a House > Household Appliances, p.46 |
| 냉장고 | refrigerator | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | nehng-jahng-goh; In & Out of a House > Household Appliances, p.46 |
| 전기밥솥 | rice cooker | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | juhn-gee-bahp-soht; In & Out of a House > Household Appliances, p.46 |
| 재봉틀 | sewing machine | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | jeh-bohng-t_l; In & Out of a House > Household Appliances, p.46 |
| 스테레오 | stereo | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | s_-teh-reh-oh; In & Out of a House > Household Appliances, p.46 |
| 레인지 | stove | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | reh-een-jee; In & Out of a House > Household Appliances, p.46 |
| 전화 | telephone | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | juhn-hwah; In & Out of a House > Household Appliances, p.46 |
| 텔레비전; 티비 | television | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | tehl-leh-bee-juhn; tee-bee; In & Out of a House > Household Appliances, p.46 |
| 비디오 | video | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | bee-dee-oh; In & Out of a House > Household Appliances, p.46 |
| 세탁기 | washer (laundry) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | seh-tahk-gee; In & Out of a House > Household Appliances, p.46 |
| 주소 | address | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | joo-soh; In & Out of a House > Around The Neighborhood, p.47 |
| 골목 | alley | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gohl-mohk; In & Out of a House > Around The Neighborhood, p.47 |
| 아파트 | apartment | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ah-pah-t_; In & Out of a House > Around The Neighborhood, p.47 |
| 아파트 단지 | apartment complex | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ah-pah-t_ dahn-jee; In & Out of a House > Around The Neighborhood, p.47 |
| 경비원 | doorman | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gyuhng-bee-wuhn; In & Out of a House > Around The Neighborhood > apartment complex, p.47 |
| 상가 | shopping mall | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | sahng-gah; In & Out of a House > Around The Neighborhood > apartment complex, p.47 |
| 제과점; 빵집 | bakery | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | jeh-gwah-juhm; bbahng-jeep; In & Out of a House > Around The Neighborhood, p.47 |
| 은행 | bank | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | _n-hehng — underscore is this book's own romanization symbol for the vowel ㅡ, not a transcription gap; In & Out of a House > Around The Neighborhood, p.47 |
| 편의점 | convenient store | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | pyuhn-_ee-juhm — underscore is this book's own romanization symbol for the vowel ㅡ, not a transcription gap; In & Out of a House > Around The Neighborhood, p.47 |
| 약국 | drug store | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | yahk-gook; In & Out of a House > Around The Neighborhood, p.47 (same headword later re-listed as "pharmacy") |
| 꽃가게; 꽃집 | flower shop | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ggoht-gah-geh; ggoht-jeep; In & Out of a House > Around The Neighborhood, p.47 |
| 병원 | hospital | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | byuhng-wuhn; In & Out of a House > Around The Neighborhood, p.47 |
| 단독주택 | house (as opposed to apartment) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | dahn-dohk-joo-tehk; In & Out of a House > Around The Neighborhood, p.47 |
| 시장 | market | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | shee-jahng; In & Out of a House > Around The Neighborhood, p.47 |
| 동네 | neighborhood | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | dohng-neh; In & Out of a House > Around The Neighborhood, p.47 |
| 공원 | park | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gohng-wuhn; In & Out of a House > Around The Neighborhood, p.47 |
| 약국 | pharmacy | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | yahk-gook; In & Out of a House > Around The Neighborhood, p.47 (duplicate headword, see "drug store" above) |
| 놀이터 | playground | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | noh-ree-tuh; In & Out of a House > Around The Neighborhood, p.47 |
| 경찰서 | police station | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gyuhng-chahl-suh; In & Out of a House > Around The Neighborhood, p.47 |
| 우체통 | postbox | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | oo-cheh-tohng; In & Out of a House > Around The Neighborhood, p.47 |
| 우체국 | post office | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | oo-cheh-gook; In & Out of a House > Around The Neighborhood, p.47 |
| 부동산 소개소 | real estate agency | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | boo-dohng-sahn soh-geh-soh; In & Out of a House > Around The Neighborhood, p.47 |
| 학군 | school district | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | hahk-goon; In & Out of a House > Around The Neighborhood, p.47 |
| 가게 | store | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gah-geh; In & Out of a House > Around The Neighborhood, p.48 |
| 길; 거리 | street | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | geel; guh-ree; In & Out of a House > Around The Neighborhood, p.48 |
| 가로등 | street light | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gah-roh-d_ng — underscore is this book's own romanization symbol for the vowel ㅡ, not a transcription gap (same underscore convention seen throughout); In & Out of a House > Around The Neighborhood, p.48 |
| 지하철역 | subway station | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | jee-hah-chuhl-yuhk; In & Out of a House > Around The Neighborhood, p.48 |
| 수퍼마켓; 마트 | supermarket | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | soo-puh-mah-keht; mah-t_; In & Out of a House > Around The Neighborhood, p.48 |
| 오세요. | Come. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | oh-seh-yo.; Directions > Expressions, p.51 |
| 길을 건너세요. | Cross the street. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gee-r_l guhn-nuh-seh-yo.; Directions > Expressions, p.51 |
| 가세요. | Go. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gah-seh-yo.; Directions > Expressions, p.51 |
| 똑바로 가세요; 쭉 가세요. | Go straight. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ddohk-bah-roh gah-seh-yo; jjook gah-seh-yo.; Directions > Expressions, p.51 |
| 올라가세요. | Go up. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ohl-lah-gah-seh-yo.; Directions > Expressions, p.51 |
| 내려가세요. | Go down. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | neh-ryuh-gah-seh-yo.; Directions > Expressions, p.51 |
| 도세요. | Turn. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | doh-seh-yo.; Directions > Expressions, p.51 |
| 왼쪽으로 도세요; 좌회전 하세요. | Turn left. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | wehn-jjoh-g_-roh doh-seh-yo; jwah-hweh-juhn hah-seh-yo.; Directions > Expressions, p.51 |
| 오른쪽으로 도세요; 우회전 하세요. | Turn right. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | oh-r_n-jjoh-g_-roh doh-seh-yo; oo-hweh-juhn hah-seh-yo.; Directions > Expressions, p.51 |
| 건너(편) | across | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | guhn-nuh(-pyuhn); Directions > Words, p.51 |
| 길건너(편) | across the street | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | geel-guhn-nuh(-pyuhn); Directions > Words, p.51 |
| 골목 | alley | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gohl-mohk; Directions > Words, p.51 (duplicate headword, also listed under Around The Neighborhood, p.47) |
| 아래; 밑 | bottom; below | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ah-reh; meet; Directions > Words, p.51 |
| 막다른길 | dead-end street | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | mahk-dah-r_n-geel; Directions > Words, p.51 |
| 방향 | directions | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | bahng-hyahng; the 4 directions are conventionally named in fixed order E-W-S-N (동서남북 dohng-suh-nahm-book); Directions > Words, p.52, footnote 1 |
| 동(쪽) | east | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | dohng(-jjohk); Directions > Words > directions, p.52 |
| 서(쪽) | west | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | suh(-jjohk); Directions > Words > directions, p.52 |
| 남(쪽) | south | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | nahm(-jjohk); Directions > Words > directions, p.52 |
| 북(쪽) | north | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | book(-jjohk); Directions > Words > directions, p.52 |
| 여기 | here | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | yuh-gee; Directions > Words, p.52 |
| 사거리 | intersection | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | sah-guh-ree; Directions > Words, p.52 |
| 왼쪽 | left side | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | wehn-jjohk; Directions > Words, p.52 |
| 좌회전 | left turn | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | jwah-hweh-juhn; Directions > Words, p.52 |
| 일방통행 | one-way traffic | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | eel-bahng-tohng-hehng; Directions > Words, p.52 |
| 고가도로 | overpass | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | goh-gah-doh-roh; Directions > Words, p.52 |
| 저기 | over there | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | juh-gee; "a place or area distant from both the speaker and the listener" (book's own footnote); Directions > Words, p.52, footnote 2 |
| 오른쪽 | right side | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | oh-r_n-jjohk; Directions > Words, p.52 |
| 우회전 | right turn | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | oo-hweh-juhn; Directions > Words, p.52 |
| 옆 | side; next to | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | yuhp; Directions > Words, p.52 |
| 계단; 층계 | stairs | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | geh-dahn; ch_ng-geh; Directions > Words, p.52 |
| 똑바로; 쪽 | straight | adverb | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ddohk-bah-roh; jjook; Directions > Words, p.52 |
| 길; 거리 | street | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | geel; guh-ree; Directions > Words, p.52 (duplicate headword, also listed under Around The Neighborhood, p.48) |
| 그쪽 | that side (listener's side) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | g_-jjohk; "the side of the listener" (book's own footnote); Directions > Words, p.52, footnote 3 |
| 저쪽 | that side (distant from both) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | juh-jjohk; "the side distant from both the speaker and the listener" (book's own footnote); Directions > Words, p.52, footnote 4 |
| 거기 | there | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | guh-gee; "a place or area near the listener" (book's own footnote); Directions > Words, p.52, footnote 5 |
| 위 | top; above | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | wee; Directions > Words, p.52 |
| 신호등 | traffic lights | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | sheen-hoh-d_ng; Directions > Words, p.52 |
| 지하도 | underpass | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | jee-hah-doh; Directions > Words, p.52 |
| 몇 번 버스 타야 돼요? | Which bus should I take? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | myuht-buhn-buh-s_ tah-yah-deh-yo?; Transportation & Traffic > Expressions > Using Public Transportation, p.55 |
| 지하철 몇 호선 타야 돼요? | Which subway line should I take? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | jee-hah-chuhl myuht-toh-suhn tah-yah-deh-yo?; Transportation & Traffic > Expressions, p.55 |
| (목적지)에 가고 싶은데요. | (It's that) I want to go to (destination). | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | (destination)eh gah-goh-shee-p_n-deh-yo.; Transportation & Traffic > Expressions, p.55 |
| (목적지) 어떻게 갑니까? | How do I get to (destination)? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | (destination) uht-duhk-keh gahm-neek-gah?; Transportation & Traffic > Expressions, p.55 |
| 이거 (목적지) 갑니까? | Does this go to (destination)? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ee-guh (destination) gahm-neek-gah?; Transportation & Traffic > Expressions, p.55 |
| 다음에서 내리면 됩니까? | Should I get off at the next stop? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | dah-_m-eh-suh neh-ree-myuhn dwehm-neek-gah?; Transportation & Traffic > Expressions, p.55 |
| 어디에서 내리면 됩니까? | Where should I get off at? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | uh-dee-eh-suh neh-ree-myuhn dwehm-neek-gah?; Transportation & Traffic > Expressions, p.55 |
| 어디에서 갈아타면 됩니까? | Where should I transfer at? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | uh-dee-eh-suh gah-rah-tah-myuhn dwehm-neek-gah?; Transportation & Traffic > Expressions, p.55 |
| 뭐로 갈아타면 됩니까? | What should I transfer to? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | mwuh-roh gah-rah-tah-myuhn dwehm-neek-gah?; Transportation & Traffic > Expressions, p.55 |
| (목적지)요. | (destination), please. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | (destination)yo.; Transportation & Traffic > Expressions > Taking a Taxi, p.56 |
| (목적지) 가 주세요. | Please go to (destination). | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | (destination) gah joo-seh-yo.; Transportation & Traffic > Expressions > Taking a Taxi, p.56 |
| 여기가 어디예요? | Where are we? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | yuh-gee-gah uh-dee-eh-yo?; Transportation & Traffic > Expressions > Taking a Taxi, p.56 |
| 여기 세워 주세요. | Please stop here. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | yuh-gee seh-wuh-joo-seh-yo.; Transportation & Traffic > Expressions > Taking a Taxi, p.56 |
| 저기 (랜드마크) 앞에서 세워 주세요. | Please stop in front of the (landmark) over there. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | juh-gee (landmark) ahp-peh-suh seh-wuh-joo-seh-yo.; Transportation & Traffic > Expressions > Taking a Taxi, p.56 |
| 얼마 나왔습니까? | How much did it come out to be? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | uhl-mah nah-waht-s_m-neek-gah?; Transportation & Traffic > Expressions > Taking a Taxi, p.56 |
| 고맙습니다. | Thank you. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | goh-mahp-s_m-nee-dah.; Transportation & Traffic > Expressions > Taking a Taxi, p.56 |
| 길이 많이 막히네요. | The road is very congested. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gee-ree mah-nee mah-kee-neh-yo.; Transportation & Traffic > Expressions > Others, p.56 |
| 길이 많이 미끄럽네요. | The road is very slippery. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gee-ree mah-nee meek-g_-ruhm-neh-yo.; Transportation & Traffic > Expressions > Others, p.56 |
| 조금 천천히 가 주세요. | Please go a little slowly. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | joh-g_m chuhn-chuh-nee gah-joo-seh-yo.; Transportation & Traffic > Expressions > Others, p.56 |
| 비행기 | airplane | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | bee-hehng-gee; Transportation & Traffic > Means of Transportation & Related Words, p.56 |
| 공항 | airport | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gohng-hahng; Transportation & Traffic > Means of Transportation & Related Words > airplane, p.56 |
| 국내선 | domestic flight | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | goong-neh-suhn; Transportation & Traffic > Means of Transportation & Related Words > airplane, p.56 |
| 국제선 | int'l flight | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gook-jeh-suhn; Transportation & Traffic > Means of Transportation & Related Words > airplane, p.56 |
| 자전거 | bicycle | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | jah-juhn-guh; Transportation & Traffic > Means of Transportation & Related Words, p.57 |
| 버스 | bus | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | buh-s_; Transportation & Traffic > Means of Transportation & Related Words, p.57 |
| 버스 정류장; 버스 정거장 | bus station | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | buh-s_-juhng-nyoo-jahng; buh-s_-juhng-guh-jahng; Transportation & Traffic > Means of Transportation & Related Words > bus, p.57 |
| 고속버스 | express bus | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | goh-sohk-buh-s_; Transportation & Traffic > Means of Transportation & Related Words > bus, p.57 |
| 고속버스 터미널 | express bus terminal | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | goh-sohk-buh-s_ tuh-mee-nuhl; Transportation & Traffic > Means of Transportation & Related Words > bus, p.57 |
| 시내버스 | local bus | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | shee-neh-buh-s_; Transportation & Traffic > Means of Transportation & Related Words > bus, p.57 |
| 시외버스 | Out-of-City bus | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | shee-weh-buh-s_; Transportation & Traffic > Means of Transportation & Related Words > bus, p.57 |
| 일반버스 | regular bus | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | eel-bahn-buh-s_; Transportation & Traffic > Means of Transportation & Related Words > bus, p.57 |
| 좌석버스 | Seated Bus | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | jwah-suhk-buh-s_; passenger count may not exceed seat count (book's own footnote); Transportation & Traffic > Means of Transportation & Related Words > bus, p.57, footnote 1 |
| 오토바이 | motorcycle | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | oh-toh-bah-ee; Transportation & Traffic > Means of Transportation & Related Words, p.57 |
| 지하철; 전철 | subway | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | jee-hah-chuhl; juhn-chuhl; Transportation & Traffic > Means of Transportation & Related Words, p.57 |
| 출구 | exit | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | chool-goo; Transportation & Traffic > Means of Transportation & Related Words > subway, p.57 |
| 출입구 | exit & entrance | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | choo-reep-goo; Transportation & Traffic > Means of Transportation & Related Words > subway, p.57 |
| (한자어 수) 호선 | subway lines in Korea: classifier | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | (Chinese-origin #) hoh-suhn; subway-line classifier uses Sino-Korean numerals; Transportation & Traffic > Means of Transportation & Related Words > subway, p.57 |
| 지하철역 | subway station | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | jee-hah-chuhl-yuhk; Transportation & Traffic > Means of Transportation & Related Words > subway, p.57 (duplicate headword, also p.48 Around The Neighborhood) |
| 갈아타는곳 | transferring point | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gah-rah-tah-n_n-goht; Transportation & Traffic > Means of Transportation & Related Words > subway, p.57 |
| 택시 | taxi | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | tehk-shee; Transportation & Traffic > Means of Transportation & Related Words, p.57 |
| 중형택시 | Midsize Taxi | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | joong-hyuhg-tehk-shee; Transportation & Traffic > Means of Transportation & Related Words > taxi, p.57 |
| 모범택시 | Exemplary Taxi | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | moh-buhm-tehk-shee; more expensive, better service/quality than regular taxi (book's own footnote); Transportation & Traffic > Means of Transportation & Related Words > taxi, p.57, footnote 2 |
| 기차 | train | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gee-chah; Transportation & Traffic > Means of Transportation & Related Words, p.58 |
| 기차역 | train station | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gee-chah-yuhk; Transportation & Traffic > Means of Transportation & Related Words > train, p.58 |
| 다리; 대교 | bridge | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | dah-ree; deh-gyo; 대교 (lit. "big"+"bridge") is used specifically in major-bridge proper names, e.g. 한강대교 "Han River Bridge" (book's own footnote); Transportation & Traffic > Words > Others, p.58, footnote 1 |
| 자동차; 차 | cars | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | jah-dohng-chah; chah; Transportation & Traffic > Words > Others, p.58 |
| 횡단보도 | crosswalk | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | hwehng-dahn-boh-doh; Transportation & Traffic > Words > Others, p.58 |
| 운전 | driving | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | oon-juhn; Transportation & Traffic > Words > Others, p.58 |
| 고속도로 | highway | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | goh-sohk-doh-roh; Transportation & Traffic > Words > Others, p.58 |
| 사거리 | intersection | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | sah-guh-ree; Transportation & Traffic > Words > Others, p.58 (duplicate headword, also p.52 Directions) |
| 일방통행 | one-way traffic | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | eel-bahng-tohng-hehng; Transportation & Traffic > Words > Others, p.58 (duplicate headword, also p.52 Directions) |
| 고가도로 | overpass | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | goh-gah-doh-roh; Transportation & Traffic > Words > Others, p.58 (duplicate headword, also p.52 Directions) |
| 주차 | parking | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | joo-chah; Transportation & Traffic > Words > Others, p.58 |
| 주차장 | parking lot | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | joo-chah-jahng; Transportation & Traffic > Words > Others, p.58 |
| 속도제한 | speed limit | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | sohk-doh-jeh-hahn; Transportation & Traffic > Words > Others, p.58 |
| 도로 표지판 | street signs | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | doh-roh pyo-jee-pahn; Transportation & Traffic > Words > Others, p.58 |
| 표 | ticket | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | pyo; Transportation & Traffic > Words > Others, p.58 |
| 토큰 | token | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | toh-k_n; Transportation & Traffic > Words > Others, p.58 |
| 신호등 | traffic lights | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | sheen-hoh-d_ng; Transportation & Traffic > Words > Others, p.58 (duplicate headword, also p.52 Directions) |
| 교통 | transportation | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gyo-tohng; Transportation & Traffic > Words > Others, p.58 |
| 터널 | tunnel | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | tuh-nuhl; Transportation & Traffic > Words > Others, p.58 |
| 지하도 | underpass | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | jee-hah-doh; Transportation & Traffic > Words > Others, p.58 (duplicate headword, also p.52 Directions) |
| (destination)에 가고 싶은데요 | (It's that) I want to go to (destination) | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *(destination)eh gah-goh-shee-p_n-deh-yo*; At The Airport > Expressions, p.61 |
| 환율이 어떻게 됩니까? | What is the exchange rate? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *hwahn-nyoo-ree uht-duhk-keh dwehm-neek-gah?*; At The Airport > Expressions, p.61 |
| 해외 | abroad | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *heh-weh*; At The Airport > Words, p.61 |
| 주소 | address | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *joo-soh*; At The Airport > Words, p.61 |
| 한국 주소 | address in Korea | noun phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *hahn-gook joo-soh*; At The Airport > Words, p.61 |
| 미국 주소 | address in the U.S. | noun phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *mee-gook joo-soh*; At The Airport > Words, p.61 |
| 항공(사) | airline | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *hahng-gohng(-sah)*; At The Airport > Words, p.61 |
| 공항 | airport | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *gohng-hahng*; At The Airport > Words, p.61 |
| 공항 버스 | Airport Bus | noun phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *gohng-hahng buh-s_*; At The Airport > Words, p.61 |
| 가방 | bag; luggage | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *gah-bahng*; At The Airport > Words, p.61 |
| 은행 | bank | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *_n-hehng*; At The Airport > Words, p.61 |
| 버스 | bus | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *buh-s_*; At The Airport > Words, p.61 |
| 비즈니스 | business | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *bee-jee-nee-s_*; loanword; At The Airport > Words, p.61 |
| 출장 | business trip | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *chool-jjahng*; At The Airport > Words, p.61 |
| 기장 | captain (of the plane) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *gee-jahng*; At The Airport > Words, p.61 |
| 세관 | customs | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *seh-gwahn*; At The Airport > Words, p.61 |
| 세관 조사 | customs inspection | noun phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *seh-gwahn-joh-sah*; At The Airport > Words, p.61 |
| 출국 | departure from a country | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *chool-gook*; At The Airport > Words, p.61 |
| 국내 | domestic | adjective/noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *goong-neh*; At The Airport > Words, p.62 |
| 국내선 | domestic flight | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *goong-neh-suhn*; At The Airport > Words, p.62 |
| 국내 여행 | domestic travel | noun phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *goong-neh-yuh-hehng*; At The Airport > Words, p.62 |
| 입국 | entry into a country | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *eep-gook*; At The Airport > Words, p.62 |
| 환율 | exchange rate | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *hwahn-nyool*; At The Airport > Words, p.62 |
| 승무원 | flight attendants | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *s_ng-moo-wuhn*; At The Airport > Words, p.62 |
| 비행기표 | flight tickets | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *bee-hehng-gee-pyo*; At The Airport > Words, p.62 |
| 외국 | foreign country | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *weh-gook*; At The Airport > Words, p.62 |
| 외국인 | foreigner | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *weh-goo-geen*; At The Airport > Words, p.62 |
| 게이트; 출구 | gates; exits | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *geh-ee-t_; chool-goo*; At The Airport > Words, p.62 |
| 안내(소) | information booth | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *ahn-neh(-soh)*; At The Airport > Words, p.62 |
| 국제 공항 | international airport | noun phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *gook-jeh gohng-hahng*; At The Airport > Words, p.62 |
| 국제선 | international flight | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *gook-jeh-suhn*; At The Airport > Words, p.62 |
| 숙소 | lodging | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *sook-soh*; At The Airport > Words, p.62 |
| 짐; 가방 | luggage | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *jeem; gah-bahng*; At The Airport > Words, p.62 |
| 여권 | passport | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *yuhk-gwuhn*; At The Airport > Words, p.62 |
| 내국인 | people of the nation | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *neh-goo-geen*; At The Airport > Words, p.62 |
| 지하철 | subway | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *jee-hah-chuhl*; At The Airport > Words, p.62 |
| 택시 | taxi | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *tehk-shee*; loanword; At The Airport > Words, p.62 |
| 교통 | transportation | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *gyo-tohng*; At The Airport > Words, p.62 |
| 여행 | travel | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *yuh-hehng*; At The Airport > Words, p.62 |
| 해외 여행 | travel abroad | noun phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *heh-weh-yuh-hehng*; At The Airport > Words, p.62 |
| 여행 가방 | travel luggage | noun phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *yuh-hehng-gah-bahng*; At The Airport > Words, p.62 |
| 여행 | trip | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *yuh-hehng*; At The Airport > Words, p.62 (same term as "travel") |
| 비자 | visa | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *bee-jah*; loanword; At The Airport > Words, p.62 |
| 방문 | visit | noun/verb | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *bahng-moon*; At The Airport > Words, p.62 |
| (#)박 (#)일 | (#) nights and (#) days | numeral phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | nights-word precedes days-word in Korean (reverse of English order), see grammar note; Lodging > Expressions, p.65 |
| 예약 하셨습니까? | Do you have a reservation? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *yeh-yahk hah-shyuht-s_m-neek-gah?*; Lodging > Expressions, p.65 |
| 예약 안 했는데요 | (It's that) I didn't make a reservation | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *yeh-yahk ahn-hehn-n_n-deh-yo*; Lodging > Expressions, p.65 |
| 예약 했는데요 | (It's that) I made a reservation | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *yeh-yahk hehn-n_n-deh-yo*; Lodging > Expressions, p.65 |
| 방 있습니까? | Is there a room available? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *bahng eet-s_m-neek-gah?*; Lodging > Expressions, p.65 |
| 일박에 얼마입니까? | What is your per night rate? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *eel-bah-geh uhl-mah-eem-neek-gah?*; Lodging > Expressions, p.65 |
| 식사 포함입니까? | Does it include a meal? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *sheek-sah poh-hahm-eem-neek-gah?*; Lodging > Expressions, p.65 |
| (date)까지 있고 싶은데요 | (It's that) I'd like to stay until (date) | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *(date)gah-jee eet-goh-shee-p_n-deh-yo*; Lodging > Expressions, p.65 |
| 체크아웃는 몇 시입니까? | What is your check-out time? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *cheh-k_-ah-oo-t_-n_n myuht-shee-eem-neek-gah?*; Lodging > Expressions, p.66 |
| 몇 시까지 방 비워야 합니까? | By what time should I be out of the room? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *myuht-sheek-gah-jee bahng bee-wuh-yah-hahm-neek-gah?*; Lodging > Expressions, p.66 |
| (a thing) 없는데요 | (It's that) there isn't (a thing) | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *(a thing) uhm-n_n-deh-yo*; Lodging > Expressions, p.66 |
| (a thing) 필요한데요 | (It's that) I need (a thing) | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *(a thing) pee-ryo-hahn-deh-yo*; Lodging > Expressions, p.66 |
| 연회장 | banquet hall | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *yuhn-hweh-jahng*; Lodging > Words, p.66 |
| 목욕 | bath | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *moh-gyok*; Lodging > Words, p.66 |
| 비즈니스센터 | business center | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *bee-jee-nee-s_-sehn-tuh*; loanword; Lodging > Words, p.66 |
| 면세점 | duty-free shop | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *myuhn-seh-juhm*; Lodging > Words, p.66 |
| 부대시설 | facilities | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *boo-deh-shee-suhl*; Lodging > Words, p.66 |
| 객실 | guest room | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *gehk-sheel*; Lodging > Words, p.66 |
| 체육관 | gym | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *cheh-yook-gwahn*; Lodging > Words, p.66 |
| 호텔 | hotel | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *hoh-tehl*; loanword; Lodging > Words, p.66 |
| 여관 | inn | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *yuh-gwahn*; Lodging > Words, p.66 |
| 식사 | meals | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *sheek-sah*; formal register, see grammar note; Lodging > Words, p.66 |
| 조식; 아침 | breakfast | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *joh-sheek; ah-cheem*; formal/informal pair, see grammar note; Lodging > Words, p.66 |
| 중식; 점심 | lunch | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *joong-sheek; juhm-shem*; formal/informal pair; Lodging > Words, p.66 |
| 석식; 저녁 | dinner | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *suhk-sheek; juh-nyuhk*; formal/informal pair; Lodging > Words, p.66 |
| 민박 | meenbahk (private-house lodging) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *meen-bahk*; see grammar note; Lodging > Words, p.67 |
| 모텔 | motel | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *moh-tehl*; loanword; Lodging > Words, p.67 |
| 온돌 | on-dohl (Korean underfloor heating) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *ohn-dohl*; culturally specific referent; Lodging > Words, p.67 |
| 예약 | reservation | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *yeh-yahk*; Lodging > Words, p.67 |
| 샤워 | shower | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *shyah-wuh*; loanword; Lodging > Words, p.67 |
| 세면용품 | toiletry | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *seh-myuhn-yong-poom*; Lodging > Words, p.67 |
| 면도기 | razor | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *myuhn-doh-gee*; Lodging > Words, p.67 |
| 비누 | soap | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *bee-noo*; Lodging > Words, p.67 |
| 칫솔 | toothbrush | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *cheet-sohl*; Lodging > Words, p.67 |
| 치약 | toothpaste | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *chee-yahk*; Lodging > Words, p.67 |
| 타월; 수건 | towel | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *tah-wuhl; soo-guhn*; Lodging > Words, p.67 |
| 좀 | a little (intensifier) | adverb | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *johm*; degree modifier, see grammar note; Food & Restaurants > Expressions, p.71 |
| 아주; 너무 | a lot (intensifier) | adverb | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *ah-joo; nuh-moo*; Food & Restaurants > Expressions, p.71 |
| 매워요 | It's spicy | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *meh-wuh-yo*; Food & Restaurants > Expressions (Tastes), p.71 |
| 짜요 | It's salty | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *jjah-yo*; Food & Restaurants > Expressions (Tastes), p.71 |
| 달아요 | It's sweet | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *dah-rah-yo*; Food & Restaurants > Expressions (Tastes), p.71 |
| 고소해요 | It's nutty | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *goh-soh-heh-yo*; Food & Restaurants > Expressions (Tastes), p.71 |
| 싱거워요 | It's bland | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *sheeng-guh-wuh-yo*; Food & Restaurants > Expressions (Tastes), p.71 |
| 써요 | It's bitter | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *ssuh-yo*; Food & Restaurants > Expressions (Tastes), p.71 |
| 시어요 | It's sour | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *shee-uh-yo*; Food & Restaurants > Expressions (Tastes), p.71 |
| 맛있어요 | It's delicious | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *mah-sheet-suh-yo*; Food & Restaurants > Expressions (Tastes), p.71 |
| 맛없어요 | It's not tasty | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *mah-duhp-suh-yo*; Food & Restaurants > Expressions (Tastes), p.71 |
| 뜨거워요 | It's hot (temperature) | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *dd_-guh-wuh-yo*; Food & Restaurants > Expressions (Temperature), p.71 |
| 차가워요; 차요 | It's cold | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *chah-gah-wuh-yo; chah-yo*; Food & Restaurants > Expressions (Temperature), p.71 |
| 미지근해요 | It's lukewarm | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *mee-jee-g_n-heh-yo*; Food & Restaurants > Expressions (Temperature), p.71 |
| 여기 뭐가 맛있어요? | What's good/tasty here? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *yuh-gee muh-gah mah-sheet-suh-yo?*; Food & Restaurants > Expressions (Others), p.71 |
| (a name of food) 주세요 | Please give me (a name of food) | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *(a name of food) joo-seh-yo*; Food & Restaurants > Expressions, p.71-72 |
| (amount) (food) 주세요 | Please give me (amount) of (a name of food) | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *(amount) joo-seh-yo*; Food & Restaurants > Expressions, p.72 |
| 어느 나라 음식 좋아하세요? | Which ethnic food do you like? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *uh-n_-nah-rah _m-sheek joh-ah-hah-seh-yo?*; Food & Restaurants > Expressions, p.72 |
| ~ 신선해요 | ~ is fresh | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *~ sheen-suhn-heh-yo*; Food & Restaurants > Expressions, p.72 |
| 제과점; 빵집 | bakery | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *jeh-gwah-juhm; bbahng-jeep*; Food & Restaurants > Words, p.72 |
| 음료수 | beverages | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *_m-nyo-soo*; Food & Restaurants > Words, p.72 |
| 커피 | coffee | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *kuh-pee*; loanword; Food & Restaurants > Words, p.72 |
| 주스 | juice | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *joo-s_*; loanword; Food & Restaurants > Words, p.72 |
| 우유 | milk | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *oo-yoo*; Food & Restaurants > Words, p.72 |
| 티; 차 | tea | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *tee; chah*; Food & Restaurants > Words, p.72 |
| 물 | water | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *mool*; Food & Restaurants > Words, p.72 |
| 빵 | bread | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *bbahng*; Food & Restaurants > Words, p.72 |
| 버터 | butter | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *buh-tuh*; loanword; Food & Restaurants > Words, p.72 |
| 케이크 | cake | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *keh-ee-k_*; loanword; Food & Restaurants > Words, p.72 |
| 치즈 | cheese | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *chee-j_*; loanword; Food & Restaurants > Words, p.72 |
| 쿠키 | cookies | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *koo-kee*; loanword; Food & Restaurants > Words, p.72 |
| 크래커 | crackers | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *k_-reh-kuh*; loanword; Food & Restaurants > Words, p.72 |
| 과자 | crackers, cookies, chips, etc. (general snack) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *gwah-jah*; Food & Restaurants > Words, p.72 |
| 도너츠 | donuts | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *doh-nuh-ch_*; loanword; Food & Restaurants > Words, p.72 |
| 만두 | dumpling | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *mahn-doo*; Food & Restaurants > Words, p.72 |
| 후식; 디저트 | dessert | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *hoo-sheek; dee-juh-t_*; Food & Restaurants > Words, p.72 |
| 계란; 달걀 | eggs | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *geh-rahn; dahl-gyahl*; Food & Restaurants > Words, p.72 |
| 외국 음식 | ethnic food | noun phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *weh-gook _m-sheek*; can take 점 suffix for the restaurant itself, see grammar note; Food & Restaurants > Words, p.73 |
| 중국 음식 | Chinese food | noun phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *joong-gook _m-sheek*; Food & Restaurants > Words, p.73 |
| 일본 음식 | Japanese food | noun phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *eel-bohn _m-sheek*; Food & Restaurants > Words, p.73 |
| 인도 음식 | Indian food | noun phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *een-doh _m-sheek*; Food & Restaurants > Words, p.73 |
| 이태리 음식 | Italian food | noun phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *ee-teh-ree _m-sheek*; Food & Restaurants > Words, p.73 |
| 베트남 음식 | Vietnamese food | noun phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *beh-t_-nahm _m-sheek*; Food & Restaurants > Words, p.73 |
| 생선 | fish (edible) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *sehng-suhn*; Food & Restaurants > Words, p.73 |
| 대구 | codfish | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *deh-goo*; Food & Restaurants > Words, p.73 |
| 고등어 | mackerel | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *goh-d_ng-uh*; Food & Restaurants > Words, p.73 |
| 생태 | pollack | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *sehng-teh*; Food & Restaurants > Words, p.73 |
| 연어 | salmon | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *yuh-nuh*; Food & Restaurants > Words, p.73 |
| 참치 | tuna | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *chahm-chee*; Food & Restaurants > Words, p.73 |
| 음식 | food | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *_m-sheek*; Food & Restaurants > Words, p.73 |
| 과일 | fruits | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *gwah-eel*; Food & Restaurants > Words, p.73 |
| 사과 | apple | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *sah-gwah*; Food & Restaurants > Words, p.73 |
| 바나나 | banana | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *bah-nah-nah*; loanword; Food & Restaurants > Words, p.73 |
| 참외 | Korean melon | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *chah-mweh*; culturally specific referent; Food & Restaurants > Words, p.73 |
| 메론 | melon | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *meh-rohn*; loanword; Food & Restaurants > Words, p.73 |
| 오렌지 | orange (fruit) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *oh-rehn-jee*; loanword; Food & Restaurants > Words, p.73 |
| 배 | pear | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *beh*; Food & Restaurants > Words, p.73 |
| 감 | persimmon | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *gahm*; Food & Restaurants > Words, p.73 |
| 딸기 | strawberry | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *ddahl-gee*; Food & Restaurants > Words, p.73 |
| 귤 | tangerine | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *gyool*; Food & Restaurants > Words, p.73 |
| 수박 | water melon | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *soo-bahk*; Food & Restaurants > Words, p.73 |
| 아이스크림 | ice cream | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *ah-ee-s_-k_-reem*; loanword; Food & Restaurants > Words, p.73 |
| 한국 음식; 한식 | Korean food | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *hahn-gook _m-sheek; hahn-sheek*; Food & Restaurants > Words, p.73 |
| 한국 음식점; 한식점 | Korean restaurant | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *hahn-gook-_m-sheek-juhm; hahn-sheek-juhm*; Food & Restaurants > Words, p.73 |
| 반찬 | Korean side dishes | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *bahn-chahn*; Food & Restaurants > Words, p.73, 76 |
| 식사 | meals | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *sheek-sah*; repeated from Lodging ch.; Food & Restaurants > Words, p.74 |
| 아침 | breakfast | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *ah-cheem*; Food & Restaurants > Words, p.74 |
| 점심 | lunch | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *juhm-sheem*; Food & Restaurants > Words, p.74 |
| 저녁 | dinner | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *juh-nyuhk*; Food & Restaurants > Words, p.74 |
| 고기 | meat | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *goh-gee*; Food & Restaurants > Words, p.74 |
| 소고기 | beef | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *soh-goh-gee*; Food & Restaurants > Words, p.74 |
| 닭고기 | chicken | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *dahk-goh-gee*; Food & Restaurants > Words, p.74 |
| 양고기 | lamb | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *yahng-goh-gee*; Food & Restaurants > Words, p.74 |
| 돼지고기 | pork | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *dweh-jee-goh-gee*; Food & Restaurants > Words, p.74 |
| 국수 | noodle | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *gook-soo*; Food & Restaurants > Words, p.74 |
| 너츠 | nuts | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *nuh-ch_*; loanword; Food & Restaurants > Words, p.74 |
| 밤 | chestnut | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *bahm*; Food & Restaurants > Words, p.74 |
| 땅콩 | peanut | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *ddahng-kohng*; Food & Restaurants > Words, p.74 |
| 잣 | pignolia; pine nut | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *jaht*; Food & Restaurants > Words, p.74 |
| 호두 | walnut | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *hoh-doo*; Food & Restaurants > Words, p.74 |
| 유기농 식품 | organic food | noun phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *yoo-gee-nohng-sheek-poom*; Food & Restaurants > Words, p.74 |
| 음식 양 | portions/amount of food | noun phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *_m-sheek yahng*; Food & Restaurants > Words, p.74 |
| (Korean #) 잔 | # of glasses | classifier phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *(#) jahn*; native-Korean-number classifier; Food & Restaurants > Words, p.74 |
| (Chinese #) 인분 | # of people(-servings) | classifier phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *(#) een-boon*; Sino-Korean-number classifier; Food & Restaurants > Words, p.74 |
| (Korean #) 접시 | # of plates | classifier phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *(#) juhp-shee*; Food & Restaurants > Words, p.74 |
| (Korean #) 모금 | # of sips | classifier phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *(#) moh-g_m*; Food & Restaurants > Words, p.74 |
| 레스토랑; 식당; 음식점 | restaurant | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *reh-s_-toh-rahng; sheek-dahng; _m-sheek-juhm*; register distinction, see grammar note; Food & Restaurants > Words, p.74 |
| 분식점 | eateries (casual) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *boon-sheek-juhm*; see grammar note; Food & Restaurants > Words, p.74 |
| 쌀 | rice (uncooked) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *ssahl*; Food & Restaurants > Words, p.74 |
| 밥 | rice (cooked) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *bahp*; Food & Restaurants > Words, p.74 |
| 해산물 | seafood | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *heh-sahn-mool*; Food & Restaurants > Words, p.75 |
| 조게 | clam | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *joh-geh*; Food & Restaurants > Words, p.75 |
| 게 | crab | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *geh*; Food & Restaurants > Words, p.75 |
| 생선 | fish | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *sehng-suhn*; repeated term; Food & Restaurants > Words, p.75 |
| 홍합 | mussel | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *hohng-hahp*; Food & Restaurants > Words, p.75 |
| 낙지 | octopus | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *nahk-jee*; Food & Restaurants > Words, p.75 |
| 새우 | shrimp | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *seh-oo*; Food & Restaurants > Words, p.75 |
| 오징어 | squid | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *oh-jeeng-uh*; Food & Restaurants > Words, p.75 |
| 양념 | seasoning | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *yahng-nyuhm*; Food & Restaurants > Words, p.75 |
| 후춧가루 | black pepper powder | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *hoo-choot-gah-roo*; Food & Restaurants > Words, p.75 |
| 고춧가루 | red pepper powder | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *goh-choot-gah-roo*; Food & Restaurants > Words, p.75 |
| 소금 | salt | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *soh-g_m*; Food & Restaurants > Words, p.75 |
| 참기름 | sesame oil | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *chahm-gee-r_m*; Food & Restaurants > Words, p.75 |
| 설탕 | sugar | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *suhl-tahng*; Food & Restaurants > Words, p.75 |
| 식초 | vinegar | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *sheek-choh*; Food & Restaurants > Words, p.75 |
| 스낵 | snack | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *s_-nehk*; loanword; Food & Restaurants > Words, p.75 |
| 맛 | tastes | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *maht*; Food & Restaurants > Words, p.75 |
| 도구 | utensils | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *doh-goo*; Food & Restaurants > Words, p.75 |
| 그릇 | bowl; plate | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *g_-r_t*; Food & Restaurants > Words, p.75 |
| 공기 | bowl (usu. for rice) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *gohng-gee*; Food & Restaurants > Words, p.75 |
| 냄비 | cauldron | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *nehm-bee*; Food & Restaurants > Words, p.75 |
| 젓가락 | chopsticks | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *juht-gah-rahk*; Food & Restaurants > Words, p.75 |
| 포크 | fork | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *poh-k_*; loanword; Food & Restaurants > Words, p.75 |
| 나이프 | knife (for eating) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *nah-ee-p_*; loanword; Food & Restaurants > Words, p.75 |
| 칼 | knife (for cooking) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *kahl*; Food & Restaurants > Words, p.75 |
| 국자 | ladle | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *gook-jah*; Food & Restaurants > Words, p.75 |
| 냅킨 | napkin | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *nehp-keen*; loanword; Food & Restaurants > Words, p.75 |
| 접시 | plate | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *juhp-shee*; Food & Restaurants > Words, p.75 |
| 앞접시 | serving plate | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *ahp-juhp-shee*; Food & Restaurants > Words, p.75 |
| 숟가락; 수저 | spoon | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *soot-gah-rahk; soo-juh*; Food & Restaurants > Words, p.75 |
| 채소; 야채 | vegetables | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *cheh-soh; yah-cheh*; Food & Restaurants > Words, p.76 |
| 배추 | cabbage (Korean) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *beh-choo*; Food & Restaurants > Words, p.76 |
| 당근; 홍당무 | carrot | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *dahng-g_n; hohng-dahng-moo*; Food & Restaurants > Words, p.76 |
| 마늘 | garlic | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *mah-n_l*; Food & Restaurants > Words, p.76 |
| 생강 | ginger | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *sehng-gahng*; Food & Restaurants > Words, p.76 |
| 고추 | hot pepper | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *goh-choo*; Food & Restaurants > Words, p.76 |
| 레터스 | lettuce | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *leh-tuh-s_*; loanword; Food & Restaurants > Words, p.76 |
| 양파 | onion | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *yahng-pah*; Food & Restaurants > Words, p.76 |
| 감자 | potato | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *gahm-jah*; Food & Restaurants > Words, p.76 |
| 파 | scallion | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *pah*; Food & Restaurants > Words, p.76 |
| 시금치 | spinach | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *shee-g_m-chee*; Food & Restaurants > Words, p.76 |
| 고구마 | sweet potato | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *goh-goo-mah*; Food & Restaurants > Words, p.76 |
| 토마토 | tomato | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *toh-mah-toh*; loanword; Food & Restaurants > Words, p.76 |
| 물 | water | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *mool*; Food & Restaurants > Words, p.76 |
| 찬물 | cold water | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *chahn-mool*; Food & Restaurants > Words, p.76 |
| 뜨거운물 | hot water | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *dd_-guh-oon-mool*; Food & Restaurants > Words, p.76 |
| 얼음물 | ice water | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *uh-r_m-mool*; Food & Restaurants > Words, p.76 |
| 만두 | dumpling | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *mahn-doo*; repeated term, "Others" subsection; Food & Restaurants > Words, p.76 |
| 떡 | Korean rice cake | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *dduhk*; Food & Restaurants > Words, p.76 |
| 반찬 | Korean side dishes | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *bahn-chahn*; repeated term; Food & Restaurants > Words, p.76 |
| 초밥 | sushi | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *choh-bahp*; Food & Restaurants > Words, p.76 |
| 튀김 | tempura | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *twee-geem*; loanword (from Japanese); Food & Restaurants > Words, p.76 |
| (a person)한테 잘 어울려요 | It looks good on (a person) | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *(a person)hahn-teh jahl uh-ool-lyuh-yo*; All About Fashion > Expressions, p.79 |
| 오늘 아주 멋있는데요 | You look very nice/stylish today | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *oh-n_l ah-joo muh-sheen-n_n-deh-yo*; All About Fashion > Expressions, p.79 |
| 요즘 (a thing) 유행이에요 | (a thing) is in fashion these days | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *yo-j_m (a thing) yoo-hehng-ee-eh-yo*; All About Fashion > Expressions, p.79 |
| (a thing) 유행 지났어요 | (a thing) is outmoded | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *(a thing) yoo-hehng jee-naht-suh-yo*; All About Fashion > Expressions, p.79 |
| 무슨 색이 어울려요? | Which color looks good (with something)? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *moo-s_n-seh-gee uh-ool-lyuh-yo?*; All About Fashion > Expressions, p.79 |
| (person/thing) 세련됐어요 | (person/thing) has a sense of style | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *(person/thing) seh-ryuhn-dweht-suh-yo*; All About Fashion > Expressions, p.79 |
| 소매 줄여 주세요 | Shorten the sleeves, please | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *soh-meh joo-ryuh-joo-seh-yo*; All About Fashion > Expressions (Alteration Shop), p.79 |
| 바지 단 줄여 주세요 | Shorten the pants length, please | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *bah-jee dahn joo-ryuh-joo-seh-yo*; All About Fashion > Expressions, p.79 |
| 늘여 주세요 | Make it bigger/longer, please | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *n_-ryuh joo-seh-yo*; All About Fashion > Expressions, p.79 |
| 액세서리 | accessories | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *ehk-seh-suh-ree*; loanword; All About Fashion > Words, p.80 |
| 발찌 | anklet | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *bahl-jjee*; All About Fashion > Words, p.80 |
| 벨트; 혁대 | belt | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *behl-t_; hyuhk-deh*; All About Fashion > Words, p.80 |
| 블라우스 | blouse | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *b_l-lah-oo-s_*; loanword; All About Fashion > Words, p.80 |
| 청바지 | blue jeans | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *chuhng-bah-jee*; All About Fashion > Words, p.80 |
| 팔찌 | bracelet | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *pahl-jjee*; All About Fashion > Words, p.80 |
| 단추 | buttons | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *dahn-choo*; All About Fashion > Words, p.80 |
| 모자 | cap | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *moh-jah*; All About Fashion > Words, p.80 |
| 캐주얼 | casual wear | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *keh-joo-uhl*; loanword; All About Fashion > Words, p.80 |
| 옷 | clothing | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *oht*; All About Fashion > Words, p.80 |
| 코트 | coat | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *koh-t_*; loanword; All About Fashion > Words, p.80 |
| 색; 색깔 | colors | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *sehk; sehk-gahl*; see grammar note; All About Fashion > Words, p.80 |
| 까망; 검정 | black | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *ggah-mahng; guhm-juhng*; All About Fashion > Words, p.80 |
| 파랑 | blue | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *pah-rahng*; All About Fashion > Words, p.80 |
| 자주 | burgundy | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *jah-joo*; All About Fashion > Words, p.80 |
| 초록 | green | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *choh-rohk*; All About Fashion > Words, p.80 |
| 회색 | gray | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *hweh-sehk*; All About Fashion > Words, p.80 |
| 곤색 | navy blue | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *gohn-sehk*; All About Fashion > Words, p.80 |
| 주황; 오렌지색 | orange (color) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *joo-hwahng; oh-rehn-jee-sehk*; see grammar note (색-exception); All About Fashion > Words, p.80 |
| 분홍; 핑크 | pink | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *boon-hohng; peeng-k_*; All About Fashion > Words, p.80 |
| 보라 | purple | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *boh-rah*; All About Fashion > Words, p.81 |
| 빨강 | red | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *bbahl-gahng*; All About Fashion > Words, p.81 |
| 하늘색 | sky blue | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *hah-n_l-sehk*; see grammar note (색-exception); All About Fashion > Words, p.81 |
| 하양 | white | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *hah-yahng*; All About Fashion > Words, p.81 |
| 노랑 | yellow | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *noh-rahng*; All About Fashion > Words, p.81 |
| 드레스 | dress | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *d_-reh-s_*; loanword; All About Fashion > Words, p.81 |
| 와이셔츠 | dress shirt | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *wah-ee-shuh-ch_*; loanword; All About Fashion > Words, p.81 |
| 귀걸이 | earrings | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *gwee-guh-ree*; All About Fashion > Words, p.81 |
| 감; 천 | fabric | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *gahm; chuhn*; All About Fashion > Words, p.81 |
| 정장 | formal wear | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *juhng-jahng*; All About Fashion > Words, p.81 |
| 안경 | glasses | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *ahn-gyuhng*; All About Fashion > Words, p.81 |
| 장갑 | gloves | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *jahng-gahp*; All About Fashion > Words, p.81 |
| 머리 | hair | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *muh-ree*; All About Fashion > Words, p.81 |
| 이발소 | barber shop | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *ee-bahl-soh*; All About Fashion > Words, p.81 |
| 염색 | coloring (hair) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *yuhm-sehk*; All About Fashion > Words, p.81 |
| 고대기 | curling iron | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *goh-deh-gee*; All About Fashion > Words, p.81 |
| 드라이기 | dryer | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *d_-rah-ee-gee*; loanword; All About Fashion > Words, p.81 |
| 헤어커트 | haircut | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *heh-uh-kuh-t_*; loanword; All About Fashion > Words, p.81 |
| 머리핀 | hairpin | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *muh-ree-peen*; All About Fashion > Words, p.81 |
| 미장원; 머리방 | hair salon | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *mee-jahng-wuhn; muh-ree-bahng*; All About Fashion > Words, p.81 |
| 머리 스타일 | hair style | noun phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *muh-ree s_-tah-eel*; All About Fashion > Words, p.81 |
| 파마 | perm | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *pah-mah*; loanword; All About Fashion > Words, p.81 |
| 모자 | hat | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *moh-jah*; repeated term (same as "cap"); All About Fashion > Words, p.81 |
| 하이힐 | high heels | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *hah-ee-heel*; loanword; All About Fashion > Words, p.81 |
| 재킷 | jacket | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *jeh-keet*; loanword; All About Fashion > Words, p.81 |
| 속옷 | lingerie | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *soh-goht*; All About Fashion > Words, p.81 |
| 화장 | makeup | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *hwah-jahng*; All About Fashion > Words, p.81 |
| 화장품 | makeup products | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *hwah-jahng-poom*; All About Fashion > Words, p.81 |
| 남자옷 | men's clothing | noun phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *nahm-jah-oht*; All About Fashion > Words, p.81 |
| 목도리 | muffler | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *mohk-doh-ree*; All About Fashion > Words, p.81 |
| 목걸이 | necklace | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *mohk-guh-ree*; All About Fashion > Words, p.82 |
| 넥타이; 타이 | necktie | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *nehk-tah-ee; tah-ee*; loanword; All About Fashion > Words, p.82 |
| 잠옷 | pajama | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *jah-moht*; All About Fashion > Words, p.82 |
| 바지 | pants | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *bah-jee*; All About Fashion > Words, p.82 |
| 무늬 | patterns | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *moo-nee*; All About Fashion > Words, p.82 |
| 향수 | perfume | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *hyahng-soo*; All About Fashion > Words, p.82 |
| 우비 | raincoat | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *oo-bee*; All About Fashion > Words, p.82 |
| 반지 | ring | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *bahn-jee*; All About Fashion > Words, p.82 |
| 스카프 | scarf | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *s_-kah-p_*; loanword; All About Fashion > Words, p.82 |
| 서츠 | shirt | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *shuh-ch_*; loanword; All About Fashion > Words, p.82 |
| 신발 | shoes | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *sheen-bahl*; All About Fashion > Words, p.82 |
| 부츠 | boots | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *boo-ch_*; loanword; All About Fashion > Words, p.82 |
| 구두 | dress shoes | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *goo-doo*; All About Fashion > Words, p.82 |
| 하이힐 | high heels | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *hah-ee-heel*; repeated term; All About Fashion > Words, p.82 |
| 장화 | rain boots | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *jahng-hwah*; All About Fashion > Words, p.82 |
| 슬리퍼 | slippers | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *s_l-lee-puh*; loanword; All About Fashion > Words, p.82 |
| 운동화 | sneakers | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *oon-dohng-hwah*; All About Fashion > Words, p.82 |
| 반바지 | shorts | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *bahn-bah-jee*; All About Fashion > Words, p.82 |
| 반팔 셔츠 | short-sleeve shirt | noun phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *bahn-pahl-shuh-ch_*; All About Fashion > Words, p.82 |
| 치마 | skirt | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *chee-mah*; All About Fashion > Words, p.82 |
| 양말 | socks | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *yahng-mahl*; All About Fashion > Words, p.82 |
| 운동복 | sportswear | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *oon-dohng-bohk*; All About Fashion > Words, p.82 |
| 스타킹 | stockings | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *s_-tah-keeng*; loanword; All About Fashion > Words, p.82 |
| 양복 | suit (men's suit) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *yahng-bohk*; All About Fashion > Words, p.82 |
| 선글라스 | sunglasses | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *suhn-g_l-lah-s_*; loanword; All About Fashion > Words, p.82 |
| 스웨터 | sweater | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *s_-weh-tuh*; loanword; All About Fashion > Words, p.82 |
| 우산 | umbrella | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *oo-sahn*; All About Fashion > Words, p.82 |
| 속옷 | undergarment | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *soh-goht*; repeated term (same as "lingerie"); All About Fashion > Words, p.82 |
| 조끼 | vest | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *johk-gee*; All About Fashion > Words, p.82 |
| 시계 | watch | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *shee-geh*; All About Fashion > Words, p.82 |
| 여자옷 | women's clothing | noun phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | *yuh-jah-oht*; All About Fashion > Words, p.82 |
| (a thing) 보고 싶은데요 | (It's that) I'd like to see (a thing) | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | boh-goh-shee-p_n-deh-yo; Shopping p.85, Expressions |
| 이거 (size) 있어요? | Do you have this in (size)? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | ee-guh (size) eet-suh-yo?; Shopping p.85 |
| 이거 (color) 있어요? | Do you have this in (color)? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | ee-guh (color) eet-suh-yo?; Shopping p.85 |
| 좋은데요 | (It's that) it's nice | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | joh-_n-deh-yo; Shopping p.85 |
| 얼마예요? | How much is it? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | uhl-mah-eh-yo?; Shopping p.85 |
| 신용 카드 받으세요? | Do you take credit cards? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | shee-nyong-kah-d_ bah-d_-seh-yo?; Shopping p.85 |
| 환불 됩니까? | Is a refund possible? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | hwahn-bool dwehm-neek-gah?; Shopping p.85 |
| 교환 됩니까? | Is an exchange possible? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | gyo-hwahn dwehm-neek-gah?; Shopping p.85 |
| 너무 비싼데요 | (It's that) it's too expensive | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | nuh-moo beet-sahn-deh-yo; Shopping p.85 |
| 이거 주세요 | Please give me this | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | ee-guh joo-seh-yo; Shopping p.85 |
| 골동품 | antique | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | gohl-dohng-poom; Shopping p.85 |
| 경매 | auction | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | gyuhng-meh; Shopping p.85 |
| 현금 | cash | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | hyuhn-g_m; Shopping p.85 |
| 편의점 | convenience store | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | pyuh-nee-juhm; Shopping p.85 |
| 신용카드 | credit card | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | shee-nyong-kah-d_; Shopping p.85 |
| 백화점 | department store | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | beh-kwah-juhm; Shopping p.86 |
| 명품 | designer merchandise | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | myuhng-poom; Shopping p.86 |
| 할인; 디시 | discount | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | hah-reen; dee-see; Shopping p.86 |
| 면세품 | duty-free merchandise | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | myuhn-seh-poom; Shopping p.86 |
| 면세점 | duty-free shop | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | myuhn-seh-juhm; Shopping p.86 |
| 바가지 | getting ripped off | noun | colloquial | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | bah-gah-jee; Shopping p.86; idiomatic consumer-complaint term |
| 흥정 | haggling | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | h_ng-juhng; Shopping p.86 |
| 시장 | market | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | shee-jahng; Shopping p.86 |
| 지불 | payment | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | jee-bool; Shopping p.86 |
| 분할; 할부 | installment (payment) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | boon-hahl; hahl-boo; Shopping p.86 |
| 완불 | payment in full | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | wahn-bool; Shopping p.86 |
| 값; 가격 | price | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | gahp; gah-gyuhk; Shopping p.86 |
| 정가 | marked price | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | juhng-ggah; Shopping p.86 |
| 가격표 | price tag | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | gah-gyuhk-pyo; Shopping p.86 |
| 구매 | purchase | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | goo-meh; Shopping p.86 |
| 소매 | retail | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | soh-meh; Shopping p.86 |
| 세일 | sale (discount) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | seh-eel; Shopping p.86; English loanword |
| 상가 | shopping district | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | sahng-gah; Shopping p.86 |
| 가게; 상점 | store | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | gah-geh; sahng-juhm; Shopping p.86; see footnote — 가게 can be suffixed to a product name to name its dedicated store |
| 수퍼(마켓) | supermarket | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | soo-puh(-mah-keht); Shopping p.86; English loanword |
| 중고품 | used merchandise | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | joong-goh-poom; Shopping p.86 |
| 도매 | wholesale | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | doh-meh; Shopping p.86 |
| 운동 하세요? | Do you exercise? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | oon-dohng hah-seh-yo?; Sports p.89 |
| 무슨 운동 좋아하세요? | What kind of sports do you like? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | moo-s_n-oon-dohng joh-ah-hah-seh-yo?; Sports p.89 |
| 누구 편이세요? | Which side are you on? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | noo-goo-pyuh-nee-seh-yo?; Sports p.89 |
| 누구 응원하세요? | Who are you rooting for? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | noo-goo _ng-wuhn-hah-seh-yo?; Sports p.89 |
| (player/team) 팬이세요? | Are you a fan of (player/team)? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | peh-nee-seh-yo?; Sports p.89 |
| (player/team) 팬이에요 | I am a fan of (player/team) | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | peh-nee-eh-yo; Sports p.89 |
| 아마추어 | amateur | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | ah-mah-choo-uh; Sports p.89; English loanword |
| 당구 | billiard | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | dahng-goo; Sports p.89 |
| 응원 | cheering | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | _ng-wuhn; Sports p.89 |
| 운동 | exercise | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | oon-dohng; Sports p.89 |
| 헬스; 헬스클럽 | gym | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | hehl-s_; hehl-s_-k_l-luhp; Sports p.89; English loanword ("health (club)") |
| 등산 | hiking | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | d_ng-sahn; Sports p.89 |
| 선수 | player | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | suhn-soo; Sports p.89 |
| 연습 | practice | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | yuhn-s_p; Sports p.89 |
| 프로 | pro | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | p_-roh; Sports p.89; English loanword |
| 스포츠; 운동 | sports | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | s_-poh-ch_; oon-dohng; Sports p.90 |
| 야구 | baseball | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | yah-goo; Sports p.90 |
| 농구 | basketball | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | nohng-goo; Sports p.90 |
| 권투; 복싱 | boxing | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | gwuhn-too; bohk-sheeng; Sports p.90 |
| 미식축구 | football (American) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | mee-sheek-chook-goo; Sports p.90; lit. "American-style football" |
| 조깅 | jogging | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | joh-geeng; Sports p.90; English loanword |
| 축구 | soccer | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | chook-goo; Sports p.90 |
| 수영 | swimming | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | soo-yuhng; Sports p.90 |
| 테니스 | tennis | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | teh-nee-s_; Sports p.90; English loanword |
| 육상 | track & field | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | yook-sahng; Sports p.90 |
| 배구 | volleyball | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | beh-goo; Sports p.90 |
| 걷기; 워킹 | walking | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | guht-gee; wuh-keeng; Sports p.90 |
| 레슬링 | wrestling | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | leht-s_l-leeng; Sports p.90; English loanword |
| 팀 | team | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | teem; Sports p.90; English loanword |
| (thing/person) 좋아하세요? | Do you like (thing/person)? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | joh-ah-hah-seh-yo?; Arts & Entertainment p.93 |
| 어떤 (things) 좋아하세요? | What kind of (things) do you like? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | uht-duhn (things) joh-ah-hah-seh-yo?; Arts & Entertainment p.93 |
| 악기 하세요? | Do you play an instrument? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | ahk-gee hah-seh-yo?; Arts & Entertainment p.93 |
| 취미가 뭐세요? | What are your hobbies? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | chwee-mee-gah mwuh-seh-yo?; Arts & Entertainment p.93 |
| 건축 | architecture | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | guhn-chook; Arts & Entertainment p.93 |
| 예술 | art (in general) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | yeh-sool; Arts & Entertainment p.93 |
| 미술관 | art museum | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | mee-sool-gwahn; Arts & Entertainment p.93 |
| 미술 | arts | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | mee-sool; Arts & Entertainment p.93 |
| 도예 | ceramics | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | doh-yeh; Arts & Entertainment p.93 |
| 유화 | oil painting | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | yoo-hwah; Arts & Entertainment p.93 |
| 그림 | painting | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | g_-reem; Arts & Entertainment p.93 |
| 조각 | sculpture | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | joh-gahk; Arts & Entertainment p.93 |
| 수채화 | watercolor painting | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | soo-cheh-hwah; Arts & Entertainment p.93 |
| 전위예술 | avant-garde art | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | juhn-wee-yeh-sool; Arts & Entertainment p.93 |
| 발레 | ballet | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | bahl-leh; Arts & Entertainment p.93; English/French loanword |
| 만화 | cartoon | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | mahn-hwah; Arts & Entertainment p.93 |
| 공연; 콘서트 | concert | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | gohng-yuhn; kohn-suh-t_; Arts & Entertainment p.93 |
| 요리 | cooking | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | yo-ree; Arts & Entertainment p.93 |
| 문화 | culture | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | moon-hwah; Arts & Entertainment p.93 |
| 춤; 댄스 | dance | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | choom; dehn-s_; Arts & Entertainment p.93 |
| 전시회 | exhibition | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | juhn-shee-hweh; Arts & Entertainment p.93 |
| 패션 | fashion | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | peht-shyuhn; Arts & Entertainment p.94; English loanword |
| 화랑; 갤러리 | gallery | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | hwah-rahng; gehl-luh-ree; Arts & Entertainment p.94 |
| 실내장식 | interior design | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | sheel-leh-jahng-sheek; Arts & Entertainment p.94 |
| 문학 | literature | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | moon-hahk; Arts & Entertainment p.94 |
| 소설 | novel | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | soh-suhl; Arts & Entertainment p.94 |
| 소설가 | novelist | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | soh-suhl-gah; Arts & Entertainment p.94 |
| 희곡 | play; drama (text) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | hee-gohk; Arts & Entertainment p.94 |
| 극작가 | playwright | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | g_k-jahk-gah; Arts & Entertainment p.94 |
| 시인 | poet | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | shee-een; Arts & Entertainment p.94 |
| 시 | poetry | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | shee; Arts & Entertainment p.94 |
| 미디아 | mass media | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | mee-dee-ah; Arts & Entertainment p.94; English loanword |
| 필름 | film | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | peel-l_m; Arts & Entertainment p.94; English loanword |
| 잡지 | magazine | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | jahp-jee; Arts & Entertainment p.94 |
| 신문 | newspaper | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | sheen-moon; Arts & Entertainment p.94 |
| 티비 | tv | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | tee-bee; Arts & Entertainment p.94; English loanword |
| 영화 | movie | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | yuhng-hwah; Arts & Entertainment p.94 |
| 영화 감상 | movie appreciation | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | yuhng-hwah gahm-sahng; Arts & Entertainment p.94 |
| 박물관 | museum | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | bahng-mool-gwahn; Arts & Entertainment p.94 |
| 박물관 방문 | museum visit | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | bahng-mool-gwahn bahng-moon; Arts & Entertainment p.94 |
| 음악 | music | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | _-mahk; Arts & Entertainment p.94 |
| 뮤지컬 | musical | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | myoo-jee-kuhl; Arts & Entertainment p.94; English loanword |
| 음악회 | music concert | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | _-mahk-kweh; Arts & Entertainment p.94 |
| 악기 | musical instrument | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | ahk-gee; Arts & Entertainment p.94 |
| 오페라 | opera | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | oh-peh-rah; Arts & Entertainment p.94; English loanword |
| 사진 | photographs | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | sah-jeen; Arts & Entertainment p.94 |
| 연극 | play (theater) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | yuhn-g_k; Arts & Entertainment p.94 |
| 독서 | reading | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | dohk-suh; Arts & Entertainment p.95 |
| 노래 부르기 | singing | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | noh-reh boo-r_-gee; Arts & Entertainment p.95 |
| 노래 | songs | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | noh-reh; Arts & Entertainment p.95 |
| 누구세요? | Who is it?; Who are you? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | noo-goo-seh-yo?; People p.99 |
| 제가 뭐라고 불러야 합니까?; 제가 어떻게 불러야 합니까? | What should I call (him, her, them, etc.)? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | jeh-gah mwuh-rah-goh bool-luh-yah hahm-neek-gah?; jeh-gah uht-duhk-keh bool-luh-yah hahm-neek-gah?; People p.99; two phrasings given |
| 청소년 | adolescence | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | chuhng-soh-nyuhn; People p.99 |
| 성인; 어른 | adult | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | suhng-een; uh-r_n; People p.99 |
| 노인 | aged person | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | noh-een; People p.99 |
| 아기; 아가 | baby | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | ah-gee; ah-gah; People p.99 |
| 소년 | boy | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | soh-nyuhn; People p.99 |
| 남자친구 | boyfriend | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | nahm-jah-cheen-goo; People p.99 |
| 어린이; 아이 | child | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | uh-ree-nee; ah-ee; People p.99 |
| 적 | enemy | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | juhk; People p.99 |
| 민족 | ethnic group | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | meen-johk; People p.99 |
| 식구 | family members | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | sheek-goo; People p.99 |
| 효녀 | filial daughter | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | hyo-nyuh; People p.99 |
| 효자 | filial son | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | hyo-jah; People p.99 |
| 외국인 | foreigner | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | weh-goo-geen; People p.99 |
| 친구 | friend | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | cheen-goo; People p.99 |
| 우정 | friendship | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | oo-juhng; People p.99 |
| 신사 | gentleman | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | sheen-sah; People p.99 |
| 소녀 | girl | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | soh-nyuh; People p.99 |
| 여자친구 | girlfriend | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | yuh-jah-cheen-goo; People p.99 |
| 영웅 | hero | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | yuhng-oong; People p.99 |
| 사람; 인간 | human | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | sah-rahm; een-gahn; People p.100 |
| 숙녀; 아가씨 | lady | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | soong-nyuh; ah-gaht-shee; People p.100 |
| 남자 | man (opp. woman) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | nahm-jah; People p.100 |
| 백만장자 | millionaire | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | behng-mahn-jahng-jah; People p.100 |
| 이웃 | neighbors | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | ee-oot; People p.100 |
| 타인 | others (opp. self) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | tah-een; People p.100 |
| 인구 | population | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | een-goo; People p.100 |
| 주인공 | protagonist | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | joo-een-gohng; People p.100 |
| 자신; 본인 | self (opp. others) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | jah-sheen; boh-neen; People p.100 |
| 방관자 | spectator | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | bahng-gwahn-jah; People p.100 |
| 인종 | race | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | een-johng; People p.100 |
| 부자 | the rich | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | boo-jah; People p.100 |
| 성인 | saint | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | suhng-een; People p.100; homophone with 성인 "adult" above — distinct word (saint vs. adult), same romanization in this book |
| 패배자 | underdog | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | peh(-beh)-jah; People p.100 |
| 승(리)자 | winner | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | s_ng(-lee)-jah; People p.100 |
| 여자 | woman (opp. man) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | yuh-jah; People p.100 |
| 아저씨 | middle-aged men (address/reference term) | noun | colloquial | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | ah-juht-shee; People p.100-101, "<Others>"; double-edged connotation — see grammar note above |
| 아줌마 | middle-aged women (address/reference term) | noun | colloquial | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | ah-joom-mah; People p.100-101, "<Others>"; double-edged connotation, see grammar note; footnote says fuller form 아주머니 is more polite |
| 아주머니 | middle-aged woman (more polite form) | noun | colloquial | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | ah-joo-muh-nee; People p.101; footnoted as more polite/courteous than 아줌마 |
| 가족이 몇 분이세요? | How many people are in your family? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | gah-joh-gee myuht-boo-nee-seh-yo?; Kinship Terms p.103 |
| 형제가 많으세요? | Do you have many siblings? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | hyuhng-jeh-gah mah-n_-seh-yo?; Kinship Terms p.103 |
| 친척이 많으세요? | Do you have many relatives? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | cheen-chuh-gee mah-n_-seh-yo?; Kinship Terms p.103 |
| 어디 사세요?; 어디 살아요? | Where do they live? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | uh-dee-sah-seh-yo? (elevating the referent); uh-dee sah-rah-yo? (referent equal/junior); Kinship Terms p.103; directly illustrates referent-elevation honorific choice |
| 이모 | aunt (mother's sister) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | ee-moh; Kinship Terms p.104; [referring+addressing] |
| 고모 | aunt (father's sister) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | goh-moh; Kinship Terms p.104; [referring+addressing] |
| 외숙모 | aunt (wife of mother's brother) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | weh-soong-moh; Kinship Terms p.104; [referring+addressing] |
| 숙모 | aunt (wife of father's brother) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | soong-moh; Kinship Terms p.104; [referring+addressing] |
| 형제 | brothers; siblings | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | hyuhng-jeh; Kinship Terms p.104; [referring only]; also used generically for "siblings" of any gender per footnote |
| 오빠 | older brother (for female speaker) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | ohp-bah; Kinship Terms p.104; [referring+addressing] |
| 형 | older brother (for male speaker) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | hyuhng; Kinship Terms p.104; [referring+addressing] |
| 남동생 | younger brother | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | nahm-dohng-sehng; Kinship Terms p.104; [referring only]; footnote: addressed by given name, not this term |
| 사촌 | cousin | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | sah-chohn; Kinship Terms p.104; [referring only]; footnote: addressed using sibling terms (오빠/형/언니/누나) by relative age, or by given name |
| 아빠 | dad | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | ahp-bah; Kinship Terms p.104; [referring+addressing] |
| 딸 | daughter | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | ddahl; Kinship Terms p.104; [referring only] |
| 며느리 | daughter-in-law | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | myuh-n_-ree; Kinship Terms p.104; [referring only] |
| 가족 | family | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | gah-johk; Kinship Terms p.104 |
| 대가족 | extended family | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | deh-gah-johk; Kinship Terms p.104 |
| 핵가족 | nuclear family | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | hehk-gah-johk; Kinship Terms p.104 |
| 아버지 | father | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | ah-buh-jee; Kinship Terms p.104; [referring+addressing] |
| 시아버지 | father-in-law (for female/daughter-in-law) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | shee-ah-buh-jee; Kinship Terms p.104; [referring only] |
| 장인어른 | father-in-law (for male/son-in-law) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | jahng-een-uh-r_n; Kinship Terms p.104; [referring+addressing] |
| 손녀 | granddaughter | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | sohn-nyuh; Kinship Terms p.104; [referring only] |
| 손자 | grandson | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | sohn-jah; Kinship Terms p.104; [referring only] |
| 할아버지 | grandfather | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | hah-rah-buh-jee; Kinship Terms p.104; [referring+addressing] |
| 할머니 | grandmother | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | hahl-muh-nee; Kinship Terms p.104; [referring+addressing] |
| 남편 | husband | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | nahm-pyuhn; Kinship Terms p.105; [referring only] |
| 엄마 | mom | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | uhm-mah; Kinship Terms p.105; [referring+addressing] |
| 어머니 | mother | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | uh-muh-nee; Kinship Terms p.105; [referring+addressing]; general term for "mother," also usable (with honorific 어머님) to address a mother-in-law |
| 시어머니 | mother-in-law (for female/daughter-in-law) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | shee-uh-muh-nee; Kinship Terms p.105; [referring only] |
| 장모님 | mother-in-law (for male/son-in-law) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | jahng-moh-neem; Kinship Terms p.105; [referring+addressing] |
| 조카 | nephew | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | joh-kah; Kinship Terms p.105; [referring only]; footnote: also often used ungendered for nieces |
| 조카(딸) | niece | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | joh-kah(-ddahl); Kinship Terms p.105; [referring only] |
| 친척 | relatives | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | cheen-chuhk; Kinship Terms p.105; [referring only] |
| 형제(자매) | siblings | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | hyuhng-jeh(-jah-meh); Kinship Terms p.105; [referring only] |
| 자매 | sisters | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | jah-meh; Kinship Terms p.105; [referring only]; used exclusively for all-female siblings per footnote |
| 언니 | older sister (for female speaker) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | uhn-nee; Kinship Terms p.105; [referring+addressing] |
| 누나 | older sister (for male speaker) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | noo-nah; Kinship Terms p.105; [referring+addressing] |
| 여동생 | younger sister | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | yuh-dohng-sehng; Kinship Terms p.105; [referring only] |
| 아들 | son | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | ah-d_l; Kinship Terms p.105; [referring only] |
| 사위 | son-in-law | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | sah-wee; Kinship Terms p.105; [referring only] |
| 삼촌 | uncle (parent's brother) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | sahm-chohn; Kinship Terms p.105; [referring+addressing] |
| 이모부 | uncle (husband of mother's sister) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | ee-moh-boo; Kinship Terms p.105; [referring+addressing] |
| 고모부 | uncle (husband of father's sister) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | goh-moh-boo; Kinship Terms p.105; [referring+addressing] |
| 아내; 와이프 | wife (one's own) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | ah-neh; wah-ee-p_; Kinship Terms p.106; [referring only]; 와이프 is an English loanword also used informally for others' wives per footnote |
| 와이프 | wife (other's) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | wah-ee-p_; Kinship Terms p.106; [referring only] |
| 부인 | wife (other's, honorific) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | boo-een; Kinship Terms p.106; [referring+addressing] |
| 안녕하셨어요? | How have you been? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ahn-nyuhng-hah-shyut-suh-yo?; Celebration & Commemoration > Expressions, p.109 |
| 안녕하세요? | How are you? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ahn-nyuhng-hah-seh-yo?; Celebration & Commemoration > Expressions, p.109 |
| 어서 오세요. | Welcome. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | uh-suh oh-seh-yo.; Celebration & Commemoration > Expressions, p.109 |
| 축하드립니다 / 축하합니다 | Congratulations. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | choo-kah-d_-reem-nee-dah (humble); choo-kah-hahm-nee-dah.; Celebration & Commemoration > Expressions, p.109 |
| 조그만 선물입니다. | It's a small gift. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | joh-g_-mahn suhn-moo-reem-nee-dah.; Celebration & Commemoration > Expressions, p.109 |
| 잘 먹겠습니다. | I will treat myself to the food. (Lit. "I will eat well.") | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | jahl muhk-geht-s_m-nee-dah.; Celebration & Commemoration > Expressions, p.109; ritual expression of gratitude to the host who prepared the food |
| 너무 맛있습니다. | It's so delicious. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | nuh-moo mah-sheet-s_m-nee-dah.; Celebration & Commemoration > Expressions, p.109 |
| 잘 먹었습니다. | I had a great meal. (Lit. "I ate well.") | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | jahl-muh-guht-s_m-nee-dah.; Celebration & Commemoration > Expressions, p.109; same ritual gratitude expression as above, past tense |
| 고맙습니다; 감사합니다 | Thank you. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | goh-mahp-s_m-nee-dah; gahm-sah-hahm-nee-dah.; Celebration & Commemoration > Expressions, p.109 |
| 이제 가야겠네요. | I should get going now. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ee-jeh gah-yah-gehn-neh-yo.; Celebration & Commemoration > Expressions, p.109-110 |
| 즐거웠습니다. | I had a good time. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | j_l-guh-wuht-s_m-nee-dah.; Celebration & Commemoration > Expressions, p.110 |
| 안녕히 계세요. | Good bye. (to the host/those staying) | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ahn-nyuhng-hee geh-seh-yo.; Celebration & Commemoration > Expressions, p.110 |
| 안녕히 가세요. | Good bye. (to the guest/those leaving) | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ahn-nyuhng-hee gah-seh-yo.; Celebration & Commemoration > Expressions, p.110 |
| 와 주셔서 고맙습니다. | Thank you for coming. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | wah joo-shyuh-suh goh-mahp-s_m-nee-dah.; Celebration & Commemoration > Expressions, p.110 |
| 초대해 주셔서 고맙습니다. | Thank you for your invitation. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | choh-deh-heh joo-shyuh-suh goh-mahp-s_m-nee-dah.; Celebration & Commemoration > Expressions, p.110 |
| 또 오세요. | Come again. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ddoh oh-seh-yo.; Celebration & Commemoration > Expressions, p.110 |
| 기념일 | anniversary | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gee-nyuh-meel; Celebration & Commemoration > Words, p.110 |
| 생일 | birthday | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | sehng-eel; Celebration & Commemoration > Words, p.110 |
| 약혼 | engagement | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | yah-kohn; Celebration & Commemoration > Words, p.110 |
| 약혼식 | engagement ceremony | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | yah-kohn-sheek; Celebration & Commemoration > Words, p.110 |
| 잔치 | feast (Korean style) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | jahn-chee; Celebration & Commemoration > Words, p.110; productive suffix appended to birth/age-milestone terms (see grammar note 5 above) |
| 장례식 | funeral | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | jahng-leh-sheek; Celebration & Commemoration > Words, p.110 |
| 선물 | gift | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | suhn-mool; Celebration & Commemoration > Words, p.110 |
| 선물 포장 | gift wrapping | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | suhn-mool poh-jahng; Celebration & Commemoration > Words, p.110 |
| 졸업 | graduation | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | joh-ruhp; Celebration & Commemoration > Words, p.110 |
| 졸업식 | graduation ceremony | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | joh-ruhp-sheek; Celebration & Commemoration > Words, p.110 |
| 손님; 하객 | guest | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | sohn-neem; hah-gehk; Celebration & Commemoration > Words, p.110 |
| 집들이 | housewarming party | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | jeep-d_-ree; Celebration & Commemoration > Words, p.111 |
| 초대 | invitation | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | choh-deh; Celebration & Commemoration > Words, p.111 |
| 초대장 | invitation card | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | choh-deht-jahng; Celebration & Commemoration > Words, p.111 |
| 파티 | party (Western style) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | pah-tee; Celebration & Commemoration > Words, p.111 |
| 피로연; 리셉션 | reception | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | pee-roh-yuhn; reet-sehp-shyuhn; Celebration & Commemoration > Words, p.111 |
| 방문 | visit | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | bahng-moon; Celebration & Commemoration > Words, p.111 |
| 결혼 | wedding; marriage | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gyuh-rohn; Celebration & Commemoration > Words, p.111 |
| 결혼식 | wedding ceremony | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gyuh-rohn-sheek; Celebration & Commemoration > Words, p.111 |
| 백일 | the 100th day from birth | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | beh-geel; Celebration & Commemoration > Words, p.111; traditional birth milestone |
| (첫)돌 | the 1st birthday | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | (chuht-)dohl; Celebration & Commemoration > Words, p.111; traditional birth milestone |
| 환갑 | the 60th birthday | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | hwahn-gahp; Celebration & Commemoration > Words, p.111; traditional age milestone |
| 칠순 | the 70th birthday | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | cheel-soon; Celebration & Commemoration > Words, p.111; traditional age milestone |
| 팔순 | the 80th birthday | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | pahl-soon; Celebration & Commemoration > Words, p.111; traditional age milestone |
| 보여요. | I see it. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | boh-yuh-yo. (statement); Senses & Emotions > Senses, p.115 |
| 보여요? | Do you see it? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | boh-yuh-yo? (question, casual); Senses & Emotions > Senses, p.115 |
| 보이세요? | Do you see it? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | boh-ee-seh-yo? (question, honorific); Senses & Emotions > Senses, p.115 |
| 들려요. | I hear it. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | d_l-lyuh-yo. (statement); Senses & Emotions > Senses, p.115 |
| 들려요? | Do you hear it? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | d_l-lyuh-yo? (question, casual); Senses & Emotions > Senses, p.115 |
| 들리세요? | Do you hear it? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | d_l-lee-seh-yo? (question, honorific); Senses & Emotions > Senses, p.115 |
| 냄새 나요. | I smell it. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | nehm-seh-nah-yo. (statement); Senses & Emotions > Senses, p.115 |
| 냄새 나요? | Do you smell it? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | nehm-seh-nah-yo? (question, casual); Senses & Emotions > Senses, p.115 |
| 냄새 나세요? | Do you smell it? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | nehm-seh-nah-seh-yo? (question, honorific); Senses & Emotions > Senses, p.115 |
| 느껴져요. | I feel it. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | n_t-gyuh-juh-yo. (statement); Senses & Emotions > Senses, p.115 |
| 느껴져요? | Do you feel it? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | n_t-gyuh-juh-yo? (question, casual); Senses & Emotions > Senses, p.115 |
| 느껴지세요? | Do you feel it? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | n_t-gyuh-jee-seh-yo? (question, honorific); Senses & Emotions > Senses, p.115 |
| 아파요. | It hurts. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ah-pah-yo. (statement); Senses & Emotions > Senses, p.115 |
| 아파요? | Does it hurt? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ah-pah-yo? (question, casual); Senses & Emotions > Senses, p.115 |
| 아프세요? | Does it hurt? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ah-p_-seh-yo? (question, honorific); Senses & Emotions > Senses, p.115 |
| 배고파요. | I am hungry. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | beh-goh-pah-yo. (statement); Senses & Emotions > Senses, p.115 |
| 배고파요? | Are you hungry? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | beh-goh-pah-yo? (question, casual); Senses & Emotions > Senses, p.115 |
| 배고프세요? | Are you hungry? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | beh-goh-p_-seh-yo? (question, honorific); Senses & Emotions > Senses, p.115 |
| 목말라요. | I am thirsty. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | mohng-mahl-lah-yo. (statement); Senses & Emotions > Senses, p.116 |
| 목말라요? | Are you thirsty? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | mohng-mahl-lah-yo? (question, casual); Senses & Emotions > Senses, p.116 |
| 목마르세요? | Are you thirsty? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | mohng-mah-r_-seh-yo? (question, honorific); Senses & Emotions > Senses, p.116 |
| 졸려요. | I am sleepy. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | johl-lyuh-yo. (statement); Senses & Emotions > Senses, p.116 |
| 졸려요? | Are you sleepy? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | johl-lyuh-yo? (question, casual); Senses & Emotions > Senses, p.116 |
| 졸리세요? | Are you sleepy? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | johl-lee-seh-yo? (question, honorific); Senses & Emotions > Senses, p.116 |
| 더워요. | I feel hot. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | duh-wuh-yo. (statement); Senses & Emotions > Senses, p.116 |
| 더워요? | Do you feel hot? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | duh-wuh-yo? (question, casual); Senses & Emotions > Senses, p.116 |
| 더우세요? | Do you feel hot? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | duh-oo-seh-yo? (question, honorific); Senses & Emotions > Senses, p.116 |
| 추워요. | I feel cold. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | choo-wuh-yo. (statement); Senses & Emotions > Senses, p.116 |
| 추워요? | Do you feel cold? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | choo-wuh-yo? (question, casual); Senses & Emotions > Senses, p.116 |
| 추우세요? | Do you feel cold? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | choo-oo-seh-yo? (question, honorific); Senses & Emotions > Senses, p.116 |
| 따뜻해요. | I feel warm. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ddaht-d_t-teh-yo. (statement); Senses & Emotions > Senses, p.116 |
| 따뜻해요? | Do you feel warm? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ddaht-d_t-teh-yo? (question, casual); Senses & Emotions > Senses, p.116 |
| 따뜻하세요? | Do you feel warm? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ddaht-d_t-tah-seh-yo? (question, honorific); Senses & Emotions > Senses, p.116 |
| 기분이 안 좋아요. | I don't feel good. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gee-boo-nee ahn-joh-ah-yo. (statement); Senses & Emotions > Emotions, p.116 |
| 기분이 안 좋아요? | Do you not feel good? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gee-boo-nee ahn-joh-ah-yo? (question, casual); Senses & Emotions > Emotions, p.116 |
| 기분이 안 좋으세요? | Do you not feel good? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gee-boo-nee ahn-joh-_-seh-yo? (question, honorific); Senses & Emotions > Emotions, p.116 |
| 기분이 좋네요! | I am in a good mood! | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gee-boo-nee john-neh-yo! (statement); Senses & Emotions > Emotions, p.116 |
| 기분이 좋네요! | You are in a good mood! | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gee-boo-nee john-neh-yo! (2nd person, casual); Senses & Emotions > Emotions, p.116 |
| 기분이 좋으시네요! | You are in a good mood! | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gee-boo-nee joh-_-shee-neh-yo! (2nd person, honorific); Senses & Emotions > Emotions, p.116 |
| 기뻐요. | I feel joyous/pleased. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | geep-buh-yo. (statement); Senses & Emotions > Emotions, p.117 |
| 기뻐요? | Are you joyous/pleased? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | geep-buh-yo? (question, casual); Senses & Emotions > Emotions, p.117 |
| 기쁘세요? | Are you joyous/pleased? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | geep-b_-seh-yo? (question, honorific); Senses & Emotions > Emotions, p.117 |
| 행복해요. | I am happy. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | hehng-boh-keh-yo. (statement); Senses & Emotions > Emotions, p.117 |
| 행복해요? | Are you happy? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | hehng-boh-keh-yo? (question, casual); Senses & Emotions > Emotions, p.117 |
| 행복하세요? | Are you happy? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | hehng-boh-kah-seh-yo? (question, honorific); Senses & Emotions > Emotions, p.117 |
| 슬퍼요. | I am sad. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | s_l-puh-yo. (statement); Senses & Emotions > Emotions, p.117 |
| 슬퍼요? | Are you sad? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | s_l-puh-yo? (question, casual); Senses & Emotions > Emotions, p.117 |
| 슬프세요? | Are you sad? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | s_l-p_-seh-yo? (question, honorific); Senses & Emotions > Emotions, p.117 |
| 무서워요. | I am scared. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | moo-suh-wuh-yo. (statement); Senses & Emotions > Emotions, p.117 |
| 무서워요? | Are you scared? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | moo-suh-wuh-yo? (question, casual); Senses & Emotions > Emotions, p.117 |
| 무서우세요? | Are you scared? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | moo-suh-oo-seh-yo? (question, honorific); Senses & Emotions > Emotions, p.117 |
| 화났어요. | I am angry. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | hwah-naht-suh-yo. (statement); Senses & Emotions > Emotions, p.117 |
| 화났어요? | Are you angry? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | hwah-naht-suh-yo? (question, casual); Senses & Emotions > Emotions, p.117 |
| 화나셨어요? | Are you angry? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | hwah-nah-shyut-suh-yo? (question, honorific); Senses & Emotions > Emotions, p.117 |
| 질투나요. | I am jealous. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | jeel-too-nah-yo. (statement); Senses & Emotions > Emotions, p.117 |
| 질투나요? | Are you jealous? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | jeel-too-nah-yo? (question, casual); Senses & Emotions > Emotions, p.117 |
| 질투나세요? | Are you jealous? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | jeel-too-nah-seh-yo? (question, honorific); Senses & Emotions > Emotions, p.117 |
| (thing/person) 싫어요. | I don't like (thing/person). | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | shee-ruh-yo. (statement); Senses & Emotions > Emotions, p.117 |
| (thing/person) 싫어요? | Do you not like (thing/person)? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | shee-ruh-yo? (question, casual); Senses & Emotions > Emotions, p.117 |
| (thing/person) 싫으세요? | Do you not like (thing/person)? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | shee-r_-seh-yo? (question, honorific); Senses & Emotions > Emotions, p.117 |
| 고통 | agony | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | goh-tohng; Senses & Emotions > Words, p.118 |
| 화 | anger | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | hwah; Senses & Emotions > Words, p.118 |
| 행복 | happiness | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | hehng-bohk; Senses & Emotions > Words, p.118 |
| 미움 | hatred | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | mee-oom; Senses & Emotions > Words, p.118 |
| 질투 | jealousy | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | jeel-too; Senses & Emotions > Words, p.118 |
| 기쁨 | joy | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | geep-boom; Senses & Emotions > Words, p.118; contrasted with 쾌락 (see next row) |
| 사랑 | love | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | sah-rahng; Senses & Emotions > Words, p.118 |
| 아픔 | pain | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ah-p_m; Senses & Emotions > Words, p.118 |
| 쾌락 | pleasure | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | kweh-rahk; Senses & Emotions > Words, p.118; footnoted as having a somewhat negative connotation unlike 기쁨, cf. 쾌락주의 "hedonism" |
| 분노 | rage | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | boon-noh; Senses & Emotions > Words, p.118 |
| 만족 | satisfaction | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | mahn-johk; Senses & Emotions > Words, p.118 |
| 슬픔 | sorrow | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | s_l-p_m; Senses & Emotions > Words, p.118 |
| 불행 | unhappiness | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | boo-reng; Senses & Emotions > Words, p.118 |
| 쾌락주의 | hedonism | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | kweh-rahk-joo-_ee; Senses & Emotions > Words footnote, p.118 |
| (name)에 알레르기 있어요. | I am allergic to (name). | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | (name)eh ahl-leh-r_-gee eet-suh-yo.; Health Matters > Expressions, p.121; Korean form usable for 3rd person too, see grammar note 2 |
| 메스꺼워요. | I feel nauseous. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | meh-s_t-guh-wuh-yo.; Health Matters > Expressions, p.121 |
| 아주 피곤해요; 아주 피로해요. | I feel very tired. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ah-joo pee-gohn-heh-yo; ah-joo pee-roh-heh-yo.; Health Matters > Expressions, p.121 |
| 쓰러졌어요. | I collapsed. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ss_-ruh-jyuht-suh-yo.; Health Matters > Expressions, p.121 |
| 다쳤어요. | I got hurt. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | dah-chyuht-suh-yo.; Health Matters > Expressions, p.121 |
| 머리 아파요. | I have a headache. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | muh-ree-ah-pah-yo.; Health Matters > Expressions, p.121 |
| 배 아파요. | I have a stomachache. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | beh-ah-pah-yo.; Health Matters > Expressions, p.121 |
| 열 나요. | I have a fever. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | yuhl-lah-yo.; Health Matters > Expressions, p.121 |
| 열이 높아요. | I have a high fever. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | yuh-ree noh-pah-yo.; Health Matters > Expressions, p.121 |
| 콧물이 나요. | I have a runny nose. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | kohn-moo-ree nah-yo.; Health Matters > Expressions, p.121 |
| 감기 들었어요; 감기 걸렸어요. | I have a cold. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gahm-gee d_-ruht-suh-yo; gahm-gee guhl-lyuht-suh-yo.; Health Matters > Expressions, p.121 |
| (body part) 아파요. | I have pain in (body part); (body part) hurts. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | (body part) ah-pah-yo.; Health Matters > Expressions, p.121 |
| 토했어요. | I vomited. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | toh-heht-suh-yo.; Health Matters > Expressions, p.122 |
| (a name)에 걸렸어요. | I have (a name of disease). | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | (a name)eh guhl-lyuht-suh-yo.; Health Matters > Expressions, p.122 |
| 괜찮아요. | I am okay. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gwehn-chah-nah-yo.; Health Matters > Expressions, p.122 |
| 좀 나았어요. | I feel a little better. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | johm nah-aht-suh-yo.; Health Matters > Expressions, p.122 |
| 복부 | abdomen | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | bohk-boo; Health Matters > Body Parts, p.122 |
| 팔 | arm | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | pahl; Health Matters > Body Parts, p.122 |
| 등 | back | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | d_ng; Health Matters > Body Parts, p.122; footnoted as the part below the neck and above the waistline, distinct from 허리 "waist" |
| 가슴 | bosom; chest | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gah-s_m; Health Matters > Body Parts, p.122 |
| 귀 | ears | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gwee; Health Matters > Body Parts, p.122 |
| 눈 | eyes | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | noon; Health Matters > Body Parts, p.122 |
| 눈썹 | eyebrows | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | noon-ssuhp; Health Matters > Body Parts, p.122 |
| 속눈썹 | eyelashes | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | sohng-noon-ssuhp; Health Matters > Body Parts, p.122 |
| 발 | feet | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | bahl; Health Matters > Body Parts, p.122 |
| 손가락 | fingers | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | sohn-ggah-rahk; Health Matters > Body Parts, p.122 |
| 손톱 | fingernails | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | sohn-tohp; Health Matters > Body Parts, p.122 |
| 잇몸 | gum | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | een-mohm; Health Matters > Body Parts, p.122 |
| 손 | hands | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | sohn; Health Matters > Body Parts, p.122 |
| 히프 | hips | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | hee-p_; Health Matters > Body Parts, p.122 |
| 다리 | leg | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | dah-ree; Health Matters > Body Parts, p.122 |
| 입술 | lips | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | eep-sool; Health Matters > Body Parts, p.122 |
| 입 | mouth | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | eep; Health Matters > Body Parts, p.122 |
| 목 | neck | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | mohk; Health Matters > Body Parts, p.122 |
| 코 | nose | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | koh; Health Matters > Body Parts, p.122 |
| 어깨 | shoulders | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | uhk-geh; Health Matters > Body Parts, p.122 |
| 허벅지 | thigh | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | huh-buhk-jee; Health Matters > Body Parts, p.123 |
| 발가락 | toes | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | bahl-ggah-rahk; Health Matters > Body Parts, p.123 |
| 발톱 | toenails | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | bahl-tohp; Health Matters > Body Parts, p.123 |
| 혀 | tongue | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | hyuh; Health Matters > Body Parts, p.123 |
| 이 | tooth | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ee; Health Matters > Body Parts, p.123 |
| 허리 | waist | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | huh-ree; Health Matters > Body Parts, p.123 |
| 동맥 | artery | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | dohng-mehk; Health Matters > Anatomy, p.123 |
| 피; 혈액 | blood | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | pee; hyuh-rehk; Health Matters > Anatomy, p.123 |
| 혈액형 | blood type | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | hyuh-rehk-kyuhng; Health Matters > Anatomy, p.123 |
| 혈관; 핏줄 | blood vessel | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | hyuhl-gwahn; peet-jool; Health Matters > Anatomy, p.123 |
| 뼈 | bone | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | bbyuh; Health Matters > Anatomy, p.123 |
| 뇌 | brain | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | nweh; Health Matters > Anatomy, p.123 |
| 식도 | esophagus | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | sheek-doh; Health Matters > Anatomy, p.123 |
| 심장 | heart | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | sheem-jahng; Health Matters > Anatomy, p.123 |
| 신장; 콩팥 | kidney | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | sheen-jahng; kohng-paht; Health Matters > Anatomy, p.123 |
| 인대 | ligament | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | een-deh; Health Matters > Anatomy, p.123 |
| 간 | liver | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gahn; Health Matters > Anatomy, p.123 |
| 폐 | lung | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | pyeh; Health Matters > Anatomy, p.123 |
| 근육 | muscle | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | g_-nyook; Health Matters > Anatomy, p.123 |
| 신경 | nerve | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | sheen-gyuhng; Health Matters > Anatomy, p.123 |
| 피부 | skin | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | pee-boo; Health Matters > Anatomy, p.123 |
| 척추 | spine; vertebrae | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | chuhk-choo; Health Matters > Anatomy, p.123 |
| 위 | stomach | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | wee; Health Matters > Anatomy, p.123 |
| 기관 | trachea | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gee-gwahn; Health Matters > Anatomy, p.123 |
| 정맥 | vein | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | juhng-mehk; Health Matters > Anatomy, p.123 |
| 앰뷸런스 | ambulance | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ehm-byool-luhn-s_; Health Matters > Regarding Medical Care, p.124 |
| 항생제 | antibiotics | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | hahng-sehng-jeh; Health Matters > Regarding Medical Care, p.124 |
| 한약 | Chinese medicine | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | hah-nyahk; Health Matters > Regarding Medical Care, p.124 |
| 종합병원 | 'comprehensive hospital' | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | johng-hahp-byuhng-wuhn; Health Matters > Regarding Medical Care, p.124; see grammar note 3a |
| 치유; 치료 | cure | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | chee-yoo; chee-ryo; Health Matters > Regarding Medical Care, p.124 |
| 퇴원 | discharge from the hospital | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | tweh-wuhn; Health Matters > Regarding Medical Care, p.124 |
| 의사 | doctor | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | _ee-sah; Health Matters > Regarding Medical Care, p.124; appended to a field name to name that field's doctor, see grammar note 3b |
| 호스피스 | hospice | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | hoh-s_-pee-s_; Health Matters > Regarding Medical Care, p.124 |
| 병원 | hospital | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | byuhng-wuhn; Health Matters > Regarding Medical Care, p.124; see grammar note 3a |
| 입원 | hospitalization | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ee-bwuhn; Health Matters > Regarding Medical Care, p.124 |
| 면역접종 | immunization shots | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | myuh-nyuhk-juhp-johng; Health Matters > Regarding Medical Care, p.124 |
| 약 | medication | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | yahk; Health Matters > Regarding Medical Care, p.124 |
| 간호사 | nurse | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gahn-hoh-sah; Health Matters > Regarding Medical Care, p.124 |
| 수술 | operation | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | soo-sool; Health Matters > Regarding Medical Care, p.124 |
| 진통제 | pain relief medication | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | jeen-tohng-jeh; Health Matters > Regarding Medical Care, p.124 |
| 약사 | pharmacist | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | yahk-sah; Health Matters > Regarding Medical Care, p.124 |
| 약국 | pharmacy | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | yahk-gook; Health Matters > Regarding Medical Care, p.124 |
| 맥박 | pulse | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | mehk-bahk; Health Matters > Regarding Medical Care, p.124 |
| 주사 | shot | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | joo-sah; Health Matters > Regarding Medical Care, p.124 |
| 소독 | sterilization | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | soh-dohk; Health Matters > Regarding Medical Care, p.125 |
| 청진기 | stethoscope | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | chuhng-jeen-gee; Health Matters > Regarding Medical Care, p.125 |
| 체온 | temperature (body) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | cheh-ohn; Health Matters > Regarding Medical Care, p.125 |
| 치료 | treatment | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | chee-ryo; Health Matters > Regarding Medical Care, p.125 |
| 대학병원 | university hospital | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | deh-hahk-byuhng-wuhn; Health Matters > Regarding Medical Care, p.125; see grammar note 3a |
| 치과 | dentistry | noun | technical.medical | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | cheek-gwah; Health Matters > Fields of Medicine, p.125 |
| 피부과 | dermatology | noun | technical.medical | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | pee-book-gwah; Health Matters > Fields of Medicine, p.125 |
| 이비인후과 | ENT | noun | technical.medical | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ee-bee-een-hook-gwah; Health Matters > Fields of Medicine, p.125 |
| 내과 | internal medicine | noun | technical.medical | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | nehk-gwah; Health Matters > Fields of Medicine, p.125; worked example for the 의사 "doctor" suffix pattern |
| 신경과 | neurology | noun | technical.medical | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | sheen-gyuhng-ggwah; Health Matters > Fields of Medicine, p.125 |
| 산부인과 | ob-gyn | noun | technical.medical | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | sahn-boo-een-ggwah; Health Matters > Fields of Medicine, p.125 |
| 안과 | ophthalmology | noun | technical.medical | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ahn-ggwah; Health Matters > Fields of Medicine, p.125 |
| 정형외과 | orthopedics | noun | technical.medical | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | juhng-hyuhng-wehk-gwah; Health Matters > Fields of Medicine, p.125 |
| 이비인후과 | otolaryngology | noun | technical.medical | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ee-bee-een-hook-gwah; Health Matters > Fields of Medicine, p.125; same term as ENT above |
| 병리과 | pathology | noun | technical.medical | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | byuhng-neek-gwah; Health Matters > Fields of Medicine, p.125 |
| 소아과 | pediatrics | noun | technical.medical | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | soh-ahk-gwah; Health Matters > Fields of Medicine, p.125 |
| 성형외과 | plastic surgery | noun | technical.medical | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | suhng-hyuhng-wehk-gwah; Health Matters > Fields of Medicine, p.126 |
| 정신과; 신경정신과 | psychiatry | noun | technical.medical | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | juhng-sheen-ggwah; sheen-gyuhng-juhng-sheen-ggwah; Health Matters > Fields of Medicine, p.126 |
| 방사선과 | radiology | noun | technical.medical | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | bahng-sah-suhn-ggwah; Health Matters > Fields of Medicine, p.126 |
| 재활의학과 | rehabilitation | noun | technical.medical | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | jeh-hwahl-_ee-hahk-gwah; Health Matters > Fields of Medicine, p.126 |
| 외과 | surgery | noun | technical.medical | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | wehk-gwah; Health Matters > Fields of Medicine, p.126 |
| 비뇨기과 | urology | noun | technical.medical | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | bee-nyo-geek-gwah; Health Matters > Fields of Medicine, p.126 |
| 알레르기 | allergy | noun | technical.medical | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ahl-leh-r_-gee; Health Matters > Regarding Health Problems, p.126 |
| 치매 | Alzheimer's disease | noun | technical.medical | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | chee-meh; Health Matters > Regarding Health Problems, p.126 |
| 빈혈 | anemia | noun | technical.medical | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | been-hyuhl; Health Matters > Regarding Health Problems, p.126 |
| 양성 | benign | adjective | technical.medical | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | yahng-suhng; Health Matters > Regarding Health Problems, p.126 |
| 암 | cancer | noun | technical.medical | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ahm; Health Matters > Regarding Health Problems, p.126 |
| 감기 | cold | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gahm-gee; Health Matters > Regarding Health Problems, p.126 |
| 우울증 | depression | noun | technical.medical | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | oo-ool-j_ng; Health Matters > Regarding Health Problems, p.126 |
| 당뇨병 | diabetes | noun | technical.medical | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | dahng-nyo-bbyuhng; Health Matters > Regarding Health Problems, p.126 |
| 피로 | fatigue | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | pee-roh; Health Matters > Regarding Health Problems, p.126 |
| 독감 | flu | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | dohk-gahm; Health Matters > Regarding Health Problems, p.126 |
| 두통 | headache | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | doo-tohng; Health Matters > Regarding Health Problems, p.126 |
| 심장마비 | heart attack | noun | technical.medical | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | sheem-jahng-mah-bee; Health Matters > Regarding Health Problems, p.126 |
| 심장병 | heart disease | noun | technical.medical | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | sheem-jahng-bbyuhng; Health Matters > Regarding Health Problems, p.126 |
| 간염 | hepatitis | noun | technical.medical | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gah-nyuhm; Health Matters > Regarding Health Problems, p.126 |
| 고혈압 | high blood pressure | noun | technical.medical | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | goh-hyuh-rahp; Health Matters > Regarding Health Problems, p.126 |
| 소화불량 | indigestion | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | soh-hwah-bool-lyahng; Health Matters > Regarding Health Problems, p.127 |
| 감염 | infection | noun | technical.medical | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gah-myuhm; Health Matters > Regarding Health Problems, p.127 |
| 염증 | inflammation | noun | technical.medical | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | yuhm-jj_ng; Health Matters > Regarding Health Problems, p.127 |
| 불면증 | insomnia | noun | technical.medical | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | bool-myuhn-jj_ng; Health Matters > Regarding Health Problems, p.127 |
| 저혈압 | low blood pressure | noun | technical.medical | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | juh-hyuh-rahp; Health Matters > Regarding Health Problems, p.127 |
| 악성 | malignant | adjective | technical.medical | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | ahk-suhng; Health Matters > Regarding Health Problems, p.127 |
| 비만 | obesity | noun | technical.medical | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | bee-mahn; Health Matters > Regarding Health Problems, p.127 |
| 마비 | paralysis | noun | technical.medical | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | mah-bee; Health Matters > Regarding Health Problems, p.127 |
| 정신분열증 | schizophrenia | noun | technical.medical | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | juhng-sheen-boo-nyuhl-jj_ng; Health Matters > Regarding Health Problems, p.127 |
| 복통; 위통 | stomachache | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | bohk-tohng; wee-tohng; Health Matters > Regarding Health Problems, p.127 |
| 스트레스 | stress | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | s_-t_-reh-s_; Health Matters > Regarding Health Problems, p.127 |
| 증세 | symptoms | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | j_ng-seh; Health Matters > Regarding Health Problems, p.127 |
| 편도선염 | tonsillitis | noun | technical.medical | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | pyuhn-doh-suhn-nyuhm; Health Matters > Regarding Health Problems, p.127 |
| 몇 과목 들으세요? | How many courses are you taking? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | myuht-gwah-mohk d_-r_-seh-yo?; Education & Schools > Expressions, p.131 |
| 몇 학년이세요? | What grade are you in? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | myuht-hahng-nyuh-nee-seh-yo?; Education & Schools > Expressions, p.131 |
| 어느 학교 다니세요? | Which school do you attend? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | uh-n_-hahk-gyo dah-nee-seh-yo?; Education & Schools > Expressions, p.131 |
| 뭐 전공 하세요? | What do you major in? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | mwuh juhn-gohng-hah-seh-yo?; Education & Schools > Expressions, p.131 |
| 뭐 전공 하셨어요? | What did you major in? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | mwuh juhn-gohng-hah-shyuht-suh-yo?; Education & Schools > Expressions, p.131 |
| 졸업하고 뭐 하고 싶으세요? | What do you want to do after graduation? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | joh-ruhp-pah-goh mwuh hah-goh-shee-p_-seh-yo?; Education & Schools > Expressions, p.131 |
| 유아원 | nursery; preschool | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | yoo-ah-wuhn; Education & Schools > Schools: chronological, p.131 |
| 유치원 | kindergarten | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | yoo-chee-wuhn; Education & Schools > Schools: chronological, p.131 |
| 초등학교 | elementary school | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | choh-d_ng-hahk-gyo; Education & Schools > Schools: chronological, p.131 |
| 중학교 | junior high school | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | joong-hahk-gyo; Education & Schools > Schools: chronological, p.131 |
| 고등학교 | high school | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | goh-d_ng-hahk-gyo; Education & Schools > Schools: chronological, p.131 |
| 대학교 | college; university | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | deh-hahk-gyo; Education & Schools > Schools: chronological, p.131 |
| 대학원 | graduate school | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | deh-hah-gwuhn; Education & Schools > Schools: chronological, p.131 |
| 사립학교 | private school | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | sah-reep-hahk-gyo; Education & Schools > Schools: others, p.131 |
| 공립학교 | public school | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gohng-neep-hahk-gyo; Education & Schools > Schools: others, p.131 |
| 학위 | academic degrees | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | hah-gwee; Education & Schools > At School, p.132 |
| 학사 | Bachelor of Arts (B.A.) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | hahk-sah; Education & Schools > At School > academic degrees, p.132 |
| 석사 | Master of Arts (M.A.) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | suhk-sah; Education & Schools > At School > academic degrees, p.132 |
| 박사 | Doctor of Philosophy (Ph.D.) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | bahk-sah; Education & Schools > At School > academic degrees, p.132 |
| 학과 | academic department | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | hahk-gwah; Education & Schools > At School, p.132 |
| 성적 | academic performance | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | suhng-juhk; Education & Schools > At School, p.132 |
| 교감 | assistant principal | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gyo-gahm; Education & Schools > At School, p.132 |
| 책 | book | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | chehk; Education & Schools > At School, p.132 |
| 쉬는시간 | break | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | shwee-n_n-shee-gahn; Education & Schools > At School, p.132 |
| 의자 | chair (furniture) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | _ee-jah; Education & Schools > At School, p.132 |
| 수업 | class | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | soo-uhp; Education & Schools > At School, p.132 |
| 교실 | classroom | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gyo-sheel; Education & Schools > At School, p.132 |
| 과목 | courses | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gwah-mohk; Education & Schools > At School, p.132; footnoted to refer to Fields of Academics for more subjects |
| 미술 | art | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | mee-sool; Education & Schools > At School > courses, p.132 |
| 영어 | English | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | yuhng-uh; Education & Schools > At School > courses, p.132 |
| 국어 | Korean | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | goo-guh; Education & Schools > At School > courses, p.132; school-subject name, distinct from 한국어 "Korean language" — see grammar note 3c |
| 산수; 수학 | mathematics | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | sahn-soo; soo-hahk; Education & Schools > At School > courses, p.132; elementary vs. junior-high-and-beyond register split, see grammar note 3d |
| 과학 | science | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gwah-hahk; Education & Schools > At School > courses, p.132 |
| 사회 | social studies | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | sah-hweh; Education & Schools > At School > courses, p.132 |
| 학장 | dean | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | hahk-jahng; Education & Schools > At School, p.132 |
| 책상 | desk | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | chehk-sahng; Education & Schools > At School, p.132 |
| 시험 | exams | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | shee-huhm; Education & Schools > At School, p.132 |
| 기말고사 | finals | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gee-mahl-goh-sah; Education & Schools > At School, p.132 |
| 친구 | friends | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | cheen-goo; Education & Schools > At School, p.132 |
| 점수 | grade | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | juhm-soo; Education & Schools > At School, p.133 |
| 숙제 | homework | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | sook-jeh; Education & Schools > At School, p.133 |
| 양호실 | infirmary | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | yahng-hoh-sheel; Education & Schools > At School, p.133 |
| 도서관 | library | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | doh-suh-gwahn; Education & Schools > At School, p.133 |
| 중간고사 | midterm | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | joong-gahn-goh-sah; Education & Schools > At School, p.133 |
| 총장 | president (university) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | chohng-jahng; Education & Schools > At School, p.133 |
| 교장 | principal | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gyo-jahng; Education & Schools > At School, p.133 |
| 교수(님) | professor | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gyo-soo(-neem); Education & Schools > At School, p.133; -님 is a generic people-referring honorific suffix, see grammar note 4 |
| 성적표 | report card | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | suhng-juhk-pyo; Education & Schools > At School, p.133 |
| 장학금 | scholarship | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | jahng-hahk-g_m; Education & Schools > At School, p.133 |
| 학교 | school | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | hahk-gyo; Education & Schools > At School, p.133 |
| 교복 | school uniform | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gyo-bohk; Education & Schools > At School, p.133 |
| 학생 | student | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | hahk-sehng; Education & Schools > At School, p.133 |
| 공부 | study | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gohng-boo; Education & Schools > At School, p.133 |
| 유학 | study abroad | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | yoo-hahk; Education & Schools > At School, p.133 |
| 선생(님) | teacher | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | suhn-sehng(-neem); Education & Schools > At School, p.133; -님 honorific suffix, see grammar note 4 |
| 교과서 | textbook | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | gyo-gwah-suh; Education & Schools > At School, p.133 |
| 학비 | tuition | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | hahk-bee; Education & Schools > At School, p.133 |
| 방학 | vacation (school) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | bahng-hahk; Education & Schools > At School, p.133 |
| 비즈니스 스쿨; 경영대학원 | business school | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | bee-jee-nee-s_ s_-kool; gyuhng-yuhng-deh-hahk-gwuhn; Education & Schools > Professional Schools, p.133 |
| 법대 | law school | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | buhp-deh; Education & Schools > Professional Schools, p.133 |
| 의대 | medical school | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | plausible_unverified | _ee-deh; Education & Schools > Professional Schools, p.133 |
| 어디서 한국말 공부하셨어요? | Where did you study Korean? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `uh-dee-suh hahn-goong-mahl gohng-boo-hah-shyuht-suh-yo?`; Studying Korean, Expressions, p.136-137 |
| 얼마동안 한국말 공부하셨어요? | How long have you studied Korean? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `uhl-maht-dohng-ahn hahn-goong-mahl gohng-boo-hah-shyuht-suh-yo?`; Studying Korean, p.136-137 |
| 한국말 배우고 싶어요 | I want to learn Korean. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `hahn-goong-mahl beh-oo-goh-shee-puh-yo.`; Studying Korean, p.136-137 |
| 한국말 잘 하고 싶어요 | I want to speak Korean well. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `hahn-goong-mahl jahl hah-goh-shee-puh-yo.`; Studying Korean, p.136-137 |
| 제가 한국말 틀리면 고쳐 주세요 | Please correct me if I say things wrong in Korean. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `jeh-gah hahn-goong-mahl t_l-lee-myuhn goh-chuh-joo-seh-yo.`; Studying Korean, p.136-137 |
| 다시 한번 말씀해 주시겠어요? | Could you say it again? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `dah-shee-hahn-buhn mahl-ss_m-heh joo-shee-geht-suh-yo?`; Studying Korean, p.136-137 |
| 조금 천천히 말씀해 주시겠어요? | Could you say it a little slow? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `joh-g_m chuhn-chuh-nee mahl-ss_m-heh joo-shee-geht-suh-yo?`; Studying Korean, p.136-137 |
| 그게 무슨 뜻이에요? | What does that mean? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `g_-geh moo-s_n dd_-shee-eh-yo?`; Studying Korean, p.138-139 |
| (a word / an expression) 무슨 뜻이에요? | What does (a word / an expression) mean? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `(a word / an expression) moo-s_n dd_-shee-eh-yo?`; Studying Korean, p.138-139 |
| ~ 쉬워요 | ~ is easy. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `~ shwee-wuh-yo.`; Studying Korean, p.138-139 |
| ~ 어려워요 | ~ is difficult. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `~ uh-ryuh-wuh-yo.`; Studying Korean, p.138-139 |
| 은어 | argot | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `_-nuh`; Studying Korean, Words, p.138-139; metalinguistic register term |
| 사전 지식 | background knowledge | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `sah-juhn jee-sheek`; Studying Korean, p.138-139 |
| 책 | book | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `chehk`; Studying Korean, p.138-139 |
| 자음 | consonant | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `jah-_m`; Studying Korean, p.138-139 |
| 문화 | culture | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `moon-hwah`; Studying Korean, p.138-139 |
| 사투리 | dialect | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `sah-too-ree`; Studying Korean, p.138-139; listed twice (also under "expression/dialect" group) |
| 회화 | dialogue | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `hweh-hwah`; Studying Korean, p.138-139; footnote: usually refers to dialogues in the context of foreign-language learning |
| 사전 | dictionary | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `sah-juhn`; Studying Korean, p.138-139 |
| 영한사전 | English-Korean dictionary | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `yuhng-hahn-sah-juhn`; Studying Korean, p.138-139 |
| 한영사전 | Korean-English dictionary | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `hah-nyuhng-sah-juhn`; Studying Korean, p.138-139 |
| 표현 | expression | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `pyo-hyuhn`; Studying Korean, p.138-139 |
| 외국어 | foreign language | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `weh-goo-guh`; Studying Korean, p.138-139 |
| 문법 | grammar | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `moon-bbuhp`; Studying Korean, p.138-139 |
| 관용어 | idiom | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `gwah-nyong-uh`; Studying Korean, p.138-139 |
| 해석; 통역 | interpretation | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `heh-suhk; tohng-yuhk`; Studying Korean, p.138-139 |
| 한국어; 한국말 | Korean language | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `hahn-goo-guh; hahn-goong-mahl`; Studying Korean, p.138-139 |
| 한국어 공부; 한국말 공부 | Korean language study | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `hahn-goo-guh gohng-boo; hahn-goong-mahl gohng-boo`; Studying Korean, p.138-139 |
| 언어; 말 | language | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `uh-nuh; mahl`; Studying Korean, p.138-139 |
| 구어(체) | spoken language (style) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `goo-uh(-cheh)`; Studying Korean, p.138-139; metalinguistic register term |
| 문어(체) | written language (style) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `moo-nuh(-cheh)`; Studying Korean, p.138-139; metalinguistic register term |
| 연습 | practice | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `yuhn-s_p`; Studying Korean, p.138-139 |
| 학원 | private educational institution | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `hah-gwuhn`; Studying Korean, p.138-139 |
| 참고서(적) | reference book | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `chahm-goh-suh(-juhk)`; Studying Korean, p.138-139 |
| 문장 | sentence | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `moon-jahng`; Studying Korean, p.138-139 |
| 능력 | skills | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `n_ng-nyuhk`; Studying Korean, p.138-139 |
| 듣기 | listening (skill) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `d_t-gee`; Studying Korean, p.138-139 |
| 읽기 | reading (skill) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `eek-gee`; Studying Korean, p.138-139 |
| 말하기 | speaking (skill) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `mahl-hah-gee`; Studying Korean, p.138-139 |
| 쓰기 | writing (skill) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `ss_-gee`; Studying Korean, p.138-139 |
| 속어 | slang | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `soh-guh`; Studying Korean, p.138-139; metalinguistic register term — the book's own word for "slang" itself |
| 표준어 | standard language | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `pyo-joo-nuh`; Studying Korean, p.138-139; metalinguistic register term |
| 교과서 | textbook | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `gyo-gwah-suh`; Studying Korean, p.138-139 |
| 번역 | translation | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `buhn-yuhk`; Studying Korean, p.138-139 |
| 어휘 | vocabulary | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `uh-hwee`; Studying Korean, p.138-139 |
| 단어 | words | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `dah-nuh`; Studying Korean, p.140-141 |
| 형용사 | adjective | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `hyuhng-yong-sah`; Studying Korean, p.140-141; grammatical-terminology vocabulary |
| 부사 | adverb | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `boo-sah`; Studying Korean, p.140-141; grammatical-terminology vocabulary |
| 명사 | noun | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `myuhng-sah`; Studying Korean, p.140-141; grammatical-terminology vocabulary |
| 조사 | particle | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `joh-sah`; Studying Korean, p.140-141; grammatical-terminology vocabulary |
| 동사 | verb | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `dohng-sah`; Studying Korean, p.140-141; grammatical-terminology vocabulary |
| 어디에서 일하세요? | Where do you work? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `uh-dee-eh-suh eel-hah-seh-yo?`; Work & Professions, Expressions, p.142-143 |
| 어떤 일 하세요? | What kind of work do you do?; What line of work are you in? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `uht-duhn-eel hah-seh-yo?`; Work & Professions, p.142-143 |
| 대학에서 뭐 전공하셨어요? | What did you major in at college? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `deh-hah-geh-suh mwuh juhn-gohng-hah-shyut-suh-yo?`; Work & Professions, p.142-143 |
| 회계사 | accountant | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `hweh-geh-sah`; Work & Professions, Professions, p.142-143 |
| 배우 | actor | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `beh-oo`; Work & Professions, p.142-143 |
| 건축가 | architect | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `guhn-chook-gah`; Work & Professions, p.142-143 |
| 예술가 | artist | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `yeh-sool-gah`; Work & Professions, p.142-143 |
| 은행원 | banker | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `_n-hehng-wuhn`; Work & Professions, p.142-143; footnote: refers specifically to bank employees, not investment bankers |
| 목수 | carpenter | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `mohk-soo`; Work & Professions, p.142-143 |
| 조리사 | chef | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `joh-ree-sah`; Work & Professions, p.142-143 |
| 한의사 | Chinese medicine doctor | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `hahn-_ee-sah`; Work & Professions, p.142-143 |
| 회사원 | company employee | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `hweh-sah-wuhn`; Work & Professions, p.142-143; also listed again p.144-145 as "employee of a company" |
| 컴퓨터 프로그래머 | computer programmer | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `kuhm-pyoo-tuh p_-roh-g_-reh-muh`; Work & Professions, p.142-143 |
| 치과의사 | dentist | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `cheek-gwah-_ee-sah`; Work & Professions, p.142-143 |
| 디자이너 | designer | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `dee-jah-ee-nuh`; Work & Professions, p.142-143 |
| 의사 | doctor | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `_ee-sah`; Work & Professions, p.144-145 |
| 연예인 | entertainers | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `yuh-neh-een`; Work & Professions, p.144-145 |
| 사업가 | entrepreneur | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `sah-uhp-gah`; Work & Professions, p.144-145 |
| 소방관 | firefighter | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `soh-bahng-gwahn`; Work & Professions, p.144-145 |
| 프리랜서 | freelancer | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `p_-ree-rehn-suh`; Work & Professions, p.144-145 |
| 공무원 | government employee | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `gohng-moo-wuhn`; Work & Professions, p.144-145 |
| 그래픽 디자이너 | graphic designer | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `g_-reh-peek dee-jah-ee-nuh`; Work & Professions, p.144-145 |
| 발명가 | inventor | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `bahl-myuhng-gah`; Work & Professions, p.144-145 |
| 변호사 | lawyer | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `byuhn-hoh-sah`; Work & Professions, p.144-145 |
| 강사 | lecturer; instructor | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `gahng-sah`; Work & Professions, p.144-145 |
| 영화감독 | movie director | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `yuhng-hwah-gahm-dohk`; Work & Professions, p.144-145 |
| 영화배우 | movie star | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `yuhng-hwah-beh-oo`; Work & Professions, p.144-145 |
| 음악가 | musician | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `_-mahk-gah`; Work & Professions, p.144-145 |
| 간호사 | nurse | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `gahn-hoh-sah`; Work & Professions, p.144-145 |
| 화가 | painter | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `hwah-gah`; Work & Professions, p.144-145 |
| 목사(님) | pastor | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `mohk-sah(-neem)`; Work & Professions, p.144-145 |
| 변리사 | patent law specialist | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `byuhl-lee-sah`; Work & Professions, p.144-145; footnote: distinct legal profession/exam from the general bar exam, handles patent-law matters |
| 사진작가 | photographer | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `sah-jeen-jahk-gah`; Work & Professions, p.144-145 |
| 경찰(관) | police | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `gyuhng-chahl-gwahn`; Work & Professions, p.144-145 |
| 정치가 | politician | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `juhng-chee-gah`; Work & Professions, p.144-145 |
| 신부(님) | priest | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `sheen-boo(-neem)`; Work & Professions, p.144-145 |
| 직업 | profession | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `jee-guhp`; Work & Professions, p.144-145 |
| 교수 | professor | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `gyo-soo`; Work & Professions, p.144-145 |
| 공인 중개사 | real estate agent | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `gohng-een-joong-geh-sah`; Work & Professions, p.144-145 |
| 학자 | scholar | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `hahk-jah`; Work & Professions, p.144-145 |
| 비서 | secretary | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `bee-suh`; Work & Professions, p.144-145 |
| 가수 | singer | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `gah-soo`; Work & Professions, p.144-145 |
| 군인 | soldier | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `goo-neen`; Work & Professions, p.144-145 |
| 텔런트 | TV star | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `tehl-luhn-t_`; Work & Professions, p.144-145 |
| 선생(님); 교사 | teacher | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `suhn-sehng(-neem); gyo-sah`; Work & Professions, p.144-145 |
| 작가 | writer | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `jahk-gah`; Work & Professions, p.144-145 |
| 광고업 | advertising industry | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `gwahng-goh-uhp`; Work & Professions, Fields of Industry, p.144-145 |
| 농업 | agriculture industry | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `nohng-uhp`; Work & Professions, p.144-145 |
| 건설업 | construction industry | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `guhn-suh-ruhp`; Work & Professions, p.144-145 |
| 요식업 | culinary industry | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `yo-shee-guhp`; Work & Professions, p.144-145 |
| 유통업 | distribution industry | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `yoo-tohng-uhp`; Work & Professions, p.144-145 |
| 금융업 | finance industry | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `g_m-yoong-uhp`; Work & Professions, p.144-145 |
| 수산업 | fishing industry | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `soo-sah-nuhp`; Work & Professions, p.144-145 |
| 제조업 | manufacturing industry | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `jeh-joh-uhp`; Work & Professions, p.144-145 |
| 연봉 | annual salary | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `yuhn-bohng`; Work & Professions, At Work, p.144-146 |
| 상사 | boss | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `sahng-sah`; Work & Professions, p.144-146 |
| 출장 | business trip | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `chool-jjahng`; Work & Professions, p.144-146 |
| 커리어; 경력 | career | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `kuh-ree-uh; gyuhng-nyuhk`; Work & Professions, p.144-146 |
| 동료 | colleague | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `dohng-nyo`; Work & Professions, p.144-146 |
| 회사 | company | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `hweh-sah`; Work & Professions, p.144-146 |
| 복리후생제도 | fringe benefits system | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `bong-nee-hoo-sehng-jeh-doh`; Work & Professions, p.146-147 |
| 퇴근 | getting off from work | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `tweh-g_n`; Work & Professions, p.146-147 |
| 출근 | going to work | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `chool-g_n`; Work & Professions, p.146-147 |
| 보험 | insurance | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `boh-huhm`; Work & Professions, p.146-147 |
| 면접 | interview | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `myuhn-juhp`; Work & Professions, p.146-147 |
| 회의; 미팅 | meeting | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `hweh-ee; mee-teeng`; Work & Professions, p.146-147 |
| 월급 | monthly salary | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `wuhl-g_p`; Work & Professions, p.146-147 |
| 사무실 | office | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `sah-moo-sheel`; Work & Professions, p.146-147 |
| 주인 | owner | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `joo-een`; Work & Professions, p.146-147 |
| 연금 | pension | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `yuhn-g_m`; Work & Professions, p.146-147 |
| 사장 | president (of a company) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `sah-jahng`; Work & Professions, p.146-147; also listed under Organizational Titles, p.148-149 |
| 승진; 진급 | promotion | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `s_ng-jeen; jeen-g_p`; Work & Professions, p.146-147 |
| 사표; 퇴직서 | resignation letter | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `sah-pyo; tweh-jeek-suh`; Work & Professions, p.146-147 |
| 이력서 | résumé | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `ee-ryuhk-suh`; Work & Professions, p.146-147 |
| 퇴직 | retirement | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `tweh-jeek`; Work & Professions, p.146-147 |
| 팀워크 | teamwork | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `teem-wuh-k_`; Work & Professions, p.146-147 |
| 휴가 | vacation (at work) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `hyoo-gah`; Work & Professions, p.146-147 |
| 직장 | work place | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `jeek-jahng`; Work & Professions, p.146-147 |
| 주급 | weekly wage | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `joo-g_p`; Work & Professions, p.146-147 |
| 회계(과/부) | accounting (dept.) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `hweh-geh`; Work & Professions, Departments, p.146-147; book notes -과/-부 suffix can be appended to any department term |
| 총무(과/부) | administration (dept.) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `chohng-moo`; Work & Professions, p.146-147 |
| 광고(과/부) | advertising (dept.) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `gwahng-goh`; Work & Professions, p.146-147 |
| 재무(과/부) | finance (dept.) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `jeh-moo`; Work & Professions, p.146-147 |
| 인사(과/부) | human resources (dept.) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `een-sah`; Work & Professions, p.146-147 |
| 마케팅(과/부) | marketing (dept.) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `mah-keh-teeng`; Work & Professions, p.146-147 |
| 업무(과/부) | operations (dept.) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `uhm-moo`; Work & Professions, p.146-147 |
| 기획(과/부) | planning (dept.) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `gee-hwehk`; Work & Professions, p.146-147 |
| 생산관리(과/부) | production management (dept.) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `sehng-sahn-gwahl-lee`; Work & Professions, p.146-147 |
| 홍보(과/부) | public relations (dept.) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `hohng-boh`; Work & Professions, p.146-147 |
| 품질관리(과/부) | quality control (dept.) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `poom-jeel-gwahl-lee`; Work & Professions, p.146-147 |
| 연구개발(과/부) | research & development (dept.) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `yuhn-goo-geh-bahl`; Work & Professions, p.146-147 |
| 영업(과/부) | sales (dept.) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `yuhng-uhp`; Work & Professions, p.146-147 |
| 회장 | chairman | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `hweh-jahng`; Work & Professions, Organizational Titles, p.148-149 |
| 부회장 | vice chairman | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `boo-hweh-jahng`; Work & Professions, p.148-149 |
| 사장 | president | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `sah-jahng`; Work & Professions, p.148-149 |
| 부사장 | vice president | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `boo-sah-jahng`; Work & Professions, p.148-149 |
| 전무 | executive director | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `juhn-moo`; Work & Professions, p.148-149 |
| 상무 | managing director | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `sahng-moo`; Work & Professions, p.148-149 |
| 이사 | director | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `ee-sah`; Work & Professions, p.148-149 |
| 부장 | general manager; division chief | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `boo-jahng`; Work & Professions, p.148-149 |
| 차장 | assistant general manager | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `chah-jahng`; Work & Professions, p.148-149 |
| 과장 | manager; section chief | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `gwah-jahng`; Work & Professions, p.148-149 |
| 대리 | deputy manager | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `deh-ree`; Work & Professions, p.148-149 |
| 사원 | employee | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `sah-wuhn`; Work & Professions, p.148-149 |
| 무슨 컴퓨터 쓰세요? | What kind of computer do you use? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `moo-s_n kuhm-pyoo-tuh ss_-seh-yo?`; Computer & the Internet, Expressions, p.150-151 |
| 맥 쓰세요, PC/IBM 쓰세요? | Do you use a Mac or a PC/IBM? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `mehk ss_-seh-yo, PC/IBM ss_-seh-yo?`; Computer & the Internet, p.150-151 |
| (source of problem) 문제가 생겼어요 | There is a problem with (source of problem). | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `(source of problem) moon-jeh-gah sehng-gyuht-suh-yo.`; Computer & the Internet, p.150-151 |
| (source of problem) 안 돼요 | (source of problem) does not work. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `(source of problem) ahn-dweh-yo.`; Computer & the Internet, p.150-151 |
| (source of problem) 잘 안 돼요 | (source of problem) does not work well. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `(source of problem) jahl ahn-dweh-yo.`; Computer & the Internet, p.150-151 |
| 취소 | cancel | verb | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `chwee-soh`; Computer & the Internet, Words > General, p.150-151 |
| 컴퓨터 | computer | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `kuhm-pyoo-tuh`; Computer & the Internet, p.150-151; loanword |
| 접속; 연결 | connection | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `juhp-sohk; yuhn-gyuhl`; Computer & the Internet, p.150-151 |
| 제어판 | control panel | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `jeh-uh-pahn`; Computer & the Internet, p.150-151 |
| 디렉토리 | directory | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `dee-rehk-toh-ree`; Computer & the Internet, p.150-151; loanword |
| 문서 | document | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `moon-suh`; Computer & the Internet, p.150-151 |
| 즐겨찾기 | favorites | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `j_l-gyuh-chaht-gee`; Computer & the Internet, p.152-153 |
| 파일; 문서 | file | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `pah-eel; moon-suh`; Computer & the Internet, p.152-153 |
| 하드웨어 | hardware | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `hah-d_-weh-uh`; Computer & the Internet, p.152-153; loanword |
| 정보 | information | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `juhng-boh`; Computer & the Internet, p.152-153 |
| 키보드 | keyboard | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `kee-boh-d_`; Computer & the Internet, p.152-153; loanword |
| 모니터 | monitor | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `moh-nee-tuh`; Computer & the Internet, p.152-153; loanword |
| PC방 | "PC room" | noun | slang | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `pee-shee-bahng`; Computer & the Internet, p.152-153; footnote: a pay-by-the-hour computer/high-speed-Internet rental venue — a distinctly Korean cultural institution |
| 인쇄; 출력 | print | verb | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `een-sweh; chool-lyuhk`; Computer & the Internet, p.152-153 |
| 프린터 | printer | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `p_-reen-tuh`; Computer & the Internet, p.152-153; loanword |
| 해상도 | resolution | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `heh-sahng-doh`; Computer & the Internet, p.152-153 |
| 다시 시작 | restart | verb | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `dah-shee shee-jahk`; Computer & the Internet, p.152-153 |
| 설정 | settings | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `suhl-jjuhng`; Computer & the Internet, p.152-153 |
| 종료 | shut down | verb | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `johng-nyoh`; Computer & the Internet, p.152-153 |
| 소프트웨어 | software | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `ssoh-p_-t_-weh-uh`; Computer & the Internet, p.152-153; loanword |
| 시작 | start | verb | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `shee-jahk`; Computer & the Internet, p.152-153 |
| 파일 (새 글) | File > new | phrase | technical | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `pah-eel / seh g_l`; Computer & the Internet, Word Processor menu list (훈글 software), p.152-153 |
| 불러오기 | open (file) | verb | technical | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `bool-luh-oh-gee`; Computer & the Internet, p.152-153 |
| 저장하기 | save | verb | technical | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `juh-jahng-hah-gee`; Computer & the Internet, p.152-153 |
| 새 이름으로 | save as | phrase | technical | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `seh ee-r_-m_-roh`; Computer & the Internet, p.152-153 |
| 인쇄 | print (menu item) | verb | technical | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `een-sweh`; Computer & the Internet, p.152-153 |
| 미리보기 | preview | verb | technical | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `mee-ree-boh-gee`; Computer & the Internet, p.152-153 |
| 끝 | exit | noun | technical | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `gg_t`; Computer & the Internet, p.152-153 |
| 편집 | Edit (menu) | noun | technical | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `pyuhn-jeep`; Computer & the Internet, p.152-153 |
| 오려두기 | cut | verb | technical | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `oh-ryuh-doo-gee`; Computer & the Internet, p.152-153 |
| 복사하기 | copy | verb | technical | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `bohk-sah-hah-gee`; Computer & the Internet, p.152-153 |
| 붙이기 | paste | verb | technical | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `boo-chee-gee`; Computer & the Internet, p.152-153 |
| 되살리기 | undo | verb | technical | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `dweh-sahl-lee-gee`; Computer & the Internet, p.152-153 |
| 모두 선택 | select all | phrase | technical | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `moh-doo suhn-tehk`; Computer & the Internet, p.152-153 |
| 찾기 | find | verb | technical | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `chaht-gee`; Computer & the Internet, p.152-153 |
| 보기 | View (menu) | noun | technical | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `boh-gee`; Computer & the Internet, p.152-153 |
| 입력 | Insert (menu) | noun | technical | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `eem-nyuhk`; Computer & the Internet, p.152-153 |
| 날짜/시간 | date and time | noun | technical | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `nahl-jjah/shee-gahn`; Computer & the Internet, p.152-153 |
| 모양 | Format (menu) | noun | technical | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `moh-yahng`; Computer & the Internet, p.152-153 |
| 글자 모양 | font | noun | technical | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `g_l-jjah moh-yahng`; Computer & the Internet, p.152-153 |
| 문단 모양 | paragraph | noun | technical | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `moon-dahn moh-yahng`; Computer & the Internet, p.152-153 |
| 편집 용지 | page setup | noun | technical | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `pyuhn-jeep yong-jee`; Computer & the Internet, p.152-153 |
| 머리말/꼬리말 | header/footer | noun | technical | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `muh-ree-mahl / ggoh-ree-mahl`; Computer & the Internet, p.152-153 |
| 쪽번호 매기기 | page numbering | verb | technical | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `jjohk-buhn-hoh meh-gee-gee`; Computer & the Internet, p.152-153 |
| 나누기 | break | noun | technical | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `nah-noo-gee`; Computer & the Internet, p.152-153 |
| 도구 | Tools (menu) | noun | technical | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `doh-goo`; Computer & the Internet, p.152-153 |
| 맞춤법 | spelling | noun | technical | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `maht-choom-buhp`; Computer & the Internet, p.152-153 |
| 사전 | dictionary (menu item) | noun | technical | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `sah-juhn`; Computer & the Internet, p.152-153 |
| 라벨 | labels | noun | technical | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `lah-behl`; Computer & the Internet, p.152-153; loanword |
| 표 | Table (menu) | noun | technical | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `pyo`; Computer & the Internet, p.152-153 |
| 표 그리기 | draw table | verb | technical | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `pyo g_-ree-gee`; Computer & the Internet, p.152-153 |
| 셀 | cell | noun | technical | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `ssehl`; Computer & the Internet, p.152-153; loanword |
| 선 | line | noun | technical | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `suhn`; Computer & the Internet, p.152-153 |
| 셀 나누기 | split cells | verb | technical | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `ssehl nah-noo-gee`; Computer & the Internet, p.152-153 |
| 셀 합치기 | merge cells | verb | technical | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `ssehl hahp-chee-gee`; Computer & the Internet, p.152-153 |
| 줄 | rows | noun | technical | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `jool`; Computer & the Internet, p.152-153 |
| 칸 | columns | noun | technical | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `kahn`; Computer & the Internet, p.152-153 |
| 줄/칸 삽입 | insert row/columns | verb | technical | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `jool/kahn sah-beep`; Computer & the Internet, p.152-153 |
| 줄/칸 지우기 | delete row/column | verb | technical | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `jool/kahn jee-oo-gee`; Computer & the Internet, p.152-153 |
| 창 | Window (menu) | noun | technical | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `chahng`; Computer & the Internet, p.154-155 |
| 도움말 | Help (menu) | noun | technical | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `doh-oom-mahl`; Computer & the Internet, p.154-155 |
| 내용 | contents | noun | technical | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `neh-yong`; Computer & the Internet, p.154-155 |
| 찾아보기 | index | noun | technical | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `chah-jah-boh-gee`; Computer & the Internet, p.154-155 |
| 다운로드; 다운받기 | download | verb | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `dah-oon-loh-d_; dah-oon-baht-gee`; Computer & the Internet, The Internet, p.154-155 |
| 이메일 | email | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `ee-meh-eel`; Computer & the Internet, p.154-155; loanword |
| 이메일 주소 | email address | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `ee-meh-eel joo-soh`; Computer & the Internet, p.154-155 |
| 홈페이지; 홈피 | homepage | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `hohm-peh-ee-jee; hohm-pee`; Computer & the Internet, p.154-155 |
| 인터넷 | Internet | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `een-tuh-neht`; Computer & the Internet, p.154-155; loanword |
| 링크 | link | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `reeng-k_`; Computer & the Internet, p.154-155; loanword |
| 로그인 | login | verb | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `loh-g_-een`; Computer & the Internet, p.154-155; loanword |
| 게시판 | message board | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `geh-shee-pahn`; Computer & the Internet, p.154-155 |
| 가입 | register | verb | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `gah-eep`; Computer & the Internet, p.154-155 |
| 검색 | search | verb | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `guhm-sehk`; Computer & the Internet, p.154-155 |
| 웹사이트 | Web site | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `wehp-ssah-ee-t_`; Computer & the Internet, p.154-155; loanword |
| 바쁩니다 | I am busy. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `bah-bb_m-nee-dah.`; Home Office & Things, Expressions, p.156-157 |
| 한가합니다 | It's slow; I'm not busy. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `hahn-gah-hahm-nee-dah.`; Home Office & Things, p.156-157 |
| ~ 필요합니다 | I need ~ | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `~ pee-ryo-hahm-nee-dah.`; Home Office & Things, p.156-157 |
| ~ 있습니까? | Is there ~? | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `~ eet-s_m-neek-gah?`; Home Office & Things, p.156-157 |
| 이거 복사/팩스 부탁합니다 | Please copy/fax this. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `ee-guh bohk-sah/pehk-s_ boo-tahk-kahm-nee-dah.`; Home Office & Things, p.156-157 |
| ~ 부탁합니다 | ~, please. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `~ boo-tahk-kahm-nee-dah.`; Home Office & Things, p.156-157; footnote: usable for requesting either a person or a thing |
| 수첩; 전자 수첩 | appointment book; electronic appointment book | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `soo-chuhp; juhn-jah-soo-chuhp`; Home Office & Things, Words, p.156-157 |
| 건전지 | batteries | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `guhn-juhn-jee`; Home Office & Things, p.156-158 |
| 비퍼; 호출기 | beeper | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `bee-puh; hoh-chool-gee`; Home Office & Things, p.156-157 |
| 바인더 | binder | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `bah-een-duh`; Home Office & Things, p.156-157; loanword |
| 계산기 | calculator | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `geh-sahn-gee`; Home Office & Things, p.156-157 |
| 달력 | calendar | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `dahl-lyuhk`; Home Office & Things, p.156-157; footnote: a general wall/desk calendar used for checking dates, distinct from 수첩 (the appointment-book-style calendar) |
| 핸드폰; 휴대폰 | cell phone | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `hehn-d_-pohn; hyoo-deh-pohn`; Home Office & Things, p.158-159 |
| 의자 | chair | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `_ee-jah`; Home Office & Things, p.158-159 |
| 클립 | clip | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `k_l-leep`; Home Office & Things, p.158-159; loanword |
| 복사기 | copier | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `bohk-sah-gee`; Home Office & Things, p.158-159 |
| 책상 | desk | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `chehk-sahng`; Home Office & Things, p.158-159 |
| 서류 | documents | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `suh-ryoo`; Home Office & Things, p.158-159 |
| 서랍 | drawer | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `suh-rahp`; Home Office & Things, p.158-159 |
| 봉투 | envelope | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `bohng-too`; Home Office & Things, p.158-159 |
| 지우개 | eraser | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `jee-oo-geh`; Home Office & Things, p.158-159 |
| 팩스 | fax | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `pehk-s_`; Home Office & Things, p.158-159; loanword |
| 팩스 번호 | fax number | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `pehk-s_ buhn-hoh`; Home Office & Things, p.158-159 |
| 파일 | file | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `pah-eel`; Home Office & Things, p.158-159; loanword |
| 형광펜 | fluorescent pen | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `hyuhng-gwahng-pehn`; Home Office & Things, p.158-159 |
| 폴더 | folder | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `pohl-duh`; Home Office & Things, p.158-159; loanword |
| 풀; 접착제 | glue | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `pool; juhp-chahk-jeh`; Home Office & Things, p.158-159 |
| 편지 | letter | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `pyuhn-jee`; Home Office & Things, p.158-159 |
| 잡지 | magazine | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `jahp-jee`; Home Office & Things, p.158-159 |
| 우편물 | mail | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `oo-pyuhn-mool`; Home Office & Things, p.158-159 |
| 샤프 | mechanical pencil | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `shyah-p_`; Home Office & Things, p.158-159; loanword (from "sharp") |
| 신문 | newspaper | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `sheen-moon`; Home Office & Things, p.158-159 |
| 노트; 공책 | notebook | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `noh-t_; gohng-chehk`; Home Office & Things, p.158-159 |
| 종이; 용지 | paper | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `johng-ee; yong-jee`; Home Office & Things, p.158-159 |
| 펜 | pen | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `pehn`; Home Office & Things, p.158-159; loanword |
| 연필 | pencil | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `yuhn-peel`; Home Office & Things, p.158-159 |
| 필통 | pencil case | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `peel-tohng`; Home Office & Things, p.158-159 |
| 연필깎기 | pencil sharpener | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `yuhn-peel-ggahk-gee`; Home Office & Things, p.158-159 |
| 수첩 | pocket diary | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `soo-chuhp`; Home Office & Things, p.158-159 |
| 엽서 | postcard | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `yuhp-suh`; Home Office & Things, p.158-159 |
| 자 | ruler | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `jah`; Home Office & Things, p.158-159 |
| 가위 | scissors | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `gah-wee`; Home Office & Things, p.158-159 |
| 우표 | stamp (postal) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `oo-pyo`; Home Office & Things, p.158-159 |
| 스테플러침 | staple | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `s_-teh-p_l-luh-cheem`; Home Office & Things, p.158-159; loanword |
| 스테플러 | stapler | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `s_-teh-p_l-luh`; Home Office & Things, p.158-159; loanword |
| 테이프 | tape | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `teh-ee-p_`; Home Office & Things, p.158-159; loanword |
| 전화; 무선전화 | telephone; wireless phone | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `juhn-hwah; moo-suhn-juhn-hwah`; Home Office & Things, p.158-159 |
| 전화 번호 | telephone number | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `juhn-hwah buhn-hoh`; Home Office & Things, p.158-159 |
| 압정 | thumbtack | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `ahp-juhng`; Home Office & Things, p.158-159 |
| 따뜻해요 | It's warm. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `ddah-dd_-teh-yo.`; Nature, Expressions > Weather, p.162-163 |
| 더워요 | It's hot. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `duh-wuh-yo.`; Nature, p.162-163 |
| 무더워요 | It's hot and humid. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `moo-duh-wuh-yo.`; Nature, p.162-163 |
| 선선해요 | It's cool. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `suhn-suhn-heh-yo.`; Nature, p.162-163 |
| 쌀쌀해요 | It's chilly. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `ssahl-ssahl-heh-yo.`; Nature, p.162-163 |
| 추워요 | It's cold. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `choo-wuh-yo.`; Nature, p.162-163 |
| 바람이 많이 불어요 | It's windy. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `bah-rah-mee mah-nee boo-ruh-yo.`; Nature, p.162-163 |
| 비 와요 | It's raining. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `bee-wah-yo.`; Nature, p.162-163 |
| 눈 와요 | It's snowing. | phrase | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `noon-wah-yo.`; Nature, p.162-163 |
| 봄 | spring | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `bohm`; Nature, Words > Seasons, p.162-163 |
| 여름 | summer | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `yuh-r_m`; Nature, p.162-163 |
| 가을 | autumn | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `gah-_l`; Nature, p.162-163 |
| 겨울 | winter | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `gyuh-ool`; Nature, p.162-163 |
| 기압 | atmospheric pressure | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `gee-ahp`; Nature, Words > Weather & Climate, p.162-163 |
| 고기압 | high atmospheric pressure | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `goh-gee-ahp`; Nature, p.162-163 |
| 저기압 | low atmospheric pressure | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `juh-gee-ahp`; Nature, p.162-163 |
| 기후 | climate | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `gee-hoo`; Nature, p.162-163 |
| 습도 | humidity | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | `s_p-doh`; Nature, p.162-163 |
| 장마 | monsoon | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | jahng-mah; Nature > Weather, p.164 |
| 비 | rain | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | bee; Nature > Weather, p.164 |
| 눈 | snow | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | noon; Nature > Weather, p.164 |
| 폭풍 | storm | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | pohk-poong; Nature > Weather, p.164 |
| 기온 | temperature (air) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | gee-ohn; Nature > Weather, p.164 |
| 체감온도 | temperature with the wind chill factor | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | cheh-gahm-ohn-doh; Nature > Weather, p.164 |
| 천둥 | thunder | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | chuhn-doong; Nature > Weather, p.164 |
| 날씨; 일기 | weather | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | nahl-ssee; eel-gee; Nature > Weather, p.164 |
| 일기예보 | weather forecast | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | eel-gee-yeh-boh; Nature > Weather, p.164 |
| 바람 | wind | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | bah-rahm; Nature > Weather, p.164 |
| 꽃 | FLOWER (generic) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | ggoht; Nature > Flowers, p.164 |
| 진달래 | azalea | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | jeen-dahl-leh; Nature > Flowers, p.164 |
| 카네이션 | carnation | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | kah-neh-ee-shyuhn; Nature > Flowers, p.164 |
| 국화 | chrysanthemum | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | goo-kwah; Nature > Flowers, p.164 |
| 개나리 | golden bell | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | geh-nah-ree; Nature > Flowers, p.164 |
| 백합 | lily | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | beh-kahp; Nature > Flowers, p.164 |
| 난초 | orchid | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | nahn-choh; Nature > Flowers, p.164 |
| 모란 | peony | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | moh-rahn; Nature > Flowers, p.164 |
| 장미 | rose | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | jahng-mee; Nature > Flowers, p.164 |
| 무궁화 | the rose of Sharon | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | moo-goong-hwah; Nature > Flowers, p.164; footnote: Korea's national flower |
| 튤립 | tulip | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | tyoo-leep; Nature > Flowers, p.164 |
| 야생화 | wild flower | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | yah-sehng-hwah; Nature > Flowers, p.164 |
| 나무 | TREE (generic) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | nah-moo; Nature > Trees, p.165 |
| 벚나무 | cherry tree | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | buhn-nah-moo; Nature > Trees, p.165 |
| 은행나무 | ginko tree | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | _n-hehng-nah-moo; Nature > Trees, p.165 |
| 단풍나무 | maple tree | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | dahn-poong-nah-moo; Nature > Trees, p.165 |
| 떡갈나무 | oak tree | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | dduhk-gahl-lah-moo; Nature > Trees, p.165 |
| 소나무 | pine tree | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | soh-nah-moo; Nature > Trees, p.165 |
| 동물 | ANIMAL (generic) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | dohng-mool; Nature > Animals, p.165 |
| 새 | bird | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | seh; Nature > Animals, p.165 |
| 돼지 | boar | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | dweh-jee; Nature > Animals, p.165; marked as one of the 12 Chinese zodiac animals |
| 고양이 | cat | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | goh-yahng-ee; Nature > Animals, p.165 |
| 닭 | chicken | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | dahk; Nature > Animals, p.165; zodiac animal |
| 소 | cow | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | soh; Nature > Animals, p.165; zodiac animal |
| 공룡 | dinosaur | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | gohng-nyong; Nature > Animals, p.165 |
| 개 | dog | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | geh; Nature > Animals, p.165; zodiac animal |
| 용 | dragon | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | yong; Nature > Animals, p.165; zodiac animal |
| 코끼리 | elephant | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | kohk-gee-ree; Nature > Animals, p.165 |
| 물고기; 생선 | fish | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | mool-ggoh-gee; sehng-suhn; Nature > Animals, p.165; footnote: 물고기 = fish in general, 생선 = fish specifically as food |
| 여우 | fox | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | yuh-oo; Nature > Animals, p.165 |
| 기린 | giraffe | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | gee-reen; Nature > Animals, p.165 |
| 하마 | hippopotamus | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | hah-mah; Nature > Animals, p.165 |
| 말 | horse | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | mahl; Nature > Animals, p.165; zodiac animal |
| 사자 | lion | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | sah-jah; Nature > Animals, p.165 |
| 원숭이 | monkey | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | wuhn-soong-ee; Nature > Animals, p.166; zodiac animal |
| 쥐 | mouse | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | jwee; Nature > Animals, p.166; zodiac animal |
| 애완동물 | pet | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | eh-wahn-dohng-mool; Nature > Animals, p.166 |
| 돼지 | pig | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | dweh-jee; Nature > Animals, p.166 (same Hangul as "boar", distinct English headword as printed) |
| 강아지 | puppy | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | gahng-ah-jee; Nature > Animals, p.166 |
| 토끼 | rabbit | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | tohk-gee; Nature > Animals, p.166; zodiac animal |
| 양 | sheep | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | yahng; Nature > Animals, p.166; zodiac animal |
| 뱀 | snake | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | behm; Nature > Animals, p.166; zodiac animal |
| 다람쥐 | squirrel | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | dah-rahm-jwee; Nature > Animals, p.166 |
| 호랑이 | tiger | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | hoh-rahng-ee; Nature > Animals, p.166; zodiac animal |
| 늑대 | wolf | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | n_k-deh; Nature > Animals, p.166 |
| 얼룩말 | zebra | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | uhl-loong-mahl; Nature > Animals, p.166 |
| 공기 | air | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | gohng-gee; Nature > Others, p.166 |
| 단풍 | autumn foliage | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | dahn-poong; Nature > Others, p.166 |
| 바다 | beach | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | bah-dah; Nature > Others, p.166 (also listed as "sea" on p.167, same Hangul/romanization) |
| 바위 | boulder | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | bah-wee; Nature > Others, p.166 (also listed as "rock" on p.167, same Hangul/romanization) |
| 시내 | brook | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | shee-neh; Nature > Others, p.166 (also listed as "stream" on p.167, same Hangul/romanization) |
| 기후 | climate | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | gee-hoo; Nature > Others, p.166 |
| 구름 | cloud | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | goo-r_m; Nature > Others, p.166 |
| 가뭄 | draught | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | gah-moom; Nature > Others, p.166 |
| 폭포 | falls (water falls) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | pohk-poh; Nature > Others, p.166 |
| 홍수 | flood | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | hohng-soo; Nature > Others, p.166 |
| 숲 | forest | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | soop; Nature > Others, p.166 |
| 잔디 | grass | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | jahn-dee; Nature > Others, p.166 |
| 언덕 | hill | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | uhn-duhk; Nature > Others, p.166 |
| 호수 | lake | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | hoh-soo; Nature > Others, p.166 |
| 땅; 토지 | land | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | ddahng; toh-jee; Nature > Others, p.167 |
| 잎; 잎사귀 | leaf | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | eep; eep-sah-gwee; Nature > Others, p.167 |
| 달 | moon | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | dahl; Nature > Others, p.167 |
| 산 | mountain | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | sahn; Nature > Others, p.167 |
| 대양 | ocean | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | deh-yahng; Nature > Others, p.167 |
| 자갈 | pebble | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | jah-gahl; Nature > Others, p.167 |
| 꽃잎 | petal | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | ggohn-neep; Nature > Others, p.167 |
| 화초 | plant | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | hwah-choh; Nature > Others, p.167 |
| 연못 | pond | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | yuhn-moht; Nature > Others, p.167 |
| 강 | river | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | gahng; Nature > Others, p.167 |
| 모래 | sand | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | moh-reh; Nature > Others, p.167 |
| 하늘 | sky | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | hah-n_l; Nature > Others, p.167 |
| 흙 | soil | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | h_k; Nature > Others, p.167 |
| 별 | star | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | byuhl; Nature > Others, p.167 |
| 해; 태양 | sun | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | heh; teh-yahng; Nature > Others, p.167 |
| 계곡 | valley | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | gyeh-gohk; Nature > Others, p.167 |
| 물 | water | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | mool; Nature > Others, p.167 |
| 파도 | wave | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | pah-doh; Nature > Others, p.167 |
| 행정(부) | administration | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | hehng-juhng(-boo); Politics, Ideology & Beyond, p.170 |
| 대사 | ambassador | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | deh-sah; Politics, p.170 |
| 무정부주의 | anarchism | noun | technical.politics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | moo-juhng-boo-joo-_ee; Politics, p.170 |
| 내각 | cabinet | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | neh-gahk; Politics, p.170 |
| 후보자 | candidate | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | hoo-boh-jah; Politics, p.170 |
| 자본주의 | capitalism | noun | technical.politics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | jah-bohn-joo-_ee; Politics, p.170 |
| 식민주의 | colonialism | noun | technical.politics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | sheeng-meen-joo-_ee; Politics, p.170 |
| 공산주의 | communism | noun | technical.politics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | gohng-sahn-joo-_ee; Politics, p.170 |
| 국회 | congress | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | goo-kweh; Politics, p.170 |
| 국회의원 | congressman | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | goo-kweh-_ee-wuhn; Politics, p.170 |
| 보수주의 | conservatism | noun | technical.politics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | boh-soo-joo-_ee; Politics, p.170 |
| 민주주의 | democracy | noun | technical.politics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | meen-joo-joo-_ee; Politics, p.170 |
| 독재자 | dictator | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | dohk-jeh-jah; Politics, p.170 |
| 독재 | dictatorship | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | dohk-jeh; Politics, p.170 |
| 외교 | diplomacy | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | weh-gyo; Politics, p.170 |
| 외교관 | diplomat | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | weh-gyo-gwahn; Politics, p.170 |
| 반체제자 | dissident | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | bahn-cheh-jeh-jah; Politics, p.170 |
| 선거 | election | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | suhn-guh; Politics, p.170 |
| 선거운동 | election campaign | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | suhn-guh-oon-dohng; Politics, p.170 |
| 대사관 | embassy | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | deh-sah-gwahn; Politics, p.170 |
| 망명 | exile | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | mahng-myuhng; Politics, p.170 |
| 파시즘 | fascism | noun | technical.politics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | pah-shee-j_m; Politics, p.170 |
| 정부 | government | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | juhng-boo; Politics, p.170 |
| 민중 | grassroots | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | meen-joong; Politics, p.172 |
| 청문회 | hearing (political) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | chuhng-moon-hweh; Politics, p.172 |
| 헤게모니 | hegemony | noun | technical.politics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | heh-geh-moh-nee; Politics, p.172 |
| 이상주의 | idealism | noun | technical.politics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | ee-sahng-joo-_ee; Politics, p.172 |
| 이데올로기 | ideology | noun | technical.politics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | ee-deh-ohl-loh-gee; Politics, p.172 |
| 제국주의 | imperialism | noun | technical.politics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | jeh-gook-joo-_ee; Politics, p.172 |
| 사법부 | judiciary | noun | technical.politics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | sah-buhp(-boo); Politics, p.172 |
| 입법부 | legislative | noun | technical.politics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | eep-buhp(-boo); Politics, p.172 |
| 자유주의 | liberalism | noun | technical.politics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | jah-yoo-joo-_ee; Politics, p.172 |
| 로비 | lobby | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | loh-bee; Politics, p.172 |
| 장관 | minister | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | jahng-gwahn; Politics, p.172 |
| 운동 | movement (political) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | oon-dohng; Politics, p.172 |
| 국수주의 | nationalism | noun | technical.politics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | gook-soo-joo-_ee; Politics, p.172 |
| 야당 | opposition party | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | yah-dahng; Politics, p.172 |
| 의회; 국회 | parliament | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | _ee-hweh; goo-kweh; Politics, p.172 |
| 애국주의 | patriotism | noun | technical.politics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | eh-gook-joo-_ee; Politics, p.172 |
| 철학 | philosophy | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | chuhl-hahk; Politics, p.172 |
| 정책 | policy | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | juhng-chehk; Politics, p.172 |
| 망명 | political exile | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | mahng-myuhng; Politics, p.172 (same Hangul as "exile" above) |
| 정당; 당 | political party | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | juhng-dahng; dahng; Politics, p.172 |
| 권력 | political power | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | gwuhl-lyuhk; Politics, p.172 |
| 정치가; 정치인 | politician | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | juhng-chee-gah; juhng-chee-een; Politics, p.172 |
| 정치 | politics | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | juhng-chee; Politics, p.172 |
| 여론조사 | poll | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | yuh-rohn-joh-sah; Politics, p.173 |
| 실용주의 | pragmatism | noun | technical.politics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | sheel-yong-joo-_ee; Politics, p.173 |
| 대통령 | president (of a nation) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | deh-tohng-nyuhng; Politics, p.173 |
| 수상 | prime minister | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | soo-sahng; Politics, p.173 |
| 진보주의 | progressivism | noun | technical.politics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | jeen-boh-joo-_ee; Politics, p.173 |
| 여론 | public opinion | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | yuh-rohn; Politics, p.173 |
| 하원의원 | representative (of the U.S.) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | hah-wuhn-_ee-wuhn; Politics, p.173 |
| 혁명 | revolution | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | hyuhng-myuhng; Politics, p.173 |
| 여당 | ruling party | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | yuh-dahng; Politics, p.173 |
| 상원의원 | senator (of the U.S.) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | sahng-wuhn-_ee-wuhn; Politics, p.173 |
| 사회주의 | socialism | noun | technical.politics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | sah-hweh-joo-_ee; Politics, p.173 |
| 사회 | society | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | sah-hweh; Politics, p.173 |
| 대변인 | speaker; spokesperson | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | deh-byuh-neen; Politics, p.173 |
| 지지자 | supporter | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | jee-jee-jah; Politics, p.173 |
| 부통령 | vice president (of a nation) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | boo-tohng-nyuhng; Politics, p.173 |
| 투표; 표 | vote | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | too-pyo; pyo; Politics, p.173 |
| 투표자; 투표인 | voter | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | too-pyo-jah; too-pyo-een; Politics, p.173 |
| 선서(진술)서 | affidavit | noun | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | suhn-suh(-jeen-sool)-suh; Law, p.176 |
| 항소 | appeal | noun | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | hahng-soh; Law, p.176 |
| 항소인 | appellant | noun | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | hahng-soh-een; Law, p.176 |
| 보석금 | bail | noun | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | boh-suhk-g_m; Law, p.176 |
| 구속 영장 | capias | noun | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | goo-sohk yuhng-jjahng; Law, p.176 (also listed as "arrest warrant" on p.178) |
| 소송 | case; lawsuit | noun | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | soh-sohng; Law, p.176 |
| 고소 | charge | noun/verb | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | goh-soh; Law, p.176 |
| 민사 ~ | civil ~ (case, etc.) | adjective | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | meen-sah ~; Law, p.176 |
| 법원; 법정 | court | noun | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | buh-bwuhn; buhp-jjuhng; Law, p.176 |
| 항소법원 | court of appeal | noun | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | hahng-soh-buh-bwuhn; Law, p.176 |
| 지방법원 | district court | noun | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | jee-bahng-buh-bwuhn; Law, p.176 |
| 대법원 | supreme court | noun | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | deh-buh-bwuhn; Law, p.176 |
| 법원 | courthouse | noun | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | buh-bwuhn; Law, p.176 |
| 형사 ~ | criminal ~ (case, etc.) | adjective | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | hyuhng-sah ~; Law, p.176 |
| 피고 | defendant | noun | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | pee-goh; Law, p.176 |
| 진술 | deposition | noun | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | jeen-sool; Law, p.176 |
| 기각 | dismissal | noun | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | gee-gahk; Law, p.176 |
| 유죄 | guilty | adjective | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | yoo-jweh; Law, p.176 |
| 기소 | indictment | noun | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | gee-soh; Law, p.176 |
| 판사 | judge | noun | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | pahn-sah; Law, p.176 |
| 재판 | judgment | noun | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | jeh-pahn; Law, p.176 |
| 배심원 | juror | noun | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | beh-shee-mwuhn; Law, p.176 |
| 법; 법률 | law | noun | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | buhp; buhm-nyool; Law, p.176 |
| 변호사 | lawyer | noun | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | byuhn-hoh-sah; Law, p.178 |
| 소송 당사자 | litigant parties | noun | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | soh-sohng dahng-sah-jah; Law, p.178 |
| 소송 | litigation | noun | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | soh-sohng; Law, p.178 (same Hangul as "case; lawsuit"/"suit") |
| 무죄 | not guilty | adjective | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | moo-jweh; Law, p.178 |
| 이의 | objection | noun | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | ee-_ee; Law, p.178 |
| 기각 | overrule | verb | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | gee-gahk; Law, p.178 (same Hangul as "dismissal") |
| 가석방; 집행 유예 | parole | noun | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | gah-suhk-bbahng; jee-pehng yoo-yeh; Law, p.178 |
| 원고; 고소인 | plaintiff | noun | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | wuhn-goh; goh-soh-een; Law, p.178 |
| 집행 유예 | probation | noun | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | jeep-pehng-yoo-yeh; Law, p.178 |
| 증거 | proof | noun | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | j_ng-guh; Law, p.178 |
| 검사 | prosecutor | noun | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | guhm-sah; Law, p.178 |
| 형; 선고 | sentence | noun | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | hyuhng; suhn-goh; Law, p.178 |
| 소환 | subpena | noun | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | soh-hwahn; Law, p.178 |
| 소송 | suit | noun | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | soh-sohng; Law, p.178 |
| 혐의자; 용의자 | suspect | noun | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | hyuhm-_ee-jah; yong-_ee-jah; Law, p.178 |
| 인정 | sustain | verb | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | een-juhng; Law, p.178 |
| 증언 | testimony | noun | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | j_ng-uhn; Law, p.178 |
| 평결; 판결 | verdict | noun | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | pyuhng-gyuhl; pahn-gyuhl; Law, p.178 |
| 영장 | warrant | noun | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | yuhng-jjahng; Law, p.178 |
| 구속 영장 | arrest warrant | noun | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | goo-sohk yuhng-jjahng; Law, p.178 |
| 수색 영장 | search warrant | noun | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | soo-sehk yuhng-jjahng; Law, p.178 |
| 철회 | withdrawal | noun | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | chuhl-hweh; Law, p.178 |
| 증인 | witness | noun | technical.legal | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | j_ng-een; Law, p.178 |
| 분석 | analysis | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | boon-suhk; Micro & Macroeconomics, p.180 |
| 자산; 재산 | asset | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | jah-sahn; jeh-sahn; Economics, p.180 |
| 회계 감사 | audit | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | hweh-geh-gahm-sah; Economics, p.180 |
| 은행 | bank | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | _n-hehng; Economics, p.180 |
| 도산; 파산 | bankruptcy | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | doh-sahn; pah-sahn; Economics, p.180 |
| 하락세 | bearish trend | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | hah-rahk-seh; Economics, p.180 |
| 채권 | bond | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | chehk-gwuhn; Economics, p.180 |
| 상승세 | bullish trend | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | sahng-s_ng-seh; Economics, p.180 |
| 자본; 자본금 | capital | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | jah-bohn; jah-bohn-g_m; Economics, p.180 |
| 수표 | check | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | soo-pyo; Economics, p.180 |
| 경쟁력 | competitiveness | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | gyuhng-jehng-nyuhk; Economics, p.180 |
| 계약 | contract | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | geh-yahk; Economics, p.180 |
| 사단법인 | corporation | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | sah-dahn-buh-been; Economics, p.180 |
| 물가 | cost of living | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | mool-ggah; Economics, p.180 |
| 빚 | debt | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | beet; Economics, p.180 |
| 수요 | demand | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | soo-yoh; Economics, p.180 |
| 불황 | depression | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | bool-hwahng; Economics, p.180 |
| 경제 | economy | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | gyuhng-jeh; Economics, p.180 |
| 순가치 | equity | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | soon-gah-chee; Economics, p.180 |
| 수출 | export | noun/verb | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | soo-chool; Economics, p.180 |
| 금융 | finance | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | g_-myoong; Economics, p.180 |
| 자유 무역 | free trade | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | jah-yoo moo-yuhk; Economics, p.180 |
| 자본; 기금 | fund | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | jah-bohn; gee-g_m; Economics, p.180 |
| 보조금; 조성금 | grant | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | boh-joh-g_m; joh-suhng-g_m; Economics, p.182 |
| 성장 | growth | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | suhng-jahng; Economics, p.182 |
| 헤지펀드 | hedge fund | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | heh-jee-puhn-d_; Economics, p.182 |
| 수입 | import | noun/verb | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | soo-eep; Economics, p.182 |
| 산업 | industry | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | sah-nuhp; Economics, p.182 |
| 농업 | agriculture | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | nohng-uhp; Economics > Industry subtypes, p.182 |
| 유통업 | distribution | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | yoo-tohng-uhp; Economics > Industry subtypes, p.182 |
| 수산업 | fishing (industry) | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | soo-sah-nuhp; Economics > Industry subtypes, p.182 |
| 임업; 임산업 | forestry | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | ee-muhp; eem-sah-nuhp; Economics > Industry subtypes, p.182 |
| 제조업 | manufacturing | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | jeh-joh-uhp; Economics > Industry subtypes, p.182 |
| 판매업 | sales | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | pahn-meh-uhp; Economics > Industry subtypes, p.182 |
| 서비스업 | service (industry) | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | ssuh-bee-ss_-uhp; Economics > Industry subtypes, p.182 |
| 인플레 | inflation | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | een-p_l-leh; Economics, p.182 |
| 보험 | insurance | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | boh-huhm; Economics, p.182 |
| 생명보험 | life insurance | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | sehng-myuhng-boh-huhm; Economics, p.182 |
| 의료보험 | medical insurance | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | _ee-ryo-boh-huhm; Economics, p.182 |
| 이자 | interest | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | ee-jah; Economics, p.182 |
| 이자율 | interest rate | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | ee-jah-yool; Economics, p.182 |
| 투자 | investment | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | too-jah; Economics, p.182 |
| 투자은행 | investment bank | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | too-jah-_n-hehng; Economics, p.182 |
| 투자자 | investor | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | too-jah-jah; Economics, p.182 |
| 정크본드 | junk bond | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | juhng-k_-bohn-d_; Economics, p.182 |
| 토지 | land | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | toh-jee; Economics, p.182 |
| 융자 | loan | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | yoong-jah; Economics, p.182 |
| 시장 | market | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | shee-jahng; Economics, p.183 |
| 외환 시장 | foreign exchange market | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | weh-hwahn shee-jahng; Economics, p.183 |
| 취업 시장 | job market | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | chwee-uhp shee-jahng; Economics, p.183 |
| 노동 시장 | labor market | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | noh-dohng shee-jahng; Economics, p.183 |
| 증권시장; 증시 | stock market | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | j_ng-ggwuhn-shee-jahng; j_ng-shee; Economics, p.183 and repeated p.184 |
| 시장 경제 | market economy | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | shee-jahng gyuhng-jeh; Economics, p.183 |
| 마케팅 | marketing | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | mah-keh-teeng; Economics, p.183 |
| 시장 조사 | market research | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | shee-jahng joh-sah; Economics, p.183 |
| 돈 | money | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | dohn; Economics, p.183 |
| 지폐 | bills (money) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | jee-peh; Economics, p.183 |
| 현금 | cash | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | hyuhn-g_m; Economics, p.183 |
| 거스름돈 | change (money owed back) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | guh-s_-r_m-dohn; Economics, p.183; footnote: specifically the change owed back from a purchase (vs. 잔돈) |
| 잔돈 | change (small money) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | jahn-dohn; Economics, p.183; footnote: can be either owed-back change or any small coins/bills in general |
| 동전 | coins | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | dohng-juhn; Economics, p.183 |
| 독점 | monopoly | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | dohk-juhm; Economics, p.183 |
| 저당 | mortgage | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | juh-dahng; Economics, p.183 |
| 다국적 기업 | multinational corporation | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | dah-gook-juhk gee-uhp; Economics, p.183 |
| 소유물 | possession | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | soh-yoo-mool; Economics, p.183 |
| 원금 | principal | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | wuhn-g_m; Economics, p.183 |
| 사기업 | private sector | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | sah-gee-uhp; Economics, p.183 |
| 제품 | product | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | jeh-poom; Economics, p.183 |
| 생산력 | productivity | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | sehng-sahn-nyuhk; Economics, p.183 |
| 이익 | profits | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | ee-eek; Economics, p.184 |
| 홍보; PR | public relations | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | hohng-boh; pee-ahl; Economics, p.184 |
| 공기업 | public sector | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | gohng-gee-uhp; Economics, p.184 |
| 구매 | purchase | noun/verb | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | goo-meh; Economics, p.184 |
| 구매력 | purchasing power | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | goo-meh-ryuhk; Economics, p.184 |
| 공급 | supply | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | gohng-g_p; Economics, p.184 (listed twice on this page, counted once) |
| 수익률 | rate of return | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | soo-eeng-nyool; Economics, p.184 |
| 부동산 | real estate | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | boo-dohng-sahn; Economics, p.184 |
| 불경기 | recession | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | bool-gyuhng-gee; Economics, p.184 |
| 저축 | saving | noun/verb | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | juh-chook; Economics, p.184 |
| 주식 | stock | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | joo-sheek; Economics, p.184 |
| 관세 | tariff | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | gwahn-seh; Economics, p.184 |
| 세금 | tax | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | seh-g_m; Economics, p.184 |
| 세금 혜택 | tax benefits | noun | technical.economics | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | seh-g_m heh-tehk; Economics, p.184 |
| 무역 | trade | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | moo-yuhk; Economics, p.184 |
| 가치 | value | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | gah-chee; Economics, p.184 |
| 국경 | border (national) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | gook-gyuhng; World & Culture, p.186 |
| 수도 | capital (city) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | soo-doh; World & Culture, p.186 |
| 문명 | civilization | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | moon-myuhng; World & Culture, p.186 |
| 고대문명 | ancient civilization | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | goh-deh-moon-myuhng; World & Culture, p.186 (printed "antient" in source — likely a typo for "ancient") |
| 동양문명 | Eastern Civilization | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | dohng-yahng-moon-myuhng; World & Culture, p.186 |
| 현대문명 | modern civilization | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | hyuhn-deh-moon-myuhng; World & Culture, p.186 |
| 서양문명 | Western civilization | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | suh-yahng-moon-myuhng; World & Culture, p.186 |
| 의식주 | clothing, food, shelter | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | _ee-sheek-joo; World & Culture, p.186 |
| 대륙 | continents | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | deh-ryook; World & Culture, p.186 |
| 아프리카 | Africa | proper noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | ah-p_-ree-kah; World & Culture, p.186 |
| 아시아 | Asia | proper noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | ah-shee-ah; World & Culture, p.186 |
| 유럽 | Europe | proper noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | yoo-ruhp; World & Culture, p.186 |
| 북미 | North America | proper noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | boong-mee; World & Culture, p.186 |
| 남미 | South America | proper noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | nahm-mee; World & Culture, p.186 |
| 나라; 국가 | countries | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | nah-rah; gook-gah; World & Culture, p.186 |
| 선진국 | advanced countries | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | suhn-jeen-gook; World & Culture, p.186 |
| 개발도상국 | developing countries | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | geh-bahl-doh-sahng-gook; World & Culture, p.186 |
| 후진국 | underdeveloped countries | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | hoo-jeen-gook; World & Culture, p.186 |
| 호주 | Australia | proper noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | hoh-joo; World & Culture > Countries, p.188; footnote: this list selects countries whose Korean names sound notably different from English |
| 벨기에 | Belgium | proper noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | behl-gee-eh; World & Culture > Countries, p.188 |
| 중앙아프리카공화국 | Central African Republic | proper noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | joong-ahng-ah-p_-ree-kah gohng-hwah-gook; World & Culture > Countries, p.188 |
| 중국 | China | proper noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | joong-gook; World & Culture > Countries, p.188 |
| 프랑스 | France | proper noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | p_-rahng-s_; World & Culture > Countries, p.188 |
| 독일 | Germany | proper noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | doh-geel; World & Culture > Countries, p.188 |
| 네덜란드 | Holland | proper noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | neh-duhl-lahn-d_; World & Culture > Countries, p.188 |
| 인도 | India | proper noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | een-doh; World & Culture > Countries, p.188 |
| 이태리 | Italy | proper noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | ee-teh-ree; World & Culture > Countries, p.188 |
| 일본 | Japan | proper noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | eel-bohn; World & Culture > Countries, p.188 |
| 한국 | Korea | proper noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | hahn-gook; World & Culture > Countries, p.188 |
| 북한 | North Korea | proper noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | book-kahn; World & Culture > Countries, p.188 |
| 남한 | South Korea | proper noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | nahm-hahn; World & Culture > Countries, p.188 |
| 남아프리카공화국 | South Africa | proper noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | nahm ah-p_-ree-kah gohng-hwah-gook; World & Culture > Countries, p.188 |
| 스위스 | Switzerland | proper noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | s_-wee-s_; World & Culture > Countries, p.188 |
| 대만 | Taiwan | proper noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | deh-mahn; World & Culture > Countries, p.188 |
| 태국 | Thailand | proper noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | teh-gook; World & Culture > Countries, p.188 |
| 영국 | United Kingdom | proper noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | yuhng-gook; World & Culture > Countries, p.188 |
| 베트남 | Vietnam | proper noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | beh-t_-nahm; World & Culture > Countries, p.188 |
| 미국 | U.S.A. | proper noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | mee-gook; World & Culture > Countries, p.188 |
| 시민 | citizen | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | shee-meen; World & Culture, p.189 |
| 내란 | civil war | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | neh-rahn; World & Culture, p.189 |
| 풍습 | convention (custom) | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | poong-s_p; World & Culture, p.189 |
| 문화 | culture | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | moon-hwah; World & Culture, p.189 |
| 화폐 | currency | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | hwah-peh; World & Culture, p.189 |
| 풍습; 관습 | custom | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | poong-s_p; gwahn-s_p; World & Culture, p.189 |
| 외교 | diplomacy | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | weh-gyo; World & Culture, p.189 (same Hangul as Politics chapter entry) |
| 왕국 | dynasty | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | wahng-gook; World & Culture, p.189 |
| 동양 | East | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | dohng-yahng; World & Culture, p.189 |
| 민족 | ethnic group | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | meen-johk; World & Culture, p.189 |
| 축제 | festival | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | chook-jeh; World & Culture, p.189 |
| 음식 | food | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | _m-sheek; World & Culture, p.189 |
| 지구촌 | global village | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | jee-goo-chohn; World & Culture, p.189 |
| 지구 | globe | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | jee-goo; World & Culture, p.189 |
| 유산 | heritage | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | yoo-sahn; World & Culture, p.189 |
| 역사 | history | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | yuhk-sah; World & Culture, p.189 |
| 국제 | international | adjective | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | gook-jeh; World & Culture, p.189 |
| 토지 | land | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | toh-jee; World & Culture, p.189 (same Hangul as Economics "land") |
| 언어 | language | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | uh-nuh; World & Culture, p.189 |
| 중동 | Middle East | proper noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | joohng-dohng; World & Culture, p.189 |
| 평화 | peace | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | pyuhng-hwah; World & Culture, p.189 |
| 대중문화 | pop culture | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | deh-joong-moon-hwah; World & Culture, p.189 |
| 인구 | population | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | een-goo; World & Culture, p.189 |
| 인종 | race | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | een-johng; World & Culture, p.189 |
| 혁명 | revolution | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | hyuhng-myuhng; World & Culture, p.189 (same Hangul as Politics chapter entry) |
| 의식 | rituals | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | _ee-sheek; World & Culture, p.190 |
| 왕족 | royalty | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | wahng-johk; World & Culture, p.190 |
| 왕 | king | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | wahng; World & Culture, p.190 |
| 왕자 | prince | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | wahng-jah; World & Culture, p.190 |
| 공주 | princess | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | gohng-joo; World & Culture, p.190 |
| 여왕 | queen | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | yuh-wahng; World & Culture, p.190 |
| 감수성; 감각 | sensibility | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | gahm-soot-suhng; gahm-gahk; World & Culture, p.190 |
| 정상회담 | summit meeting | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | juhng-sahng-hweh-dahm; World & Culture, p.190 |
| 전통 | tradition | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | juhn-tohng; World & Culture, p.190 |
| 보물 | treasure | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | boh-mool; World & Culture, p.190 |
| 전쟁 | war | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | juhn-jehng; World & Culture, p.190 |
| 종교전쟁 | religious war | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | johng-gyo-juhn-jehng; World & Culture, p.190 |
| 일차세계대전쟁 | World War I | proper noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | eel-chah seh-geh-deh juhn-jehng; World & Culture, p.190 |
| 이차세계대전쟁 | World War II | proper noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | ee-chah seh-geh-deh juhn-jehng; World & Culture, p.190 |
| 서양 | West | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | suh-yahng; World & Culture, p.190 |
| 세계 | world | noun | core | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | seh-geh; World & Culture, p.190 |
| 인류학 | anthropology | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | eel-lyoo-hahk; Fields of Academics, p.192 |
| 고고학 | archaeology | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | goh-goh-hahk; Fields of Academics, p.192 |
| 동양학 | Asian Studies | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | dohng-yahng-hahk; Fields of Academics, p.192 |
| 천문학 | astronomy | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | chuhn-moon-hahk; Fields of Academics, p.192 |
| 생물학 | biology | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | sehng-mool-hahk; Fields of Academics, p.192 |
| 생화학 | biochemistry | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | sehng-hwah-hahk; Fields of Academics, p.192 |
| 생물정보학 | bioinformatics | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | sehng-mool-juhng-boh-hahk; Fields of Academics, p.192 (printed "bioinfomatics" in source, likely a typo) |
| 생물리학 | biophysics | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | sehng mool-lee-hahk; Fields of Academics, p.192 |
| 미생물학 | microbiology | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | mee-sehng-mool-hahk; Fields of Academics, p.192 |
| 분자생물학 | molecular biology | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | boon-jah-sehng-mool-hahk; Fields of Academics, p.192 |
| 화학 | chemistry | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | hwah-hahk; Fields of Academics, p.192 |
| 언론정보학 | communication/information (studies) | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | uhl-lohn-juhng-boh-hahk; Fields of Academics, p.192 |
| 컴퓨터과학 | computer science | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | kuhm-pyoo-tuh gwah-hahk; Fields of Academics, p.192 |
| 디자인 | design | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | dee-jah-een; Fields of Academics, p.192 |
| 생태학 | ecology | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | sehng-teh-hahk; Fields of Academics, p.192 |
| 경제학 | economics | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | gyuhng-jeh-hahk; Fields of Academics, p.192 |
| 교육학 | education | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | gyo-yook-hahk; Fields of Academics, p.192 |
| 공학 | engineering | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | gohng-hahk; Fields of Academics, p.194 |
| 건축공학 | architecture (engineering) | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | guhn-chook-gohng-hahk; Fields of Academics, p.194 |
| 생의학공학 | biomedical engineering | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | sehng-_ee-hahk-gohng-hahk; Fields of Academics, p.194 |
| 화공학 | chemical engineering | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | hwah-gohng-hahk; Fields of Academics, p.194 |
| 토목공학 | civil engineering | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | toh-mohk-gohng-hahk; Fields of Academics, p.194 |
| 컴퓨터공학 | computer engineering | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | kum-pyoo-tuh-gohng-hahk; Fields of Academics, p.194 |
| 전기공학 | electrical engineering | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | juhn-gee-gohng-hahk; Fields of Academics, p.194 |
| 산업공학 | industrial engineering | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | sah-nuhp-gohng-hahk; Fields of Academics, p.194 |
| 기계공학 | mechanical engineering | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | gee-geh-gohng-hahk; Fields of Academics, p.194 |
| 나노공학 | nano engineering | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | nah-noh-gohng-hahk; Fields of Academics, p.194 |
| 환경학 | environmental studies | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | hwahn-gyuhng-hahk; Fields of Academics, p.194 |
| 미학 | esthetics | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | mee-hahk; Fields of Academics, p.194 |
| 영상학 | film & television, study of | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | yuhng-sahng-hahk; Fields of Academics, p.194 |
| 식품영양학 | food & nutritional science | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | seek-poom-yuhng-yahng-hahk; Fields of Academics, p.194 |
| 유전학 | genetics | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | yoo-juhn-hahk; Fields of Academics, p.194 |
| 지질학 | geology | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | jee-jeel-hahk; Fields of Academics, p.194 |
| 인문과학 | humanities | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | een-moon-gwah-hahk; Fields of Academics, p.194 |
| 언론정보학 | journalism & mass communication | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | uhl-lohn-juhng-boh-hahk; Fields of Academics, p.194 (same Hangul as "communication/information" above) |
| 문헌정보학 | library and information studies | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | moon-huhn-juhng-boh-hahk; Fields of Academics, p.195 |
| 언어학 | linguistics | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | uh-nuh-hahk; Fields of Academics, p.195 |
| 문학 | literature | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | moon-hahk; Fields of Academics, p.195 |
| 중어중문학 | Chinese language & literature | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | joong-uh-joong-moon-hahk; Fields of Academics, p.195; footnote: "L&L" = "Languages & Literatures" |
| 비교문학 | comparative literature | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | bee-gyo-moon-hahk; Fields of Academics, p.195 |
| 영어영문학 | English language & literature | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | yuhng-uh-yuhng-moon-hahk; Fields of Academics, p.195 |
| 불어불문학 | French language & literature | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | bool-uh-bool-moon-hahk; Fields of Academics, p.195 |
| 독어독문학 | German language & literature | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | doh-guh-dohng-moon-hahk; Fields of Academics, p.195 |
| 국어국문학 | Korean language & literature | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | goo-guh-goong-moon-hahk; Fields of Academics, p.195 |
| 노어노문학 | Russian language & literature | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | noh-uh-noh-moon-hahk; Fields of Academics, p.195 |
| 의학 | medicine | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | _ee-hahk; Fields of Academics, p.195 |
| 간호학 | nursing | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | gahn-hoh-hahk; Fields of Academics, p.195 |
| 약학 | pharmacology | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | yahk-hahk; Fields of Academics, p.195 |
| 제약학 | pharmaceutics | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | jeh-yahk-hahk; Fields of Academics, p.195 |
| 정치학 | political science | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | juhng-chee-hahk; Fields of Academics, p.195 |
| 심리학 | psychology | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | sheem-lee-hahk; Fields of Academics, p.195 |
| 종교학 | religion (academic field) | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | johng-gyo-hahk; Fields of Academics, p.195 |
| 사회복지학 | social work; social welfare | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | sah-hweh-bohk-jee-hahk; Fields of Academics, p.195 |
| 사회학 | sociology | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | sah-hweh-hahk; Fields of Academics, p.196 |
| 통계학 | statistics | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | tohng-geh-hahk; Fields of Academics, p.196 |
| 수의학 | veterinary medicine | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | soo-_ee-hahk; Fields of Academics, p.196 |
| 여성학 | women's studies | noun | technical.academic | — | contemporary (source published 2010) | — | — | dictionary | n/a | verified | yuh-suhng-hahk; Fields of Academics, p.196 |
## Grammar points

### Romanization conventions specific to this book

Each entry is glossed as English → Hangul → the book's own pronunciation-based romanization (not
Revised Romanization). Hyphens mark syllable breaks only — they don't indicate spacing in the actual
Hangul. A literal underscore (`_`) is the book's own phonetic symbol for the vowel ㅡ (the book's own
front matter describes it as sounding "like 'e' in russel") — it appears throughout the Notes-column
romanizations below (e.g. 은행 → `_n-hehng`) and is the source's own printed notation, not a
transcription gap.

### Native-Korean vs. Sino-Korean numerals: narrow sub-rules not already captured

Prior established files already cover the general dual-numeral-system-plus-classifier paradigm. Two
narrower rules from this book's own chart/footnotes appear genuinely new:
- **만-based grouping and omission for large Sino-Korean numbers.** Korean groups large numbers by
  powers of 10,000 (만, *mahn*) rather than English's powers of 1,000. A magnitude word (만, 억, etc.)
  is dropped from the spoken reading whenever a smaller place-value digit of the *same* magnitude word
  immediately follows it — e.g. in 123,400,000 the 만 of both 천만 ("ten million") and 백만 ("million")
  is silently dropped, leaving a running digit sequence. Separately, 일 ("one") is never spoken before
  십 ("ten") itself — 10 is just *sheep*, never *"eel sheep,"* though 20/30/etc. do take the leading
  digit (*ee sheep*, *sahm sheep*).
- **Irregular month-reading exceptions.** June and October don't follow the expected
  numeral-plus-월("month") pattern: June is 유월 *yoo-wuhl* (not the expected *육월/"yook-wuhl"*), and
  October is 시월 *shee-wuhl* (not the expected *십월/"sheep-wuhl"*) — a sandhi-like elision exception.
- **Native-numeral bound forms before a classifier.** Five native-Korean numerals (1, 2, 3, 4, 20)
  irregularly shorten when immediately followed by a classifier: 하나→한, 둘→두, 셋→세, 넷→네, 스물→스무
  (e.g. "11 people" = 열 한 명, using the bound 한 rather than the free-standing 하나).

### Kinship terms: referring-vs-addressing distinction

The book explicitly marks each kinship term as usable for both **referring** to a relative (3rd
person) and **addressing** them directly (2nd person), or for referring only — preserved in the table
above as `[referring+addressing]` / `[referring only]`. A few terms have gendered-speaker variants
(오빠/형 "older brother," 언니/누나 "older sister" — the term depends on the *speaker's* own gender, not
the sibling's), and several real-world usage footnotes were captured per-row: younger siblings and
cousins are typically addressed by given name rather than a kinship term; 형제 ("brothers") doubles as
the generic word for "siblings" of any gender mix, while 자매 ("sisters") is exclusively all-female;
조카 ("nephew") is often used ungendered for nieces too; and 와이프 (an English loanword for "wife") is
used informally to refer to either one's own or someone else's wife.

### Senses & Emotions: a 3-way statement / casual-question / honorific-question paradigm

For nearly every sense/emotion concept in this chapter, the book presents three parallel forms: a
plain statement, the identical string read with rising question intonation (a casual question to an
equal/junior), and a distinct honorific verb form (a question addressed to a social superior) — with
an explicit warning never to use the honorific form toward oneself. All three forms are preserved as
separate table rows above, tagged `(statement)` / `(question, casual)` / `(question, honorific)` in
Notes.

### Deictic ("there"-word) distinctions in the Directions chapter

The book's own footnotes distinguish 저기 *juh-gee* ("over there") and 저쪽 *juh-jjohk* ("that side")
as both meaning a place/side **distant from both the speaker and the listener**, while 거기 *guh-gee*
("there") and 그쪽 *g_-jjohk* ("that side") both mean a place/side **near the listener** — a glimpse
of Korean's 이/그/저 (near-speaker/near-listener/distant-from-both) three-way demonstrative system,
though only the 그-series and 저-series terms happened to appear in this book's Directions chapter (no
이-series "near speaker" term was given).

### Morphological/compounding notes captured from footnotes

- **색/색깔 color-suffix rule.** Most color terms optionally take 색 (*sehk*) or 색깔 (*sehk-gahl*)
  appended (e.g. 파랑 "blue" → 파랑색), *except* 오렌지색 ("orange") and 하늘색 ("sky blue"), which
  already lexically contain 색 and cannot take a second one. Without the 색 suffix, 오렌지 alone means
  "an orange" (the fruit) and 하늘 alone means "sky" — the suffix is what derives the color-adjective
  sense from the plain noun.
- **대교 bridge-naming compound.** 대교 *deh-gyo* ("big" + "bridge") is specifically used in the proper
  names of major bridges (e.g. 한강대교 "Han River Bridge"), distinct from the generic/smaller-bridge
  term 다리.
- **Fixed E-W-S-N citation order.** The four cardinal directions are conventionally named in the fixed
  order 동서남북 *dohng-suh-nahm-book* ("east-west-south-north") — unlike English's "north/south/
  east/west" convention.
- **의사 medical-specialty-doctor suffix.** Korean medical specialties take 의사 ("doctor") appended to
  the field name to name that field's doctor (e.g. 내과 "internal medicine" → 내과 의사 "internist") —
  a productive naming pattern, not a fixed list.
- **잔치 feast-naming suffix.** 잔치 ("feast/party") can be appended after any major birth/age-milestone
  term (백일, 돌, 환갑, 칠순, 팔순) to name the feast held for that occasion.
- **Register pairs flagged by the book itself**: 조식/중식/석식 (formal, lit. "morning/noon/evening
  meal") vs. the everyday 아침/점심/저녁 for breakfast/lunch/dinner; 레스토랑 (Western-food restaurants)
  vs. 식당/음식점 (general restaurants) vs. 분식점 (casual, inexpensive Korean eateries); 아줌마/아저씨
  (middle-aged address terms, double-edged connotation — the book advises "with discretion," and notes
  아주머니 as a more polite fuller form of 아줌마; this partially overlaps with
  `established/030_dirty_korean_everyday_slang.md`'s own coverage of 아줌마 as a register-marked,
  sometimes-pejorative address term, confirming the register judgment across two independent sources).
- **Lodging stay-length word order.** When stating a lodging stay length, Korean says the number of
  **nights** (박) before the number of **days** (일) — the reverse of common English phrasing ("2
  nights 3 days," not "3 days 2 nights").
- **Taste/degree intensifiers.** Taste/sensation expressions can be intensified by prefixing 좀 (*johm*,
  "a little") or 아주/너무 (*ah-joo*/*nuh-moo*, "a lot") — a general degree-modifier pattern introduced
  in the Food & Restaurants chapter but not specific to taste words.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes, dialogue
blocks, or explanatory prose. See `../../00_Reference_Extraction_Spec.md`. (Every row above is a
single-word/short-phrase lexical entry with its English gloss and the book's own short pronunciation
guide — standard lexicographic extraction, not prose reproduction; grammar notes above are paraphrased
in this file's own words, not quoted from the source at length.)
