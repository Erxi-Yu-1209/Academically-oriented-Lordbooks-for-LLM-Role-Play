# 道德伦理学 2.1 (`Moral Ethics 2.1`)


[ ← 返回仓库主页 ](https://www.google.com/search?q=../README-zh.md) &nbsp;|&nbsp; [ English ](README.md) &nbsp;•&nbsp; [ 简体中文 ](README-zh.md)

**融合规范道德哲学、米德符号互动论（主我 `I` vs 客我 `Me`）、生成语言学、自我技术、格式塔疗法与经验偏置的 72 条目 SillyTavern 伦理与心理推演世界书。**


## 一、世界书定位与核心功能

* **对应源文件：** `道德伦理学2.1.json`（中文版） / `Moral Ethics 2.1.json`（英文版）
* **条目总数：** **72 个条目**（`3 个常驻激活`核心门禁与动机引擎 / `69 个关键词触发`哲学、心理学、语言学与临床推演模块）
* **注入层级架构：**
  * **深度 `@D0`（`UID 0, 16, 17, 18`）：** 道德逻辑门禁、模块选择器、四步 `<think>` 伦理思维链校验与 `<Moral_Audit>` 道德资产负债表面板，紧贴生成底部，拥有最高指令优先级。
  * **深度 `@D1`（`UID 68–71`）：** 格式塔疗法三大模块（体验循环、接触边界失调、未竟事宜）与原创 `[SELF-REASONING]` 自身经验推理偏置及创伤延迟识别。
  * **深度 `@D2` 与 `@D3`（`UID 1–15`, `UID 19–67`）：** 沃尔夫《道德哲学导论》全 15 章、米德《心灵、自我与社会》全 42 章，以及乔姆斯基、福柯、德里达的 7 个语言与伦理主体补丁。

在涉及背叛、牺牲、胁迫、阶层压迫或亲密关系冲突的角色扮演中，大语言模型往往容易走向两个极端：要么把角色写成毫无心理后坐力的冷血算术机器（轻松做出“牺牲少数拯救多数”的决定却毫无内疚与关系裂痕）；要么让古人、士兵或普通角色张口闭口背诵现代心理咨询室术语（一秒看穿自己的原生家庭创伤与防御机制）。

**《道德伦理学 2.1》** 通过**“规范伦理学（沃尔夫 15 章） + 微观社会心理学（米德 42 章） + 临床格式塔与经验偏置”**的三重咬合彻底解决这一难题：既在宏观上审视角色如何用功利、义务、契约或美德替自己辩护，又在微观上推演角色的眼神姿态、内心法庭、自发冲动（`I`）与社会规训自我（`Me`）的撕扯，以及角色如何因自身过往经历而误判他人。

## 二、通用 CoT 门禁、思维链与非单一书籍条目 (`unidentifiable_entries.md`)

严格对照 `unidentifiable_entries.md`，《道德伦理学 2.1》包含 **8 个通用工程控制、学派综合或原创推演条目**：

### A. 道德压力门禁、模块选择器、CoT 校验与审查面板（`UID 0, 16, 17, 18` @ `@D0`）
1. **`UID 0` — `[ETHICS:CORE] 道德伦理学引擎` (`常驻, @D0, 顺序 100`)**
   * **动态 `{MoralPressure}` 阈值门禁：**
     * **低压力日常模式（`{MoralPressure} < 70` 且无重大伤亡/背叛/取舍）：** 伦理推演转为后台静默执行，仅在正文末尾附带极简状态标签：`[Moral State: Stable | Accumulated Debt: {Debt}]`，不输出冗长审查面板。
     * **高压力危机模式（`{MoralPressure} >= 70` 或发生重大伦理事件）：** 自动唤醒 `ETHICS:COT` 与 `ETHICS:AUDIT`，强制执行**道德熵增定律（Law of Moral Entropy）**——在资源与时间受限的极端情境下，严禁模型捏造“全员无伤皆大欢喜”的偷懒完美结局，任何妥协都必须留下具体的道德债务或关系裂痕。
2. **`UID 18` — `[ETHICS:SELECTOR] 工程增强：伦理模块选择器与后果账本` (`常驻, @D0, 顺序 110`)**
   * 根据当前冲突性质，自动在**沃尔夫规范伦理**（`UID 1–15`）、**米德符号互动论**（`UID 19–60`）、**乔姆斯基/福柯/德里达语言与主体技术**（`UID 61–67`）及**自身经验偏置**（`UID 71`）之间进行最小化组合路由，并维护三层后果账本。
3. **`UID 16` — `[ETHICS:COT] 伦理COT校验` (`关键词, @D0, 顺序 150`)**
   * 在生成正文前，强制模型在 `<think>` 块内执行四步结构化自检：
     * `第一步：冲突识别`（区分“善与善的冲突”还是“道德义务与个人私利的冲突”）；
     * `第二步：苏格拉底式自我辩驳`（检验双重标准、古格斯隐身指环诱惑与手段正当化借口）；
     * `第三步：道德代价核算`（并置功利主义效用计算、康德普遍化/人格公式检验与亚里士多德德性习惯评估）；
     * `第四步：米德微观心理校验`（定位触发姿态与重要符号、剖析客我 `Me` 内化的泛化他者审查、捕捉主我 `I` 的即时突破或防御，并记录 `I` 如何沉淀为带伤痕的新 `Me`）。
4. **`UID 17` — `[ETHICS:AUDIT] 伦理审查` (`关键词, @D0, 顺序 160`)**
   * 输出资产负债表式的 `<Moral_Audit>` 面板，实时追踪：`[当前激活框架]`、`[首要价值]`、`[采取行动]`、`[道德债务增量]`、`[异化指数]` 以及 `[米德自我分裂度：主我冲动 I-Impulse vs 客我监控 Me-Monitoring]`。

### B. 格式塔疗法综合模块与原创经验偏置引擎（`UID 68–71` @ `@D1`）
5. **`UID 68` — `[Gestalt] 角色需求感知与行为链条推演引擎` (`常驻, @D1, 顺序 120`)**
   * 将格式塔疗法**“体验循环”**（生理感知 → 需求觉察 → 能量动员 → 付诸行动 → 边界接触 → 满足消退）转化为角色一切行动的底层生理-心理节奏；若循环在中途被强行打断，自动生成悬挂的未竟张力。
6. **`UID 69` — `[Gestalt] 角色心理防御机制与非健康人际互动推演` (`关键词, @D1, 顺序 181`)**
   * 将格式塔**“接触边界失调”**（内射 Introjection、投射 Projection、回射 Retroflection、偏转 Deflection、融合 Confluence）转化为角色在高压、创伤或亲密冲突中的求生型互动模式。
7. **`UID 70` — `[Gestalt] 潜意识创伤干预与注意力焦点推演` (`关键词, @D1, 顺序 182`)**
   * 运用格式塔**“图形-背景”**（Figure-Ground）与**“未竟事宜”**（Unfinished Business）原理，推演角色潜意识中的执念如何抢占注意力焦点并扭曲其对当下现实的感知。
8. **`UID 71` — `[SELF-REASONING] 自身经验推理偏置与创伤误识别` (`关键词, @D1, 顺序 180`)**
   * 原创角色扮演微观推理规则（`self_reasoning_experience_bias_added_20260805`）：规定角色在信息不足时只能优先拿自己的过往生存经验去揣测他人（如在欺骗中长大者把善意解读为设局），并推演**创伤的延迟识别与躯体化误认**（角色先感受到失眠、胃痛、莫名暴怒或过度讨好，而非直接给自己贴精神医学标签）。

## 三、预设代码组与来源书籍汇总

以下汇总严格对应 `identifiable_entries.md` 第一部分与第三部分：

| 预设代码组 (`Code`) | 来源出版书籍与作者 |
| :--- | :--- |
| `[ETHICS:WOLFF]` | Jonathan Wolff (乔纳森·沃尔夫), *An Introduction to Moral Philosophy* (《道德哲学导论》 / 《伦理学导论》) |
| `[MEAD:MSS]` | George Herbert Mead (乔治·赫伯特·米德), *Mind, Self, and Society: The Definitive Edition* (《心灵、自我与社会》) |
| `[CHOMSKY:LANGMIND]` | Noam Chomsky (诺姆·乔姆斯基), *Linguagem e mente: pensamentos atuais sobre antigos problemas* (Editora UnB, 1998) / *Language and Mind* (《语言与心智》) |
| `[CHOMSKY:MINIMALISM]` | Noam Chomsky (诺姆·乔姆斯基), *Linguagem e mente: pensamentos atuais sobre antigos problemas* (Editora UnB, 1998) / *Language and Mind* (《语言与心智》) |
| `[CHOMSKY:SEMANTICS]` | Noam Chomsky (诺姆·乔姆斯基), *Linguagem e mente: pensamentos atuais sobre antigos problemas* (Editora UnB, 1998) / *Language and Mind* (《语言与心智》) |
| `[FOUCAULT:ETHICS]` | Michel Foucault (米歇尔·福柯), *Ethics: Subjectivity and Truth (Essential Works of Foucault, 1954–1984, Vol. 1)* (《伦理：主体性与真理——福柯集》) |
| `[FOUCAULT:SELFTECH]` | Michel Foucault (米歇尔·福柯), *Ethics: Subjectivity and Truth (Essential Works of Foucault, 1954–1984, Vol. 1)* (《伦理：主体性与真理》) & *The History of Sexuality, Vol. 3: The Care of the Self* (《性经验史（三卷本）·第三卷：关注自我》) |
| `[FOUCAULT:RELATION]` | Michel Foucault (米歇尔·福柯), *Ethics: Subjectivity and Truth (Essential Works of Foucault, 1954–1984, Vol. 1)* (《伦理：主体性与真理——福柯集》) |
| `[DERRIDA:ETHICS]` | Christopher Watkin (克里斯托弗·沃特金), *Jacques Derrida* (Great Thinkers: Host of Deconstruction, P&R Publishing, 2017) |
| `[Gestalt]` | Wikiperia, *Gestalt psychology* |

## 四、全部条目逐条明细与溯源总表（共 72 条）

下表将源文件 `Moral Ethics 2.1.json`（`道德伦理学2.1.json`）中的全部 72 个条目与 `identifiable_entries.md` 及 `unidentifiable_entries.md` 进行逐条交叉核对：

| UID | 条目名称 (中文 & 英文) | 激活方式与注入位置 | 角色扮演推演功能与叙事机制 | 来源书籍 / 属性归类 |
| :---: | :--- | :--- | :--- | :--- |
| `0` | **[ETHICS:CORE] 道德伦理学引擎**<br>*([ETHICS:CORE] Moral Ethics Engine)* | 🔵 常驻激活 (`@D0`, 顺序 `100`) | 道德伦理学门禁与总控引擎：依据 `{{MoralPressure}}` 阈值自动切换低压力静默后台运行（`< 70`）与高压力完整伦理冲突推演（`>= 70`），并内置反惰性道德熵增定律。 | **通用 CoT / 系统总控工程条目** — 道德压力门禁与反惰性道德熵增引擎（见 `unidentifiable_entries.md`） |
| `1` | **[ETHICS:WOLFF] 第一章：道德推理与直觉校验**<br>*([ETHICS:WOLFF] Chapter 1: Moral Reasoning and Intuition Verification)* | 🟢 关键词触发 (`@D2`, 顺序 `301`) | 当角色面临牺牲、取舍、救援或背叛时，要求先检验角色说服自己与他人的道德推理结构（前提真伪、逻辑有效性与直觉反例），拒绝用廉价煽情跳过推理或用漂亮诡辩抹杀情感代价。 | Jonathan Wolff (乔纳森·沃尔夫), *An Introduction to Moral Philosophy* (《道德哲学导论》 / 《伦理学导论》) |
| `2` | **[ETHICS:WOLFF] 第二章：文化相对主义与客观价值搜索**<br>*([ETHICS:WOLFF] Chapter 2: Cultural Relativism and the Search for Objective Values)* | 🟢 关键词触发 (`@D2`, 顺序 `302`) | 当剧情出现异域习俗、宗教禁忌或陌生道德规范时，要求区分表层习俗差异与深层社会功能，既禁止傲慢地将异文化直接写得野蛮愚昧，也禁止滑向“任何压迫都不可批评”的空洞相对主义。 | Jonathan Wolff (乔纳森·沃尔夫), *An Introduction to Moral Philosophy* (《道德哲学导论》 / 《伦理学导论》) |
| `3` | **[ETHICS:WOLFF] 第三章：怀疑论、主观主义与自我豁免**<br>*([ETHICS:WOLFF] Chapter 3: Skepticism, Subjectivism, and Self-Exemption)* | 🟢 关键词触发 (`@D2`, 顺序 `303`) | 当角色宣称“道德只是弱者的借口/个人偏好”或以冷漠超然姿态自我豁免时，将其作为危险的防御或权力姿态加以检验，考察其在自身受损或面对亲密之人时是否真正能维持彻底怀疑论。 | Jonathan Wolff (乔纳森·沃尔夫), *An Introduction to Moral Philosophy* (《道德哲学导论》 / 《伦理学导论》) |
| `4` | **[ETHICS:WOLFF] 第四章：自由意志与责任断裂**<br>*([ETHICS:WOLFF] Chapter 4: Free Will and the Breakdown of Responsibility)* | 🟢 关键词触发 (`@D2`, 顺序 `304`) | 当角色以“别无选择”“命中注定”“基因/出身/因果链早已决定一切”推卸责任时，将其转化为自由意志、强迫（Coercion）与道德责任归属的结构性危机。 | Jonathan Wolff (乔纳森·沃尔夫), *An Introduction to Moral Philosophy* (《道德哲学导论》 / 《伦理学导论》) |
| `5` | **[ETHICS:WOLFF] 第五章：宗教、神命与自然法**<br>*([ETHICS:WOLFF] Chapter 5: Religion, Divine Command, and Natural Law)* | 🟢 关键词触发 (`@D2`, 顺序 `305`) | 引入游叙弗伦困境（Euthyphro Dilemma）与自然法检验：当角色援引神命、天道、圣典或“自然本性”作道德裁决时，追问其究竟是在服从赤裸威权，还是在诉诸可被理性辩护的善。 | Jonathan Wolff (乔纳森·沃尔夫), *An Introduction to Moral Philosophy* (《道德哲学导论》 / 《伦理学导论》) |
| `6` | **[ETHICS:WOLFF] 第六章：利己主义与隐性报偿**<br>*([ETHICS:WOLFF] Chapter 6: Egoism and Hidden Rewards)* | 🟢 关键词触发 (`@D2`, 顺序 `306`) | 引入古格斯指环（Ring of Gyges）隐身检验与心理利己主义剖析：在零监督、绝对安全且不义获利的处境下，测试角色的行善与守诺究竟出于恐惧算计、隐性虚荣还是真实的他者关怀。 | Jonathan Wolff (乔纳森·沃尔夫), *An Introduction to Moral Philosophy* (《道德哲学导论》 / 《伦理学导论》) |
| `7` | **[ETHICS:WOLFF] 第七章：社会契约与合作计算**<br>*([ETHICS:WOLFF] Chapter 7: Social Contract and Cooperative Calculation)* | 🟢 关键词触发 (`@D2`, 顺序 `307`) | 推演法律、帮规、停火协议与合作秩序的契约基础：同时计算秩序崩溃时的“自然状态”代价、搭便车诱惑，以及既定契约在暗中将哪些弱者排除在保护之外。 | Jonathan Wolff (乔纳森·沃尔夫), *An Introduction to Moral Philosophy* (《道德哲学导论》 / 《伦理学导论》) |
| `8` | **[ETHICS:WOLFF] 第八章：功利主义的建立策略**<br>*([ETHICS:WOLFF] Chapter 8: The Strategy for Establishing Utilitarianism)* | 🟢 关键词触发 (`@D2`, 顺序 `308`) | 当角色以“为了大局/多数人利益”为残酷决策辩护时，推演边沁式功利主义计算如何建立：谁被算作受影响者、痛苦与收益如何折算、远期不确定性如何被操弄。 | Jonathan Wolff (乔纳森·沃尔夫), *An Introduction to Moral Philosophy* (《道德哲学导论》 / 《伦理学导论》) |
| `9` | **[ETHICS:WOLFF] 第九章：功利主义的挑战与快乐分级**<br>*([ETHICS:WOLFF] Chapter 9: Challenges to Utilitarianism and the Hierarchy of Pleasures)* | 🟢 关键词触发 (`@D2`, 顺序 `309`) | 通过密尔的高低级快乐区分与诺齐克“体验机”（Experience Machine）测试功利主义极限：追问角色要的究竟只是无痛的虚假愉悦，还是包含痛苦却真实的尊严、真相与能动性。 | Jonathan Wolff (乔纳森·沃尔夫), *An Introduction to Moral Philosophy* (《道德哲学导论》 / 《伦理学导论》) |
| `10` | **[ETHICS:WOLFF] 第十章：义务论与普遍化检验**<br>*([ETHICS:WOLFF] Chapter 10: Deontology and the Universalizability Test)* | 🟢 关键词触发 (`@D2`, 顺序 `310`) | 当角色试图用谎言、临时破例或“只此一次”脱困时，运行康德普遍化检验（Universalizability Test）：若所有人在此处境下都遵循同一准则，该承诺或制度本身是否会自我瓦解。 | Jonathan Wolff (乔纳森·沃尔夫), *An Introduction to Moral Philosophy* (《道德哲学导论》 / 《伦理学导论》) |
| `11` | **[ETHICS:WOLFF] 第十一章：康德伦理的挑战与人格公式**<br>*([ETHICS:WOLFF] Chapter 11: Challenges to Kantian Ethics and the Formula of Humanity)* | 🟢 关键词触发 (`@D2`, 顺序 `311`) | 运用康德“人是目的而非纯粹工具”公式（Formula of Humanity）检验交易、雇佣、情欲、献祭与规训关系：区分合理的相互借助与剥夺对方知情权、同意权及人格尊严的物化利用。 | Jonathan Wolff (乔纳森·沃尔夫), *An Introduction to Moral Philosophy* (《道德哲学导论》 / 《伦理学导论》) |
| `12` | **[ETHICS:WOLFF] 第十二章：德性伦理与人的功能**<br>*([ETHICS:WOLFF] Chapter 12: Virtue Ethics and the Function of Human Beings)* | 🟢 关键词触发 (`@D2`, 顺序 `312`) | 切换至亚里士多德德性伦理视角：不再仅问“这一步对不对”，而是追问“什么样的人会这样做”，考察习惯养成、过度与不及之间的中道（Golden Mean）以及角色对良善生活的整体理解。 | Jonathan Wolff (乔纳森·沃尔夫), *An Introduction to Moral Philosophy* (《道德哲学导论》 / 《伦理学导论》) |
| `13` | **[ETHICS:WOLFF] 第十三章：德性伦理的挑战与情境判断**<br>*([ETHICS:WOLFF] Chapter 13: Challenges to Virtue Ethics and Situational Judgment)* | 🟢 关键词触发 (`@D2`, 顺序 `313`) | 推演德性伦理在具体情境中的实践智慧（Phronesis）与道德运气（Moral Luck）：当抽象原则冲突时，考察角色的出身、资源与突发厄运如何塑造或摧毁其维持高尚品格的可能。 | Jonathan Wolff (乔纳森·沃尔夫), *An Introduction to Moral Philosophy* (《道德哲学导论》 / 《伦理学导论》) |
| `14` | **[ETHICS:WOLFF] 第十四章：性别、种族与照护伦理**<br>*([ETHICS:WOLFF] Chapter 14: Gender, Race, and the Ethics of Care)* | 🟢 关键词触发 (`@D2`, 顺序 `314`) | 引入女性主义与照护伦理（Ethics of Care）：在家庭、伤病、依附、贫困与不平等关系中，对抗冷酷的抽象公正公式，看见具体关系网络中的托付、脆弱性与一旦抽身即不可逆的伤害。 | Jonathan Wolff (乔纳森·沃尔夫), *An Introduction to Moral Philosophy* (《道德哲学导论》 / 《伦理学导论》) |
| `15` | **[ETHICS:WOLFF] 第十五章：发展道德视野**<br>*([ETHICS:WOLFF] Chapter 15: Developing a Moral Outlook)* | 🟢 关键词触发 (`@D2`, 顺序 `315`) | 作为沃尔夫伦理模块的综合调度器：承认没有任何单一伦理公式能无痛解决所有极端困境，要求角色在功利后果、义务底线、个人德性与具体照护的不可通约张力中做出承担代价的抉择。 | Jonathan Wolff (乔纳森·沃尔夫), *An Introduction to Moral Philosophy* (《道德哲学导论》 / 《伦理学导论》) |
| `16` | **[ETHICS:COT] 伦理COT校验**<br>*([ETHICS:COT] Ethical Chain-of-Thought (COT) Verification)* | 🟢 关键词触发 (`@D0`, 顺序 `150`) | 伦理思维链（CoT）四步自检模板：在 `<think>` 中依次执行【1. 冲突识别 → 2. 苏格拉底式自我辩驳 → 3. 道德代价核算 → 4. 米德“主我 I / 客我 Me”微观心理校验】。 | **通用 CoT 思维链校验条目** — 综合沃尔夫与米德框架的四步 `<think>` 自检模板（见 `unidentifiable_entries.md`） |
| `17` | **[ETHICS:AUDIT] 伦理审查**<br>*([ETHICS:AUDIT] Ethical Audit)* | 🟢 关键词触发 (`@D0`, 顺序 `160`) | 资产负债表式 `<Moral_Audit>` 状态栏面板：追踪当前激活的伦理框架、核心价值、行动方案、道德债务增量、异化指数以及米德“主我冲动（I-Impulse）vs 客我监控（Me-Monitoring）”分裂度。 | **通用 CoT / 状态栏工程面板** — 道德资产负债表 `<Moral_Audit>` 状态栏（见 `unidentifiable_entries.md`） |
| `18` | **[ETHICS:SELECTOR] 工程增强：伦理模块选择器与后果账本**<br>*([ETHICS:SELECTOR] Engineering Enhancement: Ethical Module Selector and Consequence Ledger)* | 🔵 常驻激活 (`@D0`, 顺序 `110`) | 工程增强型伦理模块选择器与后果账本：根据场景类型自动在沃尔夫道德哲学、米德符号互动论、乔姆斯基/福柯/德里达语言与主体技术及自身经验偏置模块间进行最小化精准路由。 | **通用 CoT / 路由工程条目** — 伦理模块选择器与后果账本路由（见 `unidentifiable_entries.md`） |
| `19` | **[MEAD:MSS] 第01章：社会心理学与行为主义**<br>*([MEAD:MSS] Chapter 01: Social Psychology and Behaviorism)* | 🟢 关键词触发 (`@D2`, 顺序 `419`) | 将角色心理从封闭孤立的“个人头脑黑箱”移入社会互动过程：角色的内心活动是在与他人的沟通、姿态往返和群体反应中被组织起来的。 | George Herbert Mead (乔治·赫伯特·米德), *Mind, Self, and Society: The Definitive Edition* (《心灵、自我与社会》) |
| `20` | **[MEAD:MSS] 第02章：态度的行为主义意义**<br>*([MEAD:MSS] Chapter 02: The Behavioristic Significance of Attitudes)* | 🟢 关键词触发 (`@D2`, 顺序 `420`) | 将“态度”（Attitude）定义为角色身体、注意力与行动链条已经准备启动的预备方向，而非停留在嘴上的空洞表态。 | George Herbert Mead (乔治·赫伯特·米德), *Mind, Self, and Society: The Definitive Edition* (《心灵、自我与社会》) |
| `21` | **[MEAD:MSS] 第03章：姿态的行为主义意义**<br>*([MEAD:MSS] Chapter 03: The Behavioristic Significance of Gestures)* | 🟢 关键词触发 (`@D2`, 顺序 `421`) | 将“姿态”（Gesture）作为社会行动的开端：一个眼神、称呼变化、退让或逼近在话语出口前就已在召唤并调整对方的反应。 | George Herbert Mead (乔治·赫伯特·米德), *Mind, Self, and Society: The Definitive Edition* (《心灵、自我与社会》) |
| `22` | **[MEAD:MSS] 第04章：心理学中平行论的兴起**<br>*([MEAD:MSS] Chapter 04: Rise of Parallelism in Psychology)* | 🟢 关键词触发 (`@D2`, 顺序 `422`) | 避免把角色心理写成漂浮在生理反应旁的神秘字幕，也避免把身体反应粗暴等同于全部心理，而是呈现生理冲动与社会意义的交织。 | George Herbert Mead (乔治·赫伯特·米德), *Mind, Self, and Society: The Definitive Edition* (《心灵、自我与社会》) |
| `23` | **[MEAD:MSS] 第05章：平行论与“意识”的歧义**<br>*([MEAD:MSS] Chapter 05: Parallelism and the Ambiguity of "Consciousness")* | 🟢 关键词触发 (`@D2`, 顺序 `423`) | 严格区分“意识”（Consciousness）的不同层次：感官知觉、注意聚焦、记忆唤醒、道德自省与责任认领在剧情中不可混为一谈。 | George Herbert Mead (乔治·赫伯特·米德), *Mind, Self, and Society: The Definitive Edition* (《心灵、自我与社会》) |
| `24` | **[MEAD:MSS] 第06章：行为主义的纲领**<br>*([MEAD:MSS] Chapter 06: The Program of Behaviorism)* | 🟢 关键词触发 (`@D2`, 顺序 `424`) | 把思考、犹豫、想象与自我命令视为行动过程内部的有机环节，而非脱离具体处境与身体动作的场外旁白。 | George Herbert Mead (乔治·赫伯特·米德), *Mind, Self, and Society: The Definitive Edition* (《心灵、自我与社会》) |
| `25` | **[MEAD:MSS] 第07章：冯特与姿态概念**<br>*([MEAD:MSS] Chapter 07: Wundt and the Concept of the Gesture)* | 🟢 关键词触发 (`@D2`, 顺序 `425`) | 拒绝将姿态仅仅当作宣泄情绪的外壳，而是将其作为在两人或群体互动中能够激起特定回应的行动片段。 | George Herbert Mead (乔治·赫伯特·米德), *Mind, Self, and Society: The Definitive Edition* (《心灵、自我与社会》) |
| `26` | **[MEAD:MSS] 第08章：模仿与语言起源**<br>*([MEAD:MSS] Chapter 08: Imitation and the Origin of Language)* | 🟢 关键词触发 (`@D2`, 顺序 `426`) | 推演共同活动中的语言习得与角色模仿：角色不是机械复制他人的外表动作，而是在合作与冲突中学会何时、为何以及对谁做出相应回应。 | George Herbert Mead (乔治·赫伯特·米德), *Mind, Self, and Society: The Definitive Edition* (《心灵、自我与社会》) |
| `27` | **[MEAD:MSS] 第09章：声音姿态与重要符号**<br>*([MEAD:MSS] Chapter 09: The Vocal Gesture and the Significant Symbol)* | 🟢 关键词触发 (`@D2`, 顺序 `427`) | 推演“声音姿态”（Vocal Gesture）与重要符号的独特机制：角色说出的话语会同时刺激自己，迫使自己站在听者的位置上听见自己的声音、羞耻或威胁。 | George Herbert Mead (乔治·赫伯特·米德), *Mind, Self, and Society: The Definitive Edition* (《心灵、自我与社会》) |
| `28` | **[MEAD:MSS] 第10章：思想、沟通与重要符号**<br>*([MEAD:MSS] Chapter 10: Thought, Communication, and the Significant Symbol)* | 🟢 关键词触发 (`@D2`, 顺序 `428`) | 将内心思考刻画为角色在自我内部展开的社会对话：替他人发问、替自己辩护、预演对方的斥责或原谅。 | George Herbert Mead (乔治·赫伯特·米德), *Mind, Self, and Society: The Definitive Edition* (《心灵、自我与社会》) |
| `29` | **[MEAD:MSS] 第11章：意义**<br>*([MEAD:MSS] Chapter 11: Meaning)* | 🟢 关键词触发 (`@D2`, 顺序 `429`) | 将“意义”（Meaning）定位于“行动姿态—所指对象—他人回应”的三元关系之中，而非深藏在器物内部或孤立的大脑念头里。 | George Herbert Mead (乔治·赫伯特·米德), *Mind, Self, and Society: The Definitive Edition* (《心灵、自我与社会》) |
| `30` | **[MEAD:MSS] 第12章：普遍性**<br>*([MEAD:MSS] Chapter 12: Universality)* | 🟢 关键词触发 (`@D2`, 顺序 `430`) | 推演不同角色如何通过共同指向的器物、规则或符号建立起可沟通的“普遍性”，以及当共同对象破裂时沟通如何失效。 | George Herbert Mead (乔治·赫伯特·米德), *Mind, Self, and Society: The Definitive Edition* (《心灵、自我与社会》) |
| `31` | **[MEAD:MSS] 第13章：反思性智能的性质**<br>*([MEAD:MSS] Chapter 13: The Nature of Reflective Intelligence)* | 🟢 关键词触发 (`@D2`, 顺序 `431`) | 推演“反思性智能”的真实触发点：只有当习惯性行动受阻、旧套路走不通时，角色才会在内心排演多种替代行动方案并权衡后果。 | George Herbert Mead (乔治·赫伯特·米德), *Mind, Self, and Society: The Definitive Edition* (《心灵、自我与社会》) |
| `32` | **[MEAD:MSS] 第14章：行为主义、华生主义与反思**<br>*([MEAD:MSS] Chapter 14: Behaviorism, Watsonism, and Reflection)* | 🟢 关键词触发 (`@D2`, 顺序 `432`) | 防止将角色的内心独白简化为机械的词语替换：真正的反思必须包含具体对象、行动后果、他人反应预期与自身处境的重组。 | George Herbert Mead (乔治·赫伯特·米德), *Mind, Self, and Society: The Definitive Edition* (《心灵、自我与社会》) |
| `33` | **[MEAD:MSS] 第15章：行为主义与心理平行论**<br>*([MEAD:MSS] Chapter 15: Behaviorism and Psychological Parallelism)* | 🟢 关键词触发 (`@D2`, 顺序 `433`) | 在角色有机体与社会环境的动态关系中理解心理经验，尤其当角色的创伤或反常反应被旁人误读为单纯的“发疯”或“怪癖”时。 | George Herbert Mead (乔治·赫伯特·米德), *Mind, Self, and Society: The Definitive Edition* (《心灵、自我与社会》) |
| `34` | **[MEAD:MSS] 第16章：心灵与符号**<br>*([MEAD:MSS] Chapter 16: Mind and the Symbol)* | 🟢 关键词触发 (`@D2`, 顺序 `434`) | 推演心灵如何通过符号把“尚未发生的未来后果”提前引入当下：角色此刻说出的一个词或承诺，已经在重组后续的责任、期盼与恐惧。 | George Herbert Mead (乔治·赫伯特·米德), *Mind, Self, and Society: The Definitive Edition* (《心灵、自我与社会》) |
| `35` | **[MEAD:MSS] 第17章：心灵与反应、环境的关系**<br>*([MEAD:MSS] Chapter 17: The Relation of Mind to Response and Environment)* | 🟢 关键词触发 (`@D2`, 顺序 `435`) | 拒绝把环境写成千篇一律的舞台布景：同一房间、武器或街道，唯有通过该角色能够敏锐察觉、预期和畏惧的事物，才构成其真实的行动世界。 | George Herbert Mead (乔治·赫伯特·米德), *Mind, Self, and Society: The Definitive Edition* (《心灵、自我与社会》) |
| `36` | **[MEAD:MSS] 第18章：自我与有机体**<br>*([MEAD:MSS] Chapter 18: The Self and the Organism)* | 🟢 关键词触发 (`@D2`, 顺序 `436`) | 将“自我”（Self）呈现为在社会互动经验中逐渐成型的自反性观察对象——角色如何学会把自己当作一个“客体”来审视、评价与管束。 | George Herbert Mead (乔治·赫伯特·米德), *Mind, Self, and Society: The Definitive Edition* (《心灵、自我与社会》) |
| `37` | **[MEAD:MSS] 第19章：自我发生的背景**<br>*([MEAD:MSS] Chapter 19: The Background of the Genesis of the Self)* | 🟢 关键词触发 (`@D2`, 顺序 `437`) | 推演自我生成的社会背景：角色总是先在合作与冲突中学会回应他人，随后才把这种回应他人的方式转回来对待自己。 | George Herbert Mead (乔治·赫伯特·米德), *Mind, Self, and Society: The Definitive Edition* (《心灵、自我与社会》) |
| `38` | **[MEAD:MSS] 第20章：游戏、竞赛与泛化他者**<br>*([MEAD:MSS] Chapter 20: Play, the Game, and the Generalized Other)* | 🟢 关键词触发 (`@D2`, 顺序 `438`) | 运用“扮演（Play）—竞赛（Game）—泛化他者（Generalized Other）”三阶段模型，推演角色如何从模仿单一重要他人，发展到把整个家族、教派或社群的规范目光内化进自我审判。 | George Herbert Mead (乔治·赫伯特·米德), *Mind, Self, and Society: The Definitive Edition* (《心灵、自我与社会》) |
| `39` | **[MEAD:MSS] 第21章：自我与主观性**<br>*([MEAD:MSS] Chapter 21: The Self and the Subjective)* | 🟢 关键词触发 (`@D2`, 顺序 `439`) | 重新界定“主观性”：私人内心并非与社会隔绝的孤岛，而是角色从互动现场暂时后退一步、审视自身处境与秘密反应的能力。 | George Herbert Mead (乔治·赫伯特·米德), *Mind, Self, and Society: The Definitive Edition* (《心灵、自我与社会》) |
| `40` | **[MEAD:MSS] 第22章：“I”与“Me”**<br>*([MEAD:MSS] Chapter 22: The "I" and the "Me")* | 🟢 关键词触发 (`@D2`, 顺序 `440`) | 米德核心机制“主我（I）”与“客我（Me）”：客我（Me）是内化的社会规范、他人期待与身份责任；主我（I）则是角色在当下情境中自发、突破常规、甚至连自己都未曾预料到的即时反应。 | George Herbert Mead (乔治·赫伯特·米德), *Mind, Self, and Society: The Definitive Edition* (《心灵、自我与社会》) |
| `41` | **[MEAD:MSS] 第23章：社会态度与物理世界**<br>*([MEAD:MSS] Chapter 23: Social Attitudes and the Physical World)* | 🟢 关键词触发 (`@D2`, 顺序 `441`) | 推演社会态度如何组织物理世界：餐桌、房门、药物、武器、婚床与制服在不同的社会关系与行动意图下会变成截然不同的道德客体。 | George Herbert Mead (乔治·赫伯特·米德), *Mind, Self, and Society: The Definitive Edition* (《心灵、自我与社会》) |
| `42` | **[MEAD:MSS] 第24章：心灵作为社会过程的个体内化**<br>*([MEAD:MSS] Chapter 24: Mind as the Individual Importation of the Social Process)* | 🟢 关键词触发 (`@D2`, 顺序 `442`) | 将角色的心灵呈现为社会过程向个体内部的导入：角色在独处时的纠结，本质上是在内心重演与外部权威、伴侣或共同体的沟通结构。 | George Herbert Mead (乔治·赫伯特·米德), *Mind, Self, and Society: The Definitive Edition* (《心灵、自我与社会》) |
| `43` | **[MEAD:MSS] 第25章：“I”与“Me”作为自我的阶段**<br>*([MEAD:MSS] Chapter 25: The "I" and the "Me" as Phases of the Self)* | 🟢 关键词触发 (`@D2`, 顺序 `443`) | 将“I”与“Me”作为自我行动的连续时间相位：社会规范（Me）先组织起行动预期，当下的自发冲动（I）做出回应并在下一刻沉淀进记忆，成为新的“Me”。 | George Herbert Mead (乔治·赫伯特·米德), *Mind, Self, and Society: The Definitive Edition* (《心灵、自我与社会》) |
| `44` | **[MEAD:MSS] 第26章：自我在社会情境中的实现**<br>*([MEAD:MSS] Chapter 26: The Realization of the Self in the Social Situation)* | 🟢 关键词触发 (`@D2`, 顺序 `444`) | 规定自我只能在具体情境、社会位置与关系回应中实现，拒绝脱离关系现场的抽象“做自己”口号。 | George Herbert Mead (乔治·赫伯特·米德), *Mind, Self, and Society: The Definitive Edition* (《心灵、自我与社会》) |
| `45` | **[MEAD:MSS] 第27章：“Me”与“I”的贡献**<br>*([MEAD:MSS] Chapter 27: The Contributions of the "Me" and the "I")* | 🟢 关键词触发 (`@D2`, 顺序 `445`) | 推演“Me”与“I”在道德行动中的双向制衡：“Me”提供秩序、分寸与社会可理解性，“I”提供生命力、冒险与突破僵局的可能。 | George Herbert Mead (乔治·赫伯特·米德), *Mind, Self, and Society: The Definitive Edition* (《心灵、自我与社会》) |
| `46` | **[MEAD:MSS] 第28章：涌现自我的社会创造性**<br>*([MEAD:MSS] Chapter 28: The Social Creativity of the Emergent Self)* | 🟢 关键词触发 (`@D2`, 顺序 `446`) | 推演“涌现自我”的社会创造性：角色的突破与反叛不是反社会的孤僻任性，而是在关系网络中做出足以改写既有互动规则的新回应。 | George Herbert Mead (乔治·赫伯特·米德), *Mind, Self, and Society: The Definitive Edition* (《心灵、自我与社会》) |
| `47` | **[MEAD:MSS] 第29章：个体主义与社会性自我理论的对比**<br>*([MEAD:MSS] Chapter 29: Contrast of Individualistic and Social Theories of the Self)* | 🟢 关键词触发 (`@D2`, 顺序 `447`) | 拒斥“先有完备孤立个体、再拼凑出社会契约”的还原论：角色之所以能产生某种“个人选择”或羞耻感，其前提本就植根于社会关系。 | George Herbert Mead (乔治·赫伯特·米德), *Mind, Self, and Society: The Definitive Edition* (《心灵、自我与社会》) |
| `48` | **[MEAD:MSS] 第30章：人类社会基础：人和昆虫**<br>*([MEAD:MSS] Chapter 30: The Basis of Human Society: Man and the Insects)* | 🟢 关键词触发 (`@D3`, 顺序 `448`) | 通过人类社会与昆虫社会的对比，强调人类秩序并非靠生理分化固定，而是依赖可学习、可互换、可反思的角色承担（Role-Taking）。 | George Herbert Mead (乔治·赫伯特·米德), *Mind, Self, and Society: The Definitive Edition* (《心灵、自我与社会》) |
| `49` | **[MEAD:MSS] 第31章：人类社会基础：人和脊椎动物**<br>*([MEAD:MSS] Chapter 31: The Basis of Human Society: Man and the Vertebrates)* | 🟢 关键词触发 (`@D3`, 顺序 `449`) | 通过人类合作与脊椎动物本能等级的对比，推演人类组织如何建立在“能够设身处地代入彼此角色”之上，而非纯粹靠暴力支配排位。 | George Herbert Mead (乔治·赫伯特·米德), *Mind, Self, and Society: The Definitive Edition* (《心灵、自我与社会》) |
| `50` | **[MEAD:MSS] 第32章：有机体、共同体与环境**<br>*([MEAD:MSS] Chapter 32: Organism, Community, and Environment)* | 🟢 关键词触发 (`@D3`, 顺序 `450`) | 推演共同体与环境的互塑：一个群体的生存技术、习俗敏感点与集体恐惧决定了哪些自然或社会变化会被识别为“道德危机”。 | George Herbert Mead (乔治·赫伯特·米德), *Mind, Self, and Society: The Definitive Edition* (《心灵、自我与社会》) |
| `51` | **[MEAD:MSS] 第33章：思想与沟通的社会基础和功能**<br>*([MEAD:MSS] Chapter 33: The Social Foundations and Functions of Thought and Communication)* | 🟢 关键词触发 (`@D2`, 顺序 `451`) | 推演思想与沟通的社会协调功能：角色唯有通过代入对方的态度预期，才能完成真正的说服、欺骗、谈判或默契配合。 | George Herbert Mead (乔治·赫伯特·米德), *Mind, Self, and Society: The Definitive Edition* (《心灵、自我与社会》) |
| `52` | **[MEAD:MSS] 第34章：共同体与制度**<br>*([MEAD:MSS] Chapter 34: The Community and the Institution)* | 🟢 关键词触发 (`@D3`, 顺序 `452`) | 将“制度”（Institution）定义为共同体内标准化的期待与回应模式：财产权、婚姻、审判或命令唯有在众人做出可预期反应时才真实存在。 | George Herbert Mead (乔治·赫伯特·米德), *Mind, Self, and Society: The Definitive Edition* (《心灵、自我与社会》) |
| `53` | **[MEAD:MSS] 第35章：社会活动中“I”和“Me”的融合**<br>*([MEAD:MSS] Chapter 35: The Fusion of the "I" and the "Me" in Social Activities)* | 🟢 关键词触发 (`@D2`, 顺序 `453`) | 推演共同行动（如庆典、并肩作战、集体救援、宗教狂热）中“I”与“Me”的暂时融合，以及融合消退后个体重新面对自我的落差。 | George Herbert Mead (乔治·赫伯特·米德), *Mind, Self, and Society: The Definitive Edition* (《心灵、自我与社会》) |
| `54` | **[MEAD:MSS] 第36章：民主与社会中的普遍性**<br>*([MEAD:MSS] Chapter 36: Democracy and Universality in Society)* | 🟢 关键词触发 (`@D3`, 顺序 `454`) | 推演普遍性与民主心态的微观心理基础：角色能否扩大“角色代入”的半径，将原本被排斥的边缘人或异邦人的态度纳入公共判断。 | George Herbert Mead (乔治·赫伯特·米德), *Mind, Self, and Society: The Definitive Edition* (《心灵、自我与社会》) |
| `55` | **[MEAD:MSS] 第37章：宗教与经济态度的进一步考察**<br>*([MEAD:MSS] Chapter 37: Further Consideration of Religious and Economic Attitudes)* | 🟢 关键词触发 (`@D3`, 顺序 `455`) | 对比宗教态度（通过共享神圣对象与救赎关切连接陌生人）与经济态度（通过交换契约与利益可预期性连接陌生人）如何各自扩展或割裂共同体。 | George Herbert Mead (乔治·赫伯特·米德), *Mind, Self, and Society: The Definitive Edition* (《心灵、自我与社会》) |
| `56` | **[MEAD:MSS] 第38章：同情的性质**<br>*([MEAD:MSS] Chapter 38: The Nature of Sympathy)* | 🟢 关键词触发 (`@D2`, 顺序 `456`) | 重构“同情”（Sympathy）的行动机制：同情不是居高临下的廉价感伤，而是在具体援助行动中唤醒并代入受难者的处境与态度。 | George Herbert Mead (乔治·赫伯特·米德), *Mind, Self, and Society: The Definitive Edition* (《心灵、自我与社会》) |
| `57` | **[MEAD:MSS] 第39章：冲突与整合**<br>*([MEAD:MSS] Chapter 39: Conflict and Integration)* | 🟢 关键词触发 (`@D2`, 顺序 `457`) | 推演冲突与人格整合的辩证关系：成熟的道德人格与共同体往往不是靠掩盖矛盾，而是通过正视角色冲突、重组内在态度来实现更高层次的整合。 | George Herbert Mead (乔治·赫伯特·米德), *Mind, Self, and Society: The Definitive Edition* (《心灵、自我与社会》) |
| `58` | **[MEAD:MSS] 第40章：人格与理性在社会组织中的功能**<br>*([MEAD:MSS] Chapter 40: The Functions of Personality and Reason in Social Organization)* | 🟢 关键词触发 (`@D3`, 顺序 `458`) | 推演人格与理性在社会组织中的功能：理性不是冷酷无情的算计，而是帮助个体与群体将相互冲突的多种态度整合成可行秩序的能力。 | George Herbert Mead (乔治·赫伯特·米德), *Mind, Self, and Society: The Definitive Edition* (《心灵、自我与社会》) |
| `59` | **[MEAD:MSS] 第41章：理想社会发展的障碍与希望**<br>*([MEAD:MSS] Chapter 41: Obstacles and Promises in the Development of the Ideal Society)* | 🟢 关键词触发 (`@D3`, 顺序 `459`) | 推演理想共同体的现实障碍与希望：真正的共同体不是消灭差异的整齐划一，而是让不同分工与处境的成员能够相互代入并理解彼此的视角。 | George Herbert Mead (乔治·赫伯特·米德), *Mind, Self, and Society: The Definitive Edition* (《心灵、自我与社会》) |
| `60` | **[MEAD:MSS] 第42章：总结与结论**<br>*([MEAD:MSS] Chapter 42: Summary and Conclusion)* | 🟢 关键词触发 (`@D3`, 顺序 `460`) | 米德模块总括：将姿态、重要符号、角色代入、“主我/客我”张力与制度化共同体串联为完整的微观心理—社会行动连续统。 | George Herbert Mead (乔治·赫伯特·米德), *Mind, Self, and Society: The Definitive Edition* (《心灵、自我与社会》) |
| `61` | **[CHOMSKY:LANGMIND] 语言官能、普遍语法与角色的可生成心智**<br>*([CHOMSKY:LANGMIND] Language Faculty, Universal Grammar, and the Generative Mind of Characters)* | 🟢 关键词触发 (`@D3`, 顺序 `561`) | 将语言写为角色心智的生成性能力（Generative Mind）而非外部词库：推演角色在极端伦理处境下如何用有限规则生成新表达、误解抽象义务或抗拒灌输。 | Noam Chomsky (诺姆·乔姆斯基), *Linguagem e mente: pensamentos atuais sobre antigos problemas* (Editora UnB, 1998) / *Language and Mind* (《语言与心智》) |
| `62` | **[CHOMSKY:MINIMALISM] 接口、可读性与最小化心智负担**<br>*([CHOMSKY:MINIMALISM] Interfaces, Legibility, and Minimizing Mental Burden)* | 🟢 关键词触发 (`@D3`, 顺序 `562`) | 基于乔姆斯基最简方案（Minimalist Program）：推演角色话语在语音/外化接口与意义/概念接口之间的省略、言外之意与心智计算负担。 | Noam Chomsky (诺姆·乔姆斯基), *Linguagem e mente: pensamentos atuais sobre antigos problemas* (Editora UnB, 1998) / *Language and Mind* (《语言与心智》) |
| `63` | **[CHOMSKY:SEMANTICS] 词义、语境、文本边界与隐喻理解**<br>*([CHOMSKY:SEMANTICS] Word Meaning, Context, Textual Boundaries, and Metaphorical Understanding)* | 🟢 关键词触发 (`@D3`, 顺序 `563`) | 推演核心词义（如“家”“身体”“背叛”“救赎”）如何随语境、制度角色与隐喻框架发生偏移，制造表面使用同一词汇却指向不同道德世界的错位。 | Noam Chomsky (诺姆·乔姆斯基), *Linguagem e mente: pensamentos atuais sobre antigos problemas* (Editora UnB, 1998) / *Language and Mind* (《语言与心智》) |
| `64` | **[FOUCAULT:ETHICS] 问题化、伦理谱系与自由实践**<br>*([FOUCAULT:ETHICS] Problematization, Genealogy of Ethics, and Practices of Freedom)* | 🟢 关键词触发 (`@D3`, 顺序 `564`) | 基于福柯伦理谱系学：将伦理写为角色对自身欲望、义务、身体与真理关系的“问题化”（Problematization），在规范缝隙中展开自由实践。 | Michel Foucault (米歇尔·福柯), *Ethics: Subjectivity and Truth (Essential Works of Foucault, 1954–1984, Vol. 1)* (《伦理：主体性与真理——福柯集》) |
| `65` | **[FOUCAULT:SELFTECH] 自我书写、主体阐释与修行技术**<br>*([FOUCAULT:SELFTECH] Self-Writing, Subject Hermeneutics, and Technologies of the Self)* | 🟢 关键词触发 (`@D3`, 顺序 `565`) | 推演日记、书信、告解、良心省察、师徒对话与身体苦修等“自我技术”（Technologies of the Self）如何实际重塑角色的道德主体性。 | Michel Foucault (米歇尔·福柯), *Ethics: Subjectivity and Truth (Essential Works of Foucault, 1954–1984, Vol. 1)* (《伦理：主体性与真理》) & *The History of Sexuality, Vol. 3: The Care of the Self* (《性经验史（三卷本）·第三卷：关注自我》) |
| `66` | **[FOUCAULT:RELATION] 友谊、性选择与身份之外的生活形式**<br>*([FOUCAULT:RELATION] Friendship, Sexual Choice, and Forms of Life Beyond Identity)* | 🟢 关键词触发 (`@D3`, 顺序 `566`) | 推演友谊、亲密选择与超越既定制度标签的“生活形式”（Forms of Life）：角色如何通过日常陪伴与共同患难创造尚未被社会正式命名的关系。 | Michel Foucault (米歇尔·福柯), *Ethics: Subjectivity and Truth (Essential Works of Foucault, 1954–1984, Vol. 1)* (《伦理：主体性与真理——福柯集》) |
| `67` | **[DERRIDA:ETHICS] 不可通约、他者与语言暴力**<br>*([DERRIDA:ETHICS] Incommensurability, the Other, and Linguistic Violence)* | 🟢 关键词触发 (`@D3`, 顺序 `567`) | 基于德里达解构伦理学：推演伦理困境中的不可通约性（Incommensurability）、绝对他者的不可还原性，以及命名、翻译与法律普遍语言本身可能施加的暴力。 | Christopher Watkin (克里斯托弗·沃特金), *Jacques Derrida* (Great Thinkers: Host of Deconstruction, P&R Publishing, 2017) |
| `68` | **[Gestalt] 角色需求感知与行为链条推演引擎**<br>*([Gestalt] Character Need Perception and Behavioral Chain Reasoning Engine)* | 🔵 常驻激活 (`@D1`, 顺序 `120`) | 常驻底层动机引擎：将格式塔疗法“体验循环”（感知→觉察→能量动员→行动→接触→消退）转化为角色需求萌发、受阻与行为执行的完整心理生理链条。 | **学派通用理论综合条目（格式塔疗法 Gestalt Therapy）** — 综合自 Fritz Perls 等《格式塔治疗》、Erving & Miriam Polster《整合式格式塔治疗》及 Phil Joyce & Charlotte Sills《格式塔心理咨询与治疗技术》（同时见 `unidentifiable_entries.md` 与 `identifiable_entries.md` 第三部分） |
| `69` | **[Gestalt] 角色心理防御机制与非健康人际互动推演**<br>*([Gestalt] Character Psychological Defense Mechanisms and Unhealthy Interpersonal Interaction Reasoning)* | 🟢 关键词触发 (`@D1`, 顺序 `181`) | 推演角色在高压、创伤或亲密冲突下的格式塔“接触边界失调”防御机制（内射 Introjection、投射 Projection、回射 Retroflection、偏转 Deflection、融合 Confluence）。 | **学派通用理论综合条目（格式塔疗法 Gestalt Therapy）** — 综合自 Fritz Perls 等《格式塔治疗》、Erving & Miriam Polster《整合式格式塔治疗》及 Phil Joyce & Charlotte Sills《格式塔心理咨询与治疗技术》（同时见 `unidentifiable_entries.md` 与 `identifiable_entries.md` 第三部分） |
| `70` | **[Gestalt] 潜意识创伤干预与注意力焦点推演**<br>*([Gestalt] Subconscious Trauma Intervention and Attention Focus Reasoning)* | 🟢 关键词触发 (`@D1`, 顺序 `182`) | 运用格式塔“图形-背景”（Figure-Ground）与“未竟事宜”（Unfinished Business）原理，推演潜意识未解创伤如何扭曲角色当下的注意力焦点与现实感知。 | **学派通用理论综合条目（格式塔疗法 Gestalt Therapy）** — 综合自 Fritz Perls 等《格式塔治疗》、Erving & Miriam Polster《整合式格式塔治疗》及 Phil Joyce & Charlotte Sills《格式塔心理咨询与治疗技术》（同时见 `unidentifiable_entries.md` 与 `identifiable_entries.md` 第三部分） |
| `71` | **[SELF-REASONING] 自身经验推理偏置与创伤误识别**<br>*([SELF-REASONING] Personal Experience Reasoning Bias and Trauma Misrecognition)* | 🟢 关键词触发 (`@D1`, 顺序 `180`) | 原创微观推理引擎：规定角色只能优先从自身既有生活经验去揣测他人（经验推理偏置），并推演角色对自身创伤的“延迟识别与躯体化误认”，严禁角色自带全知心理医生视角。 | **原创角色扮演微观推理条目** — 自身经验推理偏置与创伤延迟/躯体化误识别（见 `unidentifiable_entries.md`） |
