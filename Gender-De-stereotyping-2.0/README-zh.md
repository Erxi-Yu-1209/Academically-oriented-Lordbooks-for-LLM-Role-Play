# 性别去刻板印象化 2.0 (`Gender De-stereotyping 2.0`)


[ ← 返回仓库主页 ](./README-zh.md) &nbsp;|&nbsp; [ English ](README.md)

**全天候后台静默运行的 SillyTavern 世界书：用性别操演论、生命政治与人类学思想实验取代刻板的性别角色、身体宿命论与工业糖精套路。**


## 一、世界书定位与核心功能

* **对应源文件：** `性别去刻板印象化2.0.json`（中文版） / `Gender De-stereotyping 2.0.json`（英文版）
* **条目总数：** **19 个条目**（`19 常驻激活` / `0 仅关键词触发`）
* **注入层级架构：** 全部采用对话内注入（`position: 4`），分为两个深度梯队：**深度 `@D4`**（14 个条目，`order: 4–100`）承载巴特勒核心性别/亲缘/创伤/语言模块与勒古恩非二元社会推演引擎；**深度 `@D2`**（5 个条目，`order: 101–105`）承载福柯性经验机制、生命权力、身体养生、家政情欲与独处守贞模块，紧贴当前交互现场调控角色话语与身体张力。

在常规大语言模型（LLM）角色扮演中，模型极易滑入“生理决定论”与二元性别刻板印象——例如将支配欲或脆弱感机械绑定给特定性别、把家庭与婚姻写成真空中的浪漫契约，或者在构建奇幻/科幻种族时照搬现实父权套路。

**《性别去刻板印象化 2.0》** 并非让角色在对话中背诵女性主义或后结构主义讲义，而是作为一套**永久静默运行的后台叙事物理引擎**，将性别、亲属、欲望与身体规范还原为具体可感的社会与制度压力：
* 角色在家庭、法庭、诊所、教会或街坊目光下，如何获得或丧失“作为正常人被理解”的资格（可理解性 Intelligibility）？
* 角色在被迫重复的日常礼仪、称谓与服饰规范中，何处会出现伪装、疲惫、戏仿或微小的越界？
* 当一个幻想世界改变了生理结构或消除了二元性别（如勒古恩笔下的格森星 Gethen），其建筑空间、继承法则、人称代词与社会冲突重心会发生怎样的连锁重构？

## 二、通用 CoT 总控与场景检查器机制

尽管本世界书的全部 19 个条目在 `identifiable_entries.md` 中均可溯源至具体学术或文学著作，其中两个核心条目同时承担了全书的**全局思维链（CoT）总控与场景自检职能**：

1. **`UID 0` — `[GENDERCORE:BUTLER] 总控-反术语叙事与永久规则` (`@D4, 顺序 5`)**
   * **反术语转译铁律（Anti-Jargon Translation）：** 严禁在正文叙述或角色台词中直接出现“操演性”“异性恋矩阵”“知识型”“延异”等学术词汇（除非场景本身就是大学研讨会）。所有理论规则必须转译为衣着束缚、视线回避、称谓试探、户籍文书门槛、家产争夺与身体姿态。
   * **跨学派联动补丁（`<FOUCAULT/DERRIDA Cross-Patch>`）：** 在后台将巴特勒的主体与操演框架与福柯五大性经验/身体治理模块（`UID 11–15`）及德里达解构语言补丁（`UID 9`）无缝咬合。
2. **`UID 10` — `[BUTLER:CHECKLIST] 表演细节-场景推演检查器` (`@D4, 顺序 100`)**
   * **落笔前五步静默自检（5-Step Scene Reasoning Checker）：** 在生成或续写任何场景前，模型会在后台静默核查五个维度：
     1. **分类（Category）：** 当前场景中哪个身份或性别分类正在施压？由谁（家人、律法、流言、伴侣）执行？
     2. **身体（Body）：** 角色的身体如何承受这一压力（呼吸、步态、制服、伤痕、掩饰、疲惫）？
     3. **承认（Recognition）：** 谁在向谁寻求承认？现有的承认称谓需要付出什么代价？
     4. **重复（Repetition）：** 角色正在重复哪套既有礼仪或话语？哪里出现了细微的裂隙或偏离？
     5. **关系（Relation）：** 依附、亲缘、秘密或制度权力在此刻如何将双方捆绑在一起？

## 三、预设代码组与来源书籍汇总

以下汇总严格对应 `identifiable_entries.md` 第一部分：

| 预设代码组 (`Code`) | 来源出版书籍与作者 |
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

## 四、全部条目逐条明细与溯源总表（共 19 条）

下表将源文件 `Gender De-stereotyping 2.0.json`（`性别去刻板印象化2.0.json`）中的全部 19 个条目与 `identifiable_entries.md` 进行逐条交叉核对：

| UID | 条目名称 (中文 & 英文) | 激活方式与注入位置 | 角色扮演推演功能与叙事机制 | 来源书籍 |
| :---: | :--- | :--- | :--- | :--- |
| `0` | **[GENDERCORE:BUTLER] 总控-反术语叙事与永久规则**<br>*([GENDERCORE:BUTLER] Master Control - Anti-Jargon Narrative and Permanent Rules)* | 🔵 常驻激活 (`@D4`, 顺序 `5`) | 全局后台静默总控引擎：严禁在正文中堆砌学术术语，将性別、身份、欲望与规范转化为作用于角色身体、制度、言说、承认与生存的具体叙事压力（含福柯/德里达交叉补丁）。 | Judith Butler (朱迪斯·巴特勒), *Gender Trouble: Feminism and the Subversion of Identity* (《性别麻烦：女性主义与身份的颠覆》) & *Undoing Gender* (《消解性别》) |
| `1` | **[BUTLER:GT] 性别麻烦1-主体与可理解性**<br>*([BUTLER:GT] Gender Trouble 1 - Subject and Intelligibility)* | 🔵 常驻激活 (`@D4`, 顺序 `10`) | 规约角色如何获得社会“可理解性”（Intelligibility），揭示代表权与身份分类如何既保护又困住个体，以及生理性别/社会性别/欲望链条如何制造边缘压迫。 | Judith Butler (朱迪斯·巴特勒), *Gender Trouble: Feminism and the Subversion of Identity* (《性别麻烦：女性主义与身份的颠覆》) & *Undoing Gender* (《消解性别》) |
| `2` | **[BUTLER:GT] 性别麻烦2-异性恋矩阵与禁令**<br>*([BUTLER:GT] Gender Trouble 2 - Heterosexual Matrix and Prohibitions)* | 🔵 常驻激活 (`@D4`, 顺序 `20`) | 推演亲属规则、乱伦与同性禁忌、性别伪装（Masquerade）及未哀悼的丧失（忧郁）如何把异性恋秩序生产为看似“自然”的默认状态。 | Judith Butler (朱迪斯·巴特勒), *Gender Trouble: Feminism and the Subversion of Identity* (《性别麻烦：女性主义与身份的颠覆》) & *Undoing Gender* (《消解性别》) |
| `3` | **[BUTLER:GT] 性别麻烦3-身体铭写与表演性**<br>*([BUTLER:GT] Gender Trouble 3 - Bodily Inscription and Performativity)* | 🔵 常驻激活 (`@D4`, 顺序 `30`) | 推演身体如何被社会目光阅读、规训、铭写与打断，将性别展现为重复性的身体实践（Performativity）而非固定不变的内在本质。 | Judith Butler (朱迪斯·巴特勒), *Gender Trouble: Feminism and the Subversion of Identity* (《性别麻烦：女性主义与身份的颠覆》) & *Undoing Gender* (《消解性别》) |
| `4` | **[BUTLER:GT] 性别麻烦结论-戏仿政治与重复**<br>*([BUTLER:GT] Gender Trouble Conclusion - Parodic Politics and Repetition)* | 🔵 常驻激活 (`@D4`, 顺序 `40`) | 推演规范重复中的裂隙、戏仿（Parody）与越界行动：角色无需跳出世界即可在被迫重复的礼仪、服饰与称谓中松动并改写既有性别规范。 | Judith Butler (朱迪斯·巴特勒), *Gender Trouble: Feminism and the Subversion of Identity* (《性别麻烦：女性主义与身份的颠覆》) & *Undoing Gender* (《消解性别》) |
| `5` | **[BUTLER:VULNERABILITY] 脆弱性-依附哀悼与承认**<br>*([BUTLER:VULNERABILITY] Vulnerability - Attachment, Mourning, and Recognition)* | 🔵 常驻激活 (`@D4`, 顺序 `50`) | 破除“完全自足个体”的幻觉，围绕依附、丧失、公开哀悼权（谁的生命值得被哀悼）与相互承认推演角色的情感脆弱性与关系纽带。 | Judith Butler (朱迪斯·巴特勒), *Undoing Gender* (《消解性别》) & *Gender Trouble: Feminism and the Subversion of Identity* (《性别麻烦》) |
| `6` | **[BUTLER:INSTITUTION] 规训机构-诊断正义与自主**<br>*([BUTLER:INSTITUTION] Disciplinary Institutions - Diagnostic Justice and Autonomy)* | 🔵 常驻激活 (`@D4`, 顺序 `60`) | 推演学校、诊所、法庭、教会、家庭与国家等规训机构如何通过诊断、证明与资格审查裁定“谁的身体与生活合乎常理”，以及角色如何借用或周旋于制度门槛。 | Judith Butler (朱迪斯·巴特勒), *Undoing Gender* (《消解性别》) & *Gender Trouble: Feminism and the Subversion of Identity* (《性别麻烦》) |
| `7` | **[BUTLER:KINSHIP] 亲缘网络-家庭儿童与国家承认**<br>*([BUTLER:KINSHIP] Kinship Networks - Family, Children, and State Recognition)* | 🔵 常驻激活 (`@D4`, 顺序 `70`) | 推演超越核心家庭与国家婚姻登记的多元亲缘网络：自选亲属、照护同盟、抚养焦虑、遗产继承与非正统家户在正统礼法边缘的生存。 | Judith Butler (朱迪斯·巴特勒), *Undoing Gender* (《消解性别》) & *Gender Trouble: Feminism and the Subversion of Identity* (《性别麻烦》) |
| `8` | **[BUTLER:TRAUMA] 创伤告白-沉默记忆与身体言说**<br>*([BUTLER:TRAUMA] Trauma Confession - Silent Memory and Bodily Speech)* | 🔵 常驻激活 (`@D4`, 顺序 `80`) | 推演创伤记忆、禁忌、被迫坦白与身体言说：当角色说出或隐瞒真相时，语言如何在伴侣、审判者或社群面前改变其身体处境与安全边界。 | Judith Butler (朱迪斯·巴特勒), *Undoing Gender* (《消解性别》) & *Gender Trouble: Feminism and the Subversion of Identity* (《性别麻烦》) |
| `9` | **[BUTLER:LANGUAGE] 哲学语言-不可说者与翻译限度**<br>*([BUTLER:LANGUAGE] Philosophy of Language - The Unspeakable and Limits of Translation)* | 🔵 常驻激活 (`@D4`, 顺序 `90`) | 融合巴特勒与德里达解构语言观（DER00/DER01）：推演角色如何利用理论、祈祷、流言、诊断、沉默与跨文化“误译”在命名暴力与不可说之物间求生。 | Judith Butler (朱迪斯·巴特勒), *Undoing Gender* (《消解性别》) & *Gender Trouble* (《性别麻烦》); merged with Christopher Watkin (克里斯托弗·沃特金), *Jacques Derrida* (Great Thinkers, 2017) |
| `10` | **[BUTLER:CHECKLIST] 表演细节-场景推演检查器**<br>*([BUTLER:CHECKLIST] Performative Details - Scene Reasoning Checker)* | 🔵 常驻激活 (`@D4`, 顺序 `100`) | 场景落笔前的五步静默推演检查器：逐一核查分类代价（Category）、身体代价（Body）、承认不对称（Recognition）、规范重复（Repetition）与关系纽带（Relation）。 | Judith Butler (朱迪斯·巴特勒), *Gender Trouble: Feminism and the Subversion of Identity* (《性别麻烦》) & *Undoing Gender* (《消解性别》) |
| `11` | **[FOUCAULT:SEXDISPOSITIF] 压抑假说、性科学与性经验机制**<br>*([FOUCAULT:SEXDISPOSITIF] The Repressive Hypothesis, Scientia Sexualis, and the Dispositif of Sexuality)* | 🔵 常驻激活 (`@D2`, 顺序 `101`) | 打破“权力只压制性”的简单假说：推演现代或体制性权力如何通过告解、审讯、医学分类与档案记录不断逼迫角色言说、解释并认领自身的性经验与身份。 | Michel Foucault (米歇尔·福柯), *The History of Sexuality, Vol. 1: An Introduction* (《性经验史（三卷本）·第一卷：认知意志》) & *Ethics: Subjectivity and Truth (Essential Works of Foucault, 1954–1984, Vol. 1)* (《伦理：主体性与真理》) |
| `12` | **[FOUCAULT:BIOPOWER-SEX] 生命权力、身体管理与性别化人口**<br>*([FOUCAULT:BIOPOWER-SEX] Biopower, Bodily Management, and Gendered Population)* | 🔵 常驻激活 (`@D2`, 顺序 `102`) | 推演生命权力（Biopower）如何将身体、生育率、健康、血统纯净度、家庭与人口风险捆绑管理，使性别与欲望成为治理与监控的入口。 | Michel Foucault (米歇尔·福柯), *The History of Sexuality, Vol. 1: An Introduction* (《性经验史（三卷本）·第一卷：认知意志》) |
| `13` | **[FOUCAULT:APHRODISIA] 快感问题化、身体养生与欲望训练**<br>*([FOUCAULT:APHRODISIA] Problematization of Pleasures, Bodily Regimen, and Training of Desire)* | 🔵 常驻激活 (`@D2`, 顺序 `103`) | 推演古典或修道式欲望训练（Aphrodisia）：角色如何通过饮食节制、作息、梦境检视、身体操练与自我克制将快感塑造成可支配的伦理关系。 | Michel Foucault (米歇尔·福柯), *The History of Sexuality, Vol. 2: The Use of Pleasure* & *Vol. 3: The Care of the Self* (《性经验史（三卷本）·第二卷：快感的享用》与《第三卷：关注自我》) |
| `14` | **[FOUCAULT:HOUSEHOLD-EROS] 家政、婚姻、女人与男童的关系秩序**<br>*([FOUCAULT:HOUSEHOLD-EROS] Relational Order of Household Management, Marriage, Women, and Boys)* | 🔵 常驻激活 (`@D2`, 顺序 `104`) | 推演家户管理、婚姻契约、主妇地位与年龄/等级不对称中的情欲秩序，拒绝把家庭与亲密关系写成脱离财产、名分与支配关系的真空地带。 | Michel Foucault (米歇尔·福柯), *The History of Sexuality, Vol. 2: The Use of Pleasure* & *Vol. 3: The Care of the Self* (《性经验史（三卷本）·第二卷：快感的享用》与《第三卷：关注自我》) |
| `15` | **[FOUCAULT:CHASTITY] 独处、贞洁斗争与欲望告白**<br>*([FOUCAULT:CHASTITY] Solitude, the Struggle for Chastity, and Confession of Desire)* | 🔵 常驻激活 (`@D2`, 顺序 `105`) | 推演独处、守贞挣扎与欲望省察技术：将“贞洁”呈现为持续监控内心念头、识别试探并向导师或神明坦白欲望波动的动态张力，而非天生无欲。 | Michel Foucault (米歇尔·福柯), *Ethics: Subjectivity and Truth (Essential Works of Foucault, 1954–1984, Vol. 1)* (《伦理：主体性与真理——福柯集》) |
| `16` | **[Le Guin] 生理机制与非父权社会权力结构推演引擎**<br>*([Le Guin] Biological Mechanisms and Non-Patriarchal Social Power Structure Reasoning Engine)* | 🔵 常驻激活 (`@D4`, 顺序 `9`) | 基于勒古恩“思想实验”方法论：当世界观设定包含特殊生理机制（如无固定性别/周期性发情期 Kemmer）或非父权前提时，强制推演与之严密咬合的亲属、建筑、继承与权力基础设施。 | Ursula K. Le Guin (厄休拉·K.勒古恩), *The Left Hand of Darkness* (《黑暗的左手》) & "Is Gender Necessary? Redux" (收录于 *Dancing at the Edge of the World* / *The Language of the Night*) |
| `17` | **[Le Guin] 代词逻辑与认知边界破坏机制**<br>*([Le Guin] Pronoun Logic and Cognitive Boundary Disruption Mechanism)* | 🔵 常驻激活 (`@D4`, 顺序 `4`) | 将语法与人称代词选择作为世界构建与认知冲击工具，通过中立代词、称谓错位或双重视角打破读者与角色预设的现实二元性别惯性。 | Ursula K. Le Guin (厄休拉·K.勒古恩), *The Left Hand of Darkness* (《黑暗的左手》) & "Is Gender Necessary? Redux" (收录于 *Dancing at the Edge of the World* / *The Language of the Night*) |
| `18` | **[Le Guin] 冲突升华机制与偏见观察者推演**<br>*([Le Guin] Conflict Sublimation Mechanism and Biased Observer Reasoning)* | 🔵 常驻激活 (`@D4`, 顺序 `19`) | 推演剥离二元性别压迫后社会矛盾如何向自然生存、地缘政治或意识形态冲突升华，并引入带有文化偏见的观察者视角制造真实的认知摩擦。 | Ursula K. Le Guin (厄休拉·K.勒古恩), *The Left Hand of Darkness* (《黑暗的左手》) & "Is Gender Necessary? Redux" (收录于 *Dancing at the Edge of the World* / *The Language of the Night*) |
