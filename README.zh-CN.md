# Awesome Academic Research Skills

[English](README.md) | [简体中文](README.zh-CN.md)

> 一个按科研工作流组织的公开 Agent Skill、Skill Pack、研究 Agent 和辅助工具索引，服务于学术研究。

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

**核验快照：2026-09-02。** 本仓库是发现索引，不是背书或基准测试。项目说明、宿主标签和许可证均为面向上游的简要元数据；安装或复用前，请阅读链接仓库及其最新条款。

> **本版通过 GitHub 调研新增。** 标有 **New** 的条目在本版经 GitHub 源仓库核验后加入。这里刻意不列出热度指标：它们变化很快，也不能证明质量。

## 如何使用本列表

先按科研阶段选择，再用学科图例和宿主列缩小范围。为减少重复，每个仓库在可行时只归入一个主要类别，而不会因为覆盖多个阶段反复出现。

### 学科图例

| 代码 | 最适合的学科 |
| --- | --- |
| `X` | 跨学科 |
| `CS/AI` | 计算机科学与人工智能 |
| `EP` | 工程与物理科学 |
| `LS/M` | 生命科学与医学 |
| `C/M` | 化学与材料 |
| `SS/E` | 社会科学与经济学 |
| `H/L` | 人文与语言 |

### 许可证标签

`Not detected†` 表示在该核验快照中未发现明显的仓库级 SPDX 标识或根目录许可证。`Per-skill†` 和 `Mixed terms†` 表示仓库内各条目没有统一、可简单复用的单一许可证。它们不是法律意见——使用、再分发或商业使用前，请自行检查上游条款。

## 精选起点

| 你的起点需求 | 推荐项目 | 适合作为首选入口的原因 |
| --- | --- | --- |
| 证据驱动的论文规划与修改 | [MAIR scientific-paper-writing-skills](https://github.com/MAIR-Lab-HUST/scientific-paper-writing-skills) **New** | 紧凑的论文写作流程，强调论点与证据的对应。 |
| 广泛的科学工具与计算工作流 | [K-Dense scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) | 覆盖数据、文献和科学工具的跨学科大型库。 |
| 可复现的“研究到论文”检查点 | [AI4S Skills](https://github.com/ai4s-research/ai4s-skills) **New** | 对研究、实验、写作和诚信有明确工作流约束。 |
| 带质检步骤的投稿图 | [Academic Figure Skill](https://github.com/TingxiYu/academic-figure-skill) **New** | 将图表规划、多面板制作和质量检查放入一个聚焦 skill。 |
| 可追溯来源的引文工作 | [grounded-citations](https://github.com/NousResearch/hermes-agent/blob/main/skills/research/grounded-citations/SKILL.md) **New** | 聚焦于让论断与可检查的来源保持关联。 |
| 生命科学研究辅助 | [SciAgent-Skills](https://github.com/jaechang-hits/SciAgent-Skills) **New** | 覆盖生信、临床、可视化和科研交付格式。 |
| 中文优先的科研工作流 | [Tashan Research Skills](https://github.com/TashanGKD/tashan-research-skills) **New** | 提供中文科研写作、统计、可视化和演示文稿流程。 |

## 端到端科研工作流

| 名称 | 它能做什么 | 适配学科 | 宿主 / 平台 | 许可证 |
| --- | --- | --- | --- | --- |
| [academic-research-skills](https://github.com/Imbad0202/academic-research-skills) | 从研究到修改的分阶段工作流与检查点。 | `X` | Claude Code / 兼容 skill 宿主 | CC BY-NC 4.0 |
| [academic-research-skills-codex](https://github.com/Imbad0202/academic-research-skills-codex/tree/main/skills/academic-research-suite) | 面向 Codex 的文献、写作、审稿与实验套件。 | `X` | Codex | CC BY-NC 4.0 |
| [claude-scholar](https://github.com/Galaxy-Dawn/claude-scholar/tree/codex) | 从构思、代码到论文和发表材料的半自动研究流程。 | `CS/AI`, `X` | Codex CLI / Claude Code / Kimi / OpenCode | MIT |
| [AlterLab-Academic-Skills](https://github.com/AlterLab-IEU/AlterLab-Academic-Skills) | 含评测和引文检查的多学科学术工作流。 | `X` | Agent skill 宿主（见上游） | MIT |
| [scientific-paper-writing-skills](https://github.com/MAIR-Lab-HUST/scientific-paper-writing-skills) **New** | 面向科研论文的证据驱动规划、起草与修改。 | `X`, `CS/AI` | Codex skill | CC BY 4.0 |
| [academic-skills](https://github.com/voidful/academic-skills) **New** | 可用于 Agent 工作流的模块化学术研究与写作任务。 | `X` | 兼容 SKILL.md 的宿主 | MIT |
| [ai4s-skills](https://github.com/ai4s-research/ai4s-skills/tree/main/skills/experiment-suite) **New** | 研究规划、可执行实验、论文写作和诚信检查。 | `X`, `EP`, `LS/M` | Claude；提供 Codex/Cursor/Aider 路径 | MIT |
| [Academic-Research-Agent-Skill](https://github.com/ngtiendong/Academic-Research-Agent-Skill/blob/main/SKILL.md) **New** | 证据综述、创新点定位、形式化、实验设计和模拟审稿。 | `CS/AI`, `EP` | Claude / Codex-style / Gemini / 本地 LLM | MIT |

## 文献、阅读与证据

| 名称 | 它能做什么 | 适配学科 | 宿主 / 平台 | 许可证 |
| --- | --- | --- | --- | --- |
| [PaperSpine](https://github.com/WUBING2023/PaperSpine) | 从论文中重建动机、论证、证据和修改逻辑。 | `X` | Markdown / Agent skill 宿主 | MIT |
| [paper-search-mcp](https://github.com/openags/paper-search-mcp) | 为文献发现与论文检索提供 MCP 基础设施。 | `X` | MCP 客户端 | MIT |
| [grounded-citations](https://github.com/NousResearch/hermes-agent/blob/main/skills/research/grounded-citations/SKILL.md) **New** | 支持来源可追溯的论断与引文型研究笔记。 | `X` | Hermes Agent / 兼容 SKILL.md 的宿主 | MIT |

## 研究设计、实验与科学计算

| 名称 | 它能做什么 | 适配学科 | 宿主 / 平台 | 许可证 |
| --- | --- | --- | --- | --- |
| [scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) | 科学数据库、分析、计算和领域工具工作流。 | `LS/M`, `C/M`, `EP`, `X` | Codex / Claude / Cursor 等 Agent | MIT |
| [Auto-claude-code-research-in-sleep](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep) | 迭代式机器学习构思、实验与跨模型审查循环。 | `CS/AI` | Claude Code / 研究 Agent 脚本 | MIT |
| [AI-Research-SKILLs](https://github.com/Orchestra-Research/AI-Research-SKILLs) | 面向模型设计、训练与优化的 AI 研究工程技能。 | `CS/AI` | 编码 Agent 宿主（见上游） | MIT |
| [Auto-Empirical-Research-Skills](https://github.com/brycewang-stanford/Auto-Empirical-Research-Skills) | 面向因果研究、分析和统计的实证研究支持。 | `SS/E`, `X` | Agent skill 宿主（见上游） | Not detected† |
| [science-superpowers](https://github.com/K-Dense-AI/science-superpowers) **New** | 面向科学研究的 Agent 能力与可复用工作流。 | `LS/M`, `C/M`, `EP` | 科研 Agent 宿主（见上游） | MIT |
| [scientific-problem-selection](https://github.com/anthropics/life-sciences/tree/main/scientific-problem-selection) **New** | 帮助界定并选择可执行的生命科学研究问题。 | `LS/M`, `C/M` | Anthropic Agent Skills | 上游条款；无仓库 SPDX† |

## 学术写作与论文构思

| 名称 | 它能做什么 | 适配学科 | 宿主 / 平台 | 许可证 |
| --- | --- | --- | --- | --- |
| [Research-Paper-Writing-Skills](https://github.com/Master-cai/Research-Paper-Writing-Skills) | 面向机器学习、CV、NLP 和技术研究的论文写作流程。 | `CS/AI` | Agent skill 宿主（见上游） | MIT |
| [academic-paper-skills](https://github.com/lishix520/academic-paper-skills) | 带质量检查点的论文规划与写作。 | `X` | Agent skill 宿主（见上游） | MIT |
| [codex-claude-academic-skills](https://github.com/zLanqing/codex-claude-academic-skills) | 面向编码 Agent 的论文阅读、写作和科研编程。 | `CS/AI`, `EP` | Codex / Claude | MIT |
| [nature-skills](https://github.com/Yuan1z0825/nature-skills) | Nature 风格科学表达与研究图制作指导。 | `LS/M`, `C/M`, `EP` | Agent skill 宿主（见上游） | Apache-2.0 |
| [writing-skills](https://github.com/msimchowitz/writing-skills) **New** | 为清晰、严谨文本提供结构化起草与修改支持。 | `X`, `H/L` | 兼容 SKILL.md 的宿主 | MIT |

## 图表与可视化

| 名称 | 它能做什么 | 适配学科 | 宿主 / 平台 | 许可证 |
| --- | --- | --- | --- | --- |
| [academic-figure-skill](https://github.com/TingxiYu/academic-figure-skill/blob/main/SKILL.md) **New** | 规划并质检投稿图、多面板图与统计图。 | `X`, `LS/M` | Codex / Claude / Cursor / Copilot | Apache-2.0 |
| [research-grade-skills](https://github.com/Yuuqq/research-grade-skills/tree/main/scientific-skills/scientific-visualization) **New** | 可审计的科研可视化，并包含文献、海报和幻灯片支持。 | `X`, `CS/AI`, `EP` | Codex / Claude / Cursor | MIT |
| [tashan-research-skills](https://github.com/TashanGKD/tashan-research-skills/tree/main/skills/statistical-analysis) **New** | 中文科研统计、画图、演示文稿和论文检查。 | `X`, `SS/E`, `CS/AI` | Codex（Windows）/ Claude / Cursor | MIT |
| [SciAgent-Skills](https://github.com/jaechang-hits/SciAgent-Skills/tree/main/skills/data-visualization/scientific-visualization) **New** | 生命科学可视化、生信、临床统计与科研素材。 | `LS/M`, `C/M` | Codex / Claude / Cursor / Windsurf | CC BY 4.0 |
| [scifig-ai-scientific-figure-skill](https://github.com/lilingm963/scifig-ai-scientific-figure-skill/tree/main/skills/scifig-scientific-figure) **New** | 概念图、图文摘要、技术路线和研究路线图。 | `X`, `EP`, `LS/M` | Codex / Claude / OpenClaw / Hermes | MIT |

## 审稿、回复与科研诚信

| 名称 | 它能做什么 | 适配学科 | 宿主 / 平台 | 许可证 |
| --- | --- | --- | --- | --- |
| [Supervisor-Skills](https://github.com/HKUSTDial/Supervisor-Skills) | 科研指导、想法评估、论文润色与投稿前审查。 | `X`, `CS/AI` | Agent skill 宿主（见上游） | Not detected† |
| [research-paper](https://github.com/aniketkrs/research-paper) **New** | 支持论文起草、批评性检查和投稿准备。 | `X`, `CS/AI` | 兼容 SKILL.md 的宿主 | MIT |

## 文风与表达支持——辅助工具，而非科研证据系统

这些工具可改善草稿的清晰度或文风，但**不能**验证方法、数据、新颖性、引文或事实性论断。作者仍须承担核验责任。

| 名称 | 它能做什么 | 适配学科 | 宿主 / 平台 | 许可证 |
| --- | --- | --- | --- | --- |
| [academic-humanizer](https://github.com/AIScientists-Dev/academic-humanizer) | 用于论文和基金文本的后期文风调整。 | `X`, `H/L` | Agent skill 宿主（见上游） | Not detected† |
| [humanizer](https://github.com/blader/humanizer) | 清除通用文本中常见的 AI 行文模式。 | `X`, `H/L` | Agent skill 宿主（见上游） | MIT |
| [stop-slop](https://github.com/hardikpandya/stop-slop) | 针对填充语、行话和重复模式的英文后期编辑。 | `X`, `H/L` | Agent skill 宿主（见上游） | MIT |
| [no-ai-slop](https://github.com/petergyang/no-ai-slop) | 修改重复的 AI 写作模式，并尽量保留作者声音。 | `X`, `H/L` | Agent skill 宿主（见上游） | MIT |
| [shuorenhua](https://github.com/MrGeDiao/shuorenhua) | 强调事实保留的中文自然化改写。 | `X`, `H/L` | 中文写作 Agent 宿主 | MIT |
| [qu-ai-wei](https://github.com/LifelongLazyLearner/qu-ai-wei) | 改善简体中文模板化措辞和句子流畅度。 | `X`, `H/L` | 中文写作 Agent 宿主 | MIT |
| [De-AI-Prompt-Enhancer-Writer-Booster-SKILL](https://github.com/OUBIGFA/De-AI-Prompt-Enhancer-Writer-Booster-SKILL) | 去 AI 化编辑和基于风格参考的写作辅助。 | `X`, `H/L` | Agent skill 宿主（见上游） | Not detected† |
| [writing-agent](https://github.com/dongbeixiaohuo/writing-agent) | 包含起草、读者测试、审查和格式化的中文写作流程。 | `X`, `H/L` | Claude Code | MIT |

## 交付与科研格式——辅助工具

| 名称 | 它能做什么 | 适配学科 | 宿主 / 平台 | 许可证 |
| --- | --- | --- | --- | --- |
| [Anthropic 文档 Skills（PDF / PPTX / XLSX）](https://github.com/anthropics/skills/tree/main/skills/pdf) **New** | 生成、读取和质检常见科研交付格式；请遵循各 skill 的条款。 | `X` | Claude Code / Claude API | Mixed terms† |

## 框架、目录与领域集合——辅助 / 工具层

这些项目是发现入口或更宽泛的框架，而不是一个单独的学术 skill。请把其内部 skill 当作独立的上游制品，并分别阅读文档和条款。

| 名称 | 它能做什么 | 适配学科 | 宿主 / 平台 | 许可证 |
| --- | --- | --- | --- | --- |
| [medical-research-skills](https://github.com/aipoch/medical-research-skills) | 医学研究工作流的领域集合。 | `LS/M` | Agent skill 宿主（见上游） | MIT |
| [deer-flow](https://github.com/bytedance/deer-flow) | 含文献综述能力的通用研究 Agent 框架。 | `X`, `CS/AI` | DeerFlow 框架 / Web 技术栈 | MIT |
| [academic-research-skills](https://github.com/franklee16/academic-research-skills) **New** | 面向经济、金融和社科的写作、分析、可视化与审查 skills。 | `SS/E`, `X` | Claude Code | Per-skill†；根目录未检测到许可证 |
| [OpenAI Skills](https://github.com/openai/skills) **New** | 官方 Codex skill 目录及可复用 Agent 能力示例。 | `X` | Codex | Not detected† |

## 安装指引

本列表不存在安全、通用的一键安装命令。请对每个候选项目执行以下步骤：

1. 打开上游仓库，阅读其 `README`、`SKILL.md`、安装步骤、许可证和工具/API 要求。
2. 按你的宿主（例如 Codex、Claude Code、Cursor 或 MCP 客户端）遵循上游指引，只安装实际需要的 skill 或集成。
3. 在授予文件系统、网络、浏览器、凭据或云数据权限前，审阅脚本和权限请求。
4. 对任何本地副本保留上游 URL、版本/提交和许可证，便于审计和后续更新。

对于 Codex 类 skill，上游文档通常会说明目标 skill 目录和必要配置。除非已审查条款、依赖和权限，不要将整个目录批量复制进共享环境。

## 安全与科研诚信

- 将第三方 skill 视为可执行指令：使用前检查提示词、脚本、依赖和数据流。
- 不要向未审查的工具暴露未发表稿件、审稿意见、受试者数据、患者数据、专有代码、API 密钥或机构凭据。
- 逐条用一手来源和自己的原始记录核验引文、引用、结果、统计、图表和方法。引文 skill 能帮助检索，不能自动证明事实。
- 不要利用 skill 伪造证据、隐瞒局限、规避会议期刊规则、冒充同行评审或误导 AI 辅助使用情况。请遵守期刊、资助方、机构和数据集政策。
- 科学论断、实验设计、作者署名和投稿决定必须保留人工签核。

## 收录标准

一个条目应有公开仓库，以及可复用且有文档说明的工作流、skill、Agent 能力、工具集成或科研格式工具。我们更倾向于清晰说明范围、宿主兼容性、权限、溯源、评测和许可证的项目。

本列表不把星标数量当作质量分数，不把上游 skill 文本复制进索引，也不会因为一条通用提示词提到“研究”就收录它。辅助工具会被明确标注，而不会被包装成证据系统或同行评审系统。

## 参与贡献

提交 issue 或 pull request 前，请阅读 [CONTRIBUTING.md](CONTRIBUTING.md)。高质量提交应包含准确的上游 URL、一句可核验的能力说明、主要工作流类别、适配学科、支持的宿主和许可证状态。请避免宣传性措辞，并披露缺失或不清晰的许可证信息。

## 本索引的许可证

本索引自身采用 [CC0-1.0](LICENSE) 发布。每一个外链项目仍受其自身许可证、条款和署名要求约束。
