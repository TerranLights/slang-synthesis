# Russian — Established Vocabulary/Grammar: *Modern Russian Grammar: A Practical Guide* (Part 3 of 4)

**Source:** John Dunn & Shamil Khairov, *Modern Russian Grammar: A Practical Guide* (Routledge, 2009), pp. 481-720 of the PDF (10.4 verb-prefix semantics through 19.2.3 telling the time; printed pages ≈237-361). Siblings: `069_modern_russian_grammar_part1.md` (pp. 1-240), `070_modern_russian_grammar_part2.md` (pp. 241-480), `072_modern_russian_grammar_part4.md` (pp. 721-962).

**Coverage note:** every grammar point and every distinct vocabulary item from this page range, per `../../00_Reference_Extraction_Spec.md`. Repeated drill-style example sentences that introduce no new vocabulary/grammar are skipped. **PDF-extraction gotcha (new variant, not previously catalogued for this book):** this source has a genuine clean text layer for its English prose (`pdftotext` extracts it perfectly), but **every Cyrillic word/example in the entire assigned range is embedded as a small rasterized image (a `pdfimages`-extractable PNG per word/phrase), not as text at all** — `pdftotext`/PyMuPDF return literally nothing where a Cyrillic prefix/word/example sentence sits (confirmed via `page.get_text('rawdict')` returning zero characters at those positions, and via `pdfimages`/`page.get_images()` showing 10+ small embedded images per page). This is a distinct mechanism from the five font-substitution-cipher variants already catalogued for Russian's Wave 1 pass (no ToUnicode mapping exists at all to decode) and from Korean's fixed-offset CJK cipher — it is not decodable via any character-mapping trick. Tesseract was available but **no `rus` language-model traineddata is installed on this system and package installation requires root** (`apt-get`/`sudo` both failed with permission errors), so OCR fallback was not possible. **All Cyrillic content in this file was recovered by direct vision-reading**: pages rendered to PNG at 150dpi via `pdftoppm`, stacked 3-per-composite-image (verified legible at that density; 6-per-image was not), and read via the vision-capable Read tool. Every Cyrillic term in the vocabulary table below is marked `verified` for Vision Reading Confidence because each one appears on-page directly paired with the book's own English translation, which served as an immediate cross-check; no marginalia (handwritten annotation) was found anywhere in this range — the source images are clean typeset print throughout.

**Non-redundant-supplement scope note:** this range spans the end of Part A (grammar) and all of Part B (functional/communicative topics) of the book. The verb-prefix semantic survey (10.4), agreement rules (11.1-11.2), negation system (ch.15), and attitude-suffix system (16.1) overlap in topic with prior established Russian grammars (e.g. `016_big_silver_book_of_russian_verbs_part1.md`, `031_prakticheskaya_grammatika_dlya_inostrannyh_studentov.md`) but go substantially deeper/more systematically in each case — kept in full, with an explicit note at each such section below. The functional-communicative chapters (12-14, 16.2-19) — names/patronymics/address forms, greetings, being/possession, likes/opinions/negotiation formulae, numbers/time — cover territory not extracted from any prior Russian source in this project and are kept in full as new content.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| входить/войти | to go in, come in (on foot) | verb (impf/pf pair) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | 10.4.1 в(о)- movement into |
| въезжать/въехать | to drive in, enter (by vehicle) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.1 |
| вбегать/вбежать | to run in | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.1 |
| вводить/ввести | to bring in, introduce | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.1 |
| вмешиваться/вмешаться | to interfere in | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.1 |
| впускать/впустить | to let in | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.1 |
| вставлять/вставить | to insert | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.1 |
| вступать/вступить | to enter, join (e.g. a party) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.1 |
| включать/включить | to include, switch on | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.1 figurative sense |
| всходить/взойти | to rise (sun) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.2 вз(о)-/вс- upward |
| взлетать/взлететь | to take off (aeroplane) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.2 |
| взбивать/взбить | to whip (cream) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.2 agitation sense |
| взрывать/взорвать | to blow up | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.2 |
| возбуждать/возбудить | to arouse, incite | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.2 воз(о)-/вос- |
| возвышать/возвысить | to raise up | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.2 |
| возмущать/возмутить | to anger, outrage | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.2 |
| возникать/возникнуть | to arise, spring up | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.2 |
| воспитывать/воспитать | to bring up, educate | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.2 |
| восхищаться/восхититься | to admire, be captivated by | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.2 |
| возвращать(ся)/возвратить(ся), вернуть(ся) | to return | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.2 restoring sense |
| восстанавливать/восстановить | to restore | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.2 |
| выходить/выйти | to go/come out, leave (on foot) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.3 вы- outward |
| выбегать/выбежать | to run out from | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.3 |
| выносить/вынести | to carry/bring out; to endure | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.3 |
| выбрасывать/выбросить | to throw out | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.3 |
| вынимать/вынуть | to take out | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.3 |
| выписывать/выписать | to write out, subscribe | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.3 |
| выступать/выступить | to appear publicly, perform | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.3 |
| высказываться/высказаться | to have one's say | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.3 exhaustive sense |
| высыпаться/выспаться | to have a good sleep | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.3 |
| выигрывать/выиграть | to win | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.3 |
| выключать/выключить | to switch off | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.3 |
| доезжать/доехать | to travel as far as | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.4 до- completing |
| доноситься/донестись | to carry (of a sound) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.4 |
| доносить/донести на (+acc.) | to denounce someone | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.4 figurative |
| дописывать/дописать | to finish writing | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.4 |
| достраивать/достроить | to finish building | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.4 |
| дочитывать/дочитать | to finish reading | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.4 |
| доливать/долить | to top up (liquid) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.4 |
| доплачивать/доплатить | to pay a bit extra | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.4 |
| догадываться/догадаться | to guess right | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.4 |
| договариваться/договориться | to come to an agreement | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.4 |
| дожидаться/дождаться | to wait until arrival | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.4 |
| дозваниваться/дозвониться | to get through (phone) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.4 |
| допеваться/допеться (до хрипоты) | to sing until hoarse | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.4 unpleasant-consequence reflexive |
| допиться (св) (до чёртиков) | to drink to seeing pink elephants | verb | colloquial | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.4 idiomatic |
| догуляться (св) | to land oneself in trouble | verb | colloquial | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.4 |
| заходить/зайти | to go behind; to call in, drop by | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.5 за- |
| забивать/забить гол | to score a goal | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.5 |
| забрасывать/забросить шайбу | to score a goal (ice hockey) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.5 |
| засовывать/засунуть | to thrust in | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.5 |
| заворачивать/завернуть | to wrap up | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.5 |
| завязывать/завязать | to tie up | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.5 |
| закрывать/закрыть | to close, shut | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.5 |
| запирать/запереть | to lock | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.5 |
| застёгивать/застегнуть | to button up | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.5 |
| завираться/завраться | to get carried away lying | verb | colloquial | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.5 carried-away sense |
| заговариваться/заговориться | to get carried away talking | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.5 |
| засиживаться/засидеться | to sit too long | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.5 |
| зачитываться/зачитаться | to become absorbed in reading | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.5 |
| задумываться/задуматься | to become pensive | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.5 |
| заговорить | to start talking | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.5 inceptive |
| заплакать | to start crying | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.5 inceptive |
| заболевать/заболеть | to fall ill | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.5 |
| зажигать/зажечь | to ignite | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.5 |
| засыпать/заснуть | to fall asleep | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.5 |
| заблудиться (св) | to lose one's way | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.5 |
| заблуждаться (нсв) | to be mistaken | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.5 |
| забывать/забыть | to forget | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.5 |
| заваривать/заварить | to brew (tea) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.5 |
| загорать/загореть | to sunbathe, tan | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.5 |
| заказывать/заказать | to order (goods/restaurant) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.5 |
| занимать/занять | to occupy, borrow | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.5 |
| записывать/записать | to write down, record | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.5 |
| заполнять/заполнить | to fill in (a form) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.5 |
| запоминать/запомнить | to memorize | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.5 |
| заставлять/заставить | to force, compel | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.5 |
| защищать/защитить | to defend | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.5 |
| избегать/избежать | to avoid | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.6 из(о)-/ис- |
| избирать/избрать | to elect | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.6 |
| извлекать/извлечь | to extract, gain | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.6 |
| издавать/издать | to publish, emit a sound | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.6 |
| исключать/исключить | to exclude, expel | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.6 |
| тратить/истратить | to spend / spend up | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.6 exhaustion sense |
| исписывать/исписать | to fill/cover with writing | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.6 |
| нажимать/нажать (на кнопку) | to press (a button) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.7 на- |
| наклеивать/наклеить | to stick on | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.7 |
| наступать/наступить на (+acc.) | to step, tread on | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.7 |
| наговориться (св) | to talk enough | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.7 satisfaction sense |
| наедаться/наесться | to eat one's fill | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.7 |
| напиваться/напиться | to get drunk | verb | colloquial | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.7 |
| набирать/набрать | to pick up speed, to dial | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.7 |
| намекать/намекнуть | to hint | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.7 |
| настраивать/настроить | to tune | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.7 |
| находить/найти | to find | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.7 |
| недооценивать/недооценить | to underestimate | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.8 недо- insufficiency |
| недосаливать/недосолить | to undersalt | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.8 |
| обходить/обойти | to walk around; go round exhaustively | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.9 о-/об(о)- |
| облетать/облететь | to fly around, orbit | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.9 |
| описывать/описать | to describe | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.9 |
| опрашивать/опросить | to survey opinion | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.9 |
| осматривать/осмотреть | to examine, inspect | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.9 |
| оговариваться/оговориться | to make a slip of the tongue | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.9 accidental-mistake (о-) sense |
| описываться/описаться | to make a slip of the pen | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.9 |
| ослышаться (св) | to mishear | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.9 |
| ошибаться/ошибиться | to make a mistake | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.9 |
| обманывать/обмануть | to deceive | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.9 deliberate-deception (об-) sense |
| обвешивать/обвесить | to give short weight | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.9 |
| обсчитывать/обсчитать | to shortchange | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.9 |
| оглушать/оглушить | to deafen | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.9 transitivizing |
| осложнять/осложнить | to complicate | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.9 |
| обходиться/обойтись без (+gen.) | to do without | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.9 |
| отходить/отойти | to move away from | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.10 от(о)- |
| отставать/отстать | to fall behind, be slow (clock) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.10 |
| отступать/отступить | to retreat | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.10 |
| отвинчивать/отвинтить | to unscrew | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.10 |
| откусывать/откусить | to bite off | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.10 |
| отпиливать/отпилить | to saw off | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.10 |
| отвыкать/отвыкнуть | to get unused to | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.10 |
| отговаривать/отговорить | to dissuade | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.10 |
| отказывать(ся)/отказать(ся) | to refuse | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.10 |
| откладывать/отложить | to postpone | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.10 |
| отменять/отменить | to cancel | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.10 |
| отвечать/ответить | to answer | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.10 responding sense |
| отзываться/отозваться | to respond to a shout/appeal | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.10 |
| откликаться/откликнуться | to respond to a shout/appeal | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.10 |
| переходить/перейти | to go across (on foot) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.11 пере-/пре- |
| переезжать/переехать | to travel across, move house | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.11 |
| переплывать/переплыть | to swim/sail across | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.11 |
| пересекать/пересечь | to cross (a frontier) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.11 |
| перепиливать/перепилить | to saw through | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.11 |
| перерезать/перерезать | to cut through | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.11 |
| перебивать/перебить | to interrupt | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.11 |
| переоценивать/переоценить | to over-estimate | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.11 opp. of недо- |
| переплачивать/переплатить | to pay too much | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.11 |
| перестараться (св) | to try too hard | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.11 excess sense |
| переделывать/переделать | to redo | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.11 |
| передумывать/передумать | to change one's mind | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.11 |
| перезванивать/перезвонить | to phone back | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.11 |
| переписывать/переписать | to rewrite | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.11 |
| перекрикивать/перекричать | to out-shout | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.11 |
| перехитрить (св) | to outwit | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.11 |
| перебрасываться (нсв) | to throw back and forth | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.11 |
| переписываться (нсв) | to correspond (by letter) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.11 |
| перечислять/перечислить | to enumerate | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.11 |
| преграждать/преградить (путь) | to bar the way | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.11 пре- variant |
| прекращать/прекратить | to cease | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.11 |
| превышать/превысить | to exceed | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.11 |
| подкладывать/подложить | to put under (horizontal) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.12 под(о)- |
| подставлять/подставить | to put under (vertical) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.12 |
| подписывать/подписать | to sign | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.12 |
| подчёркивать/подчеркнуть | to underline | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.12 |
| подходить/подойти | to approach | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.12 |
| подвозить/подвезти | to give a lift | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.12 |
| пододвигать/пододвинуть | to bring nearer | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.12 |
| подбрасывать/подбросить | to throw up in the air | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.12 up-from-below sense |
| поддерживать/поддержать | to support | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.12 |
| поднимать/поднять | to raise | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.12 |
| подниматься/подняться | to rise, go up | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.12 |
| подбавлять/подбавить | to add a small amount | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.12 small-quantity sense |
| подогревать/подогреть | to warm up | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.12 |
| подсаливать/подсолить | to add a little salt | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.12 |
| подделывать/подделать | to forge (banknotes) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.12 furtive/illegal sense |
| поджигать/поджечь | to burn down | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.12 |
| подкупать/подкупить | to bribe | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.12 |
| подсказывать/подсказать | to prompt, whisper an answer | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.12 |
| подслушивать/подслушать | to eavesdrop, 'bug' | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.12 |
| предвидеть (нсв) | to predict | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.13 пред(о)- anticipation |
| предполагать/предположить | to assume, presuppose | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.13 |
| предупреждать/предупредить | to warn | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.13 |
| предлагать/предложить | to offer, propose | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.13 |
| представлять/представить | to present, introduce | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.13 |
| приходить/прийти | to come, arrive (on foot) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.14 при- arrival |
| приезжать/приехать | to come, arrive (by vehicle) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.14 |
| приносить/принести | to bring (on foot) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.14 |
| приземляться/приземлиться | to land | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.14 |
| приближаться/приблизиться | to approach | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.14 |
| призывать/призвать | to summon, call up (military) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.14 |
| привлекать/привлечь | to attract | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.14 |
| привязывать/привязать | to tie one thing to another | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.14 attaching sense |
| присоединять/присоединить | to join, unite | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.14 |
| пришивать/пришить | to sew on (a button) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.14 |
| приписывать/приписать | to ascribe; to add to text | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.14 |
| прибавлять/прибавить | to add | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.14 adding sense |
| пристраивать/пристроить | to build on (horizontally) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.14 |
| приболеть (св) | to be off-colour | verb | colloquial | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.14 partial/tentative-action sense |
| привставать/привстать | to half-rise | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.14 |
| прилечь (св) | to lie down for a short time | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.14 short-time sense |
| приостанавливать/приостановить | to suspend for a time | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.14 |
| присаживаться/присесть | to sit for a short time, perch | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.14 |
| прислушиваться/прислушаться к (+dat.) | to listen attentively | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.14 attentiveness sense |
| присматриваться/присмотреться к (+dat.) | to watch attentively, size up | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.14 |
| проходить/пройти | to go through / go past (on foot) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.15 про- |
| проникать/проникнуть | to penetrate | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.15 |
| пропускать/пропустить | to let through; to omit | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.15 |
| протекать/протечь | to leak through | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.15 |
| проезжать/проехать | to drive past; to miss one's stop | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.15 |
| пробалтываться/проболтаться | to let the cat out of the bag | verb | colloquial | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.15 |
| прогуливать/прогулять | to miss class, be absent | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.15 failure sense |
| прозевать (св) (свою очередь) | to miss one's turn (inattention) | verb | colloquial | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.15 |
| проигрывать/проиграть | to lose (a game) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.15 |
| пропивать/пропить (все деньги) | to drink away all one's money | verb | colloquial | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.15 |
| пробегать/пробежать (200 метров) | to cover 200m running | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.15 duration/distance sense |
| проживать/прожить (сорок лет) | to live somewhere for 40 years | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.15 |
| проводить/провести | to conduct (meeting/experiment) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.15 |
| продавать/продать | to sell | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.15 |
| просыпаться/проснуться | to wake up | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.15 |
| расходиться/разойтись | to disperse (intrans.) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.16 раз(о)-/рас- |
| разгонять/разогнать | to disperse (trans.) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.16 |
| расступаться/расступиться | to part, make way | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.16 |
| раздавать/раздать | to give out, distribute | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.16 |
| распределять/распределить | to distribute, allocate | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.16 |
| разбивать/разбить | to break into pieces | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.16 dividing sense |
| разводить(ся)/развести(сь) | to get divorced | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.16 |
| разделять/разделить | to divide up | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.16 |
| разрезать/разрезать | to slice into many pieces | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.16 |
| развязывать/развязать | to untie | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.16 reversing sense |
| раскупоривать/раскупорить | to uncork | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.16 |
| расстёгивать/расстегнуть | to unbutton | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.16 |
| раздумать (св) | to change one's mind | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.16 |
| разлюбить (св) | to stop loving | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.16 |
| разочаровывать/разочаровать | to disenchant, disappoint | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.16 |
| расхотеть (св) | to stop wanting | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.16 |
| разоружать/разоружить | to disarm | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.16 |
| разрабатывать/разработать | to work out, elaborate | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.16 thorough-action sense |
| расспрашивать/расспросить | to question, ask all about | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.16 |
| рассматривать/рассмотреть | to examine thoroughly | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.16 |
| разговориться (св) | to start talking freely | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.16 gaining-intensity reflexive |
| расплакаться (св) | to burst out crying | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.16 |
| рассмеяться (св) | to burst out laughing | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.16 |
| расхохотаться (св) | to burst into uproarious laughter | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.16 |
| сходить/сойти | to come down (on foot) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.17 с(о)- downward |
| сносить/снести | to bring down, demolish | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.17 |
| спрыгивать/спрыгнуть | to jump down | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.17 |
| спускаться/спуститься | to come down, descend | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.17 |
| сбрасывать/сбросить | to shed, throw off | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.17 removal-from-surface sense |
| сбривать/сбрить | to shave off | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.17 |
| свергать/свергнуть | to overthrow | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.17 |
| смывать/смыть | to wash off | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.17 |
| снимать/снять | to take off; to photograph/film | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.17 |
| стирать/стереть | to rub off, erase | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.17 |
| сходиться/сойтись | to congregate, come together | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.17 |
| собирать/собрать | to collect | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.17 |
| связывать/связать | to tie together | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.17 |
| соединять/соединить | to unite | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.17 |
| списывать/списать | to copy | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.17 |
| сдружиться (св) | to become friends | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.17 |
| созваниваться/созвониться | to have a phone conversation | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.17 |
| сопровождать (нсв) | to accompany (a journey) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.17 |
| сочувствовать (нсв) | to sympathize | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.17 |
| сбываться/сбыться | to come true | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.17 |
| сдавать/сдать | to hand in; to take/pass an exam | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.17 |
| сдаваться/сдаться | to give in, surrender | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.17 |
| сдерживать/сдержать | to restrain | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.17 |
| скрывать/скрыть | to hide | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.17 |
| содержать (нсв) | to contain, maintain, keep | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.17 |
| уходить/уйти | to go away (on foot) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.18 у- |
| уезжать/уехать | to go away (by transport) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.18 |
| уносить/унести | to take/carry away | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.18 |
| уклоняться/уклониться | to evade | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.18 |
| убирать/убрать | to clear away, tidy up | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.18 |
| удалять/удалить | to remove | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.18 |
| улучшать/улучшить | to improve | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.18 transitivizing-adjectives sense |
| упрощать/упростить | to simplify | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.18 |
| ухудшать/ухудшить | to make worse | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.18 |
| удочерять/удочерить | to adopt (a daughter) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.18 |
| усыновлять/усыновить | to adopt (a son) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.18 |
| усаживаться/усесться | to sit comfortably | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.18 comfortable-outcome sense |
| устанавливать/установить | to establish, install | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.18 |
| устраивать/устроить | to organize, arrange | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.18 |
| убеждать/убедить | to convince | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.18 accomplished-with-difficulty sense |
| уговаривать/уговорить | to persuade | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 10.4.18 |
| роман | novel | noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 11.1.3 apposition example |
| станция | station | noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 11.1.3 |
| акционер | shareholder | noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 11.1.3 |
| годовое общее собрание | Annual General Meeting | noun phrase | technical | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 11.1.3 |
| конечная станция | terminus | noun phrase | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 11.1.3 |
| паспорт | (internal) passport, ID | noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.0 |
| заграничный паспорт / загранпаспорт | passport for travel abroad | noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.0 |
| удостоверение | identity document | noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.0 |
| студенческий билет | student card | noun phrase | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.0 |
| имя | forename | noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1 |
| отчество | patronymic | noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1 |
| фамилия | surname | noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1 |
| Александр → Саша/Шура/Саня | male forename, full → familiar | proper noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1.1 |
| Алексей → Алёша/Лёша | male forename, full → familiar | proper noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1.1 |
| Анатолий → Толя | male forename, full → familiar | proper noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1.1 |
| Борис → Боря | male forename, full → familiar | proper noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1.1 |
| Валентин → Валя | male forename, full → familiar | proper noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1.1 |
| Василий → Вася | male forename, full → familiar | proper noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1.1 |
| Виктор → Витя | male forename, full → familiar | proper noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1.1 |
| Владимир → Володя/Вова | male forename, full → familiar | proper noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1.1 |
| Геннадий → Гена | male forename, full → familiar | proper noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1.1 |
| Григорий → Гриша | male forename, full → familiar | proper noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1.1 |
| Дмитрий → Дима/Митя | male forename, full → familiar | proper noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1.1 |
| Евгений → Женя | male forename, full → familiar | proper noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1.1 |
| Иван → Ваня | male forename, full → familiar | proper noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1.1 |
| Константин → Костя | male forename, full → familiar | proper noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1.1 |
| Михаил → Миша | male forename, full → familiar | proper noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1.1 |
| Николай → Коля | male forename, full → familiar | proper noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1.1 |
| Павел → Паша | male forename, full → familiar | proper noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1.1 fleeting vowel |
| Пётр → Петя | male forename, full → familiar | proper noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1.1 |
| Сергей → Серёжа | male forename, full → familiar | proper noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1.1 |
| Юрий → Юра | male forename, full → familiar | proper noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1.1 |
| Александра → Саша/Шура | female forename, full → familiar | proper noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1.1 |
| Анастасия → Настя | female forename, full → familiar | proper noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1.1 |
| Анна → Аня | female forename, full → familiar | proper noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1.1 |
| Валентина → Валя | female forename, full → familiar | proper noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1.1 |
| Галина → Галя | female forename, full → familiar | proper noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1.1 |
| Дарья → Даша | female forename, full → familiar | proper noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1.1 |
| Евгения → Женя | female forename, full → familiar | proper noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1.1 |
| Екатерина → Катя | female forename, full → familiar | proper noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1.1 |
| Елена → Лена | female forename, full → familiar | proper noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1.1 |
| Лариса → Лара | female forename, full → familiar | proper noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1.1 |
| Любовь → Люба | female forename, full → familiar | proper noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1.1 no fleeting vowel |
| Людмила → Люда | female forename, full → familiar | proper noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1.1 |
| Мария → Маша | female forename, full → familiar | proper noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1.1 |
| Надежда → Надя | female forename, full → familiar | proper noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1.1 |
| Наталья → Наташа | female forename, full → familiar | proper noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1.1 |
| Ольга → Оля | female forename, full → familiar | proper noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1.1 |
| Светлана → Света | female forename, full → familiar | proper noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1.1 |
| София → Соня | female forename, full → familiar | proper noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1.1 |
| Татьяна → Таня | female forename, full → familiar | proper noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1.1 |
| Михалыч (← Михайлович) | colloquial-reduced patronymic | proper noun | colloquial | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1.2 |
| Сан Саныч (← Александр Александрович) | colloquial-reduced name+patronymic | proper noun | colloquial | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1.2 |
| девичья фамилия | maiden name | noun phrase | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.1.3 |
| гражданство | citizenship, nationality (legal) | noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.5.1 |
| национальность | ethnic identity | noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.5.1 |
| еврей/еврейка | Jew (m/f) | noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.5.1 ethnonym |
| калмык/калмычка | Kalmyk (m/f) | noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.5.1 ethnonym |
| русский/русская | Russian, ethnic (m/f) | noun/adj | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.5.1-12.5.2 |
| татарин/татарка | Tatar (m/f) | noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.5.1 ethnonym |
| чеченец/чеченка | Chechen (m/f) | noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.5.1 ethnonym |
| россиянин/россиянка | citizen of Russia (state) | noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.5.1-12.5.2 |
| российский | Russian (of the state) | adj | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.5.2 |
| должность | position (job) | noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.6.1 |
| звание | rank (military) | noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.6.1 |
| сотрудник | employee, colleague | noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.6.1 |
| подхалтуривать/подхалтурить | to moonlight | verb | colloquial | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.6.1 colloquial synonym of подрабатывать |
| врач | doctor (masc.-only profession noun) | noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.6.2 category 1 |
| секретарь/секретарша | secretary (m/derogatory-informal f) | noun | core/colloquial | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.6.2 category 4, секретарша flagged as potentially derogatory |
| машинист/машинистка | locomotive driver / typist | noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.6.2 'asymmetric' pair, unrelated meanings |
| муж/жена | husband/wife | noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.7 |
| жениться на (+prep.) / выходить замуж за (+acc.) | to get married (man/woman) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.7 |
| ЗАГС | register office (acronym) | noun (acronym) | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.7 |
| гражданский брак | unofficial marriage, civil partnership | noun phrase | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.7 |
| бойфренд | boyfriend | noun | slang | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 12.7 recent English borrowing, mass-media register |
| привет | hi (informal greeting) | interjection | colloquial | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 13.2.2 |
| здорово | hi (informal, male-associated) | interjection | colloquial | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 13.2.2 |
| добро пожаловать | welcome | phrase | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 13.2.3 |
| пока | bye (informal, ты-only) | interjection | colloquial | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 13.2.4 |
| до свидания | goodbye (neutral) | phrase | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 13.2.4 |
| Как сажа бела | ironic 'things are really bad' | idiom | colloquial | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 13.2.5 humorous reversal |
| с лёгким паром | greeting to someone post-bath/steam | phrase | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 13.2.6 |
| ни пуха ни пера | good luck! | idiom | colloquial | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 13.2.6, reply "к чёрту!" |
| прозвище / кличка / ник | nickname (person/animal/internet) | noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 13.3.3 |
| название | name (of a place/institution/title) | noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 13.3.5 |
| господин/госпожа | Mr/Mrs | noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 13.4.3 |
| товарищ | comrade (largely obsolete except military/police rank use) | noun | archaic | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 13.4.3 |
| молодой человек / девушка | young man / young woman (address to a stranger) | noun phrase | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 13.5.1 |
| сударь/сударыня | sir/madam (revived, seen as quaint) | noun | archaic | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 13.5.1 |
| уважаемые | dear, esteemed (group-address adjective) | adj | formal | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 13.5.2 |
| дорогой/милый | dear (letter salutation) | adj | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 13.6.1 |
| с уважением | Yours faithfully (formal letter close) | phrase | formal | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 13.6.1 |
| алло / слушаю | hello (phone) / I'm listening (formal phone answer) | interjection | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 13.6.2 |
| автоответчик | answering machine | noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 13.6.2 |
| мобильник | mobile phone (informal) | noun | colloquial | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 13.6.2 |
| СМС (эсэмэска) | text message | noun (abbrev.) | colloquial | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 13.6.2 |
| являться | to be (formal synonym of быть) | verb | formal | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 14.1.5 |
| представлять собой | to be (formal, +acc.) | verb phrase | formal | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 14.1.5 |
| бывать (нсв) | to tend to be, be frequently | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 14.1.5 |
| оказываться/оказаться | to turn out to be | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 14.1.5 |
| становиться/стать | to become | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 14.1.6 |
| иметься (нсв) | to exist, be present (formal) | verb | formal | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 14.2.2 |
| находиться / расположен | to be located | verb/participle | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 14.2.2 |
| иметь в виду | to have in mind, to mean | verb phrase | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 14.3.2 иметь idiom set |
| иметь право | to have the right | verb phrase | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 14.3.2 |
| иметь значение | to have significance, matter | verb phrase | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 14.3.2 |
| иметь место | to take place, occur | verb phrase | formal | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 14.3.2 |
| обладать / владеть (+instr.) | to own, possess (formal) | verb | formal | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 14.3.3 |
| владеть языком | to have fluent knowledge of a language | verb phrase | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 14.3.3 |
| никогда/никак/нигде/никуда/ниоткуда/нисколько/ничуть | never/in no way/nowhere/(to)nowhere/from nowhere/not in the slightest ×2 | adverb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 15.3.1 negative adverbs |
| никто/ничто(ничего)/никакой | no one/nothing/not any | pronoun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 15.3.2 negative pronouns |
| ничей | no one's | pronoun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 15.3.2; fem. ничья also = 'draw' (sport) |
| никоим образом / ни в коем случае | in no way whatsoever | idiom | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 15.3.2 emphatic negatives |
| ничего (=all right) | OK, not bad (idiomatic) | interjection | colloquial | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 15.3.3 |
| не за что | don't mention it | phrase | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 15.5 set phrase |
| от нечего делать | from want of anything better to do | phrase | colloquial | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 15.5 |
| дальше некуда | that's the limit, can't get worse | idiom | colloquial | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 15.5 |
| не раз / не один | many times / several (pseudo-negative) | idiom | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 15.2.2 |
| дочка, доченька, дочурка (← дочь) | affectionate forms of 'daughter' | noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 16.1.3 |
| сынок, сыночек, сынишка (← сын) | affectionate forms of 'son' | noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 16.1.3 |
| братец, братишка (← брат) | affectionate/familiar-address forms of 'brother' | noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 16.1.3-16.1.4 братец also generic address to a male |
| дедуля (← дедушка) | grandpa (affectionate) | noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 16.1.3 |
| городишко (← город) | wretched/insignificant little town | noun | colloquial | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 16.1.2 negative diminutive |
| голосище (← голос) | booming/aggressive voice | noun | colloquial | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 16.1.2 augmentative |
| дружище (← друг) | mate, old friend | noun | colloquial | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 16.1.2 augmentative but positive |
| Иван → Ваня → Ванька → Ванечка | forename escalating-suffix set | proper noun | core/colloquial | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 16.1.4 close-familiarity vs strong-affection forms |
| Анна → Аня → Анька → Анечка | forename escalating-suffix set | proper noun | core/colloquial | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 16.1.4 |
| нравиться/понравиться | to like, be fond of (+dat. experiencer) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 16.2.1 |
| любить/полюбить | to love, like (transitive) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 16.2.1 |
| обожать (нсв) | to adore, admire | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 16.2.2 |
| влюбляться/влюбиться в (+acc.) | to fall in love with | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 16.2.2 |
| любовник/любовница | lover (sexual partner) | noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 16.2.2 |
| предпочитать/предпочесть | to prefer | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 16.2.3 |
| на мой вкус | to my taste | phrase | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 16.2.3 |
| великолепно/замечательно/здорово/отлично/превосходно/чудесно | wonderful/excellent/great (approval adverbs) | adverb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 16.2.4 |
| годится/так себе/пойдёт/сойдёт | OK, it will do (acceptance) | phrase | colloquial | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 16.2.4 |
| безразлично / всё равно | indifferent, all the same | adverb/phrase | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 16.2.5 |
| начхать / плевать на (+acc.) | to not give a damn about | verb | colloquial | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 16.2.5 |
| ненавидеть/возненавидеть | to hate | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 16.2.5 |
| терпеть не могу / не выношу / на дух не переношу | I can't stand (strong dislike) | idiom | colloquial | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 16.2.5 |
| хотеть/захотеть | to want | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 16.3.1 |
| желать/пожелать (+gen.) | to wish (for) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 16.3.1 |
| хотеться/захотеться | to feel like (impersonal reflexive) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 16.3.2 |
| думать/подумать / полагать / считать/счесть | to think / assume / consider (opinion verbs) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 16.4.1 |
| по моему мнению / по-моему / на мой взгляд | in my opinion | phrase | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 16.4.1 |
| соглашаться/согласиться | to agree | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 16.4.2 |
| возражать/возразить | to object | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 16.4.2 |
| ладно / так и быть / договорились | OK, fine, agreed (informal consent) | phrase | colloquial | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 16.4.2 |
| как бы не так! / ничего подобного! | nothing of the sort! (strong disagreement) | idiom | colloquial | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 16.4.3 |
| конечно / безусловно / несомненно / обязательно | of course / certainly / undoubtedly / definitely | adverb (вводное слово) | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 16.5.1 certainty |
| наверняка / железно / как пить дать | definitely, for sure (informal certainty) | adverb/idiom | colloquial | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 16.5.1 |
| может быть / кажется / вроде (бы) | perhaps / it seems (uncertainty) | phrase (вводное слово) | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 16.5.2 |
| сомневаться (нсв) в (+prep.) | to doubt | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 16.5.2 |
| вряд ли / маловероятно | it's unlikely/improbable | phrase | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 16.5.2 |
| зависеть от (+gen.) / смотря по (+dat.) | to depend on / 'it depends' | verb/phrase | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 16.5.3 |
| ли (particle) | question particle | particle | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 17.1.2 |
| разве / неужели | can it really be that...? (loaded question) | particle | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 17.2.2 |
| неужто | informal variant of неужели | particle | colloquial | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 17.2.2 |
| что ли | tag-question particle | particle | colloquial | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 17.2.3 |
| не так ли? / правда? / скажи? | tag-question phrases ('isn't it', 'don't we') | phrase | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 17.2.3 |
| кто/что/чей/какой/который | who/what/whose/which/which (interrogative pronouns) | pronoun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 17.3.1 |
| что за (+nom.) | what sort of? | phrase | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 17.3.2 |
| сколько | how much, how many | quantity word | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 17.3.3 |
| когда/где/куда/откуда/как/насколько/почему/отчего/зачем | interrogative adverbs (when/where/where-to/whence/how/to-what-extent/why×3) | adverb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 17.3.4 |
| Дед Мороз / Снегурочка | Grandfather Frost / Snow Maiden | proper noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 17.4.1 New Year folklore figures |
| тройка | troika (three-horse sleigh) | noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 17.4.2 cross-ref 8.6.1 |
| надо/нужно/необходимо | one needs to, it is necessary (obligation) | impersonal predicate | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 18.1.1 |
| должен/обязан/следует | must, is obliged to, ought to | adj/impersonal verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 18.1.2 |
| приходиться/прийтись | to have to (necessity via circumstance) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 18.1.3 |
| не обязан | not obliged to | phrase | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 18.1.4 |
| приказывать/приказать / велеть / распоряжаться/распорядиться | to order, arrange for | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 18.2.3 |
| запрещать/запретить | to forbid | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 18.2.4 |
| нельзя | it is forbidden/impossible | impersonal predicate | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 18.2.4 |
| не вздумай / (только) попробуй | don't even think of.../just try (expressive prohibition) | idiom | colloquial | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 18.2.4 |
| пожалуйста / будьте добры / будьте любезны | please (courtesy formulae) | phrase | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 18.3.1 |
| просить/попросить | to ask someone to do something | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 18.3.2 |
| умолять | to beg, plead (strongly-felt request) | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 18.3.2 |
| просьба | request (noun, used impersonally on signs) | noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 18.3.2 |
| давай(те) | let's (exhortation) | particle/verb form | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 18.3.3 |
| извини(те) / прости(те) | sorry, excuse me | phrase | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 18.3.4 |
| виноват! | sorry! (masc.-only exclamation) | interjection | colloquial | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 18.3.4 |
| сожалеть / к сожалению / жаль | to regret / unfortunately / sorry | verb/adverb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 18.3.4 |
| юбилей | round-figure birthday (jubilee) | noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 18.3.4 |
| советовать/посоветовать / рекомендовать/порекомендовать | to advise / recommend | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 18.4 |
| можно | it is possible/allowed (permission) | impersonal predicate | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 18.5 |
| с твоего/вашего разрешения | with your permission | phrase | formal | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 18.5 |
| раз (in counting) | 'once' — substitutes for один when counting | numeral | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 19.1.1 |
| равно/равняется | equals, is equal to | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 19.1 arithmetic |
| прибавить/вычесть/умножить/разделить | to add/subtract/multiply/divide | verb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 19.1 arithmetic |
| дважды/трижды/четырежды | twice/three times/four times | adverb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 19.1.3 |
| однажды | once, at some time (or other) | adverb | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 19.1.3 |
| по (distributive) | each, apiece | preposition | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 19.1.4 |
| Который час? / Сколько времени? | what time is it? | phrase | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 19.2.1 |
| утра/дня/вечера/ночи | in the morning/afternoon/evening/night (time-of-day genitive markers) | noun (gen.) | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 19.2.2 |
| полдень/полночь | midday/midnight | noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 19.2.2 |
| четверть / половина | quarter / half (of the hour) | noun | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 19.2.3 |
| без (+gen., time) | to (the hour) — minutes-to construction | preposition | core | — | contemporary (2009) | — | — | grammar_reference | n/a | verified | 19.2.3 |

## Grammar points

### 10.4 Verb-prefix semantic survey (в-, вз-/вс-/воз-/вос-, вы-, до-, за-, из-/ис-, на-, недо-, о-/об-, от(о)-, пере-/пре-, под(о)-, пред(о)-, при-, про-, раз(о)-/рас-, с(о)-, у-)
The book gives a systematic, prefix-by-prefix semantic breakdown of all major Russian spatial/directional verbal prefixes, listing both the core spatial meaning of each prefix and its figurative/idiomatic extensions (e.g. вы- covers literal 'movement out' but also 'satisfaction/completion' senses like высыпаться 'to sleep one's fill'; за- covers 'movement behind' but also inceptive senses like заплакать 'to start crying' and 'excess/carried-away' reflexives like заговариваться). See the Vocabulary table above for the full prefix-by-prefix verb inventory (pp.481-503, printed pp.237-259). **Non-redundant-supplement note:** kept in full — more systematically comparative across all 18 prefixes in one place than prior established Russian sources, which tend to treat individual prefixes piecemeal.

### 11.1-11.2 Agreement (pp.505-524, printed pp.249-268)
Noun-phrase agreement: pronouns/adjectives/один agree with their noun in number/gender/case; a numeral два/три/четыре forces genitive singular on the noun with more case flexibility on any modifying adjective. Apposition normally matches the case of what it describes, except names of literary works/companies/stations/geographical places preceded by a defining term (роман, ОАО, станция, город), which stay nominative. Subject-verb agreement: person/number in non-past, number/gender in past; вы always takes plural; кто always takes masc. sg. Collective nouns are grammatically singular (unlike English); большинство+gen.pl. often takes a plural verb; numeral/quantity-word subjects can take either singular or plural depending on word order, animacy, and verb semantics; masculine-only profession nouns referring to a woman keep a masculine attributive adjective but a feminine past-tense verb.

### 12. Establishing identity — names, ages, addresses, citizenship, occupations, marital status (pp.525-585, printed pp.259-293)
Full coverage of the Russian three-part name system (имя-отчество-фамилия), patronymic-formation rules by father's-forename ending (5 patterns plus colloquial-reduction rules), the 5 surname-declension-pattern types, foreign-name transliteration conventions, age expressions (dative-marked person + numeral+лет, and adjectival forms like двадцатилетний), postal-address conventions and abbreviations, floor-numbering offset vs. British English, registration/прописка terminology, the россиянин/русский citizenship-vs-ethnicity distinction, the 6-category occupation-and-gender-noun typology, and marital-status vocabulary. **Non-redundant-supplement note:** kept in full — onomastic/sociocultural content not previously extracted from any Russian source in this project.

### 13. Establishing contact — address forms, greetings, introductions, letters, telephone (pp.585-609, printed pp.293-305)
ты-vs-вы usage norms; the full greeting/farewell/polite-enquiry repertoire including special-occasion salutations (по+instr. and genitive-object patterns); introduction formulae; asking/giving names (зовут+acc., название for inanimate objects); the four-tier address-form system for friends/acquaintances (familiar forename < forename+patronymic < surname alone < patronymic alone, each tied to ты/вы and to specific social relationships); addressing strangers (молодой человек/девушка as the only unmarked options; problems addressing older strangers); letter-writing conventions (dorogой/уважаемый registers, formal/informal closings); telephone etiquette vocabulary.

### 14. Being, becoming and possession (pp.585-609, printed pp.293-305)
быть's missing present tense (dash convention); nominative-vs-instrumental rules for noun/adjective complements of быть across tenses, with word-order principles governing which noun is instrumental when the complement precedes the subject; short-form-adjective triggers; синонимы быть (являться, представлять собой, заключаться в, бывать, оказываться) each restricted to specific formal/aspectual nuances; existence/location verbs (иметься, находиться/расположен, стоять, лежать, сидеть); the у(+gen.)+быть possession construction vs. formal иметь (with its idiom-set) vs. обладать/владеть for valuable-property possession. **Non-redundant-supplement note:** kept in full — functional-grammar content orthogonal to prior case/paradigm-focused Russian extractions.

### 15. Negation (pp.609-633, printed pp.305-317)
Simple не-negation and its proclitic stress-shift on был; special genitive-based negation of existence/possession sentences (нет replacing есть); partial negation (не placed before just the negated word/phrase); "pseudo-negatives" (не раз, не один — negative in form, not meaning); the full negative-adverb/negative-pronoun/ни-particle system (никогда etc., никто/ничто/никакой/ничей/никой, ни...ни, emphatic ни+не); genitive-vs-accusative rules for direct objects of negated transitive verbs; and the нечего/некогда/негде/некуда/неоткуда/незачем negative-existential paradigm (the negative counterpart of possessive/existential есть-sentences, in practice more frequent than the positive). **Non-redundant-supplement note:** kept in full — substantially more systematic than the basic не-negation typically covered elsewhere in this project's Russian sources.

### 16. Expressing attitudes — suffixes, likes/dislikes, wishes, opinions, certainty (pp.633-670, printed pp.317-335)
Diminutive-suffix system: positive-connotation suffixes (softening commands/requests, or genuine affection) vs. negative-connotation suffixes (both diminutive ‑ишк(о/а) and augmentative ‑ищ(е)); family-member-noun diminutives; the two-suffix (‑к‑ vs ‑очк‑/‑еньк‑) forename-modification system with full worked tables for ~25 common names; suffixed adjectives/adverbs. Likes/loves (нравиться vs любить, their inverted subject/object roles), stronger-liking and hate vocabulary, preference/approval/indifference/disagreement formulae, wish-expressing constructions (хотеть/захотеть vs желать/пожелать vs the impersonal reflexive хотеться/захотеться vs the particle бы), and a full вводные-слова inventory for certainty/probability/uncertainty/doubt, plus the зависеть от / смотря по 'it depends' construction.

### 17. Asking questions (pp.670-690, printed pp.335-346)
Neutral yes/no questions via intonation-shift or the enclitic particle ли; negative questions as a politeness/tentativeness device (not a presupposition marker, unlike English); loaded questions with разве/неужели (differing in whether they imply speaker disbelief vs. surprise); tag questions (что ли and the не так ли?-type fixed tags); question-word categories (interrogative pronouns/quantity word/adverbs) with кто/что's special это-construction and такой-intensification; and rhetorical questions (expressing attitude, soliciting sympathy, issuing a challenge, or softening a request).

### 18. Obligation, instructions, requests, advice, permission (pp.690-715, printed pp.346-357)
Obligation gradient: надо/нужно (all registers) < необходимо (formal) < должен/обязан (agreeing predicative adjectives) < следует (impersonal) < приходиться/прийтись (circumstance-driven necessity); lack-of-obligation constructions distinguished from prohibition. Instructions/prohibitions via the imperative, the infinitive (in 4 specific registers: military/formal, official notices, product labels, recipes), reporting verbs (приказывать, велеть, распоряжаться), and запрещать/нельзя for prohibition. A full courtesy-formula inventory for requests (пожалуйста through сделайте одолжение), просить/умолять/просьба, давай(те) exhortations, apology formulae (извини(те)/прости(те), viноват!, regret vocabulary), advice verbs, and можно/permission phrasing.

### 19.1-19.2 Numbers, arithmetic, distribution, and telling the time (pp.715-720, printed pp.357-361)
Counting conventions (раз substituting for один; counting up vs. down); two constructions for stating arithmetic (равно/равняется+dative vs. an infinitive-based conditional construction with будет/получится); special multiplication-table adverb forms (дважды...десятью) distinct from but overlapping with general 'n times' adverbs, and однажды for 'once' in the general sense; по-distribution (dative with singular/тысяча-class nouns, accusative otherwise); asking the time (Который час?/Сколько времени?); whole-hour telling with the 24-hour clock (routine in Russian official/broadcast contexts) and genitive-marked parts of the day (утра/дня/вечера/ночи) standing in for a.m./p.m.; the "traditional" past/half/to-the-hour telling system introduced here (continues into the next page range, covered by `072_modern_russian_grammar_part4.md`).

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes, dialogue blocks, or explanatory prose. See `../../00_Reference_Extraction_Spec.md`. All illustrative Russian sentences quoted above are short, single-example citations paired with their own English gloss, used to demonstrate a specific grammar point — never a bulk reproduction of a source vocabulary box or dialogue passage.
