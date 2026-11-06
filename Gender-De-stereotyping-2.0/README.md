# Gender De-stereotyping 2.0 (`性别去刻板印象化2.0`)


[ ← Back to Repository Index ](https://www.google.com/search?q=../README.md) &nbsp;|&nbsp; [ English ](README.md) &nbsp;•&nbsp; [ 简体中文 ](README-zh.md)

**An always-on SillyTavern World Book that replaces formulaic gender, bodily, and relationship clichés with silent sociological, performative, and anthropological reasoning.**

## 1. Overview & Core Function

* **Source Files:** `Gender De-stereotyping 2.0.json` (English) / `性别去刻板印象化2.0.json` (Chinese)
* **Total Entries:** **19 Entries** (`19 Constant` / `0 Keyword-Only`)
* **Injection Architecture:** `position: 4` (In-Chat injection) split across **Depth `@D4`** (14 entries, `order: 4–100`) for foundational gender/kinship/worldbuilding frameworks and **Depth `@D2`** (5 entries, `order: 101–105`) for immediate scene-level Foucauldian discourse and bodily regimen dynamics.

In standard LLM roleplay, models frequently default to biological determinism and rigid romance tropes—treating gender roles as innate essences, reducing physical vulnerability to a gendered weakness, or writing non-traditional relationships as either modern ideological slogans or doomed clichés.

**Gender De-stereotyping 2.0** functions as a **silent, permanently active roleplay physics engine**. Rather than having characters recite gender theory, it forces the LLM to treat gender, kinship, desire, and bodily norms as **historical, institutional, and performative pressures**:
* How does a character become socially "legible" or "illegible" under the gaze of courts, clinics, families, or churches?
* Where does a character's public compliance crack into private exhaustion, parody, or misrecognition?
* If a speculative world alters human biology or abolishes binary gender (as in Ursula K. Le Guin's Gethen), how do architecture, inheritance, pronouns, and geopolitical conflicts reorganize in response?

## 2. General CoT & Master Control Entries

Although all 19 entries in `Gender De-stereotyping 2.0.json` trace their theoretical lineage to specific published works in `identifiable_entries.md`, two entries serve as **global Chain-of-Thought (CoT) and master control gates** for the entire World Book:

1. **`UID 0` — `[GENDERCORE:BUTLER] Master Control - Anti-Jargon Narrative and Permanent Rules` (`@D4, Order 5`)**
   * **Anti-Jargon Translation Layer:** Strictly forbids outputting academic terminology (*performativity, heterosexual matrix, dispositif, différance*) in visible prose unless the scene literally takes place in a university seminar. Every concept must be rendered through clothing, posture, forms of address, hesitation, legal thresholds, and social penalties.
   * **Cross-Module Integration (`<FOUCAULT/DERRIDA Cross-Patch>`):** Links Butler's performativity with Foucault's `SEXDISPOSITIF` / `BIOPOWER-SEX` / `APHRODISIA` / `HOUSEHOLD-EROS` / `CHASTITY` modules and Derrida's deconstructive language patch (`[BUTLER:LANGUAGE]`).
2. **`UID 10` — `[BUTLER:CHECKLIST] Performative Details - Scene Reasoning Checker` (`@D4, Order 100`)**
   * **Silent 5-Step Pre-Scene Checklist:** Before generating or continuing any scene, the LLM silently audits five questions:
     1. **Category:** Which identity or role category is under pressure right now, and who enforces it?
     2. **Body:** How does the body register that pressure (breathing, gaze, dress, injury, concealment, fatigue)?
     3. **Recognition:** Who is seeking recognition from whom, and what does the available term of recognition cost?
     4. **Repetition:** Which habitual ritual or speech act is being repeated—and where does a slight deviation or crack appear?
     5. **Relation:** How do attachment, kinship, secrecy, or institutional power bind the characters together in this moment?

## 3. Source Books Grouped by Pre-Assigned Code

Cross-referenced with Section 1 of `identifiable_entries.md`:

| Code Prefix | Source Book(s) & Author(s) |
| :--- | :--- |
| `[GENDERCORE:BUTLER]` | Judith Butler (朱迪斯·巴特勒), *Gender Trouble: Feminism and the Subversion of Identity* (《性别麻烦：女性主义与身份的颠覆》) & *Undoing Gender* (《消解性别》) |
| `[BUTLER:GT]` | Judith Butler (朱迪斯·巴特勒), *Gender Trouble: Feminism and the Subversion of Identity* (《性别麻烦：女性主义与身份的颠覆》) & *Undoing Gender* (《消解性别》) |
| `[BUTLER:VULNERABILITY]` | Judith Butler (朱迪斯·巴特勒), *Undoing Gender* (《消解性别》) & *Gender Trouble: Feminism and the Subversion of Identity* (《性别麻烦》) |
| `[BUTLER:INSTITUTION]` | Judith Butler (朱迪斯·巴特勒), *Undoing Gender* (《消解性别》) & *Gender Trouble: Feminism and the Subversion of Identity* (《性别麻烦》) |
| `[BUTLER:KINSHIP]` | Judith Butler (朱迪斯·巴特勒), *Undoing Gender* (《消解性别》) & *Gender Trouble: Feminism and the Subversion of Identity* (《性别麻烦》) |
| `[BUTLER:TRAUMA]` | Judith Butler (朱迪斯·巴特勒), *Undoing Gender* (《消解性别》) & *Gender Trouble: Feminism and the Subversion of Identity* (《性别麻烦》) |
| `[BUTLER:LANGUAGE]` | Judith Butler (朱迪斯·巴特勒), *Undoing Gender* (《消解性别》) & *Gender Trouble* (《性别麻烦》); merged with Christopher Watkin (克里斯托弗·沃特金), *Jacques Derrida* (Great Thinkers, 2017) |
| `[BUTLER:CHECKLIST]` | Judith Butler (朱迪斯·巴特勒), *Gender Trouble: Feminism and the Subversion of Identity* (《性别麻烦》) & *Undoing Gender* (《消解性别》) |
| `[FOUCAULT:SEXDISPOSITIF]` | Michel Foucault (米歇尔·福柯), *The History of Sexuality, Vol. 1: An Introduction* (《性经验史（三卷本）·第一卷：认知意志》) & *Ethics: Subjectivity and Truth (Essential Works of Foucault, 1954–1984, Vol. 1)* (《伦理：主体性与真理》) |
| `[FOUCAULT:BIOPOWER-SEX]` | Michel Foucault (米歇尔·福柯), *The History of Sexuality, Vol. 1: An Introduction* (《性经验史（三卷本）·第一卷：认知意志》) |
| `[FOUCAULT:APHRODISIA]` | Michel Foucault (米歇尔·福柯), *The History of Sexuality, Vol. 2: The Use of Pleasure* & *Vol. 3: The Care of the Self* (《性经验史（三卷本）·第二卷：快感的享用》与《第三卷：关注自我》) |
| `[FOUCAULT:HOUSEHOLD-EROS]` | Michel Foucault (米歇尔·福柯), *The History of Sexuality, Vol. 2: The Use of Pleasure* & *Vol. 3: The Care of the Self* (《性经验史（三卷本）·第二卷：快感的享用》与《第三卷：关注自我》) |
| `[FOUCAULT:CHASTITY]` | Michel Foucault (米歇尔·福柯), *Ethics: Subjectivity and Truth (Essential Works of Foucault, 1954–1984, Vol. 1)* (《伦理：主体性与真理——福柯集》) |
| `[Le Guin]` | Ursula K. Le Guin (厄休拉·K.勒古恩), *The Left Hand of Darkness* (《黑暗的左手》) & "Is Gender Necessary? Redux" (收录于 *Dancing at the Edge of the World* / *The Language of the Night*) |

## 4. Complete Entry-by-Entry Reference Table (All 19 Entries)

Every entry below is cross-referenced against `Gender De-stereotyping 2.0.json` (`性别去刻板印象化2.0.json`) and Section 2 of `identifiable_entries.md`:

| UID | Entry Title (English & Chinese) | Activation & Injection | Roleplay Function & Narrative Mechanism | Source Book(s) |
| :---: | :--- | :--- | :--- | :--- |
| `0` | **[GENDERCORE:BUTLER] Master Control - Anti-Jargon Narrative and Permanent Rules**<br>*([GENDERCORE:BUTLER] 总控-反术语叙事与永久规则)* | 🔵 Constant (`@D4`, Order `5`) | This world book is not a lecture module. It is a silent roleplay reasoning engine. Apply every rule as pressure on bodies, institutions, speech, recognition, desire, fear, family, and political survival. | Judith Butler (朱迪斯·巴特勒), *Gender Trouble: Feminism and the Subversion of Identity* (《性别麻烦：女性主义与身份的颠覆》) & *Undoing Gender* (《消解性别》) |
| `1` | **[BUTLER:GT] Gender Trouble 1 - Subject and Intelligibility**<br>*([BUTLER:GT] 性别麻烦1-主体与可理解性)* | 🔵 Constant (`@D4`, Order `10`) | This module governs how a character becomes socially legible, how representation can both protect and trap them, and how the sex/gender/desire chain constrains the world. | Judith Butler (朱迪斯·巴特勒), *Gender Trouble: Feminism and the Subversion of Identity* (《性别麻烦：女性主义与身份的颠覆》) & *Undoing Gender* (《消解性别》) |
| `2` | **[BUTLER:GT] Gender Trouble 2 - Heterosexual Matrix and Prohibitions**<br>*([BUTLER:GT] 性别麻烦2-异性恋矩阵与禁令)* | 🔵 Constant (`@D4`, Order `20`) | This module governs how kinship rules, taboo, masquerade, melancholy, and desire produce apparently natural heterosexual order. | Judith Butler (朱迪斯·巴特勒), *Gender Trouble: Feminism and the Subversion of Identity* (《性别麻烦：女性主义与身份的颠覆》) & *Undoing Gender* (《消解性别》) |
| `3` | **[BUTLER:GT] Gender Trouble 3 - Bodily Inscription and Performativity**<br>*([BUTLER:GT] 性别麻烦3-身体铭写与表演性)* | 🔵 Constant (`@D4`, Order `30`) | This module governs how bodies are read, disciplined, narrated, interrupted, and made politically meaningful. | Judith Butler (朱迪斯·巴特勒), *Gender Trouble: Feminism and the Subversion of Identity* (《性别麻烦：女性主义与身份的颠覆》) & *Undoing Gender* (《消解性别》) |
| `4` | **[BUTLER:GT] Gender Trouble Conclusion - Parodic Politics and Repetition**<br>*([BUTLER:GT] 性别麻烦结论-戏仿政治与重复)* | 🔵 Constant (`@D4`, Order `40`) | This module governs agency, parody, political action, and the possibility of changing norms from within repetition. | Judith Butler (朱迪斯·巴特勒), *Gender Trouble: Feminism and the Subversion of Identity* (《性别麻烦：女性主义与身份的颠覆》) & *Undoing Gender* (《消解性别》) |
| `5` | **[BUTLER:VULNERABILITY] Vulnerability - Attachment, Mourning, and Recognition**<br>*([BUTLER:VULNERABILITY] 脆弱性-依附哀悼与承认)* | 🔵 Constant (`@D4`, Order `50`) | This module governs grief, attachment, recognition, and the illusion of a self-contained character. | Judith Butler (朱迪斯·巴特勒), *Undoing Gender* (《消解性别》) & *Gender Trouble: Feminism and the Subversion of Identity* (《性别麻烦》) |
| `6` | **[BUTLER:INSTITUTION] Disciplinary Institutions - Diagnostic Justice and Autonomy**<br>*([BUTLER:INSTITUTION] 规训机构-诊断正义与自主)* | 🔵 Constant (`@D4`, Order `60`) | This module governs schools, clinics, courts, churches, families, workplaces, states, and any authority that decides whose body or life makes sense. | Judith Butler (朱迪斯·巴特勒), *Undoing Gender* (《消解性别》) & *Gender Trouble: Feminism and the Subversion of Identity* (《性别麻烦》) |
| `7` | **[BUTLER:KINSHIP] Kinship Networks - Family, Children, and State Recognition**<br>*([BUTLER:KINSHIP] 亲缘网络-家庭儿童与国家承认)* | 🔵 Constant (`@D4`, Order `70`) | This module governs family forms, chosen kinship, care networks, children, inheritance, household legitimacy, and state recognition. | Judith Butler (朱迪斯·巴特勒), *Undoing Gender* (《消解性别》) & *Gender Trouble: Feminism and the Subversion of Identity* (《性别麻烦》) |
| `8` | **[BUTLER:TRAUMA] Trauma Confession - Silent Memory and Bodily Speech**<br>*([BUTLER:TRAUMA] 创伤告白-沉默记忆与身体言说)* | 🔵 Constant (`@D4`, Order `80`) | This module governs trauma, taboo, confession, memory, secrecy, and scenes where saying the truth changes the body that says it. | Judith Butler (朱迪斯·巴特勒), *Undoing Gender* (《消解性别》) & *Gender Trouble: Feminism and the Subversion of Identity* (《性别麻烦》) |
| `9` | **[BUTLER:LANGUAGE] Philosophy of Language - The Unspeakable and Limits of Translation**<br>*([BUTLER:LANGUAGE] 哲学语言-不可说者与翻译限度)* | 🔵 Constant (`@D4`, Order `90`) | This module governs how characters use theory, prayer, law, gossip, diagnosis, poetry, silence, and mistranslation to live through difficult realities. | Judith Butler (朱迪斯·巴特勒), *Undoing Gender* (《消解性别》) & *Gender Trouble* (《性别麻烦》); merged with Christopher Watkin (克里斯托弗·沃特金), *Jacques Derrida* (Great Thinkers, 2017) |
| `10` | **[BUTLER:CHECKLIST] Performative Details - Scene Reasoning Checker**<br>*([BUTLER:CHECKLIST] 表演细节-场景推演检查器)* | 🔵 Constant (`@D4`, Order `100`) | Silent five-step pre-scene checklist auditing Category Cost, Bodily Cost, Asymmetric Recognition, Norm Repetition, and Relational Dependency before rendering prose. | Judith Butler (朱迪斯·巴特勒), *Gender Trouble: Feminism and the Subversion of Identity* (《性别麻烦》) & *Undoing Gender* (《消解性别》) |
| `11` | **[FOUCAULT:SEXDISPOSITIF] The Repressive Hypothesis, Scientia Sexualis, and the Dispositif of Sexuality**<br>*([FOUCAULT:SEXDISPOSITIF] 压抑假说、性科学与性经验机制)* | 🔵 Constant (`@D2`, Order `101`) | Modern power does not merely repress sex; it continually demands that characters speak about, explain, classify, and identify with their sexuality. | Michel Foucault (米歇尔·福柯), *The History of Sexuality, Vol. 1: An Introduction* (《性经验史（三卷本）·第一卷：认知意志》) & *Ethics: Subjectivity and Truth (Essential Works of Foucault, 1954–1984, Vol. 1)* (《伦理：主体性与真理》) |
| `12` | **[FOUCAULT:BIOPOWER-SEX] Biopower, Bodily Management, and Gendered Population**<br>*([FOUCAULT:BIOPOWER-SEX] 生命权力、身体管理与性别化人口)* | 🔵 Constant (`@D2`, Order `102`) | When the body, birth rates, health, risk, death, and family are linked together, gender is not merely an identity, but an entry point for population management. | Michel Foucault (米歇尔·福柯), *The History of Sexuality, Vol. 1: An Introduction* (《性经验史（三卷本）·第一卷：认知意志》) |
| `13` | **[FOUCAULT:APHRODISIA] Problematization of Pleasures, Bodily Regimen, and Training of Desire**<br>*([FOUCAULT:APHRODISIA] 快感问题化、身体养生与欲望训练)* | 🔵 Constant (`@D2`, Order `103`) | Desire is not simply released or repressed; it is shaped into a governable relationship to pleasure through diet, dreams, the body, training, and moderation. | Michel Foucault (米歇尔·福柯), *The History of Sexuality, Vol. 2: The Use of Pleasure* & *Vol. 3: The Care of the Self* (《性经验史（三卷本）·第二卷：快感的享用》与《第三卷：关注自我》) |
| `14` | **[FOUCAULT:HOUSEHOLD-EROS] Relational Order of Household Management, Marriage, Women, and Boys**<br>*([FOUCAULT:HOUSEHOLD-EROS] 家政、婚姻、女人与男童的关系秩序)* | 🔵 Constant (`@D2`, Order `104`) | Family and erotic love are not private backgrounds, but ethical fields where status, age, gender, education, and relations of domination intersect. | Michel Foucault (米歇尔·福柯), *The History of Sexuality, Vol. 2: The Use of Pleasure* & *Vol. 3: The Care of the Self* (《性经验史（三卷本）·第二卷：快感的享用》与《第三卷：关注自我》) |
| `15` | **[FOUCAULT:CHASTITY] Solitude, the Struggle for Chastity, and Confession of Desire**<br>*([FOUCAULT:CHASTITY] 独处、贞洁斗争与欲望告白)* | 🔵 Constant (`@D2`, Order `105`) | Chastity is not the absence of desire, but the technology of continuously monitoring desire, naming temptations, and reporting inner movements to a mentor or God. | Michel Foucault (米歇尔·福柯), *Ethics: Subjectivity and Truth (Essential Works of Foucault, 1954–1984, Vol. 1)* (《伦理：主体性与真理——福柯集》) |
| `16` | **[Le Guin] Biological Mechanisms and Non-Patriarchal Social Power Structure Reasoning Engine**<br>*([Le Guin] 生理机制与非父权社会权力结构推演引擎)* | 🔵 Constant (`@D4`, Order `9`) | Transform Le Guin's "thought experiment" methodology into a worldbuilding principle: any alternative biological/gender setting must generate an alternative political and social infrastructure that strictly matches it. | Ursula K. Le Guin (厄休拉·K.勒古恩), *The Left Hand of Darkness* (《黑暗的左手》) & "Is Gender Necessary? Redux" (收录于 *Dancing at the Edge of the World* / *The Language of the Night*) |
| `17` | **[Le Guin] Pronoun Logic and Cognitive Boundary Disruption Mechanism**<br>*([Le Guin] 代词逻辑与认知边界破坏机制)* | 🔵 Constant (`@D4`, Order `4`) | Treat grammar and pronoun selection as foundational worldbuilding acts, strategically using pronouns and vocabulary to disrupt the reader's real-world binary gender cognitive boundaries. | Ursula K. Le Guin (厄休拉·K.勒古恩), *The Left Hand of Darkness* (《黑暗的左手》) & "Is Gender Necessary? Redux" (收录于 *Dancing at the Edge of the World* / *The Language of the Night*) |
| `18` | **[Le Guin] Conflict Sublimation Mechanism and Biased Observer Reasoning**<br>*([Le Guin] 冲突升华机制与偏见观察者推演)* | 🔵 Constant (`@D4`, Order `19`) | Deduce the forms of social conflict after the elimination of binary gender, and forcibly filter this world through the perspective of a culturally biased, flawed narrator to build an epistemological bridge. | Ursula K. Le Guin (厄休拉·K.勒古恩), *The Left Hand of Darkness* (《黑暗的左手》) & "Is Gender Necessary? Redux" (收录于 *Dancing at the Edge of the World* / *The Language of the Night*) |
