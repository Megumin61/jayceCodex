# 《探讨 AI 产品趋势》主题索引

本文件只承担导航作用。完整原文以 `conversation.raw.json` 为准，适合程序处理的逐条消息以 `conversation.jsonl` 为准。

## 会话推进

### Turn 1：从知识库失效感重新判断 AI 产品

起点是一个曾经完成过的第二大脑 Demo：将网页、PDF 和笔记以 Markdown、RAG 和主题关联的方式沉淀；随着桌面 Agent、模型原生 context management 和 harness 能力增强，这类产品的独立价值开始受到质疑。

讨论由此提出核心判断：

> 模型越来越强以后，用来弥补模型智力不足的结构正在贬值；用来表达用户独特性、现实约束和行动权限的结构正在升值。

并将个人 AI 的长期内容拆成 Information、Memory、Procedure、Judgment、Agency 五层，把方向从 Personal Knowledge 推进到 Personal Intelligence。

### Turn 2：从 Memory 进入 Judgment 与 Expertise Compiler

这一轮补充了 Codex、Claude Code、Qoder、WorkBuddy 的上下文与记忆架构趋势，并进一步区分：

- remember me：记住用户事实与偏好；
- understand how I think：理解用户在特定条件下怎样判断；
- validated personal intelligence：判断是否经过案例和 outcome 验证。

重点洞察是：真正高信号的数据不只是用户保存了什么，而是 AI 提供了什么、用户最后改成了什么，以及结果如何，即 decision trace、correction trace 和 outcome trace。

由此形成 Expertise Compiler：专家正常工作，系统从真实 work traces 中提炼 knowledge、principles、cases、counterexamples、procedures、evals 与 tools，再由专家校准。

### Turn 3：收束为跨 Agent Context 的创业产品

用户要求先从有画面感的理想场景出发，再讨论实现。讨论以 PM、研究者、资深负责人三个场景统一为：

> 连续我的上下文 → 复用我的经验 → 复制我的能力。

主动收藏被重新定义为 attention 与 intention 信号；自动工作沉淀代表 experience。产品不能只有其中一条输入。

产品核心循环被收束为：

> Capture → Understand → Reuse → Accumulate → Transfer

创业路径则分三层：

1. Cross-Agent Context：解决每个 AI 都要重新认识用户的问题；
2. Personal Intelligence：从长期使用中形成 Experience、Judgment 与 Eval；
3. Expertise Network：将经过验证的能力授权给团队或他人调用。

MVP 定位为轻量 Desktop / Web Home + Browser Capture + MCP/API。Home 是控制面板，价值发生在用户原本使用的 Claude、Codex、Qoder 等 Agent 中。

### Turn 4：将讨论交给 Work 模式归档

最后一轮提出把本次讨论整理并保存到 GitHub。本目录即这次归档的结果。

## 核心概念

| 概念 | 在本次讨论中的含义 |
| --- | --- |
| Personal Intelligence Layer | 用户拥有、跨模型持续存在的知识、经历、判断、评价和权限层 |
| Cross-Agent Context | 同一份用户状态被不同 Agent 按需调用，而非分别维护孤立记忆 |
| Context Compiler | 根据当前任务动态组装 minimum sufficient personal context |
| Expertise Compiler | 从专家真实工作轨迹中编译出可调用、可校准、可验证的专业能力 |
| Judgment | 带场景、目标、理由、案例、反例和置信度的条件性判断 |
| Personalized Eval | 检验 Agent 是否复现用户判断、是否真正产生更好结果的评价系统 |
| Model Improvement Test | 模型能力大幅提升后，产品是被替代还是获得更强杠杆 |

## 尚未完成的关键问题

- MVP 的首批 ICP 最终选 PM、设计负责人、研究者还是更窄的人群？
- 第一次使用、7 天和 30 天分别如何创造可感知价值？
- 哪些数据可被合理捕获，如何建立隐私、权限和可撤销机制？
- Judgment schema 如何表达 scope、confidence、conflict、recency 与 provenance？
- 跨 Agent 接入先采用 MCP、浏览器扩展、文件协议还是其他方式？
- Cross-Agent Memory 如何避免只成为容易被平台吸收的 feature？
- Expertise Package 的效果如何评测，如何区分“像专家”和“真的有效”？
- B2C、团队 SaaS 与 Expertise Marketplace 的演进顺序是什么？

