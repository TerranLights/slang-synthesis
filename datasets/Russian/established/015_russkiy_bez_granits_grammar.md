# Russian — Established Vocabulary/Grammar: Русский без границ (Russian Without Borders) — Grammar Volume, Full Book

**Source:** Marina Niznik (Israel, project lead), Anna Vinokurova (Germany), Irina Vorontsova (Russian
Federation), Olga Kagan (USA), Anna Cherp (Israel) — authorial collective, published by the Israeli
Association in Support of Children of Repatriates with support from the "Russkiy Mir" Foundation,
2009 ("Russkiy_part2correct.indd", CreationDate 2009-05-10). *Русский без границ: учебник для детей
из русскоговорящих семей* ("Russian Without Borders: a textbook for children from Russian-speaking
families") — Grammar volume, pp. 1–192 (full book). Source file: `source_reference/languages/Russian/
Russian Learning Pack [up-to-date as of 2012]/Vol 3 of 3/26.Русский без границ Grammar.pdf`. This
book's sibling *Literature* volume in the same folder is out of scope for this project and was not
processed.

**Coverage note:** This is a heritage-language grammar reference for children of Russian-speaking
families living abroad — written entirely in Russian, addressed to readers who already speak Russian
natively/semi-natively and need formal grammar instruction (case system, aspect, participles, etc.)
rather than beginner vocabulary. Every grammar point across all nine chapters (Noun, Adjective,
Pronoun, Verb, Adverb, Participle, Gerund, Orthography, Grammar Review) is captured below, with
paraphrased explanations per the coverage rule. The vocabulary table captures paradigm-illustrating
words, declension/conjugation exception lists, irregular forms, idioms/proverbs the source itself
boxes out, and explicit usage-register notes (ты/вы, "ихний" as substandard, "класть" vs. non-standard
"ложить") — not every word appearing in the book's hundreds of fill-in-the-blank drill exercises, most
of which recycle already-common vocabulary (собака, стол, книга, etc.) to drill a grammatical form
rather than introduce new lexical content, per the spec's explicit instruction to skip repeated drills
that don't add new vocabulary/grammar. This is `established/` file 015 for Russian; `established/` was
otherwise empty at the time of this extraction, so no non-redundant-supplement dedup against prior
files was needed.

**PDF-extraction gotchas found:** (1) The book prints acute-accent stress marks (ударение) over
vowels for pedagogical purposes; `pdftotext -layout` renders these as a **combining acute accent
character occasionally displaced onto the wrong side of a letter cluster** (e.g. "существ́ительное"
where the mark should sit over a vowel one position earlier) — this is a cosmetic stress-mark
artifact, not a corruption of letter identity, and was not treated as significant since none of the
extracted vocabulary below depends on stress placement. (2) A handful of decorative/exercise-prompt
words are rendered in what appears to be a **substituted decorative font** that `pdftotext` decodes as
Latin-lookalike glyphs (e.g. "ÒÎÓÌ" for "слон") — this affects only isolated drill-exercise prompt
words (already low-value per the coverage rule) and was not decoded/extracted. (3) The book has a
genuine text layer throughout (no vision-reading was needed for any page). (4) No handwritten
marginalia was found anywhere in this copy.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| падеж (6 cases: именительный, родительный, дательный, винительный, творительный, предложный) | case (nominative, genitive, dative, accusative, instrumental, prepositional) | noun (grammatical term) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | n/a | p.17: full 6-case system introduced with question-word mnemonics (кто?/что?, кого?/чего?, кому?/чему?, кого?/что?, кем?/чем?, о ком?/о чём?) |
| время, имя, мать, дочь | time, name, mother, daughter | noun (declension exceptions) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | n/a | pp.9–71 passim: recurring irregular/exception nouns across the whole case paradigm (время/имя decline with an inserted -ен-; мать/дочь insert -ер-) |
| человек – люди, ребёнок – дети | person–people, child–children | noun (suppletive plural) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | n/a | p.11 ff.: suppletive/irregular plural pairs, recur through every case table as the standard exception set |
| друг – друзья, брат – братья, сын – сыновья, дерево – деревья, стул – стулья | friend/brother/son/tree/chair (irregular -ья plurals) | noun (irregular plural) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | n/a | p.11: "-ья" irregular plural class, distinct from the regular -ы/-и/-а/-я plural rule |
| город – города, дом – дома, адрес – адреса, номер – номера, профессор – профессора, директор – директора, свитер – свитера, вечер – вечера, глаз – глаза | city/house/address/number/professor/director/sweater/evening (stressed -а plural exceptions) | noun (irregular plural) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | n/a | p.11: boxed "ИСКЛЮЧЕНИЯ" (exceptions) list for the regular masculine plural rule |
| ножницы, брюки, сутки, ворота, обои, деньги, духи, чернила, часы, очки | scissors, trousers, 24-hour period, gate, wallpaper, money, perfume, ink, clock/watch, eyeglasses | noun (plurale tantum) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | n/a | p.12: nouns with no singular form; часы/очки flagged as having a genuine sg./pl. semantic split depending on meaning (clock-mechanism vs. hour-unit; eyewear vs. point-in-a-game) |
| темнота, красота, скупость, трусость, молодость, старость, железо, шерсть, пластик, сахар, соль, вода, молодёжь, человечество, интеллигенция, мебель, обувь, посуда | darkness, beauty, stinginess, cowardice, youth, old age, iron, wool, plastic, sugar, salt, water, youth(collective), humanity, intelligentsia, furniture, footwear, dishware | noun (no plural form) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | n/a | p.11: abstract qualities/materials/collective nouns with no plural form |
| делать из мухи слона | to make a mountain out of a molehill (lit. "to make an elephant out of a fly") | idiom | idiomatic | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | n/a | p.23: idiom used as reading passage; sourced by the book to a 2000-year-old Greek phrase via Lucian's "In Praise of the Fly" |
| седьмая вода на киселе, схватывает всё на лету, голова на плечах, в поте лица, заблудиться в трёх соснах | "seventh water on kissel" (very distant relation), picks things up instantly, has a good head on their shoulders, by the sweat of one's brow, to get lost in three pine trees (utterly disoriented) | idiom | idiomatic | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | n/a | p.22–23: idiom cluster drilled together, genitive-case-governing set phrases |
| страх, ссора, яблоня, песня, труд, товарищ, худо, драка | fear, quarrel, apple tree, song, labor, comrade, ill/bad, fight | noun (proverb vocabulary) | core/literary | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | n/a | p.28: genitive-case proverb set (нет друга без..., яблоко от яблони недалеко падает, etc.) |
| Москва слезам не верит; слезами горю не поможешь; дурная голова ногам покоя не даёт; делу время, потехе час | Moscow doesn't believe in tears; tears won't help grief; a foolish head gives the legs no rest; business before pleasure | proverb | literary | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | n/a | p.38: dative-case proverb set |
| благодаря / из-за | thanks to / because of | preposition (register-paired) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | n/a | p.37: минимal pair — благодаря governs dative (positive cause), из-за governs genitive (negative cause) |
| несмотря на / вопреки | despite / contrary to | preposition (register-paired) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | n/a | p.47: вопреки governs dative, несмотря на governs accusative |
| сквозь / через | through (near-synonym prepositions) | preposition | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | n/a | p.46: idioms drilled together — сквозь землю провалиться, сквозь зубы, сквозь пальцы (все governing instrumental/accusative depending on sense) |
| с характером, с головой, с руками оторвут, с корнем вырвать, со странностями, с честью, с горем пополам | strong-willed, has a good head, "they'll tear your hands off" (in high demand), to root out, eccentric, with honor, with great difficulty | idiom (instrumental-case set) | idiomatic | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | n/a | p.52: instrumental-case idiom cluster |
| это не тот / не та / не то | "that's the wrong one" (lit. "not that") | pronoun construction | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | n/a | p.107: fixed НЕ ТОТ construction meaning "incorrect/mistaken", drilled with a full film-plot cloze exercise |
| ты / вы | informal "you" / formal-or-plural "you" | pronoun (T–V register) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | n/a | p.95: explicit register rule — ты for family/close friends/peers, Вы (capitalized in polite written address to one person) for strangers/adults one doesn't know well; also used for any plural addressee |
| "ихний" | "theirs" (non-standard possessive form of "их") | pronoun (proscribed colloquialism) | colloquial | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | n/a | p.98: explicitly flagged as heard in spoken Russian but never used in writing or normative speech — их itself does not decline |
| брать/взять на себя, брать/взять себя в руки, выходить/выйти из себя, держать себя в руках, приходить/прийти в себя, уходить/уйти в себя, читать про себя, мне не по себе, так себе | to take responsibility for, to pull oneself together, to lose one's temper, to keep oneself in check, to come to one's senses, to withdraw into oneself, to read silently, to feel unwell/uneasy, so-so | idiom (reflexive-pronoun set) | idiomatic | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | n/a | p.97: idiom cluster built on the reflexive pronoun себя |
| гнать, держать, смотреть, видеть, дышать, слышать, ненавидеть, обидеть, гнать, терпеть, зависеть, вертеть | to chase/drive, hold, watch, see, breathe, hear, hate, offend, chase, endure, depend, twirl | verb (2nd-conjugation exception mnemonic) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | n/a | p.115–116: the classic 11-verb 2nd-conjugation exception list, presented as a memorization rhyme ("Гнать, держать, смотреть и видеть...") |
| дать, хотеть, есть, бежать | to give, want, eat, run | verb (irregular conjugation) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | n/a | p.121: 4 irregular verbs each mixing 1st/2nd conjugation endings across persons |
| брать – взять, класть – положить, ловить – поймать, говорить – сказать | to take, to put/lay, to catch, to say (suppletive aspect pairs) | verb (suppletive aspectual pair) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | n/a | p.126: aspect pairs whose perfective/imperfective partners have entirely different roots |
| "ложить" | (non-standard for "класть", to put/lay) | verb (proscribed colloquialism) | colloquial | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | n/a | p.126 & p.135: explicitly marked incorrect twice — the verb "ложить" without a prefix does not exist in standard Russian (only prefixed forms like положить, вложить, переложить, проложить exist); "класть" is the correct unprefixed imperfective |
| идти vs. ходить, ехать vs. ездить, бежать vs. бегать, лететь vs. летать, плыть vs. плавать, нести vs. носить, вести vs. водить, везти vs. возить | unidirectional vs. multidirectional motion verb pairs (go-on-foot, go-by-vehicle, run, fly, swim, carry, lead, transport) | verb (motion-verb pair) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | n/a | pp.138–146: full unprefixed motion-verb system; идти/ходить etc. distinguish one-time unidirectional movement from habitual/multidirectional movement; a transport-vs-on-foot distinction (идти/ходить = on foot, ехать/ездить = by vehicle) is layered on top |
| идти куда глаза глядят, ходить вокруг да около, нести чушь, ходить по краю пропасти, водить за нос, пройти сквозь огонь и воду | to wander aimlessly, to beat around the bush, to talk nonsense, to live dangerously, to deceive/lead by the nose, to go through fire and water | idiom (motion-verb set) | idiomatic | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | n/a | p.142: idiom-matching exercise built on motion verbs |
| смеётся тот, кто смеётся последний; кто ищет, тот найдёт; тише едешь – дальше будешь | he who laughs last laughs best; seek and you shall find; slower is faster (softly, softly) | proverb | literary | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | n/a | pp.132, 143: reflexive-verb and motion-verb proverb clusters |
| ненавидеть, негодовать | to hate, to be indignant | verb (не-inseparable exception) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | n/a | p.123: explicit exception list for verbs that are never written with не separately, because they don't exist without не |
| причастие (действительное/страдательное, настоящего/прошедшего времени) | participle (active/passive, present/past) | grammatical term | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | n/a | pp.154–159: participles share verb features (aspect, tense) and adjective features (case/number/gender agreement with the noun they modify) |
| деепричастие | gerund/adverbial participle | grammatical term | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | n/a | p.160: denotes a secondary simultaneous or sequential action, formed from verbs, retaining verbal aspect |
| издавна, изредка, досуха, справа, снова (vs.) впрямь, влево, насухо, начисто, заново, засветло | adverbs with из-/до-/с- (ending in -а) vs. в-/на-/за- (ending in -о) | adverb (spelling-rule pair) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | n/a | p.148: prefix-determined final-vowel spelling rule for adverbs derived from adjectives |
| никогда/некогда, нигде/негде, ниоткуда/неоткуда, никуда/некуда | never (fact) / no time (for); nowhere (fact) / nowhere (available); from nowhere (fact) / nowhere to get it from; to nowhere (fact) / nowhere to go | adverb (negative vs. "nothing available" pair) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | n/a | p.151: minimal pairs contrasting a true negative adverb (accented ни-) with an impersonal-modal "there is no place/time/way to" adverb (unaccented не-) |
| приставка при- / пре- | prefix при- (attachment/proximity/incomplete action) vs. пре- (intensifying, close to "очень" or пере-) | grammatical/orthographic term | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | n/a | p.63: spelling rule with examples пришитый карман, прикрытая дверь, прибрежная зона (при-) vs. пренеприятная новость (пре-); notes that many words' prefix meaning must simply be memorized or checked in a dictionary (прелестный, природные) |
| приставки на з–с (без-/бес-, из-/ис-, воз-/вос-, etc.) | prefixes ending in з/с | orthographic rule | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | n/a | p.63: з before a voiced root-consonant, с before a voiceless one; explicitly notes there is no such thing as a prefix consisting of the single letter з alone |
| Русский без границ vocabulary items used as gender-declension paradigm anchors (собака, невеста, картошка, дождь, календарь, физик, улица, химия, врач, тюльпан, жук, город, любовь, болезнь, ребёнок, девушка, рука, помощь, больной, человек, яблоко, мышь, герой) | dog, bride, potato, rain, calendar, physicist, street, chemistry, doctor, tulip, beetle, city, love, illness, child, girl, hand, help, patient, person, apple, mouse, hero | noun (gender-classification drill set) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | n/a | p.7: representative animate/inanimate and grammatical-gender classification set, illustrating that grammatical gender is independent of biological sex/animacy for many nouns |
| кофе | coffee | noun (gender exception) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | n/a | p.9: explicitly flagged as masculine despite ending in -е (an ending otherwise associated with neuter) |

## Grammar points

### The noun (Имя существительное) and the 6-case system

A noun names an object/entity and answers КТО? (who) for animate or ЧТО? (what) for inanimate
referents (p.6). Russian nouns are classed as собственные (proper, always capitalized) vs.
нарицательные (common), and одушевлённые (animate, answer КТО?) vs. неодушевлённые (inanimate,
answer ЧТО?) (pp.6–7). Grammatical gender (мужской/женский/средний) is largely determined by the
nominative-singular ending, with a soft-sign spelling rule distinguishing masculine (no ь after
sibilants ж/ш/ч/щ) from feminine (ь required) nouns ending in a sibilant (p.9), plus a short list of
memorized -мя neuter exceptions (время, имя) and semantically-arbitrary exceptions (кофе = masculine)
(p.9).

Plural formation follows regular ending rules per gender (masculine -ы/-и, feminine -ы/-и, neuter
-а/-я) with a substantial "Особые случаи" (special cases) and "Исключения" (exceptions) layer:
stress-shifting plurals (город–города), suppletive plurals (человек–люди, ребёнок–дети), and the -ья
plural class (брат–братья, друг–друзья, дерево–деревья) (pp.10–11). Some nouns lack a plural form
entirely (abstract qualities, materials, collective nouns) and some lack a singular form entirely
(plurale tantum: ножницы, брюки, деньги, очки, часы) — часы and очки are noted to have a genuine
semantic split between a mass/instrument sense (singular-form-only referent, "an item") and a
countable sense (p.12).

The book presents the full 6-case paradigm (nominative/genitive/dative/accusative/instrumental/
prepositional) one case at a time (pp.17–56), each with: a full singular/plural declension table
broken out by gender and stem-final consonant/vowel class, an "Исключения" exception box, a
"Запомните!" (remember!) box for special usage rules, and a governing-preposition table. Key points
paraphrased:

- **Prepositional (6th) case** is taught first pedagogically. It always occurs with the prepositions
  о/в/на (об before a word starting with a vowel), and there is a special "where" fixed-expression
  list (в углу, в лесу, в шкафу, на берегу, в саду, в Крыму, на мосту, на лугу, в порту) that takes a
  stressed -у ending rather than the expected -е (p.19).
- **Genitive (2nd) case** governs quantity words (много, мало, немного, сколько, столько, несколько)
  and a large preposition set (из, у, без, от, для, около, далеко/недалеко от, вместо, кроме, после,
  до, среди, возле) (pp.23–30). It is also the case of negated existence ("У меня нет книги").
- **Dative (3rd) case** governs impersonal-state predicates (нравиться, хорошо, плохо, холодно,
  жарко, весело, скучно, можно, нужно) — i.e. the "experiencer" of an impersonal state is dative,
  not nominative (p.34). Also used for age ("Ей 13 лет").
- **Accusative (4th) case** marks the direct object of transitive verbs and destination with
  motion-verb prepositions (в, на, за, через) (pp.39–43).
- **Instrumental (5th) case** marks the means/instrument of an action, and occurs with prepositions с,
  за, под, над, перед, рядом с, вместе с (pp.48–53). Occupation/profession after быть/работать/стать
  takes instrumental ("Он работает врачом").
- **Prepositional again** in review — a full case-and-preposition summary table cross-referencing
  all 6 cases against their governing prepositions and typical question words (pp.53–56).

### The adjective (Имя прилагательное)

An adjective answers КАКОЙ?/КАКАЯ?/КАКОЕ?/КАКИЕ? (what kind/which) and denotes a property of a noun,
agreeing with it in gender, number, and case (p.61). Endings are given in full paradigm tables mirroring
the noun-case tables, with a spelling rule that г/к/х/ж/ш/ч stems take -ие/-ий instead of -ые/-ый in
certain endings (p.62). Adjectives can also answer ЧЕЙ?/ЧЬЯ?/ЧЬЁ?/ЧЬИ? (whose) — possessive adjectives
formed from animal/person names (заячий, лисья, беличье, ослиные, мамины) (pp.65–66).

**Short-form (краткая форма) adjectives**: predicate-only forms (рад, готов, похож, нужен, согласен,
уверен, горд) that do not decline for case, only gender/number, and are often followed by a
case-governed complement (дательный for рад/согласен/похож; instrumental for доволен/горд) (pp.81–84).
A short list of adjectives (остор​ожный/осторожен, страшный/страшен, элегантный/элегантен) illustrates
the semantic difference between full and short forms — full forms tend toward a general/permanent
trait, short forms toward a specific/temporary predicate state (p.84).

**Degrees of comparison**: comparative degree either analytically (более/менее + adjective) or
synthetically (a suffix, often -ее/-ей, with consonant alternations к→ч, г→ж, х→ш, т→ч, д→ж, в→вл,
з→ж: громкий→громче, дорогой→дороже, тихий→тише, твёрдый→твёрже, чистый→чище, богатый→богаче,
дешёвый→дешевле, близкий→ближе) plus a memorized irregular set (маленький→меньше, большой→больше,
хороший→лучше, плохой→хуже, лёгкий→легче, молодой→моложе/младше, старый→старше, далёкий→дальше,
долгий→дольше, ранний→раньше) (p.85). Superlative degree either analytically (самый + adjective) or
synthetically (-ейший/-айший, or "adjective + всех/всего") (p.86).

### The pronoun (Местоимение)

Personal pronouns (я, ты, он/она/оно, мы, вы, они) decline through all 6 cases; 3rd-person pronouns
prepend an н- when governed by a preposition (без него, с ней) (pp.92–93). A special rule: the
preposition с becomes со and the preposition о becomes обо before a pronoun beginning with two
consonants (со мной, обо мне) (p.92).

The **register rule for ты/вы**: ты is used with people one knows well (parents, siblings, friends,
peers); Вы (capitalized in polite written address to one individual) is used with unfamiliar/
lesser-known adults, and always for any plural addressee regardless of familiarity (p.95).

**Reflexive pronoun себя** has no nominative form (it can never be a grammatical subject) and declines
through the remaining 5 cases identically regardless of the person/number of its antecedent (p.96).

**Possessive pronouns** (мой/твой/свой vs. наш/ваш; его/её/их) — a critical distinction: его, её, их
(3rd-person possessives) **never decline** (unlike мой/твой/свой/наш/ваш, which fully decline for
case/gender/number) (p.97). The prescriptive note: "ихний" is heard colloquially but is never used in
writing or normative speech — the correct form is always the invariant их (p.98). **Свой** vs.
его/её/их: свой refers back to the subject of the clause ("Саша читал свою книгу" = Sasha's own
book), while его/её/их refers to someone else's possession, distinguishing whose object is meant
(p.99).

**Interrogative/indefinite pronouns**: кто/что vs. кто-то/что-то (unspecified but existing) vs.
кто-нибудь/что-нибудь (unspecified, possibly hypothetical) (p.104). **Negative pronouns** никто/ничто
decline through all cases (p.105) with a 3-part orthography rule: (1) unstressed ни- when the clause's
verb is itself negated with не ("Никто ничего не знает"); (2) stressed нé- when the clause has an
infinitive instead of a finite verb ("Делать было нечего"); (3) ни/не are written separately from the
pronoun whenever a preposition intervenes ("ни с кем", "не с кем") (p.106).

**Demonstrative pronouns** этот/тот decline fully through all cases and numbers; a fixed idiom "не
тот/не та/не то" means "the wrong one/mistaken" (p.107).

### The verb (Глагол)

A verb denotes action or state and answers "что делать?" (imperfective) or "что сделать?"
(perfective) (p.111).

**Past tense** is formed with -л (+ gender/number suffix) from the infinitive stem; a set of verbs
(спасти, расти, везти, нести, мочь, печь, течь and their prefixed derivatives) do not take -л in the
masculine past form (спас, рос, вёз, нёс, мог, пёк, тёк); идти's past tense is fully suppletive
(шёл/шла/шло/шли), inherited by all its prefixed derivatives (пойти, выйти, зайти, найти, etc.)
(p.113).

**Conjugation (спряжение)**: two conjugation classes, distinguished by their personal-ending vowel
(1st conjugation: -ешь/-ет/-ем/-ете/-ют/-ут; 2nd conjugation: -ишь/-ит/-им/-ите/-ят/-ат). To spell an
unstressed ending correctly, form the infinitive first and check its class (p.115). 2nd conjugation
comprises: all -ить verbs except брить and стелить; 7 verbs in -еть (смотреть, видеть, ненавидеть,
терпеть, обидеть, вертеть, зависеть); and 4 verbs in -ать (гнать, дышать, слышать, держать) — codified
in a memorization rhyme (p.115–116). A dozen additional irregular stem-alternation types are tabulated
(работать→работаю, рисовать→рисую, писать→пишу, видеть→вижу/видишь, класть→кладу, мочь→могу, давать→
даю, мыть→мою, жить→живу, встать→встану, etc.) (pp.118–120).

**Consonant alternations in conjugation**: з/д→ж (видеть→вижу), с→ш (писать→пишу), т→ч (лететь→лечу),
б→бл (любить→люблю), п→пл (купить→куплю), в→вл (нравиться→нравлюсь), к→ч (пеку→печёшь), г→ж (берегу→
бережёшь), с→ш (носить→ношу) (p.122). These same alternations recur in participle formation (p.157).

**Aspect (вид)**: imperfective verbs (что делать?) denote an incomplete action, a process-focused
action, or a repeated/habitual action (co-occurring with words like всегда, иногда, часто, никогда,
обычно, каждый день); perfective verbs (что сделать?) denote a completed action or a sequence of
one-off actions (pp.124–125). Aspect pairs are usually formed by prefixation or suffix change
(делать→сделать, писать→написать) but some pairs are fully suppletive (брать→взять, класть→
положить, ловить→поймать, говорить→сказать) (p.126). The verb "ложить" does not exist without a
prefix in standard Russian — the correct unprefixed imperfective is класть (explicitly re-flagged as
a common error at both p.126 and p.135).

**Future tense**: simple future (perfective verb conjugated directly) vs. compound future (будет +
imperfective infinitive) — the compound form frames an ongoing/durative future action, the simple
form a single completed one (p.129).

**Reflexive verbs** (glagoly with the particle -ся/-сь) — -сь follows a vowel-final ending, -ся
follows a consonant-final ending (pp.130–131). Orthography note: infinitive forms end in -ться, 3rd
person forms end in -тся (учиться vs. учится) — distinguished by asking "что делать?" (infinitive) vs.
"что делает?" (3rd person) (p.130). Some verbs exist only in reflexive form or only in non-reflexive
form: "убираться"/"играться" are flagged as incorrect — one says убирать and играть without -ся
(p.130).

**Imperative (повелительное наклонение)**: formed from the 1st-person-singular present-tense stem
plus -й (vowel stem) or -и (consonant stem), plus -те for the plural/polite form; a set of irregular
imperatives is tabulated (встать→встань, быть→будь, есть→ешь, пить→пей, класть→клади) (pp.134–135).
Verbs are frequently used figuratively rather than literally (дождь идёт, часы идут, лёд молчит)
(p.136).

**Verbs of motion**: unprefixed motion verbs come in unidirectional/multidirectional pairs — идти
(one specific trip in one direction) vs. ходить (repeated/habitual, multiple directions, or a
round-trip already completed) — and similarly ехать/ездить, бежать/бегать, лететь/летать, плыть/
плавать, нести/носить, вести/водить, везти/возить (pp.138–139). Идти/ходить denote movement on foot;
ехать/ездить denote movement by vehicle (p.139). Idiom: transport running on a schedule is described
with идёт even for vehicles ("Автобус идёт в центр") (p.139); one takes a taxi with брать/взять but
travels by bus/train/metro with ездить/ехать (p.140). Prefixed motion verbs (при-/у-/в-/вы-/под-/
от-/пере-/про-/об-/за-/с-) systematically add directional meaning (влетать/вылетать/пролетать/
залетать/подлетать/слетать) (p.143); a rich idiom set is built on prefixed motion verbs (p.143).

### The adverb (Наречие)

An adverb denotes a property of an action (хорошо учиться), a property of an object (шаг вперёд), or a
property of another property (очень высокий) (p.147). Adverbs are formed from adjectives (тихий→тихо),
from relational adjectives with по- (новый→по-новому, французский→по-французски), from directional
adjectives (правый→справа/направо), and from certain nouns (весна→весной) (p.148).

**Spelling rule**: adverbs with the prefixes из-/до-/с- end in -а (издавна, изредка, досуха, справа,
снова); adverbs with в-/на-/за- end in -о (вправо, влево, насухо, начисто, заново, засветло) (p.148).

**Comparative/superlative degree** of -о-adverbs mirrors the adjective system (ярко→ярче→ярче всего/
всех) (p.150).

**Negative vs. impersonal-modal adverbs**: никогда (a true negation: "this will never happen") is
distinct from некогда ("there is no time" — an impersonal-modal sense); similarly нигде/негде,
ниоткуда/неоткуда, никуда/некуда (p.151). НЕ and НИ with adverbs are usually written together
(slitno) (p.151).

### Participles (Причастия)

Participles combine adjective properties (case/number/gender agreement, matching the noun they
modify) with verb properties (tense, aspect) (p.154). **Active participles** are formed from the
3rd-person-plural present-tense stem + -ущ-/-ющ-/-ащ-/-ящ- (present) or from the past-tense stem +
-вш-/-ш- (past; шёл→шедший is the memorized irregular form) (pp.154–155). **Passive participles**
(present: -ем-/-им- from the 1st-person-plural present stem; past: -нн-/-енн-/-т-) undergo the same
consonant alternations as conjugation (оскорбить→оскорблю→оскорблённый; приготовить→приготовлю→
приготовленный; украсить→украшу→украшенный) (pp.156–157). Passive participles are frequently used in
short form (Работа уже сделана. Экзамен сдан.) (p.158). A "который"-clause can systematically be
converted into either an active or a passive participial phrase, drilled extensively across both
sections (pp.155, 158–159).

### Gerunds (Деепричастия)

A gerund denotes a secondary/simultaneous action alongside the main verb of the clause, formed from
verbs and retaining aspect (imperfective vs. perfective) (p.160). A gerund plus its dependents forms
a "деепричастный оборот" (gerund phrase). **Imperfective gerunds** are formed from the 3rd-person-
plural present stem + -я/-а (работать→работая, кричать→крича) (p.161). **Perfective gerunds** are
formed from the masculine past-tense stem + -в/-вши (implied by contrast pairs given at pp. 8225 ff.,
e.g. вспомнив vs. вспоминая) — the perfective gerund marks a completed prior action, the imperfective
gerund a simultaneous ongoing one. Не is written separately from gerunds, as with verbs (p.161, boxed
rule).

### Orthography (Правописание)

Covers, in sequence: unstressed vowels in different parts of a word (о/а, е/и minimal-pair cloze
drills) (pp.166–169); voiced/voiceless consonant spelling via a "check by adding a vowel" method
(арбуз→арбузы) (p.169); the при-/пре- prefix rule (при- for attachment/proximity/incomplete action;
пре- for intensification, close to "очень" or the prefix пере-; many words' prefix choice must simply
be memorized or checked in a dictionary — прелестный, природные) (p.170); the з/с-final-prefix rule
(з before a voiced root consonant, с before voiceless; there is no such thing as a bare "з" prefix)
(p.170); the soft sign (ь) after sibilants (masculine nouns never take it — плащ, гараж, врач;
feminine nouns always do — ночь, вещь, лошадь) (p.170), including in reflexive-verb infinitives
(-ться) (p.171–172); and the НЕ/НИ orthography rule already summarized under Pronoun/Adverb above,
revisited with a large drill set (pp.173–174).

### Grammar review (Повторение грамматики, pp.178–192)

The book's closing chapter is a comprehensive cumulative review — case-ending cloze passages,
"который"-clause-to-participle conversions, "который"-clause-to-gerund conversions, adjective/adverb
formation drills, and proverb completions — recombining every grammar point already introduced
earlier in the book rather than presenting new grammar content; per the coverage rule this section
was reviewed for any genuinely new rule (none found) and its already-boxed "Запомните!" content is
folded into the relevant sections above.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes, dialogue
blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`.
