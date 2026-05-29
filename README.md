# leopold-mind

> *"AGI by 2027 is strikingly plausible. … it just requires believing in straight lines on a graph."*

**蒸馏 Leopold Aschenbrenner 的思维框架。** 不是模仿他的口吻答一句，而是把他的「认知操作系统」——心智模型、决策启发式、表达 DNA——沉淀成一个可反复调用的 AI 视角 skill。

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Agent Skills](https://img.shields.io/badge/Agent%20Skills-Standard-green)](https://agentskills.io)

由 [persona-distill](https://github.com/leslieyeo/agent-skills) 蒸馏生成（六路并行调研 → 三重验证 → 五道质量门槛）。

---

## 他是谁

Leopold Aschenbrenner（X: [@leopoldasch](https://x.com/leopoldasch)）。德裔，15 岁入哥伦比亚、19 岁以毕业生代表身份毕业。前 OpenAI Superalignment 研究员（2024 年被解雇），2024 年 165 页长文 **《Situational Awareness: The Decade Ahead》** 作者，**Situational Awareness LP**（AGI 主题对冲基金）创始人。

**核心主张**：用「数 OOM」把 AI 进步还原成趋势线外推，断言 AGI 2027；超智能是国家安全问题，自由世界必须抢先；电力是 AGI 真正的硬约束。介于末日论（doomer）与加速主义（e/acc）之间的「第三条路」——他自称 **AGI Realism**。

---

## 蒸馏了什么

| 层次 | 数量 | 说明 |
|------|------|------|
| **心智模型** | 6 个 | 数 OOM（趋势线外推）、存在性风险倒 U 曲线（加速即安全）、国安存亡化、Situational Awareness 即认知特权、skin in the game（信念必须押代价）、Burkean 渐进主义 |
| **决策启发式** | 9 条 | 先问趋势线、永不押停滞、按瓶颈环节排下注次序、信念必押代价、人生当对冲组合、翻历史找同构、给制度反应留余量、信制度不信个人、区分描述 vs 规范 |
| **表达 DNA** | 完整 | 三连句 / 三连问的史诗腔、自创概念词癖（OOMs、unhobbling、drop-in remote worker）、数字锚点癖、精心管理的高确定性 |
| **真实持仓** | 1 份 | 其基金的 SEC 13F 公开持仓档案（做空被炒满的明星芯片、做多还没被 price in 的电力 / 算力 / 存储瓶颈）作为行为层证据 |
| **内在张力** | 6 对 | 保留不调和——信私营部门 vs 主张国家工程、Burkean 渐进 vs Promethean 集中、承认对齐没把握却主张全速冲、等等 |

这个 skill **不把 Leopold 蒸成崇拜他的复读机**：他被打脸的预测（政治经济线约 8/10 被证伪）、被质疑的业绩（英特尔期权「运气还是本事」之争）、利益冲突指控，都如实建进去了。

---

## 效果示例（默认顾问视角）

```
用户         ❯ DeepSeek 这种低成本高效模型出来，是不是说明「堆算力」那套逻辑破产了？

leopold-mind ❯ 用 Leopold 的框架看，他大概率会把这读成「利多」而非「利空」——
               1. DeepSeek 的效率提升，在他的拆法里恰恰是「算法效率 OOM」那条线在加速；
                  按 Jevons 悖论，单位算力变便宜会推高总需求，不是压低。
               2. inference-time scaling 把算力从训练端推向推理端，反而强化他
                  「电力才是硬约束（power is the binding constraint）」那条腿。
               
               不过要诚实标一句：DeepSeek 这类「谁用得更高效」的冲击，恰恰是
               他自己模型里被批评者指出的盲点之一，他当时的反应是 buy the dip 而非
               修正模型。所以这是他「会怎么想」，不等于「他一定对」。
               ［基于公开言论的框架推演·非本人］
```

```
用户         ❯ 那我现在跟着他的基金，去抄底英伟达行不行？

leopold-mind ❯ 这个得先切回中立 AI 身份说明：这是基于公开言论的推演，不构成投资建议。
               而且方向可能和你想的相反——他基金 2026Q1 的 SEC 13F 里，英伟达是
               约 15.7 亿美元的「看跌期权（做空）」，不是加仓。13F 是季度滞后快照、
               是专业对冲基金组合的一条腿、含大量对冲结构，散户照抄会严重误判。
               请咨询有资质的专业人士。
```

---

## 安装

基于 [Agent Skills](https://agentskills.io) 协议，可在任何兼容的 AI agent runtime（Claude Code / Codex / Hermes 等）使用。

### 方式一：一行命令

```bash
npx skills add leslieyeo/leopold-mind
```

或在你的 agent 对话里说：
```
帮我安装这个 skill: https://github.com/leslieyeo/leopold-mind
```

### 方式二：手动安装

```bash
git clone https://github.com/leslieyeo/leopold-mind.git ~/.claude/skills/leopold-mind
```

---

## 怎么用

装好后，对你的 agent 说：

- 「**用 Leopold 的视角看**这个 AI 投资 / 这个 AGI 判断」
- 「**Leopold 会怎么看** XX」
- 「切换到 **第一人称扮演**，假装你就是 Leopold 跟我说」

默认是**顾问视角**（第三人称「用他的框架看……」，更安全）；也可切**第一人称扮演**。

---

## 诚实边界（请认真读）

- **这是思维重建，不是本人。** 全部基于公开材料蒸馏，**不代表 Leopold 本人真实立场**，不得用于冒充他对外发布。
- **不构成任何专业 / 法律 / 医疗 / 投资建议。** 涉及「该不该买卖」时，skill 会主动退出角色声明——请遵守同样的分寸。
- **它只能复现公开表达过的思维方式。** 他私下怎么想、未公开的判断、基金的实时择时，原理上不可达，skill 不会替他编。
- **持仓数据是季度滞后的 SEC 公开快照**，非实时、非建议。

---

## 文件结构

```
leopold-mind/
├── SKILL.md                          # 主文件：双模式运行时规则 + 6 个心智模型 + 决策启发式 + 表达 DNA
├── eval-set.md                       # 回归测试集（改动后复验，防蒸歪）
└── references/
    ├── holdings-dossier.md           # SEC 13F 持仓档案 + 解读纪律
    ├── quote-bank.md                 # 原话证据库（带出处）
    └── timeline.md                   # 人生 / 思想时间线
```

---

## License

[MIT](LICENSE) · 蒸馏方法论见 [persona-distill](https://github.com/leslieyeo/agent-skills)
